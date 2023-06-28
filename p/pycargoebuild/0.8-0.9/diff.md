# Comparing `tmp/pycargoebuild-0.8.tar.gz` & `tmp/pycargoebuild-0.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pycargoebuild-0.8.tar", last modified: Fri Jan  1 00:00:00 2016, max compression
+gzip compressed data, was "pycargoebuild-0.9.tar", last modified: Fri Jan  1 00:00:00 2016, max compression
```

## Comparing `pycargoebuild-0.8.tar` & `pycargoebuild-0.9.tar`

### file list

```diff
@@ -1,11 +1,11 @@
--rw-r--r--   0        0        0     1081 2022-11-09 09:31:36.847189 pycargoebuild-0.8/LICENSE
--rw-r--r--   0        0        0     2304 2022-12-11 16:55:26.062005 pycargoebuild-0.8/README.rst
--rw-r--r--   0        0        0       80 2023-06-27 14:55:13.160950 pycargoebuild-0.8/pycargoebuild/__init__.py
--rw-r--r--   0        0        0     8537 2023-06-27 14:22:16.094695 pycargoebuild-0.8/pycargoebuild/__main__.py
--rw-r--r--   0        0        0     6157 2023-06-27 13:32:53.404842 pycargoebuild-0.8/pycargoebuild/cargo.py
--rw-r--r--   0        0        0     8866 2023-06-27 14:54:19.329899 pycargoebuild-0.8/pycargoebuild/ebuild.py
--rw-r--r--   0        0        0     2572 2023-06-26 17:49:46.447413 pycargoebuild-0.8/pycargoebuild/fetch.py
--rw-r--r--   0        0        0     4645 2022-11-25 16:23:06.667384 pycargoebuild-0.8/pycargoebuild/format.py
--rw-r--r--   0        0        0     3541 2022-11-22 19:20:48.996065 pycargoebuild-0.8/pycargoebuild/license.py
--rw-r--r--   0        0        0     1126 2023-06-27 14:09:19.035713 pycargoebuild-0.8/pyproject.toml
--rw-r--r--   0        0        0     2868 1970-01-01 00:00:00.000000 pycargoebuild-0.8/PKG-INFO
+-rw-r--r--   0        0        0     1081 2022-11-09 09:31:36.847189 pycargoebuild-0.9/LICENSE
+-rw-r--r--   0        0        0     2304 2023-06-28 09:50:44.460609 pycargoebuild-0.9/README.rst
+-rw-r--r--   0        0        0       80 2023-06-28 09:50:21.343250 pycargoebuild-0.9/pycargoebuild/__init__.py
+-rw-r--r--   0        0        0     9382 2023-06-28 09:50:44.460609 pycargoebuild-0.9/pycargoebuild/__main__.py
+-rw-r--r--   0        0        0     7265 2023-06-27 19:45:01.461160 pycargoebuild-0.9/pycargoebuild/cargo.py
+-rw-r--r--   0        0        0     8929 2023-06-28 07:14:17.188842 pycargoebuild-0.9/pycargoebuild/ebuild.py
+-rw-r--r--   0        0        0     2572 2023-06-26 17:49:46.447413 pycargoebuild-0.9/pycargoebuild/fetch.py
+-rw-r--r--   0        0        0     4645 2022-11-25 16:23:06.667384 pycargoebuild-0.9/pycargoebuild/format.py
+-rw-r--r--   0        0        0     3733 2023-06-28 07:19:11.465415 pycargoebuild-0.9/pycargoebuild/license.py
+-rw-r--r--   0        0        0     1126 2023-06-27 14:09:19.035713 pycargoebuild-0.9/pyproject.toml
+-rw-r--r--   0        0        0     2868 1970-01-01 00:00:00.000000 pycargoebuild-0.9/PKG-INFO
```

### Comparing `pycargoebuild-0.8/LICENSE` & `pycargoebuild-0.9/LICENSE`

 * *Files identical despite different names*

### Comparing `pycargoebuild-0.8/README.rst` & `pycargoebuild-0.9/README.rst`

 * *Files identical despite different names*

### Comparing `pycargoebuild-0.8/pycargoebuild/__main__.py` & `pycargoebuild-0.9/pycargoebuild/__main__.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,29 +1,38 @@
 import argparse
-import io
 import logging
 import os.path
 import shutil
 import sys
 import tempfile
 import typing
 
 from pathlib import Path
 
+if sys.version_info >= (3, 11):
+    import tomllib
+else:
+    import tomli as tomllib
+
 from pycargoebuild.cargo import Crate, get_crates, get_package_metadata
 from pycargoebuild.ebuild import get_ebuild, update_ebuild
 from pycargoebuild.fetch import (fetch_crates_using_wget,
                                  fetch_crates_using_aria2,
                                  verify_crates)
 from pycargoebuild.license import load_license_mapping
 
 
 FETCHERS = ("aria2", "wget")
 
 
+class WorkspaceData(typing.NamedTuple):
+    crates: typing.FrozenSet[Crate]
+    workspace_metadata: dict
+
+
 def main(prog_name: str, *argv: str) -> int:
     argp = argparse.ArgumentParser(prog=os.path.basename(prog_name))
     argp.add_argument("-d", "--distdir",
                       type=Path,
                       help="Directory to store downloaded crates in "
                            "(default: get from Portage)")
     argp.add_argument("-f", "--force",
@@ -75,19 +84,31 @@
     def iterate_parents(directory: Path) -> typing.Generator[Path, None, None]:
         root = directory.absolute().root
         yield directory
         while not directory.samefile(root):
             directory /= ".."
             yield directory
 
-    def get_cargo_lock_file(directory: Path) -> io.BufferedReader:
+    def get_workspace_root(directory: Path) -> WorkspaceData:
         err: typing.Optional[Exception] = None
         for directory in iterate_parents(directory):
             try:
-                return open(directory / "Cargo.lock", "rb")
+                with open(directory / "Cargo.lock", "rb") as cargo_lock:
+                    try:
+                        with open(directory / "Cargo.toml",
+                                  "rb") as cargo_toml:
+                            workspace_toml = (
+                                tomllib.load(cargo_toml).get("workspace", {})
+                                                        .get("package", {}))
+                    except FileNotFoundError:
+                        workspace_toml = {}
+
+                    return WorkspaceData(
+                        crates=frozenset(get_crates(cargo_lock)),
+                        workspace_metadata=workspace_toml)
             except FileNotFoundError as e:
                 if err is None:
                     err = e
         raise RuntimeError(
             "Cargo.lock not found in any of the parent directories") from err
 
     def try_fetcher(name: str,
@@ -114,17 +135,18 @@
                     f"{', '.join(FETCHERS)})")
             assert False, f"Unexpected args.fetcher={args.fetcher}"
 
     crates: typing.Set[Crate] = set()
     pkg_metas = []
     for directory in args.directory:
         with open(directory / "Cargo.toml", "rb") as f:
-            pkg_metas.append(get_package_metadata(f))
-        with get_cargo_lock_file(directory) as f:
-            crates.update(get_crates(f))
+            workspace = get_workspace_root(directory)
+            crates.update(workspace.crates)
+            pkg_metas.append(
+                get_package_metadata(f, workspace.workspace_metadata))
     pkg_meta = pkg_metas[0]
 
     if args.no_license:
         pkg_meta = pkg_meta.with_replaced_license(None)
     elif len(args.directory) > 1:
         # Combine licenses of multiple packages
         combined_license = " AND ".join(f"( {pkg.license} )"
```

### Comparing `pycargoebuild-0.8/pycargoebuild/cargo.py` & `pycargoebuild-0.9/pycargoebuild/cargo.py`

 * *Files 13% similar despite different names*

```diff
@@ -70,15 +70,18 @@
                     f = crate_tar.extractfile(tar_info)
                     if f is None:
                         continue
 
                     # tarfile.ExFileObject() is IO[bytes] while tomli/tomllib
                     # expects BinaryIO -- but it actually is compatible
                     # https://github.com/hukkin/tomli/issues/214
-                    metadata = get_package_metadata(f)  # type: ignore
+                    try:
+                        metadata = get_package_metadata(f)  # type: ignore
+                    except WorkspaceCargoTomlError:
+                        continue
                     if (metadata.name == self.name and
                             metadata.version == self.version):
                         return path.parent
 
         raise RuntimeError(f"Package {self.name} not found in crate "
                            f"{distdir / self.filename}")
 
@@ -102,14 +105,19 @@
                                version=self.version,
                                license=new_license,
                                license_file=None,
                                description=self.description,
                                homepage=self.homepage)
 
 
+class WorkspaceCargoTomlError(RuntimeError):
+    """Cargo.toml belongs to a workspace root"""
+    pass
+
+
 def cargo_to_spdx(license_str: str) -> str:
     """
     Convert deprecated Cargo license string to SPDX-2.0, if necessary.
     """
     return license_str.replace("/", " OR ")
 
 
@@ -149,28 +157,51 @@
             else:
                 raise RuntimeError(f"Unsupported crate source: {p['source']}")
         except KeyError as e:
             raise RuntimeError("Incorrect/insufficient metadata for crate: "
                                f"{p!r}") from e
 
 
-def get_package_metadata(f: typing.BinaryIO) -> PackageMetadata:
+def get_meta_key(key: str, pkg_meta: dict,
+                 workspace_pkg_meta: dict) -> typing.Optional[str]:
+    """Get a key from package metadata respecting ``workspace: true``"""
+    value = pkg_meta.get(key)
+
+    if isinstance(value, str) or value is None:
+        return value
+    if isinstance(value, dict) and value.get("workspace") is True:
+        return get_meta_key(key, workspace_pkg_meta, {})
+    raise ValueError(f"Invalid metadata key value: {key!r}={value!r}")
+
+
+def get_package_metadata(f: typing.BinaryIO,
+                         workspace_pkg_meta: dict = {},
+                         ) -> PackageMetadata:
     """Read package from the open ``Cargo.toml`` file"""
     cargo_toml = tomllib.load(f)
 
     if "package" not in cargo_toml and "workspace" in cargo_toml:
-        raise RuntimeError(
+        raise WorkspaceCargoTomlError(
             "Specified directory seems to be a workspace root, please run "
             "pycargoebuild on one of its members instead: "
             f"{' '.join(cargo_toml['workspace']['members'])}")
 
     pkg_meta = cargo_toml["package"]
-    pkg_license = pkg_meta.get("license")
+    _get_meta_key = functools.partial(get_meta_key,
+                                      pkg_meta=pkg_meta,
+                                      workspace_pkg_meta=workspace_pkg_meta)
+
+    pkg_license = _get_meta_key("license")
     if pkg_license is not None:
         pkg_license = cargo_to_spdx(pkg_license)
+
+    pkg_version = _get_meta_key("version")
+    if pkg_version is None:
+        raise ValueError(f"No version found in {f.name}")
+
     return PackageMetadata(
         name=pkg_meta["name"],
-        version=pkg_meta["version"],
+        version=pkg_version,
         license=pkg_license,
-        license_file=pkg_meta.get("license-file"),
-        description=pkg_meta.get("description"),
-        homepage=pkg_meta.get("homepage"))
+        license_file=_get_meta_key("license-file"),
+        description=_get_meta_key("description"),
+        homepage=_get_meta_key("homepage"))
```

### Comparing `pycargoebuild-0.8/pycargoebuild/ebuild.py` & `pycargoebuild-0.9/pycargoebuild/ebuild.py`

 * *Files 2% similar despite different names*

```diff
@@ -100,33 +100,34 @@
                            distdir: Path,
                            ) -> typing.Optional[str]:
     """
     Read the metadata from specified crate and return its license string
     """
 
     filename = crate.filename
+    base_dir = crate.get_package_directory(distdir)
     with tarfile.open(distdir / filename, "r:gz") as crate_tar:
-        tarf = crate_tar.extractfile(
-            str(crate.get_package_directory(distdir) / "Cargo.toml"))
+        tarf = crate_tar.extractfile(str(base_dir / "Cargo.toml"))
         if tarf is None:
             raise RuntimeError(f"Cargo.toml not found in {filename}")
         with tarf:
             # tarfile.ExFileObject() is IO[bytes] while tomli/tomllib
             # expects BinaryIO -- but it actually is compatible
             # https://github.com/hukkin/tomli/issues/214
             crate_metadata = get_package_metadata(tarf)  # type: ignore
             if crate_metadata.license_file is not None:
                 logging.warning(
-                    f"Crate {filename} uses license-file="
+                    f"Crate {filename} (in {base_dir}) uses license-file="
                     f"{crate_metadata.license_file!r}, please inspect "
                     "the license manually and add it *separately* from crate "
                     "licenses")
             elif crate_metadata.license is None:
-                raise RuntimeError(
-                    f"Crate {filename} does not specify a license!")
+                logging.warning(
+                    f"Crate {filename} (in {base_dir}) does not specify "
+                    "a license!")
             return crate_metadata.license
 
 
 def get_crate_LICENSE(crates: typing.Iterable[Crate],
                       distdir: Path,
                       ) -> str:
     """
```

### Comparing `pycargoebuild-0.8/pycargoebuild/fetch.py` & `pycargoebuild-0.9/pycargoebuild/fetch.py`

 * *Files identical despite different names*

### Comparing `pycargoebuild-0.8/pycargoebuild/format.py` & `pycargoebuild-0.9/pycargoebuild/format.py`

 * *Files identical despite different names*

### Comparing `pycargoebuild-0.8/pycargoebuild/license.py` & `pycargoebuild-0.9/pycargoebuild/license.py`

 * *Files 3% similar despite different names*

```diff
@@ -16,14 +16,19 @@
                                      interpolation=None)
     conf.read_file(f)
     MAPPING.update((k.lower(), v) for k, v in conf.items("spdx-to-ebuild"))
 
 
 def symbol_to_ebuild(license_symbol: license_expression.LicenseSymbol) -> str:
     full_key = str(license_symbol).lower()
+    if full_key.startswith("licenseref-"):
+        logging.warning(
+            f"User defined license found: {str(license_symbol)!r}, mapping "
+            "not possible.")
+        return ""
     no_plus = full_key.replace("+", "")
     # if we do not have an exact match, check if it is a "+" expression
     # and try a match without the "+" symbol
     if full_key not in MAPPING and no_plus in MAPPING:
         logging.warning(
             f"No explicit entry for license {license_symbol} found, "
             f"assuming {str(license_symbol).replace('+', '')}.")
```

### Comparing `pycargoebuild-0.8/pyproject.toml` & `pycargoebuild-0.9/pyproject.toml`

 * *Files identical despite different names*

### Comparing `pycargoebuild-0.8/PKG-INFO` & `pycargoebuild-0.9/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pycargoebuild
-Version: 0.8
+Version: 0.9
 Summary: A generator for Rust/Cargo ebuilds written in Python
 Author-email: Michał Górny <mgorny@gentoo.org>
 Requires-Python: >=3.9
 Description-Content-Type: text/x-rst
 Classifier: License :: OSI Approved :: MIT License
 Requires-Dist: license_expression
 Requires-Dist: tomli >= 1.2.3; python_version < '3.11'
```


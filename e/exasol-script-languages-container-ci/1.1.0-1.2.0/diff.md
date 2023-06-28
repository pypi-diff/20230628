# Comparing `tmp/exasol_script_languages_container_ci-1.1.0.tar.gz` & `tmp/exasol_script_languages_container_ci-1.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "exasol_script_languages_container_ci-1.1.0.tar", max compression
+gzip compressed data, was "exasol_script_languages_container_ci-1.2.0.tar", max compression
```

## Comparing `exasol_script_languages_container_ci-1.1.0.tar` & `exasol_script_languages_container_ci-1.2.0.tar`

### file list

```diff
@@ -1,24 +1,25 @@
--rw-r--r--   0        0        0     1063 2023-05-16 07:14:42.008871 exasol_script_languages_container_ci-1.1.0/LICENSE
--rw-r--r--   0        0        0       95 2023-05-16 07:14:42.008871 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/__init__.py
--rw-r--r--   0        0        0        0 2023-05-16 07:14:42.008871 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/cli/__init__.py
--rw-r--r--   0        0        0       50 2023-05-16 07:14:42.008871 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/cli/cli.py
--rw-r--r--   0        0        0        0 2023-05-16 07:14:42.008871 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/cli/commands/__init__.py
--rw-r--r--   0        0        0     1658 2023-05-16 07:14:42.008871 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/cli/commands/run_ci.py
--rw-r--r--   0        0        0     2566 2023-05-16 07:14:42.008871 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/cli/commands/run_release.py
--rw-r--r--   0        0        0        0 2023-05-16 07:14:42.008871 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/__init__.py
--rw-r--r--   0        0        0     1304 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/asset_uploader.py
--rw-r--r--   0        0        0     1677 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/branch_config.py
--rw-r--r--   0        0        0     4992 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/ci.py
--rw-r--r--   0        0        0     2595 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/ci_build.py
--rw-r--r--   0        0        0      806 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/ci_export.py
--rw-r--r--   0        0        0      978 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/ci_push.py
--rw-r--r--   0        0        0     1104 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/ci_security_scan.py
--rw-r--r--   0        0        0     1693 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/ci_test.py
--rw-r--r--   0        0        0     1150 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/common.py
--rw-r--r--   0        0        0     1501 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/git_access.py
--rw-r--r--   0        0        0     1223 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/github_release_asset_uploader.py
--rw-r--r--   0        0        0     2786 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/release.py
--rw-r--r--   0        0        0     2443 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/release_uploader.py
--rwxr-xr-x   0        0        0      125 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/main.py
--rw-r--r--   0        0        0      785 2023-05-16 07:14:42.012872 exasol_script_languages_container_ci-1.1.0/pyproject.toml
--rw-r--r--   0        0        0      862 1970-01-01 00:00:00.000000 exasol_script_languages_container_ci-1.1.0/PKG-INFO
+-rw-r--r--   0        0        0     1063 2023-06-28 11:15:33.086414 exasol_script_languages_container_ci-1.2.0/LICENSE
+-rw-r--r--   0        0        0       95 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/cli/__init__.py
+-rw-r--r--   0        0        0       50 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/cli/cli.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/cli/commands/__init__.py
+-rw-r--r--   0        0        0     1658 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/cli/commands/run_ci.py
+-rw-r--r--   0        0        0     2566 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/cli/commands/run_release.py
+-rw-r--r--   0        0        0        0 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/__init__.py
+-rw-r--r--   0        0        0     1304 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/asset_uploader.py
+-rw-r--r--   0        0        0     1677 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/branch_config.py
+-rw-r--r--   0        0        0     4992 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/ci.py
+-rw-r--r--   0        0        0     2674 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/ci_build.py
+-rw-r--r--   0        0        0      944 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/ci_export.py
+-rw-r--r--   0        0        0     1157 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/ci_push.py
+-rw-r--r--   0        0        0     1071 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/ci_security_scan.py
+-rw-r--r--   0        0        0     1309 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/ci_step_output_printer.py
+-rw-r--r--   0        0        0     4816 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/ci_test.py
+-rw-r--r--   0        0        0      334 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/common.py
+-rw-r--r--   0        0        0     1501 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/git_access.py
+-rw-r--r--   0        0        0     1223 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/github_release_asset_uploader.py
+-rw-r--r--   0        0        0     2786 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/release.py
+-rw-r--r--   0        0        0     2443 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/release_uploader.py
+-rwxr-xr-x   0        0        0      125 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/main.py
+-rw-r--r--   0        0        0      785 2023-06-28 11:15:33.090414 exasol_script_languages_container_ci-1.2.0/pyproject.toml
+-rw-r--r--   0        0        0      862 1970-01-01 00:00:00.000000 exasol_script_languages_container_ci-1.2.0/PKG-INFO
```

### Comparing `exasol_script_languages_container_ci-1.1.0/LICENSE` & `exasol_script_languages_container_ci-1.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/cli/commands/run_ci.py` & `exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/cli/commands/run_ci.py`

 * *Files identical despite different names*

### Comparing `exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/cli/commands/run_release.py` & `exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/cli/commands/run_release.py`

 * *Files identical despite different names*

### Comparing `exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/asset_uploader.py` & `exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/asset_uploader.py`

 * *Files identical despite different names*

### Comparing `exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/branch_config.py` & `exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/branch_config.py`

 * *Files identical despite different names*

### Comparing `exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/ci.py` & `exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/ci.py`

 * *Files identical despite different names*

### Comparing `exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/ci_build.py` & `exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/ci_build.py`

 * *Files 12% similar despite different names*

```diff
@@ -2,26 +2,31 @@
 from typing import Tuple, Dict, Optional
 
 from exasol_integration_test_docker_environment.lib.api.build_test_container import build_test_container
 from exasol_integration_test_docker_environment.lib.docker.images.image_info import ImageInfo
 from exasol_script_languages_container_tool.lib.api import build
 from exasol_script_languages_container_tool.lib.tasks.test.test_container_content import build_test_container_content
 
-from exasol_script_languages_container_ci.lib.common import print_docker_images
+from exasol_script_languages_container_ci.lib.ci_step_output_printer import CIStepOutputPrinterProtocol, \
+    CIStepOutputPrinter
 
 
 class CIBuild:
+
+    def __init__(self, printer: CIStepOutputPrinterProtocol = CIStepOutputPrinter(logging.info)):
+        self._printer = printer
+
     def build(self,
               flavor_path: Tuple[str, ...],
               rebuild: bool,
               build_docker_repository: Optional[str],
               commit_sha: str,
               docker_user: str,
               docker_password: str,
-              test_container_folder: str) -> Tuple[Dict[str, Dict[str, ImageInfo]], ImageInfo]:
+              test_container_folder: str):
         """
         Build the script-language container for given flavor. And also build the test container
         """
 
         logging.info(f"Running command 'build' with parameters: {locals()}")
         if build_docker_repository is None:
             slc_image_infos = build(flavor_path=flavor_path, force_rebuild=rebuild,
@@ -43,9 +48,8 @@
         test_container_image_infos = build_test_container(
             force_rebuild=rebuild,
             workers=7,
             test_container_content=content,
             source_docker_repository_name=build_docker_repository,
             source_docker_tag_prefix=commit_sha
         )
-        print_docker_images(logging.info)
-        return slc_image_infos, test_container_image_infos
+        self._printer.print_exasol_docker_images()
```

### Comparing `exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/ci_export.py` & `exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/ci_export.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,23 +1,27 @@
 import logging
 from typing import Tuple
 
 from exasol_script_languages_container_tool.lib.api import export
 from exasol_script_languages_container_tool.lib.tasks.export.export_containers import ExportContainerResult
 
-from exasol_script_languages_container_ci.lib.common import print_docker_images
+from exasol_script_languages_container_ci.lib.ci_step_output_printer import CIStepOutputPrinterProtocol, \
+    CIStepOutputPrinter
 
 
 class CIExport:
+
+    def __init__(self, printer: CIStepOutputPrinterProtocol = CIStepOutputPrinter(logging.info)):
+        self._printer = printer
+
     def export(self,
                flavor_path: Tuple[str, ...],
-               export_path: str) -> ExportContainerResult:
+               export_path: str):
         """
         Export the flavor as tar.gz file
         """
 
         logging.info(f"Running command 'push' with parameters: {locals()}")
         export_result = export(flavor_path=flavor_path,
                                export_path=export_path,
                                workers=7)
-        print_docker_images(logging.info)
-        return export_result
+        self._printer.print_exasol_docker_images()
```

### Comparing `exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/ci_push.py` & `exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/ci_push.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,17 +1,21 @@
 import logging
 from typing import Tuple
 
-import click
 from exasol_script_languages_container_tool.lib.api.push import push
 
-from exasol_script_languages_container_ci.lib.common import print_docker_images
+from exasol_script_languages_container_ci.lib.ci_step_output_printer import CIStepOutputPrinterProtocol, \
+    CIStepOutputPrinter
 
 
 class CIPush:
+
+    def __init__(self, printer: CIStepOutputPrinterProtocol = CIStepOutputPrinter(logging.info)):
+        self._printer = printer
+
     def push(self,
              flavor_path: Tuple[str, ...],
              target_docker_repository: str,
              target_docker_tag_prefix: str,
              docker_user: str,
              docker_password: str):
         """
@@ -23,8 +27,8 @@
              push_all=True,
              force_push=True,
              workers=7,
              target_docker_repository_name=target_docker_repository,
              target_docker_tag_prefix=target_docker_tag_prefix,
              target_docker_username=docker_user,
              target_docker_password=docker_password)
-        print_docker_images(logging.info)
+        self._printer.print_exasol_docker_images()
```

### Comparing `exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/ci_security_scan.py` & `exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/ci_security_scan.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,25 +1,28 @@
 import logging
 from pathlib import Path
-from typing import Tuple
+from typing import Tuple, Callable
 
 from exasol_script_languages_container_tool.lib.api import security_scan
-from exasol_script_languages_container_tool.lib.tasks.security_scan.security_scan import AllScanResult
 
-import exasol_script_languages_container_ci.lib.common
+from exasol_script_languages_container_ci.lib.ci_step_output_printer import CIStepOutputPrinterProtocol, \
+    CIStepOutputPrinter
 
 
 class CISecurityScan:
 
-    def run_security_scan(self, flavor_path: Tuple[str, ...]) -> AllScanResult:
+    def __init__(self, printer: CIStepOutputPrinterProtocol = CIStepOutputPrinter(logging.info)):
+        self._printer = printer
+
+    def run_security_scan(self,
+                          flavor_path: Tuple[str, ...]):
         """
         Run security scan and print result
         """
 
         logging.info(f"Running command 'security_scan' with parameters {locals()}")
         security_scan_result = security_scan(flavor_path=flavor_path, workers=7)
-        exasol_script_languages_container_ci.lib.common.print_docker_images(logging.info)
         logging.info("============= SECURITY REPORT ===========")
-        # Important: Call print_file over the global module name, otherwise the patch in the unit-test does not work!
-        exasol_script_languages_container_ci.lib.common.print_file(
-            Path() / ".build_output" / "security_scan" / "security_report", logging.info)
-        return security_scan_result
+        self._printer.print_file(Path(security_scan_result.report_path))
+        self._printer.print_exasol_docker_images()
+        if not security_scan_result.scans_are_ok:
+            raise AssertionError("Some security scans not successful.")
```

### Comparing `exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/common.py` & `exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/ci_step_output_printer.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,49 +1,51 @@
-import json
-from contextlib import contextmanager
-from pathlib import Path
-from typing import Callable
 from inspect import cleandoc
+from pathlib import Path
+from typing import Callable, Protocol
 
 import docker
 
 
-def _get_docker_images():
+class CIStepOutputPrinterProtocol(Protocol):
+
+    def print_exasol_docker_images(self):
+        raise NotImplementedError()
+
+    def print_file(self, filename: Path):
+        raise NotImplementedError()
+
+
+def _get_exasol_docker_images():
     docker_client = docker.from_env()
-    exa_images = []
     try:
         exa_images = [str(img) for img in docker_client.images.list() if "exasol" in str(img)]
+        return exa_images
     finally:
         docker_client.close()
-    return exa_images
+        return []
+
+
+class CIStepOutputPrinter(CIStepOutputPrinterProtocol):
 
+    def __init__(self, writer: Callable[[str], None]):
+        self._writer = writer
 
-def print_docker_images(writer: Callable[[str], None]):
-    """
-    Prints all docker images whith "exa" in it's name to stdout.
-    :return: None
-    """
-
-    writer(cleandoc("""
-        {seperator}
-        Printing docker images
-        {seperator}
-        {images}""").format(
-        seperator=20 * "=", images="\n".join(_get_docker_images())
-    ))
-
-
-def print_file(filename: Path, writer: Callable[[str], None]):
-    """
-    Opens file readonly, reads it content and prints to writer.
-    """
-    with open(filename, "r") as f:
-        writer(f.read())
-
-
-@contextmanager
-def get_config(config_file: str):
-    """
-    Opens config file and returns parsed JSON object.
-    """
-    with open(config_file, "r") as f:
-        yield json.load(f)
+    def print_exasol_docker_images(self):
+        """
+        Prints all docker images with "exasol" in it's name to stdout.
+        :return: None
+        """
+
+        self._writer(cleandoc("""
+            {seperator}
+            Printing docker images
+            {seperator}
+            {images}""").format(
+            seperator=20 * "=", images="\n".join(_get_exasol_docker_images())
+        ))
+
+    def print_file(self, filename: Path):
+        """
+        Print the file's content to the writer.
+        """
+        with open(filename, "r") as f:
+            self._writer(f.read())
```

### Comparing `exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/git_access.py` & `exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/git_access.py`

 * *Files identical despite different names*

### Comparing `exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/github_release_asset_uploader.py` & `exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/github_release_asset_uploader.py`

 * *Files identical despite different names*

### Comparing `exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/release.py` & `exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/release.py`

 * *Files identical despite different names*

### Comparing `exasol_script_languages_container_ci-1.1.0/exasol_script_languages_container_ci/lib/release_uploader.py` & `exasol_script_languages_container_ci-1.2.0/exasol_script_languages_container_ci/lib/release_uploader.py`

 * *Files identical despite different names*

### Comparing `exasol_script_languages_container_ci-1.1.0/pyproject.toml` & `exasol_script_languages_container_ci-1.2.0/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -1,24 +1,24 @@
 [tool.poetry]
 name = "exasol-script-languages-container-ci"
-version = "1.1.0"
+version = "1.2.0"
 description = "Implements CI builds for script-language-container."
 
 license = "MIT"
 
 authors = [
     "Thomas Uebensee <ext.thomas.uebensee@exasol.com>"
 ]
 
 [tool.poetry.dependencies]
 python = ">=3.8.0,<4.0"
 click = "^8.0.3"
 GitPython = ">=3.1.0"
-exasol-script-languages-container-tool = "^0.17.0"
-exasol-integration-test-docker-environment = "^1.4.0"
+exasol-script-languages-container-tool = "^0.18.0"
+exasol-integration-test-docker-environment = "^1.7.1"
 PyGithub = "^1.55.0"
 setuptools = "^67.6.0"
 
 [build-system]
 requires = ["poetry_core>=1.0.0"]
 build-backend = "poetry.core.masonry.api"
```

### Comparing `exasol_script_languages_container_ci-1.1.0/PKG-INFO` & `exasol_script_languages_container_ci-1.2.0/PKG-INFO`

 * *Files 23% similar despite different names*

```diff
@@ -1,20 +1,20 @@
 Metadata-Version: 2.1
 Name: exasol-script-languages-container-ci
-Version: 1.1.0
+Version: 1.2.0
 Summary: Implements CI builds for script-language-container.
 License: MIT
 Author: Thomas Uebensee
 Author-email: ext.thomas.uebensee@exasol.com
 Requires-Python: >=3.8.0,<4.0
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Requires-Dist: GitPython (>=3.1.0)
 Requires-Dist: PyGithub (>=1.55.0,<2.0.0)
 Requires-Dist: click (>=8.0.3,<9.0.0)
-Requires-Dist: exasol-integration-test-docker-environment (>=1.4.0,<2.0.0)
-Requires-Dist: exasol-script-languages-container-tool (>=0.17.0,<0.18.0)
+Requires-Dist: exasol-integration-test-docker-environment (>=1.7.1,<2.0.0)
+Requires-Dist: exasol-script-languages-container-tool (>=0.18.0,<0.19.0)
 Requires-Dist: setuptools (>=67.6.0,<68.0.0)
```


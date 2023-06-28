# Comparing `tmp/windows_control-0.0.5.tar.gz` & `tmp/windows_control-0.0.6.tar.gz`

## Comparing `windows_control-0.0.5.tar` & `windows_control-0.0.6.tar`

### file list

```diff
@@ -1,12 +1,12 @@
--rw-r--r--   0        0        0      488 1970-01-01 00:00:00.000000 windows_control-0.0.5/Cargo.toml
--rw-r--r--   0        0        0     2807 2023-06-28 03:33:37.000000 windows_control-0.0.5/.github/workflows/CI.yml
--rw-r--r--   0        0        0      756 2023-06-28 03:33:37.000000 windows_control-0.0.5/.gitignore
--rw-r--r--   0        0        0     2298 2023-06-28 08:54:02.000000 windows_control-0.0.5/README.md
--rw-r--r--   0        0        0      486 2023-06-28 08:53:52.000000 windows_control-0.0.5/README.rst
--rw-r--r--   0        0        0      403 2023-06-28 08:34:41.000000 windows_control-0.0.5/justfile
--rw-r--r--   0        0        0      817 2023-06-28 08:54:11.000000 windows_control-0.0.5/pyproject.toml
--rw-r--r--   0        0        0       90 2023-06-28 05:39:06.000000 windows_control-0.0.5/src/keyboard/mod.rs
--rw-r--r--   0        0        0     1201 2023-06-28 05:51:30.000000 windows_control-0.0.5/src/lib.rs
--rw-r--r--   0        0        0      508 2023-06-28 05:39:46.000000 windows_control-0.0.5/test.py
--rw-r--r--   0        0        0     7435 2023-06-28 06:00:28.000000 windows_control-0.0.5/Cargo.lock
--rw-r--r--   0        0        0      966 1970-01-01 00:00:00.000000 windows_control-0.0.5/PKG-INFO
+-rw-r--r--   0        0        0      488 1970-01-01 00:00:00.000000 windows_control-0.0.6/Cargo.toml
+-rw-r--r--   0        0        0     2807 2023-06-28 03:33:37.000000 windows_control-0.0.6/.github/workflows/CI.yml
+-rw-r--r--   0        0        0      756 2023-06-28 03:33:37.000000 windows_control-0.0.6/.gitignore
+-rw-r--r--   0        0        0     2450 2023-06-28 09:04:22.000000 windows_control-0.0.6/README.md
+-rw-r--r--   0        0        0      485 2023-06-28 09:06:30.000000 windows_control-0.0.6/README_PUB.md
+-rw-r--r--   0        0        0      679 2023-06-28 09:02:28.000000 windows_control-0.0.6/justfile
+-rw-r--r--   0        0        0      820 2023-06-28 09:06:55.000000 windows_control-0.0.6/pyproject.toml
+-rw-r--r--   0        0        0       90 2023-06-28 05:39:06.000000 windows_control-0.0.6/src/keyboard/mod.rs
+-rw-r--r--   0        0        0     1201 2023-06-28 05:51:30.000000 windows_control-0.0.6/src/lib.rs
+-rw-r--r--   0        0        0      508 2023-06-28 05:39:46.000000 windows_control-0.0.6/test.py
+-rw-r--r--   0        0        0     7435 2023-06-28 06:00:28.000000 windows_control-0.0.6/Cargo.lock
+-rw-r--r--   0        0        0      981 1970-01-01 00:00:00.000000 windows_control-0.0.6/PKG-INFO
```

### Comparing `windows_control-0.0.5/.github/workflows/CI.yml` & `windows_control-0.0.6/.github/workflows/CI.yml`

 * *Files identical despite different names*

### Comparing `windows_control-0.0.5/.gitignore` & `windows_control-0.0.6/.gitignore`

 * *Files identical despite different names*

### Comparing `windows_control-0.0.5/README.md` & `windows_control-0.0.6/README.md`

 * *Files 9% similar despite different names*

```diff
@@ -29,24 +29,26 @@
 
 Second, make sure there is an virtual env at your project root directory. You can do it by running `python -m venv .venv` in terminal---the name `.venv` is specified for `maturin`.
 
 Then, to add new features(like new funcs or new modules), modify the `src/lib.rs` file. After making changes, generate the Python module by running `maturin develop`. This command generates a library in `target/debug`. On Windows, rename the generated library file `[your_module].dll` to `[your_module].pyd`.
 
 Finally, to test the generated library, run `python test.py` in the root directory to verify that the newly added features work correctly in Python.
 
+### Automatic Development
+
+If you have [just](https://crates.io/crates/just) installed, run just to automatically generate and test the project. The justfile contains specific commands for this purpose.
+
 ### Publish
-First, update the field `version` in file `pyproject.toml`;
-Then, use `maturin publish`(in powershell,not git bash) to publish the package to PyPI.When you see:
+First, update the field `version` in file `pyproject.toml`.
+Then, use `maturin publish`(in powershell,not git bash) to publish the package to PyPI(or just run `just pub` with [just](https://crates.io/crates/just)).When you see:
 ```bash
 🚀 Uploading 2 packages
 ✨ Packages uploaded successfully
 ```
 This means it's published successfully, and you can check it in [PyPi](https://pypi.org/project/windows-control/).
 
-### Automatic Development
-
-If you have [just](https://crates.io/crates/just) installed, run just to automatically generate and test the project. The justfile contains specific commands for this purpose.
+Finally, update section `Examples` in both `README.md`(this file) and `README.rst`.
 
 
 ## License
 
 This project is licensed under the MIT License.
```

### Comparing `windows_control-0.0.5/pyproject.toml` & `windows_control-0.0.6/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 [project]
 name = "windows_control"
-version = "0.0.5"
+version = "0.0.6"
 description = "It is used to do some control with keyboard/mouse on windows (especially on win10)."
-readme = "README.rst"
+readme = "README_PUB.md"
 requires-python = ">=3.8"
 classifiers = [
     "Programming Language :: Rust",
     "Programming Language :: Python :: Implementation :: CPython",
     "Programming Language :: Python :: Implementation :: PyPy",
 ]
```

### Comparing `windows_control-0.0.5/src/lib.rs` & `windows_control-0.0.6/src/lib.rs`

 * *Files identical despite different names*

### Comparing `windows_control-0.0.5/Cargo.lock` & `windows_control-0.0.6/Cargo.lock`

 * *Files identical despite different names*

### Comparing `windows_control-0.0.5/PKG-INFO` & `windows_control-0.0.6/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 2.1
 Name: windows_control
-Version: 0.0.5
+Version: 0.0.6
 Classifier: Programming Language :: Rust
 Classifier: Programming Language :: Python :: Implementation :: CPython
 Classifier: Programming Language :: Python :: Implementation :: PyPy
 Summary: It is used to do some control with keyboard/mouse on windows (especially on win10).
 Requires-Python: >=3.8
-Description-Content-Type: text/x-rst; charset=UTF-8
+Description-Content-Type: text/markdown; charset=UTF-8; variant=GFM
 Project-URL: repository, https://github.com/dbsxdbsx/windows_control
 
 # Project Name
 
 [windows_control](https://pypi.org/project/windows-control/) is a package named with a root Python module `windows_control`.
 It provides some simple and efficient ways to do manipulations on Windows systems(Especially on Win10) efficiently, since it is written in Rust using [PyO3](https://crates.io/crates/pyo3).
 
@@ -21,9 +21,8 @@
 ```
 
 ## Requirements
 
 - Setting for final usage: Python (version 3.9.11 or later)
 
 ## Examples
-
 (TODO)
```


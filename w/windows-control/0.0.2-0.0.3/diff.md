# Comparing `tmp/windows_control-0.0.2.tar.gz` & `tmp/windows_control-0.0.3.tar.gz`

## Comparing `windows_control-0.0.2.tar` & `windows_control-0.0.3.tar`

### file list

```diff
@@ -1,11 +1,12 @@
--rw-r--r--   0        0        0      488 1970-01-01 00:00:00.000000 windows_control-0.0.2/Cargo.toml
--rw-r--r--   0        0        0     2807 2023-06-28 03:33:37.000000 windows_control-0.0.2/.github/workflows/CI.yml
--rw-r--r--   0        0        0      756 2023-06-28 03:33:37.000000 windows_control-0.0.2/.gitignore
--rw-r--r--   0        0        0     1936 2023-06-28 08:23:20.000000 windows_control-0.0.2/README.md
--rw-r--r--   0        0        0      821 2023-06-28 08:30:46.000000 windows_control-0.0.2/justfile
--rw-r--r--   0        0        0      812 2023-06-28 08:29:56.000000 windows_control-0.0.2/pyproject.toml
--rw-r--r--   0        0        0       90 2023-06-28 05:39:06.000000 windows_control-0.0.2/src/keyboard/mod.rs
--rw-r--r--   0        0        0     1201 2023-06-28 05:51:30.000000 windows_control-0.0.2/src/lib.rs
--rw-r--r--   0        0        0      508 2023-06-28 05:39:46.000000 windows_control-0.0.2/test.py
--rw-r--r--   0        0        0     7435 2023-06-28 06:00:28.000000 windows_control-0.0.2/Cargo.lock
--rw-r--r--   0        0        0     2432 1970-01-01 00:00:00.000000 windows_control-0.0.2/PKG-INFO
+-rw-r--r--   0        0        0      488 1970-01-01 00:00:00.000000 windows_control-0.0.3/Cargo.toml
+-rw-r--r--   0        0        0     2807 2023-06-28 03:33:37.000000 windows_control-0.0.3/.github/workflows/CI.yml
+-rw-r--r--   0        0        0      756 2023-06-28 03:33:37.000000 windows_control-0.0.3/.gitignore
+-rw-r--r--   0        0        0     2296 2023-06-28 08:46:08.000000 windows_control-0.0.3/README.md
+-rw-r--r--   0        0        0     2243 2023-06-28 08:43:35.000000 windows_control-0.0.3/README.rst
+-rw-r--r--   0        0        0      403 2023-06-28 08:34:41.000000 windows_control-0.0.3/justfile
+-rw-r--r--   0        0        0      841 2023-06-28 08:45:22.000000 windows_control-0.0.3/pyproject.toml
+-rw-r--r--   0        0        0       90 2023-06-28 05:39:06.000000 windows_control-0.0.3/src/keyboard/mod.rs
+-rw-r--r--   0        0        0     1201 2023-06-28 05:51:30.000000 windows_control-0.0.3/src/lib.rs
+-rw-r--r--   0        0        0      508 2023-06-28 05:39:46.000000 windows_control-0.0.3/test.py
+-rw-r--r--   0        0        0     7435 2023-06-28 06:00:28.000000 windows_control-0.0.3/Cargo.lock
+-rw-r--r--   0        0        0     2723 1970-01-01 00:00:00.000000 windows_control-0.0.3/PKG-INFO
```

### Comparing `windows_control-0.0.2/.github/workflows/CI.yml` & `windows_control-0.0.3/.github/workflows/CI.yml`

 * *Files identical despite different names*

### Comparing `windows_control-0.0.2/.gitignore` & `windows_control-0.0.3/.gitignore`

 * *Files identical despite different names*

### Comparing `windows_control-0.0.2/README.md` & `windows_control-0.0.3/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -28,16 +28,27 @@
 
 Second, make sure there is an virtual env at your project root directory. You can do it by running `python -m venv .venv` in terminal---the name `.venv` is specified for `maturin`.
 
 Then, to add new features(like new funcs or new modules), modify the `src/lib.rs` file. After making changes, generate the Python module by running `maturin develop`. This command generates a library in `target/debug`. On Windows, rename the generated library file `[your_module].dll` to `[your_module].pyd`.
 
 Finally, to test the generated library, run `python test.py` in the root directory to verify that the newly added features work correctly in Python.
 
+### Publish
+First, update the field `version` in file `pyproject.toml`;
+Then, use `maturin publish` to publish the package to PyPI.When you see:
+```bash
+🚀 Uploading 2 packages
+✨ Packages uploaded successfully
+```
+This means it's published successfully, and you can check it in [PyPi](https://pypi.org/project/windows-control/).
+
 ### Automatic Development
 
 If you have [just](https://crates.io/crates/just) installed, run just to automatically generate and test the project. The justfile contains specific commands for this purpose.
 
 
 ## License
 
 This project is licensed under the MIT License.
 
+## A little Test
+Hi, there
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `windows_control-0.0.2/pyproject.toml` & `windows_control-0.0.3/pyproject.toml`

 * *Files 20% similar despite different names*

```diff
@@ -1,12 +1,13 @@
 [project]
 name = "windows_control"
-version = "0.0.2"
+version = "0.0.3"
 description = "It is used to do some control with keyboard/mouse on windows (especially on win10)."
-readme = "README.md"
+readme = "README.rst"
+# readme = "README.md"
 requires-python = ">=3.8"
 classifiers = [
     "Programming Language :: Rust",
     "Programming Language :: Python :: Implementation :: CPython",
     "Programming Language :: Python :: Implementation :: PyPy",
 ]
 
@@ -17,8 +18,9 @@
 
 [build-system]
 requires = ["maturin>=1.1,<2.0"]
 build-backend = "maturin"
 
 [tool.maturin]
 # "extension-module" tells pyo3 we want to build an extension module (skips linking against libpython.so)
-features = ["pyo3/extension-module"]
+features = ["pyo3/extension-module"]
+
```

### Comparing `windows_control-0.0.2/src/lib.rs` & `windows_control-0.0.3/src/lib.rs`

 * *Files identical despite different names*

### Comparing `windows_control-0.0.2/Cargo.lock` & `windows_control-0.0.3/Cargo.lock`

 * *Files identical despite different names*

### Comparing `windows_control-0.0.2/PKG-INFO` & `windows_control-0.0.3/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,18 +1,20 @@
 Metadata-Version: 2.1
 Name: windows_control
-Version: 0.0.2
+Version: 0.0.3
 Classifier: Programming Language :: Rust
 Classifier: Programming Language :: Python :: Implementation :: CPython
 Classifier: Programming Language :: Python :: Implementation :: PyPy
 Summary: It is used to do some control with keyboard/mouse on windows (especially on win10).
 Requires-Python: >=3.8
-Description-Content-Type: text/markdown; charset=UTF-8; variant=GFM
+Description-Content-Type: text/x-rst; charset=UTF-8
 Project-URL: repository, https://github.com/dbsxdbsx/windows_control
 
+# Just Test
+
 # Project Name
 
 [windows_control_python](https://pypi.org/project/windows-control/) is a project to generate a Python module named `windows_control`, which provides some simple and efficient ways to do manipulations on Windows systems(Especially on Win10). It is written in Rust using [PyO3](https://crates.io/crates/pyo3).
 ## Installation
 
 ```bash
 pip install windows_control
@@ -39,17 +41,27 @@
 
 Second, make sure there is an virtual env at your project root directory. You can do it by running `python -m venv .venv` in terminal---the name `.venv` is specified for `maturin`.
 
 Then, to add new features(like new funcs or new modules), modify the `src/lib.rs` file. After making changes, generate the Python module by running `maturin develop`. This command generates a library in `target/debug`. On Windows, rename the generated library file `[your_module].dll` to `[your_module].pyd`.
 
 Finally, to test the generated library, run `python test.py` in the root directory to verify that the newly added features work correctly in Python.
 
+### Publish
+
+use `maturin publish` to publish the package to PyPI.When you see
+```bash
+🚀 Uploading 2 packages
+✨ Packages uploaded successfully
+```
+This means it's published successfully, and you can check it in [PyPi](https://pypi.org/project/windows-control/).
+
 ### Automatic Development
 
 If you have [just](https://crates.io/crates/just) installed, run just to automatically generate and test the project. The justfile contains specific commands for this purpose.
 
 
 ## License
 
 This project is licensed under the MIT License.
 
-
+## A little Test
+Hi, there
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```


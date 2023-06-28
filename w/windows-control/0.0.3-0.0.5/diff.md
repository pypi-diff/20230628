# Comparing `tmp/windows_control-0.0.3.tar.gz` & `tmp/windows_control-0.0.5.tar.gz`

## Comparing `windows_control-0.0.3.tar` & `windows_control-0.0.5.tar`

### file list

```diff
@@ -1,12 +1,12 @@
--rw-r--r--   0        0        0      488 1970-01-01 00:00:00.000000 windows_control-0.0.3/Cargo.toml
--rw-r--r--   0        0        0     2807 2023-06-28 03:33:37.000000 windows_control-0.0.3/.github/workflows/CI.yml
--rw-r--r--   0        0        0      756 2023-06-28 03:33:37.000000 windows_control-0.0.3/.gitignore
--rw-r--r--   0        0        0     2296 2023-06-28 08:46:08.000000 windows_control-0.0.3/README.md
--rw-r--r--   0        0        0     2243 2023-06-28 08:43:35.000000 windows_control-0.0.3/README.rst
--rw-r--r--   0        0        0      403 2023-06-28 08:34:41.000000 windows_control-0.0.3/justfile
--rw-r--r--   0        0        0      841 2023-06-28 08:45:22.000000 windows_control-0.0.3/pyproject.toml
--rw-r--r--   0        0        0       90 2023-06-28 05:39:06.000000 windows_control-0.0.3/src/keyboard/mod.rs
--rw-r--r--   0        0        0     1201 2023-06-28 05:51:30.000000 windows_control-0.0.3/src/lib.rs
--rw-r--r--   0        0        0      508 2023-06-28 05:39:46.000000 windows_control-0.0.3/test.py
--rw-r--r--   0        0        0     7435 2023-06-28 06:00:28.000000 windows_control-0.0.3/Cargo.lock
--rw-r--r--   0        0        0     2723 1970-01-01 00:00:00.000000 windows_control-0.0.3/PKG-INFO
+-rw-r--r--   0        0        0      488 1970-01-01 00:00:00.000000 windows_control-0.0.5/Cargo.toml
+-rw-r--r--   0        0        0     2807 2023-06-28 03:33:37.000000 windows_control-0.0.5/.github/workflows/CI.yml
+-rw-r--r--   0        0        0      756 2023-06-28 03:33:37.000000 windows_control-0.0.5/.gitignore
+-rw-r--r--   0        0        0     2298 2023-06-28 08:54:02.000000 windows_control-0.0.5/README.md
+-rw-r--r--   0        0        0      486 2023-06-28 08:53:52.000000 windows_control-0.0.5/README.rst
+-rw-r--r--   0        0        0      403 2023-06-28 08:34:41.000000 windows_control-0.0.5/justfile
+-rw-r--r--   0        0        0      817 2023-06-28 08:54:11.000000 windows_control-0.0.5/pyproject.toml
+-rw-r--r--   0        0        0       90 2023-06-28 05:39:06.000000 windows_control-0.0.5/src/keyboard/mod.rs
+-rw-r--r--   0        0        0     1201 2023-06-28 05:51:30.000000 windows_control-0.0.5/src/lib.rs
+-rw-r--r--   0        0        0      508 2023-06-28 05:39:46.000000 windows_control-0.0.5/test.py
+-rw-r--r--   0        0        0     7435 2023-06-28 06:00:28.000000 windows_control-0.0.5/Cargo.lock
+-rw-r--r--   0        0        0      966 1970-01-01 00:00:00.000000 windows_control-0.0.5/PKG-INFO
```

### Comparing `windows_control-0.0.3/.github/workflows/CI.yml` & `windows_control-0.0.5/.github/workflows/CI.yml`

 * *Files identical despite different names*

### Comparing `windows_control-0.0.3/.gitignore` & `windows_control-0.0.5/.gitignore`

 * *Files identical despite different names*

### Comparing `windows_control-0.0.3/README.md` & `windows_control-0.0.5/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,11 @@
 # Project Name
 
 [windows_control_python](https://pypi.org/project/windows-control/) is a project to generate a Python module named `windows_control`, which provides some simple and efficient ways to do manipulations on Windows systems(Especially on Win10). It is written in Rust using [PyO3](https://crates.io/crates/pyo3).
+
 ## Installation
 
 ```bash
 pip install windows_control
 ```
 
 ## Requirements
@@ -30,25 +31,22 @@
 
 Then, to add new features(like new funcs or new modules), modify the `src/lib.rs` file. After making changes, generate the Python module by running `maturin develop`. This command generates a library in `target/debug`. On Windows, rename the generated library file `[your_module].dll` to `[your_module].pyd`.
 
 Finally, to test the generated library, run `python test.py` in the root directory to verify that the newly added features work correctly in Python.
 
 ### Publish
 First, update the field `version` in file `pyproject.toml`;
-Then, use `maturin publish` to publish the package to PyPI.When you see:
+Then, use `maturin publish`(in powershell,not git bash) to publish the package to PyPI.When you see:
 ```bash
 🚀 Uploading 2 packages
 ✨ Packages uploaded successfully
 ```
 This means it's published successfully, and you can check it in [PyPi](https://pypi.org/project/windows-control/).
 
 ### Automatic Development
 
 If you have [just](https://crates.io/crates/just) installed, run just to automatically generate and test the project. The justfile contains specific commands for this purpose.
 
 
 ## License
 
 This project is licensed under the MIT License.
-
-## A little Test
-Hi, there
```

### Comparing `windows_control-0.0.3/pyproject.toml` & `windows_control-0.0.5/pyproject.toml`

 * *Files 19% similar despite different names*

```diff
@@ -1,13 +1,12 @@
 [project]
 name = "windows_control"
-version = "0.0.3"
+version = "0.0.5"
 description = "It is used to do some control with keyboard/mouse on windows (especially on win10)."
 readme = "README.rst"
-# readme = "README.md"
 requires-python = ">=3.8"
 classifiers = [
     "Programming Language :: Rust",
     "Programming Language :: Python :: Implementation :: CPython",
     "Programming Language :: Python :: Implementation :: PyPy",
 ]
```

### Comparing `windows_control-0.0.3/src/lib.rs` & `windows_control-0.0.5/src/lib.rs`

 * *Files identical despite different names*

### Comparing `windows_control-0.0.3/Cargo.lock` & `windows_control-0.0.5/Cargo.lock`

 * *Files identical despite different names*


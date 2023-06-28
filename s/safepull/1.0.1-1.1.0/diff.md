# Comparing `tmp/safepull-1.0.1.tar.gz` & `tmp/safepull-1.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "safepull-1.0.1.tar", last modified: Mon May  1 23:28:05 2023, max compression
+gzip compressed data, was "safepull-1.1.0.tar", last modified: Wed Jun 28 03:04:46 2023, max compression
```

## Comparing `safepull-1.0.1.tar` & `safepull-1.1.0.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxrwxr-x   0 rem       (1000) rem       (1000)        0 2023-05-01 23:28:05.278447 safepull-1.0.1/
--rw-rw-r--   0 rem       (1000) rem       (1000)     1060 2023-05-01 23:04:18.000000 safepull-1.0.1/LICENSE
--rw-rw-r--   0 rem       (1000) rem       (1000)     1516 2023-05-01 23:28:05.278447 safepull-1.0.1/PKG-INFO
--rw-rw-r--   0 rem       (1000) rem       (1000)     1134 2023-05-01 23:26:22.000000 safepull-1.0.1/README.md
--rw-rw-r--   0 rem       (1000) rem       (1000)      552 2023-05-01 23:27:47.000000 safepull-1.0.1/pyproject.toml
--rw-rw-r--   0 rem       (1000) rem       (1000)       38 2023-05-01 23:28:05.278447 safepull-1.0.1/setup.cfg
-drwxrwxr-x   0 rem       (1000) rem       (1000)        0 2023-05-01 23:28:05.278447 safepull-1.0.1/src/
-drwxrwxr-x   0 rem       (1000) rem       (1000)        0 2023-05-01 23:28:05.278447 safepull-1.0.1/src/safepull/
--rw-rw-r--   0 rem       (1000) rem       (1000)        0 2023-05-01 23:04:18.000000 safepull-1.0.1/src/safepull/__init__.py
--rw-rw-r--   0 rem       (1000) rem       (1000)       64 2023-05-01 23:04:18.000000 safepull-1.0.1/src/safepull/__main__.py
--rw-rw-r--   0 rem       (1000) rem       (1000)     5087 2023-05-01 23:04:18.000000 safepull-1.0.1/src/safepull/safepull.py
-drwxrwxr-x   0 rem       (1000) rem       (1000)        0 2023-05-01 23:28:05.278447 safepull-1.0.1/src/safepull.egg-info/
--rw-rw-r--   0 rem       (1000) rem       (1000)     1516 2023-05-01 23:28:05.000000 safepull-1.0.1/src/safepull.egg-info/PKG-INFO
--rw-rw-r--   0 rem       (1000) rem       (1000)      325 2023-05-01 23:28:05.000000 safepull-1.0.1/src/safepull.egg-info/SOURCES.txt
--rw-rw-r--   0 rem       (1000) rem       (1000)        1 2023-05-01 23:28:05.000000 safepull-1.0.1/src/safepull.egg-info/dependency_links.txt
--rw-rw-r--   0 rem       (1000) rem       (1000)       51 2023-05-01 23:28:05.000000 safepull-1.0.1/src/safepull.egg-info/entry_points.txt
--rw-rw-r--   0 rem       (1000) rem       (1000)       17 2023-05-01 23:28:05.000000 safepull-1.0.1/src/safepull.egg-info/requires.txt
--rw-rw-r--   0 rem       (1000) rem       (1000)        9 2023-05-01 23:28:05.000000 safepull-1.0.1/src/safepull.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:04:46.460860 safepull-1.1.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1060 2023-06-28 03:04:37.000000 safepull-1.1.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     1520 2023-06-28 03:04:46.460860 safepull-1.1.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1138 2023-06-28 03:04:37.000000 safepull-1.1.0/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      552 2023-06-28 03:04:37.000000 safepull-1.1.0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 03:04:46.460860 safepull-1.1.0/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:04:46.460860 safepull-1.1.0/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:04:46.460860 safepull-1.1.0/src/safepull/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 03:04:37.000000 safepull-1.1.0/src/safepull/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)       64 2023-06-28 03:04:37.000000 safepull-1.1.0/src/safepull/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5079 2023-06-28 03:04:37.000000 safepull-1.1.0/src/safepull/safepull.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:04:46.460860 safepull-1.1.0/src/safepull.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1520 2023-06-28 03:04:46.000000 safepull-1.1.0/src/safepull.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      325 2023-06-28 03:04:46.000000 safepull-1.1.0/src/safepull.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 03:04:46.000000 safepull-1.1.0/src/safepull.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-28 03:04:46.000000 safepull-1.1.0/src/safepull.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 03:04:46.000000 safepull-1.1.0/src/safepull.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 03:04:46.000000 safepull-1.1.0/src/safepull.egg-info/top_level.txt
```

### Comparing `safepull-1.0.1/LICENSE` & `safepull-1.1.0/LICENSE`

 * *Files identical despite different names*

### Comparing `safepull-1.0.1/PKG-INFO` & `safepull-1.1.0/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: safepull
-Version: 1.0.1
+Version: 1.1.0
 Summary: A quick and dirty command-line script to pull down and extract .py files out of tarballs and wheels without interfacing with the setup.py file.
 License: MIT
 Project-URL: repository, https://github.com/import-pandas-as-numpy/safepull/
 Requires-Python: >=3.10
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
@@ -18,22 +18,22 @@
 Safepull is available on PyPI.
 
 `pip install safepull`
 
 # Usage Instructions
 Safepull has three command line arguments.
 
-`-p --package <packagename>` is required. When force is not specified, you will be prompted for a distribution type to download.
+Positional argument `<packagename>` is required. When force is not specified, you will be prompted for a distribution type to download.
 
 `-f --force` will attempt to download the sdist of a particular package without prompt. 
 
-`-m --metadata` will return the package name, description, and author of a partiuclar package.
+`-m --metadata` will return the package name, description, and author of a particular package.
 
 ```
-rem@rembox:~$ safepull -p numpy
+rem@rembox:~$ safepull numpy
 numpy 1.24.3
 Fundamental package for array computing in Python
 Author: Travis E. Oliphant et al.
 --0--
 Filename: numpy-1.24.3-cp310-cp310-macosx_10_9_x86_64.whl
 Package Type: bdist_wheel
 URL: https://files.pythonhosted.org/packages/f3/23/7cc851bae09cf4db90d42a701dfe525780883ada86bece45e3da7a07e76b/numpy-1.24.3-cp310-cp310-macosx_10_9_x86_64.whl
```

### Comparing `safepull-1.0.1/README.md` & `safepull-1.1.0/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -8,22 +8,22 @@
 Safepull is available on PyPI.
 
 `pip install safepull`
 
 # Usage Instructions
 Safepull has three command line arguments.
 
-`-p --package <packagename>` is required. When force is not specified, you will be prompted for a distribution type to download.
+Positional argument `<packagename>` is required. When force is not specified, you will be prompted for a distribution type to download.
 
 `-f --force` will attempt to download the sdist of a particular package without prompt. 
 
-`-m --metadata` will return the package name, description, and author of a partiuclar package.
+`-m --metadata` will return the package name, description, and author of a particular package.
 
 ```
-rem@rembox:~$ safepull -p numpy
+rem@rembox:~$ safepull numpy
 numpy 1.24.3
 Fundamental package for array computing in Python
 Author: Travis E. Oliphant et al.
 --0--
 Filename: numpy-1.24.3-cp310-cp310-macosx_10_9_x86_64.whl
 Package Type: bdist_wheel
 URL: https://files.pythonhosted.org/packages/f3/23/7cc851bae09cf4db90d42a701dfe525780883ada86bece45e3da7a07e76b/numpy-1.24.3-cp310-cp310-macosx_10_9_x86_64.whl
```

### Comparing `safepull-1.0.1/pyproject.toml` & `safepull-1.1.0/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [project]
 name = "safepull"
-version = "1.0.1"
+version = "1.1.0"
 description = "A quick and dirty command-line script to pull down and extract .py files out of tarballs and wheels without interfacing with the setup.py file."
 readme = "README.md"
 license = { text = "MIT" }
 requires-python = ">=3.10"
 dependencies = [
     "requests~=2.28.2",
 ]
```

### Comparing `safepull-1.0.1/src/safepull/safepull.py` & `safepull-1.1.0/src/safepull/safepull.py`

 * *Files 0% similar despite different names*

```diff
@@ -98,15 +98,15 @@
             whl_zip.extractall(members=zip_members)
     os.remove(file_loc)
 
 
 def run() -> None:
     parser = argparse.ArgumentParser(prog="Safepull",
                                      description="Extracts a package to the CWD without interfacing with setup.py")
-    parser.add_argument('-p', '--package', help='Package title to be downloaded.')
+    parser.add_argument('package', help='Package title to be downloaded.')
     parser.add_argument('-f', '--force', action='store_true', help='Automatically selects a download URL.')
     parser.add_argument('-m', '--metadata', action='store_true', help='Displays metadata on a package.')
     args = parser.parse_args()
 
     use_in = args.package
     if not args.package:
         use_in = input('Input a package title: ')
```

### Comparing `safepull-1.0.1/src/safepull.egg-info/PKG-INFO` & `safepull-1.1.0/src/safepull.egg-info/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: safepull
-Version: 1.0.1
+Version: 1.1.0
 Summary: A quick and dirty command-line script to pull down and extract .py files out of tarballs and wheels without interfacing with the setup.py file.
 License: MIT
 Project-URL: repository, https://github.com/import-pandas-as-numpy/safepull/
 Requires-Python: >=3.10
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
@@ -18,22 +18,22 @@
 Safepull is available on PyPI.
 
 `pip install safepull`
 
 # Usage Instructions
 Safepull has three command line arguments.
 
-`-p --package <packagename>` is required. When force is not specified, you will be prompted for a distribution type to download.
+Positional argument `<packagename>` is required. When force is not specified, you will be prompted for a distribution type to download.
 
 `-f --force` will attempt to download the sdist of a particular package without prompt. 
 
-`-m --metadata` will return the package name, description, and author of a partiuclar package.
+`-m --metadata` will return the package name, description, and author of a particular package.
 
 ```
-rem@rembox:~$ safepull -p numpy
+rem@rembox:~$ safepull numpy
 numpy 1.24.3
 Fundamental package for array computing in Python
 Author: Travis E. Oliphant et al.
 --0--
 Filename: numpy-1.24.3-cp310-cp310-macosx_10_9_x86_64.whl
 Package Type: bdist_wheel
 URL: https://files.pythonhosted.org/packages/f3/23/7cc851bae09cf4db90d42a701dfe525780883ada86bece45e3da7a07e76b/numpy-1.24.3-cp310-cp310-macosx_10_9_x86_64.whl
```


# Comparing `tmp/sv_ttk-2.4.5.tar.gz` & `tmp/sv_ttk-2.5.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sv_ttk-2.4.5.tar", last modified: Sat Apr 22 11:08:25 2023, max compression
+gzip compressed data, was "sv_ttk-2.5.0.tar", last modified: Wed Jun 28 11:27:53 2023, max compression
```

## Comparing `sv_ttk-2.4.5.tar` & `sv_ttk-2.5.0.tar`

### file list

```diff
@@ -1,21 +1,12 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-22 11:08:25.231245 sv_ttk-2.4.5/
--rw-r--r--   0 runner    (1001) docker     (123)     1079 2023-04-22 11:08:08.000000 sv_ttk-2.4.5/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     2552 2023-04-22 11:08:25.231245 sv_ttk-2.4.5/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1407 2023-04-22 11:08:08.000000 sv_ttk-2.4.5/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-04-22 11:08:25.231245 sv_ttk-2.4.5/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1982 2023-04-22 11:08:08.000000 sv_ttk-2.4.5/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-22 11:08:25.231245 sv_ttk-2.4.5/sv_ttk/
--rw-r--r--   0 runner    (1001) docker     (123)     1434 2023-04-22 11:08:23.000000 sv_ttk-2.4.5/sv_ttk/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5150 2023-04-22 11:08:23.000000 sv_ttk-2.4.5/sv_ttk/sv.tcl
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-22 11:08:25.231245 sv_ttk-2.4.5/sv_ttk/theme/
--rw-r--r--   0 runner    (1001) docker     (123)    16187 2023-04-22 11:08:23.000000 sv_ttk-2.4.5/sv_ttk/theme/dark.tcl
--rw-r--r--   0 runner    (1001) docker     (123)    16295 2023-04-22 11:08:23.000000 sv_ttk-2.4.5/sv_ttk/theme/light.tcl
--rw-r--r--   0 runner    (1001) docker     (123)     3045 2023-04-22 11:08:23.000000 sv_ttk-2.4.5/sv_ttk/theme/sprites_dark.tcl
--rw-r--r--   0 runner    (1001) docker     (123)     3092 2023-04-22 11:08:23.000000 sv_ttk-2.4.5/sv_ttk/theme/sprites_light.tcl
--rw-r--r--   0 runner    (1001) docker     (123)    18371 2023-04-22 11:08:23.000000 sv_ttk-2.4.5/sv_ttk/theme/spritesheet_dark.png
--rw-r--r--   0 runner    (1001) docker     (123)    18462 2023-04-22 11:08:23.000000 sv_ttk-2.4.5/sv_ttk/theme/spritesheet_light.png
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-22 11:08:25.231245 sv_ttk-2.4.5/sv_ttk.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     2552 2023-04-22 11:08:25.000000 sv_ttk-2.4.5/sv_ttk.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      354 2023-04-22 11:08:25.000000 sv_ttk-2.4.5/sv_ttk.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-04-22 11:08:25.000000 sv_ttk-2.4.5/sv_ttk.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-04-22 11:08:25.000000 sv_ttk-2.4.5/sv_ttk.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:27:53.410352 sv_ttk-2.5.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1079 2023-06-28 11:27:42.000000 sv_ttk-2.5.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     2512 2023-06-28 11:27:53.410352 sv_ttk-2.5.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1407 2023-06-28 11:27:42.000000 sv_ttk-2.5.0/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 11:27:42.000000 sv_ttk-2.5.0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 11:27:53.410352 sv_ttk-2.5.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1916 2023-06-28 11:27:42.000000 sv_ttk-2.5.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:27:53.410352 sv_ttk-2.5.0/sv_ttk.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2512 2023-06-28 11:27:53.000000 sv_ttk-2.5.0/sv_ttk.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      161 2023-06-28 11:27:53.000000 sv_ttk-2.5.0/sv_ttk.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:27:53.000000 sv_ttk-2.5.0/sv_ttk.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:27:53.000000 sv_ttk-2.5.0/sv_ttk.egg-info/top_level.txt
```

### Comparing `sv_ttk-2.4.5/LICENSE` & `sv_ttk-2.5.0/LICENSE`

 * *Files identical despite different names*

### Comparing `sv_ttk-2.4.5/PKG-INFO` & `sv_ttk-2.5.0/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,34 +1,33 @@
 Metadata-Version: 2.1
 Name: sv_ttk
-Version: 2.4.5
+Version: 2.5.0
 Summary: A gorgeous theme for Tkinter, based on Windows 11's UI
 Home-page: https://github.com/rdbende/Sun-Valley-ttk-theme
 Author: rdbende
-Author-email: rdbende@gmail.com
+Author-email: rdbende@proton.me
 License: MIT
 Project-URL: Source, https://github.com/rdbende/Sun-Valley-ttk-theme
 Project-URL: Documentation, https://github.com/rdbende/Sun-Valley-ttk-theme/wiki
 Project-URL: Tracker, https://github.com/rdbende/Sun-Valley-ttk-theme/issues
-Keywords: dark-theme,modern,sun-valley,tcl,tcl/tk,theme,theme,tile,tk,tkinter,ttk,windows-11,winui
+Keywords: sv-ttk,tcl,tcl/tk,theme,tile,tk,ttk,tkinter,modern,fluent,dark-theme,sun-valley,windows-11,winui
 Platform: UNKNOWN
 Classifier: Intended Audience :: Developers
 Classifier: Topic :: Software Development :: User Interfaces
 Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: 3.4
-Classifier: Programming Language :: Python :: 3.5
-Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
 Classifier: Programming Language :: Tcl
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Requires-Python: >=3.4
+Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 <img alt="Cover image" src="https://raw.githubusercontent.com/rdbende/Sun-Valley-ttk-theme/master/assets/hero_light.png">
 
 ## Installation [![image](https://static.pepy.tech/badge/sv-ttk)](https://pypi.org/project/sv-ttk)
 The theme is easily installable as a Python package
```

### Comparing `sv_ttk-2.4.5/README.md` & `sv_ttk-2.5.0/README.md`

 * *Files identical despite different names*

### Comparing `sv_ttk-2.4.5/setup.py` & `sv_ttk-2.5.0/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,62 +1,61 @@
 import re
 from pathlib import Path
 
 from setuptools import setup
 
-with (Path(__file__).parent / "README.md").open() as file:
-    long_description = re.sub(
-        r"(?s)<picture>.*</picture>",
-        '<img alt="Cover image" src="https://raw.githubusercontent.com/rdbende/Sun-Valley-ttk-theme/master/assets/hero_light.png">',
-        file.read(),
-    )
+long_description = re.sub(
+    r"(?s)<picture>.*</picture>",
+    '<img alt="Cover image" src="https://raw.githubusercontent.com/rdbende/Sun-Valley-ttk-theme/master/assets/hero_light.png">',
+    (Path(__file__).parent / "README.md").read_text(),
+)
 
 
 setup(
     name="sv_ttk",
-    version="2.4.5",
+    version="2.5.0",
     license="MIT",
     author="rdbende",
-    author_email="rdbende@gmail.com",
+    author_email="rdbende@proton.me",
     url="https://github.com/rdbende/Sun-Valley-ttk-theme",
     project_urls={
         "Source": "https://github.com/rdbende/Sun-Valley-ttk-theme",
         "Documentation": "https://github.com/rdbende/Sun-Valley-ttk-theme/wiki",
         "Tracker": "https://github.com/rdbende/Sun-Valley-ttk-theme/issues",
     },
     description="A gorgeous theme for Tkinter, based on Windows 11's UI",
     long_description=long_description,
     long_description_content_type="text/markdown",
-    packages=["sv_ttk"],
+    py_packages=["sv_ttk"],
     package_data={"sv_ttk": ["sv.tcl", "theme/*"]},
-    python_requires=">=3.4",
+    python_requires=">=3.7",
     classifiers=[
         "Intended Audience :: Developers",
         "Topic :: Software Development :: User Interfaces",
         "Programming Language :: Python :: 3 :: Only",
-        "Programming Language :: Python :: 3.4",
-        "Programming Language :: Python :: 3.5",
-        "Programming Language :: Python :: 3.6",
         "Programming Language :: Python :: 3.7",
         "Programming Language :: Python :: 3.8",
         "Programming Language :: Python :: 3.9",
         "Programming Language :: Python :: 3.10",
+        "Programming Language :: Python :: 3.11",
+        "Programming Language :: Python :: 3.12",
         "Programming Language :: Tcl",
         "License :: OSI Approved :: MIT License",
         "Operating System :: OS Independent",
     ],
     keywords=[
-        "dark-theme",
-        "modern",
-        "sun-valley",
+        "sv-ttk",
         "tcl",
         "tcl/tk",
         "theme",
-        "theme",
         "tile",
         "tk",
-        "tkinter",
         "ttk",
+        "tkinter",
+        "modern",
+        "fluent",
+        "dark-theme",
+        "sun-valley",
         "windows-11",
         "winui",
     ],
 )
```

### Comparing `sv_ttk-2.4.5/sv_ttk.egg-info/PKG-INFO` & `sv_ttk-2.5.0/sv_ttk.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,34 +1,33 @@
 Metadata-Version: 2.1
 Name: sv-ttk
-Version: 2.4.5
+Version: 2.5.0
 Summary: A gorgeous theme for Tkinter, based on Windows 11's UI
 Home-page: https://github.com/rdbende/Sun-Valley-ttk-theme
 Author: rdbende
-Author-email: rdbende@gmail.com
+Author-email: rdbende@proton.me
 License: MIT
 Project-URL: Source, https://github.com/rdbende/Sun-Valley-ttk-theme
 Project-URL: Documentation, https://github.com/rdbende/Sun-Valley-ttk-theme/wiki
 Project-URL: Tracker, https://github.com/rdbende/Sun-Valley-ttk-theme/issues
-Keywords: dark-theme,modern,sun-valley,tcl,tcl/tk,theme,theme,tile,tk,tkinter,ttk,windows-11,winui
+Keywords: sv-ttk,tcl,tcl/tk,theme,tile,tk,ttk,tkinter,modern,fluent,dark-theme,sun-valley,windows-11,winui
 Platform: UNKNOWN
 Classifier: Intended Audience :: Developers
 Classifier: Topic :: Software Development :: User Interfaces
 Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: 3.4
-Classifier: Programming Language :: Python :: 3.5
-Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
 Classifier: Programming Language :: Tcl
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Requires-Python: >=3.4
+Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 <img alt="Cover image" src="https://raw.githubusercontent.com/rdbende/Sun-Valley-ttk-theme/master/assets/hero_light.png">
 
 ## Installation [![image](https://static.pepy.tech/badge/sv-ttk)](https://pypi.org/project/sv-ttk)
 The theme is easily installable as a Python package
```


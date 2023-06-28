# Comparing `tmp/moldoc-2.0.0.tar.gz` & `tmp/moldoc-3.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "moldoc-2.0.0.tar", last modified: Mon Jun 26 15:54:42 2023, max compression
+gzip compressed data, was "moldoc-3.0.0.tar", last modified: Wed Jun 28 13:56:36 2023, max compression
```

## Comparing `moldoc-2.0.0.tar` & `moldoc-3.0.0.tar`

### file list

```diff
@@ -1,49 +1,49 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 15:54:42.329191 moldoc-2.0.0/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 15:54:42.313191 moldoc-2.0.0/.github/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 15:54:42.317191 moldoc-2.0.0/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)      554 2023-06-26 15:54:13.000000 moldoc-2.0.0/.github/workflows/publish_release.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     1111 2023-06-26 15:54:13.000000 moldoc-2.0.0/.github/workflows/tests.yaml
--rw-r--r--   0 runner    (1001) docker     (123)       84 2023-06-26 15:54:13.000000 moldoc-2.0.0/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)     1053 2023-06-26 15:54:13.000000 moldoc-2.0.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     6241 2023-06-26 15:54:42.325191 moldoc-2.0.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     5968 2023-06-26 15:54:13.000000 moldoc-2.0.0/README.rst
--rw-r--r--   0 runner    (1001) docker     (123)   117976 2023-06-26 15:54:13.000000 moldoc-2.0.0/configuration.jpg
--rw-r--r--   0 runner    (1001) docker     (123)      386 2023-06-26 15:54:13.000000 moldoc-2.0.0/justfile
--rw-r--r--   0 runner    (1001) docker     (123)  1268442 2023-06-26 15:54:13.000000 moldoc-2.0.0/moldoc.gif
--rw-r--r--   0 runner    (1001) docker     (123)      993 2023-06-26 15:54:13.000000 moldoc-2.0.0/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-26 15:54:42.329191 moldoc-2.0.0/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 15:54:42.313191 moldoc-2.0.0/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 15:54:42.321191 moldoc-2.0.0/src/moldoc/
--rw-r--r--   0 runner    (1001) docker     (123)       63 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 15:54:42.321191 moldoc-2.0.0/src/moldoc/_internal/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/_internal/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 15:54:42.325191 moldoc-2.0.0/src/moldoc/_internal/javascript/
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/_internal/javascript/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1920 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/_internal/javascript/atoms.py
--rw-r--r--   0 runner    (1001) docker     (123)      390 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/_internal/javascript/bonds.py
--rw-r--r--   0 runner    (1001) docker     (123)       88 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/_internal/javascript/bool.py
--rw-r--r--   0 runner    (1001) docker     (123)      297 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/_internal/javascript/color.py
--rw-r--r--   0 runner    (1001) docker     (123)     4078 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/_internal/javascript/material.py
--rw-r--r--   0 runner    (1001) docker     (123)     2846 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/_internal/javascript/mesh_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     1001 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/_internal/javascript/scene_config.py
--rw-r--r--   0 runner    (1001) docker     (123)   351667 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/_internal/molDraw.js
--rw-r--r--   0 runner    (1001) docker     (123)     4201 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/_internal/moldoc.py
--rw-r--r--   0 runner    (1001) docker     (123)     6217 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/_internal/molecule.py
--rw-r--r--   0 runner    (1001) docker     (123)   551410 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/_internal/three.min.js
--rw-r--r--   0 runner    (1001) docker     (123)      519 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/molecule.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 15:54:13.000000 moldoc-2.0.0/src/moldoc/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)      160 2023-06-26 15:54:42.000000 moldoc-2.0.0/src/moldoc/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 15:54:42.321191 moldoc-2.0.0/src/moldoc.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     6241 2023-06-26 15:54:42.000000 moldoc-2.0.0/src/moldoc.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1017 2023-06-26 15:54:42.000000 moldoc-2.0.0/src/moldoc.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 15:54:42.000000 moldoc-2.0.0/src/moldoc.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       62 2023-06-26 15:54:42.000000 moldoc-2.0.0/src/moldoc.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-26 15:54:42.000000 moldoc-2.0.0/src/moldoc.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 15:54:42.325191 moldoc-2.0.0/tests/
--rw-r--r--   0 runner    (1001) docker     (123)      638 2023-06-26 15:54:13.000000 moldoc-2.0.0/tests/Makefile
--rw-r--r--   0 runner    (1001) docker     (123)      799 2023-06-26 15:54:13.000000 moldoc-2.0.0/tests/make.bat
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 15:54:42.325191 moldoc-2.0.0/tests/source/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 15:54:42.325191 moldoc-2.0.0/tests/source/_static/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 15:54:13.000000 moldoc-2.0.0/tests/source/_static/empty
--rw-r--r--   0 runner    (1001) docker     (123)     1993 2023-06-26 15:54:13.000000 moldoc-2.0.0/tests/source/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)    12186 2023-06-26 15:54:13.000000 moldoc-2.0.0/tests/source/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:36.781775 moldoc-3.0.0/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:36.773775 moldoc-3.0.0/.github/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:36.777775 moldoc-3.0.0/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)      554 2023-06-28 13:56:09.000000 moldoc-3.0.0/.github/workflows/publish_release.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     1111 2023-06-28 13:56:09.000000 moldoc-3.0.0/.github/workflows/tests.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)       84 2023-06-28 13:56:09.000000 moldoc-3.0.0/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)     1053 2023-06-28 13:56:09.000000 moldoc-3.0.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     6241 2023-06-28 13:56:36.781775 moldoc-3.0.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     5968 2023-06-28 13:56:09.000000 moldoc-3.0.0/README.rst
+-rw-r--r--   0 runner    (1001) docker     (123)   117976 2023-06-28 13:56:09.000000 moldoc-3.0.0/configuration.jpg
+-rw-r--r--   0 runner    (1001) docker     (123)      386 2023-06-28 13:56:09.000000 moldoc-3.0.0/justfile
+-rw-r--r--   0 runner    (1001) docker     (123)  1268442 2023-06-28 13:56:09.000000 moldoc-3.0.0/moldoc.gif
+-rw-r--r--   0 runner    (1001) docker     (123)      993 2023-06-28 13:56:09.000000 moldoc-3.0.0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 13:56:36.781775 moldoc-3.0.0/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:36.773775 moldoc-3.0.0/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:36.777775 moldoc-3.0.0/src/moldoc/
+-rw-r--r--   0 runner    (1001) docker     (123)       63 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:36.777775 moldoc-3.0.0/src/moldoc/_internal/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/_internal/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:36.781775 moldoc-3.0.0/src/moldoc/_internal/javascript/
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/_internal/javascript/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1920 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/_internal/javascript/atoms.py
+-rw-r--r--   0 runner    (1001) docker     (123)      390 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/_internal/javascript/bonds.py
+-rw-r--r--   0 runner    (1001) docker     (123)       88 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/_internal/javascript/bool.py
+-rw-r--r--   0 runner    (1001) docker     (123)      297 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/_internal/javascript/color.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4078 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/_internal/javascript/material.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2846 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/_internal/javascript/mesh_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1001 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/_internal/javascript/scene_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)   351667 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/_internal/molDraw.js
+-rw-r--r--   0 runner    (1001) docker     (123)     4237 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/_internal/moldoc.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6217 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/_internal/molecule.py
+-rw-r--r--   0 runner    (1001) docker     (123)   551410 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/_internal/three.min.js
+-rw-r--r--   0 runner    (1001) docker     (123)      519 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/molecule.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:09.000000 moldoc-3.0.0/src/moldoc/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)      160 2023-06-28 13:56:36.000000 moldoc-3.0.0/src/moldoc/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:36.777775 moldoc-3.0.0/src/moldoc.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     6241 2023-06-28 13:56:36.000000 moldoc-3.0.0/src/moldoc.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1017 2023-06-28 13:56:36.000000 moldoc-3.0.0/src/moldoc.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:56:36.000000 moldoc-3.0.0/src/moldoc.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       62 2023-06-28 13:56:36.000000 moldoc-3.0.0/src/moldoc.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 13:56:36.000000 moldoc-3.0.0/src/moldoc.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:36.781775 moldoc-3.0.0/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      638 2023-06-28 13:56:09.000000 moldoc-3.0.0/tests/Makefile
+-rw-r--r--   0 runner    (1001) docker     (123)      799 2023-06-28 13:56:09.000000 moldoc-3.0.0/tests/make.bat
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:36.781775 moldoc-3.0.0/tests/source/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:36.781775 moldoc-3.0.0/tests/source/_static/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:56:09.000000 moldoc-3.0.0/tests/source/_static/empty
+-rw-r--r--   0 runner    (1001) docker     (123)     1993 2023-06-28 13:56:09.000000 moldoc-3.0.0/tests/source/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12186 2023-06-28 13:56:09.000000 moldoc-3.0.0/tests/source/index.rst
```

### Comparing `moldoc-2.0.0/.github/workflows/publish_release.yaml` & `moldoc-3.0.0/.github/workflows/publish_release.yaml`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/.github/workflows/tests.yaml` & `moldoc-3.0.0/.github/workflows/tests.yaml`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/LICENSE` & `moldoc-3.0.0/LICENSE`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/PKG-INFO` & `moldoc-3.0.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: moldoc
-Version: 2.0.0
+Version: 3.0.0
 Maintainer-email: Lukas Turcani <lukasturcani93@gmail.com>
 Project-URL: github, https://github.com/lukasturcani/moldoc
 Requires-Python: >=3.10
 Description-Content-Type: text/x-rst
 Provides-Extra: dev
 License-File: LICENSE
```

### Comparing `moldoc-2.0.0/README.rst` & `moldoc-3.0.0/README.rst`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/configuration.jpg` & `moldoc-3.0.0/configuration.jpg`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/moldoc.gif` & `moldoc-3.0.0/moldoc.gif`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/pyproject.toml` & `moldoc-3.0.0/pyproject.toml`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/src/moldoc/_internal/javascript/atoms.py` & `moldoc-3.0.0/src/moldoc/_internal/javascript/atoms.py`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/src/moldoc/_internal/javascript/material.py` & `moldoc-3.0.0/src/moldoc/_internal/javascript/material.py`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/src/moldoc/_internal/javascript/mesh_config.py` & `moldoc-3.0.0/src/moldoc/_internal/javascript/mesh_config.py`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/src/moldoc/_internal/javascript/scene_config.py` & `moldoc-3.0.0/src/moldoc/_internal/javascript/scene_config.py`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/src/moldoc/_internal/molDraw.js` & `moldoc-3.0.0/src/moldoc/_internal/molDraw.js`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/src/moldoc/_internal/moldoc.py` & `moldoc-3.0.0/src/moldoc/_internal/moldoc.py`

 * *Files 3% similar despite different names*

```diff
@@ -55,18 +55,18 @@
     else:
         molecule_config = default_molecule_config
 
     moldoc_node_id = node.get_moldoc_name()
 
     if not getattr(self, "moldoc_scripts_added", False):
         self.body.append(
-            '<script src="three.min.js"></script>'
-            '<script src="molDraw.js"></script>'
-            '<script src="../three.min.js"></script>'
-            '<script src="../molDraw.js"></script>'
+            '<script src="./_static/three.min.js"></script>'
+            '<script src="./_static/molDraw.js"></script>'
+            '<script src="../_static/three.min.js"></script>'
+            '<script src="../_static/molDraw.js"></script>'
             "<script>const md=molDraw;"
             "let atoms=[];"
             "let bonds=[];"
             "let maybeMolecule=undefined;"
             "</script>"
         )
         self.moldoc_scripts_added = True
```

### Comparing `moldoc-2.0.0/src/moldoc/_internal/molecule.py` & `moldoc-3.0.0/src/moldoc/_internal/molecule.py`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/src/moldoc/_internal/three.min.js` & `moldoc-3.0.0/src/moldoc/_internal/three.min.js`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/src/moldoc/molecule.py` & `moldoc-3.0.0/src/moldoc/molecule.py`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/src/moldoc.egg-info/PKG-INFO` & `moldoc-3.0.0/src/moldoc.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: moldoc
-Version: 2.0.0
+Version: 3.0.0
 Maintainer-email: Lukas Turcani <lukasturcani93@gmail.com>
 Project-URL: github, https://github.com/lukasturcani/moldoc
 Requires-Python: >=3.10
 Description-Content-Type: text/x-rst
 Provides-Extra: dev
 License-File: LICENSE
```

### Comparing `moldoc-2.0.0/src/moldoc.egg-info/SOURCES.txt` & `moldoc-3.0.0/src/moldoc.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/tests/Makefile` & `moldoc-3.0.0/tests/Makefile`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/tests/make.bat` & `moldoc-3.0.0/tests/make.bat`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/tests/source/conf.py` & `moldoc-3.0.0/tests/source/conf.py`

 * *Files identical despite different names*

### Comparing `moldoc-2.0.0/tests/source/index.rst` & `moldoc-3.0.0/tests/source/index.rst`

 * *Files identical despite different names*


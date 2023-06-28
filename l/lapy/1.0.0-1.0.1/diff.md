# Comparing `tmp/lapy-1.0.0.tar.gz` & `tmp/lapy-1.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "lapy-1.0.0.tar", last modified: Thu Jun 15 15:36:18 2023, max compression
+gzip compressed data, was "lapy-1.0.1.tar", last modified: Wed Jun 28 12:05:35 2023, max compression
```

## Comparing `lapy-1.0.0.tar` & `lapy-1.0.1.tar`

### file list

```diff
@@ -1,36 +1,36 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 15:36:18.305629 lapy-1.0.0/
--rw-r--r--   0 runner    (1001) docker     (123)     1093 2023-06-15 15:35:41.000000 lapy-1.0.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     6978 2023-06-15 15:36:18.305629 lapy-1.0.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     4431 2023-06-15 15:35:41.000000 lapy-1.0.0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 15:36:18.305629 lapy-1.0.0/lapy/
--rw-r--r--   0 runner    (1001) docker     (123)      229 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5836 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/_read_geometry.py
--rw-r--r--   0 runner    (1001) docker     (123)     6295 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/_tet_io.py
--rw-r--r--   0 runner    (1001) docker     (123)    16518 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/_tria_io.py
--rw-r--r--   0 runner    (1001) docker     (123)       98 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/_version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 15:36:18.305629 lapy-1.0.0/lapy/commands/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/commands/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      425 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/commands/sys_info.py
--rw-r--r--   0 runner    (1001) docker     (123)    16378 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/conformal.py
--rw-r--r--   0 runner    (1001) docker     (123)    24995 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/diffgeo.py
--rw-r--r--   0 runner    (1001) docker     (123)     4008 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/heat.py
--rw-r--r--   0 runner    (1001) docker     (123)     9885 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/io.py
--rw-r--r--   0 runner    (1001) docker     (123)    20764 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/plot.py
--rw-r--r--   0 runner    (1001) docker     (123)     4325 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/shapedna.py
--rw-r--r--   0 runner    (1001) docker     (123)    30701 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/solver.py
--rw-r--r--   0 runner    (1001) docker     (123)     9713 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/tet_mesh.py
--rw-r--r--   0 runner    (1001) docker     (123)    40528 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/tria_mesh.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 15:36:18.305629 lapy-1.0.0/lapy/utils/
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3620 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/utils/_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     1561 2023-06-15 15:35:41.000000 lapy-1.0.0/lapy/utils/_imports.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 15:36:18.305629 lapy-1.0.0/lapy.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     6978 2023-06-15 15:36:18.000000 lapy-1.0.0/lapy.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      559 2023-06-15 15:36:18.000000 lapy-1.0.0/lapy.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-15 15:36:18.000000 lapy-1.0.0/lapy.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       61 2023-06-15 15:36:18.000000 lapy-1.0.0/lapy.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)      404 2023-06-15 15:36:18.000000 lapy-1.0.0/lapy.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        5 2023-06-15 15:36:18.000000 lapy-1.0.0/lapy.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     3400 2023-06-15 15:35:41.000000 lapy-1.0.0/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-15 15:36:18.305629 lapy-1.0.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-15 15:35:41.000000 lapy-1.0.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:05:35.489940 lapy-1.0.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1093 2023-06-28 12:04:58.000000 lapy-1.0.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     6978 2023-06-28 12:05:35.485940 lapy-1.0.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4431 2023-06-28 12:04:58.000000 lapy-1.0.1/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:05:35.485940 lapy-1.0.1/lapy/
+-rw-r--r--   0 runner    (1001) docker     (123)      229 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5836 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/_read_geometry.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6295 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/_tet_io.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16518 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/_tria_io.py
+-rw-r--r--   0 runner    (1001) docker     (123)       98 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/_version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:05:35.485940 lapy-1.0.1/lapy/commands/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/commands/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      425 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/commands/sys_info.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16378 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/conformal.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24993 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/diffgeo.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4008 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/heat.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9885 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/io.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20764 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/plot.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4325 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/shapedna.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30701 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/solver.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9713 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/tet_mesh.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40528 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/tria_mesh.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:05:35.485940 lapy-1.0.1/lapy/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3620 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/utils/_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1561 2023-06-28 12:04:58.000000 lapy-1.0.1/lapy/utils/_imports.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:05:35.485940 lapy-1.0.1/lapy.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     6978 2023-06-28 12:05:35.000000 lapy-1.0.1/lapy.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      559 2023-06-28 12:05:35.000000 lapy-1.0.1/lapy.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:05:35.000000 lapy-1.0.1/lapy.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       61 2023-06-28 12:05:35.000000 lapy-1.0.1/lapy.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      440 2023-06-28 12:05:35.000000 lapy-1.0.1/lapy.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        5 2023-06-28 12:05:35.000000 lapy-1.0.1/lapy.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     3503 2023-06-28 12:04:58.000000 lapy-1.0.1/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 12:05:35.489940 lapy-1.0.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 12:04:58.000000 lapy-1.0.1/setup.py
```

### Comparing `lapy-1.0.0/LICENSE` & `lapy-1.0.1/LICENSE`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/PKG-INFO` & `lapy-1.0.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: lapy
-Version: 1.0.0
+Version: 1.0.1
 Summary: A package for differential geometry on meshes (Laplace, FEM)
 Author-email: Martin Reuter <martin.reuter@dzne.de>
 Maintainer-email: Martin Reuter <martin.reuter@dzne.de>
 License: MIT License
         
         Copyright (c) 2020 Deep Medical Imaging Lab (PI Reuter)
```

### Comparing `lapy-1.0.0/README.md` & `lapy-1.0.1/README.md`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/lapy/_read_geometry.py` & `lapy-1.0.1/lapy/_read_geometry.py`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/lapy/_tet_io.py` & `lapy-1.0.1/lapy/_tet_io.py`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/lapy/_tria_io.py` & `lapy-1.0.1/lapy/_tria_io.py`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/lapy/conformal.py` & `lapy-1.0.1/lapy/conformal.py`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/lapy/diffgeo.py` & `lapy-1.0.1/lapy/diffgeo.py`

 * *Files 0% similar despite different names*

```diff
@@ -507,17 +507,17 @@
         data["Creator"] = "spherically_project.py"
         data["Refine"] = 0
         data["Degree"] = 1
         data["Dimension"] = 2
         data["Elements"] = tria.t.shape[0]
         data["DoF"] = evecs.shape[0]
         data["NumEW"] = 4
-        from .io import export_ev
+        from .io import write_ev
 
-        export_ev(data, "debug.ev")
+        write_ev(data, "debug.ev")
 
     # flip efuncs to align to coordinates consistently
     ev1 = evecs[:, 1]
     # ev1maxi = np.argmax(ev1)
     # ev1mini = np.argmin(ev1)
     # cmax = v[ev1maxi,:]
     # cmin = v[ev1mini,:]
```

### Comparing `lapy-1.0.0/lapy/heat.py` & `lapy-1.0.1/lapy/heat.py`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/lapy/io.py` & `lapy-1.0.1/lapy/io.py`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/lapy/plot.py` & `lapy-1.0.1/lapy/plot.py`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/lapy/shapedna.py` & `lapy-1.0.1/lapy/shapedna.py`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/lapy/solver.py` & `lapy-1.0.1/lapy/solver.py`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/lapy/tet_mesh.py` & `lapy-1.0.1/lapy/tet_mesh.py`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/lapy/tria_mesh.py` & `lapy-1.0.1/lapy/tria_mesh.py`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/lapy/utils/_config.py` & `lapy-1.0.1/lapy/utils/_config.py`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/lapy/utils/_imports.py` & `lapy-1.0.1/lapy/utils/_imports.py`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/lapy.egg-info/PKG-INFO` & `lapy-1.0.1/lapy.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: lapy
-Version: 1.0.0
+Version: 1.0.1
 Summary: A package for differential geometry on meshes (Laplace, FEM)
 Author-email: Martin Reuter <martin.reuter@dzne.de>
 Maintainer-email: Martin Reuter <martin.reuter@dzne.de>
 License: MIT License
         
         Copyright (c) 2020 Deep Medical Imaging Lab (PI Reuter)
```

### Comparing `lapy-1.0.0/lapy.egg-info/SOURCES.txt` & `lapy-1.0.1/lapy.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `lapy-1.0.0/pyproject.toml` & `lapy-1.0.1/pyproject.toml`

 * *Files 3% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ['setuptools >= 61.0.0']
 build-backend = 'setuptools.build_meta'
 
 [project]
 name = 'lapy'
-version = '1.0.0'
+version = '1.0.1'
 description = 'A package for differential geometry on meshes (Laplace, FEM)'
 readme = 'README.md'
 license = {file = 'LICENSE'}
 requires-python = '>=3.8'
 authors = [
     {name = 'Martin Reuter', email = 'martin.reuter@dzne.de'},
 ]
@@ -62,14 +62,18 @@
     'numpydoc',
     'sphinx',
     'sphinxcontrib-bibtex',
     'sphinx-copybutton',
     'sphinx-design',
     'sphinx-gallery',
     'sphinx-issues',
+    'pypandoc',
+    'nbsphinx',
+    'IPython', # For syntax highlighting in notebooks
+    'ipykernel',
 ]
 style = [
     'bibclean',
     'black',
     'codespell',
     'isort',
     'pydocstyle[toml]',
```


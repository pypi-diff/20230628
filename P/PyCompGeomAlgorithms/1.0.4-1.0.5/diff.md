# Comparing `tmp/PyCompGeomAlgorithms-1.0.4.tar.gz` & `tmp/PyCompGeomAlgorithms-1.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "PyCompGeomAlgorithms-1.0.4.tar", last modified: Tue Jun 27 08:37:52 2023, max compression
+gzip compressed data, was "PyCompGeomAlgorithms-1.0.5.tar", last modified: Wed Jun 28 07:33:29 2023, max compression
```

## Comparing `PyCompGeomAlgorithms-1.0.4.tar` & `PyCompGeomAlgorithms-1.0.5.tar`

### file list

```diff
@@ -1,32 +1,32 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 08:37:52.349270 PyCompGeomAlgorithms-1.0.4/
--rw-rw-rw-   0        0        0     1104 2023-06-22 11:36:14.000000 PyCompGeomAlgorithms-1.0.4/LICENSE
--rw-rw-rw-   0        0        0      480 2023-06-27 08:37:52.346269 PyCompGeomAlgorithms-1.0.4/PKG-INFO
-drwxrwxrwx   0        0        0        0 2023-06-27 08:37:52.264270 PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms/
--rw-rw-rw-   0        0        0        0 2023-06-22 07:54:06.000000 PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms/__init__.py
--rw-rw-rw-   0        0        0    11303 2023-06-27 08:22:07.000000 PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms/core.py
--rw-rw-rw-   0        0        0     1918 2023-06-27 08:27:25.000000 PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms/graham.py
--rw-rw-rw-   0        0        0      920 2023-06-22 10:15:40.000000 PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms/jarvis.py
--rw-rw-rw-   0        0        0     2536 2023-06-22 08:22:43.000000 PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms/kd_tree.py
--rw-rw-rw-   0        0        0     2762 2023-06-27 08:36:35.000000 PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms/preparata.py
--rw-rw-rw-   0        0        0     2359 2023-06-27 08:34:18.000000 PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms/quickhull.py
-drwxrwxrwx   0        0        0        0 2023-06-27 08:37:52.304268 PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms.egg-info/
--rw-rw-rw-   0        0        0      480 2023-06-27 08:37:52.000000 PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      714 2023-06-27 08:37:52.000000 PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 08:37:52.000000 PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       27 2023-06-27 08:37:52.000000 PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     2199 2023-06-22 12:13:13.000000 PyCompGeomAlgorithms-1.0.4/README.md
--rw-rw-rw-   0        0        0       88 2023-06-22 19:12:11.000000 PyCompGeomAlgorithms-1.0.4/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-27 08:37:52.352268 PyCompGeomAlgorithms-1.0.4/setup.cfg
--rw-rw-rw-   0        0        0      702 2023-06-27 08:36:47.000000 PyCompGeomAlgorithms-1.0.4/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-27 08:37:52.307268 PyCompGeomAlgorithms-1.0.4/tests/
--rw-rw-rw-   0        0        0        0 2023-06-22 07:57:15.000000 PyCompGeomAlgorithms-1.0.4/tests/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-27 08:37:52.335268 PyCompGeomAlgorithms-1.0.4/tests/algorithms/
--rw-rw-rw-   0        0        0        0 2023-06-22 07:57:09.000000 PyCompGeomAlgorithms-1.0.4/tests/algorithms/__init__.py
--rw-rw-rw-   0        0        0     4573 2023-06-27 08:07:17.000000 PyCompGeomAlgorithms-1.0.4/tests/algorithms/test_graham.py
--rw-rw-rw-   0        0        0      605 2023-06-26 14:33:11.000000 PyCompGeomAlgorithms-1.0.4/tests/algorithms/test_jarvis.py
--rw-rw-rw-   0        0        0     2521 2023-06-27 08:19:04.000000 PyCompGeomAlgorithms-1.0.4/tests/algorithms/test_kd_tree.py
--rw-rw-rw-   0        0        0     3424 2023-06-27 08:19:50.000000 PyCompGeomAlgorithms-1.0.4/tests/algorithms/test_preparata.py
--rw-rw-rw-   0        0        0     3304 2023-06-27 08:34:51.000000 PyCompGeomAlgorithms-1.0.4/tests/algorithms/test_quickhull.py
-drwxrwxrwx   0        0        0        0 2023-06-27 08:37:52.341269 PyCompGeomAlgorithms-1.0.4/tests/entities/
--rw-rw-rw-   0        0        0        0 2023-06-26 14:32:45.000000 PyCompGeomAlgorithms-1.0.4/tests/entities/__init__.py
--rw-rw-rw-   0        0        0     1866 2023-06-26 14:32:52.000000 PyCompGeomAlgorithms-1.0.4/tests/entities/test_entities.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:33:29.361939 PyCompGeomAlgorithms-1.0.5/
+-rw-rw-rw-   0        0        0     1104 2023-06-22 11:36:14.000000 PyCompGeomAlgorithms-1.0.5/LICENSE
+-rw-rw-rw-   0        0        0      480 2023-06-28 07:33:29.355666 PyCompGeomAlgorithms-1.0.5/PKG-INFO
+drwxrwxrwx   0        0        0        0 2023-06-28 07:33:29.250991 PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms/
+-rw-rw-rw-   0        0        0        0 2023-06-22 07:54:06.000000 PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms/__init__.py
+-rw-rw-rw-   0        0        0    11303 2023-06-27 08:22:07.000000 PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms/core.py
+-rw-rw-rw-   0        0        0     2757 2023-06-28 07:31:28.000000 PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms/graham.py
+-rw-rw-rw-   0        0        0      920 2023-06-22 10:15:40.000000 PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms/jarvis.py
+-rw-rw-rw-   0        0        0     2536 2023-06-22 08:22:43.000000 PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms/kd_tree.py
+-rw-rw-rw-   0        0        0     2762 2023-06-27 08:36:35.000000 PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms/preparata.py
+-rw-rw-rw-   0        0        0     2359 2023-06-27 08:34:18.000000 PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms/quickhull.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:33:29.315524 PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms.egg-info/
+-rw-rw-rw-   0        0        0      480 2023-06-28 07:33:29.000000 PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      714 2023-06-28 07:33:29.000000 PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 07:33:29.000000 PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       27 2023-06-28 07:33:29.000000 PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     2199 2023-06-22 12:13:13.000000 PyCompGeomAlgorithms-1.0.5/README.md
+-rw-rw-rw-   0        0        0       88 2023-06-22 19:12:11.000000 PyCompGeomAlgorithms-1.0.5/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 07:33:29.364219 PyCompGeomAlgorithms-1.0.5/setup.cfg
+-rw-rw-rw-   0        0        0      702 2023-06-28 07:33:08.000000 PyCompGeomAlgorithms-1.0.5/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:33:29.321718 PyCompGeomAlgorithms-1.0.5/tests/
+-rw-rw-rw-   0        0        0        0 2023-06-22 07:57:15.000000 PyCompGeomAlgorithms-1.0.5/tests/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:33:29.345378 PyCompGeomAlgorithms-1.0.5/tests/algorithms/
+-rw-rw-rw-   0        0        0        0 2023-06-22 07:57:09.000000 PyCompGeomAlgorithms-1.0.5/tests/algorithms/__init__.py
+-rw-rw-rw-   0        0        0     4573 2023-06-27 08:07:17.000000 PyCompGeomAlgorithms-1.0.5/tests/algorithms/test_graham.py
+-rw-rw-rw-   0        0        0      605 2023-06-26 14:33:11.000000 PyCompGeomAlgorithms-1.0.5/tests/algorithms/test_jarvis.py
+-rw-rw-rw-   0        0        0     2521 2023-06-27 08:19:04.000000 PyCompGeomAlgorithms-1.0.5/tests/algorithms/test_kd_tree.py
+-rw-rw-rw-   0        0        0     3424 2023-06-27 08:19:50.000000 PyCompGeomAlgorithms-1.0.5/tests/algorithms/test_preparata.py
+-rw-rw-rw-   0        0        0     3304 2023-06-27 08:34:51.000000 PyCompGeomAlgorithms-1.0.5/tests/algorithms/test_quickhull.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:33:29.350535 PyCompGeomAlgorithms-1.0.5/tests/entities/
+-rw-rw-rw-   0        0        0        0 2023-06-26 14:32:45.000000 PyCompGeomAlgorithms-1.0.5/tests/entities/__init__.py
+-rw-rw-rw-   0        0        0     1866 2023-06-26 14:32:52.000000 PyCompGeomAlgorithms-1.0.5/tests/entities/test_entities.py
```

### Comparing `PyCompGeomAlgorithms-1.0.4/LICENSE` & `PyCompGeomAlgorithms-1.0.5/LICENSE`

 * *Files identical despite different names*

### Comparing `PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms/core.py` & `PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms/core.py`

 * *Files identical despite different names*

### Comparing `PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms/jarvis.py` & `PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms/jarvis.py`

 * *Files identical despite different names*

### Comparing `PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms/kd_tree.py` & `PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms/kd_tree.py`

 * *Files identical despite different names*

### Comparing `PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms/preparata.py` & `PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms/preparata.py`

 * *Files identical despite different names*

### Comparing `PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms/quickhull.py` & `PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms/quickhull.py`

 * *Files identical despite different names*

### Comparing `PyCompGeomAlgorithms-1.0.4/PyCompGeomAlgorithms.egg-info/SOURCES.txt` & `PyCompGeomAlgorithms-1.0.5/PyCompGeomAlgorithms.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `PyCompGeomAlgorithms-1.0.4/README.md` & `PyCompGeomAlgorithms-1.0.5/README.md`

 * *Files identical despite different names*

### Comparing `PyCompGeomAlgorithms-1.0.4/setup.py` & `PyCompGeomAlgorithms-1.0.5/setup.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from setuptools import setup, find_packages
 
 
 setup(
     name="PyCompGeomAlgorithms",
-    version="1.0.4",
+    version="1.0.5",
     author="artandfi (Artem Fisunenko)",
     author_email="artyom.fisunenko@gmail.com",
     description="An implementation of computational geometry algorithms in Python3.",
     packages=find_packages(),
     keywords=[
         "Python3",
         "computational geometry",
```

### Comparing `PyCompGeomAlgorithms-1.0.4/tests/algorithms/test_graham.py` & `PyCompGeomAlgorithms-1.0.5/tests/algorithms/test_graham.py`

 * *Files identical despite different names*

### Comparing `PyCompGeomAlgorithms-1.0.4/tests/algorithms/test_jarvis.py` & `PyCompGeomAlgorithms-1.0.5/tests/algorithms/test_jarvis.py`

 * *Files identical despite different names*

### Comparing `PyCompGeomAlgorithms-1.0.4/tests/algorithms/test_kd_tree.py` & `PyCompGeomAlgorithms-1.0.5/tests/algorithms/test_kd_tree.py`

 * *Files identical despite different names*

### Comparing `PyCompGeomAlgorithms-1.0.4/tests/algorithms/test_preparata.py` & `PyCompGeomAlgorithms-1.0.5/tests/algorithms/test_preparata.py`

 * *Files identical despite different names*

### Comparing `PyCompGeomAlgorithms-1.0.4/tests/algorithms/test_quickhull.py` & `PyCompGeomAlgorithms-1.0.5/tests/algorithms/test_quickhull.py`

 * *Files identical despite different names*

### Comparing `PyCompGeomAlgorithms-1.0.4/tests/entities/test_entities.py` & `PyCompGeomAlgorithms-1.0.5/tests/entities/test_entities.py`

 * *Files identical despite different names*


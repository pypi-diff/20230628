# Comparing `tmp/pytest-group-by-class-0.1.3.tar.gz` & `tmp/pytest-group-by-class-0.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pytest-group-by-class-0.1.3.tar", last modified: Tue Jun 27 20:54:04 2023, max compression
+gzip compressed data, was "pytest-group-by-class-0.1.4.tar", last modified: Tue Jun 27 21:28:15 2023, max compression
```

## Comparing `pytest-group-by-class-0.1.3.tar` & `pytest-group-by-class-0.1.4.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxr-xr-x   0 work       (502) staff       (20)        0 2023-06-27 20:54:04.493092 pytest-group-by-class-0.1.3/
--rw-r--r--   0 work       (502) staff       (20)     1739 2023-06-27 20:54:04.492971 pytest-group-by-class-0.1.3/PKG-INFO
--rw-r--r--   0 work       (502) staff       (20)      974 2023-06-27 16:00:39.000000 pytest-group-by-class-0.1.3/README.md
-drwxr-xr-x   0 work       (502) staff       (20)        0 2023-06-27 20:54:04.492040 pytest-group-by-class-0.1.3/pytest_group_by_class/
--rw-r--r--   0 work       (502) staff       (20)     2722 2023-06-26 10:59:58.000000 pytest-group-by-class-0.1.3/pytest_group_by_class/__init__.py
-drwxr-xr-x   0 work       (502) staff       (20)        0 2023-06-27 20:54:04.492803 pytest-group-by-class-0.1.3/pytest_group_by_class.egg-info/
--rw-r--r--   0 work       (502) staff       (20)     1739 2023-06-27 20:54:04.000000 pytest-group-by-class-0.1.3/pytest_group_by_class.egg-info/PKG-INFO
--rw-r--r--   0 work       (502) staff       (20)      324 2023-06-27 20:54:04.000000 pytest-group-by-class-0.1.3/pytest_group_by_class.egg-info/SOURCES.txt
--rw-r--r--   0 work       (502) staff       (20)        1 2023-06-27 20:54:04.000000 pytest-group-by-class-0.1.3/pytest_group_by_class.egg-info/dependency_links.txt
--rw-r--r--   0 work       (502) staff       (20)       47 2023-06-27 20:54:04.000000 pytest-group-by-class-0.1.3/pytest_group_by_class.egg-info/entry_points.txt
--rw-r--r--   0 work       (502) staff       (20)       12 2023-06-27 20:54:04.000000 pytest-group-by-class-0.1.3/pytest_group_by_class.egg-info/requires.txt
--rw-r--r--   0 work       (502) staff       (20)       22 2023-06-27 20:54:04.000000 pytest-group-by-class-0.1.3/pytest_group_by_class.egg-info/top_level.txt
--rw-r--r--   0 work       (502) staff       (20)       38 2023-06-27 20:54:04.493131 pytest-group-by-class-0.1.3/setup.cfg
--rw-r--r--   0 work       (502) staff       (20)     1332 2023-06-27 20:54:02.000000 pytest-group-by-class-0.1.3/setup.py
+drwxr-xr-x   0 work       (502) staff       (20)        0 2023-06-27 21:28:15.817719 pytest-group-by-class-0.1.4/
+-rw-r--r--   0 work       (502) staff       (20)     1739 2023-06-27 21:28:15.817601 pytest-group-by-class-0.1.4/PKG-INFO
+-rw-r--r--   0 work       (502) staff       (20)      974 2023-06-27 16:00:39.000000 pytest-group-by-class-0.1.4/README.md
+drwxr-xr-x   0 work       (502) staff       (20)        0 2023-06-27 21:28:15.816419 pytest-group-by-class-0.1.4/pytest_group_by_class/
+-rw-r--r--   0 work       (502) staff       (20)     2905 2023-06-27 21:26:57.000000 pytest-group-by-class-0.1.4/pytest_group_by_class/__init__.py
+drwxr-xr-x   0 work       (502) staff       (20)        0 2023-06-27 21:28:15.817443 pytest-group-by-class-0.1.4/pytest_group_by_class.egg-info/
+-rw-r--r--   0 work       (502) staff       (20)     1739 2023-06-27 21:28:15.000000 pytest-group-by-class-0.1.4/pytest_group_by_class.egg-info/PKG-INFO
+-rw-r--r--   0 work       (502) staff       (20)      324 2023-06-27 21:28:15.000000 pytest-group-by-class-0.1.4/pytest_group_by_class.egg-info/SOURCES.txt
+-rw-r--r--   0 work       (502) staff       (20)        1 2023-06-27 21:28:15.000000 pytest-group-by-class-0.1.4/pytest_group_by_class.egg-info/dependency_links.txt
+-rw-r--r--   0 work       (502) staff       (20)       47 2023-06-27 21:28:15.000000 pytest-group-by-class-0.1.4/pytest_group_by_class.egg-info/entry_points.txt
+-rw-r--r--   0 work       (502) staff       (20)       12 2023-06-27 21:28:15.000000 pytest-group-by-class-0.1.4/pytest_group_by_class.egg-info/requires.txt
+-rw-r--r--   0 work       (502) staff       (20)       22 2023-06-27 21:28:15.000000 pytest-group-by-class-0.1.4/pytest_group_by_class.egg-info/top_level.txt
+-rw-r--r--   0 work       (502) staff       (20)       38 2023-06-27 21:28:15.817757 pytest-group-by-class-0.1.4/setup.cfg
+-rw-r--r--   0 work       (502) staff       (20)     1332 2023-06-27 21:28:12.000000 pytest-group-by-class-0.1.4/setup.py
```

### Comparing `pytest-group-by-class-0.1.3/PKG-INFO` & `pytest-group-by-class-0.1.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pytest-group-by-class
-Version: 0.1.3
+Version: 0.1.4
 Summary: A Pytest plugin for running a subset of your tests by splitting them in to groups of classes.
 Home-page: https://github.com/marco-mn/pytest-group-by-class
 Author: marco-mn
 Author-email: snoopy@peanuts.com
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `pytest-group-by-class-0.1.3/README.md` & `pytest-group-by-class-0.1.4/README.md`

 * *Files identical despite different names*

### Comparing `pytest-group-by-class-0.1.3/pytest_group_by_class/__init__.py` & `pytest-group-by-class-0.1.4/pytest_group_by_class/__init__.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,20 +1,20 @@
 # -*- coding: utf-8 -*-
 import argparse
 from _pytest.config import create_terminal_writer
 
 
 def get_group(class_test_map, group_id, group_name):
     """Get the items from the passed in group based on group count."""
-    if group_id:
+    if group_id is not None:
         for cls in class_test_map:
-            if class_test_map[cls]["index"] == group_id:
+            if class_test_map[cls]["index"] == int(group_id):
                 return class_test_map[cls]["items"]
         raise ValueError("Invalid test-group-class-id argument")
-    if group_name:
+    if group_name is not None:
         for cls in class_test_map:
             if cls == group_name:
                 return class_test_map[cls]["items"]
         raise ValueError("Invalid test-group-class-name argument")
 
 
 def pytest_addoption(parser):
@@ -31,40 +31,42 @@
     data = {}
     counter = 0
     for i in items:
         test_class = i.parent.name
         if test_class not in data:
             data[test_class] = {
                 "index": counter,
-                "item   s": [i]
+                "items": [i]
             }
             counter += 1
         else:
             data[test_class]["items"].append(i)
+    print("\n")
     for cls in data:
-        print(f"{cls}:{data[cls]}")
+        print(f"Class {cls} has index {data[cls]['index']}")
     return data
 
 
 def pytest_collection_modifyitems(config, items):
     group_class = config.getoption('test-group-class')
     group_id = config.getoption('test-group-class-id')
     group_name = config.getoption('test-group-class-name')
     if group_class:
-        if not group_id and not group_name:
+        if group_id is not None and group_name is not None:
             raise ValueError("--test-group-class-id or --test-group-class-name must be specified")
         if group_id and group_name:
             raise ValueError("--test-group-class-id or --test-group-class-name cannot be both specified")
     else:
         return
     class_test_map = collect_classes(items)
     items[:] = get_group(class_test_map, group_id, group_name)
     terminal_reporter = config.pluginmanager.get_plugin('terminalreporter')
     terminal_writer = create_terminal_writer(config)
     message = terminal_writer.markup(
-        'Running test group by class #{0} ({1} tests)\n'.format(
-            group_id,
+        'Running test group by class {0} {1} ({2} tests)\n'.format(
+            "index" if group_id is not None else "name",
+            group_id if group_id is not None else group_name,
             len(items)
         ),
         yellow=True
     )
     terminal_reporter.write(message)
```

### Comparing `pytest-group-by-class-0.1.3/pytest_group_by_class.egg-info/PKG-INFO` & `pytest-group-by-class-0.1.4/pytest_group_by_class.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pytest-group-by-class
-Version: 0.1.3
+Version: 0.1.4
 Summary: A Pytest plugin for running a subset of your tests by splitting them in to groups of classes.
 Home-page: https://github.com/marco-mn/pytest-group-by-class
 Author: marco-mn
 Author-email: snoopy@peanuts.com
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `pytest-group-by-class-0.1.3/setup.py` & `pytest-group-by-class-0.1.4/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -13,15 +13,15 @@
     name="pytest-group-by-class",
     description=('A Pytest plugin for running a subset of your tests by '
                  'splitting them in to groups of classes.'),
     url='https://github.com/marco-mn/pytest-group-by-class',
     author='marco-mn',
     author_email='snoopy@peanuts.com',
     packages=['pytest_group_by_class'],
-    version='0.1.3',
+    version='0.1.4',
     long_description=read('README.md'),
     long_description_content_type="text/markdown",
     install_requires=['pytest>=2.5'],
     classifiers=['Development Status :: 5 - Production/Stable',
                  'Intended Audience :: Developers',
                  'License :: OSI Approved :: MIT License',
                  'Operating System :: OS Independent',
```


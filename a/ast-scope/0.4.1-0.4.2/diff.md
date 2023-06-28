# Comparing `tmp/ast_scope-0.4.1.tar.gz` & `tmp/ast_scope-0.4.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ast_scope-0.4.1.tar", last modified: Wed Jun 21 06:00:42 2023, max compression
+gzip compressed data, was "ast_scope-0.4.2.tar", last modified: Wed Jun 28 01:20:30 2023, max compression
```

## Comparing `ast_scope-0.4.1.tar` & `ast_scope-0.4.2.tar`

### file list

```diff
@@ -1,35 +1,35 @@
-drwxrwxr-x   0 kavi      (1000) kavi      (1000)        0 2023-06-21 06:00:42.886938 ast_scope-0.4.1/
--rw-rw-r--   0 kavi      (1000) kavi      (1000)    34502 2023-05-17 22:53:45.000000 ast_scope-0.4.1/LICENSE
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     3809 2023-06-21 06:00:42.886938 ast_scope-0.4.1/PKG-INFO
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     2360 2023-05-17 22:53:45.000000 ast_scope-0.4.1/README.md
-drwxrwxr-x   0 kavi      (1000) kavi      (1000)        0 2023-06-21 06:00:42.882938 ast_scope-0.4.1/ast_scope/
--rw-rw-r--   0 kavi      (1000) kavi      (1000)       31 2023-06-13 01:00:15.000000 ast_scope-0.4.1/ast_scope/__init__.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     2468 2023-06-13 06:23:11.000000 ast_scope-0.4.1/ast_scope/annotate.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     7848 2023-06-13 06:26:29.000000 ast_scope-0.4.1/ast_scope/annotator.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)      720 2023-06-13 01:00:15.000000 ast_scope-0.4.1/ast_scope/graph.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     1176 2023-06-13 01:00:15.000000 ast_scope-0.4.1/ast_scope/group_similar_constructs.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     3507 2023-06-13 18:35:03.000000 ast_scope-0.4.1/ast_scope/pull_scope.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     2722 2023-06-21 06:00:17.000000 ast_scope-0.4.1/ast_scope/scope.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     1090 2023-06-13 01:00:15.000000 ast_scope-0.4.1/ast_scope/utils.py
-drwxrwxr-x   0 kavi      (1000) kavi      (1000)        0 2023-06-21 06:00:42.882938 ast_scope-0.4.1/ast_scope.egg-info/
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     3809 2023-06-21 06:00:42.000000 ast_scope-0.4.1/ast_scope.egg-info/PKG-INFO
--rw-rw-r--   0 kavi      (1000) kavi      (1000)      709 2023-06-21 06:00:42.000000 ast_scope-0.4.1/ast_scope.egg-info/SOURCES.txt
--rw-rw-r--   0 kavi      (1000) kavi      (1000)        1 2023-06-21 06:00:42.000000 ast_scope-0.4.1/ast_scope.egg-info/dependency_links.txt
--rw-rw-r--   0 kavi      (1000) kavi      (1000)       14 2023-06-21 06:00:42.000000 ast_scope-0.4.1/ast_scope.egg-info/requires.txt
--rw-rw-r--   0 kavi      (1000) kavi      (1000)       16 2023-06-21 06:00:42.000000 ast_scope-0.4.1/ast_scope.egg-info/top_level.txt
--rw-rw-r--   0 kavi      (1000) kavi      (1000)       79 2023-06-21 06:00:42.886938 ast_scope-0.4.1/setup.cfg
--rw-rw-r--   0 kavi      (1000) kavi      (1000)      929 2023-06-21 06:00:22.000000 ast_scope-0.4.1/setup.py
-drwxrwxr-x   0 kavi      (1000) kavi      (1000)        0 2023-06-21 06:00:42.886938 ast_scope-0.4.1/tests/
--rw-rw-r--   0 kavi      (1000) kavi      (1000)        0 2023-05-17 22:53:45.000000 ast_scope-0.4.1/tests/__init__.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     2322 2023-05-17 22:53:45.000000 ast_scope-0.4.1/tests/argument_tests.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     2985 2023-05-17 22:53:45.000000 ast_scope-0.4.1/tests/assignment_tests.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)      590 2023-05-17 22:53:45.000000 ast_scope-0.4.1/tests/basic_scope_tests.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     3693 2023-05-17 22:53:45.000000 ast_scope-0.4.1/tests/class_tests.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     2501 2023-05-17 22:53:45.000000 ast_scope-0.4.1/tests/comprehension_tests.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     2733 2023-05-17 22:53:45.000000 ast_scope-0.4.1/tests/dependency_graph_tests.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)      356 2023-06-13 06:26:41.000000 ast_scope-0.4.1/tests/exception_tests.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     3187 2023-05-17 22:53:45.000000 ast_scope-0.4.1/tests/function_frame_tests.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     1057 2023-05-17 22:53:45.000000 ast_scope-0.4.1/tests/lambda_test.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     2620 2023-05-17 22:53:45.000000 ast_scope-0.4.1/tests/nonlocal_tests.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)      242 2023-05-17 22:53:45.000000 ast_scope-0.4.1/tests/special_symbols_tests.py
--rw-rw-r--   0 kavi      (1000) kavi      (1000)     5014 2023-05-17 22:53:45.000000 ast_scope-0.4.1/tests/utils.py
+drwxrwxr-x   0 kavi      (1000) kavi      (1000)        0 2023-06-28 01:20:30.774060 ast_scope-0.4.2/
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)    34502 2023-05-17 22:53:45.000000 ast_scope-0.4.2/LICENSE
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     3809 2023-06-28 01:20:30.774060 ast_scope-0.4.2/PKG-INFO
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     2360 2023-05-17 22:53:45.000000 ast_scope-0.4.2/README.md
+drwxrwxr-x   0 kavi      (1000) kavi      (1000)        0 2023-06-28 01:20:30.770060 ast_scope-0.4.2/ast_scope/
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)       31 2023-06-13 01:00:15.000000 ast_scope-0.4.2/ast_scope/__init__.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     2545 2023-06-28 01:19:57.000000 ast_scope-0.4.2/ast_scope/annotate.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     7848 2023-06-13 06:26:29.000000 ast_scope-0.4.2/ast_scope/annotator.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)      720 2023-06-13 01:00:15.000000 ast_scope-0.4.2/ast_scope/graph.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     1176 2023-06-13 01:00:15.000000 ast_scope-0.4.2/ast_scope/group_similar_constructs.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     3507 2023-06-13 18:35:03.000000 ast_scope-0.4.2/ast_scope/pull_scope.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     2722 2023-06-27 23:48:16.000000 ast_scope-0.4.2/ast_scope/scope.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     1090 2023-06-13 01:00:15.000000 ast_scope-0.4.2/ast_scope/utils.py
+drwxrwxr-x   0 kavi      (1000) kavi      (1000)        0 2023-06-28 01:20:30.770060 ast_scope-0.4.2/ast_scope.egg-info/
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     3809 2023-06-28 01:20:30.000000 ast_scope-0.4.2/ast_scope.egg-info/PKG-INFO
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)      709 2023-06-28 01:20:30.000000 ast_scope-0.4.2/ast_scope.egg-info/SOURCES.txt
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)        1 2023-06-28 01:20:30.000000 ast_scope-0.4.2/ast_scope.egg-info/dependency_links.txt
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)       14 2023-06-28 01:20:30.000000 ast_scope-0.4.2/ast_scope.egg-info/requires.txt
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)       16 2023-06-28 01:20:30.000000 ast_scope-0.4.2/ast_scope.egg-info/top_level.txt
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)       79 2023-06-28 01:20:30.774060 ast_scope-0.4.2/setup.cfg
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)      917 2023-06-28 01:20:16.000000 ast_scope-0.4.2/setup.py
+drwxrwxr-x   0 kavi      (1000) kavi      (1000)        0 2023-06-28 01:20:30.774060 ast_scope-0.4.2/tests/
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)        0 2023-05-17 22:53:45.000000 ast_scope-0.4.2/tests/__init__.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     2322 2023-05-17 22:53:45.000000 ast_scope-0.4.2/tests/argument_tests.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     2985 2023-05-17 22:53:45.000000 ast_scope-0.4.2/tests/assignment_tests.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)      590 2023-05-17 22:53:45.000000 ast_scope-0.4.2/tests/basic_scope_tests.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     3693 2023-05-17 22:53:45.000000 ast_scope-0.4.2/tests/class_tests.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     2501 2023-05-17 22:53:45.000000 ast_scope-0.4.2/tests/comprehension_tests.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     2733 2023-05-17 22:53:45.000000 ast_scope-0.4.2/tests/dependency_graph_tests.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)      356 2023-06-13 06:26:41.000000 ast_scope-0.4.2/tests/exception_tests.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     3187 2023-05-17 22:53:45.000000 ast_scope-0.4.2/tests/function_frame_tests.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     1057 2023-05-17 22:53:45.000000 ast_scope-0.4.2/tests/lambda_test.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     2620 2023-05-17 22:53:45.000000 ast_scope-0.4.2/tests/nonlocal_tests.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)      242 2023-05-17 22:53:45.000000 ast_scope-0.4.2/tests/special_symbols_tests.py
+-rw-rw-r--   0 kavi      (1000) kavi      (1000)     5014 2023-05-17 22:53:45.000000 ast_scope-0.4.2/tests/utils.py
```

### Comparing `ast_scope-0.4.1/LICENSE` & `ast_scope-0.4.2/LICENSE`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/PKG-INFO` & `ast_scope-0.4.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ast_scope
-Version: 0.4.1
+Version: 0.4.2
 Summary: Annotates a Python AST with the scope of symbols.
 Home-page: https://github.com/kavigupta/ast_scope
 Author: Kavi Gupta
 Author-email: ast_scope@kavigupta.org
 License: UNKNOWN
 Download-URL: https://github.com/kavigupta/ast_scope/archive/0.3.1.zip
 Description:
```

### Comparing `ast_scope-0.4.1/README.md` & `ast_scope-0.4.2/README.md`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/ast_scope/annotate.py` & `ast_scope-0.4.2/ast_scope/annotate.py`

 * *Files 5% similar despite different names*

```diff
@@ -35,14 +35,17 @@
                 if node not in self:
                     continue
                 if self[node] is not self._global_scope:
                     continue
                 g.add_edge(get_name(construct), get_name(node))
         return g
 
+    def __iter__(self):
+        return iter(self._node_to_containing_scope)
+
     def __contains__(self, node):
         return node in self._node_to_containing_scope
 
     def __getitem__(self, node):
         return self._node_to_containing_scope[node]
 
     def function_scope_for(self, node):
```

### Comparing `ast_scope-0.4.1/ast_scope/annotator.py` & `ast_scope-0.4.2/ast_scope/annotator.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/ast_scope/graph.py` & `ast_scope-0.4.2/ast_scope/graph.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/ast_scope/group_similar_constructs.py` & `ast_scope-0.4.2/ast_scope/group_similar_constructs.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/ast_scope/pull_scope.py` & `ast_scope-0.4.2/ast_scope/pull_scope.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/ast_scope/scope.py` & `ast_scope-0.4.2/ast_scope/scope.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/ast_scope/utils.py` & `ast_scope-0.4.2/ast_scope/utils.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/ast_scope.egg-info/PKG-INFO` & `ast_scope-0.4.2/ast_scope.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ast-scope
-Version: 0.4.1
+Version: 0.4.2
 Summary: Annotates a Python AST with the scope of symbols.
 Home-page: https://github.com/kavigupta/ast_scope
 Author: Kavi Gupta
 Author-email: ast_scope@kavigupta.org
 License: UNKNOWN
 Download-URL: https://github.com/kavigupta/ast_scope/archive/0.3.1.zip
 Description:
```

### Comparing `ast_scope-0.4.1/ast_scope.egg-info/SOURCES.txt` & `ast_scope-0.4.2/ast_scope.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/setup.py` & `ast_scope-0.4.2/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
 setuptools.setup(
-    name="ast_scope", # Replace with your own username
-    version="0.4.1",
+    name="ast_scope",  # Replace with your own username
+    version="0.4.2",
     author="Kavi Gupta",
     author_email="ast_scope@kavigupta.org",
     description="Annotates a Python AST with the scope of symbols.",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/kavigupta/ast_scope",
     download_url="https://github.com/kavigupta/ast_scope/archive/0.3.1.zip",
@@ -17,12 +17,10 @@
     classifiers=[
         "Programming Language :: Python :: 3.5",
         "Programming Language :: Python :: 3.6",
         "Programming Language :: Python :: 3.7",
         "Programming Language :: Python :: 3.8",
         "Operating System :: OS Independent",
     ],
-    python_requires='>=3.5',
-    install_requires=[
-        'attrs==19.3.0'
-    ]
+    python_requires=">=3.5",
+    install_requires=["attrs==19.3.0"],
 )
```

### Comparing `ast_scope-0.4.1/tests/argument_tests.py` & `ast_scope-0.4.2/tests/argument_tests.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/tests/assignment_tests.py` & `ast_scope-0.4.2/tests/assignment_tests.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/tests/basic_scope_tests.py` & `ast_scope-0.4.2/tests/basic_scope_tests.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/tests/class_tests.py` & `ast_scope-0.4.2/tests/class_tests.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/tests/comprehension_tests.py` & `ast_scope-0.4.2/tests/comprehension_tests.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/tests/dependency_graph_tests.py` & `ast_scope-0.4.2/tests/dependency_graph_tests.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/tests/function_frame_tests.py` & `ast_scope-0.4.2/tests/function_frame_tests.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/tests/lambda_test.py` & `ast_scope-0.4.2/tests/lambda_test.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/tests/nonlocal_tests.py` & `ast_scope-0.4.2/tests/nonlocal_tests.py`

 * *Files identical despite different names*

### Comparing `ast_scope-0.4.1/tests/utils.py` & `ast_scope-0.4.2/tests/utils.py`

 * *Files identical despite different names*


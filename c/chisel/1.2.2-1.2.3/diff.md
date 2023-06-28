# Comparing `tmp/chisel-1.2.2.tar.gz` & `tmp/chisel-1.2.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "chisel-1.2.2.tar", last modified: Mon Oct 31 21:10:20 2022, max compression
+gzip compressed data, was "chisel-1.2.3.tar", last modified: Wed Jun 28 14:09:54 2023, max compression
```

## Comparing `chisel-1.2.2.tar` & `chisel-1.2.3.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 21:10:20.137940 chisel-1.2.2/
--rw-r--r--   0       20 dialout     (20)     1081 2022-10-31 17:57:06.000000 chisel-1.2.2/LICENSE
--rw-r--r--   0       20 dialout     (20)     4482 2022-10-31 21:10:20.138379 chisel-1.2.2/PKG-INFO
--rw-r--r--   0       20 dialout     (20)     3465 2022-10-31 17:57:06.000000 chisel-1.2.2/README.rst
--rw-r--r--   0       20 dialout     (20)       50 2022-10-31 17:57:06.000000 chisel-1.2.2/pyproject.toml
--rw-r--r--   0       20 dialout     (20)     1053 2022-10-31 21:10:20.139541 chisel-1.2.2/setup.cfg
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 21:10:20.123686 chisel-1.2.2/src/
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 21:10:20.133203 chisel-1.2.2/src/chisel/
--rw-r--r--   0       20 dialout     (20)      502 2022-10-31 17:57:06.000000 chisel-1.2.2/src/chisel/__init__.py
--rw-r--r--   0       20 dialout     (20)    13926 2022-10-31 21:06:19.000000 chisel-1.2.2/src/chisel/action.py
--rw-r--r--   0       20 dialout     (20)    21745 2022-10-31 17:57:06.000000 chisel-1.2.2/src/chisel/app.py
--rw-r--r--   0       20 dialout     (20)     7009 2022-10-31 20:25:49.000000 chisel-1.2.2/src/chisel/doc.py
--rw-r--r--   0       20 dialout     (20)     8147 2022-10-31 17:57:06.000000 chisel-1.2.2/src/chisel/request.py
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 21:10:20.137358 chisel-1.2.2/src/chisel.egg-info/
--rw-r--r--   0       20 dialout     (20)     4482 2022-10-31 21:10:20.000000 chisel-1.2.2/src/chisel.egg-info/PKG-INFO
--rw-r--r--   0       20 dialout     (20)      314 2022-10-31 21:10:20.000000 chisel-1.2.2/src/chisel.egg-info/SOURCES.txt
--rw-r--r--   0       20 dialout     (20)        1 2022-10-31 21:10:20.000000 chisel-1.2.2/src/chisel.egg-info/dependency_links.txt
--rw-r--r--   0       20 dialout     (20)       23 2022-10-31 21:10:20.000000 chisel-1.2.2/src/chisel.egg-info/requires.txt
--rw-r--r--   0       20 dialout     (20)        7 2022-10-31 21:10:20.000000 chisel-1.2.2/src/chisel.egg-info/top_level.txt
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:09:54.089907 chisel-1.2.3/
+-rw-r--r--   0 craighobbs   (501) staff       (20)     1081 2023-06-11 21:05:17.000000 chisel-1.2.3/LICENSE
+-rw-r--r--   0 craighobbs   (501) staff       (20)     4502 2023-06-28 14:09:54.089959 chisel-1.2.3/PKG-INFO
+-rw-r--r--   0 craighobbs   (501) staff       (20)     3484 2023-06-11 21:05:17.000000 chisel-1.2.3/README.rst
+-rw-r--r--   0 craighobbs   (501) staff       (20)       50 2023-06-11 21:05:17.000000 chisel-1.2.3/pyproject.toml
+-rw-r--r--   0 craighobbs   (501) staff       (20)     1054 2023-06-28 14:09:54.090183 chisel-1.2.3/setup.cfg
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:09:54.088353 chisel-1.2.3/src/
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:09:54.089322 chisel-1.2.3/src/chisel/
+-rw-r--r--   0 craighobbs   (501) staff       (20)      502 2023-06-11 21:05:17.000000 chisel-1.2.3/src/chisel/__init__.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)    13926 2023-06-11 21:05:17.000000 chisel-1.2.3/src/chisel/action.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)    21745 2023-06-11 21:05:17.000000 chisel-1.2.3/src/chisel/app.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)     7009 2023-06-11 21:05:17.000000 chisel-1.2.3/src/chisel/doc.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)     8147 2023-06-11 21:05:17.000000 chisel-1.2.3/src/chisel/request.py
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:09:54.089816 chisel-1.2.3/src/chisel.egg-info/
+-rw-r--r--   0 craighobbs   (501) staff       (20)     4502 2023-06-28 14:09:54.000000 chisel-1.2.3/src/chisel.egg-info/PKG-INFO
+-rw-r--r--   0 craighobbs   (501) staff       (20)      314 2023-06-28 14:09:54.000000 chisel-1.2.3/src/chisel.egg-info/SOURCES.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)        1 2023-06-28 14:09:54.000000 chisel-1.2.3/src/chisel.egg-info/dependency_links.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)       23 2023-06-28 14:09:54.000000 chisel-1.2.3/src/chisel.egg-info/requires.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)        7 2023-06-28 14:09:54.000000 chisel-1.2.3/src/chisel.egg-info/top_level.txt
```

### Comparing `chisel-1.2.2/LICENSE` & `chisel-1.2.3/LICENSE`

 * *Files identical despite different names*

### Comparing `chisel-1.2.2/PKG-INFO` & `chisel-1.2.3/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,25 +1,25 @@
 Metadata-Version: 2.1
 Name: chisel
-Version: 1.2.2
+Version: 1.2.3
 Summary: Lightweight WSGI application framework, schema-validated JSON APIs, and API documentation
 Home-page: https://github.com/craigahobbs/chisel
 Author: Craig A. Hobbs
 Author-email: craigahobbs@gmail.com
 License: MIT
 Keywords: api,json,framework,schema,wsgi
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
 Classifier: Topic :: Internet :: WWW/HTTP :: WSGI
 Classifier: Topic :: Internet :: WWW/HTTP :: WSGI :: Application
 Classifier: Topic :: Software Development :: Libraries :: Application Frameworks
 Description-Content-Type: text/x-rst
 License-File: LICENSE
 
 chisel
@@ -113,11 +113,13 @@
 By default the documentation application is hosted at "/doc/". An example of of Chisel's documentation output is
 available `here <https://craigahobbs.github.io/chisel/example/#var.vName='chisel_doc_request'>`__.
 
 
 Development
 -----------
 
-This project is developed using `python-build <https://github.com/craigahobbs/python-build#readme>`__. It was started
-using `python-template <https://github.com/craigahobbs/python-template#readme>`__ as follows::
+This package is developed using `python-build <https://github.com/craigahobbs/python-build#readme>`__.
+It was started using `python-template <https://github.com/craigahobbs/python-template#readme>`__ as follows:
+
+.. code-block:: sh
 
     template-specialize python-template/template/ chisel/ -k package chisel -k name 'Craig A. Hobbs' -k email 'craigahobbs@gmail.com' -k github 'craigahobbs' -k nomain 1
```

### Comparing `chisel-1.2.2/README.rst` & `chisel-1.2.3/README.rst`

 * *Files 5% similar despite different names*

```diff
@@ -89,11 +89,13 @@
 By default the documentation application is hosted at "/doc/". An example of of Chisel's documentation output is
 available `here <https://craigahobbs.github.io/chisel/example/#var.vName='chisel_doc_request'>`__.
 
 
 Development
 -----------
 
-This project is developed using `python-build <https://github.com/craigahobbs/python-build#readme>`__. It was started
-using `python-template <https://github.com/craigahobbs/python-template#readme>`__ as follows::
+This package is developed using `python-build <https://github.com/craigahobbs/python-build#readme>`__.
+It was started using `python-template <https://github.com/craigahobbs/python-template#readme>`__ as follows:
+
+.. code-block:: sh
 
     template-specialize python-template/template/ chisel/ -k package chisel -k name 'Craig A. Hobbs' -k email 'craigahobbs@gmail.com' -k github 'craigahobbs' -k nomain 1
```

### Comparing `chisel-1.2.2/setup.cfg` & `chisel-1.2.3/setup.cfg`

 * *Files 2% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 [metadata]
 name = chisel
-version = 1.2.2
+version = 1.2.3
 url = https://github.com/craigahobbs/chisel
 author = Craig A. Hobbs
 author_email = craigahobbs@gmail.com
 license = MIT
 description = Lightweight WSGI application framework, schema-validated JSON APIs, and API documentation
 long_description = file:README.rst
 long_description_content_type = text/x-rst
 keywords = api, json, framework, schema, wsgi
 classifiers = 
 	Development Status :: 5 - Production/Stable
 	Intended Audience :: Developers
 	License :: OSI Approved :: MIT License
 	Operating System :: OS Independent
-	Programming Language :: Python :: 3.7
 	Programming Language :: Python :: 3.8
 	Programming Language :: Python :: 3.9
 	Programming Language :: Python :: 3.10
 	Programming Language :: Python :: 3.11
+	Programming Language :: Python :: 3.12
 	Topic :: Internet :: WWW/HTTP :: WSGI
 	Topic :: Internet :: WWW/HTTP :: WSGI :: Application
 	Topic :: Software Development :: Libraries :: Application Frameworks
 
 [options]
 packages = chisel
 package_dir =
```

### Comparing `chisel-1.2.2/src/chisel/action.py` & `chisel-1.2.3/src/chisel/action.py`

 * *Files identical despite different names*

### Comparing `chisel-1.2.2/src/chisel/app.py` & `chisel-1.2.3/src/chisel/app.py`

 * *Files identical despite different names*

### Comparing `chisel-1.2.2/src/chisel/doc.py` & `chisel-1.2.3/src/chisel/doc.py`

 * *Files identical despite different names*

### Comparing `chisel-1.2.2/src/chisel/request.py` & `chisel-1.2.3/src/chisel/request.py`

 * *Files identical despite different names*

### Comparing `chisel-1.2.2/src/chisel.egg-info/PKG-INFO` & `chisel-1.2.3/src/chisel.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,25 +1,25 @@
 Metadata-Version: 2.1
 Name: chisel
-Version: 1.2.2
+Version: 1.2.3
 Summary: Lightweight WSGI application framework, schema-validated JSON APIs, and API documentation
 Home-page: https://github.com/craigahobbs/chisel
 Author: Craig A. Hobbs
 Author-email: craigahobbs@gmail.com
 License: MIT
 Keywords: api,json,framework,schema,wsgi
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
 Classifier: Topic :: Internet :: WWW/HTTP :: WSGI
 Classifier: Topic :: Internet :: WWW/HTTP :: WSGI :: Application
 Classifier: Topic :: Software Development :: Libraries :: Application Frameworks
 Description-Content-Type: text/x-rst
 License-File: LICENSE
 
 chisel
@@ -113,11 +113,13 @@
 By default the documentation application is hosted at "/doc/". An example of of Chisel's documentation output is
 available `here <https://craigahobbs.github.io/chisel/example/#var.vName='chisel_doc_request'>`__.
 
 
 Development
 -----------
 
-This project is developed using `python-build <https://github.com/craigahobbs/python-build#readme>`__. It was started
-using `python-template <https://github.com/craigahobbs/python-template#readme>`__ as follows::
+This package is developed using `python-build <https://github.com/craigahobbs/python-build#readme>`__.
+It was started using `python-template <https://github.com/craigahobbs/python-template#readme>`__ as follows:
+
+.. code-block:: sh
 
     template-specialize python-template/template/ chisel/ -k package chisel -k name 'Craig A. Hobbs' -k email 'craigahobbs@gmail.com' -k github 'craigahobbs' -k nomain 1
```


# Comparing `tmp/fastexception-0.1.4.tar.gz` & `tmp/fastexception-0.1.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "fastexception-0.1.4.tar", last modified: Mon Jun 26 10:37:51 2023, max compression
+gzip compressed data, was "fastexception-0.1.5.tar", last modified: Wed Jun 28 14:07:52 2023, max compression
```

## Comparing `fastexception-0.1.4.tar` & `fastexception-0.1.5.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxrwxr-x   0 mojtaba   (1000) mojtaba   (1000)        0 2023-06-26 10:37:51.695723 fastexception-0.1.4/
--rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)     1056 2023-06-26 09:37:50.000000 fastexception-0.1.4/LICENSE
--rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)     1442 2023-06-26 10:37:51.695723 fastexception-0.1.4/PKG-INFO
--rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)     1015 2023-06-26 07:08:25.000000 fastexception-0.1.4/README.md
-drwxrwxr-x   0 mojtaba   (1000) mojtaba   (1000)        0 2023-06-26 10:37:51.695723 fastexception-0.1.4/fastexception/
--rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)       23 2023-06-26 09:38:39.000000 fastexception-0.1.4/fastexception/__init__.py
--rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)     5348 2023-06-25 19:01:41.000000 fastexception-0.1.4/fastexception/fastexception.py
-drwxrwxr-x   0 mojtaba   (1000) mojtaba   (1000)        0 2023-06-26 10:37:51.695723 fastexception-0.1.4/fastexception.egg-info/
--rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)     1442 2023-06-26 10:37:51.000000 fastexception-0.1.4/fastexception.egg-info/PKG-INFO
--rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)      267 2023-06-26 10:37:51.000000 fastexception-0.1.4/fastexception.egg-info/SOURCES.txt
--rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)        1 2023-06-26 10:37:51.000000 fastexception-0.1.4/fastexception.egg-info/dependency_links.txt
--rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)       10 2023-06-26 10:37:51.000000 fastexception-0.1.4/fastexception.egg-info/requires.txt
--rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)       14 2023-06-26 10:37:51.000000 fastexception-0.1.4/fastexception.egg-info/top_level.txt
--rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)       38 2023-06-26 10:37:51.695723 fastexception-0.1.4/setup.cfg
--rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)      776 2023-06-26 10:37:37.000000 fastexception-0.1.4/setup.py
+drwxrwxr-x   0 mojtaba   (1000) mojtaba   (1000)        0 2023-06-28 14:07:52.986551 fastexception-0.1.5/
+-rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)     1056 2023-06-26 09:37:50.000000 fastexception-0.1.5/LICENSE
+-rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)     1442 2023-06-28 14:07:52.986551 fastexception-0.1.5/PKG-INFO
+-rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)     1015 2023-06-26 07:08:25.000000 fastexception-0.1.5/README.md
+drwxrwxr-x   0 mojtaba   (1000) mojtaba   (1000)        0 2023-06-28 14:07:52.986551 fastexception-0.1.5/fastexception/
+-rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)       23 2023-06-26 09:38:39.000000 fastexception-0.1.5/fastexception/__init__.py
+-rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)     5339 2023-06-28 13:55:56.000000 fastexception-0.1.5/fastexception/fastexception.py
+drwxrwxr-x   0 mojtaba   (1000) mojtaba   (1000)        0 2023-06-28 14:07:52.986551 fastexception-0.1.5/fastexception.egg-info/
+-rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)     1442 2023-06-28 14:07:52.000000 fastexception-0.1.5/fastexception.egg-info/PKG-INFO
+-rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)      267 2023-06-28 14:07:52.000000 fastexception-0.1.5/fastexception.egg-info/SOURCES.txt
+-rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)        1 2023-06-28 14:07:52.000000 fastexception-0.1.5/fastexception.egg-info/dependency_links.txt
+-rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)       10 2023-06-28 14:07:52.000000 fastexception-0.1.5/fastexception.egg-info/requires.txt
+-rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)       14 2023-06-28 14:07:52.000000 fastexception-0.1.5/fastexception.egg-info/top_level.txt
+-rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)       38 2023-06-28 14:07:52.986551 fastexception-0.1.5/setup.cfg
+-rw-rw-r--   0 mojtaba   (1000) mojtaba   (1000)      776 2023-06-28 13:53:02.000000 fastexception-0.1.5/setup.py
```

### Comparing `fastexception-0.1.4/LICENSE` & `fastexception-0.1.5/LICENSE`

 * *Files identical despite different names*

### Comparing `fastexception-0.1.4/PKG-INFO` & `fastexception-0.1.5/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fastexception
-Version: 0.1.4
+Version: 0.1.5
 Home-page: https://github.com/mojtabapaso/fastexception
 Author: Mojtaba
 Author-email: mojtabapaso@gamil.com
 License: MIT
 Keywords: FastAPI Tools Fast Exception
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `fastexception-0.1.4/README.md` & `fastexception-0.1.5/README.md`

 * *Files identical despite different names*

### Comparing `fastexception-0.1.4/fastexception/fastexception.py` & `fastexception-0.1.5/fastexception/fastexception.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,19 +1,19 @@
-from starlette.exceptions import HTTPException
+from starlette.responses import Response
 
 
 class FastException:
     class Exceptions:
 
         def __init__(self, status, message):
             self.status = status
             self.message = message
 
         def http(self, message=None):
-            raise HTTPException(status_code=self.status, detail=message or self.message)
+            return Response(status_code=self.status, content=message or self.message)
 
     # --------------2xx----------------
     HTTP_200_OK = Exceptions(status=200, message="OK")
     HTTP_201_CREATED = Exceptions(status=201, message="Created")
     HTTP_202_ACCEPTED = Exceptions(status=202, message="Accepted")
     HTTP_203_NON_AUTHORITATIVE_INFORMATION = Exceptions(status=203, message="Non-Authoritative Information")
     HTTP_204_NO_CONTENT = Exceptions(status=204, message="No Content")
```

### Comparing `fastexception-0.1.4/fastexception.egg-info/PKG-INFO` & `fastexception-0.1.5/fastexception.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fastexception
-Version: 0.1.4
+Version: 0.1.5
 Home-page: https://github.com/mojtabapaso/fastexception
 Author: Mojtaba
 Author-email: mojtabapaso@gamil.com
 License: MIT
 Keywords: FastAPI Tools Fast Exception
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `fastexception-0.1.4/setup.py` & `fastexception-0.1.5/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 
 with open("README.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
 this_directory = Path(__file__).parent
 setup(
 
     name='fastexception',
-    version='0.1.4',
+    version='0.1.5',
     license='MIT',
     author='Mojtaba',
     author_email='mojtabapaso@gamil.com',
     packages=find_packages(),
     url='https://github.com/mojtabapaso/fastexception',
     keywords='FastAPI Tools Fast Exception',
```


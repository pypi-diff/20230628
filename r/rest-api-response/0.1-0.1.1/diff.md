# Comparing `tmp/rest_api_response-0.1.tar.gz` & `tmp/rest_api_response-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "rest_api_response-0.1.tar", last modified: Wed Jun 28 11:35:42 2023, max compression
+gzip compressed data, was "rest_api_response-0.1.1.tar", last modified: Wed Jun 28 12:06:57 2023, max compression
```

## Comparing `rest_api_response-0.1.tar` & `rest_api_response-0.1.1.tar`

### file list

```diff
@@ -1,17 +1,17 @@
-drwxr-xr-x   0 abram     (1000) israelabraham  (1001)        0 2023-06-28 11:35:42.648187 rest_api_response-0.1/
--rw-rw-r--   0 abram     (1000) israelabraham  (1001)     1061 2022-09-30 15:18:58.000000 rest_api_response-0.1/LICENSE.txt
--rw-r--r--   0 abram     (1000) israelabraham  (1001)     3708 2023-06-28 11:35:42.648187 rest_api_response-0.1/PKG-INFO
--rw-r--r--   0 abram     (1000) israelabraham  (1001)     2981 2023-06-25 19:34:11.000000 rest_api_response-0.1/README.md
--rw-rw-r--   0 abram     (1000) israelabraham  (1001)      103 2022-05-03 23:39:49.000000 rest_api_response-0.1/pyproject.toml
-drwxr-xr-x   0 abram     (1000) israelabraham  (1001)        0 2023-06-28 11:35:42.644187 rest_api_response-0.1/rest_api_response/
--rw-r--r--   0 abram     (1000) israelabraham  (1001)      934 2023-06-28 11:34:41.000000 rest_api_response-0.1/rest_api_response/__init__.py
-drwxr-xr-x   0 abram     (1000) israelabraham  (1001)        0 2023-06-28 11:35:42.648187 rest_api_response-0.1/rest_api_response.egg-info/
--rw-r--r--   0 abram     (1000) israelabraham  (1001)     3708 2023-06-28 11:35:42.000000 rest_api_response-0.1/rest_api_response.egg-info/PKG-INFO
--rw-r--r--   0 abram     (1000) israelabraham  (1001)      286 2023-06-28 11:35:42.000000 rest_api_response-0.1/rest_api_response.egg-info/SOURCES.txt
--rw-r--r--   0 abram     (1000) israelabraham  (1001)        1 2023-06-28 11:35:42.000000 rest_api_response-0.1/rest_api_response.egg-info/dependency_links.txt
--rw-r--r--   0 abram     (1000) israelabraham  (1001)       24 2023-06-28 11:35:42.000000 rest_api_response-0.1/rest_api_response.egg-info/top_level.txt
--rw-rw-r--   0 abram     (1000) israelabraham  (1001)      711 2023-06-28 11:35:42.648187 rest_api_response-0.1/setup.cfg
--rw-rw-r--   0 abram     (1000) israelabraham  (1001)      810 2023-06-25 19:03:25.000000 rest_api_response-0.1/setup.py
-drwxr-xr-x   0 abram     (1000) israelabraham  (1001)        0 2023-06-28 11:35:42.648187 rest_api_response-0.1/tests/
--rw-rw-r--   0 abram     (1000) israelabraham  (1001)        0 2022-05-03 23:39:49.000000 rest_api_response-0.1/tests/__init__.py
--rw-rw-r--   0 abram     (1000) israelabraham  (1001)      971 2023-06-28 11:33:28.000000 rest_api_response-0.1/tests/test_init.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:06:57.354719 rest_api_response-0.1.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1061 2023-06-28 12:06:44.000000 rest_api_response-0.1.1/LICENSE.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     3551 2023-06-28 12:06:57.354719 rest_api_response-0.1.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2834 2023-06-28 12:06:44.000000 rest_api_response-0.1.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      103 2023-06-28 12:06:44.000000 rest_api_response-0.1.1/pyproject.toml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:06:57.354719 rest_api_response-0.1.1/rest_api_response/
+-rw-r--r--   0 runner    (1001) docker     (123)      937 2023-06-28 12:06:44.000000 rest_api_response-0.1.1/rest_api_response/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:06:57.354719 rest_api_response-0.1.1/rest_api_response.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     3551 2023-06-28 12:06:57.000000 rest_api_response-0.1.1/rest_api_response.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      286 2023-06-28 12:06:57.000000 rest_api_response-0.1.1/rest_api_response.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:06:57.000000 rest_api_response-0.1.1/rest_api_response.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 12:06:57.000000 rest_api_response-0.1.1/rest_api_response.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      701 2023-06-28 12:06:57.354719 rest_api_response-0.1.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      806 2023-06-28 12:06:44.000000 rest_api_response-0.1.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:06:57.354719 rest_api_response-0.1.1/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:06:44.000000 rest_api_response-0.1.1/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      971 2023-06-28 12:06:44.000000 rest_api_response-0.1.1/tests/test_init.py
```

### Comparing `rest_api_response-0.1/LICENSE.txt` & `rest_api_response-0.1.1/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `rest_api_response-0.1/PKG-INFO` & `rest_api_response-0.1.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 2.1
 Name: rest_api_response
-Version: 0.1
+Version: 0.1.1
 Summary: A go-to production API response with an easy format for building APIs with Python.
-Home-page: https://github.com/israelabraham/api-response
+Home-page: https://github.com/aybruhm/api-response
 Author: Abram
 Author-email: israelvictory87@gmail.com
 License: MIT
-Project-URL: Bug Tracker, https://github.com/israelabraham/api-response/issues
+Project-URL: Bug Tracker, https://github.com/aybruhm/api-response/issues
 Keywords: api,response,custom api response
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Education
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Requires-Python: >=3
@@ -30,15 +30,15 @@
 ```bash
 pip install rest-api-response
 ```
 
 2). In the file (.py) that you wish to use it, import it:
 
 ```python
-    from rest_api_response import success_response, error_response
+from rest_api_response import success_response, error_response
 ```
 
 That's pretty much it - you can now call the function and pass the required arguments!
 
 ## Example
 
 Suppose you have an API class that returns a list of blog posts to a client:
@@ -56,31 +56,31 @@
         serializer = self.serializer_class(posts, many=True)
         return Response(serializer.data)
 ```
 
 The API response would be:
 
 ```json
-    [
-        {
-            "title": "First blog post", 
-            "content": "Lorem ipsume content", 
-            "author": 1
-        },
-        {
-            "title": "Second blog post", 
-            "content": "Lorem ipsume content", 
-            "author": 2
-        },
-        {
-            "title": "Third blog post", 
-            "content": "Lorem ipsume content", 
-            "author": 3
-        }
-    ]
+[
+    {
+        "title": "First blog post", 
+        "content": "Lorem ipsume content", 
+        "author": 1
+    },
+    {
+        "title": "Second blog post", 
+        "content": "Lorem ipsume content", 
+        "author": 2
+    },
+    {
+        "title": "Third blog post", 
+        "content": "Lorem ipsume content", 
+        "author": 3
+    }
+]
 ```
 
 This works too, but let's take the response to the next level by doing this:
 
 ```python
 # imports goes here
 ...
@@ -101,34 +101,35 @@
         )
         return Response(data=_response, status=status.HTTP_200_OK)
 ```
 
 The API response would be:
 
 ```json
-    [   "status": true, 
-        "message": "Posts retrieved!", 
-        "data": {
-            {
-                "title": "First blog post", 
-                "content": "Lorem ipsume content", 
-                "author": 1
-            },
-            {
-                "title": "Second blog post", 
-                "content": "Lorem ipsume content", 
-                "author": 2
-            },
-            {
-                "title": "Third blog post", 
-                "content": "Lorem ipsume content", 
-                "author": 3
-            }
+[   
+    "status": true, 
+    "message": "Posts retrieved!", 
+    "data": [
+        {
+            "title": "First blog post", 
+            "content": "Lorem ipsume content", 
+            "author": 1
+        },
+        {
+            "title": "Second blog post", 
+            "content": "Lorem ipsume content", 
+            "author": 2
+        },
+        {
+            "title": "Third blog post", 
+            "content": "Lorem ipsume content", 
+            "author": 3
         }
     ]
+]
 ```
 
 And that's it. You have a nicely catchy response. :-)
 
 ## Contribute
 
 All contributions are welcome:
```

### Comparing `rest_api_response-0.1/README.md` & `rest_api_response-0.1.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -11,15 +11,15 @@
 ```bash
 pip install rest-api-response
 ```
 
 2). In the file (.py) that you wish to use it, import it:
 
 ```python
-    from rest_api_response import success_response, error_response
+from rest_api_response import success_response, error_response
 ```
 
 That's pretty much it - you can now call the function and pass the required arguments!
 
 ## Example
 
 Suppose you have an API class that returns a list of blog posts to a client:
@@ -37,31 +37,31 @@
         serializer = self.serializer_class(posts, many=True)
         return Response(serializer.data)
 ```
 
 The API response would be:
 
 ```json
-    [
-        {
-            "title": "First blog post", 
-            "content": "Lorem ipsume content", 
-            "author": 1
-        },
-        {
-            "title": "Second blog post", 
-            "content": "Lorem ipsume content", 
-            "author": 2
-        },
-        {
-            "title": "Third blog post", 
-            "content": "Lorem ipsume content", 
-            "author": 3
-        }
-    ]
+[
+    {
+        "title": "First blog post", 
+        "content": "Lorem ipsume content", 
+        "author": 1
+    },
+    {
+        "title": "Second blog post", 
+        "content": "Lorem ipsume content", 
+        "author": 2
+    },
+    {
+        "title": "Third blog post", 
+        "content": "Lorem ipsume content", 
+        "author": 3
+    }
+]
 ```
 
 This works too, but let's take the response to the next level by doing this:
 
 ```python
 # imports goes here
 ...
@@ -82,34 +82,35 @@
         )
         return Response(data=_response, status=status.HTTP_200_OK)
 ```
 
 The API response would be:
 
 ```json
-    [   "status": true, 
-        "message": "Posts retrieved!", 
-        "data": {
-            {
-                "title": "First blog post", 
-                "content": "Lorem ipsume content", 
-                "author": 1
-            },
-            {
-                "title": "Second blog post", 
-                "content": "Lorem ipsume content", 
-                "author": 2
-            },
-            {
-                "title": "Third blog post", 
-                "content": "Lorem ipsume content", 
-                "author": 3
-            }
+[   
+    "status": true, 
+    "message": "Posts retrieved!", 
+    "data": [
+        {
+            "title": "First blog post", 
+            "content": "Lorem ipsume content", 
+            "author": 1
+        },
+        {
+            "title": "Second blog post", 
+            "content": "Lorem ipsume content", 
+            "author": 2
+        },
+        {
+            "title": "Third blog post", 
+            "content": "Lorem ipsume content", 
+            "author": 3
         }
     ]
+]
 ```
 
 And that's it. You have a nicely catchy response. :-)
 
 ## Contribute
 
 All contributions are welcome:
```

### Comparing `rest_api_response-0.1/rest_api_response/__init__.py` & `rest_api_response-0.1.1/rest_api_response/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -35,8 +35,9 @@
     :type data: dict
 
     :return: response
     :rtype: dict
     """
 
     response = {"status": True, "message": message, "data": data}
-    return response
+    return response
+
```

### Comparing `rest_api_response-0.1/rest_api_response.egg-info/PKG-INFO` & `rest_api_response-0.1.1/rest_api_response.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 2.1
 Name: rest-api-response
-Version: 0.1
+Version: 0.1.1
 Summary: A go-to production API response with an easy format for building APIs with Python.
-Home-page: https://github.com/israelabraham/api-response
+Home-page: https://github.com/aybruhm/api-response
 Author: Abram
 Author-email: israelvictory87@gmail.com
 License: MIT
-Project-URL: Bug Tracker, https://github.com/israelabraham/api-response/issues
+Project-URL: Bug Tracker, https://github.com/aybruhm/api-response/issues
 Keywords: api,response,custom api response
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Education
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Requires-Python: >=3
@@ -30,15 +30,15 @@
 ```bash
 pip install rest-api-response
 ```
 
 2). In the file (.py) that you wish to use it, import it:
 
 ```python
-    from rest_api_response import success_response, error_response
+from rest_api_response import success_response, error_response
 ```
 
 That's pretty much it - you can now call the function and pass the required arguments!
 
 ## Example
 
 Suppose you have an API class that returns a list of blog posts to a client:
@@ -56,31 +56,31 @@
         serializer = self.serializer_class(posts, many=True)
         return Response(serializer.data)
 ```
 
 The API response would be:
 
 ```json
-    [
-        {
-            "title": "First blog post", 
-            "content": "Lorem ipsume content", 
-            "author": 1
-        },
-        {
-            "title": "Second blog post", 
-            "content": "Lorem ipsume content", 
-            "author": 2
-        },
-        {
-            "title": "Third blog post", 
-            "content": "Lorem ipsume content", 
-            "author": 3
-        }
-    ]
+[
+    {
+        "title": "First blog post", 
+        "content": "Lorem ipsume content", 
+        "author": 1
+    },
+    {
+        "title": "Second blog post", 
+        "content": "Lorem ipsume content", 
+        "author": 2
+    },
+    {
+        "title": "Third blog post", 
+        "content": "Lorem ipsume content", 
+        "author": 3
+    }
+]
 ```
 
 This works too, but let's take the response to the next level by doing this:
 
 ```python
 # imports goes here
 ...
@@ -101,34 +101,35 @@
         )
         return Response(data=_response, status=status.HTTP_200_OK)
 ```
 
 The API response would be:
 
 ```json
-    [   "status": true, 
-        "message": "Posts retrieved!", 
-        "data": {
-            {
-                "title": "First blog post", 
-                "content": "Lorem ipsume content", 
-                "author": 1
-            },
-            {
-                "title": "Second blog post", 
-                "content": "Lorem ipsume content", 
-                "author": 2
-            },
-            {
-                "title": "Third blog post", 
-                "content": "Lorem ipsume content", 
-                "author": 3
-            }
+[   
+    "status": true, 
+    "message": "Posts retrieved!", 
+    "data": [
+        {
+            "title": "First blog post", 
+            "content": "Lorem ipsume content", 
+            "author": 1
+        },
+        {
+            "title": "Second blog post", 
+            "content": "Lorem ipsume content", 
+            "author": 2
+        },
+        {
+            "title": "Third blog post", 
+            "content": "Lorem ipsume content", 
+            "author": 3
         }
     ]
+]
 ```
 
 And that's it. You have a nicely catchy response. :-)
 
 ## Contribute
 
 All contributions are welcome:
```

### Comparing `rest_api_response-0.1/setup.cfg` & `rest_api_response-0.1.1/setup.cfg`

 * *Files 7% similar despite different names*

```diff
@@ -1,18 +1,18 @@
 [metadata]
 name = rest-api-response
-version = 0.1
+version = 0.1.1
 author = Abram
 author_email = israelvictory87@gmail.com
 description = A go-to production API response with an easy format for building APIs with Python.
 long_description = file: README.md
 long_description_content_type = text/markdown
-url = https://github.com/israelabraham/api-response
+url = https://github.com/aybruhm/api-response
 project_urls = 
-	Bug Tracker = https://github.com/israelabraham/api-response/issues
+	Bug Tracker = https://github.com/aybruhm/api-response/issues
 classifiers = 
 	Development Status :: 5 - Production/Stable
 	Intended Audience :: Education
 	Intended Audience :: Developers
 	License :: OSI Approved :: MIT License
 	Programming Language :: Python :: 3
```

### Comparing `rest_api_response-0.1/setup.py` & `rest_api_response-0.1.1/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -6,19 +6,19 @@
     "Intended Audience :: Developers",
     "License :: OSI Approved :: MIT License",
     "Programming Language :: Python :: 3",
 ]
 
 setup(
     name="rest_api_response",
-    version="0.1",
+    version="0.1.1",
     description="A go-to production API response with an easy format for building APIs with Python.", # noqa: E501
     long_description_content_type="text/markdown",
     long_description=open("README.md").read(),
-    url="https://github.com/israelabraham/api-response",
+    url="https://github.com/aybruhm/api-response",
     author="Abram",
     author_email="israelvictory87@gmail.com",
     license="MIT",
     classifiers=classifiers,
     keywords=["api", "response", "custom api response"],
     packages=find_packages(),
 )
```

### Comparing `rest_api_response-0.1/tests/test_init.py` & `rest_api_response-0.1.1/tests/test_init.py`

 * *Files identical despite different names*


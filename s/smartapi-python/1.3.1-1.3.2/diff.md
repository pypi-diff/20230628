# Comparing `tmp/smartapi-python-1.3.1.tar.gz` & `tmp/smartapi-python-1.3.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "smartapi-python-1.3.1.tar", last modified: Wed Jun 28 09:46:13 2023, max compression
+gzip compressed data, was "smartapi-python-1.3.2.tar", last modified: Wed Jun 28 12:15:21 2023, max compression
```

## Comparing `smartapi-python-1.3.1.tar` & `smartapi-python-1.3.2.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 09:46:13.742976 smartapi-python-1.3.1/
--rw-rw-r--   0 rima      (1000) rima      (1000)     5709 2023-06-28 09:46:13.742976 smartapi-python-1.3.1/PKG-INFO
--rw-rw-r--   0 rima      (1000) rima      (1000)     4765 2023-06-28 09:06:08.000000 smartapi-python-1.3.1/README.md
-drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 09:46:13.742976 smartapi-python-1.3.1/SmartApi/
--rw-rw-r--   0 rima      (1000) rima      (1000)      250 2023-06-19 07:12:24.000000 smartapi-python-1.3.1/SmartApi/__init__.py
--rw-rw-r--   0 rima      (1000) rima      (1000)     5937 2023-06-19 07:12:24.000000 smartapi-python-1.3.1/SmartApi/smartApiWebsocket.py
--rw-rw-r--   0 rima      (1000) rima      (1000)    14990 2023-06-28 08:34:24.000000 smartapi-python-1.3.1/SmartApi/smartConnect.py
--rw-rw-r--   0 rima      (1000) rima      (1000)     2176 2023-06-19 07:12:24.000000 smartapi-python-1.3.1/SmartApi/smartExceptions.py
--rw-rw-r--   0 rima      (1000) rima      (1000)    16867 2023-06-26 10:05:44.000000 smartapi-python-1.3.1/SmartApi/smartWebSocketV2.py
--rw-rw-r--   0 rima      (1000) rima      (1000)      541 2023-06-28 09:35:39.000000 smartapi-python-1.3.1/SmartApi/version.py
--rw-rw-r--   0 rima      (1000) rima      (1000)    15272 2023-06-28 08:19:24.000000 smartapi-python-1.3.1/SmartApi/webSocket.py
--rw-rw-r--   0 rima      (1000) rima      (1000)       38 2023-06-28 09:46:13.742976 smartapi-python-1.3.1/setup.cfg
--rw-rw-r--   0 rima      (1000) rima      (1000)     1283 2023-06-28 09:45:51.000000 smartapi-python-1.3.1/setup.py
-drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 09:46:13.742976 smartapi-python-1.3.1/smartapi_python.egg-info/
--rw-rw-r--   0 rima      (1000) rima      (1000)     5709 2023-06-28 09:46:13.000000 smartapi-python-1.3.1/smartapi_python.egg-info/PKG-INFO
--rw-rw-r--   0 rima      (1000) rima      (1000)      417 2023-06-28 09:46:13.000000 smartapi-python-1.3.1/smartapi_python.egg-info/SOURCES.txt
--rw-rw-r--   0 rima      (1000) rima      (1000)        1 2023-06-28 09:46:13.000000 smartapi-python-1.3.1/smartapi_python.egg-info/dependency_links.txt
--rw-rw-r--   0 rima      (1000) rima      (1000)       52 2023-06-28 09:46:13.000000 smartapi-python-1.3.1/smartapi_python.egg-info/requires.txt
--rw-rw-r--   0 rima      (1000) rima      (1000)       14 2023-06-28 09:46:13.000000 smartapi-python-1.3.1/smartapi_python.egg-info/top_level.txt
-drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 09:46:13.742976 smartapi-python-1.3.1/test/
--rw-rw-r--   0 rima      (1000) rima      (1000)        0 2023-04-19 08:19:43.000000 smartapi-python-1.3.1/test/__init__.py
--rw-rw-r--   0 rima      (1000) rima      (1000)     4436 2023-06-28 09:06:08.000000 smartapi-python-1.3.1/test/test.py
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:15:21.228074 smartapi-python-1.3.2/
+-rw-rw-r--   0 rima      (1000) rima      (1000)     5709 2023-06-28 12:15:21.228074 smartapi-python-1.3.2/PKG-INFO
+-rw-rw-r--   0 rima      (1000) rima      (1000)     4765 2023-06-28 09:06:08.000000 smartapi-python-1.3.2/README.md
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:15:21.224074 smartapi-python-1.3.2/SmartApi/
+-rw-rw-r--   0 rima      (1000) rima      (1000)      250 2023-06-19 07:12:24.000000 smartapi-python-1.3.2/SmartApi/__init__.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)     5937 2023-06-19 07:12:24.000000 smartapi-python-1.3.2/SmartApi/smartApiWebsocket.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)    14990 2023-06-28 08:34:24.000000 smartapi-python-1.3.2/SmartApi/smartConnect.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)     2176 2023-06-19 07:12:24.000000 smartapi-python-1.3.2/SmartApi/smartExceptions.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)    16867 2023-06-26 10:05:44.000000 smartapi-python-1.3.2/SmartApi/smartWebSocketV2.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)      541 2023-06-28 12:13:17.000000 smartapi-python-1.3.2/SmartApi/version.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)    15272 2023-06-28 08:19:24.000000 smartapi-python-1.3.2/SmartApi/webSocket.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)       38 2023-06-28 12:15:21.228074 smartapi-python-1.3.2/setup.cfg
+-rw-rw-r--   0 rima      (1000) rima      (1000)     1283 2023-06-28 12:13:03.000000 smartapi-python-1.3.2/setup.py
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:15:21.224074 smartapi-python-1.3.2/smartapi_python.egg-info/
+-rw-rw-r--   0 rima      (1000) rima      (1000)     5709 2023-06-28 12:15:21.000000 smartapi-python-1.3.2/smartapi_python.egg-info/PKG-INFO
+-rw-rw-r--   0 rima      (1000) rima      (1000)      417 2023-06-28 12:15:21.000000 smartapi-python-1.3.2/smartapi_python.egg-info/SOURCES.txt
+-rw-rw-r--   0 rima      (1000) rima      (1000)        1 2023-06-28 12:15:21.000000 smartapi-python-1.3.2/smartapi_python.egg-info/dependency_links.txt
+-rw-rw-r--   0 rima      (1000) rima      (1000)       52 2023-06-28 12:15:21.000000 smartapi-python-1.3.2/smartapi_python.egg-info/requires.txt
+-rw-rw-r--   0 rima      (1000) rima      (1000)       14 2023-06-28 12:15:21.000000 smartapi-python-1.3.2/smartapi_python.egg-info/top_level.txt
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:15:21.228074 smartapi-python-1.3.2/test/
+-rw-rw-r--   0 rima      (1000) rima      (1000)        0 2023-04-19 08:19:43.000000 smartapi-python-1.3.2/test/__init__.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)     4436 2023-06-28 09:06:08.000000 smartapi-python-1.3.2/test/test.py
```

### Comparing `smartapi-python-1.3.1/PKG-INFO` & `smartapi-python-1.3.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: smartapi-python
-Version: 1.3.1
+Version: 1.3.2
 Summary: Angel Broking openApi integration
 Home-page: https://github.com/angelbroking-github/smartapi-python
 Author: ab-smartapi
 Author-email: smartapi.sdk@gmail.com
 License: UNKNOWN
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
```

### Comparing `smartapi-python-1.3.1/README.md` & `smartapi-python-1.3.2/README.md`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.1/SmartApi/smartApiWebsocket.py` & `smartapi-python-1.3.2/SmartApi/smartApiWebsocket.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.1/SmartApi/smartConnect.py` & `smartapi-python-1.3.2/SmartApi/smartConnect.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.1/SmartApi/smartExceptions.py` & `smartapi-python-1.3.2/SmartApi/smartExceptions.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.1/SmartApi/smartWebSocketV2.py` & `smartapi-python-1.3.2/SmartApi/smartWebSocketV2.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.1/SmartApi/version.py` & `smartapi-python-1.3.2/SmartApi/version.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 __title__ = "smartapi-python"
 __description__ = "Angel Broking openApi integration"
 __url__ = "https://www.angelbroking.com/"
 __download_url__ = "https://github.com/angelbroking-github/smartapi-python"
-__version__ = "1.3.0"
+__version__ = "1.3.2"
 __author__ = "ab-smartapi"
 __token__ = "ab-smartapi"
 __author_email__ = "smartapi.sdk@gmail.com"
 
 
 # [pypi]
 # username = __token__
```

### Comparing `smartapi-python-1.3.1/SmartApi/webSocket.py` & `smartapi-python-1.3.2/SmartApi/webSocket.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.1/setup.py` & `smartapi-python-1.3.2/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -8,15 +8,15 @@
         "requests>=2.18.4",
         "six>=1.11.0",
         "python-dateutil>=2.6.1"
     ]
 
 setup(
     name="smartapi-python",
-    version="1.3.1",
+    version="1.3.2",
     author="ab-smartapi",
     author_email="smartapi.sdk@gmail.com",
     description="Angel Broking openApi integration",
     long_description=readme,
     long_description_content_type="text/markdown",
     url="https://github.com/angelbroking-github/smartapi-python",
     packages=find_packages(),
```

### Comparing `smartapi-python-1.3.1/smartapi_python.egg-info/PKG-INFO` & `smartapi-python-1.3.2/smartapi_python.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: smartapi-python
-Version: 1.3.1
+Version: 1.3.2
 Summary: Angel Broking openApi integration
 Home-page: https://github.com/angelbroking-github/smartapi-python
 Author: ab-smartapi
 Author-email: smartapi.sdk@gmail.com
 License: UNKNOWN
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
```

### Comparing `smartapi-python-1.3.1/test/test.py` & `smartapi-python-1.3.2/test/test.py`

 * *Files identical despite different names*


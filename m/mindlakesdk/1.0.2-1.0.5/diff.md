# Comparing `tmp/mindlakesdk-1.0.2.tar.gz` & `tmp/mindlakesdk-1.0.5.tar.gz`

## Comparing `mindlakesdk-1.0.2.tar` & `mindlakesdk-1.0.5.tar`

### file list

```diff
@@ -1,16 +1,16 @@
--rw-r--r--   0        0        0       24 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/requirements.txt
--rw-r--r--   0        0        0     1085 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/mindlakesdk/LICENSE
--rw-r--r--   0        0        0      115 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/mindlakesdk/README.md
--rw-r--r--   0        0        0     3603 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/mindlakesdk/__init__.py
--rw-r--r--   0        0        0     9614 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/mindlakesdk/cryptor.py
--rw-r--r--   0        0        0     1954 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/mindlakesdk/datalake.py
--rw-r--r--   0        0        0     6118 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/mindlakesdk/keyhelper.py
--rw-r--r--   0        0        0     6644 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/mindlakesdk/message.py
--rw-r--r--   0        0        0     6229 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/mindlakesdk/permission.py
--rw-r--r--   0        0        0     2636 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/mindlakesdk/settings.py
--rw-r--r--   0        0        0     3740 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/mindlakesdk/utils.py
--rw-r--r--   0        0        0       50 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/.gitignore
--rw-r--r--   0        0        0     1085 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/LICENSE
--rw-r--r--   0        0        0     1705 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/README.md
--rw-r--r--   0        0        0      778 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/pyproject.toml
--rw-r--r--   0        0        0     2350 2020-02-02 00:00:00.000000 mindlakesdk-1.0.2/PKG-INFO
+-rw-r--r--   0        0        0       24 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/requirements.txt
+-rw-r--r--   0        0        0     1085 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/mindlakesdk/LICENSE
+-rw-r--r--   0        0        0      115 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/mindlakesdk/README.md
+-rw-r--r--   0        0        0     3603 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/mindlakesdk/__init__.py
+-rw-r--r--   0        0        0     9614 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/mindlakesdk/cryptor.py
+-rw-r--r--   0        0        0     1954 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/mindlakesdk/datalake.py
+-rw-r--r--   0        0        0     6118 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/mindlakesdk/keyhelper.py
+-rw-r--r--   0        0        0     6644 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/mindlakesdk/message.py
+-rw-r--r--   0        0        0     6229 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/mindlakesdk/permission.py
+-rw-r--r--   0        0        0     2636 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/mindlakesdk/settings.py
+-rw-r--r--   0        0        0     3740 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/mindlakesdk/utils.py
+-rw-r--r--   0        0        0       50 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/.gitignore
+-rw-r--r--   0        0        0     1085 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/LICENSE
+-rw-r--r--   0        0        0     1803 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/README.md
+-rw-r--r--   0        0        0      778 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/pyproject.toml
+-rw-r--r--   0        0        0     2448 2020-02-02 00:00:00.000000 mindlakesdk-1.0.5/PKG-INFO
```

### Comparing `mindlakesdk-1.0.2/mindlakesdk/LICENSE` & `mindlakesdk-1.0.5/mindlakesdk/LICENSE`

 * *Files identical despite different names*

### Comparing `mindlakesdk-1.0.2/mindlakesdk/__init__.py` & `mindlakesdk-1.0.5/mindlakesdk/__init__.py`

 * *Files identical despite different names*

### Comparing `mindlakesdk-1.0.2/mindlakesdk/cryptor.py` & `mindlakesdk-1.0.5/mindlakesdk/cryptor.py`

 * *Files identical despite different names*

### Comparing `mindlakesdk-1.0.2/mindlakesdk/datalake.py` & `mindlakesdk-1.0.5/mindlakesdk/datalake.py`

 * *Files identical despite different names*

### Comparing `mindlakesdk-1.0.2/mindlakesdk/keyhelper.py` & `mindlakesdk-1.0.5/mindlakesdk/keyhelper.py`

 * *Files identical despite different names*

### Comparing `mindlakesdk-1.0.2/mindlakesdk/message.py` & `mindlakesdk-1.0.5/mindlakesdk/message.py`

 * *Files identical despite different names*

### Comparing `mindlakesdk-1.0.2/mindlakesdk/permission.py` & `mindlakesdk-1.0.5/mindlakesdk/permission.py`

 * *Files identical despite different names*

### Comparing `mindlakesdk-1.0.2/mindlakesdk/settings.py` & `mindlakesdk-1.0.5/mindlakesdk/settings.py`

 * *Files 1% similar despite different names*

```diff
@@ -66,8 +66,8 @@
                                 "type": "bytes"
                         }
                 ],
                 "stateMutability": "view",
                 "type": "function"
         }
 ]
-VERSION = 'v1.0.2'
+VERSION = 'v1.0.5'
```

### Comparing `mindlakesdk-1.0.2/mindlakesdk/utils.py` & `mindlakesdk-1.0.5/mindlakesdk/utils.py`

 * *Files identical despite different names*

### Comparing `mindlakesdk-1.0.2/LICENSE` & `mindlakesdk-1.0.5/LICENSE`

 * *Files identical despite different names*

### Comparing `mindlakesdk-1.0.2/README.md` & `mindlakesdk-1.0.5/README.md`

 * *Files 14% similar despite different names*

```diff
@@ -64,11 +64,15 @@
 
 ## Version History
 
 * v1.0
     * Initial Release
 * v1.0.1
     * Fix bug
+* v1.0.2
+    * Improve performances
+* v1.0.5
+    * Keep up the version number with TypeScript SDK
 
 ## License
 
 This project is licensed under the [MIT] License - see the LICENSE.md file for details
```

### Comparing `mindlakesdk-1.0.2/pyproject.toml` & `mindlakesdk-1.0.5/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["hatchling"]
 build-backend = "hatchling.build"
 
 [project]
 name = "mindlakesdk"
-version = "v1.0.2"
+version = "v1.0.5"
 authors = [
   { name="Mind Labs", email="biz@mindnetwork.xyz" },
 ]
 description = "A Python SDK to connect to Mind Lake"
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `mindlakesdk-1.0.2/PKG-INFO` & `mindlakesdk-1.0.5/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mindlakesdk
-Version: 1.0.2
+Version: 1.0.5
 Summary: A Python SDK to connect to Mind Lake
 Project-URL: Homepage, https://github.com/mind-network/mind-lake-sdk-python
 Project-URL: Bug Tracker, https://github.com/mind-network/mind-lake-sdk-python/issues
 Author-email: Mind Labs <biz@mindnetwork.xyz>
 License-File: LICENSE
 Keywords: datalake,encryption,web3
 Classifier: License :: OSI Approved :: MIT License
@@ -82,11 +82,15 @@
 
 ## Version History
 
 * v1.0
     * Initial Release
 * v1.0.1
     * Fix bug
+* v1.0.2
+    * Improve performances
+* v1.0.5
+    * Keep up the version number with TypeScript SDK
 
 ## License
 
 This project is licensed under the [MIT] License - see the LICENSE.md file for details
```


# Comparing `tmp/gcloud_rest_auth-4.2.1.tar.gz` & `tmp/gcloud_rest_auth-4.2.3a0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "gcloud_rest_auth-4.2.1.tar", max compression
+gzip compressed data, was "gcloud_rest_auth-4.2.3a0.tar", max compression
```

## Comparing `gcloud_rest_auth-4.2.1.tar` & `gcloud_rest_auth-4.2.3a0.tar`

### file list

```diff
@@ -1,15 +1,15 @@
--rw-r--r--   0        0        0     1063 2023-04-05 15:59:00.000000 gcloud_rest_auth-4.2.1/LICENSE
--rw-r--r--   0        0        0     2998 2023-04-05 15:59:00.000000 gcloud_rest_auth-4.2.1/README.rst
--rw-r--r--   0        0        0      212 2023-04-05 15:59:01.000000 gcloud_rest_auth-4.2.1/gcloud/__init__.py
--rw-r--r--   0        0        0        0 2023-04-05 15:59:00.000000 gcloud_rest_auth-4.2.1/gcloud/py.typed
--rw-r--r--   0        0        0      216 2023-04-05 15:59:01.000000 gcloud_rest_auth-4.2.1/gcloud/rest/__init__.py
--rw-r--r--   0        0        0     2048 2023-04-05 15:59:01.000000 gcloud_rest_auth-4.2.1/gcloud/rest/auth/__init__.py
--rw-r--r--   0        0        0      184 2023-04-05 15:59:01.000000 gcloud_rest_auth-4.2.1/gcloud/rest/auth/build_constants.py
--rw-r--r--   0        0        0     5254 2023-04-05 15:59:01.000000 gcloud_rest_auth-4.2.1/gcloud/rest/auth/iam.py
--rw-r--r--   0        0        0        0 2023-04-05 15:59:00.000000 gcloud_rest_auth-4.2.1/gcloud/rest/auth/py.typed
--rw-r--r--   0        0        0    11655 2023-04-05 15:59:01.000000 gcloud_rest_auth-4.2.1/gcloud/rest/auth/session.py
--rw-r--r--   0        0        0     9753 2023-04-05 15:59:01.000000 gcloud_rest_auth-4.2.1/gcloud/rest/auth/token.py
--rw-r--r--   0        0        0      735 2023-04-05 15:59:01.000000 gcloud_rest_auth-4.2.1/gcloud/rest/auth/utils.py
--rw-r--r--   0        0        0        0 2023-04-05 15:59:00.000000 gcloud_rest_auth-4.2.1/gcloud/rest/py.typed
--rw-r--r--   0        0        0     1110 2023-04-05 15:59:00.000000 gcloud_rest_auth-4.2.1/pyproject.toml
--rw-r--r--   0        0        0     4128 1970-01-01 00:00:00.000000 gcloud_rest_auth-4.2.1/PKG-INFO
+-rw-r--r--   0        0        0     1063 2023-06-28 12:59:37.000000 gcloud_rest_auth-4.2.3a0/LICENSE
+-rw-r--r--   0        0        0     2998 2023-06-28 12:59:37.000000 gcloud_rest_auth-4.2.3a0/README.rst
+-rw-r--r--   0        0        0      212 2023-06-28 12:59:38.000000 gcloud_rest_auth-4.2.3a0/gcloud/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 12:59:37.000000 gcloud_rest_auth-4.2.3a0/gcloud/py.typed
+-rw-r--r--   0        0        0      216 2023-06-28 12:59:38.000000 gcloud_rest_auth-4.2.3a0/gcloud/rest/__init__.py
+-rw-r--r--   0        0        0     2048 2023-06-28 12:59:38.000000 gcloud_rest_auth-4.2.3a0/gcloud/rest/auth/__init__.py
+-rw-r--r--   0        0        0      184 2023-06-28 12:59:38.000000 gcloud_rest_auth-4.2.3a0/gcloud/rest/auth/build_constants.py
+-rw-r--r--   0        0        0     5254 2023-06-28 12:59:38.000000 gcloud_rest_auth-4.2.3a0/gcloud/rest/auth/iam.py
+-rw-r--r--   0        0        0        0 2023-06-28 12:59:37.000000 gcloud_rest_auth-4.2.3a0/gcloud/rest/auth/py.typed
+-rw-r--r--   0        0        0    11655 2023-06-28 12:59:38.000000 gcloud_rest_auth-4.2.3a0/gcloud/rest/auth/session.py
+-rw-r--r--   0        0        0     9748 2023-06-28 12:59:38.000000 gcloud_rest_auth-4.2.3a0/gcloud/rest/auth/token.py
+-rw-r--r--   0        0        0      735 2023-06-28 12:59:38.000000 gcloud_rest_auth-4.2.3a0/gcloud/rest/auth/utils.py
+-rw-r--r--   0        0        0        0 2023-06-28 12:59:37.000000 gcloud_rest_auth-4.2.3a0/gcloud/rest/py.typed
+-rw-r--r--   0        0        0     1112 2023-06-28 12:59:37.000000 gcloud_rest_auth-4.2.3a0/pyproject.toml
+-rw-r--r--   0        0        0     4130 1970-01-01 00:00:00.000000 gcloud_rest_auth-4.2.3a0/PKG-INFO
```

### Comparing `gcloud_rest_auth-4.2.1/LICENSE` & `gcloud_rest_auth-4.2.3a0/LICENSE`

 * *Files identical despite different names*

### Comparing `gcloud_rest_auth-4.2.1/README.rst` & `gcloud_rest_auth-4.2.3a0/README.rst`

 * *Files identical despite different names*

### Comparing `gcloud_rest_auth-4.2.1/gcloud/rest/auth/__init__.py` & `gcloud_rest_auth-4.2.3a0/gcloud/rest/auth/__init__.py`

 * *Files identical despite different names*

### Comparing `gcloud_rest_auth-4.2.1/gcloud/rest/auth/iam.py` & `gcloud_rest_auth-4.2.3a0/gcloud/rest/auth/iam.py`

 * *Files identical despite different names*

### Comparing `gcloud_rest_auth-4.2.1/gcloud/rest/auth/session.py` & `gcloud_rest_auth-4.2.3a0/gcloud/rest/auth/session.py`

 * *Files identical despite different names*

### Comparing `gcloud_rest_auth-4.2.1/gcloud/rest/auth/token.py` & `gcloud_rest_auth-4.2.3a0/gcloud/rest/auth/token.py`

 * *Files 0% similar despite different names*

```diff
@@ -191,15 +191,15 @@
         return project
 
     def get(self) -> Optional[str]:
         self.ensure_token()
         return self.access_token
 
     def ensure_token(self) -> None:
-        if self.acquiring and not self.acquiring.cancelled():
+        if self.acquiring and not self.acquiring.done():
             self.acquiring
             return
 
         if self.access_token:
             now = datetime.datetime.utcnow()
             delta = (now - self.access_token_acquired_at).total_seconds()
             if delta <= self.access_token_duration / 2:
```

### Comparing `gcloud_rest_auth-4.2.1/gcloud/rest/auth/utils.py` & `gcloud_rest_auth-4.2.3a0/gcloud/rest/auth/utils.py`

 * *Files identical despite different names*

### Comparing `gcloud_rest_auth-4.2.1/pyproject.toml` & `gcloud_rest_auth-4.2.3a0/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "gcloud-rest-auth"
-version = "4.2.1"
+version = "4.2.3a0"
 description = "Python Client for Google Cloud Auth"
 readme = "README.rst"
 
 repository = "https://github.com/talkiq/gcloud-aio"
 authors = ["Vi Engineering <voiceai-eng@dialpad.com>"]
 license = "MIT"
 
@@ -20,15 +20,15 @@
 ]
 
 [tool.poetry.dependencies]
 python = ">= 3.7, < 4.0"
 # aiohttp = ">= 3.3.0, < 4.0.0"
 backoff = ">= 1.0.0, < 3.0.0"
 chardet = ">= 2.0, < 6.0"
-cryptography = ">= 2.0.0, < 41.0.0"
+cryptography = ">= 2.0.0, < 42.0.0"
 pyjwt = ">= 1.5.3, < 3.0.0"
 requests = ">= 2.2.1, < 3.0.0"
 setuptools = ">= 66.0.0, < 67.0.0"  # TODO: upgrade to PEP 420 namespace packages
 
 [tool.poetry.dev-dependencies]
 pytest = ">= 4.0.0, < 8.0.0"
 # pytest-asyncio = ">= 0.16.0, < 0.22.0"
```

### Comparing `gcloud_rest_auth-4.2.1/PKG-INFO` & `gcloud_rest_auth-4.2.3a0/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: gcloud-rest-auth
-Version: 4.2.1
+Version: 4.2.3a0
 Summary: Python Client for Google Cloud Auth
 Home-page: https://github.com/talkiq/gcloud-aio
 License: MIT
 Author: Vi Engineering
 Author-email: voiceai-eng@dialpad.com
 Requires-Python: >=3.7,<4.0
 Classifier: Development Status :: 5 - Production/Stable
@@ -16,15 +16,15 @@
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Topic :: Internet
 Requires-Dist: backoff (>=1.0.0,<3.0.0)
 Requires-Dist: chardet (>=2.0,<6.0)
-Requires-Dist: cryptography (>=2.0.0,<41.0.0)
+Requires-Dist: cryptography (>=2.0.0,<42.0.0)
 Requires-Dist: pyjwt (>=1.5.3,<3.0.0)
 Requires-Dist: requests (>=2.2.1,<3.0.0)
 Requires-Dist: setuptools (>=66.0.0,<67.0.0)
 Project-URL: Repository, https://github.com/talkiq/gcloud-aio
 Description-Content-Type: text/x-rst
 
 (Asyncio OR Threadsafe) Python Client for Google Cloud Auth
```


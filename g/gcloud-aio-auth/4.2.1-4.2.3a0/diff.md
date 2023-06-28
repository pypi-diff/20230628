# Comparing `tmp/gcloud_aio_auth-4.2.1.tar.gz` & `tmp/gcloud_aio_auth-4.2.3a0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "gcloud_aio_auth-4.2.1.tar", max compression
+gzip compressed data, was "gcloud_aio_auth-4.2.3a0.tar", max compression
```

## Comparing `gcloud_aio_auth-4.2.1.tar` & `gcloud_aio_auth-4.2.3a0.tar`

### file list

```diff
@@ -1,15 +1,15 @@
--rw-r--r--   0        0        0     1063 2023-04-05 16:05:26.992140 gcloud_aio_auth-4.2.1/LICENSE
--rw-r--r--   0        0        0     2988 2023-04-05 16:05:26.992140 gcloud_aio_auth-4.2.1/README.rst
--rw-r--r--   0        0        0      212 2023-04-05 16:05:26.992140 gcloud_aio_auth-4.2.1/gcloud/__init__.py
--rw-r--r--   0        0        0      212 2023-04-05 16:05:26.992140 gcloud_aio_auth-4.2.1/gcloud/aio/__init__.py
--rw-r--r--   0        0        0     2055 2023-04-05 16:05:26.992140 gcloud_aio_auth-4.2.1/gcloud/aio/auth/__init__.py
--rw-r--r--   0        0        0      184 2023-04-05 16:05:26.992140 gcloud_aio_auth-4.2.1/gcloud/aio/auth/build_constants.py
--rw-r--r--   0        0        0     5377 2023-04-05 16:05:26.992140 gcloud_aio_auth-4.2.1/gcloud/aio/auth/iam.py
--rw-r--r--   0        0        0        0 2023-04-05 16:05:26.992140 gcloud_aio_auth-4.2.1/gcloud/aio/auth/py.typed
--rw-r--r--   0        0        0    11871 2023-04-05 16:05:26.992140 gcloud_aio_auth-4.2.1/gcloud/aio/auth/session.py
--rw-r--r--   0        0        0     9924 2023-04-05 16:05:26.992140 gcloud_aio_auth-4.2.1/gcloud/aio/auth/token.py
--rw-r--r--   0        0        0      735 2023-04-05 16:05:26.992140 gcloud_aio_auth-4.2.1/gcloud/aio/auth/utils.py
--rw-r--r--   0        0        0        0 2023-04-05 16:05:26.992140 gcloud_aio_auth-4.2.1/gcloud/aio/py.typed
--rw-r--r--   0        0        0        0 2023-04-05 16:05:26.992140 gcloud_aio_auth-4.2.1/gcloud/py.typed
--rw-r--r--   0        0        0     1105 2023-04-05 16:05:26.992140 gcloud_aio_auth-4.2.1/pyproject.toml
--rw-r--r--   0        0        0     4116 1970-01-01 00:00:00.000000 gcloud_aio_auth-4.2.1/PKG-INFO
+-rw-r--r--   0        0        0     1063 2023-06-28 13:28:28.522250 gcloud_aio_auth-4.2.3a0/LICENSE
+-rw-r--r--   0        0        0     2988 2023-06-28 13:28:28.522250 gcloud_aio_auth-4.2.3a0/README.rst
+-rw-r--r--   0        0        0      212 2023-06-28 13:28:28.522250 gcloud_aio_auth-4.2.3a0/gcloud/__init__.py
+-rw-r--r--   0        0        0      212 2023-06-28 13:28:28.522250 gcloud_aio_auth-4.2.3a0/gcloud/aio/__init__.py
+-rw-r--r--   0        0        0     2055 2023-06-28 13:28:28.522250 gcloud_aio_auth-4.2.3a0/gcloud/aio/auth/__init__.py
+-rw-r--r--   0        0        0      184 2023-06-28 13:28:28.522250 gcloud_aio_auth-4.2.3a0/gcloud/aio/auth/build_constants.py
+-rw-r--r--   0        0        0     5377 2023-06-28 13:28:28.522250 gcloud_aio_auth-4.2.3a0/gcloud/aio/auth/iam.py
+-rw-r--r--   0        0        0        0 2023-06-28 13:28:28.522250 gcloud_aio_auth-4.2.3a0/gcloud/aio/auth/py.typed
+-rw-r--r--   0        0        0    11871 2023-06-28 13:28:28.522250 gcloud_aio_auth-4.2.3a0/gcloud/aio/auth/session.py
+-rw-r--r--   0        0        0     9919 2023-06-28 13:28:28.522250 gcloud_aio_auth-4.2.3a0/gcloud/aio/auth/token.py
+-rw-r--r--   0        0        0      735 2023-06-28 13:28:28.522250 gcloud_aio_auth-4.2.3a0/gcloud/aio/auth/utils.py
+-rw-r--r--   0        0        0        0 2023-06-28 13:28:28.522250 gcloud_aio_auth-4.2.3a0/gcloud/aio/py.typed
+-rw-r--r--   0        0        0        0 2023-06-28 13:28:28.522250 gcloud_aio_auth-4.2.3a0/gcloud/py.typed
+-rw-r--r--   0        0        0     1107 2023-06-28 13:28:28.522250 gcloud_aio_auth-4.2.3a0/pyproject.toml
+-rw-r--r--   0        0        0     4118 1970-01-01 00:00:00.000000 gcloud_aio_auth-4.2.3a0/PKG-INFO
```

### Comparing `gcloud_aio_auth-4.2.1/LICENSE` & `gcloud_aio_auth-4.2.3a0/LICENSE`

 * *Files identical despite different names*

### Comparing `gcloud_aio_auth-4.2.1/README.rst` & `gcloud_aio_auth-4.2.3a0/README.rst`

 * *Files identical despite different names*

### Comparing `gcloud_aio_auth-4.2.1/gcloud/aio/auth/__init__.py` & `gcloud_aio_auth-4.2.3a0/gcloud/aio/auth/__init__.py`

 * *Files identical despite different names*

### Comparing `gcloud_aio_auth-4.2.1/gcloud/aio/auth/iam.py` & `gcloud_aio_auth-4.2.3a0/gcloud/aio/auth/iam.py`

 * *Files identical despite different names*

### Comparing `gcloud_aio_auth-4.2.1/gcloud/aio/auth/session.py` & `gcloud_aio_auth-4.2.3a0/gcloud/aio/auth/session.py`

 * *Files identical despite different names*

### Comparing `gcloud_aio_auth-4.2.1/gcloud/aio/auth/token.py` & `gcloud_aio_auth-4.2.3a0/gcloud/aio/auth/token.py`

 * *Files 1% similar despite different names*

```diff
@@ -191,15 +191,15 @@
         return project
 
     async def get(self) -> Optional[str]:
         await self.ensure_token()
         return self.access_token
 
     async def ensure_token(self) -> None:
-        if self.acquiring and not self.acquiring.cancelled():
+        if self.acquiring and not self.acquiring.done():
             await self.acquiring
             return
 
         if self.access_token:
             now = datetime.datetime.utcnow()
             delta = (now - self.access_token_acquired_at).total_seconds()
             if delta <= self.access_token_duration / 2:
```

### Comparing `gcloud_aio_auth-4.2.1/gcloud/aio/auth/utils.py` & `gcloud_aio_auth-4.2.3a0/gcloud/aio/auth/utils.py`

 * *Files identical despite different names*

### Comparing `gcloud_aio_auth-4.2.1/pyproject.toml` & `gcloud_aio_auth-4.2.3a0/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "gcloud-aio-auth"
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
 aiohttp = ">= 3.3.0, < 4.0.0"
 backoff = ">= 1.0.0, < 3.0.0"
 chardet = ">= 2.0, < 6.0"
-cryptography = ">= 2.0.0, < 41.0.0"
+cryptography = ">= 2.0.0, < 42.0.0"
 pyjwt = ">= 1.5.3, < 3.0.0"
 # requests = ">= 2.2.1, < 3.0.0"
 setuptools = ">= 66.0.0, < 67.0.0"  # TODO: upgrade to PEP 420 namespace packages
 
 [tool.poetry.dev-dependencies]
 pytest = ">= 4.0.0, < 8.0.0"
 pytest-asyncio = ">= 0.16.0, < 0.22.0"
```

### Comparing `gcloud_aio_auth-4.2.1/PKG-INFO` & `gcloud_aio_auth-4.2.3a0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: gcloud-aio-auth
-Version: 4.2.1
+Version: 4.2.3a0
 Summary: Python Client for Google Cloud Auth
 Home-page: https://github.com/talkiq/gcloud-aio
 License: MIT
 Author: Vi Engineering
 Author-email: voiceai-eng@dialpad.com
 Requires-Python: >=3.7,<4.0
 Classifier: Development Status :: 5 - Production/Stable
@@ -17,15 +17,15 @@
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Topic :: Internet
 Requires-Dist: aiohttp (>=3.3.0,<4.0.0)
 Requires-Dist: backoff (>=1.0.0,<3.0.0)
 Requires-Dist: chardet (>=2.0,<6.0)
-Requires-Dist: cryptography (>=2.0.0,<41.0.0)
+Requires-Dist: cryptography (>=2.0.0,<42.0.0)
 Requires-Dist: pyjwt (>=1.5.3,<3.0.0)
 Requires-Dist: setuptools (>=66.0.0,<67.0.0)
 Project-URL: Repository, https://github.com/talkiq/gcloud-aio
 Description-Content-Type: text/x-rst
 
 (Asyncio OR Threadsafe) Python Client for Google Cloud Auth
 ===========================================================
```


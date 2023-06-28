# Comparing `tmp/amcat4py-4.0.12.tar.gz` & `tmp/amcat4py-4.0.13.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "amcat4py-4.0.12.tar", last modified: Wed Mar 15 09:25:02 2023, max compression
+gzip compressed data, was "amcat4py-4.0.13.tar", last modified: Wed Jun 28 11:50:47 2023, max compression
```

## Comparing `amcat4py-4.0.12.tar` & `amcat4py-4.0.13.tar`

### file list

```diff
@@ -1,9 +1,9 @@
-drwxrwxr-x   0 nel       (1000) nel       (1000)        0 2023-03-15 09:25:02.698279 amcat4py-4.0.12/
--rw-rw-r--   0 nel       (1000) nel       (1000)      390 2023-03-15 09:25:02.698279 amcat4py-4.0.12/PKG-INFO
-drwxrwxr-x   0 nel       (1000) nel       (1000)        0 2023-03-15 09:25:02.698279 amcat4py-4.0.12/amcat4py/
--rw-rw-r--   0 nel       (1000) nel       (1000)       37 2023-03-15 08:25:37.501577 amcat4py-4.0.12/amcat4py/__init__.py
--rw-rw-r--   0 nel       (1000) nel       (1000)     1780 2023-03-15 08:25:37.501577 amcat4py-4.0.12/amcat4py/__main__.py
--rw-rw-r--   0 nel       (1000) nel       (1000)    14276 2023-03-15 09:24:21.009577 amcat4py-4.0.12/amcat4py/amcatclient.py
--rw-rw-r--   0 nel       (1000) nel       (1000)     7549 2023-03-15 08:25:37.501577 amcat4py-4.0.12/amcat4py/auth.py
--rw-rw-r--   0 nel       (1000) nel       (1000)     1602 2023-03-15 08:25:37.501577 amcat4py-4.0.12/amcat4py/copy_index.py
--rw-rw-r--   0 nel       (1000) nel       (1000)      723 2023-03-15 09:23:13.112428 amcat4py-4.0.12/setup.py
+drwxrwxr-x   0 wva       (1000) wva       (1000)        0 2023-06-28 11:50:47.904137 amcat4py-4.0.13/
+-rw-rw-r--   0 wva       (1000) wva       (1000)      390 2023-06-28 11:50:47.904137 amcat4py-4.0.13/PKG-INFO
+drwxrwxr-x   0 wva       (1000) wva       (1000)        0 2023-06-28 11:50:47.904137 amcat4py-4.0.13/amcat4py/
+-rw-rw-r--   0 wva       (1000) wva       (1000)       37 2023-06-28 11:38:49.375105 amcat4py-4.0.13/amcat4py/__init__.py
+-rw-rw-r--   0 wva       (1000) wva       (1000)     1780 2023-06-28 11:38:49.375105 amcat4py-4.0.13/amcat4py/__main__.py
+-rw-rw-r--   0 wva       (1000) wva       (1000)    14677 2023-06-28 11:38:49.375105 amcat4py-4.0.13/amcat4py/amcatclient.py
+-rw-rw-r--   0 wva       (1000) wva       (1000)     7606 2023-06-28 11:48:38.736418 amcat4py-4.0.13/amcat4py/auth.py
+-rw-rw-r--   0 wva       (1000) wva       (1000)     1602 2023-06-28 11:38:49.379105 amcat4py-4.0.13/amcat4py/copy_index.py
+-rw-rw-r--   0 wva       (1000) wva       (1000)      723 2023-06-28 11:50:10.552332 amcat4py-4.0.13/setup.py
```

### Comparing `amcat4py-4.0.12/amcat4py/__main__.py` & `amcat4py-4.0.13/amcat4py/__main__.py`

 * *Files identical despite different names*

### Comparing `amcat4py-4.0.12/amcat4py/amcatclient.py` & `amcat4py-4.0.13/amcat4py/amcatclient.py`

 * *Files 4% similar despite different names*

```diff
@@ -107,14 +107,22 @@
 
     def _put(self, url=None, index=None, json=None, ignore_status=None):
         return self._request("put", url=self._url(url, index), json=json, ignore_status=ignore_status)
 
     def _delete(self, url=None, index=None, ignore_status=None):
         return self._request("delete", url=self._url(url, index), ignore_status=ignore_status)
 
+    def get_user(self, user: str = 'me'):
+        """Get information on the given user, or on self if no user is given
+
+        Args:
+            user (string, optional): Username (email) to get information on. Defaults to 'me'.
+        """
+        return self._get(f"users/{user}")
+
     def list_indices(self) -> List[dict]:
         """
         List all indices on this server
         :return: a list of index dicts with keys name and (your) role
         """
         return self._get("index/").json()
 
@@ -189,15 +197,15 @@
                 for date_field in date_fields:
                     if res.get(date_field):
                         date = res[date_field][:10] if self.ignore_tz else res[date_field]
                         res[date_field] = datetime.fromisoformat(date)
                 yield res
             body['scroll_id'] = d['meta']['scroll_id']
 
-    def query_aggregate(self, 
+    def query_aggregate(self,
                         index: str, *,
                         axes: Union[str, list, dict] = None,
                         queries: Union[str, list, dict] = None,
                         filters: Dict[str, Union[str, list, dict]] = None):
         """
         Execute a search query on this server and aggregate results
 
@@ -206,29 +214,32 @@
         :param queries: One or more query strings or objects to search for
         :param filters: A dictionary of filters to apply to the search
         :return: an iterator over the search results, with the requested (or all) fields
         """
         body = {"axes": axes, "queries": queries, "filters": filters}
         return self._post(f"index/{index}/aggregate", json=body).json()['data']
 
-    def create_index(self, index: str, guest_role: Optional[str] = None):
-        body = {"name": index}
+    def create_index(self, index: str, name: str = None, description: str = None, guest_role: Optional[str] = None):
+        body = {"id": index,
+                "name": name or index}
         if guest_role:
             body['guest_role'] = guest_role
+        if description:
+            body['description'] = description
         return self._post("index/", json=body).json()
 
-    def create_user(self, email, global_role=None):
+    def create_user(self, email, role=None):
         """
         Create a new user
         :param email: Email address of the new user to add
-        :param global_role: global role of the user ("writer" or "admin")
+        :param role: global role of the user ("writer" or "admin")
         """
         body = {
             "email": email,
-            "global_role": global_role,
+            "role": role,
         }
         return self._post("users/", json=body).json()
 
     def delete_user(self, email):
         """
         Delete a user from the instance
         :param email: Email address of the new user to add
@@ -259,15 +270,15 @@
         return self._put(f"index/{index}/users/{email}", json=body).json()
 
     def check_index(self, ix: str) -> Optional[dict]:
         r = self._get(index=ix, ignore_status=[404])
         if r.status_code == 404:
             return None
         return r.json()
-    
+
     def refresh_index(self, ix: str) -> None:
         """Refresh (flush) this index"""
         self._get(f"index/{ix}/refresh")
 
     def delete_index(self, index: str) -> bool:
         """Delete this index"""
         r = self._delete(index=index, ignore_status=[404])
```

### Comparing `amcat4py-4.0.12/amcat4py/auth.py` & `amcat4py-4.0.13/amcat4py/auth.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,14 +2,15 @@
 from typing import Optional
 
 import requests
 import os
 from appdirs import user_cache_dir
 from base64 import urlsafe_b64encode, b64encode
 from cryptography.fernet import Fernet
+from cryptography.hazmat.primitives import hashes
 from cryptography.hazmat.primitives.kdf.pbkdf2 import PBKDF2HMAC
 from datetime import datetime, timedelta
 from hashlib import sha256
 from json import dumps, loads
 from random import getrandbits
 from re import search
 from requests_oauthlib import OAuth2Session
@@ -179,15 +180,15 @@
 
 def make_key(key) -> bytes:
     """
     Helper function to make key for encryption of tokens
     :param key: string that is turned into key.
     """
     kdf = PBKDF2HMAC(
-        algorithm=sha256(),
+        algorithm=hashes.SHA256(),
         length=32,
         salt="supergeheim".encode(),
         iterations=5,
     )
     return urlsafe_b64encode(kdf.derive(key.encode()))
```

### Comparing `amcat4py-4.0.12/amcat4py/copy_index.py` & `amcat4py-4.0.13/amcat4py/copy_index.py`

 * *Files identical despite different names*

### Comparing `amcat4py-4.0.12/setup.py` & `amcat4py-4.0.13/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 #!/usr/bin/env python
 
 from distutils.core import setup
 
 setup(
     name="amcat4py",
-    version="4.0.12",
+    version="4.0.13",
     description="Python client for AmCAT4 API",
     author="Wouter van Atteveldt",
     author_email="wouter@vanatteveldt.com",
     packages=["amcat4py"],
     include_package_data=False,
     zip_safe=False,
     keywords=["API", "text"],
```


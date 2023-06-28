# Comparing `tmp/ciphertrust-sdk-1.0.5.tar.gz` & `tmp/ciphertrust-sdk-1.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ciphertrust-sdk-1.0.5.tar", last modified: Tue Jun 27 17:40:50 2023, max compression
+gzip compressed data, was "ciphertrust-sdk-1.0.6.tar", last modified: Wed Jun 28 00:52:54 2023, max compression
```

## Comparing `ciphertrust-sdk-1.0.5.tar` & `ciphertrust-sdk-1.0.6.tar`

### file list

```diff
@@ -1,24 +1,24 @@
-drwxr-xr-x   0 adamt      (501) staff       (20)        0 2023-06-27 17:40:50.353685 ciphertrust-sdk-1.0.5/
--rw-rw-r--   0 adamt      (501) staff       (20)     1064 2023-06-27 17:34:33.000000 ciphertrust-sdk-1.0.5/LICENSE
--rw-r--r--   0 adamt      (501) staff       (20)     5381 2023-06-27 17:40:50.353111 ciphertrust-sdk-1.0.5/PKG-INFO
--rw-rw-r--   0 adamt      (501) staff       (20)     3698 2023-06-27 17:34:33.000000 ciphertrust-sdk-1.0.5/README.md
-drwxr-xr-x   0 adamt      (501) staff       (20)        0 2023-06-27 17:40:50.345597 ciphertrust-sdk-1.0.5/ciphertrust_sdk.egg-info/
--rw-r--r--   0 adamt      (501) staff       (20)     5381 2023-06-27 17:40:50.000000 ciphertrust-sdk-1.0.5/ciphertrust_sdk.egg-info/PKG-INFO
--rw-r--r--   0 adamt      (501) staff       (20)      492 2023-06-27 17:40:50.000000 ciphertrust-sdk-1.0.5/ciphertrust_sdk.egg-info/SOURCES.txt
--rw-r--r--   0 adamt      (501) staff       (20)        1 2023-06-27 17:40:50.000000 ciphertrust-sdk-1.0.5/ciphertrust_sdk.egg-info/dependency_links.txt
--rw-r--r--   0 adamt      (501) staff       (20)       94 2023-06-27 17:40:50.000000 ciphertrust-sdk-1.0.5/ciphertrust_sdk.egg-info/requires.txt
--rw-r--r--   0 adamt      (501) staff       (20)       12 2023-06-27 17:40:50.000000 ciphertrust-sdk-1.0.5/ciphertrust_sdk.egg-info/top_level.txt
--rw-rw-r--   0 adamt      (501) staff       (20)     1054 2023-06-27 17:34:33.000000 ciphertrust-sdk-1.0.5/pyproject.toml
--rw-r--r--   0 adamt      (501) staff       (20)       38 2023-06-27 17:40:50.353890 ciphertrust-sdk-1.0.5/setup.cfg
-drwxr-xr-x   0 adamt      (501) staff       (20)        0 2023-06-27 17:40:50.341423 ciphertrust-sdk-1.0.5/src/
-drwxr-xr-x   0 adamt      (501) staff       (20)        0 2023-06-27 17:40:50.352563 ciphertrust-sdk-1.0.5/src/ciphertrust/
--rw-rw-r--   0 adamt      (501) staff       (20)      134 2023-06-27 17:34:33.000000 ciphertrust-sdk-1.0.5/src/ciphertrust/__init__.py
--rw-rw-r--   0 adamt      (501) staff       (20)       42 2023-06-27 17:34:33.000000 ciphertrust-sdk-1.0.5/src/ciphertrust/_version.py
--rw-rw-r--   0 adamt      (501) staff       (20)     6555 2023-06-27 17:34:33.000000 ciphertrust-sdk-1.0.5/src/ciphertrust/api.py
--rw-rw-r--   0 adamt      (501) staff       (20)     8086 2023-06-27 17:34:33.000000 ciphertrust-sdk-1.0.5/src/ciphertrust/auth.py
--rw-rw-r--   0 adamt      (501) staff       (20)      248 2023-06-27 17:34:33.000000 ciphertrust-sdk-1.0.5/src/ciphertrust/config.py
--rw-rw-r--   0 adamt      (501) staff       (20)      471 2023-06-27 17:34:33.000000 ciphertrust-sdk-1.0.5/src/ciphertrust/exceptions.py
--rw-rw-r--   0 adamt      (501) staff       (20)     3752 2023-06-27 17:34:33.000000 ciphertrust-sdk-1.0.5/src/ciphertrust/models.py
--rw-rw-r--   0 adamt      (501) staff       (20)    12186 2023-06-27 17:34:33.000000 ciphertrust-sdk-1.0.5/src/ciphertrust/requestapi.py
--rw-rw-r--   0 adamt      (501) staff       (20)      417 2023-06-27 17:34:33.000000 ciphertrust-sdk-1.0.5/src/ciphertrust/static.py
--rw-rw-r--   0 adamt      (501) staff       (20)     7111 2023-06-27 17:34:33.000000 ciphertrust-sdk-1.0.5/src/ciphertrust/utils.py
+drwxr-xr-x   0 adamt      (501) staff       (20)        0 2023-06-28 00:52:54.573445 ciphertrust-sdk-1.0.6/
+-rw-rw-r--   0 adamt      (501) staff       (20)     1064 2023-06-28 00:46:57.000000 ciphertrust-sdk-1.0.6/LICENSE
+-rw-r--r--   0 adamt      (501) staff       (20)     5520 2023-06-28 00:52:54.572741 ciphertrust-sdk-1.0.6/PKG-INFO
+-rw-rw-r--   0 adamt      (501) staff       (20)     3837 2023-06-28 00:46:57.000000 ciphertrust-sdk-1.0.6/README.md
+drwxr-xr-x   0 adamt      (501) staff       (20)        0 2023-06-28 00:52:54.563877 ciphertrust-sdk-1.0.6/ciphertrust_sdk.egg-info/
+-rw-r--r--   0 adamt      (501) staff       (20)     5520 2023-06-28 00:52:54.000000 ciphertrust-sdk-1.0.6/ciphertrust_sdk.egg-info/PKG-INFO
+-rw-r--r--   0 adamt      (501) staff       (20)      492 2023-06-28 00:52:54.000000 ciphertrust-sdk-1.0.6/ciphertrust_sdk.egg-info/SOURCES.txt
+-rw-r--r--   0 adamt      (501) staff       (20)        1 2023-06-28 00:52:54.000000 ciphertrust-sdk-1.0.6/ciphertrust_sdk.egg-info/dependency_links.txt
+-rw-r--r--   0 adamt      (501) staff       (20)       94 2023-06-28 00:52:54.000000 ciphertrust-sdk-1.0.6/ciphertrust_sdk.egg-info/requires.txt
+-rw-r--r--   0 adamt      (501) staff       (20)       12 2023-06-28 00:52:54.000000 ciphertrust-sdk-1.0.6/ciphertrust_sdk.egg-info/top_level.txt
+-rw-rw-r--   0 adamt      (501) staff       (20)     1054 2023-06-28 00:46:57.000000 ciphertrust-sdk-1.0.6/pyproject.toml
+-rw-r--r--   0 adamt      (501) staff       (20)       38 2023-06-28 00:52:54.573683 ciphertrust-sdk-1.0.6/setup.cfg
+drwxr-xr-x   0 adamt      (501) staff       (20)        0 2023-06-28 00:52:54.558964 ciphertrust-sdk-1.0.6/src/
+drwxr-xr-x   0 adamt      (501) staff       (20)        0 2023-06-28 00:52:54.571627 ciphertrust-sdk-1.0.6/src/ciphertrust/
+-rw-rw-r--   0 adamt      (501) staff       (20)      134 2023-06-28 00:46:57.000000 ciphertrust-sdk-1.0.6/src/ciphertrust/__init__.py
+-rw-rw-r--   0 adamt      (501) staff       (20)       42 2023-06-28 00:46:57.000000 ciphertrust-sdk-1.0.6/src/ciphertrust/_version.py
+-rw-rw-r--   0 adamt      (501) staff       (20)     6593 2023-06-28 00:46:57.000000 ciphertrust-sdk-1.0.6/src/ciphertrust/api.py
+-rw-rw-r--   0 adamt      (501) staff       (20)     8102 2023-06-28 00:46:57.000000 ciphertrust-sdk-1.0.6/src/ciphertrust/auth.py
+-rw-rw-r--   0 adamt      (501) staff       (20)      248 2023-06-28 00:46:57.000000 ciphertrust-sdk-1.0.6/src/ciphertrust/config.py
+-rw-rw-r--   0 adamt      (501) staff       (20)      471 2023-06-28 00:46:57.000000 ciphertrust-sdk-1.0.6/src/ciphertrust/exceptions.py
+-rw-rw-r--   0 adamt      (501) staff       (20)     3752 2023-06-28 00:46:57.000000 ciphertrust-sdk-1.0.6/src/ciphertrust/models.py
+-rw-rw-r--   0 adamt      (501) staff       (20)    12567 2023-06-28 00:46:57.000000 ciphertrust-sdk-1.0.6/src/ciphertrust/requestapi.py
+-rw-rw-r--   0 adamt      (501) staff       (20)      417 2023-06-28 00:46:57.000000 ciphertrust-sdk-1.0.6/src/ciphertrust/static.py
+-rw-rw-r--   0 adamt      (501) staff       (20)     7111 2023-06-28 00:46:57.000000 ciphertrust-sdk-1.0.6/src/ciphertrust/utils.py
```

### Comparing `ciphertrust-sdk-1.0.5/LICENSE` & `ciphertrust-sdk-1.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `ciphertrust-sdk-1.0.5/PKG-INFO` & `ciphertrust-sdk-1.0.6/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ciphertrust-sdk
-Version: 1.0.5
+Version: 1.0.6
 Summary: Thales CipherTrust SDK RestAPI
 Author-email: atav928 <dev@tavnets.com>
 License: MIT License
         
         Copyright (c) 2023 atav928
         
         Permission is hereby granted, free of charge, to any person obtaining a copy
@@ -33,15 +33,15 @@
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # ciphertrust-sdk
 
  Thales CipherTrust API
 
- ## Installation
+## Installation
 
  ```bash
  >>> python -m pip install ciphertrust-sdk
  ```
 
 ## Usage
 
@@ -104,22 +104,23 @@
 }
 ```
 
 ## Version
 
 | Version | Build | Changes |
 | ------- | ----- | ------- |
-| **0.0.1** | **final** | Test Relese; basic functionality |
-| **1.0.1** | **final** | Available Release with API and Auth functionality |
-| **1.0.2** | **a1** | Removed print |
-| **1.0.2** | **a2** | Added metrics in calls and additional awaits to call on mutliple calls |
-| **1.0.2** | **final** | See notes below |
-| **1.0.3** | **final** | See notes below |
-| **1.0.4** | **final** | See notes below |
-| **1.0.5** | **final** | Fixed bug passing directory param in downloads call |
+| __0.0.1__ | __final__ | Test Relese; basic functionality |
+| __1.0.1__ | __final__ | Available Release with API and Auth functionality |
+| __1.0.2__ | __a1__ | Removed print |
+| __1.0.2__ | __a2__ | Added metrics in calls and additional awaits to call on mutliple calls |
+| __1.0.2__ | __final__ | See notes below |
+| __1.0.3__ | __final__ | See notes below |
+| __1.0.4__ | __final__ | See notes below |
+| __1.0.5__ | __final__ | Fixed bug passing directory param in downloads call |
+| __1.0.6__ | __final__ | HOTFIX with generic call |
 
 ### Known Bugs/Futue Features
 
 __TODO:__
 
 * &#9745; Create a metrics fucntion to return
 * &#9745; Delete all private aand passwords being printed
@@ -129,23 +130,27 @@
   * &#9744; Logging metrics wrapper
 * &#9745; Create an average, mean, total time depending on calls being made for when you want to do a full list of keys
 * &#9745; Missing delete https action
 * &#9745; Create a download method to handle downlaoding files
 
 #### Release Notes
 
-#### v1.0.5
+#### v1.0.6
 
-* Bug fixed with passing "save_dir" into get call for downloading log files.
+* __HOTFIX__ Issue with sandard get call passes invalid arg to response.
 
 __TODO:__
 
 * Need to build additional async requests when calling multiple items.
 * Build out ability to send multiple requests and hold the type of requests to make it easier to use the SDK.
 
+#### v1.0.5
+
+* Bug fixed with passing "save_dir" into get call for downloading log files.
+
 #### v1.0.4
 
 * Updated standard download log file to include hostname in filename.
 
 #### v1.0.3
 
 * Fixed bug with headers returning a requests.exceptions.JSONDecodeError due to the way headers are formated.
```

### Comparing `ciphertrust-sdk-1.0.5/README.md` & `ciphertrust-sdk-1.0.6/README.md`

 * *Files 13% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 # ciphertrust-sdk
 
  Thales CipherTrust API
 
- ## Installation
+## Installation
 
  ```bash
  >>> python -m pip install ciphertrust-sdk
  ```
 
 ## Usage
 
@@ -69,22 +69,23 @@
 }
 ```
 
 ## Version
 
 | Version | Build | Changes |
 | ------- | ----- | ------- |
-| **0.0.1** | **final** | Test Relese; basic functionality |
-| **1.0.1** | **final** | Available Release with API and Auth functionality |
-| **1.0.2** | **a1** | Removed print |
-| **1.0.2** | **a2** | Added metrics in calls and additional awaits to call on mutliple calls |
-| **1.0.2** | **final** | See notes below |
-| **1.0.3** | **final** | See notes below |
-| **1.0.4** | **final** | See notes below |
-| **1.0.5** | **final** | Fixed bug passing directory param in downloads call |
+| __0.0.1__ | __final__ | Test Relese; basic functionality |
+| __1.0.1__ | __final__ | Available Release with API and Auth functionality |
+| __1.0.2__ | __a1__ | Removed print |
+| __1.0.2__ | __a2__ | Added metrics in calls and additional awaits to call on mutliple calls |
+| __1.0.2__ | __final__ | See notes below |
+| __1.0.3__ | __final__ | See notes below |
+| __1.0.4__ | __final__ | See notes below |
+| __1.0.5__ | __final__ | Fixed bug passing directory param in downloads call |
+| __1.0.6__ | __final__ | HOTFIX with generic call |
 
 ### Known Bugs/Futue Features
 
 __TODO:__
 
 * &#9745; Create a metrics fucntion to return
 * &#9745; Delete all private aand passwords being printed
@@ -94,23 +95,27 @@
   * &#9744; Logging metrics wrapper
 * &#9745; Create an average, mean, total time depending on calls being made for when you want to do a full list of keys
 * &#9745; Missing delete https action
 * &#9745; Create a download method to handle downlaoding files
 
 #### Release Notes
 
-#### v1.0.5
+#### v1.0.6
 
-* Bug fixed with passing "save_dir" into get call for downloading log files.
+* __HOTFIX__ Issue with sandard get call passes invalid arg to response.
 
 __TODO:__
 
 * Need to build additional async requests when calling multiple items.
 * Build out ability to send multiple requests and hold the type of requests to make it easier to use the SDK.
 
+#### v1.0.5
+
+* Bug fixed with passing "save_dir" into get call for downloading log files.
+
 #### v1.0.4
 
 * Updated standard download log file to include hostname in filename.
 
 #### v1.0.3
 
 * Fixed bug with headers returning a requests.exceptions.JSONDecodeError due to the way headers are formated.
```

### Comparing `ciphertrust-sdk-1.0.5/ciphertrust_sdk.egg-info/PKG-INFO` & `ciphertrust-sdk-1.0.6/ciphertrust_sdk.egg-info/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ciphertrust-sdk
-Version: 1.0.5
+Version: 1.0.6
 Summary: Thales CipherTrust SDK RestAPI
 Author-email: atav928 <dev@tavnets.com>
 License: MIT License
         
         Copyright (c) 2023 atav928
         
         Permission is hereby granted, free of charge, to any person obtaining a copy
@@ -33,15 +33,15 @@
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # ciphertrust-sdk
 
  Thales CipherTrust API
 
- ## Installation
+## Installation
 
  ```bash
  >>> python -m pip install ciphertrust-sdk
  ```
 
 ## Usage
 
@@ -104,22 +104,23 @@
 }
 ```
 
 ## Version
 
 | Version | Build | Changes |
 | ------- | ----- | ------- |
-| **0.0.1** | **final** | Test Relese; basic functionality |
-| **1.0.1** | **final** | Available Release with API and Auth functionality |
-| **1.0.2** | **a1** | Removed print |
-| **1.0.2** | **a2** | Added metrics in calls and additional awaits to call on mutliple calls |
-| **1.0.2** | **final** | See notes below |
-| **1.0.3** | **final** | See notes below |
-| **1.0.4** | **final** | See notes below |
-| **1.0.5** | **final** | Fixed bug passing directory param in downloads call |
+| __0.0.1__ | __final__ | Test Relese; basic functionality |
+| __1.0.1__ | __final__ | Available Release with API and Auth functionality |
+| __1.0.2__ | __a1__ | Removed print |
+| __1.0.2__ | __a2__ | Added metrics in calls and additional awaits to call on mutliple calls |
+| __1.0.2__ | __final__ | See notes below |
+| __1.0.3__ | __final__ | See notes below |
+| __1.0.4__ | __final__ | See notes below |
+| __1.0.5__ | __final__ | Fixed bug passing directory param in downloads call |
+| __1.0.6__ | __final__ | HOTFIX with generic call |
 
 ### Known Bugs/Futue Features
 
 __TODO:__
 
 * &#9745; Create a metrics fucntion to return
 * &#9745; Delete all private aand passwords being printed
@@ -129,23 +130,27 @@
   * &#9744; Logging metrics wrapper
 * &#9745; Create an average, mean, total time depending on calls being made for when you want to do a full list of keys
 * &#9745; Missing delete https action
 * &#9745; Create a download method to handle downlaoding files
 
 #### Release Notes
 
-#### v1.0.5
+#### v1.0.6
 
-* Bug fixed with passing "save_dir" into get call for downloading log files.
+* __HOTFIX__ Issue with sandard get call passes invalid arg to response.
 
 __TODO:__
 
 * Need to build additional async requests when calling multiple items.
 * Build out ability to send multiple requests and hold the type of requests to make it easier to use the SDK.
 
+#### v1.0.5
+
+* Bug fixed with passing "save_dir" into get call for downloading log files.
+
 #### v1.0.4
 
 * Updated standard download log file to include hostname in filename.
 
 #### v1.0.3
 
 * Fixed bug with headers returning a requests.exceptions.JSONDecodeError due to the way headers are formated.
```

### Comparing `ciphertrust-sdk-1.0.5/pyproject.toml` & `ciphertrust-sdk-1.0.6/pyproject.toml`

 * *Files identical despite different names*

### Comparing `ciphertrust-sdk-1.0.5/src/ciphertrust/api.py` & `ciphertrust-sdk-1.0.6/src/ciphertrust/api.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,35 +1,35 @@
 # pylint: disable=too-few-public-methods,missing-class-docstring
-"""API"""
+"""CipherTrust API"""
 
 from typing import Any, Dict
 import orjson
 
 from ciphertrust import config
 from ciphertrust.auth import Auth
 from ciphertrust.requestapi import (ctm_request, asyn_get_all)
 from ciphertrust.static import ENCODE
 
 
 class API:
-    """CipherTrust Manager API"""
+    """CipherTrust Manager API."""
 
-    def __init__(self, **kwargs: Any):
+    def __init__(self, **kwargs: Any) -> None:
+        """Generate API to call to CipherTrust Manager."""
         self.auth = Auth(**kwargs)
-
         # Bind API method classes to this object
         subclasses: dict[str, Any] = self._subclass_container()
-        self.get = subclasses["get"]()
-        self.post = subclasses["post"]()
-        self.patch = subclasses["patch"]()
-        self.delete = subclasses["delete"]()
-
-    def _subclass_container(self) -> dict[str,Any]:
-        _parent_class = self
-        return_object: dict[str,Any] = {}
+        self.get: Any = subclasses["get"]()
+        self.post: Any = subclasses["post"]()
+        self.patch: Any = subclasses["patch"]()
+        self.delete: Any = subclasses["delete"]()
+
+    def _subclass_container(self) -> dict[str, Any]:
+        _parent_class: Any = self
+        return_object: dict[str, Any] = {}
 
         class GetWrapper(Get):
             def __init__(self) -> None:
                 self._parent_class = _parent_class
         return_object["get"] = GetWrapper
 
         class PostWrapper(Post):
@@ -44,132 +44,147 @@
 
         class DeleteWrapper(Delete):
             def __init__(self) -> None:
                 self._parent_class = _parent_class
         return_object["delete"] = DeleteWrapper
         return return_object
 
-    def convert_to_string(self, query: dict[str,Any]) -> str:
-        """convert json to string
+    def convert_to_string(self, query: dict[str, Any]) -> str:
+        """Convert json to string.
 
         :param query: _description_
         :type query: dict
         :return: _description_
         :rtype: str
         """
         return orjson.dumps(query).decode(ENCODE)  # pylint: disable=no-member
 
 
 class Get:
-    """Calls generic GET requests from CipherTrust Manager
+    """Calls generic GET requests from CipherTrust Manager.
 
     :return: _description_
     :rtype: _type_
     """
+
     _parent_class = None
-    method = "GET"
+    method: str = "GET"
 
     def call(self, url_path: str, **kwargs: Any) -> dict[str, Any]:
-        """Generic Call Method
+        """Call Method for GET Requests.
 
         :param url_path: _description_
         :type url_path: str
         :return: _description_
         :rtype: dict[str, Any]
         """
-        url: str = config.API_URL.format(self._parent_class.auth.hostname, # type: ignore
+
+        url: str = config.API_URL.format(self._parent_class.auth.hostname,  # type: ignore
                                          url_path)
-        params: dict[str,Any] = kwargs.pop("params", {})
+        params: dict[str, Any] = kwargs.pop("params", {})
         stream: bool = kwargs.pop("stream", False)
         calls = {
             "standard": ctm_request,
             "list_all": asyn_get_all
         }
         get_all = "list_all" if kwargs.get("get_all", False) else "standard"
-        response: dict[str,Any] = calls[get_all](auth=self._parent_class.auth, # type: ignore
-                                                 url=url,
-                                                 method=self.method, # type: ignore
-                                                 params=params,
-                                                 timeout=self._parent_class.auth.timeout, # type: ignore
-                                                 stream=stream,
-                                                 verify=self._parent_class.auth.verify,  # type: ignore
-                                                 save_dir=kwargs.pop("save_dir", ""))
+        response: dict[str, Any] = calls[get_all](
+            auth=self._parent_class.auth,  # type: ignore
+            url=url,  # type: ignore
+            method=self.method,  # type: ignore
+            params=params,
+            timeout=self._parent_class.auth.timeout,  # type: ignore
+            stream=stream,  # type: ignore
+            verify=self._parent_class.auth.verify,  # type: ignore
+            save_dir=kwargs.pop("save_dir", ""))
         return response
 
 
 class Post:
-    """Calls generic POST requests for CipherTrust Manager
+    """Calls generic POST requests for CipherTrust Manager.
 
     :return: _description_
     :rtype: _type_
     """
     _parent_class = None
     method: str = "POST"
 
     def call(self, url_path: str, **kwargs: Any) -> Dict[str, Any]:
-        """POST call for CipherTrust Manager
+        """POST call for CipherTrust Manager.
 
         :param url_path: _description_
         :type url_path: str
         """
-        url: str = config.API_URL.format(self._parent_class.auth.hostname, url_path) # type: ignore
-        params: dict[str,Any] = kwargs.pop("params", {})
-        data: str = self._parent_class.convert_to_string( # type: ignore
+        url: str = config.API_URL.format(self._parent_class.auth.hostname, url_path)  # type: ignore
+        params: dict[str, Any] = kwargs.pop("params", {})
+        data: str = self._parent_class.convert_to_string(  # type: ignore
             query=kwargs.pop("query")) if kwargs.get("query") else ""
-        response: dict[str, Any] = ctm_request(auth=self._parent_class.auth, # type: ignore
+        response: dict[str, Any] = ctm_request(auth=self._parent_class.auth,  # type: ignore
                                                method=self.method,
                                                url=url,
                                                params=params,
                                                data=data,
                                                timeout=self._parent_class.auth.timeout,
                                                verify=self._parent_class.auth.verify)
         return response
 
 
 class Delete:
-    """DELETE API Calls"""
+    """Request method DELETE.
+
+    :return: _description_
+    :rtype: _type_
+    """
+
     _parent_class = None
     method: str = "DELETE"
 
     def call(self, url_path: str, **kwargs: Any) -> dict[str, Any]:
         """DELETE call for CipherTrust Manager
 
         :param url_path: _description_
         :type url_path: str
         :return: _description_
         :rtype: dict[str, Any]
         """
+
         url: str = config.API_URL.format(self._parent_class.auth.hostname, url_path)
         response: dict[str, Any] = ctm_request(auth=self._parent_class.auth,
                                                url=url,
                                                method=self.method,
                                                timeout=self._parent_class.auth.timeout,
                                                verify=self._parent_class.auth.verify)
         # print(f"{response=}")
         return response
 
 
 class Patch:
+    """Request method PATCH.
+
+    :return: _description_
+    :rtype: _type_
+    """
+
     _parent_class = None
     method: str = "PATCH"
 
     def call(self, url_path: str, **kwargs: Any) -> Dict[str, Any]:
         """CipherTrust API Patch calls
 
         :param url_path: _description_
         :type url_path: _type_
         :return: _description_
         :rtype: Dict[str,Any]
         """
+
         url: str = config.API_URL.format(self._parent_class.auth.hostname, url_path)
         params: dict = kwargs.pop("params", {})
         data: str = self._parent_class.convert_to_string(
             query=kwargs.pop("query")) if kwargs.get("query") else ""
         response: dict[str, Any] = ctm_request(auth=self._parent_class.auth,
                                                url=url,
                                                method=self.method,
                                                params=params,
                                                data=data,
                                                timeout=self._parent_class.auth.timeout,
                                                verify=self._parent_class.auth.verify)
-        # print(f"{response=}")
         return response
```

### Comparing `ciphertrust-sdk-1.0.5/src/ciphertrust/auth.py` & `ciphertrust-sdk-1.0.6/src/ciphertrust/auth.py`

 * *Files 1% similar despite different names*

```diff
@@ -187,9 +187,9 @@
         try:
             if time.time() >= auth.expiration:
                 auth.gen_refresh_token()
                 # print("Generatinga new token|auth.expiration=",
                 #       f"{auth.expiration}|issued={auth.issued_at}")
         except KeyError:
             raise CipherAuthError(f"Invalid Authorization {auth}")
-        return decorated(auth, **kwargs)
+        return decorated(auth, **kwargs)  # type: ignore
     return wrapper
```

### Comparing `ciphertrust-sdk-1.0.5/src/ciphertrust/models.py` & `ciphertrust-sdk-1.0.6/src/ciphertrust/models.py`

 * *Files identical despite different names*

### Comparing `ciphertrust-sdk-1.0.5/src/ciphertrust/requestapi.py` & `ciphertrust-sdk-1.0.6/src/ciphertrust/requestapi.py`

 * *Files 4% similar despite different names*

```diff
@@ -13,68 +13,74 @@
 import urllib.parse
 
 import orjson
 import httpx
 import requests
 from requests import HTTPError, Response
 
-from ciphertrust.auth import (Auth, refresh_token)
+from ciphertrust.auth import (Auth, refresh_token)  # type: ignore
 from ciphertrust.exceptions import (CipherAPIError, CipherMissingParam)
 from ciphertrust.static import (DEFAULT_HEADERS, ENCODE,
                                 DEFAULT_LIMITS_OVERRIDE, DEFAULT_TIMEOUT_CONFIG_OVERRIDE)
-from ciphertrust.utils import (reformat_exception, concat_resources, verify_path_exists)
+from ciphertrust.utils import (reformat_exception, concat_resources,  # type: ignore
+                               verify_path_exists)
 
 
 def format_request(response: Response) -> dict[str, Any]:
-    """_summary_
+    """Reformat request.
 
     :param response: _description_
     :type response: Response
     :return: _description_
     :rtype: dict[str,Any]
     """
     api_raise_error(response=response)
     json_response = {
         "exec_time": response.elapsed.total_seconds(),
-        "headers": json.loads(orjson.dumps(response.headers.__dict__["_store"]).decode('utf-8')), # pylint: disable=no-member
+        "headers": json.loads(orjson.dumps(response.headers.__dict__["_store"]).decode('utf-8')),  # pylint: disable=no-member
         "exec_time_end": datetime.datetime.utcnow().isoformat()
     }
     return json_response
 
 
 def standard_request(**kwargs: Any) -> dict[str, Any]:
-    """_summary_
+    """Call standard Request.
 
-    :return: _description_
+    :return: Adjusted Request Response
     :rtype: dict[str,Any]
     """
-    resp: Response = requests.request(**kwargs)
-    response = {**resp.json(), **format_request(resp)}
+    # Pop out saved_dir value to ensure doesn't get passed
+    kwargs.pop("saved_dir", "")
+    resp: Response = requests.request(**kwargs)  # pylint: disable=missing-timeout
+    response: dict[str, Any] = {**resp.json(), **format_request(resp)}
     return response
 
 
 def download_request(**kwargs: Any) -> dict[str, Any]:
-    """_summary_
+    """Use to Download Tar files. Only supports tar.gz can update.
 
-    :return: _description_
-    :rtype: Response
+    :return: Adjusted Request Ressponse
+    :rtype: dict[str,Any]
     """
-    chunk_size = kwargs.pop("chunk_size", 128)
-    save_path = kwargs.pop("save_dir", os.path.expanduser('~'))
+    chunk_size: int = kwargs.pop("chunk_size", 128)
+    save_path: str = kwargs.pop("save_dir", os.path.expanduser('~'))
     if not verify_path_exists(path_dir=save_path):
         raise FileExistsError(f"{save_path} does not exist")
     req: Response = requests.request(stream=True, **kwargs)  # pylint: disable=missing-timeout
-    parsed_url: urllib.parse.ParseResult = urllib.parse.urlparse(kwargs["url"])
-    save_filename = Path.joinpath(
+    parsed_url: urllib.parse.ParseResult = urllib.parse.urlparse(kwargs["url"])  # type: ignore
+    save_filename: Path = Path.joinpath(
         Path(save_path) /
-        f"{datetime.datetime.now().strftime('%Y%m%dT%H%M%S')}_ciphertrust_log_{parsed_url.hostname}.tar.gz")
+        f"{datetime.datetime.now().strftime('%Y%m%dT%H%M%S')}_ciphertrust_log_{parsed_url.hostname}.tar.gz")  # pylint: disable=line-too-long,unknown-option-value
     with open(save_filename, 'wb') as fild:
         for chunk in req.iter_content(chunk_size=chunk_size):
             fild.write(chunk)
-    response = {"message": "downloaded request completed", "location": str(save_filename)}
+    response: dict[str, str] = {
+        "message": "downloaded request completed",
+        "location": str(save_filename)
+    }
     response = {**response, **format_request(req)}
     return response
 
 
 @refresh_token
 def ctm_request(auth: Auth, **kwargs: Any) -> Dict[str, Any]:  # pylint: disable=too-many-locals
     """_summary_
@@ -112,23 +118,25 @@
         data: str = orjson.dumps(data).decode(ENCODE)  # pylint: disable=no-member
     # Add auth to header
     headers["Authorization"] = f"Bearer {auth.token}"
     request_type = {
         "download": download_request,
         "standard": standard_request
     }
-    start_time = datetime.datetime.utcnow().isoformat()
-    response: dict[str, Any] = request_type["standard" if not stream else "download"](method=method,
-                                                                                      url=url,
-                                                                                      headers=headers,
-                                                                                      data=data,
-                                                                                      params=params,
-                                                                                      verify=verify,
-                                                                                      timeout=timeout,
-                                                                                      **kwargs)
+    start_time: str = datetime.datetime.utcnow().isoformat()
+    response: dict[str, Any] = request_type["standard" if not stream else "download"](
+        method=method,
+        url=url,
+        headers=headers,
+        data=data,
+        params=params,
+        verify=verify,
+        timeout=timeout,
+        **kwargs)
+    # Adds start time to response
     response["exec_time_start"] = start_time
     return response
 
 
 @refresh_token
 async def ctm_request_async(auth: Auth, **kwargs: Any) -> Dict[str, Any]:  # pylint: disable=too-many-locals
     """_summary_
@@ -207,27 +215,30 @@
     full_listed_resp = []
     while iterations > 0:
         send_iterations = 10 if iterations <= 10 else iterations
         tmp_listed_resp = await split_up_req(auth=auth,
                                              iterations=send_iterations,  # type: ignore
                                              limit=limit,  # type: ignore
                                              **kwargs)
-        full_listed_resp = full_listed_resp + tmp_listed_resp
+        full_listed_resp: Any = full_listed_resp + tmp_listed_resp
         iterations -= 10
         print(f"One loop iteration completed new_iterations={iterations}")
     response = {**response, **build_responsde(full_listed_resp=full_listed_resp)}  # type: ignore
     response["exec_time"] = response["exec_time_end"] - start_time
     response["exec_time_end"] = datetime.datetime.utcfromtimestamp(
         response["exec_time_end"]).isoformat()
     response["exec_time_start"] = datetime.datetime.utcfromtimestamp(start_time).isoformat()
     return response
 
 
 @refresh_token
-async def split_up_req(auth: Auth, iterations: int, limit: int, **kwargs: Any) -> List[Dict[str, Any]]:
+async def split_up_req(auth: Auth,
+                       iterations: int,
+                       limit: int,
+                       **kwargs: Any) -> List[Dict[str, Any]]:
     """Splitting up requests due to too many being sent and cannot handle.
       Trying to adjust with timeout, but still causes errors on return.
 
     :param auth: _description_
     :type auth: Auth
     :param iterations: _description_
     :type iterations: int
@@ -251,33 +262,47 @@
             tasks.append(asyncio.ensure_future(ctm_request_async(auth=auth, **kwargs)))
         full_listed_resp: List[Dict[str, Any]] = await asyncio.gather(*tasks)  # type: ignore
     return full_listed_resp  # type: ignore
     # print(f"{full_listed_resp=}")
 
 
 def build_responsde(full_listed_resp: list[dict[str, Any]]) -> dict[str, Any]:
+    """Build Returned Reponse with statistics.
+
+    :param full_listed_resp: _description_
+    :type full_listed_resp: list[dict[str, Any]]
+    :return: _description_
+    :rtype: dict[str, Any]
+    """
     response: Dict[str, Any] = {
         "exec_time_end": 0.0,
         "exec_time_min": 0.0,
         "exec_time_max": 0.0,
         "exec_time_stdev": 0.0,
         "resources": []
     }
     end_time: float = time.time()
     elapsed_times: list[float] = [value["exec_time"] for value in full_listed_resp]
     response["elapsed_times"] = elapsed_times
     response["exec_time_end"] = end_time
     response["exec_time_min"] = min(elapsed_times)
     response["exec_time_max"] = max(elapsed_times)
     response["exec_time_stdev"] = statistics.stdev(elapsed_times)
-    response["resources"] = reduce(concat_resources, full_listed_resp)["resources"]
+    response["resources"] = reduce(concat_resources, full_listed_resp)["resources"]  # type: ignore
     return response
 
 
 def asyn_get_all(auth: Auth, **kwargs: Any) -> dict[str, Any]:
+    """Asyncio get All. Still under eval
+
+    :param auth: _description_
+    :type auth: Auth
+    :return: _description_
+    :rtype: dict[str, Any]
+    """
     return asyncio.run(ctm_request_list_all(auth=auth, **kwargs))
 
 
 def api_raise_error(response: Response) -> None:
     """Raises error if response not what was expected
 
     Args:
```

### Comparing `ciphertrust-sdk-1.0.5/src/ciphertrust/utils.py` & `ciphertrust-sdk-1.0.6/src/ciphertrust/utils.py`

 * *Files identical despite different names*


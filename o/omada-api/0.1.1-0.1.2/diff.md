# Comparing `tmp/omada_api-0.1.1.tar.gz` & `tmp/omada_api-0.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "omada_api-0.1.1.tar", max compression
+gzip compressed data, was "omada_api-0.1.2.tar", max compression
```

## Comparing `omada_api-0.1.1.tar` & `omada_api-0.1.2.tar`

### file list

```diff
@@ -1,7 +1,8 @@
--rw-r--r--   0        0        0     1072 2023-06-26 14:01:05.665513 omada_api-0.1.1/LICENSE
--rw-r--r--   0        0        0     3686 2023-06-26 14:01:05.665513 omada_api-0.1.1/README.md
--rw-r--r--   0        0        0       77 2023-06-26 14:01:05.665513 omada_api-0.1.1/omada/__init__.py
--rw-r--r--   0        0        0      524 2023-06-26 14:01:05.665513 omada_api-0.1.1/omada/api_bindings.py
--rw-r--r--   0        0        0    12299 2023-06-26 14:01:05.665513 omada_api-0.1.1/omada/omada.py
--rw-r--r--   0        0        0     2062 2023-06-26 14:01:13.693569 omada_api-0.1.1/pyproject.toml
--rw-r--r--   0        0        0     4698 1970-01-01 00:00:00.000000 omada_api-0.1.1/PKG-INFO
+-rw-r--r--   0        0        0     1072 2023-06-28 09:12:09.565932 omada_api-0.1.2/LICENSE
+-rw-r--r--   0        0        0     3686 2023-06-28 09:12:09.565932 omada_api-0.1.2/README.md
+-rw-r--r--   0        0        0      106 2023-06-28 09:12:09.565932 omada_api-0.1.2/omada/__init__.py
+-rw-r--r--   0        0        0      524 2023-06-28 09:12:09.565932 omada_api-0.1.2/omada/api_bindings.py
+-rw-r--r--   0        0        0      475 2023-06-28 09:12:09.565932 omada_api-0.1.2/omada/function_interface_bindings.py
+-rw-r--r--   0        0        0    12658 2023-06-28 09:12:09.565932 omada_api-0.1.2/omada/omada.py
+-rw-r--r--   0        0        0     2062 2023-06-28 09:12:19.418105 omada_api-0.1.2/pyproject.toml
+-rw-r--r--   0        0        0     4698 1970-01-01 00:00:00.000000 omada_api-0.1.2/PKG-INFO
```

### Comparing `omada_api-0.1.1/LICENSE` & `omada_api-0.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `omada_api-0.1.1/README.md` & `omada_api-0.1.2/README.md`

 * *Files identical despite different names*

### Comparing `omada_api-0.1.1/omada/api_bindings.py` & `omada_api-0.1.2/omada/api_bindings.py`

 * *Files identical despite different names*

### Comparing `omada_api-0.1.1/omada/omada.py` & `omada_api-0.1.2/omada/omada.py`

 * *Files 3% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 import typing
 from datetime import datetime
 
 import requests
 import yarl
 from requests.cookies import RequestsCookieJar
 
-from . import api_bindings
+from . import api_bindings, function_interface_bindings
 
 logger = logging.getLogger(__name__)
 
 
 def timestamp() -> int:
     """Omada API calls expects timestamp in milliseconds."""
     return int(datetime.utcnow().timestamp() * 1000)
@@ -62,24 +62,14 @@
     """Alert and event levels"""
 
     Error = 0
     Warning = 1
     Information = 2
 
 
-@enum.unique
-class ModuleFilter(enum.Enum):
-    """Alert and event modules"""
-
-    Operation = 0
-    System = 1
-    Device = 2
-    Client = 3
-
-
 @dataclasses.dataclass(frozen=True)
 class OmadaConfig:
     base_url: yarl.URL
     site: str
     omada_controller_id: typing.Optional[str] = None
     ssl_verify: bool = True
 
@@ -307,19 +297,32 @@
         self, site: typing.Optional[str] = None, archived: bool = False
     ) -> typing.Iterable[dict]:
         """Returns the list of alerts for given site."""
         params = {"filters.archived": "true" if archived else "false"}
 
         return self._geterator(f"sites/{self._find_site(site)}/alerts", params=params)
 
-    def get_site_events(
-        self, site: typing.Optional[str] = None
-    ) -> typing.Iterable[dict]:
+    def get_site_events(self, **kwargs) -> typing.Iterable[dict]:
         """Returns the list of events for given site."""
-        return self._geterator(f"sites/{self._find_site(site)}/events")
+        settings = function_interface_bindings.SiteEventsInterface(**kwargs)
+        all_params = {
+            "filters.timeStart": settings.time_start,
+            "filters.timeEnd": settings.time_end,
+            "filters.module": settings.module,
+        }
+        # Remove empty filters
+        params = {}
+        for key, value in all_params.items():
+            if value is None:
+                continue
+            else:
+                params[key] = value
+        return self._geterator(
+            f"sites/{self._find_site(settings.site)}/events", params=params
+        )
 
     def get_site_notifications(
         self, site: typing.Optional[str] = None
     ) -> typing.Iterable[dict]:
         """Returns the notification settings for given site."""
         return self._get(f"sites/{self._find_site(site)}/notification")
```

### Comparing `omada_api-0.1.1/pyproject.toml` & `omada_api-0.1.2/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "omada-api"
-version = "v0.1.1"
+version = "v0.1.2"
 description = "A simple Python wrapper for the TP-Link Omada Software Controller API"
 authors = ["Ilja O <vrghost@gmail.com>", "Gregory Haberek <ghaberek@gmail.com>"]
 license = "MIT"
 readme = "README.md"
 packages = [{include = "omada"}]
 classifiers = [
     "Development Status :: 4 - Beta",
```

### Comparing `omada_api-0.1.1/PKG-INFO` & `omada_api-0.1.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: omada-api
-Version: 0.1.1
+Version: 0.1.2
 Summary: A simple Python wrapper for the TP-Link Omada Software Controller API
 License: MIT
 Keywords: tplink,omada,wrapper
 Author: Ilja O
 Author-email: vrghost@gmail.com
 Requires-Python: >=3.8,<4.0
 Classifier: Development Status :: 4 - Beta
```


# Comparing `tmp/pyramid_jsonapi-2.2.8.tar.gz` & `tmp/pyramid_jsonapi-2.2.9.dev1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyramid_jsonapi-2.2.8.tar", last modified: Tue Jun 20 15:51:10 2023, max compression
+gzip compressed data, was "pyramid_jsonapi-2.2.9.dev1.tar", last modified: Wed Jun 28 14:41:01 2023, max compression
```

## Comparing `pyramid_jsonapi-2.2.8.tar` & `pyramid_jsonapi-2.2.9.dev1.tar`

### file list

```diff
@@ -1,47 +1,53 @@
-drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-20 15:51:10.653698 pyramid_jsonapi-2.2.8/
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    34521 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/LICENSE
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     1126 2023-06-20 15:51:10.653698 pyramid_jsonapi-2.2.8/PKG-INFO
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     3974 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/README.rst
-drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-20 15:51:10.653698 pyramid_jsonapi-2.2.8/pyramid_jsonapi/
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    24120 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/__init__.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     3898 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/callbacks_doc.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    50205 2023-06-20 15:31:41.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/collection_view.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    20994 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/endpoints.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     3679 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/filters.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     5200 2023-05-24 09:25:18.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/http_query.py
-drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-20 15:51:10.653698 pyramid_jsonapi-2.2.8/pyramid_jsonapi/metadata/
-drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-20 15:51:10.653698 pyramid_jsonapi-2.2.8/pyramid_jsonapi/metadata/JSONSchema/
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    11280 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/metadata/JSONSchema/__init__.py
-drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-20 15:51:10.653698 pyramid_jsonapi-2.2.8/pyramid_jsonapi/metadata/OpenAPI/
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    10756 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/metadata/OpenAPI/__init__.py
-drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-20 15:51:10.653698 pyramid_jsonapi-2.2.8/pyramid_jsonapi/metadata/OpenAPI/swagger-ui/
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     3771 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/metadata/OpenAPI/swagger-ui/index.mako
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     2633 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/metadata/__init__.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     6307 2022-03-25 12:58:00.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/permissions.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)      401 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/resource.py
-drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-20 15:51:10.653698 pyramid_jsonapi-2.2.8/pyramid_jsonapi/schema/
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    11044 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/schema/jsonapi-schema.json
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     4295 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/unit_tests.py
--rwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)     1634 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/version.py
-drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-20 15:51:10.653698 pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    43645 2023-05-23 16:50:14.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/__init__.py
-drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-20 15:51:10.653698 pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     5161 2023-06-20 15:29:35.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/__init__.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     3447 2023-05-24 09:25:18.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/collection_get.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     4646 2023-06-19 21:41:07.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/collection_post.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)      735 2023-06-19 21:41:20.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/item_delete.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)      818 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/item_get.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     5918 2023-02-28 11:42:33.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/item_patch.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     2748 2023-02-28 11:42:33.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/related_get.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     1703 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/relationships_delete.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)      218 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/relationships_get.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     3163 2022-03-25 12:58:00.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/relationships_patch.py
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     2364 2022-04-06 11:18:05.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/relationships_post.py
-drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-20 15:51:10.653698 pyramid_jsonapi-2.2.8/pyramid_jsonapi.egg-info/
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     1126 2023-06-20 15:51:10.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi.egg-info/PKG-INFO
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     1319 2023-06-20 15:51:10.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi.egg-info/SOURCES.txt
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)        1 2023-06-20 15:51:10.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi.egg-info/dependency_links.txt
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)      117 2023-06-20 15:51:10.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi.egg-info/requires.txt
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)       16 2023-06-20 15:51:10.000000 pyramid_jsonapi-2.2.8/pyramid_jsonapi.egg-info/top_level.txt
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)       79 2023-06-20 15:51:10.653698 pyramid_jsonapi-2.2.8/setup.cfg
--rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     1813 2023-02-27 16:12:47.000000 pyramid_jsonapi-2.2.8/setup.py
+drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-28 14:41:01.678712 pyramid_jsonapi-2.2.9.dev1/
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    34521 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/LICENSE
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     1131 2023-06-28 14:41:01.678712 pyramid_jsonapi-2.2.9.dev1/PKG-INFO
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     3974 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/README.rst
+drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-28 14:41:01.678712 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    24791 2023-06-28 14:32:06.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/__init__.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     1471 2023-06-28 14:28:19.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/authoriser.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     3898 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/callbacks_doc.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    50085 2023-06-28 14:28:19.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/collection_view.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     3911 2023-06-28 14:28:19.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/db_query.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    20994 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/endpoints.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     3679 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/filters.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     7282 2023-06-28 14:32:26.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/http_query.py
+drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-28 14:41:01.678712 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/metadata/
+drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-28 14:41:01.678712 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/metadata/JSONSchema/
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    11280 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/metadata/JSONSchema/__init__.py
+drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-28 14:41:01.678712 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/metadata/OpenAPI/
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    10756 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/metadata/OpenAPI/__init__.py
+drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-28 14:41:01.678712 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/metadata/OpenAPI/swagger-ui/
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     3771 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/metadata/OpenAPI/swagger-ui/index.mako
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     2633 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/metadata/__init__.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     6307 2022-03-25 12:58:00.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/permissions.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)      401 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/resource.py
+drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-28 14:41:01.678712 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/schema/
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    11044 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/schema/jsonapi-schema.json
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     9550 2023-06-28 14:33:17.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/serialiser.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     4295 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/unit_tests.py
+-rwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)     1634 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/version.py
+drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-28 14:41:01.678712 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)    43757 2023-06-28 14:28:19.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/__init__.py
+drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-28 14:41:01.678712 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     5161 2023-06-20 15:29:35.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/__init__.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     3447 2023-06-21 21:04:27.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/collection_get.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     4646 2023-06-19 21:41:07.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/collection_post.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)      735 2023-06-19 21:41:20.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/item_delete.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)      818 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/item_get.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     5918 2023-02-28 11:42:33.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/item_patch.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     2748 2023-02-28 11:42:33.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/related_get.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     1703 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/relationships_delete.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)      218 2022-03-24 13:46:48.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/relationships_get.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     3163 2022-03-25 12:58:00.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/relationships_patch.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     2364 2022-04-06 11:18:05.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/relationships_post.py
+drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-28 14:41:01.678712 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/selectin/
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)       33 2023-06-28 14:28:19.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/selectin/__init__.py
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     4023 2023-06-28 14:28:19.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/selectin/collection_get.py
+drwxrwxr-x   0 chiggs1   (1001) chiggs1   (1001)        0 2023-06-28 14:41:01.678712 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi.egg-info/
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     1131 2023-06-28 14:41:01.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi.egg-info/PKG-INFO
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     1505 2023-06-28 14:41:01.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi.egg-info/SOURCES.txt
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)        1 2023-06-28 14:41:01.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi.egg-info/dependency_links.txt
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)      128 2023-06-28 14:41:01.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi.egg-info/requires.txt
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)       16 2023-06-28 14:41:01.000000 pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi.egg-info/top_level.txt
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)       79 2023-06-28 14:41:01.682712 pyramid_jsonapi-2.2.9.dev1/setup.cfg
+-rw-rw-r--   0 chiggs1   (1001) chiggs1   (1001)     1831 2023-06-28 14:28:19.000000 pyramid_jsonapi-2.2.9.dev1/setup.py
```

### Comparing `pyramid_jsonapi-2.2.8/LICENSE` & `pyramid_jsonapi-2.2.9.dev1/LICENSE`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/PKG-INFO` & `pyramid_jsonapi-2.2.9.dev1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyramid_jsonapi
-Version: 2.2.8
+Version: 2.2.9.dev1
 Summary: Auto-build JSON API from sqlalchemy models using the pyramid framework
 Home-page: https://github.com/colinhiggs/pyramid-jsonapi
 Author: Colin Higgs
 Author-email: colin.higgs70@gmail.com
 License: GNU Affero General Public License v3 or later (AGPLv3+)
 Keywords: json,api,json-api,jsonapi,jsonschema,openapi,pyramid,sqlalchemy
 Platform: UNKNOWN
```

### Comparing `pyramid_jsonapi-2.2.8/README.rst` & `pyramid_jsonapi-2.2.9.dev1/README.rst`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/__init__.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -132,14 +132,15 @@
             prefix=['pyramid_jsonapi']
         )
         self.models = models
         self.get_dbsession = get_dbsession
         self.endpoint_data = pyramid_jsonapi.endpoints.EndpointData(self)
         self.filter_registry = pyramid_jsonapi.filters.FilterRegistry()
         self.metadata = {}
+        self.permission_handlers_enabled = False
 
     @staticmethod
     def error(exc, request):
         """Error method to return jsonapi compliant errors."""
         request.response.content_type = 'application/vnd.api+json'
         request.response.status_code = exc.code
         errors = {
@@ -371,14 +372,16 @@
             class_attrs
         )
         # Relationships have to be added after view_class has been constructed
         # because they need a reference to it.
         for key, rel in rels.items():
             view_rels[key] = StdRelationship(key, rel, view_class)
         view_class.permission_template = Permission.template_from_view(view_class)
+        view_class.permission_all = Permission(view_class.permission_template)
+        view_class.permission_none = Permission(view_class.permission_template, False, False, False)
 
         return view_class
 
     def enable_permission_handlers(self, stage_names):
         '''
         Add permission handlers to all views.
 
@@ -387,23 +390,27 @@
         for the stage names specified.
 
         Arguments:
             stage_names: an iterable of stage names to enable.
 
         '''
         # Build a set of all the end points from permissions.
+        if self.permission_handlers_enabled:
+            return
+        self.permission_handlers_enabled = True
         ep_names = self.endpoint_data.http_to_view_methods['all']
 
         # Add permission handlers for all view classes.
         for model, view_class in self.view_classes.items():
             for ep_name in ep_names:
                 ep_func = getattr(view_class, ep_name)
-                ep_func.stages['alter_document'].append(
-                    wf.sh_alter_document_add_denied
-                )
+                if '.loop.' in getattr(self.settings, f'workflow_{ep_name}', ''):
+                    ep_func.stages['alter_document'].append(
+                        wf.sh_alter_document_add_denied
+                    )
                 for stage_name in stage_names:
                     view_class.add_stage_handler(
                         [ep_name], [stage_name],
                         view_class.permission_handler(ep_name, stage_name)
                     )
 
 
@@ -417,42 +424,41 @@
     def __init__(self, name, obj, view_class):
         self.name = name
         self.obj = obj
         self.view_class = view_class
         self.src_class = self.view_class.model
         if isinstance(obj, RelationshipProperty):
             self.direction = self.rel_direction
+            self.to_many = getattr(self.src_class, self.name).property.uselist
             self.tgt_class = self.rel_tgt_class
             self.instrumented = getattr(self.src_class, self.name)
             self.queryable = True
         elif isinstance(obj, hybrid_property):
             pj_info = obj.info['pyramid_jsonapi']['relationship']
             self.direction = pj_info.get('direction', ONETOMANY)
+            self.to_many = self.direction in (ONETOMANY, MANYTOMANY)
             self.queryable = pj_info.get('queryable', False)
             tgt_class = pj_info.get('tgt_class')
             if isinstance(tgt_class, str):
                 for mapper in view_class.model.registry.mappers:
                     if mapper.class_.__name__ == tgt_class:
                         tgt_class = mapper.class_
                         break
             self.tgt_class = tgt_class
         elif obj.extension_type is ASSOCIATION_PROXY:
             self.direction = self.proxy_direction
+            self.to_many = self.direction is MANYTOMANY
             self.tgt_class = self.proxy_tgt_class
             self.queryable = True
 
     @property
     def rel_direction(self):
         return self.obj.direction
 
     @property
-    def to_many(self):
-        return self.direction in (ONETOMANY, MANYTOMANY)
-
-    @property
     def to_one(self):
         return not self.to_many
 
     @property
     def proxy_direction(self):
         ps = self.obj.for_class(self.src_class)
         if ps.scalar:
@@ -520,14 +526,17 @@
         if isinstance(self.obj, RelationshipProperty):
             return self.rel_mirror_relationship
         elif self.obj.extension_type is ASSOCIATION_PROXY:
             return self.proxy_mirror_relationship
         else:
             return None
 
+    def __repr__(self):
+        return f'StdRelationship({self.src_class.__name__}.{self.name} -> {self.tgt_class.__name__})'
+
 
 class DebugView:
     """Pyramid view class defining a debug API.
 
     These are available as ``/debug/{action}`` if
     ``pyramid_jsonapi.debug_endpoints == 'true'``.
```

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/callbacks_doc.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/callbacks_doc.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/collection_view.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/collection_view.py`

 * *Files 2% similar despite different names*

```diff
@@ -38,39 +38,22 @@
 MANYTOMANY = sqlalchemy.orm.interfaces.MANYTOMANY
 MANYTOONE = sqlalchemy.orm.interfaces.MANYTOONE
 
 from pyramid_jsonapi.permissions import (
     Permission,
     Targets,
 )
+from .db_query import RQLQuery
 from .http_query import QueryInfo
 import pyramid_jsonapi.workflow as wf
 
 
 Entity = namedtuple('Entity', 'type')
 
 
-class RQLQuery(BaseQuery, RQLQueryMixIn):
-
-    def _rql_ilike(self, args):
-        attr, value = args
-
-        attr = self._rql_attr(attr)
-        value = self._rql_value(value, attr)
-        value = value.replace("*", "%")
-
-        return attr.ilike(value)
-
-    def _rql_icontains(self, args):
-        attr, value = args
-        attr = self._rql_attr(attr)
-        value = self._rql_value(value, attr)
-        return attr.ilike(f'%{value}%')
-
-
 class CollectionViewBase:
     """Base class for all view classes.
 
     Arguments:
         request (pyramid.request): passed by framework.
     """
 
@@ -100,14 +83,16 @@
     rel_view = None
     relationships = None
     relname = None
     view_classes = None
     settings = None
     permission_filters = None
     permission_template = None
+    permission_all = None
+    permission_none = None
     methods = None
 
     def __init__(self, request):
         self.request = request
         self.query_info = QueryInfo(self, request)
         if self.api.get_dbsession:
             self.dbsession = self.api.get_dbsession(self)
@@ -130,14 +115,19 @@
             # StatementError is caused by e.g. id (uuid) = 1
             if not_found_message:
                 raise HTTPNotFound(not_found_message)
             else:
                 return None
         return item
 
+    def item_id(self, item):
+        """Return the value of the id column for the item."""
+        item_view = self.view_instance(item.__class__)
+        return getattr(item, item_view.key_column.name)
+
     def get_item(self, _id=None):
         """Return the item specified by _id. Will look up id from request if _id is None.
         """
         if _id is None:
             _id = self.obj_id
         return self.get_one(
             self.dbsession.query(
@@ -695,15 +685,15 @@
         if not loadonly:
             loadonly = self.allowed_requested_query_columns.keys()
         query = self.dbsession.query(
             self.model
         ).options(
             load_only(*loadonly)
         )
-        query._entities = [Entity(type=self.model)]
+        # query._entities = [Entity(type=self.model)]
         query.__class__ = RQLQuery
         return query
 
     def single_item_query(self, obj_id=None, loadonly=None):
         """A query representing the single item referenced by id.
 
         Keyword Args:
@@ -1484,14 +1474,15 @@
                 else:
                     raise TypeError(
                         f"Permission filter should return a bool or Permission, not {type(result)}."
                     )
             return Permission.from_pfilter(
                 cls.permission_template, result
             )
+        wrapped_pfunc.pfunc = pfunc
         return wrapped_pfunc
 
     @classmethod
     def register_permission_filter(
         cls, permissions, stages, pfunc, target_types=list(Targets), warn=True,
     ):
         # Permission filters should have the signature:
```

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/endpoints.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/endpoints.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/filters.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/filters.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/metadata/JSONSchema/__init__.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/metadata/JSONSchema/__init__.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/metadata/OpenAPI/__init__.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/metadata/OpenAPI/__init__.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/metadata/OpenAPI/swagger-ui/index.mako` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/metadata/OpenAPI/swagger-ui/index.mako`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/metadata/__init__.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/metadata/__init__.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/permissions.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/permissions.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/schema/jsonapi-schema.json` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/schema/jsonapi-schema.json`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/unit_tests.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/unit_tests.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/version.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/version.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/__init__.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -379,14 +379,17 @@
         # One to many.
         for ri in allowed_forward_ris:
             # Need patch on new_rel_obj.mirror_rel
             if perm == 'delete':
                 mirror_data = None
             elif perm == 'post':
                 mirror_data = src_obj_data
+            pf = rel_view.permission_filter(
+                'patch', Targets.relationship, stage
+            )
             if rel_view.permission_filter(
                 'patch', Targets.relationship, stage
             )(
                 {
                     'type': ri['type'],
                     'id': ri['id'],
                     'relationships': {
```

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/__init__.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/__init__.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/collection_get.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/collection_get.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/collection_post.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/collection_post.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/item_delete.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/item_delete.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/item_get.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/item_get.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/item_patch.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/item_patch.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/related_get.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/related_get.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/relationships_delete.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/relationships_delete.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/relationships_patch.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/relationships_patch.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi/workflow/loop/relationships_post.py` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi/workflow/loop/relationships_post.py`

 * *Files identical despite different names*

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi.egg-info/PKG-INFO` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyramid-jsonapi
-Version: 2.2.8
+Version: 2.2.9.dev1
 Summary: Auto-build JSON API from sqlalchemy models using the pyramid framework
 Home-page: https://github.com/colinhiggs/pyramid-jsonapi
 Author: Colin Higgs
 Author-email: colin.higgs70@gmail.com
 License: GNU Affero General Public License v3 or later (AGPLv3+)
 Keywords: json,api,json-api,jsonapi,jsonschema,openapi,pyramid,sqlalchemy
 Platform: UNKNOWN
```

### Comparing `pyramid_jsonapi-2.2.8/pyramid_jsonapi.egg-info/SOURCES.txt` & `pyramid_jsonapi-2.2.9.dev1/pyramid_jsonapi.egg-info/SOURCES.txt`

 * *Files 4% similar despite different names*

```diff
@@ -1,19 +1,22 @@
 LICENSE
 README.rst
 setup.cfg
 setup.py
 pyramid_jsonapi/__init__.py
+pyramid_jsonapi/authoriser.py
 pyramid_jsonapi/callbacks_doc.py
 pyramid_jsonapi/collection_view.py
+pyramid_jsonapi/db_query.py
 pyramid_jsonapi/endpoints.py
 pyramid_jsonapi/filters.py
 pyramid_jsonapi/http_query.py
 pyramid_jsonapi/permissions.py
 pyramid_jsonapi/resource.py
+pyramid_jsonapi/serialiser.py
 pyramid_jsonapi/unit_tests.py
 pyramid_jsonapi/version.py
 pyramid_jsonapi.egg-info/PKG-INFO
 pyramid_jsonapi.egg-info/SOURCES.txt
 pyramid_jsonapi.egg-info/dependency_links.txt
 pyramid_jsonapi.egg-info/requires.txt
 pyramid_jsonapi.egg-info/top_level.txt
@@ -29,8 +32,10 @@
 pyramid_jsonapi/workflow/loop/item_delete.py
 pyramid_jsonapi/workflow/loop/item_get.py
 pyramid_jsonapi/workflow/loop/item_patch.py
 pyramid_jsonapi/workflow/loop/related_get.py
 pyramid_jsonapi/workflow/loop/relationships_delete.py
 pyramid_jsonapi/workflow/loop/relationships_get.py
 pyramid_jsonapi/workflow/loop/relationships_patch.py
-pyramid_jsonapi/workflow/loop/relationships_post.py
+pyramid_jsonapi/workflow/loop/relationships_post.py
+pyramid_jsonapi/workflow/selectin/__init__.py
+pyramid_jsonapi/workflow/selectin/collection_get.py
```

### Comparing `pyramid_jsonapi-2.2.8/setup.py` & `pyramid_jsonapi-2.2.9.dev1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -4,14 +4,15 @@
 # Importing as 'from pyramid_jsonapi import version' needs the deps we
 # haven't installed yet!
 sys.path.append("pyramid_jsonapi")
 from version import get_version
 
 requires = [
     'alchemyjsonschema',
+    'cachetools',
     'jsonschema',
     'pkginfo',
     'pyramid',
     'pyramid_mako',
     'pyramid_settings_wrapper',
     'pyyaml>=5.1', # openapi-spec-validator requires >= 5.1
     'rqlalchemy',
```


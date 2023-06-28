# Comparing `tmp/superannotate_databricks_connector-0.0.1.dev1.tar.gz` & `tmp/superannotate_databricks_connector-0.0.1.dev2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "superannotate_databricks_connector-0.0.1.dev1.tar", last modified: Fri Jun 23 13:40:45 2023, max compression
+gzip compressed data, was "superannotate_databricks_connector-0.0.1.dev2.tar", last modified: Wed Jun 28 05:56:02 2023, max compression
```

## Comparing `superannotate_databricks_connector-0.0.1.dev1.tar` & `superannotate_databricks_connector-0.0.1.dev2.tar`

### file list

```diff
@@ -1,24 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-23 13:40:45.882575 superannotate_databricks_connector-0.0.1.dev1/
--rw-r--r--   0 runner    (1001) docker     (122)     1078 2023-06-23 13:40:33.000000 superannotate_databricks_connector-0.0.1.dev1/LICENSE.txt
--rw-r--r--   0 runner    (1001) docker     (122)     2374 2023-06-23 13:40:45.882575 superannotate_databricks_connector-0.0.1.dev1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (122)     1354 2023-06-23 13:40:33.000000 superannotate_databricks_connector-0.0.1.dev1/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (122)       38 2023-06-23 13:40:45.882575 superannotate_databricks_connector-0.0.1.dev1/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-23 13:40:45.878575 superannotate_databricks_connector-0.0.1.dev1/src/
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-23 13:40:45.882575 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector/
--rw-r--r--   0 runner    (1001) docker     (122)      217 2023-06-23 13:40:33.000000 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-23 13:40:45.882575 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector/schemas/
--rw-r--r--   0 runner    (1001) docker     (122)        0 2023-06-23 13:40:33.000000 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector/schemas/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)      971 2023-06-23 13:40:33.000000 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector/schemas/comment.py
--rw-r--r--   0 runner    (1001) docker     (122)     1934 2023-06-23 13:40:33.000000 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector/schemas/text_schema.py
--rw-r--r--   0 runner    (1001) docker     (122)     3020 2023-06-23 13:40:33.000000 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector/schemas/vector_schema.py
--rw-r--r--   0 runner    (1001) docker     (122)     1901 2023-06-23 13:40:33.000000 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector/text.py
--rw-r--r--   0 runner    (1001) docker     (122)     6030 2023-06-23 13:40:33.000000 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector/vector.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-23 13:40:45.882575 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector.egg-info/
--rw-r--r--   0 runner    (1001) docker     (122)     2374 2023-06-23 13:40:45.000000 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (122)      765 2023-06-23 13:40:45.000000 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (122)        1 2023-06-23 13:40:45.000000 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (122)       30 2023-06-23 13:40:45.000000 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (122)       35 2023-06-23 13:40:45.000000 superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-23 13:40:45.882575 superannotate_databricks_connector-0.0.1.dev1/tests/
--rw-r--r--   0 runner    (1001) docker     (122)      765 2023-06-23 13:40:33.000000 superannotate_databricks_connector-0.0.1.dev1/tests/test_text.py
--rw-r--r--   0 runner    (1001) docker     (122)     3582 2023-06-23 13:40:33.000000 superannotate_databricks_connector-0.0.1.dev1/tests/test_vector.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 05:56:02.733801 superannotate_databricks_connector-0.0.1.dev2/
+-rw-r--r--   0 runner    (1001) docker     (122)     1078 2023-06-28 05:55:50.000000 superannotate_databricks_connector-0.0.1.dev2/LICENSE.txt
+-rw-r--r--   0 runner    (1001) docker     (122)     2374 2023-06-28 05:56:02.733801 superannotate_databricks_connector-0.0.1.dev2/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (122)     1355 2023-06-28 05:55:50.000000 superannotate_databricks_connector-0.0.1.dev2/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (122)       38 2023-06-28 05:56:02.733801 superannotate_databricks_connector-0.0.1.dev2/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 05:56:02.725800 superannotate_databricks_connector-0.0.1.dev2/src/
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 05:56:02.729800 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/
+-rw-r--r--   0 runner    (1001) docker     (122)      217 2023-06-28 05:55:50.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 05:56:02.729800 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/schemas/
+-rw-r--r--   0 runner    (1001) docker     (122)        0 2023-06-28 05:55:50.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/schemas/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)     2274 2023-06-28 05:55:50.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/schemas/comment.py
+-rw-r--r--   0 runner    (1001) docker     (122)     2803 2023-06-28 05:55:50.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/schemas/shapes.py
+-rw-r--r--   0 runner    (1001) docker     (122)      898 2023-06-28 05:55:50.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/schemas/tag.py
+-rw-r--r--   0 runner    (1001) docker     (122)     1875 2023-06-28 05:55:50.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/schemas/text_schema.py
+-rw-r--r--   0 runner    (1001) docker     (122)     2673 2023-06-28 05:55:50.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/schemas/vector_schema.py
+-rw-r--r--   0 runner    (1001) docker     (122)     2357 2023-06-28 05:55:50.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/schemas/video_schema.py
+-rw-r--r--   0 runner    (1001) docker     (122)     1845 2023-06-28 05:55:50.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/text.py
+-rw-r--r--   0 runner    (1001) docker     (122)     6218 2023-06-28 05:55:50.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/vector.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 05:56:02.729800 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (122)     2374 2023-06-28 05:56:02.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (122)      939 2023-06-28 05:56:02.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (122)        1 2023-06-28 05:56:02.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (122)       30 2023-06-28 05:56:02.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (122)       35 2023-06-28 05:56:02.000000 superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 05:56:02.729800 superannotate_databricks_connector-0.0.1.dev2/tests/
+-rw-r--r--   0 runner    (1001) docker     (122)      765 2023-06-28 05:55:50.000000 superannotate_databricks_connector-0.0.1.dev2/tests/test_text.py
+-rw-r--r--   0 runner    (1001) docker     (122)     3477 2023-06-28 05:55:50.000000 superannotate_databricks_connector-0.0.1.dev2/tests/test_vector.py
```

### Comparing `superannotate_databricks_connector-0.0.1.dev1/LICENSE.txt` & `superannotate_databricks_connector-0.0.1.dev2/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `superannotate_databricks_connector-0.0.1.dev1/PKG-INFO` & `superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: superannotate_databricks_connector
-Version: 0.0.1.dev1
+Name: superannotate-databricks-connector
+Version: 0.0.1.dev2
 Summary: Custom functions to work with SuperAnnotate in Databricks
 Author-email: Leo Lindén <leo@superannotate.com>
 Maintainer-email: Leo Lindén <leo@superannotate.com>
 License: MIT License
         
         Copyright (c) 2023 SuperAnnotate AI Inc.
```

### Comparing `superannotate_databricks_connector-0.0.1.dev1/pyproject.toml` & `superannotate_databricks_connector-0.0.1.dev2/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 [project]
 
 name = "superannotate_databricks_connector"  # Required
 
-version = "0.0.1dev1"
+version = "0.0.1dev2"
 
 description = "Custom functions to work with SuperAnnotate in Databricks"
 
 readme = "README.md"
 
 requires-python = ">=3.8"
 
@@ -43,8 +43,8 @@
 [project.urls]  # Optional
 "Homepage" = "https://github.com/superannotateai/superannotate-databricks-connector"
 "Bug Reports" = "https://github.com/superannotateai/superannotate-databricks-connector/issues"
 "Source" = "https://github.com/superannotateai/superannotate-databricks-connector/"
 
 [build-system]
 requires = ["setuptools>=43.0.0", "wheel"]
-build-backend = "setuptools.build_meta"
+build-backend = "setuptools.build_meta"
```

### Comparing `superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector/schemas/comment.py` & `superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/schemas/tag.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,34 +1,25 @@
 from pyspark.sql.types import (
     StructType,
     StructField,
     StringType,
-    FloatType,
-    BooleanType,
+    IntegerType,
     MapType,
-    ArrayType
+    ArrayType,
 )
 
 
-def get_comment_schema():
-    comment_schema = StructType([
-        StructField("correspondence",
-                    ArrayType(MapType(
-                        StringType(),
-                        StringType())),
+def get_tag_schema():
+    schema = StructType([
+        StructField("instance_type", StringType(), True),
+        StructField("classId", IntegerType(), True),
+        StructField("probability", IntegerType(), True),
+        StructField("attributes", ArrayType(MapType(StringType(),
+                                                    StringType())),
                     True),
-        StructField("x", FloatType(), True),
-        StructField("y", FloatType(), True),
-        StructField("resolved", BooleanType(), True),
         StructField("createdAt", StringType(), True),
-        StructField("createdBy", MapType(
-            StringType(),
-            StringType()),
-                    True),
+        StructField("createdBy", MapType(StringType(), StringType()), True),
         StructField("creationType", StringType(), True),
         StructField("updatedAt", StringType(), True),
-        StructField("updatedBy", MapType(
-            StringType(),
-            StringType()),
-                    True)
-    ])
-    return comment_schema
+        StructField("updatedBy", MapType(StringType(), StringType()), True),
+        StructField("className", StringType(), True)])
+    return schema
```

### Comparing `superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector/schemas/text_schema.py` & `superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/schemas/text_schema.py`

 * *Files 4% similar despite different names*

```diff
@@ -38,15 +38,14 @@
     ])
 
 
 def get_text_schema():
     schema = StructType([
         StructField("name", StringType(), True),
         StructField("url", StringType(), True),
-        StructField("contentLength", IntegerType(), True),
         StructField("projectId", IntegerType(), True),
         StructField("status", StringType(), True),
         StructField("annotatorEmail", StringType(), True),
         StructField("qaEmail", StringType(), True),
         StructField("entities", ArrayType(get_text_entity_schema()),
                     True),
         StructField("tags", ArrayType(get_text_tag_schema()),
```

### Comparing `superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector/schemas/vector_schema.py` & `superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/schemas/comment.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,78 +1,78 @@
 from pyspark.sql.types import (
     StructType,
     StructField,
     StringType,
-    IntegerType,
     FloatType,
     BooleanType,
     MapType,
-    ArrayType
+    ArrayType,
+    IntegerType
 )
-from .comment import get_comment_schema
 
+from .shapes import get_bbox_schema
 
-def get_point_schema():
-    point_schema = StructType([
+
+def get_vector_comment_schema():
+    return StructType([
+        StructField("correspondence",
+                    ArrayType(MapType(
+                        StringType(),
+                        StringType())),
+                    True),
         StructField("x", FloatType(), True),
-        StructField("y", FloatType(), True)
+        StructField("y", FloatType(), True),
+        StructField("resolved", BooleanType(), True),
+        StructField("createdAt", StringType(), True),
+        StructField("createdBy", MapType(
+            StringType(),
+            StringType()),
+            True),
+        StructField("creationType", StringType(), True),
+        StructField("updatedAt", StringType(), True),
+        StructField("updatedBy", MapType(
+            StringType(),
+            StringType()),
+            True)
     ])
-    return point_schema
 
 
-def get_cuboid_schema():
-    cuboid_points_schema = StructType([
-        StructField("f1", get_point_schema(), True),
-        StructField("f2", get_point_schema(), True),
-        StructField("r1", get_point_schema(), True),
-        StructField("r2", get_point_schema(), True)
+def get_video_timestamp_schema():
+    return StructType([
+        StructField("timestamp", IntegerType(), True),
+        StructField("points", get_bbox_schema(), True)
     ])
-    return cuboid_points_schema
 
 
-def get_vector_instance_schema():
-    instance_schema = StructType([
-        StructField("instance_type", StringType(), True),
-        StructField("classId", IntegerType(), True),
-        StructField("probability", IntegerType(), True),
-        StructField("bbox_points", MapType(StringType(), FloatType()), True),
-        StructField("polygon_points", ArrayType(FloatType()), True),
-        StructField("polygon_exclude", ArrayType(ArrayType(FloatType())),
-                    True),
-        StructField("cuboid_points", get_cuboid_schema(), True),
-        StructField("ellipse_points", MapType(StringType(), FloatType()),
-                    True),
-        StructField("point_points", MapType(StringType(), FloatType()), True),
-        StructField("groupId", IntegerType(), True),
-        StructField("locked", BooleanType(), True),
-        StructField("attributes", ArrayType(MapType(StringType(),
-                                                    StringType())),
+def get_video_comment_parameter_schema():
+    return StructType([
+        StructField("start", IntegerType(), True),
+        StructField("end", IntegerType, True),
+        StructField("timestamps", ArrayType(
+            get_video_timestamp_schema()), True)
+    ])
+
+
+def get_video_comment_schema():
+    return StructType([
+        StructField("correspondence",
+                    ArrayType(MapType(
+                        StringType(),
+                        StringType())),
                     True),
-        StructField("trackingId", StringType(), True),
-        StructField("error", StringType(), True),
+        StructField("start", IntegerType(), True),
+        StructField("end", IntegerType(), True),
         StructField("createdAt", StringType(), True),
-        StructField("createdBy", MapType(StringType(), StringType()), True),
+        StructField("createdBy", MapType(
+            StringType(),
+            StringType()),
+            True),
         StructField("creationType", StringType(), True),
         StructField("updatedAt", StringType(), True),
-        StructField("updatedBy", MapType(StringType(), StringType()), True),
-        StructField("className", StringType(), True)
-    ])
-    return instance_schema
-
+        StructField("updatedBy", MapType(
+            StringType(),
+            StringType()),
+            True),
+        StructField("parameters",
+                    ArrayType(get_video_comment_parameter_schema()), True)
 
-def get_vector_schema():
-    schema = StructType([
-        StructField("image_height", IntegerType(), True),
-        StructField("image_width", IntegerType(), True),
-        StructField("image_name", StringType(), True),
-        StructField("projectId", IntegerType(), True),
-        StructField("isPredicted", BooleanType(), True),
-        StructField("status", StringType(), True),
-        StructField("pinned", BooleanType(), True),
-        StructField("annotatorEmail", StringType(), True),
-        StructField("qaEmail", StringType(), True),
-        StructField("instances", ArrayType(get_vector_instance_schema()),
-                    True),
-        StructField("bounding_boxes", ArrayType(IntegerType()), True),
-        StructField("comments", ArrayType(get_comment_schema()), True)
     ])
-    return schema
```

### Comparing `superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector/text.py` & `superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/text.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,9 +1,11 @@
 from datetime import datetime
-from superannotate_databricks_connector.schemas.text_schema import get_text_schema
+from superannotate_databricks_connector.schemas.text_schema import (
+    get_text_schema
+)
 
 
 def convert_dates(instance):
     """
     Parses the date columns createdAt and updatedAt
     in instances to datetime format
 
@@ -36,15 +38,14 @@
     }
     """
     rows = []
     for item in annotations:
         flattened_item = {
             "name": item["metadata"]["name"],
             "url": item["metadata"]["url"],
-            "contentLength": item["metadata"]["contentLength"],
             "projecId": item["metadata"]["projectId"],
             "status": item["metadata"]["status"],
             "annotatorEmail": item["metadata"]["annotatorEmail"],
             "qaEmail": item["metadata"]["qaEmail"],
             "entities": [convert_dates(instance) for instance
                          in item["instances"] if instance["type"] == "entity"],
             "tags": [convert_dates(instance) for instance in item["instances"]
```

### Comparing `superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector/vector.py` & `superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector/vector.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,10 @@
-from superannotate_databricks_connector.schemas.vector_schema import get_vector_schema
+from superannotate_databricks_connector.schemas.vector_schema import (
+    get_vector_schema
+)
 
 
 def process_comment(comment):
     comment["x"] = float(comment.get("x"))
     comment["y"] = float(comment.get("y"))
     return comment
 
@@ -18,33 +20,37 @@
         (dict) reformated instance
     """
     return {
         'instance_type': instance['type'],
         'classId': instance["classId"] if custom_id_map is None
         else custom_id_map.get(instance["className"]),
         'probability': instance.get('probability'),
-        'bbox_points': {k: float(v) for k, v in instance['points'].items()}
+        'bbox': {k: float(v) for k, v in instance['points'].items()}
         if instance["type"] == "bbox" else None,
-        'polygon_points': [float(p) for p in instance['points']]
+        'rbbox': {k: float(v) for k, v in instance['points'].items()}
+        if instance["type"] == "rbbox" else None,
+        'polygon': {"points": [float(p) for p in instance['points']]
+                    if instance["type"] == "polygon" else None,
+                    'exclude': instance.get("exclude")}
         if instance["type"] == "polygon" else None,
-        'polygon_exclude': instance["exclude"]
-        if instance["type"] == "polygon" else None,
-        'point_points': {"x": float(instance["x"]),
-                         "y": float(instance["y"])
-                         } if instance["type"] == "point" else None,
-        'ellipse_points': {"cx": float(instance["cx"]),
-                           "cy": float(instance["cy"]),
-                           "rx": float(instance["rx"]),
-                           "ry": float(instance["ry"]),
-                           "angle": float(instance["angle"])}
+        'point': {"x": float(instance.get("x")),
+                  "y": float(instance.get("y"))
+                  } if instance["type"] == "point" else None,
+        'ellipse': {"cx": float(instance["cx"]),
+                    "cy": float(instance["cy"]),
+                    "rx": float(instance["rx"]),
+                    "ry": float(instance["ry"]),
+                    "angle": float(instance["angle"])}
         if instance["type"] == "ellipse" else None,
-        'cuboid_points': {outer_k: {inner_k: float(inner_v)
-                                    for inner_k, inner_v in outer_v.items()}
-                          for outer_k, outer_v in instance['points'].items()}
+        'cuboid': {outer_k: {inner_k: float(inner_v)
+                             for inner_k, inner_v in outer_v.items()}
+                   for outer_k, outer_v in instance['points'].items()}
         if instance["type"] == "cuboid" else None,
+        "polyline": [float(p) for p in instance['points']]
+        if instance["type"] == "polyline" else None,
         'groupId': instance.get('groupId'),
         'locked': instance.get('locked'),
         'attributes': instance['attributes'],
         'trackingId': instance.get('trackingId'),
         'error': instance.get('error'),
         'createdAt': instance.get('createdAt'),
         'createdBy': instance.get('createdBy'),
@@ -136,19 +142,21 @@
             'isPredicted': item["metadata"]['isPredicted'],
             'status': item["metadata"]['status'],
             'pinned': item["metadata"]['pinned'],
             'annotatorEmail': item["metadata"]['annotatorEmail'],
             'qaEmail': item["metadata"]['qaEmail'],
             "instances": [process_vector_object(instance, custom_id_map)
                           for instance in item["instances"]
-                          if instance["type"] == "object"],
+                          if instance["type"] != "tag"],
             "bounding_boxes": get_boxes(item["instances"], custom_id_map),
             "tags": [process_vector_tag(instance, custom_id_map)
                      for instance in item["instances"]
                      if instance["type"] == "tag"],
             "comments": [process_comment(comment)
                          for comment in item["comments"]]
         }
+
         rows.append(flattened_item)
     schema = get_vector_schema()
+
     spark_df = spark.createDataFrame(rows, schema=schema)
     return spark_df
```

### Comparing `superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector.egg-info/PKG-INFO` & `superannotate_databricks_connector-0.0.1.dev2/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: superannotate-databricks-connector
-Version: 0.0.1.dev1
+Name: superannotate_databricks_connector
+Version: 0.0.1.dev2
 Summary: Custom functions to work with SuperAnnotate in Databricks
 Author-email: Leo Lindén <leo@superannotate.com>
 Maintainer-email: Leo Lindén <leo@superannotate.com>
 License: MIT License
         
         Copyright (c) 2023 SuperAnnotate AI Inc.
```

### Comparing `superannotate_databricks_connector-0.0.1.dev1/src/superannotate_databricks_connector.egg-info/SOURCES.txt` & `superannotate_databricks_connector-0.0.1.dev2/src/superannotate_databricks_connector.egg-info/SOURCES.txt`

 * *Files 3% similar despite different names*

```diff
@@ -6,11 +6,14 @@
 src/superannotate_databricks_connector.egg-info/PKG-INFO
 src/superannotate_databricks_connector.egg-info/SOURCES.txt
 src/superannotate_databricks_connector.egg-info/dependency_links.txt
 src/superannotate_databricks_connector.egg-info/requires.txt
 src/superannotate_databricks_connector.egg-info/top_level.txt
 src/superannotate_databricks_connector/schemas/__init__.py
 src/superannotate_databricks_connector/schemas/comment.py
+src/superannotate_databricks_connector/schemas/shapes.py
+src/superannotate_databricks_connector/schemas/tag.py
 src/superannotate_databricks_connector/schemas/text_schema.py
 src/superannotate_databricks_connector/schemas/vector_schema.py
+src/superannotate_databricks_connector/schemas/video_schema.py
 tests/test_text.py
 tests/test_vector.py
```

### Comparing `superannotate_databricks_connector-0.0.1.dev1/tests/test_text.py` & `superannotate_databricks_connector-0.0.1.dev2/tests/test_text.py`

 * *Files identical despite different names*

### Comparing `superannotate_databricks_connector-0.0.1.dev1/tests/test_vector.py` & `superannotate_databricks_connector-0.0.1.dev2/tests/test_vector.py`

 * *Files 6% similar despite different names*

```diff
@@ -13,31 +13,27 @@
     get_vector_dataframe
 )
 
 
 class TestVectorInstances(unittest.TestCase):
     def __init__(self, *args):
         super().__init__(*args)
-        with open(os.path.join(DATA_SET_PATH, "vector/example_annotation.json"), "r") as f:
+        with open(os.path.join(DATA_SET_PATH,
+                               "vector/example_annotation.json"), "r") as f:
             data = json.load(f)
-
-        target_data = []
-        with open(os.path.join(DATA_SET_PATH, 'vector/expected_instances.json'),"r") as f:
-            for line in f:
-                target_data.append(json.loads(line))
-
         self.test_data = data
-        self.target_data = target_data
         self.spark = SparkSession.builder.appName('test').getOrCreate()
 
     def __get_test_pair(self, instance_type):
         test = [data for data in self.test_data["instances"]
                 if data["type"] == instance_type][0]
-        target = [data for data in self.target_data
-                  if data["instance_type"] == instance_type][0]
+        with open(os.path.join(DATA_SET_PATH,
+                               f'vector/expected_{instance_type}.json'),
+                  "r") as f:
+            target = json.load(f)
         return test, target
 
     def __assert_equal(self, instance_type):
         test, target = self.__get_test_pair(instance_type)
         self.assertEqual(process_vector_object(test), target)
 
     def test_bounding_box(self):
@@ -92,27 +88,29 @@
                       "classId": 10228},
                      {"type": "bbox", "points": {
                          "x1": 3.19,
                          "x2": 4.23,
                          "y1": 2.1,
                          "y2": 18.9
                      },
-                      "classId": 10229}]
+            "classId": 10229}]
         target = [2, 1, 13, 22, 10228, 3, 2, 4, 19, 10229]
         self.assertEqual(get_boxes(instances), target)
 
 
 class TestVectorDataFrame(unittest.TestCase):
     def test_vector_dataframe(self):
         spark = SparkSession.builder.master("local").getOrCreate()
-        with open(os.path.join(DATA_SET_PATH, "vector/example_annotation.json"),"r") as f:
+        with open(os.path.join(DATA_SET_PATH,
+                               "vector/example_annotation.json"), "r") as f:
             data = json.load(f)
 
         actual_df = get_vector_dataframe([data], spark)
 
-        expected_df = spark.read.parquet(os.path.join(DATA_SET_PATH, "vector/expected_df.parquet"))
+        expected_df = spark.read.parquet(os.path.join(
+            DATA_SET_PATH, "vector/expected_df.parquet"))
         self.assertEqual(sorted(actual_df.collect()),
                          sorted(expected_df.collect()))
 
 
 if __name__ == '__main__':
     unittest.main()
```


# Comparing `tmp/sparksampling_proto-0.0.1.tar.gz` & `tmp/sparksampling_proto-0.1.0.tar.gz`

## Comparing `sparksampling_proto-0.0.1.tar` & `sparksampling_proto-0.1.0.tar`

### file list

```diff
@@ -1,8 +1,8 @@
--rwxr-xr-x   0        0        0     7201 2020-02-02 00:00:00.000000 sparksampling_proto-0.0.1/pb/sampling_service.proto
--rwxr-xr-x   0        0        0       22 2020-02-02 00:00:00.000000 sparksampling_proto-0.0.1/sparksampling_proto/__init__.py
--rwxr-xr-x   0        0        0    14416 2020-02-02 00:00:00.000000 sparksampling_proto-0.0.1/sparksampling_proto/sampling_service_pb2.py
--rwxr-xr-x   0        0        0     5796 2020-02-02 00:00:00.000000 sparksampling_proto-0.0.1/sparksampling_proto/sampling_service_pb2_grpc.py
--rwxr-xr-x   0        0        0     8736 2020-02-02 00:00:00.000000 sparksampling_proto-0.0.1/.gitignore
--rwxr-xr-x   0        0        0      416 2020-02-02 00:00:00.000000 sparksampling_proto-0.0.1/README.md
--rwxr-xr-x   0        0        0      658 2020-02-02 00:00:00.000000 sparksampling_proto-0.0.1/pyproject.toml
--rw-r--r--   0        0        0      799 2020-02-02 00:00:00.000000 sparksampling_proto-0.0.1/PKG-INFO
+-rw-r--r--   0        0        0     7201 2020-02-02 00:00:00.000000 sparksampling_proto-0.1.0/pb/sampling_service.proto
+-rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 sparksampling_proto-0.1.0/sparksampling_proto/__init__.py
+-rw-r--r--   0        0        0     7469 2020-02-02 00:00:00.000000 sparksampling_proto-0.1.0/sparksampling_proto/sampling_service_pb2.py
+-rw-r--r--   0        0        0     5796 2020-02-02 00:00:00.000000 sparksampling_proto-0.1.0/sparksampling_proto/sampling_service_pb2_grpc.py
+-rw-r--r--   0        0        0     8736 2020-02-02 00:00:00.000000 sparksampling_proto-0.1.0/.gitignore
+-rw-r--r--   0        0        0      417 2020-02-02 00:00:00.000000 sparksampling_proto-0.1.0/README.md
+-rw-r--r--   0        0        0      659 2020-02-02 00:00:00.000000 sparksampling_proto-0.1.0/pyproject.toml
+-rw-r--r--   0        0        0      801 2020-02-02 00:00:00.000000 sparksampling_proto-0.1.0/PKG-INFO
```

### Comparing `sparksampling_proto-0.0.1/pb/sampling_service.proto` & `sparksampling_proto-0.1.0/pb/sampling_service.proto`

 * *Files identical despite different names*

### Comparing `sparksampling_proto-0.0.1/sparksampling_proto/sampling_service_pb2_grpc.py` & `sparksampling_proto-0.1.0/sparksampling_proto/sampling_service_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `sparksampling_proto-0.0.1/.gitignore` & `sparksampling_proto-0.1.0/.gitignore`

 * *Files identical despite different names*

### Comparing `sparksampling_proto-0.0.1/pyproject.toml` & `sparksampling_proto-0.1.0/pyproject.toml`

 * *Files 16% similar despite different names*

```diff
@@ -4,16 +4,16 @@
 
 [project]
 name = "sparksampling-proto"
 description = "python proto for sparksampling"
 keywords = ["sparksampling"]
 requires-python = ">=3.7"
 dependencies = [
-    'grpcio>=1.35.0',
-    'protobuf<4',
+    'grpcio>=1.51.0',
+    'protobuf>=4',
 ]
 dynamic = ["version", ]
 
 [[project.authors]]
 name = "Wh1isper"
 email = "9573586@qq.com"
```

### Comparing `sparksampling_proto-0.0.1/PKG-INFO` & `sparksampling_proto-0.1.0/PKG-INFO`

 * *Files 22% similar despite different names*

```diff
@@ -1,18 +1,18 @@
 Metadata-Version: 2.1
 Name: sparksampling-proto
-Version: 0.0.1
+Version: 0.1.0
 Summary: python proto for sparksampling
 Project-URL: Source, https://github.com/Wh1isper/pyspark-sampling
 Author-email: Wh1isper <9573586@qq.com>
 License: BSD 3-Clause License
 Keywords: sparksampling
 Requires-Python: >=3.7
-Requires-Dist: grpcio>=1.35.0
-Requires-Dist: protobuf<4
+Requires-Dist: grpcio>=1.51.0
+Requires-Dist: protobuf>=4
 Description-Content-Type: text/markdown
 
 # protos for datasamplnig
 
 install grpc_tools
 
 ``` shell
@@ -27,8 +27,9 @@
 ```
 
 publish
 
 ```shell
 rm -rf build dist && python -m build
 twine upload dist/*
+
 ```
```


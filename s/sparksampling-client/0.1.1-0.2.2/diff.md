# Comparing `tmp/sparksampling_client-0.1.1.tar.gz` & `tmp/sparksampling_client-0.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sparksampling_client-0.1.1.tar", last modified: Fri Mar 24 02:35:48 2023, max compression
+gzip compressed data, last modified: Sun Feb  2 00:00:00 2020, max compression
```

## Comparing `sparksampling_client-0.1.1.tar` & `sparksampling_client-0.2.2.tar`

### file list

```diff
@@ -1,24 +1,17 @@
-drwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:35:48.731780 sparksampling_client-0.1.1/
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1713 2023-03-24 02:35:48.729782 sparksampling_client-0.1.1/PKG-INFO
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1086 2023-01-16 07:53:55.000000 sparksampling_client-0.1.1/README.rst
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       38 2023-03-24 02:35:48.731780 sparksampling_client-0.1.1/setup.cfg
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1416 2023-03-24 02:27:40.000000 sparksampling_client-0.1.1/setup.py
-drwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:35:48.578166 sparksampling_client-0.1.1/sparksampling_client/
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-01-16 07:53:55.000000 sparksampling_client-0.1.1/sparksampling_client/__init__.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       22 2023-03-24 02:27:48.000000 sparksampling_client-0.1.1/sparksampling_client/_version.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      542 2023-01-16 07:53:55.000000 sparksampling_client-0.1.1/sparksampling_client/cli.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      715 2023-01-16 07:53:55.000000 sparksampling_client-0.1.1/sparksampling_client/config.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-01-16 07:53:55.000000 sparksampling_client-0.1.1/sparksampling_client/logging.py
-drwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:35:48.713782 sparksampling_client-0.1.1/sparksampling_client/proto/
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:26:05.000000 sparksampling_client-0.1.1/sparksampling_client/proto/__init__.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       55 2023-03-24 02:26:28.000000 sparksampling_client-0.1.1/sparksampling_client/proto/sampling_service_pb2.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       60 2023-03-24 02:26:28.000000 sparksampling_client-0.1.1/sparksampling_client/proto/sampling_service_pb2_grpc.py
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      842 2023-01-16 07:53:55.000000 sparksampling_client-0.1.1/sparksampling_client/session.py
-drwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        0 2023-03-24 02:35:48.667782 sparksampling_client-0.1.1/sparksampling_client.egg-info/
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)     1713 2023-03-24 02:35:48.000000 sparksampling_client-0.1.1/sparksampling_client.egg-info/PKG-INFO
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)      663 2023-03-24 02:35:48.000000 sparksampling_client-0.1.1/sparksampling_client.egg-info/SOURCES.txt
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        1 2023-03-24 02:35:48.000000 sparksampling_client-0.1.1/sparksampling_client.egg-info/dependency_links.txt
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       53 2023-03-24 02:35:48.000000 sparksampling_client-0.1.1/sparksampling_client.egg-info/entry_points.txt
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)        1 2022-11-04 16:17:09.000000 sparksampling_client-0.1.1/sparksampling_client.egg-info/not-zip-safe
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       52 2023-03-24 02:35:48.000000 sparksampling_client-0.1.1/sparksampling_client.egg-info/requires.txt
--rwxrwxrwx   0 wh1isper  (1000) wh1isper  (1000)       21 2023-03-24 02:35:48.000000 sparksampling_client-0.1.1/sparksampling_client.egg-info/top_level.txt
+-rw-r--r--   0        0        0      780 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/RELEASE.md
+-rw-r--r--   0        0        0       46 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/dockerbuild/config.json
+-rw-r--r--   0        0        0      422 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/dockerbuild/ssc.Dockerfile
+-rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/sparksampling_client/__init__.py
+-rw-r--r--   0        0        0      541 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/sparksampling_client/cli.py
+-rw-r--r--   0        0        0      716 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/sparksampling_client/config.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/sparksampling_client/logging.py
+-rw-r--r--   0        0        0      840 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/sparksampling_client/session.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/sparksampling_client/proto/__init__.py
+-rw-r--r--   0        0        0       55 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/sparksampling_client/proto/sampling_service_pb2.py
+-rw-r--r--   0        0        0       60 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/sparksampling_client/proto/sampling_service_pb2_grpc.py
+-rw-r--r--   0        0        0     1225 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/tests/test_apply.py
+-rw-r--r--   0        0        0     8736 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/.gitignore
+-rw-r--r--   0        0        0    11324 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/LICENSE
+-rw-r--r--   0        0        0      730 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/README.md
+-rw-r--r--   0        0        0     1159 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/pyproject.toml
+-rw-r--r--   0        0        0     1599 2020-02-02 00:00:00.000000 sparksampling_client-0.2.2/PKG-INFO
```

### Comparing `sparksampling_client-0.1.1/PKG-INFO` & `sparksampling_client-0.2.2/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,61 +1,58 @@
 Metadata-Version: 2.1
 Name: sparksampling_client
-Version: 0.1.1
-Summary: pyspark-sampling
-Home-page: https://github.com/Wh1isper/pyspark-sampling
-Author: wh1isper
-Author-email: 9573586@qq.com
-Keywords: sparksampling_client
+Version: 0.2.2
+Summary: client for sparksampling
+Project-URL: Source, https://github.com/Wh1isper/pyspark-sampling
+Author-email: Wh1isper <9573586@qq.com>
+License: Apache License 2.0
+License-File: LICENSE
+Keywords: pyspark-sampling,sparksampling_client
 Classifier: Development Status :: 2 - Pre-Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Natural Language :: English
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.5
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
-Requires-Python: >=3.5
+Requires-Python: >=3.7
+Requires-Dist: click
+Requires-Dist: sparksampling-proto==0.0.1
+Provides-Extra: test
+Requires-Dist: pytest; extra == 'test'
+Description-Content-Type: text/markdown
 
 This is a Python Grpc Stub for ``sparksampling``
 
-========================================
-sparksampling
-========================================
-``sparksampling`` is a PySpark-based sampling and data quality assessment GRPC service that supports containerized deployments and Spark on K8S
+# sparksampling
+`sparksampling` is a PySpark-based sampling and data quality assessment GRPC service that supports containerized deployments and Spark on K8S
 
 
-Feature
-========================================
+## Feature
 
 - Common sampling methods: Random, Stratified, Simple
 - Relationship Sampling based on DAG and Topological sorting
 - Cloud Native and Spark on K8S support
 
 
-========================================
-QUICK START
-========================================
+# QUICK START
 
-Installation
-========================================
+## Installation
 
 The trial only requires direct installation using pypi
 
 ``pip install sparksampling``
 
 run as
 
 ``sparksampling``
 
 The service will start and listen on port 8530
 
-Docker
-========================================
+## Docker
 
 ``docker run -p 8530:8530 wh1isper/pysparksampling:latest``
 
-========================================
-MORE
-========================================
+# MORE
 
 For more, see our github page: https://github.com/Wh1isper/pyspark-sampling/
```

### Comparing `sparksampling_client-0.1.1/README.rst` & `sparksampling_client-0.2.2/README.md`

 * *Files 25% similar despite different names*

```diff
@@ -1,43 +1,34 @@
 This is a Python Grpc Stub for ``sparksampling``
 
-========================================
-sparksampling
-========================================
-``sparksampling`` is a PySpark-based sampling and data quality assessment GRPC service that supports containerized deployments and Spark on K8S
+# sparksampling
+`sparksampling` is a PySpark-based sampling and data quality assessment GRPC service that supports containerized deployments and Spark on K8S
 
 
-Feature
-========================================
+## Feature
 
 - Common sampling methods: Random, Stratified, Simple
 - Relationship Sampling based on DAG and Topological sorting
 - Cloud Native and Spark on K8S support
 
 
-========================================
-QUICK START
-========================================
+# QUICK START
 
-Installation
-========================================
+## Installation
 
 The trial only requires direct installation using pypi
 
 ``pip install sparksampling``
 
 run as
 
 ``sparksampling``
 
 The service will start and listen on port 8530
 
-Docker
-========================================
+## Docker
 
 ``docker run -p 8530:8530 wh1isper/pysparksampling:latest``
 
-========================================
-MORE
-========================================
+# MORE
 
 For more, see our github page: https://github.com/Wh1isper/pyspark-sampling/
```

### Comparing `sparksampling_client-0.1.1/sparksampling_client/cli.py` & `sparksampling_client-0.2.2/sparksampling_client/cli.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,35 +1,34 @@
 import click
-
 from sparksampling_client.config import reset_config
 from sparksampling_client.session import Session
 
 
 @click.command()
 def init():
     assert Session()
-    print('Pyspark sampling client initialized!')
+    print("Pyspark sampling client initialized!")
 
 
 @click.command()
 def reset():
     reset_config()
 
 
 @click.command()
-@click.argument('json_file')
+@click.argument("json_file")
 def apply(json_file):
     session = Session()
     session.apply_file(json_file)
 
 
 @click.group()
 def cli():
     pass
 
 
 cli.add_command(init)
 cli.add_command(reset)
 cli.add_command(apply)
 
-if __name__ == '__main__':
+if __name__ == "__main__":
     cli()
```

### Comparing `sparksampling_client-0.1.1/sparksampling_client/config.py` & `sparksampling_client-0.2.2/sparksampling_client/config.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,26 +1,27 @@
+import json
 import os
 import pathlib
-import json
 
-CONFIG_PATH = os.path.expanduser('~/.ssc/config.json')
+CONFIG_PATH = os.path.expanduser("~/.ssc/config.json")
 CONFIG_FILE = pathlib.Path(CONFIG_PATH)
 CONFIG_FILE.parent.mkdir(exist_ok=True)
 DEFAULT_CONFIG = {
-    'host': 'localhost',
-    'port': '8530',
+    "host": "localhost",
+    "port": "8530",
 }
 
 
 def load_config():
     if not CONFIG_FILE.exists():
-        print(f'No config file found, generating default config in {CONFIG_FILE}')
-        with CONFIG_FILE.open('w') as f:
+        print(f"No config file found, generating default config in {CONFIG_FILE}")
+        with CONFIG_FILE.open("w") as f:
             json.dump(DEFAULT_CONFIG, f)
-    print(f'Loading config from {CONFIG_FILE}')
+    print(f"Loading config from {CONFIG_FILE}")
     with CONFIG_FILE.open() as f:
         return json.load(f)
 
+
 def reset_config():
-    print(f'Config {CONFIG_FILE} reset to default')
-    with CONFIG_FILE.open('w') as f:
+    print(f"Config {CONFIG_FILE} reset to default")
+    with CONFIG_FILE.open("w") as f:
         json.dump(DEFAULT_CONFIG, f)
```

### Comparing `sparksampling_client-0.1.1/sparksampling_client/session.py` & `sparksampling_client-0.2.2/sparksampling_client/session.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,23 +1,23 @@
-import grpc
 import json
 
+import grpc
 from sparksampling_client.config import load_config
 from sparksampling_client.proto import sampling_service_pb2_grpc
 from sparksampling_client.proto.sampling_service_pb2 import SamplingRequest
 
 
-class Session():
+class Session:
     def __init__(self, host=None, port=None):
         config = load_config()
-        self.host = host or config.get('host')
-        self.port = port or config.get('port')
+        self.host = host or config.get("host")
+        self.port = port or config.get("port")
 
     def make_request(self, request):
-        with grpc.insecure_channel(f'{self.host}:{self.port}') as channel:
+        with grpc.insecure_channel(f"{self.host}:{self.port}") as channel:
             stub = sampling_service_pb2_grpc.SparkSamplingServiceStub(channel)
             response = stub.SamplingJob(request)
         return response
 
     def apply_file(self, json_file):
         with open(json_file) as f:
             request = SamplingRequest(**json.load(f))
```


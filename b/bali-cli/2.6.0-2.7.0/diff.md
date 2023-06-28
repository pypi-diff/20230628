# Comparing `tmp/bali-cli-2.6.0.tar.gz` & `tmp/bali-cli-2.7.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/bali-cli-2.6.0.tar", last modified: Thu Nov 10 08:06:21 2022, max compression
+gzip compressed data, was "dist/bali-cli-2.7.0.tar", last modified: Wed Jun 28 07:54:07 2023, max compression
```

## Comparing `bali-cli-2.6.0.tar` & `bali-cli-2.7.0.tar`

### file list

```diff
@@ -1,28 +1,28 @@
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-11-10 08:06:21.000000 bali-cli-2.6.0/
--rw-r--r--   0 runner    (1001) docker     (121)       24 2022-11-10 08:05:44.000000 bali-cli-2.6.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (121)     2656 2022-11-10 08:06:21.000000 bali-cli-2.6.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)     1604 2022-11-10 08:05:44.000000 bali-cli-2.6.0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-11-10 08:06:21.000000 bali-cli-2.6.0/bali_cli.egg-info/
--rw-r--r--   0 runner    (1001) docker     (121)     2656 2022-11-10 08:06:20.000000 bali-cli-2.6.0/bali_cli.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)      477 2022-11-10 08:06:20.000000 bali-cli-2.6.0/bali_cli.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2022-11-10 08:06:20.000000 bali-cli-2.6.0/bali_cli.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (121)       39 2022-11-10 08:06:20.000000 bali-cli-2.6.0/bali_cli.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2022-11-10 08:06:20.000000 bali-cli-2.6.0/bali_cli.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (121)      186 2022-11-10 08:06:20.000000 bali-cli-2.6.0/bali_cli.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (121)       10 2022-11-10 08:06:20.000000 bali-cli-2.6.0/bali_cli.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-11-10 08:06:21.000000 bali-cli-2.6.0/cli/
--rw-r--r--   0 runner    (1001) docker     (121)       22 2022-11-10 08:05:44.000000 bali-cli-2.6.0/cli/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)     6089 2022-11-10 08:05:44.000000 bali-cli-2.6.0/cli/biz.py
--rw-r--r--   0 runner    (1001) docker     (121)      944 2022-11-10 08:05:44.000000 bali-cli-2.6.0/cli/main.py
--rw-r--r--   0 runner    (1001) docker     (121)      332 2022-11-10 08:05:44.000000 bali-cli-2.6.0/cli/run.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-11-10 08:06:21.000000 bali-cli-2.6.0/cli/templates/
--rw-r--r--   0 runner    (1001) docker     (121)     2074 2022-11-10 08:05:44.000000 bali-cli-2.6.0/cli/templates/client.jinja2
--rw-r--r--   0 runner    (1001) docker     (121)       92 2022-11-10 08:05:44.000000 bali-cli-2.6.0/cli/templates/clients.init.jinja2
--rw-r--r--   0 runner    (1001) docker     (121)      156 2022-11-10 08:05:44.000000 bali-cli-2.6.0/cli/templates/config.jinja2
--rw-r--r--   0 runner    (1001) docker     (121)    12041 2022-11-10 08:05:44.000000 bali-cli-2.6.0/cli/templates/utils.jinja2
--rw-r--r--   0 runner    (1001) docker     (121)       38 2022-11-10 08:06:21.000000 bali-cli-2.6.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (121)      745 2022-11-10 08:05:44.000000 bali-cli-2.6.0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-11-10 08:06:21.000000 bali-cli-2.6.0/tests/
--rw-r--r--   0 runner    (1001) docker     (121)        0 2022-11-10 08:05:44.000000 bali-cli-2.6.0/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)     4687 2022-11-10 08:05:44.000000 bali-cli-2.6.0/tests/test_biz.py
--rw-r--r--   0 runner    (1001) docker     (121)      185 2022-11-10 08:05:44.000000 bali-cli-2.6.0/tests/test_main.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:54:07.000000 bali-cli-2.7.0/
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 07:53:52.000000 bali-cli-2.7.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     2656 2023-06-28 07:54:07.000000 bali-cli-2.7.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1604 2023-06-28 07:53:52.000000 bali-cli-2.7.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:54:07.000000 bali-cli-2.7.0/bali_cli.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2656 2023-06-28 07:54:07.000000 bali-cli-2.7.0/bali_cli.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      477 2023-06-28 07:54:07.000000 bali-cli-2.7.0/bali_cli.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 07:54:07.000000 bali-cli-2.7.0/bali_cli.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 07:54:07.000000 bali-cli-2.7.0/bali_cli.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 07:54:07.000000 bali-cli-2.7.0/bali_cli.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      186 2023-06-28 07:54:07.000000 bali-cli-2.7.0/bali_cli.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 07:54:07.000000 bali-cli-2.7.0/bali_cli.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:54:07.000000 bali-cli-2.7.0/cli/
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 07:53:52.000000 bali-cli-2.7.0/cli/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6105 2023-06-28 07:53:52.000000 bali-cli-2.7.0/cli/biz.py
+-rw-r--r--   0 runner    (1001) docker     (123)      944 2023-06-28 07:53:52.000000 bali-cli-2.7.0/cli/main.py
+-rw-r--r--   0 runner    (1001) docker     (123)      332 2023-06-28 07:53:52.000000 bali-cli-2.7.0/cli/run.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:54:07.000000 bali-cli-2.7.0/cli/templates/
+-rw-r--r--   0 runner    (1001) docker     (123)     2074 2023-06-28 07:53:52.000000 bali-cli-2.7.0/cli/templates/client.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)       92 2023-06-28 07:53:52.000000 bali-cli-2.7.0/cli/templates/clients.init.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)      156 2023-06-28 07:53:52.000000 bali-cli-2.7.0/cli/templates/config.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)    12041 2023-06-28 07:53:52.000000 bali-cli-2.7.0/cli/templates/utils.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 07:54:07.000000 bali-cli-2.7.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      745 2023-06-28 07:53:52.000000 bali-cli-2.7.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:54:07.000000 bali-cli-2.7.0/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:53:52.000000 bali-cli-2.7.0/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4687 2023-06-28 07:53:52.000000 bali-cli-2.7.0/tests/test_biz.py
+-rw-r--r--   0 runner    (1001) docker     (123)      185 2023-06-28 07:53:52.000000 bali-cli-2.7.0/tests/test_main.py
```

### Comparing `bali-cli-2.6.0/PKG-INFO` & `bali-cli-2.7.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: bali-cli
-Version: 2.6.0
+Version: 2.7.0
 Summary: Simplify gRPC services and clients
 Home-page: https://github.com/bali-framework/bali-cli
 Author: Josh.Yu
 Author-email: josh.yu_8@live.com
 License: MIT
 Description: <p align="center">
           <img src="https://raw.githubusercontent.com/bali-framework/bali/master/docs/img/bali.png" alt='bali framework' />
```

### Comparing `bali-cli-2.6.0/README.md` & `bali-cli-2.7.0/README.md`

 * *Files identical despite different names*

### Comparing `bali-cli-2.6.0/bali_cli.egg-info/PKG-INFO` & `bali-cli-2.7.0/bali_cli.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: bali-cli
-Version: 2.6.0
+Version: 2.7.0
 Summary: Simplify gRPC services and clients
 Home-page: https://github.com/bali-framework/bali-cli
 Author: Josh.Yu
 Author-email: josh.yu_8@live.com
 License: MIT
 Description: <p align="center">
           <img src="https://raw.githubusercontent.com/bali-framework/bali/master/docs/img/bali.png" alt='bali framework' />
```

### Comparing `bali-cli-2.6.0/cli/biz.py` & `bali-cli-2.7.0/cli/biz.py`

 * *Files 0% similar despite different names*

```diff
@@ -166,15 +166,15 @@
     current_dir = Path.cwd()
     proto_dirs = [
         current_dir / "protos",
         current_dir / "services" / "rpc",
     ]
     base_command = (
         'python3 -m grpc_tools.protoc '
-        ' -I{dir} --python_out={dir} --grpc_python_out={dir} {file}'
+        ' -I{dir} --pyi_out={dir} --python_out={dir} --grpc_python_out={dir} {file}'
     )
 
     for proto_dir in proto_dirs:
         for _1, _2, filenames in os.walk(proto_dir):
             for i in filenames:
                 file = proto_dir / i
                 if file.suffix == ".proto":
```

### Comparing `bali-cli-2.6.0/cli/main.py` & `bali-cli-2.7.0/cli/main.py`

 * *Files identical despite different names*

### Comparing `bali-cli-2.6.0/cli/templates/client.jinja2` & `bali-cli-2.7.0/cli/templates/client.jinja2`

 * *Files identical despite different names*

### Comparing `bali-cli-2.6.0/cli/templates/utils.jinja2` & `bali-cli-2.7.0/cli/templates/utils.jinja2`

 * *Files identical despite different names*

### Comparing `bali-cli-2.6.0/setup.py` & `bali-cli-2.7.0/setup.py`

 * *Files identical despite different names*

### Comparing `bali-cli-2.6.0/tests/test_biz.py` & `bali-cli-2.7.0/tests/test_biz.py`

 * *Files identical despite different names*


# Comparing `tmp/stability-sdk-0.8.1.tar.gz` & `tmp/stability-sdk-0.8.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "stability-sdk-0.8.1.tar", last modified: Thu May 18 21:37:10 2023, max compression
+gzip compressed data, was "stability-sdk-0.8.2.tar", last modified: Tue Jun 27 23:22:03 2023, max compression
```

## Comparing `stability-sdk-0.8.1.tar` & `stability-sdk-0.8.2.tar`

### file list

```diff
@@ -1,56 +1,56 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-18 21:37:10.174363 stability-sdk-0.8.1/
--rw-r--r--   0 runner    (1001) docker     (123)     1136 2023-05-18 21:36:49.000000 stability-sdk-0.8.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     7189 2023-05-18 21:37:10.174363 stability-sdk-0.8.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     5754 2023-05-18 21:36:49.000000 stability-sdk-0.8.1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      147 2023-05-18 21:36:49.000000 stability-sdk-0.8.1/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-18 21:37:10.174363 stability-sdk-0.8.1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2278 2023-05-18 21:36:49.000000 stability-sdk-0.8.1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-18 21:37:10.166363 stability-sdk-0.8.1/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-18 21:37:10.170363 stability-sdk-0.8.1/src/stability_sdk/
--rw-r--r--   0 runner    (1001) docker     (123)      433 2023-05-18 21:36:49.000000 stability-sdk-0.8.1/src/stability_sdk/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1033 2023-05-18 21:36:49.000000 stability-sdk-0.8.1/src/stability_sdk/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    55273 2023-05-18 21:36:49.000000 stability-sdk-0.8.1/src/stability_sdk/animation.py
--rw-r--r--   0 runner    (1001) docker     (123)    37904 2023-05-18 21:36:49.000000 stability-sdk-0.8.1/src/stability_sdk/animation_ui.py
--rw-r--r--   0 runner    (1001) docker     (123)    28265 2023-05-18 21:36:49.000000 stability-sdk-0.8.1/src/stability_sdk/api.py
--rw-r--r--   0 runner    (1001) docker     (123)    24351 2023-05-18 21:36:49.000000 stability-sdk-0.8.1/src/stability_sdk/client.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-18 21:37:10.170363 stability-sdk-0.8.1/src/stability_sdk/interfaces/
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-18 21:37:10.170363 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-18 21:37:10.170363 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/dashboard/
--rw-r--r--   0 runner    (1001) docker     (123)    20130 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/dashboard/dashboard_pb2.py
--rw-r--r--   0 runner    (1001) docker     (123)    25811 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/dashboard/dashboard_pb2_grpc.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-18 21:37:10.170363 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/engines/
--rw-r--r--   0 runner    (1001) docker     (123)     3615 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/engines/engines_pb2.py
--rw-r--r--   0 runner    (1001) docker     (123)     2444 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/engines/engines_pb2_grpc.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-18 21:37:10.170363 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/generation/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/generation/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    37427 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/generation/generation_pb2.py
--rw-r--r--   0 runner    (1001) docker     (123)     3861 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/generation/generation_pb2_grpc.py
--rw-r--r--   0 runner    (1001) docker     (123)     4121 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/generation/tensors_pb2.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-18 21:37:10.174363 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/project/
--rw-r--r--   0 runner    (1001) docker     (123)    16883 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/project/project_pb2.py
--rw-r--r--   0 runner    (1001) docker     (123)    14190 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/project/project_pb2_grpc.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-18 21:37:10.166363 stability-sdk-0.8.1/src/stability_sdk/interfaces/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-18 21:37:10.174363 stability-sdk-0.8.1/src/stability_sdk/interfaces/src/tensorizer/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-18 21:36:52.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/src/tensorizer/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5479 2023-05-18 21:36:52.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/src/tensorizer/protobuf.py
--rw-r--r--   0 runner    (1001) docker     (123)    34404 2023-05-18 21:36:52.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/src/tensorizer/tensorizer.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-18 21:37:10.174363 stability-sdk-0.8.1/src/stability_sdk/interfaces/src/tensorizer/tensors/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-18 21:36:52.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/src/tensorizer/tensors/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4121 2023-05-18 21:36:52.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/src/tensorizer/tensors/tensors_pb2.py
--rw-r--r--   0 runner    (1001) docker     (123)     1366 2023-05-18 21:36:52.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/src/tensorizer/test_protobuf.py
--rw-r--r--   0 runner    (1001) docker     (123)     1567 2023-05-18 21:36:52.000000 stability-sdk-0.8.1/src/stability_sdk/interfaces/src/tensorizer/test_tensorizer.py
--rw-r--r--   0 runner    (1001) docker     (123)     2289 2023-05-18 21:36:49.000000 stability-sdk-0.8.1/src/stability_sdk/matrix.py
--rw-r--r--   0 runner    (1001) docker     (123)    13063 2023-05-18 21:36:49.000000 stability-sdk-0.8.1/src/stability_sdk/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-18 21:37:10.170363 stability-sdk-0.8.1/src/stability_sdk.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     7189 2023-05-18 21:37:10.000000 stability-sdk-0.8.1/src/stability_sdk.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1718 2023-05-18 21:37:10.000000 stability-sdk-0.8.1/src/stability_sdk.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-18 21:37:10.000000 stability-sdk-0.8.1/src/stability_sdk.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      219 2023-05-18 21:37:10.000000 stability-sdk-0.8.1/src/stability_sdk.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       14 2023-05-18 21:37:10.000000 stability-sdk-0.8.1/src/stability_sdk.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-18 21:37:10.174363 stability-sdk-0.8.1/tests/
--rw-r--r--   0 runner    (1001) docker     (123)     2770 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/tests/test_animator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7770 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/tests/test_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     1479 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/tests/test_client.py
--rw-r--r--   0 runner    (1001) docker     (123)     5879 2023-05-18 21:36:50.000000 stability-sdk-0.8.1/tests/test_utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:22:03.814775 stability-sdk-0.8.2/
+-rw-r--r--   0 runner    (1001) docker     (123)     1140 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     7193 2023-06-27 23:22:03.814775 stability-sdk-0.8.2/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     5758 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      147 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 23:22:03.814775 stability-sdk-0.8.2/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2278 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:22:03.810775 stability-sdk-0.8.2/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:22:03.810775 stability-sdk-0.8.2/src/stability_sdk/
+-rw-r--r--   0 runner    (1001) docker     (123)      433 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/src/stability_sdk/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1033 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/src/stability_sdk/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    55306 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/src/stability_sdk/animation.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37904 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/src/stability_sdk/animation_ui.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28265 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/src/stability_sdk/api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24353 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/src/stability_sdk/client.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:22:03.814775 stability-sdk-0.8.2/src/stability_sdk/interfaces/
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 23:21:46.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:22:03.814775 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 23:21:46.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:22:03.814775 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/dashboard/
+-rw-r--r--   0 runner    (1001) docker     (123)    20130 2023-06-27 23:21:46.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/dashboard/dashboard_pb2.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25811 2023-06-27 23:21:46.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/dashboard/dashboard_pb2_grpc.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:22:03.814775 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/engines/
+-rw-r--r--   0 runner    (1001) docker     (123)     3615 2023-06-27 23:21:46.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/engines/engines_pb2.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2444 2023-06-27 23:21:46.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/engines/engines_pb2_grpc.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:22:03.814775 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/generation/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 23:21:46.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/generation/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37427 2023-06-27 23:21:46.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/generation/generation_pb2.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3861 2023-06-27 23:21:46.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/generation/generation_pb2_grpc.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4121 2023-06-27 23:21:46.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/generation/tensors_pb2.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:22:03.814775 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/project/
+-rw-r--r--   0 runner    (1001) docker     (123)    16883 2023-06-27 23:21:46.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/project/project_pb2.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14190 2023-06-27 23:21:46.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/project/project_pb2_grpc.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:22:03.810775 stability-sdk-0.8.2/src/stability_sdk/interfaces/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:22:03.814775 stability-sdk-0.8.2/src/stability_sdk/interfaces/src/tensorizer/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 23:21:47.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/src/tensorizer/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5479 2023-06-27 23:21:47.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/src/tensorizer/protobuf.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34404 2023-06-27 23:21:47.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/src/tensorizer/tensorizer.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:22:03.814775 stability-sdk-0.8.2/src/stability_sdk/interfaces/src/tensorizer/tensors/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 23:21:47.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/src/tensorizer/tensors/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4121 2023-06-27 23:21:47.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/src/tensorizer/tensors/tensors_pb2.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1366 2023-06-27 23:21:47.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/src/tensorizer/test_protobuf.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1567 2023-06-27 23:21:47.000000 stability-sdk-0.8.2/src/stability_sdk/interfaces/src/tensorizer/test_tensorizer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2289 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/src/stability_sdk/matrix.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13063 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/src/stability_sdk/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:22:03.814775 stability-sdk-0.8.2/src/stability_sdk.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     7193 2023-06-27 23:22:03.000000 stability-sdk-0.8.2/src/stability_sdk.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1718 2023-06-27 23:22:03.000000 stability-sdk-0.8.2/src/stability_sdk.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 23:22:03.000000 stability-sdk-0.8.2/src/stability_sdk.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      219 2023-06-27 23:22:03.000000 stability-sdk-0.8.2/src/stability_sdk.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       14 2023-06-27 23:22:03.000000 stability-sdk-0.8.2/src/stability_sdk.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:22:03.814775 stability-sdk-0.8.2/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     2770 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/tests/test_animator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7770 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/tests/test_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1479 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/tests/test_client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5879 2023-06-27 23:21:44.000000 stability-sdk-0.8.2/tests/test_utils.py
```

### Comparing `stability-sdk-0.8.1/LICENSE` & `stability-sdk-0.8.2/LICENSE`

 * *Files 15% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 
-    Copyright (c) Stability.ai, All rights reserved.
+    Copyright (c) Stability AI Ltd, All rights reserved.
 
     Permission is hereby granted, free of charge, to any person obtaining a copy
     of this software and associated documentation files (the "Software"), to deal
     in the Software without restriction, including without limitation the rights
     to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
     copies of the Software, and to permit persons to whom the Software is
     furnished to do so, subject to the following conditions:
```

### Comparing `stability-sdk-0.8.1/PKG-INFO` & `stability-sdk-0.8.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: stability-sdk
-Version: 0.8.1
+Version: 0.8.2
 Summary: Python SDK for interacting with stability.ai APIs
 Home-page: https://beta.dreamstudio.ai/
 Download-URL: https://github.com/Stability-AI/stability-sdk/
 Author: Stability AI
 Author-email: support@stability.ai
 Maintainer: Stability AI
 Maintainer-email: support@stability.ai
@@ -57,15 +57,15 @@
 - Set up in venv dependencies: `pyenv/bin/pip3 install -e .`
 - `pyenv/bin/activate` to use the venv.
 - Set the `STABILITY_HOST` environment variable. This is by default set to the production endpoint `grpc.stability.ai:443`.
 - Set the `STABILITY_KEY` environment variable.
 
 Then to invoke:
 
-`python3 -m stability_sdk generate -W 512 -H 512 "A stunning house."`
+`python3 -m stability_sdk generate -W 1024 -H 1024 "A stunning house."`
 
 It will generate and put PNGs in your current directory.
 
 To upscale:
 `python3 -m stability_sdk upscale -i "/path/to/image.png"`
 
 ## Animation UI
@@ -92,17 +92,17 @@
 
 positional arguments:
   prompt
 
 options:
   -h, --help            show this help message and exit
   --height HEIGHT, -H HEIGHT
-                        [512] height of image
+                        [1024] height of image
   --width WIDTH, -W WIDTH
-                        [512] width of image
+                        [1024] width of image
   --start_schedule START_SCHEDULE
                         [0.5] start schedule for init image (must be greater than 0; 1 is full strength
                         text prompt, no trace of image)
   --end_schedule END_SCHEDULE
                         [0.01] end schedule for init image
   --cfg_scale CFG_SCALE, -C CFG_SCALE
                         [7.0] CFG scale factor
```

### Comparing `stability-sdk-0.8.1/README.md` & `stability-sdk-0.8.2/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -22,15 +22,15 @@
 - Set up in venv dependencies: `pyenv/bin/pip3 install -e .`
 - `pyenv/bin/activate` to use the venv.
 - Set the `STABILITY_HOST` environment variable. This is by default set to the production endpoint `grpc.stability.ai:443`.
 - Set the `STABILITY_KEY` environment variable.
 
 Then to invoke:
 
-`python3 -m stability_sdk generate -W 512 -H 512 "A stunning house."`
+`python3 -m stability_sdk generate -W 1024 -H 1024 "A stunning house."`
 
 It will generate and put PNGs in your current directory.
 
 To upscale:
 `python3 -m stability_sdk upscale -i "/path/to/image.png"`
 
 ## Animation UI
@@ -57,17 +57,17 @@
 
 positional arguments:
   prompt
 
 options:
   -h, --help            show this help message and exit
   --height HEIGHT, -H HEIGHT
-                        [512] height of image
+                        [1024] height of image
   --width WIDTH, -W WIDTH
-                        [512] width of image
+                        [1024] width of image
   --start_schedule START_SCHEDULE
                         [0.5] start schedule for init image (must be greater than 0; 1 is full strength
                         text prompt, no trace of image)
   --end_schedule END_SCHEDULE
                         [0.01] end schedule for init image
   --cfg_scale CFG_SCALE, -C CFG_SCALE
                         [7.0] CFG scale factor
```

### Comparing `stability-sdk-0.8.1/setup.py` & `stability-sdk-0.8.2/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -6,15 +6,15 @@
 )
 
 with open('README.md','r') as f:
     README = f.read()
 
 setup(
     name='stability-sdk',
-    version='0.8.1',
+    version='0.8.2',
     author='Stability AI',
     author_email='support@stability.ai',
     maintainer='Stability AI',
     maintainer_email='support@stability.ai',
     url='https://beta.dreamstudio.ai/',
     download_url='https://github.com/Stability-AI/stability-sdk/',
     description='Python SDK for interacting with stability.ai APIs',
```

### Comparing `stability-sdk-0.8.1/src/stability_sdk/__main__.py` & `stability-sdk-0.8.2/src/stability_sdk/__main__.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/animation.py` & `stability-sdk-0.8.2/src/stability_sdk/animation.py`

 * *Files 1% similar despite different names*

```diff
@@ -58,15 +58,15 @@
         ]
     )
     model = param.Selector(
         default=DEFAULT_MODEL, 
         check_on_set=False, # allow old and new models without raising ValueError
         objects=[
             "stable-diffusion-v1-5", "stable-diffusion-512-v2-1", "stable-diffusion-768-v2-1", 
-            "stable-diffusion-depth-v2-0", "stable-diffusion-xl-beta-v2-2-2",
+            "stable-diffusion-depth-v2-0", "stable-diffusion-xl-beta-v2-2-2", "stable-diffusion-xl-1024-v0-9",
             "custom"
         ]
     )
     custom_model = param.String(default="", doc="Identifier of custom model to use.")
     seed = param.Integer(default=-1, doc="Provide a seed value for more deterministic behavior. Negative seed values will be replaced with a random seed (default).")
     cfg_scale = param.Number(default=7, softbounds=(0,20), doc="Classifier-free guidance scale. Strength of prompt influence on denoising process. `cfg_scale=0` gives unconditioned sampling.")
     clip_guidance = param.Selector(default='None', objects=["None", "Simple", "FastBlue", "FastGreen"], doc="CLIP-guidance preset.")
```

### Comparing `stability-sdk-0.8.1/src/stability_sdk/animation_ui.py` & `stability-sdk-0.8.2/src/stability_sdk/animation_ui.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/api.py` & `stability-sdk-0.8.2/src/stability_sdk/api.py`

 * *Files 1% similar despite different names*

```diff
@@ -65,15 +65,15 @@
 
 class Context:
     def __init__(
             self, 
             host: str="", 
             api_key: str=None, 
             stub: generation_grpc.GenerationServiceStub=None,
-            generate_engine_id: str="stable-diffusion-xl-beta-v2-2-2",
+            generate_engine_id: str="stable-diffusion-xl-1024-v0-9",
             inpaint_engine_id: str="stable-inpainting-512-v2-0",
             interpolate_engine_id: str="interpolation-server-v1",
             transform_engine_id: str="transform-server-v1",
             upscale_engine_id: str="esrgan-v1-x2plus",
         ):
         if not host and stub is None:
             raise Exception("Must provide either GRPC host or stub to Api")
@@ -100,16 +100,16 @@
         self._user_organization_id: Optional[str] = None
         self._user_profile_picture: str = ''
 
     def generate(
         self,
         prompts: List[str], 
         weights: List[float], 
-        width: int = 512, 
-        height: int = 512, 
+        width: int = 1024, 
+        height: int = 1024, 
         steps: Optional[int] = None,
         seed: Union[Sequence[int], int] = 0,
         samples: int = 1,
         cfg_scale: float = 7.0, 
         sampler: generation.DiffusionSampler = None,
         init_image: Optional[Image.Image] = None,
         init_strength: float = 0.0,
```

### Comparing `stability-sdk-0.8.1/src/stability_sdk/client.py` & `stability-sdk-0.8.2/src/stability_sdk/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -91,15 +91,15 @@
 
 
 class StabilityInference:
     def __init__(
         self,
         host: str = "grpc.stability.ai:443",
         key: str = "",
-        engine: str = "stable-diffusion-xl-beta-v2-2-2",
+        engine: str = "stable-diffusion-xl-1024-v0-9",
         upscale_engine: str = "esrgan-v1-x2plus",
         verbose: bool = False,
         wait_for_ready: bool = True,
     ):
         """
         Initialize the client.
 
@@ -151,16 +151,16 @@
         self.stub = generation_grpc.GenerationServiceStub(channel)
 
     def generate(
         self,
         prompt: Union[str, List[str], generation.Prompt, List[generation.Prompt]],
         init_image: Optional[Image.Image] = None,
         mask_image: Optional[Image.Image] = None,
-        height: int = 512,
-        width: int = 512,
+        height: int = 1024,
+        width: int = 1024,
         start_schedule: float = 1.0,
         end_schedule: float = 0.01,
         cfg_scale: float = 7.0,
         sampler: generation.DiffusionSampler = None,
         steps: Optional[int] = None,
         seed: Union[Sequence[int], int] = 0,
         samples: int = 1,
@@ -489,18 +489,18 @@
     parser_animate.add_argument("--gui", action="store_true", help="serve Gradio UI")
     parser_animate.add_argument("--share", action="store_true", help="create shareable UI link")
     parser_animate.add_argument("--output", "-o", type=str, default=".", help="root output folder")    
     
 
     parser_generate = subparsers.add_parser('generate')
     parser_generate.add_argument(
-        "--height", "-H", type=int, default=512, help="[512] height of image"
+        "--height", "-H", type=int, default=1024, help="[1024] height of image"
     )
     parser_generate.add_argument(
-        "--width", "-W", type=int, default=512, help="[512] width of image"
+        "--width", "-W", type=int, default=1024, help="[1024] width of image"
     )
     parser_generate.add_argument(
         "--start_schedule",
         type=float,
         default=0.5,
         help="[0.5] start schedule for init image (must be greater than 0, 1 is full strength text prompt, no trace of image)",
     )
@@ -546,15 +546,15 @@
     )
     parser_generate.add_argument("--show", action="store_true", help="open artifacts using PIL")
     parser_generate.add_argument(
         "--engine",
         "-e",
         type=str,
         help="engine to use for inference",
-        default="stable-diffusion-xl-beta-v2-2-2",
+        default="stable-diffusion-xl-1024-v0-9",
     )
     parser_generate.add_argument(
         "--init_image",
         "-i",
         type=str,
         help="Init image",
     )
```

### Comparing `stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/dashboard/dashboard_pb2.py` & `stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/dashboard/dashboard_pb2.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/dashboard/dashboard_pb2_grpc.py` & `stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/dashboard/dashboard_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/engines/engines_pb2.py` & `stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/engines/engines_pb2.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/engines/engines_pb2_grpc.py` & `stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/engines/engines_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/generation/generation_pb2.py` & `stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/generation/generation_pb2.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/generation/generation_pb2_grpc.py` & `stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/generation/generation_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/generation/tensors_pb2.py` & `stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/generation/tensors_pb2.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/project/project_pb2.py` & `stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/project/project_pb2.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/interfaces/gooseai/project/project_pb2_grpc.py` & `stability-sdk-0.8.2/src/stability_sdk/interfaces/gooseai/project/project_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/interfaces/src/tensorizer/protobuf.py` & `stability-sdk-0.8.2/src/stability_sdk/interfaces/src/tensorizer/protobuf.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/interfaces/src/tensorizer/tensorizer.py` & `stability-sdk-0.8.2/src/stability_sdk/interfaces/src/tensorizer/tensorizer.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/interfaces/src/tensorizer/tensors/tensors_pb2.py` & `stability-sdk-0.8.2/src/stability_sdk/interfaces/src/tensorizer/tensors/tensors_pb2.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/interfaces/src/tensorizer/test_protobuf.py` & `stability-sdk-0.8.2/src/stability_sdk/interfaces/src/tensorizer/test_protobuf.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/interfaces/src/tensorizer/test_tensorizer.py` & `stability-sdk-0.8.2/src/stability_sdk/interfaces/src/tensorizer/test_tensorizer.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/matrix.py` & `stability-sdk-0.8.2/src/stability_sdk/matrix.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk/utils.py` & `stability-sdk-0.8.2/src/stability_sdk/utils.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/src/stability_sdk.egg-info/PKG-INFO` & `stability-sdk-0.8.2/src/stability_sdk.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: stability-sdk
-Version: 0.8.1
+Version: 0.8.2
 Summary: Python SDK for interacting with stability.ai APIs
 Home-page: https://beta.dreamstudio.ai/
 Download-URL: https://github.com/Stability-AI/stability-sdk/
 Author: Stability AI
 Author-email: support@stability.ai
 Maintainer: Stability AI
 Maintainer-email: support@stability.ai
@@ -57,15 +57,15 @@
 - Set up in venv dependencies: `pyenv/bin/pip3 install -e .`
 - `pyenv/bin/activate` to use the venv.
 - Set the `STABILITY_HOST` environment variable. This is by default set to the production endpoint `grpc.stability.ai:443`.
 - Set the `STABILITY_KEY` environment variable.
 
 Then to invoke:
 
-`python3 -m stability_sdk generate -W 512 -H 512 "A stunning house."`
+`python3 -m stability_sdk generate -W 1024 -H 1024 "A stunning house."`
 
 It will generate and put PNGs in your current directory.
 
 To upscale:
 `python3 -m stability_sdk upscale -i "/path/to/image.png"`
 
 ## Animation UI
@@ -92,17 +92,17 @@
 
 positional arguments:
   prompt
 
 options:
   -h, --help            show this help message and exit
   --height HEIGHT, -H HEIGHT
-                        [512] height of image
+                        [1024] height of image
   --width WIDTH, -W WIDTH
-                        [512] width of image
+                        [1024] width of image
   --start_schedule START_SCHEDULE
                         [0.5] start schedule for init image (must be greater than 0; 1 is full strength
                         text prompt, no trace of image)
   --end_schedule END_SCHEDULE
                         [0.01] end schedule for init image
   --cfg_scale CFG_SCALE, -C CFG_SCALE
                         [7.0] CFG scale factor
```

### Comparing `stability-sdk-0.8.1/src/stability_sdk.egg-info/SOURCES.txt` & `stability-sdk-0.8.2/src/stability_sdk.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/tests/test_animator.py` & `stability-sdk-0.8.2/tests/test_animator.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/tests/test_api.py` & `stability-sdk-0.8.2/tests/test_api.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/tests/test_client.py` & `stability-sdk-0.8.2/tests/test_client.py`

 * *Files identical despite different names*

### Comparing `stability-sdk-0.8.1/tests/test_utils.py` & `stability-sdk-0.8.2/tests/test_utils.py`

 * *Files identical despite different names*


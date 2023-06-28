# Comparing `tmp/neptune_tensorboard-1.0.0rc3.tar.gz` & `tmp/neptune_tensorboard-1.0.0rc4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "neptune_tensorboard-1.0.0rc3.tar", max compression
+gzip compressed data, was "neptune_tensorboard-1.0.0rc4.tar", max compression
```

## Comparing `neptune_tensorboard-1.0.0rc3.tar` & `neptune_tensorboard-1.0.0rc4.tar`

### file list

```diff
@@ -1,14 +1,15 @@
--rw-r--r--   0        0        0      948 2023-06-23 07:20:38.059774 neptune_tensorboard-1.0.0rc3/CHANGELOG.md
--rw-r--r--   0        0        0    11357 2023-06-23 07:20:38.059774 neptune_tensorboard-1.0.0rc3/LICENSE
--rw-r--r--   0        0        0      111 2023-06-23 07:20:38.059774 neptune_tensorboard-1.0.0rc3/README.md
--rw-r--r--   0        0        0     2928 2023-06-23 07:20:54.616009 neptune_tensorboard-1.0.0rc3/pyproject.toml
--rw-r--r--   0        0        0      820 2023-06-23 07:20:38.059774 neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/__init__.py
--rw-r--r--   0        0        0     4964 2023-06-23 07:20:38.059774 neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/integration/__init__.py
--rw-r--r--   0        0        0     5671 2023-06-23 07:20:38.059774 neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/integration/pytorch_integration.py
--rw-r--r--   0        0        0     5728 2023-06-23 07:20:38.059774 neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/integration/tensorboardx_integration.py
--rw-r--r--   0        0        0     3606 2023-06-23 07:20:38.059774 neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/integration/tensorflow_integration.py
--rw-r--r--   0        0        0      292 2023-06-23 07:20:38.059774 neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/integration/utils.py
--rw-r--r--   0        0        0      760 2023-06-23 07:20:38.059774 neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/integration/version.py
--rw-r--r--   0        0        0       80 2023-06-23 07:20:38.059774 neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/sync/__init__.py
--rw-r--r--   0        0        0     3705 2023-06-23 07:20:38.059774 neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/sync/sync_impl.py
--rw-r--r--   0        0        0     2208 1970-01-01 00:00:00.000000 neptune_tensorboard-1.0.0rc3/PKG-INFO
+-rw-r--r--   0        0        0     1096 2023-06-23 09:48:37.904124 neptune_tensorboard-1.0.0rc4/CHANGELOG.md
+-rw-r--r--   0        0        0    11357 2023-06-23 09:48:37.904124 neptune_tensorboard-1.0.0rc4/LICENSE
+-rw-r--r--   0        0        0      111 2023-06-23 09:48:37.904124 neptune_tensorboard-1.0.0rc4/README.md
+-rw-r--r--   0        0        0     2990 2023-06-23 09:48:54.692382 neptune_tensorboard-1.0.0rc4/pyproject.toml
+-rw-r--r--   0        0        0      820 2023-06-23 09:48:37.904124 neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/__init__.py
+-rw-r--r--   0        0        0     4964 2023-06-23 09:48:37.904124 neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/integration/__init__.py
+-rw-r--r--   0        0        0     5671 2023-06-23 09:48:37.904124 neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/integration/pytorch_integration.py
+-rw-r--r--   0        0        0     5728 2023-06-23 09:48:37.904124 neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/integration/tensorboardx_integration.py
+-rw-r--r--   0        0        0     3606 2023-06-23 09:48:37.904124 neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/integration/tensorflow_integration.py
+-rw-r--r--   0        0        0      292 2023-06-23 09:48:37.904124 neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/integration/utils.py
+-rw-r--r--   0        0        0      760 2023-06-23 09:48:37.904124 neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/integration/version.py
+-rw-r--r--   0        0        0       80 2023-06-23 09:48:37.904124 neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/sync/__init__.py
+-rw-r--r--   0        0        0     3705 2023-06-23 09:48:37.904124 neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/sync/sync_impl.py
+-rw-r--r--   0        0        0      591 2023-06-23 09:48:37.904124 neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard_plugin/__init__.py
+-rw-r--r--   0        0        0     2208 1970-01-01 00:00:00.000000 neptune_tensorboard-1.0.0rc4/PKG-INFO
```

### Comparing `neptune_tensorboard-1.0.0rc3/CHANGELOG.md` & `neptune_tensorboard-1.0.0rc4/CHANGELOG.md`

 * *Files 26% similar despite different names*

```diff
@@ -1,7 +1,12 @@
+## neptune-tensorboard 1.0.0.pre4
+
+### Fixes
+- Export neptune plug-in correctly ([#62](https://github.com/neptune-ai/neptune-tensorboard/pull/62))
+
 ## neptune-tensorboard 1.0.0.pre3
 
 ### Changes
 - Add support to export existing Tensorboard logs via CLI plugin ([#59](https://github.com/neptune-ai/neptune-tensorboard/pull/59/))
 
 ## neptune-tensorboard 1.0.0.pre2
```

### Comparing `neptune_tensorboard-1.0.0rc3/LICENSE` & `neptune_tensorboard-1.0.0rc4/LICENSE`

 * *Files identical despite different names*

### Comparing `neptune_tensorboard-1.0.0rc3/pyproject.toml` & `neptune_tensorboard-1.0.0rc4/pyproject.toml`

 * *Files 6% similar despite different names*

```diff
@@ -42,15 +42,15 @@
 repository = "https://github.com/neptune-ai/neptune-tensorboard"
 homepage = "https://neptune.ai/"
 documentation = "https://docs.neptune.ai/integrations-and-supported-tools/model-training/tensorboard"
 include = ["CHANGELOG.md"]
 license = "Apache License 2.0"
 name = "neptune-tensorboard"
 readme = "README.md"
-version = "1.0.0-pre.3"
+version = "1.0.0-pre.4"
 classifiers = [
     "Development Status :: 4 - Beta",
     "Environment :: Console",
     "Intended Audience :: Developers",
     "Intended Audience :: Science/Research",
     "License :: OSI Approved :: Apache Software License",
     "Natural Language :: English",
@@ -67,14 +67,15 @@
     "ML Experiment Tracking",
     "ML Model Registry",
     "ML Model Store",
     "ML Metadata Store",
 ]
 packages = [
     { include = "neptune_tensorboard", from = "src" },
+    { include = "neptune_tensorboard_plugin", from = "src" },
 ]
 
 [tool.poetry.urls]
 "Tracker" = "https://github.com/neptune-ai/neptune-tensorboard/issues"
 "Documentation" = "https://docs.neptune.ai/integrations-and-supported-tools/model-training/tensorboard"
 
 [tool.black]
```

### Comparing `neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/__init__.py` & `neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/__init__.py`

 * *Files identical despite different names*

### Comparing `neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/integration/__init__.py` & `neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/integration/__init__.py`

 * *Files identical despite different names*

### Comparing `neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/integration/pytorch_integration.py` & `neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/integration/pytorch_integration.py`

 * *Files identical despite different names*

### Comparing `neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/integration/tensorboardx_integration.py` & `neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/integration/tensorboardx_integration.py`

 * *Files identical despite different names*

### Comparing `neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/integration/tensorflow_integration.py` & `neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/integration/tensorflow_integration.py`

 * *Files identical despite different names*

### Comparing `neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/integration/version.py` & `neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/integration/version.py`

 * *Files identical despite different names*

### Comparing `neptune_tensorboard-1.0.0rc3/src/neptune_tensorboard/sync/sync_impl.py` & `neptune_tensorboard-1.0.0rc4/src/neptune_tensorboard/sync/sync_impl.py`

 * *Files identical despite different names*

### Comparing `neptune_tensorboard-1.0.0rc3/PKG-INFO` & `neptune_tensorboard-1.0.0rc4/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: neptune-tensorboard
-Version: 1.0.0rc3
+Version: 1.0.0rc4
 Summary: Neptune.ai Tensorboard integration library
 Home-page: https://neptune.ai/
 License: Apache-2.0
 Keywords: MLOps,ML Experiment Tracking,ML Model Registry,ML Model Store,ML Metadata Store
 Author: neptune.ai
 Author-email: contact@neptune.ai
 Requires-Python: >=3.7,<4.0
```


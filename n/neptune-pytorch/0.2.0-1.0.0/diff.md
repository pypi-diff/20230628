# Comparing `tmp/neptune_pytorch-0.2.0.tar.gz` & `tmp/neptune_pytorch-1.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "neptune_pytorch-0.2.0.tar", max compression
+gzip compressed data, was "neptune_pytorch-1.0.0.tar", max compression
```

## Comparing `neptune_pytorch-0.2.0.tar` & `neptune_pytorch-1.0.0.tar`

### file list

```diff
@@ -1,8 +1,8 @@
--rw-r--r--   0        0        0      580 2023-05-05 19:12:40.043735 neptune_pytorch-0.2.0/CHANGELOG.md
--rw-r--r--   0        0        0    11357 2023-05-05 19:12:40.043735 neptune_pytorch-0.2.0/LICENSE
--rw-r--r--   0        0        0      132 2023-05-05 19:12:40.043735 neptune_pytorch-0.2.0/README.md
--rw-r--r--   0        0        0     2565 2023-05-05 19:12:55.616240 neptune_pytorch-0.2.0/pyproject.toml
--rw-r--r--   0        0        0      724 2023-05-05 19:12:40.043735 neptune_pytorch-0.2.0/src/neptune_pytorch/__init__.py
--rw-r--r--   0        0        0     8984 2023-05-05 19:12:40.043735 neptune_pytorch-0.2.0/src/neptune_pytorch/impl/__init__.py
--rw-r--r--   0        0        0      738 2023-05-05 19:12:40.043735 neptune_pytorch-0.2.0/src/neptune_pytorch/impl/version.py
--rw-r--r--   0        0        0     2078 1970-01-01 00:00:00.000000 neptune_pytorch-0.2.0/PKG-INFO
+-rw-r--r--   0        0        0     1115 2023-06-28 09:21:18.678046 neptune_pytorch-1.0.0/CHANGELOG.md
+-rw-r--r--   0        0        0    11357 2023-06-28 09:21:18.678046 neptune_pytorch-1.0.0/LICENSE
+-rw-r--r--   0        0        0      132 2023-06-28 09:21:18.678046 neptune_pytorch-1.0.0/README.md
+-rw-r--r--   0        0        0     2565 2023-06-28 09:21:29.902198 neptune_pytorch-1.0.0/pyproject.toml
+-rw-r--r--   0        0        0      724 2023-06-28 09:21:18.678046 neptune_pytorch-1.0.0/src/neptune_pytorch/__init__.py
+-rw-r--r--   0        0        0     8984 2023-06-28 09:21:18.678046 neptune_pytorch-1.0.0/src/neptune_pytorch/impl/__init__.py
+-rw-r--r--   0        0        0      738 2023-06-28 09:21:18.678046 neptune_pytorch-1.0.0/src/neptune_pytorch/impl/version.py
+-rw-r--r--   0        0        0     2078 1970-01-01 00:00:00.000000 neptune_pytorch-1.0.0/PKG-INFO
```

### Comparing `neptune_pytorch-0.2.0/LICENSE` & `neptune_pytorch-1.0.0/LICENSE`

 * *Files identical despite different names*

### Comparing `neptune_pytorch-0.2.0/pyproject.toml` & `neptune_pytorch-1.0.0/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -39,15 +39,15 @@
 repository = "https://github.com/neptune-ai/neptune-pytorch"
 homepage = "https://neptune.ai/"
 documentation = "https://docs.neptune.ai/integrations-and-supported-tools/model-training/pytorch"
 include = ["CHANGELOG.md"]
 license = "Apache License 2.0"
 name = "neptune-pytorch"
 readme = "README.md"
-version = "0.2.0"
+version = "1.0.0"
 classifiers = [
     "Development Status :: 4 - Beta",
     "Environment :: Console",
     "Intended Audience :: Developers",
     "Intended Audience :: Science/Research",
     "License :: OSI Approved :: Apache Software License",
     "Natural Language :: English",
```

### Comparing `neptune_pytorch-0.2.0/src/neptune_pytorch/__init__.py` & `neptune_pytorch-1.0.0/src/neptune_pytorch/__init__.py`

 * *Files identical despite different names*

### Comparing `neptune_pytorch-0.2.0/src/neptune_pytorch/impl/__init__.py` & `neptune_pytorch-1.0.0/src/neptune_pytorch/impl/__init__.py`

 * *Files identical despite different names*

### Comparing `neptune_pytorch-0.2.0/src/neptune_pytorch/impl/version.py` & `neptune_pytorch-1.0.0/src/neptune_pytorch/impl/version.py`

 * *Files identical despite different names*

### Comparing `neptune_pytorch-0.2.0/PKG-INFO` & `neptune_pytorch-1.0.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: neptune-pytorch
-Version: 0.2.0
+Version: 1.0.0
 Summary: Neptune.ai pytorch integration library
 Home-page: https://neptune.ai/
 License: Apache-2.0
 Keywords: MLOps,ML Experiment Tracking,ML Model Registry,ML Model Store,ML Metadata Store
 Author: neptune.ai
 Author-email: contact@neptune.ai
 Requires-Python: >=3.7,<4.0
```


# Comparing `tmp/underthesea_core-1.0.1-cp39-none-win_amd64.whl.zip` & `tmp/underthesea_core-1.0.2-cp39-none-win_amd64.whl.zip`

## zipinfo {}

```diff
@@ -1,6 +1,6 @@
-Zip file size: 547388 bytes, number of entries: 4
--rw-r--r--  4.6 unx     1707 b- defN 23-Jun-07 08:11 underthesea_core-1.0.1.dist-info/METADATA
--rw-r--r--  4.6 unx       94 b- defN 23-Jun-07 08:11 underthesea_core-1.0.1.dist-info/WHEEL
--rwxr-xr-x  4.6 unx  1478144 b- defN 23-Jun-07 08:11 underthesea_core.cp39-win_amd64.pyd
--rw-r--r--  4.6 unx      328 b- defN 23-Jun-07 08:11 underthesea_core-1.0.1.dist-info/RECORD
-4 files, 1480273 bytes uncompressed, 546750 bytes compressed:  63.1%
+Zip file size: 553220 bytes, number of entries: 4
+-rw-r--r--  4.6 unx     1758 b- defN 23-Jun-28 07:17 underthesea_core-1.0.2.dist-info/METADATA
+-rw-r--r--  4.6 unx       94 b- defN 23-Jun-28 07:17 underthesea_core-1.0.2.dist-info/WHEEL
+-rwxr-xr-x  4.6 unx  1498112 b- defN 23-Jun-28 07:17 underthesea_core.cp39-win_amd64.pyd
+-rw-r--r--  4.6 unx      328 b- defN 23-Jun-28 07:17 underthesea_core-1.0.2.dist-info/RECORD
+4 files, 1500292 bytes uncompressed, 552582 bytes compressed:  63.2%
```

## zipnote {}

```diff
@@ -1,13 +1,13 @@
-Filename: underthesea_core-1.0.1.dist-info/METADATA
+Filename: underthesea_core-1.0.2.dist-info/METADATA
 Comment: 
 
-Filename: underthesea_core-1.0.1.dist-info/WHEEL
+Filename: underthesea_core-1.0.2.dist-info/WHEEL
 Comment: 
 
 Filename: underthesea_core.cp39-win_amd64.pyd
 Comment: 
 
-Filename: underthesea_core-1.0.1.dist-info/RECORD
+Filename: underthesea_core-1.0.2.dist-info/RECORD
 Comment: 
 
 Zip file comment: zip-rs
```

## Comparing `underthesea_core-1.0.1.dist-info/METADATA` & `underthesea_core-1.0.2.dist-info/METADATA`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: underthesea_core
-Version: 1.0.1
+Version: 1.0.2
 Summary: Underthesea Core
 Home-Page: https://github.com/undertheseanlp/underthesea/tree/main/extensions/underthesea_core
 Author: Vu Anh <anhv.ict91@gmail.com>
 Author-Email: Vu Anh <anhv.ict91@gmail.com>
 License: GPL-3.0
 Description-Content-Type: text/markdown; charset=UTF-8; variant=GFM
 
@@ -31,8 +31,9 @@
 
 ## Release Workflow
 
 1. Change version in `Cargo.toml` and `pyproject.toml`
 2. Push to branch `core` with commit `Publish Underthesea Core`
   * This will trigger `release-pypi-core` action
 3. Check latest version in [pypi](https://pypi.org/project/underthesea_core/)
-
+
+Note*: Run a self-hosted for building `macos-arm`
```


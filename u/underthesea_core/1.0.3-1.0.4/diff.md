# Comparing `tmp/underthesea_core-1.0.3-cp39-none-win_amd64.whl.zip` & `tmp/underthesea_core-1.0.4-cp39-cp39-macosx_10_7_x86_64.whl.zip`

## zipinfo {}

```diff
@@ -1,6 +1,6 @@
-Zip file size: 553228 bytes, number of entries: 4
--rw-r--r--  4.6 unx     1758 b- defN 23-Jun-28 07:50 underthesea_core-1.0.3.dist-info/METADATA
--rw-r--r--  4.6 unx       94 b- defN 23-Jun-28 07:50 underthesea_core-1.0.3.dist-info/WHEEL
--rwxr-xr-x  4.6 unx  1498112 b- defN 23-Jun-28 07:50 underthesea_core.cp39-win_amd64.pyd
--rw-r--r--  4.6 unx      328 b- defN 23-Jun-28 07:50 underthesea_core-1.0.3.dist-info/RECORD
-4 files, 1500292 bytes uncompressed, 552590 bytes compressed:  63.2%
+Zip file size: 601573 bytes, number of entries: 4
+-rw-r--r--  4.6 unx     1730 b- defN 23-Jun-28 08:33 underthesea_core-1.0.4.dist-info/METADATA
+-rw-r--r--  4.6 unx      103 b- defN 23-Jun-28 08:33 underthesea_core-1.0.4.dist-info/WHEEL
+-rwxr-xr-x  4.6 unx  1536064 b- defN 23-Jun-28 08:33 underthesea_core.cpython-39-darwin.so
+-rw-r--r--  4.6 unx      331 b- defN 23-Jun-28 08:33 underthesea_core-1.0.4.dist-info/RECORD
+4 files, 1538228 bytes uncompressed, 600931 bytes compressed:  60.9%
```

## zipnote {}

```diff
@@ -1,13 +1,13 @@
-Filename: underthesea_core-1.0.3.dist-info/METADATA
+Filename: underthesea_core-1.0.4.dist-info/METADATA
 Comment: 
 
-Filename: underthesea_core-1.0.3.dist-info/WHEEL
+Filename: underthesea_core-1.0.4.dist-info/WHEEL
 Comment: 
 
-Filename: underthesea_core.cp39-win_amd64.pyd
+Filename: underthesea_core.cpython-39-darwin.so
 Comment: 
 
-Filename: underthesea_core-1.0.3.dist-info/RECORD
+Filename: underthesea_core-1.0.4.dist-info/RECORD
 Comment: 
 
 Zip file comment: zip-rs
```

## Comparing `underthesea_core-1.0.3.dist-info/METADATA` & `underthesea_core-1.0.4.dist-info/METADATA`

 * *Files 19% similar despite different names*

```diff
@@ -1,39 +1,39 @@
 Metadata-Version: 2.1
 Name: underthesea_core
-Version: 1.0.3
+Version: 1.0.4
 Summary: Underthesea Core
 Home-Page: https://github.com/undertheseanlp/underthesea/tree/main/extensions/underthesea_core
 Author: Vu Anh <anhv.ict91@gmail.com>
 Author-Email: Vu Anh <anhv.ict91@gmail.com>
 License: GPL-3.0
 Description-Content-Type: text/markdown; charset=UTF-8; variant=GFM
 
-# Underthesea Core
-
-Underthesea Core is a powerful extension of the popular natural language processing library Underthesea, which includes a range of efficient data preprocessing tools and machine learning models for training. Built with Rust for optimal performance, Underthesea Core offers fast processing speeds and is easy to implement, with Python bindings for seamless integration into existing projects. This extension is an essential tool for developers looking to build high-performance NLP systems that deliver accurate and reliable results.
-
-## Usage
-
-CRFFeaturizer
-
-```python
->>> from underthesea_core import CRFFeaturizer
->>> features = ["T[-1]", "T[0]", "T[1]"]
->>> dictionary = set(["sinh viên"])
->>> featurizer = CRFFeaturizer(features, dictionary)
->>> sentences = [[["sinh", "X"], ["viên", "X"], ["đi", "X"], ["học", "X"]]]
->>> featurizer.process(sentences)
-[[['T[-1]=BOS', 'T[0]=sinh', 'T[1]=viên'],
-  ['T[-1]=sinh', 'T[0]=viên', 'T[1]=đi'],
-  ['T[-1]=viên', 'T[0]=đi', 'T[1]=học'],
-  ['T[-1]=đi', 'T[0]=học', 'T[1]=EOS']]]
-```
-
-## Release Workflow
-
-1. Change version in `Cargo.toml` and `pyproject.toml`
-2. Push to branch `core` with commit `Publish Underthesea Core`
-  * This will trigger `release-pypi-core` action
-3. Check latest version in [pypi](https://pypi.org/project/underthesea_core/)
-
+# Underthesea Core
+
+Underthesea Core is a powerful extension of the popular natural language processing library Underthesea, which includes a range of efficient data preprocessing tools and machine learning models for training. Built with Rust for optimal performance, Underthesea Core offers fast processing speeds and is easy to implement, with Python bindings for seamless integration into existing projects. This extension is an essential tool for developers looking to build high-performance NLP systems that deliver accurate and reliable results.
+
+## Usage
+
+CRFFeaturizer
+
+```python
+>>> from underthesea_core import CRFFeaturizer
+>>> features = ["T[-1]", "T[0]", "T[1]"]
+>>> dictionary = set(["sinh viên"])
+>>> featurizer = CRFFeaturizer(features, dictionary)
+>>> sentences = [[["sinh", "X"], ["viên", "X"], ["đi", "X"], ["học", "X"]]]
+>>> featurizer.process(sentences)
+[[['T[-1]=BOS', 'T[0]=sinh', 'T[1]=viên'],
+  ['T[-1]=sinh', 'T[0]=viên', 'T[1]=đi'],
+  ['T[-1]=viên', 'T[0]=đi', 'T[1]=học'],
+  ['T[-1]=đi', 'T[0]=học', 'T[1]=EOS']]]
+```
+
+## Release Workflow
+
+1. Change version in `Cargo.toml` and `pyproject.toml`
+2. Push to branch `core` with commit `Publish Underthesea Core`
+  * This will trigger `release-pypi-core` action
+3. Check latest version in [pypi](https://pypi.org/project/underthesea_core/)
+
 Note*: Run a self-hosted for building `macos-arm`
```


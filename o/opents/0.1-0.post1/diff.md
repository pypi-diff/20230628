# Comparing `tmp/opents-0.1-py3-none-any.whl.zip` & `tmp/opents-0.post1-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,6 +1,15 @@
-Zip file size: 971 bytes, number of entries: 4
--rw-rw-r--  2.0 unx      144 b- defN 23-May-27 15:23 opents-0.1.dist-info/METADATA
--rw-rw-r--  2.0 unx       92 b- defN 23-May-27 15:23 opents-0.1.dist-info/WHEEL
--rw-rw-r--  2.0 unx        1 b- defN 23-May-27 15:23 opents-0.1.dist-info/top_level.txt
-?rw-rw-r--  2.0 unx      284 b- defN 23-May-27 15:23 opents-0.1.dist-info/RECORD
-4 files, 521 bytes uncompressed, 413 bytes compressed:  20.7%
+Zip file size: 8701 bytes, number of entries: 13
+-rw-rw-r--  2.0 unx       54 b- defN 23-Jun-20 07:42 opents/__init__.py
+-rw-rw-r--  2.0 unx       14 b- defN 23-Jun-20 07:42 opents/data/__init__.py
+-rw-rw-r--  2.0 unx     9063 b- defN 23-Jun-28 02:05 opents/data/datasets.py
+-rw-rw-r--  2.0 unx     6306 b- defN 23-Jun-20 13:04 opents/data/generate_datasets.py
+-rw-rw-r--  2.0 unx     3658 b- defN 23-Jun-20 11:58 opents/data/new_ucr.py
+-rw-rw-r--  2.0 unx        0 b- defN 23-May-28 15:32 opents/datasets/__init__.py
+-rw-rw-r--  2.0 unx     3133 b- defN 23-Jun-20 09:11 opents/datasets/ucr.py
+-rw-rw-r--  2.0 unx        0 b- defN 23-May-28 15:32 opents/nn/__init__.py
+-rw-rw-r--  2.0 unx        0 b- defN 23-May-28 15:32 opents/utils/__init__.py
+-rw-rw-r--  2.0 unx     1927 b- defN 23-Jun-28 04:29 opents-0.post1.dist-info/METADATA
+-rw-rw-r--  2.0 unx       92 b- defN 23-Jun-28 04:29 opents-0.post1.dist-info/WHEEL
+-rw-rw-r--  2.0 unx        7 b- defN 23-Jun-28 04:29 opents-0.post1.dist-info/top_level.txt
+?rw-rw-r--  2.0 unx     1013 b- defN 23-Jun-28 04:29 opents-0.post1.dist-info/RECORD
+13 files, 25267 bytes uncompressed, 7003 bytes compressed:  72.3%
```

## zipnote {}

```diff
@@ -1,13 +1,40 @@
-Filename: opents-0.1.dist-info/METADATA
+Filename: opents/__init__.py
 Comment: 
 
-Filename: opents-0.1.dist-info/WHEEL
+Filename: opents/data/__init__.py
 Comment: 
 
-Filename: opents-0.1.dist-info/top_level.txt
+Filename: opents/data/datasets.py
 Comment: 
 
-Filename: opents-0.1.dist-info/RECORD
+Filename: opents/data/generate_datasets.py
+Comment: 
+
+Filename: opents/data/new_ucr.py
+Comment: 
+
+Filename: opents/datasets/__init__.py
+Comment: 
+
+Filename: opents/datasets/ucr.py
+Comment: 
+
+Filename: opents/nn/__init__.py
+Comment: 
+
+Filename: opents/utils/__init__.py
+Comment: 
+
+Filename: opents-0.post1.dist-info/METADATA
+Comment: 
+
+Filename: opents-0.post1.dist-info/WHEEL
+Comment: 
+
+Filename: opents-0.post1.dist-info/top_level.txt
+Comment: 
+
+Filename: opents-0.post1.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```


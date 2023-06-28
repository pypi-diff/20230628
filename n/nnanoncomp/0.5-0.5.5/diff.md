# Comparing `tmp/nnanoncomp-0.5-py3-none-any.whl.zip` & `tmp/nnanoncomp-0.5.5-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,8 +1,10 @@
-Zip file size: 2035 bytes, number of entries: 6
--rw-r--r--  2.0 unx        0 b- defN 23-Jun-28 08:42 anon_comp_core/__init__.py
--rw-r--r--  2.0 unx     1818 b- defN 23-Jun-28 08:42 anon_comp_core/anonymization.py
--rw-r--r--  2.0 unx      168 b- defN 23-Jun-28 08:42 nnanoncomp-0.5.dist-info/METADATA
--rw-r--r--  2.0 unx       92 b- defN 23-Jun-28 08:42 nnanoncomp-0.5.dist-info/WHEEL
--rw-r--r--  2.0 unx       15 b- defN 23-Jun-28 08:42 nnanoncomp-0.5.dist-info/top_level.txt
-?rw-rw-r--  2.0 unx      469 b- defN 23-Jun-28 08:42 nnanoncomp-0.5.dist-info/RECORD
-6 files, 2562 bytes uncompressed, 1179 bytes compressed:  54.0%
+Zip file size: 2941 bytes, number of entries: 8
+-rw-r--r--  2.0 unx        0 b- defN 23-Jun-28 09:28 anon_comp_core/__init__.py
+-rw-r--r--  2.0 unx     1818 b- defN 23-Jun-28 09:28 anon_comp_core/anonymization.py
+-rw-r--r--  2.0 unx        0 b- defN 23-Jun-28 09:28 specific/Libraries/__init__.py
+-rw-r--r--  2.0 unx     1325 b- defN 23-Jun-28 09:28 specific/Libraries/anonymization_transformations.py
+-rw-r--r--  2.0 unx      170 b- defN 23-Jun-28 09:28 nnanoncomp-0.5.5.dist-info/METADATA
+-rw-r--r--  2.0 unx       92 b- defN 23-Jun-28 09:28 nnanoncomp-0.5.5.dist-info/WHEEL
+-rw-r--r--  2.0 unx       24 b- defN 23-Jun-28 09:28 nnanoncomp-0.5.5.dist-info/top_level.txt
+?rw-rw-r--  2.0 unx      669 b- defN 23-Jun-28 09:28 nnanoncomp-0.5.5.dist-info/RECORD
+8 files, 4098 bytes uncompressed, 1755 bytes compressed:  57.2%
```

## zipnote {}

```diff
@@ -1,19 +1,25 @@
 Filename: anon_comp_core/__init__.py
 Comment: 
 
 Filename: anon_comp_core/anonymization.py
 Comment: 
 
-Filename: nnanoncomp-0.5.dist-info/METADATA
+Filename: specific/Libraries/__init__.py
 Comment: 
 
-Filename: nnanoncomp-0.5.dist-info/WHEEL
+Filename: specific/Libraries/anonymization_transformations.py
 Comment: 
 
-Filename: nnanoncomp-0.5.dist-info/top_level.txt
+Filename: nnanoncomp-0.5.5.dist-info/METADATA
 Comment: 
 
-Filename: nnanoncomp-0.5.dist-info/RECORD
+Filename: nnanoncomp-0.5.5.dist-info/WHEEL
+Comment: 
+
+Filename: nnanoncomp-0.5.5.dist-info/top_level.txt
+Comment: 
+
+Filename: nnanoncomp-0.5.5.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```


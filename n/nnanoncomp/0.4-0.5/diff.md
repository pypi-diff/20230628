# Comparing `tmp/nnanoncomp-0.4-py3-none-any.whl.zip` & `tmp/nnanoncomp-0.5-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,9 +1,8 @@
-Zip file size: 2742 bytes, number of entries: 7
--rw-r--r--  2.0 unx        0 b- defN 23-Jun-27 16:48 anon_comp_core/__init__.py
--rw-r--r--  2.0 unx     1812 b- defN 23-Jun-27 16:48 anon_comp_core/anonymization.py
--rw-r--r--  2.0 unx     1325 b- defN 23-Jun-27 16:48 anon_comp_core/anonymization_transformations.py
--rw-r--r--  2.0 unx      168 b- defN 23-Jun-27 16:48 nnanoncomp-0.4.dist-info/METADATA
--rw-r--r--  2.0 unx       92 b- defN 23-Jun-27 16:48 nnanoncomp-0.4.dist-info/WHEEL
--rw-r--r--  2.0 unx       15 b- defN 23-Jun-27 16:48 nnanoncomp-0.4.dist-info/top_level.txt
-?rw-rw-r--  2.0 unx      573 b- defN 23-Jun-27 16:48 nnanoncomp-0.4.dist-info/RECORD
-7 files, 3985 bytes uncompressed, 1716 bytes compressed:  56.9%
+Zip file size: 2035 bytes, number of entries: 6
+-rw-r--r--  2.0 unx        0 b- defN 23-Jun-28 08:42 anon_comp_core/__init__.py
+-rw-r--r--  2.0 unx     1818 b- defN 23-Jun-28 08:42 anon_comp_core/anonymization.py
+-rw-r--r--  2.0 unx      168 b- defN 23-Jun-28 08:42 nnanoncomp-0.5.dist-info/METADATA
+-rw-r--r--  2.0 unx       92 b- defN 23-Jun-28 08:42 nnanoncomp-0.5.dist-info/WHEEL
+-rw-r--r--  2.0 unx       15 b- defN 23-Jun-28 08:42 nnanoncomp-0.5.dist-info/top_level.txt
+?rw-rw-r--  2.0 unx      469 b- defN 23-Jun-28 08:42 nnanoncomp-0.5.dist-info/RECORD
+6 files, 2562 bytes uncompressed, 1179 bytes compressed:  54.0%
```

## zipnote {}

```diff
@@ -1,22 +1,19 @@
 Filename: anon_comp_core/__init__.py
 Comment: 
 
 Filename: anon_comp_core/anonymization.py
 Comment: 
 
-Filename: anon_comp_core/anonymization_transformations.py
+Filename: nnanoncomp-0.5.dist-info/METADATA
 Comment: 
 
-Filename: nnanoncomp-0.4.dist-info/METADATA
+Filename: nnanoncomp-0.5.dist-info/WHEEL
 Comment: 
 
-Filename: nnanoncomp-0.4.dist-info/WHEEL
+Filename: nnanoncomp-0.5.dist-info/top_level.txt
 Comment: 
 
-Filename: nnanoncomp-0.4.dist-info/top_level.txt
-Comment: 
-
-Filename: nnanoncomp-0.4.dist-info/RECORD
+Filename: nnanoncomp-0.5.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## anon_comp_core/anonymization.py

```diff
@@ -1,14 +1,16 @@
 from pyspark.sql.streaming import StreamingQuery
 from pyspark.sql.types import StructType, StringType
 from pyspark.sql import SparkSession
 
 from pyspark.ml.feature import Bucketizer
 
-from anon_comp_core.anonymization_transformations import Transformations
+from specific.Libraries.anonymization_transformations import Transformations
+
+
 
 class BaseTable():
     def __init__(
         self,
         data_path: str,
         legal_table_name: str,
         checkpoint_path: str,
```


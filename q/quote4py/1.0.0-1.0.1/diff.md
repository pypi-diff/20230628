# Comparing `tmp/quote4py-1.0.0-py3-none-any.whl.zip` & `tmp/quote4py-1.0.1-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,9 +1,10 @@
-Zip file size: 2140 bytes, number of entries: 7
--rw-rw-r--  2.0 unx       56 b- defN 23-Jun-28 07:16 quote/__init__.py
+Zip file size: 2480 bytes, number of entries: 8
+-rw-rw-r--  2.0 unx       47 b- defN 23-Jun-28 08:25 quote/__init__.py
+-rw-rw-r--  2.0 unx      312 b- defN 23-Jun-28 08:25 quote/main.py
 -rw-rw-r--  2.0 unx      320 b- defN 23-Jun-28 07:15 quote/quote.py
 -rw-rw-r--  2.0 unx      857 b- defN 23-Jun-28 07:15 quote/quotes.txt
--rw-rw-r--  2.0 unx      124 b- defN 23-Jun-28 08:10 quote4py-1.0.0.dist-info/METADATA
--rw-rw-r--  2.0 unx       92 b- defN 23-Jun-28 08:10 quote4py-1.0.0.dist-info/WHEEL
--rw-rw-r--  2.0 unx        6 b- defN 23-Jun-28 08:10 quote4py-1.0.0.dist-info/top_level.txt
--rw-rw-r--  2.0 unx      514 b- defN 23-Jun-28 08:10 quote4py-1.0.0.dist-info/RECORD
-7 files, 1969 bytes uncompressed, 1228 bytes compressed:  37.6%
+-rw-rw-r--  2.0 unx      124 b- defN 23-Jun-28 08:45 quote4py-1.0.1.dist-info/METADATA
+-rw-rw-r--  2.0 unx       92 b- defN 23-Jun-28 08:45 quote4py-1.0.1.dist-info/WHEEL
+-rw-rw-r--  2.0 unx        6 b- defN 23-Jun-28 08:45 quote4py-1.0.1.dist-info/top_level.txt
+-rw-rw-r--  2.0 unx      583 b- defN 23-Jun-28 08:45 quote4py-1.0.1.dist-info/RECORD
+8 files, 2341 bytes uncompressed, 1466 bytes compressed:  37.4%
```

## zipnote {}

```diff
@@ -1,22 +1,25 @@
 Filename: quote/__init__.py
 Comment: 
 
+Filename: quote/main.py
+Comment: 
+
 Filename: quote/quote.py
 Comment: 
 
 Filename: quote/quotes.txt
 Comment: 
 
-Filename: quote4py-1.0.0.dist-info/METADATA
+Filename: quote4py-1.0.1.dist-info/METADATA
 Comment: 
 
-Filename: quote4py-1.0.0.dist-info/WHEEL
+Filename: quote4py-1.0.1.dist-info/WHEEL
 Comment: 
 
-Filename: quote4py-1.0.0.dist-info/top_level.txt
+Filename: quote4py-1.0.1.dist-info/top_level.txt
 Comment: 
 
-Filename: quote4py-1.0.0.dist-info/RECORD
+Filename: quote4py-1.0.1.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## quote/__init__.py

```diff
@@ -1,5 +1,5 @@
-from quote.quote import quote
+from quote.main import q
 
 __all__ = [
-    'quote'
+    'q'
 ]
```


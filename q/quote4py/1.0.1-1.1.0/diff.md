# Comparing `tmp/quote4py-1.0.1-py3-none-any.whl.zip` & `tmp/quote4py-1.1.0-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,10 +1,11 @@
-Zip file size: 2480 bytes, number of entries: 8
--rw-rw-r--  2.0 unx       47 b- defN 23-Jun-28 08:25 quote/__init__.py
--rw-rw-r--  2.0 unx      312 b- defN 23-Jun-28 08:25 quote/main.py
+Zip file size: 2776 bytes, number of entries: 9
+-rw-rw-r--  2.0 unx       58 b- defN 23-Jun-28 09:08 quote/__init__.py
+-rw-rw-r--  2.0 unx      434 b- defN 23-Jun-28 09:09 quote/main.py
 -rw-rw-r--  2.0 unx      320 b- defN 23-Jun-28 07:15 quote/quote.py
 -rw-rw-r--  2.0 unx      857 b- defN 23-Jun-28 07:15 quote/quotes.txt
--rw-rw-r--  2.0 unx      124 b- defN 23-Jun-28 08:45 quote4py-1.0.1.dist-info/METADATA
--rw-rw-r--  2.0 unx       92 b- defN 23-Jun-28 08:45 quote4py-1.0.1.dist-info/WHEEL
--rw-rw-r--  2.0 unx        6 b- defN 23-Jun-28 08:45 quote4py-1.0.1.dist-info/top_level.txt
--rw-rw-r--  2.0 unx      583 b- defN 23-Jun-28 08:45 quote4py-1.0.1.dist-info/RECORD
-8 files, 2341 bytes uncompressed, 1466 bytes compressed:  37.4%
+-rw-rw-r--  2.0 unx      125 b- defN 23-Jun-28 09:07 quote/sorry.txt
+-rw-rw-r--  2.0 unx      120 b- defN 23-Jun-28 09:21 quote4py-1.1.0.dist-info/METADATA
+-rw-rw-r--  2.0 unx       92 b- defN 23-Jun-28 09:21 quote4py-1.1.0.dist-info/WHEEL
+-rw-rw-r--  2.0 unx        6 b- defN 23-Jun-28 09:21 quote4py-1.1.0.dist-info/top_level.txt
+-rw-rw-r--  2.0 unx      654 b- defN 23-Jun-28 09:21 quote4py-1.1.0.dist-info/RECORD
+9 files, 2666 bytes uncompressed, 1656 bytes compressed:  37.9%
```

## zipnote {}

```diff
@@ -6,20 +6,23 @@
 
 Filename: quote/quote.py
 Comment: 
 
 Filename: quote/quotes.txt
 Comment: 
 
-Filename: quote4py-1.0.1.dist-info/METADATA
+Filename: quote/sorry.txt
 Comment: 
 
-Filename: quote4py-1.0.1.dist-info/WHEEL
+Filename: quote4py-1.1.0.dist-info/METADATA
 Comment: 
 
-Filename: quote4py-1.0.1.dist-info/top_level.txt
+Filename: quote4py-1.1.0.dist-info/WHEEL
 Comment: 
 
-Filename: quote4py-1.0.1.dist-info/RECORD
+Filename: quote4py-1.1.0.dist-info/top_level.txt
+Comment: 
+
+Filename: quote4py-1.1.0.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## quote/__init__.py

```diff
@@ -1,5 +1,6 @@
-from quote.main import q
+from quote.main import q,x
 
 __all__ = [
-    'q'
+    "q",
+    "x"
 ]
```

## quote/main.py

```diff
@@ -1,14 +1,19 @@
 import os
 import random
 
-def q():
-    module_dir = os.path.dirname(__file__)
+module_dir = os.path.dirname(__file__)
 
+def q():
     with open(os.path.join(module_dir, "quotes.txt"), "r") as file:
         lines = file.readlines()
 
     new_lines = [s for s in lines if s.strip() != ""]
     return random.choice(new_lines)
 
+def x():
+    with open(os.path.join(module_dir, "sorry.txt"), "r") as file:
+        content = file.read()
+    return content
+
 if __name__ == "__main__":
-    print(q())
+    print(x())
```


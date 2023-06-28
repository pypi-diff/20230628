# Comparing `tmp/quote4py-1.1.1-py3-none-any.whl.zip` & `tmp/quote4py-1.1.2-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,11 +1,11 @@
-Zip file size: 2735 bytes, number of entries: 9
--rw-rw-r--  2.0 unx       58 b- defN 23-Jun-28 09:08 quote/__init__.py
--rw-rw-r--  2.0 unx      434 b- defN 23-Jun-28 09:09 quote/main.py
--rw-rw-r--  2.0 unx      320 b- defN 23-Jun-28 07:15 quote/quote.py
--rw-rw-r--  2.0 unx      857 b- defN 23-Jun-28 07:15 quote/quotes.txt
--rw-rw-r--  2.0 unx       76 b- defN 23-Jun-28 09:24 quote/sorry.txt
--rw-rw-r--  2.0 unx      120 b- defN 23-Jun-28 09:25 quote4py-1.1.1.dist-info/METADATA
--rw-rw-r--  2.0 unx       92 b- defN 23-Jun-28 09:25 quote4py-1.1.1.dist-info/WHEEL
--rw-rw-r--  2.0 unx        6 b- defN 23-Jun-28 09:25 quote4py-1.1.1.dist-info/top_level.txt
--rw-rw-r--  2.0 unx      653 b- defN 23-Jun-28 09:25 quote4py-1.1.1.dist-info/RECORD
-9 files, 2616 bytes uncompressed, 1615 bytes compressed:  38.3%
+Zip file size: 2761 bytes, number of entries: 9
+-rw-rw-r--  2.0 unx       58 b- defN 23-Jun-28 09:27 quote/__init__.py
+-rw-rw-r--  2.0 unx      462 b- defN 23-Jun-28 09:49 quote/main.py
+-rw-rw-r--  2.0 unx      320 b- defN 23-Jun-28 09:27 quote/quote.py
+-rw-rw-r--  2.0 unx      857 b- defN 23-Jun-28 09:27 quote/quotes.txt
+-rw-rw-r--  2.0 unx       76 b- defN 23-Jun-28 09:27 quote/sorry.txt
+-rw-rw-r--  2.0 unx      120 b- defN 23-Jun-28 09:50 quote4py-1.1.2.dist-info/METADATA
+-rw-rw-r--  2.0 unx       92 b- defN 23-Jun-28 09:50 quote4py-1.1.2.dist-info/WHEEL
+-rw-rw-r--  2.0 unx        6 b- defN 23-Jun-28 09:50 quote4py-1.1.2.dist-info/top_level.txt
+-rw-rw-r--  2.0 unx      653 b- defN 23-Jun-28 09:50 quote4py-1.1.2.dist-info/RECORD
+9 files, 2644 bytes uncompressed, 1641 bytes compressed:  37.9%
```

## zipnote {}

```diff
@@ -9,20 +9,20 @@
 
 Filename: quote/quotes.txt
 Comment: 
 
 Filename: quote/sorry.txt
 Comment: 
 
-Filename: quote4py-1.1.1.dist-info/METADATA
+Filename: quote4py-1.1.2.dist-info/METADATA
 Comment: 
 
-Filename: quote4py-1.1.1.dist-info/WHEEL
+Filename: quote4py-1.1.2.dist-info/WHEEL
 Comment: 
 
-Filename: quote4py-1.1.1.dist-info/top_level.txt
+Filename: quote4py-1.1.2.dist-info/top_level.txt
 Comment: 
 
-Filename: quote4py-1.1.1.dist-info/RECORD
+Filename: quote4py-1.1.2.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## quote/main.py

```diff
@@ -7,13 +7,13 @@
     with open(os.path.join(module_dir, "quotes.txt"), "r") as file:
         lines = file.readlines()
 
     new_lines = [s for s in lines if s.strip() != ""]
     return random.choice(new_lines)
 
 def x():
-    with open(os.path.join(module_dir, "sorry.txt"), "r") as file:
+    with open(file=os.path.join(module_dir, "sorry.txt"), mode="r", encoding="utf-8") as file:
         content = file.read()
     return content
 
 if __name__ == "__main__":
     print(x())
```

## Comparing `quote4py-1.1.1.dist-info/RECORD` & `quote4py-1.1.2.dist-info/RECORD`

 * *Files 25% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 quote/__init__.py,sha256=cY3EDBb2v8H5XXTMpi4Aywf0H7WLrPKLDzBpnRjwuJo,58
-quote/main.py,sha256=0zCbtZsTOevryc1ZGtwss253iJLizqxAccisiLOE5UQ,434
+quote/main.py,sha256=xBqMJ_wYnL_bnZe1MnaVbc_UQ45867RaedlXfH09iGs,462
 quote/quote.py,sha256=6qI-8ff8eWZ4xOK6UYrxzqJFsL3eISlMH9_SaYParl4,320
 quote/quotes.txt,sha256=sKTeKTUDr3-RJ8zlD7s_gRflwuyKDsPNSJfjmVus8P0,857
 quote/sorry.txt,sha256=LcgyF1UKGXadKbc5sKkq37_bCbwv3F6e93fafPqH3yg,76
-quote4py-1.1.1.dist-info/METADATA,sha256=LE3OZOw5QcgiWN7t7aizyd3hLCIWl_E7F9pWVz46fd0,120
-quote4py-1.1.1.dist-info/WHEEL,sha256=pkctZYzUS4AYVn6dJ-7367OJZivF2e8RA9b_ZBjif18,92
-quote4py-1.1.1.dist-info/top_level.txt,sha256=iL3v97oZL6aNSN-ZP5cc1SVSYyQAGM-ecCHhFroB7mQ,6
-quote4py-1.1.1.dist-info/RECORD,,
+quote4py-1.1.2.dist-info/METADATA,sha256=5PjGVoyfiHxnlFx8RDSoAMOgQqmtkWSjy5OKwi-MmuA,120
+quote4py-1.1.2.dist-info/WHEEL,sha256=pkctZYzUS4AYVn6dJ-7367OJZivF2e8RA9b_ZBjif18,92
+quote4py-1.1.2.dist-info/top_level.txt,sha256=iL3v97oZL6aNSN-ZP5cc1SVSYyQAGM-ecCHhFroB7mQ,6
+quote4py-1.1.2.dist-info/RECORD,,
```


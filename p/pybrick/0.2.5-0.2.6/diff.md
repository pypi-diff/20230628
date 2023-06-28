# Comparing `tmp/pybrick-0.2.5-py3-none-any.whl.zip` & `tmp/pybrick-0.2.6-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,8 +1,9 @@
-Zip file size: 5457 bytes, number of entries: 6
+Zip file size: 5639 bytes, number of entries: 7
 -rw-rw-rw-  2.0 fat        0 b- defN 22-Jun-30 13:40 pybrick/__init__.py
--rw-rw-rw-  2.0 fat    12398 b- defN 23-Jun-28 15:38 pybrick/pybrick.py
--rw-rw-rw-  2.0 fat      321 b- defN 23-Jun-28 15:43 pybrick-0.2.5.dist-info/METADATA
--rw-rw-rw-  2.0 fat       92 b- defN 23-Jun-28 15:43 pybrick-0.2.5.dist-info/WHEEL
--rw-rw-rw-  2.0 fat        8 b- defN 23-Jun-28 15:43 pybrick-0.2.5.dist-info/top_level.txt
-?rw-rw-r--  2.0 fat      445 b- defN 23-Jun-28 15:43 pybrick-0.2.5.dist-info/RECORD
-6 files, 13264 bytes uncompressed, 4649 bytes compressed:  65.0%
+-rw-rw-rw-  2.0 fat       25 b- defN 23-Jun-28 15:42 pybrick/ptest.csv
+-rw-rw-rw-  2.0 fat    12397 b- defN 23-Jun-28 15:51 pybrick/pybrick.py
+-rw-rw-rw-  2.0 fat      321 b- defN 23-Jun-28 15:54 pybrick-0.2.6.dist-info/METADATA
+-rw-rw-rw-  2.0 fat       92 b- defN 23-Jun-28 15:54 pybrick-0.2.6.dist-info/WHEEL
+-rw-rw-rw-  2.0 fat        8 b- defN 23-Jun-28 15:54 pybrick-0.2.6.dist-info/top_level.txt
+?rw-rw-r--  2.0 fat      517 b- defN 23-Jun-28 15:54 pybrick-0.2.6.dist-info/RECORD
+7 files, 13360 bytes uncompressed, 4721 bytes compressed:  64.7%
```

## zipnote {}

```diff
@@ -1,19 +1,22 @@
 Filename: pybrick/__init__.py
 Comment: 
 
+Filename: pybrick/ptest.csv
+Comment: 
+
 Filename: pybrick/pybrick.py
 Comment: 
 
-Filename: pybrick-0.2.5.dist-info/METADATA
+Filename: pybrick-0.2.6.dist-info/METADATA
 Comment: 
 
-Filename: pybrick-0.2.5.dist-info/WHEEL
+Filename: pybrick-0.2.6.dist-info/WHEEL
 Comment: 
 
-Filename: pybrick-0.2.5.dist-info/top_level.txt
+Filename: pybrick-0.2.6.dist-info/top_level.txt
 Comment: 
 
-Filename: pybrick-0.2.5.dist-info/RECORD
+Filename: pybrick-0.2.6.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## pybrick/pybrick.py

```diff
@@ -247,15 +247,15 @@
         if ignoreLoadErrors:
             maxbad="-1"
         
         ddl = self.getDfDDL(src,ybTypes)
         
         dump=tempfile.mkstemp(".csv")[1]
         vprint(f"Dumping local data to {dump}")
-        src.to_csv(dump,index=False,header=True,line_terminator="\n")
+        src.to_csv(dump,index=False,header=True,lineterminator="\n")
         vprint(f"Dumped {os.path.getsize(dump)/1024/1024:0.2f}MB.")
         
         if not self.tableExists(target):
             self.execute(f"""
                 create table {target} (
                     {ddl}
                 )
```


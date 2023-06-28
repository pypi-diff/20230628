# Comparing `tmp/setlr-0.2.8-py2.py3-none-any.whl.zip` & `tmp/setlr-0.2.9-py2.py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,12 +1,12 @@
-Zip file size: 16446 bytes, number of entries: 10
--rw-r--r--  2.0 unx    28681 b- defN 18-Dec-08 00:41 setlr/__init__.py
+Zip file size: 16443 bytes, number of entries: 10
+-rw-r--r--  2.0 unx    28681 b- defN 18-Dec-08 01:03 setlr/__init__.py
 -rw-r--r--  2.0 unx    24160 b- defN 18-Dec-05 13:25 setlr/iterparse_filter.py
--rw-r--r--  2.0 unx      107 b- defN 18-Dec-08 00:41 setlr-0.2.8.dist-info/DESCRIPTION.rst
--rw-r--r--  2.0 unx       38 b- defN 18-Dec-08 00:41 setlr-0.2.8.dist-info/entry_points.txt
--rw-r--r--  2.0 unx     1011 b- defN 18-Dec-08 00:41 setlr-0.2.8.dist-info/metadata.json
--rw-r--r--  2.0 unx       47 b- defN 18-Dec-08 00:41 setlr-0.2.8.dist-info/pbr.json
--rw-r--r--  2.0 unx        6 b- defN 18-Dec-08 00:41 setlr-0.2.8.dist-info/top_level.txt
--rw-r--r--  2.0 unx      110 b- defN 18-Dec-08 00:41 setlr-0.2.8.dist-info/WHEEL
--rw-r--r--  2.0 unx      947 b- defN 18-Dec-08 00:41 setlr-0.2.8.dist-info/METADATA
--rw-r--r--  2.0 unx      820 b- defN 18-Dec-08 00:41 setlr-0.2.8.dist-info/RECORD
-10 files, 55927 bytes uncompressed, 15060 bytes compressed:  73.1%
+-rw-r--r--  2.0 unx      107 b- defN 18-Dec-08 01:04 setlr-0.2.9.dist-info/DESCRIPTION.rst
+-rw-r--r--  2.0 unx       38 b- defN 18-Dec-08 01:04 setlr-0.2.9.dist-info/entry_points.txt
+-rw-r--r--  2.0 unx     1011 b- defN 18-Dec-08 01:04 setlr-0.2.9.dist-info/metadata.json
+-rw-r--r--  2.0 unx       47 b- defN 18-Dec-08 01:04 setlr-0.2.9.dist-info/pbr.json
+-rw-r--r--  2.0 unx        6 b- defN 18-Dec-08 01:04 setlr-0.2.9.dist-info/top_level.txt
+-rw-r--r--  2.0 unx      110 b- defN 18-Dec-08 01:04 setlr-0.2.9.dist-info/WHEEL
+-rw-r--r--  2.0 unx      947 b- defN 18-Dec-08 01:04 setlr-0.2.9.dist-info/METADATA
+-rw-r--r--  2.0 unx      820 b- defN 18-Dec-08 01:04 setlr-0.2.9.dist-info/RECORD
+10 files, 55927 bytes uncompressed, 15057 bytes compressed:  73.1%
```

## zipnote {}

```diff
@@ -1,31 +1,31 @@
 Filename: setlr/__init__.py
 Comment: 
 
 Filename: setlr/iterparse_filter.py
 Comment: 
 
-Filename: setlr-0.2.8.dist-info/DESCRIPTION.rst
+Filename: setlr-0.2.9.dist-info/DESCRIPTION.rst
 Comment: 
 
-Filename: setlr-0.2.8.dist-info/entry_points.txt
+Filename: setlr-0.2.9.dist-info/entry_points.txt
 Comment: 
 
-Filename: setlr-0.2.8.dist-info/metadata.json
+Filename: setlr-0.2.9.dist-info/metadata.json
 Comment: 
 
-Filename: setlr-0.2.8.dist-info/pbr.json
+Filename: setlr-0.2.9.dist-info/pbr.json
 Comment: 
 
-Filename: setlr-0.2.8.dist-info/top_level.txt
+Filename: setlr-0.2.9.dist-info/top_level.txt
 Comment: 
 
-Filename: setlr-0.2.8.dist-info/WHEEL
+Filename: setlr-0.2.9.dist-info/WHEEL
 Comment: 
 
-Filename: setlr-0.2.8.dist-info/METADATA
+Filename: setlr-0.2.9.dist-info/METADATA
 Comment: 
 
-Filename: setlr-0.2.8.dist-info/RECORD
+Filename: setlr-0.2.9.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## setlr/__init__.py

```diff
@@ -703,15 +703,15 @@
 def load(load_resource, resources):
     logger.info('Loading %s',load_resource.identifier)
     file_graph = Dataset(default_union=True)
     to_disk = False
     for used in load_resource[prov.used]:
         if used[RDF.type : setl.Persisted]:
             to_disk = True
-            file_graph = Dataset(store='Sleeptcat', default_union=True)
+            file_graph = Dataset(store='Sleepycat', default_union=True)
             tempdir = tempfile.mkdtemp()
             logger.debug("Gathering %s into %s", load_resource.identifier, tempdir)
             file_graph.store.open(tempdir, True)
             break
     if len(list(load_resource[prov.used])) == 1:
         logger.info("Using %s",load_resource.value(prov.used).identifier)
         file_graph = resources[load_resource.value(prov.used).identifier]
```

## Comparing `setlr-0.2.8.dist-info/metadata.json` & `setlr-0.2.9.dist-info/metadata.json`

 * *Files 1% similar despite different names*

### Pretty-printed

 * *Similarity: 0.9545454545454546%*

 * *Differences: {"'version'": "'0.2.9'"}*

```diff
@@ -60,9 +60,9 @@
                 "ijson",
                 "requests-testadapter",
                 "python-slugify"
             ]
         }
     ],
     "summary": "setlr is a tool for Semantic Extraction, Transformation, and Loading.",
-    "version": "0.2.8"
+    "version": "0.2.9"
 }
```

## Comparing `setlr-0.2.8.dist-info/METADATA` & `setlr-0.2.9.dist-info/METADATA`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.0
 Name: setlr
-Version: 0.2.8
+Version: 0.2.9
 Summary: setlr is a tool for Semantic Extraction, Transformation, and Loading.
 Home-page: http://packages.python.org/setlr
 Author: Jim McCusker
 Author-email: mccusj@cs.rpi.edu
 License: Apache License 2.0
 Keywords: rdf semantic etl
 Platform: UNKNOWN
```

## Comparing `setlr-0.2.8.dist-info/RECORD` & `setlr-0.2.9.dist-info/RECORD`

 * *Files 18% similar despite different names*

```diff
@@ -1,10 +1,10 @@
-setlr/__init__.py,sha256=68twL_q_FH14jW89ibDcW0KYO6MCIczOYIrPYQdRY04,28681
+setlr/__init__.py,sha256=xha-0xRgAjyLjq4sbGz411r7UwAI-w6EVi5KXYzztpM,28681
 setlr/iterparse_filter.py,sha256=ZpCCUqhSJTy7kViSOBOMevOch2J7DgYtvP35iGK7AH8,24160
-setlr-0.2.8.dist-info/RECORD,,
-setlr-0.2.8.dist-info/metadata.json,sha256=4llmFsxxyvajr97rRSaB7JLa6ByZ0TuhmsvOW8tVC3I,1011
-setlr-0.2.8.dist-info/WHEEL,sha256=AvR0WeTpDaxT645bl5FQxUK6NPsTls2ttpcGJg3j1Xg,110
-setlr-0.2.8.dist-info/entry_points.txt,sha256=ipvvxDgnD0-9aQEDWt1iZDqBeWPtLUvN6meEPYbIR7o,38
-setlr-0.2.8.dist-info/DESCRIPTION.rst,sha256=urfLL0EEJEY8Abd6BDGDy-NCZIbpkB5PspR7CDr2ESA,107
-setlr-0.2.8.dist-info/pbr.json,sha256=AngfBfehCkK_NJcMiyvs35HGAUuLk7fWDBo_rLXknYI,47
-setlr-0.2.8.dist-info/top_level.txt,sha256=x23SyJAUjYkpfhcZIwivm0nYNx6TW3Zj7aiQMLQ3hWc,6
-setlr-0.2.8.dist-info/METADATA,sha256=E9TmQdchHZf10lV89RnDspN7W4IBvH6gQsI5m4RSxqw,947
+setlr-0.2.9.dist-info/RECORD,,
+setlr-0.2.9.dist-info/metadata.json,sha256=nsEBQfXuASrWu2TLZ48lNrRVsS5hJD_lmlT5GJ23GM4,1011
+setlr-0.2.9.dist-info/WHEEL,sha256=AvR0WeTpDaxT645bl5FQxUK6NPsTls2ttpcGJg3j1Xg,110
+setlr-0.2.9.dist-info/entry_points.txt,sha256=ipvvxDgnD0-9aQEDWt1iZDqBeWPtLUvN6meEPYbIR7o,38
+setlr-0.2.9.dist-info/DESCRIPTION.rst,sha256=urfLL0EEJEY8Abd6BDGDy-NCZIbpkB5PspR7CDr2ESA,107
+setlr-0.2.9.dist-info/pbr.json,sha256=AngfBfehCkK_NJcMiyvs35HGAUuLk7fWDBo_rLXknYI,47
+setlr-0.2.9.dist-info/top_level.txt,sha256=x23SyJAUjYkpfhcZIwivm0nYNx6TW3Zj7aiQMLQ3hWc,6
+setlr-0.2.9.dist-info/METADATA,sha256=vi5dMFP3ikxeN_mff5boHsxwFY1C4EtGbbeiLaeYmwQ,947
```


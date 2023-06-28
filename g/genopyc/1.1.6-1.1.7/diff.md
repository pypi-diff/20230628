# Comparing `tmp/genopyc-1.1.6-py3-none-any.whl.zip` & `tmp/genopyc-1.1.7-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,10 +1,10 @@
-Zip file size: 424218 bytes, number of entries: 8
--rwxrwxrwx  2.0 unx      978 b- defN 23-Jun-24 20:45 genopyc/__init__.py
--rwxrwxrwx  2.0 unx    42603 b- defN 23-Jun-27 09:05 genopyc/genopyc.py
+Zip file size: 424572 bytes, number of entries: 8
+-rwxrwxrwx  2.0 unx     1019 b- defN 23-Jun-28 13:05 genopyc/__init__.py
+-rwxrwxrwx  2.0 unx    44053 b- defN 23-Jun-28 13:05 genopyc/genopyc.py
 -rwxrwxrwx  2.0 unx  1302100 b- defN 23-Jun-21 11:17 genopyc/data/hippie_interactome.sif
--rwxrwxrwx  2.0 unx    34523 b- defN 23-Jun-27 09:08 genopyc-1.1.6.dist-info/LICENSE.txt
--rwxrwxrwx  2.0 unx      596 b- defN 23-Jun-27 09:08 genopyc-1.1.6.dist-info/METADATA
--rwxrwxrwx  2.0 unx       92 b- defN 23-Jun-27 09:08 genopyc-1.1.6.dist-info/WHEEL
--rwxrwxrwx  2.0 unx        8 b- defN 23-Jun-27 09:07 genopyc-1.1.6.dist-info/top_level.txt
-?rw-rw-r--  2.0 unx      635 b- defN 23-Jun-27 09:08 genopyc-1.1.6.dist-info/RECORD
-8 files, 1381535 bytes uncompressed, 423118 bytes compressed:  69.4%
+-rwxrwxrwx  2.0 unx    34523 b- defN 23-Jun-28 13:05 genopyc-1.1.7.dist-info/LICENSE.txt
+-rwxrwxrwx  2.0 unx      596 b- defN 23-Jun-28 13:05 genopyc-1.1.7.dist-info/METADATA
+-rwxrwxrwx  2.0 unx       92 b- defN 23-Jun-28 13:05 genopyc-1.1.7.dist-info/WHEEL
+-rwxrwxrwx  2.0 unx        8 b- defN 23-Jun-28 13:05 genopyc-1.1.7.dist-info/top_level.txt
+?rw-rw-r--  2.0 unx      636 b- defN 23-Jun-28 13:05 genopyc-1.1.7.dist-info/RECORD
+8 files, 1383027 bytes uncompressed, 423472 bytes compressed:  69.4%
```

## zipnote {}

```diff
@@ -3,23 +3,23 @@
 
 Filename: genopyc/genopyc.py
 Comment: 
 
 Filename: genopyc/data/hippie_interactome.sif
 Comment: 
 
-Filename: genopyc-1.1.6.dist-info/LICENSE.txt
+Filename: genopyc-1.1.7.dist-info/LICENSE.txt
 Comment: 
 
-Filename: genopyc-1.1.6.dist-info/METADATA
+Filename: genopyc-1.1.7.dist-info/METADATA
 Comment: 
 
-Filename: genopyc-1.1.6.dist-info/WHEEL
+Filename: genopyc-1.1.7.dist-info/WHEEL
 Comment: 
 
-Filename: genopyc-1.1.6.dist-info/top_level.txt
+Filename: genopyc-1.1.7.dist-info/top_level.txt
 Comment: 
 
-Filename: genopyc-1.1.6.dist-info/RECORD
+Filename: genopyc-1.1.7.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## genopyc/__init__.py

```diff
@@ -15,8 +15,9 @@
 from genopyc.genopyc import get_variant_info_many
 from genopyc.genopyc import get_eqtl_df
 from genopyc.genopyc import GetLDMatrix
 from genopyc.genopyc import PairwiseLD
 from genopyc.genopyc import ConvertVariantsForOT
 from genopyc.genopyc import OT_L2G
 from genopyc.genopyc import FuEnViz
-from genopyc.genopyc import plot_enrichment_analisys_network
+from genopyc.genopyc import plot_enrichment_analisys_network
+from genopyc.genopyc import ClosestGenes
```

## genopyc/genopyc.py

```diff
@@ -443,14 +443,54 @@
 #Retrieves overlapping elements of a given region 
 def get_ov_region(chromosome,start,stop,features=list):
     str_features=';'.join(['feature='+x for x in features])
     http="https://rest.ensembl.org/overlap/region/human/%s:%s-%s?%s"%(chromosome,start,stop,str_features)
     risposta=requests.get(http,headers={ "Content-Type" : "application/json"}).json()
     return risposta
 
+def ClosestGenes(positionid,chromosome,position,window_size,type_of_gene = False):
+    """ Retrieve the closeset upstream and downstrem genes given a point genomic location """
+    starting_window = position - window_size//2
+    end_window = position + window_size//2
+    elements =  get_ov_region(chromosome,starting_window,end_window, features=['gene'])
+    
+    all_genes = []
+    for e in elements:
+        if type_of_gene:
+            if e['biotype'] == type_of_gene:
+                all_genes.append((e['gene_id'],e['start'] - position,e['end'] - position))
+        else:
+            
+            all_genes.append((e['gene_id'],e['start'] - position,e['end'] - position))
+
+            
+    
+    positive_r = []
+    negative_r = []
+    for r in all_genes:
+        #Look for the closest upstream gene 
+        if r[1] > 0:
+            positive_r.append(r)
+        elif r[2] < 0:
+            negative_r.append(r)
+    if len(negative_r)>0:
+        closest_downstream_gene = max(negative_r,key = lambda x: x[2])[0]
+    else:
+        print(f'no downstream genes in the selected window for variant {positionid}')
+        closest_downstream_gene = ''
+
+    if len(positive_r)>0:
+        closest_upstream_gene = min(positive_r,key = lambda x: x[2])[0]
+    else:
+        print(f'no upstream genes in the selected window for variant {positionid}')
+        closest_upstream_gene = ''
+
+    return (positionid,closest_upstream_gene,closest_downstream_gene)
+
+
 #Retrieves the nucleotide sequence of a given position 
 def get_sequence(chromosome,start,stop):
     http="https://rest.ensembl.org/sequence/region/human/%s:%s..%s?" %(chromosome,start,stop)
     risposta=requests.get(http,headers={ "Content-Type" : "application/json"}).json()
     return risposta['seq']
 
 ## lift from grch37 to 38
```

## Comparing `genopyc-1.1.6.dist-info/LICENSE.txt` & `genopyc-1.1.7.dist-info/LICENSE.txt`

 * *Files identical despite different names*

## Comparing `genopyc-1.1.6.dist-info/METADATA` & `genopyc-1.1.7.dist-info/METADATA`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: genopyc
-Version: 1.1.6
+Version: 1.1.7
 Author: Francesco Gualdi
 License: GPL
 Description-Content-Type: text/markdown
 License-File: LICENSE.txt
 Requires-Dist: requests
 Requires-Dist: pandas
 Requires-Dist: numpy
```


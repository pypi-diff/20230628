# Comparing `tmp/odoo_addons_oca_edi-16.0.20230521.0-py3-none-any.whl.zip` & `tmp/odoo_addons_oca_edi-16.0.20230627.0-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,6 +1,6 @@
-Zip file size: 1339 bytes, number of entries: 4
--rw-r--r--  2.0 unx      597 b- defN 23-May-22 05:07 odoo_addons_oca_edi-16.0.20230521.0.dist-info/METADATA
--rw-r--r--  2.0 unx       92 b- defN 23-May-22 05:07 odoo_addons_oca_edi-16.0.20230521.0.dist-info/WHEEL
--rw-r--r--  2.0 unx        1 b- defN 23-May-22 05:07 odoo_addons_oca_edi-16.0.20230521.0.dist-info/top_level.txt
-?rw-rw-r--  2.0 unx      384 b- defN 23-May-22 05:07 odoo_addons_oca_edi-16.0.20230521.0.dist-info/RECORD
-4 files, 1074 bytes uncompressed, 581 bytes compressed:  45.9%
+Zip file size: 1344 bytes, number of entries: 4
+-rw-r--r--  2.0 unx      668 b- defN 23-Jun-28 03:24 odoo_addons_oca_edi-16.0.20230627.0.dist-info/METADATA
+-rw-r--r--  2.0 unx       92 b- defN 23-Jun-28 03:24 odoo_addons_oca_edi-16.0.20230627.0.dist-info/WHEEL
+-rw-r--r--  2.0 unx        1 b- defN 23-Jun-28 03:24 odoo_addons_oca_edi-16.0.20230627.0.dist-info/top_level.txt
+-rw-rw-r--  2.0 unx      384 b- defN 23-Jun-28 03:24 odoo_addons_oca_edi-16.0.20230627.0.dist-info/RECORD
+4 files, 1145 bytes uncompressed, 586 bytes compressed:  48.8%
```

## zipnote {}

```diff
@@ -1,13 +1,13 @@
-Filename: odoo_addons_oca_edi-16.0.20230521.0.dist-info/METADATA
+Filename: odoo_addons_oca_edi-16.0.20230627.0.dist-info/METADATA
 Comment: 
 
-Filename: odoo_addons_oca_edi-16.0.20230521.0.dist-info/WHEEL
+Filename: odoo_addons_oca_edi-16.0.20230627.0.dist-info/WHEEL
 Comment: 
 
-Filename: odoo_addons_oca_edi-16.0.20230521.0.dist-info/top_level.txt
+Filename: odoo_addons_oca_edi-16.0.20230627.0.dist-info/top_level.txt
 Comment: 
 
-Filename: odoo_addons_oca_edi-16.0.20230521.0.dist-info/RECORD
+Filename: odoo_addons_oca_edi-16.0.20230627.0.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## Comparing `odoo_addons_oca_edi-16.0.20230521.0.dist-info/METADATA` & `odoo_addons_oca_edi-16.0.20230627.0.dist-info/METADATA`

 * *Files 18% similar despite different names*

```diff
@@ -1,18 +1,19 @@
 Metadata-Version: 2.1
 Name: odoo-addons-oca-edi
-Version: 16.0.20230521.0
+Version: 16.0.20230627.0
 Summary: Meta package for oca-edi Odoo addons
 Home-page: UNKNOWN
 License: UNKNOWN
 Platform: UNKNOWN
 Classifier: Programming Language :: Python
 Classifier: Framework :: Odoo
 Classifier: Framework :: Odoo :: 16.0
 Requires-Dist: odoo-addon-account-einvoice-generate (<16.1dev,>=16.0dev)
+Requires-Dist: odoo-addon-account-invoice-facturx (<16.1dev,>=16.0dev)
 Requires-Dist: odoo-addon-base-edi (<16.1dev,>=16.0dev)
 Requires-Dist: odoo-addon-base-facturx (<16.1dev,>=16.0dev)
 Requires-Dist: odoo-addon-base-ubl (<16.1dev,>=16.0dev)
 Requires-Dist: odoo-addon-pdf-helper (<16.1dev,>=16.0dev)
 
 UNKNOWN
```


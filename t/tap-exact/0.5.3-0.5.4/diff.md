# Comparing `tmp/tap_exact-0.5.3.tar.gz` & `tmp/tap_exact-0.5.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tap_exact-0.5.3.tar", max compression
+gzip compressed data, was "tap_exact-0.5.4.tar", max compression
```

## Comparing `tap_exact-0.5.3.tar` & `tap_exact-0.5.4.tar`

### file list

```diff
@@ -1,9 +1,9 @@
--rw-r--r--   0        0        0      932 2023-06-16 19:37:33.351501 tap_exact-0.5.3/pyproject.toml
--rw-r--r--   0        0        0        0 2022-11-25 19:29:50.108600 tap_exact-0.5.3/tap_exact/__init__.py
--rw-r--r--   0        0        0     2469 2023-06-06 11:29:41.864014 tap_exact-0.5.3/tap_exact/client.py
--rw-r--r--   0        0        0    37553 2023-06-16 19:37:15.491501 tap_exact-0.5.3/tap_exact/streams.py
--rw-r--r--   0        0        0     1917 2023-06-06 09:27:46.919611 tap_exact-0.5.3/tap_exact/tap.py
--rw-r--r--   0        0        0       32 2022-11-25 19:29:50.118600 tap_exact-0.5.3/tap_exact/tests/__init__.py
--rw-r--r--   0        0        0      657 2022-11-25 19:50:07.718600 tap_exact-0.5.3/tap_exact/tests/test_core.py
--rw-r--r--   0        0        0      960 1970-01-01 00:00:00.000000 tap_exact-0.5.3/setup.py
--rw-r--r--   0        0        0      695 1970-01-01 00:00:00.000000 tap_exact-0.5.3/PKG-INFO
+-rw-r--r--   0        0        0      932 2023-06-28 13:01:11.047380 tap_exact-0.5.4/pyproject.toml
+-rw-r--r--   0        0        0        0 2022-11-25 19:29:50.108600 tap_exact-0.5.4/tap_exact/__init__.py
+-rw-r--r--   0        0        0     2469 2023-06-06 11:29:41.864014 tap_exact-0.5.4/tap_exact/client.py
+-rw-r--r--   0        0        0    37730 2023-06-28 13:02:02.287380 tap_exact-0.5.4/tap_exact/streams.py
+-rw-r--r--   0        0        0     1917 2023-06-06 09:27:46.919611 tap_exact-0.5.4/tap_exact/tap.py
+-rw-r--r--   0        0        0       32 2022-11-25 19:29:50.118600 tap_exact-0.5.4/tap_exact/tests/__init__.py
+-rw-r--r--   0        0        0      657 2022-11-25 19:50:07.718600 tap_exact-0.5.4/tap_exact/tests/test_core.py
+-rw-r--r--   0        0        0      960 1970-01-01 00:00:00.000000 tap_exact-0.5.4/setup.py
+-rw-r--r--   0        0        0      695 1970-01-01 00:00:00.000000 tap_exact-0.5.4/PKG-INFO
```

### Comparing `tap_exact-0.5.3/pyproject.toml` & `tap_exact-0.5.4/pyproject.toml`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "tap-exact"
-version = "0.5.3"
+version = "0.5.4"
 description = "`tap-exact` is a Singer tap for Exact Online, built with the Meltano Singer SDK."
 authors = ["Janick Otten"]
 keywords = [
     "ELT",
     "Exact Online",
 ]
 license = "Apache 2.0"
```

### Comparing `tap_exact-0.5.3/tap_exact/client.py` & `tap_exact-0.5.4/tap_exact/client.py`

 * *Files identical despite different names*

### Comparing `tap_exact-0.5.3/tap_exact/streams.py` & `tap_exact-0.5.4/tap_exact/streams.py`

 * *Files 0% similar despite different names*

```diff
@@ -82,28 +82,33 @@
         ),
         th.Property(
             "AmountDiscount",
             th.NumberType,
             description="Amount of discount given"
         ),
         th.Property(
+            "VATAmountDC",
+            th.NumberType,
+            description="Amount of VAT in the default currency of the company"
+        ),
+        th.Property(
             "Modified",
             th.DateTimeType,
             description="Last modified date"
         ),
     ).to_dict()
 
     def get_path(self, context: Optional[dict]) -> str:
         """Return the path of the Exact API"""
 
         replication_key_value = self.get_starting_timestamp(context).strftime('%Y-%m-%dT%H:%M:%S.%fZ')
         
         path = "/salesinvoice/SalesInvoices?" \
             f"$filter={self.replication_key}%20ge%20datetime%27{replication_key_value}%27&" \
-            "$select=InvoiceID,InvoiceDate,InvoiceNumber,InvoiceTo,InvoiceToName,OrderDate,OrderedBy,OrderedByName,Creator,CreatorFullName,AmountDC,AmountDiscount,Modified"
+            "$select=InvoiceID,InvoiceDate,InvoiceNumber,InvoiceTo,InvoiceToName,OrderDate,OrderedBy,OrderedByName,Creator,CreatorFullName,AmountDC,AmountDiscount,VATAmountDC,Modified"
 
         return path
 
 class PurchaseInvoicesStream(ExactOnlineStream):
     """Define custom stream."""
 
     name = "purchase_invoices"
```

### Comparing `tap_exact-0.5.3/tap_exact/tap.py` & `tap_exact-0.5.4/tap_exact/tap.py`

 * *Files identical despite different names*

### Comparing `tap_exact-0.5.3/tap_exact/tests/test_core.py` & `tap_exact-0.5.4/tap_exact/tests/test_core.py`

 * *Files identical despite different names*

### Comparing `tap_exact-0.5.3/setup.py` & `tap_exact-0.5.4/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 {'s3': ['fs-s3fs>=1.1.1,<2.0.0']}
 
 entry_points = \
 {'console_scripts': ['tap-exact = tap_exact.tap:TapExactOnline.cli']}
 
 setup_kwargs = {
     'name': 'tap-exact',
-    'version': '0.5.3',
+    'version': '0.5.4',
     'description': '`tap-exact` is a Singer tap for Exact Online, built with the Meltano Singer SDK.',
     'long_description': 'None',
     'author': 'Janick Otten',
     'author_email': 'None',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'None',
```

### Comparing `tap_exact-0.5.3/PKG-INFO` & `tap_exact-0.5.4/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tap-exact
-Version: 0.5.3
+Version: 0.5.4
 Summary: `tap-exact` is a Singer tap for Exact Online, built with the Meltano Singer SDK.
 License: Apache 2.0
 Keywords: ELT,Exact Online
 Author: Janick Otten
 Requires-Python: >=3.7.1,<3.11
 Classifier: License :: Other/Proprietary License
 Classifier: Programming Language :: Python :: 3
```


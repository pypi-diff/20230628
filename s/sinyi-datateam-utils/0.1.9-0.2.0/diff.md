# Comparing `tmp/sinyi_datateam_utils-0.1.9.tar.gz` & `tmp/sinyi_datateam_utils-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sinyi_datateam_utils-0.1.9.tar", last modified: Wed Jun 14 04:06:24 2023, max compression
+gzip compressed data, was "sinyi_datateam_utils-0.2.0.tar", last modified: Wed Jun 28 02:33:38 2023, max compression
```

## Comparing `sinyi_datateam_utils-0.1.9.tar` & `sinyi_datateam_utils-0.2.0.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxrwxr-x   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)        0 2023-06-14 04:06:24.342558 sinyi_datateam_utils-0.1.9/
--rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)     2406 2023-06-14 04:06:24.338558 sinyi_datateam_utils-0.1.9/PKG-INFO
--rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)     2180 2022-12-16 02:49:49.000000 sinyi_datateam_utils-0.1.9/README.md
--rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)       38 2023-06-14 04:06:24.342558 sinyi_datateam_utils-0.1.9/setup.cfg
--rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)      646 2023-06-14 04:06:05.000000 sinyi_datateam_utils-0.1.9/setup.py
-drwxrwxr-x   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)        0 2023-06-14 04:06:24.338558 sinyi_datateam_utils-0.1.9/sinyi_datateam_utils.egg-info/
--rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)     2406 2023-06-14 04:06:24.000000 sinyi_datateam_utils-0.1.9/sinyi_datateam_utils.egg-info/PKG-INFO
--rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)      316 2023-06-14 04:06:24.000000 sinyi_datateam_utils-0.1.9/sinyi_datateam_utils.egg-info/SOURCES.txt
--rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)        1 2023-06-14 04:06:24.000000 sinyi_datateam_utils-0.1.9/sinyi_datateam_utils.egg-info/dependency_links.txt
--rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)       83 2023-06-14 04:06:24.000000 sinyi_datateam_utils-0.1.9/sinyi_datateam_utils.egg-info/requires.txt
--rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)       12 2023-06-14 04:06:24.000000 sinyi_datateam_utils-0.1.9/sinyi_datateam_utils.egg-info/top_level.txt
-drwxrwxr-x   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)        0 2023-06-14 04:06:24.338558 sinyi_datateam_utils-0.1.9/sinyi_utils/
--rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)        0 2022-12-06 02:44:18.000000 sinyi_datateam_utils-0.1.9/sinyi_utils/__init__.py
--rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)     2634 2022-12-16 02:49:49.000000 sinyi_datateam_utils-0.1.9/sinyi_utils/db_connector.py
--rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)     3514 2023-06-14 04:05:13.000000 sinyi_datateam_utils-0.1.9/sinyi_utils/format_tool.py
+drwxrwxr-x   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)        0 2023-06-28 02:33:38.659679 sinyi_datateam_utils-0.2.0/
+-rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)     3182 2023-06-28 02:33:38.659679 sinyi_datateam_utils-0.2.0/PKG-INFO
+-rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)     2970 2023-06-28 02:32:33.000000 sinyi_datateam_utils-0.2.0/README.md
+-rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)       38 2023-06-28 02:33:38.659679 sinyi_datateam_utils-0.2.0/setup.cfg
+-rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)      646 2023-06-28 02:33:18.000000 sinyi_datateam_utils-0.2.0/setup.py
+drwxrwxr-x   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)        0 2023-06-28 02:33:38.659679 sinyi_datateam_utils-0.2.0/sinyi_datateam_utils.egg-info/
+-rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)     3182 2023-06-28 02:33:38.000000 sinyi_datateam_utils-0.2.0/sinyi_datateam_utils.egg-info/PKG-INFO
+-rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)      316 2023-06-28 02:33:38.000000 sinyi_datateam_utils-0.2.0/sinyi_datateam_utils.egg-info/SOURCES.txt
+-rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)        1 2023-06-28 02:33:38.000000 sinyi_datateam_utils-0.2.0/sinyi_datateam_utils.egg-info/dependency_links.txt
+-rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)       83 2023-06-28 02:33:38.000000 sinyi_datateam_utils-0.2.0/sinyi_datateam_utils.egg-info/requires.txt
+-rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)       12 2023-06-28 02:33:38.000000 sinyi_datateam_utils-0.2.0/sinyi_datateam_utils.egg-info/top_level.txt
+drwxrwxr-x   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)        0 2023-06-28 02:33:38.659679 sinyi_datateam_utils-0.2.0/sinyi_utils/
+-rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)        0 2022-12-06 02:44:18.000000 sinyi_datateam_utils-0.2.0/sinyi_utils/__init__.py
+-rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)     2634 2022-12-16 02:49:49.000000 sinyi_datateam_utils-0.2.0/sinyi_utils/db_connector.py
+-rw-rw-r--   0 Lable360PrdVMuser  (1000) Lable360PrdVMuser  (1000)     3514 2023-06-14 04:05:13.000000 sinyi_datateam_utils-0.2.0/sinyi_utils/format_tool.py
```

### Comparing `sinyi_datateam_utils-0.1.9/PKG-INFO` & `sinyi_datateam_utils-0.2.0/README.md`

 * *Files 20% similar despite different names*

```diff
@@ -1,104 +1,107 @@
-Metadata-Version: 2.1
-Name: sinyi_datateam_utils
-Version: 0.1.9
-Summary: Utilities for data analysis
-Home-page: https://SinyiDataTeam@dev.azure.com/SinyiDataTeam/Label360/_git/sinyi_utils
-Author: sinyidatateam
-Author-email: me30@sinyi.com.tw
-License: MIT
-Requires-Python: >=3.8
-Description-Content-Type: text/markdown
-
-# Introduction 
-Sinyi Datateam common module (for databricks environment)
-
-# Version
-Latest releases - https://pypi.org/project/sinyi-datateam-utils/
-
-# Getting Started
-1.	Installation process - Module has already installed in databricks cluster
-
-
-# Use Guideline
-
-## sinyi-utils module
-module tree structure:
-```
-.
-├── __init__.py
-├── db_connector.py
-└── format_tool.py
-```
-
-### format_tool
-``` python
-from sinyi_utils.format_tool import AESCrypto, roc_era_to_ad, Road8
-```
-1. AESCrypto: google decrypt & encrypt
-    - method : same as sinyi module
-
-2. roc_era_to_ad : transfer Chinese date to AD
-    Example:
-    ```python
-    roc_era_to_ad('0801122')
-
-    # Out: '19911122'
-    ```
-3. Road8
-    ```python
-    address='Address need to be normalize'
-    response = Road8.normalize(address)
-    ```
-    response will get entire json from api
-    
-### db_connector
-```python
-from sinyi_utils.db_connector import upload_blob_from_memory, DW001Connector, AzureADSConnector...
-```
-1. MssqlConnector : connector to all kinds of db
-
-#### method : query(query,database)
-```python
-# DW001Connector
-query=  """
-            TRUNCATE TABLE [TMP].[dbo].[TMP_SYNAPSE_PIPELINE_LOG_test]  
-       """
-DW001Connector.query(query,database='TMP')
-
-# AzureADSConnector/AzureTMPConnector
-query=  """
-            DELETE FROM [dbo].[SA_GENE_LIST] WHERE GENE_ID='M106_P13af_a' and MOBILE_NO = 999999;
-       """
-AzureTMPConnector.query(query)
-# out: 1 rows affected
-```
-#### method : connector(database)
-```python 
-# DW001Connector
-query = '''
-SELECT TOP(10)[AGEN_CUST_ID]
-      ,[OBJ_ID]
-      ,[RECE_ID]
-      ,[TRADE_CATE]
-      ,[CUST_CATE]
-      ,[DEAL_DATE]
-
-  FROM [DIM].[dbo].[DIM_CUSTOMER_DEAL_STATUS_DATE]
-  
-'''
-df = pd.read_sql(query,DW001Connector.connector(database='DIM'))
-# AzureADSConnector/AzureTMPConnector
-query = '''
-SELECT TOP (10) [MOBILE_NO]
-      ,[GENE_VALUE]
-  FROM [dbo].[SA_GENE_RESULT_OUTPUT]
-  
-'''
-df = pd.read_sql(query,AzureADSConnector.connector())
-
-```
-
-
-# Contribute
-TODO: Explain how other users and developers can contribute to make your code better. 
-
+# Introduction 
+Sinyi Datateam common module (for databricks environment)
+
+# Version
+Latest releases - https://pypi.org/project/sinyi-datateam-utils/
+
+# Getting Started
+1.	Installation process - Module has already installed in databricks cluster
+
+
+# Use Guideline
+
+## sinyi-utils module
+module tree structure:
+```
+.
+├── __init__.py
+├── db_connector.py
+└── format_tool.py
+```
+
+### format_tool
+``` python
+from sinyi_utils.format_tool import AESCrypto, roc_era_to_ad, Road8
+```
+1. AESCrypto: google decrypt & encrypt
+    - For envitornment databricks-dev/databricks-stg/databricks-prd
+    ```python
+        secrect_key = dbutils.secrets.get(scope = "label360-kv-dev", key = "AESCrypto-key")
+        secrect_iv =  dbutils.secrets.get(scope = "label360-kv-dev", key = "AESCrypto-iv")
+        aesc_crypto = AESCrypto(secrect_key, secrect_iv)
+    ```
+    - method: decrypt/encrypt
+    ```python
+        aesc_crypto.decrypt('QR/JKD7pcH+/lOlmejP9WjB94FTtnR0rRPrcSyorHwU=')
+    ```
+2. roc_era_to_ad : transfer Chinese date to AD
+    Example:
+    ```python
+    roc_era_to_ad('0801122')
+
+    # Out: '19911122'
+    ```
+3. Road8
+  - For envitornment databricks-dev/databricks-stg/databricks-prd
+    ```python
+        env = os.environ['ENV']
+
+        api_key = dbutils.secrets.get(scope = f"label360-kv-{env}", key = "road8-api-key")
+        host = dbutils.secrets.get(scope = f"label360-kv-{env}", key = "road8-host")
+        road8_normalize = Road8(api_key, host)
+    ```
+ - Normalize address: response will get entire json from api 
+    ```python
+        road8_normalize.normalize('臺北市萬華區武成街56巷4號二樓')
+    ```
+### db_connector
+```python
+from sinyi_utils.db_connector import upload_blob_from_memory, DW001Connector, AzureADSConnector...
+```
+1. MssqlConnector : connector to all kinds of db
+
+#### method : query(query,database)
+```python
+# DW001Connector
+query=  """
+            TRUNCATE TABLE [TMP].[dbo].[TMP_SYNAPSE_PIPELINE_LOG_test]  
+       """
+DW001Connector.query(query,database='TMP')
+
+# AzureADSConnector/AzureTMPConnector
+query=  """
+            DELETE FROM [dbo].[SA_GENE_LIST] WHERE GENE_ID='M106_P13af_a' and MOBILE_NO = 999999;
+       """
+AzureTMPConnector.query(query)
+# out: 1 rows affected
+```
+#### method : connector(database)
+```python 
+# DW001Connector
+query = '''
+SELECT TOP(10)[AGEN_CUST_ID]
+      ,[OBJ_ID]
+      ,[RECE_ID]
+      ,[TRADE_CATE]
+      ,[CUST_CATE]
+      ,[DEAL_DATE]
+
+  FROM [DIM].[dbo].[DIM_CUSTOMER_DEAL_STATUS_DATE]
+  
+'''
+df = pd.read_sql(query,DW001Connector.connector(database='DIM'))
+# AzureADSConnector/AzureTMPConnector
+query = '''
+SELECT TOP (10) [MOBILE_NO]
+      ,[GENE_VALUE]
+  FROM [dbo].[SA_GENE_RESULT_OUTPUT]
+  
+'''
+df = pd.read_sql(query,AzureADSConnector.connector())
+
+```
+
+
+# Contribute
+TODO: Explain how other users and developers can contribute to make your code better. 
+
```

### Comparing `sinyi_datateam_utils-0.1.9/setup.py` & `sinyi_datateam_utils-0.2.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 import setuptools
   
 with open("README.md", "r") as fh:
     description = fh.read()
   
 setuptools.setup(
     name="sinyi_datateam_utils",
-    version="0.1.9",
+    version="0.2.0",
     author="sinyidatateam",
     author_email="me30@sinyi.com.tw",
     packages=["sinyi_utils"],
     description="Utilities for data analysis",
     long_description=description,
     long_description_content_type="text/markdown",
     url="https://SinyiDataTeam@dev.azure.com/SinyiDataTeam/Label360/_git/sinyi_utils",
```

### Comparing `sinyi_datateam_utils-0.1.9/sinyi_datateam_utils.egg-info/PKG-INFO` & `sinyi_datateam_utils-0.2.0/PKG-INFO`

 * *Files 24% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: sinyi-datateam-utils
-Version: 0.1.9
+Name: sinyi_datateam_utils
+Version: 0.2.0
 Summary: Utilities for data analysis
 Home-page: https://SinyiDataTeam@dev.azure.com/SinyiDataTeam/Label360/_git/sinyi_utils
 Author: sinyidatateam
 Author-email: me30@sinyi.com.tw
 License: MIT
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
@@ -31,30 +31,44 @@
 ```
 
 ### format_tool
 ``` python
 from sinyi_utils.format_tool import AESCrypto, roc_era_to_ad, Road8
 ```
 1. AESCrypto: google decrypt & encrypt
-    - method : same as sinyi module
-
+    - For envitornment databricks-dev/databricks-stg/databricks-prd
+    ```python
+        secrect_key = dbutils.secrets.get(scope = "label360-kv-dev", key = "AESCrypto-key")
+        secrect_iv =  dbutils.secrets.get(scope = "label360-kv-dev", key = "AESCrypto-iv")
+        aesc_crypto = AESCrypto(secrect_key, secrect_iv)
+    ```
+    - method: decrypt/encrypt
+    ```python
+        aesc_crypto.decrypt('QR/JKD7pcH+/lOlmejP9WjB94FTtnR0rRPrcSyorHwU=')
+    ```
 2. roc_era_to_ad : transfer Chinese date to AD
     Example:
     ```python
     roc_era_to_ad('0801122')
 
     # Out: '19911122'
     ```
 3. Road8
+  - For envitornment databricks-dev/databricks-stg/databricks-prd
+    ```python
+        env = os.environ['ENV']
+
+        api_key = dbutils.secrets.get(scope = f"label360-kv-{env}", key = "road8-api-key")
+        host = dbutils.secrets.get(scope = f"label360-kv-{env}", key = "road8-host")
+        road8_normalize = Road8(api_key, host)
+    ```
+ - Normalize address: response will get entire json from api 
     ```python
-    address='Address need to be normalize'
-    response = Road8.normalize(address)
+        road8_normalize.normalize('臺北市萬華區武成街56巷4號二樓')
     ```
-    response will get entire json from api
-    
 ### db_connector
 ```python
 from sinyi_utils.db_connector import upload_blob_from_memory, DW001Connector, AzureADSConnector...
 ```
 1. MssqlConnector : connector to all kinds of db
 
 #### method : query(query,database)
```

### Comparing `sinyi_datateam_utils-0.1.9/sinyi_utils/db_connector.py` & `sinyi_datateam_utils-0.2.0/sinyi_utils/db_connector.py`

 * *Files identical despite different names*

### Comparing `sinyi_datateam_utils-0.1.9/sinyi_utils/format_tool.py` & `sinyi_datateam_utils-0.2.0/sinyi_utils/format_tool.py`

 * *Files identical despite different names*


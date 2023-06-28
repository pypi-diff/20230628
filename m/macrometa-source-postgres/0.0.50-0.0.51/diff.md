# Comparing `tmp/macrometa-source-postgres-0.0.50.tar.gz` & `tmp/macrometa-source-postgres-0.0.51.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "macrometa-source-postgres-0.0.50.tar", max compression
+gzip compressed data, was "macrometa-source-postgres-0.0.51.tar", max compression
```

## Comparing `macrometa-source-postgres-0.0.50.tar` & `macrometa-source-postgres-0.0.51.tar`

### file list

```diff
@@ -1,12 +1,12 @@
--rw-r--r--   0        0        0    11899 2023-06-20 15:04:10.363716 macrometa-source-postgres-0.0.50/LICENSE
--rw-r--r--   0        0        0    35738 2023-06-20 15:04:10.363716 macrometa-source-postgres-0.0.50/macrometa_source_postgres/__init__.py
--rw-r--r--   0        0        0     8580 2023-06-20 15:04:10.363716 macrometa-source-postgres-0.0.50/macrometa_source_postgres/connection.py
--rw-r--r--   0        0        0    20349 2023-06-20 15:04:10.363716 macrometa-source-postgres-0.0.50/macrometa_source_postgres/helper.py
--rw-r--r--   0        0        0        0 2023-06-20 15:04:10.363716 macrometa-source-postgres-0.0.50/macrometa_source_postgres/sync_strategies/__init__.py
--rw-r--r--   0        0        0     1212 2023-06-20 15:04:10.363716 macrometa-source-postgres-0.0.50/macrometa_source_postgres/sync_strategies/common.py
--rw-r--r--   0        0        0     8974 2023-06-20 15:04:10.363716 macrometa-source-postgres-0.0.50/macrometa_source_postgres/sync_strategies/full_table.py
--rw-r--r--   0        0        0    28063 2023-06-20 15:04:10.363716 macrometa-source-postgres-0.0.50/macrometa_source_postgres/sync_strategies/log_based.py
--rw-r--r--   0        0        0     3698 2023-06-20 15:04:10.363716 macrometa-source-postgres-0.0.50/macrometa_source_postgres/sync_strategies/sample_data.py
--rw-r--r--   0        0        0     1512 2023-06-20 15:04:10.619716 macrometa-source-postgres-0.0.50/pyproject.toml
--rw-r--r--   0        0        0     1077 1970-01-01 00:00:00.000000 macrometa-source-postgres-0.0.50/setup.py
--rw-r--r--   0        0        0      877 1970-01-01 00:00:00.000000 macrometa-source-postgres-0.0.50/PKG-INFO
+-rw-r--r--   0        0        0    11899 2023-06-28 12:48:11.776575 macrometa-source-postgres-0.0.51/LICENSE
+-rw-r--r--   0        0        0    35738 2023-06-28 12:48:11.776575 macrometa-source-postgres-0.0.51/macrometa_source_postgres/__init__.py
+-rw-r--r--   0        0        0     8690 2023-06-28 12:48:11.776575 macrometa-source-postgres-0.0.51/macrometa_source_postgres/connection.py
+-rw-r--r--   0        0        0    20349 2023-06-28 12:48:11.776575 macrometa-source-postgres-0.0.51/macrometa_source_postgres/helper.py
+-rw-r--r--   0        0        0        0 2023-06-28 12:48:11.776575 macrometa-source-postgres-0.0.51/macrometa_source_postgres/sync_strategies/__init__.py
+-rw-r--r--   0        0        0     1212 2023-06-28 12:48:11.776575 macrometa-source-postgres-0.0.51/macrometa_source_postgres/sync_strategies/common.py
+-rw-r--r--   0        0        0     8974 2023-06-28 12:48:11.776575 macrometa-source-postgres-0.0.51/macrometa_source_postgres/sync_strategies/full_table.py
+-rw-r--r--   0        0        0    28161 2023-06-28 12:48:11.776575 macrometa-source-postgres-0.0.51/macrometa_source_postgres/sync_strategies/log_based.py
+-rw-r--r--   0        0        0     3698 2023-06-28 12:48:11.776575 macrometa-source-postgres-0.0.51/macrometa_source_postgres/sync_strategies/sample_data.py
+-rw-r--r--   0        0        0     1512 2023-06-28 12:48:12.028580 macrometa-source-postgres-0.0.51/pyproject.toml
+-rw-r--r--   0        0        0     1077 1970-01-01 00:00:00.000000 macrometa-source-postgres-0.0.51/setup.py
+-rw-r--r--   0        0        0      877 1970-01-01 00:00:00.000000 macrometa-source-postgres-0.0.51/PKG-INFO
```

### Comparing `macrometa-source-postgres-0.0.50/LICENSE` & `macrometa-source-postgres-0.0.51/LICENSE`

 * *Files identical despite different names*

### Comparing `macrometa-source-postgres-0.0.50/macrometa_source_postgres/__init__.py` & `macrometa-source-postgres-0.0.51/macrometa_source_postgres/__init__.py`

 * *Files identical despite different names*

### Comparing `macrometa-source-postgres-0.0.50/macrometa_source_postgres/connection.py` & `macrometa-source-postgres-0.0.51/macrometa_source_postgres/connection.py`

 * *Files 2% similar despite different names*

```diff
@@ -126,16 +126,16 @@
     sql_datatype = sql_datatype.replace('[]', '')
 
     if elem is None:
         return elem
 
     type_cleaning_map = {
         'money': lambda: elem,
-        'json': lambda: json.loads(elem),
-        'jsonb': lambda: json.loads(elem),
+        'json': lambda: json.loads(elem) if isinstance(elem, (str, bytes, bytearray)) else elem,
+        'jsonb': lambda: json.loads(elem) if isinstance(elem, (str, bytes, bytearray)) else elem,
         'time with time zone': lambda: clean_time_with_time_zone(elem),
         'time without time zone': lambda: clean_time_without_time_zone(elem),
         'bit': lambda: elem == '1',
         'boolean': lambda: elem
     }
 
     if sql_datatype in type_cleaning_map:
```

### Comparing `macrometa-source-postgres-0.0.50/macrometa_source_postgres/helper.py` & `macrometa-source-postgres-0.0.51/macrometa_source_postgres/helper.py`

 * *Files identical despite different names*

### Comparing `macrometa-source-postgres-0.0.50/macrometa_source_postgres/sync_strategies/common.py` & `macrometa-source-postgres-0.0.51/macrometa_source_postgres/sync_strategies/common.py`

 * *Files identical despite different names*

### Comparing `macrometa-source-postgres-0.0.50/macrometa_source_postgres/sync_strategies/full_table.py` & `macrometa-source-postgres-0.0.51/macrometa_source_postgres/sync_strategies/full_table.py`

 * *Files identical despite different names*

### Comparing `macrometa-source-postgres-0.0.50/macrometa_source_postgres/sync_strategies/log_based.py` & `macrometa-source-postgres-0.0.51/macrometa_source_postgres/sync_strategies/log_based.py`

 * *Files 0% similar despite different names*

```diff
@@ -203,15 +203,18 @@
     if value is None:
         return value
 
     if sql_datatype == 'money':
         return value
 
     if sql_datatype in ['json', 'jsonb']:
-        return json.loads(value)
+        if isinstance(value, (str, bytes, bytearray)):
+            return json.loads(value)
+        else:
+            return value
 
     if sql_datatype == 'timestamp without time zone':
         if isinstance(value, datetime.datetime):
             # if max datetime is passed return fallback date
             if value > datetime.datetime(9999, 12, 31, 23, 59, 59, 999000):
                 return FALLBACK_DATETIME
```

### Comparing `macrometa-source-postgres-0.0.50/macrometa_source_postgres/sync_strategies/sample_data.py` & `macrometa-source-postgres-0.0.51/macrometa_source_postgres/sync_strategies/sample_data.py`

 * *Files identical despite different names*

### Comparing `macrometa-source-postgres-0.0.50/pyproject.toml` & `macrometa-source-postgres-0.0.51/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["poetry-core", "wheel"]
 build-backend = "poetry.core.masonry.api"
 
 [tool.poetry]
 name = "macrometa-source-postgres"
-version='0.0.50'
+version='0.0.51'
 description = "Macrometa Source for extracting data from PostgreSQL."
 license = "Apache-2.0"
 authors = ["Macrometa <info@macrometa.com>"]
 keywords = [
     "ELT",
     "Connectors",
     "Workflows",
```

### Comparing `macrometa-source-postgres-0.0.50/setup.py` & `macrometa-source-postgres-0.0.51/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -20,15 +20,15 @@
 
 entry_points = \
 {'console_scripts': ['macrometa-source-postgres = '
                      'macrometa_source_postgres:main']}
 
 setup_kwargs = {
     'name': 'macrometa-source-postgres',
-    'version': '0.0.50',
+    'version': '0.0.51',
     'description': 'Macrometa Source for extracting data from PostgreSQL.',
     'long_description': 'None',
     'author': 'Macrometa',
     'author_email': 'info@macrometa.com',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'None',
```

### Comparing `macrometa-source-postgres-0.0.50/PKG-INFO` & `macrometa-source-postgres-0.0.51/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: macrometa-source-postgres
-Version: 0.0.50
+Version: 0.0.51
 Summary: Macrometa Source for extracting data from PostgreSQL.
 License: Apache-2.0
 Keywords: ELT,Connectors,Workflows,Macrometa,PostgreSQL,Source
 Author: Macrometa
 Author-email: info@macrometa.com
 Requires-Python: >=3.8.1,<3.11
 Classifier: License :: OSI Approved :: Apache Software License
```


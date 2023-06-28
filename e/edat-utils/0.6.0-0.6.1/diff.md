# Comparing `tmp/edat_utils-0.6.0.tar.gz` & `tmp/edat_utils-0.6.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "edat_utils-0.6.0.tar", last modified: Wed Jun 28 14:09:05 2023, max compression
+gzip compressed data, was "edat_utils-0.6.1.tar", last modified: Wed Jun 28 14:34:09 2023, max compression
```

## Comparing `edat_utils-0.6.0.tar` & `edat_utils-0.6.1.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxrwxr-x   0 jorge     (1000) jorge     (1000)        0 2023-06-28 14:09:05.762204 edat_utils-0.6.0/
--rw-rw-r--   0 jorge     (1000) jorge     (1000)      515 2023-06-28 14:09:05.762204 edat_utils-0.6.0/PKG-INFO
--rw-rw-r--   0 jorge     (1000) jorge     (1000)      209 2023-06-28 13:33:29.000000 edat_utils-0.6.0/README.md
-drwxrwxr-x   0 jorge     (1000) jorge     (1000)        0 2023-06-28 14:09:05.762204 edat_utils-0.6.0/edat_utils/
--rw-rw-r--   0 jorge     (1000) jorge     (1000)        0 2023-06-28 13:33:29.000000 edat_utils-0.6.0/edat_utils/__init__.py
--rw-rw-r--   0 jorge     (1000) jorge     (1000)     1075 2023-06-28 13:33:29.000000 edat_utils-0.6.0/edat_utils/generic_controller.py
--rw-rw-r--   0 jorge     (1000) jorge     (1000)     4644 2023-06-28 14:00:19.000000 edat_utils-0.6.0/edat_utils/query_builder.py
--rw-rw-r--   0 jorge     (1000) jorge     (1000)     1091 2023-06-28 13:33:29.000000 edat_utils-0.6.0/edat_utils/query_runner.py
--rw-rw-r--   0 jorge     (1000) jorge     (1000)      971 2023-06-28 13:54:33.000000 edat_utils-0.6.0/edat_utils/schema.py
--rw-rw-r--   0 jorge     (1000) jorge     (1000)     1553 2023-06-28 13:33:29.000000 edat_utils-0.6.0/edat_utils/utils.py
-drwxrwxr-x   0 jorge     (1000) jorge     (1000)        0 2023-06-28 14:09:05.762204 edat_utils-0.6.0/edat_utils.egg-info/
--rw-rw-r--   0 jorge     (1000) jorge     (1000)      515 2023-06-28 14:09:05.000000 edat_utils-0.6.0/edat_utils.egg-info/PKG-INFO
--rw-rw-r--   0 jorge     (1000) jorge     (1000)      339 2023-06-28 14:09:05.000000 edat_utils-0.6.0/edat_utils.egg-info/SOURCES.txt
--rw-rw-r--   0 jorge     (1000) jorge     (1000)        1 2023-06-28 14:09:05.000000 edat_utils-0.6.0/edat_utils.egg-info/dependency_links.txt
--rw-rw-r--   0 jorge     (1000) jorge     (1000)       52 2023-06-28 14:09:05.000000 edat_utils-0.6.0/edat_utils.egg-info/requires.txt
--rw-rw-r--   0 jorge     (1000) jorge     (1000)       11 2023-06-28 14:09:05.000000 edat_utils-0.6.0/edat_utils.egg-info/top_level.txt
--rw-rw-r--   0 jorge     (1000) jorge     (1000)       38 2023-06-28 14:09:05.762204 edat_utils-0.6.0/setup.cfg
--rw-rw-r--   0 jorge     (1000) jorge     (1000)      832 2023-06-28 14:07:55.000000 edat_utils-0.6.0/setup.py
+drwxrwxr-x   0 jorge     (1000) jorge     (1000)        0 2023-06-28 14:34:09.663397 edat_utils-0.6.1/
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)      515 2023-06-28 14:34:09.663397 edat_utils-0.6.1/PKG-INFO
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)      209 2023-06-28 13:33:29.000000 edat_utils-0.6.1/README.md
+drwxrwxr-x   0 jorge     (1000) jorge     (1000)        0 2023-06-28 14:34:09.663397 edat_utils-0.6.1/edat_utils/
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)        0 2023-06-28 13:33:29.000000 edat_utils-0.6.1/edat_utils/__init__.py
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)     1075 2023-06-28 13:33:29.000000 edat_utils-0.6.1/edat_utils/generic_controller.py
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)     4833 2023-06-28 14:30:49.000000 edat_utils-0.6.1/edat_utils/query_builder.py
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)     1091 2023-06-28 13:33:29.000000 edat_utils-0.6.1/edat_utils/query_runner.py
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)      971 2023-06-28 14:31:14.000000 edat_utils-0.6.1/edat_utils/schema.py
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)     1553 2023-06-28 13:33:29.000000 edat_utils-0.6.1/edat_utils/utils.py
+drwxrwxr-x   0 jorge     (1000) jorge     (1000)        0 2023-06-28 14:34:09.663397 edat_utils-0.6.1/edat_utils.egg-info/
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)      515 2023-06-28 14:34:09.000000 edat_utils-0.6.1/edat_utils.egg-info/PKG-INFO
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)      339 2023-06-28 14:34:09.000000 edat_utils-0.6.1/edat_utils.egg-info/SOURCES.txt
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)        1 2023-06-28 14:34:09.000000 edat_utils-0.6.1/edat_utils.egg-info/dependency_links.txt
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)       52 2023-06-28 14:34:09.000000 edat_utils-0.6.1/edat_utils.egg-info/requires.txt
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)       11 2023-06-28 14:34:09.000000 edat_utils-0.6.1/edat_utils.egg-info/top_level.txt
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)       38 2023-06-28 14:34:09.663397 edat_utils-0.6.1/setup.cfg
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)      832 2023-06-28 14:31:56.000000 edat_utils-0.6.1/setup.py
```

### Comparing `edat_utils-0.6.0/PKG-INFO` & `edat_utils-0.6.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: edat_utils
-Version: 0.6.0
+Version: 0.6.1
 Summary: Biblioteca de Apoio ao desenvolvimento no EDAT
 Home-page: UNKNOWN
 Author: Escritório de Dados
 Author-email: dados@unicamp.br
 License: MIT
 Platform: UNKNOWN
 Classifier: Intended Audience :: Developers
```

### Comparing `edat_utils-0.6.0/edat_utils/generic_controller.py` & `edat_utils-0.6.1/edat_utils/generic_controller.py`

 * *Files identical despite different names*

### Comparing `edat_utils-0.6.0/edat_utils/query_builder.py` & `edat_utils-0.6.1/edat_utils/query_builder.py`

 * *Files 6% similar despite different names*

```diff
@@ -6,15 +6,21 @@
 
 AND = ' AND '
 COMMA_SEPARARATOR = ', '
 
 class EdatQueryBuilder:
 
     @staticmethod
-    def build_query(table: str, filter: EdatFilter, fields: List[str], pagination: EdatPagination, orders: List[EdatOrder], grouped: bool):
+    def build_query(table: str,
+                    filter: EdatFilter,
+                    fields: List[str],
+                    pagination: EdatPagination,
+                    orders: List[EdatOrder],
+                    grouped: bool,
+                    limit: int):
         
         select = []
         where = []
         group = []
         pagination_text = ''
         orderBy = []
 
@@ -74,30 +80,31 @@
                 pagination_text = pagination_text + ' LIMIT ' + str(pagination.limit)
             if pagination.offset and pagination.offset != 0:
                 pagination_text = pagination_text + ' OFFSET ' + str(pagination.offset)
 
         if orders:
             for order in orders:
                 if order.type.value.lower() == 'case':
-                    orderBy.append(order.type.value + ' ' + underline_field + ' ' + order.caseCondition.value)
+                    orderBy.append(order.type.value + ' ' + underline_field + ' ' + order.caseCondition)
                     break
                 underline_field = re.sub(
                     r'(?<!^)(?=[A-Z])', '_', order.field).lower()
                 orderBy.append(underline_field + ' ' + order.type.value)
 
-
         query = 'SELECT '
         query = query + COMMA_SEPARARATOR.join(select)
         query = query + ' FROM ' + table
         if where:
             query = query + ' WHERE '+ AND.join(where)
         if group:
             query = query + ' GROUP BY '+ COMMA_SEPARARATOR.join(group)
         if orderBy:
             query = query + ' ORDER BY ' + COMMA_SEPARARATOR.join(orderBy)
+        if limit:
+            query = query + ' LIMIT ' + limit
         query = query + pagination_text
        
         return query
 
     @staticmethod
     def __get_value(value):
         date_pattern_str = r'^\d{4}-\d{2}-\d{2}$'
```

### Comparing `edat_utils-0.6.0/edat_utils/query_runner.py` & `edat_utils-0.6.1/edat_utils/query_runner.py`

 * *Files identical despite different names*

### Comparing `edat_utils-0.6.0/edat_utils/schema.py` & `edat_utils-0.6.1/edat_utils/schema.py`

 * *Files identical despite different names*

### Comparing `edat_utils-0.6.0/edat_utils/utils.py` & `edat_utils-0.6.1/edat_utils/utils.py`

 * *Files identical despite different names*

### Comparing `edat_utils-0.6.0/edat_utils.egg-info/PKG-INFO` & `edat_utils-0.6.1/edat_utils.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: edat-utils
-Version: 0.6.0
+Version: 0.6.1
 Summary: Biblioteca de Apoio ao desenvolvimento no EDAT
 Home-page: UNKNOWN
 Author: Escritório de Dados
 Author-email: dados@unicamp.br
 License: MIT
 Platform: UNKNOWN
 Classifier: Intended Audience :: Developers
```

### Comparing `edat_utils-0.6.0/setup.py` & `edat_utils-0.6.1/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 # Always prefer setuptools over distutils
 from setuptools import setup, find_packages
 
 
 # This call to setup() does all the work
 setup(
     name="edat_utils",
-    version="0.6.0",
+    version="0.6.1",
     description="Biblioteca de Apoio ao desenvolvimento no EDAT",
     long_description="# Utilitarios EDAT <br /> Classes utilitarias utilizadas pelo EDAT.",
     long_description_content_type="text/markdown",
     author="Escritório de Dados",
     author_email="dados@unicamp.br",
     license="MIT",
     classifiers=[
```


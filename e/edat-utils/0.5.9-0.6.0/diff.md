# Comparing `tmp/edat_utils-0.5.9.tar.gz` & `tmp/edat_utils-0.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "edat_utils-0.5.9.tar", last modified: Wed Jun  7 15:25:56 2023, max compression
+gzip compressed data, was "edat_utils-0.6.0.tar", last modified: Wed Jun 28 14:09:05 2023, max compression
```

## Comparing `edat_utils-0.5.9.tar` & `edat_utils-0.6.0.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxrwxrwx   0        0        0        0 2023-06-07 15:25:56.882487 edat_utils-0.5.9/
--rw-rw-rw-   0        0        0      541 2023-06-07 15:25:56.882487 edat_utils-0.5.9/PKG-INFO
--rw-rw-rw-   0        0        0      225 2023-06-06 16:32:39.000000 edat_utils-0.5.9/README.md
-drwxrwxrwx   0        0        0        0 2023-06-07 15:25:56.880034 edat_utils-0.5.9/edat_utils/
--rw-rw-rw-   0        0        0        0 2023-06-06 14:50:10.000000 edat_utils-0.5.9/edat_utils/__init__.py
--rw-rw-rw-   0        0        0     1100 2023-06-06 14:50:10.000000 edat_utils-0.5.9/edat_utils/generic_controller.py
--rw-rw-rw-   0        0        0     4566 2023-06-07 15:23:05.000000 edat_utils-0.5.9/edat_utils/query_builder.py
--rw-rw-rw-   0        0        0     1122 2023-06-06 14:50:10.000000 edat_utils-0.5.9/edat_utils/query_runner.py
--rw-rw-rw-   0        0        0      970 2023-06-06 14:50:10.000000 edat_utils-0.5.9/edat_utils/schema.py
--rw-rw-rw-   0        0        0     1597 2023-06-06 14:50:10.000000 edat_utils-0.5.9/edat_utils/utils.py
-drwxrwxrwx   0        0        0        0 2023-06-07 15:25:56.882487 edat_utils-0.5.9/edat_utils.egg-info/
--rw-rw-rw-   0        0        0      541 2023-06-07 15:25:56.000000 edat_utils-0.5.9/edat_utils.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      339 2023-06-07 15:25:56.000000 edat_utils-0.5.9/edat_utils.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-07 15:25:56.000000 edat_utils-0.5.9/edat_utils.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       52 2023-06-07 15:25:56.000000 edat_utils-0.5.9/edat_utils.egg-info/requires.txt
--rw-rw-rw-   0        0        0       11 2023-06-07 15:25:56.000000 edat_utils-0.5.9/edat_utils.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-07 15:25:56.882487 edat_utils-0.5.9/setup.cfg
--rw-rw-rw-   0        0        0      855 2023-06-07 15:25:51.000000 edat_utils-0.5.9/setup.py
+drwxrwxr-x   0 jorge     (1000) jorge     (1000)        0 2023-06-28 14:09:05.762204 edat_utils-0.6.0/
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)      515 2023-06-28 14:09:05.762204 edat_utils-0.6.0/PKG-INFO
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)      209 2023-06-28 13:33:29.000000 edat_utils-0.6.0/README.md
+drwxrwxr-x   0 jorge     (1000) jorge     (1000)        0 2023-06-28 14:09:05.762204 edat_utils-0.6.0/edat_utils/
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)        0 2023-06-28 13:33:29.000000 edat_utils-0.6.0/edat_utils/__init__.py
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)     1075 2023-06-28 13:33:29.000000 edat_utils-0.6.0/edat_utils/generic_controller.py
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)     4644 2023-06-28 14:00:19.000000 edat_utils-0.6.0/edat_utils/query_builder.py
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)     1091 2023-06-28 13:33:29.000000 edat_utils-0.6.0/edat_utils/query_runner.py
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)      971 2023-06-28 13:54:33.000000 edat_utils-0.6.0/edat_utils/schema.py
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)     1553 2023-06-28 13:33:29.000000 edat_utils-0.6.0/edat_utils/utils.py
+drwxrwxr-x   0 jorge     (1000) jorge     (1000)        0 2023-06-28 14:09:05.762204 edat_utils-0.6.0/edat_utils.egg-info/
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)      515 2023-06-28 14:09:05.000000 edat_utils-0.6.0/edat_utils.egg-info/PKG-INFO
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)      339 2023-06-28 14:09:05.000000 edat_utils-0.6.0/edat_utils.egg-info/SOURCES.txt
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)        1 2023-06-28 14:09:05.000000 edat_utils-0.6.0/edat_utils.egg-info/dependency_links.txt
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)       52 2023-06-28 14:09:05.000000 edat_utils-0.6.0/edat_utils.egg-info/requires.txt
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)       11 2023-06-28 14:09:05.000000 edat_utils-0.6.0/edat_utils.egg-info/top_level.txt
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)       38 2023-06-28 14:09:05.762204 edat_utils-0.6.0/setup.cfg
+-rw-rw-r--   0 jorge     (1000) jorge     (1000)      832 2023-06-28 14:07:55.000000 edat_utils-0.6.0/setup.py
```

### Comparing `edat_utils-0.5.9/PKG-INFO` & `edat_utils-0.6.0/PKG-INFO`

 * *Files 22% similar despite different names*

```diff
@@ -1,15 +1,17 @@
-Metadata-Version: 2.1
-Name: edat_utils
-Version: 0.5.9
-Summary: Biblioteca de Apoio ao desenvolvimento no EDAT
-Home-page: UNKNOWN
-Author: Escritório de Dados
-Author-email: dados@unicamp.br
-License: MIT
-Description: # Utilitarios EDAT <br /> Classes utilitarias utilizadas pelo EDAT.
-Platform: UNKNOWN
-Classifier: Intended Audience :: Developers
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Programming Language :: Python
-Classifier: Operating System :: OS Independent
-Description-Content-Type: text/markdown
+Metadata-Version: 2.1
+Name: edat_utils
+Version: 0.6.0
+Summary: Biblioteca de Apoio ao desenvolvimento no EDAT
+Home-page: UNKNOWN
+Author: Escritório de Dados
+Author-email: dados@unicamp.br
+License: MIT
+Platform: UNKNOWN
+Classifier: Intended Audience :: Developers
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Programming Language :: Python
+Classifier: Operating System :: OS Independent
+Description-Content-Type: text/markdown
+
+# Utilitarios EDAT <br /> Classes utilitarias utilizadas pelo EDAT.
+
```

### Comparing `edat_utils-0.5.9/edat_utils/generic_controller.py` & `edat_utils-0.6.0/edat_utils/generic_controller.py`

 * *Ordering differences only*

 * *Files 7% similar despite different names*

```diff
@@ -1,26 +1,26 @@
-from typing import Any, Generic, TypeVar, Type
-from strawberry.types import Info
-from edat_utils.utils import EdatUtils
-from edat_utils.query_builder import EdatQueryBuilder
-from edat_utils.query_runner import EdatQueriyRunner
-from edat_utils.schema import EdatFilter, EdatGenericType, EdatPagination, EdatOrder, EdatPaginationWindow, EdatGrouped
-from typing import List
-
-T = TypeVar("T")
-
-
-class GenericController(Generic[T]):
-
-    def get(self, info:Info, filter: EdatFilter, pagination: EdatPagination = None, orders: List[EdatOrder] = None) -> EdatPaginationWindow[T]:             
-        table = EdatUtils.get_table_name(info)
-        grouped = EdatUtils.is_grouped(info)
-        fields = EdatUtils.get_fields(info)
-        user = EdatUtils.get_user(info)
-        query = EdatQueryBuilder.build_query(table, filter, fields, pagination, orders, grouped)
-        print(query)
-        rows = EdatQueriyRunner.list(query, user)
-        obj_list = EdatUtils.get_list(info, rows)
-        return EdatPaginationWindow(items=obj_list, total_items_count=len(obj_list))
-    
-
+from typing import Any, Generic, TypeVar, Type
+from strawberry.types import Info
+from edat_utils.utils import EdatUtils
+from edat_utils.query_builder import EdatQueryBuilder
+from edat_utils.query_runner import EdatQueriyRunner
+from edat_utils.schema import EdatFilter, EdatGenericType, EdatPagination, EdatOrder, EdatPaginationWindow, EdatGrouped
+from typing import List
+
+T = TypeVar("T")
+
+
+class GenericController(Generic[T]):
+
+    def get(self, info:Info, filter: EdatFilter, pagination: EdatPagination = None, orders: List[EdatOrder] = None) -> EdatPaginationWindow[T]:             
+        table = EdatUtils.get_table_name(info)
+        grouped = EdatUtils.is_grouped(info)
+        fields = EdatUtils.get_fields(info)
+        user = EdatUtils.get_user(info)
+        query = EdatQueryBuilder.build_query(table, filter, fields, pagination, orders, grouped)
+        print(query)
+        rows = EdatQueriyRunner.list(query, user)
+        obj_list = EdatUtils.get_list(info, rows)
+        return EdatPaginationWindow(items=obj_list, total_items_count=len(obj_list))
+    
+
```

### Comparing `edat_utils-0.5.9/edat_utils/query_builder.py` & `edat_utils-0.6.0/edat_utils/query_builder.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,114 +1,117 @@
-from edat_utils.schema import EdatFilter, EdatPagination, EdatOrder
-import re
-from typing import List
-import numbers
-from datetime import date
-
-AND = ' AND '
-COMMA_SEPARARATOR = ', '
-
-class EdatQueryBuilder:
-
-    @staticmethod
-    def build_query(table: str, filter: EdatFilter, fields: List[str], pagination: EdatPagination, orders: List[EdatOrder], grouped: bool):
-        
-        select = []
-        where = []
-        group = []
-        pagination_text = ''
-        orderBy = []
-
-        for key in filter:
-            value = filter[key]
-            if isinstance(value, dict):
-                for key_dict in list(value.keys()):
-                    value_dict = EdatQueryBuilder.__get_value(value[key_dict])
-
-                    match key:
-                        case 'eq':
-                            where.append(key_dict + ' = ' + value_dict)
-                        case 'ne':
-                            where.append(key_dict + ' != ' + value_dict)
-                        case 'like':
-                            where.append('lower(' + key_dict + ')' + ' LIKE ' + "lower('%" + eval(value_dict) + "%')")
-                        case 'isNull':
-                            where.append(key_dict + ' IS NULL ')
-                        case 'notNull':
-                            where.append(key_dict + ' IS NOT NULL ')
-                        case 'in':
-                            where.append(key_dict + ' IN ' + value_dict)
-                        case 'notIn':
-                            where.append(key_dict + ' NOT IN ' + value_dict)
-                        case 'lt':
-                            where.append(key_dict + ' < ' + value_dict)
-                        case 'lte':
-                            where.append(key_dict + ' <= ' + value_dict)
-                        case 'gt':
-                            where.append(key_dict + ' > ' + value_dict)
-                        case 'gte':
-                            where.append(key_dict + ' >= ' + value_dict)
-                        case _:
-                            where.append(key_dict + ' = ' + value_dict)
-            else:
-                where.append(key + ' = ' + str(value))
-
-        if grouped:
-            select.append("SUM(contador) as contador")
-            for field in fields:
-                if field == 'contador':
-                    continue
-                underline_field = re.sub(
-                    r'(?<!^)(?=[A-Z])', '_', field).lower()
-                select.append(underline_field)
-                group.append(underline_field)
-        else:
-            for field in fields:
-                if field == 'contador':
-                    continue
-                underline_field = re.sub(
-                    r'(?<!^)(?=[A-Z])', '_', field).lower()
-                select.append(underline_field)
-
-        if pagination:
-            if pagination.limit and pagination.limit != 0:
-                pagination_text = pagination_text + ' LIMIT ' + str(pagination.limit)
-            if pagination.offset and pagination.offset != 0:
-                pagination_text = pagination_text + ' OFFSET ' + str(pagination.offset)
-
-        if orders:
-            for order in orders:
-                underline_field = re.sub(
-                    r'(?<!^)(?=[A-Z])', '_', order.field).lower()
-                orderBy.append(underline_field + ' ' + order.type.value)
-
-
-        query = 'SELECT '
-        query = query + COMMA_SEPARARATOR.join(select)
-        query = query + ' FROM ' + table
-        if where:
-            query = query + ' WHERE '+ AND.join(where)
-        if group:
-            query = query + ' GROUP BY '+ COMMA_SEPARARATOR.join(group)
-        if orderBy:
-            query = query + ' ORDER BY ' + COMMA_SEPARARATOR.join(orderBy)
-        query = query + pagination_text
-       
-        return query
-
-    @staticmethod
-    def __get_value(value):
-        date_pattern_str = r'^\d{4}-\d{2}-\d{2}$'
-        if isinstance(value, numbers.Number):
-            return str(value)
-        elif isinstance(value, str):
-            if re.match(date_pattern_str, value):
-                return "date '" + value + "'"
-            else:
-                return "'" + value + "'"
-        elif isinstance(value, list) or isinstance(value, dict):
-            if isinstance(value[0], str):
-                return "('" + "', '".join(value) + "')"
-            else:
-                return "(" + ", ".join(map(str, value)) + ")"
-        else: 
-            return value
+from edat_utils.schema import EdatFilter, EdatPagination, EdatOrder
+import re
+from typing import List
+import numbers
+from datetime import date
+
+AND = ' AND '
+COMMA_SEPARARATOR = ', '
+
+class EdatQueryBuilder:
+
+    @staticmethod
+    def build_query(table: str, filter: EdatFilter, fields: List[str], pagination: EdatPagination, orders: List[EdatOrder], grouped: bool):
+        
+        select = []
+        where = []
+        group = []
+        pagination_text = ''
+        orderBy = []
+
+        for key in filter:
+            value = filter[key]
+            if isinstance(value, dict):
+                for key_dict in list(value.keys()):
+                    value_dict = EdatQueryBuilder.__get_value(value[key_dict])
+
+                    match key:
+                        case 'eq':
+                            where.append(key_dict + ' = ' + value_dict)
+                        case 'ne':
+                            where.append(key_dict + ' != ' + value_dict)
+                        case 'like':
+                            where.append('lower(' + key_dict + ')' + ' LIKE ' + "lower('%" + eval(value_dict) + "%')")
+                        case 'isNull':
+                            where.append(key_dict + ' IS NULL ')
+                        case 'notNull':
+                            where.append(key_dict + ' IS NOT NULL ')
+                        case 'in':
+                            where.append(key_dict + ' IN ' + value_dict)
+                        case 'notIn':
+                            where.append(key_dict + ' NOT IN ' + value_dict)
+                        case 'lt':
+                            where.append(key_dict + ' < ' + value_dict)
+                        case 'lte':
+                            where.append(key_dict + ' <= ' + value_dict)
+                        case 'gt':
+                            where.append(key_dict + ' > ' + value_dict)
+                        case 'gte':
+                            where.append(key_dict + ' >= ' + value_dict)
+                        case _:
+                            where.append(key_dict + ' = ' + value_dict)
+            else:
+                where.append(key + ' = ' + str(value))
+
+        if grouped:
+            select.append("SUM(contador) as contador")
+            for field in fields:
+                if field == 'contador':
+                    continue
+                underline_field = re.sub(
+                    r'(?<!^)(?=[A-Z])', '_', field).lower()
+                select.append(underline_field)
+                group.append(underline_field)
+        else:
+            for field in fields:
+                if field == 'contador':
+                    continue
+                underline_field = re.sub(
+                    r'(?<!^)(?=[A-Z])', '_', field).lower()
+                select.append(underline_field)
+
+        if pagination:
+            if pagination.limit and pagination.limit != 0:
+                pagination_text = pagination_text + ' LIMIT ' + str(pagination.limit)
+            if pagination.offset and pagination.offset != 0:
+                pagination_text = pagination_text + ' OFFSET ' + str(pagination.offset)
+
+        if orders:
+            for order in orders:
+                if order.type.value.lower() == 'case':
+                    orderBy.append(order.type.value + ' ' + underline_field + ' ' + order.caseCondition.value)
+                    break
+                underline_field = re.sub(
+                    r'(?<!^)(?=[A-Z])', '_', order.field).lower()
+                orderBy.append(underline_field + ' ' + order.type.value)
+
+
+        query = 'SELECT '
+        query = query + COMMA_SEPARARATOR.join(select)
+        query = query + ' FROM ' + table
+        if where:
+            query = query + ' WHERE '+ AND.join(where)
+        if group:
+            query = query + ' GROUP BY '+ COMMA_SEPARARATOR.join(group)
+        if orderBy:
+            query = query + ' ORDER BY ' + COMMA_SEPARARATOR.join(orderBy)
+        query = query + pagination_text
+       
+        return query
+
+    @staticmethod
+    def __get_value(value):
+        date_pattern_str = r'^\d{4}-\d{2}-\d{2}$'
+        if isinstance(value, numbers.Number):
+            return str(value)
+        elif isinstance(value, str):
+            if re.match(date_pattern_str, value):
+                return "date '" + value + "'"
+            else:
+                return "'" + value + "'"
+        elif isinstance(value, list) or isinstance(value, dict):
+            if isinstance(value[0], str):
+                return "('" + "', '".join(value) + "')"
+            else:
+                return "(" + ", ".join(map(str, value)) + ")"
+        else: 
+            return value
```

### Comparing `edat_utils-0.5.9/edat_utils/query_runner.py` & `edat_utils-0.6.0/edat_utils/query_runner.py`

 * *Ordering differences only*

 * *Files 11% similar despite different names*

```diff
@@ -1,31 +1,31 @@
-from sqlalchemy import create_engine
-from trino.auth import BasicAuthentication
-from decouple import config
-from sqlalchemy.sql.expression import text
-
-class EdatQueriyRunner:
-
-    @staticmethod
-    def unique_result(query:str, user: str):
-        connection = EdatQueriyRunner.__get_connection(user)
-        return connection.execute(text(query)).one()
-
-    @staticmethod
-    def list(query:str, user: str) :
-        connection = EdatQueriyRunner.__get_connection(user)
-        return connection.execute(text(query)).fetchall()
-    
-    @staticmethod
-    def __get_connection(user: str):
-        engine = create_engine(
-            f"trino://{config('TRINO_URL')}/{config('TRINO_CATALOG')}/{config('TRINO_SCHEMA')}",
-            echo=False,
-            connect_args={
-                "http_scheme": "https",
-                "auth": BasicAuthentication(config("TRINO_USERNAME"), config("TRINO_PASSWD")),
-                "extra_credential": [('a.username', user if user else config("TRINO_USERNAME"))]
-            },
-        )
-
-        connection = engine.connect()
-        return connection
+from sqlalchemy import create_engine
+from trino.auth import BasicAuthentication
+from decouple import config
+from sqlalchemy.sql.expression import text
+
+class EdatQueriyRunner:
+
+    @staticmethod
+    def unique_result(query:str, user: str):
+        connection = EdatQueriyRunner.__get_connection(user)
+        return connection.execute(text(query)).one()
+
+    @staticmethod
+    def list(query:str, user: str) :
+        connection = EdatQueriyRunner.__get_connection(user)
+        return connection.execute(text(query)).fetchall()
+    
+    @staticmethod
+    def __get_connection(user: str):
+        engine = create_engine(
+            f"trino://{config('TRINO_URL')}/{config('TRINO_CATALOG')}/{config('TRINO_SCHEMA')}",
+            echo=False,
+            connect_args={
+                "http_scheme": "https",
+                "auth": BasicAuthentication(config("TRINO_USERNAME"), config("TRINO_PASSWD")),
+                "extra_credential": [('a.username', user if user else config("TRINO_USERNAME"))]
+            },
+        )
+
+        connection = engine.connect()
+        return connection
```

### Comparing `edat_utils-0.5.9/edat_utils/utils.py` & `edat_utils-0.6.0/edat_utils/utils.py`

 * *Ordering differences only*

 * *Files 21% similar despite different names*

```diff
@@ -1,45 +1,45 @@
-from strawberry.types import Info
-import re
-from sqlalchemy.engine.row import Row
-from typing import List
-from edat_utils.schema import EdatGrouped
-
-EDAT_USER = 'X-EDAT-USER'
-
-
-class EdatUtils:
-    @staticmethod
-    def get_fields(info: Info):
-        selected_fields = {item.name for field in info.selected_fields
-                           for selection in field.selections for item in selection.selections}
-        return selected_fields
-    
-    @staticmethod
-    def get_user(info: Info):
-        request = info.context['request']
-        user =  None
-        if EDAT_USER in request.headers:
-            user = request.headers[EDAT_USER]
-        return user
-    
-    def get_table_name(info: Info):
-        name = list(info.return_type.__dict__['_type_definition'].type_var_map.values())[0].__name__
-        return re.sub(r'(?<!^)(?=[A-Z])', '_', name).lower()
-    
-
-    def get_list(info: Info, rows: List[Row]):
-        obj_list = []
-
-        class_ = list(info.return_type.__dict__['_type_definition'].type_var_map.values())[0]
-        args = class_.__init__.__code__.co_varnames[1:]
-
-        for row in rows:
-            params = row._asdict()
-            params_to_pass = {argname: params[argname] if argname in params else None  for argname in args}    
-            instance = class_(**params_to_pass)
-            obj_list.append(instance)
-        return obj_list
-    
-    def is_grouped(info: Info):
-        class_ = list(info.return_type.__dict__['_type_definition'].type_var_map.values())[0]
+from strawberry.types import Info
+import re
+from sqlalchemy.engine.row import Row
+from typing import List
+from edat_utils.schema import EdatGrouped
+
+EDAT_USER = 'X-EDAT-USER'
+
+
+class EdatUtils:
+    @staticmethod
+    def get_fields(info: Info):
+        selected_fields = {item.name for field in info.selected_fields
+                           for selection in field.selections for item in selection.selections}
+        return selected_fields
+    
+    @staticmethod
+    def get_user(info: Info):
+        request = info.context['request']
+        user =  None
+        if EDAT_USER in request.headers:
+            user = request.headers[EDAT_USER]
+        return user
+    
+    def get_table_name(info: Info):
+        name = list(info.return_type.__dict__['_type_definition'].type_var_map.values())[0].__name__
+        return re.sub(r'(?<!^)(?=[A-Z])', '_', name).lower()
+    
+
+    def get_list(info: Info, rows: List[Row]):
+        obj_list = []
+
+        class_ = list(info.return_type.__dict__['_type_definition'].type_var_map.values())[0]
+        args = class_.__init__.__code__.co_varnames[1:]
+
+        for row in rows:
+            params = row._asdict()
+            params_to_pass = {argname: params[argname] if argname in params else None  for argname in args}    
+            instance = class_(**params_to_pass)
+            obj_list.append(instance)
+        return obj_list
+    
+    def is_grouped(info: Info):
+        class_ = list(info.return_type.__dict__['_type_definition'].type_var_map.values())[0]
         return issubclass(class_, EdatGrouped)
```

### Comparing `edat_utils-0.5.9/edat_utils.egg-info/PKG-INFO` & `edat_utils-0.6.0/edat_utils.egg-info/PKG-INFO`

 * *Files 21% similar despite different names*

```diff
@@ -1,15 +1,17 @@
-Metadata-Version: 2.1
-Name: edat-utils
-Version: 0.5.9
-Summary: Biblioteca de Apoio ao desenvolvimento no EDAT
-Home-page: UNKNOWN
-Author: Escritório de Dados
-Author-email: dados@unicamp.br
-License: MIT
-Description: # Utilitarios EDAT <br /> Classes utilitarias utilizadas pelo EDAT.
-Platform: UNKNOWN
-Classifier: Intended Audience :: Developers
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Programming Language :: Python
-Classifier: Operating System :: OS Independent
-Description-Content-Type: text/markdown
+Metadata-Version: 2.1
+Name: edat-utils
+Version: 0.6.0
+Summary: Biblioteca de Apoio ao desenvolvimento no EDAT
+Home-page: UNKNOWN
+Author: Escritório de Dados
+Author-email: dados@unicamp.br
+License: MIT
+Platform: UNKNOWN
+Classifier: Intended Audience :: Developers
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Programming Language :: Python
+Classifier: Operating System :: OS Independent
+Description-Content-Type: text/markdown
+
+# Utilitarios EDAT <br /> Classes utilitarias utilizadas pelo EDAT.
+
```


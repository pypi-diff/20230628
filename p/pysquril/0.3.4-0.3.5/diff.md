# Comparing `tmp/pysquril-0.3.4.tar.gz` & `tmp/pysquril-0.3.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pysquril-0.3.4.tar", max compression
+gzip compressed data, was "pysquril-0.3.5.tar", max compression
```

## Comparing `pysquril-0.3.4.tar` & `pysquril-0.3.5.tar`

### file list

```diff
@@ -1,9 +1,10 @@
--rw-r--r--   0        0        0      524 2023-06-28 07:51:43.894245 pysquril-0.3.4/pyproject.toml
--rw-r--r--   0        0        0        0 2022-06-22 08:13:57.003868 pysquril-0.3.4/pysquril/__init__.py
--rw-r--r--   0        0        0    25249 2023-06-27 13:10:47.568080 pysquril-0.3.4/pysquril/backends.py
--rw-r--r--   0        0        0      326 2023-06-27 12:18:06.880308 pysquril-0.3.4/pysquril/exc.py
--rw-r--r--   0        0        0    21254 2023-06-20 11:11:42.555715 pysquril-0.3.4/pysquril/generator.py
--rw-r--r--   0        0        0     9497 2023-06-28 07:49:02.019482 pysquril-0.3.4/pysquril/parser.py
--rw-r--r--   0        0        0     1997 2022-11-21 13:00:47.589558 pysquril-0.3.4/pysquril/test_data.py
--rw-r--r--   0        0        0    21429 2023-06-27 13:10:47.569189 pysquril-0.3.4/pysquril/tests.py
--rw-r--r--   0        0        0      658 1970-01-01 00:00:00.000000 pysquril-0.3.4/PKG-INFO
+-rw-r--r--   0        0        0      168 2023-06-28 09:44:50.951276 pysquril-0.3.5/README.md
+-rw-r--r--   0        0        0      545 2023-06-28 09:44:50.951276 pysquril-0.3.5/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-28 09:44:50.951276 pysquril-0.3.5/pysquril/__init__.py
+-rw-r--r--   0        0        0    25536 2023-06-28 09:44:50.951276 pysquril-0.3.5/pysquril/backends.py
+-rw-r--r--   0        0        0      326 2023-06-28 09:44:50.951276 pysquril-0.3.5/pysquril/exc.py
+-rw-r--r--   0        0        0    21254 2023-06-28 09:44:50.951276 pysquril-0.3.5/pysquril/generator.py
+-rw-r--r--   0        0        0     9570 2023-06-28 09:44:50.951276 pysquril-0.3.5/pysquril/parser.py
+-rw-r--r--   0        0        0     1997 2023-06-28 09:44:50.951276 pysquril-0.3.5/pysquril/test_data.py
+-rw-r--r--   0        0        0    21714 2023-06-28 09:44:50.951276 pysquril-0.3.5/pysquril/tests.py
+-rw-r--r--   0        0        0      868 1970-01-01 00:00:00.000000 pysquril-0.3.5/PKG-INFO
```

### Comparing `pysquril-0.3.4/pyproject.toml` & `pysquril-0.3.5/pyproject.toml`

 * *Files 10% similar despite different names*

```diff
@@ -1,11 +1,12 @@
 [tool.poetry]
 name = "pysquril"
-version = "0.3.4"
+version = "0.3.5"
 description = "Python implementation of structured URI query language"
+readme = "README.md"
 repository = "https://github.com/unioslo/pysquril"
 authors = [
     "Leon du Toit <l.c.d.toit@usit.uio.no>",
     "Eirik Haatveit <haatveit@uio.no>",
 ]
 
 [tool.poetry.dependencies]
```

### Comparing `pysquril-0.3.4/pysquril/backends.py` & `pysquril-0.3.5/pysquril/backends.py`

 * *Files 2% similar despite different names*

```diff
@@ -65,33 +65,34 @@
         self.identity = identity
         self.timestamp = datetime.datetime.now().isoformat()
         self.transaction_id = self._id()
 
     def _id(self) -> str:
         return str(uuid4())
 
-    def _event(self, diff: Any, previous: Any, event: str) -> dict:
+    def _event(self, diff: Any, previous: Any, event: str, query: str) -> dict:
         return {
             "diff": diff,
             "previous": previous,
             "event": event,
             "timestamp": self.timestamp,
             "identity": self.identity,
             "event_id": self._id(),
             "transaction_id": self.transaction_id,
+            "query": query,
         }
 
-    def event_update(self, *, diff: Any, previous: Any) -> dict:
-        return self._event(diff, previous, "update")
+    def event_update(self, *, diff: Any, previous: Any, query: str) -> dict:
+        return self._event(diff, previous, "update", query)
 
-    def event_delete(self, *, diff: Any, previous: Any) -> dict:
-        return self._event(diff, previous, "delete")
+    def event_delete(self, *, diff: Any, previous: Any, query: str) -> dict:
+        return self._event(diff, previous, "delete", query)
 
-    def event_restore(self, *, diff: Any, previous: Any) -> dict:
-        return self._event(diff, previous, "restore")
+    def event_restore(self, *, diff: Any, previous: Any, query: str) -> dict:
+        return self._event(diff, previous, "restore", query)
 
 
 class DatabaseBackend(ABC):
 
     sep: str # schema separator character
 
     def __init__(
@@ -273,44 +274,45 @@
         with session_func(self.engine) as session:
             for entry in target_data:
                 target_entry = entry.get("previous")
                 pk_value = self._get_pk_value(primary_key, target_entry) if target_entry else None
                 if pk_value in handled or entry.get("event") == "restore":
                     continue
                 target_entry = entry.get("previous")
-                pk_value = target_entry.get(primary_key)
                 result = list(
                     self.table_select(
                         table_name,
                         f"where={primary_key}=eq.{pk_value}",
                     )
                 )
                 if len(result) > 1:
                     raise DataIntegrityError(f"primary_key: {primary_key} is not unique")
                 elif not result:
                     # then it is currently deleted
                     self.table_insert(table_name, target_entry, session)
                     self.table_insert(
                         f"{table_name}_audit",
-                        tsc.event_restore(diff=target_entry, previous=None),
+                        tsc.event_restore(diff=target_entry, previous=None, query=uri_query),
                         session,
                     )
                     work_done["restores"].append(entry)
                 else:
                     current_entry = result[0]
                     diff = self._diff_entries(current_entry, target_entry)
                     if diff:
+                        # note: query construction depends on the constraint
+                        # that only top-level keys are allowed in set operations
                         self.table_update(
                             table_name,
                             f"set={','.join(diff.keys())}&where={primary_key}=eq.{pk_value}",
                             data=diff,
                             tsc=tsc,
                             session=session,
                         )
-                    work_done["updates"].append(entry)
+                        work_done["updates"].append(entry)
                 handled.append(pk_value)
         return work_done
 
 
 class SqliteBackend(GenericBackend):
 
     """
@@ -447,30 +449,30 @@
         data: dict,
         tsc: Optional[AuditTransaction] = None,
         session: Optional[sqlite3.Cursor] = None,
     ) -> bool:
         audit_data = []
         tsc = AuditTransaction(self.requestor) if not tsc else tsc
         for val in self.table_select(table_name, uri_query, data=data):
-            audit_data.append(tsc.event_update(diff=data, previous=val))
+            audit_data.append(tsc.event_update(diff=data, previous=val, query=uri_query))
         sql = self.generator_class(f'"{self.schema}{self.sep}{table_name}"', uri_query, data=data)
         if session:
             session.execute(sql.update_query)
             self.table_insert(f'{table_name}_audit', audit_data, session)
         else:
             with sqlite_session(self.engine) as session:
                 session.execute(sql.update_query)
             self.table_insert(f'{table_name}_audit', audit_data)
         return True
 
     def table_delete(self, table_name: str, uri_query: str) -> bool:
         audit_data = []
         tsc = AuditTransaction(self.requestor)
         for row in self.table_select(table_name, uri_query):
-            audit_data.append(tsc.event_delete(diff=None, previous=row))
+            audit_data.append(tsc.event_delete(diff=None, previous=row, query=uri_query))
         sql = self.generator_class(f'"{self.schema}{self.sep}{table_name}"', uri_query)
         with sqlite_session(self.engine) as session:
             session.execute(sql.delete_query)
             if not table_name.endswith("_audit"):
                 self.table_create(f'{table_name}_audit', session)
                 self.table_insert(f'{table_name}_audit', audit_data, session)
         return True
@@ -635,30 +637,30 @@
         data: dict,
         tsc: Optional[AuditTransaction] = None,
         session: Optional[psycopg2.extensions.cursor] = None,
     ) -> bool:
         audit_data = []
         tsc = AuditTransaction(self.requestor) if not tsc else tsc
         for val in self.table_select(table_name, uri_query, data=data):
-            audit_data.append(tsc.event_update(diff=data, previous=val))
+            audit_data.append(tsc.event_update(diff=data, previous=val, query=uri_query))
         sql = self.generator_class(f'{self.schema}{self.sep}"{table_name}"', uri_query, data=data)
         if session:
             session.execute(sql.update_query)
             self.table_insert(f'{table_name}_audit', audit_data, session)
         else:
             with postgres_session(self.engine) as session:
                 session.execute(sql.update_query)
             self.table_insert(f'{table_name}_audit', audit_data)
         return True
 
     def table_delete(self, table_name: str, uri_query: str) -> bool:
         audit_data = []
         tsc = AuditTransaction(self.requestor)
         for row in self.table_select(table_name, uri_query):
-            audit_data.append(tsc.event_delete(diff=None, previous=row))
+            audit_data.append(tsc.event_delete(diff=None, previous=row, query=uri_query))
         sql = self.generator_class(f'{self.schema}{self.sep}"{table_name}"', uri_query)
         with postgres_session(self.engine) as session:
             session.execute(sql.delete_query)
             if not table_name.endswith("_audit"):
                 self.table_create(f'{table_name}_audit', session)
                 self.table_insert(f'{table_name}_audit', audit_data, session)
         return True
```

### Comparing `pysquril-0.3.4/pysquril/generator.py` & `pysquril-0.3.5/pysquril/generator.py`

 * *Files identical despite different names*

### Comparing `pysquril-0.3.4/pysquril/parser.py` & `pysquril-0.3.5/pysquril/parser.py`

 * *Files 0% similar despite different names*

```diff
@@ -227,14 +227,15 @@
 class SetElement(object):
 
     def __init__(self, term: str) -> None:
         self.select_term = SelectTerm(term)
         if not isinstance(self.select_term.parsed[0], Key):
             raise ParseError(f'{term} must be an instance of Key')
         if not len(self.select_term.parsed) == 1:
+            # note: relaxing this would require changes to table_restore
             raise ParseError(f'SetElements can only be top level keys - {term} is nested')
 
 
 class SetTerm(object):
 
     def __init__(self, original: str) -> None:
         self.original = original
```

### Comparing `pysquril-0.3.4/pysquril/test_data.py` & `pysquril-0.3.5/pysquril/test_data.py`

 * *Files identical despite different names*

### Comparing `pysquril-0.3.4/pysquril/tests.py` & `pysquril-0.3.5/pysquril/tests.py`

 * *Files 2% similar despite different names*

```diff
@@ -422,14 +422,15 @@
         audit_event = result[0]
         self.assertEqual(audit_event["previous"], data)
         self.assertEqual(audit_event["diff"], new_data)
         self.assertEqual(audit_event["event"], "update")
         self.assertTrue(audit_event["transaction_id"] is not None)
         self.assertTrue(audit_event["event_id"] is not None)
         self.assertTrue(audit_event["timestamp"] is not None)
+        self.assertTrue(audit_event["query"] is not None)
 
         # restore updates
         with self.assertRaises(ParseError): # missing restore directive
             self.backend.table_restore(table_name=test_table, uri_query="")
         with self.assertRaises(ParseError): # missing primary key
             self.backend.table_restore(table_name=test_table, uri_query="restore")
         with self.assertRaises(ParseError): # still missing primary key
@@ -494,21 +495,27 @@
         # automatic audit table creation on delete
         # use a nested primary key, to test restores with such keys
         some_data = {"pk": {"id": 0}, "lol": None, "cat": [1, 2]}
         some_more_data = {"pk": {"id": 1}, "neither-lol-not-not-lol": None, "cat": []}
         some_table = "yay"
         self.backend.table_insert(table_name=some_table, data=some_data)
         self.backend.table_insert(table_name=some_table, data=some_more_data)
+        self.backend.table_update(
+            table_name=some_table,
+            uri_query=f"set=lol&where=pk.id=eq.0",
+            data={"lol": "wat"},
+        )
         self.backend.table_delete(table_name=some_table, uri_query="")
         audit = list(self.backend.table_select(table_name=f"{some_table}_audit", uri_query=""))
-        self.assertTrue(len(audit), 2)
+        self.assertTrue(len(audit), 3)
         nested_result = self.backend.table_restore(
             table_name=some_table, uri_query=f"restore&primary_key=pk.id"
         )
         self.assertEqual(len(nested_result.get("restores")), 2)
+        self.assertEqual(len(nested_result.get("updates")), 0)
         self.backend.table_delete(table_name=f"{some_table}_audit", uri_query="")
 
 
 class TestSqliteBackend(TestSqlBackend):
     __test__ = True
 
     def setUp(self) -> None:
```


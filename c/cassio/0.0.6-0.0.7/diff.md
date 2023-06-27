# Comparing `tmp/cassio-0.0.6.tar.gz` & `tmp/cassio-0.0.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "cassio-0.0.6.tar", last modified: Fri Jun 23 21:55:06 2023, max compression
+gzip compressed data, was "cassio-0.0.7.tar", last modified: Tue Jun 27 22:37:28 2023, max compression
```

## Comparing `cassio-0.0.6.tar` & `cassio-0.0.7.tar`

### file list

```diff
@@ -1,33 +1,35 @@
-drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-23 21:55:06.293569 cassio-0.0.6/
--rw-rw-r--   0 stefano   (1000) stefano   (1000)     2520 2023-06-23 21:55:06.293569 cassio-0.0.6/PKG-INFO
--rw-rw-r--   0 stefano   (1000) stefano   (1000)     1084 2023-06-16 14:11:44.000000 cassio-0.0.6/README.md
--rw-rw-r--   0 stefano   (1000) stefano   (1000)       78 2023-06-23 21:55:06.293569 cassio-0.0.6/setup.cfg
--rw-rw-r--   0 stefano   (1000) stefano   (1000)     1606 2023-06-23 13:27:58.000000 cassio-0.0.6/setup.py
-drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-23 21:55:06.293569 cassio-0.0.6/src/
-drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-23 21:55:06.293569 cassio-0.0.6/src/cassio/
--rw-rw-r--   0 stefano   (1000) stefano   (1000)       93 2023-06-16 15:56:04.000000 cassio-0.0.6/src/cassio/__init__.py
-drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-23 21:55:06.293569 cassio-0.0.6/src/cassio/cql/
--rw-rw-r--   0 stefano   (1000) stefano   (1000)     2384 2023-06-16 14:33:36.000000 cassio-0.0.6/src/cassio/cql/__init__.py
-drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-23 21:55:06.293569 cassio-0.0.6/src/cassio/db_extractor/
--rw-rw-r--   0 stefano   (1000) stefano   (1000)       71 2023-05-30 22:40:16.000000 cassio-0.0.6/src/cassio/db_extractor/__init__.py
--rw-rw-r--   0 stefano   (1000) stefano   (1000)     3001 2023-06-16 14:33:36.000000 cassio-0.0.6/src/cassio/db_extractor/cassandra_extractor.py
-drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-23 21:55:06.293569 cassio-0.0.6/src/cassio/history/
--rw-rw-r--   0 stefano   (1000) stefano   (1000)       64 2023-05-23 00:11:06.000000 cassio-0.0.6/src/cassio/history/__init__.py
--rw-rw-r--   0 stefano   (1000) stefano   (1000)     1622 2023-06-19 12:49:19.000000 cassio-0.0.6/src/cassio/history/history_management.py
-drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-23 21:55:06.293569 cassio-0.0.6/src/cassio/keyvalue/
--rw-rw-r--   0 stefano   (1000) stefano   (1000)       45 2023-05-23 14:40:40.000000 cassio-0.0.6/src/cassio/keyvalue/__init__.py
--rw-rw-r--   0 stefano   (1000) stefano   (1000)     2377 2023-06-16 14:33:36.000000 cassio-0.0.6/src/cassio/keyvalue/kv_cache.py
-drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-23 21:55:06.293569 cassio-0.0.6/src/cassio/utils/
--rw-rw-r--   0 stefano   (1000) stefano   (1000)       48 2023-06-16 14:11:47.000000 cassio-0.0.6/src/cassio/utils/__init__.py
-drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-23 21:55:06.293569 cassio-0.0.6/src/cassio/utils/vector/
--rw-rw-r--   0 stefano   (1000) stefano   (1000)       65 2023-06-16 14:11:47.000000 cassio-0.0.6/src/cassio/utils/vector/__init__.py
--rw-rw-r--   0 stefano   (1000) stefano   (1000)     2554 2023-06-16 14:11:47.000000 cassio-0.0.6/src/cassio/utils/vector/distance_metrics.py
-drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-23 21:55:06.293569 cassio-0.0.6/src/cassio/vector/
--rw-rw-r--   0 stefano   (1000) stefano   (1000)       55 2023-06-16 14:11:47.000000 cassio-0.0.6/src/cassio/vector/__init__.py
--rw-rw-r--   0 stefano   (1000) stefano   (1000)     7071 2023-06-23 21:43:46.000000 cassio-0.0.6/src/cassio/vector/vector_db_driver.py
-drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-23 21:55:06.293569 cassio-0.0.6/src/cassio.egg-info/
--rw-rw-r--   0 stefano   (1000) stefano   (1000)     2520 2023-06-23 21:55:06.000000 cassio-0.0.6/src/cassio.egg-info/PKG-INFO
--rw-rw-r--   0 stefano   (1000) stefano   (1000)      643 2023-06-23 21:55:06.000000 cassio-0.0.6/src/cassio.egg-info/SOURCES.txt
--rw-rw-r--   0 stefano   (1000) stefano   (1000)        1 2023-06-23 21:55:06.000000 cassio-0.0.6/src/cassio.egg-info/dependency_links.txt
--rw-rw-r--   0 stefano   (1000) stefano   (1000)       36 2023-06-23 21:55:06.000000 cassio-0.0.6/src/cassio.egg-info/requires.txt
--rw-rw-r--   0 stefano   (1000) stefano   (1000)        7 2023-06-23 21:55:06.000000 cassio-0.0.6/src/cassio.egg-info/top_level.txt
+drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-27 22:37:28.491624 cassio-0.0.7/
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)     2125 2023-06-27 22:37:28.491624 cassio-0.0.7/PKG-INFO
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)     1084 2023-06-24 13:16:41.000000 cassio-0.0.7/README.md
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)       78 2023-06-27 22:37:28.495624 cassio-0.0.7/setup.cfg
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)     1606 2023-06-27 22:37:09.000000 cassio-0.0.7/setup.py
+drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-27 22:37:28.491624 cassio-0.0.7/src/
+drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-27 22:37:28.491624 cassio-0.0.7/src/cassio/
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)       93 2023-06-26 22:16:09.000000 cassio-0.0.7/src/cassio/__init__.py
+drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-27 22:37:28.491624 cassio-0.0.7/src/cassio/cql/
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)     2366 2023-06-27 22:37:09.000000 cassio-0.0.7/src/cassio/cql/__init__.py
+drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-27 22:37:28.491624 cassio-0.0.7/src/cassio/db_extractor/
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)       71 2023-05-20 20:25:59.000000 cassio-0.0.7/src/cassio/db_extractor/__init__.py
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)     3001 2023-06-24 13:16:41.000000 cassio-0.0.7/src/cassio/db_extractor/cassandra_extractor.py
+drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-27 22:37:28.491624 cassio-0.0.7/src/cassio/history/
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)       64 2023-06-14 20:54:50.000000 cassio-0.0.7/src/cassio/history/__init__.py
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)     1622 2023-06-24 13:16:41.000000 cassio-0.0.7/src/cassio/history/history_management.py
+drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-27 22:37:28.491624 cassio-0.0.7/src/cassio/keyvalue/
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)       45 2023-06-14 20:54:50.000000 cassio-0.0.7/src/cassio/keyvalue/__init__.py
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)     2377 2023-06-24 13:16:41.000000 cassio-0.0.7/src/cassio/keyvalue/kv_cache.py
+drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-27 22:37:28.491624 cassio-0.0.7/src/cassio/utils/
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)       48 2023-06-24 13:16:41.000000 cassio-0.0.7/src/cassio/utils/__init__.py
+drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-27 22:37:28.491624 cassio-0.0.7/src/cassio/utils/vector/
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)       65 2023-06-24 13:16:41.000000 cassio-0.0.7/src/cassio/utils/vector/__init__.py
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)     2554 2023-06-24 13:16:41.000000 cassio-0.0.7/src/cassio/utils/vector/distance_metrics.py
+drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-27 22:37:28.491624 cassio-0.0.7/src/cassio/vector/
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)       55 2023-06-24 13:16:41.000000 cassio-0.0.7/src/cassio/vector/__init__.py
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)     6469 2023-06-27 22:37:09.000000 cassio-0.0.7/src/cassio/vector/vector_db_driver.py
+drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-27 22:37:28.491624 cassio-0.0.7/src/cassio.egg-info/
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)     2125 2023-06-27 22:37:28.000000 cassio-0.0.7/src/cassio.egg-info/PKG-INFO
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)      665 2023-06-27 22:37:28.000000 cassio-0.0.7/src/cassio.egg-info/SOURCES.txt
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)        1 2023-06-27 22:37:28.000000 cassio-0.0.7/src/cassio.egg-info/dependency_links.txt
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)       36 2023-06-27 22:37:28.000000 cassio-0.0.7/src/cassio.egg-info/requires.txt
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)        7 2023-06-27 22:37:28.000000 cassio-0.0.7/src/cassio.egg-info/top_level.txt
+drwxrwxr-x   0 stefano   (1000) stefano   (1000)        0 2023-06-27 22:37:28.491624 cassio-0.0.7/tests/
+-rw-rw-r--   0 stefano   (1000) stefano   (1000)      249 2023-06-24 13:16:41.000000 cassio-0.0.7/tests/test_example.py
```

### Comparing `cassio-0.0.6/PKG-INFO` & `cassio-0.0.7/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,64 +1,15 @@
 Metadata-Version: 2.1
 Name: cassio
-Version: 0.0.6
+Version: 0.0.7
 Summary: A framework-agnostic Python library to seamlessly integrate Apache Cassandra with ML/LLM/genAI workloads.
 Home-page: https://github.com/hemidactylus/cassio
 Author: Stefano Lottini
 Author-email: stefano.lottini@datastax.com
 License: LICENSE.txt
-Description: # cassIO
-        
-        A framework-agnostic Python library to seamlessly integrate Apache Cassandra with ML/LLM/genAI workloads.
-        
-        **Note**: this is currently an alpha release.
-        
-        ## Users
-        
-        Installation is as simple as:
-        
-        ```
-        pip install cassio
-        ```
-        
-        For example usages and integration with higher-level LLM frameworks
-        such as LangChain, please visit [cassio.org](https://cassio.org).
-        
-        ## CassIO developers
-        
-        ### Developing
-        
-        To develop `cassio`, use the `requirements-dev.txt`.
-        
-        To use the dev version in an integration (e.g. your branch of LangChain),
-        
-        - `pip install -e .` in this `cassio` repo;
-        - `pip install -e .` in the LangChain `cassio` branch of [this fork](https://github.com/hemidactylus/langchain/tree/cassio);
-        - plus any additional requirement files specific to the examples
-        you're running (such as Jupyter).
-        
-        ### Publishing
-        
-        ```
-        # (bump version & commit ...)
-        python setup.py sdist bdist_wheel
-        twine upload dist/*
-        # (login to PyPI ...)
-        ```
-        
-        ### Unit testing
-        
-        In a virtualenv with the `requirements-dev.txt` installed, run:
-        
-        ```
-        pytest
-        ```
-        
-        (there's not ... much yet in the way of testing).
-        
 Keywords: cassandra,ai,llm
 Platform: UNKNOWN
 Classifier: Development Status :: 2 - Pre-Alpha
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
@@ -67,7 +18,58 @@
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Programming Language :: Python :: 3.12
 Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Topic :: Scientific/Engineering
 Classifier: Topic :: Scientific/Engineering :: Artificial Intelligence
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
+
+# cassIO
+
+A framework-agnostic Python library to seamlessly integrate Apache Cassandra with ML/LLM/genAI workloads.
+
+**Note**: this is currently an alpha release.
+
+## Users
+
+Installation is as simple as:
+
+```
+pip install cassio
+```
+
+For example usages and integration with higher-level LLM frameworks
+such as LangChain, please visit [cassio.org](https://cassio.org).
+
+## CassIO developers
+
+### Developing
+
+To develop `cassio`, use the `requirements-dev.txt`.
+
+To use the dev version in an integration (e.g. your branch of LangChain),
+
+- `pip install -e .` in this `cassio` repo;
+- `pip install -e .` in the LangChain `cassio` branch of [this fork](https://github.com/hemidactylus/langchain/tree/cassio);
+- plus any additional requirement files specific to the examples
+you're running (such as Jupyter).
+
+### Publishing
+
+```
+# (bump version & commit ...)
+python setup.py sdist bdist_wheel
+twine upload dist/*
+# (login to PyPI ...)
+```
+
+### Unit testing
+
+In a virtualenv with the `requirements-dev.txt` installed, run:
+
+```
+pytest
+```
+
+(there's not ... much yet in the way of testing).
+
+
```

### Comparing `cassio-0.0.6/README.md` & `cassio-0.0.7/README.md`

 * *Files identical despite different names*

### Comparing `cassio-0.0.6/setup.py` & `cassio-0.0.7/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import setup, find_packages
 import pathlib
 
 here = pathlib.Path(__file__).parent.resolve()
 
 setup(
     name='cassio',
-    version='0.0.6',
+    version='0.0.7',
     author='Stefano Lottini',
     author_email='stefano.lottini@datastax.com',
     package_dir={"": "src"},
     packages=find_packages(where='src'),
     # entry_points={
     #     "console_scripts": [
     #         # will we ever have a command-line cassio script?
```

### Comparing `cassio-0.0.6/src/cassio/cql/__init__.py` & `cassio-0.0.7/src/cassio/cql/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 create_vector_table = """
 CREATE TABLE IF NOT EXISTS {keyspace}.{table} (
-    document_id {idType} PRIMARY KEY,
-    embedding_vector VECTOR<FLOAT, {embeddingDimension}>,
+    document_id {key_type} PRIMARY KEY,
+    embedding_vector VECTOR<FLOAT, {embedding_dimension}>,
     document TEXT,
     metadata_blob TEXT
 )
 """
 create_vector_table_index = """
 CREATE CUSTOM INDEX IF NOT EXISTS {indexName} ON {keyspace}.{table} (embedding_vector)
 USING 'org.apache.cassandra.index.sai.StorageAttachedIndex' ;
@@ -13,15 +13,15 @@
 store_cached_vss_item = """
 INSERT INTO {keyspace}.{table} (
     document_id,
     embedding_vector,
     document,
     metadata_blob
 ) VALUES (
-    {documentIdPlaceholder},
+    %s,
     %s,
     %s,
     %s
 ){ttlSpec}
 """
 get_vector_table_item = """
 SELECT
```

### Comparing `cassio-0.0.6/src/cassio/db_extractor/cassandra_extractor.py` & `cassio-0.0.7/src/cassio/db_extractor/cassandra_extractor.py`

 * *Files identical despite different names*

### Comparing `cassio-0.0.6/src/cassio/history/history_management.py` & `cassio-0.0.7/src/cassio/history/history_management.py`

 * *Files identical despite different names*

### Comparing `cassio-0.0.6/src/cassio/keyvalue/kv_cache.py` & `cassio-0.0.7/src/cassio/keyvalue/kv_cache.py`

 * *Files identical despite different names*

### Comparing `cassio-0.0.6/src/cassio/utils/vector/distance_metrics.py` & `cassio-0.0.7/src/cassio/utils/vector/distance_metrics.py`

 * *Files identical despite different names*

### Comparing `cassio-0.0.6/src/cassio/vector/vector_db_driver.py` & `cassio-0.0.7/src/cassio/vector/vector_db_driver.py`

 * *Files 8% similar despite different names*

```diff
@@ -39,89 +39,81 @@
             table=self.table
         ))
         return self.session.execute(st).one().count
 
 
 class VectorTable(VectorMixin):
 
-    def __init__(self, session: Session, keyspace: str, table: str, embedding_dimension: int, auto_id: bool):
+    def __init__(self,
+                 session: Session,
+                 keyspace: str,
+                 table: str,
+                 embedding_dimension: int,
+                 primary_key_type: str = 'UUID'):
         self.session = session
         self.keyspace = keyspace
         self.table = table
         self.embedding_dimension = embedding_dimension
         #
-        self.auto_id = auto_id
-        #
-        self._create_table()
+        self._create_table(primary_key_type)
         self._create_index()
 
     def put(self,
             document: str,
             embedding_vector: List[float],
-            document_id: Optional[str],
+            document_id: Any,
             metadata: JSONType,
             ttl_seconds: int) -> None:
         self._put(False, document, embedding_vector, document_id, metadata, ttl_seconds)
 
     def put_async(self,
                   document: str,
                   embedding_vector: List[float],
-                  document_id: Optional[str],
+                  document_id: Any,
                   metadata: JSONType,
                   ttl_seconds: int) -> ResponseFuture:
         return self._put(True, document, embedding_vector, document_id, metadata, ttl_seconds)
 
     def _put(self,
              is_async: bool,
              document: str,
              embedding_vector: List[float],
-             document_id: Optional[str],
+             document_id: Any,
              metadata: JSONType,
              ttl_seconds: int) -> Optional[ResponseFuture]:
-        # document_id, if not autoID, must be str
-        if not self.auto_id and document_id is None:
-            raise ValueError('\'document_id\' must be specified unless autoID')
-        if self.auto_id and document_id is not None:
-            raise ValueError('\'document_id\' cannot be passes if autoID')
         if ttl_seconds:
             ttl_spec = f' USING TTL {ttl_seconds}'
         else:
             ttl_spec = ''
         st = SimpleStatement(cassio.cql.store_cached_vss_item.format(
             keyspace=self.keyspace,
             table=self.table,
-            documentIdPlaceholder='now()' if self.auto_id else '%s',
             ttlSpec=ttl_spec,
         ))
         metadata_blob = json.dumps(metadata)
-        # depending on autoID, the size of the values tuple changes:
-        values0 = (embedding_vector, document, metadata_blob)
-        values = values0 if self.auto_id else tuple([document_id] + list(values0))
+        values = (document_id, embedding_vector, document, metadata_blob)
         if is_async:
             return self.session.execute_async(st, values)
         else:
             return self.session.execute(st, values)
 
-    def get(self, document_id: str) -> Dict[str, Any]:
-        if self.auto_id:
-            raise ValueError('\'get\' not supported if autoID')
+    def get(self, document_id: Any) -> Optional[Dict[str, Any]]:
+        st = SimpleStatement(cassio.cql.get_vector_table_item.format(
+            keyspace=self.keyspace,
+            table=self.table,
+        ))
+        params = (document_id, )
+        hits = self.session.execute(st, params)
+        hit = hits.one()
+        if hit:
+            return VectorTable._jsonify_hit(hit, distance=None)
         else:
-            st = SimpleStatement(cassio.cql.get_vector_table_item.format(
-                keyspace=self.keyspace,
-                table=self.table,
-            ))
-            params = (document_id, )
-            hits = self.session.execute(st, params)
-            hit = hits.one()
-            if hit:
-                return VectorTable._jsonify_hit(hit, distance=None)
-            else:
-                return None
+            return None
 
-    def delete(self, document_id: str) -> None:
+    def delete(self, document_id: Any) -> None:
         """This operation goes through even if the row does not exist."""
         st = SimpleStatement(cassio.cql.delete_vector_table_item.format(
             keyspace=self.keyspace,
             table=self.table,
         ))
         params = (document_id, )
         self.session.execute(st, params)
@@ -181,15 +173,15 @@
     def clear(self) -> None:
         st = SimpleStatement(cassio.cql.truncate_vector_table.format(
             keyspace=self.keyspace,
             table=self.table,
         ))
         self.session.execute(st)
 
-    def _create_table(self) -> None:
+    def _create_table(self, primary_key_type: str) -> None:
         st = SimpleStatement(cassio.cql.create_vector_table.format(
             keyspace=self.keyspace,
             table=self.table,
-            idType='UUID' if self.auto_id else 'TEXT',
-            embeddingDimension=self.embedding_dimension,
+            key_type=primary_key_type,
+            embedding_dimension=self.embedding_dimension,
         ))
         self.session.execute(st)
```

### Comparing `cassio-0.0.6/src/cassio.egg-info/PKG-INFO` & `cassio-0.0.7/src/cassio.egg-info/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,64 +1,15 @@
 Metadata-Version: 2.1
 Name: cassio
-Version: 0.0.6
+Version: 0.0.7
 Summary: A framework-agnostic Python library to seamlessly integrate Apache Cassandra with ML/LLM/genAI workloads.
 Home-page: https://github.com/hemidactylus/cassio
 Author: Stefano Lottini
 Author-email: stefano.lottini@datastax.com
 License: LICENSE.txt
-Description: # cassIO
-        
-        A framework-agnostic Python library to seamlessly integrate Apache Cassandra with ML/LLM/genAI workloads.
-        
-        **Note**: this is currently an alpha release.
-        
-        ## Users
-        
-        Installation is as simple as:
-        
-        ```
-        pip install cassio
-        ```
-        
-        For example usages and integration with higher-level LLM frameworks
-        such as LangChain, please visit [cassio.org](https://cassio.org).
-        
-        ## CassIO developers
-        
-        ### Developing
-        
-        To develop `cassio`, use the `requirements-dev.txt`.
-        
-        To use the dev version in an integration (e.g. your branch of LangChain),
-        
-        - `pip install -e .` in this `cassio` repo;
-        - `pip install -e .` in the LangChain `cassio` branch of [this fork](https://github.com/hemidactylus/langchain/tree/cassio);
-        - plus any additional requirement files specific to the examples
-        you're running (such as Jupyter).
-        
-        ### Publishing
-        
-        ```
-        # (bump version & commit ...)
-        python setup.py sdist bdist_wheel
-        twine upload dist/*
-        # (login to PyPI ...)
-        ```
-        
-        ### Unit testing
-        
-        In a virtualenv with the `requirements-dev.txt` installed, run:
-        
-        ```
-        pytest
-        ```
-        
-        (there's not ... much yet in the way of testing).
-        
 Keywords: cassandra,ai,llm
 Platform: UNKNOWN
 Classifier: Development Status :: 2 - Pre-Alpha
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
@@ -67,7 +18,58 @@
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Programming Language :: Python :: 3.12
 Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Topic :: Scientific/Engineering
 Classifier: Topic :: Scientific/Engineering :: Artificial Intelligence
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
+
+# cassIO
+
+A framework-agnostic Python library to seamlessly integrate Apache Cassandra with ML/LLM/genAI workloads.
+
+**Note**: this is currently an alpha release.
+
+## Users
+
+Installation is as simple as:
+
+```
+pip install cassio
+```
+
+For example usages and integration with higher-level LLM frameworks
+such as LangChain, please visit [cassio.org](https://cassio.org).
+
+## CassIO developers
+
+### Developing
+
+To develop `cassio`, use the `requirements-dev.txt`.
+
+To use the dev version in an integration (e.g. your branch of LangChain),
+
+- `pip install -e .` in this `cassio` repo;
+- `pip install -e .` in the LangChain `cassio` branch of [this fork](https://github.com/hemidactylus/langchain/tree/cassio);
+- plus any additional requirement files specific to the examples
+you're running (such as Jupyter).
+
+### Publishing
+
+```
+# (bump version & commit ...)
+python setup.py sdist bdist_wheel
+twine upload dist/*
+# (login to PyPI ...)
+```
+
+### Unit testing
+
+In a virtualenv with the `requirements-dev.txt` installed, run:
+
+```
+pytest
+```
+
+(there's not ... much yet in the way of testing).
+
+
```

### Comparing `cassio-0.0.6/src/cassio.egg-info/SOURCES.txt` & `cassio-0.0.7/src/cassio.egg-info/SOURCES.txt`

 * *Files 9% similar despite different names*

```diff
@@ -14,8 +14,9 @@
 src/cassio/history/history_management.py
 src/cassio/keyvalue/__init__.py
 src/cassio/keyvalue/kv_cache.py
 src/cassio/utils/__init__.py
 src/cassio/utils/vector/__init__.py
 src/cassio/utils/vector/distance_metrics.py
 src/cassio/vector/__init__.py
-src/cassio/vector/vector_db_driver.py
+src/cassio/vector/vector_db_driver.py
+tests/test_example.py
```


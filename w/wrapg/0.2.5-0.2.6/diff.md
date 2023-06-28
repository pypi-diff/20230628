# Comparing `tmp/wrapg-0.2.5.tar.gz` & `tmp/wrapg-0.2.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "wrapg-0.2.5.tar", last modified: Wed Aug 24 00:23:18 2022, max compression
+gzip compressed data, was "wrapg-0.2.6.tar", last modified: Wed Jun 28 00:17:51 2023, max compression
```

## Comparing `wrapg-0.2.5.tar` & `wrapg-0.2.6.tar`

### file list

```diff
@@ -1,18 +1,23 @@
-drwxrwxrwx   0        0        0        0 2022-08-24 00:23:18.296926 wrapg-0.2.5/
--rw-rw-rw-   0        0        0     1089 2022-03-24 23:23:27.000000 wrapg-0.2.5/LICENSE
--rw-rw-rw-   0        0        0       64 2022-04-05 19:00:41.000000 wrapg-0.2.5/MANIFEST.in
--rw-rw-rw-   0        0        0     6113 2022-08-24 00:23:18.297896 wrapg-0.2.5/PKG-INFO
--rw-rw-rw-   0        0        0     5417 2022-08-17 00:09:19.000000 wrapg-0.2.5/README.md
--rw-rw-rw-   0        0        0      152 2022-08-14 20:04:05.000000 wrapg-0.2.5/pyproject.toml
--rw-rw-rw-   0        0        0      845 2022-08-24 00:23:18.305896 wrapg-0.2.5/setup.cfg
-drwxrwxrwx   0        0        0        0 2022-08-24 00:23:18.226897 wrapg-0.2.5/wrapg/
--rw-rw-rw-   0        0        0      303 2022-04-18 23:27:00.000000 wrapg-0.2.5/wrapg/__init__.py
--rw-rw-rw-   0        0        0    12532 2022-08-20 14:36:56.000000 wrapg-0.2.5/wrapg/snippet.py
--rw-rw-rw-   0        0        0     5628 2022-08-14 20:04:05.000000 wrapg-0.2.5/wrapg/util.py
--rw-rw-rw-   0        0        0    30986 2022-08-21 17:58:00.000000 wrapg-0.2.5/wrapg/wrapg.py
-drwxrwxrwx   0        0        0        0 2022-08-24 00:23:18.294932 wrapg-0.2.5/wrapg.egg-info/
--rw-rw-rw-   0        0        0     6113 2022-08-24 00:23:18.000000 wrapg-0.2.5/wrapg.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      262 2022-08-24 00:23:18.000000 wrapg-0.2.5/wrapg.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2022-08-24 00:23:18.000000 wrapg-0.2.5/wrapg.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       38 2022-08-24 00:23:18.000000 wrapg-0.2.5/wrapg.egg-info/requires.txt
--rw-rw-rw-   0        0        0        6 2022-08-24 00:23:18.000000 wrapg-0.2.5/wrapg.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 00:17:51.531217 wrapg-0.2.6/
+-rw-rw-rw-   0        0        0     1089 2022-03-24 23:23:27.000000 wrapg-0.2.6/LICENSE
+-rw-rw-rw-   0        0        0       64 2022-04-05 19:00:41.000000 wrapg-0.2.6/MANIFEST.in
+-rw-rw-rw-   0        0        0     6113 2023-06-28 00:17:51.532201 wrapg-0.2.6/PKG-INFO
+-rw-rw-rw-   0        0        0     5417 2022-08-17 00:09:19.000000 wrapg-0.2.6/README.md
+-rw-rw-rw-   0        0        0      152 2022-08-14 20:04:05.000000 wrapg-0.2.6/pyproject.toml
+-rw-rw-rw-   0        0        0      845 2023-06-28 00:17:51.536194 wrapg-0.2.6/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 00:17:51.451206 wrapg-0.2.6/tests/
+-rw-rw-rw-   0        0        0     2467 2022-08-24 00:11:04.000000 wrapg-0.2.6/tests/test_snippet_funcs.py
+-rw-rw-rw-   0        0        0     3723 2022-08-24 00:10:58.000000 wrapg-0.2.6/tests/test_upsert.py
+-rw-rw-rw-   0        0        0     2105 2022-08-24 00:11:17.000000 wrapg-0.2.6/tests/test_util_funcs.py
+-rw-rw-rw-   0        0        0     4045 2022-08-24 00:11:21.000000 wrapg-0.2.6/tests/test_wrapg_funcs.py
+drwxrwxrwx   0        0        0        0 2023-06-28 00:17:51.485192 wrapg-0.2.6/wrapg/
+-rw-rw-rw-   0        0        0      303 2022-04-18 23:27:00.000000 wrapg-0.2.6/wrapg/__init__.py
+-rw-rw-rw-   0        0        0    12532 2022-08-20 14:36:56.000000 wrapg-0.2.6/wrapg/snippet.py
+-rw-rw-rw-   0        0        0     5628 2022-08-14 20:04:05.000000 wrapg-0.2.6/wrapg/util.py
+-rw-rw-rw-   0        0        0    32571 2023-06-28 00:16:22.000000 wrapg-0.2.6/wrapg/wrapg.py
+drwxrwxrwx   0        0        0        0 2023-06-28 00:17:51.528205 wrapg-0.2.6/wrapg.egg-info/
+-rw-rw-rw-   0        0        0     6113 2023-06-28 00:17:51.000000 wrapg-0.2.6/wrapg.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      362 2023-06-28 00:17:51.000000 wrapg-0.2.6/wrapg.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 00:17:51.000000 wrapg-0.2.6/wrapg.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       38 2023-06-28 00:17:51.000000 wrapg-0.2.6/wrapg.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 00:17:51.000000 wrapg-0.2.6/wrapg.egg-info/top_level.txt
```

### Comparing `wrapg-0.2.5/LICENSE` & `wrapg-0.2.6/LICENSE`

 * *Files identical despite different names*

### Comparing `wrapg-0.2.5/PKG-INFO` & `wrapg-0.2.6/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: wrapg
-Version: 0.2.5
+Version: 0.2.6
 Summary: Wrapper around psycopg3 using easy functions to interact with postgres.
 Home-page: https://github.com/jturnercode/wrapg
 Author: jturnercode
 Author-email: jturner.code@gmail.com
 Project-URL: Bug Tracker, https://github.com/jturnercode/wrapg/issues
 Project-URL: Source Code, https://github.com/jturnercode/wrapg
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `wrapg-0.2.5/README.md` & `wrapg-0.2.6/README.md`

 * *Files identical despite different names*

### Comparing `wrapg-0.2.5/setup.cfg` & `wrapg-0.2.6/setup.cfg`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 00000000: 5b6d 6574 6164 6174 615d 0d0a 6e61 6d65  [metadata]..name
 00000010: 203d 2077 7261 7067 0d0a 7665 7273 696f   = wrapg..versio
-00000020: 6e20 3d20 302e 322e 350d 0a61 7574 686f  n = 0.2.5..autho
+00000020: 6e20 3d20 302e 322e 360d 0a61 7574 686f  n = 0.2.6..autho
 00000030: 7220 3d20 6a74 7572 6e65 7263 6f64 650d  r = jturnercode.
 00000040: 0a61 7574 686f 725f 656d 6169 6c20 3d20  .author_email = 
 00000050: 6a74 7572 6e65 722e 636f 6465 4067 6d61  jturner.code@gma
 00000060: 696c 2e63 6f6d 0d0a 6465 7363 7269 7074  il.com..descript
 00000070: 696f 6e20 3d20 5772 6170 7065 7220 6172  ion = Wrapper ar
 00000080: 6f75 6e64 2070 7379 636f 7067 3320 7573  ound psycopg3 us
 00000090: 696e 6720 6561 7379 2066 756e 6374 696f  ing easy functio
```

### Comparing `wrapg-0.2.5/wrapg/snippet.py` & `wrapg-0.2.6/wrapg/snippet.py`

 * *Files identical despite different names*

### Comparing `wrapg-0.2.5/wrapg/util.py` & `wrapg-0.2.6/wrapg/util.py`

 * *Files identical despite different names*

### Comparing `wrapg-0.2.5/wrapg/wrapg.py` & `wrapg-0.2.6/wrapg/wrapg.py`

 * *Files 2% similar despite different names*

```diff
@@ -51,15 +51,14 @@
     # Set default return type (row factory) to dictionary, can be overwritten with kwargs
     conn_final = {"row_factory": psycopg.rows.dict_row, **conn_import, **conn_kwargs}
 
     # Connect to an existing database
     with psycopg.connect(**conn_final) as conn:
         # Open a cursor to perform database operations
         with conn.cursor() as cur:
-
             # Pass raw_sql to execute()
             # example: cur.execute("SELECT * FROM tablename WHERE id = 4")
             cur.execute(query=raw_sql)
 
             # Used for testing output of raw_sql
             # print("rowcount: ", cur.rowcount)
             # print("statusmessage: ", cur.statusmessage)
@@ -72,15 +71,14 @@
                     return pd.DataFrame(cur, dtype="object")
 
                 # Save memory return iterator
                 return iter(cur.fetchall())
 
 
 def insert(data: Iterable[dict] | pd.DataFrame, table: str, conn_kwargs: dict = None):
-
     """Function for SQL's INSERT
 
     Add a row(s) into specified table
 
     Args:
         data (Iterable[dict] | pd.DataFrame): data in form of dict, list of dict, or dataframe
         table (str): name of database table
@@ -97,18 +95,16 @@
         conn_kwargs = {}
 
     # Final conn args to pass to connect()
     conn_final = {**conn_import, **conn_kwargs}
 
     # Connect to an existing database
     with psycopg.connect(**conn_final) as conn:
-
         # Open a cursor to perform database operations
         with conn.cursor() as cur:
-
             # Typ insert statement format
             # INSERT INTO table (col1, col2) VALUES (300, "vehicles");
 
             if uniform == 1:
                 # Dynamic insert query for dictionaries
                 insert_qry = snippet.insert_snip(table=table, columns=columns)
                 # print(insert_qry.as_string(conn))
@@ -164,18 +160,16 @@
 
     # Final conn parameters to pass to connect()
     # Set return default type to dictionary, can be overwritten with kwargs
     conn_final = {**conn_import, **conn_kwargs}
 
     # Connect to an existing database
     with psycopg.connect(**conn_final) as conn:
-
         # Open a cursor to perform database operations
         with conn.cursor() as cur:
-
             # =================== Ignore_Insert Qry ==================
             # INSERT INTO table (name, email)
             # VALUES('Dave','dave@yahoo.com')
             # ON CONFLICT (name)
             # DO NOTHING;
 
             try:
@@ -244,15 +238,15 @@
     data: Iterable[dict] | pd.DataFrame,
     table: str,
     keys: Iterable,
     exclude_update: Iterable = None,
     use_index: bool = True,
     conn_kwargs: dict = None,
 ):
-# TODO: should we have auto_index for auto create index & use_index for determing if index should be used?
+    # TODO: should we have auto_index for auto create index & use_index for determing if index should be used?
     """Function for SQL's INSERT ON CONFLICT DO UPDATE SET
 
     Add a row into specified table if the row with specified keys does not already exist.
     If rows with matching keys exist, update row values.
     Automatically creates unique index if one does not exist for keys provided.
 
     Args:
@@ -276,18 +270,16 @@
 
     # Final conn parameters to pass to connect()
     # Set return default type to dictionary, can be overwritten with kwargs
     conn_final = {**conn_import, **conn_kwargs}
 
     # Connect to an existing database
     with psycopg.connect(**conn_final) as conn:
-
         # Open a cursor to perform database operations
         with conn.cursor() as cur:
-
             # =================== Upsert Qry ==================
             # INSERT INTO table (name, email)
             # VALUES('Dave','dave@yahoo.com')
             # ON CONFLICT (name)
             # DO UPDATE SET email=excluded.email
             # WHERE ...;
 
@@ -370,22 +362,20 @@
 
                 # Handle all other exceptions
                 except Exception as ee:
                     print("Exception: ", ee.__init__)
                     quit()
 
             if use_index is False:
-
                 # If use_index is False
                 # First attempt to update data, confirm result
                 # If no update, then insert record
 
                 # Process uniform data without index
                 if uniform == 1:
-
                     # Update qry for uniform data
                     update_qry = snippet.update_snip(
                         table=table,
                         columns=columns,
                         keys=keys,
                         exclude_update=exclude_update,
                     )
@@ -437,15 +427,14 @@
                         )
                         # print(update_qry.as_string(conn))
                         cur.execute(query=update_qry, params=row)
                         rw_count += cur.rowcount
 
                         # if no update then insert record
                         if cur.rowcount == 0:
-
                             # Dynamic insert query for dictionaries
                             insert_qry = snippet.insert_snip(
                                 table=table, columns=tuple(row)
                             )
                             cur.execute(query=insert_qry, params=row)
 
                             rw_count += cur.rowcount
@@ -489,18 +478,16 @@
 
     # Final conn parameters to pass to connect()
     # Set return default type to dictionary, can be overwritten with kwargs
     conn_final = {**conn_import, **conn_kwargs}
 
     # Connect to an existing database
     with psycopg.connect(**conn_final) as conn:
-
         # Open a cursor to perform database operations
         with conn.cursor() as cur:
-
             # =================== Update Qry ===================
             # UPDATE table_name
             # SET column1 = value1,
             #     column2 = value2,
             #     ...
             # WHERE column = value, ...
             # RETURNING * | output_expression AS output_name;
@@ -565,15 +552,14 @@
     # Set default return type (row factory) to dictionary, can be overwritten with kwargs
     conn_final = {**conn_import, **conn_kwargs}
 
     # Connect to an existing database
     with psycopg.connect(**conn_final) as conn:
         # Open a cursor to perform database operations
         with conn.cursor() as cur:
-
             # TODO: Add optional table constriants to function
             # =================== Create Table Qry ===================
             # CREATE TABLE [IF NOT EXISTS] table_name (
             # column1 datatype(length) column_contraint,
             # column2 datatype(length) column_contraint,
             # column3 datatype(length) column_contraint,
             # table_constraints
@@ -584,14 +570,15 @@
                 """Create psycopg composable sql string for
                 defining columns within postgres table
                 ie column_name datatype(length) column_constriant
 
                 Args:
                     column_pairs (Iterable): column names
                 """
+
                 # function used to map to column names
                 def col_sql(col, value):
                     # return sql.SQL(f'"{col}" {value.upper()}')
                     return sql.SQL("{} {}").format(
                         sql.Identifier(col), sql.SQL(value.upper())
                     )
 
@@ -605,14 +592,60 @@
 
             cur.execute(query=qry)
 
             # Make the changes to the database persistent
             conn.commit()
 
 
+def create_database(name: str, conn_kwargs: dict = None):
+    """Function creating database.
+
+    Args:
+        name (str): name of database
+        conn_kwargs (dict, optional): Specify/overide conn kwargs. See full list of options,
+        https://www.postgresql.org/docs/current/libpq-connect.html#LIBPQ-PARAMKEYWORDS.
+        Defaults to None, recommend importing via .env file.
+
+    Example:
+        create_table(name="mydb")
+
+    Returns:
+        _type_: None
+    """
+
+    # Initialize conn_kwargs to empty dict if no arguments passed
+    # Merge args into conn_final
+    if conn_kwargs is None:
+        conn_kwargs = {}
+
+    # Final connection args to pass to connect()
+    # Set default return type (row factory) to dictionary, can be overwritten with kwargs
+    # dbname must equal None for connection string, db does not exist yet
+    conn_final = {**conn_import, **conn_kwargs, **{"dbname": None}}
+
+    # Connect to an existing database
+    with psycopg.connect(**conn_final) as conn:
+        # required for create database
+        conn.autocommit = True
+
+        # Open a cursor to perform database operations
+        with conn.cursor() as cur:
+            # TODO: Add optional table constriants to function
+            # =================== Create Table Qry ===================
+            # CREATE DATABASE db_name;
+
+            qry = sql.SQL("CREATE DATABASE {};").format(sql.Identifier(name))
+            # print(qry.as_string(conn))
+
+            cur.execute(query=qry)
+
+            # Make the changes to the database persistent
+            conn.commit()
+
+
 def copy_from_csv(
     table: str,
     csv_file: str,
     header: bool = False,
     block_size=50_000,
     conn_kwargs: dict = None,
 ):
@@ -642,15 +675,14 @@
     # Set default return type (row factory) to dictionary, can be overwritten with kwargs
     conn_final = {**conn_import, **conn_kwargs}
 
     # Connect to an existing database
     with psycopg.connect(**conn_final) as conn:
         # Open a cursor to perform database operations
         with conn.cursor() as cur:
-
             #! SPECIFIC COLUMNS NOT WORKING; Open ticket with pyscopg?
             # =================== Copy Qry ===================
             # "COPY cust (name, age) FROM STDIN WITH (FORMAT csv)"
 
             # If csv has header
             if header:
                 copy_sql = sql.SQL(
@@ -665,15 +697,14 @@
                 # copy_sql = sql.SQL("COPY {} FROM STDIN").format(sql.Identifier(table))
 
             with open(csv_file, "r") as f:
                 # see postgres copy options
                 # https://www.postgresql.org/docs/current/sql-copy.html
 
                 with cur.copy(copy_sql) as copy:
-
                     # Using blocks/chunks
                     while data := f.read(block_size):
                         copy.write(data)
 
                     # # Use write_row() for list(tuples) or iterable of sequences
                     # #! Do not specify COPY options such as FORMAT CSV, DELIMITER, NULL
                     # t = [("bill", 50, "here"), ("ronnie", 50, "there")]
@@ -706,18 +737,16 @@
 
     # Final conn parameters to pass to connect()
     # Set return default type to dictionary, can be overwritten with kwargs
     conn_final = {**conn_import, **conn_kwargs}
 
     # Connect to an existing database
     with psycopg.connect(**conn_final) as conn:
-
         # Open a cursor to perform database operations
         with conn.cursor() as cur:
-
             # =================== Delete Qry ===================
             # DELETE FROM table_name
             # WHERE condition---> id = 7 and badge in (2,4)
             # RETURNING (select_list | *);
 
             qry = snippet.delete_snip(table=table, where=where)
             # print(qry.as_string(conn))
@@ -746,18 +775,16 @@
 
     # Final conn parameters to pass to connect()
     # Set return default type to dictionary, can be overwritten with kwargs
     conn_final = {**conn_import, **conn_kwargs}
 
     # Connect to an existing database
     with psycopg.connect(**conn_final) as conn:
-
         # Open a cursor to perform database operations
         with conn.cursor() as cur:
-
             # =================== Delete ALL Records Qry ===================
             # DELETE FROM table_name;
 
             qry = sql.SQL("DELETE FROM {};").format(sql.Identifier(table))
             # print(qry.as_string(conn))
 
             cur.execute(query=qry)
```

### Comparing `wrapg-0.2.5/wrapg.egg-info/PKG-INFO` & `wrapg-0.2.6/wrapg.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: wrapg
-Version: 0.2.5
+Version: 0.2.6
 Summary: Wrapper around psycopg3 using easy functions to interact with postgres.
 Home-page: https://github.com/jturnercode/wrapg
 Author: jturnercode
 Author-email: jturner.code@gmail.com
 Project-URL: Bug Tracker, https://github.com/jturnercode/wrapg/issues
 Project-URL: Source Code, https://github.com/jturnercode/wrapg
 Classifier: License :: OSI Approved :: MIT License
```


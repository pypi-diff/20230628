# Comparing `tmp/bs_db_migration-0.1.1.tar.gz` & `tmp/bs_db_migration-0.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "bs_db_migration-0.1.1.tar", last modified: Wed Jun 28 11:01:27 2023, max compression
+gzip compressed data, was "bs_db_migration-0.1.2.tar", last modified: Wed Jun 28 11:13:51 2023, max compression
```

## Comparing `bs_db_migration-0.1.1.tar` & `bs_db_migration-0.1.2.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 jinwonchoi   (501) staff       (20)        0 2023-06-28 11:01:27.656758 bs_db_migration-0.1.1/
--rw-r--r--   0 jinwonchoi   (501) staff       (20)     1063 2023-02-03 01:32:29.000000 bs_db_migration-0.1.1/LICENSE
--rw-r--r--   0 jinwonchoi   (501) staff       (20)      639 2023-06-28 11:01:27.656883 bs_db_migration-0.1.1/PKG-INFO
--rw-r--r--   0 jinwonchoi   (501) staff       (20)     6745 2023-06-28 10:34:56.000000 bs_db_migration-0.1.1/README.md
--rw-r--r--   0 jinwonchoi   (501) staff       (20)       79 2023-06-28 11:01:27.657203 bs_db_migration-0.1.1/setup.cfg
--rw-r--r--   0 jinwonchoi   (501) staff       (20)     1064 2023-06-28 11:01:22.000000 bs_db_migration-0.1.1/setup.py
-drwxr-xr-x   0 jinwonchoi   (501) staff       (20)        0 2023-06-28 11:01:27.654166 bs_db_migration-0.1.1/src/
-drwxr-xr-x   0 jinwonchoi   (501) staff       (20)        0 2023-06-28 11:01:27.655750 bs_db_migration-0.1.1/src/bs_db_migration/
--rw-r--r--   0 jinwonchoi   (501) staff       (20)       22 2023-06-28 10:43:43.000000 bs_db_migration-0.1.1/src/bs_db_migration/__init__.py
--rw-r--r--   0 jinwonchoi   (501) staff       (20)     2262 2023-06-28 08:46:10.000000 bs_db_migration-0.1.1/src/bs_db_migration/config.py
--rw-r--r--   0 jinwonchoi   (501) staff       (20)      240 2023-06-28 06:29:21.000000 bs_db_migration-0.1.1/src/bs_db_migration/domain_dictionary.py
--rw-r--r--   0 jinwonchoi   (501) staff       (20)    22596 2023-06-28 10:04:25.000000 bs_db_migration-0.1.1/src/bs_db_migration/ms2postgres.py
--rw-r--r--   0 jinwonchoi   (501) staff       (20)     3259 2023-06-28 08:46:05.000000 bs_db_migration-0.1.1/src/bs_db_migration/ms2postgres_type_mapping.py
-drwxr-xr-x   0 jinwonchoi   (501) staff       (20)        0 2023-06-28 11:01:27.656553 bs_db_migration-0.1.1/src/bs_db_migration.egg-info/
--rw-r--r--   0 jinwonchoi   (501) staff       (20)      639 2023-06-28 11:01:27.000000 bs_db_migration-0.1.1/src/bs_db_migration.egg-info/PKG-INFO
--rw-r--r--   0 jinwonchoi   (501) staff       (20)      436 2023-06-28 11:01:27.000000 bs_db_migration-0.1.1/src/bs_db_migration.egg-info/SOURCES.txt
--rw-r--r--   0 jinwonchoi   (501) staff       (20)        1 2023-06-28 11:01:27.000000 bs_db_migration-0.1.1/src/bs_db_migration.egg-info/dependency_links.txt
--rw-r--r--   0 jinwonchoi   (501) staff       (20)       24 2023-06-28 11:01:27.000000 bs_db_migration-0.1.1/src/bs_db_migration.egg-info/requires.txt
--rw-r--r--   0 jinwonchoi   (501) staff       (20)       16 2023-06-28 11:01:27.000000 bs_db_migration-0.1.1/src/bs_db_migration.egg-info/top_level.txt
+drwxr-xr-x   0 jinwonchoi   (501) staff       (20)        0 2023-06-28 11:13:51.732137 bs_db_migration-0.1.2/
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)     1063 2023-02-03 01:32:29.000000 bs_db_migration-0.1.2/LICENSE
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)      639 2023-06-28 11:13:51.732250 bs_db_migration-0.1.2/PKG-INFO
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)     6745 2023-06-28 10:34:56.000000 bs_db_migration-0.1.2/README.md
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)       79 2023-06-28 11:13:51.732574 bs_db_migration-0.1.2/setup.cfg
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)     1064 2023-06-28 11:13:36.000000 bs_db_migration-0.1.2/setup.py
+drwxr-xr-x   0 jinwonchoi   (501) staff       (20)        0 2023-06-28 11:13:51.728740 bs_db_migration-0.1.2/src/
+drwxr-xr-x   0 jinwonchoi   (501) staff       (20)        0 2023-06-28 11:13:51.731034 bs_db_migration-0.1.2/src/bs_db_migration/
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)       63 2023-06-28 11:13:17.000000 bs_db_migration-0.1.2/src/bs_db_migration/__init__.py
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)     2262 2023-06-28 08:46:10.000000 bs_db_migration-0.1.2/src/bs_db_migration/config.py
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)      240 2023-06-28 06:29:21.000000 bs_db_migration-0.1.2/src/bs_db_migration/domain_dictionary.py
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)    22596 2023-06-28 10:04:25.000000 bs_db_migration-0.1.2/src/bs_db_migration/ms2postgres.py
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)     3259 2023-06-28 08:46:05.000000 bs_db_migration-0.1.2/src/bs_db_migration/ms2postgres_type_mapping.py
+drwxr-xr-x   0 jinwonchoi   (501) staff       (20)        0 2023-06-28 11:13:51.732008 bs_db_migration-0.1.2/src/bs_db_migration.egg-info/
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)      639 2023-06-28 11:13:51.000000 bs_db_migration-0.1.2/src/bs_db_migration.egg-info/PKG-INFO
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)      436 2023-06-28 11:13:51.000000 bs_db_migration-0.1.2/src/bs_db_migration.egg-info/SOURCES.txt
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)        1 2023-06-28 11:13:51.000000 bs_db_migration-0.1.2/src/bs_db_migration.egg-info/dependency_links.txt
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)       24 2023-06-28 11:13:51.000000 bs_db_migration-0.1.2/src/bs_db_migration.egg-info/requires.txt
+-rw-r--r--   0 jinwonchoi   (501) staff       (20)       16 2023-06-28 11:13:51.000000 bs_db_migration-0.1.2/src/bs_db_migration.egg-info/top_level.txt
```

### Comparing `bs_db_migration-0.1.1/LICENSE` & `bs_db_migration-0.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `bs_db_migration-0.1.1/PKG-INFO` & `bs_db_migration-0.1.2/src/bs_db_migration.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
-Name: bs_db_migration
-Version: 0.1.1
+Name: bs-db-migration
+Version: 0.1.2
 Summary: BS DB Migration
 Home-page: https://github.com/vincent841/ms2postgres.git
 Author: Jinwon Choi
 Author-email: jinwon@hatiolab.com
 License: MIT
 Description: BS DB Migration
 Keywords: database migration
```

### Comparing `bs_db_migration-0.1.1/README.md` & `bs_db_migration-0.1.2/README.md`

 * *Files identical despite different names*

### Comparing `bs_db_migration-0.1.1/setup.py` & `bs_db_migration-0.1.2/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 
 long_description = """BS DB Migration"""
 
 INSTALL_REQUIRES = ["psycopg2", "pymssql", "pyyaml"]
 
 setup(
     name="bs_db_migration",
-    version="0.1.1",
+    version="0.1.2",
     author="Jinwon Choi",
     author_email="jinwon@hatiolab.com",
     url="https://github.com/vincent841/ms2postgres.git",
     install_requires=INSTALL_REQUIRES,
     packages=find_packages(where="src"),
     package_dir={"": "src"},
     include_package_data=True,
```

### Comparing `bs_db_migration-0.1.1/src/bs_db_migration/config.py` & `bs_db_migration-0.1.2/src/bs_db_migration/config.py`

 * *Files identical despite different names*

### Comparing `bs_db_migration-0.1.1/src/bs_db_migration/ms2postgres.py` & `bs_db_migration-0.1.2/src/bs_db_migration/ms2postgres.py`

 * *Files identical despite different names*

### Comparing `bs_db_migration-0.1.1/src/bs_db_migration/ms2postgres_type_mapping.py` & `bs_db_migration-0.1.2/src/bs_db_migration/ms2postgres_type_mapping.py`

 * *Files identical despite different names*

### Comparing `bs_db_migration-0.1.1/src/bs_db_migration.egg-info/PKG-INFO` & `bs_db_migration-0.1.2/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
-Name: bs-db-migration
-Version: 0.1.1
+Name: bs_db_migration
+Version: 0.1.2
 Summary: BS DB Migration
 Home-page: https://github.com/vincent841/ms2postgres.git
 Author: Jinwon Choi
 Author-email: jinwon@hatiolab.com
 License: MIT
 Description: BS DB Migration
 Keywords: database migration
```


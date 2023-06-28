# Comparing `tmp/prom-4.4.1.tar.gz` & `tmp/prom-4.4.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "prom-4.4.1.tar", last modified: Sat Jun 24 21:19:09 2023, max compression
+gzip compressed data, was "prom-4.4.2.tar", last modified: Wed Jun 28 00:11:26 2023, max compression
```

## Comparing `prom-4.4.1.tar` & `prom-4.4.2.tar`

### file list

```diff
@@ -1,33 +1,33 @@
-drwxr-xr-x   0 jaymon     (501) staff       (20)        0 2023-06-24 21:19:09.600855 prom-4.4.1/
--rw-r--r--   0 jaymon     (501) staff       (20)     1080 2017-08-21 19:50:23.000000 prom-4.4.1/LICENSE.txt
--rw-r--r--   0 jaymon     (501) staff       (20)     5916 2023-06-24 21:19:09.600719 prom-4.4.1/PKG-INFO
--rw-r--r--   0 jaymon     (501) staff       (20)     5228 2021-05-05 22:06:50.000000 prom-4.4.1/README.md
-drwxr-xr-x   0 jaymon     (501) staff       (20)        0 2023-06-24 21:19:09.598141 prom-4.4.1/prom/
--rw-r--r--   0 jaymon     (501) staff       (20)     1456 2023-06-24 21:18:22.000000 prom-4.4.1/prom/__init__.py
--rw-r--r--   0 jaymon     (501) staff       (20)      188 2021-05-05 21:14:27.000000 prom-4.4.1/prom/compat.py
--rw-r--r--   0 jaymon     (501) staff       (20)    48726 2023-05-01 22:59:39.000000 prom-4.4.1/prom/config.py
--rw-r--r--   0 jaymon     (501) staff       (20)     2359 2023-03-27 21:02:23.000000 prom-4.4.1/prom/exception.py
-drwxr-xr-x   0 jaymon     (501) staff       (20)        0 2023-06-24 21:19:09.599164 prom-4.4.1/prom/extras/
--rw-r--r--   0 jaymon     (501) staff       (20)        0 2023-03-27 21:25:20.000000 prom-4.4.1/prom/extras/__init__.py
--rw-r--r--   0 jaymon     (501) staff       (20)     1262 2023-03-11 10:50:37.000000 prom-4.4.1/prom/extras/config.py
--rw-r--r--   0 jaymon     (501) staff       (20)     2447 2023-03-23 00:59:43.000000 prom-4.4.1/prom/extras/model.py
--rw-r--r--   0 jaymon     (501) staff       (20)    23069 2023-06-24 20:06:22.000000 prom-4.4.1/prom/extras/testdata.py
-drwxr-xr-x   0 jaymon     (501) staff       (20)        0 2023-06-24 21:19:09.599700 prom-4.4.1/prom/interface/
--rw-r--r--   0 jaymon     (501) staff       (20)     3032 2023-03-27 23:40:25.000000 prom-4.4.1/prom/interface/__init__.py
--rw-r--r--   0 jaymon     (501) staff       (20)    27763 2023-03-27 23:38:55.000000 prom-4.4.1/prom/interface/base.py
-drwxr-xr-x   0 jaymon     (501) staff       (20)        0 2023-06-24 21:19:09.600355 prom-4.4.1/prom/interface/postgres/
--rw-r--r--   0 jaymon     (501) staff       (20)    20308 2023-05-01 23:16:39.000000 prom-4.4.1/prom/interface/postgres/__init__.py
--rw-r--r--   0 jaymon     (501) staff       (20)     3109 2023-03-23 00:11:15.000000 prom-4.4.1/prom/interface/postgres/gevent.py
--rw-r--r--   0 jaymon     (501) staff       (20)    34441 2023-05-01 23:10:59.000000 prom-4.4.1/prom/interface/sql.py
--rw-r--r--   0 jaymon     (501) staff       (20)    17737 2023-05-01 22:51:11.000000 prom-4.4.1/prom/interface/sqlite.py
--rw-r--r--   0 jaymon     (501) staff       (20)    23906 2023-03-23 22:20:04.000000 prom-4.4.1/prom/model.py
--rw-r--r--   0 jaymon     (501) staff       (20)    34778 2023-03-26 19:34:46.000000 prom-4.4.1/prom/query.py
--rw-r--r--   0 jaymon     (501) staff       (20)     4610 2020-12-07 23:23:45.000000 prom-4.4.1/prom/utils.py
-drwxr-xr-x   0 jaymon     (501) staff       (20)        0 2023-06-24 21:19:09.598690 prom-4.4.1/prom.egg-info/
--rw-r--r--   0 jaymon     (501) staff       (20)     5916 2023-06-24 21:19:09.000000 prom-4.4.1/prom.egg-info/PKG-INFO
--rw-r--r--   0 jaymon     (501) staff       (20)      534 2023-06-24 21:19:09.000000 prom-4.4.1/prom.egg-info/SOURCES.txt
--rw-r--r--   0 jaymon     (501) staff       (20)        1 2023-06-24 21:19:09.000000 prom-4.4.1/prom.egg-info/dependency_links.txt
--rw-r--r--   0 jaymon     (501) staff       (20)       57 2023-06-24 21:19:09.000000 prom-4.4.1/prom.egg-info/requires.txt
--rw-r--r--   0 jaymon     (501) staff       (20)        5 2023-06-24 21:19:09.000000 prom-4.4.1/prom.egg-info/top_level.txt
--rw-r--r--   0 jaymon     (501) staff       (20)       38 2023-06-24 21:19:09.600908 prom-4.4.1/setup.cfg
--rw-r--r--   0 jaymon     (501) staff       (20)     2201 2021-10-12 23:47:11.000000 prom-4.4.1/setup.py
+drwxr-xr-x   0 jaymon     (501) staff       (20)        0 2023-06-28 00:11:26.256440 prom-4.4.2/
+-rw-r--r--   0 jaymon     (501) staff       (20)     1080 2017-08-21 19:50:23.000000 prom-4.4.2/LICENSE.txt
+-rw-r--r--   0 jaymon     (501) staff       (20)     5916 2023-06-28 00:11:26.256303 prom-4.4.2/PKG-INFO
+-rw-r--r--   0 jaymon     (501) staff       (20)     5228 2021-05-05 22:06:50.000000 prom-4.4.2/README.md
+drwxr-xr-x   0 jaymon     (501) staff       (20)        0 2023-06-28 00:11:26.254187 prom-4.4.2/prom/
+-rw-r--r--   0 jaymon     (501) staff       (20)     1456 2023-06-28 00:11:01.000000 prom-4.4.2/prom/__init__.py
+-rw-r--r--   0 jaymon     (501) staff       (20)      188 2021-05-05 21:14:27.000000 prom-4.4.2/prom/compat.py
+-rw-r--r--   0 jaymon     (501) staff       (20)    48726 2023-05-01 22:59:39.000000 prom-4.4.2/prom/config.py
+-rw-r--r--   0 jaymon     (501) staff       (20)     2359 2023-03-27 21:02:23.000000 prom-4.4.2/prom/exception.py
+drwxr-xr-x   0 jaymon     (501) staff       (20)        0 2023-06-28 00:11:26.255135 prom-4.4.2/prom/extras/
+-rw-r--r--   0 jaymon     (501) staff       (20)        0 2023-03-27 21:25:20.000000 prom-4.4.2/prom/extras/__init__.py
+-rw-r--r--   0 jaymon     (501) staff       (20)     1262 2023-03-11 10:50:37.000000 prom-4.4.2/prom/extras/config.py
+-rw-r--r--   0 jaymon     (501) staff       (20)     2447 2023-03-23 00:59:43.000000 prom-4.4.2/prom/extras/model.py
+-rw-r--r--   0 jaymon     (501) staff       (20)    23069 2023-06-24 20:06:22.000000 prom-4.4.2/prom/extras/testdata.py
+drwxr-xr-x   0 jaymon     (501) staff       (20)        0 2023-06-28 00:11:26.255661 prom-4.4.2/prom/interface/
+-rw-r--r--   0 jaymon     (501) staff       (20)     3032 2023-03-27 23:40:25.000000 prom-4.4.2/prom/interface/__init__.py
+-rw-r--r--   0 jaymon     (501) staff       (20)    27763 2023-03-27 23:38:55.000000 prom-4.4.2/prom/interface/base.py
+drwxr-xr-x   0 jaymon     (501) staff       (20)        0 2023-06-28 00:11:26.255915 prom-4.4.2/prom/interface/postgres/
+-rw-r--r--   0 jaymon     (501) staff       (20)    20308 2023-05-01 23:16:39.000000 prom-4.4.2/prom/interface/postgres/__init__.py
+-rw-r--r--   0 jaymon     (501) staff       (20)     3109 2023-03-23 00:11:15.000000 prom-4.4.2/prom/interface/postgres/gevent.py
+-rw-r--r--   0 jaymon     (501) staff       (20)    34441 2023-05-01 23:10:59.000000 prom-4.4.2/prom/interface/sql.py
+-rw-r--r--   0 jaymon     (501) staff       (20)    17737 2023-06-27 20:25:40.000000 prom-4.4.2/prom/interface/sqlite.py
+-rw-r--r--   0 jaymon     (501) staff       (20)    23833 2023-06-27 23:27:43.000000 prom-4.4.2/prom/model.py
+-rw-r--r--   0 jaymon     (501) staff       (20)    34778 2023-03-26 19:34:46.000000 prom-4.4.2/prom/query.py
+-rw-r--r--   0 jaymon     (501) staff       (20)     4610 2020-12-07 23:23:45.000000 prom-4.4.2/prom/utils.py
+drwxr-xr-x   0 jaymon     (501) staff       (20)        0 2023-06-28 00:11:26.254734 prom-4.4.2/prom.egg-info/
+-rw-r--r--   0 jaymon     (501) staff       (20)     5916 2023-06-28 00:11:26.000000 prom-4.4.2/prom.egg-info/PKG-INFO
+-rw-r--r--   0 jaymon     (501) staff       (20)      534 2023-06-28 00:11:26.000000 prom-4.4.2/prom.egg-info/SOURCES.txt
+-rw-r--r--   0 jaymon     (501) staff       (20)        1 2023-06-28 00:11:26.000000 prom-4.4.2/prom.egg-info/dependency_links.txt
+-rw-r--r--   0 jaymon     (501) staff       (20)       57 2023-06-28 00:11:26.000000 prom-4.4.2/prom.egg-info/requires.txt
+-rw-r--r--   0 jaymon     (501) staff       (20)        5 2023-06-28 00:11:26.000000 prom-4.4.2/prom.egg-info/top_level.txt
+-rw-r--r--   0 jaymon     (501) staff       (20)       38 2023-06-28 00:11:26.256487 prom-4.4.2/setup.cfg
+-rw-r--r--   0 jaymon     (501) staff       (20)     2201 2021-10-12 23:47:11.000000 prom-4.4.2/setup.py
```

### Comparing `prom-4.4.1/LICENSE.txt` & `prom-4.4.2/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/PKG-INFO` & `prom-4.4.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: prom
-Version: 4.4.1
+Version: 4.4.2
 Summary: A sensible orm for PostgreSQL or SQLite
 Home-page: http://github.com/jaymon/prom
 Author: Jay Marcyes
 Author-email: jay@marcyes.com
 License: MIT
 Classifier: Development Status :: 4 - Beta
 Classifier: Environment :: Web Environment
```

### Comparing `prom-4.4.1/README.md` & `prom-4.4.2/README.md`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/prom/__init__.py` & `prom-4.4.2/prom/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -27,15 +27,15 @@
     UniqueError,
     CloseError,
 )
 
 from . import utils
 
 
-__version__ = '4.4.1'
+__version__ = '4.4.2'
 
 
 def transaction(connection_name="", **kwargs):
     """Create a transaction 
 
     Sometimes you just need to batch a whole bunch of operation across a whole bunch
     of different models, this allows you to create a transaction outside of any
```

### Comparing `prom-4.4.1/prom/config.py` & `prom-4.4.2/prom/config.py`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/prom/exception.py` & `prom-4.4.2/prom/exception.py`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/prom/extras/config.py` & `prom-4.4.2/prom/extras/config.py`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/prom/extras/model.py` & `prom-4.4.2/prom/extras/model.py`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/prom/extras/testdata.py` & `prom-4.4.2/prom/extras/testdata.py`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/prom/interface/__init__.py` & `prom-4.4.2/prom/interface/__init__.py`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/prom/interface/base.py` & `prom-4.4.2/prom/interface/base.py`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/prom/interface/postgres/__init__.py` & `prom-4.4.2/prom/interface/postgres/__init__.py`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/prom/interface/postgres/gevent.py` & `prom-4.4.2/prom/interface/postgres/gevent.py`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/prom/interface/sql.py` & `prom-4.4.2/prom/interface/sql.py`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/prom/interface/sqlite.py` & `prom-4.4.2/prom/interface/sqlite.py`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/prom/model.py` & `prom-4.4.2/prom/model.py`

 * *Files 0% similar despite different names*

```diff
@@ -326,15 +326,14 @@
         """this runs all the fields through their iget methods to mimic them
         freshly coming out of the db, then resets modified
 
         :param fields: dict, only the fields you want to populate
         """
         schema = self.schema
         for field_name, v in fields.items():
-            fields[field_name] = schema.fields[field_name].iget(self, v)
             if field_name in schema.fields:
                 fields[field_name] = schema.fields[field_name].iget(self, v)
 
         self.modify(fields)
 
         # this marks that this was repopulated from the interface (database)
         self._interface_pk = self.pk
```

### Comparing `prom-4.4.1/prom/query.py` & `prom-4.4.2/prom/query.py`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/prom/utils.py` & `prom-4.4.2/prom/utils.py`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/prom.egg-info/PKG-INFO` & `prom-4.4.2/prom.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: prom
-Version: 4.4.1
+Version: 4.4.2
 Summary: A sensible orm for PostgreSQL or SQLite
 Home-page: http://github.com/jaymon/prom
 Author: Jay Marcyes
 Author-email: jay@marcyes.com
 License: MIT
 Classifier: Development Status :: 4 - Beta
 Classifier: Environment :: Web Environment
```

### Comparing `prom-4.4.1/prom.egg-info/SOURCES.txt` & `prom-4.4.2/prom.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `prom-4.4.1/setup.py` & `prom-4.4.2/setup.py`

 * *Files identical despite different names*


# Comparing `tmp/sqlalchemy-pagination-fastapi-0.0.1.tar.gz` & `tmp/sqlalchemy-pagination-fastapi-0.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sqlalchemy-pagination-fastapi-0.0.1.tar", last modified: Wed Jun 28 07:50:30 2023, max compression
+gzip compressed data, was "sqlalchemy-pagination-fastapi-0.0.2.tar", last modified: Wed Jun 28 08:02:56 2023, max compression
```

## Comparing `sqlalchemy-pagination-fastapi-0.0.1.tar` & `sqlalchemy-pagination-fastapi-0.0.2.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxr-xr-x   0 oriolviladrosa   (501) staff       (20)        0 2023-06-28 07:50:30.737466 sqlalchemy-pagination-fastapi-0.0.1/
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)     1072 2023-06-26 14:04:22.000000 sqlalchemy-pagination-fastapi-0.0.1/LICENSE
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)      466 2023-06-28 07:50:30.737530 sqlalchemy-pagination-fastapi-0.0.1/PKG-INFO
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)      139 2023-06-26 14:09:13.000000 sqlalchemy-pagination-fastapi-0.0.1/README.md
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)       84 2023-03-30 09:16:11.000000 sqlalchemy-pagination-fastapi-0.0.1/pyproject.toml
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)      563 2023-06-28 07:50:30.737820 sqlalchemy-pagination-fastapi-0.0.1/setup.cfg
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)       69 2023-06-28 07:50:22.000000 sqlalchemy-pagination-fastapi-0.0.1/setup.py
-drwxr-xr-x   0 oriolviladrosa   (501) staff       (20)        0 2023-06-28 07:50:30.733219 sqlalchemy-pagination-fastapi-0.0.1/src/
-drwxr-xr-x   0 oriolviladrosa   (501) staff       (20)        0 2023-06-28 07:50:30.734474 sqlalchemy-pagination-fastapi-0.0.1/src/pagination/
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)        0 2023-06-27 06:24:50.000000 sqlalchemy-pagination-fastapi-0.0.1/src/pagination/__init__.py
-drwxr-xr-x   0 oriolviladrosa   (501) staff       (20)        0 2023-06-28 07:50:30.734881 sqlalchemy-pagination-fastapi-0.0.1/src/pagination/model/
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)        0 2023-06-27 06:24:31.000000 sqlalchemy-pagination-fastapi-0.0.1/src/pagination/model/__init__.py
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)      471 2023-06-28 07:08:51.000000 sqlalchemy-pagination-fastapi-0.0.1/src/pagination/model/page_model.py
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)      445 2023-06-28 07:37:06.000000 sqlalchemy-pagination-fastapi-0.0.1/src/pagination/pagination.py
-drwxr-xr-x   0 oriolviladrosa   (501) staff       (20)        0 2023-06-28 07:50:30.737346 sqlalchemy-pagination-fastapi-0.0.1/src/sqlalchemy_pagination_fastapi.egg-info/
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)      466 2023-06-28 07:50:30.000000 sqlalchemy-pagination-fastapi-0.0.1/src/sqlalchemy_pagination_fastapi.egg-info/PKG-INFO
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)      459 2023-06-28 07:50:30.000000 sqlalchemy-pagination-fastapi-0.0.1/src/sqlalchemy_pagination_fastapi.egg-info/SOURCES.txt
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)        1 2023-06-28 07:50:30.000000 sqlalchemy-pagination-fastapi-0.0.1/src/sqlalchemy_pagination_fastapi.egg-info/dependency_links.txt
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)       39 2023-06-28 07:50:30.000000 sqlalchemy-pagination-fastapi-0.0.1/src/sqlalchemy_pagination_fastapi.egg-info/requires.txt
--rw-r--r--   0 oriolviladrosa   (501) staff       (20)       11 2023-06-28 07:50:30.000000 sqlalchemy-pagination-fastapi-0.0.1/src/sqlalchemy_pagination_fastapi.egg-info/top_level.txt
+drwxr-xr-x   0 oriolviladrosa   (501) staff       (20)        0 2023-06-28 08:02:56.714462 sqlalchemy-pagination-fastapi-0.0.2/
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)     1072 2023-06-26 14:04:22.000000 sqlalchemy-pagination-fastapi-0.0.2/LICENSE
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)      466 2023-06-28 08:02:56.714529 sqlalchemy-pagination-fastapi-0.0.2/PKG-INFO
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)      139 2023-06-26 14:09:13.000000 sqlalchemy-pagination-fastapi-0.0.2/README.md
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)       84 2023-03-30 09:16:11.000000 sqlalchemy-pagination-fastapi-0.0.2/pyproject.toml
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)      563 2023-06-28 08:02:56.715327 sqlalchemy-pagination-fastapi-0.0.2/setup.cfg
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)       69 2023-06-28 07:50:22.000000 sqlalchemy-pagination-fastapi-0.0.2/setup.py
+drwxr-xr-x   0 oriolviladrosa   (501) staff       (20)        0 2023-06-28 08:02:56.711936 sqlalchemy-pagination-fastapi-0.0.2/src/
+drwxr-xr-x   0 oriolviladrosa   (501) staff       (20)        0 2023-06-28 08:02:56.713033 sqlalchemy-pagination-fastapi-0.0.2/src/pagination/
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)        0 2023-06-27 06:24:50.000000 sqlalchemy-pagination-fastapi-0.0.2/src/pagination/__init__.py
+drwxr-xr-x   0 oriolviladrosa   (501) staff       (20)        0 2023-06-28 08:02:56.713407 sqlalchemy-pagination-fastapi-0.0.2/src/pagination/model/
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)        0 2023-06-27 06:24:31.000000 sqlalchemy-pagination-fastapi-0.0.2/src/pagination/model/__init__.py
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)      471 2023-06-28 07:08:51.000000 sqlalchemy-pagination-fastapi-0.0.2/src/pagination/model/page_model.py
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)      445 2023-06-28 07:37:06.000000 sqlalchemy-pagination-fastapi-0.0.2/src/pagination/query_pagination.py
+drwxr-xr-x   0 oriolviladrosa   (501) staff       (20)        0 2023-06-28 08:02:56.714357 sqlalchemy-pagination-fastapi-0.0.2/src/sqlalchemy_pagination_fastapi.egg-info/
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)      466 2023-06-28 08:02:56.000000 sqlalchemy-pagination-fastapi-0.0.2/src/sqlalchemy_pagination_fastapi.egg-info/PKG-INFO
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)      465 2023-06-28 08:02:56.000000 sqlalchemy-pagination-fastapi-0.0.2/src/sqlalchemy_pagination_fastapi.egg-info/SOURCES.txt
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)        1 2023-06-28 08:02:56.000000 sqlalchemy-pagination-fastapi-0.0.2/src/sqlalchemy_pagination_fastapi.egg-info/dependency_links.txt
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)       39 2023-06-28 08:02:56.000000 sqlalchemy-pagination-fastapi-0.0.2/src/sqlalchemy_pagination_fastapi.egg-info/requires.txt
+-rw-r--r--   0 oriolviladrosa   (501) staff       (20)       11 2023-06-28 08:02:56.000000 sqlalchemy-pagination-fastapi-0.0.2/src/sqlalchemy_pagination_fastapi.egg-info/top_level.txt
```

### Comparing `sqlalchemy-pagination-fastapi-0.0.1/LICENSE` & `sqlalchemy-pagination-fastapi-0.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `sqlalchemy-pagination-fastapi-0.0.1/setup.cfg` & `sqlalchemy-pagination-fastapi-0.0.2/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = sqlalchemy-pagination-fastapi
-version = 0.0.1
+version = 0.0.2
 author = Oriol Viladrosa
 author_email = oviladrosa@gmail.com
 description = Package used to paginate sqlalchemy query results.
 long_description = file: README.md
 long_description_content_type = text/markdown
 classifiers = 
 	Programming Language :: Python :: 3
```


# Comparing `tmp/sqlakeyset-2.0.1684285512.tar.gz` & `tmp/sqlakeyset-2.0.1687912386.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sqlakeyset-2.0.1684285512.tar", max compression
+gzip compressed data, was "sqlakeyset-2.0.1687912386.tar", max compression
```

## Comparing `sqlakeyset-2.0.1684285512.tar` & `sqlakeyset-2.0.1687912386.tar`

### file list

```diff
@@ -1,18 +1,17 @@
--rw-r--r--   0        0        0     1210 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/LICENSE
--rw-r--r--   0        0        0     8265 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/README.rst
--rw-r--r--   0        0        0     1295 2023-05-17 01:05:12.051476 sqlakeyset-2.0.1684285512/pyproject.toml
--rw-r--r--   0        0        0      631 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/sqlakeyset/__init__.py
--rw-r--r--   0        0        0     2717 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/sqlakeyset/asyncio.py
--rw-r--r--   0        0        0    14716 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/sqlakeyset/columns.py
--rw-r--r--   0        0        0       37 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/sqlakeyset/constants.py
--rw-r--r--   0        0        0    14213 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/sqlakeyset/paging.py
--rw-r--r--   0        0        0    10324 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/sqlakeyset/results.py
--rw-r--r--   0        0        0      347 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/sqlakeyset/serial/__init__.py
--rw-r--r--   0        0        0     5546 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/sqlakeyset/serial/serial.py
--rw-r--r--   0        0        0     2097 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/sqlakeyset/sqla.py
--rw-r--r--   0        0        0     2613 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/sqlakeyset/sqla13.py
--rw-r--r--   0        0        0     1571 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/sqlakeyset/sqla14.py
--rw-r--r--   0        0        0     4199 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/sqlakeyset/sqla20.py
--rw-r--r--   0        0        0      768 2023-05-17 01:05:06.803672 sqlakeyset-2.0.1684285512/sqlakeyset/types.py
--rw-r--r--   0        0        0     9215 1970-01-01 00:00:00.000000 sqlakeyset-2.0.1684285512/setup.py
--rw-r--r--   0        0        0     9125 1970-01-01 00:00:00.000000 sqlakeyset-2.0.1684285512/PKG-INFO
+-rw-r--r--   0        0        0     1210 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/LICENSE
+-rw-r--r--   0        0        0     8265 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/README.rst
+-rw-r--r--   0        0        0     1295 2023-06-28 00:33:06.064446 sqlakeyset-2.0.1687912386/pyproject.toml
+-rw-r--r--   0        0        0      631 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/sqlakeyset/__init__.py
+-rw-r--r--   0        0        0     2767 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/sqlakeyset/asyncio.py
+-rw-r--r--   0        0        0    14716 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/sqlakeyset/columns.py
+-rw-r--r--   0        0        0       37 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/sqlakeyset/constants.py
+-rw-r--r--   0        0        0    14213 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/sqlakeyset/paging.py
+-rw-r--r--   0        0        0    10324 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/sqlakeyset/results.py
+-rw-r--r--   0        0        0      347 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/sqlakeyset/serial/__init__.py
+-rw-r--r--   0        0        0     5546 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/sqlakeyset/serial/serial.py
+-rw-r--r--   0        0        0     2097 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/sqlakeyset/sqla.py
+-rw-r--r--   0        0        0     2613 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/sqlakeyset/sqla13.py
+-rw-r--r--   0        0        0     1571 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/sqlakeyset/sqla14.py
+-rw-r--r--   0        0        0     4199 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/sqlakeyset/sqla20.py
+-rw-r--r--   0        0        0      768 2023-06-28 00:33:00.912524 sqlakeyset-2.0.1687912386/sqlakeyset/types.py
+-rw-r--r--   0        0        0     9125 1970-01-01 00:00:00.000000 sqlakeyset-2.0.1687912386/PKG-INFO
```

### Comparing `sqlakeyset-2.0.1684285512/LICENSE` & `sqlakeyset-2.0.1687912386/LICENSE`

 * *Files identical despite different names*

### Comparing `sqlakeyset-2.0.1684285512/README.rst` & `sqlakeyset-2.0.1687912386/README.rst`

 * *Files identical despite different names*

### Comparing `sqlakeyset-2.0.1684285512/pyproject.toml` & `sqlakeyset-2.0.1687912386/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = [ "poetry-core>=1.0.0",]
 build-backend = "poetry.core.masonry.api"
 
 [tool.poetry]
 name = "sqlakeyset"
-version = "2.0.1684285512"
+version = "2.0.1687912386"
 authors = [ "Robert Lechte <robertlechte@gmail.com>", "Anthony Carapetis <anthony.carapetis@gmail.com>",]
 license = "Unlicense"
 readme = "README.rst"
 description = "offset-free paging for sqlalchemy"
 repository = "https://github.com/djrobstep/sqlakeyset"
 homepage = "https://github.com/djrobstep/sqlakeyset"
```

### Comparing `sqlakeyset-2.0.1684285512/sqlakeyset/__init__.py` & `sqlakeyset-2.0.1687912386/sqlakeyset/__init__.py`

 * *Files identical despite different names*

### Comparing `sqlakeyset-2.0.1684285512/sqlakeyset/asyncio.py` & `sqlakeyset-2.0.1687912386/sqlakeyset/asyncio.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,11 @@
+from __future__ import annotations
 from typing import Any, Optional, Tuple, TypeVar, Union
 
-from sqlalchemy import Select
+from sqlalchemy.sql.selectable import Select
 from sqlalchemy.engine.row import Row
 from sqlalchemy.ext.asyncio import AsyncConnection, AsyncSession
 
 from sqlakeyset.paging import (
     PER_PAGE_DEFAULT,
     OptionalKeyset,
     core_page_from_rows,
```

### Comparing `sqlakeyset-2.0.1684285512/sqlakeyset/columns.py` & `sqlakeyset-2.0.1687912386/sqlakeyset/columns.py`

 * *Files identical despite different names*

### Comparing `sqlakeyset-2.0.1684285512/sqlakeyset/paging.py` & `sqlakeyset-2.0.1687912386/sqlakeyset/paging.py`

 * *Files identical despite different names*

### Comparing `sqlakeyset-2.0.1684285512/sqlakeyset/results.py` & `sqlakeyset-2.0.1687912386/sqlakeyset/results.py`

 * *Files identical despite different names*

### Comparing `sqlakeyset-2.0.1684285512/sqlakeyset/serial/serial.py` & `sqlakeyset-2.0.1687912386/sqlakeyset/serial/serial.py`

 * *Files identical despite different names*

### Comparing `sqlakeyset-2.0.1684285512/sqlakeyset/sqla.py` & `sqlakeyset-2.0.1687912386/sqlakeyset/sqla.py`

 * *Files identical despite different names*

### Comparing `sqlakeyset-2.0.1684285512/sqlakeyset/sqla13.py` & `sqlakeyset-2.0.1687912386/sqlakeyset/sqla13.py`

 * *Files identical despite different names*

### Comparing `sqlakeyset-2.0.1684285512/sqlakeyset/sqla14.py` & `sqlakeyset-2.0.1687912386/sqlakeyset/sqla14.py`

 * *Files identical despite different names*

### Comparing `sqlakeyset-2.0.1684285512/sqlakeyset/sqla20.py` & `sqlakeyset-2.0.1687912386/sqlakeyset/sqla20.py`

 * *Files identical despite different names*

### Comparing `sqlakeyset-2.0.1684285512/sqlakeyset/types.py` & `sqlakeyset-2.0.1687912386/sqlakeyset/types.py`

 * *Files identical despite different names*

### Comparing `sqlakeyset-2.0.1684285512/PKG-INFO` & `sqlakeyset-2.0.1687912386/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sqlakeyset
-Version: 2.0.1684285512
+Version: 2.0.1687912386
 Summary: offset-free paging for sqlalchemy
 Home-page: https://github.com/djrobstep/sqlakeyset
 License: Unlicense
 Author: Robert Lechte
 Author-email: robertlechte@gmail.com
 Requires-Python: >=3.7,<4.0
 Classifier: License :: Other/Proprietary License
```


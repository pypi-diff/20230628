# Comparing `tmp/bl3d-0.4.0.tar.gz` & `tmp/bl3d-0.4.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "bl3d-0.4.0.tar", max compression
+gzip compressed data, was "bl3d-0.4.1.tar", max compression
```

## Comparing `bl3d-0.4.0.tar` & `bl3d-0.4.1.tar`

### file list

```diff
@@ -1,7 +1,7 @@
--rw-r--r--   0        0        0    34895 2022-11-09 08:32:45.815575 bl3d-0.4.0/LICENSE.md
--rw-r--r--   0        0        0      182 2022-11-09 07:16:37.084157 bl3d-0.4.0/README.md
--rw-r--r--   0        0        0    12095 2023-06-21 07:12:54.198624 bl3d-0.4.0/bl3d/__init__.py
--rw-r--r--   0        0        0        0 2022-11-09 08:32:45.815575 bl3d-0.4.0/bl3d/py.typed
--rw-r--r--   0        0        0      865 2023-06-21 07:18:59.870687 bl3d-0.4.0/pyproject.toml
--rw-r--r--   0        0        0      746 2023-06-21 08:41:53.353892 bl3d-0.4.0/setup.py
--rw-r--r--   0        0        0      783 2023-06-21 08:41:53.354356 bl3d-0.4.0/PKG-INFO
+-rw-r--r--   0        0        0    34895 2022-11-09 08:32:45.815575 bl3d-0.4.1/LICENSE.md
+-rw-r--r--   0        0        0      182 2022-11-09 07:16:37.084157 bl3d-0.4.1/README.md
+-rw-r--r--   0        0        0    12068 2023-06-28 09:40:13.101653 bl3d-0.4.1/bl3d/__init__.py
+-rw-r--r--   0        0        0        0 2022-11-09 08:32:45.815575 bl3d-0.4.1/bl3d/py.typed
+-rw-r--r--   0        0        0      865 2023-06-28 09:40:13.101653 bl3d-0.4.1/pyproject.toml
+-rw-r--r--   0        0        0      746 2023-06-28 09:40:22.446431 bl3d-0.4.1/setup.py
+-rw-r--r--   0        0        0      783 2023-06-28 09:40:22.446890 bl3d-0.4.1/PKG-INFO
```

### Comparing `bl3d-0.4.0/LICENSE.md` & `bl3d-0.4.1/LICENSE.md`

 * *Files identical despite different names*

### Comparing `bl3d-0.4.0/bl3d/__init__.py` & `bl3d-0.4.1/bl3d/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -195,16 +195,15 @@
 
     @classmethod
     def instanciate(cls: Type[TypeDate], value: date) -> TypeDate:
         return cls(value)
 
     @classmethod
     def from_isoformat(cls: Type[TypeDate], isoformat: str) -> TypeDate:
-        dt = datetime.fromisoformat(isoformat)
-        return cls.instanciate(dt.date())
+        return cls.instanciate(date.fromisoformat(isoformat))
 
     def __eq__(self, other: object) -> bool:
         if not isinstance(other, Date):
             return NotImplemented
         return other.__value == self.__value
 
     def __lt__(self, other: object) -> bool:
```

### Comparing `bl3d-0.4.0/pyproject.toml` & `bl3d-0.4.1/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "bl3d"
-version = "0.4.0"
+version = "0.4.1"
 description = "Domain Driven Design library"
 authors = ["Tanguy Le Carrour <tanguy@bioneland.org>"]
 license = "GPL-3.0-or-later"
 readme = "README.md"
 homepage = "https://git.easter-eggs.org/bioneland/bl3d"
 repository = "https://git.easter-eggs.org/bioneland/bl3d"
```

### Comparing `bl3d-0.4.0/setup.py` & `bl3d-0.4.1/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 ['bl3d']
 
 package_data = \
 {'': ['*']}
 
 setup_kwargs = {
     'name': 'bl3d',
-    'version': '0.4.0',
+    'version': '0.4.1',
     'description': 'Domain Driven Design library',
     'long_description': "# bl3d – A Domain Driven Design library\n\nBioneland's Domain Driven Design library (bl3d, pronounced */'bled/*) is a collection\nof classes to write domain driven designed software.\n",
     'author': 'Tanguy Le Carrour',
     'author_email': 'tanguy@bioneland.org',
     'maintainer': None,
     'maintainer_email': None,
     'url': 'https://git.easter-eggs.org/bioneland/bl3d',
```

### Comparing `bl3d-0.4.0/PKG-INFO` & `bl3d-0.4.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: bl3d
-Version: 0.4.0
+Version: 0.4.1
 Summary: Domain Driven Design library
 Home-page: https://git.easter-eggs.org/bioneland/bl3d
 License: GPL-3.0-or-later
 Author: Tanguy Le Carrour
 Author-email: tanguy@bioneland.org
 Requires-Python: >=3.9,<4.0
 Classifier: License :: OSI Approved :: GNU General Public License v3 or later (GPLv3+)
```


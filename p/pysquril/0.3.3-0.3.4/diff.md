# Comparing `tmp/pysquril-0.3.3.tar.gz` & `tmp/pysquril-0.3.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pysquril-0.3.3.tar", max compression
+gzip compressed data, was "pysquril-0.3.4.tar", max compression
```

## Comparing `pysquril-0.3.3.tar` & `pysquril-0.3.4.tar`

### file list

```diff
@@ -1,9 +1,9 @@
--rw-r--r--   0        0        0      524 2023-06-27 12:19:07.707260 pysquril-0.3.3/pyproject.toml
--rw-r--r--   0        0        0        0 2022-06-22 08:13:57.003868 pysquril-0.3.3/pysquril/__init__.py
--rw-r--r--   0        0        0    25249 2023-06-27 13:10:47.568080 pysquril-0.3.3/pysquril/backends.py
--rw-r--r--   0        0        0      326 2023-06-27 12:18:06.880308 pysquril-0.3.3/pysquril/exc.py
--rw-r--r--   0        0        0    21254 2023-06-20 11:11:42.555715 pysquril-0.3.3/pysquril/generator.py
--rw-r--r--   0        0        0     9452 2023-01-27 11:51:39.899603 pysquril-0.3.3/pysquril/parser.py
--rw-r--r--   0        0        0     1997 2022-11-21 13:00:47.589558 pysquril-0.3.3/pysquril/test_data.py
--rw-r--r--   0        0        0    21429 2023-06-27 13:10:47.569189 pysquril-0.3.3/pysquril/tests.py
--rw-r--r--   0        0        0      658 1970-01-01 00:00:00.000000 pysquril-0.3.3/PKG-INFO
+-rw-r--r--   0        0        0      524 2023-06-28 07:51:43.894245 pysquril-0.3.4/pyproject.toml
+-rw-r--r--   0        0        0        0 2022-06-22 08:13:57.003868 pysquril-0.3.4/pysquril/__init__.py
+-rw-r--r--   0        0        0    25249 2023-06-27 13:10:47.568080 pysquril-0.3.4/pysquril/backends.py
+-rw-r--r--   0        0        0      326 2023-06-27 12:18:06.880308 pysquril-0.3.4/pysquril/exc.py
+-rw-r--r--   0        0        0    21254 2023-06-20 11:11:42.555715 pysquril-0.3.4/pysquril/generator.py
+-rw-r--r--   0        0        0     9497 2023-06-28 07:49:02.019482 pysquril-0.3.4/pysquril/parser.py
+-rw-r--r--   0        0        0     1997 2022-11-21 13:00:47.589558 pysquril-0.3.4/pysquril/test_data.py
+-rw-r--r--   0        0        0    21429 2023-06-27 13:10:47.569189 pysquril-0.3.4/pysquril/tests.py
+-rw-r--r--   0        0        0      658 1970-01-01 00:00:00.000000 pysquril-0.3.4/PKG-INFO
```

### Comparing `pysquril-0.3.3/pyproject.toml` & `pysquril-0.3.4/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "pysquril"
-version = "0.3.3"
+version = "0.3.4"
 description = "Python implementation of structured URI query language"
 repository = "https://github.com/unioslo/pysquril"
 authors = [
     "Leon du Toit <l.c.d.toit@usit.uio.no>",
     "Eirik Haatveit <haatveit@uio.no>",
 ]
```

### Comparing `pysquril-0.3.3/pysquril/backends.py` & `pysquril-0.3.4/pysquril/backends.py`

 * *Files identical despite different names*

### Comparing `pysquril-0.3.3/pysquril/generator.py` & `pysquril-0.3.4/pysquril/generator.py`

 * *Files identical despite different names*

### Comparing `pysquril-0.3.3/pysquril/parser.py` & `pysquril-0.3.4/pysquril/parser.py`

 * *Files 1% similar despite different names*

```diff
@@ -3,14 +3,16 @@
 
 import json
 import re
 
 from abc import ABC, abstractmethod
 from typing import Optional, Union, Callable
 
+from pysquril.exc import ParseError
+
 class SelectElement(ABC):
     @property
     @abstractmethod
     def name(self) -> str:
         pass
     @property
     @abstractmethod
@@ -107,19 +109,19 @@
                 ArraySpecificMultiple,
                 ArrayBroadcastSingle,
                 ArrayBroadcastMultiple
             ]:
                 if re.match(ElementClass.regex, element):
                     if found:
                         msg = f'Could not uniquely identify {element} - already matched with {found}'
-                        raise Exception(msg)
+                        raise ParseError(msg)
                     element_instance = ElementClass(element)
                     found = ElementClass.name
             if not element_instance:
-                raise Exception(f'Could not parse {element}')
+                raise ParseError(f'Could not parse {element}')
             out.append(element_instance)
         return out
 
 
 class WhereElement(object):
 
     def __init__(
@@ -222,18 +224,18 @@
         return [RangeElement(start, end)]
 
 
 class SetElement(object):
 
     def __init__(self, term: str) -> None:
         self.select_term = SelectTerm(term)
-        type_msg = f'{term} must be an instance of Key'
-        assert isinstance(self.select_term.parsed[0], Key), type_msg
-        len_msg = f'SetElements can only be top level keys - {term} is nested'
-        assert len(self.select_term.parsed) == 1, len_msg
+        if not isinstance(self.select_term.parsed[0], Key):
+            raise ParseError(f'{term} must be an instance of Key')
+        if not len(self.select_term.parsed) == 1:
+            raise ParseError(f'SetElements can only be top level keys - {term} is nested')
 
 
 class SetTerm(object):
 
     def __init__(self, original: str) -> None:
         self.original = original
         self.parsed = self.parse_elements()
```

### Comparing `pysquril-0.3.3/pysquril/test_data.py` & `pysquril-0.3.4/pysquril/test_data.py`

 * *Files identical despite different names*

### Comparing `pysquril-0.3.3/pysquril/tests.py` & `pysquril-0.3.4/pysquril/tests.py`

 * *Files identical despite different names*

### Comparing `pysquril-0.3.3/PKG-INFO` & `pysquril-0.3.4/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pysquril
-Version: 0.3.3
+Version: 0.3.4
 Summary: Python implementation of structured URI query language
 Home-page: https://github.com/unioslo/pysquril
 Author: Leon du Toit
 Author-email: l.c.d.toit@usit.uio.no
 Requires-Python: >=3.7,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.7
```


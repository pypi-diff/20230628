# Comparing `tmp/pystructs3-0.0.5.tar.gz` & `tmp/pystructs3-0.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pystructs3-0.0.5.tar", last modified: Sun Jun 25 07:59:48 2023, max compression
+gzip compressed data, was "pystructs3-0.0.6.tar", last modified: Wed Jun 28 01:34:31 2023, max compression
```

## Comparing `pystructs3-0.0.5.tar` & `pystructs3-0.0.6.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 07:59:48.017256 pystructs3-0.0.5/
--rw-r--r--   0 andrew    (1000) andrew    (1000)     1075 2023-04-18 21:12:24.000000 pystructs3-0.0.5/LICENSE
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1277 2023-06-25 07:59:48.017256 pystructs3-0.0.5/PKG-INFO
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      798 2023-04-18 21:13:45.000000 pystructs3-0.0.5/README.md
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 07:59:48.017256 pystructs3-0.0.5/pystructs/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1522 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/__init__.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     2445 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/bytestr.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     3997 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/codec.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     2359 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/helpers.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     3715 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/integer.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     3178 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/lists.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     4900 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/net.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     2662 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/struct.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 07:59:48.017256 pystructs3-0.0.5/pystructs/tests/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      323 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/tests/__init__.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1538 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/tests/bytestr.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1432 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/tests/helpers.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     2156 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/tests/integer.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1824 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/tests/lists.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     2336 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/tests/net.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1471 2023-06-25 07:59:42.000000 pystructs3-0.0.5/pystructs/tests/struct.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 07:59:48.017256 pystructs3-0.0.5/pystructs3.egg-info/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1277 2023-06-25 07:59:47.000000 pystructs3-0.0.5/pystructs3.egg-info/PKG-INFO
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      538 2023-06-25 07:59:48.000000 pystructs3-0.0.5/pystructs3.egg-info/SOURCES.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)        1 2023-06-25 07:59:47.000000 pystructs3-0.0.5/pystructs3.egg-info/dependency_links.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)       28 2023-06-25 07:59:47.000000 pystructs3-0.0.5/pystructs3.egg-info/requires.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)       10 2023-06-25 07:59:47.000000 pystructs3-0.0.5/pystructs3.egg-info/top_level.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)       38 2023-06-25 07:59:48.017256 pystructs3-0.0.5/setup.cfg
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      761 2023-06-25 07:59:42.000000 pystructs3-0.0.5/setup.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:34:31.883695 pystructs3-0.0.6/
+-rw-r--r--   0 andrew    (1000) andrew    (1000)     1075 2023-04-18 21:12:24.000000 pystructs3-0.0.6/LICENSE
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1277 2023-06-28 01:34:31.883695 pystructs3-0.0.6/PKG-INFO
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      798 2023-04-18 21:13:45.000000 pystructs3-0.0.6/README.md
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:34:31.879695 pystructs3-0.0.6/pystructs/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1522 2023-06-25 07:59:42.000000 pystructs3-0.0.6/pystructs/__init__.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     2445 2023-06-25 07:59:42.000000 pystructs3-0.0.6/pystructs/bytestr.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     3997 2023-06-25 07:59:42.000000 pystructs3-0.0.6/pystructs/codec.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     2359 2023-06-25 07:59:42.000000 pystructs3-0.0.6/pystructs/helpers.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     3715 2023-06-25 07:59:42.000000 pystructs3-0.0.6/pystructs/integer.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     3178 2023-06-25 07:59:42.000000 pystructs3-0.0.6/pystructs/lists.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     4900 2023-06-25 07:59:42.000000 pystructs3-0.0.6/pystructs/net.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     2523 2023-06-25 18:11:05.000000 pystructs3-0.0.6/pystructs/struct.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:34:31.879695 pystructs3-0.0.6/pystructs/tests/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      323 2023-06-25 07:59:42.000000 pystructs3-0.0.6/pystructs/tests/__init__.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1538 2023-06-25 07:59:42.000000 pystructs3-0.0.6/pystructs/tests/bytestr.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1432 2023-06-25 07:59:42.000000 pystructs3-0.0.6/pystructs/tests/helpers.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     2156 2023-06-25 07:59:42.000000 pystructs3-0.0.6/pystructs/tests/integer.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1824 2023-06-25 07:59:42.000000 pystructs3-0.0.6/pystructs/tests/lists.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     2336 2023-06-25 07:59:42.000000 pystructs3-0.0.6/pystructs/tests/net.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1471 2023-06-25 07:59:42.000000 pystructs3-0.0.6/pystructs/tests/struct.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:34:31.883695 pystructs3-0.0.6/pystructs3.egg-info/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1277 2023-06-28 01:34:31.000000 pystructs3-0.0.6/pystructs3.egg-info/PKG-INFO
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      538 2023-06-28 01:34:31.000000 pystructs3-0.0.6/pystructs3.egg-info/SOURCES.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)        1 2023-06-28 01:34:31.000000 pystructs3-0.0.6/pystructs3.egg-info/dependency_links.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)       28 2023-06-28 01:34:31.000000 pystructs3-0.0.6/pystructs3.egg-info/requires.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)       10 2023-06-28 01:34:31.000000 pystructs3-0.0.6/pystructs3.egg-info/top_level.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)       38 2023-06-28 01:34:31.883695 pystructs3-0.0.6/setup.cfg
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      761 2023-06-28 01:34:18.000000 pystructs3-0.0.6/setup.py
```

### Comparing `pystructs3-0.0.5/LICENSE` & `pystructs3-0.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/PKG-INFO` & `pystructs3-0.0.6/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pystructs3
-Version: 0.0.5
+Version: 0.0.6
 Summary: Dataclass-Like Serialization Helpers for More Complex Data-Types
 Home-page: https://github.com/imgurbot12/pystruct
 Author: Andrew Scott
 Author-email: imgurbot12@gmail.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `pystructs3-0.0.5/README.md` & `pystructs3-0.0.6/README.md`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/pystructs/__init__.py` & `pystructs3-0.0.6/pystructs/__init__.py`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/pystructs/bytestr.py` & `pystructs3-0.0.6/pystructs/bytestr.py`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/pystructs/codec.py` & `pystructs3-0.0.6/pystructs/codec.py`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/pystructs/helpers.py` & `pystructs3-0.0.6/pystructs/helpers.py`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/pystructs/integer.py` & `pystructs3-0.0.6/pystructs/integer.py`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/pystructs/lists.py` & `pystructs3-0.0.6/pystructs/lists.py`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/pystructs/net.py` & `pystructs3-0.0.6/pystructs/net.py`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/pystructs/struct.py` & `pystructs3-0.0.6/pystructs/struct.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 """
 DataClass-Like Struct Implementation
 """
 from typing import Any, Type, Optional, ClassVar
-from typing_extensions import Self, dataclass_transform, get_type_hints
+from typing_extensions import Self, dataclass_transform
 
-from pyderive import MISSING, BaseField, dataclass, fields
+from pyderive import MISSING, BaseField, dataclass, fields, gen_slots
 
 from .codec import *
 
 #** Variables **#
 __all__ = ['field', 'Field', 'Struct']
 
 #: tracker of already compiled struct instances
@@ -19,22 +19,20 @@
 def field(*_, **kwargs) -> Any:
     """apply custom field to struct definition"""
     return Field(**kwargs)
 
 def compile(cls, slots: bool = True, **kwargs):
     """compile uncompiled structs"""
     global COMPILED
-    name   = f'{cls.__module__}.{cls.__name__}'
-    hints  = tuple(get_type_hints(cls).items())
-    tohash = (name, hints)
-    if tohash in COMPILED:
+    if cls in COMPILED:
         return
-    COMPILED.add(tohash)
-    newcls = dataclass(cls, field=Field, slots=slots, **kwargs)
-    setattr(cls, '__slots__', getattr(newcls, '__slots__'))
+    COMPILED.add(cls)
+    dataclass(cls, field=Field, **kwargs)
+    if slots:
+        setattr(cls, '__slots__', gen_slots(cls, fields(cls)))
 
 #** Classes **#
 
 @dataclass(slots=True)
 class Field(BaseField):
     codec: Optional[Type[Codec]] = None
```

### Comparing `pystructs3-0.0.5/pystructs/tests/bytestr.py` & `pystructs3-0.0.6/pystructs/tests/bytestr.py`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/pystructs/tests/helpers.py` & `pystructs3-0.0.6/pystructs/tests/helpers.py`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/pystructs/tests/integer.py` & `pystructs3-0.0.6/pystructs/tests/integer.py`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/pystructs/tests/lists.py` & `pystructs3-0.0.6/pystructs/tests/lists.py`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/pystructs/tests/net.py` & `pystructs3-0.0.6/pystructs/tests/net.py`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/pystructs/tests/struct.py` & `pystructs3-0.0.6/pystructs/tests/struct.py`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/pystructs3.egg-info/PKG-INFO` & `pystructs3-0.0.6/pystructs3.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pystructs3
-Version: 0.0.5
+Version: 0.0.6
 Summary: Dataclass-Like Serialization Helpers for More Complex Data-Types
 Home-page: https://github.com/imgurbot12/pystruct
 Author: Andrew Scott
 Author-email: imgurbot12@gmail.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `pystructs3-0.0.5/pystructs3.egg-info/SOURCES.txt` & `pystructs3-0.0.6/pystructs3.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pystructs3-0.0.5/setup.py` & `pystructs3-0.0.6/setup.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import setup, find_packages
 
 with open("README.md", "r") as f:
     readme = f.read()
 
 setup(
     name='pystructs3',
-    version='0.0.5',
+    version='0.0.6',
     license='MIT',
     author='Andrew Scott',
     author_email='imgurbot12@gmail.com',
     url='https://github.com/imgurbot12/pystruct',
     description="Dataclass-Like Serialization Helpers for More Complex Data-Types",
     long_description=readme,
     long_description_content_type="text/markdown",
```


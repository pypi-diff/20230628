# Comparing `tmp/pyderive3-0.0.4.tar.gz` & `tmp/pyderive3-0.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyderive3-0.0.4.tar", last modified: Sun Jun 25 07:58:23 2023, max compression
+gzip compressed data, was "pyderive3-0.0.5.tar", last modified: Wed Jun 28 01:33:05 2023, max compression
```

## Comparing `pyderive3-0.0.4.tar` & `pyderive3-0.0.5.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 07:58:23.407981 pyderive3-0.0.4/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     2816 2023-06-25 07:58:23.407981 pyderive3-0.0.4/PKG-INFO
--rw-r--r--   0 andrew    (1000) andrew    (1000)     2391 2023-05-28 09:26:37.000000 pyderive3-0.0.4/README.md
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 07:58:23.407981 pyderive3-0.0.4/pyderive/
--rw-r--r--   0 andrew    (1000) andrew    (1000)     1091 2023-05-28 09:09:02.000000 pyderive3-0.0.4/pyderive/__init__.py
--rw-r--r--   0 andrew    (1000) andrew    (1000)     3212 2023-06-24 00:39:03.000000 pyderive3-0.0.4/pyderive/abc.py
--rw-r--r--   0 andrew    (1000) andrew    (1000)     7980 2023-06-24 03:59:51.000000 pyderive3-0.0.4/pyderive/compat.py
--rw-r--r--   0 andrew    (1000) andrew    (1000)    10103 2023-06-24 00:38:08.000000 pyderive3-0.0.4/pyderive/compile.py
--rw-r--r--   0 andrew    (1000) andrew    (1000)    11400 2023-06-23 05:33:39.000000 pyderive3-0.0.4/pyderive/dataclasses.py
--rw-r--r--   0 andrew    (1000) andrew    (1000)     5936 2023-06-23 05:34:23.000000 pyderive3-0.0.4/pyderive/parse.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 07:58:23.407981 pyderive3-0.0.4/pyderive/tests/
--rw-r--r--   0 andrew    (1000) andrew    (1000)      119 2023-05-28 08:41:00.000000 pyderive3-0.0.4/pyderive/tests/__init__.py
--rw-r--r--   0 andrew    (1000) andrew    (1000)     2642 2023-05-28 20:41:04.000000 pyderive3-0.0.4/pyderive/tests/dataclasses.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 07:58:23.407981 pyderive3-0.0.4/pyderive3.egg-info/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     2816 2023-06-25 07:58:23.000000 pyderive3-0.0.4/pyderive3.egg-info/PKG-INFO
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      357 2023-06-25 07:58:23.000000 pyderive3-0.0.4/pyderive3.egg-info/SOURCES.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)        1 2023-06-25 07:58:23.000000 pyderive3-0.0.4/pyderive3.egg-info/dependency_links.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)       18 2023-06-25 07:58:23.000000 pyderive3-0.0.4/pyderive3.egg-info/requires.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)        9 2023-06-25 07:58:23.000000 pyderive3-0.0.4/pyderive3.egg-info/top_level.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)       38 2023-06-25 07:58:23.407981 pyderive3-0.0.4/setup.cfg
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      708 2023-06-25 07:58:03.000000 pyderive3-0.0.4/setup.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:33:05.309698 pyderive3-0.0.5/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     2816 2023-06-28 01:33:05.309698 pyderive3-0.0.5/PKG-INFO
+-rw-r--r--   0 andrew    (1000) andrew    (1000)     2391 2023-05-28 09:26:37.000000 pyderive3-0.0.5/README.md
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:33:05.309698 pyderive3-0.0.5/pyderive/
+-rw-r--r--   0 andrew    (1000) andrew    (1000)     1108 2023-06-25 18:08:28.000000 pyderive3-0.0.5/pyderive/__init__.py
+-rw-r--r--   0 andrew    (1000) andrew    (1000)     3212 2023-06-24 00:39:03.000000 pyderive3-0.0.5/pyderive/abc.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     8018 2023-06-28 01:31:36.000000 pyderive3-0.0.5/pyderive/compat.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)    11414 2023-06-28 01:31:36.000000 pyderive3-0.0.5/pyderive/compile.py
+-rw-r--r--   0 andrew    (1000) andrew    (1000)    11400 2023-06-28 00:17:25.000000 pyderive3-0.0.5/pyderive/dataclasses.py
+-rw-r--r--   0 andrew    (1000) andrew    (1000)     6165 2023-06-26 05:42:29.000000 pyderive3-0.0.5/pyderive/parse.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:33:05.309698 pyderive3-0.0.5/pyderive/tests/
+-rw-r--r--   0 andrew    (1000) andrew    (1000)      119 2023-05-28 08:41:00.000000 pyderive3-0.0.5/pyderive/tests/__init__.py
+-rw-r--r--   0 andrew    (1000) andrew    (1000)     2642 2023-05-28 20:41:04.000000 pyderive3-0.0.5/pyderive/tests/dataclasses.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:33:05.309698 pyderive3-0.0.5/pyderive3.egg-info/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     2816 2023-06-28 01:33:05.000000 pyderive3-0.0.5/pyderive3.egg-info/PKG-INFO
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      357 2023-06-28 01:33:05.000000 pyderive3-0.0.5/pyderive3.egg-info/SOURCES.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)        1 2023-06-28 01:33:05.000000 pyderive3-0.0.5/pyderive3.egg-info/dependency_links.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)       18 2023-06-28 01:33:05.000000 pyderive3-0.0.5/pyderive3.egg-info/requires.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)        9 2023-06-28 01:33:05.000000 pyderive3-0.0.5/pyderive3.egg-info/top_level.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)       38 2023-06-28 01:33:05.309698 pyderive3-0.0.5/setup.cfg
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      708 2023-06-28 01:32:21.000000 pyderive3-0.0.5/setup.py
```

### Comparing `pyderive3-0.0.4/PKG-INFO` & `pyderive3-0.0.5/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyderive3
-Version: 0.0.4
+Version: 0.0.5
 Summary: Python3 Custom Data Class Helpers
 Home-page: https://github.com/imgurbot12/pyderive
 Author: Andrew Scott
 Author-email: imgurbot12@gmail.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `pyderive3-0.0.4/README.md` & `pyderive3-0.0.5/README.md`

 * *Files identical despite different names*

### Comparing `pyderive3-0.0.4/pyderive/__init__.py` & `pyderive3-0.0.5/pyderive/__init__.py`

 * *Files 11% similar despite different names*

```diff
@@ -29,14 +29,15 @@
     'flatten_fields',
 
     'create_init',
     'create_repr',
     'create_compare',
     'create_hash',
     'assign_func',
+    'gen_slots',
     'add_slots',
     'freeze_fields',
 
     'is_dataclass',
     'field',
     'fields',
     'asdict',
```

### Comparing `pyderive3-0.0.4/pyderive/abc.py` & `pyderive3-0.0.5/pyderive/abc.py`

 * *Files identical despite different names*

### Comparing `pyderive3-0.0.4/pyderive/compat.py` & `pyderive3-0.0.5/pyderive/compat.py`

 * *Files 4% similar despite different names*

```diff
@@ -185,15 +185,15 @@
         if is_dataclass(stdfield.default_factory):
             stdfield.default_factory = \
                 std_convert_dataclass(stdfield.default_factory)
         stdfields.append(stdfield)
     return stdfields
 
 @lru_cache(maxsize=int(1e10))
-def std_convert_dataclass(cls):
+def std_convert_dataclass(cls, **kwargs):
     """
     convert pyderive dataclass to stdlib dataclass for 3rd party compatability
     
     :param cls: pyderive dataclass
     :return:    stdlib dataclass
     """
     # confirm class is pyderive dataclas
@@ -206,28 +206,24 @@
     # generate dataclass name/bases/fields
     name   = cls.__name__
     bases  = cls.__mro__
     fields = std_convert_fields(cls)
     attrs  = [(f.name, f.type, f) for f in fields]
     # generate dataclass kwargs based on python version
     params = getattr(cls, PARAMS_ATTR)
-    kwargs = {
-        'init':        bool(params.init),
-        'repr':        bool(params.repr),
-        'eq':          params.eq,
-        'order':       params.order,
-        'unsafe_hash': params.unsafe_hash,
-        'frozen':      params.frozen,
-    }
+    kwargs.setdefault('init', bool(params.init))
+    kwargs.setdefault('repr', bool(params.repr))
+    kwargs.setdefault('eq', params.eq)
+    kwargs.setdefault('order', params.order)
+    kwargs.setdefault('unsafe_hash', params.unsafe_hash)
+    kwargs.setdefault('frozen', params.frozen)
     if sys.version_info.minor >= 10:
-        kwargs.update({
-            'match_args': params.match_args,
-            'kw_only':    params.kw_only,
-            'slots':      params.slots,
-        })
+        kwargs.setdefault('match_args', params.match_args)
+        kwargs.setdefault('kw_only', params.kw_only)
+        kwargs.setdefault('slots', params.slots)
     # finalize dataclass generation
     dataclass = dataclasses.make_dataclass(name, attrs, bases=bases, **kwargs)
     # #NOTE: this magic resolves some seemingly random issues when passing 
     # # dataclasses to other 3rd party libraries
     @dataclasses.dataclass
     class DataClass(dataclass):
         pass
```

### Comparing `pyderive3-0.0.4/pyderive/compile.py` & `pyderive3-0.0.5/pyderive/compile.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,27 +1,28 @@
 """
 DataClass Compiler Utilities
 """
 from reprlib import recursive_repr
 from types import FunctionType
-from typing import Iterator, Type, List, Optional, Any, Callable, Dict
+from typing import Iterator, Tuple, Type, List, Optional, Any, Callable, Dict
 
 from .abc import *
 
 #** Variables **#
 __all__ = [
     'POST_INIT',
     'HDF',
     'HDF_VAR',
 
     'create_init',
     'create_repr',
     'create_compare',
     'create_hash',
     'assign_func',
+    'gen_slots',
     'add_slots',
     'freeze_fields',
 ]
 
 #: post init function
 POST_INIT = '__post_init__'
 
@@ -109,16 +110,23 @@
     :return:          generated init-function made from specifications
     """
     self_name = 'self'
     locals:  Dict[str, Any] = {}
     globals: Dict[str, Any] = {HDF_VAR: HDF}
     args, post, body, kwonly = ['self'], [], [], []
     for field in fields:
+        # handle non-init edge cases
+        name = field.name
+        if not field.init and field.default is MISSING \
+            and field.default_factory is MISSING:
+            # raise an error if field is an init-var
+            if field.field_type == FieldType.INIT_VAR:
+                raise TypeError(f'field {name!r} must have init as InitVar')
+            continue
         # build parameter code
-        name  = field.name
         param = _init_param(field)
         value = _init_value(field, globals)
         if field.init:
             if kw_only or field.kw_only:
                 kwonly.append(param)
             else:
                 args.append(param)
@@ -178,15 +186,15 @@
     """
     names  = [f.name for f in _stdfields(fields) if f.compare]
     self_t  = _tuple_str(names, 'self') 
     other_t = _tuple_str(names, 'other')  
     return _create_fn(func, ['self', 'other'], [
          'if other.__class__ is self.__class__:',
         f' return {self_t} {op} {other_t}',
-         'raise NotImplemented',
+         'return NotImplemented',
     ])
 
 def create_hash(fields: Fields) -> Callable:
     """
     generate hash-function for hashable fields
 
     :param fields: ordered fields used to generate hash-function
@@ -212,20 +220,41 @@
     if not overwrite and name in cls.__dict__:
         return True
     if isinstance(func, FunctionType):
         func.__qualname__ = f'{cls.__qualname__}.{func.__name__}'
     setattr(cls, name, func)
     return False
 
-def add_slots(cls: Type, fields: Fields, frozen: bool = False) -> Type:
+def gen_slots(cls: Type, fields: Fields) -> Tuple[str, ...]:
     """
     generate slots for fields connected to the given class object
 
+    WARNING: gen-slots cannot be applied to already generated
+             class objects. only during evaluation by a meta-class
+             or something similar. WHEN UNSURE USE ADD_SLOTS INSTEAD
+
+    :param cls:    class-object to assign slots onto
+    :param fields: field structure to control slot definition
+    """
+    fields = list(_stdfields(fields))
+    if '__slots__' in cls.__dict__:
+        raise TypeError(f'{cls.__name__} already specifies __slots__')
+    # ensure slots don't overlap with bases-classes
+    slots      = [f.name for f in fields]
+    bases      = cls.__mro__[1:-1]
+    base_slots = {s for b in bases for s in getattr(b, '__slots__', [])}
+    return tuple([s for s in slots if s not in base_slots])
+
+def add_slots(cls: Type, fields: Fields, frozen: bool = False) -> Type:
+    """
+    attach slots for fields connected to the given class object
+
     :param cls:    class-object to assign slots onto
     :param fields: field structure to control slot definition
+    :param frozen: apply additional methods when handing a frozen object
     :return:       updated class object
     """
     fields   = list(_stdfields(fields))
     cls_dict = dict(cls.__dict__)
     if '__slots__' in cls_dict:
         raise TypeError(f'{cls.__name__} already specifies __slots__')
     # ensure slots don't overlap with bases-classes and assign to dict
```

### Comparing `pyderive3-0.0.4/pyderive/dataclasses.py` & `pyderive3-0.0.5/pyderive/dataclasses.py`

 * *Files identical despite different names*

### Comparing `pyderive3-0.0.4/pyderive/parse.py` & `pyderive3-0.0.5/pyderive/parse.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,14 +18,16 @@
 
 #: raw field attribute name
 DERIVE_ATTR = '__derive__'
 
 #: track hashes of already compiled baseclasses
 COMPILED = set()
 
+COMPILED_ANNOTATIONS = set()
+
 #** Functions **#
 
 def remove_field(fields: ClassStruct, name: str):
     """
     remove field-name from fields heigharchy
     """
     current: Optional[ClassStruct] = fields
@@ -48,18 +50,18 @@
     :param base:    baseclass type to retrieve annotations/values from
     :param factory: field type factory used to produce fields
     :param recurse: enable recursive handling of field parsing if true
     :param delete:  delete values from class when found if true
     :param strict:  be strict on factory field type during parsing
     :return:        unprocessed dataclass field definitions
     """
-    global COMPILED
+    global COMPILED, COMPILED_ANNOTATIONS
     bases  = list(cls.__mro__) if recurse else [cls]
     fields = None
-    ftype: Type[FieldDef] = factory if strict else FieldDef #type: ignore
+    ftype: Type[FieldDef] = factory if strict else FieldDef
     while bases:
         # skip builtin bases
         base = bases.pop()
         if base is object:
             continue
         # skip if recursive and already compiled
         if recurse and hash(base) in COMPILED:
@@ -67,17 +69,21 @@
         COMPILED.add(hash(base))
         # convert stdlib dataclass fields to valid class-struct
         parent = getattr(base, DERIVE_ATTR, None)
         if parent is None and is_stddataclass(base):
             fields = convert_fields(base, ftype)
             names  = [f.name for f in fields]
             parent = ClassStruct(names, {f.name:f for f in fields})
-        # process fields
-        fields      = ClassStruct(parent=parent)
+        fields = ClassStruct(parent=parent)
+        # skip evaluations is annotations have already been checked
         annotations = getattr(base, '__annotations__', {})
+        if id(annotations) in COMPILED_ANNOTATIONS:
+            continue
+        COMPILED_ANNOTATIONS.add(id(annotations))
+        # iterate annotations
         for name, anno in annotations.items():
             # handle ClassVar
             if get_origin(anno) is ClassVar:
                 remove_field(fields, name)
                 continue
             # retrieve default-value of variable (if exists)
             default     = getattr(base, name, MISSING)
```

### Comparing `pyderive3-0.0.4/pyderive/tests/dataclasses.py` & `pyderive3-0.0.5/pyderive/tests/dataclasses.py`

 * *Files identical despite different names*

### Comparing `pyderive3-0.0.4/pyderive3.egg-info/PKG-INFO` & `pyderive3-0.0.5/pyderive3.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyderive3
-Version: 0.0.4
+Version: 0.0.5
 Summary: Python3 Custom Data Class Helpers
 Home-page: https://github.com/imgurbot12/pyderive
 Author: Andrew Scott
 Author-email: imgurbot12@gmail.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `pyderive3-0.0.4/setup.py` & `pyderive3-0.0.5/setup.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import setup, find_packages
 
 with open("README.md", "r") as f:
     readme = f.read()
 
 setup(
     name='pyderive3',
-    version='0.0.4',
+    version='0.0.5',
     license='MIT',
     author='Andrew Scott',
     author_email='imgurbot12@gmail.com',
     url='https://github.com/imgurbot12/pyderive',
     description="Python3 Custom Data Class Helpers",
     long_description=readme,
     long_description_content_type="text/markdown",
```


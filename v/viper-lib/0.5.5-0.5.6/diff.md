# Comparing `tmp/viper_lib-0.5.5.tar.gz` & `tmp/viper_lib-0.5.6.tar.gz`

## Comparing `viper_lib-0.5.5.tar` & `viper_lib-0.5.6.tar`

### file list

```diff
@@ -1,56 +1,31 @@
--rw-r--r--   0        0        0       23 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper.pth
--rw-r--r--   0        0        0     7097 2020-02-02 00:00:00.000000 viper_lib-0.5.5/async_utils.py
--rw-r--r--   0        0        0       93 2020-02-02 00:00:00.000000 viper_lib-0.5.5/cucumber.py
--rw-r--r--   0        0        0     2463 2020-02-02 00:00:00.000000 viper_lib-0.5.5/cucumber_main.py
--rw-r--r--   0        0        0     2251 2020-02-02 00:00:00.000000 viper_lib-0.5.5/persistent.py
--rw-r--r--   0        0        0       44 2020-02-02 00:00:00.000000 viper_lib-0.5.5/test.py
--rw-r--r--   0        0        0     1177 2020-02-02 00:00:00.000000 viper_lib-0.5.5/test_client.py
--rw-r--r--   0        0        0      841 2020-02-02 00:00:00.000000 viper_lib-0.5.5/test_server.py
--rw-r--r--   0        0        0      379 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/__init__.py
--rw-r--r--   0        0        0    10263 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/better_threading.py
--rw-r--r--   0        0        0      246 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/exceptions.py
--rw-r--r--   0        0        0     2084 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/format.py
--rw-r--r--   0        0        0     2744 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/frozendict.py
--rw-r--r--   0        0        0     2412 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/interactive.py
--rw-r--r--   0        0        0    15408 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/pickle_utils.py
--rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/warnings.py
--rw-r--r--   0        0        0       94 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/abc/__init__.py
--rw-r--r--   0        0        0     7181 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/abc/connection.py
--rw-r--r--   0        0        0     2957 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/abc/flux.py
--rw-r--r--   0        0        0     9410 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/abc/io.py
--rw-r--r--   0        0        0      108 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/building/__init__.py
--rw-r--r--   0        0        0     2898 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/building/module_tools.py
--rw-r--r--   0        0        0       74 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/compress/__init__.py
--rw-r--r--   0        0        0     8976 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/compress/flux.py
--rw-r--r--   0        0        0       81 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/debugging/__init__.py
--rw-r--r--   0        0        0    13402 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/debugging/chrono.py
--rw-r--r--   0        0        0     1359 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/debugging/utils.py
--rw-r--r--   0        0        0      153 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/meta/__init__.py
--rw-r--r--   0        0        0     5606 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/meta/decorators.py
--rw-r--r--   0        0        0    16443 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/meta/iterable.py
--rw-r--r--   0        0        0    17549 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/meta/procedural.py
--rw-r--r--   0        0        0     6223 2020-02-02 00:00:00.000000 viper_lib-0.5.5/Viper/meta/utils.py
--rw-r--r--   0        0        0      924 2020-02-02 00:00:00.000000 viper_lib-0.5.5/building/cy_clean.py
--rw-r--r--   0        0        0     1593 2020-02-02 00:00:00.000000 viper_lib-0.5.5/building/cy_compile.py
--rw-r--r--   0        0        0      231 2020-02-02 00:00:00.000000 viper_lib-0.5.5/crypto/__init__.py
--rw-r--r--   0        0        0      734 2020-02-02 00:00:00.000000 viper_lib-0.5.5/crypto/exceptions.py
--rw-r--r--   0        0        0    27802 2020-02-02 00:00:00.000000 viper_lib-0.5.5/crypto/flux.py
--rw-r--r--   0        0        0     5797 2020-02-02 00:00:00.000000 viper_lib-0.5.5/crypto/session.py
--rw-r--r--   0        0        0     4204 2020-02-02 00:00:00.000000 viper_lib-0.5.5/crypto/utils.py
--rw-r--r--   0        0        0       79 2020-02-02 00:00:00.000000 viper_lib-0.5.5/evolve/__init__.py
--rw-r--r--   0        0        0      874 2020-02-02 00:00:00.000000 viper_lib-0.5.5/evolve/primitives.py
--rw-r--r--   0        0        0       90 2020-02-02 00:00:00.000000 viper_lib-0.5.5/evolve/types/__init__.py
--rw-r--r--   0        0        0      118 2020-02-02 00:00:00.000000 viper_lib-0.5.5/evolve/types/utils.py
--rw-r--r--   0        0        0      680 2020-02-02 00:00:00.000000 viper_lib-0.5.5/meta/contextual.py
--rw-r--r--   0        0        0      184 2020-02-02 00:00:00.000000 viper_lib-0.5.5/meta/prototype.py
--rw-r--r--   0        0        0     2108 2020-02-02 00:00:00.000000 viper_lib-0.5.5/meta/secret.py
--rw-r--r--   0        0        0      766 2020-02-02 00:00:00.000000 viper_lib-0.5.5/meta/specialized.py
--rw-r--r--   0        0        0    15921 2020-02-02 00:00:00.000000 viper_lib-0.5.5/meta/static.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 viper_lib-0.5.5/partition/__init__.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 viper_lib-0.5.5/partition/memory.py
--rw-r--r--   0        0        0    14044 2020-02-02 00:00:00.000000 viper_lib-0.5.5/partition/primitives.py
--rw-r--r--   0        0        0     1945 2020-02-02 00:00:00.000000 viper_lib-0.5.5/.gitignore
--rw-r--r--   0        0        0     1092 2020-02-02 00:00:00.000000 viper_lib-0.5.5/LICENSE
--rw-r--r--   0        0        0      974 2020-02-02 00:00:00.000000 viper_lib-0.5.5/README.md
--rw-r--r--   0        0        0      724 2020-02-02 00:00:00.000000 viper_lib-0.5.5/pyproject.toml
--rw-r--r--   0        0        0     2725 2020-02-02 00:00:00.000000 viper_lib-0.5.5/PKG-INFO
+-rw-r--r--   0        0        0       23 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper.pth
+-rw-r--r--   0        0        0      208 2020-02-02 00:00:00.000000 viper_lib-0.5.6/token.txt
+-rw-r--r--   0        0        0      379 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/__init__.py
+-rw-r--r--   0        0        0    10263 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/better_threading.py
+-rw-r--r--   0        0        0      246 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/exceptions.py
+-rw-r--r--   0        0        0     2084 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/format.py
+-rw-r--r--   0        0        0     2744 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/frozendict.py
+-rw-r--r--   0        0        0     2412 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/interactive.py
+-rw-r--r--   0        0        0    15408 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/pickle_utils.py
+-rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/warnings.py
+-rw-r--r--   0        0        0       94 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/abc/__init__.py
+-rw-r--r--   0        0        0     7181 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/abc/connection.py
+-rw-r--r--   0        0        0     2957 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/abc/flux.py
+-rw-r--r--   0        0        0     9410 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/abc/io.py
+-rw-r--r--   0        0        0      108 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/building/__init__.py
+-rw-r--r--   0        0        0     2898 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/building/module_tools.py
+-rw-r--r--   0        0        0       74 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/compress/__init__.py
+-rw-r--r--   0        0        0     8976 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/compress/flux.py
+-rw-r--r--   0        0        0       81 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/debugging/__init__.py
+-rw-r--r--   0        0        0    13402 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/debugging/chrono.py
+-rw-r--r--   0        0        0     1359 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/debugging/utils.py
+-rw-r--r--   0        0        0      153 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/meta/__init__.py
+-rw-r--r--   0        0        0     5606 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/meta/decorators.py
+-rw-r--r--   0        0        0    16528 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/meta/iterable.py
+-rw-r--r--   0        0        0    17549 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/meta/procedural.py
+-rw-r--r--   0        0        0     6223 2020-02-02 00:00:00.000000 viper_lib-0.5.6/Viper/meta/utils.py
+-rw-r--r--   0        0        0     1945 2020-02-02 00:00:00.000000 viper_lib-0.5.6/.gitignore
+-rw-r--r--   0        0        0     1092 2020-02-02 00:00:00.000000 viper_lib-0.5.6/LICENSE
+-rw-r--r--   0        0        0      974 2020-02-02 00:00:00.000000 viper_lib-0.5.6/README.md
+-rw-r--r--   0        0        0      724 2020-02-02 00:00:00.000000 viper_lib-0.5.6/pyproject.toml
+-rw-r--r--   0        0        0     2725 2020-02-02 00:00:00.000000 viper_lib-0.5.6/PKG-INFO
```

### Comparing `viper_lib-0.5.5/Viper/better_threading.py` & `viper_lib-0.5.6/Viper/better_threading.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/format.py` & `viper_lib-0.5.6/Viper/format.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/frozendict.py` & `viper_lib-0.5.6/Viper/frozendict.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/interactive.py` & `viper_lib-0.5.6/Viper/interactive.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/pickle_utils.py` & `viper_lib-0.5.6/Viper/pickle_utils.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/warnings.py` & `viper_lib-0.5.6/Viper/warnings.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/abc/connection.py` & `viper_lib-0.5.6/Viper/abc/connection.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/abc/flux.py` & `viper_lib-0.5.6/Viper/abc/flux.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/abc/io.py` & `viper_lib-0.5.6/Viper/abc/io.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/building/module_tools.py` & `viper_lib-0.5.6/Viper/building/module_tools.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/compress/flux.py` & `viper_lib-0.5.6/Viper/compress/flux.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/debugging/chrono.py` & `viper_lib-0.5.6/Viper/debugging/chrono.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/debugging/utils.py` & `viper_lib-0.5.6/Viper/debugging/utils.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/meta/decorators.py` & `viper_lib-0.5.6/Viper/meta/decorators.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/meta/iterable.py` & `viper_lib-0.5.6/Viper/meta/iterable.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 """
 This module adds metaclasses that make classes iterable, yielding all of their instances.
 """
 
 
-from typing import Any, Iterator, Sequence, TypeVar, Type
-from weakref import WeakSet, WeakValueDictionary
+from typing import Any, Generator, Sequence, TypeVar
+from weakref import WeakValueDictionary
 
 __all__ = ["InstanceReferencingClass", "InstancePreservingClass", "InstanceReferencingHierarchy", "InstancePreservingHierarchy"]
 
 
 
 
 
@@ -38,15 +38,17 @@
     >>> del a
     >>> print(list(A))
     [A(b)]
     >>> len(A)
     1
     """
 
-    def __new__(cls : Type["InstanceReferencingClass"], name : str, bases : tuple[type], dct : dict):
+    __instances : WeakValueDictionary[int, Any]
+
+    def __new__(cls, name : str, bases : tuple[type], dct : dict):
         """
         Implements the creation of a new class
         """
         from .utils import signature_def, signature_call
         from typing import Iterable
         from functools import wraps
         from weakref import WeakValueDictionary
@@ -62,17 +64,18 @@
 
         added = False
 
         # Finding the __new__ method 
         old_new = None
         if "__new__" in dct:
             old_new = dct["__new__"]
-        for b in bases:
-            if hasattr(b, "__new__"):
-                old_new = getattr(b, "__new__")
+        else:
+            for b in bases:
+                if hasattr(b, "__new__"):
+                    old_new = getattr(b, "__new__")
         if old_new == None:
             old_new = object.__new__
 
         sig = "@wraps(old_target)\n"
 
         sig_def, env = signature_def(old_new, init_env = {"old_target" : old_new, "wraps" : wraps, "cls_dict" : s})
         
@@ -109,19 +112,19 @@
                 cls = super().__new__(cls, name, bases, dct)
             else:
                 raise
         # The Weakdict that will store all instances
         cls.__instances = s
         return cls
     
-    def __iter__(self : Type[T]) -> Iterator[T]:
+    def __iter__(self : type[T]) -> Generator[T, None, None]:
         """
         Implements the iteration over the class' instances
         """
-        return iter(self.__instances.values())
+        yield from tuple(self.__instances.values())
     
     def __len__(self) -> int:
         """
         Implements the len of this class (the number of existing instances)
         """
         return len(self.__instances)
 
@@ -152,15 +155,15 @@
     >>> del a
     >>> print(list(A))
     [A(a), A(b)]
     >>> len(A)
     2
     """
 
-    def __new__(cls : type["InstancePreservingClass"], name : str, bases : tuple[type], dct : dict):
+    def __new__(cls, name : str, bases : tuple[type], dct : dict):
         """
         Implements the creation of a new class
         """
         from .utils import signature_def, signature_call
         from functools import wraps
 
         s = []
@@ -174,17 +177,18 @@
 
         added = False
 
         # Finding the __new__ method 
         old_new = None
         if "__new__" in dct:
             old_new = dct["__new__"]
-        for b in bases:
-            if hasattr(b, "__new__"):
-                old_new = getattr(b, "__new__")
+        else:
+            for b in bases:
+                if hasattr(b, "__new__"):
+                    old_new = getattr(b, "__new__")
         if old_new == None:
             old_new = object.__new__
 
         sig = "@wraps(old_target)\n"
 
         sig_def, env = signature_def(old_new, init_env = {"old_target" : old_new, "wraps" : wraps, "cls_list" : s})
         
@@ -219,19 +223,19 @@
                 cls = super().__new__(cls, name, bases, dct)
             else:
                 raise
         # The list that will store all instances
         cls.__instances = s
         return cls
     
-    def __iter__(self : type[T]) -> Iterator[T]:
+    def __iter__(self : type[T]) -> Generator[T, None, None]:
         """
         Implements the iteration over the class' instances
         """
-        return iter(self.__instances)
+        yield from tuple(self.__instances)
     
     def __len__(self) -> int:
         """
         Implements the len of this class (the number of existing instances)
         """
         return len(self.__instances)
 
@@ -263,17 +267,17 @@
     >>> list(C)
     [<__main__.C object at 0x000001C607E30EE0>]
     >>> del b
     >>> list(A)
     [<__main__.A object at 0x000001C607E309A0>, <__main__.A object at 0x000001C607E309D0>]
     """
 
-    __instances : dict[type[T], WeakValueDictionary[int, T]] = {}
+    __instances : dict[type, WeakValueDictionary[int, Any]] = {}
 
-    def __new__(cls : type["InstanceReferencingHierarchy"], name : str, bases : tuple[type], dct : dict):
+    def __new__(cls, name : str, bases : tuple[type], dct : dict):
         """
         Implements the creation of a new class
         """            
         from weakref import WeakValueDictionary
         from .utils import signature_def, signature_call
         from functools import wraps
 
@@ -295,17 +299,18 @@
             elif isinstance(cls, (Sequence)):
                 dct["__slots__"] = list(dct["__slots__"]) + ["__weakref__"]
         
         # Finding the __new__ method 
         old_new = None
         if "__new__" in dct:
             old_new = dct["__new__"]
-        for b in bases:
-            if hasattr(b, "__new__"):
-                old_new = getattr(b, "__new__")
+        else:
+            for b in bases:
+                if hasattr(b, "__new__"):
+                    old_new = getattr(b, "__new__")
         if old_new == None:
             old_new = object.__new__
         
         sig = "@wraps(old_target)\n"
 
         sig_def, env = signature_def(old_new, init_env = {"old_target" : old_new, "wraps" : wraps, "cls_dict" : s})
         
@@ -335,28 +340,28 @@
                 cls = super().__new__(cls, name, bases, dct)
             else:
                 raise
         # The Weakdict that will store all instances
         InstanceReferencingHierarchy.__instances[cls] = s
         return cls
 
-    def __iter__(self : type[T]) -> Iterator[T]:
+    def __iter__(self : type[T]) -> Generator[T, None, None]:
         """
         Implements the iteration over the class' instances
         """
-        for cls, cls_set in set(InstanceReferencingHierarchy.__instances.items()):
+        for cls, cls_set in tuple(InstanceReferencingHierarchy.__instances.items()):
             if issubclass(cls, self):
                 yield from cls_set.values()
     
     def __len__(self) -> int:
         """
         Implements the len of this class (the number of existing instances)
         """
         l = 0
-        for cls, cls_set in set(InstanceReferencingHierarchy.__instances.items()):
+        for cls, cls_set in tuple(InstanceReferencingHierarchy.__instances.items()):
             if issubclass(cls, self):
                 l += len(cls_set)
         return l
 
 
 
 
@@ -386,17 +391,17 @@
     >>> list(C)
     [<__main__.C object at 0x000001C607E30EE0>]
     >>> del b
     >>> list(A)
     [<__main__.B object at 0x000001C607E30A00>, <__main__.A object at 0x000001C607E309A0>, <__main__.A object at 0x000001C607E309D0>]
     """
 
-    __instances : dict[type[T], list[T]] = {}
+    __instances : dict[type, list] = {}
 
-    def __new__(cls : type["InstancePreservingHierarchy"], name : str, bases : tuple[type], dct : dict):
+    def __new__(cls, name : str, bases : tuple[type], dct : dict):
         """
         Implements the creation of a new class
         """
         from .utils import signature_def, signature_call
         from functools import wraps
 
         s = []
@@ -410,17 +415,18 @@
 
         added = False
 
         # Finding the __new__ method 
         old_new = None
         if "__new__" in dct:
             old_new = dct["__new__"]
-        for b in bases:
-            if hasattr(b, "__new__"):
-                old_new = getattr(b, "__new__")
+        else:
+            for b in bases:
+                if hasattr(b, "__new__"):
+                    old_new = getattr(b, "__new__")
         if old_new == None:
             old_new = object.__new__
         
         sig = "@wraps(old_target)\n"
 
         sig_def, env = signature_def(old_new, init_env = {"old_target" : old_new, "wraps" : wraps, "cls_list" : s})
         
@@ -455,30 +461,30 @@
                 cls = super().__new__(cls, name, bases, dct)
             else:
                 raise
         # The list that will store all instances
         InstancePreservingHierarchy.__instances[cls] = s
         return cls
     
-    def __iter__(self : type[T]) -> Iterator[T]:
+    def __iter__(self : type[T]) -> Generator[T, None, None]:
         """
         Implements the iteration over the class' instances
         """
-        for cls, cls_set in InstancePreservingHierarchy.__instances.items():
+        for cls, cls_set in tuple(InstancePreservingHierarchy.__instances.items()):
             if issubclass(cls, self):
                 yield from cls_set
     
     def __len__(self) -> int:
         """
         Implements the len of this class (the number of existing instances)
         """
         l = 0
-        for cls, cls_set in InstancePreservingHierarchy.__instances.items():
+        for cls, cls_set in tuple(InstancePreservingHierarchy.__instances.items()):
             if issubclass(cls, self):
                 l += len(cls_set)
         return l
 
 
 
     
 
-del Any, Iterator, Sequence, TypeVar, T, WeakSet
+del T, Any, Generator, Sequence, TypeVar, WeakValueDictionary
```

### Comparing `viper_lib-0.5.5/Viper/meta/procedural.py` & `viper_lib-0.5.6/Viper/meta/procedural.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/Viper/meta/utils.py` & `viper_lib-0.5.6/Viper/meta/utils.py`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/.gitignore` & `viper_lib-0.5.6/.gitignore`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/LICENSE` & `viper_lib-0.5.6/LICENSE`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/README.md` & `viper_lib-0.5.6/README.md`

 * *Files identical despite different names*

### Comparing `viper_lib-0.5.5/pyproject.toml` & `viper_lib-0.5.6/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["hatchling"]
 build-backend = "hatchling.build"
 
 [project]
 name = "viper_lib"
-version = "0.5.5"
+version = "0.5.6"
 authors = [
   { name="Vincent Raulin", email="vincent.raulin.n7@gmail.com" },
 ]
 description = "A Python library full of useful Python tools."
 readme = "README.md"
 license = {file = "LICENSE"}
 requires-python = ">=3.10"
```

### Comparing `viper_lib-0.5.5/PKG-INFO` & `viper_lib-0.5.6/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: viper_lib
-Version: 0.5.5
+Version: 0.5.6
 Summary: A Python library full of useful Python tools.
 Project-URL: Repository, https://github.com/MrVoustache/Viper
 Project-URL: Bug Tracker, https://github.com/MrVoustache/Viper/issues
 Author-email: Vincent Raulin <vincent.raulin.n7@gmail.com>
 License: MIT License
         
         Copyright (c) 2023 Vincent Raulin
```


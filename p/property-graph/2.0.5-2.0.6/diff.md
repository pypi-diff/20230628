# Comparing `tmp/property-graph-2.0.5.tar.gz` & `tmp/property-graph-2.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "property-graph-2.0.5.tar", last modified: Thu Jun 22 16:00:53 2023, max compression
+gzip compressed data, was "property-graph-2.0.6.tar", last modified: Wed Jun 28 02:22:25 2023, max compression
```

## Comparing `property-graph-2.0.5.tar` & `property-graph-2.0.6.tar`

### file list

```diff
@@ -1,44 +1,44 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-22 16:00:53.603831 property-graph-2.0.5/
--rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-22 16:00:44.000000 property-graph-2.0.5/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18100 2023-06-22 16:00:53.603831 property-graph-2.0.5/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     4568 2023-06-22 16:00:44.000000 property-graph-2.0.5/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      757 2023-06-22 16:00:44.000000 property-graph-2.0.5/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-22 16:00:53.603831 property-graph-2.0.5/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-22 16:00:53.599831 property-graph-2.0.5/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-22 16:00:53.599831 property-graph-2.0.5/src/property_graph.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18100 2023-06-22 16:00:53.000000 property-graph-2.0.5/src/property_graph.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-22 16:00:53.000000 property-graph-2.0.5/src/property_graph.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-22 16:00:53.000000 property-graph-2.0.5/src/property_graph.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        5 2023-06-22 16:00:53.000000 property-graph-2.0.5/src/property_graph.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-22 16:00:53.603831 property-graph-2.0.5/src/pypg/
--rw-r--r--   0 runner    (1001) docker     (123)      161 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1629 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/locator.py
--rw-r--r--   0 runner    (1001) docker     (123)    16939 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/property.py
--rw-r--r--   0 runner    (1001) docker     (123)     1855 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/property_transcoder.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-22 16:00:53.603831 property-graph-2.0.5/src/pypg/traits/
--rw-r--r--   0 runner    (1001) docker     (123)      175 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/traits/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2725 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/traits/allowed_range.py
--rw-r--r--   0 runner    (1001) docker     (123)      990 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/traits/config.py
--rw-r--r--   0 runner    (1001) docker     (123)      138 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/traits/metadata.py
--rw-r--r--   0 runner    (1001) docker     (123)      622 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/traits/obligate.py
--rw-r--r--   0 runner    (1001) docker     (123)     4932 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/traits/observable.py
--rw-r--r--   0 runner    (1001) docker     (123)     3793 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/traits/overridable.py
--rw-r--r--   0 runner    (1001) docker     (123)      526 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/traits/read_only.py
--rw-r--r--   0 runner    (1001) docker     (123)      164 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/traits/unit.py
--rw-r--r--   0 runner    (1001) docker     (123)      535 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/traits/validated.py
--rw-r--r--   0 runner    (1001) docker     (123)    11774 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/transcode.py
--rw-r--r--   0 runner    (1001) docker     (123)      808 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/type_registry.py
--rw-r--r--   0 runner    (1001) docker     (123)      783 2023-06-22 16:00:44.000000 property-graph-2.0.5/src/pypg/type_utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-22 16:00:53.603831 property-graph-2.0.5/tests/
--rw-r--r--   0 runner    (1001) docker     (123)     4127 2023-06-22 16:00:44.000000 property-graph-2.0.5/tests/test_allowed_range.py
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-06-22 16:00:44.000000 property-graph-2.0.5/tests/test_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     1105 2023-06-22 16:00:44.000000 property-graph-2.0.5/tests/test_locator.py
--rw-r--r--   0 runner    (1001) docker     (123)      567 2023-06-22 16:00:44.000000 property-graph-2.0.5/tests/test_obligate.py
--rw-r--r--   0 runner    (1001) docker     (123)     3383 2023-06-22 16:00:44.000000 property-graph-2.0.5/tests/test_observable.py
--rw-r--r--   0 runner    (1001) docker     (123)     4142 2023-06-22 16:00:44.000000 property-graph-2.0.5/tests/test_overridable.py
--rw-r--r--   0 runner    (1001) docker     (123)     2539 2023-06-22 16:00:44.000000 property-graph-2.0.5/tests/test_property.py
--rw-r--r--   0 runner    (1001) docker     (123)      545 2023-06-22 16:00:44.000000 property-graph-2.0.5/tests/test_readonly.py
--rw-r--r--   0 runner    (1001) docker     (123)     1343 2023-06-22 16:00:44.000000 property-graph-2.0.5/tests/test_traits.py
--rw-r--r--   0 runner    (1001) docker     (123)     2966 2023-06-22 16:00:44.000000 property-graph-2.0.5/tests/test_transcoder.py
--rw-r--r--   0 runner    (1001) docker     (123)     1506 2023-06-22 16:00:44.000000 property-graph-2.0.5/tests/test_type_registry.py
--rw-r--r--   0 runner    (1001) docker     (123)     1472 2023-06-22 16:00:44.000000 property-graph-2.0.5/tests/test_type_schema_encoding.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 02:22:25.488690 property-graph-2.0.6/
+-rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 02:22:16.000000 property-graph-2.0.6/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18100 2023-06-28 02:22:25.488690 property-graph-2.0.6/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4568 2023-06-28 02:22:16.000000 property-graph-2.0.6/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      757 2023-06-28 02:22:16.000000 property-graph-2.0.6/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 02:22:25.488690 property-graph-2.0.6/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 02:22:25.472690 property-graph-2.0.6/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 02:22:25.476690 property-graph-2.0.6/src/property_graph.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18100 2023-06-28 02:22:25.000000 property-graph-2.0.6/src/property_graph.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 02:22:25.000000 property-graph-2.0.6/src/property_graph.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 02:22:25.000000 property-graph-2.0.6/src/property_graph.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        5 2023-06-28 02:22:25.000000 property-graph-2.0.6/src/property_graph.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 02:22:25.480690 property-graph-2.0.6/src/pypg/
+-rw-r--r--   0 runner    (1001) docker     (123)      161 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1629 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/locator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16969 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/property.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1855 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/property_transcoder.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 02:22:25.484690 property-graph-2.0.6/src/pypg/traits/
+-rw-r--r--   0 runner    (1001) docker     (123)      175 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/traits/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2725 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/traits/allowed_range.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1239 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/traits/config.py
+-rw-r--r--   0 runner    (1001) docker     (123)      138 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/traits/metadata.py
+-rw-r--r--   0 runner    (1001) docker     (123)      622 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/traits/obligate.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4932 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/traits/observable.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3793 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/traits/overridable.py
+-rw-r--r--   0 runner    (1001) docker     (123)      526 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/traits/read_only.py
+-rw-r--r--   0 runner    (1001) docker     (123)      164 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/traits/unit.py
+-rw-r--r--   0 runner    (1001) docker     (123)      535 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/traits/validated.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11774 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/transcode.py
+-rw-r--r--   0 runner    (1001) docker     (123)      808 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/type_registry.py
+-rw-r--r--   0 runner    (1001) docker     (123)      783 2023-06-28 02:22:16.000000 property-graph-2.0.6/src/pypg/type_utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 02:22:25.488690 property-graph-2.0.6/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     4127 2023-06-28 02:22:16.000000 property-graph-2.0.6/tests/test_allowed_range.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1648 2023-06-28 02:22:16.000000 property-graph-2.0.6/tests/test_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1105 2023-06-28 02:22:16.000000 property-graph-2.0.6/tests/test_locator.py
+-rw-r--r--   0 runner    (1001) docker     (123)      567 2023-06-28 02:22:16.000000 property-graph-2.0.6/tests/test_obligate.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3383 2023-06-28 02:22:16.000000 property-graph-2.0.6/tests/test_observable.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4142 2023-06-28 02:22:16.000000 property-graph-2.0.6/tests/test_overridable.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2539 2023-06-28 02:22:16.000000 property-graph-2.0.6/tests/test_property.py
+-rw-r--r--   0 runner    (1001) docker     (123)      545 2023-06-28 02:22:16.000000 property-graph-2.0.6/tests/test_readonly.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1343 2023-06-28 02:22:16.000000 property-graph-2.0.6/tests/test_traits.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2966 2023-06-28 02:22:16.000000 property-graph-2.0.6/tests/test_transcoder.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1506 2023-06-28 02:22:16.000000 property-graph-2.0.6/tests/test_type_registry.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1472 2023-06-28 02:22:16.000000 property-graph-2.0.6/tests/test_type_schema_encoding.py
```

### Comparing `property-graph-2.0.5/LICENSE` & `property-graph-2.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/PKG-INFO` & `property-graph-2.0.6/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: property-graph
-Version: 2.0.5
+Version: 2.0.6
 Summary: python library for working with objects as graphs of property data
 Author-email: Matt Fowler <mattefowler@gmail.com>
 License:                                  Apache License
                                    Version 2.0, January 2004
                                 http://www.apache.org/licenses/
         
            TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION
```

### Comparing `property-graph-2.0.5/README.md` & `property-graph-2.0.6/README.md`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/pyproject.toml` & `property-graph-2.0.6/pyproject.toml`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/src/property_graph.egg-info/PKG-INFO` & `property-graph-2.0.6/src/property_graph.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: property-graph
-Version: 2.0.5
+Version: 2.0.6
 Summary: python library for working with objects as graphs of property data
 Author-email: Matt Fowler <mattefowler@gmail.com>
 License:                                  Apache License
                                    Version 2.0, January 2004
                                 http://www.apache.org/licenses/
         
            TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION
```

### Comparing `property-graph-2.0.5/src/property_graph.egg-info/SOURCES.txt` & `property-graph-2.0.6/src/property_graph.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/src/pypg/locator.py` & `property-graph-2.0.6/src/pypg/locator.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/src/pypg/property.py` & `property-graph-2.0.6/src/pypg/property.py`

 * *Files 0% similar despite different names*

```diff
@@ -403,18 +403,18 @@
             instance: the instance whose Property value is being set.
             value: the value to be stored for instance.
         """
         instance.__dict__[self.attribute_key] = value
 
     def __get__(self, instance: PropertyClass, owner: PropertyType):
         proxy = self._subclass_proxies[owner]
-        return proxy if instance is None else proxy.get(instance)
+        return proxy if instance is None else proxy.__get__(instance, owner)
 
     def __set__(self, instance, value):
-        self._subclass_proxies[type(instance)].set(instance, value)
+        self._subclass_proxies[type(instance)].__set__(instance, value)
 
     def get(self, instance) -> T:
         """
         Convenience method to use Property get-semantics functionally.
         Args:
             instance: the instance whose data is retrieved.
 
@@ -476,22 +476,22 @@
                 return
             if isinstance(result, Trait):
                 yield result
             else:
                 yield from result
 
     @wraps(Property.get)
-    def get(self, instance):
+    def __get__(self, instance, owner):
         result = self._property._getter(instance)
         for t in self.__post_get:
             result = t.apply(instance, result)
         return result
 
     @wraps(Property.set)
-    def set(self, instance, value):
+    def __set__(self, instance, value):
         for t in self.__pre_set:
             value = t.apply(instance, value)
         self._property._setter(instance, value)
         for t in self.__post_set:
             t.apply(instance, value)
 
     @wraps(Property.__init_instance__)
```

### Comparing `property-graph-2.0.5/src/pypg/property_transcoder.py` & `property-graph-2.0.6/src/pypg/property_transcoder.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/src/pypg/traits/allowed_range.py` & `property-graph-2.0.6/src/pypg/traits/allowed_range.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/src/pypg/traits/config.py` & `property-graph-2.0.6/src/pypg/traits/config.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,7 +1,9 @@
+import json
+
 from pypg import Encoder, encode, MetadataTrait
 from pypg.property import PropertyClass, Property, PropertyType
 from pypg.property_transcoder import PropertyClassEncoder
 
 
 class ConfigEncoder(PropertyClassEncoder):
     def _encode(self, obj: PropertyClass):
@@ -23,7 +25,16 @@
     def has_config_data(cls, p: Property):
         for pt in p.traits:
             if isinstance(pt, Config):
                 return pt.value
         if issubclass(type(p.value_type), PropertyType):
             p_val_type: PropertyType = p.value_type
             return any(filter(cls.has_config_data, p_val_type.properties))
+
+    @classmethod
+    def to_file(cls, obj, path: str):
+        with open(path, 'w') as file:
+            json.dump(cls.encode(obj), file)
+
+    @classmethod
+    def to_string(cls, obj) -> str:
+        return json.dumps(cls.encode(obj))
```

### Comparing `property-graph-2.0.5/src/pypg/traits/obligate.py` & `property-graph-2.0.6/src/pypg/traits/obligate.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/src/pypg/traits/observable.py` & `property-graph-2.0.6/src/pypg/traits/observable.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/src/pypg/traits/overridable.py` & `property-graph-2.0.6/src/pypg/traits/overridable.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/src/pypg/traits/read_only.py` & `property-graph-2.0.6/src/pypg/traits/read_only.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/src/pypg/traits/validated.py` & `property-graph-2.0.6/src/pypg/traits/validated.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/src/pypg/transcode.py` & `property-graph-2.0.6/src/pypg/transcode.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/src/pypg/type_registry.py` & `property-graph-2.0.6/src/pypg/type_registry.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/src/pypg/type_utils.py` & `property-graph-2.0.6/src/pypg/type_utils.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/tests/test_allowed_range.py` & `property-graph-2.0.6/tests/test_allowed_range.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/tests/test_config.py` & `property-graph-2.0.6/tests/test_config.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,11 +1,15 @@
-from unittest import TestCase
+import json
+import os
+import tempfile
+from unittest import TestCase, mock
 
 from pypg import PropertyClass, MethodReference, Property, decode
 from pypg.traits.config import Config
+from pypg.transcode import from_file
 
 
 class InnerCls(PropertyClass):
     p1 = Property[int](default=0, traits=[Config(True)])
 
 
 class CfgDataCls(PropertyClass):
@@ -24,8 +28,22 @@
         cdc.inner.p1 = 1
         encoded = Config.encode(cdc)
         copy = decode(encoded)
         self.assertEqual(1, copy.inner.p1)
         self.assertEqual(1, copy.included)
 
         self.assertEqual(0, copy.excluded)
-        self.assertIsNone(copy.excluded_inner)
+        self.assertIsNone(copy.excluded_inner)
+
+    def test_to_file(self):
+        with tempfile.TemporaryDirectory() as tmpdir:
+            cdc = CfgDataCls(included=1, excluded=1, excluded_inner=InnerCls(p1=1))
+            cdc.inner.p1 = 1
+            fpath = os.path.join(tmpdir,'encoded.json')
+            Config.to_file(cdc, fpath)
+            copy = from_file(fpath)
+            self.assertEqual(cdc.inner.p1, copy.inner.p1)
+
+    def test_to_string(self):
+        cdc = CfgDataCls(included=1, excluded=1, excluded_inner=InnerCls(p1=1))
+        json_str = json.dumps(Config.encode(cdc))
+        self.assertEqual(json_str, Config.to_string(cdc))
```

### Comparing `property-graph-2.0.5/tests/test_locator.py` & `property-graph-2.0.6/tests/test_locator.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/tests/test_obligate.py` & `property-graph-2.0.6/tests/test_obligate.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/tests/test_observable.py` & `property-graph-2.0.6/tests/test_observable.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/tests/test_overridable.py` & `property-graph-2.0.6/tests/test_overridable.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/tests/test_property.py` & `property-graph-2.0.6/tests/test_property.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/tests/test_readonly.py` & `property-graph-2.0.6/tests/test_readonly.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/tests/test_traits.py` & `property-graph-2.0.6/tests/test_traits.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/tests/test_transcoder.py` & `property-graph-2.0.6/tests/test_transcoder.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/tests/test_type_registry.py` & `property-graph-2.0.6/tests/test_type_registry.py`

 * *Files identical despite different names*

### Comparing `property-graph-2.0.5/tests/test_type_schema_encoding.py` & `property-graph-2.0.6/tests/test_type_schema_encoding.py`

 * *Files identical despite different names*


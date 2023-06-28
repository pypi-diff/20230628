# Comparing `tmp/django_classy_settings-3.0.2.tar.gz` & `tmp/django_classy_settings-3.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "django_classy_settings-3.0.2.tar", max compression
+gzip compressed data, was "django_classy_settings-3.0.3.tar", max compression
```

## Comparing `django_classy_settings-3.0.2.tar` & `django_classy_settings-3.0.3.tar`

### file list

```diff
@@ -1,7 +1,7 @@
--rw-r--r--   0        0        0     1297 2015-06-16 05:39:35.220270 django_classy_settings-3.0.2/LICENSE
--rw-r--r--   0        0        0     1016 2022-09-14 22:49:58.676866 django_classy_settings-3.0.2/README.md
--rw-r--r--   0        0        0     5365 2023-03-27 02:16:25.229451 django_classy_settings-3.0.2/cbs/__init__.py
--rw-r--r--   0        0        0     1102 2023-03-09 01:09:41.869659 django_classy_settings-3.0.2/cbs/cast.py
--rw-r--r--   0        0        0     1729 2022-09-08 12:15:04.645999 django_classy_settings-3.0.2/cbs/urls.py
--rw-r--r--   0        0        0     1292 2023-04-19 23:46:11.250970 django_classy_settings-3.0.2/pyproject.toml
--rw-r--r--   0        0        0     2374 1970-01-01 00:00:00.000000 django_classy_settings-3.0.2/PKG-INFO
+-rw-r--r--   0        0        0     1297 2015-06-16 05:39:35.220270 django_classy_settings-3.0.3/LICENSE
+-rw-r--r--   0        0        0     1016 2022-09-14 22:49:58.676866 django_classy_settings-3.0.3/README.md
+-rw-r--r--   0        0        0     5477 2023-06-28 00:18:11.450193 django_classy_settings-3.0.3/cbs/__init__.py
+-rw-r--r--   0        0        0     1102 2023-03-09 01:09:41.869659 django_classy_settings-3.0.3/cbs/cast.py
+-rw-r--r--   0        0        0     1729 2022-09-08 12:15:04.645999 django_classy_settings-3.0.3/cbs/urls.py
+-rw-r--r--   0        0        0     1292 2023-06-28 00:18:26.166221 django_classy_settings-3.0.3/pyproject.toml
+-rw-r--r--   0        0        0     2374 1970-01-01 00:00:00.000000 django_classy_settings-3.0.3/PKG-INFO
```

### Comparing `django_classy_settings-3.0.2/LICENSE` & `django_classy_settings-3.0.3/LICENSE`

 * *Files identical despite different names*

### Comparing `django_classy_settings-3.0.2/README.md` & `django_classy_settings-3.0.3/README.md`

 * *Files identical despite different names*

### Comparing `django_classy_settings-3.0.2/cbs/__init__.py` & `django_classy_settings-3.0.3/cbs/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -23,14 +23,16 @@
     PREFIX = ""
 
     def __new__(cls, *args, **kwargs):
         """
         Catch case when we're used as a decorator with keyword arguments, or
         used to pre-set some defaults.
         """
+        if not args and not kwargs:
+            raise TypeError('env requires positional or keyword arguments')
         if not args:
             return partial(cls, **kwargs)
         return object.__new__(cls)
 
     def __init__(self, getter, key=None, cast=None, prefix=None):
         self.cast = cast
```

### Comparing `django_classy_settings-3.0.2/cbs/cast.py` & `django_classy_settings-3.0.3/cbs/cast.py`

 * *Files identical despite different names*

### Comparing `django_classy_settings-3.0.2/cbs/urls.py` & `django_classy_settings-3.0.3/cbs/urls.py`

 * *Files identical despite different names*

### Comparing `django_classy_settings-3.0.2/pyproject.toml` & `django_classy_settings-3.0.3/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "django-classy-settings"
-version = "3.0.2"
+version = "3.0.3"
 description = "Simple class-based settings for Django"
 license = "BSD-2-Clause"
 authors = ["Curtis Maloney <curtis@tinbrain.net>"]
 readme = "README.md"
 homepage = "https://django-classy-settings.readthedocs.io/en/latest/"
 repository = "https://github.com/funkybob/django-classy-settings"
 documentation = "https://django-classy-settings.readthedocs.io/en/latest/"
```

### Comparing `django_classy_settings-3.0.2/PKG-INFO` & `django_classy_settings-3.0.3/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: django-classy-settings
-Version: 3.0.2
+Version: 3.0.3
 Summary: Simple class-based settings for Django
 Home-page: https://django-classy-settings.readthedocs.io/en/latest/
 License: BSD-2-Clause
 Author: Curtis Maloney
 Author-email: curtis@tinbrain.net
 Requires-Python: >=3.7,<4.0
 Classifier: Development Status :: 5 - Production/Stable
```


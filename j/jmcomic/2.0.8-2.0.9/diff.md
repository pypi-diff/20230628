# Comparing `tmp/jmcomic-2.0.8.tar.gz` & `tmp/jmcomic-2.0.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "jmcomic-2.0.8.tar", last modified: Sun Jun 25 04:33:25 2023, max compression
+gzip compressed data, was "jmcomic-2.0.9.tar", last modified: Wed Jun 28 04:38:58 2023, max compression
```

## Comparing `jmcomic-2.0.8.tar` & `jmcomic-2.0.9.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-25 04:33:25.815193 jmcomic-2.0.8/
--rw-r--r--   0 runner    (1001) docker     (123)     1064 2023-06-25 04:33:15.000000 jmcomic-2.0.8/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     3541 2023-06-25 04:33:25.815193 jmcomic-2.0.8/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2696 2023-06-25 04:33:15.000000 jmcomic-2.0.8/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-25 04:33:25.815193 jmcomic-2.0.8/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1510 2023-06-25 04:33:15.000000 jmcomic-2.0.8/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-25 04:33:25.811193 jmcomic-2.0.8/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-25 04:33:25.815193 jmcomic-2.0.8/src/jmcomic/
--rw-r--r--   0 runner    (1001) docker     (123)      159 2023-06-25 04:33:15.000000 jmcomic-2.0.8/src/jmcomic/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4867 2023-06-25 04:33:15.000000 jmcomic-2.0.8/src/jmcomic/api.py
--rw-r--r--   0 runner    (1001) docker     (123)    11557 2023-06-25 04:33:15.000000 jmcomic-2.0.8/src/jmcomic/jm_client_impl.py
--rw-r--r--   0 runner    (1001) docker     (123)     5739 2023-06-25 04:33:15.000000 jmcomic-2.0.8/src/jmcomic/jm_client_interface.py
--rw-r--r--   0 runner    (1001) docker     (123)     5016 2023-06-25 04:33:15.000000 jmcomic-2.0.8/src/jmcomic/jm_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     9759 2023-06-25 04:33:15.000000 jmcomic-2.0.8/src/jmcomic/jm_entity.py
--rw-r--r--   0 runner    (1001) docker     (123)     9298 2023-06-25 04:33:15.000000 jmcomic-2.0.8/src/jmcomic/jm_option.py
--rw-r--r--   0 runner    (1001) docker     (123)    11370 2023-06-25 04:33:15.000000 jmcomic-2.0.8/src/jmcomic/jm_toolkit.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-25 04:33:25.815193 jmcomic-2.0.8/src/jmcomic.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     3541 2023-06-25 04:33:25.000000 jmcomic-2.0.8/src/jmcomic.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      409 2023-06-25 04:33:25.000000 jmcomic-2.0.8/src/jmcomic.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-25 04:33:25.000000 jmcomic-2.0.8/src/jmcomic.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-25 04:33:25.000000 jmcomic-2.0.8/src/jmcomic.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-25 04:33:25.000000 jmcomic-2.0.8/src/jmcomic.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 04:38:58.578172 jmcomic-2.0.9/
+-rw-r--r--   0 runner    (1001) docker     (123)     1064 2023-06-28 04:38:49.000000 jmcomic-2.0.9/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     3541 2023-06-28 04:38:58.578172 jmcomic-2.0.9/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2696 2023-06-28 04:38:49.000000 jmcomic-2.0.9/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 04:38:58.582172 jmcomic-2.0.9/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1510 2023-06-28 04:38:49.000000 jmcomic-2.0.9/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 04:38:58.578172 jmcomic-2.0.9/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 04:38:58.578172 jmcomic-2.0.9/src/jmcomic/
+-rw-r--r--   0 runner    (1001) docker     (123)      159 2023-06-28 04:38:49.000000 jmcomic-2.0.9/src/jmcomic/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4867 2023-06-28 04:38:49.000000 jmcomic-2.0.9/src/jmcomic/api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11565 2023-06-28 04:38:49.000000 jmcomic-2.0.9/src/jmcomic/jm_client_impl.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5739 2023-06-28 04:38:49.000000 jmcomic-2.0.9/src/jmcomic/jm_client_interface.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5023 2023-06-28 04:38:49.000000 jmcomic-2.0.9/src/jmcomic/jm_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9759 2023-06-28 04:38:49.000000 jmcomic-2.0.9/src/jmcomic/jm_entity.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9298 2023-06-28 04:38:49.000000 jmcomic-2.0.9/src/jmcomic/jm_option.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11289 2023-06-28 04:38:49.000000 jmcomic-2.0.9/src/jmcomic/jm_toolkit.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 04:38:58.578172 jmcomic-2.0.9/src/jmcomic.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     3541 2023-06-28 04:38:58.000000 jmcomic-2.0.9/src/jmcomic.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      409 2023-06-28 04:38:58.000000 jmcomic-2.0.9/src/jmcomic.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 04:38:58.000000 jmcomic-2.0.9/src/jmcomic.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 04:38:58.000000 jmcomic-2.0.9/src/jmcomic.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-28 04:38:58.000000 jmcomic-2.0.9/src/jmcomic.egg-info/top_level.txt
```

### Comparing `jmcomic-2.0.8/LICENSE` & `jmcomic-2.0.9/LICENSE`

 * *Files identical despite different names*

### Comparing `jmcomic-2.0.8/PKG-INFO` & `jmcomic-2.0.9/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jmcomic
-Version: 2.0.8
+Version: 2.0.9
 Summary: Python API For JMComic (禁漫天堂)
 Home-page: https://github.com/hect0x7/JMComic-Crawler-Python
 Author: hect0x7
 Author-email: 93357912+hect0x7@users.noreply.github.com
 Keywords: python,jmcomic,18comic,禁漫天堂,NSFW
 Classifier: Development Status :: 4 - Beta
 Classifier: Intended Audience :: Developers
```

### Comparing `jmcomic-2.0.8/README.md` & `jmcomic-2.0.9/README.md`

 * *Files identical despite different names*

### Comparing `jmcomic-2.0.8/setup.py` & `jmcomic-2.0.9/setup.py`

 * *Files identical despite different names*

### Comparing `jmcomic-2.0.8/src/jmcomic/api.py` & `jmcomic-2.0.9/src/jmcomic/api.py`

 * *Files identical despite different names*

### Comparing `jmcomic-2.0.8/src/jmcomic/jm_client_impl.py` & `jmcomic-2.0.9/src/jmcomic/jm_client_impl.py`

 * *Files 0% similar despite different names*

```diff
@@ -73,14 +73,17 @@
     def before_retry(self, e, kwargs, retry_count, url):
         jm_debug('error', str(e))
 
     def enable_cache(self, debug=False):
         def wrap_func_cache(func_name, cache_dict_name):
             import common
             if common.VERSION > '0.4.8':
+                if hasattr(self, cache_dict_name):
+                    return
+
                 cache = common.cache
                 cache_dict = {}
                 cache_hit_msg = (f'【缓存命中】{cache_dict_name} ' + '→ [{}]') if debug is True else None
                 cache_miss_msg = (f'【缓存缺失】{cache_dict_name} ' + '← [{}]') if debug is True else None
                 cache = cache(
                     cache_dict=cache_dict,
                     cache_hit_msg=cache_hit_msg,
@@ -91,17 +94,14 @@
                 if sys.version_info < (3, 9):
                     raise NotImplementedError('不支持启用JmcomicClient缓存。\n'
                                               '请更新python版本到3.9以上，'
                                               '或更新commonX: `pip install commonX --upgrade`')
                 import functools
                 cache = functools.cache
 
-            if hasattr(self, cache_dict_name):
-                return
-
             # 重载本对象的方法
             func = getattr(self, func_name)
             wrap_func = cache(func)
 
             setattr(self, func_name, wrap_func)
 
         for func in {
```

### Comparing `jmcomic-2.0.8/src/jmcomic/jm_client_interface.py` & `jmcomic-2.0.9/src/jmcomic/jm_client_interface.py`

 * *Files identical despite different names*

### Comparing `jmcomic-2.0.8/src/jmcomic/jm_config.py` & `jmcomic-2.0.9/src/jmcomic/jm_config.py`

 * *Files 0% similar despite different names*

```diff
@@ -2,17 +2,14 @@
     from common import format_ts
     print(f'{format_ts()}:【{topic}】{msg}')
 
 
 def default_postman_constructor(session, **kwargs):
     from common import Postmans
 
-    kwargs.setdefault('impersonate', 'chrome110')
-    kwargs.setdefault('headers', JmModuleConfig.headers())
-
     if session is True:
         return Postmans.new_session(**kwargs)
 
     return Postmans.new_postman(**kwargs)
 
 
 class JmModuleConfig:
@@ -97,14 +94,16 @@
 
     @classmethod
     def disable_jm_debug(cls):
         cls.enable_jm_debug = False
 
     @classmethod
     def new_postman(cls, session=False, **kwargs):
+        kwargs.setdefault('impersonate', 'chrome110')
+        kwargs.setdefault('headers', JmModuleConfig.headers())
         return cls.postman_constructor(session, **kwargs)
 
     @classmethod
     def get_jmcomic_url(cls, postman=None):
         """
         访问禁漫的永久网域，从而得到一个可用的禁漫网址
         @return: https://jm-comic2.cc
```

### Comparing `jmcomic-2.0.8/src/jmcomic/jm_entity.py` & `jmcomic-2.0.9/src/jmcomic/jm_entity.py`

 * *Files identical despite different names*

### Comparing `jmcomic-2.0.8/src/jmcomic/jm_option.py` & `jmcomic-2.0.9/src/jmcomic/jm_option.py`

 * *Files identical despite different names*

### Comparing `jmcomic-2.0.8/src/jmcomic/jm_toolkit.py` & `jmcomic-2.0.9/src/jmcomic/jm_toolkit.py`

 * *Files 1% similar despite different names*

```diff
@@ -61,19 +61,14 @@
 
         # text: JM12341
         c0 = text[0]
         c1 = text[1]
         if (c0 == 'J' or c0 == 'j') and (c1 == 'M' or c1 == 'm'):
             # JM123456
             return text[2:]
-
-        elif text.isdigit():
-            # 123456
-            return str(text)
-
         else:
             # https://xxx/photo/412038
             match = cls.pattern_jm_pa_id.search(text)
             if match is None:
                 raise AssertionError(f"无法解析jm车号, 文本为: {text}")
             return match[2]
```

### Comparing `jmcomic-2.0.8/src/jmcomic.egg-info/PKG-INFO` & `jmcomic-2.0.9/src/jmcomic.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jmcomic
-Version: 2.0.8
+Version: 2.0.9
 Summary: Python API For JMComic (禁漫天堂)
 Home-page: https://github.com/hect0x7/JMComic-Crawler-Python
 Author: hect0x7
 Author-email: 93357912+hect0x7@users.noreply.github.com
 Keywords: python,jmcomic,18comic,禁漫天堂,NSFW
 Classifier: Development Status :: 4 - Beta
 Classifier: Intended Audience :: Developers
```


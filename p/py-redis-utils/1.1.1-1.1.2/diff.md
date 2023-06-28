# Comparing `tmp/py-redis-utils-1.1.1.tar.gz` & `tmp/py-redis-utils-1.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "py-redis-utils-1.1.1.tar", last modified: Wed May 17 10:57:17 2023, max compression
+gzip compressed data, was "py-redis-utils-1.1.2.tar", last modified: Wed Jun 28 11:48:05 2023, max compression
```

## Comparing `py-redis-utils-1.1.1.tar` & `py-redis-utils-1.1.2.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxr-xr-x   0 vgurin    (1000) vgurin    (1000)        0 2023-05-17 10:57:17.800864 py-redis-utils-1.1.1/
--rw-r--r--   0 vgurin    (1000) vgurin    (1000)      416 2023-05-17 10:57:17.800864 py-redis-utils-1.1.1/PKG-INFO
--rwxrwxrwx   0 vgurin    (1000) vgurin    (1000)     1361 2023-04-11 16:05:30.000000 py-redis-utils-1.1.1/README.md
-drwxr-xr-x   0 vgurin    (1000) vgurin    (1000)        0 2023-05-17 10:57:17.800864 py-redis-utils-1.1.1/py_redis_utils.egg-info/
--rw-r--r--   0 vgurin    (1000) vgurin    (1000)      416 2023-05-17 10:57:17.000000 py-redis-utils-1.1.1/py_redis_utils.egg-info/PKG-INFO
--rw-r--r--   0 vgurin    (1000) vgurin    (1000)      286 2023-05-17 10:57:17.000000 py-redis-utils-1.1.1/py_redis_utils.egg-info/SOURCES.txt
--rw-r--r--   0 vgurin    (1000) vgurin    (1000)        1 2023-05-17 10:57:17.000000 py-redis-utils-1.1.1/py_redis_utils.egg-info/dependency_links.txt
--rw-r--r--   0 vgurin    (1000) vgurin    (1000)       63 2023-05-17 10:57:17.000000 py-redis-utils-1.1.1/py_redis_utils.egg-info/requires.txt
--rw-r--r--   0 vgurin    (1000) vgurin    (1000)       13 2023-05-17 10:57:17.000000 py-redis-utils-1.1.1/py_redis_utils.egg-info/top_level.txt
-drwxr-xr-x   0 vgurin    (1000) vgurin    (1000)        0 2023-05-17 10:57:17.800864 py-redis-utils-1.1.1/pyredisutils/
--rw-r--r--   0 vgurin    (1000) vgurin    (1000)       65 2023-05-17 09:03:25.000000 py-redis-utils-1.1.1/pyredisutils/__init__.py
--rw-r--r--   0 vgurin    (1000) vgurin    (1000)     8535 2023-05-17 10:56:48.000000 py-redis-utils-1.1.1/pyredisutils/_decorators.py
--rw-r--r--   0 vgurin    (1000) vgurin    (1000)    14363 2023-05-17 10:56:48.000000 py-redis-utils-1.1.1/pyredisutils/_settings.py
--rw-r--r--   0 vgurin    (1000) vgurin    (1000)       38 2023-05-17 10:57:17.800864 py-redis-utils-1.1.1/setup.cfg
--rw-r--r--   0 vgurin    (1000) vgurin    (1000)      786 2023-05-17 10:57:15.000000 py-redis-utils-1.1.1/setup.py
+drwxr-xr-x   0 erne      (1000) erne      (1000)        0 2023-06-28 11:48:05.065652 py-redis-utils-1.1.2/
+-rw-r--r--   0 erne      (1000) erne      (1000)      480 2023-06-28 11:48:05.065652 py-redis-utils-1.1.2/PKG-INFO
+-rwxrwxrwx   0 erne      (1000) erne      (1000)     1361 2023-02-03 14:24:27.000000 py-redis-utils-1.1.2/README.md
+drwxr-xr-x   0 erne      (1000) erne      (1000)        0 2023-06-28 11:48:05.065652 py-redis-utils-1.1.2/py_redis_utils.egg-info/
+-rw-r--r--   0 erne      (1000) erne      (1000)      480 2023-06-28 11:48:04.000000 py-redis-utils-1.1.2/py_redis_utils.egg-info/PKG-INFO
+-rw-r--r--   0 erne      (1000) erne      (1000)      286 2023-06-28 11:48:04.000000 py-redis-utils-1.1.2/py_redis_utils.egg-info/SOURCES.txt
+-rw-r--r--   0 erne      (1000) erne      (1000)        1 2023-06-28 11:48:04.000000 py-redis-utils-1.1.2/py_redis_utils.egg-info/dependency_links.txt
+-rw-r--r--   0 erne      (1000) erne      (1000)       63 2023-06-28 11:48:04.000000 py-redis-utils-1.1.2/py_redis_utils.egg-info/requires.txt
+-rw-r--r--   0 erne      (1000) erne      (1000)       13 2023-06-28 11:48:04.000000 py-redis-utils-1.1.2/py_redis_utils.egg-info/top_level.txt
+drwxr-xr-x   0 erne      (1000) erne      (1000)        0 2023-06-28 11:48:05.065652 py-redis-utils-1.1.2/pyredisutils/
+-rw-r--r--   0 erne      (1000) erne      (1000)       65 2023-06-28 11:32:15.000000 py-redis-utils-1.1.2/pyredisutils/__init__.py
+-rw-r--r--   0 erne      (1000) erne      (1000)     8535 2023-06-28 11:32:15.000000 py-redis-utils-1.1.2/pyredisutils/_decorators.py
+-rw-r--r--   0 erne      (1000) erne      (1000)    14393 2023-06-28 11:46:46.000000 py-redis-utils-1.1.2/pyredisutils/_settings.py
+-rw-r--r--   0 erne      (1000) erne      (1000)       38 2023-06-28 11:48:05.065652 py-redis-utils-1.1.2/setup.cfg
+-rw-r--r--   0 erne      (1000) erne      (1000)      786 2023-06-28 11:47:23.000000 py-redis-utils-1.1.2/setup.py
```

### Comparing `py-redis-utils-1.1.1/README.md` & `py-redis-utils-1.1.2/README.md`

 * *Files identical despite different names*

### Comparing `py-redis-utils-1.1.1/pyredisutils/_decorators.py` & `py-redis-utils-1.1.2/pyredisutils/_decorators.py`

 * *Files identical despite different names*

### Comparing `py-redis-utils-1.1.1/pyredisutils/_settings.py` & `py-redis-utils-1.1.2/pyredisutils/_settings.py`

 * *Files 1% similar despite different names*

```diff
@@ -364,19 +364,20 @@
                     }
                     diff = deepdiff.DeepDiff(self.response_template, redis_response)
                     if diff == {}:
                         pubsub.unsubscribe(f"{self.channel_name}.reply")
                         redis_client.close()
                         return True
                     values = diff.get("values_changed", {})
-                    for change in values.values():
-                        if change["old_value"] == self.request_id:
-                            continue
-                    redis_client.close()
-                    return False
+                    if all(
+                            change["old_value"] != self.request_id
+                            for change in values.values()
+                    ):
+                        redis_client.close()
+                        return False
             except TimeoutError:
                 logging.error("Haven't received any answer from Redis for 5 seconds.")
                 redis_client.close()
                 return self.make_response("Gateway Timeout", 504)
         except redis.exceptions.ConnectionError:
             return self.make_response("Bad Gateway", 502)
```

### Comparing `py-redis-utils-1.1.1/setup.py` & `py-redis-utils-1.1.2/setup.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from setuptools import setup, find_packages
 
-VERSION = "1.1.1"
+VERSION = "1.1.2"
 DESCRIPTION = "Utilities with Redis"
 
 # Setting up
 setup(
     name="py-redis-utils",
     version=VERSION,
     author="KE",
```


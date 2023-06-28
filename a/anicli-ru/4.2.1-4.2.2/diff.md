# Comparing `tmp/anicli-ru-4.2.1.tar.gz` & `tmp/anicli-ru-4.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "anicli-ru-4.2.1.tar", last modified: Thu Mar 30 19:16:01 2023, max compression
+gzip compressed data, was "anicli-ru-4.2.2.tar", last modified: Wed Jun 28 14:44:09 2023, max compression
```

## Comparing `anicli-ru-4.2.1.tar` & `anicli-ru-4.2.2.tar`

### file list

```diff
@@ -1,35 +1,35 @@
-drwxr-xr-x   0 georgiy   (1000) georgiy   (1000)        0 2023-03-30 19:16:01.532459 anicli-ru-4.2.1/
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)    35148 2021-11-01 12:04:16.000000 anicli-ru-4.2.1/LICENSE
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     4308 2023-03-30 19:16:01.532459 anicli-ru-4.2.1/PKG-INFO
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     3992 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/README.md
-drwxr-xr-x   0 georgiy   (1000) georgiy   (1000)        0 2023-03-30 19:16:01.526459 anicli-ru-4.2.1/anicli_ru/
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)       72 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/__init__.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)       93 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/__main__.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)       52 2023-03-30 19:12:07.000000 anicli-ru-4.2.1/anicli_ru/__version__.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     1117 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/_http.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     4051 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/aniboom.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)    10050 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/anicli.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)    12327 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/base.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     2988 2023-03-30 19:09:16.000000 anicli-ru-4.2.1/anicli_ru/defaults.py
-drwxr-xr-x   0 georgiy   (1000) georgiy   (1000)        0 2023-03-30 19:16:01.531459 anicli-ru-4.2.1/anicli_ru/extractors/
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)        0 2023-03-29 06:40:33.000000 anicli-ru-4.2.1/anicli_ru/extractors/__init__.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     2090 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/extractors/__template__.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     4437 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/extractors/anilibria.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     4638 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/extractors/animania.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     5598 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/extractors/animego.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     4518 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/extractors/animevost.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     6860 2023-03-30 19:09:50.000000 anicli-ru-4.2.1/anicli_ru/kodik.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     2089 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/loader.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     6405 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/options.py
-drwxr-xr-x   0 georgiy   (1000) georgiy   (1000)        0 2023-03-30 19:16:01.531459 anicli-ru-4.2.1/anicli_ru/utils/
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)       47 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/utils/__init__.py
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     2371 2023-03-29 06:40:38.000000 anicli-ru-4.2.1/anicli_ru/utils/random_agent.py
-drwxr-xr-x   0 georgiy   (1000) georgiy   (1000)        0 2023-03-30 19:16:01.528459 anicli-ru-4.2.1/anicli_ru.egg-info/
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)     4308 2023-03-30 19:16:01.000000 anicli-ru-4.2.1/anicli_ru.egg-info/PKG-INFO
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)      728 2023-03-30 19:16:01.000000 anicli-ru-4.2.1/anicli_ru.egg-info/SOURCES.txt
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)        1 2023-03-30 19:16:01.000000 anicli-ru-4.2.1/anicli_ru.egg-info/dependency_links.txt
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)       53 2023-03-30 19:16:01.000000 anicli-ru-4.2.1/anicli_ru.egg-info/entry_points.txt
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)        9 2023-03-30 19:16:01.000000 anicli-ru-4.2.1/anicli_ru.egg-info/requires.txt
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)       10 2023-03-30 19:16:01.000000 anicli-ru-4.2.1/anicli_ru.egg-info/top_level.txt
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)      428 2023-03-30 19:16:01.532459 anicli-ru-4.2.1/setup.cfg
--rw-r--r--   0 georgiy   (1000) georgiy   (1000)      687 2023-03-30 19:11:50.000000 anicli-ru-4.2.1/setup.py
+drwxr-xr-x   0 georgiy   (1000) georgiy   (1000)        0 2023-06-28 14:44:09.627041 anicli-ru-4.2.2/
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)    35148 2021-11-01 12:04:16.000000 anicli-ru-4.2.2/LICENSE
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     4288 2023-06-28 14:44:09.628041 anicli-ru-4.2.2/PKG-INFO
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     3992 2023-03-29 06:40:38.000000 anicli-ru-4.2.2/README.md
+drwxr-xr-x   0 georgiy   (1000) georgiy   (1000)        0 2023-06-28 14:44:09.622041 anicli-ru-4.2.2/anicli_ru/
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)       72 2023-03-29 06:40:38.000000 anicli-ru-4.2.2/anicli_ru/__init__.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)       93 2023-03-29 06:40:38.000000 anicli-ru-4.2.2/anicli_ru/__main__.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)       52 2023-06-28 14:43:34.000000 anicli-ru-4.2.2/anicli_ru/__version__.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     1117 2023-03-29 06:40:38.000000 anicli-ru-4.2.2/anicli_ru/_http.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     4051 2023-03-29 06:40:38.000000 anicli-ru-4.2.2/anicli_ru/aniboom.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)    10050 2023-03-29 06:40:38.000000 anicli-ru-4.2.2/anicli_ru/anicli.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)    12327 2023-06-28 14:41:08.000000 anicli-ru-4.2.2/anicli_ru/base.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     2988 2023-03-30 19:09:16.000000 anicli-ru-4.2.2/anicli_ru/defaults.py
+drwxr-xr-x   0 georgiy   (1000) georgiy   (1000)        0 2023-06-28 14:44:09.627041 anicli-ru-4.2.2/anicli_ru/extractors/
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)        0 2023-03-29 06:40:33.000000 anicli-ru-4.2.2/anicli_ru/extractors/__init__.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     2090 2023-03-29 06:40:38.000000 anicli-ru-4.2.2/anicli_ru/extractors/__template__.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     4437 2023-03-29 06:40:38.000000 anicli-ru-4.2.2/anicli_ru/extractors/anilibria.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     4638 2023-03-29 06:40:38.000000 anicli-ru-4.2.2/anicli_ru/extractors/animania.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     5598 2023-06-28 14:41:00.000000 anicli-ru-4.2.2/anicli_ru/extractors/animego.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     4518 2023-03-29 06:40:38.000000 anicli-ru-4.2.2/anicli_ru/extractors/animevost.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     6970 2023-06-28 14:40:22.000000 anicli-ru-4.2.2/anicli_ru/kodik.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     2089 2023-03-29 06:40:38.000000 anicli-ru-4.2.2/anicli_ru/loader.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     6405 2023-03-29 06:40:38.000000 anicli-ru-4.2.2/anicli_ru/options.py
+drwxr-xr-x   0 georgiy   (1000) georgiy   (1000)        0 2023-06-28 14:44:09.627041 anicli-ru-4.2.2/anicli_ru/utils/
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)       47 2023-03-29 06:40:38.000000 anicli-ru-4.2.2/anicli_ru/utils/__init__.py
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     2371 2023-03-29 06:40:38.000000 anicli-ru-4.2.2/anicli_ru/utils/random_agent.py
+drwxr-xr-x   0 georgiy   (1000) georgiy   (1000)        0 2023-06-28 14:44:09.623041 anicli-ru-4.2.2/anicli_ru.egg-info/
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)     4288 2023-06-28 14:44:09.000000 anicli-ru-4.2.2/anicli_ru.egg-info/PKG-INFO
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)      728 2023-06-28 14:44:09.000000 anicli-ru-4.2.2/anicli_ru.egg-info/SOURCES.txt
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)        1 2023-06-28 14:44:09.000000 anicli-ru-4.2.2/anicli_ru.egg-info/dependency_links.txt
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)       52 2023-06-28 14:44:09.000000 anicli-ru-4.2.2/anicli_ru.egg-info/entry_points.txt
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)        9 2023-06-28 14:44:09.000000 anicli-ru-4.2.2/anicli_ru.egg-info/requires.txt
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)       10 2023-06-28 14:44:09.000000 anicli-ru-4.2.2/anicli_ru.egg-info/top_level.txt
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)      428 2023-06-28 14:44:09.628041 anicli-ru-4.2.2/setup.cfg
+-rw-r--r--   0 georgiy   (1000) georgiy   (1000)      687 2023-03-30 19:11:50.000000 anicli-ru-4.2.2/setup.py
```

### Comparing `anicli-ru-4.2.1/LICENSE` & `anicli-ru-4.2.2/LICENSE`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/PKG-INFO` & `anicli-ru-4.2.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,16 +1,15 @@
 Metadata-Version: 2.1
 Name: anicli-ru
-Version: 4.2.1
+Version: 4.2.2
 Summary: anime grabber video api and cli tool
 Home-page: https://github.com/vypivshiy/ani-cli-ru
 Author: Georgiy aka Vypivshiy
 Author-email: 
 License: GPL-3
-Platform: UNKNOWN
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # anicli-ru
 [![CI](https://github.com/vypivshiy/ani-cli-ru/actions/workflows/ci.yml/badge.svg)](https://github.com/vypivshiy/ani-cli-ru/actions/workflows/ci.yml)
 ___
@@ -101,9 +100,7 @@
 
 [DEV GUIDE](DEV.md)
 # TODO
 * ~~dev guide~~
 * ~~CI/CD github actions: add autotest utils (without test parser), pylance, etc~~
 * ~~mypy fix typing~~
 
-
-
```

### Comparing `anicli-ru-4.2.1/README.md` & `anicli-ru-4.2.2/README.md`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/anicli_ru/_http.py` & `anicli-ru-4.2.2/anicli_ru/_http.py`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/anicli_ru/aniboom.py` & `anicli-ru-4.2.2/anicli_ru/aniboom.py`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/anicli_ru/anicli.py` & `anicli-ru-4.2.2/anicli_ru/anicli.py`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/anicli_ru/base.py` & `anicli-ru-4.2.2/anicli_ru/base.py`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/anicli_ru/defaults.py` & `anicli-ru-4.2.2/anicli_ru/defaults.py`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/anicli_ru/extractors/__template__.py` & `anicli-ru-4.2.2/anicli_ru/extractors/__template__.py`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/anicli_ru/extractors/anilibria.py` & `anicli-ru-4.2.2/anicli_ru/extractors/anilibria.py`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/anicli_ru/extractors/animania.py` & `anicli-ru-4.2.2/anicli_ru/extractors/animania.py`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/anicli_ru/extractors/animego.py` & `anicli-ru-4.2.2/anicli_ru/extractors/animego.py`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/anicli_ru/extractors/animevost.py` & `anicli-ru-4.2.2/anicli_ru/extractors/animevost.py`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/anicli_ru/kodik.py` & `anicli-ru-4.2.2/anicli_ru/kodik.py`

 * *Files 3% similar despite different names*

```diff
@@ -63,15 +63,18 @@
         def char_wrapper(e):
             return chr((ord(e.group(0)) + 13 - (65 if e.group(0) <= "Z" else 97))
                        % 26 + (65 if e.group(0) <= "Z" else 97))
 
         base64_url = re.sub(r"[a-zA-Z]", char_wrapper, url_encoded)
         if not base64_url.endswith("=="):
             base64_url += "=="
-        return f"https:{b64decode(base64_url).decode()}"
+        decoded_url = b64decode(base64_url).decode()
+        if decoded_url.startswith("https:"):
+            return decoded_url
+        return f"https:{decoded_url}"
 
     @staticmethod
     def is_kodik(url: str) -> bool:
         """return True if url player is kodik"""
         return bool(Kodik.KODIK_URL_VALIDATE.search(url))
 
     @classmethod
```

### Comparing `anicli-ru-4.2.1/anicli_ru/loader.py` & `anicli-ru-4.2.2/anicli_ru/loader.py`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/anicli_ru/options.py` & `anicli-ru-4.2.2/anicli_ru/options.py`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/anicli_ru/utils/random_agent.py` & `anicli-ru-4.2.2/anicli_ru/utils/random_agent.py`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/anicli_ru.egg-info/PKG-INFO` & `anicli-ru-4.2.2/anicli_ru.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,16 +1,15 @@
 Metadata-Version: 2.1
 Name: anicli-ru
-Version: 4.2.1
+Version: 4.2.2
 Summary: anime grabber video api and cli tool
 Home-page: https://github.com/vypivshiy/ani-cli-ru
 Author: Georgiy aka Vypivshiy
 Author-email: 
 License: GPL-3
-Platform: UNKNOWN
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # anicli-ru
 [![CI](https://github.com/vypivshiy/ani-cli-ru/actions/workflows/ci.yml/badge.svg)](https://github.com/vypivshiy/ani-cli-ru/actions/workflows/ci.yml)
 ___
@@ -101,9 +100,7 @@
 
 [DEV GUIDE](DEV.md)
 # TODO
 * ~~dev guide~~
 * ~~CI/CD github actions: add autotest utils (without test parser), pylance, etc~~
 * ~~mypy fix typing~~
 
-
-
```

### Comparing `anicli-ru-4.2.1/anicli_ru.egg-info/SOURCES.txt` & `anicli-ru-4.2.2/anicli_ru.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `anicli-ru-4.2.1/setup.py` & `anicli-ru-4.2.2/setup.py`

 * *Files identical despite different names*


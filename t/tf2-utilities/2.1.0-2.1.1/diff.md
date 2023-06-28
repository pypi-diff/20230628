# Comparing `tmp/tf2-utilities-2.1.0.tar.gz` & `tmp/tf2-utilities-2.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tf2-utilities-2.1.0.tar", last modified: Sat Jun 17 07:26:40 2023, max compression
+gzip compressed data, was "tf2-utilities-2.1.1.tar", last modified: Wed Jun 28 08:04:15 2023, max compression
```

## Comparing `tf2-utilities-2.1.0.tar` & `tf2-utilities-2.1.1.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxr-xr-x   0 dixonlokeshengheng   (501) staff       (20)        0 2023-06-17 07:26:40.903499 tf2-utilities-2.1.0/
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)     1069 2022-05-19 15:29:26.000000 tf2-utilities-2.1.0/LICENSE
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)     2218 2023-06-17 07:26:40.903345 tf2-utilities-2.1.0/PKG-INFO
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)     1586 2022-08-05 09:37:00.000000 tf2-utilities-2.1.0/README.md
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)       38 2023-06-17 07:26:40.903554 tf2-utilities-2.1.0/setup.cfg
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)     1041 2023-06-17 07:21:25.000000 tf2-utilities-2.1.0/setup.py
-drwxr-xr-x   0 dixonlokeshengheng   (501) staff       (20)        0 2023-06-17 07:26:40.902396 tf2-utilities-2.1.0/tf2_utilities.egg-info/
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)     2218 2023-06-17 07:26:40.000000 tf2-utilities-2.1.0/tf2_utilities.egg-info/PKG-INFO
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)      322 2023-06-17 07:26:40.000000 tf2-utilities-2.1.0/tf2_utilities.egg-info/SOURCES.txt
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)        1 2023-06-17 07:26:40.000000 tf2-utilities-2.1.0/tf2_utilities.egg-info/dependency_links.txt
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)       13 2023-06-17 07:26:40.000000 tf2-utilities-2.1.0/tf2_utilities.egg-info/requires.txt
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)       13 2023-06-17 07:26:40.000000 tf2-utilities-2.1.0/tf2_utilities.egg-info/top_level.txt
-drwxr-xr-x   0 dixonlokeshengheng   (501) staff       (20)        0 2023-06-17 07:26:40.903128 tf2-utilities-2.1.0/tf2utilities/
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)        0 2022-05-19 07:01:37.000000 tf2-utilities-2.1.0/tf2utilities/__init__.py
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)     3279 2022-08-05 06:49:07.000000 tf2-utilities-2.1.0/tf2utilities/main.py
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)    54078 2023-06-17 07:02:24.000000 tf2-utilities-2.1.0/tf2utilities/schema.py
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)     7398 2022-06-28 08:39:47.000000 tf2-utilities-2.1.0/tf2utilities/sku.py
--rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)      563 2022-05-18 13:06:58.000000 tf2-utilities-2.1.0/tf2utilities/webapi.py
+drwxr-xr-x   0 dixonlokeshengheng   (501) staff       (20)        0 2023-06-28 08:04:15.275847 tf2-utilities-2.1.1/
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)     1069 2022-05-19 15:29:26.000000 tf2-utilities-2.1.1/LICENSE
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)     2218 2023-06-28 08:04:15.275714 tf2-utilities-2.1.1/PKG-INFO
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)     1586 2022-08-05 09:37:00.000000 tf2-utilities-2.1.1/README.md
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)       38 2023-06-28 08:04:15.275905 tf2-utilities-2.1.1/setup.cfg
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)     1041 2023-06-28 07:59:59.000000 tf2-utilities-2.1.1/setup.py
+drwxr-xr-x   0 dixonlokeshengheng   (501) staff       (20)        0 2023-06-28 08:04:15.274791 tf2-utilities-2.1.1/tf2_utilities.egg-info/
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)     2218 2023-06-28 08:04:15.000000 tf2-utilities-2.1.1/tf2_utilities.egg-info/PKG-INFO
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)      322 2023-06-28 08:04:15.000000 tf2-utilities-2.1.1/tf2_utilities.egg-info/SOURCES.txt
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)        1 2023-06-28 08:04:15.000000 tf2-utilities-2.1.1/tf2_utilities.egg-info/dependency_links.txt
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)       13 2023-06-28 08:04:15.000000 tf2-utilities-2.1.1/tf2_utilities.egg-info/requires.txt
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)       13 2023-06-28 08:04:15.000000 tf2-utilities-2.1.1/tf2_utilities.egg-info/top_level.txt
+drwxr-xr-x   0 dixonlokeshengheng   (501) staff       (20)        0 2023-06-28 08:04:15.275511 tf2-utilities-2.1.1/tf2utilities/
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)        0 2022-05-19 07:01:37.000000 tf2-utilities-2.1.1/tf2utilities/__init__.py
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)     3279 2022-08-05 06:49:07.000000 tf2-utilities-2.1.1/tf2utilities/main.py
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)    54437 2023-06-28 07:58:02.000000 tf2-utilities-2.1.1/tf2utilities/schema.py
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)     7398 2022-06-28 08:39:47.000000 tf2-utilities-2.1.1/tf2utilities/sku.py
+-rw-r--r--   0 dixonlokeshengheng   (501) staff       (20)      563 2022-05-18 13:06:58.000000 tf2-utilities-2.1.1/tf2utilities/webapi.py
```

### Comparing `tf2-utilities-2.1.0/LICENSE` & `tf2-utilities-2.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `tf2-utilities-2.1.0/PKG-INFO` & `tf2-utilities-2.1.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tf2-utilities
-Version: 2.1.0
+Version: 2.1.1
 Summary: Get information about TF2 items, effects, skins and more
 Home-page: https://github.com/j0hnnyblack/python-tf2-utilities
 Author: Johnny Black
 Author-email: lokedixon@hotmail.my
 License: MIT
 Keywords: tf2,teamfortress2,steam,trade,trading
 Platform: UNKNOWN
```

### Comparing `tf2-utilities-2.1.0/README.md` & `tf2-utilities-2.1.1/README.md`

 * *Files identical despite different names*

### Comparing `tf2-utilities-2.1.0/setup.py` & `tf2-utilities-2.1.1/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -6,15 +6,15 @@
 HERE = path.abspath(path.dirname(__file__))
 
 with open(path.join(HERE, 'README.md'), encoding='utf-8') as f:
     long_description = f.read()
 
 setup(
     name="tf2-utilities",
-    version="2.1.0",
+    version="2.1.1",
     description="Get information about TF2 items, effects, skins and more",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/j0hnnyblack/python-tf2-utilities",
     author="Johnny Black",
     author_email="lokedixon@hotmail.my",
     license="MIT",
```

### Comparing `tf2-utilities-2.1.0/tf2_utilities.egg-info/PKG-INFO` & `tf2-utilities-2.1.1/tf2_utilities.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tf2-utilities
-Version: 2.1.0
+Version: 2.1.1
 Summary: Get information about TF2 items, effects, skins and more
 Home-page: https://github.com/j0hnnyblack/python-tf2-utilities
 Author: Johnny Black
 Author-email: lokedixon@hotmail.my
 License: MIT
 Keywords: tf2,teamfortress2,steam,trade,trading
 Platform: UNKNOWN
```

### Comparing `tf2-utilities-2.1.0/tf2utilities/main.py` & `tf2-utilities-2.1.1/tf2utilities/main.py`

 * *Files identical despite different names*

### Comparing `tf2-utilities-2.1.0/tf2utilities/schema.py` & `tf2-utilities-2.1.1/tf2utilities/schema.py`

 * *Files 1% similar despite different names*

```diff
@@ -409,16 +409,15 @@
             'haunted phantasm',
             'haunted metal scrap',
             'haunted hat',
             'unusual cap',
             'vintage tyrolean',
             'vintage merryweather',
             'haunted kraken',
-            'haunted forever!',
-            'frostbite bonnet'
+            'haunted forever!'
         ]
 
         qualitySearch = name
         for ex in exception:
             if ex in name: 
                 qualitySearch = name.replace(ex, "").strip()
                 break
@@ -467,14 +466,18 @@
                 continue
             if effect == "accursed" and "accursed apparition" in name:
                 # Accursed Apparition never be an unusual
                 continue
             if effect == "haunted" and "haunted kraken" in name:
                 # Skip Haunted effect if name include Haunted Kraken
                 continue
+            if effect == "frostbite" and "frostbite bonnet" in name:
+                # Skip Frostbite effect if name include Faunted Braken
+                continue
+
             if effect == "hot": 
                 # shotgun # shot to hell
                 # plaid potshotter # shot in the dark
                 if not item.get("wear"):
                     continue
                 elif "hot " not in name and ("shotgun" in name or "shot " in name or "plaid potshotter" in name):
                     # Shotgun
@@ -643,14 +646,20 @@
         else:
             name = name.replace(" series ", "").replace(" series#", " #")
             if "salvaged mann co. supply crate #" in name:
                 item["crateseries"] = int(name[32:])
                 item["defindex"] = 5068
                 item["quality"] = 6
                 return item
+            
+            elif "select reserve mann co. supply crate #" in name:
+                item["defindex"] = 5660
+                item["crateseries"] = 60
+                item["quality"] = 6
+                return item
 
             elif "mann co. supply crate #" in name:
                 crateseries = int(name[23:])
                 if crateseries in {1, 3, 7, 12, 13, 18, 19, 23, 26, 31, 34, 39, 43, 47, 54, 57, 75}:
                     item["defindex"] = 5022
                 elif crateseries in {2, 4, 8, 11, 14, 17, 20, 24, 27, 32, 37, 42, 44, 49, 56, 71, 76}:
                     item["defindex"] = 5041
```

### Comparing `tf2-utilities-2.1.0/tf2utilities/sku.py` & `tf2-utilities-2.1.1/tf2utilities/sku.py`

 * *Files identical despite different names*

### Comparing `tf2-utilities-2.1.0/tf2utilities/webapi.py` & `tf2-utilities-2.1.1/tf2utilities/webapi.py`

 * *Files identical despite different names*


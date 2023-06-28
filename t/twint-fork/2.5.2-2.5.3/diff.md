# Comparing `tmp/twint_fork-2.5.2.tar.gz` & `tmp/twint_fork-2.5.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "twint_fork-2.5.2.tar", last modified: Wed Jun  7 09:02:12 2023, max compression
+gzip compressed data, was "twint_fork-2.5.3.tar", last modified: Wed Jun 28 13:15:20 2023, max compression
```

## Comparing `twint_fork-2.5.2.tar` & `twint_fork-2.5.3.tar`

### file list

```diff
@@ -1,38 +1,38 @@
-drwxr-xr-x   0 hyi        (502) staff       (20)        0 2023-06-07 09:02:12.433922 twint_fork-2.5.2/
--rw-r--r--   0 hyi        (502) staff       (20)     1071 2023-03-22 13:37:09.000000 twint_fork-2.5.2/LICENSE
--rw-r--r--   0 hyi        (502) staff       (20)       26 2023-03-22 13:37:09.000000 twint_fork-2.5.2/MANIFEST.in
--rw-r--r--   0 hyi        (502) staff       (20)     7665 2023-06-07 09:02:12.433724 twint_fork-2.5.2/PKG-INFO
--rw-r--r--   0 hyi        (502) staff       (20)     6853 2023-04-26 08:12:43.000000 twint_fork-2.5.2/README.md
--rw-r--r--   0 hyi        (502) staff       (20)       38 2023-06-07 09:02:12.433973 twint_fork-2.5.2/setup.cfg
--rw-r--r--   0 hyi        (502) staff       (20)     1815 2023-06-07 09:01:59.000000 twint_fork-2.5.2/setup.py
-drwxr-xr-x   0 hyi        (502) staff       (20)        0 2023-06-07 09:02:12.429511 twint_fork-2.5.2/twint/
--rw-r--r--   0 hyi        (502) staff       (20)      808 2023-04-20 09:29:26.000000 twint_fork-2.5.2/twint/__init__.py
--rw-r--r--   0 hyi        (502) staff       (20)       61 2023-04-20 09:29:26.000000 twint_fork-2.5.2/twint/__main__.py
--rw-r--r--   0 hyi        (502) staff       (20)       64 2023-04-20 09:29:26.000000 twint_fork-2.5.2/twint/__version__.py
--rw-r--r--   0 hyi        (502) staff       (20)    15324 2023-04-26 06:33:01.000000 twint_fork-2.5.2/twint/cli.py
--rw-r--r--   0 hyi        (502) staff       (20)     2513 2023-04-20 09:29:26.000000 twint_fork-2.5.2/twint/config.py
--rw-r--r--   0 hyi        (502) staff       (20)     1080 2023-04-20 09:29:26.000000 twint_fork-2.5.2/twint/datelock.py
--rw-r--r--   0 hyi        (502) staff       (20)     4000 2023-06-07 09:01:42.000000 twint_fork-2.5.2/twint/feed.py
--rw-r--r--   0 hyi        (502) staff       (20)     4464 2023-04-20 09:29:26.000000 twint_fork-2.5.2/twint/format.py
--rw-r--r--   0 hyi        (502) staff       (20)    11838 2023-04-26 00:44:20.000000 twint_fork-2.5.2/twint/get.py
--rw-r--r--   0 hyi        (502) staff       (20)     8168 2023-04-20 09:29:26.000000 twint_fork-2.5.2/twint/output.py
--rw-r--r--   0 hyi        (502) staff       (20)    19339 2023-05-15 04:57:25.000000 twint_fork-2.5.2/twint/run.py
-drwxr-xr-x   0 hyi        (502) staff       (20)        0 2023-06-07 09:02:12.431445 twint_fork-2.5.2/twint/storage/
--rw-r--r--   0 hyi        (502) staff       (20)        0 2023-03-22 13:37:09.000000 twint_fork-2.5.2/twint/storage/__init__.py
--rw-r--r--   0 hyi        (502) staff       (20)    11197 2023-04-20 09:29:26.000000 twint_fork-2.5.2/twint/storage/db.py
--rw-r--r--   0 hyi        (502) staff       (20)    13379 2023-04-20 09:29:26.000000 twint_fork-2.5.2/twint/storage/elasticsearch.py
--rw-r--r--   0 hyi        (502) staff       (20)     6307 2023-04-20 09:29:26.000000 twint_fork-2.5.2/twint/storage/panda.py
--rw-r--r--   0 hyi        (502) staff       (20)     2161 2023-04-20 09:29:26.000000 twint_fork-2.5.2/twint/storage/write.py
--rw-r--r--   0 hyi        (502) staff       (20)     3493 2023-04-20 09:29:26.000000 twint_fork-2.5.2/twint/storage/write_meta.py
--rw-r--r--   0 hyi        (502) staff       (20)     3937 2023-04-20 09:29:26.000000 twint_fork-2.5.2/twint/token.py
--rw-r--r--   0 hyi        (502) staff       (20)     5533 2023-04-25 13:25:39.000000 twint_fork-2.5.2/twint/tweet.py
--rw-r--r--   0 hyi        (502) staff       (20)     5610 2023-06-07 06:06:54.000000 twint_fork-2.5.2/twint/url.py
--rw-r--r--   0 hyi        (502) staff       (20)     1285 2023-04-26 00:44:03.000000 twint_fork-2.5.2/twint/user.py
--rw-r--r--   0 hyi        (502) staff       (20)      622 2023-04-20 09:29:26.000000 twint_fork-2.5.2/twint/verbose.py
-drwxr-xr-x   0 hyi        (502) staff       (20)        0 2023-06-07 09:02:12.433463 twint_fork-2.5.2/twint_fork.egg-info/
--rw-r--r--   0 hyi        (502) staff       (20)     7665 2023-06-07 09:02:12.000000 twint_fork-2.5.2/twint_fork.egg-info/PKG-INFO
--rw-r--r--   0 hyi        (502) staff       (20)      645 2023-06-07 09:02:12.000000 twint_fork-2.5.2/twint_fork.egg-info/SOURCES.txt
--rw-r--r--   0 hyi        (502) staff       (20)       62 2023-06-07 09:02:12.000000 twint_fork-2.5.2/twint_fork.egg-info/dependency_links.txt
--rw-r--r--   0 hyi        (502) staff       (20)       51 2023-06-07 09:02:12.000000 twint_fork-2.5.2/twint_fork.egg-info/entry_points.txt
--rw-r--r--   0 hyi        (502) staff       (20)      142 2023-06-07 09:02:12.000000 twint_fork-2.5.2/twint_fork.egg-info/requires.txt
--rw-r--r--   0 hyi        (502) staff       (20)        6 2023-06-07 09:02:12.000000 twint_fork-2.5.2/twint_fork.egg-info/top_level.txt
+drwxr-xr-x   0 hyi        (502) staff       (20)        0 2023-06-28 13:15:20.334693 twint_fork-2.5.3/
+-rw-r--r--   0 hyi        (502) staff       (20)     1071 2023-03-22 13:37:09.000000 twint_fork-2.5.3/LICENSE
+-rw-r--r--   0 hyi        (502) staff       (20)       26 2023-03-22 13:37:09.000000 twint_fork-2.5.3/MANIFEST.in
+-rw-r--r--   0 hyi        (502) staff       (20)     7665 2023-06-28 13:15:20.334485 twint_fork-2.5.3/PKG-INFO
+-rw-r--r--   0 hyi        (502) staff       (20)     6853 2023-04-26 08:12:43.000000 twint_fork-2.5.3/README.md
+-rw-r--r--   0 hyi        (502) staff       (20)       38 2023-06-28 13:15:20.334745 twint_fork-2.5.3/setup.cfg
+-rw-r--r--   0 hyi        (502) staff       (20)     1815 2023-06-28 13:15:08.000000 twint_fork-2.5.3/setup.py
+drwxr-xr-x   0 hyi        (502) staff       (20)        0 2023-06-28 13:15:20.321635 twint_fork-2.5.3/twint/
+-rw-r--r--   0 hyi        (502) staff       (20)      808 2023-04-20 09:29:26.000000 twint_fork-2.5.3/twint/__init__.py
+-rw-r--r--   0 hyi        (502) staff       (20)       61 2023-04-20 09:29:26.000000 twint_fork-2.5.3/twint/__main__.py
+-rw-r--r--   0 hyi        (502) staff       (20)       64 2023-04-20 09:29:26.000000 twint_fork-2.5.3/twint/__version__.py
+-rw-r--r--   0 hyi        (502) staff       (20)    15324 2023-04-26 06:33:01.000000 twint_fork-2.5.3/twint/cli.py
+-rw-r--r--   0 hyi        (502) staff       (20)     2513 2023-04-20 09:29:26.000000 twint_fork-2.5.3/twint/config.py
+-rw-r--r--   0 hyi        (502) staff       (20)     1080 2023-04-20 09:29:26.000000 twint_fork-2.5.3/twint/datelock.py
+-rw-r--r--   0 hyi        (502) staff       (20)     4000 2023-06-10 09:40:17.000000 twint_fork-2.5.3/twint/feed.py
+-rw-r--r--   0 hyi        (502) staff       (20)     4519 2023-06-28 13:14:53.000000 twint_fork-2.5.3/twint/format.py
+-rw-r--r--   0 hyi        (502) staff       (20)    11838 2023-06-10 09:40:17.000000 twint_fork-2.5.3/twint/get.py
+-rw-r--r--   0 hyi        (502) staff       (20)     8168 2023-04-20 09:29:26.000000 twint_fork-2.5.3/twint/output.py
+-rw-r--r--   0 hyi        (502) staff       (20)    19339 2023-05-15 04:57:25.000000 twint_fork-2.5.3/twint/run.py
+drwxr-xr-x   0 hyi        (502) staff       (20)        0 2023-06-28 13:15:20.332472 twint_fork-2.5.3/twint/storage/
+-rw-r--r--   0 hyi        (502) staff       (20)        0 2023-03-22 13:37:09.000000 twint_fork-2.5.3/twint/storage/__init__.py
+-rw-r--r--   0 hyi        (502) staff       (20)    11197 2023-04-20 09:29:26.000000 twint_fork-2.5.3/twint/storage/db.py
+-rw-r--r--   0 hyi        (502) staff       (20)    13379 2023-04-20 09:29:26.000000 twint_fork-2.5.3/twint/storage/elasticsearch.py
+-rw-r--r--   0 hyi        (502) staff       (20)     6307 2023-04-20 09:29:26.000000 twint_fork-2.5.3/twint/storage/panda.py
+-rw-r--r--   0 hyi        (502) staff       (20)     2161 2023-04-20 09:29:26.000000 twint_fork-2.5.3/twint/storage/write.py
+-rw-r--r--   0 hyi        (502) staff       (20)     3493 2023-04-20 09:29:26.000000 twint_fork-2.5.3/twint/storage/write_meta.py
+-rw-r--r--   0 hyi        (502) staff       (20)     3937 2023-04-20 09:29:26.000000 twint_fork-2.5.3/twint/token.py
+-rw-r--r--   0 hyi        (502) staff       (20)     5533 2023-04-25 13:25:39.000000 twint_fork-2.5.3/twint/tweet.py
+-rw-r--r--   0 hyi        (502) staff       (20)     5610 2023-06-10 09:40:17.000000 twint_fork-2.5.3/twint/url.py
+-rw-r--r--   0 hyi        (502) staff       (20)     1285 2023-04-26 00:44:03.000000 twint_fork-2.5.3/twint/user.py
+-rw-r--r--   0 hyi        (502) staff       (20)      622 2023-04-20 09:29:26.000000 twint_fork-2.5.3/twint/verbose.py
+drwxr-xr-x   0 hyi        (502) staff       (20)        0 2023-06-28 13:15:20.334201 twint_fork-2.5.3/twint_fork.egg-info/
+-rw-r--r--   0 hyi        (502) staff       (20)     7665 2023-06-28 13:15:20.000000 twint_fork-2.5.3/twint_fork.egg-info/PKG-INFO
+-rw-r--r--   0 hyi        (502) staff       (20)      645 2023-06-28 13:15:20.000000 twint_fork-2.5.3/twint_fork.egg-info/SOURCES.txt
+-rw-r--r--   0 hyi        (502) staff       (20)       62 2023-06-28 13:15:20.000000 twint_fork-2.5.3/twint_fork.egg-info/dependency_links.txt
+-rw-r--r--   0 hyi        (502) staff       (20)       51 2023-06-28 13:15:20.000000 twint_fork-2.5.3/twint_fork.egg-info/entry_points.txt
+-rw-r--r--   0 hyi        (502) staff       (20)      142 2023-06-28 13:15:20.000000 twint_fork-2.5.3/twint_fork.egg-info/requires.txt
+-rw-r--r--   0 hyi        (502) staff       (20)        6 2023-06-28 13:15:20.000000 twint_fork-2.5.3/twint_fork.egg-info/top_level.txt
```

### Comparing `twint_fork-2.5.2/LICENSE` & `twint_fork-2.5.3/LICENSE`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/PKG-INFO` & `twint_fork-2.5.3/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: twint_fork
-Version: 2.5.2
+Version: 2.5.3
 Summary: An advanced Twitter scraping & OSINT tool.
 Home-page: https://github.com/yihong0618/twint
 Author: Cody Zacharias, yihong0618
 Author-email: codyzacharias@pm.me, zouzou0208@gmail.com
 License: MIT
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python
```

### Comparing `twint_fork-2.5.2/README.md` & `twint_fork-2.5.3/README.md`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/setup.py` & `twint_fork-2.5.3/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -33,15 +33,15 @@
 here = os.path.abspath(os.path.dirname(__file__))
 
 with io.open(os.path.join(here, "README.md"), encoding="utf-8") as f:
     long_description = "\n" + f.read()
 
 setup(
     name=NAME,
-    version="2.5.2",
+    version="2.5.3",
     description=DESCRIPTION,
     long_description=long_description,
     long_description_content_type="text/markdown",
     author=AUTHOR,
     author_email=EMAIL,
     python_requires=REQUIRES_PYTHON,
     url=URL,
```

### Comparing `twint_fork-2.5.2/twint/__init__.py` & `twint_fork-2.5.3/twint/__init__.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/cli.py` & `twint_fork-2.5.3/twint/cli.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/config.py` & `twint_fork-2.5.3/twint/config.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/datelock.py` & `twint_fork-2.5.3/twint/datelock.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/feed.py` & `twint_fork-2.5.3/twint/feed.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/format.py` & `twint_fork-2.5.3/twint/format.py`

 * *Files 3% similar despite different names*

```diff
@@ -17,24 +17,24 @@
         output = output.replace("{photos}", ",".join(t.photos))
         output = output.replace("{video}", str(t.video))
         output = output.replace("{thumbnail}", t.thumbnail)
         output = output.replace("{tweet}", t.tweet)
         output = output.replace("{language}", t.lang)
         output = output.replace("{hashtags}", ",".join(t.hashtags))
         output = output.replace("{cashtags}", ",".join(t.cashtags))
-        output = output.replace("{replies}", t.replies_count)
-        output = output.replace("{retweets}", t.retweets_count)
-        output = output.replace("{likes}", t.likes_count)
+        output = output.replace("{replies}", str(t.replies_count))
+        output = output.replace("{retweets}", str(t.retweets_count))
+        output = output.replace("{likes}", str(t.likes_count))
         output = output.replace("{link}", t.link)
         output = output.replace("{is_retweet}", str(t.retweet))
         output = output.replace("{user_rt_id}", str(t.user_rt_id))
         output = output.replace("{quote_url}", t.quote_url)
         output = output.replace("{near}", t.near)
         output = output.replace("{geo}", t.geo)
-        output = output.replace("{mentions}", ",".join(t.mentions))
+        output = output.replace("{mentions}", ",".join([mention['screen_name'] for mention in t.mentions]))
         output = output.replace("{translate}", t.translate)
         output = output.replace("{trans_src}", t.trans_src)
         output = output.replace("{trans_dest}", t.trans_dest)
     else:
         logme.debug(__name__ + ":Tweet:notFormat")
         output = f"{t.id_str} {t.datestamp} {t.timestamp} {t.timezone} "
```

### Comparing `twint_fork-2.5.2/twint/get.py` & `twint_fork-2.5.3/twint/get.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/output.py` & `twint_fork-2.5.3/twint/output.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/run.py` & `twint_fork-2.5.3/twint/run.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/storage/db.py` & `twint_fork-2.5.3/twint/storage/db.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/storage/elasticsearch.py` & `twint_fork-2.5.3/twint/storage/elasticsearch.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/storage/panda.py` & `twint_fork-2.5.3/twint/storage/panda.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/storage/write.py` & `twint_fork-2.5.3/twint/storage/write.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/storage/write_meta.py` & `twint_fork-2.5.3/twint/storage/write_meta.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/token.py` & `twint_fork-2.5.3/twint/token.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/tweet.py` & `twint_fork-2.5.3/twint/tweet.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/url.py` & `twint_fork-2.5.3/twint/url.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/user.py` & `twint_fork-2.5.3/twint/user.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint/verbose.py` & `twint_fork-2.5.3/twint/verbose.py`

 * *Files identical despite different names*

### Comparing `twint_fork-2.5.2/twint_fork.egg-info/PKG-INFO` & `twint_fork-2.5.3/twint_fork.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: twint-fork
-Version: 2.5.2
+Version: 2.5.3
 Summary: An advanced Twitter scraping & OSINT tool.
 Home-page: https://github.com/yihong0618/twint
 Author: Cody Zacharias, yihong0618
 Author-email: codyzacharias@pm.me, zouzou0208@gmail.com
 License: MIT
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python
```

### Comparing `twint_fork-2.5.2/twint_fork.egg-info/SOURCES.txt` & `twint_fork-2.5.3/twint_fork.egg-info/SOURCES.txt`

 * *Files identical despite different names*


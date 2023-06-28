# Comparing `tmp/Mirrorstr-0.0.6.tar.gz` & `tmp/Mirrorstr-0.0.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "Mirrorstr-0.0.6.tar", last modified: Sat Jun 10 02:23:22 2023, max compression
+gzip compressed data, was "Mirrorstr-0.0.7.tar", last modified: Wed Jun 28 14:17:13 2023, max compression
```

## Comparing `Mirrorstr-0.0.6.tar` & `Mirrorstr-0.0.7.tar`

### file list

```diff
@@ -1,22 +1,21 @@
-drwxr-xr-x   0 lira       (501) staff       (20)        0 2023-06-10 02:23:22.247808 Mirrorstr-0.0.6/
--rw-r--r--   0 lira       (501) staff       (20)     1073 2023-06-08 02:56:19.000000 Mirrorstr-0.0.6/LICENSE
--rw-r--r--   0 lira       (501) staff       (20)     3373 2023-06-10 02:23:22.247674 Mirrorstr-0.0.6/PKG-INFO
--rw-r--r--   0 lira       (501) staff       (20)     2838 2023-06-08 03:38:59.000000 Mirrorstr-0.0.6/README.md
--rw-r--r--   0 lira       (501) staff       (20)      912 2023-06-10 02:11:27.000000 Mirrorstr-0.0.6/pyproject.toml
--rw-r--r--   0 lira       (501) staff       (20)       38 2023-06-10 02:23:22.247849 Mirrorstr-0.0.6/setup.cfg
-drwxr-xr-x   0 lira       (501) staff       (20)        0 2023-06-10 02:23:22.244526 Mirrorstr-0.0.6/src/
-drwxr-xr-x   0 lira       (501) staff       (20)        0 2023-06-10 02:23:22.245966 Mirrorstr-0.0.6/src/Mirrorstr.egg-info/
--rw-r--r--   0 lira       (501) staff       (20)     3373 2023-06-10 02:23:22.000000 Mirrorstr-0.0.6/src/Mirrorstr.egg-info/PKG-INFO
--rw-r--r--   0 lira       (501) staff       (20)      472 2023-06-10 02:23:22.000000 Mirrorstr-0.0.6/src/Mirrorstr.egg-info/SOURCES.txt
--rw-r--r--   0 lira       (501) staff       (20)        1 2023-06-10 02:23:22.000000 Mirrorstr-0.0.6/src/Mirrorstr.egg-info/dependency_links.txt
--rw-r--r--   0 lira       (501) staff       (20)       60 2023-06-10 02:23:22.000000 Mirrorstr-0.0.6/src/Mirrorstr.egg-info/entry_points.txt
--rw-r--r--   0 lira       (501) staff       (20)       93 2023-06-10 02:23:22.000000 Mirrorstr-0.0.6/src/Mirrorstr.egg-info/requires.txt
--rw-r--r--   0 lira       (501) staff       (20)       10 2023-06-10 02:23:22.000000 Mirrorstr-0.0.6/src/Mirrorstr.egg-info/top_level.txt
-drwxr-xr-x   0 lira       (501) staff       (20)        0 2023-06-10 02:23:22.247321 Mirrorstr-0.0.6/src/mirrorstr/
--rw-r--r--   0 lira       (501) staff       (20)        0 2023-06-10 00:18:43.000000 Mirrorstr-0.0.6/src/mirrorstr/__init__.py
--rw-r--r--   0 lira       (501) staff       (20)       41 2023-06-10 01:30:15.000000 Mirrorstr-0.0.6/src/mirrorstr/hello_world.py
--rw-r--r--   0 lira       (501) staff       (20)     6906 2023-06-10 02:22:12.000000 Mirrorstr-0.0.6/src/mirrorstr/mirrorstr.py
--rw-r--r--   0 lira       (501) staff       (20)      677 2023-06-06 14:59:35.000000 Mirrorstr-0.0.6/src/mirrorstr/mp4_to_gif.py
--rw-r--r--   0 lira       (501) staff       (20)     1831 2023-06-10 02:05:37.000000 Mirrorstr-0.0.6/src/mirrorstr/post_note.py
--rw-r--r--   0 lira       (501) staff       (20)      148 2023-05-30 02:48:59.000000 Mirrorstr-0.0.6/src/mirrorstr/relay_list.txt
--rw-r--r--   0 lira       (501) staff       (20)      558 2023-06-03 00:24:11.000000 Mirrorstr-0.0.6/src/mirrorstr/upload_to_voidcat_and_return_url.py
+drwxr-xr-x   0 lira       (501) staff       (20)        0 2023-06-28 14:17:13.808740 Mirrorstr-0.0.7/
+-rw-r--r--   0 lira       (501) staff       (20)     1073 2023-06-08 02:56:19.000000 Mirrorstr-0.0.7/LICENSE
+-rw-r--r--   0 lira       (501) staff       (20)     3451 2023-06-28 14:17:13.808427 Mirrorstr-0.0.7/PKG-INFO
+-rw-r--r--   0 lira       (501) staff       (20)     2917 2023-06-19 00:09:57.000000 Mirrorstr-0.0.7/README.md
+-rw-r--r--   0 lira       (501) staff       (20)      923 2023-06-28 14:15:16.000000 Mirrorstr-0.0.7/pyproject.toml
+-rw-r--r--   0 lira       (501) staff       (20)       38 2023-06-28 14:17:13.808820 Mirrorstr-0.0.7/setup.cfg
+drwxr-xr-x   0 lira       (501) staff       (20)        0 2023-06-28 14:17:13.802989 Mirrorstr-0.0.7/src/
+drwxr-xr-x   0 lira       (501) staff       (20)        0 2023-06-28 14:17:13.805933 Mirrorstr-0.0.7/src/Mirrorstr.egg-info/
+-rw-r--r--   0 lira       (501) staff       (20)     3451 2023-06-28 14:17:13.000000 Mirrorstr-0.0.7/src/Mirrorstr.egg-info/PKG-INFO
+-rw-r--r--   0 lira       (501) staff       (20)      443 2023-06-28 14:17:13.000000 Mirrorstr-0.0.7/src/Mirrorstr.egg-info/SOURCES.txt
+-rw-r--r--   0 lira       (501) staff       (20)        1 2023-06-28 14:17:13.000000 Mirrorstr-0.0.7/src/Mirrorstr.egg-info/dependency_links.txt
+-rw-r--r--   0 lira       (501) staff       (20)       72 2023-06-28 14:17:13.000000 Mirrorstr-0.0.7/src/Mirrorstr.egg-info/entry_points.txt
+-rw-r--r--   0 lira       (501) staff       (20)       93 2023-06-28 14:17:13.000000 Mirrorstr-0.0.7/src/Mirrorstr.egg-info/requires.txt
+-rw-r--r--   0 lira       (501) staff       (20)       10 2023-06-28 14:17:13.000000 Mirrorstr-0.0.7/src/Mirrorstr.egg-info/top_level.txt
+drwxr-xr-x   0 lira       (501) staff       (20)        0 2023-06-28 14:17:13.808085 Mirrorstr-0.0.7/src/mirrorstr/
+-rw-r--r--   0 lira       (501) staff       (20)        0 2023-06-10 00:18:43.000000 Mirrorstr-0.0.7/src/mirrorstr/__init__.py
+-rw-r--r--   0 lira       (501) staff       (20)       41 2023-06-10 01:30:15.000000 Mirrorstr-0.0.7/src/mirrorstr/hello_world.py
+-rw-r--r--   0 lira       (501) staff       (20)     6342 2023-06-28 14:14:28.000000 Mirrorstr-0.0.7/src/mirrorstr/mirrorstr.py
+-rw-r--r--   0 lira       (501) staff       (20)      677 2023-06-06 14:59:35.000000 Mirrorstr-0.0.7/src/mirrorstr/mp4_to_gif.py
+-rw-r--r--   0 lira       (501) staff       (20)     1831 2023-06-10 02:05:37.000000 Mirrorstr-0.0.7/src/mirrorstr/post_note.py
+-rw-r--r--   0 lira       (501) staff       (20)      558 2023-06-03 00:24:11.000000 Mirrorstr-0.0.7/src/mirrorstr/upload_to_voidcat_and_return_url.py
```

### Comparing `Mirrorstr-0.0.6/LICENSE` & `Mirrorstr-0.0.7/LICENSE`

 * *Files identical despite different names*

### Comparing `Mirrorstr-0.0.6/PKG-INFO` & `Mirrorstr-0.0.7/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: Mirrorstr
-Version: 0.0.6
+Version: 0.0.7
 Summary: An application to mirror Nostr posts on twitter, and vice-versa
 Author-email: pleblira <pleblira@gmail.com>
 Project-URL: Homepage, https://github.com/pleblira/mirrorstr
 Project-URL: Bug Tracker, https://github.com/pleblira/mirrorstr/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
@@ -26,34 +26,36 @@
 
 The app is intended to be run locally from the command line.
 
 Libraries:
 https://github.com/jeffthibault/python-nostr (and its dependencies)
 https://github.com/JustAnotherArchivist/snscrape (and its dependencies)
 
-## Dependency
-This project depends on the dev version of snscrape, which is not available on PyPI. One place where you can find it is at: https://github.com/JustAnotherArchivist/snscrape.
+## Dev version of snscrape
+This project depends on the dev version of snscrape, an excellent twitter scraping library. The dev version is available on PyPI, and an additional command is needed to install it.
 
-You can install it by running the following command:
+# Install Mirrorstr
 
-'''
-pip3 install git+https://github.com/JustAnotherArchivist/snscrape.git
-'''
+```
+pip install mirrorstr && pip3 install git+https://github.com/JustAnotherArchivist/snscrape.git
+```
 
+* Not compatible with arm macs
 
 # TODO & Timeline
 
 The first functionality to develop will be Twitter => Nostr. It will take less time to develop and I think has higher demand at the moment.
 
 On the other hand, I believe that the Nostr => Twitter functionality is the end-goal for the application. The goal is for users to be on Nostr primarily and to use the application as a time-saver so their Nostr posts get mirrored on Twitter while the migration happens.
 
 ### 1 - Twitter => Nostr functionality
 [x] Twitter scraper - using the excellent tool by JustAnotherArchivist, snscrape (https://github.com/JustAnotherArchivist/snscrape)<br>
-[ ] Parse twitter content after scraping<br>
+[x] Parse twitter content after scraping<br>
 [x] Nostr posting
+[ ] Detect and import full threads
 
 ### 2 - Mirrorstr config file for Twitter => Nostr
 [ ] Select relays to post to<br>
 [ ] Add private key directly to config file, or always ask during initialization<br>
 [ ] Select monitored Twitter handle
 
 ### 3 - Nostr => Twitter
```

### Comparing `Mirrorstr-0.0.6/README.md` & `Mirrorstr-0.0.7/README.md`

 * *Files 16% similar despite different names*

```diff
@@ -12,34 +12,36 @@
 
 The app is intended to be run locally from the command line.
 
 Libraries:
 https://github.com/jeffthibault/python-nostr (and its dependencies)
 https://github.com/JustAnotherArchivist/snscrape (and its dependencies)
 
-## Dependency
-This project depends on the dev version of snscrape, which is not available on PyPI. One place where you can find it is at: https://github.com/JustAnotherArchivist/snscrape.
+## Dev version of snscrape
+This project depends on the dev version of snscrape, an excellent twitter scraping library. The dev version is available on PyPI, and an additional command is needed to install it.
 
-You can install it by running the following command:
+# Install Mirrorstr
 
-'''
-pip3 install git+https://github.com/JustAnotherArchivist/snscrape.git
-'''
+```
+pip install mirrorstr && pip3 install git+https://github.com/JustAnotherArchivist/snscrape.git
+```
 
+* Not compatible with arm macs
 
 # TODO & Timeline
 
 The first functionality to develop will be Twitter => Nostr. It will take less time to develop and I think has higher demand at the moment.
 
 On the other hand, I believe that the Nostr => Twitter functionality is the end-goal for the application. The goal is for users to be on Nostr primarily and to use the application as a time-saver so their Nostr posts get mirrored on Twitter while the migration happens.
 
 ### 1 - Twitter => Nostr functionality
 [x] Twitter scraper - using the excellent tool by JustAnotherArchivist, snscrape (https://github.com/JustAnotherArchivist/snscrape)<br>
-[ ] Parse twitter content after scraping<br>
+[x] Parse twitter content after scraping<br>
 [x] Nostr posting
+[ ] Detect and import full threads
 
 ### 2 - Mirrorstr config file for Twitter => Nostr
 [ ] Select relays to post to<br>
 [ ] Add private key directly to config file, or always ask during initialization<br>
 [ ] Select monitored Twitter handle
 
 ### 3 - Nostr => Twitter
@@ -50,8 +52,8 @@
 
 ### 4 - Mirrorstr config file for Nostr => Twitter
 [ ] Add npub(s) to monitor<br>
 [ ] Select monitored relays<br>
 [ ] Authenticate Twitter account<br>
 
 
-npub1ljraxpufmzjnfdvsw0tq9kwnypctwxus8n9w388uhkd8h73pzzlqgmdzfy / @pleblira
+npub1ljraxpufmzjnfdvsw0tq9kwnypctwxus8n9w388uhkd8h73pzzlqgmdzfy / @pleblira
```

### Comparing `Mirrorstr-0.0.6/pyproject.toml` & `Mirrorstr-0.0.7/pyproject.toml`

 * *Files 17% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools>=40.8.0", "wheel"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "Mirrorstr"
-version = "0.0.6"
+version = "0.0.7"
 authors = [
   { name="pleblira", email="pleblira@gmail.com" },
 ]
 description = "An application to mirror Nostr posts on twitter, and vice-versa"
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
@@ -26,14 +26,14 @@
 ]
 
 [project.urls]
 "Homepage" = "https://github.com/pleblira/mirrorstr"
 "Bug Tracker" = "https://github.com/pleblira/mirrorstr/issues"
 
 [project.scripts]
-mirrorstr = "mirrorstr.mirrorstr:mirrorstr"
+siggy_scrape = "siggy_scrape.siggy_scrape:siggy_scrape"
 
 [tool.setuptools.package-data]
 myModule = ["*.txt"]
 
 [tool.setuptools.packages.find]
-where = ["src"]
+where = ["src"]
```

### Comparing `Mirrorstr-0.0.6/src/Mirrorstr.egg-info/PKG-INFO` & `Mirrorstr-0.0.7/src/Mirrorstr.egg-info/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: Mirrorstr
-Version: 0.0.6
+Version: 0.0.7
 Summary: An application to mirror Nostr posts on twitter, and vice-versa
 Author-email: pleblira <pleblira@gmail.com>
 Project-URL: Homepage, https://github.com/pleblira/mirrorstr
 Project-URL: Bug Tracker, https://github.com/pleblira/mirrorstr/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
@@ -26,34 +26,36 @@
 
 The app is intended to be run locally from the command line.
 
 Libraries:
 https://github.com/jeffthibault/python-nostr (and its dependencies)
 https://github.com/JustAnotherArchivist/snscrape (and its dependencies)
 
-## Dependency
-This project depends on the dev version of snscrape, which is not available on PyPI. One place where you can find it is at: https://github.com/JustAnotherArchivist/snscrape.
+## Dev version of snscrape
+This project depends on the dev version of snscrape, an excellent twitter scraping library. The dev version is available on PyPI, and an additional command is needed to install it.
 
-You can install it by running the following command:
+# Install Mirrorstr
 
-'''
-pip3 install git+https://github.com/JustAnotherArchivist/snscrape.git
-'''
+```
+pip install mirrorstr && pip3 install git+https://github.com/JustAnotherArchivist/snscrape.git
+```
 
+* Not compatible with arm macs
 
 # TODO & Timeline
 
 The first functionality to develop will be Twitter => Nostr. It will take less time to develop and I think has higher demand at the moment.
 
 On the other hand, I believe that the Nostr => Twitter functionality is the end-goal for the application. The goal is for users to be on Nostr primarily and to use the application as a time-saver so their Nostr posts get mirrored on Twitter while the migration happens.
 
 ### 1 - Twitter => Nostr functionality
 [x] Twitter scraper - using the excellent tool by JustAnotherArchivist, snscrape (https://github.com/JustAnotherArchivist/snscrape)<br>
-[ ] Parse twitter content after scraping<br>
+[x] Parse twitter content after scraping<br>
 [x] Nostr posting
+[ ] Detect and import full threads
 
 ### 2 - Mirrorstr config file for Twitter => Nostr
 [ ] Select relays to post to<br>
 [ ] Add private key directly to config file, or always ask during initialization<br>
 [ ] Select monitored Twitter handle
 
 ### 3 - Nostr => Twitter
```

### Comparing `Mirrorstr-0.0.6/src/mirrorstr/mirrorstr.py` & `Mirrorstr-0.0.7/src/mirrorstr/mirrorstr.py`

 * *Files 17% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-from apscheduler.schedulers.background import BackgroundScheduler
+from apscheduler.schedulers.blocking import BlockingScheduler
 import time
 import random
 import subprocess
 import sys
 import json
 import datetime
 from mirrorstr.post_note import *
@@ -91,44 +91,28 @@
                         new_tweet = False
                 # print('exited while loop')
             else:
                 print('tweet is a reply')
 
 def mirrorstr():
     NOSTR_PRIVATE_KEY = input("Type Nostr nsec private key (enter 'test' to use test key nsec16pejvh2hdkf4rzrpejk93tmvuhaf8pv7eqenevk576492zqy6pfqguu985): ")
-
     TWITTER_HANDLE = input("Type Twitter handle: ")
 
     if NOSTR_PRIVATE_KEY == "test":
         NOSTR_PRIVATE_KEY = PrivateKey.from_nsec("nsec16pejvh2hdkf4rzrpejk93tmvuhaf8pv7eqenevk576492zqy6pfqguu985")
+    else:
+        NOSTR_PRIVATE_KEY = PrivateKey.from_nsec(NOSTR_PRIVATE_KEY.strip())
 
     with open('tweets.json','w') as f:
         f.write("[]")
 
     scrape = subprocess.run(['snscrape','--jsonl','-n','5','twitter-user',TWITTER_HANDLE], capture_output=True, text=True)
     json_from_output = json.loads("["+scrape.stdout.strip().replace("\n",",")+"]")
     json_from_output.reverse()
     with open('tweets.json','r+') as f:
         f.seek(0)
         f.write(json.dumps(json_from_output, indent=2))
     
-    scheduler = BackgroundScheduler()
+    scheduler = BlockingScheduler()
     scheduler.add_job(scrape_and_post, 'interval', seconds=10, args=[TWITTER_HANDLE,NOSTR_PRIVATE_KEY])
     print('\nstarting scheduler')
-    scheduler.start()
-
-    while True:
-#     with open('tweets.json', 'r') as f:
-#         tweets = json.load(f)
-#         last_queried_event_datetime = int(datetime.fromisoformat(tweets[len(tweets)-1]['date']).timestamp())
-#     # print(f"last queried event datetime {last_queried_event_datetime}")
-#     # quit()
-#     time.sleep(600)
-#     print('closing connections to relays')
-#     close_connections(relay_manager)
-#     time.sleep(5)
-#     print('restarting connection on relay manager')
-#     relay_manager = main(public_key.hex(), since=last_queried_event_datetime)
-#     print('resuming')
-        print('\nkeeping process alive')
-        time.sleep(30)
-
+    scheduler.start()
```

### Comparing `Mirrorstr-0.0.6/src/mirrorstr/mp4_to_gif.py` & `Mirrorstr-0.0.7/src/mirrorstr/mp4_to_gif.py`

 * *Files identical despite different names*

### Comparing `Mirrorstr-0.0.6/src/mirrorstr/post_note.py` & `Mirrorstr-0.0.7/src/mirrorstr/post_note.py`

 * *Files identical despite different names*

### Comparing `Mirrorstr-0.0.6/src/mirrorstr/upload_to_voidcat_and_return_url.py` & `Mirrorstr-0.0.7/src/mirrorstr/upload_to_voidcat_and_return_url.py`

 * *Files identical despite different names*


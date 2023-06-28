# Comparing `tmp/enviRobot_scoop-0.1.2.tar.gz` & `tmp/enviRobot_scoop-0.1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "enviRobot_scoop-0.1.2.tar", last modified: Wed Jun 28 12:46:49 2023, max compression
+gzip compressed data, was "enviRobot_scoop-0.1.3.tar", last modified: Wed Jun 28 13:10:07 2023, max compression
```

## Comparing `enviRobot_scoop-0.1.2.tar` & `enviRobot_scoop-0.1.3.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 12:46:49.369593 enviRobot_scoop-0.1.2/
--rw-rw-rw-   0        0        0     1061 2023-06-07 20:47:04.000000 enviRobot_scoop-0.1.2/LICENSE
--rw-rw-rw-   0        0        0      974 2023-06-28 12:46:49.368592 enviRobot_scoop-0.1.2/PKG-INFO
--rw-rw-rw-   0        0        0      492 2023-06-19 10:47:30.000000 enviRobot_scoop-0.1.2/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 12:46:49.358593 enviRobot_scoop-0.1.2/enviRobot_scoop/
--rw-rw-rw-   0        0        0        0 2023-06-07 20:27:34.000000 enviRobot_scoop-0.1.2/enviRobot_scoop/__init__.py
--rw-rw-rw-   0        0        0     1111 2023-05-17 08:59:45.000000 enviRobot_scoop-0.1.2/enviRobot_scoop/aiot_screenshot.py
--rw-rw-rw-   0        0        0     3597 2023-06-28 07:12:39.000000 enviRobot_scoop-0.1.2/enviRobot_scoop/enviRobot_scoop.py
--rw-rw-rw-   0        0        0    15189 2023-06-28 12:19:09.000000 enviRobot_scoop-0.1.2/enviRobot_scoop/gpt.py
--rw-rw-rw-   0        0        0     3879 2023-06-28 12:37:06.000000 enviRobot_scoop-0.1.2/enviRobot_scoop/plotly_screenshot.py
--rw-rw-rw-   0        0        0      419 2023-06-07 21:09:59.000000 enviRobot_scoop-0.1.2/enviRobot_scoop/upload_to_imgur.py
-drwxrwxrwx   0        0        0        0 2023-06-28 12:46:49.368592 enviRobot_scoop-0.1.2/enviRobot_scoop.egg-info/
--rw-rw-rw-   0        0        0      974 2023-06-28 12:46:49.000000 enviRobot_scoop-0.1.2/enviRobot_scoop.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      413 2023-06-28 12:46:49.000000 enviRobot_scoop-0.1.2/enviRobot_scoop.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 12:46:49.000000 enviRobot_scoop-0.1.2/enviRobot_scoop.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      206 2023-06-28 12:46:49.000000 enviRobot_scoop-0.1.2/enviRobot_scoop.egg-info/requires.txt
--rw-rw-rw-   0        0        0       16 2023-06-28 12:46:49.000000 enviRobot_scoop-0.1.2/enviRobot_scoop.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 12:46:49.369593 enviRobot_scoop-0.1.2/setup.cfg
--rw-rw-rw-   0        0        0     1066 2023-06-28 12:45:19.000000 enviRobot_scoop-0.1.2/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:10:07.174695 enviRobot_scoop-0.1.3/
+-rw-rw-rw-   0        0        0     1061 2023-06-07 20:47:04.000000 enviRobot_scoop-0.1.3/LICENSE
+-rw-rw-rw-   0        0        0      974 2023-06-28 13:10:07.174695 enviRobot_scoop-0.1.3/PKG-INFO
+-rw-rw-rw-   0        0        0      492 2023-06-19 10:47:30.000000 enviRobot_scoop-0.1.3/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 13:10:07.165697 enviRobot_scoop-0.1.3/enviRobot_scoop/
+-rw-rw-rw-   0        0        0        0 2023-06-07 20:27:34.000000 enviRobot_scoop-0.1.3/enviRobot_scoop/__init__.py
+-rw-rw-rw-   0        0        0     1111 2023-05-17 08:59:45.000000 enviRobot_scoop-0.1.3/enviRobot_scoop/aiot_screenshot.py
+-rw-rw-rw-   0        0        0     3605 2023-06-28 13:06:36.000000 enviRobot_scoop-0.1.3/enviRobot_scoop/enviRobot_scoop.py
+-rw-rw-rw-   0        0        0    15176 2023-06-28 13:06:08.000000 enviRobot_scoop-0.1.3/enviRobot_scoop/gpt.py
+-rw-rw-rw-   0        0        0     3879 2023-06-28 12:37:06.000000 enviRobot_scoop-0.1.3/enviRobot_scoop/plotly_screenshot.py
+-rw-rw-rw-   0        0        0      419 2023-06-07 21:09:59.000000 enviRobot_scoop-0.1.3/enviRobot_scoop/upload_to_imgur.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:10:07.173699 enviRobot_scoop-0.1.3/enviRobot_scoop.egg-info/
+-rw-rw-rw-   0        0        0      974 2023-06-28 13:10:07.000000 enviRobot_scoop-0.1.3/enviRobot_scoop.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      413 2023-06-28 13:10:07.000000 enviRobot_scoop-0.1.3/enviRobot_scoop.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 13:10:07.000000 enviRobot_scoop-0.1.3/enviRobot_scoop.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      206 2023-06-28 13:10:07.000000 enviRobot_scoop-0.1.3/enviRobot_scoop.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       16 2023-06-28 13:10:07.000000 enviRobot_scoop-0.1.3/enviRobot_scoop.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 13:10:07.174695 enviRobot_scoop-0.1.3/setup.cfg
+-rw-rw-rw-   0        0        0     1066 2023-06-28 13:08:34.000000 enviRobot_scoop-0.1.3/setup.py
```

### Comparing `enviRobot_scoop-0.1.2/LICENSE` & `enviRobot_scoop-0.1.3/LICENSE`

 * *Files identical despite different names*

### Comparing `enviRobot_scoop-0.1.2/PKG-INFO` & `enviRobot_scoop-0.1.3/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: enviRobot_scoop
-Version: 0.1.2
+Version: 0.1.3
 Summary: enviRobot service that can be held by Scoop.
 Home-page: https://github.com/bohachu/ask_enviRobot
 Author: JcXGTcW
 Author-email: jcxgtcw@cameo.tw
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `enviRobot_scoop-0.1.2/enviRobot_scoop/aiot_screenshot.py` & `enviRobot_scoop-0.1.3/enviRobot_scoop/aiot_screenshot.py`

 * *Files identical despite different names*

### Comparing `enviRobot_scoop-0.1.2/enviRobot_scoop/enviRobot_scoop.py` & `enviRobot_scoop-0.1.3/enviRobot_scoop/enviRobot_scoop.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 import asyncio
 import json
-from upload_to_imgur import upload_to_imgur
-import gpt
+from .upload_to_imgur import upload_to_imgur
+from . import gpt
 import random
 import string
 import os
 import re
 import sys
 import contextlib
```

### Comparing `enviRobot_scoop-0.1.2/enviRobot_scoop/gpt.py` & `enviRobot_scoop-0.1.3/enviRobot_scoop/gpt.py`

 * *Files 0% similar despite different names*

```diff
@@ -4,16 +4,16 @@
 import json
 import geocoder
 import os
 from dotenv import load_dotenv
 from geopy import Point
 from geopy.distance import distance, geodesic
 import requests
-from aiot_screenshot import aiot_screenshot
-from plotly_screenshot import save_fig
+from . import aiot_screenshot
+from .plotly_screenshot import save_fig
 import time
 
 # https://www.youtube.com/watch?v=I4T--ycOpi0&ab_channel=JieJenn
 
 load_dotenv(dotenv_path='./.env')
 
 def openai_init(key_path):
```

### Comparing `enviRobot_scoop-0.1.2/enviRobot_scoop/plotly_screenshot.py` & `enviRobot_scoop-0.1.3/enviRobot_scoop/plotly_screenshot.py`

 * *Files identical despite different names*

### Comparing `enviRobot_scoop-0.1.2/enviRobot_scoop.egg-info/PKG-INFO` & `enviRobot_scoop-0.1.3/enviRobot_scoop.egg-info/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: enviRobot-scoop
-Version: 0.1.2
+Version: 0.1.3
 Summary: enviRobot service that can be held by Scoop.
 Home-page: https://github.com/bohachu/ask_enviRobot
 Author: JcXGTcW
 Author-email: jcxgtcw@cameo.tw
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `enviRobot_scoop-0.1.2/setup.py` & `enviRobot_scoop-0.1.3/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 # 若Discription.md中有中文 須加上 encoding="utf-8"
 with open("README.md", "r",encoding="utf-8") as f:
     long_description = f.read()
     
 setuptools.setup(
     name = "enviRobot_scoop",
-    version = "0.1.2",
+    version = "0.1.3",
     author = "JcXGTcW",
     author_email="jcxgtcw@cameo.tw",
     description="enviRobot service that can be held by Scoop.",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/bohachu/ask_enviRobot",
     packages=setuptools.find_packages(),
```


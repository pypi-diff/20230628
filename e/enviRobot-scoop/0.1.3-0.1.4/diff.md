# Comparing `tmp/enviRobot_scoop-0.1.3.tar.gz` & `tmp/enviRobot_scoop-0.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "enviRobot_scoop-0.1.3.tar", last modified: Wed Jun 28 13:10:07 2023, max compression
+gzip compressed data, was "enviRobot_scoop-0.1.4.tar", last modified: Wed Jun 28 13:26:34 2023, max compression
```

## Comparing `enviRobot_scoop-0.1.3.tar` & `enviRobot_scoop-0.1.4.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 13:10:07.174695 enviRobot_scoop-0.1.3/
--rw-rw-rw-   0        0        0     1061 2023-06-07 20:47:04.000000 enviRobot_scoop-0.1.3/LICENSE
--rw-rw-rw-   0        0        0      974 2023-06-28 13:10:07.174695 enviRobot_scoop-0.1.3/PKG-INFO
--rw-rw-rw-   0        0        0      492 2023-06-19 10:47:30.000000 enviRobot_scoop-0.1.3/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 13:10:07.165697 enviRobot_scoop-0.1.3/enviRobot_scoop/
--rw-rw-rw-   0        0        0        0 2023-06-07 20:27:34.000000 enviRobot_scoop-0.1.3/enviRobot_scoop/__init__.py
--rw-rw-rw-   0        0        0     1111 2023-05-17 08:59:45.000000 enviRobot_scoop-0.1.3/enviRobot_scoop/aiot_screenshot.py
--rw-rw-rw-   0        0        0     3605 2023-06-28 13:06:36.000000 enviRobot_scoop-0.1.3/enviRobot_scoop/enviRobot_scoop.py
--rw-rw-rw-   0        0        0    15176 2023-06-28 13:06:08.000000 enviRobot_scoop-0.1.3/enviRobot_scoop/gpt.py
--rw-rw-rw-   0        0        0     3879 2023-06-28 12:37:06.000000 enviRobot_scoop-0.1.3/enviRobot_scoop/plotly_screenshot.py
--rw-rw-rw-   0        0        0      419 2023-06-07 21:09:59.000000 enviRobot_scoop-0.1.3/enviRobot_scoop/upload_to_imgur.py
-drwxrwxrwx   0        0        0        0 2023-06-28 13:10:07.173699 enviRobot_scoop-0.1.3/enviRobot_scoop.egg-info/
--rw-rw-rw-   0        0        0      974 2023-06-28 13:10:07.000000 enviRobot_scoop-0.1.3/enviRobot_scoop.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      413 2023-06-28 13:10:07.000000 enviRobot_scoop-0.1.3/enviRobot_scoop.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 13:10:07.000000 enviRobot_scoop-0.1.3/enviRobot_scoop.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      206 2023-06-28 13:10:07.000000 enviRobot_scoop-0.1.3/enviRobot_scoop.egg-info/requires.txt
--rw-rw-rw-   0        0        0       16 2023-06-28 13:10:07.000000 enviRobot_scoop-0.1.3/enviRobot_scoop.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 13:10:07.174695 enviRobot_scoop-0.1.3/setup.cfg
--rw-rw-rw-   0        0        0     1066 2023-06-28 13:08:34.000000 enviRobot_scoop-0.1.3/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:26:34.988608 enviRobot_scoop-0.1.4/
+-rw-rw-rw-   0        0        0     1061 2023-06-07 20:47:04.000000 enviRobot_scoop-0.1.4/LICENSE
+-rw-rw-rw-   0        0        0      974 2023-06-28 13:26:34.987608 enviRobot_scoop-0.1.4/PKG-INFO
+-rw-rw-rw-   0        0        0      492 2023-06-19 10:47:30.000000 enviRobot_scoop-0.1.4/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 13:26:34.981610 enviRobot_scoop-0.1.4/enviRobot_scoop/
+-rw-rw-rw-   0        0        0        0 2023-06-07 20:27:34.000000 enviRobot_scoop-0.1.4/enviRobot_scoop/__init__.py
+-rw-rw-rw-   0        0        0     1111 2023-05-17 08:59:45.000000 enviRobot_scoop-0.1.4/enviRobot_scoop/aiot_screenshot.py
+-rw-rw-rw-   0        0        0     3605 2023-06-28 13:06:36.000000 enviRobot_scoop-0.1.4/enviRobot_scoop/enviRobot_scoop.py
+-rw-rw-rw-   0        0        0    15176 2023-06-28 13:06:08.000000 enviRobot_scoop-0.1.4/enviRobot_scoop/gpt.py
+-rw-rw-rw-   0        0        0     3967 2023-06-28 13:25:31.000000 enviRobot_scoop-0.1.4/enviRobot_scoop/plotly_screenshot.py
+-rw-rw-rw-   0        0        0      419 2023-06-07 21:09:59.000000 enviRobot_scoop-0.1.4/enviRobot_scoop/upload_to_imgur.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:26:34.986608 enviRobot_scoop-0.1.4/enviRobot_scoop.egg-info/
+-rw-rw-rw-   0        0        0      974 2023-06-28 13:26:34.000000 enviRobot_scoop-0.1.4/enviRobot_scoop.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      413 2023-06-28 13:26:34.000000 enviRobot_scoop-0.1.4/enviRobot_scoop.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 13:26:34.000000 enviRobot_scoop-0.1.4/enviRobot_scoop.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      206 2023-06-28 13:26:34.000000 enviRobot_scoop-0.1.4/enviRobot_scoop.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       16 2023-06-28 13:26:34.000000 enviRobot_scoop-0.1.4/enviRobot_scoop.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 13:26:34.988608 enviRobot_scoop-0.1.4/setup.cfg
+-rw-rw-rw-   0        0        0     1066 2023-06-28 13:26:02.000000 enviRobot_scoop-0.1.4/setup.py
```

### Comparing `enviRobot_scoop-0.1.3/LICENSE` & `enviRobot_scoop-0.1.4/LICENSE`

 * *Files identical despite different names*

### Comparing `enviRobot_scoop-0.1.3/PKG-INFO` & `enviRobot_scoop-0.1.4/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: enviRobot_scoop
-Version: 0.1.3
+Version: 0.1.4
 Summary: enviRobot service that can be held by Scoop.
 Home-page: https://github.com/bohachu/ask_enviRobot
 Author: JcXGTcW
 Author-email: jcxgtcw@cameo.tw
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `enviRobot_scoop-0.1.3/enviRobot_scoop/aiot_screenshot.py` & `enviRobot_scoop-0.1.4/enviRobot_scoop/aiot_screenshot.py`

 * *Files identical despite different names*

### Comparing `enviRobot_scoop-0.1.3/enviRobot_scoop/enviRobot_scoop.py` & `enviRobot_scoop-0.1.4/enviRobot_scoop/enviRobot_scoop.py`

 * *Files identical despite different names*

### Comparing `enviRobot_scoop-0.1.3/enviRobot_scoop/gpt.py` & `enviRobot_scoop-0.1.4/enviRobot_scoop/gpt.py`

 * *Files identical despite different names*

### Comparing `enviRobot_scoop-0.1.3/enviRobot_scoop/plotly_screenshot.py` & `enviRobot_scoop-0.1.4/enviRobot_scoop/plotly_screenshot.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,11 +1,12 @@
 import plotly.graph_objects as go
 from dotenv import load_dotenv
 import pandas as pd
 import os
+from pathlib import Path
 
 load_dotenv(dotenv_path='./.env')
 
 def save_fig(center_lat, center_lon, data, image_path = 'test.png', zoom=13.5):
     
     data = pd.DataFrame(data)
     data['pm2_5'] = data['pm2_5'].astype(float)
@@ -81,14 +82,15 @@
             symbol='circle',
             color='#0000FF'
         )
     )
 
     fig = go.Figure(data=[center_trace,data], layout=layout)
     #fig.show()
+    Path(image_path).parent.mkdir(parents=True, exist_ok=True)
     fig.write_image(image_path, scale=2)
 
 if __name__ == '__main__':
     data = [{'deviceId': '10401411473', 'lat': '25.0072', 'lon': '121.5161', 'pm2_5': '4.31'}, {'deviceId': '10394742841', 'lat': '25.0072', 'lon': '121.5122', 'pm2_5': '2.45'}, {'deviceId': '10394403129', 'lat': '25.0093', 'lon': '121.5105', 'pm2_5': '2.97'}, {'deviceId': '10391606094', 'lat': '25.0037', 'lon': '121.5136', 'pm2_5': '2.97'}, {'deviceId': '10382402966', 'lat': '25.0037', 'lon': '121.5128', 'pm2_5': '3.38'}, {'deviceId': '10382310374', 'lat': '25.0128', 'lon': '121.5070', 'pm2_5': '2.62'}, {'deviceId': '10365063199', 'lat': '25.0092', 'lon': '121.5140', 'pm2_5': '3.60'}, {'deviceId': '10363938282', 'lat': '25.0114', 'lon': '121.5080', 'pm2_5': '2.09'}, {'deviceId': '10363771626', 'lat': '25.0092', 'lon': '121.5049', 'pm2_5': '1.46'}, {'deviceId': '10362311821', 'lat': '25.0049', 'lon': '121.4982', 'pm2_5': '3.35'}]
     center_lat = 25.011319
     center_lon = 121.506297
     image_path = 'scale_2.png'
```

### Comparing `enviRobot_scoop-0.1.3/enviRobot_scoop.egg-info/PKG-INFO` & `enviRobot_scoop-0.1.4/enviRobot_scoop.egg-info/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: enviRobot-scoop
-Version: 0.1.3
+Version: 0.1.4
 Summary: enviRobot service that can be held by Scoop.
 Home-page: https://github.com/bohachu/ask_enviRobot
 Author: JcXGTcW
 Author-email: jcxgtcw@cameo.tw
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `enviRobot_scoop-0.1.3/setup.py` & `enviRobot_scoop-0.1.4/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 # 若Discription.md中有中文 須加上 encoding="utf-8"
 with open("README.md", "r",encoding="utf-8") as f:
     long_description = f.read()
     
 setuptools.setup(
     name = "enviRobot_scoop",
-    version = "0.1.3",
+    version = "0.1.4",
     author = "JcXGTcW",
     author_email="jcxgtcw@cameo.tw",
     description="enviRobot service that can be held by Scoop.",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/bohachu/ask_enviRobot",
     packages=setuptools.find_packages(),
```


# Comparing `tmp/enviRobot_scoop-0.1.1.tar.gz` & `tmp/enviRobot_scoop-0.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "enviRobot_scoop-0.1.1.tar", last modified: Wed Jun  7 21:41:00 2023, max compression
+gzip compressed data, was "enviRobot_scoop-0.1.2.tar", last modified: Wed Jun 28 12:46:49 2023, max compression
```

## Comparing `enviRobot_scoop-0.1.1.tar` & `enviRobot_scoop-0.1.2.tar`

### file list

```diff
@@ -1,18 +1,19 @@
-drwxrwxrwx   0        0        0        0 2023-06-07 21:41:00.250644 enviRobot_scoop-0.1.1/
--rw-rw-rw-   0        0        0     1061 2023-06-07 20:47:04.000000 enviRobot_scoop-0.1.1/LICENSE
--rw-rw-rw-   0        0        0      835 2023-06-07 21:41:00.249643 enviRobot_scoop-0.1.1/PKG-INFO
--rw-rw-rw-   0        0        0      357 2023-06-07 21:32:41.000000 enviRobot_scoop-0.1.1/README.md
-drwxrwxrwx   0        0        0        0 2023-06-07 21:41:00.241644 enviRobot_scoop-0.1.1/enviRobot_scoop/
--rw-rw-rw-   0        0        0        0 2023-06-07 20:27:34.000000 enviRobot_scoop-0.1.1/enviRobot_scoop/__init__.py
--rw-rw-rw-   0        0        0     1111 2023-05-17 08:59:45.000000 enviRobot_scoop-0.1.1/enviRobot_scoop/aiot_screenshot.py
--rw-rw-rw-   0        0        0     3636 2023-06-07 21:18:05.000000 enviRobot_scoop-0.1.1/enviRobot_scoop/enviRobot_scoop.py
--rw-rw-rw-   0        0        0    15025 2023-06-07 21:09:27.000000 enviRobot_scoop-0.1.1/enviRobot_scoop/gpt.py
--rw-rw-rw-   0        0        0      419 2023-06-07 21:09:59.000000 enviRobot_scoop-0.1.1/enviRobot_scoop/upload_to_imgur.py
-drwxrwxrwx   0        0        0        0 2023-06-07 21:41:00.248644 enviRobot_scoop-0.1.1/enviRobot_scoop.egg-info/
--rw-rw-rw-   0        0        0      835 2023-06-07 21:41:00.000000 enviRobot_scoop-0.1.1/enviRobot_scoop.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      376 2023-06-07 21:41:00.000000 enviRobot_scoop-0.1.1/enviRobot_scoop.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-07 21:41:00.000000 enviRobot_scoop-0.1.1/enviRobot_scoop.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      176 2023-06-07 21:41:00.000000 enviRobot_scoop-0.1.1/enviRobot_scoop.egg-info/requires.txt
--rw-rw-rw-   0        0        0       16 2023-06-07 21:41:00.000000 enviRobot_scoop-0.1.1/enviRobot_scoop.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-07 21:41:00.250644 enviRobot_scoop-0.1.1/setup.cfg
--rw-rw-rw-   0        0        0     1022 2023-06-07 21:40:50.000000 enviRobot_scoop-0.1.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:46:49.369593 enviRobot_scoop-0.1.2/
+-rw-rw-rw-   0        0        0     1061 2023-06-07 20:47:04.000000 enviRobot_scoop-0.1.2/LICENSE
+-rw-rw-rw-   0        0        0      974 2023-06-28 12:46:49.368592 enviRobot_scoop-0.1.2/PKG-INFO
+-rw-rw-rw-   0        0        0      492 2023-06-19 10:47:30.000000 enviRobot_scoop-0.1.2/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 12:46:49.358593 enviRobot_scoop-0.1.2/enviRobot_scoop/
+-rw-rw-rw-   0        0        0        0 2023-06-07 20:27:34.000000 enviRobot_scoop-0.1.2/enviRobot_scoop/__init__.py
+-rw-rw-rw-   0        0        0     1111 2023-05-17 08:59:45.000000 enviRobot_scoop-0.1.2/enviRobot_scoop/aiot_screenshot.py
+-rw-rw-rw-   0        0        0     3597 2023-06-28 07:12:39.000000 enviRobot_scoop-0.1.2/enviRobot_scoop/enviRobot_scoop.py
+-rw-rw-rw-   0        0        0    15189 2023-06-28 12:19:09.000000 enviRobot_scoop-0.1.2/enviRobot_scoop/gpt.py
+-rw-rw-rw-   0        0        0     3879 2023-06-28 12:37:06.000000 enviRobot_scoop-0.1.2/enviRobot_scoop/plotly_screenshot.py
+-rw-rw-rw-   0        0        0      419 2023-06-07 21:09:59.000000 enviRobot_scoop-0.1.2/enviRobot_scoop/upload_to_imgur.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:46:49.368592 enviRobot_scoop-0.1.2/enviRobot_scoop.egg-info/
+-rw-rw-rw-   0        0        0      974 2023-06-28 12:46:49.000000 enviRobot_scoop-0.1.2/enviRobot_scoop.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      413 2023-06-28 12:46:49.000000 enviRobot_scoop-0.1.2/enviRobot_scoop.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 12:46:49.000000 enviRobot_scoop-0.1.2/enviRobot_scoop.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      206 2023-06-28 12:46:49.000000 enviRobot_scoop-0.1.2/enviRobot_scoop.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       16 2023-06-28 12:46:49.000000 enviRobot_scoop-0.1.2/enviRobot_scoop.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 12:46:49.369593 enviRobot_scoop-0.1.2/setup.cfg
+-rw-rw-rw-   0        0        0     1066 2023-06-28 12:45:19.000000 enviRobot_scoop-0.1.2/setup.py
```

### Comparing `enviRobot_scoop-0.1.1/LICENSE` & `enviRobot_scoop-0.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `enviRobot_scoop-0.1.1/enviRobot_scoop/aiot_screenshot.py` & `enviRobot_scoop-0.1.2/enviRobot_scoop/aiot_screenshot.py`

 * *Files identical despite different names*

### Comparing `enviRobot_scoop-0.1.1/enviRobot_scoop/enviRobot_scoop.py` & `enviRobot_scoop-0.1.2/enviRobot_scoop/enviRobot_scoop.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 import asyncio
 import json
-from enviRobot_scoop.upload_to_imgur import upload_to_imgur
-import enviRobot_scoop.gpt as gpt
+from upload_to_imgur import upload_to_imgur
+import gpt
 import random
 import string
 import os
 import re
 import sys
 import contextlib
```

### Comparing `enviRobot_scoop-0.1.1/enviRobot_scoop/gpt.py` & `enviRobot_scoop-0.1.2/enviRobot_scoop/gpt.py`

 * *Files 2% similar despite different names*

```diff
@@ -4,15 +4,17 @@
 import json
 import geocoder
 import os
 from dotenv import load_dotenv
 from geopy import Point
 from geopy.distance import distance, geodesic
 import requests
-from enviRobot_scoop.aiot_screenshot import aiot_screenshot
+from aiot_screenshot import aiot_screenshot
+from plotly_screenshot import save_fig
+import time
 
 # https://www.youtube.com/watch?v=I4T--ycOpi0&ab_channel=JieJenn
 
 load_dotenv(dotenv_path='./.env')
 
 def openai_init(key_path):
     openai.api_key = os.getenv('OPENAI_KEY')
@@ -87,30 +89,33 @@
         elif lang == 'EN':
             output = "An error occured while processing aiot rawdata"
     sensor_map_url = 'https://aiot.epa.gov.tw/web/iot/history/animation?'+\
             f'start={(date_now-dt.timedelta(minutes=15)).strftime("%Y-%m-%d %H:%M:%S")}&'+\
             f'end={(date_now+dt.timedelta(minutes=15)).strftime("%Y-%m-%d %H:%M:%S")}&'+\
             f'start_lat={bottom_right_lat:.4f}&end_lat={top_left_lat:.4f}&start_lon={top_left_lon:.4f}&end_lon={bottom_right_lon:.4f}'
     print('get_aiot_rawdata/take screenshot start', flush=True)
-    aiot_screenshot(sensor_map_url, f'./image/{image_name}.png')
+    #aiot_screenshot(sensor_map_url, f'./image/{image_name}.png')
+    save_fig(int_lat, int_lon, list_result, f'./image/{image_name}.png')
     print('get_aiot_rawdata/take screenshot finish', flush=True)
     if lang == 'EN':
         output += f"\n\nPM2.5 sensor map link: {sensor_map_url.replace(' ','%20')}"
     elif lang == 'CH':
         output += f"\n\nPM2.5 感測器地圖URL : {sensor_map_url.replace(' ','%20')}"
     # print('aiot api done', flush=True)
     return output
 
 def get_cwb_wind_data(int_lat, int_lon, str_datetime, lang='CH'):
     if lang not in ['EN', 'CH']:
         raise ValueError('supported language: CH, EN')
     event_loc = (int_lat, int_lon)
     event_time = dt.datetime.strptime(str_datetime, "%Y-%m-%d %H:%M:%S")
     # 後一個整點? API有問題, start_time要往後8小時
-    t = (event_time+dt.timedelta(hours=9, minutes=-event_time.minute, seconds=-event_time.second))
+    # 修好了
+    #t = (event_time+dt.timedelta(hours=9, minutes=-event_time.minute, seconds=-event_time.second))
+    t = (event_time+dt.timedelta(minutes=-event_time.minute, seconds=-event_time.second))
     str_result = "No CWB sensor data" if lang=="EN" else "無氣象局測站資料"
     for _ in range(3):
         start_time, end_time = t.strftime("%Y-%m-%d %H:%M:%S"), (t+dt.timedelta(hours=1)).strftime("%Y-%m-%d %H:%M:%S")
         t = t - dt.timedelta(hours=1)
         # print(int_lat, int_lon, str_datetime, str_five_minutes_ago, flush=True)
         cwb_api = f'https://aiot.epa.gov.tw/_/api/v2/epa_station/wind?fields=wind_direct%2Cwind_speed&sources=中央氣象局&min_lat=-90&max_lat=90&min_lon=-180&max_lon=180&start_time={start_time}&end_time={end_time}'
         # print(cwb_api, flush=True)
@@ -254,20 +259,20 @@
         content = '抱歉, 無法產生本次事件相關空氣品質報告, 或許您可以再試一次'
     else:
         content = response.choices[-1].message.content
     print('gpt_generate_report/done', flush=True)
     return content
 
 if __name__ == '__main__':
+
+    str_input = '永和仁愛公園剛剛發生大火'
     #str_input = '《環境污染事件通報》第031901號\n一、案由：反映雜草火警，已派七輛消防車前往，火勢面積很大。\n二、地點：龍井區龍興路玉府天宮附近，靠近高速公路\n三、通報來源：消防局\n四、日期：112年03月19日\n (一)報案16:01\n (二)到達:已通報前往'
-    #str_input = '永和仁愛公園剛剛發生大火'
     #str_input = '斷稜西山在2023-03-22 10:00:00有人登頂'
     #str_input = '國道五號37路段，五分鐘前看到露天燃燒'
     #str_input = '我上禮拜一下午五點走路經過中正紀念堂看到那邊有黑煙'
-    str_input = '卡米爾有限公司正在開會'
     import time
     t = time.time()
     result = eco_ask_3w_handler(str_input, image_name='aaa')
     print(result, flush=True)
     print('', flush=True)
     gpt_generate_report(result)
     print(f'used {time.time()-t:.2f} seconds', flush=True)
```

### Comparing `enviRobot_scoop-0.1.1/setup.py` & `enviRobot_scoop-0.1.2/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 # 若Discription.md中有中文 須加上 encoding="utf-8"
 with open("README.md", "r",encoding="utf-8") as f:
     long_description = f.read()
     
 setuptools.setup(
     name = "enviRobot_scoop",
-    version = "0.1.1",
+    version = "0.1.2",
     author = "JcXGTcW",
     author_email="jcxgtcw@cameo.tw",
     description="enviRobot service that can be held by Scoop.",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/bohachu/ask_enviRobot",
     packages=setuptools.find_packages(),
@@ -26,9 +26,11 @@
     'geocoder==1.38.1',
     'line-bot-sdk==2.4.2',
     'pandas==1.5.3',
     'geopy==2.3.0',
     'selenium==4.7.2',
     'pyimgur==0.6.0',
     'pyyaml==6.0',
-    'python-dotenv==0.15.0']
+    'python-dotenv==0.15.0',
+    "plotly==5.15.0",
+    "kaleido==0.2.1"]
     )
```


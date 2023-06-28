# Comparing `tmp/JarvisAI-4.8.tar.gz` & `tmp/JarvisAI-4.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "JarvisAI-4.8.tar", last modified: Sat Apr 15 05:39:49 2023, max compression
+gzip compressed data, was "JarvisAI-4.9.tar", last modified: Wed Jun 28 03:44:43 2023, max compression
```

## Comparing `JarvisAI-4.8.tar` & `JarvisAI-4.9.tar`

### file list

```diff
@@ -1,53 +1,53 @@
-drwxrwxrwx   0        0        0        0 2023-04-15 05:39:49.202029 JarvisAI-4.8/
-drwxrwxrwx   0        0        0        0 2023-04-15 05:39:49.165558 JarvisAI-4.8/JarvisAI/
--rw-rw-rw-   0        0        0    12349 2023-04-15 04:47:12.000000 JarvisAI-4.8/JarvisAI/__init__.py
-drwxrwxrwx   0        0        0        0 2023-04-15 05:39:49.186798 JarvisAI-4.8/JarvisAI/brain/
--rw-rw-rw-   0        0        0        0 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/brain/__init__.py
--rw-rw-rw-   0        0        0      931 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/brain/auth.py
--rw-rw-rw-   0        0        0     3762 2023-04-15 04:52:26.000000 JarvisAI-4.8/JarvisAI/brain/chatbot_premium.py
--rw-rw-rw-   0        0        0     2304 2023-04-15 05:00:05.000000 JarvisAI-4.8/JarvisAI/brain/intent_classification.py
--rw-rw-rw-   0        0        0      919 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/brain/ner.py
-drwxrwxrwx   0        0        0        0 2023-04-15 05:39:49.196935 JarvisAI-4.8/JarvisAI/features/
--rw-rw-rw-   0        0        0        0 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/__init__.py
--rw-rw-rw-   0        0        0     1135 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/click_photo.py
--rw-rw-rw-   0        0        0     1280 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/covid_cases.py
--rw-rw-rw-   0        0        0      333 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/date_time.py
--rw-rw-rw-   0        0        0      363 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/games.py
--rw-rw-rw-   0        0        0      310 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/greet.py
--rw-rw-rw-   0        0        0      186 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/iambored.py
--rw-rw-rw-   0        0        0     1068 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/internet_speed_test.py
--rw-rw-rw-   0        0        0      364 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/joke.py
--rw-rw-rw-   0        0        0      867 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/news.py
--rw-rw-rw-   0        0        0      333 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/places_near_me.py
--rw-rw-rw-   0        0        0      625 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/screenshot.py
--rw-rw-rw-   0        0        0      895 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/send_email.py
--rw-rw-rw-   0        0        0     1620 2023-04-15 05:30:29.000000 JarvisAI-4.8/JarvisAI/features/tell_me_about.py
--rw-rw-rw-   0        0        0     3923 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/volume_controller.py
--rw-rw-rw-   0        0        0      983 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/weather.py
--rw-rw-rw-   0        0        0      535 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/website_open.py
--rw-rw-rw-   0        0        0      449 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/whatsapp_message.py
--rw-rw-rw-   0        0        0      245 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/youtube_play.py
--rw-rw-rw-   0        0        0      492 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features/youtube_video_downloader.py
--rw-rw-rw-   0        0        0     3215 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/features_manager.py
-drwxrwxrwx   0        0        0        0 2023-04-15 05:39:49.197936 JarvisAI-4.8/JarvisAI/utils/
--rw-rw-rw-   0        0        0        0 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/utils/__init__.py
--rw-rw-rw-   0        0        0     3670 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/utils/input_output.py
-drwxrwxrwx   0        0        0        0 2023-04-15 05:39:49.198936 JarvisAI-4.8/JarvisAI/utils/speech_to_text/
--rw-rw-rw-   0        0        0        0 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/utils/speech_to_text/__init__.py
--rw-rw-rw-   0        0        0     2277 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/utils/speech_to_text/speech_to_text.py
--rw-rw-rw-   0        0        0      715 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/utils/speech_to_text/speech_to_text_whisper.py
-drwxrwxrwx   0        0        0        0 2023-04-15 05:39:49.199936 JarvisAI-4.8/JarvisAI/utils/text_to_speech/
--rw-rw-rw-   0        0        0        0 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/utils/text_to_speech/__init__.py
--rw-rw-rw-   0        0        0     3268 2023-04-03 21:49:40.000000 JarvisAI-4.8/JarvisAI/utils/text_to_speech/text_to_speech.py
-drwxrwxrwx   0        0        0        0 2023-04-15 05:39:49.184807 JarvisAI-4.8/JarvisAI.egg-info/
--rw-rw-rw-   0        0        0    12669 2023-04-15 05:39:49.000000 JarvisAI-4.8/JarvisAI.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     1350 2023-04-15 05:39:49.000000 JarvisAI-4.8/JarvisAI.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-04-15 05:39:49.000000 JarvisAI-4.8/JarvisAI.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      354 2023-04-15 05:39:49.000000 JarvisAI-4.8/JarvisAI.egg-info/requires.txt
--rw-rw-rw-   0        0        0        9 2023-04-15 05:39:49.000000 JarvisAI-4.8/JarvisAI.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     1091 2023-04-03 21:49:40.000000 JarvisAI-4.8/License.txt
--rw-rw-rw-   0        0        0       45 2023-04-03 21:49:40.000000 JarvisAI-4.8/MANIFEST.in
--rw-rw-rw-   0        0        0    12669 2023-04-15 05:39:49.201034 JarvisAI-4.8/PKG-INFO
--rw-rw-rw-   0        0        0    11757 2023-04-15 05:39:46.000000 JarvisAI-4.8/README.md
--rw-rw-rw-   0        0        0       42 2023-04-15 05:39:49.202029 JarvisAI-4.8/setup.cfg
--rw-rw-rw-   0        0        0     1856 2023-04-14 13:00:28.000000 JarvisAI-4.8/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:44:43.393633 JarvisAI-4.9/
+drwxrwxrwx   0        0        0        0 2023-06-28 03:44:43.275577 JarvisAI-4.9/JarvisAI/
+-rw-rw-rw-   0        0        0    12349 2023-04-15 04:47:12.000000 JarvisAI-4.9/JarvisAI/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:44:43.317400 JarvisAI-4.9/JarvisAI/brain/
+-rw-rw-rw-   0        0        0        0 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/brain/__init__.py
+-rw-rw-rw-   0        0        0      931 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/brain/auth.py
+-rw-rw-rw-   0        0        0     3762 2023-04-15 04:52:26.000000 JarvisAI-4.9/JarvisAI/brain/chatbot_premium.py
+-rw-rw-rw-   0        0        0     3309 2023-06-28 03:41:01.000000 JarvisAI-4.9/JarvisAI/brain/intent_classification.py
+-rw-rw-rw-   0        0        0      919 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/brain/ner.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:44:43.382720 JarvisAI-4.9/JarvisAI/features/
+-rw-rw-rw-   0        0        0        0 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/__init__.py
+-rw-rw-rw-   0        0        0     1135 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/click_photo.py
+-rw-rw-rw-   0        0        0     1280 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/covid_cases.py
+-rw-rw-rw-   0        0        0      333 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/date_time.py
+-rw-rw-rw-   0        0        0      363 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/games.py
+-rw-rw-rw-   0        0        0      310 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/greet.py
+-rw-rw-rw-   0        0        0      186 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/iambored.py
+-rw-rw-rw-   0        0        0     1068 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/internet_speed_test.py
+-rw-rw-rw-   0        0        0      364 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/joke.py
+-rw-rw-rw-   0        0        0      867 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/news.py
+-rw-rw-rw-   0        0        0      333 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/places_near_me.py
+-rw-rw-rw-   0        0        0      625 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/screenshot.py
+-rw-rw-rw-   0        0        0      895 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/send_email.py
+-rw-rw-rw-   0        0        0     1620 2023-04-15 05:30:29.000000 JarvisAI-4.9/JarvisAI/features/tell_me_about.py
+-rw-rw-rw-   0        0        0     3923 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/volume_controller.py
+-rw-rw-rw-   0        0        0      983 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/weather.py
+-rw-rw-rw-   0        0        0      535 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/website_open.py
+-rw-rw-rw-   0        0        0      449 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/whatsapp_message.py
+-rw-rw-rw-   0        0        0      245 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/youtube_play.py
+-rw-rw-rw-   0        0        0      492 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features/youtube_video_downloader.py
+-rw-rw-rw-   0        0        0     3215 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/features_manager.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:44:43.385644 JarvisAI-4.9/JarvisAI/utils/
+-rw-rw-rw-   0        0        0        0 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/utils/__init__.py
+-rw-rw-rw-   0        0        0     3670 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/utils/input_output.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:44:43.388635 JarvisAI-4.9/JarvisAI/utils/speech_to_text/
+-rw-rw-rw-   0        0        0        0 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/utils/speech_to_text/__init__.py
+-rw-rw-rw-   0        0        0     2277 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/utils/speech_to_text/speech_to_text.py
+-rw-rw-rw-   0        0        0      715 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/utils/speech_to_text/speech_to_text_whisper.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:44:43.389631 JarvisAI-4.9/JarvisAI/utils/text_to_speech/
+-rw-rw-rw-   0        0        0        0 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/utils/text_to_speech/__init__.py
+-rw-rw-rw-   0        0        0     3268 2023-04-03 21:49:40.000000 JarvisAI-4.9/JarvisAI/utils/text_to_speech/text_to_speech.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:44:43.311441 JarvisAI-4.9/JarvisAI.egg-info/
+-rw-rw-rw-   0        0        0    12669 2023-06-28 03:44:43.000000 JarvisAI-4.9/JarvisAI.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     1350 2023-06-28 03:44:43.000000 JarvisAI-4.9/JarvisAI.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 03:44:43.000000 JarvisAI-4.9/JarvisAI.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      392 2023-06-28 03:44:43.000000 JarvisAI-4.9/JarvisAI.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        9 2023-06-28 03:44:43.000000 JarvisAI-4.9/JarvisAI.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     1091 2023-04-03 21:49:40.000000 JarvisAI-4.9/License.txt
+-rw-rw-rw-   0        0        0       45 2023-04-03 21:49:40.000000 JarvisAI-4.9/MANIFEST.in
+-rw-rw-rw-   0        0        0    12669 2023-06-28 03:44:43.392622 JarvisAI-4.9/PKG-INFO
+-rw-rw-rw-   0        0        0    11757 2023-04-15 05:39:46.000000 JarvisAI-4.9/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 03:44:43.393633 JarvisAI-4.9/setup.cfg
+-rw-rw-rw-   0        0        0     1926 2023-06-28 03:44:35.000000 JarvisAI-4.9/setup.py
```

### Comparing `JarvisAI-4.8/JarvisAI/__init__.py` & `JarvisAI-4.9/JarvisAI/__init__.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/brain/auth.py` & `JarvisAI-4.9/JarvisAI/brain/auth.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/brain/chatbot_premium.py` & `JarvisAI-4.9/JarvisAI/brain/chatbot_premium.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/brain/ner.py` & `JarvisAI-4.9/JarvisAI/brain/ner.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/features/click_photo.py` & `JarvisAI-4.9/JarvisAI/features/click_photo.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/features/covid_cases.py` & `JarvisAI-4.9/JarvisAI/features/covid_cases.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/features/internet_speed_test.py` & `JarvisAI-4.9/JarvisAI/features/internet_speed_test.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/features/news.py` & `JarvisAI-4.9/JarvisAI/features/news.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/features/screenshot.py` & `JarvisAI-4.9/JarvisAI/features/screenshot.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/features/send_email.py` & `JarvisAI-4.9/JarvisAI/features/send_email.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/features/tell_me_about.py` & `JarvisAI-4.9/JarvisAI/features/tell_me_about.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/features/volume_controller.py` & `JarvisAI-4.9/JarvisAI/features/volume_controller.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/features/weather.py` & `JarvisAI-4.9/JarvisAI/features/weather.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/features/website_open.py` & `JarvisAI-4.9/JarvisAI/features/website_open.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/features_manager.py` & `JarvisAI-4.9/JarvisAI/features_manager.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/utils/input_output.py` & `JarvisAI-4.9/JarvisAI/utils/input_output.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/utils/speech_to_text/speech_to_text.py` & `JarvisAI-4.9/JarvisAI/utils/speech_to_text/speech_to_text.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/utils/speech_to_text/speech_to_text_whisper.py` & `JarvisAI-4.9/JarvisAI/utils/speech_to_text/speech_to_text_whisper.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI/utils/text_to_speech/text_to_speech.py` & `JarvisAI-4.9/JarvisAI/utils/text_to_speech/text_to_speech.py`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/JarvisAI.egg-info/PKG-INFO` & `JarvisAI-4.9/JarvisAI.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: JarvisAI
-Version: 4.8
+Version: 4.9
 Summary: JarvisAI is python library to build your own AI virtual assistant with natural language processing.
 Home-page: https://github.com/Dipeshpal/Jarvis_AI
 Author: Dipesh
 Author-email: dipeshpal17@gmail.com
 License: UNKNOWN
 Project-URL: Official Website, https://jarvisai.in
 Project-URL: Documentation, https://github.com/Dipeshpal/Jarvis_AI
```

### Comparing `JarvisAI-4.8/JarvisAI.egg-info/SOURCES.txt` & `JarvisAI-4.9/JarvisAI.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/License.txt` & `JarvisAI-4.9/License.txt`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/PKG-INFO` & `JarvisAI-4.9/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: JarvisAI
-Version: 4.8
+Version: 4.9
 Summary: JarvisAI is python library to build your own AI virtual assistant with natural language processing.
 Home-page: https://github.com/Dipeshpal/Jarvis_AI
 Author: Dipesh
 Author-email: dipeshpal17@gmail.com
 License: UNKNOWN
 Project-URL: Official Website, https://jarvisai.in
 Project-URL: Documentation, https://github.com/Dipeshpal/Jarvis_AI
```

### Comparing `JarvisAI-4.8/README.md` & `JarvisAI-4.9/README.md`

 * *Files identical despite different names*

### Comparing `JarvisAI-4.8/setup.py` & `JarvisAI-4.9/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -2,30 +2,31 @@
 from setuptools import find_namespace_packages
 
 with open("README.md", "r", encoding='utf-8') as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="JarvisAI",
-    version="4.8",
+    version="4.9",
     author="Dipesh",
     author_email="dipeshpal17@gmail.com",
     description="JarvisAI is python library to build your own AI virtual assistant with natural language processing.",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/Dipeshpal/Jarvis_AI",
     include_package_data=True,
     packages=find_namespace_packages(include=['JarvisAI.*', 'JarvisAI']),
     install_requires=['numpy', 'gtts', 'playsound', 'pyscreenshot', "opencv-python",
                       'SpeechRecognition', 'pyjokes', 'wikipedia', 'scipy', 'lazyme',
                       "requests", "pyttsx3", "spacy==3.5.0", 'pywhatkit', 'speedtest-cli',
                       'pytube', 'pycountry', 'playsound', 'pyaudio', 'mediapipe==0.8.11',
                       'pycaw', 'openai-whisper', 'shutup', 'sounddevice', 'html2text==2020.1.16',
                       'wikipedia==1.4.0', 'Markdown==3.4.1', 'markdown2==2.4.8',
-                      'lxml==4.9.2', 'googlesearch-python==1.2.3'],
+                      'lxml==4.9.2', 'googlesearch-python==1.2.3', 'selenium', 'selenium-pro',
+                      'element-manager'],
     classifiers=[
         "Programming Language :: Python :: 3",
         "License :: OSI Approved :: MIT License",
         "Operating System :: OS Independent",
     ],
     python_requires='>=3.6',
     project_urls={
```


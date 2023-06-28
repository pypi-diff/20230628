# Comparing `tmp/detect_hate_speech-0.1.1.tar.gz` & `tmp/detect_hate_speech-0.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "detect_hate_speech-0.1.1.tar", max compression
+gzip compressed data, was "detect_hate_speech-0.1.2.tar", max compression
```

## Comparing `detect_hate_speech-0.1.1.tar` & `detect_hate_speech-0.1.2.tar`

### file list

```diff
@@ -1,6 +1,6 @@
--rw-r--r--   0        0        0     1068 2023-06-28 03:02:23.524734 detect_hate_speech-0.1.1/LICENSE
--rw-r--r--   0        0        0     3958 2023-06-28 03:02:23.524734 detect_hate_speech-0.1.1/README.md
--rw-r--r--   0        0        0      836 2023-06-28 03:02:23.571734 detect_hate_speech-0.1.1/detect_hate_speech/main.py
--rw-r--r--   0        0        0     5042 2023-06-28 03:02:23.571734 detect_hate_speech-0.1.1/detect_hate_speech/utils.py
--rw-r--r--   0        0        0      332 2023-06-28 03:02:36.216597 detect_hate_speech-0.1.1/pyproject.toml
--rw-r--r--   0        0        0     4458 1970-01-01 00:00:00.000000 detect_hate_speech-0.1.1/PKG-INFO
+-rw-r--r--   0        0        0     1068 2023-06-28 03:31:49.834747 detect_hate_speech-0.1.2/LICENSE
+-rw-r--r--   0        0        0     3958 2023-06-28 03:31:49.834747 detect_hate_speech-0.1.2/README.md
+-rw-r--r--   0        0        0      836 2023-06-28 03:31:49.880748 detect_hate_speech-0.1.2/detect_hate_speech/main.py
+-rw-r--r--   0        0        0     5042 2023-06-28 03:31:49.880748 detect_hate_speech-0.1.2/detect_hate_speech/utils.py
+-rw-r--r--   0        0        0      332 2023-06-28 03:32:02.030938 detect_hate_speech-0.1.2/pyproject.toml
+-rw-r--r--   0        0        0     4458 1970-01-01 00:00:00.000000 detect_hate_speech-0.1.2/PKG-INFO
```

### Comparing `detect_hate_speech-0.1.1/LICENSE` & `detect_hate_speech-0.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `detect_hate_speech-0.1.1/README.md` & `detect_hate_speech-0.1.2/README.md`

 * *Files identical despite different names*

### Comparing `detect_hate_speech-0.1.1/detect_hate_speech/main.py` & `detect_hate_speech-0.1.2/detect_hate_speech/main.py`

 * *Files identical despite different names*

### Comparing `detect_hate_speech-0.1.1/detect_hate_speech/utils.py` & `detect_hate_speech-0.1.2/detect_hate_speech/utils.py`

 * *Files identical despite different names*

### Comparing `detect_hate_speech-0.1.1/PKG-INFO` & `detect_hate_speech-0.1.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: detect-hate-speech
-Version: 0.1.1
+Version: 0.1.2
 Summary: 
 Author: Amanda Nobre
 Author-email: amandapnobre@gmail.com
 Requires-Python: >=3.7,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
```


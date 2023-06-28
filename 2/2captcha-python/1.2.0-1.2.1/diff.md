# Comparing `tmp/2captcha-python-1.2.0.tar.gz` & `tmp/2captcha-python-1.2.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "2captcha-python-1.2.0.tar", last modified: Wed Mar  1 17:37:50 2023, max compression
+gzip compressed data, was "2captcha-python-1.2.1.tar", last modified: Wed Jun 28 15:01:08 2023, max compression
```

## Comparing `2captcha-python-1.2.0.tar` & `2captcha-python-1.2.1.tar`

### file list

```diff
@@ -1,33 +1,33 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-01 17:37:50.956490 2captcha-python-1.2.0/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-01 17:37:50.952489 2captcha-python-1.2.0/2captcha_python.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13725 2023-03-01 17:37:50.000000 2captcha-python-1.2.0/2captcha_python.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      641 2023-03-01 17:37:50.000000 2captcha-python-1.2.0/2captcha_python.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-01 17:37:50.000000 2captcha-python-1.2.0/2captcha_python.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-03-01 17:37:50.000000 2captcha-python-1.2.0/2captcha_python.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       11 2023-03-01 17:37:50.000000 2captcha-python-1.2.0/2captcha_python.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     1065 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13725 2023-03-01 17:37:50.956490 2captcha-python-1.2.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13267 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-01 17:37:50.956490 2captcha-python-1.2.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      986 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-01 17:37:50.956490 2captcha-python-1.2.0/tests/
--rwxr-xr-x   0 runner    (1001) docker     (123)     2634 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_amazon_waf.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1774 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_canvas.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      720 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_capy.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1630 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_coordinates.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1329 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_funcaptcha.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1034 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_geetest.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      758 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_geetest_v4.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1892 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_grid.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      727 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_hcaptcha.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1254 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_keycaptcha.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      985 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_lemin.py
--rw-r--r--   0 runner    (1001) docker     (123)     2205 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_normal.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1882 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_recaptcha.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     2164 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_rotate.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      835 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_text.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      847 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/tests/test_turnstile.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-01 17:37:50.956490 2captcha-python-1.2.0/twocaptcha/
--rw-r--r--   0 runner    (1001) docker     (123)      193 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/twocaptcha/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2763 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/twocaptcha/api.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    16656 2023-03-01 17:37:41.000000 2captcha-python-1.2.0/twocaptcha/solver.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:08.912310 2captcha-python-1.2.1/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:08.908310 2captcha-python-1.2.1/2captcha_python.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13725 2023-06-28 15:01:08.000000 2captcha-python-1.2.1/2captcha_python.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      641 2023-06-28 15:01:08.000000 2captcha-python-1.2.1/2captcha_python.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:01:08.000000 2captcha-python-1.2.1/2captcha_python.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 15:01:08.000000 2captcha-python-1.2.1/2captcha_python.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       11 2023-06-28 15:01:08.000000 2captcha-python-1.2.1/2captcha_python.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     1065 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13725 2023-06-28 15:01:08.912310 2captcha-python-1.2.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13267 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:01:08.912310 2captcha-python-1.2.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      986 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:08.912310 2captcha-python-1.2.1/tests/
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2634 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_amazon_waf.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1774 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_canvas.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      720 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_capy.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1630 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_coordinates.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1329 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_funcaptcha.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1034 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_geetest.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      758 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_geetest_v4.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1892 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_grid.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      727 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_hcaptcha.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1254 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_keycaptcha.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      985 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_lemin.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2205 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_normal.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1882 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_recaptcha.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2164 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_rotate.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      835 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_text.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      847 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/tests/test_turnstile.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:08.912310 2captcha-python-1.2.1/twocaptcha/
+-rw-r--r--   0 runner    (1001) docker     (123)      193 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/twocaptcha/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2763 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/twocaptcha/api.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    16728 2023-06-28 15:00:53.000000 2captcha-python-1.2.1/twocaptcha/solver.py
```

### Comparing `2captcha-python-1.2.0/2captcha_python.egg-info/PKG-INFO` & `2captcha-python-1.2.1/2captcha_python.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: 2captcha-python
-Version: 1.2.0
+Version: 1.2.1
 Summary: Python module for easy integration with 2Captcha API
 Home-page: https://github.com/2captcha/2captcha-python/
 Author: 2Captcha
 Author-email: info@2captcha.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
@@ -94,16 +94,16 @@
 ## Solve captcha
 When you submit any image-based captcha use can provide additional options to help 2captcha workers to solve it properly.
 
 ### Captcha options
 | Option        | Default Value | Description                                                                                        |
 | ------------- | ------------- | -------------------------------------------------------------------------------------------------- |
 | numeric       | 0             | Defines if captcha contains numeric or other symbols [see more info in the API docs][post options] |
-| minLength     | 0             | minimal answer lenght                                                                              |
-| maxLength     | 0             | maximum answer length                                                                              |
+| minLen        | 0             | minimal answer lenght                                                                              |
+| maxLen        | 0             | maximum answer length                                                                              |
 | phrase        | 0             | defines if the answer contains multiple words or not                                               |
 | caseSensitive | 0             | defines if the answer is case sensitive                                                            |
 | calc          | 0             | defines captcha requires calculation                                                               |
 | lang          | -             | defines the captcha language, see the [list of supported languages]                                |
 | hintImg       | -             | an image with hint shown to workers with the captcha                                               |
 | hintText      | -             | hint or task text shown to workers with the captcha                                                |
```

### Comparing `2captcha-python-1.2.0/2captcha_python.egg-info/SOURCES.txt` & `2captcha-python-1.2.1/2captcha_python.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/LICENSE` & `2captcha-python-1.2.1/LICENSE`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/PKG-INFO` & `2captcha-python-1.2.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: 2captcha-python
-Version: 1.2.0
+Version: 1.2.1
 Summary: Python module for easy integration with 2Captcha API
 Home-page: https://github.com/2captcha/2captcha-python/
 Author: 2Captcha
 Author-email: info@2captcha.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
@@ -94,16 +94,16 @@
 ## Solve captcha
 When you submit any image-based captcha use can provide additional options to help 2captcha workers to solve it properly.
 
 ### Captcha options
 | Option        | Default Value | Description                                                                                        |
 | ------------- | ------------- | -------------------------------------------------------------------------------------------------- |
 | numeric       | 0             | Defines if captcha contains numeric or other symbols [see more info in the API docs][post options] |
-| minLength     | 0             | minimal answer lenght                                                                              |
-| maxLength     | 0             | maximum answer length                                                                              |
+| minLen        | 0             | minimal answer lenght                                                                              |
+| maxLen        | 0             | maximum answer length                                                                              |
 | phrase        | 0             | defines if the answer contains multiple words or not                                               |
 | caseSensitive | 0             | defines if the answer is case sensitive                                                            |
 | calc          | 0             | defines captcha requires calculation                                                               |
 | lang          | -             | defines the captcha language, see the [list of supported languages]                                |
 | hintImg       | -             | an image with hint shown to workers with the captcha                                               |
 | hintText      | -             | hint or task text shown to workers with the captcha                                                |
```

### Comparing `2captcha-python-1.2.0/README.md` & `2captcha-python-1.2.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -80,16 +80,16 @@
 ## Solve captcha
 When you submit any image-based captcha use can provide additional options to help 2captcha workers to solve it properly.
 
 ### Captcha options
 | Option        | Default Value | Description                                                                                        |
 | ------------- | ------------- | -------------------------------------------------------------------------------------------------- |
 | numeric       | 0             | Defines if captcha contains numeric or other symbols [see more info in the API docs][post options] |
-| minLength     | 0             | minimal answer lenght                                                                              |
-| maxLength     | 0             | maximum answer length                                                                              |
+| minLen        | 0             | minimal answer lenght                                                                              |
+| maxLen        | 0             | maximum answer length                                                                              |
 | phrase        | 0             | defines if the answer contains multiple words or not                                               |
 | caseSensitive | 0             | defines if the answer is case sensitive                                                            |
 | calc          | 0             | defines captcha requires calculation                                                               |
 | lang          | -             | defines the captcha language, see the [list of supported languages]                                |
 | hintImg       | -             | an image with hint shown to workers with the captcha                                               |
 | hintText      | -             | hint or task text shown to workers with the captcha                                                |
```

### Comparing `2captcha-python-1.2.0/setup.py` & `2captcha-python-1.2.1/setup.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_amazon_waf.py` & `2captcha-python-1.2.1/tests/test_amazon_waf.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_canvas.py` & `2captcha-python-1.2.1/tests/test_canvas.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_capy.py` & `2captcha-python-1.2.1/tests/test_capy.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_coordinates.py` & `2captcha-python-1.2.1/tests/test_coordinates.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_funcaptcha.py` & `2captcha-python-1.2.1/tests/test_funcaptcha.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_geetest.py` & `2captcha-python-1.2.1/tests/test_geetest.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_geetest_v4.py` & `2captcha-python-1.2.1/tests/test_geetest_v4.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_grid.py` & `2captcha-python-1.2.1/tests/test_grid.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_hcaptcha.py` & `2captcha-python-1.2.1/tests/test_hcaptcha.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_keycaptcha.py` & `2captcha-python-1.2.1/tests/test_keycaptcha.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_lemin.py` & `2captcha-python-1.2.1/tests/test_lemin.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_normal.py` & `2captcha-python-1.2.1/tests/test_normal.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_recaptcha.py` & `2captcha-python-1.2.1/tests/test_recaptcha.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_rotate.py` & `2captcha-python-1.2.1/tests/test_rotate.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_text.py` & `2captcha-python-1.2.1/tests/test_text.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/tests/test_turnstile.py` & `2captcha-python-1.2.1/tests/test_turnstile.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/twocaptcha/api.py` & `2captcha-python-1.2.1/twocaptcha/api.py`

 * *Files identical despite different names*

### Comparing `2captcha-python-1.2.0/twocaptcha/solver.py` & `2captcha-python-1.2.1/twocaptcha/solver.py`

 * *Files 1% similar despite different names*

```diff
@@ -597,14 +597,16 @@
 
     def rename_params(self, params):
 
         replace = {
             'caseSensitive': 'regsense',
             'minLen': 'min_len',
             'maxLen': 'max_len',
+            'minLength': 'min_len',
+            'maxLength': 'max_len',
             'hintText': 'textinstructions',
             'hintImg': 'imginstructions',
             'url': 'pageurl',
             'score': 'min_score',
             'text': 'textcaptcha',
             'rows': 'recaptcharows',
             'cols': 'recaptchacols',
```


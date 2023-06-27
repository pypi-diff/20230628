# Comparing `tmp/google_translate_django4-0.3.tar.gz` & `tmp/google_translate_django4-0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "google_translate_django4-0.3.tar", last modified: Sat Jul  2 17:52:04 2022, max compression
+gzip compressed data, was "google_translate_django4-0.4.tar", last modified: Tue Jun 27 22:12:28 2023, max compression
```

## Comparing `google_translate_django4-0.3.tar` & `google_translate_django4-0.4.tar`

### file list

```diff
@@ -1,19 +1,20 @@
-drwxrwxrwx   0        0        0        0 2022-07-02 17:52:04.571136 google_translate_django4-0.3/
--rw-rw-rw-   0        0        0     1077 2022-07-02 00:36:12.000000 google_translate_django4-0.3/LICENSE.txt
--rw-rw-rw-   0        0        0     2115 2022-07-02 17:52:04.571136 google_translate_django4-0.3/PKG-INFO
--rw-rw-rw-   0        0        0     1018 2022-07-02 17:48:37.000000 google_translate_django4-0.3/README.md
-drwxrwxrwx   0        0        0        0 2022-07-02 17:52:04.555511 google_translate_django4-0.3/google_translate_django4/
--rw-rw-rw-   0        0        0        0 2020-06-26 15:01:53.000000 google_translate_django4-0.3/google_translate_django4/__init__.py
--rw-rw-rw-   0        0        0       66 2020-06-26 15:01:52.000000 google_translate_django4-0.3/google_translate_django4/admin.py
--rw-rw-rw-   0        0        0      117 2022-06-30 23:39:47.000000 google_translate_django4-0.3/google_translate_django4/apps.py
--rw-rw-rw-   0        0        0       60 2020-06-26 15:01:53.000000 google_translate_django4-0.3/google_translate_django4/models.py
--rw-rw-rw-   0        0        0       63 2020-06-26 15:01:53.000000 google_translate_django4-0.3/google_translate_django4/tests.py
--rw-rw-rw-   0        0        0       66 2020-06-26 15:01:53.000000 google_translate_django4-0.3/google_translate_django4/views.py
-drwxrwxrwx   0        0        0        0 2022-07-02 17:52:04.571136 google_translate_django4-0.3/google_translate_django4.egg-info/
--rw-rw-rw-   0        0        0     2115 2022-07-02 17:52:03.000000 google_translate_django4-0.3/google_translate_django4.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      486 2022-07-02 17:52:04.000000 google_translate_django4-0.3/google_translate_django4.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2022-07-02 17:52:03.000000 google_translate_django4-0.3/google_translate_django4.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        7 2022-07-02 17:52:04.000000 google_translate_django4-0.3/google_translate_django4.egg-info/requires.txt
--rw-rw-rw-   0        0        0       25 2022-07-02 17:52:04.000000 google_translate_django4-0.3/google_translate_django4.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      139 2022-07-02 17:52:04.586764 google_translate_django4-0.3/setup.cfg
--rw-rw-rw-   0        0        0     2139 2022-07-02 17:51:18.000000 google_translate_django4-0.3/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-27 22:12:28.789379 google_translate_django4-0.4/
+-rw-rw-rw-   0        0        0     1077 1970-01-01 00:00:00.000000 google_translate_django4-0.4/LICENSE.txt
+-rw-rw-rw-   0        0        0     2115 2023-06-27 22:12:28.789379 google_translate_django4-0.4/PKG-INFO
+-rw-rw-rw-   0        0        0     1018 1970-01-01 00:00:00.000000 google_translate_django4-0.4/README.md
+drwxrwxrwx   0        0        0        0 2023-06-27 22:12:28.772377 google_translate_django4-0.4/google_translate_django4/
+-rw-rw-rw-   0        0        0        0 1970-01-01 00:00:00.000000 google_translate_django4-0.4/google_translate_django4/__init__.py
+-rw-rw-rw-   0        0        0       66 1970-01-01 00:00:00.000000 google_translate_django4-0.4/google_translate_django4/admin.py
+-rw-rw-rw-   0        0        0      124 2023-06-27 22:04:46.000000 google_translate_django4-0.4/google_translate_django4/apps.py
+-rw-rw-rw-   0        0        0       60 1970-01-01 00:00:00.000000 google_translate_django4-0.4/google_translate_django4/models.py
+-rw-rw-rw-   0        0        0       63 1970-01-01 00:00:00.000000 google_translate_django4-0.4/google_translate_django4/tests.py
+-rw-rw-rw-   0        0        0       66 1970-01-01 00:00:00.000000 google_translate_django4-0.4/google_translate_django4/views.py
+drwxrwxrwx   0        0        0        0 2023-06-27 22:12:28.788382 google_translate_django4-0.4/google_translate_django4.egg-info/
+-rw-rw-rw-   0        0        0     2115 2023-06-27 22:12:28.000000 google_translate_django4-0.4/google_translate_django4.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      501 2023-06-27 22:12:28.000000 google_translate_django4-0.4/google_translate_django4.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-27 22:12:28.000000 google_translate_django4-0.4/google_translate_django4.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        7 2023-06-27 22:12:28.000000 google_translate_django4-0.4/google_translate_django4.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       25 2023-06-27 22:12:28.000000 google_translate_django4-0.4/google_translate_django4.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       97 2023-06-27 22:12:04.000000 google_translate_django4-0.4/pyproject.toml
+-rw-rw-rw-   0        0        0      139 2023-06-27 22:12:28.791392 google_translate_django4-0.4/setup.cfg
+-rw-rw-rw-   0        0        0     2139 2023-06-27 22:05:42.000000 google_translate_django4-0.4/setup.py
```

### Comparing `google_translate_django4-0.3/LICENSE.txt` & `google_translate_django4-0.4/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `google_translate_django4-0.3/PKG-INFO` & `google_translate_django4-0.4/google_translate_django4.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: google_translate_django4
-Version: 0.3
+Name: google-translate-django4
+Version: 0.4
 Summary: The working google translate module for Django version 4 and above
 Home-page: https://github.com/webprice/google_translate_django4
 Download-URL: https://github.com/webprice/google_translate_django4/archive/refs/tags/v_0.3.tar.gz
 Author: Serhii Hrekov
 Author-email: admin@broplanner.com
 License: MIT
 Keywords: Django translate,Django Google Translate,Google translate
```

### Comparing `google_translate_django4-0.3/README.md` & `google_translate_django4-0.4/README.md`

 * *Files identical despite different names*

### Comparing `google_translate_django4-0.3/google_translate_django4.egg-info/PKG-INFO` & `google_translate_django4-0.4/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: google-translate-django4
-Version: 0.3
+Name: google_translate_django4
+Version: 0.4
 Summary: The working google translate module for Django version 4 and above
 Home-page: https://github.com/webprice/google_translate_django4
 Download-URL: https://github.com/webprice/google_translate_django4/archive/refs/tags/v_0.3.tar.gz
 Author: Serhii Hrekov
 Author-email: admin@broplanner.com
 License: MIT
 Keywords: Django translate,Django Google Translate,Google translate
```

### Comparing `google_translate_django4-0.3/setup.py` & `google_translate_django4-0.4/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 # read the contents of your README file
 from pathlib import Path
 this_directory = Path(__file__).parent
 long_description = (this_directory / "README.md").read_text()
 setup(
   name = 'google_translate_django4',
   packages = ['google_translate_django4'],   # Chose the same as "name"
-  version = '0.3',      # Start with a small number and increase it with every change you make
+  version = '0.4',      # Start with a small number and increase it with every change you make
   license='MIT',        # Chose a license from here: https://help.github.com/articles/licensing-a-repository
   description = 'The working google translate module for Django version 4 and above',   # Give a short description about your library
   author = 'Serhii Hrekov',                   # Type in your name
   author_email = 'admin@broplanner.com',      # Type in your E-Mail
   url = 'https://github.com/webprice/google_translate_django4',   # Provide either the link to your github or to your website
   download_url = 'https://github.com/webprice/google_translate_django4/archive/refs/tags/v_0.3.tar.gz',    # I explain this later on
   long_description=long_description,
```


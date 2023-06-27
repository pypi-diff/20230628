# Comparing `tmp/google_translate_django4-0.4.tar.gz` & `tmp/google_translate_django4-0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "google_translate_django4-0.4.tar", last modified: Tue Jun 27 22:12:28 2023, max compression
+gzip compressed data, was "google_translate_django4-0.5.tar", last modified: Tue Jun 27 22:25:25 2023, max compression
```

## Comparing `google_translate_django4-0.4.tar` & `google_translate_django4-0.5.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 22:12:28.789379 google_translate_django4-0.4/
--rw-rw-rw-   0        0        0     1077 1970-01-01 00:00:00.000000 google_translate_django4-0.4/LICENSE.txt
--rw-rw-rw-   0        0        0     2115 2023-06-27 22:12:28.789379 google_translate_django4-0.4/PKG-INFO
--rw-rw-rw-   0        0        0     1018 1970-01-01 00:00:00.000000 google_translate_django4-0.4/README.md
-drwxrwxrwx   0        0        0        0 2023-06-27 22:12:28.772377 google_translate_django4-0.4/google_translate_django4/
--rw-rw-rw-   0        0        0        0 1970-01-01 00:00:00.000000 google_translate_django4-0.4/google_translate_django4/__init__.py
--rw-rw-rw-   0        0        0       66 1970-01-01 00:00:00.000000 google_translate_django4-0.4/google_translate_django4/admin.py
--rw-rw-rw-   0        0        0      124 2023-06-27 22:04:46.000000 google_translate_django4-0.4/google_translate_django4/apps.py
--rw-rw-rw-   0        0        0       60 1970-01-01 00:00:00.000000 google_translate_django4-0.4/google_translate_django4/models.py
--rw-rw-rw-   0        0        0       63 1970-01-01 00:00:00.000000 google_translate_django4-0.4/google_translate_django4/tests.py
--rw-rw-rw-   0        0        0       66 1970-01-01 00:00:00.000000 google_translate_django4-0.4/google_translate_django4/views.py
-drwxrwxrwx   0        0        0        0 2023-06-27 22:12:28.788382 google_translate_django4-0.4/google_translate_django4.egg-info/
--rw-rw-rw-   0        0        0     2115 2023-06-27 22:12:28.000000 google_translate_django4-0.4/google_translate_django4.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      501 2023-06-27 22:12:28.000000 google_translate_django4-0.4/google_translate_django4.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 22:12:28.000000 google_translate_django4-0.4/google_translate_django4.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        7 2023-06-27 22:12:28.000000 google_translate_django4-0.4/google_translate_django4.egg-info/requires.txt
--rw-rw-rw-   0        0        0       25 2023-06-27 22:12:28.000000 google_translate_django4-0.4/google_translate_django4.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       97 2023-06-27 22:12:04.000000 google_translate_django4-0.4/pyproject.toml
--rw-rw-rw-   0        0        0      139 2023-06-27 22:12:28.791392 google_translate_django4-0.4/setup.cfg
--rw-rw-rw-   0        0        0     2139 2023-06-27 22:05:42.000000 google_translate_django4-0.4/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-27 22:25:25.900753 google_translate_django4-0.5/
+-rw-rw-rw-   0        0        0     1077 1970-01-01 00:00:00.000000 google_translate_django4-0.5/LICENSE.txt
+-rw-rw-rw-   0        0        0     2102 2023-06-27 22:25:25.900753 google_translate_django4-0.5/PKG-INFO
+-rw-rw-rw-   0        0        0     1014 2023-06-27 22:16:40.000000 google_translate_django4-0.5/README.md
+drwxrwxrwx   0        0        0        0 2023-06-27 22:25:25.882754 google_translate_django4-0.5/google_translate_django4/
+-rw-rw-rw-   0        0        0        0 1970-01-01 00:00:00.000000 google_translate_django4-0.5/google_translate_django4/__init__.py
+-rw-rw-rw-   0        0        0       66 1970-01-01 00:00:00.000000 google_translate_django4-0.5/google_translate_django4/admin.py
+-rw-rw-rw-   0        0        0      124 2023-06-27 22:04:46.000000 google_translate_django4-0.5/google_translate_django4/apps.py
+-rw-rw-rw-   0        0        0       60 1970-01-01 00:00:00.000000 google_translate_django4-0.5/google_translate_django4/models.py
+-rw-rw-rw-   0        0        0       63 1970-01-01 00:00:00.000000 google_translate_django4-0.5/google_translate_django4/tests.py
+-rw-rw-rw-   0        0        0       66 1970-01-01 00:00:00.000000 google_translate_django4-0.5/google_translate_django4/views.py
+drwxrwxrwx   0        0        0        0 2023-06-27 22:25:25.898753 google_translate_django4-0.5/google_translate_django4.egg-info/
+-rw-rw-rw-   0        0        0     2102 2023-06-27 22:25:25.000000 google_translate_django4-0.5/google_translate_django4.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      501 2023-06-27 22:25:25.000000 google_translate_django4-0.5/google_translate_django4.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-27 22:25:25.000000 google_translate_django4-0.5/google_translate_django4.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        7 2023-06-27 22:25:25.000000 google_translate_django4-0.5/google_translate_django4.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       25 2023-06-27 22:25:25.000000 google_translate_django4-0.5/google_translate_django4.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       97 2023-06-27 22:12:04.000000 google_translate_django4-0.5/pyproject.toml
+-rw-rw-rw-   0        0        0      139 2023-06-27 22:25:25.901753 google_translate_django4-0.5/setup.cfg
+-rw-rw-rw-   0        0        0     2136 2023-06-27 22:25:00.000000 google_translate_django4-0.5/setup.py
```

### Comparing `google_translate_django4-0.4/LICENSE.txt` & `google_translate_django4-0.5/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `google_translate_django4-0.4/PKG-INFO` & `google_translate_django4-0.5/google_translate_django4.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
-Name: google_translate_django4
-Version: 0.4
+Name: google-translate-django4
+Version: 0.5
 Summary: The working google translate module for Django version 4 and above
 Home-page: https://github.com/webprice/google_translate_django4
-Download-URL: https://github.com/webprice/google_translate_django4/archive/refs/tags/v_0.3.tar.gz
+Download-URL: https://github.com/webprice/google_translate_django4/archive/refs/heads/main.zip
 Author: Serhii Hrekov
 Author-email: admin@broplanner.com
 License: MIT
 Keywords: Django translate,Django Google Translate,Google translate
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: Topic :: Software Development :: Build Tools
@@ -27,15 +27,15 @@
 > The orignal source and credits go to: https://pypi.org/project/django-google-translate/ (not working with Django 4+)
 
 ## Quick start
 ##### Download the package:
 ```
 pip install django-google-translate
 ```
-##### Add вЂњgoogle_translateвЂќ to your INSTALLED_APPS setting like this:
+##### Add `google_translate` to your INSTALLED_APPS setting like this:
 ```
 INSTALLED_APPS = [
     ...
     'google_translate',
 ]
 ```
 ##### Load the translate tag in your template (ideally on base.html):
```

#### encoding

```diff
@@ -1 +1 @@
-utf-8
+us-ascii
```

### Comparing `google_translate_django4-0.4/README.md` & `google_translate_django4-0.5/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 > The orignal source and credits go to: https://pypi.org/project/django-google-translate/ (not working with Django 4+)
 
 ## Quick start
 ##### Download the package:
 ```
 pip install django-google-translate
 ```
-##### Add “google_translate” to your INSTALLED_APPS setting like this:
+##### Add `google_translate` to your INSTALLED_APPS setting like this:
 ```
 INSTALLED_APPS = [
     ...
     'google_translate',
 ]
 ```
 ##### Load the translate tag in your template (ideally on base.html):
```

#### encoding

```diff
@@ -1 +1 @@
-utf-8
+us-ascii
```

### Comparing `google_translate_django4-0.4/google_translate_django4.egg-info/PKG-INFO` & `google_translate_django4-0.5/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
-Name: google-translate-django4
-Version: 0.4
+Name: google_translate_django4
+Version: 0.5
 Summary: The working google translate module for Django version 4 and above
 Home-page: https://github.com/webprice/google_translate_django4
-Download-URL: https://github.com/webprice/google_translate_django4/archive/refs/tags/v_0.3.tar.gz
+Download-URL: https://github.com/webprice/google_translate_django4/archive/refs/heads/main.zip
 Author: Serhii Hrekov
 Author-email: admin@broplanner.com
 License: MIT
 Keywords: Django translate,Django Google Translate,Google translate
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: Topic :: Software Development :: Build Tools
@@ -27,15 +27,15 @@
 > The orignal source and credits go to: https://pypi.org/project/django-google-translate/ (not working with Django 4+)
 
 ## Quick start
 ##### Download the package:
 ```
 pip install django-google-translate
 ```
-##### Add вЂњgoogle_translateвЂќ to your INSTALLED_APPS setting like this:
+##### Add `google_translate` to your INSTALLED_APPS setting like this:
 ```
 INSTALLED_APPS = [
     ...
     'google_translate',
 ]
 ```
 ##### Load the translate tag in your template (ideally on base.html):
```

#### encoding

```diff
@@ -1 +1 @@
-utf-8
+us-ascii
```

### Comparing `google_translate_django4-0.4/setup.py` & `google_translate_django4-0.5/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,21 +2,21 @@
 # read the contents of your README file
 from pathlib import Path
 this_directory = Path(__file__).parent
 long_description = (this_directory / "README.md").read_text()
 setup(
   name = 'google_translate_django4',
   packages = ['google_translate_django4'],   # Chose the same as "name"
-  version = '0.4',      # Start with a small number and increase it with every change you make
+  version = '0.5',      # Start with a small number and increase it with every change you make
   license='MIT',        # Chose a license from here: https://help.github.com/articles/licensing-a-repository
   description = 'The working google translate module for Django version 4 and above',   # Give a short description about your library
   author = 'Serhii Hrekov',                   # Type in your name
   author_email = 'admin@broplanner.com',      # Type in your E-Mail
   url = 'https://github.com/webprice/google_translate_django4',   # Provide either the link to your github or to your website
-  download_url = 'https://github.com/webprice/google_translate_django4/archive/refs/tags/v_0.3.tar.gz',    # I explain this later on
+  download_url = 'https://github.com/webprice/google_translate_django4/archive/refs/heads/main.zip',    # I explain this later on
   long_description=long_description,
   long_description_content_type='text/markdown',
 
   keywords = ['Django translate', 'Django Google Translate', 'Google translate'],   # Keywords that define your package best
   install_requires=[            # I get to this in a second
           'django',
       ],
```


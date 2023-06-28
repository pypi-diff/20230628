# Comparing `tmp/django_js_asset-2.0.0.tar.gz` & `tmp/django_js_asset-2.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "django_js_asset-2.0.0.tar", last modified: Thu Feb 10 09:05:30 2022, max compression
+gzip compressed data, last modified: Sun Feb  2 00:00:00 2020, max compression
```

## Comparing `django_js_asset-2.0.0.tar` & `django_js_asset-2.1.0.tar`

### file list

```diff
@@ -1,17 +1,19 @@
-drwxrwxr-x   0 matthias  (1000) matthias  (1000)        0 2022-02-10 09:05:30.491641 django_js_asset-2.0.0/
--rw-rw-r--   0 matthias  (1000) matthias  (1000)     1550 2022-02-10 08:45:21.000000 django_js_asset-2.0.0/LICENSE
--rw-rw-r--   0 matthias  (1000) matthias  (1000)      166 2022-02-10 08:45:21.000000 django_js_asset-2.0.0/MANIFEST.in
--rw-rw-r--   0 matthias  (1000) matthias  (1000)     3486 2022-02-10 09:05:30.491641 django_js_asset-2.0.0/PKG-INFO
--rw-rw-r--   0 matthias  (1000) matthias  (1000)     2290 2022-02-10 08:57:18.000000 django_js_asset-2.0.0/README.rst
-drwxrwxr-x   0 matthias  (1000) matthias  (1000)        0 2022-02-10 09:05:30.491641 django_js_asset-2.0.0/django_js_asset.egg-info/
--rw-rw-r--   0 matthias  (1000) matthias  (1000)     3486 2022-02-10 09:05:30.000000 django_js_asset-2.0.0/django_js_asset.egg-info/PKG-INFO
--rw-rw-r--   0 matthias  (1000) matthias  (1000)      317 2022-02-10 09:05:30.000000 django_js_asset-2.0.0/django_js_asset.egg-info/SOURCES.txt
--rw-rw-r--   0 matthias  (1000) matthias  (1000)        1 2022-02-10 09:05:30.000000 django_js_asset-2.0.0/django_js_asset.egg-info/dependency_links.txt
--rw-rw-r--   0 matthias  (1000) matthias  (1000)        1 2022-02-10 08:45:37.000000 django_js_asset-2.0.0/django_js_asset.egg-info/not-zip-safe
--rw-rw-r--   0 matthias  (1000) matthias  (1000)       30 2022-02-10 09:05:30.000000 django_js_asset-2.0.0/django_js_asset.egg-info/requires.txt
--rw-rw-r--   0 matthias  (1000) matthias  (1000)        9 2022-02-10 09:05:30.000000 django_js_asset-2.0.0/django_js_asset.egg-info/top_level.txt
-drwxrwxr-x   0 matthias  (1000) matthias  (1000)        0 2022-02-10 09:05:30.491641 django_js_asset-2.0.0/js_asset/
--rw-rw-r--   0 matthias  (1000) matthias  (1000)      156 2022-02-10 09:05:02.000000 django_js_asset-2.0.0/js_asset/__init__.py
--rw-rw-r--   0 matthias  (1000) matthias  (1000)     2723 2022-02-10 08:58:05.000000 django_js_asset-2.0.0/js_asset/js.py
--rw-rw-r--   0 matthias  (1000) matthias  (1000)     1435 2022-02-10 09:05:30.491641 django_js_asset-2.0.0/setup.cfg
--rwxrwxr-x   0 matthias  (1000) matthias  (1000)       62 2022-02-10 08:45:21.000000 django_js_asset-2.0.0/setup.py
+-rw-r--r--   0        0        0      200 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/.editorconfig
+-rw-r--r--   0        0        0     1221 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/.pre-commit-config.yaml
+-rw-r--r--   0        0        0     2896 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/CHANGELOG.rst
+-rw-r--r--   0        0        0      404 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/tox.ini
+-rw-r--r--   0        0        0      887 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/.github/workflows/tests.yml
+-rw-r--r--   0        0        0      126 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/js_asset/__init__.py
+-rw-r--r--   0        0        0     2723 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/js_asset/js.py
+-rw-r--r--   0        0        0       20 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/tests/.gitignore
+-rwxr-xr-x   0        0        0      130 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/tests/cov.sh
+-rwxr-xr-x   0        0        0      349 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/tests/manage.py
+-rw-r--r--   0        0        0       16 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/tests/requirements.txt
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/tests/testapp/__init__.py
+-rw-r--r--   0        0        0      187 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/tests/testapp/settings.py
+-rw-r--r--   0        0        0     2856 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/tests/testapp/test_js_asset.py
+-rw-r--r--   0        0        0      152 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/.gitignore
+-rw-r--r--   0        0        0     1550 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/LICENSE
+-rw-r--r--   0        0        0     2290 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/README.rst
+-rw-r--r--   0        0        0     2192 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/pyproject.toml
+-rw-r--r--   0        0        0     3437 2020-02-02 00:00:00.000000 django_js_asset-2.1.0/PKG-INFO
```

### Comparing `django_js_asset-2.0.0/LICENSE` & `django_js_asset-2.1.0/LICENSE`

 * *Files identical despite different names*

### Comparing `django_js_asset-2.0.0/PKG-INFO` & `django_js_asset-2.1.0/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,36 +1,34 @@
 Metadata-Version: 2.1
-Name: django_js_asset
-Version: 2.0.0
+Name: django-js-asset
+Version: 2.1.0
 Summary: script tag with additional attributes for django.forms.Media
-Home-page: https://github.com/matthiask/django-js-asset/
-Author: Matthias Kestenholz
-Author-email: mk@feinheit.ch
+Project-URL: Homepage, https://github.com/matthiask/django-js-asset/
+Author-email: Matthias Kestenholz <mk@feinheit.ch>
 License: BSD-3-Clause
-Platform: OS Independent
+License-File: LICENSE
 Classifier: Environment :: Web Environment
 Classifier: Framework :: Django
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: BSD License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python
-Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: 3.6
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 Classifier: Topic :: Internet :: WWW/HTTP :: Dynamic Content
 Classifier: Topic :: Software Development
 Classifier: Topic :: Software Development :: Libraries :: Application Frameworks
-Requires-Python: >=3.6
-Description-Content-Type: text/x-rst
+Requires-Python: >=3.8
+Requires-Dist: django>=3.2
 Provides-Extra: tests
-License-File: LICENSE
+Requires-Dist: coverage; extra == 'tests'
+Description-Content-Type: text/x-rst
 
 ===============================================================================
 django-js-asset -- script tag with additional attributes for django.forms.Media
 ===============================================================================
 
 .. image:: https://github.com/matthiask/django-js-asset/workflows/Tests/badge.svg
     :target: https://github.com/matthiask/django-js-asset
@@ -94,9 +92,7 @@
 =============
 
 At the time of writing this app is compatible with Django 1.8 and better
 (up to and including the Django master branch), but have a look at the
 `tox configuration
 <https://github.com/matthiask/django-js-asset/blob/main/tox.ini>`_ for
 definitive answers.
-
-
```

#### html2text {}

```diff
@@ -1,23 +1,23 @@
-Metadata-Version: 2.1 Name: django_js_asset Version: 2.0.0 Summary: script tag
-with additional attributes for django.forms.Media Home-page: https://
-github.com/matthiask/django-js-asset/ Author: Matthias Kestenholz Author-email:
-mk@feinheit.ch License: BSD-3-Clause Platform: OS Independent Classifier:
+Metadata-Version: 2.1 Name: django-js-asset Version: 2.1.0 Summary: script tag
+with additional attributes for django.forms.Media Project-URL: Homepage, https:
+//github.com/matthiask/django-js-asset/ Author-email: Matthias Kestenholz
+feinheit.ch> License: BSD-3-Clause License-File: LICENSE Classifier:
 Environment :: Web Environment Classifier: Framework :: Django Classifier:
 Intended Audience :: Developers Classifier: License :: OSI Approved :: BSD
 License Classifier: Operating System :: OS Independent Classifier: Programming
-Language :: Python Classifier: Programming Language :: Python :: 3 Classifier:
-Programming Language :: Python :: 3 :: Only Classifier: Programming Language ::
-Python :: 3.6 Classifier: Programming Language :: Python :: 3.7 Classifier:
-Programming Language :: Python :: 3.8 Classifier: Programming Language ::
-Python :: 3.9 Classifier: Programming Language :: Python :: 3.10 Classifier:
-Topic :: Internet :: WWW/HTTP :: Dynamic Content Classifier: Topic :: Software
+Language :: Python Classifier: Programming Language :: Python :: 3 :: Only
+Classifier: Programming Language :: Python :: 3.8 Classifier: Programming
+Language :: Python :: 3.9 Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11 Classifier: Topic ::
+Internet :: WWW/HTTP :: Dynamic Content Classifier: Topic :: Software
 Development Classifier: Topic :: Software Development :: Libraries ::
-Application Frameworks Requires-Python: >=3.6 Description-Content-Type: text/x-
-rst Provides-Extra: tests License-File: LICENSE
+Application Frameworks Requires-Python: >=3.8 Requires-Dist: django>=3.2
+Provides-Extra: tests Requires-Dist: coverage; extra == 'tests' Description-
+Content-Type: text/x-rst
 ===============================================================================
 django-js-asset -- script tag with additional attributes for django.forms.Media
 ===============================================================================
 .. image:: https://github.com/matthiask/django-js-asset/workflows/Tests/
 badge.svg :target: https://github.com/matthiask/django-js-asset Usage ===== Use
 this to insert a script tag via ``forms.Media`` containing additional
 attributes (such as ``id`` and ``data-*`` for CSP-compatible data injection.):
```

### Comparing `django_js_asset-2.0.0/README.rst` & `django_js_asset-2.1.0/README.rst`

 * *Files identical despite different names*

### Comparing `django_js_asset-2.0.0/js_asset/js.py` & `django_js_asset-2.1.0/js_asset/js.py`

 * *Files identical despite different names*


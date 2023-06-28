# Comparing `tmp/pretix-public-registrations-1.5.1.tar.gz` & `tmp/pretix-public-registrations-1.5.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pretix-public-registrations-1.5.1.tar", last modified: Mon Feb  6 20:36:03 2023, max compression
+gzip compressed data, was "pretix-public-registrations-1.5.2.tar", last modified: Wed Jun 28 11:32:34 2023, max compression
```

## Comparing `pretix-public-registrations-1.5.1.tar` & `pretix-public-registrations-1.5.2.tar`

### file list

```diff
@@ -1,38 +1,38 @@
-drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-02-06 20:36:03.909841 pretix-public-registrations-1.5.1/
--rw-r--r--   0 thegcat    (501) staff       (20)     1091 2023-02-06 20:10:05.000000 pretix-public-registrations-1.5.1/LICENSE
--rw-r--r--   0 thegcat    (501) staff       (20)      207 2023-02-06 19:53:36.000000 pretix-public-registrations-1.5.1/MANIFEST.in
--rw-r--r--   0 thegcat    (501) staff       (20)     2494 2023-02-06 20:36:03.909901 pretix-public-registrations-1.5.1/PKG-INFO
--rw-r--r--   0 thegcat    (501) staff       (20)     1531 2023-02-06 20:10:19.000000 pretix-public-registrations-1.5.1/README.rst
-drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-02-06 20:36:03.907005 pretix-public-registrations-1.5.1/pretix_public_registrations/
--rw-r--r--   0 thegcat    (501) staff       (20)       22 2023-02-06 20:25:59.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/__init__.py
--rw-r--r--   0 thegcat    (501) staff       (20)      986 2023-02-06 20:09:26.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/apps.py
--rw-r--r--   0 thegcat    (501) staff       (20)     1353 2023-02-06 19:36:22.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/forms.py
-drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-02-06 20:36:03.907928 pretix-public-registrations-1.5.1/pretix_public_registrations/locale/
-drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-02-06 20:36:03.904702 pretix-public-registrations-1.5.1/pretix_public_registrations/locale/de/
-drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-02-06 20:36:03.908324 pretix-public-registrations-1.5.1/pretix_public_registrations/locale/de/LC_MESSAGES/
--rw-r--r--   0 thegcat    (501) staff       (20)     1357 2023-02-06 20:10:54.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/locale/de/LC_MESSAGES/django.mo
--rw-r--r--   0 thegcat    (501) staff       (20)     2878 2023-02-06 19:59:25.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/locale/de/LC_MESSAGES/django.po
--rw-r--r--   0 thegcat    (501) staff       (20)     2620 2023-02-06 19:40:57.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/locale/django.pot
--rw-r--r--   0 thegcat    (501) staff       (20)     6717 2023-02-06 19:59:25.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/signals.py
-drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-02-06 20:36:03.904798 pretix-public-registrations-1.5.1/pretix_public_registrations/static/
-drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-02-06 20:36:03.908949 pretix-public-registrations-1.5.1/pretix_public_registrations/static/pretix_public_registrations/
--rw-r--r--   0 thegcat    (501) staff       (20)        0 2023-02-06 19:53:36.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/static/pretix_public_registrations/.gitkeep
--rw-r--r--   0 thegcat    (501) staff       (20)    16879 2022-02-08 22:17:15.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/static/pretix_public_registrations/sorttable.js
--rw-r--r--   0 thegcat    (501) staff       (20)      263 2022-02-08 22:17:15.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/static/pretix_public_registrations/ui.css
-drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-02-06 20:36:03.904892 pretix-public-registrations-1.5.1/pretix_public_registrations/templates/
-drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-02-06 20:36:03.909642 pretix-public-registrations-1.5.1/pretix_public_registrations/templates/pretix_public_registrations/
--rw-r--r--   0 thegcat    (501) staff       (20)        0 2023-02-06 19:53:36.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/templates/pretix_public_registrations/.gitkeep
--rw-r--r--   0 thegcat    (501) staff       (20)     1073 2022-02-08 22:17:15.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/templates/pretix_public_registrations/front_page.html
--rw-r--r--   0 thegcat    (501) staff       (20)      326 2022-02-08 22:17:15.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/templates/pretix_public_registrations/head.html
--rw-r--r--   0 thegcat    (501) staff       (20)      723 2023-02-06 20:24:51.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/templates/pretix_public_registrations/settings.html
--rw-r--r--   0 thegcat    (501) staff       (20)      283 2023-02-06 18:57:42.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/urls.py
--rw-r--r--   0 thegcat    (501) staff       (20)      750 2023-02-06 18:56:17.000000 pretix-public-registrations-1.5.1/pretix_public_registrations/views.py
-drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-02-06 20:36:03.907817 pretix-public-registrations-1.5.1/pretix_public_registrations.egg-info/
--rw-r--r--   0 thegcat    (501) staff       (20)     2494 2023-02-06 20:36:03.000000 pretix-public-registrations-1.5.1/pretix_public_registrations.egg-info/PKG-INFO
--rw-r--r--   0 thegcat    (501) staff       (20)     1279 2023-02-06 20:36:03.000000 pretix-public-registrations-1.5.1/pretix_public_registrations.egg-info/SOURCES.txt
--rw-r--r--   0 thegcat    (501) staff       (20)        1 2023-02-06 20:36:03.000000 pretix-public-registrations-1.5.1/pretix_public_registrations.egg-info/dependency_links.txt
--rw-r--r--   0 thegcat    (501) staff       (20)       90 2023-02-06 20:36:03.000000 pretix-public-registrations-1.5.1/pretix_public_registrations.egg-info/entry_points.txt
--rw-r--r--   0 thegcat    (501) staff       (20)       17 2023-02-06 20:36:03.000000 pretix-public-registrations-1.5.1/pretix_public_registrations.egg-info/requires.txt
--rw-r--r--   0 thegcat    (501) staff       (20)       28 2023-02-06 20:36:03.000000 pretix-public-registrations-1.5.1/pretix_public_registrations.egg-info/top_level.txt
--rw-r--r--   0 thegcat    (501) staff       (20)      868 2023-02-06 20:36:03.910173 pretix-public-registrations-1.5.1/setup.cfg
--rw-r--r--   0 thegcat    (501) staff       (20)     1871 2023-02-06 19:59:25.000000 pretix-public-registrations-1.5.1/setup.py
+drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-06-28 11:32:34.351449 pretix-public-registrations-1.5.2/
+-rw-r--r--   0 thegcat    (501) staff       (20)     1091 2023-02-06 20:10:05.000000 pretix-public-registrations-1.5.2/LICENSE
+-rw-r--r--   0 thegcat    (501) staff       (20)      207 2023-02-06 19:53:36.000000 pretix-public-registrations-1.5.2/MANIFEST.in
+-rw-r--r--   0 thegcat    (501) staff       (20)     2494 2023-06-28 11:32:34.351523 pretix-public-registrations-1.5.2/PKG-INFO
+-rw-r--r--   0 thegcat    (501) staff       (20)     1531 2023-02-06 20:10:19.000000 pretix-public-registrations-1.5.2/README.rst
+drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-06-28 11:32:34.348814 pretix-public-registrations-1.5.2/pretix_public_registrations/
+-rw-r--r--   0 thegcat    (501) staff       (20)       22 2023-06-28 11:31:31.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/__init__.py
+-rw-r--r--   0 thegcat    (501) staff       (20)      986 2023-02-06 20:09:26.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/apps.py
+-rw-r--r--   0 thegcat    (501) staff       (20)     1353 2023-02-06 19:36:22.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/forms.py
+drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-06-28 11:32:34.349962 pretix-public-registrations-1.5.2/pretix_public_registrations/locale/
+drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-06-28 11:32:34.346742 pretix-public-registrations-1.5.2/pretix_public_registrations/locale/de/
+drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-06-28 11:32:34.350302 pretix-public-registrations-1.5.2/pretix_public_registrations/locale/de/LC_MESSAGES/
+-rw-r--r--   0 thegcat    (501) staff       (20)     1357 2023-02-06 20:10:54.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/locale/de/LC_MESSAGES/django.mo
+-rw-r--r--   0 thegcat    (501) staff       (20)     2878 2023-02-06 19:59:25.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/locale/de/LC_MESSAGES/django.po
+-rw-r--r--   0 thegcat    (501) staff       (20)     2620 2023-02-06 19:40:57.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/locale/django.pot
+-rw-r--r--   0 thegcat    (501) staff       (20)     6717 2023-02-06 19:59:25.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/signals.py
+drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-06-28 11:32:34.346896 pretix-public-registrations-1.5.2/pretix_public_registrations/static/
+drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-06-28 11:32:34.350744 pretix-public-registrations-1.5.2/pretix_public_registrations/static/pretix_public_registrations/
+-rw-r--r--   0 thegcat    (501) staff       (20)        0 2023-02-06 19:53:36.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/static/pretix_public_registrations/.gitkeep
+-rw-r--r--   0 thegcat    (501) staff       (20)    16879 2022-02-08 22:17:15.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/static/pretix_public_registrations/sorttable.js
+-rw-r--r--   0 thegcat    (501) staff       (20)      263 2022-02-08 22:17:15.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/static/pretix_public_registrations/ui.css
+drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-06-28 11:32:34.347048 pretix-public-registrations-1.5.2/pretix_public_registrations/templates/
+drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-06-28 11:32:34.351306 pretix-public-registrations-1.5.2/pretix_public_registrations/templates/pretix_public_registrations/
+-rw-r--r--   0 thegcat    (501) staff       (20)        0 2023-02-06 19:53:36.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/templates/pretix_public_registrations/.gitkeep
+-rw-r--r--   0 thegcat    (501) staff       (20)     1073 2022-02-08 22:17:15.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/templates/pretix_public_registrations/front_page.html
+-rw-r--r--   0 thegcat    (501) staff       (20)      326 2022-02-08 22:17:15.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/templates/pretix_public_registrations/head.html
+-rw-r--r--   0 thegcat    (501) staff       (20)      723 2023-02-06 20:24:51.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/templates/pretix_public_registrations/settings.html
+-rw-r--r--   0 thegcat    (501) staff       (20)      267 2023-02-09 07:48:44.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/urls.py
+-rw-r--r--   0 thegcat    (501) staff       (20)      750 2023-02-06 18:56:17.000000 pretix-public-registrations-1.5.2/pretix_public_registrations/views.py
+drwxr-xr-x   0 thegcat    (501) staff       (20)        0 2023-06-28 11:32:34.349779 pretix-public-registrations-1.5.2/pretix_public_registrations.egg-info/
+-rw-r--r--   0 thegcat    (501) staff       (20)     2494 2023-06-28 11:32:34.000000 pretix-public-registrations-1.5.2/pretix_public_registrations.egg-info/PKG-INFO
+-rw-r--r--   0 thegcat    (501) staff       (20)     1279 2023-06-28 11:32:34.000000 pretix-public-registrations-1.5.2/pretix_public_registrations.egg-info/SOURCES.txt
+-rw-r--r--   0 thegcat    (501) staff       (20)        1 2023-06-28 11:32:34.000000 pretix-public-registrations-1.5.2/pretix_public_registrations.egg-info/dependency_links.txt
+-rw-r--r--   0 thegcat    (501) staff       (20)       90 2023-06-28 11:32:34.000000 pretix-public-registrations-1.5.2/pretix_public_registrations.egg-info/entry_points.txt
+-rw-r--r--   0 thegcat    (501) staff       (20)       17 2023-06-28 11:32:34.000000 pretix-public-registrations-1.5.2/pretix_public_registrations.egg-info/requires.txt
+-rw-r--r--   0 thegcat    (501) staff       (20)       28 2023-06-28 11:32:34.000000 pretix-public-registrations-1.5.2/pretix_public_registrations.egg-info/top_level.txt
+-rw-r--r--   0 thegcat    (501) staff       (20)      868 2023-06-28 11:32:34.351886 pretix-public-registrations-1.5.2/setup.cfg
+-rw-r--r--   0 thegcat    (501) staff       (20)     1871 2023-02-06 19:59:25.000000 pretix-public-registrations-1.5.2/setup.py
```

### Comparing `pretix-public-registrations-1.5.1/LICENSE` & `pretix-public-registrations-1.5.2/LICENSE`

 * *Files identical despite different names*

### Comparing `pretix-public-registrations-1.5.1/PKG-INFO` & `pretix-public-registrations-1.5.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pretix-public-registrations
-Version: 1.5.1
+Version: 1.5.2
 Summary: This plugin will give the option to attendees of an event to mark their registration as public. Public registrations will be shown along their answers to questions marked as public by the organizers on a world-readable page.
 Home-page: https://gitlab.fachschaften.org/kif/pretix-public-registrations
 Author: Felix Schäfer, Dominik Weitz
 Author-email: admin@kif.rocks
 License: MIT
 Project-URL: Bug Tracker, https://gitlab.fachschaften.org/kif/pretix-public-registrations/issues
 Project-URL: Source Code, https://gitlab.fachschaften.org/kif/pretix-public-registrations/tree/master
```

### Comparing `pretix-public-registrations-1.5.1/README.rst` & `pretix-public-registrations-1.5.2/README.rst`

 * *Files identical despite different names*

### Comparing `pretix-public-registrations-1.5.1/pretix_public_registrations/apps.py` & `pretix-public-registrations-1.5.2/pretix_public_registrations/apps.py`

 * *Files identical despite different names*

### Comparing `pretix-public-registrations-1.5.1/pretix_public_registrations/forms.py` & `pretix-public-registrations-1.5.2/pretix_public_registrations/forms.py`

 * *Files identical despite different names*

### Comparing `pretix-public-registrations-1.5.1/pretix_public_registrations/locale/de/LC_MESSAGES/django.mo` & `pretix-public-registrations-1.5.2/pretix_public_registrations/locale/de/LC_MESSAGES/django.mo`

 * *Files identical despite different names*

### Comparing `pretix-public-registrations-1.5.1/pretix_public_registrations/locale/de/LC_MESSAGES/django.po` & `pretix-public-registrations-1.5.2/pretix_public_registrations/locale/de/LC_MESSAGES/django.po`

 * *Files identical despite different names*

### Comparing `pretix-public-registrations-1.5.1/pretix_public_registrations/locale/django.pot` & `pretix-public-registrations-1.5.2/pretix_public_registrations/locale/django.pot`

 * *Files identical despite different names*

### Comparing `pretix-public-registrations-1.5.1/pretix_public_registrations/signals.py` & `pretix-public-registrations-1.5.2/pretix_public_registrations/signals.py`

 * *Files identical despite different names*

### Comparing `pretix-public-registrations-1.5.1/pretix_public_registrations/static/pretix_public_registrations/sorttable.js` & `pretix-public-registrations-1.5.2/pretix_public_registrations/static/pretix_public_registrations/sorttable.js`

 * *Files identical despite different names*

### Comparing `pretix-public-registrations-1.5.1/pretix_public_registrations/templates/pretix_public_registrations/front_page.html` & `pretix-public-registrations-1.5.2/pretix_public_registrations/templates/pretix_public_registrations/front_page.html`

 * *Files identical despite different names*

### Comparing `pretix-public-registrations-1.5.1/pretix_public_registrations/templates/pretix_public_registrations/settings.html` & `pretix-public-registrations-1.5.2/pretix_public_registrations/templates/pretix_public_registrations/settings.html`

 * *Files identical despite different names*

### Comparing `pretix-public-registrations-1.5.1/pretix_public_registrations/views.py` & `pretix-public-registrations-1.5.2/pretix_public_registrations/views.py`

 * *Files identical despite different names*

### Comparing `pretix-public-registrations-1.5.1/pretix_public_registrations.egg-info/PKG-INFO` & `pretix-public-registrations-1.5.2/pretix_public_registrations.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pretix-public-registrations
-Version: 1.5.1
+Version: 1.5.2
 Summary: This plugin will give the option to attendees of an event to mark their registration as public. Public registrations will be shown along their answers to questions marked as public by the organizers on a world-readable page.
 Home-page: https://gitlab.fachschaften.org/kif/pretix-public-registrations
 Author: Felix Schäfer, Dominik Weitz
 Author-email: admin@kif.rocks
 License: MIT
 Project-URL: Bug Tracker, https://gitlab.fachschaften.org/kif/pretix-public-registrations/issues
 Project-URL: Source Code, https://gitlab.fachschaften.org/kif/pretix-public-registrations/tree/master
```

### Comparing `pretix-public-registrations-1.5.1/pretix_public_registrations.egg-info/SOURCES.txt` & `pretix-public-registrations-1.5.2/pretix_public_registrations.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pretix-public-registrations-1.5.1/setup.cfg` & `pretix-public-registrations-1.5.2/setup.cfg`

 * *Files identical despite different names*

### Comparing `pretix-public-registrations-1.5.1/setup.py` & `pretix-public-registrations-1.5.2/setup.py`

 * *Files identical despite different names*


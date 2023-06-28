# Comparing `tmp/django-htmx-autocomplete-0.8.0.tar.gz` & `tmp/django-htmx-autocomplete-0.8.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "django-htmx-autocomplete-0.8.0.tar", last modified: Tue Jun 27 23:07:36 2023, max compression
+gzip compressed data, was "django-htmx-autocomplete-0.8.1.tar", last modified: Wed Jun 28 12:47:06 2023, max compression
```

## Comparing `django-htmx-autocomplete-0.8.0.tar` & `django-htmx-autocomplete-0.8.1.tar`

### file list

```diff
@@ -1,60 +1,60 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.845855 django-htmx-autocomplete-0.8.0/
--rw-r--r--   0 runner    (1001) docker     (123)     1082 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      157 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     6433 2023-06-27 23:07:36.845855 django-htmx-autocomplete-0.8.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     5476 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.841855 django-htmx-autocomplete-0.8.0/autocomplete/
--rw-r--r--   0 runner    (1001) docker     (123)      114 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      226 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/apps.py
--rw-r--r--   0 runner    (1001) docker     (123)    25820 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/autocomplete.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.837855 django-htmx-autocomplete-0.8.0/autocomplete/locale/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.837855 django-htmx-autocomplete-0.8.0/autocomplete/locale/en/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.841855 django-htmx-autocomplete-0.8.0/autocomplete/locale/en/LC_MESSAGES/
--rw-r--r--   0 runner    (1001) docker     (123)      380 2023-06-27 23:07:36.000000 django-htmx-autocomplete-0.8.0/autocomplete/locale/en/LC_MESSAGES/django.mo
--rw-r--r--   0 runner    (1001) docker     (123)     1663 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/locale/en/LC_MESSAGES/django.po
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.837855 django-htmx-autocomplete-0.8.0/autocomplete/locale/fr/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.841855 django-htmx-autocomplete-0.8.0/autocomplete/locale/fr/LC_MESSAGES/
--rw-r--r--   0 runner    (1001) docker     (123)     1235 2023-06-27 23:07:36.000000 django-htmx-autocomplete-0.8.0/autocomplete/locale/fr/LC_MESSAGES/django.mo
--rw-r--r--   0 runner    (1001) docker     (123)     2030 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/locale/fr/LC_MESSAGES/django.po
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.837855 django-htmx-autocomplete-0.8.0/autocomplete/static/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.837855 django-htmx-autocomplete-0.8.0/autocomplete/static/autocomplete/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.841855 django-htmx-autocomplete-0.8.0/autocomplete/static/autocomplete/css/
--rw-r--r--   0 runner    (1001) docker     (123)     6568 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/static/autocomplete/css/autocomplete.css
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.841855 django-htmx-autocomplete-0.8.0/autocomplete/static/autocomplete/js/
--rw-r--r--   0 runner    (1001) docker     (123)    13946 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/static/autocomplete/js/autocomplete.js
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.837855 django-htmx-autocomplete-0.8.0/autocomplete/templates/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.841855 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/
--rw-r--r--   0 runner    (1001) docker     (123)      612 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/ac_container.html
--rw-r--r--   0 runner    (1001) docker     (123)      914 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/chip.html
--rw-r--r--   0 runner    (1001) docker     (123)      163 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/chip_list.html
--rw-r--r--   0 runner    (1001) docker     (123)     7069 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/component.html
--rw-r--r--   0 runner    (1001) docker     (123)     1321 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/head.html
--rw-r--r--   0 runner    (1001) docker     (123)      949 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/indicator-icon.html
--rw-r--r--   0 runner    (1001) docker     (123)     2988 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/item.html
--rw-r--r--   0 runner    (1001) docker     (123)      930 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/item_list.html
--rw-r--r--   0 runner    (1001) docker     (123)      740 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/scripts.html
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.841855 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/strings/
--rw-r--r--   0 runner    (1001) docker     (123)      194 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/strings/available_results.html
--rw-r--r--   0 runner    (1001) docker     (123)       83 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/strings/backspace_instruction.html
--rw-r--r--   0 runner    (1001) docker     (123)       88 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/strings/item_selected.html
--rw-r--r--   0 runner    (1001) docker     (123)      266 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/strings/more_results.html
--rw-r--r--   0 runner    (1001) docker     (123)       44 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/strings/multiselect.html
--rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/strings/no_results.html
--rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/strings/nothing_selected.html
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/strings/selected.html
--rw-r--r--   0 runner    (1001) docker     (123)     1740 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/textinput.html
--rw-r--r--   0 runner    (1001) docker     (123)      427 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/values.html
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.841855 django-htmx-autocomplete-0.8.0/autocomplete/templatetags/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templatetags/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3898 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/templatetags/autocomplete.py
--rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/test_autocomplete.py
--rw-r--r--   0 runner    (1001) docker     (123)     5310 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/autocomplete/widgets.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:07:36.845855 django-htmx-autocomplete-0.8.0/django_htmx_autocomplete.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     6433 2023-06-27 23:07:36.000000 django-htmx-autocomplete-0.8.0/django_htmx_autocomplete.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1858 2023-06-27 23:07:36.000000 django-htmx-autocomplete-0.8.0/django_htmx_autocomplete.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 23:07:36.000000 django-htmx-autocomplete-0.8.0/django_htmx_autocomplete.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-27 23:07:36.000000 django-htmx-autocomplete-0.8.0/django_htmx_autocomplete.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-27 23:07:36.000000 django-htmx-autocomplete-0.8.0/django_htmx_autocomplete.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      108 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)     1005 2023-06-27 23:07:36.845855 django-htmx-autocomplete-0.8.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1338 2023-06-27 23:07:15.000000 django-htmx-autocomplete-0.8.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.850890 django-htmx-autocomplete-0.8.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1082 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      157 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     6433 2023-06-28 12:47:06.850890 django-htmx-autocomplete-0.8.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     5476 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.846890 django-htmx-autocomplete-0.8.1/autocomplete/
+-rw-r--r--   0 runner    (1001) docker     (123)      114 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      226 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/apps.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25303 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/autocomplete.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.842890 django-htmx-autocomplete-0.8.1/autocomplete/locale/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.842890 django-htmx-autocomplete-0.8.1/autocomplete/locale/en/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.846890 django-htmx-autocomplete-0.8.1/autocomplete/locale/en/LC_MESSAGES/
+-rw-r--r--   0 runner    (1001) docker     (123)      380 2023-06-28 12:47:06.000000 django-htmx-autocomplete-0.8.1/autocomplete/locale/en/LC_MESSAGES/django.mo
+-rw-r--r--   0 runner    (1001) docker     (123)     1663 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/locale/en/LC_MESSAGES/django.po
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.842890 django-htmx-autocomplete-0.8.1/autocomplete/locale/fr/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.846890 django-htmx-autocomplete-0.8.1/autocomplete/locale/fr/LC_MESSAGES/
+-rw-r--r--   0 runner    (1001) docker     (123)     1235 2023-06-28 12:47:06.000000 django-htmx-autocomplete-0.8.1/autocomplete/locale/fr/LC_MESSAGES/django.mo
+-rw-r--r--   0 runner    (1001) docker     (123)     2030 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/locale/fr/LC_MESSAGES/django.po
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.842890 django-htmx-autocomplete-0.8.1/autocomplete/static/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.842890 django-htmx-autocomplete-0.8.1/autocomplete/static/autocomplete/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.846890 django-htmx-autocomplete-0.8.1/autocomplete/static/autocomplete/css/
+-rw-r--r--   0 runner    (1001) docker     (123)     6568 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/static/autocomplete/css/autocomplete.css
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.846890 django-htmx-autocomplete-0.8.1/autocomplete/static/autocomplete/js/
+-rw-r--r--   0 runner    (1001) docker     (123)    13946 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/static/autocomplete/js/autocomplete.js
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.846890 django-htmx-autocomplete-0.8.1/autocomplete/templates/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.846890 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/
+-rw-r--r--   0 runner    (1001) docker     (123)      612 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/ac_container.html
+-rw-r--r--   0 runner    (1001) docker     (123)      914 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/chip.html
+-rw-r--r--   0 runner    (1001) docker     (123)      163 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/chip_list.html
+-rw-r--r--   0 runner    (1001) docker     (123)     7069 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/component.html
+-rw-r--r--   0 runner    (1001) docker     (123)     1321 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/head.html
+-rw-r--r--   0 runner    (1001) docker     (123)      949 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/indicator-icon.html
+-rw-r--r--   0 runner    (1001) docker     (123)     2988 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/item.html
+-rw-r--r--   0 runner    (1001) docker     (123)      930 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/item_list.html
+-rw-r--r--   0 runner    (1001) docker     (123)      740 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/scripts.html
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.850890 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/strings/
+-rw-r--r--   0 runner    (1001) docker     (123)      194 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/strings/available_results.html
+-rw-r--r--   0 runner    (1001) docker     (123)       83 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/strings/backspace_instruction.html
+-rw-r--r--   0 runner    (1001) docker     (123)       88 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/strings/item_selected.html
+-rw-r--r--   0 runner    (1001) docker     (123)      266 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/strings/more_results.html
+-rw-r--r--   0 runner    (1001) docker     (123)       44 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/strings/multiselect.html
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/strings/no_results.html
+-rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/strings/nothing_selected.html
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/strings/selected.html
+-rw-r--r--   0 runner    (1001) docker     (123)     1740 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/textinput.html
+-rw-r--r--   0 runner    (1001) docker     (123)      427 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/values.html
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.850890 django-htmx-autocomplete-0.8.1/autocomplete/templatetags/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templatetags/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3898 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/templatetags/autocomplete.py
+-rw-r--r--   0 runner    (1001) docker     (123)      814 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/test_autocomplete.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5310 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/autocomplete/widgets.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:06.850890 django-htmx-autocomplete-0.8.1/django_htmx_autocomplete.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     6433 2023-06-28 12:47:06.000000 django-htmx-autocomplete-0.8.1/django_htmx_autocomplete.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1858 2023-06-28 12:47:06.000000 django-htmx-autocomplete-0.8.1/django_htmx_autocomplete.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:47:06.000000 django-htmx-autocomplete-0.8.1/django_htmx_autocomplete.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-28 12:47:06.000000 django-htmx-autocomplete-0.8.1/django_htmx_autocomplete.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-28 12:47:06.000000 django-htmx-autocomplete-0.8.1/django_htmx_autocomplete.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      108 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)     1005 2023-06-28 12:47:06.850890 django-htmx-autocomplete-0.8.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1338 2023-06-28 12:46:42.000000 django-htmx-autocomplete-0.8.1/setup.py
```

### Comparing `django-htmx-autocomplete-0.8.0/LICENSE` & `django-htmx-autocomplete-0.8.1/LICENSE`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/PKG-INFO` & `django-htmx-autocomplete-0.8.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: django-htmx-autocomplete
-Version: 0.8.0
+Version: 0.8.1
 Summary: A Django autocomplete component powered by htmx
 Home-page: https://github.com/PHACDataHub/django-htmx-autocomplete
 Author: Luc Belliveau
 Author-email: luc.belliveau@canada.ca
 License: MIT
 Classifier: Environment :: Web Environment
 Classifier: Framework :: Django
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: django-htmx-autocomplete Version: 0.8.0 Summary: A
+Metadata-Version: 2.1 Name: django-htmx-autocomplete Version: 0.8.1 Summary: A
 Django autocomplete component powered by htmx Home-page: https://github.com/
 PHACDataHub/django-htmx-autocomplete Author: Luc Belliveau Author-email:
 luc.belliveau@canada.ca License: MIT Classifier: Environment :: Web Environment
 Classifier: Framework :: Django Classifier: Framework :: Django :: 4.1
 Classifier: Intended Audience :: Developers Classifier: License :: OSI Approved
 :: MIT License Classifier: Operating System :: OS Independent Classifier:
 Programming Language :: Python Classifier: Programming Language :: Python :: 3
```

### Comparing `django-htmx-autocomplete-0.8.0/README.md` & `django-htmx-autocomplete-0.8.1/README.md`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/autocomplete.py` & `django-htmx-autocomplete-0.8.1/autocomplete/autocomplete.py`

 * *Files 2% similar despite different names*

```diff
@@ -374,15 +374,15 @@
         Returns:
             str: Component ID
         """
         if override_id:
             return override_id
         return cls.component_id if cls.component_id else cls.get_route_name()
 
-    def get_items(self, search=None, values=None, request=None):
+    def get_items(self, search=None, values=None):
         """Get available items based on search or values.
 
         If search is specified, only items who's label contain the search
         term will be included in the results.  The label column is defined by
         the Meta class's `item_label` attribute.
 
         If values is specified, only items who's value is contained in the
@@ -391,23 +391,17 @@
 
         This method can be overridden to provide more advanced control over
         how items are searched for or generated.  In the case where the Meta
         class is not specified at all, the overridden method is expected to
         return an array of dictionaries where each item has the `label` and
         value` keys defined.
 
-        IMPORTANT: When used as a widget in a form, django will call the get_items
-        method in order to validate the selected items are truly part of the list - in
-        this context the request object is not available so it is important to be aware
-        of this when customizing the get_items method.
-
         Parameters:
         search (str): The search term
         values (str[]): Array of values
-        request (HttpRequest): Django request object
 
         Returns:
         array of dictionaries
         """
         items = None
         if search is not None:
             search_dict = {f"{self._item_label}__{self._lookup}": search}
@@ -492,16 +486,15 @@
 
         if method == "toggle":
             item = data.get("item", None)
             if item is None:
                 return HttpResponseBadRequest()
 
             items = self.map_items(
-                self.get_items(values=items_selected + [item], request=request),
-                items_selected,
+                self.get_items(values=items_selected + [item]), items_selected
             )
 
             def sort_items(item):
                 try:
                     return items_selected.index(f"{item.get('value')}")
                 except ValueError:
                     return len(items_selected)
@@ -521,14 +514,15 @@
                 target_item["selected"] = True
 
             if not self.multiselect:
                 for item in items:
                     if item != target_item:
                         item["selected"] = False
 
+
             template = loader.get_template("autocomplete/item.html")
             return HttpResponse(
                 template.render(
                     {
                         "name": component_name,
                         "search": "",
                         "indicator": self.indicator,
@@ -599,17 +593,15 @@
             items_selected = []
 
         override_component_id = request.GET.get("component_id", "")
         component_name = request.GET.get("name", self.name)
 
         if method == "component":
             template = loader.get_template("autocomplete/component.html")
-            selected_options = self.map_items(
-                self.get_items(values=items_selected, request=request)
-            )
+            selected_options = self.map_items(self.get_items(values=items_selected))
 
             return HttpResponse(
                 template.render(
                     {
                         "name": component_name,
                         "disabled": self.disabled,
                         "required": self.required,
@@ -628,17 +620,15 @@
             )
 
         if method == "items":
             template = loader.get_template("autocomplete/item_list.html")
             search = request.GET.get("search", "")
             show = len(search) >= self.minimum_search_length
             items = (
-                self.map_items(self.get_items(search=search, request=request), items_selected)
-                if show
-                else []
+                self.map_items(self.get_items(search), items_selected) if show else []
             )
             total_results = len(items)
             if self.max_results is not None and len(items) > self.max_results:
                 items = items[: self.max_results]
 
             return HttpResponse(
                 template.render(
```

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/locale/en/LC_MESSAGES/django.po` & `django-htmx-autocomplete-0.8.1/autocomplete/locale/en/LC_MESSAGES/django.po`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/locale/fr/LC_MESSAGES/django.mo` & `django-htmx-autocomplete-0.8.1/autocomplete/locale/fr/LC_MESSAGES/django.mo`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/locale/fr/LC_MESSAGES/django.po` & `django-htmx-autocomplete-0.8.1/autocomplete/locale/fr/LC_MESSAGES/django.po`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/static/autocomplete/css/autocomplete.css` & `django-htmx-autocomplete-0.8.1/autocomplete/static/autocomplete/css/autocomplete.css`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/static/autocomplete/js/autocomplete.js` & `django-htmx-autocomplete-0.8.1/autocomplete/static/autocomplete/js/autocomplete.js`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/ac_container.html` & `django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/ac_container.html`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/chip.html` & `django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/chip.html`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/component.html` & `django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/component.html`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/head.html` & `django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/head.html`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/indicator-icon.html` & `django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/indicator-icon.html`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/item.html` & `django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/item.html`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/item_list.html` & `django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/item_list.html`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/scripts.html` & `django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/scripts.html`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/templates/autocomplete/textinput.html` & `django-htmx-autocomplete-0.8.1/autocomplete/templates/autocomplete/textinput.html`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/templatetags/autocomplete.py` & `django-htmx-autocomplete-0.8.1/autocomplete/templatetags/autocomplete.py`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/autocomplete/widgets.py` & `django-htmx-autocomplete-0.8.1/autocomplete/widgets.py`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/django_htmx_autocomplete.egg-info/PKG-INFO` & `django-htmx-autocomplete-0.8.1/django_htmx_autocomplete.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: django-htmx-autocomplete
-Version: 0.8.0
+Version: 0.8.1
 Summary: A Django autocomplete component powered by htmx
 Home-page: https://github.com/PHACDataHub/django-htmx-autocomplete
 Author: Luc Belliveau
 Author-email: luc.belliveau@canada.ca
 License: MIT
 Classifier: Environment :: Web Environment
 Classifier: Framework :: Django
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: django-htmx-autocomplete Version: 0.8.0 Summary: A
+Metadata-Version: 2.1 Name: django-htmx-autocomplete Version: 0.8.1 Summary: A
 Django autocomplete component powered by htmx Home-page: https://github.com/
 PHACDataHub/django-htmx-autocomplete Author: Luc Belliveau Author-email:
 luc.belliveau@canada.ca License: MIT Classifier: Environment :: Web Environment
 Classifier: Framework :: Django Classifier: Framework :: Django :: 4.1
 Classifier: Intended Audience :: Developers Classifier: License :: OSI Approved
 :: MIT License Classifier: Operating System :: OS Independent Classifier:
 Programming Language :: Python Classifier: Programming Language :: Python :: 3
```

### Comparing `django-htmx-autocomplete-0.8.0/django_htmx_autocomplete.egg-info/SOURCES.txt` & `django-htmx-autocomplete-0.8.1/django_htmx_autocomplete.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `django-htmx-autocomplete-0.8.0/setup.cfg` & `django-htmx-autocomplete-0.8.1/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = django-htmx-autocomplete
-version = 0.8.0
+version = 0.8.1
 description = A Django autocomplete component powered by htmx
 long_description = file: README.md
 long_description_content_type = text/markdown
 url = https://github.com/PHACDataHub/django-htmx-autocomplete
 author = Luc Belliveau
 author_email = luc.belliveau@canada.ca
 license = MIT
```

### Comparing `django-htmx-autocomplete-0.8.0/setup.py` & `django-htmx-autocomplete-0.8.1/setup.py`

 * *Files identical despite different names*


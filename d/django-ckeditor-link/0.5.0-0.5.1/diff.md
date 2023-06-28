# Comparing `tmp/django-ckeditor-link-0.5.0.tar.gz` & `tmp/django-ckeditor-link-0.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "django-ckeditor-link-0.5.0.tar", last modified: Wed Apr 19 22:05:21 2023, max compression
+gzip compressed data, was "django-ckeditor-link-0.5.1.tar", last modified: Wed Jun 28 11:18:52 2023, max compression
```

## Comparing `django-ckeditor-link-0.5.0.tar` & `django-ckeditor-link-0.5.1.tar`

### file list

```diff
@@ -1,82 +1,82 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.392096 django-ckeditor-link-0.5.0/
--rw-r--r--   0 runner    (1001) docker     (123)     3128 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/CHANGELOG.txt
--rw-r--r--   0 runner    (1001) docker     (123)       70 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/DESCRIPTION
--rw-r--r--   0 runner    (1001) docker     (123)    18091 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      206 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     7954 2023-04-19 22:05:21.396096 django-ckeditor-link-0.5.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     7305 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.388096 django-ckeditor-link-0.5.0/ckeditor_link/
--rw-r--r--   0 runner    (1001) docker     (123)       45 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2586 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/admin.py
--rw-r--r--   0 runner    (1001) docker     (123)      313 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/conf.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.388096 django-ckeditor-link-0.5.0/ckeditor_link/link_model/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/link_model/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1147 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/link_model/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)     6370 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/link_model/models.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.388096 django-ckeditor-link-0.5.0/ckeditor_link/management/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/management/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.388096 django-ckeditor-link-0.5.0/ckeditor_link/management/commands/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/management/commands/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3105 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/management/commands/cmsplugin2ckeditor_link.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.388096 django-ckeditor-link-0.5.0/ckeditor_link/static/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.384096 django-ckeditor-link-0.5.0/ckeditor_link/static/admin/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.384096 django-ckeditor-link-0.5.0/ckeditor_link/static/admin/ckeditor_link/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.388096 django-ckeditor-link-0.5.0/ckeditor_link/static/admin/ckeditor_link/css/
--rw-r--r--   0 runner    (1001) docker     (123)      379 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/static/admin/ckeditor_link/css/link_admin.css
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.384096 django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.384096 django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.388096 django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/plugins/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.388096 django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.388096 django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/dialogs/
--rw-r--r--   0 runner    (1001) docker     (123)     6536 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/dialogs/djangolink.js
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.392096 django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/examples-not-used/
--rw-r--r--   0 runner    (1001) docker     (123)    23980 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_dialog.js
--rw-r--r--   0 runner    (1001) docker     (123)    24950 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_plugin.js
--rw-r--r--   0 runner    (1001) docker     (123)    14939 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/examples-not-used/cmsplugin_example.js
--rw-r--r--   0 runner    (1001) docker     (123)    11226 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/plugin.js
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.388096 django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.388096 django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.388096 django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.392096 django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.392096 django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/dialogs/
--rw-r--r--   0 runner    (1001) docker     (123)     6536 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/dialogs/djangolink.js
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.392096 django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/examples-not-used/
--rw-r--r--   0 runner    (1001) docker     (123)    23980 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_dialog.js
--rw-r--r--   0 runner    (1001) docker     (123)    24950 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_plugin.js
--rw-r--r--   0 runner    (1001) docker     (123)    14939 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/examples-not-used/cmsplugin_example.js
--rw-r--r--   0 runner    (1001) docker     (123)    11226 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/plugin.js
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.392096 django-ckeditor-link-0.5.0/ckeditor_link/templatetags/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/templatetags/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3359 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/templatetags/ckeditor_link_tags.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.392096 django-ckeditor-link-0.5.0/ckeditor_link/tests/
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4685 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/settings.py
--rw-r--r--   0 runner    (1001) docker     (123)       59 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/settings_no_headless.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.392096 django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      784 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/admin.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.392096 django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/migrations/
--rw-r--r--   0 runner    (1001) docker     (123)     1548 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/migrations/0001_initial.py
--rw-r--r--   0 runner    (1001) docker     (123)      641 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/migrations/0002_auto_20161128_1458.py
--rw-r--r--   0 runner    (1001) docker     (123)     2702 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/migrations/0003_cmsfilerlinkmodel_contriblinkmodel.py
--rw-r--r--   0 runner    (1001) docker     (123)     1121 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/migrations/0004_auto_20210412_0750.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/migrations/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2213 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/models.py
--rw-r--r--   0 runner    (1001) docker     (123)      138 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/views.py
--rw-r--r--   0 runner    (1001) docker     (123)     4469 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/test_editor.py
--rw-r--r--   0 runner    (1001) docker     (123)     3546 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/test_link_model.py
--rw-r--r--   0 runner    (1001) docker     (123)     2512 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/test_templatetag.py
--rw-r--r--   0 runner    (1001) docker     (123)      557 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/urls.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.392096 django-ckeditor-link-0.5.0/ckeditor_link/tests/utils/
--rw-r--r--   0 runner    (1001) docker     (123)       54 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      265 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/utils/django_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     3077 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/ckeditor_link/tests/utils/selenium_utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-19 22:05:21.392096 django-ckeditor-link-0.5.0/django_ckeditor_link.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     7954 2023-04-19 22:05:21.000000 django-ckeditor-link-0.5.0/django_ckeditor_link.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2660 2023-04-19 22:05:21.000000 django-ckeditor-link-0.5.0/django_ckeditor_link.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-04-19 22:05:21.000000 django-ckeditor-link-0.5.0/django_ckeditor_link.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-04-19 22:05:21.000000 django-ckeditor-link-0.5.0/django_ckeditor_link.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       13 2023-04-19 22:05:21.000000 django-ckeditor-link-0.5.0/django_ckeditor_link.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       14 2023-04-19 22:05:21.000000 django-ckeditor-link-0.5.0/django_ckeditor_link.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      158 2023-04-19 22:05:21.396096 django-ckeditor-link-0.5.0/setup.cfg
--rwxr-xr-x   0 runner    (1001) docker     (123)     1218 2023-04-19 22:05:08.000000 django-ckeditor-link-0.5.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.142580 django-ckeditor-link-0.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     3349 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/CHANGELOG.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       70 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/DESCRIPTION
+-rw-r--r--   0 runner    (1001) docker     (123)    18091 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      206 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     8228 2023-06-28 11:18:52.142580 django-ckeditor-link-0.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     7579 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.138580 django-ckeditor-link-0.5.1/ckeditor_link/
+-rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2586 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/admin.py
+-rw-r--r--   0 runner    (1001) docker     (123)      313 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/conf.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.138580 django-ckeditor-link-0.5.1/ckeditor_link/link_model/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/link_model/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1267 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/link_model/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6584 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/link_model/models.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.138580 django-ckeditor-link-0.5.1/ckeditor_link/management/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/management/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.138580 django-ckeditor-link-0.5.1/ckeditor_link/management/commands/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/management/commands/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3105 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/management/commands/cmsplugin2ckeditor_link.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.134580 django-ckeditor-link-0.5.1/ckeditor_link/static/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.134580 django-ckeditor-link-0.5.1/ckeditor_link/static/admin/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.134580 django-ckeditor-link-0.5.1/ckeditor_link/static/admin/ckeditor_link/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.138580 django-ckeditor-link-0.5.1/ckeditor_link/static/admin/ckeditor_link/css/
+-rw-r--r--   0 runner    (1001) docker     (123)      379 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/static/admin/ckeditor_link/css/link_admin.css
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.134580 django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.134580 django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.134580 django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/plugins/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.138580 django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.138580 django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/dialogs/
+-rw-r--r--   0 runner    (1001) docker     (123)     6536 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/dialogs/djangolink.js
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.138580 django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/examples-not-used/
+-rw-r--r--   0 runner    (1001) docker     (123)    23980 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_dialog.js
+-rw-r--r--   0 runner    (1001) docker     (123)    24950 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_plugin.js
+-rw-r--r--   0 runner    (1001) docker     (123)    14939 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/examples-not-used/cmsplugin_example.js
+-rw-r--r--   0 runner    (1001) docker     (123)    11226 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/plugin.js
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.134580 django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.134580 django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.134580 django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.138580 django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.138580 django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/dialogs/
+-rw-r--r--   0 runner    (1001) docker     (123)     6536 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/dialogs/djangolink.js
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.138580 django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/examples-not-used/
+-rw-r--r--   0 runner    (1001) docker     (123)    23980 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_dialog.js
+-rw-r--r--   0 runner    (1001) docker     (123)    24950 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_plugin.js
+-rw-r--r--   0 runner    (1001) docker     (123)    14939 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/examples-not-used/cmsplugin_example.js
+-rw-r--r--   0 runner    (1001) docker     (123)    11226 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/plugin.js
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.138580 django-ckeditor-link-0.5.1/ckeditor_link/templatetags/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/templatetags/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3359 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/templatetags/ckeditor_link_tags.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.138580 django-ckeditor-link-0.5.1/ckeditor_link/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4685 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/settings.py
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/settings_no_headless.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.142580 django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      784 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/admin.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.142580 django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/migrations/
+-rw-r--r--   0 runner    (1001) docker     (123)     1548 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/migrations/0001_initial.py
+-rw-r--r--   0 runner    (1001) docker     (123)      641 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/migrations/0002_auto_20161128_1458.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2702 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/migrations/0003_cmsfilerlinkmodel_contriblinkmodel.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1121 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/migrations/0004_auto_20210412_0750.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/migrations/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2213 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/models.py
+-rw-r--r--   0 runner    (1001) docker     (123)      138 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/views.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4469 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/test_editor.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3546 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/test_link_model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2512 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/test_templatetag.py
+-rw-r--r--   0 runner    (1001) docker     (123)      557 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/urls.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.142580 django-ckeditor-link-0.5.1/ckeditor_link/tests/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)       54 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      265 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/utils/django_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3077 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/ckeditor_link/tests/utils/selenium_utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:18:52.142580 django-ckeditor-link-0.5.1/django_ckeditor_link.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     8228 2023-06-28 11:18:52.000000 django-ckeditor-link-0.5.1/django_ckeditor_link.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2660 2023-06-28 11:18:52.000000 django-ckeditor-link-0.5.1/django_ckeditor_link.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:18:52.000000 django-ckeditor-link-0.5.1/django_ckeditor_link.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:18:52.000000 django-ckeditor-link-0.5.1/django_ckeditor_link.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-28 11:18:52.000000 django-ckeditor-link-0.5.1/django_ckeditor_link.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       14 2023-06-28 11:18:52.000000 django-ckeditor-link-0.5.1/django_ckeditor_link.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      158 2023-06-28 11:18:52.142580 django-ckeditor-link-0.5.1/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1218 2023-06-28 11:18:43.000000 django-ckeditor-link-0.5.1/setup.py
```

### Comparing `django-ckeditor-link-0.5.0/CHANGELOG.txt` & `django-ckeditor-link-0.5.1/CHANGELOG.txt`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,17 @@
 ==== 0.4.5 (under development) ===
 
 - ?
 
+==== 0.5.1 (2023-06-28) ===
+
+- introduce CKEDITOR_LINK_MODEL_USE_FILER_ADDONS, to enable usage of
+  django-filer-addons.filer_gui.fields.FilerFileField in ckeditor_link.link_model
+  (instead of the default filer field).
+
 
 ==== 0.5.0 (2023-04-19) ===
 
 - add compatibility and tests for django 4.2
 
 
 ==== 0.4.4 (2022-10-17) ===
```

### Comparing `django-ckeditor-link-0.5.0/LICENSE` & `django-ckeditor-link-0.5.1/LICENSE`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/PKG-INFO` & `django-ckeditor-link-0.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: django-ckeditor-link
-Version: 0.5.0
+Version: 0.5.1
 Summary: Alternative link dialog for ckeditor 4, using django modeladmin forms.
 Home-page: http://github.com/bnzk/django-ckeditor-link
 Author: Ben Stähli
 Author-email: bnzk@bnzk.ch
 License: MIT
 Platform: OS Independent
 Classifier: Development Status :: 4 - Beta
@@ -176,35 +176,41 @@
     
 The actual value of `cms_page` will be formatted with the  python `format(**kwargs)` function, where kwargs are the link's
 data attributes and it's values (without `data-`).
 
 
 ## Settings
 
-CKEDITOR_LINK_MODEL
+CKEDITOR_LINK_MODEL (default: `None`)
 
     # needed when using the ckeditor_link_add_links template filter, otherwise not
     CKEDITOR_LINK_MODEL = 'my_app.models.LinkModel'
 
-CKEDITOR_LINK_ATTR_MODIFIERS
+CKEDITOR_LINK_USE_CMS_FILER (default: `True` if django-cms and django-filer in INSTALLED_APPS)
+
+    # when using the ckeditor_link.link_model app, enable cms and filer integration
+
+CKEDITOR_LINK_MODEL_USE_FILER_ADDONS (default: `False`)
+
+    # when using filer integration, use django-filer-addons.filer_gui admin field
+
+CKEDITOR_LINK_ATTR_MODIFIERS (default: `{'cms_page': '{cms_page_2}'}`)
 
     # needed when using the ckeditor_link_add_links template filter
     # used to combine multi widgets values, to be in a valid form. 
     # django-cms own "PageField" needs this
     CKEDITOR_LINK_ATTR_MODIFIERS = {
         'multi_widget_field': '{multi_widget_field_1}--{multi_widget_field_whatever}'
         'cms_page': '{cms_page_2}'
     }
 
 
 ## Django Compatibility
 
-Officialy supported is django 1.11 LTS and 2.0, 2.1 and 2.2 LTS.  As there is no magic, it will probably work with older django versions.
-
-Add a chart with compatibility, one day.
+Please refer to the CHANGELOG.txt for current supported django versions.
 
 ## Contribute
 
 Fork and code. Quickstart:
 
 ```shell
     pip install -r test_requirements.txt
```

### Comparing `django-ckeditor-link-0.5.0/README.md` & `django-ckeditor-link-0.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -157,35 +157,41 @@
     
 The actual value of `cms_page` will be formatted with the  python `format(**kwargs)` function, where kwargs are the link's
 data attributes and it's values (without `data-`).
 
 
 ## Settings
 
-CKEDITOR_LINK_MODEL
+CKEDITOR_LINK_MODEL (default: `None`)
 
     # needed when using the ckeditor_link_add_links template filter, otherwise not
     CKEDITOR_LINK_MODEL = 'my_app.models.LinkModel'
 
-CKEDITOR_LINK_ATTR_MODIFIERS
+CKEDITOR_LINK_USE_CMS_FILER (default: `True` if django-cms and django-filer in INSTALLED_APPS)
+
+    # when using the ckeditor_link.link_model app, enable cms and filer integration
+
+CKEDITOR_LINK_MODEL_USE_FILER_ADDONS (default: `False`)
+
+    # when using filer integration, use django-filer-addons.filer_gui admin field
+
+CKEDITOR_LINK_ATTR_MODIFIERS (default: `{'cms_page': '{cms_page_2}'}`)
 
     # needed when using the ckeditor_link_add_links template filter
     # used to combine multi widgets values, to be in a valid form. 
     # django-cms own "PageField" needs this
     CKEDITOR_LINK_ATTR_MODIFIERS = {
         'multi_widget_field': '{multi_widget_field_1}--{multi_widget_field_whatever}'
         'cms_page': '{cms_page_2}'
     }
 
 
 ## Django Compatibility
 
-Officialy supported is django 1.11 LTS and 2.0, 2.1 and 2.2 LTS.  As there is no magic, it will probably work with older django versions.
-
-Add a chart with compatibility, one day.
+Please refer to the CHANGELOG.txt for current supported django versions.
 
 ## Contribute
 
 Fork and code. Quickstart:
 
 ```shell
     pip install -r test_requirements.txt
```

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/admin.py` & `django-ckeditor-link-0.5.1/ckeditor_link/admin.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/link_model/conf.py` & `django-ckeditor-link-0.5.1/ckeditor_link/link_model/conf.py`

 * *Files 3% similar despite different names*

```diff
@@ -8,14 +8,20 @@
 
 CKEDITOR_LINK_USE_CMS_FILER = getattr(
     settings,
     'CKEDITOR_LINK_USE_CMS_FILER',
     use
 )
 
+CKEDITOR_LINK_MODEL_USE_FILER_ADDONS = getattr(
+    settings,
+    'CKEDITOR_LINK_MODEL_USE_FILER_ADDONS',
+    False,
+)
+
 CKEDITOR_LINK_STYLE_CHOICES = getattr(
     settings, 'CKEDITOR_LINK_STYLE_CHOICES', (
         ('', _("Default")),
         ('button', _("Button")),
     )
 )
```

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/link_model/models.py` & `django-ckeditor-link-0.5.1/ckeditor_link/link_model/models.py`

 * *Files 4% similar despite different names*

```diff
@@ -8,14 +8,15 @@
 from django.conf import settings
 from django.db import models
 from django.utils.translation import gettext_lazy as _
 
 from .conf import (
     CKEDITOR_LINK_TYPE_CHOICES,
     CKEDITOR_LINK_USE_CMS_FILER,
+    CKEDITOR_LINK_MODEL_USE_FILER_ADDONS,
 )
 
 # dropped in favour of builtins/str, see above
 # try:
 #     unicode('')
 # except NameError:
 #     unicode = str
@@ -143,15 +144,19 @@
     """
     pass
 
 
 if CKEDITOR_LINK_USE_CMS_FILER:
 
     from cms.models.fields import PageField
-    from filer.fields.file import FilerFileField
+    print(CKEDITOR_LINK_MODEL_USE_FILER_ADDONS)
+    if CKEDITOR_LINK_MODEL_USE_FILER_ADDONS:
+        from filer_addons.filer_gui.fields import FilerFileField
+    else:
+        from filer.fields.file import FilerFileField
 
     class CMSFilerLinkBase(LinkBase):  # noqa
         cms_page = PageField(
             null=True,
             on_delete=models.SET_NULL,
             related_name="%(app_label)s_%(class)s_set",
             blank=True,
```

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/management/commands/cmsplugin2ckeditor_link.py` & `django-ckeditor-link-0.5.1/ckeditor_link/management/commands/cmsplugin2ckeditor_link.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/dialogs/djangolink.js` & `django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/dialogs/djangolink.js`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_dialog.js` & `django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_dialog.js`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_plugin.js` & `django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_plugin.js`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/examples-not-used/cmsplugin_example.js` & `django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/examples-not-used/cmsplugin_example.js`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/plugin.js` & `django-ckeditor-link-0.5.1/ckeditor_link/static/ckeditor/ckeditor/plugins/djangolink/plugin.js`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/dialogs/djangolink.js` & `django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/dialogs/djangolink.js`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_dialog.js` & `django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_dialog.js`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_plugin.js` & `django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/examples-not-used/ckeditor_original_link_plugin.js`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/examples-not-used/cmsplugin_example.js` & `django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/examples-not-used/cmsplugin_example.js`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/plugin.js` & `django-ckeditor-link-0.5.1/ckeditor_link/static/djangocms_text_ckeditor/ckeditor/plugins/djangolink/plugin.js`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/templatetags/ckeditor_link_tags.py` & `django-ckeditor-link-0.5.1/ckeditor_link/templatetags/ckeditor_link_tags.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/tests/settings.py` & `django-ckeditor-link-0.5.1/ckeditor_link/tests/settings.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/admin.py` & `django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/admin.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/migrations/0001_initial.py` & `django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/migrations/0001_initial.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/migrations/0002_auto_20161128_1458.py` & `django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/migrations/0002_auto_20161128_1458.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/migrations/0003_cmsfilerlinkmodel_contriblinkmodel.py` & `django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/migrations/0003_cmsfilerlinkmodel_contriblinkmodel.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/migrations/0004_auto_20210412_0750.py` & `django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/migrations/0004_auto_20210412_0750.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/tests/test_app/models.py` & `django-ckeditor-link-0.5.1/ckeditor_link/tests/test_app/models.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/tests/test_editor.py` & `django-ckeditor-link-0.5.1/ckeditor_link/tests/test_editor.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/tests/test_link_model.py` & `django-ckeditor-link-0.5.1/ckeditor_link/tests/test_link_model.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/tests/test_templatetag.py` & `django-ckeditor-link-0.5.1/ckeditor_link/tests/test_templatetag.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/tests/urls.py` & `django-ckeditor-link-0.5.1/ckeditor_link/tests/urls.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/ckeditor_link/tests/utils/selenium_utils.py` & `django-ckeditor-link-0.5.1/ckeditor_link/tests/utils/selenium_utils.py`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/django_ckeditor_link.egg-info/PKG-INFO` & `django-ckeditor-link-0.5.1/django_ckeditor_link.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: django-ckeditor-link
-Version: 0.5.0
+Version: 0.5.1
 Summary: Alternative link dialog for ckeditor 4, using django modeladmin forms.
 Home-page: http://github.com/bnzk/django-ckeditor-link
 Author: Ben Stähli
 Author-email: bnzk@bnzk.ch
 License: MIT
 Platform: OS Independent
 Classifier: Development Status :: 4 - Beta
@@ -176,35 +176,41 @@
     
 The actual value of `cms_page` will be formatted with the  python `format(**kwargs)` function, where kwargs are the link's
 data attributes and it's values (without `data-`).
 
 
 ## Settings
 
-CKEDITOR_LINK_MODEL
+CKEDITOR_LINK_MODEL (default: `None`)
 
     # needed when using the ckeditor_link_add_links template filter, otherwise not
     CKEDITOR_LINK_MODEL = 'my_app.models.LinkModel'
 
-CKEDITOR_LINK_ATTR_MODIFIERS
+CKEDITOR_LINK_USE_CMS_FILER (default: `True` if django-cms and django-filer in INSTALLED_APPS)
+
+    # when using the ckeditor_link.link_model app, enable cms and filer integration
+
+CKEDITOR_LINK_MODEL_USE_FILER_ADDONS (default: `False`)
+
+    # when using filer integration, use django-filer-addons.filer_gui admin field
+
+CKEDITOR_LINK_ATTR_MODIFIERS (default: `{'cms_page': '{cms_page_2}'}`)
 
     # needed when using the ckeditor_link_add_links template filter
     # used to combine multi widgets values, to be in a valid form. 
     # django-cms own "PageField" needs this
     CKEDITOR_LINK_ATTR_MODIFIERS = {
         'multi_widget_field': '{multi_widget_field_1}--{multi_widget_field_whatever}'
         'cms_page': '{cms_page_2}'
     }
 
 
 ## Django Compatibility
 
-Officialy supported is django 1.11 LTS and 2.0, 2.1 and 2.2 LTS.  As there is no magic, it will probably work with older django versions.
-
-Add a chart with compatibility, one day.
+Please refer to the CHANGELOG.txt for current supported django versions.
 
 ## Contribute
 
 Fork and code. Quickstart:
 
 ```shell
     pip install -r test_requirements.txt
```

### Comparing `django-ckeditor-link-0.5.0/django_ckeditor_link.egg-info/SOURCES.txt` & `django-ckeditor-link-0.5.1/django_ckeditor_link.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `django-ckeditor-link-0.5.0/setup.py` & `django-ckeditor-link-0.5.1/setup.py`

 * *Files identical despite different names*


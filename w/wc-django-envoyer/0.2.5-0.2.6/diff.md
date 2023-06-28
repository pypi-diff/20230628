# Comparing `tmp/wc-django-envoyer-0.2.5.tar.gz` & `tmp/wc-django-envoyer-0.2.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "wc-django-envoyer-0.2.5.tar", last modified: Wed Jun 21 13:53:23 2023, max compression
+gzip compressed data, was "wc-django-envoyer-0.2.6.tar", last modified: Wed Jun 28 09:12:27 2023, max compression
```

## Comparing `wc-django-envoyer-0.2.5.tar` & `wc-django-envoyer-0.2.6.tar`

### file list

```diff
@@ -1,78 +1,467 @@
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.060581 wc-django-envoyer-0.2.5/
--rwxrwxr-x   0 preusx    (1000) preusx    (1000)      487 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/CHANGELOG.md
--rwxrwxr-x   0 preusx    (1000) preusx    (1000)     1072 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/LICENSE
--rwxrwxr-x   0 preusx    (1000) preusx    (1000)      153 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/MANIFEST.in
--rwxrwxr-x   0 preusx    (1000) preusx    (1000)     1250 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/Makefile
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     7472 2023-06-21 13:53:23.060581 wc-django-envoyer-0.2.5/PKG-INFO
--rwxrwxr-x   0 preusx    (1000) preusx    (1000)     6431 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/README.md
--rwxrwxr-x   0 preusx    (1000) preusx    (1000)       79 2023-06-21 13:53:23.060581 wc-django-envoyer-0.2.5/setup.cfg
--rwxrwxr-x   0 preusx    (1000) preusx    (1000)     1762 2023-06-21 13:52:48.000000 wc-django-envoyer-0.2.5/setup.py
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.056581 wc-django-envoyer-0.2.5/tests/
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     2192 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/tests/test_celery.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     3981 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/tests/test_run.py
--rwxrwxr-x   0 preusx    (1000) preusx    (1000)      593 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/tox.ini
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.056581 wc-django-envoyer-0.2.5/wc_django_envoyer.egg-info/
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     7472 2023-06-21 13:53:23.000000 wc-django-envoyer-0.2.5/wc_django_envoyer.egg-info/PKG-INFO
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     1919 2023-06-21 13:53:23.000000 wc-django-envoyer-0.2.5/wc_django_envoyer.egg-info/SOURCES.txt
--rw-rw-r--   0 preusx    (1000) preusx    (1000)        1 2023-06-21 13:53:23.000000 wc-django-envoyer-0.2.5/wc_django_envoyer.egg-info/dependency_links.txt
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      285 2023-06-21 13:53:23.000000 wc-django-envoyer-0.2.5/wc_django_envoyer.egg-info/requires.txt
--rw-rw-r--   0 preusx    (1000) preusx    (1000)       12 2023-06-21 13:53:23.000000 wc-django-envoyer-0.2.5/wc_django_envoyer.egg-info/top_level.txt
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.056581 wc-django-envoyer-0.2.5/wcd_envoyer/
--rwxrwxr-x   0 preusx    (1000) preusx    (1000)      453 2023-06-21 13:53:02.000000 wc-django-envoyer-0.2.5/wcd_envoyer/__init__.py
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.056581 wc-django-envoyer-0.2.5/wcd_envoyer/admin/
--rw-rw-r--   0 preusx    (1000) preusx    (1000)       73 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/admin/__init__.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      474 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/admin/channels.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      376 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/admin/forms.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     1779 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/admin/messages.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     2889 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/admin/templates.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     2320 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/admin/utils.py
--rwxrwxr-x   0 preusx    (1000) preusx    (1000)      322 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/apps.py
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.060581 wc-django-envoyer-0.2.5/wcd_envoyer/channels/
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      102 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/channels/__init__.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     5692 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/channels/backend.py
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.060581 wc-django-envoyer-0.2.5/wcd_envoyer/channels/backends/
--rw-rw-r--   0 preusx    (1000) preusx    (1000)        0 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/channels/backends/__init__.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      952 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/channels/backends/console.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     4478 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/channels/backends/django_sendmail.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      852 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/channels/forms.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     1236 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/channels/registry_base.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      250 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/channels/renderers.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      560 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/conf.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      471 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/const.py
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.060581 wc-django-envoyer-0.2.5/wcd_envoyer/contrib/
--rw-rw-r--   0 preusx    (1000) preusx    (1000)        0 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/contrib/__init__.py
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.060581 wc-django-envoyer-0.2.5/wcd_envoyer/contrib/celery/
--rw-rw-r--   0 preusx    (1000) preusx    (1000)        0 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/contrib/celery/__init__.py
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.060581 wc-django-envoyer-0.2.5/wcd_envoyer/contrib/celery/services/
--rw-rw-r--   0 preusx    (1000) preusx    (1000)        0 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/contrib/celery/services/__init__.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     1191 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/contrib/celery/services/sender.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     1186 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/contrib/celery/shortcuts.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      640 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/contrib/celery/tasks.py
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.060581 wc-django-envoyer-0.2.5/wcd_envoyer/contrib/pxd_actions_tracker/
--rw-rw-r--   0 preusx    (1000) preusx    (1000)       89 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/contrib/pxd_actions_tracker/__init__.py
--rwxrwxr-x   0 preusx    (1000) preusx    (1000)      393 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/contrib/pxd_actions_tracker/apps.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      386 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/contrib/pxd_actions_tracker/handlers.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     1261 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/contrib/pxd_actions_tracker/tracker.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     1441 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/events.py
--rwxrwxr-x   0 preusx    (1000) preusx    (1000)       40 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/exceptions.py
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.060581 wc-django-envoyer-0.2.5/wcd_envoyer/migrations/
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     3457 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/migrations/0001_initial.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     1428 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/migrations/0002_auto_20230505_0852.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)        0 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/migrations/__init__.py
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.060581 wc-django-envoyer-0.2.5/wcd_envoyer/models/
--rw-rw-r--   0 preusx    (1000) preusx    (1000)       69 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/models/__init__.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      841 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/models/channels.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     2651 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/models/messages.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      415 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/models/utils.py
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.060581 wc-django-envoyer-0.2.5/wcd_envoyer/services/
--rw-rw-r--   0 preusx    (1000) preusx    (1000)        0 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/services/__init__.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     8672 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/services/sender.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      784 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/services/templates_resolver.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      935 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/shortcuts.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      129 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/signals.py
-drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-21 13:53:23.060581 wc-django-envoyer-0.2.5/wcd_envoyer/utils/
--rw-rw-r--   0 preusx    (1000) preusx    (1000)       93 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/utils/__init__.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     1514 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/utils/functional.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)     1030 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/utils/models.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      489 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/utils/registry.py
--rw-rw-r--   0 preusx    (1000) preusx    (1000)      855 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.5/wcd_envoyer/utils/types.py
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.249338 wc-django-envoyer-0.2.6/
+-rwxrwxr-x   0 preusx    (1000) preusx    (1000)      487 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/CHANGELOG.md
+-rwxrwxr-x   0 preusx    (1000) preusx    (1000)     1072 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/LICENSE
+-rwxrwxr-x   0 preusx    (1000) preusx    (1000)      153 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/MANIFEST.in
+-rwxrwxr-x   0 preusx    (1000) preusx    (1000)     1250 2023-06-28 09:11:47.000000 wc-django-envoyer-0.2.6/Makefile
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     7472 2023-06-28 09:12:27.249338 wc-django-envoyer-0.2.6/PKG-INFO
+-rwxrwxr-x   0 preusx    (1000) preusx    (1000)     6431 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/README.md
+-rwxrwxr-x   0 preusx    (1000) preusx    (1000)       79 2023-06-28 09:12:27.249338 wc-django-envoyer-0.2.6/setup.cfg
+-rwxrwxr-x   0 preusx    (1000) preusx    (1000)     1762 2023-06-22 11:31:13.000000 wc-django-envoyer-0.2.6/setup.py
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.221339 wc-django-envoyer-0.2.6/tests/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     2192 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/tests/test_celery.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3981 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/tests/test_run.py
+-rwxrwxr-x   0 preusx    (1000) preusx    (1000)      593 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/tox.ini
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.221339 wc-django-envoyer-0.2.6/wc_django_envoyer.egg-info/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     7472 2023-06-28 09:12:27.000000 wc-django-envoyer-0.2.6/wc_django_envoyer.egg-info/PKG-INFO
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)    10549 2023-06-28 09:12:27.000000 wc-django-envoyer-0.2.6/wc_django_envoyer.egg-info/SOURCES.txt
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)        1 2023-06-28 09:12:27.000000 wc-django-envoyer-0.2.6/wc_django_envoyer.egg-info/dependency_links.txt
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      285 2023-06-28 09:12:27.000000 wc-django-envoyer-0.2.6/wc_django_envoyer.egg-info/requires.txt
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)       12 2023-06-28 09:12:27.000000 wc-django-envoyer-0.2.6/wc_django_envoyer.egg-info/top_level.txt
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.221339 wc-django-envoyer-0.2.6/wcd_envoyer/
+-rwxrwxr-x   0 preusx    (1000) preusx    (1000)      453 2023-06-28 09:12:14.000000 wc-django-envoyer-0.2.6/wcd_envoyer/__init__.py
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.221339 wc-django-envoyer-0.2.6/wcd_envoyer/admin/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)       73 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/admin/__init__.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      474 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/admin/channels.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      376 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/admin/forms.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     1779 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/admin/messages.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     2889 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/admin/templates.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     2320 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/admin/utils.py
+-rwxrwxr-x   0 preusx    (1000) preusx    (1000)      322 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/apps.py
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.221339 wc-django-envoyer-0.2.6/wcd_envoyer/channels/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      102 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/channels/__init__.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     5692 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/channels/backend.py
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.221339 wc-django-envoyer-0.2.6/wcd_envoyer/channels/backends/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)        0 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/channels/backends/__init__.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      952 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/channels/backends/console.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     4478 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/channels/backends/django_sendmail.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      852 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/channels/forms.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     1236 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/channels/registry_base.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      250 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/channels/renderers.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      560 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/conf.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      471 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/const.py
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.221339 wc-django-envoyer-0.2.6/wcd_envoyer/contrib/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)        0 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/contrib/__init__.py
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.221339 wc-django-envoyer-0.2.6/wcd_envoyer/contrib/celery/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)        0 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/contrib/celery/__init__.py
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.221339 wc-django-envoyer-0.2.6/wcd_envoyer/contrib/celery/services/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)        0 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/contrib/celery/services/__init__.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     1191 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/contrib/celery/services/sender.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     1186 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/contrib/celery/shortcuts.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      640 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/contrib/celery/tasks.py
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.221339 wc-django-envoyer-0.2.6/wcd_envoyer/contrib/pxd_actions_tracker/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)       89 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/contrib/pxd_actions_tracker/__init__.py
+-rwxrwxr-x   0 preusx    (1000) preusx    (1000)      393 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/contrib/pxd_actions_tracker/apps.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      386 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/contrib/pxd_actions_tracker/handlers.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     1261 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/contrib/pxd_actions_tracker/tracker.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     1441 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/events.py
+-rwxrwxr-x   0 preusx    (1000) preusx    (1000)       40 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/exceptions.py
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.205339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/af/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.221339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/af/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/af/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/af/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.205339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ar/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.225339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ar/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      463 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ar/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3985 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ar/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.205339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ar-dz/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.225339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ar-dz/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ar-dz/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ar-dz/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.205339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ast/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.225339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ast/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ast/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ast/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.205339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/az/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.225339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/az/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/az/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/az/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.205339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/be/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.225339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/be/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      518 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/be/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     4043 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/be/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.205339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/bg/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.225339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/bg/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/bg/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/bg/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.205339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/bn/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.225339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/bn/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/bn/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/bn/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/br/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.225339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/br/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      671 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/br/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     4202 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/br/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/bs/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.225339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/bs/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      454 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/bs/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3976 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/bs/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ca/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.225339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ca/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ca/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ca/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/cs/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.225339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/cs/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      460 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/cs/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3982 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/cs/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/cy/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.225339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/cy/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      425 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/cy/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3947 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/cy/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/da/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.225339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/da/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/da/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/da/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/de/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.225339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/de/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/de/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/de/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/dsb/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/dsb/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      432 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/dsb/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3954 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/dsb/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/el/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/el/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/el/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/el/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/en/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/en/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/en/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/en/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/en-au/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/en-au/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/en-au/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/en-au/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/en-gb/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/en-gb/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/en-gb/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/en-gb/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/eo/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/eo/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/eo/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/eo/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-ar/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-ar/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-ar/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-ar/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-co/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-co/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-co/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-co/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-mx/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-mx/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-mx/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-mx/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-ni/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-ni/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-ni/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-ni/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-ve/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-ve/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-ve/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/es-ve/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/et/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/et/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/et/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/et/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/eu/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/eu/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/eu/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/eu/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fa/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fa/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      379 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fa/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3898 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fa/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fi/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fi/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fi/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fi/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fr/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.229339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fr/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      379 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fr/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3898 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fr/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fy/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fy/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fy/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/fy/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ga/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ga/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      418 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ga/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3940 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ga/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/gd/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/gd/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      441 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/gd/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3963 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/gd/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/gl/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/gl/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/gl/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/gl/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/he/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/he/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      474 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/he/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3996 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/he/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hi/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hi/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hi/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hi/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hr/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hr/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      452 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hr/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3974 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hr/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hsb/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hsb/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      432 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hsb/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3954 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hsb/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hu/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hu/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hu/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hu/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hy/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hy/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hy/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/hy/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ia/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ia/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ia/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ia/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/id/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/id/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      373 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/id/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3892 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/id/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.209339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ig/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ig/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ig/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ig/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/io/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/io/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/io/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/io/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/is/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/is/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      402 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/is/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3921 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/is/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/it/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/it/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/it/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/it/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ja/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.233339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ja/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      373 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ja/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3892 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ja/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ka/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ka/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      378 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ka/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3897 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ka/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/kab/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/kab/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/kab/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/kab/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/kk/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/kk/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      373 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/kk/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3892 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/kk/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/km/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/km/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      373 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/km/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3892 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/km/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/kn/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/kn/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      373 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/kn/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3892 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/kn/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ko/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ko/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      373 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ko/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3892 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ko/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ky/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ky/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ky/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ky/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/lb/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/lb/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/lb/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/lb/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/lt/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/lt/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      511 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/lt/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     4036 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/lt/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/lv/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/lv/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      415 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/lv/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3937 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/lv/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/mk/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/mk/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      410 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/mk/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3929 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/mk/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ml/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ml/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ml/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ml/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/mn/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/mn/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/mn/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/mn/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/mr/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/mr/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/mr/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/mr/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ms/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ms/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ms/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ms/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/my/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/my/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      373 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/my/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3892 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/my/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/nb/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.237339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/nb/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/nb/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/nb/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ne/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ne/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ne/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ne/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/nl/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/nl/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/nl/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/nl/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/nn/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/nn/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/nn/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/nn/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/os/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/os/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/os/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/os/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pa/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pa/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pa/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pa/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pl/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pl/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      526 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pl/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     4051 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pl/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pt/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pt/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pt/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pt/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pt-br/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pt-br/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pt-br/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/pt-br/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ro/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ro/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      421 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ro/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3943 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ro/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.213339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ru/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ru/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      518 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ru/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     4043 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ru/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sk/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sk/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      455 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sk/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3977 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sk/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sl/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sl/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      432 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sl/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3954 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sl/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sq/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sq/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sq/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sq/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sr/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sr/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      454 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sr/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3976 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sr/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sr-latn/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sr-latn/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sr-latn/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sr-latn/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sv/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sv/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sv/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sv/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sw/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sw/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sw/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/sw/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ta/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ta/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ta/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ta/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/te/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/te/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/te/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/te/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tg/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.241339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tg/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tg/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tg/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/th/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.245339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/th/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      373 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/th/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3892 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/th/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tk/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.245339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tk/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tk/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tk/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tr/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.245339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tr/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      379 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tr/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3898 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tr/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tt/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.245339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tt/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      373 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tt/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3892 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/tt/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/udm/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.245339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/udm/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      373 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/udm/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3892 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/udm/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/uk/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.245339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/uk/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      602 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/uk/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     4130 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/uk/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ur/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.245339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ur/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      380 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ur/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3899 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/ur/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/uz/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.245339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/uz/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/uz/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/uz/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/vi/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.245339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/vi/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      373 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/vi/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3892 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/vi/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/zh-hans/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.245339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/zh-hans/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/zh-hans/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/zh-hans/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.217339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/zh-hant/
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.245339 wc-django-envoyer-0.2.6/wcd_envoyer/locale/zh-hant/LC_MESSAGES/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      337 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/zh-hant/LC_MESSAGES/django.mo
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3853 2023-06-28 09:11:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/locale/zh-hant/LC_MESSAGES/django.po
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.245339 wc-django-envoyer-0.2.6/wcd_envoyer/migrations/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     3457 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/migrations/0001_initial.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     1428 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/migrations/0002_auto_20230505_0852.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)        0 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/migrations/__init__.py
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.245339 wc-django-envoyer-0.2.6/wcd_envoyer/models/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)       69 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/models/__init__.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      841 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/models/channels.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     2651 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/models/messages.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      415 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/models/utils.py
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.245339 wc-django-envoyer-0.2.6/wcd_envoyer/services/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)        0 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/services/__init__.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     8672 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/services/sender.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      784 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/services/templates_resolver.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      935 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/shortcuts.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      129 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/signals.py
+drwxrwxr-x   0 preusx    (1000) preusx    (1000)        0 2023-06-28 09:12:27.249338 wc-django-envoyer-0.2.6/wcd_envoyer/utils/
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)       93 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/utils/__init__.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     1514 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/utils/functional.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)     1030 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/utils/models.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      489 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/utils/registry.py
+-rw-rw-r--   0 preusx    (1000) preusx    (1000)      855 2023-06-07 12:35:50.000000 wc-django-envoyer-0.2.6/wcd_envoyer/utils/types.py
```

### Comparing `wc-django-envoyer-0.2.5/LICENSE` & `wc-django-envoyer-0.2.6/LICENSE`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/Makefile` & `wc-django-envoyer-0.2.6/Makefile`

 * *Files 3% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 package-publish:
 	rm -rf ./dist
 	python setup.py sdist
 	twine upload dist/*
 
 translations:
-	mkdir -p wcd_2factor/locale
+	mkdir -p wcd_envoyer/locale
 	django-admin.py makemessages --ignore=pilot/* --ignore=tests/* --ignore=dist/* \
 		-l af \
 		-l ar \
 		-l ar-dz \
 		-l ast \
 		-l az \
 		-l bg \
```

### Comparing `wc-django-envoyer-0.2.5/PKG-INFO` & `wc-django-envoyer-0.2.6/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: wc-django-envoyer
-Version: 0.2.5
+Version: 0.2.6
 Summary: Message sender to different channels.
 Author: WebCase
 Author-email: info@webcase.studio
 License: MIT License
 Classifier: Development Status :: 2 - Pre-Alpha
 Classifier: Programming Language :: Python :: 3
 Classifier: Intended Audience :: Developers
```

### Comparing `wc-django-envoyer-0.2.5/README.md` & `wc-django-envoyer-0.2.6/README.md`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/setup.py` & `wc-django-envoyer-0.2.6/setup.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/tests/test_celery.py` & `wc-django-envoyer-0.2.6/tests/test_celery.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/tests/test_run.py` & `wc-django-envoyer-0.2.6/tests/test_run.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/tox.ini` & `wc-django-envoyer-0.2.6/tox.ini`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wc_django_envoyer.egg-info/PKG-INFO` & `wc-django-envoyer-0.2.6/wc_django_envoyer.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: wc-django-envoyer
-Version: 0.2.5
+Version: 0.2.6
 Summary: Message sender to different channels.
 Author: WebCase
 Author-email: info@webcase.studio
 License: MIT License
 Classifier: Development Status :: 2 - Pre-Alpha
 Classifier: Programming Language :: Python :: 3
 Classifier: Intended Audience :: Developers
```

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/admin/messages.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/admin/messages.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/admin/templates.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/admin/templates.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/admin/utils.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/admin/utils.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/channels/backend.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/channels/backend.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/channels/backends/console.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/channels/backends/console.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/channels/backends/django_sendmail.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/channels/backends/django_sendmail.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/channels/forms.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/channels/forms.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/channels/registry_base.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/channels/registry_base.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/conf.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/conf.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/contrib/celery/services/sender.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/contrib/celery/services/sender.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/contrib/celery/shortcuts.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/contrib/celery/shortcuts.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/contrib/celery/tasks.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/contrib/celery/tasks.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/contrib/pxd_actions_tracker/tracker.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/contrib/pxd_actions_tracker/tracker.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/events.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/events.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/migrations/0001_initial.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/migrations/0001_initial.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/migrations/0002_auto_20230505_0852.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/migrations/0002_auto_20230505_0852.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/models/channels.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/models/channels.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/models/messages.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/models/messages.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/services/sender.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/services/sender.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/services/templates_resolver.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/services/templates_resolver.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/shortcuts.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/shortcuts.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/utils/functional.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/utils/functional.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/utils/models.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/utils/models.py`

 * *Files identical despite different names*

### Comparing `wc-django-envoyer-0.2.5/wcd_envoyer/utils/types.py` & `wc-django-envoyer-0.2.6/wcd_envoyer/utils/types.py`

 * *Files identical despite different names*


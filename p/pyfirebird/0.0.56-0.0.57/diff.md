# Comparing `tmp/pyfirebird-0.0.56.tar.gz` & `tmp/pyfirebird-0.0.57.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyfirebird-0.0.56.tar", last modified: Wed Jun 28 09:55:50 2023, max compression
+gzip compressed data, was "pyfirebird-0.0.57.tar", last modified: Wed Jun 28 10:45:25 2023, max compression
```

## Comparing `pyfirebird-0.0.56.tar` & `pyfirebird-0.0.57.tar`

### file list

```diff
@@ -1,67 +1,67 @@
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.549962 pyfirebird-0.0.56/
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      368 2023-06-28 09:55:50.549962 pyfirebird-0.0.56/PKG-INFO
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        8 2023-04-30 05:34:25.000000 pyfirebird-0.0.56/README.md
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       38 2023-06-28 09:55:50.549962 pyfirebird-0.0.56/setup.cfg
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     1303 2023-06-28 09:54:54.000000 pyfirebird-0.0.56/setup.py
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.545962 pyfirebird-0.0.56/src/
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.545962 pyfirebird-0.0.56/src/firebird/
--rw-r--r--   0 stonezhong  (1000) stonezhong  (1000)      169 2023-06-26 09:30:30.000000 pyfirebird-0.0.56/src/firebird/__init__.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)    11633 2023-06-26 09:30:32.000000 pyfirebird-0.0.56/src/firebird/base.py
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.545962 pyfirebird-0.0.56/src/firebird/cmd_tools/
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-26 09:30:31.000000 pyfirebird-0.0.56/src/firebird/cmd_tools/__init__.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     2676 2023-06-28 09:33:03.000000 pyfirebird-0.0.56/src/firebird/cmd_tools/executor.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     4809 2023-06-28 09:32:37.000000 pyfirebird-0.0.56/src/firebird/cmd_tools/executor_impl.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      649 2023-06-26 09:30:31.000000 pyfirebird-0.0.56/src/firebird/cmd_tools/fbconsole.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     3505 2023-06-28 09:30:24.000000 pyfirebird-0.0.56/src/firebird/cmd_tools/pipeline.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     4458 2023-06-28 09:33:13.000000 pyfirebird-0.0.56/src/firebird/cmd_tools/pipeline_impl.py
--rw-r--r--   0 stonezhong  (1000) stonezhong  (1000)     2972 2023-06-26 09:30:31.000000 pyfirebird-0.0.56/src/firebird/rabbitmq.py
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.545962 pyfirebird-0.0.56/src/firebird/utils/
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       60 2023-06-26 09:30:31.000000 pyfirebird-0.0.56/src/firebird/utils/__init__.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     4359 2023-06-26 09:30:31.000000 pyfirebird-0.0.56/src/firebird/utils/checkpoint.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     6614 2023-06-28 09:31:41.000000 pyfirebird-0.0.56/src/firebird/zkdb.py
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.545962 pyfirebird-0.0.56/src/firebirdconsole/
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-26 09:30:43.000000 pyfirebird-0.0.56/src/firebirdconsole/__init__.py
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.545962 pyfirebird-0.0.56/src/firebirdconsole/firebirdconsole/
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-26 09:30:43.000000 pyfirebird-0.0.56/src/firebirdconsole/firebirdconsole/__init__.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      407 2023-06-26 09:30:43.000000 pyfirebird-0.0.56/src/firebirdconsole/firebirdconsole/asgi.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     3803 2023-06-26 09:30:43.000000 pyfirebird-0.0.56/src/firebirdconsole/firebirdconsole/settings.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      836 2023-06-26 09:30:43.000000 pyfirebird-0.0.56/src/firebirdconsole/firebirdconsole/urls.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      407 2023-06-26 09:30:43.000000 pyfirebird-0.0.56/src/firebirdconsole/firebirdconsole/wsgi.py
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.549962 pyfirebird-0.0.56/src/firebirdconsole/ui/
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-26 09:30:35.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/__init__.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       63 2023-06-26 09:30:35.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/admin.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      152 2023-06-26 09:30:35.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/apps.py
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.549962 pyfirebird-0.0.56/src/firebirdconsole/ui/migrations/
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-26 09:30:32.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/migrations/__init__.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       57 2023-06-28 08:49:46.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/models.py
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.545962 pyfirebird-0.0.56/src/firebirdconsole/ui/static/
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.549962 pyfirebird-0.0.56/src/firebirdconsole/ui/static/images/
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)   126365 2023-06-26 09:30:41.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/static/images/logo.jpeg
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.549962 pyfirebird-0.0.56/src/firebirdconsole/ui/static/js-bundle/
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)  1554034 2023-06-28 09:41:29.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/static/js-bundle/home.js
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      271 2023-06-26 09:30:38.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/static/js-bundle/home.js.LICENSE.txt
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)  1670136 2023-06-28 09:41:29.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/static/js-bundle/pipeline.js
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      527 2023-06-26 09:30:35.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/static/js-bundle/pipeline.js.LICENSE.txt
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.549962 pyfirebird-0.0.56/src/firebirdconsole/ui/templates/
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     3817 2023-06-26 09:30:42.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/templates/application.html
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      217 2023-06-26 09:30:42.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/templates/index.html
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.549962 pyfirebird-0.0.56/src/firebirdconsole/ui/templatetags/
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-26 09:30:32.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/templatetags/__init__.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      639 2023-06-26 09:30:32.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/templatetags/app_filters.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       60 2023-06-26 09:30:42.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/tests.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      372 2023-06-28 00:42:35.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/urls.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      571 2023-06-26 09:30:42.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/view_tools.py
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.549962 pyfirebird-0.0.56/src/firebirdconsole/ui/views/
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       54 2023-06-26 09:30:43.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/views/__init__.py
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.549962 pyfirebird-0.0.56/src/firebirdconsole/ui/views/apis/
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       47 2023-06-28 00:42:11.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/views/apis/__init__.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     3666 2023-06-28 00:42:19.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/views/apis/main.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      288 2023-06-26 09:30:42.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/views/home.py
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      387 2023-06-26 09:30:43.000000 pyfirebird-0.0.56/src/firebirdconsole/ui/views/pipeline.py
-drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 09:55:50.549962 pyfirebird-0.0.56/src/pyfirebird.egg-info/
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      368 2023-06-28 09:55:50.000000 pyfirebird-0.0.56/src/pyfirebird.egg-info/PKG-INFO
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     1833 2023-06-28 09:55:50.000000 pyfirebird-0.0.56/src/pyfirebird.egg-info/SOURCES.txt
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        1 2023-06-28 09:55:50.000000 pyfirebird-0.0.56/src/pyfirebird.egg-info/dependency_links.txt
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      152 2023-06-28 09:55:50.000000 pyfirebird-0.0.56/src/pyfirebird.egg-info/entry_points.txt
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       72 2023-06-28 09:55:50.000000 pyfirebird-0.0.56/src/pyfirebird.egg-info/requires.txt
--rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       25 2023-06-28 09:55:50.000000 pyfirebird-0.0.56/src/pyfirebird.egg-info/top_level.txt
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.826068 pyfirebird-0.0.57/
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      368 2023-06-28 10:45:25.826068 pyfirebird-0.0.57/PKG-INFO
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        8 2023-04-30 05:34:25.000000 pyfirebird-0.0.57/README.md
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       38 2023-06-28 10:45:25.826068 pyfirebird-0.0.57/setup.cfg
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     1303 2023-06-28 10:43:38.000000 pyfirebird-0.0.57/setup.py
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.822068 pyfirebird-0.0.57/src/
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.822068 pyfirebird-0.0.57/src/firebird/
+-rw-r--r--   0 stonezhong  (1000) stonezhong  (1000)      169 2023-06-26 09:30:30.000000 pyfirebird-0.0.57/src/firebird/__init__.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)    11633 2023-06-26 09:30:32.000000 pyfirebird-0.0.57/src/firebird/base.py
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.822068 pyfirebird-0.0.57/src/firebird/cmd_tools/
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-26 09:30:31.000000 pyfirebird-0.0.57/src/firebird/cmd_tools/__init__.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     2676 2023-06-28 09:33:03.000000 pyfirebird-0.0.57/src/firebird/cmd_tools/executor.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     4809 2023-06-28 09:32:37.000000 pyfirebird-0.0.57/src/firebird/cmd_tools/executor_impl.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      649 2023-06-26 09:30:31.000000 pyfirebird-0.0.57/src/firebird/cmd_tools/fbconsole.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     3505 2023-06-28 09:30:24.000000 pyfirebird-0.0.57/src/firebird/cmd_tools/pipeline.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     4975 2023-06-28 10:42:50.000000 pyfirebird-0.0.57/src/firebird/cmd_tools/pipeline_impl.py
+-rw-r--r--   0 stonezhong  (1000) stonezhong  (1000)     2972 2023-06-26 09:30:31.000000 pyfirebird-0.0.57/src/firebird/rabbitmq.py
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.822068 pyfirebird-0.0.57/src/firebird/utils/
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       60 2023-06-26 09:30:31.000000 pyfirebird-0.0.57/src/firebird/utils/__init__.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     4359 2023-06-26 09:30:31.000000 pyfirebird-0.0.57/src/firebird/utils/checkpoint.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     6614 2023-06-28 09:31:41.000000 pyfirebird-0.0.57/src/firebird/zkdb.py
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.822068 pyfirebird-0.0.57/src/firebirdconsole/
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-26 09:30:43.000000 pyfirebird-0.0.57/src/firebirdconsole/__init__.py
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.822068 pyfirebird-0.0.57/src/firebirdconsole/firebirdconsole/
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-26 09:30:43.000000 pyfirebird-0.0.57/src/firebirdconsole/firebirdconsole/__init__.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      407 2023-06-26 09:30:43.000000 pyfirebird-0.0.57/src/firebirdconsole/firebirdconsole/asgi.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     3803 2023-06-26 09:30:43.000000 pyfirebird-0.0.57/src/firebirdconsole/firebirdconsole/settings.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      836 2023-06-26 09:30:43.000000 pyfirebird-0.0.57/src/firebirdconsole/firebirdconsole/urls.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      407 2023-06-26 09:30:43.000000 pyfirebird-0.0.57/src/firebirdconsole/firebirdconsole/wsgi.py
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.822068 pyfirebird-0.0.57/src/firebirdconsole/ui/
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-26 09:30:35.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/__init__.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       63 2023-06-26 09:30:35.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/admin.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      152 2023-06-26 09:30:35.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/apps.py
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.826068 pyfirebird-0.0.57/src/firebirdconsole/ui/migrations/
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-26 09:30:32.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/migrations/__init__.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       57 2023-06-28 08:49:46.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/models.py
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.822068 pyfirebird-0.0.57/src/firebirdconsole/ui/static/
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.826068 pyfirebird-0.0.57/src/firebirdconsole/ui/static/images/
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)   126365 2023-06-26 09:30:41.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/static/images/logo.jpeg
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.826068 pyfirebird-0.0.57/src/firebirdconsole/ui/static/js-bundle/
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)  1554034 2023-06-28 09:41:29.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/static/js-bundle/home.js
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      271 2023-06-26 09:30:38.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/static/js-bundle/home.js.LICENSE.txt
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)  1670136 2023-06-28 09:41:29.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/static/js-bundle/pipeline.js
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      527 2023-06-26 09:30:35.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/static/js-bundle/pipeline.js.LICENSE.txt
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.826068 pyfirebird-0.0.57/src/firebirdconsole/ui/templates/
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     3817 2023-06-26 09:30:42.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/templates/application.html
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      217 2023-06-26 09:30:42.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/templates/index.html
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.826068 pyfirebird-0.0.57/src/firebirdconsole/ui/templatetags/
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-26 09:30:32.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/templatetags/__init__.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      639 2023-06-26 09:30:32.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/templatetags/app_filters.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       60 2023-06-26 09:30:42.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/tests.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      372 2023-06-28 00:42:35.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/urls.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      571 2023-06-26 09:30:42.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/view_tools.py
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.826068 pyfirebird-0.0.57/src/firebirdconsole/ui/views/
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       54 2023-06-26 09:30:43.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/views/__init__.py
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.826068 pyfirebird-0.0.57/src/firebirdconsole/ui/views/apis/
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       47 2023-06-28 00:42:11.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/views/apis/__init__.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     3666 2023-06-28 00:42:19.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/views/apis/main.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      288 2023-06-26 09:30:42.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/views/home.py
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      387 2023-06-26 09:30:43.000000 pyfirebird-0.0.57/src/firebirdconsole/ui/views/pipeline.py
+drwxrwxr-x   0 stonezhong  (1000) stonezhong  (1000)        0 2023-06-28 10:45:25.826068 pyfirebird-0.0.57/src/pyfirebird.egg-info/
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      368 2023-06-28 10:45:25.000000 pyfirebird-0.0.57/src/pyfirebird.egg-info/PKG-INFO
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)     1833 2023-06-28 10:45:25.000000 pyfirebird-0.0.57/src/pyfirebird.egg-info/SOURCES.txt
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)        1 2023-06-28 10:45:25.000000 pyfirebird-0.0.57/src/pyfirebird.egg-info/dependency_links.txt
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)      152 2023-06-28 10:45:25.000000 pyfirebird-0.0.57/src/pyfirebird.egg-info/entry_points.txt
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       72 2023-06-28 10:45:25.000000 pyfirebird-0.0.57/src/pyfirebird.egg-info/requires.txt
+-rw-rw-r--   0 stonezhong  (1000) stonezhong  (1000)       25 2023-06-28 10:45:25.000000 pyfirebird-0.0.57/src/pyfirebird.egg-info/top_level.txt
```

### Comparing `pyfirebird-0.0.56/setup.py` & `pyfirebird-0.0.57/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 # The text of the README file
 with open(os.path.join(HERE, "README.md"), "r") as f:
     README = f.read()
 
 # This call to setup() does all the work
 setup(
     name="pyfirebird",
-    version="0.0.56",
+    version="0.0.57",
     description="Streaming Data Processing Framework",
     long_description=README,
     long_description_content_type="text/markdown",
     url="https://github.com/stonezhong/firebird",
     author="Stone Zhong",
     author_email="stonezhong@hotmail.com",
     license="MIT",
```

### Comparing `pyfirebird-0.0.56/src/firebird/base.py` & `pyfirebird-0.0.57/src/firebird/base.py`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebird/cmd_tools/executor.py` & `pyfirebird-0.0.57/src/firebird/cmd_tools/executor.py`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebird/cmd_tools/executor_impl.py` & `pyfirebird-0.0.57/src/firebird/cmd_tools/executor_impl.py`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebird/cmd_tools/fbconsole.py` & `pyfirebird-0.0.57/src/firebird/cmd_tools/fbconsole.py`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebird/cmd_tools/pipeline.py` & `pyfirebird-0.0.57/src/firebird/cmd_tools/pipeline.py`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebird/cmd_tools/pipeline_impl.py` & `pyfirebird-0.0.57/src/firebird/cmd_tools/pipeline_impl.py`

 * *Files 12% similar despite different names*

```diff
@@ -56,51 +56,70 @@
         pipeline = db.get_pipeline(pipeline_id)
 
     k8_config.load_kube_config()
     api = client.CoreV1Api()
     resp = api.delete_namespaced_deployment(
         name=pipeline_id,
         namespace=pipeline["namespace_name"],
+        pretty=True,
         body=client.V1DeleteOptions(
             propagation_policy="Foreground", grace_period_seconds=300
         ),
     )
+    print(resp)
+    resp = api.delete_namespaced_stateful_set(
+        name=f"{pipeline_id}-g",
+        namespace=pipeline["namespace_name"],
+        pretty=True,
+        body=client.V1DeleteOptions(
+            propagation_policy="Foreground", grace_period_seconds=300
+        ),
+    )
+    print(resp)
 
 
 def start_command(config, pipeline_id, replicas):
     with zkdb(**config['zookeeper']) as db:
         pipeline = db.get_pipeline(pipeline_id)
 
     environment = jinja2.Environment()
     template = environment.from_string("""\
 apiVersion: apps/v1
 kind: StatefulSet
 metadata:
-  name: {{pipeline_id}}
+  name: {{pipeline_id}}-g
   namespace: {{pipeline_namespace_name}}
   labels:
-    app: {{pipeline_id}}
+    app: {{pipeline_id}}-g
 spec:
   replicas: 1
   selector:
     matchLabels:
-      app: {{pipeline_id}}
+      app: {{pipeline_id}}-g
   template:
     metadata:
       labels:
-        app: {{pipeline_id}}
+        app: {{pipeline_id}}-g
     spec:
       containers:
-      - name: {{pipeline_id}}
+      - name: {{pipeline_id}}-g
         image: {{pipeline_image_name}}
         command: ["python", "-u"]
         args: ["/usr/local/lib/python3.11/site-packages/firebird/cmd_tools/executor.py", "-pid", "{{pipeline_id}}", "-rg"]
         volumeMounts:
           - name: checkpoint
             mountPath: /checkpoint
+  volumeClaimTemplates:
+    - metadata:
+        name: checkpoint
+      spec:
+        accessModes: [ "ReadWriteOnce" ]
+        resources:
+          requests:
+            storage: 20Mi
 ---
 apiVersion: apps/v1
 kind: Deployment
 metadata:
   name: {{pipeline_id}}
   namespace: {{pipeline_namespace_name}}
   labels:
```

### Comparing `pyfirebird-0.0.56/src/firebird/rabbitmq.py` & `pyfirebird-0.0.57/src/firebird/rabbitmq.py`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebird/utils/checkpoint.py` & `pyfirebird-0.0.57/src/firebird/utils/checkpoint.py`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebird/zkdb.py` & `pyfirebird-0.0.57/src/firebird/zkdb.py`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebirdconsole/firebirdconsole/settings.py` & `pyfirebird-0.0.57/src/firebirdconsole/firebirdconsole/settings.py`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebirdconsole/firebirdconsole/urls.py` & `pyfirebird-0.0.57/src/firebirdconsole/firebirdconsole/urls.py`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebirdconsole/ui/static/images/logo.jpeg` & `pyfirebird-0.0.57/src/firebirdconsole/ui/static/images/logo.jpeg`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebirdconsole/ui/static/js-bundle/home.js` & `pyfirebird-0.0.57/src/firebirdconsole/ui/static/js-bundle/home.js`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebirdconsole/ui/static/js-bundle/pipeline.js` & `pyfirebird-0.0.57/src/firebirdconsole/ui/static/js-bundle/pipeline.js`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebirdconsole/ui/static/js-bundle/pipeline.js.LICENSE.txt` & `pyfirebird-0.0.57/src/firebirdconsole/ui/static/js-bundle/pipeline.js.LICENSE.txt`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebirdconsole/ui/templates/application.html` & `pyfirebird-0.0.57/src/firebirdconsole/ui/templates/application.html`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebirdconsole/ui/templatetags/app_filters.py` & `pyfirebird-0.0.57/src/firebirdconsole/ui/templatetags/app_filters.py`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebirdconsole/ui/view_tools.py` & `pyfirebird-0.0.57/src/firebirdconsole/ui/view_tools.py`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/firebirdconsole/ui/views/apis/main.py` & `pyfirebird-0.0.57/src/firebirdconsole/ui/views/apis/main.py`

 * *Files identical despite different names*

### Comparing `pyfirebird-0.0.56/src/pyfirebird.egg-info/SOURCES.txt` & `pyfirebird-0.0.57/src/pyfirebird.egg-info/SOURCES.txt`

 * *Files identical despite different names*


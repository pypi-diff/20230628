# Comparing `tmp/etos_lib-3.2.1.tar.gz` & `tmp/etos_lib-3.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "etos_lib-3.2.1.tar", last modified: Fri Jun  9 08:22:40 2023, max compression
+gzip compressed data, was "etos_lib-3.2.2.tar", last modified: Wed Jun 28 12:45:08 2023, max compression
```

## Comparing `etos_lib-3.2.1.tar` & `etos_lib-3.2.2.tar`

### file list

```diff
@@ -1,67 +1,67 @@
-drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-09 08:22:40.065967 etos_lib-3.2.1/
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      591 2023-06-08 05:45:47.000000 etos_lib-3.2.1/.coveragerc
-drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-09 08:22:40.061967 etos_lib-3.2.1/.github/
-drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-09 08:22:40.061967 etos_lib-3.2.1/.github/workflows/
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      850 2023-06-08 05:45:47.000000 etos_lib-3.2.1/.github/workflows/main.yml
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      542 2023-06-08 05:45:47.000000 etos_lib-3.2.1/.gitignore
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      174 2023-06-08 05:45:47.000000 etos_lib-3.2.1/AUTHORS.rst
--rw-r--r--   0 tobiaspn (21118) axusers    (500)       37 2023-06-08 05:45:47.000000 etos_lib-3.2.1/CODEOWNERS
--rw-r--r--   0 tobiaspn (21118) axusers    (500)    10850 2023-06-08 05:45:47.000000 etos_lib-3.2.1/LICENSE.txt
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     1334 2023-06-09 08:22:40.065967 etos_lib-3.2.1/PKG-INFO
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      721 2023-06-08 05:45:47.000000 etos_lib-3.2.1/README.rst
-drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-09 08:22:40.061967 etos_lib-3.2.1/docs/
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     7610 2023-06-08 05:45:47.000000 etos_lib-3.2.1/docs/Makefile
-drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-09 08:22:40.061967 etos_lib-3.2.1/docs/_static/
--rw-r--r--   0 tobiaspn (21118) axusers    (500)       18 2023-06-08 05:45:47.000000 etos_lib-3.2.1/docs/_static/.gitignore
--rw-r--r--   0 tobiaspn (21118) axusers    (500)       41 2023-06-08 05:45:47.000000 etos_lib-3.2.1/docs/authors.rst
--rw-r--r--   0 tobiaspn (21118) axusers    (500)       43 2023-06-08 05:45:47.000000 etos_lib-3.2.1/docs/changelog.rst
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     9175 2023-06-08 05:45:47.000000 etos_lib-3.2.1/docs/conf.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      457 2023-06-08 05:45:47.000000 etos_lib-3.2.1/docs/index.rst
--rw-r--r--   0 tobiaspn (21118) axusers    (500)       74 2023-06-08 05:45:47.000000 etos_lib-3.2.1/docs/license.rst
--rw-r--r--   0 tobiaspn (21118) axusers    (500)       39 2023-06-08 05:45:47.000000 etos_lib-3.2.1/docs/readme.rst
--rw-r--r--   0 tobiaspn (21118) axusers    (500)       59 2023-06-08 05:45:47.000000 etos_lib-3.2.1/docs/requirements.txt
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      128 2023-06-08 05:45:47.000000 etos_lib-3.2.1/requirements.txt
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     1413 2023-06-09 08:22:40.065967 etos_lib-3.2.1/setup.cfg
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      552 2023-06-08 05:45:47.000000 etos_lib-3.2.1/setup.py
-drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-09 08:22:40.061967 etos_lib-3.2.1/src/
-drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-09 08:22:40.061967 etos_lib-3.2.1/src/etos_lib/
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     1093 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/__init__.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     4915 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/etos.py
-drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-09 08:22:40.065967 etos_lib-3.2.1/src/etos_lib/graphql/
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      702 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/graphql/__init__.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     2595 2023-06-09 08:22:30.000000 etos_lib-3.2.1/src/etos_lib/graphql/query_handler.py
-drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-09 08:22:40.065967 etos_lib-3.2.1/src/etos_lib/kubernetes/
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      727 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/kubernetes/__init__.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     3103 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/kubernetes/base.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     3288 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/kubernetes/jobs.py
-drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-09 08:22:40.065967 etos_lib-3.2.1/src/etos_lib/lib/
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      701 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/lib/__init__.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     4814 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/lib/config.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     3911 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/lib/database.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     5179 2023-06-09 06:01:45.000000 etos_lib-3.2.1/src/etos_lib/lib/debug.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)    15885 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/lib/events.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     2480 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/lib/exceptions.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      810 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/lib/feature_flags.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     4331 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/lib/http.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     4605 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/lib/monitor.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)    10944 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/lib/utils.py
-drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-09 08:22:40.065967 etos_lib-3.2.1/src/etos_lib/logging/
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      693 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/logging/__init__.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)       66 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/logging/default_config.yaml
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     2223 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/logging/filter.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     4094 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/logging/formatter.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     1967 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/logging/log_publisher.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     6829 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/logging/logger.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     2331 2023-06-08 05:45:47.000000 etos_lib-3.2.1/src/etos_lib/logging/rabbitmq_handler.py
-drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-09 08:22:40.061967 etos_lib-3.2.1/src/etos_lib.egg-info/
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     1334 2023-06-09 08:22:40.000000 etos_lib-3.2.1/src/etos_lib.egg-info/PKG-INFO
--rw-r--r--   0 tobiaspn (21118) axusers    (500)     1316 2023-06-09 08:22:40.000000 etos_lib-3.2.1/src/etos_lib.egg-info/SOURCES.txt
--rw-r--r--   0 tobiaspn (21118) axusers    (500)        1 2023-06-09 08:22:40.000000 etos_lib-3.2.1/src/etos_lib.egg-info/dependency_links.txt
--rw-r--r--   0 tobiaspn (21118) axusers    (500)        1 2023-06-08 05:46:27.000000 etos_lib-3.2.1/src/etos_lib.egg-info/not-zip-safe
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      128 2023-06-09 08:22:40.000000 etos_lib-3.2.1/src/etos_lib.egg-info/requires.txt
--rw-r--r--   0 tobiaspn (21118) axusers    (500)        9 2023-06-09 08:22:40.000000 etos_lib-3.2.1/src/etos_lib.egg-info/top_level.txt
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      241 2023-06-08 05:45:47.000000 etos_lib-3.2.1/test-requirements.txt
-drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-09 08:22:40.065967 etos_lib-3.2.1/tests/
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      692 2023-06-08 05:45:47.000000 etos_lib-3.2.1/tests/__init__.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      196 2023-06-08 05:45:47.000000 etos_lib-3.2.1/tests/conftest.py
--rw-r--r--   0 tobiaspn (21118) axusers    (500)      410 2023-06-08 05:45:47.000000 etos_lib-3.2.1/tox.ini
+drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-28 12:45:08.588040 etos_lib-3.2.2/
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      591 2023-06-28 12:44:48.000000 etos_lib-3.2.2/.coveragerc
+drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-28 12:45:08.584040 etos_lib-3.2.2/.github/
+drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-28 12:45:08.584040 etos_lib-3.2.2/.github/workflows/
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      850 2023-06-28 12:44:48.000000 etos_lib-3.2.2/.github/workflows/main.yml
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      542 2023-06-28 12:44:48.000000 etos_lib-3.2.2/.gitignore
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      174 2023-06-28 12:44:48.000000 etos_lib-3.2.2/AUTHORS.rst
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)       37 2023-06-28 12:44:48.000000 etos_lib-3.2.2/CODEOWNERS
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)    10850 2023-06-28 12:44:48.000000 etos_lib-3.2.2/LICENSE.txt
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     1334 2023-06-28 12:45:08.588040 etos_lib-3.2.2/PKG-INFO
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      721 2023-06-28 12:44:48.000000 etos_lib-3.2.2/README.rst
+drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-28 12:45:08.588040 etos_lib-3.2.2/docs/
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     7610 2023-06-28 12:44:48.000000 etos_lib-3.2.2/docs/Makefile
+drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-28 12:45:08.588040 etos_lib-3.2.2/docs/_static/
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)       18 2023-06-28 12:44:48.000000 etos_lib-3.2.2/docs/_static/.gitignore
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)       41 2023-06-28 12:44:48.000000 etos_lib-3.2.2/docs/authors.rst
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)       43 2023-06-28 12:44:48.000000 etos_lib-3.2.2/docs/changelog.rst
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     9175 2023-06-28 12:44:48.000000 etos_lib-3.2.2/docs/conf.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      457 2023-06-28 12:44:48.000000 etos_lib-3.2.2/docs/index.rst
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)       74 2023-06-28 12:44:48.000000 etos_lib-3.2.2/docs/license.rst
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)       39 2023-06-28 12:44:48.000000 etos_lib-3.2.2/docs/readme.rst
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)       59 2023-06-28 12:44:48.000000 etos_lib-3.2.2/docs/requirements.txt
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      128 2023-06-28 12:44:48.000000 etos_lib-3.2.2/requirements.txt
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     1413 2023-06-28 12:45:08.588040 etos_lib-3.2.2/setup.cfg
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      552 2023-06-28 12:44:48.000000 etos_lib-3.2.2/setup.py
+drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-28 12:45:08.584040 etos_lib-3.2.2/src/
+drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-28 12:45:08.588040 etos_lib-3.2.2/src/etos_lib/
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     1093 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/__init__.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     4915 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/etos.py
+drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-28 12:45:08.588040 etos_lib-3.2.2/src/etos_lib/graphql/
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      702 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/graphql/__init__.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     2595 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/graphql/query_handler.py
+drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-28 12:45:08.588040 etos_lib-3.2.2/src/etos_lib/kubernetes/
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      727 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/kubernetes/__init__.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     3103 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/kubernetes/base.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     3288 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/kubernetes/jobs.py
+drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-28 12:45:08.588040 etos_lib-3.2.2/src/etos_lib/lib/
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      701 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/lib/__init__.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     4814 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/lib/config.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     3911 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/lib/database.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     5179 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/lib/debug.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)    15885 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/lib/events.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     2480 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/lib/exceptions.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      810 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/lib/feature_flags.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     4331 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/lib/http.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     4605 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/lib/monitor.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)    10944 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/lib/utils.py
+drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-28 12:45:08.588040 etos_lib-3.2.2/src/etos_lib/logging/
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      693 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/logging/__init__.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)       66 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/logging/default_config.yaml
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     2223 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/logging/filter.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     4094 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/logging/formatter.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     1967 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/logging/log_publisher.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     6850 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/logging/logger.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     2331 2023-06-28 12:44:48.000000 etos_lib-3.2.2/src/etos_lib/logging/rabbitmq_handler.py
+drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-28 12:45:08.588040 etos_lib-3.2.2/src/etos_lib.egg-info/
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     1334 2023-06-28 12:45:08.000000 etos_lib-3.2.2/src/etos_lib.egg-info/PKG-INFO
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)     1316 2023-06-28 12:45:08.000000 etos_lib-3.2.2/src/etos_lib.egg-info/SOURCES.txt
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)        1 2023-06-28 12:45:08.000000 etos_lib-3.2.2/src/etos_lib.egg-info/dependency_links.txt
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)        1 2023-06-28 12:45:08.000000 etos_lib-3.2.2/src/etos_lib.egg-info/not-zip-safe
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      128 2023-06-28 12:45:08.000000 etos_lib-3.2.2/src/etos_lib.egg-info/requires.txt
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)        9 2023-06-28 12:45:08.000000 etos_lib-3.2.2/src/etos_lib.egg-info/top_level.txt
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      241 2023-06-28 12:44:48.000000 etos_lib-3.2.2/test-requirements.txt
+drwxr-xr-x   0 tobiaspn (21118) axusers    (500)        0 2023-06-28 12:45:08.588040 etos_lib-3.2.2/tests/
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      692 2023-06-28 12:44:48.000000 etos_lib-3.2.2/tests/__init__.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      196 2023-06-28 12:44:48.000000 etos_lib-3.2.2/tests/conftest.py
+-rw-r--r--   0 tobiaspn (21118) axusers    (500)      410 2023-06-28 12:44:48.000000 etos_lib-3.2.2/tox.ini
```

### Comparing `etos_lib-3.2.1/.coveragerc` & `etos_lib-3.2.2/.coveragerc`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/.github/workflows/main.yml` & `etos_lib-3.2.2/.github/workflows/main.yml`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/.gitignore` & `etos_lib-3.2.2/.gitignore`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/LICENSE.txt` & `etos_lib-3.2.2/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/PKG-INFO` & `etos_lib-3.2.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: etos_lib
-Version: 3.2.1
+Version: 3.2.2
 Summary: ETOS Library
 Home-page: https://github.com/eiffel-community/etos-library
 Author: Tobias Persson
 Author-email: tobias.persson@axis.com
 License: Apache License, Version 2.0
 Project-URL: Documentation, https://etos.readthedocs.io/
 Platform: Linux
```

### Comparing `etos_lib-3.2.1/README.rst` & `etos_lib-3.2.2/README.rst`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/docs/Makefile` & `etos_lib-3.2.2/docs/Makefile`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/docs/conf.py` & `etos_lib-3.2.2/docs/conf.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/setup.cfg` & `etos_lib-3.2.2/setup.cfg`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/setup.py` & `etos_lib-3.2.2/setup.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/__init__.py` & `etos_lib-3.2.2/src/etos_lib/__init__.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/etos.py` & `etos_lib-3.2.2/src/etos_lib/etos.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/graphql/__init__.py` & `etos_lib-3.2.2/src/etos_lib/graphql/__init__.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/graphql/query_handler.py` & `etos_lib-3.2.2/src/etos_lib/graphql/query_handler.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/kubernetes/__init__.py` & `etos_lib-3.2.2/src/etos_lib/kubernetes/__init__.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/kubernetes/base.py` & `etos_lib-3.2.2/src/etos_lib/kubernetes/base.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/kubernetes/jobs.py` & `etos_lib-3.2.2/src/etos_lib/kubernetes/jobs.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/lib/__init__.py` & `etos_lib-3.2.2/src/etos_lib/lib/__init__.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/lib/config.py` & `etos_lib-3.2.2/src/etos_lib/lib/config.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/lib/database.py` & `etos_lib-3.2.2/src/etos_lib/lib/database.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/lib/debug.py` & `etos_lib-3.2.2/src/etos_lib/lib/debug.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/lib/events.py` & `etos_lib-3.2.2/src/etos_lib/lib/events.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/lib/exceptions.py` & `etos_lib-3.2.2/src/etos_lib/lib/exceptions.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/lib/feature_flags.py` & `etos_lib-3.2.2/src/etos_lib/lib/feature_flags.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/lib/http.py` & `etos_lib-3.2.2/src/etos_lib/lib/http.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/lib/monitor.py` & `etos_lib-3.2.2/src/etos_lib/lib/monitor.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/lib/utils.py` & `etos_lib-3.2.2/src/etos_lib/lib/utils.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/logging/__init__.py` & `etos_lib-3.2.2/src/etos_lib/logging/__init__.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/logging/filter.py` & `etos_lib-3.2.2/src/etos_lib/logging/filter.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/logging/formatter.py` & `etos_lib-3.2.2/src/etos_lib/logging/formatter.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/logging/log_publisher.py` & `etos_lib-3.2.2/src/etos_lib/logging/log_publisher.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib/logging/logger.py` & `etos_lib-3.2.2/src/etos_lib/logging/logger.py`

 * *Files 1% similar despite different names*

```diff
@@ -129,15 +129,15 @@
     loglevel = logging.DEBUG
 
     root_logger = logging.getLogger()
 
     # These have to be removed as they create a loop.
     # They will still work with the other handlers.
     logging.getLogger("pika").propagate = False
-    logging.getLogger("rabbitmq_publisher").propagate = False
+    logging.getLogger("eiffellib.publishers.rabbitmq_publisher").propagate = False
     logging.getLogger("base_rabbitmq").propagate = False
 
     rabbitmq = RabbitMQLogPublisher(
         **Config().etos_rabbitmq_publisher_data(), routing_key=None
     )
     if Debug().enable_sending_logs:
         rabbitmq.start()
```

### Comparing `etos_lib-3.2.1/src/etos_lib/logging/rabbitmq_handler.py` & `etos_lib-3.2.2/src/etos_lib/logging/rabbitmq_handler.py`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/src/etos_lib.egg-info/PKG-INFO` & `etos_lib-3.2.2/src/etos_lib.egg-info/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: etos-lib
-Version: 3.2.1
+Version: 3.2.2
 Summary: ETOS Library
 Home-page: https://github.com/eiffel-community/etos-library
 Author: Tobias Persson
 Author-email: tobias.persson@axis.com
 License: Apache License, Version 2.0
 Project-URL: Documentation, https://etos.readthedocs.io/
 Platform: Linux
```

### Comparing `etos_lib-3.2.1/src/etos_lib.egg-info/SOURCES.txt` & `etos_lib-3.2.2/src/etos_lib.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `etos_lib-3.2.1/tests/__init__.py` & `etos_lib-3.2.2/tests/__init__.py`

 * *Files identical despite different names*


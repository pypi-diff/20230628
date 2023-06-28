# Comparing `tmp/tendril-filestore-0.2.4.tar.gz` & `tmp/tendril-filestore-0.2.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tendril-filestore-0.2.4.tar", last modified: Mon Jun 26 13:27:24 2023, max compression
+gzip compressed data, was "tendril-filestore-0.2.5.tar", last modified: Wed Jun 28 08:50:32 2023, max compression
```

## Comparing `tendril-filestore-0.2.4.tar` & `tendril-filestore-0.2.5.tar`

### file list

```diff
@@ -1,70 +1,70 @@
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.472344 tendril-filestore-0.2.4/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     2122 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/.gitignore
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      638 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/.readthedocs.yml
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      629 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/.travis.yml
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/CHANGELOG.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)    34520 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/LICENSE
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      173 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/MANIFEST.in
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     3543 2023-06-26 13:27:24.472344 tendril-filestore-0.2.4/PKG-INFO
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     2224 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/README.rst
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.460343 tendril-filestore-0.2.4/docs/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     7660 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/docs/Makefile
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.464344 tendril-filestore-0.2.4/docs/_static/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     2727 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/docs/_static/custom.css
--rw-rw-r--   0 chintal   (1000) chintal   (1000)   128918 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/docs/_static/favicon.ico
--rw-rw-r--   0 chintal   (1000) chintal   (1000)    96804 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/docs/_static/logo.png
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     9889 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/docs/_static/logo_packed.png
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.464344 tendril-filestore-0.2.4/docs/_templates/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1713 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/docs/_templates/about.html
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.464344 tendril-filestore-0.2.4/docs/api/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      128 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/docs/api/index.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)    13464 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/docs/conf.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      943 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/docs/index.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1548 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/docs/installation.rst
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.464344 tendril-filestore-0.2.4/docs/usage/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       35 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/docs/usage/standalone.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       49 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/docs/usage/tendril.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      131 2023-06-26 13:27:24.472344 tendril-filestore-0.2.4/setup.cfg
--rwxrwxr-x   0 chintal   (1000) chintal   (1000)     3306 2023-04-20 19:33:00.000000 tendril-filestore-0.2.4/setup.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.456344 tendril-filestore-0.2.4/src/
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.464344 tendril-filestore-0.2.4/src/tendril/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       66 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/src/tendril/__init__.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.464344 tendril-filestore-0.2.4/src/tendril/apiserver/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-12-09 17:57:19.000000 tendril-filestore-0.2.4/src/tendril/apiserver/__init__.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.464344 tendril-filestore-0.2.4/src/tendril/apiserver/routers/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-12-09 17:57:19.000000 tendril-filestore-0.2.4/src/tendril/apiserver/routers/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     6100 2023-04-21 08:02:15.000000 tendril-filestore-0.2.4/src/tendril/apiserver/routers/filestore.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.464344 tendril-filestore-0.2.4/src/tendril/authz/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-11-28 19:36:13.000000 tendril-filestore-0.2.4/src/tendril/authz/__init__.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.464344 tendril-filestore-0.2.4/src/tendril/authz/scopes/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      232 2023-02-27 21:03:32.000000 tendril-filestore-0.2.4/src/tendril/authz/scopes/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      264 2023-03-27 15:39:22.000000 tendril-filestore-0.2.4/src/tendril/authz/scopes/filestore.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.464344 tendril-filestore-0.2.4/src/tendril/common/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2023-04-19 12:09:04.000000 tendril-filestore-0.2.4/src/tendril/common/__init__.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.468344 tendril-filestore-0.2.4/src/tendril/common/filestore/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2023-04-19 11:58:32.000000 tendril-filestore-0.2.4/src/tendril/common/filestore/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1646 2023-04-19 17:38:08.000000 tendril-filestore-0.2.4/src/tendril/common/filestore/formats.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.468344 tendril-filestore-0.2.4/src/tendril/config/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1112 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/src/tendril/config/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     3744 2023-04-20 12:32:50.000000 tendril-filestore-0.2.4/src/tendril/config/filestore.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     3458 2023-04-20 12:32:52.000000 tendril-filestore-0.2.4/src/tendril/config/filestore_core.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.468344 tendril-filestore-0.2.4/src/tendril/filestore/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 21:59:13.000000 tendril-filestore-0.2.4/src/tendril/filestore/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     6838 2023-06-26 13:19:39.000000 tendril-filestore-0.2.4/src/tendril/filestore/actual.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1576 2023-04-21 12:45:53.000000 tendril-filestore-0.2.4/src/tendril/filestore/base.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     2977 2023-04-20 15:56:35.000000 tendril-filestore-0.2.4/src/tendril/filestore/buckets.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.468344 tendril-filestore-0.2.4/src/tendril/filestore/db/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-09 17:57:19.000000 tendril-filestore-0.2.4/src/tendril/filestore/db/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     6250 2023-04-19 17:30:49.000000 tendril-filestore-0.2.4/src/tendril/filestore/db/controller.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1426 2023-04-11 18:49:23.000000 tendril-filestore-0.2.4/src/tendril/filestore/db/model.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     2750 2023-04-21 12:45:53.000000 tendril-filestore-0.2.4/src/tendril/filestore/remote.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.472344 tendril-filestore-0.2.4/src/tendril_filestore.egg-info/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     3543 2023-06-26 13:27:24.000000 tendril-filestore-0.2.4/src/tendril_filestore.egg-info/PKG-INFO
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1362 2023-06-26 13:27:24.000000 tendril-filestore-0.2.4/src/tendril_filestore.egg-info/SOURCES.txt
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        1 2023-06-26 13:27:24.000000 tendril-filestore-0.2.4/src/tendril_filestore.egg-info/dependency_links.txt
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      603 2023-06-26 13:27:24.000000 tendril-filestore-0.2.4/src/tendril_filestore.egg-info/requires.txt
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        8 2023-06-26 13:27:24.000000 tendril-filestore-0.2.4/src/tendril_filestore.egg-info/top_level.txt
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-26 13:27:24.472344 tendril-filestore-0.2.4/tests/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/tests/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1060 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/tests/coveralls.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      787 2022-12-08 18:25:43.000000 tendril-filestore-0.2.4/tox.ini
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.385616 tendril-filestore-0.2.5/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     2122 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/.gitignore
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      638 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/.readthedocs.yml
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      629 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/.travis.yml
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/CHANGELOG.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)    34520 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/LICENSE
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      173 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/MANIFEST.in
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     3543 2023-06-28 08:50:32.385616 tendril-filestore-0.2.5/PKG-INFO
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     2224 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/README.rst
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.373616 tendril-filestore-0.2.5/docs/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     7660 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/Makefile
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.373616 tendril-filestore-0.2.5/docs/_static/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     2727 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/_static/custom.css
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)   128918 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/_static/favicon.ico
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)    96804 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/_static/logo.png
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     9889 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/_static/logo_packed.png
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/docs/_templates/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1713 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/_templates/about.html
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/docs/api/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      128 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/api/index.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)    13464 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/conf.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      943 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/index.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1548 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/installation.rst
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/docs/usage/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       35 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/usage/standalone.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       49 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/usage/tendril.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      131 2023-06-28 08:50:32.385616 tendril-filestore-0.2.5/setup.cfg
+-rwxrwxr-x   0 chintal   (1000) chintal   (1000)     3306 2023-04-20 19:33:00.000000 tendril-filestore-0.2.5/setup.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.365616 tendril-filestore-0.2.5/src/
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/src/tendril/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       66 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/src/tendril/__init__.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/src/tendril/apiserver/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-12-09 17:57:19.000000 tendril-filestore-0.2.5/src/tendril/apiserver/__init__.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/src/tendril/apiserver/routers/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-12-09 17:57:19.000000 tendril-filestore-0.2.5/src/tendril/apiserver/routers/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     6126 2023-06-28 08:20:08.000000 tendril-filestore-0.2.5/src/tendril/apiserver/routers/filestore.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/src/tendril/authz/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-11-28 19:36:13.000000 tendril-filestore-0.2.5/src/tendril/authz/__init__.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/src/tendril/authz/scopes/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      232 2023-02-27 21:03:32.000000 tendril-filestore-0.2.5/src/tendril/authz/scopes/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      264 2023-03-27 15:39:22.000000 tendril-filestore-0.2.5/src/tendril/authz/scopes/filestore.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/src/tendril/common/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2023-04-19 12:09:04.000000 tendril-filestore-0.2.5/src/tendril/common/__init__.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.381616 tendril-filestore-0.2.5/src/tendril/common/filestore/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2023-04-19 11:58:32.000000 tendril-filestore-0.2.5/src/tendril/common/filestore/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1646 2023-04-19 17:38:08.000000 tendril-filestore-0.2.5/src/tendril/common/filestore/formats.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.381616 tendril-filestore-0.2.5/src/tendril/config/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1112 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/src/tendril/config/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     3744 2023-04-20 12:32:50.000000 tendril-filestore-0.2.5/src/tendril/config/filestore.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     3458 2023-04-20 12:32:52.000000 tendril-filestore-0.2.5/src/tendril/config/filestore_core.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.381616 tendril-filestore-0.2.5/src/tendril/filestore/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 21:59:13.000000 tendril-filestore-0.2.5/src/tendril/filestore/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     7018 2023-06-28 08:20:08.000000 tendril-filestore-0.2.5/src/tendril/filestore/actual.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1576 2023-04-21 12:45:53.000000 tendril-filestore-0.2.5/src/tendril/filestore/base.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     2977 2023-04-20 15:56:35.000000 tendril-filestore-0.2.5/src/tendril/filestore/buckets.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.381616 tendril-filestore-0.2.5/src/tendril/filestore/db/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-09 17:57:19.000000 tendril-filestore-0.2.5/src/tendril/filestore/db/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     6250 2023-04-19 17:30:49.000000 tendril-filestore-0.2.5/src/tendril/filestore/db/controller.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1426 2023-04-11 18:49:23.000000 tendril-filestore-0.2.5/src/tendril/filestore/db/model.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     2750 2023-06-28 07:56:59.000000 tendril-filestore-0.2.5/src/tendril/filestore/remote.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.381616 tendril-filestore-0.2.5/src/tendril_filestore.egg-info/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     3543 2023-06-28 08:50:32.000000 tendril-filestore-0.2.5/src/tendril_filestore.egg-info/PKG-INFO
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1362 2023-06-28 08:50:32.000000 tendril-filestore-0.2.5/src/tendril_filestore.egg-info/SOURCES.txt
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        1 2023-06-28 08:50:32.000000 tendril-filestore-0.2.5/src/tendril_filestore.egg-info/dependency_links.txt
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      603 2023-06-28 08:50:32.000000 tendril-filestore-0.2.5/src/tendril_filestore.egg-info/requires.txt
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        8 2023-06-28 08:50:32.000000 tendril-filestore-0.2.5/src/tendril_filestore.egg-info/top_level.txt
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.385616 tendril-filestore-0.2.5/tests/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/tests/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1060 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/tests/coveralls.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      787 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/tox.ini
```

### Comparing `tendril-filestore-0.2.4/.gitignore` & `tendril-filestore-0.2.5/.gitignore`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/.readthedocs.yml` & `tendril-filestore-0.2.5/.readthedocs.yml`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/.travis.yml` & `tendril-filestore-0.2.5/.travis.yml`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/LICENSE` & `tendril-filestore-0.2.5/LICENSE`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/PKG-INFO` & `tendril-filestore-0.2.5/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tendril-filestore
-Version: 0.2.4
+Version: 0.2.5
 Summary: File Storage and Management Infrastructure for Tendril
 Home-page: https://github.com/tendril-framework/tendril-filestore
 Author: Chintalagiri Shashank
 Author-email: shashank@chintal.in
 Project-URL: Documentation, https://tendril-filestore.readthedocs.io/en/latest
 Project-URL: Bug Tracker, https://github.com/tendril-framework/tendril-filestore/issues
 Project-URL: Source Repository, https://github.com/tendril-framework/tendril-filestore
```

### Comparing `tendril-filestore-0.2.4/README.rst` & `tendril-filestore-0.2.5/README.rst`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/docs/Makefile` & `tendril-filestore-0.2.5/docs/Makefile`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/docs/_static/custom.css` & `tendril-filestore-0.2.5/docs/_static/custom.css`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/docs/_static/favicon.ico` & `tendril-filestore-0.2.5/docs/_static/favicon.ico`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/docs/_static/logo.png` & `tendril-filestore-0.2.5/docs/_static/logo.png`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/docs/_static/logo_packed.png` & `tendril-filestore-0.2.5/docs/_static/logo_packed.png`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/docs/_templates/about.html` & `tendril-filestore-0.2.5/docs/_templates/about.html`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/docs/conf.py` & `tendril-filestore-0.2.5/docs/conf.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/docs/index.rst` & `tendril-filestore-0.2.5/docs/index.rst`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/docs/installation.rst` & `tendril-filestore-0.2.5/docs/installation.rst`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/setup.py` & `tendril-filestore-0.2.5/setup.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/src/tendril/apiserver/routers/filestore.py` & `tendril-filestore-0.2.5/src/tendril/apiserver/routers/filestore.py`

 * *Files 1% similar despite different names*

```diff
@@ -140,24 +140,24 @@
     return {'deleted': filename}
 
 
 @filestore_management.get("/{bucket}/ls_fs",
                           response_model=List[str])
 async def list_files_in_bucket_fs(
         request: Request,
-        bucket: BucketName,
+        bucket: BucketName, path: str = '/',
         user: AuthUserModel = auth_spec()):
     try:
         bucket: FilestoreBucket = get_bucket(bucket)
     except KeyError:
         raise HTTPException(
             status_code=404,
             detail=f'{bucket} is not a recognized filestore bucket'
         )
-    return bucket.list()
+    return bucket.list(path=path)
 
 
 @filestore_management.get("/{bucket}/ls",
                           response_model=Page[StoredFileTModel],
                           response_model_exclude_none=True)
 async def list_files_in_bucket(
         request: Request,
```

### Comparing `tendril-filestore-0.2.4/src/tendril/common/filestore/formats.py` & `tendril-filestore-0.2.5/src/tendril/common/filestore/formats.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/src/tendril/config/__init__.py` & `tendril-filestore-0.2.5/src/tendril/config/__init__.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/src/tendril/config/filestore.py` & `tendril-filestore-0.2.5/src/tendril/config/filestore.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/src/tendril/config/filestore_core.py` & `tendril-filestore-0.2.5/src/tendril/config/filestore_core.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/src/tendril/filestore/actual.py` & `tendril-filestore-0.2.5/src/tendril/filestore/actual.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,14 +1,15 @@
 
 
 import hashlib
 import os
 
 from fs import open_fs
 from fs import move
+from fs.osfs import OSFS
 from sqlalchemy.exc import NoResultFound
 
 # Causes a circular import issue. Does not actually seem to be needed.
 # from tendril.authn.users import get_user_stub
 from tendril.filestore.base import FilestoreBucketBase
 from tendril.filestore.db.controller import register_bucket
 from tendril.filestore.db.controller import get_storedfile_owner
@@ -42,23 +43,26 @@
             if path.startswith('~'):
                 path = os.path.expanduser(path)
             path = os.path.normpath(path)
             os.makedirs(path, exist_ok=True)
         self._fs = open_fs(self._uri)
 
     @property
-    def fs(self):
+    def fs(self) -> OSFS:
         return self._fs
 
     def _create_in_db(self):
         b = register_bucket(name=self.name)
         self._id = b.id
 
     @with_db
     def _prep_for_upload(self, bucket, filename, user, overwrite=False, auto_prune=True, session=None):
+        subdir, _ = os.path.split(filename)
+        if subdir:
+            self.fs.makedirs(subdir, recreate=True)
         if bucket.fs.exists(filename):
             if not overwrite:
                 raise FileExistsError(f'{filename} already exists in the {bucket.name} bucket. Delete it first.')
             try:
                 owner = get_storedfile_owner(filename, bucket.id, session=session)
             except NoResultFound:
                 # file exists in fs but not in DB
@@ -118,22 +122,22 @@
 
         self._prep_for_upload(target_bucket, filename, user, overwrite)
 
         logger.debug(f"Moving file {filename} from bucket {self.name} to {target_bucket.name}")
         move.move_file(self.fs, filename, target_bucket.fs, filename)
         return change_file_bucket(filename, self.id, target_bucket.id, user, session=session)
 
-    def _list(self, page=None):
-        for f in self.fs.filterdir('/', page=page,
+    def _list(self, path='/', page=None):
+        for f in self.fs.filterdir(path, page=page,
                                    exclude_files=self._exclude_filenames,
                                    exclude_dirs=self._exclude_directories):
             yield f.name
 
-    def list(self, page=None):
-        return list(self._list(page=page))
+    def list(self, path='/', page=None):
+        return list(self._list(path=path, page=page))
 
     def list_info(self, include_owner=False, filenames=None,
                   pagination_params=None, page=None):
         kwargs = {}
         if filenames:
             kwargs['filenames'] = filenames
         return get_paginated_stored_files(
```

### Comparing `tendril-filestore-0.2.4/src/tendril/filestore/base.py` & `tendril-filestore-0.2.5/src/tendril/filestore/base.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/src/tendril/filestore/buckets.py` & `tendril-filestore-0.2.5/src/tendril/filestore/buckets.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/src/tendril/filestore/db/controller.py` & `tendril-filestore-0.2.5/src/tendril/filestore/db/controller.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/src/tendril/filestore/db/model.py` & `tendril-filestore-0.2.5/src/tendril/filestore/db/model.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/src/tendril/filestore/remote.py` & `tendril-filestore-0.2.5/src/tendril/filestore/remote.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/src/tendril_filestore.egg-info/PKG-INFO` & `tendril-filestore-0.2.5/src/tendril_filestore.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tendril-filestore
-Version: 0.2.4
+Version: 0.2.5
 Summary: File Storage and Management Infrastructure for Tendril
 Home-page: https://github.com/tendril-framework/tendril-filestore
 Author: Chintalagiri Shashank
 Author-email: shashank@chintal.in
 Project-URL: Documentation, https://tendril-filestore.readthedocs.io/en/latest
 Project-URL: Bug Tracker, https://github.com/tendril-framework/tendril-filestore/issues
 Project-URL: Source Repository, https://github.com/tendril-framework/tendril-filestore
```

### Comparing `tendril-filestore-0.2.4/src/tendril_filestore.egg-info/SOURCES.txt` & `tendril-filestore-0.2.5/src/tendril_filestore.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/src/tendril_filestore.egg-info/requires.txt` & `tendril-filestore-0.2.5/src/tendril_filestore.egg-info/requires.txt`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/tests/coveralls.py` & `tendril-filestore-0.2.5/tests/coveralls.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.4/tox.ini` & `tendril-filestore-0.2.5/tox.ini`

 * *Files identical despite different names*


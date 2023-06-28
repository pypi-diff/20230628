# Comparing `tmp/tendril-filestore-0.2.5.tar.gz` & `tmp/tendril-filestore-0.2.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tendril-filestore-0.2.5.tar", last modified: Wed Jun 28 08:50:32 2023, max compression
+gzip compressed data, was "tendril-filestore-0.2.6.tar", last modified: Wed Jun 28 11:07:04 2023, max compression
```

## Comparing `tendril-filestore-0.2.5.tar` & `tendril-filestore-0.2.6.tar`

### file list

```diff
@@ -1,70 +1,70 @@
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.385616 tendril-filestore-0.2.5/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     2122 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/.gitignore
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      638 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/.readthedocs.yml
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      629 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/.travis.yml
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/CHANGELOG.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)    34520 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/LICENSE
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      173 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/MANIFEST.in
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     3543 2023-06-28 08:50:32.385616 tendril-filestore-0.2.5/PKG-INFO
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     2224 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/README.rst
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.373616 tendril-filestore-0.2.5/docs/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     7660 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/Makefile
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.373616 tendril-filestore-0.2.5/docs/_static/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     2727 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/_static/custom.css
--rw-rw-r--   0 chintal   (1000) chintal   (1000)   128918 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/_static/favicon.ico
--rw-rw-r--   0 chintal   (1000) chintal   (1000)    96804 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/_static/logo.png
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     9889 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/_static/logo_packed.png
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/docs/_templates/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1713 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/_templates/about.html
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/docs/api/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      128 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/api/index.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)    13464 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/conf.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      943 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/index.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1548 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/installation.rst
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/docs/usage/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       35 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/usage/standalone.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       49 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/docs/usage/tendril.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      131 2023-06-28 08:50:32.385616 tendril-filestore-0.2.5/setup.cfg
--rwxrwxr-x   0 chintal   (1000) chintal   (1000)     3306 2023-04-20 19:33:00.000000 tendril-filestore-0.2.5/setup.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.365616 tendril-filestore-0.2.5/src/
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/src/tendril/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       66 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/src/tendril/__init__.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/src/tendril/apiserver/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-12-09 17:57:19.000000 tendril-filestore-0.2.5/src/tendril/apiserver/__init__.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/src/tendril/apiserver/routers/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-12-09 17:57:19.000000 tendril-filestore-0.2.5/src/tendril/apiserver/routers/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     6126 2023-06-28 08:20:08.000000 tendril-filestore-0.2.5/src/tendril/apiserver/routers/filestore.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/src/tendril/authz/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-11-28 19:36:13.000000 tendril-filestore-0.2.5/src/tendril/authz/__init__.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/src/tendril/authz/scopes/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      232 2023-02-27 21:03:32.000000 tendril-filestore-0.2.5/src/tendril/authz/scopes/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      264 2023-03-27 15:39:22.000000 tendril-filestore-0.2.5/src/tendril/authz/scopes/filestore.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.377616 tendril-filestore-0.2.5/src/tendril/common/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2023-04-19 12:09:04.000000 tendril-filestore-0.2.5/src/tendril/common/__init__.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.381616 tendril-filestore-0.2.5/src/tendril/common/filestore/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2023-04-19 11:58:32.000000 tendril-filestore-0.2.5/src/tendril/common/filestore/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1646 2023-04-19 17:38:08.000000 tendril-filestore-0.2.5/src/tendril/common/filestore/formats.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.381616 tendril-filestore-0.2.5/src/tendril/config/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1112 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/src/tendril/config/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     3744 2023-04-20 12:32:50.000000 tendril-filestore-0.2.5/src/tendril/config/filestore.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     3458 2023-04-20 12:32:52.000000 tendril-filestore-0.2.5/src/tendril/config/filestore_core.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.381616 tendril-filestore-0.2.5/src/tendril/filestore/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 21:59:13.000000 tendril-filestore-0.2.5/src/tendril/filestore/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     7018 2023-06-28 08:20:08.000000 tendril-filestore-0.2.5/src/tendril/filestore/actual.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1576 2023-04-21 12:45:53.000000 tendril-filestore-0.2.5/src/tendril/filestore/base.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     2977 2023-04-20 15:56:35.000000 tendril-filestore-0.2.5/src/tendril/filestore/buckets.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.381616 tendril-filestore-0.2.5/src/tendril/filestore/db/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-09 17:57:19.000000 tendril-filestore-0.2.5/src/tendril/filestore/db/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     6250 2023-04-19 17:30:49.000000 tendril-filestore-0.2.5/src/tendril/filestore/db/controller.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1426 2023-04-11 18:49:23.000000 tendril-filestore-0.2.5/src/tendril/filestore/db/model.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     2750 2023-06-28 07:56:59.000000 tendril-filestore-0.2.5/src/tendril/filestore/remote.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.381616 tendril-filestore-0.2.5/src/tendril_filestore.egg-info/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     3543 2023-06-28 08:50:32.000000 tendril-filestore-0.2.5/src/tendril_filestore.egg-info/PKG-INFO
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1362 2023-06-28 08:50:32.000000 tendril-filestore-0.2.5/src/tendril_filestore.egg-info/SOURCES.txt
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        1 2023-06-28 08:50:32.000000 tendril-filestore-0.2.5/src/tendril_filestore.egg-info/dependency_links.txt
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      603 2023-06-28 08:50:32.000000 tendril-filestore-0.2.5/src/tendril_filestore.egg-info/requires.txt
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        8 2023-06-28 08:50:32.000000 tendril-filestore-0.2.5/src/tendril_filestore.egg-info/top_level.txt
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 08:50:32.385616 tendril-filestore-0.2.5/tests/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/tests/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1060 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/tests/coveralls.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      787 2022-12-08 18:25:43.000000 tendril-filestore-0.2.5/tox.ini
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.009788 tendril-filestore-0.2.6/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     2122 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/.gitignore
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      638 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/.readthedocs.yml
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      629 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/.travis.yml
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/CHANGELOG.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)    34520 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/LICENSE
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      173 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/MANIFEST.in
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     3543 2023-06-28 11:07:04.009788 tendril-filestore-0.2.6/PKG-INFO
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     2224 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/README.rst
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.005788 tendril-filestore-0.2.6/docs/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     7660 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/docs/Makefile
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.005788 tendril-filestore-0.2.6/docs/_static/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     2727 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/docs/_static/custom.css
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)   128918 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/docs/_static/favicon.ico
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)    96804 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/docs/_static/logo.png
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     9889 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/docs/_static/logo_packed.png
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.005788 tendril-filestore-0.2.6/docs/_templates/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1713 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/docs/_templates/about.html
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.005788 tendril-filestore-0.2.6/docs/api/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      128 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/docs/api/index.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)    13464 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/docs/conf.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      943 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/docs/index.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1548 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/docs/installation.rst
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.005788 tendril-filestore-0.2.6/docs/usage/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       35 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/docs/usage/standalone.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       49 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/docs/usage/tendril.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      131 2023-06-28 11:07:04.009788 tendril-filestore-0.2.6/setup.cfg
+-rwxrwxr-x   0 chintal   (1000) chintal   (1000)     3306 2023-04-20 19:33:00.000000 tendril-filestore-0.2.6/setup.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.005788 tendril-filestore-0.2.6/src/
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.005788 tendril-filestore-0.2.6/src/tendril/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       66 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/src/tendril/__init__.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.005788 tendril-filestore-0.2.6/src/tendril/apiserver/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-12-09 17:57:19.000000 tendril-filestore-0.2.6/src/tendril/apiserver/__init__.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.005788 tendril-filestore-0.2.6/src/tendril/apiserver/routers/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-12-09 17:57:19.000000 tendril-filestore-0.2.6/src/tendril/apiserver/routers/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     6637 2023-06-28 10:43:56.000000 tendril-filestore-0.2.6/src/tendril/apiserver/routers/filestore.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.009788 tendril-filestore-0.2.6/src/tendril/authz/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-11-28 19:36:13.000000 tendril-filestore-0.2.6/src/tendril/authz/__init__.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.009788 tendril-filestore-0.2.6/src/tendril/authz/scopes/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      232 2023-02-27 21:03:32.000000 tendril-filestore-0.2.6/src/tendril/authz/scopes/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      264 2023-03-27 15:39:22.000000 tendril-filestore-0.2.6/src/tendril/authz/scopes/filestore.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.009788 tendril-filestore-0.2.6/src/tendril/common/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2023-04-19 12:09:04.000000 tendril-filestore-0.2.6/src/tendril/common/__init__.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.009788 tendril-filestore-0.2.6/src/tendril/common/filestore/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2023-04-19 11:58:32.000000 tendril-filestore-0.2.6/src/tendril/common/filestore/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1646 2023-04-19 17:38:08.000000 tendril-filestore-0.2.6/src/tendril/common/filestore/formats.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.009788 tendril-filestore-0.2.6/src/tendril/config/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1112 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/src/tendril/config/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     3744 2023-04-20 12:32:50.000000 tendril-filestore-0.2.6/src/tendril/config/filestore.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     3458 2023-04-20 12:32:52.000000 tendril-filestore-0.2.6/src/tendril/config/filestore_core.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.009788 tendril-filestore-0.2.6/src/tendril/filestore/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 21:59:13.000000 tendril-filestore-0.2.6/src/tendril/filestore/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     7292 2023-06-28 10:22:40.000000 tendril-filestore-0.2.6/src/tendril/filestore/actual.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1576 2023-04-21 12:45:53.000000 tendril-filestore-0.2.6/src/tendril/filestore/base.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     2977 2023-04-20 15:56:35.000000 tendril-filestore-0.2.6/src/tendril/filestore/buckets.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.009788 tendril-filestore-0.2.6/src/tendril/filestore/db/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-09 17:57:19.000000 tendril-filestore-0.2.6/src/tendril/filestore/db/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     6250 2023-04-19 17:30:49.000000 tendril-filestore-0.2.6/src/tendril/filestore/db/controller.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1426 2023-04-11 18:49:23.000000 tendril-filestore-0.2.6/src/tendril/filestore/db/model.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     3000 2023-06-28 10:47:37.000000 tendril-filestore-0.2.6/src/tendril/filestore/remote.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.009788 tendril-filestore-0.2.6/src/tendril_filestore.egg-info/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     3543 2023-06-28 11:07:03.000000 tendril-filestore-0.2.6/src/tendril_filestore.egg-info/PKG-INFO
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1362 2023-06-28 11:07:03.000000 tendril-filestore-0.2.6/src/tendril_filestore.egg-info/SOURCES.txt
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        1 2023-06-28 11:07:03.000000 tendril-filestore-0.2.6/src/tendril_filestore.egg-info/dependency_links.txt
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      603 2023-06-28 11:07:03.000000 tendril-filestore-0.2.6/src/tendril_filestore.egg-info/requires.txt
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        8 2023-06-28 11:07:03.000000 tendril-filestore-0.2.6/src/tendril_filestore.egg-info/top_level.txt
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 11:07:04.009788 tendril-filestore-0.2.6/tests/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/tests/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1060 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/tests/coveralls.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      787 2022-12-08 18:25:43.000000 tendril-filestore-0.2.6/tox.ini
```

### Comparing `tendril-filestore-0.2.5/.gitignore` & `tendril-filestore-0.2.6/.gitignore`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/.readthedocs.yml` & `tendril-filestore-0.2.6/.readthedocs.yml`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/.travis.yml` & `tendril-filestore-0.2.6/.travis.yml`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/LICENSE` & `tendril-filestore-0.2.6/LICENSE`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/PKG-INFO` & `tendril-filestore-0.2.6/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tendril-filestore
-Version: 0.2.5
+Version: 0.2.6
 Summary: File Storage and Management Infrastructure for Tendril
 Home-page: https://github.com/tendril-framework/tendril-filestore
 Author: Chintalagiri Shashank
 Author-email: shashank@chintal.in
 Project-URL: Documentation, https://tendril-filestore.readthedocs.io/en/latest
 Project-URL: Bug Tracker, https://github.com/tendril-framework/tendril-filestore/issues
 Project-URL: Source Repository, https://github.com/tendril-framework/tendril-filestore
```

### Comparing `tendril-filestore-0.2.5/README.rst` & `tendril-filestore-0.2.6/README.rst`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/docs/Makefile` & `tendril-filestore-0.2.6/docs/Makefile`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/docs/_static/custom.css` & `tendril-filestore-0.2.6/docs/_static/custom.css`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/docs/_static/favicon.ico` & `tendril-filestore-0.2.6/docs/_static/favicon.ico`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/docs/_static/logo.png` & `tendril-filestore-0.2.6/docs/_static/logo.png`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/docs/_static/logo_packed.png` & `tendril-filestore-0.2.6/docs/_static/logo_packed.png`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/docs/_templates/about.html` & `tendril-filestore-0.2.6/docs/_templates/about.html`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/docs/conf.py` & `tendril-filestore-0.2.6/docs/conf.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/docs/index.rst` & `tendril-filestore-0.2.6/docs/index.rst`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/docs/installation.rst` & `tendril-filestore-0.2.6/docs/installation.rst`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/setup.py` & `tendril-filestore-0.2.6/setup.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/src/tendril/apiserver/routers/filestore.py` & `tendril-filestore-0.2.6/src/tendril/apiserver/routers/filestore.py`

 * *Files 25% similar despite different names*

```diff
@@ -1,10 +1,11 @@
 
 
 from typing import List
+from typing import Optional
 from fastapi import APIRouter
 from fastapi import Depends
 from fastapi import Request
 from fastapi import File
 from fastapi import UploadFile
 from fastapi import HTTPException
 from fastapi_pagination import Page
@@ -19,14 +20,16 @@
 from tendril.filestore.actual import FilestoreBucket
 
 from tendril.common.filestore.formats import BucketName
 from tendril.common.filestore.formats import MoveRequest
 from tendril.common.filestore.formats import StoredFileTModel
 
 from tendril.config import FILESTORE_ENABLED
+from tendril.utils import log
+logger = log.get_logger(__name__, log.DEFAULT)
 
 
 filestore = APIRouter(prefix='/filestore',
                       tags=["File Management API"],
                       dependencies=[Depends(authn_dependency),
                                     auth_spec(scopes=['file_management:common'])])
 
@@ -43,47 +46,56 @@
 
 
 @filestore.post("/{bucket}/upload")
 async def upload_file_to_bucket(
         request: Request,
         bucket: BucketName,
         overwrite: bool = False,
+        actual_user: Optional[str] = None,
         file: UploadFile = File(...),
         user: AuthUserModel = auth_spec()):
+
     try:
         bucket: FilestoreBucket = get_bucket(bucket)
     except KeyError:
+        logger.info(f"Got upload request with bad bucket '{bucket}' ({file.filename})")
         raise HTTPException(
             status_code=404,
             detail=f'{bucket} is not a recognized filestore bucket'
         )
+
     if not bucket.check_accepts(file.filename):
+        logger.info(f"Got upload request with bad extension ({file.filename})")
         raise HTTPException(
             status_code=415,
             detail=f"This bucket does not allow uploads with this extension"
         )
 
     try:
-        sf = bucket.upload(file, user.id, overwrite=overwrite)
+        actual_user = actual_user or user.id
+        sf = bucket.upload(file, actual_user, overwrite=overwrite)
     except FileExistsError as e:
+        logger.info(e)
         raise HTTPException(
             status_code=409,
             detail=str(e)
         )
+
     return {'storedfileid': sf.id}
     # print(request.headers.get('authorization'))
     # print(user)
     # print(file, file.filename)
 
 
 @filestore_management.post("/{bucket}/move")
 async def move_file_from_bucket(
         request: Request,
         bucket: BucketName,
         move_request: MoveRequest,
+        actual_user: Optional[str] = None,
         user: AuthUserModel = auth_spec()):
 
     try:
         source_bucket: FilestoreBucket = get_bucket(bucket)
     except KeyError:
         raise HTTPException(
             status_code=404,
@@ -97,59 +109,63 @@
             status_code=404,
             detail=f'{move_request.to_bucket} is not a recognized filestore bucket'
         )
 
     try:
         sf = source_bucket.move(filename=move_request.filename,
                                 target_bucket=target_bucket,
-                                user=user.id,
+                                user=actual_user or user.id,
                                 overwrite=move_request.overwrite)
     except FileNotFoundError:
         raise HTTPException(
             status_code=404,
             detail=f'{move_request.filename} does not exist in the source bucket'
         )
     return {'storedfileid': sf.id}
 
 
 @filestore_management.post("/{bucket}/delete")
 async def delete_file_from_bucket(
         request: Request,
         bucket: BucketName,
         filename: str,
+        actual_user: Optional[str] = None,
         user: AuthUserModel = auth_spec()):
+
     try:
         bucket: FilestoreBucket = get_bucket(bucket)
     except KeyError:
         raise HTTPException(
             status_code=404,
             detail=f'{bucket} is not a recognized filestore bucket'
         )
 
     try:
-        bucket.delete(filename, user.id)
+        bucket.delete(filename, actual_user or user.id)
     except FileNotFoundError as e:
         raise HTTPException(
             status_code=404,
             detail=str(e)
         )
     except PermissionError as e:
         raise HTTPException(
             status_code=403,
             detail=str(e)
         )
+
     return {'deleted': filename}
 
 
 @filestore_management.get("/{bucket}/ls_fs",
                           response_model=List[str])
 async def list_files_in_bucket_fs(
         request: Request,
         bucket: BucketName, path: str = '/',
         user: AuthUserModel = auth_spec()):
+
     try:
         bucket: FilestoreBucket = get_bucket(bucket)
     except KeyError:
         raise HTTPException(
             status_code=404,
             detail=f'{bucket} is not a recognized filestore bucket'
         )
@@ -161,14 +177,15 @@
                           response_model_exclude_none=True)
 async def list_files_in_bucket(
         request: Request,
         bucket: BucketName,
         include_owner: bool = False,
         params: Params = Depends(),
         user: AuthUserModel = auth_spec()):
+
     try:
         bucket: FilestoreBucket = get_bucket(bucket)
     except KeyError:
         raise HTTPException(
             status_code=404,
             detail=f'{bucket} is not a recognized filestore bucket'
         )
```

### Comparing `tendril-filestore-0.2.5/src/tendril/common/filestore/formats.py` & `tendril-filestore-0.2.6/src/tendril/common/filestore/formats.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/src/tendril/config/__init__.py` & `tendril-filestore-0.2.6/src/tendril/config/__init__.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/src/tendril/config/filestore.py` & `tendril-filestore-0.2.6/src/tendril/config/filestore.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/src/tendril/config/filestore_core.py` & `tendril-filestore-0.2.6/src/tendril/config/filestore_core.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/src/tendril/filestore/actual.py` & `tendril-filestore-0.2.6/src/tendril/filestore/actual.py`

 * *Files 3% similar despite different names*

```diff
@@ -56,30 +56,34 @@
 
     @with_db
     def _prep_for_upload(self, bucket, filename, user, overwrite=False, auto_prune=True, session=None):
         subdir, _ = os.path.split(filename)
         if subdir:
             self.fs.makedirs(subdir, recreate=True)
         if bucket.fs.exists(filename):
-            if not overwrite:
+            if not overwrite and not auto_prune:
                 raise FileExistsError(f'{filename} already exists in the {bucket.name} bucket. Delete it first.')
             try:
                 owner = get_storedfile_owner(filename, bucket.id, session=session)
             except NoResultFound:
                 # file exists in fs but not in DB
                 if not auto_prune:
                     raise FileExistsError(f"'{filename}' already exists in the '{bucket.name}' filesystem but "
                                           f"not in the database. This needs to be manually resolved.")
                 logger.warning(f"'{filename}' exists in the '{bucket.name}' filesystem but "
                                f"not in the database. Pruning. Possible Data Loss.")
                 bucket.fs.remove(filename)
             else:
-                if not bucket.allow_overwrite and owner.puid != user:
-                    raise FileExistsError(f'{filename} already exists in the {bucket.name} bucket '
-                                          f'and owned by someone else.')
+                if overwrite:
+                    if not bucket.allow_overwrite:
+                        raise FileExistsError(f'{filename} already exists in the {bucket.name} bucket '
+                                              f'and the bucket prohibits overwrites.')
+                    elif owner.puid != user:
+                        raise FileExistsError(f'{filename} already exists in the {bucket.name} bucket '
+                                              f'and owned by someone else.')
                 logger.warning(f"Overwriting file {filename} in bucket {bucket.name}.")
                 bucket.delete(filename, user, session=session)
 
     @with_db
     def upload(self, file, user, overwrite=False, session=None):
         filename = file.filename
         self._prep_for_upload(self, filename, user, overwrite)
```

### Comparing `tendril-filestore-0.2.5/src/tendril/filestore/base.py` & `tendril-filestore-0.2.6/src/tendril/filestore/base.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/src/tendril/filestore/buckets.py` & `tendril-filestore-0.2.6/src/tendril/filestore/buckets.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/src/tendril/filestore/db/controller.py` & `tendril-filestore-0.2.6/src/tendril/filestore/db/controller.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/src/tendril/filestore/db/model.py` & `tendril-filestore-0.2.6/src/tendril/filestore/db/model.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/src/tendril/filestore/remote.py` & `tendril-filestore-0.2.6/src/tendril/filestore/remote.py`

 * *Files 25% similar despite different names*

```diff
@@ -32,27 +32,33 @@
     def _async_http_client_args(self):
         return {
             'base_url': self.uri,
             'auth': _authenticator
         }
 
     @with_async_client_cl()
-    async def upload(self, file, overwrite=False, client=None):
+    async def upload(self, file, actual_user=None, overwrite=False, client=None):
+        params = {}
+        if actual_user:
+            params['actual_user'] = actual_user
         response = await client.post(f'/v1/filestore/{self.name}/upload',
-                                     files={'file': file})
+                                     files={'file': file}, params=params)
         response.raise_for_status()
         return response.json()
 
     @with_async_client_cl()
-    async def move(self, filename, target_bucket, overwrite=False, client=None):
+    async def move(self, filename, target_bucket, actual_user=None, overwrite=False, client=None):
+        params = {}
+        if actual_user:
+            params['actual_user'] = actual_user
         data = {"to_bucket": target_bucket,
                 "filename": filename,
                 "overwrite": overwrite}
         response = await client.post(f'/v1/filestore/{self.name}/move',
-                                     json=data)
+                                     json=data, params=params)
         response.raise_for_status()
         return response.json()
 
     @with_async_client_cl()
     async def list(self, client=None):
         response = await client.get(f'/v1/filestore/{self.name}/ls_fs')
         response.raise_for_status()
```

### Comparing `tendril-filestore-0.2.5/src/tendril_filestore.egg-info/PKG-INFO` & `tendril-filestore-0.2.6/src/tendril_filestore.egg-info/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tendril-filestore
-Version: 0.2.5
+Version: 0.2.6
 Summary: File Storage and Management Infrastructure for Tendril
 Home-page: https://github.com/tendril-framework/tendril-filestore
 Author: Chintalagiri Shashank
 Author-email: shashank@chintal.in
 Project-URL: Documentation, https://tendril-filestore.readthedocs.io/en/latest
 Project-URL: Bug Tracker, https://github.com/tendril-framework/tendril-filestore/issues
 Project-URL: Source Repository, https://github.com/tendril-framework/tendril-filestore
```

### Comparing `tendril-filestore-0.2.5/src/tendril_filestore.egg-info/SOURCES.txt` & `tendril-filestore-0.2.6/src/tendril_filestore.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/src/tendril_filestore.egg-info/requires.txt` & `tendril-filestore-0.2.6/src/tendril_filestore.egg-info/requires.txt`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/tests/coveralls.py` & `tendril-filestore-0.2.6/tests/coveralls.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.5/tox.ini` & `tendril-filestore-0.2.6/tox.ini`

 * *Files identical despite different names*


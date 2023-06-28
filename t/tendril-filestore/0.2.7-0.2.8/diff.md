# Comparing `tmp/tendril-filestore-0.2.7.tar.gz` & `tmp/tendril-filestore-0.2.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tendril-filestore-0.2.7.tar", last modified: Wed Jun 28 12:01:31 2023, max compression
+gzip compressed data, was "tendril-filestore-0.2.8.tar", last modified: Wed Jun 28 15:40:31 2023, max compression
```

## Comparing `tendril-filestore-0.2.7.tar` & `tendril-filestore-0.2.8.tar`

### file list

```diff
@@ -1,70 +1,70 @@
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.963379 tendril-filestore-0.2.7/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     2122 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/.gitignore
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      638 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/.readthedocs.yml
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      629 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/.travis.yml
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/CHANGELOG.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)    34520 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/LICENSE
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      173 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/MANIFEST.in
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     3543 2023-06-28 12:01:31.963379 tendril-filestore-0.2.7/PKG-INFO
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     2224 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/README.rst
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.959379 tendril-filestore-0.2.7/docs/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     7660 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/docs/Makefile
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.959379 tendril-filestore-0.2.7/docs/_static/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     2727 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/docs/_static/custom.css
--rw-rw-r--   0 chintal   (1000) chintal   (1000)   128918 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/docs/_static/favicon.ico
--rw-rw-r--   0 chintal   (1000) chintal   (1000)    96804 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/docs/_static/logo.png
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     9889 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/docs/_static/logo_packed.png
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.959379 tendril-filestore-0.2.7/docs/_templates/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1713 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/docs/_templates/about.html
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.959379 tendril-filestore-0.2.7/docs/api/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      128 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/docs/api/index.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)    13464 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/docs/conf.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      943 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/docs/index.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1548 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/docs/installation.rst
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.959379 tendril-filestore-0.2.7/docs/usage/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       35 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/docs/usage/standalone.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       49 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/docs/usage/tendril.rst
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      131 2023-06-28 12:01:31.963379 tendril-filestore-0.2.7/setup.cfg
--rwxrwxr-x   0 chintal   (1000) chintal   (1000)     3306 2023-04-20 19:33:00.000000 tendril-filestore-0.2.7/setup.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.955379 tendril-filestore-0.2.7/src/
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.959379 tendril-filestore-0.2.7/src/tendril/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       66 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/src/tendril/__init__.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.959379 tendril-filestore-0.2.7/src/tendril/apiserver/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-12-09 17:57:19.000000 tendril-filestore-0.2.7/src/tendril/apiserver/__init__.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.959379 tendril-filestore-0.2.7/src/tendril/apiserver/routers/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-12-09 17:57:19.000000 tendril-filestore-0.2.7/src/tendril/apiserver/routers/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     6740 2023-06-28 12:00:39.000000 tendril-filestore-0.2.7/src/tendril/apiserver/routers/filestore.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.959379 tendril-filestore-0.2.7/src/tendril/authz/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-11-28 19:36:13.000000 tendril-filestore-0.2.7/src/tendril/authz/__init__.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.959379 tendril-filestore-0.2.7/src/tendril/authz/scopes/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      232 2023-02-27 21:03:32.000000 tendril-filestore-0.2.7/src/tendril/authz/scopes/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      264 2023-03-27 15:39:22.000000 tendril-filestore-0.2.7/src/tendril/authz/scopes/filestore.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.959379 tendril-filestore-0.2.7/src/tendril/common/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2023-04-19 12:09:04.000000 tendril-filestore-0.2.7/src/tendril/common/__init__.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.959379 tendril-filestore-0.2.7/src/tendril/common/filestore/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2023-04-19 11:58:32.000000 tendril-filestore-0.2.7/src/tendril/common/filestore/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1646 2023-04-19 17:38:08.000000 tendril-filestore-0.2.7/src/tendril/common/filestore/formats.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.959379 tendril-filestore-0.2.7/src/tendril/config/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1112 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/src/tendril/config/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     3744 2023-04-20 12:32:50.000000 tendril-filestore-0.2.7/src/tendril/config/filestore.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     3458 2023-04-20 12:32:52.000000 tendril-filestore-0.2.7/src/tendril/config/filestore_core.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.959379 tendril-filestore-0.2.7/src/tendril/filestore/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 21:59:13.000000 tendril-filestore-0.2.7/src/tendril/filestore/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     7292 2023-06-28 10:22:40.000000 tendril-filestore-0.2.7/src/tendril/filestore/actual.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1576 2023-04-21 12:45:53.000000 tendril-filestore-0.2.7/src/tendril/filestore/base.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     2977 2023-04-20 15:56:35.000000 tendril-filestore-0.2.7/src/tendril/filestore/buckets.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.963379 tendril-filestore-0.2.7/src/tendril/filestore/db/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-09 17:57:19.000000 tendril-filestore-0.2.7/src/tendril/filestore/db/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     6250 2023-04-19 17:30:49.000000 tendril-filestore-0.2.7/src/tendril/filestore/db/controller.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1426 2023-04-11 18:49:23.000000 tendril-filestore-0.2.7/src/tendril/filestore/db/model.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     3000 2023-06-28 10:47:37.000000 tendril-filestore-0.2.7/src/tendril/filestore/remote.py
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.963379 tendril-filestore-0.2.7/src/tendril_filestore.egg-info/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     3543 2023-06-28 12:01:31.000000 tendril-filestore-0.2.7/src/tendril_filestore.egg-info/PKG-INFO
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1362 2023-06-28 12:01:31.000000 tendril-filestore-0.2.7/src/tendril_filestore.egg-info/SOURCES.txt
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        1 2023-06-28 12:01:31.000000 tendril-filestore-0.2.7/src/tendril_filestore.egg-info/dependency_links.txt
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      603 2023-06-28 12:01:31.000000 tendril-filestore-0.2.7/src/tendril_filestore.egg-info/requires.txt
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        8 2023-06-28 12:01:31.000000 tendril-filestore-0.2.7/src/tendril_filestore.egg-info/top_level.txt
-drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 12:01:31.963379 tendril-filestore-0.2.7/tests/
--rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/tests/__init__.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)     1060 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/tests/coveralls.py
--rw-rw-r--   0 chintal   (1000) chintal   (1000)      787 2022-12-08 18:25:43.000000 tendril-filestore-0.2.7/tox.ini
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.176894 tendril-filestore-0.2.8/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     2122 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/.gitignore
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      638 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/.readthedocs.yml
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      629 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/.travis.yml
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/CHANGELOG.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)    34520 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/LICENSE
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      173 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/MANIFEST.in
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     3543 2023-06-28 15:40:31.176894 tendril-filestore-0.2.8/PKG-INFO
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     2224 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/README.rst
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.168894 tendril-filestore-0.2.8/docs/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     7660 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/docs/Makefile
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.168894 tendril-filestore-0.2.8/docs/_static/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     2727 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/docs/_static/custom.css
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)   128918 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/docs/_static/favicon.ico
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)    96804 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/docs/_static/logo.png
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     9889 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/docs/_static/logo_packed.png
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.168894 tendril-filestore-0.2.8/docs/_templates/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1713 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/docs/_templates/about.html
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.172894 tendril-filestore-0.2.8/docs/api/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      128 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/docs/api/index.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)    13464 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/docs/conf.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      943 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/docs/index.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1548 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/docs/installation.rst
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.172894 tendril-filestore-0.2.8/docs/usage/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       35 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/docs/usage/standalone.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       49 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/docs/usage/tendril.rst
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      131 2023-06-28 15:40:31.176894 tendril-filestore-0.2.8/setup.cfg
+-rwxrwxr-x   0 chintal   (1000) chintal   (1000)     3306 2023-04-20 19:33:00.000000 tendril-filestore-0.2.8/setup.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.164894 tendril-filestore-0.2.8/src/
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.172894 tendril-filestore-0.2.8/src/tendril/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       66 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/src/tendril/__init__.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.172894 tendril-filestore-0.2.8/src/tendril/apiserver/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-12-09 17:57:19.000000 tendril-filestore-0.2.8/src/tendril/apiserver/__init__.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.172894 tendril-filestore-0.2.8/src/tendril/apiserver/routers/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-12-09 17:57:19.000000 tendril-filestore-0.2.8/src/tendril/apiserver/routers/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     6740 2023-06-28 12:00:39.000000 tendril-filestore-0.2.8/src/tendril/apiserver/routers/filestore.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.172894 tendril-filestore-0.2.8/src/tendril/authz/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2022-11-28 19:36:13.000000 tendril-filestore-0.2.8/src/tendril/authz/__init__.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.172894 tendril-filestore-0.2.8/src/tendril/authz/scopes/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      232 2023-02-27 21:03:32.000000 tendril-filestore-0.2.8/src/tendril/authz/scopes/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      264 2023-03-27 15:39:22.000000 tendril-filestore-0.2.8/src/tendril/authz/scopes/filestore.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.172894 tendril-filestore-0.2.8/src/tendril/common/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)       65 2023-04-19 12:09:04.000000 tendril-filestore-0.2.8/src/tendril/common/__init__.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.172894 tendril-filestore-0.2.8/src/tendril/common/filestore/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2023-04-19 11:58:32.000000 tendril-filestore-0.2.8/src/tendril/common/filestore/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1646 2023-04-19 17:38:08.000000 tendril-filestore-0.2.8/src/tendril/common/filestore/formats.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.172894 tendril-filestore-0.2.8/src/tendril/config/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1112 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/src/tendril/config/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     3744 2023-04-20 12:32:50.000000 tendril-filestore-0.2.8/src/tendril/config/filestore.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     3458 2023-04-20 12:32:52.000000 tendril-filestore-0.2.8/src/tendril/config/filestore_core.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.172894 tendril-filestore-0.2.8/src/tendril/filestore/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 21:59:13.000000 tendril-filestore-0.2.8/src/tendril/filestore/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     7773 2023-06-28 15:39:29.000000 tendril-filestore-0.2.8/src/tendril/filestore/actual.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1576 2023-04-21 12:45:53.000000 tendril-filestore-0.2.8/src/tendril/filestore/base.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     2977 2023-04-20 15:56:35.000000 tendril-filestore-0.2.8/src/tendril/filestore/buckets.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.172894 tendril-filestore-0.2.8/src/tendril/filestore/db/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-09 17:57:19.000000 tendril-filestore-0.2.8/src/tendril/filestore/db/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     6250 2023-04-19 17:30:49.000000 tendril-filestore-0.2.8/src/tendril/filestore/db/controller.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1426 2023-04-11 18:49:23.000000 tendril-filestore-0.2.8/src/tendril/filestore/db/model.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     3000 2023-06-28 10:47:37.000000 tendril-filestore-0.2.8/src/tendril/filestore/remote.py
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.176894 tendril-filestore-0.2.8/src/tendril_filestore.egg-info/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     3543 2023-06-28 15:40:31.000000 tendril-filestore-0.2.8/src/tendril_filestore.egg-info/PKG-INFO
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1362 2023-06-28 15:40:31.000000 tendril-filestore-0.2.8/src/tendril_filestore.egg-info/SOURCES.txt
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        1 2023-06-28 15:40:31.000000 tendril-filestore-0.2.8/src/tendril_filestore.egg-info/dependency_links.txt
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      603 2023-06-28 15:40:31.000000 tendril-filestore-0.2.8/src/tendril_filestore.egg-info/requires.txt
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        8 2023-06-28 15:40:31.000000 tendril-filestore-0.2.8/src/tendril_filestore.egg-info/top_level.txt
+drwxrwxr-x   0 chintal   (1000) chintal   (1000)        0 2023-06-28 15:40:31.176894 tendril-filestore-0.2.8/tests/
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)        0 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/tests/__init__.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)     1060 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/tests/coveralls.py
+-rw-rw-r--   0 chintal   (1000) chintal   (1000)      787 2022-12-08 18:25:43.000000 tendril-filestore-0.2.8/tox.ini
```

### Comparing `tendril-filestore-0.2.7/.gitignore` & `tendril-filestore-0.2.8/.gitignore`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/.readthedocs.yml` & `tendril-filestore-0.2.8/.readthedocs.yml`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/.travis.yml` & `tendril-filestore-0.2.8/.travis.yml`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/LICENSE` & `tendril-filestore-0.2.8/LICENSE`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/PKG-INFO` & `tendril-filestore-0.2.8/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tendril-filestore
-Version: 0.2.7
+Version: 0.2.8
 Summary: File Storage and Management Infrastructure for Tendril
 Home-page: https://github.com/tendril-framework/tendril-filestore
 Author: Chintalagiri Shashank
 Author-email: shashank@chintal.in
 Project-URL: Documentation, https://tendril-filestore.readthedocs.io/en/latest
 Project-URL: Bug Tracker, https://github.com/tendril-framework/tendril-filestore/issues
 Project-URL: Source Repository, https://github.com/tendril-framework/tendril-filestore
```

### Comparing `tendril-filestore-0.2.7/README.rst` & `tendril-filestore-0.2.8/README.rst`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/docs/Makefile` & `tendril-filestore-0.2.8/docs/Makefile`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/docs/_static/custom.css` & `tendril-filestore-0.2.8/docs/_static/custom.css`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/docs/_static/favicon.ico` & `tendril-filestore-0.2.8/docs/_static/favicon.ico`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/docs/_static/logo.png` & `tendril-filestore-0.2.8/docs/_static/logo.png`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/docs/_static/logo_packed.png` & `tendril-filestore-0.2.8/docs/_static/logo_packed.png`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/docs/_templates/about.html` & `tendril-filestore-0.2.8/docs/_templates/about.html`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/docs/conf.py` & `tendril-filestore-0.2.8/docs/conf.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/docs/index.rst` & `tendril-filestore-0.2.8/docs/index.rst`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/docs/installation.rst` & `tendril-filestore-0.2.8/docs/installation.rst`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/setup.py` & `tendril-filestore-0.2.8/setup.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/src/tendril/apiserver/routers/filestore.py` & `tendril-filestore-0.2.8/src/tendril/apiserver/routers/filestore.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/src/tendril/common/filestore/formats.py` & `tendril-filestore-0.2.8/src/tendril/common/filestore/formats.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/src/tendril/config/__init__.py` & `tendril-filestore-0.2.8/src/tendril/config/__init__.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/src/tendril/config/filestore.py` & `tendril-filestore-0.2.8/src/tendril/config/filestore.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/src/tendril/config/filestore_core.py` & `tendril-filestore-0.2.8/src/tendril/config/filestore_core.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/src/tendril/filestore/actual.py` & `tendril-filestore-0.2.8/src/tendril/filestore/actual.py`

 * *Files 5% similar despite different names*

```diff
@@ -56,34 +56,42 @@
 
     @with_db
     def _prep_for_upload(self, bucket, filename, user, overwrite=False, auto_prune=True, session=None):
         subdir, _ = os.path.split(filename)
         if subdir:
             self.fs.makedirs(subdir, recreate=True)
         if bucket.fs.exists(filename):
+            # File exists in the filesystem
             if not overwrite and not auto_prune:
+                # We have no way to remove the existing file.
                 raise FileExistsError(f'{filename} already exists in the {bucket.name} bucket. Delete it first.')
             try:
                 owner = get_storedfile_owner(filename, bucket.id, session=session)
             except NoResultFound:
-                # file exists in fs but not in DB
+                # File exists in fs but not in the DB.
                 if not auto_prune:
+                    # We aren't allowed to remove it.
                     raise FileExistsError(f"'{filename}' already exists in the '{bucket.name}' filesystem but "
                                           f"not in the database. This needs to be manually resolved.")
                 logger.warning(f"'{filename}' exists in the '{bucket.name}' filesystem but "
                                f"not in the database. Pruning. Possible Data Loss.")
                 bucket.fs.remove(filename)
             else:
-                if overwrite:
-                    if not bucket.allow_overwrite:
-                        raise FileExistsError(f'{filename} already exists in the {bucket.name} bucket '
-                                              f'and the bucket prohibits overwrites.')
-                    elif owner.puid != user:
-                        raise FileExistsError(f'{filename} already exists in the {bucket.name} bucket '
-                                              f'and owned by someone else.')
+                # File also exists in the database.
+                if not overwrite:
+                    raise FileExistsError(f'{filename} already exists in the {bucket.name} bucket. Delete it first.')
+                # We may still be able to overwrite it.
+                if not bucket.allow_overwrite:
+                    # Bucket forbids overwriting
+                    raise FileExistsError(f'{filename} already exists in the {bucket.name} bucket '
+                                          f'and the bucket prohibits overwrites.')
+                if owner.puid != user:
+                    # Exisiting file is owned by someone else.
+                    raise FileExistsError(f'{filename} already exists in the {bucket.name} bucket '
+                                          f'and owned by someone else.')
                 logger.warning(f"Overwriting file {filename} in bucket {bucket.name}.")
                 bucket.delete(filename, user, session=session)
 
     @with_db
     def upload(self, file, user, overwrite=False, session=None):
         filename = file.filename
         self._prep_for_upload(self, filename, user, overwrite)
```

### Comparing `tendril-filestore-0.2.7/src/tendril/filestore/base.py` & `tendril-filestore-0.2.8/src/tendril/filestore/base.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/src/tendril/filestore/buckets.py` & `tendril-filestore-0.2.8/src/tendril/filestore/buckets.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/src/tendril/filestore/db/controller.py` & `tendril-filestore-0.2.8/src/tendril/filestore/db/controller.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/src/tendril/filestore/db/model.py` & `tendril-filestore-0.2.8/src/tendril/filestore/db/model.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/src/tendril/filestore/remote.py` & `tendril-filestore-0.2.8/src/tendril/filestore/remote.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/src/tendril_filestore.egg-info/PKG-INFO` & `tendril-filestore-0.2.8/src/tendril_filestore.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tendril-filestore
-Version: 0.2.7
+Version: 0.2.8
 Summary: File Storage and Management Infrastructure for Tendril
 Home-page: https://github.com/tendril-framework/tendril-filestore
 Author: Chintalagiri Shashank
 Author-email: shashank@chintal.in
 Project-URL: Documentation, https://tendril-filestore.readthedocs.io/en/latest
 Project-URL: Bug Tracker, https://github.com/tendril-framework/tendril-filestore/issues
 Project-URL: Source Repository, https://github.com/tendril-framework/tendril-filestore
```

### Comparing `tendril-filestore-0.2.7/src/tendril_filestore.egg-info/SOURCES.txt` & `tendril-filestore-0.2.8/src/tendril_filestore.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/src/tendril_filestore.egg-info/requires.txt` & `tendril-filestore-0.2.8/src/tendril_filestore.egg-info/requires.txt`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/tests/coveralls.py` & `tendril-filestore-0.2.8/tests/coveralls.py`

 * *Files identical despite different names*

### Comparing `tendril-filestore-0.2.7/tox.ini` & `tendril-filestore-0.2.8/tox.ini`

 * *Files identical despite different names*


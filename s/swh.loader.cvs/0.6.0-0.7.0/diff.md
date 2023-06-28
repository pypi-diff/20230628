# Comparing `tmp/swh.loader.cvs-0.6.0.tar.gz` & `tmp/swh.loader.cvs-0.7.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/swh.loader.cvs-0.6.0.tar", last modified: Mon Mar 13 11:21:07 2023, max compression
+gzip compressed data, was "swh.loader.cvs-0.7.0.tar", last modified: Wed Jun 28 09:26:49 2023, max compression
```

## Comparing `swh.loader.cvs-0.6.0.tar` & `swh.loader.cvs-0.7.0.tar`

### file list

```diff
@@ -1,95 +1,96 @@
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/
--rw-r--r--   0 jenkins    (115) docker     (999)       83 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/.git-blame-ignore-revs
--rw-r--r--   0 jenkins    (115) docker     (999)      140 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/.gitignore
--rw-r--r--   0 jenkins    (115) docker     (999)     1038 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/.pre-commit-config.yaml
--rw-r--r--   0 jenkins    (115) docker     (999)      112 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/AUTHORS
--rw-r--r--   0 jenkins    (115) docker     (999)     3397 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/CODE_OF_CONDUCT.md
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/CONTRIBUTORS
--rw-r--r--   0 jenkins    (115) docker     (999)    34523 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/LICENSE
--rw-r--r--   0 jenkins    (115) docker     (999)      112 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/MANIFEST.in
--rw-r--r--   0 jenkins    (115) docker     (999)      163 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/Makefile
--rw-r--r--   0 jenkins    (115) docker     (999)     8569 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/PKG-INFO
--rw-r--r--   0 jenkins    (115) docker     (999)     7650 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/README.rst
--rw-r--r--   0 jenkins    (115) docker     (999)      574 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/conftest.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/docs/
--rw-r--r--   0 jenkins    (115) docker     (999)       24 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/docs/.gitignore
--rw-r--r--   0 jenkins    (115) docker     (999)       39 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/docs/Makefile
--rw-r--r--   0 jenkins    (115) docker     (999)     7650 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/docs/README.rst
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/docs/_static/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/docs/_static/.placeholder
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/docs/_templates/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/docs/_templates/.placeholder
--rw-r--r--   0 jenkins    (115) docker     (999)       43 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/docs/conf.py
--rw-r--r--   0 jenkins    (115) docker     (999)      265 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/docs/index.rst
--rw-r--r--   0 jenkins    (115) docker     (999)      401 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/mypy.ini
--rw-r--r--   0 jenkins    (115) docker     (999)      304 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/pyproject.toml
--rw-r--r--   0 jenkins    (115) docker     (999)      124 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/pytest.ini
--rw-r--r--   0 jenkins    (115) docker     (999)      226 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/requirements-swh.txt
--rw-r--r--   0 jenkins    (115) docker     (999)       42 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/requirements-test.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      247 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/requirements.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      193 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/setup.cfg
--rwxr-xr-x   0 jenkins    (115) docker     (999)     2874 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/setup.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh/
--rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/__init__.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh/loader/
--rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/__init__.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/
--rw-r--r--   0 jenkins    (115) docker     (999)      465 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/__init__.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/cvs2gitdump/
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/cvs2gitdump/.github/
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/cvs2gitdump/.github/workflows/
--rw-r--r--   0 jenkins    (115) docker     (999)     1102 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/cvs2gitdump/.github/workflows/python-app.yml
--rw-r--r--   0 jenkins    (115) docker     (999)     5321 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/cvs2gitdump/README.md
--rw-r--r--   0 jenkins    (115) docker     (999)     2559 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/cvs2gitdump/cvs2gitdump.1
--rw-r--r--   0 jenkins    (115) docker     (999)    27139 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/cvs2gitdump/cvs2gitdump.py
--rw-r--r--   0 jenkins    (115) docker     (999)    17961 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/cvsclient.py
--rw-r--r--   0 jenkins    (115) docker     (999)    27815 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/loader.py
--rw-r--r--   0 jenkins    (115) docker     (999)       27 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/py.typed
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/
--rw-r--r--   0 jenkins    (115) docker     (999)    34520 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/COPYRIGHT
--rw-r--r--   0 jenkins    (115) docker     (999)       81 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/Makefile.test
--rw-r--r--   0 jenkins    (115) docker     (999)       53 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/README
--rw-r--r--   0 jenkins    (115) docker     (999)     2218 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/bar,v
--rw-r--r--   0 jenkins    (115) docker     (999)       84 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/extconf.rb
--rw-r--r--   0 jenkins    (115) docker     (999)      364 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/moo,v
--rw-r--r--   0 jenkins    (115) docker     (999)    18806 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/py-rcsparse.c
--rw-r--r--   0 jenkins    (115) docker     (999)    23810 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/queue.h
--rw-r--r--   0 jenkins    (115) docker     (999)    13359 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/rb-rcsparse.c
--rw-r--r--   0 jenkins    (115) docker     (999)    28501 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/rcsparse.c
--rw-r--r--   0 jenkins    (115) docker     (999)     2480 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/rcsparse.h
--rwxr-xr-x   0 jenkins    (115) docker     (999)      210 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/setup.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1307 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/test.rb
--rw-r--r--   0 jenkins    (115) docker     (999)    25651 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/tree.h
--rw-r--r--   0 jenkins    (115) docker     (999)      914 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse.pyi
--rw-r--r--   0 jenkins    (115) docker     (999)    18352 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/rlog.py
--rw-r--r--   0 jenkins    (115) docker     (999)      725 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tasks.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/
--rw-r--r--   0 jenkins    (115) docker     (999)    18076 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/cpmixin.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)    17083 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/dino-commitid.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)    18140 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/dino-readded-file.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)    12305 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)    12421 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository2.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)    12376 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository3.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)    12675 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository4.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)    12380 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository5.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)    12408 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository6.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)    12387 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository7.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)    12967 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository8.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)    12431 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository9.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)   536935 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/nano.rlog.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)    31678 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/rcsbase-log-kw-test-repo.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)    15002 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/runbaby.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)     3228 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/unsafe_rlog_with_unsafe_relative_path.rlog
--rw-r--r--   0 jenkins    (115) docker     (999)      551 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/unsafe_rlog_wrong_arborescence.rlog
--rw-r--r--   0 jenkins    (115) docker     (999)     2402 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/test_cvsclient.py
--rw-r--r--   0 jenkins    (115) docker     (999)    41010 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/test_loader.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1237 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/swh/loader/cvs/tests/test_tasks.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh.loader.cvs.egg-info/
--rw-r--r--   0 jenkins    (115) docker     (999)     8569 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh.loader.cvs.egg-info/PKG-INFO
--rw-r--r--   0 jenkins    (115) docker     (999)     2435 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh.loader.cvs.egg-info/SOURCES.txt
--rw-r--r--   0 jenkins    (115) docker     (999)        1 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh.loader.cvs.egg-info/dependency_links.txt
--rw-r--r--   0 jenkins    (115) docker     (999)       51 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh.loader.cvs.egg-info/entry_points.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      175 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh.loader.cvs.egg-info/requires.txt
--rw-r--r--   0 jenkins    (115) docker     (999)        4 2023-03-13 11:21:07.000000 swh.loader.cvs-0.6.0/swh.loader.cvs.egg-info/top_level.txt
--rw-r--r--   0 jenkins    (115) docker     (999)     1694 2023-03-13 11:21:05.000000 swh.loader.cvs-0.6.0/tox.ini
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:49.639590 swh.loader.cvs-0.7.0/
+-rw-r--r--   0 jenkins    (115) docker     (999)       83 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/.git-blame-ignore-revs
+-rw-r--r--   0 jenkins    (115) docker     (999)      140 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/.gitignore
+-rw-r--r--   0 jenkins    (115) docker     (999)     1038 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/.pre-commit-config.yaml
+-rw-r--r--   0 jenkins    (115) docker     (999)      112 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/AUTHORS
+-rw-r--r--   0 jenkins    (115) docker     (999)     3397 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/CODE_OF_CONDUCT.md
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/CONTRIBUTORS
+-rw-r--r--   0 jenkins    (115) docker     (999)    34523 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/LICENSE
+-rw-r--r--   0 jenkins    (115) docker     (999)      112 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/MANIFEST.in
+-rw-r--r--   0 jenkins    (115) docker     (999)      163 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/Makefile
+-rw-r--r--   0 jenkins    (115) docker     (999)     8569 2023-06-28 09:26:49.639590 swh.loader.cvs-0.7.0/PKG-INFO
+-rw-r--r--   0 jenkins    (115) docker     (999)     7650 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/README.rst
+-rw-r--r--   0 jenkins    (115) docker     (999)      574 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/conftest.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:49.627590 swh.loader.cvs-0.7.0/docs/
+-rw-r--r--   0 jenkins    (115) docker     (999)       24 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/docs/.gitignore
+-rw-r--r--   0 jenkins    (115) docker     (999)       39 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/docs/Makefile
+-rw-r--r--   0 jenkins    (115) docker     (999)     7650 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/docs/README.rst
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:49.627590 swh.loader.cvs-0.7.0/docs/_static/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/docs/_static/.placeholder
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:49.627590 swh.loader.cvs-0.7.0/docs/_templates/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/docs/_templates/.placeholder
+-rw-r--r--   0 jenkins    (115) docker     (999)       43 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/docs/conf.py
+-rw-r--r--   0 jenkins    (115) docker     (999)      265 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/docs/index.rst
+-rw-r--r--   0 jenkins    (115) docker     (999)      401 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/mypy.ini
+-rw-r--r--   0 jenkins    (115) docker     (999)      304 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/pyproject.toml
+-rw-r--r--   0 jenkins    (115) docker     (999)      124 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/pytest.ini
+-rw-r--r--   0 jenkins    (115) docker     (999)      226 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/requirements-swh.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)       42 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/requirements-test.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      247 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/requirements.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      193 2023-06-28 09:26:49.639590 swh.loader.cvs-0.7.0/setup.cfg
+-rwxr-xr-x   0 jenkins    (115) docker     (999)     2874 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/setup.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:49.627590 swh.loader.cvs-0.7.0/swh/
+-rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/__init__.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:49.631590 swh.loader.cvs-0.7.0/swh/loader/
+-rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/__init__.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:49.631590 swh.loader.cvs-0.7.0/swh/loader/cvs/
+-rw-r--r--   0 jenkins    (115) docker     (999)      465 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/__init__.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:49.631590 swh.loader.cvs-0.7.0/swh/loader/cvs/cvs2gitdump/
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:49.623590 swh.loader.cvs-0.7.0/swh/loader/cvs/cvs2gitdump/.github/
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:49.631590 swh.loader.cvs-0.7.0/swh/loader/cvs/cvs2gitdump/.github/workflows/
+-rw-r--r--   0 jenkins    (115) docker     (999)     1102 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/cvs2gitdump/.github/workflows/python-app.yml
+-rw-r--r--   0 jenkins    (115) docker     (999)     5321 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/cvs2gitdump/README.md
+-rw-r--r--   0 jenkins    (115) docker     (999)     2559 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/cvs2gitdump/cvs2gitdump.1
+-rw-r--r--   0 jenkins    (115) docker     (999)    27139 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/cvs2gitdump/cvs2gitdump.py
+-rw-r--r--   0 jenkins    (115) docker     (999)    17961 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/cvsclient.py
+-rw-r--r--   0 jenkins    (115) docker     (999)    28243 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/loader.py
+-rw-r--r--   0 jenkins    (115) docker     (999)       27 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/py.typed
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:49.635590 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/
+-rw-r--r--   0 jenkins    (115) docker     (999)    34520 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/COPYRIGHT
+-rw-r--r--   0 jenkins    (115) docker     (999)       81 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/Makefile.test
+-rw-r--r--   0 jenkins    (115) docker     (999)       53 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/README
+-rw-r--r--   0 jenkins    (115) docker     (999)     2218 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/bar,v
+-rw-r--r--   0 jenkins    (115) docker     (999)       84 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/extconf.rb
+-rw-r--r--   0 jenkins    (115) docker     (999)      364 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/moo,v
+-rw-r--r--   0 jenkins    (115) docker     (999)    18806 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/py-rcsparse.c
+-rw-r--r--   0 jenkins    (115) docker     (999)    23810 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/queue.h
+-rw-r--r--   0 jenkins    (115) docker     (999)    13359 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/rb-rcsparse.c
+-rw-r--r--   0 jenkins    (115) docker     (999)    28501 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/rcsparse.c
+-rw-r--r--   0 jenkins    (115) docker     (999)     2480 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/rcsparse.h
+-rwxr-xr-x   0 jenkins    (115) docker     (999)      210 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/setup.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1307 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/test.rb
+-rw-r--r--   0 jenkins    (115) docker     (999)    25651 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/tree.h
+-rw-r--r--   0 jenkins    (115) docker     (999)      914 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse.pyi
+-rw-r--r--   0 jenkins    (115) docker     (999)    18352 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/rlog.py
+-rw-r--r--   0 jenkins    (115) docker     (999)      725 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tasks.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:49.635590 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:49.639590 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/
+-rw-r--r--   0 jenkins    (115) docker     (999)    21731 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/alizagameapi.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    18076 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/cpmixin.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    17083 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/dino-commitid.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    18140 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/dino-readded-file.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    12305 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    12421 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository2.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    12376 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository3.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    12675 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository4.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    12380 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository5.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    12408 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository6.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    12387 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository7.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    12967 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository8.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    12431 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository9.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)   536935 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/nano.rlog.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    31678 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/rcsbase-log-kw-test-repo.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    15002 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/runbaby.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)     3228 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/unsafe_rlog_with_unsafe_relative_path.rlog
+-rw-r--r--   0 jenkins    (115) docker     (999)      551 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/unsafe_rlog_wrong_arborescence.rlog
+-rw-r--r--   0 jenkins    (115) docker     (999)     2402 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/test_cvsclient.py
+-rw-r--r--   0 jenkins    (115) docker     (999)    42919 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/test_loader.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1449 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/swh/loader/cvs/tests/test_tasks.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:26:49.631590 swh.loader.cvs-0.7.0/swh.loader.cvs.egg-info/
+-rw-r--r--   0 jenkins    (115) docker     (999)     8569 2023-06-28 09:26:49.000000 swh.loader.cvs-0.7.0/swh.loader.cvs.egg-info/PKG-INFO
+-rw-r--r--   0 jenkins    (115) docker     (999)     2478 2023-06-28 09:26:49.000000 swh.loader.cvs-0.7.0/swh.loader.cvs.egg-info/SOURCES.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)        1 2023-06-28 09:26:49.000000 swh.loader.cvs-0.7.0/swh.loader.cvs.egg-info/dependency_links.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)       51 2023-06-28 09:26:49.000000 swh.loader.cvs-0.7.0/swh.loader.cvs.egg-info/entry_points.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      175 2023-06-28 09:26:49.000000 swh.loader.cvs-0.7.0/swh.loader.cvs.egg-info/requires.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)        4 2023-06-28 09:26:49.000000 swh.loader.cvs-0.7.0/swh.loader.cvs.egg-info/top_level.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)     1694 2023-06-28 09:26:44.000000 swh.loader.cvs-0.7.0/tox.ini
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `swh.loader.cvs-0.6.0/.pre-commit-config.yaml` & `swh.loader.cvs-0.7.0/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/CODE_OF_CONDUCT.md` & `swh.loader.cvs-0.7.0/CODE_OF_CONDUCT.md`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/LICENSE` & `swh.loader.cvs-0.7.0/LICENSE`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/PKG-INFO` & `swh.loader.cvs-0.7.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: swh.loader.cvs
-Version: 0.6.0
+Version: 0.7.0
 Summary: Software Heritage CVS Loader
 Home-page: https://forge.softwareheritage.org/diffusion/swh-loader-cvs
 Author: Software Heritage developers
 Author-email: swh-devel@inria.fr
 Project-URL: Bug Reports, https://forge.softwareheritage.org/maniphest
 Project-URL: Funding, https://www.softwareheritage.org/donate
 Project-URL: Source, https://forge.softwareheritage.org/source/swh-loader-cvs
```

### Comparing `swh.loader.cvs-0.6.0/README.rst` & `swh.loader.cvs-0.7.0/README.rst`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/conftest.py` & `swh.loader.cvs-0.7.0/conftest.py`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/docs/README.rst` & `swh.loader.cvs-0.7.0/docs/README.rst`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/setup.py` & `swh.loader.cvs-0.7.0/setup.py`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/cvs2gitdump/.github/workflows/python-app.yml` & `swh.loader.cvs-0.7.0/swh/loader/cvs/cvs2gitdump/.github/workflows/python-app.yml`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/cvs2gitdump/README.md` & `swh.loader.cvs-0.7.0/swh/loader/cvs/cvs2gitdump/README.md`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/cvs2gitdump/cvs2gitdump.1` & `swh.loader.cvs-0.7.0/swh/loader/cvs/cvs2gitdump/cvs2gitdump.1`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/cvs2gitdump/cvs2gitdump.py` & `swh.loader.cvs-0.7.0/swh/loader/cvs/cvs2gitdump/cvs2gitdump.py`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/cvsclient.py` & `swh.loader.cvs-0.7.0/swh/loader/cvs/cvsclient.py`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/loader.py` & `swh.loader.cvs-0.7.0/swh/loader/cvs/loader.py`

 * *Files 2% similar despite different names*

```diff
@@ -397,17 +397,22 @@
         rsync = subprocess.run(rsync_cmd, **run_opts)
         rsync.check_returncode()
         return rsync
 
     def fetch_cvs_repo_with_rsync(self, host: str, path: str) -> None:
         # URL *must* end with a trailing slash in order to get CVSROOT listed
         url = "rsync://%s%s/" % (host, os.path.dirname(path))
-        rsync = self.execute_rsync(
-            ["rsync", url], capture_output=True, encoding="utf-8"
-        )
+        try:
+            rsync = self.execute_rsync(
+                ["rsync", url], capture_output=True, encoding="utf-8"
+            )
+        except subprocess.CalledProcessError as cpe:
+            if cpe.returncode == 23 and "No such file or directory" in cpe.stderr:
+                raise NotFound("CVS repository not found at {url}")
+            raise
         have_cvsroot = False
         have_module = False
         for line in rsync.stdout.split("\n"):
             self.log.debug("rsync server: %s", line)
             if line.endswith(" CVSROOT"):
                 have_cvsroot = True
             elif line.endswith(" %s" % self.cvs_module_name):
@@ -498,17 +503,18 @@
                     self.cvsroot_path,
                 )
 
             # The file CVSROOT/config will usually contain ASCII data only.
             # We allow UTF-8 just in case. Other encodings may result in an
             # error and will require manual intervention, for now.
             cvsconfig_path = os.path.join(self.cvsroot_path, "CVSROOT", "config")
-            cvsconfig = open(cvsconfig_path, mode="r", encoding="utf-8")
-            self.configure_custom_id_keyword(cvsconfig)
-            cvsconfig.close()
+            if os.path.exists(cvsconfig_path):
+                cvsconfig = open(cvsconfig_path, mode="r", encoding="utf-8")
+                self.configure_custom_id_keyword(cvsconfig)
+                cvsconfig.close()
 
             # Unfortunately, there is no way to convert CVS history in an
             # iterative fashion because the data is not indexed by any kind
             # of changeset ID. We need to walk the history of each and every
             # RCS file in the repository during every visit, even if no new
             # changes will be added to the SWH archive afterwards.
             # "CVS’s repository is the software equivalent of a telephone book
@@ -611,15 +617,14 @@
             raise NotFound(f"Invalid CVS origin URL '{self.origin.url}'")
 
     def fetch_data(self) -> bool:
         """Fetch the next CVS revision."""
         try:
             data = next(self.swh_revision_gen)
         except StopIteration:
-            assert self._last_revision is not None
             self.snapshot = self.generate_and_load_snapshot(self._last_revision)
             self.log.debug(
                 "SWH snapshot ID: %s", hashutil.hash_to_hex(self.snapshot.id)
             )
             self.flush()
             self.loaded_snapshot_id = self.snapshot.id
             return False
@@ -663,30 +668,36 @@
             author=author,
             committer=author,
             synthetic=True,
             extra_headers=[],
             parents=tuple(parents),
         )
 
-    def generate_and_load_snapshot(self, revision: Revision) -> Snapshot:
+    def generate_and_load_snapshot(
+        self, revision: Optional[Revision] = None
+    ) -> Snapshot:
         """Create the snapshot either from existing revision.
 
         Args:
             revision (dict): Last revision seen if any (None by default)
 
         Returns:
             Optional[Snapshot] The newly created snapshot
 
         """
         snap = Snapshot(
-            branches={
-                DEFAULT_BRANCH: SnapshotBranch(
-                    target=revision.id, target_type=TargetType.REVISION
-                )
-            }
+            branches=(
+                {
+                    DEFAULT_BRANCH: SnapshotBranch(
+                        target=revision.id, target_type=TargetType.REVISION
+                    )
+                }
+                if revision is not None
+                else {}
+            )
         )
         self.log.debug("snapshot: %s", snap)
         self.storage.snapshot_add([snap])
         return snap
 
     def store_data(self) -> None:
         "Add our current CVS changeset to the archive."
@@ -699,15 +710,15 @@
         self._contents = []
         self._directories = []
         self._revisions = []
 
     def load_status(self) -> Dict[str, Any]:
         if self.snapshot is None:
             load_status = "failed"
-        elif self.last_snapshot == self.snapshot:
+        elif self.last_snapshot == self.snapshot or not self.snapshot.branches:
             load_status = "uneventful"
         else:
             load_status = "eventful"
         return {
             "status": load_status,
         }
```

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/COPYRIGHT` & `swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/COPYRIGHT`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/bar,v` & `swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/bar,v`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/py-rcsparse.c` & `swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/py-rcsparse.c`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/queue.h` & `swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/queue.h`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/rb-rcsparse.c` & `swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/rb-rcsparse.c`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/rcsparse.c` & `swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/rcsparse.c`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/rcsparse.h` & `swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/rcsparse.h`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/test.rb` & `swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/test.rb`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse/tree.h` & `swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse/tree.h`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/rcsparse.pyi` & `swh.loader.cvs-0.7.0/swh/loader/cvs/rcsparse.pyi`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/rlog.py` & `swh.loader.cvs-0.7.0/swh/loader/cvs/rlog.py`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tasks.py` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tasks.py`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/cpmixin.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/cpmixin.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/dino-commitid.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/dino-commitid.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/dino-readded-file.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/dino-readded-file.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository2.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository2.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository3.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository3.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository4.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository4.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository5.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository5.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository6.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository6.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository7.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository7.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository8.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository8.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/greek-repository9.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/greek-repository9.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/nano.rlog.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/nano.rlog.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/rcsbase-log-kw-test-repo.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/rcsbase-log-kw-test-repo.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/runbaby.tgz` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/runbaby.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/unsafe_rlog_with_unsafe_relative_path.rlog` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/unsafe_rlog_with_unsafe_relative_path.rlog`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/data/unsafe_rlog_wrong_arborescence.rlog` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/data/unsafe_rlog_wrong_arborescence.rlog`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/test_cvsclient.py` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/test_cvsclient.py`

 * *Files identical despite different names*

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/test_loader.py` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/test_loader.py`

 * *Files 2% similar despite different names*

```diff
@@ -1354,7 +1354,61 @@
         repo_url,
         status="full",
         type="cvs",
         snapshot=CPMIXIN_SNAPSHOT.id,
     )
 
     check_snapshot(CPMIXIN_SNAPSHOT, loader.storage)
+
+
+def test_loader_cvs_with_missing_cvs_config_file(swh_storage, datadir, tmp_path):
+    archive_name = "greek-repository"
+    archive_path = os.path.join(datadir, f"{archive_name}.tgz")
+    repo_url = prepare_repository_from_archive(archive_path, archive_name, tmp_path)
+    config_path = os.path.join(repo_url.replace("file://", ""), "CVSROOT/config")
+
+    assert os.path.exists(config_path)
+    os.remove(config_path)
+    repo_url += "/greek-tree"  # CVS module name
+    loader = CvsLoader(
+        swh_storage, repo_url, cvsroot_path=os.path.join(tmp_path, archive_name)
+    )
+
+    assert loader.load() == {"status": "eventful"}
+
+
+def test_loader_cvs_rsync_not_found(swh_storage, mocker):
+    origin_url = "rsync://example.org/cvsroot/module"
+    loader = CvsLoader(swh_storage, origin_url)
+    mocker.patch.object(
+        loader, "execute_rsync"
+    ).side_effect = subprocess.CalledProcessError(
+        returncode=23,
+        cmd=["rsync", origin_url],
+        stderr='rsync: change_dir "/module" (in cvsroot) failed: No such file or directory (2)',
+    )
+    assert loader.load() == {"status": "uneventful"}
+    visit_status = (
+        swh_storage.origin_visit_get_with_statuses(origin_url).results[-1].statuses[-1]
+    )
+    assert visit_status.status == "not_found"
+
+
+def test_loader_cvs_empty_repository(swh_storage, datadir, tmp_path):
+    archive_name = "alizagameapi"
+    archive_path = os.path.join(datadir, f"{archive_name}.tgz")
+    repo_url = prepare_repository_from_archive(archive_path, archive_name, tmp_path)
+    repo_url += "/config"  # CVS module name
+
+    loader = CvsLoader(
+        swh_storage, repo_url, cvsroot_path=os.path.join(tmp_path, archive_name)
+    )
+
+    assert loader.load() == {"status": "uneventful"}
+
+    assert_last_visit_matches(
+        loader.storage,
+        repo_url,
+        status="full",
+        type="cvs",
+        snapshot=Snapshot(branches={}).id,
+    )
```

### Comparing `swh.loader.cvs-0.6.0/swh/loader/cvs/tests/test_tasks.py` & `swh.loader.cvs-0.7.0/swh/loader/cvs/tests/test_tasks.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,21 +1,28 @@
-# Copyright (C) 2019-2022  The Software Heritage developers
+# Copyright (C) 2019-2023  The Software Heritage developers
 # See the AUTHORS file at the top-level directory of this distribution
 # License: GNU General Public License version 3, or any later version
 # See top-level LICENSE file for more information
 
 import uuid
 
 import pytest
 
+from swh.loader.tests import assert_module_tasks_are_scheduler_ready
 from swh.scheduler.model import ListedOrigin, Lister
 
 NAMESPACE = "swh.loader.cvs"
 
 
+def test_tasks_loader_visit_type_match_task_name():
+    import swh.loader.cvs
+
+    assert_module_tasks_are_scheduler_ready([swh.loader.cvs])
+
+
 @pytest.fixture
 def cvs_lister():
     return Lister(name="cvs-lister", instance_name="example", id=uuid.uuid4())
 
 
 @pytest.fixture
 def cvs_listed_origin(cvs_lister):
```

### Comparing `swh.loader.cvs-0.6.0/swh.loader.cvs.egg-info/PKG-INFO` & `swh.loader.cvs-0.7.0/swh.loader.cvs.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: swh.loader.cvs
-Version: 0.6.0
+Version: 0.7.0
 Summary: Software Heritage CVS Loader
 Home-page: https://forge.softwareheritage.org/diffusion/swh-loader-cvs
 Author: Software Heritage developers
 Author-email: swh-devel@inria.fr
 Project-URL: Bug Reports, https://forge.softwareheritage.org/maniphest
 Project-URL: Funding, https://www.softwareheritage.org/donate
 Project-URL: Source, https://forge.softwareheritage.org/source/swh-loader-cvs
```

### Comparing `swh.loader.cvs-0.6.0/swh.loader.cvs.egg-info/SOURCES.txt` & `swh.loader.cvs-0.7.0/swh.loader.cvs.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -57,14 +57,15 @@
 swh/loader/cvs/rcsparse/rcsparse.h
 swh/loader/cvs/rcsparse/setup.py
 swh/loader/cvs/rcsparse/test.rb
 swh/loader/cvs/rcsparse/tree.h
 swh/loader/cvs/tests/test_cvsclient.py
 swh/loader/cvs/tests/test_loader.py
 swh/loader/cvs/tests/test_tasks.py
+swh/loader/cvs/tests/data/alizagameapi.tgz
 swh/loader/cvs/tests/data/cpmixin.tgz
 swh/loader/cvs/tests/data/dino-commitid.tgz
 swh/loader/cvs/tests/data/dino-readded-file.tgz
 swh/loader/cvs/tests/data/greek-repository.tgz
 swh/loader/cvs/tests/data/greek-repository2.tgz
 swh/loader/cvs/tests/data/greek-repository3.tgz
 swh/loader/cvs/tests/data/greek-repository4.tgz
```

### Comparing `swh.loader.cvs-0.6.0/tox.ini` & `swh.loader.cvs-0.7.0/tox.ini`

 * *Files identical despite different names*


# Comparing `tmp/swh.loader.bzr-1.3.5.tar.gz` & `tmp/swh.loader.bzr-1.3.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/swh.loader.bzr-1.3.5.tar", last modified: Wed May  3 14:26:43 2023, max compression
+gzip compressed data, was "swh.loader.bzr-1.3.6.tar", last modified: Wed Jun 28 09:58:01 2023, max compression
```

## Comparing `swh.loader.bzr-1.3.5.tar` & `swh.loader.bzr-1.3.6.tar`

### file list

```diff
@@ -1,74 +1,74 @@
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/
--rw-r--r--   0 jenkins    (115) docker     (999)       83 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/.git-blame-ignore-revs
--rw-r--r--   0 jenkins    (115) docker     (999)      122 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/.gitignore
--rw-r--r--   0 jenkins    (115) docker     (999)      848 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/.pre-commit-config.yaml
--rw-r--r--   0 jenkins    (115) docker     (999)      112 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/AUTHORS
--rw-r--r--   0 jenkins    (115) docker     (999)     3397 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/CODE_OF_CONDUCT.md
--rw-r--r--   0 jenkins    (115) docker     (999)       26 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/CONTRIBUTORS
--rw-r--r--   0 jenkins    (115) docker     (999)    35147 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/LICENSE
--rw-r--r--   0 jenkins    (115) docker     (999)      179 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/MANIFEST.in
--rw-r--r--   0 jenkins    (115) docker     (999)      163 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/Makefile
--rw-r--r--   0 jenkins    (115) docker     (999)     1215 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/PKG-INFO
--rw-r--r--   0 jenkins    (115) docker     (999)      291 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/README.rst
--rw-r--r--   0 jenkins    (115) docker     (999)      571 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/conftest.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/docs/
--rw-r--r--   0 jenkins    (115) docker     (999)       24 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/docs/.gitignore
--rw-r--r--   0 jenkins    (115) docker     (999)       39 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/docs/Makefile
--rw-r--r--   0 jenkins    (115) docker     (999)      291 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/docs/README.rst
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/docs/_static/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/docs/_static/.placeholder
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/docs/_templates/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/docs/_templates/.placeholder
--rw-r--r--   0 jenkins    (115) docker     (999)       43 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/docs/conf.py
--rw-r--r--   0 jenkins    (115) docker     (999)     2044 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/docs/how-bzr-works.rst
--rw-r--r--   0 jenkins    (115) docker     (999)      257 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/docs/index.rst
--rw-r--r--   0 jenkins    (115) docker     (999)      361 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/mypy.ini
--rw-r--r--   0 jenkins    (115) docker     (999)      237 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/pyproject.toml
--rw-r--r--   0 jenkins    (115) docker     (999)       62 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/pytest.ini
--rw-r--r--   0 jenkins    (115) docker     (999)       90 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/requirements-swh.txt
--rw-r--r--   0 jenkins    (115) docker     (999)       96 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/requirements-test.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      345 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/requirements.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      120 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/setup.cfg
--rwxr-xr-x   0 jenkins    (115) docker     (999)     2704 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/setup.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/swh/
--rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/__init__.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/swh/loader/
--rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/__init__.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/
--rw-r--r--   0 jenkins    (115) docker     (999)      470 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/__init__.py
--rw-r--r--   0 jenkins    (115) docker     (999)    26867 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/loader.py
--rw-r--r--   0 jenkins    (115) docker     (999)       27 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/py.typed
--rw-r--r--   0 jenkins    (115) docker     (999)      768 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tasks.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/__init__.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1140 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/conftest.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/
--rw-r--r--   0 jenkins    (115) docker     (999)      191 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/broken-tags.sh
--rw-r--r--   0 jenkins    (115) docker     (999)      980 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/broken-tags.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)      275 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/does-not-support-tags.sh
--rw-r--r--   0 jenkins    (115) docker     (999)     1049 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/does-not-support-tags.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)      106 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/empty.sh
--rw-r--r--   0 jenkins    (115) docker     (999)      962 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/empty.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)      400 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/ghosts.py
--rw-r--r--   0 jenkins    (115) docker     (999)     2451 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/ghosts.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)      636 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/metadata-and-type-changes.sh
--rw-r--r--   0 jenkins    (115) docker     (999)    13831 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/metadata-and-type-changes.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)      139 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/needs-upgrade.sh
--rw-r--r--   0 jenkins    (115) docker     (999)      880 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/needs-upgrade.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)      213 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/no-branch.sh
--rw-r--r--   0 jenkins    (115) docker     (999)      882 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/no-branch.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)      829 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/nominal.sh
--rw-r--r--   0 jenkins    (115) docker     (999)    11366 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/nominal.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)      360 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/renames.sh
--rw-r--r--   0 jenkins    (115) docker     (999)     5068 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/renames.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)       27 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/py.typed
--rw-r--r--   0 jenkins    (115) docker     (999)    15635 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/test_loader.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1260 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/swh/loader/bzr/tests/test_tasks.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/swh.loader.bzr.egg-info/
--rw-r--r--   0 jenkins    (115) docker     (999)     1215 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/swh.loader.bzr.egg-info/PKG-INFO
--rw-r--r--   0 jenkins    (115) docker     (999)     1716 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/swh.loader.bzr.egg-info/SOURCES.txt
--rw-r--r--   0 jenkins    (115) docker     (999)        1 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/swh.loader.bzr.egg-info/dependency_links.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      118 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/swh.loader.bzr.egg-info/entry_points.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      200 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/swh.loader.bzr.egg-info/requires.txt
--rw-r--r--   0 jenkins    (115) docker     (999)        4 2023-05-03 14:26:43.000000 swh.loader.bzr-1.3.5/swh.loader.bzr.egg-info/top_level.txt
--rw-r--r--   0 jenkins    (115) docker     (999)     1835 2023-05-03 14:26:41.000000 swh.loader.bzr-1.3.5/tox.ini
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:58:01.426675 swh.loader.bzr-1.3.6/
+-rw-r--r--   0 jenkins    (115) docker     (999)       83 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/.git-blame-ignore-revs
+-rw-r--r--   0 jenkins    (115) docker     (999)      122 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/.gitignore
+-rw-r--r--   0 jenkins    (115) docker     (999)      848 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/.pre-commit-config.yaml
+-rw-r--r--   0 jenkins    (115) docker     (999)      112 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/AUTHORS
+-rw-r--r--   0 jenkins    (115) docker     (999)     3397 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/CODE_OF_CONDUCT.md
+-rw-r--r--   0 jenkins    (115) docker     (999)       26 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/CONTRIBUTORS
+-rw-r--r--   0 jenkins    (115) docker     (999)    35147 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/LICENSE
+-rw-r--r--   0 jenkins    (115) docker     (999)      179 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/MANIFEST.in
+-rw-r--r--   0 jenkins    (115) docker     (999)      163 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/Makefile
+-rw-r--r--   0 jenkins    (115) docker     (999)     1215 2023-06-28 09:58:01.426675 swh.loader.bzr-1.3.6/PKG-INFO
+-rw-r--r--   0 jenkins    (115) docker     (999)      291 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/README.rst
+-rw-r--r--   0 jenkins    (115) docker     (999)      571 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/conftest.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:58:01.422675 swh.loader.bzr-1.3.6/docs/
+-rw-r--r--   0 jenkins    (115) docker     (999)       24 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/docs/.gitignore
+-rw-r--r--   0 jenkins    (115) docker     (999)       39 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/docs/Makefile
+-rw-r--r--   0 jenkins    (115) docker     (999)      291 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/docs/README.rst
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:58:01.422675 swh.loader.bzr-1.3.6/docs/_static/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/docs/_static/.placeholder
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:58:01.422675 swh.loader.bzr-1.3.6/docs/_templates/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/docs/_templates/.placeholder
+-rw-r--r--   0 jenkins    (115) docker     (999)       43 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/docs/conf.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     2044 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/docs/how-bzr-works.rst
+-rw-r--r--   0 jenkins    (115) docker     (999)      257 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/docs/index.rst
+-rw-r--r--   0 jenkins    (115) docker     (999)      361 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/mypy.ini
+-rw-r--r--   0 jenkins    (115) docker     (999)      237 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/pyproject.toml
+-rw-r--r--   0 jenkins    (115) docker     (999)       62 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/pytest.ini
+-rw-r--r--   0 jenkins    (115) docker     (999)       90 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/requirements-swh.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)       96 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/requirements-test.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      345 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/requirements.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      120 2023-06-28 09:58:01.426675 swh.loader.bzr-1.3.6/setup.cfg
+-rwxr-xr-x   0 jenkins    (115) docker     (999)     2704 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/setup.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:58:01.422675 swh.loader.bzr-1.3.6/swh/
+-rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/__init__.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:58:01.422675 swh.loader.bzr-1.3.6/swh/loader/
+-rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/__init__.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:58:01.422675 swh.loader.bzr-1.3.6/swh/loader/bzr/
+-rw-r--r--   0 jenkins    (115) docker     (999)      470 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/__init__.py
+-rw-r--r--   0 jenkins    (115) docker     (999)    26867 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/loader.py
+-rw-r--r--   0 jenkins    (115) docker     (999)       27 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/py.typed
+-rw-r--r--   0 jenkins    (115) docker     (999)      768 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tasks.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:58:01.422675 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/__init__.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1140 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/conftest.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:58:01.426675 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/
+-rw-r--r--   0 jenkins    (115) docker     (999)      191 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/broken-tags.sh
+-rw-r--r--   0 jenkins    (115) docker     (999)      980 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/broken-tags.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)      275 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/does-not-support-tags.sh
+-rw-r--r--   0 jenkins    (115) docker     (999)     1049 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/does-not-support-tags.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)      106 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/empty.sh
+-rw-r--r--   0 jenkins    (115) docker     (999)      962 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/empty.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)      400 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/ghosts.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     2451 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/ghosts.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)      636 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/metadata-and-type-changes.sh
+-rw-r--r--   0 jenkins    (115) docker     (999)    13831 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/metadata-and-type-changes.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)      139 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/needs-upgrade.sh
+-rw-r--r--   0 jenkins    (115) docker     (999)      880 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/needs-upgrade.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)      213 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/no-branch.sh
+-rw-r--r--   0 jenkins    (115) docker     (999)      882 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/no-branch.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)      829 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/nominal.sh
+-rw-r--r--   0 jenkins    (115) docker     (999)    11366 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/nominal.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)      360 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/renames.sh
+-rw-r--r--   0 jenkins    (115) docker     (999)     5068 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/renames.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)       27 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/py.typed
+-rw-r--r--   0 jenkins    (115) docker     (999)    15635 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/test_loader.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1477 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/swh/loader/bzr/tests/test_tasks.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 09:58:01.422675 swh.loader.bzr-1.3.6/swh.loader.bzr.egg-info/
+-rw-r--r--   0 jenkins    (115) docker     (999)     1215 2023-06-28 09:58:01.000000 swh.loader.bzr-1.3.6/swh.loader.bzr.egg-info/PKG-INFO
+-rw-r--r--   0 jenkins    (115) docker     (999)     1716 2023-06-28 09:58:01.000000 swh.loader.bzr-1.3.6/swh.loader.bzr.egg-info/SOURCES.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)        1 2023-06-28 09:58:01.000000 swh.loader.bzr-1.3.6/swh.loader.bzr.egg-info/dependency_links.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      118 2023-06-28 09:58:01.000000 swh.loader.bzr-1.3.6/swh.loader.bzr.egg-info/entry_points.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      200 2023-06-28 09:58:01.000000 swh.loader.bzr-1.3.6/swh.loader.bzr.egg-info/requires.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)        4 2023-06-28 09:58:01.000000 swh.loader.bzr-1.3.6/swh.loader.bzr.egg-info/top_level.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)     1835 2023-06-28 09:57:55.000000 swh.loader.bzr-1.3.6/tox.ini
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `swh.loader.bzr-1.3.5/.pre-commit-config.yaml` & `swh.loader.bzr-1.3.6/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/CODE_OF_CONDUCT.md` & `swh.loader.bzr-1.3.6/CODE_OF_CONDUCT.md`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/LICENSE` & `swh.loader.bzr-1.3.6/LICENSE`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/PKG-INFO` & `swh.loader.bzr-1.3.6/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: swh.loader.bzr
-Version: 1.3.5
+Version: 1.3.6
 Summary: Software Heritage Bazaar/Breezy intent
 Home-page: https://forge.softwareheritage.org/diffusion/DLDBZR/
 Author: Software Heritage developers
 Author-email: swh-devel@inria.fr
 Project-URL: Bug Reports, https://forge.softwareheritage.org/maniphest
 Project-URL: Funding, https://www.softwareheritage.org/donate
 Project-URL: Source, https://forge.softwareheritage.org/source/swh-loader-bzr
```

### Comparing `swh.loader.bzr-1.3.5/conftest.py` & `swh.loader.bzr-1.3.6/conftest.py`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/docs/how-bzr-works.rst` & `swh.loader.bzr-1.3.6/docs/how-bzr-works.rst`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/setup.py` & `swh.loader.bzr-1.3.6/setup.py`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/loader.py` & `swh.loader.bzr-1.3.6/swh/loader/bzr/loader.py`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/tasks.py` & `swh.loader.bzr-1.3.6/swh/loader/bzr/tasks.py`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/tests/conftest.py` & `swh.loader.bzr-1.3.6/swh/loader/bzr/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/broken-tags.tgz` & `swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/broken-tags.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/does-not-support-tags.tgz` & `swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/does-not-support-tags.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/empty.tgz` & `swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/empty.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/ghosts.tgz` & `swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/ghosts.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/metadata-and-type-changes.sh` & `swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/metadata-and-type-changes.sh`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/metadata-and-type-changes.tgz` & `swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/metadata-and-type-changes.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/needs-upgrade.tgz` & `swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/needs-upgrade.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/no-branch.tgz` & `swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/no-branch.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/nominal.sh` & `swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/nominal.sh`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/nominal.tgz` & `swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/nominal.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/tests/data/renames.tgz` & `swh.loader.bzr-1.3.6/swh/loader/bzr/tests/data/renames.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh/loader/bzr/tests/test_loader.py` & `swh.loader.bzr-1.3.6/swh/loader/bzr/tests/test_loader.py`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/swh.loader.bzr.egg-info/PKG-INFO` & `swh.loader.bzr-1.3.6/swh.loader.bzr.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: swh.loader.bzr
-Version: 1.3.5
+Version: 1.3.6
 Summary: Software Heritage Bazaar/Breezy intent
 Home-page: https://forge.softwareheritage.org/diffusion/DLDBZR/
 Author: Software Heritage developers
 Author-email: swh-devel@inria.fr
 Project-URL: Bug Reports, https://forge.softwareheritage.org/maniphest
 Project-URL: Funding, https://www.softwareheritage.org/donate
 Project-URL: Source, https://forge.softwareheritage.org/source/swh-loader-bzr
```

### Comparing `swh.loader.bzr-1.3.5/swh.loader.bzr.egg-info/SOURCES.txt` & `swh.loader.bzr-1.3.6/swh.loader.bzr.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `swh.loader.bzr-1.3.5/tox.ini` & `swh.loader.bzr-1.3.6/tox.ini`

 * *Files identical despite different names*


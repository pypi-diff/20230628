# Comparing `tmp/swh.loader.git-2.5.0.tar.gz` & `tmp/swh.loader.git-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/swh.loader.git-2.5.0.tar", last modified: Fri Jun  9 15:25:27 2023, max compression
+gzip compressed data, was "swh.loader.git-2.5.1.tar", last modified: Wed Jun 28 08:50:28 2023, max compression
```

## Comparing `swh.loader.git-2.5.0.tar` & `swh.loader.git-2.5.1.tar`

### file list

```diff
@@ -1,79 +1,79 @@
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/
--rw-r--r--   0 jenkins    (115) docker     (999)      140 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/.git-blame-ignore-revs
--rw-r--r--   0 jenkins    (115) docker     (999)      290 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/.gitignore
--rw-r--r--   0 jenkins    (115) docker     (999)      848 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/.pre-commit-config.yaml
--rw-r--r--   0 jenkins    (115) docker     (999)      112 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/AUTHORS
--rw-r--r--   0 jenkins    (115) docker     (999)     3397 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/CODE_OF_CONDUCT.md
--rw-r--r--   0 jenkins    (115) docker     (999)       15 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/CONTRIBUTORS
--rw-r--r--   0 jenkins    (115) docker     (999)    35147 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/LICENSE
--rw-r--r--   0 jenkins    (115) docker     (999)      237 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/MANIFEST.in
--rw-r--r--   0 jenkins    (115) docker     (999)      163 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/Makefile
--rw-r--r--   0 jenkins    (115) docker     (999)     2953 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/PKG-INFO
--rw-r--r--   0 jenkins    (115) docker     (999)     2026 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/README.md
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/bin/
--rwxr-xr-x   0 jenkins    (115) docker     (999)      605 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/bin/dir-git-repo-meta.sh
--rw-r--r--   0 jenkins    (115) docker     (999)      567 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/conftest.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/docs/
--rw-r--r--   0 jenkins    (115) docker     (999)       24 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/docs/.gitignore
--rw-r--r--   0 jenkins    (115) docker     (999)       39 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/docs/Makefile
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/docs/_static/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/docs/_static/.placeholder
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/docs/_templates/
--rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/docs/_templates/.placeholder
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/docs/attic/
--rw-r--r--   0 jenkins    (115) docker     (999)     6851 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/docs/attic/api-backend-protocol.txt
--rw-r--r--   0 jenkins    (115) docker     (999)     5476 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/docs/attic/git-loading-design.txt
--rw-r--r--   0 jenkins    (115) docker     (999)       43 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/docs/conf.py
--rw-r--r--   0 jenkins    (115) docker     (999)      360 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/docs/index.rst
--rw-r--r--   0 jenkins    (115) docker     (999)      399 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/mypy.ini
--rw-r--r--   0 jenkins    (115) docker     (999)      237 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/pyproject.toml
--rw-r--r--   0 jenkins    (115) docker     (999)      241 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/pytest.ini
--rw-r--r--   0 jenkins    (115) docker     (999)      109 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/requirements-swh.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      115 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/requirements-test.txt
--rw-r--r--   0 jenkins    (115) docker     (999)       33 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/requirements.txt
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/resources/
--rw-r--r--   0 jenkins    (115) docker     (999)      307 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/resources/local-loader-git.ini
--rw-r--r--   0 jenkins    (115) docker     (999)      307 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/resources/remote-loader-git.ini
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/resources/test/
--rw-r--r--   0 jenkins    (115) docker     (999)      502 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/resources/test/back.ini
--rw-r--r--   0 jenkins    (115) docker     (999)      125 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/resources/test/db-manager.ini
--rw-r--r--   0 jenkins    (115) docker     (999)      307 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/resources/updater.ini
--rw-r--r--   0 jenkins    (115) docker     (999)      120 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/setup.cfg
--rwxr-xr-x   0 jenkins    (115) docker     (999)     2448 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/setup.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/swh/
--rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/__init__.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/swh/loader/
--rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/__init__.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/swh/loader/git/
--rw-r--r--   0 jenkins    (115) docker     (999)      842 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/__init__.py
--rw-r--r--   0 jenkins    (115) docker     (999)     4603 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/base.py
--rw-r--r--   0 jenkins    (115) docker     (999)     9923 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/converters.py
--rw-r--r--   0 jenkins    (115) docker     (999)     2730 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/directory.py
--rw-r--r--   0 jenkins    (115) docker     (999)     8043 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/dumb.py
--rw-r--r--   0 jenkins    (115) docker     (999)    15273 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/from_disk.py
--rw-r--r--   0 jenkins    (115) docker     (999)    27520 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/loader.py
--rw-r--r--   0 jenkins    (115) docker     (999)       27 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/py.typed
--rw-r--r--   0 jenkins    (115) docker     (999)     1900 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/tasks.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/swh/loader/git/tests/
--rw-r--r--   0 jenkins    (115) docker     (999)      251 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/tests/__init__.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1331 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/tests/conftest.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/swh/loader/git/tests/data/
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/swh/loader/git/tests/data/git-repos/
--rw-r--r--   0 jenkins    (115) docker     (999)     5433 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/tests/data/git-repos/example-submodule.bundle
--rw-r--r--   0 jenkins    (115) docker     (999)    10630 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/tests/data/testrepo.tgz
--rw-r--r--   0 jenkins    (115) docker     (999)    33966 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/tests/test_converters.py
--rw-r--r--   0 jenkins    (115) docker     (999)     5871 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/tests/test_directory.py
--rw-r--r--   0 jenkins    (115) docker     (999)    20607 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/tests/test_from_disk.py
--rw-r--r--   0 jenkins    (115) docker     (999)    39895 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/tests/test_loader.py
--rw-r--r--   0 jenkins    (115) docker     (999)     2602 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/tests/test_tasks.py
--rw-r--r--   0 jenkins    (115) docker     (999)     1259 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/tests/test_tasks_directory.py
--rw-r--r--   0 jenkins    (115) docker     (999)     2799 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/tests/test_utils.py
--rw-r--r--   0 jenkins    (115) docker     (999)     5449 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/swh/loader/git/utils.py
-drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/swh.loader.git.egg-info/
--rw-r--r--   0 jenkins    (115) docker     (999)     2953 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/swh.loader.git.egg-info/PKG-INFO
--rw-r--r--   0 jenkins    (115) docker     (999)     1576 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/swh.loader.git.egg-info/SOURCES.txt
--rw-r--r--   0 jenkins    (115) docker     (999)        1 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/swh.loader.git.egg-info/dependency_links.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      158 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/swh.loader.git.egg-info/entry_points.txt
--rw-r--r--   0 jenkins    (115) docker     (999)      254 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/swh.loader.git.egg-info/requires.txt
--rw-r--r--   0 jenkins    (115) docker     (999)        4 2023-06-09 15:25:27.000000 swh.loader.git-2.5.0/swh.loader.git.egg-info/top_level.txt
--rw-r--r--   0 jenkins    (115) docker     (999)     1727 2023-06-09 15:25:26.000000 swh.loader.git-2.5.0/tox.ini
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.299480 swh.loader.git-2.5.1/
+-rw-r--r--   0 jenkins    (115) docker     (999)      140 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/.git-blame-ignore-revs
+-rw-r--r--   0 jenkins    (115) docker     (999)      290 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/.gitignore
+-rw-r--r--   0 jenkins    (115) docker     (999)      848 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/.pre-commit-config.yaml
+-rw-r--r--   0 jenkins    (115) docker     (999)      112 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/AUTHORS
+-rw-r--r--   0 jenkins    (115) docker     (999)     3397 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/CODE_OF_CONDUCT.md
+-rw-r--r--   0 jenkins    (115) docker     (999)       15 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/CONTRIBUTORS
+-rw-r--r--   0 jenkins    (115) docker     (999)    35147 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/LICENSE
+-rw-r--r--   0 jenkins    (115) docker     (999)      237 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/MANIFEST.in
+-rw-r--r--   0 jenkins    (115) docker     (999)      163 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/Makefile
+-rw-r--r--   0 jenkins    (115) docker     (999)     2953 2023-06-28 08:50:28.299480 swh.loader.git-2.5.1/PKG-INFO
+-rw-r--r--   0 jenkins    (115) docker     (999)     2026 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/README.md
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.295480 swh.loader.git-2.5.1/bin/
+-rwxr-xr-x   0 jenkins    (115) docker     (999)      605 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/bin/dir-git-repo-meta.sh
+-rw-r--r--   0 jenkins    (115) docker     (999)      567 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/conftest.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.295480 swh.loader.git-2.5.1/docs/
+-rw-r--r--   0 jenkins    (115) docker     (999)       24 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/docs/.gitignore
+-rw-r--r--   0 jenkins    (115) docker     (999)       39 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/docs/Makefile
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.295480 swh.loader.git-2.5.1/docs/_static/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/docs/_static/.placeholder
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.295480 swh.loader.git-2.5.1/docs/_templates/
+-rw-r--r--   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/docs/_templates/.placeholder
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.295480 swh.loader.git-2.5.1/docs/attic/
+-rw-r--r--   0 jenkins    (115) docker     (999)     6851 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/docs/attic/api-backend-protocol.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)     5476 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/docs/attic/git-loading-design.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)       43 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/docs/conf.py
+-rw-r--r--   0 jenkins    (115) docker     (999)      360 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/docs/index.rst
+-rw-r--r--   0 jenkins    (115) docker     (999)      399 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/mypy.ini
+-rw-r--r--   0 jenkins    (115) docker     (999)      237 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/pyproject.toml
+-rw-r--r--   0 jenkins    (115) docker     (999)      241 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/pytest.ini
+-rw-r--r--   0 jenkins    (115) docker     (999)      109 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/requirements-swh.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      115 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/requirements-test.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)       33 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/requirements.txt
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.295480 swh.loader.git-2.5.1/resources/
+-rw-r--r--   0 jenkins    (115) docker     (999)      307 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/resources/local-loader-git.ini
+-rw-r--r--   0 jenkins    (115) docker     (999)      307 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/resources/remote-loader-git.ini
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.295480 swh.loader.git-2.5.1/resources/test/
+-rw-r--r--   0 jenkins    (115) docker     (999)      502 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/resources/test/back.ini
+-rw-r--r--   0 jenkins    (115) docker     (999)      125 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/resources/test/db-manager.ini
+-rw-r--r--   0 jenkins    (115) docker     (999)      307 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/resources/updater.ini
+-rw-r--r--   0 jenkins    (115) docker     (999)      120 2023-06-28 08:50:28.299480 swh.loader.git-2.5.1/setup.cfg
+-rwxr-xr-x   0 jenkins    (115) docker     (999)     2448 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/setup.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.295480 swh.loader.git-2.5.1/swh/
+-rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/__init__.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.295480 swh.loader.git-2.5.1/swh/loader/
+-rw-r--r--   0 jenkins    (115) docker     (999)       76 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/__init__.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.299480 swh.loader.git-2.5.1/swh/loader/git/
+-rw-r--r--   0 jenkins    (115) docker     (999)      842 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/__init__.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     4603 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/base.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     9923 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/converters.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     2730 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/directory.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     8150 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/dumb.py
+-rw-r--r--   0 jenkins    (115) docker     (999)    15174 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/from_disk.py
+-rw-r--r--   0 jenkins    (115) docker     (999)    27520 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/loader.py
+-rw-r--r--   0 jenkins    (115) docker     (999)       27 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/py.typed
+-rw-r--r--   0 jenkins    (115) docker     (999)     1900 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/tasks.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.299480 swh.loader.git-2.5.1/swh/loader/git/tests/
+-rw-r--r--   0 jenkins    (115) docker     (999)      251 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/tests/__init__.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1331 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/tests/conftest.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.299480 swh.loader.git-2.5.1/swh/loader/git/tests/data/
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.299480 swh.loader.git-2.5.1/swh/loader/git/tests/data/git-repos/
+-rw-r--r--   0 jenkins    (115) docker     (999)     5433 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/tests/data/git-repos/example-submodule.bundle
+-rw-r--r--   0 jenkins    (115) docker     (999)    10630 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/tests/data/testrepo.tgz
+-rw-r--r--   0 jenkins    (115) docker     (999)    33966 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/tests/test_converters.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     5871 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/tests/test_directory.py
+-rw-r--r--   0 jenkins    (115) docker     (999)    20607 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/tests/test_from_disk.py
+-rw-r--r--   0 jenkins    (115) docker     (999)    40371 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/tests/test_loader.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     2602 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/tests/test_tasks.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     1259 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/tests/test_tasks_directory.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     2799 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/tests/test_utils.py
+-rw-r--r--   0 jenkins    (115) docker     (999)     5449 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/swh/loader/git/utils.py
+drwxr-xr-x   0 jenkins    (115) docker     (999)        0 2023-06-28 08:50:28.295480 swh.loader.git-2.5.1/swh.loader.git.egg-info/
+-rw-r--r--   0 jenkins    (115) docker     (999)     2953 2023-06-28 08:50:28.000000 swh.loader.git-2.5.1/swh.loader.git.egg-info/PKG-INFO
+-rw-r--r--   0 jenkins    (115) docker     (999)     1576 2023-06-28 08:50:28.000000 swh.loader.git-2.5.1/swh.loader.git.egg-info/SOURCES.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)        1 2023-06-28 08:50:28.000000 swh.loader.git-2.5.1/swh.loader.git.egg-info/dependency_links.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      158 2023-06-28 08:50:28.000000 swh.loader.git-2.5.1/swh.loader.git.egg-info/entry_points.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)      254 2023-06-28 08:50:28.000000 swh.loader.git-2.5.1/swh.loader.git.egg-info/requires.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)        4 2023-06-28 08:50:28.000000 swh.loader.git-2.5.1/swh.loader.git.egg-info/top_level.txt
+-rw-r--r--   0 jenkins    (115) docker     (999)     1727 2023-06-28 08:50:22.000000 swh.loader.git-2.5.1/tox.ini
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `swh.loader.git-2.5.0/.pre-commit-config.yaml` & `swh.loader.git-2.5.1/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/CODE_OF_CONDUCT.md` & `swh.loader.git-2.5.1/CODE_OF_CONDUCT.md`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/LICENSE` & `swh.loader.git-2.5.1/LICENSE`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/PKG-INFO` & `swh.loader.git-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: swh.loader.git
-Version: 2.5.0
+Version: 2.5.1
 Summary: Software Heritage git loader
 Home-page: https://forge.softwareheritage.org/diffusion/DLDG/
 Author: Software Heritage developers
 Author-email: swh-devel@inria.fr
 Project-URL: Bug Reports, https://forge.softwareheritage.org/maniphest
 Project-URL: Funding, https://www.softwareheritage.org/donate
 Project-URL: Source, https://forge.softwareheritage.org/source/swh-loader-git
```

### Comparing `swh.loader.git-2.5.0/README.md` & `swh.loader.git-2.5.1/README.md`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/bin/dir-git-repo-meta.sh` & `swh.loader.git-2.5.1/bin/dir-git-repo-meta.sh`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/conftest.py` & `swh.loader.git-2.5.1/conftest.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/docs/attic/api-backend-protocol.txt` & `swh.loader.git-2.5.1/docs/attic/api-backend-protocol.txt`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/docs/attic/git-loading-design.txt` & `swh.loader.git-2.5.1/docs/attic/git-loading-design.txt`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/setup.py` & `swh.loader.git-2.5.1/setup.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/__init__.py` & `swh.loader.git-2.5.1/swh/loader/git/__init__.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/base.py` & `swh.loader.git-2.5.1/swh/loader/git/base.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/converters.py` & `swh.loader.git-2.5.1/swh/loader/git/converters.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/directory.py` & `swh.loader.git-2.5.1/swh/loader/git/directory.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/dumb.py` & `swh.loader.git-2.5.1/swh/loader/git/dumb.py`

 * *Files 5% similar despite different names*

```diff
@@ -27,14 +27,17 @@
 
 logger = logging.getLogger(__name__)
 
 
 HEADERS = {"User-Agent": "Software Heritage dumb Git loader"}
 
 
+@http_retry(
+    before_sleep=before_sleep_log(logger, logging.WARNING),
+)
 def check_protocol(repo_url: str) -> bool:
     """Checks if a git repository can be cloned using the dumb protocol.
 
     Args:
         repo_url: Base URL of a git repository
 
     Returns:
@@ -44,14 +47,15 @@
     if not repo_url.startswith("http"):
         return False
     url = urllib.parse.urljoin(
         repo_url.rstrip("/") + "/", "info/refs?service=git-upload-pack/"
     )
     logger.debug("Fetching %s", url)
     response = requests.get(url, headers=HEADERS)
+    response.raise_for_status()
     content_type = response.headers.get("Content-Type")
     return (
         response.status_code
         in (
             200,
             304,
         )
```

### Comparing `swh.loader.git-2.5.0/swh/loader/git/from_disk.py` & `swh.loader.git-2.5.1/swh/loader/git/from_disk.py`

 * *Files 2% similar despite different names*

```diff
@@ -5,24 +5,18 @@
 from collections import defaultdict
 from datetime import datetime
 import logging
 import os
 import shutil
 from typing import Dict, Optional
 
-from dulwich.errors import ObjectFormatException
-
-try:
-    from dulwich.errors import EmptyFileException  # type: ignore
-except ImportError:
-    # dulwich >= 0.20
-    from dulwich.objects import EmptyFileException
-
 from deprecated import deprecated
+from dulwich.errors import ObjectFormatException
 import dulwich.objects
+from dulwich.objects import EmptyFileException
 import dulwich.repo
 
 from swh.loader.git.utils import raise_not_found_repository
 from swh.model import hashutil
 from swh.model.model import Snapshot, SnapshotBranch, TargetType
 from swh.storage.algos.origin import origin_get_latest_visit_status
 from swh.storage.interface import StorageInterface
@@ -98,15 +92,16 @@
         storage: StorageInterface,
         url: str,
         visit_date: Optional[datetime] = None,
         directory: Optional[str] = None,
         **kwargs,
     ):
         super().__init__(storage=storage, origin_url=url, **kwargs)
-        self.visit_date = visit_date or self.visit_date
+        if visit_date is not None:
+            self.visit_date = visit_date
         self.directory = directory
 
     def prepare(self):
         with raise_not_found_repository():
             self.repo = dulwich.repo.Repo(self.directory)
 
     def iter_objects(self):
```

### Comparing `swh.loader.git-2.5.0/swh/loader/git/loader.py` & `swh.loader.git-2.5.1/swh/loader/git/loader.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/tasks.py` & `swh.loader.git-2.5.1/swh/loader/git/tasks.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/tests/conftest.py` & `swh.loader.git-2.5.1/swh/loader/git/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/tests/data/git-repos/example-submodule.bundle` & `swh.loader.git-2.5.1/swh/loader/git/tests/data/git-repos/example-submodule.bundle`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/tests/data/testrepo.tgz` & `swh.loader.git-2.5.1/swh/loader/git/tests/data/testrepo.tgz`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/tests/test_converters.py` & `swh.loader.git-2.5.1/swh/loader/git/tests/test_converters.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/tests/test_directory.py` & `swh.loader.git-2.5.1/swh/loader/git/tests/test_directory.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/tests/test_from_disk.py` & `swh.loader.git-2.5.1/swh/loader/git/tests/test_from_disk.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/tests/test_loader.py` & `swh.loader.git-2.5.1/swh/loader/git/tests/test_loader.py`

 * *Files 1% similar despite different names*

```diff
@@ -18,15 +18,14 @@
 import attr
 from dulwich.errors import GitProtocolError, NotGitRepository, ObjectFormatException
 from dulwich.pack import REF_DELTA
 from dulwich.porcelain import push
 import dulwich.repo
 from dulwich.tests.utils import build_pack
 import pytest
-import requests_mock
 
 from swh.loader.git import converters, dumb
 from swh.loader.git.loader import FetchPackReturn, GitLoader
 from swh.loader.git.tests.test_from_disk import SNAPSHOT1, FullGitLoaderTests
 from swh.loader.tests import (
     assert_last_visit_matches,
     get_stats,
@@ -960,37 +959,53 @@
 
         mocker.patch.object(dumb, "GitObjectsFetcher", GitObjectsFetcherMissingPack)
 
         res = self.loader.load()
 
         assert res == {"status": "eventful"}
 
-    def test_http_get_retry(self, mocker):
+    def test_http_get_retry(self, mocker, requests_mock):
+        requests_mock.real_http = True
         sleep = mocker.patch.object(dumb.GitObjectsFetcher._http_get.retry, "sleep")
-        with requests_mock.Mocker(real_http=True) as http_mocker:
-            # mock requests for getting packs data
-            for root, _, files in os.walk(
-                os.path.join(self.bare_repo_path, "objects/pack")
-            ):
-                nb_files = len(files)
-                for pack in files:
-                    with open(os.path.join(root, pack), "rb") as pack_data:
-                        http_mocker.get(
-                            f"{self.repo_url}/objects/pack/{pack}",
-                            [
-                                # first request fails
-                                {"status_code": 502},
-                                # next one succeeds
-                                {"status_code": 200, "content": pack_data.read()},
-                            ],
-                        )
-
-            res = self.loader.load()
-            assert res == {"status": "eventful"}
-            sleep.assert_has_calls([mocker.call(param) for param in [1] * nb_files])
+
+        # mock requests for getting packs data
+        for root, _, files in os.walk(
+            os.path.join(self.bare_repo_path, "objects/pack")
+        ):
+            nb_files = len(files)
+            for pack in files:
+                with open(os.path.join(root, pack), "rb") as pack_data:
+                    requests_mock.get(
+                        f"{self.repo_url}/objects/pack/{pack}",
+                        [
+                            # first request fails
+                            {"status_code": 502},
+                            # next one succeeds
+                            {"status_code": 200, "content": pack_data.read()},
+                        ],
+                    )
+
+        res = self.loader.load()
+        assert res == {"status": "eventful"}
+        sleep.assert_has_calls([mocker.call(param) for param in [1] * nb_files])
+
+        sleep = mocker.patch.object(dumb.check_protocol.retry, "sleep")
+        with open(os.path.join(self.bare_repo_path, "info/refs"), "rb") as refs_data:
+            requests_mock.get(
+                f"{self.repo_url}/info/refs",
+                [
+                    # first request fails
+                    {"status_code": 502},
+                    # next one succeeds
+                    {"status_code": 200, "content": refs_data.read()},
+                ],
+            )
+
+        assert dumb.check_protocol(self.repo_url)
+        sleep.assert_has_calls([mocker.call(1)])
 
 
 class TestDumbGitLoaderWithoutPack(DumbGitLoaderTestBase):
     @classmethod
     def setup_class(cls):
         cls.with_pack_files = False
```

### Comparing `swh.loader.git-2.5.0/swh/loader/git/tests/test_tasks.py` & `swh.loader.git-2.5.1/swh/loader/git/tests/test_tasks.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/tests/test_tasks_directory.py` & `swh.loader.git-2.5.1/swh/loader/git/tests/test_tasks_directory.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/tests/test_utils.py` & `swh.loader.git-2.5.1/swh/loader/git/tests/test_utils.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh/loader/git/utils.py` & `swh.loader.git-2.5.1/swh/loader/git/utils.py`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/swh.loader.git.egg-info/PKG-INFO` & `swh.loader.git-2.5.1/swh.loader.git.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: swh.loader.git
-Version: 2.5.0
+Version: 2.5.1
 Summary: Software Heritage git loader
 Home-page: https://forge.softwareheritage.org/diffusion/DLDG/
 Author: Software Heritage developers
 Author-email: swh-devel@inria.fr
 Project-URL: Bug Reports, https://forge.softwareheritage.org/maniphest
 Project-URL: Funding, https://www.softwareheritage.org/donate
 Project-URL: Source, https://forge.softwareheritage.org/source/swh-loader-git
```

### Comparing `swh.loader.git-2.5.0/swh.loader.git.egg-info/SOURCES.txt` & `swh.loader.git-2.5.1/swh.loader.git.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `swh.loader.git-2.5.0/tox.ini` & `swh.loader.git-2.5.1/tox.ini`

 * *Files identical despite different names*


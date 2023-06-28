# Comparing `tmp/iqm-cortex-cli-4.2.tar.gz` & `tmp/iqm-cortex-cli-4.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "iqm-cortex-cli-4.2.tar", last modified: Wed May 10 08:50:49 2023, max compression
+gzip compressed data, was "iqm-cortex-cli-4.3.tar", last modified: Wed Jun 28 09:22:48 2023, max compression
```

## Comparing `iqm-cortex-cli-4.2.tar` & `iqm-cortex-cli-4.3.tar`

### file list

```diff
@@ -1,64 +1,64 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 08:50:49.432315 iqm-cortex-cli-4.2/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 08:50:49.424315 iqm-cortex-cli-4.2/.github/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 08:50:49.428315 iqm-cortex-cli-4.2/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)     1289 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/.github/workflows/ci.yml
--rw-r--r--   0 runner    (1001) docker     (123)     2494 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/.github/workflows/publish.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1339 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/.github/workflows/tag_and_release.yml
--rw-r--r--   0 runner    (1001) docker     (123)      273 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)      168 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/AUTHORS.rst
--rw-r--r--   0 runner    (1001) docker     (123)     6254 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/CHANGELOG.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1906 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/DEVELOPMENT.rst
--rw-r--r--   0 runner    (1001) docker     (123)    11356 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/LICENSE.rst
--rw-r--r--   0 runner    (1001) docker     (123)    18519 2023-05-10 08:50:49.432315 iqm-cortex-cli-4.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     4597 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/README.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 08:50:49.428315 iqm-cortex-cli-4.2/docs/
--rw-r--r--   0 runner    (1001) docker     (123)      644 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/docs/Makefile
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 08:50:49.424315 iqm-cortex-cli-4.2/docs/_static/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 08:50:49.428315 iqm-cortex-cli-4.2/docs/_static/images/
--rw-r--r--   0 runner    (1001) docker     (123)    15086 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/docs/_static/images/favicon.ico
--rw-r--r--   0 runner    (1001) docker     (123)   618471 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/docs/_static/images/logo.png
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 08:50:49.428315 iqm-cortex-cli-4.2/docs/_templates/
--rw-r--r--   0 runner    (1001) docker     (123)      663 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/docs/_templates/autosummary-class-template.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1390 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/docs/_templates/autosummary-module-template.rst
--rw-r--r--   0 runner    (1001) docker     (123)      828 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/docs/_templates/page.html
--rw-r--r--   0 runner    (1001) docker     (123)      869 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/docs/_templates/versioning.html
--rw-r--r--   0 runner    (1001) docker     (123)       41 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/docs/authors.rst
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/docs/changelog.rst
--rw-r--r--   0 runner    (1001) docker     (123)     5692 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/docs/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)      356 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/docs/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)       81 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/docs/license.rst
--rw-r--r--   0 runner    (1001) docker     (123)       39 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/docs/readme.rst
--rwxr-xr-x   0 runner    (1001) docker     (123)      199 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/lint.sh
--rw-r--r--   0 runner    (1001) docker     (123)     3603 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-10 08:50:49.432315 iqm-cortex-cli-4.2/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 08:50:49.424315 iqm-cortex-cli-4.2/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 08:50:49.428315 iqm-cortex-cli-4.2/src/cortex_cli/
--rw-r--r--   0 runner    (1001) docker     (123)      950 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/src/cortex_cli/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7079 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/src/cortex_cli/auth.py
--rw-r--r--   0 runner    (1001) docker     (123)    26447 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/src/cortex_cli/cortex_cli.py
--rw-r--r--   0 runner    (1001) docker     (123)     1212 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/src/cortex_cli/models.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/src/cortex_cli/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     6852 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/src/cortex_cli/token_manager.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 08:50:49.432315 iqm-cortex-cli-4.2/src/iqm_cortex_cli.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18519 2023-05-10 08:50:49.000000 iqm-cortex-cli-4.2/src/iqm_cortex_cli.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1279 2023-05-10 08:50:49.000000 iqm-cortex-cli-4.2/src/iqm_cortex_cli.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-10 08:50:49.000000 iqm-cortex-cli-4.2/src/iqm_cortex_cli.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       60 2023-05-10 08:50:49.000000 iqm-cortex-cli-4.2/src/iqm_cortex_cli.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)      426 2023-05-10 08:50:49.000000 iqm-cortex-cli-4.2/src/iqm_cortex_cli.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       11 2023-05-10 08:50:49.000000 iqm-cortex-cli-4.2/src/iqm_cortex_cli.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     1833 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/tag-from-pipeline.sh
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 08:50:49.432315 iqm-cortex-cli-4.2/tests/
--rw-r--r--   0 runner    (1001) docker     (123)      438 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/tests/.pylintrc
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4998 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/tests/auth_test.py
--rw-r--r--   0 runner    (1001) docker     (123)     6910 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/tests/conftest.py
--rw-r--r--   0 runner    (1001) docker     (123)    10622 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/tests/cortex_cli_auth_login_test.py
--rw-r--r--   0 runner    (1001) docker     (123)    13246 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/tests/cortex_cli_auth_logout_test.py
--rw-r--r--   0 runner    (1001) docker     (123)     6462 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/tests/cortex_cli_auth_status_test.py
--rw-r--r--   0 runner    (1001) docker     (123)     8978 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/tests/cortex_cli_init_test.py
--rw-r--r--   0 runner    (1001) docker     (123)     1266 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/tests/cortex_cli_test.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-10 08:50:49.432315 iqm-cortex-cli-4.2/tests/resources/
--rw-r--r--   0 runner    (1001) docker     (123)      142 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/tests/resources/config.json
--rw-r--r--   0 runner    (1001) docker     (123)     2238 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/tests/resources/tokens.json
--rw-r--r--   0 runner    (1001) docker     (123)     1763 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/tests/token_manager_test.py
--rw-r--r--   0 runner    (1001) docker     (123)     2008 2023-05-10 08:50:16.000000 iqm-cortex-cli-4.2/tox.ini
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:22:48.689371 iqm-cortex-cli-4.3/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:22:48.681371 iqm-cortex-cli-4.3/.github/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:22:48.685371 iqm-cortex-cli-4.3/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     1289 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/.github/workflows/ci.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     2494 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/.github/workflows/publish.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1339 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/.github/workflows/tag_and_release.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      273 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)      168 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/AUTHORS.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     6376 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/CHANGELOG.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1906 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/DEVELOPMENT.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    11356 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/LICENSE.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    18519 2023-06-28 09:22:48.689371 iqm-cortex-cli-4.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4597 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/README.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:22:48.685371 iqm-cortex-cli-4.3/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)      644 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/docs/Makefile
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:22:48.681371 iqm-cortex-cli-4.3/docs/_static/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:22:48.685371 iqm-cortex-cli-4.3/docs/_static/images/
+-rw-r--r--   0 runner    (1001) docker     (123)    15086 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/docs/_static/images/favicon.ico
+-rw-r--r--   0 runner    (1001) docker     (123)   618471 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/docs/_static/images/logo.png
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:22:48.685371 iqm-cortex-cli-4.3/docs/_templates/
+-rw-r--r--   0 runner    (1001) docker     (123)      663 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/docs/_templates/autosummary-class-template.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1390 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/docs/_templates/autosummary-module-template.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      828 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/docs/_templates/page.html
+-rw-r--r--   0 runner    (1001) docker     (123)      869 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/docs/_templates/versioning.html
+-rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/docs/authors.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/docs/changelog.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     5692 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/docs/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)      356 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/docs/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       81 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/docs/license.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/docs/readme.rst
+-rwxr-xr-x   0 runner    (1001) docker     (123)      199 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/lint.sh
+-rw-r--r--   0 runner    (1001) docker     (123)     3603 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 09:22:48.689371 iqm-cortex-cli-4.3/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:22:48.681371 iqm-cortex-cli-4.3/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:22:48.689371 iqm-cortex-cli-4.3/src/cortex_cli/
+-rw-r--r--   0 runner    (1001) docker     (123)      950 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/src/cortex_cli/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7079 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/src/cortex_cli/auth.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26433 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/src/cortex_cli/cortex_cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1212 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/src/cortex_cli/models.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/src/cortex_cli/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     7083 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/src/cortex_cli/token_manager.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:22:48.689371 iqm-cortex-cli-4.3/src/iqm_cortex_cli.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18519 2023-06-28 09:22:48.000000 iqm-cortex-cli-4.3/src/iqm_cortex_cli.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1279 2023-06-28 09:22:48.000000 iqm-cortex-cli-4.3/src/iqm_cortex_cli.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 09:22:48.000000 iqm-cortex-cli-4.3/src/iqm_cortex_cli.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       60 2023-06-28 09:22:48.000000 iqm-cortex-cli-4.3/src/iqm_cortex_cli.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      426 2023-06-28 09:22:48.000000 iqm-cortex-cli-4.3/src/iqm_cortex_cli.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       11 2023-06-28 09:22:48.000000 iqm-cortex-cli-4.3/src/iqm_cortex_cli.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     1833 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/tag-from-pipeline.sh
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:22:48.689371 iqm-cortex-cli-4.3/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      438 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/tests/.pylintrc
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4998 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/tests/auth_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6910 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/tests/conftest.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10622 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/tests/cortex_cli_auth_login_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13246 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/tests/cortex_cli_auth_logout_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6462 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/tests/cortex_cli_auth_status_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8978 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/tests/cortex_cli_init_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1266 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/tests/cortex_cli_test.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:22:48.689371 iqm-cortex-cli-4.3/tests/resources/
+-rw-r--r--   0 runner    (1001) docker     (123)      142 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/tests/resources/config.json
+-rw-r--r--   0 runner    (1001) docker     (123)     2238 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/tests/resources/tokens.json
+-rw-r--r--   0 runner    (1001) docker     (123)     4956 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/tests/token_manager_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2008 2023-06-28 09:22:14.000000 iqm-cortex-cli-4.3/tox.ini
```

### Comparing `iqm-cortex-cli-4.2/.github/workflows/ci.yml` & `iqm-cortex-cli-4.3/.github/workflows/ci.yml`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/.github/workflows/publish.yml` & `iqm-cortex-cli-4.3/.github/workflows/publish.yml`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/.github/workflows/tag_and_release.yml` & `iqm-cortex-cli-4.3/.github/workflows/tag_and_release.yml`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/CHANGELOG.rst` & `iqm-cortex-cli-4.3/CHANGELOG.rst`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,16 @@
 =========
 Changelog
 =========
 
+Version 4.3
+===========
+
+* Fix logging for multi-user systems `#48 <https://github.com/iqm-finland/cortex-cli/pull/48>`_
+
 Version 4.2
 ===========
 
 * Fix ``init`` command non-interactive mode failing for some orders of options `#44 <https://github.com/iqm-finland/cortex-cli/pull/44>`_
 
 Version 4.1
 ===========
```

### Comparing `iqm-cortex-cli-4.2/DEVELOPMENT.rst` & `iqm-cortex-cli-4.3/DEVELOPMENT.rst`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/LICENSE.rst` & `iqm-cortex-cli-4.3/LICENSE.rst`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/PKG-INFO` & `iqm-cortex-cli-4.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: iqm-cortex-cli
-Version: 4.2
+Version: 4.3
 Summary: CLI for managing user authentication when using IQM quantum computers
 Author-email: IQM Finland Oy <developers@meetiqm.com>
 License:                                  Apache License
                                    Version 2.0, January 2004
                                 http://www.apache.org/licenses/
         
            TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION
```

### Comparing `iqm-cortex-cli-4.2/README.rst` & `iqm-cortex-cli-4.3/README.rst`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/docs/Makefile` & `iqm-cortex-cli-4.3/docs/Makefile`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/docs/_static/images/favicon.ico` & `iqm-cortex-cli-4.3/docs/_static/images/favicon.ico`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/docs/_static/images/logo.png` & `iqm-cortex-cli-4.3/docs/_static/images/logo.png`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/docs/_templates/autosummary-class-template.rst` & `iqm-cortex-cli-4.3/docs/_templates/autosummary-class-template.rst`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/docs/_templates/autosummary-module-template.rst` & `iqm-cortex-cli-4.3/docs/_templates/autosummary-module-template.rst`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/docs/_templates/page.html` & `iqm-cortex-cli-4.3/docs/_templates/page.html`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/docs/_templates/versioning.html` & `iqm-cortex-cli-4.3/docs/_templates/versioning.html`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/docs/conf.py` & `iqm-cortex-cli-4.3/docs/conf.py`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/pyproject.toml` & `iqm-cortex-cli-4.3/pyproject.toml`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/src/cortex_cli/__init__.py` & `iqm-cortex-cli-4.3/src/cortex_cli/__init__.py`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/src/cortex_cli/auth.py` & `iqm-cortex-cli-4.3/src/cortex_cli/auth.py`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/src/cortex_cli/cortex_cli.py` & `iqm-cortex-cli-4.3/src/cortex_cli/cortex_cli.py`

 * *Files 1% similar despite different names*

```diff
@@ -302,17 +302,17 @@
     callback=_validate_path,
     default=CortexCliCommand.default_tokens_path,
     type=click.Path(dir_okay=False, writable=True),
     help='Location where the tokens file will be saved.',
 )
 @click.option(
     '--auth-server-url',
-    prompt='Base URL of IQM auth server',
+    prompt='Authentication server URL',
     callback=_validate_auth_server_url,
-    help='Base URL of IQM authentication server.',
+    help='Authentication server URL.',
 )
 @click.option(
     '--realm',
     prompt='Realm on IQM auth server',
     default=REALM_NAME,
     callback=_validate_auth_realm,
     help='Name of the realm on the IQM authentication server.',
```

### Comparing `iqm-cortex-cli-4.2/src/cortex_cli/models.py` & `iqm-cortex-cli-4.3/src/cortex_cli/models.py`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/src/cortex_cli/token_manager.py` & `iqm-cortex-cli-4.3/src/cortex_cli/token_manager.py`

 * *Files 3% similar despite different names*

```diff
@@ -28,21 +28,27 @@
 from cortex_cli.auth import AUTH_REQUESTS_TIMEOUT, ClientAuthenticationError, refresh_request
 from cortex_cli.models import ConfigFile
 
 if not platform.system().lower().startswith('win'):
     import daemon
 
 
-def daemonize_token_manager(cycle: int, config: ConfigFile, logfile: str = '/tmp/token_manager.log') -> None:
+def daemonize_token_manager(cycle: int, config: ConfigFile, logfile: Optional[str] = None) -> None:
     """Start a daemon process.
     Args:
         cycle: refresh cycle in seconds
         config: Cortex CLI configuration
         logfile: path to file for writing errors
     """
+    logfile = (
+        logfile
+        if logfile is not None
+        else f'{os.environ.get("XDG_STATE_HOME", f"{Path.home()}/.local/state")}/iqm-cortex-cli/token_manager.log'
+    )
+    os.makedirs(os.path.dirname(logfile), exist_ok=True)
     with open(logfile, 'w', encoding='UTF-8') as output:
         with daemon.DaemonContext(stdout=output, stderr=output):
             start_token_manager(cycle, config)
 
 
 def start_token_manager(cycle: int, config: ConfigFile, single_run: bool = False) -> None:
     """Refresh tokens periodically.
```

### Comparing `iqm-cortex-cli-4.2/src/iqm_cortex_cli.egg-info/PKG-INFO` & `iqm-cortex-cli-4.3/src/iqm_cortex_cli.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: iqm-cortex-cli
-Version: 4.2
+Version: 4.3
 Summary: CLI for managing user authentication when using IQM quantum computers
 Author-email: IQM Finland Oy <developers@meetiqm.com>
 License:                                  Apache License
                                    Version 2.0, January 2004
                                 http://www.apache.org/licenses/
         
            TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION
```

### Comparing `iqm-cortex-cli-4.2/src/iqm_cortex_cli.egg-info/SOURCES.txt` & `iqm-cortex-cli-4.3/src/iqm_cortex_cli.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/tag-from-pipeline.sh` & `iqm-cortex-cli-4.3/tag-from-pipeline.sh`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/tests/auth_test.py` & `iqm-cortex-cli-4.3/tests/auth_test.py`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/tests/conftest.py` & `iqm-cortex-cli-4.3/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/tests/cortex_cli_auth_login_test.py` & `iqm-cortex-cli-4.3/tests/cortex_cli_auth_login_test.py`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/tests/cortex_cli_auth_logout_test.py` & `iqm-cortex-cli-4.3/tests/cortex_cli_auth_logout_test.py`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/tests/cortex_cli_auth_status_test.py` & `iqm-cortex-cli-4.3/tests/cortex_cli_auth_status_test.py`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/tests/cortex_cli_init_test.py` & `iqm-cortex-cli-4.3/tests/cortex_cli_init_test.py`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/tests/cortex_cli_test.py` & `iqm-cortex-cli-4.3/tests/cortex_cli_test.py`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/tests/resources/tokens.json` & `iqm-cortex-cli-4.3/tests/resources/tokens.json`

 * *Files identical despite different names*

### Comparing `iqm-cortex-cli-4.2/tox.ini` & `iqm-cortex-cli-4.3/tox.ini`

 * *Files identical despite different names*


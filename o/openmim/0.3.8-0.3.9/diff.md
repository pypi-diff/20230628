# Comparing `tmp/openmim-0.3.8.tar.gz` & `tmp/openmim-0.3.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "openmim-0.3.8.tar", last modified: Wed Jun 28 07:41:28 2023, max compression
+gzip compressed data, was "openmim-0.3.9.tar", last modified: Wed Jun 28 07:45:11 2023, max compression
```

## Comparing `openmim-0.3.8.tar` & `openmim-0.3.9.tar`

### file list

```diff
@@ -1,58 +1,58 @@
-drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.343375 openmim-0.3.8/
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    11408 2023-06-28 07:39:52.000000 openmim-0.3.8/LICENSE
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)       27 2023-06-28 07:39:52.000000 openmim-0.3.8/MANIFEST.in
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    15568 2023-06-28 07:41:28.343375 openmim-0.3.8/PKG-INFO
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    15249 2023-06-28 07:39:52.000000 openmim-0.3.8/README.md
-drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.338375 openmim-0.3.8/mim/
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      844 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/__init__.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      159 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/__main__.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2968 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/cli.py
-drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.339375 openmim-0.3.8/mim/click/
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      460 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/click/__init__.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      790 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/click/autocompletion.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1637 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/click/compat.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     4868 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/click/customcommand.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2249 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/click/option.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      190 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/click/utils.py
-drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.340375 openmim-0.3.8/mim/commands/
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      453 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/__init__.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     5118 2023-06-28 07:40:52.000000 openmim-0.3.8/mim/commands/download.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    16187 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/gridsearch.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    14727 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/install.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2855 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/list.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     5711 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/run.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    27632 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/search.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    10686 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/test.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     9928 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/train.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2404 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/commands/uninstall.py
-drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.340375 openmim-0.3.8/mim/utils/
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1967 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/utils/__init__.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1297 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/utils/default.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1071 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/utils/progress_bars.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    16351 2023-06-28 07:39:52.000000 openmim-0.3.8/mim/utils/utils.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      500 2023-06-28 07:40:52.000000 openmim-0.3.8/mim/version.py
-drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.341375 openmim-0.3.8/openmim.egg-info/
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    15568 2023-06-28 07:41:28.000000 openmim-0.3.8/openmim.egg-info/PKG-INFO
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1056 2023-06-28 07:41:28.000000 openmim-0.3.8/openmim.egg-info/SOURCES.txt
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)        1 2023-06-28 07:41:28.000000 openmim-0.3.8/openmim.egg-info/dependency_links.txt
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)       36 2023-06-28 07:41:28.000000 openmim-0.3.8/openmim.egg-info/entry_points.txt
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      325 2023-06-28 07:41:28.000000 openmim-0.3.8/openmim.egg-info/requires.txt
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)        4 2023-06-28 07:41:28.000000 openmim-0.3.8/openmim.egg-info/top_level.txt
-drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.341375 openmim-0.3.8/requirements/
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      171 2023-06-28 07:39:52.000000 openmim-0.3.8/requirements/docs.txt
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)       67 2023-06-28 07:40:52.000000 openmim-0.3.8/requirements/install.txt
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)       35 2023-06-28 07:39:52.000000 openmim-0.3.8/requirements/tests.txt
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      590 2023-06-28 07:41:28.344375 openmim-0.3.8/setup.cfg
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     3921 2023-06-28 07:39:52.000000 openmim-0.3.8/setup.py
-drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:41:28.343375 openmim-0.3.8/tests/
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2232 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_download.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2952 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_gridsearch.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2750 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_install.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1224 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_list.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2111 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_run.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     4352 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_search.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1939 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_test.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1783 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_train.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2614 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_uninstall.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1655 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_utils.py
--rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      286 2023-06-28 07:39:52.000000 openmim-0.3.8/tests/test_version.py
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:45:11.347388 openmim-0.3.9/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    11408 2023-06-28 07:39:52.000000 openmim-0.3.9/LICENSE
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)       27 2023-06-28 07:39:52.000000 openmim-0.3.9/MANIFEST.in
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    15568 2023-06-28 07:45:11.347388 openmim-0.3.9/PKG-INFO
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    15249 2023-06-28 07:39:52.000000 openmim-0.3.9/README.md
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:45:11.342388 openmim-0.3.9/mim/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      844 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/__init__.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      159 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/__main__.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2968 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/cli.py
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:45:11.343388 openmim-0.3.9/mim/click/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      460 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/click/__init__.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      790 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/click/autocompletion.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1637 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/click/compat.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     4868 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/click/customcommand.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2249 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/click/option.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      190 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/click/utils.py
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:45:11.344388 openmim-0.3.9/mim/commands/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      453 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/commands/__init__.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     9325 2023-06-28 07:44:46.000000 openmim-0.3.9/mim/commands/download.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    16187 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/commands/gridsearch.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    14727 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/commands/install.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2855 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/commands/list.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     5711 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/commands/run.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    27632 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/commands/search.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    10686 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/commands/test.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     9928 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/commands/train.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2404 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/commands/uninstall.py
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:45:11.345388 openmim-0.3.9/mim/utils/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1967 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/utils/__init__.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1297 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/utils/default.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1071 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/utils/progress_bars.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    16351 2023-06-28 07:39:52.000000 openmim-0.3.9/mim/utils/utils.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      500 2023-06-28 07:44:46.000000 openmim-0.3.9/mim/version.py
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:45:11.346388 openmim-0.3.9/openmim.egg-info/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)    15568 2023-06-28 07:45:11.000000 openmim-0.3.9/openmim.egg-info/PKG-INFO
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1056 2023-06-28 07:45:11.000000 openmim-0.3.9/openmim.egg-info/SOURCES.txt
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)        1 2023-06-28 07:45:11.000000 openmim-0.3.9/openmim.egg-info/dependency_links.txt
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)       36 2023-06-28 07:45:11.000000 openmim-0.3.9/openmim.egg-info/entry_points.txt
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      349 2023-06-28 07:45:11.000000 openmim-0.3.9/openmim.egg-info/requires.txt
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)        4 2023-06-28 07:45:11.000000 openmim-0.3.9/openmim.egg-info/top_level.txt
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:45:11.346388 openmim-0.3.9/requirements/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      171 2023-06-28 07:39:52.000000 openmim-0.3.9/requirements/docs.txt
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)       79 2023-06-28 07:44:46.000000 openmim-0.3.9/requirements/install.txt
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)       35 2023-06-28 07:39:52.000000 openmim-0.3.9/requirements/tests.txt
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      590 2023-06-28 07:45:11.348388 openmim-0.3.9/setup.cfg
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     3921 2023-06-28 07:39:52.000000 openmim-0.3.9/setup.py
+drwxrwxr-x   0 zhouzaida (900020515) zhouzaida (900020515)        0 2023-06-28 07:45:11.347388 openmim-0.3.9/tests/
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2232 2023-06-28 07:39:52.000000 openmim-0.3.9/tests/test_download.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2952 2023-06-28 07:39:52.000000 openmim-0.3.9/tests/test_gridsearch.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2750 2023-06-28 07:39:52.000000 openmim-0.3.9/tests/test_install.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1224 2023-06-28 07:39:52.000000 openmim-0.3.9/tests/test_list.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2111 2023-06-28 07:39:52.000000 openmim-0.3.9/tests/test_run.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     4352 2023-06-28 07:39:52.000000 openmim-0.3.9/tests/test_search.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1939 2023-06-28 07:39:52.000000 openmim-0.3.9/tests/test_test.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1783 2023-06-28 07:39:52.000000 openmim-0.3.9/tests/test_train.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     2614 2023-06-28 07:39:52.000000 openmim-0.3.9/tests/test_uninstall.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)     1655 2023-06-28 07:39:52.000000 openmim-0.3.9/tests/test_utils.py
+-rw-rw-r--   0 zhouzaida (900020515) zhouzaida (900020515)      286 2023-06-28 07:39:52.000000 openmim-0.3.9/tests/test_version.py
```

### Comparing `openmim-0.3.8/LICENSE` & `openmim-0.3.9/LICENSE`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/PKG-INFO` & `openmim-0.3.9/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: openmim
-Version: 0.3.8
+Version: 0.3.9
 Summary: MIM Installs OpenMMLab packages
 Home-page: https://github.com/open-mmlab/mim
 Author: MIM Authors
 Author-email: openmmlab@gmail.com
 Requires-Python: >=3.6
 Description-Content-Type: text/markdown
 Provides-Extra: all
```

### Comparing `openmim-0.3.8/README.md` & `openmim-0.3.9/README.md`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/__init__.py` & `openmim-0.3.9/mim/__init__.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/cli.py` & `openmim-0.3.9/mim/cli.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/click/autocompletion.py` & `openmim-0.3.9/mim/click/autocompletion.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/click/compat.py` & `openmim-0.3.9/mim/click/compat.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/click/customcommand.py` & `openmim-0.3.9/mim/click/customcommand.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/click/option.py` & `openmim-0.3.9/mim/click/option.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/commands/gridsearch.py` & `openmim-0.3.9/mim/commands/gridsearch.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/commands/install.py` & `openmim-0.3.9/mim/commands/install.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/commands/list.py` & `openmim-0.3.9/mim/commands/list.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/commands/run.py` & `openmim-0.3.9/mim/commands/run.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/commands/search.py` & `openmim-0.3.9/mim/commands/search.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/commands/test.py` & `openmim-0.3.9/mim/commands/test.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/commands/train.py` & `openmim-0.3.9/mim/commands/train.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/commands/uninstall.py` & `openmim-0.3.9/mim/commands/uninstall.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/utils/__init__.py` & `openmim-0.3.9/mim/utils/__init__.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/utils/default.py` & `openmim-0.3.9/mim/utils/default.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/utils/progress_bars.py` & `openmim-0.3.9/mim/utils/progress_bars.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/mim/utils/utils.py` & `openmim-0.3.9/mim/utils/utils.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/openmim.egg-info/PKG-INFO` & `openmim-0.3.9/openmim.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: openmim
-Version: 0.3.8
+Version: 0.3.9
 Summary: MIM Installs OpenMMLab packages
 Home-page: https://github.com/open-mmlab/mim
 Author: MIM Authors
 Author-email: openmmlab@gmail.com
 Requires-Python: >=3.6
 Description-Content-Type: text/markdown
 Provides-Extra: all
```

### Comparing `openmim-0.3.8/openmim.egg-info/SOURCES.txt` & `openmim-0.3.9/openmim.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/setup.cfg` & `openmim-0.3.9/setup.cfg`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/setup.py` & `openmim-0.3.9/setup.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/tests/test_download.py` & `openmim-0.3.9/tests/test_download.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/tests/test_gridsearch.py` & `openmim-0.3.9/tests/test_gridsearch.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/tests/test_install.py` & `openmim-0.3.9/tests/test_install.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/tests/test_list.py` & `openmim-0.3.9/tests/test_list.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/tests/test_run.py` & `openmim-0.3.9/tests/test_run.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/tests/test_search.py` & `openmim-0.3.9/tests/test_search.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/tests/test_test.py` & `openmim-0.3.9/tests/test_test.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/tests/test_train.py` & `openmim-0.3.9/tests/test_train.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/tests/test_uninstall.py` & `openmim-0.3.9/tests/test_uninstall.py`

 * *Files identical despite different names*

### Comparing `openmim-0.3.8/tests/test_utils.py` & `openmim-0.3.9/tests/test_utils.py`

 * *Files identical despite different names*


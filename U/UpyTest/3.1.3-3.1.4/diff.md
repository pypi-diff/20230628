# Comparing `tmp/UpyTest-3.1.3.tar.gz` & `tmp/UpyTest-3.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "UpyTest-3.1.3.tar", last modified: Sun Jun 25 22:27:11 2023, max compression
+gzip compressed data, was "UpyTest-3.1.4.tar", last modified: Wed Jun 28 00:15:25 2023, max compression
```

## Comparing `UpyTest-3.1.3.tar` & `UpyTest-3.1.4.tar`

### file list

```diff
@@ -1,72 +1,72 @@
-drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-25 22:27:11.231478 UpyTest-3.1.3/
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      694 2023-06-25 22:27:11.231478 UpyTest-3.1.3/PKG-INFO
-drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-25 22:27:11.223478 UpyTest-3.1.3/UpyTest.egg-info/
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      694 2023-06-25 22:27:11.000000 UpyTest-3.1.3/UpyTest.egg-info/PKG-INFO
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2351 2023-06-25 22:27:11.000000 UpyTest-3.1.3/UpyTest.egg-info/SOURCES.txt
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        1 2023-06-25 22:27:11.000000 UpyTest-3.1.3/UpyTest.egg-info/dependency_links.txt
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)       14 2023-06-25 22:27:11.000000 UpyTest-3.1.3/UpyTest.egg-info/requires.txt
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)       14 2023-06-25 22:27:11.000000 UpyTest-3.1.3/UpyTest.egg-info/top_level.txt
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)       38 2023-06-25 22:27:11.231478 UpyTest-3.1.3/setup.cfg
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1985 2023-06-25 22:23:46.000000 UpyTest-3.1.3/setup.py
-drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-25 22:27:11.223478 UpyTest-3.1.3/thonnycontrib/
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      947 2023-06-24 22:43:54.000000 UpyTest-3.1.3/thonnycontrib/ThonnyLogsGenerator.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-24 22:52:20.000000 UpyTest-3.1.3/thonnycontrib/__init__.py
-drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-25 22:27:11.223478 UpyTest-3.1.3/thonnycontrib/backend/
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        0 2023-03-15 10:38:40.000000 UpyTest-3.1.3/thonnycontrib/backend/__init__.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    16304 2023-06-24 19:59:14.000000 UpyTest-3.1.3/thonnycontrib/backend/ast_parser.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    35328 2023-06-25 21:33:06.000000 UpyTest-3.1.3/thonnycontrib/backend/doctest_parser.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     5028 2023-06-24 15:10:56.000000 UpyTest-3.1.3/thonnycontrib/backend/evaluator.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     4503 2023-06-25 22:01:28.000000 UpyTest-3.1.3/thonnycontrib/backend/l1test_backend.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     6541 2023-06-24 18:11:15.000000 UpyTest-3.1.3/thonnycontrib/backend/test_finder.py
-drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-25 22:27:11.223478 UpyTest-3.1.3/thonnycontrib/backend/verdicts/
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2057 2023-06-24 19:29:56.000000 UpyTest-3.1.3/thonnycontrib/backend/verdicts/ExampleVerdict.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      496 2023-06-24 18:12:47.000000 UpyTest-3.1.3/thonnycontrib/backend/verdicts/ExceptionVerdict.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      733 2023-06-24 18:13:06.000000 UpyTest-3.1.3/thonnycontrib/backend/verdicts/FailedVerdict.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      637 2023-06-24 19:25:27.000000 UpyTest-3.1.3/thonnycontrib/backend/verdicts/FailedWhenExceptionExpectedVerdict.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      450 2023-06-24 18:12:56.000000 UpyTest-3.1.3/thonnycontrib/backend/verdicts/PassedVerdict.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      377 2023-06-24 18:13:00.000000 UpyTest-3.1.3/thonnycontrib/backend/verdicts/SetupVerdict.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-24 02:35:02.000000 UpyTest-3.1.3/thonnycontrib/backend/verdicts/__init__.py
-drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-25 22:27:11.223478 UpyTest-3.1.3/thonnycontrib/docs/
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        0 2023-03-15 10:38:40.000000 UpyTest-3.1.3/thonnycontrib/docs/__init__.py
-drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-25 22:27:11.227478 UpyTest-3.1.3/thonnycontrib/docs/res/
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      912 2023-06-21 22:17:10.000000 UpyTest-3.1.3/thonnycontrib/docs/res/error_icon.png
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1275 2023-03-15 10:38:40.000000 UpyTest-3.1.3/thonnycontrib/docs/res/failed.png
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1468 2023-06-25 02:50:15.000000 UpyTest-3.1.3/thonnycontrib/docs/res/l1test_debug.png
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2130 2023-03-15 10:38:40.000000 UpyTest-3.1.3/thonnycontrib/docs/res/l1test_icon.png
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2086 2023-03-15 10:38:40.000000 UpyTest-3.1.3/thonnycontrib/docs/res/l1test_icon_old.png
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      628 2023-04-23 12:41:34.000000 UpyTest-3.1.3/thonnycontrib/docs/res/outline_class.png
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      578 2023-04-23 12:41:32.000000 UpyTest-3.1.3/thonnycontrib/docs/res/outline_method.gif
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1213 2023-03-15 10:38:40.000000 UpyTest-3.1.3/thonnycontrib/docs/res/passed.png
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1531 2023-03-15 10:38:40.000000 UpyTest-3.1.3/thonnycontrib/docs/res/pending_icon.png
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      997 2023-06-21 22:19:21.000000 UpyTest-3.1.3/thonnycontrib/docs/res/restart_icon.png
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2282 2023-03-15 10:38:40.000000 UpyTest-3.1.3/thonnycontrib/docs/res/test_only_btn.png
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1073 2023-03-15 10:38:40.000000 UpyTest-3.1.3/thonnycontrib/docs/res/warning.png
-drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-25 22:27:11.227478 UpyTest-3.1.3/thonnycontrib/docstring_generator/
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        0 2023-03-15 10:38:40.000000 UpyTest-3.1.3/thonnycontrib/docstring_generator/__init__.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     8660 2023-06-24 13:42:03.000000 UpyTest-3.1.3/thonnycontrib/docstring_generator/doc_generator.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     7134 2023-03-15 10:38:40.000000 UpyTest-3.1.3/thonnycontrib/docstring_generator/doc_template.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1315 2023-06-25 20:12:20.000000 UpyTest-3.1.3/thonnycontrib/environement_vars.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     3756 2023-06-23 23:49:24.000000 UpyTest-3.1.3/thonnycontrib/exceptions.py
-drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-25 22:27:11.227478 UpyTest-3.1.3/thonnycontrib/l1test_configuration/
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        0 2023-03-15 10:38:40.000000 UpyTest-3.1.3/thonnycontrib/l1test_configuration/__init__.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2575 2023-04-02 02:23:42.000000 UpyTest-3.1.3/thonnycontrib/l1test_configuration/l1test_options.py
-drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-25 22:27:11.227478 UpyTest-3.1.3/thonnycontrib/l1test_frontend/
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      708 2023-06-24 22:52:29.000000 UpyTest-3.1.3/thonnycontrib/l1test_frontend/__init__.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2507 2023-06-25 03:08:15.000000 UpyTest-3.1.3/thonnycontrib/l1test_frontend/l1test_error_view.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2756 2023-06-25 13:23:15.000000 UpyTest-3.1.3/thonnycontrib/l1test_frontend/l1test_reporter.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    23428 2023-06-25 22:26:48.000000 UpyTest-3.1.3/thonnycontrib/l1test_frontend/l1test_runner.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    36550 2023-06-25 20:32:06.000000 UpyTest-3.1.3/thonnycontrib/l1test_frontend/l1test_treeview.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     3523 2023-06-25 21:48:20.000000 UpyTest-3.1.3/thonnycontrib/l1test_frontend/outlines.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     7310 2023-06-25 21:56:55.000000 UpyTest-3.1.3/thonnycontrib/plugin_loader.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2432 2023-06-25 02:35:31.000000 UpyTest-3.1.3/thonnycontrib/properties.py
-drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-25 22:27:11.231478 UpyTest-3.1.3/thonnycontrib/tests/
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        0 2023-03-15 10:38:42.000000 UpyTest-3.1.3/thonnycontrib/tests/__init__.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      348 2023-03-15 10:38:42.000000 UpyTest-3.1.3/thonnycontrib/tests/backend_mock.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1980 2023-03-15 10:38:42.000000 UpyTest-3.1.3/thonnycontrib/tests/test_doc_generator.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     4848 2023-06-24 02:33:48.000000 UpyTest-3.1.3/thonnycontrib/tests/tests_example_no_expected.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    14741 2023-06-24 02:34:31.000000 UpyTest-3.1.3/thonnycontrib/tests/tests_example_with_exception.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    18496 2023-06-24 02:34:31.000000 UpyTest-3.1.3/thonnycontrib/tests/tests_example_with_expected.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     9799 2023-06-25 13:23:15.000000 UpyTest-3.1.3/thonnycontrib/tests/tests_l1TestRunner.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     6392 2023-06-23 23:27:45.000000 UpyTest-3.1.3/thonnycontrib/tests/tests_test_finder.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    12629 2023-06-24 02:34:31.000000 UpyTest-3.1.3/thonnycontrib/tests/tests_view.py
--rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    18919 2023-06-25 22:06:41.000000 UpyTest-3.1.3/thonnycontrib/utils.py
+drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-28 00:15:25.120608 UpyTest-3.1.4/
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      694 2023-06-28 00:15:25.120608 UpyTest-3.1.4/PKG-INFO
+drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-28 00:15:25.108608 UpyTest-3.1.4/UpyTest.egg-info/
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      694 2023-06-28 00:15:25.000000 UpyTest-3.1.4/UpyTest.egg-info/PKG-INFO
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2351 2023-06-28 00:15:25.000000 UpyTest-3.1.4/UpyTest.egg-info/SOURCES.txt
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        1 2023-06-28 00:15:25.000000 UpyTest-3.1.4/UpyTest.egg-info/dependency_links.txt
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)       14 2023-06-28 00:15:25.000000 UpyTest-3.1.4/UpyTest.egg-info/requires.txt
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)       14 2023-06-28 00:15:25.000000 UpyTest-3.1.4/UpyTest.egg-info/top_level.txt
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)       38 2023-06-28 00:15:25.120608 UpyTest-3.1.4/setup.cfg
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1985 2023-06-28 00:15:21.000000 UpyTest-3.1.4/setup.py
+drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-28 00:15:25.112608 UpyTest-3.1.4/thonnycontrib/
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      947 2023-06-24 22:43:54.000000 UpyTest-3.1.4/thonnycontrib/ThonnyLogsGenerator.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-24 22:52:20.000000 UpyTest-3.1.4/thonnycontrib/__init__.py
+drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-28 00:15:25.112608 UpyTest-3.1.4/thonnycontrib/backend/
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        0 2023-03-15 10:38:40.000000 UpyTest-3.1.4/thonnycontrib/backend/__init__.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    16304 2023-06-24 19:59:14.000000 UpyTest-3.1.4/thonnycontrib/backend/ast_parser.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    35328 2023-06-25 21:33:06.000000 UpyTest-3.1.4/thonnycontrib/backend/doctest_parser.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     5028 2023-06-24 15:10:56.000000 UpyTest-3.1.4/thonnycontrib/backend/evaluator.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     4503 2023-06-25 22:01:28.000000 UpyTest-3.1.4/thonnycontrib/backend/l1test_backend.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     6541 2023-06-24 18:11:15.000000 UpyTest-3.1.4/thonnycontrib/backend/test_finder.py
+drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-28 00:15:25.112608 UpyTest-3.1.4/thonnycontrib/backend/verdicts/
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2057 2023-06-24 19:29:56.000000 UpyTest-3.1.4/thonnycontrib/backend/verdicts/ExampleVerdict.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      496 2023-06-24 18:12:47.000000 UpyTest-3.1.4/thonnycontrib/backend/verdicts/ExceptionVerdict.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      733 2023-06-24 18:13:06.000000 UpyTest-3.1.4/thonnycontrib/backend/verdicts/FailedVerdict.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      637 2023-06-24 19:25:27.000000 UpyTest-3.1.4/thonnycontrib/backend/verdicts/FailedWhenExceptionExpectedVerdict.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      450 2023-06-24 18:12:56.000000 UpyTest-3.1.4/thonnycontrib/backend/verdicts/PassedVerdict.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      377 2023-06-24 18:13:00.000000 UpyTest-3.1.4/thonnycontrib/backend/verdicts/SetupVerdict.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-24 02:35:02.000000 UpyTest-3.1.4/thonnycontrib/backend/verdicts/__init__.py
+drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-28 00:15:25.112608 UpyTest-3.1.4/thonnycontrib/docs/
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        0 2023-03-15 10:38:40.000000 UpyTest-3.1.4/thonnycontrib/docs/__init__.py
+drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-28 00:15:25.116608 UpyTest-3.1.4/thonnycontrib/docs/res/
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      912 2023-06-21 22:17:10.000000 UpyTest-3.1.4/thonnycontrib/docs/res/error_icon.png
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1275 2023-03-15 10:38:40.000000 UpyTest-3.1.4/thonnycontrib/docs/res/failed.png
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1468 2023-06-25 02:50:15.000000 UpyTest-3.1.4/thonnycontrib/docs/res/l1test_debug.png
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2130 2023-03-15 10:38:40.000000 UpyTest-3.1.4/thonnycontrib/docs/res/l1test_icon.png
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2086 2023-03-15 10:38:40.000000 UpyTest-3.1.4/thonnycontrib/docs/res/l1test_icon_old.png
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      628 2023-04-23 12:41:34.000000 UpyTest-3.1.4/thonnycontrib/docs/res/outline_class.png
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      578 2023-04-23 12:41:32.000000 UpyTest-3.1.4/thonnycontrib/docs/res/outline_method.gif
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1213 2023-03-15 10:38:40.000000 UpyTest-3.1.4/thonnycontrib/docs/res/passed.png
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1531 2023-03-15 10:38:40.000000 UpyTest-3.1.4/thonnycontrib/docs/res/pending_icon.png
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      997 2023-06-21 22:19:21.000000 UpyTest-3.1.4/thonnycontrib/docs/res/restart_icon.png
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2282 2023-03-15 10:38:40.000000 UpyTest-3.1.4/thonnycontrib/docs/res/test_only_btn.png
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1073 2023-03-15 10:38:40.000000 UpyTest-3.1.4/thonnycontrib/docs/res/warning.png
+drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-28 00:15:25.116608 UpyTest-3.1.4/thonnycontrib/docstring_generator/
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        0 2023-03-15 10:38:40.000000 UpyTest-3.1.4/thonnycontrib/docstring_generator/__init__.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     8660 2023-06-24 13:42:03.000000 UpyTest-3.1.4/thonnycontrib/docstring_generator/doc_generator.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     7134 2023-03-15 10:38:40.000000 UpyTest-3.1.4/thonnycontrib/docstring_generator/doc_template.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1315 2023-06-25 20:12:20.000000 UpyTest-3.1.4/thonnycontrib/environement_vars.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     3756 2023-06-23 23:49:24.000000 UpyTest-3.1.4/thonnycontrib/exceptions.py
+drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-28 00:15:25.116608 UpyTest-3.1.4/thonnycontrib/l1test_configuration/
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        0 2023-03-15 10:38:40.000000 UpyTest-3.1.4/thonnycontrib/l1test_configuration/__init__.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2575 2023-04-02 02:23:42.000000 UpyTest-3.1.4/thonnycontrib/l1test_configuration/l1test_options.py
+drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-28 00:15:25.120608 UpyTest-3.1.4/thonnycontrib/l1test_frontend/
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      708 2023-06-24 22:52:29.000000 UpyTest-3.1.4/thonnycontrib/l1test_frontend/__init__.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2507 2023-06-25 03:08:15.000000 UpyTest-3.1.4/thonnycontrib/l1test_frontend/l1test_error_view.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2756 2023-06-25 13:23:15.000000 UpyTest-3.1.4/thonnycontrib/l1test_frontend/l1test_reporter.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    23240 2023-06-26 21:41:29.000000 UpyTest-3.1.4/thonnycontrib/l1test_frontend/l1test_runner.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    36572 2023-06-28 00:14:02.000000 UpyTest-3.1.4/thonnycontrib/l1test_frontend/l1test_treeview.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     3523 2023-06-25 21:48:20.000000 UpyTest-3.1.4/thonnycontrib/l1test_frontend/outlines.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     7311 2023-06-26 21:06:12.000000 UpyTest-3.1.4/thonnycontrib/plugin_loader.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     2485 2023-06-26 23:21:42.000000 UpyTest-3.1.4/thonnycontrib/properties.py
+drwxrwxr-x   0 idtaleb   (1000) idtaleb   (1000)        0 2023-06-28 00:15:25.120608 UpyTest-3.1.4/thonnycontrib/tests/
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)        0 2023-03-15 10:38:42.000000 UpyTest-3.1.4/thonnycontrib/tests/__init__.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)      348 2023-03-15 10:38:42.000000 UpyTest-3.1.4/thonnycontrib/tests/backend_mock.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     1980 2023-03-15 10:38:42.000000 UpyTest-3.1.4/thonnycontrib/tests/test_doc_generator.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     4848 2023-06-24 02:33:48.000000 UpyTest-3.1.4/thonnycontrib/tests/tests_example_no_expected.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    14741 2023-06-24 02:34:31.000000 UpyTest-3.1.4/thonnycontrib/tests/tests_example_with_exception.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    18496 2023-06-24 02:34:31.000000 UpyTest-3.1.4/thonnycontrib/tests/tests_example_with_expected.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     9799 2023-06-25 13:23:15.000000 UpyTest-3.1.4/thonnycontrib/tests/tests_l1TestRunner.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)     6392 2023-06-23 23:27:45.000000 UpyTest-3.1.4/thonnycontrib/tests/tests_test_finder.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    12629 2023-06-24 02:34:31.000000 UpyTest-3.1.4/thonnycontrib/tests/tests_view.py
+-rw-rw-r--   0 idtaleb   (1000) idtaleb   (1000)    18925 2023-06-26 22:59:16.000000 UpyTest-3.1.4/thonnycontrib/utils.py
```

### Comparing `UpyTest-3.1.3/PKG-INFO` & `UpyTest-3.1.4/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: UpyTest
-Version: 3.1.3
+Version: 3.1.4
 Summary: A plug-in which adds a test framework
 Home-page: https://gitlab.univ-lille.fr/reda.idtaleb.etu/thonny_test_framework
 Author: Réda Id-taleb
 Platform: Windows
 Platform: macOS
 Platform: Linux
 Classifier: Topic :: Education :: Testing
```

### Comparing `UpyTest-3.1.3/UpyTest.egg-info/PKG-INFO` & `UpyTest-3.1.4/UpyTest.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: UpyTest
-Version: 3.1.3
+Version: 3.1.4
 Summary: A plug-in which adds a test framework
 Home-page: https://gitlab.univ-lille.fr/reda.idtaleb.etu/thonny_test_framework
 Author: Réda Id-taleb
 Platform: Windows
 Platform: macOS
 Platform: Linux
 Classifier: Topic :: Education :: Testing
```

### Comparing `UpyTest-3.1.3/UpyTest.egg-info/SOURCES.txt` & `UpyTest-3.1.4/UpyTest.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/setup.py` & `UpyTest-3.1.4/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -27,15 +27,15 @@
     return py_packs | other_packs
 
 setupdir = os.path.dirname(__file__)
 
 
 setup(
     name="UpyTest",
-    version="3.1.3",
+    version="3.1.4",
     author="Réda Id-taleb",
     description="A plug-in which adds a test framework",
     long_description="""A plug-in for Thonny which allows you to test your doc examples
  
 More info: https://gitlab.univ-lille.fr/reda.idtaleb.etu/thonny_test_framework""",
     url="https://gitlab.univ-lille.fr/reda.idtaleb.etu/thonny_test_framework",
 #    keywords="IDE education programming tests in documentation",
```

### Comparing `UpyTest-3.1.3/thonnycontrib/ThonnyLogsGenerator.py` & `UpyTest-3.1.4/thonnycontrib/ThonnyLogsGenerator.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/backend/ast_parser.py` & `UpyTest-3.1.4/thonnycontrib/backend/ast_parser.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/backend/doctest_parser.py` & `UpyTest-3.1.4/thonnycontrib/backend/doctest_parser.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/backend/evaluator.py` & `UpyTest-3.1.4/thonnycontrib/backend/evaluator.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/backend/l1test_backend.py` & `UpyTest-3.1.4/thonnycontrib/backend/l1test_backend.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/backend/test_finder.py` & `UpyTest-3.1.4/thonnycontrib/backend/test_finder.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/backend/verdicts/ExampleVerdict.py` & `UpyTest-3.1.4/thonnycontrib/backend/verdicts/ExampleVerdict.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/backend/verdicts/FailedVerdict.py` & `UpyTest-3.1.4/thonnycontrib/backend/verdicts/FailedVerdict.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/backend/verdicts/FailedWhenExceptionExpectedVerdict.py` & `UpyTest-3.1.4/thonnycontrib/backend/verdicts/FailedWhenExceptionExpectedVerdict.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/docs/res/error_icon.png` & `UpyTest-3.1.4/thonnycontrib/docs/res/error_icon.png`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/docs/res/failed.png` & `UpyTest-3.1.4/thonnycontrib/docs/res/failed.png`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/docs/res/l1test_debug.png` & `UpyTest-3.1.4/thonnycontrib/docs/res/l1test_debug.png`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/docs/res/l1test_icon.png` & `UpyTest-3.1.4/thonnycontrib/docs/res/l1test_icon.png`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/docs/res/l1test_icon_old.png` & `UpyTest-3.1.4/thonnycontrib/docs/res/l1test_icon_old.png`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/docs/res/outline_class.png` & `UpyTest-3.1.4/thonnycontrib/docs/res/outline_class.png`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/docs/res/outline_method.gif` & `UpyTest-3.1.4/thonnycontrib/docs/res/outline_method.gif`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/docs/res/passed.png` & `UpyTest-3.1.4/thonnycontrib/docs/res/passed.png`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/docs/res/pending_icon.png` & `UpyTest-3.1.4/thonnycontrib/docs/res/pending_icon.png`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/docs/res/restart_icon.png` & `UpyTest-3.1.4/thonnycontrib/docs/res/restart_icon.png`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/docs/res/test_only_btn.png` & `UpyTest-3.1.4/thonnycontrib/docs/res/test_only_btn.png`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/docs/res/warning.png` & `UpyTest-3.1.4/thonnycontrib/docs/res/warning.png`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/docstring_generator/doc_generator.py` & `UpyTest-3.1.4/thonnycontrib/docstring_generator/doc_generator.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/docstring_generator/doc_template.py` & `UpyTest-3.1.4/thonnycontrib/docstring_generator/doc_template.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/environement_vars.py` & `UpyTest-3.1.4/thonnycontrib/environement_vars.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/exceptions.py` & `UpyTest-3.1.4/thonnycontrib/exceptions.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/l1test_configuration/l1test_options.py` & `UpyTest-3.1.4/thonnycontrib/l1test_configuration/l1test_options.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/l1test_frontend/__init__.py` & `UpyTest-3.1.4/thonnycontrib/l1test_frontend/__init__.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/l1test_frontend/l1test_error_view.py` & `UpyTest-3.1.4/thonnycontrib/l1test_frontend/l1test_error_view.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/l1test_frontend/l1test_reporter.py` & `UpyTest-3.1.4/thonnycontrib/l1test_frontend/l1test_reporter.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/l1test_frontend/l1test_runner.py` & `UpyTest-3.1.4/thonnycontrib/l1test_frontend/l1test_runner.py`

 * *Files 2% similar despite different names*

```diff
@@ -44,21 +44,21 @@
         self._reporter = L1TestReporter() if not reporter else reporter
         self._has_exception = False
         self._is_l1test_running = False
         self._is_pending = False
         
         # Quand le backend envoie une réponse de type `ToplevelResponse``,
         # alors le TestRunner va invoquer la fonction `show_verdicts`
-        thonny.get_workbench().bind("ToplevelResponse", self.report_verdicts, True)
+        thonny.get_workbench().bind("ToplevelResponse", self._handle_backend_response, True)
         
         # Quand le backend envoie une réponse de type `InlineResponse``,
         # alors le TestRunner va invoquer la fonction `show_execution_state`
-        thonny.get_workbench().bind("InlineResponse", self.show_execution_state, True)
+        thonny.get_workbench().bind("InlineResponse", self._show_execution_state, True)
         
-        thonny.get_workbench().bind(L1TREE_VIEW_EVENT, self.show_right_view, True)
+        thonny.get_workbench().bind(L1TREE_VIEW_EVENT, self._handle_clicked_exception, True)
         
         # Quand le backend est redémarré en thonny nous invoquons la méthode 
         # `self._on_restart_backend()`
         thonny.get_workbench().bind(BACKEND_RESTART_EVENT, self._on_restart_backend, True)
     
     def run_l1test(self, selected_line: int=None):
         """
@@ -96,15 +96,15 @@
             
             # si on est là alors le fichier est bien sauvegardé et contient quelque chose.
             self.request_backend(selected_line)         
         except FrontendException as e: # on catche que les exception coté view
             self.terminate_running()
             self.set_has_exception(True) 
             self.clean_error_view()
-            self.show_right_view(error_msg=str(e))
+            self._show_right_view(error_msg=str(e))
     
     def request_backend(self, selected_line:int):
         """Allows to execute the `L1test` magic command. 
         
         There's two cases : 
         1. if the `L1test` is invoked for the first so the command is sent to 
         backend to be executed by the thonny's runner. 
@@ -191,15 +191,15 @@
         if selected_line:
             os.environ[SELECTED_LINE_VAR] = str(selected_line)
         
         # Une fois que execute_current() est executée un restart backend partiel est invoqué
         # pour un nouveau processus pour la commande passé en paramètre.
         thonny.get_runner().execute_current(command_name)
     
-    def show_execution_state(self, msg: InlineResponse):
+    def _show_execution_state(self, msg: InlineResponse):
         """
         This function is called when an event of type InlineResponse is received. 
         This function verfies the source of the event. If the source is L1Test so it will access to the 
         received response and then it will show the state of the execution.
         """
         if self._is_relevant_response(msg):
             self.clean_error_view()
@@ -222,15 +222,15 @@
                                     text="Interrompez avec 'ctrl+c', si ce test prend plus de temps.", 
                                     tags=("nonClickable", "orange"))
             elif state == EXECUTED_STATE: 
                 treeview.insert_row(parent=self.row, text=state, tags=("nonClickable", "green"))  
             else: # si le state == FINISHED_STATE
                 self.set_pending(False) 
     
-    def report_verdicts(self, msg: ToplevelResponse):     
+    def _handle_backend_response(self, msg: ToplevelResponse):     
         """
         This method is binded to the `TopLevelResponse` event sent by the backend.
         
         If this method is triggered so the `msg` parameter will contain the response received 
         from the backend. Please note that the `TopLevelResponse` event is not necessary sent 
         by the l1test_backend, but it can be also sent by the Shell. The shell contains an 
         internal infinite loop that waits for commands and sends the responses periodically.
@@ -243,15 +243,15 @@
         
         Note: The data is deserialized before displaying it on the view.
         """   
        
         # On vérifie si le TopLevelRespone reçu est envoyé par le l1test_backend 
         if self._is_relevant_response(msg):
             verdicts, error_msg = self.__get_verdicts_and_error(msg)
-            self.show_right_view(verdicts=verdicts, error_msg=error_msg.msg, error_title=error_msg.title)
+            self._show_right_view(verdicts=verdicts, error_msg=error_msg.msg, error_title=error_msg.title)
         else:
             # Le TopLevelReponse reçu ne nous intéresse pas.
             return 
         # On indique l'état de l'execution du la commande comme terminée
         self.terminate_running()
     
     def __get_verdicts_and_error(self, msg:ToplevelResponse):
@@ -377,55 +377,47 @@
                 if self.is_running(): 
                     self.clean_treeview()
                     treeview:L1TestTreeView = self._reporter.get_treeview()
                     treeview.insert_in_header("Starting executing tests ...", clear=True, tags="blue", 
                                               image="pending_icon.png")
                 else: # probablement une autre commande a déclenché le Restart du backend -> on fait rien
                     pass
-        self.show_right_view()
+        self._show_right_view()
     
-    def show_right_view(self, event:WorkbenchEvent=None, verdicts=None, error_msg:str=None, error_title:str=None, both=False):
+    def _show_right_view(self, verdicts=None, error_msg:str=None, error_title:str=None, both=False):
         """
-            Displays either the L1TestTreeView or the L1TestErrorView. 
-            It depends on the execution state of the l1test plugin. 
-            
-            If an error was raised by the plugin then only the Error view will be displayed.
+        Displays either the L1TestTreeView or the L1TestErrorView. 
+        It depends on the execution state of the l1test plugin. 
+        
+        If an error was raised by the plugin then only the Error view will be displayed.
         """
-        exception_details = False
-        if event and event.get("sequence") == L1TREE_VIEW_EVENT:
-            possible_keys = ["sequence", "exception_details", "both", "verdicts", "error_msg", "error_title"]
-            assert any(key in possible_keys for key in event.__dict__.keys())
-            if event.get("exception_details") != None:
-                exception_details = event.exception_details
-            if event.get("verdicts") != None:
-                verdicts = event.verdicts
-            if event.get("error_msg") != None:
-                error_msg = event.error_msg 
-            if event.get("error_title") != None: 
-                error_title = event.error_title
-            if event.get("both") != None: 
-                both = event.both
-        if (self._has_exception or exception_details):
+        if (self._has_exception or error_msg):
             if error_msg:
                 self.show_errors(exception_msg=error_msg, title=error_title)
-            if not both:
-                self._reporter.get_treeview().hide_view()
-            else:
-                self._reporter.get_treeview().show_view()
-            self._reporter.get_l1test_error_view().show_view()
+            self._reporter.get_l1test_error_view().show_view()  
+            self._reporter.get_treeview().hide_view() if not both else self._reporter.get_treeview().show_view()
         else:
             self.clean_error_view()
             if verdicts:
                 self.show_verdicts(verdicts)
-            if not both:
-                self._reporter.get_l1test_error_view().hide_view()
-            else:
-                self._reporter.get_l1test_error_view().show_view()
             self._reporter.get_treeview().show_view()
+            self._reporter.get_l1test_error_view().hide_view() if not both else self._reporter.get_l1test_error_view().show_view()    
     
+    def _handle_clicked_exception(self, event:WorkbenchEvent=None):
+        """ 
+        This function is called when the user clicks on an exception in the treeview. Then, 
+        the error view is displayed with the details of the clicked exception. 
+        """
+        possible_keys = ["sequence", "error_title", "error_msg", "both"]
+        if event and event.get("sequence") == L1TREE_VIEW_EVENT:
+            assert all(key in possible_keys for key in event.__dict__.keys())
+            self._show_right_view(error_msg=event.error_msg, 
+                                  error_title=event.error_title, 
+                                  both=event.both)
+          
     def show_verdicts(self, test_results:List[L1DocTest]):
         """
         Report the verdicts on the view.
 
         Args:
             test_results (dict): The recieved verdicts from the backend.
         """
```

### Comparing `UpyTest-3.1.3/thonnycontrib/l1test_frontend/l1test_treeview.py` & `UpyTest-3.1.4/thonnycontrib/l1test_frontend/l1test_treeview.py`

 * *Files 3% similar despite different names*

```diff
@@ -14,15 +14,18 @@
 import tkinter as tk, tkinter.font as tk_font, thonny
 from collections import namedtuple
 from thonny.codeview import *
 from typing import Dict, List
 from copy import deepcopy
 
 # La hauteur, par défault, d'une ligne dans une Treeview
-ROW_HEIGHT  = 40
+ROW_HEIGHT = 40
+
+SMALL_MARGIN = 1.1
+NORMAL_MARGIN = 1.2
 
 clickable_tag = "clickable"
 
 # L'objet qui représente un summarize
 Summarize = namedtuple('Summarize', ["total", "success", "failures", "errors", "empty"])
 
 # Palette de couleurs utilisée par la treeview
@@ -97,19 +100,21 @@
 
         self.image_references["pending_icon.png"] = get_photoImage("pending_icon.png")
         self.image_references["error_icon.png"] = get_photoImage("error_icon.png")
         self.image_references["restart_icon.png"] = get_photoImage("restart_icon.png")
         
         # add a menu to the treeview
         self.menu = tk.Menu(self.treeview, name="menu", tearoff=False)
-
-        # Here we handle the motion event of the treeview
-        self.treeview.bind("<Configure>", partial(self.__wrap_tree_content, self.treeview))
-        self.selected_item = None
         
+        # Here we handle the motion event of the treeview 
+        self.treeview.bind("<Configure>", partial(self.__wrap_tree_content, self.treeview))
+        self.treeview.bind("<Shift-I>", self.increase_row_height, True)
+        self.treeview.bind("<Shift-D>", self.decrease_row_height, True)
+        self.workbench.bind("<Shift-F>", self.update_font, True)
+
     # ------------------------------------
     # Fonctions pour le Header du treeview
     # ------------------------------------
     
     def init_header(self, row=0, column=0):
         """
         Initialize the header of the treeview. Initially, the header contains 
@@ -178,26 +183,27 @@
         self.menu.add_command(label=SHOW_ONLY_RED_TESTS, command=self.show_only_red_tests)
         self.menu.add_command(label=SHOW_ALL_TESTS, command=self.show_all_tests)
         self.menu.add_separator()
         self.menu.add_command(label=GROUP_BY_VERDICTS, command=self.group_by_verdicts)
         self.menu.add_separator()    
         self.menu.add_command(label=EXPAND_TEST_RESULTS, command=self.expand_rows) 
         self.menu.add_command(label=FOLD_TEST_RESULTS, command=self.fold_rows)
-        self.menu.add_separator()
-        self.menu.add_command(label=UPDATE_FONT_LABEL, command=self.update_font)
-        self.menu.add_command(label=REDUCE_SPACE_BETWEEN_ROWS, command=self.reduce_space_between_rows)
+        self.menu.add_separator() 
+        self.menu.add_command(label=UPDATE_FONT_LABEL, command=self.update_font, accelerator="Shift+f")
+        self.menu.add_command(label=INCREASE_SPACE_BETWEEN_ROWS, command=self.increase_row_height, accelerator="Shift+i")
+        self.menu.add_command(label=DECREASE_SPACE_BETWEEN_ROWS, command=self.decrease_row_height, accelerator="Shift+d")
         self.menu.add_command(label=REMOVE_ERROR_DETAILS if not get_option(EXCEPTION_DETAIL) else INCLUDE_ERROR_DETAILS, 
                               command=self.remove_error_details)
         self.menu.add_separator()
         self.menu.add_command(label=CLEAR_LABEL, command=self.clear_tree) 
          
     def resize_header_bar(self, event=None):
         """
-            Resize the height of the header.
-            Always keep this method otherwise the header will take the whole treeview.
+        Resize the height of the header.
+        Always keep this method otherwise the header will take the whole treeview.
         """
         height = self.tk.call((self.header_bar, "count", "-update", "-displaylines", "1.0", "end"))
         self.header_bar.configure(height=height)
 
     def update_font(self, event=None):
         """
             This is the handler of the `Update the font` option. The handler inserts the 
@@ -210,15 +216,15 @@
             be removed after refresh.
         """
         all_childs = get_all_tree_childrens(self.treeview)
         rowheight = ROW_HEIGHT
         if all_childs:
             # on calcule le meilleure height à appliquer pour la treeview.
             # Cela est fait quand la taille de la police a changé dans thonny.
-            rowheight = self.get_optimal_row_height(self.treeview, all_childs)
+            rowheight = self.get_optimal_row_height(all_childs)
                      
         self.resize_header_bar()
         # on applique la nouvelle police pour la treeview
         self.__observe_font_changing(rowheight=rowheight)
     
     def sort_by_red_tests(self):
         
@@ -346,42 +352,54 @@
             # update_tree invoque dynamiquement la valeur de l'option(`GLOBAL_VIEW`) courante
             self.update_tree_contents(self._copy_l1doctests)
             # on restaure la valeur initiale de l'option ??!
             # set_option(GLOBAL_VIEW, initial_val)
     
     def remove_error_details(self):
         if self.treeview.get_children():
-            should_report = get_option(EXCEPTION_DETAIL)
-            set_option(EXCEPTION_DETAIL, not should_report)
-            if not should_report:
+            keep_excp_details:bool = get_option(EXCEPTION_DETAIL)
+            if keep_excp_details:
                 error_view:L1TestErrorView = self.workbench.get_view(L1TestErrorView.__name__)
                 error_view.clear()
                 error_view.hide_view()
+            set_option(EXCEPTION_DETAIL, not keep_excp_details)
             self.update_tree_contents(self._copy_l1doctests)
-            
-    def reduce_space_between_rows(self):
-        all_childrens = get_all_tree_childrens(self.treeview)
-        all_texts = self.__extract_wrapped_texts(self.treeview, all_childrens)
-        max_lines = self.__get_longest_wrapped_line(all_texts)
-        current_height = self.__compute_optimal_height(max_lines, margin=0.66, padding=1.5)
-        self.style.configure("Treeview", rowheight=current_height)
+    
+    def increase_row_height(self, event):
+        if self.treeview.get_children():
+            current_height = self.get_rowheight()
+            self.style.configure("Treeview", rowheight=current_height+1)
+            self.treeview.update()
+    
+    def decrease_row_height(self, event):
+        if not self.is_empty():
+            current_height = self.get_rowheight()
+            max_lines = self.__get_longest_wrapped_line()
+            opt = self.__compute_optimal_height(max_lines, SMALL_MARGIN)
+            print("opt=", opt)
+            print("current_height=", current_height)
+            if current_height > opt:
+                self.style.configure("Treeview", rowheight=current_height-1) 
+                self.treeview.update()
         
+    def get_rowheight(self):
+        return self.style.lookup("Treeview", 'rowheight')
     # -------------------------------------------
     # Fin des fonction pour le Header du treeview
-    # -------------------------------------------
+    # ------------------------------------------
     
     def __observe_font_changing(self, event=None, rowheight=ROW_HEIGHT):
         """
             Changes the font of the treeview.
         """
         self.__update_tree_font(get_font_family_option(), 
                                 get_font_size_option(), 
                                 rowheight=rowheight)
-        #self.header_bar.config(font=(get_font_family_option(), 
-        #                             get_font_size_option()))
+        self.header_bar.config(font=(get_font_family_option(), 
+                                     get_font_size_option()))
         return "break"
     
     def __update_tree_font(self, font_family, font_size, rowheight=ROW_HEIGHT):
         """
             Applies the new font to the treeview.
         """
         self.style.configure("Treeview", 
@@ -394,83 +412,90 @@
         """
             This function wraps the text of treeview to follow its width.
         """
         widget = event.widget if event else tree
         
         if (isinstance(widget, ttk.Treeview)): 
             if (self.workbench.get_view(self.__class__.__name__).winfo_ismapped()):  
-                if not self.is_treeview_cleared():
+                if not self.is_empty():
                     width = widget.winfo_width()
                     
                     # Une heuristique a été fait pour décider du nombre de caractères par 100 pixels.
                     chars_per_100_pixels = width // (get_font_size_option())
                     
-                    all_childrens = get_all_tree_childrens(self.treeview)
-                    for iid in all_childrens:
+                    childs = get_all_tree_childrens(self.treeview)
+                    for iid in childs:
                         text = widget.item(iid)["text"]
                         wrapped = wrap(text, chars_per_100_pixels)   
                         tree.item(iid, text=wrapped)
-                    # il faut changer la hauteur des rows pour afficher tout le texte
-                    new_height = self.get_optimal_row_height(widget, all_childrens)
-                    self.style.configure("Treeview", rowheight=new_height)
+                    self.reduce_row_spaces(childs, NORMAL_MARGIN) 
+        
+    def reduce_row_spaces(self, childs, margin=NORMAL_MARGIN):
+        all_texts = self.__extract_wrapped_texts(childs)
+        max_lines = self.__get_longest_wrapped_line(all_texts)
+        opt_height = self.__compute_optimal_height(max_lines, margin)
+        self.style.configure("Treeview", rowheight=opt_height)
+        self.treeview.update()                
     
-    def __extract_wrapped_texts(self, widget: ttk.Treeview, all_childrens:list):
+    def __extract_wrapped_texts(self, childs:list):
         """
             Returns a list containing all the wrapped texts of all nodes of the treeview.
         """
-        return [widget.item(iid)["text"] for iid in all_childrens]
+        return [self.treeview.item(iid)["text"] for iid in childs]
     
-    def get_optimal_row_height(self, widget: ttk.Treeview, all_childrens:list):
+    def get_optimal_row_height(self, childs:list):
         """
             Returns the new optimal height.
         """
-        all_texts = self.__extract_wrapped_texts(widget, all_childrens)
+        all_texts = self.__extract_wrapped_texts(childs)
         
         # Quand le contenu est wrappé, on ajuste la hauteur des lignes, 
         # pour s'assurer que tout le contenu d'une ligne est affichée
         max_lines = self.__get_longest_wrapped_line(all_texts)
         return self.__compute_optimal_height(max_lines)        
         
-    def __get_longest_wrapped_line(self, all_texts:list[str]):
+    def __get_longest_wrapped_line(self, all_texts:list[str]=None):
         """
-            Returns the longest wrapped text in the treeview.
+            Returns the size of the longest wrapped text in the treeview.
         """ 
+        if not all_texts:
+            childs = get_all_tree_childrens(self.treeview)
+            all_texts = self.__extract_wrapped_texts(childs)
         sizes:list = [len(text.split("\n")) for text in all_texts]
         return max(sizes) if sizes else 1
     
-    def __compute_optimal_height(self, max_lines:int=None, margin=0.8, padding=1.55):
+    def __compute_optimal_height(self, max_lines:int=None, margin=NORMAL_MARGIN):
         """
             Uses the default font metrics to calculate the optimal row height.
             The default font metrics is multiplied by the given `max_lines`.
             
             The algorithm uses heuristics to calculate the optimal height by eliminating 
             unnecessary padding between rows of the tree as much as possible. 
             
             Args:
                 max_lines(int): The number of lines of the longest row in the treeview.
             Return:
                 (int): The new height.
         """
-        default_font = tk_font.nametofont("TkDefaultFont")
-        font_size = round(default_font.metrics("linespace") * padding) * margin 
-        lines_per_row = max_lines * font_size if max_lines else font_size
-        return round(lines_per_row)
+        row_height = get_font_size_option() * 2     # multiply by 2 to handle the line spacing
+        opt_height = max_lines * (row_height * margin) if max_lines else row_height
+        return round(opt_height)
     
     def update_tree_contents(self, l1doctests:List[L1DocTest], parent="", full_clear=True):
         """
             This function contructs and inserts the rows into the treeview.
         """
         def __update_tree_header__():            
             # We build the summarize object 
             summarize: Summarize = self.build_summarize_object(self._origin_l1doctests)
             # We insert the summarize infos into the header bar of the treeview
             self.insert_summarize_in_header_bar(summarize, self.header_bar)
             self.resize_header_bar()
         
-        self._show_highlight_selection_effect()   
+        self._restore_row_selection_effect()  
         self.clear_tree(clear_all=full_clear)
    
         if not self.__check_if_editor_is_open():
             return
 
         self.__add_verdicts_to_treeview(l1doctests, parent)
         
@@ -494,15 +519,15 @@
     def _add_node_to_tree(self, l1doctest: L1DocTest, parent=""):      
         self.__update_tree_font(get_font_family_option(), get_font_size_option())
                 
         flag: L1DocTestFlag = l1doctest.get_flag()
         verdict_config = dict(text=self._get_l1doctest_stats(l1doctest), 
                               image=self.get_icon(flag.name), 
                               open=get_option(GLOBAL_VIEW) if flag == L1DocTestFlag.FAILED_FLAG else False)
-        return self.treeview.insert(parent, "end", values=l1doctest.get_node_lineno(), tags=(clickable_tag, ), **verdict_config)
+        return self.treeview.insert(parent, "end", values=l1doctest.get_node_lineno(), tags=(clickable_tag,), **verdict_config)
     
     def _add_verdicts_to_node(self, current_node:str, examples:list[Example]):
         """ 
         This function adds to the treeview all the rows that correspond 
         to the given ast node.
         """
         def __add_as_many_rows_as_text_lines(parent, text:str, lineno:int, tags:str):
@@ -651,85 +676,71 @@
         """Clears the header of the treeview."""
         if self.header_bar:
             self.header_bar.direct_delete("1.0", "end")
             self.resize_header_bar()
     
     def _remove_highlight_selection_effect(self, event=None):
         """
-            This function remove the selection effect. When a treeview's row is selected
-            it removes the highlight effect on the selected row. So the selected row 
-            will look like it is not selected.
+        This function remove the selection effect. When a treeview's row is selected
+        it removes the highlight effect on the selected row. So the selected row 
+        will look like it is not selected.
         """
         self.style.map('Treeview', background=[], foreground=[])
     
-    def _show_highlight_selection_effect(self):
+    def _highlight_line_on_editor(self, lineno:int, editor: CodeView):
+        """Highlights the line in the editor that corresponds to the selected row in the treeview.
+
+        Args:
+            lineno (int): the line number to highlight.
+            editor (CodeView): the editor where the line will be highlighted.
+        """
+        index = editor.text.index(str(lineno) + ".0")
+        editor.text.see(index)  # make sure that the double-clicked item is visible
+        editor.text.select_lines(lineno, lineno)
+    
+    def _restore_row_selection_effect(self):
         """
-            This function show the selection effect. When a treeview's row is selected
-            it shows the highlight effect on the selected row. 
+        This function show the selection effect. When a treeview's row is selected
+        it shows the highlight effect on the selected row. 
         """
         self.style.map('Treeview', 
-                       background=[('selected', 'focus', '#ADD8E6'), ('selected', '!focus', '#ADD8E6')], 
+                       background=[('selected', 'focus', '#ADD8E6'), ('selected', '!focus', '#D3D3D3')], 
                        foreground=[('selected', 'focus', 'black'), ('selected', '!focus', 'black')])
+
     
-    def _highlight_line_on_editor(self, lineno, editor: CodeView):
-        index = editor.text.index(str(lineno) + ".0")
-        editor.text.see(index)  # make sure that the double-clicked item is visible
-        editor.text.select_lines(lineno, lineno)
-        
     def _on_select(self, event):
         """
-            When a row is selected this function will be triggered. This function highlights 
-            the line in the editor that corresponds to the seelcted row in the treeview. 
+        When a row is selected this function will be triggered. This function highlights 
+        the line in the editor that corresponds to the seelcted row in the treeview. 
         """
+        self._restore_row_selection_effect()
         editor = self.workbench.get_editor_notebook().get_current_editor()
-        self._show_highlight_selection_effect()
         if editor:
             code_view = editor.get_code_view()
             focus = self.treeview.focus()
             if not focus: 
                 return
 
             item = self.treeview.item(focus)
             values = item["values"]
             if not values:
                 return
-            
-            if focus == self.selected_item:
-                # Item is already selected, so toggle the selection state
-                if self.treeview.selection():
-                    self.selected_item = None
-                    self._remove_highlight_selection_effect()
-                    self._highlight_line_on_editor(-1, code_view)
-                    if get_option(EXCEPTION_DETAIL):
-                        self.workbench.event_generate(L1TREE_VIEW_EVENT, exception_details=False)
-                else:
-                    self._show_highlight_selection_effect()
-            else:
-                # Item is not selected, so select it and remove the previous selection
-                if self.selected_item:
-                    self.selected_item = None
-                    self._remove_highlight_selection_effect()
-                    self._highlight_line_on_editor(-1, code_view)
-                    if get_option(EXCEPTION_DETAIL):
-                        self.workbench.event_generate(L1TREE_VIEW_EVENT, exception_details=False)
-                
-                self._show_highlight_selection_effect()
-                self.selected_item = focus 
                 
-                if get_option(EXCEPTION_DETAIL): 
-                    if ExceptionVerdict.__name__ in values:
-                        self.workbench.event_generate(L1TREE_VIEW_EVENT, exception_details=True, both=True,
-                                                    error_msg=values[-1], error_title=item["text"])
-                           
-                lineno = values[0]
-                self._highlight_line_on_editor(lineno, code_view)
-                self.workbench.event_generate(
-                    "OutlineDoubleClick", item_text=self.treeview.item(self.treeview.focus(), option="text")
-                )
-  
+            if get_option(EXCEPTION_DETAIL): 
+                if ExceptionVerdict.__name__ in values:
+                    self.workbench.event_generate(L1TREE_VIEW_EVENT, error_title=item["text"],
+                                                  error_msg=values[-1], both=True)
+                    self.treeview.focus_set()
+                        
+            lineno = values[0]
+            self._highlight_line_on_editor(lineno, code_view)
+            self.workbench.event_generate(
+                "OutlineDoubleClick", item_text=self.treeview.item(self.treeview.focus(), option="text")
+            )
+
     def disable_menu(self):
         """disable the menu button of the treeview"""
         self.menu_button.state([tk.DISABLED])
         
     def enable_menu(self):
         """enable the menu button of the treeview"""
         self.menu_button.state(["!disabled"])
@@ -750,15 +761,15 @@
             if isinstance(image, str):
                 image = self.get_icon(image)
             self.header_bar.image_create(tk.END, image=image)
             text = " " + text
         self.header_bar.direct_insert(tk.END, text, tags=tags)
         self.resize_header_bar()
            
-    def is_treeview_cleared(self):
+    def is_empty(self):
         return len(self.treeview.get_children()) == 0
     
     def is_header_bar_cleared(self): 
         return not self.header_bar.get("1.0", tk.END).strip("\n")    
     
     def hide_view(self):
         self.workbench.hide_view(self.__class__.__name__)
```

### Comparing `UpyTest-3.1.3/thonnycontrib/l1test_frontend/outlines.py` & `UpyTest-3.1.4/thonnycontrib/l1test_frontend/outlines.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/plugin_loader.py` & `UpyTest-3.1.4/thonnycontrib/plugin_loader.py`

 * *Files 0% similar despite different names*

```diff
@@ -88,15 +88,15 @@
             both = False
             l1test_runner.set_has_exception(False)
         pass # Do nothing. We don't generate anything if a selected line is not a function.
     except FrontendException as e: # parsing error
         l1test_runner.set_has_exception(True)
         error_msg, error_title = str(e), CANNOT_GENERATE_THE_DOCSTRING    
               
-    l1test_runner.show_right_view(error_msg=error_msg, error_title=error_title, both=both)           
+    l1test_runner._show_right_view(error_msg=error_msg, error_title=error_title, both=both)           
     # Cette ligne est importante pour reprendre le focus sur l'éditeur
     get_workbench().get_editor_notebook().focus_set() 
     
     del docGenerator  # destruction de l'objet en mémoire (for better performance)
     
 def _writable_text_is_focused():
     """
```

### Comparing `UpyTest-3.1.3/thonnycontrib/properties.py` & `UpyTest-3.1.4/thonnycontrib/properties.py`

 * *Files 4% similar despite different names*

```diff
@@ -36,15 +36,16 @@
 RESUME_ORIGINAL_ORDER = "Resume original order"
 GROUP_BY_VERDICTS = "Group by verdicts"
 EXPAND_TEST_RESULTS = "Expand test results"
 FOLD_TEST_RESULTS = "Fold test results"
 REMOVE_ERROR_DETAILS = "Remove error details"
 INCLUDE_ERROR_DETAILS = "Include error details"
 CLEAR_LABEL = "Clear"
-REDUCE_SPACE_BETWEEN_ROWS = "Reduce extra spaces"
+INCREASE_SPACE_BETWEEN_ROWS = "Inrease row height"
+DECREASE_SPACE_BETWEEN_ROWS = "Decrease row height"
 
 # Le message affiché sur la treeview quand `l1test` est en cours d'execution
 L1TEST_IN_PROGRESS = "Executing tests in progress ..."
 
 # the evaluation states
 PENDING_STATE = "Pending" 
 EXECUTED_STATE = "Executed"
```

### Comparing `UpyTest-3.1.3/thonnycontrib/tests/test_doc_generator.py` & `UpyTest-3.1.4/thonnycontrib/tests/test_doc_generator.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/tests/tests_example_no_expected.py` & `UpyTest-3.1.4/thonnycontrib/tests/tests_example_no_expected.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/tests/tests_example_with_exception.py` & `UpyTest-3.1.4/thonnycontrib/tests/tests_example_with_exception.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/tests/tests_example_with_expected.py` & `UpyTest-3.1.4/thonnycontrib/tests/tests_example_with_expected.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/tests/tests_l1TestRunner.py` & `UpyTest-3.1.4/thonnycontrib/tests/tests_l1TestRunner.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/tests/tests_test_finder.py` & `UpyTest-3.1.4/thonnycontrib/tests/tests_test_finder.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/tests/tests_view.py` & `UpyTest-3.1.4/thonnycontrib/tests/tests_view.py`

 * *Files identical despite different names*

### Comparing `UpyTest-3.1.3/thonnycontrib/utils.py` & `UpyTest-3.1.4/thonnycontrib/utils.py`

 * *Files 0% similar despite different names*

```diff
@@ -5,27 +5,27 @@
 from setuptools import find_packages
 from thonnycontrib.exceptions import CannotImportModuleException, CannotSelectSeveralLines, CompilationError
 from .properties import BACKEND_COMMAND 
 from .environement_vars import *
 import os, re, ast, traceback, textwrap, tkinter as tk
 import thonny
     
-def wrap(string:str, length=8, break_long_words=False, separator=os.sep):   
+def wrap(string:str, length=8, break_long_words=False):   
     """Wrap a text using the `wraptext` module.
 
     Args:
         string (str): the string to wrap.
         length (int, optional): the min length from which the string will be wrapped. Defaults to 8.
         break_long_words (bool, optional): if False the entire words will not be wrapped
                                         if the words lentgh is more that the given length. Defaults to False.
         separator (str, optional): the separator around which to wrap the filenames.
     Returns:
         str: the wrapped string.
     """
-    return '\n'.join(textwrap.wrap(string, length, break_long_words=break_long_words))
+    return '\n'.join(textwrap.wrap(string, length, break_on_hyphens=False, break_long_words=break_long_words))
 
 def get_all_tree_childrens(tree: ttk.Treeview, node=None):
     """Gets recursivly all the childrens of the given node of the treeview. 
 
     Args:
         tree (ttk.Treeview): the treeview in which the childrens will be extracted.
         node (ast.AST, optional): the starting ast node from which the recursion will
```


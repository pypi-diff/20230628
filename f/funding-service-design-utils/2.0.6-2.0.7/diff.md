# Comparing `tmp/funding-service-design-utils-2.0.6.tar.gz` & `tmp/funding-service-design-utils-2.0.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "funding-service-design-utils-2.0.6.tar", last modified: Mon Jun 19 06:05:58 2023, max compression
+gzip compressed data, was "funding-service-design-utils-2.0.7.tar", last modified: Wed Jun 28 13:41:33 2023, max compression
```

## Comparing `funding-service-design-utils-2.0.6.tar` & `funding-service-design-utils-2.0.7.tar`

### file list

```diff
@@ -1,70 +1,79 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.432068 funding-service-design-utils-2.0.6/
--rw-r--r--   0 runner    (1001) docker     (123)     1127 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16060 2023-06-19 06:05:58.432068 funding-service-design-utils-2.0.6/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14229 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.428068 funding-service-design-utils-2.0.6/fsd_test_utils/
--rw-r--r--   0 runner    (1001) docker     (123)      110 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_test_utils/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.428068 funding-service-design-utils-2.0.6/fsd_test_utils/fixtures/
--rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_test_utils/fixtures/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3468 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_test_utils/fixtures/db_fixtures.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.428068 funding-service-design-utils-2.0.6/fsd_test_utils/test_config/
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_test_utils/test_config/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      200 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_test_utils/test_config/useful_config.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.428068 funding-service-design-utils-2.0.6/fsd_utils/
--rw-r--r--   0 runner    (1001) docker     (123)      821 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.428068 funding-service-design-utils-2.0.6/fsd_utils/authentication/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/authentication/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      647 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/authentication/config.py
--rw-r--r--   0 runner    (1001) docker     (123)     5239 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/authentication/decorators.py
--rw-r--r--   0 runner    (1001) docker     (123)      964 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/authentication/models.py
--rw-r--r--   0 runner    (1001) docker     (123)      605 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/authentication/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.428068 funding-service-design-utils-2.0.6/fsd_utils/config/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/config/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5305 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/config/commonconfig.py
--rw-r--r--   0 runner    (1001) docker     (123)     1517 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/config/configclass.py
--rw-r--r--   0 runner    (1001) docker     (123)     1378 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/config/notify_constants.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.428068 funding-service-design-utils-2.0.6/fsd_utils/gunicorn/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/gunicorn/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.428068 funding-service-design-utils-2.0.6/fsd_utils/gunicorn/config/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/gunicorn/config/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7691 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/gunicorn/config/devtest.py
--rw-r--r--   0 runner    (1001) docker     (123)     7032 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/gunicorn/config/local.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.432068 funding-service-design-utils-2.0.6/fsd_utils/healthchecks/
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/healthchecks/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1230 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/healthchecks/checkers.py
--rw-r--r--   0 runner    (1001) docker     (123)     1155 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/healthchecks/healthcheck.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.432068 funding-service-design-utils-2.0.6/fsd_utils/locale_selector/
--rw-r--r--   0 runner    (1001) docker     (123)       62 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/locale_selector/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1027 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/locale_selector/get_lang.py
--rw-r--r--   0 runner    (1001) docker     (123)      940 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/locale_selector/set_lang.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.432068 funding-service-design-utils-2.0.6/fsd_utils/logging/
--rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/logging/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11900 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/logging/logging.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.432068 funding-service-design-utils-2.0.6/fsd_utils/sentry/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/sentry/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      967 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/sentry/init_sentry.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.432068 funding-service-design-utils-2.0.6/fsd_utils/simple_utils/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/simple_utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      434 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/simple_utils/data_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)      788 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/simple_utils/date_utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.432068 funding-service-design-utils-2.0.6/fsd_utils/toggles/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/toggles/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      655 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/fsd_utils/toggles/toggles.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.432068 funding-service-design-utils-2.0.6/funding_service_design_utils.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16060 2023-06-19 06:05:58.000000 funding-service-design-utils-2.0.6/funding_service_design_utils.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1654 2023-06-19 06:05:58.000000 funding-service-design-utils-2.0.6/funding_service_design_utils.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-19 06:05:58.000000 funding-service-design-utils-2.0.6/funding_service_design_utils.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      351 2023-06-19 06:05:58.000000 funding-service-design-utils-2.0.6/funding_service_design_utils.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-19 06:05:58.000000 funding-service-design-utils-2.0.6/funding_service_design_utils.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     1119 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-19 06:05:58.432068 funding-service-design-utils-2.0.6/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      228 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:58.432068 funding-service-design-utils-2.0.6/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8469 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/tests/conftest.py
--rw-r--r--   0 runner    (1001) docker     (123)    11292 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/tests/test_authentication.py
--rw-r--r--   0 runner    (1001) docker     (123)     2425 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/tests/test_checkers.py
--rw-r--r--   0 runner    (1001) docker     (123)      563 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/tests/test_data_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     1502 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/tests/test_get_lang.py
--rw-r--r--   0 runner    (1001) docker     (123)     3564 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/tests/test_healthcheck.py
--rw-r--r--   0 runner    (1001) docker     (123)      628 2023-06-19 06:05:44.000000 funding-service-design-utils-2.0.6/tests/test_set_lang.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.321271 funding-service-design-utils-2.0.7/
+-rw-r--r--   0 runner    (1001) docker     (123)     1127 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17295 2023-06-28 13:41:33.321271 funding-service-design-utils-2.0.7/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15464 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.317271 funding-service-design-utils-2.0.7/fsd_test_utils/
+-rw-r--r--   0 runner    (1001) docker     (123)      110 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_test_utils/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.317271 funding-service-design-utils-2.0.7/fsd_test_utils/fixtures/
+-rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_test_utils/fixtures/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3468 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_test_utils/fixtures/db_fixtures.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.317271 funding-service-design-utils-2.0.7/fsd_test_utils/test_config/
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_test_utils/test_config/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      200 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_test_utils/test_config/useful_config.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.317271 funding-service-design-utils-2.0.7/fsd_utils/
+-rw-r--r--   0 runner    (1001) docker     (123)     1071 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.317271 funding-service-design-utils-2.0.7/fsd_utils/authentication/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/authentication/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      647 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/authentication/config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5239 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/authentication/decorators.py
+-rw-r--r--   0 runner    (1001) docker     (123)      964 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/authentication/models.py
+-rw-r--r--   0 runner    (1001) docker     (123)      605 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/authentication/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.317271 funding-service-design-utils-2.0.7/fsd_utils/config/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/config/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5305 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/config/commonconfig.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1517 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/config/configclass.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1378 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/config/notify_constants.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.317271 funding-service-design-utils-2.0.7/fsd_utils/gunicorn/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/gunicorn/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.317271 funding-service-design-utils-2.0.7/fsd_utils/gunicorn/config/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/gunicorn/config/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7691 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/gunicorn/config/devtest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7032 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/gunicorn/config/local.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.317271 funding-service-design-utils-2.0.7/fsd_utils/healthchecks/
+-rw-r--r--   0 runner    (1001) docker     (123)       65 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/healthchecks/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1230 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/healthchecks/checkers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1155 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/healthchecks/healthcheck.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.317271 funding-service-design-utils-2.0.7/fsd_utils/locale_selector/
+-rw-r--r--   0 runner    (1001) docker     (123)       62 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/locale_selector/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1027 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/locale_selector/get_lang.py
+-rw-r--r--   0 runner    (1001) docker     (123)      940 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/locale_selector/set_lang.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.321271 funding-service-design-utils-2.0.7/fsd_utils/logging/
+-rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/logging/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11900 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/logging/logging.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.321271 funding-service-design-utils-2.0.7/fsd_utils/mapping/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/mapping/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.321271 funding-service-design-utils-2.0.7/fsd_utils/mapping/application/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/mapping/application/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2865 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/mapping/application/application_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1851 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/mapping/application/free_text.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5920 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/mapping/application/multi_input.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2966 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/mapping/application/qa_mapping.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.321271 funding-service-design-utils-2.0.7/fsd_utils/sentry/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/sentry/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      967 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/sentry/init_sentry.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.321271 funding-service-design-utils-2.0.7/fsd_utils/simple_utils/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/simple_utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      434 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/simple_utils/data_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)      788 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/simple_utils/date_utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.321271 funding-service-design-utils-2.0.7/fsd_utils/toggles/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/toggles/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      655 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/fsd_utils/toggles/toggles.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.321271 funding-service-design-utils-2.0.7/funding_service_design_utils.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17295 2023-06-28 13:41:33.000000 funding-service-design-utils-2.0.7/funding_service_design_utils.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1943 2023-06-28 13:41:33.000000 funding-service-design-utils-2.0.7/funding_service_design_utils.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:41:33.000000 funding-service-design-utils-2.0.7/funding_service_design_utils.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      351 2023-06-28 13:41:33.000000 funding-service-design-utils-2.0.7/funding_service_design_utils.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 13:41:33.000000 funding-service-design-utils-2.0.7/funding_service_design_utils.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     1119 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 13:41:33.321271 funding-service-design-utils-2.0.7/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      228 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:33.321271 funding-service-design-utils-2.0.7/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8559 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/tests/conftest.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11292 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/tests/test_authentication.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2425 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/tests/test_checkers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6073 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/tests/test_data_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1502 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/tests/test_get_lang.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3564 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/tests/test_healthcheck.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6141 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/tests/test_mapping_application.py
+-rw-r--r--   0 runner    (1001) docker     (123)      628 2023-06-28 13:41:18.000000 funding-service-design-utils-2.0.7/tests/test_set_lang.py
```

### Comparing `funding-service-design-utils-2.0.6/LICENSE` & `funding-service-design-utils-2.0.7/LICENSE`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/PKG-INFO` & `funding-service-design-utils-2.0.7/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: funding-service-design-utils
-Version: 2.0.6
+Version: 2.0.7
 Summary: Utilities used by the DLUHC Funding Service Design Team
 Author-email: DLUHC <FundingServiceDesignTeam@levellingup.gov.uk>
 License: MIT License
         
         Copyright (c) 2022 Crown Copyright (Department for Levelling Up, Housing and Communities)
         
         Permission is hereby granted, free of charge, to any person obtaining a copy
@@ -74,16 +74,38 @@
 To reference a particular tag from pip, add the following to your `requirements.txt` file or use `pip install` (update version as appropriate):
 
     funding-service-design-utils==0.0.1
 
 ## Latest / in-dev version
 To reference the latest commit from a particular branch from pip, add the following to your `requirements.txt` file or use `pip install`:
 
+pip install
+
+    pip install git+https://github.com/communitiesuk/funding-service-design-utils.git@<branchName>
+
+**or**
+
+To navigate requirements.txt to your branch:
+
+Replace `funding-service-design-utils` in `requirements.in` with
+
     git+https://github.com/communitiesuk/funding-service-design-utils.git@<branchName>
 
+Build requirements with following commands
+
+    pip-compile requirements.in
+    pip-compile requirements-dev.in
+    python3 -m pip install --upgrade pip && pip install -r requirements-dev.txt
+
+Build docker with following commands
+
+    docker compose build <service_name> --no-cache
+    or
+    docker compose build --no-cache
+
 ## Local changes
 When working and testing locally, you can also install the `fsd_utils` package from your local filesystem:
 
     pip uninstall -y funding-service-design-utils
     pip install /path/to/your/working/directory/funding-service-design/utils
 
 Note: When testing locally using the docker runner, docker might use the cached version of fsd_utils. to avoid this and pick up your intended changes, run `docker compose build <service_name> --no-cache` first before running `docker compose up`.
@@ -349,7 +371,24 @@
 **Note**: Not intended to be used as a default for tests as it can lead to test pollution, so only use to debug and then remove again.
 #### _db
 Provides direct access to the database for tests. Useful if your test needs to explicitly insert/update records to prepare test data.
 #### recreate_db
 This fixture reads the pytest cache to determine whether the DB can be reused for this test run and then the db is recreated accordingly. Updates the cache value to enable reuse of the DB for future test runs. This is session scoped so the DB is not recreated for each test in a run.
 
 This is requested by `clear_test_data` so you do not need to include it separately in your project if using that fixture.
+
+
+
+## Mapping
+
+The mapping feature serves the purpose of mapping and formatting the questions and answers of the application into a text file. This functionality is utilised in the following scenarios:
+
+- Within the assessment service, it facilitates the downloading of the application's questions and answers.
+- In the notification service, it enables the posting of the applicant's application answer.
+
+To accomplish the mapping of the application's questions and answers, import
+
+    from fsd_utils import extract_questions_and_answers
+
+To format the questions and answers of the application into a text file, import
+
+    from fsd_utils import generate_text_of_application
```

### Comparing `funding-service-design-utils-2.0.6/README.md` & `funding-service-design-utils-2.0.7/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -39,16 +39,38 @@
 To reference a particular tag from pip, add the following to your `requirements.txt` file or use `pip install` (update version as appropriate):
 
     funding-service-design-utils==0.0.1
 
 ## Latest / in-dev version
 To reference the latest commit from a particular branch from pip, add the following to your `requirements.txt` file or use `pip install`:
 
+pip install
+
+    pip install git+https://github.com/communitiesuk/funding-service-design-utils.git@<branchName>
+
+**or**
+
+To navigate requirements.txt to your branch:
+
+Replace `funding-service-design-utils` in `requirements.in` with
+
     git+https://github.com/communitiesuk/funding-service-design-utils.git@<branchName>
 
+Build requirements with following commands
+
+    pip-compile requirements.in
+    pip-compile requirements-dev.in
+    python3 -m pip install --upgrade pip && pip install -r requirements-dev.txt
+
+Build docker with following commands
+
+    docker compose build <service_name> --no-cache
+    or
+    docker compose build --no-cache
+
 ## Local changes
 When working and testing locally, you can also install the `fsd_utils` package from your local filesystem:
 
     pip uninstall -y funding-service-design-utils
     pip install /path/to/your/working/directory/funding-service-design/utils
 
 Note: When testing locally using the docker runner, docker might use the cached version of fsd_utils. to avoid this and pick up your intended changes, run `docker compose build <service_name> --no-cache` first before running `docker compose up`.
@@ -314,7 +336,24 @@
 **Note**: Not intended to be used as a default for tests as it can lead to test pollution, so only use to debug and then remove again.
 #### _db
 Provides direct access to the database for tests. Useful if your test needs to explicitly insert/update records to prepare test data.
 #### recreate_db
 This fixture reads the pytest cache to determine whether the DB can be reused for this test run and then the db is recreated accordingly. Updates the cache value to enable reuse of the DB for future test runs. This is session scoped so the DB is not recreated for each test in a run.
 
 This is requested by `clear_test_data` so you do not need to include it separately in your project if using that fixture.
+
+
+
+## Mapping
+
+The mapping feature serves the purpose of mapping and formatting the questions and answers of the application into a text file. This functionality is utilised in the following scenarios:
+
+- Within the assessment service, it facilitates the downloading of the application's questions and answers.
+- In the notification service, it enables the posting of the applicant's application answer.
+
+To accomplish the mapping of the application's questions and answers, import
+
+    from fsd_utils import extract_questions_and_answers
+
+To format the questions and answers of the application into a text file, import
+
+    from fsd_utils import generate_text_of_application
```

### Comparing `funding-service-design-utils-2.0.6/fsd_test_utils/fixtures/db_fixtures.py` & `funding-service-design-utils-2.0.7/fsd_test_utils/fixtures/db_fixtures.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/authentication/config.py` & `funding-service-design-utils-2.0.7/fsd_utils/authentication/config.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/authentication/decorators.py` & `funding-service-design-utils-2.0.7/fsd_utils/authentication/decorators.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/authentication/models.py` & `funding-service-design-utils-2.0.7/fsd_utils/authentication/models.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/authentication/utils.py` & `funding-service-design-utils-2.0.7/fsd_utils/authentication/utils.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/config/commonconfig.py` & `funding-service-design-utils-2.0.7/fsd_utils/config/commonconfig.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/config/configclass.py` & `funding-service-design-utils-2.0.7/fsd_utils/config/configclass.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/config/notify_constants.py` & `funding-service-design-utils-2.0.7/fsd_utils/config/notify_constants.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/gunicorn/config/devtest.py` & `funding-service-design-utils-2.0.7/fsd_utils/gunicorn/config/devtest.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/gunicorn/config/local.py` & `funding-service-design-utils-2.0.7/fsd_utils/gunicorn/config/local.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/healthchecks/checkers.py` & `funding-service-design-utils-2.0.7/fsd_utils/healthchecks/checkers.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/healthchecks/healthcheck.py` & `funding-service-design-utils-2.0.7/fsd_utils/healthchecks/healthcheck.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/locale_selector/get_lang.py` & `funding-service-design-utils-2.0.7/fsd_utils/locale_selector/get_lang.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/locale_selector/set_lang.py` & `funding-service-design-utils-2.0.7/fsd_utils/locale_selector/set_lang.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/logging/logging.py` & `funding-service-design-utils-2.0.7/fsd_utils/logging/logging.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/sentry/init_sentry.py` & `funding-service-design-utils-2.0.7/fsd_utils/sentry/init_sentry.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/simple_utils/date_utils.py` & `funding-service-design-utils-2.0.7/fsd_utils/simple_utils/date_utils.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/fsd_utils/toggles/toggles.py` & `funding-service-design-utils-2.0.7/fsd_utils/toggles/toggles.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/funding_service_design_utils.egg-info/PKG-INFO` & `funding-service-design-utils-2.0.7/funding_service_design_utils.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: funding-service-design-utils
-Version: 2.0.6
+Version: 2.0.7
 Summary: Utilities used by the DLUHC Funding Service Design Team
 Author-email: DLUHC <FundingServiceDesignTeam@levellingup.gov.uk>
 License: MIT License
         
         Copyright (c) 2022 Crown Copyright (Department for Levelling Up, Housing and Communities)
         
         Permission is hereby granted, free of charge, to any person obtaining a copy
@@ -74,16 +74,38 @@
 To reference a particular tag from pip, add the following to your `requirements.txt` file or use `pip install` (update version as appropriate):
 
     funding-service-design-utils==0.0.1
 
 ## Latest / in-dev version
 To reference the latest commit from a particular branch from pip, add the following to your `requirements.txt` file or use `pip install`:
 
+pip install
+
+    pip install git+https://github.com/communitiesuk/funding-service-design-utils.git@<branchName>
+
+**or**
+
+To navigate requirements.txt to your branch:
+
+Replace `funding-service-design-utils` in `requirements.in` with
+
     git+https://github.com/communitiesuk/funding-service-design-utils.git@<branchName>
 
+Build requirements with following commands
+
+    pip-compile requirements.in
+    pip-compile requirements-dev.in
+    python3 -m pip install --upgrade pip && pip install -r requirements-dev.txt
+
+Build docker with following commands
+
+    docker compose build <service_name> --no-cache
+    or
+    docker compose build --no-cache
+
 ## Local changes
 When working and testing locally, you can also install the `fsd_utils` package from your local filesystem:
 
     pip uninstall -y funding-service-design-utils
     pip install /path/to/your/working/directory/funding-service-design/utils
 
 Note: When testing locally using the docker runner, docker might use the cached version of fsd_utils. to avoid this and pick up your intended changes, run `docker compose build <service_name> --no-cache` first before running `docker compose up`.
@@ -349,7 +371,24 @@
 **Note**: Not intended to be used as a default for tests as it can lead to test pollution, so only use to debug and then remove again.
 #### _db
 Provides direct access to the database for tests. Useful if your test needs to explicitly insert/update records to prepare test data.
 #### recreate_db
 This fixture reads the pytest cache to determine whether the DB can be reused for this test run and then the db is recreated accordingly. Updates the cache value to enable reuse of the DB for future test runs. This is session scoped so the DB is not recreated for each test in a run.
 
 This is requested by `clear_test_data` so you do not need to include it separately in your project if using that fixture.
+
+
+
+## Mapping
+
+The mapping feature serves the purpose of mapping and formatting the questions and answers of the application into a text file. This functionality is utilised in the following scenarios:
+
+- Within the assessment service, it facilitates the downloading of the application's questions and answers.
+- In the notification service, it enables the posting of the applicant's application answer.
+
+To accomplish the mapping of the application's questions and answers, import
+
+    from fsd_utils import extract_questions_and_answers
+
+To format the questions and answers of the application into a text file, import
+
+    from fsd_utils import generate_text_of_application
```

### Comparing `funding-service-design-utils-2.0.6/funding_service_design_utils.egg-info/SOURCES.txt` & `funding-service-design-utils-2.0.7/funding_service_design_utils.egg-info/SOURCES.txt`

 * *Files 17% similar despite different names*

```diff
@@ -25,14 +25,20 @@
 fsd_utils/healthchecks/checkers.py
 fsd_utils/healthchecks/healthcheck.py
 fsd_utils/locale_selector/__init__.py
 fsd_utils/locale_selector/get_lang.py
 fsd_utils/locale_selector/set_lang.py
 fsd_utils/logging/__init__.py
 fsd_utils/logging/logging.py
+fsd_utils/mapping/__init__.py
+fsd_utils/mapping/application/__init__.py
+fsd_utils/mapping/application/application_utils.py
+fsd_utils/mapping/application/free_text.py
+fsd_utils/mapping/application/multi_input.py
+fsd_utils/mapping/application/qa_mapping.py
 fsd_utils/sentry/__init__.py
 fsd_utils/sentry/init_sentry.py
 fsd_utils/simple_utils/__init__.py
 fsd_utils/simple_utils/data_utils.py
 fsd_utils/simple_utils/date_utils.py
 fsd_utils/toggles/__init__.py
 fsd_utils/toggles/toggles.py
@@ -44,8 +50,9 @@
 tests/__init__.py
 tests/conftest.py
 tests/test_authentication.py
 tests/test_checkers.py
 tests/test_data_utils.py
 tests/test_get_lang.py
 tests/test_healthcheck.py
+tests/test_mapping_application.py
 tests/test_set_lang.py
```

### Comparing `funding-service-design-utils-2.0.6/pyproject.toml` & `funding-service-design-utils-2.0.7/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools>=61.0"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "funding-service-design-utils"
-version = "2.0.6"
+version = "2.0.7"
 authors = [
   { name="DLUHC", email="FundingServiceDesignTeam@levellingup.gov.uk" },
 ]
 description = "Utilities used by the DLUHC Funding Service Design Team"
 readme = "README.md"
 license = { file="LICENSE" }
 requires-python = ">=3.10,<4.0"
```

### Comparing `funding-service-design-utils-2.0.6/tests/conftest.py` & `funding-service-design-utils-2.0.7/tests/conftest.py`

 * *Files 2% similar despite different names*

```diff
@@ -12,14 +12,20 @@
 
 
 def create_app():
     app = Flask("test")
     return app
 
 
+@pytest.fixture()
+def app_context():
+    with create_app().app_context():
+        yield
+
+
 @pytest.fixture(scope="function")
 def flask_test_client():
     """
     Creates the test client we will be using to test the responses
     from our app, this is a test fixture.
     :return: A flask test client.
     """
```

### Comparing `funding-service-design-utils-2.0.6/tests/test_authentication.py` & `funding-service-design-utils-2.0.7/tests/test_authentication.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/tests/test_checkers.py` & `funding-service-design-utils-2.0.7/tests/test_checkers.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/tests/test_get_lang.py` & `funding-service-design-utils-2.0.7/tests/test_get_lang.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/tests/test_healthcheck.py` & `funding-service-design-utils-2.0.7/tests/test_healthcheck.py`

 * *Files identical despite different names*

### Comparing `funding-service-design-utils-2.0.6/tests/test_set_lang.py` & `funding-service-design-utils-2.0.7/tests/test_set_lang.py`

 * *Files identical despite different names*


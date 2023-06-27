# Comparing `tmp/aiobotocore-2.5.0.tar.gz` & `tmp/aiobotocore-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "aiobotocore-2.5.0.tar", last modified: Tue Mar  7 04:10:00 2023, max compression
+gzip compressed data, was "aiobotocore-2.5.1.tar", last modified: Tue Jun 27 23:46:23 2023, max compression
```

## Comparing `aiobotocore-2.5.0.tar` & `aiobotocore-2.5.1.tar`

### file list

```diff
@@ -1,65 +1,65 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-07 04:10:00.301729 aiobotocore-2.5.0/
--rw-r--r--   0 runner    (1001) docker     (123)    10352 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/CHANGES.rst
--rw-r--r--   0 runner    (1001) docker     (123)    11516 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      100 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)    19182 2023-03-07 04:10:00.301729 aiobotocore-2.5.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     7816 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/README.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-07 04:10:00.297729 aiobotocore-2.5.0/aiobotocore/
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1010 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/_endpoint_helpers.py
--rw-r--r--   0 runner    (1001) docker     (123)      501 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/_helpers.py
--rw-r--r--   0 runner    (1001) docker     (123)     6389 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/args.py
--rw-r--r--   0 runner    (1001) docker     (123)      813 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/awsrequest.py
--rw-r--r--   0 runner    (1001) docker     (123)    22741 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     2653 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/config.py
--rw-r--r--   0 runner    (1001) docker     (123)     1509 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/configprovider.py
--rw-r--r--   0 runner    (1001) docker     (123)    38986 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/credentials.py
--rw-r--r--   0 runner    (1001) docker     (123)     3613 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/discovery.py
--rw-r--r--   0 runner    (1001) docker     (123)    12100 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/endpoint.py
--rw-r--r--   0 runner    (1001) docker     (123)     1252 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/eventstream.py
--rw-r--r--   0 runner    (1001) docker     (123)     4500 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/handlers.py
--rw-r--r--   0 runner    (1001) docker     (123)     3338 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/hooks.py
--rw-r--r--   0 runner    (1001) docker     (123)     5540 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/httpchecksum.py
--rw-r--r--   0 runner    (1001) docker     (123)     9302 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/httpsession.py
--rw-r--r--   0 runner    (1001) docker     (123)     8030 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/paginate.py
--rw-r--r--   0 runner    (1001) docker     (123)     4902 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/parsers.py
--rw-r--r--   0 runner    (1001) docker     (123)     4002 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/regions.py
--rw-r--r--   0 runner    (1001) docker     (123)     5527 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/response.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-07 04:10:00.297729 aiobotocore-2.5.0/aiobotocore/retries/
--rw-r--r--   0 runner    (1001) docker     (123)     3573 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/retries/adaptive.py
--rw-r--r--   0 runner    (1001) docker     (123)     4298 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/retries/bucket.py
--rw-r--r--   0 runner    (1001) docker     (123)      861 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/retries/special.py
--rw-r--r--   0 runner    (1001) docker     (123)     3838 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/retries/standard.py
--rw-r--r--   0 runner    (1001) docker     (123)     7961 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/retryhandler.py
--rw-r--r--   0 runner    (1001) docker     (123)     8324 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/session.py
--rw-r--r--   0 runner    (1001) docker     (123)    13736 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/signers.py
--rw-r--r--   0 runner    (1001) docker     (123)     5696 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/tokens.py
--rw-r--r--   0 runner    (1001) docker     (123)    24940 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     5153 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/aiobotocore/waiter.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-07 04:10:00.297729 aiobotocore-2.5.0/aiobotocore.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19182 2023-03-07 04:10:00.000000 aiobotocore-2.5.0/aiobotocore.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1366 2023-03-07 04:10:00.000000 aiobotocore-2.5.0/aiobotocore.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-07 04:10:00.000000 aiobotocore-2.5.0/aiobotocore.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      145 2023-03-07 04:10:00.000000 aiobotocore-2.5.0/aiobotocore.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       12 2023-03-07 04:10:00.000000 aiobotocore-2.5.0/aiobotocore.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      167 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-07 04:10:00.301729 aiobotocore-2.5.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2280 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-07 04:10:00.301729 aiobotocore-2.5.0/tests/
--rw-r--r--   0 runner    (1001) docker     (123)     8185 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_adaptive.py
--rw-r--r--   0 runner    (1001) docker     (123)    21734 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_basic_s3.py
--rw-r--r--   0 runner    (1001) docker     (123)      190 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_batch.py
--rw-r--r--   0 runner    (1001) docker     (123)     3853 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     4332 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_dynamodb.py
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_ec2.py
--rw-r--r--   0 runner    (1001) docker     (123)     3054 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_eventstreams.py
--rw-r--r--   0 runner    (1001) docker     (123)     2056 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_lambda.py
--rw-r--r--   0 runner    (1001) docker     (123)      791 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_monitor.py
--rw-r--r--   0 runner    (1001) docker     (123)     1256 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_mturk.py
--rw-r--r--   0 runner    (1001) docker     (123)    26368 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_patches.py
--rw-r--r--   0 runner    (1001) docker     (123)     5673 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_response.py
--rw-r--r--   0 runner    (1001) docker     (123)     1383 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_session.py
--rw-r--r--   0 runner    (1001) docker     (123)     3697 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_sns.py
--rw-r--r--   0 runner    (1001) docker     (123)     2176 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_sqs.py
--rw-r--r--   0 runner    (1001) docker     (123)     6030 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_version.py
--rw-r--r--   0 runner    (1001) docker     (123)      708 2023-03-07 04:09:57.000000 aiobotocore-2.5.0/tests/test_waiter.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:46:23.716825 aiobotocore-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)    10419 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/CHANGES.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    11516 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      100 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)    19300 2023-06-27 23:46:23.716825 aiobotocore-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     7816 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/README.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:46:23.712825 aiobotocore-2.5.1/aiobotocore/
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1010 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/_endpoint_helpers.py
+-rw-r--r--   0 runner    (1001) docker     (123)      501 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/_helpers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6389 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/args.py
+-rw-r--r--   0 runner    (1001) docker     (123)      813 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/awsrequest.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22830 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2653 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1509 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/configprovider.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38986 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/credentials.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3613 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/discovery.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12100 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/endpoint.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1252 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/eventstream.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4500 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/handlers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3338 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/hooks.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5540 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/httpchecksum.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9302 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/httpsession.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8030 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/paginate.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4902 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/parsers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4002 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/regions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5527 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/response.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:46:23.716825 aiobotocore-2.5.1/aiobotocore/retries/
+-rw-r--r--   0 runner    (1001) docker     (123)     3573 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/retries/adaptive.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4298 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/retries/bucket.py
+-rw-r--r--   0 runner    (1001) docker     (123)      861 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/retries/special.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3838 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/retries/standard.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7961 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/retryhandler.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8324 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/session.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13998 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/signers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5696 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/tokens.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24940 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5153 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/aiobotocore/waiter.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:46:23.716825 aiobotocore-2.5.1/aiobotocore.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19300 2023-06-27 23:46:23.000000 aiobotocore-2.5.1/aiobotocore.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1366 2023-06-27 23:46:23.000000 aiobotocore-2.5.1/aiobotocore.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 23:46:23.000000 aiobotocore-2.5.1/aiobotocore.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      172 2023-06-27 23:46:23.000000 aiobotocore-2.5.1/aiobotocore.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-27 23:46:23.000000 aiobotocore-2.5.1/aiobotocore.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      167 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 23:46:23.716825 aiobotocore-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2358 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:46:23.716825 aiobotocore-2.5.1/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     8185 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_adaptive.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21734 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_basic_s3.py
+-rw-r--r--   0 runner    (1001) docker     (123)      190 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_batch.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3853 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4332 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_dynamodb.py
+-rw-r--r--   0 runner    (1001) docker     (123)      916 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_ec2.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3054 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_eventstreams.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2056 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_lambda.py
+-rw-r--r--   0 runner    (1001) docker     (123)      791 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_monitor.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1256 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_mturk.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26368 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_patches.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5673 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1383 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_session.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3697 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_sns.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2176 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_sqs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6030 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)      708 2023-06-27 23:46:18.000000 aiobotocore-2.5.1/tests/test_waiter.py
```

### Comparing `aiobotocore-2.5.0/CHANGES.rst` & `aiobotocore-2.5.1/CHANGES.rst`

 * *Files 0% similar despite different names*

```diff
@@ -1,9 +1,13 @@
 Changes
 -------
+2.5.1 (2023-06-27)
+^^^^^^^^^^^^^^^^^^
+* bump botocore to 1.29.161
+
 2.5.0 (2023-03-06)
 ^^^^^^^^^^^^^^^^^^
 * bump botocore to 1.29.76 (thanks @jakob-keller #999)
 
 2.4.2 (2022-12-22)
 ^^^^^^^^^^^^^^^^^^
 * fix retries (#988)
```

### Comparing `aiobotocore-2.5.0/LICENSE` & `aiobotocore-2.5.1/LICENSE`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/PKG-INFO` & `aiobotocore-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: aiobotocore
-Version: 2.5.0
+Version: 2.5.1
 Summary: Async client for aws services using botocore and aiohttp
 Home-page: https://github.com/aio-libs/aiobotocore
 Download-URL: https://pypi.python.org/pypi/aiobotocore
 Author: Nikolay Novik
 Author-email: nickolainovik@gmail.com
 License: Apache License 2.0
 Classifier: Development Status :: 4 - Beta
@@ -13,14 +13,15 @@
 Classifier: Natural Language :: English
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 Classifier: Environment :: Web Environment
 Classifier: Framework :: AsyncIO
 Requires-Python: >=3.7
 Description-Content-Type: text/x-rst
 Provides-Extra: awscli
 Provides-Extra: boto3
 License-File: LICENSE
@@ -266,14 +267,18 @@
     pip install -U 'aiobotocore[awscli,boto3]'
 
 If you only need awscli and not boto3 (or vice versa) you can just install one extra or
 the other.
 
 Changes
 -------
+2.5.1 (2023-06-27)
+^^^^^^^^^^^^^^^^^^
+* bump botocore to 1.29.161
+
 2.5.0 (2023-03-06)
 ^^^^^^^^^^^^^^^^^^
 * bump botocore to 1.29.76 (thanks @jakob-keller #999)
 
 2.4.2 (2022-12-22)
 ^^^^^^^^^^^^^^^^^^
 * fix retries (#988)
```

### Comparing `aiobotocore-2.5.0/README.rst` & `aiobotocore-2.5.1/README.rst`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/_endpoint_helpers.py` & `aiobotocore-2.5.1/aiobotocore/_endpoint_helpers.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/args.py` & `aiobotocore-2.5.1/aiobotocore/args.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/awsrequest.py` & `aiobotocore-2.5.1/aiobotocore/awsrequest.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/client.py` & `aiobotocore-2.5.1/aiobotocore/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -320,17 +320,24 @@
             )
         request_context = {
             'client_region': self.meta.region_name,
             'client_config': self.meta.config,
             'has_streaming_input': operation_model.has_streaming_input,
             'auth_type': operation_model.auth_type,
         }
-        endpoint_url, additional_headers = await self._resolve_endpoint_ruleset(  # noqa: BLK100
+        api_params = await self._emit_api_params(
+            api_params=api_params,
+            operation_model=operation_model,
+            context=request_context,
+        )
+        # fmt: off
+        endpoint_url, additional_headers = await self._resolve_endpoint_ruleset(
             operation_model, api_params, request_context
         )
+        # fmt: on
         request_dict = await self._convert_to_request_dict(
             api_params=api_params,
             operation_model=operation_model,
             endpoint_url=endpoint_url,
             context=request_context,
             headers=additional_headers,
         )
@@ -395,17 +402,14 @@
         api_params,
         operation_model,
         endpoint_url,
         context=None,
         headers=None,
         set_user_agent_header=True,
     ):
-        api_params = await self._emit_api_params(
-            api_params, operation_model, context
-        )
         request_dict = self._serializer.serialize_to_request(
             api_params, operation_model
         )
         if not self._client_config.inject_host_prefix:
             request_dict.pop('host_prefix', None)
         if headers is not None:
             request_dict['headers'].update(headers)
```

### Comparing `aiobotocore-2.5.0/aiobotocore/config.py` & `aiobotocore-2.5.1/aiobotocore/config.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/configprovider.py` & `aiobotocore-2.5.1/aiobotocore/configprovider.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/credentials.py` & `aiobotocore-2.5.1/aiobotocore/credentials.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/discovery.py` & `aiobotocore-2.5.1/aiobotocore/discovery.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/endpoint.py` & `aiobotocore-2.5.1/aiobotocore/endpoint.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/eventstream.py` & `aiobotocore-2.5.1/aiobotocore/eventstream.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/handlers.py` & `aiobotocore-2.5.1/aiobotocore/handlers.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/hooks.py` & `aiobotocore-2.5.1/aiobotocore/hooks.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/httpchecksum.py` & `aiobotocore-2.5.1/aiobotocore/httpchecksum.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/httpsession.py` & `aiobotocore-2.5.1/aiobotocore/httpsession.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/paginate.py` & `aiobotocore-2.5.1/aiobotocore/paginate.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/parsers.py` & `aiobotocore-2.5.1/aiobotocore/parsers.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/regions.py` & `aiobotocore-2.5.1/aiobotocore/regions.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/response.py` & `aiobotocore-2.5.1/aiobotocore/response.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/retries/adaptive.py` & `aiobotocore-2.5.1/aiobotocore/retries/adaptive.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/retries/bucket.py` & `aiobotocore-2.5.1/aiobotocore/retries/bucket.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/retries/special.py` & `aiobotocore-2.5.1/aiobotocore/retries/special.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/retries/standard.py` & `aiobotocore-2.5.1/aiobotocore/retries/standard.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/retryhandler.py` & `aiobotocore-2.5.1/aiobotocore/retryhandler.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/session.py` & `aiobotocore-2.5.1/aiobotocore/session.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/signers.py` & `aiobotocore-2.5.1/aiobotocore/signers.py`

 * *Files 2% similar despite different names*

```diff
@@ -321,14 +321,19 @@
 
     try:
         operation_name = self._PY_TO_OP_NAME[client_method]
     except KeyError:
         raise UnknownClientMethodError(method_name=client_method)
 
     operation_model = self.meta.service_model.operation_model(operation_name)
+    params = await self._emit_api_params(
+        api_params=params,
+        operation_model=operation_model,
+        context=context,
+    )
     bucket_is_arn = ArnParser.is_arn(params.get('Bucket', ''))
     endpoint_url, additional_headers = await self._resolve_endpoint_ruleset(
         operation_model,
         params,
         context,
         ignore_signing_region=(not bucket_is_arn),
     )
@@ -381,15 +386,19 @@
     }
 
     post_presigner = AioS3PostPresigner(self._request_signer)
 
     # We choose the CreateBucket operation model because its url gets
     # serialized to what a presign post requires.
     operation_model = self.meta.service_model.operation_model('CreateBucket')
-    params = {'Bucket': bucket}
+    params = await self._emit_api_params(
+        api_params={'Bucket': bucket},
+        operation_model=operation_model,
+        context=context,
+    )
     bucket_is_arn = ArnParser.is_arn(params.get('Bucket', ''))
     endpoint_url, additional_headers = await self._resolve_endpoint_ruleset(
         operation_model,
         params,
         context,
         ignore_signing_region=(not bucket_is_arn),
     )
```

### Comparing `aiobotocore-2.5.0/aiobotocore/tokens.py` & `aiobotocore-2.5.1/aiobotocore/tokens.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/utils.py` & `aiobotocore-2.5.1/aiobotocore/utils.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore/waiter.py` & `aiobotocore-2.5.1/aiobotocore/waiter.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/aiobotocore.egg-info/PKG-INFO` & `aiobotocore-2.5.1/aiobotocore.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: aiobotocore
-Version: 2.5.0
+Version: 2.5.1
 Summary: Async client for aws services using botocore and aiohttp
 Home-page: https://github.com/aio-libs/aiobotocore
 Download-URL: https://pypi.python.org/pypi/aiobotocore
 Author: Nikolay Novik
 Author-email: nickolainovik@gmail.com
 License: Apache License 2.0
 Classifier: Development Status :: 4 - Beta
@@ -13,14 +13,15 @@
 Classifier: Natural Language :: English
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 Classifier: Environment :: Web Environment
 Classifier: Framework :: AsyncIO
 Requires-Python: >=3.7
 Description-Content-Type: text/x-rst
 Provides-Extra: awscli
 Provides-Extra: boto3
 License-File: LICENSE
@@ -266,14 +267,18 @@
     pip install -U 'aiobotocore[awscli,boto3]'
 
 If you only need awscli and not boto3 (or vice versa) you can just install one extra or
 the other.
 
 Changes
 -------
+2.5.1 (2023-06-27)
+^^^^^^^^^^^^^^^^^^
+* bump botocore to 1.29.161
+
 2.5.0 (2023-03-06)
 ^^^^^^^^^^^^^^^^^^
 * bump botocore to 1.29.76 (thanks @jakob-keller #999)
 
 2.4.2 (2022-12-22)
 ^^^^^^^^^^^^^^^^^^
 * fix retries (#988)
```

### Comparing `aiobotocore-2.5.0/aiobotocore.egg-info/SOURCES.txt` & `aiobotocore-2.5.1/aiobotocore.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/setup.py` & `aiobotocore-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -3,23 +3,23 @@
 
 from setuptools import find_packages, setup
 
 # NOTE: If updating requirements make sure to also check Pipfile for any locks
 # NOTE: When updating botocore make sure to update awscli/boto3 versions below
 install_requires = [
     # pegged to also match items in `extras_require`
-    'botocore>=1.29.76,<1.29.77',
-    'aiohttp>=3.3.1',
-    'wrapt>=1.10.10',
-    'aioitertools>=0.5.1',
+    'botocore>=1.29.161,<1.29.162',
+    'aiohttp>=3.3.1,<4.0.0',
+    'wrapt>=1.10.10, <2.0.0',
+    'aioitertools>=0.5.1,<1.0.0',
 ]
 
 extras_require = {
-    'awscli': ['awscli>=1.27.76,<1.27.77'],
-    'boto3': ['boto3>=1.26.76,<1.26.77'],
+    'awscli': ['awscli>=1.27.161,<1.27.162'],
+    'boto3': ['boto3>=1.26.161,<1.26.162'],
 }
 
 
 def read(f):
     return open(os.path.join(os.path.dirname(__file__), f)).read().strip()
 
 
@@ -49,14 +49,15 @@
         'Natural Language :: English',
         'License :: OSI Approved :: Apache Software License',
         'Programming Language :: Python :: 3',
         'Programming Language :: Python :: 3.7',
         'Programming Language :: Python :: 3.8',
         'Programming Language :: Python :: 3.9',
         'Programming Language :: Python :: 3.10',
+        'Programming Language :: Python :: 3.11',
         'Environment :: Web Environment',
         'Framework :: AsyncIO',
     ],
     author="Nikolay Novik",
     author_email="nickolainovik@gmail.com",
     url='https://github.com/aio-libs/aiobotocore',
     download_url='https://pypi.python.org/pypi/aiobotocore',
```

### Comparing `aiobotocore-2.5.0/tests/test_adaptive.py` & `aiobotocore-2.5.1/tests/test_adaptive.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/tests/test_basic_s3.py` & `aiobotocore-2.5.1/tests/test_basic_s3.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/tests/test_config.py` & `aiobotocore-2.5.1/tests/test_config.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/tests/test_dynamodb.py` & `aiobotocore-2.5.1/tests/test_dynamodb.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/tests/test_ec2.py` & `aiobotocore-2.5.1/tests/test_ec2.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/tests/test_eventstreams.py` & `aiobotocore-2.5.1/tests/test_eventstreams.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/tests/test_lambda.py` & `aiobotocore-2.5.1/tests/test_lambda.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/tests/test_monitor.py` & `aiobotocore-2.5.1/tests/test_monitor.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/tests/test_mturk.py` & `aiobotocore-2.5.1/tests/test_mturk.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/tests/test_patches.py` & `aiobotocore-2.5.1/tests/test_patches.py`

 * *Files 1% similar despite different names*

```diff
@@ -174,29 +174,29 @@
     },
     ClientCreator._register_v2_standard_retries: {
         '9ec4ff68599544b4f46067b3783287862d38fb50'
     },
     ClientCreator._register_legacy_retries: {
         '000b2f2a122602e2e741ec2e89308dc2e2b67329'
     },
-    BaseClient._make_api_call: {'bac0b84ebf6276a0c7510095ff168e6fe86a64f6'},
+    BaseClient._make_api_call: {'eba7540893a631a00ebfc3c287026ee6db993e09'},
     BaseClient._make_request: {'cfd8bbf19ea132134717cdf9c460694ddacdbf58'},
     BaseClient._convert_to_request_dict: {
-        '2e423ea67f8773c1a1a64bc516d5102555f4f61a'
+        '899c223cacbe17be646a33882ecd65aa02290b9b'
     },
     BaseClient._emit_api_params: {'abd67874dae8d5cd2788412e4699398cb915a119'},
     BaseClient._resolve_endpoint_ruleset: {
         'e8e7fe581a2e4ff1a75d1ee923c0ed2c6a0d9c9d'
     },
     BaseClient.get_paginator: {'3531d5988aaaf0fbb3885044ccee1a693ec2608b'},
     BaseClient.get_waiter: {'44f0473d993d49ac7502984a7ccee3240b088404'},
     BaseClient.__getattr__: {'3ec17f468f50789fa633d6041f40b66a2f593e77'},
     # config.py
     Config.merge: {'c3dd8c3ffe0da86953ceba4a35267dfb79c6a2c8'},
-    Config: {'90f26fb2f264c0424d60f035494402eac69de269'},
+    Config: {'c22f76d2e45e575d99ae130cdba8ea31cb7f4cdc'},
     # credentials.py
     create_mfa_serial_refresher: {'9b5e98782fcacdcea5899a6d0d29d1b9de348bb0'},
     Credentials.get_frozen_credentials: {
         'eb247f2884aee311bdabba3435e749c3b8589100'
     },
     RefreshableCredentials.__init__: {
         '1a6b83fc845f05feab117ce4fab73b13baed6e3b'
@@ -446,20 +446,20 @@
         '4f9be5feafd6c08ffd7bb8de3c9bc36bc02cbfc8'
     },
     RequestSigner._choose_signer: {'bd0e9784029b8aa182b5aec73910d94cb67c36b0'},
     RequestSigner.generate_presigned_url: {
         '417682868eacc10bf4c65f3dfbdba7d20d9250db'
     },
     add_generate_presigned_url: {'5820f74ac46b004eb79e00eea1adc467bcf4defe'},
-    generate_presigned_url: {'4bbb8eea8ebdd3d49a3c9739a990eb219ed12cc4'},
+    generate_presigned_url: {'48f6745f8a37cfba04b3b2f6fb3910210b4a7201'},
     S3PostPresigner.generate_presigned_post: {
         '269efc9af054a2fd2728d5b0a27db82c48053d7f'
     },
     add_generate_presigned_post: {'e30360f2bd893fabf47f5cdb04b0de420ccd414d'},
-    generate_presigned_post: {'1b48275e09e9c1f872a1d16e74d7e40f34cfaf90'},
+    generate_presigned_post: {'eedf40b48c63f6772ed05e3f335c8193d187f503'},
     add_generate_db_auth_token: {'f61014e6fac4b5c7ee7ac2d2bec15fb16fa9fbe5'},
     generate_db_auth_token: {'1f37e1e5982d8528841ce6b79f229b3e23a18959'},
     # tokens.py
     create_token_resolver: {'b287f4879235a4292592a49b201d2b0bc2dbf401'},
     DeferredRefreshableToken.__init__: {
         '199254ed7e211119bdebf285c5d9a9789f6dc540'
     },
@@ -576,15 +576,15 @@
     },
     EndpointDiscoveryManager._refresh_current_endpoints: {
         'f8a51047c8f395d9458a904e778a3ac156a11911'
     },
     # retries/adaptive.py
     # See comments in AsyncTokenBucket: we completely replace the ClientRateLimiter
     # implementation from botocore.
-    adaptive.ClientRateLimiter: {'e9d99c7921170815f0eaf5c2848765cd6ed90177'},
+    adaptive.ClientRateLimiter: {'9dbf36d36614a4a2e2719ca7e4382aa4694caae3'},
     adaptive.register_retry_handler: {
         '96c073719a3d5d41d1ca7ae5f7e31bbb431c75b3'
     },
     # retries/standard.py
     standard.register_retry_handler: {
         'da0ae35712211bc38938e93c4af8b7aeb999084e'
     },
@@ -606,17 +606,17 @@
     # retries/special.py
     special.RetryDDBChecksumError.is_retryable: {
         '6c6e0945b0989b13fd8e7d78dbfcde307a131eae'
     },
     # retries/bucket.py
     # See comments in AsyncTokenBucket: we completely replace the TokenBucket
     # implementation from botocore.
-    TokenBucket: {'bddbf15ba4c2f04cb7fe04992168fa0e839047e5'},
+    TokenBucket: {'ce932001b13e256d1a2cc625094989fff087d484'},
     # awsresponse.py
-    AWSResponse.content: {'1d74998e3e0abe52b52c251a1eae4971e65b1053'},
+    AWSResponse.content: {'307a4eb1d46360ef808a876d7d00cbbde6198eb1'},
     AWSResponse.text: {'a724100ba9f6d51b333b8fe470fac46376d5044a'},
     # httpchecksum.py
     handle_checksum_body: {'4b9aeef18d816563624c66c57126d1ffa6fe1993'},
     _handle_bytes_response: {'0761c4590c6addbe8c674e40fca9f7dd375a184b'},
     AwsChunkedWrapper._make_chunk: {
         '097361692f0fd6c863a17dd695739629982ef7e4'
     },
```

### Comparing `aiobotocore-2.5.0/tests/test_response.py` & `aiobotocore-2.5.1/tests/test_response.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/tests/test_session.py` & `aiobotocore-2.5.1/tests/test_session.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/tests/test_sns.py` & `aiobotocore-2.5.1/tests/test_sns.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/tests/test_sqs.py` & `aiobotocore-2.5.1/tests/test_sqs.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/tests/test_version.py` & `aiobotocore-2.5.1/tests/test_version.py`

 * *Files identical despite different names*

### Comparing `aiobotocore-2.5.0/tests/test_waiter.py` & `aiobotocore-2.5.1/tests/test_waiter.py`

 * *Files identical despite different names*


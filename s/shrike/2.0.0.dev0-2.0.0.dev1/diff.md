# Comparing `tmp/shrike-2.0.0.dev0.tar.gz` & `tmp/shrike-2.0.0.dev1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "shrike-2.0.0.dev0.tar", last modified: Thu Jun  8 20:41:44 2023, max compression
+gzip compressed data, was "shrike-2.0.0.dev1.tar", last modified: Tue Jun 27 22:16:59 2023, max compression
```

## Comparing `shrike-2.0.0.dev0.tar` & `shrike-2.0.0.dev1.tar`

### file list

```diff
@@ -1,88 +1,88 @@
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.914792 shrike-2.0.0.dev0/
--rw-r--r--   0 runner    (1001) docker     (122)     1141 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (122)       47 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (122)   252717 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/NOTICE.txt
--rw-r--r--   0 runner    (1001) docker     (122)     8629 2023-06-08 20:41:44.914792 shrike-2.0.0.dev0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (122)     6977 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/README.md
--rw-r--r--   0 runner    (1001) docker     (122)       38 2023-06-08 20:41:44.914792 shrike-2.0.0.dev0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (122)     2318 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.898791 shrike-2.0.0.dev0/shrike/
--rw-r--r--   0 runner    (1001) docker     (122)      399 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.902791 shrike-2.0.0.dev0/shrike/_core/
--rw-r--r--   0 runner    (1001) docker     (122)      344 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/_core/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)     4102 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/_core/eyesoff.py
--rw-r--r--   0 runner    (1001) docker     (122)     1682 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/_core/testing.py
--rw-r--r--   0 runner    (1001) docker     (122)     1048 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/_core/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.902791 shrike-2.0.0.dev0/shrike/build/
--rw-r--r--   0 runner    (1001) docker     (122)      427 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/build/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.902791 shrike-2.0.0.dev0/shrike/build/commands/
--rw-r--r--   0 runner    (1001) docker     (122)       73 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/build/commands/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)    61555 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/build/commands/prepare.py
--rw-r--r--   0 runner    (1001) docker     (122)     8229 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/build/commands/register.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.902791 shrike-2.0.0.dev0/shrike/build/core/
--rw-r--r--   0 runner    (1001) docker     (122)       73 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/build/core/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)    13960 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/build/core/command_line.py
--rw-r--r--   0 runner    (1001) docker     (122)     8499 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/build/core/configuration.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.902791 shrike-2.0.0.dev0/shrike/build/utils/
--rw-r--r--   0 runner    (1001) docker     (122)       73 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/build/utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)     5526 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/build/utils/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.906791 shrike-2.0.0.dev0/shrike/compliant_logging/
--rw-r--r--   0 runner    (1001) docker     (122)     1051 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/compliant_logging/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)     6036 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/compliant_logging/argparser_utils.py
--rw-r--r--   0 runner    (1001) docker     (122)      429 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/compliant_logging/constants.py
--rw-r--r--   0 runner    (1001) docker     (122)    10327 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/compliant_logging/data_conversions.py
--rw-r--r--   0 runner    (1001) docker     (122)    16169 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/compliant_logging/exceptions.py
--rw-r--r--   0 runner    (1001) docker     (122)    41145 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/compliant_logging/logging.py
--rw-r--r--   0 runner    (1001) docker     (122)    10311 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/compliant_logging/progress.py
--rw-r--r--   0 runner    (1001) docker     (122)     4875 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/compliant_logging/stack_trace_extractor.py
--rw-r--r--   0 runner    (1001) docker     (122)     1967 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/compliant_logging/system_info.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.906791 shrike-2.0.0.dev0/shrike/distributed/
--rw-r--r--   0 runner    (1001) docker     (122)      254 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/distributed/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)     9037 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/distributed/cluster_auto_setup.py
--rw-r--r--   0 runner    (1001) docker     (122)     9829 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/distributed/dask.py
--rw-r--r--   0 runner    (1001) docker     (122)     4130 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/distributed/mpi_driver.py
--rw-r--r--   0 runner    (1001) docker     (122)     5414 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/distributed/ray.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.910791 shrike-2.0.0.dev0/shrike/pipeline/
--rw-r--r--   0 runner    (1001) docker     (122)      537 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)      104 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/aml_connect.py
--rw-r--r--   0 runner    (1001) docker     (122)      354 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/argparser_utils.py
--rw-r--r--   0 runner    (1001) docker     (122)     7223 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/canary_helper.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.898791 shrike-2.0.0.dev0/shrike/pipeline/components/
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.910791 shrike-2.0.0.dev0/shrike/pipeline/components/fedavg/
--rw-r--r--   0 runner    (1001) docker     (122)      127 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/components/fedavg/env.yaml
--rw-r--r--   0 runner    (1001) docker     (122)     2616 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/components/fedavg/run.py
--rw-r--r--   0 runner    (1001) docker     (122)     2389 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/components/fedavg/spec.yaml
--rw-r--r--   0 runner    (1001) docker     (122)    35499 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/federated_learning.py
--rw-r--r--   0 runner    (1001) docker     (122)      234 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/module_helper.py
--rw-r--r--   0 runner    (1001) docker     (122)    20048 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/module_helper_base.py
--rw-r--r--   0 runner    (1001) docker     (122)    16294 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/pipeline_config.py
--rw-r--r--   0 runner    (1001) docker     (122)      206 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/pipeline_helper.py
--rw-r--r--   0 runner    (1001) docker     (122)    42898 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/pipeline_helper_base.py
--rw-r--r--   0 runner    (1001) docker     (122)     2561 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/ray_actor.py
--rw-r--r--   0 runner    (1001) docker     (122)     2685 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/telemetry_utils.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.910791 shrike-2.0.0.dev0/shrike/pipeline/testing/
--rw-r--r--   0 runner    (1001) docker     (122)      101 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/testing/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)    24460 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/testing/components.py
--rw-r--r--   0 runner    (1001) docker     (122)     2177 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/testing/importer.py
--rw-r--r--   0 runner    (1001) docker     (122)     1837 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/testing/module_run_tests.py
--rw-r--r--   0 runner    (1001) docker     (122)     7894 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/testing/pipeline_class_test.py
--rw-r--r--   0 runner    (1001) docker     (122)     7520 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/testing/pipeline_class_test_v2.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.914792 shrike-2.0.0.dev0/shrike/pipeline/v1/
--rw-r--r--   0 runner    (1001) docker     (122)      374 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)     5039 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/v1/aml_connect.py
--rw-r--r--   0 runner    (1001) docker     (122)     3565 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/v1/module_helper.py
--rw-r--r--   0 runner    (1001) docker     (122)    75640 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/v1/pipeline_helper.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.914792 shrike-2.0.0.dev0/shrike/pipeline/v2/
--rw-r--r--   0 runner    (1001) docker     (122)      382 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/v2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)     5749 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/v2/aml_connect.py
--rw-r--r--   0 runner    (1001) docker     (122)     3839 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/v2/module_helper.py
--rw-r--r--   0 runner    (1001) docker     (122)    68222 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/pipeline/v2/pipeline_helper.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.914792 shrike-2.0.0.dev0/shrike/spark/
--rw-r--r--   0 runner    (1001) docker     (122)      187 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/spark/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)     4936 2023-06-08 20:37:09.000000 shrike-2.0.0.dev0/shrike/spark/spark_net.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-08 20:41:44.902791 shrike-2.0.0.dev0/shrike.egg-info/
--rw-r--r--   0 runner    (1001) docker     (122)     8629 2023-06-08 20:41:44.000000 shrike-2.0.0.dev0/shrike.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (122)     2238 2023-06-08 20:41:44.000000 shrike-2.0.0.dev0/shrike.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (122)        1 2023-06-08 20:41:44.000000 shrike-2.0.0.dev0/shrike.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (122)     1213 2023-06-08 20:41:44.000000 shrike-2.0.0.dev0/shrike.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (122)        7 2023-06-08 20:41:44.000000 shrike-2.0.0.dev0/shrike.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.079957 shrike-2.0.0.dev1/
+-rw-r--r--   0 runner    (1001) docker     (122)     1141 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (122)       47 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (122)   252717 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/NOTICE.txt
+-rw-r--r--   0 runner    (1001) docker     (122)     8629 2023-06-27 22:16:59.075956 shrike-2.0.0.dev1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (122)     6977 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/README.md
+-rw-r--r--   0 runner    (1001) docker     (122)       38 2023-06-27 22:16:59.079957 shrike-2.0.0.dev1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (122)     2318 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.067956 shrike-2.0.0.dev1/shrike/
+-rw-r--r--   0 runner    (1001) docker     (122)      399 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.067956 shrike-2.0.0.dev1/shrike/_core/
+-rw-r--r--   0 runner    (1001) docker     (122)      344 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/_core/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)     4102 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/_core/eyesoff.py
+-rw-r--r--   0 runner    (1001) docker     (122)     1682 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/_core/testing.py
+-rw-r--r--   0 runner    (1001) docker     (122)     1048 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/_core/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.067956 shrike-2.0.0.dev1/shrike/build/
+-rw-r--r--   0 runner    (1001) docker     (122)      427 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/build/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.067956 shrike-2.0.0.dev1/shrike/build/commands/
+-rw-r--r--   0 runner    (1001) docker     (122)       73 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/build/commands/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)    60232 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/build/commands/prepare.py
+-rw-r--r--   0 runner    (1001) docker     (122)     7756 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/build/commands/register.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.071956 shrike-2.0.0.dev1/shrike/build/core/
+-rw-r--r--   0 runner    (1001) docker     (122)       73 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/build/core/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)    14964 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/build/core/command_line.py
+-rw-r--r--   0 runner    (1001) docker     (122)     8463 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/build/core/configuration.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.071956 shrike-2.0.0.dev1/shrike/build/utils/
+-rw-r--r--   0 runner    (1001) docker     (122)       73 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/build/utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)     5526 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/build/utils/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.071956 shrike-2.0.0.dev1/shrike/compliant_logging/
+-rw-r--r--   0 runner    (1001) docker     (122)     1051 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/compliant_logging/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)     6036 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/compliant_logging/argparser_utils.py
+-rw-r--r--   0 runner    (1001) docker     (122)      429 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/compliant_logging/constants.py
+-rw-r--r--   0 runner    (1001) docker     (122)    10327 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/compliant_logging/data_conversions.py
+-rw-r--r--   0 runner    (1001) docker     (122)    16169 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/compliant_logging/exceptions.py
+-rw-r--r--   0 runner    (1001) docker     (122)    41145 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/compliant_logging/logging.py
+-rw-r--r--   0 runner    (1001) docker     (122)    10311 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/compliant_logging/progress.py
+-rw-r--r--   0 runner    (1001) docker     (122)     4875 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/compliant_logging/stack_trace_extractor.py
+-rw-r--r--   0 runner    (1001) docker     (122)     1967 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/compliant_logging/system_info.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.071956 shrike-2.0.0.dev1/shrike/distributed/
+-rw-r--r--   0 runner    (1001) docker     (122)      254 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/distributed/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)     9037 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/distributed/cluster_auto_setup.py
+-rw-r--r--   0 runner    (1001) docker     (122)     9829 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/distributed/dask.py
+-rw-r--r--   0 runner    (1001) docker     (122)     4130 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/distributed/mpi_driver.py
+-rw-r--r--   0 runner    (1001) docker     (122)     5414 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/distributed/ray.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.071956 shrike-2.0.0.dev1/shrike/pipeline/
+-rw-r--r--   0 runner    (1001) docker     (122)      537 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)      104 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/aml_connect.py
+-rw-r--r--   0 runner    (1001) docker     (122)      354 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/argparser_utils.py
+-rw-r--r--   0 runner    (1001) docker     (122)     7223 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/canary_helper.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.063955 shrike-2.0.0.dev1/shrike/pipeline/components/
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.075956 shrike-2.0.0.dev1/shrike/pipeline/components/fedavg/
+-rw-r--r--   0 runner    (1001) docker     (122)      127 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/components/fedavg/env.yaml
+-rw-r--r--   0 runner    (1001) docker     (122)     2616 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/components/fedavg/run.py
+-rw-r--r--   0 runner    (1001) docker     (122)     3131 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/components/fedavg/spec.yaml
+-rw-r--r--   0 runner    (1001) docker     (122)    35499 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/federated_learning.py
+-rw-r--r--   0 runner    (1001) docker     (122)      234 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/module_helper.py
+-rw-r--r--   0 runner    (1001) docker     (122)    20048 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/module_helper_base.py
+-rw-r--r--   0 runner    (1001) docker     (122)    16294 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/pipeline_config.py
+-rw-r--r--   0 runner    (1001) docker     (122)      206 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/pipeline_helper.py
+-rw-r--r--   0 runner    (1001) docker     (122)    42898 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/pipeline_helper_base.py
+-rw-r--r--   0 runner    (1001) docker     (122)     2561 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/ray_actor.py
+-rw-r--r--   0 runner    (1001) docker     (122)     2685 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/telemetry_utils.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.075956 shrike-2.0.0.dev1/shrike/pipeline/testing/
+-rw-r--r--   0 runner    (1001) docker     (122)      101 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/testing/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)    24460 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/testing/components.py
+-rw-r--r--   0 runner    (1001) docker     (122)     2177 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/testing/importer.py
+-rw-r--r--   0 runner    (1001) docker     (122)     1837 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/testing/module_run_tests.py
+-rw-r--r--   0 runner    (1001) docker     (122)     7894 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/testing/pipeline_class_test.py
+-rw-r--r--   0 runner    (1001) docker     (122)     7520 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/testing/pipeline_class_test_v2.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.075956 shrike-2.0.0.dev1/shrike/pipeline/v1/
+-rw-r--r--   0 runner    (1001) docker     (122)      374 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)     5039 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/v1/aml_connect.py
+-rw-r--r--   0 runner    (1001) docker     (122)     3565 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/v1/module_helper.py
+-rw-r--r--   0 runner    (1001) docker     (122)    75640 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/v1/pipeline_helper.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.075956 shrike-2.0.0.dev1/shrike/pipeline/v2/
+-rw-r--r--   0 runner    (1001) docker     (122)      382 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/v2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)     5749 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/v2/aml_connect.py
+-rw-r--r--   0 runner    (1001) docker     (122)     3839 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/v2/module_helper.py
+-rw-r--r--   0 runner    (1001) docker     (122)    68222 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/pipeline/v2/pipeline_helper.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.075956 shrike-2.0.0.dev1/shrike/spark/
+-rw-r--r--   0 runner    (1001) docker     (122)      187 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/spark/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)     4936 2023-06-27 22:11:53.000000 shrike-2.0.0.dev1/shrike/spark/spark_net.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 22:16:59.067956 shrike-2.0.0.dev1/shrike.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (122)     8629 2023-06-27 22:16:58.000000 shrike-2.0.0.dev1/shrike.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (122)     2238 2023-06-27 22:16:59.000000 shrike-2.0.0.dev1/shrike.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (122)        1 2023-06-27 22:16:58.000000 shrike-2.0.0.dev1/shrike.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (122)     1253 2023-06-27 22:16:58.000000 shrike-2.0.0.dev1/shrike.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (122)        7 2023-06-27 22:16:58.000000 shrike-2.0.0.dev1/shrike.egg-info/top_level.txt
```

### Comparing `shrike-2.0.0.dev0/LICENSE` & `shrike-2.0.0.dev1/LICENSE`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/NOTICE.txt` & `shrike-2.0.0.dev1/NOTICE.txt`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/PKG-INFO` & `shrike-2.0.0.dev1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: shrike
-Version: 2.0.0.dev0
+Version: 2.0.0.dev1
 Summary: Python utilities for compliant Azure machine learning
 Home-page: https://github.com/ai-platform-ml-platform/shrike
 Author: AML Data Science
 Author-email: aml-ds@microsoft.com
 License: MIT
 Description: # Shrike: incubation for Azure ML
```

### Comparing `shrike-2.0.0.dev0/README.md` & `shrike-2.0.0.dev1/README.md`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/setup.py` & `shrike-2.0.0.dev1/setup.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/_core/eyesoff.py` & `shrike-2.0.0.dev1/shrike/_core/eyesoff.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/_core/testing.py` & `shrike-2.0.0.dev1/shrike/_core/testing.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/_core/utils.py` & `shrike-2.0.0.dev1/shrike/_core/utils.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/build/commands/prepare.py` & `shrike-2.0.0.dev1/shrike/build/commands/prepare.py`

 * *Files 3% similar despite different names*

```diff
@@ -7,14 +7,15 @@
 import multiprocessing
 import collections
 import jsonpath_ng
 import chardet
 import re
 from typing import List, Set, Union
 import shutil
+import subprocess
 from ruamel.yaml import YAML
 from git import Repo, InvalidGitRepositoryError, NoSuchPathError
 
 from shrike.build.core.command_line import Command
 from shrike.build.utils.utils import (
     create_catalog_stub,
     add_file_to_catalog,
@@ -69,16 +70,16 @@
         Return the normalized path of the directory containing a file.
         """
         return self.normalize_path(Path(file).parent, directory=True)
 
     def all_files_in_snapshot(self, manifest: str) -> List[str]:
         """
         Return a list of all normalized files in the snapshot. The input
-        (`manifest`) is assumed to be some file, whether AML-style component
-        spec or Aether-style auto-approval manifest, in the "root" of the
+        (`manifest`) is assumed to be some AML-style component
+        spec, in the "root" of the
         snapshot.
         """
         folder_path = self.folder_path(manifest)
         log.info("Absolute path for current component is: " + folder_path)
 
         # Generate a list of all files in this components folder (including subdirectories)
         rv = []
@@ -106,15 +107,18 @@
         rv = []
         if files:
             nb_cores = self.nb_cores
 
             if nb_cores == 1:
                 for component in files:
                     if action_type == ActionType.BUILD:
-                        rv.append(self.build_each_components(component))
+                        build_rv = self.build_each_components(component)
+                        if build_rv:
+                            # if build fails, build_rv is None
+                            rv.append(build_rv)
                     elif action_type == ActionType.VALIDATE:
                         self.validate_each_components(component)
                     else:
                         log.error(
                             f"Unknown value for action_type: '{action_type}'. It should be either '{ActionType.BUILD}' or '{ActionType.VALIDATE}'"
                         )
             else:
@@ -126,101 +130,53 @@
                     rv = pool.map(self.build_each_components, files)
                 elif action_type == ActionType.VALIDATE:
                     pool.map(self.validate_each_components, files)
                 pool.close()
                 pool.join()
             return rv  # type: ignore
 
-    def build_each_components(self, component) -> List[str]:
+    def build_each_components(self, component):
         """
         For one of component specification file, run `az ml component build`,
         and register the status (+ register error if build failed).
         """
         path = Path(component)
-        rv = str(path.parent / ".build" / path.name)
-        build_component_success = self.execute_azure_cli_command(
-            f"ml component build --file {component}", ignore_blowfish=True
+        res = subprocess.run(
+            args=f"mldesigner compile --source {component} --output {path.parent}/.build".split(), 
+            cwd = self.config.working_directory,
+            stdout = subprocess.PIPE,
+            stderr = subprocess.PIPE
         )
+        stderr = str(res.stderr, encoding="utf-8", errors="ignore")
+        success_log = "Mldesigner has compiled 1 components from 1 files."
+        build_component_success = res.returncode == 0 and success_log in stderr
+
         if build_component_success:
             log.info(f"Component {component} is built.")
+            with open(component, "r") as spec_file:
+                spec = YAML(typ="safe").load(spec_file)
+            component_name = spec.get("name")
+            log.info(f"component_name {component_name}")
+            return str(path.parent / ".build" / component_name /path.name)
         else:
-            self.register_error(f"Error when building component {component}.")
-        return rv  # type: ignore
+            # if build fails, the path above won't exist, so no return
+            self.register_error(f"Error when building component {component}. Logs: {stderr}")
 
     def create_catalog_files(self, files: List[str]):
         """
         Create the appropriate kind of catalog file(s), using the configured
         method ("aml" or "aether").
         """
         signing_mode = self.config.signing_mode
 
         if signing_mode == "aml":
             self.create_catalog_files_for_aml(files)
-        elif signing_mode == "aether":
-            self.create_catalog_files_for_aether(files)
         else:
             raise ValueError(f"Invalid signing_mode provided: '{signing_mode}'")
 
-    def create_catalog_files_for_aether(self, files: List[str]) -> None:
-        """
-        Create Aether-friendly .cat files, by first creating a CDF file, then
-        finding and running `makecat.exe` to create the catalog file.
-        """
-
-        makecat_default = self.config.makecat_default
-        makecat_directory = self.config.makecat_directory
-        makecat = os.path.join(makecat_directory, makecat_default)
-
-        if not os.path.exists(makecat):
-            log.info(f"Default makecat location {makecat} does not exist")
-            for path in Path(makecat_directory).rglob("makecat.exe"):
-                if "x64" in str(path).lower():
-                    makecat = path
-                    break
-        log.info(f"Makecat location: {makecat}")
-
-        for file in files:
-
-            directory = os.path.dirname(file)
-            name = os.path.split(directory)[-1]
-            cat_name = f"{name}.cat"
-            cdf_name = f"{name}.cdf"
-            path_to_cdf = os.path.join(directory, cdf_name)
-
-            cdf_contents = f"""[CatalogHeader]
-Name={cat_name}
-PublicVersion=0x0000001
-EncodingType=0x00010001
-PageHashes=true
-CATATTR1=0x00010001:OSAttr:2:6.2
-[CatalogFiles]
-"""
-            files_in_module = self.all_files_in_snapshot(file)
-            hash_lines = map(lambda p: f"<HASH>{p}={p}", files_in_module)
-            all_hashes = "\n".join(hash_lines)
-            cdf_contents += all_hashes
-
-            log.info(f"CDF file contents:\n{cdf_contents}")
-
-            with open(path_to_cdf, "w", encoding="ascii") as output:
-                output.write(cdf_contents)
-
-            success = self.execute_command([str(makecat), path_to_cdf, "-v"])
-            if success:
-                log.info(f"Creating Aether catalog files for {name} is successful.")
-                shutil.move(cat_name, directory)
-            else:
-                self.register_error(
-                    f"Error when creating Aether catalog files for {name}."
-                )
-
-            log.info(f"Removing {cdf_name}")
-            os.remove(path_to_cdf)
-            log.info(f"Finish creating aether catalog files for {name}.")
-
     def create_catalog_files_for_aml(self, files: List[str]) -> None:
         """
         Create AML-friendly catalog.json and catalog.json.sig files, using
         SHA-256 hash.
         """
 
         # For each component spec file in the input list, we'll do the following...
@@ -864,22 +820,22 @@
 
     def _create_dependencies_files_for_single_component(
         self, component, path_to_dependencies_files
     ) -> None:
         component_repo = Path(component).parent
         with open(component, "r") as spec_file:
             spec = YAML(typ="safe").load(spec_file)
+        component_name = spec.get("name")
         (
             pip_dependencies,
             conda_dependencies,
             _,
-        ) = self._extract_dependencies_and_channels(component)
+        ) = self._extract_dependencies_and_channels(component, component_name)
 
         if pip_dependencies or conda_dependencies:
-            component_name = spec.get("name")
             cur_path = os.path.join(path_to_dependencies_files, component_name)
             try:
                 os.makedirs(cur_path)
             except FileExistsError:
                 suffix = (
                     component_name
                     + "_"
@@ -899,17 +855,17 @@
             if conda_dependencies:
                 log.info(
                     f"Found conda dependencies for component {component_name} in {component_repo}. Writing to environment.yml."
                 )
                 with open(os.path.join(cur_path, "environment.yml"), "w") as file:
                     yaml.dump(conda_dependencies, file)
 
-    def _extract_dependencies_and_channels(self, component) -> List[list]:
+    def _extract_dependencies_and_channels(self, component, component_name) -> List[list]:
         component_repo = Path(component).parent
-        build_folder = os.path.join(component_repo, ".build")
+        build_folder = os.path.join(component_repo, ".build", component_name)
         if os.path.exists(build_folder):
             component_repo = build_folder
         with open(component, "r") as spec_file:
             spec = YAML(typ="safe").load(spec_file)
         pip_dependencies = []
         conda_dependencies = []
         conda_channels = []
@@ -1013,29 +969,30 @@
             built_component_files = self.process_all_components(
                 component_files, ActionType.BUILD
             )
         else:
             built_component_files = component_files
 
         # only call self.create_catalog_files if built_component_files not None
+        log.info(f"Built component files: {built_component_files}")
         if built_component_files:
             self.create_catalog_files(built_component_files)
 
         self._create_dependencies_files(component_files)
 
         self.add_conda_to_system_path()
 
     def validate_each_components(self, component) -> None:
         """
         For one of component specification file, run `az ml component validate`,
         run compliance and customized validation if enabled,
         and register the status (+ register error if validation failed).
         """
         validate_component_success = self.execute_azure_cli_command(
-            f"ml component validate --file {component}", ignore_blowfish=True
+            f"ml component validate --file {component}", stderr_is_failure=False, check_stdout_result=True, ignore_blowfish=True
         )
         compliance_validation_success = True
         customized_validation_success = True
         if self.config.enable_component_validation:
             log.info(f"Running compliance validation on {component}")
             compliance_validation_success = self.compliance_validation(component)
             if len(self.config.component_validation) > 0:
@@ -1095,19 +1052,20 @@
             ):
                 log.error(
                     f"The container base image in {component} is not allowed for compliant run."
                 )
                 return False
 
         # check whether the package feed is compliant
+        component_name = spec.get("name")
         (
             package_dependencies,
             conda_dependencies,
             conda_channels,
-        ) = self._extract_dependencies_and_channels(component=component)
+        ) = self._extract_dependencies_and_channels(component=component, component_name=component_name)
         if len(package_dependencies) > 0:
             for dependency in package_dependencies:
                 if re.match("^--index-url", dependency) or re.match(
                     "^--extra-index-url", dependency
                 ):
                     if dependency.split(" ")[1] not in ALLOWED_PACKAGE_FEEDS:
                         log.error(
```

### Comparing `shrike-2.0.0.dev0/shrike/build/commands/register.py` & `shrike-2.0.0.dev1/shrike/build/commands/register.py`

 * *Files 5% similar despite different names*

```diff
@@ -29,35 +29,44 @@
         if re.match(self.config.compliant_branch, self.config.source_branch):
             log.info(f"Current branch matches configured regular expression.")
         else:
             raise ValueError(
                 f"Current branch name doesn't match configured name pattern."
             )
 
+    def _check_if_component_name_matches_folder(self, spec_path) -> bool:
+        yaml = YAML(typ="safe")
+        with open(spec_path, "r") as file:
+            spec = yaml.load(file)
+        component_name = spec["name"]
+        return os.path.basename(os.path.dirname(spec_path)) == component_name
+
+
     def find_signed_component_specification_files(self, dir=None) -> List[str]:
         """
         Find all signed component (AML format) generated in the `prepare` step. Return the
         absolute paths of these components in the format of a list of string.
         """
         if dir is None:
             dir = self.config.working_directory
 
         signed_component_spec_files = []
         # Find the path of spec files in the '.build' folders
-        for spec_path in Path(dir).glob(f'{Path(self.config.component_specification_glob).parent}/.build/{Path(self.config.component_specification_glob).name}'):
-
+        # v2 cli creates <component_name> folder for compilation and copies the old yaml there
+        for spec_path in Path(dir).glob(
+            "**/" + Path(self.config.component_specification_glob).name
+        ):
             # Check whether the component is signed by examining catalog files
             if (
                 spec_path.parent.joinpath("catalog.json").exists()
                 and spec_path.parent.joinpath("catalog.json.sig").exists()
+                and self._check_if_component_name_matches_folder(spec_path)
             ):
                 signed_component_spec_files.append(os.path.abspath(spec_path))
-                log.info(f"Found a signed component for AML: {spec_path}")
-            elif spec_path.parent.joinpath(".build.cat").exists():
-                log.info(f"Found a signed component for Aether: {spec_path}")
+                log.info(f"Find a signed component for AML: {spec_path}")
             else:
                 log.warning(f"Found an unsigned component: {spec_path}")
             log.info(str(spec_path.parent.joinpath("catalog.json")))
 
         if len(signed_component_spec_files) == 0:
             log.info("Cannot find any signed components for AML.")
         else:
@@ -68,15 +77,15 @@
         return signed_component_spec_files
 
     def list_registered_component(self) -> None:
         """
         Log all registered component in the attached workspace by using az ml command.
         """
         list_registered_component_success = self.execute_azure_cli_command(
-            f"ml component list -o table", ignore_blowfish=True
+            f"ml component list -o table", stderr_is_failure=False, ignore_blowfish=True  # expect experimental warning on class RegistryOperations as stderr
         )
         if not list_registered_component_success:
             self.register_error(f"Error when listing registered components.")
 
     def register_all_signed_components(self, files: List[str], registry: Optional[str] = None) -> None:
         """
         Run register_component_with_status() in parallel with nb_cores threads
@@ -112,60 +121,41 @@
             self.register_component_status(component, "register", "succeeded")
         else:
             self.register_component_status(component, "register", "failed")
             self.register_error(f"Error when registering component {component}.")
 
     def register_component_command(self, component, registry: Optional[str] = None):
         register_command = f"ml component create --file {component}"
-        set_default_version = False
         component_raw_version = self.read_component_version(component)
 
         if self.config.all_component_version:
-            register_command += f" --version {self.config.all_component_version}"
+            register_command += f" --set version={self.config.all_component_version}"
             component_raw_version = self.config.all_component_version
             log.info(
                 f"Overwrite the component version with the specified value {self.config.all_component_version}"
             )
 
         if registry:
-            register_command += f" --registry {registry}"
-
-        try:
-            component_version = parse(str(component_raw_version))
-            set_default_version = (
-                component_version.base_version == str(component_raw_version)
-            )
-        except:
-            log.error(f"{component_raw_version} is not a valid version number.")
-        if set_default_version:
-            log.info(
-                f"Component {component} version {component_raw_version} is production-ready. Setting as default."
-            )
-            register_command += f" --label default"
-        else:
-            log.info(
-                f"Component {component} version {component_raw_version} is not production-ready. NOT setting as default."
-            )
+            register_command += f" --registry-name {registry}"
 
         log.info(f"Register command is {register_command}")
         return register_command
 
-    def read_component_version(self, yaml_file: str) -> str:
+    def read_component_version(self, yaml_file: str):
         yaml = YAML(typ="safe")
         with open(yaml_file, "r") as file:
             spec = yaml.load(file)
         try:
             version = spec["version"]
             log.info(f"Component {yaml_file} has version {version}.")
             return version
         except KeyError:
-            log.warning(
-                "Component does not have version attribute, attempting to read module version."
+            log.error(
+                "Component does not have version attribute."
             )
-            return spec["amlModuleIdentifier"]["moduleVersion"]
 
     def run_with_config(self):
         """
         Running component registration logic.
         """
         self.telemetry_logging(command="register")
```

### Comparing `shrike-2.0.0.dev0/shrike/build/core/command_line.py` & `shrike-2.0.0.dev1/shrike/build/core/command_line.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,23 +5,26 @@
 import base64
 import logging
 from omegaconf import OmegaConf
 from pathlib import Path
 import subprocess
 import sys
 import os
+import json
 from typing import Any, Dict, List, Optional, Tuple, Union
 from dataclasses import asdict
 
 from shrike import __version__
 from shrike.build.core.configuration import Configuration, load_configuration
 from shrike.build.utils.utils import TelemetryLogger
 
 log = logging.getLogger(__name__)
 
+os.environ["AZURE_ML_CLI_PRIVATE_FEATURES_ENABLED"] = "True"
+os.environ["AZURE_ML_INTERNAL_COMPONENTS_ENABLED"] = "True"
 
 class _LogEmphasize:
     def __init__(self, line: str):
         self.line = line
 
     def __enter__(self):
         log.info(self.line)
@@ -67,18 +70,23 @@
 
         (subscription_id, resource_group, workspace) = self.parse_workspace_arm_id(
             workspace_id
         )
         success = self.execute_azure_cli_command(
             f"account set --subscription {subscription_id}"
         )
+        
+        # expecting experimental warning in stderr for the following two commands
+        # so set stderr_is_failure=False
         success = success and self.execute_azure_cli_command(
-            f"ml folder attach --workspace-name {workspace} --resource-group {resource_group}",
-            ignore_blowfish = True
+            f"config set defaults.group={resource_group} defaults.workspace={workspace}", stderr_is_failure=False, ignore_blowfish = True
         )
+        # the following code is needed because
+        # the command above won't return any error if attaching an invalid workspace.
+        success = success and self.execute_azure_cli_command("ml workspace show", stderr_is_failure=False)
         if not success:
             self.register_error(f"Error!! Failed to attach to {workspace_id}!")
 
     def display_all_statuses(self) -> None:
         """
         Display all component statuses in an easily readable format.
         """
@@ -91,32 +99,34 @@
         """
         return _LogEmphasize(line)
 
     def ensure_component_cli_installed(self) -> bool:
         """
         Check if the component CLI is installed;
         install it if not.
-        # TODO get cli version as config.
         """
 
         # Check whether the component CLI is installed
         component_cli_exists = self.execute_azure_cli_command(
-            "extension show -n azure-cli-ml",
+            "ml component -h",
             stderr_is_failure=False,
             log_error=False,
         )
 
         if component_cli_exists:
             log.info("component CLI exists. Skipping installation.")
             return True
         else:
             log.info(
                 f"installing component CLI version {self.config.component_cli_version}."
             )
-            cli_install_command = f"extension add --source https://azuremlsdktestpypi.blob.core.windows.net/wheels/componentsdk/azure_cli_ml-{self.config.component_cli_version}-py3-none-any.whl --pip-extra-index-urls https://azuremlsdktestpypi.azureedge.net/componentsdk/{self.config.component_cli_version} --yes"
+            self.execute_azure_cli_command(command="extension remove -n azure-cli-ml", stderr_is_failure=False)
+            self.execute_azure_cli_command(command="extension remove -n ml", stderr_is_failure=False,)
+
+            cli_install_command = f"extension add -n ml --version {self.config.component_cli_version} --yes"
             if self.config.verbose:
                 cli_install_command += " --verbose"
 
             is_installed = self.execute_azure_cli_command(
                 command=cli_install_command,
                 # installation may show time to install
                 stderr_is_failure=False,
@@ -132,14 +142,15 @@
     def execute_azure_cli_command(
         self,
         command: str,
         working_dir: Optional[str] = None,
         stderr_is_failure: bool = True,
         fail_if_version_exists: bool = False,
         log_error: bool = True,
+        check_stdout_result: bool = False,
         ignore_blowfish: bool = False,
     ) -> bool:
         """
         Use this method, NOT `execute_command`, for running Azure CLI commands.
         The `command` string should contain everything AFTER the `az`.
 
         This does NOT use the `azure-cli-core` Python package
@@ -150,25 +161,26 @@
         exposes commands. The "naive approach" doesn't work.
         """
         log.debug(f"Executing: az {command}")
         az_command_bytes = bytes(f"az {command}", "utf-16le")
         az_command_b64 = base64.b64encode(az_command_bytes).decode("ascii")
         pwsh_command = ["pwsh", "-EncodedCommand", az_command_b64]
         success = self.execute_command(
-            pwsh_command, working_dir, stderr_is_failure, fail_if_version_exists, log_error, ignore_blowfish
+            pwsh_command, working_dir, stderr_is_failure, fail_if_version_exists, log_error, check_stdout_result, ignore_blowfish
         )
         return success
 
     def execute_command(
         self,
         command: List[str],
         working_dir: Optional[str] = None,
         stderr_is_failure: bool = True,
         fail_if_version_exists: bool = False,
         log_error: bool = True,
+        check_stdout_result: bool = False,
         ignore_blowfish: bool = False,
     ) -> bool:
         """
         Execute the provided shell command using the configured timeout. Working
         directory defaults to the configured one. If `stderr_is_failure` is
         set to false, stderr from the command will be converted to "vanilla"
         logs and will not affect success; 
@@ -200,31 +212,37 @@
             res = subprocess.run(
                 args=command,
                 cwd=working_dir,
                 stdout=subprocess.PIPE,
                 timeout=timeout,
                 **kwargs,
             )
-
             success = res.returncode == 0
 
             if not success:
                 if log_error:
                     log.error(f"Command failed with exit code {res.returncode}")
                 else:
                     log.info(f"Command failed with exit code {res.returncode}")
 
             stdout = res.stdout
             stderr = res.stderr
+            if success and check_stdout_result:
+                # https://msdata.visualstudio.com/Vienna/_workitems/edit/2048751
+                # success = input of operation (`validate`) is valid
+                # but need to check the results in stdout
+                if isinstance(stdout, bytes):
+                    stdout = stdout.decode("utf-8")
+                success = json.loads(stdout)["result"] == "Succeeded"
         except subprocess.TimeoutExpired as e:
             log.error(f"Command timed out after {timeout} seconds.")
             success = False
             stdout = e.stdout
             stderr = e.stderr
-
+        
         if stdout:
             for line in stdout.splitlines():
                 try:
                     line = str(line, encoding="utf-8", errors="ignore")  # type: ignore
                 except:
                     log.debug(
                         "Failed to convert the following stdout line into String (utf-8)"
```

### Comparing `shrike-2.0.0.dev0/shrike/build/core/configuration.py` & `shrike-2.0.0.dev1/shrike/build/core/configuration.py`

 * *Files 2% similar despite different names*

```diff
@@ -19,31 +19,29 @@
 
 @dataclass(frozen=True)
 class Configuration:
     # TODO: should this be handled via enum?
     activation_method: str = field(default="all")
     compliant_branch: str = field(default="^refs/heads/main$")
     source_branch: str = field(default="")
-    component_cli_version: str = field(default="0.9.18")
+    component_cli_version: str = field(default="2.17.2")
     component_specification_glob: str = field(default="**/spec.yaml")
     # TODO: consider a way of supporting both this and `*.yaml` as defaults.
     configuration_file: str = field(default="aml-build-configuration.yml")
     log_format: str = field(default="%(message)s")
     # Registration in registries is surprisingly slow.
     shell_command_timeout_in_seconds: int = field(default=1000)
     number_of_cores_parallel: int = field(default=0)
     # TODO: should this be handled via enum?
     signing_mode: str = field(default="aml")
     verbose: bool = field(default=False)
     working_directory: str = field(default_factory=lambda: os.getcwd())
     workspaces: List[str] = field(
         default_factory=lambda: _EMPTY_LIST, metadata={"nargs": "*"}
     )
-    makecat_directory: str = field(default=r"C:\Program Files (x86)\Windows Kits")
-    makecat_default: str = field(default=r"10\bin\x64\makecat.exe")
     # allow_duplicate_versions is on path to deprecation. Please avoid using it
     allow_duplicate_versions: bool = field(default=False)
     fail_if_version_exists: bool = field(default=False)
     use_build_number: bool = field(default=False)
     all_component_version: str = field(default="")
     disable_telemetry: bool = field(default=False)
     suppress_adding_repo_pr_tags: bool = field(default=False)
@@ -63,14 +61,16 @@
     Create configuration object from "implicit" command line arguments and
     environment variables.
     """
     # Strip away the first argument, which is the name of the file being
     # executed.
     args = sys.argv[1:]
     env = os.environ
+    env["AZURE_ML_CLI_PRIVATE_FEATURES_ENABLED"] = "True"
+    env["AZURE_ML_INTERNAL_COMPONENTS_ENABLED"] = "True"
     rv = load_configuration_from_args_and_env(args, dict(env))
     return rv
 
 
 def load_configuration_from_args(args) -> dict:
     """
     Load a "minimal" configuration dictionary from command line arguments. This
```

### Comparing `shrike-2.0.0.dev0/shrike/build/utils/utils.py` & `shrike-2.0.0.dev1/shrike/build/utils/utils.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/compliant_logging/__init__.py` & `shrike-2.0.0.dev1/shrike/compliant_logging/__init__.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/compliant_logging/argparser_utils.py` & `shrike-2.0.0.dev1/shrike/compliant_logging/argparser_utils.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/compliant_logging/data_conversions.py` & `shrike-2.0.0.dev1/shrike/compliant_logging/data_conversions.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/compliant_logging/exceptions.py` & `shrike-2.0.0.dev1/shrike/compliant_logging/exceptions.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/compliant_logging/logging.py` & `shrike-2.0.0.dev1/shrike/compliant_logging/logging.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/compliant_logging/progress.py` & `shrike-2.0.0.dev1/shrike/compliant_logging/progress.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/compliant_logging/stack_trace_extractor.py` & `shrike-2.0.0.dev1/shrike/compliant_logging/stack_trace_extractor.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/compliant_logging/system_info.py` & `shrike-2.0.0.dev1/shrike/compliant_logging/system_info.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/distributed/cluster_auto_setup.py` & `shrike-2.0.0.dev1/shrike/distributed/cluster_auto_setup.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/distributed/dask.py` & `shrike-2.0.0.dev1/shrike/distributed/dask.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/distributed/mpi_driver.py` & `shrike-2.0.0.dev1/shrike/distributed/mpi_driver.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/distributed/ray.py` & `shrike-2.0.0.dev1/shrike/distributed/ray.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/__init__.py` & `shrike-2.0.0.dev1/shrike/pipeline/__init__.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/canary_helper.py` & `shrike-2.0.0.dev1/shrike/pipeline/canary_helper.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/components/fedavg/run.py` & `shrike-2.0.0.dev1/shrike/pipeline/components/fedavg/run.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/federated_learning.py` & `shrike-2.0.0.dev1/shrike/pipeline/federated_learning.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/module_helper_base.py` & `shrike-2.0.0.dev1/shrike/pipeline/module_helper_base.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/pipeline_config.py` & `shrike-2.0.0.dev1/shrike/pipeline/pipeline_config.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/pipeline_helper_base.py` & `shrike-2.0.0.dev1/shrike/pipeline/pipeline_helper_base.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/ray_actor.py` & `shrike-2.0.0.dev1/shrike/pipeline/ray_actor.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/telemetry_utils.py` & `shrike-2.0.0.dev1/shrike/pipeline/telemetry_utils.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/testing/components.py` & `shrike-2.0.0.dev1/shrike/pipeline/testing/components.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/testing/importer.py` & `shrike-2.0.0.dev1/shrike/pipeline/testing/importer.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/testing/module_run_tests.py` & `shrike-2.0.0.dev1/shrike/pipeline/testing/module_run_tests.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/testing/pipeline_class_test.py` & `shrike-2.0.0.dev1/shrike/pipeline/testing/pipeline_class_test.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/testing/pipeline_class_test_v2.py` & `shrike-2.0.0.dev1/shrike/pipeline/testing/pipeline_class_test_v2.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/v1/aml_connect.py` & `shrike-2.0.0.dev1/shrike/pipeline/v1/aml_connect.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/v1/module_helper.py` & `shrike-2.0.0.dev1/shrike/pipeline/v1/module_helper.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/v1/pipeline_helper.py` & `shrike-2.0.0.dev1/shrike/pipeline/v1/pipeline_helper.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/v2/aml_connect.py` & `shrike-2.0.0.dev1/shrike/pipeline/v2/aml_connect.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/v2/module_helper.py` & `shrike-2.0.0.dev1/shrike/pipeline/v2/module_helper.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/pipeline/v2/pipeline_helper.py` & `shrike-2.0.0.dev1/shrike/pipeline/v2/pipeline_helper.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike/spark/spark_net.py` & `shrike-2.0.0.dev1/shrike/spark/spark_net.py`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike.egg-info/PKG-INFO` & `shrike-2.0.0.dev1/shrike.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: shrike
-Version: 2.0.0.dev0
+Version: 2.0.0.dev1
 Summary: Python utilities for compliant Azure machine learning
 Home-page: https://github.com/ai-platform-ml-platform/shrike
 Author: AML Data Science
 Author-email: aml-ds@microsoft.com
 License: MIT
 Description: # Shrike: incubation for Azure ML
```

### Comparing `shrike-2.0.0.dev0/shrike.egg-info/SOURCES.txt` & `shrike-2.0.0.dev1/shrike.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `shrike-2.0.0.dev0/shrike.egg-info/requires.txt` & `shrike-2.0.0.dev1/shrike.egg-info/requires.txt`

 * *Files 8% similar despite different names*

```diff
@@ -9,14 +9,16 @@
 ruamel.yaml~=0.16
 semver~=2.13
 gitpython~=3.1
 jsonpath-ng~=1.5
 chardet~=4.0
 packaging~=20.0
 opencensus-ext-azure==1.0.7
+mldesigner[pipeline]
+azure-core>=1.26.2
 
 [dev]
 argparse-dataclass~=0.1
 gitpython~=3.1
 omegaconf~=2.0
 rsa~=4.7
 ruamel.yaml~=0.16
```


# Comparing `tmp/pastis-framework-1.0.1.tar.gz` & `tmp/pastis-framework-1.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pastis-framework-1.0.1.tar", last modified: Sat Apr  8 07:45:11 2023, max compression
+gzip compressed data, was "pastis-framework-1.0.2.tar", last modified: Wed Jun 28 14:55:49 2023, max compression
```

## Comparing `pastis-framework-1.0.1.tar` & `pastis-framework-1.0.2.tar`

### file list

```diff
@@ -1,75 +1,75 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.052886 pastis-framework-1.0.1/
--rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     4032 2023-04-08 07:45:11.052886 pastis-framework-1.0.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     4789 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.048885 pastis-framework-1.0.1/bin/
--rwxr-xr-x   0 runner    (1001) docker     (123)    14414 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/bin/pastis-benchmark
--rwxr-xr-x   0 runner    (1001) docker     (123)     4835 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/bin/pastis-broker
--rwxr-xr-x   0 runner    (1001) docker     (123)     2982 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/bin/pastisd
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.048885 pastis-framework-1.0.1/engines/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.048885 pastis-framework-1.0.1/engines/pastis-aflpp/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.048885 pastis-framework-1.0.1/engines/pastis-aflpp/bin/
--rw-r--r--   0 runner    (1001) docker     (123)     4713 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-aflpp/bin/pastis-aflpp
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.048885 pastis-framework-1.0.1/engines/pastis-aflpp/broker-addon/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.048885 pastis-framework-1.0.1/engines/pastis-aflpp/broker-addon/aflppbroker/
--rw-r--r--   0 runner    (1001) docker     (123)     2811 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-aflpp/broker-addon/aflppbroker/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.048885 pastis-framework-1.0.1/engines/pastis-aflpp/pastisaflpp/
--rw-r--r--   0 runner    (1001) docker     (123)      892 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-aflpp/pastisaflpp/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4108 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-aflpp/pastisaflpp/aflpp.py
--rw-r--r--   0 runner    (1001) docker     (123)    12726 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-aflpp/pastisaflpp/driver.py
--rw-r--r--   0 runner    (1001) docker     (123)     4342 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-aflpp/pastisaflpp/replay.py
--rw-r--r--   0 runner    (1001) docker     (123)     3160 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-aflpp/pastisaflpp/workspace.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.048885 pastis-framework-1.0.1/engines/pastis-honggfuzz/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.048885 pastis-framework-1.0.1/engines/pastis-honggfuzz/bin/
--rwxr-xr-x   0 runner    (1001) docker     (123)     4645 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-honggfuzz/bin/pastis-honggfuzz
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.048885 pastis-framework-1.0.1/engines/pastis-honggfuzz/broker-addon/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.048885 pastis-framework-1.0.1/engines/pastis-honggfuzz/broker-addon/hfbroker/
--rw-r--r--   0 runner    (1001) docker     (123)     2907 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-honggfuzz/broker-addon/hfbroker/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.048885 pastis-framework-1.0.1/engines/pastis-honggfuzz/pastishf/
--rw-r--r--   0 runner    (1001) docker     (123)      858 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-honggfuzz/pastishf/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12499 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-honggfuzz/pastishf/driver.py
--rw-r--r--   0 runner    (1001) docker     (123)     3608 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-honggfuzz/pastishf/honggfuzz.py
--rw-r--r--   0 runner    (1001) docker     (123)     4768 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-honggfuzz/pastishf/replay.py
--rw-r--r--   0 runner    (1001) docker     (123)     2854 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-honggfuzz/pastishf/workspace.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.048885 pastis-framework-1.0.1/engines/pastis-triton/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.052886 pastis-framework-1.0.1/engines/pastis-triton/bin/
--rwxr-xr-x   0 runner    (1001) docker     (123)     9813 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-triton/bin/pastis-triton
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.048885 pastis-framework-1.0.1/engines/pastis-triton/broker-addon/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.052886 pastis-framework-1.0.1/engines/pastis-triton/broker-addon/pastisttbroker/
--rw-r--r--   0 runner    (1001) docker     (123)     3145 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-triton/broker-addon/pastisttbroker/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.052886 pastis-framework-1.0.1/engines/pastis-triton/pastisdse/
--rw-r--r--   0 runner    (1001) docker     (123)      448 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-triton/pastisdse/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    40783 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/engines/pastis-triton/pastisdse/pastisdse.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.052886 pastis-framework-1.0.1/libpastis/
--rw-r--r--   0 runner    (1001) docker     (123)      222 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/libpastis/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21929 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/libpastis/agent.py
--rw-r--r--   0 runner    (1001) docker     (123)     3462 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/libpastis/enginedesc.py
--rw-r--r--   0 runner    (1001) docker     (123)    10482 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/libpastis/package.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.052886 pastis-framework-1.0.1/libpastis/proto/
--rw-r--r--   0 runner    (1001) docker     (123)       82 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/libpastis/proto/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5939 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/libpastis/proto/message_pb2.py
--rw-r--r--   0 runner    (1001) docker     (123)     5939 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/libpastis/sast.py
--rw-r--r--   0 runner    (1001) docker     (123)     4901 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/libpastis/types.py
--rw-r--r--   0 runner    (1001) docker     (123)      677 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/libpastis/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.052886 pastis-framework-1.0.1/pastis_framework.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     4032 2023-04-08 07:45:11.000000 pastis-framework-1.0.1/pastis_framework.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1626 2023-04-08 07:45:11.000000 pastis-framework-1.0.1/pastis_framework.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-04-08 07:45:11.000000 pastis-framework-1.0.1/pastis_framework.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      130 2023-04-08 07:45:11.000000 pastis-framework-1.0.1/pastis_framework.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)      106 2023-04-08 07:45:11.000000 pastis-framework-1.0.1/pastis_framework.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.052886 pastis-framework-1.0.1/pastisbenchmark/
--rw-r--r--   0 runner    (1001) docker     (123)      123 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/pastisbenchmark/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      996 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/pastisbenchmark/models.py
--rw-r--r--   0 runner    (1001) docker     (123)    18707 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/pastisbenchmark/plotter.py
--rw-r--r--   0 runner    (1001) docker     (123)     4472 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/pastisbenchmark/replayer.py
--rw-r--r--   0 runner    (1001) docker     (123)    14349 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/pastisbenchmark/results.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:11.052886 pastis-framework-1.0.1/pastisbroker/
--rw-r--r--   0 runner    (1001) docker     (123)       69 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/pastisbroker/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27689 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/pastisbroker/broker.py
--rw-r--r--   0 runner    (1001) docker     (123)     7007 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/pastisbroker/client.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/pastisbroker/dashboard.py
--rw-r--r--   0 runner    (1001) docker     (123)     3779 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/pastisbroker/stat_manager.py
--rw-r--r--   0 runner    (1001) docker     (123)      929 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/pastisbroker/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     6096 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/pastisbroker/workspace.py
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-04-08 07:45:11.052886 pastis-framework-1.0.1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2228 2023-04-08 07:45:10.000000 pastis-framework-1.0.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.983854 pastis-framework-1.0.2/
+-rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     4552 2023-06-28 14:55:49.983854 pastis-framework-1.0.2/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     5289 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.979854 pastis-framework-1.0.2/bin/
+-rwxr-xr-x   0 runner    (1001) docker     (123)    15144 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/bin/pastis-benchmark
+-rwxr-xr-x   0 runner    (1001) docker     (123)     5013 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/bin/pastis-broker
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2982 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/bin/pastisd
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.975854 pastis-framework-1.0.2/engines/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.975854 pastis-framework-1.0.2/engines/pastis-aflpp/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.979854 pastis-framework-1.0.2/engines/pastis-aflpp/bin/
+-rw-r--r--   0 runner    (1001) docker     (123)     4713 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-aflpp/bin/pastis-aflpp
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.975854 pastis-framework-1.0.2/engines/pastis-aflpp/broker-addon/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.979854 pastis-framework-1.0.2/engines/pastis-aflpp/broker-addon/aflppbroker/
+-rw-r--r--   0 runner    (1001) docker     (123)     2811 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-aflpp/broker-addon/aflppbroker/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.979854 pastis-framework-1.0.2/engines/pastis-aflpp/pastisaflpp/
+-rw-r--r--   0 runner    (1001) docker     (123)      892 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-aflpp/pastisaflpp/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4226 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-aflpp/pastisaflpp/aflpp.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12726 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-aflpp/pastisaflpp/driver.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4342 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-aflpp/pastisaflpp/replay.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3160 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-aflpp/pastisaflpp/workspace.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.975854 pastis-framework-1.0.2/engines/pastis-honggfuzz/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.979854 pastis-framework-1.0.2/engines/pastis-honggfuzz/bin/
+-rwxr-xr-x   0 runner    (1001) docker     (123)     4645 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-honggfuzz/bin/pastis-honggfuzz
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.975854 pastis-framework-1.0.2/engines/pastis-honggfuzz/broker-addon/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.979854 pastis-framework-1.0.2/engines/pastis-honggfuzz/broker-addon/hfbroker/
+-rw-r--r--   0 runner    (1001) docker     (123)     2916 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-honggfuzz/broker-addon/hfbroker/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.979854 pastis-framework-1.0.2/engines/pastis-honggfuzz/pastishf/
+-rw-r--r--   0 runner    (1001) docker     (123)      858 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-honggfuzz/pastishf/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12633 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-honggfuzz/pastishf/driver.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4254 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-honggfuzz/pastishf/honggfuzz.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4768 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-honggfuzz/pastishf/replay.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2854 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-honggfuzz/pastishf/workspace.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.979854 pastis-framework-1.0.2/engines/pastis-triton/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.979854 pastis-framework-1.0.2/engines/pastis-triton/bin/
+-rwxr-xr-x   0 runner    (1001) docker     (123)     9813 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-triton/bin/pastis-triton
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.975854 pastis-framework-1.0.2/engines/pastis-triton/broker-addon/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.979854 pastis-framework-1.0.2/engines/pastis-triton/broker-addon/pastisttbroker/
+-rw-r--r--   0 runner    (1001) docker     (123)     3145 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-triton/broker-addon/pastisttbroker/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.979854 pastis-framework-1.0.2/engines/pastis-triton/pastisdse/
+-rw-r--r--   0 runner    (1001) docker     (123)      448 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-triton/pastisdse/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40781 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/engines/pastis-triton/pastisdse/pastisdse.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.979854 pastis-framework-1.0.2/libpastis/
+-rw-r--r--   0 runner    (1001) docker     (123)      222 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/libpastis/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21929 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/libpastis/agent.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3462 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/libpastis/enginedesc.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10482 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/libpastis/package.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.979854 pastis-framework-1.0.2/libpastis/proto/
+-rw-r--r--   0 runner    (1001) docker     (123)       82 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/libpastis/proto/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5939 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/libpastis/proto/message_pb2.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5939 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/libpastis/sast.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4901 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/libpastis/types.py
+-rw-r--r--   0 runner    (1001) docker     (123)      677 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/libpastis/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.983854 pastis-framework-1.0.2/pastis_framework.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     4552 2023-06-28 14:55:49.000000 pastis-framework-1.0.2/pastis_framework.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1626 2023-06-28 14:55:49.000000 pastis-framework-1.0.2/pastis_framework.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:55:49.000000 pastis-framework-1.0.2/pastis_framework.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      130 2023-06-28 14:55:49.000000 pastis-framework-1.0.2/pastis_framework.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      106 2023-06-28 14:55:49.000000 pastis-framework-1.0.2/pastis_framework.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.983854 pastis-framework-1.0.2/pastisbenchmark/
+-rw-r--r--   0 runner    (1001) docker     (123)      123 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/pastisbenchmark/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      996 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/pastisbenchmark/models.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18707 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/pastisbenchmark/plotter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4472 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/pastisbenchmark/replayer.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14349 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/pastisbenchmark/results.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:49.983854 pastis-framework-1.0.2/pastisbroker/
+-rw-r--r--   0 runner    (1001) docker     (123)       69 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/pastisbroker/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31511 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/pastisbroker/broker.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7006 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/pastisbroker/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/pastisbroker/dashboard.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3779 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/pastisbroker/stat_manager.py
+-rw-r--r--   0 runner    (1001) docker     (123)      929 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/pastisbroker/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6096 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/pastisbroker/workspace.py
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 14:55:49.983854 pastis-framework-1.0.2/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2228 2023-06-28 14:55:48.000000 pastis-framework-1.0.2/setup.py
```

### Comparing `pastis-framework-1.0.1/LICENSE` & `pastis-framework-1.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/PKG-INFO` & `pastis-framework-1.0.2/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pastis-framework
-Version: 1.0.1
+Version: 1.0.2
 Summary: PASTIS framework for collaborative fuzzing
 Home-page: https://github.com/quarkslab/pastis
 Author: Quarkslab
 License: AGPL-3.0
 Project-URL: Documentation, https://quarkslab.github.io/pastis/
 Project-URL: Bug Tracker, https://github.com/quarkslab/pastis/issues
 Project-URL: Source, https://github.com/quarkslab/pastis
@@ -174,14 +174,54 @@
 
 
 
 ---
 
 
 
+## Docker
+
+
+
+You can also run PASTIS using Docker:
+
+
+
+```bash
+
+docker pull ubuntu:22.04
+
+docker build -t pastis-docker .
+
+docker run -v <HOST-WORKSPACE>:/workspace --cap-add=SYS_PTRACE --user $(id -u $USER):$(id -g $USER) -it pastis-docker
+
+```
+
+
+
+To open another terminal to an already running container:
+
+
+
+```bash
+
+docker exec -it $(docker ps | grep 'pastis-docker' | awk '{print $1}') /bin/bash
+
+```
+
+
+
+The PASTIS Docker image has already installed all the needed dependencies such as AFL++ and Honggfuzz.
+
+
+
+---
+
+
+
 ## Papers and conference
 
 
 
 * **Symbolic Execution the Swiss-Knife of the Reverse Engineer Toolbox**  
 
   **Venue**: KLEE Workshop, 2022 [[:books:]](https://srg.doc.ic.ac.uk/klee22/talks/David-Reverse-Engineering.pdf) [[:movie_camera:]](https://youtu.be/PNbNtTa5Sp4)
```

### Comparing `pastis-framework-1.0.1/README.md` & `pastis-framework-1.0.2/README.md`

 * *Files 9% similar despite different names*

```diff
@@ -124,14 +124,34 @@
 
 
 > **Note**
 > We warmly welcome any Pull Request to add the support for a new fuzzing engine.
 
 ---
 
+## Docker
+
+You can also run PASTIS using Docker:
+
+```bash
+docker pull ubuntu:22.04
+docker build -t pastis-docker .
+docker run -v <HOST-WORKSPACE>:/workspace --cap-add=SYS_PTRACE --user $(id -u $USER):$(id -g $USER) -it pastis-docker
+```
+
+To open another terminal to an already running container:
+
+```bash
+docker exec -it $(docker ps | grep 'pastis-docker' | awk '{print $1}') /bin/bash
+```
+
+The PASTIS Docker image has already installed all the needed dependencies such as AFL++ and Honggfuzz.
+
+---
+
 ## Papers and conference
 
 * **Symbolic Execution the Swiss-Knife of the Reverse Engineer Toolbox**  
   **Venue**: KLEE Workshop, 2022 [[:books:]](https://srg.doc.ic.ac.uk/klee22/talks/David-Reverse-Engineering.pdf) [[:movie_camera:]](https://youtu.be/PNbNtTa5Sp4)  
   **Authors**: Robin David, Richard Abou Chaaya, Christian Heitman
```

#### html2text {}

```diff
@@ -39,19 +39,26 @@
 campaign.html) ## Adding a Fuzzer Integrating a fuzzer requires writing a
 Python driver using the ``libpasts`` library installed by the package. It
 requires implementing some callbacks to receive the initial configuration and
 also to receive inputs from the broker. Conversely the API enables sending
 newly generated inputs to the broker. The process is further [detailed in the
 documentation](https://quarkslab.github.io/pastis/adding-fuzzer.html). >
 **Note** > We warmly welcome any Pull Request to add the support for a new
-fuzzing engine. --- ## Papers and conference * **Symbolic Execution the Swiss-
-Knife of the Reverse Engineer Toolbox** **Venue**: KLEE Workshop, 2022 [[:
-books:]](https://srg.doc.ic.ac.uk/klee22/talks/David-Reverse-Engineering.pdf) [
-[:movie_camera:]](https://youtu.be/PNbNtTa5Sp4) **Authors**: Robin David,
-Richard Abou Chaaya, Christian Heitman * **From source code to crash test-case
-through software testing automation** **Venue**: European Cyber Week, C&ESAR
-Workshop, 2021 [paper](https://ceur-ws.org/Vol-3056/paper-02.pdf) [slides]
-(https://github.com/quarkslab/conf-presentations/blob/main-page/C%26ESAR-2021/
-CESAR-2021_slides_2-2.pdf) **Authors**: Robin David, Jonathan Salwan, Justin
-Bourroux ## Cite Pastis ```latex soon ``` ## Contributors Pastis is powered by
-[Quarkslab](https://quarkslab.com) and initially financed by DGA-MI. [**All
-contributions**](https://github.com/quarkslab/pastis/graphs/contributors)
+fuzzing engine. --- ## Docker You can also run PASTIS using Docker: ```bash
+docker pull ubuntu:22.04 docker build -t pastis-docker . docker run -v :/
+workspace --cap-add=SYS_PTRACE --user $(id -u $USER):$(id -g $USER) -it pastis-
+docker ``` To open another terminal to an already running container: ```bash
+docker exec -it $(docker ps | grep 'pastis-docker' | awk '{print $1}') /bin/
+bash ``` The PASTIS Docker image has already installed all the needed
+dependencies such as AFL++ and Honggfuzz. --- ## Papers and conference *
+**Symbolic Execution the Swiss-Knife of the Reverse Engineer Toolbox**
+**Venue**: KLEE Workshop, 2022 [[:books:]](https://srg.doc.ic.ac.uk/klee22/
+talks/David-Reverse-Engineering.pdf) [[:movie_camera:]](https://youtu.be/
+PNbNtTa5Sp4) **Authors**: Robin David, Richard Abou Chaaya, Christian Heitman *
+**From source code to crash test-case through software testing automation**
+**Venue**: European Cyber Week, C&ESAR Workshop, 2021 [paper](https://ceur-
+ws.org/Vol-3056/paper-02.pdf) [slides](https://github.com/quarkslab/conf-
+presentations/blob/main-page/C%26ESAR-2021/CESAR-2021_slides_2-2.pdf)
+**Authors**: Robin David, Jonathan Salwan, Justin Bourroux ## Cite Pastis
+```latex soon ``` ## Contributors Pastis is powered by [Quarkslab](https://
+quarkslab.com) and initially financed by DGA-MI. [**All contributions**](https:
+//github.com/quarkslab/pastis/graphs/contributors)
```

### Comparing `pastis-framework-1.0.1/bin/pastis-benchmark` & `pastis-framework-1.0.2/bin/pastis-benchmark`

 * *Files 3% similar despite different names*

```diff
@@ -154,24 +154,35 @@
 @click.option('-p', '--port', type=int, default=5555, help="Port to bind to", multiple=False)
 @click.option('--hfuzz-path', type=click.Path(exists=True, file_okay=True, dir_okay=True, readable=True), required=False, help="Custom Honggfuzz path")
 @click.option('--hfuzz-threads', type=int, default=0, help="Number of threads to launch Honggfuzz with")
 @click.option('--spawn/--no-spawn', type=bool, is_flag=True, default=True, help="Either to spawn engines or not")
 @click.option("--allow-remote", type=bool, is_flag=True, default=False, help="Enable remote connection")
 @click.option('--probe', type=str, help="Probe to load as a python module (should contain a ProbeInterface)", multiple=True)
 @click.option('--skip-cpufreq', is_flag=True, type=bool, default=False, help="Skip CPU frequency scaling check")
-def run(workspace: str, bins: str, seeds: str, mode: str, injloc: str, aflpp: bool, hfuzz: bool, triton: bool, debug: bool,
-        timeout: Optional[int], port: int, hfuzz_path: str, hfuzz_threads: int, spawn: bool, allow_remote: bool, probe: Tuple[str], skip_cpufreq: bool):
+@click.option('--start-quorum', type=int, default=0, help="Number of client connection to receive before triggering startup", show_default=True)
+@click.option('--proxy', type=str, default="", help="Run the broker as a proxy to another broker")
+def run(workspace: str, bins: str, seeds: str, mode: str, injloc: str, aflpp: bool, hfuzz: bool, triton: bool,
+        debug: bool, timeout: Optional[int], port: int, hfuzz_path: str, hfuzz_threads: int, spawn: bool,
+        allow_remote: bool, probe: Tuple[str], skip_cpufreq: bool, start_quorum: int, proxy: str):
 
     configure_logging(logging.DEBUG if debug else logging.INFO, "%(asctime)s %(name)s [%(levelname)s] %(message)s")
 
-    broker = PastisBroker(workspace, bins, BrokingMode[mode], CheckMode.CHECK_ALL, SeedInjectLoc[injloc], None, [])
+    broker = PastisBroker(workspace, bins, BrokingMode[mode], CheckMode.CHECK_ALL, SeedInjectLoc[injloc], None, [], start_quorum=start_quorum)
+
+    if proxy:  # proxy format should be:  IP:port@py_module
+        url, py_module = proxy.split("@")
+        proxy_ip, proxy_port = url.split(":")
+        broker.set_proxy(proxy_ip, int(proxy_port), py_module)
 
     # Add all given seeds as initial seed
-    for s in iterate_seeds(seeds):  # File if one file, or iterate dir if directory
-        broker.add_seed_file(s, initial=True)
+    if seeds is None:
+        logging.warning("no initial corpus provided")
+    else:
+        for s in iterate_seeds(seeds):  # File if one file, or iterate dir if directory
+            broker.add_seed_file(s, initial=True)
 
     ws_root = broker.workspace.root
 
     clients_ws = ws_root / "clients_ws"
 
     if clients_ws.exists():
         logging.error("benchmarks have already been runnned in that directory")
@@ -202,41 +213,43 @@
             sys.exit(1)
         else:  # Honggfuzz is available
             hf_ws = clients_ws / "hfuzz"
             hf_ws.mkdir()
             if spawn:
                 spawn_online_honggfuzz(hf_ws, hf_exe_path, port, hfuzz_threads)
 
-    if triton:
-        # Look for configuration files, add them to the broker and launch as many triton instances
-        tt_confs = ws_root / "triton_confs"
-        broker.load_engine_addon("pastisttbroker")
-        if tt_confs.exists():
-            for i, conf in enumerate(sorted(tt_confs.iterdir())):
-                with open(conf, "r+") as fd:
-                    tt_ws = clients_ws / f"ttdse_{i}"
-                    c = json.load(fd)
-                    c["workspace"] = str(tt_ws)
-                    fd.seek(0)
-                    json.dump(c, fd, indent=2)
-                    fd.truncate()
-                logging.info(f"Add Triton configuration: {conf}")
-                broker.add_engine_configuration("TRITON", conf)
-                if spawn:
-                    spawn_online_triton(port, probe)
-        else:
+    # Look for configuration files, add them to the broker and launch as many triton instances
+    tt_confs = ws_root / "triton_confs"
+    if not tt_confs.exists():  # if folder is empty
+        logging.info(f"{tt_confs} not found fall back current workdir")
+        tt_confs = Path("triton_confs")
+    broker.load_engine_addon("pastisttbroker")
+    if tt_confs.exists():
+        for i, conf in enumerate(sorted(tt_confs.iterdir())):
+            with open(conf, "r+") as fd:
+                tt_ws = clients_ws / f"ttdse_{i}"
+                c = json.load(fd)
+                c["workspace"] = str(tt_ws)
+                fd.seek(0)
+                json.dump(c, fd, indent=2)
+                fd.truncate()
+            logging.info(f"Add Triton configuration: {conf}")
+            broker.add_engine_configuration("TRITON", conf)
+            if triton and spawn:
+                spawn_online_triton(port, probe)
+    else:
+        if not triton:
             logging.warning("Triton enabled but no configuration found")
 
     # Bind it and start listening (clients can connect)
     ip = "*" if allow_remote else "127.0.0.1"
     broker.bind(port, ip)
     broker.run(timeout)
 
 
-
 @cli.command(context_settings=dict(show_default=True))
 @click.argument('workspace', type=click.Path(exists=True, file_okay=False, dir_okay=True, readable=True))
 @click.option('-t', '--type', type=click.Choice([x.name for x in list(ReplayType)]), default=ReplayType.qbdi.name, help="Replay type")
 @click.option('-i', '--injloc', type=click.Choice([x.name for x in list(SeedInjectLoc)]), default=SeedInjectLoc.STDIN.name, help="Seed injection location")
 @click.option('--live', type=bool, is_flag=True, default=False, help="Enable replaying input files during the campaign")
 @click.option('--stream', type=bool, is_flag=True, default=False, help="Enable streaming coverage on a ZMQ socket")
 @click.option("-t", "--timeout", type=int, default=60, help="Replay timeout")
```

### Comparing `pastis-framework-1.0.1/bin/pastis-broker` & `pastis-framework-1.0.2/bin/pastis-broker`

 * *Files 3% similar despite different names*

```diff
@@ -49,27 +49,28 @@
 @click.option('-e', '--engine', type=str, help="Fuzzing engine module to load (python module)", multiple=True)
 @click.option('--tt-config', type=click.Path(exists=True, file_okay=True, dir_okay=True, readable=True), help="Triton configuration file")
 @click.option('--hf-config', type=click.Path(exists=True, file_okay=True, dir_okay=True, readable=True), help="Honggfuzz configuration file")
 @click.option('-s', "--seed", type=click.Path(exists=True, file_okay=True, dir_okay=True, readable=True), help="Initial seed or directory of seeds to give as initial corpus", multiple=True)
 @click.option('-t', "--timeout", type=int, default=None, help="Timeout of the campaign. Time after which stopping the campaign")
 @click.option('-p', '--port', type=int, default=5555, help="Port to bind to", multiple=False, show_default=True)
 @click.option('--mem-threshold', type=int, default=85, help="RAM consumption limit", show_default=True)
+@click.option('--start-quorum', type=int, default=0, help="Number of client connection to receive before triggering startup", show_default=True)
 @click.argument('pargvs', nargs=-1)
 def main(workspace: str, sast_report: Optional[str], bins: str, mode: str, chkmode: str, injloc: str, engine: Tuple[str],
          tt_config: Optional[str], hf_config: Optional[str], seed: Tuple[str], timeout: Optional[int],
-         port: Optional[int], pargvs: Tuple[str], mem_threshold: int):
+         port: Optional[int], pargvs: Tuple[str], mem_threshold: int, start_quorum: int):
     global broker
     # Instanciate the broker
 
     chkmode = CheckMode[chkmode]
     if chkmode in [CheckMode.ALERT_ONLY, CheckMode.ALERT_ONE] and not sast_report:
         logging.error(f"Check mode {chkmode.name} requires a SAST report (use -r) to provide it")
         sys.exit(1)
 
-    broker = PastisBroker(workspace, bins, BrokingMode[mode], chkmode, SeedInjectLoc[injloc], sast_report, list(pargvs), mem_threshold)
+    broker = PastisBroker(workspace, bins, BrokingMode[mode], chkmode, SeedInjectLoc[injloc], sast_report, list(pargvs), mem_threshold, start_quorum)
 
     # Preload all Fuzzing engine if needed
     for eng in engine:
         broker.load_engine_addon(eng)
 
     # Add all the triton configuration if the parameter was a directory
     if tt_config:
```

### Comparing `pastis-framework-1.0.1/bin/pastisd` & `pastis-framework-1.0.2/bin/pastisd`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/engines/pastis-aflpp/bin/pastis-aflpp` & `pastis-framework-1.0.2/engines/pastis-aflpp/bin/pastis-aflpp`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/engines/pastis-aflpp/broker-addon/aflppbroker/__init__.py` & `pastis-framework-1.0.2/engines/pastis-aflpp/broker-addon/aflppbroker/__init__.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/engines/pastis-aflpp/pastisaflpp/__init__.py` & `pastis-framework-1.0.2/engines/pastis-aflpp/pastisaflpp/__init__.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/engines/pastis-aflpp/pastisaflpp/aflpp.py` & `pastis-framework-1.0.2/engines/pastis-aflpp/pastisaflpp/aflpp.py`

 * *Files 4% similar despite different names*

```diff
@@ -74,14 +74,18 @@
         # TODO Should we skip these steps?
         os.environ["AFL_SKIP_CPUFREQ"] = "1"
         os.environ["AFL_I_DONT_CARE_ABOUT_MISSING_CRASHES"] = "1"
 
         # Build fuzzer command line.
         aflpp_cmdline = f'{self.__path} {aflpp_arguments} -- {target_cmdline}'
 
+        # NOTE: Assuming fixed location for the input file.
+        if not stdin:
+            aflpp_cmdline += " @@"
+
         logging.info(f"Run AFL++: {aflpp_cmdline}")
         logging.debug(f"\tWorkspace: {workspace.root_dir}")
 
         # Remove empty strings when converting the command to a list.
         command = list(filter(None, aflpp_cmdline.split(' ')))
 
         # Open logfile (stdout will be redirected to this file).
```

### Comparing `pastis-framework-1.0.1/engines/pastis-aflpp/pastisaflpp/driver.py` & `pastis-framework-1.0.2/engines/pastis-aflpp/pastisaflpp/driver.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/engines/pastis-aflpp/pastisaflpp/replay.py` & `pastis-framework-1.0.2/engines/pastis-aflpp/pastisaflpp/replay.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/engines/pastis-aflpp/pastisaflpp/workspace.py` & `pastis-framework-1.0.2/engines/pastis-aflpp/pastisaflpp/workspace.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/engines/pastis-honggfuzz/bin/pastis-honggfuzz` & `pastis-framework-1.0.2/engines/pastis-honggfuzz/bin/pastis-honggfuzz`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/engines/pastis-honggfuzz/broker-addon/hfbroker/__init__.py` & `pastis-framework-1.0.2/engines/pastis-honggfuzz/broker-addon/hfbroker/__init__.py`

 * *Files 5% similar despite different names*

```diff
@@ -60,30 +60,30 @@
     @staticmethod
     def accept_file(binary_file: Path) -> Tuple[bool, Optional[ExecMode], Optional[FuzzMode]]:
         p = lief.parse(str(binary_file))
         if not p:
             return False, None, None
 
         # Search for HF instrumentation
-        good = False
+        instrumented = False
         for f in p.functions:
             if "hfuzz_" in f.name:
-                good = True
+                instrumented = True
                 break
-        if not good:
-            return False, None, None
+        if not instrumented:
+            return True, ExecMode.PERSISTENT, FuzzMode.BINARY_ONLY
 
         # Search for persistent magic
         exmode = ExecMode.SINGLE_EXEC  # by default single_exec
         sections = {x.name: x for x in p.sections}
         if '.rodata' in sections:
             rodata_content = bytearray(sections['.rodata'].content)
             if HonggfuzzEngineDescriptor.HF_PERSISTENT_SIG in rodata_content:
                 exmode = ExecMode.PERSISTENT
         else:
             if 'HF_ITER' in (x.name for x in p.imported_functions):  # More dummy method
                 exmode = ExecMode.PERSISTENT
-        return True, exmode, FuzzMode.INSTRUMENTED  # FIXME: Can honggfuzz work in binary_only?
+        return True, exmode, FuzzMode.INSTRUMENTED
 
     @staticmethod
     def supported_coverage_strategies() -> List[CoverageMode]:
         return [CoverageMode.AUTO]
```

### Comparing `pastis-framework-1.0.1/engines/pastis-honggfuzz/pastishf/__init__.py` & `pastis-framework-1.0.2/engines/pastis-honggfuzz/pastishf/__init__.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/engines/pastis-honggfuzz/pastishf/driver.py` & `pastis-framework-1.0.2/engines/pastis-honggfuzz/pastishf/driver.py`

 * *Files 2% similar despite different names*

```diff
@@ -65,29 +65,32 @@
         self._queue_to_send = []
         self._started = False
 
     @staticmethod
     def hash_seed(seed: bytes):
         return hashlib.md5(seed).hexdigest()
 
-    def start(self, package: BinaryPackage, argv: List[str], exmode: ExecMode, seed_inj: SeedInjectLoc, engine_args: str):
+    def start(self, package: BinaryPackage, argv: List[str], exmode: ExecMode, fuzzmode: FuzzMode,
+              seed_inj: SeedInjectLoc, engine_args: str):
         # Write target to disk.
         self.__package = package
         self.__target_args = argv
 
         self.workspace.start()  # Start looking at directories
 
         logging.info("Start process")
-        self.honggfuzz.start(self.__package.executable_path.absolute(),
+        if not self.honggfuzz.start(self.__package.executable_path.absolute(),
                              " ".join(argv),
                              self.workspace,
-                             exmode == ExecMode.PERSISTENT,
+                             exmode,
+                             fuzzmode,
                              seed_inj == SeedInjectLoc.STDIN,
                              engine_args,
-                             str(package.dictionary.absolute()) if package.dictionary else None)
+                             str(package.dictionary.absolute()) if package.dictionary else None):
+            self._agent.send_log(LogLevel.ERROR, "Cannot start target, HFQBDIPRELAOD not found")
         self._started = True
 
         # Start the replay worker (note that the queue might already have started to be filled by agent thread)
         self._replay_thread = threading.Thread(target=self.replay_worker, daemon=True)
         self._replay_thread.start()
 
     def stop(self):
@@ -222,15 +225,15 @@
                                            coverage_edge=coverage_edge,
                                            last_cov_update=last_cov_update)
             except:
                 logging.error(f'Error retrieving stats!')
 
     def start_received(self, fname: str, binary: bytes, engine: FuzzingEngineInfo, exmode: ExecMode, fuzzmode: FuzzMode, chkmode: CheckMode,
                        _: CoverageMode, seed_inj: SeedInjectLoc, engine_args: str, argv: List[str], sast_report: str = None):
-        logging.info(f"[START] bin:{fname} engine:{engine.name} exmode:{exmode.name} seedloc:{seed_inj.name} chk:{chkmode.name}")
+        logging.info(f"[START] bin:{fname} engine:{engine.name} exmode:{exmode.name} fuzzmode:{fuzzmode.name} seedloc:{seed_inj.name} chk:{chkmode.name}")
         if self.started:
             self._agent.send_log(LogLevel.CRITICAL, "Instance already started!")
             return
 
         if engine.name != "HONGGFUZZ":
             logging.error(f"Wrong fuzzing engine received {engine.name} while I am Honggfuzz")
             self._agent.send_log(LogLevel.ERROR, f"Invalid fuzzing engine received {engine.name} can't do anything")
@@ -249,17 +252,15 @@
 
         if sast_report:
             logging.info("Loading SAST report")
             self.__report = SASTReport.from_json(sast_report)
 
         self.__check_mode = chkmode  # CHECK_ALL, ALERT_ONLY
 
-        # FIXME: (chris) Do something with fuzz mode ?
-
-        self.start(package, argv, exmode, seed_inj, engine_args)
+        self.start(package, argv, exmode, fuzzmode, seed_inj, engine_args)
 
     def __seed_received(self, typ: SeedType, seed: bytes):
         h = self.hash_seed(seed)
         logging.info(f"[SEED] received  {h} ({typ.name})")
         self._seed_recvs.add(h)
 
         # HACK: Maybe doing it more nicely ?
```

### Comparing `pastis-framework-1.0.1/engines/pastis-honggfuzz/pastishf/honggfuzz.py` & `pastis-framework-1.0.2/engines/pastis-honggfuzz/pastishf/honggfuzz.py`

 * *Files 18% similar despite different names*

```diff
@@ -2,14 +2,15 @@
 import os
 import subprocess
 import re
 import signal
 import time
 from pathlib import Path
 from typing import Optional
+from libpastis.types import ExecMode, FuzzMode
 
 # Local imports
 from .workspace import Workspace
 
 
 class HonggfuzzNotFound(Exception):
     """ Issue raised on """
@@ -39,50 +40,61 @@
             if not path.exists():
                 raise Exception("Can't find honggfuzz in HFUZZ_PATH path!")
 
         self._threads = os.environ.get(self.HFUZZ_THREADS_VAR)
 
         self.__process = None
 
-
-    def start(self, target: str, target_arguments: str, workspace: Workspace, persistent: bool, stdin: bool, engine_args: str, dictionary: Optional[str] = None):
+    def start(self, target: str, target_arguments: str, workspace: Workspace, exmode: ExecMode, fuzzmode: FuzzMode,
+              stdin: bool, engine_args: str, dictionary: Optional[str] = None) -> bool:
         # Build target command line.
         target_cmdline = f"{target} {target_arguments}"
 
+        HFQBDIPRELOAD_LIB_PATH = os.getenv('HFQBDIPRELOAD_LIB_PATH')
+
+        if fuzzmode == FuzzMode.BINARY_ONLY and HFQBDIPRELOAD_LIB_PATH is None:
+            logging.error(f"target in BINARY_ONLY but can't find HFQBDIPRELOAD_LIB_PATH")
+            return False
+
         # Build fuzzer arguments.
-        # NOTE: Assuming the target receives inputs from stdin.
         hfuzz_arguments = ' '.join([
             f"--statsfile {workspace.stats_file}",
             f"--stdin_input" if stdin else "",
-            f"--persistent" if persistent else "",
+            f"--persistent" if exmode == ExecMode.PERSISTENT or fuzzmode == FuzzMode.BINARY_ONLY else "",
+            f"--env HFQBDI_FS=1" if fuzzmode == FuzzMode.BINARY_ONLY else "",
+            f"--env LD_PRELOAD={HFQBDIPRELOAD_LIB_PATH}/libHFQBDIpreload.so" if fuzzmode == FuzzMode.BINARY_ONLY else "",
             re.sub(r"\s", " ", engine_args),  # Any arguments coming right from the broker (remove \r\n)
             f"--logfile logfile.log",
-            f"--sanitizers_del_report true",
             f"--input {workspace.input_dir}",
             f"--dynamic_input {workspace.dynamic_input_dir}",
             f"--output {workspace.corpus_dir}",
             f"--crashdir {workspace.crash_dir}",
             f"--workspace {workspace.root_dir}",
             f"--threads {self._threads}" if self._threads else "",
             f"--dict {dictionary}" if dictionary is not None else ""
         ])
 
         # Build fuzzer command line.
         hfuzz_cmdline = f'{self.__path} {hfuzz_arguments} -- {target_cmdline}'
 
+        # NOTE: Assuming fixed location for the input file.
+        if not stdin:
+            hfuzz_cmdline += " ___FILE___"
+
         logging.info(f"Run Honggfuzz with: {hfuzz_cmdline}")
         logging.debug(f"\tWorkspace: {workspace.root_dir}")
 
         # Remove empty strings when converting the command to a list.
         command = list(filter(None, hfuzz_cmdline.split(' ')))
 
         # Create a new fuzzer process and set it apart into a new process group.
         self.__process = subprocess.Popen(command, cwd=str(workspace.root_dir), preexec_fn=os.setsid)
 
         logging.debug(f'Process pid: {self.__process.pid}')
+        return True
 
     @property
     def instanciated(self):
         return self.__process is not None
 
     def stop(self):
         if self.__process:
```

### Comparing `pastis-framework-1.0.1/engines/pastis-honggfuzz/pastishf/replay.py` & `pastis-framework-1.0.2/engines/pastis-honggfuzz/pastishf/replay.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/engines/pastis-honggfuzz/pastishf/workspace.py` & `pastis-framework-1.0.2/engines/pastis-honggfuzz/pastishf/workspace.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/engines/pastis-triton/bin/pastis-triton` & `pastis-framework-1.0.2/engines/pastis-triton/bin/pastis-triton`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/engines/pastis-triton/broker-addon/pastisttbroker/__init__.py` & `pastis-framework-1.0.2/engines/pastis-triton/broker-addon/pastisttbroker/__init__.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/engines/pastis-triton/pastisdse/pastisdse.py` & `pastis-framework-1.0.2/engines/pastis-triton/pastisdse/pastisdse.py`

 * *Files 0% similar despite different names*

```diff
@@ -83,22 +83,20 @@
     def add_probe(self, probe: ProbeInterface):
         self._probes.append(probe)
 
     def _init_callbacks(self):
         self.agent.register_seed_callback(self.seed_received)
         self.agent.register_stop_callback(self.stop_received)
 
-
     def init_agent(self, remote: str = "localhost", port: int = 5555):
         self.agent.register_start_callback(self.start_received) # register start because launched manually
         self.agent.connect(remote, port)
         self.agent.start()
         self.agent.send_hello([FuzzingEngineInfo("TRITON", pastisdse.__version__, "pastisttbroker")])
 
-
     def start(self):
         self._th = threading.Thread(target=self.run, daemon=True)
         self._th.start()
 
     def reset(self):
         """ Reset the current DSE to be able to restart from fresh settings """
         self.dse = None  # remove DSE object
```

### Comparing `pastis-framework-1.0.1/libpastis/agent.py` & `pastis-framework-1.0.2/libpastis/agent.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/libpastis/enginedesc.py` & `pastis-framework-1.0.2/libpastis/enginedesc.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/libpastis/package.py` & `pastis-framework-1.0.2/libpastis/package.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/libpastis/proto/message_pb2.py` & `pastis-framework-1.0.2/libpastis/proto/message_pb2.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/libpastis/sast.py` & `pastis-framework-1.0.2/libpastis/sast.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/libpastis/types.py` & `pastis-framework-1.0.2/libpastis/types.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/libpastis/utils.py` & `pastis-framework-1.0.2/libpastis/utils.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/pastis_framework.egg-info/PKG-INFO` & `pastis-framework-1.0.2/pastis_framework.egg-info/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pastis-framework
-Version: 1.0.1
+Version: 1.0.2
 Summary: PASTIS framework for collaborative fuzzing
 Home-page: https://github.com/quarkslab/pastis
 Author: Quarkslab
 License: AGPL-3.0
 Project-URL: Documentation, https://quarkslab.github.io/pastis/
 Project-URL: Bug Tracker, https://github.com/quarkslab/pastis/issues
 Project-URL: Source, https://github.com/quarkslab/pastis
@@ -174,14 +174,54 @@
 
 
 
 ---
 
 
 
+## Docker
+
+
+
+You can also run PASTIS using Docker:
+
+
+
+```bash
+
+docker pull ubuntu:22.04
+
+docker build -t pastis-docker .
+
+docker run -v <HOST-WORKSPACE>:/workspace --cap-add=SYS_PTRACE --user $(id -u $USER):$(id -g $USER) -it pastis-docker
+
+```
+
+
+
+To open another terminal to an already running container:
+
+
+
+```bash
+
+docker exec -it $(docker ps | grep 'pastis-docker' | awk '{print $1}') /bin/bash
+
+```
+
+
+
+The PASTIS Docker image has already installed all the needed dependencies such as AFL++ and Honggfuzz.
+
+
+
+---
+
+
+
 ## Papers and conference
 
 
 
 * **Symbolic Execution the Swiss-Knife of the Reverse Engineer Toolbox**  
 
   **Venue**: KLEE Workshop, 2022 [[:books:]](https://srg.doc.ic.ac.uk/klee22/talks/David-Reverse-Engineering.pdf) [[:movie_camera:]](https://youtu.be/PNbNtTa5Sp4)
```

### Comparing `pastis-framework-1.0.1/pastis_framework.egg-info/SOURCES.txt` & `pastis-framework-1.0.2/pastis_framework.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/pastisbenchmark/models.py` & `pastis-framework-1.0.2/pastisbenchmark/models.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/pastisbenchmark/plotter.py` & `pastis-framework-1.0.2/pastisbenchmark/plotter.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/pastisbenchmark/replayer.py` & `pastis-framework-1.0.2/pastisbenchmark/replayer.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/pastisbenchmark/results.py` & `pastis-framework-1.0.2/pastisbenchmark/results.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/pastisbroker/broker.py` & `pastis-framework-1.0.2/pastisbroker/broker.py`

 * *Files 10% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 from enum import Enum
 from collections import Counter
 import datetime
 import random
 
 # Third-party imports
 import psutil
-from libpastis import BrokerAgent, FuzzingEngineDescriptor, EngineConfiguration, BinaryPackage, SASTReport
+from libpastis import BrokerAgent, FuzzingEngineDescriptor, EngineConfiguration, BinaryPackage, SASTReport, ClientAgent
 from libpastis.types import SeedType, FuzzingEngineInfo, LogLevel, Arch, State, SeedInjectLoc, CheckMode, CoverageMode, \
                             ExecMode, AlertData, PathLike, Platform, FuzzMode
 import lief
 from tritondse import QuokkaProgram
 
 # Local imports
 from pastisbroker.client import PastisClient
@@ -43,25 +43,25 @@
     WARNING = '\033[93m'
     FAIL = '\033[91m'
     ENDC = '\033[0m'
     BOLD = '\033[1m'
     UNDERLINE = '\033[4m'
 
 
-
 class PastisBroker(BrokerAgent):
 
     def __init__(self, workspace: PathLike,
                  binaries_dir: PathLike,
                  broker_mode: BrokingMode,
                  check_mode: CheckMode = CheckMode.CHECK_ALL,
                  inject_loc: SeedInjectLoc = SeedInjectLoc.STDIN,
                  sast_report: PathLike = None,
                  p_argv: List[str] = None,
-                 memory_threshold: int = 85):
+                 memory_threshold: int = 85,
+                 start_quorum: int = 0):
         super(PastisBroker, self).__init__()
 
         # Initialize workspace
         self.workspace = Workspace(Path(workspace))
         params = {"binaries_dir": str(Path(binaries_dir).absolute()),
                   "broker_mode": broker_mode.name,
                   "check_mode": check_mode.name,
@@ -111,14 +111,22 @@
         # Create the stat manager
         self.statmanager = StatManager(self.workspace)
 
         # Watchdog to monitor RAM usage
         self.watchdog = None
         self._threshold = memory_threshold # percent
 
+        # startup quorum
+        self._startup_quorum = start_quorum
+        self._current_quorum = 0
+
+        # Proxy feature
+        self._proxy = None
+        self._proxy_cli = None
+
     def load_engine_addon(self, py_module: str) -> bool:
         desc = load_engine_descriptor(py_module)
         if desc is not None:
             self.engines[desc.NAME] = desc
             self.engines_args[desc.NAME] = []
             return True
         else:
@@ -129,23 +137,23 @@
         self.workspace.add_sast_report(self.sast_report)
         self.workspace.initialize_alert_corpus(self.sast_report)
 
     @property
     def running(self) -> bool:
         return self._running
 
-    def iter_other_clients(self, client: PastisClient) -> Generator[PastisClient, None, None]:
+    def iter_other_clients(self, cli_id: bytes) -> Generator[PastisClient, None, None]:
         """
         Generator of all clients but the one given in parameter
 
-        :param client: PastisClient client to ignore
+        :param cli_id: netid of the client to ignore
         :return: Generator of PastisClient object
         """
         for c in self.clients.values():
-            if c.netid != client.netid:
+            if c.netid != cli_id:
                 yield c
 
     def new_uid(self) -> int:
         """
         Generate a new unique id for a client (int)
 
         :return: int, unique (in an execution)
@@ -182,59 +190,77 @@
         is_new = seed not in self._seed_pool
         h = md5(seed).hexdigest()
 
         # Show log message and save seed to file
         self.statmanager.update_seed_stat(cli, typ)  # Add info only if new
         cli.log(LogLevel.INFO, f"seed {h} [{self._colored_seed_type(typ)}][{self._colored_seed_newness(is_new)}]")
         cli.add_own_seed(seed)  # Add seed in client's seed
-        self.write_seed(typ, cli, seed) # Write seed to file
+        self.write_seed(typ, cli.strid, seed) # Write seed to file
 
         if is_new:
             self._seed_pool[seed] = typ  # Save it in the local pool
         else:
             pass
             # logging.warning(f"receive duplicate seed {h} by {cli.strid}")
 
         # Iterate on all clients and send it to whomever never received it
         if self.broker_mode == BrokingMode.FULL:
-            for c in self.iter_other_clients(cli):
-                if c.is_new_seed(seed):
-                    self.send_seed(c.netid, typ, seed)  # send the seed to the client
-                    c.add_peer_seed(seed)  # Add it in its list of seed
+            self.send_seed_to_all_others(cli.netid, typ, seed)
+
+        if self.is_proxied:  # Forward it to the proxy
+            self._proxy.send_seed(typ, seed)
+
+    def send_seed_to_all_others(self, origin_id: bytes, typ: SeedType, seed: bytes) -> None:
+        for c in self.iter_other_clients(origin_id):
+            if c.is_new_seed(seed):
+                self.send_seed(c.netid, typ, seed)  # send the seed to the client
+                c.add_peer_seed(seed)  # Add it in its list of seed
 
     def add_seed_file(self, file: PathLike, initial: bool = False) -> None:
         p = Path(file)
         logging.info(f"Add seed {p.name} in pool")
         # Save seed in the workspace
         self.workspace.save_seed_file(SeedType.INPUT, p, initial)
 
         seed = p.read_bytes()
         self._seed_pool[seed] = SeedType.INPUT
         if initial:
             self._init_seed_pool[seed] = SeedType.INPUT
 
-    def write_seed(self, typ: SeedType, from_cli: PastisClient, seed: bytes):
+    def write_seed(self, typ: SeedType, cli_id: str, seed: bytes):
         t = time.strftime("%Y-%m-%d_%H:%M:%S", time.localtime())
         elapsed = str(datetime.timedelta(seconds=time.time() - self._start_time)).replace(" day, ", "d:").replace(" days, ", "d:")
-        fname = f"{t}_{elapsed}_{from_cli.strid}_{md5(seed).hexdigest()}.cov"
+        fname = f"{t}_{elapsed}_{cli_id}_{md5(seed).hexdigest()}.cov"
         self.workspace.save_seed(typ, fname, seed)
 
     def hello_received(self, cli_id: bytes, engines: List[FuzzingEngineInfo], arch: Arch, cpus: int, memory: int, hostname: str, platform: Platform):
         uid = self.new_uid()
         client = PastisClient(uid, cli_id, engines, arch, cpus, memory, hostname, platform)
         logging.info(f"[{client.strid}] [HELLO] Name:{hostname} Arch:{arch.name} engines:{[x.name for x in engines]} (cpu:{cpus}, mem:{memory})")
         self.clients[client.netid] = client
 
         # Load engines if they are not (lazy loading)
         for eng in engines:
             if eng.name not in self.engines:
                 self.load_engine_addon(eng.pymodule)
 
-        if self.running: # A client is coming in the middle of a session
-            self.start_client_and_send_corpus(client)
+        if self.running:  # A client is coming in the middle of a session
+            if self._startup_quorum:
+                self._current_quorum += 1
+                if self._current_quorum >= self._startup_quorum:
+                    logging.info(
+                        f"client number quorum ({self._current_quorum}/{self._startup_quorum}) reached, start all of them")
+                    self.start_pending_clients()  # start all pending clients (including the one triggering this func)
+                else:
+                    # Put the client on-hold to wait for quorum
+                    logging.info(f"client {client.strid} on-hold, wait quorum ({self._current_quorum}/{self._startup_quorum})")
+            else:  # there is no quorum so start immediately
+                self.start_client_and_send_corpus(client)
+        else:
+            pass  # Client connection is kept in clients dict for later
 
     def _transmit_pool(self, client, pool) -> None:
         for seed, typ in pool.items():
             self.send_seed(client.netid, typ, seed)  # necessarily a new seed
             client.add_peer_seed(seed)  # Add it in its list of seed
 
     def log_received(self, cli_id: bytes, level: LogLevel, message: str):
@@ -336,20 +362,32 @@
             logging.info(f"Send stop to {client.strid}")
             self.send_stop(client.netid)
         self._stop = True
 
         # Call the statmanager to wrap-up values
         self.statmanager.post_execution(list(self.clients.values()), self.workspace)
 
+        if self.is_proxied:
+            self._proxy.stop()
+
         if self.sast_report:  # If a SAST report was loaded
             # Write the final CSV in the workspace
             self.sast_report.write_csv(self.workspace.csv_result_file)
             # And also re-write the Klocwork report (that also contains resutls)
             self.sast_report.write(self.workspace.sast_report_file)
 
+    def start_pending_clients(self) -> None:
+        """
+        Start clients that connected but for which we did not yet send a response.
+        """
+        # Send the start message to all clients (already connected)
+        for c in self.clients.values():
+            if not c.is_running():
+                self.start_client_and_send_corpus(c)
+
     def start_client_and_send_corpus(self, client: PastisClient) -> None:
         self.start_client(client)
         # Iterate all the seed pool and send it to the client
         if self.broker_mode == BrokingMode.FULL:
             self._transmit_pool(client, self._seed_pool)
         elif self.broker_mode == BrokingMode.NO_TRANSMIT:
             self._transmit_pool(client, self._init_seed_pool)
@@ -419,15 +457,14 @@
                     logging.info(f"will start client {client.strid} to target 0x{addr:x}")
                 else:
                     logging.error(f"No alert target for binary package {package.name}")
             else:
                 logging.error(f"In mode {self.ck_mode} but the binary package is not a QBinExport")
                 return
 
-
         # Update internal client info and send him the message
         engine_args_str = engine_args.to_str() if engine_args else ""
         logging.info(f"send start client {client.id}: {package.name} [{engine.NAME}, {covmode.name}, {fuzzmod.name}, {exmode.name}]")
         client.set_running(package.name, engine, covmode, exmode, self.ck_mode, engine_args_str)
         client.configure_logger(self.workspace.log_directory, random.choice(COLORS))  # Assign custom color client
 
         self.send_start(client.netid,
@@ -439,15 +476,14 @@
                         self.ck_mode,
                         covmode,
                         FuzzingEngineInfo(engine.NAME, engine.VERSION, ""),
                         engine_args_str,
                         self.inject,
                         self.sast_report.to_json() if self.sast_report else b"")
 
-
     def _find_configuration(self, engine: FuzzingEngineDescriptor) -> Optional[EngineConfiguration]:
         """
         Find a configuration for the engine. It will iterate all configuration
         available or automatically balance de configuration if there is multiple of
         them
         :param engine:
         :return:
@@ -495,19 +531,21 @@
     def start(self, running: bool = True):
         super(PastisBroker, self).start()  # Start the listening thread
         self._start_time = time.time()
         self._running = running
         self.workspace.status = WorkspaceStatus.RUNNING
         logging.info("start broking")
 
-        # Send the start message to all clients
-        if self._running:  # If we want to run now (cmdline mode)
-            for c in self.clients.values():
-                if not c.is_running():
-                    self.start_client(c)
+        if self.is_proxied and self._proxy_cli:
+            self._running = False  # disable running wait start broker
+            self._proxy.send_hello([self._proxy_cli])
+        else:
+            # Send the start message to all clients (already connected)
+            if self._running:  # If we want to run now (cmdline mode)
+                self.start_pending_clients()
 
     def run(self, timeout: int = None):
         self.start()
         last_t = time.time()
 
         # Start infinite loop
         try:
@@ -629,7 +667,58 @@
     def _check_memory_usage(self) -> bool:
         mem = psutil.virtual_memory()
         logging.info(f"RAM usage: {mem.percent:.2f}%")
         if mem.percent >= self._threshold:
             logging.warning(f"Threshold reached: {mem.percent}%")
             return False
         return True
+
+    @property
+    def is_proxied(self) -> bool:
+        """
+        Get if the broker as a proxy to another broker.
+        """
+        return self._proxy is not None
+
+    def set_proxy(self, ip: str, port: int, py_module: str) -> bool:
+        self._proxy = ClientAgent()
+
+        # Load the engine info to impersonate
+        desc = load_engine_descriptor(py_module)
+        if desc is None:
+            logging.error("Cannot load FuzzingEngineDescriptor")
+            return False
+        else:
+            self._proxy_cli = FuzzingEngineInfo(desc.NAME, desc.VERSION, py_module)
+
+        self._proxy.register_start_callback(self._proxy_start_received)
+        self._proxy.register_seed_callback(self._proxy_seed_received)
+        self._proxy.register_stop_callback(self._proxy_stop_received)
+
+        logging.info(f"connect to broker {ip}:{port}")
+        self._proxy.connect(ip, port)
+        self._proxy.start()
+
+    def _proxy_start_received(self, fname: str, binary: bytes, engine: FuzzingEngineInfo, exmode: ExecMode,
+                              fuzzmode: FuzzMode, chkmode: CheckMode, covmode: CoverageMode, seed_inj: SeedInjectLoc,
+                              engine_args: str, argv: List[str], sast_report: str = None):
+        # FIXME: Use parameters received
+        logging.info("[PROXY] start received !")
+        self._running = True
+        if self._running:
+            self.start_pending_clients()
+
+    def _proxy_seed_received(self, typ: SeedType, seed: bytes):
+        # Forward the seed to underlying clients
+        logging.info(f"[PROXY] seed {typ.name} received forward to agents")
+
+        # Save the seed locally
+        self.write_seed(typ, "PROXY", seed)
+        self._seed_pool[seed] = typ  # add it to the pool
+        self._init_seed_pool[seed] = typ  # also consider it as initial corpus
+
+        # Forward it to all clients
+        self.send_seed_to_all_others(b"PROXY", typ, seed)
+
+    def _proxy_stop_received(self):
+        logging.info(f"[PROXY] stop received!")
+        self._stop = True
```

### Comparing `pastis-framework-1.0.1/pastisbroker/client.py` & `pastis-framework-1.0.2/pastisbroker/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -78,15 +78,14 @@
             hldr.setFormatter(logging.Formatter("%(asctime)s [%(levelname)s]: %(message)s"))
             self.logger.addHandler(hldr)
 
     @property
     def strid(self):
         return f"CLI-{self.id}-{self._engine.SHORT_NAME if self._engine else 'N/A'}"
 
-
     def is_new_seed(self, seed: bytes) -> bool:
         """
         Return true if the seed has never been sent to a client
 
         :param seed: seed bytes
         :return: True if never sent to client
         """
```

### Comparing `pastis-framework-1.0.1/pastisbroker/stat_manager.py` & `pastis-framework-1.0.2/pastisbroker/stat_manager.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/pastisbroker/utils.py` & `pastis-framework-1.0.2/pastisbroker/utils.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/pastisbroker/workspace.py` & `pastis-framework-1.0.2/pastisbroker/workspace.py`

 * *Files identical despite different names*

### Comparing `pastis-framework-1.0.1/setup.py` & `pastis-framework-1.0.2/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 with open("README.md") as f:
     lines = f.readlines()
     README = "\n".join(lines[4:7]+lines[51:])
 
 
 setup(
     name="pastis-framework",
-    version="1.0.1",
+    version="1.0.2",
     description="PASTIS framework for collaborative fuzzing",
     long_description=README,
     long_description_content_type='text/markdown',
     packages=[
         "libpastis",
         "libpastis.proto",
         "pastisbroker",
```


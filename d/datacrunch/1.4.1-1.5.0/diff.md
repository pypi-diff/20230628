# Comparing `tmp/datacrunch-1.4.1.tar.gz` & `tmp/datacrunch-1.5.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "datacrunch-1.4.1.tar", last modified: Tue Jun 20 13:53:07 2023, max compression
+gzip compressed data, was "datacrunch-1.5.0.tar", last modified: Wed Jun 28 06:59:25 2023, max compression
```

## Comparing `datacrunch-1.4.1.tar` & `datacrunch-1.5.0.tar`

### file list

```diff
@@ -1,90 +1,91 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/
--rw-r--r--   0 runner    (1001) docker     (123)     1069 2023-06-20 13:52:42.000000 datacrunch-1.4.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     5682 2023-06-20 13:53:07.079662 datacrunch-1.4.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     4759 2023-06-20 13:52:42.000000 datacrunch-1.4.1/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.075662 datacrunch-1.4.1/datacrunch/
--rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/__version__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.075662 datacrunch-1.4.1/datacrunch/authentication/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/authentication/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3589 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/authentication/authentication.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.075662 datacrunch-1.4.1/datacrunch/balance/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/balance/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1240 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/balance/balance.py
--rw-r--r--   0 runner    (1001) docker     (123)     2165 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/constants.py
--rw-r--r--   0 runner    (1001) docker     (123)     2698 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/datacrunch.py
--rw-r--r--   0 runner    (1001) docker     (123)      781 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/exceptions.py
--rw-r--r--   0 runner    (1001) docker     (123)      634 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/helpers.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.075662 datacrunch-1.4.1/datacrunch/http_client/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/http_client/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6701 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/http_client/http_client.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.075662 datacrunch-1.4.1/datacrunch/images/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/images/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/images/images.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.075662 datacrunch-1.4.1/datacrunch/instance_types/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/instance_types/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4732 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/instance_types/instance_types.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.075662 datacrunch-1.4.1/datacrunch/instances/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/instances/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14236 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/instances/instances.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.075662 datacrunch-1.4.1/datacrunch/ssh_keys/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/ssh_keys/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2907 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/ssh_keys/ssh_keys.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/datacrunch/startup_scripts/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/startup_scripts/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3172 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/startup_scripts/startup_scripts.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/datacrunch/volume_types/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/volume_types/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1828 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/volume_types/volume_types.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/datacrunch/volumes/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/volumes/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11307 2023-06-20 13:52:42.000000 datacrunch-1.4.1/datacrunch/volumes/volumes.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.075662 datacrunch-1.4.1/datacrunch.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     5682 2023-06-20 13:53:07.000000 datacrunch-1.4.1/datacrunch.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2188 2023-06-20 13:53:07.000000 datacrunch-1.4.1/datacrunch.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-20 13:53:07.000000 datacrunch-1.4.1/datacrunch.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      122 2023-06-20 13:53:07.000000 datacrunch-1.4.1/datacrunch.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-20 13:53:07.000000 datacrunch-1.4.1/datacrunch.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-20 13:53:07.079662 datacrunch-1.4.1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1468 2023-06-20 13:52:42.000000 datacrunch-1.4.1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/tests/integration_tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/integration_tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      546 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/integration_tests/conftest.py
--rw-r--r--   0 runner    (1001) docker     (123)     2565 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/integration_tests/test_volumes.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/tests/unit_tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/tests/unit_tests/authentication/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/authentication/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7490 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/authentication/test_authentication.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/tests/unit_tests/balance/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/balance/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      651 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/balance/test_balance.py
--rw-r--r--   0 runner    (1001) docker     (123)      512 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/conftest.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/tests/unit_tests/http_client/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/http_client/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6776 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/http_client/test_http_client.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/tests/unit_tests/images/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/images/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1204 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/images/test_images.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/tests/unit_tests/instance_types/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/instance_types/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3178 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/instance_types/test_instance_types.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/tests/unit_tests/instances/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/instances/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16748 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/instances/test_instances.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/tests/unit_tests/ssh_keys/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/ssh_keys/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5741 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/ssh_keys/test_ssh_keys.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/tests/unit_tests/startup_scripts/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/startup_scripts/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6039 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/startup_scripts/test_startup_scripts.py
--rw-r--r--   0 runner    (1001) docker     (123)     2090 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/test_datacrunch.py
--rw-r--r--   0 runner    (1001) docker     (123)      891 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/test_exceptions.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/tests/unit_tests/volume_types/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/volume_types/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1386 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/volume_types/test_volume_types.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-20 13:53:07.079662 datacrunch-1.4.1/tests/unit_tests/volumes/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/volumes/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20591 2023-06-20 13:52:42.000000 datacrunch-1.4.1/tests/unit_tests/volumes/test_volumes.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.865491 datacrunch-1.5.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1069 2023-06-28 06:59:17.000000 datacrunch-1.5.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     5682 2023-06-28 06:59:25.861491 datacrunch-1.5.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4759 2023-06-28 06:59:17.000000 datacrunch-1.5.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.857491 datacrunch-1.5.0/datacrunch/
+-rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/__version__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/datacrunch/authentication/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/authentication/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3589 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/authentication/authentication.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/datacrunch/balance/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/balance/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1240 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/balance/balance.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2351 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2698 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/datacrunch.py
+-rw-r--r--   0 runner    (1001) docker     (123)      781 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/exceptions.py
+-rw-r--r--   0 runner    (1001) docker     (123)      634 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/helpers.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/datacrunch/http_client/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/http_client/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6701 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/http_client/http_client.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/datacrunch/images/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/images/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/images/images.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/datacrunch/instance_types/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/instance_types/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4732 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/instance_types/instance_types.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/datacrunch/instances/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/instances/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14335 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/instances/instances.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/datacrunch/ssh_keys/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/ssh_keys/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2907 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/ssh_keys/ssh_keys.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/datacrunch/startup_scripts/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/startup_scripts/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3172 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/startup_scripts/startup_scripts.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/datacrunch/volume_types/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/volume_types/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1828 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/volume_types/volume_types.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/datacrunch/volumes/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/volumes/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11347 2023-06-28 06:59:17.000000 datacrunch-1.5.0/datacrunch/volumes/volumes.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/datacrunch.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     5682 2023-06-28 06:59:25.000000 datacrunch-1.5.0/datacrunch.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2230 2023-06-28 06:59:25.000000 datacrunch-1.5.0/datacrunch.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 06:59:25.000000 datacrunch-1.5.0/datacrunch.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      122 2023-06-28 06:59:25.000000 datacrunch-1.5.0/datacrunch.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 06:59:25.000000 datacrunch-1.5.0/datacrunch.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 06:59:25.865491 datacrunch-1.5.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1468 2023-06-28 06:59:17.000000 datacrunch-1.5.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/tests/integration_tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/integration_tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      546 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/integration_tests/conftest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1249 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/integration_tests/test_instances.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3076 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/integration_tests/test_volumes.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/tests/unit_tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/tests/unit_tests/authentication/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/authentication/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7490 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/authentication/test_authentication.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/tests/unit_tests/balance/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/balance/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      651 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/balance/test_balance.py
+-rw-r--r--   0 runner    (1001) docker     (123)      512 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/conftest.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/tests/unit_tests/http_client/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/http_client/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6776 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/http_client/test_http_client.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/tests/unit_tests/images/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/images/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1204 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/images/test_images.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/tests/unit_tests/instance_types/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/instance_types/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3178 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/instance_types/test_instance_types.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/tests/unit_tests/instances/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/instances/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16842 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/instances/test_instances.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/tests/unit_tests/ssh_keys/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/ssh_keys/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5741 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/ssh_keys/test_ssh_keys.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/tests/unit_tests/startup_scripts/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/startup_scripts/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6039 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/startup_scripts/test_startup_scripts.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2090 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/test_datacrunch.py
+-rw-r--r--   0 runner    (1001) docker     (123)      891 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/test_exceptions.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/tests/unit_tests/volume_types/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/volume_types/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1386 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/volume_types/test_volume_types.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:25.861491 datacrunch-1.5.0/tests/unit_tests/volumes/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/volumes/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20672 2023-06-28 06:59:17.000000 datacrunch-1.5.0/tests/unit_tests/volumes/test_volumes.py
```

### Comparing `datacrunch-1.4.1/LICENSE` & `datacrunch-1.5.0/LICENSE`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/PKG-INFO` & `datacrunch-1.5.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: datacrunch
-Version: 1.4.1
+Version: 1.5.0
 Summary: Official Python SDK for DataCrunch Public API
 Home-page: https://github.com/DataCrunch-io
 Author: DataCrunch Oy
 Author-email: info@datacrunch.io
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: datacrunch Version: 1.4.1 Summary: Official Python
+Metadata-Version: 2.1 Name: datacrunch Version: 1.5.0 Summary: Official Python
 SDK for DataCrunch Public API Home-page: https://github.com/DataCrunch-io
 Author: DataCrunch Oy Author-email: info@datacrunch.io Classifier: Programming
 Language :: Python :: 3 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7 Classifier: Programming
 Language :: Python :: 3.8 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10 Classifier: Programming
 Language :: Python :: 3.11 Classifier: Development Status :: 5 - Production/
```

### Comparing `datacrunch-1.4.1/README.md` & `datacrunch-1.5.0/README.md`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/datacrunch/authentication/authentication.py` & `datacrunch-1.5.0/datacrunch/authentication/authentication.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/datacrunch/balance/balance.py` & `datacrunch-1.5.0/datacrunch/balance/balance.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/datacrunch/constants.py` & `datacrunch-1.5.0/datacrunch/constants.py`

 * *Files 8% similar despite different names*

```diff
@@ -51,14 +51,22 @@
     NVMe = "NVMe"
     HDD = "HDD"
 
     def __init__(self):
         return
 
 
+class Locations:
+    FIN_01 = "FIN-01"
+    ICE_01 = "ICE-01"
+
+    def __init__(self):
+        return
+
+
 class ErrorCodes:
     INVALID_REQUEST = "invalid_request"
     UNAUTHORIZED_REQUEST = "unauthorized_request"
     INSUFFICIENT_FUNDS = "insufficient_funds"
     FORBIDDEN_ACTION = "forbidden_action"
     NOT_FOUND = "not_found"
     SERVER_ERROR = "server_error"
@@ -81,14 +89,17 @@
 
         self.volume_status: VolumeStatus = VolumeStatus()
         """Possible volume statuses"""
 
         self.volume_types: VolumeTypes = VolumeTypes()
         """Available volume types"""
 
+        self.locations: Locations = Locations()
+        """Available locations"""
+
         self.error_codes: ErrorCodes = ErrorCodes()
         """Available error codes"""
 
         self.base_url: str = base_url
         """DataCrunch's Public API URL"""
 
         self.version: str = version
```

### Comparing `datacrunch-1.4.1/datacrunch/datacrunch.py` & `datacrunch-1.5.0/datacrunch/datacrunch.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/datacrunch/exceptions.py` & `datacrunch-1.5.0/datacrunch/exceptions.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/datacrunch/helpers.py` & `datacrunch-1.5.0/datacrunch/helpers.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/datacrunch/http_client/http_client.py` & `datacrunch-1.5.0/datacrunch/http_client/http_client.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/datacrunch/images/images.py` & `datacrunch-1.5.0/datacrunch/images/images.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/datacrunch/instance_types/instance_types.py` & `datacrunch-1.5.0/datacrunch/instance_types/instance_types.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/datacrunch/instances/instances.py` & `datacrunch-1.5.0/datacrunch/instances/instances.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,9 +1,10 @@
 from typing import List, Union, Optional, Dict
 from datacrunch.helpers import stringify_class_object_properties
+from datacrunch.constants import Locations
 
 INSTANCES_ENDPOINT = '/instances'
 
 
 class Instance:
     """An instance model class"""
 
@@ -20,15 +21,15 @@
                  ssh_key_ids: List[str],
                  cpu: dict,
                  gpu: dict,
                  memory: dict,
                  storage: dict,
                  os_volume_id: str,
                  gpu_memory: dict,
-                 location: str = "FIN1",
+                 location: str = Locations.FIN_01,
                  startup_script_id: str = None,
                  is_spot: bool = False
                  ) -> None:
         """Initialize the instance object
 
         :param id: instance id
         :type id: str
@@ -58,15 +59,15 @@
         :type memory: dict
         :param storage: storate details
         :type storage: dict
         :param id: main OS volume id
         :type id: str
         :param memory: gpu memory details
         :type memory: dict
-        :param location: datacenter location, defaults to "FIN1"
+        :param location: datacenter location, defaults to "FIN-01"
         :type location: str, optional
         :param startup_script_id: startup script id, defaults to None
         :type startup_script_id: str, optional
         :param is_spot: is this a spot instance, defaults to None
         :type is_spot: bool, optional
         """
         self._id = id
@@ -264,14 +265,15 @@
         """Returns a string of the json representation of the instance
 
         :return: json representation of the instance
         :rtype: str
         """
         return stringify_class_object_properties(self)
 
+
 class InstancesService:
     """A service for interacting with the instances endpoint"""
 
     def __init__(self, http_client) -> None:
         self._http_client = http_client
 
     def get(self, status: str = None) -> List[Instance]:
@@ -291,15 +293,16 @@
             price_per_hour=instance_dict['price_per_hour'] if 'price_per_hour' in instance_dict else None,
             location=instance_dict['location'],
             hostname=instance_dict['hostname'],
             description=instance_dict['description'],
             ip=instance_dict['ip'],
             status=instance_dict['status'],
             created_at=instance_dict['created_at'],
-            ssh_key_ids=instance_dict['ssh_key_ids'] if 'ssh_key_ids' in instance_dict else [],
+            ssh_key_ids=instance_dict['ssh_key_ids'] if 'ssh_key_ids' in instance_dict else [
+            ],
             startup_script_id=instance_dict['startup_script_id'] if 'startup_script_id' in instance_dict else None,
             cpu=instance_dict['cpu'],
             gpu=instance_dict['gpu'],
             memory=instance_dict['memory'],
             storage=instance_dict['storage'],
             os_volume_id=instance_dict['os_volume_id'] if 'os_volume_id' in instance_dict else None,
             gpu_memory=instance_dict['gpu_memory'] if 'gpu_memory' in instance_dict else None,
@@ -324,15 +327,16 @@
             price_per_hour=instance_dict['price_per_hour'] if 'price_per_hour' in instance_dict else None,
             location=instance_dict['location'],
             hostname=instance_dict['hostname'],
             description=instance_dict['description'],
             ip=instance_dict['ip'],
             status=instance_dict['status'],
             created_at=instance_dict['created_at'],
-            ssh_key_ids=instance_dict['ssh_key_ids'] if 'ssh_key_ids' in instance_dict else [],
+            ssh_key_ids=instance_dict['ssh_key_ids'] if 'ssh_key_ids' in instance_dict else [
+            ],
             startup_script_id=instance_dict['startup_script_id'] if 'startup_script_id' in instance_dict else None,
             cpu=instance_dict['cpu'],
             gpu=instance_dict['gpu'],
             memory=instance_dict['memory'],
             storage=instance_dict['storage'],
             os_volume_id=instance_dict['os_volume_id'] if 'os_volume_id' in instance_dict else None,
             gpu_memory=instance_dict['gpu_memory'] if 'gpu_memory' in instance_dict else None,
@@ -342,15 +346,15 @@
 
     def create(self,
                instance_type: str,
                image: str,
                hostname: str,
                description: str,
                ssh_key_ids: list = [],
-               location: str = "FIN1",
+               location: str = Locations.FIN_01,
                startup_script_id: str = None,
                volumes: List[Dict] = None,
                existing_volumes: List[str] = None,
                os_volume: Dict = None,
                is_spot: bool = False,
                coupon: str = None) -> Instance:
         """Creates (deploys) a new instance
@@ -361,15 +365,15 @@
         :type image: str
         :param ssh_key_ids: list of ssh key ids
         :type ssh_key_ids: list
         :param hostname: instance hostname
         :type hostname: str
         :param description: instance description
         :type description: str
-        :param location: datacenter location, defaults to "FIN1"
+        :param location: datacenter location, defaults to "FIN-01"
         :type location: str, optional
         :param startup_script_id: startup script id, defaults to None
         :type startup_script_id: str, optional
         :param volumes: List of volume data dictionaries to create alongside the instance
         :type volumes: List[Dict], optional
         :param existing_volumes: List of existing volume ids to attach to the instance
         :type existing_volumes: List[str], optional
@@ -385,15 +389,15 @@
         payload = {
             "instance_type": instance_type,
             "image": image,
             "ssh_key_ids": ssh_key_ids,
             "startup_script_id": startup_script_id,
             "hostname": hostname,
             "description": description,
-            "location": location,
+            "location_code": location,
             "os_volume": os_volume,
             "volumes": volumes,
             "existing_volumes": existing_volumes,
             "is_spot": is_spot,
             "coupon": coupon
         }
         id = self._http_client.post(INSTANCES_ENDPOINT, json=payload).text
```

### Comparing `datacrunch-1.4.1/datacrunch/ssh_keys/ssh_keys.py` & `datacrunch-1.5.0/datacrunch/ssh_keys/ssh_keys.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/datacrunch/startup_scripts/startup_scripts.py` & `datacrunch-1.5.0/datacrunch/startup_scripts/startup_scripts.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/datacrunch/volume_types/volume_types.py` & `datacrunch-1.5.0/datacrunch/volume_types/volume_types.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/datacrunch/volumes/volumes.py` & `datacrunch-1.5.0/datacrunch/volumes/volumes.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 from typing import List, Union, Optional
-from datacrunch.constants import VolumeActions
+from datacrunch.constants import VolumeActions, Locations
 from datacrunch.helpers import stringify_class_object_properties
 
 VOLUMES_ENDPOINT = '/volumes'
 
 
 class Volume:
     """A volume model class"""
@@ -13,15 +13,15 @@
                  status: str,
                  name: str,
                  size: int,
                  type: str,
                  is_os_volume: bool,
                  created_at: str,
                  target: str = None,
-                 location: str = "FIN1",
+                 location: str = Locations.FIN_01,
                  instance_id: str = None,
                  ssh_key_ids: List[str] = [],
                  deleted_at: str = None,
                  ) -> None:
         """Initialize the volume object
 
         :param id: volume id
@@ -36,15 +36,15 @@
         :type type: str
         :param is_os_volume: indication whether this is an operating systen volume
         :type is_os_volume: bool
         :param created_at: the time the volume was created (UTC)
         :type created_at: str
         :param target: target device e.g. vda
         :type target: str, optional
-        :param location: datacenter location, defaults to "FIN1"
+        :param location: datacenter location, defaults to "FIN-01"
         :type location: str, optional
         :param instance_id: the instance id the volume is attached to, None if detached
         :type instance_id: str
         :param ssh_key_ids: list of ssh keys ids
         :type ssh_key_ids: List[str]
         :param deleted_at: the time the volume was deleted (UTC), defaults to None
         :type deleted_at: str, optional
@@ -234,37 +234,37 @@
         return list(map(Volume.create_from_dict, volumes_dicts))
 
     def create(self,
                type: str,
                name: str,
                size: int,
                instance_id: str = None,
-               location: str = "FIN1",
+               location: str = Locations.FIN_01,
                ) -> Volume:
         """Create new volume
 
         :param type: volume type
         :type type: str
         :param name: volume name
         :type name: str
         :param size: volume size, in GB
         :type size: int
         :param instance_id: Instance id to be attached to, defaults to None
         :type instance_id: str, optional
-        :param location: datacenter location, defaults to "FIN1"
+        :param location: datacenter location, defaults to "FIN-01"
         :type location: str, optional
         :return: the new volume object
         :rtype: Volume
         """
         payload = {
             "type": type,
             "name": name,
             "size": size,
             "instance_id": instance_id,
-            "location": location
+            "location_code": location
         }
         id = self._http_client.post(VOLUMES_ENDPOINT, json=payload).text
         volume = self.get_by_id(id)
         return volume
 
     def attach(self, id_list: Union[List[str], str], instance_id: str) -> None:
         """Attach multiple volumes or single volume to an instance
```

### Comparing `datacrunch-1.4.1/datacrunch.egg-info/PKG-INFO` & `datacrunch-1.5.0/datacrunch.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: datacrunch
-Version: 1.4.1
+Version: 1.5.0
 Summary: Official Python SDK for DataCrunch Public API
 Home-page: https://github.com/DataCrunch-io
 Author: DataCrunch Oy
 Author-email: info@datacrunch.io
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: datacrunch Version: 1.4.1 Summary: Official Python
+Metadata-Version: 2.1 Name: datacrunch Version: 1.5.0 Summary: Official Python
 SDK for DataCrunch Public API Home-page: https://github.com/DataCrunch-io
 Author: DataCrunch Oy Author-email: info@datacrunch.io Classifier: Programming
 Language :: Python :: 3 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7 Classifier: Programming
 Language :: Python :: 3.8 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10 Classifier: Programming
 Language :: Python :: 3.11 Classifier: Development Status :: 5 - Production/
```

### Comparing `datacrunch-1.4.1/datacrunch.egg-info/SOURCES.txt` & `datacrunch-1.5.0/datacrunch.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -31,14 +31,15 @@
 datacrunch/volume_types/__init__.py
 datacrunch/volume_types/volume_types.py
 datacrunch/volumes/__init__.py
 datacrunch/volumes/volumes.py
 tests/__init__.py
 tests/integration_tests/__init__.py
 tests/integration_tests/conftest.py
+tests/integration_tests/test_instances.py
 tests/integration_tests/test_volumes.py
 tests/unit_tests/__init__.py
 tests/unit_tests/conftest.py
 tests/unit_tests/test_datacrunch.py
 tests/unit_tests/test_exceptions.py
 tests/unit_tests/authentication/__init__.py
 tests/unit_tests/authentication/test_authentication.py
```

### Comparing `datacrunch-1.4.1/setup.py` & `datacrunch-1.5.0/setup.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/tests/integration_tests/conftest.py` & `datacrunch-1.5.0/tests/integration_tests/conftest.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/tests/integration_tests/test_volumes.py` & `datacrunch-1.5.0/tests/integration_tests/test_volumes.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,22 +1,26 @@
 import os
 import pytest
 from datacrunch.datacrunch import DataCrunchClient
+from datacrunch.constants import Locations, VolumeTypes, VolumeStatus
 
 IN_GITHUB_ACTIONS = os.getenv("GITHUB_ACTIONS") == "true"
 
 
+NVMe = VolumeTypes.NVMe
+
+
 @pytest.mark.skipif(IN_GITHUB_ACTIONS, reason="Test doesn't work in Github Actions.")
 @pytest.mark.withoutresponses
 class TestVolumes():
 
     def test_get_volumes_from_trash(self, datacrunch_client: DataCrunchClient):
         # create new volume
         volume = datacrunch_client.volumes.create(
-            type=datacrunch_client.constants.volume_types.NVMe, name="test_volume", size=100)
+            type=NVMe, name="test_volume", size=100)
 
         # delete volume
         datacrunch_client.volumes.delete(volume.id)
 
         # get volumes from trash
         volumes = datacrunch_client.volumes.get_in_trash()
 
@@ -25,15 +29,15 @@
 
         # cleaning: permanently delete the volume
         datacrunch_client.volumes.delete(volume.id, is_permanent=True)
 
     def test_permanently_delete_detached_volumes(seld, datacrunch_client):
         # create new volume
         volume = datacrunch_client.volumes.create(
-            type=datacrunch_client.constants.volume_types.NVMe, name="test_volume", size=100)
+            type=NVMe, name="test_volume", size=100)
 
         # permanently delete the detached volume
         datacrunch_client.volumes.delete(volume.id, is_permanent=True)
 
         # make sure the volume is not in trash
         volumes = datacrunch_client.volumes.get_in_trash()
 
@@ -45,15 +49,15 @@
 
         # assert volume status is deleted
         assert volume.status == datacrunch_client.constants.volume_status.DELETED
 
     def test_permanently_delete_a_deleted_volume_from_trash(self, datacrunch_client):
         # create new volume
         volume = datacrunch_client.volumes.create(
-            type=datacrunch_client.constants.volume_types.NVMe, name="test_volume", size=100)
+            type=NVMe, name="test_volume", size=100)
 
         # delete volume
         datacrunch_client.volumes.delete(volume.id)
 
         # permanently delete the volume
         datacrunch_client.volumes.delete(volume.id, is_permanent=True)
 
@@ -64,7 +68,20 @@
         assert volume.status == datacrunch_client.constants.volume_status.DELETED
 
         # make sure the volume is not in trash
         volumes = datacrunch_client.volumes.get_in_trash()
 
         # assert volume is not in trash
         assert volume.id not in [v.id for v in volumes]
+
+    def test_create_volume(self, datacrunch_client):
+        # create new volume
+        volume = datacrunch_client.volumes.create(
+            type=NVMe, name="test_volume", size=100, location=Locations.FIN_01)
+
+        # assert volume is created
+        assert volume.id is not None
+        assert volume.location == Locations.FIN_01
+        assert volume.status == VolumeStatus.ORDERED or volume.status == VolumeStatus.DETACHED
+
+        # cleaning: delete volume
+        datacrunch_client.volumes.delete(volume.id, is_permanent=True)
```

### Comparing `datacrunch-1.4.1/tests/unit_tests/authentication/test_authentication.py` & `datacrunch-1.5.0/tests/unit_tests/authentication/test_authentication.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/tests/unit_tests/balance/test_balance.py` & `datacrunch-1.5.0/tests/unit_tests/balance/test_balance.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/tests/unit_tests/conftest.py` & `datacrunch-1.5.0/tests/unit_tests/conftest.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/tests/unit_tests/http_client/test_http_client.py` & `datacrunch-1.5.0/tests/unit_tests/http_client/test_http_client.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/tests/unit_tests/images/test_images.py` & `datacrunch-1.5.0/tests/unit_tests/images/test_images.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/tests/unit_tests/instance_types/test_instance_types.py` & `datacrunch-1.5.0/tests/unit_tests/instance_types/test_instance_types.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/tests/unit_tests/instances/test_instances.py` & `datacrunch-1.5.0/tests/unit_tests/instances/test_instances.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 import pytest
 import responses  # https://github.com/getsentry/responses
 
 from datacrunch.exceptions import APIException
 from datacrunch.instances.instances import InstancesService, Instance
-from datacrunch.constants import Actions, ErrorCodes
+from datacrunch.constants import Actions, ErrorCodes, Locations
 
 INVALID_REQUEST = ErrorCodes.INVALID_REQUEST
 INVALID_REQUEST_MESSAGE = 'Your existence is invalid'
 
 INSTANCE_ID = 'deadc0de-a5d2-4972-ae4e-d429115d055b'
 SSH_KEY_ID = '12345dc1-a5d2-4972-ae4e-d429115d055b'
 OS_VOLUME_ID = '46fc0247-8f65-4d8a-ad73-852a8b3dc1d3'
 
 INSTANCE_TYPE = "1V100.6V"
 INSTANCE_IMAGE = "fastai"
 INSTANCE_HOSTNAME = "I'll be your host for today"
 INSTANCE_DESCRIPTION = "hope you enjoy your GPU"
 INSTANCE_STATUS = 'running'
 INSTANCE_PRICE_PER_HOUR = 0.60
-INSTANCE_LOCATION = 'FIN1'
+INSTANCE_LOCATION = Locations.FIN_01
 INSTANCE_IP = '1.2.3.4'
 INSTANCE_CREATED_AT = "whatchalookingatboy?"
 INSTANCE_OS_VOLUME = {"name": "os volume", "size": 50}
 
 PAYLOAD = [
     {
         "created_at": INSTANCE_CREATED_AT,
@@ -59,14 +59,15 @@
         "os_volume_id": OS_VOLUME_ID
     }
 ]
 
 PAYLOAD_SPOT = PAYLOAD
 PAYLOAD_SPOT[0]["is_spot"] = True
 
+
 class TestInstancesService:
     @pytest.fixture
     def instances_service(self, http_client):
         return InstancesService(http_client)
 
     @pytest.fixture
     def endpoint(self, http_client):
@@ -393,15 +394,16 @@
         responses.add(
             responses.PUT,
             url,
             status=202
         )
 
         # act
-        result = instances_service.action(id_list=[INSTANCE_ID], action=Actions.SHUTDOWN)
+        result = instances_service.action(
+            id_list=[INSTANCE_ID], action=Actions.SHUTDOWN)
 
         # assert
         assert result is None
         assert responses.assert_call_count(url, 1) is True
 
     def test_action_failed(self, instances_service, endpoint):
         # arrange - add response mock
@@ -411,24 +413,26 @@
             url,
             json={"code": INVALID_REQUEST, "message": INVALID_REQUEST_MESSAGE},
             status=400
         )
 
         # act
         with pytest.raises(APIException) as excinfo:
-            instances_service.action(id_list=[INSTANCE_ID], action="fluxturcate")
+            instances_service.action(
+                id_list=[INSTANCE_ID], action="fluxturcate")
 
         # assert
         assert excinfo.value.code == INVALID_REQUEST
         assert excinfo.value.message == INVALID_REQUEST_MESSAGE
         assert responses.assert_call_count(url, 1) is True
 
     def test_is_available_successful(self, instances_service):
         # arrange - add response mock
-        url = instances_service._http_client._base_url + '/instance-availability/' + INSTANCE_TYPE
+        url = instances_service._http_client._base_url + \
+            '/instance-availability/' + INSTANCE_TYPE
         responses.add(
             responses.GET,
             url,
             json=True,
             status=200
         )
 
@@ -437,24 +441,26 @@
 
         # assert
         assert is_available is True
         assert responses.assert_call_count(url, 1) is True
 
     def test_is_spot_available_successful(self, instances_service):
         # arrange - add response mock
-        url = instances_service._http_client._base_url + '/instance-availability/' + INSTANCE_TYPE + '?isSpot=true'
+        url = instances_service._http_client._base_url + \
+            '/instance-availability/' + INSTANCE_TYPE + '?isSpot=true'
         responses.add(
             responses.GET,
             url,
             json=True,
             status=200
         )
 
         # act
-        is_available = instances_service.is_available(INSTANCE_TYPE, is_spot=True)
+        is_available = instances_service.is_available(
+            INSTANCE_TYPE, is_spot=True)
 
         # assert
         assert is_available is True
         assert responses.assert_call_count(url, 1) is True
 
     def test_is_available_failed(self, instances_service):
         # arrange - add response mock
@@ -469,8 +475,8 @@
         # act
         with pytest.raises(APIException) as excinfo:
             instances_service.is_available('x')
 
         # assert
         assert excinfo.value.code == INVALID_REQUEST
         assert excinfo.value.message == INVALID_REQUEST_MESSAGE
-        assert responses.assert_call_count(url, 1) is True
+        assert responses.assert_call_count(url, 1) is True
```

### Comparing `datacrunch-1.4.1/tests/unit_tests/ssh_keys/test_ssh_keys.py` & `datacrunch-1.5.0/tests/unit_tests/ssh_keys/test_ssh_keys.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/tests/unit_tests/startup_scripts/test_startup_scripts.py` & `datacrunch-1.5.0/tests/unit_tests/startup_scripts/test_startup_scripts.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/tests/unit_tests/test_datacrunch.py` & `datacrunch-1.5.0/tests/unit_tests/test_datacrunch.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/tests/unit_tests/test_exceptions.py` & `datacrunch-1.5.0/tests/unit_tests/test_exceptions.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/tests/unit_tests/volume_types/test_volume_types.py` & `datacrunch-1.5.0/tests/unit_tests/volume_types/test_volume_types.py`

 * *Files identical despite different names*

### Comparing `datacrunch-1.4.1/tests/unit_tests/volumes/test_volumes.py` & `datacrunch-1.5.0/tests/unit_tests/volumes/test_volumes.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,20 +1,19 @@
 import pytest
 import responses  # https://github.com/getsentry/responses
 
 from datacrunch.exceptions import APIException
 from datacrunch.volumes.volumes import VolumesService, Volume
-from datacrunch.constants import VolumeStatus, VolumeTypes, VolumeActions, ErrorCodes
+from datacrunch.constants import VolumeStatus, VolumeTypes, VolumeActions, ErrorCodes, Locations
 
 INVALID_REQUEST = ErrorCodes.INVALID_REQUEST
 INVALID_REQUEST_MESSAGE = 'Your existence is invalid'
 
 INSTANCE_ID = "4fee633c-b119-4447-af9c-70ba17675fc5"
 
-FIN1 = "FIN1"
 NVME = "NVMe"
 HDD = "HDD"
 TARGET_VDA = "vda"
 SSH_KEY_ID = '12345dc1-a5d2-4972-ae4e-d429115d055b'
 
 NVME_VOL_ID = "cf995e26-ce69-4149-84a3-cdd1e100670f"
 NVME_VOL_STATUS = VolumeStatus.ATTACHED
@@ -35,29 +34,29 @@
 NVME_VOLUME = {
     "id": NVME_VOL_ID,
     "status": NVME_VOL_STATUS,
     "instance_id": INSTANCE_ID,
     "name": NVME_VOL_NAME,
     "size": NVME_VOL_SIZE,
     "type": NVME,
-    "location": FIN1,
+    "location": Locations.FIN_01,
     "is_os_volume": True,
     "created_at": NVME_VOL_CREATED_AT,
     "target": TARGET_VDA,
     "ssh_key_ids": SSH_KEY_ID
 }
 
 HDD_VOLUME = {
     "id": HDD_VOL_ID,
     "status": HDD_VOL_STATUS,
     "instance_id": None,
     "name": HDD_VOL_NAME,
     "size": HDD_VOL_SIZE,
     "type": HDD,
-    "location": FIN1,
+    "location": Locations.FIN_01,
     "is_os_volume": False,
     "created_at": HDD_VOL_CREATED_AT,
     "target": None,
     "ssh_key_ids": []
 }
 
 PAYLOAD = [NVME_VOLUME, HDD_VOLUME]
@@ -78,15 +77,15 @@
 
         assert volume.id == RANDOM_VOL_ID
         assert volume.status == VolumeStatus.DETACHED
         assert volume.instance_id == None
         assert volume.name == HDD_VOL_NAME
         assert volume.size == HDD_VOL_SIZE
         assert volume.type == HDD
-        assert volume.location == FIN1
+        assert volume.location == Locations.FIN_01
         assert volume.is_os_volume == False
         assert volume.created_at == HDD_VOL_CREATED_AT
         assert volume.target == None
         assert volume.ssh_key_ids == []
 
     def test_get_volumes(self, volumes_service, endpoint):
         # arrange - add response mock
@@ -109,27 +108,27 @@
         assert type(volume_hdd) == Volume
         assert volume_nvme.id == NVME_VOL_ID
         assert volume_nvme.status == NVME_VOL_STATUS
         assert volume_nvme.instance_id == INSTANCE_ID
         assert volume_nvme.name == NVME_VOL_NAME
         assert volume_nvme.size == NVME_VOL_SIZE
         assert volume_nvme.type == NVME
-        assert volume_nvme.location == FIN1
+        assert volume_nvme.location == Locations.FIN_01
         assert volume_nvme.is_os_volume
         assert volume_nvme.created_at == NVME_VOL_CREATED_AT
         assert volume_nvme.target == TARGET_VDA
         assert volume_nvme.ssh_key_ids == SSH_KEY_ID
 
         assert volume_hdd.id == HDD_VOL_ID
         assert volume_hdd.status == HDD_VOL_STATUS
         assert volume_hdd.instance_id is None
         assert volume_hdd.name == HDD_VOL_NAME
         assert volume_hdd.size == HDD_VOL_SIZE
         assert volume_hdd.type == HDD
-        assert volume_hdd.location == FIN1
+        assert volume_hdd.location == Locations.FIN_01
         assert volume_hdd.is_os_volume is False
         assert volume_hdd.created_at == HDD_VOL_CREATED_AT
         assert volume_hdd.target is None
         assert volume_hdd.ssh_key_ids == []
 
     def test_get_volumes_by_status_successful(self, volumes_service, endpoint):
         # arrange - add response mock
@@ -150,15 +149,15 @@
         assert type(volume_nvme) == Volume
         assert volume_nvme.id == NVME_VOL_ID
         assert volume_nvme.status == NVME_VOL_STATUS
         assert volume_nvme.instance_id == INSTANCE_ID
         assert volume_nvme.name == NVME_VOL_NAME
         assert volume_nvme.size == NVME_VOL_SIZE
         assert volume_nvme.type == NVME
-        assert volume_nvme.location == FIN1
+        assert volume_nvme.location == Locations.FIN_01
         assert volume_nvme.is_os_volume
         assert volume_nvme.created_at == NVME_VOL_CREATED_AT
         assert volume_nvme.target == TARGET_VDA
 
     def test_get_volumes_by_status_failed(self, volumes_service, endpoint):
         url = endpoint + "?status=flummoxed"
         responses.add(
@@ -194,15 +193,15 @@
         assert type(volume_nvme) == Volume
         assert volume_nvme.id == NVME_VOL_ID
         assert volume_nvme.status == NVME_VOL_STATUS
         assert volume_nvme.instance_id == INSTANCE_ID
         assert volume_nvme.name == NVME_VOL_NAME
         assert volume_nvme.size == NVME_VOL_SIZE
         assert volume_nvme.type == NVME
-        assert volume_nvme.location == FIN1
+        assert volume_nvme.location == Locations.FIN_01
         assert volume_nvme.is_os_volume
         assert volume_nvme.created_at == NVME_VOL_CREATED_AT
         assert volume_nvme.target == TARGET_VDA
 
     def test_get_volume_by_id_failed(self, volumes_service, endpoint):
         # arrange - add response mock
         url = endpoint + "/x"
```


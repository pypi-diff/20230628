# Comparing `tmp/skops-0.7.post0.tar.gz` & `tmp/skops-0.8.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "skops-0.7.post0.tar", last modified: Wed Jun  7 18:55:57 2023, max compression
+gzip compressed data, was "skops-0.8.0.tar", last modified: Wed Jun 28 10:02:55 2023, max compression
```

## Comparing `skops-0.7.post0.tar` & `skops-0.8.0.tar`

### file list

```diff
@@ -1,61 +1,74 @@
-drwxr-xr-x   0 adrin     (1000) adrin     (1000)        0 2023-06-07 18:55:57.182957 skops-0.7.post0/
--rw-r--r--   0 adrin     (1000) adrin     (1000)     1084 2023-01-24 13:44:03.000000 skops-0.7.post0/LICENSE
--rw-r--r--   0 adrin     (1000) adrin     (1000)       74 2023-01-24 13:44:03.000000 skops-0.7.post0/MANIFEST.in
--rw-r--r--   0 adrin     (1000) adrin     (1000)     4541 2023-06-07 18:55:57.182957 skops-0.7.post0/PKG-INFO
--rw-r--r--   0 adrin     (1000) adrin     (1000)     3090 2023-06-07 10:00:53.000000 skops-0.7.post0/README.rst
--rw-r--r--   0 adrin     (1000) adrin     (1000)     1379 2023-06-07 08:45:53.000000 skops-0.7.post0/pyproject.toml
--rw-r--r--   0 adrin     (1000) adrin     (1000)       94 2023-06-07 18:55:57.182957 skops-0.7.post0/setup.cfg
--rw-r--r--   0 adrin     (1000) adrin     (1000)     2976 2023-06-07 18:55:29.000000 skops-0.7.post0/setup.py
-drwxr-xr-x   0 adrin     (1000) adrin     (1000)        0 2023-06-07 18:55:57.176290 skops-0.7.post0/skops/
--rw-r--r--   0 adrin     (1000) adrin     (1000)     1091 2023-06-07 18:55:44.000000 skops-0.7.post0/skops/__init__.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     2412 2023-04-03 09:57:14.000000 skops-0.7.post0/skops/_min_dependencies.py
-drwxr-xr-x   0 adrin     (1000) adrin     (1000)        0 2023-06-07 18:55:57.179624 skops-0.7.post0/skops/card/
--rw-r--r--   0 adrin     (1000) adrin     (1000)      152 2023-01-24 13:44:03.000000 skops-0.7.post0/skops/card/__init__.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)    12980 2023-04-03 09:57:14.000000 skops-0.7.post0/skops/card/_markup.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)    53651 2023-06-07 08:45:53.000000 skops-0.7.post0/skops/card/_model_card.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)    12301 2023-04-03 09:57:14.000000 skops-0.7.post0/skops/card/_parser.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     7764 2023-04-03 09:57:14.000000 skops-0.7.post0/skops/card/_templates.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     1261 2023-01-24 13:44:03.000000 skops-0.7.post0/skops/card/default_template.md
-drwxr-xr-x   0 adrin     (1000) adrin     (1000)        0 2023-06-07 18:55:57.179624 skops-0.7.post0/skops/cli/
--rw-r--r--   0 adrin     (1000) adrin     (1000)        0 2023-01-24 13:44:03.000000 skops-0.7.post0/skops/cli/__init__.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     3172 2023-01-24 13:44:03.000000 skops-0.7.post0/skops/cli/_convert.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)      394 2023-01-24 13:44:03.000000 skops-0.7.post0/skops/cli/_utils.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     1653 2023-01-24 13:44:03.000000 skops-0.7.post0/skops/cli/entrypoint.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     1527 2023-04-03 09:57:14.000000 skops-0.7.post0/skops/conftest.py
-drwxr-xr-x   0 adrin     (1000) adrin     (1000)        0 2023-06-07 18:55:57.179624 skops-0.7.post0/skops/hub_utils/
--rw-r--r--   0 adrin     (1000) adrin     (1000)      306 2023-01-24 13:44:03.000000 skops-0.7.post0/skops/hub_utils/__init__.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)    24720 2023-04-03 09:57:14.000000 skops-0.7.post0/skops/hub_utils/_hf_hub.py
-drwxr-xr-x   0 adrin     (1000) adrin     (1000)        0 2023-06-07 18:55:57.182957 skops-0.7.post0/skops/io/
--rw-r--r--   0 adrin     (1000) adrin     (1000)      184 2023-04-03 09:57:14.000000 skops-0.7.post0/skops/io/__init__.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)    14059 2023-06-07 08:45:53.000000 skops-0.7.post0/skops/io/_audit.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)    19504 2023-06-07 08:45:53.000000 skops-0.7.post0/skops/io/_general.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     9570 2023-06-07 08:45:53.000000 skops-0.7.post0/skops/io/_numpy.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     7912 2023-06-07 08:45:53.000000 skops-0.7.post0/skops/io/_persist.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     1194 2023-04-03 09:57:14.000000 skops-0.7.post0/skops/io/_protocol.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     2381 2023-04-03 09:57:14.000000 skops-0.7.post0/skops/io/_scipy.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     8152 2023-06-07 08:45:53.000000 skops-0.7.post0/skops/io/_sklearn.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)      813 2023-06-07 08:45:53.000000 skops-0.7.post0/skops/io/_trusted_types.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     6960 2023-06-07 08:45:53.000000 skops-0.7.post0/skops/io/_utils.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)    12367 2023-06-07 08:45:53.000000 skops-0.7.post0/skops/io/_visualize.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)      490 2023-01-24 13:44:03.000000 skops-0.7.post0/skops/io/exceptions.py
-drwxr-xr-x   0 adrin     (1000) adrin     (1000)        0 2023-06-07 18:55:57.182957 skops-0.7.post0/skops/io/old/
--rw-r--r--   0 adrin     (1000) adrin     (1000)     1306 2023-04-03 09:57:14.000000 skops-0.7.post0/skops/io/old/_general_v0.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     1087 2023-04-03 09:57:14.000000 skops-0.7.post0/skops/io/old/_numpy_v0.py
-drwxr-xr-x   0 adrin     (1000) adrin     (1000)        0 2023-06-07 18:55:57.182957 skops-0.7.post0/skops/io/tests/
--rw-r--r--   0 adrin     (1000) adrin     (1000)     9738 2023-04-03 09:57:14.000000 skops-0.7.post0/skops/io/tests/_utils.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     5406 2023-06-07 08:45:53.000000 skops-0.7.post0/skops/io/tests/test_audit.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)    13891 2023-06-07 08:45:53.000000 skops-0.7.post0/skops/io/tests/test_external.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)    36653 2023-06-07 08:45:53.000000 skops-0.7.post0/skops/io/tests/test_persist.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     3216 2023-04-03 09:57:14.000000 skops-0.7.post0/skops/io/tests/test_persist_old.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)     2318 2023-01-24 13:44:03.000000 skops-0.7.post0/skops/io/tests/test_utils.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)    10554 2023-06-07 08:45:53.000000 skops-0.7.post0/skops/io/tests/test_visualize.py
-drwxr-xr-x   0 adrin     (1000) adrin     (1000)        0 2023-06-07 18:55:57.182957 skops-0.7.post0/skops/utils/
--rw-r--r--   0 adrin     (1000) adrin     (1000)        0 2023-01-24 13:44:03.000000 skops-0.7.post0/skops/utils/__init__.py
--rw-r--r--   0 adrin     (1000) adrin     (1000)      825 2023-04-03 09:57:14.000000 skops-0.7.post0/skops/utils/importutils.py
-drwxr-xr-x   0 adrin     (1000) adrin     (1000)        0 2023-06-07 18:55:57.176290 skops-0.7.post0/skops.egg-info/
--rw-r--r--   0 adrin     (1000) adrin     (1000)     4541 2023-06-07 18:55:57.000000 skops-0.7.post0/skops.egg-info/PKG-INFO
--rw-r--r--   0 adrin     (1000) adrin     (1000)     1169 2023-06-07 18:55:57.000000 skops-0.7.post0/skops.egg-info/SOURCES.txt
--rw-r--r--   0 adrin     (1000) adrin     (1000)        1 2023-06-07 18:55:57.000000 skops-0.7.post0/skops.egg-info/dependency_links.txt
--rw-r--r--   0 adrin     (1000) adrin     (1000)       56 2023-06-07 18:55:57.000000 skops-0.7.post0/skops.egg-info/entry_points.txt
--rw-r--r--   0 adrin     (1000) adrin     (1000)      503 2023-06-07 18:55:57.000000 skops-0.7.post0/skops.egg-info/requires.txt
--rw-r--r--   0 adrin     (1000) adrin     (1000)        6 2023-06-07 18:55:57.000000 skops-0.7.post0/skops.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:55.020368 skops-0.8.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1084 2023-06-28 10:02:39.000000 skops-0.8.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       74 2023-06-28 10:02:39.000000 skops-0.8.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     4537 2023-06-28 10:02:55.020368 skops-0.8.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3090 2023-06-28 10:02:39.000000 skops-0.8.0/README.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1379 2023-06-28 10:02:39.000000 skops-0.8.0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       94 2023-06-28 10:02:55.020368 skops-0.8.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2977 2023-06-28 10:02:39.000000 skops-0.8.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:55.016368 skops-0.8.0/skops/
+-rw-r--r--   0 runner    (1001) docker     (123)     1087 2023-06-28 10:02:39.000000 skops-0.8.0/skops/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2412 2023-06-28 10:02:39.000000 skops-0.8.0/skops/_min_dependencies.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:55.016368 skops-0.8.0/skops/card/
+-rw-r--r--   0 runner    (1001) docker     (123)      152 2023-06-28 10:02:39.000000 skops-0.8.0/skops/card/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12980 2023-06-28 10:02:39.000000 skops-0.8.0/skops/card/_markup.py
+-rw-r--r--   0 runner    (1001) docker     (123)    53934 2023-06-28 10:02:39.000000 skops-0.8.0/skops/card/_model_card.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12301 2023-06-28 10:02:39.000000 skops-0.8.0/skops/card/_parser.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7764 2023-06-28 10:02:39.000000 skops-0.8.0/skops/card/_templates.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1261 2023-06-28 10:02:39.000000 skops-0.8.0/skops/card/default_template.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:55.016368 skops-0.8.0/skops/card/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)    73705 2023-06-28 10:02:39.000000 skops-0.8.0/skops/card/tests/test_card.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5755 2023-06-28 10:02:39.000000 skops-0.8.0/skops/card/tests/test_parser.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:55.016368 skops-0.8.0/skops/cli/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:39.000000 skops-0.8.0/skops/cli/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3172 2023-06-28 10:02:39.000000 skops-0.8.0/skops/cli/_convert.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4182 2023-06-28 10:02:39.000000 skops-0.8.0/skops/cli/_update.py
+-rw-r--r--   0 runner    (1001) docker     (123)      394 2023-06-28 10:02:39.000000 skops-0.8.0/skops/cli/_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1817 2023-06-28 10:02:39.000000 skops-0.8.0/skops/cli/entrypoint.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:55.016368 skops-0.8.0/skops/cli/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     4371 2023-06-28 10:02:39.000000 skops-0.8.0/skops/cli/tests/test_convert.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1732 2023-06-28 10:02:39.000000 skops-0.8.0/skops/cli/tests/test_entrypoint.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7398 2023-06-28 10:02:39.000000 skops-0.8.0/skops/cli/tests/test_update.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1527 2023-06-28 10:02:39.000000 skops-0.8.0/skops/conftest.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:55.016368 skops-0.8.0/skops/hub_utils/
+-rw-r--r--   0 runner    (1001) docker     (123)      306 2023-06-28 10:02:39.000000 skops-0.8.0/skops/hub_utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24720 2023-06-28 10:02:39.000000 skops-0.8.0/skops/hub_utils/_hf_hub.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:55.016368 skops-0.8.0/skops/hub_utils/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      123 2023-06-28 10:02:39.000000 skops-0.8.0/skops/hub_utils/tests/common.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24255 2023-06-28 10:02:39.000000 skops-0.8.0/skops/hub_utils/tests/test_hf_hub.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:55.020368 skops-0.8.0/skops/io/
+-rw-r--r--   0 runner    (1001) docker     (123)      184 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14059 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/_audit.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19504 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/_general.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9900 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/_numpy.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7912 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/_persist.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1194 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/_protocol.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2381 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/_scipy.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8152 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/_sklearn.py
+-rw-r--r--   0 runner    (1001) docker     (123)      813 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/_trusted_types.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6960 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12367 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/_visualize.py
+-rw-r--r--   0 runner    (1001) docker     (123)      490 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/exceptions.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:55.020368 skops-0.8.0/skops/io/old/
+-rw-r--r--   0 runner    (1001) docker     (123)     1306 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/old/_general_v0.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1087 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/old/_numpy_v0.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:55.020368 skops-0.8.0/skops/io/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     9738 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/tests/_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5406 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/tests/test_audit.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13891 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/tests/test_external.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37308 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/tests/test_persist.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3216 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/tests/test_persist_old.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2318 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/tests/test_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10554 2023-06-28 10:02:39.000000 skops-0.8.0/skops/io/tests/test_visualize.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:55.020368 skops-0.8.0/skops/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:39.000000 skops-0.8.0/skops/utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      825 2023-06-28 10:02:39.000000 skops-0.8.0/skops/utils/importutils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:55.020368 skops-0.8.0/skops/utils/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      513 2023-06-28 10:02:39.000000 skops-0.8.0/skops/utils/tests/test_importutils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:02:55.016368 skops-0.8.0/skops.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     4537 2023-06-28 10:02:55.000000 skops-0.8.0/skops.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1457 2023-06-28 10:02:55.000000 skops-0.8.0/skops.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:02:55.000000 skops-0.8.0/skops.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       56 2023-06-28 10:02:55.000000 skops-0.8.0/skops.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      503 2023-06-28 10:02:55.000000 skops-0.8.0/skops.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-28 10:02:55.000000 skops-0.8.0/skops.egg-info/top_level.txt
```

### Comparing `skops-0.7.post0/LICENSE` & `skops-0.8.0/LICENSE`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/PKG-INFO` & `skops-0.8.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: skops
-Version: 0.7.post0
+Version: 0.8.0
 Summary: A set of tools to push scikit-learn based models to and pull from Hugging Face Hub
 Home-page: http://github.com/skops-dev/skops
 Download-URL: https://pypi.org/project/skops/#files
 Maintainer: Adrin Jalali
 Maintainer-email: adrin.jalali@gmail.com
 License: MIT
 Project-URL: Bug Tracker, http://github.com/skops-dev/skops/issues
```

### Comparing `skops-0.7.post0/README.rst` & `skops-0.8.0/README.rst`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/pyproject.toml` & `skops-0.8.0/pyproject.toml`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/setup.py` & `skops-0.8.0/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 #! /usr/bin/env python
 # License: 3-clause BSD
 import builtins
 
-from setuptools import setup, find_packages
+from setuptools import find_namespace_packages, setup
 
 # This is a bit (!) hackish: we are setting a global variable so that the
 # main modelcard __init__ can detect if it is being loaded by the setup
 # routine, to avoid attempting to load components.
 builtins.__SKOPS_SETUP__ = True  # type: ignore
 
 
@@ -77,15 +77,15 @@
         install_requires=min_deps.tag_to_packages["install"],
         extras_require={
             "docs": min_deps.tag_to_packages["docs"],
             "tests": min_deps.tag_to_packages["tests"],
             "rich": min_deps.tag_to_packages["rich"],
         },
         include_package_data=True,
-        packages=find_packages() + ["skops.io.old", "skops.io.tests"],
+        packages=find_namespace_packages(include=["skops*"]),
     )
 
     setup(**package_data, **metadata)
 
 
 if __name__ == "__main__":
     setup_package()
```

### Comparing `skops-0.7.post0/skops/__init__.py` & `skops-0.8.0/skops/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -12,15 +12,15 @@
 #   X.Y.ZbN   # Beta release
 #   X.Y.ZrcN  # Release Candidate
 #   X.Y.Z     # Final release
 #
 # Dev branch marker is: 'X.Y.dev' or 'X.Y.devN' where N is an integer.
 # 'X.Y.dev0' is the canonical version of 'X.Y.dev'
 #
-__version__ = "0.7.post0"
+__version__ = "0.8.0"
 
 try:
     # This variable is injected in the __builtins__ by the build
     # process. It is used to enable importing subpackages of skops when
     # the binaries are not built
     # mypy error: Cannot determine type of '__SKOPS_SETUP__'
     __SKOPS_SETUP__  # type: ignore
```

### Comparing `skops-0.7.post0/skops/_min_dependencies.py` & `skops-0.8.0/skops/_min_dependencies.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/card/_markup.py` & `skops-0.8.0/skops/card/_markup.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/card/_model_card.py` & `skops-0.8.0/skops/card/_model_card.py`

 * *Files 0% similar despite different names*

```diff
@@ -532,28 +532,28 @@
                 f"Unknown template '{self.template}', "
                 f"template must be one of the following values: {valid_templates}"
             )
             raise ValueError(msg)
 
         # default template
         if self.template == Templates.skops.value:
-            self.add(**SKOPS_TEMPLATE)
+            self.add(folded=False, **SKOPS_TEMPLATE)
             # for the skops template, automatically add some default sections
             self.add_hyperparams()
             self.add_get_started_code()
 
             if (model_diagram is True) or (model_diagram == "auto"):
                 self.add_model_plot()
             elif isinstance(model_diagram, str):
                 self.add_model_plot(section=model_diagram)
             return
 
         # non-default template
         if isinstance(self.template, Mapping):
-            self.add(**self.template)
+            self.add(folded=False, **self.template)
 
         if isinstance(model_diagram, str) and (model_diagram != "auto"):
             self.add_model_plot(section=model_diagram)
         elif model_diagram is True:
             # will trigger an error
             self.add_model_plot()
 
@@ -585,15 +585,15 @@
         return self._model
 
     @cached_property
     def _model(self):
         model = _load_model(self.model, self.trusted)
         return model
 
-    def add(self, **kwargs: str) -> Self:
+    def add(self, folded: bool = False, **kwargs: str) -> Self:
         """Add new section(s) to the model card.
 
         Add one or multiple sections to the model card. The section names are
         taken from the keys and the contents are taken from the values.
 
         To add to an existing section, use a ``"/"`` in the section name, e.g.:
 
@@ -607,26 +607,29 @@
         ``card.add(**{"A section with\\/a slash in the title": "content"})``.
 
         If a section of the given name already exists, its content will be
         overwritten.
 
         Parameters
         ----------
+        folded : bool
+            Whether to fold the sections by default or not.
+
         **kwargs : dict
             The keys of the dictionary serve as the section title and the values
             as the section content. It's possible to add to existing sections.
 
         Returns
         -------
         self : object
             Card object.
 
         """
         for key, val in kwargs.items():
-            self._add_single(key, val)
+            self._add_single(key, val, folded=folded)
         return self
 
     def _select(
         self, subsection_names: Sequence[str], create: bool = True
     ) -> dict[str, Section]:
         """Select a single section from the data.
 
@@ -757,15 +760,17 @@
         if not leaf_node_name:
             msg = f"Section name cannot be empty but got '{key}'"
             raise KeyError(msg)
 
         parent_section = self._select(subsection_names, create=False)
         del parent_section[leaf_node_name]
 
-    def _add_single(self, key: str, val: str | Section) -> Section:
+    def _add_single(
+        self, key: str, val: str | Section, folded: bool = False
+    ) -> Section:
         """Add a single section.
 
         If the (sub)section does not exist, it is created. Otherwise, the
         existing (sub)section is modified.
 
         Parameters
         ----------
@@ -773,26 +778,29 @@
             The name of the (sub)section.
 
         val: str or Section
             The value to assign to the (sub)section. If this is already a
             section, leave it as it is. If it's a string, create a
             :class:`skops.card._model_card.Section`.
 
+        folded: bool
+            Whether the (sub)section should be folded or not.
+
         Returns
         -------
         Section instance
             The section that has been added or modified.
 
         """
         *subsection_names, leaf_node_name = split_subsection_names(key)
         section = self._select(subsection_names)
 
         if isinstance(val, str):
             # val is a str, create a Section
-            new_section = Section(title=leaf_node_name, content=val)
+            new_section = Section(title=leaf_node_name, content=val, folded=folded)
         else:
             # val is already a section and can be used as is
             new_section = val
 
         if leaf_node_name in section:
             # entry exists, preserve its subsections
             old_section = section[leaf_node_name]
```

### Comparing `skops-0.7.post0/skops/card/_parser.py` & `skops-0.8.0/skops/card/_parser.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/card/_templates.py` & `skops-0.8.0/skops/card/_templates.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/card/default_template.md` & `skops-0.8.0/skops/card/default_template.md`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/cli/_convert.py` & `skops-0.8.0/skops/cli/_convert.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/cli/entrypoint.py` & `skops-0.8.0/skops/cli/entrypoint.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,11 @@
 import argparse
 
 import skops.cli._convert
+import skops.cli._update
 
 
 def main_cli(command_line_args=None):
     """Main command line interface entrypoint for all command line Skops methods.
 
     To add a new entrypoint:
         1. Create a new method to call that accepts a namespace
@@ -28,14 +29,18 @@
     #   method: the command to call (gets set to default 'func')
     #   format_parser: the function used to create a subparser for that command
     function_map = {
         "convert": {
             "method": skops.cli._convert.main,
             "format_parser": skops.cli._convert.format_parser,
         },
+        "update": {
+            "method": skops.cli._update.main,
+            "format_parser": skops.cli._update.format_parser,
+        },
     }
 
     for func_name, values in function_map.items():
         # Add subparser for each function in func map,
         # and assigns default func to be "method" from function_map
         subparser = subparsers.add_parser(func_name)
         subparser.set_defaults(func=values["method"])
```

### Comparing `skops-0.7.post0/skops/conftest.py` & `skops-0.8.0/skops/conftest.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/hub_utils/_hf_hub.py` & `skops-0.8.0/skops/hub_utils/_hf_hub.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/_audit.py` & `skops-0.8.0/skops/io/_audit.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/_general.py` & `skops-0.8.0/skops/io/_general.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/_numpy.py` & `skops-0.8.0/skops/io/_numpy.py`

 * *Files 2% similar despite different names*

```diff
@@ -252,14 +252,25 @@
     (np.ndarray, ndarray_get_state),
     (np.ma.MaskedArray, maskedarray_get_state),
     (np.ufunc, function_get_state),
     (np.dtype, dtype_get_state),
     (np.random.RandomState, random_state_get_state),
     (np.random.Generator, random_generator_get_state),
 ]
+
+try:
+    # From numpy=1.25.0 dispatching for `__array_function__` is done via
+    # a C wrapper: https://github.com/numpy/numpy/pull/23020
+    from numpy.core._multiarray_umath import _ArrayFunctionDispatcher
+
+    GET_STATE_DISPATCH_FUNCTIONS.append((_ArrayFunctionDispatcher, function_get_state))
+except ImportError:
+    pass
+
+
 # tuples of type and function that creates the instance of that type
 NODE_TYPE_MAPPING = {
     ("NdArrayNode", PROTOCOL): NdArrayNode,
     ("MaskedArrayNode", PROTOCOL): MaskedArrayNode,
     ("DTypeNode", PROTOCOL): DTypeNode,
     ("RandomStateNode", PROTOCOL): RandomStateNode,
     ("RandomGeneratorNode", PROTOCOL): RandomGeneratorNode,
```

### Comparing `skops-0.7.post0/skops/io/_persist.py` & `skops-0.8.0/skops/io/_persist.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/_protocol.py` & `skops-0.8.0/skops/io/_protocol.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/_scipy.py` & `skops-0.8.0/skops/io/_scipy.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/_sklearn.py` & `skops-0.8.0/skops/io/_sklearn.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/_trusted_types.py` & `skops-0.8.0/skops/io/_trusted_types.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/_utils.py` & `skops-0.8.0/skops/io/_utils.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/_visualize.py` & `skops-0.8.0/skops/io/_visualize.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/old/_general_v0.py` & `skops-0.8.0/skops/io/old/_general_v0.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/old/_numpy_v0.py` & `skops-0.8.0/skops/io/old/_numpy_v0.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/tests/_utils.py` & `skops-0.8.0/skops/io/tests/_utils.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/tests/test_audit.py` & `skops-0.8.0/skops/io/tests/test_audit.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/tests/test_external.py` & `skops-0.8.0/skops/io/tests/test_external.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/tests/test_persist.py` & `skops-0.8.0/skops/io/tests/test_persist.py`

 * *Files 1% similar despite different names*

```diff
@@ -45,14 +45,15 @@
 from sklearn.utils._tags import _safe_tags
 from sklearn.utils._testing import SkipTest, set_random_state
 from sklearn.utils.estimator_checks import (
     _construct_instance,
     _enforce_estimator_tags_y,
     _get_check_estimator_ids,
 )
+from sklearn.utils.fixes import parse_version, sp_version
 
 import skops
 from skops.io import dump, dumps, get_untrusted_types, load, loads
 from skops.io._audit import NODE_TYPE_MAPPING, get_tree
 from skops.io._sklearn import UNSUPPORTED_TYPES
 from skops.io._trusted_types import (
     NUMPY_DTYPE_TYPE_NAMES,
@@ -132,15 +133,24 @@
             # suppress warnings here for skipped estimators.
             with warnings.catch_warnings():
                 warnings.filterwarnings(
                     "ignore",
                     category=SkipTestWarning,
                     message="Can't instantiate estimator",
                 )
-                estimator = _construct_instance(Estimator)
+                if name == "QuantileRegressor" and sp_version >= parse_version(
+                    "1.11.0"
+                ):
+                    # The solver "interior-point" (the default solver in
+                    # scikit-learn < 1.4.0) is not available in scipy >= 1.11.0. The
+                    # default solver will be "highs" from scikit-learn >= 1.4.0.
+                    # https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.QuantileRegressor.html
+                    estimator = _construct_instance(partial(Estimator, solver="highs"))
+                else:
+                    estimator = _construct_instance(Estimator)
                 # with the kind of data we pass, it needs to be 1 for the few
                 # estimators which have this.
                 if "n_components" in estimator.get_params():
                     estimator.set_params(n_components=1)
                     # Then n_best needs to be <= n_components
                     if "n_best" in estimator.get_params():
                         estimator.set_params(n_best=1)
```

### Comparing `skops-0.7.post0/skops/io/tests/test_persist_old.py` & `skops-0.8.0/skops/io/tests/test_persist_old.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/tests/test_utils.py` & `skops-0.8.0/skops/io/tests/test_utils.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/io/tests/test_visualize.py` & `skops-0.8.0/skops/io/tests/test_visualize.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops/utils/importutils.py` & `skops-0.8.0/skops/utils/importutils.py`

 * *Files identical despite different names*

### Comparing `skops-0.7.post0/skops.egg-info/PKG-INFO` & `skops-0.8.0/skops.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: skops
-Version: 0.7.post0
+Version: 0.8.0
 Summary: A set of tools to push scikit-learn based models to and pull from Hugging Face Hub
 Home-page: http://github.com/skops-dev/skops
 Download-URL: https://pypi.org/project/skops/#files
 Maintainer: Adrin Jalali
 Maintainer-email: adrin.jalali@gmail.com
 License: MIT
 Project-URL: Bug Tracker, http://github.com/skops-dev/skops/issues
```

### Comparing `skops-0.7.post0/skops.egg-info/SOURCES.txt` & `skops-0.8.0/skops.egg-info/SOURCES.txt`

 * *Files 21% similar despite different names*

```diff
@@ -15,20 +15,28 @@
 skops.egg-info/top_level.txt
 skops/card/__init__.py
 skops/card/_markup.py
 skops/card/_model_card.py
 skops/card/_parser.py
 skops/card/_templates.py
 skops/card/default_template.md
+skops/card/tests/test_card.py
+skops/card/tests/test_parser.py
 skops/cli/__init__.py
 skops/cli/_convert.py
+skops/cli/_update.py
 skops/cli/_utils.py
 skops/cli/entrypoint.py
+skops/cli/tests/test_convert.py
+skops/cli/tests/test_entrypoint.py
+skops/cli/tests/test_update.py
 skops/hub_utils/__init__.py
 skops/hub_utils/_hf_hub.py
+skops/hub_utils/tests/common.py
+skops/hub_utils/tests/test_hf_hub.py
 skops/io/__init__.py
 skops/io/_audit.py
 skops/io/_general.py
 skops/io/_numpy.py
 skops/io/_persist.py
 skops/io/_protocol.py
 skops/io/_scipy.py
@@ -43,8 +51,9 @@
 skops/io/tests/test_audit.py
 skops/io/tests/test_external.py
 skops/io/tests/test_persist.py
 skops/io/tests/test_persist_old.py
 skops/io/tests/test_utils.py
 skops/io/tests/test_visualize.py
 skops/utils/__init__.py
-skops/utils/importutils.py
+skops/utils/importutils.py
+skops/utils/tests/test_importutils.py
```


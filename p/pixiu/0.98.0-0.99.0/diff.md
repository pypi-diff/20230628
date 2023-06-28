# Comparing `tmp/pixiu-0.98.0.tar.gz` & `tmp/pixiu-0.99.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "/Users/digiyouth/local_files/codes/oeoehui_pixiu/dist/.tmp-1jiehyp9/pixiu-0.98.0.tar", last modified: Wed Dec 28 08:31:06 2022, max compression
+gzip compressed data, was "/Users/digiyouth/local_files/codes/oeoehui_pixiu/dist/.tmp-p0_zj0s1/pixiu-0.99.0.tar", last modified: Sat Jan 14 03:08:13 2023, max compression
```

## Comparing `pixiu-0.98.0.tar` & `pixiu-0.99.0.tar`

### file list

```diff
@@ -1,67 +1,67 @@
-drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2022-12-28 08:31:06.294860 pixiu-0.98.0/
--rw-r--r--   0 digiyouth   (501) staff       (20)    26033 2022-12-28 07:44:10.000000 pixiu-0.98.0/CHANGES.md
--rw-r--r--   0 digiyouth   (501) staff       (20)    10731 2021-05-29 07:04:40.000000 pixiu-0.98.0/LICENSE
--rw-r--r--   0 digiyouth   (501) staff       (20)      299 2021-05-29 16:45:18.000000 pixiu-0.98.0/MANIFEST.in
--rw-r--r--   0 digiyouth   (501) staff       (20)    60984 2022-12-28 08:31:06.294181 pixiu-0.98.0/PKG-INFO
--rw-r--r--   0 digiyouth   (501) staff       (20)    34382 2022-03-10 02:36:10.000000 pixiu-0.98.0/README.md
--rw-r--r--   0 digiyouth   (501) staff       (20)    33885 2022-03-10 02:36:36.000000 pixiu-0.98.0/README.zh.md
-drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2022-12-28 08:31:06.187961 pixiu-0.98.0/pixiu/
--rw-r--r--   0 digiyouth   (501) staff       (20)        2 2021-04-14 08:18:33.000000 pixiu-0.98.0/pixiu/__init__.py
--rw-r--r--   0 digiyouth   (501) staff       (20)       37 2021-06-07 02:54:28.000000 pixiu-0.98.0/pixiu/__main__.py
-drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2022-12-28 08:31:06.214349 pixiu-0.98.0/pixiu/api/
--rw-r--r--   0 digiyouth   (501) staff       (20)       43 2021-05-28 05:36:16.000000 pixiu-0.98.0/pixiu/api/__init__.py
--rw-r--r--   0 digiyouth   (501) staff       (20)     1029 2022-03-09 04:19:59.000000 pixiu-0.98.0/pixiu/api/defines.py
--rw-r--r--   0 digiyouth   (501) staff       (20)      805 2022-02-24 09:15:28.000000 pixiu-0.98.0/pixiu/api/errors.py
--rw-r--r--   0 digiyouth   (501) staff       (20)     3311 2021-11-15 06:17:59.000000 pixiu-0.98.0/pixiu/api/utils.py
-drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2022-12-28 08:31:06.228644 pixiu-0.98.0/pixiu/api/v1/
--rw-r--r--   0 digiyouth   (501) staff       (20)      228 2021-06-07 07:48:49.000000 pixiu-0.98.0/pixiu/api/v1/__init__.py
--rw-r--r--   0 digiyouth   (501) staff       (20)    10918 2022-07-28 10:12:44.000000 pixiu-0.98.0/pixiu/api/v1/account.py
--rw-r--r--   0 digiyouth   (501) staff       (20)    31998 2022-12-08 03:54:51.000000 pixiu-0.98.0/pixiu/api/v1/api.py
--rw-r--r--   0 digiyouth   (501) staff       (20)     5094 2022-07-28 10:12:55.000000 pixiu-0.98.0/pixiu/api/v1/order.py
--rw-r--r--   0 digiyouth   (501) staff       (20)     9587 2022-08-26 09:48:29.000000 pixiu-0.98.0/pixiu/api/v1/symbol.py
-drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2022-12-28 08:31:06.236478 pixiu-0.98.0/pixiu/base/
--rw-r--r--   0 digiyouth   (501) staff       (20)       32 2021-04-29 03:04:44.000000 pixiu-0.98.0/pixiu/base/__init__.py
--rw-r--r--   0 digiyouth   (501) staff       (20)     4533 2022-11-04 06:52:14.000000 pixiu-0.98.0/pixiu/base/api_base.py
--rw-r--r--   0 digiyouth   (501) staff       (20)    15387 2022-12-28 07:05:00.000000 pixiu-0.98.0/pixiu/base/ea_base.py
--rw-r--r--   0 digiyouth   (501) staff       (20)     1904 2022-04-23 09:37:34.000000 pixiu-0.98.0/pixiu/base/ea_node_transformer.py
-drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2022-12-28 08:31:06.238128 pixiu-0.98.0/pixiu/live/
--rw-r--r--   0 digiyouth   (501) staff       (20)        0 2021-04-19 08:30:14.000000 pixiu-0.98.0/pixiu/live/__init__.py
--rw-r--r--   0 digiyouth   (501) staff       (20)    17277 2022-10-27 03:28:08.000000 pixiu-0.98.0/pixiu/main.py
--rw-r--r--   0 digiyouth   (501) staff       (20)    18032 2022-12-05 10:35:56.000000 pixiu-0.98.0/pixiu/pxtester.py
-drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2022-12-28 08:31:06.245991 pixiu-0.98.0/pixiu/tester/
--rw-r--r--   0 digiyouth   (501) staff       (20)       55 2022-06-17 15:51:15.000000 pixiu-0.98.0/pixiu/tester/__init__.py
--rw-r--r--   0 digiyouth   (501) staff       (20)   103271 2022-12-20 08:51:39.000000 pixiu-0.98.0/pixiu/tester/ea_tester.py
--rw-r--r--   0 digiyouth   (501) staff       (20)    26229 2022-06-20 09:33:35.000000 pixiu-0.98.0/pixiu/tester/ea_tester_graph.py
--rw-r--r--   0 digiyouth   (501) staff       (20)    20005 2022-12-06 09:27:40.000000 pixiu-0.98.0/pixiu/tester/tester_api_v1.py
-drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2022-12-28 08:31:06.202902 pixiu-0.98.0/pixiu.egg-info/
--rw-r--r--   0 digiyouth   (501) staff       (20)    60984 2022-12-28 08:31:06.000000 pixiu-0.98.0/pixiu.egg-info/PKG-INFO
--rw-r--r--   0 digiyouth   (501) staff       (20)     1282 2022-12-28 08:31:06.000000 pixiu-0.98.0/pixiu.egg-info/SOURCES.txt
--rw-r--r--   0 digiyouth   (501) staff       (20)        1 2022-12-28 08:31:06.000000 pixiu-0.98.0/pixiu.egg-info/dependency_links.txt
--rw-r--r--   0 digiyouth   (501) staff       (20)       42 2022-12-28 08:31:06.000000 pixiu-0.98.0/pixiu.egg-info/entry_points.txt
--rw-r--r--   0 digiyouth   (501) staff       (20)        1 2021-04-25 06:10:20.000000 pixiu-0.98.0/pixiu.egg-info/not-zip-safe
--rw-r--r--   0 digiyouth   (501) staff       (20)      155 2022-12-28 08:31:06.000000 pixiu-0.98.0/pixiu.egg-info/requires.txt
--rw-r--r--   0 digiyouth   (501) staff       (20)        6 2022-12-28 08:31:06.000000 pixiu-0.98.0/pixiu.egg-info/top_level.txt
--rw-r--r--   0 digiyouth   (501) staff       (20)      103 2021-05-29 03:15:23.000000 pixiu-0.98.0/pyproject.toml
-drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2022-12-28 08:31:06.253549 pixiu-0.98.0/samples/
--rw-r--r--   0 digiyouth   (501) staff       (20)     6148 2021-05-29 05:34:23.000000 pixiu-0.98.0/samples/.DS_Store
--rw-r--r--   0 digiyouth   (501) staff       (20)      276 2021-05-29 02:57:23.000000 pixiu-0.98.0/samples/HELP.txt
--rw-r--r--   0 digiyouth   (501) staff       (20)     2202 2021-06-07 03:15:59.000000 pixiu-0.98.0/samples/pixiu_sample.json
--rw-r--r--   0 digiyouth   (501) staff       (20)     2680 2021-06-07 03:24:03.000000 pixiu-0.98.0/samples/pixiu_sample.py
--rw-r--r--   0 digiyouth   (501) staff       (20)      139 2021-06-07 03:24:46.000000 pixiu-0.98.0/samples/pixiu_sample2.py
--rw-r--r--   0 digiyouth   (501) staff       (20)       38 2022-12-28 08:31:06.295246 pixiu-0.98.0/setup.cfg
--rw-r--r--   0 digiyouth   (501) staff       (20)     1474 2022-12-28 07:44:24.000000 pixiu-0.98.0/setup.py
-drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2022-12-28 08:31:06.265038 pixiu-0.98.0/tests/
--rw-r--r--   0 digiyouth   (501) staff       (20)     6148 2021-10-14 06:09:57.000000 pixiu-0.98.0/tests/.DS_Store
-drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2022-12-28 08:31:06.173660 pixiu-0.98.0/tests/scripts/
-drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2022-12-28 08:31:06.291748 pixiu-0.98.0/tests/scripts/v1/
--rw-r--r--   0 digiyouth   (501) staff       (20)     8495 2022-12-19 08:30:56.000000 pixiu-0.98.0/tests/scripts/v1/ts_base.py
--rw-r--r--   0 digiyouth   (501) staff       (20)     2997 2021-05-19 05:47:08.000000 pixiu-0.98.0/tests/scripts/v1/ts_indicators.py
--rw-r--r--   0 digiyouth   (501) staff       (20)     4469 2022-03-18 13:19:58.000000 pixiu-0.98.0/tests/scripts/v1/ts_order_buylimit.py
--rw-r--r--   0 digiyouth   (501) staff       (20)     4471 2022-03-18 13:20:16.000000 pixiu-0.98.0/tests/scripts/v1/ts_order_buystop.py
--rw-r--r--   0 digiyouth   (501) staff       (20)     8950 2022-08-26 10:32:57.000000 pixiu-0.98.0/tests/scripts/v1/ts_order_market.py
--rw-r--r--   0 digiyouth   (501) staff       (20)     4533 2022-03-18 13:21:50.000000 pixiu-0.98.0/tests/scripts/v1/ts_order_selllimit.py
--rw-r--r--   0 digiyouth   (501) staff       (20)     4488 2022-03-18 13:23:50.000000 pixiu-0.98.0/tests/scripts/v1/ts_order_sellstop.py
--rw-r--r--   0 digiyouth   (501) staff       (20)     4343 2022-08-26 10:27:31.000000 pixiu-0.98.0/tests/scripts/v1/ts_symbol_data.py
--rw-r--r--   0 digiyouth   (501) staff       (20)    29650 2022-12-20 03:26:15.000000 pixiu-0.98.0/tests/test_pixiu.py
--rw-r--r--   0 digiyouth   (501) staff       (20)  1029533 2021-04-25 09:46:15.000000 pixiu-0.98.0/tests/usdchf_m1_20210315-0329.csv
--rw-r--r--   0 digiyouth   (501) staff       (20)  2346668 2021-04-25 09:47:10.000000 pixiu-0.98.0/tests/usdchf_m1_20210315-0415.csv
+drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2023-01-14 03:08:13.382566 pixiu-0.99.0/
+-rw-r--r--   0 digiyouth   (501) staff       (20)    26240 2023-01-11 03:07:15.000000 pixiu-0.99.0/CHANGES.md
+-rw-r--r--   0 digiyouth   (501) staff       (20)    10731 2021-05-29 07:04:40.000000 pixiu-0.99.0/LICENSE
+-rw-r--r--   0 digiyouth   (501) staff       (20)      299 2021-05-29 16:45:18.000000 pixiu-0.99.0/MANIFEST.in
+-rw-r--r--   0 digiyouth   (501) staff       (20)    61191 2023-01-14 03:08:13.274363 pixiu-0.99.0/PKG-INFO
+-rw-r--r--   0 digiyouth   (501) staff       (20)    34382 2022-03-10 02:36:10.000000 pixiu-0.99.0/README.md
+-rw-r--r--   0 digiyouth   (501) staff       (20)    33885 2022-03-10 02:36:36.000000 pixiu-0.99.0/README.zh.md
+drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2023-01-14 03:08:13.162187 pixiu-0.99.0/pixiu/
+-rw-r--r--   0 digiyouth   (501) staff       (20)        2 2021-04-14 08:18:33.000000 pixiu-0.99.0/pixiu/__init__.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)       37 2021-06-07 02:54:28.000000 pixiu-0.99.0/pixiu/__main__.py
+drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2023-01-14 03:08:13.176409 pixiu-0.99.0/pixiu/api/
+-rw-r--r--   0 digiyouth   (501) staff       (20)       43 2021-05-28 05:36:16.000000 pixiu-0.99.0/pixiu/api/__init__.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)     1029 2022-03-09 04:19:59.000000 pixiu-0.99.0/pixiu/api/defines.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)      805 2022-02-24 09:15:28.000000 pixiu-0.99.0/pixiu/api/errors.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)     3311 2021-11-15 06:17:59.000000 pixiu-0.99.0/pixiu/api/utils.py
+drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2023-01-14 03:08:13.186418 pixiu-0.99.0/pixiu/api/v1/
+-rw-r--r--   0 digiyouth   (501) staff       (20)      228 2021-06-07 07:48:49.000000 pixiu-0.99.0/pixiu/api/v1/__init__.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)    10918 2022-07-28 10:12:44.000000 pixiu-0.99.0/pixiu/api/v1/account.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)    31998 2022-12-08 03:54:51.000000 pixiu-0.99.0/pixiu/api/v1/api.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)     5094 2022-07-28 10:12:55.000000 pixiu-0.99.0/pixiu/api/v1/order.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)     9587 2022-08-26 09:48:29.000000 pixiu-0.99.0/pixiu/api/v1/symbol.py
+drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2023-01-14 03:08:13.192358 pixiu-0.99.0/pixiu/base/
+-rw-r--r--   0 digiyouth   (501) staff       (20)       32 2021-04-29 03:04:44.000000 pixiu-0.99.0/pixiu/base/__init__.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)     4533 2022-11-04 06:52:14.000000 pixiu-0.99.0/pixiu/base/api_base.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)    15387 2022-12-28 07:05:00.000000 pixiu-0.99.0/pixiu/base/ea_base.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)     1904 2022-04-23 09:37:34.000000 pixiu-0.99.0/pixiu/base/ea_node_transformer.py
+drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2023-01-14 03:08:13.194188 pixiu-0.99.0/pixiu/live/
+-rw-r--r--   0 digiyouth   (501) staff       (20)        0 2021-04-19 08:30:14.000000 pixiu-0.99.0/pixiu/live/__init__.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)    17277 2022-10-27 03:28:08.000000 pixiu-0.99.0/pixiu/main.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)    18032 2022-12-05 10:35:56.000000 pixiu-0.99.0/pixiu/pxtester.py
+drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2023-01-14 03:08:13.201792 pixiu-0.99.0/pixiu/tester/
+-rw-r--r--   0 digiyouth   (501) staff       (20)       55 2022-06-17 15:51:15.000000 pixiu-0.99.0/pixiu/tester/__init__.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)   103322 2023-01-11 03:04:24.000000 pixiu-0.99.0/pixiu/tester/ea_tester.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)    26229 2022-06-20 09:33:35.000000 pixiu-0.99.0/pixiu/tester/ea_tester_graph.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)    20005 2022-12-06 09:27:40.000000 pixiu-0.99.0/pixiu/tester/tester_api_v1.py
+drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2023-01-14 03:08:13.170498 pixiu-0.99.0/pixiu.egg-info/
+-rw-r--r--   0 digiyouth   (501) staff       (20)    61191 2023-01-14 03:08:12.000000 pixiu-0.99.0/pixiu.egg-info/PKG-INFO
+-rw-r--r--   0 digiyouth   (501) staff       (20)     1282 2023-01-14 03:08:12.000000 pixiu-0.99.0/pixiu.egg-info/SOURCES.txt
+-rw-r--r--   0 digiyouth   (501) staff       (20)        1 2023-01-14 03:08:12.000000 pixiu-0.99.0/pixiu.egg-info/dependency_links.txt
+-rw-r--r--   0 digiyouth   (501) staff       (20)       42 2023-01-14 03:08:12.000000 pixiu-0.99.0/pixiu.egg-info/entry_points.txt
+-rw-r--r--   0 digiyouth   (501) staff       (20)        1 2021-04-25 06:10:20.000000 pixiu-0.99.0/pixiu.egg-info/not-zip-safe
+-rw-r--r--   0 digiyouth   (501) staff       (20)      155 2023-01-14 03:08:12.000000 pixiu-0.99.0/pixiu.egg-info/requires.txt
+-rw-r--r--   0 digiyouth   (501) staff       (20)        6 2023-01-14 03:08:12.000000 pixiu-0.99.0/pixiu.egg-info/top_level.txt
+-rw-r--r--   0 digiyouth   (501) staff       (20)      103 2021-05-29 03:15:23.000000 pixiu-0.99.0/pyproject.toml
+drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2023-01-14 03:08:13.210628 pixiu-0.99.0/samples/
+-rw-r--r--   0 digiyouth   (501) staff       (20)     6148 2021-05-29 05:34:23.000000 pixiu-0.99.0/samples/.DS_Store
+-rw-r--r--   0 digiyouth   (501) staff       (20)      276 2021-05-29 02:57:23.000000 pixiu-0.99.0/samples/HELP.txt
+-rw-r--r--   0 digiyouth   (501) staff       (20)     2202 2021-06-07 03:15:59.000000 pixiu-0.99.0/samples/pixiu_sample.json
+-rw-r--r--   0 digiyouth   (501) staff       (20)     2680 2021-06-07 03:24:03.000000 pixiu-0.99.0/samples/pixiu_sample.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)      139 2021-06-07 03:24:46.000000 pixiu-0.99.0/samples/pixiu_sample2.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)       38 2023-01-14 03:08:13.382801 pixiu-0.99.0/setup.cfg
+-rw-r--r--   0 digiyouth   (501) staff       (20)     1474 2023-01-11 03:07:54.000000 pixiu-0.99.0/setup.py
+drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2023-01-14 03:08:13.225349 pixiu-0.99.0/tests/
+-rw-r--r--   0 digiyouth   (501) staff       (20)     6148 2021-10-14 06:09:57.000000 pixiu-0.99.0/tests/.DS_Store
+drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2023-01-14 03:08:13.070460 pixiu-0.99.0/tests/scripts/
+drwxr-xr-x   0 digiyouth   (501) staff       (20)        0 2023-01-14 03:08:13.258880 pixiu-0.99.0/tests/scripts/v1/
+-rw-r--r--   0 digiyouth   (501) staff       (20)     8495 2022-12-19 08:30:56.000000 pixiu-0.99.0/tests/scripts/v1/ts_base.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)     2997 2021-05-19 05:47:08.000000 pixiu-0.99.0/tests/scripts/v1/ts_indicators.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)     4469 2022-03-18 13:19:58.000000 pixiu-0.99.0/tests/scripts/v1/ts_order_buylimit.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)     4471 2022-03-18 13:20:16.000000 pixiu-0.99.0/tests/scripts/v1/ts_order_buystop.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)     8950 2022-08-26 10:32:57.000000 pixiu-0.99.0/tests/scripts/v1/ts_order_market.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)     4533 2022-03-18 13:21:50.000000 pixiu-0.99.0/tests/scripts/v1/ts_order_selllimit.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)     4488 2022-03-18 13:23:50.000000 pixiu-0.99.0/tests/scripts/v1/ts_order_sellstop.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)     4343 2022-08-26 10:27:31.000000 pixiu-0.99.0/tests/scripts/v1/ts_symbol_data.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)    29650 2022-12-20 03:26:15.000000 pixiu-0.99.0/tests/test_pixiu.py
+-rw-r--r--   0 digiyouth   (501) staff       (20)  1029533 2021-04-25 09:46:15.000000 pixiu-0.99.0/tests/usdchf_m1_20210315-0329.csv
+-rw-r--r--   0 digiyouth   (501) staff       (20)  2346668 2021-04-25 09:47:10.000000 pixiu-0.99.0/tests/usdchf_m1_20210315-0415.csv
```

### Comparing `pixiu-0.98.0/CHANGES.md` & `pixiu-0.99.0/CHANGES.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,8 +1,17 @@
 
+### [2023-01-11]
+#### Version:
+#####   Package:
+#####    pixiu: 0.99.*.20230111
+#####
+#### **Descriptions：**
+     1.ea_tester.py:
+       1) Fix self.current_tick_index exception in execute_(self, ticket)
+
 ### [2022-12-28]
 #### Version:
 #####   Package:
 #####    pixiu: 0.98.*.20221228
 #####
 #### **Descriptions：**
      1.Add global API:
```

### Comparing `pixiu-0.98.0/LICENSE` & `pixiu-0.99.0/LICENSE`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/PKG-INFO` & `pixiu-0.99.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pixiu
-Version: 0.98.0
+Version: 0.99.0
 Summary: PiXiu - A trading backtesting tool similar to MT4/MT5
 Home-page: https://github.com/tradepython/pixiu
 Author: tradepython
 Author-email: tradepython@icloud.com
 Project-URL: Bug Tracker, https://github.com/tradepython/pixiu/issues
 Keywords: Trading Backtest Forex Stocks MT4 MT5 MetaTrade
 Classifier: Programming Language :: Python :: 3
@@ -932,14 +932,23 @@
                      The errorid.
                   
                    
 ```
 
 
 
+### [2023-01-11]
+#### Version:
+#####   Package:
+#####    pixiu: 0.99.*.20230111
+#####
+#### **Descriptions：**
+     1.ea_tester.py:
+       1) Fix self.current_tick_index exception in execute_(self, ticket)
+
 ### [2022-12-28]
 #### Version:
 #####   Package:
 #####    pixiu: 0.98.*.20221228
 #####
 #### **Descriptions：**
      1.Add global API:
```

### Comparing `pixiu-0.98.0/README.md` & `pixiu-0.99.0/README.md`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/README.zh.md` & `pixiu-0.99.0/README.zh.md`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu/api/defines.py` & `pixiu-0.99.0/pixiu/api/defines.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu/api/errors.py` & `pixiu-0.99.0/pixiu/api/errors.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu/api/utils.py` & `pixiu-0.99.0/pixiu/api/utils.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu/api/v1/account.py` & `pixiu-0.99.0/pixiu/api/v1/account.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu/api/v1/api.py` & `pixiu-0.99.0/pixiu/api/v1/api.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu/api/v1/order.py` & `pixiu-0.99.0/pixiu/api/v1/order.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu/api/v1/symbol.py` & `pixiu-0.99.0/pixiu/api/v1/symbol.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu/base/api_base.py` & `pixiu-0.99.0/pixiu/base/api_base.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu/base/ea_base.py` & `pixiu-0.99.0/pixiu/base/ea_base.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu/base/ea_node_transformer.py` & `pixiu-0.99.0/pixiu/base/ea_node_transformer.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu/main.py` & `pixiu-0.99.0/pixiu/main.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu/pxtester.py` & `pixiu-0.99.0/pixiu/pxtester.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu/tester/ea_tester.py` & `pixiu-0.99.0/pixiu/tester/ea_tester.py`

 * *Files 0% similar despite different names*

```diff
@@ -2143,16 +2143,17 @@
                     self.__update_account_log(ticket)
                     # #
                     if exit != 0:
                         if exit == 2:
                             raise PXErrorCode(EID_EAT_NOT_ENOUGH_MONEY)
                         else:
                             raise PXErrorCode(EID_EAT_EA_DEAD)
-                    self.current_tick_index += 1
+                    # self.current_tick_index += 1
                     self.on_end_tick()
+                    self.current_tick_index += 1
                 except Exception as exc:
                     if isinstance(exc, AssertionError):
                         raise exc
                     traceback.print_exc()
                     exception_msg = self.on_execute_exception()
 
                     errid = EID_EAT_ERROR
```

### Comparing `pixiu-0.98.0/pixiu/tester/ea_tester_graph.py` & `pixiu-0.99.0/pixiu/tester/ea_tester_graph.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu/tester/tester_api_v1.py` & `pixiu-0.99.0/pixiu/tester/tester_api_v1.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/pixiu.egg-info/PKG-INFO` & `pixiu-0.99.0/pixiu.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pixiu
-Version: 0.98.0
+Version: 0.99.0
 Summary: PiXiu - A trading backtesting tool similar to MT4/MT5
 Home-page: https://github.com/tradepython/pixiu
 Author: tradepython
 Author-email: tradepython@icloud.com
 Project-URL: Bug Tracker, https://github.com/tradepython/pixiu/issues
 Keywords: Trading Backtest Forex Stocks MT4 MT5 MetaTrade
 Classifier: Programming Language :: Python :: 3
@@ -932,14 +932,23 @@
                      The errorid.
                   
                    
 ```
 
 
 
+### [2023-01-11]
+#### Version:
+#####   Package:
+#####    pixiu: 0.99.*.20230111
+#####
+#### **Descriptions：**
+     1.ea_tester.py:
+       1) Fix self.current_tick_index exception in execute_(self, ticket)
+
 ### [2022-12-28]
 #### Version:
 #####   Package:
 #####    pixiu: 0.98.*.20221228
 #####
 #### **Descriptions：**
      1.Add global API:
```

### Comparing `pixiu-0.98.0/pixiu.egg-info/SOURCES.txt` & `pixiu-0.99.0/pixiu.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/samples/.DS_Store` & `pixiu-0.99.0/samples/.DS_Store`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/samples/pixiu_sample.json` & `pixiu-0.99.0/samples/pixiu_sample.json`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/samples/pixiu_sample.py` & `pixiu-0.99.0/samples/pixiu_sample.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/setup.py` & `pixiu-0.99.0/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -28,15 +28,15 @@
     'WebTest >= 1.3.1',  # py3 compat
     'pytest',
     'pytest-cov',
 ]
 
 setup(
     name='pixiu',
-    version='0.98.0',
+    version='0.99.0',
     description='PiXiu - A trading backtesting tool similar to MT4/MT5',
     long_description=README + '\n\n' + CHANGES,
     long_description_content_type="text/markdown",
     classifiers=[
         'Programming Language :: Python :: 3',
         'License :: OSI Approved :: Apache Software License'
     ],
```

### Comparing `pixiu-0.98.0/tests/.DS_Store` & `pixiu-0.99.0/tests/.DS_Store`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/tests/scripts/v1/ts_base.py` & `pixiu-0.99.0/tests/scripts/v1/ts_base.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/tests/scripts/v1/ts_indicators.py` & `pixiu-0.99.0/tests/scripts/v1/ts_indicators.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/tests/scripts/v1/ts_order_buylimit.py` & `pixiu-0.99.0/tests/scripts/v1/ts_order_buylimit.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/tests/scripts/v1/ts_order_buystop.py` & `pixiu-0.99.0/tests/scripts/v1/ts_order_buystop.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/tests/scripts/v1/ts_order_market.py` & `pixiu-0.99.0/tests/scripts/v1/ts_order_market.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/tests/scripts/v1/ts_order_selllimit.py` & `pixiu-0.99.0/tests/scripts/v1/ts_order_selllimit.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/tests/scripts/v1/ts_order_sellstop.py` & `pixiu-0.99.0/tests/scripts/v1/ts_order_sellstop.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/tests/scripts/v1/ts_symbol_data.py` & `pixiu-0.99.0/tests/scripts/v1/ts_symbol_data.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/tests/test_pixiu.py` & `pixiu-0.99.0/tests/test_pixiu.py`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/tests/usdchf_m1_20210315-0329.csv` & `pixiu-0.99.0/tests/usdchf_m1_20210315-0329.csv`

 * *Files identical despite different names*

### Comparing `pixiu-0.98.0/tests/usdchf_m1_20210315-0415.csv` & `pixiu-0.99.0/tests/usdchf_m1_20210315-0415.csv`

 * *Files identical despite different names*


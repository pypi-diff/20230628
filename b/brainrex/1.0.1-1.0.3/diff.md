# Comparing `tmp/brainrex-1.0.1.tar.gz` & `tmp/brainrex-1.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/brainrex-1.0.1.tar", last modified: Thu Dec  5 11:39:19 2019, max compression
+gzip compressed data, was "brainrex-1.0.3.tar", last modified: Wed Jun 28 11:40:02 2023, max compression
```

## Comparing `brainrex-1.0.1.tar` & `brainrex-1.0.3.tar`

### file list

```diff
@@ -1,62 +1,58 @@
-drwxr-xr-x   0 ga        (1000) ga        (1000)        0 2019-12-05 11:39:19.000000 brainrex-1.0.1/
-drwxr-xr-x   0 ga        (1000) ga        (1000)        0 2019-12-05 11:39:19.000000 brainrex-1.0.1/test/
--rw-rw-r--   0 ga        (1000) ga        (1000)      915 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_point_time_series.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     1667 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_integrations_api.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      855 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_exchange.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      920 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_anomaly_api.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      905 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_series_response.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      947 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_series_response_point.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      831 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_ohclv.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      971 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_exchange_assets_response.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      905 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_candle_response.py
--rw-rw-r--   0 ga        (1000) ga        (1000)        0 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/__init__.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      831 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_error.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      823 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_text.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      921 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_orderbook_request.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     1013 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_exchange_assets_response_inner.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      937 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_supported_exchanges.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      929 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_orderbook_response.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     1446 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_language_api.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      947 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_ticker_response_inner.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      905 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_ticker_response.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      873 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_time_series.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      897 2019-12-05 11:32:26.000000 brainrex-1.0.1/test/test_candle_request.py
--rw-r--r--   0 ga        (1000) ga        (1000)      547 2019-12-05 11:39:19.000000 brainrex-1.0.1/PKG-INFO
-drwxr-xr-x   0 ga        (1000) ga        (1000)        0 2019-12-05 11:39:19.000000 brainrex-1.0.1/brainrex.egg-info/
--rw-r--r--   0 ga        (1000) ga        (1000)      547 2019-12-05 11:39:19.000000 brainrex-1.0.1/brainrex.egg-info/PKG-INFO
--rw-r--r--   0 ga        (1000) ga        (1000)        1 2019-12-05 11:39:19.000000 brainrex-1.0.1/brainrex.egg-info/dependency_links.txt
--rw-r--r--   0 ga        (1000) ga        (1000)     1611 2019-12-05 11:39:19.000000 brainrex-1.0.1/brainrex.egg-info/SOURCES.txt
--rw-r--r--   0 ga        (1000) ga        (1000)       14 2019-12-05 11:39:19.000000 brainrex-1.0.1/brainrex.egg-info/top_level.txt
--rw-r--r--   0 ga        (1000) ga        (1000)       64 2019-12-05 11:39:19.000000 brainrex-1.0.1/brainrex.egg-info/requires.txt
-drwxr-xr-x   0 ga        (1000) ga        (1000)        0 2019-12-05 11:39:19.000000 brainrex-1.0.1/brainrex/
--rw-rw-r--   0 ga        (1000) ga        (1000)     7980 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/configuration.py
-drwxr-xr-x   0 ga        (1000) ga        (1000)        0 2019-12-05 11:39:19.000000 brainrex-1.0.1/brainrex/api/
--rw-rw-r--   0 ga        (1000) ga        (1000)     5270 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/api/anomaly_api.py
--rw-rw-r--   0 ga        (1000) ga        (1000)      243 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/api/__init__.py
--rw-rw-r--   0 ga        (1000) ga        (1000)    21091 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/api/integrations_api.py
--rw-rw-r--   0 ga        (1000) ga        (1000)    13128 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/api/language_api.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     1663 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/__init__.py
--rw-rw-r--   0 ga        (1000) ga        (1000)    24998 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/api_client.py
-drwxr-xr-x   0 ga        (1000) ga        (1000)        0 2019-12-05 11:39:19.000000 brainrex-1.0.1/brainrex/models/
--rw-rw-r--   0 ga        (1000) ga        (1000)     4159 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/error.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     2480 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/exchange_assets_response.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     2448 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/ticker_response.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     5123 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/supported_exchanges.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     1366 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/__init__.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     4001 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/series_response_point.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     2448 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/candle_response.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     5823 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/exchange_assets_response_inner.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     7778 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/ticker_response_inner.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     6000 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/orderbook_request.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     2448 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/series_response.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     5948 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/candle_request.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     6020 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/orderbook_response.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     9436 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/ohclv.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     2432 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/time_series.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     3979 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/point_time_series.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     3081 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/text.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     3213 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/models/exchange.py
--rw-rw-r--   0 ga        (1000) ga        (1000)    13195 2019-12-05 11:32:26.000000 brainrex-1.0.1/brainrex/rest.py
--rw-rw-r--   0 ga        (1000) ga        (1000)     4979 2019-12-05 07:27:07.000000 brainrex-1.0.1/README.md
--rw-rw-r--   0 ga        (1000) ga        (1000)     1394 2019-12-05 11:37:23.000000 brainrex-1.0.1/setup.py
--rw-r--r--   0 ga        (1000) ga        (1000)       79 2019-12-05 11:39:19.000000 brainrex-1.0.1/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:40:02.041983 brainrex-1.0.3/
+-rw-r--r--   0 runner    (1001) docker     (123)      532 2023-06-28 11:40:02.041983 brainrex-1.0.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4722 2023-06-28 11:39:49.000000 brainrex-1.0.3/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:40:02.033983 brainrex-1.0.3/brainrex/
+-rw-r--r--   0 runner    (1001) docker     (123)     1771 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:40:02.037983 brainrex-1.0.3/brainrex/api/
+-rw-r--r--   0 runner    (1001) docker     (123)      243 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/api/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5515 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/api/anomaly_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13256 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/api/integrations_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14482 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/api/language_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25280 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/api_client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8480 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/configuration.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:40:02.037983 brainrex-1.0.3/brainrex/models/
+-rw-r--r--   0 runner    (1001) docker     (123)     1475 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6182 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/candle_request.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2684 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/candle_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4393 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/error.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3447 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/exchange.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2716 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/exchange_assets_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6057 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/exchange_assets_response_inner.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9670 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/ohclv.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6234 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/orderbook_request.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6254 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/orderbook_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4213 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/point_time_series.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5357 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/supported_exchanges.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3315 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/text.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2684 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/ticker_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8012 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/ticker_response_inner.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2668 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/models/time_series.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13256 2023-06-28 11:39:49.000000 brainrex-1.0.3/brainrex/rest.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:40:02.033983 brainrex-1.0.3/brainrex.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      532 2023-06-28 11:40:01.000000 brainrex-1.0.3/brainrex.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1461 2023-06-28 11:40:01.000000 brainrex-1.0.3/brainrex.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:40:01.000000 brainrex-1.0.3/brainrex.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       48 2023-06-28 11:40:01.000000 brainrex-1.0.3/brainrex.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       14 2023-06-28 11:40:01.000000 brainrex-1.0.3/brainrex.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 11:40:02.041983 brainrex-1.0.3/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1492 2023-06-28 11:39:49.000000 brainrex-1.0.3/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:40:02.037983 brainrex-1.0.3/test/
+-rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1133 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_anomaly_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1135 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_candle_request.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1143 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_candle_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1069 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_error.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1093 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_exchange.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1209 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_exchange_assets_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1251 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_exchange_assets_response_inner.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1478 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_integrations_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1585 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_language_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1069 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_ohclv.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1159 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_orderbook_request.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1167 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_orderbook_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1153 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_point_time_series.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1175 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_supported_exchanges.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1061 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_text.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1143 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_ticker_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1185 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_ticker_response_inner.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1111 2023-06-28 11:39:49.000000 brainrex-1.0.3/test/test_time_series.py
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `brainrex-1.0.1/test/test_integrations_api.py` & `brainrex-1.0.3/test/test_integrations_api.py`

 * *Files 17% similar despite different names*

```diff
@@ -1,63 +1,48 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import unittest
 
 import brainrex
 from brainrex.api.integrations_api import IntegrationsApi  # noqa: E501
 from brainrex.rest import ApiException
 
 
 class TestIntegrationsApi(unittest.TestCase):
     """IntegrationsApi unit test stubs"""
 
     def setUp(self):
-        self.api = brainrex.api.integrations_api.IntegrationsApi()  # noqa: E501
+        self.api = IntegrationsApi()  # noqa: E501
 
     def tearDown(self):
         pass
 
     def test_crypto_get_candle_data(self):
         """Test case for crypto_get_candle_data
 
         Downloads candle format market data  # noqa: E501
         """
         pass
 
     def test_crypto_get_exchange_assets(self):
         """Test case for crypto_get_exchange_assets
 
-        Gets all currency pairs traded in selected exchange  # noqa: E501
-        """
-        pass
-
-    def test_crypto_get_orderbooks(self):
-        """Test case for crypto_get_orderbooks
-
-        Downloads candle format market data  # noqa: E501
-        """
-        pass
-
-    def test_crypto_get_supported_exchanges(self):
-        """Test case for crypto_get_supported_exchanges
-
-        Gets all cryptocurrency exchanges supported by the Brainrex API  # noqa: E501
+        Gets all coin pairs traded in specified exchange  # noqa: E501
         """
         pass
 
     def test_crypto_get_ticker(self):
         """Test case for crypto_get_ticker
 
         Downloads candle format market data  # noqa: E501
```

### Comparing `brainrex-1.0.1/test/test_anomaly_api.py` & `brainrex-1.0.3/test/test_time_series.py`

 * *Files 21% similar despite different names*

```diff
@@ -1,41 +1,39 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import unittest
 
 import brainrex
-from brainrex.api.anomaly_api import AnomalyApi  # noqa: E501
+from brainrex.models.time_series import TimeSeries  # noqa: E501
 from brainrex.rest import ApiException
 
 
-class TestAnomalyApi(unittest.TestCase):
-    """AnomalyApi unit test stubs"""
+class TestTimeSeries(unittest.TestCase):
+    """TimeSeries unit test stubs"""
 
     def setUp(self):
-        self.api = brainrex.api.anomaly_api.AnomalyApi()  # noqa: E501
+        pass
 
     def tearDown(self):
         pass
 
-    def test_anomaly_batch(self):
-        """Test case for anomaly_batch
-
-        Detects anomalies in historical data in batches. This endpoint uses your entire dataset as input  # noqa: E501
-        """
+    def testTimeSeries(self):
+        """Test TimeSeries"""
+        # FIXME: construct object with mandatory attributes with example values
+        # model = brainrex.models.time_series.TimeSeries()  # noqa: E501
         pass
 
 
 if __name__ == '__main__':
     unittest.main()
```

### Comparing `brainrex-1.0.1/test/test_series_response.py` & `brainrex-1.0.3/test/test_error.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,40 +1,39 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import unittest
 
 import brainrex
-from brainrex.models.series_response import SeriesResponse  # noqa: E501
+from brainrex.models.error import Error  # noqa: E501
 from brainrex.rest import ApiException
 
 
-class TestSeriesResponse(unittest.TestCase):
-    """SeriesResponse unit test stubs"""
+class TestError(unittest.TestCase):
+    """Error unit test stubs"""
 
     def setUp(self):
         pass
 
     def tearDown(self):
         pass
 
-    def testSeriesResponse(self):
-        """Test SeriesResponse"""
+    def testError(self):
+        """Test Error"""
         # FIXME: construct object with mandatory attributes with example values
-        # model = brainrex.models.series_response.SeriesResponse()  # noqa: E501
+        # model = brainrex.models.error.Error()  # noqa: E501
         pass
 
 
 if __name__ == '__main__':
     unittest.main()
```

### Comparing `brainrex-1.0.1/test/test_ohclv.py` & `brainrex-1.0.3/test/test_ohclv.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,20 +1,19 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import unittest
 
 import brainrex
 from brainrex.models.ohclv import OHCLV  # noqa: E501
 from brainrex.rest import ApiException
```

### Comparing `brainrex-1.0.1/test/test_exchange_assets_response.py` & `brainrex-1.0.3/test/test_exchange_assets_response.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,20 +1,19 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import unittest
 
 import brainrex
 from brainrex.models.exchange_assets_response import ExchangeAssetsResponse  # noqa: E501
 from brainrex.rest import ApiException
```

### Comparing `brainrex-1.0.1/test/test_candle_response.py` & `brainrex-1.0.3/test/test_candle_response.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,20 +1,19 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import unittest
 
 import brainrex
 from brainrex.models.candle_response import CandleResponse  # noqa: E501
 from brainrex.rest import ApiException
```

### Comparing `brainrex-1.0.1/test/test_error.py` & `brainrex-1.0.3/test/test_orderbook_request.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,40 +1,39 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import unittest
 
 import brainrex
-from brainrex.models.error import Error  # noqa: E501
+from brainrex.models.orderbook_request import OrderbookRequest  # noqa: E501
 from brainrex.rest import ApiException
 
 
-class TestError(unittest.TestCase):
-    """Error unit test stubs"""
+class TestOrderbookRequest(unittest.TestCase):
+    """OrderbookRequest unit test stubs"""
 
     def setUp(self):
         pass
 
     def tearDown(self):
         pass
 
-    def testError(self):
-        """Test Error"""
+    def testOrderbookRequest(self):
+        """Test OrderbookRequest"""
         # FIXME: construct object with mandatory attributes with example values
-        # model = brainrex.models.error.Error()  # noqa: E501
+        # model = brainrex.models.orderbook_request.OrderbookRequest()  # noqa: E501
         pass
 
 
 if __name__ == '__main__':
     unittest.main()
```

### Comparing `brainrex-1.0.1/test/test_text.py` & `brainrex-1.0.3/test/test_text.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,20 +1,19 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import unittest
 
 import brainrex
 from brainrex.models.text import Text  # noqa: E501
 from brainrex.rest import ApiException
```

### Comparing `brainrex-1.0.1/test/test_exchange_assets_response_inner.py` & `brainrex-1.0.3/test/test_exchange_assets_response_inner.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,20 +1,19 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import unittest
 
 import brainrex
 from brainrex.models.exchange_assets_response_inner import ExchangeAssetsResponseInner  # noqa: E501
 from brainrex.rest import ApiException
```

### Comparing `brainrex-1.0.1/test/test_orderbook_response.py` & `brainrex-1.0.3/test/test_orderbook_response.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,20 +1,19 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import unittest
 
 import brainrex
 from brainrex.models.orderbook_response import OrderbookResponse  # noqa: E501
 from brainrex.rest import ApiException
```

### Comparing `brainrex-1.0.1/test/test_language_api.py` & `brainrex-1.0.3/test/test_language_api.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,49 +1,48 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import unittest
 
 import brainrex
 from brainrex.api.language_api import LanguageApi  # noqa: E501
 from brainrex.rest import ApiException
 
 
 class TestLanguageApi(unittest.TestCase):
     """LanguageApi unit test stubs"""
 
     def setUp(self):
-        self.api = brainrex.api.language_api.LanguageApi()  # noqa: E501
+        self.api = LanguageApi()  # noqa: E501
 
     def tearDown(self):
         pass
 
     def test_language_get_crypto_entities(self):
         """Test case for language_get_crypto_entities
 
-        Named Entity Recognition software capable of understanding cryptocurrency and blockchain speficic language.  # noqa: E501
+        Extracts known crypto entities like coin names, exchanges, media from text.  # noqa: E501
         """
         pass
 
     def test_language_get_general_sentiment(self):
         """Test case for language_get_general_sentiment
 
-        This endpoints returns a score from -1 to +1 where depending on negative or positive attitude in the text.  # noqa: E501
+        Returns a -1 to 1 score, depending on positive/negative sentiment  # noqa: E501
         """
         pass
 
     def test_language_get_price_sentiment(self):
         """Test case for language_get_price_sentiment
 
         Sentiment analysis score using a model trained for buy signals.  # noqa: E501
```

### Comparing `brainrex-1.0.1/test/test_ticker_response_inner.py` & `brainrex-1.0.3/test/test_ticker_response_inner.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,20 +1,19 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import unittest
 
 import brainrex
 from brainrex.models.ticker_response_inner import TickerResponseInner  # noqa: E501
 from brainrex.rest import ApiException
```

### Comparing `brainrex-1.0.1/test/test_ticker_response.py` & `brainrex-1.0.3/test/test_ticker_response.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,20 +1,19 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import unittest
 
 import brainrex
 from brainrex.models.ticker_response import TickerResponse  # noqa: E501
 from brainrex.rest import ApiException
```

### Comparing `brainrex-1.0.1/test/test_candle_request.py` & `brainrex-1.0.3/test/test_candle_request.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,20 +1,19 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import unittest
 
 import brainrex
 from brainrex.models.candle_request import CandleRequest  # noqa: E501
 from brainrex.rest import ApiException
```

### Comparing `brainrex-1.0.1/brainrex.egg-info/SOURCES.txt` & `brainrex-1.0.3/brainrex.egg-info/SOURCES.txt`

 * *Files 16% similar despite different names*

```diff
@@ -1,9 +1,8 @@
 README.md
-setup.cfg
 setup.py
 brainrex/__init__.py
 brainrex/api_client.py
 brainrex/configuration.py
 brainrex/rest.py
 brainrex.egg-info/PKG-INFO
 brainrex.egg-info/SOURCES.txt
@@ -21,16 +20,14 @@
 brainrex/models/exchange.py
 brainrex/models/exchange_assets_response.py
 brainrex/models/exchange_assets_response_inner.py
 brainrex/models/ohclv.py
 brainrex/models/orderbook_request.py
 brainrex/models/orderbook_response.py
 brainrex/models/point_time_series.py
-brainrex/models/series_response.py
-brainrex/models/series_response_point.py
 brainrex/models/supported_exchanges.py
 brainrex/models/text.py
 brainrex/models/ticker_response.py
 brainrex/models/ticker_response_inner.py
 brainrex/models/time_series.py
 test/__init__.py
 test/test_anomaly_api.py
@@ -42,14 +39,12 @@
 test/test_exchange_assets_response_inner.py
 test/test_integrations_api.py
 test/test_language_api.py
 test/test_ohclv.py
 test/test_orderbook_request.py
 test/test_orderbook_response.py
 test/test_point_time_series.py
-test/test_series_response.py
-test/test_series_response_point.py
 test/test_supported_exchanges.py
 test/test_text.py
 test/test_ticker_response.py
 test/test_ticker_response_inner.py
 test/test_time_series.py
```

### Comparing `brainrex-1.0.1/brainrex/configuration.py` & `brainrex-1.0.3/brainrex/configuration.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,63 +1,70 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import copy
 import logging
 import multiprocessing
 import sys
 import urllib3
 
 import six
 from six.moves import http_client as httplib
 
 
-class Configuration(object):
+class TypeWithDefault(type):
+    def __init__(cls, name, bases, dct):
+        super(TypeWithDefault, cls).__init__(name, bases, dct)
+        cls._default = None
+
+    def __call__(cls):
+        if cls._default is None:
+            cls._default = type.__call__(cls)
+        return copy.copy(cls._default)
+
+    def set_default(cls, default):
+        cls._default = copy.copy(default)
+
+
+class Configuration(six.with_metaclass(TypeWithDefault, object)):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Ref: https://github.com/swagger-api/swagger-codegen
     Do not edit the class manually.
     """
 
-    _default = None
-
     def __init__(self):
         """Constructor"""
-        if self._default:
-            for key in self._default.__dict__.keys():
-                self.__dict__[key] = copy.copy(self._default.__dict__[key])
-            return
-
         # Default Base url
-        self.host = "https://api.bitlongs.com"
+        self.host = "https://api.brainrex.com"
         # Temp file folder for downloading files
         self.temp_folder_path = None
 
         # Authentication Settings
         # dict to store API key(s)
         self.api_key = {}
         # dict to store API prefix (e.g. Bearer)
         self.api_key_prefix = {}
+        # function to refresh API key if expired
+        self.refresh_api_key_hook = None
         # Username for HTTP basic authentication
         self.username = ""
         # Password for HTTP basic authentication
         self.password = ""
-
         # Logging Settings
         self.logger = {}
         self.logger["package_logger"] = logging.getLogger("brainrex")
         self.logger["urllib3_logger"] = logging.getLogger("urllib3")
         # Log format
         self.logger_format = '%(asctime)s %(levelname)s %(message)s'
         # Log stream handler
@@ -90,18 +97,14 @@
         self.connection_pool_maxsize = multiprocessing.cpu_count() * 5
 
         # Proxy URL
         self.proxy = None
         # Safe chars for path_param
         self.safe_chars_for_path_param = ''
 
-    @classmethod
-    def set_default(cls, default):
-        cls._default = default
-
     @property
     def logger_file(self):
         """The logger file.
 
         If the logger_file is None, then add stream handler and remove file
         handler. Otherwise, add file handler and remove stream handler.
 
@@ -196,19 +199,24 @@
 
     def get_api_key_with_prefix(self, identifier):
         """Gets API key (with prefix if set).
 
         :param identifier: The identifier of apiKey.
         :return: The token for api key authentication.
         """
-        if (self.api_key.get(identifier) and
-                self.api_key_prefix.get(identifier)):
-            return self.api_key_prefix[identifier] + ' ' + self.api_key[identifier]  # noqa: E501
-        elif self.api_key.get(identifier):
-            return self.api_key[identifier]
+        if self.refresh_api_key_hook:
+            self.refresh_api_key_hook(self)
+
+        key = self.api_key.get(identifier)
+        if key:
+            prefix = self.api_key_prefix.get(identifier)
+            if prefix:
+                return "%s %s" % (prefix, key)
+            else:
+                return key
 
     def get_basic_auth_token(self):
         """Gets HTTP basic authentication header (string).
 
         :return: The token for basic HTTP authentication.
         """
         return urllib3.util.make_headers(
@@ -224,21 +232,20 @@
             'APIKeyHeader':
                 {
                     'type': 'api_key',
                     'in': 'header',
                     'key': 'x-api-key',
                     'value': self.get_api_key_with_prefix('x-api-key')
                 },
-
         }
 
     def to_debug_report(self):
         """Gets the essential information for debugging.
 
         :return: The report for debugging.
         """
         return "Python SDK Debug Report:\n"\
                "OS: {env}\n"\
                "Python Version: {pyversion}\n"\
-               "Version of the API: 1.0.1\n"\
-               "SDK Package Version: 0.9.4".\
+               "Version of the API: 1.0.3-oas3\n"\
+               "SDK Package Version: 1.0.3".\
                format(env=sys.platform, pyversion=sys.version)
```

### Comparing `brainrex-1.0.1/brainrex/api/anomaly_api.py` & `brainrex-1.0.3/brainrex/api/anomaly_api.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,20 +1,19 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import re  # noqa: F401
 
 # python 2 and python 3 compatibility library
 import six
 
@@ -39,15 +38,15 @@
         The Anomaly Detect endpoint ingests time series data of all types, then monitors and detects abnormalities historical time series data. <br><br> Our AI selects from several models, choosing the one that fits the given data best, and we give you the avality to customize the sensitivy of the model. Our model has been trained to recognize anomalies in popular blockchain networks e.g. Bitcoin, Ethereum, learning from past events.  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
         >>> thread = api.anomaly_batch(async_req=True)
         >>> result = thread.get()
 
         :param async_req bool
-        :param TimeSeries request: Time Series to be analyzed, with the following format.
+        :param list[PointTimeSeries] body: Time Series to be analyzed, with the following format.
         :return: list[bool]
                  If the method is called asynchronously,
                  returns the request thread.
         """
         kwargs['_return_http_data_only'] = True
         if kwargs.get('async_req'):
             return self.anomaly_batch_with_http_info(**kwargs)  # noqa: E501
@@ -61,21 +60,21 @@
         The Anomaly Detect endpoint ingests time series data of all types, then monitors and detects abnormalities historical time series data. <br><br> Our AI selects from several models, choosing the one that fits the given data best, and we give you the avality to customize the sensitivy of the model. Our model has been trained to recognize anomalies in popular blockchain networks e.g. Bitcoin, Ethereum, learning from past events.  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
         >>> thread = api.anomaly_batch_with_http_info(async_req=True)
         >>> result = thread.get()
 
         :param async_req bool
-        :param TimeSeries request: Time Series to be analyzed, with the following format.
+        :param list[PointTimeSeries] body: Time Series to be analyzed, with the following format.
         :return: list[bool]
                  If the method is called asynchronously,
                  returns the request thread.
         """
 
-        all_params = ['request']  # noqa: E501
+        all_params = ['body']  # noqa: E501
         all_params.append('async_req')
         all_params.append('_return_http_data_only')
         all_params.append('_preload_content')
         all_params.append('_request_timeout')
 
         params = locals()
         for key, val in six.iteritems(params['kwargs']):
@@ -95,16 +94,16 @@
 
         header_params = {}
 
         form_params = []
         local_var_files = {}
 
         body_params = None
-        if 'request' in params:
-            body_params = params['request']
+        if 'body' in params:
+            body_params = params['body']
         # HTTP header `Accept`
         header_params['Accept'] = self.api_client.select_header_accept(
             ['application/json'])  # noqa: E501
 
         # HTTP header `Content-Type`
         header_params['Content-Type'] = self.api_client.select_header_content_type(  # noqa: E501
             ['application/json'])  # noqa: E501
```

### Comparing `brainrex-1.0.1/brainrex/api/integrations_api.py` & `brainrex-1.0.3/brainrex/api/integrations_api.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,20 +1,19 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import re  # noqa: F401
 
 # python 2 and python 3 compatibility library
 import six
 
@@ -29,86 +28,86 @@
     """
 
     def __init__(self, api_client=None):
         if api_client is None:
             api_client = ApiClient()
         self.api_client = api_client
 
-    def crypto_get_candle_data(self, candle_request, **kwargs):  # noqa: E501
+    def crypto_get_candle_data(self, body, **kwargs):  # noqa: E501
         """Downloads candle format market data  # noqa: E501
 
         Returns a list of candle data from specified market and data range  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.crypto_get_candle_data(candle_request, async_req=True)
+        >>> thread = api.crypto_get_candle_data(body, async_req=True)
         >>> result = thread.get()
 
         :param async_req bool
-        :param CandleRequest candle_request: The Get candles end point return market data in Open High Close Volume format. In order to use this endpoint you need to enter your API keys to your data provider in the console (required)
+        :param CandleRequest body: The Get candles end point return market data in Open High Close Volume format. In order to use this endpoint you need to enter your API keys to your data provider in the console (required)
         :return: CandleResponse
                  If the method is called asynchronously,
                  returns the request thread.
         """
         kwargs['_return_http_data_only'] = True
         if kwargs.get('async_req'):
-            return self.crypto_get_candle_data_with_http_info(candle_request, **kwargs)  # noqa: E501
+            return self.crypto_get_candle_data_with_http_info(body, **kwargs)  # noqa: E501
         else:
-            (data) = self.crypto_get_candle_data_with_http_info(candle_request, **kwargs)  # noqa: E501
+            (data) = self.crypto_get_candle_data_with_http_info(body, **kwargs)  # noqa: E501
             return data
 
-    def crypto_get_candle_data_with_http_info(self, candle_request, **kwargs):  # noqa: E501
+    def crypto_get_candle_data_with_http_info(self, body, **kwargs):  # noqa: E501
         """Downloads candle format market data  # noqa: E501
 
         Returns a list of candle data from specified market and data range  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.crypto_get_candle_data_with_http_info(candle_request, async_req=True)
+        >>> thread = api.crypto_get_candle_data_with_http_info(body, async_req=True)
         >>> result = thread.get()
 
         :param async_req bool
-        :param CandleRequest candle_request: The Get candles end point return market data in Open High Close Volume format. In order to use this endpoint you need to enter your API keys to your data provider in the console (required)
+        :param CandleRequest body: The Get candles end point return market data in Open High Close Volume format. In order to use this endpoint you need to enter your API keys to your data provider in the console (required)
         :return: CandleResponse
                  If the method is called asynchronously,
                  returns the request thread.
         """
 
-        all_params = ['candle_request']  # noqa: E501
+        all_params = ['body']  # noqa: E501
         all_params.append('async_req')
         all_params.append('_return_http_data_only')
         all_params.append('_preload_content')
         all_params.append('_request_timeout')
 
         params = locals()
         for key, val in six.iteritems(params['kwargs']):
             if key not in all_params:
                 raise TypeError(
                     "Got an unexpected keyword argument '%s'"
                     " to method crypto_get_candle_data" % key
                 )
             params[key] = val
         del params['kwargs']
-        # verify the required parameter 'candle_request' is set
-        if ('candle_request' not in params or
-                params['candle_request'] is None):
-            raise ValueError("Missing the required parameter `candle_request` when calling `crypto_get_candle_data`")  # noqa: E501
+        # verify the required parameter 'body' is set
+        if ('body' not in params or
+                params['body'] is None):
+            raise ValueError("Missing the required parameter `body` when calling `crypto_get_candle_data`")  # noqa: E501
 
         collection_formats = {}
 
         path_params = {}
 
         query_params = []
 
         header_params = {}
 
         form_params = []
         local_var_files = {}
 
         body_params = None
-        if 'candle_request' in params:
-            body_params = params['candle_request']
+        if 'body' in params:
+            body_params = params['body']
         # HTTP header `Accept`
         header_params['Accept'] = self.api_client.select_header_accept(
             ['application/json'])  # noqa: E501
 
         # HTTP header `Content-Type`
         header_params['Content-Type'] = self.api_client.select_header_content_type(  # noqa: E501
             ['application/json'])  # noqa: E501
@@ -128,86 +127,86 @@
             auth_settings=auth_settings,
             async_req=params.get('async_req'),
             _return_http_data_only=params.get('_return_http_data_only'),
             _preload_content=params.get('_preload_content', True),
             _request_timeout=params.get('_request_timeout'),
             collection_formats=collection_formats)
 
-    def crypto_get_exchange_assets(self, exchange, **kwargs):  # noqa: E501
-        """Gets all currency pairs traded in selected exchange  # noqa: E501
+    def crypto_get_exchange_assets(self, body, **kwargs):  # noqa: E501
+        """Gets all coin pairs traded in specified exchange  # noqa: E501
 
-        Returns a list of candle data from specified market and data range  # noqa: E501
+        This endpoint returns all the Available currency pairs  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.crypto_get_exchange_assets(exchange, async_req=True)
+        >>> thread = api.crypto_get_exchange_assets(body, async_req=True)
         >>> result = thread.get()
 
         :param async_req bool
-        :param Exchange exchange: Name of the cryptocurrency exchange (required)
+        :param Exchange body: Name of the cryptocurrency exchange (required)
         :return: ExchangeAssetsResponse
                  If the method is called asynchronously,
                  returns the request thread.
         """
         kwargs['_return_http_data_only'] = True
         if kwargs.get('async_req'):
-            return self.crypto_get_exchange_assets_with_http_info(exchange, **kwargs)  # noqa: E501
+            return self.crypto_get_exchange_assets_with_http_info(body, **kwargs)  # noqa: E501
         else:
-            (data) = self.crypto_get_exchange_assets_with_http_info(exchange, **kwargs)  # noqa: E501
+            (data) = self.crypto_get_exchange_assets_with_http_info(body, **kwargs)  # noqa: E501
             return data
 
-    def crypto_get_exchange_assets_with_http_info(self, exchange, **kwargs):  # noqa: E501
-        """Gets all currency pairs traded in selected exchange  # noqa: E501
+    def crypto_get_exchange_assets_with_http_info(self, body, **kwargs):  # noqa: E501
+        """Gets all coin pairs traded in specified exchange  # noqa: E501
 
-        Returns a list of candle data from specified market and data range  # noqa: E501
+        This endpoint returns all the Available currency pairs  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.crypto_get_exchange_assets_with_http_info(exchange, async_req=True)
+        >>> thread = api.crypto_get_exchange_assets_with_http_info(body, async_req=True)
         >>> result = thread.get()
 
         :param async_req bool
-        :param Exchange exchange: Name of the cryptocurrency exchange (required)
+        :param Exchange body: Name of the cryptocurrency exchange (required)
         :return: ExchangeAssetsResponse
                  If the method is called asynchronously,
                  returns the request thread.
         """
 
-        all_params = ['exchange']  # noqa: E501
+        all_params = ['body']  # noqa: E501
         all_params.append('async_req')
         all_params.append('_return_http_data_only')
         all_params.append('_preload_content')
         all_params.append('_request_timeout')
 
         params = locals()
         for key, val in six.iteritems(params['kwargs']):
             if key not in all_params:
                 raise TypeError(
                     "Got an unexpected keyword argument '%s'"
                     " to method crypto_get_exchange_assets" % key
                 )
             params[key] = val
         del params['kwargs']
-        # verify the required parameter 'exchange' is set
-        if ('exchange' not in params or
-                params['exchange'] is None):
-            raise ValueError("Missing the required parameter `exchange` when calling `crypto_get_exchange_assets`")  # noqa: E501
+        # verify the required parameter 'body' is set
+        if ('body' not in params or
+                params['body'] is None):
+            raise ValueError("Missing the required parameter `body` when calling `crypto_get_exchange_assets`")  # noqa: E501
 
         collection_formats = {}
 
         path_params = {}
 
         query_params = []
 
         header_params = {}
 
         form_params = []
         local_var_files = {}
 
         body_params = None
-        if 'exchange' in params:
-            body_params = params['exchange']
+        if 'body' in params:
+            body_params = params['body']
         # HTTP header `Accept`
         header_params['Accept'] = self.api_client.select_header_accept(
             ['application/json'])  # noqa: E501
 
         # HTTP header `Content-Type`
         header_params['Content-Type'] = self.api_client.select_header_content_type(  # noqa: E501
             ['application/json'])  # noqa: E501
@@ -227,276 +226,86 @@
             auth_settings=auth_settings,
             async_req=params.get('async_req'),
             _return_http_data_only=params.get('_return_http_data_only'),
             _preload_content=params.get('_preload_content', True),
             _request_timeout=params.get('_request_timeout'),
             collection_formats=collection_formats)
 
-    def crypto_get_orderbooks(self, orderbook_request, **kwargs):  # noqa: E501
-        """Downloads candle format market data  # noqa: E501
-
-        Returns a list of candle data from specified market and data range  # noqa: E501
-        This method makes a synchronous HTTP request by default. To make an
-        asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.crypto_get_orderbooks(orderbook_request, async_req=True)
-        >>> result = thread.get()
-
-        :param async_req bool
-        :param OrderbookRequest orderbook_request: Exchange, trading pair and date rage for data (required)
-        :return: OrderbookResponse
-                 If the method is called asynchronously,
-                 returns the request thread.
-        """
-        kwargs['_return_http_data_only'] = True
-        if kwargs.get('async_req'):
-            return self.crypto_get_orderbooks_with_http_info(orderbook_request, **kwargs)  # noqa: E501
-        else:
-            (data) = self.crypto_get_orderbooks_with_http_info(orderbook_request, **kwargs)  # noqa: E501
-            return data
-
-    def crypto_get_orderbooks_with_http_info(self, orderbook_request, **kwargs):  # noqa: E501
-        """Downloads candle format market data  # noqa: E501
-
-        Returns a list of candle data from specified market and data range  # noqa: E501
-        This method makes a synchronous HTTP request by default. To make an
-        asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.crypto_get_orderbooks_with_http_info(orderbook_request, async_req=True)
-        >>> result = thread.get()
-
-        :param async_req bool
-        :param OrderbookRequest orderbook_request: Exchange, trading pair and date rage for data (required)
-        :return: OrderbookResponse
-                 If the method is called asynchronously,
-                 returns the request thread.
-        """
-
-        all_params = ['orderbook_request']  # noqa: E501
-        all_params.append('async_req')
-        all_params.append('_return_http_data_only')
-        all_params.append('_preload_content')
-        all_params.append('_request_timeout')
-
-        params = locals()
-        for key, val in six.iteritems(params['kwargs']):
-            if key not in all_params:
-                raise TypeError(
-                    "Got an unexpected keyword argument '%s'"
-                    " to method crypto_get_orderbooks" % key
-                )
-            params[key] = val
-        del params['kwargs']
-        # verify the required parameter 'orderbook_request' is set
-        if ('orderbook_request' not in params or
-                params['orderbook_request'] is None):
-            raise ValueError("Missing the required parameter `orderbook_request` when calling `crypto_get_orderbooks`")  # noqa: E501
-
-        collection_formats = {}
-
-        path_params = {}
-
-        query_params = []
-
-        header_params = {}
-
-        form_params = []
-        local_var_files = {}
-
-        body_params = None
-        if 'orderbook_request' in params:
-            body_params = params['orderbook_request']
-        # HTTP header `Accept`
-        header_params['Accept'] = self.api_client.select_header_accept(
-            ['application/json'])  # noqa: E501
-
-        # HTTP header `Content-Type`
-        header_params['Content-Type'] = self.api_client.select_header_content_type(  # noqa: E501
-            ['application/json'])  # noqa: E501
-
-        # Authentication setting
-        auth_settings = ['APIKeyHeader']  # noqa: E501
-
-        return self.api_client.call_api(
-            '/crypto/get_orderbooks', 'POST',
-            path_params,
-            query_params,
-            header_params,
-            body=body_params,
-            post_params=form_params,
-            files=local_var_files,
-            response_type='OrderbookResponse',  # noqa: E501
-            auth_settings=auth_settings,
-            async_req=params.get('async_req'),
-            _return_http_data_only=params.get('_return_http_data_only'),
-            _preload_content=params.get('_preload_content', True),
-            _request_timeout=params.get('_request_timeout'),
-            collection_formats=collection_formats)
-
-    def crypto_get_supported_exchanges(self, **kwargs):  # noqa: E501
-        """Gets all cryptocurrency exchanges supported by the Brainrex API  # noqa: E501
-
-        Returns a list of candle data from specified market and data range  # noqa: E501
-        This method makes a synchronous HTTP request by default. To make an
-        asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.crypto_get_supported_exchanges(async_req=True)
-        >>> result = thread.get()
-
-        :param async_req bool
-        :return: SupportedExchanges
-                 If the method is called asynchronously,
-                 returns the request thread.
-        """
-        kwargs['_return_http_data_only'] = True
-        if kwargs.get('async_req'):
-            return self.crypto_get_supported_exchanges_with_http_info(**kwargs)  # noqa: E501
-        else:
-            (data) = self.crypto_get_supported_exchanges_with_http_info(**kwargs)  # noqa: E501
-            return data
-
-    def crypto_get_supported_exchanges_with_http_info(self, **kwargs):  # noqa: E501
-        """Gets all cryptocurrency exchanges supported by the Brainrex API  # noqa: E501
-
-        Returns a list of candle data from specified market and data range  # noqa: E501
-        This method makes a synchronous HTTP request by default. To make an
-        asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.crypto_get_supported_exchanges_with_http_info(async_req=True)
-        >>> result = thread.get()
-
-        :param async_req bool
-        :return: SupportedExchanges
-                 If the method is called asynchronously,
-                 returns the request thread.
-        """
-
-        all_params = []  # noqa: E501
-        all_params.append('async_req')
-        all_params.append('_return_http_data_only')
-        all_params.append('_preload_content')
-        all_params.append('_request_timeout')
-
-        params = locals()
-        for key, val in six.iteritems(params['kwargs']):
-            if key not in all_params:
-                raise TypeError(
-                    "Got an unexpected keyword argument '%s'"
-                    " to method crypto_get_supported_exchanges" % key
-                )
-            params[key] = val
-        del params['kwargs']
-
-        collection_formats = {}
-
-        path_params = {}
-
-        query_params = []
-
-        header_params = {}
-
-        form_params = []
-        local_var_files = {}
-
-        body_params = None
-        # HTTP header `Accept`
-        header_params['Accept'] = self.api_client.select_header_accept(
-            ['application/json'])  # noqa: E501
-
-        # HTTP header `Content-Type`
-        header_params['Content-Type'] = self.api_client.select_header_content_type(  # noqa: E501
-            ['application/json'])  # noqa: E501
-
-        # Authentication setting
-        auth_settings = ['APIKeyHeader']  # noqa: E501
-
-        return self.api_client.call_api(
-            '/crypto/get_supported_exchanges', 'GET',
-            path_params,
-            query_params,
-            header_params,
-            body=body_params,
-            post_params=form_params,
-            files=local_var_files,
-            response_type='SupportedExchanges',  # noqa: E501
-            auth_settings=auth_settings,
-            async_req=params.get('async_req'),
-            _return_http_data_only=params.get('_return_http_data_only'),
-            _preload_content=params.get('_preload_content', True),
-            _request_timeout=params.get('_request_timeout'),
-            collection_formats=collection_formats)
-
-    def crypto_get_ticker(self, exchange, **kwargs):  # noqa: E501
+    def crypto_get_ticker(self, body, **kwargs):  # noqa: E501
         """Downloads candle format market data  # noqa: E501
 
         Returns a list of candle data from specified market and data range  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.crypto_get_ticker(exchange, async_req=True)
+        >>> thread = api.crypto_get_ticker(body, async_req=True)
         >>> result = thread.get()
 
         :param async_req bool
-        :param Exchange exchange: Get ticker data from specified crypto exchange (required)
+        :param Exchange body: Get ticker data from specified crypto exchange (required)
         :return: TickerResponse
                  If the method is called asynchronously,
                  returns the request thread.
         """
         kwargs['_return_http_data_only'] = True
         if kwargs.get('async_req'):
-            return self.crypto_get_ticker_with_http_info(exchange, **kwargs)  # noqa: E501
+            return self.crypto_get_ticker_with_http_info(body, **kwargs)  # noqa: E501
         else:
-            (data) = self.crypto_get_ticker_with_http_info(exchange, **kwargs)  # noqa: E501
+            (data) = self.crypto_get_ticker_with_http_info(body, **kwargs)  # noqa: E501
             return data
 
-    def crypto_get_ticker_with_http_info(self, exchange, **kwargs):  # noqa: E501
+    def crypto_get_ticker_with_http_info(self, body, **kwargs):  # noqa: E501
         """Downloads candle format market data  # noqa: E501
 
         Returns a list of candle data from specified market and data range  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.crypto_get_ticker_with_http_info(exchange, async_req=True)
+        >>> thread = api.crypto_get_ticker_with_http_info(body, async_req=True)
         >>> result = thread.get()
 
         :param async_req bool
-        :param Exchange exchange: Get ticker data from specified crypto exchange (required)
+        :param Exchange body: Get ticker data from specified crypto exchange (required)
         :return: TickerResponse
                  If the method is called asynchronously,
                  returns the request thread.
         """
 
-        all_params = ['exchange']  # noqa: E501
+        all_params = ['body']  # noqa: E501
         all_params.append('async_req')
         all_params.append('_return_http_data_only')
         all_params.append('_preload_content')
         all_params.append('_request_timeout')
 
         params = locals()
         for key, val in six.iteritems(params['kwargs']):
             if key not in all_params:
                 raise TypeError(
                     "Got an unexpected keyword argument '%s'"
                     " to method crypto_get_ticker" % key
                 )
             params[key] = val
         del params['kwargs']
-        # verify the required parameter 'exchange' is set
-        if ('exchange' not in params or
-                params['exchange'] is None):
-            raise ValueError("Missing the required parameter `exchange` when calling `crypto_get_ticker`")  # noqa: E501
+        # verify the required parameter 'body' is set
+        if ('body' not in params or
+                params['body'] is None):
+            raise ValueError("Missing the required parameter `body` when calling `crypto_get_ticker`")  # noqa: E501
 
         collection_formats = {}
 
         path_params = {}
 
         query_params = []
 
         header_params = {}
 
         form_params = []
         local_var_files = {}
 
         body_params = None
-        if 'exchange' in params:
-            body_params = params['exchange']
+        if 'body' in params:
+            body_params = params['body']
         # HTTP header `Accept`
         header_params['Accept'] = self.api_client.select_header_accept(
             ['application/json'])  # noqa: E501
 
         # HTTP header `Content-Type`
         header_params['Content-Type'] = self.api_client.select_header_content_type(  # noqa: E501
             ['application/json'])  # noqa: E501
```

### Comparing `brainrex-1.0.1/brainrex/api/language_api.py` & `brainrex-1.0.3/brainrex/api/language_api.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,20 +1,19 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import re  # noqa: F401
 
 # python 2 and python 3 compatibility library
 import six
 
@@ -29,90 +28,86 @@
     """
 
     def __init__(self, api_client=None):
         if api_client is None:
             api_client = ApiClient()
         self.api_client = api_client
 
-    def language_get_crypto_entities(self, text, **kwargs):  # noqa: E501
-        """Named Entity Recognition software capable of understanding cryptocurrency and blockchain speficic language.  # noqa: E501
+    def language_get_crypto_entities(self, body, **kwargs):  # noqa: E501
+        """Extracts known crypto entities like coin names, exchanges, media from text.  # noqa: E501
 
-        This endpoint ingest text and output known entities   # noqa: E501
+        The Crypto Entities endpoint ingests written MIT Digital Currency Initiative Paper A paper describing how our sentiment and entity analyzer are built. And how the can be used for trading several cryptocurrencies successfully  We prove that using sentiment only as a input to a trading algorithm can be profitable. If combined with other machine learning models. This Paper could be published in MIT Crypto Economics Journal. <br><br> Our AI selects from several models, choosing the one that fits the given data best, and we give you the avality to customize the sensitivy of the model. Our model has been trained to recognize anomalies in popular blockchain networks e.g. Bitcoin, Ethereum, learning from past events.  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.language_get_crypto_entities(text, async_req=True)
+        >>> thread = api.language_get_crypto_entities(body, async_req=True)
         >>> result = thread.get()
 
         :param async_req bool
-        :param Text text: String of text to be analyze for investor sentiment. (required)
+        :param Text body: String of text to be analyze for investor sentiment. (required)
         :return: None
                  If the method is called asynchronously,
                  returns the request thread.
         """
         kwargs['_return_http_data_only'] = True
         if kwargs.get('async_req'):
-            return self.language_get_crypto_entities_with_http_info(text, **kwargs)  # noqa: E501
+            return self.language_get_crypto_entities_with_http_info(body, **kwargs)  # noqa: E501
         else:
-            (data) = self.language_get_crypto_entities_with_http_info(text, **kwargs)  # noqa: E501
+            (data) = self.language_get_crypto_entities_with_http_info(body, **kwargs)  # noqa: E501
             return data
 
-    def language_get_crypto_entities_with_http_info(self, text, **kwargs):  # noqa: E501
-        """Named Entity Recognition software capable of understanding cryptocurrency and blockchain speficic language.  # noqa: E501
+    def language_get_crypto_entities_with_http_info(self, body, **kwargs):  # noqa: E501
+        """Extracts known crypto entities like coin names, exchanges, media from text.  # noqa: E501
 
-        This endpoint ingest text and output known entities   # noqa: E501
+        The Crypto Entities endpoint ingests written MIT Digital Currency Initiative Paper A paper describing how our sentiment and entity analyzer are built. And how the can be used for trading several cryptocurrencies successfully  We prove that using sentiment only as a input to a trading algorithm can be profitable. If combined with other machine learning models. This Paper could be published in MIT Crypto Economics Journal. <br><br> Our AI selects from several models, choosing the one that fits the given data best, and we give you the avality to customize the sensitivy of the model. Our model has been trained to recognize anomalies in popular blockchain networks e.g. Bitcoin, Ethereum, learning from past events.  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.language_get_crypto_entities_with_http_info(text, async_req=True)
+        >>> thread = api.language_get_crypto_entities_with_http_info(body, async_req=True)
         >>> result = thread.get()
 
         :param async_req bool
-        :param Text text: String of text to be analyze for investor sentiment. (required)
+        :param Text body: String of text to be analyze for investor sentiment. (required)
         :return: None
                  If the method is called asynchronously,
                  returns the request thread.
         """
 
-        all_params = ['text']  # noqa: E501
+        all_params = ['body']  # noqa: E501
         all_params.append('async_req')
         all_params.append('_return_http_data_only')
         all_params.append('_preload_content')
         all_params.append('_request_timeout')
 
         params = locals()
         for key, val in six.iteritems(params['kwargs']):
             if key not in all_params:
                 raise TypeError(
                     "Got an unexpected keyword argument '%s'"
                     " to method language_get_crypto_entities" % key
                 )
             params[key] = val
         del params['kwargs']
-        # verify the required parameter 'text' is set
-        if ('text' not in params or
-                params['text'] is None):
-            raise ValueError("Missing the required parameter `text` when calling `language_get_crypto_entities`")  # noqa: E501
+        # verify the required parameter 'body' is set
+        if ('body' not in params or
+                params['body'] is None):
+            raise ValueError("Missing the required parameter `body` when calling `language_get_crypto_entities`")  # noqa: E501
 
         collection_formats = {}
 
         path_params = {}
 
         query_params = []
 
         header_params = {}
 
         form_params = []
         local_var_files = {}
 
         body_params = None
-        if 'text' in params:
-            body_params = params['text']
-        # HTTP header `Accept`
-        header_params['Accept'] = self.api_client.select_header_accept(
-            ['application/json'])  # noqa: E501
-
+        if 'body' in params:
+            body_params = params['body']
         # HTTP header `Content-Type`
         header_params['Content-Type'] = self.api_client.select_header_content_type(  # noqa: E501
             ['application/json'])  # noqa: E501
 
         # Authentication setting
         auth_settings = ['APIKeyHeader']  # noqa: E501
 
@@ -128,86 +123,86 @@
             auth_settings=auth_settings,
             async_req=params.get('async_req'),
             _return_http_data_only=params.get('_return_http_data_only'),
             _preload_content=params.get('_preload_content', True),
             _request_timeout=params.get('_request_timeout'),
             collection_formats=collection_formats)
 
-    def language_get_general_sentiment(self, text, **kwargs):  # noqa: E501
-        """This endpoints returns a score from -1 to +1 where depending on negative or positive attitude in the text.  # noqa: E501
+    def language_get_general_sentiment(self, body, **kwargs):  # noqa: E501
+        """Returns a -1 to 1 score, depending on positive/negative sentiment  # noqa: E501
 
-        Returns a -1 to 1 score, depending on positive/negative sentiment  # noqa: E501
+        This endpoints returns a score from -1 to +1 where depending on negative or positive attitude in the text.  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.language_get_general_sentiment(text, async_req=True)
+        >>> thread = api.language_get_general_sentiment(body, async_req=True)
         >>> result = thread.get()
 
         :param async_req bool
-        :param Text text: String of text to be analyze for general sentiment. (required)
+        :param Text body: String of text to be analyze for general sentiment. (required)
         :return: str
                  If the method is called asynchronously,
                  returns the request thread.
         """
         kwargs['_return_http_data_only'] = True
         if kwargs.get('async_req'):
-            return self.language_get_general_sentiment_with_http_info(text, **kwargs)  # noqa: E501
+            return self.language_get_general_sentiment_with_http_info(body, **kwargs)  # noqa: E501
         else:
-            (data) = self.language_get_general_sentiment_with_http_info(text, **kwargs)  # noqa: E501
+            (data) = self.language_get_general_sentiment_with_http_info(body, **kwargs)  # noqa: E501
             return data
 
-    def language_get_general_sentiment_with_http_info(self, text, **kwargs):  # noqa: E501
-        """This endpoints returns a score from -1 to +1 where depending on negative or positive attitude in the text.  # noqa: E501
+    def language_get_general_sentiment_with_http_info(self, body, **kwargs):  # noqa: E501
+        """Returns a -1 to 1 score, depending on positive/negative sentiment  # noqa: E501
 
-        Returns a -1 to 1 score, depending on positive/negative sentiment  # noqa: E501
+        This endpoints returns a score from -1 to +1 where depending on negative or positive attitude in the text.  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.language_get_general_sentiment_with_http_info(text, async_req=True)
+        >>> thread = api.language_get_general_sentiment_with_http_info(body, async_req=True)
         >>> result = thread.get()
 
         :param async_req bool
-        :param Text text: String of text to be analyze for general sentiment. (required)
+        :param Text body: String of text to be analyze for general sentiment. (required)
         :return: str
                  If the method is called asynchronously,
                  returns the request thread.
         """
 
-        all_params = ['text']  # noqa: E501
+        all_params = ['body']  # noqa: E501
         all_params.append('async_req')
         all_params.append('_return_http_data_only')
         all_params.append('_preload_content')
         all_params.append('_request_timeout')
 
         params = locals()
         for key, val in six.iteritems(params['kwargs']):
             if key not in all_params:
                 raise TypeError(
                     "Got an unexpected keyword argument '%s'"
                     " to method language_get_general_sentiment" % key
                 )
             params[key] = val
         del params['kwargs']
-        # verify the required parameter 'text' is set
-        if ('text' not in params or
-                params['text'] is None):
-            raise ValueError("Missing the required parameter `text` when calling `language_get_general_sentiment`")  # noqa: E501
+        # verify the required parameter 'body' is set
+        if ('body' not in params or
+                params['body'] is None):
+            raise ValueError("Missing the required parameter `body` when calling `language_get_general_sentiment`")  # noqa: E501
 
         collection_formats = {}
 
         path_params = {}
 
         query_params = []
 
         header_params = {}
 
         form_params = []
         local_var_files = {}
 
         body_params = None
-        if 'text' in params:
-            body_params = params['text']
+        if 'body' in params:
+            body_params = params['body']
         # HTTP header `Accept`
         header_params['Accept'] = self.api_client.select_header_accept(
             ['application/json'])  # noqa: E501
 
         # HTTP header `Content-Type`
         header_params['Content-Type'] = self.api_client.select_header_content_type(  # noqa: E501
             ['application/json'])  # noqa: E501
@@ -227,86 +222,86 @@
             auth_settings=auth_settings,
             async_req=params.get('async_req'),
             _return_http_data_only=params.get('_return_http_data_only'),
             _preload_content=params.get('_preload_content', True),
             _request_timeout=params.get('_request_timeout'),
             collection_formats=collection_formats)
 
-    def language_get_price_sentiment(self, text, **kwargs):  # noqa: E501
+    def language_get_price_sentiment(self, body, **kwargs):  # noqa: E501
         """Sentiment analysis score using a model trained for buy signals.  # noqa: E501
 
         Gives a 0 to 1 score, depending on buy/sell sentiment  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.language_get_price_sentiment(text, async_req=True)
+        >>> thread = api.language_get_price_sentiment(body, async_req=True)
         >>> result = thread.get()
 
         :param async_req bool
-        :param Text text: String of text to be analyze for investor sentiment. (required)
+        :param Text body: String of text to be analyze for investor sentiment. (required)
         :return: str
                  If the method is called asynchronously,
                  returns the request thread.
         """
         kwargs['_return_http_data_only'] = True
         if kwargs.get('async_req'):
-            return self.language_get_price_sentiment_with_http_info(text, **kwargs)  # noqa: E501
+            return self.language_get_price_sentiment_with_http_info(body, **kwargs)  # noqa: E501
         else:
-            (data) = self.language_get_price_sentiment_with_http_info(text, **kwargs)  # noqa: E501
+            (data) = self.language_get_price_sentiment_with_http_info(body, **kwargs)  # noqa: E501
             return data
 
-    def language_get_price_sentiment_with_http_info(self, text, **kwargs):  # noqa: E501
+    def language_get_price_sentiment_with_http_info(self, body, **kwargs):  # noqa: E501
         """Sentiment analysis score using a model trained for buy signals.  # noqa: E501
 
         Gives a 0 to 1 score, depending on buy/sell sentiment  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
-        >>> thread = api.language_get_price_sentiment_with_http_info(text, async_req=True)
+        >>> thread = api.language_get_price_sentiment_with_http_info(body, async_req=True)
         >>> result = thread.get()
 
         :param async_req bool
-        :param Text text: String of text to be analyze for investor sentiment. (required)
+        :param Text body: String of text to be analyze for investor sentiment. (required)
         :return: str
                  If the method is called asynchronously,
                  returns the request thread.
         """
 
-        all_params = ['text']  # noqa: E501
+        all_params = ['body']  # noqa: E501
         all_params.append('async_req')
         all_params.append('_return_http_data_only')
         all_params.append('_preload_content')
         all_params.append('_request_timeout')
 
         params = locals()
         for key, val in six.iteritems(params['kwargs']):
             if key not in all_params:
                 raise TypeError(
                     "Got an unexpected keyword argument '%s'"
                     " to method language_get_price_sentiment" % key
                 )
             params[key] = val
         del params['kwargs']
-        # verify the required parameter 'text' is set
-        if ('text' not in params or
-                params['text'] is None):
-            raise ValueError("Missing the required parameter `text` when calling `language_get_price_sentiment`")  # noqa: E501
+        # verify the required parameter 'body' is set
+        if ('body' not in params or
+                params['body'] is None):
+            raise ValueError("Missing the required parameter `body` when calling `language_get_price_sentiment`")  # noqa: E501
 
         collection_formats = {}
 
         path_params = {}
 
         query_params = []
 
         header_params = {}
 
         form_params = []
         local_var_files = {}
 
         body_params = None
-        if 'text' in params:
-            body_params = params['text']
+        if 'body' in params:
+            body_params = params['body']
         # HTTP header `Accept`
         header_params['Accept'] = self.api_client.select_header_accept(
             ['application/json'])  # noqa: E501
 
         # HTTP header `Content-Type`
         header_params['Content-Type'] = self.api_client.select_header_content_type(  # noqa: E501
             ['application/json'])  # noqa: E501
```

### Comparing `brainrex-1.0.1/brainrex/__init__.py` & `brainrex-1.0.3/brainrex/__init__.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,43 +1,39 @@
 # coding: utf-8
 
 # flake8: noqa
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 # import apis into sdk package
 from brainrex.api.anomaly_api import AnomalyApi
 from brainrex.api.integrations_api import IntegrationsApi
 from brainrex.api.language_api import LanguageApi
-
 # import ApiClient
 from brainrex.api_client import ApiClient
 from brainrex.configuration import Configuration
 # import models into sdk package
 from brainrex.models.candle_request import CandleRequest
 from brainrex.models.candle_response import CandleResponse
 from brainrex.models.error import Error
 from brainrex.models.exchange import Exchange
 from brainrex.models.exchange_assets_response import ExchangeAssetsResponse
 from brainrex.models.exchange_assets_response_inner import ExchangeAssetsResponseInner
 from brainrex.models.ohclv import OHCLV
 from brainrex.models.orderbook_request import OrderbookRequest
 from brainrex.models.orderbook_response import OrderbookResponse
 from brainrex.models.point_time_series import PointTimeSeries
-from brainrex.models.series_response import SeriesResponse
-from brainrex.models.series_response_point import SeriesResponsePoint
 from brainrex.models.supported_exchanges import SupportedExchanges
 from brainrex.models.text import Text
 from brainrex.models.ticker_response import TickerResponse
 from brainrex.models.ticker_response_inner import TickerResponseInner
 from brainrex.models.time_series import TimeSeries
```

### Comparing `brainrex-1.0.1/brainrex/api_client.py` & `brainrex-1.0.3/brainrex/api_client.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,18 +1,17 @@
 # coding: utf-8
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
-
 from __future__ import absolute_import
 
 import datetime
 import json
 import mimetypes
 from multiprocessing.pool import ThreadPool
 import os
@@ -62,34 +61,26 @@
 
     def __init__(self, configuration=None, header_name=None, header_value=None,
                  cookie=None):
         if configuration is None:
             configuration = Configuration()
         self.configuration = configuration
 
-        # Use the pool property to lazily initialize the ThreadPool.
-        self._pool = None
+        self.pool = ThreadPool()
         self.rest_client = rest.RESTClientObject(configuration)
         self.default_headers = {}
         if header_name is not None:
             self.default_headers[header_name] = header_value
         self.cookie = cookie
         # Set default User-Agent.
-        self.user_agent = 'Swagger-Codegen/0.9.4/python'
+        self.user_agent = 'Swagger-Codegen/1.0.3/python'
 
     def __del__(self):
-        if self._pool is not None:
-            self._pool.close()
-            self._pool.join()
-
-    @property
-    def pool(self):
-        if self._pool is None:
-            self._pool = ThreadPool()
-        return self._pool
+        self.pool.close()
+        self.pool.join()
 
     @property
     def user_agent(self):
         """User agent for this API client"""
         return self.default_headers['User-Agent']
 
     @user_agent.setter
@@ -528,18 +519,22 @@
         os.remove(path)
 
         content_disposition = response.getheader("Content-Disposition")
         if content_disposition:
             filename = re.search(r'filename=[\'"]?([^\'"\s]+)[\'"]?',
                                  content_disposition).group(1)
             path = os.path.join(os.path.dirname(path), filename)
-
-        with open(path, "wb") as f:
-            f.write(response.data)
-
+            response_data = response.data
+            with open(path, "wb") as f:
+                if isinstance(response_data, str):
+                    # change str to bytes so we can write it
+                    response_data = response_data.encode('utf-8')
+                    f.write(response_data)
+                else:
+                    f.write(response_data)
         return path
 
     def __deserialize_primitive(self, data, klass):
         """Deserializes string to primitive type.
 
         :param data: str.
         :param klass: class literal.
@@ -596,26 +591,25 @@
                 reason=(
                     "Failed to parse `{0}` as datetime object"
                     .format(string)
                 )
             )
 
     def __hasattr(self, object, name):
-        return name in object.__class__.__dict__
+            return name in object.__class__.__dict__
 
     def __deserialize_model(self, data, klass):
         """Deserializes list or dict to model.
 
         :param data: dict, list.
         :param klass: class literal.
         :return: model object.
         """
 
-        if (not klass.swagger_types and
-                not self.__hasattr(klass, 'get_real_child_model')):
+        if not klass.swagger_types and not self.__hasattr(klass, 'get_real_child_model'):
             return data
 
         kwargs = {}
         if klass.swagger_types is not None:
             for attr, attr_type in six.iteritems(klass.swagger_types):
                 if (data is not None and
                         klass.attribute_map[attr] in data and
```

### Comparing `brainrex-1.0.1/brainrex/models/error.py` & `brainrex-1.0.3/brainrex/models/error.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,32 +1,29 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
 class Error(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
@@ -40,20 +37,18 @@
         'code': 'code',
         'message': 'message',
         'fields': 'fields'
     }
 
     def __init__(self, code=None, message=None, fields=None):  # noqa: E501
         """Error - a model defined in Swagger"""  # noqa: E501
-
         self._code = None
         self._message = None
         self._fields = None
         self.discriminator = None
-
         if code is not None:
             self.code = code
         if message is not None:
             self.message = message
         if fields is not None:
             self.fields = fields
```

### Comparing `brainrex-1.0.1/brainrex/models/exchange_assets_response.py` & `brainrex-1.0.3/brainrex/models/exchange_assets_response.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,32 +1,29 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
 class ExchangeAssetsResponse(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
```

### Comparing `brainrex-1.0.1/brainrex/models/ticker_response.py` & `brainrex-1.0.3/brainrex/models/ticker_response.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,32 +1,29 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
 class TickerResponse(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
```

### Comparing `brainrex-1.0.1/brainrex/models/supported_exchanges.py` & `brainrex-1.0.3/brainrex/models/supported_exchanges.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,32 +1,29 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
 class SupportedExchanges(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
@@ -40,20 +37,18 @@
         'best_case_fee': 'bestCaseFee',
         'worst_case_fee': 'worstCaseFee',
         'exchange': 'exchange'
     }
 
     def __init__(self, best_case_fee=None, worst_case_fee=None, exchange=None):  # noqa: E501
         """SupportedExchanges - a model defined in Swagger"""  # noqa: E501
-
         self._best_case_fee = None
         self._worst_case_fee = None
         self._exchange = None
         self.discriminator = None
-
         if best_case_fee is not None:
             self.best_case_fee = best_case_fee
         if worst_case_fee is not None:
             self.worst_case_fee = worst_case_fee
         if exchange is not None:
             self.exchange = exchange
```

### Comparing `brainrex-1.0.1/brainrex/models/__init__.py` & `brainrex-1.0.3/brainrex/models/__init__.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,34 +1,31 @@
 # coding: utf-8
 
 # flake8: noqa
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 # import models into model package
 from brainrex.models.candle_request import CandleRequest
 from brainrex.models.candle_response import CandleResponse
 from brainrex.models.error import Error
 from brainrex.models.exchange import Exchange
 from brainrex.models.exchange_assets_response import ExchangeAssetsResponse
 from brainrex.models.exchange_assets_response_inner import ExchangeAssetsResponseInner
 from brainrex.models.ohclv import OHCLV
 from brainrex.models.orderbook_request import OrderbookRequest
 from brainrex.models.orderbook_response import OrderbookResponse
 from brainrex.models.point_time_series import PointTimeSeries
-from brainrex.models.series_response import SeriesResponse
-from brainrex.models.series_response_point import SeriesResponsePoint
 from brainrex.models.supported_exchanges import SupportedExchanges
 from brainrex.models.text import Text
 from brainrex.models.ticker_response import TickerResponse
 from brainrex.models.ticker_response_inner import TickerResponseInner
 from brainrex.models.time_series import TimeSeries
```

### Comparing `brainrex-1.0.1/brainrex/models/candle_response.py` & `brainrex-1.0.3/brainrex/models/candle_response.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,32 +1,29 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
 class CandleResponse(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
```

### Comparing `brainrex-1.0.1/brainrex/models/exchange_assets_response_inner.py` & `brainrex-1.0.3/brainrex/models/exchange_assets_response_inner.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,32 +1,29 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
 class ExchangeAssetsResponseInner(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
@@ -42,21 +39,19 @@
         'id': 'id',
         'tradin_sym': 'tradinSym',
         'symbol': 'symbol'
     }
 
     def __init__(self, name=None, id=None, tradin_sym=None, symbol=None):  # noqa: E501
         """ExchangeAssetsResponseInner - a model defined in Swagger"""  # noqa: E501
-
         self._name = None
         self._id = None
         self._tradin_sym = None
         self._symbol = None
         self.discriminator = None
-
         if name is not None:
             self.name = name
         if id is not None:
             self.id = id
         if tradin_sym is not None:
             self.tradin_sym = tradin_sym
         if symbol is not None:
```

### Comparing `brainrex-1.0.1/brainrex/models/ticker_response_inner.py` & `brainrex-1.0.3/brainrex/models/ticker_response_inner.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,32 +1,29 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
 class TickerResponseInner(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
@@ -46,23 +43,21 @@
         'price_btc': 'priceBtc',
         'price_usd': 'priceUsd',
         'symbol': 'symbol'
     }
 
     def __init__(self, last_updated=None, name=None, percent_change24h_usd=None, price_btc=None, price_usd=None, symbol=None):  # noqa: E501
         """TickerResponseInner - a model defined in Swagger"""  # noqa: E501
-
         self._last_updated = None
         self._name = None
         self._percent_change24h_usd = None
         self._price_btc = None
         self._price_usd = None
         self._symbol = None
         self.discriminator = None
-
         if last_updated is not None:
             self.last_updated = last_updated
         if name is not None:
             self.name = name
         if percent_change24h_usd is not None:
             self.percent_change24h_usd = percent_change24h_usd
         if price_btc is not None:
```

### Comparing `brainrex-1.0.1/brainrex/models/orderbook_request.py` & `brainrex-1.0.3/brainrex/models/orderbook_request.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,32 +1,29 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
 class OrderbookRequest(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
@@ -42,21 +39,19 @@
         'exchange': 'exchange',
         'limit': 'limit',
         'quote_trading_symbol': 'quote_trading_symbol'
     }
 
     def __init__(self, base_trading_symbol=None, exchange=None, limit=None, quote_trading_symbol=None):  # noqa: E501
         """OrderbookRequest - a model defined in Swagger"""  # noqa: E501
-
         self._base_trading_symbol = None
         self._exchange = None
         self._limit = None
         self._quote_trading_symbol = None
         self.discriminator = None
-
         if base_trading_symbol is not None:
             self.base_trading_symbol = base_trading_symbol
         if exchange is not None:
             self.exchange = exchange
         if limit is not None:
             self.limit = limit
         if quote_trading_symbol is not None:
```

### Comparing `brainrex-1.0.1/brainrex/models/series_response.py` & `brainrex-1.0.3/brainrex/models/time_series.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,47 +1,44 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
-class SeriesResponse(object):
+class TimeSeries(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
     swagger_types = {
     }
 
     attribute_map = {
     }
 
     def __init__(self):  # noqa: E501
-        """SeriesResponse - a model defined in Swagger"""  # noqa: E501
+        """TimeSeries - a model defined in Swagger"""  # noqa: E501
         self.discriminator = None
 
     def to_dict(self):
         """Returns the model properties as a dict"""
         result = {}
 
         for attr, _ in six.iteritems(self.swagger_types):
@@ -57,15 +54,15 @@
                 result[attr] = dict(map(
                     lambda item: (item[0], item[1].to_dict())
                     if hasattr(item[1], "to_dict") else item,
                     value.items()
                 ))
             else:
                 result[attr] = value
-        if issubclass(SeriesResponse, dict):
+        if issubclass(TimeSeries, dict):
             for key, value in self.items():
                 result[key] = value
 
         return result
 
     def to_str(self):
         """Returns the string representation of the model"""
@@ -73,15 +70,15 @@
 
     def __repr__(self):
         """For `print` and `pprint`"""
         return self.to_str()
 
     def __eq__(self, other):
         """Returns true if both objects are equal"""
-        if not isinstance(other, SeriesResponse):
+        if not isinstance(other, TimeSeries):
             return False
 
         return self.__dict__ == other.__dict__
 
     def __ne__(self, other):
         """Returns true if both objects are not equal"""
         return not self == other
```

### Comparing `brainrex-1.0.1/brainrex/models/candle_request.py` & `brainrex-1.0.3/brainrex/models/candle_request.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,32 +1,29 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
 class CandleRequest(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
@@ -42,21 +39,19 @@
         'exchange': 'exchange',
         'interval': 'interval',
         'quote_trading_symbol': 'quote_trading_symbol'
     }
 
     def __init__(self, base_trading_symbol=None, exchange=None, interval=None, quote_trading_symbol=None):  # noqa: E501
         """CandleRequest - a model defined in Swagger"""  # noqa: E501
-
         self._base_trading_symbol = None
         self._exchange = None
         self._interval = None
         self._quote_trading_symbol = None
         self.discriminator = None
-
         if base_trading_symbol is not None:
             self.base_trading_symbol = base_trading_symbol
         if exchange is not None:
             self.exchange = exchange
         if interval is not None:
             self.interval = interval
         if quote_trading_symbol is not None:
```

### Comparing `brainrex-1.0.1/brainrex/models/orderbook_response.py` & `brainrex-1.0.3/brainrex/models/orderbook_response.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,32 +1,29 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
 class OrderbookResponse(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
@@ -42,21 +39,19 @@
         'exchange': 'exchange',
         'limit': 'limit',
         'quote_trading_symbol': 'quote_trading_symbol'
     }
 
     def __init__(self, base_trading_symbol=None, exchange=None, limit=None, quote_trading_symbol=None):  # noqa: E501
         """OrderbookResponse - a model defined in Swagger"""  # noqa: E501
-
         self._base_trading_symbol = None
         self._exchange = None
         self._limit = None
         self._quote_trading_symbol = None
         self.discriminator = None
-
         if base_trading_symbol is not None:
             self.base_trading_symbol = base_trading_symbol
         if exchange is not None:
             self.exchange = exchange
         if limit is not None:
             self.limit = limit
         if quote_trading_symbol is not None:
```

### Comparing `brainrex-1.0.1/brainrex/models/ohclv.py` & `brainrex-1.0.3/brainrex/models/ohclv.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,32 +1,29 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
 class OHCLV(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
@@ -52,26 +49,24 @@
         'usd_volume': 'usdVolume',
         'btc_volume': 'btcVolume',
         'quote_volume': 'quoteVolume'
     }
 
     def __init__(self, close=None, high=None, end_date=None, open=None, time=None, volume=None, usd_volume=None, btc_volume=None, quote_volume=None):  # noqa: E501
         """OHCLV - a model defined in Swagger"""  # noqa: E501
-
         self._close = None
         self._high = None
         self._end_date = None
         self._open = None
         self._time = None
         self._volume = None
         self._usd_volume = None
         self._btc_volume = None
         self._quote_volume = None
         self.discriminator = None
-
         if close is not None:
             self.close = close
         if high is not None:
             self.high = high
         if end_date is not None:
             self.end_date = end_date
         if open is not None:
```

### Comparing `brainrex-1.0.1/brainrex/models/point_time_series.py` & `brainrex-1.0.3/brainrex/models/point_time_series.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,32 +1,29 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
 class PointTimeSeries(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
@@ -38,19 +35,17 @@
     attribute_map = {
         'timestamp': 'timestamp',
         'value': 'value'
     }
 
     def __init__(self, timestamp=None, value=None):  # noqa: E501
         """PointTimeSeries - a model defined in Swagger"""  # noqa: E501
-
         self._timestamp = None
         self._value = None
         self.discriminator = None
-
         if timestamp is not None:
             self.timestamp = timestamp
         if value is not None:
             self.value = value
 
     @property
     def timestamp(self):
```

### Comparing `brainrex-1.0.1/brainrex/models/text.py` & `brainrex-1.0.3/brainrex/models/text.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,32 +1,29 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
 class Text(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
@@ -36,18 +33,16 @@
 
     attribute_map = {
         'text': 'text'
     }
 
     def __init__(self, text=None):  # noqa: E501
         """Text - a model defined in Swagger"""  # noqa: E501
-
         self._text = None
         self.discriminator = None
-
         if text is not None:
             self.text = text
 
     @property
     def text(self):
         """Gets the text of this Text.  # noqa: E501
```

### Comparing `brainrex-1.0.1/brainrex/models/exchange.py` & `brainrex-1.0.3/brainrex/models/exchange.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,32 +1,29 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 import pprint
 import re  # noqa: F401
 
 import six
 
-
 class Exchange(object):
     """NOTE: This class is auto generated by the swagger code generator program.
 
     Do not edit the class manually.
     """
-
     """
     Attributes:
       swagger_types (dict): The key is attribute name
                             and the value is attribute type.
       attribute_map (dict): The key is attribute name
                             and the value is json key in definition.
     """
@@ -36,18 +33,16 @@
 
     attribute_map = {
         'exchange': 'exchange'
     }
 
     def __init__(self, exchange=None):  # noqa: E501
         """Exchange - a model defined in Swagger"""  # noqa: E501
-
         self._exchange = None
         self.discriminator = None
-
         if exchange is not None:
             self.exchange = exchange
 
     @property
     def exchange(self):
         """Gets the exchange of this Exchange.  # noqa: E501
```

### Comparing `brainrex-1.0.1/brainrex/rest.py` & `brainrex-1.0.3/brainrex/rest.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,20 +1,19 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from __future__ import absolute_import
 
 import io
 import json
 import logging
 import re
 import ssl
@@ -152,15 +151,15 @@
 
         try:
             # For `POST`, `PUT`, `PATCH`, `OPTIONS`, `DELETE`
             if method in ['POST', 'PUT', 'PATCH', 'OPTIONS', 'DELETE']:
                 if query_params:
                     url += '?' + urlencode(query_params)
                 if re.search('json', headers['Content-Type'], re.IGNORECASE):
-                    request_body = None
+                    request_body = '{}'
                     if body is not None:
                         request_body = json.dumps(body)
                     r = self.pool_manager.request(
                         method, url,
                         body=request_body,
                         preload_content=_preload_content,
                         timeout=timeout,
@@ -212,19 +211,14 @@
         except urllib3.exceptions.SSLError as e:
             msg = "{0}\n{1}".format(type(e).__name__, str(e))
             raise ApiException(status=0, reason=msg)
 
         if _preload_content:
             r = RESTResponse(r)
 
-            # In the python 3, the response.data is bytes.
-            # we need to decode it to string.
-            if six.PY3:
-                r.data = r.data.decode('utf8')
-
             # log response body
             logger.debug("response body: %s", r.data)
 
         if not 200 <= r.status <= 299:
             raise ApiException(http_resp=r)
 
         return r
```

### Comparing `brainrex-1.0.1/README.md` & `brainrex-1.0.3/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 # brainrex
-Provides anomaly detection and natural language processing technlogies to blockchain developers.
+The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.
 
 This Python package is automatically generated by the [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) project:
 
-- API version: 1.0.1
-- Package version: 0.9.4
-- Build package: io.swagger.codegen.languages.PythonClientCodegen
+- API version: 1.0.3-oas3
+- Package version: 1.0.3
+- Build package: io.swagger.codegen.v3.generators.python.PythonClientCodegen
 
 ## Requirements.
 
 Python 2.7 and 3.4+
 
 ## Installation & Usage
 ### pip install
 
 If the python package is hosted on Github, you can install directly from Github
 
 ```sh
-pip install git+https://github.com//.git
+pip install git+https://github.com/brainrexAI/brainrex-python.git
 ```
-(you may need to run `pip` with root permission: `sudo pip install git+https://github.com//.git`)
+(you may need to run `pip` with root permission: `sudo pip install git+https://github.com/brainrexAI/brainrex-python.git`)
 
 Then import the package:
 ```python
 import brainrex 
 ```
 
 ### Setuptools
@@ -55,70 +55,62 @@
 configuration = brainrex.Configuration()
 configuration.api_key['x-api-key'] = 'YOUR_API_KEY'
 # Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
 # configuration.api_key_prefix['x-api-key'] = 'Bearer'
 
 # create an instance of the API class
 api_instance = brainrex.AnomalyApi(brainrex.ApiClient(configuration))
-request = brainrex.TimeSeries() # TimeSeries | Time Series to be analyzed, with the following format. (optional)
+body = [brainrex.PointTimeSeries()] # list[PointTimeSeries] | Time Series to be analyzed, with the following format. (optional)
 
 try:
     # Detects anomalies in historical data in batches. This endpoint uses your entire dataset as input
-    api_response = api_instance.anomaly_batch(request=request)
+    api_response = api_instance.anomaly_batch(body=body)
     pprint(api_response)
 except ApiException as e:
     print("Exception when calling AnomalyApi->anomaly_batch: %s\n" % e)
-
 ```
 
 ## Documentation for API Endpoints
 
-All URIs are relative to *https://api.bitlongs.com*
+All URIs are relative to *https://api.brainrex.com*
 
 Class | Method | HTTP request | Description
 ------------ | ------------- | ------------- | -------------
 *AnomalyApi* | [**anomaly_batch**](docs/AnomalyApi.md#anomaly_batch) | **POST** /anomaly/json/detect | Detects anomalies in historical data in batches. This endpoint uses your entire dataset as input
 *IntegrationsApi* | [**crypto_get_candle_data**](docs/IntegrationsApi.md#crypto_get_candle_data) | **POST** /crypto/get_candles | Downloads candle format market data
-*IntegrationsApi* | [**crypto_get_exchange_assets**](docs/IntegrationsApi.md#crypto_get_exchange_assets) | **POST** /crypto/get_exchange_assets | Gets all currency pairs traded in selected exchange
-*IntegrationsApi* | [**crypto_get_orderbooks**](docs/IntegrationsApi.md#crypto_get_orderbooks) | **POST** /crypto/get_orderbooks | Downloads candle format market data
-*IntegrationsApi* | [**crypto_get_supported_exchanges**](docs/IntegrationsApi.md#crypto_get_supported_exchanges) | **GET** /crypto/get_supported_exchanges | Gets all cryptocurrency exchanges supported by the Brainrex API
+*IntegrationsApi* | [**crypto_get_exchange_assets**](docs/IntegrationsApi.md#crypto_get_exchange_assets) | **POST** /crypto/get_exchange_assets | Gets all coin pairs traded in specified exchange
 *IntegrationsApi* | [**crypto_get_ticker**](docs/IntegrationsApi.md#crypto_get_ticker) | **POST** /crypto/get_ticker | Downloads candle format market data
-*LanguageApi* | [**language_get_crypto_entities**](docs/LanguageApi.md#language_get_crypto_entities) | **POST** /entity/get_crypto_entities | Named Entity Recognition software capable of understanding cryptocurrency and blockchain speficic language.
-*LanguageApi* | [**language_get_general_sentiment**](docs/LanguageApi.md#language_get_general_sentiment) | **POST** /sentiment/get_general_sentiment | This endpoints returns a score from -1 to +1 where depending on negative or positive attitude in the text.
+*LanguageApi* | [**language_get_crypto_entities**](docs/LanguageApi.md#language_get_crypto_entities) | **POST** /entity/get_crypto_entities | Extracts known crypto entities like coin names, exchanges, media from text.
+*LanguageApi* | [**language_get_general_sentiment**](docs/LanguageApi.md#language_get_general_sentiment) | **POST** /sentiment/get_general_sentiment | Returns a -1 to 1 score, depending on positive/negative sentiment
 *LanguageApi* | [**language_get_price_sentiment**](docs/LanguageApi.md#language_get_price_sentiment) | **POST** /language/get_price_sentiment | Sentiment analysis score using a model trained for buy signals.
 
-
 ## Documentation For Models
 
  - [CandleRequest](docs/CandleRequest.md)
  - [CandleResponse](docs/CandleResponse.md)
  - [Error](docs/Error.md)
  - [Exchange](docs/Exchange.md)
  - [ExchangeAssetsResponse](docs/ExchangeAssetsResponse.md)
  - [ExchangeAssetsResponseInner](docs/ExchangeAssetsResponseInner.md)
  - [OHCLV](docs/OHCLV.md)
  - [OrderbookRequest](docs/OrderbookRequest.md)
  - [OrderbookResponse](docs/OrderbookResponse.md)
  - [PointTimeSeries](docs/PointTimeSeries.md)
- - [SeriesResponse](docs/SeriesResponse.md)
- - [SeriesResponsePoint](docs/SeriesResponsePoint.md)
  - [SupportedExchanges](docs/SupportedExchanges.md)
  - [Text](docs/Text.md)
  - [TickerResponse](docs/TickerResponse.md)
  - [TickerResponseInner](docs/TickerResponseInner.md)
  - [TimeSeries](docs/TimeSeries.md)
 
-
 ## Documentation For Authorization
 
 
 ## APIKeyHeader
 
 - **Type**: API key
 - **API key parameter name**: x-api-key
 - **Location**: HTTP header
 
 
 ## Author
 
 
-
```

### Comparing `brainrex-1.0.1/setup.py` & `brainrex-1.0.3/setup.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,48 +1,39 @@
 # coding: utf-8
 
 """
     Brainrex API
 
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
 
-    OpenAPI spec version: 1.0.1
+    OpenAPI spec version: 1.0.3-oas3
     
     Generated by: https://github.com/swagger-api/swagger-codegen.git
 """
 
-
 from setuptools import setup, find_packages  # noqa: H301
 
 NAME = "brainrex"
-VERSION = "1.0.1"
+VERSION = "1.0.3"
 # To install the library, run the following
 #
 # python setup.py install
 #
 # prerequisite: setuptools
 # http://pypi.python.org/pypi/setuptools
 
-REQUIRES = [
-    "certifi>=2017.4.17",
-    "python-dateutil>=2.1",
-    "six>=1.10",
-    "urllib3>=1.23"
-]
-    
+REQUIRES = ["urllib3 >= 1.15", "six >= 1.10", "certifi", "python-dateutil"]
 
 setup(
     name=NAME,
     version=VERSION,
-    description="Python Client for the Brainrex API.",
-    author_email="gonzalo@brainrex.com",
-    url="https://github.com/BrainrexAPI/brainrex-python",
-    license='MIT',        # Chose a license from here: https://help.github.com/articles/licensing-a-repository
-    download_url = 'https://github.com/BrainrexAPI/brainrex-python/archive/v1.0.1.tar.gz',    # I explain this later on
-    keywords=["Swagger", "Brainrex API", "anomaly detection crypto", "sentiment analysis", "blockchain"],
+    description="Brainrex API",
+    author_email="",
+    url="https://github.com/brainrexAI/brainrex-python",
+    keywords=["Swagger", "Brainrex API"],
     install_requires=REQUIRES,
     packages=find_packages(),
     include_package_data=True,
     long_description="""\
-    Provides anomaly detection and natural language processing technlogies to blockchain developers.  # noqa: E501
+    The Brainrex API is a collection of analytics tools and data integrations made for blockchain developers. In particular we offer Natural Language Processing and Anomaly detection algorithms that have been fine tune to understand text data and time series in the domain speficic setting of cryptocurrency and blockchain technology.  # noqa: E501
     """
 )
```


# Comparing `tmp/crypto-screening-1.3.1.tar.gz` & `tmp/crypto-screening-1.3.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "crypto-screening-1.3.1.tar", last modified: Wed Jun 28 11:02:51 2023, max compression
+gzip compressed data, was "crypto-screening-1.3.2.tar", last modified: Wed Jun 28 13:17:13 2023, max compression
```

## Comparing `crypto-screening-1.3.1.tar` & `crypto-screening-1.3.2.tar`

### file list

```diff
@@ -1,35 +1,35 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 11:02:51.489529 crypto-screening-1.3.1/
--rw-rw-rw-   0        0        0       98 2023-06-28 11:02:51.000000 crypto-screening-1.3.1/MANIFEST.in
--rw-rw-rw-   0        0        0     2085 2023-06-28 11:02:51.489529 crypto-screening-1.3.1/PKG-INFO
--rw-rw-rw-   0        0        0     1264 2023-06-23 16:52:27.000000 crypto-screening-1.3.1/README.md
--rw-rw-rw-   0        0        0    12920 2023-06-23 16:52:27.000000 crypto-screening-1.3.1/build.py
-drwxrwxrwx   0        0        0        0 2023-06-28 11:02:51.472420 crypto-screening-1.3.1/crypto_screening/
--rw-rw-rw-   0        0        0     6694 2023-06-23 16:52:27.000000 crypto-screening-1.3.1/crypto_screening/base.py
-drwxrwxrwx   0        0        0        0 2023-06-28 11:02:51.488527 crypto-screening-1.3.1/crypto_screening/collect/
--rw-rw-rw-   0        0        0    17713 2023-06-28 11:01:21.000000 crypto-screening-1.3.1/crypto_screening/collect/assets.py
--rw-rw-rw-   0        0        0      496 2023-06-27 10:17:11.000000 crypto-screening-1.3.1/crypto_screening/collect/document.py
--rw-rw-rw-   0        0        0     4056 2023-06-27 13:26:48.000000 crypto-screening-1.3.1/crypto_screening/collect/exchanges.py
--rw-rw-rw-   0        0        0     8360 2023-06-28 11:02:04.000000 crypto-screening-1.3.1/crypto_screening/collect/screeners.py
--rw-rw-rw-   0        0        0    19287 2023-06-28 10:54:03.000000 crypto-screening-1.3.1/crypto_screening/collect/symbols.py
--rw-rw-rw-   0        0        0    12447 2023-06-25 20:15:20.000000 crypto-screening-1.3.1/crypto_screening/dataset.py
--rw-rw-rw-   0        0        0      869 2023-06-27 10:20:56.000000 crypto-screening-1.3.1/crypto_screening/document.py
--rw-rw-rw-   0        0        0      258 2023-06-25 14:21:21.000000 crypto-screening-1.3.1/crypto_screening/exchanges.py
--rw-rw-rw-   0        0        0      180 2023-06-23 16:52:27.000000 crypto-screening-1.3.1/crypto_screening/hints.py
--rw-rw-rw-   0        0        0     2665 2023-06-23 16:52:27.000000 crypto-screening-1.3.1/crypto_screening/interval.py
--rw-rw-rw-   0        0        0    32972 2023-06-28 10:57:47.000000 crypto-screening-1.3.1/crypto_screening/ohlcv.py
--rw-rw-rw-   0        0        0    25246 2023-06-28 10:22:01.000000 crypto-screening-1.3.1/crypto_screening/orderbook.py
--rw-rw-rw-   0        0        0     2378 2023-06-27 10:23:45.000000 crypto-screening-1.3.1/crypto_screening/process.py
--rw-rw-rw-   0        0        0    32975 2023-06-28 09:52:38.000000 crypto-screening-1.3.1/crypto_screening/screener.py
--rw-rw-rw-   0        0        0     9894 2023-06-25 16:31:01.000000 crypto-screening-1.3.1/crypto_screening/symbols.py
--rw-rw-rw-   0        0        0     3845 2023-06-27 09:22:00.000000 crypto-screening-1.3.1/crypto_screening/validate.py
-drwxrwxrwx   0        0        0        0 2023-06-28 11:02:51.484575 crypto-screening-1.3.1/crypto_screening.egg-info/
--rw-rw-rw-   0        0        0     2085 2023-06-28 11:02:51.000000 crypto-screening-1.3.1/crypto_screening.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      812 2023-06-28 11:02:51.000000 crypto-screening-1.3.1/crypto_screening.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 11:02:51.000000 crypto-screening-1.3.1/crypto_screening.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       94 2023-06-28 11:02:51.000000 crypto-screening-1.3.1/crypto_screening.egg-info/requires.txt
--rw-rw-rw-   0        0        0       17 2023-06-28 11:02:51.000000 crypto-screening-1.3.1/crypto_screening.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      652 2023-06-28 11:02:51.000000 crypto-screening-1.3.1/pyproject.toml
--rw-rw-rw-   0        0        0       99 2023-06-28 09:56:21.000000 crypto-screening-1.3.1/requirements-dev.txt
--rw-rw-rw-   0        0        0       64 2023-06-23 16:55:08.000000 crypto-screening-1.3.1/requirements.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 11:02:51.490528 crypto-screening-1.3.1/setup.cfg
--rw-rw-rw-   0        0        0     1579 2023-06-28 10:59:09.000000 crypto-screening-1.3.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:17:13.181882 crypto-screening-1.3.2/
+-rw-rw-rw-   0        0        0       98 2023-06-28 13:17:12.000000 crypto-screening-1.3.2/MANIFEST.in
+-rw-rw-rw-   0        0        0     2085 2023-06-28 13:17:13.181882 crypto-screening-1.3.2/PKG-INFO
+-rw-rw-rw-   0        0        0     1264 2023-06-23 16:52:27.000000 crypto-screening-1.3.2/README.md
+-rw-rw-rw-   0        0        0    12920 2023-06-23 16:52:27.000000 crypto-screening-1.3.2/build.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:17:13.149153 crypto-screening-1.3.2/crypto_screening/
+-rw-rw-rw-   0        0        0     6694 2023-06-23 16:52:27.000000 crypto-screening-1.3.2/crypto_screening/base.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:17:13.180876 crypto-screening-1.3.2/crypto_screening/collect/
+-rw-rw-rw-   0        0        0    17713 2023-06-28 11:01:21.000000 crypto-screening-1.3.2/crypto_screening/collect/assets.py
+-rw-rw-rw-   0        0        0      496 2023-06-27 10:17:11.000000 crypto-screening-1.3.2/crypto_screening/collect/document.py
+-rw-rw-rw-   0        0        0     4056 2023-06-27 13:26:48.000000 crypto-screening-1.3.2/crypto_screening/collect/exchanges.py
+-rw-rw-rw-   0        0        0     9680 2023-06-28 12:47:21.000000 crypto-screening-1.3.2/crypto_screening/collect/screeners.py
+-rw-rw-rw-   0        0        0    19287 2023-06-28 10:54:03.000000 crypto-screening-1.3.2/crypto_screening/collect/symbols.py
+-rw-rw-rw-   0        0        0    12447 2023-06-25 20:15:20.000000 crypto-screening-1.3.2/crypto_screening/dataset.py
+-rw-rw-rw-   0        0        0      869 2023-06-27 10:20:56.000000 crypto-screening-1.3.2/crypto_screening/document.py
+-rw-rw-rw-   0        0        0      258 2023-06-25 14:21:21.000000 crypto-screening-1.3.2/crypto_screening/exchanges.py
+-rw-rw-rw-   0        0        0      180 2023-06-23 16:52:27.000000 crypto-screening-1.3.2/crypto_screening/hints.py
+-rw-rw-rw-   0        0        0     2665 2023-06-23 16:52:27.000000 crypto-screening-1.3.2/crypto_screening/interval.py
+-rw-rw-rw-   0        0        0    32972 2023-06-28 10:57:47.000000 crypto-screening-1.3.2/crypto_screening/ohlcv.py
+-rw-rw-rw-   0        0        0    25246 2023-06-28 10:22:01.000000 crypto-screening-1.3.2/crypto_screening/orderbook.py
+-rw-rw-rw-   0        0        0     2378 2023-06-27 10:23:45.000000 crypto-screening-1.3.2/crypto_screening/process.py
+-rw-rw-rw-   0        0        0    33304 2023-06-28 12:58:51.000000 crypto-screening-1.3.2/crypto_screening/screener.py
+-rw-rw-rw-   0        0        0     9894 2023-06-25 16:31:01.000000 crypto-screening-1.3.2/crypto_screening/symbols.py
+-rw-rw-rw-   0        0        0     3845 2023-06-27 09:22:00.000000 crypto-screening-1.3.2/crypto_screening/validate.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:17:13.161766 crypto-screening-1.3.2/crypto_screening.egg-info/
+-rw-rw-rw-   0        0        0     2085 2023-06-28 13:17:12.000000 crypto-screening-1.3.2/crypto_screening.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      812 2023-06-28 13:17:13.000000 crypto-screening-1.3.2/crypto_screening.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 13:17:12.000000 crypto-screening-1.3.2/crypto_screening.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       94 2023-06-28 13:17:12.000000 crypto-screening-1.3.2/crypto_screening.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       17 2023-06-28 13:17:12.000000 crypto-screening-1.3.2/crypto_screening.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      652 2023-06-28 13:17:12.000000 crypto-screening-1.3.2/pyproject.toml
+-rw-rw-rw-   0        0        0       99 2023-06-28 09:56:21.000000 crypto-screening-1.3.2/requirements-dev.txt
+-rw-rw-rw-   0        0        0       64 2023-06-23 16:55:08.000000 crypto-screening-1.3.2/requirements.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 13:17:13.181882 crypto-screening-1.3.2/setup.cfg
+-rw-rw-rw-   0        0        0     1579 2023-06-28 12:48:17.000000 crypto-screening-1.3.2/setup.py
```

### Comparing `crypto-screening-1.3.1/PKG-INFO` & `crypto-screening-1.3.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: crypto-screening
-Version: 1.3.1
+Version: 1.3.2
 Summary: A software for automatically recording real-time crypto exchanges and pairs OHLCV and Orderbook rates.
 Home-page: https://github.com/Shahaf-F-S/crypto-screening
 Author: Shahaf Frank-Shapir
 Author-email: shahaffrs@gmail.com
 License: MIT
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `crypto-screening-1.3.1/README.md` & `crypto-screening-1.3.2/README.md`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/build.py` & `crypto-screening-1.3.2/build.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/crypto_screening/base.py` & `crypto-screening-1.3.2/crypto_screening/base.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/crypto_screening/collect/assets.py` & `crypto-screening-1.3.2/crypto_screening/collect/assets.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/crypto_screening/collect/exchanges.py` & `crypto-screening-1.3.2/crypto_screening/collect/exchanges.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/crypto_screening/collect/screeners.py` & `crypto-screening-1.3.2/crypto_screening/collect/screeners.py`

 * *Files 7% similar despite different names*

```diff
@@ -16,15 +16,17 @@
     "matching_screener_pair",
     "matching_screener_pairs",
     "MarketScreenerSignature",
     "find_screeners",
     "structure_screeners",
     "live_screeners",
     "remove_empty_screeners",
-    "screeners_exchanges_symbols"
+    "screeners_exchanges_symbols",
+    "structure_exchanges_symbols_screeners",
+    "structure_exchanges_symbols_screener"
 ]
 
 AssetMatches = Iterable[Iterable[str]]
 
 def matching_screener_pair(
         screener1: BaseScreener,
         screener2: BaseScreener, /, *,
@@ -282,9 +284,58 @@
     for screener in screeners:
         data.setdefault(screener.exchange, []).append(screener.symbol)
     # end for
 
     return {
         exchange: list(set(symbols))
         for exchange, symbols in data.items()
+        if symbols
     }
-# end screeners_exchanges_symbols
+# end screeners_exchanges_symbols
+
+def structure_exchanges_symbols_screeners(
+        screeners: Iterable[BaseScreener]
+) -> Dict[str, Dict[str, List[BaseScreener]]]:
+    """
+    Structures the screener objects by exchanges and symbols
+
+    :param screeners: The screeners to structure.
+
+    :return: The structure of the screeners.
+    """
+
+    structure = {}
+
+    for screener in screeners:
+        (
+            structure.
+            setdefault(screener.exchange, {}).
+            setdefault(screener.symbol, [])
+        ).append(screener)
+    # end for
+
+    return structure
+# end structure_exchanges_symbols_screeners
+
+def structure_exchanges_symbols_screener(
+        screeners: Iterable[BaseScreener]
+) -> Dict[str, Dict[str, BaseScreener]]:
+    """
+    Structures the screener objects by exchanges and symbols
+
+    :param screeners: The screeners to structure.
+
+    :return: The structure of the screeners.
+    """
+
+    structure = {}
+
+    for screener in screeners:
+        (
+            structure.
+            setdefault(screener.exchange, {}).
+            setdefault(screener.symbol, screener)
+        )
+    # end for
+
+    return structure
+# end structure_exchanges_symbols_screener
```

### Comparing `crypto-screening-1.3.1/crypto_screening/collect/symbols.py` & `crypto-screening-1.3.2/crypto_screening/collect/symbols.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/crypto_screening/dataset.py` & `crypto-screening-1.3.2/crypto_screening/dataset.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/crypto_screening/document.py` & `crypto-screening-1.3.2/crypto_screening/document.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/crypto_screening/interval.py` & `crypto-screening-1.3.2/crypto_screening/interval.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/crypto_screening/ohlcv.py` & `crypto-screening-1.3.2/crypto_screening/ohlcv.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/crypto_screening/orderbook.py` & `crypto-screening-1.3.2/crypto_screening/orderbook.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/crypto_screening/process.py` & `crypto-screening-1.3.2/crypto_screening/process.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/crypto_screening/screener.py` & `crypto-screening-1.3.2/crypto_screening/screener.py`

 * *Files 1% similar despite different names*

```diff
@@ -658,23 +658,34 @@
         if not isinstance(data, dict):
             raise ValueError
         # end if
 
         for exchange, values in data.items():
             if not (
                 isinstance(exchange, str) and
-                isinstance(values, dict) and
-                all(
-                    isinstance(symbol, str) and
-                    isinstance(dataset, pd.DataFrame)
-                    for symbol, dataset in values.items()
+                (
+                    (
+                        isinstance(values, dict) and
+                        all(
+                            isinstance(symbol, str) and
+                            isinstance(dataset, pd.DataFrame)
+                            for symbol, dataset in values.items()
+                        )
+                    ) or (all(isinstance(value, str) for value in values))
                 )
             ):
                 raise ValueError
             # end if
+
+            if not isinstance(values, dict):
+                data[exchange] = {
+                    symbol: create_market_dataframe()
+                    for symbol in values
+                }
+            # end if
         # end for
 
     except (TypeError, ValueError):
         raise ValueError(
             f"Data must be of type {Market}, not: {data}."
         )
     # end try
@@ -1171,15 +1182,15 @@
     Structures the screener objects by exchanges and symbols
 
     :param screeners: The screeners to structure.
 
     :return: The structure of the screeners.
     """
 
-    structure: Dict[str, Dict[str, List[pd.DataFrame]]] = {}
+    structure = {}
 
     for screener in screeners:
         (
             structure.
             setdefault(screener.exchange, {}).
             setdefault(screener.symbol, [])
         ).append(screener.market)
@@ -1195,15 +1206,15 @@
     Structures the screener objects by exchanges and symbols
 
     :param screeners: The screeners to structure.
 
     :return: The structure of the screeners.
     """
 
-    structure: Dict[str, Dict[str, pd.DataFrame]] = {}
+    structure = {}
 
     for screener in screeners:
         (
             structure.
             setdefault(screener.exchange, {}).
             setdefault(screener.symbol, screener.market)
         )
```

### Comparing `crypto-screening-1.3.1/crypto_screening/symbols.py` & `crypto-screening-1.3.2/crypto_screening/symbols.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/crypto_screening/validate.py` & `crypto-screening-1.3.2/crypto_screening/validate.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/crypto_screening.egg-info/PKG-INFO` & `crypto-screening-1.3.2/crypto_screening.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: crypto-screening
-Version: 1.3.1
+Version: 1.3.2
 Summary: A software for automatically recording real-time crypto exchanges and pairs OHLCV and Orderbook rates.
 Home-page: https://github.com/Shahaf-F-S/crypto-screening
 Author: Shahaf Frank-Shapir
 Author-email: shahaffrs@gmail.com
 License: MIT
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `crypto-screening-1.3.1/crypto_screening.egg-info/SOURCES.txt` & `crypto-screening-1.3.2/crypto_screening.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.3.1/pyproject.toml` & `crypto-screening-1.3.2/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = 'crypto-screening'
-version = '1.3.1'
+version = '1.3.2'
 description = 'A software for automatically recording real-time crypto exchanges and pairs OHLCV and Orderbook rates.'
 classifiers = [
 	'Intended Audience :: Developers',
 	'License :: OSI Approved :: MIT License',
 	'Programming Language :: Python',
 	'Programming Language :: Python :: 3',
 	'Programming Language :: Python :: 3.8',
```

### Comparing `crypto-screening-1.3.1/setup.py` & `crypto-screening-1.3.2/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -20,15 +20,15 @@
         exclude=[
             "__pycache__",
             "*.pyc"
         ],
         requirements="requirements.txt",
         dev_requirements="requirements-dev.txt",
         name='crypto-screening',
-        version='1.3.1',
+        version='1.3.2',
         description=(
             "A software for automatically recording "
             "real-time crypto exchanges and pairs "
             "OHLCV and Orderbook rates."
         ),
         license='MIT',
         author="Shahaf Frank-Shapir",
```


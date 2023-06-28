# Comparing `tmp/fugle-trade-0.5.1.tar.gz` & `tmp/fugle_trade-0.5.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "fugle-trade-0.5.1.tar", max compression
+gzip compressed data, was "fugle_trade-0.5.2.tar", max compression
```

## Comparing `fugle-trade-0.5.1.tar` & `fugle_trade-0.5.2.tar`

### file list

```diff
@@ -1,12 +1,11 @@
--rw-r--r--   0        0        0     1075 2023-05-02 08:19:50.921872 fugle-trade-0.5.1/LICENSE
--rw-r--r--   0        0        0      776 2023-05-02 08:19:50.921872 fugle-trade-0.5.1/README.md
--rw-r--r--   0        0        0       22 2023-05-02 08:19:50.921872 fugle-trade-0.5.1/fugle_trade/__init__.py
--rw-r--r--   0        0        0      760 2023-05-02 08:19:50.921872 fugle-trade-0.5.1/fugle_trade/constant.py
--rw-r--r--   0        0        0      469 2023-05-02 08:19:50.921872 fugle-trade-0.5.1/fugle_trade/init.py
--rw-r--r--   0        0        0     2616 2023-05-02 08:19:50.921872 fugle-trade-0.5.1/fugle_trade/order.py
--rw-r--r--   0        0        0     8658 2023-05-02 08:19:50.921872 fugle-trade-0.5.1/fugle_trade/sdk.py
--rw-r--r--   0        0        0     1924 2023-05-02 08:19:50.921872 fugle-trade-0.5.1/fugle_trade/util.py
--rw-r--r--   0        0        0     1842 2023-05-02 08:19:50.921872 fugle-trade-0.5.1/fugle_trade/websocket.py
--rw-r--r--   0        0        0      772 2023-05-02 08:19:50.921872 fugle-trade-0.5.1/pyproject.toml
--rw-r--r--   0        0        0     1559 2023-05-02 08:20:03.063463 fugle-trade-0.5.1/setup.py
--rw-r--r--   0        0        0     1701 2023-05-02 08:20:03.063759 fugle-trade-0.5.1/PKG-INFO
+-rw-r--r--   0        0        0     1075 2023-06-28 07:02:23.086410 fugle_trade-0.5.2/LICENSE
+-rw-r--r--   0        0        0      776 2023-06-28 07:02:23.086410 fugle_trade-0.5.2/README.md
+-rw-r--r--   0        0        0       22 2023-06-28 07:02:23.086410 fugle_trade-0.5.2/fugle_trade/__init__.py
+-rw-r--r--   0        0        0      760 2023-06-28 07:02:23.086410 fugle_trade-0.5.2/fugle_trade/constant.py
+-rw-r--r--   0        0        0      469 2023-06-28 07:02:23.086410 fugle_trade-0.5.2/fugle_trade/init.py
+-rw-r--r--   0        0        0     2616 2023-06-28 07:02:23.086410 fugle_trade-0.5.2/fugle_trade/order.py
+-rw-r--r--   0        0        0     8658 2023-06-28 07:02:23.086410 fugle_trade-0.5.2/fugle_trade/sdk.py
+-rw-r--r--   0        0        0     1924 2023-06-28 07:02:23.086410 fugle_trade-0.5.2/fugle_trade/util.py
+-rw-r--r--   0        0        0     1842 2023-06-28 07:02:23.086410 fugle_trade-0.5.2/fugle_trade/websocket.py
+-rw-r--r--   0        0        0      773 2023-06-28 07:02:23.086410 fugle_trade-0.5.2/pyproject.toml
+-rw-r--r--   0        0        0     1759 1970-01-01 00:00:00.000000 fugle_trade-0.5.2/PKG-INFO
```

### Comparing `fugle-trade-0.5.1/LICENSE` & `fugle_trade-0.5.2/LICENSE`

 * *Files identical despite different names*

### Comparing `fugle-trade-0.5.1/README.md` & `fugle_trade-0.5.2/README.md`

 * *Files identical despite different names*

### Comparing `fugle-trade-0.5.1/fugle_trade/constant.py` & `fugle_trade-0.5.2/fugle_trade/constant.py`

 * *Files identical despite different names*

### Comparing `fugle-trade-0.5.1/fugle_trade/order.py` & `fugle_trade-0.5.2/fugle_trade/order.py`

 * *Files identical despite different names*

### Comparing `fugle-trade-0.5.1/fugle_trade/sdk.py` & `fugle_trade-0.5.2/fugle_trade/sdk.py`

 * *Files identical despite different names*

### Comparing `fugle-trade-0.5.1/fugle_trade/util.py` & `fugle_trade-0.5.2/fugle_trade/util.py`

 * *Files identical despite different names*

### Comparing `fugle-trade-0.5.1/fugle_trade/websocket.py` & `fugle_trade-0.5.2/fugle_trade/websocket.py`

 * *Files identical despite different names*

### Comparing `fugle-trade-0.5.1/pyproject.toml` & `fugle_trade-0.5.2/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "fugle-trade"
-version = "0.5.1"
+version = "0.5.2"
 description = ""
 authors = ["Fortuna Intelligence Co., Ltd. <development@fugle.tw>"]
 license = "MIT"
 readme = "README.md"
 homepage = "https://github.com/fugle-dev/fugle-trade-python#readme"
 repository = "https://github.com/fugle-dev/fugle-trade-python"
 documentation = "https://developer.fugle.tw/docs/trading/intro"
@@ -13,18 +13,18 @@
 
 [[tool.poetry.source]]
 name = "pypi_"
 url = "https://pypi.org/simple/"
 
 [tool.poetry.dependencies]
 python = "^3.7"
-websocket-client = "1.2.1"
+websocket-client = "^1.2.1"
 keyring = "23.5.0"
 "keyrings.cryptfile" = "1.3.8"
-fugle-trade-core = "0.5.0"
+fugle-trade-core = "0.5.1"
 
 [tool.poetry.dev-dependencies]
 pytest = "^7.1.1"
 
 [build-system]
 requires = ["poetry-core>=1.0.0"]
 build-backend = "poetry.core.masonry.api"
```

### Comparing `fugle-trade-0.5.1/PKG-INFO` & `fugle_trade-0.5.2/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,27 +1,28 @@
 Metadata-Version: 2.1
 Name: fugle-trade
-Version: 0.5.1
+Version: 0.5.2
 Summary: 
 Home-page: https://github.com/fugle-dev/fugle-trade-python#readme
 License: MIT
 Keywords: fugle,trade,stock
 Author: Fortuna Intelligence Co., Ltd.
 Author-email: development@fugle.tw
 Requires-Python: >=3.7,<4.0
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
-Requires-Dist: fugle-trade-core (==0.5.0)
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Requires-Dist: fugle-trade-core (==0.5.1)
 Requires-Dist: keyring (==23.5.0)
 Requires-Dist: keyrings.cryptfile (==1.3.8)
-Requires-Dist: websocket-client (==1.2.1)
+Requires-Dist: websocket-client (>=1.2.1,<2.0.0)
 Project-URL: Documentation, https://developer.fugle.tw/docs/trading/intro
 Project-URL: Repository, https://github.com/fugle-dev/fugle-trade-python
 Description-Content-Type: text/markdown
 
 # Fugle Trade Python SDK
 
 ## 事前準備
```


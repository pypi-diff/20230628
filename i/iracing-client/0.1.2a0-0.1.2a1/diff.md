# Comparing `tmp/iracing_client-0.1.2a0.tar.gz` & `tmp/iracing_client-0.1.2a1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "iracing_client-0.1.2a0.tar", max compression
+gzip compressed data, was "iracing_client-0.1.2a1.tar", max compression
```

## Comparing `iracing_client-0.1.2a0.tar` & `iracing_client-0.1.2a1.tar`

### file list

```diff
@@ -1,12 +1,12 @@
--rw-r--r--   0        0        0    11357 2023-06-28 14:10:43.287576 iracing_client-0.1.2a0/LICENSE
--rw-r--r--   0        0        0     3403 2023-06-28 14:10:43.287576 iracing_client-0.1.2a0/README.md
--rw-r--r--   0        0        0      577 2023-06-28 14:10:43.287576 iracing_client-0.1.2a0/pyproject.toml
--rw-r--r--   0        0        0        0 2023-06-28 14:10:43.287576 iracing_client-0.1.2a0/src/iracing_client/__init__.py
--rw-r--r--   0        0        0     4606 2023-06-28 14:10:43.287576 iracing_client-0.1.2a0/src/iracing_client/auth.py
--rw-r--r--   0        0        0        0 2023-06-28 14:10:43.287576 iracing_client-0.1.2a0/src/iracing_client/data/__init__.py
--rw-r--r--   0        0        0     2937 2023-06-28 14:10:43.287576 iracing_client-0.1.2a0/src/iracing_client/data/common.py
--rw-r--r--   0        0        0     2785 2023-06-28 14:10:43.287576 iracing_client-0.1.2a0/src/iracing_client/data/constants.py
--rw-r--r--   0        0        0     9927 2023-06-28 14:10:43.287576 iracing_client-0.1.2a0/src/iracing_client/data/league.py
--rw-r--r--   0        0        0     5450 2023-06-28 14:10:43.291576 iracing_client-0.1.2a0/src/iracing_client/data/member.py
--rw-r--r--   0        0        0      562 2023-06-28 14:10:43.291576 iracing_client-0.1.2a0/src/iracing_client/trace.py
--rw-r--r--   0        0        0     3789 1970-01-01 00:00:00.000000 iracing_client-0.1.2a0/PKG-INFO
+-rw-r--r--   0        0        0    11357 2023-06-28 14:27:32.778043 iracing_client-0.1.2a1/LICENSE
+-rw-r--r--   0        0        0     3378 2023-06-28 14:27:32.778043 iracing_client-0.1.2a1/README.md
+-rw-r--r--   0        0        0      577 2023-06-28 14:27:32.782043 iracing_client-0.1.2a1/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-28 14:27:32.782043 iracing_client-0.1.2a1/src/iracing_client/__init__.py
+-rw-r--r--   0        0        0     4606 2023-06-28 14:27:32.782043 iracing_client-0.1.2a1/src/iracing_client/auth.py
+-rw-r--r--   0        0        0        0 2023-06-28 14:27:32.782043 iracing_client-0.1.2a1/src/iracing_client/data/__init__.py
+-rw-r--r--   0        0        0     2937 2023-06-28 14:27:32.782043 iracing_client-0.1.2a1/src/iracing_client/data/common.py
+-rw-r--r--   0        0        0     2785 2023-06-28 14:27:32.782043 iracing_client-0.1.2a1/src/iracing_client/data/constants.py
+-rw-r--r--   0        0        0     9927 2023-06-28 14:27:32.782043 iracing_client-0.1.2a1/src/iracing_client/data/league.py
+-rw-r--r--   0        0        0     5450 2023-06-28 14:27:32.782043 iracing_client-0.1.2a1/src/iracing_client/data/member.py
+-rw-r--r--   0        0        0      562 2023-06-28 14:27:32.782043 iracing_client-0.1.2a1/src/iracing_client/trace.py
+-rw-r--r--   0        0        0     3764 1970-01-01 00:00:00.000000 iracing_client-0.1.2a1/PKG-INFO
```

### Comparing `iracing_client-0.1.2a0/LICENSE` & `iracing_client-0.1.2a1/LICENSE`

 * *Files identical despite different names*

### Comparing `iracing_client-0.1.2a0/README.md` & `iracing_client-0.1.2a1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -2,29 +2,29 @@
 
 [![CodeQL](https://github.com/tegataiprime/iracing-client/actions/workflows/github-code-scanning/codeql/badge.svg)](https://github.com/tegataiprime/iracing-client/actions/workflows/github-code-scanning/codeql)
 
 [![Test Suite](https://github.com/tegataiprime/iracing-client/actions/workflows/test-suite.yaml/badge.svg)](https://github.com/tegataiprime/iracing-client/actions/workflows/test-suite.yaml)
 
 [![Release](https://github.com/tegataiprime/iracing-client/actions/workflows/release.yaml/badge.svg)](https://github.com/tegataiprime/iracing-client/actions/workflows/release.yaml)
 
-# iracing-data-client
+# iracing-client
 A Python Client Library for working with iRacing Data API.
 
 This library provides communiction & error handling with the iRacing Data API.
 
 
 ## Quick Start
 
 JSON formatted data returned by iRacing is deserialized as either a `list` or `dict` using [`json.loads`](https://docs.python.org/3/library/json.html)
 
 ```python
-import iracing_data_client.auth as auth
-from iracing_data_client.data.constants import Constants
-from iracing_data_client.data.member import Member
-from iracing_data_client.data.league import League
+import iracing_client.auth as auth
+from iracing_client.data.constants import Constants
+from iracing_client.data.member import Member
+from iracing_client.data.league import League
 
 # Authenticate with iRacing
 iracing_username = os.environ.ge('IRACING_USERNAME')
 iracing_password = os.environ.ge('IRACING_PASSWORD')
 
 http_session = auth.login(iracing_username, iracing_password)
```

### Comparing `iracing_client-0.1.2a0/pyproject.toml` & `iracing_client-0.1.2a1/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "iracing-client"
-version = "0.1.2a0"
+version = "0.1.2a1"
 description = ""
 authors = ["James Carter <tegatai@gmail.com>"]
 readme = "README.md"
 packages = [{include = "src/iracing_client"}]
 
 [tool.poetry.dependencies]
 python = "^3.10"
```

### Comparing `iracing_client-0.1.2a0/src/iracing_client/auth.py` & `iracing_client-0.1.2a1/src/iracing_client/auth.py`

 * *Files identical despite different names*

### Comparing `iracing_client-0.1.2a0/src/iracing_client/data/common.py` & `iracing_client-0.1.2a1/src/iracing_client/data/common.py`

 * *Files identical despite different names*

### Comparing `iracing_client-0.1.2a0/src/iracing_client/data/constants.py` & `iracing_client-0.1.2a1/src/iracing_client/data/constants.py`

 * *Files identical despite different names*

### Comparing `iracing_client-0.1.2a0/src/iracing_client/data/league.py` & `iracing_client-0.1.2a1/src/iracing_client/data/league.py`

 * *Files identical despite different names*

### Comparing `iracing_client-0.1.2a0/src/iracing_client/data/member.py` & `iracing_client-0.1.2a1/src/iracing_client/data/member.py`

 * *Files identical despite different names*

### Comparing `iracing_client-0.1.2a0/src/iracing_client/trace.py` & `iracing_client-0.1.2a1/src/iracing_client/trace.py`

 * *Files identical despite different names*

### Comparing `iracing_client-0.1.2a0/PKG-INFO` & `iracing_client-0.1.2a1/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: iracing-client
-Version: 0.1.2a0
+Version: 0.1.2a1
 Summary: 
 Author: James Carter
 Author-email: tegatai@gmail.com
 Requires-Python: >=3.10,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
@@ -15,29 +15,29 @@
 
 [![CodeQL](https://github.com/tegataiprime/iracing-client/actions/workflows/github-code-scanning/codeql/badge.svg)](https://github.com/tegataiprime/iracing-client/actions/workflows/github-code-scanning/codeql)
 
 [![Test Suite](https://github.com/tegataiprime/iracing-client/actions/workflows/test-suite.yaml/badge.svg)](https://github.com/tegataiprime/iracing-client/actions/workflows/test-suite.yaml)
 
 [![Release](https://github.com/tegataiprime/iracing-client/actions/workflows/release.yaml/badge.svg)](https://github.com/tegataiprime/iracing-client/actions/workflows/release.yaml)
 
-# iracing-data-client
+# iracing-client
 A Python Client Library for working with iRacing Data API.
 
 This library provides communiction & error handling with the iRacing Data API.
 
 
 ## Quick Start
 
 JSON formatted data returned by iRacing is deserialized as either a `list` or `dict` using [`json.loads`](https://docs.python.org/3/library/json.html)
 
 ```python
-import iracing_data_client.auth as auth
-from iracing_data_client.data.constants import Constants
-from iracing_data_client.data.member import Member
-from iracing_data_client.data.league import League
+import iracing_client.auth as auth
+from iracing_client.data.constants import Constants
+from iracing_client.data.member import Member
+from iracing_client.data.league import League
 
 # Authenticate with iRacing
 iracing_username = os.environ.ge('IRACING_USERNAME')
 iracing_password = os.environ.ge('IRACING_PASSWORD')
 
 http_session = auth.login(iracing_username, iracing_password)
```


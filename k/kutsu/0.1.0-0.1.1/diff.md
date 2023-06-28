# Comparing `tmp/kutsu-0.1.0.tar.gz` & `tmp/kutsu-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "kutsu-0.1.0.tar", max compression
+gzip compressed data, was "kutsu-0.1.1.tar", max compression
```

## Comparing `kutsu-0.1.0.tar` & `kutsu-0.1.1.tar`

### file list

```diff
@@ -1,10 +1,10 @@
--rw-r--r--   0        0        0     1075 2023-06-27 19:06:48.559829 kutsu-0.1.0/LICENSE
--rw-r--r--   0        0        0        0 2022-11-02 12:59:51.469753 kutsu-0.1.0/README.md
--rw-r--r--   0        0        0     1897 2023-02-14 19:18:37.775923 kutsu-0.1.0/kutsu/__init__.py
--rw-r--r--   0        0        0    34323 2023-06-21 15:01:38.938540 kutsu-0.1.0/kutsu/expressions.py
--rw-r--r--   0        0        0    71115 2023-06-15 11:49:49.550870 kutsu-0.1.0/kutsu/http_request.py
--rw-r--r--   0        0        0     8423 2023-03-22 07:14:09.600096 kutsu-0.1.0/kutsu/http_server.py
--rw-r--r--   0        0        0    22501 2023-03-24 09:03:12.411470 kutsu-0.1.0/kutsu/state.py
--rw-r--r--   0        0        0     1227 2023-01-28 19:34:03.346438 kutsu-0.1.0/kutsu/util.py
--rw-r--r--   0        0        0     2883 2023-06-27 19:52:24.329108 kutsu-0.1.0/pyproject.toml
--rw-r--r--   0        0        0      907 1970-01-01 00:00:00.000000 kutsu-0.1.0/PKG-INFO
+-rw-r--r--   0        0        0     1075 2023-06-27 19:06:48.559829 kutsu-0.1.1/LICENSE
+-rw-r--r--   0        0        0        0 2022-11-02 12:59:51.469753 kutsu-0.1.1/README.md
+-rw-r--r--   0        0        0     1897 2023-02-14 19:18:37.775923 kutsu-0.1.1/kutsu/__init__.py
+-rw-r--r--   0        0        0    34323 2023-06-21 15:01:38.938540 kutsu-0.1.1/kutsu/expressions.py
+-rw-r--r--   0        0        0    71115 2023-06-15 11:49:49.550870 kutsu-0.1.1/kutsu/http_request.py
+-rw-r--r--   0        0        0     8423 2023-03-22 07:14:09.600096 kutsu-0.1.1/kutsu/http_server.py
+-rw-r--r--   0        0        0    22501 2023-03-24 09:03:12.411470 kutsu-0.1.1/kutsu/state.py
+-rw-r--r--   0        0        0     1227 2023-01-28 19:34:03.346438 kutsu-0.1.1/kutsu/util.py
+-rw-r--r--   0        0        0     2895 2023-06-28 05:31:19.316525 kutsu-0.1.1/pyproject.toml
+-rw-r--r--   0        0        0      791 1970-01-01 00:00:00.000000 kutsu-0.1.1/PKG-INFO
```

### Comparing `kutsu-0.1.0/LICENSE` & `kutsu-0.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `kutsu-0.1.0/kutsu/__init__.py` & `kutsu-0.1.1/kutsu/__init__.py`

 * *Files identical despite different names*

### Comparing `kutsu-0.1.0/kutsu/expressions.py` & `kutsu-0.1.1/kutsu/expressions.py`

 * *Files identical despite different names*

### Comparing `kutsu-0.1.0/kutsu/http_request.py` & `kutsu-0.1.1/kutsu/http_request.py`

 * *Files identical despite different names*

### Comparing `kutsu-0.1.0/kutsu/http_server.py` & `kutsu-0.1.1/kutsu/http_server.py`

 * *Files identical despite different names*

### Comparing `kutsu-0.1.0/kutsu/state.py` & `kutsu-0.1.1/kutsu/state.py`

 * *Files identical despite different names*

### Comparing `kutsu-0.1.0/kutsu/util.py` & `kutsu-0.1.1/kutsu/util.py`

 * *Files identical despite different names*

### Comparing `kutsu-0.1.0/pyproject.toml` & `kutsu-0.1.1/pyproject.toml`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 [tool.poetry]
 name = "kutsu"
-version = "0.1.0"
+version = "0.1.1"
 description = ""
 authors = ["Mikko Kortelainen <mikko.kortelainen@techelp.fi>"]
 license = "MIT"
 homepage = "https://github.com/kortsi/kutsu"
 repository = "https://github.com/kortsi/kutsu"
 readme = "README.md"
 include = ["README.md", "LICENSE"]
 
 [tool.poetry.dependencies]
-python = "^3.10"
-nest-asyncio = "^1.5.6"
-httpx = { version = "^0.23.0", extras=["http2"] }
-rich = "^12.6.0"
-Pygments = "^2.14.0"
-tornado = "^6.2"
-trio = "^0.22.0"
-boto3 = { version = "^1.26.93", optional = true }
-httpx-auth-awssigv4 = { version = "^0.1.4", optional = true }
+python = ">=3.10,<4.0"
+# TODO: is nest-asyncio needed anymore?
+nest-asyncio = ">=1.5"
+httpx = { version = ">=0.23", extras=["http2"] }
+rich = ">=12"
+Pygments = ">=2"
+tornado = ">=6"
+boto3 = { version = ">=1.26", optional = true }
+httpx-auth-awssigv4 = { version = "*", optional = true }
 
 [tool.poetry.extras]
 aws = ["boto3", "httpx-auth-awssigv4"]
 
 [tool.poetry.dev-dependencies]
 pytest = "^7.2"
 pylint = "^2.15.5"
```

### Comparing `kutsu-0.1.0/PKG-INFO` & `kutsu-0.1.1/PKG-INFO`

 * *Files 18% similar despite different names*

```diff
@@ -1,26 +1,25 @@
 Metadata-Version: 2.1
 Name: kutsu
-Version: 0.1.0
+Version: 0.1.1
 Summary: 
 Home-page: https://github.com/kortsi/kutsu
 License: MIT
 Author: Mikko Kortelainen
 Author-email: mikko.kortelainen@techelp.fi
 Requires-Python: >=3.10,<4.0
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Provides-Extra: aws
-Requires-Dist: Pygments (>=2.14.0,<3.0.0)
-Requires-Dist: boto3 (>=1.26.93,<2.0.0) ; extra == "aws"
-Requires-Dist: httpx-auth-awssigv4 (>=0.1.4,<0.2.0) ; extra == "aws"
-Requires-Dist: httpx[http2] (>=0.23.0,<0.24.0)
-Requires-Dist: nest-asyncio (>=1.5.6,<2.0.0)
-Requires-Dist: rich (>=12.6.0,<13.0.0)
-Requires-Dist: tornado (>=6.2,<7.0)
-Requires-Dist: trio (>=0.22.0,<0.23.0)
+Requires-Dist: Pygments (>=2)
+Requires-Dist: boto3 (>=1.26) ; extra == "aws"
+Requires-Dist: httpx-auth-awssigv4 ; extra == "aws"
+Requires-Dist: httpx[http2] (>=0.23)
+Requires-Dist: nest-asyncio (>=1.5)
+Requires-Dist: rich (>=12)
+Requires-Dist: tornado (>=6)
 Project-URL: Repository, https://github.com/kortsi/kutsu
 Description-Content-Type: text/markdown
```


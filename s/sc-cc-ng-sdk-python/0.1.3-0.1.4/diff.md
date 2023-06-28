# Comparing `tmp/sc_cc_ng_sdk_python-0.1.3.tar.gz` & `tmp/sc_cc_ng_sdk_python-0.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sc_cc_ng_sdk_python-0.1.3.tar", max compression
+gzip compressed data, was "sc_cc_ng_sdk_python-0.1.4.tar", max compression
```

## Comparing `sc_cc_ng_sdk_python-0.1.3.tar` & `sc_cc_ng_sdk_python-0.1.4.tar`

### file list

```diff
@@ -1,4 +1,4 @@
--rw-r--r--   0        0        0        0 2023-06-26 13:45:09.675633 sc_cc_ng_sdk_python-0.1.3/README.md
--rw-r--r--   0        0        0      530 2023-06-26 19:39:39.183266 sc_cc_ng_sdk_python-0.1.3/pyproject.toml
--rw-r--r--   0        0        0     6286 2023-06-26 19:37:08.166313 sc_cc_ng_sdk_python-0.1.3/sc_cc_ng_sdk_python/__init__.py
--rw-r--r--   0        0        0      497 1970-01-01 00:00:00.000000 sc_cc_ng_sdk_python-0.1.3/PKG-INFO
+-rw-r--r--   0        0        0        0 2023-06-26 13:45:09.675633 sc_cc_ng_sdk_python-0.1.4/README.md
+-rw-r--r--   0        0        0      530 2023-06-28 08:00:59.350471 sc_cc_ng_sdk_python-0.1.4/pyproject.toml
+-rw-r--r--   0        0        0    14892 2023-06-28 07:59:21.537546 sc_cc_ng_sdk_python-0.1.4/sc_cc_ng_sdk_python/__init__.py
+-rw-r--r--   0        0        0      497 1970-01-01 00:00:00.000000 sc_cc_ng_sdk_python-0.1.4/PKG-INFO
```

### Comparing `sc_cc_ng_sdk_python-0.1.3/pyproject.toml` & `sc_cc_ng_sdk_python-0.1.4/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "sc-cc-ng-sdk-python"
-version = "0.1.3"
+version = "0.1.4"
 description = ""
 authors = ["Rikard Olsson <rikard@thryselius.se>"]
 readme = "README.md"
 packages = [{include = "sc_cc_ng_sdk_python"}]
 
 [tool.poetry.dependencies]
 python = "^3.9"
```


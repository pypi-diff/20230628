# Comparing `tmp/polywrap_test_cases-0.1.0a34.tar.gz` & `tmp/polywrap_test_cases-0.1.0a35.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "polywrap_test_cases-0.1.0a34.tar", max compression
+gzip compressed data, was "polywrap_test_cases-0.1.0a35.tar", max compression
```

## Comparing `polywrap_test_cases-0.1.0a34.tar` & `polywrap_test_cases-0.1.0a35.tar`

### file list

```diff
@@ -1,6 +1,6 @@
--rw-r--r--   0        0        0       96 2023-06-27 11:59:05.060871 polywrap_test_cases-0.1.0a34/README.md
--rw-r--r--   0        0        0     1257 2023-06-27 11:59:05.060871 polywrap_test_cases-0.1.0a34/polywrap_test_cases/__init__.py
--rw-r--r--   0        0        0      142 2023-06-27 11:59:05.060871 polywrap_test_cases-0.1.0a34/polywrap_test_cases/__main__.py
--rw-r--r--   0        0        0        0 2023-06-27 11:59:05.060871 polywrap_test_cases-0.1.0a34/polywrap_test_cases/py.typed
--rw-r--r--   0        0        0      991 2023-06-27 12:00:31.557378 polywrap_test_cases-0.1.0a34/pyproject.toml
--rw-r--r--   0        0        0      453 1970-01-01 00:00:00.000000 polywrap_test_cases-0.1.0a34/PKG-INFO
+-rw-r--r--   0        0        0       96 2023-06-28 13:05:20.152194 polywrap_test_cases-0.1.0a35/README.md
+-rw-r--r--   0        0        0     1257 2023-06-28 13:05:20.152194 polywrap_test_cases-0.1.0a35/polywrap_test_cases/__init__.py
+-rw-r--r--   0        0        0      142 2023-06-28 13:05:20.152194 polywrap_test_cases-0.1.0a35/polywrap_test_cases/__main__.py
+-rw-r--r--   0        0        0        0 2023-06-28 13:05:20.152194 polywrap_test_cases-0.1.0a35/polywrap_test_cases/py.typed
+-rw-r--r--   0        0        0      991 2023-06-28 13:06:52.061022 polywrap_test_cases-0.1.0a35/pyproject.toml
+-rw-r--r--   0        0        0      453 1970-01-01 00:00:00.000000 polywrap_test_cases-0.1.0a35/PKG-INFO
```

### Comparing `polywrap_test_cases-0.1.0a34/polywrap_test_cases/__init__.py` & `polywrap_test_cases-0.1.0a35/polywrap_test_cases/__init__.py`

 * *Files identical despite different names*

### Comparing `polywrap_test_cases-0.1.0a34/pyproject.toml` & `polywrap_test_cases-0.1.0a35/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["poetry-core"]
 build-backend = "poetry.core.masonry.api"
 
 [tool.poetry]
 name = "polywrap-test-cases"
-version = "0.1.0a34"
+version = "0.1.0a35"
 description = "Plugin package"
 authors = ["Cesar <cesar@polywrap.io>"]
 readme = "README.md"
 
 [tool.poetry.dependencies]
 python = "^3.10"
```


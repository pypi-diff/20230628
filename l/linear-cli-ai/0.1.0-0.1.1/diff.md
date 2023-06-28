# Comparing `tmp/linear_cli_ai-0.1.0.tar.gz` & `tmp/linear_cli_ai-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "linear_cli_ai-0.1.0.tar", max compression
+gzip compressed data, was "linear_cli_ai-0.1.1.tar", max compression
```

## Comparing `linear_cli_ai-0.1.0.tar` & `linear_cli_ai-0.1.1.tar`

### file list

```diff
@@ -1,8 +1,13 @@
--rw-r--r--   0        0        0    11357 2023-06-19 14:13:31.689313 linear_cli_ai-0.1.0/LICENSE
--rw-r--r--   0        0        0       38 2023-06-19 14:13:31.689629 linear_cli_ai-0.1.0/README.md
--rw-r--r--   0        0        0      524 2023-06-23 16:31:35.612691 linear_cli_ai-0.1.0/pyproject.toml
--rw-r--r--   0        0        0        0 2023-06-23 15:09:53.034479 linear_cli_ai-0.1.0/src/__init__.py
--rw-r--r--   0        0        0     5613 2023-06-20 03:18:21.457637 linear_cli_ai-0.1.0/src/linear.py
--rw-r--r--   0        0        0     5524 2023-06-23 14:50:58.274044 linear_cli_ai-0.1.0/src/main.py
--rw-r--r--   0        0        0      817 1970-01-01 00:00:00.000000 linear_cli_ai-0.1.0/setup.py
--rw-r--r--   0        0        0      575 1970-01-01 00:00:00.000000 linear_cli_ai-0.1.0/PKG-INFO
+-rw-r--r--   0        0        0    11357 2023-06-19 14:13:31.689313 linear_cli_ai-0.1.1/LICENSE
+-rw-r--r--   0        0        0      397 2023-06-28 03:47:31.594600 linear_cli_ai-0.1.1/README.md
+-rw-r--r--   0        0        0      543 2023-06-28 08:12:43.272413 linear_cli_ai-0.1.1/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-23 15:09:53.034479 linear_cli_ai-0.1.1/src/__init__.py
+-rw-r--r--   0        0        0      101 2023-06-28 05:20:24.733251 linear_cli_ai-0.1.1/src/exceptions.py
+-rw-r--r--   0        0        0     1347 2023-06-28 07:36:53.616167 linear_cli_ai-0.1.1/src/function_schema.py
+-rw-r--r--   0        0        0     1791 2023-06-28 05:07:54.946635 linear_cli_ai-0.1.1/src/gpt.py
+-rw-r--r--   0        0        0     8338 2023-06-28 07:35:34.449550 linear_cli_ai-0.1.1/src/linear.py
+-rw-r--r--   0        0        0     1991 2023-06-28 07:46:36.815977 linear_cli_ai-0.1.1/src/linear_ai.py
+-rw-r--r--   0        0        0     4833 2023-06-28 06:43:22.960364 linear_cli_ai-0.1.1/src/main.py
+-rw-r--r--   0        0        0      297 2023-06-27 16:14:52.685333 linear_cli_ai-0.1.1/src/objectTypes.py
+-rw-r--r--   0        0        0     1229 1970-01-01 00:00:00.000000 linear_cli_ai-0.1.1/setup.py
+-rw-r--r--   0        0        0      975 1970-01-01 00:00:00.000000 linear_cli_ai-0.1.1/PKG-INFO
```

### Comparing `linear_cli_ai-0.1.0/LICENSE` & `linear_cli_ai-0.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `linear_cli_ai-0.1.0/pyproject.toml` & `linear_cli_ai-0.1.1/pyproject.toml`

 * *Files 3% similar despite different names*

```diff
@@ -1,20 +1,21 @@
 [tool.poetry]
 name = "linear-cli-ai"
-version = "0.1.0"
+version = "0.1.1"
 description = "A simple cli for interacting with linear"
 authors = ["scar3crow <rss.holmes@gmail.com>"]
 readme = "README.md"
 packages = [{include = "src"}]
 
 [tool.poetry.dependencies]
 python = "3.8.10"
 typer = {extras = ["all"], version = "^0.9.0"}
 pyinquirer = "^1.0.3"
 rich = "^13.4.2"
 requests = "^2.31.0"
 textual = {extras = ["dev"], version = "^0.28.0"}
 python-dotenv = "^1.0.0"
+openai = "^0.27.8"
 
 [build-system]
 requires = ["poetry-core"]
 build-backend = "poetry.core.masonry.api"
```


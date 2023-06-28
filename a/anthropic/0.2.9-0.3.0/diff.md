# Comparing `tmp/anthropic-0.2.9.tar.gz` & `tmp/anthropic-0.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "anthropic-0.2.9.tar", last modified: Mon May 15 15:42:59 2023, max compression
+gzip compressed data, was "anthropic-0.3.0.tar", max compression
```

## Comparing `anthropic-0.2.9.tar` & `anthropic-0.3.0.tar`

### file list

```diff
@@ -1,19 +1,28 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 15:42:58.999925 anthropic-0.2.9/
--rw-r--r--   0 runner    (1001) docker     (123)     1055 2023-05-15 15:42:47.000000 anthropic-0.2.9/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1247 2023-05-15 15:42:58.999925 anthropic-0.2.9/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      676 2023-05-15 15:42:47.000000 anthropic-0.2.9/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 15:42:58.999925 anthropic-0.2.9/anthropic/
--rw-r--r--   0 runner    (1001) docker     (123)      162 2023-05-15 15:42:47.000000 anthropic-0.2.9/anthropic/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9259 2023-05-15 15:42:47.000000 anthropic-0.2.9/anthropic/api.py
--rw-r--r--   0 runner    (1001) docker     (123)      294 2023-05-15 15:42:47.000000 anthropic-0.2.9/anthropic/constants.py
--rw-r--r--   0 runner    (1001) docker     (123)     1817 2023-05-15 15:42:47.000000 anthropic-0.2.9/anthropic/tokenizer.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 15:42:58.999925 anthropic-0.2.9/anthropic.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1247 2023-05-15 15:42:58.000000 anthropic-0.2.9/anthropic.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      299 2023-05-15 15:42:58.000000 anthropic-0.2.9/anthropic.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-15 15:42:58.000000 anthropic-0.2.9/anthropic.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      108 2023-05-15 15:42:58.000000 anthropic-0.2.9/anthropic.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       10 2023-05-15 15:42:58.000000 anthropic-0.2.9/anthropic.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      962 2023-05-15 15:42:47.000000 anthropic-0.2.9/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-15 15:42:58.999925 anthropic-0.2.9/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 15:42:58.999925 anthropic-0.2.9/tests/
--rw-r--r--   0 runner    (1001) docker     (123)      861 2023-05-15 15:42:47.000000 anthropic-0.2.9/tests/test_api.py
+-rw-r--r--   0        0        0     1056 2023-06-26 21:50:36.624119 anthropic-0.3.0/LICENSE
+-rw-r--r--   0        0        0     9666 2023-06-28 15:42:21.543919 anthropic-0.3.0/README.md
+-rw-r--r--   0        0        0     1907 2023-06-26 21:50:36.627122 anthropic-0.3.0/pyproject.toml
+-rw-r--r--   0        0        0     1999 2023-06-26 21:50:36.627612 anthropic-0.3.0/src/anthropic/__init__.py
+-rw-r--r--   0        0        0    46809 2023-06-26 21:50:36.628016 anthropic-0.3.0/src/anthropic/_base_client.py
+-rw-r--r--   0        0        0     3889 2023-06-26 21:50:36.628324 anthropic-0.3.0/src/anthropic/_base_exceptions.py
+-rw-r--r--   0        0        0    15329 2023-06-26 21:50:36.628587 anthropic-0.3.0/src/anthropic/_client.py
+-rw-r--r--   0        0        0      112 2023-06-26 21:50:36.628774 anthropic-0.3.0/src/anthropic/_constants.py
+-rw-r--r--   0        0        0     1285 2023-06-26 21:50:36.628893 anthropic-0.3.0/src/anthropic/_exceptions.py
+-rw-r--r--   0        0        0     7343 2023-06-26 21:50:36.629012 anthropic-0.3.0/src/anthropic/_models.py
+-rw-r--r--   0        0        0     4846 2023-06-26 21:50:36.629146 anthropic-0.3.0/src/anthropic/_qs.py
+-rw-r--r--   0        0        0      896 2023-06-26 21:50:36.629271 anthropic-0.3.0/src/anthropic/_resource.py
+-rw-r--r--   0        0        0     7126 2023-06-26 21:50:36.629400 anthropic-0.3.0/src/anthropic/_streaming.py
+-rw-r--r--   0        0        0      879 2023-06-26 21:50:36.629515 anthropic-0.3.0/src/anthropic/_tokenizers.py
+-rw-r--r--   0        0        0     4230 2023-06-26 21:50:36.629650 anthropic-0.3.0/src/anthropic/_types.py
+-rw-r--r--   0        0        0     1277 2023-06-26 21:50:36.629824 anthropic-0.3.0/src/anthropic/_utils/__init__.py
+-rw-r--r--   0        0        0     6710 2023-06-26 21:50:36.629952 anthropic-0.3.0/src/anthropic/_utils/_transform.py
+-rw-r--r--   0        0        0     9411 2023-06-26 21:50:36.630107 anthropic-0.3.0/src/anthropic/_utils/_utils.py
+-rw-r--r--   0        0        0      100 2023-06-26 21:50:36.630327 anthropic-0.3.0/src/anthropic/_version.py
+-rw-r--r--   0        0        0      168 2023-06-26 21:50:36.630485 anthropic-0.3.0/src/anthropic/pagination.py
+-rw-r--r--   0        0        0        0 2023-06-26 21:50:36.630566 anthropic-0.3.0/src/anthropic/py.typed
+-rw-r--r--   0        0        0      156 2023-06-26 21:50:36.630819 anthropic-0.3.0/src/anthropic/resources/__init__.py
+-rw-r--r--   0        0        0    33262 2023-06-26 21:50:36.631074 anthropic-0.3.0/src/anthropic/resources/completions.py
+-rw-r--r--   0        0        0  1774213 2023-06-26 21:50:36.640575 anthropic-0.3.0/src/anthropic/tokenizer.json
+-rw-r--r--   0        0        0      226 2023-06-26 21:50:36.640828 anthropic-0.3.0/src/anthropic/types/__init__.py
+-rw-r--r--   0        0        0      664 2023-06-26 21:50:36.640952 anthropic-0.3.0/src/anthropic/types/completion.py
+-rw-r--r--   0        0        0    12185 2023-06-26 21:50:36.641096 anthropic-0.3.0/src/anthropic/types/completion_create_params.py
+-rw-r--r--   0        0        0    10600 1970-01-01 00:00:00.000000 anthropic-0.3.0/PKG-INFO
```

### Comparing `anthropic-0.2.9/LICENSE` & `anthropic-0.3.0/LICENSE`

 * *Files 11% similar despite different names*

```diff
@@ -1,7 +1,8 @@
-Copyright 2022 Anthropic, PBC.
+Copyright 2023 Anthropic, PBC.
 
 Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
 
 The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
 
 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
+
```


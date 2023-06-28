# Comparing `tmp/corporate_reputation-0.1.0.tar.gz` & `tmp/corporate_reputation-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "corporate_reputation-0.1.0.tar", max compression
+gzip compressed data, was "corporate_reputation-0.1.1.tar", max compression
```

## Comparing `corporate_reputation-0.1.0.tar` & `corporate_reputation-0.1.1.tar`

### file list

```diff
@@ -1,9 +1,46 @@
--rw-r--r--   0        0        0     1071 2023-06-07 05:38:07.371109 corporate_reputation-0.1.0/LICENSE
--rw-r--r--   0        0        0     3684 2023-06-07 05:38:07.371109 corporate_reputation-0.1.0/README.md
--rw-r--r--   0        0        0     3014 2023-06-07 05:38:21.239310 corporate_reputation-0.1.0/pyproject.toml
--rw-r--r--   0        0        0      319 2023-06-07 05:38:07.371109 corporate_reputation-0.1.0/src/corprep/__cli__.py
--rw-r--r--   0        0        0      135 2023-06-07 05:38:07.371109 corporate_reputation-0.1.0/src/corprep/__init__.py
--rw-r--r--   0        0        0       22 2023-06-07 05:38:21.187309 corporate_reputation-0.1.0/src/corprep/_version.py
--rw-r--r--   0        0        0      338 2023-06-07 05:38:21.187309 corporate_reputation-0.1.0/src/corprep/conf/about/__init__.yaml
--rw-r--r--   0        0        0        0 2023-06-07 05:38:07.371109 corporate_reputation-0.1.0/src/corprep/py.typed
--rw-r--r--   0        0        0     4392 1970-01-01 00:00:00.000000 corporate_reputation-0.1.0/PKG-INFO
+-rw-r--r--   0        0        0     1071 2023-06-28 04:25:54.597139 corporate_reputation-0.1.1/LICENSE
+-rw-r--r--   0        0        0     3914 2023-06-28 04:25:54.597139 corporate_reputation-0.1.1/README.md
+-rw-r--r--   0        0        0     3031 2023-06-28 04:26:19.373581 corporate_reputation-0.1.1/pyproject.toml
+-rw-r--r--   0        0        0      288 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/__cli__.py
+-rw-r--r--   0        0        0      379 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/__init__.py
+-rw-r--r--   0        0        0       22 2023-06-28 04:26:19.317580 corporate_reputation-0.1.1/src/corprep/_version.py
+-rw-r--r--   0        0        0        0 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/__init__.py
+-rw-r--r--   0        0        0      338 2023-06-28 04:26:19.321580 corporate_reputation-0.1.1/src/corprep/conf/about/__init__.yaml
+-rw-r--r--   0        0        0      435 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/batch/__init__.yaml
+-rw-r--r--   0        0        0        0 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/cmd/__init__.yaml
+-rw-r--r--   0        0        0       49 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/cmd/about.yaml
+-rw-r--r--   0        0        0      155 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/cmd/copy_conf.yaml
+-rw-r--r--   0        0        0       83 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/cmd/run_task.yaml
+-rw-r--r--   0        0        0       91 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/cmd/run_workflow.yaml
+-rw-r--r--   0        0        0      320 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/config.yaml
+-rw-r--r--   0        0        0      569 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/copier/conf.yaml
+-rw-r--r--   0        0        0      709 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/dotenv/__init__.yaml
+-rw-r--r--   0        0        0      319 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/hconf.yaml
+-rw-r--r--   0        0        0     1128 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/hydra/help/help.yaml
+-rw-r--r--   0        0        0      264 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/hydra/job_logging/custom.yaml
+-rw-r--r--   0        0        0      291 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/joblib/__init__.yaml
+-rw-r--r--   0        0        0      217 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/mode/__debug__.yaml
+-rw-r--r--   0        0        0      921 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/mode/__init__.yaml
+-rw-r--r--   0        0        0       61 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/module/__init__.yaml
+-rw-r--r--   0        0        0       96 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/path/__batch__.yaml
+-rw-r--r--   0        0        0     1719 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/path/__init__.yaml
+-rw-r--r--   0        0        0      412 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/path/__task__.yaml
+-rw-r--r--   0        0        0       76 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/pipe/__dataframe__.yaml
+-rw-r--r--   0        0        0       72 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/pipe/__dataframe_external_funcs__.yaml
+-rw-r--r--   0        0        0       74 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/pipe/__dataframe_instance_methods__.yaml
+-rw-r--r--   0        0        0      119 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/pipe/__init__.yaml
+-rw-r--r--   0        0        0      237 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/pipe/load_dataframes.yaml
+-rw-r--r--   0        0        0      242 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/pipe/save_dataframes.yaml
+-rw-r--r--   0        0        0       92 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/pipe/test_preprocessing.yaml
+-rw-r--r--   0        0        0       19 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/pipeline/__init__.yaml
+-rw-r--r--   0        0        0      388 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/pipeline/__test__.yaml
+-rw-r--r--   0        0        0      742 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/project/__init__.yaml
+-rw-r--r--   0        0        0      168 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/project/__test__.yaml
+-rw-r--r--   0        0        0       36 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/running/__init__.yaml
+-rw-r--r--   0        0        0      176 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/task/__batch__.yaml
+-rw-r--r--   0        0        0      319 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/task/__init__.yaml
+-rw-r--r--   0        0        0      311 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/task/__test__.yaml
+-rw-r--r--   0        0        0       97 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/workflow/__init__.yaml
+-rw-r--r--   0        0        0       97 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/conf/workflow/__test__.yaml
+-rw-r--r--   0        0        0        0 2023-06-28 04:25:54.601139 corporate_reputation-0.1.1/src/corprep/py.typed
+-rw-r--r--   0        0        0     4661 1970-01-01 00:00:00.000000 corporate_reputation-0.1.1/PKG-INFO
```

### Comparing `corporate_reputation-0.1.0/LICENSE` & `corporate_reputation-0.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `corporate_reputation-0.1.0/README.md` & `corporate_reputation-0.1.1/README.md`

 * *Files 11% similar despite different names*

```diff
@@ -1,16 +1,19 @@
 # Reputation Analysis of Companies and CEOs
 
 [![pypi-image]][pypi-url]
 [![version-image]][release-url]
 [![release-date-image]][release-url]
 [![license-image]][license-url]
+[![codecov][codecov-image]][codecov-url]
 [![jupyter-book-image]][docs-url]
 
 <!-- Links: -->
+[codecov-image]: https://codecov.io/gh/entelecheia/corporate-reputation/branch/main/graph/badge.svg?token=[REPLACE_ME]
+[codecov-url]: https://codecov.io/gh/entelecheia/corporate-reputation
 [pypi-image]: https://img.shields.io/pypi/v/corporate-reputation
 [license-image]: https://img.shields.io/github/license/entelecheia/corporate-reputation
 [license-url]: https://github.com/entelecheia/corporate-reputation/blob/main/LICENSE
 [version-image]: https://img.shields.io/github/v/release/entelecheia/corporate-reputation?sort=semver
 [release-date-image]: https://img.shields.io/github/release-date/entelecheia/corporate-reputation
 [release-url]: https://github.com/entelecheia/corporate-reputation/releases
 [jupyter-book-image]: https://jupyterbook.org/en/stable/_images/badge.svg
```

### Comparing `corporate_reputation-0.1.0/pyproject.toml` & `corporate_reputation-0.1.1/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,23 +1,24 @@
 [tool.poetry]
 name = "corporate-reputation"
-version = "0.1.0"
+version = "0.1.1"
 description = "Unraveling Corporate and CEO Reputation using Aspect-Based Sentiment Analysis and Signal Modeling"
 authors = ["Young Joon Lee <entelecheia@hotmail.com>"]
 license = "MIT"
 homepage = "https://entelecheia.github.io/corporate-reputation"
 repository = "https://github.com/entelecheia/corporate-reputation"
 readme = "README.md"
 packages = [{ include = "corprep", from = "src" }]
 
 [tool.poetry.scripts]
 corprep = 'corprep.__cli__:main'
 
 [tool.poetry.dependencies]
 python = ">=3.8.1,<3.12"
+hyfi = "^0.15.0"
 
 [tool.poetry.group.dev]
 optional = true
 
 [tool.poetry.group.dev.dependencies]
 python-semantic-release = "^7.33.1"
 isort = "^5.12.0"
```

### Comparing `corporate_reputation-0.1.0/PKG-INFO` & `corporate_reputation-0.1.1/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,33 +1,37 @@
 Metadata-Version: 2.1
 Name: corporate-reputation
-Version: 0.1.0
+Version: 0.1.1
 Summary: Unraveling Corporate and CEO Reputation using Aspect-Based Sentiment Analysis and Signal Modeling
 Home-page: https://entelecheia.github.io/corporate-reputation
 License: MIT
 Author: Young Joon Lee
 Author-email: entelecheia@hotmail.com
 Requires-Python: >=3.8.1,<3.12
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
+Requires-Dist: hyfi (>=0.15.0,<0.16.0)
 Project-URL: Repository, https://github.com/entelecheia/corporate-reputation
 Description-Content-Type: text/markdown
 
 # Reputation Analysis of Companies and CEOs
 
 [![pypi-image]][pypi-url]
 [![version-image]][release-url]
 [![release-date-image]][release-url]
 [![license-image]][license-url]
+[![codecov][codecov-image]][codecov-url]
 [![jupyter-book-image]][docs-url]
 
 <!-- Links: -->
+[codecov-image]: https://codecov.io/gh/entelecheia/corporate-reputation/branch/main/graph/badge.svg?token=[REPLACE_ME]
+[codecov-url]: https://codecov.io/gh/entelecheia/corporate-reputation
 [pypi-image]: https://img.shields.io/pypi/v/corporate-reputation
 [license-image]: https://img.shields.io/github/license/entelecheia/corporate-reputation
 [license-url]: https://github.com/entelecheia/corporate-reputation/blob/main/LICENSE
 [version-image]: https://img.shields.io/github/v/release/entelecheia/corporate-reputation?sort=semver
 [release-date-image]: https://img.shields.io/github/release-date/entelecheia/corporate-reputation
 [release-url]: https://github.com/entelecheia/corporate-reputation/releases
 [jupyter-book-image]: https://jupyterbook.org/en/stable/_images/badge.svg
```


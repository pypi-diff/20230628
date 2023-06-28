# Comparing `tmp/rvtools-0.1.1.tar.gz` & `tmp/rvtools-0.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "rvtools-0.1.1.tar", max compression
+gzip compressed data, was "rvtools-0.1.2.tar", max compression
```

## Comparing `rvtools-0.1.1.tar` & `rvtools-0.1.2.tar`

### file list

```diff
@@ -1,31 +1,31 @@
--rw-r--r--   0        0        0     4152 2023-06-26 22:59:09.399091 rvtools-0.1.1/README.md
--rw-r--r--   0        0        0      852 2023-06-26 23:19:50.728717 rvtools-0.1.1/pyproject.toml
--rw-r--r--   0        0        0      264 2023-06-26 22:42:35.971751 rvtools-0.1.1/rvtools/__init__.py
--rw-r--r--   0        0        0      172 2023-06-26 22:48:01.905065 rvtools-0.1.1/rvtools/construct/__init__.py
--rw-r--r--   0        0        0      439 2023-06-26 22:48:02.435189 rvtools-0.1.1/rvtools/construct/__pycache__/__init__.cpython-311.pyc
--rw-r--r--   0        0        0     2573 2023-06-25 22:21:36.090266 rvtools-0.1.1/rvtools/construct/__pycache__/_helpers.cpython-311.pyc
--rw-r--r--   0        0        0     2768 2023-06-26 22:48:02.435671 rvtools-0.1.1/rvtools/construct/__pycache__/beta.cpython-311.pyc
--rw-r--r--   0        0        0     3798 2023-06-26 22:48:02.436259 rvtools-0.1.1/rvtools/construct/__pycache__/lognorm.cpython-311.pyc
--rw-r--r--   0        0        0     2764 2023-06-26 22:48:02.436685 rvtools-0.1.1/rvtools/construct/__pycache__/norm.cpython-311.pyc
--rw-r--r--   0        0        0     2641 2023-06-26 22:48:02.437087 rvtools-0.1.1/rvtools/construct/__pycache__/uniform.cpython-311.pyc
--rw-r--r--   0        0        0     1535 2023-06-25 22:20:41.612198 rvtools-0.1.1/rvtools/construct/_helpers.py
--rw-r--r--   0        0        0     1477 2023-06-26 22:48:01.909872 rvtools-0.1.1/rvtools/construct/beta.py
--rw-r--r--   0        0        0     2127 2023-06-26 22:48:01.906834 rvtools-0.1.1/rvtools/construct/lognorm.py
--rw-r--r--   0        0        0     1258 2023-06-26 22:48:01.911084 rvtools-0.1.1/rvtools/construct/norm.py
--rw-r--r--   0        0        0     1437 2023-06-26 22:48:01.914585 rvtools-0.1.1/rvtools/construct/uniform.py
--rw-r--r--   0        0        0      126 2023-06-26 20:21:17.331337 rvtools-0.1.1/rvtools/distributions/__init__.py
--rw-r--r--   0        0        0      358 2023-06-26 20:21:36.589514 rvtools-0.1.1/rvtools/distributions/__pycache__/__init__.cpython-311.pyc
--rw-r--r--   0        0        0     1726 2023-06-26 18:36:15.269055 rvtools-0.1.1/rvtools/distributions/__pycache__/certainty.cpython-311.pyc
--rw-r--r--   0        0        0     8408 2023-06-26 20:16:33.256135 rvtools-0.1.1/rvtools/distributions/__pycache__/tp_uniform.cpython-311.pyc
--rw-r--r--   0        0        0      854 2023-06-26 18:23:58.213480 rvtools-0.1.1/rvtools/distributions/certainty.py
--rw-r--r--   0        0        0     5151 2023-06-26 20:16:32.712477 rvtools-0.1.1/rvtools/distributions/tp_uniform.py
--rw-r--r--   0        0        0      556 2023-06-26 21:58:51.980313 rvtools-0.1.1/rvtools/types.py
--rw-r--r--   0        0        0        0 2023-06-25 18:12:13.995575 rvtools-0.1.1/tests/__init__.py
--rw-r--r--   0        0        0      507 2023-06-26 20:21:17.339335 rvtools-0.1.1/tests/conftest.py
--rw-r--r--   0        0        0      339 2023-06-25 21:11:58.259220 rvtools-0.1.1/tests/test_certainty.py
--rw-r--r--   0        0        0     5084 2023-06-26 22:48:01.916512 rvtools-0.1.1/tests/test_constructors.py
--rw-r--r--   0        0        0      274 2023-06-25 23:03:01.270501 rvtools-0.1.1/tests/test_docs_do_not_raise.py
--rw-r--r--   0        0        0     2159 2023-06-26 22:48:01.912458 rvtools-0.1.1/tests/test_parse_spec.py
--rw-r--r--   0        0        0     4264 2023-06-26 22:48:01.908527 rvtools-0.1.1/tests/test_tp_uniform.py
--rw-r--r--   0        0        0      513 2023-06-26 21:58:51.980481 rvtools-0.1.1/tests/test_types.py
--rw-r--r--   0        0        0     4801 1970-01-01 00:00:00.000000 rvtools-0.1.1/PKG-INFO
+-rw-r--r--   0        0        0     4152 2023-06-26 22:59:09.399091 rvtools-0.1.2/README.md
+-rw-r--r--   0        0        0      852 2023-06-28 11:05:40.707093 rvtools-0.1.2/pyproject.toml
+-rw-r--r--   0        0        0      264 2023-06-26 22:42:35.971751 rvtools-0.1.2/rvtools/__init__.py
+-rw-r--r--   0        0        0      172 2023-06-26 22:48:01.905065 rvtools-0.1.2/rvtools/construct/__init__.py
+-rw-r--r--   0        0        0      439 2023-06-26 22:48:02.435189 rvtools-0.1.2/rvtools/construct/__pycache__/__init__.cpython-311.pyc
+-rw-r--r--   0        0        0     2573 2023-06-25 22:21:36.090266 rvtools-0.1.2/rvtools/construct/__pycache__/_helpers.cpython-311.pyc
+-rw-r--r--   0        0        0     2768 2023-06-26 22:48:02.435671 rvtools-0.1.2/rvtools/construct/__pycache__/beta.cpython-311.pyc
+-rw-r--r--   0        0        0     3798 2023-06-26 22:48:02.436259 rvtools-0.1.2/rvtools/construct/__pycache__/lognorm.cpython-311.pyc
+-rw-r--r--   0        0        0     2764 2023-06-26 22:48:02.436685 rvtools-0.1.2/rvtools/construct/__pycache__/norm.cpython-311.pyc
+-rw-r--r--   0        0        0     2641 2023-06-26 22:48:02.437087 rvtools-0.1.2/rvtools/construct/__pycache__/uniform.cpython-311.pyc
+-rw-r--r--   0        0        0     1535 2023-06-25 22:20:41.612198 rvtools-0.1.2/rvtools/construct/_helpers.py
+-rw-r--r--   0        0        0     1477 2023-06-26 22:48:01.909872 rvtools-0.1.2/rvtools/construct/beta.py
+-rw-r--r--   0        0        0     2127 2023-06-26 22:48:01.906834 rvtools-0.1.2/rvtools/construct/lognorm.py
+-rw-r--r--   0        0        0     1258 2023-06-26 22:48:01.911084 rvtools-0.1.2/rvtools/construct/norm.py
+-rw-r--r--   0        0        0     1437 2023-06-26 22:48:01.914585 rvtools-0.1.2/rvtools/construct/uniform.py
+-rw-r--r--   0        0        0      126 2023-06-26 20:21:17.331337 rvtools-0.1.2/rvtools/distributions/__init__.py
+-rw-r--r--   0        0        0      358 2023-06-26 20:21:36.589514 rvtools-0.1.2/rvtools/distributions/__pycache__/__init__.cpython-311.pyc
+-rw-r--r--   0        0        0     1726 2023-06-26 18:36:15.269055 rvtools-0.1.2/rvtools/distributions/__pycache__/certainty.cpython-311.pyc
+-rw-r--r--   0        0        0     8408 2023-06-26 20:16:33.256135 rvtools-0.1.2/rvtools/distributions/__pycache__/tp_uniform.cpython-311.pyc
+-rw-r--r--   0        0        0      854 2023-06-26 18:23:58.213480 rvtools-0.1.2/rvtools/distributions/certainty.py
+-rw-r--r--   0        0        0     5151 2023-06-26 20:16:32.712477 rvtools-0.1.2/rvtools/distributions/tp_uniform.py
+-rw-r--r--   0        0        0      556 2023-06-26 21:58:51.980313 rvtools-0.1.2/rvtools/types.py
+-rw-r--r--   0        0        0        0 2023-06-25 18:12:13.995575 rvtools-0.1.2/tests/__init__.py
+-rw-r--r--   0        0        0      507 2023-06-26 20:21:17.339335 rvtools-0.1.2/tests/conftest.py
+-rw-r--r--   0        0        0      339 2023-06-25 21:11:58.259220 rvtools-0.1.2/tests/test_certainty.py
+-rw-r--r--   0        0        0     5084 2023-06-26 22:48:01.916512 rvtools-0.1.2/tests/test_constructors.py
+-rw-r--r--   0        0        0      274 2023-06-25 23:03:01.270501 rvtools-0.1.2/tests/test_docs_do_not_raise.py
+-rw-r--r--   0        0        0     2159 2023-06-26 22:48:01.912458 rvtools-0.1.2/tests/test_parse_spec.py
+-rw-r--r--   0        0        0     4264 2023-06-26 22:48:01.908527 rvtools-0.1.2/tests/test_tp_uniform.py
+-rw-r--r--   0        0        0      513 2023-06-26 21:58:51.980481 rvtools-0.1.2/tests/test_types.py
+-rw-r--r--   0        0        0     4751 1970-01-01 00:00:00.000000 rvtools-0.1.2/PKG-INFO
```

### Comparing `rvtools-0.1.1/README.md` & `rvtools-0.1.2/README.md`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/pyproject.toml` & `rvtools-0.1.2/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,26 +1,26 @@
 [tool]
 [tool.poetry]
 name = "rvtools"
-version = "0.1.1"
+version = "0.1.2"
 homepage = "https://github.com/tadamcz/rvtools"
 description = "Top-level package for Probability distribution and random variable tools."
 authors = ["Tom Adamczewski <tadamczewskipublic@gmail.com>"]
 readme = "README.md"
 classifiers=[
     'Natural Language :: English',
     'Programming Language :: Python :: 3',
 ]
 packages = [
     { include = "rvtools" },
     { include = "tests", format = "sdist" },
 ]
 
 [tool.poetry.dependencies]
-python = ">=3.8,<3.12"
+python = ">=3.9,<3.13"
 betapert = "^0.1.2"
 
 [tool.poetry.group.dev.dependencies]
 bump2version = "*"
 coverage = "*"
 pytest = ">=7.2.0"
 pytest-pycharm = "*"
```

### Comparing `rvtools-0.1.1/rvtools/construct/__pycache__/_helpers.cpython-311.pyc` & `rvtools-0.1.2/rvtools/construct/__pycache__/_helpers.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/rvtools/construct/__pycache__/beta.cpython-311.pyc` & `rvtools-0.1.2/rvtools/construct/__pycache__/beta.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/rvtools/construct/__pycache__/lognorm.cpython-311.pyc` & `rvtools-0.1.2/rvtools/construct/__pycache__/lognorm.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/rvtools/construct/__pycache__/norm.cpython-311.pyc` & `rvtools-0.1.2/rvtools/construct/__pycache__/norm.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/rvtools/construct/__pycache__/uniform.cpython-311.pyc` & `rvtools-0.1.2/rvtools/construct/__pycache__/uniform.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/rvtools/construct/_helpers.py` & `rvtools-0.1.2/rvtools/construct/_helpers.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/rvtools/construct/beta.py` & `rvtools-0.1.2/rvtools/construct/beta.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/rvtools/construct/lognorm.py` & `rvtools-0.1.2/rvtools/construct/lognorm.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/rvtools/construct/norm.py` & `rvtools-0.1.2/rvtools/construct/norm.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/rvtools/construct/uniform.py` & `rvtools-0.1.2/rvtools/construct/uniform.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/rvtools/distributions/__pycache__/certainty.cpython-311.pyc` & `rvtools-0.1.2/rvtools/distributions/__pycache__/certainty.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/rvtools/distributions/__pycache__/tp_uniform.cpython-311.pyc` & `rvtools-0.1.2/rvtools/distributions/__pycache__/tp_uniform.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/rvtools/distributions/certainty.py` & `rvtools-0.1.2/rvtools/distributions/certainty.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/rvtools/distributions/tp_uniform.py` & `rvtools-0.1.2/rvtools/distributions/tp_uniform.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/rvtools/types.py` & `rvtools-0.1.2/rvtools/types.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/tests/test_constructors.py` & `rvtools-0.1.2/tests/test_constructors.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/tests/test_parse_spec.py` & `rvtools-0.1.2/tests/test_parse_spec.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/tests/test_tp_uniform.py` & `rvtools-0.1.2/tests/test_tp_uniform.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/tests/test_types.py` & `rvtools-0.1.2/tests/test_types.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.1/PKG-INFO` & `rvtools-0.1.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,18 +1,17 @@
 Metadata-Version: 2.1
 Name: rvtools
-Version: 0.1.1
+Version: 0.1.2
 Summary: Top-level package for Probability distribution and random variable tools.
 Home-page: https://github.com/tadamcz/rvtools
 Author: Tom Adamczewski
 Author-email: tadamczewskipublic@gmail.com
-Requires-Python: >=3.8,<3.12
+Requires-Python: >=3.9,<3.13
 Classifier: Natural Language :: English
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Requires-Dist: betapert (>=0.1.2,<0.2.0)
 Description-Content-Type: text/markdown
 
 A collection of tools for conveniently working with SciPy probability distributions.
```


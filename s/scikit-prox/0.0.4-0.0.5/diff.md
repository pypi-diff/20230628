# Comparing `tmp/scikit_prox-0.0.4.tar.gz` & `tmp/scikit_prox-0.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "scikit_prox-0.0.4.tar", max compression
+gzip compressed data, was "scikit_prox-0.0.5.tar", max compression
```

## Comparing `scikit_prox-0.0.4.tar` & `scikit_prox-0.0.5.tar`

### file list

```diff
@@ -1,14 +1,14 @@
--rw-r--r--   0        0        0     1085 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/LICENSE.md
--rw-r--r--   0        0        0     3724 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/README.md
--rw-r--r--   0        0        0      643 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/pyproject.toml
--rw-r--r--   0        0        0        0 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/__init__.py
--rw-r--r--   0        0        0     1844 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/_pgd.py
--rw-r--r--   0        0        0     1593 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/_proximal_operators.py
--rw-r--r--   0        0        0      104 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/operators/__init__.py
--rw-r--r--   0        0        0     2769 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/operators/_composite.py
--rw-r--r--   0        0        0      158 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/operators/_dummy.py
--rw-r--r--   0        0        0     1492 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/operators/_tv.py
--rw-r--r--   0        0        0     9531 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/operators/_tvl1.py
--rw-r--r--   0        0        0        0 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/test/__init__.py
--rw-r--r--   0        0        0       51 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/test/test_package.py
--rw-r--r--   0        0        0     4465 1970-01-01 00:00:00.000000 scikit_prox-0.0.4/PKG-INFO
+-rw-r--r--   0        0        0     1085 2023-06-28 13:50:54.026264 scikit_prox-0.0.5/LICENSE.md
+-rw-r--r--   0        0        0     3724 2023-06-28 13:50:54.026264 scikit_prox-0.0.5/README.md
+-rw-r--r--   0        0        0      662 2023-06-28 13:50:54.026264 scikit_prox-0.0.5/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-28 13:50:54.026264 scikit_prox-0.0.5/skprox/__init__.py
+-rw-r--r--   0        0        0     1844 2023-06-28 13:50:54.026264 scikit_prox-0.0.5/skprox/_pgd.py
+-rw-r--r--   0        0        0     1561 2023-06-28 13:50:54.026264 scikit_prox-0.0.5/skprox/_proximal_operators.py
+-rw-r--r--   0        0        0      104 2023-06-28 13:50:54.026264 scikit_prox-0.0.5/skprox/operators/__init__.py
+-rw-r--r--   0        0        0     2769 2023-06-28 13:50:54.026264 scikit_prox-0.0.5/skprox/operators/_composite.py
+-rw-r--r--   0        0        0      158 2023-06-28 13:50:54.026264 scikit_prox-0.0.5/skprox/operators/_dummy.py
+-rw-r--r--   0        0        0     1492 2023-06-28 13:50:54.026264 scikit_prox-0.0.5/skprox/operators/_tv.py
+-rw-r--r--   0        0        0     9531 2023-06-28 13:50:54.026264 scikit_prox-0.0.5/skprox/operators/_tvl1.py
+-rw-r--r--   0        0        0        0 2023-06-28 13:50:54.026264 scikit_prox-0.0.5/skprox/test/__init__.py
+-rw-r--r--   0        0        0       51 2023-06-28 13:50:54.026264 scikit_prox-0.0.5/skprox/test/test_package.py
+-rw-r--r--   0        0        0     4505 1970-01-01 00:00:00.000000 scikit_prox-0.0.5/PKG-INFO
```

### Comparing `scikit_prox-0.0.4/LICENSE.md` & `scikit_prox-0.0.5/LICENSE.md`

 * *Files identical despite different names*

### Comparing `scikit_prox-0.0.4/README.md` & `scikit_prox-0.0.5/README.md`

 * *Files identical despite different names*

### Comparing `scikit_prox-0.0.4/pyproject.toml` & `scikit_prox-0.0.5/pyproject.toml`

 * *Files 10% similar despite different names*

```diff
@@ -1,22 +1,23 @@
 [tool.poetry]
 name = "scikit-prox"
-version = "0.0.4"
+version = "0.0.5"
 description = "A package for solving regularised optimisation problems in a scikit-learn style."
 authors = ["jameschapman19 <james.chapman.19@ucl.ac.uk>"]
 readme = "README.md"
 packages = [{include = "skprox"}]
 
 [tool.poetry.dependencies]
 python = "^3.8"
 scikit-learn = "^1.2.1"
 scikit-image = "^0.19.3"
 pyproximal = "^0.5.0"
 pytest = "^7.2.1"
 numpy = "^1.8.1"
+nilearn = "^0.8.1"
 
 [tool.poetry.dev-dependencies]
 black = "^22.12.0"
 flake8 = "^4.0.1"
 isort = "^5.10.1"
 mypy = "^0.910"
 pylint = "^2.12.2"
```

### Comparing `scikit_prox-0.0.4/skprox/_pgd.py` & `scikit_prox-0.0.5/skprox/_pgd.py`

 * *Files identical despite different names*

### Comparing `scikit_prox-0.0.4/skprox/_proximal_operators.py` & `scikit_prox-0.0.5/skprox/_proximal_operators.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,9 +1,7 @@
-from abc import abstractmethod
-
 from pyproximal import (
     L0,
     L0Ball,
     L1,
     L1Ball,
     L2,
     L21,
```

### Comparing `scikit_prox-0.0.4/skprox/operators/_composite.py` & `scikit_prox-0.0.5/skprox/operators/_composite.py`

 * *Files identical despite different names*

### Comparing `scikit_prox-0.0.4/skprox/operators/_tv.py` & `scikit_prox-0.0.5/skprox/operators/_tv.py`

 * *Files identical despite different names*

### Comparing `scikit_prox-0.0.4/skprox/operators/_tvl1.py` & `scikit_prox-0.0.5/skprox/operators/_tvl1.py`

 * *Files identical despite different names*

### Comparing `scikit_prox-0.0.4/PKG-INFO` & `scikit_prox-0.0.5/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,19 +1,20 @@
 Metadata-Version: 2.1
 Name: scikit-prox
-Version: 0.0.4
+Version: 0.0.5
 Summary: A package for solving regularised optimisation problems in a scikit-learn style.
 Author: jameschapman19
 Author-email: james.chapman.19@ucl.ac.uk
 Requires-Python: >=3.8,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
+Requires-Dist: nilearn (>=0.8.1,<0.9.0)
 Requires-Dist: numpy (>=1.8.1,<2.0.0)
 Requires-Dist: pyproximal (>=0.5.0,<0.6.0)
 Requires-Dist: pytest (>=7.2.1,<8.0.0)
 Requires-Dist: scikit-image (>=0.19.3,<0.20.0)
 Requires-Dist: scikit-learn (>=1.2.1,<2.0.0)
 Description-Content-Type: text/markdown
```


# Comparing `tmp/jaxdf-0.2.5.tar.gz` & `tmp/jaxdf-0.2.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "jaxdf-0.2.5.tar", max compression
+gzip compressed data, was "jaxdf-0.2.6.tar", max compression
```

## Comparing `jaxdf-0.2.5.tar` & `jaxdf-0.2.6.tar`

### file list

```diff
@@ -1,18 +1,18 @@
--rw-r--r--   0        0        0     7652 2023-06-23 12:29:53.472909 jaxdf-0.2.5/LICENSE
--rw-r--r--   0        0        0     5669 2023-06-23 12:29:53.472909 jaxdf-0.2.5/README.md
--rwxr-xr-x   0        0        0       19 2023-06-23 12:29:53.496909 jaxdf-0.2.5/jaxdf/__about__.py
--rw-r--r--   0        0        0      316 2023-06-23 12:29:53.496909 jaxdf-0.2.5/jaxdf/__init__.py
--rwxr-xr-x   0        0        0     5318 2023-06-23 12:29:53.496909 jaxdf-0.2.5/jaxdf/conv.py
--rw-r--r--   0        0        0    11860 2023-06-23 12:29:53.496909 jaxdf-0.2.5/jaxdf/core.py
--rw-r--r--   0        0        0    13240 2023-06-23 12:29:53.496909 jaxdf-0.2.5/jaxdf/discretization.py
--rw-r--r--   0        0        0      953 2023-06-23 12:29:53.496909 jaxdf-0.2.5/jaxdf/exceptions.py
--rw-r--r--   0        0        0     5283 2023-06-23 12:29:53.496909 jaxdf-0.2.5/jaxdf/geometry.py
--rw-r--r--   0        0        0      155 2023-06-23 12:29:53.496909 jaxdf-0.2.5/jaxdf/operators/__init__.py
--rw-r--r--   0        0        0    12765 2023-06-23 12:29:53.496909 jaxdf-0.2.5/jaxdf/operators/differential.py
--rw-r--r--   0        0        0     1060 2023-06-23 12:29:53.496909 jaxdf-0.2.5/jaxdf/operators/dummy.py
--rw-r--r--   0        0        0     6275 2023-06-23 12:29:53.496909 jaxdf-0.2.5/jaxdf/operators/functions.py
--rw-r--r--   0        0        0      327 2023-06-23 12:29:53.496909 jaxdf-0.2.5/jaxdf/operators/linear_algebra.py
--rw-r--r--   0        0        0     7493 2023-06-23 12:29:53.496909 jaxdf-0.2.5/jaxdf/operators/magic.py
--rw-r--r--   0        0        0     1329 2023-06-23 12:29:53.496909 jaxdf-0.2.5/jaxdf/util.py
--rw-r--r--   0        0        0     3021 2023-06-23 12:29:53.496909 jaxdf-0.2.5/pyproject.toml
--rw-r--r--   0        0        0     7513 1970-01-01 00:00:00.000000 jaxdf-0.2.5/PKG-INFO
+-rw-r--r--   0        0        0     7652 2023-06-28 12:19:52.977167 jaxdf-0.2.6/LICENSE
+-rw-r--r--   0        0        0     5733 2023-06-28 12:19:52.977167 jaxdf-0.2.6/README.md
+-rwxr-xr-x   0        0        0       19 2023-06-28 12:19:52.997168 jaxdf-0.2.6/jaxdf/__about__.py
+-rw-r--r--   0        0        0      316 2023-06-28 12:19:52.997168 jaxdf-0.2.6/jaxdf/__init__.py
+-rwxr-xr-x   0        0        0     5318 2023-06-28 12:19:52.997168 jaxdf-0.2.6/jaxdf/conv.py
+-rw-r--r--   0        0        0    11860 2023-06-28 12:19:52.997168 jaxdf-0.2.6/jaxdf/core.py
+-rw-r--r--   0        0        0    13240 2023-06-28 12:19:52.997168 jaxdf-0.2.6/jaxdf/discretization.py
+-rw-r--r--   0        0        0      953 2023-06-28 12:19:52.997168 jaxdf-0.2.6/jaxdf/exceptions.py
+-rw-r--r--   0        0        0     5283 2023-06-28 12:19:52.997168 jaxdf-0.2.6/jaxdf/geometry.py
+-rw-r--r--   0        0        0      155 2023-06-28 12:19:52.997168 jaxdf-0.2.6/jaxdf/operators/__init__.py
+-rw-r--r--   0        0        0    12765 2023-06-28 12:19:52.997168 jaxdf-0.2.6/jaxdf/operators/differential.py
+-rw-r--r--   0        0        0     1060 2023-06-28 12:19:52.997168 jaxdf-0.2.6/jaxdf/operators/dummy.py
+-rw-r--r--   0        0        0     6275 2023-06-28 12:19:52.997168 jaxdf-0.2.6/jaxdf/operators/functions.py
+-rw-r--r--   0        0        0      327 2023-06-28 12:19:52.997168 jaxdf-0.2.6/jaxdf/operators/linear_algebra.py
+-rw-r--r--   0        0        0     7493 2023-06-28 12:19:52.997168 jaxdf-0.2.6/jaxdf/operators/magic.py
+-rw-r--r--   0        0        0     1329 2023-06-28 12:19:52.997168 jaxdf-0.2.6/jaxdf/util.py
+-rw-r--r--   0        0        0     3002 2023-06-28 12:19:52.997168 jaxdf-0.2.6/pyproject.toml
+-rw-r--r--   0        0        0     7537 1970-01-01 00:00:00.000000 jaxdf-0.2.6/PKG-INFO
```

### Comparing `jaxdf-0.2.5/LICENSE` & `jaxdf-0.2.6/LICENSE`

 * *Files identical despite different names*

### Comparing `jaxdf-0.2.5/README.md` & `jaxdf-0.2.6/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 # jaxdf - JAX-based Discretization Framework
 
 [![Support](https://dcbadge.vercel.app/api/server/VtUb4fFznt?style=flat)](https://discord.gg/VtUb4fFznt)
 [![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)
 [![codecov](https://codecov.io/gh/ucl-bug/jaxdf/branch/main/graph/badge.svg?token=FIUYOCFDYL)](https://codecov.io/gh/ucl-bug/jaxdf)
-![Continous Integration](https://github.com/ucl-bug/jaxdf/actions/workflows/main.yml/badge.svg)
+[![CI](https://github.com/ucl-bug/jaxdf/actions/workflows/tests.yml/badge.svg)](https://github.com/ucl-bug/jaxdf/actions/workflows/tests.yml)
 
 [**Overview**](#overview)
 | [**Example**](#example)
 | [**Installation**](#installation)
 | [**Documentation**](https://ucl-bug.github.io/jaxdf/)
 | [**Support**](#support)
 
@@ -102,15 +102,15 @@
 
 <br/>
 
 ## Citation
 
 [![arXiv](https://img.shields.io/badge/arXiv-2111.05218-b31b1b.svg?style=flat)](https://arxiv.org/abs/2111.05218)
 
-This package will be presented at the [Differentiable Programming workshop](https://diffprogramming.mit.edu/) at NeurIPS 2021.
+An initial version of this package was presented at the [Differentiable Programming workshop](https://diffprogramming.mit.edu/) at NeurIPS 2021.
 
 ```bibtex
 @article{stanziola2021jaxdf,
     author={Stanziola, Antonio and Arridge, Simon and Cox, Ben T. and Treeby, Bradley E.},
     title={A research framework for writing differentiable PDE discretizations in JAX},
     year={2021},
     journal={Differentiable Programming workshop at Neural Information Processing Systems 2021}
```

### Comparing `jaxdf-0.2.5/jaxdf/conv.py` & `jaxdf-0.2.6/jaxdf/conv.py`

 * *Files identical despite different names*

### Comparing `jaxdf-0.2.5/jaxdf/core.py` & `jaxdf-0.2.6/jaxdf/core.py`

 * *Files identical despite different names*

### Comparing `jaxdf-0.2.5/jaxdf/discretization.py` & `jaxdf-0.2.6/jaxdf/discretization.py`

 * *Files identical despite different names*

### Comparing `jaxdf-0.2.5/jaxdf/exceptions.py` & `jaxdf-0.2.6/jaxdf/exceptions.py`

 * *Files identical despite different names*

### Comparing `jaxdf-0.2.5/jaxdf/geometry.py` & `jaxdf-0.2.6/jaxdf/geometry.py`

 * *Files identical despite different names*

### Comparing `jaxdf-0.2.5/jaxdf/operators/differential.py` & `jaxdf-0.2.6/jaxdf/operators/differential.py`

 * *Files identical despite different names*

### Comparing `jaxdf-0.2.5/jaxdf/operators/dummy.py` & `jaxdf-0.2.6/jaxdf/operators/dummy.py`

 * *Files identical despite different names*

### Comparing `jaxdf-0.2.5/jaxdf/operators/functions.py` & `jaxdf-0.2.6/jaxdf/operators/functions.py`

 * *Files identical despite different names*

### Comparing `jaxdf-0.2.5/jaxdf/operators/magic.py` & `jaxdf-0.2.6/jaxdf/operators/magic.py`

 * *Files identical despite different names*

### Comparing `jaxdf-0.2.5/jaxdf/util.py` & `jaxdf-0.2.6/jaxdf/util.py`

 * *Files identical despite different names*

### Comparing `jaxdf-0.2.5/pyproject.toml` & `jaxdf-0.2.6/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "jaxdf"
-version = "0.2.5"
+version = "0.2.6"
 description = "A JAX-based research framework for writing differentiable numerical simulators with arbitrary discretizations"
 authors = [
   "Antonio Stanziola <a.stanziola@ucl.ac.uk>",
   "Simon Arridge",
   "Ben T. Cox",
   "Bradley E. Treeby",
 ]
@@ -49,15 +49,14 @@
 "Bug Tracker" = "https://github.com/ucl-bug/jaxdf/issues"
 "Support" = "https://discord.gg/VtUb4fFznt"
 
 [tool.poetry.dependencies]
 python = "^3.9"
 plum-dispatch = "^1.6"
 jax = "^0.4.11"
-jaxlib = "^0.4.11"
 
 [tool.poetry.group.dev.dependencies]
 coverage = "^7.2.7"
 mypy = "^1.4.0"
 plumkdocs = "^0.0.2"
 pre-commit = "^3.3.3"
 mkdocs-material-extensions = "^1.0.3"
```

### Comparing `jaxdf-0.2.5/PKG-INFO` & `jaxdf-0.2.6/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jaxdf
-Version: 0.2.5
+Version: 0.2.6
 Summary: A JAX-based research framework for writing differentiable numerical simulators with arbitrary discretizations
 License: LGPL-3.0-only
 Keywords: jax,pde,discretization,differential equations,simulation,differentiable programming
 Author: Antonio Stanziola
 Author-email: a.stanziola@ucl.ac.uk
 Requires-Python: >=3.9,<4.0
 Classifier: Environment :: GPU
@@ -24,28 +24,27 @@
 Classifier: Topic :: Scientific/Engineering
 Classifier: Topic :: Scientific/Engineering :: Artificial Intelligence
 Classifier: Topic :: Scientific/Engineering :: Physics
 Classifier: Topic :: Software Development
 Classifier: Topic :: Software Development :: Libraries
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Requires-Dist: jax (>=0.4.11,<0.5.0)
-Requires-Dist: jaxlib (>=0.4.11,<0.5.0)
 Requires-Dist: plum-dispatch (>=1.6,<2.0)
 Project-URL: Bug Tracker, https://github.com/ucl-bug/jaxdf/issues
 Project-URL: Homepage, https://ucl-bug.github.io/jaxdf
 Project-URL: Repository, https://github.com/ucl-bug/jaxdf
 Project-URL: Support, https://discord.gg/VtUb4fFznt
 Description-Content-Type: text/markdown
 
 # jaxdf - JAX-based Discretization Framework
 
 [![Support](https://dcbadge.vercel.app/api/server/VtUb4fFznt?style=flat)](https://discord.gg/VtUb4fFznt)
 [![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)
 [![codecov](https://codecov.io/gh/ucl-bug/jaxdf/branch/main/graph/badge.svg?token=FIUYOCFDYL)](https://codecov.io/gh/ucl-bug/jaxdf)
-![Continous Integration](https://github.com/ucl-bug/jaxdf/actions/workflows/main.yml/badge.svg)
+[![CI](https://github.com/ucl-bug/jaxdf/actions/workflows/tests.yml/badge.svg)](https://github.com/ucl-bug/jaxdf/actions/workflows/tests.yml)
 
 [**Overview**](#overview)
 | [**Example**](#example)
 | [**Installation**](#installation)
 | [**Documentation**](https://ucl-bug.github.io/jaxdf/)
 | [**Support**](#support)
 
@@ -140,15 +139,15 @@
 
 <br/>
 
 ## Citation
 
 [![arXiv](https://img.shields.io/badge/arXiv-2111.05218-b31b1b.svg?style=flat)](https://arxiv.org/abs/2111.05218)
 
-This package will be presented at the [Differentiable Programming workshop](https://diffprogramming.mit.edu/) at NeurIPS 2021.
+An initial version of this package was presented at the [Differentiable Programming workshop](https://diffprogramming.mit.edu/) at NeurIPS 2021.
 
 ```bibtex
 @article{stanziola2021jaxdf,
     author={Stanziola, Antonio and Arridge, Simon and Cox, Ben T. and Treeby, Bradley E.},
     title={A research framework for writing differentiable PDE discretizations in JAX},
     year={2021},
     journal={Differentiable Programming workshop at Neural Information Processing Systems 2021}
```


# Comparing `tmp/scikit_prox-0.0.3.tar.gz` & `tmp/scikit_prox-0.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "scikit_prox-0.0.3.tar", max compression
+gzip compressed data, was "scikit_prox-0.0.4.tar", max compression
```

## Comparing `scikit_prox-0.0.3.tar` & `scikit_prox-0.0.4.tar`

### file list

```diff
@@ -1,12 +1,14 @@
--rw-r--r--   0        0        0     1085 2023-01-30 17:58:21.686407 scikit_prox-0.0.3/LICENSE.md
--rw-r--r--   0        0        0     3724 2023-01-30 17:58:21.686407 scikit_prox-0.0.3/README.md
--rw-r--r--   0        0        0      626 2023-01-30 17:58:21.686407 scikit_prox-0.0.3/pyproject.toml
--rw-r--r--   0        0        0        0 2023-01-30 17:58:21.686407 scikit_prox-0.0.3/skprox/__init__.py
--rw-r--r--   0        0        0      100 2023-01-30 17:58:21.686407 scikit_prox-0.0.3/skprox/linear_model/__init__.py
--rw-r--r--   0        0        0     6198 2023-01-30 17:58:21.686407 scikit_prox-0.0.3/skprox/linear_model/_base.py
--rw-r--r--   0        0        0     7222 2023-01-30 17:58:21.686407 scikit_prox-0.0.3/skprox/linear_model/_logistic.py
--rw-r--r--   0        0        0     3012 2023-01-30 17:58:21.686407 scikit_prox-0.0.3/skprox/proximal_operators.py
--rw-r--r--   0        0        0        0 2023-01-30 17:58:21.686407 scikit_prox-0.0.3/skprox/test/__init__.py
--rw-r--r--   0        0        0     2558 2023-01-30 17:58:21.686407 scikit_prox-0.0.3/skprox/test/test_logistic.py
--rw-r--r--   0        0        0     2547 2023-01-30 17:58:21.686407 scikit_prox-0.0.3/skprox/test/test_regression.py
--rw-r--r--   0        0        0     4427 1970-01-01 00:00:00.000000 scikit_prox-0.0.3/PKG-INFO
+-rw-r--r--   0        0        0     1085 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/LICENSE.md
+-rw-r--r--   0        0        0     3724 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/README.md
+-rw-r--r--   0        0        0      643 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/__init__.py
+-rw-r--r--   0        0        0     1844 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/_pgd.py
+-rw-r--r--   0        0        0     1593 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/_proximal_operators.py
+-rw-r--r--   0        0        0      104 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/operators/__init__.py
+-rw-r--r--   0        0        0     2769 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/operators/_composite.py
+-rw-r--r--   0        0        0      158 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/operators/_dummy.py
+-rw-r--r--   0        0        0     1492 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/operators/_tv.py
+-rw-r--r--   0        0        0     9531 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/operators/_tvl1.py
+-rw-r--r--   0        0        0        0 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/test/__init__.py
+-rw-r--r--   0        0        0       51 2023-06-28 13:32:06.382213 scikit_prox-0.0.4/skprox/test/test_package.py
+-rw-r--r--   0        0        0     4465 1970-01-01 00:00:00.000000 scikit_prox-0.0.4/PKG-INFO
```

### Comparing `scikit_prox-0.0.3/LICENSE.md` & `scikit_prox-0.0.4/LICENSE.md`

 * *Files identical despite different names*

### Comparing `scikit_prox-0.0.3/README.md` & `scikit_prox-0.0.4/README.md`

 * *Files identical despite different names*

### Comparing `scikit_prox-0.0.3/pyproject.toml` & `scikit_prox-0.0.4/pyproject.toml`

 * *Files 3% similar despite different names*

```diff
@@ -1,21 +1,22 @@
 [tool.poetry]
 name = "scikit-prox"
-version = "0.0.3"
+version = "0.0.4"
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
+numpy = "^1.8.1"
 
 [tool.poetry.dev-dependencies]
 black = "^22.12.0"
 flake8 = "^4.0.1"
 isort = "^5.10.1"
 mypy = "^0.910"
 pylint = "^2.12.2"
```

### Comparing `scikit_prox-0.0.3/skprox/proximal_operators.py` & `scikit_prox-0.0.4/skprox/_pgd.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,10 +1,9 @@
-from functools import partial
+from abc import abstractmethod
 
-import numpy as np
 from pyproximal import (
     L0,
     L0Ball,
     L1,
     L1Ball,
     L2,
     L21,
@@ -12,74 +11,16 @@
     Nuclear,
     NuclearBall,
     Log,
     Log1,
     Euclidean,
     EuclideanBall,
 )
-from pyproximal.ProxOperator import _check_tau
-from skimage.restoration import denoise_tv_chambolle, denoise_tv_bregman
-
-
-class Dummy:
-    def __init__(self, *args, **kwargs):
-        pass
-
-    def __call__(self, x):
-        return 0
-
-    def prox(self, x, tau):
-        return x
-
-
-class TV:
-    def __init__(self, sigma, dims, isotropic=True, max_iter=1000):
-        self.sigma = sigma
-        self.isotropic = isotropic
-        self.max_iter = max_iter
-        self.count = 0
-        self.dims = dims
-
-    def _increment_count(func):
-        """Increment counter"""
-
-        def wrapped(self, *args, **kwargs):
-            self.count += 1
-            return func(self, *args, **kwargs)
-
-        return wrapped
-
-    @_increment_count
-    @_check_tau
-    def prox(self, x, tau):
-        x = x.reshape(self.dims)
-        if self.isotropic:
-            return denoise_tv_chambolle(
-                x, weight=tau * self.sigma / 2, max_num_iter=self.max_iter
-            )
-        else:
-            return denoise_tv_bregman(
-                x,
-                weight=tau * self.sigma / 2,
-                isotropic=self.isotropic,
-                max_num_iter=self.max_iter,
-            )
-
-    def __call__(self, x):
-        m = np.zeros_like(x)
-        for d in range(x.ndim):
-            diff = np.gradient(x, axis=d)
-            if self.isotropic:
-                m += diff**2
-            else:
-                m += np.abs(diff)
-        if not self.isotropic:
-            m = np.sqrt(m)
-        return m.sum()
 
+from skprox.operators import Dummy, TV, TVL1
 
 PROXIMAL_OPERATORS = {
     "Dummy": Dummy,
     "L0": L0,
     "L0Ball": L0Ball,
     "L1": L1,
     "L1Ball": L1Ball,
@@ -89,14 +30,15 @@
     "TV": TV,
     "Nuclear": Nuclear,
     "NuclearBall": NuclearBall,
     "Log": Log,
     "Log1": Log1,
     "Euclidean": Euclidean,
     "EuclideanBall": EuclideanBall,
+    "TVL1": TVL1,
 }
 
 PROXIMAL_PARAMS = {
     "Dummy": (),
     "L0": frozenset(["sigma"]),
     "L0Ball": frozenset(["radius"]),
     "L1": frozenset(["sigma"]),
@@ -106,17 +48,30 @@
     "L21_plus_L1": frozenset(["sigma", "rho"]),
     "TV": frozenset(["sigma", "isotropic", "dims"]),
     "Nuclear": frozenset(["dim", "sigma"]),
     "NuclearBall": frozenset(["dims", "radius"]),
     "Log": frozenset(["sigma", "gamma"]),
     "Log1": frozenset(["sigma", "delta"]),
     "Euclidean": frozenset(["sigma"]),
+    "TVL1": frozenset(["sigma", "rho"]),
 }
 
 
-def _proximal_operators(proximal, filter_params=True, **params):
-    if proximal in PROXIMAL_OPERATORS:
-        if filter_params:
-            params = {k: params[k] for k in params if k in PROXIMAL_PARAMS[proximal]}
-        return PROXIMAL_OPERATORS[proximal](**params)
-    elif callable(proximal):
-        return partial(proximal, **params)
+class _PGDMixin:
+    """
+    This class will be used by all proximal gradient descent algorithms.
+
+    We would like it to flexibly allow for different gradient descent algorithms including gradient descent with momentum, Nesterov's accelerated gradient descent, and stochastic gradient descent.
+    """
+    def _proximal_gradient_descent(self, X, y, coef_):
+        """
+        This is the main proximal gradient descent algorithm.
+        """
+
+
+    @abstractmethod
+    def _compute_gradient(self, X, y, coef_):
+        pass
+
+    @abstractmethod
+    def _objective(self, X, y, coef_):
+        pass
```

### Comparing `scikit_prox-0.0.3/PKG-INFO` & `scikit_prox-0.0.4/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,19 +1,20 @@
 Metadata-Version: 2.1
 Name: scikit-prox
-Version: 0.0.3
+Version: 0.0.4
 Summary: A package for solving regularised optimisation problems in a scikit-learn style.
 Author: jameschapman19
 Author-email: james.chapman.19@ucl.ac.uk
 Requires-Python: >=3.8,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
+Requires-Dist: numpy (>=1.8.1,<2.0.0)
 Requires-Dist: pyproximal (>=0.5.0,<0.6.0)
 Requires-Dist: pytest (>=7.2.1,<8.0.0)
 Requires-Dist: scikit-image (>=0.19.3,<0.20.0)
 Requires-Dist: scikit-learn (>=1.2.1,<2.0.0)
 Description-Content-Type: text/markdown
 
 [![codecov](https://codecov.io/gh/jameschapman19/scikit-prox/branch/main/graph/badge.svg?token=Id6VAqEdoc)](https://codecov.io/gh/jameschapman19/scikit-prox)
```


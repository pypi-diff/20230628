# Comparing `tmp/rvtools-0.1.3.tar.gz` & `tmp/rvtools-0.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "rvtools-0.1.3.tar", max compression
+gzip compressed data, was "rvtools-0.1.4.tar", max compression
```

## Comparing `rvtools-0.1.3.tar` & `rvtools-0.1.4.tar`

### file list

```diff
@@ -1,31 +1,33 @@
--rw-r--r--   0        0        0     5324 2023-06-28 11:51:17.792034 rvtools-0.1.3/README.md
--rw-r--r--   0        0        0      878 2023-06-28 11:52:51.650588 rvtools-0.1.3/pyproject.toml
--rw-r--r--   0        0        0      264 2023-06-28 11:35:59.919900 rvtools-0.1.3/rvtools/__init__.py
--rw-r--r--   0        0        0      220 2023-06-28 11:36:26.456220 rvtools-0.1.3/rvtools/construct/__init__.py
--rw-r--r--   0        0        0      505 2023-06-28 11:52:06.991468 rvtools-0.1.3/rvtools/construct/__pycache__/__init__.cpython-311.pyc
--rw-r--r--   0        0        0     2573 2023-06-25 22:21:36.090266 rvtools-0.1.3/rvtools/construct/__pycache__/_helpers.cpython-311.pyc
--rw-r--r--   0        0        0     2768 2023-06-26 22:48:02.435671 rvtools-0.1.3/rvtools/construct/__pycache__/beta.cpython-311.pyc
--rw-r--r--   0        0        0     3798 2023-06-26 22:48:02.436259 rvtools-0.1.3/rvtools/construct/__pycache__/lognorm.cpython-311.pyc
--rw-r--r--   0        0        0     2764 2023-06-26 22:48:02.436685 rvtools-0.1.3/rvtools/construct/__pycache__/norm.cpython-311.pyc
--rw-r--r--   0        0        0     2641 2023-06-26 22:48:02.437087 rvtools-0.1.3/rvtools/construct/__pycache__/uniform.cpython-311.pyc
--rw-r--r--   0        0        0     1535 2023-06-25 22:20:41.612198 rvtools-0.1.3/rvtools/construct/_helpers.py
--rw-r--r--   0        0        0     1477 2023-06-26 22:48:01.909872 rvtools-0.1.3/rvtools/construct/beta.py
--rw-r--r--   0        0        0     2127 2023-06-26 22:48:01.906834 rvtools-0.1.3/rvtools/construct/lognorm.py
--rw-r--r--   0        0        0     1258 2023-06-26 22:48:01.911084 rvtools-0.1.3/rvtools/construct/norm.py
--rw-r--r--   0        0        0     1437 2023-06-26 22:48:01.914585 rvtools-0.1.3/rvtools/construct/uniform.py
--rw-r--r--   0        0        0      126 2023-06-26 20:21:17.331337 rvtools-0.1.3/rvtools/distributions/__init__.py
--rw-r--r--   0        0        0      358 2023-06-26 20:21:36.589514 rvtools-0.1.3/rvtools/distributions/__pycache__/__init__.cpython-311.pyc
--rw-r--r--   0        0        0     1726 2023-06-26 18:36:15.269055 rvtools-0.1.3/rvtools/distributions/__pycache__/certainty.cpython-311.pyc
--rw-r--r--   0        0        0     8408 2023-06-26 20:16:33.256135 rvtools-0.1.3/rvtools/distributions/__pycache__/tp_uniform.cpython-311.pyc
--rw-r--r--   0        0        0      854 2023-06-26 18:23:58.213480 rvtools-0.1.3/rvtools/distributions/certainty.py
--rw-r--r--   0        0        0     5151 2023-06-26 20:16:32.712477 rvtools-0.1.3/rvtools/distributions/tp_uniform.py
--rw-r--r--   0        0        0      556 2023-06-26 21:58:51.980313 rvtools-0.1.3/rvtools/types.py
--rw-r--r--   0        0        0        0 2023-06-25 18:12:13.995575 rvtools-0.1.3/tests/__init__.py
--rw-r--r--   0        0        0      507 2023-06-26 20:21:17.339335 rvtools-0.1.3/tests/conftest.py
--rw-r--r--   0        0        0      339 2023-06-25 21:11:58.259220 rvtools-0.1.3/tests/test_certainty.py
--rw-r--r--   0        0        0     5084 2023-06-26 22:48:01.916512 rvtools-0.1.3/tests/test_constructors.py
--rw-r--r--   0        0        0      274 2023-06-25 23:03:01.270501 rvtools-0.1.3/tests/test_docs_do_not_raise.py
--rw-r--r--   0        0        0     2159 2023-06-26 22:48:01.912458 rvtools-0.1.3/tests/test_parse_spec.py
--rw-r--r--   0        0        0     4264 2023-06-26 22:48:01.908527 rvtools-0.1.3/tests/test_tp_uniform.py
--rw-r--r--   0        0        0      513 2023-06-26 21:58:51.980481 rvtools-0.1.3/tests/test_types.py
--rw-r--r--   0        0        0     5970 1970-01-01 00:00:00.000000 rvtools-0.1.3/PKG-INFO
+-rw-r--r--   0        0        0     5605 2023-06-28 13:10:40.461684 rvtools-0.1.4/README.md
+-rw-r--r--   0        0        0      900 2023-06-28 13:11:21.607506 rvtools-0.1.4/pyproject.toml
+-rw-r--r--   0        0        0      264 2023-06-28 11:35:59.919900 rvtools-0.1.4/rvtools/__init__.py
+-rw-r--r--   0        0        0      272 2023-06-28 12:42:43.459690 rvtools-0.1.4/rvtools/construct/__init__.py
+-rw-r--r--   0        0        0      584 2023-06-28 12:42:44.064856 rvtools-0.1.4/rvtools/construct/__pycache__/__init__.cpython-311.pyc
+-rw-r--r--   0        0        0     2573 2023-06-25 22:21:36.090266 rvtools-0.1.4/rvtools/construct/__pycache__/_helpers.cpython-311.pyc
+-rw-r--r--   0        0        0     2768 2023-06-26 22:48:02.435671 rvtools-0.1.4/rvtools/construct/__pycache__/beta.cpython-311.pyc
+-rw-r--r--   0        0        0     3798 2023-06-26 22:48:02.436259 rvtools-0.1.4/rvtools/construct/__pycache__/lognorm.cpython-311.pyc
+-rw-r--r--   0        0        0     2457 2023-06-28 13:08:31.007828 rvtools-0.1.4/rvtools/construct/__pycache__/loguniform.cpython-311.pyc
+-rw-r--r--   0        0        0     2764 2023-06-26 22:48:02.436685 rvtools-0.1.4/rvtools/construct/__pycache__/norm.cpython-311.pyc
+-rw-r--r--   0        0        0     2641 2023-06-26 22:48:02.437087 rvtools-0.1.4/rvtools/construct/__pycache__/uniform.cpython-311.pyc
+-rw-r--r--   0        0        0     1535 2023-06-25 22:20:41.612198 rvtools-0.1.4/rvtools/construct/_helpers.py
+-rw-r--r--   0        0        0     1477 2023-06-26 22:48:01.909872 rvtools-0.1.4/rvtools/construct/beta.py
+-rw-r--r--   0        0        0     2127 2023-06-26 22:48:01.906834 rvtools-0.1.4/rvtools/construct/lognorm.py
+-rw-r--r--   0        0        0     1285 2023-06-28 13:08:30.232208 rvtools-0.1.4/rvtools/construct/loguniform.py
+-rw-r--r--   0        0        0     1258 2023-06-26 22:48:01.911084 rvtools-0.1.4/rvtools/construct/norm.py
+-rw-r--r--   0        0        0     1437 2023-06-26 22:48:01.914585 rvtools-0.1.4/rvtools/construct/uniform.py
+-rw-r--r--   0        0        0      126 2023-06-26 20:21:17.331337 rvtools-0.1.4/rvtools/distributions/__init__.py
+-rw-r--r--   0        0        0      358 2023-06-26 20:21:36.589514 rvtools-0.1.4/rvtools/distributions/__pycache__/__init__.cpython-311.pyc
+-rw-r--r--   0        0        0     1726 2023-06-26 18:36:15.269055 rvtools-0.1.4/rvtools/distributions/__pycache__/certainty.cpython-311.pyc
+-rw-r--r--   0        0        0     8408 2023-06-26 20:16:33.256135 rvtools-0.1.4/rvtools/distributions/__pycache__/tp_uniform.cpython-311.pyc
+-rw-r--r--   0        0        0      854 2023-06-26 18:23:58.213480 rvtools-0.1.4/rvtools/distributions/certainty.py
+-rw-r--r--   0        0        0     5151 2023-06-26 20:16:32.712477 rvtools-0.1.4/rvtools/distributions/tp_uniform.py
+-rw-r--r--   0        0        0      556 2023-06-26 21:58:51.980313 rvtools-0.1.4/rvtools/types.py
+-rw-r--r--   0        0        0        0 2023-06-25 18:12:13.995575 rvtools-0.1.4/tests/__init__.py
+-rw-r--r--   0        0        0      507 2023-06-26 20:21:17.339335 rvtools-0.1.4/tests/conftest.py
+-rw-r--r--   0        0        0      339 2023-06-25 21:11:58.259220 rvtools-0.1.4/tests/test_certainty.py
+-rw-r--r--   0        0        0     5679 2023-06-28 13:10:57.477667 rvtools-0.1.4/tests/test_constructors.py
+-rw-r--r--   0        0        0      274 2023-06-25 23:03:01.270501 rvtools-0.1.4/tests/test_docs_do_not_raise.py
+-rw-r--r--   0        0        0     2159 2023-06-26 22:48:01.912458 rvtools-0.1.4/tests/test_parse_spec.py
+-rw-r--r--   0        0        0     4264 2023-06-26 22:48:01.908527 rvtools-0.1.4/tests/test_tp_uniform.py
+-rw-r--r--   0        0        0      513 2023-06-26 21:58:51.980481 rvtools-0.1.4/tests/test_types.py
+-rw-r--r--   0        0        0     6251 1970-01-01 00:00:00.000000 rvtools-0.1.4/PKG-INFO
```

### Comparing `rvtools-0.1.3/README.md` & `rvtools-0.1.4/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -51,15 +51,15 @@
 
 These are functions that return a 'frozen' distribution object (which in SciPy means a distribution with specific parameter values). This means `lognorm(1, 2).cdf(3)` can be used, but the `lognorm.cdf(3, 1, 2)` that you may be used to from SciPy will raise an `AttributeError` with rvtools. (Given how SciPy's distribution infrastructure works, improving this would require severe hacks, as far as I can tell.)
 
 ⚠️ **Many of these function signatures intentionally diverge from `scipy.stats`.** The behaviour should generally be clear from the names of the keyword arguments. However, if you blindly use _positional_ arguments and expect the same behaviour as `scipy.stats`, bad things will happen.
 
 This is an opinionated API designed to be in line with common usage in mathematics and statistics, and my personal preferences. It may be a bad fit if you want to write code that is highly idiomatic in the Python scientific computing ecosystem.
 
-### Lognormal
+### Log-normal
 
 ```python
 from rvtools.construct import lognorm
 
 # Three ways to specify the parameters:
 
 # 1. Using (mu, sigma)
@@ -106,19 +106,33 @@
 # Two ways to specify parameters:
 
 # 1. Using bounds. This differs from SciPy.
 uniform(0, 1)
 # Bounds do not need to be ordered. This is equivalent:
 uniform(1, 0)
 
-# 2. Quantiles
+# 2. Using quantiles
 uniform(p5=0, p95=1)
 uniform(quantiles={0.05: 0, 0.95: 1})
 ```
 
+### Log-uniform
+
+```python
+from rvtools.construct import loguniform
+# Two ways to specify parameters:
+
+# 1. Using bounds. 
+# This works the same as SciPy, except that the bounds do not need to be ordered.
+loguniform(10, 1)
+
+# 2. Using quantiles
+loguniform(p5=1, p95=2)
+```
+
 ### Correlated multivariate distribution via Copula
 Specify a joint probability distribution from arbitrary marginal distributions and pairwise rank correlations.
 
 See [tadamcz/copula-wrapper](https://github.com/tadamcz/copula-wrapper) for full details, these functions are simply imported from there for convenience.
 ```python
 from rvtools.construct import CopulaJoint
 import scipy
```

### Comparing `rvtools-0.1.3/pyproject.toml` & `rvtools-0.1.4/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 [tool]
 [tool.poetry]
 name = "rvtools"
-version = "0.1.3"
+version = "0.1.4"
 homepage = "https://github.com/tadamcz/rvtools"
 description = "Top-level package for Probability distribution and random variable tools."
 authors = ["Tom Adamczewski <tadamczewskipublic@gmail.com>"]
 readme = "README.md"
 classifiers=[
     'Natural Language :: English',
     'Programming Language :: Python :: 3',
@@ -23,14 +23,15 @@
 [tool.poetry.group.dev.dependencies]
 bump2version = "*"
 coverage = "*"
 pytest = ">=7.2.0"
 pytest-pycharm = "*"
 black = {extras = ["d"], version = "*"}
 mkcodes = "^0.1.1"
+matplotlib = "^3.7.1"
 
 
 
 [tool.black]
 line-length = 100
 
 [build-system]
```

### Comparing `rvtools-0.1.3/rvtools/construct/__pycache__/_helpers.cpython-311.pyc` & `rvtools-0.1.4/rvtools/construct/__pycache__/_helpers.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/rvtools/construct/__pycache__/beta.cpython-311.pyc` & `rvtools-0.1.4/rvtools/construct/__pycache__/beta.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/rvtools/construct/__pycache__/lognorm.cpython-311.pyc` & `rvtools-0.1.4/rvtools/construct/__pycache__/lognorm.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/rvtools/construct/__pycache__/norm.cpython-311.pyc` & `rvtools-0.1.4/rvtools/construct/__pycache__/norm.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/rvtools/construct/__pycache__/uniform.cpython-311.pyc` & `rvtools-0.1.4/rvtools/construct/__pycache__/uniform.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/rvtools/construct/_helpers.py` & `rvtools-0.1.4/rvtools/construct/_helpers.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/rvtools/construct/beta.py` & `rvtools-0.1.4/rvtools/construct/beta.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/rvtools/construct/lognorm.py` & `rvtools-0.1.4/rvtools/construct/lognorm.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/rvtools/construct/norm.py` & `rvtools-0.1.4/rvtools/construct/norm.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/rvtools/construct/uniform.py` & `rvtools-0.1.4/rvtools/construct/uniform.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/rvtools/distributions/__pycache__/certainty.cpython-311.pyc` & `rvtools-0.1.4/rvtools/distributions/__pycache__/certainty.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/rvtools/distributions/__pycache__/tp_uniform.cpython-311.pyc` & `rvtools-0.1.4/rvtools/distributions/__pycache__/tp_uniform.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/rvtools/distributions/certainty.py` & `rvtools-0.1.4/rvtools/distributions/certainty.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/rvtools/distributions/tp_uniform.py` & `rvtools-0.1.4/rvtools/distributions/tp_uniform.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/rvtools/types.py` & `rvtools-0.1.4/rvtools/types.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/tests/test_constructors.py` & `rvtools-0.1.4/tests/test_constructors.py`

 * *Files 12% similar despite different names*

```diff
@@ -29,15 +29,15 @@
             our_d = construct.beta(alpha=alpha, beta=beta)
         else:
             our_d = construct.beta(alpha, beta)
         scipy_d = scipy.stats.beta(alpha, beta)
         assert_same_distribution(our_d, scipy_d)
 
     @pytest.fixture(
-        params=[{0.1: 0.2, 0.5: 0.85}, {0.1: 0.5, 0.5: 0.99}, {0.001: 0.5, 0.5: 0.99}],  #  #  #
+        params=[{0.1: 0.2, 0.5: 0.85}, {0.1: 0.5, 0.5: 0.99}, {0.001: 0.5, 0.5: 0.99}],  # #  #
         ids=lambda p: f"quantiles={p}",
     )
     def quantiles(self, request):
         return request.param
 
     def test_from_quantiles(self, quantiles):
         assert_has_quantiles(construct.beta(quantiles=quantiles), quantiles)
@@ -152,7 +152,29 @@
     def test_from_quantiles(self, quantiles):
         dist = construct.uniform(quantiles=quantiles)
         assert_has_quantiles(dist, quantiles)
 
     def test_degenerate_rvs(self):
         our_d = construct.uniform(1, 1)
         assert all(our_d.rvs(size=10) == [1] * 10)
+
+
+class TestLogUniform:
+    @pytest.fixture(
+        params=[
+            # A simple case
+            {0.1: 1, 0.9: 10_000},
+            # Small numbers
+            {0.1: 1e-6, 0.9: 1e-5},
+        ],
+        ids=lambda p: f"quantiles={p}",
+    )
+    def quantiles(self, request):
+        return request.param
+
+    def test_from_quantiles(self, quantiles):
+        dist = construct.loguniform(quantiles=quantiles)
+        assert_has_quantiles(dist, quantiles)
+
+    def test_params_unordered(self):
+        dist = construct.loguniform(10, 1)
+        assert dist.support() == pytest.approx([1, 10])
```

### Comparing `rvtools-0.1.3/tests/test_parse_spec.py` & `rvtools-0.1.4/tests/test_parse_spec.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/tests/test_tp_uniform.py` & `rvtools-0.1.4/tests/test_tp_uniform.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/tests/test_types.py` & `rvtools-0.1.4/tests/test_types.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.3/PKG-INFO` & `rvtools-0.1.4/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: rvtools
-Version: 0.1.3
+Version: 0.1.4
 Summary: Top-level package for Probability distribution and random variable tools.
 Home-page: https://github.com/tadamcz/rvtools
 Author: Tom Adamczewski
 Author-email: tadamczewskipublic@gmail.com
 Requires-Python: >=3.9,<3.13
 Classifier: Natural Language :: English
 Classifier: Programming Language :: Python :: 3
@@ -68,15 +68,15 @@
 
 These are functions that return a 'frozen' distribution object (which in SciPy means a distribution with specific parameter values). This means `lognorm(1, 2).cdf(3)` can be used, but the `lognorm.cdf(3, 1, 2)` that you may be used to from SciPy will raise an `AttributeError` with rvtools. (Given how SciPy's distribution infrastructure works, improving this would require severe hacks, as far as I can tell.)
 
 ⚠️ **Many of these function signatures intentionally diverge from `scipy.stats`.** The behaviour should generally be clear from the names of the keyword arguments. However, if you blindly use _positional_ arguments and expect the same behaviour as `scipy.stats`, bad things will happen.
 
 This is an opinionated API designed to be in line with common usage in mathematics and statistics, and my personal preferences. It may be a bad fit if you want to write code that is highly idiomatic in the Python scientific computing ecosystem.
 
-### Lognormal
+### Log-normal
 
 ```python
 from rvtools.construct import lognorm
 
 # Three ways to specify the parameters:
 
 # 1. Using (mu, sigma)
@@ -123,19 +123,33 @@
 # Two ways to specify parameters:
 
 # 1. Using bounds. This differs from SciPy.
 uniform(0, 1)
 # Bounds do not need to be ordered. This is equivalent:
 uniform(1, 0)
 
-# 2. Quantiles
+# 2. Using quantiles
 uniform(p5=0, p95=1)
 uniform(quantiles={0.05: 0, 0.95: 1})
 ```
 
+### Log-uniform
+
+```python
+from rvtools.construct import loguniform
+# Two ways to specify parameters:
+
+# 1. Using bounds. 
+# This works the same as SciPy, except that the bounds do not need to be ordered.
+loguniform(10, 1)
+
+# 2. Using quantiles
+loguniform(p5=1, p95=2)
+```
+
 ### Correlated multivariate distribution via Copula
 Specify a joint probability distribution from arbitrary marginal distributions and pairwise rank correlations.
 
 See [tadamcz/copula-wrapper](https://github.com/tadamcz/copula-wrapper) for full details, these functions are simply imported from there for convenience.
 ```python
 from rvtools.construct import CopulaJoint
 import scipy
```


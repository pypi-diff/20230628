# Comparing `tmp/rvtools-0.1.2.tar.gz` & `tmp/rvtools-0.1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "rvtools-0.1.2.tar", max compression
+gzip compressed data, was "rvtools-0.1.3.tar", max compression
```

## Comparing `rvtools-0.1.2.tar` & `rvtools-0.1.3.tar`

### file list

```diff
@@ -1,31 +1,31 @@
--rw-r--r--   0        0        0     4152 2023-06-26 22:59:09.399091 rvtools-0.1.2/README.md
--rw-r--r--   0        0        0      852 2023-06-28 11:05:40.707093 rvtools-0.1.2/pyproject.toml
--rw-r--r--   0        0        0      264 2023-06-26 22:42:35.971751 rvtools-0.1.2/rvtools/__init__.py
--rw-r--r--   0        0        0      172 2023-06-26 22:48:01.905065 rvtools-0.1.2/rvtools/construct/__init__.py
--rw-r--r--   0        0        0      439 2023-06-26 22:48:02.435189 rvtools-0.1.2/rvtools/construct/__pycache__/__init__.cpython-311.pyc
--rw-r--r--   0        0        0     2573 2023-06-25 22:21:36.090266 rvtools-0.1.2/rvtools/construct/__pycache__/_helpers.cpython-311.pyc
--rw-r--r--   0        0        0     2768 2023-06-26 22:48:02.435671 rvtools-0.1.2/rvtools/construct/__pycache__/beta.cpython-311.pyc
--rw-r--r--   0        0        0     3798 2023-06-26 22:48:02.436259 rvtools-0.1.2/rvtools/construct/__pycache__/lognorm.cpython-311.pyc
--rw-r--r--   0        0        0     2764 2023-06-26 22:48:02.436685 rvtools-0.1.2/rvtools/construct/__pycache__/norm.cpython-311.pyc
--rw-r--r--   0        0        0     2641 2023-06-26 22:48:02.437087 rvtools-0.1.2/rvtools/construct/__pycache__/uniform.cpython-311.pyc
--rw-r--r--   0        0        0     1535 2023-06-25 22:20:41.612198 rvtools-0.1.2/rvtools/construct/_helpers.py
--rw-r--r--   0        0        0     1477 2023-06-26 22:48:01.909872 rvtools-0.1.2/rvtools/construct/beta.py
--rw-r--r--   0        0        0     2127 2023-06-26 22:48:01.906834 rvtools-0.1.2/rvtools/construct/lognorm.py
--rw-r--r--   0        0        0     1258 2023-06-26 22:48:01.911084 rvtools-0.1.2/rvtools/construct/norm.py
--rw-r--r--   0        0        0     1437 2023-06-26 22:48:01.914585 rvtools-0.1.2/rvtools/construct/uniform.py
--rw-r--r--   0        0        0      126 2023-06-26 20:21:17.331337 rvtools-0.1.2/rvtools/distributions/__init__.py
--rw-r--r--   0        0        0      358 2023-06-26 20:21:36.589514 rvtools-0.1.2/rvtools/distributions/__pycache__/__init__.cpython-311.pyc
--rw-r--r--   0        0        0     1726 2023-06-26 18:36:15.269055 rvtools-0.1.2/rvtools/distributions/__pycache__/certainty.cpython-311.pyc
--rw-r--r--   0        0        0     8408 2023-06-26 20:16:33.256135 rvtools-0.1.2/rvtools/distributions/__pycache__/tp_uniform.cpython-311.pyc
--rw-r--r--   0        0        0      854 2023-06-26 18:23:58.213480 rvtools-0.1.2/rvtools/distributions/certainty.py
--rw-r--r--   0        0        0     5151 2023-06-26 20:16:32.712477 rvtools-0.1.2/rvtools/distributions/tp_uniform.py
--rw-r--r--   0        0        0      556 2023-06-26 21:58:51.980313 rvtools-0.1.2/rvtools/types.py
--rw-r--r--   0        0        0        0 2023-06-25 18:12:13.995575 rvtools-0.1.2/tests/__init__.py
--rw-r--r--   0        0        0      507 2023-06-26 20:21:17.339335 rvtools-0.1.2/tests/conftest.py
--rw-r--r--   0        0        0      339 2023-06-25 21:11:58.259220 rvtools-0.1.2/tests/test_certainty.py
--rw-r--r--   0        0        0     5084 2023-06-26 22:48:01.916512 rvtools-0.1.2/tests/test_constructors.py
--rw-r--r--   0        0        0      274 2023-06-25 23:03:01.270501 rvtools-0.1.2/tests/test_docs_do_not_raise.py
--rw-r--r--   0        0        0     2159 2023-06-26 22:48:01.912458 rvtools-0.1.2/tests/test_parse_spec.py
--rw-r--r--   0        0        0     4264 2023-06-26 22:48:01.908527 rvtools-0.1.2/tests/test_tp_uniform.py
--rw-r--r--   0        0        0      513 2023-06-26 21:58:51.980481 rvtools-0.1.2/tests/test_types.py
--rw-r--r--   0        0        0     4751 1970-01-01 00:00:00.000000 rvtools-0.1.2/PKG-INFO
+-rw-r--r--   0        0        0     5324 2023-06-28 11:51:17.792034 rvtools-0.1.3/README.md
+-rw-r--r--   0        0        0      878 2023-06-28 11:52:51.650588 rvtools-0.1.3/pyproject.toml
+-rw-r--r--   0        0        0      264 2023-06-28 11:35:59.919900 rvtools-0.1.3/rvtools/__init__.py
+-rw-r--r--   0        0        0      220 2023-06-28 11:36:26.456220 rvtools-0.1.3/rvtools/construct/__init__.py
+-rw-r--r--   0        0        0      505 2023-06-28 11:52:06.991468 rvtools-0.1.3/rvtools/construct/__pycache__/__init__.cpython-311.pyc
+-rw-r--r--   0        0        0     2573 2023-06-25 22:21:36.090266 rvtools-0.1.3/rvtools/construct/__pycache__/_helpers.cpython-311.pyc
+-rw-r--r--   0        0        0     2768 2023-06-26 22:48:02.435671 rvtools-0.1.3/rvtools/construct/__pycache__/beta.cpython-311.pyc
+-rw-r--r--   0        0        0     3798 2023-06-26 22:48:02.436259 rvtools-0.1.3/rvtools/construct/__pycache__/lognorm.cpython-311.pyc
+-rw-r--r--   0        0        0     2764 2023-06-26 22:48:02.436685 rvtools-0.1.3/rvtools/construct/__pycache__/norm.cpython-311.pyc
+-rw-r--r--   0        0        0     2641 2023-06-26 22:48:02.437087 rvtools-0.1.3/rvtools/construct/__pycache__/uniform.cpython-311.pyc
+-rw-r--r--   0        0        0     1535 2023-06-25 22:20:41.612198 rvtools-0.1.3/rvtools/construct/_helpers.py
+-rw-r--r--   0        0        0     1477 2023-06-26 22:48:01.909872 rvtools-0.1.3/rvtools/construct/beta.py
+-rw-r--r--   0        0        0     2127 2023-06-26 22:48:01.906834 rvtools-0.1.3/rvtools/construct/lognorm.py
+-rw-r--r--   0        0        0     1258 2023-06-26 22:48:01.911084 rvtools-0.1.3/rvtools/construct/norm.py
+-rw-r--r--   0        0        0     1437 2023-06-26 22:48:01.914585 rvtools-0.1.3/rvtools/construct/uniform.py
+-rw-r--r--   0        0        0      126 2023-06-26 20:21:17.331337 rvtools-0.1.3/rvtools/distributions/__init__.py
+-rw-r--r--   0        0        0      358 2023-06-26 20:21:36.589514 rvtools-0.1.3/rvtools/distributions/__pycache__/__init__.cpython-311.pyc
+-rw-r--r--   0        0        0     1726 2023-06-26 18:36:15.269055 rvtools-0.1.3/rvtools/distributions/__pycache__/certainty.cpython-311.pyc
+-rw-r--r--   0        0        0     8408 2023-06-26 20:16:33.256135 rvtools-0.1.3/rvtools/distributions/__pycache__/tp_uniform.cpython-311.pyc
+-rw-r--r--   0        0        0      854 2023-06-26 18:23:58.213480 rvtools-0.1.3/rvtools/distributions/certainty.py
+-rw-r--r--   0        0        0     5151 2023-06-26 20:16:32.712477 rvtools-0.1.3/rvtools/distributions/tp_uniform.py
+-rw-r--r--   0        0        0      556 2023-06-26 21:58:51.980313 rvtools-0.1.3/rvtools/types.py
+-rw-r--r--   0        0        0        0 2023-06-25 18:12:13.995575 rvtools-0.1.3/tests/__init__.py
+-rw-r--r--   0        0        0      507 2023-06-26 20:21:17.339335 rvtools-0.1.3/tests/conftest.py
+-rw-r--r--   0        0        0      339 2023-06-25 21:11:58.259220 rvtools-0.1.3/tests/test_certainty.py
+-rw-r--r--   0        0        0     5084 2023-06-26 22:48:01.916512 rvtools-0.1.3/tests/test_constructors.py
+-rw-r--r--   0        0        0      274 2023-06-25 23:03:01.270501 rvtools-0.1.3/tests/test_docs_do_not_raise.py
+-rw-r--r--   0        0        0     2159 2023-06-26 22:48:01.912458 rvtools-0.1.3/tests/test_parse_spec.py
+-rw-r--r--   0        0        0     4264 2023-06-26 22:48:01.908527 rvtools-0.1.3/tests/test_tp_uniform.py
+-rw-r--r--   0        0        0      513 2023-06-26 21:58:51.980481 rvtools-0.1.3/tests/test_types.py
+-rw-r--r--   0        0        0     5970 1970-01-01 00:00:00.000000 rvtools-0.1.3/PKG-INFO
```

### Comparing `rvtools-0.1.2/README.md` & `rvtools-0.1.3/README.md`

 * *Files 18% similar despite different names*

```diff
@@ -32,18 +32,20 @@
 # In other words, this is like the Dirac delta distribution, but at any
 # value (e.g. 42), not just 0.
 certainty(42)
 assert isinstance(certainty, scipy.stats.rv_continuous)
 ```
 
 ### PERT
-See [tadamcz/betapert](https://github.com/tadamcz/betapert), these functions are simply imported from there for convenience.
+Defined by the minimum, most likely, and maximum values. An alternative to the triangular distribution with a smoother shape.
+
+See [tadamcz/betapert](https://github.com/tadamcz/betapert) (these distributions are simply imported from there for convenience).
 ```python
 from rvtools import pert, mpert
-pert(1, 2, 4)
+pert(1, 2, 4)  # minimum, most likely (mode), maximum
 mpert(1, 2, 4, lambd=2.5)
 ```
 
 
 
 ## Constructors for common distributions
 
@@ -108,14 +110,37 @@
 # Bounds do not need to be ordered. This is equivalent:
 uniform(1, 0)
 
 # 2. Quantiles
 uniform(p5=0, p95=1)
 uniform(quantiles={0.05: 0, 0.95: 1})
 ```
+
+### Correlated multivariate distribution via Copula
+Specify a joint probability distribution from arbitrary marginal distributions and pairwise rank correlations.
+
+See [tadamcz/copula-wrapper](https://github.com/tadamcz/copula-wrapper) for full details, these functions are simply imported from there for convenience.
+```python
+from rvtools.construct import CopulaJoint
+import scipy
+# Marginals and correlations as dictionaries (can also be list and matrix) 
+marginals = {
+	"consumption elasticity": scipy.stats.uniform(0.75, 3),
+	"market return": scipy.stats.lognorm(0.05, 0.05),
+	"risk of war": scipy.stats.beta(1, 50)
+}
+tau = {
+	# Missing pairs are assumed to be independent
+	("risk of war", "market return"): -0.5,
+}
+CopulaJoint(marginals, kendall_tau=tau)  # Spearman's rho is also supported
+```
+
+For arcane implementation reasons (see [tadamcz/copula-wrapper](https://github.com/tadamcz/copula-wrapper)) the other constructors are functions, while `CopulaJoint` is a class. You shouldn't have to think about this: both return a frozen distribution object when called. 
+
 ## 'Type' checkers
 A 'frozen' distribution inherits from `scipy.stats._distn_infrastructure.rv_frozen`. This means its Python type does not expose the distribution family (e.g. whether it's a `norm` or `lognorm`). 
 
 These functions let you check this at runtime (by looking at the `dist` attribute of a frozen distribution).
 
 ```python
 from rvtools.types import is_frozen_norm, is_frozen_lognorm, is_frozen_beta
@@ -124,9 +149,8 @@
 
 assert is_frozen_norm(scipy.stats.norm(0, 1))
 assert is_frozen_norm(rvtools.construct.norm(p10=0, p90=1))
 ```
 
 # TODO
 ## Truncated lognormal
-## Add https://github.com/tadamcz/copula-wrapper once quality is good enough
 ## Add https://github.com/tadamcz/metalogistic once quality is good enough
```

### Comparing `rvtools-0.1.2/pyproject.toml` & `rvtools-0.1.3/pyproject.toml`

 * *Files 11% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 [tool]
 [tool.poetry]
 name = "rvtools"
-version = "0.1.2"
+version = "0.1.3"
 homepage = "https://github.com/tadamcz/rvtools"
 description = "Top-level package for Probability distribution and random variable tools."
 authors = ["Tom Adamczewski <tadamczewskipublic@gmail.com>"]
 readme = "README.md"
 classifiers=[
     'Natural Language :: English',
     'Programming Language :: Python :: 3',
@@ -14,14 +14,15 @@
     { include = "rvtools" },
     { include = "tests", format = "sdist" },
 ]
 
 [tool.poetry.dependencies]
 python = ">=3.9,<3.13"
 betapert = "^0.1.2"
+copula-wrapper = "^0.1.1"
 
 [tool.poetry.group.dev.dependencies]
 bump2version = "*"
 coverage = "*"
 pytest = ">=7.2.0"
 pytest-pycharm = "*"
 black = {extras = ["d"], version = "*"}
```

### Comparing `rvtools-0.1.2/rvtools/construct/__pycache__/_helpers.cpython-311.pyc` & `rvtools-0.1.3/rvtools/construct/__pycache__/_helpers.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/rvtools/construct/__pycache__/beta.cpython-311.pyc` & `rvtools-0.1.3/rvtools/construct/__pycache__/beta.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/rvtools/construct/__pycache__/lognorm.cpython-311.pyc` & `rvtools-0.1.3/rvtools/construct/__pycache__/lognorm.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/rvtools/construct/__pycache__/norm.cpython-311.pyc` & `rvtools-0.1.3/rvtools/construct/__pycache__/norm.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/rvtools/construct/__pycache__/uniform.cpython-311.pyc` & `rvtools-0.1.3/rvtools/construct/__pycache__/uniform.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/rvtools/construct/_helpers.py` & `rvtools-0.1.3/rvtools/construct/_helpers.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/rvtools/construct/beta.py` & `rvtools-0.1.3/rvtools/construct/beta.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/rvtools/construct/lognorm.py` & `rvtools-0.1.3/rvtools/construct/lognorm.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/rvtools/construct/norm.py` & `rvtools-0.1.3/rvtools/construct/norm.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/rvtools/construct/uniform.py` & `rvtools-0.1.3/rvtools/construct/uniform.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/rvtools/distributions/__pycache__/certainty.cpython-311.pyc` & `rvtools-0.1.3/rvtools/distributions/__pycache__/certainty.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/rvtools/distributions/__pycache__/tp_uniform.cpython-311.pyc` & `rvtools-0.1.3/rvtools/distributions/__pycache__/tp_uniform.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/rvtools/distributions/certainty.py` & `rvtools-0.1.3/rvtools/distributions/certainty.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/rvtools/distributions/tp_uniform.py` & `rvtools-0.1.3/rvtools/distributions/tp_uniform.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/rvtools/types.py` & `rvtools-0.1.3/rvtools/types.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/tests/test_constructors.py` & `rvtools-0.1.3/tests/test_constructors.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/tests/test_parse_spec.py` & `rvtools-0.1.3/tests/test_parse_spec.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/tests/test_tp_uniform.py` & `rvtools-0.1.3/tests/test_tp_uniform.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/tests/test_types.py` & `rvtools-0.1.3/tests/test_types.py`

 * *Files identical despite different names*

### Comparing `rvtools-0.1.2/PKG-INFO` & `rvtools-0.1.3/PKG-INFO`

 * *Files 19% similar despite different names*

```diff
@@ -1,21 +1,22 @@
 Metadata-Version: 2.1
 Name: rvtools
-Version: 0.1.2
+Version: 0.1.3
 Summary: Top-level package for Probability distribution and random variable tools.
 Home-page: https://github.com/tadamcz/rvtools
 Author: Tom Adamczewski
 Author-email: tadamczewskipublic@gmail.com
 Requires-Python: >=3.9,<3.13
 Classifier: Natural Language :: English
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Requires-Dist: betapert (>=0.1.2,<0.2.0)
+Requires-Dist: copula-wrapper (>=0.1.1,<0.2.0)
 Description-Content-Type: text/markdown
 
 A collection of tools for conveniently working with SciPy probability distributions.
 
 # Installation
 ```shell
 pip install rvtools  # or `poetry add rvtools`
@@ -48,18 +49,20 @@
 # In other words, this is like the Dirac delta distribution, but at any
 # value (e.g. 42), not just 0.
 certainty(42)
 assert isinstance(certainty, scipy.stats.rv_continuous)
 ```
 
 ### PERT
-See [tadamcz/betapert](https://github.com/tadamcz/betapert), these functions are simply imported from there for convenience.
+Defined by the minimum, most likely, and maximum values. An alternative to the triangular distribution with a smoother shape.
+
+See [tadamcz/betapert](https://github.com/tadamcz/betapert) (these distributions are simply imported from there for convenience).
 ```python
 from rvtools import pert, mpert
-pert(1, 2, 4)
+pert(1, 2, 4)  # minimum, most likely (mode), maximum
 mpert(1, 2, 4, lambd=2.5)
 ```
 
 
 
 ## Constructors for common distributions
 
@@ -124,14 +127,37 @@
 # Bounds do not need to be ordered. This is equivalent:
 uniform(1, 0)
 
 # 2. Quantiles
 uniform(p5=0, p95=1)
 uniform(quantiles={0.05: 0, 0.95: 1})
 ```
+
+### Correlated multivariate distribution via Copula
+Specify a joint probability distribution from arbitrary marginal distributions and pairwise rank correlations.
+
+See [tadamcz/copula-wrapper](https://github.com/tadamcz/copula-wrapper) for full details, these functions are simply imported from there for convenience.
+```python
+from rvtools.construct import CopulaJoint
+import scipy
+# Marginals and correlations as dictionaries (can also be list and matrix) 
+marginals = {
+	"consumption elasticity": scipy.stats.uniform(0.75, 3),
+	"market return": scipy.stats.lognorm(0.05, 0.05),
+	"risk of war": scipy.stats.beta(1, 50)
+}
+tau = {
+	# Missing pairs are assumed to be independent
+	("risk of war", "market return"): -0.5,
+}
+CopulaJoint(marginals, kendall_tau=tau)  # Spearman's rho is also supported
+```
+
+For arcane implementation reasons (see [tadamcz/copula-wrapper](https://github.com/tadamcz/copula-wrapper)) the other constructors are functions, while `CopulaJoint` is a class. You shouldn't have to think about this: both return a frozen distribution object when called. 
+
 ## 'Type' checkers
 A 'frozen' distribution inherits from `scipy.stats._distn_infrastructure.rv_frozen`. This means its Python type does not expose the distribution family (e.g. whether it's a `norm` or `lognorm`). 
 
 These functions let you check this at runtime (by looking at the `dist` attribute of a frozen distribution).
 
 ```python
 from rvtools.types import is_frozen_norm, is_frozen_lognorm, is_frozen_beta
@@ -140,9 +166,8 @@
 
 assert is_frozen_norm(scipy.stats.norm(0, 1))
 assert is_frozen_norm(rvtools.construct.norm(p10=0, p90=1))
 ```
 
 # TODO
 ## Truncated lognormal
-## Add https://github.com/tadamcz/copula-wrapper once quality is good enough
 ## Add https://github.com/tadamcz/metalogistic once quality is good enough
```


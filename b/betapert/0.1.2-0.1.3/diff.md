# Comparing `tmp/betapert-0.1.2.tar.gz` & `tmp/betapert-0.1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "betapert-0.1.2.tar", max compression
+gzip compressed data, was "betapert-0.1.3.tar", max compression
```

## Comparing `betapert-0.1.2.tar` & `betapert-0.1.3.tar`

### file list

```diff
@@ -1,11 +1,11 @@
--rw-r--r--   0        0        0     2412 2023-06-25 15:02:17.636963 betapert-0.1.2/README.md
--rw-r--r--   0        0        0     2709 2023-06-25 14:04:25.518999 betapert-0.1.2/betapert/__init__.py
--rw-r--r--   0        0        0     2814 2023-06-25 14:04:25.514803 betapert-0.1.2/betapert/funcs.py
--rw-r--r--   0        0        0      833 2023-06-25 15:02:25.937415 betapert-0.1.2/pyproject.toml
--rw-r--r--   0        0        0        0 2023-06-23 22:47:37.319709 betapert-0.1.2/tests/__init__.py
--rw-r--r--   0        0        0     1110 2023-06-25 14:04:25.512858 betapert-0.1.2/tests/conftest.py
--rw-r--r--   0        0        0     1972 2023-06-25 13:03:16.467533 betapert-0.1.2/tests/test_frozen.py
--rw-r--r--   0        0        0      864 2023-06-25 14:04:25.517734 betapert-0.1.2/tests/test_generalization.py
--rw-r--r--   0        0        0     3790 2023-06-25 13:55:10.358243 betapert-0.1.2/tests/test_mpert_parametrized.py
--rw-r--r--   0        0        0     1487 2023-06-25 14:04:25.516401 betapert-0.1.2/tests/test_special_cases.py
--rw-r--r--   0        0        0     3033 1970-01-01 00:00:00.000000 betapert-0.1.2/PKG-INFO
+-rw-r--r--   0        0        0     2412 2023-06-25 15:02:17.636963 betapert-0.1.3/README.md
+-rw-r--r--   0        0        0     2713 2023-06-26 19:52:51.563296 betapert-0.1.3/betapert/__init__.py
+-rw-r--r--   0        0        0     2814 2023-06-25 14:04:25.514803 betapert-0.1.3/betapert/funcs.py
+-rw-r--r--   0        0        0      833 2023-06-28 11:01:33.587861 betapert-0.1.3/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-23 22:47:37.319709 betapert-0.1.3/tests/__init__.py
+-rw-r--r--   0        0        0     1099 2023-06-26 19:51:56.628431 betapert-0.1.3/tests/conftest.py
+-rw-r--r--   0        0        0     1972 2023-06-25 13:03:16.467533 betapert-0.1.3/tests/test_frozen.py
+-rw-r--r--   0        0        0      864 2023-06-25 14:04:25.517734 betapert-0.1.3/tests/test_generalization.py
+-rw-r--r--   0        0        0     3790 2023-06-25 13:55:10.358243 betapert-0.1.3/tests/test_mpert_parametrized.py
+-rw-r--r--   0        0        0     1487 2023-06-25 14:04:25.516401 betapert-0.1.3/tests/test_special_cases.py
+-rw-r--r--   0        0        0     2983 1970-01-01 00:00:00.000000 betapert-0.1.3/PKG-INFO
```

### Comparing `betapert-0.1.2/README.md` & `betapert-0.1.3/README.md`

 * *Files identical despite different names*

### Comparing `betapert-0.1.2/betapert/__init__.py` & `betapert-0.1.3/betapert/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -63,12 +63,12 @@
     def _ppf(self, q, mini, mode, maxi, lambd):
         return funcs.ppf(q, mini, mode, maxi, lambd)
 
     def _rvs(self, mini, mode, maxi, lambd, size=None, random_state=None):
         return funcs.rvs(mini, mode, maxi, lambd, size=size, random_state=random_state)
 
 
-# ``pert`` and ``mpert`` being instances, not classes, is not idiomatic Python, but it is core to the way SciPy's
+# ``pert`` and ``mpert`` being instances, not classes, is not IMO idiomatic Python, but it is core to the way SciPy's
 # ``rv_continuous`` class works. See examples of how SciPy defines their distributions in
 # ``scipy/stats/_continuous_distns.py``.
 pert = PERT()
 mpert = ModifiedPERT()
```

### Comparing `betapert-0.1.2/betapert/funcs.py` & `betapert-0.1.3/betapert/funcs.py`

 * *Files identical despite different names*

### Comparing `betapert-0.1.2/pyproject.toml` & `betapert-0.1.3/pyproject.toml`

 * *Files 25% similar despite different names*

```diff
@@ -1,26 +1,26 @@
 [tool]
 [tool.poetry]
 name = "betapert"
-version = "0.1.2"
+version = "0.1.3"
 homepage = "https://github.com/tadamcz/betapert"
 description = "Top-level package for beta-PERT distribution."
 authors = ["Tom Adamczewski <tadamczewskipublic@gmail.com>"]
 readme = "README.md"
 classifiers=[
     'Natural Language :: English',
     'Programming Language :: Python :: 3',
 ]
 packages = [
     { include = "betapert" },
     { include = "tests", format = "sdist" },
 ]
 
 [tool.poetry.dependencies]
-python = ">=3.8,<3.12"
+python = ">=3.9,<3.13"
 scipy = "^1.10.1"
 
 [tool.poetry.group.dev.dependencies]
 bump2version = "*"
 coverage = "*"
 pytest = ">=7.2.0"
 black = {extras = ["d"], version = "*"}
```

### Comparing `betapert-0.1.2/tests/conftest.py` & `betapert-0.1.3/tests/conftest.py`

 * *Files 25% similar despite different names*

```diff
@@ -10,15 +10,15 @@
         # The mode is very close to the minimum
         (0, 1 / 300, 1),
         # The mode is very close to the maximum
         (0, 299 / 300, 1),
         # Large values
         (1e6, 1e6 + 1, 1e6 + 2),
         # Small values
-        (1e-6, 1e-6 + 1, 1e-6 + 2),
+        (0, 1e-6, 2e-6),
     ],
     ids=lambda x: f"mini={x[0]}, mode={x[1]}, maxi={x[2]}",
 )
 def params(request):
     """Provide required parameters (mini, mode, maxi)"""
     return request.param
```

### Comparing `betapert-0.1.2/tests/test_frozen.py` & `betapert-0.1.3/tests/test_frozen.py`

 * *Files identical despite different names*

### Comparing `betapert-0.1.2/tests/test_generalization.py` & `betapert-0.1.3/tests/test_generalization.py`

 * *Files identical despite different names*

### Comparing `betapert-0.1.2/tests/test_mpert_parametrized.py` & `betapert-0.1.3/tests/test_mpert_parametrized.py`

 * *Files identical despite different names*

### Comparing `betapert-0.1.2/tests/test_special_cases.py` & `betapert-0.1.3/tests/test_special_cases.py`

 * *Files identical despite different names*

### Comparing `betapert-0.1.2/PKG-INFO` & `betapert-0.1.3/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,18 +1,17 @@
 Metadata-Version: 2.1
 Name: betapert
-Version: 0.1.2
+Version: 0.1.3
 Summary: Top-level package for beta-PERT distribution.
 Home-page: https://github.com/tadamcz/betapert
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
 Requires-Dist: scipy (>=1.10.1,<2.0.0)
 Description-Content-Type: text/markdown
 
 This package provides the [PERT](https://en.wikipedia.org/wiki/PERT_distribution) (also known as beta-PERT) distribution.
```


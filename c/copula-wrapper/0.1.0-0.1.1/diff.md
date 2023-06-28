# Comparing `tmp/copula_wrapper-0.1.0.tar.gz` & `tmp/copula_wrapper-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "copula_wrapper-0.1.0.tar", max compression
+gzip compressed data, was "copula_wrapper-0.1.1.tar", max compression
```

## Comparing `copula_wrapper-0.1.0.tar` & `copula_wrapper-0.1.1.tar`

### file list

```diff
@@ -1,21 +1,21 @@
--rw-r--r--   0        0        0     7263 2023-06-28 10:46:09.217336 copula_wrapper-0.1.0/README.md
--rw-r--r--   0        0        0      128 2023-06-27 12:48:32.771037 copula_wrapper-0.1.0/copula_wrapper/__init__.py
--rw-r--r--   0        0        0      771 2023-06-28 10:52:21.748249 copula_wrapper-0.1.0/copula_wrapper/correlation_convert.py
--rw-r--r--   0        0        0     8201 2023-06-28 10:32:47.818642 copula_wrapper-0.1.0/copula_wrapper/joint_distribution.py
--rw-r--r--   0        0        0     1061 2023-06-28 10:28:03.488301 copula_wrapper-0.1.0/pyproject.toml
--rw-r--r--   0        0        0      527 2022-09-15 10:13:48.083787 copula_wrapper-0.1.0/tests/__init__.py
--rw-r--r--   0        0        0     2055 2023-06-28 10:46:58.475889 copula_wrapper-0.1.0/tests/conftest.py
--rw-r--r--   0        0        0      939 2023-06-28 10:46:09.213901 copula_wrapper-0.1.0/tests/e2e/__init__.py
--rw-r--r--   0        0        0      933 2023-06-28 10:46:10.005341 copula_wrapper-0.1.0/tests/e2e/__pycache__/__init__.cpython-310.pyc
--rw-r--r--   0        0        0     2536 2023-06-28 10:49:58.377127 copula_wrapper-0.1.0/tests/e2e/__pycache__/test_8_dimensional.cpython-310-pytest-7.4.0.pyc
--rw-r--r--   0        0        0      512 2023-06-27 17:20:04.541468 copula_wrapper-0.1.0/tests/e2e/__pycache__/test_correlation.cpython-310-pytest-7.4.0.pyc
--rw-r--r--   0        0        0     3323 2023-06-27 17:20:04.544575 copula_wrapper-0.1.0/tests/e2e/__pycache__/test_marginals.cpython-310-pytest-7.4.0.pyc
--rw-r--r--   0        0        0     2481 2023-06-28 10:49:33.844051 copula_wrapper-0.1.0/tests/e2e/test_8_dimensional.py
--rw-r--r--   0        0        0      196 2023-06-27 17:13:42.865027 copula_wrapper-0.1.0/tests/e2e/test_correlation.py
--rw-r--r--   0        0        0     1253 2023-06-27 17:13:42.860059 copula_wrapper-0.1.0/tests/e2e/test_marginals.py
--rw-r--r--   0        0        0    12139 2022-09-15 10:13:48.084054 copula_wrapper-0.1.0/tests/seeds.py
--rw-r--r--   0        0        0      649 2022-09-15 10:13:48.084155 copula_wrapper-0.1.0/tests/shared.py
--rw-r--r--   0        0        0      611 2023-06-27 13:45:29.807228 copula_wrapper-0.1.0/tests/test_copula_param.py
--rw-r--r--   0        0        0      280 2023-06-27 12:49:08.538047 copula_wrapper-0.1.0/tests/test_docs_do_not_raise.py
--rw-r--r--   0        0        0     1242 2023-06-28 08:39:19.526158 copula_wrapper-0.1.0/tests/test_validate_rank_corr.py
--rw-r--r--   0        0        0     7923 1970-01-01 00:00:00.000000 copula_wrapper-0.1.0/PKG-INFO
+-rw-r--r--   0        0        0     7263 2023-06-28 10:46:09.217336 copula_wrapper-0.1.1/README.md
+-rw-r--r--   0        0        0      129 2023-06-28 11:21:57.906760 copula_wrapper-0.1.1/copula_wrapper/__init__.py
+-rw-r--r--   0        0        0      849 2023-06-28 11:21:57.920888 copula_wrapper-0.1.1/copula_wrapper/correlation_convert.py
+-rw-r--r--   0        0        0     8105 2023-06-28 11:21:57.979103 copula_wrapper-0.1.1/copula_wrapper/joint_distribution.py
+-rw-r--r--   0        0        0     1011 2023-06-28 11:26:19.263888 copula_wrapper-0.1.1/pyproject.toml
+-rw-r--r--   0        0        0      527 2022-09-15 10:13:48.083787 copula_wrapper-0.1.1/tests/__init__.py
+-rw-r--r--   0        0        0     2049 2023-06-28 11:21:57.952446 copula_wrapper-0.1.1/tests/conftest.py
+-rw-r--r--   0        0        0      939 2023-06-28 10:46:09.213901 copula_wrapper-0.1.1/tests/e2e/__init__.py
+-rw-r--r--   0        0        0      933 2023-06-28 10:46:10.005341 copula_wrapper-0.1.1/tests/e2e/__pycache__/__init__.cpython-310.pyc
+-rw-r--r--   0        0        0     2536 2023-06-28 10:49:58.377127 copula_wrapper-0.1.1/tests/e2e/__pycache__/test_8_dimensional.cpython-310-pytest-7.4.0.pyc
+-rw-r--r--   0        0        0      512 2023-06-28 11:22:23.484423 copula_wrapper-0.1.1/tests/e2e/__pycache__/test_correlation.cpython-310-pytest-7.4.0.pyc
+-rw-r--r--   0        0        0     3332 2023-06-28 11:22:23.488712 copula_wrapper-0.1.1/tests/e2e/__pycache__/test_marginals.cpython-310-pytest-7.4.0.pyc
+-rw-r--r--   0        0        0     2481 2023-06-28 10:49:33.844051 copula_wrapper-0.1.1/tests/e2e/test_8_dimensional.py
+-rw-r--r--   0        0        0      197 2023-06-28 11:21:57.928787 copula_wrapper-0.1.1/tests/e2e/test_correlation.py
+-rw-r--r--   0        0        0     1352 2023-06-28 11:21:57.948131 copula_wrapper-0.1.1/tests/e2e/test_marginals.py
+-rw-r--r--   0        0        0    12139 2022-09-15 10:13:48.084054 copula_wrapper-0.1.1/tests/seeds.py
+-rw-r--r--   0        0        0      649 2022-09-15 10:13:48.084155 copula_wrapper-0.1.1/tests/shared.py
+-rw-r--r--   0        0        0      679 2023-06-28 11:21:57.941382 copula_wrapper-0.1.1/tests/test_copula_param.py
+-rw-r--r--   0        0        0      280 2023-06-27 12:49:08.538047 copula_wrapper-0.1.1/tests/test_docs_do_not_raise.py
+-rw-r--r--   0        0        0     1242 2023-06-28 08:39:19.526158 copula_wrapper-0.1.1/tests/test_validate_rank_corr.py
+-rw-r--r--   0        0        0     7974 1970-01-01 00:00:00.000000 copula_wrapper-0.1.1/PKG-INFO
```

### Comparing `copula_wrapper-0.1.0/README.md` & `copula_wrapper-0.1.1/README.md`

 * *Files identical despite different names*

### Comparing `copula_wrapper-0.1.0/copula_wrapper/correlation_convert.py` & `copula_wrapper-0.1.1/copula_wrapper/correlation_convert.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,26 +1,26 @@
 import numpy as np
 
 
 def to_pearsons_rho(kendall=None, spearman=None):
-	"""
-	Bivariate Pearson's rho from bivariate rank correlations (Kendall's tau or Spearman's rho).
+    """
+    Bivariate Pearson's rho from bivariate rank correlations (Kendall's tau or Spearman's rho).
 
-	References: https://www.mathworks.com/help/stats/copulas-generate-correlated-samples.html
-	"""
+    References: https://www.mathworks.com/help/stats/copulas-generate-correlated-samples.html
+    """
 
-	if kendall is not None and spearman is not None:
-		raise ValueError("Must provide exactly one of `kendall` or `spearman`.")
+    if kendall is not None and spearman is not None:
+        raise ValueError("Must provide exactly one of `kendall` or `spearman`.")
 
-	if kendall is not None:
-		func = lambda kendalls_tau: np.sin(kendalls_tau * np.pi / 2)
-		arg = kendall
-	elif spearman is not None:
-		func = lambda spearmans_rho: 2 * np.sin(spearmans_rho * np.pi / 6)
-		arg = spearman
-	else:
-		raise ValueError("Must provide exactly one of `kendall` or `spearman`.")
-
-	try:
-		return func(arg)
-	except TypeError:
-		return np.vectorize(func)(arg)
+    if kendall is not None:
+        func = lambda kendalls_tau: np.sin(kendalls_tau * np.pi / 2)
+        arg = kendall
+    elif spearman is not None:
+        func = lambda spearmans_rho: 2 * np.sin(spearmans_rho * np.pi / 6)
+        arg = spearman
+    else:
+        raise ValueError("Must provide exactly one of `kendall` or `spearman`.")
+
+    try:
+        return func(arg)
+    except TypeError:
+        return np.vectorize(func)(arg)
```

### Comparing `copula_wrapper-0.1.0/copula_wrapper/joint_distribution.py` & `copula_wrapper-0.1.1/copula_wrapper/joint_distribution.py`

 * *Files 2% similar despite different names*

```diff
@@ -49,32 +49,28 @@
         # For extensibility
         # So in the future, the family could be given as a string argument, e.g. "Clayton" or "StudentT"
         # The reason I haven't done this yet is that it would make the signature more complicated,
         # and require even more argument parsing code.
         # In terms of the copulas currently supported by statsmodels:
         # - For the archimedean copulas, rank correlation would need to be given as a single float.
         # - For the StudentT copula, an additional parameter of degrees of freedom would need to be given.
-        CopulaClass = getattr(
-            statsmodels.distributions.copula.api, self.family + "Copula"
-        )
+        CopulaClass = getattr(statsmodels.distributions.copula.api, self.family + "Copula")
 
         rank_corr = filter_none(spearman_rho=spearman_rho, kendall_tau=kendall_tau)
 
         if rank_corr.keys() == {"spearman_rho"}:
             marginals, spearman_rho = self._parse_init_args(marginals, spearman_rho)
             # This line would need to be changed if we added more copula families
             copula_corr = to_pearsons_rho(spearman=spearman_rho)
         elif rank_corr.keys() == {"kendall_tau"}:
             marginals, kendall_tau = self._parse_init_args(marginals, kendall_tau)
             # The appropriate correlation measure for the copula. For extensibility.
             copula_corr = CopulaClass()._arg_from_tau(kendall_tau)
         else:
-            raise ValueError(
-                f"Must provide exactly one of `spearman_rho` or `kendall_tau`."
-            )
+            raise ValueError(f"Must provide exactly one of `spearman_rho` or `kendall_tau`.")
 
         copula = CopulaClass(copula_corr)
         self._wrapped = CopulaDistribution(copula, marginals)
 
     def rvs(self, size=1, random_state=None):
         array = self._wrapped.rvs(nobs=size, random_state=random_state)
         if self.idx_to_name:
@@ -110,17 +106,15 @@
                 raise ValueError(
                     "Cannot provide an array argument when marginals were given as a dict."
                 )
             return x
         else:
             raise TypeError(f"Expected dict or Sequence, got {type(x)}.")
 
-    def _parse_init_args(
-        self, marginals, rank_corr
-    ) -> tuple[list[rv_frozen], np.ndarray[Real]]:
+    def _parse_init_args(self, marginals, rank_corr) -> tuple[list[rv_frozen], np.ndarray[Real]]:
         """
         Parses arguments to the constructor, checks their validity, and converts them to the form
         expected by statsmodels.
         """
         n_dimensions = len(marginals)
         if n_dimensions < 2:
             raise ValueError("Must provide at least two marginals.")
@@ -128,17 +122,15 @@
         got_named = self.idx_to_name is not None and isinstance(rank_corr, dict)
         try:
             np.asarray(rank_corr)
             got_positional = self.idx_to_name is None
         except TypeError:
             got_positional = False
         if not xor(got_named, got_positional):
-            raise ValueError(
-                "Must provide marginals and rank correlation in the same format."
-            )
+            raise ValueError("Must provide marginals and rank correlation in the same format.")
 
         if got_named:
             self._validate_corr_dict(rank_corr)
             rank_corr = self._to_matrix(rank_corr)
             marginals = list(marginals.values())
         if got_positional:
             rank_corr = np.asarray(rank_corr)
```

### Comparing `copula_wrapper-0.1.0/pyproject.toml` & `copula_wrapper-0.1.1/pyproject.toml`

 * *Files 16% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 [tool]
 [tool.poetry]
 name = "copula_wrapper"
-version = "0.1.0"
+version = "0.1.1"
 homepage = "https://github.com/tadamcz/copula-wrapper"
 description = "Top-level package for statsmodels copula wrapper."
 authors = ["Tom Adamczewski <tadamczewskipublic@gmail.com>"]
 readme = "README.md"
 classifiers=[
     'Natural Language :: English',
     'Programming Language :: Python :: 3',
@@ -13,27 +13,27 @@
 packages = [
     { include = "copula_wrapper" },
     { include = "tests", format = "sdist" },
 ]
 
 
 [tool.poetry.dependencies]
-python = ">=3.9,<3.11"
+python = ">=3.9,<3.13"
 scipy = "^1.11.0"
 numpy = "^1.23.0"
 pandas = "^1.4.3"
 statsmodels = "^0.13.2"
 
 [tool.poetry.group.dev.dependencies]
 bump2version = "*"
 coverage = "*"
 pytest = ">=7.2.0"
 pytest-pycharm = "*"
 pytest-xdist = "^2.5.0"
-nonstd = { git = "https://github.com/tadamcz/nonstd", rev = "main" }
+rvtools = "^0.1.2"
 black = {extras = ["d"], version = "*"}
 matplotlib = "^3.7.1"
 mkcodes = "^0.1.1"
 seaborn = "^0.11.2"
 vulture = "^2.7"
```

### Comparing `copula_wrapper-0.1.0/tests/__init__.py` & `copula_wrapper-0.1.1/tests/__init__.py`

 * *Files identical despite different names*

### Comparing `copula_wrapper-0.1.0/tests/conftest.py` & `copula_wrapper-0.1.1/tests/conftest.py`

 * *Files 1% similar despite different names*

```diff
@@ -67,17 +67,15 @@
     ],
     ids=lambda rs: f"pairwise_corrs={rs}",
 )
 def rank_corr(request):
     return request.param
 
 
-@pytest.fixture(
-    params=["spearman_rho", "kendall_tau"], ids=lambda p: f"rank_corr_measure={p}"
-)
+@pytest.fixture(params=["spearman_rho", "kendall_tau"], ids=lambda p: f"rank_corr_measure={p}")
 def rank_corr_measure(request):
     return request.param
 
 
 @pytest.fixture
 def joint_distribution(marginals, rank_corr, rank_corr_measure):
     return CopulaJoint(marginals, **{rank_corr_measure: rank_corr})
```

### Comparing `copula_wrapper-0.1.0/tests/e2e/__init__.py` & `copula_wrapper-0.1.1/tests/e2e/__init__.py`

 * *Files identical despite different names*

### Comparing `copula_wrapper-0.1.0/tests/e2e/__pycache__/__init__.cpython-310.pyc` & `copula_wrapper-0.1.1/tests/e2e/__pycache__/__init__.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `copula_wrapper-0.1.0/tests/e2e/__pycache__/test_8_dimensional.cpython-310-pytest-7.4.0.pyc` & `copula_wrapper-0.1.1/tests/e2e/__pycache__/test_8_dimensional.cpython-310-pytest-7.4.0.pyc`

 * *Files identical despite different names*

### Comparing `copula_wrapper-0.1.0/tests/e2e/__pycache__/test_correlation.cpython-310-pytest-7.4.0.pyc` & `copula_wrapper-0.1.1/tests/e2e/__pycache__/test_correlation.cpython-310-pytest-7.4.0.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.10, timestamp-based, .py timestamp: Tue Jun 27 17:13:42 2023 UTC, .py size: 196 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 4% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 6f0d 0d0a 0000 0000 c618 9b64 c400 0000  o..........d....
+00000000: 6f0d 0d0a 0000 0000 d517 9c64 c500 0000  o..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0002 0000 0040 0000 0073 3200 0000 6400  .....@...s2...d.
 00000030: 6401 6c00 5a01 6400 6401 6c02 6d03 0200  d.l.Z.d.d.l.m...
 00000040: 0100 6d04 5a05 0100 6400 6402 6c06 6d07  ..m.Z...d.d.l.m.
 00000050: 5a07 0100 6403 6404 8400 5a08 6401 5300  Z...d.d...Z.d.S.
 00000060: 2905 e900 0000 004e a901 da10 6173 7365  )......N....asse
 00000070: 7274 5f72 616e 6b5f 636f 7272 6303 0000  rt_rank_corrc...
```

### Comparing `copula_wrapper-0.1.0/tests/e2e/__pycache__/test_marginals.cpython-310-pytest-7.4.0.pyc` & `copula_wrapper-0.1.1/tests/e2e/__pycache__/test_marginals.cpython-310-pytest-7.4.0.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.10, timestamp-based, .py timestamp: Tue Jun 27 17:13:42 2023 UTC, .py size: 1253 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 6f0d 0d0a 0000 0000 c618 9b64 e504 0000  o..........d....
+00000000: 6f0d 0d0a 0000 0000 d517 9c64 4805 0000  o..........dH...
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0002 0000 0040 0000 0073 7600 0000 6400  .....@...sv...d.
 00000030: 6401 6c00 5a01 6400 6401 6c02 6d03 0200  d.l.Z.d.d.l.m...
 00000040: 0100 6d04 5a05 0100 6400 6401 6c06 5a07  ..m.Z...d.d.l.Z.
 00000050: 6400 6402 6c08 6d09 5a09 0100 6400 6403  d.d.l.m.Z...d.d.
 00000060: 6c0a 6d0b 5a0b 0100 6400 6401 6c0c 5a0d  l.m.Z...d.d.l.Z.
 00000070: 6400 6404 6c0e 6d0f 5a0f 0100 6400 6405  d.d.l.m.Z...d.d.
@@ -126,83 +126,84 @@
 000007d0: 7473 2f65 3265 2f74 6573 745f 6d61 7267  ts/e2e/test_marg
 000007e0: 696e 616c 732e 7079 da0b 7465 7374 5f64  inals.py..test_d
 000007f0: 6f6d 6169 6e0a 0000 0073 1200 0000 1201  omain....s......
 00000800: 0801 0c01 c001 0e01 fe01 c600 0280 04fb  ................
 00000810: 7234 0000 0063 0200 0000 0000 0000 0000  r4...c..........
 00000820: 0000 0200 0000 0500 0000 4300 0000 7312  ..........C...s.
 00000830: 0000 0074 007c 007c 0164 0164 028d 0301  ...t.|.|.d.d....
-00000840: 0064 0353 0029 047a 9a0a 0954 6865 204b  .d.S.).z...The K
-00000850: 6f6c 6d6f 676f 726f 762d 536d 6972 6e6f  olmogorov-Smirno
-00000860: 7620 7374 6174 6973 7469 6320 6973 2074  v statistic is t
-00000870: 6865 096d 6178 696d 756d 2076 6572 7469  he.maximum verti
-00000880: 6361 6c20 6469 7374 616e 6365 2062 6574  cal distance bet
-00000890: 7765 656e 2074 6865 2065 6d70 6972 6963  ween the empiric
-000008a0: 616c 2043 4446 2061 6e64 2074 6865 2074  al CDF and the t
-000008b0: 6865 6f72 6574 6963 616c 2043 4446 2e0a  heoretical CDF..
-000008c0: 0a09 4974 2773 2074 6865 7265 666f 7265  ..It's therefore
-000008d0: 2062 6574 7765 656e 2030 2061 6e64 2031   between 0 and 1
-000008e0: 2e0a 09e7 fca9 f1d2 4d62 603f a901 da03  ........Mb`?....
-000008f0: 746f 6c4e 7205 0000 0029 0272 2500 0000  tolNr....).r%...
-00000900: 7226 0000 0072 3200 0000 7232 0000 0072  r&...r2...r2...r
-00000910: 3300 0000 da17 7465 7374 5f6b 6f6c 6d6f  3.....test_kolmo
-00000920: 676f 726f 765f 736d 6972 6e6f 7613 0000  gorov_smirnov...
-00000930: 0073 0200 0000 1206 7238 0000 0063 0100  .s......r8...c..
-00000940: 0000 0000 0000 0000 0000 0c00 0000 0700  ................
-00000950: 0000 4300 0000 7326 0100 0064 017d 0174  ..C...s&...d.}.t
-00000960: 00a0 0164 0264 02a1 0274 00a0 0264 0364  ...d.d...t...d.d
-00000970: 04a1 0274 037c 0183 0164 059c 037d 0264  ...t.|...d...}.d
-00000980: 0664 0769 017d 0374 047c 0266 0169 007c  .d.i.}.t.|.f.i.|
-00000990: 007c 0369 01a4 018e 017d 047c 04a0 0564  .|.i.....}.|...d
-000009a0: 08a1 017d 0574 066a 077d 067c 0564 0919  ...}.t.j.}.|.d..
-000009b0: 007d 077c 077c 016b 027d 087c 067c 0883  .}.|.|.k.}.|.|..
-000009c0: 017d 097c 0973 7f74 08a0 0964 0a7c 0866  .}.|.s.t...d.|.f
-000009d0: 0164 0b7c 077c 0166 02a1 0474 08a0 0a7c  .d.|.|.f...t...|
-000009e0: 07a1 0164 0c74 0ba0 0ca1 0076 0073 4f74  ...d.t.....v.sOt
-000009f0: 08a0 0d7c 01a1 0172 5474 08a0 0a7c 01a1  ...|...rTt...|..
-00000a00: 016e 0164 0c64 0d9c 0216 007d 0a64 0e64  .n.d.d.....}.d.d
-00000a10: 0f74 0ba0 0ca1 0076 0073 6574 08a0 0d74  .t.....v.set...t
-00000a20: 06a1 0172 6a74 08a0 0a74 06a1 016e 0164  ...rjt...t...n.d
-00000a30: 0f74 08a0 0a7c 06a1 017c 0a74 08a0 0a7c  .t...|...|.t...|
-00000a40: 09a1 0164 109c 0416 007d 0b74 0e74 08a0  ...d.....}.t.t..
-00000a50: 0f7c 0ba1 0183 0182 0164 0004 007d 0604  .|.......d...}..
-00000a60: 007d 0704 007d 087d 097c 0264 093d 0074  .}...}.}.|.d.=.t
-00000a70: 107c 057c 0264 1164 128d 0301 0064 0053  .|.|.d.d.....d.S
-00000a80: 0029 134e 67ae 47e1 7a14 aef3 3f72 1200  .).Ng.G.z...?r..
-00000a90: 0000 e902 0000 00e9 0300 0000 2903 da01  ............)...
-00000aa0: 6eda 0162 da09 6365 7274 6169 6e74 7929  n..b..certainty)
-00000ab0: 0272 3b00 0000 723d 0000 0067 e17a 14ae  .r;...r=...g.z..
-00000ac0: 47e1 da3f 6940 420f 0072 3d00 0000 2901  G..?i@B..r=...).
-00000ad0: fa02 3d3d 2901 7a12 2528 7079 3429 7320  ..==).z.%(py4)s 
-00000ae0: 3d3d 2025 2870 7936 2973 da05 5641 4c55  == %(py6)s..VALU
-00000af0: 4529 0272 1400 0000 720a 0000 0072 0b00  E).r....r....r..
-00000b00: 0000 720c 0000 0072 0d00 0000 7235 0000  ..r....r....r5..
-00000b10: 0072 3600 0000 2911 7203 0000 00da 046e  .r6...).r......n
-00000b20: 6f72 6dda 0462 6574 6172 0200 0000 7204  orm..betar....r.
-00000b30: 0000 00da 0372 7673 720c 0000 0072 1a00  .....rvsr....r..
-00000b40: 0000 721b 0000 0072 1c00 0000 7220 0000  ..r....r....r ..
-00000b50: 0072 1d00 0000 721e 0000 0072 1f00 0000  .r....r....r....
-00000b60: 7221 0000 0072 2200 0000 7206 0000 0029  r!...r"...r....)
-00000b70: 0cda 1172 616e 6b5f 636f 7272 5f6d 6561  ...rank_corr_mea
-00000b80: 7375 7265 723f 0000 0072 2600 0000 da09  surer?...r&.....
-00000b90: 7261 6e6b 5f63 6f72 725a 026a 6472 2500  rank_corrZ.jdr%.
-00000ba0: 0000 7229 0000 0072 2f00 0000 722a 0000  ..r)...r/...r*..
-00000bb0: 0072 2c00 0000 722d 0000 0072 2e00 0000  .r,...r-...r....
-00000bc0: 7232 0000 0072 3200 0000 7233 0000 00da  r2...r2...r3....
-00000bd0: 0e74 6573 745f 6365 7274 6169 6e74 791c  .test_certainty.
-00000be0: 0000 0073 1600 0000 0401 0a02 0a01 0601  ...s............
-00000bf0: 06fd 0805 1401 0a01 c402 0602 1201 7245  ..............rE
-00000c00: 0000 0029 15da 0862 7569 6c74 696e 7372  ...)...builtinsr
-00000c10: 1d00 0000 da19 5f70 7974 6573 742e 6173  ......_pytest.as
-00000c20: 7365 7274 696f 6e2e 7265 7772 6974 65da  sertion.rewrite.
-00000c30: 0961 7373 6572 7469 6f6e da07 7265 7772  .assertion..rewr
-00000c40: 6974 6572 1b00 0000 da05 6e75 6d70 7972  iter......numpyr
-00000c50: 0c00 0000 5a14 6e6f 6e73 7464 2e64 6973  ....Z.nonstd.dis
-00000c60: 7472 6962 7574 696f 6e73 7202 0000 00da  tributionsr.....
-00000c70: 0573 6369 7079 7203 0000 005a 0c74 6573  .scipyr....Z.tes
-00000c80: 7473 2e73 6861 7265 6472 1800 0000 da0e  ts.sharedr......
-00000c90: 636f 7075 6c61 5f77 7261 7070 6572 7204  copula_wrapperr.
-00000ca0: 0000 005a 0974 6573 7473 2e65 3265 7206  ...Z.tests.e2er.
-00000cb0: 0000 0072 3400 0000 7238 0000 0072 4500  ...r4...r8...rE.
-00000cc0: 0000 7232 0000 0072 3200 0000 7232 0000  ..r2...r2...r2..
-00000cd0: 0072 3300 0000 da08 3c6d 6f64 756c 653e  .r3.....<module>
-00000ce0: 0100 0000 7312 0000 0022 000c 010c 0108  ....s...."......
-00000cf0: 020c 010c 0108 0308 090c 09              ...........
+00000840: 0064 0353 0029 047a a30a 2020 2020 5468  .d.S.).z..    Th
+00000850: 6520 4b6f 6c6d 6f67 6f72 6f76 2d53 6d69  e Kolmogorov-Smi
+00000860: 726e 6f76 2073 7461 7469 7374 6963 2069  rnov statistic i
+00000870: 7320 7468 6509 6d61 7869 6d75 6d20 7665  s the.maximum ve
+00000880: 7274 6963 616c 2064 6973 7461 6e63 6520  rtical distance 
+00000890: 6265 7477 6565 6e20 7468 6520 656d 7069  between the empi
+000008a0: 7269 6361 6c20 4344 4620 616e 6420 7468  rical CDF and th
+000008b0: 6520 7468 656f 7265 7469 6361 6c20 4344  e theoretical CD
+000008c0: 462e 0a0a 2020 2020 4974 2773 2074 6865  F...    It's the
+000008d0: 7265 666f 7265 2062 6574 7765 656e 2030  refore between 0
+000008e0: 2061 6e64 2031 2e0a 2020 2020 e7fc a9f1   and 1..    ....
+000008f0: d24d 6260 3fa9 01da 0374 6f6c 4e72 0500  .Mb`?....tolNr..
+00000900: 0000 2902 7225 0000 0072 2600 0000 7232  ..).r%...r&...r2
+00000910: 0000 0072 3200 0000 7233 0000 00da 1774  ...r2...r3.....t
+00000920: 6573 745f 6b6f 6c6d 6f67 6f72 6f76 5f73  est_kolmogorov_s
+00000930: 6d69 726e 6f76 1300 0000 7302 0000 0012  mirnov....s.....
+00000940: 0672 3800 0000 6301 0000 0000 0000 0000  .r8...c.........
+00000950: 0000 000c 0000 0007 0000 0043 0000 0073  ...........C...s
+00000960: 2601 0000 6401 7d01 7400 a001 6402 6402  &...d.}.t...d.d.
+00000970: a102 7400 a002 6403 6404 a102 7403 7c01  ..t...d.d...t.|.
+00000980: 8301 6405 9c03 7d02 6406 6407 6901 7d03  ..d...}.d.d.i.}.
+00000990: 7404 7c02 6601 6900 7c00 7c03 6901 a401  t.|.f.i.|.|.i...
+000009a0: 8e01 7d04 7c04 a005 6408 a101 7d05 7406  ..}.|...d...}.t.
+000009b0: 6a07 7d06 7c05 6409 1900 7d07 7c07 7c01  j.}.|.d...}.|.|.
+000009c0: 6b02 7d08 7c06 7c08 8301 7d09 7c09 737f  k.}.|.|...}.|.s.
+000009d0: 7408 a009 640a 7c08 6601 640b 7c07 7c01  t...d.|.f.d.|.|.
+000009e0: 6602 a104 7408 a00a 7c07 a101 640c 740b  f...t...|...d.t.
+000009f0: a00c a100 7600 734f 7408 a00d 7c01 a101  ....v.sOt...|...
+00000a00: 7254 7408 a00a 7c01 a101 6e01 640c 640d  rTt...|...n.d.d.
+00000a10: 9c02 1600 7d0a 640e 640f 740b a00c a100  ....}.d.d.t.....
+00000a20: 7600 7365 7408 a00d 7406 a101 726a 7408  v.set...t...rjt.
+00000a30: a00a 7406 a101 6e01 640f 7408 a00a 7c06  ..t...n.d.t...|.
+00000a40: a101 7c0a 7408 a00a 7c09 a101 6410 9c04  ..|.t...|...d...
+00000a50: 1600 7d0b 740e 7408 a00f 7c0b a101 8301  ..}.t.t...|.....
+00000a60: 8201 6400 0400 7d06 0400 7d07 0400 7d08  ..d...}...}...}.
+00000a70: 7d09 7c02 6409 3d00 7410 7c05 7c02 6411  }.|.d.=.t.|.|.d.
+00000a80: 6412 8d03 0100 6400 5300 2913 4e67 ae47  d.....d.S.).Ng.G
+00000a90: e17a 14ae f33f 7212 0000 00e9 0200 0000  .z...?r.........
+00000aa0: e903 0000 0029 03da 016e da01 62da 0963  .....)...n..b..c
+00000ab0: 6572 7461 696e 7479 2902 723b 0000 0072  ertainty).r;...r
+00000ac0: 3d00 0000 67e1 7a14 ae47 e1da 3f69 4042  =...g.z..G..?i@B
+00000ad0: 0f00 723d 0000 0029 01fa 023d 3d29 017a  ..r=...)...==).z
+00000ae0: 1225 2870 7934 2973 203d 3d20 2528 7079  .%(py4)s == %(py
+00000af0: 3629 73da 0556 414c 5545 2902 7214 0000  6)s..VALUE).r...
+00000b00: 0072 0a00 0000 720b 0000 0072 0c00 0000  .r....r....r....
+00000b10: 720d 0000 0072 3500 0000 7236 0000 0029  r....r5...r6...)
+00000b20: 1172 0300 0000 da04 6e6f 726d da04 6265  .r......norm..be
+00000b30: 7461 7202 0000 0072 0400 0000 da03 7276  tar....r......rv
+00000b40: 7372 0c00 0000 721a 0000 0072 1b00 0000  sr....r....r....
+00000b50: 721c 0000 0072 2000 0000 721d 0000 0072  r....r ...r....r
+00000b60: 1e00 0000 721f 0000 0072 2100 0000 7222  ....r....r!...r"
+00000b70: 0000 0072 0600 0000 290c da11 7261 6e6b  ...r....)...rank
+00000b80: 5f63 6f72 725f 6d65 6173 7572 6572 3f00  _corr_measurer?.
+00000b90: 0000 7226 0000 00da 0972 616e 6b5f 636f  ..r&.....rank_co
+00000ba0: 7272 5a02 6a64 7225 0000 0072 2900 0000  rrZ.jdr%...r)...
+00000bb0: 722f 0000 0072 2a00 0000 722c 0000 0072  r/...r*...r,...r
+00000bc0: 2d00 0000 722e 0000 0072 3200 0000 7232  -...r....r2...r2
+00000bd0: 0000 0072 3300 0000 da0e 7465 7374 5f63  ...r3.....test_c
+00000be0: 6572 7461 696e 7479 1c00 0000 7316 0000  ertainty....s...
+00000bf0: 0004 010a 020a 0106 0106 fd08 0514 010a  ................
+00000c00: 01c4 0206 0212 0172 4500 0000 2915 da08  .......rE...)...
+00000c10: 6275 696c 7469 6e73 721d 0000 00da 195f  builtinsr......_
+00000c20: 7079 7465 7374 2e61 7373 6572 7469 6f6e  pytest.assertion
+00000c30: 2e72 6577 7269 7465 da09 6173 7365 7274  .rewrite..assert
+00000c40: 696f 6eda 0772 6577 7269 7465 721b 0000  ion..rewriter...
+00000c50: 00da 056e 756d 7079 720c 0000 005a 146e  ...numpyr....Z.n
+00000c60: 6f6e 7374 642e 6469 7374 7269 6275 7469  onstd.distributi
+00000c70: 6f6e 7372 0200 0000 da05 7363 6970 7972  onsr......scipyr
+00000c80: 0300 0000 5a0c 7465 7374 732e 7368 6172  ....Z.tests.shar
+00000c90: 6564 7218 0000 00da 0e63 6f70 756c 615f  edr......copula_
+00000ca0: 7772 6170 7065 7272 0400 0000 5a09 7465  wrapperr....Z.te
+00000cb0: 7374 732e 6532 6572 0600 0000 7234 0000  sts.e2er....r4..
+00000cc0: 0072 3800 0000 7245 0000 0072 3200 0000  .r8...rE...r2...
+00000cd0: 7232 0000 0072 3200 0000 7233 0000 00da  r2...r2...r3....
+00000ce0: 083c 6d6f 6475 6c65 3e01 0000 0073 1200  .<module>....s..
+00000cf0: 0000 2200 0c01 0c01 0802 0c01 0c01 0803  ..".............
+00000d00: 0809 0c09                                ....
```

### Comparing `copula_wrapper-0.1.0/tests/e2e/test_8_dimensional.py` & `copula_wrapper-0.1.1/tests/e2e/test_8_dimensional.py`

 * *Files identical despite different names*

### Comparing `copula_wrapper-0.1.0/tests/seeds.py` & `copula_wrapper-0.1.1/tests/seeds.py`

 * *Files identical despite different names*

### Comparing `copula_wrapper-0.1.0/tests/shared.py` & `copula_wrapper-0.1.1/tests/shared.py`

 * *Files identical despite different names*

### Comparing `copula_wrapper-0.1.0/tests/test_copula_param.py` & `copula_wrapper-0.1.1/tests/test_copula_param.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,21 +1,25 @@
 import pytest
 
 from copula_wrapper import correlation_convert
 
 
-@pytest.fixture(params=['spearman', 'kendall'], ids=lambda p: f"method={p}")
+@pytest.fixture(params=["spearman", "kendall"], ids=lambda p: f"method={p}")
 def corr_method(request):
-	return request.param
+    return request.param
 
 
 @pytest.fixture(params=[0, 1], ids=lambda p: f"corr={p}")
 def extremes_corr(request):
-	return request.param
+    return request.param
 
 
 def test_extremes(corr_method, extremes_corr):
-	if corr_method == 'kendall':
-		assert correlation_convert.to_pearsons_rho(kendall=extremes_corr) == pytest.approx(extremes_corr)
-
-	if corr_method == 'spearman':
-		assert correlation_convert.to_pearsons_rho(spearman=extremes_corr) == pytest.approx(extremes_corr)
+    if corr_method == "kendall":
+        assert correlation_convert.to_pearsons_rho(kendall=extremes_corr) == pytest.approx(
+            extremes_corr
+        )
+
+    if corr_method == "spearman":
+        assert correlation_convert.to_pearsons_rho(spearman=extremes_corr) == pytest.approx(
+            extremes_corr
+        )
```

### Comparing `copula_wrapper-0.1.0/tests/test_validate_rank_corr.py` & `copula_wrapper-0.1.1/tests/test_validate_rank_corr.py`

 * *Files identical despite different names*

### Comparing `copula_wrapper-0.1.0/PKG-INFO` & `copula_wrapper-0.1.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,19 +1,20 @@
 Metadata-Version: 2.1
 Name: copula-wrapper
-Version: 0.1.0
+Version: 0.1.1
 Summary: Top-level package for statsmodels copula wrapper.
 Home-page: https://github.com/tadamcz/copula-wrapper
 Author: Tom Adamczewski
 Author-email: tadamczewskipublic@gmail.com
-Requires-Python: >=3.9,<3.11
+Requires-Python: >=3.9,<3.13
 Classifier: Natural Language :: English
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 Requires-Dist: numpy (>=1.23.0,<2.0.0)
 Requires-Dist: pandas (>=1.4.3,<2.0.0)
 Requires-Dist: scipy (>=1.11.0,<2.0.0)
 Requires-Dist: statsmodels (>=0.13.2,<0.14.0)
 Description-Content-Type: text/markdown
 
 Suppose we want to specify a continuous `n`-dimensional joint probability distribution by giving:
```


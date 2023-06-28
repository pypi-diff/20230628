# Comparing `tmp/p2g-0.1.95.tar.gz` & `tmp/p2g-0.2.29.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "p2g-0.1.95.tar", max compression
+gzip compressed data, was "p2g-0.2.29.tar", max compression
```

## Comparing `p2g-0.1.95.tar` & `p2g-0.2.29.tar`

### file list

```diff
@@ -1,80 +1,41 @@
--rwxr-xr-x   0        0        0    37659 2023-06-05 00:48:44.920564 p2g-0.1.95/README.rst
--rwxr-xr-x   0        0        0     1176 2023-06-05 00:34:28.494786 p2g-0.1.95/p2g/__init__.py
--rwxr-xr-x   0        0        0       28 2023-06-05 00:34:28.494786 p2g-0.1.95/p2g/__main__.py
--rwxr-xr-x   0        0        0      727 2023-06-05 00:34:28.494786 p2g-0.1.95/p2g/axis.py
--rwxr-xr-x   0        0        0     1116 2023-06-05 00:34:28.494786 p2g-0.1.95/p2g/builtin.py
--rwxr-xr-x   0        0        0     3433 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/coords.py
--rw-r--r--   0        0        0     3392 2023-06-05 00:36:50.149728 p2g-0.1.95/p2g/debug.py
--rwxr-xr-x   0        0        0       19 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/doc/authors.org
--rwxr-xr-x   0        0        0       52 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/doc/authors.rst
--rwxr-xr-x   0        0        0     6302 2023-06-05 00:44:28.647246 p2g-0.1.95/p2g/doc/haas.org
--rwxr-xr-x   0        0        0    16060 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/doc/haas.txt
--rw-r--r--   0        0        0    23868 2023-06-05 00:48:35.872376 p2g-0.1.95/p2g/doc/readme.md
--rwxr-xr-x   0        0        0    25481 2023-06-05 00:48:34.032338 p2g-0.1.95/p2g/doc/readme.org
--rwxr-xr-x   0        0        0    37659 2023-06-05 00:48:42.764519 p2g-0.1.95/p2g/doc/readme.rst
--rwxr-xr-x   0        0        0     2544 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/err.py
--rwxr-xr-x   0        0        0     2835 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/examples/csearch.py
--rwxr-xr-x   0        0        0     2735 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/examples/defs.py
--rwxr-xr-x   0        0        0     1853 2023-06-05 00:44:30.363281 p2g-0.1.95/p2g/examples/probecalibrate.nc
--rwxr-xr-x   0        0        0     1099 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/examples/probecalibrate.py
--rwxr-xr-x   0        0        0     9503 2023-06-05 00:44:29.931272 p2g-0.1.95/p2g/examples/vicecenter.nc
--rwxr-xr-x   0        0        0     4094 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/examples/vicecenter.py
--rwxr-xr-x   0        0        0     1397 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/gbl.py
--rwxr-xr-x   0        0        0     3683 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/goto.py
--rw-r--r--   0        0        0     6899 2023-06-05 00:44:29.467263 p2g-0.1.95/p2g/haas.py
--rwxr-xr-x   0        0        0     3506 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/lib.py
--rwxr-xr-x   0        0        0     4589 2023-06-05 00:38:17.119534 p2g-0.1.95/p2g/main.py
--rwxr-xr-x   0        0        0    16200 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/makestdvars.py
--rwxr-xr-x   0        0        0    21488 2023-06-04 23:59:54.699683 p2g-0.1.95/p2g/mvarsorig
--rwxr-xr-x   0        0        0      687 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/nd.py
--rwxr-xr-x   0        0        0    13765 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/op.py
--rwxr-xr-x   0        0        0      621 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/opinfo.py
--rwxr-xr-x   0        0        0     6945 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/ptest.py
--rwxr-xr-x   0        0        0     3267 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/scalar.py
--rwxr-xr-x   0        0        0     7098 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/stat.py
--rwxr-xr-x   0        0        0     1859 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/symbol.py
--rwxr-xr-x   0        0        0      222 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/conftest.py
--rwxr-xr-x   0        0        0       24 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/dummy.py
--rw-r--r--   0        0        0       46 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/golden/error_forcefail1.nc
--rw-r--r--   0        0        0        5 2023-06-05 00:44:39.415469 p2g-0.1.95/p2g/tests/golden/error_xfail_force_fail.nc
--rwxr-xr-x   0        0        0        3 2023-06-05 00:44:41.715517 p2g-0.1.95/p2g/tests/golden/meta_simple_xfail1.nc
--rw-r--r--   0        0        0       44 2023-06-05 00:44:41.727517 p2g-0.1.95/p2g/tests/golden/meta_transitory_golden.nc
--rwxr-xr-x   0        0        0     1587 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/golden/probecalibrate.nc
--rwxr-xr-x   0        0        0     8407 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/golden/vicecenter.nc
--rwxr-xr-x   0        0        0      176 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/not_pytest.py
--rwxr-xr-x   0        0        0     2579 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_axes.py
--rwxr-xr-x   0        0        0      553 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_basic.py
--rwxr-xr-x   0        0        0     6290 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_builtins.py
--rwxr-xr-x   0        0        0      205 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_comment.py
--rwxr-xr-x   0        0        0     5351 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_coords.py
--rwxr-xr-x   0        0        0      476 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_edge.py
--rwxr-xr-x   0        0        0     3279 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_error.py
--rwxr-xr-x   0        0        0      547 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_example.py
--rwxr-xr-x   0        0        0      769 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_expr.py
--rwxr-xr-x   0        0        0     1822 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_for.py
--rwxr-xr-x   0        0        0     4998 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_func.py
--rwxr-xr-x   0        0        0     1705 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_goto.py
--rwxr-xr-x   0        0        0       48 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_gvar.py
--rwxr-xr-x   0        0        0     7255 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_interp.py
--rwxr-xr-x   0        0        0      545 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_linenos.py
--rwxr-xr-x   0        0        0     3637 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_main.py
--rwxr-xr-x   0        0        0      513 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_makestdvars.py
--rwxr-xr-x   0        0        0     1947 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_meta.py
--rwxr-xr-x   0        0        0     1637 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_nt1.py
--rwxr-xr-x   0        0        0     6522 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_op.py
--rwxr-xr-x   0        0        0     9020 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_smoke.py
--rwxr-xr-x   0        0        0     1070 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_str.py
--rwxr-xr-x   0        0        0     1276 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_tuple.py
--rwxr-xr-x   0        0        0     4411 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_vars.py
--rwxr-xr-x   0        0        0     9536 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/tests/test_vector.py
--rwxr-xr-x   0        0        0     1310 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/thanksto
--rwxr-xr-x   0        0        0     6116 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/vector.py
--rwxr-xr-x   0        0        0       23 2023-06-05 00:49:03.496949 p2g-0.1.95/p2g/version.py
--rwxr-xr-x   0        0        0      856 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/visible.py
--rwxr-xr-x   0        0        0    11831 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/walk.py
--rwxr-xr-x   0        0        0     3165 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/walkbase.py
--rwxr-xr-x   0        0        0     4734 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/walkexpr.py
--rwxr-xr-x   0        0        0     6576 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/walkfunc.py
--rwxr-xr-x   0        0        0     3580 2023-06-05 00:34:28.498787 p2g-0.1.95/p2g/walkns.py
--rwxr-xr-x   0        0        0     3895 2023-06-05 00:49:03.232944 p2g-0.1.95/pyproject.toml
--rw-r--r--   0        0        0    37765 1970-01-01 00:00:00.000000 p2g-0.1.95/PKG-INFO
+-rwxr-xr-x   0        0        0     1393 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/__init__.py
+-rw-r--r--   0        0        0       34 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/__main__.py
+-rwxr-xr-x   0        0        0      689 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/axis.py
+-rwxr-xr-x   0        0        0     1215 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/builtin.py
+-rwxr-xr-x   0        0        0     3359 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/coords.py
+-rwxr-xr-x   0        0        0       16 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/doc/authors.org
+-rw-r--r--   0        0        0    12120 2023-06-28 04:33:05.268181 p2g-0.2.29/p2g/doc/haas.org
+-rw-r--r--   0        0        0    16060 2023-06-28 04:33:05.900186 p2g-0.2.29/p2g/doc/haas.txt
+-rw-r--r--   0        0        0     1075 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/doc/license.org
+-rwxr-xr-x   0        0        0    40665 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/doc/readme.org
+-rw-r--r--   0        0        0    41409 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/doc/readme.txt
+-rwxr-xr-x   0        0        0     2403 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/err.py
+-rwxr-xr-x   0        0        0     2732 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/examples/csearch.py
+-rwxr-xr-x   0        0        0     2764 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/examples/defs.py
+-rw-r--r--   0        0        0     1883 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/examples/probecalibrate.nc
+-rwxr-xr-x   0        0        0     1174 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/examples/probecalibrate.py
+-rw-r--r--   0        0        0    10558 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/examples/vicecenter.nc
+-rwxr-xr-x   0        0        0     3942 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/examples/vicecenter.py
+-rwxr-xr-x   0        0        0     1930 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/gbl.py
+-rwxr-xr-x   0        0        0     5360 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/goto.py
+-rw-r--r--   0        0        0     6907 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/haas.py
+-rwxr-xr-x   0        0        0     1254 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/lib.py
+-rwxr-xr-x   0        0        0     6051 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/main.py
+-rwxr-xr-x   0        0        0    15870 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/makestdvars.py
+-rwxr-xr-x   0        0        0    21488 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/mvarsorig
+-rwxr-xr-x   0        0        0     2195 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/nd.py
+-rwxr-xr-x   0        0        0    13407 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/op.py
+-rwxr-xr-x   0        0        0     7032 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/ptest.py
+-rwxr-xr-x   0        0        0     3005 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/scalar.py
+-rwxr-xr-x   0        0        0     7359 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/stat.py
+-rwxr-xr-x   0        0        0     2744 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/symbol.py
+-rwxr-xr-x   0        0        0     1310 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/thanksto
+-rwxr-xr-x   0        0        0     6467 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/vector.py
+-rwxr-xr-x   0        0        0      787 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/visible.py
+-rwxr-xr-x   0        0        0    11837 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/walk.py
+-rwxr-xr-x   0        0        0     6364 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/walkbase.py
+-rwxr-xr-x   0        0        0     4674 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/walkexpr.py
+-rwxr-xr-x   0        0        0     6429 2023-06-28 04:32:41.423947 p2g-0.2.29/p2g/walkfunc.py
+-rwxr-xr-x   0        0        0     3609 2023-06-28 04:32:41.427947 p2g-0.2.29/pyproject.toml
+-rw-r--r--   0        0        0    38275 2023-06-28 04:32:41.427947 p2g-0.2.29/readme.md
+-rw-r--r--   0        0        0    39187 1970-01-01 00:00:00.000000 p2g-0.2.29/PKG-INFO
```

### Comparing `p2g-0.1.95/p2g/axis.py` & `p2g-0.2.29/p2g/axis.py`

 * *Files 27% similar despite different names*

```diff
@@ -1,39 +1,39 @@
-from p2g import err
-from p2g import scalar
-
-
-NAMES = "xyz"
-
-# special case constant for vectors of naxes size.
-
-
-class Axes(scalar.Constant):
-
-    def __init__(self):
-        super().__init__(len(NAMES))
-    @property
-    def _value(self):
-        return len(NAMES)
-
-    @_value.setter
-    def _value(self, inset):
-        pass
-
-
-def low_names_v():
-    return NAMES.lower()
-
-
-def low_names(idx):
-    return NAMES[idx]
-
-
-def axis_name_to_index(axis_char):
-    return NAMES.index(axis_char)
-
-
-def name_to_indexes_list(name: str) -> list[int]:
-    try:
-        return [axis_name_to_index(ch) for ch in name]
-    except ValueError:
-        return err.compiler(f"Bad axis letter in '{name}'")
+from p2g import err
+from p2g import scalar
+
+
+NAMES = "xyz"
+
+# special case constant for vectors of naxes size.
+
+
+class Axes(scalar.Constant):
+    def __init__(self):
+        super().__init__(len(NAMES))
+
+    @property
+    def _value(self):
+        return len(NAMES)
+
+    @_value.setter
+    def _value(self, inset):
+        pass
+
+
+def low_names_v():
+    return NAMES.lower()
+
+
+def low_names(idx):
+    return NAMES[idx]
+
+
+def axis_name_to_index(axis_char):
+    return NAMES.index(axis_char)
+
+
+def name_to_indexes_list(name: str) -> list[int]:
+    try:
+        return [axis_name_to_index(ch) for ch in name]
+    except ValueError:
+        return err.compiler(f"Bad axis letter in '{name}'.")
```

### Comparing `p2g-0.1.95/p2g/builtin.py` & `p2g-0.2.29/p2g/builtin.py`

 * *Files 25% similar despite different names*

```diff
@@ -1,65 +1,62 @@
-from p2g import scalar
-
-
-# pragma: no cover
-
-# just type hints.
-
-# pylint: disable=redefined-builtin
-# pylint: disable=invalid-name
-
-
-def abs(_v) -> scalar.Scalar:
-    return scalar.ConstantNone()
-
-
-def acos(_v) -> scalar.Scalar:
-    return scalar.ConstantNone()
-
-
-def asin(_v) -> scalar.Scalar:
-    return scalar.ConstantNone()
-
-
-def atan(_v) -> scalar.Scalar:
-    return scalar.ConstantNone()
-
-
-def cos(_v) -> scalar.Scalar:
-    return scalar.ConstantNone()
-
-
-def exp(_v) -> scalar.Scalar:
-    return scalar.ConstantNone()
-
-
-def fix(_v) -> scalar.Scalar:
-    return scalar.ConstantNone()
-
-
-def fup(_v) -> scalar.Scalar:
-    return scalar.ConstantNone()
-
-
-def ln(_v) -> scalar.Scalar:
-    return scalar.ConstantNone()
-
-
-def sin(_v) -> scalar.Scalar:
-    return scalar.ConstantNone()
-
-
-def sqrt(_v) -> scalar.Scalar:
-    return scalar.ConstantNone()
-
-
-def tan(_v) -> scalar.Scalar:
-    return scalar.ConstantNone()
-
-
-def exists(_v) -> scalar.Scalar:
-    return scalar.ConstantNone()
-
-
-def ground(_v) -> scalar.Scalar:
-    return scalar.ConstantNone()
+from p2g import scalar
+
+
+# Just type hints, can't be called.
+# pylint: disable=redefined-builtin
+# pylint: disable=invalid-name
+
+
+def abs(_v) -> scalar.Scalar:  # no cover
+    return scalar.ConstantNone()
+
+
+def acos(_v) -> scalar.Scalar:  # no cover
+    return scalar.ConstantNone()
+
+
+def asin(_v) -> scalar.Scalar:  # no cover
+    return scalar.ConstantNone()
+
+
+def atan(_v) -> scalar.Scalar:  # no cover
+    return scalar.ConstantNone()
+
+
+def cos(_v) -> scalar.Scalar:  # no cover
+    return scalar.ConstantNone()
+
+
+def exp(_v) -> scalar.Scalar:  # no cover
+    return scalar.ConstantNone()
+
+
+def fix(_v) -> scalar.Scalar:  # no cover
+    return scalar.ConstantNone()
+
+
+def fup(_v) -> scalar.Scalar:  # no cover
+    return scalar.ConstantNone()
+
+
+def ln(_v) -> scalar.Scalar:  # no cover
+    return scalar.ConstantNone()
+
+
+def sin(_v) -> scalar.Scalar:  # no cover
+    return scalar.ConstantNone()
+
+
+def sqrt(_v) -> scalar.Scalar:  # no cover
+    return scalar.ConstantNone()
+
+
+def tan(_v) -> scalar.Scalar:  # no cover
+    return scalar.ConstantNone()
+
+
+def exists(_v) -> scalar.Scalar:  # no cover
+    return scalar.ConstantNone()
+
+
+def ground(_v) -> scalar.Scalar:  # no cover
+    return scalar.ConstantNone()
```

### Comparing `p2g-0.1.95/p2g/doc/haas.txt` & `p2g-0.2.29/p2g/doc/haas.txt`

 * *Files 0% similar despite different names*

```diff
@@ -177,8 +177,8 @@
 │  #51601 … #51800 │   200 │  V │  Float  │ VPS_FEEDRATE              │
 │  #51801 … #52000 │   200 │  V │  Float  │ APPROX_LENGTH             │
 │  #52001 … #52200 │   200 │  V │  Float  │ APPROX_DIAMETER           │
 │  #52201 … #52400 │   200 │  V │  Float  │ EDGE_MEASURE_HEIGHT       │
 │  #52401 … #52600 │   200 │  V │  Float  │ TOOL_TOLERANCE            │
 │  #52601 … #52800 │   200 │  V │  Float  │ PROBE_TYPE                │
 └──────────────────┴───────┴────┴─────────┴───────────────────────────┘
-           Generated by /home/sac/pg1/p2g/p2g/makestdvars.py           
+       Generated by /home/runner/work/p2g/p2g/p2g/makestdvars.py
```

### Comparing `p2g-0.1.95/p2g/err.py` & `p2g-0.2.29/p2g/err.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,103 +1,101 @@
-import dataclasses
-import pathlib
-import sys
-import typing
-
-from p2g import gbl
-from p2g import lib
-
-
-@dataclasses.dataclass
-class NodePlace:
-    col_offset_first: int
-    col_offset_past: int
-    lineno: int
-    funcname: str
-    filename: str
-
-
-@dataclasses.dataclass
-class State:
-    last_pos: NodePlace
-
-    def __init__(self):
-        self.last_pos = NodePlace(0, 0, 0, "", "")
-
-
-state = State()
-
-
-def mark_pos(last_pos):
-    state.last_pos = last_pos
-
-
-def src_code_from_line_near(pos, lineno):
-    with lib.openr(pos.filename) as inf:
-        src = inf.read()
-        lines = lib.splitnl(src)
-        return lines[lineno - 1]
-
-
-def src_code_from_node_place(pos):
-    return src_code_from_line_near(pos, pos.lineno)
-
-
-def note_from_node_place(pos, absolute_lines, topfn=None):
-    relfixer = 1
-    if (gbl.config.relative_lines or (not absolute_lines)) and topfn is not None:
-        relfixer = topfn.__code__.co_firstlineno
-
-    filename = pos.filename
-    if gbl.config.relative_paths:
-        orig = pathlib.Path(filename)
-        filename = "/".join(orig.parts[-3:])
-
-    reportable_line = pos.lineno - relfixer + 1
-    col_offset = pos.col_offset_first
-    col_width = pos.col_offset_past - col_offset
-    pfx = ":".join(
-        [
-            str(filename),
-            str(reportable_line),
-            str(pos.col_offset_first),
-            str(pos.col_offset_past),
-            " ",
-        ]
-    )
-
-    return pfx, " " * (len(pfx) + col_offset) + "^" * col_width
-
-
-class CompilerError(Exception):
-    pos: NodePlace
-    message: str
-
-    # def __str__(self):
-    #     return str(self.message)
-
-    def __init__(self, pos, message: str):
-        super().__init__()
-        self.pos = pos
-        self.message = message
-
-    def error_lines(self, absolute_lines, topfn):
-        sourceline = src_code_from_node_place(self.pos)
-        pfx, carat = note_from_node_place(self.pos, absolute_lines, topfn)
-
-        return [self.message, pfx + sourceline, carat]
-
-    def report_error(self, outf=None, absolute_lines=True, topfn=None):
-        if outf is None:
-            outf = sys.stderr
-
-        for line in self.error_lines(absolute_lines, topfn):
-            print(line, file=outf)
-
-
-def compiler(message, exc=None, err_pos=None) -> typing.NoReturn:
-    if gbl.config.bp_on_error:  # for debug
-        breakpoint()
-
-    if not err_pos:
-        err_pos = state.last_pos
-    raise CompilerError(err_pos, str(message)) from exc
+import dataclasses
+import pathlib
+import typing
+
+from p2g import gbl
+
+
+@dataclasses.dataclass
+class NodePlace:
+    col_offset_first: int
+    col_offset_past: int
+    lineno: int
+    funcname: str
+    filename: str
+
+
+@dataclasses.dataclass
+class State:
+    last_pos: NodePlace
+
+    def __init__(self):
+        self.last_pos = NodePlace(0, 0, 0, "", "")
+
+
+state = State()
+
+
+def mark_pos(last_pos):
+    state.last_pos = last_pos
+
+
+def src_code_from_line_near(pos, lineno):
+    with gbl.openr(pos.filename) as (inf, etrace):
+        if etrace:
+            return ""
+        src = gbl.logread(inf)
+        lines = gbl.splitnl(src)
+        return lines[lineno - 1]
+
+
+def src_code_from_node_place(pos):
+    return src_code_from_line_near(pos, pos.lineno)
+
+
+def note_from_node_place(pos, absolute_lines, topfn=None):
+    relfixer = 1
+    if (gbl.config.tin_test or (not absolute_lines)) and topfn is not None:
+        relfixer = topfn.__code__.co_firstlineno
+
+    filename = pos.filename
+    if gbl.config.tin_test:
+        orig = pathlib.Path(filename)
+        filename = "/".join(orig.parts[-3:])
+
+    reportable_line = pos.lineno - relfixer + 1
+    col_offset = pos.col_offset_first
+    col_width = pos.col_offset_past - col_offset
+    pfx = ":".join(
+        [
+            str(filename),
+            str(reportable_line),
+            str(pos.col_offset_first),
+            str(pos.col_offset_past),
+            " ",
+        ]
+    )
+
+    return pfx, " " * (len(pfx) + col_offset) + "^" * col_width
+
+
+class CompilerError(Exception):
+    pos: NodePlace
+    message: str
+
+    # def __str__(self):
+    #     return str(self.message)
+
+    def __init__(self, pos, message: str):
+        super().__init__()
+        self.pos = pos
+        self.message = message
+
+    def error_lines(self, absolute_lines, topfn):
+        sourceline = src_code_from_node_place(self.pos)
+        pfx, carat = note_from_node_place(self.pos, absolute_lines, topfn)
+
+        return [self.message, pfx + sourceline, carat]
+
+    def report_error(self, absolute_lines=True, topfn=None):
+        for line in self.error_lines(absolute_lines, topfn):
+            gbl.eprint(line)
+
+
+def compiler(message, exc=None, err_pos=None) -> typing.NoReturn:
+    if gbl.config.bp_on_error:  # for debug
+        breakpoint()
+        breakpoint()
+
+    if not err_pos:
+        err_pos = state.last_pos
+    raise CompilerError(err_pos, str(message)) from exc
```

### Comparing `p2g-0.1.95/p2g/examples/csearch.py` & `p2g-0.2.29/p2g/examples/csearch.py`

 * *Ordering differences only*

 * *Files 14% similar despite different names*

```diff
@@ -1,103 +1,103 @@
-from typing import Optional
-
-import p2g as pg
-
-
-class SearchConstraint:
-    # position roughly center above start of search.
-    above: pg.Vec
-    # min size of thing to look for.
-
-    amin: pg.Vec
-    # max size to search in one dimension for the thing
-    # to probe.  pg.RVALnstains max size of things measured.
-    amax: pg.Vec
-
-    # when measuring z, how far to
-    # move from an xy edge inwards to work it out.
-    indent: pg.Vec
-
-    # steps between probes
-
-    delta: pg.Vec
-    # safe distance above probed z surface to move
-    skim_distance: pg.Vec
-
-    # how far to backoff before probing slowly
-    backoff: pg.Vec
-
-    # how far to look down for a surface once we've
-    # already located the rough z0
-    search_depth: pg.Vec
-    # how far to look down and not found is a not there
-    #
-    found_if_below: pg.Vec
-
-    # to work out when there's a probe hit,
-    # say probe from z down to 0,   then any stop < iota
-    # is taken as a miss.
-    iota: pg.Vec
-
-    def __init__(
-        self,
-        amin: pg.Vec,
-        amax: pg.Vec,
-        above: pg.Vec,
-        delta: pg.Vec,
-        skim_distance=None,
-        indent: Optional[pg.Vec] = None,
-        backoff: Optional[pg.Vec] = None,
-        search_depth=None,
-        found_if_below=None,
-        iota=None,
-    ):
-        super().__init__()
-
-        if search_depth is None:
-            search_depth = pg.Const(-0.1)
-
-        if found_if_below is None:
-            found_if_below = search_depth * 0.5
-
-        if backoff is None:
-            backoff = pg.Const(x=0.1, y=0.1, z=0.1)
-
-        if indent is None:
-            indent = round(amax * 0.1, 1)
-
-        if skim_distance is None:
-            skim_distance = pg.Const(0.3)
-
-        if iota is None:
-            iota = pg.Const(x=0.025, y=0.025, z=0.025)
-
-        self.iota = iota
-        self.delta = delta
-
-        self.amin = amin
-        self.indent = indent
-        self.amax = amax
-
-        self.above = above
-        self.skim_distance = skim_distance
-        self.backoff = backoff
-        self.search_depth = search_depth
-        self.found_if_below = found_if_below
-
-    @property
-    def comment(self):
-        return [
-            "Search Constraints:",
-            "start:",
-            f"  {self.above}",
-            "boundary:",
-            f"  x= (-{(self.amax[0] * 0.5)}..-{(self.amin[0] * 0.5)})"
-            f"..({(self.amin[0] * 0.5)}..{(self.amax[0] * 0.5)})",
-            f"  y= (-{(self.amax[1] * 0.5)}..-{(self.amin[1] * 0.5)})"
-            f"..({(self.amin[1] * 0.5)}..{(self.amax[1] * 0.5)})",
-            f"  z= ({(-self.amax[2])}..{(-self.amin[2])})",
-            "indent:",
-            f"  {self.indent}",
-            "delta:",
-            f"  {self.delta}",
-        ]
+from typing import Optional
+
+import p2g as pg
+
+
+class SearchConstraint:
+    # position roughly center above start of search.
+    above: pg.Vec
+    # min size of thing to look for.
+
+    amin: pg.Vec
+    # max size to search in one dimension for the thing
+    # to probe.  pg.RVALnstains max size of things measured.
+    amax: pg.Vec
+
+    # when measuring z, how far to
+    # move from an xy edge inwards to work it out.
+    indent: pg.Vec
+
+    # steps between probes
+
+    delta: pg.Vec
+    # safe distance above probed z surface to move
+    skim_distance: pg.Vec
+
+    # how far to backoff before probing slowly
+    backoff: pg.Vec
+
+    # how far to look down for a surface once we've
+    # already located the rough z0
+    search_depth: pg.Vec
+    # how far to look down and not found is a not there
+    #
+    found_if_below: pg.Vec
+
+    # to work out when there's a probe hit,
+    # say probe from z down to 0,   then any stop < iota
+    # is taken as a miss.
+    iota: pg.Vec
+
+    def __init__(
+        self,
+        amin: pg.Vec,
+        amax: pg.Vec,
+        above: pg.Vec,
+        delta: pg.Vec,
+        skim_distance=None,
+        indent: Optional[pg.Vec] = None,
+        backoff: Optional[pg.Vec] = None,
+        search_depth=None,
+        found_if_below=None,
+        iota=None,
+    ):
+        super().__init__()
+
+        if search_depth is None:
+            search_depth = pg.Const(-0.1)
+
+        if found_if_below is None:
+            found_if_below = search_depth * 0.5
+
+        if backoff is None:
+            backoff = pg.Const(x=0.1, y=0.1, z=0.1)
+
+        if indent is None:
+            indent = round(amax * 0.1, 1)
+
+        if skim_distance is None:
+            skim_distance = pg.Const(0.3)
+
+        if iota is None:
+            iota = pg.Const(x=0.025, y=0.025, z=0.025)
+
+        self.iota = iota
+        self.delta = delta
+
+        self.amin = amin
+        self.indent = indent
+        self.amax = amax
+
+        self.above = above
+        self.skim_distance = skim_distance
+        self.backoff = backoff
+        self.search_depth = search_depth
+        self.found_if_below = found_if_below
+
+    @property
+    def comment(self):
+        return [
+            "Search Constraints:",
+            "start:",
+            f"  {self.above}",
+            "boundary:",
+            f"  x= (-{(self.amax[0] * 0.5)}..-{(self.amin[0] * 0.5)})"
+            f"..({(self.amin[0] * 0.5)}..{(self.amax[0] * 0.5)})",
+            f"  y= (-{(self.amax[1] * 0.5)}..-{(self.amin[1] * 0.5)})"
+            f"..({(self.amin[1] * 0.5)}..{(self.amax[1] * 0.5)})",
+            f"  z= ({(-self.amax[2])}..{(-self.amin[2])})",
+            "indent:",
+            f"  {self.indent}",
+            "delta:",
+            f"  {self.delta}",
+        ]
```

### Comparing `p2g-0.1.95/p2g/examples/defs.py` & `p2g-0.2.29/p2g/examples/defs.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,90 +1,94 @@
-import enum
-
-import p2g as p2g
-
-from p2g.haas import *
-
-
-class ONumbers(enum.IntEnum):
-    PROBE_VICE_CENTER = 100
-    ALIGNC = enum.auto()
-    ROTARY_PROBE_BORE = enum.auto()
-    ABOVE_VICE = enum.auto()
-    ABOVE_ROTARY = enum.auto()
-    PROBE_CALIBRATE = enum.auto()
-
-
-class Tool(enum.IntEnum):
-    PROBE = 1
-    KNOWN_LENGTH = 2
-
-
-# pylint: disable=too-many-instance-attributes
-class JobDefs(p2g.Symbols):
-    def __init__(self):
-        super().__init__()
-        self.MACHINE_ABS_ABOVE_OTS = p2g.Const(x=-1.16, y=-7.5, z=-8.0)
-        self.MACHINE_ABS_ABOVE_RING = p2g.Const(x=-16.46, y=-3.5, z=-22.7)
-        self.MACHINE_ABS_ABOVE_ROTARY = p2g.Const(x=-12.5214, y=-12.9896, z=-7.0)
-        self.MACHINE_ABS_ABOVE_SEARCH_ROTARY_LHS_5X8 = p2g.Const(
-            x=-15.5, y=-17.50, z=-14.0
-        )
-        self.MACHINE_ABS_ABOVE_VICE = p2g.Const(x=-28.0, y=-10.0, z=-16.00)
-        self.MACHINE_ABS_CLOSE_ABOVE_OTS = p2g.Const(x=-1.16, y=-7.5, z=-7.6)
-        self.MACHINE_ABS_CLOSE_ABOVE_TOOL_TOUCH = p2g.Const(
-            x=-1.16,
-            y=-7.5,
-            z=-7.6,
-        )
-        self.MACHINE_ABS_HOME2 = p2g.Const(x=-15.0, y=-15.0, z=-2.0)
-        self.MACHINE_ABS_ROTARY_HOME = p2g.Const(x=-12, y=0.0, z=-3.0)
-        self.MACHINE_ABS_Z0 = p2g.Const(z=0.0)
-
-        self.MACHINE_ABS_ZMIN = p2g.Const(z=-22.0)
-        self.PROBE_RING_DIAMETER = 0.7
-        m1 = p2g.Const(x=0.0, y=0.0, z=-0.7)
-        self.MACHINE_ABS_SEARCH_ROTARY_LHS_5X8 = (
-            self.MACHINE_ABS_ABOVE_SEARCH_ROTARY_LHS_5X8 + m1
-        )
-
-        self.FAST_FEED = 650.0
-        self.SLOW_PROBE_FEED = 10.0
-        self.FAST_PROBE_FEED = 100.0
-
-        probe = p2g.goto.probe.mcode(MUST_SKIP).work
-        self.slow_probe = probe.feed(self.SLOW_PROBE_FEED)
-
-        self.fast_probe = probe.feed(self.FAST_PROBE_FEED)
-        self.goto = p2g.goto.work.feed(self.FAST_FEED)
-
-        self.init_finished()
-
-    def load_tool(self, tool):
-        p2g.code(f"T{tool:02} M06")
-
-    def setup_probing(self):
-        self.load_tool(Tool.PROBE)
-
-        p2g.code(PROBE_ON)
-        p2g.code(NO_LOOKAHEAD)
-
-    def message(self, txt: str, code: int = 101):
-        p2g.message(MESSAGE[0], txt, code=code)
-
-    def alarm(self, txt: str, code: int = 101):
-        p2g.message(ALARM[0], txt, code=code)
-
-    def ots_on(self):
-        p2g.code(OTS_ON)
-
-    def spindle_probe_on(self):
-        p2g.code(SPINDLE_PROBE_ON)
-
-    def ots_calibrate(self):
-        p2g.code("G65 P9023 A20. K5. S0.5 D-2.")
-
-    def spindle_probe_find_height(self):
-        p2g.code("G65 P9023 A21. T1.")
-
-    def spindle_probe_find_radius(self):
-        p2g.code("G65 P9023 A10.0 D0.7")
+import enum
+
+from p2g import *
+from p2g.haas import *
+
+
+# class ONumbers(enum.IntEnum):
+#     PROBE_VICE_CENTER = 100
+#     ALIGNC = enum.auto()
+#     ROTARY_PROBE_BORE = enum.auto()
+#     ABOVE_VICE = enum.auto()
+#     ABOVE_ROTARY = enum.auto()
+#     PROBE_CALIBRATE = enum.auto()
+
+
+class Tool(enum.IntEnum):
+    PROBE = 1
+    KNOWN_LENGTH = 2
+
+
+# pylint: disable=too-many-instance-attributes
+class JobDefs:
+    def __init__(self):
+        super().__init__()
+        self.MACHINE_ABS_ABOVE_OTS = Const(x=-1.16, y=-7.5, z=-7.5)
+
+        # ots tool and probe are different lengths.
+        self.MACHINE_ABS_PROBE_ABOVE_OTS = Const(x=-1.16, y=-7.5, z=-7.5)
+
+        self.MACHINE_ABS_PROBE_ABOVE_RING = Const(x=-16.46, y=-3.5, z=-22.7)
+        self.MACHINE_ABS_ABOVE_ROTARY = Const(x=-12.5214, y=-12.9896, z=-7.0)
+        self.MACHINE_ABS_ABOVE_SEARCH_ROTARY_LHS_5X8 = Const(x=-15.5, y=-17.50, z=-14.0)
+        self.MACHINE_ABS_ABOVE_VICE = Const(x=-28.0, y=-10.0, z=-16.00)
+        self.MACHINE_ABS_CLOSE_ABOVE_OTS = Const(x=-1.16, y=-7.5, z=-7.6)
+        self.MACHINE_ABS_CLOSE_ABOVE_TOOL_TOUCH = Const(
+            x=-1.16,
+            y=-7.5,
+            z=-7.6,
+        )
+        self.MACHINE_ABS_HOME2 = Const(x=-15.0, y=-15.0, z=-2.0)
+        self.MACHINE_ABS_ROTARY_HOME = Const(x=-12, y=0.0, z=-3.0)
+        self.MACHINE_ABS_Z0 = Const(z=0.0)
+
+        self.MACHINE_ABS_ZMIN = Const(z=-22.0)
+        self.PROBE_RING_DIAMETER = 0.7
+        m1 = Const(x=0.0, y=0.0, z=-0.7)
+        self.MACHINE_ABS_SEARCH_ROTARY_LHS_5X8 = (
+            self.MACHINE_ABS_ABOVE_SEARCH_ROTARY_LHS_5X8 + m1
+        )
+
+        self.FAST_FEED = 65.0
+        self.SLOW_PROBE_FEED = 10.0
+        self.FAST_PROBE_FEED = 10.0
+
+        probe = goto.probe.mcode(MUST_SKIP).work
+        self.slow_probe = probe.feed(self.SLOW_PROBE_FEED)
+
+        self.fast_mabs_probe = probe.machine.absolute.feed(self.FAST_PROBE_FEED)
+        self.slow_mabs_probe = probe.machine.absolute.feed(self.SLOW_PROBE_FEED)
+        self.goto = goto.work.feed(self.FAST_FEED)
+
+    def load_tool(self, tool):
+        codenl(f"T{tool:02} M06")
+
+    def setup_probing(self):
+        self.load_tool(Tool.PROBE)
+
+        codenl(PROBE_ON)
+        codenl(NO_LOOKAHEAD)
+
+    def pause(self, txt: str):
+        comment("")
+        message(MESSAGE, txt)
+        comment("")
+
+    def alarm(self, txt: str):
+        comment("")
+        message(ALARM, txt)
+        comment("")
+
+    def ots_on(self):
+        codenl(OTS_ON)
+
+    def spindle_probe_on(self):
+        codenl(SPINDLE_PROBE_ON)
+
+    def ots_calibrate(self):
+        codenl("G65 P9023 A20. K5. S0.5 D-2.")
+
+    def spindle_probe_find_height(self):
+        codenl("G65 P9023 A21. T1.")
+
+    def spindle_probe_find_radius(self):
+        codenl("G65 P9023 A10.0 D0.7")
```

### Comparing `p2g-0.1.95/p2g/examples/vicecenter.nc` & `p2g-0.2.29/p2g/examples/vicecenter.nc`

 * *Files 19% similar despite different names*

```diff
@@ -1,168 +1,232 @@
-  O0001                           ( VICECENTER                    )
+( brc                    :  #102.x  #103.y             )
+( cursor                 :  #104.x  #105.y             )
+( error                  :  #106.x  #107.y             )
+( G55                    : #5241.x #5242.y #5243.z     )
+( its                    :  #106.x                     )
+( MACHINE_POS            : #5021.x #5022.y #5023.z     )
+( output                 :  #100.x  #101.y             )
+( output                 :  #102.x  #103.y             )
+( PROBE_R                :  #556.x  #557.y             )
+( SKIP_POS               : #5061.x #5062.y #5063.z     )
+( tlc                    :  #100.x  #101.y             )
+( WCS                    : #5241.x #5242.y #5243.z     )
+( amax                   :  14.000,  8.000,  3.000     )
+( amin                   :   7.000,  4.000, -5.000     )
+( backoff                :   0.100,  0.100,  0.100     )
+( delta                  :   0.750,  0.400             )
+( iota                   :   0.025,  0.025,  0.025     )
+( MACHINE_ABS_ABOVE_VICE : -28.000,-10.000,-16.000     )
+( start_search           :   0.000, -2.000             )
+( start_search           :  -3.500,  0.000             )
+( start_search           :   3.500,  0.000             )
+( start_search           :   0.000,  2.000             )
+( stop_search            :  -7.000,  0.000             )
+( stop_search            :   0.000, -4.000             )
+( stop_search            :   0.000,  4.000             )
+( stop_search            :   7.000,  0.000             )
+( fast_mabs_probe        : 10.0 M79 machine xyz probe  )
+( slow_probe             : 10.0 M79 work xyz probe     )
+  O0001                           ( vicecenter                    )
+
 ( Find center of plate in vice, )
 (  result in [#5241]            )
 ( Search Constraints:           )
 ( start:                        )
 (   -28.0, -13.0, -16.0         )
 ( boundary:                     )
 (   x= [-7.0..-3.5]..[3.5..7.0] )
 (   y= [-4.0..-2.0]..[2.0..4.0] )
 (   z= [-3.0..5.0]              )
 ( indent:                       )
 (   1.4, 0.8, 0.3               )
 ( delta:                        )
 (   0.75, 0.4                   )
-( MACHINE_ABS_ABOVE_VICE : -28.,-10.,-16.            )
-( slow_probe             : probe M79 work xyz  10.0  )
-( fast_probe             : probe M79 work xyz  100.0 )
-( goto                   :   work xyz  650.0         )
-( WCS                    : #5241.x                   )
-( tlc                    :                           )
-( brc                    :                           )
-( cursor                 :  #104.x  #105.y           )
-( error                  :                           )
   T01 M06                         ( st.setup_probing[]            )
   G65 P9832
   G103 P1
   G04 P1
   G04 P1
   G04 P1
   G55                             ( set_wcs[st.WCS]               )
-  G01 G90 G53 F650. z0.           ( st..machine[z=0]              )
-  G01 G90 G53 F650. x-28. y-13.   ( st..machine.xy_then_z[sch.above])
-  G01 G90 G53 F650. z-16.
+  G01 G53 G90 F65. z0.            ( st.goto.machine[z=0]          )
+  G01 G53 G90 F65. x-28. y-13.    ( st.goto.machine.xy_then_z[sch.above])
+  G01 G53 G90 F65. z-16.
+
 ( find top z roughly set [#5241].z. )
   #5241= #5021                    ( st.WCS.xyz = MACHINE_POS.xyz  )
   #5242= #5022
   #5243= #5023
-  G01 G90 G31 M79 F100. z-5.      ( st.fast_probe[z=sch.amin.z]   )
+  G01 G53 G90 G31 M79 F10. z-5.   ( st.fast_mabs_probe[z=sch.amin.z])
   #5243= #5023                    ( st.WCS.z = MACHINE_POS.z      )
-  #3006= 101.                     ( check g55                     )
+
+
+  (# 3006) = 101 (check g55)
+
+
+
 ( now work.z should be 0 at surface )
 ( and work.xy roughly middle        )
-  G01 G90 F650. z0.3              ( st.[z=sch.skim_distance]      )
+  G01 G90 F65. z0.3               ( st.goto[z=sch.skim_distance]  )
   #104= 0.                        ( st.cursor = Var[2][0, 0]      )
   #105= 0.
-(                                      )
+
+
 ( quickly move probe to find left edge )
   #106= 5.6667                    (     [abs[stop_search - start_search] / sch.delta][di.cur_axis] + 1,)
   #104= -3.5                      ( cursor[di.cur_axis] = start_search[di.cur_axis])
-L2000                             ( while its > 0:                )
-  IF [#106 LE 0.] GOTO 2002
-  G01 G90 F650. x#104 y#105       (     st.[cursor]               )
-  G01 G90 G31 M79 F100. z-0.1     (     st.fast_probe[z=sch.search_depth])
-  IF [#5063 LT -0.075] GOTO 2001  (     if SKIP_POS.z < sch.search_depth + sch.iota:)
+  G01 G90 F65. x#104 y#105        ( st.goto.xy_then_z[cursor]     )
+N1000                             ( while its > 0:                )
+  IF [#106 LE 0.] GOTO 1002
+  G01 G90 F65. x#104 y#105        (     st.goto.z_then_xy[cursor] )
+  G01 G53 G90 G31 M79 F10. z-0.1  (     st.fast_mabs_probe[z=sch.search_depth])
+  IF [#5063 LT -0.075] GOTO 1001  (     if SKIP_POS.z < sch.search_depth + sch.iota:)
   #104= #104 - 0.75               (     cursor.xy += delta        )
   #106= #106 - 1.                 (     its -= 1                  )
-  GOTO 2000
-L2002
-  #3000= 101.                     ( search for left failed        )
-L2001                             (     st.alarm[f"search for {di.name} failed"])
+  GOTO 1000
+N1002
+
+
+  (# 3000) = 101 (search for left failed)
+
+
+N1001                             (     st.alarm[f"search for {di.name} failed"])
+
 ( back off a bit to the left, then slowly probe  )
 ( rightwards for precise measurement.            )
   #104= #104 - 0.1                ( cursor.xy += sch.backoff * di.dxdy)
-  G01 G90 F650. x#104 y#105       ( st.[cursor.xy]                )
-  G01 G90 G31 M79 F10. x0. y0.    ( st.slow_probe[[0, 0]]         )
+  G01 G90 F65. x#104 y#105        ( st.goto[cursor.xy]            )
+  G01 G53 G90 G31 M79 F10. x0. y0.( st.slow_mabs_probe[[0, 0]]    )
   #100= #5061 - #556              ( output[di.cur_axis] = [SKIP_POS + PROBE_R * di.dxdy][di.cur_axis])
+
 ( reposition above surface skim height, )
 ( just inside left edge                 )
-  G01 G91 F650. x-0.1 y0.         ( st..relative[sch.backoff.xy * di.dxdy])
-  G01 G90 F650. z0.3              ( st.[z=sch.skim_distance]      )
+  G01 G91 F65. x-0.1 y0.          ( st.goto.relative[sch.backoff.xy * di.dxdy])
+  G01 G90 F65. z0.3               ( st.goto[z=sch.skim_distance]  )
   #104= #104 + 1.4                ( cursor.xy += -sch.indent.xy * di.dxdy)
-  G01 G90 F650. x#104 y#105       ( st.[cursor]                   )
-(                                      )
+  G01 G90 F65. x#104 y#105        ( st.goto[cursor]               )
+
+
 ( quickly move probe to find near edge )
   #106= 6.                        (     [abs[stop_search - start_search] / sch.delta][di.cur_axis] + 1,)
   #105= -2.                       ( cursor[di.cur_axis] = start_search[di.cur_axis])
-L2003                             ( while its > 0:                )
-  IF [#106 LE 0.] GOTO 2005
-  G01 G90 F650. x#104 y#105       (     st.[cursor]               )
-  G01 G90 G31 M79 F100. z-0.1     (     st.fast_probe[z=sch.search_depth])
-  IF [#5063 LT -0.075] GOTO 2004  (     if SKIP_POS.z < sch.search_depth + sch.iota:)
+  G01 G90 F65. x#104 y#105        ( st.goto.xy_then_z[cursor]     )
+N1003                             ( while its > 0:                )
+  IF [#106 LE 0.] GOTO 1005
+  G01 G90 F65. x#104 y#105        (     st.goto.z_then_xy[cursor] )
+  G01 G53 G90 G31 M79 F10. z-0.1  (     st.fast_mabs_probe[z=sch.search_depth])
+  IF [#5063 LT -0.075] GOTO 1004  (     if SKIP_POS.z < sch.search_depth + sch.iota:)
   #105= #105 - 0.4                (     cursor.xy += delta        )
   #106= #106 - 1.                 (     its -= 1                  )
-  GOTO 2003
-L2005
-  #3000= 101.                     ( search for near failed        )
-L2004                             (     st.alarm[f"search for {di.name} failed"])
+  GOTO 1003
+N1005
+
+
+  (# 3000) = 101 (search for near failed)
+
+
+N1004                             (     st.alarm[f"search for {di.name} failed"])
+
 ( back off a bit to the near, then slowly probe  )
 ( farwards for precise measurement.              )
   #105= #105 - 0.1                ( cursor.xy += sch.backoff * di.dxdy)
-  G01 G90 F650. x#104 y#105       ( st.[cursor.xy]                )
-  G01 G90 G31 M79 F10. x0. y0.    ( st.slow_probe[[0, 0]]         )
+  G01 G90 F65. x#104 y#105        ( st.goto[cursor.xy]            )
+  G01 G53 G90 G31 M79 F10. x0. y0.( st.slow_mabs_probe[[0, 0]]    )
   #103= #5062 - #557              ( output[di.cur_axis] = [SKIP_POS + PROBE_R * di.dxdy][di.cur_axis])
+
 ( reposition above surface skim height, )
 ( just inside near edge                 )
-  G01 G91 F650. x0. y-0.1         ( st..relative[sch.backoff.xy * di.dxdy])
-  G01 G90 F650. z0.3              ( st.[z=sch.skim_distance]      )
+  G01 G91 F65. x0. y-0.1          ( st.goto.relative[sch.backoff.xy * di.dxdy])
+  G01 G90 F65. z0.3               ( st.goto[z=sch.skim_distance]  )
   #105= #105 + 0.8                ( cursor.xy += -sch.indent.xy * di.dxdy)
-  G01 G90 F650. x#104 y#105       ( st.[cursor]                   )
-(                                     )
+  G01 G90 F65. x#104 y#105        ( st.goto[cursor]               )
+
+
 ( quickly move probe to find far edge )
   #106= 6.                        (     [abs[stop_search - start_search] / sch.delta][di.cur_axis] + 1,)
   #105= 2.                        ( cursor[di.cur_axis] = start_search[di.cur_axis])
-L2006                             ( while its > 0:                )
-  IF [#106 LE 0.] GOTO 2008
-  G01 G90 F650. x#104 y#105       (     st.[cursor]               )
-  G01 G90 G31 M79 F100. z-0.1     (     st.fast_probe[z=sch.search_depth])
-  IF [#5063 LT -0.075] GOTO 2007  (     if SKIP_POS.z < sch.search_depth + sch.iota:)
+  G01 G90 F65. x#104 y#105        ( st.goto.xy_then_z[cursor]     )
+N1006                             ( while its > 0:                )
+  IF [#106 LE 0.] GOTO 1008
+  G01 G90 F65. x#104 y#105        (     st.goto.z_then_xy[cursor] )
+  G01 G53 G90 G31 M79 F10. z-0.1  (     st.fast_mabs_probe[z=sch.search_depth])
+  IF [#5063 LT -0.075] GOTO 1007  (     if SKIP_POS.z < sch.search_depth + sch.iota:)
   #105= #105 + 0.4                (     cursor.xy += delta        )
   #106= #106 - 1.                 (     its -= 1                  )
-  GOTO 2006
-L2008
-  #3000= 101.                     ( search for far failed         )
-L2007                             (     st.alarm[f"search for {di.name} failed"])
+  GOTO 1006
+N1008
+
+
+  (# 3000) = 101 (search for far failed)
+
+
+N1007                             (     st.alarm[f"search for {di.name} failed"])
+
 ( back off a bit to the far, then slowly probe  )
 ( nearwards for precise measurement.            )
   #105= #105 + 0.1                ( cursor.xy += sch.backoff * di.dxdy)
-  G01 G90 F650. x#104 y#105       ( st.[cursor.xy]                )
-  G01 G90 G31 M79 F10. x0. y0.    ( st.slow_probe[[0, 0]]         )
+  G01 G90 F65. x#104 y#105        ( st.goto[cursor.xy]            )
+  G01 G53 G90 G31 M79 F10. x0. y0.( st.slow_mabs_probe[[0, 0]]    )
   #101= #5062 + #557              ( output[di.cur_axis] = [SKIP_POS + PROBE_R * di.dxdy][di.cur_axis])
+
 ( reposition above surface skim height, )
 ( just inside far edge                  )
-  G01 G91 F650. x0. y0.1          ( st..relative[sch.backoff.xy * di.dxdy])
-  G01 G90 F650. z0.3              ( st.[z=sch.skim_distance]      )
+  G01 G91 F65. x0. y0.1           ( st.goto.relative[sch.backoff.xy * di.dxdy])
+  G01 G90 F65. z0.3               ( st.goto[z=sch.skim_distance]  )
   #105= #105 - 0.8                ( cursor.xy += -sch.indent.xy * di.dxdy)
-  G01 G90 F650. x#104 y#105       ( st.[cursor]                   )
-  G01 G90 F650. x0. y0.           ( st.[0, 0]                     )
-(                                       )
+  G01 G90 F65. x#104 y#105        ( st.goto[cursor]               )
+  G01 G90 F65. x0. y0.            ( st.goto[0, 0]                 )
+
+
 ( quickly move probe to find right edge )
   #106= 5.6667                    (     [abs[stop_search - start_search] / sch.delta][di.cur_axis] + 1,)
   #104= 3.5                       ( cursor[di.cur_axis] = start_search[di.cur_axis])
-L2009                             ( while its > 0:                )
-  IF [#106 LE 0.] GOTO 2011
-  G01 G90 F650. x#104 y#105       (     st.[cursor]               )
-  G01 G90 G31 M79 F100. z-0.1     (     st.fast_probe[z=sch.search_depth])
-  IF [#5063 LT -0.075] GOTO 2010  (     if SKIP_POS.z < sch.search_depth + sch.iota:)
+  G01 G90 F65. x#104 y#105        ( st.goto.xy_then_z[cursor]     )
+N1009                             ( while its > 0:                )
+  IF [#106 LE 0.] GOTO 1011
+  G01 G90 F65. x#104 y#105        (     st.goto.z_then_xy[cursor] )
+  G01 G53 G90 G31 M79 F10. z-0.1  (     st.fast_mabs_probe[z=sch.search_depth])
+  IF [#5063 LT -0.075] GOTO 1010  (     if SKIP_POS.z < sch.search_depth + sch.iota:)
   #104= #104 + 0.75               (     cursor.xy += delta        )
   #106= #106 - 1.                 (     its -= 1                  )
-  GOTO 2009
-L2011
-  #3000= 101.                     ( search for right failed       )
-L2010                             (     st.alarm[f"search for {di.name} failed"])
+  GOTO 1009
+N1011
+
+
+  (# 3000) = 101 (search for right failed)
+
+
+N1010                             (     st.alarm[f"search for {di.name} failed"])
+
 ( back off a bit to the right, then slowly probe  )
 ( leftwards for precise measurement.              )
   #104= #104 + 0.1                ( cursor.xy += sch.backoff * di.dxdy)
-  G01 G90 F650. x#104 y#105       ( st.[cursor.xy]                )
-  G01 G90 G31 M79 F10. x0. y0.    ( st.slow_probe[[0, 0]]         )
+  G01 G90 F65. x#104 y#105        ( st.goto[cursor.xy]            )
+  G01 G53 G90 G31 M79 F10. x0. y0.( st.slow_mabs_probe[[0, 0]]    )
   #102= #5061 + #556              ( output[di.cur_axis] = [SKIP_POS + PROBE_R * di.dxdy][di.cur_axis])
+
 ( reposition above surface skim height, )
 ( just inside right edge                )
-  G01 G91 F650. x0.1 y0.          ( st..relative[sch.backoff.xy * di.dxdy])
-  G01 G90 F650. z0.3              ( st.[z=sch.skim_distance]      )
+  G01 G91 F65. x0.1 y0.           ( st.goto.relative[sch.backoff.xy * di.dxdy])
+  G01 G90 F65. z0.3               ( st.goto[z=sch.skim_distance]  )
   #104= #104 - 1.4                ( cursor.xy += -sch.indent.xy * di.dxdy)
-  G01 G90 F650. x#104 y#105       ( st.[cursor]                   )
+  G01 G90 F65. x#104 y#105        ( st.goto[cursor]               )
+
 (  the 'error' between 0,0 and where we )
 (  calculate the center to be gets      )
 (  added to cos and voila.              )
   #106= [#100 + #102] / 2.        ( st.error = Var[2][[st.tlc + st.brc] / 2.0])
   #107= [#101 + #103] / 2.
   #5241= #5241 + #106             ( st.WCS.xy += st.error.xy      )
   #5242= #5242 + #107
-  G01 G90 F650. x0. y0.           ( st.[0, 0]                     )
+  G01 G90 F65. x0. y0.            ( st.goto[0, 0]                 )
+
 (  final slow probe to find the surface z )
   G01 G90 G31 M79 F10. z-0.1      ( st.slow_probe[z=sch.search_depth])
   #5243= #5063                    ( st.WCS.z = SKIP_POS.z         )
-  G01 G90 G53 F650. z-16.         ( st..machine[z=sch.above.z]    )
-  #3000= 103.                     (  what changed                 )
-  M30                             ( st.alarm[" what changed", 103])
+  G01 G53 G90 F65. z-16.          ( st.goto.machine[z=sch.above.z])
+
+
+  (# 3000) = 101 ( what changed)
+
+
+  M30
```

### Comparing `p2g-0.1.95/p2g/haas.py` & `p2g-0.2.29/p2g/haas.py`

 * *Files 1% similar despite different names*

```diff
@@ -13,16 +13,16 @@
 FEED_SLOW = 50.0
 PROBE_FAST = 50.0
 PROBE_SLOW = 10.0
 PROBE_ON = ["G65 P9832"]
 PROBE_H = p2g.Fixed[3](addr=2001)
 OTS_ON = ["M59 P2", "G04 P1.0", "M59 P3"]
 OTS_OFF = ["M69 P2", "M68 P3"]
-SPINDLE_PROBE_ON = "P9832"
-SPINDLE_PROBE_OFF = "P9833"
+SPINDLE_PROBE_ON = "G65 P9832"
+SPINDLE_PROBE_OFF = "G65 P9833"
 NO_LOOKAHEAD = ["G103 P1", "G04 P1", "G04 P1", "G04 P1"]
 
 # MACHINE GEN BELOW
 NULL = p2g.Fixed(addr=0)
 MACRO_ARGUMENTS = p2g.Fixed[33](addr=1)
 # 34 .. 99 - ..
 GP_SAVED1 = p2g.Fixed[100](addr=100)
```

### Comparing `p2g-0.1.95/p2g/makestdvars.py` & `p2g-0.2.29/p2g/makestdvars.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,491 +1,492 @@
-import pathlib
-import re
-
-import rich.console
-
-from rich.table import Table
-
-from p2g import lib
-
-
-# three sorts of py outputs, as an arrays,  as attributes to a
-# class, or straight into global names.
-
-INTO_ARRAY = 0
-INDENT = "    "
-INTO_ATTR = 0
-INDENT = "    "
-
-INTO_GBL = 1
-INDENT = ""
-
-
-def def_prefix(key):
-    if INTO_ARRAY:  # no cover
-        return f'dst["{key}"]'
-    if INTO_ATTR:  # no cover
-        return f"dst.{key}"
-    if INTO_GBL:
-        return f"{key}"
-    raise AssertionError
-
-
-MAKE_PFX = "p2g."
-
-
-# pylint: disable=invalid-name
-# pylint: disable=too-many-instance-attributes
-# pylint: disable=too-many-statements
-class NAXES:
-    def __init__(self):
-        pass
-
-    def __str__(self):
-        return "NAXES"
-
-
-class MacroVar:
-    def __init__(self, *, key, addr, alias=None, size=None, name="", typ=""):
-        self.typ = typ
-        self.key = key
-        self.addr = addr
-
-        self.name = name
-        self.alias = alias
-        self.size = size
-        suffix = ""
-        self.last = None
-        if isinstance(self.size, NAXES):
-            self.last = NAXES
-            suffix = "…"
-        else:
-            self.last = self.addr + self.size - 1
-            if self.last != self.addr:
-                suffix = f" … #{self.last:5}"
-        self.range_as_text = f"#{self.addr:5}{suffix}"
-
-    def for_regen(self):
-        funcname = self.__class__.__qualname__
-        res = [str(self.addr)]
-        if self.size is not None:
-            res.append(f"size={self.size}")
-        restxt = ", ".join(res)
-        return f"{def_prefix(self.name)} = {funcname}({restxt})"
-
-    # for the .txt output
-    def for_txt(self):
-        return (
-            self.range_as_text,
-            str(self.size),
-            self.key,
-            self.typ,
-            self.name,
-        )
-
-    def for_org(self):
-        return f"| ={self.name}= | ~{self.size}~ | ~{self.range_as_text}~ |\n"
-
-    def for_py_out(self):
-        return f"# {self.addr} .. {self.last} {self.name} .."
-
-    def __lt__(self, other):
-        return self.addr < other.addr
-
-
-class Gen(MacroVar):
-    def __init__(
-        self,
-        *,
-        exp_name,
-        idc,
-        addr,
-        size=None,
-        typ,
-    ):
-        self.exp_name = exp_name
-
-        super().__init__(
-            key=idc,
-            addr=addr,
-            size=size,
-            typ=typ,
-        )
-
-    def for_py_out(self):
-        rs = ""
-
-        sstr = ""
-        if self.size is not None and self.size != 1:
-            sstr = f"[{self.size}]"
-        return f"{def_prefix(self.name)} = {MAKE_PFX}Fixed{sstr}({rs}addr={self.addr})"
-
-
-def one(addr, typ="Float"):
-    return Gen(
-        exp_name="Fixed",
-        idc="v" + typ[0],
-        addr=addr,
-        size=1,
-        typ=typ,
-    )
-
-
-def ione(addr):
-    return one(addr, typ="Int")
-
-
-class Alias(MacroVar):
-    def __init__(self, src):
-        super().__init__(key="A", addr=src.addr, size=src.size, alias=src)
-
-    def for_regen(self):
-        return f"{def_prefix(self.name.ljust(20))} = alias({def_prefix}{self.alias.name})"
-
-    def for_py_out(self):
-        return f"{def_prefix(self.name)} = {MAKE_PFX}alias({def_prefix(self.alias.name)})"
-
-    def for_txt(self):
-        return (
-            self.range_as_text,
-            str(self.size),
-            self.key,
-            self.typ,
-            " also " + self.name,
-        )
-
-
-def fixed(addr, size, typ="Float"):
-    return Gen(
-        exp_name="Fixed",
-        idc="V",
-        addr=addr,
-        size=size,
-        typ=typ,
-    )
-
-
-class Gap(MacroVar):
-    C = 0
-
-    def __init__(self, addr, size=None):
-        super().__init__(key="_", addr=addr, size=size)
-        self.name = "-"
-
-    def for_regen(self):
-        self.name = f"gap{Gap.C:02}"
-        Gap.C += 1
-        return super().for_regen()
-
-
-def cwcpos(addr):
-    return Gen(exp_name="CWCPos", idc="m", addr=addr, size=NAXES(), typ="Float")
-
-
-def machinepos(addr):
-    return Gen(exp_name="MachinePos", idc="m", addr=addr, size=NAXES(), typ="Float")
-
-
-def workoffsettable(addr):
-    return Gen(exp_name="WorkOffsetTable", idc="W", addr=addr, typ="Float", size=NAXES())
-
-
-def tooltable(addr, size, typ="Float"):
-    return Gen(exp_name="ToolTable", idc="T", addr=addr, size=size, typ=typ)
-
-
-class PalletTable(MacroVar):
-    def __init__(self, addr, size):
-        super().__init__(key="L", addr=addr, size=size, typ="Int")
-
-
-class Names:
-    interesting: list[MacroVar]
-
-    def __init__(self):
-        object.__setattr__(self, "interesting", [])
-
-    def py_write_to(self, out):
-        for v in self.interesting:
-            out.write(INDENT + v.for_py_out() + "\n")
-
-    def __setattr__(self, key, value):
-        if key[0].isupper():
-            value.name = key
-            object.__setattr__(self, key, value)
-
-        self.interesting.append(value)
-
-
-class HaasNames(Names):
-    title = "HAAS"
-
-    def __init__(self):
-        super().__init__()
-
-        self.NULL = one(0)
-        self.MACRO_ARGUMENTS = fixed(1, size=33)
-        self.gap01 = Gap(34, size=66)
-        self.GP_SAVED1 = fixed(100, size=100)
-        self.gap02 = Gap(200, size=300)
-        self.GP_SAVED2 = fixed(500, size=50)
-
-        self.PROBE_CALIBRATION1 = fixed(550, size=6)
-        self.PROBE_R = fixed(556, size=3)
-        self.PROBE_CALIBRATION2 = fixed(559, size=22)
-
-        self.GP_SAVED3 = fixed(581, size=119)
-        self.gap03 = Gap(700, size=100)
-        self.GP_SAVED4 = fixed(800, size=200)
-        self.INPUTS = fixed(1000, size=64)
-        self.MAX_LOADS_XYZAB = fixed(1064, size=5)
-        self.gap04 = Gap(1069, size=11)
-        self.RAW_ANALOG = fixed(1080, size=10)
-        self.FILTERED_ANALOG = fixed(1090, size=8)
-        self.SPINDLE_LOAD = one(1098)
-        self.gap05 = Gap(1099, size=165)
-        self.MAX_LOADS_CTUVW = fixed(1264, size=5)
-        self.gap06 = Gap(1269, size=332)
-        self.TOOL_TBL_FLUTES = tooltable(1601, size=200, typ="Int")
-        self.TOOL_TBL_VIBRATION = tooltable(1801, size=200)
-        self.TOOL_TBL_OFFSETS = tooltable(2001, size=200)
-        self.TOOL_TBL_WEAR = tooltable(2201, size=200)
-        self.TOOL_TBL_DROFFSET = tooltable(2401, size=200)
-        self.TOOL_TBL_DRWEAR = tooltable(2601, size=200)
-        self.gap07 = Gap(2801, size=199)
-        self.ALARM = one(3000, typ="Int")
-        self.T_MS = one(3001, typ="Time")
-        self.T_HR = one(3002, typ="Time")
-        self.SINGLE_BLOCK_OFF = ione(3003)
-        self.FEED_HOLD_OFF = ione(3004)
-        self.gap08 = Gap(3005, size=1)
-        self.MESSAGE = ione(3006)
-        self.gap09 = Gap(3007, size=4)
-        self.YEAR_MONTH_DAY = one(3011, typ="Time")
-        self.HOUR_MINUTE_SECOND = one(3012, typ="Time")
-        self.gap10 = Gap(3013, size=7)
-        self.POWER_ON_TIME = one(3020, typ="Time")
-        self.CYCLE_START_TIME = one(3021, typ="Time")
-        self.FEED_TIMER = one(3022, typ="Time")
-        self.CUR_PART_TIMER = one(3023, typ="Time")
-        self.LAST_COMPLETE_PART_TIMER = one(3024, typ="Time")
-        self.LAST_PART_TIMER = one(3025, typ="Time")
-        self.TOOL_IN_SPIDLE = ione(3026)
-        self.SPINDLE_RPM = ione(3027)
-        self.PALLET_LOADED = ione(3028)
-        self.gap11 = Gap(3029, size=1)
-        self.SINGLE_BLOCK = ione(3030)
-        self.AGAP = one(3031)
-        self.BLOCK_DELETE = ione(3032)
-        self.OPT_STOP = ione(3033)
-        self.gap12 = Gap(3034, size=162)
-        self.TIMER_CELL_SAFE = one(3196, typ="Time")
-        self.gap13 = Gap(3197, size=4)
-        self.TOOL_TBL_DIAMETER = tooltable(3201, size=200)
-        self.TOOL_TBL_COOLANT_POSITION = tooltable(3401, size=200)
-        self.gap14 = Gap(3601, size=300)
-        self.M30_COUNT1 = ione(3901)
-        self.M30_COUNT2 = ione(3902)
-        self.gap15 = Gap(3903, size=98)
-        self.LAST_BLOCK_G = fixed(4001, size=21)
-        self.gap16 = Gap(4022, size=79)
-        self.LAST_BLOCK_ADDRESS = fixed(4101, size=26)
-        self.gap17 = Gap(4127, size=874)
-        self.LAST_TARGET_POS = cwcpos(5001)
-        self.MACHINE_POS = machinepos(5021)
-        self.WORK_POS = cwcpos(5041)
-        self.SKIP_POS = cwcpos(5061)
-        self.TOOL_OFFSET = fixed(5081, size=20)
-        self.gap18 = Gap(5101, size=100)
-        self.G52 = workoffsettable(5201)
-        self.G54 = workoffsettable(5221)
-        self.G55 = workoffsettable(5241)
-        self.G56 = workoffsettable(5261)
-        self.G57 = workoffsettable(5281)
-        self.G58 = workoffsettable(5301)
-        self.G59 = workoffsettable(5321)
-        self.gap19 = Gap(5341, size=60)
-        self.TOOL_TBL_FEED_TIMERS = tooltable(5401, size=100, typ="Secs")
-        self.TOOL_TBL_TOTAL_TIMERS = tooltable(5501, size=100, typ="Secs")
-        self.TOOL_TBL_LIFE_LIMITS = tooltable(5601, size=100, typ="Int")
-        self.TOOL_TBL_LIFE_COUNTERS = tooltable(5701, size=100, typ="Int")
-        self.TOOL_TBL_LIFE_MAX_LOADS = tooltable(5801, size=100)
-        self.TOOL_TBL_LIFE_LOAD_LIMITS = tooltable(5901, size=100)
-        self.gap20 = Gap(6001, size=197)
-        self.NGC_CF = ione(6198)
-        self.gap21 = Gap(6199, size=802)
-        self.G154_P1 = workoffsettable(7001)
-        self.G154_P2 = workoffsettable(7021)
-        self.G154_P3 = workoffsettable(7041)
-        self.G154_P4 = workoffsettable(7061)
-        self.G154_P5 = workoffsettable(7081)
-        self.G154_P6 = workoffsettable(7101)
-        self.G154_P7 = workoffsettable(7121)
-        self.G154_P8 = workoffsettable(7141)
-        self.G154_P9 = workoffsettable(7161)
-        self.G154_P10 = workoffsettable(7181)
-        self.G154_P11 = workoffsettable(7201)
-        self.G154_P12 = workoffsettable(7221)
-        self.G154_P13 = workoffsettable(7241)
-        self.G154_P14 = workoffsettable(7261)
-        self.G154_P15 = workoffsettable(7281)
-        self.G154_P16 = workoffsettable(7301)
-        self.G154_P17 = workoffsettable(7321)
-        self.G154_P18 = workoffsettable(7341)
-        self.G154_P19 = workoffsettable(7361)
-        self.G154_P20 = workoffsettable(7381)
-        self.gap22 = Gap(7401, size=100)
-        self.PALLET_PRIORITY = PalletTable(7501, size=100)
-        self.PALLET_STATUS = PalletTable(7601, size=100)
-        self.PALLET_PROGRAM = PalletTable(7701, size=100)
-        self.PALLET_USAGE = PalletTable(7801, size=100)
-        self.gap23 = Gap(7901, size=599)
-        self.ATM_ID = ione(8500)
-        self.ATM_PERCENT = one(8501, typ="Percent")
-        self.ATM_TOTAL_AVL_USAGE = ione(8502)
-        self.ATM_TOTAL_AVL_HOLE_COUNT = ione(8503)
-        self.ATM_TOTAL_AVL_FEED_TIME = one(8504, typ="Secs")
-        self.ATM_TOTAL_AVL_TOTAL_TIME = one(8505, typ="Secs")
-        self.gap24 = Gap(8506, size=4)
-        self.ATM_NEXT_TOOL_NUMBER = ione(8510)
-        self.ATM_NEXT_TOOL_LIFE = one(8511, typ="Percent")
-        self.ATM_NEXT_TOOL_AVL_USAGE = ione(8512)
-        self.ATM_NEXT_TOOL_HOLE_COUNT = ione(8513)
-        self.ATM_NEXT_TOOL_FEED_TIME = one(8514, typ="Secs")
-        self.ATM_NEXT_TOOL_TOTAL_TIME = one(8515, typ="Secs")
-        self.gap25 = Gap(8516, size=34)
-        self.TOOL_ID = ione(8550)
-        self.TOOL_FLUTES = ione(8551)
-        self.TOOL_MAX_VIBRATION = one(8552)
-        self.TOOL_LENGTH_OFFSETS = one(8553)
-        self.TOOL_LENGTH_WEAR = one(8554)
-        self.TOOL_DIAMETER_OFFSETS = one(8555)
-        self.TOOL_DIAMETER_WEAR = one(8556)
-        self.TOOL_ACTUAL_DIAMETER = one(8557)
-        self.TOOL_COOLANT_POSITION = ione(8558)
-        self.TOOL_FEED_TIMER = one(8559, typ="Secs")
-        self.TOOL_TOTAL_TIMER = one(8560, typ="Secs")
-        self.TOOL_LIFE_LIMIT = one(8561)
-        self.TOOL_LIFE_COUNTER = one(8562)
-        self.TOOL_LIFE_MAX_LOAD = one(8563)
-        self.TOOL_LIFE_LOAD_LIMIT = one(8564)
-        self.gap26 = Gap(8565, size=435)
-        self.THERMAL_COMP_ACC = one(9000)
-        self.gap27 = Gap(9001, size=15)
-        self.THERMAL_SPINDLE_COMP_ACC = one(9016)
-        self.gap28 = Gap(9017, size=983)
-        self.GVARIABLES3 = fixed(10000, size=1000)
-        self.INPUTS1 = fixed(11000, size=256)
-        self.gap29 = Gap(11256, size=744)
-        self.OUTPUT1 = fixed(12000, size=256)
-        self.gap30 = Gap(12256, size=744)
-        self.FILTERED_ANALOG1 = fixed(13000, size=13)
-        self.COOLANT_LEVEL = one(13013)
-        self.FILTERED_ANALOG2 = fixed(13014, size=50)
-        self.gap31 = Gap(13064, size=936)
-        self.SETTING = fixed(20000, size=10000)
-        self.PARAMETER = fixed(30000, size=10000)
-
-        self.TOOL_TYP = fixed(50001, size=200)
-        self.TOOL_MATERIAL = fixed(50201, size=200)
-        self.gap32 = Gap(50401, 50600)
-        self.gap32 = Gap(51001, 51300)
-        self.CURRENT_OFFSET = fixed(50601, size=200)
-        self.CURRENT_OFFSET2 = fixed(50801, size=200)
-        self.VPS_TEMPLATE_OFFSET = fixed(51301, size=100)
-        self.WORK_MATERIAL = fixed(51401, size=200)
-        self.VPS_FEEDRATE = fixed(51601, size=200)
-
-        self.APPROX_LENGTH = fixed(51801, size=200)
-        self.APPROX_DIAMETER = fixed(52001, size=200)
-        self.EDGE_MEASURE_HEIGHT = fixed(52201, size=200)
-        self.TOOL_TOLERANCE = fixed(52401, size=200)
-        self.PROBE_TYPE = fixed(52601, size=200)
-
-        self.PROBE = Alias(self.SKIP_POS)
-        self.WORK = Alias(self.WORK_POS)
-
-        self.MACHINE = Alias(self.MACHINE_POS)
-        self.G53 = Alias(self.MACHINE_POS)
-
-
-def txt_out(outname, names):
-    guts = Table(
-        title=f"{names.title} Macro Variables",
-        caption=f"Generated by {__file__}",
-    )
-
-    guts.add_column("Range", justify="right")
-    guts.add_column("N", justify="right")
-    guts.add_column("K", justify="right")
-    guts.add_column("Type", justify="center")
-    guts.add_column("Name", justify="left")
-
-    snames = sorted(names.interesting)
-    for el in snames:
-        guts.add_row(*el.for_txt())
-        if el.alias:
-            el = el.alias
-
-    with open(outname, "w", encoding="utf-8") as out:
-        console = rich.console.Console(file=out)
-        console.print(guts, style=None)
-        print("Generated ", outname)
-
-
-def regen_out(outname, defs):
-    with open(outname, "w", encoding="utf-8") as out:
-        for el in sorted(defs.interesting):
-            out.write("        " + el.for_regen())
-
-
-def org_out(outname, defs):
-    with lib.openw(outname) as out:
-        #        out.write("1 2 3\n")
-
-        #        out.write("#+begin_example\n")
-
-        out.write("| Name | Size | Address |\n")
-        out.write("| / | <r> |  |\n")
-
-        for el in sorted(defs.interesting):
-            if el.name != "-":
-                out.write(el.for_org())
-
-        out.write("|------|------|---------|\n")
-
-
-#        out.write("#+end_example\n")
-
-
-def py_out(target_filename, defs):
-    tmp_filepath = pathlib.Path(target_filename).with_suffix(".tmp")
-
-    with open(target_filename, encoding="utf-8") as inf:
-        repl = re.match(
-            "(.*?# MACHINE GEN BELOW.*?).*(.*?# MACHINE.*)",
-            inf.read(),
-            flags=re.DOTALL,
-        )
-    if repl is not None:
-        with open(tmp_filepath, "w", encoding="utf-8") as out:
-            out.write(repl.group(1) + "\n")
-            defs.py_write_to(out)
-            out.write(INDENT + repl.group(2))
-        tmp_filepath.rename(target_filename)
-
-
-def makestdvars(outtxt_name, outdef_name, outpy_name, outorg_name):
-    try:
-        for names in [HaasNames()]:
-            if outtxt_name:
-                txt_out(outtxt_name, names)
-            if outdef_name:
-                regen_out(outdef_name, names)
-            if outorg_name:
-                org_out(outorg_name, names)
-            if outpy_name:
-                py_out(outpy_name, names)
-    except FileNotFoundError as exc:  # no cover
-        print(f"FAIL {exc.args[1]} '{exc.filename}'")
-        return 1
-    return 0
+import pathlib
+import re
+
+import rich.console
+
+from rich.table import Table
+
+from p2g import lib
+
+
+# three sorts of py outputs, as an arrays,  as attributes to a
+# class, or straight into global names.
+
+INTO_ARRAY = 0
+INDENT = "    "
+INTO_ATTR = 0
+INDENT = "    "
+
+INTO_GBL = 1
+INDENT = ""
+
+
+def def_prefix(key):
+    if INTO_ARRAY:  # no cover
+        return f'dst["{key}"]'
+    if INTO_ATTR:  # no cover
+        return f"dst.{key}"
+
+    return f"{key}"
+
+
+MAKE_PFX = "p2g."
+
+
+# pylint: disable=invalid-name
+# pylint: disable=too-many-instance-attributes
+# pylint: disable=too-many-statements
+class NAXES:
+    def __init__(self):
+        pass
+
+    def __str__(self):
+        return "NAXES"
+
+
+class MacroVar:
+    def __init__(self, *, key, addr, alias=None, size=None, name="", typ=""):
+        self.typ = typ
+        self.key = key
+        self.addr = addr
+
+        self.name = name
+        self.alias = alias
+        self.size = size
+        suffix = ""
+        self.last = None
+        if isinstance(self.size, NAXES):
+            self.size_as_text = "naxes"
+            self.last = NAXES
+            suffix = "…"
+        else:
+            self.last = self.addr + self.size - 1
+            # that's a non breaking space
+            self.size_as_text = f"{self.size:5}"
+
+            if self.last != self.addr:
+                suffix = f" … #{self.last:5}"
+        self.range_as_text = f"#{self.addr:5}{suffix}".center(15)
+
+    def for_regen(self):
+        funcname = self.__class__.__qualname__
+        res = [str(self.addr)]
+        if self.size is not None:
+            res.append(f"size={self.size}")
+        restxt = ", ".join(res)
+        return f"{def_prefix(self.name)} = {funcname}({restxt})"
+
+    # for the .txt output
+    def for_txt(self):
+        return (
+            self.range_as_text,
+            str(self.size),
+            self.key,
+            self.typ,
+            self.name,
+        )
+
+    def for_org(self):
+        return (
+            f"| <code>{self.name}</code> "
+            + f"| <code>{self.size_as_text}</code>"
+            + f"| <code>{self.range_as_text}</code> |\n"
+        )
+
+    def for_py_out(self):
+        return f"# {self.addr} .. {self.last} {self.name} .."
+
+    def __lt__(self, other):
+        return self.addr < other.addr
+
+
+class Gen(MacroVar):
+    def __init__(
+        self,
+        *,
+        exp_name,
+        idc,
+        addr,
+        size=None,
+        typ,
+    ):
+        self.exp_name = exp_name
+
+        super().__init__(
+            key=idc,
+            addr=addr,
+            size=size,
+            typ=typ,
+        )
+
+    def for_py_out(self):
+        rs = ""
+
+        sstr = ""
+        if self.size is not None and self.size != 1:
+            sstr = f"[{self.size}]"
+        return f"{def_prefix(self.name)} = {MAKE_PFX}Fixed{sstr}({rs}addr={self.addr})"
+
+
+def one(addr, typ="Float"):
+    return Gen(
+        exp_name="Fixed",
+        idc="v" + typ[0],
+        addr=addr,
+        size=1,
+        typ=typ,
+    )
+
+
+def ione(addr):
+    return one(addr, typ="Int")
+
+
+class Alias(MacroVar):
+    def __init__(self, src):
+        super().__init__(key="A", addr=src.addr, size=src.size, alias=src)
+
+    def for_regen(self):
+        assert self.alias is not None
+        return f"{def_prefix(self.name.ljust(20))} = alias({def_prefix}{self.alias.name})"
+
+    def for_py_out(self):
+        assert self.alias is not None
+        return f"{def_prefix(self.name)} = {MAKE_PFX}alias({def_prefix(self.alias.name)})"
+
+    def for_txt(self):
+        return (
+            self.range_as_text,
+            str(self.size),
+            self.key,
+            self.typ,
+            " also " + self.name,
+        )
+
+
+def fixed(addr, size, typ="Float"):
+    return Gen(
+        exp_name="Fixed",
+        idc="V",
+        addr=addr,
+        size=size,
+        typ=typ,
+    )
+
+
+class Gap(MacroVar):
+    C = 0
+
+    def __init__(self, addr, size=None):
+        super().__init__(key="_", addr=addr, size=size)
+        self.name = "-"
+
+    def for_regen(self):
+        self.name = f"gap{Gap.C:02}"
+        Gap.C += 1
+        return super().for_regen()
+
+
+def cwcpos(addr):
+    return Gen(exp_name="CWCPos", idc="m", addr=addr, size=NAXES(), typ="Float")
+
+
+def machinepos(addr):
+    return Gen(exp_name="MachinePos", idc="m", addr=addr, size=NAXES(), typ="Float")
+
+
+def workoffsettable(addr):
+    return Gen(exp_name="WorkOffsetTable", idc="W", addr=addr, typ="Float", size=NAXES())
+
+
+def tooltable(addr, size, typ="Float"):
+    return Gen(exp_name="ToolTable", idc="T", addr=addr, size=size, typ=typ)
+
+
+class PalletTable(MacroVar):
+    def __init__(self, addr, size):
+        super().__init__(key="L", addr=addr, size=size, typ="Int")
+
+
+class Names:
+    interesting: list[MacroVar]
+
+    def __init__(self):
+        object.__setattr__(self, "interesting", [])
+
+    def py_write_to(self, out):
+        for v in self.interesting:
+            out.write(INDENT + v.for_py_out() + "\n")
+
+    def __setattr__(self, key, value):
+        if key[0].isupper():
+            value.name = key
+            object.__setattr__(self, key, value)
+
+        self.interesting.append(value)
+
+
+class HaasNames(Names):
+    title = "HAAS"
+
+    def __init__(self):
+        super().__init__()
+
+        self.NULL = one(0)
+        self.MACRO_ARGUMENTS = fixed(1, size=33)
+        self.gap01 = Gap(34, size=66)
+        self.GP_SAVED1 = fixed(100, size=100)
+        self.gap02 = Gap(200, size=300)
+        self.GP_SAVED2 = fixed(500, size=50)
+
+        self.PROBE_CALIBRATION1 = fixed(550, size=6)
+        self.PROBE_R = fixed(556, size=3)
+        self.PROBE_CALIBRATION2 = fixed(559, size=22)
+
+        self.GP_SAVED3 = fixed(581, size=119)
+        self.gap03 = Gap(700, size=100)
+        self.GP_SAVED4 = fixed(800, size=200)
+        self.INPUTS = fixed(1000, size=64)
+        self.MAX_LOADS_XYZAB = fixed(1064, size=5)
+        self.gap04 = Gap(1069, size=11)
+        self.RAW_ANALOG = fixed(1080, size=10)
+        self.FILTERED_ANALOG = fixed(1090, size=8)
+        self.SPINDLE_LOAD = one(1098)
+        self.gap05 = Gap(1099, size=165)
+        self.MAX_LOADS_CTUVW = fixed(1264, size=5)
+        self.gap06 = Gap(1269, size=332)
+        self.TOOL_TBL_FLUTES = tooltable(1601, size=200, typ="Int")
+        self.TOOL_TBL_VIBRATION = tooltable(1801, size=200)
+        self.TOOL_TBL_OFFSETS = tooltable(2001, size=200)
+        self.TOOL_TBL_WEAR = tooltable(2201, size=200)
+        self.TOOL_TBL_DROFFSET = tooltable(2401, size=200)
+        self.TOOL_TBL_DRWEAR = tooltable(2601, size=200)
+        self.gap07 = Gap(2801, size=199)
+        self.ALARM = one(3000, typ="Int")
+        self.T_MS = one(3001, typ="Time")
+        self.T_HR = one(3002, typ="Time")
+        self.SINGLE_BLOCK_OFF = ione(3003)
+        self.FEED_HOLD_OFF = ione(3004)
+        self.gap08 = Gap(3005, size=1)
+        self.MESSAGE = ione(3006)
+        self.gap09 = Gap(3007, size=4)
+        self.YEAR_MONTH_DAY = one(3011, typ="Time")
+        self.HOUR_MINUTE_SECOND = one(3012, typ="Time")
+        self.gap10 = Gap(3013, size=7)
+        self.POWER_ON_TIME = one(3020, typ="Time")
+        self.CYCLE_START_TIME = one(3021, typ="Time")
+        self.FEED_TIMER = one(3022, typ="Time")
+        self.CUR_PART_TIMER = one(3023, typ="Time")
+        self.LAST_COMPLETE_PART_TIMER = one(3024, typ="Time")
+        self.LAST_PART_TIMER = one(3025, typ="Time")
+        self.TOOL_IN_SPIDLE = ione(3026)
+        self.SPINDLE_RPM = ione(3027)
+        self.PALLET_LOADED = ione(3028)
+        self.gap11 = Gap(3029, size=1)
+        self.SINGLE_BLOCK = ione(3030)
+        self.AGAP = one(3031)
+        self.BLOCK_DELETE = ione(3032)
+        self.OPT_STOP = ione(3033)
+        self.gap12 = Gap(3034, size=162)
+        self.TIMER_CELL_SAFE = one(3196, typ="Time")
+        self.gap13 = Gap(3197, size=4)
+        self.TOOL_TBL_DIAMETER = tooltable(3201, size=200)
+        self.TOOL_TBL_COOLANT_POSITION = tooltable(3401, size=200)
+        self.gap14 = Gap(3601, size=300)
+        self.M30_COUNT1 = ione(3901)
+        self.M30_COUNT2 = ione(3902)
+        self.gap15 = Gap(3903, size=98)
+        self.LAST_BLOCK_G = fixed(4001, size=21)
+        self.gap16 = Gap(4022, size=79)
+        self.LAST_BLOCK_ADDRESS = fixed(4101, size=26)
+        self.gap17 = Gap(4127, size=874)
+        self.LAST_TARGET_POS = cwcpos(5001)
+        self.MACHINE_POS = machinepos(5021)
+        self.WORK_POS = cwcpos(5041)
+        self.SKIP_POS = cwcpos(5061)
+        self.TOOL_OFFSET = fixed(5081, size=20)
+        self.gap18 = Gap(5101, size=100)
+        self.G52 = workoffsettable(5201)
+        self.G54 = workoffsettable(5221)
+        self.G55 = workoffsettable(5241)
+        self.G56 = workoffsettable(5261)
+        self.G57 = workoffsettable(5281)
+        self.G58 = workoffsettable(5301)
+        self.G59 = workoffsettable(5321)
+        self.gap19 = Gap(5341, size=60)
+        self.TOOL_TBL_FEED_TIMERS = tooltable(5401, size=100, typ="Secs")
+        self.TOOL_TBL_TOTAL_TIMERS = tooltable(5501, size=100, typ="Secs")
+        self.TOOL_TBL_LIFE_LIMITS = tooltable(5601, size=100, typ="Int")
+        self.TOOL_TBL_LIFE_COUNTERS = tooltable(5701, size=100, typ="Int")
+        self.TOOL_TBL_LIFE_MAX_LOADS = tooltable(5801, size=100)
+        self.TOOL_TBL_LIFE_LOAD_LIMITS = tooltable(5901, size=100)
+        self.gap20 = Gap(6001, size=197)
+        self.NGC_CF = ione(6198)
+        self.gap21 = Gap(6199, size=802)
+        self.G154_P1 = workoffsettable(7001)
+        self.G154_P2 = workoffsettable(7021)
+        self.G154_P3 = workoffsettable(7041)
+        self.G154_P4 = workoffsettable(7061)
+        self.G154_P5 = workoffsettable(7081)
+        self.G154_P6 = workoffsettable(7101)
+        self.G154_P7 = workoffsettable(7121)
+        self.G154_P8 = workoffsettable(7141)
+        self.G154_P9 = workoffsettable(7161)
+        self.G154_P10 = workoffsettable(7181)
+        self.G154_P11 = workoffsettable(7201)
+        self.G154_P12 = workoffsettable(7221)
+        self.G154_P13 = workoffsettable(7241)
+        self.G154_P14 = workoffsettable(7261)
+        self.G154_P15 = workoffsettable(7281)
+        self.G154_P16 = workoffsettable(7301)
+        self.G154_P17 = workoffsettable(7321)
+        self.G154_P18 = workoffsettable(7341)
+        self.G154_P19 = workoffsettable(7361)
+        self.G154_P20 = workoffsettable(7381)
+        self.gap22 = Gap(7401, size=100)
+        self.PALLET_PRIORITY = PalletTable(7501, size=100)
+        self.PALLET_STATUS = PalletTable(7601, size=100)
+        self.PALLET_PROGRAM = PalletTable(7701, size=100)
+        self.PALLET_USAGE = PalletTable(7801, size=100)
+        self.gap23 = Gap(7901, size=599)
+        self.ATM_ID = ione(8500)
+        self.ATM_PERCENT = one(8501, typ="Percent")
+        self.ATM_TOTAL_AVL_USAGE = ione(8502)
+        self.ATM_TOTAL_AVL_HOLE_COUNT = ione(8503)
+        self.ATM_TOTAL_AVL_FEED_TIME = one(8504, typ="Secs")
+        self.ATM_TOTAL_AVL_TOTAL_TIME = one(8505, typ="Secs")
+        self.gap24 = Gap(8506, size=4)
+        self.ATM_NEXT_TOOL_NUMBER = ione(8510)
+        self.ATM_NEXT_TOOL_LIFE = one(8511, typ="Percent")
+        self.ATM_NEXT_TOOL_AVL_USAGE = ione(8512)
+        self.ATM_NEXT_TOOL_HOLE_COUNT = ione(8513)
+        self.ATM_NEXT_TOOL_FEED_TIME = one(8514, typ="Secs")
+        self.ATM_NEXT_TOOL_TOTAL_TIME = one(8515, typ="Secs")
+        self.gap25 = Gap(8516, size=34)
+        self.TOOL_ID = ione(8550)
+        self.TOOL_FLUTES = ione(8551)
+        self.TOOL_MAX_VIBRATION = one(8552)
+        self.TOOL_LENGTH_OFFSETS = one(8553)
+        self.TOOL_LENGTH_WEAR = one(8554)
+        self.TOOL_DIAMETER_OFFSETS = one(8555)
+        self.TOOL_DIAMETER_WEAR = one(8556)
+        self.TOOL_ACTUAL_DIAMETER = one(8557)
+        self.TOOL_COOLANT_POSITION = ione(8558)
+        self.TOOL_FEED_TIMER = one(8559, typ="Secs")
+        self.TOOL_TOTAL_TIMER = one(8560, typ="Secs")
+        self.TOOL_LIFE_LIMIT = one(8561)
+        self.TOOL_LIFE_COUNTER = one(8562)
+        self.TOOL_LIFE_MAX_LOAD = one(8563)
+        self.TOOL_LIFE_LOAD_LIMIT = one(8564)
+        self.gap26 = Gap(8565, size=435)
+        self.THERMAL_COMP_ACC = one(9000)
+        self.gap27 = Gap(9001, size=15)
+        self.THERMAL_SPINDLE_COMP_ACC = one(9016)
+        self.gap28 = Gap(9017, size=983)
+        self.GVARIABLES3 = fixed(10000, size=1000)
+        self.INPUTS1 = fixed(11000, size=256)
+        self.gap29 = Gap(11256, size=744)
+        self.OUTPUT1 = fixed(12000, size=256)
+        self.gap30 = Gap(12256, size=744)
+        self.FILTERED_ANALOG1 = fixed(13000, size=13)
+        self.COOLANT_LEVEL = one(13013)
+        self.FILTERED_ANALOG2 = fixed(13014, size=50)
+        self.gap31 = Gap(13064, size=936)
+        self.SETTING = fixed(20000, size=10000)
+        self.PARAMETER = fixed(30000, size=10000)
+
+        self.TOOL_TYP = fixed(50001, size=200)
+        self.TOOL_MATERIAL = fixed(50201, size=200)
+        self.gap32 = Gap(50401, 50600)
+        self.gap32 = Gap(51001, 51300)
+        self.CURRENT_OFFSET = fixed(50601, size=200)
+        self.CURRENT_OFFSET2 = fixed(50801, size=200)
+        self.VPS_TEMPLATE_OFFSET = fixed(51301, size=100)
+        self.WORK_MATERIAL = fixed(51401, size=200)
+        self.VPS_FEEDRATE = fixed(51601, size=200)
+
+        self.APPROX_LENGTH = fixed(51801, size=200)
+        self.APPROX_DIAMETER = fixed(52001, size=200)
+        self.EDGE_MEASURE_HEIGHT = fixed(52201, size=200)
+        self.TOOL_TOLERANCE = fixed(52401, size=200)
+        self.PROBE_TYPE = fixed(52601, size=200)
+
+        self.PROBE = Alias(self.SKIP_POS)
+        self.WORK = Alias(self.WORK_POS)
+
+        self.MACHINE = Alias(self.MACHINE_POS)
+        self.G53 = Alias(self.MACHINE_POS)
+
+
+def txt_out(outname, names):
+    guts = Table(
+        title=f"{names.title} Macro Variables",
+        caption=f"Generated by {__file__}",
+    )
+
+    guts.add_column("Range", justify="right")
+    guts.add_column("N", justify="right")
+    guts.add_column("K", justify="right")
+    guts.add_column("Type", justify="center")
+    guts.add_column("Name", justify="left")
+
+    snames = sorted(names.interesting)
+    for el in snames:
+        guts.add_row(*el.for_txt())
+        if el.alias:
+            el = el.alias
+
+    with lib.openw(outname) as out:
+        console = rich.console.Console(file=out)
+        console.print(guts, style=None)
+        print("Generated ", outname)
+
+
+def regen_out(outname, defs):
+    with open(outname, "w", encoding="utf-8") as out:
+        for el in sorted(defs.interesting):
+            out.write("        " + el.for_regen())
+
+
+def org_out(outname, defs):
+    with lib.openw(outname) as out:
+        out.write(
+            "| <code>Name</code>          |  <code>Size</code> | <code>Address</code>         |\n"
+        )
+        out.write("| --- | --- | --- |\n")
+        for el in sorted(defs.interesting):
+            if el.name != "-":
+                out.write(el.for_org())
+
+
+def py_out(target_filename, defs):
+    tmp_filepath = pathlib.Path(target_filename).with_suffix(".tmp")
+
+    with open(target_filename, encoding="utf-8") as inf:
+        repl = re.match(
+            "(.*?# MACHINE GEN BELOW.*?).*(.*?# MACHINE.*)",
+            inf.read(),
+            flags=re.DOTALL,
+        )
+    if repl is not None:
+        with open(tmp_filepath, "w", encoding="utf-8") as out:
+            out.write(repl.group(1) + "\n")
+            defs.py_write_to(out)
+            out.write(INDENT + repl.group(2))
+        tmp_filepath.rename(target_filename)
+
+
+def makestdvars(outtxt_name, outdef_name, outpy_name, outorg_name):
+    try:
+        for names in [HaasNames()]:
+            if outtxt_name:
+                txt_out(outtxt_name, names)
+            if outdef_name:
+                regen_out(outdef_name, names)
+            if outorg_name:
+                org_out(outorg_name, names)
+            if outpy_name:
+                py_out(outpy_name, names)
+    except FileNotFoundError as exc:  # no cover
+        print(f"FAIL {exc.args[1]} '{exc.filename}'")
+        return 1
+    return 0
```

### Comparing `p2g-0.1.95/p2g/mvarsorig` & `p2g-0.2.29/p2g/mvarsorig`

 * *Files identical despite different names*

### Comparing `p2g-0.1.95/p2g/op.py` & `p2g-0.2.29/p2g/op.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,494 +1,498 @@
-import abc
-import ast
-import math
-import typing
-
-from p2g import err
-from p2g import gbl
-from p2g import lib
-from p2g import nd
-from p2g import opinfo
-from p2g import scalar
-from p2g import vector
-
-
-OptRes = typing.Optional[scalar.Scalar]
-
-op_byclass: typing.Dict[typing.Any, opinfo.Opinfo] = {}
-allops: typing.Dict[str, opinfo.Opinfo] = {}
-
-
-def parensif(cond, thing):
-    if cond:
-        return "[" + thing + "]"
-    return thing
-
-
-def get_prec(thing):
-    return getattr(thing, "prec", 20)
-
-
-class Binop(scalar.Scalar):
-    def __init__(self, opfo, lhs, rhs):
-        super().__init__(opfo)
-        assert opfo.pyn != "-rev"
-        self.lhs = lhs
-        self.rhs = rhs
-
-    def same(self, other):
-        return (
-            self.opfo == other.opfo
-            and lib.same(self.lhs, other.lhs)
-            and lib.same(self.rhs, other.rhs)
-        )
-
-    def to_gcode(self, modi: nd.NodeModifier) -> str:
-        if self.opfo.g_func:
-            res = [
-                nd.to_gcode(self.lhs, modi),
-                nd.to_gcode(self.rhs, modi),
-            ]
-            return f"{self.opfo.gname}[{','.join(res)}]"
-
-        res = []
-
-        outer_prec = self.opfo.prec
-
-        def handle_term(node):
-            return parensif(
-                get_prec(node) < outer_prec,
-                nd.to_gcode(node, modi),
-            )
-
-        res.append(handle_term(self.lhs))
-        res.append(self.opfo.gname)
-        res.append(handle_term(self.rhs))
-
-        if modi & nd.NodeModifier.NOSPACE:
-            return "".join(res)
-        return " ".join(res)
-
-    def __repr__(self):
-        return f"({self.lhs}{self.opfo.pyn}{self.rhs})"
-
-
-def make_scalar_binop(opfo, lhs, rhs):
-    # can it be done right now?
-    if isinstance(rhs, scalar.ConstantNone):
-        rhs = scalar.wrap_scalar(0)
-    if isinstance(lhs, scalar.Constant) and isinstance(rhs, scalar.Constant):
-        lval = lhs.value
-        rval = rhs.value
-        if isinstance(lval, float) or isinstance(rval, float):
-            lval = float(lval)
-            rval = float(rval)
-        if opfo.pyn == "round":
-            rval = int(rval)
-        res = getattr(lval, opfo.mth)(rval)
-        return scalar.Constant(res)
-    # put contant on rhs if we can
-    if (
-        opfo.comm
-        and isinstance(lhs, scalar.Constant)
-        and not isinstance(rhs, scalar.Constant)
-    ):
-        lhs, rhs = rhs, lhs
-
-    if opfo.opt2 and (res := opfo.opt2(opfo, lhs, rhs)) is not None:
-        return res
-
-    return Binop(opfo, lhs, rhs)
-
-
-def make_scalar_add(lhs, rhs):
-    return make_scalar_binop(allops["+"], lhs, rhs)
-
-
-def a2opfo(optyp):
-    return op_byclass[optyp]
-
-
-def opt1_func(opfo, arg) -> OptRes:
-    if not isinstance(arg, scalar.Constant):
-        return None
-
-    return scalar.wrap_scalar(opfo.lam(arg.to_float()))
-
-
-class Unop(scalar.Scalar):
-    def __init__(self, opfo, child):
-        super().__init__(opfo)
-        self.child = child
-
-    def get_address(self):
-        return self.child
-
-    def same(self, other):
-        return self.opfo == other.opfo and lib.same(self.child, other.child)
-
-    def to_gcode(self, modifier=nd.NodeModifier.EMPTY):
-        res = []
-
-        if self.opfo.pyn == "#":
-            gbl.iface.add_varref(self.child)
-
-        outer_prec = self.opfo.prec
-
-        res.append(self.opfo.gname)
-        # at least # is left right associative.
-        inside_prec = get_prec(self.child)
-
-        if self.opfo.pyn == "#":
-            modifier |= nd.NodeModifier.ADDRESS
-
-        res.append(
-            parensif(
-                outer_prec >= inside_prec,
-                nd.to_gcode(self.child, modifier),
-            )
-        )
-
-        return "".join(res)
-
-    def __repr__(self):
-        return f"({self.opfo.pyn} {self.child})"
-
-
-def make_scalar_unop(opfo, child: scalar.Scalar):
-    child = scalar.wrap_scalar(child)
-    if opfo.opt1 and (res := opfo.opt1(opfo, child)) is not None:
-        return res
-
-    if isinstance(child, scalar.Constant):
-        return scalar.wrap_scalar(getattr(child.value, opfo.mth)())
-
-    return Unop(opfo, child)
-
-
-def make_vec_binop(opfo, lhs, rhs=None, force_ourtype=False):
-    if not force_ourtype and not isinstance(lhs, (int, float, nd.EBase)):
-        return getattr(lhs, opfo.mth)(rhs)
-
-    lhs = vector.wrap_maybe_vec(lhs)
-
-    if rhs is None:
-        # actually unop.
-
-        return vector.sorv_from_list(
-            [make_scalar_unop(opfo, el) for el in lhs.everything()]
-        )
-    rhs = vector.wrap_maybe_vec(rhs)
-    return vector.sorv_from_list(
-        [
-            make_scalar_binop(opfo, lel, rel)
-            for lel, rel in zip(lhs.everything(), rhs.forever())
-        ]
-    )
-
-
-def make_scalar_func(fname, *args):
-    ofo = allops[fname]
-    return make_vec_binop(ofo, args[0], force_ourtype=True)
-
-
-class MAST(abc.ABC):
-    opfo: opinfo.Opinfo
-
-
-MAST.register(ast.AST)
-
-
-class HASH(MAST):
-    pass
-
-
-class ABS(MAST):
-    pass
-
-
-class RSUB(MAST):
-    pass
-
-
-class ROUND(MAST):
-    pass
-
-
-revop = {
-    "+": "+",
-    "-": "+",
-    "*": "*",
-    "/": "*",
-}
-
-
-# a  + k1  + k2 -> a + (k1+k2)
-def opt2_fold(opfo, lhs, rhs) -> OptRes:
-    rop = revop.get(opfo.pyn)
-
-    if (
-        rop
-        and isinstance(lhs, Binop)
-        and lhs.opfo == opfo
-        and lhs.rhs.is_constant
-        and rhs.is_constant
-    ):
-        return make_scalar_binop(
-            opfo,
-            lhs.lhs,
-            make_scalar_binop(
-                allops[rop],
-                lhs.rhs,
-                rhs,
-            ),
-        )
-
-    return None
-
-
-def opt2_mul(opfo, lhs, rhs) -> OptRes:
-    match rhs.to_float():
-        case 0.0:
-            return scalar.Constant(0.0)
-        case 1.0:
-            return lhs
-        case -1.0:
-            return make_scalar_unop(allops["un-"], lhs)
-
-    return opt2_fold(opfo, lhs, rhs)
-
-
-def opt2_div(opfo, lhs, rhs) -> OptRes:
-    match rhs.to_float():
-        case None:
-            return None
-        case 0.0:
-            err.compiler("Attempt to divide by zero.")
-        case 1.0:
-            return lhs
-        case -1.0:
-            return make_scalar_unop(allops["un-"], lhs)
-
-    return opt2_fold(opfo, lhs, rhs)
-
-
-not_compop = {
-    "==": "!=",
-    "!=": "==",
-    "<": ">=",
-    ">": "<=",
-    "<=": ">",
-    ">=": "<",
-}
-
-
-def opt1_not(_opinfo, arg) -> OptRes:
-    if arg.is_constant:
-        return scalar.Constant(not arg.value)
-
-    # got not(comop, turn into (inverted compop))
-
-    if notted := not_compop.get(arg.opfo.pyn):
-        return make_scalar_binop(allops[notted], arg.lhs, arg.rhs)
-
-    rhs = scalar.Constant(0)
-    return make_scalar_binop(allops["!="], arg, rhs)
-
-
-def opt1_plus(_, arg) -> OptRes:
-    return arg
-
-
-# don't have binary not operator, make from xor.
-def opt1_invert(_, arg) -> OptRes:
-    rhs = scalar.wrap_scalar(-1)
-    return make_scalar_binop(allops["^"], arg, rhs)
-
-
-# turn a1 > a2  == 0
-# => (a1 <= a2)
-
-
-def opt2_eq(opfo, lhs: scalar.Scalar, rhs: scalar.Scalar) -> OptRes:
-    if lib.same(lhs, rhs):
-        return scalar.Constant(opfo.pyn == "==")
-
-    if not isinstance(rhs, scalar.Constant) or rhs.value != 0.0:
-        return None
-
-    if isinstance(lhs, Binop):
-        if rev := not_compop.get(lhs.opfo.pyn):
-            if opfo.pyn == "==":
-                return make_scalar_binop(
-                    allops[rev],
-                    lhs.lhs,
-                    lhs.rhs,
-                )
-            return lhs
-    return None
-
-
-def opt2_matmul(_opfo, _lhs, _rhs) -> OptRes:  # for debug
-    return None
-
-
-def opt2_add(opfo, lhs, rhs) -> OptRes:
-    if (res := opt2_fold(opfo, lhs, rhs)) is not None:
-        return res
-
-    if isinstance(rhs, Unop) and rhs.opfo.pyn == "un-":
-        return make_scalar_binop(allops["-"], lhs, rhs.child)
-
-    if isinstance(rhs, scalar.Constant):
-        rhsv = rhs.to_float()
-        if rhsv < 0.0:
-            return make_scalar_binop(allops["-"], lhs, -rhsv)
-        if rhsv == 0.0:
-            return lhs
-
-    return None
-
-
-def make_fmt(val, fmt):
-    if isinstance(val, str):
-        return val
-    val = scalar.wrap_scalar(val)
-    if isinstance(val, scalar.Constant):
-        if fmt and fmt[-1] == "x":
-            return format(val.to_int(), fmt)
-        return format(val.to_float(), fmt)
-    gfmt = f"[{fmt[0]}{fmt[2]}]" if fmt else ""
-
-    return "[" + val.to_gcode(nd.NodeModifier.NOSPACE) + "]" + gfmt
-
-
-def opt2_sub(opfo, lhs, rhs) -> OptRes:
-    if (res := opt2_fold(opfo, lhs, rhs)) is not None:
-        return res
-
-    # a -  - b -> a + b
-    if isinstance(rhs, Unop) and rhs.opfo.pyn == "un-":
-        return make_scalar_binop(allops["+"], lhs, rhs.child)
-
-    if isinstance(rhs, scalar.Constant):
-        rhsv = rhs.to_float()
-        if rhsv == 0.0:
-            return lhs
-
-    return None
-
-
-def unwrap_int(val):
-    try:
-        return val.to_int()
-    except AttributeError:
-        return val
-
-
-def make_slice(low, high, step):
-    return slice(
-        unwrap_int(low),
-        unwrap_int(high),
-        unwrap_int(step),
-    )
-
-
-def hashop(arg):
-    return Unop(allops["#"], arg)
-
-
-def make_hashop(lhs, rhs):
-    return hashop(make_scalar_add(lhs, rhs))
-
-
-vector.MemVec.make_hashop = make_hashop
-
-
-def opinfo_install(opfo: opinfo.Opinfo):
-    def make_multi_binop_tramp(lhs, rhs):
-        return make_vec_binop(opfo, lhs, rhs)
-
-    def make_multi_unop_tramp(child):
-        return vector.sorv_from_list(
-            [make_scalar_unop(opfo, cel) for cel in child.everything()]
-        )
-
-    def make_scalar_binop_tramp(lhs, rhs):
-        return make_scalar_binop(opfo, lhs, scalar.wrap_scalar(rhs))
-
-    def make_scalar_unop_tramp(child):
-        return make_scalar_unop(opfo, child)
-
-    if opfo.mth:
-        if isinstance(opfo.mth, str):
-            if opfo.nargs == 1:
-                setattr(vector.Vec, opfo.mth, make_multi_unop_tramp)
-                setattr(scalar.Scalar, opfo.mth, make_scalar_unop_tramp)
-            else:
-                setattr(vector.Vec, opfo.mth, make_multi_binop_tramp)
-                setattr(scalar.Scalar, opfo.mth, make_scalar_binop_tramp)
-
-
-def reg(**kwargs):
-    opi = opinfo.Opinfo(**kwargs)
-    allops[opi.pyn] = opi
-    op_byclass[opi.astc] = opi
-    opinfo_install(opi)
-
-
-def regfunc(name, lam):
-    reg(
-        pyn=name,
-        lam=lam,
-        gname=name.upper(),
-        prec=20,
-        nargs=1,
-        opt1=opt1_func,
-    )
-
-
-regfunc("cos", lambda x: math.cos(math.radians(x)))
-regfunc("sin", lambda x: math.sin(math.radians(x)))
-regfunc("tan", lambda x: math.tan(math.radians(x)))
-regfunc("acos", lambda x: math.degrees(math.acos(x)))
-regfunc("asin", lambda x: math.degrees(math.asin(x)))
-regfunc("atan", lambda x: math.degrees(math.atan(x)))
-regfunc("exp", math.exp)
-regfunc("ln", math.log)
-regfunc("sqrt", math.sqrt)
-regfunc("exists", id)
-regfunc("fup", math.ceil)
-regfunc("fix", math.floor)
-regfunc("ground", round)
-
-
-# fmt: off
-# noqa: E203
-reg(astc=ast.BitOr    , pyn="|"     , mth="__or__"       , gname="OR"    , prec=4, comm=True)
-reg(astc=ast.BitXor   , pyn="^"     , mth="__xor__"      , gname="XOR"   , prec=5, comm=True)
-reg(astc=ast.BitAnd   , pyn="&"     , mth="__and__"      , gname="AND"   , prec=6, comm=True)
-reg(astc=ast.Lt       , pyn="<"     , mth="__lt__"       , gname="LT"    , prec=10)
-reg(astc=ast.LtE      , pyn="<="    , mth="__le__"       , gname="LE"    , prec=10)
-reg(astc=ast.NotEq    , pyn="!="    , mth="__ne__"       , gname="NE"    , prec=10, comm=True, opt2=opt2_eq)
-reg(astc=ast.Eq       , pyn="=="    , mth="__eq__"       , gname="EQ"    , prec=10, comm=True, opt2=opt2_eq)
-reg(astc=ast.Gt       , pyn=">"     , mth="__gt__"       , gname="GT"    , prec=10)
-reg(astc=ast.GtE      , pyn=">="    , mth="__ge__"       , gname="GE"    , prec=10)
-reg(astc=ast.Sub      , pyn="-"     , mth="__sub__"      , gname="-"     , prec=12, opt2=opt2_sub)
-reg(astc=None         , pyn="-rev"  , mth="__rsub__"     , gname="-rev"  , prec=12)
-reg(astc=ast.Add      , pyn="+"     , mth="__add__"      , gname="+"     , prec=12, comm=True, opt2=opt2_add)
-reg(astc=None         , pyn="round" , mth="__round__"    , gname="round" , prec=12)
-reg(astc=ast.Mult     , pyn="*"     , mth="__mul__"      , gname="*"     , prec=13, comm=True, opt2=opt2_mul)
-reg(astc=ast.Div      , pyn="/"     , mth="__truediv__"  , gname="/"     , prec=13, opt2=opt2_div)
-reg(astc=ast.FloorDiv , pyn="//"    , mth="__floordiv__" , gname="//"    , prec=13, opt2=opt2_div)
-reg(astc=ast.Mod      , pyn="%"     , mth="__mod__"      , gname="MOD"   , prec=14)
-reg(astc=ast.Pow      , pyn="**"    , mth="__pow__"      , gname="POW"   , prec=15, g_func=True)
-reg(astc=ast.USub     , pyn="un-"   , mth="__neg__"      , gname="-"     , prec=14, nargs=1)
-reg(astc=ast.UAdd     , pyn="un+"   , mth="__pos__"      , gname="+"     , prec=14, nargs=1, opt1=opt1_plus)
-reg(astc=ast.MatMult  , pyn="m*"    , mth=""             , gname="ERRR"  , prec=20, nargs=2, opt2=opt2_matmul)
-reg(astc=ast.Invert   , pyn="un~"   , mth="__invert__"   , gname="un~"   , prec=14, nargs=1, opt1=opt1_invert)
-reg(astc=ast.Not      , pyn="unot"  , mth=""             , gname="unot"  , prec=14, nargs=1, opt1=opt1_not)
-reg(astc=None         , pyn="abs"   , mth="__abs__"      , gname="ABS"   , prec=15, nargs=1, g_func=True)
-reg(astc=None         , pyn="#"     , mth=""             , gname="#"     , prec=19, nargs=1)
-
-
-# fmt:on
+import abc
+import ast
+import math
+import typing
+
+from p2g import err
+from p2g import lib
+from p2g import nd
+from p2g import scalar
+from p2g import symbol
+from p2g import vector
+
+
+OptRes = typing.Optional[scalar.Scalar]
+ScalarScalar = typing.Union[scalar.Scalar, int, float, bool]
+
+op_byclass: typing.Dict[typing.Any, nd.Opinfo] = {}
+allops: typing.Dict[str, nd.Opinfo] = {}
+
+
+def parensif(cond, thing):
+    if cond:
+        return "[" + thing + "]"
+    return thing
+
+
+def get_prec(thing):
+    return getattr(thing, "prec", 20)
+
+
+class Binop(scalar.Scalar):
+    def __init__(self, opfo, lhs, rhs):
+        super().__init__(opfo)
+        assert opfo.pyn != "-rev"
+        self.lhs = lhs
+        self.rhs = rhs
+
+    def same(self, other):
+        return (
+            self.opfo == other.opfo
+            and lib.same(self.lhs, other.lhs)
+            and lib.same(self.rhs, other.rhs)
+        )
+
+    def to_gcode(self, modi: nd.NodeModifier) -> str:
+        if self.opfo.g_func:
+            res = [
+                nd.to_gcode(self.lhs, modi),
+                nd.to_gcode(self.rhs, modi),
+            ]
+            return f"{self.opfo.gname}[{','.join(res)}]"
+
+        res = []
+
+        outer_prec = self.opfo.prec
+
+        def handle_term(node):
+            return parensif(
+                get_prec(node) < outer_prec,
+                nd.to_gcode(node, modi),
+            )
+
+        res.append(handle_term(self.lhs))
+        res.append(self.opfo.gname)
+        res.append(handle_term(self.rhs))
+
+        if modi & nd.NodeModifier.NOSPACE:
+            return "".join(res)
+        return " ".join(res)
+
+    def __repr__(self):
+        return f"({self.lhs}{self.opfo.pyn}{self.rhs})"
+
+
+def make_scalar_binop(opfo, lhs, rhs):
+    # can it be done right now?
+    if isinstance(rhs, scalar.ConstantNone):
+        rhs = scalar.wrap_scalar(0)
+    if isinstance(lhs, scalar.Constant) and isinstance(rhs, scalar.Constant):
+        lval = lhs.value
+        rval = rhs.value
+        if isinstance(lval, float) or isinstance(rval, float):
+            lval = float(lval)
+            rval = float(rval)
+        if opfo.pyn == "round":
+            rval = int(rval)
+        res = getattr(lval, opfo.mth)(rval)
+        return scalar.Constant(res)
+    # put contant on rhs if we can
+    if (
+        opfo.comm
+        and isinstance(lhs, scalar.Constant)
+        and not isinstance(rhs, scalar.Constant)
+    ):
+        lhs, rhs = rhs, lhs
+
+    if opfo.opt2 and (res := opfo.opt2(opfo, lhs, rhs)) is not None:
+        return res
+
+    return Binop(opfo, lhs, rhs)
+
+
+def make_scalar_add(lhs, rhs):
+    return make_scalar_binop(allops["+"], lhs, rhs)
+
+
+def a2opfo(optyp):
+    return op_byclass[optyp]
+
+
+def opt1_func(opfo, arg) -> OptRes:
+    if not isinstance(arg, scalar.Constant):
+        return None
+
+    return scalar.wrap_scalar(opfo.lam(arg.to_float()))
+
+
+class Unop(scalar.Scalar):
+    def __init__(self, opfo, child):
+        super().__init__(opfo)
+        self.child = child
+
+    def get_address(self):
+        return self.child
+
+    def same(self, other):
+        return self.opfo == other.opfo and lib.same(self.child, other.child)
+
+    def to_gcode(self, modifier=nd.NodeModifier.EMPTY):
+        res = []
+
+        if self.opfo.pyn == "#":
+            try:
+                addr = int(self.child)
+                symbol.Table.add_varref(addr, err.state.last_pos)
+            except TypeError:
+                pass
+
+        outer_prec = self.opfo.prec
+
+        res.append(self.opfo.gname)
+        # at least # is left right associative.
+        inside_prec = get_prec(self.child)
+
+        if self.opfo.pyn == "#":
+            modifier |= nd.NodeModifier.ADDRESS
+
+        res.append(
+            parensif(
+                outer_prec >= inside_prec,
+                nd.to_gcode(self.child, modifier),
+            )
+        )
+
+        return "".join(res)
+
+    def __repr__(self):
+        return f"({self.opfo.pyn} {self.child})"
+
+
+def make_scalar_unop(opfo, child: ScalarScalar):
+    child = scalar.wrap_scalar(child)
+    if opfo.opt1 and (res := opfo.opt1(opfo, child)) is not None:
+        return res
+
+    if isinstance(child, scalar.Constant):
+        return scalar.wrap_scalar(getattr(child.value, opfo.mth)())
+
+    return Unop(opfo, child)
+
+
+def make_vec_binop(opfo, lhs, rhs=None, force_ourtype=False):
+    if not force_ourtype and not isinstance(lhs, (int, float, nd.EBase)):
+        return getattr(lhs, opfo.mth)(rhs)
+
+    lhs = vector.wrap_maybe_vec(lhs)
+
+    if rhs is None:
+        # actually unop.
+
+        return vector.sorv_from_list(
+            [make_scalar_unop(opfo, el) for el in lhs.everything()]
+        )
+    rhs = vector.wrap_maybe_vec(rhs)
+    return vector.sorv_from_list(
+        [
+            make_scalar_binop(opfo, lel, rel)
+            for lel, rel in zip(lhs.everything(), rhs.forever())
+        ]
+    )
+
+
+def make_scalar_func(fname, *args):
+    ofo = allops[fname]
+    return make_vec_binop(ofo, args[0], force_ourtype=True)
+
+
+class MAST(abc.ABC):
+    opfo: nd.Opinfo
+
+
+MAST.register(ast.AST)
+
+
+class HASH(MAST):
+    pass
+
+
+class ABS(MAST):
+    pass
+
+
+class RSUB(MAST):
+    pass
+
+
+class ROUND(MAST):
+    pass
+
+
+revop = {
+    "+": "+",
+    "-": "+",
+    "*": "*",
+    "/": "*",
+}
+
+
+# a  + k1  + k2 -> a + (k1+k2)
+def opt2_fold(opfo, lhs, rhs) -> OptRes:
+    rop = revop.get(opfo.pyn)
+
+    if (
+        rop
+        and isinstance(lhs, Binop)
+        and lhs.opfo == opfo
+        and lhs.rhs.is_constant
+        and rhs.is_constant
+    ):
+        return make_scalar_binop(
+            opfo,
+            lhs.lhs,
+            make_scalar_binop(
+                allops[rop],
+                lhs.rhs,
+                rhs,
+            ),
+        )
+
+    return None
+
+
+def opt2_mul(opfo, lhs, rhs) -> OptRes:
+    match rhs.to_float():
+        case 0.0:
+            return scalar.Constant(0.0)
+        case 1.0:
+            return lhs
+        case -1.0:
+            return make_scalar_unop(allops["un-"], lhs)
+
+    return opt2_fold(opfo, lhs, rhs)
+
+
+def opt2_div(opfo, lhs, rhs) -> OptRes:
+    match rhs.to_float():
+        case None:
+            return None
+        case 0.0:
+            err.compiler("Attempt to divide by zero.")
+        case 1.0:
+            return lhs
+        case -1.0:
+            return make_scalar_unop(allops["un-"], lhs)
+
+    return opt2_fold(opfo, lhs, rhs)
+
+
+not_compop = {
+    "==": "!=",
+    "!=": "==",
+    "<": ">=",
+    ">": "<=",
+    "<=": ">",
+    ">=": "<",
+}
+
+
+def opt1_not(_nd, arg) -> OptRes:
+    if arg.is_constant:
+        return scalar.Constant(not arg.value)
+
+    # got not(comop, turn into (inverted compop))
+
+    if notted := not_compop.get(arg.opfo.pyn):
+        return make_scalar_binop(allops[notted], arg.lhs, arg.rhs)
+
+    rhs = scalar.Constant(0)
+    return make_scalar_binop(allops["!="], arg, rhs)
+
+
+def opt1_plus(_, arg) -> OptRes:
+    return arg
+
+
+# don't have binary not operator, make from xor.
+def opt1_invert(_, arg) -> OptRes:
+    rhs = scalar.wrap_scalar(-1)
+    return make_scalar_binop(allops["^"], arg, rhs)
+
+
+# turn a1 > a2  == 0
+# => (a1 <= a2)
+
+
+def opt2_eq(opfo, lhs: scalar.Scalar, rhs: scalar.Scalar) -> OptRes:
+    if lib.same(lhs, rhs):
+        return scalar.Constant(opfo.pyn == "==")
+
+    if not isinstance(rhs, scalar.Constant) or rhs.value != 0.0:
+        return None
+
+    if isinstance(lhs, Binop):
+        if rev := not_compop.get(lhs.opfo.pyn):
+            if opfo.pyn == "==":
+                return make_scalar_binop(
+                    allops[rev],
+                    lhs.lhs,
+                    lhs.rhs,
+                )
+            return lhs
+    return None
+
+
+def opt2_matmul(_opfo, _lhs, _rhs) -> OptRes:  # for debug
+    return None
+
+
+def opt2_add(opfo, lhs, rhs) -> OptRes:
+    if (res := opt2_fold(opfo, lhs, rhs)) is not None:
+        return res
+
+    if isinstance(rhs, Unop) and rhs.opfo.pyn == "un-":
+        return make_scalar_binop(allops["-"], lhs, rhs.child)
+
+    if isinstance(rhs, scalar.Constant):
+        rhsv = rhs.to_float()
+        if rhsv < 0.0:
+            return make_scalar_binop(allops["-"], lhs, -rhsv)
+        if rhsv == 0.0:
+            return lhs
+
+    return None
+
+
+def make_fmt(val, fmt):
+    if isinstance(val, str):
+        return val
+    val = scalar.wrap_scalar(val)
+    if isinstance(val, scalar.Constant):
+        if fmt and fmt[-1] == "x":
+            return format(val.to_int(), fmt)
+        return format(val.to_float(), fmt)
+    gfmt = f"[{fmt[0]}{fmt[2]}]" if fmt else ""
+
+    return "[" + val.to_gcode(nd.NodeModifier.NOSPACE) + "]" + gfmt
+
+
+def opt2_sub(opfo, lhs, rhs) -> OptRes:
+    if (res := opt2_fold(opfo, lhs, rhs)) is not None:
+        return res
+
+    # a -  - b -> a + b
+    if isinstance(rhs, Unop) and rhs.opfo.pyn == "un-":
+        return make_scalar_binop(allops["+"], lhs, rhs.child)
+
+    if isinstance(rhs, scalar.Constant):
+        rhsv = rhs.to_float()
+        if rhsv == 0.0:
+            return lhs
+
+    return None
+
+
+def unwrap_int(val):
+    try:
+        return val.to_int()
+    except AttributeError:
+        return val
+
+
+def make_slice(low, high, step):
+    return slice(
+        unwrap_int(low),
+        unwrap_int(high),
+        unwrap_int(step),
+    )
+
+
+def hashop(arg):
+    return Unop(allops["#"], arg)
+
+
+def make_hashop(lhs, rhs):
+    return hashop(make_scalar_add(lhs, rhs))
+
+
+vector.MemVec.make_hashop = make_hashop
+
+
+def nd_install(opfo: nd.Opinfo):
+    def make_multi_binop_tramp(lhs, rhs):
+        return make_vec_binop(opfo, lhs, rhs)
+
+    def make_multi_unop_tramp(child):
+        return vector.sorv_from_list(
+            [make_scalar_unop(opfo, cel) for cel in child.everything()]
+        )
+
+    def make_scalar_binop_tramp(lhs, rhs):
+        return make_scalar_binop(opfo, lhs, scalar.wrap_scalar(rhs))
+
+    def make_scalar_unop_tramp(child):
+        return make_scalar_unop(opfo, child)
+
+    if opfo.mth:
+        if isinstance(opfo.mth, str):
+            if opfo.nargs == 1:
+                setattr(vector.Vec, opfo.mth, make_multi_unop_tramp)
+                setattr(scalar.Scalar, opfo.mth, make_scalar_unop_tramp)
+            else:
+                setattr(vector.Vec, opfo.mth, make_multi_binop_tramp)
+                setattr(scalar.Scalar, opfo.mth, make_scalar_binop_tramp)
+
+
+def reg(**kwargs):
+    opi = nd.Opinfo(**kwargs)
+    allops[opi.pyn] = opi
+    op_byclass[opi.astc] = opi
+    nd_install(opi)
+
+
+def regfunc(name, lam):
+    reg(
+        pyn=name,
+        lam=lam,
+        gname=name.upper(),
+        prec=20,
+        nargs=1,
+        opt1=opt1_func,
+    )
+
+
+regfunc("cos", lambda x: math.cos(math.radians(x)))
+regfunc("sin", lambda x: math.sin(math.radians(x)))
+regfunc("tan", lambda x: math.tan(math.radians(x)))
+regfunc("acos", lambda x: math.degrees(math.acos(x)))
+regfunc("asin", lambda x: math.degrees(math.asin(x)))
+regfunc("atan", lambda x: math.degrees(math.atan(x)))
+regfunc("exp", math.exp)
+regfunc("ln", math.log)
+regfunc("sqrt", math.sqrt)
+regfunc("exists", id)
+regfunc("fup", math.ceil)
+regfunc("fix", math.floor)
+regfunc("ground", round)
+
+
+# fmt: off
+# noqa: E203
+reg(astc=ast.BitOr    , pyn="|"     , mth="__or__"       , gname="OR"    , prec=4, comm=True)
+reg(astc=ast.BitXor   , pyn="^"     , mth="__xor__"      , gname="XOR"   , prec=5, comm=True)
+reg(astc=ast.BitAnd   , pyn="&"     , mth="__and__"      , gname="AND"   , prec=6, comm=True)
+reg(astc=ast.Lt       , pyn="<"     , mth="__lt__"       , gname="LT"    , prec=10)
+reg(astc=ast.LtE      , pyn="<="    , mth="__le__"       , gname="LE"    , prec=10)
+reg(astc=ast.NotEq    , pyn="!="    , mth="__ne__"       , gname="NE"    , prec=10, comm=True, opt2=opt2_eq)
+reg(astc=ast.Eq       , pyn="=="    , mth="__eq__"       , gname="EQ"    , prec=10, comm=True, opt2=opt2_eq)
+reg(astc=ast.Gt       , pyn=">"     , mth="__gt__"       , gname="GT"    , prec=10)
+reg(astc=ast.GtE      , pyn=">="    , mth="__ge__"       , gname="GE"    , prec=10)
+reg(astc=ast.Sub      , pyn="-"     , mth="__sub__"      , gname="-"     , prec=12, opt2=opt2_sub)
+reg(astc=None         , pyn="-rev"  , mth="__rsub__"     , gname="-rev"  , prec=12)
+reg(astc=ast.Add      , pyn="+"     , mth="__add__"      , gname="+"     , prec=12, comm=True, opt2=opt2_add)
+reg(astc=None         , pyn="round" , mth="__round__"    , gname="round" , prec=12)
+reg(astc=ast.Mult     , pyn="*"     , mth="__mul__"      , gname="*"     , prec=13, comm=True, opt2=opt2_mul)
+reg(astc=ast.Div      , pyn="/"     , mth="__truediv__"  , gname="/"     , prec=13, opt2=opt2_div)
+reg(astc=ast.FloorDiv , pyn="//"    , mth="__floordiv__" , gname="//"    , prec=13, opt2=opt2_div)
+reg(astc=ast.Mod      , pyn="%"     , mth="__mod__"      , gname="MOD"   , prec=14)
+reg(astc=ast.Pow      , pyn="**"    , mth="__pow__"      , gname="POW"   , prec=15, g_func=True)
+reg(astc=ast.USub     , pyn="un-"   , mth="__neg__"      , gname="-"     , prec=14, nargs=1)
+reg(astc=ast.UAdd     , pyn="un+"   , mth="__pos__"      , gname="+"     , prec=14, nargs=1, opt1=opt1_plus)
+reg(astc=ast.MatMult  , pyn="m*"    , mth=""             , gname="ERRR"  , prec=20, nargs=2, opt2=opt2_matmul)
+reg(astc=ast.Invert   , pyn="un~"   , mth="__invert__"   , gname="un~"   , prec=14, nargs=1, opt1=opt1_invert)
+reg(astc=ast.Not      , pyn="unot"  , mth=""             , gname="unot"  , prec=14, nargs=1, opt1=opt1_not)
+reg(astc=None         , pyn="abs"   , mth="__abs__"      , gname="ABS"   , prec=15, nargs=1, g_func=True)
+reg(astc=None         , pyn="#"     , mth=""             , gname="#"     , prec=19, nargs=1)
+
+
+# fmt:on
```

### Comparing `p2g-0.1.95/p2g/ptest.py` & `p2g-0.2.29/p2g/ptest.py`

 * *Files 21% similar despite different names*

```diff
@@ -1,265 +1,274 @@
-import functools
-import inspect
-import itertools
-import pathlib
-import typing
-
-import pytest
-
-from p2g import err
-from p2g import gbl
-from p2g import lib
-from p2g import walk
-
-
-# takes fn, works out where it lives, where to find golden output and
-# where to put test output
-# test_foo.py (test_zap) will make a tests/golden/foo_zap.nc file.
-
-
-def make_file_path(func, new_suffix) -> pathlib.Path:
-    # this_file_path <- <somewhere>/ptest.py
-    this_file_path = pathlib.Path(__file__)
-    # this_file_directory <- <somewhere>/p2g
-    this_file_directory = this_file_path.parent
-
-    # file_part <- function's filename
-    file_part = str(pathlib.Path(func.__code__.co_filename).stem)
-    file_part = file_part.replace("test_", "")
-
-    # can be in <srcdir>/tests or ../tests depending upon
-    # if run installed or not. Look for testdir.
-
-    for tests_dir in [
-        this_file_directory / "tests",
-        this_file_directory.parent / "tests",
-    ]:
-        if (tests_dir / "golden").exists():
-            break
-    else:  # pragma: no cover
-        err.compiler("can't find tests")
-
-    # generated_dir <- <somewhere>/tests/golden
-    generated_dir = tests_dir / "golden"
-    generated_dir.mkdir(exist_ok=True)
-    #  <somewhere>/tests/golden/foo_zap.nc
-
-    new_filename = func.__name__.replace("test", file_part)
-    return (generated_dir / new_filename).with_suffix(new_suffix)
-
-
-def strip_comments(txt):
-    txt = txt.replace(" ", "")
-    idx = txt.find("(")
-    if idx >= 0:
-        return txt[:idx].strip()
-    return txt.strip()
-
-
-# find differences between two str lists
-# line where error found, and a list of *s assocaited with
-# broken lines.
-
-SAME_MARKER = " | "
-DIFF_MARKER = " * "
-
-
-def strip_lines_comments(block):
-    for line in block:
-        yield strip_comments(line)
-
-
-# find differences in stuff which isn't commented.
-# return a set of lines with diffs.
-def find_differences(
-    golden_data: typing.Sequence[str],
-    callow_data: typing.Sequence[str],
-    check_comments: bool,
-):
-    lhs_src = golden_data
-    rhs_src = callow_data
-    if not check_comments:
-        lhs_src = strip_lines_comments(lhs_src)
-        rhs_src = strip_lines_comments(rhs_src)
-
-    diffs = set()
-    # skip same stuff
-    for line, (want, got) in enumerate(
-        itertools.zip_longest(lhs_src, rhs_src, fillvalue="")
-    ):
-        if want != got:
-            diffs.add(line)
-    return diffs
-
-
-@lib.g2l
-def format_differences(marks, golden_data: list[str], callow_data: list[str]):
-    fromto = slice(max(min(marks) - 4, 0), min(marks) + 10)
-
-    lhs_width = max(len(x) for x in golden_data[fromto])
-
-    def fmt(lhs, middle, rhs):
-        return lhs.ljust(lhs_width) + middle + rhs
-
-    yield fmt("want", "", "got")
-
-    for idx, (lhs, rhs) in enumerate(
-        itertools.zip_longest(
-            golden_data[fromto],
-            callow_data[fromto],
-            fillvalue=" - ",
-        )
-    ):
-        yield fmt(
-            lhs,
-            DIFF_MARKER if idx + fromto.start in marks else SAME_MARKER,
-            rhs,
-        )
-
-
-@lib.g2l
-def read_and_trim(path):
-    lines = lib.splitnl(path.read_text())
-    for line in lines:
-        yield line
-
-
-def writelines(path, txt):
-    return path.write_text(lib.nljoin(txt))
-
-
-# when a test fails, create source which would
-# have passed.
-
-
-def make_decorated_source_seed(fn, callow_path, callow_data):
-    tofix = ["@p2g.must_be("]
-    for line in callow_data:
-        quotechar = '"'
-        if quotechar in line:
-            quotechar = "'"
-        if line:
-            tofix.append(quotechar + line + quotechar + ",")
-    tofix.append(")\n")
-
-    lines = lib.splitnl(inspect.getsource(fn))
-
-    while lines and not lines[0].startswith("def"):
-        lines = lines[1:]
-
-    writelines(callow_path, tofix + lines)
-
-
-# compile fn, return generated errors or text.
-@lib.g2l
-def get_all_comp_outputs(fn):
-    try:
-        outlines = walk.compile2g(
-            fn.__name__,
-            inspect.getsourcefile(fn),
-            job_name=None,
-            in_pytest=True,
-        )
-    except err.CompilerError as exn:
-        outlines = exn.error_lines(absolute_lines=False, topfn=fn)
-    return outlines
-
-
-# when called from test, exceptions are sent to output file
-# as well as being passed up.
-
-
-# compile code and compare output with file.
-
-
-def check_must_be_worker(fn, gold_data, check_comments=False):
-    callow = get_all_comp_outputs(fn)
-
-    markers = find_differences(gold_data, callow, check_comments)
-
-    if not markers:
-        return
-    etext = format_differences(markers, gold_data, callow)
-
-    make_decorated_source_seed(fn, make_file_path(fn, ".decorator"), callow)
-
-    if "FORCE" in gold_data[0]:
-        return
-
-    # if running in pytest then exist out gracefully for them.
-    # otherwise, running in debug harness.
-    if gbl.config.debug:  # for debug
-        err.compiler(f"ptest error {lib.nljoin(etext)}")
-
-    pytest.fail(lib.nljoin(etext))  # for debug
-
-
-def check_golden_worker(fn, check_comments):
-    callow = get_all_comp_outputs(fn)
-
-    gold_path = make_file_path(fn, ".nc")
-    if gold_path.exists():
-        gold_data = read_and_trim(gold_path)
-
-        markers = find_differences(gold_data, callow, check_comments)
-        if not markers:
-            return
-        etext = format_differences(markers, gold_data, callow)
-        writelines(make_file_path(fn, ".got"), callow)
-
-        # if running in pytest then exist out gracefully for them.
-        # otherwise, running in debug harness.
-        if gbl.config.debug:
-            err.compiler(f"ptest error {lib.nljoin(etext)}")  # for debug
-
-        pytest.fail(lib.nljoin(etext))
-
-    else:
-        # no source gold, make it.
-        writelines(gold_path, callow)
-
-
-# decorator for tests, turns the node into ast and calls
-# the output comparer, uses relative linenumbers in reports
-# so things can be added without breaking exisiting
-
-
-def check_golden(check_comments=False):
-    def check_golden_(fn):
-        @functools.wraps(fn)
-        def check_golden__():
-            check_golden_worker(fn, check_comments)
-
-        return check_golden__
-
-    return check_golden_
-
-
-def check_golden_nodec(fn):
-    @functools.wraps(fn)
-    def check_golden__():
-        check_golden_worker(fn, False)
-
-    return check_golden__
-
-
-def must_be(*text):
-    def must_be_(fn):
-        @functools.wraps(fn)
-        def must_be__():
-            check_must_be_worker(fn, text)
-
-        return must_be__
-
-    return must_be_
-
-
-def must_be_cc(*text):
-    def must_be_(fn):
-        @functools.wraps(fn)
-        def must_be__():
-            check_must_be_worker(fn, text, check_comments=True)
-
-        return must_be__
-
-    return must_be_
+import functools
+import inspect
+import itertools
+import pathlib
+import typing
+
+from p2g import err
+from p2g import gbl
+from p2g import lib
+from p2g import walk
+
+
+# takes fn, works out where it lives, where to find golden output and
+# where to put test output
+# test_foo.py (test_zap) will make a tests/golden/test_foo_test_zap.nc file.
+
+
+def make_file_path(func, new_suffix) -> pathlib.Path:
+    # this_file_path <- <somewhere>/ptest.py
+    this_file_path = pathlib.Path(__file__)
+    # this_file_directory <- <somewhere>/p2g
+    this_file_directory = this_file_path.parent
+
+    # file_part <- function's filename
+    file_part = str(pathlib.Path(func.__code__.co_filename).stem)
+    #    file_part = file_part.replace("test_", "")
+
+    # can be in <srcdir>/tests or ../tests depending upon
+    # if run installed or not. Look for testdir.
+
+    for tests_dir in [
+        this_file_directory / "tests",
+        this_file_directory.parent / "tests",
+    ]:
+        if (tests_dir / "golden").exists():
+            break
+    else:  # pragma: no cover
+        breakpoint()
+
+        err.compiler("can't find tests")
+
+    # generated_dir <- <somewhere>/tests/golden
+    generated_dir = tests_dir / "golden"
+    generated_dir.mkdir(exist_ok=True)
+    #  <somewhere>/tests/golden/foo_zap.nc
+
+    #    new_filename = func.__name__.replace("test", file_part)
+    new_filename = file_part + "_" + func.__name__
+    return (generated_dir / new_filename).with_suffix(new_suffix)
+
+
+def strip_comments(txt):
+    txt = txt.replace(" ", "")
+    idx = txt.find("(")
+    if idx >= 0:
+        return txt[:idx].strip()
+    return txt.strip()
+
+
+# find differences between two str lists
+# line where error found, and a list of *s assocaited with
+# broken lines.
+
+SAME_MARKER = " | "
+DIFF_MARKER = " * "
+
+
+def strip_lines_comments(block):
+    for line in block:
+        yield strip_comments(line)
+
+
+# find differences in stuff which isn't commented.
+# return a set of lines with diffs.
+def find_differences(
+    golden_data: typing.Sequence[str],
+    callow_data: typing.Sequence[str],
+    check_comments: bool,
+):
+    lhs_src = golden_data
+    rhs_src = callow_data
+    if not check_comments:
+        lhs_src = strip_lines_comments(lhs_src)
+        rhs_src = strip_lines_comments(rhs_src)
+
+    diffs = set()
+    # skip same stuff
+    for line, (want, got) in enumerate(
+        itertools.zip_longest(lhs_src, rhs_src, fillvalue="")
+    ):
+        if want != got:
+            diffs.add(line)
+    return diffs
+
+
+@gbl.g2l
+def format_differences(marks, golden_data: list[str], callow_data: list[str]):
+    fromto = slice(max(min(marks) - 4, 0), min(marks) + 10)
+
+    lhs_width = max(len(x) for x in golden_data[fromto])
+
+    def fmt(lhs, middle, rhs):
+        return lhs.ljust(lhs_width) + middle + rhs
+
+    yield fmt("want", "", "got")
+
+    for idx, (lhs, rhs) in enumerate(
+        itertools.zip_longest(
+            golden_data[fromto],
+            callow_data[fromto],
+            fillvalue=" - ",
+        )
+    ):
+        yield fmt(
+            lhs,
+            DIFF_MARKER if idx + fromto.start in marks else SAME_MARKER,
+            rhs,
+        )
+
+
+def writelines(fn, suffix, txt, comment):
+    path = make_file_path(fn, suffix)
+    print(f"WRRTIGIN {comment} to ", path)
+    gbl.log(f"Ptest error, writing to {comment}")
+    return path.write_text(lib.nljoin(txt))
+
+
+# when a test fails, create source which would
+# have passed.
+
+
+def make_decorated_source_seed(fn, callow_data):
+    tofix = ["@must_be("]
+    for line in callow_data:
+        quotechar = '"'
+        if quotechar in line:
+            quotechar = "'"
+        if line:
+            tofix.append(quotechar + line + quotechar + ",")
+    tofix.append(")\n")
+
+    lines = gbl.splitnl(inspect.getsource(fn))
+
+    while lines and not lines[0].startswith("def"):
+        lines = lines[1:]
+
+    writelines(fn, ".decorator", tofix + lines, "creating decorator")
+
+
+# compile fn, return generated errors or text.
+@gbl.g2l
+def get_all_comp_outputs(fn):
+    try:
+        outlines = walk.compile2g(fn.__name__, inspect.getsourcefile(fn), job_name=None)
+    except err.CompilerError as exn:
+        outlines = exn.error_lines(absolute_lines=False, topfn=fn)
+
+    return outlines
+
+
+@gbl.g2l
+def read_and_trim(path):
+    lines = gbl.splitnl(path.read_text())
+    for line in lines:
+        yield line
+
+
+# when called from test, exceptions are sent to output file
+# as well as being passed up.
+
+
+# compile code and compare output with file.
+
+
+def check_must_be_worker(fn, gold_data, check_comments=False):
+    callow_data = list(get_all_comp_outputs(fn))
+
+    markers = find_differences(gold_data, callow_data, check_comments)
+
+    if not markers:
+        return
+    etext = format_differences(markers, gold_data, callow_data)
+
+    make_decorated_source_seed(fn, callow_data)
+
+    if "FORCE" in gold_data[0]:
+        return
+
+    # if running in pytest then exist out gracefully for them.
+    # otherwise, running in debug harness.
+    if gbl.config.debug:  # for debug
+        err.compiler(f"ptest error {lib.nljoin(etext)}")
+
+    assert False, lib.nljoin(etext)  # for debug
+
+
+def check_golden_worker(fn, check_comments):
+    callow = list(get_all_comp_outputs(fn))
+
+    gold_path = make_file_path(fn, ".nc")
+    if gold_path.exists():
+        gold_data = list(read_and_trim(gold_path))
+
+        markers = find_differences(gold_data, callow, check_comments)
+        if not markers:
+            return
+        etext = format_differences(markers, gold_data, callow)
+
+        writelines(fn, ".got", callow, "compare fail so")
+
+        # if running in pytest then exist out gracefully for them.
+        # otherwise, running in debug harness.
+        if gbl.config.debug:  # for debug
+            for line in etext:
+                print(line)
+            err.compiler(f"ptest error {lib.nljoin(etext)}")
+
+        assert False, lib.nljoin(etext)
+
+    else:
+        # no source gold, make it.
+        writelines(fn, ".nc", callow, "no source gold, create")
+
+
+# decorator for tests, turns the node into ast and calls
+# the output comparer, uses relative linenumbers in reports
+# so things can be added without breaking exisiting
+
+
+def check_golden(check_comments=False):
+    def check_golden_(fn):
+        @functools.wraps(fn)
+        def check_golden__():
+            check_golden_worker(fn, check_comments)
+
+        return check_golden__
+
+    return check_golden_
+
+
+def check_golden_nodec(fn):
+    @functools.wraps(fn)
+    def check_golden__():
+        check_golden_worker(fn, False)
+
+    return check_golden__
+
+
+def must_be(*text):
+    def must_be_(fn):
+        @functools.wraps(fn)
+        def must_be__():
+            check_must_be_worker(fn, text)
+
+        return must_be__
+
+    return must_be_
+
+
+def must_be_cc(*text):
+    def must_be_(fn):
+        @functools.wraps(fn)
+        def must_be__():
+            check_must_be_worker(fn, text, check_comments=True)
+
+        return must_be__
+
+    return must_be_
+
+
+def init_for_pytest():
+    gbl.config = gbl.config._replace(
+        narrow_output=True,
+    )
```

### Comparing `p2g-0.1.95/p2g/scalar.py` & `p2g-0.2.29/p2g/scalar.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,147 +1,145 @@
-import typing
-
-from p2g import nd
-from p2g import opinfo
-
-
-Ctype = typing.Union[float, int, str]
-
-
-class Scalar(nd.EBase):
-    opfo: opinfo.Opinfo
-    is_none_constant = False
-    is_constant = False
-    is_string_constant = False
-    is_numeric_constant = False
-    is_scalar = True
-
-    def __init__(self, opfo):
-        self.opfo = opfo
-
-    @property
-    def prec(self):
-        return self.opfo.prec
-
-    def get_address(self):
-        return None
-
-    def forever(self):
-        while True:
-            yield self
-
-    def to_float(self):
-        return None
-
-    def everything(self):
-        yield self
-
-    def to_int(self):
-        raise NotImplementedError()
-
-    # placeholder to east typechecking,
-    # overwitten by op install machines.
-    def __add__(self, _other):
-        pass
-
-    def __lt__(self, _other):
-        pass
-
-
-class ConstantBase(Scalar):
-    is_constant = True
-
-
-class Constant(ConstantBase):
-    _value: int | float
-    is_numeric_constant = True
-
-    def __init__(self, value: int | float):
-        super().__init__(opinfo.const_opinfo)
-        self._value = value
-
-    @property
-    def value(self):
-        return self._value
-
-    def same(self, other: "Constant"):
-        return isinstance(other, Constant) and other.value == self._value
-
-    def to_int(self) -> int:
-        return int(self._value)
-
-    def to_float(self):
-        return float(self._value)
-
-    def to_gcode(self, modifier=nd.NodeModifier.EMPTY) -> str:
-        if modifier & nd.NodeModifier.ADDRESS:
-            return str(int(self._value))
-        return nd.to_gcode_from_float(self._value)
-
-    def __bool__(self):
-        if self._value:
-            return True
-
-        return False
-
-    def __int__(self) -> int:
-        return int(self._value)
-
-    def __repr__(self):
-        return f"<{self._value}>"
-
-    def __str__(self):
-        return str(self._value)
-
-
-class ConstantNone(ConstantBase):
-    is_none_constant = True
-
-    def __init__(self):
-        super().__init__(opinfo.const_opinfo)
-
-
-class ConstantStr(ConstantBase):
-    value: str
-    is_string_constant = True
-
-    def __init__(self, value: str):
-        super().__init__(opinfo.const_opinfo)
-        self.value = value
-
-    def to_gcode(self, modifier=nd.NodeModifier.EMPTY) -> str:
-        # as an integer literal or as a string.
-
-        if modifier & nd.NodeModifier.ARGUMENT:
-            return f"{ord(self.value)}."
-        return f"'{self.value}'"
-
-
-def wrap_optional_scalar(thing) -> typing.Optional[Scalar]:
-    if isinstance(thing, str):
-        return ConstantStr(thing)
-
-    if isinstance(thing, (int, float, bool)):
-        return Constant(thing)
-    if isinstance(thing, Scalar):
-        return thing
-    return None
-
-
-def wrap_scalar(thing) -> Scalar:
-    if thing is None:
-        return ConstantNone()
-    res = wrap_optional_scalar(thing)
-    if res is not None:
-        return res
-
-    return thing.to_scalar()
-
-
-# make a range between wrapped items and yield ints
-def urange(start, stop, step=1):
-    stop = int(stop)
-    step = int(step)
-
-    tmp = list(range(int(start), stop, step))
-    for el in tmp:
-        yield el
+import typing
+
+from p2g import nd
+
+
+Ctype = typing.Union[float, int, str]
+
+
+class Scalar(nd.EBase):
+    opfo: nd.Opinfo
+    is_none_constant = False
+    is_constant = False
+    is_string_constant = False
+    is_numeric_constant = False
+    is_scalar = True
+
+    def __init__(self, opfo):
+        self.opfo = opfo
+
+    @property
+    def prec(self):
+        return self.opfo.prec
+
+    def get_address(self):
+        return None
+
+    def forever(self):
+        while True:
+            yield self
+
+    def to_float(self):
+        return None
+
+    def everything(self):
+        yield self
+
+    # placeholder to east typechecking,
+    # overwitten by op install machines.
+
+    def __add__(self, _other):  # no cover
+        pass
+
+    def __lt__(self, _other):  # no cover
+        pass
+
+    def __int__(self) -> int:
+        raise TypeError
+
+
+class ConstantBase(Scalar):
+    is_constant = True
+
+
+class Constant(ConstantBase):
+    _value: int | float
+    is_numeric_constant = True
+
+    def __init__(self, value: int | float):
+        super().__init__(nd.const_nd)
+        self._value = value
+
+    @property
+    def value(self):
+        return self._value
+
+    def same(self, other: "Constant"):
+        return isinstance(other, Constant) and other.value == self._value
+
+    def to_int(self) -> int:
+        return int(self)
+
+    def to_float(self):
+        return float(self._value)
+
+    def to_gcode(self, modifier=nd.NodeModifier.EMPTY) -> str:
+        return nd.to_gcode_from_float(self._value, modifier)
+
+    def __bool__(self):
+        if self._value:
+            return True
+
+        return False
+
+    def __int__(self) -> int:
+        return int(self._value)
+
+    def __repr__(self):
+        return f"<{self._value}>"
+
+    def __str__(self):
+        return str(self._value)
+
+
+class ConstantNone(ConstantBase):
+    is_none_constant = True
+
+    def __init__(self):
+        super().__init__(nd.const_nd)
+
+
+class ConstantStr(ConstantBase):
+    value: str
+    is_string_constant = True
+
+    def __init__(self, value: str):
+        super().__init__(nd.const_nd)
+        self.value = value
+
+    def to_gcode(self, modifier=nd.NodeModifier.EMPTY) -> str:
+        # as an integer literal or as a string.
+
+        if modifier & nd.NodeModifier.ARGUMENT:
+            return f"{ord(self.value)}."
+        return f"'{self.value}'"
+
+
+def wrap_optional_scalar(thing) -> typing.Optional[Scalar]:
+    if isinstance(thing, str):
+        return ConstantStr(thing)
+
+    if isinstance(thing, (int, float, bool)):
+        return Constant(thing)
+    if isinstance(thing, Scalar):
+        return thing
+    return None
+
+
+def wrap_scalar(thing) -> Scalar:
+    if thing is None:
+        return ConstantNone()
+    res = wrap_optional_scalar(thing)
+    if res is not None:
+        return res
+
+    return thing.to_scalar()
+
+
+# make a range between wrapped items and yield ints
+def urange(start, stop, step=1):
+    stop = int(stop)
+    step = int(step)
+
+    tmp = list(range(int(start), stop, step))
+    for el in tmp:
+        yield el
```

### Comparing `p2g-0.1.95/p2g/stat.py` & `p2g-0.2.29/p2g/stat.py`

 * *Files 23% similar despite different names*

```diff
@@ -1,312 +1,325 @@
-import abc
-import dataclasses
-import itertools
-import typing
-
-from loguru import logger
-
-from p2g import err
-from p2g import gbl
-from p2g import lib
-from p2g import nd
-
-
-COMMENT_INDENT = 34
-
-
-# infront of code which isn't a label
-NORMAL_PREFIX = "  "
-
-
-@dataclasses.dataclass
-class Label:
-    idx: int
-    used: bool
-
-    def __init__(self, idx: int):
-        self.idx = idx
-        self.used = False
-
-    def as_gcode_ref(self):
-        return f"{self.idx}"
-
-    def as_gcode_definition(self):
-        return f"L{self.idx}"
-
-
-# auto comment is a comment which comes from
-# the source, rather than being typed.
-# we take liberties to increase information density.
-
-
-# remove bad chars from a comment.
-def clean_comment_chars(txt: str):
-    res = ""
-    for ch in txt:
-        match ch:
-            case "(":
-                ch = "["
-            case ")":
-                ch = "]"
-
-        res += ch
-    return res
-
-
-def compress_and_clean(line: str):
-    guts = clean_comment_chars(line)
-    for too_talky in ["p2g.", "goto", "var."]:
-        guts = guts.replace(too_talky, "")
-
-    if guts.startswith("    "):
-        guts = guts[4:]
-
-    return "( " + guts.ljust(30) + ")"
-
-
-@dataclasses.dataclass
-class StatBase(abc.ABC):
-    _comtxt: str
-
-    def __init__(self, comtxt=""):
-        self.pos = err.state.last_pos
-        self._comtxt = comtxt
-
-    def to_line_lhs(self) -> list[str]:
-        raise AssertionError
-
-    @lib.g2l
-    def to_full_lines(self, blockstate):
-        comtxt = self._comtxt
-        if not comtxt:
-            comtxt = err.src_code_from_node_place(self.pos)
-        comtxt = compress_and_clean(comtxt)
-        if comtxt == blockstate.prev_comtxt:
-            comtxt = ""
-        else:
-            blockstate.prev_comtxt = comtxt
-
-        for code_txt, com_txt in itertools.zip_longest(
-            self.to_line_lhs(),
-            [comtxt],
-            fillvalue="",
-        ):
-            # If code would leak into comment, put out the comment on
-            # own line.  If in narrow mode (by option,  or default if
-            # in pytest or debug), put on own line too.
-
-            if gbl.config.narrow_output:
-                comment_indent = 0
-            else:
-                comment_indent = COMMENT_INDENT
-
-            code_comment_gap = comment_indent - len(code_txt)
-            if code_comment_gap < 0:
-                first_line = com_txt
-                second_line = code_txt
-            else:
-                if com_txt:
-                    first_line = code_txt + " " * code_comment_gap + com_txt
-                else:
-                    first_line = code_txt
-                second_line = ""
-            if first_line:
-                yield first_line
-            if second_line:
-                yield second_line
-
-
-@dataclasses.dataclass
-class Nest:
-    first_label: int
-    next_label: int
-
-    prev: "Nest"
-    slist: list[StatBase]
-    cur: "Nest" = typing.cast("Nest", None)
-
-    def __init__(self, in_pytest=False):
-        self.prev = Nest.cur
-        if not in_pytest and Nest.cur:
-            self.first_label = self.prev.first_label + 1000
-        else:
-            self.first_label = 1000
-        Nest.cur = self
-        self.next_label = self.first_label
-        self.slist = []
-
-    def get_label(self):
-        res = self.next_label
-        self.next_label += 1
-        return Label(res)
-
-    @classmethod
-    def add_stat(cls, stat):
-        Nest.cur.slist.append(stat)
-
-    @lib.g2l
-    def to_full_lines(self):
-        class BS:
-            prev_comtxt = ""
-
-        blockstate = BS()
-        for line in self.slist:
-            yield from line.to_full_lines(blockstate)
-
-    def __enter__(self):
-        return self
-
-    def __exit__(self, *_exn):
-        Nest.cur = self.prev
-
-
-class CommentLines(StatBase):
-    def __init__(self, lines):
-        super().__init__()
-        self.lines = lines
-
-    def to_full_lines(self, _):
-        lines = list(map(str, self.lines))
-        lines = lib.pad_to_same_width(lines)
-
-        for line in lines:
-            if line:
-                yield "( " + clean_comment_chars(line) + " )"
-
-
-def add_stat(stat):
-    logger.info(f"Adding {stat}")
-    Nest.add_stat(stat)
-
-
-def comment(*lines):
-    add_stat(CommentLines(lines))
-
-
-def com(*lines):
-    comment(*lines)
-
-
-@dataclasses.dataclass
-class Goto(StatBase):
-    target: Label
-
-    def __init__(self, target: Label):
-        super().__init__()
-        self.target = target
-
-    def to_line_lhs(self):
-        yield f"  GOTO {self.target.as_gcode_ref()}"
-
-
-@dataclasses.dataclass
-class If(StatBase):
-    exp: typing.Any
-    on_t: Label
-
-    def __init__(self, exp, on_t: Label):
-        super().__init__()
-
-        self.exp = exp
-        self.on_t = on_t
-
-    def to_line_lhs(self):
-        lhs = f"IF [{nd.to_gcode(self.exp)}] "
-        rhs = f"GOTO {self.on_t.as_gcode_ref()}"
-        yield NORMAL_PREFIX + lhs + rhs
-
-
-@dataclasses.dataclass
-class Code(StatBase):
-    txt: str
-
-    def __init__(self, txt, ctxt):
-        super().__init__(ctxt)
-        self.txt = txt
-
-    def to_line_lhs(self):
-        yield NORMAL_PREFIX + self.txt
-
-
-@dataclasses.dataclass
-class Dprint(StatBase):
-    txt: str
-
-    def __init__(self, txt):
-        super().__init__()
-        self.txt = txt
-
-    def to_line_lhs(self):
-        yield "DPRNT[" + self.txt + "]"
-
-
-@dataclasses.dataclass
-class ByLambda(StatBase):
-    def __init__(self, fn):
-        super().__init__()
-        self.fn = fn
-
-    def to_full_lines(self, _):
-        return self.fn()
-
-    @classmethod
-    def emit(cls, fn):
-        add_stat(ByLambda(fn))
-
-
-class Set(StatBase):
-    lhs: nd.EBase
-    rhs: nd.EBase
-
-    def __init__(self, lhs: nd.EBase, rhs: nd.EBase, comtxt: str = ""):
-        super().__init__(comtxt)
-        assert isinstance(lhs, nd.EBase)
-        self.lhs = lhs
-        self.rhs = rhs
-
-    @lib.g2l
-    def to_line_lhs(self):
-        lhs = self.lhs.to_gcode(nd.NodeModifier.EMPTY)
-        rhs = self.rhs.to_gcode(nd.NodeModifier.ARGUMENT)
-        yield f"{NORMAL_PREFIX}{lhs}= {rhs}"
-
-
-def append_set(dst, src, comtxt=""):
-    if not lib.same(dst, src):
-        add_stat(Set(dst, src, comtxt))
-
-
-def code(txt, comtxt: str = ""):
-    if isinstance(txt, str):
-        add_stat(Code(txt, comtxt))
-        return
-
-    for line in txt:
-        code(str(line), comtxt)
-        comtxt = ""
-
-
-@dataclasses.dataclass
-class LabelDef(StatBase):
-    labeldef: Label
-
-    def __init__(self, labeldef: Label):
-        self.labeldef = labeldef
-        super().__init__()
-
-    def to_line_lhs(self):
-        yield f"{self.labeldef.as_gcode_definition()}"
-
-
-def next_label():
-    return Nest.cur.get_label()
-
-
-def dprint(fstr):
-    fstr = fstr.replace(" ", "*")
-    add_stat(Dprint(fstr))
-
-
-# when run from tests, sometimes we get generated
-# statements by surprise.
-top = Nest()
+import abc
+import dataclasses
+import itertools
+import typing
+
+from p2g import err
+from p2g import gbl
+from p2g import lib
+from p2g import nd
+
+
+COMMENT_INDENT = 34
+
+
+# infront of code which isn't a label
+NORMAL_PREFIX = "  "
+
+
+@dataclasses.dataclass
+class Label:
+    idx: int
+    used: bool
+
+    def __init__(self, idx: int):
+        self.idx = idx
+        self.used = False
+
+    def as_gcode_ref(self):
+        return f"{self.idx}"
+
+    def as_gcode_definition(self):
+        return f"N{self.idx}"
+
+
+# auto comment is a comment which comes from
+# the source, rather than being typed.
+# we take liberties to increase information density.
+
+
+# remove bad chars from a comment.
+def clean_comment_chars(txt: str):
+    res = ""
+    for ch in txt:
+        match ch:
+            case "(":
+                ch = "["
+            case ")":
+                ch = "]"
+
+        res += ch
+    return res
+
+
+def compress_and_clean(line: str):
+    guts = clean_comment_chars(line)
+    for too_talky in ["p2g.", "var."]:
+        guts = guts.replace(too_talky, "")
+
+    if guts.startswith("    "):
+        guts = guts[4:]
+
+    return "( " + guts.ljust(30) + ")"
+
+
+@dataclasses.dataclass
+class StatBase(abc.ABC):
+    _comment: str
+
+    def __init__(self, comment_txt=None):
+        self.pos = err.state.last_pos
+
+        # if specifically asked for none, then we're done.
+        if comment_txt == "<none>":
+            self._comment = ""
+        else:
+            # no comment supplied, then use source line.
+            if not comment_txt:
+                comment_txt = err.src_code_from_node_place(self.pos)
+            comment_txt = compress_and_clean(comment_txt)
+            self._comment = comment_txt
+
+    def to_line_lhs(self) -> list[str]:
+        raise AssertionError
+
+    @gbl.g2l
+    def to_full_lines(self, blockstate):
+        comtxt = self._comment
+        if comtxt == blockstate.prev_comtxt:
+            comtxt = ""
+        else:
+            blockstate.prev_comtxt = comtxt
+
+        for code_txt, com_txt in itertools.zip_longest(
+            self.to_line_lhs(),
+            [comtxt],
+            fillvalue="",
+        ):
+            # If code would leak into comment, put out the comment on
+            # own line.  If in narrow mode (by option,  or default if
+            # in pytest or debug), put on own line too.
+
+            if gbl.config.narrow_output:
+                comment_indent = 0
+            else:
+                comment_indent = COMMENT_INDENT
+
+            code_comment_gap = comment_indent - len(code_txt)
+            if code_comment_gap < 0:
+                first_line = com_txt
+                second_line = code_txt
+            else:
+                if com_txt:
+                    first_line = code_txt + " " * code_comment_gap + com_txt
+                else:
+                    first_line = code_txt
+                second_line = ""
+            if first_line:
+                yield first_line
+            if second_line:
+                yield second_line
+
+
+@dataclasses.dataclass
+class Nest:
+    first_label: int
+    next_label: int
+
+    prev: "Nest"
+    slist: list[StatBase]
+    cur: "Nest" = typing.cast("Nest", None)
+
+    def __init__(self):
+        self.prev = Nest.cur
+        if gbl.config.tin_test or not Nest.cur:
+            self.first_label = 1000
+        else:
+            self.first_label = self.prev.first_label + 1000
+
+        Nest.cur = self
+        self.next_label = self.first_label
+        self.slist = []
+
+    def get_label(self):
+        res = self.next_label
+        self.next_label += 1
+        return Label(res)
+
+    @classmethod
+    def add_stat(cls, stat):
+        Nest.cur.slist.append(stat)
+
+    @gbl.g2l
+    def to_full_lines(self):
+        class BS:
+            prev_comtxt = ""
+
+        blockstate = BS()
+        for line in self.slist:
+            yield from line.to_full_lines(blockstate)
+
+    def __enter__(self):
+        return self
+
+    def __exit__(self, *_exn):
+        Nest.cur = self.prev
+
+
+class CommentLines(StatBase):
+    def __init__(self, lines):
+        super().__init__()
+        self.lines = lines
+
+    def to_full_lines(self, _):
+        lines = list(map(str, self.lines))
+
+        def max_str_len(lines):
+            return len(max(lines, key=len, default=""))
+
+        def pad_to_same_width(lines):
+            wid = max_str_len(lines)
+            res = []
+            for line in lines:
+                res.append(line.ljust(wid))
+            return res
+
+        lines = pad_to_same_width(lines)
+
+        for line in lines:
+            if line.strip():
+                yield "( " + clean_comment_chars(line) + " )"
+            else:
+                yield ""
+
+
+def add_stat(stat):
+    gbl.log(f"Adding {stat}")
+    Nest.add_stat(stat)
+
+
+def comment(*lines):
+    add_stat(CommentLines(" "))
+    add_stat(CommentLines(lines))
+
+
+def com(*lines):
+    add_stat(CommentLines(lines))
+
+
+@dataclasses.dataclass
+class Goto(StatBase):
+    target: Label
+
+    def __init__(self, target: Label):
+        super().__init__()
+        self.target = target
+
+    def to_line_lhs(self):
+        yield f"  GOTO {self.target.as_gcode_ref()}"
+
+
+@dataclasses.dataclass
+class If(StatBase):
+    exp: typing.Any
+    on_t: Label
+
+    def __init__(self, exp, on_t: Label):
+        super().__init__()
+
+        self.exp = exp
+        self.on_t = on_t
+
+    def to_line_lhs(self):
+        lhs = f"IF [{nd.to_gcode(self.exp)}] "
+        rhs = f"GOTO {self.on_t.as_gcode_ref()}"
+        yield NORMAL_PREFIX + lhs + rhs
+
+
+@dataclasses.dataclass
+class Code(StatBase):
+    txt: str
+
+    def __init__(self, txtargs, comment_txt=""):
+        super().__init__(comment_txt=comment_txt)
+
+        self.txt = lib.unwind(txtargs)
+
+    def to_line_lhs(self):
+        yield NORMAL_PREFIX + self.txt
+
+
+@dataclasses.dataclass
+class Dprint(StatBase):
+    txt: str
+
+    def __init__(self, txt):
+        super().__init__("<none>")
+        self.txt = txt
+
+    def to_line_lhs(self):
+        yield "DPRNT[" + self.txt + "]"
+
+
+class Set(StatBase):
+    lhs: nd.EBase
+    rhs: nd.EBase
+
+    def __init__(self, lhs: nd.EBase, rhs: nd.EBase, comtxt: str = ""):
+        super().__init__(comtxt)
+        assert isinstance(lhs, nd.EBase)
+        self.lhs = lhs
+        self.rhs = rhs
+
+    @gbl.g2l
+    def to_line_lhs(self):
+        lhs = self.lhs.to_gcode(nd.NodeModifier.EMPTY)
+        rhs = self.rhs.to_gcode(nd.NodeModifier.ARGUMENT)
+        yield f"{NORMAL_PREFIX}{lhs}= {rhs}"
+
+
+def append_set(dst, src, comtxt=""):
+    if not lib.same(dst, src):
+        add_stat(Set(dst, src, comtxt))
+
+
+def code(*txtargs, comment_txt: str = ""):
+    add_stat(Code(txtargs, comment_txt=comment_txt))
+
+
+def codenl(txtlst, comtxt: str = ""):
+    if isinstance(txtlst, str):
+        add_stat(Code(txtlst, comtxt))
+    else:
+        for txt in txtlst:
+            codenl(txt, comtxt)
+            comtxt = ""
+
+
+# take list of args and chain them
+# and then join. Take care with strings.
+
+
+@dataclasses.dataclass
+class LabelDef(StatBase):
+    labeldef: Label
+
+    def __init__(self, labeldef: Label):
+        self.labeldef = labeldef
+        super().__init__()
+
+    def to_line_lhs(self):
+        yield f"{self.labeldef.as_gcode_definition()}"
+
+
+def next_label():
+    return Nest.cur.get_label()
+
+
+def dprint(fstr):
+    fstr = fstr.replace(" ", "*")
+    add_stat(Dprint(fstr))
+
+
+# when run from tests, sometimes we get generated
+# statements by surprise.
+top = Nest()
```

### Comparing `p2g-0.1.95/p2g/thanksto` & `p2g-0.2.29/p2g/thanksto`

 * *Files identical despite different names*

### Comparing `p2g-0.1.95/p2g/walkfunc.py` & `p2g-0.2.29/p2g/walkfunc.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,232 +1,237 @@
-import ast
-import dataclasses
-import itertools
-import typing
-
-from p2g import err
-from p2g import gbl
-from p2g import op
-from p2g import stat
-from p2g import walkbase
-from p2g import walkns
-
-
-class Marker:
-    pass
-
-
-# look through caller's args and insert defaults
-# etc. to be compatible with callee, return dict
-# with mapping.
-
-
-def formal_kwargs(formalspec, formals, kwargs, pos) -> dict[str, typing.Any]:
-    # Process incoming keyword arguments, putting them in namespace if
-    # actual arg exists by that name, or offload to function's kwarg
-    # if any. All make needed checks and error out.
-    func_kwarg = {}
-    final_dict = {}
-    all_formals = {
-        x.arg
-        for x in itertools.chain(formals.args, formals.kwonlyargs, formals.kw_defaults)
-        if x is not None
-    }
-
-    for key, value in kwargs.items():
-        if key in all_formals:
-            final_dict[key] = value
-        elif formalspec.kwarg:
-            func_kwarg[key] = value
-        else:
-            err.compiler("bad arguments.", err_pos=pos)
-
-    if formalspec.kwarg:
-        final_dict[formalspec.kwarg.arg] = func_kwarg
-    return final_dict
-
-
-def check_missing(final_dict, formalspec, pos):
-    # check for missing args
-    for formal in itertools.chain(formalspec.args, formalspec.kwonlyargs):
-        if formal.arg not in final_dict:
-            err.compiler(f"Missing argument {formal.arg}", err_pos=pos)
-
-
-def get_defaults(walker, formals):
-    first_defaulted = len(formals.args) - len(formals.defaults)
-    return {
-        # position args defaults
-        el.arg: walker.visit(formals.defaults[idx - first_defaulted])
-        for idx, el in enumerate(formals.args)
-        if idx >= first_defaulted
-    } | {
-        # kwargs defaults
-        el.arg: walker.visit(val)
-        for el, val in zip(formals.kwonlyargs, formals.kw_defaults)
-        if val is not None
-    }
-
-
-def gather_func_formals(func_def, *args, **kwargs):
-    walker = func_def.walker
-    formals = func_def.node.args
-
-    # report error in caller rather than definition.
-    pos = err.state.last_pos
-
-    final_dict = {}
-
-    formalspec = func_def.node.args
-
-    if formalspec.vararg:
-        final_dict[formalspec.vararg.arg] = args[len(formalspec.args) :]
-    else:
-        if len(args) > len(formalspec.args):
-            err.compiler("bad arguments", err_pos=pos)
-
-    for i in range(min(len(args), len(formalspec.args))):
-        final_dict[formalspec.args[i].arg] = args[i]
-
-    # result contains at least the defaults.
-    final_dict |= get_defaults(walker, formals)
-    final_dict |= formal_kwargs(formalspec, formals, kwargs, pos)
-
-    check_missing(final_dict, formalspec, pos)
-
-    err.state.last_pos = pos
-    return final_dict
-
-
-# calling a function, emit code to call, and
-# generate the called code.  And save it, to make
-# sure that other generations make the same.
-
-
-def inline(func_def, *args, **kwargs):
-    walker = func_def.walker
-    prev_file = walker.file_name
-    prev_func = walker.func_name
-
-    walker.file_name = func_def.file_name
-    walker.func_name = func_def.func_name
-
-    # We need to switch from dynamic execution scope to lexical scope
-    # in which function was defined (then switch back on return).
-    dyna_scope = walker.ns
-    walker.ns = func_def.lexical_scope
-    res = None
-    with walker.pushpopns(walkns.FunctionNS()):
-        formals_dict = gather_func_formals(func_def, *args, **kwargs)
-
-        walker.ns.guts.update(formals_dict)
-
-        res = walker.visit_slist(func_def.node.body)
-
-    walker.ns = dyna_scope
-    walker.func_name = prev_func
-    walker.file_name = prev_file
-    return res
-
-
-@dataclasses.dataclass
-class FuncDefWrap:
-    file_name: str
-    func_name: str
-
-    node: ast.AST
-    walker: "WalkFunc"
-    lexical_scope: walkns.ANamespace
-    call: bool
-
-    gen: list[stat.StatBase]
-
-    def __init__(self, walker, node):
-        self.call = False
-        self.gen = []
-        for decorator in node.decorator_list:
-            walker.visit(decorator)
-
-        self.file_name = walker.module_ns["__file__"]
-        self.func_name = node.name
-        self.node = node
-        self.walker = walker
-        self.lexical_scope = walker.ns
-
-    def __call__(self, *args, **kwargs):
-        return inline(self, *args, **kwargs)
-
-
-def interpfunc(fun):
-    def func(*args, **kwargs):
-        if args and isinstance(args[0], Marker):
-            return fun
-        return fun(*args, **kwargs)
-
-    return func
-
-
-@dataclasses.dataclass
-class FuncArgsDescr:
-    defndesc: typing.Any
-    args: list[typing.Any]
-    kwargs: dict[str, typing.Any]
-
-    def __init__(self, walker, node):
-        args = []
-        for arg in node.args:
-            if isinstance(arg, ast.Starred):
-                args.extend(walker.visit(arg.value))
-            else:
-                args.append(walker.visit(arg))
-
-        kwargs = {}
-        for keyword in node.keywords:
-            val = walker.visit(keyword.value)
-            if keyword.arg is None:
-                kwargs.update(val)
-            else:
-                kwargs[keyword.arg] = val
-        self.args = args
-        self.kwargs = kwargs
-
-
-class WalkFunc(walkbase.WalkBase):
-    def _visit_call(self, node):
-        defn = self.visit(node.func)
-        desc = FuncArgsDescr(self, node)
-        if defn.__module__ == "p2g.builtin":
-            return op.make_scalar_func(defn.__name__, *desc.args)
-
-        #        return desc.callit(*desc.args, **desc.kwargs)
-        # f = interpfunc(desc.func)
-        # return f
-
-        return defn(*desc.args, **desc.kwargs)
-
-    def _visit_functiondef(self, node):
-        desc = FuncDefWrap(self, node)
-        #        self.funcmaps[node.name] = desc
-        ifunc = interpfunc(desc)
-        self.ns[node.name] = ifunc
-
-
-def digest_top(walker, func_name, srcpath, job_name):
-    try:
-        fncdef = walker.ns[func_name]
-        desc = fncdef(Marker())
-    except KeyError:
-        err.compiler(f"No such function '{func_name}' in '{srcpath}'.")
-
-    if not gbl.config.in_pytest:
-        stat.add_stat(stat.Code(job_name, srcpath.stem.upper()))
-
-    if gbl.config.bp_on_error:  # no cover
-        inline(desc)
-    else:
-        try:
-            inline(desc)
-        except (AttributeError, IndexError) as exn:
-            err.compiler(exn)
-
-    if not gbl.config.in_pytest:
-        stat.add_stat(stat.Code("M30", None))
+import ast
+import dataclasses
+import itertools
+import typing
+
+from p2g import err
+from p2g import gbl
+from p2g import op
+from p2g import stat
+from p2g import walkbase
+
+
+class Marker:
+    pass
+
+
+# look through caller's args and insert defaults
+# etc. to be compatible with callee, return dict
+# with mapping.
+
+
+def formal_kwargs(formalspec, formals, kwargs, pos) -> dict[str, typing.Any]:
+    # Process incoming keyword arguments, putting them in namespace if
+    # actual arg exists by that name, or offload to function's kwarg
+    # if any. All make needed checks and error out.
+    func_kwarg = {}
+    final_dict = {}
+    all_formals = {
+        x.arg
+        for x in itertools.chain(formals.args, formals.kwonlyargs, formals.kw_defaults)
+        if x is not None
+    }
+
+    for key, value in kwargs.items():
+        if key in all_formals:
+            final_dict[key] = value
+        elif formalspec.kwarg:
+            func_kwarg[key] = value
+        else:
+            err.compiler("Bad arguments.", err_pos=pos)
+
+    if formalspec.kwarg:
+        final_dict[formalspec.kwarg.arg] = func_kwarg
+    return final_dict
+
+
+def check_missing(final_dict, formalspec, pos):
+    # check for missing args
+    for formal in itertools.chain(formalspec.args, formalspec.kwonlyargs):
+        if formal.arg not in final_dict:
+            err.compiler(f"Missing argument '{formal.arg}'.", err_pos=pos)
+
+
+def get_defaults(walker, formals):
+    first_defaulted = len(formals.args) - len(formals.defaults)
+    return {
+        # position args defaults
+        el.arg: walker.visit(formals.defaults[idx - first_defaulted])
+        for idx, el in enumerate(formals.args)
+        if idx >= first_defaulted
+    } | {
+        # kwargs defaults
+        el.arg: walker.visit(val)
+        for el, val in zip(formals.kwonlyargs, formals.kw_defaults)
+        if val is not None
+    }
+
+
+def gather_func_formals(func_def, *args, **kwargs):
+    walker = func_def.walker
+    formals = func_def.node.args
+
+    # report error in caller rather than definition.
+    pos = err.state.last_pos
+
+    final_dict = {}
+
+    formalspec = func_def.node.args
+
+    if formalspec.vararg:
+        final_dict[formalspec.vararg.arg] = args[len(formalspec.args) :]
+    else:
+        if len(args) > len(formalspec.args):
+            err.compiler("Bad arguments.", err_pos=pos)
+
+    for i in range(min(len(args), len(formalspec.args))):
+        final_dict[formalspec.args[i].arg] = args[i]
+
+    # result contains at least the defaults.
+    final_dict |= get_defaults(walker, formals)
+    final_dict |= formal_kwargs(formalspec, formals, kwargs, pos)
+
+    check_missing(final_dict, formalspec, pos)
+
+    err.state.last_pos = pos
+    return final_dict
+
+
+# calling a function, emit code to call, and
+# generate the called code.  And save it, to make
+# sure that other generations make the same.
+
+
+def inline(func_def, *args, **kwargs):
+    walker = func_def.walker
+    prev_file = walker.file_name
+    prev_func = walker.func_name
+
+    walker.file_name = func_def.file_name
+    walker.func_name = func_def.func_name
+
+    # We need to switch from dynamic execution scope to lexical scope
+    # in which function was defined (then switch back on return).
+    dyna_scope = walker.ns
+    walker.ns = func_def.lexical_scope
+    res = None
+
+    with walker.pushpopns(walkbase.FunctionNS()):
+        formals_dict = gather_func_formals(func_def, *args, **kwargs)
+
+        walker.ns.guts.update(formals_dict)
+
+        res = walker.visit_slist(func_def.node.body)
+
+    walker.ns = dyna_scope
+    walker.func_name = prev_func
+    walker.file_name = prev_file
+    return res
+
+
+@dataclasses.dataclass
+class FuncDefWrap:
+    file_name: str
+    func_name: str
+
+    node: ast.AST
+    walker: "WalkFunc"
+    lexical_scope: walkbase.ANamespace
+    call: bool
+
+    gen: list[stat.StatBase]
+
+    def __init__(self, walker, node):
+        self.call = False
+        self.gen = []
+        self.func_name = node.name
+
+        self.file_name = walker.module_ns["__file__"]
+
+        self.node = node
+        self.walker = walker
+        self.lexical_scope = walker.ns
+
+    def __call__(self, *args, **kwargs):
+        return inline(self, *args, **kwargs)
+
+
+def interpfunc(fun):
+    def func(*args, **kwargs):
+        if args and isinstance(args[0], Marker):
+            return fun
+        return fun(*args, **kwargs)
+
+    return func
+
+
+@dataclasses.dataclass
+class FuncArgsDescr:
+    args: list[typing.Any]
+    kwargs: dict[str, typing.Any]
+
+    def __init__(self, walker, node):
+        args = []
+        for arg in node.args:
+            if isinstance(arg, ast.Starred):
+                args.extend(walker.visit(arg.value))
+            else:
+                args.append(walker.visit(arg))
+
+        kwargs = {}
+        for keyword in node.keywords:
+            val = walker.visit(keyword.value)
+            if keyword.arg is None:
+                kwargs.update(val)
+            else:
+                kwargs[keyword.arg] = val
+        self.args = args
+        self.kwargs = kwargs
+
+
+def funcall(target, *args, **kwargs):
+    return target(*args, **kwargs)
+
+
+class WalkFunc(walkbase.WalkBase):
+    def _visit_call(self, node):
+        defn = self.visit(node.func)
+        desc = FuncArgsDescr(self, node)
+        if defn.__module__ == "p2g.builtin":
+            return op.make_scalar_func(defn.__name__, *desc.args)
+
+        #        return desc.callit(*desc.args, **desc.kwargs)
+        # f = interpfunc(desc.func)
+        # return f
+        return funcall(defn, *desc.args, **desc.kwargs)
+
+    def _visit_functiondef(self, node):
+        desc = FuncDefWrap(self, node)
+        #        self.funcmaps[node.name] = desc
+        ifunc = interpfunc(desc)
+        self.ns[node.name] = ifunc
+
+
+def digest_top(walker, func_name, srcpath, job_name, args):
+    if args is None:
+        args = []
+    try:
+        fncdef = walker.ns[func_name]
+        desc = fncdef(Marker())
+    except KeyError:
+        err.compiler(f"No such function '{func_name}' in '{srcpath}'.")
+
+    def insides():
+        if gbl.config.bp_on_error:  # no cover
+            inline(desc, *args)
+        else:
+            try:
+                inline(desc, *args)
+            except (AttributeError, IndexError) as exn:
+                err.compiler(exn)
+
+    if gbl.config.boiler_plate and job_name:
+        stat.code([job_name], comment_txt=func_name)
+        insides()
+        stat.add_stat(stat.Code("M30", "<none>"))
+    else:
+        insides()
```

### Comparing `p2g-0.1.95/pyproject.toml` & `p2g-0.2.29/pyproject.toml`

 * *Files 9% similar despite different names*

```diff
@@ -1,102 +1,97 @@
 [tool.poetry]
 
-
-
 name = "p2g"
-version = "0.1.95"
+version = "0.2.29"
 description = "Transpile python into cnc gcode."
 authors = ["sac <sac@0x5ac.com>"]
-readme = "README.rst"
+readme = "readme.md" 
 license = "MIT"
-keywords = ["cnc", "gcode", "mill", "haas"]
+keywords = ["cnc", "gcode", "mill", "haas", "g-code", "probe", "vf"]
 classifiers = [
 "Development Status :: 3 - Alpha",
 "Intended Audience :: Manufacturing",
 "Intended Audience :: Other Audience",
 "Topic :: Software Development :: Compilers",
 "Programming Language :: Python",
 ]
 repository = 'https://github.com/0x5ac/p2g'
 homepage = 'https://github.com/0x5ac/p2g'
 
 
 packages = [
-    { include = "p2g", format = "sdist"},
-
+    { include = "p2g",    format = "sdist"},
 ]
 
 
 [tool.poetry.dependencies]
-
 python = "^3.10"
-docopt = "^0.6.2"
-pytest =  "^7.3.1"
 typeguard = "^3.0.2"
 rich = "^13.3.4"
-loguru = "^0.7.0"
+docopt = "^0.6.2"
+
 [tool.poetry.scripts]
 p2g = "p2g.main:main"
 
 [tool.poetry.group.dev.dependencies]
 pytest = {extras = ["all"], version = "^7.3.1"}
 pytest-cov = "^4.0.0"
 coverage = "^7.2.3"
-
 mypy = "^1.2.0"
 pylint = "^2.17.2"
 pydeps = "^1.12.1"
 flake8-annotations-complexity = "^0.0.7"
 flake8-pyproject = {extras = ["all"], version = "^1.2.3"}
 black = "^23.3.0"
 ssort = "^0.11.6"
 tox = "^4.5.1"
 deptry = "^0.8.0"
 mccabe = "^0.7.0"
 wrapt = "^1.15.0"
 dill = "^0.3.6"
 autoflake = "^2.1.1"
+ruff = "^0.0.272"
+pyright = "^1.1.314"
+
+[tool.deptry]
+ignore_missing = [ "csearch" , "defs", "pytest" ]
+ignore_obsolete = [  "typeguard" ]
+extend_exclude = [ 'p2g/tests' ] 
 
 [tool.pyright]
 disable = "N802"
 ignore = ["N802"]
 include = ["p2g/*.py"]
+exclude= [ "p2g/tests" , "p2g/doc", "p2g/examples"]
+omit = ['p2g/tests/*.py']
 [tool.isort]
 force_alphabetical_sort_within_sections = true
 #force_single_line = true
 combine_as_imports = true
 lines_between_types = 1
 known_localfolder = "p2g"
 lines_after_imports = 2
 float_to_top = true
 force_single_line = true
-src_paths = ["p2g"]
-
+src_paths = ["p2g","tests"]
+skip = ["tests/test_meta.py"]
 
 
 [tool.black]
 line-length=90
 
-
-[tool.pylama]
-linters = "mccabe,mypy,pycodestyle,pydocstyle,isort"
-max_line_length = 100
-ignore = "W0611,E501,D212,C0116,W0611,D100,D104,D101,C0115,C0114,D103,D105,D107,D102,N802,E800,B601,G004,E203,D209,D205,D400,E402"
-ignore-errors="E203"
-exclude= [ "p2g/tests", "p2g/doc" ]
-[tool.mypy]
+[tool.mypy] 
 ignore_missing_imports = true
 check_untyped_defs = true
-exclude= [ "p2g/tests" , "p2g/doc"]
+exclude= [ "p2g/tests" , "p2g/doc", "p2g/examples"]
 
 [tool.pydocstyle]
 ignore  = "D103,D101,D107,D100,D102,D105, D104"
 
 
-
 [build-system]
 requires = ["poetry-core"]
 build-backend = "poetry.core.masonry.api"
 
 
 
 [tool.pylint]
@@ -114,44 +109,39 @@
 "wrong-import-position",
 "logging-fstring-interpolation",
 "forgotten-debug-statement",
 "W1203"
 ]
 
 good-names = "_,fn,el,ns,ch,i,n"
-ignore = ['p2g/tests']
+ignore = ['tests']
 [tool.pytest.ini_options]
 
-testpaths="p2g/tests"
 filterwarnings = [
     "ignore:Module already imported so cannot be rewritten"
 ]
 
 console_output_style="classic"
 log_format="%(asctime)s %(message)s"
 log_date_format="%H%M"
 addopts="-p no:pylama -p no:pytest_pylama --cov=p2g --cov-append --tb=short -m 'not forcefail'"
 
 [tool.coverage.run]
-# though it looks like python,
-# this code is examined but not actually not run.
-#omit = ["p2g/examples/*", "p2g/tests/*"]
-#include = ["p2g/*.py"]
-omit=["./*.py", "p2g/debug.py", "p2g/builtin.py", "p2g/examples/*.py", "p2g/tests/*.py"]
-[tool.coverage.report]
-#show_missing = true
-#skip_covered = true
-exclude_lines = ["raise AssertionError", "pragma: no cover", "pass","soon", ".*placeholder.*", "for debug", "hard to test right", "no cover; crashes pytest", "no cover"]
 
 
+[tool.coverage.report]
+include = ["p2g/*.py"]
+exclude_lines = ["NotImplemented", "AssertionError", "for debug",  "no cover","@(abc\\.)?abstractmethod" ]
+omit = ["tests/*.py","examples/*.py","p2g/__main__.py"]
+
 
 [tool.flake8]
 ignore = ['E231', 'E241', "T201", "SCS109", "B601", "IF100","SCS108", "S101","W503",
 'G004','E203', 'R504']
-exclude= ['p2g/tests', 'p2g/examples', 'p2g/doc']
+exclude= ['tests', 'examples', 'doc']
 per-file-ignores = [
     '__init__.py:F401',
     '__main__.py:E402',     #  module level import not at top of file
     'builtin.py:A001',    
     'op.py:E203,E501',
 
 # function names with mixed case in exports.
```


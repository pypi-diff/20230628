# Comparing `tmp/scinumtools-1.4.1.tar.gz` & `tmp/scinumtools-1.5.0.tar.gz`

## Comparing `scinumtools-1.4.1.tar` & `scinumtools-1.5.0.tar`

### file list

```diff
@@ -1,65 +1,67 @@
--rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.4.1/requirements.txt
--rw-r--r--   0        0        0      343 2020-02-02 00:00:00.000000 scinumtools-1.4.1/.github/workflows/pytest.yml
--rw-r--r--   0        0        0     1084 2020-02-02 00:00:00.000000 scinumtools-1.4.1/.github/workflows/python-publish.yml
--rw-r--r--   0        0        0      100 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/__init__.py
--rw-r--r--   0        0        0      530 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/data/CachingClass.py
--rw-r--r--   0        0        0     1786 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/data/ImageClass.py
--rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/data/PlottingClass.py
--rw-r--r--   0        0        0      145 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/data/__init__.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/math/__init__.py
--rw-r--r--   0        0        0     1969 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/math/solver/AtomClass.py
--rw-r--r--   0        0        0      574 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/math/solver/ExpressionClass.py
--rw-r--r--   0        0        0     7525 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/math/solver/OperatorClass.py
--rw-r--r--   0        0        0     3803 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/math/solver/SolverClass.py
--rw-r--r--   0        0        0     1210 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/math/solver/TokensClass.py
--rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/math/solver/__init__.py
--rw-r--r--   0        0        0     2455 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/phys/ConstantsClass.py
--rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/phys/__init__.py
--rw-r--r--   0        0        0     5118 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/phys/units/DimensionsClass.py
--rw-r--r--   0        0        0    10765 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/phys/units/QuantityClass.py
--rw-r--r--   0        0        0      555 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/phys/units/UnitClass.py
--rw-r--r--   0        0        0     2538 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/phys/units/UnitConverters.py
--rw-r--r--   0        0        0    10773 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/phys/units/UnitList.py
--rw-r--r--   0        0        0      132 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/phys/units/__init__.py
--rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/stats/StopwatchClass.py
--rw-r--r--   0        0        0       38 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/stats/__init__.py
--rw-r--r--   0        0        0     5509 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/structs/CollectorClass.py
--rw-r--r--   0        0        0     2488 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/structs/ParameterClass.py
--rw-r--r--   0        0        0      169 2020-02-02 00:00:00.000000 scinumtools-1.4.1/src/scinumtools/structs/__init__.py
--rw-r--r--   0        0        0       59 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/README.md
--rw-r--r--   0        0        0     1218 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/cached_data.npy
--rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/pyproject.toml
--rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/requirements.txt
--rw-r--r--   0        0        0     6537 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/test_data.py
--rw-r--r--   0        0        0     4225 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/test_math.py
--rw-r--r--   0        0        0      207 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/test_physics.py
--rw-r--r--   0        0        0      941 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/test_stats.py
--rw-r--r--   0        0        0     4184 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/test_struct.py
--rw-r--r--   0        0        0     6127 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/test_units.py
--rw-r--r--   0        0        0      100 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/__init__.py
--rw-r--r--   0        0        0      473 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/data/CachingClass.py
--rw-r--r--   0        0        0     1786 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/data/ImageClass.py
--rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/data/PlottingClass.py
--rw-r--r--   0        0        0      145 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/data/__init__.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/math/__init__.py
--rw-r--r--   0        0        0     1969 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/math/solver/AtomClass.py
--rw-r--r--   0        0        0      574 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/math/solver/ExpressionClass.py
--rw-r--r--   0        0        0     7525 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/math/solver/OperatorClass.py
--rw-r--r--   0        0        0     3803 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/math/solver/SolverClass.py
--rw-r--r--   0        0        0     1210 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/math/solver/TokensClass.py
--rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/math/solver/__init__.py
--rw-r--r--   0        0        0     2455 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/phys/ConstantsClass.py
--rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/phys/__init__.py
--rw-r--r--   0        0        0     9181 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/phys/units/QuantityClass.py
--rw-r--r--   0        0        0     2153 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/phys/units/UnitConverters.py
--rw-r--r--   0        0        0    10140 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/phys/units/UnitList.py
--rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/phys/units/__init__.py
--rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/stats/StopwatchClass.py
--rw-r--r--   0        0        0       38 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/stats/__init__.py
--rw-r--r--   0        0        0     5397 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/structs/CollectorClass.py
--rw-r--r--   0        0        0     2488 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/structs/ParameterClass.py
--rw-r--r--   0        0        0      169 2020-02-02 00:00:00.000000 scinumtools-1.4.1/tests/src/scinumtools/structs/__init__.py
--rw-r--r--   0        0        0     3081 2020-02-02 00:00:00.000000 scinumtools-1.4.1/.gitignore
--rw-r--r--   0        0        0       59 2020-02-02 00:00:00.000000 scinumtools-1.4.1/README.md
--rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 scinumtools-1.4.1/pyproject.toml
--rw-r--r--   0        0        0      605 2020-02-02 00:00:00.000000 scinumtools-1.4.1/PKG-INFO
+-rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.0/requirements.txt
+-rw-r--r--   0        0        0      343 2020-02-02 00:00:00.000000 scinumtools-1.5.0/.github/workflows/pytest.yml
+-rw-r--r--   0        0        0     1084 2020-02-02 00:00:00.000000 scinumtools-1.5.0/.github/workflows/python-publish.yml
+-rw-r--r--   0        0        0      100 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/__init__.py
+-rw-r--r--   0        0        0      530 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/data/CachingClass.py
+-rw-r--r--   0        0        0     1786 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/data/ImageClass.py
+-rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/data/PlottingClass.py
+-rw-r--r--   0        0        0      145 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/data/__init__.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/math/__init__.py
+-rw-r--r--   0        0        0     1969 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/math/solver/AtomClass.py
+-rw-r--r--   0        0        0      574 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/math/solver/ExpressionClass.py
+-rw-r--r--   0        0        0     7525 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/math/solver/OperatorClass.py
+-rw-r--r--   0        0        0     3803 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/math/solver/SolverClass.py
+-rw-r--r--   0        0        0     1210 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/math/solver/TokensClass.py
+-rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/math/solver/__init__.py
+-rw-r--r--   0        0        0     2455 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/phys/ConstantsClass.py
+-rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/phys/__init__.py
+-rw-r--r--   0        0        0     2535 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/phys/units/BaseUnitsClass.py
+-rw-r--r--   0        0        0     3283 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/phys/units/DimensionsClass.py
+-rw-r--r--   0        0        0    10773 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/phys/units/QuantityClass.py
+-rw-r--r--   0        0        0     3067 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/phys/units/RatioClass.py
+-rw-r--r--   0        0        0      555 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/phys/units/UnitClass.py
+-rw-r--r--   0        0        0     2538 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/phys/units/UnitConverters.py
+-rw-r--r--   0        0        0    10710 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/phys/units/UnitList.py
+-rw-r--r--   0        0        0      182 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/phys/units/__init__.py
+-rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/stats/StopwatchClass.py
+-rw-r--r--   0        0        0       38 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/stats/__init__.py
+-rw-r--r--   0        0        0     5509 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/structs/CollectorClass.py
+-rw-r--r--   0        0        0     2488 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/structs/ParameterClass.py
+-rw-r--r--   0        0        0      169 2020-02-02 00:00:00.000000 scinumtools-1.5.0/src/scinumtools/structs/__init__.py
+-rw-r--r--   0        0        0       59 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/README.md
+-rw-r--r--   0        0        0     1218 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/cached_data.npy
+-rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/pyproject.toml
+-rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/requirements.txt
+-rw-r--r--   0        0        0     6537 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/test_data.py
+-rw-r--r--   0        0        0     4225 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/test_math.py
+-rw-r--r--   0        0        0      207 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/test_physics.py
+-rw-r--r--   0        0        0      941 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/test_stats.py
+-rw-r--r--   0        0        0     4184 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/test_struct.py
+-rw-r--r--   0        0        0     8218 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/test_units.py
+-rw-r--r--   0        0        0      100 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/__init__.py
+-rw-r--r--   0        0        0      473 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/data/CachingClass.py
+-rw-r--r--   0        0        0     1786 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/data/ImageClass.py
+-rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/data/PlottingClass.py
+-rw-r--r--   0        0        0      145 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/data/__init__.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/math/__init__.py
+-rw-r--r--   0        0        0     1969 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/math/solver/AtomClass.py
+-rw-r--r--   0        0        0      574 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/math/solver/ExpressionClass.py
+-rw-r--r--   0        0        0     7525 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/math/solver/OperatorClass.py
+-rw-r--r--   0        0        0     3803 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/math/solver/SolverClass.py
+-rw-r--r--   0        0        0     1210 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/math/solver/TokensClass.py
+-rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/math/solver/__init__.py
+-rw-r--r--   0        0        0     2455 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/phys/ConstantsClass.py
+-rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/phys/__init__.py
+-rw-r--r--   0        0        0     9181 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/phys/units/QuantityClass.py
+-rw-r--r--   0        0        0     2153 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/phys/units/UnitConverters.py
+-rw-r--r--   0        0        0    10140 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/phys/units/UnitList.py
+-rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/phys/units/__init__.py
+-rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/stats/StopwatchClass.py
+-rw-r--r--   0        0        0       38 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/stats/__init__.py
+-rw-r--r--   0        0        0     5397 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/structs/CollectorClass.py
+-rw-r--r--   0        0        0     2488 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/structs/ParameterClass.py
+-rw-r--r--   0        0        0      169 2020-02-02 00:00:00.000000 scinumtools-1.5.0/tests/src/scinumtools/structs/__init__.py
+-rw-r--r--   0        0        0     3081 2020-02-02 00:00:00.000000 scinumtools-1.5.0/.gitignore
+-rw-r--r--   0        0        0       59 2020-02-02 00:00:00.000000 scinumtools-1.5.0/README.md
+-rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 scinumtools-1.5.0/pyproject.toml
+-rw-r--r--   0        0        0      605 2020-02-02 00:00:00.000000 scinumtools-1.5.0/PKG-INFO
```

### Comparing `scinumtools-1.4.1/.github/workflows/python-publish.yml` & `scinumtools-1.5.0/.github/workflows/python-publish.yml`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/src/scinumtools/data/CachingClass.py` & `scinumtools-1.5.0/src/scinumtools/data/CachingClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/src/scinumtools/data/ImageClass.py` & `scinumtools-1.5.0/src/scinumtools/data/ImageClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/src/scinumtools/data/PlottingClass.py` & `scinumtools-1.5.0/src/scinumtools/data/PlottingClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/src/scinumtools/math/solver/AtomClass.py` & `scinumtools-1.5.0/src/scinumtools/math/solver/AtomClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/src/scinumtools/math/solver/ExpressionClass.py` & `scinumtools-1.5.0/src/scinumtools/math/solver/ExpressionClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/src/scinumtools/math/solver/OperatorClass.py` & `scinumtools-1.5.0/src/scinumtools/math/solver/OperatorClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/src/scinumtools/math/solver/SolverClass.py` & `scinumtools-1.5.0/src/scinumtools/math/solver/SolverClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/src/scinumtools/math/solver/TokensClass.py` & `scinumtools-1.5.0/src/scinumtools/math/solver/TokensClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/src/scinumtools/phys/ConstantsClass.py` & `scinumtools-1.5.0/src/scinumtools/phys/ConstantsClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/src/scinumtools/phys/units/QuantityClass.py` & `scinumtools-1.5.0/tests/src/scinumtools/phys/units/QuantityClass.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,17 +1,18 @@
 from typing import List
 import numpy as np
 import re
+from math import isclose
 from typing import Union
+from dataclasses import dataclass
 
 from ...structs.ParameterClass import ParameterDict
 from ...math.solver import ExpressionSolver, AtomBase, OperatorPar, OperatorMul, OperatorTruediv
 from .UnitList import *
-from .UnitConverters import *
-#from .DimensionsClass import *
+from .UnitConverters import TemperatureConverter
 
 class Quantity:
     prefixes: dict            # list of prefixes 
     unitlist: dict            # list of units
     
     magnitude: float          # quantity magnitude
     dimensions: List[int]     # quantity dimensions
@@ -53,98 +54,63 @@
                 self.baseunits = {UnitBase[d]:dim for d,dim in enumerate(self.dimensions) if dim!=0}
         else:
             raise Exception("Insufficient quantity definition", magnitude, dimensions, baseunits)
         # Remove zero base units
         for unit in list(self.baseunits.keys()):
             if self.baseunits[unit]==0:
                 del self.baseunits[unit]
-
-    def _add(self, left, right):
-        if not isinstance(left, Quantity):
-            left = Quantity(left)
-        if not isinstance(right, Quantity):
-            right = Quantity(right)
-        if not left.dimensions==right.dimensions:
-            raise Exception('Addition of two units with different dimensions:', self, right)
-        magnitude = left.magnitude + right.magnitude
-        dimensions = list(left.dimensions)
-        baseunits = dict(left.baseunits)
-        return Quantity(magnitude, dimensions, baseunits)
-
+        
     def __add__(self, other):
-        return self._add(self, other)
-    
-    def __radd__(self, other):
-        return self._add(other, self)
-
-    def _sub(self, left, right):
-        if not isinstance(left, Quantity):
-            left = Quantity(left)
-        if not isinstance(right, Quantity):
-            right = Quantity(right)
-        if not left.dimensions==right.dimensions:
-            raise Exception('Substraction of two units with different dimensions:', self, right)
-        magnitude = left.magnitude - right.magnitude
-        dimensions = list(left.dimensions)
-        baseunits = dict(left.baseunits)
+        if not isinstance(other, Quantity):
+            other = Quantity(other)
+        if not self.dimensions==other.dimensions:
+            raise Exception('Addition of two units with different dimensions:', self, other)
+        magnitude = self.magnitude + other.magnitude
+        dimensions = list(self.dimensions)
+        baseunits = dict(self.baseunits)
         return Quantity(magnitude, dimensions, baseunits)
 
     def __sub__(self, other):
-        return self._sub(self, other)
-
-    def __rsub__(self, other):
-        return self._sub(other, self)
+        if not isinstance(other, Quantity):
+            other = Quantity(other)
+        if not self.dimensions==other.dimensions:
+            raise Exception('Substraction of two units with different dimensions:', self, other)
+        magnitude = self.magnitude - other.magnitude
+        dimensions = list(self.dimensions)
+        baseunits = dict(self.baseunits)
+        return Quantity(magnitude, dimensions, baseunits)
     
-    def _mul(self, left, right):
-        if not isinstance(left, Quantity):
-            left = Quantity(left)
-        if not isinstance(right, Quantity):
-            right = Quantity(right)
-        magnitude = left.magnitude * right.magnitude
-        dimensions = [left.dimensions[i]+right.dimensions[i] for i in range(len(UnitBase))]
-        baseunits = dict(left.baseunits)
-        for unit,exp in right.baseunits.items():
+    def __mul__(self, other):
+        if not isinstance(other, Quantity):
+            other = Quantity(other)
+        magnitude = self.magnitude * other.magnitude
+        dimensions = [self.dimensions[i]+other.dimensions[i] for i in range(len(UnitBase))]
+        baseunits = dict(self.baseunits)
+        for unit,exp in other.baseunits.items():
             baseunits[unit] = baseunits[unit]+exp if unit in baseunits else exp
         return Quantity(magnitude, dimensions, baseunits)
 
-    def __mul__(self, other):
-        return self._mul(self, other)
-
-    def __rmul__(self, other):
-        return self._mul(other, self)
-    
-    def _truediv(self, left, right):
-        if not isinstance(left, Quantity):
-            left = Quantity(left)
-        if not isinstance(right, Quantity):
-            right = Quantity(right)
-        magnitude = left.magnitude / right.magnitude
-        dimensions = [left.dimensions[i]-right.dimensions[i] for i in range(len(UnitBase))]
-        baseunits = dict(left.baseunits)
-        for unit,exp in right.baseunits.items():
+    def __truediv__(self, other):
+        if not isinstance(other, Quantity):
+            other = Quantity(other)
+        magnitude = self.magnitude / other.magnitude
+        dimensions = [self.dimensions[i]-other.dimensions[i] for i in range(len(UnitBase))]
+        baseunits = dict(self.baseunits)
+        for unit,exp in other.baseunits.items():
             baseunits[unit] = baseunits[unit]-exp if unit in baseunits else -exp
         return Quantity(magnitude, dimensions, baseunits)
 
-    def __truediv__(self, other):
-        return self._truediv(self, other)
-    
-    def __rtruediv__(self, other):
-        return self._truediv(other, self)
-    
     def __pow__(self, power):
         magnitude = self.magnitude**power
         dimensions = [self.dimensions[i]*power for i in range(len(UnitBase))]
         baseunits = {unit:exp*power for unit,exp in self.baseunits.items()}
         return Quantity(magnitude, dimensions, baseunits)
 
-    def __neg__(self):
-        return Quantity(-self.magnitude, self.dimensions, self.baseunits)
-    
     def __eq__(self, other):
-        if not np.allclose(self.magnitude, other.magnitude, rtol=self.precision):
+        if not isclose(self.magnitude, other.magnitude, rel_tol=self.precision):
             return False
         if self.dimensions!=other.dimensions:
             return False
         return True
     
     def __str__(self):
         magnitude = self.value()
@@ -170,27 +136,14 @@
         else:
             return f"Quantity({magnitude:s})"
 
     def __array__(self):
         return self.magnitude
 
     def __array_wrap__(self, out_arr, context=None):
-        """
-        if context[0]==np.sqrt:
-            dimensions = []
-            for d in range(len(UnitBase)):
-                dimensions.append( self.dimensions[d] )
-                if dimensions[d]==0:
-                    continue
-                elif isinstance(dimensions[d], int):
-                    dimensions[d] = Ratio(dimensions[d], 2)
-                elif isinstance(dimensions[d], Ratio):
-                    dimensions[d] = Ratio(dimensions[d][0], dimensions[d][1]+2)
-            print(dimensions)
-        """
         return Quantity(out_arr, self.dimensions, self.baseunits)
     
     def _atom_parser(self, string=None):
         # parse number
         m = re.match(r'^[-]?([0-9.]+)(e([0-9+-]+)|)$', str(string))
         if m:
             magnitude = float(string)
@@ -264,13 +217,12 @@
                 if np.all([-unit1.dimensions[d]==unit2.dimensions[d] for d in range(len(UnitBase))]):
                     unit1 = Quantity(1)/self
                 else:
                     raise Exception("Converting units with different dimensions:",
                                     unit1.dimensions, unit2.dimensions)
             with TemperatureConverter(unit1.baseunits, unit2.baseunits) as tc:
                 if tc.convertable:
-                    unit2.magnitude = unit1.magnitude/tc.convert(unit1.magnitude, unit2.magnitude)
-                    #return Quantity(tc.convert(unit1.magnitude, unit2.magnitude), units)
+                    return Quantity(tc.convert(unit1.magnitude, unit2.magnitude), units)
             unit = unit1/unit2
             return Quantity(unit.magnitude, units)
         else:
             raise Exception("Invalid units format:", units)
```

### Comparing `scinumtools-1.4.1/src/scinumtools/phys/units/UnitClass.py` & `scinumtools-1.5.0/src/scinumtools/phys/units/UnitClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/src/scinumtools/phys/units/UnitConverters.py` & `scinumtools-1.5.0/src/scinumtools/phys/units/UnitConverters.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/src/scinumtools/phys/units/UnitList.py` & `scinumtools-1.5.0/src/scinumtools/phys/units/UnitList.py`

 * *Files 1% similar despite different names*

```diff
@@ -21,16 +21,14 @@
     'p':        (1.0e-12,        [ 0, 0, 0, 0, 0, 0, 0, 0],  '1e-12',                  'pico'             ), 
     'f':        (1.0e-15,        [ 0, 0, 0, 0, 0, 0, 0, 0],  '1e-15',                  'femto'            ), 
     'a':        (1.0e-18,        [ 0, 0, 0, 0, 0, 0, 0, 0],  '1e-18',                  'atto'             ), 
     'z':        (1.0e-21,        [ 0, 0, 0, 0, 0, 0, 0, 0],  '1e-21',                  'zepto'            ), 
     'y':        (1.0e-24,        [ 0, 0, 0, 0, 0, 0, 0, 0],  '1e-24',                  'yocto'            ), 
 }                                                                                        
             
-UnitBase = ['m','g','s','K','C','cd','mol','rad']
-            
 UnitStandard = {
     # base physical units
     'm':        (1.0,            [ 1, 0, 0, 0, 0, 0, 0, 0],  None,                     'meter'            ),
     'g':        (1.0,            [ 0, 1, 0, 0, 0, 0, 0, 0],  None,                     'gram'             ),
     's':        (1.0,            [ 0, 0, 1, 0, 0, 0, 0, 0],  None,                     'second'           ),
     'K':        (1.0,            [ 0, 0, 0, 1, 0, 0, 0, 0],  None,                     'kelvin'           ),
     'C':        (1.0,            [ 0, 0, 0, 0, 1, 0, 0, 0],  None,                     'coulomb'          ),
```

### Comparing `scinumtools-1.4.1/src/scinumtools/stats/StopwatchClass.py` & `scinumtools-1.5.0/src/scinumtools/stats/StopwatchClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/src/scinumtools/structs/CollectorClass.py` & `scinumtools-1.5.0/src/scinumtools/structs/CollectorClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/src/scinumtools/structs/ParameterClass.py` & `scinumtools-1.5.0/src/scinumtools/structs/ParameterClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/cached_data.npy` & `scinumtools-1.5.0/tests/cached_data.npy`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/pyproject.toml` & `scinumtools-1.5.0/tests/pyproject.toml`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/test_data.py` & `scinumtools-1.5.0/tests/test_data.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/test_math.py` & `scinumtools-1.5.0/tests/test_math.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/test_stats.py` & `scinumtools-1.5.0/tests/test_stats.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/test_struct.py` & `scinumtools-1.5.0/tests/test_struct.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/test_units.py` & `scinumtools-1.5.0/tests/test_units.py`

 * *Files 25% similar despite different names*

```diff
@@ -5,25 +5,106 @@
 import sys
 sys.path.insert(0, 'src')
 
 from scinumtools.structs import ParameterDict
 from scinumtools.phys.units.UnitList import UnitStandard, UnitPrefixes
 from scinumtools.phys.units import *
 
+def test_quantity():
+    
+    assert str(Quantity(123e2)) == "Quantity(1.230e+04)"
+    
+    result = "Quantity(1.230e+04 m*s2:3)"
+    assert str(Quantity(123e2, [1,0,(2,3),0,0,0,0,0] ))    == result
+    assert str(Quantity(123e2, Dimensions(m=1, s=(2,3)) )) == result
+
+    result = "Quantity(1.230e+04 J2*kg2:3)"
+    assert str(Quantity(123e2, {'J': 2, 'kg':(2,3)} )) == result
+    assert str(Quantity(123e2, BaseUnits({'J': 2, 'kg':(2,3)}) )) == result
+    
+def test_units():
+
+    assert str(Unit('m'))         == "Quantity(1.000e+00 m)"
+    assert str(Unit('kg*m2*s-2')) == "Quantity(1.000e+00 kg*m2*s-2)"
+    
+    unit = Unit()
+    assert str(unit.m)      == "Quantity(1.000e+00 m)"
+    assert str(2*unit.kJ)   == "Quantity(2.000e+00 kJ)"
+    assert str(unit.kg*unit.m**2/unit.s**2) == "Quantity(1.000e+00 kg*m2*s-2)"
+    assert str(unit.J.to('erg')) == "Quantity(1.000e+07 erg)"
+
+def test_constants():
+
+    assert str(Constant('c')) == "Quantity(1.000e+00 [c])"
+
+    const = Constant()
+    assert str(const.c)   == "Quantity(1.000e+00 [c])"
+    assert str(const.m_e) == "Quantity(1.000e+00 [m_e])"
+    
+def test_dimensions():
+
+    # Test simplification
+    dims = Dimensions(m=(5,-2), g=3, s=1, cd=(-0,3), K=(34,1), rad=(18,12))
+    assert str(dims) == "Dimensions(m=-5:2 g=3 s=1 K=34 rad=3:2)"
+
+    # Test arithmetics
+    dims1 = Dimensions(m=3, g=(3,2))
+    dims2 = Dimensions(m=2, g=(4,7))
+    assert not dims1==dims2
+    assert str(dims1+dims2) == "Dimensions(m=5 g=29:14)"
+    assert str(dims1-dims2) == "Dimensions(m=1 g=13:14)"
+    assert str(dims1*2)     == "Dimensions(m=6 g=3)"
+    assert str(dims2*0.5)   == "Dimensions(m=1 g=2:7)"
+
+    # Test values
+    value = [3, (3,2), 0, 0, 0, 0, 0, 0]
+    dims = Dimensions(*value)
+    assert str(dims) == "Dimensions(m=3 g=3:2)" 
+    assert dims.value() == value
+    assert dims.value(dtype=dict) == {'m': 3, 'g':(3,2)}
+    
+def test_base_units():
+
+    # Test simplification
+    bu = BaseUnits({'g':(3,2), 'km': 3, '[m_p]': (3,1)})
+    assert str(bu) == "BaseUnits(g=3:2 km=3 [m_p]=3)"
+
+    # Test arithmetics
+    bu1 = BaseUnits({'km':3,'g':(3,2)})
+    bu2 = BaseUnits({'km':2,'g':(4,7)})
+    assert not bu1 == bu2
+    assert str(bu1+bu2)  == "BaseUnits(km=5 g=29:14)"
+    assert str(bu1-bu2)  == "BaseUnits(km=1 g=13:14)"
+    assert str(bu1*2)    == "BaseUnits(km=6 g=3)"
+    assert str(bu2*0.5)  == "BaseUnits(km=1 g=2:7)"
+
+    # Test values
+    value = {"km": 2, "K": (3,2)}
+    bu = BaseUnits(dict(value))
+    assert str(bu) == "BaseUnits(km=2 K=3:2)"
+    assert bu.value() == value
+    
 def test_definitions():
     
     unitlist = ParameterDict(['magnitude','dimensions','definition','name'], UnitStandard)
     for symbol, unit in unitlist.items():
         if not isinstance(unit['definition'],str):
             continue
         q = Quantity(1, unit['definition'])
         assert isclose(q.magnitude,  unit['magnitude'], rel_tol=1e-07)
-        assert q.dimensions == unit['dimensions']
+        assert q.dimensions.value() == unit['dimensions']
+        
     prefixes = ParameterDict(['magnitude','dimensions','definition','name'], UnitPrefixes)
-
+    for symbol, unit in prefixes.items():
+        if not isinstance(unit['definition'],str):
+            continue
+        q = Quantity(1, unit['definition'])
+        assert isclose(q.magnitude,  unit['magnitude'], rel_tol=1e-07)
+        assert q.dimensions.value() == unit['dimensions']
+        
 def test_temperatures():
     
     # Temperature conversions
     assert str(Quantity(23,'K').to('Cel'))        == "Quantity(-2.501e+02 Cel)"
     assert str(Quantity(23,'K').to('degF'))       == "Quantity(-4.183e+02 degF)"
     assert str(Quantity(23,'K').to('degR'))       == "Quantity(4.140e+01 degR)"
     assert str(Quantity(23,'Cel').to('K'))        == "Quantity(2.961e+02 K)"
@@ -40,15 +121,15 @@
 def test_inversion():
 
     assert str(Quantity(23, 'Hz').to('s'))     == "Quantity(4.348e-02 s)"
     assert str(Quantity(34, 'Ohm').to('S'))    == "Quantity(2.941e-02 S)"
     assert str(Quantity(102, 'J').to('erg-1')) == "Quantity(9.804e-10 erg-1)"
 
 def test_scalar_arithmetics():
-    
+
     q = Quantity(123e2, [3,3,0,0,1,0,0,0])
     assert str(q) == "Quantity(1.230e+04 m3*g3*C)"    
     q /= Quantity(123, 'C')
     assert str(q) == "Quantity(1.000e+02 m3*g3)"
     q *= Quantity(2, 's2')
     assert str(q) == "Quantity(2.000e+02 m3*g3*s2)"
     q = Quantity(123, "kg3*cm-2*s")
@@ -67,16 +148,16 @@
     assert str(q) == "Quantity(1.230e+00 kg3*s*cm-3)"
     q = Quantity(134e-34)
     assert str(q) == "Quantity(1.340e-32)"
     
     with pytest.raises(Exception) as excinfo:
         q = q.to("kg3*s/cm3")
     assert excinfo.value.args[0]=="Converting units with different dimensions:"
-    assert excinfo.value.args[1]==[0, 0, 0, 0, 0, 0, 0, 0]
-    assert excinfo.value.args[2]==[-3, 3, 1, 0, 0, 0, 0, 0]
+    assert excinfo.value.args[1].value()==[0, 0, 0, 0, 0, 0, 0, 0]
+    assert excinfo.value.args[2].value()==[-3, 3, 1, 0, 0, 0, 0, 0]
 
 def test_array_arithmetics():
 
     # Test basic arithmetics
     q = Quantity([2,3,4], 'm')
     assert str(q) == "Quantity([2. 3. 4.] m)"
     q += Quantity(2, 'm')
@@ -100,62 +181,34 @@
 
     # Test unit conversion on arrays
     assert str(Quantity([1,2,3], 'm').to('km')) == "Quantity([0.001 0.002 0.003] km)"
 
 def test_numpy():
     
     # Test numpy functions
-    assert str(np.sqrt(Quantity([4, 9, 16], 'm2'))) == "Quantity([2. 3. 4.] m2)"
+    assert str(np.sqrt(Quantity([4, 9, 16], 'm2')))  == "Quantity([2. 3. 4.] m)"
+    assert str(np.sqrt(Quantity([4, 9, 16], 'm3')))  == "Quantity([2. 3. 4.] m3:2)"
+    assert str(np.sqrt(Quantity([4, 9, 16], 'm-3')))  == "Quantity([2. 3. 4.] m-3:2)"
+    assert str(np.sqrt(Quantity([4, 9, 16], 'm2:3')))  == "Quantity([2. 3. 4.] m1:3)"
+    assert str(np.sqrt(Quantity([4, 9, 16], 'm2:3*g3:5*s5')))  == "Quantity([2. 3. 4.] m1:3*g3:10*s5:2)"
+    assert str(np.cbrt(Quantity([8, 27, 64], 'm3'))) == "Quantity([2. 3. 4.] m)"
+    assert str(np.power(Quantity([2, 3, 4], 'm'),3)) == "Quantity([ 8. 27. 64.] m3)"
 
 def test_operation_sides():
     
     p = Quantity([2,3,4], 'm')
     q = Quantity([5,6,7], 'm')
     assert p+q == q+p
     assert p-q == -(q-p)
     assert q*2 == 2*q
     assert p/2 == 1/(2/p)
-
-def test_units():
-
-    assert str(Unit('m'))         == "Quantity(1.000e+00 m)"
-    assert str(Unit('kg*m2*s-2')) == "Quantity(1.000e+00 kg*m2*s-2)"
-    
-    unit = Unit()
-    assert str(unit.m)      == "Quantity(1.000e+00 m)"
-    assert str(2*unit.kJ)   == "Quantity(2.000e+00 kJ)"
-    assert str(unit.kg*unit.m**2/unit.s**2) == "Quantity(1.000e+00 kg*m2*s-2)"
-    assert str(unit.J.to('erg')) == "Quantity(1.000e+07 erg)"
-
-def test_constants():
-
-    assert str(Constant('c')) == "Quantity(1.000e+00 [c])"
-
-    const = Constant()
-    assert str(const.c)   == "Quantity(1.000e+00 [c])"
-    assert str(const.m_e) == "Quantity(1.000e+00 [m_e])"
     
 def test_unique_names():
 
     units = list(UnitStandard.keys())
     for unit in UnitStandard.keys():
         for prefix in UnitPrefixes.keys():
             units.append(f"{prefix}{unit}")
     units.sort()
     seen = set()
     dupes = [x for x in units if x in seen or seen.add(x)]    
     assert len(dupes)==0
-
-def test_dimensions():
-    
-    dims = Dimensions(m=(5,-2), g=3, s=1, cd=(-0,3), K=(34,1), rad=(18,12))
-    assert str(dims) == "Dimensions(m=Ratio(-5,2), g=3, s=1, K=34, rad=Ratio(3,2))"
-
-    dims1 = Dimensions(m=3, g=(3,2))
-    dims2 = Dimensions(m=2, g=(4,7))
-    assert not dims1==dims2
-    assert str(dims1+dims1) == "Dimensions(m=3, g=Ratio(3,2))"
-    assert str(dims2-dims2) == "Dimensions(m=2, g=Ratio(4,7))"
-    assert str(dims1*dims2) == "Dimensions(m=5, g=Ratio(29,14))"
-    assert str(dims1/dims2) == "Dimensions(m=1, g=Ratio(13,14))"
-    assert str(dims1**2)    == "Dimensions(m=6, g=3)"
-    assert str(dims2**0.5)  == "Dimensions(m=1, g=Ratio(2,7))"
```

### Comparing `scinumtools-1.4.1/tests/src/scinumtools/data/ImageClass.py` & `scinumtools-1.5.0/tests/src/scinumtools/data/ImageClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/src/scinumtools/data/PlottingClass.py` & `scinumtools-1.5.0/tests/src/scinumtools/data/PlottingClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/src/scinumtools/math/solver/AtomClass.py` & `scinumtools-1.5.0/tests/src/scinumtools/math/solver/AtomClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/src/scinumtools/math/solver/ExpressionClass.py` & `scinumtools-1.5.0/tests/src/scinumtools/math/solver/ExpressionClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/src/scinumtools/math/solver/OperatorClass.py` & `scinumtools-1.5.0/tests/src/scinumtools/math/solver/OperatorClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/src/scinumtools/math/solver/SolverClass.py` & `scinumtools-1.5.0/tests/src/scinumtools/math/solver/SolverClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/src/scinumtools/math/solver/TokensClass.py` & `scinumtools-1.5.0/tests/src/scinumtools/math/solver/TokensClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/src/scinumtools/phys/ConstantsClass.py` & `scinumtools-1.5.0/tests/src/scinumtools/phys/ConstantsClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/src/scinumtools/phys/units/QuantityClass.py` & `scinumtools-1.5.0/src/scinumtools/phys/units/QuantityClass.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,164 +1,215 @@
 from typing import List
 import numpy as np
 import re
-from math import isclose
 from typing import Union
-from dataclasses import dataclass
 
 from ...structs.ParameterClass import ParameterDict
 from ...math.solver import ExpressionSolver, AtomBase, OperatorPar, OperatorMul, OperatorTruediv
 from .UnitList import *
-from .UnitConverters import TemperatureConverter
+from .UnitConverters import *
+from .DimensionsClass import Dimensions
+from .BaseUnitsClass import BaseUnits
+from .RatioClass import Ratio
 
 class Quantity:
     prefixes: dict            # list of prefixes 
     unitlist: dict            # list of units
     
     magnitude: float          # quantity magnitude
-    dimensions: List[int]     # quantity dimensions
-    baseunits: dict           # base units
+    dimensions: Dimensions    # quantity dimensions
+    baseunits: BaseUnits      # base units
 
     precision: float = 1e-7
 
     def __init__(
             self, magnitude:float,
-            dimensions = None,
-            baseunits = {}
+            dimensions: Union[str,list,np.ndarray,Dimensions,dict,BaseUnits] = None,
+            baseunits: Union[dict,BaseUnits] = None
     ):
         # Initialize settings
         self.unitlist = ParameterDict(['magnitude','dimensions','definition','name'], UnitStandard)
         self.prefixes = ParameterDict(['magnitude','dimensions','definition','name'], UnitPrefixes)
         if isinstance(magnitude, (int,float)):
             self.magnitude = float(magnitude)
         elif isinstance(magnitude, list):
             self.magnitude = np.array(magnitude, dtype=float)
         elif isinstance(magnitude, np.ndarray):
             self.magnitude = magnitude.astype(float)
         else:
             raise Exception("Magnitude can be either a number or an list/array of numbers")
         # Set quantity
         if dimensions is None:
-            self.dimensions = [0]*len(UnitBase)
-            self.baseunits = {}
-        elif isinstance(dimensions, str):
+            self.dimensions = Dimensions()
+            self.baseunits = BaseUnits()
+        elif isinstance(dimensions, (str, dict, BaseUnits)):
+            if isinstance(dimensions, dict):
+                dimensions = BaseUnits(dimensions).expression()
+            elif isinstance(dimensions, BaseUnits):
+                dimensions = dimensions.expression()
             with ExpressionSolver(self._atom_parser, [OperatorPar,OperatorMul,OperatorTruediv]) as es:
                 unit = es.solve(dimensions)
             self.magnitude *= unit.magnitude
-            self.dimensions = list(unit.dimensions)
-            self.baseunits = dict(unit.baseunits)
-        elif isinstance(dimensions, (list, np.ndarray)):
-            self.dimensions = list(dimensions)
-            if baseunits:
+            self.dimensions = unit.dimensions
+            self.baseunits = unit.baseunits
+        elif isinstance(dimensions, (list, np.ndarray, Dimensions)):
+            if isinstance(dimensions, Dimensions):
+                self.dimensions = dimensions
+            else:
+                self.dimensions = Dimensions(*dimensions)
+            if isinstance(baseunits, dict):
+                self.baseunits = BaseUnits(baseunits)
+            elif isinstance(baseunits, BaseUnits):
                 self.baseunits = baseunits
             else:
-                self.baseunits = {UnitBase[d]:dim for d,dim in enumerate(self.dimensions) if dim!=0}
+                self.baseunits = BaseUnits(self.dimensions.value(dtype=dict))
         else:
             raise Exception("Insufficient quantity definition", magnitude, dimensions, baseunits)
-        # Remove zero base units
-        for unit in list(self.baseunits.keys()):
-            if self.baseunits[unit]==0:
-                del self.baseunits[unit]
-        
+
+    def _add(self, left, right):
+        if not isinstance(left, Quantity):
+            left = Quantity(left)
+        if not isinstance(right, Quantity):
+            right = Quantity(right)
+        magnitude = left.magnitude + right.magnitude
+        if not left.dimensions == right.dimensions:
+            raise Exception('Dimension does not match:', left.dimensions, right.dimensions)
+        dimensions = left.dimensions
+        baseunits = left.baseunits
+        return Quantity(magnitude, dimensions, baseunits)
+
     def __add__(self, other):
-        if not isinstance(other, Quantity):
-            other = Quantity(other)
-        if not self.dimensions==other.dimensions:
-            raise Exception('Addition of two units with different dimensions:', self, other)
-        magnitude = self.magnitude + other.magnitude
-        dimensions = list(self.dimensions)
-        baseunits = dict(self.baseunits)
+        return self._add(self, other)
+    
+    def __radd__(self, other):
+        return self._add(other, self)
+
+    def _sub(self, left, right):
+        if not isinstance(left, Quantity):
+            left = Quantity(left)
+        if not isinstance(right, Quantity):
+            right = Quantity(right)
+        magnitude = left.magnitude - right.magnitude
+        if not left.dimensions == right.dimensions:
+            raise Exception('Dimension does not match:', left.dimensions, right.dimensions)
+        dimensions = left.dimensions
+        baseunits = left.baseunits
         return Quantity(magnitude, dimensions, baseunits)
 
     def __sub__(self, other):
-        if not isinstance(other, Quantity):
-            other = Quantity(other)
-        if not self.dimensions==other.dimensions:
-            raise Exception('Substraction of two units with different dimensions:', self, other)
-        magnitude = self.magnitude - other.magnitude
-        dimensions = list(self.dimensions)
-        baseunits = dict(self.baseunits)
-        return Quantity(magnitude, dimensions, baseunits)
+        return self._sub(self, other)
+
+    def __rsub__(self, other):
+        return self._sub(other, self)
     
-    def __mul__(self, other):
-        if not isinstance(other, Quantity):
-            other = Quantity(other)
-        magnitude = self.magnitude * other.magnitude
-        dimensions = [self.dimensions[i]+other.dimensions[i] for i in range(len(UnitBase))]
-        baseunits = dict(self.baseunits)
-        for unit,exp in other.baseunits.items():
-            baseunits[unit] = baseunits[unit]+exp if unit in baseunits else exp
+    def _mul(self, left, right):
+        if not isinstance(left, Quantity):
+            left = Quantity(left)
+        if not isinstance(right, Quantity):
+            right = Quantity(right)
+        magnitude = left.magnitude * right.magnitude
+        dimensions = left.dimensions + right.dimensions
+        baseunits = left.baseunits + right.baseunits
         return Quantity(magnitude, dimensions, baseunits)
 
-    def __truediv__(self, other):
-        if not isinstance(other, Quantity):
-            other = Quantity(other)
-        magnitude = self.magnitude / other.magnitude
-        dimensions = [self.dimensions[i]-other.dimensions[i] for i in range(len(UnitBase))]
-        baseunits = dict(self.baseunits)
-        for unit,exp in other.baseunits.items():
-            baseunits[unit] = baseunits[unit]-exp if unit in baseunits else -exp
+    def __mul__(self, other):
+        return self._mul(self, other)
+
+    def __rmul__(self, other):
+        return self._mul(other, self)
+    
+    def _truediv(self, left, right):
+        if not isinstance(left, Quantity):
+            left = Quantity(left)
+        if not isinstance(right, Quantity):
+            right = Quantity(right)
+        magnitude = left.magnitude / right.magnitude
+        dimensions = left.dimensions - right.dimensions
+        baseunits = left.baseunits - right.baseunits
         return Quantity(magnitude, dimensions, baseunits)
 
+    def __truediv__(self, other):
+        return self._truediv(self, other)
+    
+    def __rtruediv__(self, other):
+        return self._truediv(other, self)
+    
     def __pow__(self, power):
         magnitude = self.magnitude**power
-        dimensions = [self.dimensions[i]*power for i in range(len(UnitBase))]
-        baseunits = {unit:exp*power for unit,exp in self.baseunits.items()}
+        dimensions = self.dimensions*power
+        baseunits = self.baseunits*power
         return Quantity(magnitude, dimensions, baseunits)
 
+    def __neg__(self):
+        return Quantity(-self.magnitude, self.dimensions, self.baseunits)
+    
     def __eq__(self, other):
-        if not isclose(self.magnitude, other.magnitude, rel_tol=self.precision):
+        if not np.allclose(self.magnitude, other.magnitude, rtol=self.precision):
             return False
-        if self.dimensions!=other.dimensions:
+        if not self.dimensions==other.dimensions:
             return False
         return True
     
     def __str__(self):
         magnitude = self.value()
         if isinstance(magnitude, np.ndarray):
             with np.printoptions(precision=3, suppress=False, threshold=5):
                 magnitude = f"{str(magnitude):s}"
         else:
             magnitude = f"{magnitude:.03e}"
-        if self.baseunits:
-            return f"Quantity({magnitude:s} {self.units()})"
+        baseunits = self.baseunits.expression()
+        if baseunits:
+            return f"Quantity({magnitude:s} {baseunits})"
         else:
             return f"Quantity({magnitude:s})"
             
     def __repr__(self):
         magnitude = self.value()
         if isinstance(magnitude, np.ndarray):
             with np.printoptions(precision=3, suppress=False, threshold=5):
                 magnitude = f"{str(magnitude):s}"
         else:
             magnitude = f"{magnitude:.03e}"
-        if self.baseunits:
-            return f"Quantity({magnitude:s} {self.units()})"
+        baseunits = self.baseunits.expression()
+        if baseunits:
+            return f"Quantity({magnitude:s} {baseunits})"
         else:
             return f"Quantity({magnitude:s})"
 
     def __array__(self):
         return self.magnitude
 
     def __array_wrap__(self, out_arr, context=None):
-        return Quantity(out_arr, self.dimensions, self.baseunits)
+        dimensions = self.dimensions
+        baseunits = self.baseunits
+        if context:
+            if context[0]==np.sqrt:
+                dimensions /= 2
+                baseunits /= 2
+            elif context[0]==np.cbrt:
+                dimensions /= 3
+                baseunits /= 3
+            elif context[0]==np.power:
+                dimensions *= context[1][1]
+                baseunits *= context[1][1]
+        return Quantity(out_arr, dimensions, baseunits)
     
     def _atom_parser(self, string=None):
         # parse number
         m = re.match(r'^[-]?([0-9.]+)(e([0-9+-]+)|)$', str(string))
         if m:
             magnitude = float(string)
             return Quantity(magnitude)
         # parse unit
         string_bak = string
         exp, base, prefix = '', '', ''
         symbol, string = string[-1], ' '+string[:-1]
         # parse exponent
         while len(string):
-            if not re.match('^[0-9+-]{1}$', symbol):
+            if not re.match('^[0-9'+Ratio.symbol+'+-]{1}$', symbol):
                 break
             exp = symbol+exp
             symbol, string = string[-1], string[:-1]
         # parse unit symbol
         unitkeys = self.unitlist.keys()
         while len(string):
             nbase = len(base)+1
@@ -176,53 +227,54 @@
             symbol, string = string[-1], string[:-1]
             if symbol==' ':
                 break
         if prefix:
             if prefix not in self.prefixes.keys():
                 raise Exception(f"Unknown unit prefix:", string_bak)
             magnitude *= self.prefixes[prefix].magnitude
-            unitid = f"{prefix:s}:{unitid}"
+            unitid = f"{prefix:s}{BaseUnits.symbol}{unitid}"
         # apply exponent
-        if exp:
+        if exp and Ratio.symbol in exp:
+            exp = exp.split(Ratio.symbol)
+            exprat = Ratio(int(exp[0]), int(exp[1]))
+            magnitude = magnitude**(int(exp[0])/int(exp[1]))
+            dimensions = [exprat*dim for dim in dimensions]
+            baseunits = {unitid: exprat}
+        elif exp:
             exp = int(exp)
             magnitude = magnitude**exp
             dimensions = [dim*exp for dim in dimensions]
-            baseunits = {unitid: exp}
+            baseunits = {unitid: exp}            
         else:
             baseunits = {unitid: 1}
         return Quantity(magnitude, dimensions, baseunits)
     
     def value(self):
-        if self.baseunits:
-            unit = self/Quantity(1,self.units(self.baseunits))
+        baseunits = self.baseunits.expression()
+        if baseunits:
+            unit = self/Quantity(1,baseunits)
+            return unit.magnitude
         else:
             return self.magnitude
-        return unit.magnitude
 
-    def units(self, baseunits=None):
-        if baseunits is None:
-            baseunits = self.baseunits
-        units = []
-        for unitid,exponent in baseunits.items():
-            symbol = unitid.replace(':','')
-            units.append(f"{symbol}" if exponent==1 else f"{symbol}{exponent}")
-        return "*".join(units)
+    def units(self):
+        return self.baseunits.expression()
 
     def to(self, units):
         if isinstance(units,str):
             unit1 = self
             unit2 = Quantity(1,units)
             # Check if units can be directly converted
-            if unit1.dimensions!=unit2.dimensions:
+            if not unit1.dimensions==unit2.dimensions:
                 # Check if inverted unit can be converted
-                if np.all([-unit1.dimensions[d]==unit2.dimensions[d] for d in range(len(UnitBase))]):
+                if -unit1.dimensions==unit2.dimensions:
                     unit1 = Quantity(1)/self
                 else:
                     raise Exception("Converting units with different dimensions:",
                                     unit1.dimensions, unit2.dimensions)
-            with TemperatureConverter(unit1.baseunits, unit2.baseunits) as tc:
+            with TemperatureConverter(unit1.baseunits.value(), unit2.baseunits.value()) as tc:
                 if tc.convertable:
-                    return Quantity(tc.convert(unit1.magnitude, unit2.magnitude), units)
+                    unit2.magnitude = unit1.magnitude/tc.convert(unit1.magnitude, unit2.magnitude)
             unit = unit1/unit2
             return Quantity(unit.magnitude, units)
         else:
             raise Exception("Invalid units format:", units)
```

### Comparing `scinumtools-1.4.1/tests/src/scinumtools/phys/units/UnitConverters.py` & `scinumtools-1.5.0/tests/src/scinumtools/phys/units/UnitConverters.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/src/scinumtools/phys/units/UnitList.py` & `scinumtools-1.5.0/tests/src/scinumtools/phys/units/UnitList.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/src/scinumtools/stats/StopwatchClass.py` & `scinumtools-1.5.0/tests/src/scinumtools/stats/StopwatchClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/src/scinumtools/structs/CollectorClass.py` & `scinumtools-1.5.0/tests/src/scinumtools/structs/CollectorClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/tests/src/scinumtools/structs/ParameterClass.py` & `scinumtools-1.5.0/tests/src/scinumtools/structs/ParameterClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/.gitignore` & `scinumtools-1.5.0/.gitignore`

 * *Files identical despite different names*

### Comparing `scinumtools-1.4.1/pyproject.toml` & `scinumtools-1.5.0/pyproject.toml`

 * *Files 19% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["hatchling"]
 build-backend = "hatchling.build"
 
 [project]
 name = "scinumtools"
-version = "1.4.1"
+version = "1.5.0"
 authors = [
   { name="Ondrej Pego Jaura", email="vrtulka23@pm.me" },
 ]
 description = "Set of most frequently used tools for a rapid numerical code development in Python."
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```


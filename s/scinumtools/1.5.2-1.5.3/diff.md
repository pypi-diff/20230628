# Comparing `tmp/scinumtools-1.5.2.tar.gz` & `tmp/scinumtools-1.5.3.tar.gz`

## Comparing `scinumtools-1.5.2.tar` & `scinumtools-1.5.3.tar`

### file list

```diff
@@ -1,67 +1,67 @@
--rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.2/requirements.txt
--rw-r--r--   0        0        0      343 2020-02-02 00:00:00.000000 scinumtools-1.5.2/.github/workflows/pytest.yml
--rw-r--r--   0        0        0     1084 2020-02-02 00:00:00.000000 scinumtools-1.5.2/.github/workflows/python-publish.yml
--rw-r--r--   0        0        0      100 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/__init__.py
--rw-r--r--   0        0        0      530 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/data/CachingClass.py
--rw-r--r--   0        0        0     1786 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/data/ImageClass.py
--rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/data/PlottingClass.py
--rw-r--r--   0        0        0      145 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/data/__init__.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/math/__init__.py
--rw-r--r--   0        0        0     1969 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/math/solver/AtomClass.py
--rw-r--r--   0        0        0      574 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/math/solver/ExpressionClass.py
--rw-r--r--   0        0        0     7525 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/math/solver/OperatorClass.py
--rw-r--r--   0        0        0     3803 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/math/solver/SolverClass.py
--rw-r--r--   0        0        0     1210 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/math/solver/TokensClass.py
--rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/math/solver/__init__.py
--rw-r--r--   0        0        0     2455 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/ConstantsClass.py
--rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/__init__.py
--rw-r--r--   0        0        0     2535 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/BaseUnitsClass.py
--rw-r--r--   0        0        0     3283 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/DimensionsClass.py
--rw-r--r--   0        0        0    11143 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/QuantityClass.py
--rw-r--r--   0        0        0     3067 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/RatioClass.py
--rw-r--r--   0        0        0      555 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/UnitClass.py
--rw-r--r--   0        0        0     2538 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/UnitConverters.py
--rw-r--r--   0        0        0    10710 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/UnitList.py
--rw-r--r--   0        0        0      182 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/__init__.py
--rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/stats/StopwatchClass.py
--rw-r--r--   0        0        0       38 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/stats/__init__.py
--rw-r--r--   0        0        0     5509 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/structs/CollectorClass.py
--rw-r--r--   0        0        0     2488 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/structs/ParameterClass.py
--rw-r--r--   0        0        0      169 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/structs/__init__.py
--rw-r--r--   0        0        0       59 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/README.md
--rw-r--r--   0        0        0     1218 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/cached_data.npy
--rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/pyproject.toml
--rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/requirements.txt
--rw-r--r--   0        0        0     6537 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/test_data.py
--rw-r--r--   0        0        0     4225 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/test_math.py
--rw-r--r--   0        0        0      207 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/test_physics.py
--rw-r--r--   0        0        0      941 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/test_stats.py
--rw-r--r--   0        0        0     4184 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/test_struct.py
--rw-r--r--   0        0        0     8442 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/test_units.py
--rw-r--r--   0        0        0      100 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/__init__.py
--rw-r--r--   0        0        0      473 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/data/CachingClass.py
--rw-r--r--   0        0        0     1786 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/data/ImageClass.py
--rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/data/PlottingClass.py
--rw-r--r--   0        0        0      145 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/data/__init__.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/math/__init__.py
--rw-r--r--   0        0        0     1969 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/math/solver/AtomClass.py
--rw-r--r--   0        0        0      574 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/math/solver/ExpressionClass.py
--rw-r--r--   0        0        0     7525 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/math/solver/OperatorClass.py
--rw-r--r--   0        0        0     3803 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/math/solver/SolverClass.py
--rw-r--r--   0        0        0     1210 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/math/solver/TokensClass.py
--rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/math/solver/__init__.py
--rw-r--r--   0        0        0     2455 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/phys/ConstantsClass.py
--rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/phys/__init__.py
--rw-r--r--   0        0        0     9181 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/phys/units/QuantityClass.py
--rw-r--r--   0        0        0     2153 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/phys/units/UnitConverters.py
--rw-r--r--   0        0        0    10140 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/phys/units/UnitList.py
--rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/phys/units/__init__.py
--rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/stats/StopwatchClass.py
--rw-r--r--   0        0        0       38 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/stats/__init__.py
--rw-r--r--   0        0        0     5397 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/structs/CollectorClass.py
--rw-r--r--   0        0        0     2488 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/structs/ParameterClass.py
--rw-r--r--   0        0        0      169 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/structs/__init__.py
--rw-r--r--   0        0        0     3081 2020-02-02 00:00:00.000000 scinumtools-1.5.2/.gitignore
--rw-r--r--   0        0        0       59 2020-02-02 00:00:00.000000 scinumtools-1.5.2/README.md
--rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 scinumtools-1.5.2/pyproject.toml
--rw-r--r--   0        0        0      605 2020-02-02 00:00:00.000000 scinumtools-1.5.2/PKG-INFO
+-rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.3/requirements.txt
+-rw-r--r--   0        0        0      343 2020-02-02 00:00:00.000000 scinumtools-1.5.3/.github/workflows/pytest.yml
+-rw-r--r--   0        0        0     1084 2020-02-02 00:00:00.000000 scinumtools-1.5.3/.github/workflows/python-publish.yml
+-rw-r--r--   0        0        0      100 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/__init__.py
+-rw-r--r--   0        0        0      530 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/data/CachingClass.py
+-rw-r--r--   0        0        0     1786 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/data/ImageClass.py
+-rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/data/PlottingClass.py
+-rw-r--r--   0        0        0      145 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/data/__init__.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/math/__init__.py
+-rw-r--r--   0        0        0     1969 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/math/solver/AtomClass.py
+-rw-r--r--   0        0        0      574 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/math/solver/ExpressionClass.py
+-rw-r--r--   0        0        0     7525 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/math/solver/OperatorClass.py
+-rw-r--r--   0        0        0     3803 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/math/solver/SolverClass.py
+-rw-r--r--   0        0        0     1210 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/math/solver/TokensClass.py
+-rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/math/solver/__init__.py
+-rw-r--r--   0        0        0     2455 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/phys/ConstantsClass.py
+-rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/phys/__init__.py
+-rw-r--r--   0        0        0     2535 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/phys/units/BaseUnitsClass.py
+-rw-r--r--   0        0        0     3283 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/phys/units/DimensionsClass.py
+-rw-r--r--   0        0        0    11029 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/phys/units/QuantityClass.py
+-rw-r--r--   0        0        0     3067 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/phys/units/RatioClass.py
+-rw-r--r--   0        0        0      555 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/phys/units/UnitClass.py
+-rw-r--r--   0        0        0     2538 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/phys/units/UnitConverters.py
+-rw-r--r--   0        0        0    10710 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/phys/units/UnitList.py
+-rw-r--r--   0        0        0      182 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/phys/units/__init__.py
+-rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/stats/StopwatchClass.py
+-rw-r--r--   0        0        0       38 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/stats/__init__.py
+-rw-r--r--   0        0        0     5509 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/structs/CollectorClass.py
+-rw-r--r--   0        0        0     2488 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/structs/ParameterClass.py
+-rw-r--r--   0        0        0      169 2020-02-02 00:00:00.000000 scinumtools-1.5.3/src/scinumtools/structs/__init__.py
+-rw-r--r--   0        0        0       59 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/README.md
+-rw-r--r--   0        0        0     1218 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/cached_data.npy
+-rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/pyproject.toml
+-rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/requirements.txt
+-rw-r--r--   0        0        0     6537 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/test_data.py
+-rw-r--r--   0        0        0     4225 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/test_math.py
+-rw-r--r--   0        0        0      207 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/test_physics.py
+-rw-r--r--   0        0        0      941 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/test_stats.py
+-rw-r--r--   0        0        0     4184 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/test_struct.py
+-rw-r--r--   0        0        0     8930 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/test_units.py
+-rw-r--r--   0        0        0      100 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/__init__.py
+-rw-r--r--   0        0        0      473 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/data/CachingClass.py
+-rw-r--r--   0        0        0     1786 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/data/ImageClass.py
+-rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/data/PlottingClass.py
+-rw-r--r--   0        0        0      145 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/data/__init__.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/math/__init__.py
+-rw-r--r--   0        0        0     1969 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/math/solver/AtomClass.py
+-rw-r--r--   0        0        0      574 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/math/solver/ExpressionClass.py
+-rw-r--r--   0        0        0     7525 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/math/solver/OperatorClass.py
+-rw-r--r--   0        0        0     3803 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/math/solver/SolverClass.py
+-rw-r--r--   0        0        0     1210 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/math/solver/TokensClass.py
+-rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/math/solver/__init__.py
+-rw-r--r--   0        0        0     2455 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/phys/ConstantsClass.py
+-rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/phys/__init__.py
+-rw-r--r--   0        0        0     9181 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/phys/units/QuantityClass.py
+-rw-r--r--   0        0        0     2153 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/phys/units/UnitConverters.py
+-rw-r--r--   0        0        0    10140 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/phys/units/UnitList.py
+-rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/phys/units/__init__.py
+-rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/stats/StopwatchClass.py
+-rw-r--r--   0        0        0       38 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/stats/__init__.py
+-rw-r--r--   0        0        0     5397 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/structs/CollectorClass.py
+-rw-r--r--   0        0        0     2488 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/structs/ParameterClass.py
+-rw-r--r--   0        0        0      169 2020-02-02 00:00:00.000000 scinumtools-1.5.3/tests/src/scinumtools/structs/__init__.py
+-rw-r--r--   0        0        0     3081 2020-02-02 00:00:00.000000 scinumtools-1.5.3/.gitignore
+-rw-r--r--   0        0        0       59 2020-02-02 00:00:00.000000 scinumtools-1.5.3/README.md
+-rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 scinumtools-1.5.3/pyproject.toml
+-rw-r--r--   0        0        0      605 2020-02-02 00:00:00.000000 scinumtools-1.5.3/PKG-INFO
```

### Comparing `scinumtools-1.5.2/.github/workflows/python-publish.yml` & `scinumtools-1.5.3/.github/workflows/python-publish.yml`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/data/CachingClass.py` & `scinumtools-1.5.3/src/scinumtools/data/CachingClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/data/ImageClass.py` & `scinumtools-1.5.3/src/scinumtools/data/ImageClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/data/PlottingClass.py` & `scinumtools-1.5.3/src/scinumtools/data/PlottingClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/math/solver/AtomClass.py` & `scinumtools-1.5.3/src/scinumtools/math/solver/AtomClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/math/solver/ExpressionClass.py` & `scinumtools-1.5.3/src/scinumtools/math/solver/ExpressionClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/math/solver/OperatorClass.py` & `scinumtools-1.5.3/src/scinumtools/math/solver/OperatorClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/math/solver/SolverClass.py` & `scinumtools-1.5.3/src/scinumtools/math/solver/SolverClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/math/solver/TokensClass.py` & `scinumtools-1.5.3/src/scinumtools/math/solver/TokensClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/phys/ConstantsClass.py` & `scinumtools-1.5.3/src/scinumtools/phys/ConstantsClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/phys/units/BaseUnitsClass.py` & `scinumtools-1.5.3/src/scinumtools/phys/units/BaseUnitsClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/phys/units/DimensionsClass.py` & `scinumtools-1.5.3/src/scinumtools/phys/units/DimensionsClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/phys/units/QuantityClass.py` & `scinumtools-1.5.3/src/scinumtools/phys/units/QuantityClass.py`

 * *Files 2% similar despite different names*

```diff
@@ -263,26 +263,23 @@
             return unit.magnitude
         else:
             return self.magnitude
 
     def units(self):
         return self.baseunits.expression()
 
-    def to(self, units):
-        if isinstance(units,str):
-            unit1 = self
-            unit2 = Quantity(1,units)
-            # Check if units can be directly converted
-            if not unit1.dimensions==unit2.dimensions:
-                # Check if inverted unit can be converted
-                if -unit1.dimensions==unit2.dimensions:
-                    unit1 = Quantity(1)/self
-                else:
-                    raise Exception("Converting units with different dimensions:",
-                                    unit1.dimensions, unit2.dimensions)
-            with TemperatureConverter(unit1.baseunits.value(), unit2.baseunits.value()) as tc:
-                if tc.convertable:
-                    unit2.magnitude = unit1.magnitude/tc.convert(unit1.magnitude, unit2.magnitude)
-            unit = unit1/unit2
-            return Quantity(unit.magnitude, units)
-        else:
-            raise Exception("Invalid units format:", units)
+    def to(self, units: Union[str,list,np.ndarray,Dimensions,dict,BaseUnits]):
+        unit1 = self
+        unit2 = Quantity(1,units)
+        # Check if units can be directly converted
+        if not unit1.dimensions==unit2.dimensions:
+            # Check if inverted unit can be converted
+            if -unit1.dimensions==unit2.dimensions:
+                unit1 = Quantity(1)/self
+            else:
+                raise Exception("Converting units with different dimensions:",
+                                unit1.dimensions, unit2.dimensions)
+        with TemperatureConverter(unit1.baseunits.value(), unit2.baseunits.value()) as tc:
+            if tc.convertable:
+                unit2.magnitude = unit1.magnitude/tc.convert(unit1.magnitude, unit2.magnitude)
+        unit = unit1/unit2
+        return Quantity(unit.magnitude, units)
```

### Comparing `scinumtools-1.5.2/src/scinumtools/phys/units/RatioClass.py` & `scinumtools-1.5.3/src/scinumtools/phys/units/RatioClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/phys/units/UnitClass.py` & `scinumtools-1.5.3/src/scinumtools/phys/units/UnitClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/phys/units/UnitConverters.py` & `scinumtools-1.5.3/src/scinumtools/phys/units/UnitConverters.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/phys/units/UnitList.py` & `scinumtools-1.5.3/src/scinumtools/phys/units/UnitList.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/stats/StopwatchClass.py` & `scinumtools-1.5.3/src/scinumtools/stats/StopwatchClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/structs/CollectorClass.py` & `scinumtools-1.5.3/src/scinumtools/structs/CollectorClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/src/scinumtools/structs/ParameterClass.py` & `scinumtools-1.5.3/src/scinumtools/structs/ParameterClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/cached_data.npy` & `scinumtools-1.5.3/tests/cached_data.npy`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/pyproject.toml` & `scinumtools-1.5.3/tests/pyproject.toml`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/test_data.py` & `scinumtools-1.5.3/tests/test_data.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/test_math.py` & `scinumtools-1.5.3/tests/test_math.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/test_stats.py` & `scinumtools-1.5.3/tests/test_stats.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/test_struct.py` & `scinumtools-1.5.3/tests/test_struct.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/test_units.py` & `scinumtools-1.5.3/tests/test_units.py`

 * *Files 5% similar despite different names*

```diff
@@ -101,37 +101,14 @@
     for symbol, unit in prefixes.items():
         if not isinstance(unit['definition'],str):
             continue
         q = Quantity(1, unit['definition'])
         assert isclose(q.magnitude,  unit['magnitude'], rel_tol=1e-07)
         assert q.dimensions.value() == unit['dimensions']
         
-def test_temperatures():
-    
-    # Temperature conversions
-    assert str(Quantity(23,'K').to('Cel'))        == "Quantity(-2.501e+02 Cel)"
-    assert str(Quantity(23,'K').to('degF'))       == "Quantity(-4.183e+02 degF)"
-    assert str(Quantity(23,'K').to('degR'))       == "Quantity(4.140e+01 degR)"
-    assert str(Quantity(23,'Cel').to('K'))        == "Quantity(2.961e+02 K)"
-    assert str(Quantity(23,'Cel').to('degF'))     == "Quantity(7.340e+01 degF)"
-    assert str(Quantity(23,'Cel').to('degR'))     == "Quantity(5.331e+02 degR)"
-    assert str(Quantity(23,'degF').to('K'))       == "Quantity(2.681e+02 K)"
-    assert str(Quantity(23,'degF').to('Cel'))     == "Quantity(-5.000e+00 Cel)"
-    assert str(Quantity(23,'degF').to('degR'))    == "Quantity(4.827e+02 degR)"
-    assert str(Quantity(23,'degR').to('K'))       == "Quantity(1.278e+01 K)"
-    assert str(Quantity(23,'degR').to('Cel'))     == "Quantity(-2.604e+02 Cel)"
-    assert str(Quantity(23,'degR').to('degF'))    == "Quantity(-4.367e+02 degF)"
-    assert str(Quantity(2300,'Cel').to('kK'))     == "Quantity(2.573e+00 kK)"
-    
-def test_inversion():
-
-    assert str(Quantity(23, 'Hz').to('s'))     == "Quantity(4.348e-02 s)"
-    assert str(Quantity(34, 'Ohm').to('S'))    == "Quantity(2.941e-02 S)"
-    assert str(Quantity(102, 'J').to('erg-1')) == "Quantity(9.804e-10 erg-1)"
-
 def test_scalar_arithmetics():
 
     q = Quantity(123e2, [3,3,0,0,1,0,0,0])
     assert str(q) == "Quantity(1.230e+04 m3*g3*C)"    
     q /= Quantity(123, 'C')
     assert str(q) == "Quantity(1.000e+02 m3*g3)"
     q *= Quantity(2, 's2')
@@ -155,14 +132,23 @@
     
     with pytest.raises(Exception) as excinfo:
         q = q.to("kg3*s/cm3")
     assert excinfo.value.args[0]=="Converting units with different dimensions:"
     assert excinfo.value.args[1].value()==[0, 0, 0, 0, 0, 0, 0, 0]
     assert excinfo.value.args[2].value()==[-3, 3, 1, 0, 0, 0, 0, 0]
 
+    # test unit conversion on scalars
+    result = "Quantity(3.000e+03 m)"
+    assert str(Quantity(3, 'km').to('m'))                 == result
+    assert str(Quantity(3, 'km').to([1,0,0,0,0,0,0,0]))   == result
+    assert str(Quantity(3, 'km').to(Dimensions(m=1)))     == result
+    assert str(Quantity(3, 'km').to({'m':1}))             == result
+    assert str(Quantity(3, 'km').to(BaseUnits({'m':1})))  == result
+    assert str(Quantity(3, 'km').to(Unit().m))            == result
+    
 def test_array_arithmetics():
 
     # Test basic arithmetics
     q = Quantity([2,3,4], 'm')
     assert str(q) == "Quantity([2. 3. 4.] m)"
     q += Quantity(2, 'm')
     assert str(q) == "Quantity([4. 5. 6.] m)"
@@ -213,7 +199,30 @@
     for unit in UnitStandard.keys():
         for prefix in UnitPrefixes.keys():
             units.append(f"{prefix}{unit}")
     units.sort()
     seen = set()
     dupes = [x for x in units if x in seen or seen.add(x)]    
     assert len(dupes)==0
+
+def test_temperatures():
+    
+    # Temperature conversions
+    assert str(Quantity(23,'K').to('Cel'))        == "Quantity(-2.501e+02 Cel)"
+    assert str(Quantity(23,'K').to('degF'))       == "Quantity(-4.183e+02 degF)"
+    assert str(Quantity(23,'K').to('degR'))       == "Quantity(4.140e+01 degR)"
+    assert str(Quantity(23,'Cel').to('K'))        == "Quantity(2.961e+02 K)"
+    assert str(Quantity(23,'Cel').to('degF'))     == "Quantity(7.340e+01 degF)"
+    assert str(Quantity(23,'Cel').to('degR'))     == "Quantity(5.331e+02 degR)"
+    assert str(Quantity(23,'degF').to('K'))       == "Quantity(2.681e+02 K)"
+    assert str(Quantity(23,'degF').to('Cel'))     == "Quantity(-5.000e+00 Cel)"
+    assert str(Quantity(23,'degF').to('degR'))    == "Quantity(4.827e+02 degR)"
+    assert str(Quantity(23,'degR').to('K'))       == "Quantity(1.278e+01 K)"
+    assert str(Quantity(23,'degR').to('Cel'))     == "Quantity(-2.604e+02 Cel)"
+    assert str(Quantity(23,'degR').to('degF'))    == "Quantity(-4.367e+02 degF)"
+    assert str(Quantity(2300,'Cel').to('kK'))     == "Quantity(2.573e+00 kK)"
+    
+def test_inversion():
+
+    assert str(Quantity(23, 'Hz').to('s'))     == "Quantity(4.348e-02 s)"
+    assert str(Quantity(34, 'Ohm').to('S'))    == "Quantity(2.941e-02 S)"
+    assert str(Quantity(102, 'J').to('erg-1')) == "Quantity(9.804e-10 erg-1)"
```

### Comparing `scinumtools-1.5.2/tests/src/scinumtools/data/ImageClass.py` & `scinumtools-1.5.3/tests/src/scinumtools/data/ImageClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/src/scinumtools/data/PlottingClass.py` & `scinumtools-1.5.3/tests/src/scinumtools/data/PlottingClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/src/scinumtools/math/solver/AtomClass.py` & `scinumtools-1.5.3/tests/src/scinumtools/math/solver/AtomClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/src/scinumtools/math/solver/ExpressionClass.py` & `scinumtools-1.5.3/tests/src/scinumtools/math/solver/ExpressionClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/src/scinumtools/math/solver/OperatorClass.py` & `scinumtools-1.5.3/tests/src/scinumtools/math/solver/OperatorClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/src/scinumtools/math/solver/SolverClass.py` & `scinumtools-1.5.3/tests/src/scinumtools/math/solver/SolverClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/src/scinumtools/math/solver/TokensClass.py` & `scinumtools-1.5.3/tests/src/scinumtools/math/solver/TokensClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/src/scinumtools/phys/ConstantsClass.py` & `scinumtools-1.5.3/tests/src/scinumtools/phys/ConstantsClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/src/scinumtools/phys/units/QuantityClass.py` & `scinumtools-1.5.3/tests/src/scinumtools/phys/units/QuantityClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/src/scinumtools/phys/units/UnitConverters.py` & `scinumtools-1.5.3/tests/src/scinumtools/phys/units/UnitConverters.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/src/scinumtools/phys/units/UnitList.py` & `scinumtools-1.5.3/tests/src/scinumtools/phys/units/UnitList.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/src/scinumtools/stats/StopwatchClass.py` & `scinumtools-1.5.3/tests/src/scinumtools/stats/StopwatchClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/src/scinumtools/structs/CollectorClass.py` & `scinumtools-1.5.3/tests/src/scinumtools/structs/CollectorClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/tests/src/scinumtools/structs/ParameterClass.py` & `scinumtools-1.5.3/tests/src/scinumtools/structs/ParameterClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/.gitignore` & `scinumtools-1.5.3/.gitignore`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.2/pyproject.toml` & `scinumtools-1.5.3/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["hatchling"]
 build-backend = "hatchling.build"
 
 [project]
 name = "scinumtools"
-version = "1.5.2"
+version = "1.5.3"
 authors = [
   { name="Ondrej Pego Jaura", email="vrtulka23@pm.me" },
 ]
 description = "Set of most frequently used tools for a rapid numerical code development in Python."
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `scinumtools-1.5.2/PKG-INFO` & `scinumtools-1.5.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: scinumtools
-Version: 1.5.2
+Version: 1.5.3
 Summary: Set of most frequently used tools for a rapid numerical code development in Python.
 Project-URL: Homepage, https://github.com/vrtulka23/scinumtools
 Project-URL: Bug Tracker, https://github.com/vrtulka23/scinumtools/issues
 Author-email: Ondrej Pego Jaura <vrtulka23@pm.me>
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
```


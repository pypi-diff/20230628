# Comparing `tmp/scinumtools-1.5.1.tar.gz` & `tmp/scinumtools-1.5.2.tar.gz`

## Comparing `scinumtools-1.5.1.tar` & `scinumtools-1.5.2.tar`

### file list

```diff
@@ -1,67 +1,67 @@
--rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.1/requirements.txt
--rw-r--r--   0        0        0      343 2020-02-02 00:00:00.000000 scinumtools-1.5.1/.github/workflows/pytest.yml
--rw-r--r--   0        0        0     1084 2020-02-02 00:00:00.000000 scinumtools-1.5.1/.github/workflows/python-publish.yml
--rw-r--r--   0        0        0      100 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/__init__.py
--rw-r--r--   0        0        0      530 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/data/CachingClass.py
--rw-r--r--   0        0        0     1786 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/data/ImageClass.py
--rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/data/PlottingClass.py
--rw-r--r--   0        0        0      145 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/data/__init__.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/math/__init__.py
--rw-r--r--   0        0        0     1969 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/math/solver/AtomClass.py
--rw-r--r--   0        0        0      574 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/math/solver/ExpressionClass.py
--rw-r--r--   0        0        0     7525 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/math/solver/OperatorClass.py
--rw-r--r--   0        0        0     3803 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/math/solver/SolverClass.py
--rw-r--r--   0        0        0     1210 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/math/solver/TokensClass.py
--rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/math/solver/__init__.py
--rw-r--r--   0        0        0     2455 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/phys/ConstantsClass.py
--rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/phys/__init__.py
--rw-r--r--   0        0        0     2535 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/phys/units/BaseUnitsClass.py
--rw-r--r--   0        0        0     3283 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/phys/units/DimensionsClass.py
--rw-r--r--   0        0        0    10848 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/phys/units/QuantityClass.py
--rw-r--r--   0        0        0     3067 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/phys/units/RatioClass.py
--rw-r--r--   0        0        0      555 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/phys/units/UnitClass.py
--rw-r--r--   0        0        0     2538 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/phys/units/UnitConverters.py
--rw-r--r--   0        0        0    10710 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/phys/units/UnitList.py
--rw-r--r--   0        0        0      182 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/phys/units/__init__.py
--rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/stats/StopwatchClass.py
--rw-r--r--   0        0        0       38 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/stats/__init__.py
--rw-r--r--   0        0        0     5509 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/structs/CollectorClass.py
--rw-r--r--   0        0        0     2488 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/structs/ParameterClass.py
--rw-r--r--   0        0        0      169 2020-02-02 00:00:00.000000 scinumtools-1.5.1/src/scinumtools/structs/__init__.py
--rw-r--r--   0        0        0       59 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/README.md
--rw-r--r--   0        0        0     1218 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/cached_data.npy
--rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/pyproject.toml
--rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/requirements.txt
--rw-r--r--   0        0        0     6537 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/test_data.py
--rw-r--r--   0        0        0     4225 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/test_math.py
--rw-r--r--   0        0        0      207 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/test_physics.py
--rw-r--r--   0        0        0      941 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/test_stats.py
--rw-r--r--   0        0        0     4184 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/test_struct.py
--rw-r--r--   0        0        0     8289 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/test_units.py
--rw-r--r--   0        0        0      100 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/__init__.py
--rw-r--r--   0        0        0      473 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/data/CachingClass.py
--rw-r--r--   0        0        0     1786 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/data/ImageClass.py
--rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/data/PlottingClass.py
--rw-r--r--   0        0        0      145 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/data/__init__.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/math/__init__.py
--rw-r--r--   0        0        0     1969 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/math/solver/AtomClass.py
--rw-r--r--   0        0        0      574 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/math/solver/ExpressionClass.py
--rw-r--r--   0        0        0     7525 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/math/solver/OperatorClass.py
--rw-r--r--   0        0        0     3803 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/math/solver/SolverClass.py
--rw-r--r--   0        0        0     1210 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/math/solver/TokensClass.py
--rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/math/solver/__init__.py
--rw-r--r--   0        0        0     2455 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/phys/ConstantsClass.py
--rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/phys/__init__.py
--rw-r--r--   0        0        0     9181 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/phys/units/QuantityClass.py
--rw-r--r--   0        0        0     2153 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/phys/units/UnitConverters.py
--rw-r--r--   0        0        0    10140 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/phys/units/UnitList.py
--rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/phys/units/__init__.py
--rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/stats/StopwatchClass.py
--rw-r--r--   0        0        0       38 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/stats/__init__.py
--rw-r--r--   0        0        0     5397 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/structs/CollectorClass.py
--rw-r--r--   0        0        0     2488 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/structs/ParameterClass.py
--rw-r--r--   0        0        0      169 2020-02-02 00:00:00.000000 scinumtools-1.5.1/tests/src/scinumtools/structs/__init__.py
--rw-r--r--   0        0        0     3081 2020-02-02 00:00:00.000000 scinumtools-1.5.1/.gitignore
--rw-r--r--   0        0        0       59 2020-02-02 00:00:00.000000 scinumtools-1.5.1/README.md
--rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 scinumtools-1.5.1/pyproject.toml
--rw-r--r--   0        0        0      605 2020-02-02 00:00:00.000000 scinumtools-1.5.1/PKG-INFO
+-rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.2/requirements.txt
+-rw-r--r--   0        0        0      343 2020-02-02 00:00:00.000000 scinumtools-1.5.2/.github/workflows/pytest.yml
+-rw-r--r--   0        0        0     1084 2020-02-02 00:00:00.000000 scinumtools-1.5.2/.github/workflows/python-publish.yml
+-rw-r--r--   0        0        0      100 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/__init__.py
+-rw-r--r--   0        0        0      530 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/data/CachingClass.py
+-rw-r--r--   0        0        0     1786 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/data/ImageClass.py
+-rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/data/PlottingClass.py
+-rw-r--r--   0        0        0      145 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/data/__init__.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/math/__init__.py
+-rw-r--r--   0        0        0     1969 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/math/solver/AtomClass.py
+-rw-r--r--   0        0        0      574 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/math/solver/ExpressionClass.py
+-rw-r--r--   0        0        0     7525 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/math/solver/OperatorClass.py
+-rw-r--r--   0        0        0     3803 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/math/solver/SolverClass.py
+-rw-r--r--   0        0        0     1210 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/math/solver/TokensClass.py
+-rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/math/solver/__init__.py
+-rw-r--r--   0        0        0     2455 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/ConstantsClass.py
+-rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/__init__.py
+-rw-r--r--   0        0        0     2535 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/BaseUnitsClass.py
+-rw-r--r--   0        0        0     3283 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/DimensionsClass.py
+-rw-r--r--   0        0        0    11143 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/QuantityClass.py
+-rw-r--r--   0        0        0     3067 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/RatioClass.py
+-rw-r--r--   0        0        0      555 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/UnitClass.py
+-rw-r--r--   0        0        0     2538 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/UnitConverters.py
+-rw-r--r--   0        0        0    10710 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/UnitList.py
+-rw-r--r--   0        0        0      182 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/phys/units/__init__.py
+-rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/stats/StopwatchClass.py
+-rw-r--r--   0        0        0       38 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/stats/__init__.py
+-rw-r--r--   0        0        0     5509 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/structs/CollectorClass.py
+-rw-r--r--   0        0        0     2488 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/structs/ParameterClass.py
+-rw-r--r--   0        0        0      169 2020-02-02 00:00:00.000000 scinumtools-1.5.2/src/scinumtools/structs/__init__.py
+-rw-r--r--   0        0        0       59 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/README.md
+-rw-r--r--   0        0        0     1218 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/cached_data.npy
+-rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/pyproject.toml
+-rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/requirements.txt
+-rw-r--r--   0        0        0     6537 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/test_data.py
+-rw-r--r--   0        0        0     4225 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/test_math.py
+-rw-r--r--   0        0        0      207 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/test_physics.py
+-rw-r--r--   0        0        0      941 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/test_stats.py
+-rw-r--r--   0        0        0     4184 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/test_struct.py
+-rw-r--r--   0        0        0     8442 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/test_units.py
+-rw-r--r--   0        0        0      100 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/__init__.py
+-rw-r--r--   0        0        0      473 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/data/CachingClass.py
+-rw-r--r--   0        0        0     1786 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/data/ImageClass.py
+-rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/data/PlottingClass.py
+-rw-r--r--   0        0        0      145 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/data/__init__.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/math/__init__.py
+-rw-r--r--   0        0        0     1969 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/math/solver/AtomClass.py
+-rw-r--r--   0        0        0      574 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/math/solver/ExpressionClass.py
+-rw-r--r--   0        0        0     7525 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/math/solver/OperatorClass.py
+-rw-r--r--   0        0        0     3803 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/math/solver/SolverClass.py
+-rw-r--r--   0        0        0     1210 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/math/solver/TokensClass.py
+-rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/math/solver/__init__.py
+-rw-r--r--   0        0        0     2455 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/phys/ConstantsClass.py
+-rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/phys/__init__.py
+-rw-r--r--   0        0        0     9181 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/phys/units/QuantityClass.py
+-rw-r--r--   0        0        0     2153 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/phys/units/UnitConverters.py
+-rw-r--r--   0        0        0    10140 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/phys/units/UnitList.py
+-rw-r--r--   0        0        0       36 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/phys/units/__init__.py
+-rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/stats/StopwatchClass.py
+-rw-r--r--   0        0        0       38 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/stats/__init__.py
+-rw-r--r--   0        0        0     5397 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/structs/CollectorClass.py
+-rw-r--r--   0        0        0     2488 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/structs/ParameterClass.py
+-rw-r--r--   0        0        0      169 2020-02-02 00:00:00.000000 scinumtools-1.5.2/tests/src/scinumtools/structs/__init__.py
+-rw-r--r--   0        0        0     3081 2020-02-02 00:00:00.000000 scinumtools-1.5.2/.gitignore
+-rw-r--r--   0        0        0       59 2020-02-02 00:00:00.000000 scinumtools-1.5.2/README.md
+-rw-r--r--   0        0        0      629 2020-02-02 00:00:00.000000 scinumtools-1.5.2/pyproject.toml
+-rw-r--r--   0        0        0      605 2020-02-02 00:00:00.000000 scinumtools-1.5.2/PKG-INFO
```

### Comparing `scinumtools-1.5.1/.github/workflows/python-publish.yml` & `scinumtools-1.5.2/.github/workflows/python-publish.yml`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/data/CachingClass.py` & `scinumtools-1.5.2/src/scinumtools/data/CachingClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/data/ImageClass.py` & `scinumtools-1.5.2/src/scinumtools/data/ImageClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/data/PlottingClass.py` & `scinumtools-1.5.2/src/scinumtools/data/PlottingClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/math/solver/AtomClass.py` & `scinumtools-1.5.2/src/scinumtools/math/solver/AtomClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/math/solver/ExpressionClass.py` & `scinumtools-1.5.2/src/scinumtools/math/solver/ExpressionClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/math/solver/OperatorClass.py` & `scinumtools-1.5.2/src/scinumtools/math/solver/OperatorClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/math/solver/SolverClass.py` & `scinumtools-1.5.2/src/scinumtools/math/solver/SolverClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/math/solver/TokensClass.py` & `scinumtools-1.5.2/src/scinumtools/math/solver/TokensClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/phys/ConstantsClass.py` & `scinumtools-1.5.2/src/scinumtools/phys/ConstantsClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/phys/units/BaseUnitsClass.py` & `scinumtools-1.5.2/src/scinumtools/phys/units/BaseUnitsClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/phys/units/DimensionsClass.py` & `scinumtools-1.5.2/src/scinumtools/phys/units/DimensionsClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/phys/units/QuantityClass.py` & `scinumtools-1.5.2/src/scinumtools/phys/units/QuantityClass.py`

 * *Files 1% similar despite different names*

```diff
@@ -47,14 +47,18 @@
             elif isinstance(dimensions, BaseUnits):
                 dimensions = dimensions.expression()
             with ExpressionSolver(self._atom_parser, [OperatorPar,OperatorMul,OperatorTruediv]) as es:
                 unit = es.solve(dimensions)
             self.magnitude *= unit.magnitude
             self.dimensions = unit.dimensions
             self.baseunits = unit.baseunits
+        elif isinstance(dimensions, Quantity):
+            self.magnitude *= dimensions.magnitude
+            self.dimensions = dimensions.dimensions
+            self.baseunits = dimensions.baseunits
         elif isinstance(dimensions, (list, np.ndarray, Dimensions)):
             if isinstance(dimensions, Dimensions):
                 self.dimensions = dimensions
             else:
                 self.dimensions = Dimensions(*dimensions)
             if isinstance(baseunits, dict):
                 self.baseunits = BaseUnits(baseunits)
@@ -217,14 +221,16 @@
             nbase = len(base)+1
             ukeys = [key[-nbase:] for key in unitkeys]
             if symbol+base not in ukeys:
                 break
             base = symbol+base
             symbol, string = string[-1], string[:-1]
         unitid = f"{base:s}"
+        if base not in self.unitlist.keys():
+            raise Exception('Unknown unit', base)
         magnitude = self.unitlist[base].magnitude
         dimensions = self.unitlist[base].dimensions
         # parse unit prefix
         while len(string):
             prefix = symbol+prefix
             symbol, string = string[-1], string[:-1]
             if symbol==' ':
```

### Comparing `scinumtools-1.5.1/src/scinumtools/phys/units/RatioClass.py` & `scinumtools-1.5.2/src/scinumtools/phys/units/RatioClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/phys/units/UnitClass.py` & `scinumtools-1.5.2/src/scinumtools/phys/units/UnitClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/phys/units/UnitConverters.py` & `scinumtools-1.5.2/src/scinumtools/phys/units/UnitConverters.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/phys/units/UnitList.py` & `scinumtools-1.5.2/src/scinumtools/phys/units/UnitList.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/stats/StopwatchClass.py` & `scinumtools-1.5.2/src/scinumtools/stats/StopwatchClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/structs/CollectorClass.py` & `scinumtools-1.5.2/src/scinumtools/structs/CollectorClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/src/scinumtools/structs/ParameterClass.py` & `scinumtools-1.5.2/src/scinumtools/structs/ParameterClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/cached_data.npy` & `scinumtools-1.5.2/tests/cached_data.npy`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/pyproject.toml` & `scinumtools-1.5.2/tests/pyproject.toml`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/test_data.py` & `scinumtools-1.5.2/tests/test_data.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/test_math.py` & `scinumtools-1.5.2/tests/test_math.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/test_stats.py` & `scinumtools-1.5.2/tests/test_stats.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/test_struct.py` & `scinumtools-1.5.2/tests/test_struct.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/test_units.py` & `scinumtools-1.5.2/tests/test_units.py`

 * *Files 2% similar despite different names*

```diff
@@ -16,14 +16,18 @@
     result = "Quantity(1.230e+04 m*s2:3)"
     assert str(Quantity(123e2, [1,0,(2,3),0,0,0,0,0] ))    == result
     assert str(Quantity(123e2, Dimensions(m=1, s=(2,3)) )) == result
 
     result = "Quantity(1.230e+04 J2*kg2:3)"
     assert str(Quantity(123e2, {'J': 2, 'kg':(2,3)} )) == result
     assert str(Quantity(123e2, BaseUnits({'J': 2, 'kg':(2,3)}) )) == result
+
+    result = "Quantity(2.460e+04 m)"
+    assert str(Quantity(123e2, Quantity(2, 'm'))) == result
+    assert str(Quantity(123e2, 2*Unit('m'))) == result
     
 def test_units():
 
     assert str(Unit('m'))         == "Quantity(1.000e+00 m)"
     assert str(Unit('kg*m2*s-2')) == "Quantity(1.000e+00 kg*m2*s-2)"
     
     unit = Unit()
```

### Comparing `scinumtools-1.5.1/tests/src/scinumtools/data/ImageClass.py` & `scinumtools-1.5.2/tests/src/scinumtools/data/ImageClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/src/scinumtools/data/PlottingClass.py` & `scinumtools-1.5.2/tests/src/scinumtools/data/PlottingClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/src/scinumtools/math/solver/AtomClass.py` & `scinumtools-1.5.2/tests/src/scinumtools/math/solver/AtomClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/src/scinumtools/math/solver/ExpressionClass.py` & `scinumtools-1.5.2/tests/src/scinumtools/math/solver/ExpressionClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/src/scinumtools/math/solver/OperatorClass.py` & `scinumtools-1.5.2/tests/src/scinumtools/math/solver/OperatorClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/src/scinumtools/math/solver/SolverClass.py` & `scinumtools-1.5.2/tests/src/scinumtools/math/solver/SolverClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/src/scinumtools/math/solver/TokensClass.py` & `scinumtools-1.5.2/tests/src/scinumtools/math/solver/TokensClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/src/scinumtools/phys/ConstantsClass.py` & `scinumtools-1.5.2/tests/src/scinumtools/phys/ConstantsClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/src/scinumtools/phys/units/QuantityClass.py` & `scinumtools-1.5.2/tests/src/scinumtools/phys/units/QuantityClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/src/scinumtools/phys/units/UnitConverters.py` & `scinumtools-1.5.2/tests/src/scinumtools/phys/units/UnitConverters.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/src/scinumtools/phys/units/UnitList.py` & `scinumtools-1.5.2/tests/src/scinumtools/phys/units/UnitList.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/src/scinumtools/stats/StopwatchClass.py` & `scinumtools-1.5.2/tests/src/scinumtools/stats/StopwatchClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/src/scinumtools/structs/CollectorClass.py` & `scinumtools-1.5.2/tests/src/scinumtools/structs/CollectorClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/tests/src/scinumtools/structs/ParameterClass.py` & `scinumtools-1.5.2/tests/src/scinumtools/structs/ParameterClass.py`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/.gitignore` & `scinumtools-1.5.2/.gitignore`

 * *Files identical despite different names*

### Comparing `scinumtools-1.5.1/pyproject.toml` & `scinumtools-1.5.2/pyproject.toml`

 * *Files 20% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["hatchling"]
 build-backend = "hatchling.build"
 
 [project]
 name = "scinumtools"
-version = "1.5.1"
+version = "1.5.2"
 authors = [
   { name="Ondrej Pego Jaura", email="vrtulka23@pm.me" },
 ]
 description = "Set of most frequently used tools for a rapid numerical code development in Python."
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `scinumtools-1.5.1/PKG-INFO` & `scinumtools-1.5.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: scinumtools
-Version: 1.5.1
+Version: 1.5.2
 Summary: Set of most frequently used tools for a rapid numerical code development in Python.
 Project-URL: Homepage, https://github.com/vrtulka23/scinumtools
 Project-URL: Bug Tracker, https://github.com/vrtulka23/scinumtools/issues
 Author-email: Ondrej Pego Jaura <vrtulka23@pm.me>
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
```


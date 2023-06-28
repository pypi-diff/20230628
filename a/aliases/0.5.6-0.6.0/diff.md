# Comparing `tmp/aliases-0.5.6.tar.gz` & `tmp/aliases-0.6.0.tar.gz`

## Comparing `aliases-0.5.6.tar` & `aliases-0.6.0.tar`

### file list

```diff
@@ -1,11 +1,31 @@
--rw-r--r--   0        0        0     1117 2020-02-02 00:00:00.000000 aliases-0.5.6/.github/workflows/python-publish.yml
--rw-r--r--   0        0        0      291 2020-02-02 00:00:00.000000 aliases-0.5.6/src/aliases/__init__.py
--rw-r--r--   0        0        0      973 2020-02-02 00:00:00.000000 aliases-0.5.6/src/aliases/dict.py
--rw-r--r--   0        0        0     1919 2020-02-02 00:00:00.000000 aliases-0.5.6/src/aliases/pandas_accessor.py
--rw-r--r--   0        0        0     3764 2020-02-02 00:00:00.000000 aliases-0.5.6/src/aliases/space.py
--rw-r--r--   0        0        0      640 2020-02-02 00:00:00.000000 aliases-0.5.6/src/aliases/string.py
--rw-r--r--   0        0        0     1799 2020-02-02 00:00:00.000000 aliases-0.5.6/.gitignore
--rw-r--r--   0        0        0     1065 2020-02-02 00:00:00.000000 aliases-0.5.6/LICENSE
--rw-r--r--   0        0        0     3143 2020-02-02 00:00:00.000000 aliases-0.5.6/README.rst
--rw-r--r--   0        0        0      970 2020-02-02 00:00:00.000000 aliases-0.5.6/pyproject.toml
--rw-r--r--   0        0        0     3986 2020-02-02 00:00:00.000000 aliases-0.5.6/PKG-INFO
+-rw-r--r--   0        0        0      171 2020-02-02 00:00:00.000000 aliases-0.6.0/.readthedocs.yml
+-rw-r--r--   0        0        0      117 2020-02-02 00:00:00.000000 aliases-0.6.0/requirements-dev.txt
+-rw-r--r--   0        0        0     1117 2020-02-02 00:00:00.000000 aliases-0.6.0/.github/workflows/python-publish.yml
+-rw-r--r--   0        0        0      638 2020-02-02 00:00:00.000000 aliases-0.6.0/docs/Makefile
+-rw-r--r--   0        0        0      769 2020-02-02 00:00:00.000000 aliases-0.6.0/docs/make.bat
+-rw-r--r--   0        0        0      477 2020-02-02 00:00:00.000000 aliases-0.6.0/docs/source/conf.py
+-rw-r--r--   0        0        0     3066 2020-02-02 00:00:00.000000 aliases-0.6.0/docs/source/getting_started.rst
+-rw-r--r--   0        0        0      309 2020-02-02 00:00:00.000000 aliases-0.6.0/docs/source/index.rst
+-rw-r--r--   0        0        0       76 2020-02-02 00:00:00.000000 aliases-0.6.0/docs/source/installation.rst
+-rw-r--r--   0        0        0       29 2020-02-02 00:00:00.000000 aliases-0.6.0/docs/source/reference/dict.rst
+-rw-r--r--   0        0        0      196 2020-02-02 00:00:00.000000 aliases-0.6.0/docs/source/reference/pandas.rst
+-rw-r--r--   0        0        0      358 2020-02-02 00:00:00.000000 aliases-0.6.0/docs/source/reference/polars.rst
+-rw-r--r--   0        0        0       95 2020-02-02 00:00:00.000000 aliases-0.6.0/docs/source/reference/processor.rst
+-rw-r--r--   0        0        0       76 2020-02-02 00:00:00.000000 aliases-0.6.0/docs/source/reference/space.rst
+-rw-r--r--   0        0        0       95 2020-02-02 00:00:00.000000 aliases-0.6.0/docs/source/reference/string.rst
+-rw-r--r--   0        0        0      129 2020-02-02 00:00:00.000000 aliases-0.6.0/docs/source/reference/string_function.rst
+-rw-r--r--   0        0        0      160 2020-02-02 00:00:00.000000 aliases-0.6.0/docs/source/reference/toc.rst
+-rw-r--r--   0        0        0      648 2020-02-02 00:00:00.000000 aliases-0.6.0/src/aliases/__init__.py
+-rw-r--r--   0        0        0      973 2020-02-02 00:00:00.000000 aliases-0.6.0/src/aliases/dict.py
+-rw-r--r--   0        0        0     1639 2020-02-02 00:00:00.000000 aliases-0.6.0/src/aliases/pandas_accessor.py
+-rw-r--r--   0        0        0     2741 2020-02-02 00:00:00.000000 aliases-0.6.0/src/aliases/polars_accessor.py
+-rw-r--r--   0        0        0      861 2020-02-02 00:00:00.000000 aliases-0.6.0/src/aliases/processor.py
+-rw-r--r--   0        0        0     5127 2020-02-02 00:00:00.000000 aliases-0.6.0/src/aliases/space.py
+-rw-r--r--   0        0        0      640 2020-02-02 00:00:00.000000 aliases-0.6.0/src/aliases/string.py
+-rw-r--r--   0        0        0     3084 2020-02-02 00:00:00.000000 aliases-0.6.0/src/aliases/string_function.py
+-rw-r--r--   0        0        0      324 2020-02-02 00:00:00.000000 aliases-0.6.0/src/aliases/third_party_classes.py
+-rw-r--r--   0        0        0       30 2020-02-02 00:00:00.000000 aliases-0.6.0/.gitignore
+-rw-r--r--   0        0        0     1065 2020-02-02 00:00:00.000000 aliases-0.6.0/LICENSE
+-rw-r--r--   0        0        0      400 2020-02-02 00:00:00.000000 aliases-0.6.0/README.rst
+-rw-r--r--   0        0        0      970 2020-02-02 00:00:00.000000 aliases-0.6.0/pyproject.toml
+-rw-r--r--   0        0        0     1243 2020-02-02 00:00:00.000000 aliases-0.6.0/PKG-INFO
```

### Comparing `aliases-0.5.6/.github/workflows/python-publish.yml` & `aliases-0.6.0/.github/workflows/python-publish.yml`

 * *Files identical despite different names*

### Comparing `aliases-0.5.6/src/aliases/dict.py` & `aliases-0.6.0/src/aliases/dict.py`

 * *Files identical despite different names*

### Comparing `aliases-0.5.6/src/aliases/pandas_accessor.py` & `aliases-0.6.0/src/aliases/pandas_accessor.py`

 * *Files 14% similar despite different names*

```diff
@@ -2,44 +2,36 @@
 
 import pandas as pd
 
 from aliases.space import AliasSpace, _sentinel
 
 
 @pd.api.extensions.register_series_accessor("aliases")
-class SeriesAliasAccessor:
+class PandasSeriesAliasAccessor:
     def __init__(self, pandas_obj: pd.Series) -> None:
         self._obj = pandas_obj
 
-    def preprocess(self, space: AliasSpace) -> pd.Series:
-        result = self._obj
-        if not space.case_sensitive:
-            result = result.str.lower()
-        if space.pandas_process_func is not None:
-            result = space.pandas_process_func(result)
-        return result
-
     def representative(
         self,
         space: AliasSpace,
         missing: t.Any = _sentinel,
         raise_missing: bool = False,
     ) -> pd.Series:
-        result = self.preprocess(space=space).map(space.mapper)
+        result = space.processor(self._obj).map(space.mapper)
         is_missing = result.isna()
         if is_missing.any() and raise_missing:
             raise KeyError(f"{self._obj[is_missing].values} not found in {space}")
         if missing is not _sentinel:
             return result.fillna(missing)
         result[is_missing] = self._obj[is_missing].values
         return result
 
 
 @pd.api.extensions.register_dataframe_accessor("aliases")
-class DataFrameAliasAccessor:
+class PandasDataFrameAliasAccessor:
     def __init__(self, pandas_obj: pd.DataFrame) -> None:
         self._obj = pandas_obj
 
     def representative(
         self,
         space: AliasSpace,
         columns: list[str] | None = None,
```

### Comparing `aliases-0.5.6/src/aliases/string.py` & `aliases-0.6.0/src/aliases/string.py`

 * *Files identical despite different names*

### Comparing `aliases-0.5.6/LICENSE` & `aliases-0.6.0/LICENSE`

 * *Files identical despite different names*

### Comparing `aliases-0.5.6/pyproject.toml` & `aliases-0.6.0/pyproject.toml`

 * *Files identical despite different names*


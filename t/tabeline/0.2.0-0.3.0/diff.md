# Comparing `tmp/tabeline-0.2.0.tar.gz` & `tmp/tabeline-0.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tabeline-0.2.0.tar", max compression
+gzip compressed data, was "tabeline-0.3.0.tar", max compression
```

## Comparing `tabeline-0.2.0.tar` & `tabeline-0.3.0.tar`

### file list

```diff
@@ -1,17 +1,17 @@
--rw-r--r--   0        0        0     1057 2022-05-27 00:58:00.822079 tabeline-0.2.0/LICENSE
--rw-r--r--   0        0        0     1709 2023-04-21 01:31:22.559414 tabeline-0.2.0/README.md
--rw-r--r--   0        0        0     1966 2023-04-22 10:01:16.847548 tabeline-0.2.0/pyproject.toml
--rw-r--r--   0        0        0       97 2023-04-21 02:03:52.594662 tabeline-0.2.0/src/tabeline/__init__.py
--rw-r--r--   0        0        0    22663 2023-04-21 18:11:21.414724 tabeline-0.2.0/src/tabeline/_data_frame.py
--rw-r--r--   0        0        0      365 2023-04-21 01:31:22.563413 tabeline-0.2.0/src/tabeline/_dummy.py
--rw-r--r--   0        0        0      241 2022-04-10 13:57:42.631712 tabeline-0.2.0/src/tabeline/_expression/__init__.py
--rw-r--r--   0        0        0     2450 2022-07-24 20:02:47.710297 tabeline-0.2.0/src/tabeline/_expression/_functions.py
--rw-r--r--   0        0        0     4313 2022-04-10 13:57:42.631712 tabeline-0.2.0/src/tabeline/_expression/_parser.py
--rw-r--r--   0        0        0     5363 2022-04-10 13:57:42.631712 tabeline-0.2.0/src/tabeline/_expression/_substitute.py
--rw-r--r--   0        0        0     3744 2022-04-10 13:57:42.631712 tabeline-0.2.0/src/tabeline/_expression/_to_polars.py
--rw-r--r--   0        0        0     2902 2022-04-10 13:57:42.631712 tabeline-0.2.0/src/tabeline/_expression/ast.py
--rw-r--r--   0        0        0      573 2022-04-10 13:57:42.635712 tabeline-0.2.0/src/tabeline/_result.py
--rw-r--r--   0        0        0      733 2022-04-12 00:13:33.013959 tabeline-0.2.0/src/tabeline/_validation.py
--rw-r--r--   0        0        0     1918 2023-04-21 01:31:22.559414 tabeline-0.2.0/src/tabeline/exceptions.py
--rw-r--r--   0        0        0      381 2023-04-21 01:31:22.559414 tabeline-0.2.0/src/tabeline/testing.py
--rw-r--r--   0        0        0     2896 1970-01-01 00:00:00.000000 tabeline-0.2.0/PKG-INFO
+-rw-r--r--   0        0        0     1062 2023-06-28 10:08:20.880692 tabeline-0.3.0/LICENSE
+-rw-r--r--   0        0        0     1708 2023-04-26 09:54:10.670471 tabeline-0.3.0/README.md
+-rw-r--r--   0        0        0     1914 2023-06-28 10:16:38.864033 tabeline-0.3.0/pyproject.toml
+-rw-r--r--   0        0        0      136 2023-06-27 13:07:54.545095 tabeline-0.3.0/src/tabeline/__init__.py
+-rw-r--r--   0        0        0     1364 2023-05-03 23:40:51.395289 tabeline-0.3.0/src/tabeline/_concatenate.py
+-rw-r--r--   0        0        0    22663 2023-06-27 12:23:24.487028 tabeline-0.3.0/src/tabeline/_data_frame.py
+-rw-r--r--   0        0        0      365 2023-04-21 01:31:22.563413 tabeline-0.3.0/src/tabeline/_dummy.py
+-rw-r--r--   0        0        0      195 2023-06-27 13:06:17.969366 tabeline-0.3.0/src/tabeline/_expression/__init__.py
+-rw-r--r--   0        0        0     2832 2023-05-04 11:38:10.169202 tabeline-0.3.0/src/tabeline/_expression/_functions.py
+-rw-r--r--   0        0        0     4071 2023-06-27 13:13:14.028287 tabeline-0.3.0/src/tabeline/_expression/_parser.py
+-rw-r--r--   0        0        0     5363 2022-04-10 13:57:42.631712 tabeline-0.3.0/src/tabeline/_expression/_substitute.py
+-rw-r--r--   0        0        0     3744 2022-04-10 13:57:42.631712 tabeline-0.3.0/src/tabeline/_expression/_to_polars.py
+-rw-r--r--   0        0        0     2788 2023-06-27 13:13:17.724278 tabeline-0.3.0/src/tabeline/_expression/ast.py
+-rw-r--r--   0        0        0      733 2023-05-03 12:09:48.914426 tabeline-0.3.0/src/tabeline/_validation.py
+-rw-r--r--   0        0        0     3570 2023-05-03 23:40:51.395289 tabeline-0.3.0/src/tabeline/exceptions.py
+-rw-r--r--   0        0        0      381 2023-04-21 01:31:22.559414 tabeline-0.3.0/src/tabeline/testing.py
+-rw-r--r--   0        0        0     2910 1970-01-01 00:00:00.000000 tabeline-0.3.0/PKG-INFO
```

### Comparing `tabeline-0.2.0/LICENSE` & `tabeline-0.3.0/LICENSE`

 * *Files 1% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-Copyright (c) 2022 David R Hagen
+Copyright (c) 2022-2023 David R Hagen
 
 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:
```

### Comparing `tabeline-0.2.0/README.md` & `tabeline-0.3.0/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 # Tabeline
 
-Tabeline is a data frame and data grammar library. You write the expressions in strings and supply them to methods on the `DataFrame` class. The  strings are parsed by Parsita and converted into Polars for execution.
+Tabeline is a data frame and data grammar library. You write the expressions in strings and supply them to methods on the `DataFrame` class. The strings are parsed by Parsita and converted into Polars for execution.
 
 Tabeline draws inspiration from dplyr, the data grammar of R's tidyverse, especially for its methods names. The `filter`, `mutate`, `group_by`, and `summarize` methods should all feel familiar. But Tabeline is as proper a Python library as can be, using methods instead of pipes, like is standard in R. 
 
 Tabeline uses Polars under the hood, but adds a lot of handling of edge cases from Polars, which otherwise result in crashes or behavior that is not type stable.
 
 See the [Documentation](https://tabeline.drhagen.com) for the full user guide.
```

### Comparing `tabeline-0.2.0/pyproject.toml` & `tabeline-0.3.0/pyproject.toml`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "tabeline"
-version = "0.2.0"
+version = "0.3.0"
 description = "A data frame and data grammar library"
 authors = ["David Hagen <david@drhagen.com>"]
 license = "MIT"
 readme = "README.md"
 documentation = "https://tabeline.drhagen.com"
 repository = "https://github.com/drhagen/tabeline"
 keywords = ["dataframe", "datatable", "datagrammar", "dplyr"]
@@ -14,46 +14,46 @@
     "Topic :: Software Development :: Libraries :: Python Modules",
     "Operating System :: OS Independent",
 ]
 
 
 [tool.poetry.dependencies]
 python = "^3.9"
-polars = "^0.17.5"
-parsita = "^1.7.0"
-typing_extensions = "^4.3.0"
-pandas = { version = "^1.4.3", optional = true }
-pyarrow = { version = "^11.0.0", optional = true }
+polars = "^0.17|^0.18"
+numpy = "^1.24"
+parsita = "^2.0"
+typing_extensions = "^4.3"
+pandas = { version = "^1.4", optional = true }
+pyarrow = { version = "^11.0", optional = true }
 
 [tool.poetry.dev-dependencies]
 nox_poetry = "^1.0.2"
 
 # Converters
 pyarrow = "^11.0.0"
 pandas = "^1.4"
 
 # Test
-pytest = "^7.1.1"
-coverage = { version = "^6.3.2", extras = ["toml"] }
-pytest-cov = "^3.0.0"
+pytest = "^7.2"
+pytest-cov = "*"
 
 # Black
 black = ">=22.3.0"
 
 # Isort
 isort = "^5.9.3"
 
 # Flake8
 flake8 = "^4.0.1"
 pyproject-flake8 = "^0.0.1a3"
 pep8-naming = "^0.12.1"
 flake8-noqa = "^1.2.1"
 
 # Docs
-mkdocs-material = "^8.2.8"
+mkdocs-material = "^9"
 
 [tool.poetry.extras]
 pandas = ["pandas", "pyarrow"]
 
 
 [tool.pytest.ini_options]
 xfail_strict = true
```

### Comparing `tabeline-0.2.0/src/tabeline/_data_frame.py` & `tabeline-0.3.0/src/tabeline/_data_frame.py`

 * *Files 0% similar despite different names*

```diff
@@ -175,15 +175,15 @@
 
                 return DataFrame(new_df, self.group_levels)
 
     def slice1(self, indexes: list[int], /) -> DataFrame:
         return self.slice0([index - 1 for index in indexes])
 
     def filter(self, predicate: str, /) -> DataFrame:
-        expression = to_polars(Expression.parse(predicate).or_die())
+        expression = to_polars(Expression.parse(predicate).unwrap())
 
         if self.width == 0:
             # There is no way to evaluate an expression outside a data frame, so
             # make a dummy data frame with the right number of rows.
             # eager=True needed because lazy expressions are not allowed in
             # the constructor
             # https://github.com/pola-rs/polars/issues/2983
@@ -346,20 +346,20 @@
         # because a column may refer to previous columns, which is not allowed
         # in a select context in polars:
         # https://stackoverflow.com/q/71105136/
         polars_operation = df.lazy()
         if len(group_set) == 0:
             for name, mutator in mutators.items():
                 polars_operation = polars_operation.with_columns(
-                    to_polars(Expression.parse(mutator).or_die()).alias(name)
+                    to_polars(Expression.parse(mutator).unwrap()).alias(name)
                 )
         else:
             for name, mutator in mutators.items():
                 polars_operation = polars_operation.with_columns(
-                    to_polars(Expression.parse(mutator).or_die())
+                    to_polars(Expression.parse(mutator).unwrap())
                     .over(list(self.group_names))
                     .alias(name)
                 )
 
         if self.width == 0:
             polars_operation = polars_operation.drop(dummy_name)
 
@@ -407,15 +407,15 @@
 
         # There is no way to sequentially evaluate expressions in a groupby
         # context, so each reducer must be substituted into subsequent reducers:
         # https://stackoverflow.com/q/71120396/
         substituted_reducers = {}
         for name, reducer in reducers.items():
             substituted_reducers[name] = substitute(
-                Expression.parse(reducer).or_die(), substituted_reducers
+                Expression.parse(reducer).unwrap(), substituted_reducers
             )
 
         polars_expressions = [
             to_polars(reducer).alias(name) for name, reducer in substituted_reducers.items()
         ]
 
         if len(polars_expressions) == 0:
```

### Comparing `tabeline-0.2.0/src/tabeline/_expression/_functions.py` & `tabeline-0.3.0/src/tabeline/_expression/_functions.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,13 +1,14 @@
 __all__ = ["Function", "function_by_name"]
 
 from dataclasses import dataclass
 from typing import Any, Callable, Generic, TypeVar
 from typing_extensions import ParamSpec  # Not present in Python 3.9
 
+import numpy as np
 import polars as pl
 
 P = ParamSpec("P")
 R = TypeVar("R")
 
 
 @dataclass(frozen=True)
@@ -28,17 +29,17 @@
     Function("log2", lambda x: x.log(2)),
     Function("log10", lambda x: x.log10()),
     Function("exp", lambda x: x.exp()),
     Function("pow", lambda x, y: x**y),
     Function("sin", lambda x: x.sin()),
     Function("cos", lambda x: x.cos()),
     Function("tan", lambda x: x.tan()),
-    # Function("arcsin", lambda x: x.arcsin()),  # Decide on name
-    # Function("arccos", lambda x: x.arccos()),  # Decide on name
-    # Function("arctan", lambda x: x.arctan()),  # Decide on name
+    Function("arcsin", lambda x: x.arcsin()),
+    Function("arccos", lambda x: x.arccos()),
+    Function("arctan", lambda x: x.arctan()),
     Function("floor", lambda x: x.floor()),
     Function("ceil", lambda x: x.ceil()),
     # Numeric -> boolean elementwise
     Function("is_nan", lambda x: x.is_nan()),
     # Numeric -> numeric reduction
     Function("std", lambda x: x.std()),
     Function("var", lambda x: x.var()),
@@ -50,17 +51,30 @@
     Function(
         "quantile",
         lambda x, quantile: x.quantile(pl.select(quantile)[0, 0], interpolation="linear"),
     ),
     Function(
         "trapz", lambda x, y: 0.5 * ((x - x.shift()) * (y + y.shift())).sum()
     ),  # https://github.com/pola-rs/polars/issues/3043
+    Function(
+        "interp",
+        lambda x, xp, fp: pl.apply(
+            exprs=[x, xp, fp],
+            function=lambda args: pl.Series(
+                [np.interp(args[0], args[1], args[2])], dtype=pl.Float64
+            ),
+        ),
+    ),  # https://stackoverflow.com/a/69585269/
     # Boolean -> boolean reduction
     Function("any", lambda x: x.any()),
     Function("all", lambda x: x.all()),
     # Any -> any reduction
     # Function("mode", lambda x: x.mode()),  # Not type stable
     Function("first", lambda x: x.first()),
     Function("last", lambda x: x.last()),
+    Function(
+        "if_else",
+        lambda condition, true, false=None: pl.when(condition).then(true).otherwise(false),
+    ),
 ]
 
 function_by_name: dict[str, Function[Any, Any]] = {x.name: x for x in built_in_functions}
```

### Comparing `tabeline-0.2.0/src/tabeline/_expression/_parser.py` & `tabeline-0.3.0/src/tabeline/_expression/_parser.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,16 +1,15 @@
-__all__ = ["parse_expression", "ParseError"]
+__all__ = ["parse_expression"]
 
 from functools import reduce
 from typing import Literal, Union
 
-from parsita import Failure, TextParsers, lit, opt, pred, reg, rep, rep1sep, repsep
+from parsita import ParserContext, Result, lit, opt, pred, reg, rep, rep1sep, repsep
 from parsita.util import constant, splat
 
-from .. import _result
 from . import ast
 from .ast import Expression
 
 reserved_names = {"None", "True", "False", "inf", "nan"}
 
 
 def make_exponent(first: Expression, maybe_second: Union[tuple[()], tuple[Expression]]):
@@ -67,15 +66,15 @@
             return ast.GreaterThan(first, second)
         elif op == "<":
             return ast.LessThan(first, second)
         else:
             raise NotImplementedError
 
 
-class ExpressionParser(TextParsers):
+class ExpressionParser(ParserContext, whitespace=r"[ ]*"):
     name = pred(reg(r"[A-Za-z_][A-Za-z_0-9]*"), lambda x: x not in reserved_names, "non-keyword")
 
     # Atoms
     null = lit("None") > constant(ast.NullLiteral())
 
     true = lit("True") > constant(ast.BooleanLiteral(True))
     false = lit("False") > constant(ast.BooleanLiteral(False))
@@ -125,18 +124,9 @@
 
     unary_boolean = not_expression | comparison_expression
 
     and_expression = rep1sep(unary_boolean, "&") > (lambda x: reduce(ast.And, x))
     expression = rep1sep(and_expression, "|") > (lambda x: reduce(ast.Or, x))
 
 
-class ParseError(Exception):
-    pass
-
-
-def parse_expression(text: str) -> _result.Result[Expression, ParseError]:
-    result = ExpressionParser.expression.parse(text)
-
-    if isinstance(result, Failure):
-        return _result.Failure(ParseError(result.message))
-    else:
-        return _result.Success(result.or_die())
+def parse_expression(text: str) -> Result:
+    return ExpressionParser.expression.parse(text)
```

### Comparing `tabeline-0.2.0/src/tabeline/_expression/_substitute.py` & `tabeline-0.3.0/src/tabeline/_expression/_substitute.py`

 * *Files identical despite different names*

### Comparing `tabeline-0.2.0/src/tabeline/_expression/_to_polars.py` & `tabeline-0.3.0/src/tabeline/_expression/_to_polars.py`

 * *Files identical despite different names*

### Comparing `tabeline-0.2.0/src/tabeline/_expression/ast.py` & `tabeline-0.3.0/src/tabeline/_expression/ast.py`

 * *Files 4% similar despite different names*

```diff
@@ -25,25 +25,21 @@
     "LessThanOrEqual",
     "Not",
     "And",
     "Or",
 ]
 
 from dataclasses import dataclass
-from typing import TYPE_CHECKING
 
-from .._result import Result
-
-if TYPE_CHECKING:
-    from ._parser import ParseError
+from parsita import Result
 
 
 class Expression:
     @staticmethod
-    def parse(text: str) -> Result[Expression, ParseError]:
+    def parse(text: str) -> Result:
         from ._parser import parse_expression
 
         return parse_expression(text)
 
 
 @dataclass(frozen=True)
 class NullLiteral(Expression):
```

### Comparing `tabeline-0.2.0/src/tabeline/_validation.py` & `tabeline-0.3.0/src/tabeline/_validation.py`

 * *Files identical despite different names*

### Comparing `tabeline-0.2.0/PKG-INFO` & `tabeline-0.3.0/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tabeline
-Version: 0.2.0
+Version: 0.3.0
 Summary: A data frame and data grammar library
 Home-page: https://github.com/drhagen/tabeline
 License: MIT
 Keywords: dataframe,datatable,datagrammar,dplyr
 Author: David Hagen
 Author-email: david@drhagen.com
 Requires-Python: >=3.9,<4.0
@@ -14,26 +14,27 @@
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Provides-Extra: pandas
-Requires-Dist: pandas (>=1.4.3,<2.0.0) ; extra == "pandas"
-Requires-Dist: parsita (>=1.7.0,<2.0.0)
-Requires-Dist: polars (>=0.17.5,<0.18.0)
-Requires-Dist: pyarrow (>=11.0.0,<12.0.0) ; extra == "pandas"
-Requires-Dist: typing_extensions (>=4.3.0,<5.0.0)
+Requires-Dist: numpy (>=1.24,<2.0)
+Requires-Dist: pandas (>=1.4,<2.0) ; extra == "pandas"
+Requires-Dist: parsita (>=2.0,<3.0)
+Requires-Dist: polars (>=0.17,<0.19)
+Requires-Dist: pyarrow (>=11.0,<12.0) ; extra == "pandas"
+Requires-Dist: typing_extensions (>=4.3,<5.0)
 Project-URL: Documentation, https://tabeline.drhagen.com
 Project-URL: Repository, https://github.com/drhagen/tabeline
 Description-Content-Type: text/markdown
 
 # Tabeline
 
-Tabeline is a data frame and data grammar library. You write the expressions in strings and supply them to methods on the `DataFrame` class. The  strings are parsed by Parsita and converted into Polars for execution.
+Tabeline is a data frame and data grammar library. You write the expressions in strings and supply them to methods on the `DataFrame` class. The strings are parsed by Parsita and converted into Polars for execution.
 
 Tabeline draws inspiration from dplyr, the data grammar of R's tidyverse, especially for its methods names. The `filter`, `mutate`, `group_by`, and `summarize` methods should all feel familiar. But Tabeline is as proper a Python library as can be, using methods instead of pipes, like is standard in R. 
 
 Tabeline uses Polars under the hood, but adds a lot of handling of edge cases from Polars, which otherwise result in crashes or behavior that is not type stable.
 
 See the [Documentation](https://tabeline.drhagen.com) for the full user guide.
```


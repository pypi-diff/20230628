# Comparing `tmp/flake8_pyi-23.5.0.tar.gz` & `tmp/flake8_pyi-23.6.0.tar.gz`

## Comparing `flake8_pyi-23.5.0.tar` & `flake8_pyi-23.6.0.tar`

### file list

```diff
@@ -1,43 +1,45 @@
--rw-r--r--   0        0        0      205 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/.editorconfig
--rw-r--r--   0        0        0     1463 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/.flake8
--rw-r--r--   0        0        0      802 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/.pre-commit-config.yaml
--rw-r--r--   0        0        0    14655 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/CHANGELOG.md
--rw-r--r--   0        0        0     2084 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/CONTRIBUTING.md
--rw-r--r--   0        0        0    80868 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/pyi.py
--rw-r--r--   0        0        0      636 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/.github/scripts/typeshed_primer_download_errors.js
--rw-r--r--   0        0        0     1038 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/.github/scripts/typeshed_primer_post_comment.js
--rw-r--r--   0        0        0     1876 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/.github/workflows/check.yml
--rw-r--r--   0        0        0      998 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/.github/workflows/publish.yml
--rw-r--r--   0        0        0     1918 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/.github/workflows/typeshed_primer.yml
--rw-r--r--   0        0        0     1142 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/.github/workflows/typeshed_primer_comment.yml
--rw-r--r--   0        0        0     4299 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/aliases.pyi
--rw-r--r--   0        0        0     7119 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/attribute_annotations.pyi
--rw-r--r--   0        0        0     1987 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/calls.pyi
--rw-r--r--   0        0        0     7111 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/classdefs.pyi
--rw-r--r--   0        0        0      480 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/comparisons.pyi
--rw-r--r--   0        0        0     5166 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/defaults.pyi
--rw-r--r--   0        0        0      373 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/defaults_py38.pyi
--rw-r--r--   0        0        0      236 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/del.pyi
--rw-r--r--   0        0        0      497 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/emptyclasses.pyi
--rw-r--r--   0        0        0     1299 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/emptyfunctions.pyi
--rw-r--r--   0        0        0     4333 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/exit_methods.pyi
--rw-r--r--   0        0        0      533 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/forward_refs.pyi
--rw-r--r--   0        0        0     1163 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/forward_refs_annassign.pyi
--rw-r--r--   0        0        0    10739 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/imports.pyi
--rw-r--r--   0        0        0      703 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/names_requiring_values.pyi
--rw-r--r--   0        0        0      906 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/never_vs_noreturn.pyi
--rw-r--r--   0        0        0     1966 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/pep604_union_types.pyi
--rw-r--r--   0        0        0     3178 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/quotes.pyi
--rw-r--r--   0        0        0      281 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/sysplatform.pyi
--rw-r--r--   0        0        0     1938 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/sysversioninfo.pyi
--rw-r--r--   0        0        0     2132 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/test_pyi_files.py
--rw-r--r--   0        0        0     2138 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/type_comments.pyi
--rw-r--r--   0        0        0     2361 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/typevar.pyi
--rw-r--r--   0        0        0     8912 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/union_duplicates.pyi
--rw-r--r--   0        0        0     2052 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/unused_things.pyi
--rw-r--r--   0        0        0      299 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/tests/vanilla_flake8_not_clean_forward_refs.pyi
--rw-r--r--   0        0        0      823 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/.gitignore
--rw-r--r--   0        0        0     1080 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/LICENSE
--rw-r--r--   0        0        0    12305 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/README.md
--rw-r--r--   0        0        0     2829 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/pyproject.toml
--rw-r--r--   0        0        0    14348 2020-02-02 00:00:00.000000 flake8_pyi-23.5.0/PKG-INFO
+-rw-r--r--   0        0        0      205 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/.editorconfig
+-rw-r--r--   0        0        0     1463 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/.flake8
+-rw-r--r--   0        0        0      802 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/.pre-commit-config.yaml
+-rw-r--r--   0        0        0    16677 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/CHANGELOG.md
+-rw-r--r--   0        0        0     2084 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/CONTRIBUTING.md
+-rw-r--r--   0        0        0    10411 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/ERRORCODES.md
+-rw-r--r--   0        0        0    80277 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/pyi.py
+-rw-r--r--   0        0        0      636 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/.github/scripts/typeshed_primer_download_errors.js
+-rw-r--r--   0        0        0     1038 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/.github/scripts/typeshed_primer_post_comment.js
+-rw-r--r--   0        0        0     1947 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/.github/workflows/check.yml
+-rw-r--r--   0        0        0      998 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/.github/workflows/publish.yml
+-rw-r--r--   0        0        0     1969 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/.github/workflows/typeshed_primer.yml
+-rw-r--r--   0        0        0     1142 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/.github/workflows/typeshed_primer_comment.yml
+-rw-r--r--   0        0        0      349 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/F822.pyi
+-rw-r--r--   0        0        0     4299 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/aliases.pyi
+-rw-r--r--   0        0        0     7119 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/attribute_annotations.pyi
+-rw-r--r--   0        0        0     1987 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/calls.pyi
+-rw-r--r--   0        0        0     7111 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/classdefs.pyi
+-rw-r--r--   0        0        0      480 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/comparisons.pyi
+-rw-r--r--   0        0        0     5562 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/defaults.pyi
+-rw-r--r--   0        0        0      236 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/del.pyi
+-rw-r--r--   0        0        0      497 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/emptyclasses.pyi
+-rw-r--r--   0        0        0     1299 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/emptyfunctions.pyi
+-rw-r--r--   0        0        0     4333 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/exit_methods.pyi
+-rw-r--r--   0        0        0     1339 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/forward_refs.pyi
+-rw-r--r--   0        0        0     1163 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/forward_refs_annassign.pyi
+-rw-r--r--   0        0        0    11079 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/imports.pyi
+-rw-r--r--   0        0        0      703 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/names_requiring_values.pyi
+-rw-r--r--   0        0        0      906 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/never_vs_noreturn.pyi
+-rw-r--r--   0        0        0     1966 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/pep604_union_types.pyi
+-rw-r--r--   0        0        0     3693 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/pep695_py312.pyi
+-rw-r--r--   0        0        0     3501 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/quotes.pyi
+-rw-r--r--   0        0        0      281 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/sysplatform.pyi
+-rw-r--r--   0        0        0     2339 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/sysversioninfo.pyi
+-rw-r--r--   0        0        0     2111 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/test_pyi_files.py
+-rw-r--r--   0        0        0     2138 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/type_comments.pyi
+-rw-r--r--   0        0        0     2513 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/typevar.pyi
+-rw-r--r--   0        0        0     8912 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/union_duplicates.pyi
+-rw-r--r--   0        0        0     3368 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/unused_things.pyi
+-rw-r--r--   0        0        0      299 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/tests/vanilla_flake8_not_clean_forward_refs.pyi
+-rw-r--r--   0        0        0      823 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/.gitignore
+-rw-r--r--   0        0        0     1080 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/LICENSE
+-rw-r--r--   0        0        0     2597 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/README.md
+-rw-r--r--   0        0        0     2807 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/pyproject.toml
+-rw-r--r--   0        0        0     4612 2020-02-02 00:00:00.000000 flake8_pyi-23.6.0/PKG-INFO
```

### Comparing `flake8_pyi-23.5.0/.flake8` & `flake8_pyi-23.6.0/.flake8`

 * *Files 1% similar despite different names*

```diff
@@ -15,15 +15,15 @@
 #       E302 expected 2 blank lines
 #       E305 expected 2 blank lines
 #       E701 multiple statements on one line (colon) -- disallows "..." on the same line
 #       E704 multiple statements on one line (def) -- disallows function body on the same line as the def
 #
 # flake8-bugbear rules that cause too many false positives:
 #       B905 "`zip()` without an explicit `strict=True` parameter --
-#           the `strict` parameter was introduced in Python 3.10; we support Python 3.7
+#           the `strict` parameter was introduced in Python 3.10; we support Python 3.8
 #       B907 "Use !r inside f-strings instead of manual quotes" --
 #           produces false positives if you're surrounding things with double quotes
 
 [flake8]
 max-line-length = 80
 max-complexity = 12
 noqa-require-code = true
```

### Comparing `flake8_pyi-23.5.0/.pre-commit-config.yaml` & `flake8_pyi-23.6.0/.pre-commit-config.yaml`

 * *Files 1% similar despite different names*

```diff
@@ -8,15 +8,15 @@
       - id: check-toml
       - id: check-merge-conflict
       - id: mixed-line-ending
   - repo: https://github.com/psf/black
     rev: 23.3.0 # must match pyproject.toml
     hooks:
       - id: black
-        language_version: python3.7
+        language_version: python3.8
   - repo: https://github.com/pycqa/isort
     rev: 5.12.0 # must match pyproject.toml
     hooks:
       - id: isort
         name: isort (python)
 
 ci:
```

### Comparing `flake8_pyi-23.5.0/CHANGELOG.md` & `flake8_pyi-23.6.0/CHANGELOG.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,9 +1,47 @@
 # Change Log
 
+## 23.6.0
+
+Features:
+* Support Python 3.12
+* Support [PEP 695](https://peps.python.org/pep-0695/) syntax for declaring
+  type aliases
+* Correctly emit Y019 errors for PEP-695 methods that are generic around a `TypeVar`
+  instead of returning `typing_extensions.Self`
+* Introduce Y057: Do not use `typing.ByteString` or `collections.abc.ByteString`. These
+  types have unclear semantics, and are deprecated; use  `typing_extensions.Buffer` or
+  a union such as `bytes | bytearray | memoryview` instead. See
+  [PEP 688](https://peps.python.org/pep-0688/) for more details.
+* The way in which flake8-pyi modifies pyflakes runs has been improved:
+  * When flake8-pyi is installed, pyflakes will now complain about forward references
+    in default values for function and method parameters (the same as pyflakes
+    does when it checks `.py` files). Unlike in `.py` files, forward references
+    in default values are legal in stub files. However, they are never necessary,
+    and are considered bad style. (Forward references for parameter *annotations*
+    are still allowed.)
+
+    Contributed by [tomasr8](https://github.com/tomasr8).
+  * When flake8-pyi is installed, pyflakes's F822 check now produces many fewer false
+    positives when flake8 is run on `.pyi` files. It now understands that `x: int` in a
+    stub file is sufficient for `x` to be considered "bound", and that `"x"` can
+    therefore be included in `__all__`.
+
+Bugfixes:
+* Y018, Y046, Y047 and Y049 previously failed to detect unused
+  TypeVars/ParamSpecs/TypeAliases/TypedDicts/Protocols if the object in question had
+  multiple definitions in the same file (e.g. across two branches of an `if
+  sys.version_info >= (3, 10)` check). This bug has now been fixed.
+* Y020 was previously not emitted if quoted annotations were used in TypeVar
+  constraints. This bug has now been fixed.
+
+Other changes:
+* flake8-pyi no longer supports being run on Python 3.7, which has reached its end of life.
+* flake8-pyi no longer supports being run with flake8 <v6.
+
 ## 23.5.0
 
 * flake8-pyi no longer supports being run with flake8 <5.0.4.
 * The way in which flake8-pyi modifies pyflakes runs has been improved:
   * When flake8-pyi is installed, pyflakes now correctly recognises an annotation as
     being equivalent to a binding assignment in a stub file, reducing false
     positives from flake8's F821 error code.
```

### Comparing `flake8_pyi-23.5.0/CONTRIBUTING.md` & `flake8_pyi-23.6.0/CONTRIBUTING.md`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/pyi.py` & `flake8_pyi-23.6.0/pyi.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,30 +1,29 @@
 #!/usr/bin/env python3
 from __future__ import annotations
 
 import argparse
 import ast
 import logging
-import optparse
 import re
 import sys
 from collections import Counter, defaultdict
 from collections.abc import Container, Iterable, Iterator, Sequence
-from contextlib import contextmanager, suppress
+from contextlib import contextmanager
 from copy import deepcopy
 from dataclasses import dataclass
 from functools import partial
 from itertools import chain, zip_longest
 from keyword import iskeyword
-from pathlib import Path
 from typing import TYPE_CHECKING, Any, ClassVar, NamedTuple, Union
 
-from flake8 import checker  # type: ignore[import]
-from flake8.options.manager import OptionManager  # type: ignore[import]
-from flake8.plugins.pyflakes import FlakesChecker  # type: ignore[import]
+from flake8 import checker
+from flake8.options.manager import OptionManager
+from flake8.plugins.finder import LoadedPlugin
+from flake8.plugins.pyflakes import FlakesChecker
 from pyflakes.checker import ModuleScope
 
 if sys.version_info >= (3, 9):
     from ast import unparse
 else:
     from ast_decompiler import decompile
 
@@ -34,18 +33,23 @@
 
 if TYPE_CHECKING:
     # We don't have typing_extensions as a runtime dependency,
     # but all our annotations are stringized due to __future__ annotations,
     # and mypy thinks typing_extensions is part of the stdlib.
     from typing_extensions import Literal, TypeAlias, TypeGuard
 
-__version__ = "23.5.0"
+__version__ = "23.6.0"
 
 LOG = logging.getLogger("flake8.pyi")
 
+if sys.version_info >= (3, 12):
+    _TypeAliasNodeType: TypeAlias = ast.TypeAlias | ast.AnnAssign
+else:
+    _TypeAliasNodeType: TypeAlias = ast.AnnAssign
+
 if sys.version_info >= (3, 9):
     _SliceContents: TypeAlias = ast.expr
 else:
     _SliceContents: TypeAlias = Union[ast.expr, ast.slice]
 
 
 class Error(NamedTuple):
@@ -98,17 +102,18 @@
     # Typing_extensions aliases for contextlib
     "typing_extensions.ContextManager": ("contextlib.AbstractContextManager", "T"),
     "typing_extensions.AsyncContextManager": (
         "contextlib.AbstractAsyncContextManager",
         "T",
     ),
     # typing aliases for collections.abc
-    # typing.AbstractSet is deliberately omitted (special-cased elsewhere)
-    # If the second element of the tuple is `None`, it signals that the object shouldn't be parameterized
-    "typing.ByteString": ("collections.abc.ByteString", None),
+    # typing.AbstractSet and typing.ByteString are deliberately omitted
+    # (special-cased elsewhere).
+    # If the second element of the tuple is `None`,
+    # it signals that the object shouldn't be parameterized
     "typing.Collection": ("collections.abc.Collection", "T"),
     "typing.ItemsView": ("collections.abc.ItemsView", _MAPPING_SLICE),
     "typing.KeysView": ("collections.abc.KeysView", "KeyType"),
     "typing.Mapping": ("collections.abc.Mapping", _MAPPING_SLICE),
     "typing.MappingView": ("collections.abc.MappingView", None),
     "typing.MutableMapping": ("collections.abc.MutableMapping", _MAPPING_SLICE),
     "typing.MutableSequence": ("collections.abc.MutableSequence", "T"),
@@ -177,70 +182,61 @@
 
 
 class PyiAwareFlakesChecker(FlakesChecker):
     def __init__(self, tree: ast.AST, *args: Any, **kwargs: Any) -> None:
         super().__init__(PyflakesPreProcessor().visit(tree), *args, **kwargs)
 
     @property
-    def annotationsFutureEnabled(self):
-        """pyflakes can already handle forward refs for annotations, but only via
-        `from __future__ import annotations`.
+    def annotationsFutureEnabled(self) -> Literal[True]:
+        """Always allow forward references in `.pyi` files.
 
-        We don't want to bother including this in every file, so we just set this to `True`.
+        Pyflakes can already handle forward refs for annotations,
+        but only via `from __future__ import annotations`.
+        In a stub file, `from __future__ import annotations` is unnecessary,
+        so we pretend to pyflakes that it's always present when linting a `.pyi` file.
         """
         return True
 
     @annotationsFutureEnabled.setter
-    def annotationsFutureEnabled(self, value: bool):
+    def annotationsFutureEnabled(self, value: bool) -> None:
         """Does nothing, as we always want this property to be `True`."""
         pass
 
-    def deferHandleNode(self, node: ast.AST | None, parent) -> None:
-        self.deferFunction(lambda: self.handleNode(node, parent))
-
     def ASSIGN(
         self, tree: ast.Assign, omit: str | tuple[str, ...] | None = None
     ) -> None:
-        """This is a custom implementation of ASSIGN derived from
+        """Defer evaluation of assignments in the module scope.
+
+        This is a custom implementation of ASSIGN, originally derived from
         handleChildren() in pyflakes 1.3.0.
 
-        The point here is that on module level, there's type aliases that we
-        want to bind eagerly, but defer computation of the values of the
-        assignments (the type aliases might have forward references).
+        This reduces false positives for:
+          - TypeVars bound or constrained to forward references
+          - Assignments to forward references that are not explicitly
+            demarcated as type aliases.
         """
         if not isinstance(self.scope, ModuleScope):
             super().ASSIGN(tree)
             return
 
         for target in tree.targets:
             self.handleNode(target, tree)
 
-        self.deferHandleNode(tree.value, tree)
-
-    def LAMBDA(self, node: ast.Lambda) -> None:
-        """This is likely very brittle, currently works for pyflakes 1.3.0.
-
-        Deferring annotation handling depends on the fact that during calls
-        to LAMBDA visiting the function's body is already deferred and the
-        only eager calls to `handleNode` are for annotations.
-        """
-        self.handleNode, self.deferHandleNode = self.deferHandleNode, self.handleNode  # type: ignore[method-assign]
-        super().LAMBDA(node)
-        self.handleNode, self.deferHandleNode = self.deferHandleNode, self.handleNode  # type: ignore[method-assign]
+        self.deferFunction(lambda: self.handleNode(tree.value, tree))
 
     def handleNodeDelete(self, node: ast.AST) -> None:
         """Null implementation.
 
         Lets users use `del` in stubs to denote private names.
         """
         return
 
 
 class PyiAwareFileChecker(checker.FileChecker):
-    def run_check(self, plugin, **kwargs: Any) -> Any:
+    def run_check(self, plugin: LoadedPlugin, **kwargs: Any) -> Any:
         if plugin.obj is FlakesChecker:
             if self.filename == "-":
                 filename = self.options.stdin_display_name
             else:
                 filename = self.filename
 
             if filename.endswith(".pyi"):
@@ -295,15 +291,16 @@
 
     Return True if `node` is either:
     1). Of shape `ast.Name(id=<name>)`, or;
     2). Of shape `ast.Attribute(value=ast.Name(id=<parent>), attr=<name>)`,
         where <parent> is a string that can be found within the `from_` collection of
         strings.
 
-    >>> _is_AsyncIterator = partial(_is_object, name="AsyncIterator", from_=_TYPING_MODULES | {"collections.abc"})
+    >>> modules = _TYPING_MODULES | {"collections.abc"}
+    >>> _is_AsyncIterator = partial(_is_object, name="AsyncIterator", from_=modules)
     >>> _is_AsyncIterator(_ast_node_for("AsyncIterator"))
     True
     >>> _is_AsyncIterator(_ast_node_for("typing.AsyncIterator"))
     True
     >>> _is_AsyncIterator(_ast_node_for("typing_extensions.AsyncIterator"))
     True
     >>> _is_AsyncIterator(_ast_node_for("collections.abc.AsyncIterator"))
@@ -362,17 +359,18 @@
     is a module in `modules`.
     If it is, return the part after the dot; if it isn't, return `None`.
 
     If `classnode` is anything else, return `None`.
 
     >>> _get_name_of_class_if_from_modules(_ast_node_for('int'), modules={'builtins'})
     'int'
-    >>> _get_name_of_class_if_from_modules(_ast_node_for('builtins.int'), modules={'builtins'})
+    >>> int_node = _ast_node_for('builtins.int')
+    >>> _get_name_of_class_if_from_modules(int_node, modules={'builtins'})
     'int'
-    >>> _get_name_of_class_if_from_modules(_ast_node_for('builtins.int'), modules={'typing'}) is None
+    >>> _get_name_of_class_if_from_modules(int_node, modules={'typing'}) is None
     True
     """
     if isinstance(classnode, ast.Name):
         return classnode.id
     if isinstance(classnode, ast.Attribute):
         module_node = classnode.value
         if isinstance(module_node, ast.Name) and module_node.id in modules:
@@ -402,22 +400,15 @@
     cls_name = _get_name_of_class_if_from_modules(
         node, modules=_TYPING_MODULES | {"builtins"}
     )
     return cls_name in {"type", "Type"}
 
 
 def _is_None(node: ast.expr) -> bool:
-    # <=3.7: `BaseException | None` parses as:
-    #     BinOp(left=Name(id='BaseException'), op=BitOr(), right=NameConstant(value=None))`
-    # >=3.8: `BaseException | None` parses as
-    #     BinOp(left=Name(id='BaseException'), op=BitOr(), right=Constant(value=None))`
-    #
-    # ast.NameConstant is deprecated in 3.8+, but doesn't raise a DeprecationWarning,
-    # and the isinstance() check still works
-    return isinstance(node, ast.NameConstant) and node.value is None
+    return isinstance(node, ast.Constant) and node.value is None
 
 
 class ExitArgAnalysis(NamedTuple):
     is_union_with_None: bool
     non_None_part: ast.expr | None
 
     def __repr__(self) -> str:
@@ -466,19 +457,21 @@
     return the name of the object.
     Else, return None.
 
     >>> _get_collections_abc_obj_id(_ast_node_for('AsyncIterator[str]'))
     'AsyncIterator'
     >>> _get_collections_abc_obj_id(_ast_node_for('typing.AsyncIterator[str]'))
     'AsyncIterator'
-    >>> _get_collections_abc_obj_id(_ast_node_for('typing_extensions.AsyncIterator[str]'))
+    >>> node = _ast_node_for('typing_extensions.AsyncIterator[str]')
+    >>> _get_collections_abc_obj_id(node)
     'AsyncIterator'
     >>> _get_collections_abc_obj_id(_ast_node_for('collections.abc.AsyncIterator[str]'))
     'AsyncIterator'
-    >>> _get_collections_abc_obj_id(_ast_node_for('collections.OrderedDict[str, int]')) is None
+    >>> node = _ast_node_for('collections.OrderedDict[str, int]')
+    >>> _get_collections_abc_obj_id(node) is None
     True
     """
     if not isinstance(node, ast.Subscript):
         return None
     return _get_name_of_class_if_from_modules(
         node.value, modules=_TYPING_MODULES | {"collections.abc"}
     )
@@ -502,23 +495,24 @@
     }
 )
 
 
 def _has_bad_hardcoded_returns(
     method: ast.FunctionDef | ast.AsyncFunctionDef, *, classdef: ast.ClassDef
 ) -> bool:
-    """Return `True` if `function` should be rewritten using `typing_extensions.Self`."""
+    """Return `True` if `function` should be rewritten with `typing_extensions.Self`."""
     # Much too complex for our purposes to worry
     # about overloaded functions or abstractmethods
     if any(
         _is_overload(deco) or _is_abstractmethod(deco) for deco in method.decorator_list
     ):
         return False
 
-    if not _non_kw_only_args_of(method.args):  # weird, but theoretically possible
+    # weird, but theoretically possible
+    if not method.args.posonlyargs and not method.args.args:
         return False
 
     method_name, returns = method.name, method.returns
 
     if isinstance(method, ast.AsyncFunctionDef):
         return (
             method_name == "__aenter__"
@@ -548,20 +542,22 @@
 
 
 def _unparse_func_node(node: ast.FunctionDef | ast.AsyncFunctionDef) -> str:
     """Unparse a function node, and reformat it to fit on one line."""
     return re.sub(r"\s+", " ", unparse(node))
 
 
-def _is_list_of_str_nodes(seq: list[ast.expr | None]) -> TypeGuard[list[ast.Str]]:
-    return all(isinstance(item, ast.Str) for item in seq)
+def _is_list_of_str_nodes(seq: list[ast.expr | None]) -> TypeGuard[list[ast.Constant]]:
+    return all(
+        isinstance(item, ast.Constant) and type(item.value) is str for item in seq
+    )
 
 
 def _is_bad_TypedDict(node: ast.Call) -> bool:
-    """Evaluate whether an assignment-based TypedDict should be rewritten using class syntax.
+    """Should the assignment-based TypedDict `node` be rewritten using class syntax?
 
     Return `False` if the TypedDict appears as though it may be invalidly defined;
     type-checkers will raise an error in that eventuality.
     """
 
     args = node.args
     if len(args) != 2:
@@ -577,29 +573,22 @@
         return False
 
     typed_dict_fields = typed_dict_annotations.keys
 
     if not _is_list_of_str_nodes(typed_dict_fields):
         return False
 
-    fieldnames = [field.s for field in typed_dict_fields]
+    fieldnames = [field.value for field in typed_dict_fields]
 
     return all(
         fieldname.isidentifier() and not iskeyword(fieldname)
         for fieldname in fieldnames
     )
 
 
-def _non_kw_only_args_of(args: ast.arguments) -> list[ast.arg]:
-    """Return a list containing the pos-only args and pos-or-kwd args of `args`"""
-    # pos-only args don't exist on 3.7
-    pos_only_args: list[ast.arg] = getattr(args, "posonlyargs", [])
-    return pos_only_args + args.args
-
-
 def _is_assignment_which_must_have_a_value(
     target_name: str | None, *, in_class: bool
 ) -> bool:
     return (target_name in {"__match_args__", "__slots__"} and in_class) or (
         target_name == "__all__" and not in_class
     )
 
@@ -615,18 +604,19 @@
     multiple_type_subscripts_in_union: bool
     combined_type_subscripts: list[_SliceContents]
 
 
 def _analyse_union(members: Sequence[ast.expr]) -> UnionAnalysis:
     """Return a tuple providing analysis of a given sequence of union members.
 
-    >>> union = _ast_node_for(
-    ...     'Union[int, memoryview, memoryview, Literal["foo"], Literal[1], type[float], type[str]]'
+    >>> source = 'Union[int, memoryview, memoryview, Literal["foo"], Literal[1], type[float], type[str]]'
+    >>> union = _ast_node_for(source)
+    >>> members = (
+    ...     union.slice.elts if sys.version_info >= (3, 9) else union.slice.value.elts
     ... )
-    >>> members = union.slice.elts if sys.version_info >= (3, 9) else union.slice.value.elts
     >>> analysis = _analyse_union(members)
     >>> len(analysis.members_by_dump["Name(id='memoryview', ctx=Load())"])
     2
     >>> analysis.dupes_in_union
     True
     >>> "int" in analysis.builtins_classes_in_union
     True
@@ -741,21 +731,25 @@
                 )
                 for subnode in chain(node.keys, node.values)
             )
         )
 
     # `...`, bools, None, str, bytes,
     # positive ints, positive floats, positive complex numbers with no real part
-    if isinstance(node, (ast.Ellipsis, ast.NameConstant, ast.Str, ast.Bytes, ast.Num)):
+    if isinstance(node, ast.Constant):
         return True
 
     # Negative ints, negative floats, negative complex numbers with no real part,
     # some constants from the math module
     if isinstance(node, ast.UnaryOp) and isinstance(node.op, ast.USub):
-        if isinstance(node.operand, ast.Num):
+        numeric_types = {int, float, complex}
+        if (
+            isinstance(node.operand, ast.Constant)
+            and type(node.operand.value) in numeric_types
+        ):
             return True
         if isinstance(node.operand, ast.Attribute) and isinstance(
             node.operand.value, ast.Name
         ):
             fullname = f"{node.operand.value.id}.{node.operand.attr}"
             return (
                 fullname in _ALLOWED_MATH_ATTRIBUTES_IN_DEFAULTS
@@ -763,27 +757,27 @@
             )
         return False
 
     # Complex numbers with a real part and an imaginary part...
     if (
         isinstance(node, ast.BinOp)
         and isinstance(node.op, (ast.Add, ast.Sub))
-        and isinstance(node.right, ast.Num)
-        and type(node.right.n) is complex
+        and isinstance(node.right, ast.Constant)
+        and type(node.right.value) is complex
     ):
         left = node.left
         # ...Where the real part is positive:
-        if isinstance(left, ast.Num) and type(left.n) is not complex:
+        if isinstance(left, ast.Constant) and type(left.value) in {int, float}:
             return True
         # ...Where the real part is negative:
         if (
             isinstance(left, ast.UnaryOp)
             and isinstance(left.op, ast.USub)
-            and isinstance(left.operand, ast.Num)
-            and type(left.operand.n) is not complex
+            and isinstance(left.operand, ast.Constant)
+            and type(left.operand.value) in {int, float}
         ):
             return True
         return False
 
     # Special cases
     if isinstance(node, ast.Attribute) and isinstance(node.value, ast.Name):
         fullname = f"{node.value.id}.{node.attr}"
@@ -810,18 +804,16 @@
         and _is_valid_pep_604_union_member(node.right)
     )
 
 
 def _is_valid_default_value_without_annotation(node: ast.expr) -> bool:
     """Is `node` a valid default for an assignment without an annotation?"""
     return (
-        isinstance(
-            node, (ast.Call, ast.Name, ast.Attribute, ast.Subscript, ast.Ellipsis)
-        )
-        or _is_None(node)
+        isinstance(node, (ast.Call, ast.Name, ast.Attribute, ast.Subscript))
+        or (isinstance(node, ast.Constant) and node.value in {None, ...})
         or _is_valid_pep_604_union(node)
     )
 
 
 _KNOWN_ENUM_BASES = frozenset(
     {"Enum", "Flag", "IntEnum", "IntFlag", "StrEnum", "ReprEnum"}
 )
@@ -859,47 +851,72 @@
     @property
     def active(self) -> bool:
         """Determine whether the level of nesting is currently non-zero"""
         return bool(self.nesting)
 
 
 class PyiVisitor(ast.NodeVisitor):
-    def __init__(self, filename: Path | None = None) -> None:
-        self.filename = Path("(none)") if filename is None else filename
-        self.errors: list[Error] = []
-        # Mapping of all private TypeVars/ParamSpecs/TypeVarTuples
-        # to the nodes where they're defined
-        self.typevarlike_defs: dict[TypeVarInfo, ast.Assign] = {}
-        # A list of all private Protocol-definition nodes
-        self.protocol_defs: list[ast.ClassDef] = []
-        # The same for class-based private TypedDicts
-        self.class_based_typeddicts: list[ast.ClassDef] = []
-        # Mapping of private TypedDicts to the nodes where they're defined
-        self.assignment_based_typeddicts: dict[str, ast.Assign] = {}
-        # The same for private TypeAliases
-        self.typealias_decls: dict[str, ast.AnnAssign] = {}
-        # Mapping of each name in the file to the no. of occurrences
-        self.all_name_occurrences: Counter[str] = Counter()
+    filename: str
+    errors: list[Error]
+
+    # Mapping of all private TypeVars/ParamSpecs/TypeVarTuples
+    # to the nodes where they're defined.
+    #
+    # The value type is a list, because any given TypeVar
+    # could have multiple definitions,
+    # e.g. in different sys.version_info branches
+    typevarlike_defs: defaultdict[TypeVarInfo, list[ast.Assign]]
+    # The same for private protocol definitions
+    protocol_defs: defaultdict[str, list[ast.ClassDef]]
+    # The same for class-based private TypedDicts
+    class_based_typeddicts: defaultdict[str, list[ast.ClassDef]]
+    # And for assignment-based TypedDicts
+    assignment_based_typeddicts: defaultdict[str, list[ast.Assign]]
+    # And for private TypeAliases
+    typealias_decls: defaultdict[str, list[_TypeAliasNodeType]]
+
+    # Mapping of each name in the file to the no. of occurrences
+    all_name_occurrences: Counter[str]
+
+    string_literals_allowed: NestingCounter
+    in_function: NestingCounter
+    in_class: NestingCounter
+    visiting_arg: NestingCounter
+
+    # This is only relevant for visiting classes
+    current_class_node: ast.ClassDef | None = None
+
+    def __init__(self, filename: str) -> None:
+        self.filename = filename
+        self.errors = []
+        self.typevarlike_defs = defaultdict(list)
+        self.protocol_defs = defaultdict(list)
+        self.class_based_typeddicts = defaultdict(list)
+        self.assignment_based_typeddicts = defaultdict(list)
+        self.typealias_decls = defaultdict(list)
+        self.all_name_occurrences = Counter()
         self.string_literals_allowed = NestingCounter()
         self.in_function = NestingCounter()
         self.in_class = NestingCounter()
         self.visiting_arg = NestingCounter()
-        # This is only relevant for visiting classes
-        self.current_class_node: ast.ClassDef | None = None
 
     def __repr__(self) -> str:
         return f"{self.__class__.__name__}(filename={self.filename!r})"
 
     def _check_import_or_attribute(
         self, node: ast.Attribute | ast.ImportFrom, module_name: str, object_name: str
     ) -> None:
         fullname = f"{module_name}.{object_name}"
 
+        # Y057 errors
+        if fullname in {"typing.ByteString", "collections.abc.ByteString"}:
+            error_message = Y057.format(module=module_name)
+
         # Y022 errors
-        if fullname in _BAD_Y022_IMPORTS:
+        elif fullname in _BAD_Y022_IMPORTS:
             good_cls_name, slice_contents = _BAD_Y022_IMPORTS[fullname]
             params = "" if slice_contents is None else f"[{slice_contents}]"
             error_message = Y022.format(
                 good_syntax=f'"{good_cls_name}{params}"',
                 bad_syntax=f'"{fullname}{params}"',
             )
 
@@ -939,44 +956,39 @@
         else:
             return
 
         self.error(node, error_message)
 
     def visit_Attribute(self, node: ast.Attribute) -> None:
         self.generic_visit(node)
-        thing = node.value
-        if not isinstance(thing, ast.Name):
-            return
-
         self._check_import_or_attribute(
-            node=node, module_name=thing.id, object_name=node.attr
+            node=node, module_name=unparse(node.value), object_name=node.attr
         )
 
     def visit_ImportFrom(self, node: ast.ImportFrom) -> None:
         self.generic_visit(node)
         module_name = node.module
 
         if module_name is None:
             return
 
         imported_names = {obj.name: obj for obj in node.names}
 
-        if module_name == "collections.abc":
-            if (
-                "Set" in imported_names
-                and imported_names["Set"].asname != "AbstractSet"
-            ):
-                self.error(node, Y025)
-            return
-
         if module_name == "__future__":
             if "annotations" in imported_names:
                 self.error(node, Y044)
             return
 
+        if (
+            module_name == "collections.abc"
+            and "Set" in imported_names
+            and imported_names["Set"].asname != "AbstractSet"
+        ):
+            self.error(node, Y025)
+
         for object_name in imported_names:
             self._check_import_or_attribute(node, module_name, object_name)
 
         if module_name == "typing" and "AbstractSet" in imported_names:
             self.error(node, Y038)
 
     def _check_for_typevarlike_assignments(
@@ -989,15 +1001,15 @@
         in the file in which they are defined.
         """
         cls_name = _get_name_of_class_if_from_modules(function, modules=_TYPING_MODULES)
 
         if cls_name in {"TypeVar", "ParamSpec", "TypeVarTuple"}:
             if object_name.startswith("_"):
                 target_info = TypeVarInfo(cls_name=cls_name, name=object_name)
-                self.typevarlike_defs[target_info] = node
+                self.typevarlike_defs[target_info].append(node)
             else:
                 self.error(node, Y001.format(cls_name))
 
     def _check_default_value_without_type_annotation(
         self, node: ast.Assign, assignment: ast.expr, target_name: str
     ) -> None:
         if _is_valid_default_value_without_annotation(assignment):
@@ -1043,15 +1055,15 @@
         if target_name is None:
             return
         assert isinstance(target, ast.Name)
         if isinstance(assignment, ast.Call):
             function = assignment.func
             if _is_TypedDict(function):
                 if target_name.startswith("_"):
-                    self.assignment_based_typeddicts[target_name] = node
+                    self.assignment_based_typeddicts[target_name].append(node)
             else:
                 self._check_for_typevarlike_assignments(
                     node=node, function=function, object_name=target_name
                 )
             return
 
         if not is_special_assignment:
@@ -1121,78 +1133,57 @@
         elif (
             isinstance(function, ast.Attribute)
             and isinstance(function.value, ast.Name)
             and function.value.id == "__all__"
         ):
             return self.error(node, Y056.format(method=f".{function.attr}()"))
 
-        # String literals can appear in positional arguments for
-        # TypeVar definitions.
-        with self.string_literals_allowed.enabled():
-            for arg in node.args:
-                self.visit(arg)
-        # But in keyword arguments they're most likely TypeVar bounds,
+        # String literals can appear as the first positional argument for
+        # TypeVar/ParamSpec/TypeVarTuple/NamedTuple/TypedDict/NewType definitions, etc.
+        if node.args:
+            with self.string_literals_allowed.enabled():
+                self.visit(node.args[0])
+        # But in other arguments they're most likely TypeVar bounds,
         # which should not be quoted.
-        for kw in node.keywords:
-            self.visit(kw)
-
-    def _check_for_Y053(self, node: ast.Constant | ast.Str | ast.Bytes) -> None:
-        if len(node.s) > 50:
-            self.error(node, Y053)
-
-    def _check_for_Y054(self, node: ast.Constant | ast.Num) -> None:
-        # The maximum character limit is arbitrary, but here's what it's based on:
-        # Hex representation of 32-bit integers tend to be 10 chars.
-        # So is the decimal representation of the maximum positive signed 32-bit integer.
-        # 0xFFFFFFFF --> 4294967295
-        if len(str(node.n)) > 10:
-            self.error(node, Y054)
+        for arg in chain(node.args[1:], node.keywords):
+            self.visit(arg)
 
-    # 3.8+
     def visit_Constant(self, node: ast.Constant) -> None:
         if isinstance(node.value, str) and not self.string_literals_allowed.active:
             self.error(node, Y020)
         elif isinstance(node.value, (str, bytes)):
-            self._check_for_Y053(node)
+            if len(node.value) > 50:
+                self.error(node, Y053)
         elif isinstance(node.value, (int, float, complex)):
-            self._check_for_Y054(node)
-
-    # 3.7
-    def visit_Str(self, node: ast.Str) -> None:
-        if self.string_literals_allowed.active:
-            self._check_for_Y053(node)
-        else:
-            self.error(node, Y020)
-
-    # 3.7
-    def visit_Bytes(self, node: ast.Bytes) -> None:
-        self._check_for_Y053(node)
-
-    # 3.7
-    def visit_Num(self, node: ast.Num) -> None:
-        self._check_for_Y054(node)
+            if len(str(node.value)) > 10:
+                # The maximum character limit is arbitrary, but here's what it's based on:
+                # Hex representation of 32-bit integers tend to be 10 chars.
+                # So is the decimal representation
+                # of the maximum positive signed 32-bit integer.
+                # 0xFFFFFFFF --> 4294967295
+                self.error(node, Y054)
 
     def visit_Expr(self, node: ast.Expr) -> None:
-        if isinstance(node.value, ast.Str):
+        if isinstance(node.value, ast.Constant) and isinstance(node.value.value, str):
             self.error(node, Y021)
         else:
             self.generic_visit(node)
 
     _Y042_REGEX = re.compile(r"^_?[a-z]")
 
     # Y043: Error for alias names in "T"
     # (plus possibly a single digit afterwards), but only if:
     #
     # - The name starts with "_"
     # - The penultimate character in the name is an ASCII-lowercase letter
     _Y043_REGEX = re.compile(r"^_.*[a-z]T\d?$")
 
-    def _check_typealias(self, node: ast.AnnAssign, alias_name: str) -> None:
+    def _check_typealias(self, node: _TypeAliasNodeType, alias_name: str) -> None:
         if alias_name.startswith("_"):
-            self.typealias_decls[alias_name] = node
+            self.typealias_decls[alias_name].append(node)
         if self._Y042_REGEX.match(alias_name):
             self.error(node, Y042)
         if self._Y043_REGEX.match(alias_name):
             self.error(node, Y043)
 
     def visit_AnnAssign(self, node: ast.AnnAssign) -> None:
         node_annotation = node.annotation
@@ -1236,14 +1227,20 @@
             node_value, (ast.Attribute, ast.Name)
         ):
             return
 
         if node_value and not _is_valid_default_value_with_annotation(node_value):
             self.error(node, Y015)
 
+    if sys.version_info >= (3, 12):
+
+        def visit_TypeAlias(self, node: ast.TypeAlias) -> None:
+            self.generic_visit(node)
+            self._check_typealias(node=node, alias_name=node.name.id)
+
     def _check_union_members(
         self, members: Sequence[ast.expr], is_pep_604_union: bool
     ) -> None:
         first_union_member = members[0]
         analysis = _analyse_union(members)
 
         for member_list in analysis.members_by_dump.values():
@@ -1258,28 +1255,24 @@
                 self._error_for_multiple_type_subscripts_in_union(
                     first_union_member, analysis, is_pep_604_union
                 )
             if self.visiting_arg.active:
                 self._check_for_redundant_numeric_unions(first_union_member, analysis)
 
     def _check_for_Y051_violations(self, analysis: UnionAnalysis) -> None:
-        """Search for redundant unions fitting the pattern `str | Literal["foo"]`, etc."""
+        """Search for redundant unions such as `str | Literal["foo"]`, etc."""
         literal_classes_present: defaultdict[str, list[_SliceContents]]
         literal_classes_present = defaultdict(list)
         for literal in analysis.combined_literal_members:
-            if isinstance(literal, ast.Str):
-                literal_classes_present["str"].append(literal)
-            elif isinstance(literal, ast.Bytes):
-                literal_classes_present["bytes"].append(literal)
-            elif isinstance(literal, ast.Num):
-                if type(literal.n) is int:
-                    literal_classes_present["int"].append(literal)
-            elif isinstance(literal, ast.NameConstant):
-                if type(literal.value) is bool:
-                    literal_classes_present["bool"].append(literal)
+            interesting_builtins = {str, bytes, int, bool}
+            if (
+                isinstance(literal, ast.Constant)
+                and type(literal.value) in interesting_builtins
+            ):
+                literal_classes_present[type(literal.value).__name__].append(literal)
         for cls, literals in literal_classes_present.items():
             if cls in analysis.builtins_classes_in_union:
                 first_literal_present = literals[0]
                 self.error(
                     first_literal_present,
                     Y051.format(
                         literal_subtype=f"Literal[{unparse(first_literal_present)}]",
@@ -1434,33 +1427,32 @@
         # unless this is on, comparisons against a single integer aren't allowed
         must_be_single = False
         # if strict equality is allowed, it must be against a tuple of this length
         can_have_strict_equals: int | None = None
         version_info = node.left
         if isinstance(version_info, ast.Subscript):
             slc = version_info.slice
-            # TODO: ast.Num works, but is deprecated
-            if isinstance(slc, ast.Num):
+            if isinstance(slc, ast.Constant):
                 # anything other than the integer 0 doesn't make much sense
-                if isinstance(slc.n, int) and slc.n == 0:
+                if type(slc.value) is int and slc.value == 0:
                     must_be_single = True
                 else:
                     self.error(node, Y003)
                     return
             elif isinstance(slc, ast.Slice):
                 if slc.lower is not None or slc.step is not None:
                     self.error(node, Y003)
                     return
                 elif (
                     # allow only [:1] and [:2]
-                    isinstance(slc.upper, ast.Num)
-                    and isinstance(slc.upper.n, int)
-                    and slc.upper.n in (1, 2)
+                    isinstance(slc.upper, ast.Constant)
+                    and type(slc.upper.value) is int
+                    and slc.upper.value in {1, 2}
                 ):
-                    can_have_strict_equals = slc.upper.n
+                    can_have_strict_equals = slc.upper.value
                 else:
                     self.error(node, Y003)
                     return
             else:
                 # extended slicing
                 self.error(node, Y003)
                 return
@@ -1475,20 +1467,26 @@
         node: ast.Compare,
         *,
         must_be_single: bool = False,
         can_have_strict_equals: int | None = None,
     ) -> None:
         comparator = node.comparators[0]
         if must_be_single:
-            if not isinstance(comparator, ast.Num) or not isinstance(comparator.n, int):
+            if (
+                not isinstance(comparator, ast.Constant)
+                or type(comparator.value) is not int
+            ):
                 self.error(node, Y003)
         elif not isinstance(comparator, ast.Tuple):
             self.error(node, Y003)
         else:
-            if not all(isinstance(elt, ast.Num) for elt in comparator.elts):
+            if not all(
+                isinstance(elt, ast.Constant) and type(elt.value) is int
+                for elt in comparator.elts
+            ):
                 self.error(node, Y003)
             elif len(comparator.elts) > 2:
                 # mypy only supports major and minor version checks
                 self.error(node, Y004)
 
             cmpop = node.ops[0]
             if isinstance(cmpop, (ast.Lt, ast.GtE)):
@@ -1506,67 +1504,71 @@
         cmpop = node.ops[0]
         # "in" might also make sense but we don't currently have one
         if not isinstance(cmpop, (ast.Eq, ast.NotEq)):
             self.error(node, Y007)
             return
 
         comparator = node.comparators[0]
-        if isinstance(comparator, ast.Str):
+        if isinstance(comparator, ast.Constant) and type(comparator.value) is str:
             # other values are possible but we don't need them right now
             # this protects against typos
-            if comparator.s not in ("linux", "win32", "cygwin", "darwin"):
-                self.error(node, Y008.format(platform=comparator.s))
+            if comparator.value not in {"linux", "win32", "cygwin", "darwin"}:
+                self.error(node, Y008.format(platform=comparator.value))
         else:
             self.error(node, Y007)
 
     def visit_ClassDef(self, node: ast.ClassDef) -> None:
         if node.name.startswith("_") and not self.in_class.active:
             for base in node.bases:
                 if _is_Protocol(base):
-                    self.protocol_defs.append(node)
+                    self.protocol_defs[node.name].append(node)
                     break
                 if _is_TypedDict(base):
-                    self.class_based_typeddicts.append(node)
+                    self.class_based_typeddicts[node.name].append(node)
                     break
 
         old_class_node = self.current_class_node
         self.current_class_node = node
         with self.in_class.enabled():
             self.generic_visit(node)
         self.current_class_node = old_class_node
 
         if any(_is_builtins_object(base_node) for base_node in node.bases):
             self.error(node, Y040)
 
         # empty class body should contain "..." not "pass"
         if len(node.body) == 1:
             statement = node.body[0]
-            if isinstance(statement, ast.Expr) and isinstance(
-                statement.value, ast.Ellipsis
+            if (
+                isinstance(statement, ast.Expr)
+                and isinstance(statement.value, ast.Constant)
+                and statement.value.value is ...
             ):
                 return
             elif isinstance(statement, ast.Pass):
                 self.error(statement, Y009)
                 return
 
         for statement in node.body:
             # "pass" should not used in class body
             if isinstance(statement, ast.Pass):
                 self.error(statement, Y012)
             # "..." should not be used in non-empty class body
-            elif isinstance(statement, ast.Expr) and isinstance(
-                statement.value, ast.Ellipsis
+            elif (
+                isinstance(statement, ast.Expr)
+                and isinstance(statement.value, ast.Constant)
+                and statement.value.value is ...
             ):
                 self.error(statement, Y013)
 
     def _check_exit_method(  # noqa: C901
         self, node: ast.FunctionDef | ast.AsyncFunctionDef, method_name: str
     ) -> None:
         all_args = node.args
-        non_kw_only_args = _non_kw_only_args_of(all_args)
+        non_kw_only_args = all_args.posonlyargs + all_args.args
         num_args = len(non_kw_only_args)
         varargs = all_args.vararg
 
         def error_for_bad_exit_method(details: str) -> None:
             self.error(node, Y036.format(method_name=method_name, details=details))
 
         if num_args < 4:
@@ -1724,15 +1726,15 @@
 
         if method_name in {"__exit__", "__aexit__"}:
             return self._check_exit_method(node=node, method_name=method_name)
 
         if all_args.kwonlyargs:
             return
 
-        non_kw_only_args = _non_kw_only_args_of(all_args)
+        non_kw_only_args = all_args.posonlyargs + all_args.args
 
         # Raise an error for defining __str__ or __repr__ on a class, but only if:
         # 1). The method is not decorated with @abstractmethod
         # 2). The method has the exact same signature as object.__str__/object.__repr__
         if method_name in {"__repr__", "__str__"}:
             if (
                 len(non_kw_only_args) == 1
@@ -1762,24 +1764,37 @@
         self._visit_function(node)
 
     def _Y019_error(
         self, node: ast.FunctionDef | ast.AsyncFunctionDef, typevar_name: str
     ) -> None:
         cleaned_method = deepcopy(node)
         cleaned_method.decorator_list.clear()
-        first_arg = _non_kw_only_args_of(cleaned_method.args)[0]
-        first_arg.annotation = None
+        if sys.version_info >= (3, 12):
+            cleaned_method.type_params = [
+                param
+                for param in cleaned_method.type_params
+                if not (isinstance(param, ast.TypeVar) and param.name == typevar_name)
+            ]
+        non_kw_only_args = cleaned_method.args.posonlyargs + cleaned_method.args.args
+        non_kw_only_args[0].annotation = None
         new_syntax = _unparse_func_node(cleaned_method)
         new_syntax = re.sub(rf"\b{typevar_name}\b", "Self", new_syntax)
-        self.error(
-            # pass the node for the first argument to `self.error`,
-            # rather than the function node,
-            # as linenos differ in Python 3.7 and 3.8+ for decorated functions
-            node.args.args[0],
-            Y019.format(typevar_name=typevar_name, new_syntax=new_syntax),
+        self.error(node, Y019.format(typevar_name=typevar_name, new_syntax=new_syntax))
+
+    @staticmethod
+    def _is_likely_private_typevar(
+        method: ast.FunctionDef | ast.AsyncFunctionDef, tvar_name: str
+    ) -> bool:
+        if tvar_name.startswith("_"):
+            return True
+        if sys.version_info < (3, 12):
+            return False
+        return any(  # type: ignore[unreachable]
+            isinstance(param, ast.TypeVar) and param.name == tvar_name
+            for param in method.type_params
         )
 
     def _check_instance_method_for_bad_typevars(
         self,
         *,
         method: ast.FunctionDef | ast.AsyncFunctionDef,
         first_arg_annotation: ast.Name | ast.Subscript,
@@ -1789,15 +1804,15 @@
             return
 
         if first_arg_annotation.id != return_annotation.id:
             return
 
         arg1_annotation_name = first_arg_annotation.id
 
-        if arg1_annotation_name.startswith("_"):
+        if self._is_likely_private_typevar(method, arg1_annotation_name):
             self._Y019_error(method, arg1_annotation_name)
 
     def _check_class_method_for_bad_typevars(
         self,
         *,
         method: ast.FunctionDef | ast.AsyncFunctionDef,
         first_arg_annotation: ast.Name | ast.Subscript,
@@ -1813,15 +1828,17 @@
 
         # Don't error if the first argument is annotated
         # with `builtins.type[T]` or `typing.Type[T]`
         # These are edge cases, and it's hard to give good error messages for them.
         if not _is_name(first_arg_annotation.value, "type"):
             return
 
-        if cls_typevar == return_annotation.id and cls_typevar.startswith("_"):
+        if cls_typevar == return_annotation.id and self._is_likely_private_typevar(
+            method, cls_typevar
+        ):
             self._Y019_error(method, cls_typevar)
 
     def check_self_typevars(self, node: ast.FunctionDef | ast.AsyncFunctionDef) -> None:
         pos_or_keyword_args = node.args.args
 
         if not pos_or_keyword_args:
             return
@@ -1863,33 +1880,34 @@
         if len(body) > 1:
             self.error(body[1], Y048)
         elif body:
             statement = body[0]
             # normally, should just be "..."
             if isinstance(statement, ast.Pass):
                 self.error(statement, Y009)
-            # Ellipsis is fine. Str (docstrings) is not but we produce
-            # tailored error message for it elsewhere.
+            # ... is fine. Docstrings are not but we produce
+            # tailored error message for them elsewhere.
             elif not (
                 isinstance(statement, ast.Expr)
-                and isinstance(statement.value, (ast.Ellipsis, ast.Str))
+                and isinstance(statement.value, ast.Constant)
+                and isinstance(statement.value.value, (str, type(...)))
             ):
                 self.error(statement, Y010)
 
         if self.in_class.active:
             self.check_self_typevars(node)
 
     def visit_arg(self, node: ast.arg) -> None:
         if _is_NoReturn(node.annotation):
             self.error(node, Y050)
         with self.visiting_arg.enabled():
             self.generic_visit(node)
 
     def visit_arguments(self, node: ast.arguments) -> None:
-        args = _non_kw_only_args_of(node)
+        args = node.posonlyargs + node.args
         defaults = [None] * (len(args) - len(node.defaults)) + node.defaults
         assert len(args) == len(defaults)
         for arg, default in zip(args, defaults):
             self.check_arg_default(arg, default)
         if node.vararg is not None:
             self.visit(node.vararg)
         for arg, default in zip_longest(node.kwonlyargs, node.kw_defaults):
@@ -1917,115 +1935,92 @@
         - TypeVars
         - ParamSpecs
         - TypeVarTuples
         - Aliases
         - Protocols
         - TypedDicts
         """
-        for (cls_name, typevar_name), def_node in self.typevarlike_defs.items():
-            if self.all_name_occurrences[typevar_name] == 1:
-                self.error(
-                    def_node,
-                    Y018.format(typevarlike_cls=cls_name, typevar_name=typevar_name),
-                )
-        for protocol in self.protocol_defs:
-            if self.all_name_occurrences[protocol.name] == 0:
-                self.error(protocol, Y046.format(protocol_name=protocol.name))
-        for class_based_typeddict in self.class_based_typeddicts:
-            cls_name = class_based_typeddict.name
-            if self.all_name_occurrences[cls_name] == 0:
-                self.error(class_based_typeddict, Y049.format(typeddict_name=cls_name))
-        for td_name, td_node in self.assignment_based_typeddicts.items():
-            if self.all_name_occurrences[td_name] == 1:
-                self.error(td_node, Y049.format(typeddict_name=td_name))
-        for alias_name, alias in self.typealias_decls.items():
-            if self.all_name_occurrences[alias_name] == 1:
-                self.error(alias, Y047.format(alias_name=alias_name))
+        for (cls_name, typevar_name), tv_nodelist in self.typevarlike_defs.items():
+            if self.all_name_occurrences[typevar_name] == len(tv_nodelist):
+                msg = Y018.format(typevarlike_cls=cls_name, typevar_name=typevar_name)
+                self.error(tv_nodelist[0], msg)
+        for proto_name, proto_nodelist in self.protocol_defs.items():
+            if self.all_name_occurrences[proto_name] == 0:
+                self.error(proto_nodelist[0], Y046.format(protocol_name=proto_name))
+        for td_name, cls_td_nodelist in self.class_based_typeddicts.items():
+            if self.all_name_occurrences[td_name] == 0:
+                self.error(cls_td_nodelist[0], Y049.format(typeddict_name=td_name))
+        for td_name, ass_td_nodelist in self.assignment_based_typeddicts.items():
+            if self.all_name_occurrences[td_name] == len(ass_td_nodelist):
+                self.error(ass_td_nodelist[0], Y049.format(typeddict_name=td_name))
+        for alias_name, alias_nodelist in self.typealias_decls.items():
+            if self.all_name_occurrences[alias_name] == len(alias_nodelist):
+                self.error(alias_nodelist[0], Y047.format(alias_name=alias_name))
 
     def run(self, tree: ast.AST) -> Iterator[Error]:
         self.visit(tree)
         self._check_for_unused_things()
         yield from self.errors
 
 
 _TYPE_COMMENT_REGEX = re.compile(r"#\s*type:\s*(?!\s?ignore)([^#]+)(\s*#.*?)?$")
 
 
-def _check_for_type_comments(path: Path) -> Iterator[Error]:
-    stublines = path.read_text(encoding="UTF-8").splitlines()
-    for lineno, line in enumerate(stublines, start=1):
+def _check_for_type_comments(lines: list[str]) -> Iterator[Error]:
+    for lineno, line in enumerate(lines, start=1):
         cleaned_line = line.strip()
 
         if cleaned_line.startswith("#"):
             continue
 
-        match = _TYPE_COMMENT_REGEX.search(cleaned_line)
-        if not match:
-            continue
+        if match := _TYPE_COMMENT_REGEX.search(cleaned_line):
+            type_comment = match.group(1).strip()
 
-        type_comment = match.group(1).strip()
+            try:
+                ast.parse(type_comment)
+            except SyntaxError:
+                continue
 
-        try:
-            ast.parse(type_comment)
-        except SyntaxError:
-            continue
-
-        yield Error(lineno, 0, Y033, PyiTreeChecker)
+            yield Error(lineno, 0, Y033, PyiTreeChecker)
 
 
 @dataclass
 class PyiTreeChecker:
     name: ClassVar[str] = "flake8-pyi"
     version: ClassVar[str] = __version__
 
-    tree: ast.Module | None = None
+    tree: ast.Module
+    lines: list[str]
     filename: str = "(none)"
-    options: argparse.Namespace | None = None
 
     def run(self) -> Iterable[Error]:
-        assert self.tree is not None
-        path = Path(self.filename)
-        if path.suffix == ".pyi":
-            yield from _check_for_type_comments(path)
+        if self.filename.endswith(".pyi"):
+            yield from _check_for_type_comments(self.lines)
             tree = LegacyNormalizer().visit(self.tree)
-            yield from PyiVisitor(filename=path).run(tree)
+            yield from PyiVisitor(filename=self.filename).run(tree)
 
-    @classmethod
-    def add_options(cls, parser: OptionManager) -> None:
+    @staticmethod
+    def add_options(parser: OptionManager) -> None:
         """This is brittle, there's multiple levels of caching of defaults."""
-        if isinstance(parser.parser, argparse.ArgumentParser):
-            parser.parser.set_defaults(filename="*.py,*.pyi")
-        else:
-            for option in parser.options:
-                if option.long_option_name == "--filename":
-                    option.default = "*.py,*.pyi"
-                    option.option_kwargs["default"] = option.default
-                    option.to_optparse().default = option.default
-                    parser.parser.defaults[option.dest] = option.default
-
-        with suppress(optparse.OptionConflictError):
-            # In tests, sometimes this option gets called twice for some reason.
-            parser.add_option(
-                "--no-pyi-aware-file-checker",
-                default=False,
-                action="store_true",
-                parse_from_config=True,
-                help="don't patch flake8 with .pyi-aware file checker",
-            )
+        parser.parser.set_defaults(filename="*.py,*.pyi")
+        parser.add_option(
+            "--no-pyi-aware-file-checker",
+            default=False,
+            action="store_true",
+            parse_from_config=True,
+            help="don't patch flake8 with .pyi-aware file checker",
+        )
 
-    @classmethod
-    def parse_options(
-        cls, optmanager: OptionManager, options: argparse.Namespace, extra_args
-    ) -> None:
-        """This is also brittle, only checked with flake8 3.2.1 and master."""
+    @staticmethod
+    def parse_options(options: argparse.Namespace) -> None:
         if not options.no_pyi_aware_file_checker:
             checker.FileChecker = PyiAwareFileChecker
 
 
-# Please keep error code lists in README and CHANGELOG up to date
+# Please keep error code lists in ERRORCODES and CHANGELOG up to date
 Y001 = "Y001 Name of private {} must start with _"
 Y002 = (
     "Y002 If test must be a simple comparison against sys.platform or sys.version_info"
 )
 Y003 = "Y003 Unrecognized sys.version_info check"
 Y004 = "Y004 Version comparison must use only major and minor version"
 Y005 = "Y005 Version comparison must be against a length-{n} tuple"
@@ -2064,15 +2059,16 @@
 )
 Y033 = (
     "Y033 Do not use type comments in stubs "
     '(e.g. use "x: int" instead of "x = ... # type: int")'
 )
 Y034 = (
     'Y034 {methods} usually return "self" at runtime. '
-    'Consider using "typing_extensions.Self" in "{method_name}", e.g. "{suggested_syntax}"'
+    'Consider using "typing_extensions.Self" in "{method_name}", '
+    'e.g. "{suggested_syntax}"'
 )
 Y035 = (
     'Y035 "{var}" in a stub file must have a value, '
     'as it has the same semantics as "{var}" at runtime.'
 )
 Y036 = "Y036 Badly defined {method_name} method: {details}"
 Y037 = "Y037 Use PEP 604 union types instead of {old_syntax} (e.g. {example})."
@@ -2106,7 +2102,10 @@
     ">10 characters long are not permitted"
 )
 Y055 = 'Y055 Multiple "type[Foo]" members in a union. {suggestion}'
 Y056 = (
     'Y056 Calling "{method}" on "__all__" may not be supported by all type checkers '
     "(use += instead)"
 )
+Y057 = (
+    "Y057 Do not use {module}.ByteString, which has unclear semantics and is deprecated"
+)
```

### Comparing `flake8_pyi-23.5.0/.github/scripts/typeshed_primer_download_errors.js` & `flake8_pyi-23.6.0/.github/scripts/typeshed_primer_download_errors.js`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/.github/scripts/typeshed_primer_post_comment.js` & `flake8_pyi-23.6.0/.github/scripts/typeshed_primer_post_comment.js`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/.github/workflows/check.yml` & `flake8_pyi-23.6.0/.github/workflows/check.yml`

 * *Files 5% similar despite different names*

```diff
@@ -1,14 +1,16 @@
 name: tests
 
 on:
   push:
     branches:
       - main
   pull_request:
+    paths-ignore:
+      - "**/*.md"
   workflow_dispatch:
 
 permissions:
   contents: read
 
 env:
   PIP_DISABLE_PIP_VERSION_CHECK: 1
@@ -23,15 +25,15 @@
 jobs:
   mypy:
     name: mypy
     runs-on: ubuntu-latest
     timeout-minutes: 5
     strategy:
       matrix:
-        python-version: ["3.7", "3.11"]
+        python-version: ["3.8", "3.11"]
       fail-fast: false
     steps:
       - uses: actions/checkout@v3
       - uses: actions/setup-python@v4
         with:
           python-version: ${{ matrix.python-version }}
           cache: pip
@@ -57,18 +59,19 @@
   tests:
     name: pytest suite
     timeout-minutes: 10
     runs-on: ${{ matrix.os }}
     strategy:
       matrix:
         os: ["ubuntu-latest", "macos-latest", "windows-latest"]
-        python-version: ["3.7", "3.8", "3.9", "3.10", "3.11"]
+        python-version: ["3.8", "3.9", "3.10", "3.11", "3.12"]
       fail-fast: false
     steps:
       - uses: actions/checkout@v3
       - uses: actions/setup-python@v4
         with:
           python-version: ${{ matrix.python-version }}
+          allow-prereleases: true
           cache: pip
           cache-dependency-path: pyproject.toml
       - run: pip install -e .[dev]
       - run: python3 -m pytest -vv
```

### Comparing `flake8_pyi-23.5.0/.github/workflows/publish.yml` & `flake8_pyi-23.6.0/.github/workflows/publish.yml`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/.github/workflows/typeshed_primer.yml` & `flake8_pyi-23.6.0/.github/workflows/typeshed_primer.yml`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,14 @@
 name: typeshed_primer
 
 on:
   pull_request:
+    paths:
+      - "pyi.py"
+      - ".github/**/*"
   workflow_dispatch:
 
 permissions:
   contents: read
 
 env:
   PIP_DISABLE_PIP_VERSION_CHECK: 1
```

### Comparing `flake8_pyi-23.5.0/.github/workflows/typeshed_primer_comment.yml` & `flake8_pyi-23.6.0/.github/workflows/typeshed_primer_comment.yml`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/tests/aliases.pyi` & `flake8_pyi-23.6.0/tests/aliases.pyi`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/tests/attribute_annotations.pyi` & `flake8_pyi-23.6.0/tests/attribute_annotations.pyi`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/tests/calls.pyi` & `flake8_pyi-23.6.0/tests/calls.pyi`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/tests/classdefs.pyi` & `flake8_pyi-23.6.0/tests/classdefs.pyi`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/tests/defaults.pyi` & `flake8_pyi-23.6.0/tests/defaults.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -70,7 +70,14 @@
 def f36(x: str = sys.winver) -> None: ...
 
 def f37(x: str = "a_very_long_stringgggggggggggggggggggggggggggggggggggggggggggggg") -> None: ...  # Y053 String and bytes literals >50 characters long are not permitted
 def f38(x: bytes = b"a_very_long_byte_stringggggggggggggggggggggggggggggggggggggg") -> None: ...  # Y053 String and bytes literals >50 characters long are not permitted
 
 foo: str = "a_very_long_stringgggggggggggggggggggggggggggggggggggggggggggggg"  # Y053 String and bytes literals >50 characters long are not permitted
 bar: bytes = b"a_very_long_byte_stringggggggggggggggggggggggggggggggggggggg"  # Y053 String and bytes literals >50 characters long are not permitted
+
+# Tests for PEP-570 syntax
+def f39(x: "int", /) -> None: ...  # Y020 Quoted annotations should never be used in stubs
+def f40(x: int, /) -> None: ...
+def f41(x: int, /, y: "int") -> None: ...  # Y020 Quoted annotations should never be used in stubs
+def f42(x: str = "y", /) -> None: ...
+def f43(x: str = os.pathsep, /) -> None: ...  # Y011 Only simple default values allowed for typed arguments
```

### Comparing `flake8_pyi-23.5.0/tests/emptyfunctions.pyi` & `flake8_pyi-23.6.0/tests/emptyfunctions.pyi`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/tests/exit_methods.pyi` & `flake8_pyi-23.6.0/tests/exit_methods.pyi`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/tests/forward_refs_annassign.pyi` & `flake8_pyi-23.6.0/tests/forward_refs_annassign.pyi`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/tests/imports.pyi` & `flake8_pyi-23.6.0/tests/imports.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -33,15 +33,14 @@
     MutableMapping,
     MappingView,
     KeysView,
     ItemsView,
     ValuesView,
     Sequence,
     MutableSequence,
-    ByteString
 )
 from re import Match, Pattern
 # Things that are of no use for stub files are intentionally omitted.
 from typing import (
     Any,
     ClassVar,
     Generic,
@@ -89,15 +88,14 @@
 from typing_extensions import ContextManager  # Y022 Use "contextlib.AbstractContextManager[T]" instead of "typing_extensions.ContextManager[T]" (PEP 585 syntax)
 from typing_extensions import AsyncGenerator  # Y022 Use "collections.abc.AsyncGenerator[YieldType, SendType]" instead of "typing_extensions.AsyncGenerator[YieldType, SendType]" (PEP 585 syntax)
 from typing_extensions import Coroutine  # Y022 Use "collections.abc.Coroutine[YieldType, SendType, ReturnType]" instead of "typing_extensions.Coroutine[YieldType, SendType, ReturnType]" (PEP 585 syntax)
 from typing import ContextManager  # Y022 Use "contextlib.AbstractContextManager[T]" instead of "typing.ContextManager[T]" (PEP 585 syntax)
 from typing import OrderedDict  # Y022 Use "collections.OrderedDict[KeyType, ValueType]" instead of "typing.OrderedDict[KeyType, ValueType]" (PEP 585 syntax)
 from typing_extensions import OrderedDict  # Y022 Use "collections.OrderedDict[KeyType, ValueType]" instead of "typing_extensions.OrderedDict[KeyType, ValueType]" (PEP 585 syntax)
 from typing import Callable  # Y022 Use "collections.abc.Callable" instead of "typing.Callable" (PEP 585 syntax)
-from typing import ByteString  # Y022 Use "collections.abc.ByteString" instead of "typing.ByteString" (PEP 585 syntax)
 from typing import Container  # Y022 Use "collections.abc.Container[T]" instead of "typing.Container[T]" (PEP 585 syntax)
 from typing import Hashable  # Y022 Use "collections.abc.Hashable" instead of "typing.Hashable" (PEP 585 syntax)
 from typing import ItemsView  # Y022 Use "collections.abc.ItemsView[KeyType, ValueType]" instead of "typing.ItemsView[KeyType, ValueType]" (PEP 585 syntax)
 from typing import Iterable  # Y022 Use "collections.abc.Iterable[T]" instead of "typing.Iterable[T]" (PEP 585 syntax)
 from typing import Iterator  # Y022 Use "collections.abc.Iterator[T]" instead of "typing.Iterator[T]" (PEP 585 syntax)
 from typing import KeysView  # Y022 Use "collections.abc.KeysView[KeyType]" instead of "typing.KeysView[KeyType]" (PEP 585 syntax)
 from typing import Mapping  # Y022 Use "collections.abc.Mapping[KeyType, ValueType]" instead of "typing.Mapping[KeyType, ValueType]" (PEP 585 syntax)
@@ -124,14 +122,16 @@
 from typing_extensions import runtime_checkable  # Y023 Use "typing.runtime_checkable" instead of "typing_extensions.runtime_checkable"
 
 # BAD IMPORTS: OTHER
 from collections import namedtuple  # Y024 Use "typing.NamedTuple" instead of "collections.namedtuple"
 from collections.abc import Set  # Y025 Use "from collections.abc import Set as AbstractSet" to avoid confusion with "builtins.set"
 from typing import AbstractSet  # Y038 Use "from collections.abc import Set as AbstractSet" instead of "from typing import AbstractSet" (PEP 585 syntax)
 from typing import Text  # Y039 Use "str" instead of "typing.Text"
+from typing import ByteString  # Y057 Do not use typing.ByteString, which has unclear semantics and is deprecated
+from collections.abc import ByteString  # Y057 Do not use collections.abc.ByteString, which has unclear semantics and is deprecated
 
 # GOOD ATTRIBUTE ACCESS
 foo: typing.SupportsIndex
 baz: re.Pattern[str]
 
 @typing_extensions.final
 def bar(arg: collections.abc.Sized) -> typing_extensions.Literal[True]: ...
@@ -160,7 +160,9 @@
 # BAD ATTRIBUTE ACCESS (Y023 code)
 class Foo:
     attribute: typing_extensions.ClassVar[int]  # Y023 Use "typing.ClassVar[T]" instead of "typing_extensions.ClassVar[T]"
 
 # BAD ATTRIBUTE ACCESS: OTHER
 j: collections.namedtuple  # Y024 Use "typing.NamedTuple" instead of "collections.namedtuple"
 m: typing.Text  # Y039 Use "str" instead of "typing.Text"
+o: typing.ByteString  # Y057 Do not use typing.ByteString, which has unclear semantics and is deprecated
+p: collections.abc.ByteString  # Y057 Do not use collections.abc.ByteString, which has unclear semantics and is deprecated
```

### Comparing `flake8_pyi-23.5.0/tests/names_requiring_values.pyi` & `flake8_pyi-23.6.0/tests/names_requiring_values.pyi`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/tests/never_vs_noreturn.pyi` & `flake8_pyi-23.6.0/tests/never_vs_noreturn.pyi`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/tests/pep604_union_types.pyi` & `flake8_pyi-23.6.0/tests/pep604_union_types.pyi`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/tests/quotes.pyi` & `flake8_pyi-23.6.0/tests/quotes.pyi`

 * *Files 13% similar despite different names*

```diff
@@ -1,24 +1,34 @@
 import sys
 import typing
-from typing import Annotated, Literal, TypeAlias, TypeVar
+from typing import Annotated, Literal, NewType, TypeAlias, TypeVar
 
 import typing_extensions
 
 __all__ = ["f", "g"]
 __all__ += ["h"]
 __all__.extend(["i"])  # Y056 Calling ".extend()" on "__all__" may not be supported by all type checkers (use += instead)
 __all__.append("j")  # Y056 Calling ".append()" on "__all__" may not be supported by all type checkers (use += instead)
 __all__.remove("j")  # Y056 Calling ".remove()" on "__all__" may not be supported by all type checkers (use += instead)
 __match_args__ = ('foo',)  # Y052 Need type annotation for "__match_args__"
 __slots__ = ('foo',)  # Y052 Need type annotation for "__slots__"
 
 def f(x: "int"): ...  # Y020 Quoted annotations should never be used in stubs
 def g(x: list["int"]): ...  # Y020 Quoted annotations should never be used in stubs
 _T = TypeVar("_T", bound="int")  # Y020 Quoted annotations should never be used in stubs
+_T2 = TypeVar("_T", bound=int)
+_S = TypeVar("_S")
+_U = TypeVar("_U", "int", "str")  # Y020 Quoted annotations should never be used in stubs  # Y020 Quoted annotations should never be used in stubs
+_U2 = TypeVar("_U", int, str)
+
+# This is invalid, but type checkers will flag it, so we don't need to
+_V = TypeVar()
+
+def make_sure_those_typevars_arent_flagged_as_unused(a: _T, b: _T2, c: _S, d: _U, e: _U2, f: _V) -> tuple[_T, _T2, _S, _U, _U2, _V]: ...
+
 def h(w: Literal["a", "b"], x: typing.Literal["c"], y: typing_extensions.Literal["d"], z: _T) -> _T: ...
 
 def i(x: Annotated[int, "lots", "of", "strings"], b: typing.Annotated[str, "more", "strings"]) -> None:
     """Documented and guaranteed useful."""  # Y021 Docstrings should not be included in stubs
 
 def j() -> "int": ...  # Y020 Quoted annotations should never be used in stubs
 Alias: TypeAlias = list["int"]  # Y020 Quoted annotations should never be used in stubs
@@ -52,18 +62,14 @@
     """Docstring"""  # Y021 Docstrings should not be included in stubs
     ...  # Y013 Non-empty class body must not contain "..."
 
 class DocstringAndPass:
     """Docstring"""  # Y021 Docstrings should not be included in stubs
     pass  # Y012 Class body must not contain "pass"
 
-# These two shouldn't trigger Y020 -- empty strings can't be "quoted annotations"
+# These three shouldn't trigger Y020 -- empty strings can't be "quoted annotations"
 k = ""  # Y052 Need type annotation for "k"
 el = r""  # Y052 Need type annotation for "el"
+m = u""  # Y052 Need type annotation for "m"
 
-# The following should also pass,
-# But we can't test for it in CI, because the error message is *very* slightly different on 3.7
-#
-# On 3.7:
-# m = u""  # Y015 Bad default value. Use "m = ..." instead of "m = ''"
-# On 3.8+:
-# m = u""  # Y015 Bad default value. Use "m = ..." instead of "m = u''"
+_N = NewType("_N", int)
+_NBad = NewType("_N", "int")  # Y020 Quoted annotations should never be used in stubs
```

### Comparing `flake8_pyi-23.5.0/tests/sysversioninfo.pyi` & `flake8_pyi-23.6.0/tests/sysversioninfo.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -1,18 +1,22 @@
 import sys
 
 if sys.version_info[0] == 2: ...
+if sys.version_info[0] == True: ...  # Y003 Unrecognized sys.version_info check  # E712 comparison to True should be 'if cond is True:' or 'if cond:'
 if sys.version_info[0.0] == 2: ...  # Y003 Unrecognized sys.version_info check
+if sys.version_info[False] == 2: ...  # Y003 Unrecognized sys.version_info check
 if sys.version_info[0j] == 2: ...  # Y003 Unrecognized sys.version_info check
 if sys.version_info[0] == (2, 7): ...  # Y003 Unrecognized sys.version_info check
 if sys.version_info[0] == '2': ...  # Y003 Unrecognized sys.version_info check
 if sys.version_info[1:] >= (7, 11): ...  # Y003 Unrecognized sys.version_info check
 if sys.version_info[::-1] < (11, 7): ...  # Y003 Unrecognized sys.version_info check
 if sys.version_info[:3] >= (2, 7): ...  # Y003 Unrecognized sys.version_info check
+if sys.version_info[:True] >= (2, 7): ...  # Y003 Unrecognized sys.version_info check
 if sys.version_info[:1] == (2,): ...
+if sys.version_info[:1] == (True,): ...  # Y003 Unrecognized sys.version_info check
 if sys.version_info[:1] == (2, 7): ...  # Y005 Version comparison must be against a length-1 tuple
 if sys.version_info[:2] == (2, 7): ...
 if sys.version_info[:2] == (2,): ...  # Y005 Version comparison must be against a length-2 tuple
 if sys.version_info[:2] == "lol": ...  # Y003 Unrecognized sys.version_info check
 if sys.version_info[:2.0] >= (3, 9): ...  # Y003 Unrecognized sys.version_info check
 if sys.version_info[:2j] >= (3, 9): ...  # Y003 Unrecognized sys.version_info check
 if sys.version_info[:, :] >= (2, 7): ...  # Y003 Unrecognized sys.version_info check
```

### Comparing `flake8_pyi-23.5.0/tests/test_pyi_files.py` & `flake8_pyi-23.6.0/tests/test_pyi_files.py`

 * *Files 2% similar despite different names*

```diff
@@ -9,16 +9,15 @@
 
 
 @pytest.mark.parametrize("path", glob.glob("tests/*.pyi"))
 def test_pyi_file(path: str) -> None:
     flags = []
     expected_output = ""
 
-    match = re.search(r"_py3(\d+)\.pyi$", path)
-    if match is not None:
+    if match := re.search(r"_py3(\d+)\.pyi$", path):
         if sys.version_info < (3, int(match.group(1))):
             pytest.skip(f"Python {sys.version_info} is too old for {path}")
 
     with open(path, encoding="UTF-8") as file:
         file_contents = file.read()
 
     for lineno, line in enumerate(file_contents.splitlines(), start=1):
```

### Comparing `flake8_pyi-23.5.0/tests/type_comments.pyi` & `flake8_pyi-23.6.0/tests/type_comments.pyi`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/tests/typevar.pyi` & `flake8_pyi-23.6.0/tests/typevar.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -24,25 +24,27 @@
 
 _UsedInClassDef = TypeVar("_UsedInClassDef", bound=bytes)
 class UsesATypeVar2(list[_UsedInClassDef]): ...
 
 _UsedInAnnotatedSubscript = TypeVar("_UsedInAnnotatedSubscript", bound=list[int])
 def func3(arg: Annotated[_UsedInAnnotatedSubscript, "Important metadata"]) -> Annotated[_UsedInAnnotatedSubscript, "More important metadata"]: ...
 
-_S = TypeVar("_S")
+# Make sure TypeVars constrained and bound to forward references are permitted by pyflakes
+_S = TypeVar("_S", bound=BadClass)
+_S2 = TypeVar("_S2", BadClass, GoodClass)
 
 class BadClass:
     def __new__(cls: type[_S], *args: str, **kwargs: int) -> _S: ...  # Y019 Use "typing_extensions.Self" instead of "_S", e.g. "def __new__(cls, *args: str, **kwargs: int) -> Self: ..."
     def bad_instance_method(self: _S, arg: bytes) -> _S: ...  # Y019 Use "typing_extensions.Self" instead of "_S", e.g. "def bad_instance_method(self, arg: bytes) -> Self: ..."
     @classmethod
     def bad_class_method(cls: type[_S], arg: int) -> _S: ...  # Y019 Use "typing_extensions.Self" instead of "_S", e.g. "def bad_class_method(cls, arg: int) -> Self: ..."
 
 class GoodClass:
     def __new__(cls: type[Self], *args: list[int], **kwargs: set[str]) -> Self: ...
     def good_instance_method_1(self: Self, arg: bytes) -> Self: ...
-    def good_instance_method_2(self, arg1: _S, arg2: _S) -> _S: ...
+    def good_instance_method_2(self, arg1: _S2, arg2: _S2) -> _S2: ...
     @classmethod
     def good_cls_method_1(cls: type[Self], arg: int) -> Self: ...
     @classmethod
     def good_cls_method_2(cls, arg1: _S, arg2: _S) -> _S: ...
     @staticmethod
     def static_method(arg1: _S) -> _S: ...
```

### Comparing `flake8_pyi-23.5.0/tests/union_duplicates.pyi` & `flake8_pyi-23.6.0/tests/union_duplicates.pyi`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/.gitignore` & `flake8_pyi-23.6.0/.gitignore`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/LICENSE` & `flake8_pyi-23.6.0/LICENSE`

 * *Files identical despite different names*

### Comparing `flake8_pyi-23.5.0/README.md` & `flake8_pyi-23.6.0/ERRORCODES.md`

 * *Files 18% similar despite different names*

```diff
@@ -1,40 +1,10 @@
-# flake8-pyi
-
-A plugin for Flake8 that provides specializations for
-[type hinting stub files](https://www.python.org/dev/peps/pep-0484/#stub-files),
-especially interesting for linting
-[typeshed](https://github.com/python/typeshed/).
-
-Refer to [this documentation](https://typing.readthedocs.io/en/latest/source/stubs.html) for more
-details on stub files.
-
-## Functionality
-
-1. Adds the `.pyi` extension to the default value of the `--filename`
-   command-line argument to Flake8.  This means stubs are linted by default with
-   this plugin enabled, without needing to explicitly list every file.
-
-2. Modifies PyFlakes runs for `.pyi` files to defer checking type annotation
-   expressions after the entire file has been read.  This enables support for
-   first-class forward references that stub files use.
-
-3. Provides a number of `.pyi`-specific warnings that enforce typeshed's
-   style guide.
-
-Note: Be careful when using this plugin in the same environment as other flake8
-plugins, as they might generate errors that are inappropriate for
-`.pyi` files (e.g., about missing docstrings). We recommend running
-`flake8-pyi` in a dedicated environment in your CI.
-
-
 ## List of warnings
 
-This plugin reserves codes starting with **Y0**. The following warnings are
-currently emitted:
+The following warnings are currently emitted:
 
 | Code | Description
 |------|-------------
 | Y001 | Names of `TypeVar`s, `ParamSpec`s and `TypeVarTuple`s in stubs should usually start with `_`. This makes sure you don't accidentally expose names internal to the stub.
 | Y002 | An `if` test must be a simple comparison against `sys.platform` or `sys.version_info`. Stub files support simple conditionals to indicate differences between Python versions or platforms, but type checkers only understand a limited subset of Python syntax. This warning is emitted on conditionals that type checkers may not understand.
 | Y003 | Unrecognized `sys.version_info` check. Similar to Y002, but adds some additional checks specific to `sys.version_info` comparisons.
 | Y004 | Version comparison must use only major and minor version. Type checkers like mypy don't know about patch versions of Python (e.g. 3.4.3 versus 3.4.4), only major and minor versions (3.3 versus 3.4). Therefore, version checks in stubs should only use the major and minor versions. If new functionality was introduced in a patch version, pretend that it was there all along.
@@ -55,15 +25,15 @@
 | Y019 | Certain kinds of methods should use `typing_extensions.Self` instead of defining custom `TypeVar`s for their return annotation. This check currently applies for instance methods that return `self`, class methods that return an instance of `cls`, and `__new__` methods.
 | Y020 | Quoted annotations should never be used in stubs.
 | Y021 | Docstrings should not be included in stubs.
 | Y022 | The `typing` and `typing_extensions` modules include various aliases to stdlib objects. Use these as little as possible (e.g. prefer `builtins.list` over `typing.List`, `collections.Counter` over `typing.Counter`, etc.).
 | Y023 | Where there is no detriment to backwards compatibility, import objects such as `ClassVar` and `NoReturn` from `typing` rather than `typing_extensions`.
 | Y024 | Use `typing.NamedTuple` instead of `collections.namedtuple`, as it allows for more precise type inference.
 | Y025 | Always alias `collections.abc.Set` when importing it, so as to avoid confusion with `builtins.set`. E.g. use `from collections.abc import Set as AbstractSet` instead of `from collections.abc import Set`.
-| Y026 | Type aliases should be explicitly demarcated with `typing.TypeAlias`.
+| Y026 | Type aliases should be explicitly demarcated with `typing.TypeAlias` (or use a [PEP-695](https://peps.python.org/pep-0695/) type statement).
 | Y028 | Always use class-based syntax for `typing.NamedTuple`, instead of assignment-based syntax.
 | Y029 | It is almost always redundant to define `__str__` or `__repr__` in a stub file, as the signatures are almost always identical to `object.__str__` and `object.__repr__`.
 | Y030 | Union expressions should never have more than one `Literal` member, as `Literal[1] \| Literal[2]` is semantically identical to `Literal[1, 2]`.
 | Y031 | `TypedDict`s should use class-based syntax instead of assignment-based syntax wherever possible. (In situations where this is not possible, such as if a field is a Python keyword or an invalid identifier, this error will not be emitted.)
 | Y032 | The second argument of an `__eq__` or `__ne__` method should usually be annotated with `object` rather than `Any`.
 | Y033 | Do not use type comments (e.g. `x = ... # type: int`) in stubs. Always use annotations instead (e.g. `x: int`).
 | Y034 | Y034 detects common errors where certain methods are annotated as having a fixed return type, despite returning `self` at runtime. Such methods should be annotated with `typing_extensions.Self`. This check looks for:<br><br>&nbsp;&nbsp;**1.**&nbsp;&nbsp;Any in-place BinOp dunder methods (`__iadd__`, `__ior__`, etc.) that do not return `Self`.<br>&nbsp;&nbsp;**2.**&nbsp;&nbsp;`__new__`, `__enter__` and `__aenter__` methods that return the class's name unparameterised.<br>&nbsp;&nbsp;**3.**&nbsp;&nbsp;`__iter__` methods that return `Iterator`, even if the class inherits directly from `Iterator`.<br>&nbsp;&nbsp;**4.**&nbsp;&nbsp;`__aiter__` methods that return `AsyncIterator`, even if the class inherits directly from `AsyncIterator`.<br><br>This check excludes methods decorated with `@overload` or `@abstractmethod`.
@@ -85,36 +55,8 @@
 | Y050 | Prefer `typing_extensions.Never` over `typing.NoReturn` for argument annotations. This is a purely stylistic choice in the name of readability.
 | Y051 | Y051 detects redundant unions between `Literal` types and builtin supertypes. For example, `Literal[5]` is redundant in the union `int \| Literal[5]`, and `Literal[True]` is redundant in the union `Literal[True] \| bool`.
 | Y052 | Y052 disallows assignments to constant values where the assignment does not have a type annotation. For example, `x = 0` in the global namespace is ambiguous in a stub, as there are four different types that could be inferred for the variable `x`: `int`, `Final[int]`, `Literal[0]`, or `Final[Literal[0]]`. Enum members are excluded from this check, as are various special assignments such as `__all__` and `__match_args__`.
 | Y053 | Only string and bytes literals <=50 characters long are permitted.
 | Y054 | Only numeric literals with a string representation <=10 characters long are permitted.
 | Y055 | Unions of the form `type[X] \| type[Y]` can be simplified to `type[X \| Y]`. Similarly, `Union[type[X], type[Y]]` can be simplified to `type[Union[X, Y]]`.
 | Y056 | Do not call methods such as `.append()`, `.extend()` or `.remove()` on `__all__`. Different type checkers have varying levels of support for calling these methods on `__all__`. Use `+=` instead, which is known to be supported by all major type checkers.
-
-Note that several error codes recommend using types from `typing_extensions` or
-`_typeshed`. Strictly speaking, these packages are not part of the standard
-library. However, these packages are included in typeshed's `stdlib/`
-directory, meaning that type checkers believe them to be part of the standard
-library even if this does not reflect the reality at runtime. As such, since
-stubs are never executed at runtime, types from `typing_extensions` and
-`_typeshed` can be used freely in a stubs package, even if the package does not
-have an explicit dependency on either `typing_extensions` or typeshed.
-
-Flake8-pyi's checks may produce false positives on stubs that aim to support Python 2.
-
-## License
-
-MIT
-
-
-## Authors
-
-Originally created by [Łukasz Langa](mailto:lukasz@langa.pl) and
-now maintained by
-[Jelle Zijlstra](mailto:jelle.zijlstra@gmail.com),
-[Alex Waygood](mailto:alex.waygood@gmail.com),
-Sebastian Rittau, Akuli, and Shantanu.
-
-## See also
-
-* [Changelog](./CHANGELOG.md)
-* [Information for contributors](./CONTRIBUTING.md)
+| Y057 | Do not use `typing.ByteString` or `collections.abc.ByteString`. These types have unclear semantics, and are deprecated; use  `typing_extensions.Buffer` or a union such as `bytes \| bytearray \| memoryview` instead. See [PEP 688](https://peps.python.org/pep-0688/) for more details.
```

#### encoding

```diff
@@ -1 +1 @@
-utf-8
+us-ascii
```

### Comparing `flake8_pyi-23.5.0/pyproject.toml` & `flake8_pyi-23.6.0/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -14,15 +14,15 @@
   { name="Sebastian Rittau" },
   { name="Akuli" },
   { name="Shantanu" },
 ]
 description = "A plugin for flake8 to enable linting .pyi stub files."
 license = { text = "MIT" }
 readme = "README.md"
-requires-python = ">=3.7"
+requires-python = ">=3.8"
 keywords = [
     "flake8",
     "pyi",
     "bugs",
     "pyflakes",
     "linter",
     "qa",
@@ -34,43 +34,43 @@
     "Environment :: Console",
     "Framework :: Flake8",
     "Intended Audience :: Developers",
     "License :: OSI Approved :: MIT License",
     "Operating System :: OS Independent",
     "Programming Language :: Python",
     "Programming Language :: Python :: 3 :: Only",
-    "Programming Language :: Python :: 3.7",
     "Programming Language :: Python :: 3.8",
     "Programming Language :: Python :: 3.9",
     "Programming Language :: Python :: 3.10",
     "Programming Language :: Python :: 3.11",
+    "Programming Language :: Python :: 3.12",
     "Topic :: Software Development :: Libraries :: Python Modules",
     "Topic :: Software Development :: Quality Assurance",
 ]
 dependencies = [
-    "flake8 >= 5.0.4, < 7.0.0",
+    "flake8 >= 6.0.0, < 7.0.0",
     "pyflakes >= 2.1.1",
     "ast-decompiler >= 0.7.0, < 1.0; python_version < '3.9'",
 ]
 
 [project.urls]
 "Homepage" = "https://github.com/PyCQA/flake8-pyi"
 "Source" = "https://github.com/PyCQA/flake8-pyi"
 "Bug Tracker" = "https://github.com/PyCQA/flake8-pyi/issues"
 "Changelog" = "https://github.com/PyCQA/flake8-pyi/blob/main/CHANGELOG.md"
 
 [project.optional-dependencies]
 dev = [
-    "black==23.3.0",                          # Must match .pre-commit-config.yaml
-    "flake8-bugbear==23.2.13",
-    "flake8-noqa==1.3.0",
-    "isort==5.12.0; python_version >= '3.8'", # Must match .pre-commit-config.yaml
-    "mypy==1.1.1",
-    "pre-commit-hooks==4.4.0",                # Must match .pre-commit-config.yaml
-    "pytest==7.2.2",
+    "black==23.3.0",            # Must match .pre-commit-config.yaml
+    "flake8-bugbear==23.6.5",
+    "flake8-noqa==1.3.2",
+    "isort==5.12.0",            # Must match .pre-commit-config.yaml
+    "mypy==1.4.1",
+    "pre-commit-hooks==4.4.0",  # Must match .pre-commit-config.yaml
+    "pytest==7.4.0",
     "types-pyflakes<4",
 ]
 
 [project.entry-points]
 "flake8.extension" = {Y0 = "pyi:PyiTreeChecker"}
 
 [tool.hatch.version]
@@ -79,24 +79,26 @@
 [tool.isort]
 profile = "black"
 combine_as_imports = true
 skip = ["tests/imports.pyi"]
 skip_gitignore = true
 
 [tool.black]
-target-version = ['py37']
+target-version = ['py38']
 skip-magic-trailing-comma = true
 force-exclude = ".*\\.pyi"
 
 [tool.mypy]
 files = ["pyi.py", "tests/test_pyi_files.py"]
 show_traceback = true
 pretty = true
 strict = true
 enable_error_code = "ignore-without-code,redundant-expr,possibly-undefined"
 warn_unreachable = true
 allow_subclassing_any = true
-allow_untyped_defs = true
-allow_incomplete_defs = true
+
+[[tool.mypy.overrides]]
+module = 'flake8.*'
+ignore_missing_imports = true
 
 [tool.pytest.ini_options]
 addopts = "--doctest-modules"
```


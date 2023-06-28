# Comparing `tmp/graphtage-0.2.8.tar.gz` & `tmp/graphtage-0.2.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "graphtage-0.2.8.tar", last modified: Wed Jun 21 19:35:23 2023, max compression
+gzip compressed data, was "graphtage-0.2.9.tar", last modified: Wed Jun 28 13:13:41 2023, max compression
```

## Comparing `graphtage-0.2.8.tar` & `graphtage-0.2.9.tar`

### file list

```diff
@@ -1,52 +1,54 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 19:35:23.465860 graphtage-0.2.8/
--rw-r--r--   0 runner    (1001) docker     (123)     7652 2023-06-21 19:35:15.000000 graphtage-0.2.8/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-21 19:35:15.000000 graphtage-0.2.8/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     7718 2023-06-21 19:35:23.465860 graphtage-0.2.8/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     6883 2023-06-21 19:35:15.000000 graphtage-0.2.8/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 19:35:23.461860 graphtage-0.2.8/graphtage/
--rw-r--r--   0 runner    (1001) docker     (123)     1052 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16025 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    15059 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/bounds.py
--rw-r--r--   0 runner    (1001) docker     (123)     5261 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/csv.py
--rw-r--r--   0 runner    (1001) docker     (123)    18468 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/edits.py
--rw-r--r--   0 runner    (1001) docker     (123)    30535 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/expressions.py
--rw-r--r--   0 runner    (1001) docker     (123)    11969 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/fibonacci.py
--rw-r--r--   0 runner    (1001) docker     (123)    16882 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/formatter.py
--rw-r--r--   0 runner    (1001) docker     (123)    37826 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/graphtage.py
--rw-r--r--   0 runner    (1001) docker     (123)     9747 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/json.py
--rw-r--r--   0 runner    (1001) docker     (123)    16443 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/levenshtein.py
--rw-r--r--   0 runner    (1001) docker     (123)    28141 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/matching.py
--rw-r--r--   0 runner    (1001) docker     (123)     5498 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/multiset.py
--rw-r--r--   0 runner    (1001) docker     (123)     5617 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/plist.py
--rw-r--r--   0 runner    (1001) docker     (123)    22582 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/printer.py
--rw-r--r--   0 runner    (1001) docker     (123)     5954 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/progress.py
--rw-r--r--   0 runner    (1001) docker     (123)    10319 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/pydiff.py
--rw-r--r--   0 runner    (1001) docker     (123)    11128 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/search.py
--rw-r--r--   0 runner    (1001) docker     (123)    12812 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/sequences.py
--rw-r--r--   0 runner    (1001) docker     (123)    24295 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/tree.py
--rw-r--r--   0 runner    (1001) docker     (123)    14573 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     2844 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/version.py
--rw-r--r--   0 runner    (1001) docker     (123)    16277 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/xml.py
--rw-r--r--   0 runner    (1001) docker     (123)     8391 2023-06-21 19:35:15.000000 graphtage-0.2.8/graphtage/yaml.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 19:35:23.461860 graphtage-0.2.8/graphtage.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     7718 2023-06-21 19:35:23.000000 graphtage-0.2.8/graphtage.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      992 2023-06-21 19:35:23.000000 graphtage-0.2.8/graphtage.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-21 19:35:23.000000 graphtage-0.2.8/graphtage.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       54 2023-06-21 19:35:23.000000 graphtage-0.2.8/graphtage.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)      211 2023-06-21 19:35:23.000000 graphtage-0.2.8/graphtage.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-21 19:35:23.000000 graphtage-0.2.8/graphtage.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-21 19:35:23.465860 graphtage-0.2.8/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-06-21 19:35:15.000000 graphtage-0.2.8/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 19:35:23.465860 graphtage-0.2.8/test/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-21 19:35:15.000000 graphtage-0.2.8/test/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4307 2023-06-21 19:35:15.000000 graphtage-0.2.8/test/test_bounds.py
--rw-r--r--   0 runner    (1001) docker     (123)     2469 2023-06-21 19:35:15.000000 graphtage-0.2.8/test/test_expressions.py
--rw-r--r--   0 runner    (1001) docker     (123)     4161 2023-06-21 19:35:15.000000 graphtage-0.2.8/test/test_fibonacci.py
--rw-r--r--   0 runner    (1001) docker     (123)    10748 2023-06-21 19:35:15.000000 graphtage-0.2.8/test/test_formatting.py
--rw-r--r--   0 runner    (1001) docker     (123)     6887 2023-06-21 19:35:15.000000 graphtage-0.2.8/test/test_graphtage.py
--rw-r--r--   0 runner    (1001) docker     (123)     2978 2023-06-21 19:35:15.000000 graphtage-0.2.8/test/test_levenshtein.py
--rw-r--r--   0 runner    (1001) docker     (123)     3151 2023-06-21 19:35:15.000000 graphtage-0.2.8/test/test_matching.py
--rw-r--r--   0 runner    (1001) docker     (123)      831 2023-06-21 19:35:15.000000 graphtage-0.2.8/test/test_pydiff.py
--rw-r--r--   0 runner    (1001) docker     (123)     1475 2023-06-21 19:35:15.000000 graphtage-0.2.8/test/test_search.py
--rw-r--r--   0 runner    (1001) docker     (123)     1835 2023-06-21 19:35:15.000000 graphtage-0.2.8/test/test_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)      755 2023-06-21 19:35:15.000000 graphtage-0.2.8/test/test_xml.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:13:41.725187 graphtage-0.2.9/
+-rw-r--r--   0 runner    (1001) docker     (123)     7652 2023-06-28 13:13:29.000000 graphtage-0.2.9/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 13:13:29.000000 graphtage-0.2.9/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     7718 2023-06-28 13:13:41.725187 graphtage-0.2.9/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     6883 2023-06-28 13:13:29.000000 graphtage-0.2.9/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:13:41.725187 graphtage-0.2.9/graphtage/
+-rw-r--r--   0 runner    (1001) docker     (123)     1012 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14789 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15059 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/bounds.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1570 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/constraints.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5261 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/csv.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18505 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/edits.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30535 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/expressions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11969 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/fibonacci.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16882 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/formatter.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37993 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/graphtage.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9933 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/json.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16443 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/levenshtein.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28141 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/matching.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5498 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/multiset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5617 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/plist.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22582 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/printer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6020 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/progress.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10319 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/pydiff.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11128 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/search.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12812 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/sequences.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24417 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/tree.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14573 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2844 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16277 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/xml.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8391 2023-06-28 13:13:29.000000 graphtage-0.2.9/graphtage/yaml.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:13:41.725187 graphtage-0.2.9/graphtage.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     7718 2023-06-28 13:13:41.000000 graphtage-0.2.9/graphtage.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1042 2023-06-28 13:13:41.000000 graphtage-0.2.9/graphtage.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:13:41.000000 graphtage-0.2.9/graphtage.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       54 2023-06-28 13:13:41.000000 graphtage-0.2.9/graphtage.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      211 2023-06-28 13:13:41.000000 graphtage-0.2.9/graphtage.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 13:13:41.000000 graphtage-0.2.9/graphtage.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 13:13:41.725187 graphtage-0.2.9/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-06-28 13:13:29.000000 graphtage-0.2.9/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:13:41.725187 graphtage-0.2.9/test/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:13:29.000000 graphtage-0.2.9/test/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4307 2023-06-28 13:13:29.000000 graphtage-0.2.9/test/test_bounds.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1064 2023-06-28 13:13:29.000000 graphtage-0.2.9/test/test_constraints.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2469 2023-06-28 13:13:29.000000 graphtage-0.2.9/test/test_expressions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4161 2023-06-28 13:13:29.000000 graphtage-0.2.9/test/test_fibonacci.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10748 2023-06-28 13:13:29.000000 graphtage-0.2.9/test/test_formatting.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6887 2023-06-28 13:13:29.000000 graphtage-0.2.9/test/test_graphtage.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2978 2023-06-28 13:13:29.000000 graphtage-0.2.9/test/test_levenshtein.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3151 2023-06-28 13:13:29.000000 graphtage-0.2.9/test/test_matching.py
+-rw-r--r--   0 runner    (1001) docker     (123)      831 2023-06-28 13:13:29.000000 graphtage-0.2.9/test/test_pydiff.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1475 2023-06-28 13:13:29.000000 graphtage-0.2.9/test/test_search.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1835 2023-06-28 13:13:29.000000 graphtage-0.2.9/test/test_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)      755 2023-06-28 13:13:29.000000 graphtage-0.2.9/test/test_xml.py
```

### Comparing `graphtage-0.2.8/LICENSE` & `graphtage-0.2.9/LICENSE`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/PKG-INFO` & `graphtage-0.2.9/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: graphtage
-Version: 0.2.8
+Version: 0.2.9
 Summary: A utility to diff tree-like files such as JSON and XML.
 Home-page: https://github.com/trailofbits/graphtage
 Author: Trail of Bits
 License: LGPL-3.0-or-later
 Project-URL: Documentation, https://trailofbits.github.io/graphtage
 Project-URL: Source, https://github.com/trailofbits/graphtage
 Project-URL: Tracker, https://github.com/trailofbits/graphtage/issues
```

### Comparing `graphtage-0.2.8/README.md` & `graphtage-0.2.9/README.md`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/__init__.py` & `graphtage-0.2.9/graphtage/__init__.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,16 +1,18 @@
 from . import graphtage
 
 from .graphtage import *
 from .tree import *
 from .edits import *
 
 from .version import __version__, VERSION_STRING
-from . import bounds, edits, expressions, fibonacci, formatter, levenshtein, matching, printer, pydiff, \
-                                                               search, sequences, tree, utils
+from . import (
+    bounds, constraints, edits, expressions, fibonacci, formatter, levenshtein, matching, printer, pydiff, search,
+    sequences, tree, utils
+)
 from . import csv, json, xml, yaml, plist
 
 import inspect
 
 # All of the classes in SUBMODULES_TO_SUBSUME should really be in the top-level `graphtage` module.
 # They are separated into submodules solely for making the Python file sizes more manageable.
 # So the following code loops over those submodules and reassigns all of the classes to the top-level module.
```

### Comparing `graphtage-0.2.8/graphtage/__main__.py` & `graphtage-0.2.9/graphtage/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,22 +1,20 @@
 import argparse
 import logging
 import mimetypes
 import os
 import sys
-from abc import ABCMeta, abstractmethod
-from typing import Optional
 
 from colorama.ansi import Fore
 
-from .edits import Edit
 from . import expressions
 from . import graphtage
 from . import printer as printermodule
 from . import version
+from .constraints import MatchIf, MatchUnless
 from .printer import HTMLPrinter, Printer
 from .utils import Tempfile
 
 
 log = logging.getLogger('graphtage')
 
 
@@ -35,49 +33,14 @@
             return self._tempfile.__enter__()
 
     def __exit__(self, *args, **kwargs):
         if self._tempfile is not None:
             return self._tempfile.__exit__(*args, **kwargs)
 
 
-class ConditionalMatcher(metaclass=ABCMeta):
-    def __init__(self, condition: expressions.Expression):
-        self.condition: expressions.Expression = condition
-
-    @abstractmethod
-    def __call__(self, from_node: graphtage.TreeNode, to_node: graphtage.TreeNode) -> Optional[Edit]:
-        raise NotImplementedError()
-
-    @classmethod
-    def apply(cls, node: graphtage.TreeNode, condition: expressions.Expression):
-        if node.edit_modifiers is None:
-            node.edit_modifiers = []
-        node.edit_modifiers.append(cls(condition))
-
-
-class MatchIf(ConditionalMatcher):
-    def __call__(self, from_node: graphtage.TreeNode, to_node: graphtage.TreeNode) -> Optional[Edit]:
-        try:
-            if self.condition.eval(locals={'from': from_node, 'to': to_node}):
-                return None
-        except Exception as e:
-            log.debug(f"{e!s} while evaluating --match-if for nodes {from_node} and {to_node}")
-        return graphtage.Replace(from_node, to_node)
-
-
-class MatchUnless(ConditionalMatcher):
-    def __call__(self, from_node: graphtage.TreeNode, to_node: graphtage.TreeNode) -> Optional[Edit]:
-        try:
-            if self.condition.eval(locals={'from': from_node.to_obj(), 'to': to_node.to_obj()}):
-                return graphtage.Replace(from_node, to_node)
-        except Exception as e:
-            log.debug(f"{e!s} while evaluating --match-unless for nodes {from_node} and {to_node}")
-        return None
-
-
 def main(argv=None) -> int:
     parser = argparse.ArgumentParser(
         description='A diff utility for tree-like files such as JSON, XML, HTML, YAML, and CSV.'
     )
     parser.add_argument('FROM_PATH', type=str, nargs='?', default='-',
                         help='the source file to diff; pass \'-\' to read from STDIN')
     parser.add_argument('TO_PATH', type=str, nargs='?', default='-',
@@ -316,24 +279,28 @@
 
     try:
         with printer:
             with PathOrStdin(args.FROM_PATH) as from_path:
                 with PathOrStdin(args.TO_PATH) as to_path:
                     from_format = graphtage.get_filetype(from_path, from_mime)
                     to_format = graphtage.get_filetype(to_path, to_mime)
-                    from_tree = from_format.build_tree_handling_errors(from_path, options)
-                    if isinstance(from_tree, str):
-                        sys.stderr.write(from_tree)
-                        sys.stderr.write('\n\n')
-                        sys.exit(1)
-                    to_tree = to_format.build_tree_handling_errors(to_path, options)
-                    if isinstance(to_tree, str):
-                        sys.stderr.write(to_tree)
-                        sys.stderr.write('\n\n')
-                        sys.exit(1)
+                    with printer.tqdm(desc=f"Loading {from_path!s}", total=2, leave=False) as t:
+                        from_tree = from_format.build_tree_handling_errors(from_path, options)
+                        t.desc = f"Loading {to_path!s}"
+                        t.update(1)
+                        if isinstance(from_tree, str):
+                            sys.stderr.write(from_tree)
+                            sys.stderr.write('\n\n')
+                            sys.exit(1)
+                        to_tree = to_format.build_tree_handling_errors(to_path, options)
+                        t.update(1)
+                        if isinstance(to_tree, str):
+                            sys.stderr.write(to_tree)
+                            sys.stderr.write('\n\n')
+                            sys.exit(1)
                     if match_if is not None or match_unless is not None:
                         for node in from_tree.dfs():
                             if match_if is not None:
                                 MatchIf.apply(node, match_if)
                             if match_unless is not None:
                                 MatchUnless.apply(node, match_unless)
                     had_edits = False
```

### Comparing `graphtage-0.2.8/graphtage/bounds.py` & `graphtage-0.2.9/graphtage/bounds.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/csv.py` & `graphtage-0.2.9/graphtage/csv.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/edits.py` & `graphtage-0.2.9/graphtage/edits.py`

 * *Files 4% similar despite different names*

```diff
@@ -376,31 +376,31 @@
         self._cost = None
         self.explode_edits = explode_edits
         self._add: Callable[[Edit], Any] = lambda e: add_to_collection(self._sub_edits, e)
         super().__init__(from_node=from_node,
                          to_node=to_node,
                          cost_upper_bound=cost_upper_bound)
 
-    @property
-    def valid(self) -> bool:
-        if not super().valid:
-            return False
-        is_valid = True
-        if self._edit_iter is None:
-            for e in self._sub_edits:
-                if not e.valid:
-                    is_valid = False
-                    break
-        if not is_valid:
-            self.valid = False
-        return is_valid
-
-    @valid.setter
-    def valid(self, is_valid: bool):
-        self._valid = is_valid
+    # @property
+    # def valid(self) -> bool:
+    #     if not super().valid:
+    #         return False
+    #     is_valid = True
+    #     if self._edit_iter is None:
+    #         for e in self._sub_edits:
+    #             if not e.valid:
+    #                 is_valid = False
+    #                 break
+    #     if not is_valid:
+    #         self.valid = False
+    #     return is_valid
+    #
+    # @valid.setter
+    # def valid(self, is_valid: bool):
+    #     self._valid = is_valid
 
     def print(self, formatter: GraphtageFormatter, printer: Printer):
         for sub_edit in self.edits():
             sub_edit.print(formatter, printer)
 
     def _expand_edits(self) -> Optional[Edit]:
         if self._edit_iter is not None:
```

### Comparing `graphtage-0.2.8/graphtage/expressions.py` & `graphtage-0.2.9/graphtage/expressions.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/fibonacci.py` & `graphtage-0.2.9/graphtage/fibonacci.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/formatter.py` & `graphtage-0.2.9/graphtage/formatter.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/graphtage.py` & `graphtage-0.2.9/graphtage/graphtage.py`

 * *Files 1% similar despite different names*

```diff
@@ -22,14 +22,16 @@
         """Creates a node with the given object.
 
         Args:
             obj: The underlying Python object wrapped by the node.
 
         """
         self.object = obj
+        # self.__hash__ gets called so often we cache the result:
+        self.__hash = hash(obj)
 
     def to_obj(self):
         """Returns the object wrapped by this node.
 
         This is equivalent to::
 
             return self.object
@@ -95,15 +97,15 @@
     def __eq__(self, other):
         if isinstance(other, LeafNode):
             return self.object == other.object
         else:
             return self.object == other
 
     def __hash__(self):
-        return hash(self.object)
+        return self.__hash
 
     def __repr__(self):
         return f"{self.__class__.__name__}({self.object!r})"
 
     def __str__(self):
         return str(self.object)
 
@@ -172,14 +174,16 @@
             allow_key_edits: If :const:`False`, only consider matching against another key/value pair node if it has
                 the same key.
 
         """
         self.key: LeafNode = key
         self.value: TreeNode = value
         self.allow_key_edits: bool = allow_key_edits
+        # self.__hash__ gets called so often, we cache the result:
+        self.__hash = hash((key, value))
 
     def to_obj(self):
         return self.key, self.value
 
     def print_parent_context(self, printer: Printer, for_child: TreeNode):
         if for_child.parent is not self:
             # this is not one of our children!
@@ -265,15 +269,15 @@
 
         """
         if not isinstance(other, KeyValuePairNode):
             return False
         return self.key == other.key and self.value == other.value
 
     def __hash__(self):
-        return hash((self.key, self.value))
+        return self.__hash
 
     def __len__(self):
         return 2
 
     def __iter__(self):
         yield self.key
         yield self.value
@@ -892,15 +896,15 @@
         else:
             return True
 
     def __eq__(self, other):
         return isinstance(other, NullNode)
 
     def __hash__(self):
-        return hash(self.object)
+        return 0
 
     def __repr__(self):
         return f"{self.__class__.__name__}()"
 
 
 def string_edit_distance(s1: str, s2: str) -> EditDistance:
     """A convenience function for computing the edit distance between two strings.
```

### Comparing `graphtage-0.2.8/graphtage/json.py` & `graphtage-0.2.9/graphtage/json.py`

 * *Files 3% similar despite different names*

```diff
@@ -8,15 +8,15 @@
 import json
 import json5
 import os
 from typing import Optional, Union
 
 from .graphtage import BoolNode, BuildOptions, DictNode, Filetype, FixedKeyDictNode, \
     FloatNode, IntegerNode, KeyValuePairNode, LeafNode, ListNode, NullNode, StringFormatter, StringNode
-from .printer import Fore, Printer
+from .printer import DEFAULT_PRINTER, Fore, Printer
 from .sequences import SequenceFormatter
 from .tree import ContainerNode, GraphtageFormatter, TreeNode
 
 
 def build_tree(
         python_obj: Union[int, float, bool, str, bytes, list, dict],
         options: Optional[BuildOptions] = None,
@@ -49,22 +49,24 @@
         return StringNode(python_obj)
     elif isinstance(python_obj, bytes):
         return StringNode(python_obj.decode('utf-8'))
     elif force_leaf_node:
         raise ValueError(f"{python_obj!r} was expected to be an int or string, but was instead a {type(python_obj)}")
     elif isinstance(python_obj, list) or isinstance(python_obj, tuple):
         return ListNode(
-            [build_tree(n, options=options) for n in python_obj],
+            [build_tree(n, options=options) for n in
+             DEFAULT_PRINTER.tqdm(python_obj, delay=2.0, desc="Loading JSON List", leave=False)],
             allow_list_edits=options.allow_list_edits,
             allow_list_edits_when_same_length=options.allow_list_edits_when_same_length
         )
     elif isinstance(python_obj, dict):
         dict_items = {
             build_tree(k, options=options, force_leaf_node=True):
-                build_tree(v, options=options) for k, v in python_obj.items()
+                build_tree(v, options=options) for k, v in
+            DEFAULT_PRINTER.tqdm(python_obj.items(), delay=2.0, desc="Loading JSON Dict", leave=False)
         }
         if options.allow_key_edits:
             dict_node = DictNode.from_dict(dict_items)
             dict_node.auto_match_keys = options.auto_match_keys
             return dict_node
         else:
             return FixedKeyDictNode.from_dict(dict_items)
```

### Comparing `graphtage-0.2.8/graphtage/levenshtein.py` & `graphtage-0.2.9/graphtage/levenshtein.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/matching.py` & `graphtage-0.2.9/graphtage/matching.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/multiset.py` & `graphtage-0.2.9/graphtage/multiset.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/plist.py` & `graphtage-0.2.9/graphtage/plist.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/printer.py` & `graphtage-0.2.9/graphtage/printer.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/progress.py` & `graphtage-0.2.9/graphtage/progress.py`

 * *Files 2% similar despite different names*

```diff
@@ -50,22 +50,22 @@
             
             """
         except io.UnsupportedOperation as e:
             self.write_raw = True
 
     def tqdm(self, *args, **kwargs) -> tqdm:
         """Returns a :class:`tqdm.tqdm` object."""
-        if self.quiet:
-            kwargs['disable'] = True
+        if self.quiet or 'disable' not in kwargs:
+            kwargs['disable'] = self.quiet
         return tqdm(*args, **kwargs)
 
     def trange(self, *args, **kwargs) -> trange:
         """Returns a :class:`tqdm.trange` object."""
-        if self.quiet:
-            kwargs['disable'] = True
+        if self.quiet or 'disable' not in kwargs:
+            kwargs['disable'] = self.quiet
         return trange(*args, **kwargs)
 
     def flush(self, final=False):
         """Flushes this writer.
 
         If :obj:`final` is :const:`True`, any extra bytes will be flushed along with a final newline.
```

### Comparing `graphtage-0.2.8/graphtage/pydiff.py` & `graphtage-0.2.9/graphtage/pydiff.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/search.py` & `graphtage-0.2.9/graphtage/search.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/sequences.py` & `graphtage-0.2.9/graphtage/sequences.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/tree.py` & `graphtage-0.2.9/graphtage/tree.py`

 * *Files 2% similar despite different names*

```diff
@@ -332,38 +332,32 @@
 
     Tree nodes are intended to be immutable. :class:`EditedTreeNode`, on the other hand, can be mutable. See
     :meth:`TreeNode.make_edited`.
 
     """
     _total_size = None
     _parent: Optional["TreeNode"] = None
-    edit_modifiers: Optional[List[Callable[["TreeNode", "TreeNode"], Optional[Edit]]]] = None
+    _edit_modifiers: Optional[List[Callable[["TreeNode", "TreeNode"], Optional[Edit]]]] = None
 
     @property
     def edited(self) -> bool:
         """Returns whether this node has been edited.
 
         The default implementation returns :const:`False`, whereas :meth:`EditedTreeNode.edited` returns :const:`True`.
 
         """
         return False
 
     def _edits_with_modifiers(self, node: 'TreeNode') -> Edit:
-        for modifier in self.edit_modifiers:
+        for modifier in self._edit_modifiers:
             ret = modifier(self, node)
             if ret is not None:
                 return ret
         return self.__class__.edits(self, node)
 
-    def __getattribute__(self, item):
-        if item == 'edits' and super().__getattribute__('edit_modifiers'):
-            return super().__getattribute__('_edits_with_modifiers')
-        else:
-            return super().__getattribute__(item)
-
     @abstractmethod
     def to_obj(self):
         """Returns a pure Python representation of this node.
 
         For example, a node representing a list, like :class:`graphtage.ListNode`, should return a Python :class:`list`.
         A node representing a mapping, like :class:`graphtage.MappingNode`, should return a Python :class:`dict`.
         Container nodes should recursively call :meth:`TreeNode.to_obj` on all of their children.
@@ -452,27 +446,35 @@
 
         Returns:
             Edit: The best possible edit.
 
         """
         raise NotImplementedError()
 
+    def add_edit_modifier(self, modifier: Callable[["TreeNode", "TreeNode"], Optional[Edit]]):
+        if self._edit_modifiers is None:
+            self._edit_modifiers = []
+            self.edits = self._edits_with_modifiers
+        self._edit_modifiers.append(modifier)
+
     def make_edited(self) -> Union[EditedTreeNode, T]:
         """Returns a new, copied instance of this node that is also an instance of :class:`EditedTreeNode`.
 
         This is equivalent to::
 
             return self.__class__.edited_type()(self)
 
         Returns:
             Union[EditedTreeNode, T]: A copied version of this node that is also an instance of :class:`EditedTreeNode`
             and thereby mutable.
 
         """
         ret = self.__class__.edited_type()(self)
+        if ret._edit_modifiers is not None:
+            ret.edits = ret._edits_with_modifiers
         assert isinstance(ret, self.__class__)
         assert isinstance(ret, EditedTreeNode)
         return ret
 
     def editable_dict(self) -> Dict[str, Any]:
         """Copies :obj:`self.__dict__`, calling :meth:`TreeNode.editable_dict` on any :class:`TreeNode` objects therein.
```

### Comparing `graphtage-0.2.8/graphtage/utils.py` & `graphtage-0.2.9/graphtage/utils.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/version.py` & `graphtage-0.2.9/graphtage/version.py`

 * *Files 0% similar despite different names*

```diff
@@ -55,15 +55,15 @@
 deploying to PyPI.
 
 If :const:`True`, the git branch will be included in the version string.
 
 """
 
 
-__version__: Tuple[Union[int, str], ...] = (0, 2, 8)
+__version__: Tuple[Union[int, str], ...] = (0, 2, 9)
 
 if DEV_BUILD:
     branch_name = git_branch()
     if branch_name is None:
         __version__ = __version__ + ('git',)
     else:
         __version__ = __version__ + ('git', branch_name)
```

### Comparing `graphtage-0.2.8/graphtage/xml.py` & `graphtage-0.2.9/graphtage/xml.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage/yaml.py` & `graphtage-0.2.9/graphtage/yaml.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/graphtage.egg-info/PKG-INFO` & `graphtage-0.2.9/graphtage.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: graphtage
-Version: 0.2.8
+Version: 0.2.9
 Summary: A utility to diff tree-like files such as JSON and XML.
 Home-page: https://github.com/trailofbits/graphtage
 Author: Trail of Bits
 License: LGPL-3.0-or-later
 Project-URL: Documentation, https://trailofbits.github.io/graphtage
 Project-URL: Source, https://github.com/trailofbits/graphtage
 Project-URL: Tracker, https://github.com/trailofbits/graphtage/issues
```

### Comparing `graphtage-0.2.8/graphtage.egg-info/SOURCES.txt` & `graphtage-0.2.9/graphtage.egg-info/SOURCES.txt`

 * *Files 11% similar despite different names*

```diff
@@ -1,14 +1,15 @@
 LICENSE
 MANIFEST.in
 README.md
 setup.py
 graphtage/__init__.py
 graphtage/__main__.py
 graphtage/bounds.py
+graphtage/constraints.py
 graphtage/csv.py
 graphtage/edits.py
 graphtage/expressions.py
 graphtage/fibonacci.py
 graphtage/formatter.py
 graphtage/graphtage.py
 graphtage/json.py
@@ -30,14 +31,15 @@
 graphtage.egg-info/SOURCES.txt
 graphtage.egg-info/dependency_links.txt
 graphtage.egg-info/entry_points.txt
 graphtage.egg-info/requires.txt
 graphtage.egg-info/top_level.txt
 test/__init__.py
 test/test_bounds.py
+test/test_constraints.py
 test/test_expressions.py
 test/test_fibonacci.py
 test/test_formatting.py
 test/test_graphtage.py
 test/test_levenshtein.py
 test/test_matching.py
 test/test_pydiff.py
```

### Comparing `graphtage-0.2.8/setup.py` & `graphtage-0.2.9/setup.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/test/test_bounds.py` & `graphtage-0.2.9/test/test_bounds.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/test/test_expressions.py` & `graphtage-0.2.9/test/test_expressions.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/test/test_fibonacci.py` & `graphtage-0.2.9/test/test_fibonacci.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/test/test_formatting.py` & `graphtage-0.2.9/test/test_formatting.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/test/test_graphtage.py` & `graphtage-0.2.9/test/test_graphtage.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/test/test_levenshtein.py` & `graphtage-0.2.9/test/test_levenshtein.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/test/test_matching.py` & `graphtage-0.2.9/test/test_matching.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/test/test_pydiff.py` & `graphtage-0.2.9/test/test_pydiff.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/test/test_search.py` & `graphtage-0.2.9/test/test_search.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/test/test_utils.py` & `graphtage-0.2.9/test/test_utils.py`

 * *Files identical despite different names*

### Comparing `graphtage-0.2.8/test/test_xml.py` & `graphtage-0.2.9/test/test_xml.py`

 * *Files identical despite different names*


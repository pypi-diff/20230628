# Comparing `tmp/schemamodels-0.8.0.tar.gz` & `tmp/schemamodels-0.9.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "schemamodels-0.8.0.tar", max compression
+gzip compressed data, was "schemamodels-0.9.0.tar", max compression
```

## Comparing `schemamodels-0.8.0.tar` & `schemamodels-0.9.0.tar`

### file list

```diff
@@ -1,9 +1,9 @@
--rw-r--r--   0        0        0    32473 2023-05-31 03:33:36.221264 schemamodels-0.8.0/LICENSE
-drwxr-xr-x   0        0        0        0 2023-05-31 03:33:36.221264 schemamodels-0.8.0/LICENSES/
--rw-r--r--   0        0        0     2750 2023-06-05 15:06:05.104701 schemamodels-0.8.0/README.md
--rw-r--r--   0        0        0      573 2023-06-10 19:37:07.104319 schemamodels-0.8.0/pyproject.toml
--rw-r--r--   0        0        0     8422 2023-06-10 19:34:47.373494 schemamodels-0.8.0/schemamodels/__init__.py
--rw-r--r--   0        0        0      848 2023-05-31 03:33:36.225264 schemamodels-0.8.0/schemamodels/bases.py
--rw-r--r--   0        0        0       93 2023-05-31 03:33:36.225264 schemamodels-0.8.0/schemamodels/dynamic.py
--rw-r--r--   0        0        0      410 2023-05-31 03:33:36.225264 schemamodels-0.8.0/schemamodels/exceptions.py
--rw-r--r--   0        0        0     3370 1970-01-01 00:00:00.000000 schemamodels-0.8.0/PKG-INFO
+-rw-r--r--   0        0        0    32473 2023-05-31 03:33:36.221264 schemamodels-0.9.0/LICENSE
+drwxr-xr-x   0        0        0        0 2023-05-31 03:33:36.221264 schemamodels-0.9.0/LICENSES/
+-rw-r--r--   0        0        0     2750 2023-06-05 15:06:05.104701 schemamodels-0.9.0/README.md
+-rw-r--r--   0        0        0      573 2023-06-28 05:00:14.158346 schemamodels-0.9.0/pyproject.toml
+-rw-r--r--   0        0        0     8721 2023-06-28 04:57:12.510406 schemamodels-0.9.0/schemamodels/__init__.py
+-rw-r--r--   0        0        0      848 2023-05-31 03:33:36.225264 schemamodels-0.9.0/schemamodels/bases.py
+-rw-r--r--   0        0        0       93 2023-05-31 03:33:36.225264 schemamodels-0.9.0/schemamodels/dynamic.py
+-rw-r--r--   0        0        0      410 2023-05-31 03:33:36.225264 schemamodels-0.9.0/schemamodels/exceptions.py
+-rw-r--r--   0        0        0     3370 1970-01-01 00:00:00.000000 schemamodels-0.9.0/PKG-INFO
```

### Comparing `schemamodels-0.8.0/LICENSE` & `schemamodels-0.9.0/LICENSE`

 * *Files identical despite different names*

### Comparing `schemamodels-0.8.0/README.md` & `schemamodels-0.9.0/README.md`

 * *Files identical despite different names*

### Comparing `schemamodels-0.8.0/pyproject.toml` & `schemamodels-0.9.0/pyproject.toml`

 * *Files 18% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "schemamodels"
-version = "0.8.0"
+version = "0.9.0"
 description = "Dynamically create useful data classes from JSON schemas"
 authors = ["'Jurnell Cockhren' <jurnell@civichacker.com>"]
 license = "GPL-3.0-or-later"
 readme = "README.md"
 
 [tool.poetry.dependencies]
 python = "^3.8"
```

### Comparing `schemamodels-0.8.0/schemamodels/__init__.py` & `schemamodels-0.9.0/schemamodels/__init__.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 # SPDX-FileCopyrightText: 2023 Civic Hacker, LLC
 # SPDX-License-Identifier: GPL-3.0-or-later
 
 import sys
-from dataclasses import make_dataclass, field, fields as fs
+from dataclasses import make_dataclass, field, fields as fs, asdict
 from re import sub
 import importlib
 from operator import gt, ge, lt, le, mod, xor, not_, contains
 from typing import Callable
 
 from functools import partial, reduce
 
@@ -191,14 +191,17 @@
             make_dataclass,
             klassname,
             fields + fields_with_defaults,
             frozen=True,
             namespace={
                 '_errorhandler': self.error_handler.apply,
                 '_renderer': self.renderer.apply,
+                'tocsv': lambda self, header=False: f'{",".join(asdict(self).keys())}\n{",".join(asdict(self).values())}' if header else ",".join(asdict(self).values()),
+                'tolist': lambda self: list(asdict(self).values()),
+                'todict': lambda self: asdict(self),
                 '__post_init__': lambda self: constraints(self)._errorhandler(self)._renderer(self)
             })
         if sys.version_info.major == 3 and sys.version_info.minor >= 10:
             dataklass = dklass(slots=True)
         else:
             dataklass = dklass()
         setattr(self.dmod,
```

### Comparing `schemamodels-0.8.0/schemamodels/bases.py` & `schemamodels-0.9.0/schemamodels/bases.py`

 * *Files identical despite different names*

### Comparing `schemamodels-0.8.0/PKG-INFO` & `schemamodels-0.9.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: schemamodels
-Version: 0.8.0
+Version: 0.9.0
 Summary: Dynamically create useful data classes from JSON schemas
 License: GPL-3.0-or-later
 Author: 'Jurnell Cockhren'
 Author-email: jurnell@civichacker.com
 Requires-Python: >=3.8,<4.0
 Classifier: License :: OSI Approved :: GNU General Public License v3 or later (GPLv3+)
 Classifier: Programming Language :: Python :: 3
```


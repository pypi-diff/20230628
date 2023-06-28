# Comparing `tmp/samshee-0.1.6.tar.gz` & `tmp/samshee-0.1.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "samshee-0.1.6.tar", last modified: Thu Jun  1 10:47:26 2023, max compression
+gzip compressed data, was "samshee-0.1.8.tar", last modified: Wed Jun 28 04:16:55 2023, max compression
```

## Comparing `samshee-0.1.6.tar` & `samshee-0.1.8.tar`

### file list

```diff
@@ -1,20 +1,21 @@
-drwxr-xr-x   0 jakob     (1000) jakob     (1000)        0 2023-06-01 10:47:26.698886 samshee-0.1.6/
--rw-r--r--   0 jakob     (1000) jakob     (1000)     1068 2023-01-20 14:22:02.000000 samshee-0.1.6/LICENSE
--rw-r--r--   0 jakob     (1000) jakob     (1000)     8620 2023-06-01 10:47:26.698886 samshee-0.1.6/PKG-INFO
--rw-r--r--   0 jakob     (1000) jakob     (1000)     6621 2023-02-13 06:26:50.000000 samshee-0.1.6/README.md
--rw-r--r--   0 jakob     (1000) jakob     (1000)      919 2023-06-01 10:40:04.000000 samshee-0.1.6/pyproject.toml
--rw-r--r--   0 jakob     (1000) jakob     (1000)       38 2023-06-01 10:47:26.698886 samshee-0.1.6/setup.cfg
-drwxr-xr-x   0 jakob     (1000) jakob     (1000)        0 2023-06-01 10:47:26.695552 samshee-0.1.6/src/
-drwxr-xr-x   0 jakob     (1000) jakob     (1000)        0 2023-06-01 10:47:26.695552 samshee-0.1.6/src/samshee/
--rw-r--r--   0 jakob     (1000) jakob     (1000)      134 2023-02-13 05:48:16.000000 samshee-0.1.6/src/samshee/__init__.py
--rw-r--r--   0 jakob     (1000) jakob     (1000)     4281 2023-02-15 05:05:57.000000 samshee-0.1.6/src/samshee/samplesheetv2.py
--rw-r--r--   0 jakob     (1000) jakob     (1000)     5605 2023-03-20 07:31:49.000000 samshee-0.1.6/src/samshee/sectionedsheet.py
--rw-r--r--   0 jakob     (1000) jakob     (1000)    26705 2023-06-01 10:39:47.000000 samshee-0.1.6/src/samshee/validation.py
-drwxr-xr-x   0 jakob     (1000) jakob     (1000)        0 2023-06-01 10:47:26.698886 samshee-0.1.6/src/samshee.egg-info/
--rw-r--r--   0 jakob     (1000) jakob     (1000)     8620 2023-06-01 10:47:26.000000 samshee-0.1.6/src/samshee.egg-info/PKG-INFO
--rw-r--r--   0 jakob     (1000) jakob     (1000)      340 2023-06-01 10:47:26.000000 samshee-0.1.6/src/samshee.egg-info/SOURCES.txt
--rw-r--r--   0 jakob     (1000) jakob     (1000)        1 2023-06-01 10:47:26.000000 samshee-0.1.6/src/samshee.egg-info/dependency_links.txt
--rw-r--r--   0 jakob     (1000) jakob     (1000)       17 2023-06-01 10:47:26.000000 samshee-0.1.6/src/samshee.egg-info/requires.txt
--rw-r--r--   0 jakob     (1000) jakob     (1000)        8 2023-06-01 10:47:26.000000 samshee-0.1.6/src/samshee.egg-info/top_level.txt
-drwxr-xr-x   0 jakob     (1000) jakob     (1000)        0 2023-06-01 10:47:26.698886 samshee-0.1.6/tests/
--rw-r--r--   0 jakob     (1000) jakob     (1000)     8092 2023-06-01 10:46:57.000000 samshee-0.1.6/tests/test_validation.py
+drwxr-xr-x   0 jakob     (1000) jakob     (1000)        0 2023-06-28 04:16:55.268589 samshee-0.1.8/
+-rw-r--r--   0 jakob     (1000) jakob     (1000)     1068 2023-01-20 14:22:02.000000 samshee-0.1.8/LICENSE
+-rw-r--r--   0 jakob     (1000) jakob     (1000)     8620 2023-06-28 04:16:55.268589 samshee-0.1.8/PKG-INFO
+-rw-r--r--   0 jakob     (1000) jakob     (1000)     6621 2023-02-13 06:26:50.000000 samshee-0.1.8/README.md
+-rw-r--r--   0 jakob     (1000) jakob     (1000)      919 2023-06-28 04:16:36.000000 samshee-0.1.8/pyproject.toml
+-rw-r--r--   0 jakob     (1000) jakob     (1000)       38 2023-06-28 04:16:55.268589 samshee-0.1.8/setup.cfg
+drwxr-xr-x   0 jakob     (1000) jakob     (1000)        0 2023-06-28 04:16:55.265256 samshee-0.1.8/src/
+drwxr-xr-x   0 jakob     (1000) jakob     (1000)        0 2023-06-28 04:16:55.268589 samshee-0.1.8/src/samshee/
+-rw-r--r--   0 jakob     (1000) jakob     (1000)      134 2023-02-13 05:48:16.000000 samshee-0.1.8/src/samshee/__init__.py
+-rw-r--r--   0 jakob     (1000) jakob     (1000)     4281 2023-02-15 05:05:57.000000 samshee-0.1.8/src/samshee/samplesheetv2.py
+-rw-r--r--   0 jakob     (1000) jakob     (1000)     5695 2023-06-28 04:15:30.000000 samshee-0.1.8/src/samshee/sectionedsheet.py
+-rw-r--r--   0 jakob     (1000) jakob     (1000)    26695 2023-06-22 06:36:42.000000 samshee-0.1.8/src/samshee/validation.py
+drwxr-xr-x   0 jakob     (1000) jakob     (1000)        0 2023-06-28 04:16:55.268589 samshee-0.1.8/src/samshee.egg-info/
+-rw-r--r--   0 jakob     (1000) jakob     (1000)     8620 2023-06-28 04:16:55.000000 samshee-0.1.8/src/samshee.egg-info/PKG-INFO
+-rw-r--r--   0 jakob     (1000) jakob     (1000)      357 2023-06-28 04:16:55.000000 samshee-0.1.8/src/samshee.egg-info/SOURCES.txt
+-rw-r--r--   0 jakob     (1000) jakob     (1000)        1 2023-06-28 04:16:55.000000 samshee-0.1.8/src/samshee.egg-info/dependency_links.txt
+-rw-r--r--   0 jakob     (1000) jakob     (1000)       17 2023-06-28 04:16:55.000000 samshee-0.1.8/src/samshee.egg-info/requires.txt
+-rw-r--r--   0 jakob     (1000) jakob     (1000)        8 2023-06-28 04:16:55.000000 samshee-0.1.8/src/samshee.egg-info/top_level.txt
+drwxr-xr-x   0 jakob     (1000) jakob     (1000)        0 2023-06-28 04:16:55.268589 samshee-0.1.8/tests/
+-rw-r--r--   0 jakob     (1000) jakob     (1000)      890 2023-06-28 04:14:45.000000 samshee-0.1.8/tests/test_io.py
+-rw-r--r--   0 jakob     (1000) jakob     (1000)     8092 2023-06-01 10:46:57.000000 samshee-0.1.8/tests/test_validation.py
```

### Comparing `samshee-0.1.6/LICENSE` & `samshee-0.1.8/LICENSE`

 * *Files identical despite different names*

### Comparing `samshee-0.1.6/PKG-INFO` & `samshee-0.1.8/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: samshee
-Version: 0.1.6
+Version: 0.1.8
 Summary: A schema-agnostic parser and writer for illumina sample sheets v2.
 Author-email: Jakob Simeth <jakob.simeth@ukr.de>
 License: MIT License
         
         Copyright © 2023 Jakob Simeth
         
         Permission is hereby granted, free of charge, to any person obtaining a copy
```

### Comparing `samshee-0.1.6/README.md` & `samshee-0.1.8/README.md`

 * *Files identical despite different names*

### Comparing `samshee-0.1.6/pyproject.toml` & `samshee-0.1.8/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools>=61.0"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "samshee"
-version = "0.1.6"
+version = "0.1.8"
 authors = [
   { name="Jakob Simeth", email="jakob.simeth@ukr.de" }
 ]
 description="A schema-agnostic parser and writer for illumina sample sheets v2."
 readme = "README.md"
 license={file = "LICENSE"}
 requires-python = ">=3.9"
```

### Comparing `samshee-0.1.6/src/samshee/samplesheetv2.py` & `samshee-0.1.8/src/samshee/samplesheetv2.py`

 * *Files identical despite different names*

### Comparing `samshee-0.1.6/src/samshee/sectionedsheet.py` & `samshee-0.1.8/src/samshee/sectionedsheet.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from pathlib import Path
 from collections import OrderedDict
 from typing import TypeAlias, Union
 import re
-from io import StringIO
+from io import StringIO, IOBase
 import csv
 import json
 
 """A simple value type."""
 ValueType: TypeAlias = Union[str, int, float, bool]
 
 
@@ -141,17 +141,19 @@
             s = parse_settings(content.rstrip("\n "))
             res[name] = s
         else:
             res[name] = parse_data(content.rstrip("\n "))
     return res
 
 
-def read_sectionedsheet(filename: Union[Path, str]) -> SectionedSheet:
+def read_sectionedsheet(file: Union[Path, str, IOBase]) -> SectionedSheet:
     """reads a file and parses it to a SectionedSheet"""
-    with open(filename, "r") as f:
+    if isinstance(file, IOBase):
+        return parse_sectionedsheet(file.read())
+    with open(file, "r") as f:
         return parse_sectionedsheet(f.read())
 
 
 def parse_sectionedsheet_from_json(
     jsonstr: str, explicitly_settings_section=["header", "reads"]
 ) -> SectionedSheet:
     """parses a json string to a SectionedSheet"""
```

### Comparing `samshee-0.1.6/src/samshee/validation.py` & `samshee-0.1.8/src/samshee/validation.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 import itertools
 import re
 from typing import Callable, cast, Mapping, Tuple, Optional
 
-from jsonschema import Draft202012Validator
+from jsonschema import Draft7Validator
 from jsonschema.exceptions import ErrorTree, best_match
 
 from samshee.sectionedsheet import SectionedSheet, Settings, Data
 
 #
 # a schema that validates a sectioned sheet to be a samplesheet
 # this follows
@@ -564,15 +564,15 @@
                 )
 
     for i, schema in enumerate(validation):
         if isinstance(schema, dict):
             name = f"anonymous validator #{i}"
             if "title" in schema:
                 name = schema["title"]
-            v = Draft202012Validator(schema).iter_errors(doc)
+            v = Draft7Validator(schema).iter_errors(doc)
             errs = []
             for err in v:
                 errs.append((err.json_path, err.message))
             if len(errs) == 1:
                 raise Exception(
                     f"{name} raised validation error: {errs[0][0]}: {errs[0][1]}"
                 )
```

### Comparing `samshee-0.1.6/src/samshee.egg-info/PKG-INFO` & `samshee-0.1.8/src/samshee.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: samshee
-Version: 0.1.6
+Version: 0.1.8
 Summary: A schema-agnostic parser and writer for illumina sample sheets v2.
 Author-email: Jakob Simeth <jakob.simeth@ukr.de>
 License: MIT License
         
         Copyright © 2023 Jakob Simeth
         
         Permission is hereby granted, free of charge, to any person obtaining a copy
```

### Comparing `samshee-0.1.6/tests/test_validation.py` & `samshee-0.1.8/tests/test_validation.py`

 * *Files identical despite different names*


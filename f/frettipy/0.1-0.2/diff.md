# Comparing `tmp/frettipy-0.1.tar.gz` & `tmp/frettipy-0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "frettipy-0.1.tar", last modified: Thu Jun 30 19:37:19 2022, max compression
+gzip compressed data, was "frettipy-0.2.tar", last modified: Wed Jun 28 13:14:23 2023, max compression
```

## Comparing `frettipy-0.1.tar` & `frettipy-0.2.tar`

### file list

```diff
@@ -1,13 +1,13 @@
-drwxr-xr-x   0 jan       (1000) jan       (1000)        0 2022-06-30 19:37:19.148882 frettipy-0.1/
--rw-rw-r--   0 jan       (1000) jan       (1000)      638 2021-05-27 16:42:16.000000 frettipy-0.1/LICENSE
--rw-r--r--   0 jan       (1000) jan       (1000)     1402 2022-06-30 19:37:19.148882 frettipy-0.1/PKG-INFO
--rw-r--r--   0 jan       (1000) jan       (1000)     1008 2022-06-30 18:33:07.000000 frettipy-0.1/README.md
--rwxr-xr-x   0 jan       (1000) jan       (1000)     6687 2022-06-30 14:28:29.000000 frettipy-0.1/frettipy
-drwxr-xr-x   0 jan       (1000) jan       (1000)        0 2022-06-30 19:37:19.148882 frettipy-0.1/frettipy.egg-info/
--rw-r--r--   0 jan       (1000) jan       (1000)     1402 2022-06-30 19:37:18.000000 frettipy-0.1/frettipy.egg-info/PKG-INFO
--rw-r--r--   0 jan       (1000) jan       (1000)      188 2022-06-30 19:37:19.000000 frettipy-0.1/frettipy.egg-info/SOURCES.txt
--rw-r--r--   0 jan       (1000) jan       (1000)        1 2022-06-30 19:37:18.000000 frettipy-0.1/frettipy.egg-info/dependency_links.txt
--rw-r--r--   0 jan       (1000) jan       (1000)        1 2022-06-30 19:37:19.000000 frettipy-0.1/frettipy.egg-info/top_level.txt
--rw-rw-r--   0 jan       (1000) jan       (1000)       94 2021-05-27 16:51:37.000000 frettipy-0.1/pyproject.toml
--rw-rw-r--   0 jan       (1000) jan       (1000)      459 2022-06-30 19:37:19.148882 frettipy-0.1/setup.cfg
--rwxrwxr-x   0 jan       (1000) jan       (1000)       62 2021-05-27 16:50:49.000000 frettipy-0.1/setup.py
+drwxr-xr-x   0 jan       (1000) jan       (1000)        0 2023-06-28 13:14:23.337445 frettipy-0.2/
+-rw-r--r--   0 jan       (1000) jan       (1000)      643 2023-01-02 15:13:56.000000 frettipy-0.2/LICENSE
+-rw-r--r--   0 jan       (1000) jan       (1000)     1772 2023-06-28 13:14:23.337445 frettipy-0.2/PKG-INFO
+-rw-r--r--   0 jan       (1000) jan       (1000)     1378 2023-06-28 12:58:31.000000 frettipy-0.2/README.md
+-rwxr-xr-x   0 jan       (1000) jan       (1000)     7515 2023-06-28 13:11:01.000000 frettipy-0.2/frettipy
+drwxr-xr-x   0 jan       (1000) jan       (1000)        0 2023-06-28 13:14:23.337445 frettipy-0.2/frettipy.egg-info/
+-rw-r--r--   0 jan       (1000) jan       (1000)     1772 2023-06-28 13:14:23.000000 frettipy-0.2/frettipy.egg-info/PKG-INFO
+-rw-r--r--   0 jan       (1000) jan       (1000)      188 2023-06-28 13:14:23.000000 frettipy-0.2/frettipy.egg-info/SOURCES.txt
+-rw-r--r--   0 jan       (1000) jan       (1000)        1 2023-06-28 13:14:23.000000 frettipy-0.2/frettipy.egg-info/dependency_links.txt
+-rw-r--r--   0 jan       (1000) jan       (1000)        1 2023-06-28 13:14:23.000000 frettipy-0.2/frettipy.egg-info/top_level.txt
+-rw-rw-r--   0 jan       (1000) jan       (1000)       94 2021-05-28 06:56:41.000000 frettipy-0.2/pyproject.toml
+-rw-r--r--   0 jan       (1000) jan       (1000)      459 2023-06-28 13:14:23.337445 frettipy-0.2/setup.cfg
+-rwxr-xr-x   0 jan       (1000) jan       (1000)       62 2023-01-02 15:13:56.000000 frettipy-0.2/setup.py
```

### Comparing `frettipy-0.1/LICENSE` & `frettipy-0.2/LICENSE`

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-Copyright (C) 2021 Jan Berges
+Copyright (C) 2021-2023 Jan Berges
 
 Permission to use, copy, modify, and/or distribute this software for any
 purpose with or without fee is hereby granted.
 
 THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH
 REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY
 AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT,
```

### Comparing `frettipy-0.1/PKG-INFO` & `frettipy-0.2/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: frettipy
-Version: 0.1
+Version: 0.2
 Summary: No fretting about pretty Python
 Home-page: https://github.com/janberges/frettipy
 Author: Jan Berges
 Author-email: 
 Classifier: Programming Language :: Python
 Classifier: License :: Freely Distributable
 Classifier: Operating System :: POSIX :: Linux
@@ -26,21 +26,32 @@
 * Slices: no spaces around slice operators
 * Dictionaries: spaces after colon (but not before)
 * Spaces around assignment operators
 * Block initiation: no spaces before colon
 * Spaces after commas (but not before)
 * No double spaces
 * Single space between non-whitespace character and comment
+* No space before opening bracket (except after keyword)
 * Four spaces instead of tabs
 * No trailing whitespace
 * No double blank lines
 * No blank line at end of file
 * No blank line at beginning of file
 
-**Use with care! Python files are modified recursively and in place!**
+## Synopsis
+
+This script formats Python source code following the above style conventions.
+
+    frettipy [-f] [-r] FILE
+
+If `-f` is present, `FILE` **is modified in place!** Keep a copy or use version
+control. Otherwise the intended modifications are shown without changing `FILE`.
+
+If `-r` is present and `FILE` is a directory, **all .py files in the directory
+tree are processed!**
 
 ## Installation
 
 Either from PyPI:
 
     python3 -m pip install frettipy
```

### Comparing `frettipy-0.1/README.md` & `frettipy-0.2/README.md`

 * *Files 18% similar despite different names*

```diff
@@ -12,21 +12,32 @@
 * Slices: no spaces around slice operators
 * Dictionaries: spaces after colon (but not before)
 * Spaces around assignment operators
 * Block initiation: no spaces before colon
 * Spaces after commas (but not before)
 * No double spaces
 * Single space between non-whitespace character and comment
+* No space before opening bracket (except after keyword)
 * Four spaces instead of tabs
 * No trailing whitespace
 * No double blank lines
 * No blank line at end of file
 * No blank line at beginning of file
 
-**Use with care! Python files are modified recursively and in place!**
+## Synopsis
+
+This script formats Python source code following the above style conventions.
+
+    frettipy [-f] [-r] FILE
+
+If `-f` is present, `FILE` **is modified in place!** Keep a copy or use version
+control. Otherwise the intended modifications are shown without changing `FILE`.
+
+If `-r` is present and `FILE` is a directory, **all .py files in the directory
+tree are processed!**
 
 ## Installation
 
 Either from PyPI:
 
     python3 -m pip install frettipy
```

### Comparing `frettipy-0.1/frettipy` & `frettipy-0.2/frettipy`

 * *Files 13% similar despite different names*

```diff
@@ -1,14 +1,18 @@
 #!/usr/bin/env python3
 
 """Usage: frettipy [-f] [-r] FILE
 
 This script formats Python source code following the below style conventions.
-IF -f IS GIVEN, FILE WILL BE MODIFIED IN PLACE! If -r IS GIVEN AND FILE IS A
-DIRECTORY, ALL .py FILES IN THE DIRECTORY TREE WILL BE PROCESSED!
+
+If `-f` is present, `FILE` **is modified in place!** Keep a copy or use version
+control. Otherwise the intended modifications are shown without changing `FILE`.
+
+If `-r` is present and `FILE` is a directory, **all .py files in the directory
+tree are processed!**
 """
 
 import re
 import sys
 
 # parse arguments:
 
@@ -102,16 +106,25 @@
 
 for n in range(len(groups) - N, len(groups)):
     groups[n] = dereference(groups[n])
 
 # isolate expressions in brackets:
 
 while re.search('[([{]', code):
+    count = 0
+
     for opener, closer in '()', '[]', '{}':
-        code = re.sub(r'\%s[^()[\]{}]*\%s' % (opener, closer), replace, code)
+        code, N = re.subn(r'\%s[^()[\]{}]*\%s' % (opener, closer), replace,
+            code)
+
+        count += N
+
+    if not count:
+        print('\033[0;33mUnmatched parenthesis found!\033[0m')
+        break
 
 code, N = re.subn(r'np\.array___\d+___', replace, code)
 
 for n in range(len(groups) - N, len(groups)):
     groups[n] = dereference(groups[n])
 
 # define overarching group for convenience:
@@ -121,17 +134,20 @@
 # define operators:
 
 unary = r'\+|-|~|\^'
 binary = r'\+|-|\*\*?|//?|%|&|\||<<|>>'
 comparison = '<=?|>=?|=='
 assignment = '(%s)?=' % binary
 
-# define keywords that indicate start of expression:
+# define keywords, some of which indicate start of expression:
 
-keywords = {'return', 'if', 'else', 'in'}
+keywords = {'and', 'as', 'assert', 'async', 'await', 'break', 'class',
+    'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for',
+    'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not',
+    'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield'}
 
 # fix style of all groups:
 
 for n in range(len(groups)):
     if re.match(r'[\'"#]|np\.array', groups[n]):
         # PREFER SINGLE OVER DOUBLE QUOTATION MARKS:
         groups[n] = re.sub(r'^"([^"\']*)"$', r"'\1'", groups[n])
@@ -193,14 +209,20 @@
     groups[n] = re.sub(r'(?<=\S) {2,}(?=\S)', ' ', groups[n])
 
     # SINGLE SPACE BETWEEN NON-WHITESPACE CHARACTER AND COMMENT:
     groups[n] = re.sub(r'(?<=\S)___\d+___', lambda match:
         (' ' if re.match('#', place(match)) else '') + match.group(0),
         groups[n])
 
+    # NO SPACE BEFORE OPENING BRACKET (EXCEPT AFTER KEYWORD):
+    groups[n] = re.sub(r'(\w+) *(___\d+___)', lambda match:
+        match.group(1) + ' ' * (match.group(1) in keywords) + match.group(2)
+        if re.match('[([{]', dereference(match.group(2))) else match.group(0),
+        groups[n])
+
 # reinsert isolated groups:
 
 code = dereference(code)
 
 # FOUR SPACES INSTEAD OF TABS:
 code = re.sub(r'\t', ' ' * 4, code)
```

### Comparing `frettipy-0.1/frettipy.egg-info/PKG-INFO` & `frettipy-0.2/frettipy.egg-info/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: frettipy
-Version: 0.1
+Version: 0.2
 Summary: No fretting about pretty Python
 Home-page: https://github.com/janberges/frettipy
 Author: Jan Berges
 Author-email: 
 Classifier: Programming Language :: Python
 Classifier: License :: Freely Distributable
 Classifier: Operating System :: POSIX :: Linux
@@ -26,21 +26,32 @@
 * Slices: no spaces around slice operators
 * Dictionaries: spaces after colon (but not before)
 * Spaces around assignment operators
 * Block initiation: no spaces before colon
 * Spaces after commas (but not before)
 * No double spaces
 * Single space between non-whitespace character and comment
+* No space before opening bracket (except after keyword)
 * Four spaces instead of tabs
 * No trailing whitespace
 * No double blank lines
 * No blank line at end of file
 * No blank line at beginning of file
 
-**Use with care! Python files are modified recursively and in place!**
+## Synopsis
+
+This script formats Python source code following the above style conventions.
+
+    frettipy [-f] [-r] FILE
+
+If `-f` is present, `FILE` **is modified in place!** Keep a copy or use version
+control. Otherwise the intended modifications are shown without changing `FILE`.
+
+If `-r` is present and `FILE` is a directory, **all .py files in the directory
+tree are processed!**
 
 ## Installation
 
 Either from PyPI:
 
     python3 -m pip install frettipy
```


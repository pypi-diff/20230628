# Comparing `tmp/FiveMCipherFinder-1.6.0.tar.gz` & `tmp/FiveMCipherFinder-1.7.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "FiveMCipherFinder-1.6.0.tar", last modified: Sun Oct  2 12:03:48 2022, max compression
+gzip compressed data, was "FiveMCipherFinder-1.7.0.tar", last modified: Wed Jun 28 12:33:48 2023, max compression
```

## Comparing `FiveMCipherFinder-1.6.0.tar` & `FiveMCipherFinder-1.7.0.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-10-02 12:03:48.245931 FiveMCipherFinder-1.6.0/
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-10-02 12:03:48.245931 FiveMCipherFinder-1.6.0/FiveMCipherFinder.egg-info/
--rw-r--r--   0 runner    (1001) docker     (121)     1794 2022-10-02 12:03:48.000000 FiveMCipherFinder-1.6.0/FiveMCipherFinder.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)      307 2022-10-02 12:03:48.000000 FiveMCipherFinder-1.6.0/FiveMCipherFinder.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2022-10-02 12:03:48.000000 FiveMCipherFinder-1.6.0/FiveMCipherFinder.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (121)       50 2022-10-02 12:03:48.000000 FiveMCipherFinder-1.6.0/FiveMCipherFinder.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (121)       13 2022-10-02 12:03:48.000000 FiveMCipherFinder-1.6.0/FiveMCipherFinder.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (121)     1078 2022-10-02 12:03:35.000000 FiveMCipherFinder-1.6.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (121)     1794 2022-10-02 12:03:48.245931 FiveMCipherFinder-1.6.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)     1168 2022-10-02 12:03:35.000000 FiveMCipherFinder-1.6.0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-10-02 12:03:48.245931 FiveMCipherFinder-1.6.0/cipherFinder/
--rw-r--r--   0 runner    (1001) docker     (121)       64 2022-10-02 12:03:35.000000 FiveMCipherFinder-1.6.0/cipherFinder/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)     4242 2022-10-02 12:03:35.000000 FiveMCipherFinder-1.6.0/cipherFinder/finder.py
--rw-r--r--   0 runner    (1001) docker     (121)      107 2022-10-02 12:03:35.000000 FiveMCipherFinder-1.6.0/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (121)      737 2022-10-02 12:03:48.245931 FiveMCipherFinder-1.6.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (121)       37 2022-10-02 12:03:35.000000 FiveMCipherFinder-1.6.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:33:48.198967 FiveMCipherFinder-1.7.0/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:33:48.198967 FiveMCipherFinder-1.7.0/FiveMCipherFinder.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2893 2023-06-28 12:33:48.000000 FiveMCipherFinder-1.7.0/FiveMCipherFinder.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      307 2023-06-28 12:33:48.000000 FiveMCipherFinder-1.7.0/FiveMCipherFinder.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:33:48.000000 FiveMCipherFinder-1.7.0/FiveMCipherFinder.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       50 2023-06-28 12:33:48.000000 FiveMCipherFinder-1.7.0/FiveMCipherFinder.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-28 12:33:48.000000 FiveMCipherFinder-1.7.0/FiveMCipherFinder.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     1078 2023-06-28 12:33:38.000000 FiveMCipherFinder-1.7.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     2893 2023-06-28 12:33:48.198967 FiveMCipherFinder-1.7.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2267 2023-06-28 12:33:38.000000 FiveMCipherFinder-1.7.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:33:48.198967 FiveMCipherFinder-1.7.0/cipherFinder/
+-rw-r--r--   0 runner    (1001) docker     (123)       64 2023-06-28 12:33:38.000000 FiveMCipherFinder-1.7.0/cipherFinder/__init__.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     5319 2023-06-28 12:33:38.000000 FiveMCipherFinder-1.7.0/cipherFinder/finder.py
+-rw-r--r--   0 runner    (1001) docker     (123)       92 2023-06-28 12:33:38.000000 FiveMCipherFinder-1.7.0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 12:33:48.198967 FiveMCipherFinder-1.7.0/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (123)       37 2023-06-28 12:33:38.000000 FiveMCipherFinder-1.7.0/setup.py
```

### Comparing `FiveMCipherFinder-1.6.0/LICENSE` & `FiveMCipherFinder-1.7.0/LICENSE`

 * *Files identical despite different names*

### Comparing `FiveMCipherFinder-1.6.0/cipherFinder/finder.py` & `FiveMCipherFinder-1.7.0/cipherFinder/finder.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-#!/bin/python3.8
+#!/bin/python3.11
 
 #  Copyright (c) 2022. - exersalza
 #
 #  Permission is hereby granted, free of charge, to any person obtaining a copy
 #  of this software and associated documentation files (the "Software"), to deal
 #  in the Software without restriction, including without limitation the rights
 #  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
@@ -20,42 +20,105 @@
 #  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 #  SOFTWARE.
 from __future__ import annotations
 
 import os
 import re
 import sys
+import platform
+
 from datetime import datetime as dt
+from gibberish_detector import detector
 
 REGEX = r'(((\\x|\\u)([a-fA-F0-9]{2})){2})'
+COLORS = ['\033[0m', '\033[91m', '\033[92m']
+
+det = detector.create_from_model('big.model')
+
+log = []
 
 
 def validate_lines(lines) -> list[tuple]:
     """ Validate the lines that are given through the 'lines' parameter.
 
     Parameters
     ----------
     lines : list
         The lines from the current read file.
 
     Returns
     -------
     list[tuple]
-        A list with infected lines (or false positives by AntiCheat or obfuscated code)
+        A list with infected lines 
+        (or false positives by AntiCheat or obfuscated code)
     """
 
     ret = []
 
     for ln, line in enumerate(lines, start=1):  # ln: lineNumber
         if re.findall(REGEX, rf'{line}', re.MULTILINE and re.IGNORECASE):
             ret.append((ln, line))
 
     return ret
 
 
+def do_gibberish_check(lines) -> list[tuple[str, int]]:
+    """ Do a check if the given lines are making any sens.
+    Can still throw false-positives
+
+    Parameters
+    ----------
+    lines : list
+        The lines from the current read file.
+
+    Returns
+    -------
+    list[tuple[str, int]]
+        A Tuple List with infected lines or false positives
+        as in `validate_lines`.
+
+    """
+    l_counter = 1
+    matches = []
+
+    for i in lines:
+        if 'local' in i and det.is_gibberish(rf'{i}'):
+            matches.append((l_counter, i))
+
+        l_counter += 1
+    return matches
+
+
+def check_file(d, file, count) -> tuple[int, int]: 
+    with open(f'{d}/{file}', 'r', encoding='utf-8') as f:
+        try:
+            lines = f.readlines()
+        except UnicodeDecodeError:
+            print(f'Can\'t decode `{d}/{file}`.')
+            return 1, count
+        
+        match = validate_lines(lines)
+        
+        if '--v2' in sys.argv:
+            match += do_gibberish_check(lines)
+
+        if match:
+            for ln, line in match:
+                path = d.replace('\\', '/') + f'/{file}'
+                to_log = f'File: {path}\nLineNumber: {ln}\n'
+
+                if '--verbose' in sys.argv:  # Log in console.
+                    print(to_log)
+
+
+                log.append(to_log + f'Line: {line!r}\n----------------\n')
+                count += 1
+    return 0, count
+
+
 def main() -> int:
     """ Validates lua files.
 
     Usage:
     ------
     Run the program: `find-cipher <path> [exclude path] [--verbose]`.
 
@@ -76,56 +139,48 @@
         Return code
     """
 
     if '-h' in sys.argv:
         print(main.__doc__)
         return 0
 
-    log = []
-    count = 0
     pattern = ''.join([(i.replace(',', ')|(') if '--' not in i else '') for i in sys.argv[2:]])
+    local_path = '.'
+    count = 0 
 
-    for d, _, files in os.walk(sys.argv[1] if len(sys.argv) > 1 else '.'):
+    if len(sys.argv) > 1 and '--' not in sys.argv[1]:
+        local_path = sys.argv[1]
+    
+    for d, _, files in os.walk(local_path):
         if pattern and re.findall(f'{"(" + pattern + ")"}', fr'{d}'.format(d=d), re.MULTILINE and re.IGNORECASE):
             continue
 
         for file in files:
             if '.lua' not in file:
                 continue
 
-            with open(f'{d}/{file}', 'r', encoding='utf-8') as f:
-                try:
-                    lines = f.readlines()
-                except UnicodeDecodeError:
-                    print(f'Can\'t decode `{d}/{file}`.')
-                    continue
-
-                match = validate_lines(lines)
-
-                if match:
-                    for ln, line in match:
-                        path = d.replace('\\', '/') + f'/{file}'
-                        to_log = f'File: {path}\nLineNumber: {ln}\n'
-
-                        if '--verbose' in sys.argv:  # Log in console.
-                            print(to_log)
+            _, count = check_file(d, file, count)
+    # Write log
+    
+    red = ''
+    green = ''
+    white = ''
 
-                        log.append(to_log + f'Line: \'{line}\'\n----------------\n')
-                        count += 1
+    if 'linux' in platform.platform().lower():
+        white, red, green = COLORS
 
-    # Write log
     if log:
         with open(f'CipherLog-{dt.now():%H-%M-%S}.txt', 'w+', encoding='utf-8') as f:
             f.writelines(log)
-
-        print('\033[91mOh no, the program find a spy in your files x.x '
-              f'Check the CipherLog.txt file for location and trigger. {count} where found!'
-              '\033[0m\n#staysafe')
+        
+        print(f'{red}Oh no, the program found a spy in your files x.x '
+              f'Check the CipherLog.txt for location and trigger. {count} where found!'
+              f'{white}\n#staysafe')
         return 0
-
-    print('\033[92mNice! There where no Cipher\'s found!\033[0m')
+    
+    print(f'{green}Nice! There were no Cipher\'s found!{white}')
 
     return 0
 
 
 if __name__ == '__main__':
     sys.exit(main())
```

### Comparing `FiveMCipherFinder-1.6.0/setup.cfg` & `FiveMCipherFinder-1.7.0/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = FiveMCipherFinder
-version = 1.6.0
+version = 1.7.0
 description = Finds Cipher in lua scripts.
 long_description = file: README.md
 long_description_content_type = text/markdown
 license = MIT
 author = exersalza
 url = https://github.com/exersalza/FivemCipherFinder
 project_urls =
```


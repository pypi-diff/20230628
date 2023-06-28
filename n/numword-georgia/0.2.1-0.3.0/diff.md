# Comparing `tmp/numword-georgia-0.2.1.tar.gz` & `tmp/numword_georgia-0.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "numword-georgia-0.2.1.tar", max compression
+gzip compressed data, last modified: Sun Feb  2 00:00:00 2020, max compression
```

## Comparing `numword-georgia-0.2.1.tar` & `numword_georgia-0.3.0.tar`

### file list

```diff
@@ -1,7 +1,13 @@
--rw-r--r--   0        0        0     1070 2022-10-04 23:09:17.846237 numword-georgia-0.2.1/LICENSE
--rw-r--r--   0        0        0      651 2022-10-04 23:07:52.820094 numword-georgia-0.2.1/README.md
--rw-r--r--   0        0        0       83 2022-10-04 23:07:52.820094 numword-georgia-0.2.1/numword_georgia/__init__.py
--rw-r--r--   0        0        0     2215 2022-10-04 23:07:52.820094 numword-georgia-0.2.1/numword_georgia/translators.py
--rw-r--r--   0        0        0      825 2022-10-04 23:54:23.373123 numword-georgia-0.2.1/pyproject.toml
--rw-r--r--   0        0        0     1293 1970-01-01 00:00:00.000000 numword-georgia-0.2.1/setup.py
--rw-r--r--   0        0        0     1335 1970-01-01 00:00:00.000000 numword-georgia-0.2.1/PKG-INFO
+-rw-r--r--   0        0        0      229 2020-02-02 00:00:00.000000 numword_georgia-0.3.0/.editorconfig
+-rw-r--r--   0        0        0     1755 2020-02-02 00:00:00.000000 numword_georgia-0.3.0/taplo.toml
+-rw-r--r--   0        0        0      139 2020-02-02 00:00:00.000000 numword_georgia-0.3.0/.vscode/settings.json
+-rw-r--r--   0        0        0      129 2020-02-02 00:00:00.000000 numword_georgia-0.3.0/src/numword_georgia/__about__.py
+-rw-r--r--   0        0        0      183 2020-02-02 00:00:00.000000 numword_georgia-0.3.0/src/numword_georgia/__init__.py
+-rw-r--r--   0        0        0     2139 2020-02-02 00:00:00.000000 numword_georgia-0.3.0/src/numword_georgia/translators.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 numword_georgia-0.3.0/tests/__init__.py
+-rw-r--r--   0        0        0     3484 2020-02-02 00:00:00.000000 numword_georgia-0.3.0/tests/numword_georgia_test.py
+-rw-r--r--   0        0        0     1819 2020-02-02 00:00:00.000000 numword_georgia-0.3.0/.gitignore
+-rw-r--r--   0        0        0     1070 2020-02-02 00:00:00.000000 numword_georgia-0.3.0/LICENSE
+-rw-r--r--   0        0        0     1140 2020-02-02 00:00:00.000000 numword_georgia-0.3.0/README.md
+-rw-r--r--   0        0        0     3485 2020-02-02 00:00:00.000000 numword_georgia-0.3.0/pyproject.toml
+-rw-r--r--   0        0        0     2201 2020-02-02 00:00:00.000000 numword_georgia-0.3.0/PKG-INFO
```

### Comparing `numword-georgia-0.2.1/LICENSE` & `numword_georgia-0.3.0/LICENSE`

 * *Files identical despite different names*

### Comparing `numword-georgia-0.2.1/numword_georgia/translators.py` & `numword_georgia-0.3.0/src/numword_georgia/translators.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,9 +1,11 @@
+# SPDX-FileCopyrightText: 2023-present Sergei Blinov <blinovsv@gmail.com>
+#
+# SPDX-License-Identifier: MIT
 # coding: utf-8
-__author__ = "awnion"
 
 BASE = {
     0: "ნულ",
     1: "ერთ",
     2: "ორ",
     3: "სამ",
     4: "ოთხ",
@@ -85,16 +87,7 @@
             result += BASE[d] + _M
         result += _20
         if n == 0:
             return result + _I
         result += _DA
 
     return result + BASE[n] + _I
-
-
-def main():
-    for number in [5909, 9999, 7000, 7707, 91]:
-        print(f"Number {number} is '{translate(number)}'")
-
-
-if __name__ == "__main__":
-    main()
```


# Comparing `tmp/jkUnicode-2.0.2.tar.gz` & `tmp/jkUnicode-2.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "jkUnicode-2.0.2.tar", last modified: Tue Mar 28 15:32:25 2023, max compression
+gzip compressed data, was "jkUnicode-2.0.3.tar", last modified: Wed Jun 28 08:09:14 2023, max compression
```

## Comparing `jkUnicode-2.0.2.tar` & `jkUnicode-2.0.3.tar`

### file list

```diff
@@ -1,48 +1,48 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-28 15:32:25.263510 jkUnicode-2.0.2/
--rw-r--r--   0 runner    (1001) docker     (123)     1074 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     4707 2023-03-28 15:32:25.263510 jkUnicode-2.0.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     4051 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-28 15:32:25.251509 jkUnicode-2.0.2/lib/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-28 15:32:25.259510 jkUnicode-2.0.2/lib/jkUnicode/
--rw-r--r--   0 runner    (1001) docker     (123)     9246 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1515 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/aglfn.py
--rw-r--r--   0 runner    (1001) docker     (123)    30807 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/aglfnData.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-28 15:32:25.259510 jkUnicode-2.0.2/lib/jkUnicode/cmdline/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/cmdline/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3369 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/cmdline/ortho.py
--rw-r--r--   0 runner    (1001) docker     (123)      847 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/cmdline/uniinfo.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-28 15:32:25.263510 jkUnicode-2.0.2/lib/jkUnicode/json/
--rw-r--r--   0 runner    (1001) docker     (123)       88 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/json/ignored_characters.json
--rw-r--r--   0 runner    (1001) docker     (123)    10148 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/json/ignored_languages.json
--rw-r--r--   0 runner    (1001) docker     (123)  1404126 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/json/language_characters.json
--rw-r--r--   0 runner    (1001) docker     (123)     5251 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/json/languages.json
--rw-r--r--   0 runner    (1001) docker     (123)     5046 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/json/scripts.json
--rw-r--r--   0 runner    (1001) docker     (123)     7063 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/json/territories.json
--rw-r--r--   0 runner    (1001) docker     (123)    30868 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/orthography.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/py.typed
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-28 15:32:25.263510 jkUnicode-2.0.2/lib/jkUnicode/tools/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/tools/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1374 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/tools/helpers.py
--rw-r--r--   0 runner    (1001) docker     (123)     1246 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/tools/jsonhelpers.py
--rw-r--r--   0 runner    (1001) docker     (123)     6745 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/tools/xmlhelpers.py
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/uniBlock.py
--rw-r--r--   0 runner    (1001) docker     (123)    14070 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/uniBlockData.py
--rw-r--r--   0 runner    (1001) docker     (123)    58924 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/uniCase.py
--rw-r--r--   0 runner    (1001) docker     (123)   646770 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/uniCat.py
--rw-r--r--   0 runner    (1001) docker     (123)    54403 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/uniDecomposition.py
--rw-r--r--   0 runner    (1001) docker     (123)  1478896 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/uniName.py
--rw-r--r--   0 runner    (1001) docker     (123)     2383 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/uniNiceName.py
--rw-r--r--   0 runner    (1001) docker     (123)    10119 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/uniRangesBits.py
--rw-r--r--   0 runner    (1001) docker     (123)      368 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/uniScript.py
--rw-r--r--   0 runner    (1001) docker     (123)    74012 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/lib/jkUnicode/uniScriptData.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-28 15:32:25.259510 jkUnicode-2.0.2/lib/jkUnicode.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     4707 2023-03-28 15:32:25.000000 jkUnicode-2.0.2/lib/jkUnicode.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1178 2023-03-28 15:32:25.000000 jkUnicode-2.0.2/lib/jkUnicode.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-28 15:32:25.000000 jkUnicode-2.0.2/lib/jkUnicode.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      100 2023-03-28 15:32:25.000000 jkUnicode-2.0.2/lib/jkUnicode.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-03-28 15:32:25.000000 jkUnicode-2.0.2/lib/jkUnicode.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       10 2023-03-28 15:32:25.000000 jkUnicode-2.0.2/lib/jkUnicode.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-28 15:32:25.000000 jkUnicode-2.0.2/lib/jkUnicode.egg-info/zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)      151 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)     1368 2023-03-28 15:32:25.263510 jkUnicode-2.0.2/setup.cfg
--rwxr-xr-x   0 runner    (1001) docker     (123)      205 2023-03-28 15:32:15.000000 jkUnicode-2.0.2/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:09:14.958651 jkUnicode-2.0.3/
+-rw-r--r--   0 runner    (1001) docker     (123)     1074 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     4707 2023-06-28 08:09:14.958651 jkUnicode-2.0.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4051 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:09:14.950651 jkUnicode-2.0.3/lib/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:09:14.954651 jkUnicode-2.0.3/lib/jkUnicode/
+-rw-r--r--   0 runner    (1001) docker     (123)     9246 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1542 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/aglfn.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30635 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/aglfnData.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:09:14.954651 jkUnicode-2.0.3/lib/jkUnicode/cmdline/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/cmdline/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3369 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/cmdline/ortho.py
+-rw-r--r--   0 runner    (1001) docker     (123)      847 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/cmdline/uniinfo.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:09:14.958651 jkUnicode-2.0.3/lib/jkUnicode/json/
+-rw-r--r--   0 runner    (1001) docker     (123)       88 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/json/ignored_characters.json
+-rw-r--r--   0 runner    (1001) docker     (123)    10148 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/json/ignored_languages.json
+-rw-r--r--   0 runner    (1001) docker     (123)  1404126 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/json/language_characters.json
+-rw-r--r--   0 runner    (1001) docker     (123)     5251 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/json/languages.json
+-rw-r--r--   0 runner    (1001) docker     (123)     5046 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/json/scripts.json
+-rw-r--r--   0 runner    (1001) docker     (123)     7063 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/json/territories.json
+-rw-r--r--   0 runner    (1001) docker     (123)    31126 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/orthography.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/py.typed
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:09:14.958651 jkUnicode-2.0.3/lib/jkUnicode/tools/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/tools/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1374 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/tools/helpers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1246 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/tools/jsonhelpers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6745 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/tools/xmlhelpers.py
+-rw-r--r--   0 runner    (1001) docker     (123)      971 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/uniBlock.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14070 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/uniBlockData.py
+-rw-r--r--   0 runner    (1001) docker     (123)    58924 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/uniCase.py
+-rw-r--r--   0 runner    (1001) docker     (123)   646770 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/uniCat.py
+-rw-r--r--   0 runner    (1001) docker     (123)    54403 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/uniDecomposition.py
+-rw-r--r--   0 runner    (1001) docker     (123)  1478896 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/uniName.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2383 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/uniNiceName.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10119 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/uniRangesBits.py
+-rw-r--r--   0 runner    (1001) docker     (123)      368 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/uniScript.py
+-rw-r--r--   0 runner    (1001) docker     (123)    74012 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/lib/jkUnicode/uniScriptData.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:09:14.954651 jkUnicode-2.0.3/lib/jkUnicode.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     4707 2023-06-28 08:09:14.000000 jkUnicode-2.0.3/lib/jkUnicode.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1178 2023-06-28 08:09:14.000000 jkUnicode-2.0.3/lib/jkUnicode.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 08:09:14.000000 jkUnicode-2.0.3/lib/jkUnicode.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      100 2023-06-28 08:09:14.000000 jkUnicode-2.0.3/lib/jkUnicode.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 08:09:14.000000 jkUnicode-2.0.3/lib/jkUnicode.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 08:09:14.000000 jkUnicode-2.0.3/lib/jkUnicode.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 08:09:14.000000 jkUnicode-2.0.3/lib/jkUnicode.egg-info/zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      151 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)     1368 2023-06-28 08:09:14.958651 jkUnicode-2.0.3/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (123)      205 2023-06-28 08:09:05.000000 jkUnicode-2.0.3/setup.py
```

### Comparing `jkUnicode-2.0.2/LICENSE` & `jkUnicode-2.0.3/LICENSE`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/PKG-INFO` & `jkUnicode-2.0.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jkUnicode
-Version: 2.0.2
+Version: 2.0.3
 Summary: Unicode support libraries
 Home-page: https://pypi.org/project/jkUnicode/
 Author: Jens Kutilek
 License: MIT
 Project-URL: Documentation, https://jkunicode.readthedocs.io/en/latest/
 Project-URL: Source, https://github.com/jenskutilek/jkUnicode
 Project-URL: Tracker, https://github.com/jenskutilek/jkUnicode/issues
```

### Comparing `jkUnicode-2.0.2/README.md` & `jkUnicode-2.0.3/README.md`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/__init__.py` & `jkUnicode-2.0.3/lib/jkUnicode/__init__.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/aglfn.py` & `jkUnicode-2.0.3/lib/jkUnicode/aglfn.py`

 * *Files 5% similar despite different names*

```diff
@@ -12,23 +12,24 @@
     specified glyph name. It handles AGLFN names, uniXXXX names, uXXXXX names,
     ligature names, variant names, and PUA-encoded ornament names (orn001 -
     orn999, starting at 0xEA01).
 
     :param name: The glyph name.
     :type name: str"""
     ornName = compile("^orn[0-9]{3}$")
+    length = len(name)
     if "_" in name:
         return None
     elif "." in name[1:]:
         return None
     elif name in nameToUnicode.keys():
         return nameToUnicode[name]
-    elif name[0:3] == "uni" and len(name) == 7:
+    elif length == 7 and name.startswith("uni"):
         return int(name[3:], 16)
-    elif name[0] == "u" and len(name) == 6:
+    elif length == 6 and name.startswith("u"):
         try:
             return int(name[1:], 16)
         except ValueError:
             return None
     elif ornName.match(name):
         return 0xEA00 + int(name[3:6])
     else:
```

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/aglfnData.py` & `jkUnicode-2.0.3/lib/jkUnicode/aglfnData.py`

 * *Files 1% similar despite different names*

```diff
@@ -330,15 +330,15 @@
     "existential": 0x2203,  # THERE EXISTS
     "f": 0x0066,  # LATIN SMALL LETTER F
     "female": 0x2640,  # FEMALE SIGN
     "figuredash": 0x2012,  # FIGURE DASH
     "filledbox": 0x25A0,  # BLACK SQUARE
     "filledrect": 0x25AC,  # BLACK RECTANGLE
     "five": 0x0035,  # DIGIT FIVE
-    "fiveeighths": 0x215D,  # VULGAR FRACTION FIVE EIGHTHS
+    # "fiveeighths": 0x215D,  # VULGAR FRACTION FIVE EIGHTHS
     "florin": 0x0192,  # LATIN SMALL LETTER F WITH HOOK
     "four": 0x0034,  # DIGIT FOUR
     "fraction": 0x2044,  # FRACTION SLASH
     "franc": 0x20A3,  # FRENCH FRANC SIGN
     "g": 0x0067,  # LATIN SMALL LETTER G
     "gamma": 0x03B3,  # GREEK SMALL LETTER GAMMA
     "gbreve": 0x011F,  # LATIN SMALL LETTER G WITH BREVE
@@ -440,15 +440,15 @@
     "omega": 0x03C9,  # GREEK SMALL LETTER OMEGA
     "omega1": 0x03D6,  # GREEK PI SYMBOL
     "omegatonos": 0x03CE,  # GREEK SMALL LETTER OMEGA WITH TONOS
     "omicron": 0x03BF,  # GREEK SMALL LETTER OMICRON
     "omicrontonos": 0x03CC,  # GREEK SMALL LETTER OMICRON WITH TONOS
     "one": 0x0031,  # DIGIT ONE
     "onedotenleader": 0x2024,  # ONE DOT LEADER
-    "oneeighth": 0x215B,  # VULGAR FRACTION ONE EIGHTH
+    # "oneeighth": 0x215B,  # VULGAR FRACTION ONE EIGHTH
     "onehalf": 0x00BD,  # VULGAR FRACTION ONE HALF
     "onequarter": 0x00BC,  # VULGAR FRACTION ONE QUARTER
     "onethird": 0x2153,  # VULGAR FRACTION ONE THIRD
     "openbullet": 0x25E6,  # WHITE BULLET
     "ordfeminine": 0x00AA,  # FEMININE ORDINAL INDICATOR
     "ordmasculine": 0x00BA,  # MASCULINE ORDINAL INDICATOR
     "orthogonal": 0x221F,  # RIGHT ANGLE
@@ -505,15 +505,15 @@
     "scaron": 0x0161,  # LATIN SMALL LETTER S WITH CARON
     "scedilla": 0x015F,  # LATIN SMALL LETTER S WITH CEDILLA
     "scircumflex": 0x015D,  # LATIN SMALL LETTER S WITH CIRCUMFLEX
     "second": 0x2033,  # DOUBLE PRIME
     "section": 0x00A7,  # SECTION SIGN
     "semicolon": 0x003B,  # SEMICOLON
     "seven": 0x0037,  # DIGIT SEVEN
-    "seveneighths": 0x215E,  # VULGAR FRACTION SEVEN EIGHTHS
+    # "seveneighths": 0x215E,  # VULGAR FRACTION SEVEN EIGHTHS
     "shade": 0x2592,  # MEDIUM SHADE
     "sigma": 0x03C3,  # GREEK SMALL LETTER SIGMA
     "sigma1": 0x03C2,  # GREEK SMALL LETTER FINAL SIGMA
     "similar": 0x223C,  # TILDE OPERATOR
     "six": 0x0036,  # DIGIT SIX
     "slash": 0x002F,  # SOLIDUS
     "smileface": 0x263A,  # WHITE SMILING FACE
@@ -528,15 +528,15 @@
     "tbar": 0x0167,  # LATIN SMALL LETTER T WITH STROKE
     "tcaron": 0x0165,  # LATIN SMALL LETTER T WITH CARON
     "therefore": 0x2234,  # THEREFORE
     "theta": 0x03B8,  # GREEK SMALL LETTER THETA
     "theta1": 0x03D1,  # GREEK THETA SYMBOL
     "thorn": 0x00FE,  # LATIN SMALL LETTER THORN
     "three": 0x0033,  # DIGIT THREE
-    "threeeighths": 0x215C,  # VULGAR FRACTION THREE EIGHTHS
+    # "threeeighths": 0x215C,  # VULGAR FRACTION THREE EIGHTHS
     "threequarters": 0x00BE,  # VULGAR FRACTION THREE QUARTERS
     "tilde": 0x02DC,  # SMALL TILDE
     "tildecomb": 0x0303,  # COMBINING TILDE
     "tonos": 0x0384,  # GREEK TONOS
     "trademark": 0x2122,  # TRADE MARK SIGN
     "triagdn": 0x25BC,  # BLACK DOWN-POINTING TRIANGLE
     "triaglf": 0x25C4,  # BLACK LEFT-POINTING POINTER
@@ -583,16 +583,8 @@
     "ygrave": 0x1EF3,  # LATIN SMALL LETTER Y WITH GRAVE
     "z": 0x007A,  # LATIN SMALL LETTER Z
     "zacute": 0x017A,  # LATIN SMALL LETTER Z WITH ACUTE
     "zcaron": 0x017E,  # LATIN SMALL LETTER Z WITH CARON
     "zdotaccent": 0x017C,  # LATIN SMALL LETTER Z WITH DOT ABOVE
     "zero": 0x0030,  # DIGIT ZERO
     "zeta": 0x03B6,  # GREEK SMALL LETTER ZETA
-    # Local additions:
-    "CR": 0x000D,
-    "NULL": 0x0000,
-    "fi": 0xFB01,
-    "fl": 0xFB02,
-    "onesuperior": 0x00B9,
-    "threesuperior": 0x00B3,
-    "twosuperior": 0x00B2,
 }
```

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/cmdline/ortho.py` & `jkUnicode-2.0.3/lib/jkUnicode/cmdline/ortho.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/cmdline/uniinfo.py` & `jkUnicode-2.0.3/lib/jkUnicode/cmdline/uniinfo.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/json/ignored_languages.json` & `jkUnicode-2.0.3/lib/jkUnicode/json/ignored_languages.json`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/json/language_characters.json` & `jkUnicode-2.0.3/lib/jkUnicode/json/language_characters.json`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/json/languages.json` & `jkUnicode-2.0.3/lib/jkUnicode/json/languages.json`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/json/scripts.json` & `jkUnicode-2.0.3/lib/jkUnicode/json/scripts.json`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/json/territories.json` & `jkUnicode-2.0.3/lib/jkUnicode/json/territories.json`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/orthography.py` & `jkUnicode-2.0.3/lib/jkUnicode/orthography.py`

 * *Files 2% similar despite different names*

```diff
@@ -709,14 +709,36 @@
         ]
 
     def get_almost_supported_punctuation(self) -> List[Orthography]:
         return [
             o for o in self.orthographies if o.almost_supported_punctuation()
         ]
 
+    def get_kern_list(self, include_optional=False) -> Set[Tuple[int, ...]]:
+        """
+        Return a list of character pairs that may appear in any supported
+        orthography for the current cmap.
+
+        :param include_optional: Include optional characters.
+        :type include_optional: bool
+        """
+        import itertools
+
+        m = self.get_supported_orthographies_minimum_inclusive()
+        possible_pairs = set()
+        for ot in m:
+            if include_optional:
+                unicodes = ot.unicodes_base | ot.unicodes_optional
+            else:
+                unicodes = ot.unicodes_base
+            ot_pairs = set(itertools.combinations_with_replacement(unicodes, 2))
+            possible_pairs |= ot_pairs
+        # print([(chr(L), chr(R)) for L, R in sorted(possible_pairs)])
+        return possible_pairs
+
     def __len__(self) -> int:
         """
         Return the number of known orthographies.
         """
         return len(self.orthographies)
 
     def __repr__(self) -> str:
@@ -875,38 +897,23 @@
         m = self.get_almost_supported(n)
         print(
             "Orthographies which can be supported with max. %i additional %s:"
             % (n, "character" if n == 1 else "characters")
         )
         self.print_report(m, "missing_base", bcp47=bcp47)
 
-    def report_kill_list(self, bcp47=False) -> None:
+    def report_kern_list(self, bcp47=False, include_optional=False) -> None:
         """
-        Print a list of character pairs that do not appear in any supported
+        Print a list of character pairs that may appear in any supported
         orthography for the current cmap.
 
         :param bcp47: Output BCP47 subtags instead of names
         :type bcp47: bool
         """
-        import itertools
-
-        m = self.get_supported_orthographies_minimum_inclusive()
-        possible_pairs = set()
-        for ot in m:
-            unicodes = ot.unicodes_base  # | ot.unicodes_optional
-            ot_pairs = set(itertools.combinations_with_replacement(unicodes, 2))
-            name = ot.identifier if bcp47 else ot.name
-            print(
-                f"{name}: {len(unicodes)} characters, "
-                f"{len(ot_pairs)} possible combinations"
-            )
-            possible_pairs |= ot_pairs
-        # for L, R in sorted(list(possible_pairs)):
-        #     print("%s%s" % (chr(L), chr(R)))
-        print(possible_pairs)
+        print(self.get_kern_list(include_optional))
 
     def split_bcp47(self, value: str) -> Tuple[str, str, str]:
         code = value
         script = "DFLT"
         territory = "dflt"
         if "-" in value:
             parts = value.split("-")
```

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/tools/helpers.py` & `jkUnicode-2.0.3/lib/jkUnicode/tools/helpers.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/tools/jsonhelpers.py` & `jkUnicode-2.0.3/lib/jkUnicode/tools/jsonhelpers.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/tools/xmlhelpers.py` & `jkUnicode-2.0.3/lib/jkUnicode/tools/xmlhelpers.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/uniBlock.py` & `jkUnicode-2.0.3/lib/jkUnicode/uniBlock.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/uniBlockData.py` & `jkUnicode-2.0.3/lib/jkUnicode/uniBlockData.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/uniCase.py` & `jkUnicode-2.0.3/lib/jkUnicode/uniCase.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/uniCat.py` & `jkUnicode-2.0.3/lib/jkUnicode/uniCat.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/uniDecomposition.py` & `jkUnicode-2.0.3/lib/jkUnicode/uniDecomposition.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/uniName.py` & `jkUnicode-2.0.3/lib/jkUnicode/uniName.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/uniNiceName.py` & `jkUnicode-2.0.3/lib/jkUnicode/uniNiceName.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/uniRangesBits.py` & `jkUnicode-2.0.3/lib/jkUnicode/uniRangesBits.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode/uniScriptData.py` & `jkUnicode-2.0.3/lib/jkUnicode/uniScriptData.py`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/lib/jkUnicode.egg-info/PKG-INFO` & `jkUnicode-2.0.3/lib/jkUnicode.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jkUnicode
-Version: 2.0.2
+Version: 2.0.3
 Summary: Unicode support libraries
 Home-page: https://pypi.org/project/jkUnicode/
 Author: Jens Kutilek
 License: MIT
 Project-URL: Documentation, https://jkunicode.readthedocs.io/en/latest/
 Project-URL: Source, https://github.com/jenskutilek/jkUnicode
 Project-URL: Tracker, https://github.com/jenskutilek/jkUnicode/issues
```

### Comparing `jkUnicode-2.0.2/lib/jkUnicode.egg-info/SOURCES.txt` & `jkUnicode-2.0.3/lib/jkUnicode.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `jkUnicode-2.0.2/setup.cfg` & `jkUnicode-2.0.3/setup.cfg`

 * *Files 7% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = jkUnicode
-version = 2.0.2
+version = 2.0.3
 description = Unicode support libraries
 long_description = file: README.md
 long_description_content_type = text/markdown; charset=UTF-8
 url = https://pypi.org/project/jkUnicode/
 author = Jens Kutilek
 license = MIT
 license_file = LICENSE
```


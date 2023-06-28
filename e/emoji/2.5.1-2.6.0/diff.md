# Comparing `tmp/emoji-2.5.1.tar.gz` & `tmp/emoji-2.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "emoji-2.5.1.tar", last modified: Thu Jun 15 17:40:47 2023, max compression
+gzip compressed data, was "emoji-2.6.0.tar", last modified: Wed Jun 28 09:02:12 2023, max compression
```

## Comparing `emoji-2.5.1.tar` & `emoji-2.6.0.tar`

### file list

```diff
@@ -1,40 +1,40 @@
-drwxr-xr-x   0 tahir      (501) staff       (20)        0 2023-06-15 17:40:47.604040 emoji-2.5.1/
--rw-r--r--   0 tahir      (501) staff       (20)     4202 2023-06-15 17:36:32.000000 emoji-2.5.1/CHANGES.md
--rw-r--r--   0 tahir      (501) staff       (20)     1483 2023-06-08 08:36:57.000000 emoji-2.5.1/LICENSE.txt
--rw-r--r--   0 tahir      (501) staff       (20)      142 2023-05-24 12:55:25.000000 emoji-2.5.1/MANIFEST.in
--rw-r--r--   0 tahir      (501) staff       (20)     5157 2023-06-15 17:40:47.604136 emoji-2.5.1/PKG-INFO
--rw-r--r--   0 tahir      (501) staff       (20)     3817 2023-06-08 08:34:25.000000 emoji-2.5.1/README.rst
-drwxr-xr-x   0 tahir      (501) staff       (20)        0 2023-06-15 17:40:47.594983 emoji-2.5.1/emoji/
--rw-r--r--   0 tahir      (501) staff       (20)     2342 2023-06-15 17:36:32.000000 emoji-2.5.1/emoji/__init__.py
--rw-r--r--   0 tahir      (501) staff       (20)      929 2023-06-08 08:34:25.000000 emoji-2.5.1/emoji/__init__.pyi
--rw-r--r--   0 tahir      (501) staff       (20)    13513 2023-06-08 14:53:57.000000 emoji-2.5.1/emoji/core.py
--rw-r--r--   0 tahir      (501) staff       (20)     1310 2023-06-08 08:34:25.000000 emoji-2.5.1/emoji/core.pyi
--rw-r--r--   0 tahir      (501) staff       (20)        0 2023-05-24 12:55:25.000000 emoji-2.5.1/emoji/py.typed
--rw-r--r--   0 tahir      (501) staff       (20)    11876 2023-06-15 17:34:39.000000 emoji-2.5.1/emoji/tokenizer.py
--rw-r--r--   0 tahir      (501) staff       (20)     1201 2023-06-08 08:34:25.000000 emoji-2.5.1/emoji/tokenizer.pyi
-drwxr-xr-x   0 tahir      (501) staff       (20)        0 2023-06-15 17:40:47.600147 emoji-2.5.1/emoji/unicode_codes/
--rw-r--r--   0 tahir      (501) staff       (20)     1291 2023-06-08 08:34:25.000000 emoji-2.5.1/emoji/unicode_codes/__init__.py
--rw-r--r--   0 tahir      (501) staff       (20)      243 2023-05-24 12:55:25.000000 emoji-2.5.1/emoji/unicode_codes/__init__.pyi
--rw-r--r--   0 tahir      (501) staff       (20)  2919285 2023-06-08 14:53:57.000000 emoji-2.5.1/emoji/unicode_codes/data_dict.py
--rw-r--r--   0 tahir      (501) staff       (20)      155 2023-05-24 12:55:25.000000 emoji-2.5.1/emoji/unicode_codes/data_dict.pyi
--rw-r--r--   0 tahir      (501) staff       (20)        0 2023-05-24 12:55:25.000000 emoji-2.5.1/emoji/unicode_codes/py.typed
-drwxr-xr-x   0 tahir      (501) staff       (20)        0 2023-06-15 17:40:47.595833 emoji-2.5.1/emoji.egg-info/
--rw-r--r--   0 tahir      (501) staff       (20)     5157 2023-06-15 17:40:47.000000 emoji-2.5.1/emoji.egg-info/PKG-INFO
--rw-r--r--   0 tahir      (501) staff       (20)      734 2023-06-15 17:40:47.000000 emoji-2.5.1/emoji.egg-info/SOURCES.txt
--rw-r--r--   0 tahir      (501) staff       (20)        1 2023-06-15 17:40:47.000000 emoji-2.5.1/emoji.egg-info/dependency_links.txt
--rw-r--r--   0 tahir      (501) staff       (20)       33 2023-06-15 17:40:47.000000 emoji-2.5.1/emoji.egg-info/requires.txt
--rw-r--r--   0 tahir      (501) staff       (20)        6 2023-06-15 17:40:47.000000 emoji-2.5.1/emoji.egg-info/top_level.txt
--rw-r--r--   0 tahir      (501) staff       (20)        1 2023-05-24 12:55:46.000000 emoji-2.5.1/emoji.egg-info/zip-safe
--rw-r--r--   0 tahir      (501) staff       (20)      107 2023-06-15 17:40:47.604379 emoji-2.5.1/setup.cfg
--rw-r--r--   0 tahir      (501) staff       (20)     2674 2023-06-08 08:34:25.000000 emoji-2.5.1/setup.py
-drwxr-xr-x   0 tahir      (501) staff       (20)        0 2023-06-15 17:40:47.603824 emoji-2.5.1/tests/
--rw-r--r--   0 tahir      (501) staff       (20)       45 2023-06-08 08:34:25.000000 emoji-2.5.1/tests/__init__.py
--rw-r--r--   0 tahir      (501) staff       (20)     4997 2023-06-15 17:34:39.000000 emoji-2.5.1/tests/test_analyze.py
--rw-r--r--   0 tahir      (501) staff       (20)    25995 2023-06-08 14:53:57.000000 emoji-2.5.1/tests/test_core.py
--rw-r--r--   0 tahir      (501) staff       (20)     1739 2023-06-08 14:53:57.000000 emoji-2.5.1/tests/test_dict.py
--rw-r--r--   0 tahir      (501) staff       (20)     2139 2023-06-08 14:53:57.000000 emoji-2.5.1/tests/test_nfkc.py
--rw-r--r--   0 tahir      (501) staff       (20)     1355 2023-06-08 08:34:25.000000 emoji-2.5.1/tests/test_unicode_codes.py
--rw-r--r--   0 tahir      (501) staff       (20)     3522 2023-06-08 14:53:57.000000 emoji-2.5.1/tests/test_versions.py
--rw-r--r--   0 tahir      (501) staff       (20)     7928 2023-06-15 17:34:39.000000 emoji-2.5.1/tests/test_zwj_common.py
--rw-r--r--   0 tahir      (501) staff       (20)     6489 2023-06-08 14:53:57.000000 emoji-2.5.1/tests/test_zwj_keep.py
--rw-r--r--   0 tahir      (501) staff       (20)     5502 2023-06-08 14:53:57.000000 emoji-2.5.1/tests/test_zwj_remove.py
+drwxr-xr-x   0 tahir      (501) staff       (20)        0 2023-06-28 09:02:12.315892 emoji-2.6.0/
+-rw-r--r--   0 tahir      (501) staff       (20)     4309 2023-06-28 08:51:40.000000 emoji-2.6.0/CHANGES.md
+-rw-r--r--   0 tahir      (501) staff       (20)     1483 2023-06-08 08:36:57.000000 emoji-2.6.0/LICENSE.txt
+-rw-r--r--   0 tahir      (501) staff       (20)      142 2023-05-24 12:55:25.000000 emoji-2.6.0/MANIFEST.in
+-rw-r--r--   0 tahir      (501) staff       (20)     5157 2023-06-28 09:02:12.315989 emoji-2.6.0/PKG-INFO
+-rw-r--r--   0 tahir      (501) staff       (20)     3817 2023-06-08 08:34:25.000000 emoji-2.6.0/README.rst
+drwxr-xr-x   0 tahir      (501) staff       (20)        0 2023-06-28 09:02:12.305486 emoji-2.6.0/emoji/
+-rw-r--r--   0 tahir      (501) staff       (20)     2358 2023-06-28 08:51:40.000000 emoji-2.6.0/emoji/__init__.py
+-rw-r--r--   0 tahir      (501) staff       (20)      929 2023-06-08 08:34:25.000000 emoji-2.6.0/emoji/__init__.pyi
+-rw-r--r--   0 tahir      (501) staff       (20)    13860 2023-06-28 08:51:40.000000 emoji-2.6.0/emoji/core.py
+-rw-r--r--   0 tahir      (501) staff       (20)     1310 2023-06-08 08:34:25.000000 emoji-2.6.0/emoji/core.pyi
+-rw-r--r--   0 tahir      (501) staff       (20)        0 2023-05-24 12:55:25.000000 emoji-2.6.0/emoji/py.typed
+-rw-r--r--   0 tahir      (501) staff       (20)    11876 2023-06-15 17:34:39.000000 emoji-2.6.0/emoji/tokenizer.py
+-rw-r--r--   0 tahir      (501) staff       (20)     1201 2023-06-08 08:34:25.000000 emoji-2.6.0/emoji/tokenizer.pyi
+drwxr-xr-x   0 tahir      (501) staff       (20)        0 2023-06-28 09:02:12.310639 emoji-2.6.0/emoji/unicode_codes/
+-rw-r--r--   0 tahir      (501) staff       (20)     1291 2023-06-08 08:34:25.000000 emoji-2.6.0/emoji/unicode_codes/__init__.py
+-rw-r--r--   0 tahir      (501) staff       (20)      243 2023-05-24 12:55:25.000000 emoji-2.6.0/emoji/unicode_codes/__init__.pyi
+-rw-r--r--   0 tahir      (501) staff       (20)  2919285 2023-06-08 14:53:57.000000 emoji-2.6.0/emoji/unicode_codes/data_dict.py
+-rw-r--r--   0 tahir      (501) staff       (20)      155 2023-05-24 12:55:25.000000 emoji-2.6.0/emoji/unicode_codes/data_dict.pyi
+-rw-r--r--   0 tahir      (501) staff       (20)        0 2023-05-24 12:55:25.000000 emoji-2.6.0/emoji/unicode_codes/py.typed
+drwxr-xr-x   0 tahir      (501) staff       (20)        0 2023-06-28 09:02:12.306366 emoji-2.6.0/emoji.egg-info/
+-rw-r--r--   0 tahir      (501) staff       (20)     5157 2023-06-28 09:02:12.000000 emoji-2.6.0/emoji.egg-info/PKG-INFO
+-rw-r--r--   0 tahir      (501) staff       (20)      734 2023-06-28 09:02:12.000000 emoji-2.6.0/emoji.egg-info/SOURCES.txt
+-rw-r--r--   0 tahir      (501) staff       (20)        1 2023-06-28 09:02:12.000000 emoji-2.6.0/emoji.egg-info/dependency_links.txt
+-rw-r--r--   0 tahir      (501) staff       (20)       33 2023-06-28 09:02:12.000000 emoji-2.6.0/emoji.egg-info/requires.txt
+-rw-r--r--   0 tahir      (501) staff       (20)        6 2023-06-28 09:02:12.000000 emoji-2.6.0/emoji.egg-info/top_level.txt
+-rw-r--r--   0 tahir      (501) staff       (20)        1 2023-05-24 12:55:46.000000 emoji-2.6.0/emoji.egg-info/zip-safe
+-rw-r--r--   0 tahir      (501) staff       (20)      107 2023-06-28 09:02:12.316230 emoji-2.6.0/setup.cfg
+-rw-r--r--   0 tahir      (501) staff       (20)     2674 2023-06-08 08:34:25.000000 emoji-2.6.0/setup.py
+drwxr-xr-x   0 tahir      (501) staff       (20)        0 2023-06-28 09:02:12.315677 emoji-2.6.0/tests/
+-rw-r--r--   0 tahir      (501) staff       (20)       45 2023-06-08 08:34:25.000000 emoji-2.6.0/tests/__init__.py
+-rw-r--r--   0 tahir      (501) staff       (20)     4997 2023-06-15 17:34:39.000000 emoji-2.6.0/tests/test_analyze.py
+-rw-r--r--   0 tahir      (501) staff       (20)    26522 2023-06-28 08:51:40.000000 emoji-2.6.0/tests/test_core.py
+-rw-r--r--   0 tahir      (501) staff       (20)     1739 2023-06-08 14:53:57.000000 emoji-2.6.0/tests/test_dict.py
+-rw-r--r--   0 tahir      (501) staff       (20)     2139 2023-06-08 14:53:57.000000 emoji-2.6.0/tests/test_nfkc.py
+-rw-r--r--   0 tahir      (501) staff       (20)     1355 2023-06-08 08:34:25.000000 emoji-2.6.0/tests/test_unicode_codes.py
+-rw-r--r--   0 tahir      (501) staff       (20)     3522 2023-06-08 14:53:57.000000 emoji-2.6.0/tests/test_versions.py
+-rw-r--r--   0 tahir      (501) staff       (20)     7928 2023-06-15 17:34:39.000000 emoji-2.6.0/tests/test_zwj_common.py
+-rw-r--r--   0 tahir      (501) staff       (20)     6489 2023-06-08 14:53:57.000000 emoji-2.6.0/tests/test_zwj_keep.py
+-rw-r--r--   0 tahir      (501) staff       (20)     5502 2023-06-08 14:53:57.000000 emoji-2.6.0/tests/test_zwj_remove.py
```

### Comparing `emoji-2.5.1/CHANGES.md` & `emoji-2.6.0/CHANGES.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,14 @@
 emoji
 =====
 
+v2.6.0 (2023-06-28)
+-----
+* Added new function purely_emoji() | Check if a string contains only emojis
+
 v2.5.1 (2023-06-15)
 -----
 * Fix Malformed zero width joiner (\u200d) causes IndexError
 
 v2.5.0 (2023-06-08)
 -----
 * Added support for Multi-person skintones
@@ -20,15 +24,15 @@
 -----
 * Added Indonesian and Simplified Chinese
 * Bug fixing
 
 v2.2.0 (2022-10-31)
 -----
 * Added support for Unicode Version 15
-* Added more translations for existing languages: (similar to Turkish Language)
+* Added more translations for existing languages: (similar to the Turkish Language)
 * Added Readme on how to add a language
 * Fix 2.0.0: sphinx warnings reference target not found
 
 v2.1.0 (2022-09-17)
 -----
 * Added Farsi support
 * Added Trove classifiers for Python 3.10 and 3.11
@@ -39,23 +43,23 @@
 * Removed unused language=None parameters
 * Removed use_alias parameter
 * Removed the get_regexp method
 * Removed emoji_lis
 * Removed distinct_emoji_lis
 * Made the list of languages public: emoji.LANGUAGES = ['en','es','pt','it','fr','de']
 * Updated translations to release-41 (no changes compared to release-40)
-* Generate a documentation for the public functions from the docstrings with Sphinx
+* Generate documentation for the public functions from the docstrings with Sphinx
 * Added some more examples to the README: e.g. how to replace/remove emojis
 * Total count of emojis:  4702
 
 v1.7.0 (2022-03-07)
 -----
 * Added `emoji_list()` and `distinct_emoji_list()`
 * Added deprecation warnings for several functions and variables that will be removed in version 2.0.0.
-  If you don't want to see these warnings, you can stay with 1.6.x. For example in pip/requirements.txt you can pin to 1.6.x with `emoji~=1.6.3`.
+  If you don't want to see these warnings, you can stay with 1.6.x. For example, in pip/requirements.txt you can pin to 1.6.x with `emoji~=1.6.3`.
 
 v1.6.3 (2022-01-15)
 -----
 * Added support for counting unique emojis
 
 v1.6.2 (2021-12-06)
 -----
```

### Comparing `emoji-2.5.1/LICENSE.txt` & `emoji-2.6.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/PKG-INFO` & `emoji-2.6.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: emoji
-Version: 2.5.1
+Version: 2.6.0
 Summary: Emoji for Python
 Home-page: https://github.com/carpedm20/emoji/
 Author: Taehoon Kim, Kevin Wurster
 Author-email: carpedm20@gmail.com
 License: New BSD
 Keywords: emoji
 Classifier: Development Status :: 5 - Production/Stable
```

### Comparing `emoji-2.5.1/README.rst` & `emoji-2.6.0/README.rst`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/emoji/__init__.py` & `emoji-2.6.0/emoji/__init__.py`

 * *Files 5% similar despite different names*

```diff
@@ -15,21 +15,21 @@
 from emoji.core import *
 from emoji.unicode_codes import *
 
 __all__ = [
     # emoji.core
     'emojize', 'demojize', 'analyze', 'config',
     'emoji_list', 'distinct_emoji_list', 'emoji_count',
-    'replace_emoji', 'is_emoji', 'version',
+    'replace_emoji', 'is_emoji', 'purely_emoji', 'version',
     'Token', 'EmojiMatch', 'EmojiMatchZWJ', 'EmojiMatchZWJNonRGI',
     # emoji.unicode_codes
     'EMOJI_DATA', 'STATUS', 'LANGUAGES',
 ]
 
-__version__ = '2.5.1'
+__version__ = '2.6.0'
 __author__ = 'Taehoon Kim, Kevin Wurster'
 __email__ = 'carpedm20@gmail.com'
 # and wursterk@gmail.com, tahir.jalilov@gmail.com
 __source__ = 'https://github.com/carpedm20/emoji/'
 __license__ = '''
 New BSD License
```

### Comparing `emoji-2.5.1/emoji/__init__.pyi` & `emoji-2.6.0/emoji/__init__.pyi`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/emoji/core.py` & `emoji-2.6.0/emoji/core.py`

 * *Files 2% similar despite different names*

```diff
@@ -12,15 +12,15 @@
 
 from emoji import unicode_codes
 from emoji.tokenizer import Token, EmojiMatch, EmojiMatchZWJ, EmojiMatchZWJNonRGI, tokenize, filter_tokens
 
 __all__ = [
     'emojize', 'demojize', 'analyze', 'config',
     'emoji_list', 'distinct_emoji_list', 'emoji_count',
-    'replace_emoji', 'is_emoji', 'version',
+    'replace_emoji', 'is_emoji', 'purely_emoji', 'version',
     'Token', 'EmojiMatch', 'EmojiMatchZWJ', 'EmojiMatchZWJNonRGI',
 ]
 
 _DEFAULT_DELIMITER = ':'
 _EMOJI_NAME_PATTERN = '\\w\\-&.’”“()!#*+?–,/«»\u0300\u0301\u0302\u0303\u0308\u030a\u0327\u064b\u064e\u064f\u0650\u0653\u0654\u3099\u30fb\u309a'
 
 
@@ -310,20 +310,29 @@
     if unique:
         return len(distinct_emoji_list(string))
     return len(emoji_list(string))
 
 
 def is_emoji(string):
     """
-    Returns True if the string is an emoji, and it is "recommended for
+    Returns True if the string is a single emoji, and it is "recommended for
     general interchange" by Unicode.org.
     """
     return string in unicode_codes.EMOJI_DATA
 
 
+def purely_emoji(string: str) -> bool:
+    """
+    Returns True if the string contains only emojis.
+    This might not imply that `is_emoji` for all the characters, for example,
+    if the string contains variation selectors.
+    """
+    return all(isinstance(m.value, EmojiMatch) for m in analyze(string, non_emoji=True))
+
+
 def version(string):
     """
     Returns the Emoji Version of the emoji.
 
     See https://www.unicode.org/reports/tr51/#Versioning for more information.
         >>> emoji.version("😁")
         0.6
```

### Comparing `emoji-2.5.1/emoji/core.pyi` & `emoji-2.6.0/emoji/core.pyi`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/emoji/tokenizer.py` & `emoji-2.6.0/emoji/tokenizer.py`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/emoji/tokenizer.pyi` & `emoji-2.6.0/emoji/tokenizer.pyi`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/emoji/unicode_codes/__init__.py` & `emoji-2.6.0/emoji/unicode_codes/__init__.py`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/emoji/unicode_codes/data_dict.py` & `emoji-2.6.0/emoji/unicode_codes/data_dict.py`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/emoji.egg-info/PKG-INFO` & `emoji-2.6.0/emoji.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: emoji
-Version: 2.5.1
+Version: 2.6.0
 Summary: Emoji for Python
 Home-page: https://github.com/carpedm20/emoji/
 Author: Taehoon Kim, Kevin Wurster
 Author-email: carpedm20@gmail.com
 License: New BSD
 Keywords: emoji
 Classifier: Development Status :: 5 - Production/Stable
```

### Comparing `emoji-2.5.1/emoji.egg-info/SOURCES.txt` & `emoji-2.6.0/emoji.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/setup.py` & `emoji-2.6.0/setup.py`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/tests/test_analyze.py` & `emoji-2.6.0/tests/test_analyze.py`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/tests/test_core.py` & `emoji-2.6.0/tests/test_core.py`

 * *Files 2% similar despite different names*

```diff
@@ -354,14 +354,16 @@
     assert emoji.replace_emoji('Hello 🇫🇷👌', replace) == 'Hello xx'
 
 
 def test_is_emoji():
     assert emoji.is_emoji('😁')
     assert not emoji.is_emoji('H')
     assert emoji.is_emoji('🇫🇷')
+    assert not emoji.is_emoji('🇫🇷🇫🇷')
+    assert not emoji.is_emoji('\ufe0f')  # variation selector
 
 
 def test_long_emoji():
     assert emoji.demojize('This is \U0001F9D1\U0001F3FC\U0000200D\U0001F37C example text') == 'This is :person_feeding_baby_medium-light_skin_tone: example text'
     assert emoji.demojize('This is \U0001f468\U0001f3ff\u200d\u2764\ufe0f\u200d\U0001f468\U0001f3ff example text \U0001F469\U0001F3FB\U0000200D\U0001F91D\U0000200D\U0001F468\U0001F3FF') == 'This is :couple_with_heart_man_man_dark_skin_tone: example text :woman_and_man_holding_hands_light_skin_tone_dark_skin_tone:'
     assert emoji.demojize('This is \U0001f468\U0001f3ff\u200d\u2764\ufe0f\u200d\U0001f468\U0001f3ff\U0001f468\U0001f3ff\u200d\u2764\ufe0f\u200d\U0001f48b\u200d\U0001f468\U0001f3ff example text \U0001F469\U0001F3FB\U0000200D\U0001F91D\U0000200D\U0001F468\U0001F3FF') == 'This is :couple_with_heart_man_man_dark_skin_tone::kiss_man_man_dark_skin_tone: example text :woman_and_man_holding_hands_light_skin_tone_dark_skin_tone:'
     assert emoji.demojize('\U0001F46B\U0001F3FB This is \U0001f468\U0001f3ff\U0001f468\U0001f3ff\u200d\u2764\ufe0f\u200d\U0001f468\U0001f3ff\U0001f468\U0001f3ff\u200d\u2764\ufe0f\u200d\U0001f48b\u200d\U0001f468\U0001f3ff example text \U0001F469\U0001F3FB\U0000200D\U0001F91D\U0000200D\U0001F468\U0001F3FF') == ':woman_and_man_holding_hands_light_skin_tone: This is :man_dark_skin_tone::couple_with_heart_man_man_dark_skin_tone::kiss_man_man_dark_skin_tone: example text :woman_and_man_holding_hands_light_skin_tone_dark_skin_tone:'
@@ -508,7 +510,23 @@
     combined = emoji.emojize(text % ":woman_dark_skin_tone:")
     seperated = emoji.emojize(text % ":woman::dark_skin_tone:")
     assert combined == seperated,  "%r != %r" % (ascii(combined), ascii(seperated))
 
     combined = emoji.emojize(text % ":woman_dark_skin_tone_white_hair:")
     seperated = emoji.emojize(text % ":woman::dark_skin_tone:\u200d:white_hair:")
     assert combined == seperated,  "%r != %r" % (ascii(combined), ascii(seperated))
+
+
+purely_emoji_testdata = [
+    ('\U0001f600\ufe0f', True),
+    ('\U0001f600', True),
+    ('\U0001f600\U0001f600\U0001f600', True),
+    ('abc', False),
+    ('abc\U0001f600', False),
+    ('\U0001f600c', False),
+    ('\u270a\U0001f3fe', True),
+]
+
+
+@pytest.mark.parametrize("string,expected", purely_emoji_testdata)
+def test_purely_emoji(string: str, expected: bool):
+    assert emoji.purely_emoji(string) == expected
```

### Comparing `emoji-2.5.1/tests/test_dict.py` & `emoji-2.6.0/tests/test_dict.py`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/tests/test_nfkc.py` & `emoji-2.6.0/tests/test_nfkc.py`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/tests/test_unicode_codes.py` & `emoji-2.6.0/tests/test_unicode_codes.py`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/tests/test_versions.py` & `emoji-2.6.0/tests/test_versions.py`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/tests/test_zwj_common.py` & `emoji-2.6.0/tests/test_zwj_common.py`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/tests/test_zwj_keep.py` & `emoji-2.6.0/tests/test_zwj_keep.py`

 * *Files identical despite different names*

### Comparing `emoji-2.5.1/tests/test_zwj_remove.py` & `emoji-2.6.0/tests/test_zwj_remove.py`

 * *Files identical despite different names*


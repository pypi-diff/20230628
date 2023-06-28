# Comparing `tmp/reynir-correct-3.4.6.tar.gz` & `tmp/reynir-correct-3.4.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "reynir-correct-3.4.6.tar", last modified: Mon Dec 12 18:47:58 2022, max compression
+gzip compressed data, was "reynir-correct-3.4.7.tar", last modified: Wed Jun 28 10:51:55 2023, max compression
```

## Comparing `reynir-correct-3.4.6.tar` & `reynir-correct-3.4.7.tar`

### file list

```diff
@@ -1,51 +1,51 @@
-drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2022-12-12 18:47:58.334191 reynir-correct-3.4.6/
--rw-r--r--   0 sveinbjorn   (501) staff       (20)     1113 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/LICENSE
--rw-r--r--   0 sveinbjorn   (501) staff       (20)      125 2021-01-18 17:35:45.000000 reynir-correct-3.4.6/MANIFEST.in
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    19701 2022-12-12 18:47:58.332445 reynir-correct-3.4.6/PKG-INFO
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    18295 2022-10-25 22:15:52.000000 reynir-correct-3.4.6/README.rst
--rw-r--r--   0 sveinbjorn   (501) staff       (20)       38 2022-12-12 18:47:58.334394 reynir-correct-3.4.6/setup.cfg
--rw-r--r--   0 sveinbjorn   (501) staff       (20)     4676 2022-12-12 18:45:46.000000 reynir-correct-3.4.6/setup.py
-drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2022-12-12 18:47:58.266791 reynir-correct-3.4.6/src/
--rw-r--r--   0 sveinbjorn   (501) staff       (20)     6148 2022-10-10 15:17:48.000000 reynir-correct-3.4.6/src/.DS_Store
-drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2022-12-12 18:47:58.272964 reynir-correct-3.4.6/src/reynir_correct/
--rw-r--r--   0 sveinbjorn   (501) staff       (20)     6148 2021-09-02 17:49:03.000000 reynir-correct-3.4.6/src/reynir_correct/.DS_Store
--rw-r--r--   0 sveinbjorn   (501) staff       (20)     2453 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/src/reynir_correct/__init__.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)     5342 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/src/reynir_correct/annotation.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    18592 2022-08-08 14:27:16.000000 reynir-correct-3.4.6/src/reynir_correct/checker.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)     4125 2022-12-12 18:46:41.000000 reynir-correct-3.4.6/src/reynir_correct/classifier.py
-drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2022-12-12 18:47:58.283372 reynir-correct-3.4.6/src/reynir_correct/config/
--rw-r--r--   0 sveinbjorn   (501) staff       (20)   134189 2022-12-12 18:46:11.000000 reynir-correct-3.4.6/src/reynir_correct/config/GreynirCorrect.conf
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    33278 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/src/reynir_correct/config/IEC_nonwords.tsv
--rw-r--r--   0 sveinbjorn   (501) staff       (20)   213240 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/src/reynir_correct/config/IceSQuErVersion01.tsv
--rw-r--r--   0 sveinbjorn   (501) staff       (20)  3663001 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/src/reynir_correct/config/Storasnid_ritm.csv
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    18356 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/src/reynir_correct/config/TabooWords.conf
--rw-r--r--   0 sveinbjorn   (501) staff       (20) 18606079 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/src/reynir_correct/config/WrongWords.conf
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    54033 2022-08-08 14:27:16.000000 reynir-correct-3.4.6/src/reynir_correct/errfinder.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)   128080 2022-08-08 14:27:16.000000 reynir-correct-3.4.6/src/reynir_correct/errtokenizer.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)     5044 2022-10-17 19:23:26.000000 reynir-correct-3.4.6/src/reynir_correct/main.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)   121469 2022-12-12 18:46:11.000000 reynir-correct-3.4.6/src/reynir_correct/pattern.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)        0 2020-05-19 01:42:51.000000 reynir-correct-3.4.6/src/reynir_correct/py.typed
-drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2022-12-12 18:47:58.327464 reynir-correct-3.4.6/src/reynir_correct/resources/
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    10664 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/src/reynir_correct/resources/iceloc_prep.json
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    24787 2021-01-18 17:35:45.000000 reynir-correct-3.4.6/src/reynir_correct/resources/nonwords.csv
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    38058 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/src/reynir_correct/settings.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    34965 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/src/reynir_correct/spelling.py
-drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2022-12-12 18:47:58.329834 reynir-correct-3.4.6/src/reynir_correct/tools/
--rw-r--r--   0 sveinbjorn   (501) staff       (20)     2698 2022-08-08 14:27:16.000000 reynir-correct-3.4.6/src/reynir_correct/tools/diffchecker.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)     1062 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/src/reynir_correct/tools/ritmyndirchecker.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)       22 2022-12-12 18:45:46.000000 reynir-correct-3.4.6/src/reynir_correct/version.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    23185 2022-12-12 18:46:11.000000 reynir-correct-3.4.6/src/reynir_correct/wrappers.py
-drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2022-12-12 18:47:58.274870 reynir-correct-3.4.6/src/reynir_correct.egg-info/
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    19701 2022-12-12 18:47:58.000000 reynir-correct-3.4.6/src/reynir_correct.egg-info/PKG-INFO
--rw-r--r--   0 sveinbjorn   (501) staff       (20)     1329 2022-12-12 18:47:58.000000 reynir-correct-3.4.6/src/reynir_correct.egg-info/SOURCES.txt
--rw-r--r--   0 sveinbjorn   (501) staff       (20)        1 2022-12-12 18:47:58.000000 reynir-correct-3.4.6/src/reynir_correct.egg-info/dependency_links.txt
--rw-r--r--   0 sveinbjorn   (501) staff       (20)       54 2022-12-12 18:47:58.000000 reynir-correct-3.4.6/src/reynir_correct.egg-info/entry_points.txt
--rw-r--r--   0 sveinbjorn   (501) staff       (20)       99 2022-12-12 18:47:58.000000 reynir-correct-3.4.6/src/reynir_correct.egg-info/requires.txt
--rw-r--r--   0 sveinbjorn   (501) staff       (20)       15 2022-12-12 18:47:58.000000 reynir-correct-3.4.6/src/reynir_correct.egg-info/top_level.txt
--rw-r--r--   0 sveinbjorn   (501) staff       (20)        1 2022-08-08 14:35:51.000000 reynir-correct-3.4.6/src/reynir_correct.egg-info/zip-safe
-drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2022-12-12 18:47:58.331812 reynir-correct-3.4.6/test/
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    72465 2022-08-08 14:27:16.000000 reynir-correct-3.4.6/test/test_allkinds.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    14454 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/test/test_annotator.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    16007 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/test/test_patterns.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)     2080 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/test/test_serializers.py
--rw-r--r--   0 sveinbjorn   (501) staff       (20)    18470 2022-07-11 13:30:00.000000 reynir-correct-3.4.6/test/test_tokenizer.py
+drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2023-06-28 10:51:55.485947 reynir-correct-3.4.7/
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)     1113 2022-12-20 17:36:46.000000 reynir-correct-3.4.7/LICENSE.txt
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)      125 2021-01-18 17:35:45.000000 reynir-correct-3.4.7/MANIFEST.in
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    20113 2023-06-28 10:51:55.485643 reynir-correct-3.4.7/PKG-INFO
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    18723 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/README.rst
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)       38 2023-06-28 10:51:55.486025 reynir-correct-3.4.7/setup.cfg
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)     4598 2023-06-27 19:12:14.000000 reynir-correct-3.4.7/setup.py
+drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2023-06-28 10:51:55.416807 reynir-correct-3.4.7/src/
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)     6148 2023-05-26 16:44:07.000000 reynir-correct-3.4.7/src/.DS_Store
+drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2023-06-28 10:51:55.433064 reynir-correct-3.4.7/src/reynir_correct/
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)     6148 2022-12-20 17:51:46.000000 reynir-correct-3.4.7/src/reynir_correct/.DS_Store
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)     2408 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/src/reynir_correct/__init__.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)     5342 2022-12-20 17:22:32.000000 reynir-correct-3.4.7/src/reynir_correct/annotation.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    20928 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/src/reynir_correct/checker.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)     4086 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/src/reynir_correct/classifier.py
+drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2023-06-28 10:51:55.448954 reynir-correct-3.4.7/src/reynir_correct/config/
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)   135235 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/src/reynir_correct/config/GreynirCorrect.conf
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    33278 2022-07-11 13:30:00.000000 reynir-correct-3.4.7/src/reynir_correct/config/IEC_nonwords.tsv
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)   213240 2022-07-11 13:30:00.000000 reynir-correct-3.4.7/src/reynir_correct/config/IceSQuErVersion01.tsv
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)  3663001 2022-07-11 13:30:00.000000 reynir-correct-3.4.7/src/reynir_correct/config/Storasnid_ritm.csv
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    18356 2022-12-20 17:22:32.000000 reynir-correct-3.4.7/src/reynir_correct/config/TabooWords.conf
+-rw-r--r--   0 sveinbjorn   (501) staff       (20) 18606079 2022-07-11 13:30:00.000000 reynir-correct-3.4.7/src/reynir_correct/config/WrongWords.conf
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    54033 2022-12-20 17:22:32.000000 reynir-correct-3.4.7/src/reynir_correct/errfinder.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)   130639 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/src/reynir_correct/errtokenizer.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)     5682 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/src/reynir_correct/main.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)   121154 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/src/reynir_correct/pattern.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)        0 2020-05-19 01:42:51.000000 reynir-correct-3.4.7/src/reynir_correct/py.typed
+drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2023-06-28 10:51:55.480091 reynir-correct-3.4.7/src/reynir_correct/resources/
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    10664 2022-07-11 13:30:00.000000 reynir-correct-3.4.7/src/reynir_correct/resources/iceloc_prep.json
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    24787 2021-01-18 17:35:45.000000 reynir-correct-3.4.7/src/reynir_correct/resources/nonwords.csv
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    43785 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/src/reynir_correct/settings.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    34965 2022-12-20 17:22:32.000000 reynir-correct-3.4.7/src/reynir_correct/spelling.py
+drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2023-06-28 10:51:55.481571 reynir-correct-3.4.7/src/reynir_correct/tools/
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)     2835 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/src/reynir_correct/tools/diffchecker.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)     1133 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/src/reynir_correct/tools/ritmyndirchecker.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)       22 2023-06-27 19:11:17.000000 reynir-correct-3.4.7/src/reynir_correct/version.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    23521 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/src/reynir_correct/wrappers.py
+drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2023-06-28 10:51:55.436067 reynir-correct-3.4.7/src/reynir_correct.egg-info/
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    20113 2023-06-28 10:51:55.000000 reynir-correct-3.4.7/src/reynir_correct.egg-info/PKG-INFO
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)     1333 2023-06-28 10:51:55.000000 reynir-correct-3.4.7/src/reynir_correct.egg-info/SOURCES.txt
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)        1 2023-06-28 10:51:55.000000 reynir-correct-3.4.7/src/reynir_correct.egg-info/dependency_links.txt
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)       53 2023-06-28 10:51:55.000000 reynir-correct-3.4.7/src/reynir_correct.egg-info/entry_points.txt
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)       99 2023-06-28 10:51:55.000000 reynir-correct-3.4.7/src/reynir_correct.egg-info/requires.txt
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)       15 2023-06-28 10:51:55.000000 reynir-correct-3.4.7/src/reynir_correct.egg-info/top_level.txt
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)        1 2022-08-08 14:35:51.000000 reynir-correct-3.4.7/src/reynir_correct.egg-info/zip-safe
+drwxr-xr-x   0 sveinbjorn   (501) staff       (20)        0 2023-06-28 10:51:55.484840 reynir-correct-3.4.7/test/
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    72921 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/test/test_allkinds.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    14599 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/test/test_annotator.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    16122 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/test/test_patterns.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)     2267 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/test/test_serializers.py
+-rw-r--r--   0 sveinbjorn   (501) staff       (20)    18984 2023-06-27 19:10:33.000000 reynir-correct-3.4.7/test/test_tokenizer.py
```

### Comparing `reynir-correct-3.4.6/LICENSE` & `reynir-correct-3.4.7/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `reynir-correct-3.4.6/PKG-INFO` & `reynir-correct-3.4.7/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,17 +1,16 @@
 Metadata-Version: 2.1
 Name: reynir-correct
-Version: 3.4.6
+Version: 3.4.7
 Summary: A spelling and grammar corrector for Icelandic
 Home-page: https://github.com/mideind/GreynirCorrect
 Author: Miðeind ehf
 Author-email: mideind@mideind.is
 License: MIT
 Keywords: nlp,parser,icelandic,spellchecker
-Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: Science/Research
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: Unix
 Classifier: Operating System :: POSIX
 Classifier: Operating System :: Microsoft :: Windows
@@ -26,15 +25,15 @@
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Programming Language :: Python :: Implementation :: CPython
 Classifier: Programming Language :: Python :: Implementation :: PyPy
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Classifier: Topic :: Utilities
 Classifier: Topic :: Text Processing :: Linguistic
 Provides-Extra: sentence_classifier
-License-File: LICENSE
+License-File: LICENSE.txt
 
 
 .. image:: https://img.shields.io/badge/License-MIT-yellow.svg
     :target: https://opensource.org/licenses/MIT
 .. image:: https://img.shields.io/badge/python-3.7-blue.svg
     :target: https://www.python.org/downloads/release/python-370/
 .. image:: https://img.shields.io/pypi/v/reynir-correct
@@ -202,14 +201,18 @@
 +-----------------------------------+--------------------------------------------------+-----------------+
 | | ``one_sent``                    | The input contains a single sentence only.       | ``False``       |
 |                                   | Sentence splitting should not be attempted.      |                 |
 +-----------------------------------+--------------------------------------------------+-----------------+
 | | ``ignore_rules``                | A set of error codes that should be ignored      | ``set()``       |
 |                                   | in the annotation process.                       |                 |
 +-----------------------------------+--------------------------------------------------+-----------------+
+| | ``tov_config``                  | Path to an additional configuration file that    | ``False``       |
+|                                   | may be provided for correcting custom            |                 |
+|                                   | tone-of-voice issues.                            |                 |
++-----------------------------------+--------------------------------------------------+-----------------+
 
 An overview of error codes is available `here <https://github.com/mideind/GreynirCorrect/blob/master/doc/errorcodes.rst>`__.
 
 *************
 Prerequisites
 *************
 
@@ -467,9 +470,7 @@
 and `here in Icelandic <https://bin.arnastofnun.is/gogn/mimisbrunnur/>`_.
 
 In accordance with the BÍN license terms, credit is hereby given as follows:
 
 *Beygingarlýsing íslensks nútímamáls. Stofnun Árna Magnússonar í íslenskum fræðum.*
 *Höfundur og ritstjóri Kristín Bjarnadóttir.*
 
-
-
```

### Comparing `reynir-correct-3.4.6/README.rst` & `reynir-correct-3.4.7/README.rst`

 * *Files 1% similar despite different names*

```diff
@@ -168,14 +168,18 @@
 +-----------------------------------+--------------------------------------------------+-----------------+
 | | ``one_sent``                    | The input contains a single sentence only.       | ``False``       |
 |                                   | Sentence splitting should not be attempted.      |                 |
 +-----------------------------------+--------------------------------------------------+-----------------+
 | | ``ignore_rules``                | A set of error codes that should be ignored      | ``set()``       |
 |                                   | in the annotation process.                       |                 |
 +-----------------------------------+--------------------------------------------------+-----------------+
+| | ``tov_config``                  | Path to an additional configuration file that    | ``False``       |
+|                                   | may be provided for correcting custom            |                 |
+|                                   | tone-of-voice issues.                            |                 |
++-----------------------------------+--------------------------------------------------+-----------------+
 
 An overview of error codes is available `here <https://github.com/mideind/GreynirCorrect/blob/master/doc/errorcodes.rst>`__.
 
 *************
 Prerequisites
 *************
```

### Comparing `reynir-correct-3.4.6/setup.py` & `reynir-correct-3.4.7/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-#!/usr/bin/env python
+#!/usr/bin/env python3
 """
     Greynir: Natural language processing for Icelandic
 
     Setup.py
 
     Copyright (C) 2022 Miðeind ehf.
     Original author: Vilhjálmur Þorsteinsson
@@ -32,17 +32,14 @@
     This module sets up the GreynirCorrect package and installs the
     'correct' command-line utility.
 
     This package requires Python >= 3.7, and supports PyPy >= 3.7.
 
 """
 
-from __future__ import print_function
-from __future__ import unicode_literals
-
 import io
 import re
 import sys
 
 from glob import glob
 from os.path import basename, dirname, join, splitext
 
@@ -110,15 +107,15 @@
         "Programming Language :: Python :: Implementation :: PyPy",
         "Topic :: Software Development :: Libraries :: Python Modules",
         "Topic :: Utilities",
         "Topic :: Text Processing :: Linguistic",
     ],
     keywords=["nlp", "parser", "icelandic", "spellchecker"],
     setup_requires=[],
-    install_requires=["reynir>=3.5.1", "icegrams>=1.1.0", "typing_extensions"],
+    install_requires=["reynir>=3.5.3", "icegrams>=1.1.2", "typing_extensions"],
     extras_require={
         "sentence_classifier": ["transformers", "datasets", "torch"],
     },
     # Set up a 'correct' command ('correct.exe' on Windows),
     # which calls main() in src/reynir-correct/main.py
     entry_points={
         "console_scripts": [
```

### Comparing `reynir-correct-3.4.6/src/.DS_Store` & `reynir-correct-3.4.7/src/.DS_Store`

 * *Files 18% similar despite different names*

```diff
@@ -29,37 +29,37 @@
 000001c0: 0000 0000 0000 0000 0000 0000 0000 0000  ................
 000001d0: 0000 0000 0000 0000 0000 0000 0000 0000  ................
 000001e0: 0000 0000 0000 0000 0000 0000 0000 0000  ................
 000001f0: 0000 0000 0000 0000 0000 0000 0000 0000  ................
 00000200: 0000 0000 0000 0000 0000 0008 0000 000e  ................
 00000210: 0072 0065 0079 006e 0069 0072 005f 0063  .r.e.y.n.i.r._.c
 00000220: 006f 0072 0072 0065 0063 0074 6c67 3153  .o.r.r.e.c.tlg1S
-00000230: 636f 6d70 0000 0000 0165 d686 0000 000e  comp.....e......
+00000230: 636f 6d70 0000 0000 0166 00b6 0000 000e  comp.....f......
 00000240: 0072 0065 0079 006e 0069 0072 005f 0063  .r.e.y.n.i.r._.c
 00000250: 006f 0072 0072 0065 0063 0074 6d6f 4444  .o.r.r.e.c.tmoDD
-00000260: 626c 6f62 0000 0008 ae73 3984 ab50 c441  blob.....s9..P.A
+00000260: 626c 6f62 0000 0008 bc32 e3c0 30d7 c441  blob.....2..0..A
 00000270: 0000 000e 0072 0065 0079 006e 0069 0072  .....r.e.y.n.i.r
 00000280: 005f 0063 006f 0072 0072 0065 0063 0074  ._.c.o.r.r.e.c.t
-00000290: 6d6f 6444 626c 6f62 0000 0008 ae73 3984  modDblob.....s9.
-000002a0: ab50 c441 0000 000e 0072 0065 0079 006e  .P.A.....r.e.y.n
+00000290: 6d6f 6444 626c 6f62 0000 0008 bc32 e3c0  modDblob.....2..
+000002a0: 30d7 c441 0000 000e 0072 0065 0079 006e  0..A.....r.e.y.n
 000002b0: 0069 0072 005f 0063 006f 0072 0072 0065  .i.r._.c.o.r.r.e
 000002c0: 0063 0074 7068 3153 636f 6d70 0000 0000  .c.tph1Scomp....
-000002d0: 0167 0000 0000 0017 0072 0065 0079 006e  .g.......r.e.y.n
+000002d0: 0167 4000 0000 0017 0072 0065 0079 006e  .g@......r.e.y.n
 000002e0: 0069 0072 005f 0063 006f 0072 0072 0065  .i.r._.c.o.r.r.e
 000002f0: 0063 0074 002e 0065 0067 0067 002d 0069  .c.t...e.g.g.-.i
 00000300: 006e 0066 006f 6c67 3153 636f 6d70 0000  .n.f.olg1Scomp..
-00000310: 0000 0000 5101 0000 0017 0072 0065 0079  ....Q......r.e.y
+00000310: 0000 0000 52bb 0000 0017 0072 0065 0079  ....R......r.e.y
 00000320: 006e 0069 0072 005f 0063 006f 0072 0072  .n.i.r._.c.o.r.r
 00000330: 0065 0063 0074 002e 0065 0067 0067 002d  .e.c.t...e.g.g.-
 00000340: 0069 006e 0066 006f 6d6f 4444 626c 6f62  .i.n.f.omoDDblob
-00000350: 0000 0008 b404 f463 ab50 c441 0000 0017  .......c.P.A....
+00000350: 0000 0008 d025 9cb5 14a9 c441 0000 0017  .....%.....A....
 00000360: 0072 0065 0079 006e 0069 0072 005f 0063  .r.e.y.n.i.r._.c
 00000370: 006f 0072 0072 0065 0063 0074 002e 0065  .o.r.r.e.c.t...e
 00000380: 0067 0067 002d 0069 006e 0066 006f 6d6f  .g.g.-.i.n.f.omo
-00000390: 6444 626c 6f62 0000 0008 b404 f463 ab50  dDblob.......c.P
+00000390: 6444 626c 6f62 0000 0008 d025 9cb5 14a9  dDblob.....%....
 000003a0: c441 0000 0017 0072 0065 0079 006e 0069  .A.....r.e.y.n.i
 000003b0: 0072 005f 0063 006f 0072 0072 0065 0063  .r._.c.o.r.r.e.c
 000003c0: 0074 002e 0065 0067 0067 002d 0069 006e  .t...e.g.g.-.i.n
 000003d0: 0066 006f 7068 3153 636f 6d70 0000 0000  .f.oph1Scomp....
 000003e0: 0000 b000 0000 0000 0000 0000 0000 0000  ................
 000003f0: 0000 0000 0000 0000 0000 0000 0000 0000  ................
 00000400: 0000 0000 0000 0000 0000 0000 0000 0000  ................
```

### Comparing `reynir-correct-3.4.6/src/reynir_correct/__init__.py` & `reynir-correct-3.4.7/src/reynir_correct/__init__.py`

 * *Files 10% similar despite different names*

```diff
@@ -80,9 +80,7 @@
     "check_errors",
     "AnnotatedSentence",
     "Annotation",
     "__version__",
     "__author__",
     "__copyright__",
 )
-
-Settings.read("config/GreynirCorrect.conf")
```

### Comparing `reynir-correct-3.4.6/src/reynir_correct/annotation.py` & `reynir-correct-3.4.7/src/reynir_correct/annotation.py`

 * *Files identical despite different names*

### Comparing `reynir-correct-3.4.6/src/reynir_correct/checker.py` & `reynir-correct-3.4.7/src/reynir_correct/checker.py`

 * *Files 4% similar despite different names*

```diff
@@ -43,31 +43,35 @@
     E001: The sentence could not be parsed
     E002: A nonterminal tagged with 'error' is present in the parse tree
     E003: An impersonal verb occurs with an incorrect subject case
     E004: The sentence is probably not in Icelandic
 
 """
 
+from importlib.abc import Loader
 from typing import (
     Any,
     FrozenSet,
     Mapping,
     cast,
     Iterable,
     Iterator,
     List,
     Tuple,
     Dict,
     Type,
     Optional,
 )
 from typing_extensions import TypedDict
-
+from importlib.machinery import ModuleSpec
+from types import ModuleType
+import importlib.util
+import os
+import sys
 from threading import Lock
-from typing_extensions import TypedDict
 from islenska.basics import Ksnid
 
 from reynir import (
     Greynir,
     correct_spaces,
     TOK,
     Tok,
@@ -81,14 +85,15 @@
 from reynir.bintokenizer import StringIterable
 from reynir.binparser import BIN_Grammar, BIN_Parser, VariantHandler
 from reynir.fastparser import (
     Fast_Parser,
     ffi,  # type: ignore
 )
 from reynir.reducer import Reducer
+from reynir_correct.settings import Settings
 
 from .annotation import Annotation
 from .errtokenizer import CorrectToken, tokenize as tokenize_and_correct
 from .errfinder import ErrorFinder, ErrorDetectionToken
 from .pattern import PatternMatcher
 
 
@@ -115,14 +120,29 @@
     "URE": "úrelt",
     "SJALD": "sjaldgæft",
     "VILLA": "villa",
     "GAM": "gamalt",
 }
 
 
+def load_config(options: Dict[str, Any]):
+    """Load the default configuration file and return a Settings object. Optionally load
+    an additional config if given."""
+    settings = Settings()
+    settings.read(os.path.join("config", "GreynirCorrect.conf"))
+    if options.get("tov_config", False):
+        # check whether the config path is valid:
+        try:
+            settings.read(options["tov_config"], external=True)
+        except FileNotFoundError:
+            print("File not found: " + options["tov_config"])
+            sys.exit(1)
+    return settings
+
+
 def style_warning(k: Ksnid) -> str:
     """Return a style warning for the given Ksnid tuple, if any"""
     if k.malsnid in STYLE_WARNINGS:
         return k.malsnid
     if k.bmalsnid in STYLE_WARNINGS:
         return k.bmalsnid
     return ""
@@ -171,39 +191,39 @@
     @staticmethod
     def wrap_token(t: Tok, ix: int) -> ErrorDetectionToken:
         """Create an instance of a wrapped token"""
         return ErrorDetectionToken(t, ix)
 
 
 class GreynirCorrect(Greynir):
-
     """Parser augmented with the ability to add spelling and grammar
     annotations to the returned sentences"""
 
     # GreynirCorrect has its own class instances of a parser and a reducer,
     # separate from the Greynir class, as they use different settings and
     # parsing enviroments
     _parser: Optional[ErrorDetectingParser] = None
     _reducer = None
     _lock = Lock()
 
-    def __init__(self, **options: Any) -> None:
+    def __init__(self, settings: Settings, **options: Any) -> None:
         self._annotate_unparsed_sentences = options.pop(
             "annotate_unparsed_sentences", True
         )
         self._ignore_rules: FrozenSet[str] = options.get("ignore_rules", set())
         super().__init__(**options)
         self._options = options
+        self.settings = settings
         # if options:
         #    raise ValueError(f"Unknown option(s) for GreynirCorrect: {options}")
 
     def tokenize(self, text: StringIterable) -> Iterator[Tok]:
         """Use the correcting tokenizer instead of the normal one"""
         # The CorrectToken class is a duck-typing implementation of Tok
-        return tokenize_and_correct(text, **self._options)
+        return tokenize_and_correct(text, settings=self.settings, **self._options)
 
     @classmethod
     def _dump_token(cls, tok: Tok) -> Tuple[Any, ...]:
         """Override token dumping function from Greynir,
         providing a JSON-dumpable object"""
         assert isinstance(tok, CorrectToken)
         return CorrectToken.dump(tok)
@@ -361,17 +381,31 @@
                     )
                 )
         else:
             # Successfully parsed:
             # Add annotations for error-marked nonterminals from the grammar
             # found in the parse tree
             ErrorFinder(ann, sent).run()
+            pm = PatternMatcher(ann, sent)
+            # Check whether external tone of voice patterns are given
+            if self.settings.tone_of_voice_patterns.PATH:
+                file_path = self.settings.tone_of_voice_patterns.PATH
+                module_name = os.path.splitext(os.path.basename(file_path))[0]
+                # Import the module
+                spec: Optional[ModuleSpec] = importlib.util.spec_from_file_location(module_name, file_path)
+                if spec is None:
+                    raise FileNotFoundError(f"Could not find a spec for module '{module_name}' at '{file_path}'")
+                assert isinstance(spec.loader, Loader)
+                module: ModuleType = importlib.util.module_from_spec(spec)
+                spec.loader.exec_module(module)
+                # Add the external patterns to the pattern matcher
+                module.add_extra_patterns(pm)  # type: ignore # Mypy doesn't know about add_extra_patterns()
             # Run the pattern matcher on the sentence,
             # annotating questionable patterns
-            PatternMatcher(ann, sent).run()
+            pm.run()
         # Sort the annotations by their start token index,
         # and then by decreasing span length
         ann.sort(key=lambda a: (a.start, -a.end))
         # Eliminate duplicates, i.e. identical annotation
         # codes for identical spans
         i = 1
         while i < len(ann):
@@ -391,61 +425,78 @@
         before returning it to the client"""
         sent = AnnotatedSentence(job, s)
         # Add spelling and grammar annotations to the sentence
         sent.annotations = self.annotate(sent)
         return sent
 
 
-def check_single(sentence_text: str, **options: Any) -> Optional[Sentence]:
+def create_rc_instance(rc: Optional[GreynirCorrect], **options: Any) -> GreynirCorrect:
+    """Create a global GreynirCorrect instance if it doesn't exist already.
+    If the rc argument is not None, it is returned as is."""
+    if rc is None:
+        rc = GreynirCorrect(load_config(options), **options)
+    return rc
+
+
+def check_single(
+    sentence_text: str, rc: Optional[GreynirCorrect] = None, **options: Any
+) -> Optional[Sentence]:
     """Check and annotate a single sentence, given in plain text"""
     # Returns None if no sentence was parsed
+    rc = create_rc_instance(rc, **options)
     max_sent_tokens = options.pop("max_sent_tokens", DEFAULT_MAX_SENT_TOKENS)
-    rc = GreynirCorrect(**options)
     return rc.parse_single(sentence_text, max_sent_tokens=max_sent_tokens)
 
 
-def check_tokens(tokens: Iterable[CorrectToken], **options: Any) -> Optional[Sentence]:
+def check_tokens(
+    tokens: Iterable[CorrectToken], rc: Optional[GreynirCorrect] = None, **options: Any
+) -> Optional[Sentence]:
     """Check and annotate a single sentence, given as a token list"""
     # Returns None if no sentence was parsed
+    rc = create_rc_instance(rc, **options)
     max_sent_tokens = options.pop("max_sent_tokens", DEFAULT_MAX_SENT_TOKENS)
-    rc = GreynirCorrect(**options)
     return rc.parse_tokens(tokens, max_sent_tokens=max_sent_tokens)
 
 
-def check(text: str, **options: Any) -> Iterable[Paragraph]:
+def check(
+    text: str, rc: Optional[GreynirCorrect] = None, **options: Any
+) -> Iterable[Paragraph]:
     """Return a generator of checked paragraphs of text,
     each being a generator of checked sentences with
     annotations"""
     split_paragraphs = options.pop("split_paragraphs", False)
     max_sent_tokens = options.pop("max_sent_tokens", DEFAULT_MAX_SENT_TOKENS)
-    rc = GreynirCorrect(**options)
+    rc = create_rc_instance(rc, **options)
     # This is an asynchronous (on-demand) parse job
     job = rc.submit(
         text,
         parse=True,
         split_paragraphs=split_paragraphs,
         max_sent_tokens=max_sent_tokens,
     )
     yield from job.paragraphs()
 
 
 def check_with_custom_parser(
     text: str,
     *,
+    settings: Settings,
     parser_class: Type[GreynirCorrect] = GreynirCorrect,
     progress_func: ProgressFunc = None,
     split_paragraphs: bool = False,
     annotate_unparsed_sentences: bool = True,
-    **options: Any,
+    **options: Dict[str, Any],
 ) -> CheckResult:
     """Return a dict containing parsed paragraphs as well as statistics,
     using the given correction/parser class. This is a low-level
     function; normally check_with_stats() should be used."""
     rc = parser_class(
-        annotate_unparsed_sentences=annotate_unparsed_sentences, **options
+        annotate_unparsed_sentences=annotate_unparsed_sentences,
+        settings=settings,
+        **options,
     )
     job = rc.submit(
         text,
         parse=True,
         split_paragraphs=split_paragraphs,
         progress_func=progress_func,
     )
@@ -460,21 +511,23 @@
         ambiguity=job.ambiguity,
         parse_time=job.parse_time,
     )
 
 
 def check_with_stats(
     text: str,
+    settings: Settings,
     *,
     split_paragraphs: bool = False,
     progress_func: ProgressFunc = None,
     annotate_unparsed_sentences: bool = True,
     **options: Any,
 ) -> CheckResult:
     """Return a dict containing parsed paragraphs as well as statistics"""
     return check_with_custom_parser(
         text,
+        settings=settings,
         split_paragraphs=split_paragraphs,
         progress_func=progress_func,
         annotate_unparsed_sentences=annotate_unparsed_sentences,
         **options,
     )
```

### Comparing `reynir-correct-3.4.6/src/reynir_correct/classifier.py` & `reynir-correct-3.4.7/src/reynir_correct/classifier.py`

 * *Files 3% similar despite different names*

```diff
@@ -42,15 +42,14 @@
 
 """
 
 from typing import List, Union, overload
 
 
 try:
-    from datasets import load_dataset
     from transformers import pipeline  # type: ignore
 except:
     import warnings
 
     warningtext = (
         "Tried to import the classifier module without the required packages installed.\n"
         "The required packages are in the 'sentence_classifier' extra\n"
@@ -79,15 +78,15 @@
 
     @overload
     def classify(self, text: List[str]) -> List[bool]:
         ...
 
     def classify(self, text: Union[str, List[str]]) -> Union[List[bool], bool]:
         """Classify a sentence or sentences.
-        For each sentence, return true iff the sentence probably contains an error."""
+        For each sentence, return true if the sentence probably contains an error."""
         if isinstance(text, str):
             text = [text]
 
         pipe_result = self.pipe([self._domain_prefix + t for t in text])
         result: List[bool] = [
             r["generated_text"] == self._true_label for r in pipe_result
         ]
```

### Comparing `reynir-correct-3.4.6/src/reynir_correct/config/GreynirCorrect.conf` & `reynir-correct-3.4.7/src/reynir_correct/config/GreynirCorrect.conf`

 * *Files 0% similar despite different names*

```diff
@@ -2731,33 +2731,38 @@
 
 
 [allowed_multiples]
 
 # Set of word forms that are allowed to appear consecutively in text
 
 á
+átta
 að
 af
-átta
 auður
 bæði
 bannið
 bara
 efni
 eftir
 eigi
 eigum
+einn
 eins
+eitt
 er
 fá
 falla
 fallið
 ferð
 festi
+fimm
 finnur
+fjórir
+fjögur
 flæði
 flokkar
 formið
 frá
 fram
 framan
 fylgi
@@ -2810,14 +2815,16 @@
 móti
 mun
 myndir
 næst
 neðan
 niðri
 niður
+níu
+núll
 ó
 ofan
 ómar
 opnir
 orðin
 ráðum
 rennur
@@ -2825,31 +2832,35 @@
 reynir
 riðlar
 riðli
 sæti
 safnið
 sé
 sem
+sex
 sér
 sett
 síðan
+sjö
 skipið
 skráðir
 sótt
 spenna
 standa
 stofna
 streymi
 strokið
 stundum
 svala
 sýna
 talið
 til
 tíma
+tveir
+tvö
 um
 undan
 undir
 upp
 úr
 út
 úti
@@ -2870,14 +2881,16 @@
 vernda
 við
 vikum
 yfir
 yrði
 þegar
 þjóna
+þrír
+þrjú
 
 
 [wrong_compounds]
 
 # Words that should not be written as compounds
 
 "afhverju", "af hverju"
@@ -4664,15 +4677,15 @@
 fyrir okkar leiti               $error(IY, fyrir okkar leyti)
 að sjálfsdáðum              	$error(AÐAF, af sjálfsdáðum)
 að ásettu ráði              	$error(AÐAF, af ásettu ráði)
 að öllu afli                	$error(AÐAF, af öllu afli)
 að því tilefni              	$error(AÐAF, af því tilefni)
 að því tilskyldu            	$error(YI, að því tilskildu)
 beggja megin                	$error(WRONG_WORD, báðum megin) # eða beggja vegna
-björn í híði					$error(IIYY, björn í hýði)
+björn í hýði					$error(IIYY, björn í híði)
 blöðum um það að flétta         $error(WRONG_WORD, blöðum um það að fletta)
 burtséð frá                 	$error(WRONG_PHRASE, að undanskildu)  # eða án tillits til
 bæn sýna uppfyllta				$error(YYII, bæn sína uppfyllta)
 drauma sýna rætast				$error(YYII, drauma sína rætast)
 eiga þakkir skilið          	$error(WRONG_FORM, eiga þakkir skildar) # (mælt með)
 á þakkir skilið          	    $error(WRONG_FORM, á þakkir skildar) # (mælt með)
 átti þakkir skilið        	    $error(WRONG_FORM, átti þakkir skildar) # (mælt með)
@@ -4836,10 +4849,45 @@
 þessi aðilar                    $error(WRONG_FORM, þessir aðilar)
 þíðir ekkert að					$error(IIYY, þýðir ekkert að)
 þýða í ísinn					$error(IIYY, þíða í ísinn)
 þessar stundirnar               $error(WRONG_NUMBER, þessa stundina)
 að sjálfu sér 					$error(AÐAF, af sjálfu sér)
 þar að leiðandi					$error(AÐAF, þar af leiðandi)
 
+
 # Include WrongWords.conf file
+$include WrongWords.conf
 
-$include WrongWords.conf
+# Tradition says these word parts should rather be used
+# Using the results in a context-dependent error
+# Attn.: Make sure these errors are available as a prefix
+[wrong_formers]
+"akstur", "aksturs"
+"athugana", "athugunar"
+"ferminga", "fermingar"
+"fjárfestinga", "fjárfestingar"
+"forvarna", "forvarnar"
+"heyrna", "heyrnar"
+"kvartana", "kvörtunar"
+"loftlags", "loftslags"
+"næringa", "næringar"
+"pantana", "pöntunar"
+"ráðninga", "ráðningar"
+"skráninga", "skráningar"
+"Vestfjarðar", "Vestfjarða"
+"ábendinga", "ábendingar"
+
+# Using these word parts results in a context-independent error
+# Attn.: Make sure these errors are available in prefix.txt in BinPackage
+[wrong_formers_ci]
+"Atlandshafs", "Atlantshafs"
+"akríl", "akrýl"
+"dísel", "dísil"
+"eyrnar", "eyrna"
+"feykna", "feikna"
+"fjarskiptar", "fjarskipta"
+"fyrna", "firna"
+"griðar", "griða"  # griðarstaður
+"hönnuna", "hönnunar"
+"kvenn", "kven"
+"Lundúnar", "Lundúna"
+"öldungar", "öldunga"
```

### Comparing `reynir-correct-3.4.6/src/reynir_correct/config/IEC_nonwords.tsv` & `reynir-correct-3.4.7/src/reynir_correct/config/IEC_nonwords.tsv`

 * *Files identical despite different names*

### Comparing `reynir-correct-3.4.6/src/reynir_correct/config/IceSQuErVersion01.tsv` & `reynir-correct-3.4.7/src/reynir_correct/config/IceSQuErVersion01.tsv`

 * *Files identical despite different names*

### Comparing `reynir-correct-3.4.6/src/reynir_correct/config/Storasnid_ritm.csv` & `reynir-correct-3.4.7/src/reynir_correct/config/Storasnid_ritm.csv`

 * *Files identical despite different names*

### Comparing `reynir-correct-3.4.6/src/reynir_correct/config/TabooWords.conf` & `reynir-correct-3.4.7/src/reynir_correct/config/TabooWords.conf`

 * *Files identical despite different names*

### Comparing `reynir-correct-3.4.6/src/reynir_correct/config/WrongWords.conf` & `reynir-correct-3.4.7/src/reynir_correct/config/WrongWords.conf`

 * *Files identical despite different names*

### Comparing `reynir-correct-3.4.6/src/reynir_correct/errfinder.py` & `reynir-correct-3.4.7/src/reynir_correct/errfinder.py`

 * *Files identical despite different names*

### Comparing `reynir-correct-3.4.6/src/reynir_correct/errtokenizer.py` & `reynir-correct-3.4.7/src/reynir_correct/errtokenizer.py`

 * *Files 3% similar despite different names*

```diff
@@ -74,30 +74,15 @@
     load_token,
     StringIterable,
     TokenIterator,
 )
 from reynir.bindb import GreynirBin
 from reynir.binparser import BIN_Token, VariantHandler
 from islenska.basics import Ksnid
-
-from .settings import (
-    AllowedMultiples,
-    WrongCompounds,
-    SplitCompounds,
-    UniqueErrors,
-    MultiwordErrors,
-    CapitalizationErrors,
-    TabooWords,
-    CIDErrorForms,
-    Morphemes,
-    Ritmyndir,
-    RitmyndirDetails,
-    IecNonwords,
-    Settings,
-)
+from .settings import Settings
 from .spelling import Corrector
 
 
 # Token constructor classes
 TokenCtor = Type["Correct_TOK"]
 
 # Words that contain any letter from the following set are assumed
@@ -767,14 +752,54 @@
         d["detail"] = self.detail
         d["suggest"] = self.suggest
         d["suggestlist"] = self._suggestlist
         return d
 
 
 @register_error_class
+class ToneOfVoiceWarning(Error):
+
+    """A ToneOfVoiceWarning marks a word that is not conforming to a particular tone of voice."""
+
+    # 001: Tone of voice word usage warning, with suggested replacement.
+
+    def __init__(
+        self,
+        code: str,
+        txt: str,
+        detail: Optional[str],
+        original: str,
+        suggest: Optional[str],
+        suggestlist: Optional[List[str]] = None,
+    ) -> None:
+        # Tone of voice word warnings start with "V"
+        super().__init__(
+            "V" + code, is_warning=True, original=original, suggest=suggest
+        )
+        self._txt = txt
+        self._detail = detail
+        self._suggestlist = suggestlist
+
+    @property
+    def description(self) -> str:
+        return self._txt
+
+    @property
+    def detail(self) -> Optional[str]:
+        return self._detail
+
+    def to_dict(self) -> Dict[str, Any]:
+        d = super().to_dict()
+        d["detail"] = self.detail
+        d["suggest"] = self.suggest
+        d["suggestlist"] = self._suggestlist
+        return d
+
+
+@register_error_class
 class StyleWarning(Error):
 
     """A StyleWarning marks a word that is annotated with a
     style comment in BÍN (malsnid/bmalsnid properties in Ksnid)."""
 
     # Y001/w: Style warning for word.
 
@@ -996,14 +1021,15 @@
 
 
 def parse_errors(
     token_stream: Iterator[Tok],
     db: GreynirBin,
     only_ci: bool,
     ignore_rules: FrozenSet[str],
+    settings: Settings,
 ) -> Iterator[CorrectToken]:
 
     """This tokenization phase is done before BÍN annotation
     and before static phrases are identified. It finds duplicated words,
     and words that have been incorrectly split or should be split."""
 
     def get() -> CorrectToken:
@@ -1041,15 +1067,14 @@
     #     # If any meaning of the following word has a stem (lemma)
     #     # that fits the second part of the split compound, we
     #     # have a match
     #     return any(m.stofn.replace("-", "") in next_stems for m in meanings)
 
     token: CorrectToken = cast(CorrectToken, None)
     at_sentence_start = False
-
     try:
 
         # Maintain a one-token lookahead
         token = get()
 
         while True:
             next_token = get()
@@ -1149,15 +1174,15 @@
             if (
                 not only_ci
                 and token.txt
                 and next_token.txt
                 and token.txt == next_token.txt
                 and token.kind == TOK.WORD
             ):
-                if token.txt.lower() in AllowedMultiples.SET:
+                if token.txt.lower() in settings.allowed_multiples.SET:
                     if "C004/w" not in ignore_rules:
                         next_token.set_error(
                             CompoundError(
                                 "004/w",
                                 "'{0}' er að öllum líkindum ofaukið".format(
                                     next_token.txt
                                 ),
@@ -1235,16 +1260,16 @@
                     token = CorrectToken.word("-" + second, original="")
                 yield token
                 token = next_token
                 at_sentence_start = False
                 continue
 
             # Splitting wrongly compounded words
-            if token.txt and token.txt.lower() in WrongCompounds.DICT:
-                correct_phrase = list(WrongCompounds.DICT[token.txt.lower()])
+            if token.txt and token.txt.lower() in settings.wrong_compounds.DICT:
+                correct_phrase = list(settings.wrong_compounds.DICT[token.txt.lower()])
                 # Make the split phrase emulate the case of
                 # the original token
                 if token.txt.isupper():
                     # All upper case
                     for ix, p in enumerate(correct_phrase):
                         correct_phrase[ix] = p.upper()
                 else:
@@ -1275,25 +1300,25 @@
                         yield token
                 token = next_token
                 at_sentence_start = False
                 continue
 
             # Unite wrongly split compounds, or at least suggest uniting them
             if token.txt and (
-                token.txt.lower() in SplitCompounds.DICT
-                or token.txt.lower() in Morphemes.BOUND_DICT
+                token.txt.lower() in settings.split_compounds.DICT
+                or token.txt.lower() in settings.morphemes.BOUND_DICT
             ):
                 if only_ci:
-                    if token.txt.lower() in SplitCompounds.DICT:
+                    if token.txt.lower() in settings.split_compounds.DICT:
                         # Don't want to correct
                         yield token
                         token = next_token
                         at_sentence_start = False
                         continue
-                    if token.txt.lower() in Morphemes.BOUND_DICT:
+                    if token.txt.lower() in settings.morphemes.BOUND_DICT:
                         # Only want to mark as an error, can't fix in CI-mode.
                         if "S007" not in ignore_rules:
                             token.set_error(
                                 SpellingError(
                                     "007",
                                     "Orðhlutinn '{0}' á ekki að standa stakur".format(
                                         token.txt
@@ -1321,15 +1346,15 @@
                     at_sentence_start = False
                     continue
                 if token.txt.isupper() and not next_token.txt.isupper():
                     # ...and vice versa
                     yield token
                     token = next_token
                     continue
-                next_stems = SplitCompounds.DICT.get(token.txt.lower())
+                next_stems = settings.split_compounds.DICT.get(token.txt.lower())
                 if not next_stems:
                     yield token
                     token = next_token
                     at_sentence_start = False
                     continue
                 _, meanings = db.lookup_g(
                     next_token.txt.lower(), at_sentence_start=False
@@ -1361,15 +1386,15 @@
                         token = get()
                     else:
                         yield token
                         yield next_token
                         token = get()
                     at_sentence_start = False
                     continue
-                next_pos = Morphemes.BOUND_DICT.get(token.txt.lower())
+                next_pos = settings.morphemes.BOUND_DICT.get(token.txt.lower())
                 if not next_pos:
                     yield token
                     token = next_token
                     at_sentence_start = False
                     continue
                 poses = set(m.ordfl for m in meanings if m.ordfl in next_pos)
                 notposes = set(m.ordfl for m in meanings if m.ordfl not in next_pos)
@@ -1508,33 +1533,38 @@
 class MultiwordErrorStream(MatchingStream):
 
     """Class that filters a token stream looking for multi-word
     matches with the MultiwordErrors phrase dictionary,
     and inserting replacement phrases when matches are found"""
 
     def __init__(
-        self, db: GreynirBin, token_ctor: TokenCtor, ignore_rules: FrozenSet[str]
+        self,
+        db: GreynirBin,
+        token_ctor: TokenCtor,
+        ignore_rules: FrozenSet[str],
+        settings,
     ) -> None:
-        super().__init__(MultiwordErrors.DICT)
+        super().__init__(settings.multiword_errors.DICT)
         self._token_ctor = token_ctor
         self._db = db
         self._ignore_rules = ignore_rules
+        self.multiword_errors = settings.multiword_errors
 
     def length(self, ix: int) -> int:
         """Return the length (word count) of the original phrase
         that is being replaced"""
-        return MultiwordErrors.get_phrase_length(ix)
+        return self.multiword_errors.get_phrase_length(ix)
 
     def match(self, tq: List[Tok], ix: int) -> Iterable[Tok]:
         """This is a complete match of an error phrase;
         yield the replacement phrase"""
-        if "P_" + MultiwordErrors.get_code(ix) in self._ignore_rules:
+        if "P_" + self.multiword_errors.get_code(ix) in self._ignore_rules:
             yield from tq
             return
-        replacement = MultiwordErrors.get_replacement(ix)
+        replacement = self.multiword_errors.get_replacement(ix)
         db = self._db
         token_ctor = self._token_ctor
         len_tq = len(tq)
         len_replacement = len(replacement)
         capfirst = False
         for i, replacement_word in enumerate(replacement):
             # !!! TODO: at_sentence_start
@@ -1558,15 +1588,15 @@
             repstring = " ".join(replacement)
             if capfirst:
                 repstring = repstring.capitalize()
                 capfirst = False
             if i == 0:
                 ct.set_error(
                     PhraseError(
-                        MultiwordErrors.get_code(ix),
+                        self.multiword_errors.get_code(ix),
                         "Orðasambandið '{0}' var leiðrétt í '{1}'".format(
                             " ".join(t.txt for t in tq), repstring
                         ),
                         span=len(replacement),
                         original=" ".join(t.txt for t in tq),
                         suggest=repstring,
                     )
@@ -1580,82 +1610,48 @@
 
 
 def handle_multiword_errors(
     token_stream: Iterator[CorrectToken],
     db: GreynirBin,
     token_ctor: TokenCtor,
     ignore_rules: FrozenSet[str],
+    settings: Settings,
 ) -> Iterator[CorrectToken]:
 
     """Parse a stream of tokens looking for multiword phrases
     containing errors.
     The algorithm implements N-token lookahead where N is the
     length of the longest phrase.
     """
-
-    mwes = MultiwordErrorStream(db, token_ctor, ignore_rules)
+    mwes = MultiwordErrorStream(db, token_ctor, ignore_rules, settings)
     tok_stream = cast(Iterator[Tok], token_stream)
     yield from cast(Iterator[CorrectToken], mwes.process(tok_stream))
 
 
 # Compound word stuff
 
 # Illegal prefixes that will be split off from the rest of the word
 # Attn.: Make sure these errors are available as a prefix
 NOT_FORMERS = frozenset(("allra", "alhliða", "fjölnota", "margnota", "ótal"))
 
-# Tradition says these word parts should rather be used
-# Using them results in a context-dependent error
-# Attn.: Make sure these errors are available as a prefix
-WRONG_FORMERS: Mapping[str, str] = {
-    "akstur": "aksturs",
-    "athugana": "athugunar",
-    "ferminga": "fermingar",
-    "fjárfestinga": "fjárfestingar",
-    "forvarna": "forvarnar",
-    "heyrna": "heyrnar",
-    "kvartana": "kvörtunar",
-    "loftlags": "loftslags",
-    "næringa": "næringar",
-    "pantana": "pöntunar",
-    "ráðninga": "ráðningar",
-    "skráninga": "skráningar",
-    "Vestfjarðar": "Vestfjarða",
-    "ábendinga": "ábendingar",
-}
-
-# Using these word parts results in a context-independent error
-# Attn.: Make sure these errors are available in prefix.txt in BinPackage
-WRONG_FORMERS_CI: Mapping[str, str] = {
-    "Atlandshafs": "Atlantshafs",
-    "akríl": "akrýl",
-    "dísel": "dísil",
-    "eyrnar": "eyrna",
-    "feykna": "feikna",
-    "fjarskiptar": "fjarskipta",
-    "fyrna": "firna",
-    "griðar": "griða",  # griðarstaður
-    "kvenn": "kven",
-    "Lundúnar": "Lundúna",
-    "öldungar": "öldunga",
-}
-
 
 def fix_compound_words(
     token_stream: Iterable[CorrectToken],
     db: GreynirBin,
     token_ctor: TokenCtor,
     only_ci: bool,
     ignore_rules: FrozenSet[str],
+    settings: Settings,
 ) -> Iterator[CorrectToken]:
 
     """Fix incorrectly compounded words"""
 
     at_sentence_start = False
-
+    WRONG_FORMERS = settings.wrong_formers.DICT
+    WRONG_FORMERS_CI = settings.wrong_formers_cid.DICT
     for token in token_stream:
         if token.kind == TOK.S_BEGIN:
             yield token
             at_sentence_start = True
             continue
         if token.txt and token.txt.endswith("-og") and len(token.txt) > 3:
             # TODO Token has been split at this point (fjármála - og)
@@ -1690,15 +1686,14 @@
             or not token.has_meanings
             or "-" not in token.meanings[0].stofn
         ):
             # Not a compound word
             yield token
             at_sentence_start = False
             continue
-
         # Compound word
         cw: List[str] = token.meanings[0].stofn.split("-")
         # Special case for the prefix "ótal" which the compounder
         # splits into ó-tal
         if len(cw) >= 3 and cw[0] == "ó" and cw[1] == "tal":
             cw = ["ótal"] + cw[2:]
 
@@ -1722,20 +1717,20 @@
                 )
                 yield t1
                 at_sentence_start = False
                 _, m = db.lookup_g(suffix, at_sentence_start)
                 token = token_ctor.Word(suffix, m, token=token)
                 token.original = ""
 
-        elif cw0 in Morphemes.FREE_DICT:
+        elif cw0 in settings.morphemes.FREE_DICT:
             # Check which PoS, attachment depends on that
             at_sentence_start = False
             suffix = token.txt[len(cw0) :]
             prefix = emulate_case(cw0, template=token.txt)
-            freepos = Morphemes.FREE_DICT.get(cw0)
+            freepos = settings.morphemes.FREE_DICT.get(cw0)
             assert freepos is not None
             _, meanings2 = db.lookup_g(suffix, at_sentence_start)
             poses = set(m.ordfl for m in meanings2 if m.ordfl in freepos)
             if not poses:
                 yield token
                 continue
             notposes = set(m.ordfl for m in meanings2 if m.ordfl not in freepos)
@@ -1772,15 +1767,14 @@
                                 token.txt, tp
                             ),
                             original=token.txt,
                             suggest="{} {}".format(prefix, suffix),
                             span=2,
                         )
                     )
-
         elif cw0 in WRONG_FORMERS_CI:
             if "C006" not in ignore_rules:
                 correct_former = WRONG_FORMERS_CI[cw0]
                 corrected = correct_former + token.txt[len(cw0) :]
                 corrected = emulate_case(corrected, template=token.txt)
                 _, m = db.lookup_g(corrected, at_sentence_start)
                 t1 = token_ctor.Word(corrected, m, token=token)
@@ -1826,14 +1820,15 @@
     corrector: Corrector,
     only_ci: bool,
     ignore_rules: FrozenSet[str],
     apply_suggestions: bool,
     suppress_suggestions: bool,
     generate_suggestion_list: bool,
     suggest_not_correct: bool,
+    settings: Settings,
 ) -> Iterator[CorrectToken]:
 
     """Try to identify unknown words in the token stream, for instance
     as spelling errors (character juxtaposition, deletion, insertion...)"""
     at_sentence_start = False
     context: Tuple[str, ...] = tuple()
     db = corrector.db
@@ -1918,21 +1913,21 @@
         token.add_corrected_meanings(m)
         return token
 
     def add_ritmyndir_error(token: CorrectToken) -> CorrectToken:
         """Add an error with corresponding correct value and details given info in Ritmyndir"""
         # TODO At the moment the code assumes only one correct value is available in data
         lemma = token.txt
-        code = Ritmyndir.get_code(token.txt)
+        code = settings.ritmyndir.get_code(token.txt)
         if code in NEUTRAL_RITMYNDIR_CODES:
             # Not an error
             return token
         if code in ignore_rules:
             return token
-        corrected = Ritmyndir.get_correct_form(token.txt)
+        corrected = settings.ritmyndir.get_correct_form(token.txt)
         if (
             # Needed due to difference in title case for Icelandic and English in MWE
             token.txt[0].istitle()
             and not token.txt.isupper()
             and not token.cap_sentence_start
             and not corrected.istitle()
         ):
@@ -1963,15 +1958,15 @@
     def get_details(
         code: str, txt: str, correct: str, lemma: str
     ) -> Tuple[str, str, List[str]]:
         """Return short and detailed descriptions for the error category plus a link to grammar references where possible"""
         # text is the short version, about the category and the error.
         # details is the long version with references.
         try:
-            standref, cat, det = RitmyndirDetails.DICT[code]
+            standref, cat, det = settings.ritmyndir_details.DICT[code]
         except KeyError:
             return ("", "", [""])
         references: List[str] = []
         text = "{}: '{}' -> '{}'".format(cat, txt, correct)
         details = det
         details = details.format(original=txt, correct=correct, lemma=lemma)
         # Adding references to Ritreglur
@@ -2109,30 +2104,30 @@
             at_sentence_start = False
             continue
 
         # The token is a word
 
         # Wrong word forms in Ritmyndir, more information than
         # in UniqueErrors
-        if Ritmyndir.contains(token.txt):
+        if settings.ritmyndir.contains(token.txt):
             rtok = add_ritmyndir_error(token)
             at_sentence_start = False
             # Update the context with the replaced token
             context = (prev_context + tuple(rtok.txt.split()))[-3:]
             yield rtok
             continue
 
         # Check unique errors - some of those may have
         # BÍN annotations via the compounder
         # Examples: 'kvenær' -> 'hvenær', 'starfssemi' -> 'starfsemi'
         # !!! TODO: Handle upper/lowercase
-        if token.txt in UniqueErrors.DICT:
+        if token.txt in settings.unique_errors.DICT:
             # Note: corrected is a tuple
             rtok = token
-            corrected = UniqueErrors.DICT[token.txt]
+            corrected = settings.unique_errors.DICT[token.txt]
             assert isinstance(corrected, tuple)
             corrected_display = " ".join(corrected)
             if "S001" not in ignore_rules:
                 for ix, corrected_word in enumerate(corrected):
                     if ix == 0:
                         rtok = replace_word(1, token, corrected_word, corrected_display)
                         at_sentence_start = False
@@ -2142,17 +2137,17 @@
                         rtok = replace_word(1, token, corrected_word, None)
                     yield rtok
                     context = (prev_context + tuple(rtok.txt.split()))[-3:]
                     prev_context = context
             continue
 
         # Similarly, check Icelandic Error Corpus Nonwords
-        if token.txt in IecNonwords.DICT:
+        if token.txt in settings.iec_nonwords.DICT:
             # Note: corrected is a tuple
-            corrected = IecNonwords.DICT[token.txt]
+            corrected = settings.iec_nonwords.DICT[token.txt]
             assert isinstance(corrected, tuple)
             corrected_display = " ".join(corrected)
             if "S001" not in ignore_rules:
                 for ix, corrected_word in enumerate(corrected):
                     rtok = token
                     if ix == 0:
                         rtok = replace_word(1, token, corrected_word, corrected_display)
@@ -2198,17 +2193,17 @@
                 continue
 
         # Check wrong word forms, i.e. those that do not exist in BÍN
         # !!! TODO: Some error forms are present in BÍN but in a different
         # !!! TODO: case (for instance, 'á' as a nominative of 'ær').
         # !!! TODO: We are not handling those here.
         # !!! TODO: Handle upper/lowercase
-        if not token.val and CIDErrorForms.contains(token.txt):
+        if not token.val and settings.cid_error_forms.contains(token.txt):
             rtok = token
-            corr_txt = CIDErrorForms.get_correct_form(token.txt)
+            corr_txt = settings.cid_error_forms.get_correct_form(token.txt)
             if "S002" not in ignore_rules:
                 rtok = replace_word(2, token, corr_txt, corr_txt)
             at_sentence_start = False
             # Update the context with the replaced token
             context = (prev_context + tuple(rtok.txt.split()))[-3:]
             yield rtok
             continue
@@ -2350,20 +2345,20 @@
 
 def fix_capitalization(
     token_stream: Iterable[CorrectToken],
     db: GreynirBin,
     token_ctor: TokenCtor,
     only_ci: bool,
     ignore_rules: FrozenSet[str],
+    settings: Settings,
 ) -> Iterator[CorrectToken]:
 
     """Annotate tokens with errors if they are capitalized incorrectly"""
-
-    stems = CapitalizationErrors.SET_REV
-    wrong_stems = CapitalizationErrors.SET
+    stems = settings.capitalization_errors.SET_REV
+    wrong_stems = settings.capitalization_errors.SET
 
     # This variable must be defined before is_wrong() because
     # the function closes over it
     # The states are ("sentence_start", "after_ordinal", "in_sentence")
     state = "sentence_start"
 
     def is_wrong(token: CorrectToken) -> bool:
@@ -2579,14 +2574,15 @@
 def late_fix_capitalization(
     token_stream: Iterable[CorrectToken],
     db: GreynirBin,
     token_ctor: TokenCtor,
     only_ci: bool,
     ignore_rules: FrozenSet[str],
     suppress_suggestions: bool,
+    settings: Settings,
 ) -> Iterator[CorrectToken]:
 
     """Annotate final, coalesced tokens with errors
     if they are capitalized incorrectly"""
 
     def number_error(
         token: CorrectToken, replace: str, code: str, instruction_txt: str
@@ -2606,16 +2602,15 @@
                 original=original_txt,
                 suggest=replace,
             )
         )
         return ct
 
     at_sentence_start = False
-    stems = CapitalizationErrors.SET
-
+    stems = settings.capitalization_errors.SET
     for token in token_stream:
         if token.kind == TOK.S_BEGIN:
             yield token
             at_sentence_start = True
             continue
         if (
             isinstance(token, CorrectToken)  # type: ignore
@@ -2821,89 +2816,132 @@
         # Remove all annotations and revert corrections for tokens in whitelist/wordlist
         # NOTE: Only checks for the case present in the whitelist
         if token.original and token.original.strip() in ignore_wordlist:
             token.remove_error(token.original.strip())
         yield token
 
 
-def check_taboo_words(token_stream: Iterable[CorrectToken]) -> Iterator[CorrectToken]:
-    """Annotate taboo words with warnings"""
+def create_template_dict(
+    settings, explanation: str, explanation_w_sugg: str, error_warning, words
+):
+    template_dict = {}
+    template_dict["explanation"] = explanation
+    template_dict["explanation_w_sugg"] = explanation_w_sugg
+    template_dict["error_warning"] = error_warning
+    template_dict["words"] = words
+    return template_dict
 
-    tdict = TabooWords.DICT
 
-    for token in token_stream:
-        # Check taboo words
-        if (  # type: ignore
-            token.val is not None and token.has_meanings and token.txt not in NOT_TABOO
-        ):
-            # We skip checks for tokens already containing an error, as the taboo word
-            # might be the system's invention.
-            # !!! TODO: This could be made more efficient if all
-            # !!! TODO: taboo word forms could be generated ahead of time
-            # !!! TODO: and checked via a set lookup
-            for m in token.meanings:
-                key = m.stofn.replace("-", "")
-                # First, look up the lemma + _ + word category
-                t = tdict.get(key + "_" + m.ordfl)
-                if t is None:
-                    # Then, look up the lemma only
-                    t = tdict.get(key)
-                if t is not None:
-                    # Taboo word
-                    replacement, detail = t
-                    # There can be multiple suggested replacements,
-                    # for instance 'þungunarrof_hk/meðgöngurof_hk'
-                    sw = replacement.split("/")
-                    suggestion = ""
-                    suggest = None
-                    sugglist: List[str] = []
-                    if len(sw) == 1 and sw[0].split("_")[0] == key:
-                        # We have a single suggested word, which is the same as the
-                        # taboo word: there is no suggestion, only a notification
-                        explanation = "Óheppilegt eða óviðurkvæmilegt orð"
-                    else:
-                        suggestion = ", ".join(f"'{w.split('_')[0]}'" for w in sw)
-                        # Trick to replace the last ", " with " eða ":
-                        # replace the first " ," with " aðe " in a reversed string,
-                        # then re-reverse it
-                        suggestion = suggestion[::-1].replace(" ,", " aðe ", 1)[::-1]
-                        explanation = (
-                            f"Óheppilegt eða óviðurkvæmilegt orð, "
-                            f"skárra væri t.d. {suggestion}"
-                        )
-                        suggest = sw[0].split("_")[0]
-                        sugglist = list(w.split("_")[0] for w in sw)
-                    if (
-                        token.error_code
-                        and token.original
-                        and token.error_code[0] == "W"
-                        and token.txt.strip() != token.original.strip()
-                    ):
-                        # The system seems to have used automatic methods to 'correct'
-                        # to a taboo word: remove the error
-                        orig = (
-                            token.original.strip()
-                            if token.original
-                            else token.txt.strip()
-                        )
-                        token.remove_error(orig)
-                    else:
-                        token.set_error(
-                            TabooWarning(
-                                "001",
-                                explanation,
-                                detail or None,
-                                token.txt,
-                                suggest,
-                                sugglist,
+def check_wording(
+    token_stream: Iterable[CorrectToken],
+    settings: Settings,
+    db: GreynirBin,
+    suggest_not_correct: bool,
+) -> Iterator[CorrectToken]:
+    """Annotate words to be flagged, with warnings. Here we check for both taboo words and
+    tone of voice issues as determined by an additional config, if given."""
+
+    taboo_data = create_template_dict(
+        settings,
+        "Óheppilegt eða óviðurkvæmilegt orð",
+        "Óheppilegt eða óviðurkvæmilegt orð, skárra væri t.d. ",
+        TabooWarning,
+        settings.taboo_words.DICT,
+    )
+
+    tone_of_voice_data = create_template_dict(
+        settings,
+        "Orðið er ekki í samræmi við raddblæ okkar",
+        "Orðið er ekki í samræmi við raddblæ okkar, í staðinn gætirðu notað ",
+        ToneOfVoiceWarning,
+        settings.tone_of_voice_words.DICT,
+    )
+
+    def handle_template_data(token_stream, tdict):
+        for token in token_stream:
+            # Check taboo words
+            if (  # type: ignore
+                token.val is not None
+                and token.has_meanings
+                and token.txt not in NOT_TABOO
+            ):
+                # We skip checks for tokens already containing an error, as the flagged word
+                # might be the system's invention.
+                for m in token.meanings:
+                    key = m.stofn.replace("-", "")
+                    # First, look up the lemma + _ + word category
+                    t = tdict["words"].get(key + "_" + m.ordfl)
+                    if t is None:
+                        # Then, look up the lemma only
+                        t = tdict["words"].get(key)
+                    if t is not None:
+                        # Flagged word
+                        replacement, detail = t
+                        # There can be multiple suggested replacements,
+                        # for instance 'þungunarrof_hk/meðgöngurof_hk'
+                        sw = replacement.split("/")
+                        suggestion = ""
+                        suggest = None
+
+                        suggest, sugg_cat = sw[0].split("_")
+                        sugglist: List[str] = []
+                        if len(sw) == 1 and sw[0].split("_")[0] == key:
+                            # We have a single suggested word, which is the same as the
+                            # flagged word: there is no suggestion, only a notification
+                            explanation = tdict["explanation"]
+                        else:
+                            suggestion = ", ".join(f"'{w.split('_')[0]}'" for w in sw)
+                            # Trick to replace the last ", " with " eða ":
+                            # replace the first " ," with " aðe " in a reversed string,
+                            # then re-reverse it
+                            suggestion = suggestion[::-1].replace(" ,", " aðe ", 1)[
+                                ::-1
+                            ]
+                            explanation = f'{tdict["explanation_w_sugg"]} {suggestion}'
+                            sugglist = list(w.split("_")[0] for w in sw)
+                        if (
+                            token.error_code
+                            and token.original
+                            and token.error_code[0] == "W"
+                            and token.txt.strip() != token.original.strip()
+                        ):
+                            # The system seems to have used automatic methods to 'correct'
+                            # to a flagged word: remove the error
+                            orig = (
+                                token.original.strip()
+                                if token.original
+                                else token.txt.strip()
                             )
-                        )
-                        # !!! TODO: Add correctly inflected suggestion here
-                    break
-        yield token
+                            token.remove_error(orig)
+                        else:
+                            beyging = token[2][0].beyging
+                            suggest_object = db.lookup_variants(
+                                suggest, sugg_cat, beyging, lemma=suggest
+                            )
+                            if suggest_object:
+                                bmynd = suggest_object[0].bmynd
+                                suggest = emulate_case(bmynd, template=token.txt)
+                            # Word not found in BÍN
+                            # else:
+                            token.set_error(
+                                tdict["error_warning"](
+                                    "001",
+                                    explanation,
+                                    detail or None,
+                                    token.txt,
+                                    suggest,
+                                    sugglist,
+                                )
+                            )
+                        break
+            yield token
+
+    token_stream = handle_template_data(token_stream, taboo_data)
+    token_stream = handle_template_data(token_stream, tone_of_voice_data)
+    yield from token_stream
 
 
 def check_style(
     token_stream: Iterable[CorrectToken],
     db: GreynirBin,
     ignore_rules: FrozenSet[str],
 ) -> Iterator[CorrectToken]:
@@ -2924,14 +2962,15 @@
                 # We use the first meaning only, but theoretically there could
                 # be different annotations for different meanings.
                 k = k_meanings[0]
                 warning = STYLE_WARNINGS[style_warning(k)]
                 # Check whether we have a suggestion in BÍN
                 suggestion = None
                 suffix = ""
+
                 if k.millivisun:
                     # Cross-reference to another word
                     k_suggestions = db.lookup_id(k.millivisun)
                     # Find the same inflection form as the original word, if available
                     k_sugg = next((s for s in k_suggestions if s.mark == k.mark), None)
                     if k_sugg is not None:
                         # Found a suggestion: emulate its case
@@ -3106,77 +3145,88 @@
     """Override the default tokenization pipeline defined in bintokenizer.py
     in GreynirPackage, adding a correction phase"""
 
     # Use the Correct_TOK class to construct tokens, instead of
     # TOK (tokenizer.py) or Bin_TOK (bintokenizer.py)
     _token_ctor = cast(TokenConstructor, Correct_TOK)
 
-    def __init__(self, text_or_gen: StringIterable, **options: Any) -> None:
+    def __init__(
+        self, text_or_gen: StringIterable, settings: Settings, **options: Any
+    ) -> None:
         super().__init__(text_or_gen, **options)
         self._corrector: Optional[Corrector] = None
         # If only_ci is True, we only correct context-independent errors
         self._only_ci = options.pop("only_ci", False)
         # If apply_suggestions is True, we are aggressive in modifying
         # tokens with suggested corrections, i.e. not just suggesting them
         self._apply_suggestions = options.pop("apply_suggestions", False)
         # If generate_suggestion_list is True, we get a list of suggestions from
         # the spelling suggestion module
         self._generate_suggestion_list = options.pop("generate_suggestion_list", False)
         # Skip spelling suggestions
         self._suppress_suggestions = options.pop("suppress_suggestions", False)
-        # Only give suggestions, don't correct anything automatically
+        # Only give suggestions, don't correct everything automatically. Currently only applies to lookup_unknown_words and check_wording.
         self._suggest_not_correct = options.pop("suggest_not_correct", False)
         # Wordlist for words that should not be marked as errors or corrected
         self._ignore_wordlist = options.pop("ignore_wordlist", set())
         self._ignore_rules = options.pop("ignore_rules", set())
+        self.settings = settings
 
     def correct_tokens(self, stream: TokenIterator) -> TokenIterator:
         """Add a correction pass just before BÍN annotation"""
         assert self._db is not None
-        return parse_errors(stream, self._db, self._only_ci, self._ignore_rules)
+        return parse_errors(
+            stream, self._db, self._only_ci, self._ignore_rules, self.settings
+        )
 
     def check_spelling(self, stream: TokenIterator) -> TokenIterator:
         """Attempt to resolve unknown words"""
         # Create a Corrector on the first invocation
         assert self._db is not None
         if self._corrector is None:
             self._corrector = Corrector(self._db)
         only_ci = self._only_ci
         ignore_rules = self._ignore_rules
+
         # Shenanigans to satisfy mypy
         token_ctor = cast(TokenCtor, self._token_ctor)
         ct_stream = cast(Iterator[CorrectToken], stream)
         # Fix compound words
         ct_stream = fix_compound_words(
-            ct_stream, self._db, token_ctor, only_ci, ignore_rules
+            ct_stream, self._db, token_ctor, only_ci, ignore_rules, self.settings
         )
         # Fix multiword error phrases
         if not only_ci:
             ct_stream = handle_multiword_errors(
-                ct_stream, self._db, token_ctor, ignore_rules
+                ct_stream, self._db, token_ctor, ignore_rules, self.settings
             )
         # Fix capitalization
         ct_stream = fix_capitalization(
-            ct_stream, self._db, token_ctor, only_ci, ignore_rules
+            ct_stream, self._db, token_ctor, only_ci, ignore_rules, self.settings
         )
         # Fix single-word errors
         ct_stream = lookup_unknown_words(
             ct_stream,
             token_ctor,
             self._corrector,
             only_ci,
             ignore_rules,
             self._apply_suggestions,
             self._suppress_suggestions,
             self._generate_suggestion_list,
             self._suggest_not_correct,
+            self.settings,
         )
-        # Check taboo words
-        if not only_ci and "T001/w" not in ignore_rules and "T001" not in ignore_rules:
-            ct_stream = check_taboo_words(ct_stream)
+        # Check taboo words and tone of voice words
+        err_codes = {"T001/w", "T001", "V001/w", "V001"}
+        if not only_ci and all(code not in ignore_rules for code in err_codes):
+            ct_stream = check_wording(
+                ct_stream, self.settings, self._db, self._suggest_not_correct
+            )
+
         # Check context-independent style errors, indicated in BÍN
         ct_stream = check_style(ct_stream, self._db, ignore_rules)
         return ct_stream
 
     def final_correct(self, stream: TokenIterator) -> TokenIterator:
         """Final correction pass"""
         assert self._db is not None
@@ -3187,20 +3237,23 @@
         ct_stream = late_fix_capitalization(
             ct_stream,
             self._db,
             token_ctor,
             self._only_ci,
             self._ignore_rules,
             self._suppress_suggestions,
+            self.settings,
         )
 
         ct_stream = late_fix_merges(
             ct_stream, self._ignore_wordlist, self._ignore_rules
         )
         return ct_stream
 
 
-def tokenize(text_or_gen: StringIterable, **options: Any) -> Iterator[CorrectToken]:
+def tokenize(
+    text_or_gen: StringIterable, settings: Settings, **options: Any
+) -> Iterator[CorrectToken]:
     """Tokenize text using the correction pipeline,
     overriding a part of the default tokenization pipeline"""
-    pipeline = CorrectionPipeline(text_or_gen, **options)
+    pipeline = CorrectionPipeline(text_or_gen, settings, **options)
     return cast(Iterator[CorrectToken], pipeline.tokenize())
```

### Comparing `reynir-correct-3.4.6/src/reynir_correct/main.py` & `reynir-correct-3.4.7/src/reynir_correct/main.py`

 * *Files 15% similar despite different names*

```diff
@@ -40,14 +40,15 @@
     Dict,
     Union,
 )
 
 import sys
 import argparse
 from .wrappers import check_errors
+from .settings import Settings
 
 
 # File types for UTF-8 encoded text files
 ReadFile = argparse.FileType("r", encoding="utf-8")
 WriteFile = argparse.FileType("w", encoding="utf-8")
 
 # Define the command line arguments
@@ -133,14 +134,30 @@
 parser.add_argument(
     "--sentence_prefilter",
     help="Run a heuristic filter on sentences to determine whether they are probably correct. Probably correct sentences will not go through the full parsing process.",
     action="store_true",
 )
 
 
+parser.add_argument(
+    "--tov_config",
+    nargs=1,
+    type=str,
+    help="Add additional use-specific rules in a configuration file to check for custom tone-of-voice issues. Uses the same format as the default GreynirCorrect.conf file",
+    default=False,
+)
+
+parser.add_argument(
+    "--suggest_not_correct",
+    help="Instead of directly changing the text, some stylistic errors are presented as suggestions only.",
+    action="store_true",
+    default=False,
+)
+
+
 def main() -> None:
     """Main function, called when the 'correct' command is invoked"""
 
     args = parser.parse_args()
     # Fill options with information from args
     if args.infile is sys.stdin and sys.stdin.isatty():
         # terminal input is empty, most likely no value was given for infile:
@@ -152,16 +169,20 @@
     if args.suppress_suggestions:
         options["suppress_suggestions"] = args.suppress_suggestions
     options["format"] = args.format
     if args.json:
         options["format"] = "json"
     elif args.csv:
         options["format"] = "csv"
+    if args.tov_config:
+        options["tov_config"] = args.tov_config[0]
     options["spaced"] = args.spaced
     options["normalize"] = args.normalize
     options["all_errors"] = args.all_errors or args.grammar
     options["sentence_prefilter"] = args.sentence_prefilter
+    options["suggest_not_correct"] = args.suggest_not_correct
+
     print(check_errors(**options), file=args.outfile)
 
 
 if __name__ == "__main__":
     main()
```

### Comparing `reynir-correct-3.4.6/src/reynir_correct/pattern.py` & `reynir-correct-3.4.7/src/reynir_correct/pattern.py`

 * *Files 7% similar despite different names*

```diff
@@ -49,15 +49,14 @@
     Callable,
     Dict,
     Optional,
     Union,
     cast,
 )
 
-from threading import Lock
 from functools import partial
 import os
 import json
 
 from islenska import Bin
 
 from reynir import Sentence, NounPhrase
@@ -65,19 +64,18 @@
 from reynir.verbframe import VerbErrors
 from reynir.matcher import ContextDict
 from reynir.bintokenizer import ALL_CASES
 
 from reynir_correct.errtokenizer import emulate_case
 
 from .annotation import Annotation
-from reynir_correct.errtokenizer import emulate_case
 
 
 # The types involved in pattern processing
-AnnotationFunction = Callable[["PatternMatcher", SimpleTree], None]
+AnnotationFunction = Callable[[SimpleTree], None]
 PatternTuple = Tuple[
     Union[str, Set[str], FrozenSet[str]], str, AnnotationFunction, Optional[ContextDict]
 ]
 
 BIN = Bin()
 
 # Variants not needed for lookup
@@ -157,51 +155,44 @@
     # * Trigger lemma, which must be present in the sentence for the pattern
     #   to be applied. This is an optimization only, to save unnecessary matching.
     #   If the trigger is falsy (None, ""), it is not applied and the sentence will be
     #   checked regardless of its content.
     # * Match pattern expression, to be passed to match_pattern()
     # * Annotation function, called for each match
     # * Context dictionary to be passed to match_pattern()
-
-    PATTERNS: List[PatternTuple] = []
-
-    _LOCK = Lock()
-
-    ctx_af: ContextDict = cast(ContextDict, None)
-    ctx_að: ContextDict = cast(ContextDict, None)
-    ctx_noun_af: ContextDict = cast(ContextDict, None)
-    ctx_noun_af_obj: ContextDict = cast(ContextDict, None)
-    ctx_verb_01: ContextDict = cast(ContextDict, None)
-    ctx_verb_02: ContextDict = cast(ContextDict, None)
-    ctx_noun_að: ContextDict = cast(ContextDict, None)
-    ctx_subjsing: ContextDict = cast(ContextDict, None)
-    ctx_place_names: ContextDict = cast(ContextDict, None)
-    ctx_uncertain_verbs: ContextDict = cast(ContextDict, None)
-    ctx_confident_verbs: ContextDict = cast(ContextDict, None)
-    ctx_dir_loc: ContextDict = cast(ContextDict, None)
-
     def __init__(self, ann: List[Annotation], sent: Sentence) -> None:
         # Annotation list
         self._ann = ann
         # The original sentence object
         self._sent = sent
         # Token list
         self._tokens = sent.tokens
         # Terminal node list
         self._terminal_nodes = sent.terminal_nodes
-        # Avoid race conditions in multi-threaded scenarios
-        with self._LOCK:
-            if not self.PATTERNS:
-                # First instance: create the class-wide pattern list
-                self.create_patterns()
 
-    @classmethod
-    def get_wordform(
-        cls, word: str, lemma: str, cat: str, variants: Iterable[str]
-    ) -> str:
+        self.PATTERNS: List[PatternTuple] = []
+
+        self.ctx_af: ContextDict = cast(ContextDict, None)
+        self.ctx_að: ContextDict = cast(ContextDict, None)
+        self.ctx_noun_af: ContextDict = cast(ContextDict, None)
+        self.ctx_noun_af_obj: ContextDict = cast(ContextDict, None)
+        self.ctx_verb_01: ContextDict = cast(ContextDict, None)
+        self.ctx_verb_02: ContextDict = cast(ContextDict, None)
+        self.ctx_noun_að: ContextDict = cast(ContextDict, None)
+        self.ctx_subjsing: ContextDict = cast(ContextDict, None)
+        self.ctx_place_names: ContextDict = cast(ContextDict, None)
+        self.ctx_uncertain_verbs: ContextDict = cast(ContextDict, None)
+        self.ctx_confident_verbs: ContextDict = cast(ContextDict, None)
+        self.ctx_dir_loc: ContextDict = cast(ContextDict, None)
+
+        # First instance: create the class-wide pattern list
+        self.create_patterns()
+
+    @staticmethod
+    def get_wordform(word: str, lemma: str, cat: str, variants: Iterable[str]) -> str:
         """Get correct wordform from BinPackage,
         given a set of variants"""
         realvars: Union[Set[str], Iterable[str]]
         if cat == "so":
             # Get rid of irrelevant variants for verbs
             realvars = set(variants) - SKIPVARS
             if "lhþt" not in realvars:
@@ -1372,15 +1363,15 @@
         realso = realso.first_match("so_nh")
         if realso is None:
             return
         _, end = realso.span
         if "þt" in so.all_variants:
             # The past tense behaves differently, much less likely to be an error
             return
-        suggest = self.get_wordform(
+        suggest = PatternMatcher.get_wordform(
             realso.text.lower(), realso.lemma, realso.cat, so.all_variants
         )
         if not suggest:
             return
         text = (
             f"Mælt er með að sleppa '{so.tidy_text} að' og beygja frekar sögnina "
             f"'{realso.lemma}' svo hún verði '{suggest}'."
@@ -1560,15 +1551,15 @@
             return
         start, end = so.span
         if "þt" in so.all_variants:
             return
         variants = set(so.all_variants) - {"vh"}
         variants.add("fh")
         so_text = so.text.lower()
-        suggest = self.get_wordform(so_text, so.lemma, so.cat, variants)
+        suggest = PatternMatcher.get_wordform(so_text, so.lemma, so.cat, variants)
         if suggest == so_text:
             return
         if not suggest:
             return
         text = (
             f"Hér á líklega að nota framsöguhátt sagnarinnar '{so_text}', "
             f"þ.e. '{suggest}'."
@@ -1608,15 +1599,15 @@
         so = vp.first_match("so")
         if so is None:
             return
         start, end = so.span
         variants = set(so.all_variants) - {"fh"}
         variants.add("vh")
         so_text = so.text.lower()
-        suggest = self.get_wordform(so_text, so.lemma, so.cat, variants)
+        suggest = PatternMatcher.get_wordform(so_text, so.lemma, so.cat, variants)
         if not suggest or suggest == so_text:
             return
         text = (
             f"Hér er réttara að nota viðtengingarhátt "
             f"sagnarinnar '{so.lemma}', þ.e. '{suggest}'."
         )
         if kind == "ACK":
@@ -1708,15 +1699,15 @@
         no = match.first_match("no_ft")
         if no is None:
             return
         start, end = so.span
         variants = set(so.all_variants) - {"et"}
         variants.add("ft")
         so_text = so.text.lower()
-        suggest = self.get_wordform(so_text, so.lemma, so.cat, variants)
+        suggest = PatternMatcher.get_wordform(so_text, so.lemma, so.cat, variants)
         if not suggest or suggest == so_text:
             return
         text = (
             f"Hér er réttara að nota fleirtölu "
             f"sagnarinnar '{so.lemma}', þ.e. '{suggest}'."
         )
         if kind == "GEN":
@@ -1765,15 +1756,15 @@
         no = match.first_match("no_et")
         if no is None:
             return
         start, end = so.span
         variants = set(so.all_variants) - {"ft"}
         variants.add("et")
         so_text = so.text.lower()
-        suggest = self.get_wordform(so_text, so.lemma, so.cat, variants)
+        suggest = PatternMatcher.get_wordform(so_text, so.lemma, so.cat, variants)
         if not suggest or suggest == so_text:
             return
         text = (
             f"Hér er réttara að nota eintölu "
             f"sagnarinnar '{so.lemma}', þ.e. '{suggest}'."
         )
         if kind == "GEN":
@@ -1842,26 +1833,24 @@
                 text=text,
                 detail=detail,
                 original="né",
                 suggest=correction,
             )
         )
 
-    @classmethod
-    def add_pattern(cls, p: PatternTuple) -> None:
+    def add_pattern(self, p: PatternTuple) -> None:
         """Validates and adds a pattern to the class global pattern list"""
         _, pattern, _, ctx = p
         if "%" in pattern:
             assert ctx is not None, "Missing context for pattern with %macro"
         else:
             assert ctx is None, "Unnecessary context given for pattern with no %macro"
-        cls.PATTERNS.append(p)
+        self.PATTERNS.append(p)
 
-    @classmethod
-    def create_patterns(cls) -> None:
+    def create_patterns(self) -> None:
         """Initialize the list of patterns and handling functions"""
 
         # Access the dictionary of verb+preposition attachment errors
         # from the settings (actually from the reynir settings),
         # read from config/Verbs.conf
         prep_errors = VerbErrors.PREPOSITIONS_ERRORS
 
@@ -1906,515 +1895,515 @@
             # does not have arguments (i.e. it doesn't have 1 or 2 arguments; it may
             # have none or 0). An example is a 'so_0_gm_fh_nt' terminal matching the
             # verb 'leita'.
 
             # Note that we use the own_lemma_mm property instead of own_lemma. This
             # means that the lambda condition matches middle voice stem forms,
             # such as 'dást' instead of 'dá'.
-            cls.ctx_af = {
+            self.ctx_af = {
                 "verb": lambda tree: (
                     tree.own_lemma_mm in verbs_af
                     and not (set(tree.variants) & {"1", "2"})
                 )
             }
             # Catch sentences such as 'Jón leitaði af kettinum'
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     verbs_af,  # Trigger lemma for this pattern
                     'VP > { VP >> { %verb } PP >> { P > { "af" } } }',
-                    cls.wrong_preposition_af,
-                    cls.ctx_af,
+                    self.wrong_preposition_af,
+                    self.ctx_af,
                 )
             )
             # Catch sentences such as 'Vissulega er hægt að brosa af þessu',
             # 'Friðgeir var leitandi af kettinum í allan dag'
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     verbs_af,  # Trigger lemma for this pattern
                     '. > { (NP-PRD | IP-INF) > { VP > { %verb } } PP >> { P > { "af" } } }',
-                    cls.wrong_preposition_af,
-                    cls.ctx_af,
+                    self.wrong_preposition_af,
+                    self.ctx_af,
                 )
             )
             # Catch "Það sem Jón spurði ekki af...", "Jón spyr (ekki) af því."
-            #    cls.add_pattern(
+            #    self.add_pattern(
             #        (
             #            "spyrja",  # Trigger lemma for this pattern
             #            "IP > { VP >> { 'spyrja' } ADVP > { 'af' } }",
-            #            cls.wrong_preposition_af,
-            #            cls.ctx_af,
+            #            self.wrong_preposition_af,
+            #            self.ctx_af,
             #        )
             #    )
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "spyrja",  # Trigger lemma for this pattern
                     "VP > { VP > { 'spyrja' } ADVP > { \"af\" } }",
-                    cls.wrong_preposition_spyrja_af,
+                    self.wrong_preposition_spyrja_af,
                     None,
                 )
             )
             # Catch "Jón spyr af því."
-            #    cls.add_pattern(
+            #    self.add_pattern(
             #        (
             #            "spyrja",  # Trigger lemma for this pattern
             #            "IP > { VP >> { 'spyrja' } PP > { 'af' } }",
-            #            cls.wrong_preposition_af,
+            #            self.wrong_preposition_af,
             #            None,
             #        )
             #    )
             # Catch "...vegna þess að dýr leita af öðrum smærri dýrum."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "leita",  # Trigger lemma for this pattern
                     "VP > { PP >> { 'leita' } PP > 'af' }",
-                    cls.wrong_preposition_af,
+                    self.wrong_preposition_af,
                     None,
                 )
             )
 
             # Catch "Þetta er mesta vitleysa sem ég hef orðið vitni af", "Hún varð vitni af því þegar kúturinn sprakk"
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "vitni",  # Trigger lemma for this pattern
                     "VP > { VP > { ('verða'|'vera') } NP > { \"vitni\" } ADVP > \"af\" }",
-                    cls.wrong_preposition_vitni_af,
+                    self.wrong_preposition_vitni_af,
                     None,
                 )
             )
             # Catch "Hún gerði grín af því.", "Þetta er mesta vitleysa sem ég hef gert grín af.", "...og gerir grín af sjálfum sér."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "grín",  # Trigger lemma for this pattern
                     # "IP",
                     "VP > { NP > { 'grín' } ( PP|ADVP ) > { \"af\" } }",
-                    cls.wrong_preposition_grin_af,
+                    self.wrong_preposition_grin_af,
                     None,
                 )
             )
             # Catch "Hann leiðir (ekki) líkur af því.", "Hann hefur aldrei leitt líkur af því."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "leiða",  # Trigger lemma for this pattern
                     "VP > { VP > { 'leiða' } NP > { ('líkur' | 'rök' | 'rak') } PP > { \"af\" } }",
-                    cls.wrong_preposition_leida_af,
+                    self.wrong_preposition_leida_af,
                     None,
                 )
             )
             # Catch "Tíminn markar upphaf af því."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "upphaf",  # Trigger lemma for this pattern
                     "VP > { VP > { 'marka' } NP-OBJ > { 'upphaf' PP > { 'af' } } }",
-                    cls.wrong_preposition_marka_af,
+                    self.wrong_preposition_marka_af,
                     None,
                 )
             )
             # Catch "Það markar ekki upphaf af því."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     frozenset(
                         ("upphafinn", "upphaf")
                     ),  # Trigger lemma for this pattern
                     "VP > { VP > { 'marka' } NP > { ('upphafinn'|'upphaf') } PP > { 'af' } }",
-                    cls.wrong_preposition_marka_af,
+                    self.wrong_preposition_marka_af,
                     None,
                 )
             )
             # Catch "Það markar upphaf af því."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "upphaf",  # Trigger lemma for this pattern
                     "VP > { VP > { VP > { 'marka' } NP-SUBJ > { 'upphaf' } } PP > { 'af' } }",
-                    cls.wrong_preposition_marka_af,
+                    self.wrong_preposition_marka_af,
                     None,
                 )
             )
-            #    cls.add_pattern(
+            #    self.add_pattern(
             #        (
             #            "upphefja",  # Trigger lemma for this pattern
             #            "IP",
-            #            cls.wrong_preposition_marka_af,
+            #            self.wrong_preposition_marka_af,
             #            None,
             #        )
             #    )
             # Catch "Það hefur ekki markað upphafið af því."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "upphefja",  # Trigger lemma for this pattern
                     "VP > { NP > { 'markaður' } VP > { 'upphefja' } PP > { 'af' } }",
-                    cls.wrong_preposition_marka_af,
+                    self.wrong_preposition_marka_af,
                     None,
                 )
             )
             # Catch "Jón leggur hann (ekki) af velli.", "Jón hefur (ekki) lagt hann af velli."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     frozenset(
                         ("völlur", "vell", "velli")
                     ),  # Trigger lemmas for this pattern
                     'VP > { VP > { \'leggja\' } PP > { P > { "af" } NP > { "velli" } } }',
-                    cls.wrong_preposition_leggja_af,
+                    self.wrong_preposition_leggja_af,
                     None,
                 )
             )
             # Catch "Jón kann það (ekki) utan af."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "kunna",  # Trigger lemma for this pattern
                     "VP > { VP > { 'kunna' } ADVP > { 'utan' } ADVP > { 'af' } }",
-                    cls.wrong_preposition_utan_af,
+                    self.wrong_preposition_utan_af,
                     None,
                 )
             )
             # Catch "Honum varð af ósk sinni."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "ósk",  # Trigger lemma for this pattern
                     "(S-MAIN | IP) > { VP > { 'verða' } PP > { 'af' NP > { 'ósk' } } }",
-                    cls.wrong_preposition_verða_af,
+                    self.wrong_preposition_verða_af,
                     None,
                 )
             )
             # Catch "...en varð ekki af ósk sinni."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "ósk",  # Trigger lemma for this pattern
                     "IP > { VP > { VP > { 'verða' } PP > { P > { 'af' } NP > { 'ósk' } } } }",
-                    cls.wrong_preposition_verða_af,
+                    self.wrong_preposition_verða_af,
                     None,
                 )
             )
             # Catch "Ég varð (ekki) uppvís af athæfinu.", "Hann hafði (ekki) orðið uppvís af því."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "uppvís",  # Trigger lemma for this pattern
                     "VP > { VP > { 'verða' } NP > { 'uppvís' } PP > { 'af' } }",
-                    cls.wrong_preposition_uppvis_af,
+                    self.wrong_preposition_uppvis_af,
                     None,
                 )
             )
 
         if verbs_að:
             # Create matching patterns with a context that catches the að/af verbs.
-            cls.ctx_að = {
+            self.ctx_að = {
                 "verb": lambda tree: (
                     tree.own_lemma_mm in verbs_að
                     and not (set(tree.variants) & {"1", "2"})
                 )
             }
             # Catch sentences such as 'Jón heillaðist að kettinum'
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     verbs_að,  # Trigger lemmas for this pattern
                     'VP > { VP >> { %verb } PP >> { P > { "að" } } }',
-                    cls.wrong_preposition_að,
-                    cls.ctx_að,
+                    self.wrong_preposition_að,
+                    self.ctx_að,
                 )
             )
             # Catch sentences such as 'Vissulega er hægt að heillast að þessu'
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     verbs_að,  # Trigger lemma for this pattern
                     '(NP-PRD | IP-INF) > { VP > { %verb } } PP >> { P > { "að" } }',
-                    cls.wrong_preposition_að,
-                    cls.ctx_að,
+                    self.wrong_preposition_að,
+                    self.ctx_að,
                 )
             )
             # Catch "Þetta er fallegasta kona sem ég hef orðið heillaður að"
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "heilla",  # Trigger lemma for this pattern
                     "VP > { VP > [ .* ('verða' | 'vera') ] NP-PRD > [ .* 'heilla' .* ADVP > { \"að\" } ] }",
-                    cls.wrong_preposition_heillaður_að,
+                    self.wrong_preposition_heillaður_að,
                     None,
                 )
             )
             # Catch "Ég hef lengi verið heillaður að henni."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "heilla",  # Trigger lemma for this pattern
                     "NP > { NP >> { 'heilla' } PP > { 'að' } }",
-                    cls.wrong_preposition_heillaður_að,
+                    self.wrong_preposition_heillaður_að,
                     None,
                 )
             )
             # Catch "Ég er (ekki) hluti að heildinni.", "Við höfum öll verið hluti að heildinni."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "hluti",  # Trigger lemma for this pattern
                     "VP > { NP > { 'hluti' } PP > { \"að\" } }",
                     # "VP > { VP > { 'vera' NP-PRD > { 'hluti' } } PP > { 'að' } }",
-                    cls.wrong_preposition_hluti_að,
+                    self.wrong_preposition_hluti_að,
                     None,
                 )
             )
             # Catch "Þeir sögðu að ég hefði verið hluti að heildinni."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "hluti",  # Trigger lemma for this pattern
                     "NP > { 'hluti' PP > { \"að\" } }",
-                    cls.wrong_preposition_hluti_að,
+                    self.wrong_preposition_hluti_að,
                     None,
                 )
             )
             # Catch "Þeir sögðu að ég hefði verið hluti að heildinni."  # Two patterns to catch the same sentence due to variable parsing
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "hluti",  # Trigger lemma for this pattern
                     "VP > { CP >> { 'hluti' } PP > { \"að\" } }",
-                    cls.wrong_preposition_hluti_að,
+                    self.wrong_preposition_hluti_að,
                     None,
                 )
             )
             # Catch "Ég hef (ekki) áhyggjur að honum.", "Ég hef áhyggjur að því að honum líði illa."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "áhyggja",  # Trigger lemma for this pattern
                     "VP > { NP > { 'áhyggja' } PP > { \"að\" } }",
                     # "VP > { VP >> { 'áhyggja' } PP > { 'að' } }",
-                    cls.wrong_preposition_ahyggja_að,
+                    self.wrong_preposition_ahyggja_að,
                     None,
                 )
             )
             # Catch "Ég hafði ekki lagt mikið að mörkum."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     frozenset(("mörk", "mark")),  # Trigger lemmas for this pattern
                     'VP > { VP >> { \'leggja\' } PP > { "að" "mörkum" } }',
-                    cls.wrong_preposition_að_mörkum,
+                    self.wrong_preposition_að_mörkum,
                     None,
                 )
             )
             # Catch "Jón hefur látið gott að sér leiða."
-            # cls.add_pattern(
+            # self.add_pattern(
             #    (
             #        "leiða",  # Trigger lemma for this pattern
             #        "VP > { VP > { 'láta' } PP > { P > \"að\" } VP > { 'leiða' } }",
-            #        cls.wrong_preposition_að_leiða,
+            #        self.wrong_preposition_að_leiða,
             #        None,
             #    )
             # )
             # Catch "Ég lét gott að mér leiða."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "leiða",  # Trigger lemma for this pattern
                     'VP > [ .* VP > { \'láta\' } NP ("að mér"|"að þér"|"að sér") \'leiða\']',
-                    cls.wrong_preposition_að_leiða,
+                    self.wrong_preposition_að_leiða,
                     None,
                 )
             )
             # Catch "Ég lét (ekki) gott að mér leiða." (In case of different parse)
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "leiður",  # Trigger lemma for this pattern
                     'VP > [ VP > [ .* \'láta\' .* ] NP > [ .* "gott" .* ] PP > [ "að" NP > [ ("mér"|"þér"|"sér"|"okkur") ] "leiða" ] ]',
-                    cls.wrong_preposition_að_leiða,
+                    self.wrong_preposition_að_leiða,
                     None,
                 )
             )
             # Catch "Hann lét (ekki) gott að sér leiða"
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "leiða",  # Trigger lemma for this pattern
                     'VP > [ VP > [ .* \'láta\' .* ] .* NP > [ .* "gott" .* ] PP > [ "að" NP > [ ("mér"|"þér"|"sér"|"okkur") ] ] VP > { \'leiða\' } ]',
-                    cls.wrong_preposition_að_leiða,
+                    self.wrong_preposition_að_leiða,
                     None,
                 )
             )
             # Catch "...lét ég (ekki) gott að mér leiða"
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "leiða",  # Trigger lemma for this pattern
                     'VP > [ VP > [ .* \'láta\' .* ] .* IP > [ NP > [ .* "gott" PP > [ "að" NP > [ ("mér"|"þér"|"sér"|"okkur") ] ] ] VP > { \'leiða\' } ] ]',
-                    cls.wrong_preposition_að_leiða,
+                    self.wrong_preposition_að_leiða,
                     None,
                 )
             )
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     frozenset(
                         ("leiða", "leiður")
                     ),  # Trigger lemma for this pattern (probably a wrong parse)
                     'VP > [ .* \'láta\' .* NP-OBJ > [ .* "gott" .* ("að mér leiða" | "að sér leiða" | "að þér leiða") ] ]',
-                    cls.wrong_preposition_að_leiða,
+                    self.wrong_preposition_að_leiða,
                     None,
                 )
             )
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     frozenset(
                         ("leiða", "leiður")
                     ),  # Trigger lemma for this pattern (probably a wrong parse)
                     'VP > { IP-INF > { "að" "láta" } NP-PRD > { "gott" } PP > [ "að" ( "mér" | "þér" | "sér" ) "leiða" ] }',
-                    cls.wrong_preposition_að_leiða,
+                    self.wrong_preposition_að_leiða,
                     None,
                 )
             )
             # Catch "Hún á/fær/hlýtur (ekki) heiðurinn að þessu.", "Hún hafði (ekki) fengið/hlotið heiðurinn að þessu." ÞA: Including 'eiga' here causes double annotation
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "heiður",  # Trigger lemma for this pattern
                     (
                         "( "
                         "VP > [ VP-AUX? .* VP > { ( 'fá'|'hljóta' ) } .* NP-OBJ > { 'heiður' PP > { P > { 'að' } NP } } ] "
                         "| "
                         "VP > [ VP-AUX? .* VP > { ( 'fá'|'hljóta' ) } .* NP-OBJ > { 'heiður' } PP > { P > { 'að' } NP } ] "
                         ") "
                     ),
-                    cls.wrong_preposition_heiður_að,
+                    self.wrong_preposition_heiður_að,
                     None,
                 )
             )
             # Catch "Hún á (ekki) mikið/fullt/helling/gommu... að börnum."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "eiga",  # Trigger lemma for this pattern
                     (
                         "( "
                         "VP > [ VP-AUX? .* VP > { 'eiga' } .* NP-OBJ PP > { P > { 'að' } NP } ] "
                         "| "
                         "VP > [ VP-AUX? .* VP > { 'eiga' } .* NP-OBJ > { PP > { P > { 'að' } NP } } ] "
                         ") "
                     ),
-                    cls.wrong_preposition_eiga_að,
+                    self.wrong_preposition_eiga_að,
                     None,
                 )
             )
             # Catch "Hún á (ekki) lítið að börnum."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "eiga",  # Trigger lemma for this pattern
                     "VP > { VP > { 'eiga' } ADVP > { 'lítið' } PP > { P > { 'að' } NP } }",
-                    cls.wrong_preposition_eiga_að,
+                    self.wrong_preposition_eiga_að,
                     None,
                 )
             )
             # Catch "Það er (ekki) til mikið að þessu."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "vera",  # Trigger lemma for this pattern
                     "VP > { VP > { 'vera' } NP > { NP >> { 'til' } PP > { 'að' } } }",
-                    cls.wrong_preposition_vera_til_að,
+                    self.wrong_preposition_vera_til_að,
                     None,
                 )
             )
             # Catch "Mikið er til að þessu."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "vera",  # Trigger lemma for this pattern
                     "( S|VP ) > { NP VP > { 'vera' } ADVP > { 'til' } PP > { 'að' } }",
-                    cls.wrong_preposition_vera_til_að,
+                    self.wrong_preposition_vera_til_að,
                     None,
                 )
             )
             # Catch "Ekki er mikið til að þessu."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "vera",  # Trigger lemma for this pattern
                     "VP > { VP > { 'vera' } ADVP > { 'til' } PP > { 'að' } }",
-                    cls.wrong_preposition_vera_til_að,
+                    self.wrong_preposition_vera_til_að,
                     None,
                 )
             )
             # Catch "Hún hefur (ekki) gagn að þessu.", "Hún hefur (ekki) haft gagn að þessu."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "gagn",  # Trigger lemma for this pattern
                     "VP > { NP > { 'gagn' } PP > { \"að\" } }",
-                    cls.wrong_preposition_gagn_að,
+                    self.wrong_preposition_gagn_að,
                     None,
                 )
             )
             # Catch "Hvaða gagn hef ég að þessu?"
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "gagn",  # Trigger lemma for this pattern
                     "S > { NP > { 'gagn' } IP > { VP > { VP > { 'hafa' } PP > { 'að' } } } }",
-                    cls.wrong_preposition_gagn_að,
+                    self.wrong_preposition_gagn_að,
                     None,
                 )
             )
             # Catch "Fréttir bárust (ekki) að slysinu."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "frétt",  # Trigger lemma for this pattern
                     "( IP|VP ) > { NP > { 'frétt' } VP > { PP > { P > { 'að' } } } }",
-                    cls.wrong_preposition_frettir_að,
+                    self.wrong_preposition_frettir_að,
                     None,
                 )
             )
             # Catch "Það bárust (ekki) fréttir að slysinu."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "frétt",  # Trigger lemma for this pattern
                     "NP > { 'frétt' PP > { P > { 'að' } } }",
-                    cls.wrong_preposition_frettir_að,
+                    self.wrong_preposition_frettir_að,
                     None,
                 )
             )
             # Catch "Hætta stafar (ekki) að þessu.", "Hætta hefur (ekki) stafað að þessu."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "stafa",  # Trigger lemma for this pattern
                     "VP > { VP >> { 'stafa' } ( PP|ADVP ) > { 'að' } }",
-                    cls.wrong_preposition_stafa_að,
+                    self.wrong_preposition_stafa_að,
                     None,
                 )
             )
             # Catch "Hún er (ekki) ólétt af sínu þriðja barni.", "Hún hefur (ekki) verið ólétt af sínu þriðja barni."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "óléttur",  # Trigger lemma for this pattern
                     "VP > { NP > { 'óléttur' } PP > { 'af' } }",
-                    cls.wrong_preposition_ólétt_af,
+                    self.wrong_preposition_ólétt_af,
                     None,
                 )
             )
             # Catch "Hún heyrði að lausa starfinu.", "Hún hefur (ekki) heyrt að lausa starfinu."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "heyra",  # Trigger lemma for this pattern
                     "( "
                     "VP > { VP >> { 'heyra' } PP > { 'að' } }"
                     "| "
                     "VP > [ VP > { 'heyra' } .* NP > { PP > { 'að' } } .* ]"
                     ") ",
-                    cls.wrong_preposition_heyra_að,
+                    self.wrong_preposition_heyra_að,
                     None,
                 )
             )
             # Catch "Ég hef (ekki) gaman að henni.", "Ég hef aldrei haft gaman að henni."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "gaman",  # Trigger lemma for this pattern
                     "( "
                     "VP > { VP > { 'hafa' } NP > { 'gaman' } PP > { 'að' } }"
                     "| "
                     "VP > [ .* VP > { 'hafa' } .* NP > { 'gaman' PP > { 'að' } } .* ]"
                     ")",
-                    cls.wrong_preposition_hafa_gaman_að,
+                    self.wrong_preposition_hafa_gaman_að,
                     None,
                 )
             )
             # Catch "Ég var valinn að henni.", "Ég hafði (ekki) verið valinn að henni."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "velja",  # Trigger lemma for this pattern
                     "VP > { VP > { 'velja' } PP > { 'að' } }",
                     # "NP-PRD > { NP-PRD > { 'velja' } PP > { 'að' } }",
-                    cls.wrong_preposition_valinn_að,
+                    self.wrong_preposition_valinn_að,
                     None,
                 )
             )
             # Catch "Ég var ekki valinn að henni.", "Þau voru sérstaklega valin að stjórninni."
-            cls.add_pattern(
+            self.add_pattern(
                 (
                     "valinn",  # Trigger lemma for this pattern
                     "VP > { NP > { 'valinn' } PP > { 'að' } }",
-                    cls.wrong_preposition_valinn_að,
+                    self.wrong_preposition_valinn_að,
                     None,
                 )
             )
 
         # Verbs used wrongly with particular nouns
         def wrong_noun(nouns: FrozenSet[str], tree: SimpleTree) -> bool:
             """Context matching function for the %noun macro in combinations
@@ -2441,40 +2430,40 @@
                 "átekt_ef",
             ]
         )
         # The macro %verb expands to "@'bjóða'" which matches terminals
         # whose corresponding token has a meaning with the 'bjóða' lemma.
         # The macro %noun is resolved by calling the function wrong_noun()
         # with the potentially matching tree node as an argument.
-        cls.ctx_verb_01 = {"verb": "@'bjóða'", "noun": partial(wrong_noun, NOUNS_01)}
-        cls.add_pattern(
+        self.ctx_verb_01 = {"verb": "@'bjóða'", "noun": partial(wrong_noun, NOUNS_01)}
+        self.add_pattern(
             (
                 "bjóða",  # Trigger lemma for this pattern
                 "VP > { VP > { %verb } NP-OBJ >> { %noun } }",
-                lambda self, match: self.wrong_verb_use(
+                lambda match: self.wrong_verb_use(
                     match,
                     "bíða",
-                    cls.ctx_verb_01,
+                    self.ctx_verb_01,
                 ),
-                cls.ctx_verb_01,
+                self.ctx_verb_01,
             )
         )
 
         NOUNS_02: FrozenSet[str] = frozenset(["haus_þgf", "þvottur_þgf"])
-        cls.ctx_verb_02 = {"verb": "@'hegna'", "noun": partial(wrong_noun, NOUNS_02)}
-        cls.add_pattern(
+        self.ctx_verb_02 = {"verb": "@'hegna'", "noun": partial(wrong_noun, NOUNS_02)}
+        self.add_pattern(
             (
                 "hegna",  # Trigger lemma for this pattern
                 "VP > { VP > { %verb } NP-OBJ >> { %noun } }",
-                lambda self, match: self.wrong_verb_use(
+                lambda match: self.wrong_verb_use(
                     match,
                     "hengja",
-                    cls.ctx_verb_02,
+                    self.ctx_verb_02,
                 ),
-                cls.ctx_verb_02,
+                self.ctx_verb_02,
             )
         )
 
         # 'af' incorrectly used with particular nouns
         def wrong_noun_af(nouns: FrozenSet[str], tree: SimpleTree) -> bool:
             """Context matching function for the %noun macro in combination
             with 'af'"""
@@ -2489,22 +2478,22 @@
             return (lemma + "_" + case) in nouns
 
         NOUNS_AF: FrozenSet[str] = frozenset(
             ("beiðni_þgf", "siður_þgf", "tilefni_þgf", "fyrirmynd_þgf")
         )
         # The macro %noun is resolved by calling the function wrong_noun_af()
         # with the potentially matching tree node as an argument.
-        cls.ctx_noun_af = {"noun": partial(wrong_noun_af, NOUNS_AF)}
+        self.ctx_noun_af = {"noun": partial(wrong_noun_af, NOUNS_AF)}
         af_lemmas = set(n.split("_")[0] for n in NOUNS_AF)
-        cls.add_pattern(
+        self.add_pattern(
             (
                 af_lemmas,  # Trigger lemmas for this pattern
                 "PP > { P > { 'af' } NP > { %noun } }",
-                lambda self, match: self.wrong_af_use(match, cls.ctx_noun_af),
-                cls.ctx_noun_af,
+                lambda match: self.wrong_af_use(match, self.ctx_noun_af),
+                self.ctx_noun_af,
             )
         )
 
         NOUNS_AF_OBJ: FrozenSet[str] = frozenset(
             [
                 "aðgangur_þf",
                 "aðgangur_nf",
@@ -2523,38 +2512,38 @@
                 "uppskrift_nf",
                 "uppskrift_þf",
                 # "grín_þf"
             ]
         )
         # The macro %noun is resolved by calling the function wrong_noun_af()
         # with the potentially matching tree node as an argument.
-        cls.ctx_noun_af_obj = {"noun": partial(wrong_noun_af, NOUNS_AF_OBJ)}
+        self.ctx_noun_af_obj = {"noun": partial(wrong_noun_af, NOUNS_AF_OBJ)}
         af_lemmas = set(n.split("_")[0] for n in NOUNS_AF_OBJ)
-        cls.add_pattern(
+        self.add_pattern(
             (
                 af_lemmas,  # Trigger lemmas for this pattern
                 "NP > { %noun PP > { P > { 'af' } } }",
-                lambda self, match: self.wrong_af_use(match, cls.ctx_noun_af_obj),
-                cls.ctx_noun_af_obj,
+                lambda match: self.wrong_af_use(match, self.ctx_noun_af_obj),
+                self.ctx_noun_af_obj,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 af_lemmas,  # Trigger lemmas for this pattern
                 "VP > { VP >> { %noun } PP > { P > { 'af' } } }",
-                lambda self, match: self.wrong_af_use(match, cls.ctx_noun_af_obj),
-                cls.ctx_noun_af_obj,
+                lambda match: self.wrong_af_use(match, self.ctx_noun_af_obj),
+                self.ctx_noun_af_obj,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 af_lemmas,  # Trigger lemmas for this pattern
                 "VP > { PP > { NP > %noun } PP > { 'af' } }",
-                lambda self, match: self.wrong_af_use(match, cls.ctx_noun_af_obj),
-                cls.ctx_noun_af_obj,
+                lambda match: self.wrong_af_use(match, self.ctx_noun_af_obj),
+                self.ctx_noun_af_obj,
             )
         )
 
         def wrong_noun_að(nouns: Set[str], tree: SimpleTree) -> bool:
             """Context matching function for the %noun macro in combination
             with 'að'"""
             lemma = tree.own_lemma
@@ -2572,119 +2561,119 @@
             "togi_þgf",
             "kraftur_þgf",
             "hálfa_þgf",
             "hálfur_þgf",
         }
         # The macro %noun is resolved by calling the function wrong_noun_að()
         # with the potentially matching tree node as an argument.
-        cls.ctx_noun_að = {"noun": partial(wrong_noun_að, NOUNS_AÐ)}
+        self.ctx_noun_að = {"noun": partial(wrong_noun_að, NOUNS_AÐ)}
         að_lemmas = set(n.split("_")[0] for n in NOUNS_AÐ)
-        cls.add_pattern(
+        self.add_pattern(
             (
                 að_lemmas,  # Trigger lemma for this pattern
                 "PP > { P > { 'að' } NP > { %noun } }",
-                lambda self, match: self.wrong_að_use(match, cls.ctx_noun_að),
-                cls.ctx_noun_að,
+                lambda match: self.wrong_að_use(match, self.ctx_noun_að),
+                self.ctx_noun_að,
             )
         )
 
         def maybe_place(tree: SimpleTree) -> bool:
             """Context matching function for the %maybe_place macro.
             Returns True if the associated lemma is an uppercase
             word that might be a place name."""
             lemma = tree.lemma
             return lemma[0].isupper() if lemma else False
 
         # Check prepositions used with place names
-        cls.ctx_place_names = {"maybe_place": maybe_place}
-        cls.add_pattern(
+        self.ctx_place_names = {"maybe_place": maybe_place}
+        self.add_pattern(
             (
                 frozenset(("á", "í")),  # Trigger lemmas for this pattern
                 "PP > { P > ('á' | 'í') NP > %maybe_place }",
-                lambda self, match: self.check_pp_with_place(match),
-                cls.ctx_place_names,
+                lambda match: self.check_pp_with_place(match),
+                self.ctx_place_names,
             )
         )
         # Check use of 'bjóða e-m birginn' instead of 'bjóða e-m byrginn'
         # !!! TODO: This is a provisional placeholder for similar cases
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "birgir",  # Trigger lemma for this pattern
                 "VP > [ VP > { 'bjóða' } .* NP-IOBJ .* NP-OBJ > { \"birginn\" } ]",
-                cls.wrong_noun_with_verb,
+                self.wrong_noun_with_verb,
                 None,
             )
         )
         # Check use of "vera að" instead of a simple verb
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "vera",  # Trigger lemma for this pattern
                 "IP > {VP > [VP > { @'vera' } (ADVP|NP-SUBJ)? IP-INF > {TO > nhm}]}",
-                lambda self, match: self.vera_að(match),
+                lambda match: self.vera_að(match),
                 None,
             )
         )
 
         # Check mood in subclauses
 
         # Concessive clause - viðurkenningarsetning
-        cls.add_pattern(
+        self.add_pattern(
             (
                 frozenset(
                     ("þrátt fyrir", "þrátt", "þó", "þótt")
                 ),  # Trigger lemmas for this pattern
                 "CP-ADV-ACK > { IP >> {VP > so_fh} }",
-                lambda self, match: self.mood_ind("ACK", match),
+                lambda match: self.mood_ind("ACK", match),
                 None,
             )
         )
         # Relative clause - tilvísunarsetning
-        cls.add_pattern(
+        self.add_pattern(
             (
                 frozenset(("sem", "er")),  # Trigger lemmas for this pattern
                 "CP-REL > { IP >> {VP > so_vh} }",
-                lambda self, match: self.mood_sub("REL", match),
+                lambda match: self.mood_sub("REL", match),
                 None,
             )
         )
         # Temporal clause - tíðarsetning
-        cls.add_pattern(
+        self.add_pattern(
             (
                 frozenset(
                     ("áður", "eftir", "þangað", "þegar")
                 ),  # Trigger lemmas for this pattern
                 "CP-ADV-TEMP > { IP >> {VP > so_vh} }",
-                lambda self, match: self.mood_sub("TEMP/w", match),
+                lambda match: self.mood_sub("TEMP/w", match),
                 None,
             )
         )
         # Conditional clause - skilyrðissetning
-        cls.add_pattern(
+        self.add_pattern(
             (
                 frozenset(("ef", "svo")),  # Trigger lemmas for this pattern
                 "CP-ADV-COND > { IP >> {VP > so_vh} }",
-                lambda self, match: self.mood_sub("COND", match),
+                lambda match: self.mood_sub("COND", match),
                 None,
             )
         )
         # Purpose clause - tilgangssetning
-        cls.add_pattern(
+        self.add_pattern(
             (
                 frozenset(("til", "svo")),  # Trigger lemmas for this pattern
                 "CP-ADV-PURP > { IP >> {VP > so_fh} }",
-                lambda self, match: self.mood_ind("PURP", match),
+                lambda match: self.mood_ind("PURP", match),
                 None,
             )
         )
         # Article errors; demonstrative pronouns and nouns with an article
-        cls.add_pattern(
+        self.add_pattern(
             (
                 frozenset(("sá", "þessi")),  # Trigger lemmas for this pattern
                 "NP > [.* fn .* no_gr]",
-                lambda self, match: self.doubledefinite(match),
+                lambda match: self.doubledefinite(match),
                 None,
             )
         )
 
         # Check errors in dir4loc
         def dir4loc(verbs: FrozenSet[str], tree: SimpleTree) -> bool:
             """Context matching function for the %noun macro in combination
@@ -2694,379 +2683,379 @@
                 # The passed-in tree node is probably not a terminal
                 return False
             return lemma in verbs
 
         VERBS = frozenset(("safna", "kaupa", "læsa", "geyma"))
         # The macro %verb is resolved by calling the function dir4loc()
         # with the potentially matching tree node as an argument.
-        cls.ctx_dir_loc = {"verb": partial(dir4loc, VERBS)}
-        cls.add_pattern(
+        self.ctx_dir_loc = {"verb": partial(dir4loc, VERBS)}
+        self.add_pattern(
             (
                 "út",  # Trigger lemma for this pattern
                 "VP > { VP > { %verb } NP > { PP > { ADVP > { 'út' } P > { 'í' } NP > { 'búð' } } } }",
-                lambda self, match: self.dir_loc(match),
-                cls.ctx_dir_loc,
+                lambda match: self.dir_loc(match),
+                self.ctx_dir_loc,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "inn",  # Trigger lemma for this pattern
                 "VP > { VP > { %verb } ADVP > { 'saman' } PP > { ADVP > { 'inn' } P > { 'í' } NP } }",
-                lambda self, match: self.dir_loc(match),
-                cls.ctx_dir_loc,
+                lambda match: self.dir_loc(match),
+                self.ctx_dir_loc,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "inn",  # Trigger lemma for this pattern
                 "VP > { VP > { %verb } NP > { PP > { ADVP > { 'inn' } } } }",
-                lambda self, match: self.dir_loc(match),
-                cls.ctx_dir_loc,
+                lambda match: self.dir_loc(match),
+                self.ctx_dir_loc,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "inn",  # Trigger lemma for this pattern
                 "VP > { VP > { %verb } ADVP > { 'inn' } }",
-                lambda self, match: self.dir_loc(match),
-                cls.ctx_dir_loc,
+                lambda match: self.dir_loc(match),
+                self.ctx_dir_loc,
             )
         )
 
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "út",  # Trigger lemma for this pattern
                 "( PP|VP|IP ) > [ .* ADVP > { 'út' } PP > [ P > { ( 'í'|'á'|'um' ) } NP > ( no_þgf|pfn_þgf ) ] ]",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "út",  # Trigger lemma for this pattern
                 "( PP|VP|IP ) > [ .* VP > { 'hafa' } .* ADVP > { 'út' } PP > [ P > { ( 'í'|'á'|'um' ) } NP > ( no_þgf|pfn_þgf ) ] ]",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "út",  # Trigger lemma for this pattern
                 "NP > [ ( no_nf|pfn_nf ) PP > [ ADVP > { 'út' } PP > [ P > { ( 'í'|'á'|'um' ) } NP > ( no_þgf|pfn_þgf ) ] ] ]",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "út",  # Trigger lemma for this pattern
                 "( IP|NP|VP ) > { IP >> [ .* ADVP > { 'út' } ] PP > [ P > { ( 'í'|'á'|'um' ) } NP > ( no_þgf|pfn_þgf ) ] }",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "út",  # Trigger lemma for this pattern
                 "VP > [ .* VP > { VP > [ 'vera' ] IP >> { ADVP > [ 'út' ] } } .* PP > [ P > [ 'á' ] NP > { ( no_þgf|pfn_þgf ) } ] .* ]",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "út",  # Trigger lemma for this pattern
                 "VP > [ VP > [ 'gera' ] NP > [ .* PP > { ADVP > { 'út' } P > [ 'í' ] NP } ] ]",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "útá",  # Trigger lemma for this pattern
                 "PP > { P > { 'útá' } NP > { ( no_þgf|pfn_þgf ) } }",
-                lambda self, match: self.dir_loc_comp(match),
+                lambda match: self.dir_loc_comp(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "útí",  # Trigger lemma for this pattern
                 "PP > { P > { 'útí' } NP > { ( no_þgf|pfn_þgf ) } }",
-                lambda self, match: self.dir_loc_comp(match),
+                lambda match: self.dir_loc_comp(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "inn",  # Trigger lemma for this pattern
                 "( PP|VP|IP ) > [ .* ADVP > { 'inn' } PP > { P > { ( 'í'|'á' ) } NP > { ( no_þgf|pfn_þgf ) } } .* ]",
                 #    "( PP|VP|IP ) > [ .* ADVP > { 'inn' } .* PP > { P > { ( 'í'|'á' ) } NP > { ( no_þgf|pfn_þgf ) } } .* ]",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "inn",  # Trigger lemma for this pattern
                 "( IP|NP|VP ) > { IP >> [ .* ADVP > { 'inn' } ] PP > [ P > { ( 'í'|'á' ) } NP > ( no_þgf|pfn_þgf ) ] }",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "inn",  # Trigger lemma for this pattern
                 "NP > { IP >> { VP > { 'vera' } ADVP > { 'inn' } } PP > [ P > { ( 'í'|'á' ) } NP > ( no_þgf|pfn_þgf ) ] }",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "inn",  # Trigger lemma for this pattern
                 "VP > { VP > { 'verða' } ADVP > { 'inn' } PP > [ P > { ( 'í'|'á' ) } NP > ( no_þgf|pfn_þgf ) ] }",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "geyma",  # Trigger lemma for this pattern
                 "VP > { VP > { 'geyma' } ADVP > { 'inn' } PP }",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "inná",  # Trigger lemma for this pattern
                 "PP > { P > { 'inná' } NP > { ( no_þgf|pfn_þgf ) } }",
-                lambda self, match: self.dir_loc_comp(match),
+                lambda match: self.dir_loc_comp(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "inní",  # Trigger lemma for this pattern
                 "VP > { VP > [ .* ] NP > { PP > { P > { 'inní' } NP > { ( no_þgf|pfn_þgf ) } } } }",
                 # "PP > { P > { 'inní' } NP > { ( no_þgf|pfn_þgf ) } }",
-                lambda self, match: self.dir_loc_comp(match),
+                lambda match: self.dir_loc_comp(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "inn",  # Trigger lemma for this pattern
                 "VP > [ VP > { ( 'verða'|'vera' ) } .* ADVP > { 'inn' } PP > { P > { 'á' } } ]",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "inn",  # Trigger lemma for this pattern
                 "VP > [ VP > { 'vera' } .* ADVP > { 'inn' } PP > { P > { 'í' } } ]",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
         # Catches "Ég hef upp á honum."
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "upp",  # Trigger lemma for this pattern
                 "( PP|VP|IP ) > [ VP > { ('standa'|'hafa') } .* ADVP > { 'upp' } PP > { P > { ( 'í'|'á' ) } NP > { ( no_þgf|pfn_þgf ) } } ]",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
         # Catches "Það liggur í augum upp."
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "auga",  # Trigger lemma for this pattern
                 "VP > [ VP > [ 'liggja' ] PP > [ P > { ( 'í'|'á' ) } NP > { 'auga' } ] ADVP > [ 'upp' ] ]",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "teningur",  # Trigger lemma for this pattern
                 "PP > [ .* ADVP > { 'upp' } PP > { P > { ( 'í'|'á' ) } NP > { 'teningur' } } ]",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "upp",  # Trigger lemma for this pattern
                 "( IP|NP|VP ) > [ IP >> { ADVP > { 'upp' } } PP > [ P > { ( 'í'|'á' ) } NP > ( no_þgf|pfn_þgf ) ] ]",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
 
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "upp",  # Trigger lemma for this pattern
                 "VP > [ VP >> { VP > { VP > { 'hafa' } ADVP > { 'upp' } } } PP > [ P > { ( 'í'|'á' ) } NP > ( no_þgf|pfn_þgf ) ] .* ]",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "uppá",  # Trigger lemma for this pattern
                 "VP > { VP > { 'taka' } NP > { PP > { P > { 'uppá' } NP > { ( no_þgf|pfn_þgf|no_þf|pfn_þf ) } } } }",
-                lambda self, match: self.dir_loc_comp(match),
+                lambda match: self.dir_loc_comp(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "uppí",  # Trigger lemma for this pattern
                 "PP > { P > { 'uppí' } NP > { ( no_þgf|pfn_þgf ) } }",
-                lambda self, match: self.dir_loc_comp(match),
+                lambda match: self.dir_loc_comp(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "uppí",  # Trigger lemma for this pattern
                 "VP > { VP > { 'vera' } PP > { P > { 'uppí' } NP > { ( no_þf|pfn_þf ) } } }",
-                lambda self, match: self.dir_loc_comp(match),
+                lambda match: self.dir_loc_comp(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "niður",  # Trigger lemma for this pattern
                 "( PP|VP|IP ) > [ .* ADVP > { 'niður' } PP > { P > { ( 'í'|'á' ) } NP > ( no_þgf|pfn_þgf ) } ]",
-                lambda self, match: self.dir_loc_simple(match),
+                lambda match: self.dir_loc_simple(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "niður",  # Trigger lemma for this pattern
                 "VP > [ VP > { 'vera' } .* PP > { ADVP > { 'niður' } P > { 'í' } NP } ]",
-                lambda self, match: self.dir_loc_simple(match),
+                lambda match: self.dir_loc_simple(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "verða",  # Trigger lemma for this pattern
                 "VP > { VP > { 'verða' } NP > { ( pfn_þgf|abfn_þgf ) } NP > { 'út' 'um' } }",
-                lambda self, match: self.dir_loc_ut_um(match),
+                lambda match: self.dir_loc_ut_um(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "standa",  # Trigger lemma for this pattern
                 "IP > { ADVP > { 'upp' } VP > { VP > { 'vera' } NP > { 'standa' } } }",
-                lambda self, match: self.dir_loc_simple(match),
+                lambda match: self.dir_loc_simple(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "út",  # Trigger lemma for this pattern
                 "VP > { VP > [ 'vera' ] NP > { PP > { ADVP > { 'út' } PP > { P > { 'um' } NP } } } }",
-                lambda self, match: self.dir_loc_simple(match),
+                lambda match: self.dir_loc_simple(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "út",  # Trigger lemma for this pattern
                 "VP > { VP > [ 'vera' ] NP > [ .* PP > { ADVP > { 'út' } PP > { P > { 'um' } NP } } ] }",
-                lambda self, match: self.dir_loc_ut_um(match),
+                lambda match: self.dir_loc_ut_um(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "út",  # Trigger lemma for this pattern
                 "VP > { VP PP >> { NP > { PP > { ADVP > { 'út' } PP > { P > { 'um' } NP } } } } }",
-                lambda self, match: self.dir_loc_ut_um(match),
+                lambda match: self.dir_loc_ut_um(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "út",  # Trigger lemma for this pattern
                 "VP > { VP > [ 'vera' ] ADVP > [ 'út' ] PP > { P > [ 'um' ] } }",
-                lambda self, match: self.dir_loc_ut_um(match),
+                lambda match: self.dir_loc_ut_um(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "út",  # Trigger lemma for this pattern
                 "VP > { VP > [ 'vera' .* ] NP > { 'út' 'um' } }",
-                lambda self, match: self.dir_loc_ut_um(match),
+                lambda match: self.dir_loc_ut_um(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "útum",  # Trigger lemma for this pattern
                 "VP > { VP > { 'vera' } NP > { 'útum' } }",
-                lambda self, match: self.dir_loc_ut_um(match),
+                lambda match: self.dir_loc_ut_um(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "útum",  # Trigger lemma for this pattern
                 "VP > { VP > { 'sækja' } PP > { 'um' } NP > { 'útum' } }",
-                lambda self, match: self.dir_loc_ut_um(match),
+                lambda match: self.dir_loc_ut_um(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "út",  # Trigger lemma for this pattern
                 "VP > { VP > [ 'vera' .* ] ADVP > { 'út' } PP > { P > { 'um' } NP } }",
-                lambda self, match: self.dir_loc_ut_um(match),
+                lambda match: self.dir_loc_ut_um(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "út",  # Trigger lemma for this pattern
                 "VP > { VP > { 'gera' } NP > [ .* PP > { ADVP > { 'út' } P > { 'í' } } ] }",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "inn",  # Trigger lemma for this pattern
                 "VP > { VP >> { ADVP > { 'hér' } } PP > { ADVP > { 'inn' } } }",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "Skagi",  # Trigger lemma for this pattern
                 "VP > { VP > { 'vera' } PP >> { PP > { ADVP > { 'upp' } P > { 'á' } NP > { 'Skagi' } } } }",
-                lambda self, match: self.dir_loc(match),
+                lambda match: self.dir_loc(match),
                 None,
             )
         )
 
-        cls.add_pattern(
+        self.add_pattern(
             (
                 "né",  # Trigger lemma for this pattern
                 " IP >> { 'né' } ",
-                lambda self, match: self.né(match),
+                lambda match: self.né(match),
                 None,
             )
         )
 
         def subjsing(nouns: FrozenSet[str], tree: SimpleTree) -> bool:
             """Context matching function for the %noun macro"""
             if not tree.is_terminal:
@@ -3078,38 +3067,38 @@
                 # The passed-in tree node is probably not a terminal
                 return False
             return lemma in nouns
 
         NOUNS_NUM = frozenset(("þríeyki", "tvíeyki", "hluti", "hópur"))
         # The macro %noun is resolved by calling the function subjnum()
         # with the potentially matching tree node as an argument.
-        cls.ctx_subjsing = {"noun": partial(subjsing, NOUNS_NUM)}
+        self.ctx_subjsing = {"noun": partial(subjsing, NOUNS_NUM)}
 
-        cls.add_pattern(
+        self.add_pattern(
             (
                 NOUNS_NUM,  # Trigger lemmas for this pattern
                 "NP-SUBJ >> [ %noun .* 'og' ]",
-                lambda self, match: self.singsub("QUANT", match),
-                cls.ctx_subjsing,
+                lambda match: self.singsub("QUANT", match),
+                self.ctx_subjsing,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 NOUNS_NUM,  # Trigger lemmas for this pattern
                 "NP-SUBJ >> [ %noun .* NP-POSS >> { no_ft_ef } ]",
-                lambda self, match: self.singsub("GEN", match),
-                cls.ctx_subjsing,
+                lambda match: self.singsub("GEN", match),
+                self.ctx_subjsing,
             )
         )
-        cls.add_pattern(
+        self.add_pattern(
             (
                 NOUNS_NUM,
                 "NP-SUBJ >> [ %noun .* PP >> [ no_ft_ef  ]]",
-                lambda self, match: self.singsub("AF", match),
-                cls.ctx_subjsing,
+                lambda match: self.singsub("AF", match),
+                self.ctx_subjsing,
             )
         )
 
     def run(self) -> None:
         """Apply the patterns to the sentence"""
         tree = None if self._sent is None else self._sent.tree
         if tree is None:
@@ -3134,8 +3123,8 @@
 
         for trigger, pattern, func, context in self.PATTERNS:
             # We only do the expensive pattern matching if the trigger lemma
             # for a pattern rule (if given) is actually found in the sentence
             if lemma_match(trigger):
                 for match in tree.all_matches(pattern, context):
                     # Call the annotation function for this match
-                    func(self, match)
+                    func(match)
```

### Comparing `reynir-correct-3.4.6/src/reynir_correct/resources/iceloc_prep.json` & `reynir-correct-3.4.7/src/reynir_correct/resources/iceloc_prep.json`

 * *Files identical despite different names*

### Comparing `reynir-correct-3.4.6/src/reynir_correct/resources/nonwords.csv` & `reynir-correct-3.4.7/src/reynir_correct/resources/nonwords.csv`

 * *Files identical despite different names*

### Comparing `reynir-correct-3.4.6/src/reynir_correct/settings.py` & `reynir-correct-3.4.7/src/reynir_correct/settings.py`

 * *Files 8% similar despite different names*

```diff
@@ -46,14 +46,15 @@
 import threading
 
 from collections import defaultdict
 
 from reynir.basics import ConfigError, LineReader
 from reynir.bindb import GreynirBin
 from reynir.bintokenizer import StateDict
+import importlib.util
 
 
 ErrorFormTuple = Tuple[str, str, int, str, str]
 # (lemma, id, cat, correct_word_form, tag, eink, malsnid, stafs, aslatt, beyg)
 RitmyndirTuple = Tuple[str, int, str, str, str, int, str, str, str, str]
 # (ritregla/spelling rule, category, other detail ) }
 DetailsTuple = Tuple[str, str, str]
@@ -67,594 +68,611 @@
     3: "R003",
     4: "R004",
     5: "R005",
 }
 
 
 class AllowedMultiples:
+    def __init__(self) -> None:
+        self.SET: Set[str] = set()
 
-    # Set of word forms allowed to appear more than once in a row
-    SET: Set[str] = set()
-
-    @staticmethod
-    def add(word: str) -> None:
-        AllowedMultiples.SET.add(word)
+    def add(self, word: str) -> None:
+        self.SET.add(word)
 
 
 class WrongCompounds:
+    def __init__(self) -> None:
+        # Dictionary structure: dict { wrong_compound : "right phrase" }
+        self.DICT: Dict[str, Tuple[str, ...]] = {}
 
-    # Dictionary structure: dict { wrong_compound : "right phrase" }
-    DICT: Dict[str, Tuple[str, ...]] = {}
-
-    @staticmethod
-    def add(word: str, parts: Tuple[str, ...]) -> None:
-        if word in WrongCompounds.DICT:
+    def add(self, word: str, parts: Tuple[str, ...]) -> None:
+        if word in self.DICT:
             raise ConfigError(
                 "Multiple definition of '{0}' in wrong_compounds section".format(word)
             )
         assert isinstance(parts, tuple)
-        WrongCompounds.DICT[word] = parts
+        self.DICT[word] = parts
 
 
 class SplitCompounds:
 
     # Dict of the form { first_part : set(second_part_stem) }
-    DICT: Dict[str, Set[str]] = defaultdict(set)
+    def __init__(self) -> None:
+        self.DICT: Dict[str, Set[str]] = defaultdict(set)
 
-    @staticmethod
-    def add(first_part: str, second_part_stem: str) -> None:
-        if (
-            first_part in SplitCompounds.DICT
-            and second_part_stem in SplitCompounds.DICT[first_part]
-        ):
+    def add(self, first_part: str, second_part_stem: str) -> None:
+        if first_part in self.DICT and second_part_stem in self.DICT[first_part]:
             raise ConfigError(
                 "Multiple definition of '{0}' in split_compounds section".format(
                     first_part + " " + second_part_stem
                 )
             )
-        SplitCompounds.DICT[first_part].add(second_part_stem)
+        self.DICT[first_part].add(second_part_stem)
 
 
 class UniqueErrors:
 
     # Dictionary structure: dict { wrong_word : (tuple of right words) }
-    DICT: Dict[str, Tuple[str, ...]] = dict()
+    def __init__(self) -> None:
+        self.DICT: Dict[str, Tuple[str, ...]] = dict()
 
-    @staticmethod
-    def add(word: str, corr: Tuple[str, ...]) -> None:
-        if word in UniqueErrors.DICT:
+    def add(self, word: str, corr: Tuple[str, ...]) -> None:
+        if word in self.DICT:
             raise ConfigError(
                 "Multiple definition of '{0}' in unique_errors section".format(word)
             )
-        UniqueErrors.DICT[word] = corr
+        self.DICT[word] = corr
 
 
 class MultiwordErrors:
+    def __init__(self) -> None:
+        # Dictionary structure: dict { phrase tuple: error specification }
+        # List of tuples of multiword error phrases and their word category lists
+        self.LIST: List[Tuple[Tuple[str, ...], str, List[str]]] = []
+        # Parsing dictionary keyed by first word of phrase
+        self.DICT: StateDict = defaultdict(list)
+        # Error dictionary, { phrase : (error_code, right_phrase, right_parts_of_speech) }
+        self.ERROR_DICT: Dict[Tuple[str, ...], str] = dict()
 
-    # Dictionary structure: dict { phrase tuple: error specification }
-    # List of tuples of multiword error phrases and their word category lists
-    LIST: List[Tuple[Tuple[str, ...], str, List[str]]] = []
-    # Parsing dictionary keyed by first word of phrase
-    DICT: StateDict = defaultdict(list)
-    # Error dictionary, { phrase : (error_code, right_phrase, right_parts_of_speech) }
-    ERROR_DICT: Dict[Tuple[str, ...], str] = dict()
-
-    @staticmethod
-    def add(words: Tuple[str, ...], error: str) -> None:
-        if words in MultiwordErrors.ERROR_DICT:
+    def add(self, words: Tuple[str, ...], error: str) -> None:
+        if words in self.ERROR_DICT:
             raise ConfigError(
                 "Multiple definition of '{0}' in multiword_errors section".format(
                     " ".join(words)
                 )
             )
-        MultiwordErrors.ERROR_DICT[words] = error
+        self.ERROR_DICT[words] = error
 
         # Add to phrase list
-        ix = len(MultiwordErrors.LIST)
+        ix = len(self.LIST)
 
         a = error.split(",")
         if len(a) != 2:
             raise ConfigError("Expected two comma-separated parameters within $error()")
         code = a[0].strip()
         replacement = a[1].strip().split()
 
         # Append the phrase and the error specification in tuple form
-        MultiwordErrors.LIST.append((words, code, replacement))
+        self.LIST.append((words, code, replacement))
 
         # Dictionary structure: dict { firstword: [ (restword_list, phrase_index) ] }
-        MultiwordErrors.DICT[words[0]].append((list(words[1:]), ix))
+        self.DICT[words[0]].append((list(words[1:]), ix))
 
-    @staticmethod
-    def get_phrase(ix: int) -> Tuple[str, ...]:
+    def get_phrase(self, ix: int) -> Tuple[str, ...]:
         """Return the original phrase with index ix"""
-        return MultiwordErrors.LIST[ix][0]
+        return self.LIST[ix][0]
 
-    @staticmethod
-    def get_phrase_length(ix: int) -> int:
+    def get_phrase_length(self, ix: int) -> int:
         """Return the count of words in the original phrase with index ix"""
-        return len(MultiwordErrors.LIST[ix][0])
+        return len(self.LIST[ix][0])
 
-    @staticmethod
-    def get_code(ix: int) -> str:
+    def get_code(self, ix: int) -> str:
         """Return the error code with index ix"""
-        return MultiwordErrors.LIST[ix][1]
+        return self.LIST[ix][1]
 
-    @staticmethod
-    def get_replacement(ix: int) -> List[str]:
+    def get_replacement(self, ix: int) -> List[str]:
         """Return the replacement phrase with index ix"""
-        return MultiwordErrors.LIST[ix][2]
+        return self.LIST[ix][2]
 
 
 class TabooWords:
+    def __init__(self) -> None:
+        # Dictionary structure: dict { taboo_word : (suggested_replacement, explanation) }
+        self.DICT: Dict[str, Tuple[str, str]] = {}
 
-    # Dictionary structure: dict { taboo_word : (suggested_replacement, explanation) }
-    DICT: Dict[str, Tuple[str, str]] = {}
-
-    @staticmethod
-    def add(word: str, replacement: str, explanation: str) -> None:
-        if word in TabooWords.DICT:
+    def add(self, word: str, replacement: str, explanation: str) -> None:
+        if word in self.DICT:
             raise ConfigError(
                 "Multiple definition of '{0}' in taboo_words section".format(word)
             )
         db = GreynirBin.get_db()
         a = word.split("_")
         _, m = db.lookup_g(a[0])
         if not m or (len(a) >= 2 and all(mm.ordfl != a[1] for mm in m)):
             raise ConfigError("The taboo word '{0}' is not found in BÍN".format(word))
-        TabooWords.DICT[word] = (replacement, explanation)
+        self.DICT[word] = (replacement, explanation)
 
 
-class Suggestions:
+class ToneOfVoiceWords:
+    def __init__(self) -> None:
+        # Dictionary structure: dict { tone_of_voice : (suggested_replacement, explanation) }
+        self.DICT: Dict[str, Tuple[str, str]] = {}
+
+    def add(self, word: str, replacement: str, explanation: str) -> None:
+        if word in self.DICT:
+            raise ConfigError(
+                "Multiple definition of '{0}' in tone_of_voice section".format(word)
+            )
+        db = GreynirBin.get_db()
+        a = word.split("_")
+        _, m = db.lookup_g(a[0])
+        if not m or (len(a) >= 2 and all(mm.ordfl != a[1] for mm in m)):
+            raise ConfigError("The word '{0}' is not found in BÍN".format(word))
+        self.DICT[word] = (replacement, explanation)
+
 
-    # Dictionary structure: dict { bad_word : [ suggested_replacements ] }
-    DICT: Dict[str, List[str]] = {}
+class ToneOfVoicePatterns:
+    def __init__(self) -> None:
+        # A path to a python module containing third party tone of voice patterns
+        self.PATH: str = ""
 
-    @staticmethod
-    def add(word: str, replacements: List[str]) -> None:
-        if word in Suggestions.DICT:
+    def add(self, fpath: str) -> None:
+        self.PATH = fpath
+
+
+class Suggestions:
+    def __init__(self) -> None:
+        # Dictionary structure: dict { bad_word : [ suggested_replacements ] }
+        self.DICT: Dict[str, List[str]] = {}
+
+    def add(self, word: str, replacements: List[str]) -> None:
+        if word in self.DICT:
             raise ConfigError(
                 "Multiple definition of '{0}' in suggestions section".format(word)
             )
-        Suggestions.DICT[word] = replacements
+        self.DICT[word] = replacements
 
 
 class CapitalizationErrors:
+    def __init__(self) -> None:
+        # Set of wrongly capitalized words
+        self.SET: Set[str] = set()
+        # Reverse capitalization (íslendingur -> Íslendingur, Danskur -> danskur)
+        self.SET_REV: Set[str] = set()
 
-    # Set of wrongly capitalized words
-    SET: Set[str] = set()
-    # Reverse capitalization (íslendingur -> Íslendingur, Danskur -> danskur)
-    SET_REV: Set[str] = set()
-
-    @staticmethod
-    def emulate_case(s: str, template: str) -> str:
+    def emulate_case(self, s: str, template: str) -> str:
         """Return the string s but emulating the case of the template
         (lower/upper/capitalized)"""
         if template.isupper():
             return s.upper()
         if template and template[0].isupper():
             return s.capitalize()
         return s
 
-    @staticmethod
-    def reverse_capitalization(word: str, *, split_on_hyphen: bool = False) -> str:
+    def reverse_capitalization(
+        self, word: str, *, split_on_hyphen: bool = False
+    ) -> str:
         """Return a word with its capitalization reversed (lower <-> upper case)"""
         if split_on_hyphen and "-" in word:
             # 'norður-kórea' -> 'Norður-Kórea'
             return "-".join(
-                CapitalizationErrors.reverse_capitalization(part)
-                for part in word.split("-")
+                self.reverse_capitalization(part) for part in word.split("-")
             )
         if word.islower():
             # Lowercase word
             word_rev = word.capitalize()
         elif word.isupper() and len(word) > 1:
             # Multi-letter uppercase acronym
             word_rev = word.capitalize()
         elif word[0].isupper() and word[1:].islower():
             # Uppercase word
             word_rev = word.lower()
         else:
             raise ConfigError("'{0}' cannot have mixed capitalization".format(word))
         return word_rev
 
-    @staticmethod
-    def add(word: str) -> None:
+    def add(self, word: str) -> None:
         """Add the given (wrongly capitalized) word stem to the stem set"""
         # We support compound words such as 'félags- og barnamálaráðherra' here
         split_on_hyphen = False
         if " " in word:
             prefix, suffix = word.rsplit(" ", maxsplit=1)
             prefix += " "
         else:
             prefix, suffix = "", word
             # Split_on_hyphen is True for e.g. 'norður-kórea' and 'nýja-sjáland'
             split_on_hyphen = "-" in word
         db = GreynirBin().get_db()
         # The suffix may not be in BÍN except as a compound, and in that
         # case we want its hyphenated lemma
-        suffix_rev = CapitalizationErrors.reverse_capitalization(
+        suffix_rev = self.reverse_capitalization(
             suffix, split_on_hyphen=split_on_hyphen
         )
         _, m = db.lookup_g(suffix_rev)
         # Only consider lemmas
         m = [mm for mm in m if mm.stofn == mm.ordmynd]
         if not m:
             raise ConfigError(
                 "No BÍN meaning for '{0}' (from error word '{1}') in capitalization_errors section".format(
                     suffix_rev, word
                 )
             )
         if not prefix:
             # This might be something like 'barnamálaráðherra' which comes out
             # with a lemma of 'barnamála-ráðherra'
-            word = CapitalizationErrors.emulate_case(m[0].stofn, template=word)
+            word = self.emulate_case(m[0].stofn, template=word)
         else:
             # This might be something like 'félags- og barnamálaráðherra' which comes out
             # with a lemma of 'félags- og barnamála-ráðherra'
             word = prefix + m[0].stofn
-        if word in CapitalizationErrors.SET:
+        if word in self.SET:
             raise ConfigError(
                 "Multiple definition of '{0}' in capitalization_errors section".format(
                     word
                 )
             )
         # Construct the reverse casing of the word
-        word_rev = CapitalizationErrors.reverse_capitalization(
-            word, split_on_hyphen=split_on_hyphen
-        )
+        word_rev = self.reverse_capitalization(word, split_on_hyphen=split_on_hyphen)
         # Add the word and its reverse case to the set of errors
-        CapitalizationErrors.SET.add(word)
-        CapitalizationErrors.SET_REV.add(word_rev)
+        self.SET.add(word)
+        self.SET_REV.add(word_rev)
 
 
 class OwForms:
+    def __init__(self) -> None:
+        # dict { wrong_word_form : (lemma, correct_word_form, id, cat, tag) }
+        self.DICT: Dict[str, Tuple[str, str, int, str, str]] = dict()
 
-    # dict { wrong_word_form : (lemma, correct_word_form, id, cat, tag) }
-    DICT: Dict[str, Tuple[str, str, int, str, str]] = dict()
-
-    @staticmethod
-    def contains(word: str) -> bool:
+    def contains(self, word: str) -> bool:
         """Check whether the word form is in the error forms dictionary,
         either in its original casing or in a lower case form"""
-        d = OwForms.DICT
+        d = self.DICT
         if word.islower():
             return word in d
         return word in d or word.lower() in d
 
-    @staticmethod
-    def add(wrong_form: str, meaning: Tuple[str, str, int, str, str]) -> None:
-        OwForms.DICT[wrong_form] = meaning
-
-    @staticmethod
-    def get_lemma(wrong_form: str) -> str:
-        return OwForms.DICT[wrong_form][0]
+    def add(self, wrong_form: str, meaning: Tuple[str, str, int, str, str]) -> None:
+        self.DICT[wrong_form] = meaning
+
+    def get_lemma(self, wrong_form: str) -> str:
+        return self.DICT[wrong_form][0]
 
-    @staticmethod
-    def get_correct_form(wrong_form: str) -> str:
+    def get_correct_form(self, wrong_form: str) -> str:
         """Return a corrected form of the given word, attempting
         to emulate the lower/upper/title case of the word"""
         # First, try the original casing of the wrong form
-        c = OwForms.DICT.get(wrong_form)
+        c = self.DICT.get(wrong_form)
         if c is not None:
             # Found it: we're done
             return c[1]
         # Lookup a lower case version
-        c = OwForms.DICT.get(wrong_form.lower())
+        c = self.DICT.get(wrong_form.lower())
         if c is None:
             # Not found: can't correct
             return wrong_form
         form = c[1]
         if wrong_form.istitle():
             return form.title()
         if wrong_form.isupper():
             return form.upper()
         return form
 
-    @staticmethod
-    def get_id(wrong_form: str) -> int:
-        return OwForms.DICT[wrong_form][2]
-
-    @staticmethod
-    def get_category(wrong_form: str) -> str:
-        return OwForms.DICT[wrong_form][3]
-
-    @staticmethod
-    def get_tag(wrong_form: str) -> str:
-        return OwForms.DICT[wrong_form][4]
+    def get_id(self, wrong_form: str) -> int:
+        return self.DICT[wrong_form][2]
 
+    def get_category(self, wrong_form: str) -> str:
+        return self.DICT[wrong_form][3]
 
-class CIDErrorForms:
+    def get_tag(self, wrong_form: str) -> str:
+        return self.DICT[wrong_form][4]
 
-    # dict { wrong_word_form : (lemma, correct_word_form, id, cat, tag) }
-    DICT: Dict[str, ErrorFormTuple] = dict()
 
-    @staticmethod
-    def contains(word: str) -> bool:
+class CIDErrorForms:
+    def __init__(self) -> None:
+        # dict { wrong_word_form : (lemma, correct_word_form, id, cat, tag) }
+        self.DICT: Dict[str, ErrorFormTuple] = dict()
+
+    def contains(self, word: str) -> bool:
         """Check whether the word form is in the error forms dictionary,
         either in its original casing or in a lower case form"""
-        d = CIDErrorForms.DICT
+        d = self.DICT
         return word in d or word.lower() in d
 
-    @staticmethod
-    def add(wrong_form: str, meaning: ErrorFormTuple) -> None:
-        CIDErrorForms.DICT[wrong_form] = meaning
-
-    @staticmethod
-    def get_lemma(wrong_form: str) -> str:
-        return CIDErrorForms.DICT[wrong_form][0]
+    def add(self, wrong_form: str, meaning: ErrorFormTuple) -> None:
+        self.DICT[wrong_form] = meaning
+
+    def get_lemma(self, wrong_form: str) -> str:
+        return self.DICT[wrong_form][0]
 
-    @staticmethod
-    def get_correct_form(wrong_form: str) -> str:
+    def get_correct_form(self, wrong_form: str) -> str:
         """Return a corrected form of the given word, attempting
         to emulate the lower/upper/title case of the word"""
         # First, try the original casing of the wrong form
-        c = CIDErrorForms.DICT.get(wrong_form)
+        c = self.DICT.get(wrong_form)
         if c is not None:
             # Found it: we're done
             return c[1]
         # Lookup a lower case version
-        c = CIDErrorForms.DICT.get(wrong_form.lower())
+        c = self.DICT.get(wrong_form.lower())
         if c is None:
             # Not found: can't correct
             return wrong_form
         form = c[1]
         if wrong_form.istitle():
             return form.title()
         if wrong_form.isupper():
             return form.upper()
         return form
 
-    @staticmethod
-    def get_id(wrong_form: str) -> int:
-        return CIDErrorForms.DICT[wrong_form][2]
-
-    @staticmethod
-    def get_category(wrong_form: str) -> str:
-        return CIDErrorForms.DICT[wrong_form][3]
-
-    @staticmethod
-    def get_tag(wrong_form: str) -> str:
-        return CIDErrorForms.DICT[wrong_form][4]
+    def get_id(self, wrong_form: str) -> int:
+        return self.DICT[wrong_form][2]
 
+    def get_category(self, wrong_form: str) -> str:
+        return self.DICT[wrong_form][3]
+
+    def get_tag(self, wrong_form: str) -> str:
+        return self.DICT[wrong_form][4]
 
-class CDErrorForms:
 
-    # dict { wrong_word_form : (lemma, correct_word_form, id, cat, tag) }
-    DICT: Dict[str, ErrorFormTuple] = dict()
+class CDErrorForms:
+    def __init__(self) -> None:
+        # dict { wrong_word_form : (lemma, correct_word_form, id, cat, tag) }
+        self.DICT: Dict[str, ErrorFormTuple] = dict()
 
-    @staticmethod
-    def contains(word: str) -> bool:
+    def contains(self, word: str) -> bool:
         """Check whether the word form is in the error forms dictionary,
         either in its original casing or in a lower case form"""
-        d = CDErrorForms.DICT
+        d = self.DICT
         if word.islower():
             return word in d
         return word in d or word.lower() in d
 
-    @staticmethod
-    def add(wrong_form: str, meaning: ErrorFormTuple) -> None:
-        CDErrorForms.DICT[wrong_form] = meaning
-
-    @staticmethod
-    def get_lemma(wrong_form: str) -> str:
-        return CDErrorForms.DICT[wrong_form][0]
+    def add(self, wrong_form: str, meaning: ErrorFormTuple) -> None:
+        self.DICT[wrong_form] = meaning
 
-    @staticmethod
-    def get_correct_form(wrong_form: str) -> str:
+    def get_lemma(self, wrong_form: str) -> str:
+        return self.DICT[wrong_form][0]
+
+    def get_correct_form(self, wrong_form: str) -> str:
         """Return a corrected form of the given word, attempting
         to emulate the lower/upper/title case of the word"""
         # First, try the original casing of the wrong form
-        c = CDErrorForms.DICT.get(wrong_form)
+        c = self.DICT.get(wrong_form)
         if c is not None:
             # Found it: we're done
             return c[1]
         # Lookup a lower case version
-        c = CDErrorForms.DICT.get(wrong_form.lower())
+        c = self.DICT.get(wrong_form.lower())
         if c is None:
             # Not found: can't correct
             return wrong_form
         form = c[1]
         if wrong_form.istitle():
             return form.title()
         if wrong_form.isupper():
             return form.upper()
         return form
 
-    @staticmethod
-    def get_id(wrong_form: str) -> int:
-        return CDErrorForms.DICT[wrong_form][2]
-
-    @staticmethod
-    def get_category(wrong_form: str) -> str:
-        return CDErrorForms.DICT[wrong_form][3]
-
-    @staticmethod
-    def get_tag(wrong_form: str) -> str:
-        return CDErrorForms.DICT[wrong_form][4]
+    def get_id(self, wrong_form: str) -> int:
+        return self.DICT[wrong_form][2]
 
+    def get_category(self, wrong_form: str) -> str:
+        return self.DICT[wrong_form][3]
+
+    def get_tag(self, wrong_form: str) -> str:
+        return self.DICT[wrong_form][4]
 
-class Morphemes:
 
-    # dict { morpheme : [ preferred PoS ] }
-    BOUND_DICT: Dict[str, List[str]] = {}
-    # dict { morpheme : [ excluded PoS ] }
-    FREE_DICT: Dict[str, List[str]] = {}
+class Morphemes:
+    def __init__(self) -> None:
+        # dict { morpheme : [ preferred PoS ] }
+        self.BOUND_DICT: Dict[str, List[str]] = {}
+        # dict { morpheme : [ excluded PoS ] }
+        self.FREE_DICT: Dict[str, List[str]] = {}
 
-    @staticmethod
-    def add(morph: str, boundlist: List[str], freelist: List[str]) -> None:
+    def add(self, morph: str, boundlist: List[str], freelist: List[str]) -> None:
         if not boundlist:
             raise ConfigError("A definition of allowed PoS is necessary with morphemes")
-        Morphemes.BOUND_DICT[morph] = boundlist
+        self.BOUND_DICT[morph] = boundlist
         # The freelist may be empty
-        Morphemes.FREE_DICT[morph] = freelist
+        self.FREE_DICT[morph] = freelist
 
 
 class Ritmyndir:
 
     # dict { wrong_word_form : (lemma, id, cat, correct_word_form, tag, eink, malsnid, stafs, aslatt, beyg) }
     # þurrð;10963;kvk;þurðar;þurrðar;EFET;0;URE;;;;1745-1745;KLIM
     # þurrka;425063;so;þurkaði;þurrkaði;;4;VILLA;R4RR;;;;SKOLAVERK
-    DICT: Dict[str, RitmyndirTuple] = dict()
+    def __init__(self):
+        self.DICT: Dict[str, RitmyndirTuple] = dict()
 
-    @staticmethod
-    def contains(word: str) -> bool:
+    def contains(self, word: str) -> bool:
         """Check whether the word form is in the Ritmyndir dictionary"""
-        d = Ritmyndir.DICT
-        return word in d or word.lower() in d
+        return word in self.DICT or word.lower() in self.DICT
+
+    def get_lemma(self, wrong_form: str) -> Optional[str]:
+        return self.get_entry(wrong_form, 0)
+
+    def get_id(self, wrong_form: str) -> Optional[int]:
+        return self.get_entry(wrong_form, 1)
+
+    def get_cat(self, wrong_form: str) -> str:
+        return self.get_entry(wrong_form, 2)
+
+    def get_correct_form(self, wrong_form: str) -> str:
+        return self.get_entry(wrong_form, 3)
 
-    @staticmethod
-    def get_lemma(wrong_form: str) -> Optional[str]:
-        return Ritmyndir.get_entry(wrong_form, 0)
-
-    @staticmethod
-    def get_id(wrong_form: str) -> Optional[int]:
-        return Ritmyndir.get_entry(wrong_form, 1)
-
-    @staticmethod
-    def get_cat(wrong_form: str) -> str:
-        return Ritmyndir.get_entry(wrong_form, 2)
-
-    @staticmethod
-    def get_correct_form(wrong_form: str) -> str:
-        return Ritmyndir.get_entry(wrong_form, 3)
-
-    @staticmethod
-    def get_tag(wrong_form: str) -> str:
-        return Ritmyndir.get_entry(wrong_form, 4)
-
-    @staticmethod
-    def get_eink(wrong_form: str) -> int:
-        eink = Ritmyndir.get_entry(wrong_form, 3)
+    def get_tag(self, wrong_form: str) -> str:
+        return self.get_entry(wrong_form, 4)
+
+    def get_eink(self, wrong_form: str) -> int:
+        eink = self.get_entry(wrong_form, 3)
         if not eink:
             eink = 1
         return eink
 
-    @staticmethod
-    def get_malsnid(wrong_form: str) -> str:
-        return Ritmyndir.get_entry(wrong_form, 6).split(",")[0]
-
-    @staticmethod
-    def get_stafs(wrong_form: str) -> str:
-        return Ritmyndir.get_entry(wrong_form, 7).split(",")[0]
-
-    @staticmethod
-    def get_aslatt(wrong_form: str) -> str:
-        return Ritmyndir.get_entry(wrong_form, 8).split(",")[0]
-
-    @staticmethod
-    def get_beyg(wrong_form: str) -> str:
-        return Ritmyndir.get_entry(wrong_form, 9).split(",")[0]
-
-    @staticmethod
-    def get_code(wrong_form: str) -> str:
-        code = Ritmyndir.get_stafs(wrong_form)
+    def get_malsnid(self, wrong_form: str) -> str:
+        return self.get_entry(wrong_form, 6).split(",")[0]
+
+    def get_stafs(self, wrong_form: str) -> str:
+        return self.get_entry(wrong_form, 7).split(",")[0]
+
+    def get_aslatt(self, wrong_form: str) -> str:
+        return self.get_entry(wrong_form, 8).split(",")[0]
+
+    def get_beyg(self, wrong_form: str) -> str:
+        return self.get_entry(wrong_form, 9).split(",")[0]
+
+    def get_code(self, wrong_form: str) -> str:
+        code = self.get_stafs(wrong_form)
         if not code:
-            code = Ritmyndir.get_aslatt(wrong_form)
+            code = self.get_aslatt(wrong_form)
         if not code:
-            code = Ritmyndir.get_beyg(wrong_form)
+            code = self.get_beyg(wrong_form)
         if not code:
-            code = Ritmyndir.get_malsnid(wrong_form)
+            code = self.get_malsnid(wrong_form)
         if not code:
-            code = R_EINKUNN[Ritmyndir.get_eink(wrong_form)]
+            code = R_EINKUNN[self.get_eink(wrong_form)]
         if not code:
             code = "R001"
         return code
 
-    @staticmethod
-    def get_entry(wrong_form: str, index: int) -> Any:
-        entry = Ritmyndir.DICT.get(wrong_form, Ritmyndir.DICT.get(wrong_form.lower()))
+    def get_entry(self, wrong_form: str, index: int) -> Any:
+        entry = self.DICT.get(wrong_form, self.DICT.get(wrong_form.lower()))
         return entry[index] if entry else None
 
-    @staticmethod
-    def add(wrong_form: str, details: RitmyndirTuple) -> None:
+    def add(self, wrong_form: str, details: RitmyndirTuple) -> None:
         # TODO Same ritmynd can occur multiple times in the data from different references, how to handle?
         # TODO Also check if the same ritmynd has many different corrections in the data,
         # so we don't just overwrite former values. The DICT entries can be a list of corrections, using defaultdict()
-        Ritmyndir.DICT[wrong_form] = details
+        self.DICT[wrong_form] = details
 
 
 class RitmyndirDetails:
-    # "Ritmyndir error code" : ("ritregla/spelling rule", "category", "other detail" ) }
-    DICT: Dict[str, DetailsTuple] = dict()
+    def __init__(self) -> None:
+        # "Ritmyndir error code" : ("ritregla/spelling rule", "category", "other detail" ) }
+        self.DICT: Dict[str, DetailsTuple] = dict()
 
-    @staticmethod
-    def add(code: str, details: DetailsTuple) -> None:
-        RitmyndirDetails.DICT[code] = details
+    def add(self, code: str, details: DetailsTuple) -> None:
+        self.DICT[code] = details
 
 
 class IecNonwords:
-    # Dictionary structure: dict { wrong_word : (tuple of right words) }
-    DICT: Dict[str, Tuple[str, ...]] = dict()
+    def __init__(self) -> None:
+        # Dictionary structure: dict { wrong_word : (tuple of right words) }
+        self.DICT: Dict[str, Tuple[str, ...]] = dict()
 
-    @staticmethod
-    def add(word: str, corr: Tuple[str, ...]) -> None:
-        if word in IecNonwords.DICT:
+    def add(self, word: str, corr: Tuple[str, ...]) -> None:
+        if word in self.DICT:
             # Happens in the data, just skip it
             # raise ConfigError(
             #    "Multiple definition of '{0}' in IEC nonwords data".format(word)
             # )
             return
-        IecNonwords.DICT[word] = corr
+        self.DICT[word] = corr
 
 
 class Icesquer:
-    # Dictionary structure: dict { wrong_word : (tuple of right words) }
-    DICT: Dict[str, Tuple[str, ...]] = dict()
+    def __init__(self) -> None:
+        # Dictionary structure: dict { wrong_word : (tuple of right words) }
+        self.DICT: Dict[str, Tuple[str, ...]] = dict()
 
-    @staticmethod
-    def add(word: str, corr: Tuple[str, ...]) -> None:
-        if word in Icesquer.DICT:
+    def add(self, word: str, corr: Tuple[str, ...]) -> None:
+        if word in self.DICT:
             # Happens in the data, just skip it
             # raise ConfigError(
             #    "Multiple definition of '{0}' in IEC nonwords data".format(word)
             # )
             return
-        Icesquer.DICT[word] = corr
+        self.DICT[word] = corr
+
+
+class WrongFormers:
+    def __init__(self) -> None:
+        # Dictionary structure: dict { wrong_word : right_word }
+        self.DICT: Dict[str, Tuple[str, ...]] = dict()
+
+    def add(self, word: str, corr: Tuple[str, ...]) -> None:
+        if word in self.DICT:
+            # Happens in the data, just skip it
+            return
+        self.DICT[word] = corr
+
+
+class WrongFormersCID:
+    def __init__(self) -> None:
+        # Dictionary structure: dict { wrong_word : right_word }
+        self.DICT: Dict[str, Tuple[str, ...]] = dict()
+
+    def add(self, word: str, corr: Tuple[str, ...]) -> None:
+        if word in self.DICT:
+            # Happens in the data, just skip it
+            return
+        self.DICT[word] = corr
 
 
 class Settings:
 
     """Global settings"""
 
+    def __init__(self):
+        self.allowed_multiples = AllowedMultiples()
+        self.wrong_compounds = WrongCompounds()
+        self.split_compounds = SplitCompounds()
+        self.unique_errors = UniqueErrors()
+        self.multiword_errors = MultiwordErrors()
+        self.taboo_words = TabooWords()
+        self.suggestions = Suggestions()
+        self.capitalization_errors = CapitalizationErrors()
+        self.ow_forms = OwForms()
+        self.cid_error_forms = CIDErrorForms()
+        self.cd_error_forms = CDErrorForms()
+        self.morphemes = Morphemes()
+        self.ritmyndir = Ritmyndir()
+        self.ritmyndir_details = RitmyndirDetails()
+        self.iec_nonwords = IecNonwords()
+        self.icesquer = Icesquer()
+        self.tone_of_voice_words = ToneOfVoiceWords()
+        self.tone_of_voice_patterns = ToneOfVoicePatterns()
+        self.wrong_formers = WrongFormers()
+        self.wrong_formers_cid = WrongFormersCID()
+
     _lock = threading.Lock()
     loaded = False
     DEBUG = os.environ.get("DEBUG", "").strip() in TRUE
 
     # Configuration settings from the GreynirCorrect.conf file
 
-    @staticmethod
-    def _handle_settings(s: str) -> None:
+    def _handle_settings(self, s: str) -> None:
         """Handle config parameters in the settings section"""
         a: List[str] = s.lower().split("=", maxsplit=1)
         par = a[0].strip().lower()
         val = a[1].strip()
         try:
             if par == "debug":
                 Settings.DEBUG = val in TRUE
             else:
                 raise ConfigError("Unknown configuration parameter '{0}'".format(par))
         except ValueError:
             raise ConfigError("Invalid parameter value: {0} = {1}".format(par, val))
 
-    @staticmethod
-    def _handle_allowed_multiples(s: str) -> None:
+    def _handle_allowed_multiples(self, s: str) -> None:
         """Handle config parameters in the allowed_multiples section"""
         assert s
         if len(s.split()) != 1:
             raise ConfigError(
                 "Only one word per line allowed in allowed_multiples section"
             )
-        if s in AllowedMultiples.SET:
+        if s in self.allowed_multiples.SET:
             raise ConfigError(
                 "'{0}' is repeated in allowed_multiples section".format(s)
             )
-        AllowedMultiples.add(s)
+        self.allowed_multiples.add(s)
 
-    @staticmethod
-    def _handle_wrong_compounds(s: str) -> None:
+    def _handle_wrong_compounds(self, s: str) -> None:
         """Handle config parameters in the wrong_compounds section"""
         a = s.lower().split(",", maxsplit=1)
         if len(a) != 2:
             raise ConfigError("Expected comma between compound word and its parts")
         word = a[0].strip().strip('"')
         parts = a[1].strip().strip('"').split()
         if not word:
@@ -663,26 +681,24 @@
             )
         if len(parts) < 2:
             raise ConfigError("Missing word part(s) in wrong_compounds section")
         if len(word.split()) != 1:
             raise ConfigError(
                 "Multiple words not allowed before comma in wrong_compounds section"
             )
-        WrongCompounds.add(word, tuple(parts))
+        self.wrong_compounds.add(word, tuple(parts))
 
-    @staticmethod
-    def _handle_split_compounds(s: str) -> None:
+    def _handle_split_compounds(self, s: str) -> None:
         """Handle config parameters in the split_compounds section"""
         parts = s.split()
         if len(parts) != 2:
             raise ConfigError("Missing word part(s) in split_compounds section")
-        SplitCompounds.add(parts[0], parts[1])
+        self.split_compounds.add(parts[0], parts[1])
 
-    @staticmethod
-    def _handle_unique_errors(s: str) -> None:
+    def _handle_unique_errors(self, s: str) -> None:
         """Handle config parameters in the unique_errors section"""
         a = s.lower().split(",", maxsplit=1)
         if len(a) != 2:
             raise ConfigError("Expected comma between error word and its correction")
         word = a[0].strip()
         if len(word) < 3:
             raise ConfigError(
@@ -704,23 +720,21 @@
         corr_t = tuple(corr.split())
         if not word:
             raise ConfigError("Expected word before the comma in unique_errors section")
         if len(word.split()) != 1:
             raise ConfigError(
                 "Multiple words not allowed before the comma in unique_errors section"
             )
-        UniqueErrors.add(word, corr_t)
+        self.unique_errors.add(word, corr_t)
 
-    @staticmethod
-    def _handle_capitalization_errors(s: str) -> None:
+    def _handle_capitalization_errors(self, s: str) -> None:
         """Handle config parameters in the capitalization_errors section"""
-        CapitalizationErrors.add(s)
+        self.capitalization_errors.add(s)
 
-    @staticmethod
-    def _handle_taboo_words(s: str) -> None:
+    def _handle_taboo_words(self, s: str) -> None:
         """Handle config parameters in the taboo_words section"""
         # Start by parsing explanation string off the end (right hand side), if present
         lquote = s.find('"')
         rquote = s.rfind('"')
         if (lquote >= 0) != (rquote >= 0):
             raise ConfigError(
                 "Explanation string for taboo word should be enclosed in double quotes"
@@ -743,48 +757,87 @@
         else:
             replacement = taboo
         # Check all replacement words, which are separated by slashes '/'
         if any(r.count("_") != 1 for r in replacement.split("/")):
             raise ConfigError(
                 "Suggested replacement(s) should include a word category (_xx)"
             )
-        TabooWords.add(taboo, replacement, explanation)
+        self.taboo_words.add(taboo, replacement, explanation)
+
+    def _handle_tone_of_voice_words(self, s: str) -> None:
+        """Handle config parameters in the tone_of_voice section."""
+        # Start by parsing explanation string off the end (right hand side), if present
+        lquote = s.find('"')
+        rquote = s.rfind('"')
+        if (lquote >= 0) != (rquote >= 0):
+            raise ConfigError(
+                "Explanation string for a word should be enclosed in double quotes"
+            )
+        if lquote >= 0:
+            # Obtain explanation from within quotes
+            explanation = s[lquote + 1 : rquote].strip()
+            s = s[:lquote].rstrip()
+        else:
+            # No explanation
+            explanation = ""
+        if not s:
+            raise ConfigError("Expected a word to flag and a suggested replacement")
+        a = s.lower().split()
+        if len(a) > 2:
+            raise ConfigError("Expected a word to flag and a suggested replacement")
+        flagged_word = a[0].strip()
+        if len(a) == 2:
+            replacement = a[1].strip()
+        else:
+            replacement = flagged_word
+        # Check all replacement words, which are separated by slashes '/'
+        if any(r.count("_") != 1 for r in replacement.split("/")):
+            raise ConfigError(
+                "Suggested replacement(s) should include a word category (_xx)"
+            )
+        self.tone_of_voice_words.add(flagged_word, replacement, explanation)
 
-    @staticmethod
-    def _handle_suggestions(s: str) -> None:
+    def _handle_tone_of_voice_patterns(self, s: str) -> None:
+        """Handle module path for external patterns."""
+        # the string includes quotes, let's remove them
+        p = s.split("=")[1].strip().strip('"')
+        # Should only be a path to a python file
+        if not os.path.exists(p):
+            raise ConfigError("Not a valid path. Expected a path to a Python file")
+        self.tone_of_voice_patterns.add(p)
+
+    def _handle_suggestions(self, s: str) -> None:
         """Handle config parameters in the suggestions section"""
         a = s.lower().split()
         if len(a) < 2:
             raise ConfigError(
-                "Expected bad word and at least one suggested replacement"
+                "Expected flagged word and at least one suggested replacement"
             )
         if any(w.count("_") != 1 for w in a[1:]):
             raise ConfigError(
                 "Suggested replacements should include word category (_xx)"
             )
-        Suggestions.add(a[0].strip(), [w.strip() for w in a[1:]])
+        self.suggestions.add(a[0].strip(), [w.strip() for w in a[1:]])
 
-    @staticmethod
-    def _handle_multiword_errors(s: str) -> None:
+    def _handle_multiword_errors(self, s: str) -> None:
         """Handle config parameters in the multiword_errors section"""
         a = s.lower().split("$error", maxsplit=1)
         if len(a) != 2:
             raise ConfigError("Expected phrase followed by $error(...)")
         phrase = tuple(a[0].strip().split())
         if len(phrase) < 2:
             raise ConfigError("Multiword phrase must contain at least two words")
         error = a[1].strip()
         if len(error) < 3:
             raise ConfigError("Incomplete error specification for multiword phrase")
         if error[0] != "(" or error[-1] != ")":
             raise ConfigError("Error specification should be enclosed in parentheses")
-        MultiwordErrors.add(phrase, error[1:-1])
+        self.multiword_errors.add(phrase, error[1:-1])
 
-    @staticmethod
-    def _handle_ow_forms(s: str) -> None:
+    def _handle_ow_forms(self, s: str) -> None:
         """Handle config parameters in the ow_forms section"""
         split = s.strip().split(";")
         if len(split) != 6:
             raise ConfigError("Expected wrong form;lemma;correct form;id;category;tag")
         wrong_form = split[0].strip()
         correct_form = split[2].strip()
         if wrong_form == correct_form:
@@ -796,18 +849,17 @@
         meaning: ErrorFormTuple = (
             split[1].strip(),  # Lemma (stofn)
             correct_form,  # Correct form (ordmynd)
             int(split[3]),  # Id (utg)
             split[4].strip(),  # Category (ordfl)
             split[5].strip(),  # Tag (beyging)
         )
-        OwForms.add(wrong_form, meaning)
+        self.ow_forms.add(wrong_form, meaning)
 
-    @staticmethod
-    def _handle_error_forms(s: str) -> None:
+    def _handle_error_forms(self, s: str) -> None:
         """Handle config parameters in the error_forms section"""
         split = s.strip().split(";")
         if len(split) != 7:
             raise ConfigError(
                 "Expected wrong form;lemma;correct form;id;category;tag;errortype"
             )
         wrong_form = split[0].strip()
@@ -821,22 +873,21 @@
             correct_form,  # Correct form (ordmynd)
             int(split[3]),  # Id (utg)
             split[4].strip(),  # Category (ordfl)
             split[5].strip(),  # Tag (beyging)
         )
         etype = split[6].strip()
         if etype == "cid":
-            CIDErrorForms.add(wrong_form, meaning)  # context-independent errors
+            self.cid_error_forms.add(wrong_form, meaning)  # context-independent errors
         elif etype == "cd":
-            CDErrorForms.add(wrong_form, meaning)  # context-dependent errors
+            self.cd_error_forms.add(wrong_form, meaning)  # context-dependent errors
         else:
             raise ConfigError("Wrong error type given, expected 'cid' or 'cd'")
 
-    @staticmethod
-    def _handle_morphemes(s: str) -> None:
+    def _handle_morphemes(self, s: str) -> None:
         """Process the contents of the [morphemes] section"""
         freelist: List[str] = []
         boundlist: List[str] = []
         spl = s.split()
         if len(spl) < 2:
             raise ConfigError(
                 "Expected at least a prefix and an attachment specification"
@@ -848,18 +899,17 @@
                     boundlist.append(pos[1:])
                 elif pos.startswith("-"):
                     freelist.append(pos[1:])
                 else:
                     raise ConfigError(
                         "Attachment specification should start with '+' or '-'"
                     )
-        Morphemes.add(m, boundlist, freelist)
+        self.morphemes.add(m, boundlist, freelist)
 
-    @staticmethod
-    def _handle_ritmyndir(s: str) -> None:
+    def _handle_ritmyndir(self, s: str) -> None:
         """Handle data from Ritmyndir in Stórasnið in BÍN/DIM"""
         split = s.strip().split(";")
         if len(split) != 13:
             raise ConfigError(
                 "Expected lemma, id, cat, wrong_word_form, correct_word_form, tag, eink, malsnid, stafs, aslatt, beyg, age, ref"
             )
         ref = split[12].strip()
@@ -882,30 +932,28 @@
             split[5].strip(),  # tag
             int(split[6].strip()),  # eink
             split[7].strip(),  # malsnid
             split[8].strip(),  # stafs
             split[9].strip(),  # aslatt
             split[10].strip(),  # beyg
         )
-        Ritmyndir.add(wrong_form, meaning)
+        self.ritmyndir.add(wrong_form, meaning)
 
-    @staticmethod
-    def _handle_ritmyndir_details(s: str) -> None:
+    def _handle_ritmyndir_details(self, s: str) -> None:
         """Handle data on Ritmyndir categories, including references to the Icelandic Standards"""
         # "Ritmyndir error code" : ("ritregla/spelling rule", "category", "other detail" )
         split = s.split(":", maxsplit=1)
         code = split[0].strip().strip('"')
         dsplit = split[1].split('", "')
         rule = dsplit[0].strip().strip('"')
         cat = dsplit[1].strip().strip('"')
         det = dsplit[2].strip().strip('"')
-        RitmyndirDetails.DICT[code] = (rule, cat, det)
+        self.ritmyndir_details.DICT[code] = (rule, cat, det)
 
-    @staticmethod
-    def _handle_iec_nonwords(s: str) -> None:
+    def _handle_iec_nonwords(self, s: str) -> None:
         """Handle config parameters in the Icelandic Error Corpus Nonwords"""
         a = s.lower().split("\t")
         if len(a) != 2:
             # Happens in the data, just skip it
             # raise ConfigError("Expected tab between error word and its correction")
             return
         word = a[0].strip()
@@ -923,18 +971,17 @@
             raise ConfigError("Expected word before the comma in unique_errors section")
         if len(word.split()) != 1:
             # Happens in the data, just skip it
             return
             # raise ConfigError(
             #    "Multiple words not allowed before the comma in unique_errors section"
             # )
-        IecNonwords.add(word, corr_t)
+        self.iec_nonwords.add(word, corr_t)
 
-    @staticmethod
-    def _handle_icesquer(s: str) -> None:
+    def _handle_icesquer(self, s: str) -> None:
         """Handle config parameters in the Icelandic Error Corpus Nonwords"""
         a = s.lower().split("\t")
         if len(a) != 2:
             # Happens in the data, just skip it
             # raise ConfigError("Expected tab between error word and its correction")
             return
         word = a[0].strip()
@@ -952,50 +999,82 @@
             raise ConfigError("Expected word before the comma in unique_errors section")
         if len(word.split()) != 1:
             # Happens in the data, just skip it
             return
             # raise ConfigError(
             #    "Multiple words not allowed before the comma in unique_errors section"
             # )
-        Icesquer.add(word, corr_t)
+        self.icesquer.add(word, corr_t)
 
-    @staticmethod
-    def read(fname: str) -> None:
-        """Read configuration file"""
+    def _handle_wrong_formers(self, s: str) -> None:
+        """Handle config parameters in the wrong_formers section"""
+        a = s.lower().split(",", maxsplit=1)
+        if len(a) != 2:
+            raise ConfigError("Expected comma between the word and its correction")
+        word = a[0].strip().strip('"')
+        correction = a[1].strip().strip('"')
+        if not word:
+            raise ConfigError("Expected word before the comma in wrong_formers section")
+        if not correction:
+            raise ConfigError("Expected word after the comma in wrong_formers section")
+        if len(word.split()) != 1 or len(correction.split()) != 1:
+            raise ConfigError("Expected one word on each side in wrong_formers")
+        self.wrong_formers.add(word, correction)
 
-        with Settings._lock:
+    def _handle_wrong_formers_cid(self, s: str) -> None:
+        """Handle config parameters in the wrong_formers section"""
+        a = s.lower().split(",", maxsplit=1)
+        if len(a) != 2:
+            raise ConfigError("Expected comma between the word and its correction")
+        word = a[0].strip().strip('"')
+        correction = a[1].strip().strip('"')
+        if not word:
+            raise ConfigError("Expected word before the comma in wrong_formers section")
+        if not correction:
+            raise ConfigError("Expected word after the comma in wrong_formers section")
+        if len(word.split()) != 1 or len(correction.split()) != 1:
+            raise ConfigError("Expected one word on each side in wrong_formers")
+        self.wrong_formers_cid.add(word, correction)
 
-            if Settings.loaded or UniqueErrors.DICT or AllowedMultiples.SET:
-                return
+    def read(self, fname: str, external: bool = False) -> None:
+        """Read configuration file"""
 
+        with Settings._lock:
             CONFIG_HANDLERS = {
                 "settings": Settings._handle_settings,
                 "allowed_multiples": Settings._handle_allowed_multiples,
                 "wrong_compounds": Settings._handle_wrong_compounds,
                 "split_compounds": Settings._handle_split_compounds,
                 "unique_errors": Settings._handle_unique_errors,
                 "capitalization_errors": Settings._handle_capitalization_errors,
                 "taboo_words": Settings._handle_taboo_words,
+                "tone_of_voice_words": Settings._handle_tone_of_voice_words,
+                "tone_of_voice_patterns": Settings._handle_tone_of_voice_patterns,
                 "suggestions": Settings._handle_suggestions,
                 "multiword_errors": Settings._handle_multiword_errors,
                 "morphemes": Settings._handle_morphemes,
                 "ow_forms": Settings._handle_ow_forms,
                 "error_forms": Settings._handle_error_forms,
                 "auto_ow": Settings._handle_ow_forms,
                 "auto_error": Settings._handle_error_forms,
                 "iec_nonwords": Settings._handle_iec_nonwords,
                 "icesquer": Settings._handle_icesquer,
                 "ritmyndir": Settings._handle_ritmyndir,
                 "ritmyndir_details": Settings._handle_ritmyndir_details,
+                "wrong_formers": Settings._handle_wrong_formers,
+                "wrong_formers_ci": Settings._handle_wrong_formers_cid,
             }
             handler = None  # Current section handler
 
             rdr = None
+
             try:
-                rdr = LineReader(fname, package_name=__name__)
+                # If an external path is given, use it to read the file
+                package_name = None if external else __name__
+                rdr = LineReader(fname, package_name=package_name)
                 for s in rdr.lines():
                     # Ignore comments
                     ix = s.find("#")
                     if ix >= 0:
                         s = s[0:ix]
                     s = s.strip()
                     if not s:
@@ -1008,15 +1087,15 @@
                             handler = CONFIG_HANDLERS[section]
                             continue
                         raise ConfigError("Unknown section name '{0}'".format(section))
                     if handler is None:
                         raise ConfigError("No handler for config line '{0}'".format(s))
                     # Call the correct handler depending on the section
                     try:
-                        handler(s)
+                        handler(self, s)
                     except ConfigError as e:
                         # Add file name and line number information to the exception
                         # if it's not already there
                         e.set_pos(rdr.fname(), rdr.line())
                         raise e
 
             except ConfigError as e:
```

### Comparing `reynir-correct-3.4.6/src/reynir_correct/spelling.py` & `reynir-correct-3.4.7/src/reynir_correct/spelling.py`

 * *Files identical despite different names*

### Comparing `reynir-correct-3.4.6/src/reynir_correct/tools/diffchecker.py` & `reynir-correct-3.4.7/src/reynir_correct/tools/diffchecker.py`

 * *Files 5% similar despite different names*

```diff
@@ -3,15 +3,14 @@
 """
 Easy way to look at input and output together.
 To run for the file 'prufa.txt':
 $ python diffchecker.py prufa.txt
 
 """
 from reynir_correct.wrappers import check_errors
-
 from typing import (
     Iterator,
     Iterable,
     Dict,
     Set,
     Union,
 )
@@ -43,24 +42,28 @@
 
     options: Dict[str, Union[str, bool, Set[str]]] = {}
     options["format"] = "text"  # text, json, csv, m2
     options["annotations"] = True
     options["all_errors"] = True
     # options["input"] = open("prufa.txt", "r")
     options["one_sent"] = False
-    # options["generate_suggestion_list"] = True
-    options["ignore_comments"] = False  # Only used here
+    options["generate_suggestion_list"] = True
+    options["ignore_comments"] = True  # Only used here
     options["generate_suggestion_list"] = False
     options["annotate_unparsed_sentences"] = True
     options["suppress_suggestions"] = False
     options["replace_html_escapes"] = True
     options["ignore_wordlist"] = set()
     options["spaced"] = False
     options["print_all"] = True
     options["ignore_rules"] = set()
+    options["suggest_not_correct"] = False
+    options["extra_config"] = "config/ExtraWords.conf"
+    options["extra_tone_of_voice"] = True
+
     args = parser.parse_args()
     infile = args.infile
     if infile is sys.stdin and sys.stdin.isatty():
         # terminal input is empty, most likely no value was given for infile:
         # Nothing we can do
         print("No input has been given, nothing can be returned")
         sys.exit(1)
```

### Comparing `reynir-correct-3.4.6/src/reynir_correct/tools/ritmyndirchecker.py` & `reynir-correct-3.4.7/src/reynir_correct/tools/ritmyndirchecker.py`

 * *Files 19% similar despite different names*

```diff
@@ -15,20 +15,21 @@
 )
 
 # Error codes that are not explicitly an error
 IGNORE = set(["GAM", "SO-ÞGF4ÞF", "OSB-BMYND", "SJALD", "STAD", "AV"])
 
 
 def main() -> None:
-
+    ritmyndir = Ritmyndir()
+    ritmyndir_details = RitmyndirDetails()
     allcodes: Set[str] = set()
-    for entry in Ritmyndir.DICT:
-        allcodes.add(Ritmyndir.get_code(entry))
+    for entry in ritmyndir.DICT:
+        allcodes.add(ritmyndir.get_code(entry))
     detcodes: Set[str] = set()
-    for keycode in RitmyndirDetails.DICT:
+    for keycode in ritmyndir_details.DICT:
         detcodes.add(keycode)
 
     # Compare
     newcodes = allcodes - detcodes - IGNORE
     outdated = detcodes - allcodes - IGNORE
 
     print("=====================")
```

### Comparing `reynir-correct-3.4.6/src/reynir_correct/wrappers.py` & `reynir-correct-3.4.7/src/reynir_correct/wrappers.py`

 * *Files 2% similar despite different names*

```diff
@@ -78,15 +78,16 @@
 
 from tokenizer import detokenize, text_from_tokens, normalized_text_from_tokens, TOK
 from tokenizer.definitions import AmountTuple, NumberTuple
 
 from .errtokenizer import CorrectToken, Error
 from .errtokenizer import tokenize as errtokenize
 from .annotation import Annotation
-from .checker import check_tokens
+from .checker import GreynirCorrect, check_tokens, load_config
+from .settings import Settings
 
 
 class AnnTokenDict(TypedDict, total=False):
 
     """Type of the token dictionaries returned from check_errors()"""
 
     # Token kind
@@ -189,35 +190,36 @@
         return quote(t.val)
     return t.val
 
 
 def check_errors(**options: Any) -> str:
     """Return a string in the chosen format and correction level
     using the spelling and grammar checker"""
+    rc = GreynirCorrect(load_config(options), **options)
     input = options.get("input", None)
     if isinstance(input, str):
         options["input"] = [input]
     if options.get("all_errors", True):
-        return check_grammar(**options)
+        return check_grammar(rc=rc)
     else:
-        return check_spelling(**options)
+        return check_spelling(settings=rc.settings, **options)
 
 
-def check_spelling(**options: Any) -> str:
+def check_spelling(settings: Settings, **options: Any) -> str:
     # Initialize sentence accumulator list
     # Function to convert a token list to output text
     format = options.get("format", "json")
     if options.get("spaced", False):
         if options.get("normalize", False):
             to_text = normalized_text_from_tokens
         else:
             to_text = text_from_tokens
     else:
         to_text = partial(detokenize, normalize=True)
-    toks = sentence_stream(**options)
+    toks = sentence_stream(settings=settings, **options)
     unisum: List[str] = []
     allsum: List[str] = []
     annlist: List[str] = []
     annotations = options.get("annotations", False)
     print_all = options.get("print_all", False)
     for toklist in toks:
         if format == "text":
@@ -265,25 +267,25 @@
         if annlist:
             unistr = unistr + "\n" + "\n".join(annlist)
     else:
         unistr = "\n".join(unisum)
     return unistr
 
 
-def test_spelling(**options: Any) -> Tuple[str, TokenSumType]:
+def test_spelling(settings: Settings, **options: Any) -> Tuple[str, TokenSumType]:
     # Initialize sentence accumulator list
     # Function to convert a token list to output text
     if options.get("spaced", False):
         if options.get("normalize", False):
             to_text = normalized_text_from_tokens
         else:
             to_text = text_from_tokens
     else:
         to_text = partial(detokenize, normalize=True)
-    toks = sentence_stream(**options)
+    toks = sentence_stream(settings=settings, **options)
     unisum: List[str] = []
     toksum: TokenSumType = []
     annlist: List[str] = []
     print_all = options.get("print_all", False)
     for toklist in toks:
         unisum.append(to_text(toklist))
         if print_all:
@@ -297,49 +299,50 @@
         if annlist:
             unistr = unistr + "\n" + "\n".join(annlist)
     else:
         unistr = "\n".join(unisum)
     return unistr, toksum
 
 
-def sentence_stream(**options: Any) -> Iterator[List[CorrectToken]]:
+def sentence_stream(settings: Settings, **options: Any) -> Iterator[List[CorrectToken]]:
     """Yield a stream of sentence token lists from the source text"""
     # Initialize sentence accumulator list
     curr_sent: List[CorrectToken] = []
     gen = options.get("input", None)
     if gen is None:
         gen = sys.stdin
-    for t in errtokenize(gen, **options):
+    for t in errtokenize(gen, settings, **options):
         # Normal shallow parse, one line per sentence,
         # tokens separated by spaces
         curr_sent.append(t)
         if t.kind in TOK.END:
             # End of sentence/paragraph
             yield curr_sent
             curr_sent = []
     if curr_sent:
         yield curr_sent
 
 
-def test_grammar(**options: Any) -> Tuple[str, TokenSumType]:
+def test_grammar(rc: GreynirCorrect, **options: Any) -> Tuple[str, TokenSumType]:
     """Do a full spelling and grammar check of the source text"""
 
     accumul: List[str] = []
     offset = 0
     alltoks: TokenSumType = []
     inneroptions: Dict[str, Union[str, bool]] = {}
     inneroptions["annotate_unparsed_sentences"] = options.get(
         "annotate_unparsed_sentences", True
     )
     inneroptions["ignore_rules"] = options.get("ignore_rules", set())
     annlist: List[str] = []
-    for toklist in sentence_stream(**options):
+
+    for toklist in sentence_stream(rc.settings, **options):
         # Invoke the spelling and grammar checker on the token list
         # Only contains options relevant to the grammar check
-        sent = check_tokens(toklist, **inneroptions)
+        sent = check_tokens(toklist, rc, **inneroptions)
         if sent is None:
             # Should not happen?
             continue
 
         # Maintain token character offsets, accumulated over the entire source text
         token_offsets: Dict[int, int] = dict()
         for ix, t in enumerate(toklist):
@@ -380,31 +383,28 @@
         accumul.append(txt)
 
     accumstr = "\n".join(accumul)
 
     return accumstr, alltoks
 
 
-def check_grammar(**options: Any) -> str:
+def check_grammar(rc: GreynirCorrect) -> str:
     """Do a full spelling and grammar check of the source text"""
-
     inneroptions: Dict[str, Union[str, bool]] = {}
-    inneroptions["annotate_unparsed_sentences"] = options.get(
+    inneroptions["annotate_unparsed_sentences"] = rc._options.get(
         "annotate_unparsed_sentences", True
     )
-    inneroptions["ignore_rules"] = options.get("ignore_rules", set())
-
+    inneroptions["ignore_rules"] = rc._options.get("ignore_rules", set())
     sentence_results: List[Dict[str, Any]] = []
-
     sentence_classifier: Optional[SentenceClassifier] = None
 
-    for raw_tokens in sentence_stream(**options):
+    for raw_tokens in sentence_stream(settings=rc.settings, **rc._options):
         original_sentence = "".join([t.original or t.txt for t in raw_tokens])
 
-        if options.get("sentence_prefilter", False):
+        if rc._options.get("sentence_prefilter", False):
             # Only construct the classifier model if we need it
             from .classifier import SentenceClassifier
 
             if sentence_classifier is None:
                 sentence_classifier = SentenceClassifier()
 
             if not sentence_classifier.classify(original_sentence):
@@ -425,15 +425,15 @@
                         "partially_corrected": original_sentence,
                         "annotations": [],
                         "tokens": nice_tokens,
                     }
                 )
                 continue
 
-        annotated_sentence = check_tokens(raw_tokens, **inneroptions)
+        annotated_sentence = check_tokens(raw_tokens, rc, **inneroptions)
         if annotated_sentence is None:
             # This should not happen, but we check to be sure, and to satisfy mypy
             # TODO: Should we rather raise an exception instead of silently discarding the sentence?
             continue
 
         # Extract the annotation list (defensive programming here)
         annotations: List[Annotation] = getattr(
@@ -493,19 +493,19 @@
                 "corrected": fully_corrected_sentence,
                 "annotations": annotations,
                 "tokens": tokens,
             }
         )
 
     extra_text_options = {
-        "annotations": options.get("annotations", False),
-        "print_all": options.get("print_all", False),
+        "annotations": rc._options.get("annotations", False),
+        "print_all": rc._options.get("print_all", False),
     }
     return format_output(
-        sentence_results, options.get("format", "json"), extra_text_options
+        sentence_results, rc._options.get("format", "json"), extra_text_options
     )
 
 
 def format_output(
     sentence_results: List[Dict[str, Any]],
     format_type: str,
     extra_text_options: Dict[str, Any],
```

### Comparing `reynir-correct-3.4.6/src/reynir_correct.egg-info/PKG-INFO` & `reynir-correct-3.4.7/src/reynir_correct.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,17 +1,16 @@
 Metadata-Version: 2.1
 Name: reynir-correct
-Version: 3.4.6
+Version: 3.4.7
 Summary: A spelling and grammar corrector for Icelandic
 Home-page: https://github.com/mideind/GreynirCorrect
 Author: Miðeind ehf
 Author-email: mideind@mideind.is
 License: MIT
 Keywords: nlp,parser,icelandic,spellchecker
-Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: Science/Research
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: Unix
 Classifier: Operating System :: POSIX
 Classifier: Operating System :: Microsoft :: Windows
@@ -26,15 +25,15 @@
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Programming Language :: Python :: Implementation :: CPython
 Classifier: Programming Language :: Python :: Implementation :: PyPy
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Classifier: Topic :: Utilities
 Classifier: Topic :: Text Processing :: Linguistic
 Provides-Extra: sentence_classifier
-License-File: LICENSE
+License-File: LICENSE.txt
 
 
 .. image:: https://img.shields.io/badge/License-MIT-yellow.svg
     :target: https://opensource.org/licenses/MIT
 .. image:: https://img.shields.io/badge/python-3.7-blue.svg
     :target: https://www.python.org/downloads/release/python-370/
 .. image:: https://img.shields.io/pypi/v/reynir-correct
@@ -202,14 +201,18 @@
 +-----------------------------------+--------------------------------------------------+-----------------+
 | | ``one_sent``                    | The input contains a single sentence only.       | ``False``       |
 |                                   | Sentence splitting should not be attempted.      |                 |
 +-----------------------------------+--------------------------------------------------+-----------------+
 | | ``ignore_rules``                | A set of error codes that should be ignored      | ``set()``       |
 |                                   | in the annotation process.                       |                 |
 +-----------------------------------+--------------------------------------------------+-----------------+
+| | ``tov_config``                  | Path to an additional configuration file that    | ``False``       |
+|                                   | may be provided for correcting custom            |                 |
+|                                   | tone-of-voice issues.                            |                 |
++-----------------------------------+--------------------------------------------------+-----------------+
 
 An overview of error codes is available `here <https://github.com/mideind/GreynirCorrect/blob/master/doc/errorcodes.rst>`__.
 
 *************
 Prerequisites
 *************
 
@@ -467,9 +470,7 @@
 and `here in Icelandic <https://bin.arnastofnun.is/gogn/mimisbrunnur/>`_.
 
 In accordance with the BÍN license terms, credit is hereby given as follows:
 
 *Beygingarlýsing íslensks nútímamáls. Stofnun Árna Magnússonar í íslenskum fræðum.*
 *Höfundur og ritstjóri Kristín Bjarnadóttir.*
 
-
-
```

### Comparing `reynir-correct-3.4.6/src/reynir_correct.egg-info/SOURCES.txt` & `reynir-correct-3.4.7/src/reynir_correct.egg-info/SOURCES.txt`

 * *Files 4% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-LICENSE
+LICENSE.txt
 MANIFEST.in
 README.rst
 setup.py
 src/.DS_Store
 src/reynir_correct/.DS_Store
 src/reynir_correct/__init__.py
 src/reynir_correct/annotation.py
```

### Comparing `reynir-correct-3.4.6/test/test_allkinds.py` & `reynir-correct-3.4.7/test/test_allkinds.py`

 * *Files 1% similar despite different names*

```diff
@@ -31,21 +31,26 @@
 
     This module tests both the token-level error detection and correction
     and the sentence-level annotation functionality of GreynirCorrect.
 
 """
 
 # Run with 'pytest -v' for verbose mode
-
+import pytest
 import reynir_correct as rc
 from reynir_correct import detokenize
 from reynir_correct.wrappers import test_grammar as wrap_check
 
 # Tests for errtokenizer.py
 
+# Global settings object for the tests
+settings = rc.Settings()
+settings.read("../reynir_correct/config/GreynirCorrect.conf")
+gc = rc.GreynirCorrect(settings=settings)
+
 
 def dump(tokens):
     print("\n{0} tokens:\n".format(len(tokens)))
     for token in tokens:
         print("{0}".format(token))
         err = token.error_description
         if err:
@@ -58,15 +63,15 @@
 
 
 def check(p, options={}):
     """Return a corrected, normalized string form of the input along with the tokens"""
     options["input"] = [p]
     options["one_sent"] = False
 
-    return wrap_check(**options)
+    return wrap_check(rc=gc, **options)
 
 
 def test_punctuation(verbose=False):
     # Quotation marks
     s, g = check('Hann var kallaður ,,pottormur" og var "hrekkjusvín".')
     assert "„pottormur“" in s
     assert "„hrekkjusvín“" in s
@@ -512,29 +517,30 @@
     s, g = check("Ríkissjóður tók m.a 30 ma lán.")
     assert "m.a. " in s
     assert "m.a " not in s
     assert g[3].error_code == "A002"
 
 
 def test_capitalization(verbose=False):
+    # NOTE "Eskimói" has now been added to BÍN, and as an error in Storasnid_ord.csv, but not to Storasnid_ritm.csv.
     s, g = check(
         "Einn Aríi, Búddisti, Eskimói, Gyðingur, sjálfstæðismaður, "
         "Múslími og Sjíti gengu inn á bar í evrópu."
     )
     assert "aríi" in s
     assert "búddisti" in s
-    assert "eskimói" in s or "inúíti" in s  # both the cap and taboo error are corrected
+    # assert "eskimói" in s or "inúíti" in s  # both the cap and taboo error are corrected.
     # assert "gyðingur" in s
     assert "Sjálfstæðismaður" in s
     assert "múslími" in s
     assert "sjíti" in s
     assert "Evrópu" in s
     assert g[2].error_code == "Z001"  # aríi
     assert g[4].error_code == "Z001"  # búddisti
-    assert g[6].error_code == "Z001" or g[6].error_code == "T001/w"  # eskimói/inúíti
+    # assert g[6].error_code == "Z001" or g[6].error_code == "T001/w"  # eskimói/inúíti
     # assert g[8].error_code == "Z001"  # gyðingur
     assert g[10].error_code == "Z002"  # Sjálfstæðismaður
     assert g[12].error_code == "Z001"  # múslími
     assert g[14].error_code == "Z001"  # sjíti
 
     s, g = check(
         "Á íslandi búa íslendingar og í danmörku búa Danskir danir í Nóvember en ekki fríslendingar."
@@ -630,15 +636,16 @@
     assert "Sumarólympíuleikunum" in s
     assert "Líbanar" in s
     assert g[5].error_code == "Z002"  # Vetrarólympíuleikunum
     assert g[7].error_code == "Z002"  # Sumarólympíuleikunum
     assert g[9].error_code == "Z002"  # Líbanar
 
     g = rc.tokenize(
-        "Nýr Loftslagsráðherra, Innviðaráðherra og Umhverfisráðherra er Afróasískur, talar Dravídamál, fylgir Lútherstrú og er miðflokksmaður."
+        "Nýr Loftslagsráðherra, Innviðaráðherra og Umhverfisráðherra er Afróasískur, talar Dravídamál, fylgir Lútherstrú og er miðflokksmaður.",
+        gc.settings,
     )
     g = list(g)
     if verbose:
         dump(g)
     s = normalize(g)
     assert "loftslagsráðherra" in s
     assert "innviðaráðherra" in s
@@ -652,15 +659,16 @@
     assert g[6].error_code == "Z001"  # umhverfisráðherra
     assert g[8].error_code == "Z001"  # afróasískur
     assert g[11].error_code == "Z001"  # dravídamál
     assert g[14].error_code == "Z001"  # lútherstrú
     assert g[17].error_code == "Z002"  # Miðflokksmaður
 
     g = rc.tokenize(
-        "Hann er Suðurkákasískur, tínir Unnarfald, býr í neðra-breiðholti og elskar Múmínálfa og óskarsverðlaunin."
+        "Hann er Suðurkákasískur, tínir Unnarfald, býr í neðra-breiðholti og elskar Múmínálfa og óskarsverðlaunin.",
+        gc.settings,
     )
     g = list(g)
     if verbose:
         dump(g)
     s = normalize(g)
     assert "suðurkákasískur" in s
     assert "unnarfald" in s
@@ -669,26 +677,29 @@
     assert "Óskarsverðlaunin" in s
     assert g[3].error_code == "Z001"  # suðurkákasískur
     assert g[6].error_code == "Z001"  # unnarfald
     assert g[10].error_code == "Z002"  # Neðra-Breiðholti
     assert g[13].error_code == "Z001"  # múmínálfa
     assert g[15].error_code == "Z002"  # Óskarsverðlaunin
 
-    g = rc.tokenize("Í Seinni Heimsstyrjöldinni gerðist meira en í Kalda Stríðinu.")
+    g = rc.tokenize(
+        "Í Seinni Heimsstyrjöldinni gerðist meira en í Kalda Stríðinu.", gc.settings
+    )
     g = list(g)
     if verbose:
         dump(g)
     s = normalize(g)
     assert "heimsstyrjöldinni" in s
     assert "stríðinu" in s
     assert g[3].error_code == "Z001"  # heimsstyrjöldinni
     assert g[9].error_code == "Z001"  # stríðinu
 
     g = rc.tokenize(
-        "Ég tala Víetnömsku, Indónesísku, er Afrísk-amerísk, karíbi, Karíbskur, austur-evrópubúi og vestur-evrópubúi"
+        "Ég tala Víetnömsku, Indónesísku, er Afrísk-amerísk, karíbi, Karíbskur, austur-evrópubúi og vestur-evrópubúi",
+        gc.settings,
     )
     g = list(g)
     if verbose:
         dump(g)
     s = normalize(g)
     assert "víetnömsku" in s
     assert "indónesísku" in s
@@ -1126,26 +1137,26 @@
         assert len(sent.annotations) == len(annotations)
         for a, (start, end, code) in zip(sent.annotations, annotations):
             assert a.start == start
             assert a.end == end
             assert a.code == code
 
     # Test check_single()
-    check_sent(rc.check_single(s))
+    check_sent(rc.check_single(s, gc))
     # Test check()
-    for pg in rc.check(s):
+    for pg in rc.check(s, gc):
         for sent in pg:
             check_sent(sent)
     # Test check_with_stats()
-    for pg in rc.check_with_stats(s)["paragraphs"]:
+    for pg in rc.check_with_stats(s, gc.settings)["paragraphs"]:
         for sent in pg:
             check_sent(sent)
 
     # Test presevation of original token text
-    tlist = list(rc.tokenize(s))
+    tlist = list(rc.tokenize(s, gc.settings))
     len_tokens = sum(len(t.original or "") for t in tlist)
     assert len_tokens == len(s)
 
 
 def test_NP_agreement(verbose=False):
     # Beygingarsamræmi
     # fjöldi X gerðu... P_NT_FjöldiHluti
@@ -1483,41 +1494,41 @@
 
 def test_compounds():
     s = "Ég hitti fjármála-og efnahagsráðherra."
     check_sentence(s, [(2, 2, "S005")])
 
 
 def test_styles():
-    a = rc.check_single("Spanendurnir afdjöfluðu á afarorðunum.")
+    a = rc.check_single("Spanendurnir afdjöfluðu á afarorðunum.", gc)
     assert len(a.annotations) == 3
     assert a.annotations[0].code == "Y001/w"
     assert "úrelt" in a.annotations[0].detail
     assert a.annotations[1].code == "Y001/w"
     assert "sjaldgæft" in a.annotations[1].detail
     assert a.annotations[2].code == "Y001/w"
     assert "úrelt" in a.annotations[2].detail
     a = rc.check_single(
-        "Jón átti höfundarétt og spaghetti fyrir sveitastjórnarkosningarnar."
+        "Jón átti höfundarétt og spaghetti fyrir sveitastjórnarkosningarnar.", gc
     )
     assert len(a.annotations) == 3
     assert a.annotations[0].code == "Y001/w"
     assert "villa" in a.annotations[0].detail
     assert "höfundarétt" in a.annotations[0].detail
     assert "spagettí" in a.annotations[1].text
     assert a.annotations[2].code == "Y001/w"
     assert "villa" in a.annotations[2].detail
     assert "sveitastjórnarkosningarnar" in a.annotations[2].detail
-    a = rc.check_single("Kamesið mitt er ferlega óhreint.")
+    a = rc.check_single("Kamesið mitt er ferlega óhreint.", gc)
     assert len(a.annotations) == 1
     assert a.annotations[0].code == "Y001/w"
     assert "úrelt" in a.annotations[0].detail
     assert "Kamesið" in a.annotations[0].detail
     assert "Kamersið" in a.annotations[0].detail
     assert a.annotations[0].suggest == "Kamersið"
-    a = rc.check_single("Páll kyngdi belgverska konfektinu.")
+    a = rc.check_single("Páll kyngdi belgverska konfektinu.", gc)
     assert len(a.annotations) == 1
     assert a.annotations[0].code == "Y001/w"
     assert "gamalt" in a.annotations[0].detail
     assert "belgverska" in a.annotations[0].detail
     assert "belgíska" in a.annotations[0].detail
     assert a.annotations[0].suggest == "belgíska"
```

### Comparing `reynir-correct-3.4.6/test/test_annotator.py` & `reynir-correct-3.4.7/test/test_annotator.py`

 * *Files 2% similar despite different names*

```diff
@@ -63,15 +63,17 @@
 
 import reynir_correct
 
 
 @pytest.fixture(scope="module")
 def rc():
     """Provide a module-scoped GreynirCorrect instance as a test fixture"""
-    r = reynir_correct.GreynirCorrect()
+    settings = reynir_correct.Settings()
+    settings.read("../reynir_correct/config/GreynirCorrect.conf")
+    r = reynir_correct.GreynirCorrect(settings)
     yield r
     # Do teardown here
     r.__class__.cleanup()
 
 
 def dump(tokens):
     print("\n{0} tokens:\n".format(len(tokens)))
@@ -127,26 +129,26 @@
                 assert a.code == code
 
     # Test check_single()
     sent = rc.parse_single(s)
     assert isinstance(sent, reynir_correct.AnnotatedSentence)
     check_sent(sent)
     # Test check()
-    for pg in reynir_correct.check(s):
+    for pg in reynir_correct.check(s, rc):
         for sent in pg:
             assert isinstance(sent, reynir_correct.AnnotatedSentence)
             check_sent(sent)
     # Test check_with_stats()
-    for pg in reynir_correct.check_with_stats(s)["paragraphs"]:
+    for pg in reynir_correct.check_with_stats(s, rc.settings)["paragraphs"]:
         for sent in pg:
             assert isinstance(sent, reynir_correct.AnnotatedSentence)
             check_sent(sent)
 
     # Test presevation of original token text
-    tlist = list(reynir_correct.tokenize(s))
+    tlist = list(reynir_correct.tokenize(s, rc.settings))
     len_tokens = sum(len(t.original or "") for t in tlist)
     assert len_tokens == len(s)
 
 
 def test_multiword_phrases(rc):
     s = "Einn af drengjunum fór í sund af gefnu tilefni."
     check_sentence(rc, s, [(6, 8, "P_afað")])
```

### Comparing `reynir-correct-3.4.6/test/test_patterns.py` & `reynir-correct-3.4.7/test/test_patterns.py`

 * *Files 2% similar despite different names*

```diff
@@ -40,15 +40,17 @@
 
 from test_annotator import check_sentence  # type: ignore
 
 
 @pytest.fixture(scope="module")
 def rc():
     """Provide a module-scoped GreynirCorrect instance as a test fixture"""
-    r = reynir_correct.GreynirCorrect()
+    settings = reynir_correct.Settings()
+    settings.read("../reynir_correct/config/GreynirCorrect.conf")
+    r = reynir_correct.GreynirCorrect(settings)
     yield r
     # Do teardown here
     r.__class__.cleanup()
 
 
 def test_verb_af(rc):
     s = "Ráðherrann dáðist af hugrekki stjórnarandstöðunnar."
@@ -336,15 +338,16 @@
     s = "Börnin voru inná vellinum allan daginn."
     check_sentence(rc, s, [(2, 3, "P_DIR_LOC"), (2, 2, "W001/w")])
     #    s = "Hann var oft upp á hestinum."
     #    check_sentence(rc, s, [(3, 5, "P_DIR_LOC")])
     s = "Málið liggur í augum upp."
     check_sentence(rc, s, [(2, 4, "P_DIR_LOC")])
     #    s = "Þau eru alltaf uppí bústað."
-    #    check_sentence(rc, s, [(1, 4, "P_DIR_LOC"), (3, 3, "W001/w")])     # Span is either 1,4 or 3,4 (depending on parsing), but always corrected.
+    #    check_sentence(rc, s, [(1, 4, "P_DIR_LOC"), (3, 3, "W001/w")])
+    # Span is either 1,4 or 3,4 (depending on parsing), but always corrected.
     s = "Hún var niður í bæ í gær."
     check_sentence(rc, s, [(1, 5, "P_DIR_LOC")])
     #    s = "Ég varð mér út um smá mat."
     #    check_sentence(rc, s, [(3, 6, "P_DIR_LOC")])
     #    s = "Þegar upp er staðið erum við öll eins."
     #    check_sentence(rc, s, [(1, 3, "P_DIR_LOC")])
     #    s = "Út í heimi er þetta öðruvísi."
```

### Comparing `reynir-correct-3.4.6/test/test_serializers.py` & `reynir-correct-3.4.7/test/test_serializers.py`

 * *Files 15% similar despite different names*

```diff
@@ -33,15 +33,20 @@
         "Það var 17. júní árið 2020 í frakklandi.",
         "Við sáum tvo seli og öruglega fleiri en 100 máva.",
         "Klukkan var orðinn tólf þegar við fórum heim.",
         "Bíllinn kostaði €30.000 en ég greyddi 25500 USD fyrir hann.",
         "morguninn eftir vakknaði ég kl. 07:30.",
         "Ég var firstur á fætur en þuríður Hálfdánardóttir var numer 2.",
     ]
-    gc = rc.GreynirCorrect()
+
+    # Global settings object for the tests
+    settings = rc.Settings()
+    settings.read("../reynir_correct/config/GreynirCorrect.conf")
+    gc = rc.GreynirCorrect(settings=settings)
+
     job = gc.submit(sents, parse=True)
     for pg in job.paragraphs():
         for sent in pg:
             assert sent.tree is not None
 
             json_str = gc.dumps_single(sent, indent=2)
             new = gc.loads_single(json_str)
@@ -49,13 +54,15 @@
             assert new.tree is not None
 
             assert sent.tokens == new.tokens
             assert sent.terminals == new.terminals
             assert sent.tree.flat_with_all_variants == new.tree.flat_with_all_variants
 
             cls = gc.__class__
-            assert json.loads(sent.dumps(cls, indent=2)) == json.loads(new.dumps(cls, indent=2))
+            assert json.loads(sent.dumps(cls, indent=2)) == json.loads(
+                new.dumps(cls, indent=2)
+            )
 
 
 if __name__ == "__main__":
     # When invoked as a main module, do a verbose test
     test_serializers()
```

### Comparing `reynir-correct-3.4.6/test/test_tokenizer.py` & `reynir-correct-3.4.7/test/test_tokenizer.py`

 * *Files 4% similar despite different names*

```diff
@@ -31,17 +31,24 @@
 
     This module tests the token-level error detection and correction
     of GreynirCorrect.
 
 """
 
 from typing import Iterable, cast
-import reynir_correct as rc
+import reynir_correct
 import tokenizer
 from reynir_correct.wrappers import test_spelling as check_errors
+import pytest
+
+
+# Global settings object for the tests
+settings = reynir_correct.Settings()
+settings.read("../reynir_correct/config/GreynirCorrect.conf")
+gc = reynir_correct.GreynirCorrect(settings=settings)
 
 
 def dump(tokens):
     print(
         "\n{1}\n{0} tokens:\n".format(
             len(tokens),
             tokenizer.correct_spaces(" ".join(t.txt for t in tokens if t.txt)),
@@ -55,27 +62,29 @@
 
 
 def gen_to_string(g):
     return tokenizer.correct_spaces(" ".join(t.txt for t in g if t.txt))
 
 
 def roundtrip(s: str) -> str:
-    return rc.detokenize(cast(Iterable[tokenizer.Tok], rc.tokenize(s)))
+    return reynir_correct.detokenize(
+        cast(Iterable[tokenizer.Tok], reynir_correct.tokenize(s))
+    )
 
 
 def check(p):
     """Return a corrected, normalized string form of the input along with the tokens"""
     options: Dict[str, Union[str, bool]] = {}
     options["spaced"] = False
     options["input"] = [p]
     options["one_sent"] = False
     options[
         "print_all"
     ] = True  # If input is many sentences, one string (and token list) for all
-    return check_errors(**options)
+    return check_errors(gc.settings, **options)
 
 
 def test_correct(verbose=False):
     """Test the spelling and grammar correction module"""
 
     s, g = check(
         "Kexið er gott báðumegin, sagði sagði Cthulhu og rak sig uppundir þakið. "
@@ -276,23 +285,25 @@
     assert s.startswith("Finnar ")
     assert "finnarnir" not in s
     assert "Finnarnir" in s
     assert "finnana" not in s
     assert "Finnana" in s
     assert "Finna" in s
 
+    # NOTE "Eskimói" has now been added to BÍN, and as an error in Storasnid_ord.csv, but not to Storasnid_ritm.csv.
+    # The latter is used as error vocabulary, the error information in the former is not read in BinPackage. This overrides our handling.
     s, g = check(
         "Gyðingurinn sagði að Lenínisminn tröllriði öllu en Eskimóinn taldi að "
         "það ætti fremur við um Marxismann en Sjítann."
     )
     assert s.startswith("Gyðingurinn ")
     assert "Lenínisminn" not in s
     assert "lenínisminn" in s
-    assert "Eskimóinn" not in s
-    assert "eskimóinn" in s
+    # assert "Eskimóinn" not in s
+    # assert "eskimóinn" in s
     assert "Sjítann" not in s
     assert "sjítann" in s
     assert "Marxismann" not in s
     assert "marxismann" in s
 
     s, g = check(
         "30. Desember á ég afmæli en ég held upp á það 20. JÚLÍ "
```


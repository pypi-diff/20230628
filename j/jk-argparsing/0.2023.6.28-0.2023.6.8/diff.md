# Comparing `tmp/jk_argparsing-0.2023.6.28.tar.gz` & `tmp/jk_argparsing-0.2023.6.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "jk_argparsing-0.2023.6.28.tar", last modified: Wed Jun 28 11:02:28 2023, max compression
+gzip compressed data, was "jk_argparsing-0.2023.6.8.tar", last modified: Thu Jun  8 12:11:21 2023, max compression
```

## Comparing `jk_argparsing-0.2023.6.28.tar` & `jk_argparsing-0.2023.6.8.tar`

### file list

```diff
@@ -1,48 +1,48 @@
-drwxrwx---   0 woodoo    (1000) woodoo    (1000)        0 2023-06-28 11:02:28.726412 jk_argparsing-0.2023.6.28/
--rw-r-----   0 woodoo    (1000) woodoo    (1000)    10173 2022-02-11 00:30:29.000000 jk_argparsing-0.2023.6.28/LICENSE.txt
--rw-r-----   0 woodoo    (1000) woodoo    (1000)       38 2023-02-08 17:48:11.000000 jk_argparsing-0.2023.6.28/MANIFEST.in
--rw-rw----   0 woodoo    (1000) woodoo    (1000)    14413 2023-06-28 11:02:28.726412 jk_argparsing-0.2023.6.28/PKG-INFO
--rw-r-----   0 woodoo    (1000) woodoo    (1000)    11551 2022-02-11 00:30:29.000000 jk_argparsing-0.2023.6.28/README.md
-drwxrwx---   0 woodoo    (1000) woodoo    (1000)        0 2023-06-28 11:02:28.722412 jk_argparsing-0.2023.6.28/jk_argparsing/
--rw-r-----   0 woodoo    (1000) woodoo    (1000)     3085 2021-05-31 06:40:42.000000 jk_argparsing-0.2023.6.28/jk_argparsing/ArgCommand.py
--rw-r-----   0 woodoo    (1000) woodoo    (1000)     6581 2023-06-28 06:37:34.000000 jk_argparsing-0.2023.6.28/jk_argparsing/ArgItemBase.py
--rw-r-----   0 woodoo    (1000) woodoo    (1000)     3223 2021-05-29 18:45:05.000000 jk_argparsing-0.2023.6.28/jk_argparsing/ArgOption.py
--rw-r-----   0 woodoo    (1000) woodoo    (1000)     1122 2021-03-07 10:14:55.000000 jk_argparsing-0.2023.6.28/jk_argparsing/ArgUtils.py
--rw-r-----   0 woodoo    (1000) woodoo    (1000)       97 2021-01-18 18:05:11.000000 jk_argparsing-0.2023.6.28/jk_argparsing/ArgsOptionDataDict.py
--rw-r-----   0 woodoo    (1000) woodoo    (1000)    29473 2023-06-08 12:10:08.000000 jk_argparsing-0.2023.6.28/jk_argparsing/ArgsParser.py
--rw-r-----   0 woodoo    (1000) woodoo    (1000)     8606 2023-02-08 17:44:23.000000 jk_argparsing-0.2023.6.28/jk_argparsing/AvailableLicenseList.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     7590 2021-09-10 09:13:40.000000 jk_argparsing-0.2023.6.28/jk_argparsing/BashCompletionLocal.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)      155 2021-05-29 18:32:56.000000 jk_argparsing-0.2023.6.28/jk_argparsing/EnumParameterType.py
--rw-r-----   0 woodoo    (1000) woodoo    (1000)     2989 2023-02-08 17:43:49.000000 jk_argparsing-0.2023.6.28/jk_argparsing/LicenseInfo.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     7935 2023-06-28 06:38:55.000000 jk_argparsing-0.2023.6.28/jk_argparsing/OptionParameter.py
--rw-r-----   0 woodoo    (1000) woodoo    (1000)     5230 2021-05-29 19:23:36.000000 jk_argparsing-0.2023.6.28/jk_argparsing/ParsedArgs.py
--rw-r-----   0 woodoo    (1000) woodoo    (1000)      169 2023-06-28 06:36:07.000000 jk_argparsing-0.2023.6.28/jk_argparsing/__init__.py
-drwxrwx---   0 woodoo    (1000) woodoo    (1000)        0 2023-06-28 11:02:28.722412 jk_argparsing-0.2023.6.28/jk_argparsing/impl/
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     1275 2022-02-10 23:49:48.000000 jk_argparsing-0.2023.6.28/jk_argparsing/impl/ImplementationErrorException.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)        2 2023-02-08 17:48:11.000000 jk_argparsing-0.2023.6.28/jk_argparsing/impl/__init__.py
-drwxrwx---   0 woodoo    (1000) woodoo    (1000)        0 2023-06-28 11:02:28.726412 jk_argparsing-0.2023.6.28/jk_argparsing/textmodel/
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     1337 2021-03-07 13:42:01.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textmodel/TBlock.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     1431 2022-02-11 00:05:20.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textmodel/TList.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     2322 2022-02-11 00:06:15.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textmodel/TSection.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     2209 2022-02-11 00:09:50.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textmodel/VisSettings.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)      123 2023-02-08 17:48:11.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textmodel/__init__.py
-drwxrwx---   0 woodoo    (1000) woodoo    (1000)        0 2023-06-28 11:02:28.726412 jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     2042 2021-03-07 14:46:56.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/ITextBlock.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     5111 2022-02-11 00:24:53.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/TextBlock.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     3135 2021-03-07 14:47:18.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/TextBlockSequence.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     3212 2021-03-07 14:47:26.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/TextColumnsBlock.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     1856 2021-03-07 14:47:32.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/TextEmpty.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     4845 2021-03-07 14:47:46.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/TextGridBlock.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     2317 2021-03-07 14:47:54.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/TextPrefixBlock.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     2840 2021-03-07 14:47:59.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/XLineFragment.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)      377 2023-02-08 17:48:11.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/__init__.py
--rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     1060 2021-03-07 11:59:59.000000 jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/columnLayouterL2R.py
-drwxrwx---   0 woodoo    (1000) woodoo    (1000)        0 2023-06-28 11:02:28.722412 jk_argparsing-0.2023.6.28/jk_argparsing.egg-info/
--rw-rw----   0 woodoo    (1000) woodoo    (1000)    14413 2023-06-28 11:02:28.000000 jk_argparsing-0.2023.6.28/jk_argparsing.egg-info/PKG-INFO
--rw-rw----   0 woodoo    (1000) woodoo    (1000)     1379 2023-06-28 11:02:28.000000 jk_argparsing-0.2023.6.28/jk_argparsing.egg-info/SOURCES.txt
--rw-rw----   0 woodoo    (1000) woodoo    (1000)        1 2023-06-28 11:02:28.000000 jk_argparsing-0.2023.6.28/jk_argparsing.egg-info/dependency_links.txt
--rw-rw----   0 woodoo    (1000) woodoo    (1000)        1 2023-02-09 06:11:13.000000 jk_argparsing-0.2023.6.28/jk_argparsing.egg-info/not-zip-safe
--rw-rw----   0 woodoo    (1000) woodoo    (1000)       23 2023-06-28 11:02:28.000000 jk_argparsing-0.2023.6.28/jk_argparsing.egg-info/requires.txt
--rw-rw----   0 woodoo    (1000) woodoo    (1000)       14 2023-06-28 11:02:28.000000 jk_argparsing-0.2023.6.28/jk_argparsing.egg-info/top_level.txt
--rw-rw----   0 woodoo    (1000) woodoo    (1000)       38 2023-06-28 11:02:28.726412 jk_argparsing-0.2023.6.28/setup.cfg
--rw-r-----   0 woodoo    (1000) woodoo    (1000)     1498 2023-06-28 06:36:07.000000 jk_argparsing-0.2023.6.28/setup.py
+drwxrwx---   0 woodoo    (1000) woodoo    (1000)        0 2023-06-08 12:11:21.257011 jk_argparsing-0.2023.6.8/
+-rw-r-----   0 woodoo    (1000) woodoo    (1000)    10173 2022-02-11 00:30:29.000000 jk_argparsing-0.2023.6.8/LICENSE.txt
+-rw-r-----   0 woodoo    (1000) woodoo    (1000)       38 2023-02-08 17:48:11.000000 jk_argparsing-0.2023.6.8/MANIFEST.in
+-rw-rw----   0 woodoo    (1000) woodoo    (1000)    14412 2023-06-08 12:11:21.257011 jk_argparsing-0.2023.6.8/PKG-INFO
+-rw-r-----   0 woodoo    (1000) woodoo    (1000)    11551 2022-02-11 00:30:29.000000 jk_argparsing-0.2023.6.8/README.md
+drwxrwx---   0 woodoo    (1000) woodoo    (1000)        0 2023-06-08 12:11:21.253011 jk_argparsing-0.2023.6.8/jk_argparsing/
+-rw-r-----   0 woodoo    (1000) woodoo    (1000)     3085 2021-05-31 06:40:42.000000 jk_argparsing-0.2023.6.8/jk_argparsing/ArgCommand.py
+-rw-r-----   0 woodoo    (1000) woodoo    (1000)     6519 2021-05-29 19:28:37.000000 jk_argparsing-0.2023.6.8/jk_argparsing/ArgItemBase.py
+-rw-r-----   0 woodoo    (1000) woodoo    (1000)     3223 2021-05-29 18:45:05.000000 jk_argparsing-0.2023.6.8/jk_argparsing/ArgOption.py
+-rw-r-----   0 woodoo    (1000) woodoo    (1000)     1122 2021-03-07 10:14:55.000000 jk_argparsing-0.2023.6.8/jk_argparsing/ArgUtils.py
+-rw-r-----   0 woodoo    (1000) woodoo    (1000)       97 2021-01-18 18:05:11.000000 jk_argparsing-0.2023.6.8/jk_argparsing/ArgsOptionDataDict.py
+-rw-r-----   0 woodoo    (1000) woodoo    (1000)    29473 2023-06-08 12:10:08.000000 jk_argparsing-0.2023.6.8/jk_argparsing/ArgsParser.py
+-rw-r-----   0 woodoo    (1000) woodoo    (1000)     8606 2023-02-08 17:44:23.000000 jk_argparsing-0.2023.6.8/jk_argparsing/AvailableLicenseList.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     7590 2021-09-10 09:13:40.000000 jk_argparsing-0.2023.6.8/jk_argparsing/BashCompletionLocal.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)      155 2021-05-29 18:32:56.000000 jk_argparsing-0.2023.6.8/jk_argparsing/EnumParameterType.py
+-rw-r-----   0 woodoo    (1000) woodoo    (1000)     2989 2023-02-08 17:43:49.000000 jk_argparsing-0.2023.6.8/jk_argparsing/LicenseInfo.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     7679 2021-05-29 19:25:20.000000 jk_argparsing-0.2023.6.8/jk_argparsing/OptionParameter.py
+-rw-r-----   0 woodoo    (1000) woodoo    (1000)     5230 2021-05-29 19:23:36.000000 jk_argparsing-0.2023.6.8/jk_argparsing/ParsedArgs.py
+-rw-r-----   0 woodoo    (1000) woodoo    (1000)      168 2023-06-08 12:10:28.000000 jk_argparsing-0.2023.6.8/jk_argparsing/__init__.py
+drwxrwx---   0 woodoo    (1000) woodoo    (1000)        0 2023-06-08 12:11:21.253011 jk_argparsing-0.2023.6.8/jk_argparsing/impl/
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     1275 2022-02-10 23:49:48.000000 jk_argparsing-0.2023.6.8/jk_argparsing/impl/ImplementationErrorException.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)        2 2023-02-08 17:48:11.000000 jk_argparsing-0.2023.6.8/jk_argparsing/impl/__init__.py
+drwxrwx---   0 woodoo    (1000) woodoo    (1000)        0 2023-06-08 12:11:21.257011 jk_argparsing-0.2023.6.8/jk_argparsing/textmodel/
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     1337 2021-03-07 13:42:01.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textmodel/TBlock.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     1431 2022-02-11 00:05:20.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textmodel/TList.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     2322 2022-02-11 00:06:15.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textmodel/TSection.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     2209 2022-02-11 00:09:50.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textmodel/VisSettings.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)      123 2023-02-08 17:48:11.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textmodel/__init__.py
+drwxrwx---   0 woodoo    (1000) woodoo    (1000)        0 2023-06-08 12:11:21.257011 jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     2042 2021-03-07 14:46:56.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/ITextBlock.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     5111 2022-02-11 00:24:53.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/TextBlock.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     3135 2021-03-07 14:47:18.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/TextBlockSequence.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     3212 2021-03-07 14:47:26.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/TextColumnsBlock.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     1856 2021-03-07 14:47:32.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/TextEmpty.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     4845 2021-03-07 14:47:46.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/TextGridBlock.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     2317 2021-03-07 14:47:54.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/TextPrefixBlock.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     2840 2021-03-07 14:47:59.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/XLineFragment.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)      377 2023-02-08 17:48:11.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/__init__.py
+-rw-rw-r--   0 woodoo    (1000) woodoo    (1000)     1060 2021-03-07 11:59:59.000000 jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/columnLayouterL2R.py
+drwxrwx---   0 woodoo    (1000) woodoo    (1000)        0 2023-06-08 12:11:21.253011 jk_argparsing-0.2023.6.8/jk_argparsing.egg-info/
+-rw-rw----   0 woodoo    (1000) woodoo    (1000)    14412 2023-06-08 12:11:21.000000 jk_argparsing-0.2023.6.8/jk_argparsing.egg-info/PKG-INFO
+-rw-rw----   0 woodoo    (1000) woodoo    (1000)     1379 2023-06-08 12:11:21.000000 jk_argparsing-0.2023.6.8/jk_argparsing.egg-info/SOURCES.txt
+-rw-rw----   0 woodoo    (1000) woodoo    (1000)        1 2023-06-08 12:11:21.000000 jk_argparsing-0.2023.6.8/jk_argparsing.egg-info/dependency_links.txt
+-rw-rw----   0 woodoo    (1000) woodoo    (1000)        1 2023-02-09 06:11:13.000000 jk_argparsing-0.2023.6.8/jk_argparsing.egg-info/not-zip-safe
+-rw-rw----   0 woodoo    (1000) woodoo    (1000)       23 2023-06-08 12:11:21.000000 jk_argparsing-0.2023.6.8/jk_argparsing.egg-info/requires.txt
+-rw-rw----   0 woodoo    (1000) woodoo    (1000)       14 2023-06-08 12:11:21.000000 jk_argparsing-0.2023.6.8/jk_argparsing.egg-info/top_level.txt
+-rw-rw----   0 woodoo    (1000) woodoo    (1000)       38 2023-06-08 12:11:21.257011 jk_argparsing-0.2023.6.8/setup.cfg
+-rw-r-----   0 woodoo    (1000) woodoo    (1000)     1497 2023-06-08 12:10:28.000000 jk_argparsing-0.2023.6.8/setup.py
```

### Comparing `jk_argparsing-0.2023.6.28/LICENSE.txt` & `jk_argparsing-0.2023.6.8/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/PKG-INFO` & `jk_argparsing-0.2023.6.8/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jk_argparsing
-Version: 0.2023.6.28
+Version: 0.2023.6.8
 Summary: A python module for parsing of program arguments.
 Home-page: UNKNOWN
 Author: Jürgen Knauth
 Author-email: pubsrc@binary-overflow.de
 License: Apache2
 Description: jk_argparsing
         =============
```

### Comparing `jk_argparsing-0.2023.6.28/README.md` & `jk_argparsing-0.2023.6.8/README.md`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/ArgCommand.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/ArgCommand.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/ArgItemBase.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/ArgItemBase.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-
+	
 
 
 import os
 import re
 import typing
 
 from .EnumParameterType import EnumParameterType
@@ -123,15 +123,14 @@
 	#
 
 	def expectDirectory(self,
 			displayName:str,
 			minLength:int = None,
 			maxLength:int = None,
 			mustExist:bool = False,
-			mustBeEmpty:bool = False,
 			toAbsolutePath:bool = False,
 			baseDir:str = None,
 		):
 
 		if self._canHaveNoMoreExpectations:
 			raise Exception("After a list argument no other arguments can be used!")
 
@@ -151,15 +150,14 @@
 		#if self._isShortOption:
 		#	raise Exception("Short options cannot have arguments!")
 
 		p = OptionParameter(displayName, self, EnumParameterType.Directory)
 		p.minLength = minLength
 		p.maxLength = maxLength
 		p.mustExist = mustExist
-		p.mustBeEmpty = mustBeEmpty
 		p.toAbsolutePath = toAbsolutePath
 		p.baseDir = baseDir
 		self._optionParameters.append(p)
 
 		return self
 	#
 
@@ -209,15 +207,15 @@
 		p.strRegEx = regex
 		self._optionParameters.append(p)
 
 		return self
 	#
 
 	def expectInt32(self,
-			displayName:str,
+			displayName,
 			minValue:int = None,
 			maxValue:int = None,
 		):
 
 		if self._canHaveNoMoreExpectations:
 			raise Exception("After a list argument no other arguments can be used!")
```

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/ArgOption.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/ArgOption.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/ArgUtils.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/ArgUtils.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/ArgsParser.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/ArgsParser.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/AvailableLicenseList.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/AvailableLicenseList.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/BashCompletionLocal.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/BashCompletionLocal.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/LicenseInfo.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/LicenseInfo.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/OptionParameter.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/OptionParameter.py`

 * *Files 5% similar despite different names*

```diff
@@ -33,29 +33,28 @@
 		self.minLength = None
 		self.maxLength = None
 		self.minValue = None
 		self.maxValue = None
 		self.strEnumValues = None
 		self.strRegEx = None
 		self.mustExist = None
-		self.mustBeEmpty = None
 		self.baseDir = None
 		self.toAbsolutePath = None
 	#
 
 
 	################################################################################################################################
 	## Public Properties
 	################################################################################################################################
 
 	################################################################################################################################
 	## Helper Methods
 	################################################################################################################################
 
-	def __parseFile(self, sinput:str) -> str:
+	def __parseFile(self, sinput):
 		assert isinstance(sinput, str)
 
 		if self.minLength is not None:
 			if len(sinput) < self.minLength:
 				raise Exception("Invalid argument value specified for option " + repr(str(self.option)) + ": " + repr(sinput))
 
 		if self.maxLength is not None:
@@ -70,15 +69,15 @@
 		if self.mustExist:
 			if not os.path.isfile(sinput):
 				raise Exception("File specified for option " + repr(str(self.option)) + " does not exist: " + repr(sinput))			# NEW FIX
 
 		return sinput
 	#
 
-	def __parseFileOrDirectory(self, sinput:str) -> str:
+	def __parseFileOrDirectory(self, sinput):
 		assert isinstance(sinput, str)
 
 		if self.minLength is not None:
 			if len(sinput) < self.minLength:
 				raise Exception("Invalid argument value specified for option " + repr(str(self.option)) + ": " + repr(sinput))
 
 		if self.maxLength is not None:
@@ -93,15 +92,15 @@
 		if self.mustExist:
 			if not os.path.exists(sinput):
 				raise Exception("File or directory specified for option " + repr(str(self.option)) + " does not exist: " + repr(sinput))
 
 		return sinput
 	#
 
-	def __parseDirectory(self, sinput:str) -> str:
+	def __parseDirectory(self, sinput):
 		assert isinstance(sinput, str)
 
 		if self.minLength is not None:
 			if len(sinput) < self.minLength:
 				raise Exception("Invalid argument value specified for option " + repr(str(self.option)) + ": " + repr(sinput))
 
 		if self.maxLength is not None:
@@ -113,22 +112,18 @@
 				sinput = os.path.join(self.baseDir, sinput)
 			sinput = os.path.abspath(sinput)
 
 		if self.mustExist:
 			if not os.path.isdir(sinput):
 				raise Exception("Directory specified for option " + repr(str(self.option)) + " does not exist: " + repr(sinput))
 
-		if self.mustBeEmpty:
-			if bool(os.listdir(sinput)):
-				raise Exception("Directory specified for option " + repr(str(self.option)) + " is not empty: " + repr(sinput))
-
 		return sinput
 	#
 
-	def __parseString(self, sinput:str) -> str:
+	def __parseString(self, sinput):
 		assert isinstance(sinput, str)
 
 		if self.strEnumValues is not None:
 			for v in self.strEnumValues:
 				if sinput == v:
 					return sinput
 			raise Exception("Invalid argument value specified for option " + repr(str(self.option)) + ": " + repr(sinput))
@@ -146,15 +141,15 @@
 			m = regex.match(sinput)
 			if m is None:
 				raise Exception("Invalid argument value specified for option " + repr(str(self.option)) + ": " + repr(sinput))
 
 		return sinput
 	#
 
-	def __parseInt32(self, sinput:str) -> int:
+	def __parseInt32(self, sinput):
 		try:
 			n = int(sinput)
 		except:
 			raise Exception("Argument is not a valid integer value at option " + repr(str(self.option)) + ": " + repr(sinput))
 
 		if self.minValue is not None:
 			if n < self.minValue:
@@ -168,15 +163,15 @@
 	################################################################################################################################
 	## Public Methods
 	################################################################################################################################
 
 	#
 	# This is the old version of the parsing method. This should be replaced by a new implementation, but right now this old version is still in use.
 	#
-	def parse(self, sinput:str):
+	def parse(self, sinput):
 		assert isinstance(sinput, str)
 
 		if self.type == EnumParameterType.String:
 			return self.__parseString(sinput)
 		elif self.type == EnumParameterType.Int32:
 			return self.__parseInt32(sinput)
 		elif self.type == EnumParameterType.File:
```

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/ParsedArgs.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/ParsedArgs.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/impl/ImplementationErrorException.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/impl/ImplementationErrorException.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/textmodel/TBlock.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/textmodel/TBlock.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/textmodel/TList.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/textmodel/TList.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/textmodel/TSection.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/textmodel/TSection.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/textmodel/VisSettings.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/textmodel/VisSettings.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/ITextBlock.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/ITextBlock.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/TextBlock.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/TextBlock.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/TextBlockSequence.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/TextBlockSequence.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/TextColumnsBlock.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/TextColumnsBlock.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/TextEmpty.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/TextEmpty.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/TextGridBlock.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/TextGridBlock.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/TextPrefixBlock.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/TextPrefixBlock.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/XLineFragment.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/XLineFragment.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing/textprimitives/columnLayouterL2R.py` & `jk_argparsing-0.2023.6.8/jk_argparsing/textprimitives/columnLayouterL2R.py`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing.egg-info/PKG-INFO` & `jk_argparsing-0.2023.6.8/jk_argparsing.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jk-argparsing
-Version: 0.2023.6.28
+Version: 0.2023.6.8
 Summary: A python module for parsing of program arguments.
 Home-page: UNKNOWN
 Author: Jürgen Knauth
 Author-email: pubsrc@binary-overflow.de
 License: Apache2
 Description: jk_argparsing
         =============
```

### Comparing `jk_argparsing-0.2023.6.28/jk_argparsing.egg-info/SOURCES.txt` & `jk_argparsing-0.2023.6.8/jk_argparsing.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `jk_argparsing-0.2023.6.28/setup.py` & `jk_argparsing-0.2023.6.8/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -45,12 +45,12 @@
 		"jk_argparsing",
 		"jk_argparsing.textmodel",
 		"jk_argparsing.textprimitives",
 		"jk_argparsing.impl",
 	],
 	scripts = [
 	],
-	version = '0.2023.6.28',
+	version = '0.2023.6.8',
 	zip_safe = False,
 	long_description = readme(),
 	long_description_content_type = "text/markdown",
 )
```


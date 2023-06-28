# Comparing `tmp/pyspartn-0.1.7.tar.gz` & `tmp/pyspartn-0.1.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyspartn-0.1.7.tar", last modified: Tue Jun  6 06:31:21 2023, max compression
+gzip compressed data, was "pyspartn-0.1.8.tar", last modified: Wed Jun 28 06:43:15 2023, max compression
```

## Comparing `pyspartn-0.1.7.tar` & `pyspartn-0.1.8.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 steve      (501) staff       (20)        0 2023-06-06 06:31:21.714692 pyspartn-0.1.7/
--rw-r--r--   0 steve      (501) staff       (20)     1613 2023-03-28 07:19:43.000000 pyspartn-0.1.7/LICENSE
--rw-r--r--   0 steve      (501) staff       (20)       64 2023-03-28 07:19:43.000000 pyspartn-0.1.7/MANIFEST.in
--rw-r--r--   0 steve      (501) staff       (20)    14381 2023-06-06 06:31:21.714522 pyspartn-0.1.7/PKG-INFO
--rw-r--r--   0 steve      (501) staff       (20)    11288 2023-06-06 06:30:11.000000 pyspartn-0.1.7/README.md
--rw-r--r--   0 steve      (501) staff       (20)     2445 2023-06-06 06:30:11.000000 pyspartn-0.1.7/pyproject.toml
--rw-r--r--   0 steve      (501) staff       (20)       38 2023-06-06 06:31:21.714735 pyspartn-0.1.7/setup.cfg
-drwxr-xr-x   0 steve      (501) staff       (20)        0 2023-06-06 06:31:21.706720 pyspartn-0.1.7/src/
-drwxr-xr-x   0 steve      (501) staff       (20)        0 2023-06-06 06:31:21.712929 pyspartn-0.1.7/src/pyspartn/
--rw-r--r--   0 steve      (501) staff       (20)      598 2023-06-06 06:30:11.000000 pyspartn-0.1.7/src/pyspartn/__init__.py
--rw-r--r--   0 steve      (501) staff       (20)      162 2023-06-06 06:30:11.000000 pyspartn-0.1.7/src/pyspartn/_version.py
--rw-r--r--   0 steve      (501) staff       (20)      671 2023-03-28 07:19:43.000000 pyspartn-0.1.7/src/pyspartn/exceptions.py
--rw-r--r--   0 steve      (501) staff       (20)     2465 2023-03-28 07:19:43.000000 pyspartn-0.1.7/src/pyspartn/socket_stream.py
--rw-r--r--   0 steve      (501) staff       (20)     6598 2023-06-06 06:30:11.000000 pyspartn-0.1.7/src/pyspartn/spartnhelpers.py
--rw-r--r--   0 steve      (501) staff       (20)    17676 2023-06-06 06:30:11.000000 pyspartn-0.1.7/src/pyspartn/spartnmessage.py
--rw-r--r--   0 steve      (501) staff       (20)     9141 2023-06-06 06:30:11.000000 pyspartn-0.1.7/src/pyspartn/spartnreader.py
--rw-r--r--   0 steve      (501) staff       (20)      222 2023-03-28 07:19:43.000000 pyspartn-0.1.7/src/pyspartn/spartntables.py
--rw-r--r--   0 steve      (501) staff       (20)     8642 2023-04-13 07:54:16.000000 pyspartn-0.1.7/src/pyspartn/spartntypes_core.py
--rw-r--r--   0 steve      (501) staff       (20)    18755 2023-06-06 06:30:11.000000 pyspartn-0.1.7/src/pyspartn/spartntypes_get.py
-drwxr-xr-x   0 steve      (501) staff       (20)        0 2023-06-06 06:31:21.713797 pyspartn-0.1.7/src/pyspartn.egg-info/
--rw-r--r--   0 steve      (501) staff       (20)    14381 2023-06-06 06:31:21.000000 pyspartn-0.1.7/src/pyspartn.egg-info/PKG-INFO
--rw-r--r--   0 steve      (501) staff       (20)      576 2023-06-06 06:31:21.000000 pyspartn-0.1.7/src/pyspartn.egg-info/SOURCES.txt
--rw-r--r--   0 steve      (501) staff       (20)        1 2023-06-06 06:31:21.000000 pyspartn-0.1.7/src/pyspartn.egg-info/dependency_links.txt
--rw-r--r--   0 steve      (501) staff       (20)      134 2023-06-06 06:31:21.000000 pyspartn-0.1.7/src/pyspartn.egg-info/requires.txt
--rw-r--r--   0 steve      (501) staff       (20)        9 2023-06-06 06:31:21.000000 pyspartn-0.1.7/src/pyspartn.egg-info/top_level.txt
-drwxr-xr-x   0 steve      (501) staff       (20)        0 2023-06-06 06:31:21.714254 pyspartn-0.1.7/tests/
--rw-r--r--   0 steve      (501) staff       (20)     4043 2023-03-28 07:19:43.000000 pyspartn-0.1.7/tests/test_socket.py
--rw-r--r--   0 steve      (501) staff       (20)     6054 2023-04-16 08:49:28.000000 pyspartn-0.1.7/tests/test_static.py
--rw-r--r--   0 steve      (501) staff       (20)    28728 2023-04-16 08:49:28.000000 pyspartn-0.1.7/tests/test_stream.py
+drwxr-xr-x   0 steve      (501) staff       (20)        0 2023-06-28 06:43:15.340652 pyspartn-0.1.8/
+-rw-r--r--   0 steve      (501) staff       (20)     1613 2023-03-28 07:19:43.000000 pyspartn-0.1.8/LICENSE
+-rw-r--r--   0 steve      (501) staff       (20)       64 2023-03-28 07:19:43.000000 pyspartn-0.1.8/MANIFEST.in
+-rw-r--r--   0 steve      (501) staff       (20)    16543 2023-06-28 06:43:15.340447 pyspartn-0.1.8/PKG-INFO
+-rw-r--r--   0 steve      (501) staff       (20)    13464 2023-06-28 06:39:26.000000 pyspartn-0.1.8/README.md
+-rw-r--r--   0 steve      (501) staff       (20)     2445 2023-06-28 06:39:26.000000 pyspartn-0.1.8/pyproject.toml
+-rw-r--r--   0 steve      (501) staff       (20)       38 2023-06-28 06:43:15.340717 pyspartn-0.1.8/setup.cfg
+drwxr-xr-x   0 steve      (501) staff       (20)        0 2023-06-28 06:43:15.335939 pyspartn-0.1.8/src/
+drwxr-xr-x   0 steve      (501) staff       (20)        0 2023-06-28 06:43:15.338664 pyspartn-0.1.8/src/pyspartn/
+-rw-r--r--   0 steve      (501) staff       (20)      598 2023-06-06 06:30:11.000000 pyspartn-0.1.8/src/pyspartn/__init__.py
+-rw-r--r--   0 steve      (501) staff       (20)      162 2023-06-28 06:39:26.000000 pyspartn-0.1.8/src/pyspartn/_version.py
+-rw-r--r--   0 steve      (501) staff       (20)      671 2023-03-28 07:19:43.000000 pyspartn-0.1.8/src/pyspartn/exceptions.py
+-rw-r--r--   0 steve      (501) staff       (20)     2441 2023-06-12 06:49:18.000000 pyspartn-0.1.8/src/pyspartn/socket_stream.py
+-rw-r--r--   0 steve      (501) staff       (20)     6991 2023-06-28 06:39:26.000000 pyspartn-0.1.8/src/pyspartn/spartnhelpers.py
+-rw-r--r--   0 steve      (501) staff       (20)    17920 2023-06-28 06:39:26.000000 pyspartn-0.1.8/src/pyspartn/spartnmessage.py
+-rw-r--r--   0 steve      (501) staff       (20)     9670 2023-06-28 06:39:26.000000 pyspartn-0.1.8/src/pyspartn/spartnreader.py
+-rw-r--r--   0 steve      (501) staff       (20)      222 2023-03-28 07:19:43.000000 pyspartn-0.1.8/src/pyspartn/spartntables.py
+-rw-r--r--   0 steve      (501) staff       (20)     8642 2023-04-13 07:54:16.000000 pyspartn-0.1.8/src/pyspartn/spartntypes_core.py
+-rw-r--r--   0 steve      (501) staff       (20)    18755 2023-06-06 06:30:11.000000 pyspartn-0.1.8/src/pyspartn/spartntypes_get.py
+drwxr-xr-x   0 steve      (501) staff       (20)        0 2023-06-28 06:43:15.339513 pyspartn-0.1.8/src/pyspartn.egg-info/
+-rw-r--r--   0 steve      (501) staff       (20)    16543 2023-06-28 06:43:15.000000 pyspartn-0.1.8/src/pyspartn.egg-info/PKG-INFO
+-rw-r--r--   0 steve      (501) staff       (20)      576 2023-06-28 06:43:15.000000 pyspartn-0.1.8/src/pyspartn.egg-info/SOURCES.txt
+-rw-r--r--   0 steve      (501) staff       (20)        1 2023-06-28 06:43:15.000000 pyspartn-0.1.8/src/pyspartn.egg-info/dependency_links.txt
+-rw-r--r--   0 steve      (501) staff       (20)      134 2023-06-28 06:43:15.000000 pyspartn-0.1.8/src/pyspartn.egg-info/requires.txt
+-rw-r--r--   0 steve      (501) staff       (20)        9 2023-06-28 06:43:15.000000 pyspartn-0.1.8/src/pyspartn.egg-info/top_level.txt
+drwxr-xr-x   0 steve      (501) staff       (20)        0 2023-06-28 06:43:15.340007 pyspartn-0.1.8/tests/
+-rw-r--r--   0 steve      (501) staff       (20)     4043 2023-03-28 07:19:43.000000 pyspartn-0.1.8/tests/test_socket.py
+-rw-r--r--   0 steve      (501) staff       (20)     5882 2023-06-28 06:39:26.000000 pyspartn-0.1.8/tests/test_static.py
+-rw-r--r--   0 steve      (501) staff       (20)    30348 2023-06-28 06:39:26.000000 pyspartn-0.1.8/tests/test_stream.py
```

### Comparing `pyspartn-0.1.7/LICENSE` & `pyspartn-0.1.8/LICENSE`

 * *Files identical despite different names*

### Comparing `pyspartn-0.1.7/PKG-INFO` & `pyspartn-0.1.8/PKG-INFO`

 * *Files 13% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyspartn
-Version: 0.1.7
+Version: 0.1.8
 Summary: SPARTN protocol parser
 Author-email: semuadmin <semuadmin@semuconsulting.com>
 Maintainer-email: semuadmin <semuadmin@semuconsulting.com>
 License: BSD 3-Clause License ("BSD License 2.0", "Revised BSD License", "New BSD License", or "Modified BSD License")
         
         Copyright (c) 2023, SEMU Consulting
         All rights reserved.
@@ -96,41 +96,41 @@
 ![Release Date](https://img.shields.io/github/release-date-pre/semuconsulting/pyspartn)
 ![Last Commit](https://img.shields.io/github/last-commit/semuconsulting/pyspartn)
 ![Contributors](https://img.shields.io/github/contributors/semuconsulting/pyspartn.svg)
 ![Open Issues](https://img.shields.io/github/issues-raw/semuconsulting/pyspartn)
 
 The `SPARTNReader` class is fully functional and is capable of parsing individual SPARTN transport-layer messages from a binary data stream containing *solely* SPARTN data, with their associated metadata (message type/subtype, payload length, encryption parameters, etc.).
 
-The `SPARTNMessage` class implements a provisional decrypt and decode for OCB, HPAC and GAD message types but it has not yet been fully tested (*appears to be working OK for HPAC messages*).
+The `SPARTNMessage` class implements a provisional decrypt and decode for OCB, HPAC and GAD message types but it has not yet been fully tested (*appears to be working OK for HPAC and GAD messages but issues remain with OCB payloads*).
 
 There are some additional complexities for messages where `timeTagtype` = 0. See https://portal.u-blox.com/s/question/0D52p0000CimfsOCQQ/spartn-initialization-vector-iv-details for discussion.
 
 Sphinx API Documentation in HTML format is available at [https://www.semuconsulting.com/pyspartn](https://www.semuconsulting.com/pyspartn).
 
 Contributions welcome - please refer to [CONTRIBUTING.MD](https://github.com/semuconsulting/pyspartn/blob/master/CONTRIBUTING.md).
 
 [Bug reports](https://github.com/semuconsulting/pyspartn/blob/master/.github/ISSUE_TEMPLATE/bug_report.md) and [Feature requests](https://github.com/semuconsulting/pyspartn/blob/master/.github/ISSUE_TEMPLATE/feature_request.md) - please use the templates provided.
 
 ---
 ## <a name="installation">Installation</a>
 
 `pyspartn` is compatible with Python >=3.8 and has no third-party library dependencies.
 
-In the following, `python` & `pip` refer to the Python 3 executables. You may need to type 
-`python3` or `pip3`, depending on your particular environment.
+In the following, `python3` & `pip` refer to the Python 3 executables. You may need to type 
+`python` or `pip3`, depending on your particular environment.
 
 ![Python version](https://img.shields.io/pypi/pyversions/pyspartn.svg?style=flat)
 [![PyPI version](https://img.shields.io/pypi/v/pyspartn)](https://pypi.org/project/pyspartn/)
 ![PyPI downloads](https://img.shields.io/pypi/dm/pyspartn.svg?style=flat)
 
 The recommended way to install the latest version of `pyspartn` is with
 [pip](http://pypi.python.org/pypi/pip/):
 
 ```shell
-python -m pip install --upgrade pyspartn
+python3 -m pip install --upgrade pyspartn
 ```
 
 If required, `pyspartn` can also be installed into a virtual environment, e.g.:
 
 ```shell
 python3 -m pip install --user --upgrade virtualenv
 python3 -m virtualenv env
@@ -182,27 +182,41 @@
 >>> spr = SPARTNReader(stream)
 >>> for (raw_data, parsed_data) in spr: print(parsed_data)
 ```
 
 ---
 ## <a name="parsing">Parsing</a>
 
-You can parse individual SPARTN messages using the static `SPARTNReader.parse(data)` function, which takes a bytes array containing a binary SPARTN message and returns a `SPARTNMessage` object. The optional `decode` keyword argument signifies whether to decrypt and decode the full payload (default = `False`). If `decode` is set to `True` and the message is encrypted (`eaf=1`), the decryption key must be provided via the `key` keyword argument - see example below.
+You can parse individual SPARTN messages using the static `SPARTNReader.parse(data)` function, which takes a bytes array containing a binary SPARTN message and returns a `SPARTNMessage` object. The optional `decode` keyword argument signifies whether to decrypt and decode the full payload (default = `False`). If `decode` is set to `True` and the message is encrypted (`eaf=1`), you *must* provide the following keyword arguments:
+- `key` - the current SPARTN decryption key as provided by your SPARTN service (normally 32 hexadecimal characters). 
+- `basedate` - a nominal datetime to be used where timeTagtype = 0 (16-bit gnssTimeTag format). This is needed by the decryption routine to determine the cryptographic Initialisation Vector (IV). If you're parsing messages in real time, this can default to `datetime.now()`. If you're parsing data from an older log, you will need to use the datetime the log was originally captured on. See examples below.
 
 **NB:** Once instantiated, a `SPARTNMMessage` object is immutable.
 
-Examples:
+Example - without payload decryption:
 
 ```python
 >>> from pyspartn import SPARTNReader
 >>> msg = SPARTNReader.parse(b"s\x00\x12\xe2\x00|\x10[\x12H\xf5\t\xa0\xb4+\x99\x02\x15\xe2\x05\x85\xb7\x83\xc5\xfd\x0f\xfe\xdf\x18\xbe\x7fv \xc3`\x82\x98\x10\x07\xdc\xeb\x82\x7f\xcf\xf8\x9e\xa3ta\xad", decode=False)
 >>> print(msg)
 <SPARTN(SPARTN-1X-OCB-GPS, msgType=0, msgSubtype=0, nData=37, eaf=1, crcType=2, frameCrc=2, timeTagtype=0, gnssTimeTag=3970, solutionId=5, solutionProcId=11)>
 ```
 
+Example - with payload decryption (requires key and, for messages where timeTagtype = 0, a nominal basedate for IV calculation):
+
+```python
+>>> from pyspartn import SPARTNReader
+>>> from datetime import datetime
+>>> msg = SPARTNReader.parse(b'\x73\x04\x19\x62\x03\xfa\x20\x5b\x1f\xc8\x31\x0b\x03\xd3\xa4\xb1\xdb\x79\x21\xcb\x5c\x27\x12\xa7\xa8\xc2\x52\xfd\x4a\xfb\x1a\x96\x3b\x64\x2a\x4e\xcd\x86\xbb\x31\x7c\x61\xde\xf5\xdb\x3d\xa3\x2c\x65\xd5\x05\x9f\x1c\xd9\x96\x47\x3b\xca\x13\x5e\x5e\x54\x80', decode=True, key="6b30302427df05b4d98911ebff3a4d95", basedate=datetime(2023,6,27,22,3,0))
+                                                                               
+>>> print(msg)
+<SPARTN(SPARTN-1X-GAD, msgType=2, nData=50, eaf=1, crcType=2, frameCrc=2, msgSubtype=0, timeTagtype=0, gnssTimeTag=32580, solutionId=5, solutionProcId=11, encryptionId=1, encryptionSeq=63, authInd=1, embAuthLen=0, crc=6182016, SF005=37, SF068=1, SF069=0, SF030=7, SF031_01=32, SF032_01=1332, SF033_01=1987, SF034_01=6, SF035_01=2, SF036_01=5, SF037_01=22, SF031_02=33, SF032_02=1332, SF033_02=2033, SF034_02=6, SF035_02=3, SF036_02=5, SF037_02=16, SF031_03=34, SF032_03=1301, SF033_03=1921, SF034_03=2, SF035_03=6, SF036_03=18, SF037_03=10, SF031_04=35, SF032_04=1297, SF033_04=1987, SF034_04=3, SF035_04=3, SF036_04=12, SF037_04=22, SF031_05=36, SF032_05=1448, SF033_05=1768, SF034_05=6, SF035_05=2, SF036_05=5, SF037_05=30, SF031_06=37, SF032_06=1391, SF033_06=1745, SF034_06=4, SF035_06=7, SF036_06=7, SF037_06=10, SF031_07=38, SF032_07=1360, SF033_07=1906, SF034_07=3, SF035_07=2, SF036_07=8, SF037_07=22)>
+```
+
+
 The `SPARTNMessage` object exposes different public attributes depending on its message type or 'identity'. SPARTN data fields are denoted `SFnnn` - use the `datadesc()` helper method to obtain a more user-friendly text description of the data field.
 
 ```python
 >>> from pyspartn import SPARTNReader, datadesc
 >>> msg = SPARTNReader.parse(b'\x73\x03\x35\xec\x08\xc7\xd4\x20\x70\x5b\x1f\xc ... \x1e\xbe\x18\x43\x2d\x57\xe7\xa7', decode=True, key="00112233445566778899aabbccddeeff")
 >>> print(msg)
 <SPARTN(SPARTN-1X-HPAC-GPS, msgType=1, nData=619, eaf=1, crcType=2, frameCrc=12, msgSubtype=0, timeTagtype=1, gnssTimeTag=419070990, solutionId=5, solutionProcId=11, encryptionId=1, encryptionSeq=63, authInd=1, embAuthLen=0, crc=5760935, SF005=508, SF068=1, SF069=0, SF030=9, SF031_01=0, SF039_01=0, SF040T_01=1, SF040I_01=1, SF041_01=1, SF042_01=2, SF043_01=127, SF044_01=1, SF048_01=213, SF049a_01=257, SF049b_01=253, SF054_01=1, SatBitmaskLen_01=0, SF011_01=70263185, SF055_01_01=6, SF056_01_01=1, SF060_01_01=8944, ... SF061b_09_08=8287)>
```

### Comparing `pyspartn-0.1.7/README.md` & `pyspartn-0.1.8/README.md`

 * *Files 15% similar despite different names*

```diff
@@ -35,41 +35,41 @@
 ![Release Date](https://img.shields.io/github/release-date-pre/semuconsulting/pyspartn)
 ![Last Commit](https://img.shields.io/github/last-commit/semuconsulting/pyspartn)
 ![Contributors](https://img.shields.io/github/contributors/semuconsulting/pyspartn.svg)
 ![Open Issues](https://img.shields.io/github/issues-raw/semuconsulting/pyspartn)
 
 The `SPARTNReader` class is fully functional and is capable of parsing individual SPARTN transport-layer messages from a binary data stream containing *solely* SPARTN data, with their associated metadata (message type/subtype, payload length, encryption parameters, etc.).
 
-The `SPARTNMessage` class implements a provisional decrypt and decode for OCB, HPAC and GAD message types but it has not yet been fully tested (*appears to be working OK for HPAC messages*).
+The `SPARTNMessage` class implements a provisional decrypt and decode for OCB, HPAC and GAD message types but it has not yet been fully tested (*appears to be working OK for HPAC and GAD messages but issues remain with OCB payloads*).
 
 There are some additional complexities for messages where `timeTagtype` = 0. See https://portal.u-blox.com/s/question/0D52p0000CimfsOCQQ/spartn-initialization-vector-iv-details for discussion.
 
 Sphinx API Documentation in HTML format is available at [https://www.semuconsulting.com/pyspartn](https://www.semuconsulting.com/pyspartn).
 
 Contributions welcome - please refer to [CONTRIBUTING.MD](https://github.com/semuconsulting/pyspartn/blob/master/CONTRIBUTING.md).
 
 [Bug reports](https://github.com/semuconsulting/pyspartn/blob/master/.github/ISSUE_TEMPLATE/bug_report.md) and [Feature requests](https://github.com/semuconsulting/pyspartn/blob/master/.github/ISSUE_TEMPLATE/feature_request.md) - please use the templates provided.
 
 ---
 ## <a name="installation">Installation</a>
 
 `pyspartn` is compatible with Python >=3.8 and has no third-party library dependencies.
 
-In the following, `python` & `pip` refer to the Python 3 executables. You may need to type 
-`python3` or `pip3`, depending on your particular environment.
+In the following, `python3` & `pip` refer to the Python 3 executables. You may need to type 
+`python` or `pip3`, depending on your particular environment.
 
 ![Python version](https://img.shields.io/pypi/pyversions/pyspartn.svg?style=flat)
 [![PyPI version](https://img.shields.io/pypi/v/pyspartn)](https://pypi.org/project/pyspartn/)
 ![PyPI downloads](https://img.shields.io/pypi/dm/pyspartn.svg?style=flat)
 
 The recommended way to install the latest version of `pyspartn` is with
 [pip](http://pypi.python.org/pypi/pip/):
 
 ```shell
-python -m pip install --upgrade pyspartn
+python3 -m pip install --upgrade pyspartn
 ```
 
 If required, `pyspartn` can also be installed into a virtual environment, e.g.:
 
 ```shell
 python3 -m pip install --user --upgrade virtualenv
 python3 -m virtualenv env
@@ -121,27 +121,41 @@
 >>> spr = SPARTNReader(stream)
 >>> for (raw_data, parsed_data) in spr: print(parsed_data)
 ```
 
 ---
 ## <a name="parsing">Parsing</a>
 
-You can parse individual SPARTN messages using the static `SPARTNReader.parse(data)` function, which takes a bytes array containing a binary SPARTN message and returns a `SPARTNMessage` object. The optional `decode` keyword argument signifies whether to decrypt and decode the full payload (default = `False`). If `decode` is set to `True` and the message is encrypted (`eaf=1`), the decryption key must be provided via the `key` keyword argument - see example below.
+You can parse individual SPARTN messages using the static `SPARTNReader.parse(data)` function, which takes a bytes array containing a binary SPARTN message and returns a `SPARTNMessage` object. The optional `decode` keyword argument signifies whether to decrypt and decode the full payload (default = `False`). If `decode` is set to `True` and the message is encrypted (`eaf=1`), you *must* provide the following keyword arguments:
+- `key` - the current SPARTN decryption key as provided by your SPARTN service (normally 32 hexadecimal characters). 
+- `basedate` - a nominal datetime to be used where timeTagtype = 0 (16-bit gnssTimeTag format). This is needed by the decryption routine to determine the cryptographic Initialisation Vector (IV). If you're parsing messages in real time, this can default to `datetime.now()`. If you're parsing data from an older log, you will need to use the datetime the log was originally captured on. See examples below.
 
 **NB:** Once instantiated, a `SPARTNMMessage` object is immutable.
 
-Examples:
+Example - without payload decryption:
 
 ```python
 >>> from pyspartn import SPARTNReader
 >>> msg = SPARTNReader.parse(b"s\x00\x12\xe2\x00|\x10[\x12H\xf5\t\xa0\xb4+\x99\x02\x15\xe2\x05\x85\xb7\x83\xc5\xfd\x0f\xfe\xdf\x18\xbe\x7fv \xc3`\x82\x98\x10\x07\xdc\xeb\x82\x7f\xcf\xf8\x9e\xa3ta\xad", decode=False)
 >>> print(msg)
 <SPARTN(SPARTN-1X-OCB-GPS, msgType=0, msgSubtype=0, nData=37, eaf=1, crcType=2, frameCrc=2, timeTagtype=0, gnssTimeTag=3970, solutionId=5, solutionProcId=11)>
 ```
 
+Example - with payload decryption (requires key and, for messages where timeTagtype = 0, a nominal basedate for IV calculation):
+
+```python
+>>> from pyspartn import SPARTNReader
+>>> from datetime import datetime
+>>> msg = SPARTNReader.parse(b'\x73\x04\x19\x62\x03\xfa\x20\x5b\x1f\xc8\x31\x0b\x03\xd3\xa4\xb1\xdb\x79\x21\xcb\x5c\x27\x12\xa7\xa8\xc2\x52\xfd\x4a\xfb\x1a\x96\x3b\x64\x2a\x4e\xcd\x86\xbb\x31\x7c\x61\xde\xf5\xdb\x3d\xa3\x2c\x65\xd5\x05\x9f\x1c\xd9\x96\x47\x3b\xca\x13\x5e\x5e\x54\x80', decode=True, key="6b30302427df05b4d98911ebff3a4d95", basedate=datetime(2023,6,27,22,3,0))
+                                                                               
+>>> print(msg)
+<SPARTN(SPARTN-1X-GAD, msgType=2, nData=50, eaf=1, crcType=2, frameCrc=2, msgSubtype=0, timeTagtype=0, gnssTimeTag=32580, solutionId=5, solutionProcId=11, encryptionId=1, encryptionSeq=63, authInd=1, embAuthLen=0, crc=6182016, SF005=37, SF068=1, SF069=0, SF030=7, SF031_01=32, SF032_01=1332, SF033_01=1987, SF034_01=6, SF035_01=2, SF036_01=5, SF037_01=22, SF031_02=33, SF032_02=1332, SF033_02=2033, SF034_02=6, SF035_02=3, SF036_02=5, SF037_02=16, SF031_03=34, SF032_03=1301, SF033_03=1921, SF034_03=2, SF035_03=6, SF036_03=18, SF037_03=10, SF031_04=35, SF032_04=1297, SF033_04=1987, SF034_04=3, SF035_04=3, SF036_04=12, SF037_04=22, SF031_05=36, SF032_05=1448, SF033_05=1768, SF034_05=6, SF035_05=2, SF036_05=5, SF037_05=30, SF031_06=37, SF032_06=1391, SF033_06=1745, SF034_06=4, SF035_06=7, SF036_06=7, SF037_06=10, SF031_07=38, SF032_07=1360, SF033_07=1906, SF034_07=3, SF035_07=2, SF036_07=8, SF037_07=22)>
+```
+
+
 The `SPARTNMessage` object exposes different public attributes depending on its message type or 'identity'. SPARTN data fields are denoted `SFnnn` - use the `datadesc()` helper method to obtain a more user-friendly text description of the data field.
 
 ```python
 >>> from pyspartn import SPARTNReader, datadesc
 >>> msg = SPARTNReader.parse(b'\x73\x03\x35\xec\x08\xc7\xd4\x20\x70\x5b\x1f\xc ... \x1e\xbe\x18\x43\x2d\x57\xe7\xa7', decode=True, key="00112233445566778899aabbccddeeff")
 >>> print(msg)
 <SPARTN(SPARTN-1X-HPAC-GPS, msgType=1, nData=619, eaf=1, crcType=2, frameCrc=12, msgSubtype=0, timeTagtype=1, gnssTimeTag=419070990, solutionId=5, solutionProcId=11, encryptionId=1, encryptionSeq=63, authInd=1, embAuthLen=0, crc=5760935, SF005=508, SF068=1, SF069=0, SF030=9, SF031_01=0, SF039_01=0, SF040T_01=1, SF040I_01=1, SF041_01=1, SF042_01=2, SF043_01=127, SF044_01=1, SF048_01=213, SF049a_01=257, SF049b_01=253, SF054_01=1, SatBitmaskLen_01=0, SF011_01=70263185, SF055_01_01=6, SF056_01_01=1, SF060_01_01=8944, ... SF061b_09_08=8287)>
```

### Comparing `pyspartn-0.1.7/pyproject.toml` & `pyspartn-0.1.8/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 authors = [
     {name = "semuadmin", email = "semuadmin@semuconsulting.com"},
 ]
 maintainers = [
   {name = "semuadmin", email = "semuadmin@semuconsulting.com"}
 ]
 description = "SPARTN protocol parser"
-version = "0.1.7"
+version = "0.1.8"
 license = {file = "LICENSE"}
 readme = "README.md"
 requires-python = ">=3.8"
 classifiers = [
     "Operating System :: OS Independent",
     "Development Status :: 2 - Pre-Alpha",
     "Environment :: MacOS X",
```

### Comparing `pyspartn-0.1.7/src/pyspartn/__init__.py` & `pyspartn-0.1.8/src/pyspartn/__init__.py`

 * *Files identical despite different names*

### Comparing `pyspartn-0.1.7/src/pyspartn/exceptions.py` & `pyspartn-0.1.8/src/pyspartn/exceptions.py`

 * *Files identical despite different names*

### Comparing `pyspartn-0.1.7/src/pyspartn/socket_stream.py` & `pyspartn-0.1.8/src/pyspartn/socket_stream.py`

 * *Files 1% similar despite different names*

```diff
@@ -42,16 +42,15 @@
         Read bytes from socket into internal buffer.
 
         :return: return code (0 = failure, 1 = success)
         :rtype: bool
         """
 
         try:
-            data = self._socket.recv(self._bufsize)
-            self._buffer += data
+            self._buffer += self._socket.recv(self._bufsize)
         except (OSError, TimeoutError):
             return False
         return True
 
     @property
     def buffer(self) -> bytearray:
         """
```

### Comparing `pyspartn-0.1.7/src/pyspartn/spartnhelpers.py` & `pyspartn-0.1.8/src/pyspartn/spartnhelpers.py`

 * *Files 10% similar despite different names*

```diff
@@ -6,15 +6,15 @@
 
 :author: semuadmin
 :copyright: SEMU Consulting © 2023
 :license: BSD 3-Clause
 """
 # pylint: disable=invalid-name
 
-from datetime import datetime
+from datetime import datetime, timedelta
 
 from cryptography.hazmat.primitives.ciphers import Cipher, algorithms, modes
 
 from pyspartn.exceptions import SPARTNMessageError
 from pyspartn.spartntypes_core import SPARTN_DATA_FIELDS, TIMEBASE
 
 
@@ -204,35 +204,41 @@
     :return: string of escaped bytes
     :rtype: str
     """
 
     return "b'{}'".format("".join(f"\\x{b:02x}" for b in val))
 
 
-def convert_timetag(timetag16: int, timetag32: int = None) -> int:
+def convert_timetag(timetag16: int, basedate: datetime = datetime.now()) -> int:
     """
     Convert 16-bit timetag to 32-bit format.
-    16-bit format = half days in seconds
-    32-bit format = total seconds since 2010-01-01
 
-    TODO it appears this may require the 32-bit timetag from an earlier SPARTN message
+    32-bit timetag format represents total seconds since TIMEBASE (2010-01-01).
+    16-bit timetag format represents seconds past nearest half day date. It
+    requires knowledge of the nearest half day date to convert unambiguously to
+    a 32-bit timetag equlvalent.
+
+    e.g. if nearest half day date is "2023-06-27 12:00:00", a timetag16
+    of 32580 represents "2023-06-27 00:00:00" + 12*3600 + 32580,
+    or "2023-06-20 21:03:00"
+    ("2023-06-20 21:03:00" - "2010-01-01 00:00:00") = 425595780 seconds
 
     :param int timetag16: 16-bit gnssTimeTag
-    :param int timetag32: 32-bit gnssTimeTag from external source (defaults to datetime.now())
+    :param int basedate: date to nearest half day (if none, will use today's date)
     :return: 32-bit gnssTimeTag
     :rtype: int
     """
 
-    if timetag32 is None:
-        time32 = (datetime.now() - TIMEBASE).total_seconds()
-    else:
-        time32 = timetag32
-    basis32 = time32 - (time32 % 43200)
-    timetag32 = timetag16 + basis32
-    return int(timetag32)
+    base16 = datetime(basedate.year, basedate.month, basedate.day, 0, 0, 0)
+    secs = timetag16
+    if basedate.hour >= 12:
+        secs += 43200
+    time16 = base16 + timedelta(seconds=secs)
+    timetag32 = int((time16 - TIMEBASE).total_seconds())
+    return timetag32
 
 
 def datadesc(datafield: str) -> str:
     """
     Get description of data field.
 
     :param str datafield: datafield e.g. 'SF054'
```

### Comparing `pyspartn-0.1.7/src/pyspartn/spartnmessage.py` & `pyspartn-0.1.8/src/pyspartn/spartnmessage.py`

 * *Files 4% similar despite different names*

```diff
@@ -10,14 +10,15 @@
 
 :author: semuadmin
 :copyright: SEMU Consulting © 2023
 :license: BSD 3-Clause
 """
 # pylint: disable=invalid-name too-many-instance-attributes
 
+from datetime import datetime
 from os import getenv
 
 from pyspartn.exceptions import (
     ParameterError,
     SPARTNMessageError,
     SPARTNParseError,
     SPARTNTypeError,
@@ -52,14 +53,15 @@
     def __init__(self, **kwargs):
         """
         Constructor.
 
         :param bytes transport: (kwarg) SPARTN message transport (None)
         :param bool decode: (kwarg) decrypt and decode payloads (False)
         :param str key: (kwarg) decryption key as hexadecimal string (None)
+        :param datetime basedate: (kwarg) basedate for 16-bit gnssTimeTag (today's date)
         :param bool validate: (kwarg) validate CRC (True)
         :param bool scaling: (kwarg) apply attribute scaling factors (True)
         :raises: ParameterError if invalid parameters
         """
 
         # object is mutable during initialisation only
         super().__setattr__("_immutable", False)
@@ -72,14 +74,17 @@
         self._preamble = bitsval(self._transport, 0, 8)
         if self._preamble != SPARTN_PRE:  # not SPARTN
             raise SPARTNParseError(f"Unknown message preamble {self._preamble}")
 
         self._scaling = kwargs.get("scaling", False)
         self._decode = kwargs.get("decode", False)
         key = kwargs.get("key", getenv("MQTTKEY", None))  # 128-bit key
+        self._basedate = kwargs.get(
+            "basedate", datetime.now()
+        )  # basedate for 16-bit gnssTimeTag
         if key is None:
             self._key = None
         else:
             self._key = bytes.fromhex(key)
         self._iv = None
 
         if self._decode and self._key is None:
@@ -185,16 +190,16 @@
 
         :return: IV as bytes
         :rtype: bytes
         """
 
         if self.timeTagtype:  # 32-bits
             timeTag = self.gnssTimeTag
-        else:  # Convert 16-bit timetag to 32 bits (WHY???!!!)
-            timeTag = convert_timetag(self.gnssTimeTag)
+        else:  # Convert 16-bit timetag to 32 bits
+            timeTag = convert_timetag(self.gnssTimeTag, self._basedate)
 
         iv = (
             (self.msgType << 121)  # TF002 7 bits
             + (self.nData << 111)  # TF003 10 bits
             + (self.msgSubtype << 107)  # TF007 4 bits
             + (timeTag << 75)  # TF009 32 bits
             + (self.solutionId << 68)  # TF010 7 bits
```

### Comparing `pyspartn-0.1.7/src/pyspartn/spartnreader.py` & `pyspartn-0.1.8/src/pyspartn/spartnreader.py`

 * *Files 8% similar despite different names*

```diff
@@ -21,14 +21,15 @@
 
 :author: semuadmin
 :copyright: SEMU Consulting © 2023
 :license: BSD 3-Clause
 """
 # pylint: disable=invalid-name too-many-instance-attributes
 
+from datetime import datetime
 from os import getenv
 from socket import socket
 
 from pyspartn.exceptions import (
     ParameterError,
     SPARTNMessageError,
     SPARTNParseError,
@@ -47,14 +48,15 @@
 
     def __init__(self, datastream, **kwargs):
         """Constructor.
 
         :param datastream stream: input data stream
         :param bool decode: (kwarg) decrypt and decode payload (False)
         :param str key: (kwarg) decryption key as hexadecimal string (None)
+        :param datetime basedate: (kwarg) basedate for 16-bit gnssTimeTag (today's date)
         :param int quitonerror: (kwarg) 0 = ignore,  1 = log and continue, 2 = (re)raise (1)
         :param int errorhandler: (kwarg) error handling object or function (None)
         :param int validate: (kwarg) 0 = ignore invalid CRC, 1 = validate CRC (1)
         :param bool scaling: (kwarg) apply attribute scaling True/False (True)
         :param int bufsize: (kwarg) socket recv buffer size (4096)
         :raises: SPARTNStreamError (if mode is invalid)
         """
@@ -65,14 +67,17 @@
         else:
             self._stream = datastream
         self._validate = int(kwargs.get("validate", VALCRC))
         self._quitonerror = int(kwargs.get("quitonerror", ERRLOG))
         self._errorhandler = kwargs.get("errorhandler", None)
         self._decode = kwargs.get("decode", False)
         self._key = kwargs.get("key", getenv("MQTTKEY", None))  # 128-bit key
+        self._basedate = kwargs.get(
+            "basedate", datetime.now()
+        )  # basedate for 16-bit gnssTimeTag
 
         if self._decode and self._key is None:
             raise ParameterError("Key must be provided if decoding is enabled")
 
     def __iter__(self):
         """Iterator."""
 
@@ -187,15 +192,19 @@
         core = framestart + payDesc + payload + embAuth
         raw_data = preamble + core + crcb
         if self._validate & VALCRC:
             if not valid_crc(core, crc, crcType):
                 raise SPARTNParseError(f"Invalid CRC {crc}")
 
         parsed_data = self.parse(
-            raw_data, validate=self._validate, decode=self._decode, key=self._key
+            raw_data,
+            validate=self._validate,
+            decode=self._decode,
+            key=self._key,
+            basedate=self._basedate,
         )
         return (raw_data, parsed_data)
 
     def _read_bytes(self, size: int) -> bytes:
         """
         Read a specified number of bytes from stream.
 
@@ -243,22 +252,28 @@
         """
         Parse SPARTN message to SPARTNMessage object.
 
         :param bytes message: SPARTN raw message bytes
         :param int validate: (kwarg) 0 = ignore invalid CRC, 1 = validate CRC (1)
         :param int decode: (kwarg) decode payload True/False
         :param str key: (kwarg) decryption key (required if decode = 1)
+        :param datetime basedate: (kwarg) basedate for 16-bit gnssTimeTag (today's date)
         :return: SPARTNMessage object
         :rtype: SPARTNMessage
         :raises: SPARTN...Error (if data stream contains invalid data or unknown message type)
         """
         # pylint: disable=unused-argument
 
         validate = int(kwargs.get("validate", VALCRC))
         decode = kwargs.get("decode", False)
         key = kwargs.get("key", None)
+        basedate = kwargs.get("basedate", datetime.now())
         if decode and key is None:
             raise ParameterError("Key must be provided if decoding is enabled")
 
         return SPARTNMessage(
-            transport=message, decode=decode, key=key, validate=validate
+            transport=message,
+            decode=decode,
+            key=key,
+            basedate=basedate,
+            validate=validate,
         )
```

### Comparing `pyspartn-0.1.7/src/pyspartn/spartntypes_core.py` & `pyspartn-0.1.8/src/pyspartn/spartntypes_core.py`

 * *Files identical despite different names*

### Comparing `pyspartn-0.1.7/src/pyspartn/spartntypes_get.py` & `pyspartn-0.1.8/src/pyspartn/spartntypes_get.py`

 * *Files identical despite different names*

### Comparing `pyspartn-0.1.7/src/pyspartn.egg-info/PKG-INFO` & `pyspartn-0.1.8/src/pyspartn.egg-info/PKG-INFO`

 * *Files 13% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyspartn
-Version: 0.1.7
+Version: 0.1.8
 Summary: SPARTN protocol parser
 Author-email: semuadmin <semuadmin@semuconsulting.com>
 Maintainer-email: semuadmin <semuadmin@semuconsulting.com>
 License: BSD 3-Clause License ("BSD License 2.0", "Revised BSD License", "New BSD License", or "Modified BSD License")
         
         Copyright (c) 2023, SEMU Consulting
         All rights reserved.
@@ -96,41 +96,41 @@
 ![Release Date](https://img.shields.io/github/release-date-pre/semuconsulting/pyspartn)
 ![Last Commit](https://img.shields.io/github/last-commit/semuconsulting/pyspartn)
 ![Contributors](https://img.shields.io/github/contributors/semuconsulting/pyspartn.svg)
 ![Open Issues](https://img.shields.io/github/issues-raw/semuconsulting/pyspartn)
 
 The `SPARTNReader` class is fully functional and is capable of parsing individual SPARTN transport-layer messages from a binary data stream containing *solely* SPARTN data, with their associated metadata (message type/subtype, payload length, encryption parameters, etc.).
 
-The `SPARTNMessage` class implements a provisional decrypt and decode for OCB, HPAC and GAD message types but it has not yet been fully tested (*appears to be working OK for HPAC messages*).
+The `SPARTNMessage` class implements a provisional decrypt and decode for OCB, HPAC and GAD message types but it has not yet been fully tested (*appears to be working OK for HPAC and GAD messages but issues remain with OCB payloads*).
 
 There are some additional complexities for messages where `timeTagtype` = 0. See https://portal.u-blox.com/s/question/0D52p0000CimfsOCQQ/spartn-initialization-vector-iv-details for discussion.
 
 Sphinx API Documentation in HTML format is available at [https://www.semuconsulting.com/pyspartn](https://www.semuconsulting.com/pyspartn).
 
 Contributions welcome - please refer to [CONTRIBUTING.MD](https://github.com/semuconsulting/pyspartn/blob/master/CONTRIBUTING.md).
 
 [Bug reports](https://github.com/semuconsulting/pyspartn/blob/master/.github/ISSUE_TEMPLATE/bug_report.md) and [Feature requests](https://github.com/semuconsulting/pyspartn/blob/master/.github/ISSUE_TEMPLATE/feature_request.md) - please use the templates provided.
 
 ---
 ## <a name="installation">Installation</a>
 
 `pyspartn` is compatible with Python >=3.8 and has no third-party library dependencies.
 
-In the following, `python` & `pip` refer to the Python 3 executables. You may need to type 
-`python3` or `pip3`, depending on your particular environment.
+In the following, `python3` & `pip` refer to the Python 3 executables. You may need to type 
+`python` or `pip3`, depending on your particular environment.
 
 ![Python version](https://img.shields.io/pypi/pyversions/pyspartn.svg?style=flat)
 [![PyPI version](https://img.shields.io/pypi/v/pyspartn)](https://pypi.org/project/pyspartn/)
 ![PyPI downloads](https://img.shields.io/pypi/dm/pyspartn.svg?style=flat)
 
 The recommended way to install the latest version of `pyspartn` is with
 [pip](http://pypi.python.org/pypi/pip/):
 
 ```shell
-python -m pip install --upgrade pyspartn
+python3 -m pip install --upgrade pyspartn
 ```
 
 If required, `pyspartn` can also be installed into a virtual environment, e.g.:
 
 ```shell
 python3 -m pip install --user --upgrade virtualenv
 python3 -m virtualenv env
@@ -182,27 +182,41 @@
 >>> spr = SPARTNReader(stream)
 >>> for (raw_data, parsed_data) in spr: print(parsed_data)
 ```
 
 ---
 ## <a name="parsing">Parsing</a>
 
-You can parse individual SPARTN messages using the static `SPARTNReader.parse(data)` function, which takes a bytes array containing a binary SPARTN message and returns a `SPARTNMessage` object. The optional `decode` keyword argument signifies whether to decrypt and decode the full payload (default = `False`). If `decode` is set to `True` and the message is encrypted (`eaf=1`), the decryption key must be provided via the `key` keyword argument - see example below.
+You can parse individual SPARTN messages using the static `SPARTNReader.parse(data)` function, which takes a bytes array containing a binary SPARTN message and returns a `SPARTNMessage` object. The optional `decode` keyword argument signifies whether to decrypt and decode the full payload (default = `False`). If `decode` is set to `True` and the message is encrypted (`eaf=1`), you *must* provide the following keyword arguments:
+- `key` - the current SPARTN decryption key as provided by your SPARTN service (normally 32 hexadecimal characters). 
+- `basedate` - a nominal datetime to be used where timeTagtype = 0 (16-bit gnssTimeTag format). This is needed by the decryption routine to determine the cryptographic Initialisation Vector (IV). If you're parsing messages in real time, this can default to `datetime.now()`. If you're parsing data from an older log, you will need to use the datetime the log was originally captured on. See examples below.
 
 **NB:** Once instantiated, a `SPARTNMMessage` object is immutable.
 
-Examples:
+Example - without payload decryption:
 
 ```python
 >>> from pyspartn import SPARTNReader
 >>> msg = SPARTNReader.parse(b"s\x00\x12\xe2\x00|\x10[\x12H\xf5\t\xa0\xb4+\x99\x02\x15\xe2\x05\x85\xb7\x83\xc5\xfd\x0f\xfe\xdf\x18\xbe\x7fv \xc3`\x82\x98\x10\x07\xdc\xeb\x82\x7f\xcf\xf8\x9e\xa3ta\xad", decode=False)
 >>> print(msg)
 <SPARTN(SPARTN-1X-OCB-GPS, msgType=0, msgSubtype=0, nData=37, eaf=1, crcType=2, frameCrc=2, timeTagtype=0, gnssTimeTag=3970, solutionId=5, solutionProcId=11)>
 ```
 
+Example - with payload decryption (requires key and, for messages where timeTagtype = 0, a nominal basedate for IV calculation):
+
+```python
+>>> from pyspartn import SPARTNReader
+>>> from datetime import datetime
+>>> msg = SPARTNReader.parse(b'\x73\x04\x19\x62\x03\xfa\x20\x5b\x1f\xc8\x31\x0b\x03\xd3\xa4\xb1\xdb\x79\x21\xcb\x5c\x27\x12\xa7\xa8\xc2\x52\xfd\x4a\xfb\x1a\x96\x3b\x64\x2a\x4e\xcd\x86\xbb\x31\x7c\x61\xde\xf5\xdb\x3d\xa3\x2c\x65\xd5\x05\x9f\x1c\xd9\x96\x47\x3b\xca\x13\x5e\x5e\x54\x80', decode=True, key="6b30302427df05b4d98911ebff3a4d95", basedate=datetime(2023,6,27,22,3,0))
+                                                                               
+>>> print(msg)
+<SPARTN(SPARTN-1X-GAD, msgType=2, nData=50, eaf=1, crcType=2, frameCrc=2, msgSubtype=0, timeTagtype=0, gnssTimeTag=32580, solutionId=5, solutionProcId=11, encryptionId=1, encryptionSeq=63, authInd=1, embAuthLen=0, crc=6182016, SF005=37, SF068=1, SF069=0, SF030=7, SF031_01=32, SF032_01=1332, SF033_01=1987, SF034_01=6, SF035_01=2, SF036_01=5, SF037_01=22, SF031_02=33, SF032_02=1332, SF033_02=2033, SF034_02=6, SF035_02=3, SF036_02=5, SF037_02=16, SF031_03=34, SF032_03=1301, SF033_03=1921, SF034_03=2, SF035_03=6, SF036_03=18, SF037_03=10, SF031_04=35, SF032_04=1297, SF033_04=1987, SF034_04=3, SF035_04=3, SF036_04=12, SF037_04=22, SF031_05=36, SF032_05=1448, SF033_05=1768, SF034_05=6, SF035_05=2, SF036_05=5, SF037_05=30, SF031_06=37, SF032_06=1391, SF033_06=1745, SF034_06=4, SF035_06=7, SF036_06=7, SF037_06=10, SF031_07=38, SF032_07=1360, SF033_07=1906, SF034_07=3, SF035_07=2, SF036_07=8, SF037_07=22)>
+```
+
+
 The `SPARTNMessage` object exposes different public attributes depending on its message type or 'identity'. SPARTN data fields are denoted `SFnnn` - use the `datadesc()` helper method to obtain a more user-friendly text description of the data field.
 
 ```python
 >>> from pyspartn import SPARTNReader, datadesc
 >>> msg = SPARTNReader.parse(b'\x73\x03\x35\xec\x08\xc7\xd4\x20\x70\x5b\x1f\xc ... \x1e\xbe\x18\x43\x2d\x57\xe7\xa7', decode=True, key="00112233445566778899aabbccddeeff")
 >>> print(msg)
 <SPARTN(SPARTN-1X-HPAC-GPS, msgType=1, nData=619, eaf=1, crcType=2, frameCrc=12, msgSubtype=0, timeTagtype=1, gnssTimeTag=419070990, solutionId=5, solutionProcId=11, encryptionId=1, encryptionSeq=63, authInd=1, embAuthLen=0, crc=5760935, SF005=508, SF068=1, SF069=0, SF030=9, SF031_01=0, SF039_01=0, SF040T_01=1, SF040I_01=1, SF041_01=1, SF042_01=2, SF043_01=127, SF044_01=1, SF048_01=213, SF049a_01=257, SF049b_01=253, SF054_01=1, SatBitmaskLen_01=0, SF011_01=70263185, SF055_01_01=6, SF056_01_01=1, SF060_01_01=8944, ... SF061b_09_08=8287)>
```

### Comparing `pyspartn-0.1.7/src/pyspartn.egg-info/SOURCES.txt` & `pyspartn-0.1.8/src/pyspartn.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pyspartn-0.1.7/tests/test_socket.py` & `pyspartn-0.1.8/tests/test_socket.py`

 * *Files identical despite different names*

### Comparing `pyspartn-0.1.7/tests/test_static.py` & `pyspartn-0.1.8/tests/test_static.py`

 * *Files 12% similar despite different names*

```diff
@@ -91,21 +91,18 @@
         pt = decrypt(ct, key, iv, "CTR")
         self.assertEqual(msg, pt[0:-pad])
         ct, pad = encrypt(msg, key, iv, "CBC")
         pt = decrypt(ct, key, iv, "CBC")
         self.assertEqual(msg, pt[0:-pad])
 
     def testtimetag(self):
-        timetag32 = (datetime(2023, 3, 14) - TIMEBASE).total_seconds()
-        EXPECTED_SECS = 416451490
-        EXPECTED_DATE = datetime(2023, 3, 14, 0, 58, 10)
-        res = convert_timetag(3490, timetag32)
-        self.assertEqual(res, EXPECTED_SECS)
-        dat = TIMEBASE + timedelta(seconds=res)
-        self.assertEqual(dat, EXPECTED_DATE)
+        basedate = datetime(2023, 6, 27, 23, 13, 0)
+        EXPECTED_RES = 425595780
+        res = convert_timetag(32580, basedate)
+        self.assertEqual(res, EXPECTED_RES)
 
     def testiv(self):
         IV32 = "031800c03cb4306c2b40000000000001"
         IV16 = "001400c03cb4586c2580000000000001"
 
         msgType = 0  # 1
         nData = 40  # 560
@@ -171,10 +168,11 @@
 
     def testdatadesc(self):  # test datadesc
         res = datadesc("SF054")
         self.assertEqual(res, "Ionosphere equation type")
         res = datadesc("SF043_01")
         self.assertEqual(res, "Area average vertical hydrostatic delay")
 
+
 if __name__ == "__main__":
     # import sys;sys.argv = ['', 'Test.testName']
     unittest.main()
```

### Comparing `pyspartn-0.1.7/tests/test_stream.py` & `pyspartn-0.1.8/tests/test_stream.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,20 +5,22 @@
 @author: semuadmin
 """
 
 import os
 import sys
 import unittest
 from io import StringIO
+from datetime import datetime
 
 from pyspartn.exceptions import SPARTNMessageError, SPARTNParseError, ParameterError
 from pyspartn.spartnreader import SPARTNReader, SPARTNMessage
 from pyspartn.spartntypes_core import ERRRAISE, ERRIGNORE, ERRLOG
 
-SPARTNKEY = "0d1472ea83e351d8b24632ed42f0cee2"
+SPARTNKEY_HPAC = "0d1472ea83e351d8b24632ed42f0cee2"
+SPARTNKEY_GAD = "6b30302427df05b4d98911ebff3a4d95"
 
 
 class StreamTest(unittest.TestCase):
     def setUp(self):
         self.maxDiff = None
         self.dirname = os.path.dirname(__file__)
         self.streamSPARTN = open(os.path.join(self.dirname, "spartn_mqtt.log"), "rb")
@@ -149,15 +151,15 @@
     def testpayloadgetter(self):  # test decrypted payload property
         EXPECTED_RESULT = b"\xfe\x09\x20\x00\x14\xa7\xfb\x56\x02\xfd\x20\x21\x81\x0c\x8b\x62\xf0\x82\xaa\x00\xf5\xc9\x49\x06\x3c\x00\x2b\x85\xea\x0e\xa8\x07\xdb\x20\x94\x03\xef\xfb\x36\x61\x08\x77\x20\x43\x5c\x35\x70\x76\x40\x68\x98\xb5\x20\x78\x81\x71\x31\x79\x41\x69\x03\x08\x08\x05\x29\xfe\xd9\x7e\xbf\x48\x08\x60\x43\x22\xd8\xa0\x20\x82\x7f\xf9\xf2\x13\xc2\x1a\xff\x23\x60\xc0\x83\x12\x01\xb5\xc7\xef\x02\x73\xfe\xab\x92\xf6\x15\x68\x0a\x97\x06\xd4\x19\xd0\x16\xa6\x1f\xd8\x29\xe0\x5b\x5c\x3e\x70\x74\x40\xbe\x04\x01\x49\x7f\xb4\x60\x2f\xf2\x02\x18\x10\xc8\x8e\x29\x68\x2c\x60\x0d\x2c\x80\xf0\x87\x40\x0e\x58\x43\xa0\xa6\x80\xc9\x31\xf7\x40\x6d\x00\x29\xe5\x31\x85\xf2\x02\x83\xc2\x87\x05\xf4\x07\xa5\x8b\x16\x09\xa8\x1a\x8f\x15\xb4\x1a\xd0\x38\x01\x80\x52\x5f\xed\x88\x0c\x08\x80\x86\x04\x32\x29\x89\xb9\xf7\x98\x05\x93\x1e\x3c\x02\x70\x06\x1e\x07\xf7\xf6\xe0\x21\x4c\x80\xef\xa7\x40\x18\xb9\x0e\x60\x77\x80\x84\x70\x3e\x3f\x9f\x01\xf1\x61\x82\x7f\x96\x06\x52\xc2\xfc\xfd\x7c\x0c\x60\x80\x14\x97\xfb\x51\xf8\xfc\x20\x21\x81\x0c\x88\xe2\x94\x7e\xd1\xff\xb3\xc7\x43\x02\xc3\xfe\x23\x83\xb5\xfd\xa8\x09\xd3\x21\x2b\xe5\xcf\xf6\x1e\x48\x58\x27\x20\x1f\x2c\x26\x0f\xe6\x40\x84\x38\xac\x9f\x8d\x81\xc4\xb1\x5a\xbe\xf7\x03\xb0\x28\x05\x26\x02\xd2\x80\x40\xc8\x08\x60\x43\x32\x98\xc1\xde\xfe\x81\x01\x72\x04\x3e\xd3\x00\x30\xe0\xc1\x7d\x7e\x05\x14\xc9\xa4\xf1\xa4\x06\x45\x90\xb5\xff\x78\x0d\x07\x05\x4b\xec\x50\x3c\x1e\x1a\x77\xcd\x20\x93\x3c\x7c\xcf\xf5\x41\x46\x58\x69\x5f\x41\x82\x70\x18\x02\x93\x01\x6b\x41\x60\x04\x04\x30\x21\x99\x1c\x69\x6f\x7f\x40\x78\xb9\x11\x5f\xbb\x80\x2c\xb0\x9c\x3e\xaf\x02\x49\xe5\x4b\x79\x5a\x04\xa4\xc8\xda\xfe\xcc\x0a\xc3\x85\x51\xf4\xa8\x1b\x07\x14\xd3\xda\x30\x56\x1e\x4c\x77\xf2\x20\xa6\x1c\x52\x6f\x84\xc1\x54\x0e\x01\x49\x80\xb6\x20\x2f\xf2\x02\x18\x10\xcc\x96\x30\xb7\xe5\xdf\xf7\x4c\x76\x2f\xf4\xbf\xcc\x38\x4b\xdf\xb8\x80\xa8\xb2\x74\x3d\xfe\xff\xca\x64\x63\x81\xfa\x02\x81\xc3\x02\xfc\xc4\x0a\x65\x8d\x15\xf1\x38\x22\x8f\x2a\xcc\x0e\x50\x48\x8e\x33\x17\xda\xa0\x84\x08\x00\xa5\x40\x59\x4f\xe8\x01\x01\x0c\x00\x66\x5b\x1c\x0b\xd1\xd0\x00\x2e\x4f\x77\xca\x9f\x94\x1c\x18\x2f\x93\x40\x32\x99\x06\xdf\xf8\x80\x3c\xb0\x3d\xbe\x85\x01\xa9\x61\x14\x7b\x92\x06\xe4\xc6\x03\x02\x0c\x08\x65\x84\x9d\xf3\xb8\x17\xc2\x40\x29\x50\x16\x6b\xf6\x08\x40\x43\x02\x19\x94\xc6\x7a\xfb\x03\xf9\x29\x8f\x3e\x03\x17\xf2\x07\x06\xdb\xf9\x4f\xf9\xa6\x59\x27\xbe\x1f\xec\x4c\x74\x30\x2c\x3f\xe2\x38\x3b\x9f\xce\x80\x7c\x71\x3a\x3e\x79\x03\x2a\xe3\xbc\x82\x46\x04\x11\xc4\x6e\xfd\x7c\x0a\x40"
         with open(os.path.join(self.dirname, "spartnHPAC.log"), "rb") as stream:
             spr = SPARTNReader(
                 stream,
                 quitonerror=ERRRAISE,
                 decode=True,
-                key=SPARTNKEY,
+                key=SPARTNKEY_HPAC,
             )
             for raw, parsed in spr:
                 if raw is not None:
                     print(parsed.payload)
                     self.assertEqual(parsed.payload, EXPECTED_RESULT)
 
     def testHPACLOG(
@@ -165,15 +167,32 @@
     ):  # test decoding of SPARTN HPAC message
         EXPECTED_RESULT = "<SPARTN(SPARTN-1X-HPAC-GPS, msgType=1, nData=619, eaf=1, crcType=2, frameCrc=12, msgSubtype=0, timeTagtype=1, gnssTimeTag=419070990, solutionId=5, solutionProcId=11, encryptionId=1, encryptionSeq=63, authInd=1, embAuthLen=0, crc=5760935, SF005=508, SF068=1, SF069=0, SF030=9, SF031_01=0, SF039_01=0, SF040T_01=1, SF040I_01=1, SF041_01=1, SF042_01=2, SF043_01=127, SF044_01=1, SF048_01=213, SF049a_01=257, SF049b_01=253, SF054_01=1, SatBitmaskLen_01=0, SF011_01=70263185, SF055_01_01=6, SF056_01_01=1, SF060_01_01=8944, SF061a_01_01=8362, SF061b_01_01=8207, SF055_01_02=5, SF056_01_02=1, SF060_01_02=9380, SF061a_01_02=8391, SF061b_01_02=8193, SF055_01_03=5, SF056_01_03=1, SF060_01_03=8570, SF061a_01_03=8426, SF061b_01_03=8223, SF055_01_04=6, SF056_01_04=1, SF060_01_04=9234, SF061a_01_04=8223, SF061b_01_04=8182, SF055_01_05=6, SF056_01_05=1, SF060_01_05=9744, SF061a_01_05=8668, SF061b_01_05=8259, SF055_01_06=5, SF056_01_06=1, SF060_01_06=8619, SF061a_01_06=8428, SF061b_01_06=8244, SF055_01_07=4, SF056_01_07=1, SF060_01_07=8916, SF061a_01_07=8312, SF061b_01_07=8284, SF055_01_08=4, SF056_01_08=1, SF060_01_08=8946, SF061a_01_08=8372, SF061b_01_08=8289, SF031_02=1, SF039_02=0, SF040T_02=1, SF040I_02=1, SF041_02=1, SF042_02=2, SF043_02=127, SF044_02=1, SF048_02=217, SF049a_02=253, SF049b_02=253, SF054_02=1, SatBitmaskLen_02=0, SF011_02=70263185, SF055_02_01=6, SF056_02_01=1, SF060_02_01=8832, SF061a_02_01=8322, SF061b_02_01=8190, SF055_02_02=7, SF056_02_02=1, SF060_02_02=9255, SF061a_02_02=8461, SF061b_02_02=8164, SF055_02_03=6, SF056_02_03=1, SF060_02_03=8384, SF061a_02_03=8388, SF061b_02_03=8219, SF055_02_04=5, SF056_02_04=1, SF060_02_04=9207, SF061a_02_04=8270, SF061b_02_04=8181, SF055_02_05=5, SF056_02_05=1, SF060_02_05=9405, SF061a_02_05=8534, SF061b_02_05=8234, SF055_02_06=5, SF056_02_06=1, SF060_02_06=8410, SF061a_02_06=8398, SF061b_02_06=8237, SF055_02_07=4, SF056_02_07=1, SF060_02_07=8701, SF061a_02_07=8359, SF061b_02_07=8283, SF055_02_08=5, SF056_02_08=1, SF060_02_08=8691, SF061a_02_08=8424, SF061b_02_08=8287, SF031_03=2, SF039_03=0, SF040T_03=1, SF040I_03=1, SF041_03=1, SF042_03=1, SF043_03=127, SF044_03=1, SF048_03=209, SF049a_03=257, SF049b_03=255, SF054_03=1, SatBitmaskLen_03=0, SF011_03=70263185, SF055_03_01=1, SF056_03_01=1, SF060_03_01=8854, SF061a_03_01=8369, SF061b_03_01=8205, SF055_03_02=2, SF056_03_02=1, SF060_03_02=9223, SF061a_03_02=8462, SF061b_03_02=8199, SF055_03_03=2, SF056_03_03=1, SF060_03_03=8462, SF061a_03_03=8358, SF061b_03_03=8242, SF055_03_04=4, SF056_03_04=1, SF060_03_04=9198, SF061a_03_04=8246, SF061b_03_04=8197, SF055_03_05=3, SF056_03_05=1, SF060_03_05=9521, SF061a_03_05=8572, SF061b_03_05=8232, SF055_03_06=3, SF056_03_06=1, SF060_03_06=8515, SF061a_03_06=8382, SF061b_03_06=8253, SF055_03_07=2, SF056_03_07=1, SF060_03_07=8901, SF061a_03_07=8346, SF061b_03_07=8298, SF055_03_08=3, SF056_03_08=1, SF060_03_08=8886, SF061a_03_08=8406, SF061b_03_08=8304, SF031_04=3, SF039_04=0, SF040T_04=1, SF040I_04=1, SF041_04=1, SF042_04=1, SF043_04=127, SF044_04=1, SF048_04=216, SF049a_04=257, SF049b_04=258, SF054_04=1, SatBitmaskLen_04=0, SF011_04=70263185, SF055_04_01=4, SF056_04_01=1, SF060_04_01=8814, SF061a_04_01=8057, SF061b_04_01=8214, SF055_04_02=4, SF056_04_02=1, SF060_04_02=9159, SF061a_04_02=8211, SF061b_04_02=8204, SF055_04_03=3, SF056_04_03=1, SF060_04_03=8319, SF061a_04_03=8155, SF061b_04_03=8225, SF055_04_04=4, SF056_04_04=1, SF060_04_04=9223, SF061a_04_04=8014, SF061b_04_04=8204, SF055_04_05=5, SF056_04_05=1, SF060_04_05=9273, SF061a_04_05=8311, SF061b_04_05=8225, SF055_04_06=1, SF056_04_06=1, SF060_04_06=8316, SF061a_04_06=8143, SF061b_04_06=8254, SF055_04_07=2, SF056_04_07=1, SF060_04_07=8578, SF061a_04_07=8165, SF061b_04_07=8293, SF055_04_08=2, SF056_04_08=1, SF060_04_08=8574, SF061a_04_08=8111, SF061b_04_08=8291, SF031_05=4, SF039_05=0, SF040T_05=1, SF040I_05=1, SF041_05=1, SF042_05=1, SF043_05=127, SF044_05=1, SF048_05=212, SF049a_05=252, SF049b_05=252, SF054_05=1, SatBitmaskLen_05=0, SF011_05=70263185, SF055_05_01=1, SF056_05_01=1, SF060_05_01=8852, SF061a_05_01=8116, SF061b_05_01=8187, SF055_05_02=3, SF056_05_02=1, SF060_05_02=9121, SF061a_05_02=8280, SF061b_05_02=8177, SF055_05_03=1, SF056_05_03=1, SF060_05_03=8429, SF061a_05_03=8154, SF061b_05_03=8231, SF055_05_04=4, SF056_05_04=1, SF060_05_04=9253, SF061a_05_04=7982, SF061b_05_04=8172, SF055_05_05=3, SF056_05_05=1, SF060_05_05=9349, SF061a_05_05=8348, SF061b_05_05=8223, SF055_05_06=2, SF056_05_06=1, SF060_05_06=8496, SF061a_05_06=8140, SF061b_05_06=8258, SF055_05_07=1, SF056_05_07=1, SF060_05_07=8882, SF061a_05_07=8077, SF061b_05_07=8305, SF055_05_08=2, SF056_05_08=1, SF060_05_08=8885, SF061a_05_08=8059, SF061b_05_08=8310, SF031_06=5, SF039_06=0, SF040T_06=1, SF040I_06=1, SF041_06=1, SF042_06=1, SF043_06=128, SF044_06=1, SF048_06=210, SF049a_06=256, SF049b_06=259, SF054_06=1, SatBitmaskLen_06=0, SF011_06=70263193, SF055_06_01=4, SF056_06_01=1, SF060_06_01=8967, SF061a_06_01=7934, SF061b_06_01=8256, SF055_06_02=5, SF056_06_02=1, SF060_06_02=9224, SF061a_06_02=8041, SF061b_06_02=8198, SF055_06_03=1, SF056_06_03=1, SF060_06_03=8385, SF061a_06_03=8031, SF061b_06_03=8273, SF055_06_04=4, SF056_06_04=1, SF060_06_04=9426, SF061a_06_04=7732, SF061b_06_04=8242, SF055_06_05=2, SF056_06_05=1, SF060_06_05=9261, SF061a_06_05=8183, SF061b_06_05=8244, SF055_06_06=1, SF056_06_06=1, SF060_06_06=8361, SF061a_06_06=8034, SF061b_06_06=8312, SF055_06_07=3, SF056_06_07=1, SF060_06_07=8615, SF061a_06_07=7988, SF061b_06_07=8339, SF055_06_08=3, SF056_06_08=1, SF060_06_08=9190, SF061a_06_08=8170, SF061b_06_08=8355, SF055_06_09=2, SF056_06_09=1, SF060_06_09=8613, SF061a_06_09=8001, SF061b_06_09=8348, SF031_07=6, SF039_07=0, SF040T_07=1, SF040I_07=1, SF041_07=1, SF042_07=1, SF043_07=128, SF044_07=1, SF048_07=214, SF049a_07=261, SF049b_07=256, SF054_07=1, SatBitmaskLen_07=0, SF011_07=70263193, SF055_07_01=1, SF056_07_01=1, SF060_07_01=9035, SF061a_07_01=7934, SF061b_07_01=8252, SF055_07_02=5, SF056_07_02=1, SF060_07_02=9285, SF061a_07_02=8123, SF061b_07_02=8203, SF055_07_03=2, SF056_07_03=1, SF060_07_03=8504, SF061a_07_03=8023, SF061b_07_03=8265, SF055_07_04=3, SF056_07_04=1, SF060_07_04=9547, SF061a_07_04=7766, SF061b_07_04=8266, SF055_07_05=4, SF056_07_05=1, SF060_07_05=9325, SF061a_07_05=8153, SF061b_07_05=8278, SF055_07_06=1, SF056_07_06=1, SF060_07_06=8532, SF061a_07_06=8010, SF061b_07_06=8300, SF055_07_07=1, SF056_07_07=1, SF060_07_07=8858, SF061a_07_07=7889, SF061b_07_07=8364, SF055_07_08=3, SF056_07_08=1, SF060_07_08=9415, SF061a_07_08=8136, SF061b_07_08=8358, SF055_07_09=1, SF056_07_09=1, SF060_07_09=8851, SF061a_07_09=7945, SF061b_07_09=8362, SF031_08=7, SF039_08=0, SF040T_08=1, SF040I_08=1, SF041_08=1, SF042_08=1, SF043_08=128, SF044_08=1, SF048_08=216, SF049a_08=257, SF049b_08=255, SF054_08=1, SatBitmaskLen_08=0, SF011_08=70263193, SF055_08_01=2, SF056_08_01=1, SF060_08_01=8971, SF061a_08_01=8087, SF061b_08_01=8183, SF055_08_02=4, SF056_08_02=1, SF060_08_02=9137, SF061a_08_02=8169, SF061b_08_02=8166, SF055_08_03=1, SF056_08_03=1, SF060_08_03=8495, SF061a_08_03=8120, SF061b_08_03=8234, SF055_08_04=2, SF056_08_04=1, SF060_08_04=9448, SF061a_08_04=7935, SF061b_08_04=8185, SF055_08_05=4, SF056_08_05=1, SF060_08_05=9315, SF061a_08_05=8318, SF061b_08_05=8232, SF055_08_06=1, SF056_08_06=1, SF060_08_06=8577, SF061a_08_06=8088, SF061b_08_06=8275, SF055_08_07=2, SF056_08_07=1, SF060_08_07=9029, SF061a_08_07=7955, SF061b_08_07=8330, SF055_08_08=3, SF056_08_08=1, SF060_08_08=9561, SF061a_08_08=8306, SF061b_08_08=8337, SF055_08_09=1, SF056_08_09=1, SF060_08_09=9009, SF061a_08_09=8042, SF061b_08_09=8324, SF031_09=8, SF039_09=0, SF040T_09=1, SF040I_09=1, SF041_09=1, SF042_09=2, SF043_09=128, SF044_09=1, SF048_09=202, SF049a_09=254, SF049b_09=256, SF054_09=1, SatBitmaskLen_09=0, SF011_09=70255001, SF055_09_01=6, SF056_09_01=1, SF060_09_01=9089, SF061a_09_01=7822, SF061b_09_01=8192, SF055_09_02=5, SF056_09_02=1, SF060_09_02=9463, SF061a_09_02=7978, SF061b_09_02=8084, SF055_09_03=1, SF056_09_03=1, SF060_09_03=8385, SF061a_09_03=7974, SF061b_09_03=8217, SF055_09_04=4, SF056_09_04=1, SF060_09_04=9243, SF061a_09_04=8184, SF061b_09_04=8207, SF055_09_05=2, SF056_09_05=1, SF060_09_05=8315, SF061a_09_05=8002, SF061b_09_05=8245, SF055_09_06=2, SF056_09_06=1, SF060_09_06=8468, SF061a_09_06=7908, SF061b_09_06=8302, SF055_09_07=4, SF056_09_07=1, SF060_09_07=8961, SF061a_09_07=8257, SF061b_09_07=8259, SF055_09_08=2, SF056_09_08=1, SF060_09_08=8487, SF061a_09_08=7995, SF061b_09_08=8287)>"
         with open(os.path.join(self.dirname, "spartnHPAC.log"), "rb") as stream:
             spr = SPARTNReader(
                 stream,
                 quitonerror=ERRRAISE,
                 decode=True,
-                key=SPARTNKEY,
+                key=SPARTNKEY_HPAC,
+            )
+            for raw, parsed in spr:
+                if raw is not None:
+                    # print(parsed)
+                    self.assertEqual(str(parsed), EXPECTED_RESULT)
+
+    def testGADLOG(
+        self,
+    ):  # test decoding of SPARTN GAD message
+        EXPECTED_RESULT = "<SPARTN(SPARTN-1X-GAD, msgType=2, nData=50, eaf=1, crcType=2, frameCrc=2, msgSubtype=0, timeTagtype=0, gnssTimeTag=32580, solutionId=5, solutionProcId=11, encryptionId=1, encryptionSeq=63, authInd=1, embAuthLen=0, crc=6182016, SF005=37, SF068=1, SF069=0, SF030=7, SF031_01=32, SF032_01=1332, SF033_01=1987, SF034_01=6, SF035_01=2, SF036_01=5, SF037_01=22, SF031_02=33, SF032_02=1332, SF033_02=2033, SF034_02=6, SF035_02=3, SF036_02=5, SF037_02=16, SF031_03=34, SF032_03=1301, SF033_03=1921, SF034_03=2, SF035_03=6, SF036_03=18, SF037_03=10, SF031_04=35, SF032_04=1297, SF033_04=1987, SF034_04=3, SF035_04=3, SF036_04=12, SF037_04=22, SF031_05=36, SF032_05=1448, SF033_05=1768, SF034_05=6, SF035_05=2, SF036_05=5, SF037_05=30, SF031_06=37, SF032_06=1391, SF033_06=1745, SF034_06=4, SF035_06=7, SF036_06=7, SF037_06=10, SF031_07=38, SF032_07=1360, SF033_07=1906, SF034_07=3, SF035_07=2, SF036_07=8, SF037_07=22)>"
+        with open(os.path.join(self.dirname, "spartnGAD.log"), "rb") as stream:
+            spr = SPARTNReader(
+                stream,
+                quitonerror=ERRRAISE,
+                decode=True,
+                key=SPARTNKEY_GAD,
+                basedate=datetime(2023, 6, 27, 22, 3, 0),
             )
             for raw, parsed in spr:
                 if raw is not None:
                     # print(parsed)
                     self.assertEqual(str(parsed), EXPECTED_RESULT)
 
     # def testOCBLOG(
```


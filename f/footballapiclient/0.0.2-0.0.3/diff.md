# Comparing `tmp/footballapiclient-0.0.2.tar.gz` & `tmp/footballapiclient-0.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "footballapiclient-0.0.2.tar", max compression
+gzip compressed data, was "footballapiclient-0.0.3.tar", max compression
```

## Comparing `footballapiclient-0.0.2.tar` & `footballapiclient-0.0.3.tar`

### file list

```diff
@@ -1,16 +1,18 @@
--rw-r--r--   0        0        0      211 2023-06-08 22:15:54.132080 footballapiclient-0.0.2/footballAPIClient/__init__.py
--rw-r--r--   0        0        0        0 2023-06-08 20:50:42.375846 footballapiclient-0.0.2/footballAPIClient/__main__.py
--rw-r--r--   0        0        0      185 2023-06-06 15:02:35.081060 footballapiclient-0.0.2/footballAPIClient/_constants.py
--rw-r--r--   0        0        0      547 2023-06-04 08:23:05.053509 footballapiclient-0.0.2/footballAPIClient/Exceptions/__pycache__/ApiKeyMissingError.cpython-39.pyc
--rw-r--r--   0        0        0      556 2023-06-04 14:28:11.403008 footballapiclient-0.0.2/footballAPIClient/Exceptions/__pycache__/APILimitExceededError.cpython-39.pyc
--rw-r--r--   0        0        0      876 2023-06-02 19:58:25.420894 footballapiclient-0.0.2/footballAPIClient/Exceptions/__pycache__/MissingParametersError.cpython-39.pyc
--rw-r--r--   0        0        0      105 2023-06-04 08:03:20.072635 footballapiclient-0.0.2/footballAPIClient/Exceptions/ApiKeyMissingError.py
--rw-r--r--   0        0        0      110 2023-06-04 14:28:10.117768 footballapiclient-0.0.2/footballAPIClient/Exceptions/APILimitExceededError.py
--rw-r--r--   0        0        0      405 2023-06-02 19:58:24.807867 footballapiclient-0.0.2/footballAPIClient/Exceptions/MissingParametersError.py
--rw-r--r--   0        0        0    42260 2023-06-08 20:26:24.796046 footballapiclient-0.0.2/footballAPIClient/footballAPI.py
--rw-r--r--   0        0        0     7177 2023-06-08 19:41:32.466861 footballapiclient-0.0.2/footballAPIClient/helpers/__pycache__/ParameterValidator.cpython-39.pyc
--rw-r--r--   0        0        0     6870 2023-06-08 20:07:33.392693 footballapiclient-0.0.2/footballAPIClient/helpers/ParameterValidator.py
--rw-r--r--   0        0        0     1092 2023-06-05 18:10:22.673709 footballapiclient-0.0.2/LICENSE
--rw-r--r--   0        0        0      593 2023-06-08 22:16:12.219634 footballapiclient-0.0.2/pyproject.toml
--rw-r--r--   0        0        0     1597 2023-06-08 22:15:44.243327 footballapiclient-0.0.2/README.md
--rw-r--r--   0        0        0     2313 1970-01-01 00:00:00.000000 footballapiclient-0.0.2/PKG-INFO
+-rw-r--r--   0        0        0      211 2023-06-28 15:33:55.442788 footballapiclient-0.0.3/footballAPIClient/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 15:37:36.756322 footballapiclient-0.0.3/footballAPIClient/__main__.py
+-rw-r--r--   0        0        0      185 2023-06-06 15:02:35.081060 footballapiclient-0.0.3/footballAPIClient/_constants.py
+-rw-r--r--   0        0        0      547 2023-06-04 08:23:05.053509 footballapiclient-0.0.3/footballAPIClient/Exceptions/__pycache__/ApiKeyMissingError.cpython-39.pyc
+-rw-r--r--   0        0        0      556 2023-06-04 14:28:11.403008 footballapiclient-0.0.3/footballAPIClient/Exceptions/__pycache__/APILimitExceededError.cpython-39.pyc
+-rw-r--r--   0        0        0      547 2023-06-28 15:30:04.094603 footballapiclient-0.0.3/footballAPIClient/Exceptions/__pycache__/InvalidApiKeyError.cpython-39.pyc
+-rw-r--r--   0        0        0      876 2023-06-02 19:58:25.420894 footballapiclient-0.0.3/footballAPIClient/Exceptions/__pycache__/MissingParametersError.cpython-39.pyc
+-rw-r--r--   0        0        0      105 2023-06-04 08:03:20.072635 footballapiclient-0.0.3/footballAPIClient/Exceptions/ApiKeyMissingError.py
+-rw-r--r--   0        0        0      110 2023-06-04 14:28:10.117768 footballapiclient-0.0.3/footballAPIClient/Exceptions/APILimitExceededError.py
+-rw-r--r--   0        0        0      105 2023-06-28 15:24:26.674870 footballapiclient-0.0.3/footballAPIClient/Exceptions/InvalidApiKeyError.py
+-rw-r--r--   0        0        0      405 2023-06-02 19:58:24.807867 footballapiclient-0.0.3/footballAPIClient/Exceptions/MissingParametersError.py
+-rw-r--r--   0        0        0    42521 2023-06-28 15:30:03.258607 footballapiclient-0.0.3/footballAPIClient/footballAPI.py
+-rw-r--r--   0        0        0     7517 2023-06-28 14:48:30.416016 footballapiclient-0.0.3/footballAPIClient/helpers/__pycache__/ParameterValidator.cpython-39.pyc
+-rw-r--r--   0        0        0     6870 2023-06-08 20:07:33.392693 footballapiclient-0.0.3/footballAPIClient/helpers/ParameterValidator.py
+-rw-r--r--   0        0        0     1092 2023-06-05 18:10:22.673709 footballapiclient-0.0.3/LICENSE
+-rw-r--r--   0        0        0      593 2023-06-28 15:34:07.542618 footballapiclient-0.0.3/pyproject.toml
+-rw-r--r--   0        0        0     1597 2023-06-08 22:15:44.243327 footballapiclient-0.0.3/README.md
+-rw-r--r--   0        0        0     2313 1970-01-01 00:00:00.000000 footballapiclient-0.0.3/PKG-INFO
```

### Comparing `footballapiclient-0.0.2/footballAPIClient/Exceptions/__pycache__/ApiKeyMissingError.cpython-39.pyc` & `footballapiclient-0.0.3/footballAPIClient/Exceptions/__pycache__/ApiKeyMissingError.cpython-39.pyc`

 * *Files identical despite different names*

### Comparing `footballapiclient-0.0.2/footballAPIClient/Exceptions/__pycache__/APILimitExceededError.cpython-39.pyc` & `footballapiclient-0.0.3/footballAPIClient/Exceptions/__pycache__/APILimitExceededError.cpython-39.pyc`

 * *Files identical despite different names*

### Comparing `footballapiclient-0.0.2/footballAPIClient/Exceptions/__pycache__/MissingParametersError.cpython-39.pyc` & `footballapiclient-0.0.3/footballAPIClient/Exceptions/__pycache__/MissingParametersError.cpython-39.pyc`

 * *Files identical despite different names*

### Comparing `footballapiclient-0.0.2/footballAPIClient/footballAPI.py` & `footballapiclient-0.0.3/footballAPIClient/footballAPI.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,14 @@
 import os
 from http.client import HTTPException
 
 import requests
 import logging
 
+from footballAPIClient.Exceptions.InvalidApiKeyError import InvalidApiKeyError
 from footballAPIClient.Exceptions.MissingParametersError import MissingParametersError
 from footballAPIClient.Exceptions.ApiKeyMissingError import ApiKeyMissingError
 from footballAPIClient.helpers.ParameterValidator import ParameterValidator
 from footballAPIClient.Exceptions.APILimitExceededError import APILimitExceededError
 from footballAPIClient._constants import RAPID_API, FOOTBALL_API, FOOTBALL_API_URI, RAPID_API_URI
 
 
@@ -52,15 +53,18 @@
             if isinstance(e, KeyError):
                 raise ApiKeyMissingError("No API_KEY set as environment variable or provided.")
             else:
                 raise
 
     def _update_credit(self):
         self._logger.info("Updating credits")
-        data = self.get_status()
+        try:
+            data = self.get_status()
+        except Exception as e:
+            raise
         self._max_credit = data["response"]["requests"]["limit_day"]
         current_used_credit = data["response"]["requests"]["current"] + 1  # as a fail-safe situation added 1
         self._available_credit = self._max_credit - current_used_credit
         self._logger.info(f"{self._available_credit} credit(s) available.")
 
     def _get_headers(self):
         headers = {}
@@ -253,15 +257,18 @@
         """
         It allows you to:
         - To follow your consumption in real time
         - Check the status of our servers
         Note: This call does not count against the daily quota.
         :return: Returns the status json schema
         """
-        return self._get('status')
+        data = self._get('status')
+        if data["errors"]:
+            raise InvalidApiKeyError(data["errors"]["token"])
+        return data
 
     def get_countries(self, name: str = None, code: str = None, search: str = None):
         """
         Get the list of available countries for the leagues endpoint.
 
         :param name: The name of the country
         :param code: The Alpha2 code of the country
```

### Comparing `footballapiclient-0.0.2/footballAPIClient/helpers/__pycache__/ParameterValidator.cpython-39.pyc` & `footballapiclient-0.0.3/footballAPIClient/helpers/__pycache__/ParameterValidator.cpython-39.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.9, timestamp-based, .py timestamp: Thu Jun  8 19:40:09 2023 UTC, .py size: 6562 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 3% similar despite different names*

```diff
@@ -1,19 +1,19 @@
-00000000: 610d 0d0a 0000 0000 992e 8264 a219 0000  a..........d....
+00000000: 610d 0d0a 0000 0000 0535 8264 d61a 0000  a........5.d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0003 0000 0040 0000 0073 4600 0000 6400  .....@...sF...d.
 00000030: 6401 6c00 5a00 6400 6402 6c01 6d01 5a01  d.l.Z.d.d.l.m.Z.
 00000040: 0100 6400 6401 6c02 5a02 6400 6403 6c03  ..d.d.l.Z.d.d.l.
 00000050: 6d04 5a04 0100 6400 6404 6c03 6d05 5a05  m.Z...d.d.l.m.Z.
 00000060: 0100 4700 6405 6406 8400 6406 8302 5a06  ..G.d.d...d...Z.
 00000070: 6401 5300 2907 e900 0000 004e 2901 da08  d.S.)......N)...
 00000080: 6461 7465 7469 6d65 2901 da09 5241 5049  datetime)...RAPI
 00000090: 445f 4150 4929 01da 0c46 4f4f 5442 414c  D_API)...FOOTBAL
 000000a0: 4c5f 4150 4963 0000 0000 0000 0000 0000  L_APIc..........
-000000b0: 0000 0000 0000 0400 0000 4000 0000 736c  ..........@...sl
+000000b0: 0000 0000 0000 0400 0000 4000 0000 737e  ..........@...s~
 000000c0: 0100 0065 005a 0164 005a 0265 0365 0464  ...e.Z.d.Z.e.e.d
 000000d0: 019c 0164 0264 0384 0483 015a 0565 0364  ...d.d.....Z.e.d
 000000e0: 0464 0584 0083 015a 0665 0365 0465 0464  .d.....Z.e.e.e.d
 000000f0: 069c 0264 0764 0884 0483 015a 0765 0365  ...d.d.....Z.e.e
 00000100: 0865 0464 069c 0264 0964 0a84 0483 015a  .e.d...d.d.....Z
 00000110: 0965 0364 0b64 0c84 0083 015a 0a65 0365  .e.d.d.....Z.e.e
 00000120: 0464 0d9c 0164 0e64 0f84 0483 015a 0b65  .d...d.d.....Z.e
@@ -28,422 +28,443 @@
 000001b0: 0464 249c 0164 2564 2684 0483 015a 1465  .d$..d%d&....Z.e
 000001c0: 0365 0464 279c 0164 2864 2984 0483 015a  .e.d'..d(d)....Z
 000001d0: 1565 0365 0864 2a9c 0164 2b64 2c84 0483  .e.e.d*..d+d,...
 000001e0: 015a 1665 0365 0464 2d9c 0164 2e64 2f84  .Z.e.e.d-..d.d/.
 000001f0: 0483 015a 1765 0365 0464 309c 0164 3164  ...Z.e.e.d0..d1d
 00000200: 3284 0483 015a 1865 0365 0464 189c 0164  2....Z.e.e.d...d
 00000210: 3364 3484 0483 015a 1965 0365 0464 189c  3d4....Z.e.e.d..
-00000220: 0164 3564 3684 0483 015a 1a64 3753 0029  .d5d6....Z.d7S.)
-00000230: 38da 1250 6172 616d 6574 6572 5661 6c69  8..ParameterVali
-00000240: 6461 746f 7229 01da 0668 6561 6465 7263  dator)...headerc
-00000250: 0100 0000 0000 0000 0000 0000 0200 0000  ................
-00000260: 0200 0000 4300 0000 7320 0000 0074 0074  ....C...s ...t.t
-00000270: 0168 027d 017c 00a0 02a1 007c 0176 0172  .h.}.|.....|.v.r
-00000280: 1c74 0364 0183 0182 0164 0053 0029 024e  .t.d.....d.S.).N
-00000290: 7a32 616c 6c6f 7765 6420 6163 636f 756e  z2allowed accoun
-000002a0: 7420 7479 7065 7320 3a20 2772 6170 6964  t types : 'rapid
-000002b0: 2d61 7069 272c 2027 6170 692d 7370 6f72  -api', 'api-spor
-000002c0: 7473 2720 2904 7203 0000 0072 0400 0000  ts' ).r....r....
-000002d0: da05 6c6f 7765 72da 0a56 616c 7565 4572  ..lower..ValueEr
-000002e0: 726f 7229 0272 0600 0000 5a10 616c 6c6f  ror).r....Z.allo
-000002f0: 7765 645f 6163 636f 756e 7473 a900 7209  wed_accounts..r.
-00000300: 0000 00fa 5c45 3a5c 436f 6465 735c 5079  ....\E:\Codes\Py
-00000310: 6368 6172 6d50 726f 6a65 6374 735c 666f  charmProjects\fo
-00000320: 6f74 6261 6c6c 2d41 5049 2d63 6c69 656e  otball-API-clien
-00000330: 745c 666f 6f74 6261 6c6c 4150 4943 6c69  t\footballAPICli
-00000340: 656e 745c 6865 6c70 6572 735c 5061 7261  ent\helpers\Para
-00000350: 6d65 7465 7256 616c 6964 6174 6f72 2e70  meterValidator.p
-00000360: 79da 1c76 616c 6964 6174 655f 6163 636f  y..validate_acco
-00000370: 756e 745f 6865 6164 6572 5f74 7970 650b  unt_header_type.
-00000380: 0000 0073 0600 0000 0002 0802 0c01 7a2f  ...s..........z/
-00000390: 5061 7261 6d65 7465 7256 616c 6964 6174  ParameterValidat
-000003a0: 6f72 2e76 616c 6964 6174 655f 6163 636f  or.validate_acco
-000003b0: 756e 745f 6865 6164 6572 5f74 7970 6563  unt_header_typec
-000003c0: 0000 0000 0000 0000 0000 0000 0100 0000  ................
-000003d0: 0300 0000 4700 0000 731a 0000 0074 0064  ....G...s....t.d
-000003e0: 0164 0284 007c 0044 0083 0183 0172 1664  .d...|.D.....r.d
-000003f0: 0353 0064 0453 0029 054e 6301 0000 0000  .S.d.S.).Nc.....
-00000400: 0000 0000 0000 0002 0000 0003 0000 0073  ...............s
-00000410: 0000 0073 1600 0000 7c00 5d0e 7d01 7c01  ...s....|.].}.|.
-00000420: 6400 7500 5600 0100 7102 6400 5300 a901  d.u.V...q.d.S...
-00000430: 4e72 0900 0000 2902 da02 2e30 da05 7061  Nr....)....0..pa
-00000440: 7261 6d72 0900 0000 7209 0000 0072 0a00  ramr....r....r..
-00000450: 0000 da09 3c67 656e 6578 7072 3e14 0000  ....<genexpr>...
-00000460: 00f3 0000 0000 7a3a 5061 7261 6d65 7465  ......z:Paramete
-00000470: 7256 616c 6964 6174 6f72 2e63 6865 636b  rValidator.check
-00000480: 5f6d 6973 7369 6e67 5f70 6172 616d 732e  _missing_params.
-00000490: 3c6c 6f63 616c 733e 2e3c 6765 6e65 7870  <locals>.<genexp
-000004a0: 723e 5446 2901 da03 616c 6c29 01da 0461  r>TF)...all)...a
-000004b0: 7267 7372 0900 0000 7209 0000 0072 0a00  rgsr....r....r..
-000004c0: 0000 da14 6368 6563 6b5f 6d69 7373 696e  ....check_missin
-000004d0: 675f 7061 7261 6d73 1200 0000 7306 0000  g_params....s...
-000004e0: 0000 0212 0104 017a 2750 6172 616d 6574  .......z'Paramet
-000004f0: 6572 5661 6c69 6461 746f 722e 6368 6563  erValidator.chec
-00000500: 6b5f 6d69 7373 696e 675f 7061 7261 6d73  k_missing_params
-00000510: a902 da03 7661 6cda 0a66 6965 6c64 5f6e  ....val..field_n
-00000520: 616d 6563 0200 0000 0000 0000 0000 0000  amec............
-00000530: 0200 0000 0300 0000 4300 0000 731c 0000  ........C...s...
-00000540: 0074 007c 0074 0183 0273 1874 027c 019b  .t.|.t...s.t.|..
-00000550: 0064 019d 0283 0182 0164 0053 0029 024e  .d.......d.S.).N
-00000560: 7a13 206d 7573 7420 6265 2061 6e20 7374  z. must be an st
-00000570: 7269 6e67 2e29 03da 0a69 7369 6e73 7461  ring.)...isinsta
-00000580: 6e63 65da 0373 7472 da09 5479 7065 4572  nce..str..TypeEr
-00000590: 726f 7272 1400 0000 7209 0000 0072 0900  rorr....r....r..
-000005a0: 0000 720a 0000 00da 1176 616c 6964 6174  ..r......validat
-000005b0: 655f 7479 7065 5f73 7472 1800 0000 7304  e_type_str....s.
-000005c0: 0000 0000 020a 017a 2450 6172 616d 6574  .......z$Paramet
-000005d0: 6572 5661 6c69 6461 746f 722e 7661 6c69  erValidator.vali
-000005e0: 6461 7465 5f74 7970 655f 7374 7263 0200  date_type_strc..
-000005f0: 0000 0000 0000 0000 0000 0200 0000 0300  ................
-00000600: 0000 4300 0000 731c 0000 0074 007c 0074  ..C...s....t.|.t
-00000610: 0183 0273 1874 027c 019b 0064 019d 0283  ...s.t.|...d....
-00000620: 0182 0164 0053 0029 024e 7a14 206d 7573  ...d.S.).Nz. mus
-00000630: 7420 6265 2061 6e20 696e 7465 6765 722e  t be an integer.
-00000640: 2903 7217 0000 00da 0369 6e74 7219 0000  ).r......intr...
-00000650: 0072 1400 0000 7209 0000 0072 0900 0000  .r....r....r....
-00000660: 720a 0000 00da 1176 616c 6964 6174 655f  r......validate_
-00000670: 7479 7065 5f69 6e74 1d00 0000 7304 0000  type_int....s...
-00000680: 0000 020a 017a 2450 6172 616d 6574 6572  .....z$Parameter
-00000690: 5661 6c69 6461 746f 722e 7661 6c69 6461  Validator.valida
-000006a0: 7465 5f74 7970 655f 696e 7463 0000 0000  te_type_intc....
-000006b0: 0000 0000 0000 0000 0600 0000 0800 0000  ................
-000006c0: 0b00 0000 7394 0000 0064 0164 0264 0367  ....s....d.d.d.g
-000006d0: 0266 0264 0464 0264 0567 0266 0264 0364  .f.d.d.d.g.f.d.d
-000006e0: 0467 0166 0264 0264 0467 0166 0264 0564  .g.f.d.d.g.f.d.d
-000006f0: 0467 0166 0264 0667 0064 07a2 0166 0267  .g.f.d.g.d...f.g
-00000700: 067d 017c 0144 005d 505c 027d 027d 0388  .}.|.D.]P\.}.}..
-00000710: 00a0 007c 02a1 017d 047c 0464 0075 0172  ...|...}.|.d.u.r
-00000720: 3e74 0187 0066 0164 0864 0984 087c 0344  >t...f.d.d...|.D
-00000730: 0083 0183 0172 3e64 0aa0 027c 03a1 017d  .....r>d...|...}
-00000740: 0574 0364 0b7c 029b 0064 0c7c 059b 0064  .t.d.|...d.|...d
-00000750: 0d9d 0583 0182 0171 3e64 0053 0029 0e4e  .......q>d.S.).N
-00000760: da06 7365 6172 6368 da06 6c65 6167 7565  ..search..league
-00000770: da04 7465 616d da06 7365 6173 6f6e da02  ..team..season..
-00000780: 6964 da04 7061 6765 2905 721d 0000 0072  id..page).r....r
-00000790: 2000 0000 721f 0000 0072 1e00 0000 7221   ...r....r....r!
-000007a0: 0000 0063 0100 0000 0000 0000 0000 0000  ...c............
-000007b0: 0200 0000 0400 0000 3300 0000 731c 0000  ........3...s...
-000007c0: 007c 005d 147d 0188 00a0 007c 01a1 0164  .|.].}.....|...d
-000007d0: 0075 0056 0001 0071 0264 0053 0072 0c00  .u.V...q.d.S.r..
-000007e0: 0000 2901 da03 6765 7429 0272 0d00 0000  ..)...get).r....
-000007f0: 5a0e 7265 7175 6972 6564 5f66 6965 6c64  Z.required_field
-00000800: a901 da06 6b77 6172 6773 7209 0000 0072  ....kwargsr....r
-00000810: 0a00 0000 720f 0000 002f 0000 0073 0200  ....r..../...s..
-00000820: 0000 0401 7a3c 5061 7261 6d65 7465 7256  ....z<ParameterV
-00000830: 616c 6964 6174 6f72 2e76 616c 6964 6174  alidator.validat
-00000840: 655f 706c 6179 6572 5f66 6965 6c64 732e  e_player_fields.
-00000850: 3c6c 6f63 616c 733e 2e3c 6765 6e65 7870  <locals>.<genexp
-00000860: 723e 7a02 2c20 fa01 277a 2d27 2072 6571  r>z., ..'z-' req
-00000870: 7569 7265 7320 6174 206c 6561 7374 206f  uires at least o
-00000880: 6e65 206f 6620 7468 6520 6f74 6865 7220  ne of the other 
-00000890: 6669 656c 6473 3a20 da01 2e29 0472 2300  fields: ...).r#.
-000008a0: 0000 7211 0000 00da 046a 6f69 6e72 0800  ..r......joinr..
-000008b0: 0000 2906 7225 0000 005a 0b66 6965 6c64  ..).r%...Z.field
-000008c0: 5f70 6169 7273 da05 6669 656c 645a 0f72  _pairs..fieldZ.r
-000008d0: 6571 7569 7265 645f 6669 656c 6473 5a0b  equired_fieldsZ.
-000008e0: 6669 656c 645f 7661 6c75 655a 1472 6571  field_valueZ.req
-000008f0: 7569 7265 645f 6669 656c 645f 6e61 6d65  uired_field_name
-00000900: 7372 0900 0000 7224 0000 0072 0a00 0000  sr....r$...r....
-00000910: da16 7661 6c69 6461 7465 5f70 6c61 7965  ..validate_playe
-00000920: 725f 6669 656c 6473 2200 0000 731c 0000  r_fields"...s...
-00000930: 0000 030a 010a 0108 0108 0108 010a fa04  ................
-00000940: 090c 010a 0114 0102 ff08 020a 017a 2950  .............z)P
-00000950: 6172 616d 6574 6572 5661 6c69 6461 746f  arameterValidato
-00000960: 722e 7661 6c69 6461 7465 5f70 6c61 7965  r.validate_playe
-00000970: 725f 6669 656c 6473 a901 721d 0000 0063  r_fields..r....c
-00000980: 0100 0000 0000 0000 0000 0000 0100 0000  ................
-00000990: 0200 0000 4300 0000 7318 0000 0074 007c  ....C...s....t.|
-000009a0: 0083 0164 016b 0572 1474 0164 0283 0182  ...d.k.r.t.d....
-000009b0: 0164 0053 0029 034e e903 0000 007a 2d20  .d.S.).N.....z- 
-000009c0: 5365 6172 6368 2066 6965 6c64 206d 7573  Search field mus
-000009d0: 7420 6861 7665 2061 7420 6c65 6173 7420  t have at least 
-000009e0: 3320 6368 6172 6163 7465 7273 a902 da03  3 characters....
-000009f0: 6c65 6e72 0800 0000 722b 0000 0072 0900  lenr....r+...r..
-00000a00: 0000 7209 0000 0072 0a00 0000 da15 7661  ..r....r......va
-00000a10: 6c69 6461 7465 5f73 6561 7263 685f 6669  lidate_search_fi
-00000a20: 656c 6434 0000 0073 0400 0000 0002 0c01  eld4...s........
-00000a30: 7a28 5061 7261 6d65 7465 7256 616c 6964  z(ParameterValid
-00000a40: 6174 6f72 2e76 616c 6964 6174 655f 7365  ator.validate_se
-00000a50: 6172 6368 5f66 6965 6c64 6301 0000 0000  arch_fieldc.....
-00000a60: 0000 0000 0000 0001 0000 0002 0000 0043  ...............C
-00000a70: 0000 0073 1800 0000 7400 7c00 8301 6401  ...s....t.|...d.
-00000a80: 6b05 7214 7401 6402 8301 8201 6400 5300  k.r.t.d.....d.S.
-00000a90: 2903 4ee9 0400 0000 7a2d 2053 6561 7263  ).N.....z- Searc
-00000aa0: 6820 6669 656c 6420 6d75 7374 2068 6176  h field must hav
-00000ab0: 6520 6174 206c 6561 7374 2034 2063 6861  e at least 4 cha
-00000ac0: 7261 6374 6572 7372 2d00 0000 722b 0000  ractersr-...r+..
-00000ad0: 0072 0900 0000 7209 0000 0072 0a00 0000  .r....r....r....
-00000ae0: da1c 7661 6c69 6461 7465 5f70 6c61 7965  ..validate_playe
-00000af0: 725f 7365 6172 6368 5f66 6965 6c64 3900  r_search_field9.
-00000b00: 0000 7304 0000 0000 020c 017a 2f50 6172  ..s........z/Par
-00000b10: 616d 6574 6572 5661 6c69 6461 746f 722e  ameterValidator.
-00000b20: 7661 6c69 6461 7465 5f70 6c61 7965 725f  validate_player_
-00000b30: 7365 6172 6368 5f66 6965 6c64 a901 da04  search_field....
-00000b40: 636f 6465 6301 0000 0000 0000 0000 0000  codec...........
-00000b50: 0001 0000 0003 0000 0043 0000 0073 2400  .........C...s$.
-00000b60: 0000 7400 6a01 6a02 7c00 6401 8d01 6400  ..t.j.j.|.d...d.
-00000b70: 7500 7220 7403 7c00 9b00 6402 9d02 8301  u.r t.|...d.....
-00000b80: 8201 6400 5300 2903 4e29 015a 0761 6c70  ..d.S.).N).Z.alp
-00000b90: 6861 5f32 7a1c 2069 7320 6e6f 7420 6120  ha_2z. is not a 
-00000ba0: 7661 6c69 6420 636f 756e 7472 7920 636f  valid country co
-00000bb0: 6465 2904 da09 7079 636f 756e 7472 79da  de)...pycountry.
-00000bc0: 0963 6f75 6e74 7269 6573 7223 0000 00da  .countriesr#....
-00000bd0: 0b4c 6f6f 6b75 7045 7272 6f72 7232 0000  .LookupErrorr2..
-00000be0: 0072 0900 0000 7209 0000 0072 0a00 0000  .r....r....r....
-00000bf0: da13 7661 6c69 6461 7465 5f63 6f64 655f  ..validate_code_
-00000c00: 6669 656c 643e 0000 0073 0400 0000 0002  field>...s......
-00000c10: 1201 7a26 5061 7261 6d65 7465 7256 616c  ..z&ParameterVal
-00000c20: 6964 6174 6f72 2e76 616c 6964 6174 655f  idator.validate_
-00000c30: 636f 6465 5f66 6965 6c64 2901 7220 0000  code_field).r ..
-00000c40: 0063 0100 0000 0000 0000 0000 0000 0200  .c..............
-00000c50: 0000 0500 0000 4300 0000 7320 0000 0064  ......C...s ...d
-00000c60: 017d 0174 00a0 017c 0174 027c 0083 01a1  .}.t...|.t.|....
-00000c70: 0273 1c74 0364 0283 0182 0164 0053 0029  .s.t.d.....d.S.)
-00000c80: 034e 7a07 5e5c 647b 347d 247a 3449 6e76  .Nz.^\d{4}$z4Inv
-00000c90: 616c 6964 2073 6561 736f 6e20 666f 726d  alid season form
-00000ca0: 6174 2e20 4578 7065 6374 6564 2066 6f72  at. Expected for
-00000cb0: 6d61 743a 2059 5959 5920 2879 6561 7229  mat: YYYY (year)
-00000cc0: 2e29 04da 0272 65da 056d 6174 6368 7218  .)...re..matchr.
-00000cd0: 0000 0072 0800 0000 2902 7220 0000 00da  ...r....).r ....
-00000ce0: 0770 6174 7465 726e 7209 0000 0072 0900  .patternr....r..
-00000cf0: 0000 720a 0000 00da 1576 616c 6964 6174  ..r......validat
-00000d00: 655f 7365 6173 6f6e 5f66 6965 6c64 4300  e_season_fieldC.
-00000d10: 0000 7308 0000 0000 0204 0110 0108 017a  ..s............z
-00000d20: 2850 6172 616d 6574 6572 5661 6c69 6461  (ParameterValida
-00000d30: 746f 722e 7661 6c69 6461 7465 5f73 6561  tor.validate_sea
-00000d40: 736f 6e5f 6669 656c 6429 0172 2900 0000  son_field).r)...
-00000d50: 6301 0000 0000 0000 0000 0000 0002 0000  c...............
-00000d60: 0002 0000 0043 0000 0073 1c00 0000 6401  .....C...s....d.
-00000d70: 6402 6802 7d01 7c00 7c01 7601 7218 7400  d.h.}.|.|.v.r.t.
-00000d80: 6403 8301 8201 6400 5300 2904 4e72 1e00  d.....d.S.).Nr..
-00000d90: 0000 5a03 6375 707a 1c61 6c6c 6f77 6564  ..Z.cupz.allowed
-00000da0: 2076 616c 7565 7320 3a20 6c65 6167 7565   values : league
-00000db0: 2c20 6375 70a9 0172 0800 0000 a902 7229  , cup..r......r)
-00000dc0: 0000 005a 0c61 6c6c 6f77 6564 5f76 616c  ...Z.allowed_val
-00000dd0: 7372 0900 0000 7209 0000 0072 0a00 0000  sr....r....r....
-00000de0: da13 7661 6c69 6461 7465 5f74 7970 655f  ..validate_type_
-00000df0: 6669 656c 644a 0000 0073 0800 0000 0002  fieldJ...s......
-00000e00: 0801 0801 0802 7a26 5061 7261 6d65 7465  ......z&Paramete
-00000e10: 7256 616c 6964 6174 6f72 2e76 616c 6964  rValidator.valid
-00000e20: 6174 655f 7479 7065 5f66 6965 6c64 6301  ate_type_fieldc.
-00000e30: 0000 0000 0000 0000 0000 0002 0000 0002  ................
-00000e40: 0000 0043 0000 0073 1c00 0000 6401 6402  ...C...s....d.d.
-00000e50: 6802 7d01 7c00 7c01 7601 7218 7400 6403  h.}.|.|.v.r.t.d.
-00000e60: 8301 8201 6400 5300 2904 4eda 0474 7275  ....d.S.).N..tru
-00000e70: 65da 0566 616c 7365 7a35 616c 6c6f 7765  e..falsez5allowe
-00000e80: 6420 7661 6c75 6573 2069 6e20 6375 7272  d values in curr
-00000e90: 656e 7420 6669 656c 6420 6172 6520 3a20  ent field are : 
-00000ea0: 2774 7275 6527 2c20 2766 616c 7365 2772  'true', 'false'r
-00000eb0: 3c00 0000 723d 0000 0072 0900 0000 7209  <...r=...r....r.
-00000ec0: 0000 0072 0a00 0000 da16 7661 6c69 6461  ...r......valida
-00000ed0: 7465 5f63 7572 7265 6e74 5f66 6965 6c64  te_current_field
-00000ee0: 5200 0000 7308 0000 0000 0208 0108 0108  R...s...........
-00000ef0: 017a 2950 6172 616d 6574 6572 5661 6c69  .z)ParameterVali
-00000f00: 6461 746f 722e 7661 6c69 6461 7465 5f63  dator.validate_c
-00000f10: 7572 7265 6e74 5f66 6965 6c64 a901 da04  urrent_field....
-00000f20: 6c61 7374 6301 0000 0000 0000 0000 0000  lastc...........
-00000f30: 0001 0000 0003 0000 0043 0000 0073 1c00  .........C...s..
-00000f40: 0000 7400 7401 7c00 8301 8301 6401 6b01  ..t.t.|.....d.k.
-00000f50: 7218 7402 6402 8301 8201 6400 5300 2903  r.t.d.....d.S.).
-00000f60: 4ee9 0200 0000 7a34 5468 6520 6c61 7374  N.....z4The last
-00000f70: 2066 6965 6c64 2063 616e 6e6f 7420 6578   field cannot ex
-00000f80: 6365 6564 2032 2063 6861 7261 6374 6572  ceed 2 character
-00000f90: 7320 696e 206c 656e 6774 682e a903 722e  s in length...r.
-00000fa0: 0000 0072 1800 0000 7208 0000 0072 4200  ...r....r....rB.
-00000fb0: 0000 7209 0000 0072 0900 0000 720a 0000  ..r....r....r...
-00000fc0: 00da 1376 616c 6964 6174 655f 6c61 7374  ...validate_last
-00000fd0: 5f66 6965 6c64 5900 0000 7306 0000 0000  _fieldY...s.....
-00000fe0: 0210 0108 017a 2650 6172 616d 6574 6572  .....z&Parameter
-00000ff0: 5661 6c69 6461 746f 722e 7661 6c69 6461  Validator.valida
-00001000: 7465 5f6c 6173 745f 6669 656c 6463 0100  te_last_fieldc..
-00001010: 0000 0000 0000 0000 0000 0100 0000 0200  ................
-00001020: 0000 4300 0000 7318 0000 0074 007c 0083  ..C...s....t.|..
-00001030: 0164 016b 0372 1474 0164 0283 0182 0164  .d.k.r.t.d.....d
-00001040: 0053 0029 034e 722c 0000 007a 154e 6f74  .S.).Nr,...z.Not
-00001050: 2061 2076 616c 6964 2074 6561 6d20 636f   a valid team co
-00001060: 6465 722d 0000 0072 3200 0000 7209 0000  der-...r2...r...
-00001070: 0072 0900 0000 720a 0000 00da 1876 616c  .r....r......val
-00001080: 6964 6174 655f 7465 616d 5f63 6f64 655f  idate_team_code_
-00001090: 6669 656c 645f 0000 0073 0600 0000 0002  field_...s......
-000010a0: 0c01 0801 7a2b 5061 7261 6d65 7465 7256  ....z+ParameterV
-000010b0: 616c 6964 6174 6f72 2e76 616c 6964 6174  alidator.validat
-000010c0: 655f 7465 616d 5f63 6f64 655f 6669 656c  e_team_code_fiel
-000010d0: 6463 0100 0000 0000 0000 0000 0000 0100  dc..............
-000010e0: 0000 0800 0000 4300 0000 7330 0000 007a  ......C...s0...z
-000010f0: 1074 00a0 017c 0064 01a1 0201 0057 006e  .t...|.d.....W.n
-00001100: 1a04 0074 0279 2a01 0001 0001 0074 0264  ...t.y*......t.d
-00001110: 0283 0182 0159 006e 0230 0064 0053 0029  .....Y.n.0.d.S.)
-00001120: 034e 7a08 2559 2d25 6d2d 2564 7a33 496e  .Nz.%Y-%m-%dz3In
-00001130: 7661 6c69 6420 6461 7465 2066 6f72 6d61  valid date forma
-00001140: 742e 2045 7870 6563 7465 6420 666f 726d  t. Expected form
-00001150: 6174 3a20 2759 5959 592d 4d4d 2d44 4427  at: 'YYYY-MM-DD'
-00001160: 2e29 0372 0200 0000 da08 7374 7270 7469  .).r......strpti
-00001170: 6d65 7208 0000 0029 01da 0464 6174 6572  mer....)...dater
-00001180: 0900 0000 7209 0000 0072 0a00 0000 da13  ....r....r......
-00001190: 7661 6c69 6461 7465 5f64 6174 655f 6669  validate_date_fi
-000011a0: 656c 6465 0000 0073 0800 0000 0002 0201  elde...s........
-000011b0: 1001 0c01 7a26 5061 7261 6d65 7465 7256  ....z&ParameterV
-000011c0: 616c 6964 6174 6f72 2e76 616c 6964 6174  alidator.validat
-000011d0: 655f 6461 7465 5f66 6965 6c64 2901 da03  e_date_field)...
-000011e0: 6964 7363 0100 0000 0000 0000 0000 0000  idsc............
-000011f0: 0200 0000 0400 0000 4300 0000 731c 0000  ........C...s...
-00001200: 0064 017d 0174 00a0 017c 017c 00a1 0273  .d.}.t...|.|...s
-00001210: 1874 0264 0283 0182 0164 0053 0029 034e  .t.d.....d.S.).N
-00001220: fa19 5e5c 647b 312c 7d28 3f3a 2d5c 647b  ..^\d{1,}(?:-\d{
-00001230: 312c 7d29 7b30 2c31 397d 247a 436e 6f74  1,}){0,19}$zCnot
-00001240: 2061 2076 616c 6964 2069 6473 2066 6f72   a valid ids for
-00001250: 6d61 742e 2066 6f72 6d61 743a 2027 6964  mat. format: 'id
-00001260: 2d69 642d 6964 2720 7769 7468 2061 206d  -id-id' with a m
-00001270: 6178 696d 756d 206f 6620 3230 2069 6473  aximum of 20 ids
-00001280: a903 7238 0000 0072 3900 0000 7208 0000  ..r8...r9...r...
-00001290: 0029 0272 4b00 0000 723a 0000 0072 0900  .).rK...r:...r..
-000012a0: 0000 7209 0000 0072 0a00 0000 da12 7661  ..r....r......va
-000012b0: 6c69 6461 7465 5f69 6473 5f66 6965 6c64  lidate_ids_field
-000012c0: 6c00 0000 7306 0000 0000 0204 010c 017a  l...s..........z
-000012d0: 2550 6172 616d 6574 6572 5661 6c69 6461  %ParameterValida
-000012e0: 746f 722e 7661 6c69 6461 7465 5f69 6473  tor.validate_ids
-000012f0: 5f66 6965 6c64 2901 da04 6c69 7665 6301  _field)...livec.
-00001300: 0000 0000 0000 0000 0000 0003 0000 0005  ................
-00001310: 0000 0043 0000 0073 3c00 0000 6401 7d01  ...C...s<...d.}.
-00001320: 6402 7d02 7400 7401 a002 7c01 7c00 a102  d.}.t.t...|.|...
-00001330: 8301 0100 7401 a002 7c01 7c00 a102 7338  ....t...|.|...s8
-00001340: 7401 a002 7c02 7c00 a102 7338 7403 6403  t...|.|...s8t.d.
-00001350: 8301 8201 6400 5300 2904 4e7a 0461 6c6c  ....d.S.).Nz.all
-00001360: 2472 4c00 0000 7a23 6c69 7665 2068 6173  $rL...z#live has
-00001370: 2076 616c 7565 7320 2761 6c6c 2720 6f72   values 'all' or
-00001380: 2027 6964 2d69 642d 6964 2729 04da 0570   'id-id-id')...p
-00001390: 7269 6e74 7238 0000 0072 3900 0000 7208  rintr8...r9...r.
-000013a0: 0000 0029 0372 4f00 0000 5a08 7061 7474  ...).rO...Z.patt
-000013b0: 6572 6e31 5a08 7061 7474 6572 6e32 7209  ern1Z.pattern2r.
-000013c0: 0000 0072 0900 0000 720a 0000 00da 1376  ...r....r......v
-000013d0: 616c 6964 6174 655f 6c69 7665 5f66 6965  alidate_live_fie
-000013e0: 6c64 7200 0000 730a 0000 0000 0204 0104  ldr...s.........
-000013f0: 0110 0118 017a 2650 6172 616d 6574 6572  .....z&Parameter
-00001400: 5661 6c69 6461 746f 722e 7661 6c69 6461  Validator.valida
-00001410: 7465 5f6c 6976 655f 6669 656c 64a9 01da  te_live_field...
-00001420: 056e 6578 745f 6301 0000 0000 0000 0000  .next_c.........
-00001430: 0000 0001 0000 0003 0000 0043 0000 0073  ...........C...s
-00001440: 1c00 0000 7400 7401 7c00 8301 8301 6401  ....t.t.|.....d.
-00001450: 6b01 7218 7402 6402 8301 8201 6400 5300  k.r.t.d.....d.S.
-00001460: 2903 4e72 4400 0000 7a34 5468 6520 6e65  ).NrD...z4The ne
-00001470: 7874 2066 6965 6c64 2063 616e 6e6f 7420  xt field cannot 
-00001480: 6578 6365 6564 2032 2063 6861 7261 6374  exceed 2 charact
-00001490: 6572 7320 696e 206c 656e 6774 682e 7245  ers in length.rE
-000014a0: 0000 0072 5200 0000 7209 0000 0072 0900  ...rR...r....r..
-000014b0: 0000 720a 0000 00da 1376 616c 6964 6174  ..r......validat
-000014c0: 655f 6e65 7874 5f66 6965 6c64 7a00 0000  e_next_fieldz...
-000014d0: 7306 0000 0000 0210 0108 017a 2650 6172  s..........z&Par
-000014e0: 616d 6574 6572 5661 6c69 6461 746f 722e  ameterValidator.
-000014f0: 7661 6c69 6461 7465 5f6e 6578 745f 6669  validate_next_fi
-00001500: 656c 6429 01da 0673 7461 7475 7363 0100  eld)...statusc..
-00001510: 0000 0000 0000 0000 0000 0300 0000 0600  ................
-00001520: 0000 4300 0000 7338 0000 0067 0064 01a2  ..C...s8...g.d..
-00001530: 017d 0164 02a0 0064 03a0 017c 01a1 0164  .}.d...d...|...d
-00001540: 03a0 017c 01a1 01a1 027d 0274 02a0 037c  ...|.....}.t...|
-00001550: 027c 00a1 0273 3474 0464 0483 0182 0164  .|...s4t.d.....d
-00001560: 0053 0029 054e 2913 5a03 5442 445a 024e  .S.).N).Z.TBDZ.N
-00001570: 535a 0231 485a 0248 545a 0232 48da 0245  SZ.1HZ.HTZ.2H..E
-00001580: 545a 0242 54da 0150 5a04 5355 5350 5a03  TZ.BT..PZ.SUSPZ.
-00001590: 494e 545a 0246 545a 0341 4554 5a03 5045  INTZ.FTZ.AETZ.PE
-000015a0: 4eda 0350 5354 5a04 4341 4e43 5a03 4142  N..PSTZ.CANCZ.AB
-000015b0: 445a 0341 5744 5a02 574f 5a04 4c49 5645  DZ.AWDZ.WOZ.LIVE
-000015c0: 7a10 5e28 7b7d 2928 3f3a 2d28 7b7d 2929  z.^({})(?:-({}))
-000015d0: 2a24 da01 7c7a 2149 6e63 6f72 7265 6374  *$..|z!Incorrect
-000015e0: 2073 7461 7475 7320 7661 6c75 6520 7072   status value pr
-000015f0: 6f76 6964 6564 2e20 2905 da06 666f 726d  ovided. )...form
-00001600: 6174 7228 0000 0072 3800 0000 7239 0000  atr(...r8...r9..
-00001610: 0072 0800 0000 2903 7255 0000 005a 1661  .r....).rU...Z.a
-00001620: 6c6c 6f77 6564 5f66 6978 7475 7265 5f73  llowed_fixture_s
-00001630: 7461 7475 7372 3a00 0000 7209 0000 0072  tatusr:...r....r
-00001640: 0900 0000 720a 0000 00da 1576 616c 6964  ....r......valid
-00001650: 6174 655f 7374 6174 7573 5f66 6965 6c64  ate_status_field
-00001660: 8000 0000 730a 0000 0000 0208 1618 020c  ....s...........
-00001670: 0108 017a 2850 6172 616d 6574 6572 5661  ...z(ParameterVa
-00001680: 6c69 6461 746f 722e 7661 6c69 6461 7465  lidator.validate
-00001690: 5f73 7461 7475 735f 6669 656c 6429 01da  _status_field)..
-000016a0: 0368 3268 6301 0000 0000 0000 0000 0000  .h2hc...........
-000016b0: 0002 0000 0004 0000 0043 0000 0073 1c00  .........C...s..
-000016c0: 0000 6401 7d01 7400 a001 7c01 7c00 a102  ..d.}.t...|.|...
-000016d0: 7318 7402 6402 8301 8201 6400 5300 2903  s.t.d.....d.S.).
-000016e0: 4e7a 0e5e 5c64 7b31 2c7d 2d5c 647b 312c  Nz.^\d{1,}-\d{1,
-000016f0: 7d7a 1449 6e63 6f72 7265 6374 2068 3268  }z.Incorrect h2h
-00001700: 2076 616c 7565 2e72 4d00 0000 2902 725c   value.rM...).r\
-00001710: 0000 0072 3a00 0000 7209 0000 0072 0900  ...r:...r....r..
-00001720: 0000 720a 0000 00da 1276 616c 6964 6174  ..r......validat
-00001730: 655f 6832 685f 6669 656c 649e 0000 0073  e_h2h_field....s
-00001740: 0800 0000 0002 0402 0c01 0801 7a25 5061  ............z%Pa
-00001750: 7261 6d65 7465 7256 616c 6964 6174 6f72  rameterValidator
-00001760: 2e76 616c 6964 6174 655f 6832 685f 6669  .validate_h2h_fi
-00001770: 656c 6463 0100 0000 0000 0000 0000 0000  eldc............
-00001780: 0200 0000 0200 0000 4300 0000 7320 0000  ........C...s ..
-00001790: 0068 0064 01a3 017d 017c 00a0 00a1 007c  .h.d...}.|.....|
-000017a0: 0176 0172 1c74 0164 0283 0182 0164 0053  .v.r.t.d.....d.S
-000017b0: 0029 034e 3e03 0000 00da 0573 7562 7374  .).N>......subst
-000017c0: da04 676f 616c 5a04 6361 7264 7a31 5468  ..goalZ.cardz1Th
-000017d0: 6520 5479 7065 2066 6965 6c64 206d 7573  e Type field mus
-000017e0: 7420 6265 206f 6e65 206f 663a 2067 6f61  t be one of: goa
-000017f0: 6c2c 2063 6172 642c 2073 7562 7374 2ea9  l, card, subst..
-00001800: 0272 0700 0000 7208 0000 00a9 0272 2900  .r....r......r).
-00001810: 0000 5a0d 5f61 6c6c 6f77 6564 5f76 616c  ..Z._allowed_val
-00001820: 7372 0900 0000 7209 0000 0072 0a00 0000  sr....r....r....
-00001830: da22 7661 6c69 6461 7465 5f66 6978 7475  ."validate_fixtu
-00001840: 7265 5f65 7665 6e74 735f 7479 7065 5f66  re_events_type_f
-00001850: 6965 6c64 a600 0000 7306 0000 0000 0208  ield....s.......
-00001860: 020c 017a 3550 6172 616d 6574 6572 5661  ...z5ParameterVa
-00001870: 6c69 6461 746f 722e 7661 6c69 6461 7465  lidator.validate
-00001880: 5f66 6978 7475 7265 5f65 7665 6e74 735f  _fixture_events_
-00001890: 7479 7065 5f66 6965 6c64 6301 0000 0000  type_fieldc.....
-000018a0: 0000 0000 0000 0002 0000 0003 0000 0043  ...............C
-000018b0: 0000 0073 2600 0000 6800 6401 a301 7d01  ...s&...h.d...}.
-000018c0: 7c00 a000 a100 7c01 7601 7222 7401 6402  |.....|.v.r"t.d.
-000018d0: 7c01 9b00 9d02 8301 8201 6400 5300 2903  |.........d.S.).
-000018e0: 4e3e 1000 0000 5a08 6f66 6673 6964 6573  N>....Z.offsides
-000018f0: 7a10 676f 616c 6b65 6570 6572 2073 6176  z.goalkeeper sav
-00001900: 6573 7a10 7368 6f74 7320 6f75 7473 6964  esz.shots outsid
-00001910: 6562 6f78 7a0c 636f 726e 6572 206b 6963  eboxz.corner kic
-00001920: 6b73 7a0f 7368 6f74 7320 696e 7369 6465  ksz.shots inside
-00001930: 626f 787a 0f62 616c 6c20 706f 7373 6573  boxz.ball posses
-00001940: 7369 6f6e 5a05 666f 756c 737a 0c79 656c  sionZ.foulsz.yel
-00001950: 6c6f 7720 6361 7264 737a 0d73 686f 7473  low cardsz.shots
-00001960: 206f 6e20 676f 616c 7a0e 7368 6f74 7320   on goalz.shots 
-00001970: 6f66 6620 676f 616c 7a09 7265 6420 6361  off goalz.red ca
-00001980: 7264 737a 0b74 6f74 616c 2073 686f 7473  rdsz.total shots
-00001990: 7a0d 626c 6f63 6b65 6420 7368 6f74 737a  z.blocked shotsz
-000019a0: 0f70 6173 7365 7320 6163 6375 7261 7465  .passes accurate
-000019b0: 7a08 7061 7373 6573 2025 7a0c 746f 7461  z.passes %z.tota
-000019c0: 6c20 7061 7373 6573 7a22 204e 6f74 2076  l passesz" Not v
-000019d0: 616c 6964 2074 7970 652e 2041 7661 696c  alid type. Avail
-000019e0: 6162 6c65 2074 7970 6573 3a20 7260 0000  able types: r`..
-000019f0: 0072 6100 0000 7209 0000 0072 0900 0000  .ra...r....r....
-00001a00: 720a 0000 00da 2676 616c 6964 6174 655f  r.....&validate_
-00001a10: 6669 7874 7572 655f 7374 6174 6973 7469  fixture_statisti
-00001a20: 6373 5f74 7970 655f 6669 656c 64ad 0000  cs_type_field...
-00001a30: 0073 0600 0000 0002 0812 0c01 7a39 5061  .s..........z9Pa
-00001a40: 7261 6d65 7465 7256 616c 6964 6174 6f72  rameterValidator
-00001a50: 2e76 616c 6964 6174 655f 6669 7874 7572  .validate_fixtur
-00001a60: 655f 7374 6174 6973 7469 6373 5f74 7970  e_statistics_typ
-00001a70: 655f 6669 656c 644e 291b da08 5f5f 6e61  e_fieldN)...__na
-00001a80: 6d65 5f5f da0a 5f5f 6d6f 6475 6c65 5f5f  me__..__module__
-00001a90: da0c 5f5f 7175 616c 6e61 6d65 5f5f da0c  ..__qualname__..
-00001aa0: 7374 6174 6963 6d65 7468 6f64 7218 0000  staticmethodr...
-00001ab0: 0072 0b00 0000 7213 0000 0072 1a00 0000  .r....r....r....
-00001ac0: 721b 0000 0072 1c00 0000 722a 0000 0072  r....r....r*...r
-00001ad0: 2f00 0000 7231 0000 0072 3700 0000 723b  /...r1...r7...r;
-00001ae0: 0000 0072 3e00 0000 7241 0000 0072 4600  ...r>...rA...rF.
-00001af0: 0000 7247 0000 0072 4a00 0000 724e 0000  ..rG...rJ...rN..
-00001b00: 0072 5100 0000 7254 0000 0072 5b00 0000  .rQ...rT...r[...
-00001b10: 725d 0000 0072 6200 0000 7263 0000 0072  r]...rb...rc...r
-00001b20: 0900 0000 7209 0000 0072 0900 0000 720a  ....r....r....r.
-00001b30: 0000 0072 0500 0000 0900 0000 7354 0000  ...r........sT..
-00001b40: 0008 0202 0110 0602 010a 0502 0112 0402  ................
-00001b50: 0112 0402 010a 1102 0110 0402 010a 0402  ................
-00001b60: 0110 0402 0110 0602 0110 0702 0110 0602  ................
-00001b70: 0110 0502 010a 0502 010a 0602 0110 0502  ................
-00001b80: 0110 0702 0110 0502 0110 1d02 0110 0702  ................
-00001b90: 0110 0602 0172 0500 0000 2907 7238 0000  .....r....).r8..
-00001ba0: 0072 0200 0000 7234 0000 00da 1c66 6f6f  .r....r4.....foo
-00001bb0: 7462 616c 6c41 5049 436c 6965 6e74 2e5f  tballAPIClient._
-00001bc0: 636f 6e73 7461 6e74 7372 0300 0000 7204  constantsr....r.
-00001bd0: 0000 0072 0500 0000 7209 0000 0072 0900  ...r....r....r..
-00001be0: 0000 7209 0000 0072 0a00 0000 da08 3c6d  ..r....r......<m
-00001bf0: 6f64 756c 653e 0100 0000 730a 0000 0008  odule>....s.....
-00001c00: 010c 0108 020c 010c 03                   .........
+00000220: 0164 3564 3684 0483 015a 1a65 0365 0464  .d5d6....Z.e.e.d
+00000230: 189c 0164 3764 3884 0483 015a 1b64 3953  ...d7d8....Z.d9S
+00000240: 0029 3ada 1250 6172 616d 6574 6572 5661  .):..ParameterVa
+00000250: 6c69 6461 746f 7229 01da 0668 6561 6465  lidator)...heade
+00000260: 7263 0100 0000 0000 0000 0000 0000 0200  rc..............
+00000270: 0000 0200 0000 4300 0000 7320 0000 0074  ......C...s ...t
+00000280: 0074 0168 027d 017c 00a0 02a1 007c 0176  .t.h.}.|.....|.v
+00000290: 0172 1c74 0364 0183 0182 0164 0053 0029  .r.t.d.....d.S.)
+000002a0: 024e 7a32 616c 6c6f 7765 6420 6163 636f  .Nz2allowed acco
+000002b0: 756e 7420 7479 7065 7320 3a20 2772 6170  unt types : 'rap
+000002c0: 6964 2d61 7069 272c 2027 6170 692d 7370  id-api', 'api-sp
+000002d0: 6f72 7473 2720 2904 7203 0000 0072 0400  orts' ).r....r..
+000002e0: 0000 da05 6c6f 7765 72da 0a56 616c 7565  ....lower..Value
+000002f0: 4572 726f 7229 0272 0600 0000 5a10 616c  Error).r....Z.al
+00000300: 6c6f 7765 645f 6163 636f 756e 7473 a900  lowed_accounts..
+00000310: 7209 0000 00fa 5c45 3a5c 436f 6465 735c  r.....\E:\Codes\
+00000320: 5079 6368 6172 6d50 726f 6a65 6374 735c  PycharmProjects\
+00000330: 666f 6f74 6261 6c6c 2d41 5049 2d63 6c69  football-API-cli
+00000340: 656e 745c 666f 6f74 6261 6c6c 4150 4943  ent\footballAPIC
+00000350: 6c69 656e 745c 6865 6c70 6572 735c 5061  lient\helpers\Pa
+00000360: 7261 6d65 7465 7256 616c 6964 6174 6f72  rameterValidator
+00000370: 2e70 79da 1c76 616c 6964 6174 655f 6163  .py..validate_ac
+00000380: 636f 756e 745f 6865 6164 6572 5f74 7970  count_header_typ
+00000390: 650b 0000 0073 0600 0000 0002 0802 0c01  e....s..........
+000003a0: 7a2f 5061 7261 6d65 7465 7256 616c 6964  z/ParameterValid
+000003b0: 6174 6f72 2e76 616c 6964 6174 655f 6163  ator.validate_ac
+000003c0: 636f 756e 745f 6865 6164 6572 5f74 7970  count_header_typ
+000003d0: 6563 0000 0000 0000 0000 0000 0000 0100  ec..............
+000003e0: 0000 0300 0000 4700 0000 731a 0000 0074  ......G...s....t
+000003f0: 0064 0164 0284 007c 0044 0083 0183 0172  .d.d...|.D.....r
+00000400: 1664 0353 0064 0453 0029 054e 6301 0000  .d.S.d.S.).Nc...
+00000410: 0000 0000 0000 0000 0002 0000 0003 0000  ................
+00000420: 0073 0000 0073 1600 0000 7c00 5d0e 7d01  .s...s....|.].}.
+00000430: 7c01 6400 7500 5600 0100 7102 6400 5300  |.d.u.V...q.d.S.
+00000440: a901 4e72 0900 0000 2902 da02 2e30 da05  ..Nr....)....0..
+00000450: 7061 7261 6d72 0900 0000 7209 0000 0072  paramr....r....r
+00000460: 0a00 0000 da09 3c67 656e 6578 7072 3e14  ......<genexpr>.
+00000470: 0000 00f3 0000 0000 7a3a 5061 7261 6d65  ........z:Parame
+00000480: 7465 7256 616c 6964 6174 6f72 2e63 6865  terValidator.che
+00000490: 636b 5f6d 6973 7369 6e67 5f70 6172 616d  ck_missing_param
+000004a0: 732e 3c6c 6f63 616c 733e 2e3c 6765 6e65  s.<locals>.<gene
+000004b0: 7870 723e 5446 2901 da03 616c 6c29 01da  xpr>TF)...all)..
+000004c0: 0461 7267 7372 0900 0000 7209 0000 0072  .argsr....r....r
+000004d0: 0a00 0000 da14 6368 6563 6b5f 6d69 7373  ......check_miss
+000004e0: 696e 675f 7061 7261 6d73 1200 0000 7306  ing_params....s.
+000004f0: 0000 0000 0212 0104 017a 2750 6172 616d  .........z'Param
+00000500: 6574 6572 5661 6c69 6461 746f 722e 6368  eterValidator.ch
+00000510: 6563 6b5f 6d69 7373 696e 675f 7061 7261  eck_missing_para
+00000520: 6d73 a902 da03 7661 6cda 0a66 6965 6c64  ms....val..field
+00000530: 5f6e 616d 6563 0200 0000 0000 0000 0000  _namec..........
+00000540: 0000 0200 0000 0300 0000 4300 0000 731c  ..........C...s.
+00000550: 0000 0074 007c 0074 0183 0273 1874 027c  ...t.|.t...s.t.|
+00000560: 019b 0064 019d 0283 0182 0164 0053 0029  ...d.......d.S.)
+00000570: 024e 7a13 206d 7573 7420 6265 2061 6e20  .Nz. must be an 
+00000580: 7374 7269 6e67 2e29 03da 0a69 7369 6e73  string.)...isins
+00000590: 7461 6e63 65da 0373 7472 da09 5479 7065  tance..str..Type
+000005a0: 4572 726f 7272 1400 0000 7209 0000 0072  Errorr....r....r
+000005b0: 0900 0000 720a 0000 00da 1176 616c 6964  ....r......valid
+000005c0: 6174 655f 7479 7065 5f73 7472 1800 0000  ate_type_str....
+000005d0: 7304 0000 0000 020a 017a 2450 6172 616d  s........z$Param
+000005e0: 6574 6572 5661 6c69 6461 746f 722e 7661  eterValidator.va
+000005f0: 6c69 6461 7465 5f74 7970 655f 7374 7263  lidate_type_strc
+00000600: 0200 0000 0000 0000 0000 0000 0200 0000  ................
+00000610: 0300 0000 4300 0000 731c 0000 0074 007c  ....C...s....t.|
+00000620: 0074 0183 0273 1874 027c 019b 0064 019d  .t...s.t.|...d..
+00000630: 0283 0182 0164 0053 0029 024e 7a14 206d  .....d.S.).Nz. m
+00000640: 7573 7420 6265 2061 6e20 696e 7465 6765  ust be an intege
+00000650: 722e 2903 7217 0000 00da 0369 6e74 7219  r.).r......intr.
+00000660: 0000 0072 1400 0000 7209 0000 0072 0900  ...r....r....r..
+00000670: 0000 720a 0000 00da 1176 616c 6964 6174  ..r......validat
+00000680: 655f 7479 7065 5f69 6e74 1d00 0000 7304  e_type_int....s.
+00000690: 0000 0000 020a 017a 2450 6172 616d 6574  .......z$Paramet
+000006a0: 6572 5661 6c69 6461 746f 722e 7661 6c69  erValidator.vali
+000006b0: 6461 7465 5f74 7970 655f 696e 7463 0000  date_type_intc..
+000006c0: 0000 0000 0000 0000 0000 0600 0000 0800  ................
+000006d0: 0000 0b00 0000 7394 0000 0064 0164 0264  ......s....d.d.d
+000006e0: 0367 0266 0264 0464 0264 0567 0266 0264  .g.f.d.d.d.g.f.d
+000006f0: 0364 0467 0166 0264 0264 0467 0166 0264  .d.g.f.d.d.g.f.d
+00000700: 0564 0467 0166 0264 0667 0064 07a2 0166  .d.g.f.d.g.d...f
+00000710: 0267 067d 017c 0144 005d 505c 027d 027d  .g.}.|.D.]P\.}.}
+00000720: 0388 00a0 007c 02a1 017d 047c 0464 0075  .....|...}.|.d.u
+00000730: 0172 3e74 0187 0066 0164 0864 0984 087c  .r>t...f.d.d...|
+00000740: 0344 0083 0183 0172 3e64 0aa0 027c 03a1  .D.....r>d...|..
+00000750: 017d 0574 0364 0b7c 029b 0064 0c7c 059b  .}.t.d.|...d.|..
+00000760: 0064 0d9d 0583 0182 0171 3e64 0053 0029  .d.......q>d.S.)
+00000770: 0e4e da06 7365 6172 6368 da06 6c65 6167  .N..search..leag
+00000780: 7565 da04 7465 616d da06 7365 6173 6f6e  ue..team..season
+00000790: da02 6964 da04 7061 6765 2905 721d 0000  ..id..page).r...
+000007a0: 0072 2000 0000 721f 0000 0072 1e00 0000  .r ...r....r....
+000007b0: 7221 0000 0063 0100 0000 0000 0000 0000  r!...c..........
+000007c0: 0000 0200 0000 0400 0000 3300 0000 731c  ..........3...s.
+000007d0: 0000 007c 005d 147d 0188 00a0 007c 01a1  ...|.].}.....|..
+000007e0: 0164 0075 0056 0001 0071 0264 0053 0072  .d.u.V...q.d.S.r
+000007f0: 0c00 0000 2901 da03 6765 7429 0272 0d00  ....)...get).r..
+00000800: 0000 5a0e 7265 7175 6972 6564 5f66 6965  ..Z.required_fie
+00000810: 6c64 a901 da06 6b77 6172 6773 7209 0000  ld....kwargsr...
+00000820: 0072 0a00 0000 720f 0000 002f 0000 0073  .r....r..../...s
+00000830: 0200 0000 0401 7a3c 5061 7261 6d65 7465  ......z<Paramete
+00000840: 7256 616c 6964 6174 6f72 2e76 616c 6964  rValidator.valid
+00000850: 6174 655f 706c 6179 6572 5f66 6965 6c64  ate_player_field
+00000860: 732e 3c6c 6f63 616c 733e 2e3c 6765 6e65  s.<locals>.<gene
+00000870: 7870 723e 7a02 2c20 fa01 277a 2d27 2072  xpr>z., ..'z-' r
+00000880: 6571 7569 7265 7320 6174 206c 6561 7374  equires at least
+00000890: 206f 6e65 206f 6620 7468 6520 6f74 6865   one of the othe
+000008a0: 7220 6669 656c 6473 3a20 da01 2e29 0472  r fields: ...).r
+000008b0: 2300 0000 7211 0000 00da 046a 6f69 6e72  #...r......joinr
+000008c0: 0800 0000 2906 7225 0000 005a 0b66 6965  ....).r%...Z.fie
+000008d0: 6c64 5f70 6169 7273 da05 6669 656c 645a  ld_pairs..fieldZ
+000008e0: 0f72 6571 7569 7265 645f 6669 656c 6473  .required_fields
+000008f0: 5a0b 6669 656c 645f 7661 6c75 655a 1472  Z.field_valueZ.r
+00000900: 6571 7569 7265 645f 6669 656c 645f 6e61  equired_field_na
+00000910: 6d65 7372 0900 0000 7224 0000 0072 0a00  mesr....r$...r..
+00000920: 0000 da16 7661 6c69 6461 7465 5f70 6c61  ....validate_pla
+00000930: 7965 725f 6669 656c 6473 2200 0000 731c  yer_fields"...s.
+00000940: 0000 0000 030a 010a 0108 0108 0108 010a  ................
+00000950: fa04 090c 010a 0114 0102 ff08 020a 017a  ...............z
+00000960: 2950 6172 616d 6574 6572 5661 6c69 6461  )ParameterValida
+00000970: 746f 722e 7661 6c69 6461 7465 5f70 6c61  tor.validate_pla
+00000980: 7965 725f 6669 656c 6473 a901 721d 0000  yer_fields..r...
+00000990: 0063 0100 0000 0000 0000 0000 0000 0100  .c..............
+000009a0: 0000 0200 0000 4300 0000 7318 0000 0074  ......C...s....t
+000009b0: 007c 0083 0164 016b 0572 1474 0164 0283  .|...d.k.r.t.d..
+000009c0: 0182 0164 0053 0029 034e e903 0000 007a  ...d.S.).N.....z
+000009d0: 2d20 5365 6172 6368 2066 6965 6c64 206d  - Search field m
+000009e0: 7573 7420 6861 7665 2061 7420 6c65 6173  ust have at leas
+000009f0: 7420 3320 6368 6172 6163 7465 7273 a902  t 3 characters..
+00000a00: da03 6c65 6e72 0800 0000 722b 0000 0072  ..lenr....r+...r
+00000a10: 0900 0000 7209 0000 0072 0a00 0000 da15  ....r....r......
+00000a20: 7661 6c69 6461 7465 5f73 6561 7263 685f  validate_search_
+00000a30: 6669 656c 6434 0000 0073 0400 0000 0002  field4...s......
+00000a40: 0c01 7a28 5061 7261 6d65 7465 7256 616c  ..z(ParameterVal
+00000a50: 6964 6174 6f72 2e76 616c 6964 6174 655f  idator.validate_
+00000a60: 7365 6172 6368 5f66 6965 6c64 6301 0000  search_fieldc...
+00000a70: 0000 0000 0000 0000 0001 0000 0002 0000  ................
+00000a80: 0043 0000 0073 1800 0000 7400 7c00 8301  .C...s....t.|...
+00000a90: 6401 6b05 7214 7401 6402 8301 8201 6400  d.k.r.t.d.....d.
+00000aa0: 5300 2903 4ee9 0400 0000 7a2d 2053 6561  S.).N.....z- Sea
+00000ab0: 7263 6820 6669 656c 6420 6d75 7374 2068  rch field must h
+00000ac0: 6176 6520 6174 206c 6561 7374 2034 2063  ave at least 4 c
+00000ad0: 6861 7261 6374 6572 7372 2d00 0000 722b  haractersr-...r+
+00000ae0: 0000 0072 0900 0000 7209 0000 0072 0a00  ...r....r....r..
+00000af0: 0000 da1c 7661 6c69 6461 7465 5f70 6c61  ....validate_pla
+00000b00: 7965 725f 7365 6172 6368 5f66 6965 6c64  yer_search_field
+00000b10: 3900 0000 7304 0000 0000 020c 017a 2f50  9...s........z/P
+00000b20: 6172 616d 6574 6572 5661 6c69 6461 746f  arameterValidato
+00000b30: 722e 7661 6c69 6461 7465 5f70 6c61 7965  r.validate_playe
+00000b40: 725f 7365 6172 6368 5f66 6965 6c64 a901  r_search_field..
+00000b50: da04 636f 6465 6301 0000 0000 0000 0000  ..codec.........
+00000b60: 0000 0001 0000 0003 0000 0043 0000 0073  ...........C...s
+00000b70: 2400 0000 7400 6a01 6a02 7c00 6401 8d01  $...t.j.j.|.d...
+00000b80: 6400 7500 7220 7403 7c00 9b00 6402 9d02  d.u.r t.|...d...
+00000b90: 8301 8201 6400 5300 2903 4e29 015a 0761  ....d.S.).N).Z.a
+00000ba0: 6c70 6861 5f32 7a1c 2069 7320 6e6f 7420  lpha_2z. is not 
+00000bb0: 6120 7661 6c69 6420 636f 756e 7472 7920  a valid country 
+00000bc0: 636f 6465 2904 da09 7079 636f 756e 7472  code)...pycountr
+00000bd0: 79da 0963 6f75 6e74 7269 6573 7223 0000  y..countriesr#..
+00000be0: 00da 0b4c 6f6f 6b75 7045 7272 6f72 7232  ...LookupErrorr2
+00000bf0: 0000 0072 0900 0000 7209 0000 0072 0a00  ...r....r....r..
+00000c00: 0000 da13 7661 6c69 6461 7465 5f63 6f64  ....validate_cod
+00000c10: 655f 6669 656c 643e 0000 0073 0400 0000  e_field>...s....
+00000c20: 0002 1201 7a26 5061 7261 6d65 7465 7256  ....z&ParameterV
+00000c30: 616c 6964 6174 6f72 2e76 616c 6964 6174  alidator.validat
+00000c40: 655f 636f 6465 5f66 6965 6c64 2901 7220  e_code_field).r 
+00000c50: 0000 0063 0100 0000 0000 0000 0000 0000  ...c............
+00000c60: 0200 0000 0500 0000 4300 0000 7320 0000  ........C...s ..
+00000c70: 0064 017d 0174 00a0 017c 0174 027c 0083  .d.}.t...|.t.|..
+00000c80: 01a1 0273 1c74 0364 0283 0182 0164 0053  ...s.t.d.....d.S
+00000c90: 0029 034e 7a07 5e5c 647b 347d 247a 3449  .).Nz.^\d{4}$z4I
+00000ca0: 6e76 616c 6964 2073 6561 736f 6e20 666f  nvalid season fo
+00000cb0: 726d 6174 2e20 4578 7065 6374 6564 2066  rmat. Expected f
+00000cc0: 6f72 6d61 743a 2059 5959 5920 2879 6561  ormat: YYYY (yea
+00000cd0: 7229 2e29 04da 0272 65da 056d 6174 6368  r).)...re..match
+00000ce0: 7218 0000 0072 0800 0000 2902 7220 0000  r....r....).r ..
+00000cf0: 00da 0770 6174 7465 726e 7209 0000 0072  ...patternr....r
+00000d00: 0900 0000 720a 0000 00da 1576 616c 6964  ....r......valid
+00000d10: 6174 655f 7365 6173 6f6e 5f66 6965 6c64  ate_season_field
+00000d20: 4300 0000 7308 0000 0000 0204 0110 0108  C...s...........
+00000d30: 017a 2850 6172 616d 6574 6572 5661 6c69  .z(ParameterVali
+00000d40: 6461 746f 722e 7661 6c69 6461 7465 5f73  dator.validate_s
+00000d50: 6561 736f 6e5f 6669 656c 6429 0172 2900  eason_field).r).
+00000d60: 0000 6301 0000 0000 0000 0000 0000 0002  ..c.............
+00000d70: 0000 0002 0000 0043 0000 0073 1c00 0000  .......C...s....
+00000d80: 6401 6402 6802 7d01 7c00 7c01 7601 7218  d.d.h.}.|.|.v.r.
+00000d90: 7400 6403 8301 8201 6400 5300 2904 4e72  t.d.....d.S.).Nr
+00000da0: 1e00 0000 da03 6375 707a 1c61 6c6c 6f77  ......cupz.allow
+00000db0: 6564 2076 616c 7565 7320 3a20 6c65 6167  ed values : leag
+00000dc0: 7565 2c20 6375 70a9 0172 0800 0000 a902  ue, cup..r......
+00000dd0: 7229 0000 005a 0c61 6c6c 6f77 6564 5f76  r)...Z.allowed_v
+00000de0: 616c 7372 0900 0000 7209 0000 0072 0a00  alsr....r....r..
+00000df0: 0000 da13 7661 6c69 6461 7465 5f74 7970  ....validate_typ
+00000e00: 655f 6669 656c 644a 0000 0073 0800 0000  e_fieldJ...s....
+00000e10: 0002 0801 0801 0802 7a26 5061 7261 6d65  ........z&Parame
+00000e20: 7465 7256 616c 6964 6174 6f72 2e76 616c  terValidator.val
+00000e30: 6964 6174 655f 7479 7065 5f66 6965 6c64  idate_type_field
+00000e40: 6301 0000 0000 0000 0000 0000 0002 0000  c...............
+00000e50: 0002 0000 0043 0000 0073 1c00 0000 6401  .....C...s....d.
+00000e60: 6402 6802 7d01 7c00 7c01 7601 7218 7400  d.h.}.|.|.v.r.t.
+00000e70: 6403 8301 8201 6400 5300 2904 4eda 0474  d.....d.S.).N..t
+00000e80: 7275 65da 0566 616c 7365 7a35 616c 6c6f  rue..falsez5allo
+00000e90: 7765 6420 7661 6c75 6573 2069 6e20 6375  wed values in cu
+00000ea0: 7272 656e 7420 6669 656c 6420 6172 6520  rrent field are 
+00000eb0: 3a20 2774 7275 6527 2c20 2766 616c 7365  : 'true', 'false
+00000ec0: 2772 3d00 0000 723e 0000 0072 0900 0000  'r=...r>...r....
+00000ed0: 7209 0000 0072 0a00 0000 da16 7661 6c69  r....r......vali
+00000ee0: 6461 7465 5f63 7572 7265 6e74 5f66 6965  date_current_fie
+00000ef0: 6c64 5200 0000 7308 0000 0000 0208 0108  ldR...s.........
+00000f00: 0108 017a 2950 6172 616d 6574 6572 5661  ...z)ParameterVa
+00000f10: 6c69 6461 746f 722e 7661 6c69 6461 7465  lidator.validate
+00000f20: 5f63 7572 7265 6e74 5f66 6965 6c64 a901  _current_field..
+00000f30: da04 6c61 7374 6301 0000 0000 0000 0000  ..lastc.........
+00000f40: 0000 0001 0000 0003 0000 0043 0000 0073  ...........C...s
+00000f50: 1c00 0000 7400 7401 7c00 8301 8301 6401  ....t.t.|.....d.
+00000f60: 6b01 7218 7402 6402 8301 8201 6400 5300  k.r.t.d.....d.S.
+00000f70: 2903 4ee9 0200 0000 7a34 5468 6520 6c61  ).N.....z4The la
+00000f80: 7374 2066 6965 6c64 2063 616e 6e6f 7420  st field cannot 
+00000f90: 6578 6365 6564 2032 2063 6861 7261 6374  exceed 2 charact
+00000fa0: 6572 7320 696e 206c 656e 6774 682e a903  ers in length...
+00000fb0: 722e 0000 0072 1800 0000 7208 0000 0072  r....r....r....r
+00000fc0: 4300 0000 7209 0000 0072 0900 0000 720a  C...r....r....r.
+00000fd0: 0000 00da 1376 616c 6964 6174 655f 6c61  .....validate_la
+00000fe0: 7374 5f66 6965 6c64 5900 0000 7306 0000  st_fieldY...s...
+00000ff0: 0000 0210 0108 017a 2650 6172 616d 6574  .......z&Paramet
+00001000: 6572 5661 6c69 6461 746f 722e 7661 6c69  erValidator.vali
+00001010: 6461 7465 5f6c 6173 745f 6669 656c 6463  date_last_fieldc
+00001020: 0100 0000 0000 0000 0000 0000 0100 0000  ................
+00001030: 0200 0000 4300 0000 7318 0000 0074 007c  ....C...s....t.|
+00001040: 0083 0164 016b 0372 1474 0164 0283 0182  ...d.k.r.t.d....
+00001050: 0164 0053 0029 034e 722c 0000 007a 154e  .d.S.).Nr,...z.N
+00001060: 6f74 2061 2076 616c 6964 2074 6561 6d20  ot a valid team 
+00001070: 636f 6465 722d 0000 0072 3200 0000 7209  coder-...r2...r.
+00001080: 0000 0072 0900 0000 720a 0000 00da 1876  ...r....r......v
+00001090: 616c 6964 6174 655f 7465 616d 5f63 6f64  alidate_team_cod
+000010a0: 655f 6669 656c 645f 0000 0073 0600 0000  e_field_...s....
+000010b0: 0002 0c01 0801 7a2b 5061 7261 6d65 7465  ......z+Paramete
+000010c0: 7256 616c 6964 6174 6f72 2e76 616c 6964  rValidator.valid
+000010d0: 6174 655f 7465 616d 5f63 6f64 655f 6669  ate_team_code_fi
+000010e0: 656c 6463 0100 0000 0000 0000 0000 0000  eldc............
+000010f0: 0100 0000 0800 0000 4300 0000 7330 0000  ........C...s0..
+00001100: 007a 1074 00a0 017c 0064 01a1 0201 0057  .z.t...|.d.....W
+00001110: 006e 1a04 0074 0279 2a01 0001 0001 0074  .n...t.y*......t
+00001120: 0264 0283 0182 0159 006e 0230 0064 0053  .d.....Y.n.0.d.S
+00001130: 0029 034e 7a08 2559 2d25 6d2d 2564 7a33  .).Nz.%Y-%m-%dz3
+00001140: 496e 7661 6c69 6420 6461 7465 2066 6f72  Invalid date for
+00001150: 6d61 742e 2045 7870 6563 7465 6420 666f  mat. Expected fo
+00001160: 726d 6174 3a20 2759 5959 592d 4d4d 2d44  rmat: 'YYYY-MM-D
+00001170: 4427 2e29 0372 0200 0000 da08 7374 7270  D'.).r......strp
+00001180: 7469 6d65 7208 0000 0029 01da 0464 6174  timer....)...dat
+00001190: 6572 0900 0000 7209 0000 0072 0a00 0000  er....r....r....
+000011a0: da13 7661 6c69 6461 7465 5f64 6174 655f  ..validate_date_
+000011b0: 6669 656c 6465 0000 0073 0800 0000 0002  fielde...s......
+000011c0: 0201 1001 0c01 7a26 5061 7261 6d65 7465  ......z&Paramete
+000011d0: 7256 616c 6964 6174 6f72 2e76 616c 6964  rValidator.valid
+000011e0: 6174 655f 6461 7465 5f66 6965 6c64 2901  ate_date_field).
+000011f0: da03 6964 7363 0100 0000 0000 0000 0000  ..idsc..........
+00001200: 0000 0200 0000 0400 0000 4300 0000 731c  ..........C...s.
+00001210: 0000 0064 017d 0174 00a0 017c 017c 00a1  ...d.}.t...|.|..
+00001220: 0273 1874 0264 0283 0182 0164 0053 0029  .s.t.d.....d.S.)
+00001230: 034e fa19 5e5c 647b 312c 7d28 3f3a 2d5c  .N..^\d{1,}(?:-\
+00001240: 647b 312c 7d29 7b30 2c31 397d 247a 436e  d{1,}){0,19}$zCn
+00001250: 6f74 2061 2076 616c 6964 2069 6473 2066  ot a valid ids f
+00001260: 6f72 6d61 742e 2066 6f72 6d61 743a 2027  ormat. format: '
+00001270: 6964 2d69 642d 6964 2720 7769 7468 2061  id-id-id' with a
+00001280: 206d 6178 696d 756d 206f 6620 3230 2069   maximum of 20 i
+00001290: 6473 a903 7238 0000 0072 3900 0000 7208  ds..r8...r9...r.
+000012a0: 0000 0029 0272 4c00 0000 723a 0000 0072  ...).rL...r:...r
+000012b0: 0900 0000 7209 0000 0072 0a00 0000 da12  ....r....r......
+000012c0: 7661 6c69 6461 7465 5f69 6473 5f66 6965  validate_ids_fie
+000012d0: 6c64 6c00 0000 7306 0000 0000 0204 010c  ldl...s.........
+000012e0: 017a 2550 6172 616d 6574 6572 5661 6c69  .z%ParameterVali
+000012f0: 6461 746f 722e 7661 6c69 6461 7465 5f69  dator.validate_i
+00001300: 6473 5f66 6965 6c64 2901 da04 6c69 7665  ds_field)...live
+00001310: 6301 0000 0000 0000 0000 0000 0003 0000  c...............
+00001320: 0005 0000 0043 0000 0073 3c00 0000 6401  .....C...s<...d.
+00001330: 7d01 6402 7d02 7400 7401 a002 7c01 7c00  }.d.}.t.t...|.|.
+00001340: a102 8301 0100 7401 a002 7c01 7c00 a102  ......t...|.|...
+00001350: 7338 7401 a002 7c02 7c00 a102 7338 7403  s8t...|.|...s8t.
+00001360: 6403 8301 8201 6400 5300 2904 4e7a 0461  d.....d.S.).Nz.a
+00001370: 6c6c 2472 4d00 0000 7a23 6c69 7665 2068  ll$rM...z#live h
+00001380: 6173 2076 616c 7565 7320 2761 6c6c 2720  as values 'all' 
+00001390: 6f72 2027 6964 2d69 642d 6964 2729 04da  or 'id-id-id')..
+000013a0: 0570 7269 6e74 7238 0000 0072 3900 0000  .printr8...r9...
+000013b0: 7208 0000 0029 0372 5000 0000 5a08 7061  r....).rP...Z.pa
+000013c0: 7474 6572 6e31 5a08 7061 7474 6572 6e32  ttern1Z.pattern2
+000013d0: 7209 0000 0072 0900 0000 720a 0000 00da  r....r....r.....
+000013e0: 1376 616c 6964 6174 655f 6c69 7665 5f66  .validate_live_f
+000013f0: 6965 6c64 7200 0000 730a 0000 0000 0204  ieldr...s.......
+00001400: 0104 0110 0118 017a 2650 6172 616d 6574  .......z&Paramet
+00001410: 6572 5661 6c69 6461 746f 722e 7661 6c69  erValidator.vali
+00001420: 6461 7465 5f6c 6976 655f 6669 656c 64a9  date_live_field.
+00001430: 01da 056e 6578 745f 6301 0000 0000 0000  ...next_c.......
+00001440: 0000 0000 0001 0000 0003 0000 0043 0000  .............C..
+00001450: 0073 1c00 0000 7400 7401 7c00 8301 8301  .s....t.t.|.....
+00001460: 6401 6b01 7218 7402 6402 8301 8201 6400  d.k.r.t.d.....d.
+00001470: 5300 2903 4e72 4500 0000 7a34 5468 6520  S.).NrE...z4The 
+00001480: 6e65 7874 2066 6965 6c64 2063 616e 6e6f  next field canno
+00001490: 7420 6578 6365 6564 2032 2063 6861 7261  t exceed 2 chara
+000014a0: 6374 6572 7320 696e 206c 656e 6774 682e  cters in length.
+000014b0: 7246 0000 0072 5300 0000 7209 0000 0072  rF...rS...r....r
+000014c0: 0900 0000 720a 0000 00da 1376 616c 6964  ....r......valid
+000014d0: 6174 655f 6e65 7874 5f66 6965 6c64 7a00  ate_next_fieldz.
+000014e0: 0000 7306 0000 0000 0210 0108 017a 2650  ..s..........z&P
+000014f0: 6172 616d 6574 6572 5661 6c69 6461 746f  arameterValidato
+00001500: 722e 7661 6c69 6461 7465 5f6e 6578 745f  r.validate_next_
+00001510: 6669 656c 6429 01da 0673 7461 7475 7363  field)...statusc
+00001520: 0100 0000 0000 0000 0000 0000 0300 0000  ................
+00001530: 0600 0000 4300 0000 7338 0000 0067 0064  ....C...s8...g.d
+00001540: 01a2 017d 0164 02a0 0064 03a0 017c 01a1  ...}.d...d...|..
+00001550: 0164 03a0 017c 01a1 01a1 027d 0274 02a0  .d...|.....}.t..
+00001560: 037c 027c 00a1 0273 3474 0464 0483 0182  .|.|...s4t.d....
+00001570: 0164 0053 0029 054e 2913 5a03 5442 445a  .d.S.).N).Z.TBDZ
+00001580: 024e 535a 0231 485a 0248 545a 0232 48da  .NSZ.1HZ.HTZ.2H.
+00001590: 0245 545a 0242 54da 0150 5a04 5355 5350  .ETZ.BT..PZ.SUSP
+000015a0: da03 494e 545a 0246 545a 0341 4554 5a03  ..INTZ.FTZ.AETZ.
+000015b0: 5045 4eda 0350 5354 5a04 4341 4e43 5a03  PEN..PSTZ.CANCZ.
+000015c0: 4142 445a 0341 5744 5a02 574f 5a04 4c49  ABDZ.AWDZ.WOZ.LI
+000015d0: 5645 7a10 5e28 7b7d 2928 3f3a 2d28 7b7d  VEz.^({})(?:-({}
+000015e0: 2929 2a24 da01 7c7a 2149 6e63 6f72 7265  ))*$..|z!Incorre
+000015f0: 6374 2073 7461 7475 7320 7661 6c75 6520  ct status value 
+00001600: 7072 6f76 6964 6564 2e20 2905 da06 666f  provided. )...fo
+00001610: 726d 6174 7228 0000 0072 3800 0000 7239  rmatr(...r8...r9
+00001620: 0000 0072 0800 0000 2903 7256 0000 005a  ...r....).rV...Z
+00001630: 1661 6c6c 6f77 6564 5f66 6978 7475 7265  .allowed_fixture
+00001640: 5f73 7461 7475 7372 3a00 0000 7209 0000  _statusr:...r...
+00001650: 0072 0900 0000 720a 0000 00da 1576 616c  .r....r......val
+00001660: 6964 6174 655f 7374 6174 7573 5f66 6965  idate_status_fie
+00001670: 6c64 8000 0000 730a 0000 0000 0208 1618  ld....s.........
+00001680: 020c 0108 017a 2850 6172 616d 6574 6572  .....z(Parameter
+00001690: 5661 6c69 6461 746f 722e 7661 6c69 6461  Validator.valida
+000016a0: 7465 5f73 7461 7475 735f 6669 656c 6429  te_status_field)
+000016b0: 01da 0368 3268 6301 0000 0000 0000 0000  ...h2hc.........
+000016c0: 0000 0002 0000 0004 0000 0043 0000 0073  ...........C...s
+000016d0: 1c00 0000 6401 7d01 7400 a001 7c01 7c00  ....d.}.t...|.|.
+000016e0: a102 7318 7402 6402 8301 8201 6400 5300  ..s.t.d.....d.S.
+000016f0: 2903 4e7a 0e5e 5c64 7b31 2c7d 2d5c 647b  ).Nz.^\d{1,}-\d{
+00001700: 312c 7d7a 1449 6e63 6f72 7265 6374 2068  1,}z.Incorrect h
+00001710: 3268 2076 616c 7565 2e72 4e00 0000 2902  2h value.rN...).
+00001720: 725e 0000 0072 3a00 0000 7209 0000 0072  r^...r:...r....r
+00001730: 0900 0000 720a 0000 00da 1276 616c 6964  ....r......valid
+00001740: 6174 655f 6832 685f 6669 656c 649e 0000  ate_h2h_field...
+00001750: 0073 0800 0000 0002 0402 0c01 0801 7a25  .s............z%
+00001760: 5061 7261 6d65 7465 7256 616c 6964 6174  ParameterValidat
+00001770: 6f72 2e76 616c 6964 6174 655f 6832 685f  or.validate_h2h_
+00001780: 6669 656c 6463 0100 0000 0000 0000 0000  fieldc..........
+00001790: 0000 0200 0000 0200 0000 4300 0000 7320  ..........C...s 
+000017a0: 0000 0068 0064 01a3 017d 017c 00a0 00a1  ...h.d...}.|....
+000017b0: 007c 0176 0172 1c74 0164 0283 0182 0164  .|.v.r.t.d.....d
+000017c0: 0053 0029 034e 3e03 0000 00da 0573 7562  .S.).N>......sub
+000017d0: 7374 5a04 6361 7264 5a04 676f 616c 7a31  stZ.cardZ.goalz1
+000017e0: 5468 6520 5479 7065 2066 6965 6c64 206d  The Type field m
+000017f0: 7573 7420 6265 206f 6e65 206f 663a 2067  ust be one of: g
+00001800: 6f61 6c2c 2063 6172 642c 2073 7562 7374  oal, card, subst
+00001810: 2ea9 0272 0700 0000 7208 0000 00a9 0272  ...r....r......r
+00001820: 2900 0000 5a0d 5f61 6c6c 6f77 6564 5f76  )...Z._allowed_v
+00001830: 616c 7372 0900 0000 7209 0000 0072 0a00  alsr....r....r..
+00001840: 0000 da22 7661 6c69 6461 7465 5f66 6978  ..."validate_fix
+00001850: 7475 7265 5f65 7665 6e74 735f 7479 7065  ture_events_type
+00001860: 5f66 6965 6c64 a600 0000 7306 0000 0000  _field....s.....
+00001870: 0208 020c 017a 3550 6172 616d 6574 6572  .....z5Parameter
+00001880: 5661 6c69 6461 746f 722e 7661 6c69 6461  Validator.valida
+00001890: 7465 5f66 6978 7475 7265 5f65 7665 6e74  te_fixture_event
+000018a0: 735f 7479 7065 5f66 6965 6c64 6301 0000  s_type_fieldc...
+000018b0: 0000 0000 0000 0000 0002 0000 0003 0000  ................
+000018c0: 0043 0000 0073 2600 0000 6800 6401 a301  .C...s&...h.d...
+000018d0: 7d01 7c00 a000 a100 7c01 7601 7222 7401  }.|.....|.v.r"t.
+000018e0: 6402 7c01 9b00 9d02 8301 8201 6400 5300  d.|.........d.S.
+000018f0: 2903 4e3e 1000 0000 7a0f 6261 6c6c 2070  ).N>....z.ball p
+00001900: 6f73 7365 7373 696f 6e7a 0c74 6f74 616c  ossessionz.total
+00001910: 2070 6173 7365 737a 1067 6f61 6c6b 6565   passesz.goalkee
+00001920: 7065 7220 7361 7665 735a 0566 6f75 6c73  per savesZ.fouls
+00001930: 7a0d 7368 6f74 7320 6f6e 2067 6f61 6c7a  z.shots on goalz
+00001940: 0b74 6f74 616c 2073 686f 7473 7a10 7368  .total shotsz.sh
+00001950: 6f74 7320 6f75 7473 6964 6562 6f78 7a0f  ots outsideboxz.
+00001960: 7368 6f74 7320 696e 7369 6465 626f 787a  shots insideboxz
+00001970: 0d62 6c6f 636b 6564 2073 686f 7473 5a08  .blocked shotsZ.
+00001980: 6f66 6673 6964 6573 7a08 7061 7373 6573  offsidesz.passes
+00001990: 2025 7a0c 636f 726e 6572 206b 6963 6b73   %z.corner kicks
+000019a0: 7a0e 7368 6f74 7320 6f66 6620 676f 616c  z.shots off goal
+000019b0: 7a0c 7965 6c6c 6f77 2063 6172 6473 7a09  z.yellow cardsz.
+000019c0: 7265 6420 6361 7264 737a 0f70 6173 7365  red cardsz.passe
+000019d0: 7320 6163 6375 7261 7465 7a20 2054 6865  s accuratez  The
+000019e0: 2054 7970 6520 6669 656c 6420 6d75 7374   Type field must
+000019f0: 2062 6520 6f6e 6520 6f66 3a20 7261 0000   be one of: ra..
+00001a00: 0072 6200 0000 7209 0000 0072 0900 0000  .rb...r....r....
+00001a10: 720a 0000 00da 2676 616c 6964 6174 655f  r.....&validate_
+00001a20: 6669 7874 7572 655f 7374 6174 6973 7469  fixture_statisti
+00001a30: 6373 5f74 7970 655f 6669 656c 64ad 0000  cs_type_field...
+00001a40: 0073 0600 0000 0002 0812 0c01 7a39 5061  .s..........z9Pa
+00001a50: 7261 6d65 7465 7256 616c 6964 6174 6f72  rameterValidator
+00001a60: 2e76 616c 6964 6174 655f 6669 7874 7572  .validate_fixtur
+00001a70: 655f 7374 6174 6973 7469 6373 5f74 7970  e_statistics_typ
+00001a80: 655f 6669 656c 6463 0100 0000 0000 0000  e_fieldc........
+00001a90: 0000 0000 0200 0000 0200 0000 4300 0000  ............C...
+00001aa0: 7320 0000 0068 0064 01a3 017d 017c 00a0  s ...h.d...}.|..
+00001ab0: 00a1 007c 0176 0172 1c74 0164 0283 0182  ...|.v.r.t.d....
+00001ac0: 0164 0053 0029 034e 3e04 0000 005a 0966  .d.S.).N>....Z.f
+00001ad0: 6f72 6d61 7469 6f6e 5a07 7374 6172 7478  ormationZ.startx
+00001ae0: 695a 0b73 7562 7374 6974 7574 6573 da05  iZ.substitutes..
+00001af0: 636f 6163 687a 4654 6865 2054 7970 6520  coachzFThe Type 
+00001b00: 6669 656c 6420 6d75 7374 2062 6520 6f6e  field must be on
+00001b10: 6520 6f66 3a20 636f 6163 682c 2066 6f72  e of: coach, for
+00001b20: 6d61 7469 6f6e 2c20 7374 6172 7478 692c  mation, startxi,
+00001b30: 2073 7562 7374 6974 7574 6573 2e72 6100   substitutes.ra.
+00001b40: 0000 7262 0000 0072 0900 0000 7209 0000  ..rb...r....r...
+00001b50: 0072 0a00 0000 da23 7661 6c69 6461 7465  .r.....#validate
+00001b60: 5f66 6978 7475 7265 5f6c 696e 6575 7073  _fixture_lineups
+00001b70: 5f74 7970 655f 6669 656c 64c4 0000 0073  _type_field....s
+00001b80: 0600 0000 0002 0802 0c01 7a36 5061 7261  ..........z6Para
+00001b90: 6d65 7465 7256 616c 6964 6174 6f72 2e76  meterValidator.v
+00001ba0: 616c 6964 6174 655f 6669 7874 7572 655f  alidate_fixture_
+00001bb0: 6c69 6e65 7570 735f 7479 7065 5f66 6965  lineups_type_fie
+00001bc0: 6c64 4e29 1cda 085f 5f6e 616d 655f 5fda  ldN)...__name__.
+00001bd0: 0a5f 5f6d 6f64 756c 655f 5fda 0c5f 5f71  .__module__..__q
+00001be0: 7561 6c6e 616d 655f 5fda 0c73 7461 7469  ualname__..stati
+00001bf0: 636d 6574 686f 6472 1800 0000 720b 0000  cmethodr....r...
+00001c00: 0072 1300 0000 721a 0000 0072 1b00 0000  .r....r....r....
+00001c10: 721c 0000 0072 2a00 0000 722f 0000 0072  r....r*...r/...r
+00001c20: 3100 0000 7237 0000 0072 3b00 0000 723f  1...r7...r;...r?
+00001c30: 0000 0072 4200 0000 7247 0000 0072 4800  ...rB...rG...rH.
+00001c40: 0000 724b 0000 0072 4f00 0000 7252 0000  ..rK...rO...rR..
+00001c50: 0072 5500 0000 725d 0000 0072 5f00 0000  .rU...r]...r_...
+00001c60: 7263 0000 0072 6400 0000 7266 0000 0072  rc...rd...rf...r
+00001c70: 0900 0000 7209 0000 0072 0900 0000 720a  ....r....r....r.
+00001c80: 0000 0072 0500 0000 0900 0000 7358 0000  ...r........sX..
+00001c90: 0008 0202 0110 0602 010a 0502 0112 0402  ................
+00001ca0: 0112 0402 010a 1102 0110 0402 010a 0402  ................
+00001cb0: 0110 0402 0110 0602 0110 0702 0110 0602  ................
+00001cc0: 0110 0502 010a 0502 010a 0602 0110 0502  ................
+00001cd0: 0110 0702 0110 0502 0110 1d02 0110 0702  ................
+00001ce0: 0110 0602 0110 1602 0172 0500 0000 2907  .........r....).
+00001cf0: 7238 0000 0072 0200 0000 7234 0000 00da  r8...r....r4....
+00001d00: 1c66 6f6f 7462 616c 6c41 5049 436c 6965  .footballAPIClie
+00001d10: 6e74 2e5f 636f 6e73 7461 6e74 7372 0300  nt._constantsr..
+00001d20: 0000 7204 0000 0072 0500 0000 7209 0000  ..r....r....r...
+00001d30: 0072 0900 0000 7209 0000 0072 0a00 0000  .r....r....r....
+00001d40: da08 3c6d 6f64 756c 653e 0100 0000 730a  ..<module>....s.
+00001d50: 0000 0008 010c 0108 020c 010c 03         .............
```

### Comparing `footballapiclient-0.0.2/footballAPIClient/helpers/ParameterValidator.py` & `footballapiclient-0.0.3/footballAPIClient/helpers/ParameterValidator.py`

 * *Files identical despite different names*

### Comparing `footballapiclient-0.0.2/LICENSE` & `footballapiclient-0.0.3/LICENSE`

 * *Files identical despite different names*

### Comparing `footballapiclient-0.0.2/pyproject.toml` & `footballapiclient-0.0.3/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["poetry-core>=1.0.0"]
 build-backend = "poetry.core.masonry.api"
 
 [tool.poetry]
 name = "footballAPIClient"
-version = "0.0.2"
+version = "0.0.3"
 description = "Python Binding (API wrapper) for the Football API."
 authors = ["Rishav Ganguly <rishav.ganguly07@gmail.com>"]
 readme = "README.md"
 classifiers = [
     "Development Status :: 4 - Beta",
     "Programming Language :: Python :: 3",
     "License :: OSI Approved :: MIT License",
```

### Comparing `footballapiclient-0.0.2/README.md` & `footballapiclient-0.0.3/README.md`

 * *Files identical despite different names*

### Comparing `footballapiclient-0.0.2/PKG-INFO` & `footballapiclient-0.0.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: footballapiclient
-Version: 0.0.2
+Version: 0.0.3
 Summary: Python Binding (API wrapper) for the Football API.
 Author: Rishav Ganguly
 Author-email: rishav.ganguly07@gmail.com
 Requires-Python: >=3.7,<4.0
 Classifier: Development Status :: 4 - Beta
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```


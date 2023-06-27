# Comparing `tmp/ss13_tools-2.3.0.tar.gz` & `tmp/ss13_tools-2.3.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ss13_tools-2.3.0.tar", max compression
+gzip compressed data, was "ss13_tools-2.3.1.tar", max compression
```

## Comparing `ss13_tools-2.3.0.tar` & `ss13_tools-2.3.1.tar`

### file list

```diff
@@ -1,51 +1,51 @@
--rw-r--r--   0        0        0     2301 2023-06-12 01:20:17.412910 ss13_tools-2.3.0/README.md
--rw-r--r--   0        0        0     1008 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/pyproject.toml
--rw-r--r--   0        0        0      325 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/__init__.py
--rw-r--r--   0        0        0     1175 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/__main__.py
--rw-r--r--   0        0        0       22 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/__version__.py
--rw-r--r--   0        0        0      438 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/auth/__init__.py
--rw-r--r--   0        0        0      205 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/auth/__main__.py
--rw-r--r--   0        0        0      346 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/auth/constants.py
--rw-r--r--   0        0        0    10698 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/auth/tg.py
--rw-r--r--   0        0        0      182 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/byond/__init__.py
--rw-r--r--   0        0        0      543 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/byond/__main__.py
--rw-r--r--   0        0        0       59 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/byond/constants.py
--rw-r--r--   0        0        0     2424 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/byond/key_tools.py
--rw-r--r--   0        0        0      162 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/centcom/__init__.py
--rw-r--r--   0        0        0     1099 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/centcom/__main__.py
--rw-r--r--   0        0        0      394 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/centcom/ban.py
--rw-r--r--   0        0        0     1492 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/centcom/ban_types.py
--rw-r--r--   0        0        0       68 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/centcom/constants.py
--rw-r--r--   0        0        0      614 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/cli.py
--rw-r--r--   0        0        0      222 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/constants.py
--rw-r--r--   0        0        0    18265 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/log_buddy/README.md
--rw-r--r--   0        0        0      198 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/log_buddy/__init__.py
--rw-r--r--   0        0        0     5561 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/log_buddy/__main__.py
--rw-r--r--   0        0        0      768 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/log_buddy/constants.py
--rw-r--r--   0        0        0      562 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/log_buddy/expressions.py
--rw-r--r--   0        0        0    52497 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/log_buddy/log.py
--rw-r--r--   0        0        0    17063 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/log_buddy/log_magics.py
--rw-r--r--   0        0        0    28437 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/log_buddy/log_parser.py
--rw-r--r--   0        0        0      554 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/log_downloader/__init__.py
--rw-r--r--   0        0        0     2011 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/log_downloader/__main__.py
--rw-r--r--   0        0        0     7393 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/log_downloader/base.py
--rw-r--r--   0        0        0     4566 2023-06-12 01:20:17.420911 ss13_tools-2.3.0/ss13_tools/log_downloader/ckey.py
--rw-r--r--   0        0        0      517 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/log_downloader/constants.py
--rw-r--r--   0        0        0     4492 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/log_downloader/round.py
--rw-r--r--   0        0        0    10429 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/menu.py
--rw-r--r--   0        0        0     1247 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/menu_item.py
--rw-r--r--   0        0        0     1880 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/scrubby/CKeyController.py
--rw-r--r--   0        0        0     2341 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/scrubby/RoundController.py
--rw-r--r--   0        0        0      622 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/scrubby/__init__.py
--rw-r--r--   0        0        0      107 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/scrubby/__main__.py
--rw-r--r--   0        0        0      433 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/scrubby/constants.py
--rw-r--r--   0        0        0        0 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/scrubby/investigate.py
--rw-r--r--   0        0        0     1201 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/scrubby/round_data.py
--rw-r--r--   0        0        0      154 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/slur_detector/__init__.py
--rw-r--r--   0        0        0      320 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/slur_detector/__main__.py
--rw-r--r--   0        0        0       21 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/slur_detector/constants.py
--rw-r--r--   0        0        0     2740 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/slur_detector/slur_detector.py
--rw-r--r--   0        0        0      987 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/slur_detector/slur_file.py
--rw-r--r--   0        0        0      201 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/slur_detector/word_detection.py
--rw-r--r--   0        0        0      327 2023-06-12 01:20:17.424911 ss13_tools-2.3.0/ss13_tools/util.py
--rw-r--r--   0        0        0     3172 1970-01-01 00:00:00.000000 ss13_tools-2.3.0/PKG-INFO
+-rw-r--r--   0        0        0     2301 2023-06-27 21:59:05.069392 ss13_tools-2.3.1/README.md
+-rw-r--r--   0        0        0     1008 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/pyproject.toml
+-rw-r--r--   0        0        0      325 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/__init__.py
+-rw-r--r--   0        0        0     1175 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/__main__.py
+-rw-r--r--   0        0        0       22 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/__version__.py
+-rw-r--r--   0        0        0      438 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/auth/__init__.py
+-rw-r--r--   0        0        0      205 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/auth/__main__.py
+-rw-r--r--   0        0        0      346 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/auth/constants.py
+-rw-r--r--   0        0        0    10698 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/auth/tg.py
+-rw-r--r--   0        0        0      182 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/byond/__init__.py
+-rw-r--r--   0        0        0      543 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/byond/__main__.py
+-rw-r--r--   0        0        0       59 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/byond/constants.py
+-rw-r--r--   0        0        0     2424 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/byond/key_tools.py
+-rw-r--r--   0        0        0      162 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/centcom/__init__.py
+-rw-r--r--   0        0        0     1099 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/centcom/__main__.py
+-rw-r--r--   0        0        0      394 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/centcom/ban.py
+-rw-r--r--   0        0        0     1492 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/centcom/ban_types.py
+-rw-r--r--   0        0        0       68 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/centcom/constants.py
+-rw-r--r--   0        0        0      614 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/cli.py
+-rw-r--r--   0        0        0      222 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/constants.py
+-rw-r--r--   0        0        0    18265 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/log_buddy/README.md
+-rw-r--r--   0        0        0      198 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/log_buddy/__init__.py
+-rw-r--r--   0        0        0     5561 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/log_buddy/__main__.py
+-rw-r--r--   0        0        0      768 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/log_buddy/constants.py
+-rw-r--r--   0        0        0      562 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/log_buddy/expressions.py
+-rw-r--r--   0        0        0    52497 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/log_buddy/log.py
+-rw-r--r--   0        0        0    17063 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/log_buddy/log_magics.py
+-rw-r--r--   0        0        0    28437 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/log_buddy/log_parser.py
+-rw-r--r--   0        0        0      554 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/log_downloader/__init__.py
+-rw-r--r--   0        0        0     2011 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/log_downloader/__main__.py
+-rw-r--r--   0        0        0     7393 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/log_downloader/base.py
+-rw-r--r--   0        0        0     4738 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/log_downloader/ckey.py
+-rw-r--r--   0        0        0      517 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/log_downloader/constants.py
+-rw-r--r--   0        0        0     4492 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/log_downloader/round.py
+-rw-r--r--   0        0        0    10429 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/menu.py
+-rw-r--r--   0        0        0     1247 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/menu_item.py
+-rw-r--r--   0        0        0     1880 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/scrubby/CKeyController.py
+-rw-r--r--   0        0        0     2341 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/scrubby/RoundController.py
+-rw-r--r--   0        0        0      622 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/scrubby/__init__.py
+-rw-r--r--   0        0        0      107 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/scrubby/__main__.py
+-rw-r--r--   0        0        0      433 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/scrubby/constants.py
+-rw-r--r--   0        0        0        0 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/scrubby/investigate.py
+-rw-r--r--   0        0        0     1201 2023-06-27 21:59:05.077392 ss13_tools-2.3.1/ss13_tools/scrubby/round_data.py
+-rw-r--r--   0        0        0      154 2023-06-27 21:59:05.081392 ss13_tools-2.3.1/ss13_tools/slur_detector/__init__.py
+-rw-r--r--   0        0        0      320 2023-06-27 21:59:05.081392 ss13_tools-2.3.1/ss13_tools/slur_detector/__main__.py
+-rw-r--r--   0        0        0       21 2023-06-27 21:59:05.081392 ss13_tools-2.3.1/ss13_tools/slur_detector/constants.py
+-rw-r--r--   0        0        0     2740 2023-06-27 21:59:05.081392 ss13_tools-2.3.1/ss13_tools/slur_detector/slur_detector.py
+-rw-r--r--   0        0        0      987 2023-06-27 21:59:05.081392 ss13_tools-2.3.1/ss13_tools/slur_detector/slur_file.py
+-rw-r--r--   0        0        0      201 2023-06-27 21:59:05.081392 ss13_tools-2.3.1/ss13_tools/slur_detector/word_detection.py
+-rw-r--r--   0        0        0      327 2023-06-27 21:59:05.081392 ss13_tools-2.3.1/ss13_tools/util.py
+-rw-r--r--   0        0        0     3172 1970-01-01 00:00:00.000000 ss13_tools-2.3.1/PKG-INFO
```

### Comparing `ss13_tools-2.3.0/README.md` & `ss13_tools-2.3.1/README.md`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/pyproject.toml` & `ss13_tools-2.3.1/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "SS13-tools"
-version = "2.3.0"
+version = "2.3.1"
 description = "Python toolchain for SS13"
 authors = ["RigglePrime <27156122+RigglePrime@users.noreply.github.com>", "tattle <66640614+dragomagol@users.noreply.github.com>"]
 readme = "README.md"
 repository = "https://github.com/RigglePrime/SS13-tools"
 keywords = ["ss13", "tgstation"]
 
 [tool.poetry.dependencies]
```

### Comparing `ss13_tools-2.3.0/ss13_tools/__main__.py` & `ss13_tools-2.3.1/ss13_tools/__main__.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/auth/tg.py` & `ss13_tools-2.3.1/ss13_tools/auth/tg.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/byond/__main__.py` & `ss13_tools-2.3.1/ss13_tools/byond/__main__.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/byond/key_tools.py` & `ss13_tools-2.3.1/ss13_tools/byond/key_tools.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/centcom/__main__.py` & `ss13_tools-2.3.1/ss13_tools/centcom/__main__.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/centcom/ban_types.py` & `ss13_tools-2.3.1/ss13_tools/centcom/ban_types.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/cli.py` & `ss13_tools-2.3.1/ss13_tools/cli.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/log_buddy/README.md` & `ss13_tools-2.3.1/ss13_tools/log_buddy/README.md`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/log_buddy/__main__.py` & `ss13_tools-2.3.1/ss13_tools/log_buddy/__main__.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/log_buddy/constants.py` & `ss13_tools-2.3.1/ss13_tools/log_buddy/constants.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/log_buddy/expressions.py` & `ss13_tools-2.3.1/ss13_tools/log_buddy/expressions.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/log_buddy/log.py` & `ss13_tools-2.3.1/ss13_tools/log_buddy/log.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/log_buddy/log_magics.py` & `ss13_tools-2.3.1/ss13_tools/log_buddy/log_magics.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/log_buddy/log_parser.py` & `ss13_tools-2.3.1/ss13_tools/log_buddy/log_parser.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/log_downloader/__init__.py` & `ss13_tools-2.3.1/ss13_tools/log_downloader/__init__.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/log_downloader/__main__.py` & `ss13_tools-2.3.1/ss13_tools/log_downloader/__main__.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/log_downloader/base.py` & `ss13_tools-2.3.1/ss13_tools/log_downloader/base.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/log_downloader/ckey.py` & `ss13_tools-2.3.1/ss13_tools/log_downloader/ckey.py`

 * *Files 2% similar despite different names*

```diff
@@ -12,24 +12,26 @@
 
 class CkeyLogDownloaderException(Exception):
     """Uh oh, something went wrong"""
 
 
 class CkeyLogDownloader(LogDownloader):
     """Downloads logs in which a ckey was present"""
+    key: Annotated[Optional[str], "User's key, can be None"]
     ckey: Annotated[Optional[str], "Canonical form of user's key, can be None"]
     only_played: Annotated[bool, "If ckey is set dictates if the log downloader only counts player rounds"]\
         = DEFAULT_ONLY_PLAYED
     number_of_rounds: Annotated[int, "The number of rounds to download"] = DEFAULT_NUMBER_OF_ROUNDS
     output_path: Annotated[str, "Where should we write the file to?"] = DEFAULT_CKEY_OUTPUT_PATH.format(ckey="output")
     filter_logs: Annotated[bool, "Should we filter the logs?"] = True
 
     def __init__(self, key: str = None, only_played: bool = DEFAULT_ONLY_PLAYED,
                  number_of_rounds: int = DEFAULT_NUMBER_OF_ROUNDS, output_path: str = None) -> None:
-        self.ckey = canonicalize(key) if key else None
+        self.key = key
+        self.ckey = canonicalize(key) if self.key else None
         self.only_played = only_played
         self.number_of_rounds = number_of_rounds
         output_path = output_path or DEFAULT_CKEY_OUTPUT_PATH
         self.output_path = output_path.format(ckey=self.ckey or "output")
 
     async def _update_round_list(self) -> None:
         self.round_resources = []
@@ -50,17 +52,19 @@
 
     def _filter_lines(self, logs: Iterable[bytes]) -> Iterable[bytes]:
         if not self.filter_logs:
             for log in logs:
                 yield log
         if not self.ckey:
             raise CkeyLogDownloaderException("Ckey was empty")
+        key = self.key.lower().encode('utf-8')
         ckey = self.ckey.lower().encode('utf-8')
         for log in logs:
-            if ckey in log.lower():
+            log = log.lower()
+            if key in log or ckey in log:
                 yield log
 
     @staticmethod
     def interactive() -> LogDownloader:
         ckey = input("CKEY: ").strip()
         while True:
             number_of_rounds = input(f"How many rounds? [{DEFAULT_NUMBER_OF_ROUNDS}] ")
```

### Comparing `ss13_tools-2.3.0/ss13_tools/log_downloader/constants.py` & `ss13_tools-2.3.1/ss13_tools/log_downloader/constants.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/log_downloader/round.py` & `ss13_tools-2.3.1/ss13_tools/log_downloader/round.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/menu.py` & `ss13_tools-2.3.1/ss13_tools/menu.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/menu_item.py` & `ss13_tools-2.3.1/ss13_tools/menu_item.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/scrubby/CKeyController.py` & `ss13_tools-2.3.1/ss13_tools/scrubby/CKeyController.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/scrubby/RoundController.py` & `ss13_tools-2.3.1/ss13_tools/scrubby/RoundController.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/scrubby/__init__.py` & `ss13_tools-2.3.1/ss13_tools/scrubby/__init__.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/scrubby/round_data.py` & `ss13_tools-2.3.1/ss13_tools/scrubby/round_data.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/slur_detector/slur_detector.py` & `ss13_tools-2.3.1/ss13_tools/slur_detector/slur_detector.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/ss13_tools/slur_detector/slur_file.py` & `ss13_tools-2.3.1/ss13_tools/slur_detector/slur_file.py`

 * *Files identical despite different names*

### Comparing `ss13_tools-2.3.0/PKG-INFO` & `ss13_tools-2.3.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ss13-tools
-Version: 2.3.0
+Version: 2.3.1
 Summary: Python toolchain for SS13
 Home-page: https://github.com/RigglePrime/SS13-tools
 Keywords: ss13,tgstation
 Author: RigglePrime
 Author-email: 27156122+RigglePrime@users.noreply.github.com
 Requires-Python: >=3.9.1,<3.12
 Classifier: Programming Language :: Python :: 3
```


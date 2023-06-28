# Comparing `tmp/zavod-0.6.3.tar.gz` & `tmp/zavod-0.7.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "zavod-0.6.3.tar", last modified: Wed May 24 15:48:35 2023, max compression
+gzip compressed data, was "zavod-0.7.0.tar", last modified: Wed Jun 28 10:44:24 2023, max compression
```

## Comparing `zavod-0.6.3.tar` & `zavod-0.7.0.tar`

### file list

```diff
@@ -1,37 +1,38 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-24 15:48:35.758710 zavod-0.6.3/
--rw-r--r--   0 runner    (1001) docker     (123)     1065 2023-05-24 15:46:22.000000 zavod-0.6.3/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       68 2023-05-24 15:46:22.000000 zavod-0.6.3/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)      542 2023-05-24 15:48:35.758710 zavod-0.6.3/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      169 2023-05-24 15:46:22.000000 zavod-0.6.3/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-24 15:48:35.758710 zavod-0.6.3/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1457 2023-05-24 15:46:22.000000 zavod-0.6.3/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-24 15:48:35.758710 zavod-0.6.3/zavod/
--rw-r--r--   0 runner    (1001) docker     (123)     1975 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      941 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/audit.py
--rw-r--r--   0 runner    (1001) docker     (123)      213 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/cli.py
--rw-r--r--   0 runner    (1001) docker     (123)     3123 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/context.py
--rw-r--r--   0 runner    (1001) docker     (123)      551 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/dataset.py
--rw-r--r--   0 runner    (1001) docker     (123)     1329 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/http.py
--rw-r--r--   0 runner    (1001) docker     (123)     2394 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/logs.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-24 15:48:35.758710 zavod-0.6.3/zavod/parse/
--rw-r--r--   0 runner    (1001) docker     (123)      237 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/parse/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3092 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/parse/addresses.py
--rw-r--r--   0 runner    (1001) docker     (123)     3962 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/parse/names.py
--rw-r--r--   0 runner    (1001) docker     (123)      785 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/parse/xml.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)      448 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/settings.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-24 15:48:35.758710 zavod-0.6.3/zavod/sinks/
--rw-r--r--   0 runner    (1001) docker     (123)      203 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/sinks/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1130 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/sinks/common.py
--rw-r--r--   0 runner    (1001) docker     (123)      367 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/sinks/json_entity.py
--rw-r--r--   0 runner    (1001) docker     (123)      439 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/sinks/json_statement.py
--rw-r--r--   0 runner    (1001) docker     (123)      572 2023-05-24 15:46:22.000000 zavod-0.6.3/zavod/util.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-24 15:48:35.758710 zavod-0.6.3/zavod.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      542 2023-05-24 15:48:35.000000 zavod-0.6.3/zavod.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      627 2023-05-24 15:48:35.000000 zavod-0.6.3/zavod.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-24 15:48:35.000000 zavod-0.6.3/zavod.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       40 2023-05-24 15:48:35.000000 zavod-0.6.3/zavod.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-24 15:48:35.000000 zavod-0.6.3/zavod.egg-info/namespace_packages.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-24 15:48:16.000000 zavod-0.6.3/zavod.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)      270 2023-05-24 15:48:35.000000 zavod-0.6.3/zavod.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       12 2023-05-24 15:48:35.000000 zavod-0.6.3/zavod.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:44:23.995987 zavod-0.7.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1065 2023-06-28 10:42:35.000000 zavod-0.7.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-28 10:42:35.000000 zavod-0.7.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)      561 2023-06-28 10:44:23.995987 zavod-0.7.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      169 2023-06-28 10:42:35.000000 zavod-0.7.0/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 10:44:23.995987 zavod-0.7.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1457 2023-06-28 10:42:35.000000 zavod-0.7.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:44:23.995987 zavod-0.7.0/zavod/
+-rw-r--r--   0 runner    (1001) docker     (123)     2018 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      941 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/audit.py
+-rw-r--r--   0 runner    (1001) docker     (123)      213 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3123 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/context.py
+-rw-r--r--   0 runner    (1001) docker     (123)      551 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1329 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/http.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2394 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/logs.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:44:23.995987 zavod-0.7.0/zavod/parse/
+-rw-r--r--   0 runner    (1001) docker     (123)      276 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/parse/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3300 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/parse/addresses.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3962 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/parse/names.py
+-rw-r--r--   0 runner    (1001) docker     (123)      785 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/parse/xml.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)      448 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/settings.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:44:23.995987 zavod-0.7.0/zavod/sinks/
+-rw-r--r--   0 runner    (1001) docker     (123)      300 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/sinks/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1050 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/sinks/common.py
+-rw-r--r--   0 runner    (1001) docker     (123)      367 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/sinks/json_entity.py
+-rw-r--r--   0 runner    (1001) docker     (123)      439 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/sinks/json_statement.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1528 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/sinks/pack_statement.py
+-rw-r--r--   0 runner    (1001) docker     (123)      572 2023-06-28 10:42:35.000000 zavod-0.7.0/zavod/util.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:44:23.995987 zavod-0.7.0/zavod.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      561 2023-06-28 10:44:23.000000 zavod-0.7.0/zavod.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      657 2023-06-28 10:44:23.000000 zavod-0.7.0/zavod.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:44:23.000000 zavod-0.7.0/zavod.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-28 10:44:23.000000 zavod-0.7.0/zavod.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:44:23.000000 zavod-0.7.0/zavod.egg-info/namespace_packages.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:44:08.000000 zavod-0.7.0/zavod.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      270 2023-06-28 10:44:23.000000 zavod-0.7.0/zavod.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-28 10:44:23.000000 zavod-0.7.0/zavod.egg-info/top_level.txt
```

### Comparing `zavod-0.6.3/LICENSE` & `zavod-0.7.0/LICENSE`

 * *Files identical despite different names*

### Comparing `zavod-0.6.3/PKG-INFO` & `zavod-0.7.0/PKG-INFO`

 * *Files 21% similar despite different names*

```diff
@@ -1,16 +1,18 @@
 Metadata-Version: 2.1
 Name: zavod
-Version: 0.6.3
+Version: 0.7.0
 Summary: Data factory for followthemoney data.
 Home-page: https://github.com/opensanctions/zavod
 Author: Friedrich Lindenberg
 Author-email: friedrich@opensanctions.org
 License: MIT
 Keywords: data mapping identity followthemoney etl parsing
+Platform: UNKNOWN
 Description-Content-Type: text/markdown
 Provides-Extra: dev
 License-File: LICENSE
 
 # zavod
 
 Zavod is the FollowTheMoney data factory. It contains a variety of useful functions for building small and reproducible data pipelines that generate FtM graphs.
+
```

### Comparing `zavod-0.6.3/setup.py` & `zavod-0.7.0/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 
 with open("README.md") as f:
     long_description = f.read()
 
 
 setup(
     name="zavod",
-    version="0.6.3",
+    version="0.7.0",
     description="Data factory for followthemoney data.",
     long_description=long_description,
     long_description_content_type="text/markdown",
     keywords="data mapping identity followthemoney etl parsing",
     author="Friedrich Lindenberg",
     author_email="friedrich@opensanctions.org",
     url="https://github.com/opensanctions/zavod",
@@ -18,15 +18,15 @@
     packages=find_packages(exclude=["ez_setup", "examples", "tests"]),
     namespace_packages=[],
     include_package_data=True,
     package_data={"": ["zavod/data/*", "zavod/py.typed"]},
     zip_safe=False,
     install_requires=[
         "followthemoney >= 3.2.0, < 4.0.0",
-        "nomenklatura >= 2.9.1, < 3.0.0",
+        "nomenklatura >= 3.0.1, < 4.0.0",
         "addressformatting >= 1.3.0, < 2.0.0",
         "datapatch >= 0.2.1",
         "click >= 8.0.0, < 8.2.0",
         "requests",
         "structlog",
         "lxml",
     ],
```

### Comparing `zavod-0.6.3/zavod/__init__.py` & `zavod-0.7.0/zavod/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,22 +1,22 @@
 import logging
 from pathlib import Path
-from typing import Generator, Optional
+from typing import Generator, Optional, Type
 from contextlib import contextmanager
 from nomenklatura.entity import CompositeEntity
 from followthemoney.util import PathLike
 
 from zavod import settings
 from zavod.context import GenericZavod
 from zavod.dataset import ZavodDataset, ZD
 from zavod.logs import configure_logging, get_logger
 from zavod.sinks.common import Sink
 from zavod.sinks.json_entity import JSONEntitySink
 
-__version__ = "0.6.3"
+__version__ = "0.7.0"
 __all__ = [
     "init",
     "context",
     "Zavod",
     "ZavodDataset",
     "ZD",
     "PathLike",
@@ -34,22 +34,23 @@
 
 def init(
     metadata_path: PathLike,
     verbose: bool = False,
     data_path: Path = settings.DATA_PATH,
     out_file: Optional[PathLike] = "fragments.json",
     sink: Optional[Sink[CompositeEntity]] = None,
+    sink_cls: Type[Sink[CompositeEntity]] = JSONEntitySink,
 ) -> Zavod:
     """Initiate the zavod working environment and create a processing context."""
     level = logging.DEBUG if verbose else logging.INFO
     configure_logging(level=level)
     if out_file is not None and sink is None:
         out_path = data_path.joinpath(out_file)
         out_path.parent.mkdir(exist_ok=True, parents=True)
-        sink = JSONEntitySink[CompositeEntity](out_path)
+        sink = sink_cls(out_path)
     dataset = ZavodDataset.from_path(metadata_path)
     return Zavod(dataset, CompositeEntity, data_path=data_path, sink=sink)
 
 
 @contextmanager
 def init_context(
     metadata_path: PathLike,
```

### Comparing `zavod-0.6.3/zavod/audit.py` & `zavod-0.7.0/zavod/audit.py`

 * *Files identical despite different names*

### Comparing `zavod-0.6.3/zavod/context.py` & `zavod-0.7.0/zavod/context.py`

 * *Files identical despite different names*

### Comparing `zavod-0.6.3/zavod/dataset.py` & `zavod-0.7.0/zavod/dataset.py`

 * *Files identical despite different names*

### Comparing `zavod-0.6.3/zavod/http.py` & `zavod-0.7.0/zavod/http.py`

 * *Files identical despite different names*

### Comparing `zavod-0.6.3/zavod/logs.py` & `zavod-0.7.0/zavod/logs.py`

 * *Files identical despite different names*

### Comparing `zavod-0.6.3/zavod/parse/addresses.py` & `zavod-0.7.0/zavod/parse/addresses.py`

 * *Files 6% similar despite different names*

```diff
@@ -11,31 +11,37 @@
 
 
 @cache
 def get_formatter() -> AddressFormatter:
     return AddressFormatter()
 
 
-@lru_cache(maxsize=200000)
-def format_line(
+@lru_cache(maxsize=5000)
+def format_address(
     summary: Optional[str] = None,
     po_box: Optional[str] = None,
     street: Optional[str] = None,
+    house: Optional[str] = None,
+    house_number: Optional[str] = None,
     postal_code: Optional[str] = None,
     city: Optional[str] = None,
+    county: Optional[str] = None,
     state: Optional[str] = None,
     country_code: Optional[str] = None,
 ) -> str:
     data = {
         "attention": summary,
         "house": po_box,
         "road": street,
+        "house": house,
+        "house_number": house_number,
         "postcode": postal_code,
         "city": city,
-        "state": state,
+        "county": county,
+        "state_district": state,
     }
     return get_formatter().one_line(data, country=country_code)
 
 
 def make_address(
     context: GenericZavod[CE, ZD],
     full: Optional[str] = None,
@@ -71,15 +77,15 @@
     address.add("region", region, lang=lang)
     address.add("state", state, quiet=True, lang=lang)
     address.add("country", country, lang=lang)
     address.add("country", country_code)
 
     country_code = address.first("country")
     if not full:
-        full = format_line(
+        full = format_address(
             summary=summary,
             po_box=po_box,
             street=street,
             postal_code=postal_code,
             city=city,
             state=join_text(region, state, sep=", "),
             country_code=country_code,
```

### Comparing `zavod-0.6.3/zavod/parse/names.py` & `zavod-0.7.0/zavod/parse/names.py`

 * *Files identical despite different names*

### Comparing `zavod-0.6.3/zavod/parse/xml.py` & `zavod-0.7.0/zavod/parse/xml.py`

 * *Files identical despite different names*

### Comparing `zavod-0.6.3/zavod/sinks/common.py` & `zavod-0.7.0/zavod/sinks/common.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,43 +1,42 @@
 import sys
-from threading import Lock
+from threading import RLock
 from typing import Generic, BinaryIO, Optional
 from followthemoney.util import PathLike
 
 from nomenklatura.entity import CE
 
 
 class Sink(Generic[CE]):
+    def __init__(self, path: PathLike) -> None:
+        self.path = path
+
     def emit(self, entity: CE) -> None:
         raise NotImplemented
 
     def close(self) -> None:
         pass
 
 
 class FileSink(Sink[CE]):
     def __init__(self, path: PathLike) -> None:
-        self.path = path
-        self.lock = Lock()
+        super().__init__(path)
+        self.lock = RLock()
         self.fh: Optional[BinaryIO] = None
 
     def emit_locked(self, fh: BinaryIO, entity: CE) -> None:
         raise NotImplemented
 
     def emit(self, entity: CE) -> None:
         with self.lock:
             if self.fh is None:
-                if str(self.path) == "-":
-                    self.fh = sys.stdout.buffer
-                else:
-                    self.fh = open(self.path, "wb")
+                self.fh = open(self.path, "wb")
             self.emit_locked(self.fh, entity)
 
     def close(self) -> None:
         with self.lock:
             if self.fh is not None:
-                if str(self.path) != "-":
-                    self.fh.close()
+                self.fh.close()
                 self.fh = None
 
     def __str__(self) -> str:
         return str(self.path)
```

### Comparing `zavod-0.6.3/zavod/util.py` & `zavod-0.7.0/zavod/util.py`

 * *Files identical despite different names*

### Comparing `zavod-0.6.3/zavod.egg-info/PKG-INFO` & `zavod-0.7.0/zavod.egg-info/PKG-INFO`

 * *Files 21% similar despite different names*

```diff
@@ -1,16 +1,18 @@
 Metadata-Version: 2.1
 Name: zavod
-Version: 0.6.3
+Version: 0.7.0
 Summary: Data factory for followthemoney data.
 Home-page: https://github.com/opensanctions/zavod
 Author: Friedrich Lindenberg
 Author-email: friedrich@opensanctions.org
 License: MIT
 Keywords: data mapping identity followthemoney etl parsing
+Platform: UNKNOWN
 Description-Content-Type: text/markdown
 Provides-Extra: dev
 License-File: LICENSE
 
 # zavod
 
 Zavod is the FollowTheMoney data factory. It contains a variety of useful functions for building small and reproducible data pipelines that generate FtM graphs.
+
```

### Comparing `zavod-0.6.3/zavod.egg-info/SOURCES.txt` & `zavod-0.7.0/zavod.egg-info/SOURCES.txt`

 * *Files 18% similar despite different names*

```diff
@@ -23,8 +23,9 @@
 zavod/parse/__init__.py
 zavod/parse/addresses.py
 zavod/parse/names.py
 zavod/parse/xml.py
 zavod/sinks/__init__.py
 zavod/sinks/common.py
 zavod/sinks/json_entity.py
-zavod/sinks/json_statement.py
+zavod/sinks/json_statement.py
+zavod/sinks/pack_statement.py
```


# Comparing `tmp/tagreader-4.1.4.tar.gz` & `tmp/tagreader-4.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tagreader-4.1.4.tar", max compression
+gzip compressed data, was "tagreader-4.2.0.tar", max compression
```

## Comparing `tagreader-4.1.4.tar` & `tagreader-4.2.0.tar`

### file list

```diff
@@ -1,12 +1,12 @@
--rw-r--r--   0        0        0     1064 2023-06-06 13:10:02.326221 tagreader-4.1.4/LICENSE
--rw-r--r--   0        0        0     2561 2023-06-15 12:41:41.851734 tagreader-4.1.4/README.md
--rw-r--r--   0        0        0     1633 2023-06-28 11:03:37.658388 tagreader-4.1.4/pyproject.toml
--rw-r--r--   0        0        0      351 2023-06-14 10:40:53.499388 tagreader-4.1.4/tagreader/__init__.py
--rw-r--r--   0        0        0      282 2023-06-09 06:24:33.101915 tagreader-4.1.4/tagreader/__version__.py
--rw-r--r--   0        0        0    12723 2023-06-14 10:40:53.499996 tagreader-4.1.4/tagreader/cache.py
--rw-r--r--   0        0        0    23700 2023-06-28 10:48:44.445290 tagreader-4.1.4/tagreader/clients.py
--rw-r--r--   0        0        0      198 2023-06-09 06:24:33.104271 tagreader-4.1.4/tagreader/logger.py
--rw-r--r--   0        0        0    25164 2023-06-21 08:33:16.577206 tagreader-4.1.4/tagreader/odbc_handlers.py
--rw-r--r--   0        0        0     8215 2023-06-14 13:05:07.541522 tagreader-4.1.4/tagreader/utils.py
--rw-r--r--   0        0        0    32496 2023-06-28 10:45:36.341065 tagreader-4.1.4/tagreader/web_handlers.py
--rw-r--r--   0        0        0     4404 1970-01-01 00:00:00.000000 tagreader-4.1.4/PKG-INFO
+-rw-r--r--   0        0        0     1064 2023-06-06 13:10:02.326221 tagreader-4.2.0/LICENSE
+-rw-r--r--   0        0        0     2561 2023-06-15 12:41:41.851734 tagreader-4.2.0/README.md
+-rw-r--r--   0        0        0     1633 2023-06-28 12:51:14.513858 tagreader-4.2.0/pyproject.toml
+-rw-r--r--   0        0        0      351 2023-06-14 10:40:53.499388 tagreader-4.2.0/tagreader/__init__.py
+-rw-r--r--   0        0        0      282 2023-06-09 06:24:33.101915 tagreader-4.2.0/tagreader/__version__.py
+-rw-r--r--   0        0        0    12790 2023-06-28 12:51:14.514876 tagreader-4.2.0/tagreader/cache.py
+-rw-r--r--   0        0        0    23557 2023-06-28 12:51:14.515437 tagreader-4.2.0/tagreader/clients.py
+-rw-r--r--   0        0        0      198 2023-06-09 06:24:33.104271 tagreader-4.2.0/tagreader/logger.py
+-rw-r--r--   0        0        0    25164 2023-06-21 08:33:16.577206 tagreader-4.2.0/tagreader/odbc_handlers.py
+-rw-r--r--   0        0        0     8215 2023-06-14 13:05:07.541522 tagreader-4.2.0/tagreader/utils.py
+-rw-r--r--   0        0        0    32496 2023-06-28 10:45:36.341065 tagreader-4.2.0/tagreader/web_handlers.py
+-rw-r--r--   0        0        0     4404 1970-01-01 00:00:00.000000 tagreader-4.2.0/PKG-INFO
```

### Comparing `tagreader-4.1.4/LICENSE` & `tagreader-4.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `tagreader-4.1.4/README.md` & `tagreader-4.2.0/README.md`

 * *Files identical despite different names*

### Comparing `tagreader-4.1.4/pyproject.toml` & `tagreader-4.2.0/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "tagreader"
-version = "4.1.4"
+version = "4.2.0"
 description = "Tagreader is a Python package for reading trend data from the OSIsoft PI and Aspen Infoplus.21 IMS systems."
 authors = ["Einar S. Idsø <eiids@equinor.com>"]
 license = "MIT"
 readme = "README.md"
 packages = [{include = "tagreader"}]
 keywords=["Aspen InfoPlus.21", "OSIsoft PI"]
 homepage = "https://github.com/equinor/tagreader-python"
```

### Comparing `tagreader-4.1.4/tagreader/cache.py` & `tagreader-4.2.0/tagreader/cache.py`

 * *Files 26% similar despite different names*

```diff
@@ -107,38 +107,38 @@
     def _key_path(
         self,
         tagname: str,
         readtype: ReaderType,
         ts: Union[int, timedelta],
         stepped: bool,
         status: bool,
-        starttime: Optional[datetime] = None,
-        endtime: Optional[datetime] = None,
+        start_time: Optional[datetime] = None,
+        end_time: Optional[datetime] = None,
     ) -> str:
         """Return a string on the form
-        $tagname$readtype[$sample_time][$stepped][$status]$_starttime_endtime
+        $tagname$readtype[$sample_time][$stepped][$status]$_start_time_end_time
         tagname: safe tagname
         sample_time: integer value. Empty for RAW.
         stepped: "stepped" if value was read as stepped. Empty if not.
         status: "status" if value contains status. Empty if not.
-        starttime: The starttime of the query that created the bucket.
-        endtime: The endtime of the query that created the bucket.
+        start_time: The start_time of the query that created the bucket.
+        end_time: The end_time of the query that created the bucket.
         """
         tagname = safe_tagname(tagname)
 
         ts = (
             int(ts.total_seconds())
             if readtype != ReaderType.RAW and isinstance(ts, timedelta)
             else ts
         )
         timespan = ""
-        if starttime is not None:
-            starttime_epoch = timestamp_to_epoch(starttime)
-            endtime_epoch = timestamp_to_epoch(endtime) if endtime else endtime
-            timespan = f"$_{starttime_epoch}_{endtime_epoch}"
+        if start_time is not None:
+            start_time_epoch = timestamp_to_epoch(start_time)
+            end_time_epoch = timestamp_to_epoch(end_time) if end_time else end_time
+            timespan = f"$_{start_time_epoch}_{end_time_epoch}"
 
         keyval = (
             f"${tagname}"
             f"${readtype.name}"
             f"{(ts is not None and readtype != ReaderType.RAW) * f'$s{ts}'}"
             f"{stepped * '$stepped'}"
             f"{status * '$status'}"
@@ -150,112 +150,112 @@
         self,
         df: pd.DataFrame,
         tagname: str,
         readtype: ReaderType,
         ts: timedelta,
         stepped: bool,
         status: bool,
-        starttime: datetime,
-        endtime: datetime,
+        start_time: datetime,
+        end_time: datetime,
     ) -> None:
         if df.empty:
             return
 
         intersecting = self.get_intersecting_datasets(
             tagname=tagname,
             readtype=readtype,
             ts=ts,
             stepped=stepped,
             status=status,
-            starttime=starttime,
-            endtime=endtime,
+            start_time=start_time,
+            end_time=end_time,
         )
         if len(intersecting) > 0:
             for dataset in intersecting:
                 this_start, this_end = self._get_intervals_from_dataset_name(dataset)
-                starttime = min(starttime, this_start if this_start else starttime)
-                endtime = max(endtime, this_end if this_end else endtime)
+                start_time = min(start_time, this_start if this_start else start_time)
+                end_time = max(end_time, this_end if this_end else end_time)
                 df2 = self.get(dataset)
                 if df2 is not None:
                     df = pd.concat([df, df2], axis=0)
                 self.delete(dataset)
         key = self._key_path(
             tagname=tagname,
             readtype=readtype,
             ts=ts,
             stepped=stepped,
             status=status,
-            starttime=starttime,
-            endtime=endtime,
+            start_time=start_time,
+            end_time=end_time,
         )
         self.put(key=key, value=clean_dataframe(df))
 
     @staticmethod
     def _get_intervals_from_dataset_name(
         name: str,
     ) -> Tuple[datetime, datetime]:
         name_with_times = name.split("$")[-1]
         if not name_with_times.count("_") == 2:
             return (None, None)  # type: ignore[return-value]
-        _, starttime_epoch, endtime_epoch = name_with_times.split("_")
-        starttime = pd.to_datetime(int(starttime_epoch), unit="s").tz_localize("UTC")
-        endtime = pd.to_datetime(int(endtime_epoch), unit="s").tz_localize("UTC")
-        return starttime, endtime
+        _, start_time_epoch, end_time_epoch = name_with_times.split("_")
+        start_time = pd.to_datetime(int(start_time_epoch), unit="s").tz_localize("UTC")
+        end_time = pd.to_datetime(int(end_time_epoch), unit="s").tz_localize("UTC")
+        return start_time, end_time
 
     def get_intersecting_datasets(
         self,
         tagname: str,
         readtype: ReaderType,
         ts: Union[int, timedelta],
         stepped: bool,
         status: bool,
-        starttime: datetime,
-        endtime: datetime,
+        start_time: datetime,
+        end_time: datetime,
     ) -> List[str]:
         if not len(self) > 0:
             return []
         intersecting_datasets = []
         for dataset in self.iterkeys():
             target_key = self._key_path(
                 tagname=tagname,
                 readtype=readtype,
-                starttime=None,
-                endtime=None,
+                start_time=None,
+                end_time=None,
                 ts=ts,
                 stepped=stepped,
                 status=status,
             )
             if target_key in dataset:
-                starttime_ds, endtime_ds = self._get_intervals_from_dataset_name(
+                start_time_ds, end_time_ds = self._get_intervals_from_dataset_name(
                     dataset
                 )
-                if endtime_ds >= starttime and endtime >= starttime_ds:
+                if end_time_ds >= start_time and end_time >= start_time_ds:
                     intersecting_datasets.append(dataset)
         return intersecting_datasets
 
     def get_missing_intervals(
         self,
         tagname: str,
         readtype: ReaderType,
         ts: Union[int, timedelta],
         stepped: bool,
         status: bool,
-        starttime: datetime,
-        endtime: datetime,
+        start_time: datetime,
+        end_time: datetime,
     ) -> List[Tuple[datetime, datetime]]:
         datasets = self.get_intersecting_datasets(
             tagname=tagname,
             readtype=readtype,
             ts=ts,
             stepped=stepped,
             status=status,
-            starttime=starttime,
-            endtime=endtime,
+            start_time=start_time,
+            end_time=end_time,
         )
-        missing_intervals = [(starttime, endtime)]
+        missing_intervals = [(start_time, end_time)]
         for dataset in datasets:
             b = self._get_intervals_from_dataset_name(dataset)
             for _ in range(0, len(missing_intervals)):
                 r = missing_intervals.pop(0)
                 if b[1] < r[0] or b[0] > r[1]:
                     # No overlap
                     missing_intervals.append(r)
@@ -277,38 +277,38 @@
     def fetch(
         self,
         tagname: str,
         readtype: ReaderType,
         ts: Union[int, timedelta],
         stepped: bool,
         status: bool,
-        starttime: datetime,
-        endtime: datetime,
+        start_time: datetime,
+        end_time: datetime,
     ) -> pd.DataFrame:
         df = pd.DataFrame()
         if not len(self) > 0:
             return df
 
         if isinstance(ts, timedelta):
             ts = int(ts.total_seconds())
 
         datasets = self.get_intersecting_datasets(
             tagname=tagname,
             readtype=readtype,
             ts=ts,
             stepped=stepped,
             status=status,
-            starttime=starttime,
-            endtime=endtime,
+            start_time=start_time,
+            end_time=end_time,
         )
 
         for dataset in datasets:
             df2 = self.get(dataset)
             if df2 is not None:
-                df = pd.concat([df, df2.loc[starttime:endtime]], axis=0)  # type: ignore[call-overload, misc]
+                df = pd.concat([df, df2.loc[start_time:end_time]], axis=0)  # type: ignore[call-overload, misc]
 
         return clean_dataframe(df)
 
 
 class SmartCache(BaseCache):
     @staticmethod
     def key_path(
```

### Comparing `tagreader-4.1.4/tagreader/clients.py` & `tagreader-4.2.0/tagreader/clients.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,9 @@
-import concurrent
 import os
-from concurrent.futures import ThreadPoolExecutor
+import warnings
 from datetime import datetime, timedelta
 from itertools import groupby
 from operator import itemgetter
 from pathlib import Path
 from typing import Any, Dict, List, Optional, Tuple, Union
 from urllib.error import HTTPError
 
@@ -307,14 +306,15 @@
         tz: pytz.timezone = pytz.timezone("Europe/Oslo"),
         url: Optional[str] = None,
         host: Optional[str] = None,
         port: Optional[int] = None,
         handler_options: Dict[str, Union[int, float, str]] = {},  # noqa:
         verifySSL: bool = True,
         auth: Optional[Any] = None,
+        cache: Optional[Union[SmartCache, BucketCache]] = None,
     ):
         if isinstance(imstype, str):
             try:
                 imstype = getattr(IMSType, imstype.upper())
             except AttributeError:
                 raise ValueError(
                     f"imstype needs to be one of {', '.join([v for v in IMSType.__members__.values()])}."
@@ -328,15 +328,24 @@
             url=url,
             host=host,
             port=port,
             options=handler_options,
             verifySSL=verifySSL,
             auth=auth,
         )
-        self.cache = SmartCache(directory=Path(".") / ".cache" / datasource)
+        if cache:
+            self.cache = cache
+        else:
+            self.cache = SmartCache(directory=Path(".") / ".cache" / datasource)
+            warnings.warn(
+                "Caching will no longer be the default behavior in Tagreader version 5"
+                ". Please spe"
+                "sify chash argument to keep current behaviour.",
+                FutureWarning,
+            )
 
     def connect(self) -> None:
         self.handler.connect()
 
     def search_tag(
         self, tag: Optional[str] = None, desc: Optional[str] = None
     ) -> List[Tuple[str, str]]:
@@ -388,15 +397,15 @@
                     start_time=start_time, stop_time=stop_time, ts=ts, max_steps=None
                 )
                 df = cache.fetch(
                     tagname=tag,
                     readtype=read_type,
                     ts=ts,
                     start_time=time_slice[0],
-                    stop_time=time_slice[1],
+                    end_time=time_slice[1],
                 )
                 missing_intervals = get_missing_intervals(
                     df=df,
                     start_time=start_time,
                     stop_time=stop_time,
                     ts=ts,
                     read_type=read_type,
@@ -415,16 +424,16 @@
                 )
                 missing_intervals = cache.get_missing_intervals(
                     tagname=tag,
                     readtype=read_type,
                     ts=ts,
                     stepped=stepped,
                     status=get_status,
-                    starttime=start_time,
-                    endtime=stop_time,
+                    start_time=start_time,
+                    end_time=stop_time,
                 )
                 if not missing_intervals:
                     return df.tz_convert(self.tz).sort_index()
 
             metadata = self._get_metadata(tag)
             frames = [df]
             for start, stop in missing_intervals:
@@ -607,38 +616,29 @@
         tags = list(dict.fromkeys(tags))
         if len(oldtags) > len(tags):
             duplicates = set([x for n, x in enumerate(oldtags) if x in oldtags[:n]])
             logger.warning(
                 f"Duplicate tags found, removed duplicates: {', '.join(duplicates)}"
             )
 
-        # Fixme: Temporary reading from IMS using Threads to improve performance. Need to use batch queries or at least
-        #     keep the same connection between queries.
         results = []
-        with ThreadPoolExecutor(
-            max_workers=min(10, (os.cpu_count() or 1) + 4)
-        ) as executor:
-            for i, tag in enumerate(tags):
-                results.append(
-                    executor.submit(
-                        self._read_single_tag,
-                        tag=tag,
-                        start_time=start_time,
-                        stop_time=end_time,
-                        ts=ts,
-                        read_type=read_type,
-                        get_status=get_status,
-                        cache=self.cache,
-                    )
+        for i, tag in enumerate(tags):
+            results.append(
+                self._read_single_tag(
+                    tag=tag,
+                    start_time=start_time,
+                    stop_time=end_time,
+                    ts=ts,
+                    read_type=read_type,
+                    get_status=get_status,
+                    cache=self.cache,
                 )
+            )
 
-        return pd.concat(
-            [result.result() for result in concurrent.futures.as_completed(results)],
-            axis=1,
-        )
+        return pd.concat(results, axis=1)
 
     def query_sql(self, query: str, parse: bool = True):
         """[summary]
         Args:
             query (str): [description]
             parse (bool, optional): Whether to attempt to parse query return
                                     value as table. Defaults to True.
```

### Comparing `tagreader-4.1.4/tagreader/odbc_handlers.py` & `tagreader-4.2.0/tagreader/odbc_handlers.py`

 * *Files identical despite different names*

### Comparing `tagreader-4.1.4/tagreader/utils.py` & `tagreader-4.2.0/tagreader/utils.py`

 * *Files identical despite different names*

### Comparing `tagreader-4.1.4/tagreader/web_handlers.py` & `tagreader-4.2.0/tagreader/web_handlers.py`

 * *Files identical despite different names*

### Comparing `tagreader-4.1.4/PKG-INFO` & `tagreader-4.2.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tagreader
-Version: 4.1.4
+Version: 4.2.0
 Summary: Tagreader is a Python package for reading trend data from the OSIsoft PI and Aspen Infoplus.21 IMS systems.
 Home-page: https://github.com/equinor/tagreader-python
 License: MIT
 Keywords: Aspen InfoPlus.21,OSIsoft PI
 Author: Einar S. Idsø
 Author-email: eiids@equinor.com
 Requires-Python: >=3.8,<4.0
```


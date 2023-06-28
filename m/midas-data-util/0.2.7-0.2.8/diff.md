# Comparing `tmp/midas-data-util-0.2.7.tar.gz` & `tmp/midas-data-util-0.2.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "midas-data-util-0.2.7.tar", last modified: Tue Jun 27 23:15:53 2023, max compression
+gzip compressed data, was "midas-data-util-0.2.8.tar", last modified: Wed Jun 28 00:00:49 2023, max compression
```

## Comparing `midas-data-util-0.2.7.tar` & `midas-data-util-0.2.8.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 23:15:53.471872 midas-data-util-0.2.7/
--rw-rw-rw-   0        0        0    11558 2023-04-07 08:14:57.000000 midas-data-util-0.2.7/LICENSE
--rw-rw-rw-   0        0        0      520 2023-06-27 23:15:53.469878 midas-data-util-0.2.7/PKG-INFO
--rw-rw-rw-   0        0        0      116 2023-04-07 08:58:48.000000 midas-data-util-0.2.7/README.md
--rw-rw-rw-   0        0        0      623 2023-06-27 23:14:52.000000 midas-data-util-0.2.7/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-27 23:15:53.471872 midas-data-util-0.2.7/setup.cfg
-drwxrwxrwx   0        0        0        0 2023-06-27 23:15:53.338104 midas-data-util-0.2.7/src/
-drwxrwxrwx   0        0        0        0 2023-06-27 23:15:53.379858 midas-data-util-0.2.7/src/midas/
--rw-rw-rw-   0        0        0     2631 2023-04-12 07:17:33.000000 midas-data-util-0.2.7/src/midas/__init__.py
--rw-rw-rw-   0        0        0     6044 2023-06-27 23:13:59.000000 midas-data-util-0.2.7/src/midas/data_encoder.py
--rw-rw-rw-   0        0        0    11528 2023-04-12 11:59:47.000000 midas-data-util-0.2.7/src/midas/event.py
--rw-rw-rw-   0        0        0     9382 2023-06-26 00:40:40.000000 midas-data-util-0.2.7/src/midas/playfab.py
--rw-rw-rw-   0        0        0     4327 2023-04-12 12:04:40.000000 midas-data-util-0.2.7/src/midas/session.py
--rw-rw-rw-   0        0        0     3448 2023-04-12 12:05:02.000000 midas-data-util-0.2.7/src/midas/user.py
-drwxrwxrwx   0        0        0        0 2023-06-27 23:15:53.462896 midas-data-util-0.2.7/src/midas_data_util.egg-info/
--rw-rw-rw-   0        0        0      520 2023-06-27 23:15:53.000000 midas-data-util-0.2.7/src/midas_data_util.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      373 2023-06-27 23:15:53.000000 midas-data-util-0.2.7/src/midas_data_util.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 23:15:53.000000 midas-data-util-0.2.7/src/midas_data_util.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       87 2023-06-27 23:15:53.000000 midas-data-util-0.2.7/src/midas_data_util.egg-info/requires.txt
--rw-rw-rw-   0        0        0        6 2023-06-27 23:15:53.000000 midas-data-util-0.2.7/src/midas_data_util.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 00:00:49.096859 midas-data-util-0.2.8/
+-rw-rw-rw-   0        0        0    11558 2023-04-07 08:14:57.000000 midas-data-util-0.2.8/LICENSE
+-rw-rw-rw-   0        0        0      520 2023-06-28 00:00:49.095861 midas-data-util-0.2.8/PKG-INFO
+-rw-rw-rw-   0        0        0      116 2023-04-07 08:58:48.000000 midas-data-util-0.2.8/README.md
+-rw-rw-rw-   0        0        0      623 2023-06-27 23:59:30.000000 midas-data-util-0.2.8/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 00:00:49.096859 midas-data-util-0.2.8/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 00:00:49.048955 midas-data-util-0.2.8/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 00:00:49.068911 midas-data-util-0.2.8/src/midas/
+-rw-rw-rw-   0        0        0     2631 2023-04-12 07:17:33.000000 midas-data-util-0.2.8/src/midas/__init__.py
+-rw-rw-rw-   0        0        0     6114 2023-06-28 00:00:25.000000 midas-data-util-0.2.8/src/midas/data_encoder.py
+-rw-rw-rw-   0        0        0    11559 2023-06-28 00:00:25.000000 midas-data-util-0.2.8/src/midas/event.py
+-rw-rw-rw-   0        0        0     9382 2023-06-26 00:40:40.000000 midas-data-util-0.2.8/src/midas/playfab.py
+-rw-rw-rw-   0        0        0     4327 2023-04-12 12:04:40.000000 midas-data-util-0.2.8/src/midas/session.py
+-rw-rw-rw-   0        0        0     3448 2023-04-12 12:05:02.000000 midas-data-util-0.2.8/src/midas/user.py
+drwxrwxrwx   0        0        0        0 2023-06-28 00:00:49.093868 midas-data-util-0.2.8/src/midas_data_util.egg-info/
+-rw-rw-rw-   0        0        0      520 2023-06-28 00:00:49.000000 midas-data-util-0.2.8/src/midas_data_util.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      373 2023-06-28 00:00:49.000000 midas-data-util-0.2.8/src/midas_data_util.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 00:00:49.000000 midas-data-util-0.2.8/src/midas_data_util.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       87 2023-06-28 00:00:49.000000 midas-data-util-0.2.8/src/midas_data_util.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 00:00:49.000000 midas-data-util-0.2.8/src/midas_data_util.egg-info/top_level.txt
```

### Comparing `midas-data-util-0.2.7/LICENSE` & `midas-data-util-0.2.8/LICENSE`

 * *Files identical despite different names*

### Comparing `midas-data-util-0.2.7/PKG-INFO` & `midas-data-util-0.2.8/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: midas-data-util
-Version: 0.2.7
+Version: 0.2.8
 Summary: a package with useful functions for downloading and working with midas generated analytics data
 Author-email: nightcycle <coyer@nightcycle.us>
 Classifier: Programming Language :: Python :: 3
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.10
 Description-Content-Type: text/markdown
 License-File: LICENSE
```

### Comparing `midas-data-util-0.2.7/pyproject.toml` & `midas-data-util-0.2.8/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools>=61.0"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "midas-data-util"
-version = "0.2.7"
+version = "0.2.8"
 authors = [
   { name="nightcycle", email="coyer@nightcycle.us" },
 ]
 dependencies = [
 	"lxml~=4.9.2", 
 	"pandas~=2.0.0",
 	"adal~=1.2.7",
```

### Comparing `midas-data-util-0.2.7/src/midas/__init__.py` & `midas-data-util-0.2.8/src/midas/__init__.py`

 * *Files identical despite different names*

### Comparing `midas-data-util-0.2.7/src/midas/data_encoder.py` & `midas-data-util-0.2.8/src/midas/data_encoder.py`

 * *Files 4% similar despite different names*

```diff
@@ -193,34 +193,42 @@
 
 			out[k] = v
 
 		return out
 
 	return restore_values(restore_keys(encoded_data), encoding_value_dict, encoding_arrays)
 
-def replace_quoted_strings(text):
-    pattern = r'""(.+?)"":'
-    replacement = r'\'\1\':'
-    result = re.sub(pattern, replacement, text)
-    return result
+def format_json_str(text) -> str:
+	text = text.replace("'\":", "`\":")
+	text = text.replace("\"'", "\"`")
+	text = text.replace("\"", "'")
+	text = text.replace("'", "\"")
+	text = text.replace("`", "'")
+	text = text.replace("False", "false")
+	text = text.replace("True", "true")
+
+	return text
 
 def decode_raw_df(raw_df: DataFrame, encoding_config: Any) -> DataFrame:
 	untyped_raw_df: Any = raw_df
 	raw_record_list: list[RawRowData] = untyped_raw_df.to_dict(orient="records")
 
 	decoded_record_list: list[DecodedRowData] = []
 	for raw_row_data in raw_record_list:
 		event_data: Any = {}
 		if type(raw_row_data["EventData"]) == str:
-			encoded_data_str = replace_quoted_strings(raw_row_data["EventData"].replace("'", "\"").replace("False", "false").replace("True", "true"))
+
+			encoded_data_str = format_json_str(raw_row_data["EventData"])
+	
 			event_data = json.loads(encoded_data_str)
 		else:
 			event_data = raw_row_data["EventData"]
 		encoded_state_data = event_data["State"]
 		decoded_state_data = decode(encoded_state_data, encoding_config)
+
 		event_data["State"] = decoded_state_data
 		decoded_row_data: DecodedRowData = {
 				"EventData": event_data,
 				"Timestamp": raw_row_data["Timestamp"],
 				"PlayFabUserId": raw_row_data["PlayFabUserId"],
 				"EventName": raw_row_data["EventName"],
 				"EventId": raw_row_data["EventId"],
```

### Comparing `midas-data-util-0.2.7/src/midas/event.py` & `midas-data-util-0.2.8/src/midas/event.py`

 * *Files 1% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 import json
 from uuid import uuid4
 from pandas import DataFrame
 from datetime import datetime
 from typing import Any
 from .playfab import get_datetime_from_playfab_str, get_playfab_str_from_datetime
 from .data_encoder import DecodedRowData as RowData
-from .data_encoder import VersionData, EventData, BaseStateTree
+from .data_encoder import VersionData, EventData, BaseStateTree, format_json_str
 
 SID_GEN_REFIX = "!generated"
 
 def get_if_session_id_generated(session_id: str) -> bool:
 	pattern = session_id[0:len(SID_GEN_REFIX)]
 	result = pattern == SID_GEN_REFIX
 	# print(f"is_gen: {result} since {pattern} is start of {session_id}")
@@ -75,15 +75,14 @@
 	is_sequential: bool
 	state_date: BaseStateTree
 
 	def __init__(
 		self, 
 		row_data: RowData
 	):
-		
 		self.name = row_data["EventName"]
 		self.event_id = row_data["EventId"]
 		self.timestamp: datetime = get_datetime_from_playfab_str(row_data["Timestamp"])
 
 		event_data: EventData = row_data["EventData"]
 		state_data = event_data["State"]
 	
@@ -201,17 +200,18 @@
 ) -> list[Event]:
 	initial_events: list[Event] = []
 
 	user_events: dict[str, list[Event]] = {}
 
 	print("organizing events by user_id")
 	for row_index, row_data in decoded_df.iterrows():
-
 		if type(row_data["EventData"]) == str:
-			row_data["EventData"] = json.loads(row_data["EventData"].replace("'", "\"").replace("False", "false").replace("True", "true"))
+			event_data = json.loads(format_json_str(row_data["EventData"]))
+			print(json.dumps(event_data, indent=5))
+			row_data["EventData"] = event_data
 
 		event = Event(row_data)
 		if not event.user_id in user_events:
 			user_events[event.user_id] = []
 		
 		user_events[event.user_id].append(event)
 		initial_events.append(event)
```

### Comparing `midas-data-util-0.2.7/src/midas/playfab.py` & `midas-data-util-0.2.8/src/midas/playfab.py`

 * *Files identical despite different names*

### Comparing `midas-data-util-0.2.7/src/midas/session.py` & `midas-data-util-0.2.8/src/midas/session.py`

 * *Files identical despite different names*

### Comparing `midas-data-util-0.2.7/src/midas/user.py` & `midas-data-util-0.2.8/src/midas/user.py`

 * *Files identical despite different names*

### Comparing `midas-data-util-0.2.7/src/midas_data_util.egg-info/PKG-INFO` & `midas-data-util-0.2.8/src/midas_data_util.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: midas-data-util
-Version: 0.2.7
+Version: 0.2.8
 Summary: a package with useful functions for downloading and working with midas generated analytics data
 Author-email: nightcycle <coyer@nightcycle.us>
 Classifier: Programming Language :: Python :: 3
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.10
 Description-Content-Type: text/markdown
 License-File: LICENSE
```


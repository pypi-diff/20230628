# Comparing `tmp/mighty_logger-0.7.0.tar.gz` & `tmp/mighty_logger-0.7.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mighty_logger-0.7.0.tar", last modified: Mon Jun 26 14:26:27 2023, max compression
+gzip compressed data, was "mighty_logger-0.7.1.tar", last modified: Wed Jun 28 10:18:30 2023, max compression
```

## Comparing `mighty_logger-0.7.0.tar` & `mighty_logger-0.7.1.tar`

### file list

```diff
@@ -1,39 +1,44 @@
-drwxrwxrwx   0        0        0        0 2023-06-26 14:26:27.352771 mighty_logger-0.7.0/
--rw-rw-rw-   0        0        0    11357 2023-04-10 16:24:05.000000 mighty_logger-0.7.0/LICENSE
--rw-rw-rw-   0        0        0    10783 2023-06-26 14:26:27.352771 mighty_logger-0.7.0/PKG-INFO
--rw-rw-rw-   0        0        0     9841 2023-06-26 14:22:34.000000 mighty_logger-0.7.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-26 14:26:27.267418 mighty_logger-0.7.0/mighty_logger/
--rw-rw-rw-   0        0        0      863 2023-06-24 13:25:16.000000 mighty_logger-0.7.0/mighty_logger/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-26 14:26:27.300465 mighty_logger-0.7.0/mighty_logger/basic/
--rw-rw-rw-   0        0        0      789 2023-06-26 10:51:25.000000 mighty_logger-0.7.0/mighty_logger/basic/__init__.py
--rw-rw-rw-   0        0        0     8304 2023-06-25 13:09:47.000000 mighty_logger-0.7.0/mighty_logger/basic/basic_logger.py
--rw-rw-rw-   0        0        0     1499 2023-06-26 10:49:56.000000 mighty_logger-0.7.0/mighty_logger/basic/exceptions.py
-drwxrwxrwx   0        0        0        0 2023-06-26 14:26:27.319235 mighty_logger-0.7.0/mighty_logger/basic/lib_types/
--rw-rw-rw-   0        0        0      875 2023-06-25 13:20:13.000000 mighty_logger-0.7.0/mighty_logger/basic/lib_types/__init__.py
--rw-rw-rw-   0        0        0     1086 2023-06-25 13:07:43.000000 mighty_logger-0.7.0/mighty_logger/basic/lib_types/animation_type.py
--rw-rw-rw-   0        0        0     1848 2023-06-25 13:06:36.000000 mighty_logger-0.7.0/mighty_logger/basic/lib_types/entry_type.py
--rw-rw-rw-   0        0        0     1297 2023-06-26 11:32:43.000000 mighty_logger-0.7.0/mighty_logger/basic/lib_types/environment_type.py
--rw-rw-rw-   0        0        0      874 2023-06-25 13:06:36.000000 mighty_logger-0.7.0/mighty_logger/basic/lib_types/status_message_type.py
--rw-rw-rw-   0        0        0     4317 2023-06-26 11:33:46.000000 mighty_logger-0.7.0/mighty_logger/basic/lib_types/text_buffer_type.py
--rw-rw-rw-   0        0        0      823 2023-04-11 10:58:04.000000 mighty_logger-0.7.0/mighty_logger/basic/patterns.py
--rw-rw-rw-   0        0        0    27826 2023-06-26 11:10:15.000000 mighty_logger-0.7.0/mighty_logger/powerful_logger.py
--rw-rw-rw-   0        0        0     7054 2023-06-26 11:10:15.000000 mighty_logger-0.7.0/mighty_logger/simple_logger.py
-drwxrwxrwx   0        0        0        0 2023-06-26 14:26:27.348772 mighty_logger-0.7.0/mighty_logger/src/
--rw-rw-rw-   0        0        0     1110 2023-06-24 13:02:04.000000 mighty_logger-0.7.0/mighty_logger/src/__init__.py
--rw-rw-rw-   0        0        0     9975 2023-06-25 13:20:13.000000 mighty_logger-0.7.0/mighty_logger/src/animation.py
--rw-rw-rw-   0        0        0     4572 2023-06-11 16:58:31.000000 mighty_logger-0.7.0/mighty_logger/src/ansi_format.py
--rw-rw-rw-   0        0        0     8659 2023-06-11 16:58:31.000000 mighty_logger-0.7.0/mighty_logger/src/color_picker.py
--rw-rw-rw-   0        0        0    38487 2023-06-25 13:20:13.000000 mighty_logger-0.7.0/mighty_logger/src/entry_types.py
--rw-rw-rw-   0        0        0     1140 2023-06-25 13:20:13.000000 mighty_logger-0.7.0/mighty_logger/src/environments.py
--rw-rw-rw-   0        0        0     5473 2023-06-25 13:20:13.000000 mighty_logger-0.7.0/mighty_logger/src/status_variables.py
--rw-rw-rw-   0        0        0    10787 2023-06-26 11:01:56.000000 mighty_logger-0.7.0/mighty_logger/src/text_buffer.py
-drwxrwxrwx   0        0        0        0 2023-06-26 14:26:27.272243 mighty_logger-0.7.0/mighty_logger.egg-info/
--rw-rw-rw-   0        0        0    10783 2023-06-26 14:26:27.000000 mighty_logger-0.7.0/mighty_logger.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      994 2023-06-26 14:26:27.000000 mighty_logger-0.7.0/mighty_logger.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-26 14:26:27.000000 mighty_logger-0.7.0/mighty_logger.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       14 2023-06-26 14:26:27.000000 mighty_logger-0.7.0/mighty_logger.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-26 14:26:27.353772 mighty_logger-0.7.0/setup.cfg
--rw-rw-rw-   0        0        0     1707 2023-06-25 13:24:09.000000 mighty_logger-0.7.0/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-26 14:26:27.350771 mighty_logger-0.7.0/test/
--rw-rw-rw-   0        0        0     2626 2023-06-25 14:48:08.000000 mighty_logger-0.7.0/test/test.py
--rw-rw-rw-   0        0        0      837 2023-06-26 10:38:49.000000 mighty_logger-0.7.0/test/test_simple.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.974367 mighty_logger-0.7.1/
+-rw-rw-rw-   0        0        0    11357 2023-04-10 16:24:05.000000 mighty_logger-0.7.1/LICENSE
+-rw-rw-rw-   0        0        0    10813 2023-06-28 10:18:30.975366 mighty_logger-0.7.1/PKG-INFO
+-rw-rw-rw-   0        0        0     9871 2023-06-27 18:52:45.000000 mighty_logger-0.7.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.896680 mighty_logger-0.7.1/mighty_logger/
+-rw-rw-rw-   0        0        0      863 2023-06-27 18:40:32.000000 mighty_logger-0.7.1/mighty_logger/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.909681 mighty_logger-0.7.1/mighty_logger/basic/
+-rw-rw-rw-   0        0        0      789 2023-06-26 10:51:25.000000 mighty_logger-0.7.1/mighty_logger/basic/__init__.py
+-rw-rw-rw-   0        0        0     9979 2023-06-28 09:48:23.000000 mighty_logger-0.7.1/mighty_logger/basic/basic_logger.py
+-rw-rw-rw-   0        0        0     1499 2023-06-26 10:49:56.000000 mighty_logger-0.7.1/mighty_logger/basic/exceptions.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.943501 mighty_logger-0.7.1/mighty_logger/basic/lib_types/
+-rw-rw-rw-   0        0        0      921 2023-06-27 12:43:22.000000 mighty_logger-0.7.1/mighty_logger/basic/lib_types/__init__.py
+-rw-rw-rw-   0        0        0     1086 2023-06-25 13:07:43.000000 mighty_logger-0.7.1/mighty_logger/basic/lib_types/animation_type.py
+-rw-rw-rw-   0        0        0     1883 2023-06-27 18:12:22.000000 mighty_logger-0.7.1/mighty_logger/basic/lib_types/entry_type.py
+-rw-rw-rw-   0        0        0     1297 2023-06-26 11:32:43.000000 mighty_logger-0.7.1/mighty_logger/basic/lib_types/environment_type.py
+-rw-rw-rw-   0        0        0      798 2023-06-27 12:43:22.000000 mighty_logger-0.7.1/mighty_logger/basic/lib_types/sorting_key_type.py
+-rw-rw-rw-   0        0        0      874 2023-06-25 13:06:36.000000 mighty_logger-0.7.1/mighty_logger/basic/lib_types/status_message_type.py
+-rw-rw-rw-   0        0        0     4317 2023-06-26 11:33:46.000000 mighty_logger-0.7.1/mighty_logger/basic/lib_types/text_buffer_type.py
+-rw-rw-rw-   0        0        0     6862 2023-06-28 09:48:23.000000 mighty_logger-0.7.1/mighty_logger/basic/modifier.py
+-rw-rw-rw-   0        0        0      823 2023-04-11 10:58:04.000000 mighty_logger-0.7.1/mighty_logger/basic/patterns.py
+-rw-rw-rw-   0        0        0    28476 2023-06-28 09:48:23.000000 mighty_logger-0.7.1/mighty_logger/powerful_logger.py
+-rw-rw-rw-   0        0        0     6701 2023-06-28 09:53:14.000000 mighty_logger-0.7.1/mighty_logger/simple_logger.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.966690 mighty_logger-0.7.1/mighty_logger/src/
+-rw-rw-rw-   0        0        0      956 2023-06-28 09:48:23.000000 mighty_logger-0.7.1/mighty_logger/src/__init__.py
+-rw-rw-rw-   0        0        0     9975 2023-06-25 13:20:13.000000 mighty_logger-0.7.1/mighty_logger/src/animations.py
+-rw-rw-rw-   0        0        0     4572 2023-06-11 16:58:31.000000 mighty_logger-0.7.1/mighty_logger/src/ansi_format.py
+-rw-rw-rw-   0        0        0     8659 2023-06-11 16:58:31.000000 mighty_logger-0.7.1/mighty_logger/src/color_picker.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.971752 mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/
+-rw-rw-rw-   0        0        0      810 2023-06-28 09:48:23.000000 mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/__init__.py
+-rw-rw-rw-   0        0        0    39613 2023-06-27 18:12:22.000000 mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/entry_types.py
+-rw-rw-rw-   0        0        0     1140 2023-06-25 13:20:13.000000 mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/environments.py
+-rw-rw-rw-   0        0        0      873 2023-06-27 12:43:22.000000 mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/sorting_keys.py
+-rw-rw-rw-   0        0        0     5473 2023-06-25 13:20:13.000000 mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/status_variables.py
+-rw-rw-rw-   0        0        0    10808 2023-06-28 09:48:23.000000 mighty_logger-0.7.1/mighty_logger/src/text_buffer.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.900681 mighty_logger-0.7.1/mighty_logger.egg-info/
+-rw-rw-rw-   0        0        0    10813 2023-06-28 10:18:30.000000 mighty_logger-0.7.1/mighty_logger.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     1246 2023-06-28 10:18:30.000000 mighty_logger-0.7.1/mighty_logger.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 10:18:30.000000 mighty_logger-0.7.1/mighty_logger.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       14 2023-06-28 10:18:30.000000 mighty_logger-0.7.1/mighty_logger.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 10:18:30.975366 mighty_logger-0.7.1/setup.cfg
+-rw-rw-rw-   0        0        0     1757 2023-06-28 09:49:41.000000 mighty_logger-0.7.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.974367 mighty_logger-0.7.1/test/
+-rw-rw-rw-   0        0        0     3073 2023-06-28 09:53:14.000000 mighty_logger-0.7.1/test/test.py
+-rw-rw-rw-   0        0        0      924 2023-06-28 09:53:14.000000 mighty_logger-0.7.1/test/test_simple.py
```

### Comparing `mighty_logger-0.7.0/LICENSE` & `mighty_logger-0.7.1/LICENSE`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.0/PKG-INFO` & `mighty_logger-0.7.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mighty_logger
-Version: 0.7.0
+Version: 0.7.1
 Summary: Powerful functional logger
 Home-page: https://github.com/Nakama3942/mighty_logger
 Author: Kalynovsky 'Nakamura Akira' Valentin
 Author-email: nakama3942@gmail.com
 License: Apache License, Version 2.0, see LICENSE file
 Project-URL: Releases, https://github.com/Nakama3942/mighty_logger/releases
 Classifier: Development Status :: 3 - Alpha
@@ -104,15 +104,15 @@
 - [x] v0.3.0 - Background update (added background for log entries)
 - [x] v0.4.0 - Buffer update (added text buffer)
 - [x] v0.5.0 - Unifying update (console and HTML are combined into one class)
 - [x] v0.5.1 - Hints update (added status message templates and hint symbols (icons) near log entries status)
 - [x] v0.6.0 - Progress update (added start of some log entries in threads (process))
 - [x] v0.6.1 - Animation update (added animations in processes)
 - [x] v0.7.0 - "Buffer improvement" update (buffer development completed and entry type system reworked)
-- [ ] v0.7.1 - Search update (added search by log entry types)
+- [x] v0.7.1 - Modding update (buffer modification added - sorting, searching and selecting)
 - [ ] v0.8.0 - Export update (added conversion to different types, such as csv, pdf, etc.)
 - [ ] v0.9.0 - Extension update (made wheel format and instruction of toml)
 - [ ] v0.9.1 - Documenting update (all updates since v0.7.0 are documented; updated old documentation; documentation site generation added)
 - [ ] v1.0.0 - Completion of logger development (logger development completed)
 - [ ] v1.1.0 - Font update (added a class that formats text outside the logger)
 
 </details>
```

### Comparing `mighty_logger-0.7.0/README.md` & `mighty_logger-0.7.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -85,15 +85,15 @@
 - [x] v0.3.0 - Background update (added background for log entries)
 - [x] v0.4.0 - Buffer update (added text buffer)
 - [x] v0.5.0 - Unifying update (console and HTML are combined into one class)
 - [x] v0.5.1 - Hints update (added status message templates and hint symbols (icons) near log entries status)
 - [x] v0.6.0 - Progress update (added start of some log entries in threads (process))
 - [x] v0.6.1 - Animation update (added animations in processes)
 - [x] v0.7.0 - "Buffer improvement" update (buffer development completed and entry type system reworked)
-- [ ] v0.7.1 - Search update (added search by log entry types)
+- [x] v0.7.1 - Modding update (buffer modification added - sorting, searching and selecting)
 - [ ] v0.8.0 - Export update (added conversion to different types, such as csv, pdf, etc.)
 - [ ] v0.9.0 - Extension update (made wheel format and instruction of toml)
 - [ ] v0.9.1 - Documenting update (all updates since v0.7.0 are documented; updated old documentation; documentation site generation added)
 - [ ] v1.0.0 - Completion of logger development (logger development completed)
 - [ ] v1.1.0 - Font update (added a class that formats text outside the logger)
 
 </details>
```

### Comparing `mighty_logger-0.7.0/mighty_logger/__init__.py` & `mighty_logger-0.7.1/mighty_logger/__init__.py`

 * *Files 10% similar despite different names*

```diff
@@ -12,13 +12,13 @@
 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
 """
 
-from .powerful_logger import Logger
-from .simple_logger import SimpleLogger
+from .powerful_logger import MightyLogger
+from .simple_logger import Logger
 
 __authot__ = "Kalynovsky 'Nakamura Akira' Valentin"
-__version__ = "0.7.0"
+__version__ = "0.7.1"
 __email__ = "nakama3942@gmail.com"
```

### Comparing `mighty_logger-0.7.0/mighty_logger/basic/__init__.py` & `mighty_logger-0.7.1/mighty_logger/basic/__init__.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.0/mighty_logger/basic/basic_logger.py` & `mighty_logger-0.7.1/mighty_logger/basic/basic_logger.py`

 * *Files 17% similar despite different names*

```diff
@@ -14,18 +14,19 @@
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
 """
 
 import datetime, platform, os, random
 
+from mighty_logger.basic.lib_types.entry_type import EntryType
 from mighty_logger.basic.lib_types.environment_type import EnvironmentType
 from mighty_logger.basic.patterns import Singleton
+from mighty_logger.src.lib_types_collection.environments import LogEnvironments
 from mighty_logger.src.ansi_format import GetAnsiFormat
-from mighty_logger.src.environments import LogEnvironments
 
 class BasicLogger(Singleton):
 	def __init__(
 		self,
 		program_name: str,
 		env: EnvironmentType
 	) -> None:
@@ -96,20 +97,20 @@
 					f":{platform.version()}" +
 					":{}:{}".format(*platform.architecture()) +
 					f":{platform.machine()}"
 				)
 
 	def _assemble_entry(
 		self,
-		colors: list[str, str, str, str, str, str],
+		entry_type: EntryType,
+		icon_set: int,
 		animation: str,
-		icon: str,
 		status_message_text: str,
-		message_type: str,
 		message_text: str,
+		entry_background: bool,
 		local_settings: dict
 	) -> str:
 		"""
 		A method that assemble an entry into a string and returns it.
 
 		:param colors: 6 colors that the method uses to assemble the string
 		:param animation: Animation of entry
@@ -131,67 +132,67 @@
 
 		match self._environment.environment_name:
 			case LogEnvironments.CONSOLE.environment_name:
 				return (
 					(f"{GetAnsiFormat('bold/on')}" if bold else "") +
 					(f"{GetAnsiFormat('italic/on')}" if italic else "") +
 					(f"{GetAnsiFormat('invert/on')}" if invert else "") +
-					f"{colors[5]}" +
-					f"{colors[4]}-?entry> {animation} " +
-					(f"{colors[0]}*{datetime.datetime.now()} " if time_entry else "") +
-					f"{icon} " +
-					(f"{colors[1]}#STATUS: " if status_entry else "") +
-					(f"{colors[2]}{status_message_text} " if status_message_entry else "") +
-					(f"{colors[3]}{message_type} - " if status_type_entry else "") +
-					(f"{colors[4]}{message_text}" if message_entry else "") +
+					f"{entry_type.background_color[self._environment.environment_code][entry_background]}" +
+					f"{entry_type.message_color[self._environment.environment_code][entry_background]}-?entry> {animation} " +
+					(f"{entry_type.time_color[self._environment.environment_code][entry_background]}*{datetime.datetime.now()} " if time_entry else "") +
+					f"{entry_type.icon[icon_set]} " +
+					(f"{entry_type.status_color[self._environment.environment_code][entry_background]}#STATUS: " if status_entry else "") +
+					(f"{entry_type.status_message_color[self._environment.environment_code][entry_background]}{status_message_text} " if status_message_entry else "") +
+					(f"{entry_type.type_color[self._environment.environment_code][entry_background]}{entry_type.type_name} - " if status_type_entry else "") +
+					(f"{entry_type.message_color[self._environment.environment_code][entry_background]}{message_text}" if message_entry else "") +
 					f"{GetAnsiFormat('reset/on')}"
 				)
 			case LogEnvironments.PLAIN_CONSOLE.environment_name:
 				return (
 					f"-?entry> {animation} " +
 					(f"*{datetime.datetime.now()} " if time_entry else "") +
-					f"{icon} " +
+					f"{entry_type.icon[icon_set]} " +
 					(f"#STATUS: " if status_entry else "") +
 					(f"{status_message_text} " if status_message_entry else "") +
-					(f"{message_type} - " if status_type_entry else "") +
+					(f"{entry_type.type_name} - " if status_type_entry else "") +
 					(f"{message_text}" if message_entry else "")
 				)
 			case LogEnvironments.HTML.environment_name:
 				return (
 					(f"<b>" if bold else "") +
 					(f"<i>" if italic else "") +
-					f"<span style='background-color: #{colors[5]};'>" +
-					f"<span style='color: #{colors[4]};'>-?entry> {animation} </span>" +
-					(f"<span style='color: #{colors[0]};'>*{datetime.datetime.now()} </span>" if time_entry else "") +
-					f"{icon} " +
-					(f"<span style='color: #{colors[1]};'>#STATUS: </span>" if status_entry else "") +
-					(f"<span style='color: #{colors[2]};'>{status_message_text} </span>" if status_message_entry else "") +
-					(f"<span style='color: #{colors[3]};'>{message_type} - </span>" if status_type_entry else "") +
-					(f"<span style='color: #{colors[4]};'>{message_text}</span></span>" if message_entry else "") +
+					f"<span style='background-color: #{entry_type.background_color[self._environment.environment_code][entry_background]};'>" +
+					f"<span style='color: #{entry_type.message_color[self._environment.environment_code][entry_background]};'>-?entry> {animation} </span>" +
+					(f"<span style='color: #{entry_type.time_color[self._environment.environment_code][entry_background]};'>*{datetime.datetime.now()} </span>" if time_entry else "") +
+					f"{entry_type.icon[icon_set]} " +
+					(f"<span style='color: #{entry_type.status_color[self._environment.environment_code][entry_background]};'>#STATUS: </span>" if status_entry else "") +
+					(f"<span style='color: #{entry_type.status_message_color[self._environment.environment_code][entry_background]};'>{status_message_text} </span>" if status_message_entry else "") +
+					(f"<span style='color: #{entry_type.type_color[self._environment.environment_code][entry_background]};'>{entry_type.type_name} - </span>" if status_type_entry else "") +
+					(f"<span style='color: #{entry_type.message_color[self._environment.environment_code][entry_background]};'>{message_text}</span></span>" if message_entry else "") +
 					(f"</i>" if italic else "") +
 					(f"</b>" if bold else "")
 				)
 			case LogEnvironments.MARKDOWN.environment_name:
 				return (
 						(f"<b>" if bold else "") +
 						(f"<i>" if italic else "") +
-						f"<span style='background-color: #{colors[5]};'>" +
-						f"<span style='color: #{colors[4]};'>-?entry> {animation} </span>" +
-						(f"<span style='color: #{colors[0]};'>*{datetime.datetime.now()} </span>" if time_entry else "") +
-						f"{icon} " +
-						(f"<span style='color: #{colors[1]};'>#STATUS: </span>" if status_entry else "") +
-						(f"<span style='color: #{colors[2]};'>{status_message_text} </span>" if status_message_entry else "") +
-						(f"<span style='color: #{colors[3]};'>{message_type} - </span>" if status_type_entry else "") +
-						(f"<span style='color: #{colors[4]};'>{message_text}</span></span>" if message_entry else "") +
+						f"<span style='background-color: #{entry_type.background_color[self._environment.environment_code][entry_background]};'>" +
+						f"<span style='color: #{entry_type.message_color[self._environment.environment_code][entry_background]};'>-?entry> {animation} </span>" +
+						(f"<span style='color: #{entry_type.time_color[self._environment.environment_code][entry_background]};'>*{datetime.datetime.now()} </span>" if time_entry else "") +
+						f"{entry_type.icon[icon_set]} " +
+						(f"<span style='color: #{entry_type.status_color[self._environment.environment_code][entry_background]};'>#STATUS: </span>" if status_entry else "") +
+						(f"<span style='color: #{entry_type.status_message_color[self._environment.environment_code][entry_background]};'>{status_message_text} </span>" if status_message_entry else "") +
+						(f"<span style='color: #{entry_type.type_color[self._environment.environment_code][entry_background]};'>{entry_type.type_name} - </span>" if status_type_entry else "") +
+						(f"<span style='color: #{entry_type.message_color[self._environment.environment_code][entry_background]};'>{message_text}</span></span>" if message_entry else "") +
 						(f"</i>" if italic else "") +
 						(f"</b>" if bold else "")
 				)
 			case LogEnvironments.PLAIN.environment_name:
 				return (
 					f"-?entry> {animation} " +
 					(f"*{datetime.datetime.now()} " if time_entry else "") +
-					f"{icon} " +
+					f"{entry_type.icon[icon_set]} " +
 					(f"#STATUS: " if status_entry else "") +
 					(f"{status_message_text} " if status_message_entry else "") +
-					(f"{message_type} - " if status_type_entry else "") +
+					(f"{entry_type.type_name} - " if status_type_entry else "") +
 					(f"{message_text}" if message_entry else "")
 				)
```

### Comparing `mighty_logger-0.7.0/mighty_logger/basic/exceptions.py` & `mighty_logger-0.7.1/mighty_logger/basic/exceptions.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.0/mighty_logger/basic/lib_types/__init__.py` & `mighty_logger-0.7.1/mighty_logger/basic/lib_types/__init__.py`

 * *Files 10% similar despite different names*

```diff
@@ -15,9 +15,10 @@
 See the License for the specific language governing permissions and
 limitations under the License.
 """
 
 from .animation_type import IndefiniteAnimationType, DefiniteAnimationType
 from .entry_type import EntryType
 from .environment_type import EnvironmentType
+from .sorting_key_type import SortingKeyType
 from .status_message_type import StatusMessageType
 from .text_buffer_type import TextBufferType
```

### Comparing `mighty_logger-0.7.0/mighty_logger/basic/lib_types/animation_type.py` & `mighty_logger-0.7.1/mighty_logger/basic/lib_types/animation_type.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.0/mighty_logger/basic/lib_types/entry_type.py` & `mighty_logger-0.7.1/mighty_logger/basic/lib_types/entry_type.py`

 * *Files 8% similar despite different names*

```diff
@@ -17,21 +17,21 @@
 """
 
 class EntryType:
 	def __init__(
 		self,
 		*,
 		type_name: str,
-		time_color: tuple,
-		status_color: tuple,
-		status_message_color: tuple,
-		type_color: tuple,
-		message_color: tuple,
-		background_color: tuple,
-		icon: tuple
+		time_color: tuple = (),
+		status_color: tuple = (),
+		status_message_color: tuple = (),
+		type_color: tuple = (),
+		message_color: tuple = (),
+		background_color: tuple = (),
+		icon: tuple = ()
 	) -> None:
 		self.__type_name: str = type_name
 		self.__time_color: tuple = time_color
 		self.__status_color: tuple = status_color
 		self.__status_message_color: tuple = status_message_color
 		self.__type_color: tuple = type_color
 		self.__message_color: tuple = message_color
```

### Comparing `mighty_logger-0.7.0/mighty_logger/basic/lib_types/environment_type.py` & `mighty_logger-0.7.1/mighty_logger/basic/lib_types/environment_type.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.0/mighty_logger/basic/lib_types/status_message_type.py` & `mighty_logger-0.7.1/mighty_logger/basic/lib_types/status_message_type.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.0/mighty_logger/basic/lib_types/text_buffer_type.py` & `mighty_logger-0.7.1/mighty_logger/basic/lib_types/text_buffer_type.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.0/mighty_logger/basic/patterns.py` & `mighty_logger-0.7.1/mighty_logger/basic/patterns.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.0/mighty_logger/powerful_logger.py` & `mighty_logger-0.7.1/mighty_logger/powerful_logger.py`

 * *Files 11% similar despite different names*

```diff
@@ -21,24 +21,30 @@
 from datetime import datetime
 
 from mighty_logger.basic.lib_types.animation_type import BasicAnimationType,\
 	IndefiniteAnimationType,\
 	DefiniteAnimationType
 from mighty_logger.basic.lib_types.entry_type import EntryType
 from mighty_logger.basic.lib_types.environment_type import EnvironmentType
+from mighty_logger.basic.lib_types.sorting_key_type import SortingKeyType
 from mighty_logger.basic.lib_types.status_message_type import StatusMessageType
 from mighty_logger.basic.lib_types.text_buffer_type import TextBufferType
 from mighty_logger.basic.basic_logger import BasicLogger
 from mighty_logger.basic.exceptions import ReCreationException, InitException
-from mighty_logger.src.animation import IndefiniteAnimations, DefiniteAnimations
-from mighty_logger.src.entry_types import ServiceLogger, LoggerEntryTypes, ServiceProcessEntryTypes, ServiceTimerEntryTypes
-from mighty_logger.src.environments import LogEnvironments
+from mighty_logger.basic.modifier import Modifier
+from mighty_logger.src.lib_types_collection.entry_types import ServiceLogger,\
+	LoggerEntryTypes,\
+	ServiceProcessEntryTypes,\
+	ServiceTimerEntryTypes
+from mighty_logger.src.lib_types_collection.environments import LogEnvironments
+from mighty_logger.src.lib_types_collection.sorting_keys import SortingKeys
+from mighty_logger.src.animations import IndefiniteAnimations, DefiniteAnimations
 from mighty_logger.src.text_buffer import BasicTextBuffer, TextBuffer
 
-class Logger(BasicLogger):
+class MightyLogger(BasicLogger):
 	"""
 	The Logger class is a class that implements the functionality
 	of logging the work of software in different directions.\n
 	It has a color output of information, settings for the operation of the log.
 	Only one class object can be created!!!\n
 	Implements the output of the following information:\n
 	1) Record creation time;
@@ -253,14 +259,68 @@
 			self._buffer.update_console()
 		data = self._buffer.input(input_text)
 		self._buffer.replace(-1, f"{input_text}{data}")
 		return data
 
 	# ######################################################################################## #
 	#                                                                                          #
+	#                                    Modifier of Logger                                    #
+	#                                                                                          #
+	# ######################################################################################## #
+
+	def sort(self, key: SortingKeyType) -> None:
+		sorter = Modifier(self._buffer.get_data().copy(), self._environment)
+		sorter.sort(key)
+		sorted_buffer = sorter.entries
+		self.clearly()
+		for entry in sorted_buffer:
+			self.empty(entry)
+
+	def sort_with_save(self, key: SortingKeyType) -> None:
+		original = self._buffer.get_data().copy()
+		sorter = Modifier(self._buffer.get_data(), self._environment)
+		sorter.sort(key)
+		self._buffer.save("sorted_logs", False)
+		self._buffer.get_data().clear()
+		self._buffer.get_data().extend(original)
+
+	def search(self, keyword: str, empty: bool = False) -> None:
+		searcher = Modifier(self._buffer.get_data().copy(), self._environment)
+		searcher.search(keyword, empty)
+		searched_buffer = searcher.entries
+		self.clearly()
+		for entry in searched_buffer:
+			self.empty(entry)
+
+	def search_with_save(self, keyword: str, empty: bool = False) -> None:
+		original = self._buffer.get_data().copy()
+		searcher = Modifier(self._buffer.get_data(), self._environment)
+		searcher.search(keyword, empty)
+		self._buffer.save("searched_logs", False)
+		self._buffer.get_data().clear()
+		self._buffer.get_data().extend(original)
+
+	def select(self, entry_type: EntryType) -> None:
+		selector = Modifier(self._buffer.get_data().copy(), self._environment)
+		selector.select(entry_type)
+		selected_buffer = selector.entries
+		self.clearly()
+		for entry in selected_buffer:
+			self.empty(entry)
+
+	def select_with_save(self, entry_type: EntryType) -> None:
+		original = self._buffer.get_data().copy()
+		selector = Modifier(self._buffer.get_data(), self._environment)
+		selector.select(entry_type)
+		self._buffer.save("selected_logs", False)
+		self._buffer.get_data().clear()
+		self._buffer.get_data().extend(original)
+
+	# ######################################################################################## #
+	#                                                                                          #
 	#                                    Entering to Logger                                    #
 	#                                                                                          #
 	# ######################################################################################## #
 
 	def entry(
 		self,
 		*,
@@ -280,27 +340,20 @@
 		:param local_settings: Dictionary of local entering settings
 		"""
 		if local_settings is None:
 			local_settings = {}
 		background = local_background if local_background is not None else self.global_background
 		self.empty(
 			self._assemble_entry(
-				[
-					entry_type.time_color[self._environment.environment_code][background],
-					entry_type.status_color[self._environment.environment_code][background],
-					entry_type.status_message_color[self._environment.environment_code][background],
-					entry_type.type_color[self._environment.environment_code][background],
-					entry_type.message_color[self._environment.environment_code][background],
-					entry_type.background_color[self._environment.environment_code][background]
-				],
+				entry_type,
+				self._icon_set,
 				self._progress_time,
-				entry_type.icon[self._icon_set],
 				status_message.current_status_message,
-				entry_type.type_name,
 				message_text,
+				background,
 				local_settings
 			)
 		)
 
 	# ######################################################################################## #
 	#                                                                                          #
 	#                                  Entering to Processes                                   #
@@ -376,27 +429,20 @@
 		self._buffer << "."
 		if self._environment.updatable:
 			self._buffer.update_console()
 		while not self._progress_interrupt:
 			animation_item = self._animation.animation[animation_index]
 			background = local_background if local_background is not None else self.global_background
 			self._buffer.get_data()[-1] = self._assemble_entry(
-				[
-					ServiceProcessEntryTypes.process.time_color[self._environment.environment_code][background],
-					ServiceProcessEntryTypes.process.status_color[self._environment.environment_code][background],
-					ServiceProcessEntryTypes.process.status_message_color[self._environment.environment_code][background],
-					ServiceProcessEntryTypes.process.type_color[self._environment.environment_code][background],
-					ServiceProcessEntryTypes.process.message_color[self._environment.environment_code][background],
-					ServiceProcessEntryTypes.process.background_color[self._environment.environment_code][background]
-				],
+				ServiceProcessEntryTypes.process,
+				self._icon_set,
 				animation_item,
-				ServiceProcessEntryTypes.process.icon[self._icon_set],
 				status_message.current_status_message,
-				ServiceProcessEntryTypes.process.type_name,
 				message_text,
+				background,
 				local_settings
 			)
 			animation_index = (animation_index + 1) % len(self._animation.animation)
 			if self._environment.updatable:
 				self._buffer.update_entry()
 			sleep(0.1)
 		if self._environment.updatable:
@@ -475,27 +521,20 @@
 			if old_progress_rise == self._progress_rise:
 				continue
 			else:
 				old_progress_rise = self._progress_rise
 				animation_item = f"{self._animation.animation[(self._progress_rise // 15) + (2 if self._progress_rise == 100 else 1)]} - {self._progress_rise} %"
 				background = local_background if local_background is not None else self.global_background
 				self._buffer.get_data()[-1] = self._assemble_entry(
-					[
-						ServiceProcessEntryTypes.process.time_color[self._environment.environment_code][background],
-						ServiceProcessEntryTypes.process.status_color[self._environment.environment_code][background],
-						ServiceProcessEntryTypes.process.status_message_color[self._environment.environment_code][background],
-						ServiceProcessEntryTypes.process.type_color[self._environment.environment_code][background],
-						ServiceProcessEntryTypes.process.message_color[self._environment.environment_code][background],
-						ServiceProcessEntryTypes.process.background_color[self._environment.environment_code][background]
-					],
+					ServiceProcessEntryTypes.process,
+					self._icon_set,
 					animation_item,
-					ServiceProcessEntryTypes.process.icon[self._icon_set],
 					status_message.current_status_message,
-					ServiceProcessEntryTypes.process.type_name,
 					message_text,
+					background,
 					local_settings
 				)
 				if self._environment.updatable:
 					self._buffer.update_entry()
 			sleep(0.1)
 		if self._environment.updatable:
 			self._buffer.update_console()
```

### Comparing `mighty_logger-0.7.0/mighty_logger/simple_logger.py` & `mighty_logger-0.7.1/mighty_logger/simple_logger.py`

 * *Files 12% similar despite different names*

```diff
@@ -13,59 +13,44 @@
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
 """
 
 from mighty_logger.basic.lib_types.environment_type import EnvironmentType
-from mighty_logger.src.entry_types import LoggerEntryTypes, ServiceProcessEntryTypes
-from mighty_logger.src.environments import LogEnvironments
-from mighty_logger import Logger
+from mighty_logger.src.lib_types_collection.entry_types import LoggerEntryTypes, ServiceProcessEntryTypes
+from mighty_logger.src.lib_types_collection.environments import LogEnvironments
+from mighty_logger.powerful_logger import MightyLogger
 
-class SimpleLogger:
+class Logger:
 	"""
 	...
 	"""
 
 	def __init__(
 		self,
 		program_name: str = "Unknown",
 		environment: EnvironmentType = LogEnvironments.PLAIN,
 		console_width: int = 60
 	):
-		if Logger._instance is not None:
-			self.__logger = Logger._instance
+		if MightyLogger._instance is not None:
+			self.__logger = MightyLogger._instance
 			self.notice("An existing logger was taken into use")
 		else:
-			self.__logger = Logger(
+			self.__logger = MightyLogger(
 				program_name=program_name,
 				log_environment=environment,
 				console_width=console_width,
 				status_global_entry=False,
 				status_message_global_entry=False
 			)
 
-	def get_logger(self) -> Logger:
+	def might(self) -> MightyLogger:
 		return self.__logger
 
-	def print(self, printing_text: str) -> None:
-		self.__logger.empty(entry=printing_text)
-
-	def input(self, printing_text: str) -> str:
-		return self.__logger.getty(printing_text)
-
-	def save(self, name_file: str, clean: bool = True) -> None:
-		self.__logger.savy(name_file, clean)
-
-	def load(self, name_file: str) -> None:
-		self.__logger.loady(name_file)
-
-	def separator(self) -> None:
-		self.__logger.separator()
-
 	def debug(self, message_text: str = "...") -> None:
 		"""
 		Debugging information logging:
 		Can be used to log entry any information while debugging an application.
 
 		:param message_text: Log entry message
 		"""
```

### Comparing `mighty_logger-0.7.0/mighty_logger/src/__init__.py` & `mighty_logger-0.7.1/mighty_logger/src/__init__.py`

 * *Files 12% similar despite different names*

```diff
@@ -12,22 +12,19 @@
 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
 """
 
-from .animation import IndefiniteAnimations, DefiniteAnimations
+from .animations import IndefiniteAnimations, DefiniteAnimations
 from .ansi_format import GetAnsiFormat
 from .color_picker import DecColor,\
 	HexColor,\
 	AnsiColor,\
 	Dec2Hex,\
 	Dec2Ansi,\
 	Hex2Dec,\
 	Hex2Ansi,\
 	Ansi2Dec,\
 	Ansi2Hex
-from .entry_types import LoggerEntryTypes, ProcessEntryTypes
-from .environments import LogEnvironments
-from .status_variables import StatusMessagePatterns
 from .text_buffer import BasicTextBuffer, TextBuffer
```

### Comparing `mighty_logger-0.7.0/mighty_logger/src/animation.py` & `mighty_logger-0.7.1/mighty_logger/src/animations.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.0/mighty_logger/src/ansi_format.py` & `mighty_logger-0.7.1/mighty_logger/src/ansi_format.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.0/mighty_logger/src/color_picker.py` & `mighty_logger-0.7.1/mighty_logger/src/color_picker.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.0/mighty_logger/src/entry_types.py` & `mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/entry_types.py`

 * *Files 7% similar despite different names*

```diff
@@ -84,15 +84,15 @@
 		icon=('🐛', '🐞', '🚧', '🔬')
 	)
 	"""
 	Debugging information logging:
 	Can be used to log entry any information while debugging an application.
 	"""
 	debug_performance = EntryType(
-		type_name="%DEBUG PERFORMANCE",
+		type_name="%DEBUG-PERFORMANCE",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			("", "")
 		),
@@ -1098,15 +1098,15 @@
 	"""
 	Fail information logging:
 	Used to log entry a message about the failed execution of the process.
 	"""
 
 class ServiceTimerEntryTypes:
 	start_timer = EntryType(
-		type_name="^START TIMER",
+		type_name="^START-TIMER",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('LAVENDERBLUSH', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			("", "")
 		),
@@ -1148,15 +1148,15 @@
 		icon=('⏰', '🕑', '🟩', '⏳')
 	)
 	"""
 	Information logging of starting Timer:
 	Used to notify the start of the Timer.
 	"""
 	timer_mark = EntryType(
-		type_name="^TIMER MARK",
+		type_name="^TIMER-MARK",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			("", "")
 		),
@@ -1198,15 +1198,15 @@
 		icon=('⌚', '🕕', '🟨', '⏱️')
 	)
 	"""
 	Information logging of mark Timer:
 	Used to notify the mark of the Timer.
 	"""
 	stop_timer = EntryType(
-		type_name="^STOP TIMER",
+		type_name="^STOP-TIMER",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('PURPLE', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('PURPLE')),
 			(HexColor('ORCHID'), HexColor('PURPLE')),
 			("", "")
 		),
@@ -1247,7 +1247,33 @@
 		),
 		icon=('⏲️', '🕙', '🟪', '⌛')
 	)
 	"""
 	Information logging of stopping Timer:
 	Used to notify the stop of the Timer.
 	"""
+
+class SelectionTypes:
+	debug = EntryType(type_name="%DEBUG")
+	debug_performance = EntryType(type_name="%DEBUG-PERFORMANCE")
+	performance = EntryType(type_name="%PERFORMANCE")
+	event = EntryType(type_name="~EVENT")
+	audit = EntryType(type_name="~AUDIT")
+	metrics = EntryType(type_name="~METRICS")
+	user = EntryType(type_name="~USER")
+	message = EntryType(type_name="@MESSAGE")
+	info = EntryType(type_name="@INFO")
+	notice = EntryType(type_name="@NOTICE")
+	warning = EntryType(type_name="!WARNING")
+	error = EntryType(type_name="!!ERROR")
+	critical = EntryType(type_name="!!!@CRITICAL")
+	resolved = EntryType(type_name="!RESOLVED")
+	unresolved = EntryType(type_name="!UNRESOLVED")
+	achievement = EntryType(type_name="&ACHIEVEMENT")
+	milestone = EntryType(type_name="&MILESTONE")
+	initiation = EntryType(type_name="&INITIATION")
+	process = EntryType(type_name="&PROGRESS")
+	success = EntryType(type_name="&SUCCESS")
+	fail = EntryType(type_name="&FAIL")
+	start_timer = EntryType(type_name="^START-TIMER")
+	timer_mark = EntryType(type_name="^TIMER-MARK")
+	stop_timer = EntryType(type_name="^STOP-TIMER")
```

### Comparing `mighty_logger-0.7.0/mighty_logger/src/environments.py` & `mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/environments.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.0/mighty_logger/src/status_variables.py` & `mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/status_variables.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.0/mighty_logger/src/text_buffer.py` & `mighty_logger-0.7.1/mighty_logger/src/text_buffer.py`

 * *Files 0% similar despite different names*

```diff
@@ -18,15 +18,15 @@
 
 import sys, re
 
 from mighty_logger.basic.lib_types.environment_type import EnvironmentType
 from mighty_logger.basic.lib_types.text_buffer_type import TextBufferType
 from mighty_logger.basic.exceptions import ReCreationException, EnvironmentException
 from mighty_logger.basic.patterns import Singleton
-from mighty_logger.src.environments import LogEnvironments
+from mighty_logger.src.lib_types_collection.environments import LogEnvironments
 
 class BasicTextBuffer(Singleton, TextBufferType):
 	"""
 	A class with a basic implementation of a simple text buffer. It is intended
 	to be used in conjunction with HTML, but this is optional.
 	"""
```

### Comparing `mighty_logger-0.7.0/mighty_logger.egg-info/PKG-INFO` & `mighty_logger-0.7.1/mighty_logger.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mighty-logger
-Version: 0.7.0
+Version: 0.7.1
 Summary: Powerful functional logger
 Home-page: https://github.com/Nakama3942/mighty_logger
 Author: Kalynovsky 'Nakamura Akira' Valentin
 Author-email: nakama3942@gmail.com
 License: Apache License, Version 2.0, see LICENSE file
 Project-URL: Releases, https://github.com/Nakama3942/mighty_logger/releases
 Classifier: Development Status :: 3 - Alpha
@@ -104,15 +104,15 @@
 - [x] v0.3.0 - Background update (added background for log entries)
 - [x] v0.4.0 - Buffer update (added text buffer)
 - [x] v0.5.0 - Unifying update (console and HTML are combined into one class)
 - [x] v0.5.1 - Hints update (added status message templates and hint symbols (icons) near log entries status)
 - [x] v0.6.0 - Progress update (added start of some log entries in threads (process))
 - [x] v0.6.1 - Animation update (added animations in processes)
 - [x] v0.7.0 - "Buffer improvement" update (buffer development completed and entry type system reworked)
-- [ ] v0.7.1 - Search update (added search by log entry types)
+- [x] v0.7.1 - Modding update (buffer modification added - sorting, searching and selecting)
 - [ ] v0.8.0 - Export update (added conversion to different types, such as csv, pdf, etc.)
 - [ ] v0.9.0 - Extension update (made wheel format and instruction of toml)
 - [ ] v0.9.1 - Documenting update (all updates since v0.7.0 are documented; updated old documentation; documentation site generation added)
 - [ ] v1.0.0 - Completion of logger development (logger development completed)
 - [ ] v1.1.0 - Font update (added a class that formats text outside the logger)
 
 </details>
```

### Comparing `mighty_logger-0.7.0/mighty_logger.egg-info/SOURCES.txt` & `mighty_logger-0.7.1/mighty_logger.egg-info/SOURCES.txt`

 * *Files 24% similar despite different names*

```diff
@@ -8,24 +8,28 @@
 mighty_logger.egg-info/PKG-INFO
 mighty_logger.egg-info/SOURCES.txt
 mighty_logger.egg-info/dependency_links.txt
 mighty_logger.egg-info/top_level.txt
 mighty_logger/basic/__init__.py
 mighty_logger/basic/basic_logger.py
 mighty_logger/basic/exceptions.py
+mighty_logger/basic/modifier.py
 mighty_logger/basic/patterns.py
 mighty_logger/basic/lib_types/__init__.py
 mighty_logger/basic/lib_types/animation_type.py
 mighty_logger/basic/lib_types/entry_type.py
 mighty_logger/basic/lib_types/environment_type.py
+mighty_logger/basic/lib_types/sorting_key_type.py
 mighty_logger/basic/lib_types/status_message_type.py
 mighty_logger/basic/lib_types/text_buffer_type.py
 mighty_logger/src/__init__.py
-mighty_logger/src/animation.py
+mighty_logger/src/animations.py
 mighty_logger/src/ansi_format.py
 mighty_logger/src/color_picker.py
-mighty_logger/src/entry_types.py
-mighty_logger/src/environments.py
-mighty_logger/src/status_variables.py
 mighty_logger/src/text_buffer.py
+mighty_logger/src/lib_types_collection/__init__.py
+mighty_logger/src/lib_types_collection/entry_types.py
+mighty_logger/src/lib_types_collection/environments.py
+mighty_logger/src/lib_types_collection/sorting_keys.py
+mighty_logger/src/lib_types_collection/status_variables.py
 test/test.py
 test/test_simple.py
```

### Comparing `mighty_logger-0.7.0/setup.py` & `mighty_logger-0.7.1/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -19,15 +19,15 @@
 from setuptools import setup
 
 with open("README.md", "r", encoding='utf-8') as readme_file:
     readme = readme_file.read()
 
 setup(
     name="mighty_logger",
-    version="0.7.0",
+    version="0.7.1",
 
     author="Kalynovsky 'Nakamura Akira' Valentin",
     author_email="nakama3942@gmail.com",
 
     description="Powerful functional logger",
     long_description=readme,
     long_description_content_type="text/markdown",
@@ -35,14 +35,15 @@
     url="https://github.com/Nakama3942/mighty_logger",
 
     license="Apache License, Version 2.0, see LICENSE file",
 
     packages=[
         'mighty_logger',
         'mighty_logger.src',
+        'mighty_logger.src.lib_types_collection',
         'mighty_logger.basic',
         'mighty_logger.basic.lib_types'
     ],
     classifiers=[
         "Development Status :: 3 - Alpha",
         "Intended Audience :: Developers",
         "License :: OSI Approved :: Apache Software License",
```

### Comparing `mighty_logger-0.7.0/test/test.py` & `mighty_logger-0.7.1/test/test.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,14 +1,19 @@
 from time import sleep
 
-from mighty_logger import Logger
-from mighty_logger.src import LoggerEntryTypes, ProcessEntryTypes, LogEnvironments, IndefiniteAnimations, DefiniteAnimations
+from mighty_logger import MightyLogger
+from mighty_logger.src.lib_types_collection import LoggerEntryTypes,\
+	ProcessEntryTypes,\
+	LogEnvironments,\
+	SortingKeys,\
+	SelectionTypes
+from mighty_logger.src import IndefiniteAnimations, DefiniteAnimations
 
 if __name__ == "__main__":
-	logger = Logger(program_name="Installer", log_environment=LogEnvironments.CONSOLE, console_width=115, status_message_global_entry=False)
+	logger = MightyLogger(program_name="Installer", log_environment=LogEnvironments.CONSOLE, console_width=115, status_message_global_entry=False)
 	logger.publish_author()
 
 	logger.start_timer(message_text="Timer started")
 	logger.entry(entry_type=LoggerEntryTypes.message, message_text="Program installation started")
 
 	sleep(1)
 	logger.start_indefinite_process(animation=IndefiniteAnimations.SuperSpace, message_text="File upload")
@@ -82,8 +87,16 @@
 	logger.progress_rise(100)
 	sleep(1.3)
 	logger.stop_process(message_text="Program installed")
 
 	logger.stop_timer(message_text="Timer completed")
 	logger.empty(entry=data)
 
-	logger.savy("log", False)
+	# logger.savy("log", False)
+
+	logger.sort(SortingKeys.SORT_ON_TYPE)
+	# logger.sort_with_save(SortingKeys.SORT_ON_TYPE)
+	# logger.search("o", True)
+	# logger.search_with_save("o", True)
+	# logger.select(SelectionTypes.initiation)
+	# logger.select_with_save(SelectionTypes.initiation)
+	logger.entry(entry_type=LoggerEntryTypes.info, message_text="Logger sorted")
```

### Comparing `mighty_logger-0.7.0/test/test_simple.py` & `mighty_logger-0.7.1/test/test_simple.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,35 +1,36 @@
 from time import sleep
 
-from mighty_logger import SimpleLogger
-from mighty_logger.src import LogEnvironments
+from mighty_logger import Logger
+from mighty_logger.src.lib_types_collection import LogEnvironments
 
 if __name__ == "__main__":
-	logger = SimpleLogger("Installer", LogEnvironments.PLAIN, 115)
+	logger = Logger("Installer", LogEnvironments.CONSOLE, 115)
 	sleep(1)
 	logger.message("Program installation started")
 	sleep(1)
 	logger.warning("Newer version found")
 	sleep(1)
-	logger.separator()
+	logger.might().separator()
 	sleep(1)
-	data = logger.input("Enter password: ")
+	data = logger.might().getty("Enter password: ")
 	sleep(1)
 	logger.error("Incompatibility found")
 	sleep(1)
 	logger.fail("Program not installed")
 	sleep(1)
-	logger.print(data)
+	logger.might().empty(data)
 	sleep(1)
-	logger.save("log", True)
+	logger.might().savy("log", False)
 	sleep(1)
 	logger.debug("la la la")
 	sleep(1)
-	logger.load("log")
+	logger.might().loady("log")
 	sleep(1)
 	logger.debug("bla bla bla")
 	sleep(1)
-	logger.get_logger().extractly(2)
+	logger.might().extractly(2)
 	sleep(1)
 	logger.debug("String has deleted")
 	sleep(1)
-	logger.print(logger.get_logger().catchy(1))
+	logger.might().empty(logger.might().catchy(1))
+	logger.might().savy("log", False)
```


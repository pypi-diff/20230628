# Comparing `tmp/mighty_logger-0.7.1.tar.gz` & `tmp/mighty_logger-0.7.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mighty_logger-0.7.1.tar", last modified: Wed Jun 28 10:18:30 2023, max compression
+gzip compressed data, was "mighty_logger-0.7.2.tar", last modified: Wed Jun 28 12:24:10 2023, max compression
```

## Comparing `mighty_logger-0.7.1.tar` & `mighty_logger-0.7.2.tar`

### file list

```diff
@@ -1,44 +1,44 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.974367 mighty_logger-0.7.1/
--rw-rw-rw-   0        0        0    11357 2023-04-10 16:24:05.000000 mighty_logger-0.7.1/LICENSE
--rw-rw-rw-   0        0        0    10813 2023-06-28 10:18:30.975366 mighty_logger-0.7.1/PKG-INFO
--rw-rw-rw-   0        0        0     9871 2023-06-27 18:52:45.000000 mighty_logger-0.7.1/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.896680 mighty_logger-0.7.1/mighty_logger/
--rw-rw-rw-   0        0        0      863 2023-06-27 18:40:32.000000 mighty_logger-0.7.1/mighty_logger/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.909681 mighty_logger-0.7.1/mighty_logger/basic/
--rw-rw-rw-   0        0        0      789 2023-06-26 10:51:25.000000 mighty_logger-0.7.1/mighty_logger/basic/__init__.py
--rw-rw-rw-   0        0        0     9979 2023-06-28 09:48:23.000000 mighty_logger-0.7.1/mighty_logger/basic/basic_logger.py
--rw-rw-rw-   0        0        0     1499 2023-06-26 10:49:56.000000 mighty_logger-0.7.1/mighty_logger/basic/exceptions.py
-drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.943501 mighty_logger-0.7.1/mighty_logger/basic/lib_types/
--rw-rw-rw-   0        0        0      921 2023-06-27 12:43:22.000000 mighty_logger-0.7.1/mighty_logger/basic/lib_types/__init__.py
--rw-rw-rw-   0        0        0     1086 2023-06-25 13:07:43.000000 mighty_logger-0.7.1/mighty_logger/basic/lib_types/animation_type.py
--rw-rw-rw-   0        0        0     1883 2023-06-27 18:12:22.000000 mighty_logger-0.7.1/mighty_logger/basic/lib_types/entry_type.py
--rw-rw-rw-   0        0        0     1297 2023-06-26 11:32:43.000000 mighty_logger-0.7.1/mighty_logger/basic/lib_types/environment_type.py
--rw-rw-rw-   0        0        0      798 2023-06-27 12:43:22.000000 mighty_logger-0.7.1/mighty_logger/basic/lib_types/sorting_key_type.py
--rw-rw-rw-   0        0        0      874 2023-06-25 13:06:36.000000 mighty_logger-0.7.1/mighty_logger/basic/lib_types/status_message_type.py
--rw-rw-rw-   0        0        0     4317 2023-06-26 11:33:46.000000 mighty_logger-0.7.1/mighty_logger/basic/lib_types/text_buffer_type.py
--rw-rw-rw-   0        0        0     6862 2023-06-28 09:48:23.000000 mighty_logger-0.7.1/mighty_logger/basic/modifier.py
--rw-rw-rw-   0        0        0      823 2023-04-11 10:58:04.000000 mighty_logger-0.7.1/mighty_logger/basic/patterns.py
--rw-rw-rw-   0        0        0    28476 2023-06-28 09:48:23.000000 mighty_logger-0.7.1/mighty_logger/powerful_logger.py
--rw-rw-rw-   0        0        0     6701 2023-06-28 09:53:14.000000 mighty_logger-0.7.1/mighty_logger/simple_logger.py
-drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.966690 mighty_logger-0.7.1/mighty_logger/src/
--rw-rw-rw-   0        0        0      956 2023-06-28 09:48:23.000000 mighty_logger-0.7.1/mighty_logger/src/__init__.py
--rw-rw-rw-   0        0        0     9975 2023-06-25 13:20:13.000000 mighty_logger-0.7.1/mighty_logger/src/animations.py
--rw-rw-rw-   0        0        0     4572 2023-06-11 16:58:31.000000 mighty_logger-0.7.1/mighty_logger/src/ansi_format.py
--rw-rw-rw-   0        0        0     8659 2023-06-11 16:58:31.000000 mighty_logger-0.7.1/mighty_logger/src/color_picker.py
-drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.971752 mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/
--rw-rw-rw-   0        0        0      810 2023-06-28 09:48:23.000000 mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/__init__.py
--rw-rw-rw-   0        0        0    39613 2023-06-27 18:12:22.000000 mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/entry_types.py
--rw-rw-rw-   0        0        0     1140 2023-06-25 13:20:13.000000 mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/environments.py
--rw-rw-rw-   0        0        0      873 2023-06-27 12:43:22.000000 mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/sorting_keys.py
--rw-rw-rw-   0        0        0     5473 2023-06-25 13:20:13.000000 mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/status_variables.py
--rw-rw-rw-   0        0        0    10808 2023-06-28 09:48:23.000000 mighty_logger-0.7.1/mighty_logger/src/text_buffer.py
-drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.900681 mighty_logger-0.7.1/mighty_logger.egg-info/
--rw-rw-rw-   0        0        0    10813 2023-06-28 10:18:30.000000 mighty_logger-0.7.1/mighty_logger.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     1246 2023-06-28 10:18:30.000000 mighty_logger-0.7.1/mighty_logger.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 10:18:30.000000 mighty_logger-0.7.1/mighty_logger.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       14 2023-06-28 10:18:30.000000 mighty_logger-0.7.1/mighty_logger.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 10:18:30.975366 mighty_logger-0.7.1/setup.cfg
--rw-rw-rw-   0        0        0     1757 2023-06-28 09:49:41.000000 mighty_logger-0.7.1/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 10:18:30.974367 mighty_logger-0.7.1/test/
--rw-rw-rw-   0        0        0     3073 2023-06-28 09:53:14.000000 mighty_logger-0.7.1/test/test.py
--rw-rw-rw-   0        0        0      924 2023-06-28 09:53:14.000000 mighty_logger-0.7.1/test/test_simple.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:24:10.597877 mighty_logger-0.7.2/
+-rw-rw-rw-   0        0        0    11357 2023-04-10 16:24:05.000000 mighty_logger-0.7.2/LICENSE
+-rw-rw-rw-   0        0        0    10892 2023-06-28 12:24:10.597877 mighty_logger-0.7.2/PKG-INFO
+-rw-rw-rw-   0        0        0     9949 2023-06-28 11:14:28.000000 mighty_logger-0.7.2/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 12:24:10.459263 mighty_logger-0.7.2/mighty_logger/
+-rw-rw-rw-   0        0        0      861 2023-06-28 11:14:28.000000 mighty_logger-0.7.2/mighty_logger/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:24:10.507455 mighty_logger-0.7.2/mighty_logger/basic/
+-rw-rw-rw-   0        0        0      789 2023-06-26 10:51:25.000000 mighty_logger-0.7.2/mighty_logger/basic/__init__.py
+-rw-rw-rw-   0        0        0    10109 2023-06-28 10:45:25.000000 mighty_logger-0.7.2/mighty_logger/basic/basic_logger.py
+-rw-rw-rw-   0        0        0     1499 2023-06-26 10:49:56.000000 mighty_logger-0.7.2/mighty_logger/basic/exceptions.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:24:10.541187 mighty_logger-0.7.2/mighty_logger/basic/lib_types/
+-rw-rw-rw-   0        0        0      921 2023-06-27 12:43:22.000000 mighty_logger-0.7.2/mighty_logger/basic/lib_types/__init__.py
+-rw-rw-rw-   0        0        0     1086 2023-06-25 13:07:43.000000 mighty_logger-0.7.2/mighty_logger/basic/lib_types/animation_type.py
+-rw-rw-rw-   0        0        0     2030 2023-06-28 10:45:25.000000 mighty_logger-0.7.2/mighty_logger/basic/lib_types/entry_type.py
+-rw-rw-rw-   0        0        0     1297 2023-06-26 11:32:43.000000 mighty_logger-0.7.2/mighty_logger/basic/lib_types/environment_type.py
+-rw-rw-rw-   0        0        0      798 2023-06-27 12:43:22.000000 mighty_logger-0.7.2/mighty_logger/basic/lib_types/sorting_key_type.py
+-rw-rw-rw-   0        0        0      874 2023-06-25 13:06:36.000000 mighty_logger-0.7.2/mighty_logger/basic/lib_types/status_message_type.py
+-rw-rw-rw-   0        0        0     4317 2023-06-26 11:33:46.000000 mighty_logger-0.7.2/mighty_logger/basic/lib_types/text_buffer_type.py
+-rw-rw-rw-   0        0        0     7087 2023-06-28 10:57:00.000000 mighty_logger-0.7.2/mighty_logger/basic/modifier.py
+-rw-rw-rw-   0        0        0      823 2023-04-11 10:58:04.000000 mighty_logger-0.7.2/mighty_logger/basic/patterns.py
+-rw-rw-rw-   0        0        0    28476 2023-06-28 09:48:23.000000 mighty_logger-0.7.2/mighty_logger/mighty_logger.py
+-rw-rw-rw-   0        0        0     6699 2023-06-28 11:14:28.000000 mighty_logger-0.7.2/mighty_logger/simple_logger.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:24:10.565611 mighty_logger-0.7.2/mighty_logger/src/
+-rw-rw-rw-   0        0        0      956 2023-06-28 09:48:23.000000 mighty_logger-0.7.2/mighty_logger/src/__init__.py
+-rw-rw-rw-   0        0        0     9975 2023-06-25 13:20:13.000000 mighty_logger-0.7.2/mighty_logger/src/animations.py
+-rw-rw-rw-   0        0        0     4572 2023-06-11 16:58:31.000000 mighty_logger-0.7.2/mighty_logger/src/ansi_format.py
+-rw-rw-rw-   0        0        0     8659 2023-06-11 16:58:31.000000 mighty_logger-0.7.2/mighty_logger/src/color_picker.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:24:10.593877 mighty_logger-0.7.2/mighty_logger/src/lib_types_collection/
+-rw-rw-rw-   0        0        0      831 2023-06-28 10:57:00.000000 mighty_logger-0.7.2/mighty_logger/src/lib_types_collection/__init__.py
+-rw-rw-rw-   0        0        0    40877 2023-06-28 11:04:00.000000 mighty_logger-0.7.2/mighty_logger/src/lib_types_collection/entry_types.py
+-rw-rw-rw-   0        0        0     1140 2023-06-25 13:20:13.000000 mighty_logger-0.7.2/mighty_logger/src/lib_types_collection/environments.py
+-rw-rw-rw-   0        0        0      873 2023-06-27 12:43:22.000000 mighty_logger-0.7.2/mighty_logger/src/lib_types_collection/sorting_keys.py
+-rw-rw-rw-   0        0        0     5473 2023-06-25 13:20:13.000000 mighty_logger-0.7.2/mighty_logger/src/lib_types_collection/status_variables.py
+-rw-rw-rw-   0        0        0    10808 2023-06-28 09:48:23.000000 mighty_logger-0.7.2/mighty_logger/src/text_buffer.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:24:10.478883 mighty_logger-0.7.2/mighty_logger.egg-info/
+-rw-rw-rw-   0        0        0    10892 2023-06-28 12:24:10.000000 mighty_logger-0.7.2/mighty_logger.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     1244 2023-06-28 12:24:10.000000 mighty_logger-0.7.2/mighty_logger.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 12:24:10.000000 mighty_logger-0.7.2/mighty_logger.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       14 2023-06-28 12:24:10.000000 mighty_logger-0.7.2/mighty_logger.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 12:24:10.598876 mighty_logger-0.7.2/setup.cfg
+-rw-rw-rw-   0        0        0     1757 2023-06-28 11:14:28.000000 mighty_logger-0.7.2/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:24:10.596879 mighty_logger-0.7.2/test/
+-rw-rw-rw-   0        0        0     3073 2023-06-28 11:06:47.000000 mighty_logger-0.7.2/test/test.py
+-rw-rw-rw-   0        0        0      924 2023-06-28 09:53:14.000000 mighty_logger-0.7.2/test/test_simple.py
```

### Comparing `mighty_logger-0.7.1/LICENSE` & `mighty_logger-0.7.2/LICENSE`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/PKG-INFO` & `mighty_logger-0.7.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mighty_logger
-Version: 0.7.1
+Version: 0.7.2
 Summary: Powerful functional logger
 Home-page: https://github.com/Nakama3942/mighty_logger
 Author: Kalynovsky 'Nakamura Akira' Valentin
 Author-email: nakama3942@gmail.com
 License: Apache License, Version 2.0, see LICENSE file
 Project-URL: Releases, https://github.com/Nakama3942/mighty_logger/releases
 Classifier: Development Status :: 3 - Alpha
@@ -105,14 +105,15 @@
 - [x] v0.4.0 - Buffer update (added text buffer)
 - [x] v0.5.0 - Unifying update (console and HTML are combined into one class)
 - [x] v0.5.1 - Hints update (added status message templates and hint symbols (icons) near log entries status)
 - [x] v0.6.0 - Progress update (added start of some log entries in threads (process))
 - [x] v0.6.1 - Animation update (added animations in processes)
 - [x] v0.7.0 - "Buffer improvement" update (buffer development completed and entry type system reworked)
 - [x] v0.7.1 - Modding update (buffer modification added - sorting, searching and selecting)
+- [x] v0.7.2 - Categories update (separated the entry category from the type)
 - [ ] v0.8.0 - Export update (added conversion to different types, such as csv, pdf, etc.)
 - [ ] v0.9.0 - Extension update (made wheel format and instruction of toml)
 - [ ] v0.9.1 - Documenting update (all updates since v0.7.0 are documented; updated old documentation; documentation site generation added)
 - [ ] v1.0.0 - Completion of logger development (logger development completed)
 - [ ] v1.1.0 - Font update (added a class that formats text outside the logger)
 
 </details>
```

### Comparing `mighty_logger-0.7.1/README.md` & `mighty_logger-0.7.2/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -86,14 +86,15 @@
 - [x] v0.4.0 - Buffer update (added text buffer)
 - [x] v0.5.0 - Unifying update (console and HTML are combined into one class)
 - [x] v0.5.1 - Hints update (added status message templates and hint symbols (icons) near log entries status)
 - [x] v0.6.0 - Progress update (added start of some log entries in threads (process))
 - [x] v0.6.1 - Animation update (added animations in processes)
 - [x] v0.7.0 - "Buffer improvement" update (buffer development completed and entry type system reworked)
 - [x] v0.7.1 - Modding update (buffer modification added - sorting, searching and selecting)
+- [x] v0.7.2 - Categories update (separated the entry category from the type)
 - [ ] v0.8.0 - Export update (added conversion to different types, such as csv, pdf, etc.)
 - [ ] v0.9.0 - Extension update (made wheel format and instruction of toml)
 - [ ] v0.9.1 - Documenting update (all updates since v0.7.0 are documented; updated old documentation; documentation site generation added)
 - [ ] v1.0.0 - Completion of logger development (logger development completed)
 - [ ] v1.1.0 - Font update (added a class that formats text outside the logger)
 
 </details>
```

### Comparing `mighty_logger-0.7.1/mighty_logger/__init__.py` & `mighty_logger-0.7.2/mighty_logger/__init__.py`

 * *Files 3% similar despite different names*

```diff
@@ -12,13 +12,13 @@
 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
 """
 
-from .powerful_logger import MightyLogger
+from .mighty_logger import MightyLogger
 from .simple_logger import Logger
 
 __authot__ = "Kalynovsky 'Nakamura Akira' Valentin"
-__version__ = "0.7.1"
+__version__ = "0.7.2"
 __email__ = "nakama3942@gmail.com"
```

### Comparing `mighty_logger-0.7.1/mighty_logger/basic/__init__.py` & `mighty_logger-0.7.2/mighty_logger/basic/__init__.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/basic/basic_logger.py` & `mighty_logger-0.7.2/mighty_logger/basic/basic_logger.py`

 * *Files 3% similar despite different names*

```diff
@@ -138,61 +138,61 @@
 					(f"{GetAnsiFormat('invert/on')}" if invert else "") +
 					f"{entry_type.background_color[self._environment.environment_code][entry_background]}" +
 					f"{entry_type.message_color[self._environment.environment_code][entry_background]}-?entry> {animation} " +
 					(f"{entry_type.time_color[self._environment.environment_code][entry_background]}*{datetime.datetime.now()} " if time_entry else "") +
 					f"{entry_type.icon[icon_set]} " +
 					(f"{entry_type.status_color[self._environment.environment_code][entry_background]}#STATUS: " if status_entry else "") +
 					(f"{entry_type.status_message_color[self._environment.environment_code][entry_background]}{status_message_text} " if status_message_entry else "") +
-					(f"{entry_type.type_color[self._environment.environment_code][entry_background]}{entry_type.type_name} - " if status_type_entry else "") +
+					(f"{entry_type.type_color[self._environment.environment_code][entry_background]}{entry_type.type_category}{entry_type.type_name} - " if status_type_entry else "") +
 					(f"{entry_type.message_color[self._environment.environment_code][entry_background]}{message_text}" if message_entry else "") +
 					f"{GetAnsiFormat('reset/on')}"
 				)
 			case LogEnvironments.PLAIN_CONSOLE.environment_name:
 				return (
 					f"-?entry> {animation} " +
 					(f"*{datetime.datetime.now()} " if time_entry else "") +
 					f"{entry_type.icon[icon_set]} " +
 					(f"#STATUS: " if status_entry else "") +
 					(f"{status_message_text} " if status_message_entry else "") +
-					(f"{entry_type.type_name} - " if status_type_entry else "") +
+					(f"{entry_type.type_category}{entry_type.type_name} - " if status_type_entry else "") +
 					(f"{message_text}" if message_entry else "")
 				)
 			case LogEnvironments.HTML.environment_name:
 				return (
 					(f"<b>" if bold else "") +
 					(f"<i>" if italic else "") +
 					f"<span style='background-color: #{entry_type.background_color[self._environment.environment_code][entry_background]};'>" +
 					f"<span style='color: #{entry_type.message_color[self._environment.environment_code][entry_background]};'>-?entry> {animation} </span>" +
 					(f"<span style='color: #{entry_type.time_color[self._environment.environment_code][entry_background]};'>*{datetime.datetime.now()} </span>" if time_entry else "") +
 					f"{entry_type.icon[icon_set]} " +
 					(f"<span style='color: #{entry_type.status_color[self._environment.environment_code][entry_background]};'>#STATUS: </span>" if status_entry else "") +
 					(f"<span style='color: #{entry_type.status_message_color[self._environment.environment_code][entry_background]};'>{status_message_text} </span>" if status_message_entry else "") +
-					(f"<span style='color: #{entry_type.type_color[self._environment.environment_code][entry_background]};'>{entry_type.type_name} - </span>" if status_type_entry else "") +
+					(f"<span style='color: #{entry_type.type_color[self._environment.environment_code][entry_background]};'>{entry_type.type_category}{entry_type.type_name} - </span>" if status_type_entry else "") +
 					(f"<span style='color: #{entry_type.message_color[self._environment.environment_code][entry_background]};'>{message_text}</span></span>" if message_entry else "") +
 					(f"</i>" if italic else "") +
 					(f"</b>" if bold else "")
 				)
 			case LogEnvironments.MARKDOWN.environment_name:
 				return (
 						(f"<b>" if bold else "") +
 						(f"<i>" if italic else "") +
 						f"<span style='background-color: #{entry_type.background_color[self._environment.environment_code][entry_background]};'>" +
 						f"<span style='color: #{entry_type.message_color[self._environment.environment_code][entry_background]};'>-?entry> {animation} </span>" +
 						(f"<span style='color: #{entry_type.time_color[self._environment.environment_code][entry_background]};'>*{datetime.datetime.now()} </span>" if time_entry else "") +
 						f"{entry_type.icon[icon_set]} " +
 						(f"<span style='color: #{entry_type.status_color[self._environment.environment_code][entry_background]};'>#STATUS: </span>" if status_entry else "") +
 						(f"<span style='color: #{entry_type.status_message_color[self._environment.environment_code][entry_background]};'>{status_message_text} </span>" if status_message_entry else "") +
-						(f"<span style='color: #{entry_type.type_color[self._environment.environment_code][entry_background]};'>{entry_type.type_name} - </span>" if status_type_entry else "") +
+						(f"<span style='color: #{entry_type.type_color[self._environment.environment_code][entry_background]};'>{entry_type.type_category}{entry_type.type_name} - </span>" if status_type_entry else "") +
 						(f"<span style='color: #{entry_type.message_color[self._environment.environment_code][entry_background]};'>{message_text}</span></span>" if message_entry else "") +
 						(f"</i>" if italic else "") +
 						(f"</b>" if bold else "")
 				)
 			case LogEnvironments.PLAIN.environment_name:
 				return (
 					f"-?entry> {animation} " +
 					(f"*{datetime.datetime.now()} " if time_entry else "") +
 					f"{entry_type.icon[icon_set]} " +
 					(f"#STATUS: " if status_entry else "") +
 					(f"{status_message_text} " if status_message_entry else "") +
-					(f"{entry_type.type_name} - " if status_type_entry else "") +
+					(f"{entry_type.type_category}{entry_type.type_name} - " if status_type_entry else "") +
 					(f"{message_text}" if message_entry else "")
 				)
```

### Comparing `mighty_logger-0.7.1/mighty_logger/basic/exceptions.py` & `mighty_logger-0.7.2/mighty_logger/basic/exceptions.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/basic/lib_types/__init__.py` & `mighty_logger-0.7.2/mighty_logger/basic/lib_types/__init__.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/basic/lib_types/animation_type.py` & `mighty_logger-0.7.2/mighty_logger/basic/lib_types/animation_type.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/basic/lib_types/entry_type.py` & `mighty_logger-0.7.2/mighty_logger/basic/lib_types/entry_type.py`

 * *Files 9% similar despite different names*

```diff
@@ -16,33 +16,39 @@
 limitations under the License.
 """
 
 class EntryType:
 	def __init__(
 		self,
 		*,
+		type_category: str,
 		type_name: str,
 		time_color: tuple = (),
 		status_color: tuple = (),
 		status_message_color: tuple = (),
 		type_color: tuple = (),
 		message_color: tuple = (),
 		background_color: tuple = (),
 		icon: tuple = ()
 	) -> None:
+		self.__type_category: str = type_category
 		self.__type_name: str = type_name
 		self.__time_color: tuple = time_color
 		self.__status_color: tuple = status_color
 		self.__status_message_color: tuple = status_message_color
 		self.__type_color: tuple = type_color
 		self.__message_color: tuple = message_color
 		self.__background_color: tuple = background_color
 		self.__icon: tuple = icon
 
 	@property
+	def type_category(self) -> str:
+		return self.__type_category
+
+	@property
 	def type_name(self) -> str:
 		return self.__type_name
 
 	@property
 	def time_color(self) -> tuple:
 		return self.__time_color
```

### Comparing `mighty_logger-0.7.1/mighty_logger/basic/lib_types/environment_type.py` & `mighty_logger-0.7.2/mighty_logger/basic/lib_types/environment_type.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/basic/lib_types/sorting_key_type.py` & `mighty_logger-0.7.2/mighty_logger/basic/lib_types/sorting_key_type.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/basic/lib_types/status_message_type.py` & `mighty_logger-0.7.2/mighty_logger/basic/lib_types/status_message_type.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/basic/lib_types/text_buffer_type.py` & `mighty_logger-0.7.2/mighty_logger/basic/lib_types/text_buffer_type.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/basic/modifier.py` & `mighty_logger-0.7.2/mighty_logger/basic/modifier.py`

 * *Files 3% similar despite different names*

```diff
@@ -176,16 +176,21 @@
 					cleared_entry = re.sub(r"<.*?>", "", entry)
 				case LogEnvironments.MARKDOWN.environment_name:
 					cleared_entry = re.sub(r"<.*?>", "", entry)
 				case LogEnvironments.PLAIN.environment_name:
 					cleared_entry = entry
 			if cleared_entry.startswith("-?"):
 				parts = cleared_entry.split("*")[1].split()
-				if parts[4] == entry_type.type_name:
-					selected_entries.append(self.__entries.pop(index + 1 - len(selected_entries) - count_excess))
-					continue
+				if entry_type.type_category == "":
+					if parts[4][1:] == entry_type.type_name:
+						selected_entries.append(self.__entries.pop(index + 1 - len(selected_entries) - count_excess))
+						continue
+				else:
+					if parts[4][0] == entry_type.type_category:
+						selected_entries.append(self.__entries.pop(index + 1 - len(selected_entries) - count_excess))
+						continue
 			self.__entries.pop(index + 1 - len(selected_entries) - count_excess)
 			count_excess += 1
 
 		self.__entries.append("--------------------------------Selected entries--------------------------------")
 		self.__entries.extend(selected_entries)
 		self.__entries.append("--------------------------------------------------------------------------------")
```

### Comparing `mighty_logger-0.7.1/mighty_logger/basic/patterns.py` & `mighty_logger-0.7.2/mighty_logger/basic/patterns.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/powerful_logger.py` & `mighty_logger-0.7.2/mighty_logger/mighty_logger.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/simple_logger.py` & `mighty_logger-0.7.2/mighty_logger/simple_logger.py`

 * *Files 1% similar despite different names*

```diff
@@ -15,15 +15,15 @@
 See the License for the specific language governing permissions and
 limitations under the License.
 """
 
 from mighty_logger.basic.lib_types.environment_type import EnvironmentType
 from mighty_logger.src.lib_types_collection.entry_types import LoggerEntryTypes, ServiceProcessEntryTypes
 from mighty_logger.src.lib_types_collection.environments import LogEnvironments
-from mighty_logger.powerful_logger import MightyLogger
+from mighty_logger.mighty_logger import MightyLogger
 
 class Logger:
 	"""
 	...
 	"""
 
 	def __init__(
```

### Comparing `mighty_logger-0.7.1/mighty_logger/src/__init__.py` & `mighty_logger-0.7.2/mighty_logger/src/__init__.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/src/animations.py` & `mighty_logger-0.7.2/mighty_logger/src/animations.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/src/ansi_format.py` & `mighty_logger-0.7.2/mighty_logger/src/ansi_format.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/src/color_picker.py` & `mighty_logger-0.7.2/mighty_logger/src/color_picker.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/__init__.py` & `mighty_logger-0.7.2/mighty_logger/src/lib_types_collection/__init__.py`

 * *Files 12% similar despite different names*

```diff
@@ -12,11 +12,11 @@
 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
 """
 
-from .entry_types import LoggerEntryTypes, ProcessEntryTypes, SelectionTypes
+from .entry_types import LoggerEntryTypes, ProcessEntryTypes, SelectionTypes, SelectionCategories
 from .environments import LogEnvironments
 from .sorting_keys import SortingKeys
 from .status_variables import StatusMessagePatterns
```

### Comparing `mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/entry_types.py` & `mighty_logger-0.7.2/mighty_logger/src/lib_types_collection/entry_types.py`

 * *Files 6% similar despite different names*

```diff
@@ -34,15 +34,16 @@
 			("", HexColor('GOLD')),
 			("", "")
 		)
 	)
 
 class LoggerEntryTypes:
 	debug = EntryType(
-		type_name="%DEBUG",
+		type_category="%",
+		type_name="DEBUG",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			("", "")
 		),
@@ -84,15 +85,16 @@
 		icon=('🐛', '🐞', '🚧', '🔬')
 	)
 	"""
 	Debugging information logging:
 	Can be used to log entry any information while debugging an application.
 	"""
 	debug_performance = EntryType(
-		type_name="%DEBUG-PERFORMANCE",
+		type_category="%",
+		type_name="DEBUG-PERFORMANCE",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			("", "")
 		),
@@ -135,15 +137,16 @@
 	)
 	"""
 	Performance debugging information logging:
 	Can be used to log entry the execution time of operations or other
 	performance information while the application is being debugged.
 	"""
 	performance = EntryType(
-		type_name="%PERFORMANCE",
+		type_category="%",
+		type_name="PERFORMANCE",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			("", "")
 		),
@@ -186,15 +189,16 @@
 	)
 	"""
 	Performance information logging:
 	Can be used to log entry the execution time of operations or
 	other application performance information.
 	"""
 	event = EntryType(
-		type_name="~EVENT",
+		type_category="~",
+		type_name="EVENT",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			("", "")
 		),
@@ -237,15 +241,16 @@
 	)
 	"""
 	Event information logging:
 	Can be used to log entry specific events in the application,
 	such as button presses or mouse cursor movements.
 	"""
 	audit = EntryType(
-		type_name="~AUDIT",
+		type_category="~",
+		type_name="AUDIT",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			("", "")
 		),
@@ -288,15 +293,16 @@
 	)
 	"""
 	Audit information logging:
 	Can be used to log entry changes in the system, such as creating or
 	deleting users, as well as changes in security settings.
 	"""
 	metrics = EntryType(
-		type_name="~METRICS",
+		type_category="~",
+		type_name="METRICS",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			("", "")
 		),
@@ -338,15 +344,16 @@
 		icon=('📊', '📈', '📉', '📄')
 	)
 	"""
 	Metrics information logging:
 	Can be used to log entry metrics to track application performance and identify issues.
 	"""
 	user = EntryType(
-		type_name="~USER",
+		type_category="~",
+		type_name="USER",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			("", "")
 		),
@@ -389,15 +396,16 @@
 	)
 	"""
 	User information logging:
 	Can be used to log entry custom logs to store additional information
 	that may be useful for diagnosing problems.
 	"""
 	message = EntryType(
-		type_name="@MESSAGE",
+		type_category="@",
+		type_name="MESSAGE",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			("", "")
 		),
@@ -439,15 +447,16 @@
 		icon=('💬', '📝', '🗒️', '📨')
 	)
 	"""
 	Message information logging:
 	Can be used for the usual output of ordinary messages about the program's operation.
 	"""
 	info = EntryType(
-		type_name="@INFO",
+		type_category="@",
+		type_name="INFO",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			("", "")
 		),
@@ -489,15 +498,16 @@
 		icon=('ℹ️', '🔍', '📌', '🔔')
 	)
 	"""
 	Default information logging:
 	Can be used to log entry messages with specific content about the operation of the program.
 	"""
 	notice = EntryType(
-		type_name="@NOTICE",
+		type_category="@",
+		type_name="NOTICE",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			("", "")
 		),
@@ -539,15 +549,16 @@
 		icon=('📌', '📎', '🔖', '🚩')
 	)
 	"""
 	Notice information logging:
 	Can be used to flag important events that might be missed with a normal logging level.
 	"""
 	warning = EntryType(
-		type_name="!WARNING",
+		type_category="!",
+		type_name="WARNING",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			("", "")
 		),
@@ -589,15 +600,16 @@
 		icon=('⚠️', '⚡️', '⛔️', '⚠️')
 	)
 	"""
 	Warning information logging:
 	Can be used to log entry warnings that the program may work with unpredictable results.
 	"""
 	error = EntryType(
-		type_name="!!ERROR",
+		type_category="!",
+		type_name="!ERROR",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('PLUM', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('PLUM')),
 			(HexColor('ORCHID'), HexColor('PLUM')),
 			("", "")
 		),
@@ -639,15 +651,16 @@
 		icon=('❌', '🚫', '💔', '🔺')
 	)
 	"""
 	Error information logging:
 	Used to log entry errors and crashes in the program.
 	"""
 	critical = EntryType(
-		type_name="!!!@CRITICAL",
+		type_category="!",
+		type_name="!!@CRITICAL",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('PLUM', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('PLUM')),
 			(HexColor('ORCHID'), HexColor('PLUM')),
 			("", "")
 		),
@@ -689,15 +702,16 @@
 		icon=('🔥', '🚨', '⛔️', '🚒')
 	)
 	"""
 	Critical error information logging:
 	Used to log entry for critical and unpredictable program failures.
 	"""
 	resolved = EntryType(
-		type_name="!RESOLVED",
+		type_category="!",
+		type_name="RESOLVED",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('LAVENDERBLUSH', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			("", "")
 		),
@@ -741,15 +755,16 @@
 	"""
 	Resolved information logging:
 	Used to log entry resolved solutions to problems and errors.
 	\n
 	Since v0.6.0
 	"""
 	unresolved = EntryType(
-		type_name="!UNRESOLVED",
+		type_category="!",
+		type_name="UNRESOLVED",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('LAVENDERBLUSH', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			("", "")
 		),
@@ -795,15 +810,16 @@
 	Used to log entry unresolved solutions to problems and errors.
 	\n
 	Since v0.6.0
 	"""
 
 class ProcessEntryTypes:
 	achievement = EntryType(
-		type_name="&ACHIEVEMENT",
+		type_category="&",
+		type_name="ACHIEVEMENT",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			("", "")
 		),
@@ -845,15 +861,16 @@
 		icon=('🏆', '🏆', '🌟', '🎖️')
 	)
 	"""
 	Achievement information logging:
 	Used to log entry the achievements gained while executing a process.
 	"""
 	milestone = EntryType(
-		type_name="&MILESTONE",
+		type_category="&",
+		type_name="MILESTONE",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('LAVENDERBLUSH', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			("", "")
 		),
@@ -897,15 +914,16 @@
 	"""
 	Milestone information logging:
 	Used to log entry the milestones gained while executing a process.
 	"""
 
 class ServiceProcessEntryTypes:
 	initiation = EntryType(
-		type_name="&INITIATION",
+		type_category="&",
+		type_name="INITIATION",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('LAVENDERBLUSH', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			("", "")
 		),
@@ -947,15 +965,16 @@
 		icon=('🚀', '🚀', '🔥', '🔧')
 	)
 	"""
 	Initiation information logging:
 	Used to explain the running process.
 	"""
 	process = EntryType(
-		type_name="&PROGRESS",
+		type_category="&",
+		type_name="PROGRESS",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('PURPLE', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('PURPLE')),
 			(HexColor('ORCHID'), HexColor('PURPLE')),
 			("", "")
 		),
@@ -996,15 +1015,16 @@
 		),
 		icon=('⏳', '🔄', '⚙️', '🕰️')
 	)
 	"""
 	...
 	"""
 	success = EntryType(
-		type_name="&SUCCESS",
+		type_category="&",
+		type_name="SUCCESS",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('LAVENDERBLUSH', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			("", "")
 		),
@@ -1046,15 +1066,16 @@
 		icon=('✔️', '🎉', '👍', '✅')
 	)
 	"""
 	Success information logging:
 	Used to log entry a message about the success of the process.
 	"""
 	fail = EntryType(
-		type_name="&FAIL",
+		type_category="&",
+		type_name="FAIL",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('LAVENDERBLUSH', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			("", "")
 		),
@@ -1098,15 +1119,16 @@
 	"""
 	Fail information logging:
 	Used to log entry a message about the failed execution of the process.
 	"""
 
 class ServiceTimerEntryTypes:
 	start_timer = EntryType(
-		type_name="^START-TIMER",
+		type_category="^",
+		type_name="START-TIMER",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('LAVENDERBLUSH', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			(HexColor('ORCHID'), HexColor('LAVENDERBLUSH')),
 			("", "")
 		),
@@ -1148,15 +1170,16 @@
 		icon=('⏰', '🕑', '🟩', '⏳')
 	)
 	"""
 	Information logging of starting Timer:
 	Used to notify the start of the Timer.
 	"""
 	timer_mark = EntryType(
-		type_name="^TIMER-MARK",
+		type_category="^",
+		type_name="TIMER-MARK",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('DARKMAGENTA', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			(HexColor('ORCHID'), HexColor('DARKMAGENTA')),
 			("", "")
 		),
@@ -1198,15 +1221,16 @@
 		icon=('⌚', '🕕', '🟨', '⏱️')
 	)
 	"""
 	Information logging of mark Timer:
 	Used to notify the mark of the Timer.
 	"""
 	stop_timer = EntryType(
-		type_name="^STOP-TIMER",
+		type_category="^",
+		type_name="STOP-TIMER",
 		time_color=(
 			(AnsiColor('ORCHID', "foreground"), AnsiColor('PURPLE', "foreground")),
 			("", ""),
 			(HexColor('ORCHID'), HexColor('PURPLE')),
 			(HexColor('ORCHID'), HexColor('PURPLE')),
 			("", "")
 		),
@@ -1249,31 +1273,39 @@
 	)
 	"""
 	Information logging of stopping Timer:
 	Used to notify the stop of the Timer.
 	"""
 
 class SelectionTypes:
-	debug = EntryType(type_name="%DEBUG")
-	debug_performance = EntryType(type_name="%DEBUG-PERFORMANCE")
-	performance = EntryType(type_name="%PERFORMANCE")
-	event = EntryType(type_name="~EVENT")
-	audit = EntryType(type_name="~AUDIT")
-	metrics = EntryType(type_name="~METRICS")
-	user = EntryType(type_name="~USER")
-	message = EntryType(type_name="@MESSAGE")
-	info = EntryType(type_name="@INFO")
-	notice = EntryType(type_name="@NOTICE")
-	warning = EntryType(type_name="!WARNING")
-	error = EntryType(type_name="!!ERROR")
-	critical = EntryType(type_name="!!!@CRITICAL")
-	resolved = EntryType(type_name="!RESOLVED")
-	unresolved = EntryType(type_name="!UNRESOLVED")
-	achievement = EntryType(type_name="&ACHIEVEMENT")
-	milestone = EntryType(type_name="&MILESTONE")
-	initiation = EntryType(type_name="&INITIATION")
-	process = EntryType(type_name="&PROGRESS")
-	success = EntryType(type_name="&SUCCESS")
-	fail = EntryType(type_name="&FAIL")
-	start_timer = EntryType(type_name="^START-TIMER")
-	timer_mark = EntryType(type_name="^TIMER-MARK")
-	stop_timer = EntryType(type_name="^STOP-TIMER")
+	debug = EntryType(type_category="", type_name="DEBUG")
+	debug_performance = EntryType(type_category="", type_name="DEBUG-PERFORMANCE")
+	performance = EntryType(type_category="", type_name="PERFORMANCE")
+	event = EntryType(type_category="", type_name="EVENT")
+	audit = EntryType(type_category="", type_name="AUDIT")
+	metrics = EntryType(type_category="", type_name="METRICS")
+	user = EntryType(type_category="", type_name="USER")
+	message = EntryType(type_category="", type_name="MESSAGE")
+	info = EntryType(type_category="", type_name="INFO")
+	notice = EntryType(type_category="", type_name="NOTICE")
+	warning = EntryType(type_category="", type_name="WARNING")
+	error = EntryType(type_category="", type_name="!ERROR")
+	critical = EntryType(type_category="", type_name="!!@CRITICAL")
+	resolved = EntryType(type_category="", type_name="RESOLVED")
+	unresolved = EntryType(type_category="", type_name="UNRESOLVED")
+	achievement = EntryType(type_category="", type_name="ACHIEVEMENT")
+	milestone = EntryType(type_category="", type_name="MILESTONE")
+	initiation = EntryType(type_category="", type_name="INITIATION")
+	process = EntryType(type_category="", type_name="PROGRESS")
+	success = EntryType(type_category="", type_name="SUCCESS")
+	fail = EntryType(type_category="", type_name="FAIL")
+	start_timer = EntryType(type_category="", type_name="START-TIMER")
+	timer_mark = EntryType(type_category="", type_name="TIMER-MARK")
+	stop_timer = EntryType(type_category="", type_name="STOP-TIMER")
+
+class SelectionCategories:
+	debug = EntryType(type_category="%", type_name="")
+	event = EntryType(type_category="~", type_name="")
+	message = EntryType(type_category="@", type_name="")
+	error = EntryType(type_category="!", type_name="")
+	process = EntryType(type_category="&", type_name="")
+	timer = EntryType(type_category="^", type_name="")
```

### Comparing `mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/environments.py` & `mighty_logger-0.7.2/mighty_logger/src/lib_types_collection/environments.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/sorting_keys.py` & `mighty_logger-0.7.2/mighty_logger/src/lib_types_collection/sorting_keys.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/src/lib_types_collection/status_variables.py` & `mighty_logger-0.7.2/mighty_logger/src/lib_types_collection/status_variables.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger/src/text_buffer.py` & `mighty_logger-0.7.2/mighty_logger/src/text_buffer.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/mighty_logger.egg-info/PKG-INFO` & `mighty_logger-0.7.2/mighty_logger.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mighty-logger
-Version: 0.7.1
+Version: 0.7.2
 Summary: Powerful functional logger
 Home-page: https://github.com/Nakama3942/mighty_logger
 Author: Kalynovsky 'Nakamura Akira' Valentin
 Author-email: nakama3942@gmail.com
 License: Apache License, Version 2.0, see LICENSE file
 Project-URL: Releases, https://github.com/Nakama3942/mighty_logger/releases
 Classifier: Development Status :: 3 - Alpha
@@ -105,14 +105,15 @@
 - [x] v0.4.0 - Buffer update (added text buffer)
 - [x] v0.5.0 - Unifying update (console and HTML are combined into one class)
 - [x] v0.5.1 - Hints update (added status message templates and hint symbols (icons) near log entries status)
 - [x] v0.6.0 - Progress update (added start of some log entries in threads (process))
 - [x] v0.6.1 - Animation update (added animations in processes)
 - [x] v0.7.0 - "Buffer improvement" update (buffer development completed and entry type system reworked)
 - [x] v0.7.1 - Modding update (buffer modification added - sorting, searching and selecting)
+- [x] v0.7.2 - Categories update (separated the entry category from the type)
 - [ ] v0.8.0 - Export update (added conversion to different types, such as csv, pdf, etc.)
 - [ ] v0.9.0 - Extension update (made wheel format and instruction of toml)
 - [ ] v0.9.1 - Documenting update (all updates since v0.7.0 are documented; updated old documentation; documentation site generation added)
 - [ ] v1.0.0 - Completion of logger development (logger development completed)
 - [ ] v1.1.0 - Font update (added a class that formats text outside the logger)
 
 </details>
```

### Comparing `mighty_logger-0.7.1/mighty_logger.egg-info/SOURCES.txt` & `mighty_logger-0.7.2/mighty_logger.egg-info/SOURCES.txt`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 LICENSE
 README.md
 setup.cfg
 setup.py
 mighty_logger/__init__.py
-mighty_logger/powerful_logger.py
+mighty_logger/mighty_logger.py
 mighty_logger/simple_logger.py
 mighty_logger.egg-info/PKG-INFO
 mighty_logger.egg-info/SOURCES.txt
 mighty_logger.egg-info/dependency_links.txt
 mighty_logger.egg-info/top_level.txt
 mighty_logger/basic/__init__.py
 mighty_logger/basic/basic_logger.py
```

### Comparing `mighty_logger-0.7.1/setup.py` & `mighty_logger-0.7.2/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -19,15 +19,15 @@
 from setuptools import setup
 
 with open("README.md", "r", encoding='utf-8') as readme_file:
     readme = readme_file.read()
 
 setup(
     name="mighty_logger",
-    version="0.7.1",
+    version="0.7.2",
 
     author="Kalynovsky 'Nakamura Akira' Valentin",
     author_email="nakama3942@gmail.com",
 
     description="Powerful functional logger",
     long_description=readme,
     long_description_content_type="text/markdown",
```

### Comparing `mighty_logger-0.7.1/test/test.py` & `mighty_logger-0.7.2/test/test.py`

 * *Files identical despite different names*

### Comparing `mighty_logger-0.7.1/test/test_simple.py` & `mighty_logger-0.7.2/test/test_simple.py`

 * *Files identical despite different names*


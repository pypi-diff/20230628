# Comparing `tmp/cognite_extractor_utils-5.1.0.tar.gz` & `tmp/cognite_extractor_utils-5.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "cognite_extractor_utils-5.1.0.tar", max compression
+gzip compressed data, was "cognite_extractor_utils-5.2.0.tar", max compression
```

## Comparing `cognite_extractor_utils-5.1.0.tar` & `cognite_extractor_utils-5.2.0.tar`

### file list

```diff
@@ -1,26 +1,26 @@
--rw-r--r--   0        0        0    10173 2023-06-12 12:33:44.287061 cognite_extractor_utils-5.1.0/LICENSE
--rw-r--r--   0        0        0     4091 2023-06-12 12:33:44.287061 cognite_extractor_utils-5.1.0/README.md
--rw-r--r--   0        0        0      739 2023-06-12 12:33:44.287061 cognite_extractor_utils-5.1.0/cognite/extractorutils/__init__.py
--rw-r--r--   0        0        0     1431 2023-06-12 12:33:44.287061 cognite_extractor_utils-5.1.0/cognite/extractorutils/_inner_util.py
--rw-r--r--   0        0        0    15990 2023-06-12 12:33:44.287061 cognite_extractor_utils-5.1.0/cognite/extractorutils/base.py
--rw-r--r--   0        0        0     2861 2023-06-12 12:33:44.287061 cognite_extractor_utils-5.1.0/cognite/extractorutils/configtools/__init__.py
--rw-r--r--   0        0        0     4294 2023-06-12 12:33:44.287061 cognite_extractor_utils-5.1.0/cognite/extractorutils/configtools/_util.py
--rw-r--r--   0        0        0    19616 2023-06-12 12:33:44.287061 cognite_extractor_utils-5.1.0/cognite/extractorutils/configtools/elements.py
--rw-r--r--   0        0        0     9188 2023-06-12 12:33:44.287061 cognite_extractor_utils-5.1.0/cognite/extractorutils/configtools/loaders.py
--rw-r--r--   0        0        0     1061 2023-06-12 12:33:44.287061 cognite_extractor_utils-5.1.0/cognite/extractorutils/exceptions.py
--rw-r--r--   0        0        0    14604 2023-06-12 12:33:44.287061 cognite_extractor_utils-5.1.0/cognite/extractorutils/metrics.py
--rw-r--r--   0        0        0     1005 2023-06-12 12:33:44.287061 cognite_extractor_utils-5.1.0/cognite/extractorutils/middleware.py
--rw-r--r--   0        0        0        0 2023-06-12 12:33:44.287061 cognite_extractor_utils-5.1.0/cognite/extractorutils/py.typed
--rw-r--r--   0        0        0    17449 2023-06-12 12:33:44.291061 cognite_extractor_utils-5.1.0/cognite/extractorutils/statestore.py
--rw-r--r--   0        0        0     3054 2023-06-12 12:33:44.291061 cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader/__init__.py
--rw-r--r--   0        0        0     5240 2023-06-12 12:33:44.291061 cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader/_base.py
--rw-r--r--   0        0        0     3865 2023-06-12 12:33:44.291061 cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader/_metrics.py
--rw-r--r--   0        0        0     5292 2023-06-12 12:33:44.291061 cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader/events.py
--rw-r--r--   0        0        0    11351 2023-06-12 12:33:44.291061 cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader/files.py
--rw-r--r--   0        0        0     6888 2023-06-12 12:33:44.291061 cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader/raw.py
--rw-r--r--   0        0        0    25071 2023-06-12 12:33:44.291061 cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader/time_series.py
--rw-r--r--   0        0        0     7404 2023-06-12 12:33:44.291061 cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader_extractor.py
--rw-r--r--   0        0        0     1146 2023-06-12 12:33:44.291061 cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader_types.py
--rw-r--r--   0        0        0    13352 2023-06-12 12:33:44.291061 cognite_extractor_utils-5.1.0/cognite/extractorutils/util.py
--rw-r--r--   0        0        0     1650 2023-06-12 12:33:44.291061 cognite_extractor_utils-5.1.0/pyproject.toml
--rw-r--r--   0        0        0     5407 1970-01-01 00:00:00.000000 cognite_extractor_utils-5.1.0/PKG-INFO
+-rw-r--r--   0        0        0    10173 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/LICENSE
+-rw-r--r--   0        0        0     4090 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/README.md
+-rw-r--r--   0        0        0      739 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/__init__.py
+-rw-r--r--   0        0        0     1558 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/_inner_util.py
+-rw-r--r--   0        0        0    15974 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/base.py
+-rw-r--r--   0        0        0     2861 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/configtools/__init__.py
+-rw-r--r--   0        0        0     4739 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/configtools/_util.py
+-rw-r--r--   0        0        0    19910 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/configtools/elements.py
+-rw-r--r--   0        0        0     9545 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/configtools/loaders.py
+-rw-r--r--   0        0        0     1061 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/exceptions.py
+-rw-r--r--   0        0        0    14929 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/metrics.py
+-rw-r--r--   0        0        0     1108 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/middleware.py
+-rw-r--r--   0        0        0        0 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/py.typed
+-rw-r--r--   0        0        0    17829 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/statestore.py
+-rw-r--r--   0        0        0     3054 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader/__init__.py
+-rw-r--r--   0        0        0     4983 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader/_base.py
+-rw-r--r--   0        0        0     3865 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader/_metrics.py
+-rw-r--r--   0        0        0     6118 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader/events.py
+-rw-r--r--   0        0        0    11674 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader/files.py
+-rw-r--r--   0        0        0     7021 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader/raw.py
+-rw-r--r--   0        0        0    26579 2023-06-28 07:09:15.525399 cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader/time_series.py
+-rw-r--r--   0        0        0     7476 2023-06-28 07:09:15.529399 cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader_extractor.py
+-rw-r--r--   0        0        0     1146 2023-06-28 07:09:15.529399 cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader_types.py
+-rw-r--r--   0        0        0    14284 2023-06-28 07:09:15.529399 cognite_extractor_utils-5.2.0/cognite/extractorutils/util.py
+-rw-r--r--   0        0        0     2066 2023-06-28 07:09:15.529399 cognite_extractor_utils-5.2.0/pyproject.toml
+-rw-r--r--   0        0        0     5406 1970-01-01 00:00:00.000000 cognite_extractor_utils-5.2.0/PKG-INFO
```

### Comparing `cognite_extractor_utils-5.1.0/LICENSE` & `cognite_extractor_utils-5.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `cognite_extractor_utils-5.1.0/README.md` & `cognite_extractor_utils-5.2.0/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -85,8 +85,7 @@
 ```
 $ poetry run pre-commit install
 ```
 
 Each public method, class and module should have docstrings. Docstrings are written in the [Google
 style](https://google.github.io/styleguide/pyguide.html#38-comments-and-docstrings). Please include unit and/or
 integration tests for submitted code, and remember to update the [changelog](./CHANGELOG.md).
-
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/__init__.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -12,9 +12,9 @@
 #  See the License for the specific language governing permissions and
 #  limitations under the License.
 
 """
 Cognite extractor utils is a Python package that simplifies the development of new extractors.
 """
 
-__version__ = "5.1.0"
+__version__ = "5.2.0"
 from .base import Extractor
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/_inner_util.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/_inner_util.py`

 * *Files 10% similar despite different names*

```diff
@@ -14,28 +14,29 @@
 
 """
 A module containing utilities meant for use inside the extractor-utils package
 """
 
 import json
 from decimal import Decimal
+from typing import Any, Dict, Union
 
 
 def _resolve_log_level(level: str) -> int:
     return {"NOTSET": 0, "DEBUG": 10, "INFO": 20, "WARNING": 30, "ERROR": 40, "CRITICAL": 50}[level.upper()]
 
 
 class _DecimalEncoder(json.JSONEncoder):
-    def default(self, obj):
+    def default(self, obj: Any) -> Dict[str, str]:
         if isinstance(obj, Decimal):
             return {"type": "decimal_encoded", "value": str(obj)}
         return super(_DecimalEncoder, self).default(obj)
 
 
 class _DecimalDecoder(json.JSONDecoder):
-    def __init__(self, *args, **kwargs):
+    def __init__(self, *args: Any, **kwargs: Any) -> None:
         json.JSONDecoder.__init__(self, object_hook=self.object_hook, *args, **kwargs)
 
-    def object_hook(self, obj_dict):
+    def object_hook(self, obj_dict: Dict[str, str]) -> Union[Dict[str, str], Decimal]:
         if obj_dict.get("type") == "decimal_encoded":
             return Decimal(obj_dict["value"])
         return obj_dict
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/base.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/base.py`

 * *Files 3% similar despite different names*

```diff
@@ -17,18 +17,18 @@
 import sys
 from dataclasses import is_dataclass
 from enum import Enum
 from threading import Event, Thread
 from types import TracebackType
 from typing import Any, Callable, Dict, Generic, Optional, Type, TypeVar
 
-from cognite.client import CogniteClient
-from cognite.client.data_classes import ExtractionPipeline, ExtractionPipelineRun
 from dotenv import find_dotenv, load_dotenv
 
+from cognite.client import CogniteClient
+from cognite.client.data_classes import ExtractionPipeline, ExtractionPipelineRun
 from cognite.extractorutils.configtools import BaseConfig, ConfigResolver, StateStoreConfig
 from cognite.extractorutils.exceptions import InvalidConfigError
 from cognite.extractorutils.metrics import BaseMetrics
 from cognite.extractorutils.statestore import AbstractStateStore, LocalStateStore, NoStateStore
 from cognite.extractorutils.util import set_event_on_interrupt
 
 
@@ -90,15 +90,15 @@
         reload_config_action: ReloadConfigAction = ReloadConfigAction.DO_NOTHING,
     ):
         self.name = name
         self.description = description
         self.run_handle = run_handle
         self.config_class = config_class
         self.use_default_state_store = use_default_state_store
-        self.version = version
+        self.version = version or "unknown"
         self.cancellation_token = cancellation_token
         self.config_file_path = config_file_path
         self.continuous_extractor = continuous_extractor
         self.heartbeat_waiting_time = heartbeat_waiting_time
         self.handle_interrupts = handle_interrupts
         self.reload_config_interval = reload_config_interval
         self.reload_config_action = reload_config_action
@@ -113,15 +113,15 @@
         self.logger: logging.Logger
 
         self.should_be_restarted = False
 
         if metrics:
             self.metrics = metrics
         else:
-            self.metrics = BaseMetrics(extractor_name=name, extractor_version=version)
+            self.metrics = BaseMetrics(extractor_name=name, extractor_version=self.version)
 
     def _initial_load_config(self, override_path: Optional[str] = None) -> None:
         """
         Load a configuration file, either from the specified path, or by a path specified by the user in a command line
         arg. Will quit further execution of no path is given.
 
         Args:
@@ -129,36 +129,36 @@
         """
         if override_path:
             self.config_resolver = ConfigResolver(override_path, self.config_class)
         else:
             self.config_resolver = ConfigResolver.from_cli(self.name, self.description, self.version, self.config_class)
 
         self.config = self.config_resolver.config
-        Extractor._config_singleton = self.config
+        Extractor._config_singleton = self.config  # type: ignore
 
-        def config_refresher():
+        def config_refresher() -> None:
             while not self.cancellation_token.is_set():
                 self.cancellation_token.wait(self.reload_config_interval)
                 if self.config_resolver.has_changed:
                     self._reload_config()
 
         if self.reload_config_interval and self.reload_config_action != ReloadConfigAction.DO_NOTHING:
             Thread(target=config_refresher, name="ConfigReloader", daemon=True).start()
 
-    def reload_config_callback(self):
+    def reload_config_callback(self) -> None:
         self.logger.error("Method for reloading configs has not been overridden in subclass")
 
     def _reload_config(self) -> None:
         self.logger.info("Config file has changed")
 
         if self.reload_config_action == ReloadConfigAction.REPLACE_ATTRIBUTE:
             self.logger.info("Loading in new config file")
             self.config_resolver.accept_new_config()
             self.config = self.config_resolver.config
-            Extractor._config_singleton = self.config
+            Extractor._config_singleton = self.config  # type: ignore
 
         elif self.reload_config_action == ReloadConfigAction.SHUTDOWN:
             self.logger.info("Shutting down, expecting to be restarted")
             self.cancellation_token.set()
 
         elif self.reload_config_action == ReloadConfigAction.CALLBACK:
             self.logger.info("Loading in new config file")
@@ -189,15 +189,15 @@
         if state_store_config:
             self.state_store = state_store_config.create_state_store(self.cognite_client, self.use_default_state_store)
         else:
             self.state_store = LocalStateStore("states.json") if self.use_default_state_store else NoStateStore()
 
         try:
             self.state_store.initialize()
-        except ValueError as e:
+        except ValueError:
             self.logger.exception("Could not load state store, using an empty state store as default")
 
         Extractor._statestore_singleton = self.state_store
 
     def _report_success(self) -> None:
         """
         Called on a successful exit of the extractor
@@ -208,26 +208,24 @@
                 ExtractionPipelineRun(
                     extpipe_external_id=self.extraction_pipeline.external_id,
                     status="success",
                     message="Successful shutdown",
                 )
             )
 
-    def _report_error(self, exc_type: Type[BaseException], exc_val: BaseException, exc_tb: TracebackType) -> None:
+    def _report_error(self, exception: BaseException) -> None:
         """
         Called on an unsuccessful exit of the extractor
 
         Args:
-            exc_type: Type of exception that caused the extractor to fail
-            exc_val: Exception object that caused the extractor to fail
-            exc_tb: Stack trace of where the extractor failed
+            exception: Exception object that caused the extractor to fail
         """
-        self.logger.error("Unexpected error during extraction", exc_info=exc_val)
+        self.logger.error("Unexpected error during extraction", exc_info=exception)
         if self.extraction_pipeline:
-            message = f"{exc_type.__name__}: {str(exc_val)}"[:1000]
+            message = f"{type(exception).__name__}: {str(exception)}"[:1000]
 
             self.logger.info(f"Reporting new failed run: {message}")
             self.cognite_client.extraction_pipelines.runs.create(
                 ExtractionPipelineRun(
                     extpipe_external_id=self.extraction_pipeline.external_id, status="failure", message=message
                 )
             )
@@ -250,16 +248,16 @@
                 dotenv_message = "No .env file found"
         else:
             dotenv_message = "No .env file imported when using Cognite Functions"
 
         try:
             self._initial_load_config(override_path=self.config_file_path)
         except InvalidConfigError as e:
-            print("Critical error: Could not read config file", file=sys.stderr)
-            print(str(e), file=sys.stderr)
+            print("Critical error: Could not read config file", file=sys.stderr)  # noqa: T201
+            print(str(e), file=sys.stderr)  # noqa: T201
             sys.exit(1)
 
         if not self.configured_logger:
             self.config.logger.setup_logging()
             self.configured_logger = True
 
         self.logger = logging.getLogger(__name__)
@@ -272,28 +270,28 @@
         self.cognite_client = self.config.cognite.get_cognite_client(self.name)
         self._load_state_store()
         self.state_store.start()
 
         self.extraction_pipeline = self.config.cognite.get_extraction_pipeline(self.cognite_client)
 
         try:
-            self.config.metrics.start_pushers(self.cognite_client)
+            self.config.metrics.start_pushers(self.cognite_client)  # type: ignore
         except AttributeError:
             pass
 
-        def heartbeat_loop():
+        def heartbeat_loop() -> None:
             while not self.cancellation_token.is_set():
                 self.cancellation_token.wait(self.heartbeat_waiting_time)
 
                 if not self.cancellation_token.is_set():
                     self.logger.info("Reporting new heartbeat")
                     try:
                         self.cognite_client.extraction_pipelines.runs.create(
                             ExtractionPipelineRun(
-                                extpipe_external_id=self.extraction_pipeline.external_id, status="seen"
+                                extpipe_external_id=self.extraction_pipeline.external_id, status="seen"  # type: ignore
                             )
                         )
                     except Exception:
                         self.logger.exception("Failed to report heartbeat")
 
         if self.extraction_pipeline:
             self.logger.info("Starting heartbeat loop")
@@ -332,20 +330,20 @@
         """
         self.cancellation_token.set()
 
         if self.state_store:
             self.state_store.synchronize()
 
         try:
-            self.config.metrics.stop_pushers()
+            self.config.metrics.stop_pushers()  # type: ignore
         except AttributeError:
             pass
 
         if exc_val:
-            self._report_error(exc_type, exc_val, exc_tb)
+            self._report_error(exc_val)
         else:
             self._report_success()
 
         self.started = False
         return exc_val is None
 
     def run(self) -> None:
@@ -360,16 +358,16 @@
         if self.run_handle:
             self.run_handle(self.cognite_client, self.state_store, self.config, self.cancellation_token)
         else:
             raise ValueError("No run_handle defined")
 
     @classmethod
     def get_current_config(cls) -> CustomConfigClass:
-        if Extractor._config_singleton is None:
+        if Extractor._config_singleton is None:  # type: ignore
             raise ValueError("No config singleton created. Have a config file been loaded?")
-        return Extractor._config_singleton
+        return Extractor._config_singleton  # type: ignore
 
     @classmethod
     def get_current_statestore(cls) -> AbstractStateStore:
         if Extractor._statestore_singleton is None:
             raise ValueError("No state store singleton created. Have a state store been loaded?")
         return Extractor._statestore_singleton
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/configtools/__init__.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/configtools/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -12,17 +12,17 @@
 #  See the License for the specific language governing permissions and
 #  limitations under the License.
 
 """
 Module containing tools for loading and verifying config files, and a YAML loader to automatically serialize these
 dataclasses from a config file.
 
-Configs are described as ``dataclass``\es, and use the ``BaseConfig`` class as a superclass to get a few things built-in:
-config version, Cognite project and logging. Use type hints to specify types, use the ``Optional`` type to specify that
-a config parameter is optional, and give the attribute a value to give it a default.
+Configs are described as ``dataclass``\es, and use the ``BaseConfig`` class as a superclass to get a few things
+built-in: config version, Cognite project and logging. Use type hints to specify types, use the ``Optional`` type to
+specify that a config parameter is optional, and give the attribute a value to give it a default.
 
 For example, a config class for an extractor may look like the following:
 
 .. code-block:: python
 
     @dataclass
     class ExtractorConfig:
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/configtools/_util.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/configtools/_util.py`

 * *Files 7% similar despite different names*

```diff
@@ -10,15 +10,15 @@
 #  distributed under the License is distributed on an "AS IS" BASIS,
 #  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #  See the License for the specific language governing permissions and
 #  limitations under the License.
 import base64
 import re
 from pathlib import Path
-from typing import Any, Dict, Optional, Tuple
+from typing import Any, Callable, Dict, List, Optional, Tuple, Union
 
 from cryptography.hazmat.primitives import hashes
 from cryptography.hazmat.primitives import serialization as serialization
 from cryptography.hazmat.primitives.serialization import pkcs12 as pkcs12
 from cryptography.x509 import load_pem_x509_certificate
 
 from cognite.extractorutils.exceptions import InvalidConfigError
@@ -33,76 +33,82 @@
         dictionary: Dictionary to update.
         case_style: Existing casing convention. Either 'snake', 'hyphen' or 'camel'.
 
     Returns:
         An updated dictionary with keys in the given convention.
     """
 
-    def fix_list(list_, key_translator):
+    def fix_list(list_: List[Any], key_translator: Callable[[str], str]) -> List[Any]:
         if list_ is None:
             return []
 
-        new_list = [None] * len(list_)
+        new_list: List[Any] = [None] * len(list_)
         for i, element in enumerate(list_):
             if isinstance(element, dict):
                 new_list[i] = fix_dict(element, key_translator)
             elif isinstance(element, list):
                 new_list[i] = fix_list(element, key_translator)
             else:
                 new_list[i] = element
         return new_list
 
-    def fix_dict(dict_, key_translator):
+    def fix_dict(dict_: Dict[str, Any], key_translator: Callable[[str], str]) -> Dict[str, Any]:
         if dict_ is None:
             return {}
 
-        new_dict = {}
+        new_dict: Dict[str, Any] = {}
         for key in dict_:
             if isinstance(dict_[key], dict):
                 new_dict[key_translator(key)] = fix_dict(dict_[key], key_translator)
             elif isinstance(dict_[key], list):
                 new_dict[key_translator(key)] = fix_list(dict_[key], key_translator)
             else:
                 new_dict[key_translator(key)] = dict_[key]
         return new_dict
 
-    def translate_hyphen(key):
+    def translate_hyphen(key: str) -> str:
         return key.replace("-", "_")
 
-    def translate_camel(key):
+    def translate_camel(key: str) -> str:
         return re.sub(r"([A-Z]+)", r"_\1", key).strip("_").lower()
 
     if case_style == "snake" or case_style == "underscore":
         return dictionary
     elif case_style == "hyphen" or case_style == "kebab":
         return fix_dict(dictionary, translate_hyphen)
     elif case_style == "camel" or case_style == "pascal":
         return fix_dict(dictionary, translate_camel)
     else:
         raise ValueError(f"Invalid case style: {case_style}")
 
 
-def _load_certificate_data(cert_path: str, password: Optional[str]) -> Tuple[str, str]:
+def _load_certificate_data(cert_path: str, password: Optional[str]) -> Union[Tuple[str, str], Tuple[bytes, bytes]]:
     path = Path(cert_path)
     cert_data = Path(path).read_bytes()
 
     if path.suffix == ".pem":
         cert = load_pem_x509_certificate(cert_data)
         private_key = serialization.load_pem_private_key(cert_data, password=password.encode() if password else None)
         private_key_str = private_key.private_bytes(
             encoding=serialization.Encoding.PEM,
             format=serialization.PrivateFormat.TraditionalOpenSSL,
             encryption_algorithm=serialization.NoEncryption(),
         )
-        return (base64.b16encode(cert.fingerprint(hashes.SHA1())), private_key_str)
+        return base64.b16encode(cert.fingerprint(hashes.SHA1())), private_key_str
     elif path.suffix == ".pfx":
-        (private_key, cert, _) = pkcs12.load_key_and_certificates(
+        (private_key_pfx, cert_pfx, _) = pkcs12.load_key_and_certificates(
             cert_data, password=password.encode() if password else None
         )
-        private_key_str = private_key.private_bytes(
+
+        if private_key_pfx is None:
+            raise InvalidConfigError(f"Can't load private key from {cert_path}")
+        if cert_pfx is None:
+            raise InvalidConfigError(f"Can't load certificate from {cert_path}")
+
+        private_key_str = private_key_pfx.private_bytes(
             encoding=serialization.Encoding.PEM,
             format=serialization.PrivateFormat.TraditionalOpenSSL,
             encryption_algorithm=serialization.NoEncryption(),
         )
-        return (base64.b16encode(cert.fingerprint(hashes.SHA1())), private_key_str)
+        return base64.b16encode(cert_pfx.fingerprint(hashes.SHA1())), private_key_str
     else:
         raise InvalidConfigError(f"Unknown certificate format '{path.suffix}'. Allowed formats are 'pem' and 'pfx'")
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/configtools/elements.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/configtools/elements.py`

 * *Files 1% similar despite different names*

```diff
@@ -16,23 +16,23 @@
 import time
 from dataclasses import dataclass, field
 from datetime import timedelta
 from enum import Enum
 from logging.handlers import TimedRotatingFileHandler
 from threading import Event
 from time import sleep
-from typing import Dict, List, Optional, Tuple, Union
+from typing import Any, Dict, List, Optional, Tuple, Union
 from urllib.parse import urljoin
 
 import yaml
-from cognite.client import ClientConfig, CogniteClient
-from cognite.client.credentials import OAuthClientCertificate, OAuthClientCredentials
-from cognite.client.data_classes import Asset, DataSet, ExtractionPipeline
 from prometheus_client import REGISTRY, start_http_server
 
+from cognite.client import ClientConfig, CogniteClient
+from cognite.client.credentials import CredentialProvider, OAuthClientCertificate, OAuthClientCredentials
+from cognite.client.data_classes import Asset, DataSet, ExtractionPipeline
 from cognite.extractorutils.configtools._util import _load_certificate_data
 from cognite.extractorutils.exceptions import InvalidConfigError
 from cognite.extractorutils.metrics import AbstractMetricsPusher, CognitePusher, PrometheusPusher
 from cognite.extractorutils.statestore import AbstractStateStore, LocalStateStore, NoStateStore, RawStateStore
 from cognite.extractorutils.util import EitherId
 
 _logger = logging.getLogger(__name__)
@@ -86,15 +86,15 @@
 
     @property
     def either_id(self) -> EitherId:
         return EitherId(id=self.id, external_id=self.external_id)
 
 
 class TimeIntervalConfig(yaml.YAMLObject):
-    def __init__(self, expression):
+    def __init__(self, expression: str) -> None:
         self._interval, self._expression = TimeIntervalConfig._parse_expression(expression)
 
     @classmethod
     def _parse_expression(cls, expression: str) -> Tuple[int, str]:
         # First, try to parse pure number and assume seconds (for backwards compatibility)
         try:
             return int(expression), f"{expression}s"
@@ -142,15 +142,15 @@
         return self._expression
 
     def __repr__(self) -> str:
         return self._expression
 
 
 class FileSizeConfig(yaml.YAMLObject):
-    def __init__(self, expression):
+    def __init__(self, expression: str) -> None:
         self._bytes, self._expression = FileSizeConfig._parse_expression(expression)
 
     @classmethod
     def _parse_expression(cls, expression: str) -> Tuple[int, str]:
         # First, try to parse pure number and assume bytes
         try:
             return int(expression), f"{expression}s"
@@ -237,77 +237,78 @@
     extraction_pipeline: Optional[EitherIdConfig]
     timeout: TimeIntervalConfig = TimeIntervalConfig("30s")
     connection: ConnectionConfig = field(default_factory=ConnectionConfig)
     external_id_prefix: str = ""
     host: str = "https://api.cognitedata.com"
 
     def get_cognite_client(
-        self, client_name: str, token_custom_args: Optional[Dict[str, str]] = None, use_experimental_sdk=False
+        self, client_name: str, token_custom_args: Optional[Dict[str, str]] = None, use_experimental_sdk: bool = False
     ) -> CogniteClient:
         from cognite.client.config import global_config
 
         global_config.disable_pypi_version_check = True
         global_config.disable_gzip = self.connection.disable_gzip
         global_config.status_forcelist = set(self.connection.status_forcelist)
         global_config.max_retries = self.connection.max_retries
         global_config.max_retries_connect = self.connection.max_retries_connect
         global_config.max_retry_backoff = self.connection.max_retry_backoff
         global_config.max_connection_pool_size = self.connection.max_connection_pool_size
         global_config.disable_ssl = self.connection.disable_ssl
         global_config.proxies = self.connection.proxies
 
+        credential_provider: CredentialProvider
         if self.idp_authentication.certificate:
             if self.idp_authentication.certificate.authority_url:
                 authority_url = self.idp_authentication.certificate.authority_url
             elif self.idp_authentication.tenant:
                 authority_url = urljoin(self.idp_authentication.authority, self.idp_authentication.tenant)
             else:
                 raise InvalidConfigError("Either authority-url or tenant is required for certificate authentication")
             (thumprint, key) = _load_certificate_data(
                 self.idp_authentication.certificate.path, self.idp_authentication.certificate.password
             )
             credential_provider = OAuthClientCertificate(
                 authority_url=authority_url,
                 client_id=self.idp_authentication.client_id,
-                cert_thumbprint=thumprint,
-                certificate=key,
+                cert_thumbprint=str(thumprint),
+                certificate=str(key),
                 scopes=self.idp_authentication.scopes,
             )
 
         elif self.idp_authentication.secret:
-            kwargs = {}
+            kwargs: Dict[str, Any] = {}
             if self.idp_authentication.token_url:
                 kwargs["token_url"] = self.idp_authentication.token_url
             elif self.idp_authentication.tenant:
                 base_url = urljoin(self.idp_authentication.authority, self.idp_authentication.tenant)
                 kwargs["token_url"] = f"{base_url}/oauth2/v2.0/token"
             kwargs["client_id"] = self.idp_authentication.client_id
             kwargs["client_secret"] = self.idp_authentication.secret
             kwargs["scopes"] = self.idp_authentication.scopes
             if token_custom_args is None:
                 token_custom_args = {}
             if self.idp_authentication.resource:
                 token_custom_args["resource"] = self.idp_authentication.resource
             if self.idp_authentication.audience:
                 token_custom_args["audience"] = self.idp_authentication.audience
-            credential_provider = OAuthClientCredentials(**kwargs, **token_custom_args)
+            credential_provider = OAuthClientCredentials(**kwargs, **token_custom_args)  # type: ignore
 
         else:
             raise InvalidConfigError("No client certificate or secret provided")
 
         client_config = ClientConfig(
             project=self.project,
             base_url=self.host,
             client_name=client_name,
             timeout=self.timeout.seconds,
             credentials=credential_provider,
         )
 
         if use_experimental_sdk:
-            from cognite.experimental import CogniteClient as ExperimentalCogniteClient
+            from cognite.experimental import CogniteClient as ExperimentalCogniteClient  # type: ignore
 
             return ExperimentalCogniteClient(client_config)
 
         return CogniteClient(client_config)
 
     def get_data_set(self, cdf_client: CogniteClient) -> Optional[DataSet]:
         if self.data_set_external_id:
@@ -320,25 +321,25 @@
             logging.getLogger(__name__).warning("Using data-set-id is deprecated, please use data-set/id instead")
             return cdf_client.data_sets.retrieve(external_id=self.data_set_external_id)
 
         if not self.data_set:
             return None
 
         return cdf_client.data_sets.retrieve(
-            id=self.data_set.either_id.internal_id, external_id=self.data_set.either_id.external_id
+            id=self.data_set.either_id.internal_id, external_id=self.data_set.either_id.external_id  # type: ignore
         )
 
     def get_extraction_pipeline(self, cdf_client: CogniteClient) -> Optional[ExtractionPipeline]:
         if not self.extraction_pipeline:
             return None
 
         either_id = self.extraction_pipeline.either_id
         extraction_pipeline = cdf_client.extraction_pipelines.retrieve(
-            id=either_id.internal_id,
-            external_id=either_id.external_id,
+            id=either_id.internal_id,  # type: ignore
+            external_id=either_id.external_id,  # type: ignore
         )
         if extraction_pipeline is None:
             raise ValueError(f"Extraction pipeline with {either_id.type()} {either_id.content()} not found")
         return extraction_pipeline
 
 
 @dataclass
@@ -362,15 +363,15 @@
     console: Optional[_ConsoleLoggingConfig]
     file: Optional[_FileLoggingConfig]
     # enables metrics on the number of log messages recorded (per logger and level)
     # In order to collect/see result MetricsConfig should be set as well, so metrics are propagated to
     # Prometheus and/or Cognite
     metrics: Optional[bool] = False
 
-    def setup_logging(self, suppress_console=False) -> None:
+    def setup_logging(self, suppress_console: bool = False) -> None:
         """
         Sets up the default logger in the logging package to be configured as defined in this config object
 
         Args:
             suppress_console: Don't log to console regardless of config. Useful when running an extractor as a Windows
                 service
         """
@@ -451,14 +452,15 @@
 
     def start_pushers(self, cdf_client: CogniteClient, cancellation_token: Event = Event()) -> None:
         self._pushers: List[AbstractMetricsPusher] = []
         self._clear_on_stop: Dict[PrometheusPusher, int] = {}
 
         push_gateways = self.push_gateways or []
 
+        pusher: AbstractMetricsPusher
         for counter, push_gateway in enumerate(push_gateways):
             pusher = PrometheusPusher(
                 job_name=push_gateway.job_name,
                 username=push_gateway.username,
                 password=push_gateway.password,
                 url=push_gateway.host,
                 push_interval=push_gateway.push_interval.seconds,
@@ -470,15 +472,15 @@
             self._pushers.append(pusher)
             if push_gateway.clear_after is not None:
                 self._clear_on_stop[pusher] = push_gateway.clear_after.seconds
 
         if self.cognite:
             asset = None
 
-            if self.cognite.asset_name is not None:
+            if self.cognite.asset_name is not None and self.cognite.asset_external_id:
                 asset = Asset(name=self.cognite.asset_name, external_id=self.cognite.asset_external_id)
 
             pusher = CognitePusher(
                 cdf_client=cdf_client,
                 external_id_prefix=self.cognite.external_id_prefix,
                 push_interval=self.cognite.push_interval.seconds,
                 asset=asset,
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/configtools/loaders.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/configtools/loaders.py`

 * *Files 6% similar despite different names*

```diff
@@ -36,18 +36,18 @@
 CustomConfigClass = TypeVar("CustomConfigClass", bound=BaseConfig)
 
 
 def _load_yaml(
     source: Union[TextIO, str],
     config_type: Type[CustomConfigClass],
     case_style: str = "hyphen",
-    expand_envvars=True,
+    expand_envvars: bool = True,
     dict_manipulator: Callable[[Dict[str, Any]], Dict[str, Any]] = lambda x: x,
 ) -> CustomConfigClass:
-    def env_constructor(_: yaml.SafeLoader, node):
+    def env_constructor(_: yaml.SafeLoader, node: yaml.Node) -> bool:
         bool_values = {
             "true": True,
             "false": False,
         }
         expanded_value = os.path.expandvars(node.value)
         return bool_values.get(expanded_value.lower(), expanded_value)
 
@@ -57,15 +57,15 @@
     EnvLoader.add_implicit_resolver("!env", re.compile(r"\$\{([^}^{]+)\}"), None)
     EnvLoader.add_constructor("!env", env_constructor)
 
     loader = EnvLoader if expand_envvars else yaml.SafeLoader
 
     # Safe to use load instead of safe_load since both loader classes are based on SafeLoader
     try:
-        config_dict = yaml.load(source, Loader=loader)
+        config_dict = yaml.load(source, Loader=loader)  # noqa: S506
     except ScannerError as e:
         location = e.problem_mark or e.context_mark
         formatted_location = f" at line {location.line+1}, column {location.column+1}" if location is not None else ""
         cause = e.problem or e.context
         raise InvalidConfigError(f"Invalid YAML{formatted_location}: {cause or ''}") from e
 
     config_dict = dict_manipulator(config_dict)
@@ -76,15 +76,18 @@
             data=config_dict, data_class=config_type, config=dacite.Config(strict=True, cast=[Enum, TimeIntervalConfig])
         )
     except dacite.UnexpectedDataError as e:
         unknowns = [f'"{k.replace("_", "-") if case_style == "hyphen" else k}"' for k in e.keys]
         raise InvalidConfigError(f"Unknown config parameter{'s' if len(unknowns) > 1 else ''} {', '.join(unknowns)}")
 
     except (dacite.WrongTypeError, dacite.MissingValueError, dacite.UnionMatchError) as e:
-        path = e.field_path.replace("_", "-") if case_style == "hyphen" else e.field_path
+        if e.field_path:
+            path = e.field_path.replace("_", "-") if case_style == "hyphen" else e.field_path
+        else:
+            path = None
 
         def name(type_: Type) -> str:
             return type_.__name__ if hasattr(type_, "__name__") else str(type_)
 
         def all_types(type_: Type) -> Iterable[Type]:
             return type_.__args__ if hasattr(type_, "__args__") else [type_]
 
@@ -102,15 +105,18 @@
 
     config._file_hash = sha256(json.dumps(config_dict).encode("utf-8")).hexdigest()
 
     return config
 
 
 def load_yaml(
-    source: Union[TextIO, str], config_type: Type[CustomConfigClass], case_style: str = "hyphen", expand_envvars=True
+    source: Union[TextIO, str],
+    config_type: Type[CustomConfigClass],
+    case_style: str = "hyphen",
+    expand_envvars: bool = True,
 ) -> CustomConfigClass:
     """
     Read a YAML file, and create a config object based on its contents.
 
     Args:
         source: Input stream (as returned by open(...)) or string containing YAML.
         config_type: Class of config type (i.e. your custom subclass of BaseConfig).
@@ -131,15 +137,15 @@
     def __init__(self, config_path: str, config_type: Type[CustomConfigClass]):
         self.config_path = config_path
         self.config_type = config_type
 
         self._config: Optional[CustomConfigClass] = None
         self._next_config: Optional[CustomConfigClass] = None
 
-    def _reload_file(self):
+    def _reload_file(self) -> None:
         with open(self.config_path, "r") as stream:
             self._config_text = stream.read()
 
     @property
     def is_remote(self) -> bool:
         raw_config_type = yaml.safe_load(self._config_text).get("type")
         if raw_config_type is None:
@@ -148,25 +154,25 @@
         config_type = ConfigType(raw_config_type)
         return config_type == ConfigType.REMOTE
 
     @property
     def has_changed(self) -> bool:
         try:
             self._resolve_config()
-        except Exception as e:
+        except Exception:
             _logger.exception("Failed to reload configuration file")
             return False
-        return self._config._file_hash != self._next_config._file_hash
+        return self._config._file_hash != self._next_config._file_hash if self._config else True  # type: ignore
 
     @property
     def config(self) -> CustomConfigClass:
         if self._config is None:
             self._resolve_config()
             self.accept_new_config()
-        return self._config
+        return self._config  # type: ignore
 
     def accept_new_config(self) -> None:
         self._config = self._next_config
 
     @classmethod
     def from_cli(
         cls, name: str, description: str, version: str, config_type: Type[CustomConfigClass]
@@ -192,31 +198,33 @@
             "token_url": local_part.cognite.idp_authentication.token_url,
             "resource": local_part.cognite.idp_authentication.resource,
             "authority": local_part.cognite.idp_authentication.authority,
         }
         if local_part.cognite.host is not None:
             remote_part["cognite"]["host"] = local_part.cognite.host
         remote_part["cognite"]["project"] = local_part.cognite.project
+
+        # Ignoring None type, extraction pipelines is required at this point
         remote_part["cognite"]["extraction-pipeline"] = {}
-        remote_part["cognite"]["extraction-pipeline"]["id"] = local_part.cognite.extraction_pipeline.id
+        remote_part["cognite"]["extraction-pipeline"]["id"] = local_part.cognite.extraction_pipeline.id  # type: ignore
         remote_part["cognite"]["extraction-pipeline"][
             "external_id"
-        ] = local_part.cognite.extraction_pipeline.external_id
+        ] = local_part.cognite.extraction_pipeline.external_id  # type: ignore
 
         return remote_part
 
     def _resolve_config(self) -> None:
         self._reload_file()
 
         if self.is_remote:
             _logger.debug("Loading remote config file")
-            tmp_config: _BaseConfig = load_yaml(self._config_text, _BaseConfig)
+            tmp_config: _BaseConfig = load_yaml(self._config_text, _BaseConfig)  # type: ignore
             client = tmp_config.cognite.get_cognite_client("config_resolver")
             response = client.extraction_pipelines.config.retrieve(
-                tmp_config.cognite.get_extraction_pipeline(client).external_id
+                tmp_config.cognite.get_extraction_pipeline(client).external_id  # type: ignore  # ignoring extpipe None
             )
 
             self._next_config = _load_yaml(
                 source=response.config,
                 config_type=self.config_type,
                 dict_manipulator=lambda d: self._inject_cognite(tmp_config, d),
             )
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/exceptions.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/exceptions.py`

 * *Files identical despite different names*

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/metrics.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/metrics.py`

 * *Files 2% similar despite different names*

```diff
@@ -39,31 +39,36 @@
 
 import logging
 import os
 import threading
 from abc import ABC, abstractmethod
 from threading import Event
 from time import sleep
-from typing import Any, Callable, Dict, List, Optional, T, Tuple, Type, Union
+from types import TracebackType
+from typing import Any, Callable, Dict, List, Optional, Tuple, Type, TypeVar, Union
 
 import arrow
 import psutil
-from cognite.client import CogniteClient
-from cognite.client.data_classes import Asset, TimeSeries
-from cognite.client.exceptions import CogniteDuplicatedError
 from prometheus_client import Gauge, Info, Metric
 from prometheus_client.core import REGISTRY
 from prometheus_client.exposition import basic_auth_handler, delete_from_gateway, pushadd_to_gateway
 
+from cognite.client import CogniteClient
+from cognite.client.data_classes import Asset, Datapoints, DatapointsArray, TimeSeries
+from cognite.client.exceptions import CogniteDuplicatedError
+
 from .util import ensure_time_series
 
 _metrics_singularities = {}
 
 
-def safe_get(cls: Type[T], *args, **kwargs) -> T:
+T = TypeVar("T")
+
+
+def safe_get(cls: Type[T], *args: Any, **kwargs: Any) -> T:
     """
     A factory for instances of metrics collections.
 
     Since Prometheus doesn't allow multiple metrics with the same name, any subclass of BaseMetrics must never be
     created more than once. This function creates an instance of the given class on the first call and stores it, any
     subsequent calls with the same class as argument will return the same instance.
 
@@ -222,15 +227,17 @@
 
         Returns:
             self
         """
         self.start()
         return self
 
-    def __exit__(self, exc_type, exc_val, exc_tb) -> None:
+    def __exit__(
+        self, exc_type: Optional[Type[BaseException]], exc_val: Optional[BaseException], exc_tb: Optional[TracebackType]
+    ) -> None:
         """
         Wraps around stop method, for use as context manager
 
         Args:
             exc_type: Exception type
             exc_val: Exception value
             exc_tb: Traceback
@@ -266,15 +273,15 @@
 
         self.username = username
         self.job_name = job_name
         self.password = password
 
         self.url = url
 
-    def _auth_handler(self, url: str, method: str, timeout: int, headers: Dict[str, str], data: Any) -> Callable:
+    def _auth_handler(self, url: str, method: str, timeout: int, headers: List[Tuple[str, str]], data: Any) -> Callable:
         """
         Returns a authentication handler against the Prometheus Pushgateway to use in the pushadd_to_gateway method.
 
         Args:
             url:      Push gateway
             method:   HTTP method
             timeout:  Request timeout (seconds)
@@ -294,15 +301,15 @@
             return
 
         try:
             pushadd_to_gateway(self.url, job=self.job_name, registry=REGISTRY, handler=self._auth_handler)
 
         except OSError as exp:
             self.logger.warning("Failed to push metrics to %s: %s", self.url, str(exp))
-        except:
+        except Exception:
             self.logger.exception("Failed to push metrics to %s", self.url)
 
         self.logger.debug("Pushed metrics to %s", self.url)
 
     def clear_gateway(self) -> None:
         """
         Delete metrics stored at the gateway (reset gateway).
@@ -350,14 +357,15 @@
         """
         Initialize the CDF tenant with the necessary time series and asset.
         """
         time_series: List[TimeSeries] = []
 
         if self.asset is not None:
             # Ensure that asset exist, and retrieve internal ID
+            asset: Optional[Asset]
             try:
                 asset = self.cdf_client.assets.create(self.asset)
             except CogniteDuplicatedError:
                 asset = self.cdf_client.assets.retrieve(external_id=self.asset.external_id)
 
             asset_id = asset.id if asset is not None else None
 
@@ -370,27 +378,27 @@
 
                 time_series.append(
                     TimeSeries(
                         external_id=external_id,
                         name=metric.name,
                         legacy_name=external_id,
                         description=metric.documentation,
-                        asset_id=asset_id,
+                        asset_id=asset_id,  # type: ignore  # this is optional. Type hint in SDK is wrong
                     )
                 )
 
         ensure_time_series(self.cdf_client, time_series)
 
     def _push_to_server(self) -> None:
         """
         Create datapoints an push them to their respective time series
         """
         timestamp = int(arrow.get().float_timestamp * 1000)
 
-        datapoints: List[Dict[str, Union[str, List[Tuple[float, float]]]]] = []
+        datapoints: List[Dict[str, Union[str, int, List[Any], Datapoints, DatapointsArray]]] = []
 
         for metric in REGISTRY.collect():
             if type(metric) == Metric and metric.type in ["gauge", "counter"]:
                 if len(metric.samples) == 0:
                     continue
 
                 external_id = self.external_id_prefix + metric.name
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/middleware.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/middleware.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,18 +1,23 @@
+"""
+This module is deprecated and will be removed in a future version
+"""
+
+
 from sys import platform
-from typing import Union
+from typing import Any, Union
 
-from cognite.client.data_classes import Event, Row
+from cognite.client.data_classes import Row
 
 
 class JQMiddleware:
     def __init__(self, jq_rules: str) -> None:
         if platform == "win32":
             raise Exception("Windows platform doesn't support jq bindings for Python yet")
-        import jq
+        import jq  # type: ignore
 
         self._jq = jq.compile(jq_rules)
 
     def __call__(self, data: Union[Row, dict]) -> Union[Row, dict]:
         if not isinstance(data, (Row, dict)):
             raise ValueError(f"type {type(data).__name__} is not currently supported")
 
@@ -22,10 +27,10 @@
 
         if isinstance(data, dict):
             data = self._jq.input(data).first()
             self._raise_for_non_dict(data)
 
         return data
 
-    def _raise_for_non_dict(self, data):
+    def _raise_for_non_dict(self, data: Any) -> None:
         if not isinstance(data, dict):
             raise ValueError("output of jq middleware must be a dict")
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/statestore.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/statestore.py`

 * *Files 2% similar despite different names*

```diff
@@ -85,22 +85,21 @@
 
 """
 
 import json
 import logging
 import threading
 from abc import ABC, abstractmethod
-from decimal import Decimal
-from threading import Lock
-from typing import Any, Callable, Dict, List, Optional, Tuple, Union
+from types import TracebackType
+from typing import Any, Callable, Dict, List, Optional, Tuple, Type, Union
 
-from cognite.client import CogniteClient
-from cognite.client.exceptions import CogniteAPIError
 from requests.exceptions import ConnectionError
 
+from cognite.client import CogniteClient
+from cognite.client.exceptions import CogniteAPIError
 from cognite.extractorutils.uploader import DataPointList
 
 from ._inner_util import _DecimalDecoder, _DecimalEncoder, _resolve_log_level
 from .util import retry
 
 RETRY_BACKOFF_FACTOR = 1.5
 RETRY_MAX_DELAY = 15
@@ -136,16 +135,14 @@
 
         self.thread = threading.Thread(target=self._run, daemon=True, name=thread_name)
         self.lock = threading.RLock()
         self.cancellation_token: threading.Event = cancellation_token
 
         self._deleted: List[str] = []
 
-        self.lock = Lock()
-
     def start(self) -> None:
         """
         Start saving state periodically if save_interval is set.
         This calls the synchronize method every save_interval seconds.
         """
         if self.save_interval is not None:
             self.cancellation_token.clear()
@@ -199,20 +196,20 @@
             external_id: An external ID or list of external IDs to get states for
 
         Returns:
             A tuple with (low, high) watermarks, or a list of tuples
         """
         with self.lock:
             if isinstance(external_id, list):
-                l = []
+                states = []
                 for e in external_id:
                     state = self._local_state.get(e, {})
-                    l.append((state.get("low"), state.get("high")))
+                    states.append((state.get("low"), state.get("high")))
 
-                return l
+                return states
 
             else:
                 state = self._local_state.get(external_id, {})
                 return state.get("low"), state.get("high")
 
     def set_state(self, external_id: str, low: Optional[Any] = None, high: Optional[Any] = None) -> None:
         """
@@ -259,22 +256,22 @@
         Get a callable suitable for passing to a time series upload queue as post_upload_function, that will
         automatically update the states in this state store when that upload queue is uploading.
 
         Returns:
             A function that expands the current states with the values given
         """
 
-        def callback(uploaded_points: List[Dict[str, Union[str, DataPointList]]]):
+        def callback(uploaded_points: List[Dict[str, Union[str, DataPointList]]]) -> None:
             for time_series in uploaded_points:
                 # Use CDF timestamps
                 data_points = time_series["datapoints"]
                 if data_points:
                     high = max(data_points)[0]
                     low = min(data_points)[0]
-                    external_id = time_series["externalId"]
+                    external_id: str = time_series["externalId"]  # type: ignore  # known to be str from where we set it
                     self.expand_state(external_id, low, high)
 
         return callback
 
     def outside_state(self, external_id: str, new_state: Any) -> bool:
         """
         Check if a new proposed state is outside state interval (ie, if a new datapoint should be processed).
@@ -297,15 +294,15 @@
             return True
         if low is not None and new_state < low:
             return True
 
         return False
 
     def __getitem__(self, external_id: str) -> Tuple[Any, Any]:
-        return self.get_state(external_id)
+        return self.get_state(external_id)  # type: ignore  # will not be list if input is single str
 
     def __setitem__(self, key: str, value: Tuple[Any, Any]) -> None:
         self.set_state(external_id=key, low=value[0], high=value[1])
 
     def __contains__(self, external_id: str) -> bool:
         return external_id in self._local_state
 
@@ -378,15 +375,16 @@
 
         Args:
             force: Enable re-initialization, ie overwrite when called multiple times
         """
         if self._initialized and not force:
             return
 
-        rows = self._cdf_client.raw.rows.list(db_name=self.database, table_name=self.table, limit=None)
+        # ignore type since list _is_ optional, sdk types are wrong
+        rows = self._cdf_client.raw.rows.list(db_name=self.database, table_name=self.table, limit=None)  # type: ignore
 
         with self.lock:
             self._local_state.clear()
             for row in rows:
                 self._local_state[row.key] = row.columns
 
         self._initialized = True
@@ -418,15 +416,17 @@
 
         Returns:
             self
         """
         self.start()
         return self
 
-    def __exit__(self, exc_type, exc_val, exc_tb) -> None:
+    def __exit__(
+        self, exc_type: Optional[Type[BaseException]], exc_val: Optional[BaseException], exc_tb: Optional[TracebackType]
+    ) -> None:
         """
         Wraps around stop method, for use as context manager
 
         Args:
             exc_type: Exception type
             exc_val: Exception value
             exc_tb: Traceback
@@ -496,15 +496,17 @@
 
         Returns:
             self
         """
         self.start()
         return self
 
-    def __exit__(self, exc_type, exc_val, exc_tb) -> None:
+    def __exit__(
+        self, exc_type: Optional[Type[BaseException]], exc_val: Optional[BaseException], exc_tb: Optional[TracebackType]
+    ) -> None:
         """
         Wraps around stop method, for use as context manager
 
         Args:
             exc_type: Exception type
             exc_val: Exception value
             exc_tb: Traceback
@@ -513,15 +515,15 @@
 
 
 class NoStateStore(AbstractStateStore):
     """
     A state store that only keeps states in memory and never stores or initializes from external sources.
     """
 
-    def __init__(self):
+    def __init__(self) -> None:
         super().__init__()
 
     def initialize(self, force: bool = False) -> None:
         pass
 
     def synchronize(self) -> None:
         pass
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader/__init__.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader/__init__.py`

 * *Files identical despite different names*

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader/_base.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader/_base.py`

 * *Files 9% similar despite different names*

```diff
@@ -15,16 +15,16 @@
 import logging
 import threading
 from abc import ABC, abstractmethod
 from dataclasses import dataclass
 from typing import Any, Callable, List, Optional
 
 from arrow import Arrow
-from cognite.client import CogniteClient
 
+from cognite.client import CogniteClient
 from cognite.extractorutils._inner_util import _resolve_log_level
 
 
 class AbstractUploadQueue(ABC):
     """
     Abstract uploader class.
 
@@ -84,25 +84,18 @@
 
         Args:
             uploaded: List of uploaded data
         """
         if self.post_upload_function is not None:
             try:
                 self.post_upload_function(uploaded)
-            except Exception as e:
+            except Exception:
                 logging.getLogger(__name__).exception("Error during upload callback")
 
     @abstractmethod
-    def add_to_upload_queue(self, *args) -> None:
-        """
-        Adds an element to the upload queue. The queue will be uploaded if the queue byte size is larger than the
-        threshold specified in the config.
-        """
-
-    @abstractmethod
     def upload(self) -> None:
         """
         Uploads the queue.
         """
 
     def _run(self) -> None:
         """
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader/_metrics.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader/_metrics.py`

 * *Files identical despite different names*

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader/events.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader/events.py`

 * *Files 3% similar despite different names*

```diff
@@ -9,22 +9,23 @@
 #  Unless required by applicable law or agreed to in writing, software
 #  distributed under the License is distributed on an "AS IS" BASIS,
 #  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #  See the License for the specific language governing permissions and
 #  limitations under the License.
 
 import threading
-from typing import Callable, List, Optional
+from types import TracebackType
+from typing import Callable, List, Optional, Type
 
 import arrow
-from cognite.client import CogniteClient
-from cognite.client.data_classes import Event
-from cognite.client.exceptions import CogniteAPIError
 from requests import ConnectionError
 
+from cognite.client import CogniteClient
+from cognite.client.data_classes import Event
+from cognite.client.exceptions import CogniteAPIError, CogniteDuplicatedError
 from cognite.extractorutils.uploader._base import (
     RETRIES,
     RETRY_BACKOFF_FACTOR,
     RETRY_DELAY,
     RETRY_MAX_DELAY,
     AbstractUploadQueue,
 )
@@ -127,28 +128,45 @@
     @retry(
         exceptions=(CogniteAPIError, ConnectionError),
         tries=RETRIES,
         delay=RETRY_DELAY,
         max_delay=RETRY_MAX_DELAY,
         backoff=RETRY_BACKOFF_FACTOR,
     )
-    def _upload_batch(self):
-        self.cdf_client.events.create([e for e in self.upload_queue])
+    def _upload_batch(self) -> None:
+        try:
+            self.cdf_client.events.create([e for e in self.upload_queue])
+        except CogniteDuplicatedError as e:
+            duplicated_ids = set([dup["externalId"] for dup in e.duplicated if "externalId" in dup])
+            failed: List[Event] = [e for e in e.failed]
+            to_create = []
+            to_update = []
+            for evt in failed:
+                if evt.external_id is not None and evt.external_id in duplicated_ids:
+                    to_update.append(evt)
+                else:
+                    to_create.append(evt)
+            if to_create:
+                self.cdf_client.events.create(to_create)
+            if to_update:
+                self.cdf_client.events.update(to_update)
 
     def __enter__(self) -> "EventUploadQueue":
         """
         Wraps around start method, for use as context manager
 
         Returns:
             self
         """
         self.start()
         return self
 
-    def __exit__(self, exc_type, exc_val, exc_tb) -> None:
+    def __exit__(
+        self, exc_type: Optional[Type[BaseException]], exc_val: Optional[BaseException], exc_tb: Optional[TracebackType]
+    ) -> None:
         """
         Wraps around stop method, for use as context manager
 
         Args:
             exc_type: Exception type
             exc_val: Exception value
             exc_tb: Traceback
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader/files.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader/files.py`

 * *Files 2% similar despite different names*

```diff
@@ -11,22 +11,23 @@
 #  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #  See the License for the specific language governing permissions and
 #  limitations under the License.
 
 import threading
 from concurrent.futures import ThreadPoolExecutor
 from os import PathLike
-from typing import Any, Callable, List, Optional, Tuple, Union
+from types import TracebackType
+from typing import Any, Callable, List, Optional, Tuple, Type, Union
 
 import arrow
+from requests import ConnectionError
+
 from cognite.client import CogniteClient
 from cognite.client.data_classes import Event, FileMetadata
 from cognite.client.exceptions import CogniteAPIError
-from requests import ConnectionError
-
 from cognite.extractorutils.uploader._base import (
     RETRIES,
     RETRY_BACKOFF_FACTOR,
     RETRY_DELAY,
     RETRY_MAX_DELAY,
     AbstractUploadQueue,
 )
@@ -85,15 +86,15 @@
 
         self.files_queued = FILES_UPLOADER_QUEUED
         self.files_written = FILES_UPLOADER_WRITTEN
         self.queue_size = FILES_UPLOADER_QUEUE_SIZE
         self.latency = FILES_UPLOADER_LATENCY
         self.latency_zero_point = arrow.utcnow()
 
-    def add_to_upload_queue(self, file_meta: FileMetadata, file_name: Union[str, PathLike] = None) -> None:
+    def add_to_upload_queue(self, file_meta: FileMetadata, file_name: Union[str, PathLike]) -> None:
         """
         Add file to upload queue. The queue will be uploaded if the queue size is larger than the threshold
         specified in the __init__.
 
         Args:
             file_meta: File metadata-object
             file_name: Path to file to be uploaded.
@@ -137,22 +138,22 @@
     @retry(
         exceptions=(CogniteAPIError, ConnectionError),
         tries=RETRIES,
         delay=RETRY_DELAY,
         max_delay=RETRY_MAX_DELAY,
         backoff=RETRY_BACKOFF_FACTOR,
     )
-    def _upload_single(self, index, file_name, file_meta):
+    def _upload_single(self, index: int, file_name: Union[str, PathLike], file_meta: FileMetadata) -> None:
         # Upload file
-        file_meta = self.cdf_client.files.upload(file_name, overwrite=self.overwrite_existing, **file_meta.dump())
+        file_meta = self.cdf_client.files.upload(str(file_name), overwrite=self.overwrite_existing, **file_meta.dump())  # type: ignore
 
         # Update meta-object in queue
         self.upload_queue[index] = (file_meta, file_name)
 
-    def _upload_batch(self):
+    def _upload_batch(self) -> None:
         # Concurrently execute file-uploads
 
         with ThreadPoolExecutor(self.cdf_client.config.max_workers) as pool:
             for i, (file_meta, file_name) in enumerate(self.upload_queue):
                 pool.submit(self._upload_single, i, file_name, file_meta)
 
     def __enter__(self) -> "FileUploadQueue":
@@ -161,15 +162,17 @@
 
         Returns:
             self
         """
         self.start()
         return self
 
-    def __exit__(self, exc_type, exc_val, exc_tb) -> None:
+    def __exit__(
+        self, exc_type: Optional[Type[BaseException]], exc_val: Optional[BaseException], exc_tb: Optional[TracebackType]
+    ) -> None:
         """
         Wraps around stop method, for use as context manager
 
         Args:
             exc_type: Exception type
             exc_val: Exception value
             exc_tb: Traceback
@@ -208,15 +211,15 @@
         post_upload_function: Optional[Callable[[List[Any]], None]] = None,
         max_queue_size: Optional[int] = None,
         max_upload_interval: Optional[int] = None,
         trigger_log_level: str = "DEBUG",
         thread_name: Optional[str] = None,
         overwrite_existing: bool = False,
         cancellation_token: threading.Event = threading.Event(),
-    ):
+    ) -> None:
         super().__init__(
             cdf_client,
             post_upload_function,
             max_queue_size,
             max_upload_interval,
             trigger_log_level,
             thread_name,
@@ -273,28 +276,28 @@
 
             # Clear queue
             self.upload_queue.clear()
             self.upload_queue_size = 0
             self.logger.info(f"Uploaded {self.upload_queue_size} files")
             self.queue_size.set(self.upload_queue_size)
 
-    def _upload_batch(self):
+    def _upload_batch(self) -> None:
         # Concurrently execute bytes-uploads
         with ThreadPoolExecutor(self.cdf_client.config.max_workers) as pool:
             for i, (frame, metadata) in enumerate(self.upload_queue):
                 pool.submit(self._upload_single, i, frame, metadata)
 
     @retry(
         exceptions=(CogniteAPIError, ConnectionError),
         tries=RETRIES,
         delay=RETRY_DELAY,
         max_delay=RETRY_MAX_DELAY,
         backoff=RETRY_BACKOFF_FACTOR,
     )
-    def _upload_single(self, index: int, content: bytes, metadata: FileMetadata):
+    def _upload_single(self, index: int, content: bytes, metadata: FileMetadata) -> None:
         # Upload object
         file_meta_data: FileMetadata = self.cdf_client.files.upload_bytes(
             content, overwrite=self.overwrite_existing, **metadata.dump()
         )
 
         # Update meta-object in queue
         self.upload_queue[index] = (content, file_meta_data)
@@ -305,15 +308,17 @@
 
         Returns:
             self
         """
         self.start()
         return self
 
-    def __exit__(self, exc_type, exc_val, exc_tb) -> None:
+    def __exit__(
+        self, exc_type: Optional[Type[BaseException]], exc_val: Optional[BaseException], exc_tb: Optional[TracebackType]
+    ) -> None:
         """
         Wraps around stop method, for use as context manager
 
         Args:
             exc_type: Exception type
             exc_val: Exception value
             exc_tb: Traceback
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader/raw.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader/raw.py`

 * *Files 6% similar despite different names*

```diff
@@ -9,23 +9,24 @@
 #  Unless required by applicable law or agreed to in writing, software
 #  distributed under the License is distributed on an "AS IS" BASIS,
 #  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #  See the License for the specific language governing permissions and
 #  limitations under the License.
 
 import threading
-from typing import Any, Callable, Dict, List, Optional
+from types import TracebackType
+from typing import Any, Callable, Dict, List, Optional, Type
 
 import arrow
 from arrow import Arrow
+from requests import ConnectionError
+
 from cognite.client import CogniteClient
 from cognite.client.data_classes import Row
 from cognite.client.exceptions import CogniteAPIError, CogniteReadTimeout
-from requests import ConnectionError
-
 from cognite.extractorutils.uploader._base import (
     RETRIES,
     RETRY_BACKOFF_FACTOR,
     RETRY_DELAY,
     RETRY_MAX_DELAY,
     AbstractUploadQueue,
     TimestampedObject,
@@ -71,15 +72,15 @@
             post_upload_function,
             max_queue_size,
             max_upload_interval,
             trigger_log_level,
             thread_name,
             cancellation_token,
         )
-        self.upload_queue: Dict[str, Dict[str, List[TimestampedObject]]] = dict()
+        self.upload_queue: Dict[str, Dict[str, List[TimestampedObject]]] = {}
 
         # It is a hack since Prometheus client registers metrics on object creation, so object has to be created once
         self.rows_queued = RAW_UPLOADER_ROWS_QUEUED
         self.rows_written = RAW_UPLOADER_ROWS_WRITTEN
         self.rows_duplicates = RAW_UPLOADER_ROWS_DUPLICATES
         self.queue_size = RAW_UPLOADER_QUEUE_SIZE
         self.latency = RAW_UPLOADER_LATENCY
@@ -93,15 +94,15 @@
             database: The database to upload the Raw object to
             table: The table to upload the Raw object to
             raw_row: The row object
         """
         with self.lock:
             # Ensure that the dicts has correct keys
             if database not in self.upload_queue:
-                self.upload_queue[database] = dict()
+                self.upload_queue[database] = {}
             if table not in self.upload_queue[database]:
                 self.upload_queue[database][table] = []
 
             # Append row to queue
             self.upload_queue[database][table].append(TimestampedObject(payload=raw_row, created=Arrow.utcnow()))
             self.upload_queue_size += 1
             self.rows_queued.labels(f"{database}:{table}").inc()
@@ -148,29 +149,31 @@
     @retry(
         exceptions=(CogniteAPIError, ConnectionError, CogniteReadTimeout),
         tries=RETRIES,
         delay=RETRY_DELAY,
         max_delay=RETRY_MAX_DELAY,
         backoff=RETRY_BACKOFF_FACTOR,
     )
-    def _upload_batch(self, database: str, table: str, patch: List[Row]):
+    def _upload_batch(self, database: str, table: str, patch: List[Row]) -> None:
         # Upload
         self.cdf_client.raw.rows.insert(db_name=database, table_name=table, row=patch, ensure_parent=True)
 
     def __enter__(self) -> "RawUploadQueue":
         """
         Wraps around start method, for use as context manager
 
         Returns:
             self
         """
         self.start()
         return self
 
-    def __exit__(self, exc_type, exc_val, exc_tb) -> None:
+    def __exit__(
+        self, exc_type: Optional[Type[BaseException]], exc_val: Optional[BaseException], exc_tb: Optional[TracebackType]
+    ) -> None:
         """
         Wraps around stop method, for use as context manager
 
         Args:
             exc_type: Exception type
             exc_val: Exception value
             exc_tb: Traceback
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader/time_series.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader/time_series.py`

 * *Files 4% similar despite different names*

```diff
@@ -11,22 +11,23 @@
 #  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #  See the License for the specific language governing permissions and
 #  limitations under the License.
 
 import math
 import threading
 from datetime import datetime
-from typing import Any, Callable, Dict, List, Optional, Tuple, Union
+from types import TracebackType
+from typing import Any, Callable, Dict, List, Optional, Tuple, Type, Union
 
 import arrow
+from requests import ConnectionError
+
 from cognite.client import CogniteClient
 from cognite.client.data_classes import Sequence, SequenceData, TimeSeries
 from cognite.client.exceptions import CogniteAPIError, CogniteDuplicatedError, CogniteNotFoundError
-from requests import ConnectionError
-
 from cognite.extractorutils.uploader._base import (
     RETRIES,
     RETRY_BACKOFF_FACTOR,
     RETRY_DELAY,
     RETRY_MAX_DELAY,
     AbstractUploadQueue,
 )
@@ -44,17 +45,15 @@
 from cognite.extractorutils.util import EitherId, retry
 
 MIN_DATAPOINT_TIMESTAMP = 31536000000
 MAX_DATAPOINT_STRING_LENGTH = 255
 MAX_DATAPOINT_VALUE = 1e100
 MIN_DATAPOINT_VALUE = -1e100
 
-DataPoint = Union[
-    Dict[str, Union[int, float, str, datetime]], Tuple[Union[int, float, datetime], Union[int, float, str]]
-]
+DataPoint = Tuple[Union[int, float, datetime], Union[int, float, str]]
 DataPointList = List[DataPoint]
 
 
 def default_time_series_factory(external_id: str, datapoints: DataPointList) -> TimeSeries:
     """
     Default time series factory used when create_missing in a TimeSeriesUploadQueue is given as a boolean.
 
@@ -62,15 +61,15 @@
         external_id: External ID of time series to create
         datapoints: The list of datapoints that were tried to be inserted
 
     Returns:
         A TimeSeries object with external_id set, and the is_string automatically detected
     """
     is_string = (
-        isinstance(datapoints[0].get("value"), str)
+        isinstance(datapoints[0].get("value"), str)  # type: ignore  # input might be dict to keep compatibility
         if isinstance(datapoints[0], dict)
         else isinstance(datapoints[0][1], str)
     )
     return TimeSeries(external_id=external_id, is_string=is_string)
 
 
 class TimeSeriesUploadQueue(AbstractUploadQueue):
@@ -114,58 +113,66 @@
             max_queue_size,
             max_upload_interval,
             trigger_log_level,
             thread_name,
             cancellation_token,
         )
 
+        self.missing_factory: Callable[[str, DataPointList], TimeSeries]
+
         if isinstance(create_missing, bool):
             self.create_missing = create_missing
             self.missing_factory = default_time_series_factory
         else:
             self.create_missing = True
             self.missing_factory = create_missing
 
-        self.upload_queue: Dict[EitherId, DataPointList] = dict()
+        self.upload_queue: Dict[EitherId, DataPointList] = {}
 
         self.points_queued = TIMESERIES_UPLOADER_POINTS_QUEUED
         self.points_written = TIMESERIES_UPLOADER_POINTS_WRITTEN
         self.queue_size = TIMESERIES_UPLOADER_QUEUE_SIZE
         self.latency = TIMESERIES_UPLOADER_LATENCY
         self.latency_zero_point = arrow.utcnow()
         self.data_set_id = data_set_id
 
-    def _verify_datapoint_time(self, time: Union[int, float, datetime]) -> bool:
+    def _verify_datapoint_time(self, time: Union[int, float, datetime, str]) -> bool:
         if isinstance(time, int) or isinstance(time, float):
             return not math.isnan(time) and time >= MIN_DATAPOINT_TIMESTAMP
+        elif isinstance(time, str):
+            return False
         else:
             return time.timestamp() * 1000.0 >= MIN_DATAPOINT_TIMESTAMP
 
-    def _verify_datapoint_value(self, value: Union[int, float, str]) -> bool:
+    def _verify_datapoint_value(self, value: Union[int, float, datetime, str]) -> bool:
         if isinstance(value, float):
             return not (
                 math.isnan(value) or math.isinf(value) or value > MAX_DATAPOINT_VALUE or value < MIN_DATAPOINT_VALUE
             )
         elif isinstance(value, str):
             return len(value) <= MAX_DATAPOINT_STRING_LENGTH
+        elif isinstance(value, datetime):
+            return False
         else:
             return True
 
     def _is_datapoint_valid(
         self,
         dp: DataPoint,
     ) -> bool:
-        if isinstance(dp, Dict):
+        if isinstance(dp, dict):
             return self._verify_datapoint_time(dp["timestamp"]) and self._verify_datapoint_value(dp["value"])
-        elif isinstance(dp, Tuple):
+        elif isinstance(dp, tuple):
             return self._verify_datapoint_time(dp[0]) and self._verify_datapoint_value(dp[1])
         else:
             return True
 
-    def add_to_upload_queue(self, *, id: int = None, external_id: str = None, datapoints: DataPointList = []) -> None:
+    def add_to_upload_queue(
+        self, *, id: Optional[int] = None, external_id: Optional[str] = None, datapoints: DataPointList = []
+    ) -> None:
         """
         Add data points to upload queue. The queue will be uploaded if the queue size is larger than the threshold
         specified in the __init__.
 
         Args:
             id: Internal ID of time series. Either this or external_id must be set.
             external_id: External ID of time series. Either this or external_id must be set.
@@ -232,15 +239,15 @@
     @retry(
         exceptions=(CogniteAPIError, ConnectionError),
         tries=RETRIES,
         delay=RETRY_DELAY,
         max_delay=RETRY_MAX_DELAY,
         backoff=RETRY_BACKOFF_FACTOR,
     )
-    def _upload_batch(self, upload_this: List[Dict], retries=5) -> List[Dict]:
+    def _upload_batch(self, upload_this: List[Dict], retries: int = 5) -> List[Dict]:
         if len(upload_this) == 0:
             return upload_this
 
         try:
             self.cdf_client.time_series.data.insert_multiple(upload_this)
 
         except CogniteNotFoundError as ex:
@@ -272,16 +279,17 @@
                             ts.data_set_id = self.data_set_id
                 self.cdf_client.time_series.create(to_create)
 
                 retry_these.extend([EitherId(external_id=i) for i in create_these_ids])
 
                 if len(ex.not_found) != len(create_these_ids):
                     missing = [id_dict for id_dict in ex.not_found if id_dict.get("externalId") not in retry_these]
+                    missing_num = len(ex.not_found) - len(create_these_ids)
                     self.logger.error(
-                        f"{len(ex.not_found) - len(create_these_ids)} time series not found, and could not be created automatically:\n"
+                        f"{missing_num} time series not found, and could not be created automatically:\n"
                         + str(missing)
                         + "\nData will be dropped"
                     )
 
             # Remove entries with non-existing time series from upload queue
             upload_this = [
                 entry
@@ -300,15 +308,17 @@
 
         Returns:
             self
         """
         self.start()
         return self
 
-    def __exit__(self, exc_type, exc_val, exc_tb) -> None:
+    def __exit__(
+        self, exc_type: Optional[Type[BaseException]], exc_val: Optional[BaseException], exc_tb: Optional[TracebackType]
+    ) -> None:
         """
         Wraps around stop method, for use as context manager
 
         Args:
             exc_type: Exception type
             exc_val: Exception value
             exc_tb: Traceback
@@ -330,22 +340,22 @@
         self,
         cdf_client: CogniteClient,
         post_upload_function: Optional[Callable[[List[Any]], None]] = None,
         max_queue_size: Optional[int] = None,
         max_upload_interval: Optional[int] = None,
         trigger_log_level: str = "DEBUG",
         thread_name: Optional[str] = None,
-        create_missing=False,
+        create_missing: bool = False,
         cancellation_token: threading.Event = threading.Event(),
     ):
         """
         Args:
             cdf_client: Cognite Data Fusion client to use
-            post_upload_function: A function that will be called after each upload. The function will be given one argument:
-                A list of the events that were uploaded.
+            post_upload_function: A function that will be called after each upload. The function will be given one
+                argument: A list of the events that were uploaded.
             max_queue_size: Maximum size of upload queue. Defaults to no max size.
             max_upload_interval: Automatically trigger an upload each m seconds when run as a thread (use start/stop
                 methods).
             trigger_log_level: Log level to log upload triggers to.
             thread_name: Thread name of uploader thread.
             create_missing: Create missing sequences if possible (ie, if external id is used)
         """
@@ -356,40 +366,40 @@
             post_upload_function,
             max_queue_size,
             max_upload_interval,
             trigger_log_level,
             thread_name,
             cancellation_token,
         )
-        self.upload_queue: Dict[EitherId, SequenceData] = dict()
-        self.sequence_metadata: Dict[EitherId, Dict[str, Union[str, int, float]]] = dict()
-        self.sequence_asset_external_ids: Dict[EitherId, str] = dict()
-        self.sequence_dataset_external_ids: Dict[EitherId, str] = dict()
-        self.sequence_names: Dict[EitherId, str] = dict()
-        self.sequence_descriptions: Dict[EitherId, str] = dict()
-        self.column_definitions: Dict[EitherId, List[Dict[str, str]]] = dict()
-        self.asset_ids: Dict[str, int] = dict()
-        self.dataset_ids: Dict[str, int] = dict()
+        self.upload_queue: Dict[EitherId, SequenceData] = {}
+        self.sequence_metadata: Dict[EitherId, Dict[str, Union[str, int, float]]] = {}
+        self.sequence_asset_external_ids: Dict[EitherId, str] = {}
+        self.sequence_dataset_external_ids: Dict[EitherId, str] = {}
+        self.sequence_names: Dict[EitherId, str] = {}
+        self.sequence_descriptions: Dict[EitherId, str] = {}
+        self.column_definitions: Dict[EitherId, List[Dict[str, str]]] = {}
+        self.asset_ids: Dict[str, int] = {}
+        self.dataset_ids: Dict[str, int] = {}
         self.create_missing = create_missing
 
         self.points_queued = SEQUENCES_UPLOADER_POINTS_QUEUED
         self.points_written = SEQUENCES_UPLOADER_POINTS_WRITTEN
         self.queue_size = SEQUENCES_UPLOADER_QUEUE_SIZE
         self.latency = SEQUENCES_UPLOADER_LATENCY
         self.latency_zero_point = arrow.utcnow()
 
     def set_sequence_metadata(
         self,
         metadata: Dict[str, Union[str, int, float]],
-        id: int = None,
-        external_id: str = None,
-        asset_external_id: str = None,
-        dataset_external_id: str = None,
-        name: str = None,
-        description: str = None,
+        id: Optional[int] = None,
+        external_id: Optional[str] = None,
+        asset_external_id: Optional[str] = None,
+        dataset_external_id: Optional[str] = None,
+        name: Optional[str] = None,
+        description: Optional[str] = None,
     ) -> None:
         """
         Set sequence metadata. Metadata will be cached until the sequence is created. The metadata will be updated
         if the sequence already exists
 
         Args:
             metadata: Sequence metadata
@@ -400,21 +410,25 @@
             asset_external_id: Sequence asset external ID
             dataset_external_id: Sequence dataset external ID
             name: Sequence name
             description: Sequence description
         """
         either_id = EitherId(id=id, external_id=external_id)
         self.sequence_metadata[either_id] = metadata
-        self.sequence_asset_external_ids[either_id] = asset_external_id
-        self.sequence_dataset_external_ids[either_id] = dataset_external_id
-        self.sequence_names[either_id] = name
-        self.sequence_descriptions[either_id] = description
+        if asset_external_id:
+            self.sequence_asset_external_ids[either_id] = asset_external_id
+        if dataset_external_id:
+            self.sequence_dataset_external_ids[either_id] = dataset_external_id
+        if name:
+            self.sequence_names[either_id] = name
+        if description:
+            self.sequence_descriptions[either_id] = description
 
     def set_sequence_column_definition(
-        self, col_def: List[Dict[str, str]], id: int = None, external_id: str = None
+        self, col_def: List[Dict[str, str]], id: Optional[int] = None, external_id: Optional[str] = None
     ) -> None:
         """
         Set sequence column definition
 
         Args:
             col_def: Sequence column definition
             id: Sequence internal ID
@@ -430,16 +444,16 @@
         rows: Union[
             Dict[int, List[Union[int, float, str]]],
             List[Tuple[int, Union[int, float, str]]],
             List[Dict[str, Any]],
             SequenceData,
         ],
         column_external_ids: Optional[List[dict]] = None,
-        id: int = None,
-        external_id: str = None,
+        id: Optional[int] = None,
+        external_id: Optional[str] = None,
     ) -> None:
         """
         Add sequence rows to upload queue. Mirrors implementation of SequenceApi.insert. Inserted rows will be
         cached until uploaded
 
         Args:
             rows: The rows to be inserted. Can either be a list of tuples, a list of ["rownumber": ..., "values": ...]
@@ -458,30 +472,30 @@
 
         if isinstance(rows, SequenceData):
             # Already in desired format
             pass
         elif isinstance(rows, dict):
             rows = [{"rowNumber": row_number, "values": values} for row_number, values in rows.items()]
 
-            rows = SequenceData(id=id, external_id=id, rows=rows, columns=column_external_ids)
+            rows = SequenceData(id=id, external_id=id, rows=rows, columns=column_external_ids)  # type: ignore
 
         elif isinstance(rows, list):
             if isinstance(rows[0], tuple) or isinstance(rows[0], list):
                 rows = [{"rowNumber": row_number, "values": values} for row_number, values in rows]
 
-            rows = SequenceData(id=id, external_id=id, rows=rows, columns=column_external_ids)
+            rows = SequenceData(id=id, external_id=id, rows=rows, columns=column_external_ids)  # type: ignore
         else:
             raise TypeError("Unsupported type for sequence rows: {}".format(type(rows)))
 
         with self.lock:
             seq = self.upload_queue.get(either_id)
             if seq is not None:
                 # Update sequence
-                seq.values.extend(rows.values)
-                seq.row_numbers.extend(rows.row_numbers)
+                seq.values.extend(rows.values)  # type: ignore  # type is list, mypy is wrong
+                seq.row_numbers.extend(rows.row_numbers)  # type: ignore
 
                 self.upload_queue[either_id] = seq
             else:
                 self.upload_queue[either_id] = rows
             self.upload_queue_size = len(self.upload_queue)
             self.queue_size.set(self.upload_queue_size)
             self.points_queued.inc()
@@ -513,36 +527,39 @@
 
             self.upload_queue.clear()
             self.upload_queue_size = 0
             self.logger.info(f"Uploaded {self.upload_queue_size} sequence rows")
             self.queue_size.set(self.upload_queue_size)
 
     @retry(
-        exceptions=CogniteAPIError,
+        exceptions=[CogniteAPIError],
         tries=RETRIES,
         delay=RETRY_DELAY,
         max_delay=RETRY_MAX_DELAY,
         backoff=RETRY_BACKOFF_FACTOR,
     )
     def _upload_single(self, either_id: EitherId, upload_this: SequenceData) -> SequenceData:
         self.logger.debug("Writing {} rows to sequence {}".format(len(upload_this.values), either_id))
 
         try:
             self.cdf_client.sequences.data.insert(
-                id=either_id.internal_id, external_id=either_id.external_id, rows=upload_this, column_external_ids=None
+                id=either_id.internal_id,  # type: ignore
+                external_id=either_id.external_id,  # type: ignore
+                rows=upload_this,
+                column_external_ids=None,
             )
         except CogniteNotFoundError as ex:
             if self.create_missing:
                 # Create missing sequence
                 self._create_or_update(either_id)
 
                 # Retry
                 self.cdf_client.sequences.data.insert(
-                    id=either_id.internal_id,
-                    external_id=either_id.external_id,
+                    id=either_id.internal_id,  # type: ignore
+                    external_id=either_id.external_id,  # type: ignore
                     rows=upload_this,
                     column_external_ids=None,
                 )
             else:
                 raise ex
 
         return upload_this
@@ -552,86 +569,93 @@
         Create or update sequence, based on provided metadata and column definitions
 
         Args:
             either_id: Id/External Id of sequence to be updated
         """
 
         column_def = self.column_definitions.get(either_id)
+        if column_def is None:
+            self.logger.error(f"Can't create sequence {str(either_id)}, no column definitions provided")
 
         try:
             seq = self.cdf_client.sequences.create(
                 Sequence(
-                    id=either_id.internal_id,
-                    external_id=either_id.external_id,
-                    name=self.sequence_names.get(either_id, None),
-                    description=self.sequence_descriptions.get(either_id, None),
-                    metadata=self.sequence_metadata.get(either_id, None),
-                    asset_id=self.asset_ids.get(self.sequence_asset_external_ids.get(either_id, None), None),
-                    data_set_id=self.dataset_ids.get(self.sequence_dataset_external_ids.get(either_id, None), None),
-                    columns=column_def,
+                    id=either_id.internal_id,  # type: ignore  # these are optional, the SDK types are wrong
+                    external_id=either_id.external_id,  # type: ignore
+                    name=self.sequence_names.get(either_id, None),  # type: ignore
+                    description=self.sequence_descriptions.get(either_id, None),  # type: ignore
+                    metadata=self.sequence_metadata.get(either_id, None),  # type: ignore
+                    asset_id=self.asset_ids.get(self.sequence_asset_external_ids.get(either_id, None), None),  # type: ignore
+                    data_set_id=self.dataset_ids.get(self.sequence_dataset_external_ids.get(either_id, None), None),  # type: ignore
+                    columns=column_def,  # type: ignore  # We already  checked for None, mypy is wrong
                 )
             )
 
         except CogniteDuplicatedError:
             self.logger.info("Sequnce already exist: {}".format(either_id))
-            seq = self.cdf_client.sequences.retrieve(id=either_id.internal_id, external_id=either_id.external_id)
+            seq = self.cdf_client.sequences.retrieve(
+                id=either_id.internal_id,  # type: ignore  # these are optional, the SDK types are wrong
+                external_id=either_id.external_id,  # type: ignore
+            )
 
         # Update definition of cached sequence
         cseq = self.upload_queue[either_id]
         cseq.columns = seq.columns
 
     def _resolve_asset_ids(self) -> None:
         """
         Resolve id of assets if specified, for use in sequence creation
         """
         assets = set(self.sequence_asset_external_ids.values())
-        assets.discard(None)
+        assets.discard(None)  # type: ignore  # safeguard, remove Nones if any
 
         if len(assets) > 0:
             try:
                 self.asset_ids = {
                     asset.external_id: asset.id
                     for asset in self.cdf_client.assets.retrieve_multiple(
                         external_ids=list(assets), ignore_unknown_ids=True
                     )
                 }
             except Exception as e:
                 self.logger.error("Error in resolving asset id: %s", str(e))
-                self.asset_ids = dict()
+                self.asset_ids = {}
 
     def _resolve_dataset_ids(self) -> None:
         """
         Resolve id of datasets if specified, for use in sequence creation
         """
         datasets = set(self.sequence_dataset_external_ids.values())
-        datasets.discard(None)
+        datasets.discard(None)  # type: ignore  # safeguard, remove Nones if any
 
         if len(datasets) > 0:
             try:
                 self.dataset_ids = {
                     dataset.external_id: dataset.id
                     for dataset in self.cdf_client.data_sets.retrieve_multiple(
                         external_ids=list(datasets), ignore_unknown_ids=True
                     )
                 }
             except Exception as e:
                 self.logger.error("Error in resolving dataset id: %s", str(e))
-                self.dataset_ids = dict()
+                self.dataset_ids = {}
 
     def __enter__(self) -> "SequenceUploadQueue":
         """
         Wraps around start method, for use as context manager
 
         Returns:
             self
         """
         self.start()
         return self
 
-    def __exit__(self, exc_type, exc_val, exc_tb) -> None:
+    def __exit__(
+        self, exc_type: Optional[Type[BaseException]], exc_val: Optional[BaseException], exc_tb: Optional[TracebackType]
+    ) -> None:
         """
         Wraps around stop method, for use as context manager
 
         Args:
             exc_type: Exception type
             exc_val: Exception value
             exc_tb: Traceback
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader_extractor.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader_extractor.py`

 * *Files 2% similar despite different names*

```diff
@@ -11,22 +11,22 @@
 #  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #  See the License for the specific language governing permissions and
 #  limitations under the License.
 
 """
 A module containing a slightly more advanced base extractor class, sorting a generic output into upload queues.
 """
-
+import threading
 from dataclasses import dataclass
 from types import TracebackType
-from typing import Callable, Iterable, List, Optional, Type, TypeVar
+from typing import Any, Callable, Iterable, List, Optional, Type, TypeVar
 
-from cognite.client import CogniteClient
 from more_itertools import peekable
 
+from cognite.client import CogniteClient
 from cognite.extractorutils.base import Extractor
 from cognite.extractorutils.configtools import BaseConfig, TimeIntervalConfig
 from cognite.extractorutils.metrics import BaseMetrics
 from cognite.extractorutils.statestore import AbstractStateStore
 from cognite.extractorutils.uploader import EventUploadQueue, RawUploadQueue, TimeSeriesUploadQueue
 from cognite.extractorutils.uploader_types import CdfTypes, Event, InsertDatapoints, RawRow
 
@@ -74,20 +74,20 @@
     def __init__(
         self,
         *,
         name: str,
         description: str,
         version: Optional[str] = None,
         run_handle: Optional[
-            Callable[[CogniteClient, AbstractStateStore, UploaderExtractorConfigClass, Event], None]
+            Callable[[CogniteClient, AbstractStateStore, UploaderExtractorConfigClass, threading.Event], None]
         ] = None,
         config_class: Type[UploaderExtractorConfigClass],
         metrics: Optional[BaseMetrics] = None,
         use_default_state_store: bool = True,
-        cancellation_token: Event = Event(),
+        cancellation_token: threading.Event = threading.Event(),
         config_file_path: Optional[str] = None,
         continuous_extractor: bool = False,
         heartbeat_waiting_time: int = 600,
         handle_interrupts: bool = True,
         middleware: List[Callable[[dict], dict]] = [],
     ):
         super(UploaderExtractor, self).__init__(
@@ -103,18 +103,17 @@
             continuous_extractor=continuous_extractor,
             heartbeat_waiting_time=heartbeat_waiting_time,
             handle_interrupts=handle_interrupts,
         )
         self.middleware = middleware if isinstance(middleware, list) else []
 
     def handle_output(self, output: CdfTypes) -> None:
-        if not isinstance(output, Iterable):
-            output = [output]
+        list_output = [output] if not isinstance(output, Iterable) else output
+        peekable_output = peekable(list_output)
 
-        peekable_output = peekable(output)
         peek = peekable_output.peek(None)
 
         if peek is None:
             return
 
         if isinstance(peek, Event):
             for event in peekable_output:
@@ -129,15 +128,15 @@
             for datapoints in peekable_output:
                 self.time_series_queue.add_to_upload_queue(
                     id=datapoints.id, external_id=datapoints.external_id, datapoints=datapoints.datapoints
                 )
         else:
             raise ValueError(f"Unexpected type: {type(peek)}")
 
-    def _apply_middleware(self, item):
+    def _apply_middleware(self, item: Any) -> Any:
         for mw in self.middleware:
             item = mw(item)
         return item
 
     def __enter__(self) -> "UploaderExtractor":
         super(UploaderExtractor, self).__enter__()
```

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/uploader_types.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/uploader_types.py`

 * *Files identical despite different names*

### Comparing `cognite_extractor_utils-5.1.0/cognite/extractorutils/util.py` & `cognite_extractor_utils-5.2.0/cognite/extractorutils/util.py`

 * *Files 5% similar despite different names*

```diff
@@ -19,20 +19,21 @@
 import logging
 import random
 import signal
 import threading
 from functools import partial, wraps
 from threading import Event, Thread
 from time import time
-from typing import Any, Dict, Generator, Iterable, Optional, Tuple, Type, Union
+from typing import Any, Callable, Generator, Iterable, Optional, Tuple, Type, TypeVar, Union
+
+from decorator import decorator
 
 from cognite.client import CogniteClient
 from cognite.client.data_classes import Asset, ExtractionPipelineRun, TimeSeries
 from cognite.client.exceptions import CogniteNotFoundError
-from decorator import decorator
 
 
 def _ensure(endpoint: Any, items: Iterable[Any]) -> None:
     try:
         external_ids = [ts.external_id for ts in items]
 
         # Not doing anything with the result, only want to make sure they exist. This will throw an exception if not.
@@ -76,15 +77,15 @@
     """
     Set given event on SIGINT (Ctrl-C) instead of throwing a KeyboardInterrupt exception.
 
     Args:
         stop_event: Event to set
     """
 
-    def sigint_handler(sig, frame):
+    def sigint_handler(sig_num: int, frame: Any) -> None:
         logger = logging.getLogger(__name__)
         logger.warning("Interrupt signal received, stopping extractor gracefully")
         stop_event.set()
         logger.info("Waiting for threads to complete. Send another interrupt to force quit.")
         signal.signal(signal.SIGINT, signal.default_int_handler)
 
     try:
@@ -102,26 +103,32 @@
         id: Internal ID
         externalId or external_id: external ID
 
     Raises:
         TypeError: If none of both of id types are set.
     """
 
-    def __init__(self, **kwargs):
+    def __init__(self, **kwargs: Union[int, str, None]):
         internal_id = kwargs.get("id")
         external_id = kwargs.get("externalId") or kwargs.get("external_id")
 
         if internal_id is None and external_id is None:
             raise TypeError("Either id or external_id must be set")
 
         if internal_id is not None and external_id is not None:
             raise TypeError("Only one of id and external_id can be set")
 
-        self.internal_id = internal_id
-        self.external_id = external_id
+        if internal_id is not None and not isinstance(internal_id, int):
+            raise TypeError("Internal IDs must be integers")
+
+        if external_id is not None and not isinstance(external_id, str):
+            raise TypeError("Internal IDs must be integers")
+
+        self.internal_id: Optional[int] = internal_id
+        self.external_id: Optional[str] = external_id
 
     def type(self) -> str:
         """
         Get the type of the ID
 
         Returns:
             'id' if the EitherId represents an internal ID, 'externalId' if the EitherId represents an external ID
@@ -131,15 +138,15 @@
     def content(self) -> Union[int, str]:
         """
         Get the value of the ID
 
         Returns:
             The ID
         """
-        return self.internal_id or self.external_id
+        return self.internal_id or self.external_id  # type: ignore  # checked to be not None in init
 
     def __eq__(self, other: Any) -> bool:
         """
         Compare with another object. Only returns true if other is an EitherId with the same type and content
 
         Args:
             other: Another object
@@ -176,20 +183,23 @@
 
         Returns:
             A string rep of the EitherId
         """
         return self.__str__()
 
 
+_T1 = TypeVar("_T1")
+
+
 def add_extraction_pipeline(
     extraction_pipeline_ext_id: str,
     cognite_client: CogniteClient,
     heartbeat_waiting_time: int = 600,
     added_message: str = "",
-):
+) -> Callable[[Callable[..., _T1]], Callable[..., _T1]]:
     """
     This is to be used as a decorator for extractor functions to add extraction pipeline information
 
     Args:
         extraction_pipeline_ext_id:
         cognite_client:
         heartbeat_waiting_time:
@@ -210,17 +220,17 @@
     # TODO 1. Consider refactoring this decorator to share methods with the Extractor context manager in .base.py
     # as they serve a similar purpose
 
     cancellation_token: Event = Event()
 
     _logger = logging.getLogger(__name__)
 
-    def decorator_ext_pip(input_function):
+    def decorator_ext_pip(input_function: Callable[..., _T1]) -> Callable[..., _T1]:
         @wraps(input_function)
-        def wrapper_ext_pip(*args, **kwargs):
+        def wrapper_ext_pip(*args: Any, **kwargs: Any) -> _T1:
             ##############################
             # Setup Extraction Pipelines #
             ##############################
             _logger.info("Setting up Extraction Pipelines")
 
             def _report_success() -> None:
                 message = f"Successful shutdown of function '{input_function.__name__}'. {added_message}"
@@ -252,28 +262,30 @@
                     cancellation_token.wait(heartbeat_waiting_time)
 
             ##############################
             # Run the extractor function #
             ##############################
             _logger.info(f"Starting to run function: {input_function.__name__}")
 
+            heartbeat_thread: Optional[Thread] = None
             try:
                 heartbeat_thread = Thread(target=heartbeat_loop, name="HeartbeatLoop", daemon=True)
                 heartbeat_thread.start()
                 output = input_function(*args, **kwargs)
             except Exception as e:
                 _report_error(exception=e)
                 _logger.error(f"Extraction failed with exception: {e}")
                 raise e
             else:
                 _report_success()
-                _logger.info(f"Extraction ran successfully")
+                _logger.info("Extraction ran successfully")
             finally:
                 cancellation_token.set()
-                heartbeat_thread.join()
+                if heartbeat_thread:
+                    heartbeat_thread.join()
 
             return output
 
         return wrapper_ext_pip
 
     return decorator_ext_pip
 
@@ -308,33 +320,36 @@
             logger.warning("Iteration time longer than target time, will not sleep")
 
         else:
             logger.debug(f"Iteration took {iteration_time:.1f} s, sleeping {target_time - iteration_time:.1f} s")
             cancellation_token.wait(target_time - iteration_time)
 
 
+_T2 = TypeVar("_T2")
+
+
 def _retry_internal(
-    f,
+    f: Callable[..., _T2],
     cancellation_token: threading.Event = threading.Event(),
-    exceptions: Iterable[Type[Exception]] = Exception,
+    exceptions: Iterable[Type[Exception]] = [Exception],
     tries: int = -1,
     delay: float = 0,
     max_delay: Optional[float] = None,
     backoff: float = 1,
     jitter: Union[float, Tuple[float, float]] = 0,
-):
+) -> _T2:
     logger = logging.getLogger(__name__)
 
     while tries and not cancellation_token.is_set():
         try:
             return f()
-        except exceptions as e:
+        except exceptions as e:  # type: ignore  # Exception is an exception type, smh mypy
             tries -= 1
             if not tries:
-                raise
+                raise e
 
             if logger is not None:
                 logger.warning("%s, retrying in %s seconds...", e, delay)
 
             cancellation_token.wait(delay)
             delay *= backoff
 
@@ -342,24 +357,26 @@
                 delay += random.uniform(*jitter)
             else:
                 delay += jitter
 
             if max_delay is not None:
                 delay = min(delay, max_delay)
 
+    return None  # type: ignore  # unreachable, we will have raised an exception before this
+
 
 def retry(
     cancellation_token: threading.Event = threading.Event(),
-    exceptions: Iterable[Type[Exception]] = Exception,
+    exceptions: Iterable[Type[Exception]] = [Exception],
     tries: int = -1,
     delay: float = 0,
     max_delay: Optional[float] = None,
     backoff: float = 1,
     jitter: Union[float, Tuple[float, float]] = 0,
-):
+) -> Callable[[Callable[..., _T2]], Callable[..., _T2]]:
     """
     Returns a retry decorator.
 
     This is adapted from https://github.com/invl/retry
 
     Args:
         cancellation_token: a threading token that is waited on.
@@ -371,17 +388,17 @@
         jitter: extra seconds added to delay between attempts. default: 0.
                    fixed if a number, random if a range tuple (min, max)
         logger: logger.warning(fmt, error, delay) will be called on failed attempts.
                    default: retry.logging_logger. if None, logging is disabled.
     """
 
     @decorator
-    def retry_decorator(f, *fargs, **fkwargs):
-        args = fargs if fargs else list()
-        kwargs = fkwargs if fkwargs else dict()
+    def retry_decorator(f: Callable[..., _T2], *fargs: Any, **fkwargs: Any) -> _T2:
+        args = fargs if fargs else []
+        kwargs = fkwargs if fkwargs else {}
 
         return _retry_internal(
             partial(f, *args, **kwargs),
             cancellation_token,
             exceptions,
             tries,
             delay,
```

### Comparing `cognite_extractor_utils-5.1.0/PKG-INFO` & `cognite_extractor_utils-5.2.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cognite-extractor-utils
-Version: 5.1.0
+Version: 5.2.0
 Summary: Utilities for easier development of extractors for CDF
 Home-page: https://github.com/cognitedata/python-extractor-utils
 License: Apache-2.0
 Author: Mathias Lohne
 Author-email: mathias.lohne@cognite.com
 Requires-Python: >=3.8.0,<4.0.0
 Classifier: License :: OSI Approved :: Apache Software License
@@ -117,8 +117,7 @@
 $ poetry run pre-commit install
 ```
 
 Each public method, class and module should have docstrings. Docstrings are written in the [Google
 style](https://google.github.io/styleguide/pyguide.html#38-comments-and-docstrings). Please include unit and/or
 integration tests for submitted code, and remember to update the [changelog](./CHANGELOG.md).
 
-
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: cognite-extractor-utils Version: 5.1.0 Summary:
+Metadata-Version: 2.1 Name: cognite-extractor-utils Version: 5.2.0 Summary:
 Utilities for easier development of extractors for CDF Home-page: https://
 github.com/cognitedata/python-extractor-utils License: Apache-2.0 Author:
 Mathias Lohne Author-email: mathias.lohne@cognite.com Requires-Python:
 >=3.8.0,<4.0.0 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3 Classifier: Programming
 Language :: Python :: 3.8 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10 Classifier: Programming
```


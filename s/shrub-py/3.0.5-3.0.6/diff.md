# Comparing `tmp/shrub_py-3.0.5.tar.gz` & `tmp/shrub_py-3.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "shrub_py-3.0.5.tar", max compression
+gzip compressed data, was "shrub_py-3.0.6.tar", max compression
```

## Comparing `shrub_py-3.0.5.tar` & `shrub_py-3.0.6.tar`

### file list

```diff
@@ -1,25 +1,25 @@
--rw-r--r--   0        0        0    11536 2023-04-26 16:50:29.661012 shrub_py-3.0.5/LICENSE
--rw-r--r--   0        0        0     1285 2023-04-26 16:50:29.661012 shrub_py-3.0.5/README.md
--rw-r--r--   0        0        0      818 2023-04-26 16:50:29.661012 shrub_py-3.0.5/pyproject.toml
--rw-r--r--   0        0        0        0 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/__init__.py
--rw-r--r--   0        0        0     1723 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/base.py
--rw-r--r--   0        0        0     6189 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/command.py
--rw-r--r--   0        0        0     7208 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/config.py
--rw-r--r--   0        0        0    28873 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/operations.py
--rw-r--r--   0        0        0        0 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/py.typed
--rw-r--r--   0        0        0     9305 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/task.py
--rw-r--r--   0        0        0      266 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/v2/__init__.py
--rw-r--r--   0        0        0    22752 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/v2/command.py
--rw-r--r--   0        0        0      992 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/v2/dict_creation_util.py
--rw-r--r--   0        0        0     2386 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/v2/project.py
--rw-r--r--   0        0        0     5561 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/v2/task.py
--rw-r--r--   0        0        0     9495 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/v2/variant.py
--rw-r--r--   0        0        0        0 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/v3/__init__.py
--rw-r--r--   0        0        0     1439 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/v3/evg_build_variant.py
--rw-r--r--   0        0        0    33046 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/v3/evg_command.py
--rw-r--r--   0        0        0     3187 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/v3/evg_project.py
--rw-r--r--   0        0        0     1663 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/v3/evg_task.py
--rw-r--r--   0        0        0     1968 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/v3/evg_task_group.py
--rw-r--r--   0        0        0      921 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/v3/shrub_service.py
--rw-r--r--   0        0        0     9253 2023-04-26 16:50:29.661012 shrub_py-3.0.5/src/shrub/variant.py
--rw-r--r--   0        0        0     2282 1970-01-01 00:00:00.000000 shrub_py-3.0.5/PKG-INFO
+-rw-r--r--   0        0        0    11536 2023-06-27 23:15:07.085320 shrub_py-3.0.6/LICENSE
+-rw-r--r--   0        0        0     1285 2023-06-27 23:15:07.085320 shrub_py-3.0.6/README.md
+-rw-r--r--   0        0        0      817 2023-06-27 23:15:07.089320 shrub_py-3.0.6/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/__init__.py
+-rw-r--r--   0        0        0     1723 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/base.py
+-rw-r--r--   0        0        0     6189 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/command.py
+-rw-r--r--   0        0        0     7208 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/config.py
+-rw-r--r--   0        0        0    28873 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/operations.py
+-rw-r--r--   0        0        0        0 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/py.typed
+-rw-r--r--   0        0        0     9305 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/task.py
+-rw-r--r--   0        0        0      266 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/v2/__init__.py
+-rw-r--r--   0        0        0    22752 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/v2/command.py
+-rw-r--r--   0        0        0      992 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/v2/dict_creation_util.py
+-rw-r--r--   0        0        0     2386 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/v2/project.py
+-rw-r--r--   0        0        0     5561 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/v2/task.py
+-rw-r--r--   0        0        0     9495 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/v2/variant.py
+-rw-r--r--   0        0        0        0 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/v3/__init__.py
+-rw-r--r--   0        0        0     1439 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/v3/evg_build_variant.py
+-rw-r--r--   0        0        0    33152 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/v3/evg_command.py
+-rw-r--r--   0        0        0     3187 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/v3/evg_project.py
+-rw-r--r--   0        0        0     1663 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/v3/evg_task.py
+-rw-r--r--   0        0        0     1968 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/v3/evg_task_group.py
+-rw-r--r--   0        0        0      921 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/v3/shrub_service.py
+-rw-r--r--   0        0        0    10210 2023-06-27 23:15:07.089320 shrub_py-3.0.6/src/shrub/variant.py
+-rw-r--r--   0        0        0     2228 1970-01-01 00:00:00.000000 shrub_py-3.0.6/PKG-INFO
```

### Comparing `shrub_py-3.0.5/LICENSE` & `shrub_py-3.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/README.md` & `shrub_py-3.0.6/README.md`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/pyproject.toml` & `shrub_py-3.0.6/pyproject.toml`

 * *Files 16% similar despite different names*

```diff
@@ -1,35 +1,35 @@
 [tool.poetry]
 name = "shrub.py"
-version = "3.0.5"
+version = "3.0.6"
 description = "Library for creating evergreen configurations"
 authors = [
     "David Bradford <david.bradford@mongodb.com>",
     "Lydia Stepanek <lydia.stepanek@mongodb.com>",
     "Tausif Rahman <tausif.rahman@mongodb.com>"
 ]
 license = "Apache-2.0"
 readme = "README.md"
 repository = "https://github.com/evergreen-ci/shrub.py"
 packages = [
     { include = "shrub", from = "src" },
 ]
 
 [tool.poetry.dependencies]
-python = ">3.6.1"
+python = ">3.7.0"
 PyYaml = "^5.1"
 dataclasses = {version = "^0.7", python = "3.6.*"}
 pydantic = "^1.8"
 git-url-parse = "^1"
 typing-extensions = "^4"
 
 [tool.poetry.dev-dependencies]
 pytest = "^6.0"
 pytest-black = "^0.3"
 pytest-flake8 = "^1.0"
 pytest-mypy = "^0.8.0"
-black = "^19.10b0"
+black = "^23.3.0"
 types-PyYAML = "^5.4.10"
 flake8 = "3.9.2"
 
 [tool.black]
 line-length = 100
```

### Comparing `shrub_py-3.0.5/src/shrub/base.py` & `shrub_py-3.0.6/src/shrub/base.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/command.py` & `shrub_py-3.0.6/src/shrub/command.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/config.py` & `shrub_py-3.0.6/src/shrub/config.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/operations.py` & `shrub_py-3.0.6/src/shrub/operations.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/task.py` & `shrub_py-3.0.6/src/shrub/task.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/v2/command.py` & `shrub_py-3.0.6/src/shrub/v2/command.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/v2/dict_creation_util.py` & `shrub_py-3.0.6/src/shrub/v2/dict_creation_util.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/v2/project.py` & `shrub_py-3.0.6/src/shrub/v2/project.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/v2/task.py` & `shrub_py-3.0.6/src/shrub/v2/task.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/v2/variant.py` & `shrub_py-3.0.6/src/shrub/v2/variant.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/v3/evg_build_variant.py` & `shrub_py-3.0.6/src/shrub/v3/evg_build_variant.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/v3/evg_command.py` & `shrub_py-3.0.6/src/shrub/v3/evg_command.py`

 * *Files 2% similar despite different names*

```diff
@@ -194,21 +194,21 @@
         # We override the constructor here in order to clear out any `None` values in the
         # params.
         if kwargs.get("params") is not None:
             kwargs["params"] = {k: v for k, v in kwargs["params"].items() if v is not None}
         super().__init__(**kwargs)
 
     class Config:
-
         allow_population_by_field_name = True
         use_enum_values = True
 
 
 EvgCommand = Union[
-    FunctionCall, BuiltInCommand,
+    FunctionCall,
+    BuiltInCommand,
 ]
 
 
 # Built in commands
 
 
 def archive_targz_extract(
@@ -288,15 +288,16 @@
             "ignore_artifacts_for_spawn": ignore_artifacts_for_spawn,
         },
         command_type=command_type,
     )
 
 
 def attach_results(
-    file_location: str, command_type: Optional[EvgCommandType] = None,
+    file_location: str,
+    command_type: Optional[EvgCommandType] = None,
 ) -> BuiltInCommand:
     """
     Command to attach test results to the task results.
 
     :param file_location: Location of test results to attach.
     :param command_type: How failures should be reported.
     :return: attach.results command.
@@ -325,25 +326,28 @@
         command="attach.xunit_results",
         params={"file": file, "files": files},
         command_type=command_type,
     )
 
 
 def downstream_expansions_set(
-    file: Optional[str] = None, command_type: Optional[EvgCommandType] = None,
+    file: Optional[str] = None,
+    command_type: Optional[EvgCommandType] = None,
 ) -> BuiltInCommand:
     """
-    Command used by parent patches to pass key-value pairs to its children patches. 
+    Command used by parent patches to pass key-value pairs to its children patches.
 
     :param file: File containg key-value pairs for the child.
     :param command_type: How failures should be reported.
     :return:  downstream_expansions.set command.
     """
     return BuiltInCommand(
-        command="downstream_expansions.set", params={"file": file}, command_type=command_type,
+        command="downstream_expansions.set",
+        params={"file": file},
+        command_type=command_type,
     )
 
 
 def expansions_update(
     updates: Optional[List[KeyValueParam]] = None,
     file: Optional[str] = None,
     ignore_missing_file: Optional[bool] = None,
@@ -369,15 +373,17 @@
             "env": env,
         },
         command_type=command_type,
     )
 
 
 def expansions_write(
-    file: str, redacted: Optional[bool] = None, command_type: Optional[EvgCommandType] = None,
+    file: str,
+    redacted: Optional[bool] = None,
+    command_type: Optional[EvgCommandType] = None,
 ) -> BuiltInCommand:
     """
     Command to write expansion definitions to a file.
 
     :param file: File to write expansions to.
     :param redacted: If True, redacted expansions will be included.
     :param command_type: How failures should be reported.
@@ -387,25 +393,28 @@
         command="expansions.write",
         params={"file": file, "redacted": redacted},
         command_type=command_type,
     )
 
 
 def generate_tasks(
-    files: List[str], command_type: Optional[EvgCommandType] = None,
+    files: List[str],
+    command_type: Optional[EvgCommandType] = None,
 ) -> BuiltInCommand:
     """
     Command to generate tasks dynamically.
 
     :param files: List of files containing evergreen json configuration to generate.
     :param command_type: How failures should be reported.
     :return: generate.tasks command.
     """
     return BuiltInCommand(
-        command="generate.tasks", params={"files": files}, command_type=command_type,
+        command="generate.tasks",
+        params={"files": files},
+        command_type=command_type,
     )
 
 
 def git_get_project(
     directory: str,
     token: Optional[str] = None,
     revisions: Optional[Dict[str, str]] = None,
@@ -424,25 +433,28 @@
         command="git.get_project",
         params={"directory": directory, "token": token, "revisions": revisions},
         command_type=command_type,
     )
 
 
 def gotest_parse_files(
-    files: List[str], command_type: Optional[EvgCommandType] = None,
+    files: List[str],
+    command_type: Optional[EvgCommandType] = None,
 ) -> BuiltInCommand:
     """
     Parameters to attach gotest test results to the task results.
 
     :param files: List of files containing gotest test results.
     :param command_type: How failures should be reported.
     :return: gotest.parse_files command.
     """
     return BuiltInCommand(
-        command="gotest.parse_files", params={"files": files}, command_type=command_type,
+        command="gotest.parse_files",
+        params={"files": files},
+        command_type=command_type,
     )
 
 
 def host_create(
     provider: CloudProvider,
     security_group_ids: List[str],
     file: Optional[str] = None,
@@ -584,31 +596,37 @@
             "silent": silent,
         },
         command_type=command_type,
     )
 
 
 def json_send(
-    file: str, name: str, command_type: Optional[EvgCommandType] = None,
+    file: str,
+    name: str,
+    command_type: Optional[EvgCommandType] = None,
 ) -> BuiltInCommand:
     """
     Send json data to the task results.
 
     :param file: File containing json data to send.
     :param name: Name of the file to save.
     :param command_type: How failures should be reported.
     :return: json send command.
     """
     return BuiltInCommand(
-        command="json.send", params={"file": file, "name": name}, command_type=command_type,
+        command="json.send",
+        params={"file": file, "name": name},
+        command_type=command_type,
     )
 
 
 def key_val_inc(
-    destination: str, key: str, command_type: Optional[EvgCommandType] = None,
+    destination: str,
+    key: str,
+    command_type: Optional[EvgCommandType] = None,
 ) -> BuiltInCommand:
     """
     Command for key/val increment.
 
     :param destination:
     :param key:
     :param command_type: How failures should be reported.
```

### Comparing `shrub_py-3.0.5/src/shrub/v3/evg_project.py` & `shrub_py-3.0.6/src/shrub/v3/evg_project.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/v3/evg_task.py` & `shrub_py-3.0.6/src/shrub/v3/evg_task.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/v3/evg_task_group.py` & `shrub_py-3.0.6/src/shrub/v3/evg_task_group.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/v3/shrub_service.py` & `shrub_py-3.0.6/src/shrub/v3/shrub_service.py`

 * *Files identical despite different names*

### Comparing `shrub_py-3.0.5/src/shrub/variant.py` & `shrub_py-3.0.6/src/shrub/variant.py`

 * *Files 3% similar despite different names*

```diff
@@ -20,26 +20,28 @@
         self._batch_time_secs = None
         self._task_specs = []
         self._distro_run_on = []
         self._expansions = {}
         self._display_task_specs = []
         self._modules = []
         self._activate = None
+        self._cron = None
 
     def _yaml_map(self):
         return {
             "_build_name": {NAME_KEY: "name", RECURSE_KEY: False},
             "_build_display_name": {NAME_KEY: "display_name", RECURSE_KEY: False},
             "_batch_time_secs": {NAME_KEY: "batchtime", RECURSE_KEY: False},
             "_task_specs": {NAME_KEY: "tasks", RECURSE_KEY: True},
             "_distro_run_on": {NAME_KEY: "run_on", RECURSE_KEY: False},
             "_expansions": {NAME_KEY: "expansions", RECURSE_KEY: False},
             "_display_task_specs": {NAME_KEY: "display_tasks", RECURSE_KEY: True},
             "_modules": {NAME_KEY: "modules", RECURSE_KEY: False},
             "_activate": {NAME_KEY: "activate", RECURSE_KEY: False},
+            "_cron": {NAME_KEY: "cron", RECURSE_KEY: False},
         }
 
     def get_name(self):
         """
         Get the name of this build variant.
         :return: name of build variant.
         """
@@ -206,35 +208,50 @@
         """
         if not isinstance(activate, bool) and activate is not None:
             raise TypeError("activate only accepts a bool or None")
 
         self._activate = activate
         return self
 
+    def cron(self, cron):
+        """
+        Specify a crontab value for when this variant should be activated.
+
+        :param cron: The timing on crontab format for when this should be activated
+        :return: instance of task spec
+        """
+        if not isinstance(cron, str):
+            raise TypeError("cron only accepts a string")
+
+        self._cron = cron
+        return self
+
 
 class TaskSpec(EvergreenBuilder):
     """A spec for adding a task to a variant."""
 
     def __init__(self, name):
         """
         Create a task spec.
 
         :param name: name of task.
         """
         self._name = name
         self._stepback = None
         self._distro = []
         self._activate = None
+        self._cron = None
 
     def _yaml_map(self):
         return {
             "_name": {NAME_KEY: "name", RECURSE_KEY: False},
             "_stepback": {NAME_KEY: "stepback", RECURSE_KEY: False},
             "_distro": {NAME_KEY: "distros", RECURSE_KEY: False},
             "_activate": {NAME_KEY: "activate", RECURSE_KEY: False},
+            "_cron": {NAME_KEY: "cron", RECURSE_KEY: False},
         }
 
     def stepback(self):
         """
         Enable stepback for this task.
         :return:
         """
@@ -263,14 +280,27 @@
         """
         if not isinstance(activate, bool) and activate is not None:
             raise TypeError("activate only accepts a bool or None")
 
         self._activate = activate
         return self
 
+    def cron(self, cron):
+        """
+        Specify a crontab value for when this task should be activated.
+
+        :param cron: The timing on crontab format for when this should be activated
+        :return: instance of task spec
+        """
+        if not isinstance(cron, str):
+            raise TypeError("cron only accepts a string")
+
+        self._cron = cron
+        return self
+
 
 class DisplayTaskDefinition(EvergreenBuilder):
     """Defines a display task for evergreen."""
 
     def __init__(self, name):
         """
         Create a display task definition.
```

### Comparing `shrub_py-3.0.5/PKG-INFO` & `shrub_py-3.0.6/PKG-INFO`

 * *Files 19% similar despite different names*

```diff
@@ -1,25 +1,24 @@
 Metadata-Version: 2.1
 Name: shrub-py
-Version: 3.0.5
+Version: 3.0.6
 Summary: Library for creating evergreen configurations
 Home-page: https://github.com/evergreen-ci/shrub.py
 License: Apache-2.0
 Author: David Bradford
 Author-email: david.bradford@mongodb.com
-Requires-Python: >3.6.1
+Requires-Python: >3.7.0
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Requires-Dist: PyYaml (>=5.1,<6.0)
-Requires-Dist: dataclasses (>=0.7,<0.8) ; python_full_version >= "3.6.0" and python_full_version < "3.7.0"
+Requires-Dist: dataclasses (>=0.7,<0.8) ; python_version >= "3.6.dev0" and python_version < "3.7.dev0"
 Requires-Dist: git-url-parse (>=1,<2)
 Requires-Dist: pydantic (>=1.8,<2.0)
 Requires-Dist: typing-extensions (>=4,<5)
 Project-URL: Repository, https://github.com/evergreen-ci/shrub.py
 Description-Content-Type: text/markdown
 
 # shrub.py
```


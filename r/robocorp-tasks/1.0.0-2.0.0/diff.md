# Comparing `tmp/robocorp_tasks-1.0.0.tar.gz` & `tmp/robocorp_tasks-2.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "robocorp_tasks-1.0.0.tar", max compression
+gzip compressed data, was "robocorp_tasks-2.0.0.tar", max compression
```

## Comparing `robocorp_tasks-1.0.0.tar` & `robocorp_tasks-2.0.0.tar`

### file list

```diff
@@ -1,20 +1,20 @@
--rw-r--r--   0        0        0     4871 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/README.md
--rw-r--r--   0        0        0     1162 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/pyproject.toml
--rw-r--r--   0        0        0     3502 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/__init__.py
--rw-r--r--   0        0        0       79 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/__main__.py
--rw-r--r--   0        0        0     4495 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/_argdispatch.py
--rw-r--r--   0        0        0     1457 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/_callback.py
--rw-r--r--   0        0        0     5121 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/_collect_tasks.py
--rw-r--r--   0        0        0    10192 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/_commands.py
--rw-r--r--   0        0        0     2245 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/_config.py
--rw-r--r--   0        0        0      182 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/_exceptions.py
--rw-r--r--   0        0        0     1122 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/_hooks.py
--rw-r--r--   0        0        0     1367 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/_lifecycle.py
--rw-r--r--   0        0        0     4078 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/_log_auto_setup.py
--rw-r--r--   0        0        0      461 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/_log_output_setup.py
--rw-r--r--   0        0        0     3943 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/_protocols.py
--rw-r--r--   0        0        0     5489 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/_task.py
--rw-r--r--   0        0        0     2436 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/_toml_settings.py
--rw-r--r--   0        0        0      869 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/cli.py
--rw-r--r--   0        0        0        0 2023-06-13 15:01:29.774650 robocorp_tasks-1.0.0/src/robocorp/tasks/py.typed
--rw-r--r--   0        0        0     5461 1970-01-01 00:00:00.000000 robocorp_tasks-1.0.0/PKG-INFO
+-rw-r--r--   0        0        0     5432 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/README.md
+-rw-r--r--   0        0        0     1234 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/pyproject.toml
+-rw-r--r--   0        0        0     3502 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/__init__.py
+-rw-r--r--   0        0        0       79 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/__main__.py
+-rw-r--r--   0        0        0     4495 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/_argdispatch.py
+-rw-r--r--   0        0        0     1457 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/_callback.py
+-rw-r--r--   0        0        0     5121 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/_collect_tasks.py
+-rw-r--r--   0        0        0    10199 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/_commands.py
+-rw-r--r--   0        0        0     2245 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/_config.py
+-rw-r--r--   0        0        0      182 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/_exceptions.py
+-rw-r--r--   0        0        0     1122 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/_hooks.py
+-rw-r--r--   0        0        0     1367 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/_lifecycle.py
+-rw-r--r--   0        0        0     5080 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/_log_auto_setup.py
+-rw-r--r--   0        0        0      461 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/_log_output_setup.py
+-rw-r--r--   0        0        0     3943 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/_protocols.py
+-rw-r--r--   0        0        0     5489 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/_task.py
+-rw-r--r--   0        0        0     2436 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/_toml_settings.py
+-rw-r--r--   0        0        0      869 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/cli.py
+-rw-r--r--   0        0        0        0 2023-06-28 12:52:46.820026 robocorp_tasks-2.0.0/src/robocorp/tasks/py.typed
+-rw-r--r--   0        0        0     6209 1970-01-01 00:00:00.000000 robocorp_tasks-2.0.0/PKG-INFO
```

### Comparing `robocorp_tasks-1.0.0/README.md` & `robocorp_tasks-2.0.0/README.md`

 * *Files 14% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 # robocorp-tasks
 
 `robocorp-tasks` is a Python framework designed to simplify the development 
 of Python automations.
 
-> Note: The current version (1.0.0) is now in beta. Semantic versioning is used in the project.
+> Note: The current version (2.0.0) is now in beta. Semantic versioning is used in the project.
 
 ## Why
 
 While Python is widely used in the automation world, many solutions end up being 
 ad-hoc, making it difficult to navigate different projects and keep up with the
 features required for analysing the results of such automations afterwards.
 
@@ -74,39 +74,60 @@
 
 
 `log_filter_rules` is a list of dictionaries where entries may be added to specify
 how to handle logging for a particular module.
 
 There are three different logging configurations that may be applied:
 
-- `exclude` (default for library code): skips logging a module.
+- `exclude`: skips logging a module.
 - `full_log` (default for user code): logs a module with full information, such as method calls, arguments, yields, local assigns, and more.
-- `log_on_project_call` logs only method calls, arguments, return values and exceptions, but only when a library method is called from user code. This configuration is meant to be used for library logging.
+- `log_on_project_call` (default for library code -- since 2.0): logs only method calls, arguments, return values and exceptions, but only when a library method is called from user code. This configuration is meant to be used for library logging.
+
+Note that the default for the library code may be configured through `default_library_filter_kind`.
 
 Example of `pyproject.toml` where the `rpaframework` and `selenium` 
-libraries are configured to be logged:
+libraries are configured to be logged and all other libraries are
+excluded by default:
 
 
 ```
 [tool.robocorp.log]
 
 log_filter_rules = [
     {name = "RPA", kind = "log_on_project_call"},
     {name = "selenium", kind = "log_on_project_call"},
     {name = "SeleniumLibrary", kind = "log_on_project_call"},
 ]
+
+default_library_filter_kind = "exclude"
 ```
 
 Note that when specifying a module name to match in `log_filter_rules`, 
 the name may either match exactly or the module name must start with the 
 name followed by a dot.
 
 This means that, for example, `RPA` would match `RPA.Browser`,
 but not `RPAmodule` nor `another.RPA`.
 
+Also, as of `robocorp-tasks 2.0`, it's also possible to use `fnmatch` style names.
+
+i.e.:
+
+```
+[tool.robocorp.log]
+
+log_filter_rules = [
+    {name = "proj.*", kind = "full_log"},
+    {name = "proj[AB]", kind = "full_log"},
+]
+```
+
+Note that the order of the rules is important as rules which appear
+first are matched before the ones that appear afterwards.
+
 
 ## Log output customization
 
 By default, the log output will be saved to an `output` directory, where each file 
 can be up to `1MB` and up to `5` files are kept before old ones are deleted. 
 When the run finishes, a `log.html` file will be created in the output directory 
 containing the log viewer with the log contents embedded.
```

### Comparing `robocorp_tasks-1.0.0/pyproject.toml` & `robocorp_tasks-2.0.0/pyproject.toml`

 * *Files 11% similar despite different names*

```diff
@@ -1,27 +1,29 @@
 [tool.poetry]
 name = "robocorp-tasks"
-version = "1.0.0"
+version = "2.0.0"
 description = "The automation framework for Python"
 authors = [
 	"Fabio Zadrozny <fabio@robocorp.com>",
 ]
 readme = "README.md"
+repository = "https://github.com/robocorp/robo/"
+license = "Apache-2.0"
 packages = [{include = "robocorp/tasks", from = "src"}]
 classifiers = [
     "Development Status :: 4 - Beta",
     "Topic :: Software Development :: Libraries :: Application Frameworks",
     "Programming Language :: Python :: 3.9",
     "Programming Language :: Python :: 3.10",
     "Programming Language :: Python :: 3.11",
 ]
 
 [tool.poetry.dependencies]
 python = "^3.9"
-robocorp-log = "^1"
+robocorp-log = "^2"
 
 [tool.poetry.group.dev.dependencies]
 robocorp-devutils = {path = "../devutils/", develop = true}
 
 [tool.mypy]
 mypy_path = "src:tests"
```

### Comparing `robocorp_tasks-1.0.0/src/robocorp/tasks/__init__.py` & `robocorp_tasks-2.0.0/src/robocorp/tasks/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -32,15 +32,15 @@
 automatically logged is not imported prior the the `cli.main` call.
 """
 from pathlib import Path
 from typing import Optional
 
 from ._protocols import ITask
 
-__version__ = "1.0.0"
+__version__ = "2.0.0"
 version_info = [int(x) for x in __version__.split(".")]
 
 
 def task(func):
     """
     Decorator for tasks (entry points) which can be executed by `robocorp.tasks`.
```

### Comparing `robocorp_tasks-1.0.0/src/robocorp/tasks/_argdispatch.py` & `robocorp_tasks-2.0.0/src/robocorp/tasks/_argdispatch.py`

 * *Files identical despite different names*

### Comparing `robocorp_tasks-1.0.0/src/robocorp/tasks/_callback.py` & `robocorp_tasks-2.0.0/src/robocorp/tasks/_callback.py`

 * *Files identical despite different names*

### Comparing `robocorp_tasks-1.0.0/src/robocorp/tasks/_collect_tasks.py` & `robocorp_tasks-2.0.0/src/robocorp/tasks/_collect_tasks.py`

 * *Files identical despite different names*

### Comparing `robocorp_tasks-1.0.0/src/robocorp/tasks/_commands.py` & `robocorp_tasks-2.0.0/src/robocorp/tasks/_commands.py`

 * *Files 2% similar despite different names*

```diff
@@ -140,19 +140,19 @@
         task_names = [task_name]
         task_or_tasks = "task"
     else:
         task_names = task_name
         task_name = ", ".join(str(x) for x in task_names)
         task_or_tasks = "task" if len(task_names) == 1 else "tasks"
 
-    config: log.BaseConfig
+    config: log.AutoLogConfigBase
     pyproject_path_and_contents = read_pyproject_toml(p)
     pyproject_toml_contents: dict
     if pyproject_path_and_contents is None:
-        config = log.ConfigFilesFiltering()
+        config = log.DefaultAutoLogConfig()
         pyproject_toml_contents = {}
     else:
         config = read_robocorp_log_config(context, pyproject_path_and_contents)
         pyproject_toml_contents = pyproject_path_and_contents.toml_contents
 
     run_config = RunConfig(
         Path(output_dir),
```

### Comparing `robocorp_tasks-1.0.0/src/robocorp/tasks/_config.py` & `robocorp_tasks-2.0.0/src/robocorp/tasks/_config.py`

 * *Files identical despite different names*

### Comparing `robocorp_tasks-1.0.0/src/robocorp/tasks/_hooks.py` & `robocorp_tasks-2.0.0/src/robocorp/tasks/_hooks.py`

 * *Files identical despite different names*

### Comparing `robocorp_tasks-1.0.0/src/robocorp/tasks/_lifecycle.py` & `robocorp_tasks-2.0.0/src/robocorp/tasks/_lifecycle.py`

 * *Files identical despite different names*

### Comparing `robocorp_tasks-1.0.0/src/robocorp/tasks/_log_auto_setup.py` & `robocorp_tasks-2.0.0/src/robocorp/tasks/_log_auto_setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -6,32 +6,53 @@
 from robocorp.tasks._protocols import PyProjectInfo
 
 from ._protocols import IContextErrorReport, ITask
 
 
 def read_robocorp_log_config(
     context: IContextErrorReport, pyproject: PyProjectInfo
-) -> log.BaseConfig:
+) -> log.AutoLogConfigBase:
     from ._toml_settings import read_section_from_toml
+    from robocorp.log import FilterKind
 
     if not pyproject.toml_contents:
-        log.ConfigFilesFiltering()
+        log.DefaultAutoLogConfig()
 
     obj: Any = pyproject.toml_contents
     filters: List[log.Filter] = []
+
+    default_library_filter_kind = FilterKind.log_on_project_call
+
     if isinstance(obj, dict):
         # Filter(name="RPA", kind=FilterKind.log_on_project_call),
         # Filter("selenium", FilterKind.log_on_project_call),
         # Filter("SeleniumLibrary", FilterKind.log_on_project_call),
         obj = read_section_from_toml(pyproject, "tool.robocorp.log", context)
 
         if isinstance(obj, dict):
             filters = _load_filters(obj, context, pyproject.pyproject)
+            kind = obj.get("default_library_filter_kind")
 
-    return log.ConfigFilesFiltering(filters=filters)
+            if kind is not None:
+                if not isinstance(kind, str):
+                    context.show_error(
+                        f"Expected 'tool.robocorp.log.log_filter_rules.default_library_filter_kind' to have 'kind' as a str (and not {type(kind)} in {pyproject}."
+                    )
+                else:
+                    f: Optional[log.FilterKind] = getattr(log.FilterKind, kind, None)
+                    if f is None:
+                        context.show_error(
+                            f"Rule from 'tool.robocorp.log.log_filter_rules.default_library_filter_kind' has invalid 'kind': >>{kind}<< in {pyproject}."
+                        )
+                    else:
+                        default_library_filter_kind = f
+
+    return log.DefaultAutoLogConfig(
+        filters=filters, default_library_filter_kind=default_library_filter_kind
+    )
 
 
 def _load_filters(
     obj: dict, context: IContextErrorReport, pyproject: Path
 ) -> List[log.Filter]:
     filters: List[log.Filter] = []
     log_filter_rules: list = []
@@ -101,15 +122,15 @@
 
 def _log_after_task_run(task: ITask):
     status = task.status
     log.end_task(task.name, task.module_name, status, task.message)
 
 
 @contextmanager
-def setup_cli_auto_logging(config: Optional[log.BaseConfig]):
+def setup_cli_auto_logging(config: Optional[log.AutoLogConfigBase]):
     # This needs to be called before importing code which needs to show in the log
     # (user or library).
 
     from robocorp.tasks._hooks import after_task_run, before_task_run
 
     with log.setup_auto_logging(config):
         with before_task_run.register(_log_before_task_run), after_task_run.register(
```

### Comparing `robocorp_tasks-1.0.0/src/robocorp/tasks/_protocols.py` & `robocorp_tasks-2.0.0/src/robocorp/tasks/_protocols.py`

 * *Files identical despite different names*

### Comparing `robocorp_tasks-1.0.0/src/robocorp/tasks/_task.py` & `robocorp_tasks-2.0.0/src/robocorp/tasks/_task.py`

 * *Files identical despite different names*

### Comparing `robocorp_tasks-1.0.0/src/robocorp/tasks/_toml_settings.py` & `robocorp_tasks-2.0.0/src/robocorp/tasks/_toml_settings.py`

 * *Files identical despite different names*

### Comparing `robocorp_tasks-1.0.0/src/robocorp/tasks/cli.py` & `robocorp_tasks-2.0.0/src/robocorp/tasks/cli.py`

 * *Files identical despite different names*

### Comparing `robocorp_tasks-1.0.0/PKG-INFO` & `robocorp_tasks-2.0.0/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,29 +1,33 @@
 Metadata-Version: 2.1
 Name: robocorp-tasks
-Version: 1.0.0
+Version: 2.0.0
 Summary: The automation framework for Python
+Home-page: https://github.com/robocorp/robo/
+License: Apache-2.0
 Author: Fabio Zadrozny
 Author-email: fabio@robocorp.com
 Requires-Python: >=3.9,<4.0
 Classifier: Development Status :: 4 - Beta
+Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Topic :: Software Development :: Libraries :: Application Frameworks
-Requires-Dist: robocorp-log (>=1,<2)
+Requires-Dist: robocorp-log (>=2,<3)
+Project-URL: Repository, https://github.com/robocorp/robo/
 Description-Content-Type: text/markdown
 
 # robocorp-tasks
 
 `robocorp-tasks` is a Python framework designed to simplify the development 
 of Python automations.
 
-> Note: The current version (1.0.0) is now in beta. Semantic versioning is used in the project.
+> Note: The current version (2.0.0) is now in beta. Semantic versioning is used in the project.
 
 ## Why
 
 While Python is widely used in the automation world, many solutions end up being 
 ad-hoc, making it difficult to navigate different projects and keep up with the
 features required for analysing the results of such automations afterwards.
 
@@ -90,39 +94,60 @@
 
 
 `log_filter_rules` is a list of dictionaries where entries may be added to specify
 how to handle logging for a particular module.
 
 There are three different logging configurations that may be applied:
 
-- `exclude` (default for library code): skips logging a module.
+- `exclude`: skips logging a module.
 - `full_log` (default for user code): logs a module with full information, such as method calls, arguments, yields, local assigns, and more.
-- `log_on_project_call` logs only method calls, arguments, return values and exceptions, but only when a library method is called from user code. This configuration is meant to be used for library logging.
+- `log_on_project_call` (default for library code -- since 2.0): logs only method calls, arguments, return values and exceptions, but only when a library method is called from user code. This configuration is meant to be used for library logging.
+
+Note that the default for the library code may be configured through `default_library_filter_kind`.
 
 Example of `pyproject.toml` where the `rpaframework` and `selenium` 
-libraries are configured to be logged:
+libraries are configured to be logged and all other libraries are
+excluded by default:
 
 
 ```
 [tool.robocorp.log]
 
 log_filter_rules = [
     {name = "RPA", kind = "log_on_project_call"},
     {name = "selenium", kind = "log_on_project_call"},
     {name = "SeleniumLibrary", kind = "log_on_project_call"},
 ]
+
+default_library_filter_kind = "exclude"
 ```
 
 Note that when specifying a module name to match in `log_filter_rules`, 
 the name may either match exactly or the module name must start with the 
 name followed by a dot.
 
 This means that, for example, `RPA` would match `RPA.Browser`,
 but not `RPAmodule` nor `another.RPA`.
 
+Also, as of `robocorp-tasks 2.0`, it's also possible to use `fnmatch` style names.
+
+i.e.:
+
+```
+[tool.robocorp.log]
+
+log_filter_rules = [
+    {name = "proj.*", kind = "full_log"},
+    {name = "proj[AB]", kind = "full_log"},
+]
+```
+
+Note that the order of the rules is important as rules which appear
+first are matched before the ones that appear afterwards.
+
 
 ## Log output customization
 
 By default, the log output will be saved to an `output` directory, where each file 
 can be up to `1MB` and up to `5` files are kept before old ones are deleted. 
 When the run finishes, a `log.html` file will be created in the output directory 
 containing the log viewer with the log contents embedded.
```


# Comparing `tmp/hidori-0.2.0.tar.gz` & `tmp/hidori-0.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "hidori-0.2.0.tar", max compression
+gzip compressed data, was "hidori-0.3.0.tar", max compression
```

## Comparing `hidori-0.2.0.tar` & `hidori-0.3.0.tar`

### file list

```diff
@@ -1,43 +1,60 @@
--rw-r--r--   0        0        0    13827 2022-09-19 18:24:14.910300 hidori-0.2.0/LICENSE-EUPL
--rw-r--r--   0        0        0     1074 2022-09-10 03:13:56.665275 hidori-0.2.0/LICENSE-MIT
--rw-r--r--   0        0        0     2831 2022-09-20 22:57:47.960872 hidori-0.2.0/README.md
--rw-r--r--   0        0        0     1515 2022-09-22 00:05:15.114352 hidori-0.2.0/pyproject.toml
--rw-r--r--   0        0        0        0 2022-09-08 22:46:50.502067 hidori-0.2.0/src/hidori_cli/__init__.py
--rw-r--r--   0        0        0        0 2022-09-09 09:24:10.431738 hidori-0.2.0/src/hidori_cli/apps/__init__.py
--rw-r--r--   0        0        0     1135 2022-09-10 13:31:06.793495 hidori-0.2.0/src/hidori_cli/apps/base.py
--rw-r--r--   0        0        0      212 2022-09-10 13:31:06.567494 hidori-0.2.0/src/hidori_cli/apps/pipeline.py
--rw-r--r--   0        0        0      207 2022-09-10 13:31:06.727495 hidori-0.2.0/src/hidori_cli/commands/__init__.py
--rw-r--r--   0        0        0     1714 2022-09-16 01:03:59.283100 hidori-0.2.0/src/hidori_cli/commands/base.py
--rw-r--r--   0        0        0      656 2022-09-17 17:37:02.647707 hidori-0.2.0/src/hidori_cli/commands/pipeline_run.py
--rw-r--r--   0        0        0       79 2022-09-15 21:19:40.862070 hidori-0.2.0/src/hidori_common/__init__.py
--rw-r--r--   0        0        0     1598 2022-09-17 18:21:42.518064 hidori-0.2.0/src/hidori_common/cli.py
--rw-r--r--   0        0        0        0 2022-09-21 23:39:18.473501 hidori-0.2.0/src/hidori_core/__init__.py
--rw-r--r--   0        0        0        0 2022-09-13 16:00:41.870165 hidori-0.2.0/src/hidori_core/compat/__init__.py
--rw-r--r--   0        0        0      398 2022-09-16 09:48:26.370444 hidori-0.2.0/src/hidori_core/compat/typing.py
--rw-r--r--   0        0        0      366 2022-09-21 23:40:10.884325 hidori-0.2.0/src/hidori_core/modules/__init__.py
--rw-r--r--   0        0        0     1632 2022-09-21 23:40:10.887325 hidori-0.2.0/src/hidori_core/modules/apt.py
--rw-r--r--   0        0        0     1248 2022-09-13 16:00:41.870165 hidori-0.2.0/src/hidori_core/modules/base.py
--rw-r--r--   0        0        0     3147 2022-09-21 23:39:35.192445 hidori-0.2.0/src/hidori_core/modules/dnf.py
--rw-r--r--   0        0        0      569 2022-09-11 11:07:35.028606 hidori-0.2.0/src/hidori_core/modules/hello.py
--rw-r--r--   0        0        0     1297 2022-09-16 02:18:43.133968 hidori-0.2.0/src/hidori_core/modules/hostname.py
--rw-r--r--   0        0        0      182 2022-09-20 23:26:01.574488 hidori-0.2.0/src/hidori_core/schema/__init__.py
--rw-r--r--   0        0        0     3202 2022-09-20 23:46:05.525449 hidori-0.2.0/src/hidori_core/schema/base.py
--rw-r--r--   0        0        0     1414 2022-09-18 23:10:03.234357 hidori-0.2.0/src/hidori_core/schema/constraints.py
--rw-r--r--   0        0        0      310 2022-09-13 16:00:41.870165 hidori-0.2.0/src/hidori_core/schema/errors.py
--rw-r--r--   0        0        0     3431 2022-09-20 23:44:29.181594 hidori-0.2.0/src/hidori_core/schema/fields.py
--rw-r--r--   0        0        0       75 2022-09-10 13:31:06.775495 hidori-0.2.0/src/hidori_core/utils/__init__.py
--rw-r--r--   0        0        0      951 2022-09-17 18:22:55.427760 hidori-0.2.0/src/hidori_core/utils/messenger.py
--rw-r--r--   0        0        0       78 2022-09-17 17:34:51.434308 hidori-0.2.0/src/hidori_pipelines/__init__.py
--rw-r--r--   0        0        0     1161 2022-09-20 23:40:56.072912 hidori-0.2.0/src/hidori_pipelines/group.py
--rw-r--r--   0        0        0     6225 2022-09-21 23:40:20.032294 hidori-0.2.0/src/hidori_pipelines/pipeline.py
--rw-r--r--   0        0        0        0 2022-09-09 14:22:24.331318 hidori-0.2.0/src/hidori_runner/__init__.py
--rw-r--r--   0        0        0        0 2022-09-10 00:56:01.716212 hidori-0.2.0/src/hidori_runner/drivers/__init__.py
--rw-r--r--   0        0        0        0 2022-09-10 00:55:46.519313 hidori-0.2.0/src/hidori_runner/drivers/local.py
--rw-r--r--   0        0        0        0 2022-09-10 00:55:51.325281 hidori-0.2.0/src/hidori_runner/drivers/ssh.py
--rw-r--r--   0        0        0      796 2022-09-15 23:59:35.573584 hidori-0.2.0/src/hidori_runner/executors/remote.py
--rw-r--r--   0        0        0        0 2022-09-09 11:08:46.659194 hidori-0.2.0/src/hidori_runner/transports/__init__.py
--rw-r--r--   0        0        0        0 2022-09-09 11:44:50.178584 hidori-0.2.0/src/hidori_runner/transports/docker.py
--rw-r--r--   0        0        0        0 2022-09-09 11:44:54.244568 hidori-0.2.0/src/hidori_runner/transports/podman.py
--rw-r--r--   0        0        0        0 2022-09-09 11:44:45.830602 hidori-0.2.0/src/hidori_runner/transports/ssh.py
--rw-r--r--   0        0        0     4717 1970-01-01 00:00:00.000000 hidori-0.2.0/setup.py
--rw-r--r--   0        0        0     3887 1970-01-01 00:00:00.000000 hidori-0.2.0/PKG-INFO
+-rw-r--r--   0        0        0    13827 2022-09-19 18:24:14.910300 hidori-0.3.0/LICENSE-EUPL
+-rw-r--r--   0        0        0     1074 2022-09-10 03:13:56.665275 hidori-0.3.0/LICENSE-MIT
+-rw-r--r--   0        0        0     2796 2023-06-27 00:26:45.165955 hidori-0.3.0/README.md
+-rw-r--r--   0        0        0     2073 2023-06-28 01:22:31.186946 hidori-0.3.0/pyproject.toml
+-rw-r--r--   0        0        0        0 2022-09-08 22:46:50.502067 hidori-0.3.0/src/hidori_cli/__init__.py
+-rw-r--r--   0        0        0        0 2022-09-09 09:24:10.431738 hidori-0.3.0/src/hidori_cli/apps/__init__.py
+-rw-r--r--   0        0        0     1698 2023-06-26 14:59:00.817132 hidori-0.3.0/src/hidori_cli/apps/base.py
+-rw-r--r--   0        0        0      199 2022-09-24 23:59:43.919359 hidori-0.3.0/src/hidori_cli/apps/hidori.py
+-rw-r--r--   0        0        0      212 2022-09-10 13:31:06.567494 hidori-0.3.0/src/hidori_cli/apps/pipeline.py
+-rw-r--r--   0        0        0      361 2022-09-24 23:51:18.257887 hidori-0.3.0/src/hidori_cli/commands/__init__.py
+-rw-r--r--   0        0        0     2002 2023-06-26 22:53:18.999485 hidori-0.3.0/src/hidori_cli/commands/base.py
+-rw-r--r--   0        0        0     1433 2023-06-27 00:36:50.976841 hidori-0.3.0/src/hidori_cli/commands/hidori.py
+-rw-r--r--   0        0        0      393 2023-06-26 00:05:05.687736 hidori-0.3.0/src/hidori_cli/commands/pipeline.py
+-rw-r--r--   0        0        0      639 2023-06-26 21:28:33.682274 hidori-0.3.0/src/hidori_cli/commands/pipeline_run.py
+-rw-r--r--   0        0        0      624 2023-06-26 22:52:28.648573 hidori-0.3.0/src/hidori_cli/fields/__init__.py
+-rw-r--r--   0        0        0     1437 2023-06-26 19:02:32.747378 hidori-0.3.0/src/hidori_cli/fields/base.py
+-rw-r--r--   0        0        0      474 2023-06-26 22:04:58.562110 hidori-0.3.0/src/hidori_cli/fields/boolean.py
+-rw-r--r--   0        0        0      484 2023-06-26 15:47:33.342508 hidori-0.3.0/src/hidori_cli/fields/extra_data.py
+-rw-r--r--   0        0        0     1394 2023-06-26 15:50:17.945375 hidori-0.3.0/src/hidori_cli/fields/filepath.py
+-rw-r--r--   0        0        0      578 2023-06-26 21:58:58.567436 hidori-0.3.0/src/hidori_cli/fields/text.py
+-rw-r--r--   0        0        0      579 2023-06-26 15:47:33.342508 hidori-0.3.0/src/hidori_cli/fields/version.py
+-rw-r--r--   0        0        0        0 2022-09-28 21:26:04.712398 hidori-0.3.0/src/hidori_cli/py.typed
+-rw-r--r--   0        0        0       75 2022-10-19 22:00:51.533352 hidori-0.3.0/src/hidori_common/__init__.py
+-rw-r--r--   0        0        0     1705 2023-06-26 00:07:30.731745 hidori-0.3.0/src/hidori_common/cli.py
+-rw-r--r--   0        0        0      953 2022-11-13 07:15:19.434648 hidori-0.3.0/src/hidori_common/dirs.py
+-rw-r--r--   0        0        0        0 2022-09-28 21:23:57.247109 hidori-0.3.0/src/hidori_common/py.typed
+-rw-r--r--   0        0        0      988 2023-06-27 20:12:30.065208 hidori-0.3.0/src/hidori_common/typings.py
+-rw-r--r--   0        0        0        0 2023-06-26 00:03:11.340730 hidori-0.3.0/src/hidori_core/__init__.py
+-rw-r--r--   0        0        0      366 2022-09-21 23:40:10.884325 hidori-0.3.0/src/hidori_core/modules/__init__.py
+-rw-r--r--   0        0        0     2123 2023-06-02 22:52:42.845056 hidori-0.3.0/src/hidori_core/modules/apt.py
+-rw-r--r--   0        0        0     1011 2022-10-19 21:58:41.079764 hidori-0.3.0/src/hidori_core/modules/base.py
+-rw-r--r--   0        0        0     3060 2023-06-02 22:52:42.847056 hidori-0.3.0/src/hidori_core/modules/dnf.py
+-rw-r--r--   0        0        0      538 2022-10-12 00:59:14.649125 hidori-0.3.0/src/hidori_core/modules/hello.py
+-rw-r--r--   0        0        0     1194 2022-09-26 00:28:26.394225 hidori-0.3.0/src/hidori_core/modules/hostname.py
+-rw-r--r--   0        0        0        0 2022-09-28 21:26:17.444327 hidori-0.3.0/src/hidori_core/py.typed
+-rw-r--r--   0        0        0      247 2022-10-16 19:46:22.053745 hidori-0.3.0/src/hidori_core/schema/__init__.py
+-rw-r--r--   0        0        0     2931 2022-09-30 23:41:01.548007 hidori-0.3.0/src/hidori_core/schema/base.py
+-rw-r--r--   0        0        0     1414 2023-05-30 01:04:18.449994 hidori-0.3.0/src/hidori_core/schema/constraints.py
+-rw-r--r--   0        0        0      310 2022-09-13 16:00:41.870165 hidori-0.3.0/src/hidori_core/schema/errors.py
+-rw-r--r--   0        0        0     3410 2023-06-02 22:52:42.849056 hidori-0.3.0/src/hidori_core/schema/fields.py
+-rw-r--r--   0        0        0       75 2022-09-10 13:31:06.775495 hidori-0.3.0/src/hidori_core/utils/__init__.py
+-rw-r--r--   0        0        0     1162 2022-10-19 21:58:41.079764 hidori-0.3.0/src/hidori_core/utils/messenger.py
+-rw-r--r--   0        0        0       78 2022-10-03 19:17:18.629342 hidori-0.3.0/src/hidori_pipelines/__init__.py
+-rw-r--r--   0        0        0     1686 2023-06-28 01:26:41.168786 hidori-0.3.0/src/hidori_pipelines/group.py
+-rw-r--r--   0        0        0     3090 2023-06-27 17:57:29.791741 hidori-0.3.0/src/hidori_pipelines/pipeline.py
+-rw-r--r--   0        0        0        0 2022-09-28 21:26:23.916291 hidori-0.3.0/src/hidori_pipelines/py.typed
+-rw-r--r--   0        0        0        0 2022-09-09 14:22:24.331318 hidori-0.3.0/src/hidori_runner/__init__.py
+-rw-r--r--   0        0        0      143 2022-10-03 19:15:07.731540 hidori-0.3.0/src/hidori_runner/drivers/__init__.py
+-rw-r--r--   0        0        0     4960 2023-06-27 22:55:38.367929 hidori-0.3.0/src/hidori_runner/drivers/base.py
+-rw-r--r--   0        0        0        0 2022-09-10 00:55:46.519313 hidori-0.3.0/src/hidori_runner/drivers/local.py
+-rw-r--r--   0        0        0      757 2023-06-27 22:55:41.590927 hidori-0.3.0/src/hidori_runner/drivers/ssh.py
+-rw-r--r--   0        0        0      666 2023-06-27 22:55:55.260920 hidori-0.3.0/src/hidori_runner/drivers/utils.py
+-rw-r--r--   0        0        0     2298 2022-11-10 20:26:44.099716 hidori-0.3.0/src/hidori_runner/executors/remote.py
+-rw-r--r--   0        0        0        0 2022-09-28 21:26:32.912240 hidori-0.3.0/src/hidori_runner/py.typed
+-rw-r--r--   0        0        0       82 2022-10-03 19:15:07.731540 hidori-0.3.0/src/hidori_runner/transports/__init__.py
+-rw-r--r--   0        0        0        0 2022-09-09 11:44:50.178584 hidori-0.3.0/src/hidori_runner/transports/docker.py
+-rw-r--r--   0        0        0        0 2022-09-09 11:44:54.244568 hidori-0.3.0/src/hidori_runner/transports/podman.py
+-rw-r--r--   0        0        0     2182 2023-06-27 20:01:07.605772 hidori-0.3.0/src/hidori_runner/transports/ssh.py
+-rw-r--r--   0        0        0      869 2023-06-27 00:06:41.297314 hidori-0.3.0/src/hidori_runner/transports/utils.py
+-rw-r--r--   0        0        0     3802 1970-01-01 00:00:00.000000 hidori-0.3.0/PKG-INFO
```

### Comparing `hidori-0.2.0/LICENSE-EUPL` & `hidori-0.3.0/LICENSE-EUPL`

 * *Files identical despite different names*

### Comparing `hidori-0.2.0/LICENSE-MIT` & `hidori-0.3.0/LICENSE-MIT`

 * *Files identical despite different names*

### Comparing `hidori-0.2.0/README.md` & `hidori-0.3.0/README.md`

 * *Files 19% similar despite different names*

```diff
@@ -1,37 +1,39 @@
 # Hidori
 
 [![PyPI](https://img.shields.io/pypi/v/hidori)](https://pypi.org/project/hidori/)
-[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/hidori-dev/hidori/main.svg)](https://results.pre-commit.ci/latest/github/hidori-dev/hidori/main)
+[![CI](https://github.com/hidori-dev/hidori/actions/workflows/ci.yml/badge.svg)](https://github.com/hidori-dev/hidori/actions/workflows/ci.yml)
 [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/hidori-dev/hidori)
 
-Hidori is a modern, agentless, zero-dependency[^1][^2] variation on updating system state. General rule of thumb is that changes to the system are only done if the requested state is different from the actual state. Hidori modules are idempotent if the system is already in the desired state.
-Every change in the target system is reported through the modules log as "affected".
+Hidori is a modern, agentless, zero-dependency[^1] variation on updating system state. General rule of thumb is that changes to the system are only done if the requested state is different from the actual state. Hidori modules are idempotent if the system is already in the desired state.
+Every change in the destination system is reported through the modules log as "affected".
 
-Hidori communicates with a target machine through appropriate protocol that is designated by the chosen driver.
+Hidori communicates with destination machines through appropriate protocol that is designated by the chosen driver.
+
+![Hidori demo](https://raw.githubusercontent.com/hidori-dev/hidori/main/assets/hidori_demo.gif)
 
 ## Install
 
 Depending on your environment you might wish to install Hidori globally or locally using chosen Python dependency manager such as poetry or pip.
-Ultimately, the choice is yours. Either way, Hidori is safe for your Python environment - it does not pull any dependencies from PyPI[^2].
+Ultimately, the choice is yours. Either way, Hidori is safe for your Python environment - it does not pull any dependencies from PyPI.
 
 Example using pip:
 ```sh
 pip install hidori
 ```
 
 ## Hello World
 
-With Hidori installed you need a single TOML file that provides where and what should be done. A simple 'hello world' example assuming that some machine is available at the given IP address:
+With Hidori installed you need a single TOML file that provides where and what should be done. A simple 'hello world' example assuming that some machine is available at the given target:
 
 ```toml
-[hosts]
+[destinations]
 
-  [hosts.vm]
-  ip = "192.168.122.31"
+  [destinations.vm]
+  target = "192.168.122.31"
   user = "root"
 
 [tasks]
 
   [tasks."Say hello"]
   module = "hello"
 ```
@@ -48,31 +50,29 @@
 [root@vm: Say hello]
 [16:03:19] OK: Hello from Linux debian 4.19.0-21-amd64
 ```
 
 ## Support
 
 In general, Hidori is based on Python 3.11, but `hidori_core` runs with any version of Python that is still supported.
-Reason for that is vast majority of target systems don't have the latest Python runtime installed, so therefore `hidori_core`
-which includes all the code that runs on a target system can be expected to be supported according to the following table:
+Reason for that is vast majority of destination systems don't have the latest Python runtime installed, so therefore `hidori_core`
+which includes all the code that runs on a destination system can be expected to be supported according to the following table:
 
 | Python Version |     EOL Date     |
 | -------------- | ---------------- |
-| 3.7            | July 2023        |
 | 3.8            | November 2024    |
 | 3.9            | November 2025    |
 | 3.10           | November 2026    |
 | 3.11           | November 2027(?) |
 
 ## Development
 
 The dev environment can be setup with poetry:
 ```sh
 poetry install
 ```
 
 [^1]: Except for the necessary runtime - python, and system libraries that are used by modules
-[^2]: typing-extensions are necessary until at least July 2023 when Python 3.7's support will end
 
 ## License
 
 Hidori is licensed under both the [MIT](LICENSE-MIT) and the [EUPL-1.2](LICENSE-EUPL) licenses.
```

### Comparing `hidori-0.2.0/src/hidori_cli/apps/base.py` & `hidori-0.3.0/src/hidori_cli/apps/base.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,30 +1,43 @@
 import argparse
 import re
 
 from hidori_cli.commands import COMMAND_REGISTRY, Command
-from hidori_cli.commands.base import BaseData
+from hidori_cli.commands.base import BASE_COMMAND_NAME, BaseData
 
 
 class BaseCLIApplication:
     def __init__(self) -> None:
         name_parts: list[str] = re.findall(".[^A-Z]*", type(self).__name__)[:-1]
         self.name = "-".join([p.lower() for p in name_parts])
         self.parser = argparse.ArgumentParser(description=self.__doc__)
         self._commands: dict[str, Command[BaseData]] = {}
         self._register_commands()
 
     def _register_commands(self) -> None:
-        subparsers = self.parser.add_subparsers(dest="subparser_name")
+        command_classes = COMMAND_REGISTRY[self.name].values()
+        # Conditionally create subparsers for the application parser only
+        # if there are any subcommands defined for this application.
+        if any([obj.name != BASE_COMMAND_NAME for obj in command_classes]):
+            subparsers = self.parser.add_subparsers(dest="subparser_name")
+        else:
+            subparsers = None
+
         for command_cls in COMMAND_REGISTRY[self.name].values():
-            subparser = subparsers.add_parser(
-                command_cls.name, help=command_cls.__doc__
-            )
-            self._commands[command_cls.name] = command_cls(subparser)
+            if command_cls.name == BASE_COMMAND_NAME:
+                parser_obj = self.parser
+            else:
+                assert subparsers is not None
+                parser_obj = subparsers.add_parser(
+                    command_cls.name, help=command_cls.__doc__
+                )
+            self._commands[command_cls.name] = command_cls(parser_obj)
 
     def run(self) -> None:
         parser_data = self.parser.parse_args()
-        subparser_name: str = parser_data.subparser_name
-        command = self._commands[subparser_name]
+        command_name: str = (
+            getattr(parser_data, "subparser_name", BASE_COMMAND_NAME)
+            or BASE_COMMAND_NAME
+        )
 
-        data = command.data_cls(**parser_data.__dict__)
-        command.execute(data)
+        command = self._commands[command_name]
+        command.run(parser_data.__dict__)
```

### Comparing `hidori-0.2.0/src/hidori_cli/commands/pipeline_run.py` & `hidori-0.3.0/src/hidori_cli/commands/pipeline_run.py`

 * *Files 23% similar despite different names*

```diff
@@ -1,22 +1,24 @@
+import pathlib
 from dataclasses import dataclass, field
 
 from hidori_cli.commands.base import BaseData, Command
 from hidori_pipelines import PipelineGroup
 
 
 @dataclass
 class PipelineRunData(BaseData):
-    # TODO: Filepath type with validation that file exists?
-    pipeline_file: str = field(metadata={"help": "Path to the TOML pipeline file"})
+    pipeline_path: pathlib.Path = field(
+        metadata={"help": "Path to the TOML pipeline file"}
+    )
 
 
 class PipelineRunCommand(Command[PipelineRunData]):
     """pipeline-run command"""
 
     data_cls = PipelineRunData
 
     def execute(self, data: PipelineRunData) -> None:
-        group = PipelineGroup.from_toml_path(data.pipeline_file)
+        group = PipelineGroup.from_toml_path(str(data.pipeline_path))
         for pipeline in group:
             pipeline.prepare()
             pipeline.run()
```

### Comparing `hidori-0.2.0/src/hidori_common/cli.py` & `hidori-0.3.0/src/hidori_common/cli.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,8 +1,9 @@
 import datetime
+import importlib.metadata
 
 
 class Colors:
     RED = "\033[31m"
     GREEN = "\033[32m"
     BLUE = "\033[34m"
     RESET = "\033[39m"
@@ -24,15 +25,19 @@
     "success": "OK",
     "error": "ERROR",
     "affected": "AFFECTED",
     "info": "INFO",
 }
 
 
-class CLIMessageWriter:
+def get_version() -> str:
+    return importlib.metadata.version("hidori")
+
+
+class ConsolePrinter:
     def __init__(self, *, user: str, target: str) -> None:
         self.user = user
         self.target = target
 
     def print_one(self, data: dict[str, str]) -> None:
         self._print_header(data["task"])
         self._print_entry(data["type"], data["message"])
@@ -55,8 +60,8 @@
         status = STATUS_MAP[message_type]
         print(
             f"[{curr_time}] {Modifiers.BOLD}{color}{status}:"
             f"{Colors.RESET if color else ''}{Modifiers.RESET} {message}"
         )
 
     def _get_current_time(self) -> str:
-        return datetime.datetime.now().strftime("%H:%M:%S")
+        return datetime.datetime.now().strftime(r"%b %d %H:%M:%S")
```

### Comparing `hidori-0.2.0/src/hidori_core/modules/apt.py` & `hidori-0.3.0/src/hidori_core/modules/apt.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,52 +1,66 @@
 import io
-from typing import Any, Dict, Optional
+from typing import Any, Dict, Literal, Optional
 
 try:
     import apt
 except ImportError:
-    apt = None
+    ...
 
-from hidori_core.compat.typing import Literal
 from hidori_core.modules.base import Module
 from hidori_core.schema import Schema
 from hidori_core.schema.constraints import Requires
 from hidori_core.utils.messenger import Messenger
 
 APT_STATE_INSTALLED = "installed"
+APT_STATE_REMOVED = "removed"
 
 
-def condition_state_installed(data: Dict[str, Any]) -> bool:
-    return data.get("state") == APT_STATE_INSTALLED
+def condition_state_requires_package(data: Dict[str, Any]) -> bool:
+    return data.get("state") in [APT_STATE_INSTALLED, APT_STATE_REMOVED]
 
 
 class AptSchema(Schema):
-    state: Literal["upgraded", "installed"] = Requires(
-        ["package"], data_conditions=[condition_state_installed]
+    state: Literal["upgraded", "installed", "removed"] = Requires(
+        ["package"], data_conditions=[condition_state_requires_package]
     )
     package: Optional[str]
 
 
 class AptModule(Module, name="apt", schema_cls=AptSchema):
     def execute(
-        self, validated_data: Dict[str, Any], messenger: Messenger
-    ) -> Dict[str, str]:
+        self, validated_data: Dict[str, Optional[str]], messenger: Messenger
+    ) -> None:
+        assert apt
+
         cache = apt.Cache(apt.progress.text.OpProgress(io.StringIO()))
         package_name = validated_data.get("package")
 
-        if validated_data["state"] == "installed":
+        if validated_data["state"] == APT_STATE_INSTALLED and package_name:
             apt_pkg = cache[package_name]
             if apt_pkg.is_installed:
                 messenger.queue_success(f"package {package_name} is already installed")
-                return {"state": "unaffected"}
+                return
 
             messenger.queue_info(
                 f"will install {apt_pkg.name} to version {apt_pkg.candidate.version}"
             )
 
             apt_pkg.mark_install()
             cache.commit()
             messenger.queue_affected(f"package {package_name} has been installed")
-            return {"state": "affected"}
+            return
+
+        if validated_data["state"] == APT_STATE_REMOVED and package_name:
+            apt_pkg = cache[package_name]
+            if not apt_pkg.is_installed:
+                messenger.queue_success(f"package {package_name} is not installed")
+                return
+
+            messenger.queue_info(f"will remove {apt_pkg.name}")
+
+            apt_pkg.mark_delete()
+            cache.commit()
+            messenger.queue_affected(f"package {package_name} has been removed  ")
+            return
 
         messenger.queue_error("internal error")
-        return {"state": "error"}
```

### Comparing `hidori-0.2.0/src/hidori_core/modules/dnf.py` & `hidori-0.3.0/src/hidori_core/modules/dnf.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,15 +1,14 @@
-from typing import Any, Dict, Optional
+from typing import Any, Dict, Literal, Optional
 
 try:
     import dnf
 except ImportError:
-    dnf = None
+    ...
 
-from hidori_core.compat.typing import Literal
 from hidori_core.modules.base import Module
 from hidori_core.schema.base import Schema
 from hidori_core.schema.constraints import Requires
 from hidori_core.utils import Messenger
 
 DNF_STATE_INSTALLED = "installed"
 DNF_STATE_UPGRADED = "upgraded"
@@ -24,62 +23,63 @@
         ["package"], data_conditions=[condition_state_installed]
     )
     package: Optional[str]
 
 
 class DnfModule(Module, name="dnf", schema_cls=DnfSchema):
     def execute(
-        self, validated_data: Dict[str, Any], messenger: Messenger
-    ) -> Dict[str, str]:
+        self, validated_data: Dict[str, Optional[str]], messenger: Messenger
+    ) -> None:
+        assert dnf
+
         base = dnf.Base()
         base.read_all_repos()
         base.fill_sack()
         package_name = validated_data.get("package")
 
-        if validated_data["state"] == "installed":
+        if validated_data["state"] == "installed" and package_name:
             # TODO: Only allow package to be a list and name it packages
             # TODO: Verify that package exists in repos
             # TODO: Allow to provide version with `package:version` or
             # `package:latest` notation
-            installed_query = base.sack.query().installed()
-            if installed_query.filter(name=package_name):
+            if base.sack.query().installed().filter(name=package_name).run():
                 messenger.queue_success(f"package {package_name} is already installed")
-                return {"state": "unaffected"}
+                return
 
+            # TODO: Handle package not existing (dnf.exceptions.PackageNotFoundError)
             base.install(package_name)
             base.resolve()
             base.download_packages(base.transaction.install_set)
 
             for package in base.transaction.install_set:
                 # TODO: verbose only, messenger should accept boolean parameter verbose
                 messenger.queue_info(
                     f"will install {package.name} to version "
                     f"{package.version}-{package.release}"
                 )
 
             base.do_transaction()
             messenger.queue_affected(f"package {package_name} has been installed")
-            return {"state": "affected"}
+            return
 
         if validated_data["state"] == "upgraded" and package_name is None:
             base.upgrade_all()
             base.resolve()
             base.download_packages(base.transaction.install_set)
 
             if not base.transaction.install_set:
                 messenger.queue_success("all packages are up to date")
-                return {"state": "unaffected"}
+                return
 
             package_count = len(base.transaction.install_set)
             for package in base.transaction.install_set:
                 # TODO: verbose only, messenger should accept boolean parameter verbose
                 messenger.queue_info(
                     f"will upgrade {package.name} to version "
                     f"{package.version}-{package.release}"
                 )
 
             base.do_transaction()
             messenger.queue_affected(f"performed upgrade of {package_count} packages")
-            return {"state": "affected"}
+            return
 
         messenger.queue_error("internal error")
-        return {"state": "error"}
```

### Comparing `hidori-0.2.0/src/hidori_core/modules/hello.py` & `hidori-0.3.0/src/hidori_core/modules/hello.py`

 * *Files 14% similar despite different names*

```diff
@@ -7,14 +7,13 @@
 
 
 class HelloSchema(Schema):
     ...
 
 
 class HelloModule(Module, name="hello", schema_cls=HelloSchema):
-    def execute(self, validated_data: Dict[str, object], messenger: Messenger):
+    def execute(self, validated_data: Dict[str, object], messenger: Messenger) -> None:
         uname_result = os.uname()
         messenger.queue_success(
             f"Hello from {uname_result.sysname} {uname_result.nodename} "
             f"{uname_result.release}"
         )
-        return {"state": "unaffected"}
```

### Comparing `hidori-0.2.0/src/hidori_core/modules/hostname.py` & `hidori-0.3.0/src/hidori_core/modules/hostname.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,39 +1,35 @@
 from typing import Dict
 
 try:
     import dbus
 except ImportError:
-    dbus = None
+    ...
 
 from hidori_core.modules.base import Module
 from hidori_core.schema import Schema
 from hidori_core.utils import Messenger
 
+BUS_NAME = "org.freedesktop.hostname1"
+
 
 class HostnameSchema(Schema):
     name: str
 
 
 class HostnameModule(Module, name="hostname", schema_cls=HostnameSchema):
-    def execute(
-        self, validated_data: Dict[str, str], messenger: Messenger
-    ) -> Dict[str, str]:
-        new_hostname = validated_data["name"]
+    def execute(self, validated_data: Dict[str, str], messenger: Messenger) -> None:
+        assert dbus
 
         sysbus = dbus.SystemBus()
-        hostnamed_proxy = sysbus.get_object(
-            "org.freedesktop.hostname1", "/org/freedesktop/hostname1"
-        )
+        hostnamed_proxy = sysbus.get_object(BUS_NAME, "/org/freedesktop/hostname1")
 
         dbus_iface = dbus.Interface(hostnamed_proxy, "org.freedesktop.DBus.Properties")
-        old_hostname = dbus_iface.Get("org.freedesktop.hostname1", "StaticHostname")
+        old_hostname = dbus_iface.Get(BUS_NAME, "StaticHostname")
+        new_hostname = validated_data["name"]
         if old_hostname == new_hostname:
             messenger.queue_success(f"hostname already set to {new_hostname}")
-            return {"state": "unaffected"}
-
-        # TODO: can only do that with escalated privileges
-        hostname_iface = dbus.Interface(hostnamed_proxy, "org.freedesktop.hostname1")
-        hostname_iface.SetStaticHostname(new_hostname, False)
-
-        messenger.queue_affected(f"hostname changed to {new_hostname}")
-        return {"state": "affected"}
+        else:
+            # TODO: can only do that with escalated privileges
+            hostname_iface = dbus.Interface(hostnamed_proxy, BUS_NAME)
+            hostname_iface.SetStaticHostname(new_hostname, False)
+            messenger.queue_affected(f"hostname changed to {new_hostname}")
```

### Comparing `hidori-0.2.0/src/hidori_core/schema/base.py` & `hidori-0.3.0/src/hidori_core/schema/base.py`

 * *Files 14% similar despite different names*

```diff
@@ -36,18 +36,17 @@
         ...
 
     def apply(self, schema: "Schema", data: Dict[str, Any]) -> None:
         ...
 
 
 class Schema:
-    # TODO: Add support for sub-schemas (especially for PipelineSchema)
     fields: Dict[str, Field]
 
-    def __init_subclass__(cls):
+    def __init_subclass__(cls) -> None:
         cls.fields = {}
         errors = {}
 
         for name, annotation in cls.__annotations__.items():
             if name == "fields":
                 continue
 
@@ -61,51 +60,47 @@
 
             cls.fields[name] = field_from_annotation(annotation)
 
         if errors:
             raise SchemaError(errors)
 
     def validate(self, data: Dict[str, Any]) -> Dict[str, Any]:
-        validated_data: Dict[str, Any] = {}
         errors = {}
 
         for name, field in self.fields.items():
             constraint = getattr(self, name, None)
             if constraint and isinstance(constraint, Constraint):
                 constraint.apply(self, data)
 
             try:
                 # TODO: No such field provided in data
                 field_data = data.get(name)
                 field.validate(field_data)
-                validated_data[name] = field_data
             except ValidationError as e:
                 errors[name] = str(e)
                 continue
             except SkipFieldError:
                 continue
 
         if errors:
             raise SchemaError(errors)
 
-        return validated_data
+        return data
 
 
 def field_from_annotation(annotation: Any, required: bool = True) -> Field:
     for field_cls in FIELDS_REGISTRY:
         field = field_cls.from_annotation(annotation, required)
         if field is not None:
             return field
 
     if annotation.__origin__ == Union:
-        # TODO: Impl unions other than Optional when necessary
         assert len(annotation.__args__) == 2
 
         required = False
         for base_type in annotation.__args__:
             if isinstance(None, base_type):
                 continue
 
             return field_from_annotation(base_type, required)
 
-    # TODO: Finish impl for other cases
     raise RuntimeError("internal error")
```

### Comparing `hidori-0.2.0/src/hidori_core/schema/constraints.py` & `hidori-0.3.0/src/hidori_core/schema/constraints.py`

 * *Files identical despite different names*

### Comparing `hidori-0.2.0/src/hidori_core/schema/fields.py` & `hidori-0.3.0/src/hidori_core/schema/fields.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,17 +1,12 @@
 import inspect
-from typing import Any, Dict, Optional, Tuple, Type
+from typing import Any, Dict, Literal, Optional, Tuple, Type
 
-from hidori_core.compat.typing import Literal
-from hidori_core.schema.base import (
-    Field,
-    Schema,
-    ValidationError,
-    field_from_annotation,
-)
+from hidori_core.schema.base import Field, Schema, field_from_annotation
+from hidori_core.schema.errors import ValidationError
 
 
 class Anything(Field):
     @classmethod
     def from_annotation(
         cls, annotation: Any, required: bool = True
     ) -> Optional["Anything"]:
```

### Comparing `hidori-0.2.0/src/hidori_core/utils/messenger.py` & `hidori-0.3.0/src/hidori_core/utils/messenger.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,35 +1,43 @@
 import json
-from typing import List
+from typing import Dict, List
 
 
 class Messenger:
     def __init__(self, task_name: str) -> None:
         self._task: str = task_name
-        self._messages: List[str] = []
+        self._messages: List[Dict[str, str]] = []
+
+    @property
+    def is_empty(self) -> bool:
+        return len(self._messages) == 0
+
+    @property
+    def has_errors(self) -> bool:
+        return any([m["type"] == "error" for m in self._messages])
 
     def queue(self, ty: str, message: str) -> None:
         self._messages.append(
-            json.dumps(
-                {
-                    "type": ty,
-                    "task": self._task,
-                    "message": message,
-                }
-            )
+            {
+                "type": ty,
+                "task": self._task,
+                "message": message,
+            }
         )
 
     def queue_success(self, message: str) -> None:
         self.queue(ty="success", message=message)
 
     def queue_error(self, message: str) -> None:
         self.queue(ty="error", message=message)
 
     def queue_affected(self, message: str) -> None:
         self.queue(ty="affected", message=message)
 
     def queue_info(self, message: str) -> None:
         self.queue(ty="info", message=message)
 
-    def flush(self):
+    def flush(self) -> None:
         while self._messages:
-            print(self._messages.pop(0))
+            print(json.dumps(self._messages.pop(0)))
+
+        self._messages = []
```

### Comparing `hidori-0.2.0/src/hidori_pipelines/group.py` & `hidori-0.3.0/src/hidori_pipelines/group.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,45 +1,52 @@
-from typing import Any, Iterable, Iterator
-
+import itertools
 import tomllib
+from typing import Any, Iterable, Iterator
 
 from hidori_core.schema import Schema
-from hidori_pipelines.pipeline import Pipeline
-
-
-class TargetSchema(Schema):
-    ip: str
-    user: str
+from hidori_pipelines.pipeline import DestinationData, Pipeline
+from hidori_runner.drivers import create_driver
 
 
 class PipelineSchema(Schema):
-    hosts: dict[str, TargetSchema]
+    destinations: dict[str, dict[str, Any]]
     tasks: dict[str, dict[str, Any]]
 
 
 class PipelineGroup(Iterable[Pipeline]):
     @classmethod
-    def from_toml_path(cls, path: str):
+    def from_toml_path(cls, path: str) -> "PipelineGroup":
         with open(path, "rb") as f:
             return cls(tomllib.load(f))
 
     def __init__(self, data: dict[str, Any]) -> None:
         schema = PipelineSchema()
         schema.validate(data)
 
-        self._hosts_data = [
-            {"target": host, "data": data} for host, data in data["hosts"].items()
+        self._destinations_data: list[DestinationData] = [
+            {"target": target, "driver": create_driver(destination_data)}
+            for target, destination_data in data["destinations"].items()
         ]
         self._pipeline_data = data["tasks"]
-        self._hosts = data["hosts"].keys()
         self._current = 0
 
     def __iter__(self) -> Iterator[Pipeline]:
         return self
 
     def __next__(self) -> Pipeline:
-        if self._current >= len(self._hosts_data):
+        if self._current >= len(self._destinations_data):
             raise StopIteration()
 
-        host_data = self._hosts_data[self._current]
+        destination_data = self._destinations_data[self._current]
         self._current += 1
-        return Pipeline(host_data, self._pipeline_data)
+        return Pipeline(destination_data, self._pipeline_data)
+
+    def run(self, batch_size: int | None = None):
+        # while pipelines := list(itertools.islice(self, batch_size)):
+        # for pipeline in pipelines:
+        # pipeline.prepare()
+        pipelines = self.create_prepared_pipelines()
+
+    def create_prepared_pipelines(self) -> Iterator[Pipeline]:
+        for pipeline in self:
+            pipeline.prepare()
+            yield pipeline
```

### Comparing `hidori-0.2.0/PKG-INFO` & `hidori-0.3.0/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,61 +1,62 @@
 Metadata-Version: 2.1
 Name: hidori
-Version: 0.2.0
+Version: 0.3.0
 Summary: A modern, agentless, zero-dependency system state assurance
 Home-page: https://github.com/hidori-dev/hidori
 License: MIT
 Author: Piotr Szpetkowski
 Author-email: piotr.szpetkowski@pyquest.space
 Requires-Python: >=3.11,<4.0
 Classifier: Development Status :: 2 - Pre-Alpha
 Classifier: Environment :: Console
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: European Union Public Licence 1.2 (EUPL 1.2)
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Topic :: System :: Installation/Setup
-Requires-Dist: typing-extensions (>=4.3.0,<5.0.0)
 Project-URL: Bug Tracker, https://github.com/hidori-dev/hidori/issues
 Project-URL: Changelog, https://github.com/hidori-dev/hidori/blob/main/CHANGELOG.md
 Project-URL: Repository, https://github.com/hidori-dev/hidori
 Description-Content-Type: text/markdown
 
 # Hidori
 
 [![PyPI](https://img.shields.io/pypi/v/hidori)](https://pypi.org/project/hidori/)
-[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/hidori-dev/hidori/main.svg)](https://results.pre-commit.ci/latest/github/hidori-dev/hidori/main)
+[![CI](https://github.com/hidori-dev/hidori/actions/workflows/ci.yml/badge.svg)](https://github.com/hidori-dev/hidori/actions/workflows/ci.yml)
 [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/hidori-dev/hidori)
 
-Hidori is a modern, agentless, zero-dependency[^1][^2] variation on updating system state. General rule of thumb is that changes to the system are only done if the requested state is different from the actual state. Hidori modules are idempotent if the system is already in the desired state.
-Every change in the target system is reported through the modules log as "affected".
+Hidori is a modern, agentless, zero-dependency[^1] variation on updating system state. General rule of thumb is that changes to the system are only done if the requested state is different from the actual state. Hidori modules are idempotent if the system is already in the desired state.
+Every change in the destination system is reported through the modules log as "affected".
+
+Hidori communicates with destination machines through appropriate protocol that is designated by the chosen driver.
 
-Hidori communicates with a target machine through appropriate protocol that is designated by the chosen driver.
+![Hidori demo](https://raw.githubusercontent.com/hidori-dev/hidori/main/assets/hidori_demo.gif)
 
 ## Install
 
 Depending on your environment you might wish to install Hidori globally or locally using chosen Python dependency manager such as poetry or pip.
-Ultimately, the choice is yours. Either way, Hidori is safe for your Python environment - it does not pull any dependencies from PyPI[^2].
+Ultimately, the choice is yours. Either way, Hidori is safe for your Python environment - it does not pull any dependencies from PyPI.
 
 Example using pip:
 ```sh
 pip install hidori
 ```
 
 ## Hello World
 
-With Hidori installed you need a single TOML file that provides where and what should be done. A simple 'hello world' example assuming that some machine is available at the given IP address:
+With Hidori installed you need a single TOML file that provides where and what should be done. A simple 'hello world' example assuming that some machine is available at the given target:
 
 ```toml
-[hosts]
+[destinations]
 
-  [hosts.vm]
-  ip = "192.168.122.31"
+  [destinations.vm]
+  target = "192.168.122.31"
   user = "root"
 
 [tasks]
 
   [tasks."Say hello"]
   module = "hello"
 ```
@@ -72,32 +73,30 @@
 [root@vm: Say hello]
 [16:03:19] OK: Hello from Linux debian 4.19.0-21-amd64
 ```
 
 ## Support
 
 In general, Hidori is based on Python 3.11, but `hidori_core` runs with any version of Python that is still supported.
-Reason for that is vast majority of target systems don't have the latest Python runtime installed, so therefore `hidori_core`
-which includes all the code that runs on a target system can be expected to be supported according to the following table:
+Reason for that is vast majority of destination systems don't have the latest Python runtime installed, so therefore `hidori_core`
+which includes all the code that runs on a destination system can be expected to be supported according to the following table:
 
 | Python Version |     EOL Date     |
 | -------------- | ---------------- |
-| 3.7            | July 2023        |
 | 3.8            | November 2024    |
 | 3.9            | November 2025    |
 | 3.10           | November 2026    |
 | 3.11           | November 2027(?) |
 
 ## Development
 
 The dev environment can be setup with poetry:
 ```sh
 poetry install
 ```
 
 [^1]: Except for the necessary runtime - python, and system libraries that are used by modules
-[^2]: typing-extensions are necessary until at least July 2023 when Python 3.7's support will end
 
 ## License
 
 Hidori is licensed under both the [MIT](LICENSE-MIT) and the [EUPL-1.2](LICENSE-EUPL) licenses.
```


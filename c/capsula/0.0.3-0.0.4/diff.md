# Comparing `tmp/capsula-0.0.3.tar.gz` & `tmp/capsula-0.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "capsula-0.0.3.tar", max compression
+gzip compressed data, was "capsula-0.0.4.tar", max compression
```

## Comparing `capsula-0.0.3.tar` & `capsula-0.0.4.tar`

### file list

```diff
@@ -1,10 +1,11 @@
--rw-r--r--   0        0        0     1074 2023-06-23 14:46:03.560678 capsula-0.0.3/LICENSE
--rw-r--r--   0        0        0     4107 2023-06-28 12:33:50.283621 capsula-0.0.3/README.md
--rw-r--r--   0        0        0       48 2023-06-28 11:47:35.793639 capsula-0.0.3/capsula/__init__.py
--rw-r--r--   0        0        0     1654 2023-06-28 11:47:35.793639 capsula-0.0.3/capsula/__main__.py
--rw-r--r--   0        0        0       22 2023-06-28 12:38:06.943652 capsula-0.0.3/capsula/_version.py
--rw-r--r--   0        0        0     2909 2023-06-28 12:06:12.283638 capsula-0.0.3/capsula/capture.py
--rw-r--r--   0        0        0     4487 2023-06-28 12:06:12.283638 capsula-0.0.3/capsula/context.py
--rw-r--r--   0        0        0      849 2023-06-28 11:47:35.803639 capsula-0.0.3/capsula/hash.py
--rw-r--r--   0        0        0     3436 2023-06-28 12:38:06.943652 capsula-0.0.3/pyproject.toml
--rw-r--r--   0        0        0     4671 1970-01-01 00:00:00.000000 capsula-0.0.3/PKG-INFO
+-rw-r--r--   0        0        0     1074 2023-06-23 14:46:03.560678 capsula-0.0.4/LICENSE
+-rw-r--r--   0        0        0     4919 2023-06-28 15:02:08.779507 capsula-0.0.4/README.md
+-rw-r--r--   0        0        0       48 2023-06-28 11:47:35.793639 capsula-0.0.4/capsula/__init__.py
+-rw-r--r--   0        0        0     2211 2023-06-28 15:02:08.779507 capsula-0.0.4/capsula/__main__.py
+-rw-r--r--   0        0        0       22 2023-06-28 15:04:01.839506 capsula-0.0.4/capsula/_version.py
+-rw-r--r--   0        0        0     2861 2023-06-28 15:02:08.779507 capsula-0.0.4/capsula/capture.py
+-rw-r--r--   0        0        0     4433 2023-06-28 15:02:08.779507 capsula-0.0.4/capsula/context.py
+-rw-r--r--   0        0        0      849 2023-06-28 11:47:35.803639 capsula-0.0.4/capsula/hash.py
+-rw-r--r--   0        0        0     1690 2023-06-28 15:02:08.779507 capsula-0.0.4/capsula/monitor.py
+-rw-r--r--   0        0        0     3651 2023-06-28 15:04:01.839506 capsula-0.0.4/pyproject.toml
+-rw-r--r--   0        0        0     5483 1970-01-01 00:00:00.000000 capsula-0.0.4/PKG-INFO
```

### Comparing `capsula-0.0.3/LICENSE` & `capsula-0.0.4/LICENSE`

 * *Files identical despite different names*

### Comparing `capsula-0.0.3/README.md` & `capsula-0.0.4/README.md`

 * *Files 19% similar despite different names*

```diff
@@ -22,15 +22,15 @@
 
 At the root of your project, create a `capsula.toml` file wit the following content:
 
 ```toml
 [capture]
 vault-directory = 'vault'
 
-subdirectory-template = '%Y%m%d_%H%M%S'
+capsule-template = '%Y%m%d_%H%M%S'
 
 include-cpu = false
 
 pre-capture-commands = [
     'poetry lock --check'
 ]
 
@@ -48,15 +48,15 @@
 ```
 
 
 ## Usage
 
 ### Context Capture
 
-Running `capsula capture` in the project root (the directory where `capsula.toml` is located) captures the execution context and stores it in a vault directory. The vault directory is specified in the `capsula.toml` file. The vault directory is organized by subdirectories, each of which contains the captured context of a single execution. The subdirectory name is generated using the `subdirectory-template` option in the `capsula.toml` file. The default template is `%Y%m%d_%H%M%S`, which generates a subdirectory name in the format of `YYYYMMDD_HHMMSS`. The context is stored in a JSON file named `context.json`.
+Running `capsula capture` in the project root (the directory where `capsula.toml` is located) captures the execution context and stores it in a vault directory. The vault directory is specified in the `capsula.toml` file. The vault directory is organized by subdirectories ("capsules"), each of which contains the captured context of a single execution. The capsule name is generated using the `capsule-template` option in the `capsula.toml` file. The default template is `%Y%m%d_%H%M%S`, which generates a capsule name in the format of `YYYYMMDD_HHMMSS`. The context is stored in a JSON file named `context.json`.
 
 Example of `context.json`:
 
 ```json
 {
     "platform": {
         "machine": "x86_64",
@@ -106,10 +106,48 @@
             "hash_algorithm": "sha256",
             "file_hash": "bd2ee84e4ab22528f89431ca4693c6db58aa304380b36cee7d3e21e19f756df2"
         }
     }
 }
 ```
 
+### Execution Monitoring
+
+Running `capsula monitor <commands>` in the project root (the directory where `capsula.toml` is located) monitors the execution of the specified commands. The context is logged in the `context.json` file in the capsule directory, and the command execution is logged in the `pre-run-info.json` and `post-run-info.json` files in the capsule directory.
+
+## Try it out
+
+### Prerequisites
+
+- [Poetry](https://python-poetry.org/docs/#installation)
+
+### Steps
+
+1. Clone this repository:
+
+```bash
+git clone git@github.com:shunichironomura/capsula.git
+```
+
+2. Install the package, including the examples:
+
+```bash
+poetry install --with examples
+```
+
+3. Run the example:
+
+Context capture:
+
+```bash
+capsula capture
+```
+
+Execution monitoring:
+
+```bash
+capsula monitor python examples/calculate_pi.py
+```
+
 ## Roadmap
 
 See [#1](https://github.com/shunichironomura/capsula/issues/1).
```

### Comparing `capsula-0.0.3/capsula/capture.py` & `capsula-0.0.4/capsula/capture.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from __future__ import annotations
 
 import logging
 import shlex
 import subprocess
-from datetime import datetime
+from datetime import UTC, datetime
 from pathlib import Path
 from typing import Literal
 
 from pydantic import BaseModel, Field
 
 from capsula.context import Context
 
@@ -27,15 +27,15 @@
     repositories: dict[str, Path] = Field(default_factory=dict)
 
 
 class CaptureConfig(BaseModel):
     """Configuration for the capture command."""
 
     vault_directory: Path
-    subdirectory_template: str
+    capsule_template: str
 
     # Whether to include the Capsula version in the output file.
     # include_capsula_version: bool = True # noqa: ERA001
 
     include_cpu: bool = True
 
     pre_capture_commands: list[str] = Field(default_factory=list)
@@ -47,29 +47,26 @@
     git: GitConfig = Field(default_factory=GitConfig)
 
     class Config:  # noqa: D106
         alias_generator = to_hyphen_case
         populate_by_name = False
         extra = "forbid"
 
-    _subdirectory: Path | None = None
+    _capsule_directory: Path | None = None
 
     @property
-    def subdirectory(self) -> Path:
-        if self._subdirectory is None:
-            self._subdirectory = self.vault_directory / datetime.now(tz=None).strftime(  # noqa: DTZ005
-                self.subdirectory_template,
+    def capsule(self) -> Path:
+        if self._capsule_directory is None:
+            self._capsule_directory = self.vault_directory / datetime.now(UTC).astimezone().strftime(
+                self.capsule_template,
             )
-        return self._subdirectory
+        return self._capsule_directory
 
 
-def capture(
-    *,
-    config: CaptureConfig,
-) -> None:
+def capture(*, config: CaptureConfig) -> Context:
     """Capture the context."""
     logger.debug(f"Capture config: {config}")
 
     logger.debug(f"CWD: {Path.cwd()}")
     for command in config.pre_capture_commands:
         logger.debug(f"Running pre-capture command: {command}")
         result = subprocess.run(shlex.split(command), capture_output=True, text=True)  # noqa: S603
@@ -80,20 +77,19 @@
             logger.error(f"Pre-capture command stderr: {result.stderr}")
             msg = f"Pre-capture command failed: {command}"
             raise RuntimeError(msg)
 
     logger.info("Capturing the context.")
 
     try:
-        config.subdirectory.mkdir(parents=True, exist_ok=False)
+        config.capsule.mkdir(parents=True, exist_ok=False)
     except FileExistsError:
-        logger.exception(f"Subdirectory already exists: {config.subdirectory}")
+        logger.exception(f"Capsule already exists: {config.capsule}")
         raise
 
     ctx = Context.capture(config)
 
     # Write the context to the output file.
-    ctx_json = ctx.model_dump_json(
-        indent=4,
-    )
-    with (config.subdirectory / "context.json").open("w") as output_file:
-        output_file.write(ctx_json)
+    with (config.capsule / "context.json").open("w") as output_file:
+        output_file.write(ctx.model_dump_json(indent=4))
+
+    return ctx
```

### Comparing `capsula-0.0.3/capsula/context.py` & `capsula-0.0.4/capsula/context.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,34 +1,32 @@
 from __future__ import annotations
 
 import os
 import platform as pf
 from abc import ABC, abstractmethod
 from pathlib import Path
 from shutil import copyfile
-from typing import TYPE_CHECKING, Literal, Self
+from typing import TYPE_CHECKING, Any, Literal, Self
 
 from cpuinfo import get_cpu_info
 from git.repo import Repo
 from pydantic import BaseModel, Field
 
 from capsula.hash import compute_hash
 
 if TYPE_CHECKING:
-    from collections.abc import Hashable
-
     from capsula.capture import CaptureConfig
 
 
 class ContextItem(BaseModel, ABC):
     """Base class for context items."""
 
     @classmethod
     @abstractmethod
-    def capture(cls, config: CaptureConfig) -> Self | dict[Hashable, Self]:
+    def capture(cls, config: CaptureConfig) -> Self | dict[Any, Self]:
         """Capture the context item."""
         raise NotImplementedError
 
 
 class Architecture(ContextItem):
     bits: str
     linkage: str
@@ -97,27 +95,27 @@
 class GitInfo(ContextItem):
     path: Path
     sha: str
     branch: str
     remotes: list[GitRemote]
 
     @classmethod
-    def capture(cls, config: CaptureConfig) -> dict[Path, Self]:
+    def capture(cls, config: CaptureConfig) -> dict[str, Self]:
         git_infos = {}
         for name, path in config.git.repositories.items():
             repo = Repo(path)
             git_infos[name] = cls(
                 path=path,
                 sha=repo.head.object.hexsha,
                 remotes=[GitRemote(name=remote.name, url=remote.url) for remote in repo.remotes],
                 branch=repo.active_branch.name,
             )
 
             diff = repo.git.diff()
-            with (config.subdirectory / f"{name}.diff").open("w") as diff_file:
+            with (config.capsule / f"{name}.diff").open("w") as diff_file:
                 diff_file.write(diff)
 
         return git_infos
 
 
 class FileContext(ContextItem):
     hash_algorithm: Literal["md5", "sha1", "sha256", "sha3"]
@@ -128,15 +126,15 @@
         files = {}
         for path, file_config in config.files.items():
             files[path] = cls(
                 hash=compute_hash(path, file_config.hash_algorithm),
                 hash_algorithm=file_config.hash_algorithm,
             )
             if file_config.copy_:
-                copyfile(path, config.subdirectory / path.name)
+                copyfile(path, config.capsule / path.name)
 
         return files
 
 
 class Context(ContextItem):
     """Execution context to be stored and used later."""
 
@@ -147,15 +145,15 @@
     # We use the default factory to avoid the overhead of getting the CPU info, which is slow.
     cpu: dict | None
 
     environment_variables: dict[str, str]
 
     cwd: Path
 
-    git: dict[Path, GitInfo]
+    git: dict[str, GitInfo]
 
     files: dict[Path, FileContext]
 
     @classmethod
     def capture(cls, config: CaptureConfig) -> Self:
         return cls(
             platform=Platform.capture(config),
```

### Comparing `capsula-0.0.3/capsula/hash.py` & `capsula-0.0.4/capsula/hash.py`

 * *Files identical despite different names*

### Comparing `capsula-0.0.3/pyproject.toml` & `capsula-0.0.4/pyproject.toml`

 * *Files 14% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "capsula"
-version = "0.0.3"
+version = "0.0.4"
 description = "A Python package to capture and reproduce command execution contexts"
 authors = ["Shunichiro Nomura <nomura@space.t.u-tokyo.ac.jp>"]
 license = "MIT"
 readme = "README.md"
 packages = [{include = "capsula"}]
 
 [tool.poetry.dependencies]
@@ -17,21 +17,31 @@
 [tool.poetry.group.dev.dependencies]
 ruff = ">=0.0.275"
 black = ">=23.3.0"
 mypy = ">=1.4.0"
 pre-commit = ">=3.3.3"
 pytest = ">=7.4.0"
 
+[tool.poetry.group.examples]
+optional = true
+
+[tool.poetry.group.examples.dependencies]
+numpy = ">=1.25.0"
+
 [tool.poetry.scripts]
 capsula = "capsula.__main__:main"
 
 [build-system]
 requires = ["poetry-core"]
 build-backend = "poetry.core.masonry.api"
 
+[[tool.mypy.overrides]]
+module = "cpuinfo"
+ignore_missing_imports = true
+
 [tool.black]
 line-length = 120
 include = '\.pyi?$'
 target-version = ["py311"]
 
 exclude = '''
 /(
@@ -76,24 +86,27 @@
     "D407", # Missing dashed underline after section
 ]
 
 [tool.ruff.per-file-ignores]
 "tests/*" = [
     # "ANN201",
 ]
+"examples/*" = [
+    "INP001",
+]
 # "scripts/*" = [
 #     "INP001",
 # ]
 
 [tool.tbump]
 # Uncomment this if your project is hosted on GitHub:
 github_url = "https://github.com/shunichironomura/capsula/"
 
 [tool.tbump.version]
-current = "0.0.3"
+current = "0.0.4"
 
 # Example of a semver regexp.
 # Make sure this matches current_version before
 # using tbump
 regex = '''
   (?P<major>\d+)
   \.
```

### Comparing `capsula-0.0.3/PKG-INFO` & `capsula-0.0.4/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: capsula
-Version: 0.0.3
+Version: 0.0.4
 Summary: A Python package to capture and reproduce command execution contexts
 License: MIT
 Author: Shunichiro Nomura
 Author-email: nomura@space.t.u-tokyo.ac.jp
 Requires-Python: >=3.11
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
@@ -39,15 +39,15 @@
 
 At the root of your project, create a `capsula.toml` file wit the following content:
 
 ```toml
 [capture]
 vault-directory = 'vault'
 
-subdirectory-template = '%Y%m%d_%H%M%S'
+capsule-template = '%Y%m%d_%H%M%S'
 
 include-cpu = false
 
 pre-capture-commands = [
     'poetry lock --check'
 ]
 
@@ -65,15 +65,15 @@
 ```
 
 
 ## Usage
 
 ### Context Capture
 
-Running `capsula capture` in the project root (the directory where `capsula.toml` is located) captures the execution context and stores it in a vault directory. The vault directory is specified in the `capsula.toml` file. The vault directory is organized by subdirectories, each of which contains the captured context of a single execution. The subdirectory name is generated using the `subdirectory-template` option in the `capsula.toml` file. The default template is `%Y%m%d_%H%M%S`, which generates a subdirectory name in the format of `YYYYMMDD_HHMMSS`. The context is stored in a JSON file named `context.json`.
+Running `capsula capture` in the project root (the directory where `capsula.toml` is located) captures the execution context and stores it in a vault directory. The vault directory is specified in the `capsula.toml` file. The vault directory is organized by subdirectories ("capsules"), each of which contains the captured context of a single execution. The capsule name is generated using the `capsule-template` option in the `capsula.toml` file. The default template is `%Y%m%d_%H%M%S`, which generates a capsule name in the format of `YYYYMMDD_HHMMSS`. The context is stored in a JSON file named `context.json`.
 
 Example of `context.json`:
 
 ```json
 {
     "platform": {
         "machine": "x86_64",
@@ -123,11 +123,49 @@
             "hash_algorithm": "sha256",
             "file_hash": "bd2ee84e4ab22528f89431ca4693c6db58aa304380b36cee7d3e21e19f756df2"
         }
     }
 }
 ```
 
+### Execution Monitoring
+
+Running `capsula monitor <commands>` in the project root (the directory where `capsula.toml` is located) monitors the execution of the specified commands. The context is logged in the `context.json` file in the capsule directory, and the command execution is logged in the `pre-run-info.json` and `post-run-info.json` files in the capsule directory.
+
+## Try it out
+
+### Prerequisites
+
+- [Poetry](https://python-poetry.org/docs/#installation)
+
+### Steps
+
+1. Clone this repository:
+
+```bash
+git clone git@github.com:shunichironomura/capsula.git
+```
+
+2. Install the package, including the examples:
+
+```bash
+poetry install --with examples
+```
+
+3. Run the example:
+
+Context capture:
+
+```bash
+capsula capture
+```
+
+Execution monitoring:
+
+```bash
+capsula monitor python examples/calculate_pi.py
+```
+
 ## Roadmap
 
 See [#1](https://github.com/shunichironomura/capsula/issues/1).
```


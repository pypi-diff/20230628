# Comparing `tmp/snk-0.8.0.tar.gz` & `tmp/snk-0.9.0.tar.gz`

## Comparing `snk-0.8.0.tar` & `snk-0.9.0.tar`

### file list

```diff
@@ -1,50 +1,54 @@
--rw-r--r--   0        0        0       83 2020-02-02 00:00:00.000000 snk-0.8.0/Dockerfile
--rw-r--r--   0        0        0      670 2020-02-02 00:00:00.000000 snk-0.8.0/mkdocs.yml
--rw-r--r--   0        0        0      476 2020-02-02 00:00:00.000000 snk-0.8.0/.github/workflows/mkdocs.yml
--rw-r--r--   0        0        0      613 2020-02-02 00:00:00.000000 snk-0.8.0/.github/workflows/publish.yml
--rw-r--r--   0        0        0      564 2020-02-02 00:00:00.000000 snk-0.8.0/.github/workflows/tests.yml
--rw-r--r--   0        0        0       15 2020-02-02 00:00:00.000000 snk-0.8.0/docs/CNAME
--rw-r--r--   0        0        0     3073 2020-02-02 00:00:00.000000 snk-0.8.0/docs/index.md
--rw-r--r--   0        0        0     3997 2020-02-02 00:00:00.000000 snk-0.8.0/docs/managing_pipelines.md
--rw-r--r--   0        0        0     8994 2020-02-02 00:00:00.000000 snk-0.8.0/docs/pipeline_packages.md
--rw-r--r--   0        0        0     4955 2020-02-02 00:00:00.000000 snk-0.8.0/docs/snk_config_file.md
--rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 snk-0.8.0/docs/reference/cli.md
--rw-r--r--   0        0        0       16 2020-02-02 00:00:00.000000 snk-0.8.0/docs/reference/errors.md
--rw-r--r--   0        0        0       14 2020-02-02 00:00:00.000000 snk-0.8.0/docs/reference/main.md
--rw-r--r--   0        0        0       14 2020-02-02 00:00:00.000000 snk-0.8.0/docs/reference/nest.md
--rw-r--r--   0        0        0       18 2020-02-02 00:00:00.000000 snk-0.8.0/docs/reference/pipeline.md
--rw-r--r--   0        0        0      125 2020-02-02 00:00:00.000000 snk-0.8.0/snk/__about__.py
--rw-r--r--   0        0        0      154 2020-02-02 00:00:00.000000 snk-0.8.0/snk/__init__.py
--rw-r--r--   0        0        0      401 2020-02-02 00:00:00.000000 snk-0.8.0/snk/errors.py
--rw-r--r--   0        0        0     5868 2020-02-02 00:00:00.000000 snk-0.8.0/snk/main.py
--rw-r--r--   0        0        0    16434 2020-02-02 00:00:00.000000 snk-0.8.0/snk/nest.py
--rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 snk-0.8.0/snk/pipeline.py
--rw-r--r--   0        0        0      279 2020-02-02 00:00:00.000000 snk-0.8.0/snk/cli/__init__.py
--rw-r--r--   0        0        0    20042 2020-02-02 00:00:00.000000 snk-0.8.0/snk/cli/cli.py
--rw-r--r--   0        0        0     6981 2020-02-02 00:00:00.000000 snk-0.8.0/snk/cli/config.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 snk-0.8.0/snk/cli/options.py
--rw-r--r--   0        0        0     9225 2020-02-02 00:00:00.000000 snk-0.8.0/snk/cli/utils.py
--rw-r--r--   0        0        0     6148 2020-02-02 00:00:00.000000 snk-0.8.0/tests/.DS_Store
--rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 snk-0.8.0/tests/__init__.py
--rw-r--r--   0        0        0     1625 2020-02-02 00:00:00.000000 snk-0.8.0/tests/conftest.py
--rw-r--r--   0        0        0     1504 2020-02-02 00:00:00.000000 snk-0.8.0/tests/test_nest.py
--rw-r--r--   0        0        0     1671 2020-02-02 00:00:00.000000 snk-0.8.0/tests/test_pipline_cli.py
--rw-r--r--   0        0        0     1470 2020-02-02 00:00:00.000000 snk-0.8.0/tests/test_snk.py
--rw-r--r--   0        0        0     2389 2020-02-02 00:00:00.000000 snk-0.8.0/tests/test_snk_config.py
--rw-r--r--   0        0        0      581 2020-02-02 00:00:00.000000 snk-0.8.0/tests/utils.py
--rw-r--r--   0        0        0     9605 2020-02-02 00:00:00.000000 snk-0.8.0/tests/data/artic_v4.1.bed
--rw-r--r--   0        0        0      907 2020-02-02 00:00:00.000000 snk-0.8.0/tests/data/config.yaml
--rw-r--r--   0        0        0   242003 2020-02-02 00:00:00.000000 snk-0.8.0/tests/data/cov.fasta
--rwxr-xr-x   0        0        0      297 2020-02-02 00:00:00.000000 snk-0.8.0/tests/data/bin/snk-basic-pipeline
--rw-r--r--   0        0        0      198 2020-02-02 00:00:00.000000 snk-0.8.0/tests/data/pipeline/.snk
--rw-r--r--   0        0        0       74 2020-02-02 00:00:00.000000 snk-0.8.0/tests/data/pipeline/cli.py
--rw-r--r--   0        0        0       40 2020-02-02 00:00:00.000000 snk-0.8.0/tests/data/pipeline/config.yaml
--rw-r--r--   0        0        0        4 2020-02-02 00:00:00.000000 snk-0.8.0/tests/data/pipeline/resources/data.txt
--rw-r--r--   0        0        0      156 2020-02-02 00:00:00.000000 snk-0.8.0/tests/data/pipeline/workflow/Snakefile
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 snk-0.8.0/tests/data/pipeline/workflow/envs/base.yml
--rw-r--r--   0        0        0        8 2020-02-02 00:00:00.000000 snk-0.8.0/tests/data/pipeline/workflow/profiles/base/config.yaml
--rw-r--r--   0        0        0      118 2020-02-02 00:00:00.000000 snk-0.8.0/.gitignore
--rw-r--r--   0        0        0     1101 2020-02-02 00:00:00.000000 snk-0.8.0/LICENSE.txt
--rw-r--r--   0        0        0     2848 2020-02-02 00:00:00.000000 snk-0.8.0/README.md
--rw-r--r--   0        0        0     1681 2020-02-02 00:00:00.000000 snk-0.8.0/pyproject.toml
--rw-r--r--   0        0        0     3834 2020-02-02 00:00:00.000000 snk-0.8.0/PKG-INFO
+-rw-r--r--   0        0        0       83 2020-02-02 00:00:00.000000 snk-0.9.0/Dockerfile
+-rw-r--r--   0        0        0      670 2020-02-02 00:00:00.000000 snk-0.9.0/mkdocs.yml
+-rw-r--r--   0        0        0      476 2020-02-02 00:00:00.000000 snk-0.9.0/.github/workflows/mkdocs.yml
+-rw-r--r--   0        0        0      613 2020-02-02 00:00:00.000000 snk-0.9.0/.github/workflows/publish.yml
+-rw-r--r--   0        0        0      564 2020-02-02 00:00:00.000000 snk-0.9.0/.github/workflows/tests.yml
+-rw-r--r--   0        0        0       15 2020-02-02 00:00:00.000000 snk-0.9.0/docs/CNAME
+-rw-r--r--   0        0        0     3073 2020-02-02 00:00:00.000000 snk-0.9.0/docs/index.md
+-rw-r--r--   0        0        0     3997 2020-02-02 00:00:00.000000 snk-0.9.0/docs/managing_pipelines.md
+-rw-r--r--   0        0        0     8994 2020-02-02 00:00:00.000000 snk-0.9.0/docs/pipeline_packages.md
+-rw-r--r--   0        0        0     4955 2020-02-02 00:00:00.000000 snk-0.9.0/docs/snk_config_file.md
+-rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 snk-0.9.0/docs/reference/cli.md
+-rw-r--r--   0        0        0       16 2020-02-02 00:00:00.000000 snk-0.9.0/docs/reference/errors.md
+-rw-r--r--   0        0        0       14 2020-02-02 00:00:00.000000 snk-0.9.0/docs/reference/main.md
+-rw-r--r--   0        0        0       14 2020-02-02 00:00:00.000000 snk-0.9.0/docs/reference/nest.md
+-rw-r--r--   0        0        0       18 2020-02-02 00:00:00.000000 snk-0.9.0/docs/reference/pipeline.md
+-rw-r--r--   0        0        0      125 2020-02-02 00:00:00.000000 snk-0.9.0/snk/__about__.py
+-rw-r--r--   0        0        0      154 2020-02-02 00:00:00.000000 snk-0.9.0/snk/__init__.py
+-rw-r--r--   0        0        0      401 2020-02-02 00:00:00.000000 snk-0.9.0/snk/errors.py
+-rw-r--r--   0        0        0     5868 2020-02-02 00:00:00.000000 snk-0.9.0/snk/main.py
+-rw-r--r--   0        0        0    16434 2020-02-02 00:00:00.000000 snk-0.9.0/snk/nest.py
+-rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 snk-0.9.0/snk/pipeline.py
+-rw-r--r--   0        0        0      279 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/__init__.py
+-rw-r--r--   0        0        0    19432 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/cli.py
+-rw-r--r--   0        0        0     6981 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/config.py
+-rw-r--r--   0        0        0     1603 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/dynamic_typer.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/options.py
+-rw-r--r--   0        0        0     9225 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/utils.py
+-rw-r--r--   0        0        0     5082 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/workflow.py
+-rw-r--r--   0        0        0       23 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/subcommands/__init__.py
+-rw-r--r--   0        0        0     3383 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/subcommands/env.py
+-rw-r--r--   0        0        0     6148 2020-02-02 00:00:00.000000 snk-0.9.0/tests/.DS_Store
+-rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 snk-0.9.0/tests/__init__.py
+-rw-r--r--   0        0        0     1625 2020-02-02 00:00:00.000000 snk-0.9.0/tests/conftest.py
+-rw-r--r--   0        0        0     1504 2020-02-02 00:00:00.000000 snk-0.9.0/tests/test_nest.py
+-rw-r--r--   0        0        0     1671 2020-02-02 00:00:00.000000 snk-0.9.0/tests/test_pipline_cli.py
+-rw-r--r--   0        0        0     1470 2020-02-02 00:00:00.000000 snk-0.9.0/tests/test_snk.py
+-rw-r--r--   0        0        0     2389 2020-02-02 00:00:00.000000 snk-0.9.0/tests/test_snk_config.py
+-rw-r--r--   0        0        0      581 2020-02-02 00:00:00.000000 snk-0.9.0/tests/utils.py
+-rw-r--r--   0        0        0     9605 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/artic_v4.1.bed
+-rw-r--r--   0        0        0      907 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/config.yaml
+-rw-r--r--   0        0        0   242003 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/cov.fasta
+-rwxr-xr-x   0        0        0      297 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/bin/snk-basic-pipeline
+-rw-r--r--   0        0        0       74 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/pipeline/cli.py
+-rw-r--r--   0        0        0       40 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/pipeline/config.yaml
+-rw-r--r--   0        0        0      198 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/pipeline/snk.yaml
+-rw-r--r--   0        0        0        4 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/pipeline/resources/data.txt
+-rw-r--r--   0        0        0      156 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/pipeline/workflow/Snakefile
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/pipeline/workflow/envs/base.yml
+-rw-r--r--   0        0        0        8 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/pipeline/workflow/profiles/base/config.yaml
+-rw-r--r--   0        0        0      118 2020-02-02 00:00:00.000000 snk-0.9.0/.gitignore
+-rw-r--r--   0        0        0     1101 2020-02-02 00:00:00.000000 snk-0.9.0/LICENSE.txt
+-rw-r--r--   0        0        0     2848 2020-02-02 00:00:00.000000 snk-0.9.0/README.md
+-rw-r--r--   0        0        0     1681 2020-02-02 00:00:00.000000 snk-0.9.0/pyproject.toml
+-rw-r--r--   0        0        0     3834 2020-02-02 00:00:00.000000 snk-0.9.0/PKG-INFO
```

### Comparing `snk-0.8.0/mkdocs.yml` & `snk-0.9.0/mkdocs.yml`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/.github/workflows/publish.yml` & `snk-0.9.0/.github/workflows/publish.yml`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/.github/workflows/tests.yml` & `snk-0.9.0/.github/workflows/tests.yml`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/docs/index.md` & `snk-0.9.0/docs/index.md`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/docs/managing_pipelines.md` & `snk-0.9.0/docs/managing_pipelines.md`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/docs/pipeline_packages.md` & `snk-0.9.0/docs/pipeline_packages.md`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/docs/snk_config_file.md` & `snk-0.9.0/docs/snk_config_file.md`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/snk/main.py` & `snk-0.9.0/snk/main.py`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/snk/nest.py` & `snk-0.9.0/snk/nest.py`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/snk/pipeline.py` & `snk-0.9.0/snk/pipeline.py`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/snk/cli/cli.py` & `snk-0.9.0/snk/cli/cli.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,37 +1,39 @@
 import inspect
 import platform
 
 import sys
 import typer
 from pathlib import Path
-from typing import Optional, List, Callable
+from typing import Optional, List
 import subprocess
 import shutil
 import os
 from contextlib import contextmanager
 
 import snakemake
 from rich.console import Console
 from rich.syntax import Syntax
 from art import text2art
 
+from snk.cli.dynamic_typer import DynamicTyper
+from snk.cli.subcommands import EnvApp
 
 from .config import (
     SnkConfig,
     get_config_from_pipeline_dir,
     load_pipeline_snakemake_config,
 )
 from .utils import add_dynamic_options, build_dynamic_cli_options, parse_config_args, dag_filetype_callback
 from snk.pipeline import Pipeline
 
 
-class CLI:
+class CLI(DynamicTyper):
     """
-    Constructor for the CLI class.
+    Constructor for the dynamic Snk CLI class.
     Args:
       pipeline_dir_path (Path): Path to the pipeline directory.
     Side Effects:
       Initializes the CLI class.
     Examples:
       >>> CLI(Path('/path/to/pipeline'))
     """
@@ -105,60 +107,38 @@
             invoke_without_command=True,
             context_settings={"help_option_names": ["-h", "--help"]},
         )
         self.register_command(
             self.info, help="Display information about current pipeline install."
         )
         self.register_command(self.config, help="Access the pipeline configuration.")
-        self.register_command(self.env, help="Access the pipeline conda environments.")
-        self.register_command(self.profile, help="Access the pipeline profiles.")
+        if self.pipeline.environments:
+            env_app = EnvApp(
+                pipeline=self.pipeline, 
+                conda_prefix_dir=self.conda_prefix_dir,
+                snakemake_config=self.snakemake_config,
+                snakefile=self.snakefile,
+            )
+            self.register_group(
+                env_app,
+                name="env",
+                help="Access the pipeline conda environments."
+            )
+        if self.pipeline.profiles:
+            self.register_command(self.profile, help="Access the pipeline profiles.")
         self.register_command(
             add_dynamic_options(self.options)(self.run),
-            help="Run the dynamically generated pipeline CLI.\n\nAll unrecognized arguments are passed onto Snakemake.",
+            help="Run the Snakemake pipeline.\n\nAll unrecognized arguments are passed onto Snakemake.",
             context_settings={
                 "allow_extra_args": True,
                 "ignore_unknown_options": True,
                 "help_option_names": ["-h", "--help"],
             },
         )
 
-    def __call__(self):
-        """
-        Invoke the CLI.
-        Side Effects:
-          Invokes the CLI.
-        Examples:
-          >>> CLI(Path('/path/to/pipeline'))()
-        """
-        self.app()
-
-    def register_command(self, command: Callable, **command_kwargs) -> None:
-        """
-        Register a command to the CLI.
-        Args:
-          command (Callable): The command to register.
-        Side Effects:
-          Registers the command to the CLI.
-        Examples:
-          >>> CLI.register_command(my_command)
-        """
-        self.app.command(**command_kwargs)(command)
-
-    def register_callback(self, command: Callable, **command_kwargs) -> None:
-        """
-        Register a callback to the CLI.
-        Args:
-          command (Callable): The callback to register.
-        Side Effects:
-          Registers the callback to the CLI.
-        Examples:
-          >>> CLI.register_callback(my_callback)
-        """
-        self.app.callback(**command_kwargs)(command)
-
     def create_logo(self, tagline="A Snakemake pipeline CLI generated with snk", font="small"):
         """
         Create a logo for the CLI.
         Args:
           font (str): The font to use for the logo.
         Returns:
           str: The logo.
@@ -273,17 +253,14 @@
                 if copied_resource.exists():
                     if self.verbose:
                         typer.secho(
                             f"Deleting '{copied_resource.name}' resource...",
                             fg=typer.colors.YELLOW,
                         )
                     remove_resource(copied_resource)
-    def error(self, msg):
-        typer.secho(msg, fg="red")
-        raise typer.Exit(1)
     
     def run(
         self,
         ctx: typer.Context,
         target: str = typer.Argument(
             None, help="File to generate. If None will run the pipeline 'all' rule."
         ),
```

### Comparing `snk-0.8.0/snk/cli/config.py` & `snk-0.9.0/snk/cli/config.py`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/snk/cli/utils.py` & `snk-0.9.0/snk/cli/utils.py`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/tests/.DS_Store` & `snk-0.9.0/tests/.DS_Store`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/tests/conftest.py` & `snk-0.9.0/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/tests/test_nest.py` & `snk-0.9.0/tests/test_nest.py`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/tests/test_pipline_cli.py` & `snk-0.9.0/tests/test_pipline_cli.py`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/tests/test_snk.py` & `snk-0.9.0/tests/test_snk.py`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/tests/test_snk_config.py` & `snk-0.9.0/tests/test_snk_config.py`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/tests/utils.py` & `snk-0.9.0/tests/utils.py`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/tests/data/artic_v4.1.bed` & `snk-0.9.0/tests/data/artic_v4.1.bed`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/tests/data/config.yaml` & `snk-0.9.0/tests/data/config.yaml`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/tests/data/cov.fasta` & `snk-0.9.0/tests/data/cov.fasta`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/LICENSE.txt` & `snk-0.9.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/README.md` & `snk-0.9.0/README.md`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/pyproject.toml` & `snk-0.9.0/pyproject.toml`

 * *Files identical despite different names*

### Comparing `snk-0.8.0/PKG-INFO` & `snk-0.9.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: snk
-Version: 0.8.0
+Version: 0.9.0
 Project-URL: Documentation, https://github.com/wytamma/snk#readme
 Project-URL: Issues, https://github.com/wytamma/snk/issues
 Project-URL: Source, https://github.com/wytamma/snk
 Author-email: Wytamma Wirth <wytamma.wirth@me.com>
 License-Expression: MIT
 License-File: LICENSE.txt
 Classifier: Development Status :: 4 - Beta
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: snk Version: 0.8.0 Project-URL: Documentation,
+Metadata-Version: 2.1 Name: snk Version: 0.9.0 Project-URL: Documentation,
 https://github.com/wytamma/snk#readme Project-URL: Issues, https://github.com/
 wytamma/snk/issues Project-URL: Source, https://github.com/wytamma/snk Author-
 email: Wytamma Wirth
 wirth@me.com> License-Expression: MIT License-File: LICENSE.txt Classifier:
 Development Status :: 4 - Beta Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3.7 Classifier: Programming
 Language :: Python :: 3.8 Classifier: Programming Language :: Python :: 3.9
```


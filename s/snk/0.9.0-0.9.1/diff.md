# Comparing `tmp/snk-0.9.0.tar.gz` & `tmp/snk-0.9.1.tar.gz`

## Comparing `snk-0.9.0.tar` & `snk-0.9.1.tar`

### file list

```diff
@@ -1,54 +1,57 @@
--rw-r--r--   0        0        0       83 2020-02-02 00:00:00.000000 snk-0.9.0/Dockerfile
--rw-r--r--   0        0        0      670 2020-02-02 00:00:00.000000 snk-0.9.0/mkdocs.yml
--rw-r--r--   0        0        0      476 2020-02-02 00:00:00.000000 snk-0.9.0/.github/workflows/mkdocs.yml
--rw-r--r--   0        0        0      613 2020-02-02 00:00:00.000000 snk-0.9.0/.github/workflows/publish.yml
--rw-r--r--   0        0        0      564 2020-02-02 00:00:00.000000 snk-0.9.0/.github/workflows/tests.yml
--rw-r--r--   0        0        0       15 2020-02-02 00:00:00.000000 snk-0.9.0/docs/CNAME
--rw-r--r--   0        0        0     3073 2020-02-02 00:00:00.000000 snk-0.9.0/docs/index.md
--rw-r--r--   0        0        0     3997 2020-02-02 00:00:00.000000 snk-0.9.0/docs/managing_pipelines.md
--rw-r--r--   0        0        0     8994 2020-02-02 00:00:00.000000 snk-0.9.0/docs/pipeline_packages.md
--rw-r--r--   0        0        0     4955 2020-02-02 00:00:00.000000 snk-0.9.0/docs/snk_config_file.md
--rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 snk-0.9.0/docs/reference/cli.md
--rw-r--r--   0        0        0       16 2020-02-02 00:00:00.000000 snk-0.9.0/docs/reference/errors.md
--rw-r--r--   0        0        0       14 2020-02-02 00:00:00.000000 snk-0.9.0/docs/reference/main.md
--rw-r--r--   0        0        0       14 2020-02-02 00:00:00.000000 snk-0.9.0/docs/reference/nest.md
--rw-r--r--   0        0        0       18 2020-02-02 00:00:00.000000 snk-0.9.0/docs/reference/pipeline.md
--rw-r--r--   0        0        0      125 2020-02-02 00:00:00.000000 snk-0.9.0/snk/__about__.py
--rw-r--r--   0        0        0      154 2020-02-02 00:00:00.000000 snk-0.9.0/snk/__init__.py
--rw-r--r--   0        0        0      401 2020-02-02 00:00:00.000000 snk-0.9.0/snk/errors.py
--rw-r--r--   0        0        0     5868 2020-02-02 00:00:00.000000 snk-0.9.0/snk/main.py
--rw-r--r--   0        0        0    16434 2020-02-02 00:00:00.000000 snk-0.9.0/snk/nest.py
--rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 snk-0.9.0/snk/pipeline.py
--rw-r--r--   0        0        0      279 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/__init__.py
--rw-r--r--   0        0        0    19432 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/cli.py
--rw-r--r--   0        0        0     6981 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/config.py
--rw-r--r--   0        0        0     1603 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/dynamic_typer.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/options.py
--rw-r--r--   0        0        0     9225 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/utils.py
--rw-r--r--   0        0        0     5082 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/workflow.py
--rw-r--r--   0        0        0       23 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/subcommands/__init__.py
--rw-r--r--   0        0        0     3383 2020-02-02 00:00:00.000000 snk-0.9.0/snk/cli/subcommands/env.py
--rw-r--r--   0        0        0     6148 2020-02-02 00:00:00.000000 snk-0.9.0/tests/.DS_Store
--rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 snk-0.9.0/tests/__init__.py
--rw-r--r--   0        0        0     1625 2020-02-02 00:00:00.000000 snk-0.9.0/tests/conftest.py
--rw-r--r--   0        0        0     1504 2020-02-02 00:00:00.000000 snk-0.9.0/tests/test_nest.py
--rw-r--r--   0        0        0     1671 2020-02-02 00:00:00.000000 snk-0.9.0/tests/test_pipline_cli.py
--rw-r--r--   0        0        0     1470 2020-02-02 00:00:00.000000 snk-0.9.0/tests/test_snk.py
--rw-r--r--   0        0        0     2389 2020-02-02 00:00:00.000000 snk-0.9.0/tests/test_snk_config.py
--rw-r--r--   0        0        0      581 2020-02-02 00:00:00.000000 snk-0.9.0/tests/utils.py
--rw-r--r--   0        0        0     9605 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/artic_v4.1.bed
--rw-r--r--   0        0        0      907 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/config.yaml
--rw-r--r--   0        0        0   242003 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/cov.fasta
--rwxr-xr-x   0        0        0      297 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/bin/snk-basic-pipeline
--rw-r--r--   0        0        0       74 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/pipeline/cli.py
--rw-r--r--   0        0        0       40 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/pipeline/config.yaml
--rw-r--r--   0        0        0      198 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/pipeline/snk.yaml
--rw-r--r--   0        0        0        4 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/pipeline/resources/data.txt
--rw-r--r--   0        0        0      156 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/pipeline/workflow/Snakefile
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/pipeline/workflow/envs/base.yml
--rw-r--r--   0        0        0        8 2020-02-02 00:00:00.000000 snk-0.9.0/tests/data/pipeline/workflow/profiles/base/config.yaml
--rw-r--r--   0        0        0      118 2020-02-02 00:00:00.000000 snk-0.9.0/.gitignore
--rw-r--r--   0        0        0     1101 2020-02-02 00:00:00.000000 snk-0.9.0/LICENSE.txt
--rw-r--r--   0        0        0     2848 2020-02-02 00:00:00.000000 snk-0.9.0/README.md
--rw-r--r--   0        0        0     1681 2020-02-02 00:00:00.000000 snk-0.9.0/pyproject.toml
--rw-r--r--   0        0        0     3834 2020-02-02 00:00:00.000000 snk-0.9.0/PKG-INFO
+-rw-r--r--   0        0        0       83 2020-02-02 00:00:00.000000 snk-0.9.1/Dockerfile
+-rw-r--r--   0        0        0      670 2020-02-02 00:00:00.000000 snk-0.9.1/mkdocs.yml
+-rw-r--r--   0        0        0      476 2020-02-02 00:00:00.000000 snk-0.9.1/.github/workflows/mkdocs.yml
+-rw-r--r--   0        0        0      613 2020-02-02 00:00:00.000000 snk-0.9.1/.github/workflows/publish.yml
+-rw-r--r--   0        0        0      564 2020-02-02 00:00:00.000000 snk-0.9.1/.github/workflows/tests.yml
+-rw-r--r--   0        0        0       15 2020-02-02 00:00:00.000000 snk-0.9.1/docs/CNAME
+-rw-r--r--   0        0        0     3073 2020-02-02 00:00:00.000000 snk-0.9.1/docs/index.md
+-rw-r--r--   0        0        0     3997 2020-02-02 00:00:00.000000 snk-0.9.1/docs/managing_pipelines.md
+-rw-r--r--   0        0        0     8994 2020-02-02 00:00:00.000000 snk-0.9.1/docs/pipeline_packages.md
+-rw-r--r--   0        0        0     4955 2020-02-02 00:00:00.000000 snk-0.9.1/docs/snk_config_file.md
+-rw-r--r--   0        0        0     2917 2020-02-02 00:00:00.000000 snk-0.9.1/docs/CLI/env.md
+-rw-r--r--   0        0        0      532 2020-02-02 00:00:00.000000 snk-0.9.1/docs/CLI/index.md
+-rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 snk-0.9.1/docs/reference/cli.md
+-rw-r--r--   0        0        0       16 2020-02-02 00:00:00.000000 snk-0.9.1/docs/reference/errors.md
+-rw-r--r--   0        0        0       14 2020-02-02 00:00:00.000000 snk-0.9.1/docs/reference/main.md
+-rw-r--r--   0        0        0       14 2020-02-02 00:00:00.000000 snk-0.9.1/docs/reference/nest.md
+-rw-r--r--   0        0        0       18 2020-02-02 00:00:00.000000 snk-0.9.1/docs/reference/pipeline.md
+-rw-r--r--   0        0        0      125 2020-02-02 00:00:00.000000 snk-0.9.1/snk/__about__.py
+-rw-r--r--   0        0        0      154 2020-02-02 00:00:00.000000 snk-0.9.1/snk/__init__.py
+-rw-r--r--   0        0        0      401 2020-02-02 00:00:00.000000 snk-0.9.1/snk/errors.py
+-rw-r--r--   0        0        0     5868 2020-02-02 00:00:00.000000 snk-0.9.1/snk/main.py
+-rw-r--r--   0        0        0    16434 2020-02-02 00:00:00.000000 snk-0.9.1/snk/nest.py
+-rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 snk-0.9.1/snk/pipeline.py
+-rw-r--r--   0        0        0      279 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/__init__.py
+-rw-r--r--   0        0        0    19560 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/cli.py
+-rw-r--r--   0        0        0     6981 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/config.py
+-rw-r--r--   0        0        0     1700 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/dynamic_typer.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/options.py
+-rw-r--r--   0        0        0     9225 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/utils.py
+-rw-r--r--   0        0        0     5265 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/workflow.py
+-rw-r--r--   0        0        0       23 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/subcommands/__init__.py
+-rw-r--r--   0        0        0     4894 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/subcommands/env.py
+-rw-r--r--   0        0        0     6148 2020-02-02 00:00:00.000000 snk-0.9.1/tests/.DS_Store
+-rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 snk-0.9.1/tests/__init__.py
+-rw-r--r--   0        0        0     1625 2020-02-02 00:00:00.000000 snk-0.9.1/tests/conftest.py
+-rw-r--r--   0        0        0     1504 2020-02-02 00:00:00.000000 snk-0.9.1/tests/test_nest.py
+-rw-r--r--   0        0        0     1671 2020-02-02 00:00:00.000000 snk-0.9.1/tests/test_pipline_cli.py
+-rw-r--r--   0        0        0     1470 2020-02-02 00:00:00.000000 snk-0.9.1/tests/test_snk.py
+-rw-r--r--   0        0        0     2389 2020-02-02 00:00:00.000000 snk-0.9.1/tests/test_snk_config.py
+-rw-r--r--   0        0        0      581 2020-02-02 00:00:00.000000 snk-0.9.1/tests/utils.py
+-rw-r--r--   0        0        0     9605 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/artic_v4.1.bed
+-rw-r--r--   0        0        0      907 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/config.yaml
+-rw-r--r--   0        0        0   242003 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/cov.fasta
+-rwxr-xr-x   0        0        0      297 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/bin/snk-basic-pipeline
+-rw-r--r--   0        0        0       74 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/cli.py
+-rw-r--r--   0        0        0       40 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/config.yaml
+-rw-r--r--   0        0        0      198 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/snk.yaml
+-rw-r--r--   0        0        0        4 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/resources/data.txt
+-rw-r--r--   0        0        0      156 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/workflow/Snakefile
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/workflow/envs/base.yml
+-rw-r--r--   0        0        0     1050 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/workflow/envs/pandas.yml
+-rw-r--r--   0        0        0        8 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/workflow/profiles/base/config.yaml
+-rw-r--r--   0        0        0      144 2020-02-02 00:00:00.000000 snk-0.9.1/.gitignore
+-rw-r--r--   0        0        0     1101 2020-02-02 00:00:00.000000 snk-0.9.1/LICENSE.txt
+-rw-r--r--   0        0        0     2848 2020-02-02 00:00:00.000000 snk-0.9.1/README.md
+-rw-r--r--   0        0        0     1681 2020-02-02 00:00:00.000000 snk-0.9.1/pyproject.toml
+-rw-r--r--   0        0        0     3834 2020-02-02 00:00:00.000000 snk-0.9.1/PKG-INFO
```

### Comparing `snk-0.9.0/mkdocs.yml` & `snk-0.9.1/mkdocs.yml`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/.github/workflows/publish.yml` & `snk-0.9.1/.github/workflows/publish.yml`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/.github/workflows/tests.yml` & `snk-0.9.1/.github/workflows/tests.yml`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/docs/index.md` & `snk-0.9.1/docs/index.md`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/docs/managing_pipelines.md` & `snk-0.9.1/docs/managing_pipelines.md`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/docs/pipeline_packages.md` & `snk-0.9.1/docs/pipeline_packages.md`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/docs/snk_config_file.md` & `snk-0.9.1/docs/snk_config_file.md`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/snk/main.py` & `snk-0.9.1/snk/main.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/snk/nest.py` & `snk-0.9.1/snk/nest.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/snk/pipeline.py` & `snk-0.9.1/snk/pipeline.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/snk/cli/cli.py` & `snk-0.9.1/snk/cli/cli.py`

 * *Files 0% similar despite different names*

```diff
@@ -104,15 +104,15 @@
         # registration
         self.register_callback(
             callback,
             invoke_without_command=True,
             context_settings={"help_option_names": ["-h", "--help"]},
         )
         self.register_command(
-            self.info, help="Display information about current pipeline install."
+            self.info, help="Display information about the pipeline."
         )
         self.register_command(self.config, help="Access the pipeline configuration.")
         if self.pipeline.environments:
             env_app = EnvApp(
                 pipeline=self.pipeline, 
                 conda_prefix_dir=self.conda_prefix_dir,
                 snakemake_config=self.snakemake_config,
@@ -454,31 +454,34 @@
 
         info_dict = {}
         info_dict["name"] = self.pipeline.path.name
         info_dict["version"] = self.pipeline.version
         info_dict["pipeline_dir_path"] = str(self.pipeline.path)
         typer.echo(json.dumps(info_dict, indent=2))
 
-    def config(self):
+    def config(self, pretty: bool = typer.Option(False, "--pretty", "-p")):
         """
         Access the pipeline configuration.
         Side Effects:
           Prints the pipeline configuration.
         Examples:
           >>> CLI.config()
         """
         config_path = get_config_from_pipeline_dir(self.pipeline.path)
         if not config_path:
             typer.secho("Could not find config...", fg="red")
             raise typer.Exit(1)
         with open(config_path) as f:
             code = f.read()
-            syntax = Syntax(code, "yaml")
-            console = Console()
-            console.print(syntax)
+            if pretty:
+                syntax = Syntax(code, "yaml")
+                console = Console()
+                console.print(syntax)
+            else:
+                typer.echo(code)
 
     def env(
         self,
         name: str = typer.Argument(None, help="The name of the environment."),
     ):
         """
         Access the pipeline conda environments.
```

### Comparing `snk-0.9.0/snk/cli/config.py` & `snk-0.9.1/snk/cli/config.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/snk/cli/dynamic_typer.py` & `snk-0.9.1/snk/cli/dynamic_typer.py`

 * *Files 10% similar despite different names*

```diff
@@ -46,10 +46,14 @@
         Side Effects:
           Registers the subcommand group to the CLI.
         Examples:
           >>> CLI.register_app(my_group)
         """
         self.app.add_typer(group.app, **command_kwargs)
     
-    def error(self, msg):
+    def error(self, msg, exit=True):
         typer.secho(msg, fg="red")
-        raise typer.Exit(1)
+        if exit:
+          raise typer.Exit(1)
+    
+    def log(self, msg):
+        typer.secho(msg, fg="yellow")
```

### Comparing `snk-0.9.0/snk/cli/utils.py` & `snk-0.9.1/snk/cli/utils.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/snk/cli/workflow.py` & `snk-0.9.1/snk/cli/workflow.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,8 +1,10 @@
+from pathlib import Path
 from snakemake import Workflow, update_config, load_configfile, dict_to_key_value_args, common
+from snakemake.persistence import Persistence
 import os
 
 def create_workflow( 
         snakefile,
         cache=None,
         lint=None,
         cores=1,
@@ -132,9 +134,10 @@
             conda_base_path=conda_base_path,
             check_envvars=not lint,  # for linting, we do not need to check whether requested envvars exist
             all_temp=all_temp,
             local_groupid=local_groupid,
             keep_metadata=keep_metadata,
             latency_wait=latency_wait,
         )
+        workflow.persistence = Persistence(conda_prefix=Path(conda_prefix).resolve() if conda_prefix else None)
         return workflow
```

### Comparing `snk-0.9.0/snk/cli/subcommands/env.py` & `snk-0.9.1/snk/cli/subcommands/env.py`

 * *Files 27% similar despite different names*

```diff
@@ -1,31 +1,43 @@
+import os
+import shutil
 import subprocess
 from pathlib import Path
+import sys
 from typing import List, Optional
 import typer
 
 from snk.cli.dynamic_typer import DynamicTyper
 from snk.cli.workflow import create_workflow
 from snk.pipeline import Pipeline
 from rich.console import Console
 from rich.syntax import Syntax
-from snakemake.deployment.conda import Conda, Env
+from snakemake.deployment.conda import Conda, Env, CreateCondaEnvironmentException
 from snk.cli.config import get_config_from_pipeline_dir
 
 class EnvApp(DynamicTyper):
     def __init__(self, pipeline: Pipeline, conda_prefix_dir: Path, snakemake_config, snakefile: Path):
         self.pipeline = pipeline
         self.conda_prefix_dir = conda_prefix_dir
         self.snakemake_config = snakemake_config
         self.snakefile = snakefile
         self.app = typer.Typer()
+        self.workflow = create_workflow(
+            self.snakefile,
+            config=self.snakemake_config,
+            configfiles=[get_config_from_pipeline_dir(self.pipeline.path)],
+            use_conda = True,
+            conda_prefix=self.conda_prefix_dir.resolve(),
+        )
         self.register_command(self.list, help="List the environments in the pipeline.")
         self.register_command(self.show, help="Show the environments config file contents.")
         self.register_command(self.run, help="Run a command in one of the pipeline environments.")
         self.register_command(self.activate, help="Activate a pipeline conda environment.")
+        self.register_command(self.prune, help="Delete all conda environments")
+        self.register_command(self.create, help="Create all conda environments")
 
     def list(self):
         environments_dir_yellow = typer.style(
             self.pipeline.path / "envs", fg=typer.colors.YELLOW
         )
         typer.echo(
             f"Found {len(self.pipeline.environments)} environments in {environments_dir_yellow}"
@@ -34,39 +46,37 @@
             typer.echo(f'- {env.stem}')
     
     def _get_conda_env_path(self, name: str) -> Path:
         env = [e for e in self.pipeline.environments if e.stem == name]
         if not env:
             self.error(f"Environment {name} not found!")
         return env[0]
+    
+    def _shellcmd(self, env_address: str, cmd: str) -> str:
+        if sys.platform.lower().startswith("win"):
+            return Conda().shellcmd_win(env_address, cmd)
+        return Conda().shellcmd(env_address, cmd)
 
     def show(self, name: str = typer.Argument(..., help="The name of the environment.")):
         env_path = self._get_conda_env_path(name)
-        # typer.echo(f"{env}", err=True)
         with open(env_path) as f:
             code = f.read()
             syntax = Syntax(code, "yaml")
             console = Console()
             console.print(syntax)
 
     def run(
             self, 
-            name: str = typer.Argument(..., help="The name of the environment."),
-            cmd: List[str] = typer.Argument(..., help="The command to run.")
+            env_name: str = typer.Option(..., "--env", "-e", help="The name of the environment."),
+            cmd: List[str] = typer.Argument(..., help="The command to run in environment.")
         ):
-        env_path = self._get_conda_env_path(name)
-        workflow = create_workflow(
-            self.snakefile,
-            config=self.snakemake_config,
-            configfiles=[get_config_from_pipeline_dir(self.pipeline.path)],
-            use_conda = True,
-        )
-        env = Env(workflow, env_file=env_path, env_dir=self.conda_prefix_dir)
-        cmd = Conda().shellcmd(env.address, " ".join(cmd))
-        
+        env_path = self._get_conda_env_path(env_name)
+        env = Env(self.workflow, env_file=env_path.resolve())
+        env.create()
+        cmd = self._shellcmd(env.address, " ".join(cmd))
         proc = subprocess.Popen(
             cmd,
             bufsize=-1,
             shell=True,
             stdout=subprocess.PIPE,
             stderr=subprocess.PIPE,
         )
@@ -74,13 +84,33 @@
         if proc.returncode:
             if stderr:
                 self.error(stderr)
             raise subprocess.CalledProcessError(proc.returncode, cmd, output=stdout, stderr=stderr)
         if stdout:
             typer.echo(stdout)
 
-    def create(self, name: Optional[str] = typer.Argument(..., help="The name of the environment.")):
-        raise NotImplementedError
+    def prune(self, force: bool = typer.Option(False, "--force", "-f", help="Force deletion of the environments.")):
+        if force or input(f"Delete {self.conda_prefix_dir}? [y/N] ").lower() == "y":
+            # delete self.conda_prefix_dir directory
+            shutil.rmtree(self.conda_prefix_dir)
+            self.log(f"Deleted {self.conda_prefix_dir}")
     
-    def activate(self, name: str = typer.Argument(..., help="The name of the environment.")):
-        raise NotImplementedError
+    def create(self):
+        for env_path in self.pipeline.environments:
+            env = Env(self.workflow, env_file=env_path.resolve())
+            try:
+                env.create()
+            except CreateCondaEnvironmentException:
+                self.error(f"Environment {env_path.name} could not be created!", exit=False)
+
+
+    def activate(self, env_name: str = typer.Argument(..., help="The name of the environment.")):
+        env_path = self._get_conda_env_path(env_name)
+        env = Env(self.workflow, env_file=env_path.resolve())
+        env.create()
+        user_shell = os.environ.get('SHELL', '/bin/sh')
+        activate_cmd = self._shellcmd(env.address, user_shell)
+        self.log(f"Activating {env_name} environment... (type 'exit' to deactivate)")
+        subprocess.run(activate_cmd, shell=True, env=os.environ.copy())
+        self.log(f"Exiting {env_name} environment...")
+
```

### Comparing `snk-0.9.0/tests/.DS_Store` & `snk-0.9.1/tests/.DS_Store`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/tests/conftest.py` & `snk-0.9.1/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/tests/test_nest.py` & `snk-0.9.1/tests/test_nest.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/tests/test_pipline_cli.py` & `snk-0.9.1/tests/test_pipline_cli.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/tests/test_snk.py` & `snk-0.9.1/tests/test_snk.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/tests/test_snk_config.py` & `snk-0.9.1/tests/test_snk_config.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/tests/utils.py` & `snk-0.9.1/tests/utils.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/tests/data/artic_v4.1.bed` & `snk-0.9.1/tests/data/artic_v4.1.bed`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/tests/data/config.yaml` & `snk-0.9.1/tests/data/config.yaml`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/tests/data/cov.fasta` & `snk-0.9.1/tests/data/cov.fasta`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/LICENSE.txt` & `snk-0.9.1/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/README.md` & `snk-0.9.1/README.md`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/pyproject.toml` & `snk-0.9.1/pyproject.toml`

 * *Files identical despite different names*

### Comparing `snk-0.9.0/PKG-INFO` & `snk-0.9.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: snk
-Version: 0.9.0
+Version: 0.9.1
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
-Metadata-Version: 2.1 Name: snk Version: 0.9.0 Project-URL: Documentation,
+Metadata-Version: 2.1 Name: snk Version: 0.9.1 Project-URL: Documentation,
 https://github.com/wytamma/snk#readme Project-URL: Issues, https://github.com/
 wytamma/snk/issues Project-URL: Source, https://github.com/wytamma/snk Author-
 email: Wytamma Wirth
 wirth@me.com> License-Expression: MIT License-File: LICENSE.txt Classifier:
 Development Status :: 4 - Beta Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3.7 Classifier: Programming
 Language :: Python :: 3.8 Classifier: Programming Language :: Python :: 3.9
```


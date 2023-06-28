# Comparing `tmp/snk-0.9.1.tar.gz` & `tmp/snk-0.9.2.tar.gz`

## Comparing `snk-0.9.1.tar` & `snk-0.9.2.tar`

### file list

```diff
@@ -1,57 +1,57 @@
--rw-r--r--   0        0        0       83 2020-02-02 00:00:00.000000 snk-0.9.1/Dockerfile
--rw-r--r--   0        0        0      670 2020-02-02 00:00:00.000000 snk-0.9.1/mkdocs.yml
--rw-r--r--   0        0        0      476 2020-02-02 00:00:00.000000 snk-0.9.1/.github/workflows/mkdocs.yml
--rw-r--r--   0        0        0      613 2020-02-02 00:00:00.000000 snk-0.9.1/.github/workflows/publish.yml
--rw-r--r--   0        0        0      564 2020-02-02 00:00:00.000000 snk-0.9.1/.github/workflows/tests.yml
--rw-r--r--   0        0        0       15 2020-02-02 00:00:00.000000 snk-0.9.1/docs/CNAME
--rw-r--r--   0        0        0     3073 2020-02-02 00:00:00.000000 snk-0.9.1/docs/index.md
--rw-r--r--   0        0        0     3997 2020-02-02 00:00:00.000000 snk-0.9.1/docs/managing_pipelines.md
--rw-r--r--   0        0        0     8994 2020-02-02 00:00:00.000000 snk-0.9.1/docs/pipeline_packages.md
--rw-r--r--   0        0        0     4955 2020-02-02 00:00:00.000000 snk-0.9.1/docs/snk_config_file.md
--rw-r--r--   0        0        0     2917 2020-02-02 00:00:00.000000 snk-0.9.1/docs/CLI/env.md
--rw-r--r--   0        0        0      532 2020-02-02 00:00:00.000000 snk-0.9.1/docs/CLI/index.md
--rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 snk-0.9.1/docs/reference/cli.md
--rw-r--r--   0        0        0       16 2020-02-02 00:00:00.000000 snk-0.9.1/docs/reference/errors.md
--rw-r--r--   0        0        0       14 2020-02-02 00:00:00.000000 snk-0.9.1/docs/reference/main.md
--rw-r--r--   0        0        0       14 2020-02-02 00:00:00.000000 snk-0.9.1/docs/reference/nest.md
--rw-r--r--   0        0        0       18 2020-02-02 00:00:00.000000 snk-0.9.1/docs/reference/pipeline.md
--rw-r--r--   0        0        0      125 2020-02-02 00:00:00.000000 snk-0.9.1/snk/__about__.py
--rw-r--r--   0        0        0      154 2020-02-02 00:00:00.000000 snk-0.9.1/snk/__init__.py
--rw-r--r--   0        0        0      401 2020-02-02 00:00:00.000000 snk-0.9.1/snk/errors.py
--rw-r--r--   0        0        0     5868 2020-02-02 00:00:00.000000 snk-0.9.1/snk/main.py
--rw-r--r--   0        0        0    16434 2020-02-02 00:00:00.000000 snk-0.9.1/snk/nest.py
--rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 snk-0.9.1/snk/pipeline.py
--rw-r--r--   0        0        0      279 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/__init__.py
--rw-r--r--   0        0        0    19560 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/cli.py
--rw-r--r--   0        0        0     6981 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/config.py
--rw-r--r--   0        0        0     1700 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/dynamic_typer.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/options.py
--rw-r--r--   0        0        0     9225 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/utils.py
--rw-r--r--   0        0        0     5265 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/workflow.py
--rw-r--r--   0        0        0       23 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/subcommands/__init__.py
--rw-r--r--   0        0        0     4894 2020-02-02 00:00:00.000000 snk-0.9.1/snk/cli/subcommands/env.py
--rw-r--r--   0        0        0     6148 2020-02-02 00:00:00.000000 snk-0.9.1/tests/.DS_Store
--rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 snk-0.9.1/tests/__init__.py
--rw-r--r--   0        0        0     1625 2020-02-02 00:00:00.000000 snk-0.9.1/tests/conftest.py
--rw-r--r--   0        0        0     1504 2020-02-02 00:00:00.000000 snk-0.9.1/tests/test_nest.py
--rw-r--r--   0        0        0     1671 2020-02-02 00:00:00.000000 snk-0.9.1/tests/test_pipline_cli.py
--rw-r--r--   0        0        0     1470 2020-02-02 00:00:00.000000 snk-0.9.1/tests/test_snk.py
--rw-r--r--   0        0        0     2389 2020-02-02 00:00:00.000000 snk-0.9.1/tests/test_snk_config.py
--rw-r--r--   0        0        0      581 2020-02-02 00:00:00.000000 snk-0.9.1/tests/utils.py
--rw-r--r--   0        0        0     9605 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/artic_v4.1.bed
--rw-r--r--   0        0        0      907 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/config.yaml
--rw-r--r--   0        0        0   242003 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/cov.fasta
--rwxr-xr-x   0        0        0      297 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/bin/snk-basic-pipeline
--rw-r--r--   0        0        0       74 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/cli.py
--rw-r--r--   0        0        0       40 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/config.yaml
--rw-r--r--   0        0        0      198 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/snk.yaml
--rw-r--r--   0        0        0        4 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/resources/data.txt
--rw-r--r--   0        0        0      156 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/workflow/Snakefile
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/workflow/envs/base.yml
--rw-r--r--   0        0        0     1050 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/workflow/envs/pandas.yml
--rw-r--r--   0        0        0        8 2020-02-02 00:00:00.000000 snk-0.9.1/tests/data/pipeline/workflow/profiles/base/config.yaml
--rw-r--r--   0        0        0      144 2020-02-02 00:00:00.000000 snk-0.9.1/.gitignore
--rw-r--r--   0        0        0     1101 2020-02-02 00:00:00.000000 snk-0.9.1/LICENSE.txt
--rw-r--r--   0        0        0     2848 2020-02-02 00:00:00.000000 snk-0.9.1/README.md
--rw-r--r--   0        0        0     1681 2020-02-02 00:00:00.000000 snk-0.9.1/pyproject.toml
--rw-r--r--   0        0        0     3834 2020-02-02 00:00:00.000000 snk-0.9.1/PKG-INFO
+-rw-r--r--   0        0        0       83 2020-02-02 00:00:00.000000 snk-0.9.2/Dockerfile
+-rw-r--r--   0        0        0      670 2020-02-02 00:00:00.000000 snk-0.9.2/mkdocs.yml
+-rw-r--r--   0        0        0      476 2020-02-02 00:00:00.000000 snk-0.9.2/.github/workflows/mkdocs.yml
+-rw-r--r--   0        0        0      613 2020-02-02 00:00:00.000000 snk-0.9.2/.github/workflows/publish.yml
+-rw-r--r--   0        0        0      564 2020-02-02 00:00:00.000000 snk-0.9.2/.github/workflows/tests.yml
+-rw-r--r--   0        0        0       15 2020-02-02 00:00:00.000000 snk-0.9.2/docs/CNAME
+-rw-r--r--   0        0        0     3073 2020-02-02 00:00:00.000000 snk-0.9.2/docs/index.md
+-rw-r--r--   0        0        0     3997 2020-02-02 00:00:00.000000 snk-0.9.2/docs/managing_pipelines.md
+-rw-r--r--   0        0        0     8994 2020-02-02 00:00:00.000000 snk-0.9.2/docs/pipeline_packages.md
+-rw-r--r--   0        0        0     4955 2020-02-02 00:00:00.000000 snk-0.9.2/docs/snk_config_file.md
+-rw-r--r--   0        0        0     2917 2020-02-02 00:00:00.000000 snk-0.9.2/docs/CLI/env.md
+-rw-r--r--   0        0        0      532 2020-02-02 00:00:00.000000 snk-0.9.2/docs/CLI/index.md
+-rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 snk-0.9.2/docs/reference/cli.md
+-rw-r--r--   0        0        0       16 2020-02-02 00:00:00.000000 snk-0.9.2/docs/reference/errors.md
+-rw-r--r--   0        0        0       14 2020-02-02 00:00:00.000000 snk-0.9.2/docs/reference/main.md
+-rw-r--r--   0        0        0       14 2020-02-02 00:00:00.000000 snk-0.9.2/docs/reference/nest.md
+-rw-r--r--   0        0        0       18 2020-02-02 00:00:00.000000 snk-0.9.2/docs/reference/pipeline.md
+-rw-r--r--   0        0        0      125 2020-02-02 00:00:00.000000 snk-0.9.2/snk/__about__.py
+-rw-r--r--   0        0        0      154 2020-02-02 00:00:00.000000 snk-0.9.2/snk/__init__.py
+-rw-r--r--   0        0        0      401 2020-02-02 00:00:00.000000 snk-0.9.2/snk/errors.py
+-rw-r--r--   0        0        0     5868 2020-02-02 00:00:00.000000 snk-0.9.2/snk/main.py
+-rw-r--r--   0        0        0    16434 2020-02-02 00:00:00.000000 snk-0.9.2/snk/nest.py
+-rw-r--r--   0        0        0     2606 2020-02-02 00:00:00.000000 snk-0.9.2/snk/pipeline.py
+-rw-r--r--   0        0        0      279 2020-02-02 00:00:00.000000 snk-0.9.2/snk/cli/__init__.py
+-rw-r--r--   0        0        0    19528 2020-02-02 00:00:00.000000 snk-0.9.2/snk/cli/cli.py
+-rw-r--r--   0        0        0     6981 2020-02-02 00:00:00.000000 snk-0.9.2/snk/cli/config.py
+-rw-r--r--   0        0        0     1700 2020-02-02 00:00:00.000000 snk-0.9.2/snk/cli/dynamic_typer.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 snk-0.9.2/snk/cli/options.py
+-rw-r--r--   0        0        0     9225 2020-02-02 00:00:00.000000 snk-0.9.2/snk/cli/utils.py
+-rw-r--r--   0        0        0     5265 2020-02-02 00:00:00.000000 snk-0.9.2/snk/cli/workflow.py
+-rw-r--r--   0        0        0       23 2020-02-02 00:00:00.000000 snk-0.9.2/snk/cli/subcommands/__init__.py
+-rw-r--r--   0        0        0     4497 2020-02-02 00:00:00.000000 snk-0.9.2/snk/cli/subcommands/env.py
+-rw-r--r--   0        0        0     6148 2020-02-02 00:00:00.000000 snk-0.9.2/tests/.DS_Store
+-rw-r--r--   0        0        0      103 2020-02-02 00:00:00.000000 snk-0.9.2/tests/__init__.py
+-rw-r--r--   0        0        0     1625 2020-02-02 00:00:00.000000 snk-0.9.2/tests/conftest.py
+-rw-r--r--   0        0        0     1504 2020-02-02 00:00:00.000000 snk-0.9.2/tests/test_nest.py
+-rw-r--r--   0        0        0     1671 2020-02-02 00:00:00.000000 snk-0.9.2/tests/test_pipline_cli.py
+-rw-r--r--   0        0        0     1470 2020-02-02 00:00:00.000000 snk-0.9.2/tests/test_snk.py
+-rw-r--r--   0        0        0     2389 2020-02-02 00:00:00.000000 snk-0.9.2/tests/test_snk_config.py
+-rw-r--r--   0        0        0      581 2020-02-02 00:00:00.000000 snk-0.9.2/tests/utils.py
+-rw-r--r--   0        0        0     9605 2020-02-02 00:00:00.000000 snk-0.9.2/tests/data/artic_v4.1.bed
+-rw-r--r--   0        0        0      907 2020-02-02 00:00:00.000000 snk-0.9.2/tests/data/config.yaml
+-rw-r--r--   0        0        0   242003 2020-02-02 00:00:00.000000 snk-0.9.2/tests/data/cov.fasta
+-rwxr-xr-x   0        0        0      297 2020-02-02 00:00:00.000000 snk-0.9.2/tests/data/bin/snk-basic-pipeline
+-rw-r--r--   0        0        0       74 2020-02-02 00:00:00.000000 snk-0.9.2/tests/data/pipeline/cli.py
+-rw-r--r--   0        0        0       40 2020-02-02 00:00:00.000000 snk-0.9.2/tests/data/pipeline/config.yaml
+-rw-r--r--   0        0        0      198 2020-02-02 00:00:00.000000 snk-0.9.2/tests/data/pipeline/snk.yaml
+-rw-r--r--   0        0        0        4 2020-02-02 00:00:00.000000 snk-0.9.2/tests/data/pipeline/resources/data.txt
+-rw-r--r--   0        0        0      156 2020-02-02 00:00:00.000000 snk-0.9.2/tests/data/pipeline/workflow/Snakefile
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 snk-0.9.2/tests/data/pipeline/workflow/envs/base.yml
+-rw-r--r--   0        0        0     1050 2020-02-02 00:00:00.000000 snk-0.9.2/tests/data/pipeline/workflow/envs/pandas.yml
+-rw-r--r--   0        0        0        8 2020-02-02 00:00:00.000000 snk-0.9.2/tests/data/pipeline/workflow/profiles/base/config.yaml
+-rw-r--r--   0        0        0      144 2020-02-02 00:00:00.000000 snk-0.9.2/.gitignore
+-rw-r--r--   0        0        0     1101 2020-02-02 00:00:00.000000 snk-0.9.2/LICENSE.txt
+-rw-r--r--   0        0        0     2848 2020-02-02 00:00:00.000000 snk-0.9.2/README.md
+-rw-r--r--   0        0        0     1681 2020-02-02 00:00:00.000000 snk-0.9.2/pyproject.toml
+-rw-r--r--   0        0        0     3834 2020-02-02 00:00:00.000000 snk-0.9.2/PKG-INFO
```

### Comparing `snk-0.9.1/mkdocs.yml` & `snk-0.9.2/mkdocs.yml`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/.github/workflows/publish.yml` & `snk-0.9.2/.github/workflows/publish.yml`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/.github/workflows/tests.yml` & `snk-0.9.2/.github/workflows/tests.yml`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/docs/index.md` & `snk-0.9.2/docs/index.md`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/docs/managing_pipelines.md` & `snk-0.9.2/docs/managing_pipelines.md`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/docs/pipeline_packages.md` & `snk-0.9.2/docs/pipeline_packages.md`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/docs/snk_config_file.md` & `snk-0.9.2/docs/snk_config_file.md`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/docs/CLI/env.md` & `snk-0.9.2/docs/CLI/env.md`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/docs/CLI/index.md` & `snk-0.9.2/docs/CLI/index.md`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/snk/main.py` & `snk-0.9.2/snk/main.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/snk/nest.py` & `snk-0.9.2/snk/nest.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/snk/pipeline.py` & `snk-0.9.2/snk/pipeline.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/snk/cli/cli.py` & `snk-0.9.2/snk/cli/cli.py`

 * *Files 2% similar despite different names*

```diff
@@ -19,15 +19,20 @@
 from snk.cli.subcommands import EnvApp
 
 from .config import (
     SnkConfig,
     get_config_from_pipeline_dir,
     load_pipeline_snakemake_config,
 )
-from .utils import add_dynamic_options, build_dynamic_cli_options, parse_config_args, dag_filetype_callback
+from .utils import (
+    add_dynamic_options,
+    build_dynamic_cli_options,
+    parse_config_args,
+    dag_filetype_callback,
+)
 from snk.pipeline import Pipeline
 
 
 class CLI(DynamicTyper):
     """
     Constructor for the dynamic Snk CLI class.
     Args:
@@ -39,35 +44,38 @@
     """
 
     def __init__(self, pipeline_dir_path: Path = None) -> None:
         if not pipeline_dir_path:
             # get the calling frame (the frame of the function that called this function)
             calling_frame = inspect.currentframe().f_back
             # get the file path from the calling frame
-            pipeline_dir_path = Path(calling_frame.f_globals['__file__'])
+            pipeline_dir_path = Path(calling_frame.f_globals["__file__"])
         if pipeline_dir_path.is_file():
             pipeline_dir_path = pipeline_dir_path.parent
         self.pipeline = Pipeline(path=pipeline_dir_path)
+        self.version = self.pipeline.version
         self.app = typer.Typer()
         self.snakemake_config = load_pipeline_snakemake_config(pipeline_dir_path)
-        self.snk_config = SnkConfig.from_pipeline_dir(pipeline_dir_path, create_if_not_exists=True)
+        self.snk_config = SnkConfig.from_pipeline_dir(
+            pipeline_dir_path, create_if_not_exists=True
+        )
         self.options = build_dynamic_cli_options(self.snakemake_config, self.snk_config)
         self.snakefile = self._find_snakefile()
         self.conda_prefix_dir = pipeline_dir_path / ".conda"
         if " " in str(pipeline_dir_path):
             # cannot have spaces!
             self.singularity_prefix_dir = None
         else:
             self.singularity_prefix_dir = pipeline_dir_path / ".singularity"
         self.name = self.pipeline.name
         self.verbose = False
 
         def _print_pipline_version(ctx: typer.Context, value: bool):
             if value:
-                typer.echo(self.pipeline.version)
+                typer.echo(self.version)
                 raise typer.Exit()
 
         def _print_pipline_path(ctx: typer.Context, value: bool):
             if value:
                 typer.echo(self.pipeline.path)
                 raise typer.Exit()
 
@@ -90,56 +98,54 @@
                 is_eager=True,
                 callback=_print_pipline_path,
                 show_default=False,
             ),
         ):
             if ctx.invoked_subcommand is None:
                 typer.echo(f"{ctx.get_help()}")
-        
+
         # dynamically create the logo
         tagline: str = self.snk_config.tagline
         font: str = self.snk_config.font
         self.logo = self.create_logo(tagline=tagline, font=font)
         callback.__doc__ = self.logo
 
         # registration
         self.register_callback(
             callback,
             invoke_without_command=True,
             context_settings={"help_option_names": ["-h", "--help"]},
         )
-        self.register_command(
-            self.info, help="Display information about the pipeline."
-        )
+        self.register_command(self.info, help="Display information about the pipeline.")
         self.register_command(self.config, help="Access the pipeline configuration.")
         if self.pipeline.environments:
             env_app = EnvApp(
-                pipeline=self.pipeline, 
+                pipeline=self.pipeline,
                 conda_prefix_dir=self.conda_prefix_dir,
                 snakemake_config=self.snakemake_config,
                 snakefile=self.snakefile,
             )
             self.register_group(
-                env_app,
-                name="env",
-                help="Access the pipeline conda environments."
+                env_app, name="env", help="Access the pipeline conda environments."
             )
         if self.pipeline.profiles:
             self.register_command(self.profile, help="Access the pipeline profiles.")
         self.register_command(
             add_dynamic_options(self.options)(self.run),
             help="Run the Snakemake pipeline.\n\nAll unrecognized arguments are passed onto Snakemake.",
             context_settings={
                 "allow_extra_args": True,
                 "ignore_unknown_options": True,
                 "help_option_names": ["-h", "--help"],
             },
         )
 
-    def create_logo(self, tagline="A Snakemake pipeline CLI generated with snk", font="small"):
+    def create_logo(
+        self, tagline="A Snakemake pipeline CLI generated with snk", font="small"
+    ):
         """
         Create a logo for the CLI.
         Args:
           font (str): The font to use for the logo.
         Returns:
           str: The logo.
         Examples:
@@ -177,19 +183,16 @@
         for path in snakemake.SNAKEFILE_CHOICES:
             if (self.pipeline.path / path).exists():
                 return self.pipeline.path / path
         raise FileNotFoundError("Snakefile not found!")
 
     @contextmanager
     def copy_resources(
-            self, 
-            resources: List[Path], 
-            cleanup: bool, 
-            symlink_resources: bool = False
-        ):
+        self, resources: List[Path], cleanup: bool, symlink_resources: bool = False
+    ):
         """
         Copy resources to the current working directory.
         Args:
           resources (List[Path]): A list of paths to the resources to copy.
           cleanup (bool): If True, the resources will be removed after the function exits.
         Side Effects:
           Copies the resources to the current working directory.
@@ -219,18 +222,17 @@
             if resource.is_symlink():
                 resource.unlink()
             elif resource.is_dir():
                 shutil.rmtree(resource)
             else:
                 os.remove(resource)
 
-
-        resources_folder = self.pipeline.path / 'resources'
+        resources_folder = self.pipeline.path / "resources"
         if resources_folder.exists():
-            resources.insert(0, Path('resources'))
+            resources.insert(0, Path("resources"))
         if self.verbose:
             typer.secho(
                 f"Copying {len(resources)} resources to working directory...",
                 fg=typer.colors.YELLOW,
             )
         try:
             for resource in resources:
@@ -253,15 +255,15 @@
                 if copied_resource.exists():
                     if self.verbose:
                         typer.secho(
                             f"Deleting '{copied_resource.name}' resource...",
                             fg=typer.colors.YELLOW,
                         )
                     remove_resource(copied_resource)
-    
+
     def run(
         self,
         ctx: typer.Context,
         target: str = typer.Argument(
             None, help="File to generate. If None will run the pipeline 'all' rule."
         ),
         configfile: Path = typer.Option(
@@ -301,18 +303,18 @@
         keep_snakemake: bool = typer.Option(
             False,
             "--keep-snakemake",
             "-S",
             help="Keep .snakemake folder after pipeline completes.",
         ),
         dag: Optional[Path] = typer.Option(
-            None, 
+            None,
             "--dag",
             "-d",
-            help="Save directed acyclic graph to file. Must end in .pdf, .png or .svg", 
+            help="Save directed acyclic graph to file. Must end in .pdf, .png or .svg",
             callback=dag_filetype_callback,
         ),
         cores: int = typer.Option(
             None,
             "--cores",
             "-c",
             help="Set the number of cores to use. If None will use all cores.",
@@ -345,15 +347,19 @@
           verbose (bool): Run pipeline in verbose mode.
           help_snakemake (bool): Print the snakemake help and exit.
         Side Effects:
           Runs the pipeline.
         Examples:
           >>> CLI.run(target='my_target', configfile=Path('/path/to/config.yaml'), resource=[Path('/path/to/resource')], verbose=True)
         """
-        if platform.system() == "Darwin" and platform.processor() == "arm" and not os.environ.get("CONDA_SUBDIR"):
+        if (
+            platform.system() == "Darwin"
+            and platform.processor() == "arm"
+            and not os.environ.get("CONDA_SUBDIR")
+        ):
             os.environ["CONDA_SUBDIR"] = "osx-64"
         self.verbose = verbose
         args = []
         if not cores:
             cores = "all"
         args.extend(
             [
@@ -421,17 +427,17 @@
             typer.secho(f"snakemake {' '.join(args)}\n", fg=typer.colors.MAGENTA)
 
         try:
             self.snk_config.add_resources(resource, self.pipeline.path)
         except FileNotFoundError as e:
             self.error(str(e))
         with self.copy_resources(
-            self.snk_config.resources, 
-            cleanup=not keep_resources, 
-            symlink_resources=self.snk_config.symlink_resources
+            self.snk_config.resources,
+            cleanup=not keep_resources,
+            symlink_resources=self.snk_config.symlink_resources,
         ):
             if dag:
                 return self.save_dag(snakemake_args=args, filename=dag)
             try:
                 snakemake.main(args)
             except SystemExit as e:
                 status = int(str(e))
@@ -450,15 +456,15 @@
         Examples:
           >>> CLI.info()
         """
         import json
 
         info_dict = {}
         info_dict["name"] = self.pipeline.path.name
-        info_dict["version"] = self.pipeline.version
+        info_dict["version"] = self.version
         info_dict["pipeline_dir_path"] = str(self.pipeline.path)
         typer.echo(json.dumps(info_dict, indent=2))
 
     def config(self, pretty: bool = typer.Option(False, "--pretty", "-p")):
         """
         Access the pipeline configuration.
         Side Effects:
@@ -508,44 +514,40 @@
         )
         typer.echo(
             f"Found {len(self.pipeline.profiles)} profiles in {profiles_dir_yellow}"
         )
         for profile in self.pipeline.profiles:
             typer.echo(f"- {profile.name}")
 
-    
-    def save_dag(
-        self,
-        snakemake_args: List[str],
-        filename: Path
-    ):
+    def save_dag(self, snakemake_args: List[str], filename: Path):
         from contextlib import redirect_stdout
         import io
 
         snakemake_args.append("--dag")
-        
-        fileType = filename.suffix.lstrip('.')
-        
+
+        fileType = filename.suffix.lstrip(".")
+
         # Create a file-like object to redirect the stdout
         snakemake_output = io.StringIO()
         # Use redirect_stdout to redirect stdout to the file-like object
         with redirect_stdout(snakemake_output):
             # Capture the output of snakemake.main(args) using a try-except block
             try:
                 snakemake.main(snakemake_args)
             except SystemExit:  # Catch SystemExit exception to prevent termination
                 pass
         try:
-            echo_process = subprocess.Popen(['echo', snakemake_output.getvalue()], stdout=subprocess.PIPE)
-            dot_process = subprocess.Popen(['dot', f'-T{fileType}'], stdin=echo_process.stdout, stdout=subprocess.PIPE)
-            with open(filename, 'w') as output_file:
+            echo_process = subprocess.Popen(
+                ["echo", snakemake_output.getvalue()], stdout=subprocess.PIPE
+            )
+            dot_process = subprocess.Popen(
+                ["dot", f"-T{fileType}"],
+                stdin=echo_process.stdout,
+                stdout=subprocess.PIPE,
+            )
+            with open(filename, "w") as output_file:
                 if self.verbose:
-                    typer.secho(
-                        f"Saving dag to {filename}", fg=typer.colors.YELLOW
-                    )
-                subprocess.run(['cat'], stdin=dot_process.stdout, stdout=output_file)
+                    typer.secho(f"Saving dag to {filename}", fg=typer.colors.YELLOW)
+                subprocess.run(["cat"], stdin=dot_process.stdout, stdout=output_file)
         except (subprocess.CalledProcessError, FileNotFoundError):
-            typer.echo(
-                "dot command not found!", fg=typer.colors.RED, err=True
-            )
+            typer.echo("dot command not found!", fg=typer.colors.RED, err=True)
             raise typer.Exit(1)
-
```

### Comparing `snk-0.9.1/snk/cli/config.py` & `snk-0.9.2/snk/cli/config.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/snk/cli/dynamic_typer.py` & `snk-0.9.2/snk/cli/dynamic_typer.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/snk/cli/utils.py` & `snk-0.9.2/snk/cli/utils.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/snk/cli/workflow.py` & `snk-0.9.2/snk/cli/workflow.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/snk/cli/subcommands/env.py` & `snk-0.9.2/snk/cli/subcommands/env.py`

 * *Files 7% similar despite different names*

```diff
@@ -69,28 +69,15 @@
             env_name: str = typer.Option(..., "--env", "-e", help="The name of the environment."),
             cmd: List[str] = typer.Argument(..., help="The command to run in environment.")
         ):
         env_path = self._get_conda_env_path(env_name)
         env = Env(self.workflow, env_file=env_path.resolve())
         env.create()
         cmd = self._shellcmd(env.address, " ".join(cmd))
-        proc = subprocess.Popen(
-            cmd,
-            bufsize=-1,
-            shell=True,
-            stdout=subprocess.PIPE,
-            stderr=subprocess.PIPE,
-        )
-        stdout, stderr = proc.communicate()
-        if proc.returncode:
-            if stderr:
-                self.error(stderr)
-            raise subprocess.CalledProcessError(proc.returncode, cmd, output=stdout, stderr=stderr)
-        if stdout:
-            typer.echo(stdout)
+        subprocess.run(cmd, shell=True, env=os.environ.copy())
 
     def prune(self, force: bool = typer.Option(False, "--force", "-f", help="Force deletion of the environments.")):
         if force or input(f"Delete {self.conda_prefix_dir}? [y/N] ").lower() == "y":
             # delete self.conda_prefix_dir directory
             shutil.rmtree(self.conda_prefix_dir)
             self.log(f"Deleted {self.conda_prefix_dir}")
     
@@ -101,16 +88,16 @@
                 env.create()
             except CreateCondaEnvironmentException:
                 self.error(f"Environment {env_path.name} could not be created!", exit=False)
 
 
     def activate(self, env_name: str = typer.Argument(..., help="The name of the environment.")):
         env_path = self._get_conda_env_path(env_name)
+        self.log(f"Activating {env_name} environment... (type 'exit' to deactivate)")
         env = Env(self.workflow, env_file=env_path.resolve())
         env.create()
         user_shell = os.environ.get('SHELL', '/bin/sh')
         activate_cmd = self._shellcmd(env.address, user_shell)
-        self.log(f"Activating {env_name} environment... (type 'exit' to deactivate)")
         subprocess.run(activate_cmd, shell=True, env=os.environ.copy())
         self.log(f"Exiting {env_name} environment...")
```

### Comparing `snk-0.9.1/tests/.DS_Store` & `snk-0.9.2/tests/.DS_Store`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/tests/conftest.py` & `snk-0.9.2/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/tests/test_nest.py` & `snk-0.9.2/tests/test_nest.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/tests/test_pipline_cli.py` & `snk-0.9.2/tests/test_pipline_cli.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/tests/test_snk.py` & `snk-0.9.2/tests/test_snk.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/tests/test_snk_config.py` & `snk-0.9.2/tests/test_snk_config.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/tests/utils.py` & `snk-0.9.2/tests/utils.py`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/tests/data/artic_v4.1.bed` & `snk-0.9.2/tests/data/artic_v4.1.bed`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/tests/data/config.yaml` & `snk-0.9.2/tests/data/config.yaml`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/tests/data/cov.fasta` & `snk-0.9.2/tests/data/cov.fasta`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/tests/data/pipeline/workflow/envs/pandas.yml` & `snk-0.9.2/tests/data/pipeline/workflow/envs/pandas.yml`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/LICENSE.txt` & `snk-0.9.2/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/README.md` & `snk-0.9.2/README.md`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/pyproject.toml` & `snk-0.9.2/pyproject.toml`

 * *Files identical despite different names*

### Comparing `snk-0.9.1/PKG-INFO` & `snk-0.9.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: snk
-Version: 0.9.1
+Version: 0.9.2
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
-Metadata-Version: 2.1 Name: snk Version: 0.9.1 Project-URL: Documentation,
+Metadata-Version: 2.1 Name: snk Version: 0.9.2 Project-URL: Documentation,
 https://github.com/wytamma/snk#readme Project-URL: Issues, https://github.com/
 wytamma/snk/issues Project-URL: Source, https://github.com/wytamma/snk Author-
 email: Wytamma Wirth
 wirth@me.com> License-Expression: MIT License-File: LICENSE.txt Classifier:
 Development Status :: 4 - Beta Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3.7 Classifier: Programming
 Language :: Python :: 3.8 Classifier: Programming Language :: Python :: 3.9
```


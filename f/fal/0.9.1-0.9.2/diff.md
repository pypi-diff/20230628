# Comparing `tmp/fal-0.9.1.tar.gz` & `tmp/fal-0.9.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "fal-0.9.1.tar", max compression
+gzip compressed data, was "fal-0.9.2.tar", max compression
```

## Comparing `fal-0.9.1.tar` & `fal-0.9.2.tar`

### file list

```diff
@@ -1,46 +1,46 @@
--rw-r--r--   0        0        0    11804 2023-05-16 14:16:33.206267 fal-0.9.1/README.md
--rw-r--r--   0        0        0     2619 2023-05-16 14:16:48.306693 fal-0.9.1/pyproject.toml
--rw-r--r--   0        0        0      221 2023-05-16 14:16:33.214268 fal-0.9.1/src/fal/__init__.py
--rw-r--r--   0        0        0       21 2023-05-16 14:16:33.214268 fal-0.9.1/src/fal/cli/__init__.py
--rw-r--r--   0        0        0     8499 2023-05-16 14:16:33.214268 fal-0.9.1/src/fal/cli/args.py
--rw-r--r--   0        0        0     2120 2023-05-16 14:16:33.214268 fal-0.9.1/src/fal/cli/cli.py
--rw-r--r--   0        0        0     5469 2023-05-16 14:16:33.214268 fal-0.9.1/src/fal/cli/dbt_runner.py
--rw-r--r--   0        0        0     5815 2023-05-16 14:16:33.214268 fal-0.9.1/src/fal/cli/fal_runner.py
--rw-r--r--   0        0        0     4430 2023-05-16 14:16:33.214268 fal-0.9.1/src/fal/cli/flow_runner.py
--rw-r--r--   0        0        0       56 2023-05-16 14:16:33.214268 fal-0.9.1/src/fal/cli/model_generator/__init__.py
--rw-r--r--   0        0        0     5505 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/cli/model_generator/model_generator.py
--rw-r--r--   0        0        0     3180 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/cli/model_generator/module_check.py
--rw-r--r--   0        0        0     9742 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/cli/selectors.py
--rw-r--r--   0        0        0    12306 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/fal_script.py
--rw-r--r--   0        0        0        0 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/feature_store/__init__.py
--rw-r--r--   0        0        0      401 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/feature_store/feature.py
--rw-r--r--   0        0        0     8394 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/node_graph.py
--rw-r--r--   0        0        0        0 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/packages/__init__.py
--rw-r--r--   0        0        0     1603 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/packages/bridge.py
--rw-r--r--   0        0        0     5332 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/packages/dependency_analysis.py
--rw-r--r--   0        0        0      793 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/packages/environments/__init__.py
--rw-r--r--   0        0        0     9482 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/packages/environments/base.py
--rw-r--r--   0        0        0     4395 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/packages/environments/conda.py
--rw-r--r--   0        0        0     3369 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/packages/environments/virtual_env.py
--rw-r--r--   0        0        0     4776 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/packages/isolated_runner.py
--rw-r--r--   0        0        0        0 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/planner/__init__.py
--rw-r--r--   0        0        0     5635 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/planner/executor.py
--rw-r--r--   0        0        0     6475 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/planner/plan.py
--rw-r--r--   0        0        0     6761 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/planner/schedule.py
--rw-r--r--   0        0        0     9041 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/planner/tasks.py
--rw-r--r--   0        0        0        0 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/telemetry/__init__.py
--rw-r--r--   0        0        0    11416 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/telemetry/telemetry.py
--rw-r--r--   0        0        0     3043 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/typing.py
--rw-r--r--   0        0        0     1711 2023-05-16 14:16:33.218268 fal-0.9.1/src/fal/utils.py
--rw-r--r--   0        0        0        0 2023-05-16 14:16:33.218268 fal-0.9.1/src/faldbt/__init__.py
--rw-r--r--   0        0        0    24563 2023-05-16 14:16:33.218268 fal-0.9.1/src/faldbt/lib.py
--rw-r--r--   0        0        0     3273 2023-05-16 14:16:33.218268 fal-0.9.1/src/faldbt/logger.py
--rw-r--r--   0        0        0     1850 2023-05-16 14:16:33.218268 fal-0.9.1/src/faldbt/magics.py
--rw-r--r--   0        0        0     9057 2023-05-16 14:16:33.218268 fal-0.9.1/src/faldbt/parse.py
--rw-r--r--   0        0        0    27131 2023-05-16 14:16:33.218268 fal-0.9.1/src/faldbt/project.py
--rw-r--r--   0        0        0        0 2023-05-16 14:16:33.218268 fal-0.9.1/src/faldbt/utils/__init__.py
--rw-r--r--   0        0        0     1970 2023-05-16 14:16:33.218268 fal-0.9.1/src/faldbt/utils/yaml_helper.py
--rw-r--r--   0        0        0      317 2023-05-16 14:16:33.218268 fal-0.9.1/src/faldbt/version.py
--rw-r--r--   0        0        0       33 2023-05-16 14:16:33.218268 fal-0.9.1/tests/_fal_testing/__init__.py
--rw-r--r--   0        0        0     1786 2023-05-16 14:16:33.218268 fal-0.9.1/tests/_fal_testing/utils.py
--rw-r--r--   0        0        0    13992 1970-01-01 00:00:00.000000 fal-0.9.1/PKG-INFO
+-rw-r--r--   0        0        0    11804 2023-06-28 15:00:25.701967 fal-0.9.2/README.md
+-rw-r--r--   0        0        0     2498 2023-06-28 15:00:40.853979 fal-0.9.2/pyproject.toml
+-rw-r--r--   0        0        0      221 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/__init__.py
+-rw-r--r--   0        0        0       21 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/cli/__init__.py
+-rw-r--r--   0        0        0     7450 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/cli/args.py
+-rw-r--r--   0        0        0     1019 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/cli/cli.py
+-rw-r--r--   0        0        0     5469 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/cli/dbt_runner.py
+-rw-r--r--   0        0        0     5815 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/cli/fal_runner.py
+-rw-r--r--   0        0        0     4430 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/cli/flow_runner.py
+-rw-r--r--   0        0        0       56 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/cli/model_generator/__init__.py
+-rw-r--r--   0        0        0     5505 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/cli/model_generator/model_generator.py
+-rw-r--r--   0        0        0     3180 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/cli/model_generator/module_check.py
+-rw-r--r--   0        0        0     9742 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/cli/selectors.py
+-rw-r--r--   0        0        0    12306 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/fal_script.py
+-rw-r--r--   0        0        0        0 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/feature_store/__init__.py
+-rw-r--r--   0        0        0      401 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/feature_store/feature.py
+-rw-r--r--   0        0        0     8394 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/node_graph.py
+-rw-r--r--   0        0        0        0 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/packages/__init__.py
+-rw-r--r--   0        0        0     1603 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/packages/bridge.py
+-rw-r--r--   0        0        0     5332 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/packages/dependency_analysis.py
+-rw-r--r--   0        0        0      793 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/packages/environments/__init__.py
+-rw-r--r--   0        0        0     9482 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/packages/environments/base.py
+-rw-r--r--   0        0        0     4395 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/packages/environments/conda.py
+-rw-r--r--   0        0        0     3369 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/packages/environments/virtual_env.py
+-rw-r--r--   0        0        0     4776 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/packages/isolated_runner.py
+-rw-r--r--   0        0        0        0 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/planner/__init__.py
+-rw-r--r--   0        0        0     5635 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/planner/executor.py
+-rw-r--r--   0        0        0     6475 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/planner/plan.py
+-rw-r--r--   0        0        0     6761 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/planner/schedule.py
+-rw-r--r--   0        0        0     9041 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/planner/tasks.py
+-rw-r--r--   0        0        0        0 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/telemetry/__init__.py
+-rw-r--r--   0        0        0    11416 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/telemetry/telemetry.py
+-rw-r--r--   0        0        0     3043 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/typing.py
+-rw-r--r--   0        0        0     1711 2023-06-28 15:00:25.713967 fal-0.9.2/src/fal/utils.py
+-rw-r--r--   0        0        0        0 2023-06-28 15:00:25.713967 fal-0.9.2/src/faldbt/__init__.py
+-rw-r--r--   0        0        0    24563 2023-06-28 15:00:25.713967 fal-0.9.2/src/faldbt/lib.py
+-rw-r--r--   0        0        0     3273 2023-06-28 15:00:25.713967 fal-0.9.2/src/faldbt/logger.py
+-rw-r--r--   0        0        0     1850 2023-06-28 15:00:25.713967 fal-0.9.2/src/faldbt/magics.py
+-rw-r--r--   0        0        0     9057 2023-06-28 15:00:25.713967 fal-0.9.2/src/faldbt/parse.py
+-rw-r--r--   0        0        0    27131 2023-06-28 15:00:25.713967 fal-0.9.2/src/faldbt/project.py
+-rw-r--r--   0        0        0        0 2023-06-28 15:00:25.713967 fal-0.9.2/src/faldbt/utils/__init__.py
+-rw-r--r--   0        0        0     1970 2023-06-28 15:00:25.713967 fal-0.9.2/src/faldbt/utils/yaml_helper.py
+-rw-r--r--   0        0        0      317 2023-06-28 15:00:25.713967 fal-0.9.2/src/faldbt/version.py
+-rw-r--r--   0        0        0       33 2023-06-28 15:00:25.713967 fal-0.9.2/tests/_fal_testing/__init__.py
+-rw-r--r--   0        0        0     1786 2023-06-28 15:00:25.713967 fal-0.9.2/tests/_fal_testing/utils.py
+-rw-r--r--   0        0        0    13982 1970-01-01 00:00:00.000000 fal-0.9.2/PKG-INFO
```

### Comparing `fal-0.9.1/README.md` & `fal-0.9.2/README.md`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/pyproject.toml` & `fal-0.9.2/pyproject.toml`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "fal"
-version = "0.9.1"
+version = "0.9.2"
 description = "fal allows you to run python scripts directly from your dbt project."
 homepage = "https://github.com/fal-ai/fal/blob/-/projects/fal"
 documentation = "https://docs.fal.ai"
 repository = "https://github.com/fal-ai/fal"
 readme = "README.md"
 authors = [ "Features & Labels <hello@fal.ai>" ]
 packages = [
@@ -15,30 +15,29 @@
 
 keywords = [ "dbt", "pandas" ]
 classifiers = [
     "Development Status :: 4 - Beta"
 ]
 
 [tool.poetry.dependencies]
-# TODO: Python 3.11 after dill>0.3.6 version
-python = ">=3.7.2, <3.11"
-dbt-core = ">=1.5,<1.6"
+python = ">=3.7.2, <3.12"
+dbt-core = ">=1.5,<=1.5.1"
 pandas = "^1.3.4"
 PyYAML = "^6.0"
 agate-sql = "^0.5.8"
 requests = "^2.27.1"
 posthog = "^1.4.5"
 astor = "^0.8.1"
 deprecation = "^2.1.0"
 "backports.functools_lru_cache" = "^1.6.4"
 
 # Environment management related dependencies
 platformdirs = "^2.5.2"
 virtualenv = "^20.16.2"
-dill = "^0.3.5.1, <0.3.6"
+dill = ">=0.3.6,<0.3.7"
 importlib-metadata = ">=4.12.0"
 packaging = ">20.9"
 
 # Adapters
 
 ## snowflake
 snowflake-connector-python = { version = "~=3.0", extras = ["pandas"], optional = true }
@@ -49,17 +48,14 @@
 
 ## redshift
 sqlalchemy-redshift = { version = "^0.8.9", optional = true }
 
 ## duckdb
 duckdb-engine = { version = "^0.1.8", optional = true }
 
-# fal cloud
-koldstart = { version = "^0.6.16", optional = true }
-
 # dev
 pytest = { version = "^5.2", optional = true }
 black = { version = "^22.3", optional = true }
 behave = { version = "^1.2.6", optional = true }
 mock = { version = "^4.0.3", optional = true }
 pytest-mock = { version = "^3.7.0", optional = true }
 matplotlib = { version = "^3.5.2", optional = true }
@@ -77,15 +73,15 @@
     "behave",
     "mock",
     "pytest-mock",
 ]
 dev = [
     "matplotlib"
 ]
-cloud = ["koldstart"]
+cloud = []
 
 [tool.poetry.dev-dependencies]
 pytest = { version = "^5.2", optional = true }
 black = { version = "^22.3", optional = true }
 behave = { version = "^1.2.6", optional = true }
 mock = { version = "^4.0.3", optional = true }
 pytest-mock = { version = "^3.7.0", optional = true }
```

### Comparing `fal-0.9.1/src/fal/cli/args.py` & `fal-0.9.2/src/fal/cli/args.py`

 * *Files 15% similar despite different names*

```diff
@@ -198,52 +198,14 @@
     _add_threads_option(flow_run_parser)
     _add_state_option(flow_run_parser)
     _add_vars_option(flow_run_parser)
     _add_target_option(flow_run_parser)
     _add_full_refresh_option(flow_run_parser)
 
 
-def _build_cloud_parser(sub: argparse.ArgumentParser):
-    cloud_command_parsers = sub.add_subparsers(
-        title="cloud commands",
-        dest="cloud_command",
-        metavar="COMMAND",
-        required=True,
-    )
-
-    cloud_command_parsers.add_parser(
-        name="login",
-        help="Login to fal cloud",
-    )
-
-    cloud_command_parsers.add_parser(
-        name="logout",
-        help="Logout of fal cloud",
-    )
-
-    generator_parser = cloud_command_parsers.add_parser(
-        name="key-generate",
-        help="Generate a secret key for fal cloud",
-    )
-
-    generator_parser.add_argument(
-        "--host",
-        type=str,
-        default="api.alpha.fal.ai",
-        help="Specify fal cloud host instance URL",
-    )
-
-    generator_parser.add_argument(
-        "--port",
-        type=str,
-        default="443",
-        help="Specify fal cloud host instance PORT",
-    )
-
-
 def _build_cli_parser():
     parser = argparse.ArgumentParser(
         prog="fal",
         description="Run Python scripts on dbt models",
     )
 
     version = pkg_resources.get_distribution("fal").version
@@ -281,21 +243,14 @@
     flow_parser = command_parsers.add_parser(
         name="flow",
         help="Execute fal and dbt commands in correct order",
     )
 
     _build_flow_parser(flow_parser)
 
-    cloud_parser = command_parsers.add_parser(
-        name="cloud",
-        help="Interact with fal cloud",
-    )
-
-    _build_cloud_parser(cloud_parser)
-
     return parser
 
 
 cli_parser = _build_cli_parser()
 
 
 def parse_args(argv: List[str]) -> argparse.Namespace:
```

### Comparing `fal-0.9.1/src/fal/cli/dbt_runner.py` & `fal-0.9.2/src/fal/cli/dbt_runner.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/cli/fal_runner.py` & `fal-0.9.2/src/fal/cli/fal_runner.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/cli/flow_runner.py` & `fal-0.9.2/src/fal/cli/flow_runner.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/cli/model_generator/model_generator.py` & `fal-0.9.2/src/fal/cli/model_generator/model_generator.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/cli/model_generator/module_check.py` & `fal-0.9.2/src/fal/cli/model_generator/module_check.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/cli/selectors.py` & `fal-0.9.2/src/fal/cli/selectors.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/fal_script.py` & `fal-0.9.2/src/fal/fal_script.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/node_graph.py` & `fal-0.9.2/src/fal/node_graph.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/packages/bridge.py` & `fal-0.9.2/src/fal/packages/bridge.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/packages/dependency_analysis.py` & `fal-0.9.2/src/fal/packages/dependency_analysis.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/packages/environments/__init__.py` & `fal-0.9.2/src/fal/packages/environments/__init__.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/packages/environments/base.py` & `fal-0.9.2/src/fal/packages/environments/base.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/packages/environments/conda.py` & `fal-0.9.2/src/fal/packages/environments/conda.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/packages/environments/virtual_env.py` & `fal-0.9.2/src/fal/packages/environments/virtual_env.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/packages/isolated_runner.py` & `fal-0.9.2/src/fal/packages/isolated_runner.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/planner/executor.py` & `fal-0.9.2/src/fal/planner/executor.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/planner/plan.py` & `fal-0.9.2/src/fal/planner/plan.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/planner/schedule.py` & `fal-0.9.2/src/fal/planner/schedule.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/planner/tasks.py` & `fal-0.9.2/src/fal/planner/tasks.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/telemetry/telemetry.py` & `fal-0.9.2/src/fal/telemetry/telemetry.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/typing.py` & `fal-0.9.2/src/fal/typing.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/fal/utils.py` & `fal-0.9.2/src/fal/utils.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/faldbt/lib.py` & `fal-0.9.2/src/faldbt/lib.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/faldbt/logger.py` & `fal-0.9.2/src/faldbt/logger.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/faldbt/magics.py` & `fal-0.9.2/src/faldbt/magics.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/faldbt/parse.py` & `fal-0.9.2/src/faldbt/parse.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/faldbt/project.py` & `fal-0.9.2/src/faldbt/project.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/src/faldbt/utils/yaml_helper.py` & `fal-0.9.2/src/faldbt/utils/yaml_helper.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/tests/_fal_testing/utils.py` & `fal-0.9.2/tests/_fal_testing/utils.py`

 * *Files identical despite different names*

### Comparing `fal-0.9.1/PKG-INFO` & `fal-0.9.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,21 +1,22 @@
 Metadata-Version: 2.1
 Name: fal
-Version: 0.9.1
+Version: 0.9.2
 Summary: fal allows you to run python scripts directly from your dbt project.
 Home-page: https://github.com/fal-ai/fal/blob/-/projects/fal
 Keywords: dbt,pandas
 Author: Features & Labels
 Author-email: hello@fal.ai
-Requires-Python: >=3.7.2,<3.11
+Requires-Python: >=3.7.2,<3.12
 Classifier: Development Status :: 4 - Beta
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 Provides-Extra: athena
 Provides-Extra: bigquery
 Provides-Extra: cloud
 Provides-Extra: dev
 Provides-Extra: duckdb
 Provides-Extra: postgres
 Provides-Extra: redshift
@@ -23,21 +24,20 @@
 Provides-Extra: test
 Requires-Dist: PyYAML (>=6.0,<7.0)
 Requires-Dist: agate-sql (>=0.5.8,<0.6.0)
 Requires-Dist: astor (>=0.8.1,<0.9.0)
 Requires-Dist: backports.functools_lru_cache (>=1.6.4,<2.0.0)
 Requires-Dist: behave (>=1.2.6,<2.0.0) ; extra == "test"
 Requires-Dist: black (>=22.3,<23.0) ; extra == "test"
-Requires-Dist: dbt-core (>=1.5,<1.6)
+Requires-Dist: dbt-core (>=1.5,<=1.5.1)
 Requires-Dist: deprecation (>=2.1.0,<3.0.0)
-Requires-Dist: dill (>=0.3.5.1,<0.3.6)
+Requires-Dist: dill (>=0.3.6,<0.3.7)
 Requires-Dist: duckdb-engine (>=0.1.8,<0.2.0) ; extra == "duckdb"
 Requires-Dist: google-cloud-bigquery[pandas] (>=3.5.0,<3.6.0) ; extra == "bigquery"
 Requires-Dist: importlib-metadata (>=4.12.0)
-Requires-Dist: koldstart (>=0.6.16,<0.7.0) ; extra == "cloud"
 Requires-Dist: matplotlib (>=3.5.2,<4.0.0) ; extra == "dev"
 Requires-Dist: mock (>=4.0.3,<5.0.0) ; extra == "test"
 Requires-Dist: packaging (>20.9)
 Requires-Dist: pandas (>=1.3.4,<2.0.0)
 Requires-Dist: platformdirs (>=2.5.2,<3.0.0)
 Requires-Dist: posthog (>=1.4.5,<2.0.0)
 Requires-Dist: pytest (>=5.2,<6.0) ; extra == "test"
```


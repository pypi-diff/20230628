# Comparing `tmp/dbt-graph-builder-0.1.1.tar.gz` & `tmp/dbt-graph-builder-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dbt-graph-builder-0.1.1.tar", last modified: Mon Jun 26 13:56:12 2023, max compression
+gzip compressed data, was "dbt-graph-builder-0.2.0.tar", last modified: Wed Jun 28 13:11:18 2023, max compression
```

## Comparing `dbt-graph-builder-0.1.1.tar` & `dbt-graph-builder-0.2.0.tar`

### file list

```diff
@@ -1,26 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 13:56:12.415528 dbt-graph-builder-0.1.1/
--rw-r--r--   0 runner    (1001) docker     (123)     1141 2023-06-26 13:55:52.000000 dbt-graph-builder-0.1.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     4767 2023-06-26 13:56:12.415528 dbt-graph-builder-0.1.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2922 2023-06-26 13:55:52.000000 dbt-graph-builder-0.1.1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)     1849 2023-06-26 13:55:52.000000 dbt-graph-builder-0.1.1/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-26 13:56:12.415528 dbt-graph-builder-0.1.1/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 13:56:12.411528 dbt-graph-builder-0.1.1/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 13:56:12.411528 dbt-graph-builder-0.1.1/src/dbt_graph_builder/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 13:55:52.000000 dbt-graph-builder-0.1.1/src/dbt_graph_builder/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2357 2023-06-26 13:55:52.000000 dbt-graph-builder-0.1.1/src/dbt_graph_builder/builder.py
--rw-r--r--   0 runner    (1001) docker     (123)     5232 2023-06-26 13:55:52.000000 dbt-graph-builder-0.1.1/src/dbt_graph_builder/gateway.py
--rw-r--r--   0 runner    (1001) docker     (123)    11688 2023-06-26 13:55:52.000000 dbt-graph-builder-0.1.1/src/dbt_graph_builder/graph.py
--rw-r--r--   0 runner    (1001) docker     (123)      279 2023-06-26 13:55:52.000000 dbt-graph-builder-0.1.1/src/dbt_graph_builder/node_type.py
--rw-r--r--   0 runner    (1001) docker     (123)     1450 2023-06-26 13:55:52.000000 dbt-graph-builder-0.1.1/src/dbt_graph_builder/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 13:56:12.415528 dbt-graph-builder-0.1.1/src/dbt_graph_builder.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     4767 2023-06-26 13:56:12.000000 dbt-graph-builder-0.1.1/src/dbt_graph_builder.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      604 2023-06-26 13:56:12.000000 dbt-graph-builder-0.1.1/src/dbt_graph_builder.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 13:56:12.000000 dbt-graph-builder-0.1.1/src/dbt_graph_builder.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-26 13:56:12.000000 dbt-graph-builder-0.1.1/src/dbt_graph_builder.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-26 13:56:12.000000 dbt-graph-builder-0.1.1/src/dbt_graph_builder.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 13:56:12.415528 dbt-graph-builder-0.1.1/tests/
--rw-r--r--   0 runner    (1001) docker     (123)     4121 2023-06-26 13:55:52.000000 dbt-graph-builder-0.1.1/tests/test_gateway.py
--rw-r--r--   0 runner    (1001) docker     (123)     1542 2023-06-26 13:55:52.000000 dbt-graph-builder-0.1.1/tests/test_graph.py
--rw-r--r--   0 runner    (1001) docker     (123)     4630 2023-06-26 13:55:52.000000 dbt-graph-builder-0.1.1/tests/test_graph_dag_dependencies.py
--rw-r--r--   0 runner    (1001) docker     (123)    10427 2023-06-26 13:55:52.000000 dbt-graph-builder-0.1.1/tests/test_graph_dependencies.py
--rw-r--r--   0 runner    (1001) docker     (123)     4863 2023-06-26 13:55:52.000000 dbt-graph-builder-0.1.1/tests/test_graph_ephemeral_operator.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:11:18.566602 dbt-graph-builder-0.2.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1141 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     4767 2023-06-28 13:11:18.566602 dbt-graph-builder-0.2.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2922 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/VERSION
+-rw-r--r--   0 runner    (1001) docker     (123)     1910 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 13:11:18.566602 dbt-graph-builder-0.2.0/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:11:18.566602 dbt-graph-builder-0.2.0/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:11:18.566602 dbt-graph-builder-0.2.0/src/dbt_graph_builder/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/src/dbt_graph_builder/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2507 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/src/dbt_graph_builder/builder.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5232 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/src/dbt_graph_builder/gateway.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11688 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/src/dbt_graph_builder/graph.py
+-rw-r--r--   0 runner    (1001) docker     (123)      279 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/src/dbt_graph_builder/node_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1450 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/src/dbt_graph_builder/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:11:18.566602 dbt-graph-builder-0.2.0/src/dbt_graph_builder.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     4767 2023-06-28 13:11:18.000000 dbt-graph-builder-0.2.0/src/dbt_graph_builder.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      612 2023-06-28 13:11:18.000000 dbt-graph-builder-0.2.0/src/dbt_graph_builder.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:11:18.000000 dbt-graph-builder-0.2.0/src/dbt_graph_builder.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 13:11:18.000000 dbt-graph-builder-0.2.0/src/dbt_graph_builder.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-28 13:11:18.000000 dbt-graph-builder-0.2.0/src/dbt_graph_builder.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:11:18.566602 dbt-graph-builder-0.2.0/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     4121 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/tests/test_gateway.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1630 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/tests/test_graph.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4647 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/tests/test_graph_dag_dependencies.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9677 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/tests/test_graph_dependencies.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4693 2023-06-28 13:10:59.000000 dbt-graph-builder-0.2.0/tests/test_graph_ephemeral_operator.py
```

### Comparing `dbt-graph-builder-0.1.1/LICENSE` & `dbt-graph-builder-0.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `dbt-graph-builder-0.1.1/PKG-INFO` & `dbt-graph-builder-0.2.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dbt-graph-builder
-Version: 0.1.1
+Version: 0.2.0
 Summary: DBT Graph Builder
 Author-email: Piotr Tutak <piotr.tutak@getindata.com>
 License:     MIT License
         
             Copyright (c) Microsoft Corporation.
         
             Permission is hereby granted, free of charge, to any person obtaining a copy
```

### Comparing `dbt-graph-builder-0.1.1/README.md` & `dbt-graph-builder-0.2.0/README.md`

 * *Files identical despite different names*

### Comparing `dbt-graph-builder-0.1.1/pyproject.toml` & `dbt-graph-builder-0.2.0/pyproject.toml`

 * *Files 5% similar despite different names*

```diff
@@ -1,32 +1,32 @@
 [build-system]
 requires = ["setuptools>=61", "wheel"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "dbt-graph-builder"
-version = "0.1.1"
 description = "DBT Graph Builder"
 authors = [
     {name = "Piotr Tutak", email = "piotr.tutak@getindata.com"},
 ]
 classifiers = [
     "Development Status :: 3 - Alpha",
     "Intended Audience :: Developers",
     "License :: OSI Approved :: MIT License",
     "Programming Language :: Python :: 3 :: Only",
     "Programming Language :: Python :: 3.10",
     "Programming Language :: Python :: 3.11"
 ]
 dependencies = [
-    "networkx>=2.6.3",
+    "networkx>=2.6,<3",
 ]
 requires-python = ">=3.10"
 readme = "README.md"
 license = {file = "LICENSE"}
+dynamic = ["version"]
 
 [tool.bandit]
 exclude_dirs = ["build","dist","tests","scripts"]
 number = 4
 recursive = true
 targets = "src"
 
@@ -71,14 +71,17 @@
     "notebooks: marks as notebook test",
     "gpu: marks as gpu test",
     "spark: marks tests which need Spark",
     "slow: marks tests as slow",
     "unit: fast offline tests",
 ]
 
+[tool.setuptools.dynamic]
+version = {file = "VERSION"}
+
 [tool.pdm.dev-dependencies]
 dev = [
     "pre-commit",
     "pytest",
     "pytest-cov",
     "pytest-xdist",
     "pytest-github-actions-annotate-failures",
```

### Comparing `dbt-graph-builder-0.1.1/src/dbt_graph_builder/builder.py` & `dbt-graph-builder-0.2.0/src/dbt_graph_builder/builder.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,43 +1,47 @@
 import json
 import logging
 import os
-from typing import Any, cast
+from typing import Any, NamedTuple, cast
 
 from dbt_graph_builder.gateway import GatewayConfiguration, TaskGraphConfiguration
 from dbt_graph_builder.graph import DbtManifestGraph
 
 LOGGER = logging.getLogger(__name__)
 
 
+class GraphConfiguration(NamedTuple):
+    """Graph configuration."""
+
+    gateway_config: GatewayConfiguration = GatewayConfiguration(gateway_task_name="gateway", separation_schemas=[])
+    enable_dags_dependencies: bool = False
+    show_ephemeral_models: bool = False
+
+
 def create_tasks_graph(
-    gateway_config: GatewayConfiguration,
     manifest: dict[str, Any],
-    enable_dags_dependencies: bool,
-    show_ephemeral_models: bool,
+    graph_config: GraphConfiguration = GraphConfiguration(),
 ) -> DbtManifestGraph:
     """Create tasks graph.
 
     Args:
-        gateway_config (GatewayConfiguration): Gateway configuration.
         manifest (dict[str, Any]): Manifest.
-        enable_dags_dependencies (bool): If True, add external dependencies to the graph.
-        show_ephemeral_models (bool): If True, show ephemeral models in the graph.
+        graph_config (GraphConfiguration, optional): Graph configuration. Defaults to GraphConfiguration().
 
     Returns:
         DbtManifestGraph: Tasks graph.
     """
     LOGGER.info("Creating tasks graph")
-    dbt_airflow_graph = DbtManifestGraph(TaskGraphConfiguration(gateway_config))
+    dbt_airflow_graph = DbtManifestGraph(TaskGraphConfiguration(graph_config.gateway_config))
     dbt_airflow_graph.add_execution_tasks(manifest)
-    if enable_dags_dependencies:
+    if graph_config.enable_dags_dependencies:
         LOGGER.debug("Adding external dependencies")
         dbt_airflow_graph.add_external_dependencies(manifest)
-    dbt_airflow_graph.create_edges_from_dependencies(enable_dags_dependencies)
-    if not show_ephemeral_models:
+    dbt_airflow_graph.create_edges_from_dependencies(graph_config.enable_dags_dependencies)
+    if not graph_config.show_ephemeral_models:
         LOGGER.debug("Removing ephemeral nodes from graph")
         dbt_airflow_graph.remove_ephemeral_nodes_from_graph()
     LOGGER.debug("Contracting test nodes")
     dbt_airflow_graph.contract_test_nodes()
     return dbt_airflow_graph
```

### Comparing `dbt-graph-builder-0.1.1/src/dbt_graph_builder/gateway.py` & `dbt-graph-builder-0.2.0/src/dbt_graph_builder/gateway.py`

 * *Files identical despite different names*

### Comparing `dbt-graph-builder-0.1.1/src/dbt_graph_builder/graph.py` & `dbt-graph-builder-0.2.0/src/dbt_graph_builder/graph.py`

 * *Files identical despite different names*

### Comparing `dbt-graph-builder-0.1.1/src/dbt_graph_builder/utils.py` & `dbt-graph-builder-0.2.0/src/dbt_graph_builder/utils.py`

 * *Files identical despite different names*

### Comparing `dbt-graph-builder-0.1.1/src/dbt_graph_builder.egg-info/PKG-INFO` & `dbt-graph-builder-0.2.0/src/dbt_graph_builder.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dbt-graph-builder
-Version: 0.1.1
+Version: 0.2.0
 Summary: DBT Graph Builder
 Author-email: Piotr Tutak <piotr.tutak@getindata.com>
 License:     MIT License
         
             Copyright (c) Microsoft Corporation.
         
             Permission is hereby granted, free of charge, to any person obtaining a copy
```

### Comparing `dbt-graph-builder-0.1.1/src/dbt_graph_builder.egg-info/SOURCES.txt` & `dbt-graph-builder-0.2.0/src/dbt_graph_builder.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -1,9 +1,10 @@
 LICENSE
 README.md
+VERSION
 pyproject.toml
 src/dbt_graph_builder/__init__.py
 src/dbt_graph_builder/builder.py
 src/dbt_graph_builder/gateway.py
 src/dbt_graph_builder/graph.py
 src/dbt_graph_builder/node_type.py
 src/dbt_graph_builder/utils.py
```

### Comparing `dbt-graph-builder-0.1.1/tests/test_gateway.py` & `dbt-graph-builder-0.2.0/tests/test_gateway.py`

 * *Files identical despite different names*

### Comparing `dbt-graph-builder-0.1.1/tests/test_graph.py` & `dbt-graph-builder-0.2.0/tests/test_graph.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,25 +1,28 @@
 from os import path
 
 from dbt_graph_builder.builder import (
+    GraphConfiguration,
     create_gateway_config,
     create_tasks_graph,
     load_dbt_manifest,
 )
 from dbt_graph_builder.node_type import NodeType
 
 
 def test_manifest_graph():
     # given
     # when
     graph = create_tasks_graph(
-        gateway_config=create_gateway_config({"save_points": ["stg", "pp_private_working_schema_dbt_test__audit"]}),
         manifest=load_dbt_manifest(path.join(path.dirname(__file__), "manifests/manifest.json")),
-        enable_dags_dependencies=True,
-        show_ephemeral_models=False,
+        graph_config=GraphConfiguration(
+            gateway_config=create_gateway_config({"save_points": ["stg", "pp_private_working_schema_dbt_test__audit"]}),
+            enable_dags_dependencies=True,
+            show_ephemeral_models=False,
+        ),
     )
 
     # then
     assert list(graph.get_graph_nodes()) == [
         (
             "stg_pp_private_working_schema_dbt_test__audit_gateway",
             {
```

### Comparing `dbt-graph-builder-0.1.1/tests/test_graph_dag_dependencies.py` & `dbt-graph-builder-0.2.0/tests/test_graph_dag_dependencies.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 from dbt_graph_builder.builder import (
-    create_gateway_config,
+    GraphConfiguration,
     create_tasks_graph,
     load_dbt_manifest,
 )
 from dbt_graph_builder.node_type import NodeType
 
 from .utils import manifest_file_with_models
 
@@ -42,18 +42,19 @@
     # given
     manifest_path = manifest_file_with_models(
         {"model.dbt_test.dependent_model": ["source.upstream_pipeline_sources.upstream_pipeline.some_final_model"]},
         extra_metadata_data,
     )
     # when
     graph = create_tasks_graph(
-        gateway_config=create_gateway_config({}),
         manifest=load_dbt_manifest(manifest_path),
-        enable_dags_dependencies=True,
-        show_ephemeral_models=False,
+        graph_config=GraphConfiguration(
+            enable_dags_dependencies=True,
+            show_ephemeral_models=False,
+        ),
     )
     # then
     assert graph.get_graph_sources() == ["source.upstream_pipeline_sources.upstream_pipeline.some_final_model"]
     assert graph.get_graph_sinks() == ["model.dbt_test.dependent_model"]
     assert list(graph.get_graph_nodes()) == [
         (
             "model.dbt_test.dependent_model",
@@ -90,18 +91,19 @@
             ]
         },
         extra_metadata_data,
     )
 
     # when
     graph = create_tasks_graph(
-        gateway_config=create_gateway_config({}),
         manifest=load_dbt_manifest(manifest_path),
-        enable_dags_dependencies=True,
-        show_ephemeral_models=False,
+        graph_config=GraphConfiguration(
+            enable_dags_dependencies=True,
+            show_ephemeral_models=False,
+        ),
     )
 
     # then
     assert graph.get_graph_sources() == ["source.upstream_pipeline_sources.upstream_pipeline.some_final_model"]
     assert graph.get_graph_sinks() == ["model.dbt_test.dependent_model"]
     assert list(graph.get_graph_nodes()) == [
         (
```

### Comparing `dbt-graph-builder-0.1.1/tests/test_graph_dependencies.py` & `dbt-graph-builder-0.2.0/tests/test_graph_dependencies.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,28 +1,19 @@
-from dbt_graph_builder.builder import (
-    create_gateway_config,
-    create_tasks_graph,
-    load_dbt_manifest,
-)
+from dbt_graph_builder.builder import create_tasks_graph, load_dbt_manifest
 from dbt_graph_builder.node_type import NodeType
 
 from .utils import manifest_file_with_models
 
 
 def test_run_test_dependency():
     # given
     manifest_path = manifest_file_with_models({"model.dbt_test.model1": []})
 
     # when
-    graph = create_tasks_graph(
-        gateway_config=create_gateway_config({}),
-        manifest=load_dbt_manifest(manifest_path),
-        enable_dags_dependencies=False,
-        show_ephemeral_models=False,
-    )
+    graph = create_tasks_graph(manifest=load_dbt_manifest(manifest_path))
 
     # then
     assert list(graph.get_graph_edges()) == []
     assert list(graph.get_graph_nodes()) == [
         ("model.dbt_test.model1", {"select": "model1", "depends_on": [], "node_type": NodeType.RUN_TEST})
     ]
     assert graph.get_graph_sinks() == ["model.dbt_test.model1"]
@@ -35,20 +26,15 @@
         {
             "model.dbt_test.model1": [],
             "model.dbt_test.model2": ["model.dbt_test.model1"],
         }
     )
 
     # when
-    graph = create_tasks_graph(
-        gateway_config=create_gateway_config({}),
-        manifest=load_dbt_manifest(manifest_path),
-        enable_dags_dependencies=False,
-        show_ephemeral_models=False,
-    )
+    graph = create_tasks_graph(manifest=load_dbt_manifest(manifest_path))
 
     # then
     assert list(graph.get_graph_edges()) == [("model.dbt_test.model1", "model.dbt_test.model2")]
     assert list(graph.get_graph_nodes()) == [
         ("model.dbt_test.model1", {"select": "model1", "depends_on": [], "node_type": NodeType.RUN_TEST}),
         (
             "model.dbt_test.model2",
@@ -67,20 +53,15 @@
             "model.dbt_test.model2": ["model.dbt_test.model1"],
             "model.dbt_test.model3": ["model.dbt_test.model1", "model.dbt_test.model2"],
             "model.dbt_test.model4": ["model.dbt_test.model3"],
         }
     )
 
     # when
-    graph = create_tasks_graph(
-        gateway_config=create_gateway_config({}),
-        manifest=load_dbt_manifest(manifest_path),
-        enable_dags_dependencies=False,
-        show_ephemeral_models=False,
-    )
+    graph = create_tasks_graph(manifest=load_dbt_manifest(manifest_path))
 
     # then
     assert list(graph.get_graph_edges()) == [
         ("model.dbt_test.model1", "model.dbt_test.model2"),
         ("model.dbt_test.model1", "model.dbt_test.model3"),
         ("model.dbt_test.model2", "model.dbt_test.model3"),
         ("model.dbt_test.model3", "model.dbt_test.model4"),
@@ -117,20 +98,15 @@
             "model.dbt_test.model3": ["model.dbt_test.model2"],
             "test.dbt_test.test1": ["model.dbt_test.model1"],
             "test.dbt_test.test2": ["model.dbt_test.model1", "model.dbt_test.model2"],
         }
     )
 
     # when
-    graph = create_tasks_graph(
-        gateway_config=create_gateway_config({}),
-        manifest=load_dbt_manifest(manifest_path),
-        enable_dags_dependencies=False,
-        show_ephemeral_models=False,
-    )
+    graph = create_tasks_graph(manifest=load_dbt_manifest(manifest_path))
 
     # then
     assert list(graph.get_graph_edges()) == [
         ("model.dbt_test.model1", "model.dbt_test.model2"),
         ("model.dbt_test.model1", "model1_model2_test"),
         ("model.dbt_test.model2", "model.dbt_test.model3"),
         ("model.dbt_test.model2", "model1_model2_test"),
@@ -174,20 +150,15 @@
             "test.dbt_test.test3": ["model.dbt_test.model2", "model.dbt_test.model3"],
             "test.dbt_test.test4": ["model.dbt_test.model3", "model.dbt_test.model2"],
             "test.dbt_test.test5": ["model.dbt_test.model3", "model.dbt_test.model2"],
         }
     )
 
     # when
-    graph = create_tasks_graph(
-        gateway_config=create_gateway_config({}),
-        manifest=load_dbt_manifest(manifest_path),
-        enable_dags_dependencies=False,
-        show_ephemeral_models=False,
-    )
+    graph = create_tasks_graph(manifest=load_dbt_manifest(manifest_path))
 
     # then
     assert list(graph.get_graph_edges()) == [
         ("model.dbt_test.model1", "model.dbt_test.model2"),
         ("model.dbt_test.model1", "model.dbt_test.model4"),
         ("model.dbt_test.model2", "model.dbt_test.model3"),
         ("model.dbt_test.model2", "model.dbt_test.model4"),
```

### Comparing `dbt-graph-builder-0.1.1/tests/test_graph_ephemeral_operator.py` & `dbt-graph-builder-0.2.0/tests/test_graph_ephemeral_operator.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,26 +1,26 @@
 from os import path
 
 from dbt_graph_builder.builder import (
-    create_gateway_config,
+    GraphConfiguration,
     create_tasks_graph,
     load_dbt_manifest,
 )
 from dbt_graph_builder.node_type import NodeType
-from tests.utils import task_group_prefix_builder
 
 
 def test_ephemeral_dag():
     # given
     # when
     graph = create_tasks_graph(
-        gateway_config=create_gateway_config({}),
         manifest=load_dbt_manifest(path.join(path.dirname(__file__), "manifests/manifest_ephemeral.json")),
-        enable_dags_dependencies=False,
-        show_ephemeral_models=True,
+        graph_config=GraphConfiguration(
+            enable_dags_dependencies=False,
+            show_ephemeral_models=True,
+        ),
     )
 
     # then
     assert list(graph.get_graph_nodes()) == [
         (
             "model.dbt_test.model1",
             {"select": "model1", "depends_on": ["source.dbt_test.source1"], "node_type": NodeType.RUN_TEST},
@@ -95,18 +95,15 @@
     assert graph.get_graph_sources() == ["model.dbt_test.model1", "model.dbt_test.model5", "model.dbt_test.model6"]
 
 
 def test_no_ephemeral_dag():
     # given
     # when
     graph = create_tasks_graph(
-        gateway_config=create_gateway_config({}),
         manifest=load_dbt_manifest(path.join(path.dirname(__file__), "manifests/manifest_ephemeral.json")),
-        enable_dags_dependencies=False,
-        show_ephemeral_models=False,
     )
 
     # then
     assert list(graph.get_graph_nodes()) == [
         (
             "model.dbt_test.model1",
             {"select": "model1", "depends_on": ["source.dbt_test.source1"], "node_type": NodeType.RUN_TEST},
```


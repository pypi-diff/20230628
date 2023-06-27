# Comparing `tmp/astronomer_cosmos-0.7.3.tar.gz` & `tmp/astronomer_cosmos-0.7.4.tar.gz`

## Comparing `astronomer_cosmos-0.7.3.tar` & `astronomer_cosmos-0.7.4.tar`

### file list

```diff
@@ -1,52 +1,49 @@
--rw-r--r--   0        0        0      108 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/__init__.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/core/__init__.py
--rw-r--r--   0        0        0     3596 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/core/airflow.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/core/graph/__init__.py
--rw-r--r--   0        0        0     1578 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/core/graph/entities.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/__init__.py
--rw-r--r--   0        0        0     3707 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/__init__.py
--rw-r--r--   0        0        0      201 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/constants.py
--rw-r--r--   0        0        0     4161 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/dag.py
--rw-r--r--   0        0        0      446 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/dataset.py
--rw-r--r--   0        0        0    11528 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/render.py
--rw-r--r--   0        0        0     4386 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/task_group.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/__init__.py
--rw-r--r--   0        0        0      904 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/operators/__init__.py
--rw-r--r--   0        0        0     9047 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/operators/base.py
--rw-r--r--   0        0        0     5076 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/operators/docker.py
--rw-r--r--   0        0        0     5481 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/operators/kubernetes.py
--rw-r--r--   0        0        0      371 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/operators/lazy_load.py
--rw-r--r--   0        0        0    19405 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/operators/local.py
--rw-r--r--   0        0        0     5307 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/operators/virtualenv.py
--rw-r--r--   0        0        0     1938 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/__init__.py
--rw-r--r--   0        0        0     5525 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/base.py
--rw-r--r--   0        0        0      192 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/bigquery/__init__.py
--rw-r--r--   0        0        0     1305 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/bigquery/service_account_file.py
--rw-r--r--   0        0        0      151 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/databricks/__init__.py
--rw-r--r--   0        0        0     1445 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/databricks/token.py
--rw-r--r--   0        0        0      157 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/exasol/__init__.py
--rw-r--r--   0        0        0     2304 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/exasol/user_pass.py
--rw-r--r--   0        0        0      163 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/postgres/__init__.py
--rw-r--r--   0        0        0     1776 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/postgres/user_pass.py
--rw-r--r--   0        0        0      163 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/redshift/__init__.py
--rw-r--r--   0        0        0     1724 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/redshift/user_pass.py
--rw-r--r--   0        0        0      166 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/snowflake/__init__.py
--rw-r--r--   0        0        0     2806 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/snowflake/user_pass.py
--rw-r--r--   0        0        0      139 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/spark/__init__.py
--rw-r--r--   0        0        0     1185 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/spark/thrift.py
--rw-r--r--   0        0        0      377 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/trino/__init__.py
--rw-r--r--   0        0        0     1262 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/trino/base.py
--rw-r--r--   0        0        0     1314 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/trino/certificate.py
--rw-r--r--   0        0        0     1382 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/trino/jwt.py
--rw-r--r--   0        0        0     1284 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/trino/ldap.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/utils/__init__.py
--rw-r--r--   0        0        0     4445 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/utils/adapted_subprocesshook.py
--rw-r--r--   0        0        0      225 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/utils/data_aware_scheduling.py
--rw-r--r--   0        0        0     2516 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/utils/warn_parsing.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/parser/__init__.py
--rw-r--r--   0        0        0    11200 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/cosmos/providers/dbt/parser/project.py
--rw-r--r--   0        0        0     2069 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/.gitignore
--rw-r--r--   0        0        0    11357 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/LICENSE
--rw-r--r--   0        0        0     3498 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/README.rst
--rw-r--r--   0        0        0     4706 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/pyproject.toml
--rw-r--r--   0        0        0     6965 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.3/PKG-INFO
+-rw-r--r--   0        0        0     3424 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/__init__.py
+-rw-r--r--   0        0        0      201 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/constants.py
+-rw-r--r--   0        0        0     4161 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/dag.py
+-rw-r--r--   0        0        0      622 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/dataset.py
+-rw-r--r--   0        0        0    11460 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/render.py
+-rw-r--r--   0        0        0     4386 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/task_group.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/core/__init__.py
+-rw-r--r--   0        0        0     3596 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/core/airflow.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/core/graph/__init__.py
+-rw-r--r--   0        0        0     1578 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/core/graph/entities.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/dbt/__init__.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/dbt/parser/__init__.py
+-rw-r--r--   0        0        0     2516 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/dbt/parser/output.py
+-rw-r--r--   0        0        0    11165 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/dbt/parser/project.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/hooks/__init__.py
+-rw-r--r--   0        0        0     4445 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/hooks/subprocess.py
+-rw-r--r--   0        0        0      904 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/operators/__init__.py
+-rw-r--r--   0        0        0     9126 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/operators/base.py
+-rw-r--r--   0        0        0     5057 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/operators/docker.py
+-rw-r--r--   0        0        0     5462 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/operators/kubernetes.py
+-rw-r--r--   0        0        0      371 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/operators/lazy_load.py
+-rw-r--r--   0        0        0    19302 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/operators/local.py
+-rw-r--r--   0        0        0     5288 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/operators/virtualenv.py
+-rw-r--r--   0        0        0     1938 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/__init__.py
+-rw-r--r--   0        0        0     5525 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/base.py
+-rw-r--r--   0        0        0      192 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/bigquery/__init__.py
+-rw-r--r--   0        0        0     1286 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/bigquery/service_account_file.py
+-rw-r--r--   0        0        0      151 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/databricks/__init__.py
+-rw-r--r--   0        0        0     1445 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/databricks/token.py
+-rw-r--r--   0        0        0      157 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/exasol/__init__.py
+-rw-r--r--   0        0        0     2304 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/exasol/user_pass.py
+-rw-r--r--   0        0        0      163 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/postgres/__init__.py
+-rw-r--r--   0        0        0     1776 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/postgres/user_pass.py
+-rw-r--r--   0        0        0      163 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/redshift/__init__.py
+-rw-r--r--   0        0        0     1724 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/redshift/user_pass.py
+-rw-r--r--   0        0        0      166 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/snowflake/__init__.py
+-rw-r--r--   0        0        0     2806 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/snowflake/user_pass.py
+-rw-r--r--   0        0        0      139 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/spark/__init__.py
+-rw-r--r--   0        0        0     1185 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/spark/thrift.py
+-rw-r--r--   0        0        0      377 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/trino/__init__.py
+-rw-r--r--   0        0        0     1262 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/trino/base.py
+-rw-r--r--   0        0        0     1314 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/trino/certificate.py
+-rw-r--r--   0        0        0     1382 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/trino/jwt.py
+-rw-r--r--   0        0        0     1284 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/cosmos/profiles/trino/ldap.py
+-rw-r--r--   0        0        0     2069 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/.gitignore
+-rw-r--r--   0        0        0    11357 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/LICENSE
+-rw-r--r--   0        0        0     3498 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/README.rst
+-rw-r--r--   0        0        0     4706 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/pyproject.toml
+-rw-r--r--   0        0        0     6965 2020-02-02 00:00:00.000000 astronomer_cosmos-0.7.4/PKG-INFO
```

### Comparing `astronomer_cosmos-0.7.3/cosmos/core/airflow.py` & `astronomer_cosmos-0.7.4/cosmos/core/airflow.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/core/graph/entities.py` & `astronomer_cosmos-0.7.4/cosmos/core/graph/entities.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/__init__.py` & `astronomer_cosmos-0.7.4/cosmos/__init__.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,88 +1,88 @@
-# type: ignore
 """
-dbt support for Airflow. Contains dags, task groups, and operators.
+Astronomer Cosmos is a library for rendering dbt workflows in Airflow.
+
+Contains dags, task groups, and operators.
 """
 
-# re-export user facing utilities
-from cosmos.providers.dbt.core.utils.data_aware_scheduling import get_dbt_dataset
+__version__ = "0.7.4"
+
+from cosmos.dataset import get_dbt_dataset
 
 # re-export the dag and task group
-from cosmos.providers.dbt.dag import DbtDag
-from cosmos.providers.dbt.task_group import DbtTaskGroup
+from cosmos.dag import DbtDag
+from cosmos.task_group import DbtTaskGroup
 
 # re-export the operators
-from .core.operators.local import (
+from cosmos.operators.local import (
     DbtDepsLocalOperator,
     DbtLSLocalOperator,
     DbtRunLocalOperator,
     DbtRunOperationLocalOperator,
     DbtSeedLocalOperator,
     DbtSnapshotLocalOperator,
     DbtTestLocalOperator,
 )
 
 try:
-    from .core.operators.docker import (
+    from cosmos.operators.docker import (
         DbtLSDockerOperator,
         DbtRunDockerOperator,
         DbtRunOperationDockerOperator,
         DbtSeedDockerOperator,
         DbtSnapshotDockerOperator,
         DbtTestDockerOperator,
     )
 except ImportError:
-    from .core.operators.lazy_load import MissingPackage
+    from cosmos.operators.lazy_load import MissingPackage
 
-    DbtLSDockerOperator = MissingPackage("cosmos.providers.dbt.core.operators.docker.DbtLSDockerOperator", "docker")
-    DbtRunDockerOperator = MissingPackage("cosmos.providers.dbt.core.operators.docker.DbtRunDockerOperator", "docker")
+    DbtLSDockerOperator = MissingPackage("cosmos.operators.docker.DbtLSDockerOperator", "docker")
+    DbtRunDockerOperator = MissingPackage("cosmos.operators.docker.DbtRunDockerOperator", "docker")
     DbtRunOperationDockerOperator = MissingPackage(
-        "cosmos.providers.dbt.core.operators.docker.DbtRunOperationDockerOperator",
+        "cosmos.operators.docker.DbtRunOperationDockerOperator",
         "docker",
     )
-    DbtSeedDockerOperator = MissingPackage("cosmos.providers.dbt.core.operators.docker.DbtSeedDockerOperator", "docker")
-    DbtSnapshotDockerOperator = MissingPackage(
-        "cosmos.providers.dbt.core.operators.docker.DbtSnapshotDockerOperator", "docker"
-    )
-    DbtTestDockerOperator = MissingPackage("cosmos.providers.dbt.core.operators.docker.DbtTestDockerOperator", "docker")
+    DbtSeedDockerOperator = MissingPackage("cosmos.operators.docker.DbtSeedDockerOperator", "docker")
+    DbtSnapshotDockerOperator = MissingPackage("cosmos.operators.docker.DbtSnapshotDockerOperator", "docker")
+    DbtTestDockerOperator = MissingPackage("cosmos.operators.docker.DbtTestDockerOperator", "docker")
 
 try:
-    from .core.operators.kubernetes import (
+    from cosmos.operators.kubernetes import (
         DbtLSKubernetesOperator,
         DbtRunKubernetesOperator,
         DbtRunOperationKubernetesOperator,
         DbtSeedKubernetesOperator,
         DbtSnapshotKubernetesOperator,
         DbtTestKubernetesOperator,
     )
 except ImportError:
-    from .core.operators.lazy_load import MissingPackage
+    from cosmos.operators.lazy_load import MissingPackage
 
     DbtLSKubernetesOperator = MissingPackage(
-        "cosmos.providers.dbt.core.operators.kubernetes.DbtLSKubernetesOperator",
+        "cosmos.operators.kubernetes.DbtLSKubernetesOperator",
         "kubernetes",
     )
     DbtRunKubernetesOperator = MissingPackage(
-        "cosmos.providers.dbt.core.operators.kubernetes.DbtRunKubernetesOperator",
+        "cosmos.operators.kubernetes.DbtRunKubernetesOperator",
         "kubernetes",
     )
     DbtRunOperationKubernetesOperator = MissingPackage(
-        "cosmos.providers.dbt.core.operators.kubernetes.DbtRunOperationKubernetesOperator",
+        "cosmos.operators.kubernetes.DbtRunOperationKubernetesOperator",
         "kubernetes",
     )
     DbtSeedKubernetesOperator = MissingPackage(
-        "cosmos.providers.dbt.core.operators.kubernetes.DbtSeedKubernetesOperator",
+        "cosmos.operators.kubernetes.DbtSeedKubernetesOperator",
         "kubernetes",
     )
     DbtSnapshotKubernetesOperator = MissingPackage(
-        "cosmos.providers.dbt.core.operators.kubernetes.DbtSnapshotKubernetesOperator",
+        "cosmos.operators.kubernetes.DbtSnapshotKubernetesOperator",
         "kubernetes",
     )
     DbtTestKubernetesOperator = MissingPackage(
-        "cosmos.providers.dbt.core.operators.kubernetes.DbtTestKubernetesOperator",
+        "cosmos.operators.kubernetes.DbtTestKubernetesOperator",
         "kubernetes",
     )
 
 __all__ = [
     "DbtLSLocalOperator",
     "DbtRunOperationLocalOperator",
     "DbtRunLocalOperator",
```

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/dag.py` & `astronomer_cosmos-0.7.4/cosmos/dag.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/render.py` & `astronomer_cosmos-0.7.4/cosmos/render.py`

 * *Files 1% similar despite different names*

```diff
@@ -12,26 +12,26 @@
     from typing_extensions import Literal
 
 from typing import Any, Callable, Dict, List, Optional
 
 from airflow.exceptions import AirflowException
 
 from cosmos.core.graph.entities import CosmosEntity, Group, Task
-from cosmos.providers.dbt.core.utils.data_aware_scheduling import get_dbt_dataset
-from cosmos.providers.dbt.parser.project import DbtModelType, DbtProject
+from cosmos.dataset import get_dbt_dataset
+from cosmos.dbt.parser.project import DbtModelType, DbtProject
 
 logger = logging.getLogger(__name__)
 
 
 def calculate_operator_class(
     execution_mode: str,
     dbt_class: str,
 ) -> str:
     "Given an execution mode and dbt class, return the operator class to use"
-    return f"cosmos.providers.dbt.core.operators.{execution_mode}.{dbt_class}{execution_mode.capitalize()}Operator"
+    return f"cosmos.operators.{execution_mode}.{dbt_class}{execution_mode.capitalize()}Operator"
 
 
 def render_project(
     dbt_project_name: str,
     dbt_root_path: str = "/usr/local/airflow/dags/dbt",
     dbt_models_dir: str = "models",
     dbt_snapshots_dir: str = "snapshots",
```

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/task_group.py` & `astronomer_cosmos-0.7.4/cosmos/task_group.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/operators/__init__.py` & `astronomer_cosmos-0.7.4/cosmos/operators/__init__.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/operators/base.py` & `astronomer_cosmos-0.7.4/cosmos/operators/base.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from __future__ import annotations
 
 import logging
 import os
 import shutil
-from typing import Any, Dict, Sequence, Tuple
+from typing import Any, Sequence, Tuple
 
 import yaml
 from airflow.models.baseoperator import BaseOperator
 from airflow.utils.context import Context
 from airflow.utils.operator_helpers import context_to_airflow_vars
 
 logger = logging.getLogger(__name__)
@@ -48,15 +48,15 @@
     :param skip_exit_code: If task exits with this exit code, leave the task
         in ``skipped`` state (default: 99). If set to ``None``, any non-zero
         exit code will be treated as a failure.
     :param cancel_query_on_kill: If true, then cancel any running queries when the task's on_kill() is executed.
         Otherwise, the query will keep running when the task is killed.
     :param dbt_executable_path: Path to dbt executable can be used with venv
         (i.e. /home/astro/.pyenv/versions/dbt_venv/bin/dbt)
-    :param dbt_cmd_flags: Flags passed to dbt command override those that are calculated.
+    :param dbt_cmd_flags: List of flags to pass to dbt command
     """
 
     template_fields: Sequence[str] = ("env", "vars")
     global_flags = (
         "project_dir",
         "select",
         "exclude",
@@ -93,15 +93,15 @@
         schema: str = None,
         env: dict = None,
         append_env: bool = False,
         output_encoding: str = "utf-8",
         skip_exit_code: int = 99,
         cancel_query_on_kill: bool = True,
         dbt_executable_path: str = "dbt",
-        dbt_cmd_flags: Dict[str, Any] = {},
+        dbt_cmd_flags: list[str] = None,
         **kwargs,
     ) -> None:
         self.project_dir = project_dir
         self.conn_id = conn_id
         self.base_cmd = base_cmd
         self.select = select
         self.exclude = exclude
@@ -203,19 +203,26 @@
 
     def build_cmd(
         self,
         context: Context,
         cmd_flags: list[str] | None = None,
     ) -> Tuple[list[str], dict]:
         dbt_cmd = [self.dbt_executable_path]
+
         if isinstance(self.base_cmd, str):
             dbt_cmd.append(self.base_cmd)
         else:
             dbt_cmd.extend(self.base_cmd)
+
         dbt_cmd.extend(self.add_global_flags())
+
         # add command specific flags
         if cmd_flags:
             dbt_cmd.extend(cmd_flags)
 
+        # add user-supplied args
+        if self.dbt_cmd_flags:
+            dbt_cmd.extend(self.dbt_cmd_flags)
+
         env = self.get_env(context)
 
         return dbt_cmd, env
```

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/operators/docker.py` & `astronomer_cosmos-0.7.4/cosmos/operators/docker.py`

 * *Files 1% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 
 import logging
 from typing import Callable, Optional, Sequence
 
 import yaml
 from airflow.utils.context import Context
 
-from cosmos.providers.dbt.core.operators.base import DbtBaseOperator
+from cosmos.operators.base import DbtBaseOperator
 
 logger = logging.getLogger(__name__)
 
 # docker is an optional dependency, so we need to check if it's installed
 try:
     from airflow.providers.docker.operators.docker import DockerOperator
 except ImportError:
```

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/operators/kubernetes.py` & `astronomer_cosmos-0.7.4/cosmos/operators/kubernetes.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 
 import logging
 from typing import Callable, Optional, Sequence
 
 import yaml
 from airflow.utils.context import Context
 
-from cosmos.providers.dbt.core.operators.base import DbtBaseOperator
+from cosmos.operators.base import DbtBaseOperator
 
 logger = logging.getLogger(__name__)
 
 # kubernetes is an optional dependency, so we need to check if it's installed
 try:
     from airflow.providers.cncf.kubernetes.backcompat.backwards_compat_converters import (
         convert_env_vars,
```

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/operators/local.py` & `astronomer_cosmos-0.7.4/cosmos/operators/local.py`

 * *Files 2% similar despite different names*

```diff
@@ -11,22 +11,22 @@
 import yaml
 from airflow.compat.functools import cached_property
 from airflow.exceptions import AirflowException, AirflowSkipException
 from airflow.utils.context import Context
 from airflow.utils.session import NEW_SESSION, provide_session
 from sqlalchemy.orm import Session
 
-from cosmos.providers.dbt.constants import DEFAULT_DBT_PROFILE_NAME, DEFAULT_DBT_TARGET_NAME
-from cosmos.providers.dbt.core.operators.base import DbtBaseOperator
-from cosmos.providers.dbt.core.profiles import get_profile_mapping
-from cosmos.providers.dbt.core.utils.adapted_subprocesshook import (
+from cosmos.constants import DEFAULT_DBT_PROFILE_NAME, DEFAULT_DBT_TARGET_NAME
+from cosmos.operators.base import DbtBaseOperator
+from cosmos.profiles import get_profile_mapping
+from cosmos.hooks.subprocess import (
     FullOutputSubprocessHook,
     FullOutputSubprocessResult,
 )
-from cosmos.providers.dbt.core.utils.warn_parsing import (
+from cosmos.dbt.parser.output import (
     extract_log_issues,
     parse_output,
 )
 
 logger = logging.getLogger(__name__)
```

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/operators/virtualenv.py` & `astronomer_cosmos-0.7.4/cosmos/operators/virtualenv.py`

 * *Files 1% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 from tempfile import TemporaryDirectory
 from typing import TYPE_CHECKING
 
 
 from airflow.compat.functools import cached_property
 from airflow.utils.python_virtualenv import prepare_virtualenv
 
-from cosmos.providers.dbt.core.operators.local import (
+from cosmos.operators.local import (
     DbtDocsLocalOperator,
     DbtLocalBaseOperator,
     DbtLSLocalOperator,
     DbtRunLocalOperator,
     DbtRunOperationLocalOperator,
     DbtSeedLocalOperator,
     DbtSnapshotLocalOperator,
```

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/__init__.py` & `astronomer_cosmos-0.7.4/cosmos/profiles/__init__.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/base.py` & `astronomer_cosmos-0.7.4/cosmos/profiles/base.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/bigquery/service_account_file.py` & `astronomer_cosmos-0.7.4/cosmos/profiles/bigquery/service_account_file.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 "Maps Airflow GCP connections to dbt BigQuery profiles if they use a service account file."
 from __future__ import annotations
 
 from typing import Any
 
-from cosmos.providers.dbt.core.profiles.base import BaseProfileMapping
+from cosmos.profiles.base import BaseProfileMapping
 
 
 class GoogleCloudServiceAccountFileProfileMapping(BaseProfileMapping):
     """
     Maps Airflow GCP connections to dbt BigQuery profiles if they use a service account file.
 
     https://docs.getdbt.com/reference/warehouse-setups/bigquery-setup#service-account-file
```

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/databricks/token.py` & `astronomer_cosmos-0.7.4/cosmos/profiles/databricks/token.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/exasol/user_pass.py` & `astronomer_cosmos-0.7.4/cosmos/profiles/exasol/user_pass.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/postgres/user_pass.py` & `astronomer_cosmos-0.7.4/cosmos/profiles/postgres/user_pass.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/redshift/user_pass.py` & `astronomer_cosmos-0.7.4/cosmos/profiles/redshift/user_pass.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/snowflake/user_pass.py` & `astronomer_cosmos-0.7.4/cosmos/profiles/snowflake/user_pass.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/spark/thrift.py` & `astronomer_cosmos-0.7.4/cosmos/profiles/spark/thrift.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/trino/base.py` & `astronomer_cosmos-0.7.4/cosmos/profiles/trino/base.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/trino/certificate.py` & `astronomer_cosmos-0.7.4/cosmos/profiles/trino/certificate.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/trino/jwt.py` & `astronomer_cosmos-0.7.4/cosmos/profiles/trino/jwt.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/profiles/trino/ldap.py` & `astronomer_cosmos-0.7.4/cosmos/profiles/trino/ldap.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/utils/adapted_subprocesshook.py` & `astronomer_cosmos-0.7.4/cosmos/hooks/subprocess.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/core/utils/warn_parsing.py` & `astronomer_cosmos-0.7.4/cosmos/dbt/parser/output.py`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/cosmos/providers/dbt/parser/project.py` & `astronomer_cosmos-0.7.4/cosmos/dbt/parser/project.py`

 * *Files 0% similar despite different names*

```diff
@@ -128,15 +128,15 @@
         env = jinja2.Environment()
         ast = env.parse(code)
 
         # iterate over the jinja nodes to extract info
         for base_node in ast.find_all(jinja2.nodes.Call):
             if hasattr(base_node.node, "name"):
                 # check we have a ref - this indicates a dependency
-                if base_node.node.name == "ref" or base_node.node.name == "source":
+                if base_node.node.name == "ref":
                     # if it is, get the first argument
                     first_arg = base_node.args[0]
                     if isinstance(first_arg, jinja2.nodes.Const):
                         # and add it to the config
                         config.upstream_models.add(first_arg.value)
 
                 # check if we have a config - this could contain tags
```

### Comparing `astronomer_cosmos-0.7.3/.gitignore` & `astronomer_cosmos-0.7.4/.gitignore`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/LICENSE` & `astronomer_cosmos-0.7.4/LICENSE`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/README.rst` & `astronomer_cosmos-0.7.4/README.rst`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/pyproject.toml` & `astronomer_cosmos-0.7.4/pyproject.toml`

 * *Files identical despite different names*

### Comparing `astronomer_cosmos-0.7.3/PKG-INFO` & `astronomer_cosmos-0.7.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: astronomer-cosmos
-Version: 0.7.3
+Version: 0.7.4
 Summary: Render 3rd party workflows in Airflow
 Project-URL: Homepage, https://github.com/astronomer/astronomer-cosmos
 Project-URL: Documentation, https://github.com/astronomer/astronomer-cosmos
 Author-email: Astronomer <humans@astronomer.io>
 License-Expression: Apache-2.0
 License-File: LICENSE
 Keywords: airflow,apache-airflow,astronomer,dags,dbt
```


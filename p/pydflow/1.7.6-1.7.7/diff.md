# Comparing `tmp/pydflow-1.7.6.tar.gz` & `tmp/pydflow-1.7.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pydflow-1.7.6.tar", last modified: Tue Jun 27 03:22:11 2023, max compression
+gzip compressed data, was "pydflow-1.7.7.tar", last modified: Wed Jun 28 14:50:50 2023, max compression
```

## Comparing `pydflow-1.7.6.tar` & `pydflow-1.7.7.tar`

### file list

```diff
@@ -1,71 +1,71 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 03:22:11.742232 pydflow-1.7.6/
--rw-r--r--   0 runner    (1001) docker     (123)     7816 2023-06-27 03:21:58.000000 pydflow-1.7.6/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-27 03:21:58.000000 pydflow-1.7.6/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)    33145 2023-06-27 03:22:11.742232 pydflow-1.7.6/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    32758 2023-06-27 03:21:58.000000 pydflow-1.7.6/README.md
--rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-27 03:21:58.000000 pydflow-1.7.6/VERSION
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 03:22:11.742232 pydflow-1.7.6/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1170 2023-06-27 03:21:58.000000 pydflow-1.7.6/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 03:22:11.734232 pydflow-1.7.6/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 03:22:11.738232 pydflow-1.7.6/src/dflow/
--rw-r--r--   0 runner    (1001) docker     (123)     2824 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)       62 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    15398 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/argo_objects.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 03:22:11.738232 pydflow-1.7.6/src/dflow/client/
--rw-r--r--   0 runner    (1001) docker     (123)      386 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/client/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17690 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/client/v1alpha1_artifact.py
--rw-r--r--   0 runner    (1001) docker     (123)     8926 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/client/v1alpha1_parameter.py
--rw-r--r--   0 runner    (1001) docker     (123)     6122 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/client/v1alpha1_retry_strategy.py
--rw-r--r--   0 runner    (1001) docker     (123)     5861 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/client/v1alpha1_sequence.py
--rw-r--r--   0 runner    (1001) docker     (123)     9974 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/client/v1alpha1_value_from.py
--rw-r--r--   0 runner    (1001) docker     (123)     4546 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/common.py
--rw-r--r--   0 runner    (1001) docker     (123)     5740 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/config.py
--rw-r--r--   0 runner    (1001) docker     (123)      338 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/context.py
--rw-r--r--   0 runner    (1001) docker     (123)     3514 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/context_syntax.py
--rw-r--r--   0 runner    (1001) docker     (123)     5591 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/dag.py
--rw-r--r--   0 runner    (1001) docker     (123)    11261 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/executor.py
--rw-r--r--   0 runner    (1001) docker     (123)    51335 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/io.py
--rw-r--r--   0 runner    (1001) docker     (123)    13861 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/main.py
--rw-r--r--   0 runner    (1001) docker     (123)    23997 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/op_template.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 03:22:11.738232 pydflow-1.7.6/src/dflow/plugins/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/plugins/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14571 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/plugins/bohrium.py
--rw-r--r--   0 runner    (1001) docker     (123)     7570 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/plugins/datasets.py
--rw-r--r--   0 runner    (1001) docker     (123)    23061 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/plugins/dispatcher.py
--rw-r--r--   0 runner    (1001) docker     (123)     5411 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/plugins/launching.py
--rw-r--r--   0 runner    (1001) docker     (123)     6126 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/plugins/lebesgue.py
--rw-r--r--   0 runner    (1001) docker     (123)     3683 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/plugins/metadata.py
--rw-r--r--   0 runner    (1001) docker     (123)     3210 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/plugins/oss.py
--rw-r--r--   0 runner    (1001) docker     (123)     5482 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/plugins/ray.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 03:22:11.738232 pydflow-1.7.6/src/dflow/python/
--rw-r--r--   0 runner    (1001) docker     (123)      432 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/python/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8678 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/python/op.py
--rw-r--r--   0 runner    (1001) docker     (123)     6134 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/python/opio.py
--rw-r--r--   0 runner    (1001) docker     (123)    31751 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/python/python_op_template.py
--rw-r--r--   0 runner    (1001) docker     (123)    12148 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/python/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)      673 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/resource.py
--rw-r--r--   0 runner    (1001) docker     (123)    16413 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/slurm.py
--rw-r--r--   0 runner    (1001) docker     (123)   103446 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/step.py
--rw-r--r--   0 runner    (1001) docker     (123)     5763 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/steps.py
--rw-r--r--   0 runner    (1001) docker     (123)     3909 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/task.py
--rw-r--r--   0 runner    (1001) docker     (123)     8753 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/util_ops.py
--rw-r--r--   0 runner    (1001) docker     (123)    25735 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)    45198 2023-06-27 03:21:58.000000 pydflow-1.7.6/src/dflow/workflow.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 03:22:11.738232 pydflow-1.7.6/src/pydflow.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    33145 2023-06-27 03:22:11.000000 pydflow-1.7.6/src/pydflow.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1547 2023-06-27 03:22:11.000000 pydflow-1.7.6/src/pydflow.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 03:22:11.000000 pydflow-1.7.6/src/pydflow.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       42 2023-06-27 03:22:11.000000 pydflow-1.7.6/src/pydflow.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)      138 2023-06-27 03:22:11.000000 pydflow-1.7.6/src/pydflow.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       46 2023-06-27 03:22:11.000000 pydflow-1.7.6/src/pydflow.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 03:22:11.742232 pydflow-1.7.6/tests/
--rw-r--r--   0 runner    (1001) docker     (123)     2122 2023-06-27 03:21:58.000000 pydflow-1.7.6/tests/test_big_parameter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2254 2023-06-27 03:21:58.000000 pydflow-1.7.6/tests/test_conditional_outputs.py
--rw-r--r--   0 runner    (1001) docker     (123)     2442 2023-06-27 03:21:58.000000 pydflow-1.7.6/tests/test_dag.py
--rw-r--r--   0 runner    (1001) docker     (123)     2148 2023-06-27 03:21:58.000000 pydflow-1.7.6/tests/test_group_size.py
--rw-r--r--   0 runner    (1001) docker     (123)     8450 2023-06-27 03:21:58.000000 pydflow-1.7.6/tests/test_makevasp.py
--rw-r--r--   0 runner    (1001) docker     (123)     2573 2023-06-27 03:21:58.000000 pydflow-1.7.6/tests/test_python.py
--rw-r--r--   0 runner    (1001) docker     (123)     1839 2023-06-27 03:21:58.000000 pydflow-1.7.6/tests/test_recurse.py
--rw-r--r--   0 runner    (1001) docker     (123)     1926 2023-06-27 03:21:58.000000 pydflow-1.7.6/tests/test_reuse.py
--rw-r--r--   0 runner    (1001) docker     (123)     2162 2023-06-27 03:21:58.000000 pydflow-1.7.6/tests/test_slices.py
--rw-r--r--   0 runner    (1001) docker     (123)     2351 2023-06-27 03:21:58.000000 pydflow-1.7.6/tests/test_subpath_slices.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:50:50.314248 pydflow-1.7.7/
+-rw-r--r--   0 runner    (1001) docker     (123)     7816 2023-06-28 14:50:39.000000 pydflow-1.7.7/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-28 14:50:39.000000 pydflow-1.7.7/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)    33145 2023-06-28 14:50:50.310248 pydflow-1.7.7/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    32758 2023-06-28 14:50:39.000000 pydflow-1.7.7/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-28 14:50:39.000000 pydflow-1.7.7/VERSION
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 14:50:50.314248 pydflow-1.7.7/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1170 2023-06-28 14:50:39.000000 pydflow-1.7.7/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:50:50.302248 pydflow-1.7.7/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:50:50.306248 pydflow-1.7.7/src/dflow/
+-rw-r--r--   0 runner    (1001) docker     (123)     2824 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)       62 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15398 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/argo_objects.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:50:50.306248 pydflow-1.7.7/src/dflow/client/
+-rw-r--r--   0 runner    (1001) docker     (123)      386 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/client/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17690 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/client/v1alpha1_artifact.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8926 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/client/v1alpha1_parameter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6122 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/client/v1alpha1_retry_strategy.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5861 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/client/v1alpha1_sequence.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9974 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/client/v1alpha1_value_from.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4546 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/common.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5740 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/config.py
+-rw-r--r--   0 runner    (1001) docker     (123)      338 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/context.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3514 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/context_syntax.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5540 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/dag.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11261 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/executor.py
+-rw-r--r--   0 runner    (1001) docker     (123)    51335 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/io.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13861 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/main.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23997 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/op_template.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:50:50.310248 pydflow-1.7.7/src/dflow/plugins/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/plugins/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14571 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/plugins/bohrium.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7570 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/plugins/datasets.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23061 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/plugins/dispatcher.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5411 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/plugins/launching.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6126 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/plugins/lebesgue.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3683 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/plugins/metadata.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3210 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/plugins/oss.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5482 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/plugins/ray.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:50:50.310248 pydflow-1.7.7/src/dflow/python/
+-rw-r--r--   0 runner    (1001) docker     (123)      432 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/python/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8678 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/python/op.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6134 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/python/opio.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31750 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/python/python_op_template.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12408 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/python/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)      673 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16413 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/slurm.py
+-rw-r--r--   0 runner    (1001) docker     (123)   102485 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/step.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5712 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/steps.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3909 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/task.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8753 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/util_ops.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25540 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45198 2023-06-28 14:50:39.000000 pydflow-1.7.7/src/dflow/workflow.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:50:50.310248 pydflow-1.7.7/src/pydflow.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    33145 2023-06-28 14:50:50.000000 pydflow-1.7.7/src/pydflow.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1547 2023-06-28 14:50:50.000000 pydflow-1.7.7/src/pydflow.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:50:50.000000 pydflow-1.7.7/src/pydflow.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       42 2023-06-28 14:50:50.000000 pydflow-1.7.7/src/pydflow.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      138 2023-06-28 14:50:50.000000 pydflow-1.7.7/src/pydflow.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       46 2023-06-28 14:50:50.000000 pydflow-1.7.7/src/pydflow.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:50:50.310248 pydflow-1.7.7/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     2122 2023-06-28 14:50:39.000000 pydflow-1.7.7/tests/test_big_parameter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2254 2023-06-28 14:50:39.000000 pydflow-1.7.7/tests/test_conditional_outputs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2442 2023-06-28 14:50:39.000000 pydflow-1.7.7/tests/test_dag.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2148 2023-06-28 14:50:39.000000 pydflow-1.7.7/tests/test_group_size.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8450 2023-06-28 14:50:39.000000 pydflow-1.7.7/tests/test_makevasp.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2573 2023-06-28 14:50:39.000000 pydflow-1.7.7/tests/test_python.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1839 2023-06-28 14:50:39.000000 pydflow-1.7.7/tests/test_recurse.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1926 2023-06-28 14:50:39.000000 pydflow-1.7.7/tests/test_reuse.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2162 2023-06-28 14:50:39.000000 pydflow-1.7.7/tests/test_slices.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2351 2023-06-28 14:50:39.000000 pydflow-1.7.7/tests/test_subpath_slices.py
```

### Comparing `pydflow-1.7.6/LICENSE` & `pydflow-1.7.7/LICENSE`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/PKG-INFO` & `pydflow-1.7.7/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pydflow
-Version: 1.7.6
+Version: 1.7.7
 Summary: Dflow is a Python framework for constructing scientific computing workflows employing Argo Workflows as the workflow engine.
 Home-page: https://github.com/deepmodeling/dflow
 Author: Xinzijian Liu
 Author-email: liuxzj@dp.tech
 License: LGPLv3
 Requires-Python: >=3.6
 Description-Content-Type: text/markdown
```

### Comparing `pydflow-1.7.6/README.md` & `pydflow-1.7.7/README.md`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/setup.py` & `pydflow-1.7.7/setup.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/__init__.py` & `pydflow-1.7.7/src/dflow/__init__.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/argo_objects.py` & `pydflow-1.7.7/src/dflow/argo_objects.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/client/v1alpha1_artifact.py` & `pydflow-1.7.7/src/dflow/client/v1alpha1_artifact.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/client/v1alpha1_parameter.py` & `pydflow-1.7.7/src/dflow/client/v1alpha1_parameter.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/client/v1alpha1_retry_strategy.py` & `pydflow-1.7.7/src/dflow/client/v1alpha1_retry_strategy.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/client/v1alpha1_sequence.py` & `pydflow-1.7.7/src/dflow/client/v1alpha1_sequence.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/client/v1alpha1_value_from.py` & `pydflow-1.7.7/src/dflow/client/v1alpha1_value_from.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/common.py` & `pydflow-1.7.7/src/dflow/common.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/config.py` & `pydflow-1.7.7/src/dflow/config.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/context_syntax.py` & `pydflow-1.7.7/src/dflow/context_syntax.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/dag.py` & `pydflow-1.7.7/src/dflow/dag.py`

 * *Files 2% similar despite different names*

```diff
@@ -148,9 +148,9 @@
                 self.tasks[j].outputs = deepcopy(t.outputs)
             self.running.remove(self.tasks[j])
             self.finished.append(self.tasks[j])
             self.resolve()
 
         assert len(self.finished) == len(self.tasks), "cyclic graph"
 
-    def add_slices(self, slices, input_artifact_prefix=None):
-        add_slices(self, slices, input_artifact_prefix)
+    def add_slices(self, slices):
+        add_slices(self, slices)
```

### Comparing `pydflow-1.7.6/src/dflow/executor.py` & `pydflow-1.7.7/src/dflow/executor.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/io.py` & `pydflow-1.7.7/src/dflow/io.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/main.py` & `pydflow-1.7.7/src/dflow/main.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/op_template.py` & `pydflow-1.7.7/src/dflow/op_template.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/plugins/bohrium.py` & `pydflow-1.7.7/src/dflow/plugins/bohrium.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/plugins/datasets.py` & `pydflow-1.7.7/src/dflow/plugins/datasets.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/plugins/dispatcher.py` & `pydflow-1.7.7/src/dflow/plugins/dispatcher.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/plugins/launching.py` & `pydflow-1.7.7/src/dflow/plugins/launching.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/plugins/lebesgue.py` & `pydflow-1.7.7/src/dflow/plugins/lebesgue.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/plugins/metadata.py` & `pydflow-1.7.7/src/dflow/plugins/metadata.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/plugins/oss.py` & `pydflow-1.7.7/src/dflow/plugins/oss.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/plugins/ray.py` & `pydflow-1.7.7/src/dflow/plugins/ray.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/python/op.py` & `pydflow-1.7.7/src/dflow/python/op.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/python/opio.py` & `pydflow-1.7.7/src/dflow/python/opio.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/python/python_op_template.py` & `pydflow-1.7.7/src/dflow/python/python_op_template.py`

 * *Files 1% similar despite different names*

```diff
@@ -10,15 +10,15 @@
 
 from .. import __path__
 from ..common import S3Artifact
 from ..config import config
 from ..io import (PVC, InputArtifact, InputParameter, Inputs, OutputArtifact,
                   OutputParameter, Outputs)
 from ..op_template import PythonScriptOPTemplate
-from ..utils import add_prefix_to_slice, randstr, s3_config
+from ..utils import randstr, s3_config
 from .op import OP, iwd
 from .opio import Artifact, BigParameter, Parameter
 
 try:
     from argo.workflows.client import (V1alpha1UserContainer, V1Volume,
                                        V1VolumeMount)
 
@@ -57,14 +57,17 @@
             sub_path: bool = False,
             group_size: Optional[int] = None,
             shuffle: bool = False,
             random_seed: int = 0,
             pool_size: Optional[int] = None,
             register_first_only: bool = False,
     ) -> None:
+        if sub_path:
+            assert input_artifact is not None, \
+                "input artifact not provided in subpath mode"
         self.input_parameter = input_parameter if input_parameter is not \
             None else []
         self.input_artifact = input_artifact if input_artifact is not None \
             else []
         self.output_parameter = output_parameter if output_parameter is not \
             None else []
         self.output_artifact = output_artifact if output_artifact is not \
@@ -156,14 +159,15 @@
                  image: Optional[str] = None,
                  command: Union[str, List[str]] = None,
                  output_artifact_save: Dict[str,
                                             List[Union[PVC, S3Artifact]]]
                  = None,
                  output_artifact_archive: Dict[str, Optional[str]] = None,
                  output_parameter_default: Dict[str, Any] = None,
+                 input_artifact_prefix: Dict[str, str] = None,
                  input_artifact_slices: Dict[str, str] = None,
                  input_parameter_slices: Dict[str, str] = None,
                  output_artifact_slices: Dict[str, str] = None,
                  output_parameter_slices: Dict[str, str] = None,
                  output_artifact_global_name: Dict[str, str] = None,
                  output_parameter_global_name: Dict[str, str] = None,
                  slices: Optional[Slices] = None,
@@ -325,46 +329,42 @@
                                         op_class.progress_total)
         self.memoize_key = memoize_key
 
         self.op_class = op_class
         self.input_sign = input_sign
         self.output_sign = output_sign
         self.op = op
+        self.input_artifact_prefix = {} if input_artifact_prefix is None \
+            else input_artifact_prefix
         self.input_artifact_slices = {} if input_artifact_slices is None \
             else input_artifact_slices
         self.input_parameter_slices = {} if input_parameter_slices is None \
             else input_parameter_slices
         self.output_artifact_slices = {} if output_artifact_slices is None \
             else output_artifact_slices
         self.output_parameter_slices = {} if output_parameter_slices is None \
             else output_parameter_slices
         self.set_slices(slices)
         self.download_method = "download"
 
-    def set_slices(self, slices, input_artifact_prefix=None):
+    def set_slices(self, slices):
         self.slices = slices
         self.input_artifact_slices = {}
         self.input_parameter_slices = {}
         self.output_artifact_slices = {}
         self.output_parameter_slices = {}
         if slices is not None:
-            self.add_slices(slices, input_artifact_prefix)
+            self.add_slices(slices)
         else:
             self.render_script()
 
-    def add_slices(self, slices: Slices, input_artifact_prefix=None):
-        if input_artifact_prefix is None:
-            input_artifact_prefix = {}
+    def add_slices(self, slices: Slices):
         if slices.input_artifact and not slices.sub_path:
             for name in slices.input_artifact:
-                if name in input_artifact_prefix:
-                    self.input_artifact_slices[name] = add_prefix_to_slice(
-                        input_artifact_prefix[name], slices.slices)
-                else:
-                    self.input_artifact_slices[name] = slices.slices
+                self.input_artifact_slices[name] = slices.slices
         if slices.input_parameter:
             for name in slices.input_parameter:
                 self.input_parameter_slices[name] = slices.slices
         if slices.output_artifact:
             self.output_artifact_slices = {}
             for name in slices.output_artifact:
                 self.output_artifact_slices[name] = slices.slices
@@ -484,19 +484,20 @@
                         name in self.slices.input_artifact:
                     script += "    input['%s'] = handle_input_artifact('%s', "\
                         "input_sign['%s'], %s, r'%s', '{{inputs.parameters."\
                         "dflow_%s_sub_path}}', None)\n" % (
                             name, name, name, slices, self.tmp_root, name)
                 else:
                     script += "    input['%s'] = handle_input_artifact('%s', "\
-                        "input_sign['%s'], %s, r'%s', None, %s, "\
-                        "keys_of_parts=%s)\n" % (
+                        "input_sign['%s'], %s, r'%s', None, n_parts=%s, "\
+                        "keys_of_parts=%s, prefix=%s)\n" % (
                             name, name, name, slices, self.tmp_root,
                             self.n_parts.get(name, None),
-                            self.keys_of_parts.get(name, None))
+                            self.keys_of_parts.get(name, None),
+                            self.input_artifact_prefix.get(name, None))
             else:
                 slices = self.get_slices(input_parameter_slices, name)
                 if isinstance(sign, BigParameter) and \
                         config["mode"] != "debug":
                     script += "    input['%s'] = handle_input_parameter('%s',"\
                         " '', input_sign['%s'], %s, r'%s')\n" \
                         % (name, name, name, slices, self.tmp_root)
```

### Comparing `pydflow-1.7.6/src/dflow/python/utils.py` & `pydflow-1.7.7/src/dflow/python/utils.py`

 * *Files 4% similar despite different names*

```diff
@@ -38,30 +38,34 @@
             path_list = new_path_list
             path_dict = path_list
     return path_list, path_dict
 
 
 def handle_input_artifact(name, sign, slices=None, data_root="/tmp",
                           sub_path=None, n_parts=None, keys_of_parts=None,
-                          path=None):
+                          path=None, prefix=None):
+    def has_str(s):
+        return isinstance(s, str) or (
+            isinstance(s, list) and any(map(lambda x: isinstance(x, str), s)))
+
     require_dict = sign.type in [
         Dict[str, str], Dict[str, Path], NestedDict[str], NestedDict[Path]] \
-        or slices is not None
+        or has_str(prefix) or has_str(slices)
 
     if n_parts is not None:
         path_list = []
         path_dict = []
         for i in range(n_parts):
             art_path = '%s/inputs/artifacts/dflow_%s_%s' % (data_root, name, i)
             remove_empty_dir_tag(art_path)
             pl = assemble_path_list(art_path)
             if require_dict:
                 pd = assemble_path_nested_dict(art_path)
-                if slices is not None:
-                    pl, pd = get_slices(pl, pd, slices[i])
+                if prefix is not None:
+                    pl, pd = get_slices(pl, pd, prefix[i])
                 if isinstance(pd, list) and len(pd) == 1:
                     path_dict.append(pd[0])
                 else:
                     path_dict.append(pd)
             if pl:
                 path_list += pl
             else:
@@ -70,16 +74,16 @@
         path_list = []
         path_dict = {}
         for i in keys_of_parts:
             art_path = '%s/inputs/artifacts/dflow_%s_%s' % (data_root, name, i)
             remove_empty_dir_tag(art_path)
             pl = assemble_path_list(art_path)
             pd = assemble_path_nested_dict(art_path)
-            if slices is not None:
-                pl, pd = get_slices(pl, pd, slices[i])
+            if prefix is not None:
+                pl, pd = get_slices(pl, pd, prefix[i])
             if isinstance(pd, list) and len(pd) == 1:
                 path_dict[i] = pd[0]
             else:
                 path_dict[i] = pd
             if pl:
                 path_list += pl
             else:
@@ -90,17 +94,20 @@
             if path is None else path
         if sub_path is not None:
             art_path = os.path.join(art_path, sub_path)
         if not os.path.exists(art_path):  # for optional artifact
             return None
         remove_empty_dir_tag(art_path)
         path_list = assemble_path_list(art_path)
+        path_dict = {}
         if require_dict:
             path_dict = assemble_path_nested_dict(art_path)
-            path_list, path_dict = get_slices(path_list, path_dict, slices)
+            path_list, path_dict = get_slices(path_list, path_dict, prefix)
+
+    path_list, path_dict = get_slices(path_list, path_dict, slices)
 
     if sign.type == str:
         if len(path_list) == 1 and sign.sub_path:
             return path_list[0]
         else:
             return art_path
     elif sign.type == Path:
```

### Comparing `pydflow-1.7.6/src/dflow/resource.py` & `pydflow-1.7.7/src/dflow/resource.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/slurm.py` & `pydflow-1.7.7/src/dflow/slurm.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/step.py` & `pydflow-1.7.7/src/dflow/step.py`

 * *Files 0% similar despite different names*

```diff
@@ -17,16 +17,16 @@
 from .io import (PVC, ArgoVar, Expression, InputArtifact, InputParameter,
                  OutputArtifact, OutputParameter, if_expression, to_expr)
 from .op_template import (OPTemplate, PythonScriptOPTemplate, ScriptOPTemplate,
                           ShellOPTemplate)
 from .python import Slices
 from .resource import Resource
 from .util_ops import CheckNumSuccess, CheckSuccessRatio, InitArtifactForSlices
-from .utils import (add_prefix_to_slice, catalog_of_artifact, copy_file,
-                    flatten, merge_dir, randstr, upload_artifact)
+from .utils import (catalog_of_artifact, copy_file, flatten, merge_dir,
+                    randstr, upload_artifact)
 
 try:
     from argo.workflows.client import (V1alpha1Arguments, V1alpha1ContinueOn,
                                        V1alpha1ResourceTemplate,
                                        V1alpha1WorkflowStep, V1VolumeMount)
 
     from .client import V1alpha1Sequence
@@ -316,15 +316,14 @@
         self.outputs.set_step(self)
         self.continue_on_failed = continue_on_failed
         self.continue_on_error = continue_on_error
         self.continue_on_num_success = continue_on_num_success
         self.continue_on_success_ratio = continue_on_success_ratio
         self.check_step = None
         self.prepare_step = None
-        self.input_artifact_slices = {}
 
         if parameters is not None:
             self.set_parameters(parameters)
 
         if artifacts is not None:
             self.set_artifacts(artifacts)
 
@@ -360,25 +359,27 @@
         if self.key is not None:
             self.template.inputs.parameters["dflow_key"] = InputParameter(
                 value="")
             self.inputs.parameters["dflow_key"] = InputParameter(
                 value=str(self.key))
 
         if slices is not None:
+            from .dag import DAG
+            from .steps import Steps
+            assert isinstance(self.template, (DAG, Steps)), \
+                "Please specify slices in PythonOPTemplate "\
+                "if the template is a Python OP template"
             self.template = self.template.copy()
             self.template.slices = slices
             for name, par in self.template.inputs.parameters.items():
                 if name not in self.inputs.parameters:
                     self.inputs.parameters[name] = deepcopy(par)
-            self.template.add_slices(slices, self.input_artifact_slices)
-            from .dag import DAG
-            from .steps import Steps
-            if isinstance(self.template, (DAG, Steps)):
-                self.inputs.parameters["dflow_slice"] = InputParameter(
-                    value=slices.slices)
+            self.template.add_slices(slices)
+            self.inputs.parameters["dflow_slice"] = InputParameter(
+                value=slices.slices)
 
         sum_var = None
         if isinstance(self.with_param, ArgoRange) and \
                 isinstance(self.with_param.end, ArgoSum):
             sum_var = self.with_param.end.param
 
         if self.with_sequence is not None and \
@@ -431,16 +432,15 @@
                     "{{inputs.parameters.dflow_range_step}})"\
                     "[%s] for i in range({{item}}*%s, min(({{item}}+1)*%s"\
                     ", {{inputs.parameters.dflow_nslices}}))]" % (
                         old_slices.replace("{{item}}", "shuffled[i]"
                                            if self.template.slices.shuffle
                                            else "i"), group_size, group_size)
                 # re-render the script
-                self.template.set_slices(self.template.slices,
-                                         self.input_artifact_slices)
+                self.template.set_slices(self.template.slices)
                 self.with_param = argo_range(if_expression(
                     "%s %% %s > 0" % (nslices, group_size),
                     "%s/%s + 1" % (nslices, group_size),
                     "%s/%s" % (nslices, group_size)))
             elif self.with_param is not None:
                 self.template.inputs.parameters["dflow_with_param"] = \
                     InputParameter()
@@ -455,16 +455,15 @@
                     "[json.loads(r'''{{inputs.parameters.dflow_with_param}}"\
                     "''')[%s] for i in range({{item}}*%s, min(({{item}}+1)*%s"\
                     ", {{inputs.parameters.dflow_nslices}}))]" % (
                         old_slices.replace("{{item}}", "shuffled[i]"
                                            if self.template.slices.shuffle
                                            else "i"), group_size, group_size)
                 # re-render the script
-                self.template.set_slices(self.template.slices,
-                                         self.input_artifact_slices)
+                self.template.set_slices(self.template.slices)
                 self.with_param = argo_range(if_expression(
                     "%s %% %s > 0" % (nslices, group_size),
                     "%s/%s + 1" % (nslices, group_size),
                     "%s/%s" % (nslices, group_size)))
             if self.with_sequence is not None:
                 self.template.inputs.parameters["dflow_sequence_start"] = \
                     InputParameter()
@@ -509,16 +508,15 @@
                     % (old_slices.replace(
                         "'{{item}}'", "('%s' %% j)" % format)
                         if format is not None
                         else old_slices.replace("{{item}}", "j"),
                         "shuffled[i]" if self.template.slices.shuffle else "i",
                         group_size, group_size)
                 # re-render the script
-                self.template.set_slices(self.template.slices,
-                                         self.input_artifact_slices)
+                self.template.set_slices(self.template.slices)
                 self.with_sequence = argo_sequence(
                     count=if_expression(
                         "%s %% %s > 0" % (nslices, group_size),
                         "%s/%s + 1" % (nslices, group_size),
                         "%s/%s" % (nslices, group_size)), format=format)
 
             self.inputs.parameters["dflow_nslices"] = InputParameter(
@@ -1146,15 +1144,15 @@
                 else:
                     for i, a in enumerate(v):
                         vn = "dflow_%s_%s" % (k, i)
                         self.template.inputs.artifacts[vn].path = \
                             "%s/inputs/artifacts/%s" % (self.template.tmp_root,
                                                         vn)
                     if any(map(lambda x: x is not None, slices)):
-                        self.template.input_artifact_slices[k] = slices
+                        self.template.input_artifact_prefix[k] = slices
                     self.template.n_parts[k] = len(v)
                     self.template.render_script()
                 del self.template.inputs.artifacts[k]
                 del self.inputs.artifacts[k]
             elif isinstance(v, dict):
                 self.template = self.template.copy()
                 slices = {}
@@ -1186,23 +1184,22 @@
                 else:
                     for i, a in flat_v.items():
                         vn = "dflow_%s_%s" % (k, i)
                         self.template.inputs.artifacts[vn].path = \
                             "%s/inputs/artifacts/%s" % (self.template.tmp_root,
                                                         vn)
                     if any(map(lambda x: x is not None, slices.values())):
-                        self.template.input_artifact_slices[k] = slices
+                        self.template.input_artifact_prefix[k] = slices
                     self.template.keys_of_parts[k] = list(v.keys())
                     self.template.render_script()
                 del self.template.inputs.artifacts[k]
                 del self.inputs.artifacts[k]
             else:
                 self.inputs.artifacts[k].source = v
                 if hasattr(v, "slice") and v.slice is not None:
-                    self.input_artifact_slices[k] = v.slice
                     self.template = self.template.copy()
                     if isinstance(v.slice, (InputParameter, OutputParameter)):
                         self.template.inputs.parameters[
                             "dflow_%s" % v.slice.name] = InputParameter()
                         self.inputs.parameters["dflow_%s" % v.slice.name] = \
                             InputParameter(value=v.slice)
                         v.slice = "{{inputs.parameters.dflow_%s}}" % \
@@ -1223,22 +1220,16 @@
                                                            art.source.slice)
                                     else:
                                         slice = v.slice
                                     step.set_artifacts({
                                         name: self.template.inputs.artifacts[
                                             k][slice]})
                     else:
-                        if k in self.template.input_artifact_slices:
-                            old = self.template.input_artifact_slices[k]
-                            self.template.input_artifact_slices[k] = \
-                                add_prefix_to_slice(v.slice, old)
-                        else:
-                            self.template.input_artifact_slices[k] = v.slice \
-                                if isinstance(v.slice, int) \
-                                else "'%s'" % v.slice
+                        self.template.input_artifact_prefix[k] = v.slice \
+                            if isinstance(v.slice, int) else "'%s'" % v.slice
                         self.template.render_script()
                 if config["save_path_as_parameter"]:
                     if isinstance(v, S3Artifact) and v.path_list is not None:
                         try:
                             path_list = catalog_of_artifact(v)
                             if path_list:
                                 v.path_list = path_list
@@ -2118,17 +2109,15 @@
     expr = expr.replace("sprig.atoi", "int")
     expr = expr.replace(" ? ", " and ")
     expr = expr.replace(" : ", " or ")
     expr = expr.replace("asFloat", "float")
     return expr
 
 
-def add_slices(templ: OPTemplate, slices: Slices, input_artifact_prefix=None):
-    if input_artifact_prefix is None:
-        input_artifact_prefix = {}
+def add_slices(templ: OPTemplate, slices: Slices):
     templ.inputs.parameters["dflow_slice"] = InputParameter(
         value=slices.slices)
 
     steps = []
     for s in templ:
         if isinstance(s, list):
             steps += s
@@ -2154,20 +2143,15 @@
     for name in slices.input_artifact:
         for step in steps:
             for art in list(step.inputs.artifacts.values()):
                 # input artifact referring to sliced input artifact
                 if art.source is templ.inputs.artifacts[name] or getattr(
                     art.source, "parent", None) is \
                         templ.inputs.artifacts[name]:
-                    if name in input_artifact_prefix:
-                        slice = input_artifact_prefix[name]
-                        pattern = add_prefix_to_slice(
-                            slice, "{{inputs.parameters.dflow_slice}}")
-                    else:
-                        pattern = "{{inputs.parameters.dflow_slice}}"
+                    pattern = "{{inputs.parameters.dflow_slice}}"
                     step.template.inputs.parameters["dflow_slice"] = \
                         InputParameter()
                     step.template.add_slices(Slices(
                         pattern,
                         input_artifact=[art.name],
                         sub_path=slices.sub_path,
                         pool_size=slices.pool_size))
```

### Comparing `pydflow-1.7.6/src/dflow/steps.py` & `pydflow-1.7.7/src/dflow/steps.py`

 * *Files 2% similar despite different names*

```diff
@@ -144,9 +144,9 @@
                         if not step[j].continue_on_failed:
                             raise RuntimeError("Step %s failed" % step[j])
                     else:
                         step[j].outputs = deepcopy(ps.outputs)
             else:
                 step.run(self, context)
 
-    def add_slices(self, slices, input_artifact_prefix=None):
-        add_slices(self, slices, input_artifact_prefix)
+    def add_slices(self, slices):
+        add_slices(self, slices)
```

### Comparing `pydflow-1.7.6/src/dflow/task.py` & `pydflow-1.7.7/src/dflow/task.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/util_ops.py` & `pydflow-1.7.7/src/dflow/util_ops.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/dflow/utils.py` & `pydflow-1.7.7/src/dflow/utils.py`

 * *Files 3% similar despite different names*

```diff
@@ -783,13 +783,7 @@
     def copy(self, src: str, dst: str) -> None:
         self.client.copy_object(self.bucket_name, dst,
                                 CopySource(self.bucket_name, src))
 
     def get_md5(self, key: str) -> str:
         return self.client.stat_object(bucket_name=self.bucket_name,
                                        object_name=key).etag
-
-
-def add_prefix_to_slice(prefix, slices):
-    return "(lambda x: ['%s.' + str(i) for i in x] "\
-        "if isinstance(x, list) else '%s.' + str(x))(%s)" % (
-            prefix, prefix, slices)
```

### Comparing `pydflow-1.7.6/src/dflow/workflow.py` & `pydflow-1.7.7/src/dflow/workflow.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/src/pydflow.egg-info/PKG-INFO` & `pydflow-1.7.7/src/pydflow.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pydflow
-Version: 1.7.6
+Version: 1.7.7
 Summary: Dflow is a Python framework for constructing scientific computing workflows employing Argo Workflows as the workflow engine.
 Home-page: https://github.com/deepmodeling/dflow
 Author: Xinzijian Liu
 Author-email: liuxzj@dp.tech
 License: LGPLv3
 Requires-Python: >=3.6
 Description-Content-Type: text/markdown
```

### Comparing `pydflow-1.7.6/src/pydflow.egg-info/SOURCES.txt` & `pydflow-1.7.7/src/pydflow.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/tests/test_big_parameter.py` & `pydflow-1.7.7/tests/test_big_parameter.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/tests/test_conditional_outputs.py` & `pydflow-1.7.7/tests/test_conditional_outputs.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/tests/test_dag.py` & `pydflow-1.7.7/tests/test_dag.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/tests/test_group_size.py` & `pydflow-1.7.7/tests/test_group_size.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/tests/test_makevasp.py` & `pydflow-1.7.7/tests/test_makevasp.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/tests/test_python.py` & `pydflow-1.7.7/tests/test_python.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/tests/test_recurse.py` & `pydflow-1.7.7/tests/test_recurse.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/tests/test_reuse.py` & `pydflow-1.7.7/tests/test_reuse.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/tests/test_slices.py` & `pydflow-1.7.7/tests/test_slices.py`

 * *Files identical despite different names*

### Comparing `pydflow-1.7.6/tests/test_subpath_slices.py` & `pydflow-1.7.7/tests/test_subpath_slices.py`

 * *Files identical despite different names*


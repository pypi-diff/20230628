# Comparing `tmp/gordo-5.1.1.tar.gz` & `tmp/gordo-5.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "gordo-5.1.1.tar", last modified: Mon Jun  5 16:48:56 2023, max compression
+gzip compressed data, was "gordo-5.1.2.tar", last modified: Wed Jun 28 12:49:51 2023, max compression
```

## Comparing `gordo-5.1.1.tar` & `gordo-5.1.2.tar`

### file list

```diff
@@ -1,303 +1,303 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.134157 gordo-5.1.1/
--rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-05 16:46:43.000000 gordo-5.1.1/.dockerignore
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-05 16:46:43.000000 gordo-5.1.1/.gitattributes
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.114157 gordo-5.1.1/.github/
--rw-r--r--   0 runner    (1001) docker     (123)      127 2023-06-05 16:46:43.000000 gordo-5.1.1/.github/dependabot.yml 
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.114157 gordo-5.1.1/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)     1537 2023-06-05 16:46:43.000000 gordo-5.1.1/.github/workflows/main.yml
--rw-r--r--   0 runner    (1001) docker     (123)     2663 2023-06-05 16:46:43.000000 gordo-5.1.1/.github/workflows/master-ci.yml
--rw-r--r--   0 runner    (1001) docker     (123)      816 2023-06-05 16:46:43.000000 gordo-5.1.1/.github/workflows/release.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1255 2023-06-05 16:46:43.000000 gordo-5.1.1/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)      407 2023-06-05 16:46:43.000000 gordo-5.1.1/.readthedocs.yml
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/.trivyignore
--rw-r--r--   0 runner    (1001) docker     (123)     3157 2023-06-05 16:46:43.000000 gordo-5.1.1/Dockerfile
--rw-r--r--   0 runner    (1001) docker     (123)    34282 2023-06-05 16:46:43.000000 gordo-5.1.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     4105 2023-06-05 16:46:43.000000 gordo-5.1.1/Makefile
--rw-r--r--   0 runner    (1001) docker     (123)     4059 2023-06-05 16:48:56.134157 gordo-5.1.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     3406 2023-06-05 16:46:43.000000 gordo-5.1.1/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.114157 gordo-5.1.1/benchmarks/
--rw-r--r--   0 runner    (1001) docker     (123)      371 2023-06-05 16:46:43.000000 gordo-5.1.1/benchmarks/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.114157 gordo-5.1.1/benchmarks/load_test/
--rw-r--r--   0 runner    (1001) docker     (123)     1148 2023-06-05 16:46:43.000000 gordo-5.1.1/benchmarks/load_test/README.md
--rw-r--r--   0 runner    (1001) docker     (123)     2950 2023-06-05 16:46:43.000000 gordo-5.1.1/benchmarks/load_test/load_test.py
--rw-r--r--   0 runner    (1001) docker     (123)      368 2023-06-05 16:46:43.000000 gordo-5.1.1/benchmarks/load_test/task_set.py.jinja2
--rw-r--r--   0 runner    (1001) docker     (123)     1267 2023-06-05 16:46:43.000000 gordo-5.1.1/benchmarks/test_ml_server.py
--rw-r--r--   0 runner    (1001) docker     (123)      213 2023-06-05 16:46:43.000000 gordo-5.1.1/build.sh
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.114157 gordo-5.1.1/docs/
--rw-r--r--   0 runner    (1001) docker     (123)      834 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/Makefile
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.114157 gordo-5.1.1/docs/_static/
--rw-r--r--   0 runner    (1001) docker     (123)      191 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/_static/Gordo_C4.README
--rw-r--r--   0 runner    (1001) docker     (123)    46836 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/_static/Gordo_C4.svg
--rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/_static/_placeholder.txt
--rw-r--r--   0 runner    (1001) docker     (123)   113230 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/_static/architecture_diagram.png
--rw-r--r--   0 runner    (1001) docker     (123)     1329 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/_static/architecture_diagram.py
--rw-r--r--   0 runner    (1001) docker     (123)    19427 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/_static/argo_logo.png
--rw-r--r--   0 runner    (1001) docker     (123)   162857 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/_static/endpoint-metadata.png
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.118157 gordo-5.1.1/docs/api/
--rw-r--r--   0 runner    (1001) docker     (123)      570 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/builder.rst
--rw-r--r--   0 runner    (1001) docker     (123)      209 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/cli.rst
--rw-r--r--   0 runner    (1001) docker     (123)      193 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.118157 gordo-5.1.1/docs/api/machine/
--rw-r--r--   0 runner    (1001) docker     (123)      144 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/machine/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      109 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/machine/loader.rst
--rw-r--r--   0 runner    (1001) docker     (123)      445 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/machine/machine.rst
--rw-r--r--   0 runner    (1001) docker     (123)      641 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/machine/metadata.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.118157 gordo-5.1.1/docs/api/machine/model/
--rw-r--r--   0 runner    (1001) docker     (123)      725 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/machine/model/anomaly.rst
--rw-r--r--   0 runner    (1001) docker     (123)      190 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/machine/model/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      996 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/machine/model/model-factories.rst
--rw-r--r--   0 runner    (1001) docker     (123)      215 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/machine/model/model.rst
--rw-r--r--   0 runner    (1001) docker     (123)      120 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/machine/model/register.rst
--rw-r--r--   0 runner    (1001) docker     (123)      309 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/machine/model/transformer-funcs.rst
--rw-r--r--   0 runner    (1001) docker     (123)      348 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/machine/model/transformers.rst
--rw-r--r--   0 runner    (1001) docker     (123)      111 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/machine/model/utils.rst
--rw-r--r--   0 runner    (1001) docker     (123)      452 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/machine/validators.rst
--rw-r--r--   0 runner    (1001) docker     (123)      411 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/reporters.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1146 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/serializer.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.118157 gordo-5.1.1/docs/api/server/
--rw-r--r--   0 runner    (1001) docker     (123)      313 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/server/anomaly.rst
--rw-r--r--   0 runner    (1001) docker     (123)      282 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/server/base.rst
--rw-r--r--   0 runner    (1001) docker     (123)      153 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/server/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      347 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/server/prometheus.rst
--rw-r--r--   0 runner    (1001) docker     (123)      120 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/server/properties.rst
--rw-r--r--   0 runner    (1001) docker     (123)      111 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/server/server.rst
--rw-r--r--   0 runner    (1001) docker     (123)      266 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/server/utils.rst
--rw-r--r--   0 runner    (1001) docker     (123)      536 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/util.rst
--rw-r--r--   0 runner    (1001) docker     (123)      864 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/api/workflow.rst
--rw-r--r--   0 runner    (1001) docker     (123)     6121 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/conf.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.118157 gordo-5.1.1/docs/general/
--rw-r--r--   0 runner    (1001) docker     (123)      148 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/general/cli.rst
--rw-r--r--   0 runner    (1001) docker     (123)     8411 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/general/cluster_deployment.rst
--rw-r--r--   0 runner    (1001) docker     (123)    13035 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/general/endpoints.rst
--rw-r--r--   0 runner    (1001) docker     (123)      110 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/general/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      461 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.118157 gordo-5.1.1/docs/ml/
--rw-r--r--   0 runner    (1001) docker     (123)      118 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/ml/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1888 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/ml/model_configuration.rst
--rw-r--r--   0 runner    (1001) docker     (123)     3934 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/ml/model_output.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1690 2023-06-05 16:46:43.000000 gordo-5.1.1/docs/overview.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.118157 gordo-5.1.1/examples/
--rw-r--r--   0 runner    (1001) docker     (123)    19682 2023-06-05 16:46:43.000000 gordo-5.1.1/examples/Gordo-Workflow-High-Level.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)    10253 2023-06-05 16:46:43.000000 gordo-5.1.1/examples/Pipelines-with-Gordo.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)     3061 2023-06-05 16:46:43.000000 gordo-5.1.1/examples/config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      726 2023-06-05 16:46:43.000000 gordo-5.1.1/examples/model-configuration.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     1452 2023-06-05 16:46:43.000000 gordo-5.1.1/examples/test-project.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     1577 2023-06-05 16:46:43.000000 gordo-5.1.1/functions.sh
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.118157 gordo-5.1.1/gordo/
--rw-r--r--   0 runner    (1001) docker     (123)     2348 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      160 2023-06-05 16:48:55.000000 gordo-5.1.1/gordo/_version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.122157 gordo-5.1.1/gordo/builder/
--rw-r--r--   0 runner    (1001) docker     (123)       75 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/builder/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    26331 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/builder/build_model.py
--rw-r--r--   0 runner    (1001) docker     (123)     2386 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/builder/local_build.py
--rw-r--r--   0 runner    (1001) docker     (123)      557 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/builder/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.122157 gordo-5.1.1/gordo/cli/
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/cli/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11228 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/cli/cli.py
--rw-r--r--   0 runner    (1001) docker     (123)     1915 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/cli/custom_types.py
--rw-r--r--   0 runner    (1001) docker     (123)     7329 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/cli/exceptions_reporter.py
--rw-r--r--   0 runner    (1001) docker     (123)    20677 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/cli/workflow_generator.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.122157 gordo-5.1.1/gordo/machine/
--rw-r--r--   0 runner    (1001) docker     (123)      164 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)       97 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/constants.py
--rw-r--r--   0 runner    (1001) docker     (123)     1366 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/encoders.py
--rw-r--r--   0 runner    (1001) docker     (123)     2722 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/loader.py
--rw-r--r--   0 runner    (1001) docker     (123)     8679 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/machine.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.122157 gordo-5.1.1/gordo/machine/metadata/
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/metadata/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1496 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/metadata/metadata.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.122157 gordo-5.1.1/gordo/machine/model/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.122157 gordo-5.1.1/gordo/machine/model/anomaly/
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/anomaly/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      664 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/anomaly/base.py
--rw-r--r--   0 runner    (1001) docker     (123)    24402 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/anomaly/diff.py
--rw-r--r--   0 runner    (1001) docker     (123)      827 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/base.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.122157 gordo-5.1.1/gordo/machine/model/factories/
--rw-r--r--   0 runner    (1001) docker     (123)      115 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/factories/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8689 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/factories/feedforward_autoencoder.py
--rw-r--r--   0 runner    (1001) docker     (123)     9398 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/factories/lstm_autoencoder.py
--rw-r--r--   0 runner    (1001) docker     (123)     2350 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/factories/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)    25569 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/models.py
--rw-r--r--   0 runner    (1001) docker     (123)     2336 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/register.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.122157 gordo-5.1.1/gordo/machine/model/transformer_funcs/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/transformer_funcs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      784 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/transformer_funcs/general.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.122157 gordo-5.1.1/gordo/machine/model/transformers/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/transformers/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4765 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/transformers/imputer.py
--rw-r--r--   0 runner    (1001) docker     (123)     6033 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/model/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     9927 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/machine/validators.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.122157 gordo-5.1.1/gordo/reporters/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/reporters/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      888 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/reporters/base.py
--rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/reporters/exceptions.py
--rw-r--r--   0 runner    (1001) docker     (123)    15800 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/reporters/mlflow.py
--rw-r--r--   0 runner    (1001) docker     (123)     2970 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/reporters/postgres.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.122157 gordo-5.1.1/gordo/serializer/
--rw-r--r--   0 runner    (1001) docker     (123)      271 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/serializer/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12471 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/serializer/from_definition.py
--rw-r--r--   0 runner    (1001) docker     (123)     5804 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/serializer/into_definition.py
--rw-r--r--   0 runner    (1001) docker     (123)     5859 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/serializer/serializer.py
--rw-r--r--   0 runner    (1001) docker     (123)     1054 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/serializer/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.126157 gordo-5.1.1/gordo/server/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/server/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.126157 gordo-5.1.1/gordo/server/blueprints/
--rw-r--r--   0 runner    (1001) docker     (123)       72 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/server/blueprints/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4229 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/server/blueprints/anomaly.py
--rw-r--r--   0 runner    (1001) docker     (123)     7114 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/server/blueprints/base.py
--rw-r--r--   0 runner    (1001) docker     (123)      923 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/server/model_io.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.126157 gordo-5.1.1/gordo/server/prometheus/
--rw-r--r--   0 runner    (1001) docker     (123)      124 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/server/prometheus/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      124 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/server/prometheus/gunicorn_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     4793 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/server/prometheus/metrics.py
--rw-r--r--   0 runner    (1001) docker     (123)      636 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/server/prometheus/server.py
--rw-r--r--   0 runner    (1001) docker     (123)     2839 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/server/properties.py
--rw-r--r--   0 runner    (1001) docker     (123)    10227 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/server/server.py
--rw-r--r--   0 runner    (1001) docker     (123)    16553 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/server/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.126157 gordo-5.1.1/gordo/util/
--rw-r--r--   0 runner    (1001) docker     (123)      126 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/util/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3712 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/util/disk_registry.py
--rw-r--r--   0 runner    (1001) docker     (123)      179 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/util/text.py
--rw-r--r--   0 runner    (1001) docker     (123)     1352 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/util/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     3180 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/util/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     1984 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.126157 gordo-5.1.1/gordo/workflow/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/workflow/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.126157 gordo-5.1.1/gordo/workflow/config_elements/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/workflow/config_elements/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7367 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/workflow/config_elements/normalized_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     3507 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/workflow/config_elements/schemas.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.126157 gordo-5.1.1/gordo/workflow/workflow_generator/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/workflow/workflow_generator/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3034 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/workflow/workflow_generator/helpers.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.126157 gordo-5.1.1/gordo/workflow/workflow_generator/resources/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/workflow/workflow_generator/resources/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    70808 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/workflow/workflow_generator/resources/argo-workflow.yml.template
--rw-r--r--   0 runner    (1001) docker     (123)     4252 2023-06-05 16:46:43.000000 gordo-5.1.1/gordo/workflow/workflow_generator/workflow_generator.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.118157 gordo-5.1.1/gordo.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     4059 2023-06-05 16:48:55.000000 gordo-5.1.1/gordo.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     8772 2023-06-05 16:48:56.000000 gordo-5.1.1/gordo.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-05 16:48:55.000000 gordo-5.1.1/gordo.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       42 2023-06-05 16:48:55.000000 gordo-5.1.1/gordo.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)     2535 2023-06-05 16:48:55.000000 gordo-5.1.1/gordo.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-05 16:48:55.000000 gordo-5.1.1/gordo.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-05 16:48:55.000000 gordo-5.1.1/gordo.egg-info/zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)      151 2023-06-05 16:46:43.000000 gordo-5.1.1/mypy.ini
--rw-r--r--   0 runner    (1001) docker     (123)      586 2023-06-05 16:46:43.000000 gordo-5.1.1/pytest.ini
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.126157 gordo-5.1.1/requirements/
--rw-r--r--   0 runner    (1001) docker     (123)      105 2023-06-05 16:46:43.000000 gordo-5.1.1/requirements/docs_requirements.in
--rw-r--r--   0 runner    (1001) docker     (123)     9367 2023-06-05 16:46:43.000000 gordo-5.1.1/requirements/full_requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-05 16:46:43.000000 gordo-5.1.1/requirements/mlflow_requirements.in
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-05 16:46:43.000000 gordo-5.1.1/requirements/postgres_requirements.in
--rw-r--r--   0 runner    (1001) docker     (123)      291 2023-06-05 16:46:43.000000 gordo-5.1.1/requirements/requirements.in
--rw-r--r--   0 runner    (1001) docker     (123)      445 2023-06-05 16:46:43.000000 gordo-5.1.1/requirements/test_requirements.in
--rw-r--r--   0 runner    (1001) docker     (123)     7207 2023-06-05 16:46:43.000000 gordo-5.1.1/requirements/test_requirements.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.110157 gordo-5.1.1/resources/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.110157 gordo-5.1.1/resources/grafana/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.126157 gordo-5.1.1/resources/grafana/dashboards/
--rw-r--r--   0 runner    (1001) docker     (123)    26787 2023-06-05 16:46:43.000000 gordo-5.1.1/resources/grafana/dashboards/Gordo_servers-VictoriaMetrics.json
--rw-r--r--   0 runner    (1001) docker     (123)      249 2023-06-05 16:46:43.000000 gordo-5.1.1/resources/grafana/dashboards/how_to_modify_dashboard.md
--rw-r--r--   0 runner    (1001) docker     (123)    30418 2023-06-05 16:46:43.000000 gordo-5.1.1/resources/grafana/dashboards/machines.json
--rwxr-xr-x   0 runner    (1001) docker     (123)      774 2023-06-05 16:46:43.000000 gordo-5.1.1/run_workflow_and_argo.sh
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.126157 gordo-5.1.1/scripts/
--rw-r--r--   0 runner    (1001) docker     (123)     4811 2023-06-05 16:46:43.000000 gordo-5.1.1/scripts/download_argo.py
--rw-r--r--   0 runner    (1001) docker     (123)     7438 2023-06-05 16:46:43.000000 gordo-5.1.1/scripts/github_docker.py
--rw-r--r--   0 runner    (1001) docker     (123)     2516 2023-06-05 16:46:43.000000 gordo-5.1.1/scripts/tests.sh
--rw-r--r--   0 runner    (1001) docker     (123)      977 2023-06-05 16:46:43.000000 gordo-5.1.1/scripts/trivy_scan.sh
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-05 16:48:56.134157 gordo-5.1.1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2553 2023-06-05 16:46:43.000000 gordo-5.1.1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.126157 gordo-5.1.1/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      668 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/config-test.yaml
--rw-r--r--   0 runner    (1001) docker     (123)    13192 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/conftest.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.126157 gordo-5.1.1/tests/gordo/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.130157 gordo-5.1.1/tests/gordo/builder/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/builder/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    25155 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/builder/test_builder.py
--rw-r--r--   0 runner    (1001) docker     (123)     3705 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/builder/test_local_build.py
--rw-r--r--   0 runner    (1001) docker     (123)      679 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/builder/test_utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.130157 gordo-5.1.1/tests/gordo/cli/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/cli/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16399 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/cli/test_cli.py
--rw-r--r--   0 runner    (1001) docker     (123)     4647 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/cli/test_exception_reporter.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.130157 gordo-5.1.1/tests/gordo/client/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/client/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    15444 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/client/test_client.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.130157 gordo-5.1.1/tests/gordo/machine/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.130157 gordo-5.1.1/tests/gordo/machine/metadata/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/metadata/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      715 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/metadata/test_metadata.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.130157 gordo-5.1.1/tests/gordo/machine/model/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/model/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.130157 gordo-5.1.1/tests/gordo/machine/model/anomaly/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/model/anomaly/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    29275 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/model/anomaly/test_anomaly_detectors.py
--rw-r--r--   0 runner    (1001) docker     (123)     1022 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/model/test_factories_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     6493 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/model/test_feedforward_autoencoder.py
--rw-r--r--   0 runner    (1001) docker     (123)     6285 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/model/test_lstm_autoencoder.py
--rw-r--r--   0 runner    (1001) docker     (123)    13442 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/model/test_model.py
--rw-r--r--   0 runner    (1001) docker     (123)     2863 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/model/test_raw_keras.py
--rw-r--r--   0 runner    (1001) docker     (123)     1297 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/model/test_register.py
--rw-r--r--   0 runner    (1001) docker     (123)     6124 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/model/test_transformers.py
--rw-r--r--   0 runner    (1001) docker     (123)     3945 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/model/test_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     4897 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/test_descriptors.py
--rw-r--r--   0 runner    (1001) docker     (123)     5634 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/test_loader.py
--rw-r--r--   0 runner    (1001) docker     (123)     1812 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/machine/test_machine.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.130157 gordo-5.1.1/tests/gordo/reporters/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/reporters/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9936 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/reporters/test_mlflow_reporter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2143 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/reporters/test_postgres_reporter.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.130157 gordo-5.1.1/tests/gordo/serializer/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/serializer/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      273 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/serializer/definition_test_model.py
--rw-r--r--   0 runner    (1001) docker     (123)    11792 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/serializer/test_serializer_from_definition.py
--rw-r--r--   0 runner    (1001) docker     (123)    11387 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/serializer/test_serializer_into_definition.py
--rw-r--r--   0 runner    (1001) docker     (123)     4431 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/serializer/test_serializer_load_dump.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.130157 gordo-5.1.1/tests/gordo/server/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/server/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3940 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/server/test_anomaly_blueprint.py
--rw-r--r--   0 runner    (1001) docker     (123)     3404 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/server/test_base_blueprint.py
--rw-r--r--   0 runner    (1001) docker     (123)    17791 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/server/test_gordo_server.py
--rw-r--r--   0 runner    (1001) docker     (123)     1065 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/server/test_model_io.py
--rw-r--r--   0 runner    (1001) docker     (123)     3820 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/server/test_prometheus.py
--rw-r--r--   0 runner    (1001) docker     (123)     5096 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/server/test_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)      778 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/test_version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.134157 gordo-5.1.1/tests/gordo/util/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/util/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2280 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/util/test_disk_registry.py
--rw-r--r--   0 runner    (1001) docker     (123)        2 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/util/test_sensor_tag.py
--rw-r--r--   0 runner    (1001) docker     (123)     1312 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/util/test_version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.134157 gordo-5.1.1/tests/gordo/workflow/
--rw-r--r--   0 runner    (1001) docker     (123)     8311 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_config_elements.py
--rw-r--r--   0 runner    (1001) docker     (123)     1494 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_helpers.py
--rw-r--r--   0 runner    (1001) docker     (123)     2088 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_normalized_config.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.134157 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-05 16:48:56.134157 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/
--rw-r--r--   0 runner    (1001) docker     (123)      406 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-empty-default-data-provider.yml
--rw-r--r--   0 runner    (1001) docker     (123)      982 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-allowed-timestamps.yml
--rw-r--r--   0 runner    (1001) docker     (123)      958 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-datasource.yml
--rw-r--r--   0 runner    (1001) docker     (123)      782 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-disable-influx.yml
--rw-r--r--   0 runner    (1001) docker     (123)      750 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-empty-tag-list.yml
--rw-r--r--   0 runner    (1001) docker     (123)      620 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-failing-resource-format.yml
--rw-r--r--   0 runner    (1001) docker     (123)      239 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-missing-timezone-quoted.yml
--rw-r--r--   0 runner    (1001) docker     (123)      235 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-missing-timezone.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1012 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-model-builder-spec.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      864 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-quotes.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1718 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-runtime-images.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      744 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-runtime-labels.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     1575 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-runtime-resource.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      836 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-selective-influx.yml
--rw-r--r--   0 runner    (1001) docker     (123)      460 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-simple.yml
--rw-r--r--   0 runner    (1001) docker     (123)      695 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-timestamp-1.yml
--rw-r--r--   0 runner    (1001) docker     (123)      693 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-timestamp-2.yml
--rw-r--r--   0 runner    (1001) docker     (123)      693 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-timestamp-3.yml
--rw-r--r--   0 runner    (1001) docker     (123)      914 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-with-log-key.yml
--rw-r--r--   0 runner    (1001) docker     (123)      808 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-with-models.yml
--rw-r--r--   0 runner    (1001) docker     (123)    28554 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/test_workflow_generator.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/mocs.py
--rw-r--r--   0 runner    (1001) docker     (123)     1259 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/test_examples.py
--rw-r--r--   0 runner    (1001) docker     (123)      507 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/test_formatting.py
--rw-r--r--   0 runner    (1001) docker     (123)     3733 2023-06-05 16:46:43.000000 gordo-5.1.1/tests/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.655880 gordo-5.1.2/
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 12:47:36.000000 gordo-5.1.2/.dockerignore
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 12:47:36.000000 gordo-5.1.2/.gitattributes
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.631880 gordo-5.1.2/.github/
+-rw-r--r--   0 runner    (1001) docker     (123)      127 2023-06-28 12:47:36.000000 gordo-5.1.2/.github/dependabot.yml 
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.631880 gordo-5.1.2/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     1537 2023-06-28 12:47:36.000000 gordo-5.1.2/.github/workflows/main.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     2663 2023-06-28 12:47:36.000000 gordo-5.1.2/.github/workflows/master-ci.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      816 2023-06-28 12:47:36.000000 gordo-5.1.2/.github/workflows/release.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1255 2023-06-28 12:47:36.000000 gordo-5.1.2/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)      407 2023-06-28 12:47:36.000000 gordo-5.1.2/.readthedocs.yml
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/.trivyignore
+-rw-r--r--   0 runner    (1001) docker     (123)     3157 2023-06-28 12:47:36.000000 gordo-5.1.2/Dockerfile
+-rw-r--r--   0 runner    (1001) docker     (123)    34282 2023-06-28 12:47:36.000000 gordo-5.1.2/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     4105 2023-06-28 12:47:36.000000 gordo-5.1.2/Makefile
+-rw-r--r--   0 runner    (1001) docker     (123)     4064 2023-06-28 12:49:51.655880 gordo-5.1.2/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3412 2023-06-28 12:47:36.000000 gordo-5.1.2/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.631880 gordo-5.1.2/benchmarks/
+-rw-r--r--   0 runner    (1001) docker     (123)      371 2023-06-28 12:47:36.000000 gordo-5.1.2/benchmarks/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.635880 gordo-5.1.2/benchmarks/load_test/
+-rw-r--r--   0 runner    (1001) docker     (123)     1148 2023-06-28 12:47:36.000000 gordo-5.1.2/benchmarks/load_test/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)     2950 2023-06-28 12:47:36.000000 gordo-5.1.2/benchmarks/load_test/load_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)      368 2023-06-28 12:47:36.000000 gordo-5.1.2/benchmarks/load_test/task_set.py.jinja2
+-rw-r--r--   0 runner    (1001) docker     (123)     1267 2023-06-28 12:47:36.000000 gordo-5.1.2/benchmarks/test_ml_server.py
+-rw-r--r--   0 runner    (1001) docker     (123)      213 2023-06-28 12:47:36.000000 gordo-5.1.2/build.sh
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.635880 gordo-5.1.2/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)      834 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/Makefile
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.635880 gordo-5.1.2/docs/_static/
+-rw-r--r--   0 runner    (1001) docker     (123)      191 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/_static/Gordo_C4.README
+-rw-r--r--   0 runner    (1001) docker     (123)    46836 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/_static/Gordo_C4.svg
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/_static/_placeholder.txt
+-rw-r--r--   0 runner    (1001) docker     (123)   113230 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/_static/architecture_diagram.png
+-rw-r--r--   0 runner    (1001) docker     (123)     1329 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/_static/architecture_diagram.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19427 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/_static/argo_logo.png
+-rw-r--r--   0 runner    (1001) docker     (123)   162857 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/_static/endpoint-metadata.png
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.635880 gordo-5.1.2/docs/api/
+-rw-r--r--   0 runner    (1001) docker     (123)      570 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/builder.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      559 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/cli.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      193 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.635880 gordo-5.1.2/docs/api/machine/
+-rw-r--r--   0 runner    (1001) docker     (123)      144 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/machine/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      109 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/machine/loader.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      445 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/machine/machine.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      641 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/machine/metadata.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.635880 gordo-5.1.2/docs/api/machine/model/
+-rw-r--r--   0 runner    (1001) docker     (123)      725 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/machine/model/anomaly.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      190 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/machine/model/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      996 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/machine/model/model-factories.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      215 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/machine/model/model.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      120 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/machine/model/register.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      307 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/machine/model/transformer-funcs.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      348 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/machine/model/transformers.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      111 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/machine/model/utils.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      452 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/machine/validators.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      411 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/reporters.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1146 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/serializer.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.635880 gordo-5.1.2/docs/api/server/
+-rw-r--r--   0 runner    (1001) docker     (123)      313 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/server/anomaly.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      282 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/server/base.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      153 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/server/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      347 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/server/prometheus.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      120 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/server/properties.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      111 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/server/server.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      266 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/server/utils.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      536 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/util.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      864 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/api/workflow.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     6281 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/conf.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.639880 gordo-5.1.2/docs/general/
+-rw-r--r--   0 runner    (1001) docker     (123)      148 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/general/cli.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     8411 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/general/cluster_deployment.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    13449 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/general/endpoints.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      110 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/general/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      461 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.639880 gordo-5.1.2/docs/ml/
+-rw-r--r--   0 runner    (1001) docker     (123)      118 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/ml/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     3623 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/ml/model_configuration.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     4587 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/ml/model_output.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1676 2023-06-28 12:47:36.000000 gordo-5.1.2/docs/overview.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.639880 gordo-5.1.2/examples/
+-rw-r--r--   0 runner    (1001) docker     (123)    42032 2023-06-28 12:47:36.000000 gordo-5.1.2/examples/Gordo-Workflow-High-Level.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)    10253 2023-06-28 12:47:36.000000 gordo-5.1.2/examples/Pipelines-with-Gordo.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)     3061 2023-06-28 12:47:36.000000 gordo-5.1.2/examples/config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      726 2023-06-28 12:47:36.000000 gordo-5.1.2/examples/model-configuration.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     1452 2023-06-28 12:47:36.000000 gordo-5.1.2/examples/test-project.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     1577 2023-06-28 12:47:36.000000 gordo-5.1.2/functions.sh
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.639880 gordo-5.1.2/gordo/
+-rw-r--r--   0 runner    (1001) docker     (123)     2348 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      160 2023-06-28 12:49:51.000000 gordo-5.1.2/gordo/_version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.639880 gordo-5.1.2/gordo/builder/
+-rw-r--r--   0 runner    (1001) docker     (123)       75 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/builder/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26331 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/builder/build_model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2386 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/builder/local_build.py
+-rw-r--r--   0 runner    (1001) docker     (123)      557 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/builder/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.639880 gordo-5.1.2/gordo/cli/
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/cli/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11203 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/cli/cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1915 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/cli/custom_types.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7329 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/cli/exceptions_reporter.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20677 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/cli/workflow_generator.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.639880 gordo-5.1.2/gordo/machine/
+-rw-r--r--   0 runner    (1001) docker     (123)      164 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)       97 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1366 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/encoders.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2722 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/loader.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8679 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/machine.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.639880 gordo-5.1.2/gordo/machine/metadata/
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/metadata/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1496 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/metadata/metadata.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.643880 gordo-5.1.2/gordo/machine/model/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.643880 gordo-5.1.2/gordo/machine/model/anomaly/
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/anomaly/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      664 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/anomaly/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24402 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/anomaly/diff.py
+-rw-r--r--   0 runner    (1001) docker     (123)      827 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/base.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.643880 gordo-5.1.2/gordo/machine/model/factories/
+-rw-r--r--   0 runner    (1001) docker     (123)      115 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/factories/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8689 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/factories/feedforward_autoencoder.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9398 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/factories/lstm_autoencoder.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2350 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/factories/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25569 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/models.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2337 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/register.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.643880 gordo-5.1.2/gordo/machine/model/transformer_funcs/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/transformer_funcs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      784 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/transformer_funcs/general.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.643880 gordo-5.1.2/gordo/machine/model/transformers/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/transformers/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4765 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/transformers/imputer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6033 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/model/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9927 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/machine/validators.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.643880 gordo-5.1.2/gordo/reporters/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/reporters/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      888 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/reporters/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/reporters/exceptions.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15808 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/reporters/mlflow.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2970 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/reporters/postgres.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.643880 gordo-5.1.2/gordo/serializer/
+-rw-r--r--   0 runner    (1001) docker     (123)      271 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/serializer/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12471 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/serializer/from_definition.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5804 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/serializer/into_definition.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5859 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/serializer/serializer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1054 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/serializer/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.643880 gordo-5.1.2/gordo/server/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/server/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.643880 gordo-5.1.2/gordo/server/blueprints/
+-rw-r--r--   0 runner    (1001) docker     (123)       72 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/server/blueprints/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4229 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/server/blueprints/anomaly.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7114 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/server/blueprints/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)      923 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/server/model_io.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.643880 gordo-5.1.2/gordo/server/prometheus/
+-rw-r--r--   0 runner    (1001) docker     (123)      124 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/server/prometheus/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      124 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/server/prometheus/gunicorn_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4793 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/server/prometheus/metrics.py
+-rw-r--r--   0 runner    (1001) docker     (123)      636 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/server/prometheus/server.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2888 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/server/properties.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10227 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/server/server.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16553 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/server/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.643880 gordo-5.1.2/gordo/util/
+-rw-r--r--   0 runner    (1001) docker     (123)      126 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/util/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3712 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/util/disk_registry.py
+-rw-r--r--   0 runner    (1001) docker     (123)      179 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/util/text.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1352 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/util/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3180 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/util/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1984 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.643880 gordo-5.1.2/gordo/workflow/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/workflow/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.647880 gordo-5.1.2/gordo/workflow/config_elements/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/workflow/config_elements/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7367 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/workflow/config_elements/normalized_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3507 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/workflow/config_elements/schemas.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.647880 gordo-5.1.2/gordo/workflow/workflow_generator/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/workflow/workflow_generator/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3034 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/workflow/workflow_generator/helpers.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.647880 gordo-5.1.2/gordo/workflow/workflow_generator/resources/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/workflow/workflow_generator/resources/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    70808 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/workflow/workflow_generator/resources/argo-workflow.yml.template
+-rw-r--r--   0 runner    (1001) docker     (123)     4252 2023-06-28 12:47:36.000000 gordo-5.1.2/gordo/workflow/workflow_generator/workflow_generator.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.639880 gordo-5.1.2/gordo.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     4064 2023-06-28 12:49:51.000000 gordo-5.1.2/gordo.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     8772 2023-06-28 12:49:51.000000 gordo-5.1.2/gordo.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:49:51.000000 gordo-5.1.2/gordo.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       42 2023-06-28 12:49:51.000000 gordo-5.1.2/gordo.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     2549 2023-06-28 12:49:51.000000 gordo-5.1.2/gordo.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-28 12:49:51.000000 gordo-5.1.2/gordo.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:49:51.000000 gordo-5.1.2/gordo.egg-info/zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      151 2023-06-28 12:47:36.000000 gordo-5.1.2/mypy.ini
+-rw-r--r--   0 runner    (1001) docker     (123)      586 2023-06-28 12:47:36.000000 gordo-5.1.2/pytest.ini
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.647880 gordo-5.1.2/requirements/
+-rw-r--r--   0 runner    (1001) docker     (123)      119 2023-06-28 12:47:36.000000 gordo-5.1.2/requirements/docs_requirements.in
+-rw-r--r--   0 runner    (1001) docker     (123)     9256 2023-06-28 12:47:36.000000 gordo-5.1.2/requirements/full_requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 12:47:36.000000 gordo-5.1.2/requirements/mlflow_requirements.in
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 12:47:36.000000 gordo-5.1.2/requirements/postgres_requirements.in
+-rw-r--r--   0 runner    (1001) docker     (123)      291 2023-06-28 12:47:36.000000 gordo-5.1.2/requirements/requirements.in
+-rw-r--r--   0 runner    (1001) docker     (123)      445 2023-06-28 12:47:36.000000 gordo-5.1.2/requirements/test_requirements.in
+-rw-r--r--   0 runner    (1001) docker     (123)     7207 2023-06-28 12:47:36.000000 gordo-5.1.2/requirements/test_requirements.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.631880 gordo-5.1.2/resources/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.631880 gordo-5.1.2/resources/grafana/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.647880 gordo-5.1.2/resources/grafana/dashboards/
+-rw-r--r--   0 runner    (1001) docker     (123)    26787 2023-06-28 12:47:36.000000 gordo-5.1.2/resources/grafana/dashboards/Gordo_servers-VictoriaMetrics.json
+-rw-r--r--   0 runner    (1001) docker     (123)      249 2023-06-28 12:47:36.000000 gordo-5.1.2/resources/grafana/dashboards/how_to_modify_dashboard.md
+-rw-r--r--   0 runner    (1001) docker     (123)    30418 2023-06-28 12:47:36.000000 gordo-5.1.2/resources/grafana/dashboards/machines.json
+-rwxr-xr-x   0 runner    (1001) docker     (123)      774 2023-06-28 12:47:36.000000 gordo-5.1.2/run_workflow_and_argo.sh
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.647880 gordo-5.1.2/scripts/
+-rw-r--r--   0 runner    (1001) docker     (123)     4811 2023-06-28 12:47:36.000000 gordo-5.1.2/scripts/download_argo.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7438 2023-06-28 12:47:36.000000 gordo-5.1.2/scripts/github_docker.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2516 2023-06-28 12:47:36.000000 gordo-5.1.2/scripts/tests.sh
+-rw-r--r--   0 runner    (1001) docker     (123)      977 2023-06-28 12:47:36.000000 gordo-5.1.2/scripts/trivy_scan.sh
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 12:49:51.655880 gordo-5.1.2/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2553 2023-06-28 12:47:36.000000 gordo-5.1.2/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.647880 gordo-5.1.2/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      668 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/config-test.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)    13192 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/conftest.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.647880 gordo-5.1.2/tests/gordo/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.647880 gordo-5.1.2/tests/gordo/builder/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/builder/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25155 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/builder/test_builder.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3705 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/builder/test_local_build.py
+-rw-r--r--   0 runner    (1001) docker     (123)      679 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/builder/test_utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.647880 gordo-5.1.2/tests/gordo/cli/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/cli/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16399 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/cli/test_cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4647 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/cli/test_exception_reporter.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.647880 gordo-5.1.2/tests/gordo/client/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/client/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15444 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/client/test_client.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.651880 gordo-5.1.2/tests/gordo/machine/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.651880 gordo-5.1.2/tests/gordo/machine/metadata/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/metadata/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      715 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/metadata/test_metadata.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.651880 gordo-5.1.2/tests/gordo/machine/model/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/model/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.651880 gordo-5.1.2/tests/gordo/machine/model/anomaly/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/model/anomaly/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29275 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/model/anomaly/test_anomaly_detectors.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1022 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/model/test_factories_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6493 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/model/test_feedforward_autoencoder.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6285 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/model/test_lstm_autoencoder.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13442 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/model/test_model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2863 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/model/test_raw_keras.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1297 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/model/test_register.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6124 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/model/test_transformers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3945 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/model/test_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4897 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/test_descriptors.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5634 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/test_loader.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1812 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/machine/test_machine.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.651880 gordo-5.1.2/tests/gordo/reporters/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/reporters/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9936 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/reporters/test_mlflow_reporter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2143 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/reporters/test_postgres_reporter.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.651880 gordo-5.1.2/tests/gordo/serializer/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/serializer/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      273 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/serializer/definition_test_model.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11792 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/serializer/test_serializer_from_definition.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11387 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/serializer/test_serializer_into_definition.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4431 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/serializer/test_serializer_load_dump.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.651880 gordo-5.1.2/tests/gordo/server/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/server/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3940 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/server/test_anomaly_blueprint.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3404 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/server/test_base_blueprint.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17791 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/server/test_gordo_server.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1065 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/server/test_model_io.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3820 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/server/test_prometheus.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5096 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/server/test_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)      778 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/test_version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.651880 gordo-5.1.2/tests/gordo/util/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/util/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2280 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/util/test_disk_registry.py
+-rw-r--r--   0 runner    (1001) docker     (123)        2 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/util/test_sensor_tag.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1312 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/util/test_version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.651880 gordo-5.1.2/tests/gordo/workflow/
+-rw-r--r--   0 runner    (1001) docker     (123)     8311 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_config_elements.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1494 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_helpers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2088 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_normalized_config.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.651880 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:49:51.655880 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/
+-rw-r--r--   0 runner    (1001) docker     (123)      406 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-empty-default-data-provider.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      982 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-allowed-timestamps.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      958 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-datasource.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      782 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-disable-influx.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      750 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-empty-tag-list.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      620 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-failing-resource-format.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      239 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-missing-timezone-quoted.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      235 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-missing-timezone.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1012 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-model-builder-spec.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      864 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-quotes.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1718 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-runtime-images.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      744 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-runtime-labels.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     1575 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-runtime-resource.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      836 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-selective-influx.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      460 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-simple.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      695 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-timestamp-1.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      693 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-timestamp-2.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      693 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-timestamp-3.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      914 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-with-log-key.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      808 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-with-models.yml
+-rw-r--r--   0 runner    (1001) docker     (123)    28554 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/test_workflow_generator.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/mocs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1259 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/test_examples.py
+-rw-r--r--   0 runner    (1001) docker     (123)      507 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/test_formatting.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3733 2023-06-28 12:47:36.000000 gordo-5.1.2/tests/utils.py
```

### Comparing `gordo-5.1.1/.github/workflows/main.yml` & `gordo-5.1.2/.github/workflows/main.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/.github/workflows/master-ci.yml` & `gordo-5.1.2/.github/workflows/master-ci.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/.github/workflows/release.yml` & `gordo-5.1.2/.github/workflows/release.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/.gitignore` & `gordo-5.1.2/.gitignore`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/Dockerfile` & `gordo-5.1.2/Dockerfile`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/LICENSE` & `gordo-5.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/Makefile` & `gordo-5.1.2/Makefile`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/PKG-INFO` & `gordo-5.1.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: gordo
-Version: 5.1.1
+Version: 5.1.2
 Summary: Train and build models for Argo / Kubernetes
 Home-page: https://github.com/equinor/gordo
 Author: Equinor ASA
 Author-email: fg_gpl@equinor.com
 License: AGPLv3
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: GNU Affero General Public License v3
@@ -50,14 +50,16 @@
 
 ## Components
 
 * [gordo-controller](https://github.com/equinor/gordo-controller/) - Kubernetes controller for the Gordo CRDs.
 * [gordo-core](https://github.com/equinor/gordo-core/) - Gordo core library.
 * [gordo-client](https://github.com/equinor/gordo-client/) - Gordo server's client. It can make predictions from deployed models.
 
+---
+
 [Documentation is available on Read the Docs](https://gordo1.readthedocs.io/)
 
 ---
 ## Install
 
 [gordo-helm](https://github.com/equinor/gordo-helm) - you can use [gordo](https://github.com/equinor/gordo-helm/tree/main/charts/gordo) helm chart from this repository to deploy gordo infrastructure to your Kubernetes cluster.
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: gordo Version: 5.1.1 Summary: Train and build
+Metadata-Version: 2.1 Name: gordo Version: 5.1.2 Summary: Train and build
 models for Argo / Kubernetes Home-page: https://github.com/equinor/gordo
 Author: Equinor ASA Author-email: fg_gpl@equinor.com License: AGPLv3
 Classifier: Intended Audience :: Developers Classifier: License :: OSI Approved
 :: GNU Affero General Public License v3 Classifier: Natural Language :: English
 Classifier: Programming Language :: Python :: 3.9 Classifier: Programming
 Language :: Python :: 3.10 Description-Content-Type: text/markdown Provides-
 Extra: mlflow Provides-Extra: postgres Provides-Extra: tests Provides-Extra:
@@ -14,16 +14,16 @@
                                 [Build_Status]
 --- ## About Gordo fulfills the role of inhaling config files and supplying
 components to the pipeline of: 1. Fetching data 2. Training model 3. Serving
 model ## Components * [gordo-controller](https://github.com/equinor/gordo-
 controller/) - Kubernetes controller for the Gordo CRDs. * [gordo-core](https:/
 /github.com/equinor/gordo-core/) - Gordo core library. * [gordo-client](https:/
 /github.com/equinor/gordo-client/) - Gordo server's client. It can make
-predictions from deployed models. [Documentation is available on Read the Docs]
-(https://gordo1.readthedocs.io/) --- ## Install [gordo-helm](https://
+predictions from deployed models. --- [Documentation is available on Read the
+Docs](https://gordo1.readthedocs.io/) --- ## Install [gordo-helm](https://
 github.com/equinor/gordo-helm) - you can use [gordo](https://github.com/
 equinor/gordo-helm/tree/main/charts/gordo) helm chart from this repository to
 deploy gordo infrastructure to your Kubernetes cluster. ### Python package `pip
 install --upgrade gordo` With additional extras: `pip install gordo
 [postgres,mlflow]` Bleeding edge: `pip install git+https://github.com/equinor/
 gordo.git` ## Developer manual This section will explain how to start
 development of Gordo. ### Setup Create and activate a virtual environment
```

### Comparing `gordo-5.1.1/README.md` & `gordo-5.1.2/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -29,14 +29,16 @@
 
 ## Components
 
 * [gordo-controller](https://github.com/equinor/gordo-controller/) - Kubernetes controller for the Gordo CRDs.
 * [gordo-core](https://github.com/equinor/gordo-core/) - Gordo core library.
 * [gordo-client](https://github.com/equinor/gordo-client/) - Gordo server's client. It can make predictions from deployed models.
 
+---
+
 [Documentation is available on Read the Docs](https://gordo1.readthedocs.io/)
 
 ---
 ## Install
 
 [gordo-helm](https://github.com/equinor/gordo-helm) - you can use [gordo](https://github.com/equinor/gordo-helm/tree/main/charts/gordo) helm chart from this repository to deploy gordo infrastructure to your Kubernetes cluster. 
 
@@ -114,8 +116,8 @@
 ### Build the documentation
 
 This command will run the local documentation server:
 
 ```console
 > cd docs/
 > make watch
-```
+```
```

#### html2text {}

```diff
@@ -5,16 +5,16 @@
                                 [Build_Status]
 --- ## About Gordo fulfills the role of inhaling config files and supplying
 components to the pipeline of: 1. Fetching data 2. Training model 3. Serving
 model ## Components * [gordo-controller](https://github.com/equinor/gordo-
 controller/) - Kubernetes controller for the Gordo CRDs. * [gordo-core](https:/
 /github.com/equinor/gordo-core/) - Gordo core library. * [gordo-client](https:/
 /github.com/equinor/gordo-client/) - Gordo server's client. It can make
-predictions from deployed models. [Documentation is available on Read the Docs]
-(https://gordo1.readthedocs.io/) --- ## Install [gordo-helm](https://
+predictions from deployed models. --- [Documentation is available on Read the
+Docs](https://gordo1.readthedocs.io/) --- ## Install [gordo-helm](https://
 github.com/equinor/gordo-helm) - you can use [gordo](https://github.com/
 equinor/gordo-helm/tree/main/charts/gordo) helm chart from this repository to
 deploy gordo infrastructure to your Kubernetes cluster. ### Python package `pip
 install --upgrade gordo` With additional extras: `pip install gordo
 [postgres,mlflow]` Bleeding edge: `pip install git+https://github.com/equinor/
 gordo.git` ## Developer manual This section will explain how to start
 development of Gordo. ### Setup Create and activate a virtual environment
```

### Comparing `gordo-5.1.1/benchmarks/load_test/README.md` & `gordo-5.1.2/benchmarks/load_test/README.md`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/benchmarks/load_test/load_test.py` & `gordo-5.1.2/benchmarks/load_test/load_test.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/benchmarks/test_ml_server.py` & `gordo-5.1.2/benchmarks/test_ml_server.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/Makefile` & `gordo-5.1.2/docs/Makefile`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/_static/Gordo_C4.svg` & `gordo-5.1.2/docs/_static/Gordo_C4.svg`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/_static/architecture_diagram.png` & `gordo-5.1.2/docs/_static/architecture_diagram.png`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/_static/architecture_diagram.py` & `gordo-5.1.2/docs/_static/architecture_diagram.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/_static/argo_logo.png` & `gordo-5.1.2/docs/_static/argo_logo.png`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/_static/endpoint-metadata.png` & `gordo-5.1.2/docs/_static/endpoint-metadata.png`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/api/builder.rst` & `gordo-5.1.2/docs/api/builder.rst`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/api/machine/metadata.rst` & `gordo-5.1.2/docs/api/machine/metadata.rst`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/api/machine/model/anomaly.rst` & `gordo-5.1.2/docs/api/machine/model/anomaly.rst`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/api/machine/model/model-factories.rst` & `gordo-5.1.2/docs/api/machine/model/model-factories.rst`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/api/serializer.rst` & `gordo-5.1.2/docs/api/serializer.rst`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/api/util.rst` & `gordo-5.1.2/docs/api/util.rst`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/api/workflow.rst` & `gordo-5.1.2/docs/api/workflow.rst`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/conf.py` & `gordo-5.1.2/docs/conf.py`

 * *Files 3% similar despite different names*

```diff
@@ -10,14 +10,16 @@
 import sys
 import datetime
 import importlib
 import inspect
 
 _module_path = os.path.join(os.path.dirname(__file__), "..")
 sys.path.insert(0, _module_path)
+_examples_path = os.path.join(os.path.dirname(__file__), "..", "examples")
+# sys.path.insert(0, _examples_path)
 
 import gordo
 
 from gordo.util.version import parse_version, GordoRelease
 
 project = "gordo"
 copyright = f"2019-{datetime.date.today().year}, Equinor"
@@ -38,21 +40,24 @@
     "sphinx.ext.extlinks",
     "sphinx.ext.linkcode",
     "sphinx.ext.autosectionlabel",
     "IPython.sphinxext.ipython_directive",
     "IPython.sphinxext.ipython_console_highlighting",
     "sphinx_copybutton",
     "sphinx_click",
+    "nbsphinx"
 ]
 
 root_doc = "index"
 
 templates_path = ["_templates"]
 exclude_patterns = ["_build", "Thumbs.db", ".DS_Store"]
 
+source_suffix = [".rst", ".md"]
+
 code_url = f"https://github.com/equinor/{project}/blob/{commit}"
 
 _ignore_linkcode_infos = [
     # caused "OSError: could not find class definition"
     {"module": "gordo_core.utils", "fullname": "PredictionResult"},
     {'module': 'gordo.workflow.config_elements.schemas', 'fullname': 'Model.Config.extra'},
     {'module': 'gordo.reporters.postgres', 'fullname': 'Machine.DoesNotExist'}
```

### Comparing `gordo-5.1.1/docs/general/cluster_deployment.rst` & `gordo-5.1.2/docs/general/cluster_deployment.rst`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/docs/general/endpoints.rst` & `gordo-5.1.2/docs/general/endpoints.rst`

 * *Files 4% similar despite different names*

```diff
@@ -15,14 +15,16 @@
 A detailed example of this API usage could be found :ref:`here <general/cluster_deployment:working with api>`.
 
 .. _post-prediction:
 
 POST /prediction
 ^^^^^^^^^^^^^^^^
 
+``/gordo/v0/<gordo_project>/<gordo_name>/prediction``
+
 :func:`gordo.server.blueprints.base.post_prediction`
 
 The ``/prediction`` endpoint will return the basic values a model
 is capable of returning. Namely, this will be:
 
 - ``model-output``:
     - The raw model output, after calling ``.predict`` on the model or pipeline
@@ -141,14 +143,16 @@
 
 
 ----
 
 POST /anomaly/prediction
 ^^^^^^^^^^^^^^^^^^^^^^^^
 
+``/gordo/v0/<gordo_project>/<gordo_name>/anomaly/prediction``
+
 :func:`gordo.server.blueprints.anomaly.post_anomaly_prediction`
 
 The ``/anomaly/prediction`` endpoint will return the data supplied by the :ref:`post-prediction` endpoint
 but reserved for models which inherit from :class:`gordo.machine.model.anomaly.base.AnomalyDetectorBase`
 
 By this restriction, additional features are calculated and returned.
 
@@ -223,46 +227,58 @@
 against.
 
 .. _get-metadata:
 
 GET /metadata
 ^^^^^^^^^^^^^
 
+``/gordo/v0/<gordo_project>/expected-models``
+
 :func:`gordo.server.blueprints.base.get_metadata`
 
 Various metadata surrounding the current model and environment.
 
 GET /expected-models
 ^^^^^^^^^^^^^^^^^^^^
 
+``/gordo/v0/<gordo_project>/expected-models``
+
 :func:`gordo.server.blueprints.base.get`
 
 Returns list of models for this project. Those models are expected to be built.
 
 GET /models
 ^^^^^^^^^^^
 
+``/gordo/v0/<gordo_project>/models``
+
 :func:`gordo.server.blueprints.base.get_model_list`
 
 List of the current built models.
 
 GET /revisions
 ^^^^^^^^^^^^^^
 
+``/gordo/v0/<gordo_project>/revisions``
+
 :func:`gordo.server.blueprints.base.get_revision_list`
 
 List of available model revisions (versions).
 
 
 GET /download-model
 ^^^^^^^^^^^^^^^^^^^
 
+``/gordo/v0/<gordo_project>/<gordo_name>/download-model``
+
 :func:`gordo.server.blueprints.base.get_download_model`
 
 Returns the current model being served. Loadable via :func:`gordo.serializer.loads`.
 
 DELETE /revision
 ^^^^^^^^^^^^^^^^
 
+``/gordo/v0/<gordo_project>/<gordo_name>/revision/<revision>``
+
 :func:`gordo.server.blueprints.base.delete_model_revision`
 
 Delete one particular revision from the storage.
```

### Comparing `gordo-5.1.1/docs/ml/model_configuration.rst` & `gordo-5.1.2/docs/ml/model_configuration.rst`

 * *Files 26% similar despite different names*

```diff
@@ -36,8 +36,53 @@
 In turn, this method is wrapped around the class :class:`gordo.builder.build_model.ModelBuilder`, which is the top-level
 
 We will focus on the output that is created using :func:`sklearn.model_selection.cross_validate` method,
 which is used when using the model for predictions.
 
 :class:`gordo.machine.machine.Machine` class holds basically all information that is contained in the one Gordo config.
 The :class:`gordo.builder.build_model.ModelBuilder` class takes a :class:`gordo.machine.machine.Machine` and does the heavy lifting
-when it comes to data fetching, cross-validation and model training.
+when it comes to data fetching, cross-validation and model training.
+
+Evaluation specification
+^^^^^^^^^^^^^^^^^^^^^^^^
+
+Alongside the ML-model itself, all aspects of the cross-validation evaluation is parameterized in the config:
+
+.. code-block:: yaml
+
+   - evaluation:
+        cv: 
+          sklearn.model_selection.TimeSeriesSplit:
+            n_splits: 3
+        cv_mode: full_build
+        scoring_scaler: sklearn.preprocessing.MinMaxScaler
+        metrics:
+        - explained_variance_score
+        - r2_score
+        - mean_squared_error
+        - mean_absolute_error
+
+Alternatively, the ``cv_mode`` can be set to ``cross_val_only`` which will not fit the final model.
+
+Cross-validation methods
+^^^^^^^^^^^^^^^^^^^^^^^^
+
+Setting ``cv`` to :class:`sklearn.model_selection.TimeSeriesSplit` , the dataset is split as depicted below.
+Independent of the number of splits, the test set always is of the same size.
+
+An alternative is to use `k-fold <https://scikit-learn.org/stable/modules/cross_validation.html>`_ cross-validation.
+Here, one can decide to shuffle the data before it is split into folds.
+In contradiction to the time-series-split above, which augments the considered data in each fold with time-consecutive observations, this method is uncoupled from the time dimension.
+This must be considered when comparing results from different folds.
+
+The following parameters can then be set as such:
+
+.. code-block:: yaml
+
+   - evaluation:
+        cv: 
+          sklearn.model_selection.KFold:
+            n_splits: 3
+            shuffle: True
+            random_state: 0
+
+Borrowed from `scikit-learn <https://scikit-learn.org/stable/auto_examples/model_selection/plot_cv_indices.html#sphx-glr-auto-examples-model-selection-plot-cv-indices-py>`_ , which performs the actual split/train for us.
```

### Comparing `gordo-5.1.1/docs/ml/model_output.rst` & `gordo-5.1.2/docs/ml/model_output.rst`

 * *Files 11% similar despite different names*

```diff
@@ -105,7 +105,17 @@
 The cross-validation scheme is explained in the `model evaluation and training metadata <>` section, and the calculation of the anomaly confidence.
 
 Based on these thresholds, the following metrics are reported:
 
 
 * ``anomaly-confidence`` = ``tag-anomaly-scaled`` / ``feature-thresholds-per-fold(last fold)``
 * ``total-anomaly-confidence`` = ``total-anomaly-scaled`` / ``aggregate-thresholds-per-fold(last-fold)``
+
+Scaling of data during cross-validation
+^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
+
+Before the cross-validation is executed, the ``scoring_scaler`` is extracted.
+This is used to transform the data before the wanted metrics are calculated.
+
+An internal method, :func:`gordo.builder.build_model.ModelBuilder.build_metrics_dict`, is called prior to the cross-validation, which specified list ``metrics`` and the ``scoring_scaler``.
+This method builds a callable dictionary by using the nested function :func:`gordo.machine.model.utils.metric_wrapper`.
+This generated dictionary now contains information about the ``scoring_scaler`` which will be used later.
```

### Comparing `gordo-5.1.1/docs/overview.rst` & `gordo-5.1.2/docs/overview.rst`

 * *Files 7% similar despite different names*

```diff
@@ -7,19 +7,19 @@
 The main interface after building the models is a set of ``REST`` APIs
 
 .. image:: _static/architecture_diagram.png
 
 `Gordo <https://github.com/equinor/gordo-helm/blob/main/charts/gordo/templates/crds/gordos.equinor.com.yaml>`_ is a `CustomResourceDefinition <https://kubernetes.io/docs/tasks/extend-kubernetes/custom-resources/custom-resource-definitions/>`_
 represents the project and could contains multiple Machine Learning models.
 
-`Model <https://github.com/equinor/gordo-helm/blob/main/charts/gordo/templates/crds/models.equinor.com.yaml>`_ is the CustomResourceDefinition
-represents the project and can contains multiple Machine Learning models.
-
 `gordo-controller <https://github.com/equinor/gordo-controller>`_ is a `K8S controller <https://cluster-api.sigs.k8s.io/developer/providers/implementers-guide/controllers_and_reconciliation.html>`_ and an API server that provides Gordos/Models statuses.
 
 ``dpl`` is a deployment `Job <https://kubernetes.io/docs/concepts/workloads/controllers/job/>`_ thats run :ref:`generate workflow <general/cli:generate>` command.
 
 ``model_builder1``, ``model_builder2`` Jobs builds ML models with :ref:`build <general/cli:build>` command.
 
+`Model <https://github.com/equinor/gordo-helm/blob/main/charts/gordo/templates/crds/models.equinor.com.yaml>`_ is the CustomResourceDefinition
+represents the model entity generated by the Argo workflow.
+
 ``storage`` is `PersistentVolume <https://kubernetes.io/docs/concepts/storage/persistent-volumes/>`_ where ML models have to be stored.
 
 ``gordo-server`` is a ML Server. Full API spec can be found :ref:`here <general/endpoints:endpoints>`.
```

### Comparing `gordo-5.1.1/examples/Pipelines-with-Gordo.ipynb` & `gordo-5.1.2/examples/Pipelines-with-Gordo.ipynb`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/examples/config.yaml` & `gordo-5.1.2/examples/config.yaml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/examples/model-configuration.yaml` & `gordo-5.1.2/examples/model-configuration.yaml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/examples/test-project.yaml` & `gordo-5.1.2/examples/test-project.yaml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/functions.sh` & `gordo-5.1.2/functions.sh`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/__init__.py` & `gordo-5.1.2/gordo/__init__.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/builder/build_model.py` & `gordo-5.1.2/gordo/builder/build_model.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/builder/local_build.py` & `gordo-5.1.2/gordo/builder/local_build.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/builder/utils.py` & `gordo-5.1.2/gordo/builder/utils.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/cli/cli.py` & `gordo-5.1.2/gordo/cli/cli.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,8 @@
 # -*- coding: utf-8 -*-
-
-"""
-CLI interfaces
-"""
-
 import logging
 import sys
 import traceback
 import jinja2
 import yaml
 import click
```

### Comparing `gordo-5.1.1/gordo/cli/custom_types.py` & `gordo-5.1.2/gordo/cli/custom_types.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/cli/exceptions_reporter.py` & `gordo-5.1.2/gordo/cli/exceptions_reporter.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/cli/workflow_generator.py` & `gordo-5.1.2/gordo/cli/workflow_generator.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/encoders.py` & `gordo-5.1.2/gordo/machine/encoders.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/loader.py` & `gordo-5.1.2/gordo/machine/loader.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/machine.py` & `gordo-5.1.2/gordo/machine/machine.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/metadata/metadata.py` & `gordo-5.1.2/gordo/machine/metadata/metadata.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/model/anomaly/base.py` & `gordo-5.1.2/gordo/machine/model/anomaly/base.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/model/anomaly/diff.py` & `gordo-5.1.2/gordo/machine/model/anomaly/diff.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/model/base.py` & `gordo-5.1.2/gordo/machine/model/base.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/model/factories/feedforward_autoencoder.py` & `gordo-5.1.2/gordo/machine/model/factories/feedforward_autoencoder.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/model/factories/lstm_autoencoder.py` & `gordo-5.1.2/gordo/machine/model/factories/lstm_autoencoder.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/model/factories/utils.py` & `gordo-5.1.2/gordo/machine/model/factories/utils.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/model/models.py` & `gordo-5.1.2/gordo/machine/model/models.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/model/register.py` & `gordo-5.1.2/gordo/machine/model/register.py`

 * *Files 6% similar despite different names*

```diff
@@ -11,15 +11,15 @@
     """
         Decorator to register a function as an available 'type' in supporting
         factory classes such as :class:`gordo.machine.model.models.KerasAutoEncoder`.
 
         When submitting the config file, it's important that the 'kind' is compatible
         with 'type'.
 
-        ie. 'type': 'KerasAutoEncoder' should support the object returned by a given
+        ie. ``type='KerasAutoEncoder'`` should support the object returned by a given
         decorated function.
 
 
     .. code:: python
 
         from gordo_compontents.models.register import register_model_builder
```

### Comparing `gordo-5.1.1/gordo/machine/model/transformer_funcs/general.py` & `gordo-5.1.2/gordo/machine/model/transformer_funcs/general.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/model/transformers/imputer.py` & `gordo-5.1.2/gordo/machine/model/transformers/imputer.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/model/utils.py` & `gordo-5.1.2/gordo/machine/model/utils.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/machine/validators.py` & `gordo-5.1.2/gordo/machine/validators.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/reporters/base.py` & `gordo-5.1.2/gordo/reporters/base.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/reporters/mlflow.py` & `gordo-5.1.2/gordo/reporters/mlflow.py`

 * *Files 1% similar despite different names*

```diff
@@ -58,31 +58,33 @@
     Set remote tracking URI for mlflow to AzureML workspace
 
     Parameters
     ----------
     workspace_kwargs
         AzureML Workspace configuration to use for remote MLFlow tracking. An
         empty dict will result in local logging by the MlflowClient.
-        Example::
 
-            `{
+        .. code-block::
+
+            {
                  "subscription_id":<value>,
                  "resource_group":<value>,
                  "workspace_name":<value>
-             }`
+            }
     service_principal_kwargs: dict
         AzureML ServicePrincipalAuthentication keyword arguments. An empty dict
         will result in interactive authentication.
-        Example::
 
-            `{
+        .. code-block::
+
+            {
                  "tenant_id":<value>,
                  "service_principal_id":<value>,
                  "service_principal_password":<value>
-             }`
+            }
 
     Returns
     -------
         Client with tracking uri set to AzureML if configured.
     """
     logger.info("Creating MLflow tracking client.")
```

### Comparing `gordo-5.1.1/gordo/reporters/postgres.py` & `gordo-5.1.2/gordo/reporters/postgres.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/serializer/from_definition.py` & `gordo-5.1.2/gordo/serializer/from_definition.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/serializer/into_definition.py` & `gordo-5.1.2/gordo/serializer/into_definition.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/serializer/serializer.py` & `gordo-5.1.2/gordo/serializer/serializer.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/serializer/utils.py` & `gordo-5.1.2/gordo/serializer/utils.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/server/blueprints/anomaly.py` & `gordo-5.1.2/gordo/server/blueprints/anomaly.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/server/blueprints/base.py` & `gordo-5.1.2/gordo/server/blueprints/base.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/server/model_io.py` & `gordo-5.1.2/gordo/server/model_io.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/server/prometheus/metrics.py` & `gordo-5.1.2/gordo/server/prometheus/metrics.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/server/prometheus/server.py` & `gordo-5.1.2/gordo/server/prometheus/server.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/server/properties.py` & `gordo-5.1.2/gordo/server/properties.py`

 * *Files 1% similar despite different names*

```diff
@@ -18,15 +18,17 @@
     --------
     >>> find_path_in_dict(["parent", "child"], {"parent": {"child": 42}})
     42
 
     Parameters
     ----------
     path
+        List of nested keys
     data
+        Dict to find
 
     Returns
     -------
 
     """
     reversed_path = copy.copy(path)
     reversed_path.reverse()
```

### Comparing `gordo-5.1.1/gordo/server/server.py` & `gordo-5.1.2/gordo/server/server.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/server/utils.py` & `gordo-5.1.2/gordo/server/utils.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/util/disk_registry.py` & `gordo-5.1.2/gordo/util/disk_registry.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/util/utils.py` & `gordo-5.1.2/gordo/util/utils.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/util/version.py` & `gordo-5.1.2/gordo/util/version.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/utils.py` & `gordo-5.1.2/gordo/utils.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/workflow/config_elements/normalized_config.py` & `gordo-5.1.2/gordo/workflow/config_elements/normalized_config.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/workflow/config_elements/schemas.py` & `gordo-5.1.2/gordo/workflow/config_elements/schemas.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/workflow/workflow_generator/helpers.py` & `gordo-5.1.2/gordo/workflow/workflow_generator/helpers.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/workflow/workflow_generator/resources/argo-workflow.yml.template` & `gordo-5.1.2/gordo/workflow/workflow_generator/resources/argo-workflow.yml.template`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo/workflow/workflow_generator/workflow_generator.py` & `gordo-5.1.2/gordo/workflow/workflow_generator/workflow_generator.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo.egg-info/PKG-INFO` & `gordo-5.1.2/gordo.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: gordo
-Version: 5.1.1
+Version: 5.1.2
 Summary: Train and build models for Argo / Kubernetes
 Home-page: https://github.com/equinor/gordo
 Author: Equinor ASA
 Author-email: fg_gpl@equinor.com
 License: AGPLv3
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: GNU Affero General Public License v3
@@ -50,14 +50,16 @@
 
 ## Components
 
 * [gordo-controller](https://github.com/equinor/gordo-controller/) - Kubernetes controller for the Gordo CRDs.
 * [gordo-core](https://github.com/equinor/gordo-core/) - Gordo core library.
 * [gordo-client](https://github.com/equinor/gordo-client/) - Gordo server's client. It can make predictions from deployed models.
 
+---
+
 [Documentation is available on Read the Docs](https://gordo1.readthedocs.io/)
 
 ---
 ## Install
 
 [gordo-helm](https://github.com/equinor/gordo-helm) - you can use [gordo](https://github.com/equinor/gordo-helm/tree/main/charts/gordo) helm chart from this repository to deploy gordo infrastructure to your Kubernetes cluster.
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: gordo Version: 5.1.1 Summary: Train and build
+Metadata-Version: 2.1 Name: gordo Version: 5.1.2 Summary: Train and build
 models for Argo / Kubernetes Home-page: https://github.com/equinor/gordo
 Author: Equinor ASA Author-email: fg_gpl@equinor.com License: AGPLv3
 Classifier: Intended Audience :: Developers Classifier: License :: OSI Approved
 :: GNU Affero General Public License v3 Classifier: Natural Language :: English
 Classifier: Programming Language :: Python :: 3.9 Classifier: Programming
 Language :: Python :: 3.10 Description-Content-Type: text/markdown Provides-
 Extra: mlflow Provides-Extra: postgres Provides-Extra: tests Provides-Extra:
@@ -14,16 +14,16 @@
                                 [Build_Status]
 --- ## About Gordo fulfills the role of inhaling config files and supplying
 components to the pipeline of: 1. Fetching data 2. Training model 3. Serving
 model ## Components * [gordo-controller](https://github.com/equinor/gordo-
 controller/) - Kubernetes controller for the Gordo CRDs. * [gordo-core](https:/
 /github.com/equinor/gordo-core/) - Gordo core library. * [gordo-client](https:/
 /github.com/equinor/gordo-client/) - Gordo server's client. It can make
-predictions from deployed models. [Documentation is available on Read the Docs]
-(https://gordo1.readthedocs.io/) --- ## Install [gordo-helm](https://
+predictions from deployed models. --- [Documentation is available on Read the
+Docs](https://gordo1.readthedocs.io/) --- ## Install [gordo-helm](https://
 github.com/equinor/gordo-helm) - you can use [gordo](https://github.com/
 equinor/gordo-helm/tree/main/charts/gordo) helm chart from this repository to
 deploy gordo infrastructure to your Kubernetes cluster. ### Python package `pip
 install --upgrade gordo` With additional extras: `pip install gordo
 [postgres,mlflow]` Bleeding edge: `pip install git+https://github.com/equinor/
 gordo.git` ## Developer manual This section will explain how to start
 development of Gordo. ### Setup Create and activate a virtual environment
```

### Comparing `gordo-5.1.1/gordo.egg-info/SOURCES.txt` & `gordo-5.1.2/gordo.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/gordo.egg-info/requires.txt` & `gordo-5.1.2/gordo.egg-info/requires.txt`

 * *Files 2% similar despite different names*

```diff
@@ -15,14 +15,15 @@
 [docs]
 sphinx~=6.2
 sphinx-autobuild~=2021.3
 sphinx-copybutton~=0.5
 furo~=2023.5
 sphinx-click~=4.4
 ipython~=8.13
+nbsphinx~=0.9
 mlflow~=2.3
 azureml-core~=1.49
 peewee~=3.14
 psycopg2-binary~=2.9
 
 [full]
 mlflow~=2.3
```

### Comparing `gordo-5.1.1/pytest.ini` & `gordo-5.1.2/pytest.ini`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/requirements/full_requirements.txt` & `gordo-5.1.2/requirements/full_requirements.txt`

 * *Files 2% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 #
-# This file is autogenerated by pip-compile with Python 3.9
+# This file is autogenerated by pip-compile with Python 3.10
 # by the following command:
 #
-#    pip-compile --output-file=full_requirements.txt mlflow_requirements.in postgres_requirements.in requirements.in
+#    pip-compile --output-file=full_requirements.txt --resolver=backtracking mlflow_requirements.in postgres_requirements.in requirements.in
 #
 absl-py==1.4.0
     # via
     #   tensorboard
     #   tensorflow
 adal==1.2.7
     # via
@@ -25,15 +25,15 @@
     #   azure-graphrbac
     #   azure-mgmt-authorization
     #   azure-mgmt-containerregistry
     #   azure-mgmt-keyvault
     #   azure-mgmt-resource
     #   azure-mgmt-storage
     #   azureml-core
-azure-core==1.27.0
+azure-core==1.27.1
     # via
     #   azure-mgmt-core
     #   azureml-core
     #   msrest
 azure-graphrbac==0.61.1
     # via azureml-core
 azure-mgmt-authorization==3.0.0
@@ -49,15 +49,15 @@
     #   azure-mgmt-storage
 azure-mgmt-keyvault==10.2.2
     # via azureml-core
 azure-mgmt-resource==22.0.0
     # via azureml-core
 azure-mgmt-storage==21.0.0
     # via azureml-core
-azureml-core==1.51.0
+azureml-core==1.52.0
     # via -r mlflow_requirements.in
 backports-tempfile==1.0
     # via azureml-core
 backports-weakref==1.0.post1
     # via backports-tempfile
 bcrypt==4.0.1
     # via paramiko
@@ -85,30 +85,30 @@
     #   flask
     #   gordo-client
     #   mlflow
 cloudpickle==2.2.1
     # via mlflow
 contextlib2==21.6.0
     # via azureml-core
-contourpy==1.0.7
+contourpy==1.1.0
     # via matplotlib
-cryptography==40.0.2
+cryptography==41.0.1
     # via
     #   adal
     #   azureml-core
     #   msal
     #   paramiko
     #   pyjwt
     #   pyopenssl
     #   secretstorage
 cycler==0.11.0
     # via matplotlib
 databricks-cli==0.17.7
     # via mlflow
-dataclasses-json==0.5.7
+dataclasses-json==0.5.8
     # via -r requirements.in
 dictdiffer==0.9.0
     # via -r requirements.in
 docker==6.1.3
     # via
     #   azureml-core
     #   mlflow
@@ -116,71 +116,65 @@
     # via mlflow
 flask==2.3.2
     # via
     #   -r requirements.in
     #   mlflow
 flatbuffers==23.5.26
     # via tensorflow
-fonttools==4.39.4
+fonttools==4.40.0
     # via matplotlib
 gast==0.4.0
     # via tensorflow
 gitdb==4.0.10
     # via gitpython
 gitpython==3.1.31
     # via mlflow
-google-auth==2.19.1
+google-auth==2.21.0
     # via
     #   google-auth-oauthlib
     #   tensorboard
 google-auth-oauthlib==1.0.0
     # via tensorboard
 google-pasta==0.2.0
     # via tensorflow
-gordo-client==6.2.0
+gordo-client==6.2.2
     # via -r requirements.in
-gordo-core==0.3.1
+gordo-core==0.3.2
     # via gordo-client
 graphviz==0.20.1
     # via catboost
 greenlet==2.0.2
     # via sqlalchemy
-grpcio==1.54.2
+grpcio==1.56.0
     # via
     #   tensorboard
     #   tensorflow
 gunicorn==20.1.0
     # via
     #   -r requirements.in
     #   mlflow
-h5py==3.8.0
+h5py==3.9.0
     # via
     #   -r requirements.in
     #   tensorflow
 humanfriendly==10.0
     # via azureml-core
 idna==3.4
     # via requests
-importlib-metadata==6.6.0
-    # via
-    #   flask
-    #   jax
-    #   markdown
-    #   mlflow
-importlib-resources==5.12.0
-    # via matplotlib
+importlib-metadata==6.7.0
+    # via mlflow
 influxdb==5.3.1
     # via gordo-core
 isodate==0.6.1
     # via
     #   azure-mgmt-keyvault
     #   msrest
 itsdangerous==2.1.2
     # via flask
-jax==0.4.11
+jax==0.4.13
     # via tensorflow
 jeepney==0.8.0
     # via secretstorage
 jinja2==3.1.2
     # via
     #   -r requirements.in
     #   flask
@@ -218,17 +212,17 @@
     #   marshmallow-enum
 marshmallow-enum==1.5.1
     # via dataclasses-json
 matplotlib==3.7.1
     # via
     #   catboost
     #   mlflow
-ml-dtypes==0.1.0
+ml-dtypes==0.2.0
     # via jax
-mlflow==2.3.2
+mlflow==2.4.1
     # via -r mlflow_requirements.in
 msal==1.22.0
     # via
     #   azureml-core
     #   msal-extensions
 msal-extensions==1.0.0
     # via azureml-core
@@ -303,21 +297,21 @@
     # via azureml-core
 peewee==3.16.2
     # via -r postgres_requirements.in
 pillow==9.5.0
     # via matplotlib
 pkginfo==1.9.6
     # via azureml-core
-plotly==5.14.1
+plotly==5.15.0
     # via catboost
 portalocker==2.7.0
     # via msal-extensions
 prometheus-client==0.17.0
     # via -r requirements.in
-protobuf==4.23.2
+protobuf==4.23.3
     # via
     #   mlflow
     #   tensorboard
     #   tensorflow
 psycopg2-binary==2.9.6
     # via -r postgres_requirements.in
 pyarrow==10.0.1
@@ -329,15 +323,15 @@
     #   ndg-httpsclient
     #   pyasn1-modules
     #   rsa
 pyasn1-modules==0.3.0
     # via google-auth
 pycparser==2.21
     # via cffi
-pydantic==1.10.8
+pydantic==1.10.9
     # via gordo-client
 pygments==2.15.1
     # via knack
 pyjwt[crypto]==2.7.0
     # via
     #   adal
     #   azureml-core
@@ -345,15 +339,15 @@
     #   msal
 pynacl==1.5.0
     # via paramiko
 pyopenssl==23.2.0
     # via
     #   azureml-core
     #   ndg-httpsclient
-pyparsing==3.0.9
+pyparsing==3.1.0
     # via
     #   matplotlib
     #   packaging
 pysocks==1.7.1
     # via requests
 python-dateutil==2.8.2
     # via
@@ -396,15 +390,15 @@
     #   msrest
 rsa==4.9
     # via google-auth
 scikit-learn==1.2.2
     # via
     #   gordo-core
     #   mlflow
-scipy==1.10.1
+scipy==1.11.0
     # via
     #   catboost
     #   jax
     #   mlflow
     #   scikit-learn
 secretstorage==3.3.3
     # via azureml-core
@@ -424,29 +418,29 @@
     #   isodate
     #   msrestazure
     #   python-dateutil
     #   querystring-parser
     #   tensorflow
 smmap==5.0.0
     # via gitdb
-sqlalchemy==2.0.15
+sqlalchemy==2.0.17
     # via
     #   alembic
     #   mlflow
 sqlparse==0.4.4
     # via mlflow
 tabulate==0.9.0
     # via
     #   databricks-cli
     #   knack
 tenacity==8.2.2
     # via plotly
 tensorboard==2.12.3
     # via tensorflow
-tensorboard-data-server==0.7.0
+tensorboard-data-server==0.7.1
     # via tensorboard
 tensorflow==2.12.0
     # via -r requirements.in
 tensorflow-estimator==2.12.0
     # via tensorflow
 tensorflow-io-gcs-filesystem==0.32.0
     # via tensorflow
@@ -467,30 +461,28 @@
 urllib3==1.26.16
     # via
     #   azureml-core
     #   databricks-cli
     #   docker
     #   google-auth
     #   requests
-websocket-client==1.5.2
+websocket-client==1.6.1
     # via docker
-werkzeug==2.3.4
+werkzeug==2.3.6
     # via
     #   flask
     #   tensorboard
 wheel==0.40.0
     # via
     #   astunparse
     #   tensorboard
 wrapt==1.14.1
     # via
     #   gordo-client
     #   tensorflow
-xarray==2023.5.0
+xarray==2023.6.0
     # via gordo-core
 zipp==3.15.0
-    # via
-    #   importlib-metadata
-    #   importlib-resources
+    # via importlib-metadata
 
 # The following packages are considered to be unsafe in a requirements file:
 # setuptools
```

### Comparing `gordo-5.1.1/requirements/test_requirements.txt` & `gordo-5.1.2/requirements/test_requirements.txt`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/resources/grafana/dashboards/Gordo_servers-VictoriaMetrics.json` & `gordo-5.1.2/resources/grafana/dashboards/Gordo_servers-VictoriaMetrics.json`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/resources/grafana/dashboards/machines.json` & `gordo-5.1.2/resources/grafana/dashboards/machines.json`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/run_workflow_and_argo.sh` & `gordo-5.1.2/run_workflow_and_argo.sh`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/scripts/download_argo.py` & `gordo-5.1.2/scripts/download_argo.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/scripts/github_docker.py` & `gordo-5.1.2/scripts/github_docker.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/scripts/tests.sh` & `gordo-5.1.2/scripts/tests.sh`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/scripts/trivy_scan.sh` & `gordo-5.1.2/scripts/trivy_scan.sh`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/setup.py` & `gordo-5.1.2/setup.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/config-test.yaml` & `gordo-5.1.2/tests/config-test.yaml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/conftest.py` & `gordo-5.1.2/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/builder/test_builder.py` & `gordo-5.1.2/tests/gordo/builder/test_builder.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/builder/test_local_build.py` & `gordo-5.1.2/tests/gordo/builder/test_local_build.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/builder/test_utils.py` & `gordo-5.1.2/tests/gordo/builder/test_utils.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/cli/test_cli.py` & `gordo-5.1.2/tests/gordo/cli/test_cli.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/cli/test_exception_reporter.py` & `gordo-5.1.2/tests/gordo/cli/test_exception_reporter.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/client/test_client.py` & `gordo-5.1.2/tests/gordo/client/test_client.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/machine/metadata/test_metadata.py` & `gordo-5.1.2/tests/gordo/machine/metadata/test_metadata.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/machine/model/anomaly/test_anomaly_detectors.py` & `gordo-5.1.2/tests/gordo/machine/model/anomaly/test_anomaly_detectors.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/machine/model/test_factories_utils.py` & `gordo-5.1.2/tests/gordo/machine/model/test_factories_utils.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/machine/model/test_feedforward_autoencoder.py` & `gordo-5.1.2/tests/gordo/machine/model/test_feedforward_autoencoder.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/machine/model/test_lstm_autoencoder.py` & `gordo-5.1.2/tests/gordo/machine/model/test_lstm_autoencoder.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/machine/model/test_model.py` & `gordo-5.1.2/tests/gordo/machine/model/test_model.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/machine/model/test_raw_keras.py` & `gordo-5.1.2/tests/gordo/machine/model/test_raw_keras.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/machine/model/test_register.py` & `gordo-5.1.2/tests/gordo/machine/model/test_register.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/machine/model/test_transformers.py` & `gordo-5.1.2/tests/gordo/machine/model/test_transformers.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/machine/model/test_utils.py` & `gordo-5.1.2/tests/gordo/machine/model/test_utils.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/machine/test_descriptors.py` & `gordo-5.1.2/tests/gordo/machine/test_descriptors.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/machine/test_loader.py` & `gordo-5.1.2/tests/gordo/machine/test_loader.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/machine/test_machine.py` & `gordo-5.1.2/tests/gordo/machine/test_machine.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/reporters/test_mlflow_reporter.py` & `gordo-5.1.2/tests/gordo/reporters/test_mlflow_reporter.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/reporters/test_postgres_reporter.py` & `gordo-5.1.2/tests/gordo/reporters/test_postgres_reporter.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/serializer/test_serializer_from_definition.py` & `gordo-5.1.2/tests/gordo/serializer/test_serializer_from_definition.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/serializer/test_serializer_into_definition.py` & `gordo-5.1.2/tests/gordo/serializer/test_serializer_into_definition.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/serializer/test_serializer_load_dump.py` & `gordo-5.1.2/tests/gordo/serializer/test_serializer_load_dump.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/server/test_anomaly_blueprint.py` & `gordo-5.1.2/tests/gordo/server/test_anomaly_blueprint.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/server/test_base_blueprint.py` & `gordo-5.1.2/tests/gordo/server/test_base_blueprint.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/server/test_gordo_server.py` & `gordo-5.1.2/tests/gordo/server/test_gordo_server.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/server/test_model_io.py` & `gordo-5.1.2/tests/gordo/server/test_model_io.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/server/test_prometheus.py` & `gordo-5.1.2/tests/gordo/server/test_prometheus.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/server/test_utils.py` & `gordo-5.1.2/tests/gordo/server/test_utils.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/test_version.py` & `gordo-5.1.2/tests/gordo/test_version.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/util/test_disk_registry.py` & `gordo-5.1.2/tests/gordo/util/test_disk_registry.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/util/test_version.py` & `gordo-5.1.2/tests/gordo/util/test_version.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_config_elements.py` & `gordo-5.1.2/tests/gordo/workflow/test_config_elements.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_helpers.py` & `gordo-5.1.2/tests/gordo/workflow/test_helpers.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_normalized_config.py` & `gordo-5.1.2/tests/gordo/workflow/test_normalized_config.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-allowed-timestamps.yml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-allowed-timestamps.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-datasource.yml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-datasource.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-disable-influx.yml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-disable-influx.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-empty-tag-list.yml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-empty-tag-list.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-failing-resource-format.yml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-failing-resource-format.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-model-builder-spec.yaml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-model-builder-spec.yaml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-quotes.yml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-quotes.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-runtime-images.yaml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-runtime-images.yaml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-runtime-labels.yaml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-runtime-labels.yaml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-runtime-resource.yaml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-runtime-resource.yaml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-selective-influx.yml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-selective-influx.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-timestamp-1.yml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-timestamp-1.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-timestamp-2.yml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-timestamp-2.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-timestamp-3.yml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-timestamp-3.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-with-log-key.yml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-with-log-key.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/data/config-test-with-models.yml` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/data/config-test-with-models.yml`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/gordo/workflow/test_workflow_generator/test_workflow_generator.py` & `gordo-5.1.2/tests/gordo/workflow/test_workflow_generator/test_workflow_generator.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/test_examples.py` & `gordo-5.1.2/tests/test_examples.py`

 * *Files identical despite different names*

### Comparing `gordo-5.1.1/tests/utils.py` & `gordo-5.1.2/tests/utils.py`

 * *Files identical despite different names*


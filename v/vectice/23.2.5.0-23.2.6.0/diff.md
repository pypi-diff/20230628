# Comparing `tmp/vectice-23.2.5.0.tar.gz` & `tmp/vectice-23.2.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "vectice-23.2.5.0.tar", last modified: Wed Jun 14 08:05:33 2023, max compression
+gzip compressed data, was "vectice-23.2.6.0.tar", last modified: Wed Jun 28 08:17:15 2023, max compression
```

## Comparing `vectice-23.2.5.0.tar` & `vectice-23.2.6.0.tar`

### file list

```diff
@@ -1,134 +1,136 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 08:05:33.595195 vectice-23.2.5.0/
--rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-14 08:05:24.000000 vectice-23.2.5.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1381 2023-06-14 08:05:33.595195 vectice-23.2.5.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)       94 2023-06-14 08:05:24.000000 vectice-23.2.5.0/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      122 2023-06-14 08:05:24.000000 vectice-23.2.5.0/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       67 2023-06-14 08:05:33.595195 vectice-23.2.5.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     3160 2023-06-14 08:05:24.000000 vectice-23.2.5.0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 08:05:33.579195 vectice-23.2.5.0/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 08:05:33.579195 vectice-23.2.5.0/src/vectice/
--rw-r--r--   0 runner    (1001) docker     (123)     2681 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/__version__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 08:05:33.583195 vectice-23.2.5.0/src/vectice/api/
--rw-r--r--   0 runner    (1001) docker     (123)      601 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3424 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/_auth.py
--rw-r--r--   0 runner    (1001) docker     (123)      259 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     7956 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/attachment.py
--rw-r--r--   0 runner    (1001) docker     (123)    18655 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/client.py
--rw-r--r--   0 runner    (1001) docker     (123)      456 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/compatibility.py
--rw-r--r--   0 runner    (1001) docker     (123)     4474 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/gql_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     2629 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/gql_code.py
--rw-r--r--   0 runner    (1001) docker     (123)     3475 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/gql_code_version.py
--rw-r--r--   0 runner    (1001) docker     (123)     5126 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/gql_dataset.py
--rw-r--r--   0 runner    (1001) docker     (123)      817 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/gql_entity_file.py
--rw-r--r--   0 runner    (1001) docker     (123)      790 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/gql_feature_flag.py
--rw-r--r--   0 runner    (1001) docker     (123)     4710 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/gql_model.py
--rw-r--r--   0 runner    (1001) docker     (123)     1191 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/gql_user_workspace_api.py
--rw-r--r--   0 runner    (1001) docker     (123)      896 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/http_error.py
--rw-r--r--   0 runner    (1001) docker     (123)    12727 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/http_error_handlers.py
--rw-r--r--   0 runner    (1001) docker     (123)     7729 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/iteration.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 08:05:33.587195 vectice-23.2.5.0/src/vectice/api/json/
--rw-r--r--   0 runner    (1001) docker     (123)     2785 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1011 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/artifact_version.py
--rw-r--r--   0 runner    (1001) docker     (123)      238 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/attachment.py
--rw-r--r--   0 runner    (1001) docker     (123)     2081 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/code.py
--rw-r--r--   0 runner    (1001) docker     (123)     5900 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/code_version.py
--rw-r--r--   0 runner    (1001) docker     (123)      326 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/compatibility.py
--rw-r--r--   0 runner    (1001) docker     (123)     2076 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/dataset_register.py
--rw-r--r--   0 runner    (1001) docker     (123)     1428 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/dataset_representation.py
--rw-r--r--   0 runner    (1001) docker     (123)      780 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/dataset_version.py
--rw-r--r--   0 runner    (1001) docker     (123)      911 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/dataset_version_representation.py
--rw-r--r--   0 runner    (1001) docker     (123)      150 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/entity_file.py
--rw-r--r--   0 runner    (1001) docker     (123)     1099 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/files_metadata.py
--rw-r--r--   0 runner    (1001) docker     (123)     4540 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/iteration.py
--rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/last_assets.py
--rw-r--r--   0 runner    (1001) docker     (123)      922 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/metric.py
--rw-r--r--   0 runner    (1001) docker     (123)     1674 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/model.py
--rw-r--r--   0 runner    (1001) docker     (123)     2157 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/model_register.py
--rw-r--r--   0 runner    (1001) docker     (123)     1268 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/model_representation.py
--rw-r--r--   0 runner    (1001) docker     (123)     4369 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/model_version.py
--rw-r--r--   0 runner    (1001) docker     (123)     1328 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/model_version_representation.py
--rw-r--r--   0 runner    (1001) docker     (123)      352 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/page.py
--rw-r--r--   0 runner    (1001) docker     (123)     1050 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/paged_response.py
--rw-r--r--   0 runner    (1001) docker     (123)     1784 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/phase.py
--rw-r--r--   0 runner    (1001) docker     (123)      961 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/project.py
--rw-r--r--   0 runner    (1001) docker     (123)     1549 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/property.py
--rw-r--r--   0 runner    (1001) docker     (123)      692 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/public_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     2815 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/step.py
--rw-r--r--   0 runner    (1001) docker     (123)      510 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/user_and_workspace.py
--rw-r--r--   0 runner    (1001) docker     (123)      235 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/user_declared_version.py
--rw-r--r--   0 runner    (1001) docker     (123)      606 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json/workspace.py
--rw-r--r--   0 runner    (1001) docker     (123)       94 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/json_object.py
--rw-r--r--   0 runner    (1001) docker     (123)     1590 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/last_assets.py
--rw-r--r--   0 runner    (1001) docker     (123)     4819 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/phase.py
--rw-r--r--   0 runner    (1001) docker     (123)     3046 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/project.py
--rw-r--r--   0 runner    (1001) docker     (123)     8182 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/rest_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     6235 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/step.py
--rw-r--r--   0 runner    (1001) docker     (123)      996 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     2514 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/api/workspace.py
--rw-r--r--   0 runner    (1001) docker     (123)    25217 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/connection.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 08:05:33.591195 vectice-23.2.5.0/src/vectice/models/
--rw-r--r--   0 runner    (1001) docker     (123)      684 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2377 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/attachment_container.py
--rw-r--r--   0 runner    (1001) docker     (123)    14035 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/dataset.py
--rw-r--r--   0 runner    (1001) docker     (123)      329 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/errors.py
--rw-r--r--   0 runner    (1001) docker     (123)     6202 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/git_version.py
--rw-r--r--   0 runner    (1001) docker     (123)    10607 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/iteration.py
--rw-r--r--   0 runner    (1001) docker     (123)      954 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/metric.py
--rw-r--r--   0 runner    (1001) docker     (123)     8601 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/model.py
--rw-r--r--   0 runner    (1001) docker     (123)    13356 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/phase.py
--rw-r--r--   0 runner    (1001) docker     (123)     6876 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/project.py
--rw-r--r--   0 runner    (1001) docker     (123)      817 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/property.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 08:05:33.591195 vectice-23.2.5.0/src/vectice/models/representation/
--rw-r--r--   0 runner    (1001) docker     (123)      560 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/representation/dataset_representation.py
--rw-r--r--   0 runner    (1001) docker     (123)      351 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/representation/dataset_version_representation.py
--rw-r--r--   0 runner    (1001) docker     (123)      510 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/representation/model_representation.py
--rw-r--r--   0 runner    (1001) docker     (123)      459 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/representation/model_version_representation.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 08:05:33.591195 vectice-23.2.5.0/src/vectice/models/resource/
--rw-r--r--   0 runner    (1001) docker     (123)      612 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4547 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/base.py
--rw-r--r--   0 runner    (1001) docker     (123)     7432 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/bigquery_resource.py
--rw-r--r--   0 runner    (1001) docker     (123)     2287 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/description.py
--rw-r--r--   0 runner    (1001) docker     (123)     5766 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/file_resource.py
--rw-r--r--   0 runner    (1001) docker     (123)     5722 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/gcs_resource.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 08:05:33.595195 vectice-23.2.5.0/src/vectice/models/resource/metadata/
--rw-r--r--   0 runner    (1001) docker     (123)      658 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/metadata/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2076 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/metadata/base.py
--rw-r--r--   0 runner    (1001) docker     (123)     5568 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/metadata/column_metadata.py
--rw-r--r--   0 runner    (1001) docker     (123)      531 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/metadata/dataframe_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     2502 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/metadata/db_metadata.py
--rw-r--r--   0 runner    (1001) docker     (123)     1989 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/metadata/df_wrapper_default.py
--rw-r--r--   0 runner    (1001) docker     (123)     1438 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/metadata/df_wrapper_pandas.py
--rw-r--r--   0 runner    (1001) docker     (123)     5798 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/metadata/df_wrapper_pandas_default.py
--rw-r--r--   0 runner    (1001) docker     (123)     2375 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/metadata/df_wrapper_pyspark_pandas.py
--rw-r--r--   0 runner    (1001) docker     (123)      861 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/metadata/df_wrapper_resource.py
--rw-r--r--   0 runner    (1001) docker     (123)     5780 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/metadata/df_wrapper_spark_df.py
--rw-r--r--   0 runner    (1001) docker     (123)     2959 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/metadata/files_metadata.py
--rw-r--r--   0 runner    (1001) docker     (123)      775 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/metadata/pyspark_pandas_dataframe_typing.py
--rw-r--r--   0 runner    (1001) docker     (123)     3601 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/metadata/source.py
--rw-r--r--   0 runner    (1001) docker     (123)     7446 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/resource/s3_resource.py
--rw-r--r--   0 runner    (1001) docker     (123)    29923 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/step.py
--rw-r--r--   0 runner    (1001) docker     (123)     1327 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/step_dataset.py
--rw-r--r--   0 runner    (1001) docker     (123)     1178 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/step_image.py
--rw-r--r--   0 runner    (1001) docker     (123)     1388 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/step_model.py
--rw-r--r--   0 runner    (1001) docker     (123)     1930 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/step_number.py
--rw-r--r--   0 runner    (1001) docker     (123)     1764 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/step_string.py
--rw-r--r--   0 runner    (1001) docker     (123)     5956 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/models/workspace.py
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/py.typed
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 08:05:33.595195 vectice-23.2.5.0/src/vectice/utils/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      384 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/utils/api_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)      884 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/utils/automatic_link_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     5322 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/utils/common_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)      685 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/utils/configuration.py
--rw-r--r--   0 runner    (1001) docker     (123)     9491 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/utils/deprecation.py
--rw-r--r--   0 runner    (1001) docker     (123)      497 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/utils/instance_helper.py
--rw-r--r--   0 runner    (1001) docker     (123)     6533 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/utils/last_assets.py
--rw-r--r--   0 runner    (1001) docker     (123)     5359 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/utils/logging_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)      384 2023-06-14 08:05:24.000000 vectice-23.2.5.0/src/vectice/utils/vectice_ids_regex.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 08:05:33.579195 vectice-23.2.5.0/src/vectice.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1381 2023-06-14 08:05:33.000000 vectice-23.2.5.0/src/vectice.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     4481 2023-06-14 08:05:33.000000 vectice-23.2.5.0/src/vectice.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-14 08:05:33.000000 vectice-23.2.5.0/src/vectice.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      629 2023-06-14 08:05:33.000000 vectice-23.2.5.0/src/vectice.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-14 08:05:33.000000 vectice-23.2.5.0/src/vectice.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:17:15.555713 vectice-23.2.6.0/
+-rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 08:17:01.000000 vectice-23.2.6.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     1381 2023-06-28 08:17:15.555713 vectice-23.2.6.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)       94 2023-06-28 08:17:01.000000 vectice-23.2.6.0/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      122 2023-06-28 08:17:01.000000 vectice-23.2.6.0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       67 2023-06-28 08:17:15.555713 vectice-23.2.6.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     3160 2023-06-28 08:17:01.000000 vectice-23.2.6.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:17:15.531712 vectice-23.2.6.0/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:17:15.535712 vectice-23.2.6.0/src/vectice/
+-rw-r--r--   0 runner    (1001) docker     (123)     2681 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/__version__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:17:15.539713 vectice-23.2.6.0/src/vectice/api/
+-rw-r--r--   0 runner    (1001) docker     (123)      601 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3424 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/_auth.py
+-rw-r--r--   0 runner    (1001) docker     (123)      259 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7956 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/attachment.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19481 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)      456 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/compatibility.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4543 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/gql_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2629 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/gql_code.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3475 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/gql_code_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5126 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/gql_dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)      817 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/gql_entity_file.py
+-rw-r--r--   0 runner    (1001) docker     (123)      790 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/gql_feature_flag.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4710 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/gql_model.py
+-rw-r--r--   0 runner    (1001) docker     (123)      924 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/gql_organization.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1191 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/gql_user_workspace_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)      896 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/http_error.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12727 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/http_error_handlers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7729 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/iteration.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:17:15.543713 vectice-23.2.6.0/src/vectice/api/json/
+-rw-r--r--   0 runner    (1001) docker     (123)     2873 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1011 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/artifact_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)      238 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/attachment.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2081 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/code.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5900 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/code_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)      326 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/compatibility.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2076 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/dataset_register.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1428 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/dataset_representation.py
+-rw-r--r--   0 runner    (1001) docker     (123)      780 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/dataset_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)      911 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/dataset_version_representation.py
+-rw-r--r--   0 runner    (1001) docker     (123)      150 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/entity_file.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1099 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/files_metadata.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4540 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/iteration.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/last_assets.py
+-rw-r--r--   0 runner    (1001) docker     (123)      922 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/metric.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1674 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2157 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/model_register.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1268 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/model_representation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4369 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/model_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1328 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/model_version_representation.py
+-rw-r--r--   0 runner    (1001) docker     (123)      373 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/organization_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)      352 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/page.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1050 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/paged_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1784 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/phase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      961 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/project.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1549 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/property.py
+-rw-r--r--   0 runner    (1001) docker     (123)      692 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/public_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2815 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/step.py
+-rw-r--r--   0 runner    (1001) docker     (123)      510 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/user_and_workspace.py
+-rw-r--r--   0 runner    (1001) docker     (123)      235 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/user_declared_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)      606 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json/workspace.py
+-rw-r--r--   0 runner    (1001) docker     (123)       94 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/json_object.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1590 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/last_assets.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4819 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/phase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3046 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/project.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8182 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/rest_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6235 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/step.py
+-rw-r--r--   0 runner    (1001) docker     (123)      996 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2514 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/api/workspace.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23656 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/connection.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:17:15.547713 vectice-23.2.6.0/src/vectice/models/
+-rw-r--r--   0 runner    (1001) docker     (123)      684 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2377 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/attachment_container.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14757 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)      329 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/errors.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6202 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/git_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10638 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/iteration.py
+-rw-r--r--   0 runner    (1001) docker     (123)      954 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/metric.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8601 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/model.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11049 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/phase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6907 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/project.py
+-rw-r--r--   0 runner    (1001) docker     (123)      817 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/property.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:17:15.547713 vectice-23.2.6.0/src/vectice/models/representation/
+-rw-r--r--   0 runner    (1001) docker     (123)      560 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/representation/dataset_representation.py
+-rw-r--r--   0 runner    (1001) docker     (123)      351 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/representation/dataset_version_representation.py
+-rw-r--r--   0 runner    (1001) docker     (123)      510 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/representation/model_representation.py
+-rw-r--r--   0 runner    (1001) docker     (123)      459 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/representation/model_version_representation.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:17:15.551713 vectice-23.2.6.0/src/vectice/models/resource/
+-rw-r--r--   0 runner    (1001) docker     (123)      612 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4500 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7405 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/bigquery_resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2287 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/description.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5739 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/file_resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5695 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/gcs_resource.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:17:15.551713 vectice-23.2.6.0/src/vectice/models/resource/metadata/
+-rw-r--r--   0 runner    (1001) docker     (123)      658 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/metadata/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2592 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/metadata/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5568 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/metadata/column_metadata.py
+-rw-r--r--   0 runner    (1001) docker     (123)      531 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/metadata/dataframe_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2594 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/metadata/db_metadata.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2059 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/metadata/df_wrapper_default.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1438 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/metadata/df_wrapper_pandas.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5810 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/metadata/df_wrapper_pandas_default.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2375 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/metadata/df_wrapper_pyspark_pandas.py
+-rw-r--r--   0 runner    (1001) docker     (123)      895 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/metadata/df_wrapper_resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5744 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/metadata/df_wrapper_spark_df.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3014 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/metadata/files_metadata.py
+-rw-r--r--   0 runner    (1001) docker     (123)      775 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/metadata/pyspark_pandas_dataframe_typing.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4028 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/metadata/source.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7419 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/resource/s3_resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30604 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/step.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1327 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/step_dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1231 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/step_image.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1388 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/step_model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1930 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/step_number.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1764 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/step_string.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5956 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/models/workspace.py
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/py.typed
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:17:15.555713 vectice-23.2.6.0/src/vectice/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      384 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/utils/api_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)      884 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/utils/automatic_link_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5322 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/utils/common_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)      685 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/utils/configuration.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9491 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/utils/deprecation.py
+-rw-r--r--   0 runner    (1001) docker     (123)      497 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/utils/instance_helper.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6533 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/utils/last_assets.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5359 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/utils/logging_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)      384 2023-06-28 08:17:01.000000 vectice-23.2.6.0/src/vectice/utils/vectice_ids_regex.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:17:15.535712 vectice-23.2.6.0/src/vectice.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1381 2023-06-28 08:17:15.000000 vectice-23.2.6.0/src/vectice.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4561 2023-06-28 08:17:15.000000 vectice-23.2.6.0/src/vectice.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 08:17:15.000000 vectice-23.2.6.0/src/vectice.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      629 2023-06-28 08:17:15.000000 vectice-23.2.6.0/src/vectice.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-28 08:17:15.000000 vectice-23.2.6.0/src/vectice.egg-info/top_level.txt
```

### Comparing `vectice-23.2.5.0/LICENSE` & `vectice-23.2.6.0/LICENSE`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/PKG-INFO` & `vectice-23.2.6.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: vectice
-Version: 23.2.5.0
+Version: 23.2.6.0
 Summary: Vectice Python library
 Home-page: https://www.vectice.com
 Author: Vectice Inc.
 Author-email: sdk@vectice.com
 License: Apache License 2.0
 Keywords: Vectice,Client,API,Adapter
 Platform: Linux
```

### Comparing `vectice-23.2.5.0/setup.py` & `vectice-23.2.6.0/setup.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/__init__.py` & `vectice-23.2.6.0/src/vectice/__init__.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/__init__.py` & `vectice-23.2.6.0/src/vectice/api/__init__.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/_auth.py` & `vectice-23.2.6.0/src/vectice/api/_auth.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/attachment.py` & `vectice-23.2.6.0/src/vectice/api/attachment.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/client.py` & `vectice-23.2.6.0/src/vectice/api/client.py`

 * *Files 10% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 from vectice.api.compatibility import CompatibilityApi
 from vectice.api.gql_code import GqlCodeApi
 from vectice.api.gql_code_version import GqlCodeVersionApi
 from vectice.api.gql_dataset import GqlDatasetApi
 from vectice.api.gql_entity_file import GqlEntityFileApi
 from vectice.api.gql_feature_flag import GqlFeatureFlagApi
 from vectice.api.gql_model import GqlModelApi
+from vectice.api.gql_organization import GqlOrganizationApi
 from vectice.api.gql_user_workspace_api import UserAndDefaultWorkspaceApi
 from vectice.api.http_error_handlers import MissingReferenceError, VecticeException
 from vectice.api.iteration import IterationApi
 from vectice.api.json import (
     ArtifactName,
     CodeInput,
     CodeVersionCreateBody,
@@ -38,23 +39,25 @@
 from vectice.api.json.dataset_representation import DatasetRepresentationOutput
 from vectice.api.json.dataset_version import DatasetVersionOutput
 from vectice.api.json.dataset_version_representation import DatasetVersionRepresentationOutput
 from vectice.api.json.iteration import IterationStatus
 from vectice.api.json.metric import MetricInput
 from vectice.api.json.model_representation import ModelRepresentationOutput
 from vectice.api.json.model_version_representation import ModelVersionRepresentationOutput
+from vectice.api.json.organization_config import OrgConfigOutput
 from vectice.api.last_assets import LastAssetApi
 from vectice.api.phase import PhaseApi
 from vectice.api.project import ProjectApi
 from vectice.api.step import StepApi
 from vectice.api.version import VersionApi
 from vectice.api.workspace import WorkspaceApi
 from vectice.models.dataset import Dataset
 from vectice.models.representation.dataset_version_representation import DatasetVersionRepresentation
 from vectice.models.representation.model_version_representation import ModelVersionRepresentation
+from vectice.models.resource.metadata.base import MetadataSettings
 from vectice.utils.vectice_ids_regex import WORKSPACE_VID_REG
 
 if TYPE_CHECKING:
     from io import BytesIO, IOBase
 
     from requests import Response
 
@@ -82,14 +85,15 @@
         api_endpoint: str,
     ):
         self.auth = Auth(api_endpoint=api_endpoint, api_token=token)
         transport = RequestsHTTPTransport(url=self.auth.api_base_url + "/graphql", verify=self.auth.verify_certificate)
         logging.getLogger("gql.transport.requests").setLevel("WARNING")
         self._gql_client = GQLClient(transport=transport)
         self._logger = logging.getLogger(self.__class__.__name__)
+        self._org_config = self._get_org_config()
 
     @property
     def version_api(self) -> str:
         return __version__
 
     @property
     def version_backend(self) -> str:
@@ -98,14 +102,17 @@
             if version.artifact_name == ArtifactName.BACKEND:
                 return version.version
         raise ValueError("No version found for backend.")
 
     def check_compatibility(self) -> CompatibilityOutput:
         return CompatibilityApi(self.auth).check_version()
 
+    def _get_org_config(self) -> OrgConfigOutput:
+        return GqlOrganizationApi(self._gql_client, self.auth).get_organization_config()
+
     def list_projects(
         self,
         workspace: str,
     ) -> PagedResponse[ProjectOutput]:
         """List the projects in a workspace.
 
         Parameters:
@@ -313,21 +320,29 @@
     ) -> DatasetRegisterOutput:
         if dataset._has_bigquery_resource and self.is_feature_flag_enabled("bigquery-dataset-source") is False:
             raise VecticeException(DISABLED_FEATURE_FLAG_MESSAGE.format("bigquery-dataset-source"))
 
         if dataset._has_dataframe is True and self.is_feature_flag_enabled("dataset-dataframe") is False:
             raise VecticeException(DISABLED_FEATURE_FLAG_MESSAGE.format("dataset-dataframe"))
 
+        if dataset._has_spark_df is True and self.is_feature_flag_enabled("dataset-spark-dataframe") is False:
+            raise VecticeException(DISABLED_FEATURE_FLAG_MESSAGE.format("dataset-spark-dataframe"))
+
         name = self.get_dataset_name(dataset)
         derived_from = self.get_derived_from(dataset)
-        if isinstance(dataset.resource, tuple):
-            # modeling dataset
-            metadata_asdict = [data_source.metadata.asdict() for data_source in dataset.resource if data_source]
-        else:
-            metadata_asdict = [dataset.resource.metadata.asdict()]
+        resources = dataset.resource if isinstance(dataset.resource, tuple) else [dataset.resource]
+        metadata_asdict = []
+        for resource in resources:
+            if resource is not None:
+                resource.metadata.set_settings(
+                    MetadataSettings(
+                        minimum_rows_for_statistics=self._org_config.configuration.df_statistics_row_threshold
+                    )
+                )
+                metadata_asdict.append(resource.metadata.asdict())
 
         properties = (
             [vars(PropertyInput(prop.key, prop.value)) for prop in dataset.properties] if dataset.properties else None
         )
 
         dataset_register_input = DatasetRegisterInput(
             name=name,
```

### Comparing `vectice-23.2.5.0/src/vectice/api/gql_api.py` & `vectice-23.2.6.0/src/vectice/api/gql_api.py`

 * *Files 2% similar despite different names*

```diff
@@ -5,14 +5,15 @@
 from vectice.api.http_error_handlers import ClientErrorHandler
 from vectice.api.json import (
     CodeOutput,
     CodeVersionOutput,
     DatasetRegisterOutput,
     IterationOutput,
     ModelRegisterOutput,
+    OrgConfigOutput,
     PagedResponse,
     PhaseOutput,
     ProjectOutput,
     PublicConfigOutput,
     StepOutput,
     UserActivity,
     UserAndDefaultWorkspaceOutput,
@@ -85,14 +86,15 @@
             "ModelVersion": ModelVersionRepresentationOutput,
             "UserActivity": UserActivity,
             "Code": CodeOutput,
             "CodeVersion": CodeVersionOutput,
             "PublicConfigOutput": PublicConfigOutput,
             "UserAndDefaultWorkspaceOutput": UserAndDefaultWorkspaceOutput,
             "StepDefinition": StepOutput,
+            "OrgConfigOutput": OrgConfigOutput,
         }
 
 
 class GqlApi:
     def __init__(self, client: Client, auth: Auth):
         self.client = client
         self.auth = auth
```

### Comparing `vectice-23.2.5.0/src/vectice/api/gql_code.py` & `vectice-23.2.6.0/src/vectice/api/gql_code.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/gql_code_version.py` & `vectice-23.2.6.0/src/vectice/api/gql_code_version.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/gql_dataset.py` & `vectice-23.2.6.0/src/vectice/api/gql_dataset.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/gql_entity_file.py` & `vectice-23.2.6.0/src/vectice/api/gql_entity_file.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/gql_feature_flag.py` & `vectice-23.2.6.0/src/vectice/api/gql_feature_flag.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/gql_model.py` & `vectice-23.2.6.0/src/vectice/api/gql_model.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/gql_user_workspace_api.py` & `vectice-23.2.6.0/src/vectice/api/gql_user_workspace_api.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/http_error.py` & `vectice-23.2.6.0/src/vectice/api/http_error.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/http_error_handlers.py` & `vectice-23.2.6.0/src/vectice/api/http_error_handlers.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/iteration.py` & `vectice-23.2.6.0/src/vectice/api/iteration.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/__init__.py` & `vectice-23.2.6.0/src/vectice/api/json/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,14 +20,15 @@
     IterationStepArtifactInput,
     IterationStepArtifactType,
 )
 from vectice.api.json.last_assets import ActivityTargetType, UserActivity
 from vectice.api.json.metric import MetricInput, MetricOutput
 from vectice.api.json.model_register import ModelRegisterInput, ModelRegisterOutput, ModelType
 from vectice.api.json.model_version import ModelVersionInput, ModelVersionOutput, ModelVersionStatus
+from vectice.api.json.organization_config import OrgConfigOutput
 from vectice.api.json.page import Page
 from vectice.api.json.paged_response import PagedResponse
 from vectice.api.json.phase import PhaseInput, PhaseOutput
 from vectice.api.json.project import ProjectInput, ProjectOutput
 from vectice.api.json.property import PropertyInput, PropertyOutput
 from vectice.api.json.public_config import ArtifactName, PublicConfigOutput
 from vectice.api.json.step import StepInput, StepOutput
@@ -78,8 +79,9 @@
     "DatasetRegisterOutput",
     "ModelRegisterOutput",
     "ActivityTargetType",
     "UserActivity",
     "CodeVersionCreateBody",
     "ArtifactName",
     "PublicConfigOutput",
+    "OrgConfigOutput",
 ]
```

### Comparing `vectice-23.2.5.0/src/vectice/api/json/artifact_version.py` & `vectice-23.2.6.0/src/vectice/api/json/artifact_version.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/code.py` & `vectice-23.2.6.0/src/vectice/api/json/code.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/code_version.py` & `vectice-23.2.6.0/src/vectice/api/json/code_version.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/dataset_register.py` & `vectice-23.2.6.0/src/vectice/api/json/dataset_register.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/dataset_representation.py` & `vectice-23.2.6.0/src/vectice/api/json/dataset_representation.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/dataset_version.py` & `vectice-23.2.6.0/src/vectice/api/json/dataset_version.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/dataset_version_representation.py` & `vectice-23.2.6.0/src/vectice/api/json/dataset_version_representation.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/files_metadata.py` & `vectice-23.2.6.0/src/vectice/api/json/files_metadata.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/iteration.py` & `vectice-23.2.6.0/src/vectice/api/json/iteration.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/last_assets.py` & `vectice-23.2.6.0/src/vectice/api/json/last_assets.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/metric.py` & `vectice-23.2.6.0/src/vectice/api/json/metric.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/model.py` & `vectice-23.2.6.0/src/vectice/api/json/model.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/model_register.py` & `vectice-23.2.6.0/src/vectice/api/json/model_register.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/model_representation.py` & `vectice-23.2.6.0/src/vectice/api/json/model_representation.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/model_version.py` & `vectice-23.2.6.0/src/vectice/api/json/model_version.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/model_version_representation.py` & `vectice-23.2.6.0/src/vectice/api/json/model_version_representation.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/paged_response.py` & `vectice-23.2.6.0/src/vectice/api/json/paged_response.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/phase.py` & `vectice-23.2.6.0/src/vectice/api/json/phase.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/project.py` & `vectice-23.2.6.0/src/vectice/api/json/project.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/property.py` & `vectice-23.2.6.0/src/vectice/api/json/property.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/public_config.py` & `vectice-23.2.6.0/src/vectice/api/json/public_config.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/step.py` & `vectice-23.2.6.0/src/vectice/api/json/step.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/json/workspace.py` & `vectice-23.2.6.0/src/vectice/api/json/workspace.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/last_assets.py` & `vectice-23.2.6.0/src/vectice/api/last_assets.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/phase.py` & `vectice-23.2.6.0/src/vectice/api/phase.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/project.py` & `vectice-23.2.6.0/src/vectice/api/project.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/rest_api.py` & `vectice-23.2.6.0/src/vectice/api/rest_api.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/step.py` & `vectice-23.2.6.0/src/vectice/api/step.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/version.py` & `vectice-23.2.6.0/src/vectice/api/version.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/api/workspace.py` & `vectice-23.2.6.0/src/vectice/api/workspace.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/connection.py` & `vectice-23.2.6.0/src/vectice/connection.py`

 * *Files 4% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 
 import logging
 import os
 import re
 from contextlib import suppress
 from pathlib import Path
 from textwrap import dedent
-from typing import overload
+from typing import ClassVar, overload
 
 import dotenv
 from rich.table import Table
 
 from vectice.api import Client
 from vectice.api.http_error_handlers import InvalidIdError
 from vectice.api.json.iteration import IterationOutput
@@ -24,15 +24,14 @@
 from vectice.models.representation.dataset_representation import DatasetRepresentation
 from vectice.models.representation.dataset_version_representation import DatasetVersionRepresentation
 from vectice.models.representation.model_representation import ModelRepresentation
 from vectice.models.representation.model_version_representation import ModelVersionRepresentation
 from vectice.models.workspace import Workspace
 from vectice.utils.common_utils import _temp_print, hide_logs
 from vectice.utils.configuration import Configuration
-from vectice.utils.deprecation import deprecate
 from vectice.utils.last_assets import _connection_logging, _get_last_assets, _get_last_user_and_default_workspace
 from vectice.utils.logging_utils import CONNECTION_PROJECT_LOGGING, CONNECTION_WORKSPACE_LOGGING, format_description
 from vectice.utils.vectice_ids_regex import (
     DATASET_VERSION_VID_REG,
     DATASET_VID_REG,
     ITERATION_VID_REG,
     MODEL_VERSION_VID_REG,
@@ -82,15 +81,15 @@
 
         connection = vectice.connect()
         ```
 
     See [`Connection.connect`][vectice.connection.Connection.connect] for more info.
     """
 
-    USER_FILES_PATH = [
+    USER_FILES_PATH: ClassVar[list[str]] = [
         ".vectice",
         str(Path.home() / ".vectice"),
         ".env",
         str(Path.home() / ".env"),
         "/etc/vectice/api.cfg",
     ]
 
@@ -625,53 +624,7 @@
         return project_output
 
     def _get_workspace_from_str(self, workspace: str) -> Workspace:
         return self._build_workspace_from_output(self._client.get_workspace(workspace))
 
     def _get_project_from_str(self, project: str, workspace: str | None = None) -> Project:
         return self._build_project_from_output(self._client.get_project(project, workspace))
-
-    @staticmethod
-    @deprecate(
-        reason="Use _get_config_workspace(...) method instead.",
-        warn_at="23.2.4.0",
-        fail_at="23.2.5.0",
-        remove_at="23.2.6.0",
-    )
-    def _get_workspace(config) -> str | None:
-        try:
-            return Connection._get_config_item("WORKSPACE", config)
-        except ValueError:
-            return None
-
-    @staticmethod
-    @deprecate(
-        reason="Use _get_config_project(...) method instead.",
-        warn_at="23.2.4.0",
-        fail_at="23.2.5.0",
-        remove_at="23.2.6.0",
-    )
-    def _get_project(config) -> str | None:
-        try:
-            return str(Connection._get_config_item("PROJECT", config))
-        except ValueError:
-            return None
-
-    @deprecate(
-        reason="Use workspace(...) method instead.",
-        warn_at="23.2.4.0",
-        fail_at="23.2.5.0",
-        remove_at="23.2.6.0",
-    )
-    def get_workspace(self, workspace: str, user_name: str, host: str) -> Workspace:
-        workspace_output: Workspace = self._get_workspace_from_str(workspace)
-        return self._log_workspace(workspace_output, user_name, host)
-
-    @deprecate(
-        reason="Use project(...) method instead.",
-        warn_at="23.2.4.0",
-        fail_at="23.2.5.0",
-        remove_at="23.2.6.0",
-    )
-    def get_project(self, workspace: str, project: str, user_name: str, host: str) -> Project:
-        workspace_output: Workspace = self._get_workspace_from_str(workspace)
-        return self._log_project(workspace_output, project, user_name, host)
```

### Comparing `vectice-23.2.5.0/src/vectice/models/__init__.py` & `vectice-23.2.6.0/src/vectice/models/__init__.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/attachment_container.py` & `vectice-23.2.6.0/src/vectice/models/attachment_container.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/dataset.py` & `vectice-23.2.6.0/src/vectice/models/dataset.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,13 +1,14 @@
 from __future__ import annotations
 
 import logging
 from datetime import datetime
 from typing import Union
 
+from pyspark.sql.dataframe import DataFrame as SparkDF
 from typing_extensions import get_args
 
 from vectice.models.property import Property
 from vectice.models.representation.dataset_representation import DatasetRepresentation
 from vectice.models.representation.dataset_version_representation import DatasetVersionRepresentation
 from vectice.models.resource.base import Resource
 from vectice.models.resource.bigquery_resource import BigQueryResource
@@ -78,14 +79,33 @@
         self._has_dataframe = (
             (self._resource is not None and self._resource._dataframes is not None)
             or (self._training_resource is not None and self._training_resource._dataframes is not None)
             or (self._testing_resource is not None and self._testing_resource._dataframes is not None)
             or (self._validation_resource is not None and self._validation_resource._dataframes is not None)
         )
 
+        if self._has_dataframe:
+
+            def has_spark(resource: Resource | None) -> bool:
+                if resource is None or resource._dataframes is None:
+                    return False
+                for df in resource._dataframes:
+                    if isinstance(df, SparkDF):
+                        return True
+                return False
+
+            self._has_spark_df = (
+                has_spark(self._resource)
+                or has_spark(self._training_resource)
+                or has_spark(self._testing_resource)
+                or has_spark(self._validation_resource)
+            )
+        else:
+            self._has_spark_df = False
+
     @staticmethod
     def origin(
         resource: Resource,
         name: str | None = None,
         properties: dict[str, str | int] | list[Property] | Property | None = None,
         attachments: str | list[str] | None = None,
     ) -> Dataset:
```

### Comparing `vectice-23.2.5.0/src/vectice/models/git_version.py` & `vectice-23.2.6.0/src/vectice/models/git_version.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/iteration.py` & `vectice-23.2.6.0/src/vectice/models/iteration.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from __future__ import annotations
 
 import logging
 from contextlib import suppress
 from textwrap import dedent
-from typing import TYPE_CHECKING
+from typing import TYPE_CHECKING, ClassVar
 
 from rich.table import Table
 
 from vectice.api.http_error_handlers import NoStepsInPhaseError, VecticeException
 from vectice.api.json.iteration import (
     IterationInput,
     IterationStatus,
@@ -62,15 +62,15 @@
     To create a new iteration:
 
     ```python
     my_iteration = my_phase.create_iteration()
     ```
     """
 
-    __slots__ = [
+    __slots__: ClassVar[list[str]] = [
         "_id",
         "_index",
         "_phase",
         "_status",
         "_client",
         "_model",
         "_current_step",
```

### Comparing `vectice-23.2.5.0/src/vectice/models/metric.py` & `vectice-23.2.6.0/src/vectice/models/metric.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/model.py` & `vectice-23.2.6.0/src/vectice/models/model.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/phase.py` & `vectice-23.2.6.0/src/vectice/models/phase.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,29 +1,26 @@
 from __future__ import annotations
 
 import logging
 import re
 from textwrap import dedent
-from typing import TYPE_CHECKING, overload
+from typing import TYPE_CHECKING, ClassVar
 
 from rich.table import Table
 
 from vectice.api.http_error_handlers import (
     InvalidIdError,
-    InvalidReferenceError,
     LastIterationNotWritableError,
     MultipleActiveIterationsError,
 )
-from vectice.api.json.iteration import IterationStatus
+from vectice.api.json.iteration import IterationOutput, IterationStatus
 from vectice.api.json.phase import PhaseStatus
 from vectice.models.iteration import Iteration
 from vectice.utils.common_utils import _temp_print
-from vectice.utils.deprecation import deprecate
-from vectice.utils.last_assets import _get_last_user_and_default_workspace
-from vectice.utils.logging_utils import format_description, get_iteration_status
+from vectice.utils.logging_utils import get_iteration_status
 from vectice.utils.vectice_ids_regex import ITERATION_VID_REG
 
 if TYPE_CHECKING:
     from vectice import Connection
     from vectice.api import Client
     from vectice.models import Project, Workspace
 
@@ -71,15 +68,15 @@
     NOTE: **Phases and Steps Definitions are created in the Vectice App,
     Iterations are created from the Vectice Python API.**
 
     See the documentation of [Iterations][vectice.models.Iteration]
     for more information about iterations.
     """
 
-    __slots__ = [
+    __slots__: ClassVar[list[str]] = [
         "_id",
         "_project",
         "_name",
         "_index",
         "_status",
         "_client",
         "_current_iteration",
@@ -172,30 +169,14 @@
         """The phase's name, id, and index.
 
         Returns:
             A dictionary containing the `name`, `id`, and `index` items.
         """
         return {"name": self.name, "id": self.id, "index": self.index}
 
-    @property
-    @deprecate(
-        reason="Use list_iterations() instead.",
-        warn_at="23.2.3.0",
-        fail_at="23.2.5.0",
-        remove_at="23.2.6.0",
-    )
-    def iterations(self) -> list[Iteration]:
-        """The phase's iterations.
-
-        Returns:
-            The phase's iterations.
-        """
-        iteration_outputs = self._client.list_iterations(self.id)
-        return [Iteration(item.id, item.index, self, item.status) for item in iteration_outputs.list]
-
     def list_iterations(self, only_mine: bool = False, statuses: list[IterationStatus] | None = None) -> None:
         """Prints a list of iterations belonging to the phase in a tabular format, limited to the last 10 items.
 
         Parameters:
             only_mine: Display only the iterations where the user is the owner.
             statuses: Filter iterations on specified statuses.
 
@@ -231,119 +212,86 @@
         # For quick access to the list of iterations in the Vectice web app, visit:
         # {self._client.auth._API_BASE_URL}/phase/{self.id}/iterations?w={self.workspace.id}"""
         ).lstrip()
         _temp_print(description)
         _temp_print(table=rich_table)
         _temp_print(link)
 
-    @deprecate(
-        reason="This method is deprecated, to get your list of steps use the list_steps() of the iteration object.",
-        warn_at="23.2.4.0",
-        fail_at="23.2.5.0",
-        remove_at="23.2.6.0",
-    )
-    def list_steps(self) -> None:
-        """Prints a list of step definitions belonging to the phase in a tabular format, limited to the first 10 items. A link is provided to view the remaining step definitions.
+    def create_or_get_current_iteration(self) -> Iteration | None:
+        """Get or create an iteration.
 
-        > **Deprecated** <br>
-        > To get your list of steps use the list_steps() of the iteration object.
+        If your last updated iteration is writable (Not Started or In Progress), Vectice will return it.
+        Otherwise, Vectice will create a new one and return it.
+        If multiple writable iterations are found, Vectice will print a list of the iterations to complete or cancel.
 
         Returns:
-            None
-        """
-        steps_output = self._client.list_step_definitions(self.id)
-        user_name, _ = _get_last_user_and_default_workspace(self._client)
-
-        rich_table = Table(expand=True, show_edge=False)
+            An iteration or None if Vectice could not determine which iteration to retrieve.
 
-        rich_table.add_column("shortcut", justify="left", no_wrap=True, min_width=3, max_width=20)
-        rich_table.add_column("name", justify="left", no_wrap=True, min_width=5, max_width=10)
-        rich_table.add_column("description", justify="left", no_wrap=True, min_width=3, max_width=15)
-
-        for count, step in enumerate(steps_output, 1):
-            if count > 10:
-                break
-            rich_table.add_row(step.slug, step.name, format_description(step.description))
-        description = f"""There are {len(steps_output)} steps required in the phase {self.name!r} and a maximum of 10 steps are displayed in the table below:"""
-        link = dedent(
-            f"""
-        For quick access to the list of step definitions in the Vectice web app, visit:
-        {self._client.auth._API_BASE_URL}/phase/{self.id}/steps?w={self.workspace.id}"""
-        ).lstrip()
-        _temp_print(description)
-        _temp_print(table=rich_table)
-        _temp_print(link)
+        Raises:
+            VecticeException: When attempting to create an iteration but there isn't any step inside the phase.
+        """
+        try:
+            iteration_output = self._client.get_last_iteration(self.id)
+        except (LastIterationNotWritableError, MultipleActiveIterationsError) as e:
+            _logger.warning(str(e.value))
+            self.list_iterations(True, [IterationStatus.NotStarted, IterationStatus.InProgress])
+            return None
 
-    @overload
-    def iteration(self, index: int) -> Iteration:
-        ...
-
-    @overload
-    def iteration(self, index: int | str = "last") -> Iteration | None:
-        ...
+        return self._build_iteration_from_output_and_log(iteration_output)
 
-    def iteration(self, index: int | str = "last") -> Iteration | None:
+    def iteration(self, index: int | str) -> Iteration:
         """Get an iteration.
 
         Fetch and return an iteration by index or id.
-        If index is 'last' and last iteration is not writable, will create a new one and return it.
 
         Parameters:
-            index: The index or id of an existing iteration or 'last' to retrieve the last one.
+            index: The index or id of an existing iteration.
 
         Returns:
-            An iteration or None if Vectice could not determine which iteration to retrieve.
+            An iteration.
 
         Raises:
-            VecticeException: When attempting to create an iteration but there isn't any step inside the phase.
-            InvalidIdError: When index is a string not 'last' and not matching 'ITR-[int]'
+            InvalidIdError: When index is a string and not matching 'ITR-[int]'
             IterationIdError: Iteration with specified id does not exist.
             IterationIndexError: Iteration with specified index does not exist.
         """
         if isinstance(index, str):
-            if index == "last":
-                if self._client.is_feature_flag_enabled("iteration-method") is False:
-                    raise InvalidIdError("iteration", index)
-                try:
-                    iteration_output = self._client.get_last_iteration(self.id)
-                except (LastIterationNotWritableError, MultipleActiveIterationsError) as e:
-                    _logger.warning(str(e.value))
-                    self.list_iterations(True, [IterationStatus.NotStarted, IterationStatus.InProgress])
-                    return None
-            elif re.search(ITERATION_VID_REG, index):
+            if re.search(ITERATION_VID_REG, index):
                 iteration_output = self._client.get_iteration_by_id(index)
             else:
-                raise InvalidReferenceError("iteration", index)
+                raise InvalidIdError("iteration", index)
         else:
             iteration_output = self._client.get_iteration_by_index(self.id, index)
 
-        iteration_object = Iteration(
+        return self._build_iteration_from_output_and_log(iteration_output)
+
+    def _build_iteration_from_output_and_log(self, iteration_output: IterationOutput) -> Iteration:
+        iteration = Iteration(
             id=iteration_output.id,
             index=iteration_output.index,
             phase=self,
             status=iteration_output.status,
         )
-
-        base_log = dedent(f"Iteration number {iteration_output.index!r} successfully retrieved.")
-        if iteration_output.status in [IterationStatus.Completed, IterationStatus.Abandoned]:
+        base_log = dedent(f"Iteration number {iteration.index!r} successfully retrieved.")
+        if iteration.status in [IterationStatus.Completed, IterationStatus.Abandoned]:
             base_log += dedent(
                 f"""
-                WARN: Iteration is {iteration_object.status}."""
+                WARN: Iteration is {iteration.status}."""
             )
 
         logging_output = dedent(
             f"""
                 {base_log}
 
                 For quick access to the Iteration in the Vectice web app, visit:
-                {self._client.auth._API_BASE_URL}/browse/iteration/{iteration_object.id}"""
+                {self._client.auth._API_BASE_URL}/browse/iteration/{iteration.id}"""
         ).lstrip()
         _logger.info(logging_output)
-        self._current_iteration = iteration_object
-        return iteration_object
+        self._current_iteration = iteration
+        return iteration
 
     def create_iteration(self) -> Iteration:
         """Create a new iteration.
 
         Create and return an iteration.
 
         Returns:
```

### Comparing `vectice-23.2.5.0/src/vectice/models/project.py` & `vectice-23.2.6.0/src/vectice/models/project.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from __future__ import annotations
 
 import logging
 from textwrap import dedent
-from typing import TYPE_CHECKING
+from typing import TYPE_CHECKING, ClassVar
 
 from rich.table import Table
 
 from vectice.models.phase import Phase
 from vectice.utils.common_utils import _temp_print
 from vectice.utils.logging_utils import get_phase_status
 
@@ -44,15 +44,15 @@
     my_project = vectice.connect(..., workspace="Iris workspace", project="Iris project")
     ```
 
     See [`Connection.connect`][vectice.Connection.connect] to learn
     how to connect to Vectice.
     """
 
-    __slots__ = ["_id", "_workspace", "_name", "_description", "_phase", "_client", "_pointers"]
+    __slots__: ClassVar[list[str]] = ["_id", "_workspace", "_name", "_description", "_phase", "_client", "_pointers"]
 
     def __init__(
         self,
         id: str,
         workspace: Workspace,
         name: str,
         description: str | None = None,
```

### Comparing `vectice-23.2.5.0/src/vectice/models/property.py` & `vectice-23.2.6.0/src/vectice/models/property.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/representation/dataset_representation.py` & `vectice-23.2.6.0/src/vectice/models/representation/dataset_representation.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/__init__.py` & `vectice-23.2.6.0/src/vectice/models/resource/__init__.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/base.py` & `vectice-23.2.6.0/src/vectice/models/resource/base.py`

 * *Files 5% similar despite different names*

```diff
@@ -74,15 +74,15 @@
         self._paths = paths if isinstance(paths, list) else [paths]
 
         self._dataframes = dataframes if isinstance(dataframes, list) or dataframes is None else [dataframes]
         if self._dataframes is not None:
             for dataframe in self._dataframes:
                 if dataframe is not None and not isinstance(dataframe, get_args(DataFrameType)):
                     raise ValueError(
-                        f"Argument 'dataframe' of type '{type(dataframe)}' is invalid, only pandas DataFrame, Spark Dataframe and PySpark Pandas DataFrame are supported."
+                        f"Argument 'dataframe' of type '{type(dataframe)}' is invalid, only Pandas DataFrame is supported."
                     )
 
     @property
     def data(self) -> dict:
         """The resource's data.
 
         Returns:
```

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/bigquery_resource.py` & `vectice-23.2.6.0/src/vectice/models/resource/bigquery_resource.py`

 * *Files 1% similar despite different names*

```diff
@@ -38,15 +38,15 @@
         dataframes: DataFrameType | list[DataFrameType] | None = None,
         bq_client: BQClient | None = None,
     ):
         """Initialize a BigQuery resource.
 
         Parameters:
             paths: The paths to retrieve the datasets or the tables.
-            dataframes (Optional): The dataframes allowing vectice to optionally compute more metadata about this resource such as columns stats. (Support Spark, Pandas and Pandas on Spark)
+            dataframes (Optional): The dataframes allowing vectice to optionally compute more metadata about this resource such as columns stats. (Support Pandas)
             bq_client (Optional): The `google.cloud.bigquery.Client` to optionally retrieve file size, creation date and updated date (used for auto-versioning).
         """
         super().__init__(paths=paths, dataframes=dataframes)
         self.bq_client = bq_client
 
     def _fetch_data(self) -> dict[str, tuple[Table | None, DataFrameType | None]]:
         tables: dict[str, tuple[Table | None, DataFrameType | None]] = {}
```

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/description.py` & `vectice-23.2.6.0/src/vectice/models/resource/description.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/file_resource.py` & `vectice-23.2.6.0/src/vectice/models/resource/file_resource.py`

 * *Files 1% similar despite different names*

```diff
@@ -54,15 +54,15 @@
         paths: str | list[str],
         dataframes: DataFrameType | list[DataFrameType] | None = None,
     ):
         """Initialize a file resource.
 
         Parameters:
             paths: The paths of the files to wrap.
-            dataframes (Optional): The dataframes allowing vectice to optionally compute more metadata about this resource such as columns stats. (Support Spark, Pandas and Pandas on Spark)
+            dataframes (Optional): The dataframes allowing vectice to optionally compute more metadata about this resource such as columns stats. (Support Pandas)
 
         Examples:
             The following example shows how to wrap a CSV file
             called `iris.csv` in the current directory:
 
             ```python
             from vectice import FileResource
```

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/gcs_resource.py` & `vectice-23.2.6.0/src/vectice/models/resource/gcs_resource.py`

 * *Files 2% similar despite different names*

```diff
@@ -40,15 +40,15 @@
         dataframes: DataFrameType | list[DataFrameType] | None = None,
         gcs_client: Client | None = None,
     ):
         """Initialize a GCS resource.
 
         Parameters:
             uris: The uris of the referenced resources. Should follow the pattern 'gs://<bucket_name>/<file_path_inside_bucket>'
-            dataframes (Optional): The dataframes allowing vectice to optionally compute more metadata about this resource such as columns stats. (Support Spark, Pandas and Pandas on Spark)
+            dataframes (Optional): The dataframes allowing vectice to optionally compute more metadata about this resource such as columns stats. (Support Pandas)
             gcs_client (Optional): The `google.cloud.storage.Client` to optionally retrieve file size, creation date and updated date (used for auto-versioning) up to 5000 files.
         """
         super().__init__(paths=uris, dataframes=dataframes)
         self.gcs_client = gcs_client
 
         for uri in self._paths:
             if not re.search(GS_URI_REG, uri):
```

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/metadata/__init__.py` & `vectice-23.2.6.0/src/vectice/models/resource/metadata/__init__.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/metadata/column_metadata.py` & `vectice-23.2.6.0/src/vectice/models/resource/metadata/column_metadata.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/metadata/dataframe_config.py` & `vectice-23.2.6.0/src/vectice/models/resource/metadata/dataframe_config.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/metadata/db_metadata.py` & `vectice-23.2.6.0/src/vectice/models/resource/metadata/db_metadata.py`

 * *Files 7% similar despite different names*

```diff
@@ -28,14 +28,17 @@
             usage: The usage of the metadata.
             origin: The origin of the metadata.
         """
         super().__init__(size=size, type=DatasetSourceType.DB, usage=usage, origin=origin)
         self.dbs = dbs
 
     def asdict(self) -> dict:
+        for db in self.dbs:
+            if self._settings is not None:
+                db.set_settings(self._settings)
         return {
             **super().asdict(),
             "dbs": [db.asdict() for db in self.dbs],
         }
 
 
 class MetadataDB(Source):
@@ -54,15 +57,15 @@
         Parameters:
             name: The name of the table.
             columns: The columns that compose the table.
             rows_number: The number of row of the table.
             size: The size of the table.
             updated_date: The date of last update of the table.
             created_date: The creation date of the table.
-            dataframe (Optional): A dataframe allowing vectice to optionally compute more metadata about this resource such as columns stats, size, rows number and column numbers. (Support Spark, Pandas and Pandas on Spark)
+            dataframe (Optional): A dataframe allowing vectice to optionally compute more metadata about this resource such as columns stats, size, rows number and column numbers. (Support Pandas)
         """
         super().__init__(
             name=name,
             size=size,
             columns=list(columns),
             updated_date=updated_date,
             created_date=created_date,
```

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/metadata/df_wrapper_default.py` & `vectice-23.2.6.0/src/vectice/models/resource/metadata/df_wrapper_default.py`

 * *Files 24% similar despite different names*

```diff
@@ -6,15 +6,14 @@
 
 from pandas import Series
 from pyspark.sql.dataframe import DataFrame as SparkDF
 
 from vectice.models.resource.metadata.column_metadata import Column, Size
 from vectice.models.resource.metadata.dataframe_config import (
     MAX_COLUMNS_CAPTURE_STATS,
-    MIN_ROWS_CAPTURE_STATS,
     DataFrameTypeWithoutWrapper,
 )
 from vectice.models.resource.metadata.df_wrapper_resource import DataFrameWrapper
 
 _logger = logging.getLogger(__name__)
 
 
@@ -26,29 +25,31 @@
         super().__init__(dataframe)
 
     @abstractmethod
     def get_size(self) -> Size:
         pass
 
     @abstractmethod
-    def __capture_column_stats__(self, column, min_rows_to_compute_stats: int = MIN_ROWS_CAPTURE_STATS):
+    def __capture_column_stats__(self, column, minimum_rows_for_statistics: int):
         pass
 
-    def capture_columns(self) -> list[Column]:
+    def capture_columns(self, minimum_rows_for_statistics: int) -> list[Column]:
         columns: list[Column] = []
         dtypes = self.dataframe.dtypes
         column_names_with_types = dtypes.astype(str).to_dict().items() if isinstance(dtypes, Series) else dtypes
         for idx, (name, d_type) in enumerate(column_names_with_types):
             if idx >= MAX_COLUMNS_CAPTURE_STATS:
                 _logger.warning(
                     f"Statistics are only captured for the first {MAX_COLUMNS_CAPTURE_STATS} columns of your dataframe."
                 )
                 break
             column = self.dataframe.select(name) if isinstance(self.dataframe, SparkDF) else self.dataframe[name]
-            category_type, stats = self.__capture_column_stats__(column)
+            category_type, stats = self.__capture_column_stats__(
+                column, minimum_rows_for_statistics=minimum_rows_for_statistics
+            )
             columns.append(
                 Column(
                     name=name,
                     data_type=d_type if d_type != "object" else "string",
                     stats=stats,
                     category_type=category_type,
                 )
```

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/metadata/df_wrapper_pandas.py` & `vectice-23.2.6.0/src/vectice/models/resource/metadata/df_wrapper_pandas.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/metadata/df_wrapper_pandas_default.py` & `vectice-23.2.6.0/src/vectice/models/resource/metadata/df_wrapper_pandas_default.py`

 * *Files 5% similar despite different names*

```diff
@@ -11,18 +11,15 @@
     DateStat,
     MostCommon,
     NumericalStat,
     Quantiles,
     Size,
     TextStat,
 )
-from vectice.models.resource.metadata.dataframe_config import (
-    MIN_ROWS_CAPTURE_STATS,
-    DataFramePandasType,
-)
+from vectice.models.resource.metadata.dataframe_config import DataFramePandasType
 from vectice.models.resource.metadata.df_wrapper_default import DataFrameDefaultWrapper
 
 PT = TypeVar("PT", bound=DataFramePandasType)
 
 
 class DataFrameDefaultPandasWrapper(DataFrameDefaultWrapper[PT], Generic[PT]):
     rows: int
@@ -49,35 +46,39 @@
                 return True
         except TypeError:
             pass
 
         return False
 
     def __capture_column_stats__(
-        self, series: Series, min_rows_to_compute_stats: int = MIN_ROWS_CAPTURE_STATS
+        self, series: Series, minimum_rows_for_statistics: int
     ) -> tuple[ColumnCategoryType | None, TextStat | BooleanStat | NumericalStat | DateStat | None]:
         if api.types.is_bool_dtype(series):
             return (
                 ColumnCategoryType.BOOLEAN,
-                self.__compute_boolean_column_statistics__(series) if self.rows >= min_rows_to_compute_stats else None,
+                self.__compute_boolean_column_statistics__(series)
+                if self.rows >= minimum_rows_for_statistics
+                else None,
             )
         elif api.types.is_numeric_dtype(series):
             return (
                 ColumnCategoryType.NUMERICAL,
-                self.__compute_numeric_column_statistics__(series) if self.rows >= min_rows_to_compute_stats else None,
+                self.__compute_numeric_column_statistics__(series)
+                if self.rows >= minimum_rows_for_statistics
+                else None,
             )
         elif self.is_date_series(series):
             return (
                 ColumnCategoryType.DATE,
-                self.__compute_date_column_statistics__(series) if self.rows >= min_rows_to_compute_stats else None,
+                self.__compute_date_column_statistics__(series) if self.rows >= minimum_rows_for_statistics else None,
             )
         elif api.types.is_string_dtype(series) | api.types.is_categorical_dtype(series):
             return (
                 ColumnCategoryType.TEXT,
-                self.__compute_string_column_statistics__(series) if self.rows >= min_rows_to_compute_stats else None,
+                self.__compute_string_column_statistics__(series) if self.rows >= minimum_rows_for_statistics else None,
             )
         return None, None
 
     def __compute_boolean_column_statistics__(self, series: Series) -> BooleanStat:
         """Parse a dataframe series and return statistics about it.
 
         The computed statistics are:
```

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/metadata/df_wrapper_pyspark_pandas.py` & `vectice-23.2.6.0/src/vectice/models/resource/metadata/df_wrapper_pyspark_pandas.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/metadata/df_wrapper_resource.py` & `vectice-23.2.6.0/src/vectice/models/resource/metadata/df_wrapper_resource.py`

 * *Files 14% similar despite different names*

```diff
@@ -18,13 +18,13 @@
     abstact methods (`capture_columns()`, `get_size()`).
     """
 
     def __init__(self, dataframe: T):
         self.dataframe = dataframe
 
     @abstractmethod
-    def capture_columns(self) -> list[Column]:
+    def capture_columns(self, minimum_rows_for_statistics: int) -> list[Column]:
         pass
 
     @abstractmethod
     def get_size(self) -> Size:
         pass
```

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/metadata/df_wrapper_spark_df.py` & `vectice-23.2.6.0/src/vectice/models/resource/metadata/df_wrapper_spark_df.py`

 * *Files 8% similar despite different names*

```diff
@@ -12,51 +12,54 @@
     DateStat,
     MostCommon,
     NumericalStat,
     Quantiles,
     Size,
     TextStat,
 )
-from vectice.models.resource.metadata.dataframe_config import MIN_ROWS_CAPTURE_STATS
 from vectice.models.resource.metadata.df_wrapper_default import DataFrameDefaultWrapper
 
 
 class SparkDFWrapper(DataFrameDefaultWrapper[SparkDF]):
     def __init__(self, dataframe: SparkDF):
         super().__init__(dataframe)
         self.spark = SparkSession.builder.getOrCreate()
 
     def get_size(self) -> Size:
         self.rows: int = self.dataframe.count()
         self.columns_numbers: int = len(self.dataframe.columns)
 
         return Size(rows=self.rows, columns=self.columns_numbers)
 
-    def __capture_column_stats__(self, column: SparkDF, min_rows_to_compute_stats: int = MIN_ROWS_CAPTURE_STATS):
+    def __capture_column_stats__(self, column: SparkDF, minimum_rows_for_statistics: int):
         column_type = column.dtypes[0][1]
 
         if column_type == "boolean":
             return (
                 ColumnCategoryType.BOOLEAN,
-                self.__compute_boolean_column_statistics__(column) if self.rows >= min_rows_to_compute_stats else None,
+                self.__compute_boolean_column_statistics__(column)
+                if self.rows >= minimum_rows_for_statistics
+                else None,
             )
         elif column_type in ["tinyint", "smallint", "int", "bigint", "float", "double", "decimal"]:
             return (
                 ColumnCategoryType.NUMERICAL,
-                self.__compute_numeric_column_statistics__(column) if self.rows >= min_rows_to_compute_stats else None,
+                self.__compute_numeric_column_statistics__(column)
+                if self.rows >= minimum_rows_for_statistics
+                else None,
             )
         elif column_type == "date" or column_type == "timestamp":
             return (
                 ColumnCategoryType.DATE,
-                self.__compute_date_column_statistics__(column) if self.rows >= min_rows_to_compute_stats else None,
+                self.__compute_date_column_statistics__(column) if self.rows >= minimum_rows_for_statistics else None,
             )
         elif column_type in ["string", "char", "varchar"]:
             return (
                 ColumnCategoryType.TEXT,
-                self.__compute_string_column_statistics__(column) if self.rows >= min_rows_to_compute_stats else None,
+                self.__compute_string_column_statistics__(column) if self.rows >= minimum_rows_for_statistics else None,
             )
 
         return None, None
 
     def __compute_boolean_column_statistics__(self, column: SparkDF):
         true_count = column.filter(column[0] == lit(True)).count()
         false_count = column.filter(column[0] == lit(False)).count()
```

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/metadata/files_metadata.py` & `vectice-23.2.6.0/src/vectice/models/resource/metadata/files_metadata.py`

 * *Files 7% similar despite different names*

```diff
@@ -28,17 +28,19 @@
             usage: The usage of the dataset.
             origin: Where the dataset files come from.
         """
         super().__init__(size=size, type=DatasetSourceType.FILES, origin=origin, usage=usage)
         self.files = files
 
     def asdict(self) -> dict:
+        for file in self.files:
+            if self._settings is not None:
+                file.set_settings(self._settings)
         return {
             **super().asdict(),
-            "filesCount": len(self.files),
             "files": [file.asdict() for file in self.files],
         }
 
 
 class File(Source):
     """Describe a dataset file."""
 
@@ -60,15 +62,15 @@
             name: The name of the file.
             size: The size of the file.
             fingerprint: The hash of the file.
             created_date: The date of creation of the file.
             updated_date: The date of last update of the file.
             uri: The uri of the file.
             columns: The columns coming from the dataframe with the statistics.
-            dataframe (Optional): A dataframe allowing vectice to optionally compute more metadata about this resource such as columns stats, size, rows number and column numbers. (Support Spark, Pandas and Pandas on Spark)
+            dataframe (Optional): A dataframe allowing vectice to optionally compute more metadata about this resource such as columns stats, size, rows number and column numbers. (Support Pandas)
             content_type (Optional): HTTP 'Content-Type' header for this file.
         """
         super().__init__(
             name=name,
             size=size,
             columns=columns,
             created_date=created_date,
```

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/metadata/pyspark_pandas_dataframe_typing.py` & `vectice-23.2.6.0/src/vectice/models/resource/metadata/pyspark_pandas_dataframe_typing.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/metadata/source.py` & `vectice-23.2.6.0/src/vectice/models/resource/metadata/source.py`

 * *Files 7% similar despite different names*

```diff
@@ -3,16 +3,17 @@
 import logging
 from typing import Dict
 
 from pandas.core.frame import DataFrame as PandasDF
 from pyspark.pandas.frame import DataFrame as PysparkPandasDF
 from pyspark.sql.dataframe import DataFrame as SparkDF
 
+from vectice.models.resource.metadata.base import MetadataSettings
 from vectice.models.resource.metadata.column_metadata import Column
-from vectice.models.resource.metadata.dataframe_config import MIN_ROWS_CAPTURE_STATS, DataFrameType
+from vectice.models.resource.metadata.dataframe_config import DataFrameType
 from vectice.models.resource.metadata.df_wrapper_pandas import PandasDFWrapper
 from vectice.models.resource.metadata.df_wrapper_pyspark_pandas import PysparkPandasDFWrapper
 from vectice.models.resource.metadata.df_wrapper_resource import DataFrameWrapper
 from vectice.models.resource.metadata.df_wrapper_spark_df import SparkDFWrapper
 
 _logger = logging.getLogger(__name__)
 
@@ -31,52 +32,62 @@
 
         Parameters:
             name: The name of the source.
             size: The size of the source.
             columns: The columns that compose the source.
             updated_date: The date of last update of the source.
             created_date: The date of last update of the source.
-            dataframe (Optional): A dataframe allowing vectice to optionally compute more metadata about this resource such as columns stats, size, rows number and column numbers. (Support Spark, Pandas and Pandas on Spark)
+            dataframe (Optional): A dataframe allowing vectice to optionally compute more metadata about this resource such as columns stats, size, rows number and column numbers. (Support Pandas)
         """
         self.name = name
         self.size = size
         self.columns = columns
         self.created_date = created_date
         self.updated_date = updated_date
         self._dataframe = dataframe
         self._wrapper: PandasDFWrapper | PysparkPandasDFWrapper | SparkDFWrapper | None = None
+        self._settings = MetadataSettings()
 
         if isinstance(self._dataframe, PandasDF):
             self._wrapper = PandasDFWrapper(self._dataframe)
         elif isinstance(self._dataframe, SparkDF):
             self._wrapper = SparkDFWrapper(self._dataframe)
         elif isinstance(self._dataframe, PysparkPandasDF):
             _logger.warning(
                 "WARNING: Pandas on spark is not supported yet, pass a Pandas or a Spark DataFrame to get statistics."
             )
         elif isinstance(self._dataframe, DataFrameWrapper):
             _logger.warning(
                 "WARNING: Custom wrappers are not supported yet, pass a Pandas or a Spark DataFrame to get statistics."
             )
 
+    def set_settings(self, settings: MetadataSettings):
+        self._settings = settings
+
     def asdict(self) -> dict:
         size_info: Dict[str, int | float | None] = {"rowsNumber": None, "columnsNumber": None}
+        skipped_statistics = False
         if self._wrapper is not None:
             df_info = self._wrapper.get_size()
-            if df_info.rows < MIN_ROWS_CAPTURE_STATS:
+            minimum_rows_for_statistics = self._settings.minimum_rows_for_statistics
+            if df_info.rows < minimum_rows_for_statistics:
+                skipped_statistics = True
                 _logger.warning(
-                    f"Statistics are not captured if numbers of rows are below {MIN_ROWS_CAPTURE_STATS}, to keep the data anonymous."
+                    f"Statistics are not captured if numbers of rows are below {minimum_rows_for_statistics}, to keep the data anonymous."
                 )
             size_info = df_info.asdict()
 
         columns_list: list[Column] = self.columns if self.columns is not None else []
-        columns_list = self._wrapper.capture_columns() if self._wrapper is not None else columns_list
+        columns_list = (
+            self._wrapper.capture_columns(minimum_rows_for_statistics) if self._wrapper is not None else columns_list
+        )
         columns_list_dict = [col.asdict() for col in columns_list]
 
         return {
             **size_info,
             "size": self.size,
             "name": self.name,
             "updatedDate": self.updated_date,
             "createdDate": self.created_date,
             "columns": columns_list_dict,
+            "skippedStatistics": skipped_statistics,
         }
```

### Comparing `vectice-23.2.5.0/src/vectice/models/resource/s3_resource.py` & `vectice-23.2.6.0/src/vectice/models/resource/s3_resource.py`

 * *Files 1% similar despite different names*

```diff
@@ -43,15 +43,15 @@
         dataframes: DataFrameType | list[DataFrameType] | None = None,
         s3_client: Client | None = None,
     ):
         """Initialize an S3 resource.
 
         Parameters:
             uris: The uris of the resources to get. Should follow the pattern 's3://<bucket_name>/<file_path_inside_bucket>'
-            dataframes (Optional): The dataframes allowing vectice to optionally compute more metadata about this resource such as columns stats. (Support Spark, Pandas and Pandas on Spark)
+            dataframes (Optional): The dataframes allowing vectice to optionally compute more metadata about this resource such as columns stats. (Support Pandas)
             s3_client (Optional): The Amazon s3 client to optionally retrieve file size, creation date and updated date (used for auto-versioning) up to 5000 files.
         """
         super().__init__(paths=uris, dataframes=dataframes)
         self.s3_client = s3_client
 
         for uri in self._paths:
             if not re.search(S3_URI_REG, uri):
```

### Comparing `vectice-23.2.5.0/src/vectice/models/step.py` & `vectice-23.2.6.0/src/vectice/models/step.py`

 * *Files 4% similar despite different names*

```diff
@@ -156,14 +156,15 @@
             artifact_input, filename = self._create_image_artifact(value)
             artifact = IterationStepArtifact(
                 entity_file_id=artifact_input.id, type=IterationStepArtifactType.EntityFile
             )
             step = StepImage(self, value)
             self._iadd_comment_or_image(value, artifact)(self, _logger, filename)
         elif isinstance(value, (int, float, str)):
+            self._check_string_sanity(value)
             artifact_input = IterationStepArtifactInput(text=str(value), type="Comment")
             artifact = IterationStepArtifact(text=value, type=IterationStepArtifactType.Comment)
             step = StepString(self, value) if isinstance(value, str) else StepNumber(self, value)
             self._client.add_iteration_step_artifact(self._id, artifact_input)
             self._iadd_comment_or_image(value, artifact)(self, _logger)
         elif (
             isinstance(value, Model)
@@ -275,14 +276,18 @@
             step = StepDataset(self, dataset_artifact)
             _register_dataset_logging(self, dataset_output, value, attachments_output, _logger, copy_artifacts)
         else:
             raise TypeError(f"Expected Comment, Dataset or a Model, got {type(value)}")
 
         self._iteration._steps[self.name] = step
 
+    def _check_string_sanity(self, value: str):
+        if value == "":
+            raise VecticeException("Cannot assign an empty comment. Please provide a valid comment")
+
     def _iadd_comment_or_image(self, value, artifact: IterationStepArtifact):
         self.artifacts.append(artifact)
         self._warn_step_change(value)
         return _comment_or_image_logging
 
     def _keep_artifacts_and_update_step(self, step_type: StepType, value) -> None:
         artifacts = list(
@@ -337,14 +342,18 @@
             for artifact in artifacts
         ]
         # Ensure no crossover or duplicates
         maintain_artifacts = _maintain_and_add_artifacts(session_artifacts, existing_artifacts)
         self._client.update_iteration_step_artifact(self.id, step_type, artifacts=maintain_artifacts)
         self._warn_step_change(value)
 
+    def _flush_artifacts(self, step_type: StepType):
+        self._client.update_iteration_step_artifact(step_id=self.id, step_type=step_type, artifacts=[])
+        self.artifacts = []
+
     def _step_factory_and_update(self, value) -> Step | StepString | StepNumber | StepDataset | StepModel:
         # TODO cyclic imports
         from vectice.models.dataset import Dataset
         from vectice.models.model import Model
         from vectice.models.representation.dataset_representation import DatasetRepresentation
         from vectice.models.representation.dataset_version_representation import DatasetVersionRepresentation
         from vectice.models.representation.model_representation import ModelRepresentation
@@ -359,18 +368,19 @@
 
         if isinstance(value, (int, float)):
             self._update_iteration_step(StepType.StepNumber, value)
             return StepNumber(step=self, number=value)
 
         img_value = is_image(value)
         if img_value:
-            self._update_iteration_step(StepType.StepImage, img_value)
+            self._update_iteration_step(StepType.StepImage, img_value, True)
             return StepImage(self, img_value)
 
         if isinstance(value, str):
+            self._check_string_sanity(value)
             self._update_iteration_step(StepType.StepString, value)
             return StepString(self, string=value)
 
         if (
             isinstance(value, Model)
             or isinstance(value, ModelRepresentation)
             or isinstance(value, ModelVersionRepresentation)
@@ -498,33 +508,38 @@
                 id=data["datasetVersion"]["vecticeId"],
                 type=IterationStepArtifactType.DataSetVersion.name,
             )
         artifacts = [artifact]
         artifacts += attachments if attachments else []
         return artifacts
 
-    def _create_image_artifact(self, value: str | IOBase | Image) -> tuple[IterationStepArtifactInput, str]:
+    def _create_image_artifact(
+        self, value: str | IOBase | Image, flush_step_artifacts=False
+    ) -> tuple[IterationStepArtifactInput, str]:
+        if flush_step_artifacts is True:
+            self._flush_artifacts(step_type=StepType.StepImage)
+
         image, filename = _get_image_variables(value)
         try:
             artifact, *_ = self._client.create_phase_attachments(
                 [("file", (filename, image))], self.phase.id, self.project.id, self.id
             )
             if isinstance(image, BufferedReader):
                 image.close()
             return (
                 IterationStepArtifactInput(id=artifact["fileId"], type=IterationStepArtifactType.EntityFile.name),
                 filename,
             )
         except Exception as error:
             raise ValueError("Check the provided image.") from error
 
-    def _update_iteration_step(self, type: StepType, value):
+    def _update_iteration_step(self, type: StepType, value, flush_step_artifacts=False):
         filename: str | None = None
         if type is StepType.StepImage:
-            _, filename = self._create_image_artifact(value)
+            _, filename = self._create_image_artifact(value=value, flush_step_artifacts=flush_step_artifacts)
             self._warn_step_change(StepType.StepImage)
         elif isinstance(value, (str, int, float)):
             self._client.update_iteration_step_artifact(
                 self.id,
                 type,
                 [IterationStepArtifactInput(type="Comment", text=str(value))],
             )
```

### Comparing `vectice-23.2.5.0/src/vectice/models/step_dataset.py` & `vectice-23.2.6.0/src/vectice/models/step_dataset.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/step_image.py` & `vectice-23.2.6.0/src/vectice/models/step_image.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,25 +1,27 @@
 from __future__ import annotations
 
 import logging
 from io import IOBase
 
+from PIL.Image import Image
+
 from vectice.api.json.step import StepType
 from vectice.models.step import Step
 
 _logger = logging.getLogger(__name__)
 
 
 class StepImage(Step):
     """Model a Vectice step's image.
 
     A StepImage stores an image.
     """
 
-    def __init__(self, step: Step, image: str | IOBase | None = None):
+    def __init__(self, step: Step, image: str | IOBase | Image | None = None):
         """Initialize a step's image.
 
         Parameters:
             step: The step
             image: The step's image.
         """
         super().__init__(
@@ -28,20 +30,20 @@
             name=step.name,
             index=step.index,
             slug=step.slug,
             description=step._description,
             step_type=StepType.StepImage,
             artifacts=step.artifacts,
         )
-        self._image: str | IOBase | None = image
+        self._image: str | IOBase | Image | None = image
 
     def __repr__(self):
         return f"StepImage(name='{self.name}', id={self.id}, description='{self._description}', image={self.image})"
 
     @property
-    def image(self) -> str | IOBase | None:
+    def image(self) -> str | IOBase | Image | None:
         """The step's image.
 
         Returns:
             The step's image.
         """
         return self._image
```

### Comparing `vectice-23.2.5.0/src/vectice/models/step_model.py` & `vectice-23.2.6.0/src/vectice/models/step_model.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/step_number.py` & `vectice-23.2.6.0/src/vectice/models/step_number.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/step_string.py` & `vectice-23.2.6.0/src/vectice/models/step_string.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/models/workspace.py` & `vectice-23.2.6.0/src/vectice/models/workspace.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/utils/automatic_link_utils.py` & `vectice-23.2.6.0/src/vectice/utils/automatic_link_utils.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/utils/common_utils.py` & `vectice-23.2.6.0/src/vectice/utils/common_utils.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/utils/configuration.py` & `vectice-23.2.6.0/src/vectice/utils/configuration.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/utils/deprecation.py` & `vectice-23.2.6.0/src/vectice/utils/deprecation.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/utils/last_assets.py` & `vectice-23.2.6.0/src/vectice/utils/last_assets.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice/utils/logging_utils.py` & `vectice-23.2.6.0/src/vectice/utils/logging_utils.py`

 * *Files identical despite different names*

### Comparing `vectice-23.2.5.0/src/vectice.egg-info/PKG-INFO` & `vectice-23.2.6.0/src/vectice.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: vectice
-Version: 23.2.5.0
+Version: 23.2.6.0
 Summary: Vectice Python library
 Home-page: https://www.vectice.com
 Author: Vectice Inc.
 Author-email: sdk@vectice.com
 License: Apache License 2.0
 Keywords: Vectice,Client,API,Adapter
 Platform: Linux
```

### Comparing `vectice-23.2.5.0/src/vectice.egg-info/SOURCES.txt` & `vectice-23.2.6.0/src/vectice.egg-info/SOURCES.txt`

 * *Files 4% similar despite different names*

```diff
@@ -21,14 +21,15 @@
 src/vectice/api/gql_api.py
 src/vectice/api/gql_code.py
 src/vectice/api/gql_code_version.py
 src/vectice/api/gql_dataset.py
 src/vectice/api/gql_entity_file.py
 src/vectice/api/gql_feature_flag.py
 src/vectice/api/gql_model.py
+src/vectice/api/gql_organization.py
 src/vectice/api/gql_user_workspace_api.py
 src/vectice/api/http_error.py
 src/vectice/api/http_error_handlers.py
 src/vectice/api/iteration.py
 src/vectice/api/json_object.py
 src/vectice/api/last_assets.py
 src/vectice/api/phase.py
@@ -53,14 +54,15 @@
 src/vectice/api/json/last_assets.py
 src/vectice/api/json/metric.py
 src/vectice/api/json/model.py
 src/vectice/api/json/model_register.py
 src/vectice/api/json/model_representation.py
 src/vectice/api/json/model_version.py
 src/vectice/api/json/model_version_representation.py
+src/vectice/api/json/organization_config.py
 src/vectice/api/json/page.py
 src/vectice/api/json/paged_response.py
 src/vectice/api/json/phase.py
 src/vectice/api/json/project.py
 src/vectice/api/json/property.py
 src/vectice/api/json/public_config.py
 src/vectice/api/json/step.py
```

### Comparing `vectice-23.2.5.0/src/vectice.egg-info/requires.txt` & `vectice-23.2.6.0/src/vectice.egg-info/requires.txt`

 * *Files identical despite different names*


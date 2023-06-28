# Comparing `tmp/evadb-0.2.9.tar.gz` & `tmp/evadb-0.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "evadb-0.2.9.tar", last modified: Fri Jun  9 19:52:51 2023, max compression
+gzip compressed data, was "evadb-0.3.0.tar", last modified: Tue Jun 27 23:59:46 2023, max compression
```

## Comparing `evadb-0.2.9.tar` & `evadb-0.3.0.tar`

### file list

```diff
@@ -1,470 +1,472 @@
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.965659 evadb-0.2.9/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    11357 2023-06-08 04:02:21.000000 evadb-0.2.9/LICENSE.txt
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    14468 2023-06-09 19:52:51.965659 evadb-0.2.9/PKG-INFO
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    13794 2023-06-09 18:15:47.000000 evadb-0.2.9/README.md
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.921658 evadb-0.2.9/evadb/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      905 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/__init__.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.921658 evadb-0.2.9/evadb/binder/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/binder/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     8762 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/binder/binder_utils.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    15520 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/binder/statement_binder.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7982 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/binder/statement_binder_context.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.921658 evadb-0.2.9/evadb/catalog/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      618 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    19317 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/catalog_manager.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3346 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/catalog_type.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     9337 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/catalog_utils.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.921658 evadb-0.2.9/evadb/catalog/models/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/models/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1503 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/models/association_models.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4751 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/models/base_model.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4551 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/models/column_catalog.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2871 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/models/index_catalog.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2441 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/models/table_catalog.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3022 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/models/udf_cache_catalog.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3101 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/models/udf_catalog.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1804 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/models/udf_cost_catalog.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3923 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/models/udf_io_catalog.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2205 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/models/udf_metadata_catalog.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6789 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/models/utils.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2126 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/schema_utils.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.925658 evadb-0.2.9/evadb/catalog/services/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/services/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1291 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/services/base_service.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3377 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/services/column_catalog_service.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2970 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/services/index_catalog_service.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4961 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/services/table_catalog_service.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3999 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/services/udf_cache_catalog_service.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3249 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/services/udf_catalog_service.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3036 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/services/udf_cost_catalog_service.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2934 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/services/udf_io_catalog_service.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2226 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/services/udf_metadata_catalog_service.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2732 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/catalog/sql_config.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.925658 evadb-0.2.9/evadb/configuration/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      622 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/configuration/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5035 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/configuration/bootstrap_environment.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2508 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/configuration/configuration_manager.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1031 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/configuration/constants.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      884 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/constants.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1964 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/database.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      568 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/evadb.yml
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2018 2023-06-08 22:16:07.000000 evadb-0.2.9/evadb/evadb_cmd_client.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2685 2023-06-08 22:16:07.000000 evadb-0.2.9/evadb/evadb_server.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.929658 evadb-0.2.9/evadb/executor/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      617 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3803 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/abstract_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2324 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/apply_and_merge_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2035 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/create_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5099 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/create_index_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1952 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/create_mat_view_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7186 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/create_udf_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4740 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/delete_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4999 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/drop_object_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3619 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/exchange_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3025 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/execution_context.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5373 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/executor_utils.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1596 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/explain_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2005 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/function_scan_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1897 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/groupby_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1944 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/hash_join_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2247 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/insert_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1688 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/join_build_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1843 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/lateral_join_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1655 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/limit_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3084 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/load_csv_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1742 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/load_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5950 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/load_multimedia_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1616 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/nested_loop_join_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4263 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/orderby_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     8310 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/plan_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1716 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/pp_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1367 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/predicate_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1362 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/project_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2078 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/ray_utils.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1267 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/rename_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1485 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/sample_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1918 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/seq_scan_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1846 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/show_info_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2622 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/storage_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1336 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/union_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4395 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/executor/vector_index_scan_executor.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.929658 evadb-0.2.9/evadb/expression/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      619 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/expression/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5561 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/expression/abstract_expression.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3979 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/expression/aggregation_expression.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1624 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/expression/arithmetic_expression.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4357 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/expression/comparison_expression.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2550 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/expression/constant_value_expression.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    10445 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/expression/expression_utils.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    10046 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/expression/function_expression.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3059 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/expression/logical_expression.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4693 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/expression/tuple_value_expression.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.929658 evadb-0.2.9/evadb/interfaces/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/interfaces/__init__.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.929658 evadb-0.2.9/evadb/interfaces/relational/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/interfaces/relational/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    12597 2023-06-09 01:44:52.000000 evadb-0.2.9/evadb/interfaces/relational/db.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7741 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/interfaces/relational/relation.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4628 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/interfaces/relational/utils.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.929658 evadb-0.2.9/evadb/models/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      637 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/models/__init__.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.929658 evadb-0.2.9/evadb/models/catalog/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/models/catalog/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1336 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/models/catalog/frame_info.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      859 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/models/catalog/properties.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.929658 evadb-0.2.9/evadb/models/server/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/models/server/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1971 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/models/server/response.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.929658 evadb-0.2.9/evadb/models/storage/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/models/storage/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    15331 2023-06-09 18:53:37.000000 evadb-0.2.9/evadb/models/storage/batch.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.933658 evadb-0.2.9/evadb/optimizer/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      624 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3269 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/binder.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2145 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/cost_model.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3460 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/group.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2677 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/group_expression.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4347 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/memo.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    36735 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/operators.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4040 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/optimizer_context.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      986 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/optimizer_task_stack.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    12600 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/optimizer_tasks.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    11290 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/optimizer_utils.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4281 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/plan_generator.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1171 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/property.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.933658 evadb-0.2.9/evadb/optimizer/rules/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/rules/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1023 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/rules/pattern.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    49299 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/rules/rules.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7376 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/rules/rules_base.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7511 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/rules/rules_manager.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    13358 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/optimizer/statement_to_opr_converter.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.937658 evadb-0.2.9/evadb/parser/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1362 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/alias.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2754 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/create_index_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2884 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/create_mat_view_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5324 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/create_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4436 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/create_udf_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2058 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/delete_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2131 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/drop_object_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    19687 2023-06-08 15:06:21.000000 evadb-0.2.9/evadb/parser/evadb.lark
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1390 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/explain_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2932 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/insert_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1724 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_parser.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.937658 evadb-0.2.9/evadb/parser/lark_visitor/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2685 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_visitor/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2171 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_visitor/_common_clauses_ids.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    10840 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_visitor/_create_statements.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1410 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_visitor/_delete_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2007 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_visitor/_drop_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1010 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_visitor/_explain_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4684 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_visitor/_expressions.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5780 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_visitor/_functions.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2473 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_visitor/_insert_statements.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2247 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_visitor/_load_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      938 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_visitor/_rename_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2149 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_visitor/_select_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1118 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_visitor/_show_statements.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     9481 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/lark_visitor/_table_sources.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3224 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/load_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1233 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/parser.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2015 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/rename_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6258 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/select_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1466 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/show_statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1430 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/statement.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     8649 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/table_ref.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1892 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/types.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4271 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/parser/utils.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.941658 evadb-0.2.9/evadb/plan_nodes/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      616 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1699 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/abstract_join_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3457 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/abstract_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1463 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/abstract_scan_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1940 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/apply_and_merge_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2483 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/create_index_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2086 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/create_mat_view_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2210 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/create_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3483 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/create_udf_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1961 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/delete_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1499 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/drop_object_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2063 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/exchange_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1039 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/explain_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1763 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/function_scan_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1507 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/groupby_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1722 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/hash_join_build_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2191 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/hash_join_probe_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2033 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/insert_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1418 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/lateral_join_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1476 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/limit_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2720 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/load_data_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1520 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/nested_loop_join_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1570 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/orderby_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1185 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/pp_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1253 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/predicate_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1257 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/project_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1624 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/rename_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1477 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/sample_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1768 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/seq_scan_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1209 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/show_info_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4431 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/storage_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1408 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/types.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1251 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/union_plan.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2732 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/plan_nodes/vector_index_scan_plan.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.941658 evadb-0.2.9/evadb/readers/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/readers/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2328 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/readers/abstract_reader.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2656 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/readers/csv_reader.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6001 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/readers/decord_reader.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.941658 evadb-0.2.9/evadb/readers/document/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/readers/document/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1473 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/readers/document/document_reader.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1981 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/readers/document/registry.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.941658 evadb-0.2.9/evadb/readers/image/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/readers/image/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1071 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/readers/image/opencv_image_reader.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2054 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/readers/pdf_reader.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.941658 evadb-0.2.9/evadb/server/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      625 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/server/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3474 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/server/command_handler.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3609 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/server/interpreter.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3357 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/server/server.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.941658 evadb-0.2.9/evadb/storage/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      618 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/storage/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6187 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/storage/abstract_media_storage_engine.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2497 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/storage/abstract_storage_engine.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1785 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/storage/document_storage_engine.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1789 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/storage/image_storage_engine.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1764 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/storage/pdf_storage_engine.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     9483 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/storage/sqlite_storage_engine.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2066 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/storage/storage_engine.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2562 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/storage/video_storage_engine.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.945659 evadb-0.2.9/evadb/third_party/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      607 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/third_party/__init__.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.945659 evadb-0.2.9/evadb/third_party/huggingface/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      614 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/third_party/huggingface/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1428 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/third_party/huggingface/binder.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6485 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/third_party/huggingface/create.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2625 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/third_party/huggingface/model.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.945659 evadb-0.2.9/evadb/third_party/vector_stores/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      609 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/third_party/vector_stores/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3288 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/third_party/vector_stores/faiss.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2964 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/third_party/vector_stores/qdrant.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1378 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/third_party/vector_stores/types.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1608 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/third_party/vector_stores/utils.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.945659 evadb-0.2.9/evadb/udfs/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      618 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/__init__.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.945659 evadb-0.2.9/evadb/udfs/abstract/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      627 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/abstract/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2446 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/abstract/abstract_udf.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4058 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/abstract/hf_abstract_udf.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3853 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/abstract/pytorch_abstract_udf.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3928 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/abstract/tracker_abstract_udf.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3468 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/asl_action_recognition.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3600 2023-06-09 01:44:52.000000 evadb-0.2.9/evadb/udfs/chatgpt.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.945659 evadb-0.2.9/evadb/udfs/decorators/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/decorators/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2192 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/decorators/decorators.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.949659 evadb-0.2.9/evadb/udfs/decorators/io_descriptors/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/decorators/io_descriptors/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2761 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/decorators/io_descriptors/abstract_types.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3386 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/decorators/io_descriptors/data_types.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2073 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/decorators/utils.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5482 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/emotion_detector.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2547 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/face_detector.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6022 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/fastrcnn_object_detector.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1826 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/feature_extractor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1030 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/gpu_compatible.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3532 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/mnist_image_classifier.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2204 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/mvit_action_recognition.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.949659 evadb-0.2.9/evadb/udfs/ndarray/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      640 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/ndarray/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2482 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/ndarray/annotate.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2572 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/ndarray/array_count.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1651 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/ndarray/crop.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1183 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/ndarray/fuzzy_join.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2210 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/ndarray/gaussian_blur.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2212 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/ndarray/horizontal_flip.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1561 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/ndarray/open.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1786 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/ndarray/similarity.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2149 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/ndarray/to_grayscale.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2198 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/ndarray/vertical_flip.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2756 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/ocr_extractor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2705 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/saliency_feature_extractor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3182 2023-06-09 18:53:37.000000 evadb-0.2.9/evadb/udfs/sentence_feature_extractor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2177 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/sentence_transformer_feature_extractor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2911 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/sift_feature_extractor.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.949659 evadb-0.2.9/evadb/udfs/trackers/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      638 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/trackers/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2377 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/trackers/nor_fair.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.949659 evadb-0.2.9/evadb/udfs/tutorials/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      638 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/tutorials/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     8636 2023-06-09 01:44:52.000000 evadb-0.2.9/evadb/udfs/udf_bootstrap_queries.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3871 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/udfs/yolo_object_detector.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.949659 evadb-0.2.9/evadb/utils/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      615 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/utils/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      911 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/utils/errors.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6763 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/utils/generic_utils.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1958 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/utils/kv_cache.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      987 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/utils/logging_manager.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1390 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/utils/math_utils.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1564 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/utils/s3_utils.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1696 2023-06-08 22:16:06.000000 evadb-0.2.9/evadb/utils/stats.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      123 2023-06-09 19:52:49.000000 evadb-0.2.9/evadb/version.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.921658 evadb-0.2.9/evadb.egg-info/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    14468 2023-06-09 19:52:51.000000 evadb-0.2.9/evadb.egg-info/PKG-INFO
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    14227 2023-06-09 19:52:51.000000 evadb-0.2.9/evadb.egg-info/SOURCES.txt
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)        1 2023-06-09 19:52:51.000000 evadb-0.2.9/evadb.egg-info/dependency_links.txt
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)       96 2023-06-09 19:52:51.000000 evadb-0.2.9/evadb.egg-info/entry_points.txt
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1436 2023-06-09 19:52:51.000000 evadb-0.2.9/evadb.egg-info/requires.txt
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)       23 2023-06-09 19:52:51.000000 evadb-0.2.9/evadb.egg-info/top_level.txt
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)       90 2023-06-08 04:02:21.000000 evadb-0.2.9/pyproject.toml
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)       38 2023-06-09 19:52:51.965659 evadb-0.2.9/setup.cfg
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4722 2023-06-09 19:45:40.000000 evadb-0.2.9/setup.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.949659 evadb-0.2.9/test/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/__init__.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.949659 evadb-0.2.9/test/benchmark_tests/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/benchmark_tests/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1265 2023-06-08 22:16:06.000000 evadb-0.2.9/test/benchmark_tests/conftest.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6893 2023-06-08 22:16:06.000000 evadb-0.2.9/test/benchmark_tests/test_benchmark_pytorch.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.949659 evadb-0.2.9/test/binder/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/binder/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    14199 2023-06-08 22:16:06.000000 evadb-0.2.9/test/binder/test_statement_binder.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     8056 2023-06-08 22:16:06.000000 evadb-0.2.9/test/binder/test_statement_binder_context.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.953659 evadb-0.2.9/test/catalog/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/catalog/__init__.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.953659 evadb-0.2.9/test/catalog/models/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/catalog/models/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7252 2023-06-08 22:16:06.000000 evadb-0.2.9/test/catalog/models/test_models.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7355 2023-06-08 22:16:06.000000 evadb-0.2.9/test/catalog/test_catalog_manager.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1406 2023-06-08 22:16:06.000000 evadb-0.2.9/test/catalog/test_column_type.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.953659 evadb-0.2.9/test/executor/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/executor/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1110 2023-06-08 22:16:06.000000 evadb-0.2.9/test/executor/test_abstract_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4081 2023-06-08 22:16:06.000000 evadb-0.2.9/test/executor/test_create_udf_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4273 2023-06-08 22:16:06.000000 evadb-0.2.9/test/executor/test_execution_context.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4747 2023-06-08 22:16:06.000000 evadb-0.2.9/test/executor/test_limit_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2936 2023-06-08 22:16:06.000000 evadb-0.2.9/test/executor/test_orderby_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     9933 2023-06-08 22:16:06.000000 evadb-0.2.9/test/executor/test_plan_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1867 2023-06-08 22:16:06.000000 evadb-0.2.9/test/executor/test_sample_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3037 2023-06-08 22:16:06.000000 evadb-0.2.9/test/executor/test_seq_scan_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      851 2023-06-08 22:16:06.000000 evadb-0.2.9/test/executor/utils.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.953659 evadb-0.2.9/test/expression/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/expression/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3734 2023-06-08 22:16:06.000000 evadb-0.2.9/test/expression/test_abstract_expression.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5159 2023-06-08 22:16:06.000000 evadb-0.2.9/test/expression/test_aggregation.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2985 2023-06-08 22:16:06.000000 evadb-0.2.9/test/expression/test_arithmetic.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5590 2023-06-08 22:16:06.000000 evadb-0.2.9/test/expression/test_comparison.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2883 2023-06-08 22:16:06.000000 evadb-0.2.9/test/expression/test_expression_tree.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7571 2023-06-08 22:16:06.000000 evadb-0.2.9/test/expression/test_expression_utils.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2701 2023-06-08 22:16:06.000000 evadb-0.2.9/test/expression/test_function_expression.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    10256 2023-06-08 22:16:06.000000 evadb-0.2.9/test/expression/test_logical.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.957659 evadb-0.2.9/test/integration_tests/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3703 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_array_count.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6124 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_create_index_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3900 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_create_table_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5205 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_delete_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7102 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_drop_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2373 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_error_handling_with_ray.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3683 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_explain_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2862 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_fuzzy_join.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    17573 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_huggingface_udfs.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3964 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_insert_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3100 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_like.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    21912 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_load_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2024 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_load_pdf_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7740 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_mat_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2667 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_open.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    11073 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_optimizer_rules.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    15580 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_pytorch.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3083 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_rename_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    10854 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_reuse.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5321 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_s3_load_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2361 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_saliency.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    31947 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_select_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3452 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_show_info_executor.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    15009 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_similarity.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    12511 2023-06-08 22:16:06.000000 evadb-0.2.9/test/integration_tests/test_udf_executor.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.957659 evadb-0.2.9/test/interfaces/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/interfaces/__init__.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.957659 evadb-0.2.9/test/interfaces/relational/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/interfaces/relational/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    12386 2023-06-08 22:16:07.000000 evadb-0.2.9/test/interfaces/relational/test_relational_api.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1606 2023-06-08 22:16:06.000000 evadb-0.2.9/test/markers.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.957659 evadb-0.2.9/test/models/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/models/__init__.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.957659 evadb-0.2.9/test/models/catalog/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/models/catalog/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1016 2023-06-08 22:16:06.000000 evadb-0.2.9/test/models/catalog/test_frame_info.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.957659 evadb-0.2.9/test/models/storage/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/models/storage/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5925 2023-06-08 22:16:06.000000 evadb-0.2.9/test/models/storage/test_batch.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.957659 evadb-0.2.9/test/optimizer/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/optimizer/__init__.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.961659 evadb-0.2.9/test/optimizer/rules/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/optimizer/rules/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    11754 2023-06-08 22:16:06.000000 evadb-0.2.9/test/optimizer/rules/test_rules.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4246 2023-06-08 22:16:06.000000 evadb-0.2.9/test/optimizer/test_binder.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2329 2023-06-08 22:16:06.000000 evadb-0.2.9/test/optimizer/test_cascade_optimizer.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4512 2023-06-08 22:16:06.000000 evadb-0.2.9/test/optimizer/test_cost_model.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2697 2023-06-08 22:16:06.000000 evadb-0.2.9/test/optimizer/test_group.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2002 2023-06-08 22:16:06.000000 evadb-0.2.9/test/optimizer/test_memo.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1053 2023-06-08 22:16:06.000000 evadb-0.2.9/test/optimizer/test_optimizer_context.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5668 2023-06-08 22:16:06.000000 evadb-0.2.9/test/optimizer/test_optimizer_task.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2008 2023-06-08 22:16:06.000000 evadb-0.2.9/test/optimizer/test_optimizer_utils.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    13113 2023-06-08 22:16:06.000000 evadb-0.2.9/test/optimizer/test_statement_to_opr_converter.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.961659 evadb-0.2.9/test/parser/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/parser/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    35848 2023-06-08 22:16:06.000000 evadb-0.2.9/test/parser/test_parser.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7797 2023-06-08 22:16:06.000000 evadb-0.2.9/test/parser/test_parser_statements.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.961659 evadb-0.2.9/test/plan_nodes/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/plan_nodes/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5987 2023-06-08 22:16:06.000000 evadb-0.2.9/test/plan_nodes/test_plan.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.961659 evadb-0.2.9/test/readers/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/readers/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1694 2023-06-08 22:16:06.000000 evadb-0.2.9/test/readers/test_csv_reader.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     8128 2023-06-08 22:16:06.000000 evadb-0.2.9/test/readers/test_decord_reader.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.961659 evadb-0.2.9/test/server/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/server/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1278 2023-06-08 22:16:06.000000 evadb-0.2.9/test/server/test_command_handler.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5221 2023-06-08 22:16:06.000000 evadb-0.2.9/test/server/test_db_api.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2617 2023-06-08 22:16:06.000000 evadb-0.2.9/test/server/test_interpreter.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2171 2023-06-08 22:16:06.000000 evadb-0.2.9/test/server/test_server.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.961659 evadb-0.2.9/test/storage/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/storage/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4512 2023-06-08 22:16:06.000000 evadb-0.2.9/test/storage/test_sqlite_storage_engine.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4165 2023-06-08 22:16:06.000000 evadb-0.2.9/test/storage/test_video_storage.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3341 2023-06-08 22:16:06.000000 evadb-0.2.9/test/test_eva_cmd_client.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1310 2023-06-08 22:16:06.000000 evadb-0.2.9/test/test_eva_imports.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1427 2023-06-08 22:16:06.000000 evadb-0.2.9/test/test_eva_server.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.961659 evadb-0.2.9/test/udfs/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      640 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/__init__.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.961659 evadb-0.2.9/test/udfs/decorators/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/decorators/__init__.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.961659 evadb-0.2.9/test/udfs/decorators/io_descriptors/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/decorators/io_descriptors/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7437 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/decorators/io_descriptors/test_descriptors.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2145 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/decorators/test_decorators.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.961659 evadb-0.2.9/test/udfs/ndarray/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      650 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/ndarray/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1852 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/ndarray/test_annotate.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      853 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/ndarray/test_array_count.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2414 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/ndarray/test_crop.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2026 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/ndarray/test_flips.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1671 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/ndarray/test_gaussian_blur.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2264 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/ndarray/test_open.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1668 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/ndarray/test_to_grayscale.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4424 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/test_abstract_udf.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4083 2023-06-09 01:44:52.000000 evadb-0.2.9/test/udfs/test_chatgpt.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2164 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/test_emotion_detector.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3363 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/test_facenet_udf.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2558 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/test_fastrcnn_object_detector.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2774 2023-06-08 22:16:06.000000 evadb-0.2.9/test/udfs/test_yolo_object_detector.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    17789 2023-06-08 22:16:06.000000 evadb-0.2.9/test/util.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.965659 evadb-0.2.9/test/utils/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.2.9/test/utils/__init__.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3939 2023-06-08 22:16:06.000000 evadb-0.2.9/test/utils/test_generic_utils.py
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2283 2023-06-08 22:16:06.000000 evadb-0.2.9/test/utils/test_timer.py
-drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-09 19:52:51.965659 evadb-0.2.9/third_party/
--rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-08 04:02:21.000000 evadb-0.2.9/third_party/__init__.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.689784 evadb-0.3.0/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    11357 2023-06-08 04:02:21.000000 evadb-0.3.0/LICENSE.txt
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    13108 2023-06-27 23:59:46.689784 evadb-0.3.0/PKG-INFO
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    12298 2023-06-27 00:54:48.000000 evadb-0.3.0/README.md
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.645783 evadb-0.3.0/evadb/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      905 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/__init__.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.645783 evadb-0.3.0/evadb/binder/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/binder/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     8749 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/binder/binder_utils.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    14313 2023-06-27 00:54:47.000000 evadb-0.3.0/evadb/binder/statement_binder.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7978 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/binder/statement_binder_context.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.649783 evadb-0.3.0/evadb/catalog/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      618 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    19545 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/catalog/catalog_manager.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3373 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/catalog/catalog_type.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    10319 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/catalog/catalog_utils.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.649783 evadb-0.3.0/evadb/catalog/models/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/models/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1503 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/models/association_models.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4751 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/models/base_model.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4551 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/models/column_catalog.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2871 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/models/index_catalog.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2441 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/models/table_catalog.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3022 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/models/udf_cache_catalog.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3101 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/models/udf_catalog.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1804 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/models/udf_cost_catalog.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3923 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/models/udf_io_catalog.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2205 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/models/udf_metadata_catalog.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6789 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/models/utils.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2126 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/schema_utils.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.649783 evadb-0.3.0/evadb/catalog/services/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/services/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1291 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/services/base_service.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3377 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/services/column_catalog_service.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2970 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/services/index_catalog_service.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4961 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/services/table_catalog_service.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3999 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/services/udf_cache_catalog_service.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3249 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/services/udf_catalog_service.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3036 2023-06-25 03:38:24.000000 evadb-0.3.0/evadb/catalog/services/udf_cost_catalog_service.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2934 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/services/udf_io_catalog_service.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2226 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/catalog/services/udf_metadata_catalog_service.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2793 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/catalog/sql_config.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.649783 evadb-0.3.0/evadb/configuration/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      622 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/configuration/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5035 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/configuration/bootstrap_environment.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2508 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/configuration/configuration_manager.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1055 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/configuration/constants.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      884 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/constants.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1964 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/database.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      570 2023-06-26 03:28:32.000000 evadb-0.3.0/evadb/evadb.yml
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2018 2023-06-08 22:16:07.000000 evadb-0.3.0/evadb/evadb_cmd_client.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2685 2023-06-08 22:16:07.000000 evadb-0.3.0/evadb/evadb_server.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.653783 evadb-0.3.0/evadb/executor/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      617 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3803 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/abstract_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2324 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/apply_and_merge_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2034 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/executor/create_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5099 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/create_index_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7395 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/executor/create_udf_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4732 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/executor/delete_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4959 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/executor/drop_object_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3635 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/executor/exchange_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3025 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/execution_context.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5513 2023-06-25 22:35:38.000000 evadb-0.3.0/evadb/executor/executor_utils.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1596 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/explain_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2005 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/function_scan_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1897 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/groupby_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1944 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/hash_join_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2243 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/executor/insert_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1688 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/join_build_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1843 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/lateral_join_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1655 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/limit_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3080 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/executor/load_csv_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1742 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/load_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6141 2023-06-26 03:15:21.000000 evadb-0.3.0/evadb/executor/load_multimedia_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1616 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/nested_loop_join_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4263 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/orderby_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     8299 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/executor/plan_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1716 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/pp_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1367 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/predicate_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1362 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/project_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2443 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/executor/ray_utils.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1267 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/rename_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1485 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/sample_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1918 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/seq_scan_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1846 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/show_info_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2646 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/executor/storage_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1336 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/union_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4395 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/executor/vector_index_scan_executor.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.653783 evadb-0.3.0/evadb/expression/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      619 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/expression/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5561 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/expression/abstract_expression.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3979 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/expression/aggregation_expression.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1624 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/expression/arithmetic_expression.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4357 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/expression/comparison_expression.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2550 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/expression/constant_value_expression.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    10445 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/expression/expression_utils.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    10064 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/expression/function_expression.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3059 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/expression/logical_expression.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4330 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/expression/tuple_value_expression.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.653783 evadb-0.3.0/evadb/interfaces/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/interfaces/__init__.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.657783 evadb-0.3.0/evadb/interfaces/relational/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/interfaces/relational/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    19500 2023-06-26 14:59:01.000000 evadb-0.3.0/evadb/interfaces/relational/db.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7755 2023-06-22 16:24:39.000000 evadb-0.3.0/evadb/interfaces/relational/relation.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4596 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/interfaces/relational/utils.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.657783 evadb-0.3.0/evadb/models/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      637 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/models/__init__.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.657783 evadb-0.3.0/evadb/models/catalog/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/models/catalog/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1336 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/models/catalog/frame_info.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      859 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/models/catalog/properties.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.657783 evadb-0.3.0/evadb/models/server/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/models/server/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1971 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/models/server/response.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.657783 evadb-0.3.0/evadb/models/storage/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/models/storage/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    15331 2023-06-09 18:53:37.000000 evadb-0.3.0/evadb/models/storage/batch.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.657783 evadb-0.3.0/evadb/optimizer/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      624 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/optimizer/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3269 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/optimizer/binder.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2145 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/optimizer/cost_model.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3460 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/optimizer/group.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2677 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/optimizer/group_expression.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4347 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/optimizer/memo.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    35384 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/optimizer/operators.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4040 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/optimizer/optimizer_context.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      986 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/optimizer/optimizer_task_stack.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    12600 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/optimizer/optimizer_tasks.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    11286 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/optimizer/optimizer_utils.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4184 2023-06-26 14:59:01.000000 evadb-0.3.0/evadb/optimizer/plan_generator.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1171 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/optimizer/property.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.657783 evadb-0.3.0/evadb/optimizer/rules/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/optimizer/rules/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1023 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/optimizer/rules/pattern.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    48746 2023-06-27 00:54:47.000000 evadb-0.3.0/evadb/optimizer/rules/rules.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7274 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/optimizer/rules/rules_base.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7741 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/optimizer/rules/rules_manager.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    12770 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/optimizer/statement_to_opr_converter.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.661783 evadb-0.3.0/evadb/parser/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1362 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/alias.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2754 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/create_index_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5324 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/create_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4436 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/create_udf_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2058 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/delete_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2131 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/drop_object_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    19665 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/parser/evadb.lark
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1390 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/explain_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2932 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/insert_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1724 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/lark_parser.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.661783 evadb-0.3.0/evadb/parser/lark_visitor/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2685 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/lark_visitor/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2163 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/parser/lark_visitor/_common_clauses_ids.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     9784 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/parser/lark_visitor/_create_statements.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1410 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/lark_visitor/_delete_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2007 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/lark_visitor/_drop_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1010 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/lark_visitor/_explain_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5894 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/parser/lark_visitor/_expressions.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5776 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/parser/lark_visitor/_functions.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2510 2023-06-26 14:59:01.000000 evadb-0.3.0/evadb/parser/lark_visitor/_insert_statements.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2247 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/lark_visitor/_load_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      938 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/lark_visitor/_rename_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2149 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/lark_visitor/_select_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1118 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/lark_visitor/_show_statements.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     9562 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/parser/lark_visitor/_table_sources.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3224 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/load_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1233 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/parser.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2015 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/rename_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6258 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/select_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1466 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/show_statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1430 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/parser/statement.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     9180 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/parser/table_ref.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1849 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/parser/types.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6234 2023-06-22 16:24:39.000000 evadb-0.3.0/evadb/parser/utils.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.665784 evadb-0.3.0/evadb/plan_nodes/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      616 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1699 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/abstract_join_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3457 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/abstract_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1463 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/abstract_scan_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1940 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/apply_and_merge_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2483 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/create_index_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2210 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/create_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3483 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/create_udf_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1961 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/delete_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1499 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/drop_object_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2063 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/exchange_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1039 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/explain_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1763 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/function_scan_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1507 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/groupby_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1722 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/hash_join_build_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2191 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/hash_join_probe_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2033 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/insert_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1418 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/lateral_join_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1476 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/limit_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2720 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/load_data_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1520 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/nested_loop_join_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1570 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/orderby_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1185 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/pp_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1253 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/predicate_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1257 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/project_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1624 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/rename_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1477 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/sample_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1768 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/seq_scan_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1209 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/show_info_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4559 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/plan_nodes/storage_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1370 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/plan_nodes/types.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1251 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/union_plan.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2732 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/plan_nodes/vector_index_scan_plan.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.665784 evadb-0.3.0/evadb/readers/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/readers/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2328 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/readers/abstract_reader.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2620 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/readers/csv_reader.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5877 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/readers/decord_reader.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.665784 evadb-0.3.0/evadb/readers/document/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/readers/document/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2079 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/readers/document/document_reader.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2109 2023-06-22 16:24:39.000000 evadb-0.3.0/evadb/readers/document/registry.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.665784 evadb-0.3.0/evadb/readers/image/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/readers/image/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1163 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/readers/image/opencv_image_reader.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2139 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/readers/pdf_reader.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.665784 evadb-0.3.0/evadb/server/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      625 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/server/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3871 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/server/command_handler.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3641 2023-06-26 14:59:01.000000 evadb-0.3.0/evadb/server/interpreter.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3393 2023-06-26 14:59:01.000000 evadb-0.3.0/evadb/server/server.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.669784 evadb-0.3.0/evadb/storage/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      618 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/storage/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6187 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/storage/abstract_media_storage_engine.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2497 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/storage/abstract_storage_engine.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1870 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/storage/document_storage_engine.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1789 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/storage/image_storage_engine.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1764 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/storage/pdf_storage_engine.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     9483 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/storage/sqlite_storage_engine.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2066 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/storage/storage_engine.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2562 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/storage/video_storage_engine.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.669784 evadb-0.3.0/evadb/third_party/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      607 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/third_party/__init__.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.669784 evadb-0.3.0/evadb/third_party/huggingface/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      614 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/third_party/huggingface/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1428 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/third_party/huggingface/binder.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6593 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/third_party/huggingface/create.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2697 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/third_party/huggingface/model.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.669784 evadb-0.3.0/evadb/third_party/vector_stores/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      609 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/third_party/vector_stores/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2919 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/third_party/vector_stores/faiss.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2852 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/third_party/vector_stores/qdrant.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1378 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/third_party/vector_stores/types.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1608 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/third_party/vector_stores/utils.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.669784 evadb-0.3.0/evadb/udfs/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      618 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/__init__.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.669784 evadb-0.3.0/evadb/udfs/abstract/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      627 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/abstract/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2446 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/abstract/abstract_udf.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4249 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/abstract/hf_abstract_udf.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4067 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/abstract/pytorch_abstract_udf.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3928 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/abstract/tracker_abstract_udf.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3462 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/asl_action_recognition.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4684 2023-06-27 00:54:47.000000 evadb-0.3.0/evadb/udfs/chatgpt.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.673784 evadb-0.3.0/evadb/udfs/decorators/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/decorators/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2192 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/decorators/decorators.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.673784 evadb-0.3.0/evadb/udfs/decorators/io_descriptors/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/decorators/io_descriptors/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2761 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/decorators/io_descriptors/abstract_types.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3386 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/decorators/io_descriptors/data_types.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2073 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/decorators/utils.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6056 2023-06-25 23:15:30.000000 evadb-0.3.0/evadb/udfs/emotion_detector.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2886 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/face_detector.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5851 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/fastrcnn_object_detector.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1826 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/feature_extractor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2516 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/fuzzy_join.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1030 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/gpu_compatible.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3993 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/mnist_image_classifier.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2183 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/mvit_action_recognition.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.673784 evadb-0.3.0/evadb/udfs/ndarray/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      640 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/ndarray/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2582 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/ndarray/annotate.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2572 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/ndarray/array_count.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1651 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/ndarray/crop.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1183 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/ndarray/fuzzy_join.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2310 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/ndarray/gaussian_blur.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2327 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/ndarray/horizontal_flip.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1662 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/ndarray/open.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1887 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/ndarray/similarity.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2233 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/ndarray/to_grayscale.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2313 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/ndarray/vertical_flip.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2705 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/saliency_feature_extractor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2545 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/sentence_feature_extractor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3159 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/sift_feature_extractor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2176 2023-06-27 23:59:04.000000 evadb-0.3.0/evadb/udfs/text_filter_keyword.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.673784 evadb-0.3.0/evadb/udfs/trackers/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      638 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/udfs/trackers/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2506 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/trackers/nor_fair.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     8714 2023-06-27 00:54:47.000000 evadb-0.3.0/evadb/udfs/udf_bootstrap_queries.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3825 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/udfs/yolo_object_detector.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.673784 evadb-0.3.0/evadb/utils/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      615 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/utils/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      911 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/utils/errors.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    12289 2023-06-27 00:54:47.000000 evadb-0.3.0/evadb/utils/generic_utils.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1958 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/utils/kv_cache.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      987 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/utils/logging_manager.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1390 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/utils/math_utils.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1651 2023-06-21 17:21:29.000000 evadb-0.3.0/evadb/utils/s3_utils.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1696 2023-06-08 22:16:06.000000 evadb-0.3.0/evadb/utils/stats.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      123 2023-06-27 23:59:44.000000 evadb-0.3.0/evadb/version.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.645783 evadb-0.3.0/evadb.egg-info/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    13108 2023-06-27 23:59:46.000000 evadb-0.3.0/evadb.egg-info/PKG-INFO
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    14257 2023-06-27 23:59:46.000000 evadb-0.3.0/evadb.egg-info/SOURCES.txt
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)        1 2023-06-27 23:59:46.000000 evadb-0.3.0/evadb.egg-info/dependency_links.txt
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      100 2023-06-27 23:59:46.000000 evadb-0.3.0/evadb.egg-info/entry_points.txt
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1418 2023-06-27 23:59:46.000000 evadb-0.3.0/evadb.egg-info/requires.txt
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)       23 2023-06-27 23:59:46.000000 evadb-0.3.0/evadb.egg-info/top_level.txt
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)       90 2023-06-08 04:02:21.000000 evadb-0.3.0/pyproject.toml
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)       38 2023-06-27 23:59:46.689784 evadb-0.3.0/setup.cfg
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4769 2023-06-27 23:59:01.000000 evadb-0.3.0/setup.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.673784 evadb-0.3.0/test/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/__init__.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.673784 evadb-0.3.0/test/app_tests/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-21 17:21:29.000000 evadb-0.3.0/test/app_tests/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1799 2023-06-26 03:15:21.000000 evadb-0.3.0/test/app_tests/test_pandas_qa.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3237 2023-06-21 17:21:29.000000 evadb-0.3.0/test/app_tests/test_privategpt.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2022 2023-06-27 00:54:47.000000 evadb-0.3.0/test/app_tests/test_youtube_channel_qa.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2025 2023-06-22 16:24:39.000000 evadb-0.3.0/test/app_tests/test_youtube_qa.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.677784 evadb-0.3.0/test/benchmark_tests/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/benchmark_tests/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1265 2023-06-08 22:16:06.000000 evadb-0.3.0/test/benchmark_tests/conftest.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6923 2023-06-25 23:15:30.000000 evadb-0.3.0/test/benchmark_tests/test_benchmark_pytorch.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.677784 evadb-0.3.0/test/binder/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/binder/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    14091 2023-06-25 23:15:30.000000 evadb-0.3.0/test/binder/test_statement_binder.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     8188 2023-06-21 17:21:29.000000 evadb-0.3.0/test/binder/test_statement_binder_context.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.677784 evadb-0.3.0/test/catalog/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/catalog/__init__.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.677784 evadb-0.3.0/test/catalog/models/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/catalog/models/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7252 2023-06-08 22:16:06.000000 evadb-0.3.0/test/catalog/models/test_models.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7355 2023-06-08 22:16:06.000000 evadb-0.3.0/test/catalog/test_catalog_manager.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1406 2023-06-08 22:16:06.000000 evadb-0.3.0/test/catalog/test_column_type.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.677784 evadb-0.3.0/test/executor/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/executor/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1110 2023-06-08 22:16:06.000000 evadb-0.3.0/test/executor/test_abstract_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4081 2023-06-08 22:16:06.000000 evadb-0.3.0/test/executor/test_create_udf_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4273 2023-06-08 22:16:06.000000 evadb-0.3.0/test/executor/test_execution_context.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4747 2023-06-08 22:16:06.000000 evadb-0.3.0/test/executor/test_limit_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2936 2023-06-08 22:16:06.000000 evadb-0.3.0/test/executor/test_orderby_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     9933 2023-06-08 22:16:06.000000 evadb-0.3.0/test/executor/test_plan_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1867 2023-06-08 22:16:06.000000 evadb-0.3.0/test/executor/test_sample_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3037 2023-06-08 22:16:06.000000 evadb-0.3.0/test/executor/test_seq_scan_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      851 2023-06-08 22:16:06.000000 evadb-0.3.0/test/executor/utils.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.677784 evadb-0.3.0/test/expression/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/expression/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3734 2023-06-08 22:16:06.000000 evadb-0.3.0/test/expression/test_abstract_expression.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5123 2023-06-21 17:21:29.000000 evadb-0.3.0/test/expression/test_aggregation.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2985 2023-06-08 22:16:06.000000 evadb-0.3.0/test/expression/test_arithmetic.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5590 2023-06-08 22:16:06.000000 evadb-0.3.0/test/expression/test_comparison.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2871 2023-06-21 17:21:29.000000 evadb-0.3.0/test/expression/test_expression_tree.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7567 2023-06-21 17:21:29.000000 evadb-0.3.0/test/expression/test_expression_utils.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2701 2023-06-08 22:16:06.000000 evadb-0.3.0/test/expression/test_function_expression.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    10224 2023-06-21 17:21:29.000000 evadb-0.3.0/test/expression/test_logical.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.681784 evadb-0.3.0/test/integration_tests/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/integration_tests/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3703 2023-06-08 22:16:06.000000 evadb-0.3.0/test/integration_tests/test_array_count.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     6362 2023-06-25 23:15:30.000000 evadb-0.3.0/test/integration_tests/test_create_index_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3966 2023-06-25 23:15:30.000000 evadb-0.3.0/test/integration_tests/test_create_table_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5271 2023-06-21 17:21:29.000000 evadb-0.3.0/test/integration_tests/test_delete_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7282 2023-06-25 23:15:30.000000 evadb-0.3.0/test/integration_tests/test_drop_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2373 2023-06-25 23:15:30.000000 evadb-0.3.0/test/integration_tests/test_error_handling_with_ray.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3683 2023-06-08 22:16:06.000000 evadb-0.3.0/test/integration_tests/test_explain_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2862 2023-06-08 22:16:06.000000 evadb-0.3.0/test/integration_tests/test_fuzzy_join.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    17606 2023-06-27 00:54:47.000000 evadb-0.3.0/test/integration_tests/test_huggingface_udfs.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3964 2023-06-08 22:16:06.000000 evadb-0.3.0/test/integration_tests/test_insert_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3100 2023-06-08 22:16:06.000000 evadb-0.3.0/test/integration_tests/test_like.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    23292 2023-06-27 23:59:04.000000 evadb-0.3.0/test/integration_tests/test_load_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2028 2023-06-27 23:59:04.000000 evadb-0.3.0/test/integration_tests/test_load_pdf_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2667 2023-06-08 22:16:06.000000 evadb-0.3.0/test/integration_tests/test_open.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    11073 2023-06-25 23:15:30.000000 evadb-0.3.0/test/integration_tests/test_optimizer_rules.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    15830 2023-06-25 23:15:30.000000 evadb-0.3.0/test/integration_tests/test_pytorch.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3083 2023-06-08 22:16:06.000000 evadb-0.3.0/test/integration_tests/test_rename_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    10968 2023-06-25 23:15:30.000000 evadb-0.3.0/test/integration_tests/test_reuse.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5432 2023-06-21 17:21:29.000000 evadb-0.3.0/test/integration_tests/test_s3_load_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2416 2023-06-25 23:15:30.000000 evadb-0.3.0/test/integration_tests/test_saliency.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    32438 2023-06-25 23:15:30.000000 evadb-0.3.0/test/integration_tests/test_select_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3452 2023-06-08 22:16:06.000000 evadb-0.3.0/test/integration_tests/test_show_info_executor.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    16799 2023-06-27 00:54:47.000000 evadb-0.3.0/test/integration_tests/test_similarity.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2069 2023-06-27 23:59:04.000000 evadb-0.3.0/test/integration_tests/test_text_filtering.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    12693 2023-06-27 00:54:47.000000 evadb-0.3.0/test/integration_tests/test_udf_executor.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.681784 evadb-0.3.0/test/interfaces/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/interfaces/__init__.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.681784 evadb-0.3.0/test/interfaces/relational/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/interfaces/relational/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    15497 2023-06-27 23:59:01.000000 evadb-0.3.0/test/interfaces/relational/test_relational_api.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1874 2023-06-27 23:59:01.000000 evadb-0.3.0/test/markers.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.681784 evadb-0.3.0/test/models/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/models/__init__.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.681784 evadb-0.3.0/test/models/catalog/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/models/catalog/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1016 2023-06-08 22:16:06.000000 evadb-0.3.0/test/models/catalog/test_frame_info.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.681784 evadb-0.3.0/test/models/storage/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/models/storage/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5925 2023-06-08 22:16:06.000000 evadb-0.3.0/test/models/storage/test_batch.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.681784 evadb-0.3.0/test/optimizer/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/optimizer/__init__.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.685784 evadb-0.3.0/test/optimizer/rules/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/optimizer/rules/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    11782 2023-06-25 23:15:30.000000 evadb-0.3.0/test/optimizer/rules/test_rules.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4246 2023-06-08 22:16:06.000000 evadb-0.3.0/test/optimizer/test_binder.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2329 2023-06-08 22:16:06.000000 evadb-0.3.0/test/optimizer/test_cascade_optimizer.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4512 2023-06-08 22:16:06.000000 evadb-0.3.0/test/optimizer/test_cost_model.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2697 2023-06-08 22:16:06.000000 evadb-0.3.0/test/optimizer/test_group.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2002 2023-06-08 22:16:06.000000 evadb-0.3.0/test/optimizer/test_memo.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1053 2023-06-08 22:16:06.000000 evadb-0.3.0/test/optimizer/test_optimizer_context.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5668 2023-06-08 22:16:06.000000 evadb-0.3.0/test/optimizer/test_optimizer_task.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2008 2023-06-08 22:16:06.000000 evadb-0.3.0/test/optimizer/test_optimizer_utils.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    12882 2023-06-25 23:15:30.000000 evadb-0.3.0/test/optimizer/test_statement_to_opr_converter.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.685784 evadb-0.3.0/test/parser/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/parser/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    35519 2023-06-25 23:15:30.000000 evadb-0.3.0/test/parser/test_parser.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7747 2023-06-25 23:15:30.000000 evadb-0.3.0/test/parser/test_parser_statements.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.685784 evadb-0.3.0/test/plan_nodes/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/plan_nodes/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5540 2023-06-25 23:15:30.000000 evadb-0.3.0/test/plan_nodes/test_plan.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.685784 evadb-0.3.0/test/readers/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/readers/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1682 2023-06-21 17:21:29.000000 evadb-0.3.0/test/readers/test_csv_reader.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     8218 2023-06-21 17:21:29.000000 evadb-0.3.0/test/readers/test_decord_reader.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.685784 evadb-0.3.0/test/server/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/server/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1278 2023-06-08 22:16:06.000000 evadb-0.3.0/test/server/test_command_handler.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1252 2023-06-27 00:55:06.000000 evadb-0.3.0/test/server/test_configuration_file.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     5221 2023-06-08 22:16:06.000000 evadb-0.3.0/test/server/test_db_api.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2687 2023-06-21 17:21:29.000000 evadb-0.3.0/test/server/test_interpreter.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2171 2023-06-08 22:16:06.000000 evadb-0.3.0/test/server/test_server.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.685784 evadb-0.3.0/test/storage/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/storage/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4512 2023-06-08 22:16:06.000000 evadb-0.3.0/test/storage/test_sqlite_storage_engine.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4165 2023-06-08 22:16:06.000000 evadb-0.3.0/test/storage/test_video_storage.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3341 2023-06-08 22:16:06.000000 evadb-0.3.0/test/test_eva_cmd_client.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1310 2023-06-08 22:16:06.000000 evadb-0.3.0/test/test_eva_imports.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1427 2023-06-08 22:16:06.000000 evadb-0.3.0/test/test_eva_server.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.685784 evadb-0.3.0/test/udfs/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      640 2023-06-08 22:16:06.000000 evadb-0.3.0/test/udfs/__init__.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.685784 evadb-0.3.0/test/udfs/decorators/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/udfs/decorators/__init__.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.685784 evadb-0.3.0/test/udfs/decorators/io_descriptors/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/udfs/decorators/io_descriptors/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     7437 2023-06-08 22:16:06.000000 evadb-0.3.0/test/udfs/decorators/io_descriptors/test_descriptors.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2145 2023-06-08 22:16:06.000000 evadb-0.3.0/test/udfs/decorators/test_decorators.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.689784 evadb-0.3.0/test/udfs/ndarray/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      650 2023-06-08 22:16:06.000000 evadb-0.3.0/test/udfs/ndarray/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1951 2023-06-21 17:21:29.000000 evadb-0.3.0/test/udfs/ndarray/test_annotate.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      853 2023-06-08 22:16:06.000000 evadb-0.3.0/test/udfs/ndarray/test_array_count.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2414 2023-06-08 22:16:06.000000 evadb-0.3.0/test/udfs/ndarray/test_crop.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2187 2023-06-21 17:21:29.000000 evadb-0.3.0/test/udfs/ndarray/test_flips.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1764 2023-06-21 17:21:29.000000 evadb-0.3.0/test/udfs/ndarray/test_gaussian_blur.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2362 2023-06-21 17:21:29.000000 evadb-0.3.0/test/udfs/ndarray/test_open.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1761 2023-06-21 17:21:29.000000 evadb-0.3.0/test/udfs/ndarray/test_to_grayscale.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     4499 2023-06-27 23:59:01.000000 evadb-0.3.0/test/udfs/test_abstract_udf.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2913 2023-06-25 04:22:18.000000 evadb-0.3.0/test/udfs/test_chatgpt.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2257 2023-06-21 17:21:29.000000 evadb-0.3.0/test/udfs/test_emotion_detector.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2892 2023-06-21 17:21:29.000000 evadb-0.3.0/test/udfs/test_facenet_udf.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     1938 2023-06-21 17:21:29.000000 evadb-0.3.0/test/udfs/test_fastrcnn_object_detector.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2920 2023-06-21 17:21:29.000000 evadb-0.3.0/test/udfs/test_yolo_object_detector.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)    18203 2023-06-27 00:54:47.000000 evadb-0.3.0/test/util.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.689784 evadb-0.3.0/test/utils/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)      589 2023-06-08 22:16:06.000000 evadb-0.3.0/test/utils/__init__.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     3939 2023-06-08 22:16:06.000000 evadb-0.3.0/test/utils/test_generic_utils.py
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)     2283 2023-06-08 22:16:06.000000 evadb-0.3.0/test/utils/test_timer.py
+drwxr-xr-x   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-27 23:59:46.689784 evadb-0.3.0/third_party/
+-rw-r--r--   0 jarulraj3 (347863) gtperson  (2626)        0 2023-06-08 04:02:21.000000 evadb-0.3.0/third_party/__init__.py
```

### Comparing `evadb-0.2.9/LICENSE.txt` & `evadb-0.3.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/PKG-INFO` & `evadb-0.3.0/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,203 +1,191 @@
 Metadata-Version: 2.1
 Name: evadb
-Version: 0.2.9
+Version: 0.3.0
 Summary: EvaDB AI-Relational Database System
 Home-page: https://github.com/georgia-tech-db/eva
 Download-URL: https://github.com/georgia-tech-db/eva
 Author: Georgia Tech Database Group
 Author-email: arulraj@gatech.edu
 License: Apache License 2.0
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
+Provides-Extra: ray
+Provides-Extra: vision
+Provides-Extra: document
+Provides-Extra: udf
+Provides-Extra: notebook
+Provides-Extra: qdrant
 Provides-Extra: dev
 License-File: LICENSE.txt
 
 # EvaDB AI-SQL Database System
 
 <div>
         <a href="https://colab.research.google.com/github/georgia-tech-db/eva/blob/master/tutorials/03-emotion-analysis.ipynb">
             <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open EvaDB on Colab"/>
         </a>
         <a href="https://join.slack.com/t/eva-db/shared_invite/zt-1i10zyddy-PlJ4iawLdurDv~aIAq90Dg">
-            <img alt="Slack" src="https://img.shields.io/badge/slack-eva-ff69b4.svg?logo=slack">
+            <img alt="Slack" src="https://img.shields.io/badge/slack-evadb-ff69b4.svg?logo=slack">
         </a>          
         <a href="https://twitter.com/evadb_ai">
-            <img alt="Twitter" src="https://img.shields.io/badge/twitter-eva-bde1ee.svg?logo=twitter">
+            <img alt="Twitter" src="https://img.shields.io/badge/twitter-evadb-bde1ee.svg?logo=twitter">
         </a>  
         <a href="https://github.com/orgs/georgia-tech-db/projects/3">
-            <img src="https://img.shields.io/badge/eva-roadmap-a6c096" alt="Roadmap"/>
+            <img src="https://img.shields.io/badge/evadb-roadmap-a6c096" alt="Roadmap"/>
         </a>
         <img alt="PyPI" src="https://img.shields.io/pypi/v/evadb.svg"/>
         <img alt="License" src="https://img.shields.io/badge/license-Apache%202-brightgreen.svg?logo=apache"/>
         <img alt="Coverage Status" src="https://coveralls.io/repos/github/georgia-tech-db/eva/badge.svg?branch=master"/>     
         <a href="https://pepy.tech/project/evadb">
-          <img alt="Downloads" src="https://static.pepy.tech/badge/evadb/month"/>
+          <img alt="Downloads" src="https://static.pepy.tech/badge/evadb"/>
         </a>
         <img alt="Python Versions" src="https://img.shields.io/badge/Python--versions-3.8%20|%203.9%20|%203.10-brightgreen"/>       
 </div>
 
 <p align="center"> <b><h3>EvaDB is a database system for building simpler and faster AI-powered applications.</b></h3> </p>
 
-EvaDB is an AI-SQL database system for developing applications powered by AI models. We aim to simplify the development and deployment of AI-powered applications that operate on structured (tables, feature stores) and unstructured data (text documents, videos, PDFs, podcasts, etc.).
+EvaDB is a database system for developing AI apps. We aim to simplify the development and deployment of AI-powered apps that operate on unstructured data (text documents, videos, PDFs, podcasts, etc.) and structured data (tables, vector index).
 
-EvaDB accelerates AI pipelines by 10x using a collection of performance optimizations inspired by time-tested SQL database systems, including data-parallel query execution, function caching, sampling, and cost-based predicate reordering. EvaDB supports an AI-oriented query language tailored for analyzing both structured and unstructured data. It has first-class support for PyTorch, Hugging Face, YOLO, and Open AI models.
-
-The high-level Python and SQL APIs allows even beginners to use EvaDB in a few lines of code. Advanced users can define custom user-defined functions that wrap around any AI model or Python library. EvaDB is fully implemented in Python and licensed under the Apache license.
+The high-level Python and SQL APIs allow beginners to use EvaDB in a few lines of code. Advanced users can define custom user-defined functions that wrap around any AI model or Python library. EvaDB is fully implemented in Python and licensed under the Apache license.
 
 ## Quick Links
 
 - [Features](#features)
 - [Quick Start](#quick-start)
 - [Documentation](#documentation)
-- [Roadmap](https://github.com/orgs/georgia-tech-db/projects/3)
-- [Architecture Diagram](#architecture-diagram)
-- [Illustrative Applications](#illustrative-applications)
-- [Screenshots](#screenshots)
 - [Community and Support](#community-and-support)
 - [Twitter](https://twitter.com/evadb_ai)
-- [Contributing](#contributing)
-- [License](#license)
 
 ## Features
 
-- 🔮 Build simpler AI-powered applications using short Python or SQL queries
+- 🔮 Build simpler AI-powered applications using Python functions or SQL queries
 - ⚡️ 10x faster applications using AI-centric query optimization  
 - 💰 Save money spent on GPUs
 - 🚀 First-class support for your custom deep learning models through user-defined functions
 - 📦 Built-in caching to eliminate redundant model invocations across queries
 - ⌨️ First-class support for PyTorch, Hugging Face, YOLO, and Open AI models
 - 🐍 Installable via pip and fully implemented in Python
 
 ## Illustrative Applications
 
 Here are some illustrative EvaDB-powered applications (each Jupyter notebook can be opened on Google Colab):
 
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/11-similarity-search-for-motif-mining.html">Reddit Image Similarity Search</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/08-chatgpt.html">ChatGPT-based video question answering</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/12-query-pdf.html">Quering PDF documents</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/02-object-detection.html">Analysing traffic flow with YOLO</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/03-emotion-analysis.html">Examining emotion palette of a movie</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/07-object-segmentation-huggingface.html">Image segmentation with Hugging Face</a>
- * 🔮 <a href="https://github.com/georgia-tech-db/license-plate-recognition">Recognizing license plates</a>
- * 🔮 <a href="https://github.com/georgia-tech-db/toxicity-classification">Analysing toxicity of social media memes </a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/13-privategpt.html">PrivateGPT</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/08-chatgpt.html">ChatGPT-based Video Question Answering</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/12-query-pdf.html">Querying PDF Documents</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/02-object-detection.html">Analysing Traffic Flow with YOLO</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/03-emotion-analysis.html">Examining Emotions of Movie</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/07-object-segmentation-huggingface.html">Image Segmentation with Hugging Face</a>
 
 ## Documentation
 
-* [Detailed Documentation](https://evadb.readthedocs.io/)
+* [Documentation](https://evadb.readthedocs.io/)
   - The <a href="https://evadb.readthedocs.io/en/stable/source/overview/installation.html">Getting Started</a> page shows how you can use EvaDB for different AI tasks and how you can easily extend EvaDB to support your custom deep learning model through user-defined functions.
-  - The <a href="https://evadb.readthedocs.io/en/latest/source/tutorials/11-similarity-search-for-motif-mining.html">User Guides</a> section contains Jupyter Notebooks that demonstrate how to use various features of EvaDB. Each notebook includes a link to Google Colab, where you can run the code yourself.
-* [Tutorials](https://github.com/georgia-tech-db/eva/blob/master/tutorials/03-emotion-analysis.ipynb)
+  - The <a href="https://evadb.readthedocs.io/en/latest/source/tutorials/13-privategpt.html">User Guides</a> section contains Jupyter Notebooks that demonstrate how to use various features of EvaDB. Each notebook includes a link to Google Colab, where you can run the code yourself.
 * [Join us on Slack](https://join.slack.com/t/eva-db/shared_invite/zt-1i10zyddy-PlJ4iawLdurDv~aIAq90Dg)
 * [Follow us on Twitter](https://twitter.com/evadb_ai)
-* [Medium-Term Roadmap](https://github.com/orgs/georgia-tech-db/projects/3)
-* [Demo](https://evadb.readthedocs.io/en/stable/source/tutorials/08-chatgpt.html)
+* [Roadmap](https://github.com/orgs/georgia-tech-db/projects/3)
 
 ## Quick Start
 
-- Install EvaDB using the pip package manager. EvaDB supports Python versions >= 3.8:
+- Step 1: Install EvaDB using pip. EvaDB supports Python versions >= `3.8`:
 
 ```shell
 pip install evadb
 ```
 
-- To launch and connect to an EvaDB server in a Jupyter notebook, check out this [illustrative emotion analysis notebook](https://github.com/georgia-tech-db/eva/blob/master/tutorials/03-emotion-analysis.ipynb):
-```shell
-cursor = connect_to_server()
-```
-
-- Load a video onto the EvaDB server (we use [ua_detrac.mp4](data/ua_detrac/ua_detrac.mp4) for illustration):
-
-```mysql
-LOAD VIDEO "data/ua_detrac/ua_detrac.mp4" INTO TrafficVideo;
-```
-
-- That's it! You can now run queries over the loaded video:
+- Step 2: Write your AI app!
 
-```mysql
-SELECT id, data FROM TrafficVideo WHERE id < 5;
-```
-
-- Search for frames in the video that contain a car:
-
-```mysql
-SELECT id, data FROM TrafficVideo WHERE ['car'] <@ Yolo(data).labels;
-```
-| Source Video  | Query Result |
-|---------------|--------------|
-|<img alt="Source Video" src="https://github.com/georgia-tech-db/eva/releases/download/v0.1.0/traffic-input.webp" width="300"> |<img alt="Query Result" src="https://github.com/georgia-tech-db/eva/releases/download/v0.1.0/traffic-output.webp" width="300"> |
+```python
+import evadb
 
-- Search for frames in the video that contain a pedestrian and a car:
+# Grab a EvaDB cursor to load data and run queries
+cursor = evadb.connect().cursor()
 
-```mysql
-SELECT id, data FROM TrafficVideo WHERE ['pedestrian', 'car'] <@ Yolo(data).labels;
+# Load a collection of news videos into the 'news_videos' table
+# This command returns a Pandas Dataframe with the query's output
+# In this case, the output indicates the number of loaded videos
+cursor.load(
+    file_regex="news_videos/*.mp4",
+    format="VIDEO",
+    table_name="news_videos"
+).df()
+
+# Define a function that wraps around your deep learning model
+# Here, this function wraps around an off-the-shelf speech-to-text (Whisper) model
+# Such functions are known as user-defined functions or UDFs
+# So, we are creating a Whisper UDF here
+# After creating the UDF, we can use the function in any query
+cursor.create_udf(
+    udf_name="SpeechRecognizer",
+    type="HuggingFace",
+    task='automatic-speech-recognition',
+    model='openai/whisper-base'
+).df()
+
+# EvaDB automatically extract the audio from the video
+# We only need to run the SpeechRecongizer UDF on the 'audio' column
+# to get the transcript and persist it in a table called 'transcripts'
+cursor.query(
+    """CREATE TABLE transcripts AS
+       SELECT SpeechRecognizer(audio) from news_videos;"""
+).df()
+
+# We next incrementally construct the ChatGPT query using EvaDB's Python API
+# The query is based on the 'transcripts' table
+# This table has a column called 'text' with the transcript text
+query = cursor.table('transcripts')
+
+# Since ChatGPT is a built-in function, we don't have to define it
+# We can just directly use it in the query
+# We need to set the OPENAI_KEY as an environment variable
+os.environ["OPENAI_KEY"] = OPENAI_KEY
+query = query.select("ChatGPT('Is this video summary related to LLMs', text)")
+
+# Finally, we run the query to get the results as a dataframe
+response = query.df()
+```
+
+- **Chain multiple models in a single query to set up useful AI pipelines**
+
+```python
+# Analyse emotions of actors in an Interstellar movie clip using PyTorch models
+query = cursor.table("Interstellar")
+# Get faces using a `FaceDetector` function
+query = query.cross_apply("UNNEST(FaceDetector(data))", "Face(bounding_box, confidence)")
+# Focus only on frames 100 through 200 in the clip
+query = query.filter("id > 100 AND id < 200")
+# Get the emotions of the detected faces using a `EmotionDetector` function
+query = query.select("id, bbox, EmotionDetector(Crop(data, bounding_box))")
+
+# Run the query and get the query result as a dataframe
+response = query.df()
 ```
+- **EvaDB runs AI apps 10--100x faster using its AI-centric query optimizer**. Three key built-in optimizations are:
 
-- Search for frames with more than three cars:
+   💾 **Caching**: EvaDB automatically caches and reuses model inference results.
 
-```mysql
-SELECT id, data FROM TrafficVideo WHERE ArrayCount(Yolo(data).labels, 'car') > 3;
-```
-
-- **Use your custom deep learning model in queries** with a user-defined function (UDF):
-
-```mysql
-CREATE UDF IF NOT EXISTS Yolo
-TYPE  ultralytics
-'model' 'yolov8m.pt';
-```
-
-- **Chain multiple models in a single query** to set up useful AI pipelines.
-
-```mysql
-   -- Analyse emotions of faces in a video
-   SELECT id, bbox, EmotionDetector(Crop(data, bbox)) 
-   FROM MovieVideo JOIN LATERAL UNNEST(FaceDetector(data)) AS Face(bbox, conf)  
-   WHERE id < 15;
-```
-
-- **EvaDB runs queries faster using its AI-centric query optimizer**. Two key optimizations are:
-
-   💾 **Caching**: EvaDB automatically caches and reuses previous query results (especially model inference results), eliminating redundant computation and reducing query processing time.
-
-   🎯 **Predicate Reordering**: EvaDB optimizes the order in which the query predicates are evaluated (e.g., runs the faster, more selective model first), leading to faster queries and lower inference costs.
-
-Consider these two exploratory queries on a dataset of dog images:
-<img align="right" style="display:inline;" width="40%" src="https://github.com/georgia-tech-db/eva/blob/master/data/assets/eva_performance_comparison.png?raw=true"></a>
-
-```mysql
-  -- Query 1: Find all images of black-colored dogs
-  SELECT id, bbox FROM dogs 
-  JOIN LATERAL UNNEST(Yolo(data)) AS Obj(label, bbox, score) 
-  WHERE Obj.label = 'dog' 
-    AND Color(Crop(data, bbox)) = 'black'; 
-
-  -- Query 2: Find all Great Danes that are black-colored
-  SELECT id, bbox FROM dogs 
-  JOIN LATERAL UNNEST(Yolo(data)) AS Obj(label, bbox, score) 
-  WHERE Obj.label = 'dog' 
-    AND DogBreedClassifier(Crop(data, bbox)) = 'great dane' 
-    AND Color(Crop(data, bbox)) = 'black';
-```
+   ⚡️ **Parallel Query Execution**: EvaDB runs the app in parallel on all the available hardware resources (CPUs and GPUs).
 
-By reusing the results of the first query and reordering the predicates based on the available cached inference results, EvaDB runs the second query **10x faster**!
+   🎯 **Model Ordering**: EvaDB optimizes the order in which models are evaluated (e.g., runs the faster, more selective model first).
 
 ## Architecture Diagram
 
-This diagram presents the key components of EvaDB. EvaDB's AI-centric Query Optimizer takes a parsed query as input and generates a query plan that is then executed by the Query Engine. The Query Engine hits multiple storage engines to retrieve the data required for efficiently running the query:
+This diagram presents the key components of EvaDB. EvaDB's AI-centric query optimizer takes a query as input and generates a query plan that is executed by the query engine. The query engine hits the relevant storage engines to quickly retrieve the data required for efficiently running the query:
 1. Structured data (SQL database system connected via `sqlalchemy`).
-2. Unstructured media data (on cloud buckets or local filesystem).
-3. Vector data (vector database system).
+2. Unstructured media data (on cloud buckets/local filesystem).
+3. Feature data (vector database system).
 
-<img width="700" alt="Architecture Diagram" src="https://github.com/georgia-tech-db/eva/assets/5521975/01452ec9-87d9-4d27-90b2-c0b1ab29b16c">
+<img width="500" alt="Architecture Diagram" src="https://github.com/georgia-tech-db/eva/assets/5521975/01452ec9-87d9-4d27-90b2-c0b1ab29b16c">
 
 ## Screenshots
 
 ### 🔮 [Traffic Analysis](https://evadb.readthedocs.io/en/stable/source/tutorials/02-object-detection.html) (Object Detection Model)
 | Source Video  | Query Result |
 |---------------|--------------|
 |<img alt="Source Video" src="https://github.com/georgia-tech-db/eva/releases/download/v0.1.0/traffic-input.webp" width="300"> |<img alt="Query Result" src="https://github.com/georgia-tech-db/eva/releases/download/v0.1.0/traffic-output.webp" width="300"> |
```

#### html2text {}

```diff
@@ -1,110 +1,98 @@
-Metadata-Version: 2.1 Name: evadb Version: 0.2.9 Summary: EvaDB AI-Relational
+Metadata-Version: 2.1 Name: evadb Version: 0.3.0 Summary: EvaDB AI-Relational
 Database System Home-page: https://github.com/georgia-tech-db/eva Download-URL:
 https://github.com/georgia-tech-db/eva Author: Georgia Tech Database Group
 Author-email: arulraj@gatech.edu License: Apache License 2.0 Classifier:
 Development Status :: 5 - Production/Stable Classifier: License :: OSI Approved
 :: Apache Software License Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9 Classifier: Programming
 Language :: Python :: 3.10 Requires-Python: >=3.8 Description-Content-Type:
-text/markdown Provides-Extra: dev License-File: LICENSE.txt # EvaDB AI-SQL
-Database System
+text/markdown Provides-Extra: ray Provides-Extra: vision Provides-Extra:
+document Provides-Extra: udf Provides-Extra: notebook Provides-Extra: qdrant
+Provides-Extra: dev License-File: LICENSE.txt # EvaDB AI-SQL Database System
 [Open_EvaDB_on_Colab] [Slack] [Twitter] [Roadmap] [PyPI] [License] [Coverage
 Status] [Downloads] [Python Versions]
 **** EvaDB is a database system for building simpler and faster AI-powered
 applications. ****
-EvaDB is an AI-SQL database system for developing applications powered by AI
-models. We aim to simplify the development and deployment of AI-powered
-applications that operate on structured (tables, feature stores) and
-unstructured data (text documents, videos, PDFs, podcasts, etc.). EvaDB
-accelerates AI pipelines by 10x using a collection of performance optimizations
-inspired by time-tested SQL database systems, including data-parallel query
-execution, function caching, sampling, and cost-based predicate reordering.
-EvaDB supports an AI-oriented query language tailored for analyzing both
-structured and unstructured data. It has first-class support for PyTorch,
-Hugging Face, YOLO, and Open AI models. The high-level Python and SQL APIs
-allows even beginners to use EvaDB in a few lines of code. Advanced users can
-define custom user-defined functions that wrap around any AI model or Python
-library. EvaDB is fully implemented in Python and licensed under the Apache
-license. ## Quick Links - [Features](#features) - [Quick Start](#quick-start) -
-[Documentation](#documentation) - [Roadmap](https://github.com/orgs/georgia-
-tech-db/projects/3) - [Architecture Diagram](#architecture-diagram) -
-[Illustrative Applications](#illustrative-applications) - [Screenshots]
-(#screenshots) - [Community and Support](#community-and-support) - [Twitter]
-(https://twitter.com/evadb_ai) - [Contributing](#contributing) - [License]
-(#license) ## Features - ð® Build simpler AI-powered applications using short
-Python or SQL queries - â¡ï¸ 10x faster applications using AI-centric query
-optimization - ð° Save money spent on GPUs - ð First-class support for
-your custom deep learning models through user-defined functions - ð¦ Built-in
-caching to eliminate redundant model invocations across queries - â¨ï¸ First-
-class support for PyTorch, Hugging Face, YOLO, and Open AI models - ð
-Installable via pip and fully implemented in Python ## Illustrative
-Applications Here are some illustrative EvaDB-powered applications (each
-Jupyter notebook can be opened on Google Colab): * ð® Reddit_Image_Similarity
-Search * ð® ChatGPT-based_video_question_answering * ð® Quering_PDF
-documents * ð® Analysing_traffic_flow_with_YOLO * ð® Examining_emotion
-palette_of_a_movie * ð® Image_segmentation_with_Hugging_Face * ð®
-Recognizing_license_plates * ð® Analysing_toxicity_of_social_media_memes ##
-Documentation * [Detailed Documentation](https://evadb.readthedocs.io/) - The
-Getting_Started page shows how you can use EvaDB for different AI tasks and how
-you can easily extend EvaDB to support your custom deep learning model through
-user-defined functions. - The User_Guides section contains Jupyter Notebooks
-that demonstrate how to use various features of EvaDB. Each notebook includes a
-link to Google Colab, where you can run the code yourself. * [Tutorials](https:
-//github.com/georgia-tech-db/eva/blob/master/tutorials/03-emotion-
-analysis.ipynb) * [Join us on Slack](https://join.slack.com/t/eva-db/
-shared_invite/zt-1i10zyddy-PlJ4iawLdurDv~aIAq90Dg) * [Follow us on Twitter]
-(https://twitter.com/evadb_ai) * [Medium-Term Roadmap](https://github.com/orgs/
-georgia-tech-db/projects/3) * [Demo](https://evadb.readthedocs.io/en/stable/
-source/tutorials/08-chatgpt.html) ## Quick Start - Install EvaDB using the pip
-package manager. EvaDB supports Python versions >= 3.8: ```shell pip install
-evadb ``` - To launch and connect to an EvaDB server in a Jupyter notebook,
-check out this [illustrative emotion analysis notebook](https://github.com/
-georgia-tech-db/eva/blob/master/tutorials/03-emotion-analysis.ipynb): ```shell
-cursor = connect_to_server() ``` - Load a video onto the EvaDB server (we use
-[ua_detrac.mp4](data/ua_detrac/ua_detrac.mp4) for illustration): ```mysql LOAD
-VIDEO "data/ua_detrac/ua_detrac.mp4" INTO TrafficVideo; ``` - That's it! You
-can now run queries over the loaded video: ```mysql SELECT id, data FROM
-TrafficVideo WHERE id < 5; ``` - Search for frames in the video that contain a
-car: ```mysql SELECT id, data FROM TrafficVideo WHERE ['car'] <@ Yolo
-(data).labels; ``` | Source Video | Query Result | |---------------|-----------
----| |[Source Video] |[Query Result] | - Search for frames in the video that
-contain a pedestrian and a car: ```mysql SELECT id, data FROM TrafficVideo
-WHERE ['pedestrian', 'car'] <@ Yolo(data).labels; ``` - Search for frames with
-more than three cars: ```mysql SELECT id, data FROM TrafficVideo WHERE
-ArrayCount(Yolo(data).labels, 'car') > 3; ``` - **Use your custom deep learning
-model in queries** with a user-defined function (UDF): ```mysql CREATE UDF IF
-NOT EXISTS Yolo TYPE ultralytics 'model' 'yolov8m.pt'; ``` - **Chain multiple
-models in a single query** to set up useful AI pipelines. ```mysql -- Analyse
-emotions of faces in a video SELECT id, bbox, EmotionDetector(Crop(data, bbox))
-FROM MovieVideo JOIN LATERAL UNNEST(FaceDetector(data)) AS Face(bbox, conf)
-WHERE id < 15; ``` - **EvaDB runs queries faster using its AI-centric query
-optimizer**. Two key optimizations are: ð¾ **Caching**: EvaDB automatically
-caches and reuses previous query results (especially model inference results),
-eliminating redundant computation and reducing query processing time. ð¯
-**Predicate Reordering**: EvaDB optimizes the order in which the query
-predicates are evaluated (e.g., runs the faster, more selective model first),
-leading to faster queries and lower inference costs. Consider these two
-exploratory queries on a dataset of dog images: [https://github.com/georgia-
-tech-db/eva/blob/master/data/assets/eva_performance_comparison.png?raw=true]
- ```mysql -- Query 1: Find all images of black-colored dogs SELECT id, bbox
-FROM dogs JOIN LATERAL UNNEST(Yolo(data)) AS Obj(label, bbox, score) WHERE
-Obj.label = 'dog' AND Color(Crop(data, bbox)) = 'black'; -- Query 2: Find all
-Great Danes that are black-colored SELECT id, bbox FROM dogs JOIN LATERAL
-UNNEST(Yolo(data)) AS Obj(label, bbox, score) WHERE Obj.label = 'dog' AND
-DogBreedClassifier(Crop(data, bbox)) = 'great dane' AND Color(Crop(data, bbox))
-= 'black'; ``` By reusing the results of the first query and reordering the
-predicates based on the available cached inference results, EvaDB runs the
-second query **10x faster**! ## Architecture Diagram This diagram presents the
-key components of EvaDB. EvaDB's AI-centric Query Optimizer takes a parsed
-query as input and generates a query plan that is then executed by the Query
-Engine. The Query Engine hits multiple storage engines to retrieve the data
+EvaDB is a database system for developing AI apps. We aim to simplify the
+development and deployment of AI-powered apps that operate on unstructured data
+(text documents, videos, PDFs, podcasts, etc.) and structured data (tables,
+vector index). The high-level Python and SQL APIs allow beginners to use EvaDB
+in a few lines of code. Advanced users can define custom user-defined functions
+that wrap around any AI model or Python library. EvaDB is fully implemented in
+Python and licensed under the Apache license. ## Quick Links - [Features]
+(#features) - [Quick Start](#quick-start) - [Documentation](#documentation) -
+[Community and Support](#community-and-support) - [Twitter](https://
+twitter.com/evadb_ai) ## Features - ð® Build simpler AI-powered applications
+using Python functions or SQL queries - â¡ï¸ 10x faster applications using
+AI-centric query optimization - ð° Save money spent on GPUs - ð First-
+class support for your custom deep learning models through user-defined
+functions - ð¦ Built-in caching to eliminate redundant model invocations
+across queries - â¨ï¸ First-class support for PyTorch, Hugging Face, YOLO,
+and Open AI models - ð Installable via pip and fully implemented in Python
+## Illustrative Applications Here are some illustrative EvaDB-powered
+applications (each Jupyter notebook can be opened on Google Colab): * ð®
+PrivateGPT * ð® ChatGPT-based_Video_Question_Answering * ð® Querying_PDF
+Documents * ð® Analysing_Traffic_Flow_with_YOLO * ð® Examining_Emotions_of
+Movie * ð® Image_Segmentation_with_Hugging_Face ## Documentation *
+[Documentation](https://evadb.readthedocs.io/) - The Getting_Started page shows
+how you can use EvaDB for different AI tasks and how you can easily extend
+EvaDB to support your custom deep learning model through user-defined
+functions. - The User_Guides section contains Jupyter Notebooks that
+demonstrate how to use various features of EvaDB. Each notebook includes a link
+to Google Colab, where you can run the code yourself. * [Join us on Slack]
+(https://join.slack.com/t/eva-db/shared_invite/zt-1i10zyddy-
+PlJ4iawLdurDv~aIAq90Dg) * [Follow us on Twitter](https://twitter.com/evadb_ai)
+* [Roadmap](https://github.com/orgs/georgia-tech-db/projects/3) ## Quick Start
+- Step 1: Install EvaDB using pip. EvaDB supports Python versions >= `3.8`:
+```shell pip install evadb ``` - Step 2: Write your AI app! ```python import
+evadb # Grab a EvaDB cursor to load data and run queries cursor = evadb.connect
+().cursor() # Load a collection of news videos into the 'news_videos' table #
+This command returns a Pandas Dataframe with the query's output # In this case,
+the output indicates the number of loaded videos cursor.load
+( file_regex="news_videos/*.mp4", format="VIDEO", table_name="news_videos" ).df
+() # Define a function that wraps around your deep learning model # Here, this
+function wraps around an off-the-shelf speech-to-text (Whisper) model # Such
+functions are known as user-defined functions or UDFs # So, we are creating a
+Whisper UDF here # After creating the UDF, we can use the function in any query
+cursor.create_udf( udf_name="SpeechRecognizer", type="HuggingFace",
+task='automatic-speech-recognition', model='openai/whisper-base' ).df() # EvaDB
+automatically extract the audio from the video # We only need to run the
+SpeechRecongizer UDF on the 'audio' column # to get the transcript and persist
+it in a table called 'transcripts' cursor.query( """CREATE TABLE transcripts AS
+SELECT SpeechRecognizer(audio) from news_videos;""" ).df() # We next
+incrementally construct the ChatGPT query using EvaDB's Python API # The query
+is based on the 'transcripts' table # This table has a column called 'text'
+with the transcript text query = cursor.table('transcripts') # Since ChatGPT is
+a built-in function, we don't have to define it # We can just directly use it
+in the query # We need to set the OPENAI_KEY as an environment variable
+os.environ["OPENAI_KEY"] = OPENAI_KEY query = query.select("ChatGPT('Is this
+video summary related to LLMs', text)") # Finally, we run the query to get the
+results as a dataframe response = query.df() ``` - **Chain multiple models in a
+single query to set up useful AI pipelines** ```python # Analyse emotions of
+actors in an Interstellar movie clip using PyTorch models query = cursor.table
+("Interstellar") # Get faces using a `FaceDetector` function query =
+query.cross_apply("UNNEST(FaceDetector(data))", "Face(bounding_box,
+confidence)") # Focus only on frames 100 through 200 in the clip query =
+query.filter("id > 100 AND id < 200") # Get the emotions of the detected faces
+using a `EmotionDetector` function query = query.select("id, bbox,
+EmotionDetector(Crop(data, bounding_box))") # Run the query and get the query
+result as a dataframe response = query.df() ``` - **EvaDB runs AI apps 10--100x
+faster using its AI-centric query optimizer**. Three key built-in optimizations
+are: ð¾ **Caching**: EvaDB automatically caches and reuses model inference
+results. â¡ï¸ **Parallel Query Execution**: EvaDB runs the app in parallel on
+all the available hardware resources (CPUs and GPUs). ð¯ **Model Ordering**:
+EvaDB optimizes the order in which models are evaluated (e.g., runs the faster,
+more selective model first). ## Architecture Diagram This diagram presents the
+key components of EvaDB. EvaDB's AI-centric query optimizer takes a query as
+input and generates a query plan that is executed by the query engine. The
+query engine hits the relevant storage engines to quickly retrieve the data
 required for efficiently running the query: 1. Structured data (SQL database
 system connected via `sqlalchemy`). 2. Unstructured media data (on cloud
-buckets or local filesystem). 3. Vector data (vector database system).
+buckets/local filesystem). 3. Feature data (vector database system).
 [Architecture Diagram] ## Screenshots ### ð® [Traffic Analysis](https://
 evadb.readthedocs.io/en/stable/source/tutorials/02-object-detection.html)
 (Object Detection Model) | Source Video | Query Result | |---------------|-----
 ---------| |[Source Video] |[Query Result] | ### ð® [PDF Question Answering]
 (https://evadb.readthedocs.io/en/stable/source/tutorials/12-query-pdf.html)
 (Question Answering Model) | App | |-----| |[Source Video] | ### ð® [MNIST
 Digit Recognition](https://evadb.readthedocs.io/en/stable/source/tutorials/01-
```

### Comparing `evadb-0.2.9/README.md` & `evadb-0.3.0/evadb.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,184 +1,191 @@
+Metadata-Version: 2.1
+Name: evadb
+Version: 0.3.0
+Summary: EvaDB AI-Relational Database System
+Home-page: https://github.com/georgia-tech-db/eva
+Download-URL: https://github.com/georgia-tech-db/eva
+Author: Georgia Tech Database Group
+Author-email: arulraj@gatech.edu
+License: Apache License 2.0
+Classifier: Development Status :: 5 - Production/Stable
+Classifier: License :: OSI Approved :: Apache Software License
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Requires-Python: >=3.8
+Description-Content-Type: text/markdown
+Provides-Extra: ray
+Provides-Extra: vision
+Provides-Extra: document
+Provides-Extra: udf
+Provides-Extra: notebook
+Provides-Extra: qdrant
+Provides-Extra: dev
+License-File: LICENSE.txt
+
 # EvaDB AI-SQL Database System
 
 <div>
         <a href="https://colab.research.google.com/github/georgia-tech-db/eva/blob/master/tutorials/03-emotion-analysis.ipynb">
             <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open EvaDB on Colab"/>
         </a>
         <a href="https://join.slack.com/t/eva-db/shared_invite/zt-1i10zyddy-PlJ4iawLdurDv~aIAq90Dg">
-            <img alt="Slack" src="https://img.shields.io/badge/slack-eva-ff69b4.svg?logo=slack">
+            <img alt="Slack" src="https://img.shields.io/badge/slack-evadb-ff69b4.svg?logo=slack">
         </a>          
         <a href="https://twitter.com/evadb_ai">
-            <img alt="Twitter" src="https://img.shields.io/badge/twitter-eva-bde1ee.svg?logo=twitter">
+            <img alt="Twitter" src="https://img.shields.io/badge/twitter-evadb-bde1ee.svg?logo=twitter">
         </a>  
         <a href="https://github.com/orgs/georgia-tech-db/projects/3">
-            <img src="https://img.shields.io/badge/eva-roadmap-a6c096" alt="Roadmap"/>
+            <img src="https://img.shields.io/badge/evadb-roadmap-a6c096" alt="Roadmap"/>
         </a>
         <img alt="PyPI" src="https://img.shields.io/pypi/v/evadb.svg"/>
         <img alt="License" src="https://img.shields.io/badge/license-Apache%202-brightgreen.svg?logo=apache"/>
         <img alt="Coverage Status" src="https://coveralls.io/repos/github/georgia-tech-db/eva/badge.svg?branch=master"/>     
         <a href="https://pepy.tech/project/evadb">
-          <img alt="Downloads" src="https://static.pepy.tech/badge/evadb/month"/>
+          <img alt="Downloads" src="https://static.pepy.tech/badge/evadb"/>
         </a>
         <img alt="Python Versions" src="https://img.shields.io/badge/Python--versions-3.8%20|%203.9%20|%203.10-brightgreen"/>       
 </div>
 
 <p align="center"> <b><h3>EvaDB is a database system for building simpler and faster AI-powered applications.</b></h3> </p>
 
-EvaDB is an AI-SQL database system for developing applications powered by AI models. We aim to simplify the development and deployment of AI-powered applications that operate on structured (tables, feature stores) and unstructured data (text documents, videos, PDFs, podcasts, etc.).
-
-EvaDB accelerates AI pipelines by 10x using a collection of performance optimizations inspired by time-tested SQL database systems, including data-parallel query execution, function caching, sampling, and cost-based predicate reordering. EvaDB supports an AI-oriented query language tailored for analyzing both structured and unstructured data. It has first-class support for PyTorch, Hugging Face, YOLO, and Open AI models.
+EvaDB is a database system for developing AI apps. We aim to simplify the development and deployment of AI-powered apps that operate on unstructured data (text documents, videos, PDFs, podcasts, etc.) and structured data (tables, vector index).
 
-The high-level Python and SQL APIs allows even beginners to use EvaDB in a few lines of code. Advanced users can define custom user-defined functions that wrap around any AI model or Python library. EvaDB is fully implemented in Python and licensed under the Apache license.
+The high-level Python and SQL APIs allow beginners to use EvaDB in a few lines of code. Advanced users can define custom user-defined functions that wrap around any AI model or Python library. EvaDB is fully implemented in Python and licensed under the Apache license.
 
 ## Quick Links
 
 - [Features](#features)
 - [Quick Start](#quick-start)
 - [Documentation](#documentation)
-- [Roadmap](https://github.com/orgs/georgia-tech-db/projects/3)
-- [Architecture Diagram](#architecture-diagram)
-- [Illustrative Applications](#illustrative-applications)
-- [Screenshots](#screenshots)
 - [Community and Support](#community-and-support)
 - [Twitter](https://twitter.com/evadb_ai)
-- [Contributing](#contributing)
-- [License](#license)
 
 ## Features
 
-- 🔮 Build simpler AI-powered applications using short Python or SQL queries
+- 🔮 Build simpler AI-powered applications using Python functions or SQL queries
 - ⚡️ 10x faster applications using AI-centric query optimization  
 - 💰 Save money spent on GPUs
 - 🚀 First-class support for your custom deep learning models through user-defined functions
 - 📦 Built-in caching to eliminate redundant model invocations across queries
 - ⌨️ First-class support for PyTorch, Hugging Face, YOLO, and Open AI models
 - 🐍 Installable via pip and fully implemented in Python
 
 ## Illustrative Applications
 
 Here are some illustrative EvaDB-powered applications (each Jupyter notebook can be opened on Google Colab):
 
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/11-similarity-search-for-motif-mining.html">Reddit Image Similarity Search</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/08-chatgpt.html">ChatGPT-based video question answering</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/12-query-pdf.html">Quering PDF documents</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/02-object-detection.html">Analysing traffic flow with YOLO</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/03-emotion-analysis.html">Examining emotion palette of a movie</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/07-object-segmentation-huggingface.html">Image segmentation with Hugging Face</a>
- * 🔮 <a href="https://github.com/georgia-tech-db/license-plate-recognition">Recognizing license plates</a>
- * 🔮 <a href="https://github.com/georgia-tech-db/toxicity-classification">Analysing toxicity of social media memes </a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/13-privategpt.html">PrivateGPT</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/08-chatgpt.html">ChatGPT-based Video Question Answering</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/12-query-pdf.html">Querying PDF Documents</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/02-object-detection.html">Analysing Traffic Flow with YOLO</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/03-emotion-analysis.html">Examining Emotions of Movie</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/07-object-segmentation-huggingface.html">Image Segmentation with Hugging Face</a>
 
 ## Documentation
 
-* [Detailed Documentation](https://evadb.readthedocs.io/)
+* [Documentation](https://evadb.readthedocs.io/)
   - The <a href="https://evadb.readthedocs.io/en/stable/source/overview/installation.html">Getting Started</a> page shows how you can use EvaDB for different AI tasks and how you can easily extend EvaDB to support your custom deep learning model through user-defined functions.
-  - The <a href="https://evadb.readthedocs.io/en/latest/source/tutorials/11-similarity-search-for-motif-mining.html">User Guides</a> section contains Jupyter Notebooks that demonstrate how to use various features of EvaDB. Each notebook includes a link to Google Colab, where you can run the code yourself.
-* [Tutorials](https://github.com/georgia-tech-db/eva/blob/master/tutorials/03-emotion-analysis.ipynb)
+  - The <a href="https://evadb.readthedocs.io/en/latest/source/tutorials/13-privategpt.html">User Guides</a> section contains Jupyter Notebooks that demonstrate how to use various features of EvaDB. Each notebook includes a link to Google Colab, where you can run the code yourself.
 * [Join us on Slack](https://join.slack.com/t/eva-db/shared_invite/zt-1i10zyddy-PlJ4iawLdurDv~aIAq90Dg)
 * [Follow us on Twitter](https://twitter.com/evadb_ai)
-* [Medium-Term Roadmap](https://github.com/orgs/georgia-tech-db/projects/3)
-* [Demo](https://evadb.readthedocs.io/en/stable/source/tutorials/08-chatgpt.html)
+* [Roadmap](https://github.com/orgs/georgia-tech-db/projects/3)
 
 ## Quick Start
 
-- Install EvaDB using the pip package manager. EvaDB supports Python versions >= 3.8:
+- Step 1: Install EvaDB using pip. EvaDB supports Python versions >= `3.8`:
 
 ```shell
 pip install evadb
 ```
 
-- To launch and connect to an EvaDB server in a Jupyter notebook, check out this [illustrative emotion analysis notebook](https://github.com/georgia-tech-db/eva/blob/master/tutorials/03-emotion-analysis.ipynb):
-```shell
-cursor = connect_to_server()
-```
-
-- Load a video onto the EvaDB server (we use [ua_detrac.mp4](data/ua_detrac/ua_detrac.mp4) for illustration):
-
-```mysql
-LOAD VIDEO "data/ua_detrac/ua_detrac.mp4" INTO TrafficVideo;
-```
-
-- That's it! You can now run queries over the loaded video:
-
-```mysql
-SELECT id, data FROM TrafficVideo WHERE id < 5;
-```
-
-- Search for frames in the video that contain a car:
-
-```mysql
-SELECT id, data FROM TrafficVideo WHERE ['car'] <@ Yolo(data).labels;
-```
-| Source Video  | Query Result |
-|---------------|--------------|
-|<img alt="Source Video" src="https://github.com/georgia-tech-db/eva/releases/download/v0.1.0/traffic-input.webp" width="300"> |<img alt="Query Result" src="https://github.com/georgia-tech-db/eva/releases/download/v0.1.0/traffic-output.webp" width="300"> |
-
-- Search for frames in the video that contain a pedestrian and a car:
-
-```mysql
-SELECT id, data FROM TrafficVideo WHERE ['pedestrian', 'car'] <@ Yolo(data).labels;
-```
-
-- Search for frames with more than three cars:
-
-```mysql
-SELECT id, data FROM TrafficVideo WHERE ArrayCount(Yolo(data).labels, 'car') > 3;
-```
-
-- **Use your custom deep learning model in queries** with a user-defined function (UDF):
+- Step 2: Write your AI app!
 
-```mysql
-CREATE UDF IF NOT EXISTS Yolo
-TYPE  ultralytics
-'model' 'yolov8m.pt';
-```
+```python
+import evadb
 
-- **Chain multiple models in a single query** to set up useful AI pipelines.
+# Grab a EvaDB cursor to load data and run queries
+cursor = evadb.connect().cursor()
 
-```mysql
-   -- Analyse emotions of faces in a video
-   SELECT id, bbox, EmotionDetector(Crop(data, bbox)) 
-   FROM MovieVideo JOIN LATERAL UNNEST(FaceDetector(data)) AS Face(bbox, conf)  
-   WHERE id < 15;
+# Load a collection of news videos into the 'news_videos' table
+# This command returns a Pandas Dataframe with the query's output
+# In this case, the output indicates the number of loaded videos
+cursor.load(
+    file_regex="news_videos/*.mp4",
+    format="VIDEO",
+    table_name="news_videos"
+).df()
+
+# Define a function that wraps around your deep learning model
+# Here, this function wraps around an off-the-shelf speech-to-text (Whisper) model
+# Such functions are known as user-defined functions or UDFs
+# So, we are creating a Whisper UDF here
+# After creating the UDF, we can use the function in any query
+cursor.create_udf(
+    udf_name="SpeechRecognizer",
+    type="HuggingFace",
+    task='automatic-speech-recognition',
+    model='openai/whisper-base'
+).df()
+
+# EvaDB automatically extract the audio from the video
+# We only need to run the SpeechRecongizer UDF on the 'audio' column
+# to get the transcript and persist it in a table called 'transcripts'
+cursor.query(
+    """CREATE TABLE transcripts AS
+       SELECT SpeechRecognizer(audio) from news_videos;"""
+).df()
+
+# We next incrementally construct the ChatGPT query using EvaDB's Python API
+# The query is based on the 'transcripts' table
+# This table has a column called 'text' with the transcript text
+query = cursor.table('transcripts')
+
+# Since ChatGPT is a built-in function, we don't have to define it
+# We can just directly use it in the query
+# We need to set the OPENAI_KEY as an environment variable
+os.environ["OPENAI_KEY"] = OPENAI_KEY
+query = query.select("ChatGPT('Is this video summary related to LLMs', text)")
+
+# Finally, we run the query to get the results as a dataframe
+response = query.df()
+```
+
+- **Chain multiple models in a single query to set up useful AI pipelines**
+
+```python
+# Analyse emotions of actors in an Interstellar movie clip using PyTorch models
+query = cursor.table("Interstellar")
+# Get faces using a `FaceDetector` function
+query = query.cross_apply("UNNEST(FaceDetector(data))", "Face(bounding_box, confidence)")
+# Focus only on frames 100 through 200 in the clip
+query = query.filter("id > 100 AND id < 200")
+# Get the emotions of the detected faces using a `EmotionDetector` function
+query = query.select("id, bbox, EmotionDetector(Crop(data, bounding_box))")
+
+# Run the query and get the query result as a dataframe
+response = query.df()
 ```
+- **EvaDB runs AI apps 10--100x faster using its AI-centric query optimizer**. Three key built-in optimizations are:
 
-- **EvaDB runs queries faster using its AI-centric query optimizer**. Two key optimizations are:
-
-   💾 **Caching**: EvaDB automatically caches and reuses previous query results (especially model inference results), eliminating redundant computation and reducing query processing time.
+   💾 **Caching**: EvaDB automatically caches and reuses model inference results.
 
-   🎯 **Predicate Reordering**: EvaDB optimizes the order in which the query predicates are evaluated (e.g., runs the faster, more selective model first), leading to faster queries and lower inference costs.
-
-Consider these two exploratory queries on a dataset of dog images:
-<img align="right" style="display:inline;" width="40%" src="https://github.com/georgia-tech-db/eva/blob/master/data/assets/eva_performance_comparison.png?raw=true"></a>
-
-```mysql
-  -- Query 1: Find all images of black-colored dogs
-  SELECT id, bbox FROM dogs 
-  JOIN LATERAL UNNEST(Yolo(data)) AS Obj(label, bbox, score) 
-  WHERE Obj.label = 'dog' 
-    AND Color(Crop(data, bbox)) = 'black'; 
-
-  -- Query 2: Find all Great Danes that are black-colored
-  SELECT id, bbox FROM dogs 
-  JOIN LATERAL UNNEST(Yolo(data)) AS Obj(label, bbox, score) 
-  WHERE Obj.label = 'dog' 
-    AND DogBreedClassifier(Crop(data, bbox)) = 'great dane' 
-    AND Color(Crop(data, bbox)) = 'black';
-```
+   ⚡️ **Parallel Query Execution**: EvaDB runs the app in parallel on all the available hardware resources (CPUs and GPUs).
 
-By reusing the results of the first query and reordering the predicates based on the available cached inference results, EvaDB runs the second query **10x faster**!
+   🎯 **Model Ordering**: EvaDB optimizes the order in which models are evaluated (e.g., runs the faster, more selective model first).
 
 ## Architecture Diagram
 
-This diagram presents the key components of EvaDB. EvaDB's AI-centric Query Optimizer takes a parsed query as input and generates a query plan that is then executed by the Query Engine. The Query Engine hits multiple storage engines to retrieve the data required for efficiently running the query:
+This diagram presents the key components of EvaDB. EvaDB's AI-centric query optimizer takes a query as input and generates a query plan that is executed by the query engine. The query engine hits the relevant storage engines to quickly retrieve the data required for efficiently running the query:
 1. Structured data (SQL database system connected via `sqlalchemy`).
-2. Unstructured media data (on cloud buckets or local filesystem).
-3. Vector data (vector database system).
+2. Unstructured media data (on cloud buckets/local filesystem).
+3. Feature data (vector database system).
 
-<img width="700" alt="Architecture Diagram" src="https://github.com/georgia-tech-db/eva/assets/5521975/01452ec9-87d9-4d27-90b2-c0b1ab29b16c">
+<img width="500" alt="Architecture Diagram" src="https://github.com/georgia-tech-db/eva/assets/5521975/01452ec9-87d9-4d27-90b2-c0b1ab29b16c">
 
 ## Screenshots
 
 ### 🔮 [Traffic Analysis](https://evadb.readthedocs.io/en/stable/source/tutorials/02-object-detection.html) (Object Detection Model)
 | Source Video  | Query Result |
 |---------------|--------------|
 |<img alt="Source Video" src="https://github.com/georgia-tech-db/eva/releases/download/v0.1.0/traffic-input.webp" width="300"> |<img alt="Query Result" src="https://github.com/georgia-tech-db/eva/releases/download/v0.1.0/traffic-output.webp" width="300"> |
```

#### html2text {}

```diff
@@ -1,101 +1,98 @@
-# EvaDB AI-SQL Database System
+Metadata-Version: 2.1 Name: evadb Version: 0.3.0 Summary: EvaDB AI-Relational
+Database System Home-page: https://github.com/georgia-tech-db/eva Download-URL:
+https://github.com/georgia-tech-db/eva Author: Georgia Tech Database Group
+Author-email: arulraj@gatech.edu License: Apache License 2.0 Classifier:
+Development Status :: 5 - Production/Stable Classifier: License :: OSI Approved
+:: Apache Software License Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9 Classifier: Programming
+Language :: Python :: 3.10 Requires-Python: >=3.8 Description-Content-Type:
+text/markdown Provides-Extra: ray Provides-Extra: vision Provides-Extra:
+document Provides-Extra: udf Provides-Extra: notebook Provides-Extra: qdrant
+Provides-Extra: dev License-File: LICENSE.txt # EvaDB AI-SQL Database System
 [Open_EvaDB_on_Colab] [Slack] [Twitter] [Roadmap] [PyPI] [License] [Coverage
 Status] [Downloads] [Python Versions]
 **** EvaDB is a database system for building simpler and faster AI-powered
 applications. ****
-EvaDB is an AI-SQL database system for developing applications powered by AI
-models. We aim to simplify the development and deployment of AI-powered
-applications that operate on structured (tables, feature stores) and
-unstructured data (text documents, videos, PDFs, podcasts, etc.). EvaDB
-accelerates AI pipelines by 10x using a collection of performance optimizations
-inspired by time-tested SQL database systems, including data-parallel query
-execution, function caching, sampling, and cost-based predicate reordering.
-EvaDB supports an AI-oriented query language tailored for analyzing both
-structured and unstructured data. It has first-class support for PyTorch,
-Hugging Face, YOLO, and Open AI models. The high-level Python and SQL APIs
-allows even beginners to use EvaDB in a few lines of code. Advanced users can
-define custom user-defined functions that wrap around any AI model or Python
-library. EvaDB is fully implemented in Python and licensed under the Apache
-license. ## Quick Links - [Features](#features) - [Quick Start](#quick-start) -
-[Documentation](#documentation) - [Roadmap](https://github.com/orgs/georgia-
-tech-db/projects/3) - [Architecture Diagram](#architecture-diagram) -
-[Illustrative Applications](#illustrative-applications) - [Screenshots]
-(#screenshots) - [Community and Support](#community-and-support) - [Twitter]
-(https://twitter.com/evadb_ai) - [Contributing](#contributing) - [License]
-(#license) ## Features - ð® Build simpler AI-powered applications using short
-Python or SQL queries - â¡ï¸ 10x faster applications using AI-centric query
-optimization - ð° Save money spent on GPUs - ð First-class support for
-your custom deep learning models through user-defined functions - ð¦ Built-in
-caching to eliminate redundant model invocations across queries - â¨ï¸ First-
-class support for PyTorch, Hugging Face, YOLO, and Open AI models - ð
-Installable via pip and fully implemented in Python ## Illustrative
-Applications Here are some illustrative EvaDB-powered applications (each
-Jupyter notebook can be opened on Google Colab): * ð® Reddit_Image_Similarity
-Search * ð® ChatGPT-based_video_question_answering * ð® Quering_PDF
-documents * ð® Analysing_traffic_flow_with_YOLO * ð® Examining_emotion
-palette_of_a_movie * ð® Image_segmentation_with_Hugging_Face * ð®
-Recognizing_license_plates * ð® Analysing_toxicity_of_social_media_memes ##
-Documentation * [Detailed Documentation](https://evadb.readthedocs.io/) - The
-Getting_Started page shows how you can use EvaDB for different AI tasks and how
-you can easily extend EvaDB to support your custom deep learning model through
-user-defined functions. - The User_Guides section contains Jupyter Notebooks
-that demonstrate how to use various features of EvaDB. Each notebook includes a
-link to Google Colab, where you can run the code yourself. * [Tutorials](https:
-//github.com/georgia-tech-db/eva/blob/master/tutorials/03-emotion-
-analysis.ipynb) * [Join us on Slack](https://join.slack.com/t/eva-db/
-shared_invite/zt-1i10zyddy-PlJ4iawLdurDv~aIAq90Dg) * [Follow us on Twitter]
-(https://twitter.com/evadb_ai) * [Medium-Term Roadmap](https://github.com/orgs/
-georgia-tech-db/projects/3) * [Demo](https://evadb.readthedocs.io/en/stable/
-source/tutorials/08-chatgpt.html) ## Quick Start - Install EvaDB using the pip
-package manager. EvaDB supports Python versions >= 3.8: ```shell pip install
-evadb ``` - To launch and connect to an EvaDB server in a Jupyter notebook,
-check out this [illustrative emotion analysis notebook](https://github.com/
-georgia-tech-db/eva/blob/master/tutorials/03-emotion-analysis.ipynb): ```shell
-cursor = connect_to_server() ``` - Load a video onto the EvaDB server (we use
-[ua_detrac.mp4](data/ua_detrac/ua_detrac.mp4) for illustration): ```mysql LOAD
-VIDEO "data/ua_detrac/ua_detrac.mp4" INTO TrafficVideo; ``` - That's it! You
-can now run queries over the loaded video: ```mysql SELECT id, data FROM
-TrafficVideo WHERE id < 5; ``` - Search for frames in the video that contain a
-car: ```mysql SELECT id, data FROM TrafficVideo WHERE ['car'] <@ Yolo
-(data).labels; ``` | Source Video | Query Result | |---------------|-----------
----| |[Source Video] |[Query Result] | - Search for frames in the video that
-contain a pedestrian and a car: ```mysql SELECT id, data FROM TrafficVideo
-WHERE ['pedestrian', 'car'] <@ Yolo(data).labels; ``` - Search for frames with
-more than three cars: ```mysql SELECT id, data FROM TrafficVideo WHERE
-ArrayCount(Yolo(data).labels, 'car') > 3; ``` - **Use your custom deep learning
-model in queries** with a user-defined function (UDF): ```mysql CREATE UDF IF
-NOT EXISTS Yolo TYPE ultralytics 'model' 'yolov8m.pt'; ``` - **Chain multiple
-models in a single query** to set up useful AI pipelines. ```mysql -- Analyse
-emotions of faces in a video SELECT id, bbox, EmotionDetector(Crop(data, bbox))
-FROM MovieVideo JOIN LATERAL UNNEST(FaceDetector(data)) AS Face(bbox, conf)
-WHERE id < 15; ``` - **EvaDB runs queries faster using its AI-centric query
-optimizer**. Two key optimizations are: ð¾ **Caching**: EvaDB automatically
-caches and reuses previous query results (especially model inference results),
-eliminating redundant computation and reducing query processing time. ð¯
-**Predicate Reordering**: EvaDB optimizes the order in which the query
-predicates are evaluated (e.g., runs the faster, more selective model first),
-leading to faster queries and lower inference costs. Consider these two
-exploratory queries on a dataset of dog images: [https://github.com/georgia-
-tech-db/eva/blob/master/data/assets/eva_performance_comparison.png?raw=true]
- ```mysql -- Query 1: Find all images of black-colored dogs SELECT id, bbox
-FROM dogs JOIN LATERAL UNNEST(Yolo(data)) AS Obj(label, bbox, score) WHERE
-Obj.label = 'dog' AND Color(Crop(data, bbox)) = 'black'; -- Query 2: Find all
-Great Danes that are black-colored SELECT id, bbox FROM dogs JOIN LATERAL
-UNNEST(Yolo(data)) AS Obj(label, bbox, score) WHERE Obj.label = 'dog' AND
-DogBreedClassifier(Crop(data, bbox)) = 'great dane' AND Color(Crop(data, bbox))
-= 'black'; ``` By reusing the results of the first query and reordering the
-predicates based on the available cached inference results, EvaDB runs the
-second query **10x faster**! ## Architecture Diagram This diagram presents the
-key components of EvaDB. EvaDB's AI-centric Query Optimizer takes a parsed
-query as input and generates a query plan that is then executed by the Query
-Engine. The Query Engine hits multiple storage engines to retrieve the data
+EvaDB is a database system for developing AI apps. We aim to simplify the
+development and deployment of AI-powered apps that operate on unstructured data
+(text documents, videos, PDFs, podcasts, etc.) and structured data (tables,
+vector index). The high-level Python and SQL APIs allow beginners to use EvaDB
+in a few lines of code. Advanced users can define custom user-defined functions
+that wrap around any AI model or Python library. EvaDB is fully implemented in
+Python and licensed under the Apache license. ## Quick Links - [Features]
+(#features) - [Quick Start](#quick-start) - [Documentation](#documentation) -
+[Community and Support](#community-and-support) - [Twitter](https://
+twitter.com/evadb_ai) ## Features - ð® Build simpler AI-powered applications
+using Python functions or SQL queries - â¡ï¸ 10x faster applications using
+AI-centric query optimization - ð° Save money spent on GPUs - ð First-
+class support for your custom deep learning models through user-defined
+functions - ð¦ Built-in caching to eliminate redundant model invocations
+across queries - â¨ï¸ First-class support for PyTorch, Hugging Face, YOLO,
+and Open AI models - ð Installable via pip and fully implemented in Python
+## Illustrative Applications Here are some illustrative EvaDB-powered
+applications (each Jupyter notebook can be opened on Google Colab): * ð®
+PrivateGPT * ð® ChatGPT-based_Video_Question_Answering * ð® Querying_PDF
+Documents * ð® Analysing_Traffic_Flow_with_YOLO * ð® Examining_Emotions_of
+Movie * ð® Image_Segmentation_with_Hugging_Face ## Documentation *
+[Documentation](https://evadb.readthedocs.io/) - The Getting_Started page shows
+how you can use EvaDB for different AI tasks and how you can easily extend
+EvaDB to support your custom deep learning model through user-defined
+functions. - The User_Guides section contains Jupyter Notebooks that
+demonstrate how to use various features of EvaDB. Each notebook includes a link
+to Google Colab, where you can run the code yourself. * [Join us on Slack]
+(https://join.slack.com/t/eva-db/shared_invite/zt-1i10zyddy-
+PlJ4iawLdurDv~aIAq90Dg) * [Follow us on Twitter](https://twitter.com/evadb_ai)
+* [Roadmap](https://github.com/orgs/georgia-tech-db/projects/3) ## Quick Start
+- Step 1: Install EvaDB using pip. EvaDB supports Python versions >= `3.8`:
+```shell pip install evadb ``` - Step 2: Write your AI app! ```python import
+evadb # Grab a EvaDB cursor to load data and run queries cursor = evadb.connect
+().cursor() # Load a collection of news videos into the 'news_videos' table #
+This command returns a Pandas Dataframe with the query's output # In this case,
+the output indicates the number of loaded videos cursor.load
+( file_regex="news_videos/*.mp4", format="VIDEO", table_name="news_videos" ).df
+() # Define a function that wraps around your deep learning model # Here, this
+function wraps around an off-the-shelf speech-to-text (Whisper) model # Such
+functions are known as user-defined functions or UDFs # So, we are creating a
+Whisper UDF here # After creating the UDF, we can use the function in any query
+cursor.create_udf( udf_name="SpeechRecognizer", type="HuggingFace",
+task='automatic-speech-recognition', model='openai/whisper-base' ).df() # EvaDB
+automatically extract the audio from the video # We only need to run the
+SpeechRecongizer UDF on the 'audio' column # to get the transcript and persist
+it in a table called 'transcripts' cursor.query( """CREATE TABLE transcripts AS
+SELECT SpeechRecognizer(audio) from news_videos;""" ).df() # We next
+incrementally construct the ChatGPT query using EvaDB's Python API # The query
+is based on the 'transcripts' table # This table has a column called 'text'
+with the transcript text query = cursor.table('transcripts') # Since ChatGPT is
+a built-in function, we don't have to define it # We can just directly use it
+in the query # We need to set the OPENAI_KEY as an environment variable
+os.environ["OPENAI_KEY"] = OPENAI_KEY query = query.select("ChatGPT('Is this
+video summary related to LLMs', text)") # Finally, we run the query to get the
+results as a dataframe response = query.df() ``` - **Chain multiple models in a
+single query to set up useful AI pipelines** ```python # Analyse emotions of
+actors in an Interstellar movie clip using PyTorch models query = cursor.table
+("Interstellar") # Get faces using a `FaceDetector` function query =
+query.cross_apply("UNNEST(FaceDetector(data))", "Face(bounding_box,
+confidence)") # Focus only on frames 100 through 200 in the clip query =
+query.filter("id > 100 AND id < 200") # Get the emotions of the detected faces
+using a `EmotionDetector` function query = query.select("id, bbox,
+EmotionDetector(Crop(data, bounding_box))") # Run the query and get the query
+result as a dataframe response = query.df() ``` - **EvaDB runs AI apps 10--100x
+faster using its AI-centric query optimizer**. Three key built-in optimizations
+are: ð¾ **Caching**: EvaDB automatically caches and reuses model inference
+results. â¡ï¸ **Parallel Query Execution**: EvaDB runs the app in parallel on
+all the available hardware resources (CPUs and GPUs). ð¯ **Model Ordering**:
+EvaDB optimizes the order in which models are evaluated (e.g., runs the faster,
+more selective model first). ## Architecture Diagram This diagram presents the
+key components of EvaDB. EvaDB's AI-centric query optimizer takes a query as
+input and generates a query plan that is executed by the query engine. The
+query engine hits the relevant storage engines to quickly retrieve the data
 required for efficiently running the query: 1. Structured data (SQL database
 system connected via `sqlalchemy`). 2. Unstructured media data (on cloud
-buckets or local filesystem). 3. Vector data (vector database system).
+buckets/local filesystem). 3. Feature data (vector database system).
 [Architecture Diagram] ## Screenshots ### ð® [Traffic Analysis](https://
 evadb.readthedocs.io/en/stable/source/tutorials/02-object-detection.html)
 (Object Detection Model) | Source Video | Query Result | |---------------|-----
 ---------| |[Source Video] |[Query Result] | ### ð® [PDF Question Answering]
 (https://evadb.readthedocs.io/en/stable/source/tutorials/12-query-pdf.html)
 (Question Answering Model) | App | |-----| |[Source Video] | ### ð® [MNIST
 Digit Recognition](https://evadb.readthedocs.io/en/stable/source/tutorials/01-
```

### Comparing `evadb-0.2.9/evadb/__init__.py` & `evadb-0.3.0/evadb/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/binder/__init__.py` & `evadb-0.3.0/evadb/binder/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/binder/binder_utils.py` & `evadb-0.3.0/evadb/binder/binder_utils.py`

 * *Files 3% similar despite different names*

```diff
@@ -17,14 +17,15 @@
 import re
 from typing import TYPE_CHECKING, List
 
 from evadb.catalog.catalog_type import TableType
 from evadb.catalog.catalog_utils import (
     get_video_table_column_definitions,
     is_document_table,
+    is_pdf_table,
     is_string_col,
     is_video_table,
 )
 from evadb.expression.function_expression import FunctionExpression
 from evadb.parser.alias import Alias
 
 if TYPE_CHECKING:
@@ -84,15 +85,15 @@
 def extend_star(
     binder_context: StatementBinderContext,
 ) -> List[TupleValueExpression]:
     col_objs = binder_context._get_all_alias_and_col_name()
 
     target_list = list(
         [
-            TupleValueExpression(col_name=col_name, table_alias=alias)
+            TupleValueExpression(name=col_name, table_alias=alias)
             for alias, col_name in col_objs
         ]
     )
     return target_list
 
 
 def check_groupby_pattern(table_ref: TableRef, groupby_string: str) -> None:
@@ -113,29 +114,30 @@
         err_msg = "Grouping by frames only supported for videos"
         raise BinderError(err_msg)
 
     if suffix_string == "samples" and not is_video_table(table_ref.table.table_obj):
         err_msg = "Grouping by samples only supported for videos"
         raise BinderError(err_msg)
 
-    if suffix_string == "paragraphs" and not is_document_table(
-        table_ref.table.table_obj
-    ):
-        err_msg = "Grouping by paragraphs only supported for documents"
+    if suffix_string == "paragraphs" and not is_pdf_table(table_ref.table.table_obj):
+        err_msg = "Grouping by paragraphs only supported for pdf tables"
         raise BinderError(err_msg)
 
     # TODO ACTION condition on segment length?
 
 
 def check_table_object_is_groupable(table_ref: TableRef) -> None:
-    if not is_video_table(table_ref.table.table_obj) and not is_document_table(
-        table_ref.table.table_obj
+    table_obj = table_ref.table.table_obj
+
+    if not (
+        is_video_table(table_obj)
+        or is_document_table(table_obj)
+        or is_pdf_table(table_obj)
     ):
-        err_msg = "GROUP BY only supported for video and document tables"
-        raise BinderError(err_msg)
+        raise BinderError("GROUP BY only supported for video and document tables")
 
 
 def check_column_name_is_string(col_ref) -> None:
     if not is_string_col(col_ref.col_object):
         err_msg = "LIKE only supported for string columns"
         raise BinderError(err_msg)
 
@@ -184,28 +186,26 @@
     # 1. Bind the source video
     video_data = node.children[0]
     binder_context.bind(video_data)
 
     # 2. Construct the detector
     # convert detector to FunctionExpression before binding
     # eg. YoloV5 -> YoloV5(data)
-    detector = FunctionExpression(None, node.children[1].col_name)
+    detector = FunctionExpression(None, node.children[1].name)
     detector.append_child(video_data.copy())
     binder_context.bind(detector)
 
     # 3. Construct the tracker
     # convert tracker to FunctionExpression before binding
     # eg. ByteTracker -> ByteTracker(id, data, labels, bboxes, scores)
-    tracker = FunctionExpression(None, node.children[2].col_name)
+    tracker = FunctionExpression(None, node.children[2].name)
     # create the video id expression
     columns = get_video_table_column_definitions()
     tracker.append_child(
-        TupleValueExpression(
-            col_name=columns[1].name, table_alias=video_data.table_alias
-        )
+        TupleValueExpression(name=columns[1].name, table_alias=video_data.table_alias)
     )
     tracker.append_child(video_data.copy())
     binder_context.bind(tracker)
     # append the bound output of detector
     for obj in detector.output_objs:
         col_alias = "{}.{}".format(obj.udf_name.lower(), obj.name.lower())
         child = TupleValueExpression(
```

### Comparing `evadb-0.2.9/evadb/binder/statement_binder.py` & `evadb-0.3.0/evadb/binder/statement_binder.py`

 * *Files 8% similar despite different names*

```diff
@@ -24,31 +24,30 @@
     check_table_object_is_groupable,
     extend_star,
     handle_bind_extract_object_function,
     resolve_alias_table_value_expression,
 )
 from evadb.binder.statement_binder_context import StatementBinderContext
 from evadb.catalog.catalog_type import NdArrayType, TableType, VideoColumnName
-from evadb.catalog.catalog_utils import get_metadata_properties
+from evadb.catalog.catalog_utils import get_metadata_properties, is_document_table
 from evadb.configuration.constants import EvaDB_INSTALLATION_DIR
 from evadb.expression.abstract_expression import AbstractExpression, ExpressionType
 from evadb.expression.function_expression import FunctionExpression
 from evadb.expression.tuple_value_expression import TupleValueExpression
 from evadb.parser.create_index_statement import CreateIndexStatement
-from evadb.parser.create_mat_view_statement import CreateMaterializedViewStatement
 from evadb.parser.create_statement import ColumnDefinition, CreateTableStatement
 from evadb.parser.delete_statement import DeleteTableStatement
 from evadb.parser.explain_statement import ExplainStatement
 from evadb.parser.rename_statement import RenameTableStatement
 from evadb.parser.select_statement import SelectStatement
 from evadb.parser.statement import AbstractStatement
 from evadb.parser.table_ref import TableRef
 from evadb.parser.types import UDFType
 from evadb.third_party.huggingface.binder import assign_hf_udf
-from evadb.utils.generic_utils import get_file_checksum, load_udf_class_from_file
+from evadb.utils.generic_utils import load_udf_class_from_file
 from evadb.utils.logging_manager import logger
 
 
 class StatementBinder:
     def __init__(self, binder_context: StatementBinderContext):
         self._binder_context = binder_context
         self._catalog: Callable = binder_context._catalog
@@ -77,20 +76,30 @@
             self.bind(node.udf_func)
 
         # TODO: create index currently only supports single numpy column.
         assert len(node.col_list) == 1, "Index cannot be created on more than 1 column"
 
         # TODO: create index currently only works on TableInfo, but will extend later.
         assert node.table_ref.is_table_atom(), "Index can only be created on Tableinfo"
-
         if not node.udf_func:
             # Feature table type needs to be float32 numpy array.
+            assert (
+                len(node.col_list) == 1
+            ), f"Index can be only created on one column, but instead {len(node.col_list)} are provided"
             col_def = node.col_list[0]
+
             table_ref_obj = node.table_ref.table.table_obj
-            col = [col for col in table_ref_obj.columns if col.name == col_def.name][0]
+            col_list = [
+                col for col in table_ref_obj.columns if col.name == col_def.name
+            ]
+            assert (
+                len(col_list) == 1
+            ), f"Index is created on non-existent column {col_def.name}"
+
+            col = col_list[0]
             assert (
                 col.array_type == NdArrayType.FLOAT32
             ), "Index input needs to be float32."
             assert len(col.array_dimensions) == 2
         else:
             # Output of the UDF should be 2 dimension and float32 type.
             udf_obj = self._catalog().get_udf_catalog_entry_by_name(node.udf_func.name)
@@ -111,15 +120,15 @@
                 check_column_name_is_string(node.where_clause.children[0])
 
         if node.target_list:
             # SELECT * support
             if (
                 len(node.target_list) == 1
                 and isinstance(node.target_list[0], TupleValueExpression)
-                and node.target_list[0].col_name == "*"
+                and node.target_list[0].name == "*"
             ):
                 node.target_list = extend_star(self._binder_context)
             for expr in node.target_list:
                 self.bind(expr)
         if node.groupby_clause:
             self.bind(node.groupby_clause)
             check_table_object_is_groupable(node.from_table)
@@ -129,18 +138,25 @@
                 self.bind(expr[0])
         if node.union_link:
             current_context = self._binder_context
             self._binder_context = StatementBinderContext(self._catalog)
             self.bind(node.union_link)
             self._binder_context = current_context
 
+        # chunk_params only supported for DOCUMENT TYPE
+        if node.from_table.chunk_params:
+            assert is_document_table(
+                node.from_table.table.table_obj
+            ), "CHUNK related parameters only supported for DOCUMENT tables."
+
         assert not (
             self._binder_context.is_retrieve_audio()
             and self._binder_context.is_retrieve_video()
         ), "Cannot query over both audio and video streams"
+
         if self._binder_context.is_retrieve_audio():
             node.from_table.get_audio = True
         if self._binder_context.is_retrieve_video():
             node.from_table.get_video = True
 
     @bind.register(DeleteTableStatement)
     def _bind_delete_statement(self, node: DeleteTableStatement):
@@ -163,15 +179,15 @@
                         "Unsupported expression type {}.".format(expr.etype)
                     )
 
             binded_col_list = []
             idx = 0
             for expr in node.query.target_list:
                 output_objs = (
-                    [(expr.col_name, expr.col_object)]
+                    [(expr.name, expr.col_object)]
                     if expr.etype == ExpressionType.TUPLE_VALUE
                     else zip(expr.projection_columns, expr.output_objs)
                 )
                 for col_name, output_obj in output_objs:
                     binded_col_list.append(
                         ColumnDefinition(
                             col_name,
@@ -179,54 +195,14 @@
                             output_obj.array_type,
                             output_obj.array_dimensions,
                         )
                     )
                     idx += 1
             node.column_list = binded_col_list
 
-    @bind.register(CreateMaterializedViewStatement)
-    def _bind_create_mat_statement(self, node: CreateMaterializedViewStatement):
-        self.bind(node.query)
-        num_projected_columns = 0
-        # TODO we should fix the binder. All binded object should have the same interface.
-        for expr in node.query.target_list:
-            if expr.etype == ExpressionType.TUPLE_VALUE:
-                num_projected_columns += 1
-            elif expr.etype == ExpressionType.FUNCTION_EXPRESSION:
-                num_projected_columns += len(expr.output_objs)
-            else:
-                raise BinderError("Unsupported expression type {}.".format(expr.etype))
-
-        assert (
-            len(node.col_list) == 0 or len(node.col_list) == num_projected_columns
-        ), "Projected columns mismatch, expected {} found {}.".format(
-            len(node.col_list), num_projected_columns
-        )
-        binded_col_list = []
-        idx = 0
-        for expr in node.query.target_list:
-            output_objs = (
-                [(expr.col_name, expr.col_object)]
-                if expr.etype == ExpressionType.TUPLE_VALUE
-                else zip(expr.projection_columns, expr.output_objs)
-            )
-            for col_name, output_obj in output_objs:
-                binded_col_list.append(
-                    ColumnDefinition(
-                        col_name
-                        if len(node.col_list) == 0
-                        else node.col_list[idx].name,
-                        output_obj.type,
-                        output_obj.array_type,
-                        output_obj.array_dimensions,
-                    )
-                )
-                idx += 1
-        node.col_list = binded_col_list
-
     @bind.register(RenameTableStatement)
     def _bind_rename_table_statement(self, node: RenameTableStatement):
         self.bind(node.old_table_ref)
         assert (
             node.old_table_ref.table.table_obj.table_type != TableType.STRUCTURED_DATA
         ), "Rename not yet supported on structured data"
 
@@ -255,37 +231,37 @@
             func_expr = node.table_valued_expr.func_expr
             func_expr.alias = node.alias
             self.bind(func_expr)
             output_cols = []
             for obj, alias in zip(func_expr.output_objs, func_expr.alias.col_names):
                 col_alias = "{}.{}".format(func_expr.alias.alias_name, alias)
                 alias_obj = TupleValueExpression(
-                    col_name=alias,
+                    name=alias,
                     table_alias=func_expr.alias.alias_name,
                     col_object=obj,
                     col_alias=col_alias,
                 )
                 output_cols.append(alias_obj)
             self._binder_context.add_derived_table_alias(
                 func_expr.alias.alias_name, output_cols
             )
         else:
             raise BinderError(f"Unsupported node {type(node)}")
 
     @bind.register(TupleValueExpression)
     def _bind_tuple_expr(self, node: TupleValueExpression):
         table_alias, col_obj = self._binder_context.get_binded_column(
-            node.col_name, node.table_alias
+            node.name, node.table_alias
         )
         node.table_alias = table_alias
-        if node.col_name == VideoColumnName.audio:
+        if node.name == VideoColumnName.audio:
             self._binder_context.enable_audio_retrieval()
-        if node.col_name == VideoColumnName.data:
+        if node.name == VideoColumnName.data:
             self._binder_context.enable_video_retrieval()
-        node.col_alias = "{}.{}".format(table_alias, node.col_name.lower())
+        node.col_alias = "{}.{}".format(table_alias, node.name.lower())
         node.col_object = col_obj
 
     @bind.register(FunctionExpression)
     def _bind_func_expr(self, node: FunctionExpression):
         # handle the special case of "extract_object"
         if node.name.upper() == str(UDFType.EXTRACT_OBJECT):
             handle_bind_extract_object_function(node, self)
@@ -293,16 +269,16 @@
         # bind all the children
         for child in node.children:
             self.bind(child)
 
         udf_obj = self._catalog().get_udf_catalog_entry_by_name(node.name)
         if udf_obj is None:
             err_msg = (
-                f"UDF with name {node.name} does not exist in the catalog. "
-                "Please create the UDF using CREATE UDF command."
+                f"Function '{node.name}' does not exist in the catalog. "
+                "Please create the function using CREATE UDF command."
             )
             logger.error(err_msg)
             raise BinderError(err_msg)
 
         if udf_obj.type == "HuggingFace":
             node.function = assign_hf_udf(udf_obj)
 
@@ -314,30 +290,30 @@
                 udf_obj.impl_file_path = (
                     Path(f"{udf_dir}/yolo_object_detector.py").absolute().as_posix()
                 )
 
             # Verify the consistency of the UDF. If the checksum of the UDF does not
             # match the one stored in the catalog, an error will be thrown and the user
             # will be asked to register the UDF again.
-            assert (
-                get_file_checksum(udf_obj.impl_file_path) == udf_obj.checksum
-            ), f"""UDF file {udf_obj.impl_file_path} has been modified from the
-                registration. Please use DROP UDF to drop it and re-create it using CREATE UDF."""
+            # assert (
+            #     get_file_checksum(udf_obj.impl_file_path) == udf_obj.checksum
+            # ), f"""UDF file {udf_obj.impl_file_path} has been modified from the
+            #     registration. Please use DROP UDF to drop it and re-create it # using CREATE UDF."""
 
             try:
                 udf_class = load_udf_class_from_file(
                     udf_obj.impl_file_path,
                     udf_obj.name,
                 )
                 # certain udfs take additional inputs like yolo needs the model_name
                 # these arguments are passed by the user as part of metadata
                 node.function = lambda: udf_class(**get_metadata_properties(udf_obj))
             except Exception as e:
                 err_msg = (
-                    f"{str(e)}. Please verify that the UDF class name in the"
+                    f"{str(e)}. Please verify that the UDF class name in the "
                     "implementation file matches the UDF name."
                 )
                 logger.error(err_msg)
                 raise BinderError(err_msg)
 
         node.udf_obj = udf_obj
         output_objs = self._catalog().get_udf_io_catalog_output_entries(udf_obj)
```

### Comparing `evadb-0.2.9/evadb/binder/statement_binder_context.py` & `evadb-0.3.0/evadb/binder/statement_binder_context.py`

 * *Files 0% similar despite different names*

```diff
@@ -91,15 +91,15 @@
         self._check_duplicate_alias(alias)
         col_alias_map = {}
         for expr in target_list:
             if isinstance(expr, FunctionExpression):
                 for obj in expr.output_objs:
                     col_alias_map[obj.name] = obj
             elif isinstance(expr, TupleValueExpression):
-                col_alias_map[expr.col_name] = expr.col_object
+                col_alias_map[expr.name] = expr.col_object
             else:
                 continue
 
         self._derived_table_alias_map[alias] = col_alias_map
 
     def get_binded_column(
         self, col_name: str, alias: str = None
```

### Comparing `evadb-0.2.9/evadb/catalog/__init__.py` & `evadb-0.3.0/evadb/catalog/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/catalog_manager.py` & `evadb-0.3.0/evadb/catalog/catalog_manager.py`

 * *Files 1% similar despite different names*

```diff
@@ -87,14 +87,22 @@
         """
         This method resets the state of the singleton instance.
         It should clear the contents of the catalog tables and any storage data
         Used by testcases to reset the db state before
         """
         self._clear_catalog_contents()
 
+    def close(self):
+        """
+        This method closes all the connections
+        """
+        if self.sql_config is not None:
+            sqlalchemy_engine = self.sql_config.engine
+            sqlalchemy_engine.dispose()
+
     def _bootstrap_catalog(self):
         """Bootstraps catalog.
         This method runs all tasks required for using catalog. Currently,
         it includes only one task ie. initializing database. It creates the
         catalog database and tables if they do not exist.
         """
         logger.info("Bootstrapping catalog")
```

### Comparing `evadb-0.2.9/evadb/catalog/catalog_type.py` & `evadb-0.3.0/evadb/catalog/catalog_type.py`

 * *Files 4% similar despite different names*

```diff
@@ -119,14 +119,15 @@
 class ImageColumnName(EvaDBEnum):
     name  # noqa: F821
     data  # noqa: F821
 
 
 class DocumentColumnName(EvaDBEnum):
     name  # noqa: F821
+    chunk_id  # noqa: F821
     data  # noqa: F821
     metadata  # noqa: F821
 
 
 class PDFColumnName(EvaDBEnum):
     name  # noqa: F821
     page  # noqa: F821
```

### Comparing `evadb-0.2.9/evadb/catalog/catalog_utils.py` & `evadb-0.3.0/evadb/catalog/catalog_utils.py`

 * *Files 5% similar despite different names*

```diff
@@ -27,14 +27,15 @@
 )
 from evadb.catalog.models.utils import (
     ColumnCatalogEntry,
     TableCatalogEntry,
     UdfCacheCatalogEntry,
     UdfCatalogEntry,
 )
+from evadb.catalog.sql_config import IDENTIFIER_COLUMN
 from evadb.configuration.configuration_manager import ConfigurationManager
 from evadb.expression.function_expression import FunctionExpression
 from evadb.expression.tuple_value_expression import TupleValueExpression
 from evadb.parser.create_statement import ColConstraintInfo, ColumnDefinition
 from evadb.utils.generic_utils import get_str_hash, remove_directory_contents
 
 CATALOG_TABLES = [
@@ -52,18 +53,19 @@
 
 
 def is_video_table(table: TableCatalogEntry):
     return table.table_type == TableType.VIDEO_DATA
 
 
 def is_document_table(table: TableCatalogEntry):
-    return (
-        table.table_type == TableType.DOCUMENT_DATA
-        or table.table_type == TableType.PDF_DATA
-    )
+    return table.table_type == TableType.DOCUMENT_DATA
+
+
+def is_pdf_table(table: TableCatalogEntry):
+    return table.table_type == TableType.PDF_DATA
 
 
 def is_string_col(col: ColumnCatalogEntry):
     return col.type == ColumnType.TEXT or col.array_type == NdArrayType.STR
 
 
 def get_video_table_column_definitions() -> List[ColumnDefinition]:
@@ -115,25 +117,29 @@
     ]
     return columns
 
 
 def get_document_table_column_definitions() -> List[ColumnDefinition]:
     """
     name: file path
-    data: file extracted data
+    chunk_id: chunk id (0-indexed for each file)
+    data: text data associated with the chunk
     """
     columns = [
         ColumnDefinition(
             DocumentColumnName.name.name,
             ColumnType.TEXT,
             None,
             None,
             ColConstraintInfo(unique=True),
         ),
         ColumnDefinition(
+            DocumentColumnName.chunk_id.name, ColumnType.INTEGER, None, None
+        ),
+        ColumnDefinition(
             DocumentColumnName.data.name,
             ColumnType.TEXT,
             None,
             None,
         ),
     ]
     return columns
@@ -156,25 +162,53 @@
             None,
             None,
         ),
     ]
     return columns
 
 
-def get_table_primary_columns(table_catalog_obj: TableCatalogEntry):
+def get_table_primary_columns(
+    table_catalog_obj: TableCatalogEntry,
+) -> List[ColumnDefinition]:
+    """
+    Get the primary columns for a table based on its table type.
+
+    Args:
+        table_catalog_obj (TableCatalogEntry): The table catalog object.
+
+    Returns:
+        List[ColumnDefinition]: The list of primary columns for the table.
+    """
+    primary_columns = [
+        ColumnDefinition(IDENTIFIER_COLUMN, ColumnType.INTEGER, None, None)
+    ]
+    # _row_id for all the TableTypes, however for Video data and PDF data we also add frame_id (id) and paragraph as part of unique key
     if table_catalog_obj.table_type == TableType.VIDEO_DATA:
-        return get_video_table_column_definitions()[:2]
-    elif table_catalog_obj.table_type == TableType.IMAGE_DATA:
-        return get_image_table_column_definitions()[:1]
-    elif table_catalog_obj.table_type == TableType.DOCUMENT_DATA:
-        return get_document_table_column_definitions()[:1]
+        # _row_id, id
+        primary_columns.append(
+            ColumnDefinition(VideoColumnName.id.name, ColumnType.INTEGER, None, None),
+        )
+
     elif table_catalog_obj.table_type == TableType.PDF_DATA:
-        return get_pdf_table_column_definitions()[:3]
-    else:
-        raise Exception(f"Unexpected table type {table_catalog_obj.table_type}")
+        # _row_id, paragraph
+        primary_columns.append(
+            ColumnDefinition(
+                PDFColumnName.paragraph.name, ColumnType.INTEGER, None, None
+            )
+        )
+
+    elif table_catalog_obj.table_type == TableType.DOCUMENT_DATA:
+        # _row_id, chunk_id
+        primary_columns.append(
+            ColumnDefinition(
+                DocumentColumnName.chunk_id.name, ColumnType.INTEGER, None, None
+            )
+        )
+
+    return primary_columns
 
 
 def xform_column_definitions_to_catalog_entries(
     col_list: List[ColumnDefinition],
 ) -> List[ColumnCatalogEntry]:
     """Create column catalog entries for the input parsed column list.
```

### Comparing `evadb-0.2.9/evadb/catalog/models/__init__.py` & `evadb-0.3.0/evadb/catalog/models/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/models/association_models.py` & `evadb-0.3.0/evadb/catalog/models/association_models.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/models/base_model.py` & `evadb-0.3.0/evadb/catalog/models/base_model.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/models/column_catalog.py` & `evadb-0.3.0/evadb/catalog/models/column_catalog.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/models/index_catalog.py` & `evadb-0.3.0/evadb/catalog/models/index_catalog.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/models/table_catalog.py` & `evadb-0.3.0/evadb/catalog/models/table_catalog.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/models/udf_cache_catalog.py` & `evadb-0.3.0/evadb/catalog/models/udf_cache_catalog.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/models/udf_catalog.py` & `evadb-0.3.0/evadb/catalog/models/udf_catalog.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/models/udf_cost_catalog.py` & `evadb-0.3.0/evadb/catalog/models/udf_cost_catalog.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/models/udf_io_catalog.py` & `evadb-0.3.0/evadb/catalog/models/udf_io_catalog.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/models/udf_metadata_catalog.py` & `evadb-0.3.0/evadb/catalog/models/udf_metadata_catalog.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/models/utils.py` & `evadb-0.3.0/evadb/catalog/models/utils.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/schema_utils.py` & `evadb-0.3.0/evadb/catalog/schema_utils.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/services/__init__.py` & `evadb-0.3.0/evadb/catalog/services/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/services/base_service.py` & `evadb-0.3.0/evadb/catalog/services/base_service.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/services/column_catalog_service.py` & `evadb-0.3.0/evadb/catalog/services/column_catalog_service.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/services/index_catalog_service.py` & `evadb-0.3.0/evadb/catalog/services/index_catalog_service.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/services/table_catalog_service.py` & `evadb-0.3.0/evadb/catalog/services/table_catalog_service.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/services/udf_cache_catalog_service.py` & `evadb-0.3.0/evadb/catalog/services/udf_cache_catalog_service.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/services/udf_catalog_service.py` & `evadb-0.3.0/evadb/catalog/services/udf_catalog_service.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/services/udf_cost_catalog_service.py` & `evadb-0.3.0/evadb/catalog/services/udf_cost_catalog_service.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/services/udf_io_catalog_service.py` & `evadb-0.3.0/evadb/catalog/services/udf_io_catalog_service.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/services/udf_metadata_catalog_service.py` & `evadb-0.3.0/evadb/catalog/services/udf_metadata_catalog_service.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/catalog/sql_config.py` & `evadb-0.3.0/evadb/catalog/sql_config.py`

 * *Files 3% similar despite different names*

```diff
@@ -57,15 +57,15 @@
         """Initializes the engine and session for database operations
 
         Retrieves the database uri for connection from ConfigurationManager.
         """
 
         self.worker_uri = str(uri)
         # set echo=True to log SQL
-        self.engine = create_engine(self.worker_uri)
+        self.engine = create_engine(self.worker_uri, connect_args={"timeout": 1000})
 
         if self.engine.url.get_backend_name() == "sqlite":
             # enforce foreign key constraint and wal logging for sqlite
             # https://docs.sqlalchemy.org/en/20/dialects/sqlite.html#foreign-key-support
 
             def _enable_sqlite_pragma(dbapi_con, con_record):
                 dbapi_con.execute("pragma foreign_keys=ON")
@@ -76,7 +76,8 @@
                 # optimal design. Ideally, we should implement a connection pool for
                 # better management.
                 # dbapi_con.execute("pragma journal_mode=WAL")
 
             event.listen(self.engine, "connect", _enable_sqlite_pragma)
         # statements
         self.session = scoped_session(sessionmaker(bind=self.engine))
+        self.session.close()
```

### Comparing `evadb-0.2.9/evadb/configuration/__init__.py` & `evadb-0.3.0/evadb/configuration/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/configuration/bootstrap_environment.py` & `evadb-0.3.0/evadb/configuration/bootstrap_environment.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/configuration/configuration_manager.py` & `evadb-0.3.0/evadb/configuration/configuration_manager.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/configuration/constants.py` & `evadb-0.3.0/evadb/configuration/constants.py`

 * *Files 3% similar despite different names*

```diff
@@ -15,14 +15,15 @@
 from pathlib import Path
 
 import evadb
 
 EvaDB_INSTALLATION_DIR = Path(evadb.__file__).parent
 EvaDB_ROOT_DIR = Path(evadb.__file__).parent.parent
 EvaDB_DATABASE_DIR = "evadb_data"
+EvaDB_APPS_DIR = "apps"
 EvaDB_DATASET_DIR = "evadb_datasets"
 EvaDB_CONFIG_FILE = "evadb.yml"
 UDF_DIR = "udfs"
 CATALOG_DIR = "catalog"
 INDEX_DIR = "index"
 CACHE_DIR = "cache"
 DATASET_DATAFRAME_NAME = "dataset"
```

### Comparing `evadb-0.2.9/evadb/constants.py` & `evadb-0.3.0/evadb/constants.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/database.py` & `evadb-0.3.0/evadb/database.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/evadb.yml` & `evadb-0.3.0/evadb/evadb.yml`

 * *Files 2% similar despite different names*

```diff
@@ -27,10 +27,10 @@
 000001a0: 6d70 5f64 6972 3a20 2222 0a20 2073 335f  mp_dir: "".  s3_
 000001b0: 646f 776e 6c6f 6164 5f64 6972 3a20 2222  download_dir: ""
 000001c0: 0a0a 7365 7276 6572 3a0a 2020 686f 7374  ..server:.  host
 000001d0: 3a20 2230 2e30 2e30 2e30 220a 2020 706f  : "0.0.0.0".  po
 000001e0: 7274 3a20 3838 3033 0a20 2073 6f63 6b65  rt: 8803.  socke
 000001f0: 745f 7469 6d65 6f75 743a 2036 300a 0a65  t_timeout: 60..e
 00000200: 7870 6572 696d 656e 7461 6c3a 0a20 2072  xperimental:.  r
-00000210: 6179 3a20 5472 7565 0a0a 7468 6972 645f  ay: True..third_
-00000220: 7061 7274 793a 0a20 204f 5045 4e41 495f  party:.  OPENAI_
-00000230: 4b45 593a 2022 220a                      KEY: "".
+00000210: 6179 3a20 4661 6c73 6520 0a0a 7468 6972  ay: False ..thir
+00000220: 645f 7061 7274 793a 0a20 204f 5045 4e41  d_party:.  OPENA
+00000230: 495f 4b45 593a 2022 220a                 I_KEY: "".
```

### Comparing `evadb-0.2.9/evadb/evadb_cmd_client.py` & `evadb-0.3.0/evadb/evadb_cmd_client.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/evadb_server.py` & `evadb-0.3.0/evadb/evadb_server.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/__init__.py` & `evadb-0.3.0/evadb/executor/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/abstract_executor.py` & `evadb-0.3.0/evadb/executor/abstract_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/apply_and_merge_executor.py` & `evadb-0.3.0/evadb/executor/apply_and_merge_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/create_executor.py` & `evadb-0.3.0/evadb/executor/create_executor.py`

 * *Files 2% similar despite different names*

```diff
@@ -35,15 +35,15 @@
             )
             storage_engine = StorageEngine.factory(self.db, catalog_entry)
             storage_engine.create(table=catalog_entry)
 
             if self.children != []:
                 assert (
                     len(self.children) == 1
-                ), "Create materialized view expects 1 child, finds {}".format(
+                ), "Create table from query expects 1 child, finds {}".format(
                     len(self.children)
                 )
                 child = self.children[0]
 
                 # Populate the table
                 for batch in child.exec():
                     batch.drop_column_alias()
```

### Comparing `evadb-0.2.9/evadb/executor/create_index_executor.py` & `evadb-0.3.0/evadb/executor/create_index_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/create_mat_view_executor.py` & `evadb-0.3.0/evadb/executor/insert_executor.py`

 * *Files 24% similar despite different names*

```diff
@@ -8,40 +8,51 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
+import pandas as pd
+
+from evadb.catalog.catalog_type import TableType
 from evadb.database import EvaDBDatabase
 from evadb.executor.abstract_executor import AbstractExecutor
-from evadb.executor.executor_utils import handle_if_not_exists
-from evadb.plan_nodes.create_mat_view_plan import CreateMaterializedViewPlan
+from evadb.models.storage.batch import Batch
+from evadb.plan_nodes.insert_plan import InsertPlan
 from evadb.storage.storage_engine import StorageEngine
 
 
-class CreateMaterializedViewExecutor(AbstractExecutor):
-    def __init__(self, db: EvaDBDatabase, node: CreateMaterializedViewPlan):
+class InsertExecutor(AbstractExecutor):
+    def __init__(self, db: EvaDBDatabase, node: InsertPlan):
         super().__init__(db, node)
 
     def exec(self, *args, **kwargs):
-        """Create materialized view executor"""
-        if not handle_if_not_exists(
-            self.catalog(), self.node.view, self.node.if_not_exists
-        ):
-            assert (
-                len(self.children) == 1
-            ), "Create materialized view expects 1 child, finds {}".format(
-                len(self.children)
-            )
-            child = self.children[0]
-
-            view_catalog_entry = self.catalog().create_and_insert_table_catalog_entry(
-                self.node.view, self.node.columns
-            )
-            storage_engine = StorageEngine.factory(self.db, view_catalog_entry)
-            storage_engine.create(table=view_catalog_entry)
-
-            # Populate the view
-            for batch in child.exec():
-                batch.drop_column_alias()
-                storage_engine.write(view_catalog_entry, batch)
+        storage_engine = None
+        table_catalog_entry = None
+
+        # Get catalog entry
+        table_name = self.node.table_ref.table.table_name
+        database_name = self.node.table_ref.table.database_name
+        table_catalog_entry = self.catalog().get_table_catalog_entry(
+            table_name, database_name
+        )
+
+        # Implemented only for STRUCTURED_DATA
+        assert (
+            table_catalog_entry.table_type == TableType.STRUCTURED_DATA
+        ), "INSERT only implemented for structured data"
+
+        values_to_insert = [val_node.value for val_node in self.node.value_list]
+        tuple_to_insert = tuple(values_to_insert)
+        columns_to_insert = [col_node.name for col_node in self.node.column_list]
+
+        # Adding all values to Batch for insert
+        dataframe = pd.DataFrame([tuple_to_insert], columns=columns_to_insert)
+        batch = Batch(dataframe)
+
+        storage_engine = StorageEngine.factory(self.db, table_catalog_entry)
+        storage_engine.write(table_catalog_entry, batch)
+
+        yield Batch(
+            pd.DataFrame([f"Number of rows loaded: {str(len(values_to_insert))}"])
+        )
```

### Comparing `evadb-0.2.9/evadb/executor/create_udf_executor.py` & `evadb-0.3.0/evadb/executor/create_udf_executor.py`

 * *Files 4% similar despite different names*

```diff
@@ -23,15 +23,19 @@
 from evadb.database import EvaDBDatabase
 from evadb.executor.abstract_executor import AbstractExecutor
 from evadb.models.storage.batch import Batch
 from evadb.plan_nodes.create_udf_plan import CreateUDFPlan
 from evadb.third_party.huggingface.create import gen_hf_io_catalog_entries
 from evadb.udfs.decorators.utils import load_io_from_udf_decorators
 from evadb.utils.errors import UDFIODefinitionError
-from evadb.utils.generic_utils import load_udf_class_from_file
+from evadb.utils.generic_utils import (
+    load_udf_class_from_file,
+    try_to_import_torch,
+    try_to_import_ultralytics,
+)
 from evadb.utils.logging_manager import logger
 
 
 class CreateUDFExecutor(AbstractExecutor):
     def __init__(self, db: EvaDBDatabase, node: CreateUDFPlan):
         super().__init__(db, node)
         self.udf_dir = (
@@ -40,26 +44,30 @@
 
     def handle_huggingface_udf(self):
         """Handle HuggingFace UDFs
 
         HuggingFace UDFs are special UDFs that are not loaded from a file.
         So we do not need to call the setup method on them like we do for other UDFs.
         """
+        # We need atleast one deep learning framework for HuggingFace
+        # Torch or Tensorflow
+        try_to_import_torch()
         impl_path = f"{self.udf_dir}/abstract/hf_abstract_udf.py"
         io_list = gen_hf_io_catalog_entries(self.node.name, self.node.metadata)
         return (
             self.node.name,
             impl_path,
             self.node.udf_type,
             io_list,
             self.node.metadata,
         )
 
     def handle_ultralytics_udf(self):
         """Handle Ultralytics UDFs"""
+        try_to_import_ultralytics()
 
         impl_path = (
             Path(f"{self.udf_dir}/yolo_object_detector.py").absolute().as_posix()
         )
         udf = self._try_initializing_udf(
             impl_path, udf_args=get_metadata_properties(self.node)
         )
@@ -123,34 +131,32 @@
     def _try_initializing_udf(
         self, impl_path: str, udf_args: Dict = {}
     ) -> UdfCatalogEntry:
         """Attempts to initialize UDF given the implementation file path and arguments.
 
         Args:
             impl_path (str): The file path of the UDF implementation file.
-            udf_args (Dict, optional): Dictionary of arguments to pass to the UDF.
-            Defaults to {}.
+            udf_args (Dict, optional): Dictionary of arguments to pass to the UDF. Defaults to {}.
 
         Returns:
-            UdfCatalogEntry: A UdfCatalogEntry object that represents the initialized
-            UDF.
+            UdfCatalogEntry: A UdfCatalogEntry object that represents the initialized UDF.
 
         Raises:
             RuntimeError: If an error occurs while initializing the UDF.
         """
 
         # load the udf class from the file
         try:
             # loading the udf class from the file
             udf = load_udf_class_from_file(impl_path, self.node.name)
             # initializing the udf class calls the setup method internally
             udf(**udf_args)
         except Exception as e:
             err_msg = f"Error creating UDF: {str(e)}"
-            logger.error(err_msg)
+            # logger.error(err_msg)
             raise RuntimeError(err_msg)
 
         return udf
 
     def _resolve_udf_io(self, udf: UdfCatalogEntry) -> List[UdfIOCatalogEntry]:
         """Private method that resolves the input/output definitions for a given UDF.
         It first searches for the input/outputs in the CREATE statement. If not found, it resolves them using decorators. If not found there as well, it raises an error.
```

### Comparing `evadb-0.2.9/evadb/executor/delete_executor.py` & `evadb-0.3.0/evadb/executor/delete_executor.py`

 * *Files 1% similar despite different names*

```diff
@@ -42,24 +42,24 @@
         self, table: TableCatalogEntry, predicate_node: ComparisonExpression
     ):
         filter_clause = None
         left = predicate_node.get_child(0)
         right = predicate_node.get_child(1)
 
         if type(left) == TupleValueExpression:
-            column = left.col_name
+            column = left.name
             x = table.columns[column]
         elif type(left) == ConstantValueExpression:
             value = left.value
             x = value
         else:
             left_filter_clause = self.predicate_node_to_filter_clause(table, left)
 
         if type(right) == TupleValueExpression:
-            column = right.col_name
+            column = right.name
             y = table.columns[column]
         elif type(right) == ConstantValueExpression:
             value = right.value
             y = value
         else:
             right_filter_clause = self.predicate_node_to_filter_clause(table, right)
```

### Comparing `evadb-0.2.9/evadb/executor/drop_object_executor.py` & `evadb-0.3.0/evadb/executor/drop_object_executor.py`

 * *Files 1% similar despite different names*

```diff
@@ -43,15 +43,14 @@
         elif self.node.object_type == ObjectType.UDF:
             yield self._handle_drop_udf(self.node.name, self.node.if_exists)
 
     def _handle_drop_table(self, table_name: str, if_exists: bool):
         if not self.catalog().check_table_exists(table_name):
             err_msg = "Table: {} does not exist".format(table_name)
             if if_exists:
-                logger.warning(err_msg)
                 return Batch(pd.DataFrame([err_msg]))
             else:
                 raise ExecutorError(err_msg)
 
         table_obj = self.catalog().get_table_catalog_entry(table_name)
         storage_engine = StorageEngine.factory(self.db, table_obj)
```

### Comparing `evadb-0.2.9/evadb/executor/exchange_executor.py` & `evadb-0.3.0/evadb/executor/exchange_executor.py`

 * *Files 2% similar despite different names*

```diff
@@ -10,16 +10,14 @@
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 from typing import Iterator
 
-from ray.util.queue import Queue
-
 from evadb.database import EvaDBDatabase
 from evadb.executor.abstract_executor import AbstractExecutor
 from evadb.executor.executor_utils import ExecutorError
 from evadb.executor.ray_utils import (
     StageCompleteSignal,
     ray_parallel,
     ray_pull,
@@ -61,41 +59,43 @@
         super().__init__(db, node)
 
     def build_inner_executor(self, inner_executor):
         self.inner_executor = inner_executor
         self.inner_executor.children = [QueueReaderExecutor()]
 
     def exec(self) -> Iterator[Batch]:
+        from ray.util.queue import Queue
+
         input_queue = Queue(maxsize=100)
         output_queue = Queue(maxsize=100)
 
         # Pull data from child executor
         assert (
             len(self.children) == 1
         ), "Exchange currently only supports parallelization of node with only one child"
-        ray_pull_task = ray_pull.remote(
+        ray_pull_task = ray_pull().remote(
             self.ray_pull_env_conf_dict,
             self.children[0],
             input_queue,
         )
 
         # Parallel the inner executor.
         ray_parallel_task_list = []
         for i in range(self.parallelism):
             ray_parallel_task_list.append(
-                ray_parallel.remote(
+                ray_parallel().remote(
                     self.ray_parallel_env_conf_dict[i],
                     self.inner_executor,
                     input_queue,
                     output_queue,
                 )
             )
 
-        ray_wait_and_alert.remote([ray_pull_task], input_queue)
-        ray_wait_and_alert.remote(ray_parallel_task_list, output_queue)
+        ray_wait_and_alert().remote([ray_pull_task], input_queue)
+        ray_wait_and_alert().remote(ray_parallel_task_list, output_queue)
 
         while True:
             res = output_queue.get(block=True)
             if res is StageCompleteSignal:
                 break
             elif isinstance(res, ExecutorError):
                 raise res
```

### Comparing `evadb-0.2.9/evadb/executor/execution_context.py` & `evadb-0.3.0/evadb/executor/execution_context.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/executor_utils.py` & `evadb-0.3.0/evadb/executor/executor_utils.py`

 * *Files 4% similar despite different names*

```diff
@@ -13,26 +13,25 @@
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import glob
 import os
 from pathlib import Path
 from typing import TYPE_CHECKING, Generator, List
 
-import cv2
-
 if TYPE_CHECKING:
     from evadb.catalog.catalog_manager import CatalogManager
 
 from evadb.catalog.catalog_type import VectorStoreType
 from evadb.expression.abstract_expression import AbstractExpression
 from evadb.expression.function_expression import FunctionExpression
 from evadb.models.storage.batch import Batch
 from evadb.parser.table_ref import TableInfo
 from evadb.parser.types import FileFormatType
 from evadb.readers.document.registry import SUPPORTED_TYPES
+from evadb.utils.generic_utils import try_to_import_cv2
 from evadb.utils.logging_manager import logger
 
 
 class ExecutorError(Exception):
     pass
 
 
@@ -89,14 +88,17 @@
     # Table does not exist
     else:
         return False
 
 
 def validate_image(image_path: Path) -> bool:
     try:
+        try_to_import_cv2()
+        import cv2
+
         data = cv2.imread(str(image_path))
         return data is not None
     except Exception as e:
         logger.warning(
             f"Unexpected Exception {e} occurred while reading image file {image_path}"
         )
         return False
@@ -104,14 +106,17 @@
 
 def iter_path_regex(path_regex: Path) -> Generator[str, None, None]:
     return glob.iglob(os.path.expanduser(path_regex), recursive=True)
 
 
 def validate_video(video_path: Path) -> bool:
     try:
+        try_to_import_cv2()
+        import cv2
+
         vid = cv2.VideoCapture(str(video_path))
         if not vid.isOpened():
             return False
         return True
     except Exception as e:
         logger.warning(
             f"Unexpected Exception {e} occurred while reading video file {video_path}"
```

### Comparing `evadb-0.2.9/evadb/executor/explain_executor.py` & `evadb-0.3.0/evadb/executor/explain_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/function_scan_executor.py` & `evadb-0.3.0/evadb/executor/function_scan_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/groupby_executor.py` & `evadb-0.3.0/evadb/executor/groupby_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/hash_join_executor.py` & `evadb-0.3.0/evadb/executor/hash_join_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/insert_executor.py` & `evadb-0.3.0/evadb/storage/document_storage_engine.py`

 * *Files 24% similar despite different names*

```diff
@@ -8,51 +8,34 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-import pandas as pd
+from pathlib import Path
+from typing import Iterator
 
-from evadb.catalog.catalog_type import TableType
+from evadb.catalog.models.table_catalog import TableCatalogEntry
 from evadb.database import EvaDBDatabase
-from evadb.executor.abstract_executor import AbstractExecutor
 from evadb.models.storage.batch import Batch
-from evadb.plan_nodes.insert_plan import InsertPlan
-from evadb.storage.storage_engine import StorageEngine
+from evadb.readers.document.document_reader import DocumentReader
+from evadb.storage.abstract_media_storage_engine import AbstractMediaStorageEngine
 
 
-class InsertExecutor(AbstractExecutor):
-    def __init__(self, db: EvaDBDatabase, node: InsertPlan):
-        super().__init__(db, node)
-
-    def exec(self, *args, **kwargs):
-        storage_engine = None
-        table_catalog_entry = None
-
-        # Get catalog entry
-        table_name = self.node.table_ref.table.table_name
-        database_name = self.node.table_ref.table.database_name
-        table_catalog_entry = self.catalog().get_table_catalog_entry(
-            table_name, database_name
-        )
-
-        # Implemented only for STRUCTURED_DATA
-        assert (
-            table_catalog_entry.table_type == TableType.STRUCTURED_DATA
-        ), "INSERT only implemented for structured data"
-
-        values_to_insert = [val_node.value for val_node in self.node.value_list]
-        tuple_to_insert = tuple(values_to_insert)
-        columns_to_insert = [col_node.col_name for col_node in self.node.column_list]
-
-        # Adding all values to Batch for insert
-        dataframe = pd.DataFrame([tuple_to_insert], columns=columns_to_insert)
-        batch = Batch(dataframe)
-
-        storage_engine = StorageEngine.factory(self.db, table_catalog_entry)
-        storage_engine.write(table_catalog_entry, batch)
-
-        yield Batch(
-            pd.DataFrame([f"Number of rows loaded: {str(len(values_to_insert))}"])
-        )
+class DocumentStorageEngine(AbstractMediaStorageEngine):
+    def __init__(self, db: EvaDBDatabase):
+        super().__init__(db)
+
+    def read(self, table: TableCatalogEntry, chunk_params: dict) -> Iterator[Batch]:
+        for doc_files in self._rdb_handler.read(self._get_metadata_table(table), 12):
+            for _, (row_id, file_name) in doc_files.iterrows():
+                system_file_name = self._xform_file_url_to_file_name(file_name)
+                doc_file = Path(table.file_url) / system_file_name
+                # setting batch_mem_size = 1, we need fix it
+                reader = DocumentReader(
+                    str(doc_file), batch_mem_size=1, chunk_params=chunk_params
+                )
+                for batch in reader.read():
+                    batch.frames[table.columns[0].name] = row_id
+                    batch.frames[table.columns[1].name] = str(file_name)
+                    yield batch
```

### Comparing `evadb-0.2.9/evadb/executor/join_build_executor.py` & `evadb-0.3.0/evadb/executor/join_build_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/lateral_join_executor.py` & `evadb-0.3.0/evadb/executor/lateral_join_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/limit_executor.py` & `evadb-0.3.0/evadb/executor/limit_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/load_csv_executor.py` & `evadb-0.3.0/evadb/executor/load_csv_executor.py`

 * *Files 0% similar despite different names*

```diff
@@ -49,15 +49,15 @@
             raise ExecutorError(error)
 
         # Get the column information
         column_list = []
         for column in table_obj.columns:
             column_list.append(
                 TupleValueExpression(
-                    col_name=column.name,
+                    name=column.name,
                     table_alias=table_obj.name.lower(),
                     col_object=column,
                 )
             )
 
         # Read the CSV file
         # converters is a dictionary of functions that convert the values
```

### Comparing `evadb-0.2.9/evadb/executor/load_executor.py` & `evadb-0.3.0/evadb/executor/load_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/load_multimedia_executor.py` & `evadb-0.3.0/evadb/executor/load_multimedia_executor.py`

 * *Files 4% similar despite different names*

```diff
@@ -19,26 +19,34 @@
 import pandas as pd
 
 from evadb.catalog.models.table_catalog import TableCatalogEntry
 from evadb.database import EvaDBDatabase
 from evadb.executor.abstract_executor import AbstractExecutor
 from evadb.executor.executor_utils import ExecutorError, iter_path_regex, validate_media
 from evadb.models.storage.batch import Batch
+from evadb.parser.types import FileFormatType
 from evadb.plan_nodes.load_data_plan import LoadDataPlan
 from evadb.storage.abstract_storage_engine import AbstractStorageEngine
 from evadb.storage.storage_engine import StorageEngine
 from evadb.utils.errors import DatasetFileNotFoundError
+from evadb.utils.generic_utils import try_to_import_cv2, try_to_import_decord
 from evadb.utils.logging_manager import logger
 from evadb.utils.s3_utils import download_from_s3
 
 
 class LoadMultimediaExecutor(AbstractExecutor):
     def __init__(self, db: EvaDBDatabase, node: LoadDataPlan):
         super().__init__(db, node)
         self.media_type = self.node.file_options["file_format"]
+        # check for appropriate packages
+        if self.media_type == FileFormatType.IMAGE:
+            try_to_import_cv2()
+        elif self.media_type == FileFormatType.VIDEO:
+            try_to_import_decord()
+            try_to_import_cv2()
 
     def exec(self, *args, **kwargs):
         storage_engine = None
         table_obj = None
         try:
             video_files = []
             valid_files = []
@@ -68,28 +76,27 @@
                 invalid_files = [
                     str(path)
                     for path, is_valid in zip(video_files, valid_bitmap)
                     if not is_valid
                 ]
 
                 invalid_files_str = "\n".join(invalid_files)
-                err_msg = f"Load {self.media_type.name} failed due to invalid files: \n{invalid_files_str}"
-                logger.error(err_msg)
+                err_msg = f"no valid file found at -- '{invalid_files_str}'."
                 raise ValueError(err_msg)
 
             # Get valid files.
             valid_files = [
                 str(path)
                 for path, is_valid in zip(video_files, valid_bitmap)
                 if is_valid
             ]
 
             if not valid_files:
                 raise DatasetFileNotFoundError(
-                    f"Load {self.media_type.name} failed due to no valid files found on path {str(self.node.file_path)}"
+                    f"no file found at -- '{str(self.node.file_path)}'."
                 )
 
             # Create catalog entry
             table_info = self.node.table_info
             database_name = table_info.database_name
             table_name = table_info.table_name
             # Sanity check to make sure there is no existing table with same name
@@ -119,16 +126,15 @@
             )
 
         except Exception as e:
             # If we fail to obtain the storage engine or table object,
             # there is no further action to take.
             if storage_engine and table_obj:
                 self._rollback_load(storage_engine, table_obj, do_create)
-            err_msg = f"Load {self.media_type.name} failed: encountered unexpected error {str(e)}"
-            logger.error(err_msg)
+            err_msg = f"Load {self.media_type.name} failed: {str(e)}"
             raise ExecutorError(err_msg)
         else:
             yield Batch(
                 pd.DataFrame(
                     [
                         f"Number of loaded {self.media_type.name}: {str(len(valid_files))}"
                     ]
```

### Comparing `evadb-0.2.9/evadb/executor/nested_loop_join_executor.py` & `evadb-0.3.0/evadb/executor/nested_loop_join_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/orderby_executor.py` & `evadb-0.3.0/evadb/executor/orderby_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/plan_executor.py` & `evadb-0.3.0/evadb/executor/plan_executor.py`

 * *Files 2% similar despite different names*

```diff
@@ -15,15 +15,14 @@
 from typing import Iterator
 
 from evadb.database import EvaDBDatabase
 from evadb.executor.abstract_executor import AbstractExecutor
 from evadb.executor.apply_and_merge_executor import ApplyAndMergeExecutor
 from evadb.executor.create_executor import CreateExecutor
 from evadb.executor.create_index_executor import CreateIndexExecutor
-from evadb.executor.create_mat_view_executor import CreateMaterializedViewExecutor
 from evadb.executor.create_udf_executor import CreateUDFExecutor
 from evadb.executor.delete_executor import DeleteExecutor
 from evadb.executor.drop_object_executor import DropObjectExecutor
 from evadb.executor.exchange_executor import ExchangeExecutor
 from evadb.executor.executor_utils import ExecutorError
 from evadb.executor.explain_executor import ExplainExecutor
 from evadb.executor.function_scan_executor import FunctionScanExecutor
@@ -120,16 +119,14 @@
             executor_node = LateralJoinExecutor(db=self._db, node=plan)
         elif plan_opr_type == PlanOprType.HASH_JOIN:
             executor_node = HashJoinExecutor(db=self._db, node=plan)
         elif plan_opr_type == PlanOprType.HASH_BUILD:
             executor_node = BuildJoinExecutor(db=self._db, node=plan)
         elif plan_opr_type == PlanOprType.FUNCTION_SCAN:
             executor_node = FunctionScanExecutor(db=self._db, node=plan)
-        elif plan_opr_type == PlanOprType.CREATE_MATERIALIZED_VIEW:
-            executor_node = CreateMaterializedViewExecutor(db=self._db, node=plan)
         elif plan_opr_type == PlanOprType.EXCHANGE:
             executor_node = ExchangeExecutor(db=self._db, node=plan)
             inner_executor = self._build_execution_tree(plan.inner_plan)
             executor_node.build_inner_executor(inner_executor)
         elif plan_opr_type == PlanOprType.PROJECT:
             executor_node = ProjectExecutor(db=self._db, node=plan)
         elif plan_opr_type == PlanOprType.PREDICATE_FILTER:
@@ -151,17 +148,23 @@
         if plan_opr_type != PlanOprType.EXPLAIN:
             # Build Executor Tree for children
             for children in plan.children:
                 executor_node.append_child(self._build_execution_tree(children))
 
         return executor_node
 
-    def execute_plan(self) -> Iterator[Batch]:
+    def execute_plan(
+        self,
+        do_not_raise_exceptions: bool = False,
+        do_not_print_exceptions: bool = False,
+    ) -> Iterator[Batch]:
         """execute the plan tree"""
         try:
             execution_tree = self._build_execution_tree(self._plan)
             output = execution_tree.exec()
             if output is not None:
                 yield from output
         except Exception as e:
-            logger.exception(str(e))
-            raise ExecutorError(e)
+            if do_not_raise_exceptions is False:
+                if do_not_print_exceptions is False:
+                    logger.exception(str(e))
+                raise ExecutorError(e)
```

### Comparing `evadb-0.2.9/evadb/executor/pp_executor.py` & `evadb-0.3.0/evadb/executor/pp_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/predicate_executor.py` & `evadb-0.3.0/evadb/executor/predicate_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/project_executor.py` & `evadb-0.3.0/evadb/executor/project_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/ray_utils.py` & `evadb-0.3.0/evadb/executor/ray_utils.py`

 * *Files 14% similar despite different names*

```diff
@@ -11,56 +11,73 @@
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import os
 from typing import Callable, Dict, List
 
-import ray
-from ray.exceptions import RayTaskError
-from ray.util.queue import Queue
-
 from evadb.executor.executor_utils import ExecutorError
 
 
 class StageCompleteSignal:
     pass
 
 
-@ray.remote(num_cpus=0)
-def ray_wait_and_alert(tasks: List[ray.ObjectRef], queue: Queue):
-    try:
-        ray.get(tasks)
-        queue.put(StageCompleteSignal)
-    except RayTaskError as e:
-        queue.put(ExecutorError(e.cause))
+def ray_wait_and_alert():
+    import ray
+    from ray.exceptions import RayTaskError
+    from ray.util.queue import Queue
+
+    @ray.remote(num_cpus=0)
+    def _ray_wait_and_alert(tasks: List[ray.ObjectRef], queue: Queue):
+        try:
+            ray.get(tasks)
+            queue.put(StageCompleteSignal)
+        except RayTaskError as e:
+            queue.put(ExecutorError(e.cause))
+
+    return _ray_wait_and_alert
 
 
 # Max calls set to 1 to forcefully release GPU resource when the job is
 # complete. We choose to bypass resource management of Ray, but instead
 # control GPU resource ourselves by configuring the environmental variables
 # when the job enters the Ray process. Due to that, resource release is not
 # cleanly done on the Ray side, we need to set this to prevent memory leak.
 # More detailed explanation can be found in
 # https://github.com/georgia-tech-db/eva/pull/731
-@ray.remote(max_calls=1)
-def ray_parallel(
-    conf_dict: Dict[str, str],
-    executor: Callable,
-    input_queue: Queue,
-    output_queue: Queue,
-):
-    for k, v in conf_dict.items():
-        os.environ[k] = v
-
-    gen = executor(input_queue=input_queue)
-    for next_item in gen:
-        output_queue.put(next_item)
-
-
-@ray.remote(max_calls=1)
-def ray_pull(conf_dict: Dict[str, str], executor: Callable, input_queue: Queue):
-    for k, v in conf_dict.items():
-        os.environ[k] = v
 
-    for next_item in executor():
-        input_queue.put(next_item)
+
+def ray_parallel():
+    import ray
+    from ray.util.queue import Queue
+
+    @ray.remote(max_calls=1)
+    def _ray_parallel(
+        conf_dict: Dict[str, str],
+        executor: Callable,
+        input_queue: Queue,
+        output_queue: Queue,
+    ):
+        for k, v in conf_dict.items():
+            os.environ[k] = v
+
+        gen = executor(input_queue=input_queue)
+        for next_item in gen:
+            output_queue.put(next_item)
+
+    return _ray_parallel
+
+
+def ray_pull():
+    import ray
+    from ray.util.queue import Queue
+
+    @ray.remote(max_calls=1)
+    def _ray_pull(conf_dict: Dict[str, str], executor: Callable, input_queue: Queue):
+        for k, v in conf_dict.items():
+            os.environ[k] = v
+
+        for next_item in executor():
+            input_queue.put(next_item)
+
+    return _ray_pull
```

### Comparing `evadb-0.2.9/evadb/executor/rename_executor.py` & `evadb-0.3.0/evadb/executor/rename_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/sample_executor.py` & `evadb-0.3.0/evadb/executor/sample_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/seq_scan_executor.py` & `evadb-0.3.0/evadb/executor/seq_scan_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/show_info_executor.py` & `evadb-0.3.0/evadb/executor/show_info_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/storage_executor.py` & `evadb-0.3.0/evadb/executor/storage_executor.py`

 * *Files 4% similar despite different names*

```diff
@@ -41,15 +41,15 @@
                     sampling_type=self.node.sampling_type,
                     read_audio=self.node.table_ref.get_audio,
                     read_video=self.node.table_ref.get_video,
                 )
             elif self.node.table.table_type == TableType.IMAGE_DATA:
                 return storage_engine.read(self.node.table)
             elif self.node.table.table_type == TableType.DOCUMENT_DATA:
-                return storage_engine.read(self.node.table)
+                return storage_engine.read(self.node.table, self.node.chunk_params)
             elif self.node.table.table_type == TableType.STRUCTURED_DATA:
                 return storage_engine.read(self.node.table, self.node.batch_mem_size)
             elif self.node.table.table_type == TableType.PDF_DATA:
                 return storage_engine.read(self.node.table)
             else:
                 raise ExecutorError(
                     f"Unsupported TableType  {self.node.table.table_type} encountered"
```

### Comparing `evadb-0.2.9/evadb/executor/union_executor.py` & `evadb-0.3.0/evadb/executor/union_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/executor/vector_index_scan_executor.py` & `evadb-0.3.0/evadb/executor/vector_index_scan_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/expression/__init__.py` & `evadb-0.3.0/evadb/expression/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/expression/abstract_expression.py` & `evadb-0.3.0/evadb/expression/abstract_expression.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/expression/aggregation_expression.py` & `evadb-0.3.0/evadb/expression/aggregation_expression.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/expression/arithmetic_expression.py` & `evadb-0.3.0/evadb/expression/arithmetic_expression.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/expression/comparison_expression.py` & `evadb-0.3.0/evadb/expression/comparison_expression.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/expression/constant_value_expression.py` & `evadb-0.3.0/evadb/expression/constant_value_expression.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/expression/expression_utils.py` & `evadb-0.3.0/evadb/expression/expression_utils.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/expression/function_expression.py` & `evadb-0.3.0/evadb/expression/function_expression.py`

 * *Files 2% similar despite different names*

```diff
@@ -42,15 +42,17 @@
     output is None, the binder sets output_objs to list of all
     output columns of the FunctionExpression. Eg, ['labels',
     'boxes']. Otherwise, only the output columns.
 
     FunctionExpression also needs to prepend its alias to all the
     projected columns. This is important as other parts of the query
     might be assessing the results using alias. Eg,
-    `Select OD.labels FROM Video JOIN LATERAL ObjDetector AS OD;`
+
+    `Select Detector.labels
+     FROM Video JOIN LATERAL ObjDetector AS Detector;`
     """
 
     def __init__(
         self,
         func: Callable,
         name: str,
         output: str = None,
```

### Comparing `evadb-0.2.9/evadb/expression/logical_expression.py` & `evadb-0.3.0/evadb/expression/logical_expression.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/expression/tuple_value_expression.py` & `evadb-0.3.0/evadb/expression/tuple_value_expression.py`

 * *Files 10% similar despite different names*

```diff
@@ -24,43 +24,36 @@
     ExpressionType,
 )
 
 
 class TupleValueExpression(AbstractExpression):
     def __init__(
         self,
-        col_name: str = None,
+        name: str = None,
         table_alias: str = None,
-        col_idx: int = -1,
         col_object: Union[ColumnCatalogEntry, UdfIOCatalogEntry] = None,
         col_alias=None,
     ):
         super().__init__(ExpressionType.TUPLE_VALUE, rtype=ExpressionReturnType.INVALID)
-        self._col_name = col_name
+        self._name = name
         self._table_alias = table_alias
-        self._table_id = None
-        self._col_idx = col_idx
         self._col_object = col_object
         self._col_alias = col_alias
 
     @property
-    def table_id(self) -> int:
-        return self._table_id
-
-    @property
     def table_alias(self) -> str:
         return self._table_alias
 
     @table_alias.setter
     def table_alias(self, table_alias):
         self._table_alias = table_alias
 
     @property
-    def col_name(self) -> str:
-        return self._col_name
+    def name(self) -> str:
+        return self._name
 
     @property
     def col_object(self) -> Union[ColumnCatalogEntry, UdfIOCatalogEntry]:
         return self._col_object
 
     @col_object.setter
     def col_object(self, value: Union[ColumnCatalogEntry, UdfIOCatalogEntry]):
@@ -101,37 +94,33 @@
     def __eq__(self, other):
         is_subtree_equal = super().__eq__(other)
         if not isinstance(other, TupleValueExpression):
             return False
         return (
             is_subtree_equal
             and self.table_alias == other.table_alias
-            and self.table_id == other.table_id
-            and self.col_name == other.col_name
+            and self.name == other.name
             and self.col_alias == other.col_alias
             and self.col_object == other.col_object
-            and self._col_idx == other._col_idx
         )
 
     def __str__(self) -> str:
         expr_str = ""
         if self.table_alias:
             expr_str += f"{str(self.table_alias)}."
-        if self.col_name:
-            expr_str += f"{str(self.col_name)}"
+        if self.name:
+            expr_str += f"{str(self.name)}"
         if self.col_alias:
             expr_str += f" AS {str(self.col_alias)}"
         expr_str += ""
         return expr_str
 
     def __hash__(self) -> int:
         return hash(
             (
                 super().__hash__(),
                 self.table_alias,
-                self.table_id,
-                self.col_name,
+                self.name,
                 self.col_alias,
                 self.col_object,
-                self._col_idx,
             )
         )
```

### Comparing `evadb-0.2.9/evadb/interfaces/__init__.py` & `evadb-0.3.0/evadb/interfaces/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/interfaces/relational/__init__.py` & `evadb-0.3.0/evadb/interfaces/relational/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/interfaces/relational/db.py` & `evadb-0.3.0/evadb/interfaces/relational/db.py`

 * *Files 25% similar despite different names*

```diff
@@ -22,24 +22,30 @@
 from evadb.interfaces.relational.relation import EvaDBQuery
 from evadb.interfaces.relational.utils import execute_statement, try_binding
 from evadb.models.server.response import Response
 from evadb.models.storage.batch import Batch
 from evadb.parser.alias import Alias
 from evadb.parser.select_statement import SelectStatement
 from evadb.parser.utils import (
+    parse_create_table,
     parse_create_udf,
     parse_create_vector_index,
     parse_drop_index,
     parse_drop_table,
     parse_drop_udf,
+    parse_explain,
+    parse_insert,
     parse_load,
     parse_query,
+    parse_rename,
+    parse_show,
     parse_table_clause,
 )
 from evadb.udfs.udf_bootstrap_queries import init_builtin_udfs
+from evadb.utils.generic_utils import is_ray_enabled_and_installed
 from evadb.utils.logging_manager import logger
 
 
 class EvaDBConnection:
     def __init__(self, evadb: EvaDBDatabase, reader, writer):
         self._reader = reader
         self._writer = writer
@@ -52,16 +58,25 @@
 
         Returns:
             EvaDBCursor: The cursor object used to execute queries.
 
 
         Examples:
             >>> import evadb
-            >>> connection = connect()
+            >>> connection = evadb.connection()
             >>> cursor = connection.cursor()
+
+        The cursor can be used to execute queries.
+
+            >>> cursor.query('SELECT * FROM sample_table;').df()
+               col1  col2
+            0     1     2
+            1     3     4
+            2     5     6
+
         """
         # One unique cursor for one connection
         if self._cursor is None:
             self._cursor = EvaDBCursor(self)
         return self._cursor
 
 
@@ -130,31 +145,49 @@
         def func_sync(*args, **kwargs):
             loop = asyncio.get_event_loop()
             res = loop.run_until_complete(func(*args, **kwargs))
             return res
 
         return func_sync
 
-    def table(self, table_name: str) -> EvaDBQuery:
+    def table(
+        self, table_name: str, chunk_size: int = None, chunk_overlap: int = None
+    ) -> EvaDBQuery:
         """
         Retrieves data from a table in the database.
 
         Args:
-            table_name (str): Name of the table.
+            table_name (str): The name of the table to retrieve data from.
+            chunk_size (int, optional): The size of the chunk to break the document into. Only valid for DOCUMENT tables.
+                If not provided, the default value is 4000.
+            chunk_overlap (int, optional): The overlap between consecutive chunks. Only valid for DOCUMENT tables.
+                If not provided, the default value is 200.
 
         Returns:
-            EvaDBQuery: The EvaDBQuery object representing the table query.
+            EvaDBQuery: An EvaDBQuery object representing the table query.
 
         Examples:
-            >>> relation = conn.table("sample_table")
+            >>> relation = cursor.table("sample_table")
+            >>> relation = cursor.select('*')
+            >>> relation.df()
+               col1  col2
+            0     1     2
+            1     3     4
+            2     5     6
+
+            Read a document table using chunk_size 100 and chunk_overlap 10.
+
+            >>> relation = cursor.table("doc_table", chunk_size=100, chunk_overlap=10)
         """
-        table = parse_table_clause(table_name)
+        table = parse_table_clause(
+            table_name, chunk_size=chunk_size, chunk_overlap=chunk_overlap
+        )
         # SELECT * FROM table
         select_stmt = SelectStatement(
-            target_list=[TupleValueExpression(col_name="*")], from_table=table
+            target_list=[TupleValueExpression(name="*")], from_table=table
         )
         try_binding(self._evadb.catalog, select_stmt)
         return EvaDBQuery(self._evadb, select_stmt, alias=Alias(table_name.lower()))
 
     def df(self) -> pandas.DataFrame:
         """
         Returns the result as a pandas DataFrame.
@@ -162,15 +195,20 @@
         Returns:
             pandas.DataFrame: The result as a DataFrame.
 
         Raises:
             Exception: If no valid result is available with the current connection.
 
         Examples:
-            >>> result = conn.query("CREATE TABLE IF NOT EXISTS youtube_video_text AS SELECT SpeechRecognizer(audio) FROM youtube_video;").df()
+            >>> result = cursor.query("CREATE TABLE IF NOT EXISTS youtube_video_text AS SELECT SpeechRecognizer(audio) FROM youtube_video;").df()
+            >>> result
+            Empty DataFrame
+            >>> relation = cursor.table("youtube_video_text").select('*').df()
+                speechrecognizer.response
+            0	"Sample Text from speech recognizer"
         """
         if not self._result:
             raise Exception("No valid result with the current cursor")
         return self._result.frames
 
     def create_vector_index(
         self, index_name: str, table_name: str, expr: str, using: str
@@ -186,20 +224,27 @@
 
         Returns:
             EvaDBCursor: The EvaDBCursor object.
 
         Examples:
             Create a Vector Index using QDRANT
 
-            >>> conn.create_vector_index(
+            >>> cursor.create_vector_index(
                     "faiss_index",
                     table_name="meme_images",
                     expr="SiftFeatureExtractor(data)",
                     using="QDRANT"
-                )
+                ).df()
+                        0
+                0	Index faiss_index successfully added to the database
+            >>> relation = cursor.table("PDFs")
+            >>> relation.order("Similarity(ImageFeatureExtractor(Open('/images/my_meme')), ImageFeatureExtractor(data) ) DESC")
+            >>> relation.df()
+
+
         """
         stmt = parse_create_vector_index(index_name, table_name, expr, using)
         self._result = execute_statement(self._evadb, stmt)
         return self
 
     def load(
         self, file_regex: str, table_name: str, format: str, **kwargs
@@ -215,15 +260,18 @@
 
         Returns:
             EvaDBQuery: The EvaDBQuery object representing the load query.
 
         Examples:
             Load the online_video.mp4 file into table named 'youtube_video'.
 
-            >>> conn.load("online_video.mp4", "youtube_video", "video")
+            >>> cursor.load(file_regex="online_video.mp4", table_name="youtube_video", format="video").df()
+                    0
+            0	Number of loaded VIDEO: 1
+
         """
         # LOAD {FORMAT} file_regex INTO table_name
         stmt = parse_load(table_name, file_regex, format, **kwargs)
         return EvaDBQuery(self._evadb, stmt)
 
     def drop_table(self, table_name: str, if_exists: bool = True) -> "EvaDBQuery":
         """
@@ -235,15 +283,17 @@
 
         Returns:
             EvaDBQuery: The EvaDBQuery object representing the DROP TABLE.
 
         Examples:
             Drop table 'sample_table'
 
-            >>> conn.drop_table("sample_table", if_exists = True)
+            >>> cursor.drop_table("sample_table", if_exists = True).df()
+                0
+            0	Table Successfully dropped: sample_table
         """
         stmt = parse_drop_table(table_name, if_exists)
         return EvaDBQuery(self._evadb, stmt)
 
     def drop_udf(self, udf_name: str, if_exists: bool = True) -> "EvaDBQuery":
         """
         Drop a udf in the database.
@@ -254,15 +304,17 @@
 
         Returns:
             EvaDBQuery: The EvaDBQuery object representing the DROP UDF.
 
         Examples:
             Drop UDF 'ObjectDetector'
 
-            >>> conn.drop_udf("ObjectDetector", if_exists = True)
+            >>> cursor.drop_udf("ObjectDetector", if_exists = True)
+                0
+            0	UDF Successfully dropped: ObjectDetector
         """
         stmt = parse_drop_udf(udf_name, if_exists)
         return EvaDBQuery(self._evadb, stmt)
 
     def drop_index(self, index_name: str, if_exists: bool = True) -> "EvaDBQuery":
         """
         Drop an index in the database.
@@ -273,15 +325,15 @@
 
         Returns:
             EvaDBQuery: The EvaDBQuery object representing the DROP INDEX.
 
         Examples:
             Drop the index with name 'faiss_index'
 
-            >>> conn.drop_index("faiss_index", if_exists = True)
+            >>> cursor.drop_index("faiss_index", if_exists = True)
         """
         stmt = parse_drop_index(index_name, if_exists)
         return EvaDBQuery(self._evadb, stmt)
 
     def create_udf(
         self,
         udf_name: str,
@@ -300,35 +352,186 @@
             type (str): Type of the udf (e.g. HuggingFace).
             **kwargs: Additional keyword arguments for configuring the create udf operation.
 
         Returns:
             EvaDBQuery: The EvaDBQuery object representing the UDF created.
 
         Examples:
-            >>> conn.create_udf("MnistImageClassifier", if_exists = True, 'mnist_image_classifier.py')
+            >>> cursor.create_udf("MnistImageClassifier", if_exists = True, 'mnist_image_classifier.py')
+                0
+            0	UDF Successfully created: MnistImageClassifier
         """
         stmt = parse_create_udf(udf_name, if_not_exists, impl_path, type, **kwargs)
         return EvaDBQuery(self._evadb, stmt)
 
+    def create_table(
+        self, table_name: str, if_not_exists: bool = True, columns: str = None, **kwargs
+    ) -> "EvaDBQuery":
+        """
+        Create a udf in the database.
+
+        Args:
+            udf_name (str): Name of the udf to be created.
+            if_not_exists (bool): If True, do not raise an error if the UDF already exist. If False, raise an error.
+            impl_path (str): Path string to udf's implementation.
+            type (str): Type of the udf (e.g. HuggingFace).
+            **kwargs: Additional keyword arguments for configuring the create udf operation.
+
+        Returns:
+            EvaDBQuery: The EvaDBQuery object representing the UDF created.
+
+        Examples:
+            >>> cursor.create_table("MyCSV", if_exists = True, columns=\"\"\"
+                    id INTEGER UNIQUE,
+                    frame_id INTEGER,
+                    video_id INTEGER,
+                    dataset_name TEXT(30),
+                    label TEXT(30),
+                    bbox NDARRAY FLOAT32(4),
+                    object_id INTEGER\"\"\"
+                    )
+                0
+            0	Table Successfully created: MyCSV
+        """
+        stmt = parse_create_table(table_name, if_not_exists, columns, **kwargs)
+        return EvaDBQuery(self._evadb, stmt)
+
     def query(self, sql_query: str) -> EvaDBQuery:
         """
         Executes a SQL query.
 
         Args:
             sql_query (str): The SQL query to be executed
 
         Returns:
             EvaDBQuery: The EvaDBQuery object.
 
         Examples:
-            >>> conn.query("DROP UDF IF EXISTS SentenceFeatureExtractor;")
+            >>> cursor.query("DROP UDF IF EXISTS SentenceFeatureExtractor;")
+            >>> cursor.query('SELECT * FROM sample_table;').df()
+               col1  col2
+            0     1     2
+            1     3     4
+            2     5     6
         """
         stmt = parse_query(sql_query)
         return EvaDBQuery(self._evadb, stmt)
 
+    def show(self, object_type: str, **kwargs) -> EvaDBQuery:
+        """
+        Shows all entries of the current object_type.
+
+        Args:
+            show_type (str): The type of SHOW query to be executed
+            **kwargs: Additional keyword arguments for configuring the SHOW operation.
+
+        Returns:
+            EvaDBQuery: The EvaDBQuery object.
+
+        Examples:
+            >>> cursor.show("tables").df()
+                name
+            0	SampleTable1
+            1	SampleTable2
+            2	SampleTable3
+        """
+        stmt = parse_show(object_type, **kwargs)
+        return EvaDBQuery(self._evadb, stmt)
+
+    def explain(self, sql_query: str) -> EvaDBQuery:
+        """
+        Executes an EXPLAIN query.
+
+        Args:
+            sql_query (str): The SQL query to be explained
+
+        Returns:
+            EvaDBQuery: The EvaDBQuery object.
+
+        Examples:
+            >>> proposed_plan = cursor.explain("SELECT * FROM sample_table;").df()
+            >>> for step in proposed_plan[0]:
+            >>>   pprint(step)
+             |__ ProjectPlan
+                |__ SeqScanPlan
+                    |__ StoragePlan
+        """
+        stmt = parse_explain(sql_query)
+        return EvaDBQuery(self._evadb, stmt)
+
+    def insert(self, table_name, columns, values, **kwargs) -> EvaDBQuery:
+        """
+        Executes an INSERT query.
+
+        Args:
+            table_name (str): The name of the table to insert into
+            columns (list): The list of columns to insert into
+            values (list): The list of values to insert
+            **kwargs: Additional keyword arguments for configuring the INSERT operation.
+
+        Returns:
+            EvaDBQuery: The EvaDBQuery object.
+
+        Examples:
+            >>> cursor.insert("sample_table", ["id", "name"], [1, "Alice"])
+        """
+        stmt = parse_insert(table_name, columns, values, **kwargs)
+        return EvaDBQuery(self._evadb, stmt)
+
+    def rename(self, table_name, new_table_name, **kwargs) -> EvaDBQuery:
+        """
+        Executes a RENAME query.
+
+        Args:
+            table_name (str): The name of the table to rename
+            new_table_name (str): The new name of the table
+            **kwargs: Additional keyword arguments for configuring the RENAME operation.
+
+        Returns:
+            EvaDBQuery: The EvaDBQuery object.
+
+        Examples:
+            >>> cursor.show("tables").df()
+                name
+            0	SampleVideoTable
+            1	SampleTable
+            2	MyCSV
+            3	videotable
+            >>> cursor.rename("videotable", "sample_table").df()
+            _
+            >>> cursor.show("tables").df()
+                        name
+            0	SampleVideoTable
+            1	SampleTable
+            2	MyCSV
+            3	sample_table
+
+        """
+        stmt = parse_rename(table_name, new_table_name, **kwargs)
+        return EvaDBQuery(self._evadb, stmt)
+
+    def close(self):
+        """
+        Closes the connection.
+
+        Args: None
+
+        Returns:  None
+
+        Examples:
+            >>> cursor.close()
+        """
+        self._evadb.catalog().close()
+
+        ray_enabled = self._evadb.config.get_value("experimental", "ray")
+        if is_ray_enabled_and_installed(ray_enabled):
+            import ray
+
+            ray.shutdown()
+
 
 def connect(
     evadb_dir: str = EvaDB_DATABASE_DIR, sql_backend: str = None
 ) -> EvaDBConnection:
     """
     Connects to the EvaDB server and returns a connection object.
```

### Comparing `evadb-0.2.9/evadb/interfaces/relational/relation.py` & `evadb-0.3.0/evadb/interfaces/relational/relation.py`

 * *Files 2% similar despite different names*

```diff
@@ -53,15 +53,15 @@
         Args:
             alias (str): an alias name to be set for the Relation.
 
         Returns:
             EvaDBQuery: Aliased Relation.
 
         Examples:
-            >>> relation = conn.table("sample_table")
+            >>> relation = cursor.table("sample_table")
             >>> relation.alias('table')
         """
         self._alias = Alias(alias)
 
     def cross_apply(self, expr: str, alias: str) -> "EvaDBQuery":
         """Execute a expr on all the rows of the relation
 
@@ -72,15 +72,15 @@
         Returns:
             `EvaDBQuery`: relation
 
         Examples:
 
             Runs Yolo on all the frames of the input table
 
-            >>> relation = conn.table("videos")
+            >>> relation = cursor.table("videos")
             >>> relation.cross_apply("Yolo(data)", "objs(labels, bboxes, scores)")
 
             Runs Yolo on all the frames of the input table and unnest each object as separate row.
 
             >>> relation.cross_apply("unnest(Yolo(data))", "obj(label, bbox, score)")
         """
         assert self._query_node.from_table is not None
@@ -127,15 +127,15 @@
 
         Parameters:
             expr (str): The filter expression.
 
         Returns:
             EvaDBQuery : Filtered EvaDBQuery.
         Examples:
-            >>> relation = conn.table("sample_table")
+            >>> relation = cursor.table("sample_table")
             >>> relation.filter("col1 > 10")
 
             Filter by sql string
 
             >>> relation.filter("col1 > 10 AND col1 < 20")
 
         """
@@ -155,15 +155,15 @@
         Args:
             num (int): Number of records to return. Will return num records or all records if the Relation contains fewer records.
 
         Returns:
             EvaDBQuery: Relation with subset of records
 
         Examples:
-            >>> relation = conn.table("sample_table")
+            >>> relation = cursor.table("sample_table")
             >>> relation.limit(10)
 
         """
 
         limit_expr = create_limit_expression(num)
         self._query_node = handle_select_clause(
             self._query_node, self._alias, "limit_count", limit_expr
@@ -179,15 +179,15 @@
         Args:
             order_expr (str): sql expression to order the relation
 
         Returns:
             EvaDBQuery: A EvaDBQuery ordered based on the order_expr.
 
         Examples:
-            >>> relation = conn.table("PDFs")
+            >>> relation = cursor.table("PDFs")
             >>> relation.order("Similarity(SentenceTransformerFeatureExtractor('When was the NATO created?'), SentenceTransformerFeatureExtractor(data) ) DESC")
 
         """
 
         parsed_expr = parse_sql_orderby_expr(order_expr)
         self._query_node = handle_select_clause(
             self._query_node, self._alias, "orderby_list", parsed_expr
@@ -204,15 +204,15 @@
         Parameters:
             exprs (Union[str, List[str]]): The expression(s) to be selected. If '*' is provided, it expands to all columns in the current EvaDBQuery.
 
         Returns:
             EvaDBQuery: A EvaDBQuery with subset (or all) of columns.
 
         Examples:
-            >>> relation = conn.table("sample_table")
+            >>> relation = cursor.table("sample_table")
 
             Select all columns in the EvaDBQuery.
 
             >>> relation.select("*")
 
             Select all subset of columns in the EvaDBQuery.
 
@@ -243,12 +243,12 @@
     def sql_query(self) -> str:
         """Get the SQL query that is equivalent to the relation
 
         Returns:
             str: the sql query
 
         Examples:
-            >>> relation = conn.table("sample_table").project('i')
+            >>> relation = cursor.table("sample_table").project('i')
             >>> relation.sql_query()
         """
 
         return str(self._query_node)
```

### Comparing `evadb-0.2.9/evadb/interfaces/relational/utils.py` & `evadb-0.3.0/evadb/interfaces/relational/utils.py`

 * *Files 2% similar despite different names*

```diff
@@ -8,15 +8,14 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-import asyncio
 from typing import Callable, List, Union
 
 from evadb.binder.statement_binder import StatementBinder
 from evadb.binder.statement_binder_context import StatementBinderContext
 from evadb.database import EvaDBDatabase
 from evadb.executor.plan_executor import PlanExecutor
 from evadb.expression.abstract_expression import AbstractExpression
@@ -51,27 +50,27 @@
 def sql_predicate_to_expresssion_tree(expr: str) -> AbstractExpression:
     return parse_predicate_expression(expr)
 
 
 def execute_statement(evadb: EvaDBDatabase, statement: AbstractStatement) -> Batch:
     StatementBinder(StatementBinderContext(evadb.catalog)).bind(statement)
     l_plan = StatementToPlanConverter().visit(statement)
-    p_plan = asyncio.run(PlanGenerator(evadb).build(l_plan))
+    p_plan = PlanGenerator(evadb).build(l_plan)
     output = PlanExecutor(evadb, p_plan).execute_plan()
     if output:
         batch_list = list(output)
         return Batch.concat(batch_list, copy=False)
 
 
 def string_to_lateral_join(expr: str, alias: str):
     return parse_lateral_join(expr, alias)
 
 
 def create_star_expression():
-    return [TupleValueExpression(col_name="*")]
+    return [TupleValueExpression(name="*")]
 
 
 def create_limit_expression(num: int):
     return ConstantValueExpression(num)
 
 
 def try_binding(catalog: Callable, stmt: AbstractStatement):
```

### Comparing `evadb-0.2.9/evadb/models/__init__.py` & `evadb-0.3.0/evadb/models/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/models/catalog/__init__.py` & `evadb-0.3.0/evadb/models/catalog/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/models/catalog/frame_info.py` & `evadb-0.3.0/evadb/models/catalog/frame_info.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/models/catalog/properties.py` & `evadb-0.3.0/evadb/models/catalog/properties.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/models/server/__init__.py` & `evadb-0.3.0/evadb/models/server/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/models/server/response.py` & `evadb-0.3.0/evadb/models/server/response.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/models/storage/__init__.py` & `evadb-0.3.0/evadb/models/storage/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/models/storage/batch.py` & `evadb-0.3.0/evadb/models/storage/batch.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/optimizer/__init__.py` & `evadb-0.3.0/evadb/optimizer/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/optimizer/binder.py` & `evadb-0.3.0/evadb/optimizer/binder.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/optimizer/cost_model.py` & `evadb-0.3.0/evadb/optimizer/cost_model.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/optimizer/group.py` & `evadb-0.3.0/evadb/optimizer/group.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/optimizer/group_expression.py` & `evadb-0.3.0/evadb/optimizer/group_expression.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/optimizer/memo.py` & `evadb-0.3.0/evadb/optimizer/memo.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/optimizer/operators.py` & `evadb-0.3.0/evadb/optimizer/operators.py`

 * *Files 1% similar despite different names*

```diff
@@ -52,15 +52,14 @@
     LOGICALUNION = auto()
     LOGICALGROUPBY = auto()
     LOGICALORDERBY = auto()
     LOGICALLIMIT = auto()
     LOGICALSAMPLE = auto()
     LOGICALJOIN = auto()
     LOGICALFUNCTIONSCAN = auto()
-    LOGICAL_CREATE_MATERIALIZED_VIEW = auto()
     LOGICAL_SHOW = auto()
     LOGICALEXPLAIN = auto()
     LOGICALCREATEINDEX = auto()
     LOGICAL_APPLY_AND_MERGE = auto()
     LOGICAL_EXTRACT_OBJECT = auto()
     LOGICAL_VECTOR_INDEX_SCAN = auto()
     LOGICALDELIMITER = auto()
@@ -176,23 +175,25 @@
         video: TableRef,
         table_obj: TableCatalogEntry,
         alias: str,
         predicate: AbstractExpression = None,
         target_list: List[AbstractExpression] = None,
         sampling_rate: int = None,
         sampling_type: str = None,
+        chunk_params: dict = {},
         children=None,
     ):
         self._video = video
         self._table_obj = table_obj
         self._alias = alias
         self._predicate = predicate
         self._target_list = target_list
         self._sampling_rate = sampling_rate
         self._sampling_type = sampling_type
+        self.chunk_params = chunk_params
         super().__init__(OperatorType.LOGICALGET, children)
 
     @property
     def video(self):
         return self._video
 
     @property
@@ -228,27 +229,29 @@
             and self.video == other.video
             and self.table_obj == other.table_obj
             and self.alias == other.alias
             and self.predicate == other.predicate
             and self.target_list == other.target_list
             and self.sampling_rate == other.sampling_rate
             and self.sampling_type == other.sampling_type
+            and self.chunk_params == other.chunk_params
         )
 
     def __hash__(self) -> int:
         return hash(
             (
                 super().__hash__(),
                 self.alias,
                 self.video,
                 self.table_obj,
                 self.predicate,
                 tuple(self.target_list or []),
                 self.sampling_rate,
                 self.sampling_type,
+                frozenset(self.chunk_params.items()),
             )
         )
 
 
 class LogicalQueryDerivedGet(Operator):
     def __init__(
         self,
@@ -1008,68 +1011,14 @@
                 self.left_keys,
                 self.right_keys,
                 tuple(self.join_project or []),
             )
         )
 
 
-class LogicalCreateMaterializedView(Operator):
-    """Logical node for create materialized view operations
-    Arguments:
-        view {TableRef}: [view table that is to be created]
-        col_list{List[ColumnDefinition]} -- column names in the view
-        if_not_exists {bool}: [whether to override if view exists]
-    """
-
-    def __init__(
-        self,
-        view: TableInfo,
-        col_list: List[ColumnDefinition],
-        if_not_exists: bool = False,
-        children=None,
-    ):
-        super().__init__(OperatorType.LOGICAL_CREATE_MATERIALIZED_VIEW, children)
-        self._view = view
-        self._col_list = col_list
-        self._if_not_exists = if_not_exists
-
-    @property
-    def view(self):
-        return self._view
-
-    @property
-    def if_not_exists(self):
-        return self._if_not_exists
-
-    @property
-    def col_list(self):
-        return self._col_list
-
-    def __eq__(self, other):
-        is_subtree_equal = super().__eq__(other)
-        if not isinstance(other, LogicalCreateMaterializedView):
-            return False
-        return (
-            is_subtree_equal
-            and self.view == other.view
-            and self.col_list == other.col_list
-            and self.if_not_exists == other.if_not_exists
-        )
-
-    def __hash__(self) -> int:
-        return hash(
-            (
-                super().__hash__(),
-                self.view,
-                tuple(self.col_list),
-                self.if_not_exists,
-            )
-        )
-
-
 class LogicalShow(Operator):
     def __init__(self, show_type: ShowType, children: List = None):
         super().__init__(OperatorType.LOGICAL_SHOW, children)
         self._show_type = show_type
 
     @property
     def show_type(self):
```

### Comparing `evadb-0.2.9/evadb/optimizer/optimizer_context.py` & `evadb-0.3.0/evadb/optimizer/optimizer_context.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/optimizer/optimizer_task_stack.py` & `evadb-0.3.0/evadb/optimizer/optimizer_task_stack.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/optimizer/optimizer_tasks.py` & `evadb-0.3.0/evadb/optimizer/optimizer_tasks.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/optimizer/optimizer_utils.py` & `evadb-0.3.0/evadb/optimizer/optimizer_utils.py`

 * *Files 0% similar despite different names*

```diff
@@ -214,15 +214,15 @@
         if isinstance(col_catalog_obj, ColumnCatalogEntry):
             new_keys = []
             table_obj = catalog.get_table_catalog_entry(col_catalog_obj.table_name)
             for col in get_table_primary_columns(table_obj):
                 new_obj = catalog.get_column_catalog_entry(table_obj, col.name)
                 new_keys.append(
                     TupleValueExpression(
-                        col_name=col.name,
+                        name=col.name,
                         table_alias=child.table_alias,
                         col_object=new_obj,
                         col_alias=f"{child.table_alias}.{col.name}",
                     )
                 )
 
             return new_keys
```

### Comparing `evadb-0.2.9/evadb/optimizer/plan_generator.py` & `evadb-0.3.0/evadb/optimizer/plan_generator.py`

 * *Files 4% similar despite different names*

```diff
@@ -8,33 +8,28 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-import asyncio
-
-import nest_asyncio
 
 from evadb.database import EvaDBDatabase
 from evadb.optimizer.cost_model import CostModel
 from evadb.optimizer.operators import Operator
 from evadb.optimizer.optimizer_context import OptimizerContext
 from evadb.optimizer.optimizer_task_stack import OptimizerTaskStack
 from evadb.optimizer.optimizer_tasks import (
     BottomUpRewrite,
     OptimizeGroup,
     TopDownRewrite,
 )
 from evadb.optimizer.property import PropertyType
 from evadb.optimizer.rules.rules_manager import RulesManager
 
-nest_asyncio.apply()
-
 
 class PlanGenerator:
     """
     Used for building Physical Plan from Logical Plan.
     """
 
     def __init__(
@@ -65,15 +60,15 @@
             child_plan = self.build_optimal_physical_plan(
                 child_grp_id, optimizer_context
             )
             physical_plan.append_child(child_plan)
 
         return physical_plan
 
-    async def optimize(self, logical_plan: Operator):
+    def optimize(self, logical_plan: Operator):
         optimizer_context = OptimizerContext(
             self.db, self.cost_model, self.rules_manager
         )
         memo = optimizer_context.memo
         grp_expr = optimizer_context.add_opr_to_group(opr=logical_plan)
         root_grp_id = grp_expr.group_id
         root_expr = memo.groups[root_grp_id].logical_exprs[0]
@@ -105,15 +100,15 @@
         optimizer_context.task_stack.push(OptimizeGroup(root_group, optimizer_context))
         self.execute_task_stack(optimizer_context.task_stack)
 
         # Build Optimal Tree
         optimal_plan = self.build_optimal_physical_plan(root_grp_id, optimizer_context)
         return optimal_plan
 
-    async def build(self, logical_plan: Operator):
+    def build(self, logical_plan: Operator):
         # apply optimizations
         try:
-            plan = await asyncio.wait_for(self.optimize(logical_plan), timeout=60.0)
+            plan = self.optimize(logical_plan)
         except TimeoutError:
-            print("Optimizer timed out!")
+            raise ValueError("Optimizer timed out!")
 
         return plan
```

### Comparing `evadb-0.2.9/evadb/optimizer/property.py` & `evadb-0.3.0/evadb/optimizer/property.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/optimizer/rules/__init__.py` & `evadb-0.3.0/evadb/optimizer/rules/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/optimizer/rules/pattern.py` & `evadb-0.3.0/evadb/optimizer/rules/pattern.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/optimizer/rules/rules.py` & `evadb-0.3.0/evadb/optimizer/rules/rules.py`

 * *Files 2% similar despite different names*

```diff
@@ -35,15 +35,14 @@
     extract_pushdown_predicate_for_alias,
     get_expression_execution_cost,
 )
 from evadb.optimizer.rules.pattern import Pattern
 from evadb.optimizer.rules.rules_base import Promise, Rule, RuleType
 from evadb.parser.types import JoinType, ParserOrderBySortType
 from evadb.plan_nodes.apply_and_merge_plan import ApplyAndMergePlan
-from evadb.plan_nodes.create_mat_view_plan import CreateMaterializedViewPlan
 from evadb.plan_nodes.exchange_plan import ExchangePlan
 from evadb.plan_nodes.explain_plan import ExplainPlan
 from evadb.plan_nodes.hash_join_build_plan import HashJoinBuildPlan
 from evadb.plan_nodes.nested_loop_join_plan import NestedLoopJoinPlan
 from evadb.plan_nodes.predicate_plan import PredicatePlan
 from evadb.plan_nodes.project_plan import ProjectPlan
 from evadb.plan_nodes.show_info_plan import ShowInfoPlan
@@ -52,15 +51,14 @@
     from evadb.optimizer.optimizer_context import OptimizerContext
 
 from evadb.optimizer.operators import (
     Dummy,
     LogicalApplyAndMerge,
     LogicalCreate,
     LogicalCreateIndex,
-    LogicalCreateMaterializedView,
     LogicalCreateUDF,
     LogicalDelete,
     LogicalDropObject,
     LogicalExchange,
     LogicalExplain,
     LogicalExtractObject,
     LogicalFilter,
@@ -874,14 +872,15 @@
         after.append_child(
             StoragePlan(
                 before.table_obj,
                 before.video,
                 predicate=before.predicate,
                 sampling_rate=before.sampling_rate,
                 sampling_type=before.sampling_type,
+                chunk_params=before.chunk_params,
             )
         )
         yield after
 
 
 class LogicalDerivedGetToPhysical(Rule):
     def __init__(self):
@@ -1101,37 +1100,14 @@
             join_node.join_type, join_node.join_predicate
         )
         nested_loop_join_plan.append_child(join_node.lhs())
         nested_loop_join_plan.append_child(join_node.rhs())
         yield nested_loop_join_plan
 
 
-class LogicalCreateMaterializedViewToPhysical(Rule):
-    def __init__(self):
-        pattern = Pattern(OperatorType.LOGICAL_CREATE_MATERIALIZED_VIEW)
-        pattern.append_child(Pattern(OperatorType.DUMMY))
-        super().__init__(RuleType.LOGICAL_MATERIALIZED_VIEW_TO_PHYSICAL, pattern)
-
-    def promise(self):
-        return Promise.LOGICAL_MATERIALIZED_VIEW_TO_PHYSICAL
-
-    def check(self, grp_id: int, context: OptimizerContext):
-        return True
-
-    def apply(self, before: LogicalCreateMaterializedView, context: OptimizerContext):
-        after = CreateMaterializedViewPlan(
-            before.view,
-            columns=before.col_list,
-            if_not_exists=before.if_not_exists,
-        )
-        for child in before.children:
-            after.append_child(child)
-        yield after
-
-
 class LogicalFilterToPhysical(Rule):
     def __init__(self):
         pattern = Pattern(OperatorType.LOGICALFILTER)
         pattern.append_child(Pattern(OperatorType.DUMMY))
         super().__init__(RuleType.LOGICAL_FILTER_TO_PHYSICAL, pattern)
 
     def promise(self):
@@ -1240,14 +1216,29 @@
             before.search_query_expr,
         )
         for child in before.children:
             after.append_child(child)
         yield after
 
 
+"""
+Rules to optimize Ray.
+"""
+
+
+def get_ray_env_dict():
+    # Get the highest GPU id and expose all GPUs that have id lower than
+    # the max id.
+    if len(Context().gpus) > 0:
+        max_gpu_id = max(Context().gpus) + 1
+        return {"CUDA_VISIBLE_DEVICES": ",".join([str(n) for n in range(max_gpu_id)])}
+    else:
+        return {}
+
+
 class LogicalExchangeToPhysical(Rule):
     def __init__(self):
         pattern = Pattern(OperatorType.LOGICALEXCHANGE)
         pattern.append_child(Pattern(OperatorType.DUMMY))
         super().__init__(RuleType.LOGICAL_EXCHANGE_TO_PHYSICAL, pattern)
 
     def promise(self):
@@ -1274,23 +1265,23 @@
 
     def check(self, grp_id: int, context: OptimizerContext):
         return True
 
     def apply(self, before: LogicalApplyAndMerge, context: OptimizerContext):
         apply_plan = ApplyAndMergePlan(before.func_expr, before.alias, before.do_unnest)
 
-        parallelism = 2 if len(Context().gpus) > 1 else 1
-        ray_parallel_env_conf_dict = [
-            {"CUDA_VISIBLE_DEVICES": str(i)} for i in range(parallelism)
-        ]
+        parallelism = 2
+
+        ray_process_env_dict = get_ray_env_dict()
+        ray_parallel_env_conf_dict = [ray_process_env_dict for _ in range(parallelism)]
 
         exchange_plan = ExchangePlan(
             inner_plan=apply_plan,
             parallelism=parallelism,
-            ray_pull_env_conf_dict={"CUDA_VISIBLE_DEVICES": "0"},
+            ray_pull_env_conf_dict=ray_process_env_dict,
             ray_parallel_env_conf_dict=ray_parallel_env_conf_dict,
         )
         for child in before.children:
             exchange_plan.append_child(child)
 
         yield exchange_plan
 
@@ -1313,23 +1304,25 @@
         if before.target_list is None or not any(
             [isinstance(expr, FunctionExpression) for expr in before.target_list]
         ):
             for child in before.children:
                 project_plan.append_child(child)
             yield project_plan
         else:
-            parallelism = 2 if len(Context().gpus) > 1 else 1
+            parallelism = 2
+
+            ray_process_env_dict = get_ray_env_dict()
             ray_parallel_env_conf_dict = [
-                {"CUDA_VISIBLE_DEVICES": str(i)} for i in range(parallelism)
+                ray_process_env_dict for _ in range(parallelism)
             ]
 
             exchange_plan = ExchangePlan(
                 inner_plan=project_plan,
                 parallelism=parallelism,
-                ray_pull_env_conf_dict={"CUDA_VISIBLE_DEVICES": "0"},
+                ray_pull_env_conf_dict=ray_process_env_dict,
                 ray_parallel_env_conf_dict=ray_parallel_env_conf_dict,
             )
             for child in before.children:
                 exchange_plan.append_child(child)
             yield exchange_plan
```

### Comparing `evadb-0.2.9/evadb/optimizer/rules/rules_base.py` & `evadb-0.3.0/evadb/optimizer/rules/rules_base.py`

 * *Files 2% similar despite different names*

```diff
@@ -64,15 +64,14 @@
     LOGICAL_DELETE_TO_PHYSICAL = auto()
     LOGICAL_LOAD_TO_PHYSICAL = auto()
     LOGICAL_CREATE_TO_PHYSICAL = auto()
     LOGICAL_CREATE_FROM_SELECT_TO_PHYSICAL = auto()
     LOGICAL_RENAME_TO_PHYSICAL = auto()
     LOGICAL_DROP_OBJECT_TO_PHYSICAL = auto()
     LOGICAL_CREATE_UDF_TO_PHYSICAL = auto()
-    LOGICAL_MATERIALIZED_VIEW_TO_PHYSICAL = auto()
     LOGICAL_GET_TO_SEQSCAN = auto()
     LOGICAL_SAMPLE_TO_UNIFORMSAMPLE = auto()
     LOGICAL_DERIVED_GET_TO_PHYSICAL = auto()
     LOGICAL_LATERAL_JOIN_TO_PHYSICAL = auto()
     LOGICAL_JOIN_TO_PHYSICAL_HASH_JOIN = auto()
     LOGICAL_JOIN_TO_PHYSICAL_NESTED_LOOP_JOIN = auto()
     LOGICAL_FUNCTION_SCAN_TO_PHYSICAL = auto()
@@ -94,15 +93,14 @@
     Rule with a higher enum will be preferred in case of
     conflict
     """
 
     # IMPLEMENTATION RULES
     LOGICAL_EXCHANGE_TO_PHYSICAL = auto()
     LOGICAL_UNION_TO_PHYSICAL = auto()
-    LOGICAL_MATERIALIZED_VIEW_TO_PHYSICAL = auto()
     LOGICAL_GROUPBY_TO_PHYSICAL = auto()
     LOGICAL_ORDERBY_TO_PHYSICAL = auto()
     LOGICAL_LIMIT_TO_PHYSICAL = auto()
     LOGICAL_INSERT_TO_PHYSICAL = auto()
     LOGICAL_DELETE_TO_PHYSICAL = auto()
     LOGICAL_RENAME_TO_PHYSICAL = auto()
     LOGICAL_DROP_OBJECT_TO_PHYSICAL = auto()
```

### Comparing `evadb-0.2.9/evadb/optimizer/rules/rules_manager.py` & `evadb-0.3.0/evadb/optimizer/rules/rules_manager.py`

 * *Files 3% similar despite different names*

```diff
@@ -25,15 +25,14 @@
     CombineSimilarityOrderByAndLimitToVectorIndexScan,
     EmbedFilterIntoGet,
     EmbedSampleIntoGet,
     LogicalApplyAndMergeToPhysical,
     LogicalApplyAndMergeToRayPhysical,
     LogicalCreateFromSelectToPhysical,
     LogicalCreateIndexToVectorIndex,
-    LogicalCreateMaterializedViewToPhysical,
     LogicalCreateToPhysical,
     LogicalCreateUDFToPhysical,
     LogicalDeleteToPhysical,
     LogicalDerivedGetToPhysical,
     LogicalDropObjectToPhysical,
     LogicalExchangeToPhysical,
     LogicalExplainToPhysical,
@@ -58,14 +57,15 @@
     PushDownFilterThroughApplyAndMerge,
     PushDownFilterThroughJoin,
     ReorderPredicates,
     XformExtractObjectToLinearFlow,
     XformLateralJoinToLinearFlow,
 )
 from evadb.optimizer.rules.rules_base import Rule
+from evadb.utils.generic_utils import is_ray_enabled_and_installed
 
 
 class RulesManager:
     def __init__(self, config: ConfigurationManager):
         self._logical_rules = [
             LogicalInnerJoinCommutativity(),
             CacheFunctionExpressionInApply(),
@@ -103,24 +103,28 @@
             LogicalGroupByToPhysical(),
             LogicalOrderByToPhysical(),
             LogicalLimitToPhysical(),
             LogicalJoinToPhysicalNestedLoopJoin(),
             LogicalLateralJoinToPhysical(),
             LogicalJoinToPhysicalHashJoin(),
             LogicalFunctionScanToPhysical(),
-            LogicalCreateMaterializedViewToPhysical(),
             LogicalFilterToPhysical(),
             LogicalShowToPhysical(),
             LogicalExplainToPhysical(),
             LogicalCreateIndexToVectorIndex(),
             LogicalVectorIndexScanToPhysical(),
         ]
 
+        # These rules are enabled only if
+        # (1) ray is installed and (2) ray is enabled
+        # Ray must be installed using pip
+        # It must also be enabled in "evadb.yml"
+        # NOTE: By default, it is not enabled
         ray_enabled = config.get_value("experimental", "ray")
-        if ray_enabled:
+        if is_ray_enabled_and_installed(ray_enabled):
             self._implementation_rules.extend(
                 [
                     LogicalExchangeToPhysical(),
                     LogicalApplyAndMergeToRayPhysical(),
                     LogicalProjectToRayPhysical(),
                 ]
             )
```

### Comparing `evadb-0.2.9/evadb/optimizer/statement_to_opr_converter.py` & `evadb-0.3.0/evadb/optimizer/statement_to_opr_converter.py`

 * *Files 4% similar despite different names*

```diff
@@ -12,15 +12,14 @@
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 from evadb.expression.abstract_expression import AbstractExpression
 from evadb.optimizer.operators import (
     LogicalCreate,
     LogicalCreateIndex,
-    LogicalCreateMaterializedView,
     LogicalCreateUDF,
     LogicalDelete,
     LogicalDropObject,
     LogicalExplain,
     LogicalExtractObject,
     LogicalFilter,
     LogicalFunctionScan,
@@ -39,15 +38,14 @@
     LogicalUnion,
 )
 from evadb.optimizer.optimizer_utils import (
     column_definition_to_udf_io,
     metadata_definition_to_udf_metadata,
 )
 from evadb.parser.create_index_statement import CreateIndexStatement
-from evadb.parser.create_mat_view_statement import CreateMaterializedViewStatement
 from evadb.parser.create_statement import CreateTableStatement
 from evadb.parser.create_udf_statement import CreateUDFStatement
 from evadb.parser.delete_statement import DeleteTableStatement
 from evadb.parser.drop_object_statement import DropObjectStatement
 from evadb.parser.explain_statement import ExplainStatement
 from evadb.parser.insert_statement import InsertTableStatement
 from evadb.parser.load_statement import LoadDataStatement
@@ -291,23 +289,14 @@
             statement.table_info,
             statement.path,
             statement.column_list,
             statement.file_options,
         )
         self._plan = load_data_opr
 
-    def visit_materialized_view(self, statement: CreateMaterializedViewStatement):
-        mat_view_opr = LogicalCreateMaterializedView(
-            statement.view_info, statement.col_list, statement.if_not_exists
-        )
-
-        self.visit_select(statement.query)
-        mat_view_opr.append_child(self._plan)
-        self._plan = mat_view_opr
-
     def visit_show(self, statement: ShowStatement):
         show_opr = LogicalShow(statement.show_type)
         self._plan = show_opr
 
     def visit_explain(self, statement: ExplainStatement):
         explain_opr = LogicalExplain([self.visit(statement.explainable_stmt)])
         self._plan = explain_opr
@@ -347,16 +336,14 @@
             self.visit_rename(statement)
         elif isinstance(statement, CreateUDFStatement):
             self.visit_create_udf(statement)
         elif isinstance(statement, DropObjectStatement):
             self.visit_drop_object(statement)
         elif isinstance(statement, LoadDataStatement):
             self.visit_load_data(statement)
-        elif isinstance(statement, CreateMaterializedViewStatement):
-            self.visit_materialized_view(statement)
         elif isinstance(statement, ShowStatement):
             self.visit_show(statement)
         elif isinstance(statement, ExplainStatement):
             self.visit_explain(statement)
         elif isinstance(statement, CreateIndexStatement):
             self.visit_create_index(statement)
         elif isinstance(statement, DeleteTableStatement):
```

### Comparing `evadb-0.2.9/evadb/parser/__init__.py` & `evadb-0.3.0/evadb/parser/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/alias.py` & `evadb-0.3.0/evadb/parser/alias.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/create_index_statement.py` & `evadb-0.3.0/evadb/parser/create_index_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/create_statement.py` & `evadb-0.3.0/evadb/parser/create_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/create_udf_statement.py` & `evadb-0.3.0/evadb/parser/create_udf_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/delete_statement.py` & `evadb-0.3.0/evadb/parser/delete_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/drop_object_statement.py` & `evadb-0.3.0/evadb/parser/drop_object_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/evadb.lark` & `evadb-0.3.0/evadb/parser/evadb.lark`

 * *Files 4% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 // Top Level Description
 
 start: (sql_statement? ";")+
 
 sql_statement: ddl_statement | dml_statement | utility_statement
         
-ddl_statement: create_database | create_table | create_index | create_udf | create_materialized_view
+ddl_statement: create_database | create_table | create_index | create_udf
     | drop_database | drop_table | drop_udf | drop_index | rename_table
     
 dml_statement: select_statement | insert_statement | update_statement
     | delete_statement | load_statement
     
 utility_statement: describe_statement | show_statement | help_statement | explain_statement
 
@@ -25,17 +25,14 @@
 // Rename statements
 
 rename_table: RENAME TABLE table_name TO table_name
     
 // Create UDFs
 create_udf: CREATE UDF if_not_exists? udf_name INPUT create_definitions OUTPUT create_definitions TYPE udf_type IMPL udf_impl udf_metadata* | CREATE UDF if_not_exists? udf_name IMPL udf_impl udf_metadata* | CREATE UDF if_not_exists? udf_name TYPE udf_type udf_metadata*
 
-// Create Materialized View
-create_materialized_view: CREATE MATERIALIZED VIEW if_not_exists? table_name ("(" uid_list ")")? AS select_statement
-
 // Details
 udf_name: uid
 
 udf_type: uid
 
 udf_impl: string_literal
 
@@ -106,17 +103,21 @@
 order_by_expression: expression sort_order?
 
 sort_order: ASC | DESC
 
 // Forcing EXPLICIT JOIN KEYWORD
 table_sources: table_source
     
-table_source: table_source_item_with_sample join_part* 
-    
-table_source_item_with_sample: table_source_item alias_clause? (sample_clause | sample_clause_with_type)?
+table_source: table_source_item_with_param join_part* 
+
+table_source_item_with_param: table_source_item alias_clause? (sample_params | chunk_params)?
+
+sample_params:  sample_clause | sample_clause_with_type
+
+chunk_params: CHUNK_SIZE decimal_literal | CHUNK_SIZE decimal_literal CHUNK_OVERLAP decimal_literal | CHUNK_OVERLAP decimal_literal
 
 table_source_item: table_name | subquery_table_source_item   
     
 
 table_valued_function: function_call                                
     | UNNEST LR_BRACKET function_call RR_BRACKET   
     
@@ -124,15 +125,16 @@
     
 sample_clause: SAMPLE decimal_literal
 
 sample_clause_with_type: SAMPLE sample_type decimal_literal*
 
 sample_type: IFRAMES | AUDIORATE
 
-join_part: JOIN table_source_item_with_sample (ON expression | USING LR_BRACKET uid_list RR_BRACKET)?  ->inner_join
+
+join_part: JOIN table_source_item_with_param (ON expression | USING LR_BRACKET uid_list RR_BRACKET)?  ->inner_join
          | JOIN LATERAL table_valued_function alias_clause? ->lateral_join
     
 alias_clause: AS? uid "(" uid_list ")" | AS? uid
     
 // Select Statement Details
 
 query_expression: "(" query_specification ")" | "(" query_expression ")"
@@ -158,15 +160,15 @@
     
 help_statement: HELP STRING_LITERAL
     
 show_statement: SHOW (UDFS | TABLES)
 
 explain_statement: EXPLAIN explainable_statement
 
-explainable_statement : select_statement | insert_statement | update_statement | delete_statement | create_materialized_view
+explainable_statement : select_statement | insert_statement | update_statement | delete_statement | create_table
 
 // Common Clauses
 
 //    DB Objects
 
 full_id: uid dotted_id?
     
@@ -303,14 +305,16 @@
 AND:                                 "AND"i
 ANY:                                 "ANY"i
 ANYDIM:                              "ANYDIM"i
 AS:                                  "AS"i
 ASC:                                 "ASC"i
 BLOB:                                "BLOB"i
 BY:                                  "BY"i
+CHUNK_SIZE:                          "CHUNK_SIZE"i
+CHUNK_OVERLAP:                       "CHUNK_OVERLAP"i
 COLUMN:                              "COLUMN"i
 CREATE:                              "CREATE"i
 DATABASE:                            "DATABASE"i
 DEFAULT:                             "DEFAULT"i
 DELETE:                              "DELETE"i
 DESC:                                "DESC"i
 DESCRIBE:                            "DESCRIBE"i
@@ -436,18 +440,14 @@
 // UDF
 UDF:						         "UDF"i
 INPUT:                               "INPUT"i
 OUTPUT:                              "OUTPUT"i
 TYPE:                                "TYPE"i
 IMPL:                                "IMPL"i
 
-// MATERIALIZED
-MATERIALIZED:                        "MATERIALIZED"i
-VIEW:                                "VIEW"i
-
 // Common function names
 
 ABS:                                 "ABS"i
 
 // Operators
 // Operators. Assignment
```

### Comparing `evadb-0.2.9/evadb/parser/explain_statement.py` & `evadb-0.3.0/evadb/parser/explain_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/insert_statement.py` & `evadb-0.3.0/evadb/parser/insert_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/lark_parser.py` & `evadb-0.3.0/evadb/parser/lark_parser.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/lark_visitor/__init__.py` & `evadb-0.3.0/evadb/parser/lark_visitor/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/lark_visitor/_common_clauses_ids.py` & `evadb-0.3.0/evadb/parser/lark_visitor/_common_clauses_ids.py`

 * *Files 1% similar despite different names*

```diff
@@ -36,17 +36,17 @@
 
     def full_column_name(self, tree):
         uid = self.visit(tree.children[0])
 
         # check for dottedid
         if len(tree.children) > 1:
             dotted_id = self.visit(tree.children[1])
-            return TupleValueExpression(table_alias=uid, col_name=dotted_id)
+            return TupleValueExpression(table_alias=uid, name=dotted_id)
         else:
-            return TupleValueExpression(col_name=uid)
+            return TupleValueExpression(name=uid)
 
     def dotted_id(self, tree):
         dotted_id = str(tree.children[0])
         dotted_id = dotted_id.lstrip(".")
         return dotted_id
 
     def simple_id(self, tree):
```

### Comparing `evadb-0.2.9/evadb/parser/lark_visitor/_create_statements.py` & `evadb-0.3.0/evadb/parser/lark_visitor/_create_statements.py`

 * *Files 4% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 # limitations under the License.
 
 from lark import Tree
 
 from evadb.catalog.catalog_type import ColumnType, NdArrayType, VectorStoreType
 from evadb.expression.tuple_value_expression import TupleValueExpression
 from evadb.parser.create_index_statement import CreateIndexStatement
-from evadb.parser.create_mat_view_statement import CreateMaterializedViewStatement
 from evadb.parser.create_statement import (
     ColConstraintInfo,
     ColumnDefinition,
     CreateTableStatement,
 )
 from evadb.parser.table_ref import TableRef
 from evadb.parser.types import ColumnConstraintEnum
@@ -228,40 +227,14 @@
         dimensions = self.dimension_helper(tree)
         return dimensions
 
     def length_dimension_list(self, tree):
         dimensions = self.dimension_helper(tree)
         return dimensions
 
-    # MATERIALIZED VIEW
-    def create_materialized_view(self, tree):
-        view_info = None
-        if_not_exists = False
-        query = None
-        uid_list = []
-
-        for child in tree.children:
-            if isinstance(child, Tree):
-                if child.data == "table_name":
-                    view_info = self.visit(child)
-                elif child.data == "if_not_exists":
-                    if_not_exists = True
-                elif child.data == "uid_list":
-                    uid_list = self.visit(child)
-                elif child.data == "simple_select":
-                    query = self.visit(child)
-
-        # When uid_list is empty, the column information is inferred from the subquery in the binder.
-        col_list = [
-            ColumnDefinition(uid.col_name, None, None, None) for uid in uid_list
-        ]
-        return CreateMaterializedViewStatement(
-            view_info, col_list, if_not_exists, query
-        )
-
     def vector_store_type(self, tree):
         vector_store_type = None
         token = tree.children[1]
 
         if str.upper(token) == "FAISS":
             vector_store_type = VectorStoreType.FAISS
         elif str.upper(token) == "QDRANT":
@@ -294,14 +267,13 @@
 
             # Traverse to the tuple value expression.
             while not isinstance(index_elem, TupleValueExpression):
                 index_elem = index_elem.children[0]
             index_elem = [index_elem]
 
         col_list = [
-            ColumnDefinition(tv_expr.col_name, None, None, None)
-            for tv_expr in index_elem
+            ColumnDefinition(tv_expr.name, None, None, None) for tv_expr in index_elem
         ]
 
         return CreateIndexStatement(
             index_name, table_ref, col_list, vector_store_type, udf_func
         )
```

### Comparing `evadb-0.2.9/evadb/parser/lark_visitor/_delete_statement.py` & `evadb-0.3.0/evadb/parser/lark_visitor/_delete_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/lark_visitor/_drop_statement.py` & `evadb-0.3.0/evadb/parser/lark_visitor/_drop_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/lark_visitor/_explain_statement.py` & `evadb-0.3.0/evadb/parser/lark_visitor/_explain_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/lark_visitor/_expressions.py` & `evadb-0.3.0/evadb/parser/lark_visitor/_expressions.py`

 * *Files 20% similar despite different names*

```diff
@@ -105,21 +105,52 @@
         for child in tree.children:
             if isinstance(child, Tree):
                 if child.data == "expression_or_default":
                     expression = self.visit(child)
                     expr_list.append(expression)
         return expr_list
 
+    def sample_params(self, tree):
+        sample_type = None
+        sample_freq = None
+        for child in tree.children:
+            if child.data == "sample_clause":
+                sample_freq = self.visit(child)
+            elif child.data == "sample_clause_with_type":
+                sample_type, sample_freq = self.visit(child)
+        return sample_type, sample_freq
+
     def sample_clause(self, tree):
         sample_list = self.visit_children(tree)
         assert len(sample_list) == 2
         return ConstantValueExpression(sample_list[1])
 
     def sample_clause_with_type(self, tree):
         sample_list = self.visit_children(tree)
         assert len(sample_list) == 3 or len(sample_list) == 2
         if len(sample_list) == 3:
             return ConstantValueExpression(sample_list[1]), ConstantValueExpression(
                 sample_list[2]
             )
         else:
             return ConstantValueExpression(sample_list[1]), ConstantValueExpression(1)
+
+    def chunk_params(self, tree):
+        chunk_params = self.visit_children(tree)
+        assert len(chunk_params) == 2 or len(chunk_params) == 4
+        if len(chunk_params) == 4:
+            return {
+                "chunk_size": ConstantValueExpression(chunk_params[1]),
+                "chunk_overlap": ConstantValueExpression(chunk_params[3]),
+            }
+
+        elif len(chunk_params) == 2:
+            if chunk_params[0] == "CHUNK_SIZE":
+                return {
+                    "chunk_size": ConstantValueExpression(chunk_params[1]),
+                }
+            elif chunk_params[0] == "CHUNK_OVERLAP":
+                return {
+                    "chunk_overlap": ConstantValueExpression(chunk_params[1]),
+                }
+            else:
+                assert f"incorrect keyword found {chunk_params[0]}"
```

### Comparing `evadb-0.2.9/evadb/parser/lark_visitor/_functions.py` & `evadb-0.3.0/evadb/parser/lark_visitor/_functions.py`

 * *Files 0% similar despite different names*

```diff
@@ -135,12 +135,12 @@
                     agg_func_name = self.visit(child).value
             elif isinstance(child, Token):
                 token = child.value
                 # Support for COUNT(*)
                 if token != "*":
                     agg_func_name = token
                 else:
-                    agg_func_arg = TupleValueExpression(col_name="id")
+                    agg_func_arg = TupleValueExpression(name="id")
 
         agg_func_type = self.get_aggregate_function_type(agg_func_name)
         agg_expr = AggregationExpression(agg_func_type, None, agg_func_arg)
         return agg_expr
```

### Comparing `evadb-0.2.9/evadb/parser/lark_visitor/_insert_statements.py` & `evadb-0.3.0/evadb/parser/lark_visitor/_insert_statements.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,15 +24,16 @@
 ##################################################################
 class Insert:
     def insert_statement(self, tree):
         table_ref = None
         column_list = []
         value_list = []
 
-        # print(tree.pretty())
+        # from pprint import pprint
+        # pprint(tree.pretty())
 
         for child in tree.children:
             if isinstance(child, Tree):
                 if child.data == "table_name":
                     table_name = self.visit(child)
                     table_ref = TableRef(table_name)
                 elif child.data == "uid_list":
```

### Comparing `evadb-0.2.9/evadb/parser/lark_visitor/_load_statement.py` & `evadb-0.3.0/evadb/parser/lark_visitor/_load_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/lark_visitor/_rename_statement.py` & `evadb-0.3.0/evadb/parser/lark_visitor/_rename_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/lark_visitor/_select_statement.py` & `evadb-0.3.0/evadb/parser/lark_visitor/_select_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/lark_visitor/_show_statements.py` & `evadb-0.3.0/evadb/parser/lark_visitor/_show_statements.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/lark_visitor/_table_sources.py` & `evadb-0.3.0/evadb/parser/lark_visitor/_table_sources.py`

 * *Files 3% similar despite different names*

```diff
@@ -26,15 +26,15 @@
 ##################################################################
 
 
 class TableSources:
     def select_elements(self, tree):
         kind = tree.children[0]
         if kind == "*":
-            select_list = [TupleValueExpression(col_name="*")]
+            select_list = [TupleValueExpression(name="*")]
         else:
             select_list = []
             for child in tree.children:
                 element = self.visit(child)
                 select_list.append(element)
         return select_list
 
@@ -43,15 +43,15 @@
 
     def table_source(self, tree):
         left_node = None
         join_nodes = []
 
         for child in tree.children:
             if isinstance(child, Tree):
-                if child.data == "table_source_item_with_sample":
+                if child.data == "table_source_item_with_param":
                     left_node = self.visit(child)
                     join_nodes = [left_node]
                 elif child.data.endswith("join"):
                     table = self.visit(child)
                     join_nodes.append(table)
 
         num_table_joins = len(join_nodes)
@@ -63,33 +63,38 @@
             for i in range(num_table_joins - 1):
                 join_nodes[i + 1].join_node.left = join_nodes[i]
 
             return join_nodes[-1]
         else:
             return join_nodes[0]
 
-    def table_source_item_with_sample(self, tree):
+    def table_source_item_with_param(self, tree):
         sample_freq = None
         sample_type = None
         alias = None
         table = None
+        chunk_params = {}
 
         for child in tree.children:
             if isinstance(child, Tree):
                 if child.data == "table_source_item":
                     table = self.visit(child)
-                elif child.data == "sample_clause":
-                    sample_freq = self.visit(child)
-                elif child.data == "sample_clause_with_type":
+                elif child.data == "sample_params":
                     sample_type, sample_freq = self.visit(child)
+                elif child.data == "chunk_params":
+                    chunk_params = self.visit(child)
                 elif child.data == "alias_clause":
                     alias = self.visit(child)
 
         return TableRef(
-            table=table, alias=alias, sample_freq=sample_freq, sample_type=sample_type
+            table=table,
+            alias=alias,
+            sample_freq=sample_freq,
+            sample_type=sample_type,
+            chunk_params=chunk_params,
         )
 
     def table_source_item(self, tree):
         return self.visit(tree.children[0])
 
     def query_specification(self, tree):
         target_list = None
@@ -156,15 +161,15 @@
     # Join
     def inner_join(self, tree):
         table = None
         join_predicate = None
 
         for child in tree.children:
             if isinstance(child, Tree):
-                if child.data == "table_source_item_with_sample":
+                if child.data == "table_source_item_with_param":
                     table = self.visit(child)
                 elif child.data.endswith("expression"):
                     join_predicate = self.visit(child)
 
         return TableRef(
             JoinNode(
                 None,
@@ -267,10 +272,10 @@
 
         for child in tree.children:
             if isinstance(child, Tree):
                 if child.data == "uid":
                     alias_name = self.visit(child)
                 elif child.data == "uid_list":
                     column_list = self.visit(child)
-                    column_list = [col.col_name for col in column_list]
+                    column_list = [col.name for col in column_list]
 
         return Alias(alias_name, column_list)
```

### Comparing `evadb-0.2.9/evadb/parser/load_statement.py` & `evadb-0.3.0/evadb/parser/load_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/parser.py` & `evadb-0.3.0/evadb/parser/parser.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/rename_statement.py` & `evadb-0.3.0/evadb/parser/rename_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/select_statement.py` & `evadb-0.3.0/evadb/parser/select_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/show_statement.py` & `evadb-0.3.0/evadb/parser/show_statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/statement.py` & `evadb-0.3.0/evadb/parser/statement.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/parser/table_ref.py` & `evadb-0.3.0/evadb/parser/table_ref.py`

 * *Files 4% similar despite different names*

```diff
@@ -157,20 +157,26 @@
         self,
         table: Union[TableInfo, TableValuedExpression, SelectStatement, JoinNode],
         alias: Alias = None,
         sample_freq: float = None,
         sample_type: str = None,
         get_audio: bool = False,
         get_video: bool = False,
+        chunk_params: dict = {},
     ):
+        # clean up so that we can support arbitrary new attributes
         self._ref_handle = table
         self._sample_freq = sample_freq
         self._sample_type = sample_type
         self._get_audio = get_audio
         self._get_video = get_video
+
+        # related to DOCUMENT tables
+        # chunk_size, chunk_overlap
+        self.chunk_params = chunk_params
         # Alias generation must happen after ref handle is initialized
         self.alias = alias or self.generate_alias()
 
     @property
     def sample_freq(self):
         return self._sample_freq
 
@@ -256,41 +262,52 @@
         # create alias for the table
         # TableInfo -> table_name.lower()
         # SelectStatement -> select
         if isinstance(self._ref_handle, TableInfo):
             return Alias(self._ref_handle.table_name.lower())
 
     def __str__(self):
+        parts = []
         if self.is_select():
-            table_ref_str = f"( {str(self._ref_handle)} ) AS {self.alias}"
+            parts.append(f"( {str(self._ref_handle)} ) AS {self.alias}")
         else:
-            table_ref_str = f"{str(self._ref_handle)}"
+            parts.append(str(self._ref_handle))
 
         if self.sample_freq is not None:
-            table_ref_str += f" {str(self.sample_freq)}"
+            parts.append(str(self.sample_freq))
         if self.sample_type is not None:
-            table_ref_str += f" {str(self.sample_type)}"
-        return table_ref_str
+            parts.append(str(self.sample_type))
+
+        if self.chunk_params is not None:
+            parts.append(
+                " ".join(
+                    [f"{key}: {value}" for key, value in self.chunk_params.items()]
+                )
+            )
+
+        return " ".join(parts)
 
     def __eq__(self, other):
         if not isinstance(other, TableRef):
             return False
         return (
             self._ref_handle == other._ref_handle
             and self.alias == other.alias
             and self.sample_freq == other.sample_freq
             and self.sample_type == other.sample_type
             and self.get_video == other.get_video
             and self.get_audio == other.get_audio
+            and self.chunk_params == other.chunk_params
         )
 
     def __hash__(self) -> int:
         return hash(
             (
                 self._ref_handle,
                 self.alias,
                 self.sample_freq,
                 self.sample_type,
                 self.get_video,
                 self.get_audio,
+                frozenset(self.chunk_params.items()),
             )
         )
```

### Comparing `evadb-0.2.9/evadb/parser/types.py` & `evadb-0.3.0/evadb/parser/types.py`

 * *Files 2% similar despite different names*

```diff
@@ -32,15 +32,14 @@
     CREATE  # noqa: F821
     RENAME  # noqa: F821
     DROP_OBJECT  # noqa: F821
     INSERT  # noqa: F821
     DELETE  # noqa: F821
     CREATE_UDF  # noqa: F821
     LOAD_DATA  # noqa: F821
-    CREATE_MATERIALIZED_VIEW  # noqa: F821
     SHOW  # noqa: F821
     EXPLAIN  # noqa: F821
     CREATE_INDEX  # noqa: F821
     # add other types
 
 
 class ParserOrderBySortType(EvaDBEnum):
```

### Comparing `evadb-0.2.9/evadb/plan_nodes/__init__.py` & `evadb-0.3.0/evadb/plan_nodes/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/abstract_join_plan.py` & `evadb-0.3.0/evadb/plan_nodes/abstract_join_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/abstract_plan.py` & `evadb-0.3.0/evadb/plan_nodes/abstract_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/abstract_scan_plan.py` & `evadb-0.3.0/evadb/plan_nodes/abstract_scan_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/apply_and_merge_plan.py` & `evadb-0.3.0/evadb/plan_nodes/apply_and_merge_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/create_index_plan.py` & `evadb-0.3.0/evadb/plan_nodes/create_index_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/create_mat_view_plan.py` & `evadb-0.3.0/evadb/plan_nodes/create_plan.py`

 * *Files 12% similar despite different names*

```diff
@@ -10,57 +10,62 @@
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 from typing import List
 
-from evadb.parser.create_statement import ColumnDefinition
+from evadb.catalog.models.column_catalog import ColumnCatalogEntry
 from evadb.parser.table_ref import TableInfo
 from evadb.plan_nodes.abstract_plan import AbstractPlan
 from evadb.plan_nodes.types import PlanOprType
 
 
-class CreateMaterializedViewPlan(AbstractPlan):
+class CreatePlan(AbstractPlan):
     """
-    This plan is used for storing information required for creating
-    materialized view.
+    This plan is used for storing information required for create table
+    operations.
     Arguments:
-        view {TableRef} -- table ref for view to be created in storage
-        col_list{List[ColumnDefinition]} -- column names in the view
-        if_not_exists {bool} -- Whether to override if there is existing view
+        video_ref {TableInfo} -- video ref for table to be created in storage
+        column_list {List[ColumnCatalogEntry]} -- Columns to be added
+        if_not_exists {bool} -- Whether to override if there is existing table
     """
 
     def __init__(
         self,
-        view: TableInfo,
-        columns: List[ColumnDefinition],
+        table_info: TableInfo,
+        column_list: List[ColumnCatalogEntry],
         if_not_exists: bool = False,
     ):
-        super().__init__(PlanOprType.CREATE_MATERIALIZED_VIEW)
-        self._view = view
-        self._columns = columns
+        super().__init__(PlanOprType.CREATE)
+        self._table_info = table_info
+        self._column_list = column_list
         self._if_not_exists = if_not_exists
 
     @property
-    def view(self):
-        return self._view
+    def table_info(self):
+        return self._table_info
 
     @property
     def if_not_exists(self):
         return self._if_not_exists
 
     @property
-    def columns(self):
-        return self._columns
+    def column_list(self):
+        return self._column_list
 
     def __str__(self):
-        return "CreateMaterializedViewPlan(view={}, \
-            columns={}, \
+        return "CreatePlan(table_ref={}, \
+            column_list={}, \
             if_not_exists={})".format(
-            self._view, self._columns, self._if_not_exists
+            self._table_info, self._column_list, self._if_not_exists
         )
 
     def __hash__(self) -> int:
         return hash(
-            (super().__hash__(), self.view, self.if_not_exists, tuple(self.columns))
+            (
+                super().__hash__(),
+                self.table_info,
+                self.if_not_exists,
+                tuple(self.column_list),
+            )
         )
```

### Comparing `evadb-0.2.9/evadb/plan_nodes/create_plan.py` & `evadb-0.3.0/test/udfs/test_fastrcnn_object_detector.py`

 * *Files 24% similar despite different names*

```diff
@@ -8,64 +8,50 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-from typing import List
+import os
+import unittest
 
-from evadb.catalog.models.column_catalog import ColumnCatalogEntry
-from evadb.parser.table_ref import TableInfo
-from evadb.plan_nodes.abstract_plan import AbstractPlan
-from evadb.plan_nodes.types import PlanOprType
-
-
-class CreatePlan(AbstractPlan):
-    """
-    This plan is used for storing information required for create table
-    operations.
-    Arguments:
-        video_ref {TableInfo} -- video ref for table to be created in storage
-        column_list {List[ColumnCatalogEntry]} -- Columns to be added
-        if_not_exists {bool} -- Whether to override if there is existing table
-    """
-
-    def __init__(
-        self,
-        table_info: TableInfo,
-        column_list: List[ColumnCatalogEntry],
-        if_not_exists: bool = False,
-    ):
-        super().__init__(PlanOprType.CREATE)
-        self._table_info = table_info
-        self._column_list = column_list
-        self._if_not_exists = if_not_exists
-
-    @property
-    def table_info(self):
-        return self._table_info
-
-    @property
-    def if_not_exists(self):
-        return self._if_not_exists
-
-    @property
-    def column_list(self):
-        return self._column_list
-
-    def __str__(self):
-        return "CreatePlan(table_ref={}, \
-            column_list={}, \
-            if_not_exists={})".format(
-            self._table_info, self._column_list, self._if_not_exists
-        )
-
-    def __hash__(self) -> int:
-        return hash(
-            (
-                super().__hash__(),
-                self.table_info,
-                self.if_not_exists,
-                tuple(self.column_list),
-            )
-        )
+import pandas as pd
+
+from evadb.models.storage.batch import Batch
+from evadb.utils.generic_utils import try_to_import_cv2
+
+NUM_FRAMES = 10
+
+
+class FastRCNNObjectDetectorTest(unittest.TestCase):
+    def __init__(self, *args, **kwargs):
+        super().__init__(*args, **kwargs)
+        self.base_path = os.path.dirname(os.path.abspath(__file__))
+
+    def _load_image(self, path):
+        try_to_import_cv2()
+        import cv2
+
+        img = cv2.imread(path)
+        return cv2.cvtColor(img, cv2.COLOR_BGR2RGB)
+
+    @unittest.skip("disable test due to model downloading time")
+    def test_should_return_batches_equivalent_to_number_of_frames(self):
+        from evadb.udfs.fastrcnn_object_detector import FastRCNNObjectDetector
+
+        frame_dog = {
+            "id": 1,
+            "data": self._load_image(os.path.join(self.base_path, "data", "dog.jpeg")),
+        }
+        frame_dog_cat = {
+            "id": 2,
+            "data": self._load_image(
+                os.path.join(self.base_path, "data", "dog_cat.jpg")
+            ),
+        }
+        frame_batch = Batch(pd.DataFrame([frame_dog, frame_dog_cat]))
+        detector = FastRCNNObjectDetector()
+        result = detector.classify(frame_batch)
+
+        self.assertEqual(["dog"], result[0].labels)
+        self.assertEqual(["cat", "dog"], result[1].labels)
```

### Comparing `evadb-0.2.9/evadb/plan_nodes/create_udf_plan.py` & `evadb-0.3.0/evadb/plan_nodes/create_udf_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/delete_plan.py` & `evadb-0.3.0/evadb/plan_nodes/delete_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/drop_object_plan.py` & `evadb-0.3.0/evadb/plan_nodes/drop_object_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/exchange_plan.py` & `evadb-0.3.0/evadb/plan_nodes/exchange_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/explain_plan.py` & `evadb-0.3.0/evadb/plan_nodes/explain_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/function_scan_plan.py` & `evadb-0.3.0/evadb/plan_nodes/function_scan_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/groupby_plan.py` & `evadb-0.3.0/evadb/plan_nodes/groupby_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/hash_join_build_plan.py` & `evadb-0.3.0/evadb/plan_nodes/hash_join_build_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/hash_join_probe_plan.py` & `evadb-0.3.0/evadb/plan_nodes/hash_join_probe_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/insert_plan.py` & `evadb-0.3.0/evadb/plan_nodes/insert_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/lateral_join_plan.py` & `evadb-0.3.0/evadb/plan_nodes/lateral_join_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/limit_plan.py` & `evadb-0.3.0/evadb/plan_nodes/limit_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/load_data_plan.py` & `evadb-0.3.0/evadb/plan_nodes/load_data_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/nested_loop_join_plan.py` & `evadb-0.3.0/evadb/plan_nodes/nested_loop_join_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/orderby_plan.py` & `evadb-0.3.0/evadb/plan_nodes/orderby_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/pp_plan.py` & `evadb-0.3.0/evadb/plan_nodes/pp_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/predicate_plan.py` & `evadb-0.3.0/evadb/plan_nodes/predicate_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/project_plan.py` & `evadb-0.3.0/evadb/plan_nodes/project_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/rename_plan.py` & `evadb-0.3.0/evadb/plan_nodes/rename_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/sample_plan.py` & `evadb-0.3.0/evadb/plan_nodes/sample_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/seq_scan_plan.py` & `evadb-0.3.0/evadb/plan_nodes/seq_scan_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/show_info_plan.py` & `evadb-0.3.0/evadb/plan_nodes/show_info_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/storage_plan.py` & `evadb-0.3.0/evadb/plan_nodes/storage_plan.py`

 * *Files 11% similar despite different names*

```diff
@@ -45,27 +45,29 @@
         limit: int = None,
         total_shards: int = 0,
         curr_shard: int = 0,
         predicate: AbstractExpression = None,
         sampling_rate: int = None,
         batch_mem_size: int = 30000000,
         sampling_type: str = None,
+        chunk_params: dict = {},
     ):
         super().__init__(PlanOprType.STORAGE_PLAN)
         self._table = table
         self._table_ref = table_ref
         self._batch_mem_size = batch_mem_size
         self._skip_frames = skip_frames
         self._offset = offset
         self._limit = limit
         self._total_shards = total_shards
         self._curr_shard = curr_shard
         self._predicate = predicate
         self._sampling_rate = sampling_rate
         self._sampling_type = sampling_type
+        self.chunk_params = chunk_params
 
     @property
     def table(self):
         return self._table
 
     @property
     def table_ref(self):
@@ -143,9 +145,10 @@
                 self.offset,
                 self.limit,
                 self.total_shards,
                 self.curr_shard,
                 self.predicate,
                 self.sampling_rate,
                 self.sampling_type,
+                frozenset(self.chunk_params.items()),
             )
         )
```

### Comparing `evadb-0.2.9/evadb/plan_nodes/types.py` & `evadb-0.3.0/evadb/plan_nodes/types.py`

 * *Files 6% similar despite different names*

```diff
@@ -34,15 +34,14 @@
     LIMIT = auto()
     SAMPLE = auto()
     FUNCTION_SCAN = auto()
     NESTED_LOOP_JOIN = auto()
     HASH_JOIN = auto()
     LATERAL_JOIN = auto()
     HASH_BUILD = auto()
-    CREATE_MATERIALIZED_VIEW = auto()
     EXCHANGE = auto()
     PREDICATE_FILTER = auto()
     PROJECT = auto()
     SHOW_INFO = auto()
     EXPLAIN = auto()
     CREATE_INDEX = auto()
     APPLY_AND_MERGE = auto()
```

### Comparing `evadb-0.2.9/evadb/plan_nodes/union_plan.py` & `evadb-0.3.0/evadb/plan_nodes/union_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/plan_nodes/vector_index_scan_plan.py` & `evadb-0.3.0/evadb/plan_nodes/vector_index_scan_plan.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/readers/__init__.py` & `evadb-0.3.0/evadb/readers/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/readers/abstract_reader.py` & `evadb-0.3.0/evadb/readers/abstract_reader.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/readers/csv_reader.py` & `evadb-0.3.0/evadb/readers/csv_reader.py`

 * *Files 2% similar despite different names*

```diff
@@ -46,20 +46,18 @@
         logger.info("Reading CSV frames")
 
         # TODO: Need to add strong sanity checks on the columns.
 
         # Read the csv in chunks, and only keep the columns we need.
         # Ignore _row_id that we don't need to take care of.
         col_list_names = [
-            col.col_name
-            for col in self._column_list
-            if col.col_name != IDENTIFIER_COLUMN
+            col.name for col in self._column_list if col.name != IDENTIFIER_COLUMN
         ]
 
-        col_map = {col.col_name: col for col in self._column_list}
+        col_map = {col.name: col for col in self._column_list}
         for chunk in pd.read_csv(self.file_url, chunksize=512, usecols=col_list_names):
             # apply the required conversions
             for col in chunk.columns:
                 # TODO: Is there a better way to do this?
                 if (
                     isinstance(chunk[col].iloc[0], str)
                     and col_map[col].col_object.type.name == "NDARRAY"
```

### Comparing `evadb-0.2.9/evadb/readers/decord_reader.py` & `evadb-0.3.0/evadb/readers/decord_reader.py`

 * *Files 4% similar despite different names*

```diff
@@ -17,28 +17,17 @@
 import numpy as np
 
 from evadb.catalog.catalog_type import VideoColumnName
 from evadb.constants import AUDIORATE, IFRAMES
 from evadb.expression.abstract_expression import AbstractExpression
 from evadb.expression.expression_utils import extract_range_list_from_predicate
 from evadb.readers.abstract_reader import AbstractReader
+from evadb.utils.generic_utils import try_to_import_decord
 from evadb.utils.logging_manager import logger
 
-# Lazy import to avoid torch init failures
-_decord = None
-
-
-def _lazy_import_decord():
-    global _decord
-    if _decord is None:
-        import decord
-
-        _decord = decord
-    return _decord
-
 
 class DecordReader(AbstractReader):
     def __init__(
         self,
         *args,
         predicate: AbstractExpression = None,
         sampling_rate: int = None,
@@ -102,15 +91,17 @@
                 # align begin with sampling rate
                 if begin % self._sampling_rate:
                     begin += self._sampling_rate - (begin % self._sampling_rate)
                 for frame_id in range(begin, end + 1, self._sampling_rate):
                     yield self._get_frame(frame_id)
 
     def initialize_reader(self):
-        decord = _lazy_import_decord()
+        try_to_import_decord()
+        import decord
+
         if self._read_audio:
             assert (
                 self._sampling_type != IFRAMES
             ), "Cannot use IFRAMES with audio streams"
             sample_rate = 16000
             if self._sampling_type == AUDIORATE and self._sampling_rate != 1:
                 sample_rate = self._sampling_rate
```

### Comparing `evadb-0.2.9/evadb/readers/document/__init__.py` & `evadb-0.3.0/evadb/readers/document/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/readers/document/registry.py` & `evadb-0.3.0/evadb/readers/document/registry.py`

 * *Files 14% similar despite different names*

```diff
@@ -9,55 +9,63 @@
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 
+from evadb.utils.generic_utils import try_to_import_langchain
+
+SUPPORTED_TYPES = [
+    ".csv",
+    ".doc",
+    ".docx",
+    ".enex",
+    ".eml",
+    ".epub",
+    ".html",
+    ".md",
+    ".pdf",
+    ".ppt",
+    ".pptx",
+    ".txt",
+]
+
 
 def _lazy_import_loader():
-    import_err_msg = "`langchain` package not found, please run `pip install langchain`"
-    try:
-        from langchain.document_loaders import (
-            EverNoteLoader,
-            PDFMinerLoader,
-            TextLoader,
-            UnstructuredEmailLoader,
-            UnstructuredEPubLoader,
-            UnstructuredHTMLLoader,
-            UnstructuredMarkdownLoader,
-            UnstructuredPowerPointLoader,
-            UnstructuredWordDocumentLoader,
-        )
-    except ImportError:
-        raise ImportError(import_err_msg)
+    try_to_import_langchain()
+    from langchain.document_loaders import (
+        CSVLoader,
+        EverNoteLoader,
+        PDFMinerLoader,
+        TextLoader,
+        UnstructuredEmailLoader,
+        UnstructuredEPubLoader,
+        UnstructuredHTMLLoader,
+        UnstructuredMarkdownLoader,
+        UnstructuredPowerPointLoader,
+        UnstructuredWordDocumentLoader,
+    )
 
     LOADER_MAPPING = {
         ".doc": (UnstructuredWordDocumentLoader, {}),
         ".docx": (UnstructuredWordDocumentLoader, {}),
         ".enex": (EverNoteLoader, {}),
         ".eml": (UnstructuredEmailLoader, {}),
         ".epub": (UnstructuredEPubLoader, {}),
         ".html": (UnstructuredHTMLLoader, {}),
+        ".csv": (CSVLoader, {}),
         ".md": (UnstructuredMarkdownLoader, {}),
         ".pdf": (PDFMinerLoader, {}),
         ".ppt": (UnstructuredPowerPointLoader, {}),
         ".pptx": (UnstructuredPowerPointLoader, {}),
         ".txt": (TextLoader, {"encoding": "utf8"}),
         # Add more mappings for other file extensions and loaders as needed
     }
     return LOADER_MAPPING
 
 
-SUPPORTED_TYPES = [
-    ".doc",
-    ".docx",
-    ".enex",
-    ".eml",
-    ".epub",
-    ".html",
-    ".md",
-    ".pdf",
-    ".ppt",
-    ".pptx",
-    ".txt",
-]
+def _lazy_import_text_splitter():
+    try_to_import_langchain()
+    from langchain.text_splitter import RecursiveCharacterTextSplitter
+
+    return RecursiveCharacterTextSplitter
```

### Comparing `evadb-0.2.9/evadb/readers/image/__init__.py` & `evadb-0.3.0/evadb/readers/image/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/readers/image/opencv_image_reader.py` & `evadb-0.3.0/evadb/readers/image/opencv_image_reader.py`

 * *Files 11% similar despite different names*

```diff
@@ -10,21 +10,23 @@
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 from typing import Dict, Iterator
 
-import cv2
-
 from evadb.readers.abstract_reader import AbstractReader
+from evadb.utils.generic_utils import try_to_import_cv2
 
 
 class CVImageReader(AbstractReader):
     def __init__(self, *args, **kwargs):
         super().__init__(*args, **kwargs)
 
     def _read(self) -> Iterator[Dict]:
+        try_to_import_cv2()
+        import cv2
+
         im_bgr = cv2.imread(str(self.file_url))
         im_rgb = cv2.cvtColor(im_bgr, cv2.COLOR_BGR2RGB)
         assert im_rgb is not None, f"Failed to read image file {self.file_url}"
         yield {"data": im_rgb}
```

### Comparing `evadb-0.2.9/evadb/readers/pdf_reader.py` & `evadb-0.3.0/evadb/readers/pdf_reader.py`

 * *Files 5% similar despite different names*

```diff
@@ -11,26 +11,27 @@
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 from typing import Dict, Iterator
 
 from evadb.readers.abstract_reader import AbstractReader
+from evadb.utils.generic_utils import try_to_import_fitz
 
 
 class PDFReader(AbstractReader):
     def __init__(self, *args, **kwargs):
         """
         Reads a PDF file and yields frame data.
         Args:
             column_list: list of columns (TupleValueExpression)
             to read from the PDF file
         """
-
         super().__init__(*args, **kwargs)
+        try_to_import_fitz()
 
     def _read(self) -> Iterator[Dict]:
         import fitz
 
         doc = fitz.open(self.file_url)
 
         # PAGE ID, PARAGRAPH ID, STRING
```

### Comparing `evadb-0.2.9/evadb/server/__init__.py` & `evadb-0.3.0/evadb/server/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/server/command_handler.py` & `evadb-0.3.0/evadb/server/command_handler.py`

 * *Files 15% similar despite different names*

```diff
@@ -8,15 +8,14 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-import asyncio
 from typing import Iterator, Optional
 
 from evadb.binder.statement_binder import StatementBinder
 from evadb.binder.statement_binder_context import StatementBinderContext
 from evadb.database import EvaDBDatabase
 from evadb.executor.plan_executor import PlanExecutor
 from evadb.models.server.response import Response, ResponseStatus
@@ -25,39 +24,60 @@
 from evadb.optimizer.statement_to_opr_converter import StatementToPlanConverter
 from evadb.parser.parser import Parser
 from evadb.utils.logging_manager import logger
 from evadb.utils.stats import Timer
 
 
 def execute_query(
-    evadb: EvaDBDatabase, query, report_time: bool = False, **kwargs
+    evadb: EvaDBDatabase,
+    query,
+    report_time: bool = False,
+    do_not_raise_exceptions: bool = False,
+    do_not_print_exceptions: bool = False,
+    **kwargs
 ) -> Iterator[Batch]:
     """
     Execute the query and return a result generator.
     """
     query_compile_time = Timer()
     plan_generator = kwargs.pop("plan_generator", PlanGenerator(evadb))
     with query_compile_time:
         stmt = Parser().parse(query)[0]
         StatementBinder(StatementBinderContext(evadb.catalog)).bind(stmt)
         l_plan = StatementToPlanConverter().visit(stmt)
-        p_plan = asyncio.run(plan_generator.build(l_plan))
-        output = PlanExecutor(evadb, p_plan).execute_plan()
+        p_plan = plan_generator.build(l_plan)
+        output = PlanExecutor(evadb, p_plan).execute_plan(
+            do_not_raise_exceptions, do_not_print_exceptions
+        )
+
+    if report_time is True:
+        query_compile_time.log_elapsed_time("Query Compile Time")
 
-    query_compile_time.log_elapsed_time("Query Compile Time")
     return output
 
 
 def execute_query_fetch_all(
-    evadb: EvaDBDatabase, query=None, **kwargs
+    evadb: EvaDBDatabase,
+    query=None,
+    report_time: bool = False,
+    do_not_raise_exceptions: bool = False,
+    do_not_print_exceptions: bool = False,
+    **kwargs
 ) -> Optional[Batch]:
     """
     Execute the query and fetch all results into one Batch object.
     """
-    output = execute_query(evadb, query, report_time=True, **kwargs)
+    output = execute_query(
+        evadb,
+        query,
+        report_time,
+        do_not_raise_exceptions,
+        do_not_print_exceptions,
+        **kwargs
+    )
     if output:
         batch_list = list(output)
         return Batch.concat(batch_list, copy=False)
 
 
 async def handle_request(evadb: EvaDBDatabase, client_writer, request_message):
     """
```

### Comparing `evadb-0.2.9/evadb/server/interpreter.py` & `evadb-0.3.0/evadb/server/interpreter.py`

 * *Files 1% similar despite different names*

```diff
@@ -53,15 +53,17 @@
 
 
 async def read_from_client_and_send_to_server(
     stdin_reader: StreamReader, writer: StreamWriter, server_reader: StreamReader
 ):
     VERSION = VERSION_DICT["VERSION"]
     intro = f"evadb (v{VERSION})\nType 'EXIT;' to exit the client \n"
-    print(intro, flush=True)
+    from pprint import pprint
+
+    pprint(intro, flush=True)
 
     prompt = "evadb=#"
 
     # The EvaDBDatabase object is not passed from the command line client.
     # The concept is to always send a SQL query to the server, which is responsible for
     # executing it and returning the results. However, in the Pythonic interface, we
     # adopt a serverless approach and don't rely on the EvaDBDatabase object.
```

### Comparing `evadb-0.2.9/evadb/server/server.py` & `evadb-0.3.0/evadb/server/server.py`

 * *Files 5% similar despite different names*

```diff
@@ -37,15 +37,17 @@
         """
         Start the server
         Server objects are asynchronous context managers.
 
         hostname: hostname of the server
         port: port of the server
         """
-        print(f"EvaDB server started at host {host} and port {port}")
+        from pprint import pprint
+
+        pprint(f"EvaDB server started at host {host} and port {port}")
         self._evadb = init_evadb_instance(db_dir, host, port, custom_db_uri)
 
         self._server = await asyncio.start_server(self.accept_client, host, port)
 
         # load built-in udfs
         mode = self._evadb.config.get_value("core", "mode")
         init_builtin_udfs(self._evadb, mode=mode)
```

### Comparing `evadb-0.2.9/evadb/storage/__init__.py` & `evadb-0.3.0/evadb/storage/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/storage/abstract_media_storage_engine.py` & `evadb-0.3.0/evadb/storage/abstract_media_storage_engine.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/storage/abstract_storage_engine.py` & `evadb-0.3.0/evadb/storage/abstract_storage_engine.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/storage/document_storage_engine.py` & `evadb-0.3.0/evadb/storage/image_storage_engine.py`

 * *Files 11% similar despite different names*

```diff
@@ -14,26 +14,26 @@
 # limitations under the License.
 from pathlib import Path
 from typing import Iterator
 
 from evadb.catalog.models.table_catalog import TableCatalogEntry
 from evadb.database import EvaDBDatabase
 from evadb.models.storage.batch import Batch
-from evadb.readers.document.document_reader import DocumentReader
+from evadb.readers.image.opencv_image_reader import CVImageReader
 from evadb.storage.abstract_media_storage_engine import AbstractMediaStorageEngine
 
 
-class DocumentStorageEngine(AbstractMediaStorageEngine):
+class ImageStorageEngine(AbstractMediaStorageEngine):
     def __init__(self, db: EvaDBDatabase):
         super().__init__(db)
 
     def read(self, table: TableCatalogEntry) -> Iterator[Batch]:
-        for doc_files in self._rdb_handler.read(self._get_metadata_table(table), 12):
-            for _, (row_id, file_name) in doc_files.iterrows():
+        for image_files in self._rdb_handler.read(self._get_metadata_table(table), 12):
+            for _, (row_id, file_name) in image_files.iterrows():
                 system_file_name = self._xform_file_url_to_file_name(file_name)
-                doc_file = Path(table.file_url) / system_file_name
+                image_file = Path(table.file_url) / system_file_name
                 # setting batch_mem_size = 1, we need fix it
-                reader = DocumentReader(str(doc_file), batch_mem_size=1)
+                reader = CVImageReader(str(image_file), batch_mem_size=1)
                 for batch in reader.read():
                     batch.frames[table.columns[0].name] = row_id
                     batch.frames[table.columns[1].name] = str(file_name)
                     yield batch
```

### Comparing `evadb-0.2.9/evadb/storage/image_storage_engine.py` & `evadb-0.3.0/evadb/storage/pdf_storage_engine.py`

 * *Files 12% similar despite different names*

```diff
@@ -14,26 +14,26 @@
 # limitations under the License.
 from pathlib import Path
 from typing import Iterator
 
 from evadb.catalog.models.table_catalog import TableCatalogEntry
 from evadb.database import EvaDBDatabase
 from evadb.models.storage.batch import Batch
-from evadb.readers.image.opencv_image_reader import CVImageReader
+from evadb.readers.pdf_reader import PDFReader
 from evadb.storage.abstract_media_storage_engine import AbstractMediaStorageEngine
 
 
-class ImageStorageEngine(AbstractMediaStorageEngine):
+class PDFStorageEngine(AbstractMediaStorageEngine):
     def __init__(self, db: EvaDBDatabase):
         super().__init__(db)
 
     def read(self, table: TableCatalogEntry) -> Iterator[Batch]:
         for image_files in self._rdb_handler.read(self._get_metadata_table(table), 12):
             for _, (row_id, file_name) in image_files.iterrows():
                 system_file_name = self._xform_file_url_to_file_name(file_name)
                 image_file = Path(table.file_url) / system_file_name
                 # setting batch_mem_size = 1, we need fix it
-                reader = CVImageReader(str(image_file), batch_mem_size=1)
+                reader = PDFReader(str(image_file), batch_mem_size=1)
                 for batch in reader.read():
                     batch.frames[table.columns[0].name] = row_id
                     batch.frames[table.columns[1].name] = str(file_name)
                     yield batch
```

### Comparing `evadb-0.2.9/evadb/storage/pdf_storage_engine.py` & `evadb-0.3.0/evadb/udfs/decorators/utils.py`

 * *Files 26% similar despite different names*

```diff
@@ -8,32 +8,46 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-from pathlib import Path
-from typing import Iterator
+from typing import List, Type
 
-from evadb.catalog.models.table_catalog import TableCatalogEntry
-from evadb.database import EvaDBDatabase
-from evadb.models.storage.batch import Batch
-from evadb.readers.pdf_reader import PDFReader
-from evadb.storage.abstract_media_storage_engine import AbstractMediaStorageEngine
-
-
-class PDFStorageEngine(AbstractMediaStorageEngine):
-    def __init__(self, db: EvaDBDatabase):
-        super().__init__(db)
-
-    def read(self, table: TableCatalogEntry) -> Iterator[Batch]:
-        for image_files in self._rdb_handler.read(self._get_metadata_table(table), 12):
-            for _, (row_id, file_name) in image_files.iterrows():
-                system_file_name = self._xform_file_url_to_file_name(file_name)
-                image_file = Path(table.file_url) / system_file_name
-                # setting batch_mem_size = 1, we need fix it
-                reader = PDFReader(str(image_file), batch_mem_size=1)
-                for batch in reader.read():
-                    batch.frames[table.columns[0].name] = row_id
-                    batch.frames[table.columns[1].name] = str(file_name)
-                    yield batch
+from evadb.catalog.models.udf_io_catalog import UdfIOCatalogEntry
+from evadb.udfs.abstract.abstract_udf import AbstractUDF
+
+
+def load_io_from_udf_decorators(
+    udf: Type[AbstractUDF], is_input=False
+) -> List[Type[UdfIOCatalogEntry]]:
+    """Load the inputs/outputs from the udf decorators and return a list of UdfIOCatalogEntry objects
+
+    Args:
+        udf (Object): UDF object
+        is_input (bool, optional): True if inputs are to be loaded. Defaults to False.
+
+    Returns:
+        Type[UdfIOCatalogEntry]: UdfIOCatalogEntry object created from the input decorator in setup
+    """
+    tag_key = "input" if is_input else "output"
+    io_signature = None
+    if hasattr(udf.forward, "tags") and tag_key in udf.forward.tags:
+        io_signature = udf.forward.tags[tag_key]
+    else:
+        # Attempt to populate from the parent class and stop at the first parent class
+        # where the required tags are found.
+        for base_class in udf.__bases__:
+            if hasattr(base_class, "forward") and hasattr(base_class.forward, "tags"):
+                if tag_key in base_class.forward.tags:
+                    io_signature = base_class.forward.tags[tag_key]
+                    break
+
+    assert (
+        io_signature is not None
+    ), f"Cannot infer io signature from the decorator for {udf}."
+
+    result_list = []
+    for io in io_signature:
+        result_list.extend(io.generate_catalog_entries(is_input))
+    return result_list
```

### Comparing `evadb-0.2.9/evadb/storage/sqlite_storage_engine.py` & `evadb-0.3.0/evadb/storage/sqlite_storage_engine.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/storage/storage_engine.py` & `evadb-0.3.0/evadb/storage/storage_engine.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/storage/video_storage_engine.py` & `evadb-0.3.0/evadb/storage/video_storage_engine.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/third_party/__init__.py` & `evadb-0.3.0/evadb/third_party/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/third_party/huggingface/__init__.py` & `evadb-0.3.0/evadb/third_party/huggingface/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/third_party/huggingface/binder.py` & `evadb-0.3.0/evadb/third_party/huggingface/binder.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/third_party/huggingface/create.py` & `evadb-0.3.0/evadb/third_party/huggingface/create.py`

 * *Files 9% similar despite different names*

```diff
@@ -11,27 +11,26 @@
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 from typing import Dict, List, Type, Union
 
 import numpy as np
-from PIL import Image, ImageDraw
-from transformers import pipeline
 
 from evadb.catalog.catalog_type import ColumnType, NdArrayType
 from evadb.catalog.models.udf_io_catalog import UdfIOCatalogEntry
 from evadb.catalog.models.udf_metadata_catalog import UdfMetadataCatalogEntry
 from evadb.third_party.huggingface.model import (
     ASRHFModel,
     AudioHFModel,
     HFInputTypes,
     ImageHFModel,
     TextHFModel,
 )
+from evadb.utils.generic_utils import try_to_import_transformers
 
 """
 We currently support the following tasks from HuggingFace.
 Each task is mapped to the type of input it expects.
 """
 INPUT_TYPE_FOR_SUPPORTED_TASKS = {
     "audio-classification": HFInputTypes.AUDIO,
@@ -67,14 +66,16 @@
 
 
 def sample_text():
     return "My name is Sarah and I live in London"
 
 
 def sample_image():
+    from PIL import Image, ImageDraw
+
     width, height = 224, 224
     image = Image.new("RGB", (width, height), "white")
     draw = ImageDraw.Draw(image)
 
     circle_radius = min(width, height) // 4
     circle_center = (width // 2, height // 2)
     circle_bbox = (
@@ -111,14 +112,17 @@
     assert "task" in pipeline_args, "Task Not Found In Model Definition"
     task = pipeline_args["task"]
     assert (
         task in INPUT_TYPE_FOR_SUPPORTED_TASKS
     ), f"Task {task} not supported in EvaDB currently"
 
     # Construct the pipeline
+    try_to_import_transformers()
+    from transformers import pipeline
+
     pipe = pipeline(**pipeline_args)
 
     # Run the pipeline through a dummy input to get a sample output
     input_type = INPUT_TYPE_FOR_SUPPORTED_TASKS[task]
     model_input = gen_sample_input(input_type)
     model_output = pipe(model_input)
```

### Comparing `evadb-0.2.9/evadb/third_party/huggingface/model.py` & `evadb-0.3.0/evadb/third_party/huggingface/model.py`

 * *Files 7% similar despite different names*

```diff
@@ -10,20 +10,18 @@
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 from typing import Any
 
-import decord
 import numpy as np
-from PIL import Image
 
 from evadb.udfs.abstract.hf_abstract_udf import AbstractHFUdf
-from evadb.utils.generic_utils import EvaDBEnum
+from evadb.utils.generic_utils import EvaDBEnum, try_to_import_decord
 
 
 class HFInputTypes(EvaDBEnum):
     TEXT  # noqa: F821
     IMAGE  # noqa: F821
     AUDIO  # noqa: F821
     VIDEO  # noqa: F821
@@ -43,14 +41,16 @@
     """
     Base Model for all HF Models that take in images as input
     """
 
     def input_formatter(self, inputs: Any):
         frames_list = inputs.values.tolist()
         frames = np.vstack(frames_list)
+        from PIL import Image
+
         images = [Image.fromarray(row) for row in frames]
         return images
 
 
 class AudioHFModel(AbstractHFUdf):
     """
     Base Model for all HF Models that take in audio as input
@@ -60,14 +60,18 @@
         # if audio is being passed using decord reader, we already have the audio as numpy arrays,
         # merge into single array and return
         if inputs.columns.str.contains("audio").any():
             return np.concatenate(inputs.iloc[:, 0].values)
         # else expect that the user passed an array of video file paths, get audio as numpy array
         audio = []
         files = inputs.iloc[:, 0].tolist()
+
+        try_to_import_decord()
+        import decord
+
         for file in files:
             # must read audio at 16000Hz because most models were trained at this sampling rate
             reader = decord.AudioReader(file, mono=True, sample_rate=16000)
             audio.append(reader[0:].asnumpy()[0])
         return audio
```

### Comparing `evadb-0.2.9/evadb/third_party/vector_stores/__init__.py` & `evadb-0.3.0/evadb/third_party/vector_stores/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/third_party/vector_stores/faiss.py` & `evadb-0.3.0/evadb/third_party/vector_stores/faiss.py`

 * *Files 20% similar despite different names*

```diff
@@ -19,62 +19,51 @@
 
 from evadb.third_party.vector_stores.types import (
     FeaturePayload,
     VectorIndexQuery,
     VectorIndexQueryResult,
     VectorStore,
 )
-
-_faiss = None
-
-
-def _lazy_load_faiss():
-    global _faiss
-    if _faiss is None:
-        import_err_msg = "`faiss` package not found, please visit https://github.com/facebookresearch/faiss/wiki/Installing-Faiss for instructions"
-        try:
-            import faiss  # noqa: F401
-
-            _faiss = faiss
-        except ImportError:
-            raise ImportError(import_err_msg)
-    return _faiss
-
+from evadb.utils.generic_utils import try_to_import_faiss
 
 required_params = ["index_path"]
 
 
 class FaissVectorStore(VectorStore):
     def __init__(self, index_name: str, index_path: str) -> None:
         # Reference to Faiss documentation.
         # IDMap: https://github.com/facebookresearch/faiss/wiki/Pre--and-post-processing#faiss-id-mapping
         # Other index types: https://github.com/facebookresearch/faiss/wiki/The-index-factory
-        self.faiss = _lazy_load_faiss()
+        try_to_import_faiss()
         self._index_name = index_name
         self._index_path = index_path
         self._index = None
 
     def create(self, vector_dim: int):
-        self._index = self.faiss.IndexIDMap2(self.faiss.IndexHNSWFlat(vector_dim, 32))
+        import faiss
+
+        self._index = faiss.IndexIDMap2(faiss.IndexHNSWFlat(vector_dim, 32))
 
     def add(self, payload: List[FeaturePayload]):
         assert self._index is not None, "Please create an index before adding features."
         for row in payload:
             embedding = np.array(row.embedding, dtype="float32")
             if len(embedding.shape) != 2:
                 embedding = embedding.reshape(1, -1)
             self._index.add_with_ids(embedding, np.array([row.id]))
 
     def persist(self):
         assert self._index is not None, "Please create an index before calling persist."
-        faiss = _lazy_load_faiss()
+        import faiss
+
         faiss.write_index(self._index, self._index_path)
 
     def query(self, query: VectorIndexQuery) -> VectorIndexQueryResult:
-        faiss = _lazy_load_faiss()
+        import faiss
+
         if self._index is None:
             self._index = faiss.read_index(self._index_path)
         assert self._index is not None, "Cannot query as index does not exists."
         embedding = np.array(query.embedding, dtype="float32")
         if len(embedding.shape) != 2:
             embedding = embedding.reshape(1, -1)
```

### Comparing `evadb-0.2.9/evadb/third_party/vector_stores/qdrant.py` & `evadb-0.3.0/evadb/third_party/vector_stores/qdrant.py`

 * *Files 14% similar despite different names*

```diff
@@ -16,30 +16,26 @@
 
 from evadb.third_party.vector_stores.types import (
     FeaturePayload,
     VectorIndexQuery,
     VectorIndexQueryResult,
     VectorStore,
 )
+from evadb.utils.generic_utils import try_to_import_qdrant_client
 
 _qdrant_client_instance = None
 
 required_params = ["index_db"]
 
 
 def get_qdrant_client(path: str):
     global _qdrant_client_instance
     if _qdrant_client_instance is None:
-        import_err_msg = (
-            "`qdrant-client` package not found, please run `pip install qdrant-client`"
-        )
-        try:
-            import qdrant_client  # noqa: F401
-        except ImportError:
-            raise ImportError(import_err_msg)
+        try_to_import_qdrant_client()
+        import qdrant_client  # noqa: F401
 
         # creating a local mode client
         # modify to support server modes
         # https://github.com/qdrant/qdrant-client
         _qdrant_client_instance = qdrant_client.QdrantClient(path=path)
     return _qdrant_client_instance
```

### Comparing `evadb-0.2.9/evadb/third_party/vector_stores/types.py` & `evadb-0.3.0/evadb/third_party/vector_stores/types.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/third_party/vector_stores/utils.py` & `evadb-0.3.0/evadb/third_party/vector_stores/utils.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/__init__.py` & `evadb-0.3.0/evadb/udfs/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/abstract/__init__.py` & `evadb-0.3.0/evadb/udfs/abstract/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/abstract/abstract_udf.py` & `evadb-0.3.0/evadb/udfs/abstract/abstract_udf.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/abstract/hf_abstract_udf.py` & `evadb-0.3.0/evadb/udfs/abstract/hf_abstract_udf.py`

 * *Files 10% similar despite different names*

```diff
@@ -11,19 +11,19 @@
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 from typing import Any
 
 import pandas as pd
-from transformers import pipeline
 
 from evadb.catalog.models.udf_catalog import UdfCatalogEntry
 from evadb.udfs.abstract.abstract_udf import AbstractUDF
 from evadb.udfs.gpu_compatible import GPUCompatible
+from evadb.utils.generic_utils import try_to_import_transformers
 
 
 class AbstractHFUdf(AbstractUDF, GPUCompatible):
     """
     An abstract class for all HuggingFace models.
 
     This is implemented using the pipeline API from HuggingFace. pipeline is an
@@ -46,14 +46,17 @@
         pipeline_args = self.default_pipeline_args
         for entry in udf_obj.metadata:
             if entry.value.isnumeric():
                 pipeline_args[entry.key] = int(entry.value)
             else:
                 pipeline_args[entry.key] = entry.value
         self.pipeline_args = pipeline_args
+        try_to_import_transformers()
+        from transformers import pipeline
+
         self.hf_udf_obj = pipeline(**pipeline_args, device=device)
 
     def setup(self, *args, **kwargs) -> None:
         super().setup(*args, **kwargs)
 
     @property
     def default_pipeline_args(self) -> dict:
@@ -95,9 +98,12 @@
     def forward(self, inputs, *args, **kwargs) -> pd.DataFrame:
         hf_input = self.input_formatter(inputs)
         hf_output = self.hf_udf_obj(hf_input, *args, **kwargs)
         evadb_output = self.output_formatter(hf_output)
         return evadb_output
 
     def to_device(self, device: str) -> GPUCompatible:
+        try_to_import_transformers()
+        from transformers import pipeline
+
         self.hf_udf_obj = pipeline(**self.pipeline_args, device=device)
         return self
```

### Comparing `evadb-0.2.9/evadb/udfs/abstract/pytorch_abstract_udf.py` & `evadb-0.3.0/evadb/udfs/abstract/pytorch_abstract_udf.py`

 * *Files 6% similar despite different names*

```diff
@@ -11,26 +11,35 @@
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 
 import numpy as np
 import pandas as pd
-import torch
 from numpy.typing import ArrayLike
-from PIL import Image
-from torch import Tensor, nn
-from torchvision.transforms import Compose, transforms
 
 from evadb.configuration.configuration_manager import ConfigurationManager
 from evadb.udfs.abstract.abstract_udf import (
     AbstractClassifierUDF,
     AbstractTransformationUDF,
 )
 from evadb.udfs.gpu_compatible import GPUCompatible
+from evadb.utils.generic_utils import (
+    try_to_import_pillow,
+    try_to_import_torch,
+    try_to_import_torchvision,
+)
+
+try_to_import_pillow()
+try_to_import_torch()
+try_to_import_torchvision()
+
+from PIL import Image
+from torch import nn
+from torchvision.transforms import Compose, transforms
 
 
 class PytorchAbstractClassifierUDF(AbstractClassifierUDF, nn.Module, GPUCompatible):
     """
     A pytorch based classifier. Used to make sure we make maximum
     utilization of features provided by pytorch without reinventing the wheel.
     """
@@ -60,41 +69,45 @@
         """
 
         frames = args[0]
         if isinstance(frames, pd.DataFrame):
             frames = frames.transpose().values.tolist()[0]
 
         gpu_batch_size = ConfigurationManager().get_value("executor", "gpu_batch_size")
+        import torch
+
         tens_batch = torch.cat([self.transform(x) for x in frames]).to(
             self.get_device()
         )
 
         if gpu_batch_size:
             chunks = torch.split(tens_batch, gpu_batch_size)
             outcome = pd.DataFrame()
             for tensor in chunks:
                 outcome = pd.concat([outcome, self.forward(tensor)], ignore_index=True)
             return outcome
         else:
             return self.forward(frames)
 
-    def as_numpy(self, val: Tensor) -> np.ndarray:
+    def as_numpy(self, val) -> np.ndarray:
         """
         Given a tensor in GPU, detach and get the numpy output
         Arguments:
              val (Tensor): tensor to be converted
         Returns:
             np.ndarray: numpy array representation
         """
         return val.detach().cpu().numpy()
 
     def to_device(self, device: str) -> GPUCompatible:
         """
         Required to make class a member of GPUCompatible Protocol.
         """
+        import torch
+
         return self.to(torch.device("cuda:{}".format(device)))
 
 
 class PytorchAbstractTransformationUDF(AbstractTransformationUDF, Compose):
     """
     Use PyTorch torchvision transforms as EvaDB transforms.
     """
```

### Comparing `evadb-0.2.9/evadb/udfs/abstract/tracker_abstract_udf.py` & `evadb-0.3.0/evadb/udfs/abstract/tracker_abstract_udf.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/asl_action_recognition.py` & `evadb-0.3.0/evadb/udfs/asl_action_recognition.py`

 * *Files 10% similar despite different names*

```diff
@@ -14,56 +14,52 @@
 # limitations under the License.
 
 import os
 import pickle as pkl
 
 import numpy as np
 import pandas as pd
-import torch
-import torchvision
-
-try:
-    from torchvision.models.video import R3D_18_Weights, r3d_18
-
-except ImportError:
-    raise ImportError(
-        f"torchvision>=0.14.0 is required to use video_resnet, found {torchvision.__version__}"
-    )
-import torch.nn as nn
-import torchvision
 
 from evadb.udfs.abstract.pytorch_abstract_udf import PytorchAbstractClassifierUDF
+from evadb.utils.generic_utils import try_to_import_torch, try_to_import_torchvision
 
 
 class ASLActionRecognition(PytorchAbstractClassifierUDF):
     @property
     def name(self) -> str:
         return "ASLActionRecognition"
 
     def download_weights(self):
+        try_to_import_torch()
+        import torch
+
         if not os.path.exists(self.asl_weights_path):
             torch.hub.download_url_to_file(
                 self.asl_weights_url,
                 self.asl_weights_path,
                 hash_prefix=None,
                 progress=True,
             )
 
     def setup(self):
         self.asl_weights_url = (
             "https://www.dropbox.com/s/s9l1mezuplc6ttl/asl_top20_resnet_wts.pth?raw=1"
         )
+        import torch
 
         self.asl_weights_path = torch.hub.get_dir() + "/asl_weights.pth"
         self.download_weights()
 
+        try_to_import_torchvision()
+        from torchvision.models.video import R3D_18_Weights, r3d_18
+
         self.weights = R3D_18_Weights.DEFAULT
         self.model = r3d_18(weights=self.weights)
         in_feats = self.model.fc.in_features
-        self.model.fc = nn.Linear(in_feats, 20)
+        self.model.fc = torch.nn.Linear(in_feats, 20)
         self.model.load_state_dict(
             torch.load(self.asl_weights_path, map_location="cpu")
         )
         self.model.eval()
 
         self.preprocess = self.weights.transforms()
 
@@ -77,22 +73,26 @@
         for action, index in action_to_index_map.items():
             actions_arr[index] = action
         return np.asarray(actions_arr)
 
     def forward(self, segments):
         return self.classify(segments)
 
-    def transform(self, segments) -> torch.Tensor:
+    def transform(self, segments):
+        import torch
+
         segments = torch.Tensor(segments)
         permute_order = [2, 1, 0]
         segments = segments[:, :, :, permute_order]
         segments = segments.permute(0, 3, 1, 2).to(torch.uint8)
         return self.preprocess(segments).unsqueeze(0)
 
-    def classify(self, segments: torch.Tensor) -> pd.DataFrame:
+    def classify(self, segments) -> pd.DataFrame:
+        import torch
+
         with torch.no_grad():
             preds = self.model(segments).softmax(1)
         label_indices = preds.argmax(axis=1)
 
         actions = self.labels[label_indices]
         # TODO ACTION: In the current pipeline, actions will always get batches on
         # length 1, so this case would never be invoked.
```

### Comparing `evadb-0.2.9/evadb/udfs/chatgpt.py` & `evadb-0.3.0/evadb/udfs/chatgpt.py`

 * *Files 20% similar despite different names*

```diff
@@ -12,39 +12,34 @@
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 
 
 import os
 
-import openai
 import pandas as pd
 from retry import retry
 
 from evadb.catalog.catalog_type import NdArrayType
 from evadb.configuration.configuration_manager import ConfigurationManager
 from evadb.udfs.abstract.abstract_udf import AbstractUDF
 from evadb.udfs.decorators.decorators import forward, setup
 from evadb.udfs.decorators.io_descriptors.data_types import PandasDataframe
+from evadb.utils.generic_utils import try_to_import_openai
 
 _VALID_CHAT_COMPLETION_MODEL = [
     "gpt-4",
     "gpt-4-0314",
     "gpt-4-32k",
     "gpt-4-32k-0314",
     "gpt-3.5-turbo",
     "gpt-3.5-turbo-0301",
 ]
 
 
-@retry(tries=6, delay=10)
-def completion_with_backoff(**kwargs):
-    return openai.ChatCompletion.create(**kwargs)
-
-
 class ChatGPT(AbstractUDF):
     @property
     def name(self) -> str:
         return "ChatGPT"
 
     @setup(cacheable=False, udf_type="chat-completion", batchable=True)
     def setup(
@@ -55,63 +50,97 @@
         assert model in _VALID_CHAT_COMPLETION_MODEL, f"Unsupported ChatGPT {model}"
         self.model = model
         self.temperature = temperature
 
     @forward(
         input_signatures=[
             PandasDataframe(
-                columns=["prompt", "query"],
+                columns=["query", "content", "prompt"],
                 column_types=[
                     NdArrayType.STR,
                     NdArrayType.STR,
+                    NdArrayType.STR,
                 ],
-                column_shapes=[(1,), (1,)],
+                column_shapes=[(1,), (1,), (None,)],
             )
         ],
         output_signatures=[
             PandasDataframe(
                 columns=["response"],
                 column_types=[
                     NdArrayType.STR,
                 ],
                 column_shapes=[(1,)],
             )
         ],
     )
     def forward(self, text_df):
+        try_to_import_openai()
+        import openai
+
+        @retry(tries=6, delay=20)
+        def completion_with_backoff(**kwargs):
+            try:
+                response = openai.ChatCompletion.create(**kwargs)
+                answer = response.choices[0].message.content
+            # ignore API rate limit error etc.
+            except Exception as e:
+                answer = f"{e}"
+            return answer
+
         # Register API key, try configuration manager first
         openai.api_key = ConfigurationManager().get_value("third_party", "OPENAI_KEY")
         # If not found, try OS Environment Variable
         if len(openai.api_key) == 0:
             openai.api_key = os.environ.get("OPENAI_KEY", "")
         assert (
             len(openai.api_key) != 0
         ), "Please set your OpenAI API key in evadb.yml file (third_party, open_api_key) or environment variable (OPENAI_KEY)"
 
-        prompts = text_df[text_df.columns[0]]
-        queries = text_df[text_df.columns[1]]
+        queries = text_df[text_df.columns[0]]
+        content = text_df[text_df.columns[0]]
+        if len(text_df.columns) > 1:
+            queries = text_df.iloc[:, 0]
+            content = text_df.iloc[:, 1]
+
+        prompt = None
+        if len(text_df.columns) > 2:
+            prompt = text_df.iloc[0, 2]
 
         # openai api currently supports answers to a single prompt only
         # so this udf is designed for that
         results = []
 
-        for prompt, query in zip(prompts, queries):
-            if prompt != "None":
-                query = prompt + ": " + query
-
+        for query, content in zip(queries, content):
             params = {
                 "model": self.model,
                 "temperature": self.temperature,
-                "messages": [
+                "messages": [],
+            }
+
+            def_sys_prompt_message = {
+                "role": "system",
+                "content": prompt
+                if prompt is not None
+                else "You are a helpful assistant that accomplishes user tasks.",
+            }
+
+            params["messages"].append(def_sys_prompt_message)
+            params["messages"].extend(
+                [
                     {
                         "role": "user",
-                        "content": query,
-                    }
+                        "content": f"Here is some context : {content}",
+                    },
+                    {
+                        "role": "user",
+                        "content": f"Complete the following task: {query}",
+                    },
                 ],
-            }
+            )
 
-            response = completion_with_backoff(**params)
-            results.append(response.choices[0].message.content)
+            answer = completion_with_backoff(**params)
+            results.append(answer)
 
         df = pd.DataFrame({"response": results})
 
         return df
```

### Comparing `evadb-0.2.9/evadb/udfs/decorators/__init__.py` & `evadb-0.3.0/evadb/udfs/decorators/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/decorators/decorators.py` & `evadb-0.3.0/evadb/udfs/decorators/decorators.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/decorators/io_descriptors/__init__.py` & `evadb-0.3.0/evadb/udfs/decorators/io_descriptors/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/decorators/io_descriptors/abstract_types.py` & `evadb-0.3.0/evadb/udfs/decorators/io_descriptors/abstract_types.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/decorators/io_descriptors/data_types.py` & `evadb-0.3.0/evadb/udfs/decorators/io_descriptors/data_types.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/decorators/utils.py` & `evadb-0.3.0/evadb/udfs/ndarray/vertical_flip.py`

 * *Files 25% similar despite different names*

```diff
@@ -8,46 +8,64 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-from typing import List, Type
+import numpy as np
+import pandas as pd
 
-from evadb.catalog.models.udf_io_catalog import UdfIOCatalogEntry
+from evadb.catalog.catalog_type import NdArrayType
 from evadb.udfs.abstract.abstract_udf import AbstractUDF
-
-
-def load_io_from_udf_decorators(
-    udf: Type[AbstractUDF], is_input=False
-) -> List[Type[UdfIOCatalogEntry]]:
-    """Load the inputs/outputs from the udf decorators and return a list of UdfIOCatalogEntry objects
-
-    Args:
-        udf (Object): UDF object
-        is_input (bool, optional): True if inputs are to be loaded. Defaults to False.
-
-    Returns:
-        Type[UdfIOCatalogEntry]: UdfIOCatalogEntry object created from the input decorator in setup
-    """
-    tag_key = "input" if is_input else "output"
-    io_signature = None
-    if hasattr(udf.forward, "tags") and tag_key in udf.forward.tags:
-        io_signature = udf.forward.tags[tag_key]
-    else:
-        # Attempt to populate from the parent class and stop at the first parent class
-        # where the required tags are found.
-        for base_class in udf.__bases__:
-            if hasattr(base_class, "forward") and hasattr(base_class.forward, "tags"):
-                if tag_key in base_class.forward.tags:
-                    io_signature = base_class.forward.tags[tag_key]
-                    break
-
-    assert (
-        io_signature is not None
-    ), f"Cannot infer io signature from the decorator for {udf}."
-
-    result_list = []
-    for io in io_signature:
-        result_list.extend(io.generate_catalog_entries(is_input))
-    return result_list
+from evadb.udfs.decorators.decorators import forward, setup
+from evadb.udfs.decorators.io_descriptors.data_types import PandasDataframe
+from evadb.utils.generic_utils import try_to_import_cv2
+
+
+class VerticalFlip(AbstractUDF):
+    @setup(cacheable=False, udf_type="cv2-transformation", batchable=True)
+    def setup(self):
+        try_to_import_cv2()
+
+    @property
+    def name(self):
+        return "VerticalFlip"
+
+    @forward(
+        input_signatures=[
+            PandasDataframe(
+                columns=["data"],
+                column_types=[NdArrayType.FLOAT32],
+                column_shapes=[(None, None, 3)],
+            )
+        ],
+        output_signatures=[
+            PandasDataframe(
+                columns=["vertically_flipped_frame_array"],
+                column_types=[NdArrayType.FLOAT32],
+                column_shapes=[(None, None, 3)],
+            )
+        ],
+    )
+    def forward(self, frame: pd.DataFrame) -> pd.DataFrame:
+        """
+        Apply vertical flip to the frame
+
+         Returns:
+             ret (pd.DataFrame): The modified frame.
+        """
+
+        def verticalFlip(row: pd.Series) -> np.ndarray:
+            row = row.to_list()
+            frame = row[0]
+            try_to_import_cv2()
+            import cv2
+
+            frame = cv2.flip(frame, 0)
+            # since cv2 by default reads an image in BGR
+            frame = cv2.cvtColor(frame, cv2.COLOR_BGR2RGB)
+            return frame
+
+        ret = pd.DataFrame()
+        ret["vertically_flipped_frame_array"] = frame.apply(verticalFlip, axis=1)
+        return ret
```

### Comparing `evadb-0.2.9/evadb/udfs/emotion_detector.py` & `evadb-0.3.0/evadb/udfs/emotion_detector.py`

 * *Files 13% similar despite different names*

```diff
@@ -14,22 +14,21 @@
 # limitations under the License.
 
 import os
 from typing import List
 
 import numpy as np
 import pandas as pd
-import torch
-import torch.nn as nn
-import torch.nn.functional as F
-from PIL import Image
-from torch import Tensor
-from torchvision import transforms
 
 from evadb.udfs.abstract.pytorch_abstract_udf import PytorchAbstractClassifierUDF
+from evadb.utils.generic_utils import (
+    try_to_import_pillow,
+    try_to_import_torch,
+    try_to_import_torchvision,
+)
 
 # VGG configuration
 cfg = {
     "VGG19": [
         64,
         64,
         "M",
@@ -51,123 +50,138 @@
         512,
         512,
         "M",
     ],
 }
 
 
-# helper class for VGG
-class VGG(nn.Module):
-    def __init__(self, vgg_name):
-        super(VGG, self).__init__()
-        self.features = self._make_layers(cfg[vgg_name])
-        self.classifier = nn.Linear(512, 7)
-
-    def forward(self, x):
-        out = self.features(x)
-        out = out.view(out.size(0), -1)
-        out = F.dropout(out, p=0.5, training=self.training)
-        out = self.classifier(out)
-        return out
-
-    def _make_layers(self, cfg):
-        layers = []
-        in_channels = 3
-        for x in cfg:
-            if x == "M":
-                layers += [nn.MaxPool2d(kernel_size=2, stride=2)]
-            else:
-                layers += [
-                    nn.Conv2d(in_channels, x, kernel_size=3, padding=1),
-                    nn.BatchNorm2d(x),
-                    nn.ReLU(inplace=True),
-                ]
-                in_channels = x
-        layers += [nn.AvgPool2d(kernel_size=1, stride=1)]
-        return nn.Sequential(*layers)
-
-
 class EmotionDetector(PytorchAbstractClassifierUDF):
     """
     Arguments:
         threshold (float): Threshold for classifier confidence score
     """
 
     @property
     def name(self) -> str:
         return "EmotionDetector"
 
     def _download_weights(self, weights_url, weights_path):
+        import torch
+
         if not os.path.exists(weights_path):
             torch.hub.download_url_to_file(
                 weights_url,
                 weights_path,
                 hash_prefix=None,
                 progress=True,
             )
 
     def setup(self, threshold=0.85):
         self.threshold = threshold
+        try_to_import_pillow()
+        try_to_import_torch()
+        try_to_import_torchvision()
+
+        import torch
+        import torch.nn.functional as F
+
         model_url = (
             "https://www.dropbox.com/s/85b63eahka5r439/emotion_detector.t7?raw=1"
         )
         model_weights_path = torch.hub.get_dir() + "/emotion_detector.t7"
         # pull model weights from dropbox if not present
         self._download_weights(model_url, model_weights_path)
 
+        # helper class for VGG
+        class VGG(torch.nn.Module):
+            def __init__(self, vgg_name):
+                super(VGG, self).__init__()
+                self.features = self._make_layers(cfg[vgg_name])
+                self.classifier = torch.nn.Linear(512, 7)
+
+            def forward(self, x):
+                out = self.features(x)
+                out = out.view(out.size(0), -1)
+                out = F.dropout(out, p=0.5, training=self.training)
+                out = self.classifier(out)
+                return out
+
+            def _make_layers(self, cfg):
+                layers = []
+                in_channels = 3
+                for x in cfg:
+                    if x == "M":
+                        layers += [torch.nn.MaxPool2d(kernel_size=2, stride=2)]
+                    else:
+                        layers += [
+                            torch.nn.Conv2d(in_channels, x, kernel_size=3, padding=1),
+                            torch.nn.BatchNorm2d(x),
+                            torch.nn.ReLU(inplace=True),
+                        ]
+                        in_channels = x
+                layers += [torch.nn.AvgPool2d(kernel_size=1, stride=1)]
+                return torch.nn.Sequential(*layers)
+
         # load model
         self.model = VGG("VGG19")
 
         # self.get_device() infers device from the loaded model, so not using it
         device = torch.device("cuda" if torch.cuda.is_available() else "cpu")
         model_state = torch.load(model_weights_path, map_location=device)
         self.model.load_state_dict(model_state["net"])
         self.model.eval()
 
         # for augmentation
         self.cut_size = 44
 
-    def transforms_ed(self, frame: Image) -> Tensor:
+    def transforms_ed(self, frame):
         """
         Performs augmentation on input frame
         Arguments:
             frame (Tensor): Frame on which augmentation needs
             to be performed
         Returns:
             frame (Tensor): Augmented frame
         """
+        from torchvision import transforms
 
         # convert to grayscale, resize and make tensor
         frame = frame.convert("L")
         frame = transforms.functional.resize(frame, (48, 48))
         frame = transforms.functional.to_tensor(frame)
 
         return frame
 
     def transform(self, images: np.ndarray):
         # reverse the channels from opencv
+        from PIL import Image
+
         return self.transforms_ed(Image.fromarray(images[:, :, ::-1]))
 
     @property
     def labels(self) -> List[str]:
         return ["angry", "disgust", "fear", "happy", "sad", "surprise", "neutral"]
 
-    def forward(self, frames: Tensor) -> pd.DataFrame:
+    def forward(self, frames) -> pd.DataFrame:
         """
         Performs predictions on input frames
         Arguments:
             frames (Tensor): Frames on which predictions need
             to be performed
         Returns:
             outcome (pd.DataFrame): Emotion Predictions for input frames
         """
 
         # result dataframe
         outcome = []
 
+        import torch
+        import torch.nn.functional as F
+        from torchvision import transforms
+
         # convert to 3 channels, ten crop and stack
         frames = frames.repeat(3, 1, 1)
         frames = transforms.functional.ten_crop(frames, self.cut_size)
         frames = torch.stack([crop for crop in frames])
 
         # perform predictions and take mean over crops
         predictions = self.model(frames)
```

### Comparing `evadb-0.2.9/evadb/udfs/face_detector.py` & `evadb-0.3.0/evadb/udfs/face_detector.py`

 * *Files 11% similar despite different names*

```diff
@@ -13,37 +13,49 @@
 # See the License for the specific language governing permissions and
 # limitations under the License.
 
 from typing import List
 
 import numpy as np
 import pandas as pd
-import torch
-from facenet_pytorch import MTCNN
 
 from evadb.udfs.abstract.abstract_udf import AbstractClassifierUDF
 from evadb.udfs.gpu_compatible import GPUCompatible
+from evadb.utils.generic_utils import (
+    try_to_import_facenet_pytorch,
+    try_to_import_torch,
+    try_to_import_torchvision,
+)
 from evadb.utils.logging_manager import logger
 
 
 class FaceDetector(AbstractClassifierUDF, GPUCompatible):
     """
     Arguments:
         threshold (float): Threshold for classifier confidence score
     """
 
     def setup(self, threshold=0.85):
         self.threshold = threshold
+        try_to_import_torch()
+        try_to_import_torchvision()
+        try_to_import_facenet_pytorch()
+        from facenet_pytorch import MTCNN
+
         self.model = MTCNN()
 
     @property
     def name(self) -> str:
         return "FaceDetector"
 
     def to_device(self, device: str):
+        try_to_import_facenet_pytorch()
+        import torch
+        from facenet_pytorch import MTCNN
+
         gpu = "cuda:{}".format(device)
         self.model = MTCNN(device=torch.device(gpu))
         return self
 
     @property
     def labels(self) -> List[str]:
         return []
```

### Comparing `evadb-0.2.9/evadb/udfs/fastrcnn_object_detector.py` & `evadb-0.3.0/evadb/udfs/fastrcnn_object_detector.py`

 * *Files 5% similar despite different names*

```diff
@@ -20,30 +20,15 @@
 from evadb.catalog.catalog_type import NdArrayType
 from evadb.udfs.abstract.pytorch_abstract_udf import PytorchAbstractClassifierUDF
 from evadb.udfs.decorators.decorators import forward, setup
 from evadb.udfs.decorators.io_descriptors.data_types import (
     PandasDataframe,
     PyTorchTensor,
 )
-
-try:
-    from torch import Tensor
-except ImportError as e:
-    raise ImportError(
-        f"Failed to import with error {e}, \
-        please try `pip install torch`"
-    )
-
-try:
-    import torchvision
-except ImportError as e:
-    raise ImportError(
-        f"Failed to import with error {e}, \
-        please try `pip install torch`"
-    )
+from evadb.utils.generic_utils import try_to_import_torch, try_to_import_torchvision
 
 
 class FastRCNNObjectDetector(PytorchAbstractClassifierUDF):
     """
     Arguments:
         threshold (float): Threshold for classifier confidence score
 
@@ -51,14 +36,18 @@
 
     @property
     def name(self) -> str:
         return "fastrcnn"
 
     @setup(cacheable=True, udf_type="object_detection", batchable=True)
     def setup(self, threshold=0.85):
+        try_to_import_torch()
+        try_to_import_torchvision()
+        import torchvision
+
         self.threshold = threshold
         self.model = torchvision.models.detection.fasterrcnn_resnet50_fpn(
             weights="COCO_V1", progress=False
         )
         self.model.eval()
 
     @property
@@ -174,15 +163,15 @@
                     NdArrayType.FLOAT32,
                     NdArrayType.FLOAT32,
                 ],
                 column_shapes=[(None,), (None,), (None,)],
             )
         ],
     )
-    def forward(self, frames: Tensor) -> pd.DataFrame:
+    def forward(self, frames) -> pd.DataFrame:
         """
         Performs predictions on input frames
         Arguments:
             frames (np.ndarray): Frames on which predictions need
             to be performed
 
         Returns:
```

### Comparing `evadb-0.2.9/evadb/udfs/feature_extractor.py` & `evadb-0.3.0/evadb/udfs/feature_extractor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/gpu_compatible.py` & `evadb-0.3.0/evadb/udfs/gpu_compatible.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/mnist_image_classifier.py` & `evadb-0.3.0/evadb/udfs/mnist_image_classifier.py`

 * *Files 17% similar despite different names*

```diff
@@ -11,92 +11,96 @@
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 from collections import OrderedDict
 
 import pandas as pd
-import torch
-import torch.nn as nn
-import torch.utils.model_zoo as model_zoo
-from PIL import Image
-from torch import Tensor
-from torchvision.transforms import Compose, Grayscale, Normalize, ToTensor
 
 from evadb.udfs.abstract.pytorch_abstract_udf import PytorchAbstractClassifierUDF
+from evadb.utils.generic_utils import try_to_import_torch, try_to_import_torchvision
 
 
 class MnistImageClassifier(PytorchAbstractClassifierUDF):
     @property
     def name(self) -> str:
         return "MnistImageClassifier"
 
     def setup(self):
+        try_to_import_torch()
+        try_to_import_torchvision()
+        import torch
+        import torch.nn as nn
+
+        model_urls = {
+            "mnist": "http://ml.cs.tsinghua.edu.cn/~chenxi/pytorch-models/mnist-b07bb66b.pth"  # noqa
+        }
+
+        # https://github.com/aaron-xichen/pytorch-playground/blob/master/
+        class MLP(nn.Module):
+            def __init__(self, input_dims, n_hiddens, n_class):
+                super(MLP, self).__init__()
+                assert isinstance(input_dims, int), "Please provide int for input_dims"
+                self.input_dims = input_dims
+                current_dims = input_dims
+                layers = OrderedDict()
+
+                if isinstance(n_hiddens, int):
+                    n_hiddens = [n_hiddens]
+                else:
+                    n_hiddens = list(n_hiddens)
+                for i, n_hidden in enumerate(n_hiddens):
+                    layers["fc{}".format(i + 1)] = nn.Linear(current_dims, n_hidden)
+                    layers["relu{}".format(i + 1)] = nn.ReLU()
+                    layers["drop{}".format(i + 1)] = nn.Dropout(0.2)
+                    current_dims = n_hidden
+                layers["out"] = nn.Linear(current_dims, n_class)
+
+                self.model = nn.Sequential(layers)
+
+            def forward(self, input):
+                input = input.view(input.size(0), -1)
+                assert input.size(1) == self.input_dims
+                return self.model.forward(input)
+
+        def mnist(input_dims=784, n_hiddens=[256, 256], n_class=10, pretrained=None):
+            model = MLP(input_dims, n_hiddens, n_class)
+            import torch.utils.model_zoo as model_zoo
+
+            if pretrained is not None:
+                m = model_zoo.load_url(
+                    model_urls["mnist"], map_location=torch.device("cpu")
+                )
+                state_dict = m.state_dict() if isinstance(m, nn.Module) else m
+                assert isinstance(state_dict, (dict, OrderedDict)), type(state_dict)
+                model.load_state_dict(state_dict)
+            return model
+
         self.model = mnist(pretrained=True)
         self.model.eval()
 
     @property
     def labels(self):
         return list([str(num) for num in range(10)])
 
-    def transform(self, images) -> Compose:
+    def transform(self, images):
+        from PIL import Image
+        from torchvision.transforms import Compose, Grayscale, Normalize, ToTensor
+
         composed = Compose(
             [
                 Grayscale(num_output_channels=1),
                 ToTensor(),
                 Normalize((0.1307,), (0.3081,)),
             ]
         )
         # reverse the channels from opencv
         return composed(Image.fromarray(images[:, :, ::-1])).unsqueeze(0)
 
-    def forward(self, frames: Tensor) -> pd.DataFrame:
+    def forward(self, frames) -> pd.DataFrame:
         outcome = []
         predictions = self.model(frames)
         for prediction in predictions:
             label = self.as_numpy(prediction.data.argmax())
             outcome.append({"label": str(label)})
 
         return pd.DataFrame(outcome, columns=["label"])
-
-
-model_urls = {
-    "mnist": "http://ml.cs.tsinghua.edu.cn/~chenxi/pytorch-models/mnist-b07bb66b.pth"  # noqa
-}
-
-
-# https://github.com/aaron-xichen/pytorch-playground/blob/master/
-class MLP(nn.Module):
-    def __init__(self, input_dims, n_hiddens, n_class):
-        super(MLP, self).__init__()
-        assert isinstance(input_dims, int), "Please provide int for input_dims"
-        self.input_dims = input_dims
-        current_dims = input_dims
-        layers = OrderedDict()
-
-        if isinstance(n_hiddens, int):
-            n_hiddens = [n_hiddens]
-        else:
-            n_hiddens = list(n_hiddens)
-        for i, n_hidden in enumerate(n_hiddens):
-            layers["fc{}".format(i + 1)] = nn.Linear(current_dims, n_hidden)
-            layers["relu{}".format(i + 1)] = nn.ReLU()
-            layers["drop{}".format(i + 1)] = nn.Dropout(0.2)
-            current_dims = n_hidden
-        layers["out"] = nn.Linear(current_dims, n_class)
-
-        self.model = nn.Sequential(layers)
-
-    def forward(self, input):
-        input = input.view(input.size(0), -1)
-        assert input.size(1) == self.input_dims
-        return self.model.forward(input)
-
-
-def mnist(input_dims=784, n_hiddens=[256, 256], n_class=10, pretrained=None):
-    model = MLP(input_dims, n_hiddens, n_class)
-    if pretrained is not None:
-        m = model_zoo.load_url(model_urls["mnist"], map_location=torch.device("cpu"))
-        state_dict = m.state_dict() if isinstance(m, nn.Module) else m
-        assert isinstance(state_dict, (dict, OrderedDict)), type(state_dict)
-        model.load_state_dict(state_dict)
-    return model
```

### Comparing `evadb-0.2.9/evadb/udfs/mvit_action_recognition.py` & `evadb-0.3.0/evadb/udfs/mvit_action_recognition.py`

 * *Files 8% similar despite different names*

```diff
@@ -11,50 +11,51 @@
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 
 import numpy as np
 import pandas as pd
-import torch
-import torchvision
 
-try:
-    from torchvision.models.video import MViT_V2_S_Weights, mvit_v2_s
-except ImportError:
-    raise ImportError(
-        f"torchvision>=0.14.0 is required to use MVITActionRecognition, found {torchvision.__version__}"
-    )
 from evadb.udfs.abstract.pytorch_abstract_udf import PytorchAbstractClassifierUDF
+from evadb.utils.generic_utils import try_to_import_torch, try_to_import_torchvision
 
 
 class MVITActionRecognition(PytorchAbstractClassifierUDF):
     @property
     def name(self) -> str:
         return "MVITActionRecognition"
 
     def setup(self):
+        try_to_import_torchvision()
+        try_to_import_torch()
+        from torchvision.models.video import MViT_V2_S_Weights, mvit_v2_s
+
         self.weights = MViT_V2_S_Weights.DEFAULT
         self.model = mvit_v2_s(weights=self.weights)
         self.preprocess = self.weights.transforms()
         self.model.eval()
 
     @property
     def labels(self) -> np.array([str]):
         return np.array(self.weights.meta["categories"])
 
     def forward(self, segments):
         return self.classify(segments)
 
-    def transform(self, segments) -> torch.Tensor:
+    def transform(self, segments):
+        import torch
+
         segments = torch.Tensor(segments)
         segments = segments.permute(0, 3, 1, 2)
         return self.preprocess(segments).unsqueeze(0)
 
-    def classify(self, segments: torch.Tensor) -> pd.DataFrame:
+    def classify(self, segments) -> pd.DataFrame:
+        import torch
+
         with torch.no_grad():
             preds = self.model(segments).softmax(1)
         label_indices = preds.argmax(axis=1)
         actions = self.labels[label_indices]
         # TODO ACTION: In the current pipeline, actions will always get batches on
         # length 1, so this case would never be invoked.
         if np.isscalar(actions) == 1:
```

### Comparing `evadb-0.2.9/evadb/udfs/ndarray/__init__.py` & `evadb-0.3.0/evadb/udfs/ndarray/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/ndarray/annotate.py` & `evadb-0.3.0/evadb/udfs/ndarray/annotate.py`

 * *Files 4% similar despite different names*

```diff
@@ -8,22 +8,22 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-import cv2
 import numpy as np
 import pandas as pd
 
 from evadb.catalog.catalog_type import NdArrayType
 from evadb.udfs.abstract.abstract_udf import AbstractUDF
 from evadb.udfs.decorators.decorators import forward, setup
 from evadb.udfs.decorators.io_descriptors.data_types import PandasDataframe
+from evadb.utils.generic_utils import try_to_import_cv2
 
 color = (207, 248, 64)
 thickness = 4
 
 
 class Annotate(AbstractUDF):
     @setup(cacheable=False, udf_type="cv2-transformation", batchable=True)
@@ -62,14 +62,16 @@
              ret (pd.DataFrame): The modified frame.
         """
 
         def annotate(row: pd.Series) -> np.ndarray:
             row = row.to_list()
             frame = row[0]
             bboxes = row[2]
+            try_to_import_cv2()
+            import cv2
 
             for bbox in bboxes:
                 x1, y1, x2, y2 = np.asarray(bbox, dtype="int")
                 x1, y1, x2, y2 = int(x1), int(y1), int(x2), int(y2)
                 frame = cv2.rectangle(frame, (x1, y1), (x2, y2), color, thickness)
             return frame
```

### Comparing `evadb-0.2.9/evadb/udfs/ndarray/array_count.py` & `evadb-0.3.0/evadb/udfs/ndarray/array_count.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/ndarray/crop.py` & `evadb-0.3.0/evadb/udfs/ndarray/crop.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/ndarray/fuzzy_join.py` & `evadb-0.3.0/evadb/udfs/ndarray/fuzzy_join.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/ndarray/gaussian_blur.py` & `evadb-0.3.0/evadb/udfs/ndarray/gaussian_blur.py`

 * *Files 6% similar despite different names*

```diff
@@ -8,22 +8,22 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-import cv2
 import numpy as np
 import pandas as pd
 
 from evadb.catalog.catalog_type import NdArrayType
 from evadb.udfs.abstract.abstract_udf import AbstractUDF
 from evadb.udfs.decorators.decorators import forward, setup
 from evadb.udfs.decorators.io_descriptors.data_types import PandasDataframe
+from evadb.utils.generic_utils import try_to_import_cv2
 
 
 class GaussianBlur(AbstractUDF):
     @setup(cacheable=False, udf_type="cv2-transformation", batchable=True)
     def setup(self):
         pass
 
@@ -54,14 +54,16 @@
          Returns:
              ret (pd.DataFrame): The modified frame.
         """
 
         def gaussianBlur(row: pd.Series) -> np.ndarray:
             row = row.to_list()
             frame = row[0]
+            try_to_import_cv2()
+            import cv2
 
             frame = cv2.GaussianBlur(frame, (5, 5), cv2.BORDER_DEFAULT)
             # since cv2 by default reads an image in BGR
             frame = cv2.cvtColor(frame, cv2.COLOR_BGR2RGB)
 
             return frame
```

### Comparing `evadb-0.2.9/evadb/udfs/ndarray/horizontal_flip.py` & `evadb-0.3.0/evadb/udfs/ndarray/horizontal_flip.py`

 * *Files 10% similar despite different names*

```diff
@@ -8,28 +8,28 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-import cv2
 import numpy as np
 import pandas as pd
 
 from evadb.catalog.catalog_type import NdArrayType
 from evadb.udfs.abstract.abstract_udf import AbstractUDF
 from evadb.udfs.decorators.decorators import forward, setup
 from evadb.udfs.decorators.io_descriptors.data_types import PandasDataframe
+from evadb.utils.generic_utils import try_to_import_cv2
 
 
 class HorizontalFlip(AbstractUDF):
     @setup(cacheable=False, udf_type="cv2-transformation", batchable=True)
     def setup(self):
-        pass
+        try_to_import_cv2()
 
     @property
     def name(self):
         return "HorizontalFlip"
 
     @forward(
         input_signatures=[
@@ -54,14 +54,16 @@
          Returns:
              ret (pd.DataFrame): The modified frame.
         """
 
         def horizontalFlip(row: pd.Series) -> np.ndarray:
             row = row.to_list()
             frame = row[0]
+            try_to_import_cv2()
+            import cv2
 
             frame = cv2.flip(frame, 1)
             # since cv2 by default reads an image in BGR
             frame = cv2.cvtColor(frame, cv2.COLOR_BGR2RGB)
             return frame
 
         ret = pd.DataFrame()
```

### Comparing `evadb-0.2.9/evadb/udfs/ndarray/open.py` & `evadb-0.3.0/evadb/udfs/ndarray/open.py`

 * *Files 22% similar despite different names*

```diff
@@ -8,25 +8,26 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-import cv2
 import numpy as np
 import pandas as pd
 
 from evadb.udfs.abstract.abstract_udf import AbstractUDF
+from evadb.utils.generic_utils import try_to_import_cv2
 
 
 class Open(AbstractUDF):
     def setup(self):
         # cache data to avoid expensive open files on disk
         self._data_cache = dict()
+        try_to_import_cv2()
 
     @property
     def name(self):
         return "Open"
 
     def forward(self, df: pd.DataFrame) -> pd.DataFrame:
         """
@@ -37,14 +38,16 @@
         """
 
         def _open(row: pd.Series) -> np.ndarray:
             path_str = row[0]
             if path_str in self._data_cache:
                 data = self._data_cache[path_str]
             else:
+                import cv2
+
                 data = cv2.imread(path_str)
                 assert data is not None, f"Failed to open file {path_str}"
             self._data_cache[path_str] = data
 
             return data
 
         ret = pd.DataFrame()
```

### Comparing `evadb-0.2.9/evadb/udfs/ndarray/similarity.py` & `evadb-0.3.0/evadb/udfs/ndarray/similarity.py`

 * *Files 8% similar despite different names*

```diff
@@ -8,25 +8,26 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-import faiss
 import pandas as pd
 
 from evadb.udfs.abstract.abstract_udf import AbstractUDF
+from evadb.utils.generic_utils import try_to_import_faiss
 
 
 class Similarity(AbstractUDF):
     def _get_distance(self, numpy_distance):
         return numpy_distance[0][0]
 
     def setup(self):
+        try_to_import_faiss()
         pass
 
     @property
     def name(self):
         return "Similarity"
 
     def forward(self, df: pd.DataFrame) -> pd.DataFrame:
@@ -42,14 +43,16 @@
             )
 
             # TODO: currently system takes care of feature vector shape
             # transformation. Improve this later on.
             # Transform to 2D.
             open_feat_np = open_feat_np.reshape(1, -1)
             base_feat_np = base_feat_np.reshape(1, -1)
+            import faiss
+
             distance_np = faiss.pairwise_distances(open_feat_np, base_feat_np)
 
             return self._get_distance(distance_np)
 
         ret = pd.DataFrame()
         ret["distance"] = df.apply(_similarity, axis=1)
         return ret
```

### Comparing `evadb-0.2.9/evadb/udfs/ndarray/to_grayscale.py` & `evadb-0.3.0/evadb/udfs/ndarray/to_grayscale.py`

 * *Files 8% similar despite different names*

```diff
@@ -8,28 +8,28 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-import cv2
 import numpy as np
 import pandas as pd
 
 from evadb.catalog.catalog_type import NdArrayType
 from evadb.udfs.abstract.abstract_udf import AbstractUDF
 from evadb.udfs.decorators.decorators import forward, setup
 from evadb.udfs.decorators.io_descriptors.data_types import PandasDataframe
+from evadb.utils.generic_utils import try_to_import_cv2
 
 
 class ToGrayscale(AbstractUDF):
     @setup(cacheable=False, udf_type="cv2-transformation", batchable=True)
     def setup(self):
-        pass
+        try_to_import_cv2()
 
     @property
     def name(self):
         return "ToGrayscale"
 
     @forward(
         input_signatures=[
@@ -55,14 +55,16 @@
              ret (pd.DataFrame): The modified frame.
         """
 
         def toGrayscale(row: pd.Series) -> np.ndarray:
             row = row.to_list()
             frame = row[0]
 
+            import cv2
+
             frame = cv2.cvtColor(frame, cv2.COLOR_BGR2GRAY)
             frame = cv2.cvtColor(frame, cv2.COLOR_GRAY2RGB)
 
             return frame
 
         ret = pd.DataFrame()
         ret["grayscale_frame_array"] = frame.apply(toGrayscale, axis=1)
```

### Comparing `evadb-0.2.9/evadb/udfs/ndarray/vertical_flip.py` & `evadb-0.3.0/evadb/udfs/fuzzy_join.py`

 * *Files 20% similar despite different names*

```diff
@@ -8,62 +8,68 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-import cv2
+
+
+# coding=utf-8
+# Copyright 2018-2022 EVA
+#
+# Licensed under the Apache License, Version 2.0 (the "License");
+# you may not use this file except in compliance with the License.
+# You may obtain a copy of the License at
+#
+#     http://www.apache.org/licenses/LICENSE-2.0
+#
+# Unless required by applicable law or agreed to in writing, software
+# distributed under the License is distributed on an "AS IS" BASIS,
+# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
+# See the License for the specific language governing permissions and
+# limitations under the License.
 import numpy as np
 import pandas as pd
+from thefuzz import fuzz
 
 from evadb.catalog.catalog_type import NdArrayType
 from evadb.udfs.abstract.abstract_udf import AbstractUDF
 from evadb.udfs.decorators.decorators import forward, setup
 from evadb.udfs.decorators.io_descriptors.data_types import PandasDataframe
 
 
-class VerticalFlip(AbstractUDF):
-    @setup(cacheable=False, udf_type="cv2-transformation", batchable=True)
+class FuzzDistance(AbstractUDF):
+    @setup(cacheable=False, udf_type="FeatureExtraction", batchable=False)
     def setup(self):
         pass
 
     @property
-    def name(self):
-        return "VerticalFlip"
+    def name(self) -> str:
+        return "FuzzDistance"
 
     @forward(
         input_signatures=[
             PandasDataframe(
-                columns=["data"],
-                column_types=[NdArrayType.FLOAT32],
-                column_shapes=[(None, None, 3)],
+                columns=["data1", "data2"],
+                column_types=[NdArrayType.STR, NdArrayType.STR],
+                column_shapes=[(1), (1)],
             )
         ],
         output_signatures=[
             PandasDataframe(
-                columns=["vertically_flipped_frame_array"],
+                columns=["distance"],
                 column_types=[NdArrayType.FLOAT32],
-                column_shapes=[(None, None, 3)],
+                column_shapes=[(1)],
             )
         ],
     )
-    def forward(self, frame: pd.DataFrame) -> pd.DataFrame:
-        """
-        Apply vertical flip to the frame
-
-         Returns:
-             ret (pd.DataFrame): The modified frame.
-        """
-
-        def verticalFlip(row: pd.Series) -> np.ndarray:
-            row = row.to_list()
-            frame = row[0]
-
-            frame = cv2.flip(frame, 0)
-            # since cv2 by default reads an image in BGR
-            frame = cv2.cvtColor(frame, cv2.COLOR_BGR2RGB)
-            return frame
+    def forward(self, df: pd.DataFrame) -> pd.DataFrame:
+        def _forward(row: pd.Series) -> np.ndarray:
+            data1 = row.iloc[0]
+            data2 = row.iloc[1]
+            distance = fuzz.ratio(data1, data2)
+            return distance
 
         ret = pd.DataFrame()
-        ret["vertically_flipped_frame_array"] = frame.apply(verticalFlip, axis=1)
+        ret["distance"] = df.apply(_forward, axis=1)
         return ret
```

### Comparing `evadb-0.2.9/evadb/udfs/saliency_feature_extractor.py` & `evadb-0.3.0/evadb/udfs/saliency_feature_extractor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/sentence_transformer_feature_extractor.py` & `evadb-0.3.0/evadb/udfs/sentence_feature_extractor.py`

 * *Files 16% similar despite different names*

```diff
@@ -10,23 +10,36 @@
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import numpy as np
 import pandas as pd
-from sentence_transformers import SentenceTransformer
 
 from evadb.catalog.catalog_type import NdArrayType
 from evadb.udfs.abstract.abstract_udf import AbstractUDF
 from evadb.udfs.decorators.decorators import forward, setup
 from evadb.udfs.decorators.io_descriptors.data_types import PandasDataframe
 from evadb.udfs.gpu_compatible import GPUCompatible
 
 
+def try_to_import_sentence_transformers():
+    try:
+        import sentence_transformers  # noqa: F401
+    except ImportError:
+        raise ValueError(
+            """Could not import sentence-transformers python package.
+                Please install it with `pip install sentence-transformers`."""
+        )
+
+
+try_to_import_sentence_transformers()
+from sentence_transformers import SentenceTransformer  # noqa: E402
+
+
 class SentenceTransformerFeatureExtractor(AbstractUDF, GPUCompatible):
     @setup(cacheable=False, udf_type="FeatureExtraction", batchable=False)
     def setup(self):
         self.model = SentenceTransformer("all-MiniLM-L6-v2")
 
     def to_device(self, device: str) -> GPUCompatible:
         self.model = self.model.to(device)
```

### Comparing `evadb-0.2.9/evadb/udfs/sift_feature_extractor.py` & `evadb-0.3.0/evadb/udfs/sift_feature_extractor.py`

 * *Files 14% similar despite different names*

```diff
@@ -8,30 +8,35 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-import cv2
-import kornia
 import numpy as np
 import pandas as pd
-import torch
 
 from evadb.catalog.catalog_type import NdArrayType
 from evadb.udfs.abstract.abstract_udf import AbstractUDF
 from evadb.udfs.decorators.decorators import forward, setup
 from evadb.udfs.decorators.io_descriptors.data_types import PandasDataframe
 from evadb.udfs.gpu_compatible import GPUCompatible
+from evadb.utils.generic_utils import (
+    try_to_import_cv2,
+    try_to_import_kornia,
+    try_to_import_torch,
+)
 
 
 class SiftFeatureExtractor(AbstractUDF, GPUCompatible):
     @setup(cacheable=False, udf_type="FeatureExtraction", batchable=False)
     def setup(self):
+        try_to_import_kornia()
+        import kornia
+
         self.model = kornia.feature.SIFTDescriptor(100)
 
     def to_device(self, device: str) -> GPUCompatible:
         self.model = self.model.to(device)
         return self
 
     @property
@@ -54,23 +59,29 @@
             )
         ],
     )
     def forward(self, df: pd.DataFrame) -> pd.DataFrame:
         def _forward(row: pd.Series) -> np.ndarray:
             # Prepare gray image to batched gray image within size.
             rgb_img = row[0]
+            try_to_import_cv2()
+            import cv2
+
             gray_img = cv2.cvtColor(rgb_img, cv2.COLOR_RGB2GRAY)
             resized_gray_img = cv2.resize(
                 gray_img, (100, 100), interpolation=cv2.INTER_AREA
             )
             resized_gray_img = np.moveaxis(resized_gray_img, -1, 0)
             batch_resized_gray_img = np.expand_dims(resized_gray_img, axis=0)
             batch_resized_gray_img = np.expand_dims(batch_resized_gray_img, axis=0)
             batch_resized_gray_img = batch_resized_gray_img.astype(np.float32)
 
+            try_to_import_torch()
+            import torch
+
             # Sift inference.
             with torch.no_grad():
                 torch_feat = self.model(torch.from_numpy(batch_resized_gray_img))
                 feat = torch_feat.numpy()
 
             # Feature reshape.
             feat = feat.reshape(1, -1)
```

### Comparing `evadb-0.2.9/evadb/udfs/trackers/__init__.py` & `evadb-0.3.0/evadb/udfs/trackers/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/udfs/trackers/nor_fair.py` & `evadb-0.3.0/evadb/udfs/trackers/nor_fair.py`

 * *Files 6% similar despite different names*

```diff
@@ -9,36 +9,41 @@
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import numpy as np
-from norfair import Detection, Tracker
 
 from evadb.udfs.abstract.tracker_abstract_udf import EvaDBTrackerAbstractUDF
+from evadb.utils.generic_utils import try_to_import_norfair
 from evadb.utils.math_utils import get_centroid
 
 DISTANCE_THRESHOLD_CENTROID: int = 30
 
 
 class NorFairTracker(EvaDBTrackerAbstractUDF):
     @property
     def name(self) -> str:
         return "NorFairTracker"
 
     def setup(self, distance_threshold=DISTANCE_THRESHOLD_CENTROID) -> None:
         # https://github.com/tryolabs/norfair/blob/74b11edde83941dd6e32bcccd5fa849e16bf8564/norfair/tracker.py#L18
+        try_to_import_norfair()
+        from norfair import Tracker
+
         self.tracker = Tracker(
             distance_function="euclidean",
             distance_threshold=distance_threshold,
         )
         self.prev_frame_id = None
 
     def forward(self, frame_id, frame, labels, bboxes, scores):
+        from norfair import Detection
+
         norfair_detections = [
             Detection(
                 points=get_centroid(bbox),
                 scores=np.array([score]),
                 label=hash(label) % 10**8,
                 data=(label, bbox, score),
             )
```

### Comparing `evadb-0.2.9/evadb/udfs/tutorials/__init__.py` & `evadb-0.3.0/test/udfs/__init__.py`

 * *Files 22% similar despite different names*

```diff
@@ -8,8 +8,8 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-"""user defined functions for object tracking"""
+"""user defined functions operating on ndarrays"""
```

### Comparing `evadb-0.2.9/evadb/udfs/udf_bootstrap_queries.py` & `evadb-0.3.0/evadb/udfs/udf_bootstrap_queries.py`

 * *Files 15% similar despite different names*

```diff
@@ -118,24 +118,14 @@
 )
 
 Yolo_udf_query = """CREATE UDF IF NOT EXISTS Yolo
       TYPE  ultralytics
       'model' 'yolov8m.pt';
       """
 
-ocr_udf_query = """CREATE UDF IF NOT EXISTS OCRExtractor
-      INPUT  (frame NDARRAY UINT8(3, ANYDIM, ANYDIM))
-      OUTPUT (labels NDARRAY STR(10), bboxes NDARRAY FLOAT32(ANYDIM, 4),
-                scores NDARRAY FLOAT32(ANYDIM))
-      TYPE  OCRExtraction
-      IMPL  '{}/udfs/ocr_extractor.py';
-      """.format(
-    EvaDB_INSTALLATION_DIR
-)
-
 face_detection_udf_query = """CREATE UDF IF NOT EXISTS FaceDetector
                   INPUT  (frame NDARRAY UINT8(3, ANYDIM, ANYDIM))
                   OUTPUT (bboxes NDARRAY FLOAT32(ANYDIM, 4),
                           scores NDARRAY FLOAT32(ANYDIM))
                   TYPE  FaceDetection
                   IMPL  '{}/udfs/face_detector.py';
         """.format(
@@ -189,60 +179,78 @@
 
 chatgpt_udf_query = """CREATE UDF IF NOT EXISTS ChatGPT
         IMPL '{}/udfs/chatgpt.py';
         """.format(
     EvaDB_INSTALLATION_DIR
 )
 
+yolo8n_query = """CREATE UDF IF NOT EXISTS Yolo
+            TYPE  ultralytics
+            'model' 'yolov8n.pt';
+        """
+
 
 def init_builtin_udfs(db: EvaDBDatabase, mode: str = "debug") -> None:
     """Load the built-in UDFs into the system during system bootstrapping.
 
     The function loads a set of pre-defined UDF queries based on the `mode` argument.
     In 'debug' mode, the function loads debug UDFs along with release UDFs.
     In 'release' mode, only release UDFs are loaded. In addition, in 'debug' mode,
     the function loads a smaller model to accelerate the test suite time.
 
     Args:
         mode (str, optional): The mode for loading UDFs, either 'debug' or 'release'.
         Defaults to 'debug'.
 
     """
+
+    # Attempting to import torch module
+    # It is necessary to import torch before to avoid encountering a
+    # "RuntimeError: random_device could not be read"
+    # The suspicion is that importing torch prior to decord resolves this issue
+    try:
+        import torch  # noqa: F401
+    except ImportError:
+        pass
+
+    # Enable environment variables
+    # Relevant for transformer-based models
+    import os
+
+    os.environ["PROTOCOL_BUFFERS_PYTHON_IMPLEMENTATION"] = "python"
+    os.environ["TOKENIZERS_PARALLELISM"] = "false"
+
     # list of UDF queries to load
     queries = [
+        mnistcnn_udf_query,
         Fastrcnn_udf_query,
         ArrayCount_udf_query,
         Crop_udf_query,
         Open_udf_query,
         Similarity_udf_query,
         norfair_obj_tracker_query,
-        mnistcnn_udf_query,
         chatgpt_udf_query,
-        # Disabled because required packages (eg., easy_ocr might not be preinstalled)
-        # face_detection_udf_query,
-        # ocr_udf_query,
-        # Mvit_udf_query, - Disabled as it requires specific pytorch package
-        # Sift_udf_query, - requires package kornia
+        face_detection_udf_query,
+        # Mvit_udf_query,
+        Sift_udf_query,
+        Yolo_udf_query,
     ]
 
-    if mode == "release":
-        # if mode is 'release', add the Yolo query to the list
-        queries.append(Yolo_udf_query)
-    else:
-        # if mode is 'debug', add debug UDFs and a smaller Yolo model
+    # if mode is 'debug', add debug UDFs
+    if mode == "debug":
         queries.extend(
             [
                 DummyObjectDetector_udf_query,
                 DummyMultiObjectDetector_udf_query,
                 DummyFeatureExtractor_udf_query,
             ]
         )
 
-        yolo8n = """CREATE UDF IF NOT EXISTS Yolo
-            TYPE  ultralytics
-            'model' 'yolov8n.pt';
-        """
-        queries.append(yolo8n)
-
     # execute each query in the list of UDF queries
+    # ignore exceptions during the bootstrapping phase due to missing packages
     for query in queries:
-        execute_query_fetch_all(db, query)
+        try:
+            execute_query_fetch_all(
+                db, query, do_not_print_exceptions=True, do_not_raise_exceptions=True
+            )
+        except Exception:
+            pass
```

### Comparing `evadb-0.2.9/evadb/udfs/yolo_object_detector.py` & `evadb-0.3.0/evadb/udfs/yolo_object_detector.py`

 * *Files 4% similar despite different names*

```diff
@@ -16,36 +16,32 @@
 import pandas as pd
 
 from evadb.catalog.catalog_type import NdArrayType
 from evadb.udfs.abstract.abstract_udf import AbstractUDF
 from evadb.udfs.decorators.decorators import forward, setup
 from evadb.udfs.decorators.io_descriptors.data_types import PandasDataframe
 from evadb.udfs.gpu_compatible import GPUCompatible
-
-try:
-    from ultralytics import YOLO
-except ImportError as e:
-    raise ImportError(
-        f"Failed to import with error {e}, \
-        please try `pip install ultralytics`"
-    )
+from evadb.utils.generic_utils import try_to_import_ultralytics
 
 
 class Yolo(AbstractUDF, GPUCompatible):
     """
     Arguments:
         threshold (float): Threshold for classifier confidence score
     """
 
     @property
     def name(self) -> str:
         return "yolo"
 
     @setup(cacheable=True, udf_type="object_detection", batchable=True)
     def setup(self, model: str, threshold=0.3):
+        try_to_import_ultralytics()
+        from ultralytics import YOLO
+
         self.threshold = threshold
         self.model = YOLO(model)
         self.device = "cpu"
 
     @forward(
         input_signatures=[
             PandasDataframe(
```

### Comparing `evadb-0.2.9/evadb/utils/__init__.py` & `evadb-0.3.0/evadb/utils/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/utils/errors.py` & `evadb-0.3.0/evadb/utils/errors.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/utils/kv_cache.py` & `evadb-0.3.0/evadb/utils/kv_cache.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/utils/logging_manager.py` & `evadb-0.3.0/evadb/utils/logging_manager.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/utils/math_utils.py` & `evadb-0.3.0/evadb/utils/math_utils.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb/utils/s3_utils.py` & `evadb-0.3.0/evadb/utils/s3_utils.py`

 * *Files 10% similar despite different names*

```diff
@@ -12,15 +12,15 @@
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 
 import re
 from pathlib import Path
 
-import boto3
+from evadb.utils.generic_utils import try_to_import_moto
 
 
 # write a function that splits s3 uri into bucket and key
 def parse_s3_uri(s3_uri):
     """
     Parses the S3 URI and returns the bucket name and key
     """
@@ -29,14 +29,17 @@
     return bucket_name, key
 
 
 def download_from_s3(s3_uri, save_dir):
     """
     Downloads a file from s3 to the local file system
     """
+    try_to_import_moto()
+    import boto3
+
     s3_client = boto3.client("s3")
     s3_uri = s3_uri.as_posix()
     bucket_name, regex_key = parse_s3_uri(s3_uri)
     s3_bucket = boto3.resource("s3").Bucket(bucket_name)
     file_save_paths = []
     for obj in s3_bucket.objects.all():
         if re.search(re.sub("\*", ".*", regex_key), obj.key):  # noqa: W605
```

### Comparing `evadb-0.2.9/evadb/utils/stats.py` & `evadb-0.3.0/evadb/utils/stats.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/evadb.egg-info/PKG-INFO` & `evadb-0.3.0/README.md`

 * *Files 11% similar despite different names*

```diff
@@ -1,203 +1,166 @@
-Metadata-Version: 2.1
-Name: evadb
-Version: 0.2.9
-Summary: EvaDB AI-Relational Database System
-Home-page: https://github.com/georgia-tech-db/eva
-Download-URL: https://github.com/georgia-tech-db/eva
-Author: Georgia Tech Database Group
-Author-email: arulraj@gatech.edu
-License: Apache License 2.0
-Classifier: Development Status :: 5 - Production/Stable
-Classifier: License :: OSI Approved :: Apache Software License
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Requires-Python: >=3.8
-Description-Content-Type: text/markdown
-Provides-Extra: dev
-License-File: LICENSE.txt
-
 # EvaDB AI-SQL Database System
 
 <div>
         <a href="https://colab.research.google.com/github/georgia-tech-db/eva/blob/master/tutorials/03-emotion-analysis.ipynb">
             <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open EvaDB on Colab"/>
         </a>
         <a href="https://join.slack.com/t/eva-db/shared_invite/zt-1i10zyddy-PlJ4iawLdurDv~aIAq90Dg">
-            <img alt="Slack" src="https://img.shields.io/badge/slack-eva-ff69b4.svg?logo=slack">
+            <img alt="Slack" src="https://img.shields.io/badge/slack-evadb-ff69b4.svg?logo=slack">
         </a>          
         <a href="https://twitter.com/evadb_ai">
-            <img alt="Twitter" src="https://img.shields.io/badge/twitter-eva-bde1ee.svg?logo=twitter">
+            <img alt="Twitter" src="https://img.shields.io/badge/twitter-evadb-bde1ee.svg?logo=twitter">
         </a>  
         <a href="https://github.com/orgs/georgia-tech-db/projects/3">
-            <img src="https://img.shields.io/badge/eva-roadmap-a6c096" alt="Roadmap"/>
+            <img src="https://img.shields.io/badge/evadb-roadmap-a6c096" alt="Roadmap"/>
         </a>
         <img alt="PyPI" src="https://img.shields.io/pypi/v/evadb.svg"/>
         <img alt="License" src="https://img.shields.io/badge/license-Apache%202-brightgreen.svg?logo=apache"/>
         <img alt="Coverage Status" src="https://coveralls.io/repos/github/georgia-tech-db/eva/badge.svg?branch=master"/>     
         <a href="https://pepy.tech/project/evadb">
-          <img alt="Downloads" src="https://static.pepy.tech/badge/evadb/month"/>
+          <img alt="Downloads" src="https://static.pepy.tech/badge/evadb"/>
         </a>
         <img alt="Python Versions" src="https://img.shields.io/badge/Python--versions-3.8%20|%203.9%20|%203.10-brightgreen"/>       
 </div>
 
 <p align="center"> <b><h3>EvaDB is a database system for building simpler and faster AI-powered applications.</b></h3> </p>
 
-EvaDB is an AI-SQL database system for developing applications powered by AI models. We aim to simplify the development and deployment of AI-powered applications that operate on structured (tables, feature stores) and unstructured data (text documents, videos, PDFs, podcasts, etc.).
-
-EvaDB accelerates AI pipelines by 10x using a collection of performance optimizations inspired by time-tested SQL database systems, including data-parallel query execution, function caching, sampling, and cost-based predicate reordering. EvaDB supports an AI-oriented query language tailored for analyzing both structured and unstructured data. It has first-class support for PyTorch, Hugging Face, YOLO, and Open AI models.
+EvaDB is a database system for developing AI apps. We aim to simplify the development and deployment of AI-powered apps that operate on unstructured data (text documents, videos, PDFs, podcasts, etc.) and structured data (tables, vector index).
 
-The high-level Python and SQL APIs allows even beginners to use EvaDB in a few lines of code. Advanced users can define custom user-defined functions that wrap around any AI model or Python library. EvaDB is fully implemented in Python and licensed under the Apache license.
+The high-level Python and SQL APIs allow beginners to use EvaDB in a few lines of code. Advanced users can define custom user-defined functions that wrap around any AI model or Python library. EvaDB is fully implemented in Python and licensed under the Apache license.
 
 ## Quick Links
 
 - [Features](#features)
 - [Quick Start](#quick-start)
 - [Documentation](#documentation)
-- [Roadmap](https://github.com/orgs/georgia-tech-db/projects/3)
-- [Architecture Diagram](#architecture-diagram)
-- [Illustrative Applications](#illustrative-applications)
-- [Screenshots](#screenshots)
 - [Community and Support](#community-and-support)
 - [Twitter](https://twitter.com/evadb_ai)
-- [Contributing](#contributing)
-- [License](#license)
 
 ## Features
 
-- 🔮 Build simpler AI-powered applications using short Python or SQL queries
+- 🔮 Build simpler AI-powered applications using Python functions or SQL queries
 - ⚡️ 10x faster applications using AI-centric query optimization  
 - 💰 Save money spent on GPUs
 - 🚀 First-class support for your custom deep learning models through user-defined functions
 - 📦 Built-in caching to eliminate redundant model invocations across queries
 - ⌨️ First-class support for PyTorch, Hugging Face, YOLO, and Open AI models
 - 🐍 Installable via pip and fully implemented in Python
 
 ## Illustrative Applications
 
 Here are some illustrative EvaDB-powered applications (each Jupyter notebook can be opened on Google Colab):
 
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/11-similarity-search-for-motif-mining.html">Reddit Image Similarity Search</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/08-chatgpt.html">ChatGPT-based video question answering</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/12-query-pdf.html">Quering PDF documents</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/02-object-detection.html">Analysing traffic flow with YOLO</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/03-emotion-analysis.html">Examining emotion palette of a movie</a>
- * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/07-object-segmentation-huggingface.html">Image segmentation with Hugging Face</a>
- * 🔮 <a href="https://github.com/georgia-tech-db/license-plate-recognition">Recognizing license plates</a>
- * 🔮 <a href="https://github.com/georgia-tech-db/toxicity-classification">Analysing toxicity of social media memes </a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/13-privategpt.html">PrivateGPT</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/08-chatgpt.html">ChatGPT-based Video Question Answering</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/12-query-pdf.html">Querying PDF Documents</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/02-object-detection.html">Analysing Traffic Flow with YOLO</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/03-emotion-analysis.html">Examining Emotions of Movie</a>
+ * 🔮 <a href="https://evadb.readthedocs.io/en/stable/source/tutorials/07-object-segmentation-huggingface.html">Image Segmentation with Hugging Face</a>
 
 ## Documentation
 
-* [Detailed Documentation](https://evadb.readthedocs.io/)
+* [Documentation](https://evadb.readthedocs.io/)
   - The <a href="https://evadb.readthedocs.io/en/stable/source/overview/installation.html">Getting Started</a> page shows how you can use EvaDB for different AI tasks and how you can easily extend EvaDB to support your custom deep learning model through user-defined functions.
-  - The <a href="https://evadb.readthedocs.io/en/latest/source/tutorials/11-similarity-search-for-motif-mining.html">User Guides</a> section contains Jupyter Notebooks that demonstrate how to use various features of EvaDB. Each notebook includes a link to Google Colab, where you can run the code yourself.
-* [Tutorials](https://github.com/georgia-tech-db/eva/blob/master/tutorials/03-emotion-analysis.ipynb)
+  - The <a href="https://evadb.readthedocs.io/en/latest/source/tutorials/13-privategpt.html">User Guides</a> section contains Jupyter Notebooks that demonstrate how to use various features of EvaDB. Each notebook includes a link to Google Colab, where you can run the code yourself.
 * [Join us on Slack](https://join.slack.com/t/eva-db/shared_invite/zt-1i10zyddy-PlJ4iawLdurDv~aIAq90Dg)
 * [Follow us on Twitter](https://twitter.com/evadb_ai)
-* [Medium-Term Roadmap](https://github.com/orgs/georgia-tech-db/projects/3)
-* [Demo](https://evadb.readthedocs.io/en/stable/source/tutorials/08-chatgpt.html)
+* [Roadmap](https://github.com/orgs/georgia-tech-db/projects/3)
 
 ## Quick Start
 
-- Install EvaDB using the pip package manager. EvaDB supports Python versions >= 3.8:
+- Step 1: Install EvaDB using pip. EvaDB supports Python versions >= `3.8`:
 
 ```shell
 pip install evadb
 ```
 
-- To launch and connect to an EvaDB server in a Jupyter notebook, check out this [illustrative emotion analysis notebook](https://github.com/georgia-tech-db/eva/blob/master/tutorials/03-emotion-analysis.ipynb):
-```shell
-cursor = connect_to_server()
-```
-
-- Load a video onto the EvaDB server (we use [ua_detrac.mp4](data/ua_detrac/ua_detrac.mp4) for illustration):
-
-```mysql
-LOAD VIDEO "data/ua_detrac/ua_detrac.mp4" INTO TrafficVideo;
-```
-
-- That's it! You can now run queries over the loaded video:
-
-```mysql
-SELECT id, data FROM TrafficVideo WHERE id < 5;
-```
-
-- Search for frames in the video that contain a car:
-
-```mysql
-SELECT id, data FROM TrafficVideo WHERE ['car'] <@ Yolo(data).labels;
-```
-| Source Video  | Query Result |
-|---------------|--------------|
-|<img alt="Source Video" src="https://github.com/georgia-tech-db/eva/releases/download/v0.1.0/traffic-input.webp" width="300"> |<img alt="Query Result" src="https://github.com/georgia-tech-db/eva/releases/download/v0.1.0/traffic-output.webp" width="300"> |
-
-- Search for frames in the video that contain a pedestrian and a car:
-
-```mysql
-SELECT id, data FROM TrafficVideo WHERE ['pedestrian', 'car'] <@ Yolo(data).labels;
-```
-
-- Search for frames with more than three cars:
-
-```mysql
-SELECT id, data FROM TrafficVideo WHERE ArrayCount(Yolo(data).labels, 'car') > 3;
-```
-
-- **Use your custom deep learning model in queries** with a user-defined function (UDF):
+- Step 2: Write your AI app!
 
-```mysql
-CREATE UDF IF NOT EXISTS Yolo
-TYPE  ultralytics
-'model' 'yolov8m.pt';
-```
+```python
+import evadb
 
-- **Chain multiple models in a single query** to set up useful AI pipelines.
+# Grab a EvaDB cursor to load data and run queries
+cursor = evadb.connect().cursor()
 
-```mysql
-   -- Analyse emotions of faces in a video
-   SELECT id, bbox, EmotionDetector(Crop(data, bbox)) 
-   FROM MovieVideo JOIN LATERAL UNNEST(FaceDetector(data)) AS Face(bbox, conf)  
-   WHERE id < 15;
+# Load a collection of news videos into the 'news_videos' table
+# This command returns a Pandas Dataframe with the query's output
+# In this case, the output indicates the number of loaded videos
+cursor.load(
+    file_regex="news_videos/*.mp4",
+    format="VIDEO",
+    table_name="news_videos"
+).df()
+
+# Define a function that wraps around your deep learning model
+# Here, this function wraps around an off-the-shelf speech-to-text (Whisper) model
+# Such functions are known as user-defined functions or UDFs
+# So, we are creating a Whisper UDF here
+# After creating the UDF, we can use the function in any query
+cursor.create_udf(
+    udf_name="SpeechRecognizer",
+    type="HuggingFace",
+    task='automatic-speech-recognition',
+    model='openai/whisper-base'
+).df()
+
+# EvaDB automatically extract the audio from the video
+# We only need to run the SpeechRecongizer UDF on the 'audio' column
+# to get the transcript and persist it in a table called 'transcripts'
+cursor.query(
+    """CREATE TABLE transcripts AS
+       SELECT SpeechRecognizer(audio) from news_videos;"""
+).df()
+
+# We next incrementally construct the ChatGPT query using EvaDB's Python API
+# The query is based on the 'transcripts' table
+# This table has a column called 'text' with the transcript text
+query = cursor.table('transcripts')
+
+# Since ChatGPT is a built-in function, we don't have to define it
+# We can just directly use it in the query
+# We need to set the OPENAI_KEY as an environment variable
+os.environ["OPENAI_KEY"] = OPENAI_KEY
+query = query.select("ChatGPT('Is this video summary related to LLMs', text)")
+
+# Finally, we run the query to get the results as a dataframe
+response = query.df()
+```
+
+- **Chain multiple models in a single query to set up useful AI pipelines**
+
+```python
+# Analyse emotions of actors in an Interstellar movie clip using PyTorch models
+query = cursor.table("Interstellar")
+# Get faces using a `FaceDetector` function
+query = query.cross_apply("UNNEST(FaceDetector(data))", "Face(bounding_box, confidence)")
+# Focus only on frames 100 through 200 in the clip
+query = query.filter("id > 100 AND id < 200")
+# Get the emotions of the detected faces using a `EmotionDetector` function
+query = query.select("id, bbox, EmotionDetector(Crop(data, bounding_box))")
+
+# Run the query and get the query result as a dataframe
+response = query.df()
 ```
+- **EvaDB runs AI apps 10--100x faster using its AI-centric query optimizer**. Three key built-in optimizations are:
 
-- **EvaDB runs queries faster using its AI-centric query optimizer**. Two key optimizations are:
-
-   💾 **Caching**: EvaDB automatically caches and reuses previous query results (especially model inference results), eliminating redundant computation and reducing query processing time.
+   💾 **Caching**: EvaDB automatically caches and reuses model inference results.
 
-   🎯 **Predicate Reordering**: EvaDB optimizes the order in which the query predicates are evaluated (e.g., runs the faster, more selective model first), leading to faster queries and lower inference costs.
-
-Consider these two exploratory queries on a dataset of dog images:
-<img align="right" style="display:inline;" width="40%" src="https://github.com/georgia-tech-db/eva/blob/master/data/assets/eva_performance_comparison.png?raw=true"></a>
-
-```mysql
-  -- Query 1: Find all images of black-colored dogs
-  SELECT id, bbox FROM dogs 
-  JOIN LATERAL UNNEST(Yolo(data)) AS Obj(label, bbox, score) 
-  WHERE Obj.label = 'dog' 
-    AND Color(Crop(data, bbox)) = 'black'; 
-
-  -- Query 2: Find all Great Danes that are black-colored
-  SELECT id, bbox FROM dogs 
-  JOIN LATERAL UNNEST(Yolo(data)) AS Obj(label, bbox, score) 
-  WHERE Obj.label = 'dog' 
-    AND DogBreedClassifier(Crop(data, bbox)) = 'great dane' 
-    AND Color(Crop(data, bbox)) = 'black';
-```
+   ⚡️ **Parallel Query Execution**: EvaDB runs the app in parallel on all the available hardware resources (CPUs and GPUs).
 
-By reusing the results of the first query and reordering the predicates based on the available cached inference results, EvaDB runs the second query **10x faster**!
+   🎯 **Model Ordering**: EvaDB optimizes the order in which models are evaluated (e.g., runs the faster, more selective model first).
 
 ## Architecture Diagram
 
-This diagram presents the key components of EvaDB. EvaDB's AI-centric Query Optimizer takes a parsed query as input and generates a query plan that is then executed by the Query Engine. The Query Engine hits multiple storage engines to retrieve the data required for efficiently running the query:
+This diagram presents the key components of EvaDB. EvaDB's AI-centric query optimizer takes a query as input and generates a query plan that is executed by the query engine. The query engine hits the relevant storage engines to quickly retrieve the data required for efficiently running the query:
 1. Structured data (SQL database system connected via `sqlalchemy`).
-2. Unstructured media data (on cloud buckets or local filesystem).
-3. Vector data (vector database system).
+2. Unstructured media data (on cloud buckets/local filesystem).
+3. Feature data (vector database system).
 
-<img width="700" alt="Architecture Diagram" src="https://github.com/georgia-tech-db/eva/assets/5521975/01452ec9-87d9-4d27-90b2-c0b1ab29b16c">
+<img width="500" alt="Architecture Diagram" src="https://github.com/georgia-tech-db/eva/assets/5521975/01452ec9-87d9-4d27-90b2-c0b1ab29b16c">
 
 ## Screenshots
 
 ### 🔮 [Traffic Analysis](https://evadb.readthedocs.io/en/stable/source/tutorials/02-object-detection.html) (Object Detection Model)
 | Source Video  | Query Result |
 |---------------|--------------|
 |<img alt="Source Video" src="https://github.com/georgia-tech-db/eva/releases/download/v0.1.0/traffic-input.webp" width="300"> |<img alt="Query Result" src="https://github.com/georgia-tech-db/eva/releases/download/v0.1.0/traffic-output.webp" width="300"> |
```

#### html2text {}

```diff
@@ -1,110 +1,88 @@
-Metadata-Version: 2.1 Name: evadb Version: 0.2.9 Summary: EvaDB AI-Relational
-Database System Home-page: https://github.com/georgia-tech-db/eva Download-URL:
-https://github.com/georgia-tech-db/eva Author: Georgia Tech Database Group
-Author-email: arulraj@gatech.edu License: Apache License 2.0 Classifier:
-Development Status :: 5 - Production/Stable Classifier: License :: OSI Approved
-:: Apache Software License Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9 Classifier: Programming
-Language :: Python :: 3.10 Requires-Python: >=3.8 Description-Content-Type:
-text/markdown Provides-Extra: dev License-File: LICENSE.txt # EvaDB AI-SQL
-Database System
+# EvaDB AI-SQL Database System
 [Open_EvaDB_on_Colab] [Slack] [Twitter] [Roadmap] [PyPI] [License] [Coverage
 Status] [Downloads] [Python Versions]
 **** EvaDB is a database system for building simpler and faster AI-powered
 applications. ****
-EvaDB is an AI-SQL database system for developing applications powered by AI
-models. We aim to simplify the development and deployment of AI-powered
-applications that operate on structured (tables, feature stores) and
-unstructured data (text documents, videos, PDFs, podcasts, etc.). EvaDB
-accelerates AI pipelines by 10x using a collection of performance optimizations
-inspired by time-tested SQL database systems, including data-parallel query
-execution, function caching, sampling, and cost-based predicate reordering.
-EvaDB supports an AI-oriented query language tailored for analyzing both
-structured and unstructured data. It has first-class support for PyTorch,
-Hugging Face, YOLO, and Open AI models. The high-level Python and SQL APIs
-allows even beginners to use EvaDB in a few lines of code. Advanced users can
-define custom user-defined functions that wrap around any AI model or Python
-library. EvaDB is fully implemented in Python and licensed under the Apache
-license. ## Quick Links - [Features](#features) - [Quick Start](#quick-start) -
-[Documentation](#documentation) - [Roadmap](https://github.com/orgs/georgia-
-tech-db/projects/3) - [Architecture Diagram](#architecture-diagram) -
-[Illustrative Applications](#illustrative-applications) - [Screenshots]
-(#screenshots) - [Community and Support](#community-and-support) - [Twitter]
-(https://twitter.com/evadb_ai) - [Contributing](#contributing) - [License]
-(#license) ## Features - ð® Build simpler AI-powered applications using short
-Python or SQL queries - â¡ï¸ 10x faster applications using AI-centric query
-optimization - ð° Save money spent on GPUs - ð First-class support for
-your custom deep learning models through user-defined functions - ð¦ Built-in
-caching to eliminate redundant model invocations across queries - â¨ï¸ First-
-class support for PyTorch, Hugging Face, YOLO, and Open AI models - ð
-Installable via pip and fully implemented in Python ## Illustrative
-Applications Here are some illustrative EvaDB-powered applications (each
-Jupyter notebook can be opened on Google Colab): * ð® Reddit_Image_Similarity
-Search * ð® ChatGPT-based_video_question_answering * ð® Quering_PDF
-documents * ð® Analysing_traffic_flow_with_YOLO * ð® Examining_emotion
-palette_of_a_movie * ð® Image_segmentation_with_Hugging_Face * ð®
-Recognizing_license_plates * ð® Analysing_toxicity_of_social_media_memes ##
-Documentation * [Detailed Documentation](https://evadb.readthedocs.io/) - The
-Getting_Started page shows how you can use EvaDB for different AI tasks and how
-you can easily extend EvaDB to support your custom deep learning model through
-user-defined functions. - The User_Guides section contains Jupyter Notebooks
-that demonstrate how to use various features of EvaDB. Each notebook includes a
-link to Google Colab, where you can run the code yourself. * [Tutorials](https:
-//github.com/georgia-tech-db/eva/blob/master/tutorials/03-emotion-
-analysis.ipynb) * [Join us on Slack](https://join.slack.com/t/eva-db/
-shared_invite/zt-1i10zyddy-PlJ4iawLdurDv~aIAq90Dg) * [Follow us on Twitter]
-(https://twitter.com/evadb_ai) * [Medium-Term Roadmap](https://github.com/orgs/
-georgia-tech-db/projects/3) * [Demo](https://evadb.readthedocs.io/en/stable/
-source/tutorials/08-chatgpt.html) ## Quick Start - Install EvaDB using the pip
-package manager. EvaDB supports Python versions >= 3.8: ```shell pip install
-evadb ``` - To launch and connect to an EvaDB server in a Jupyter notebook,
-check out this [illustrative emotion analysis notebook](https://github.com/
-georgia-tech-db/eva/blob/master/tutorials/03-emotion-analysis.ipynb): ```shell
-cursor = connect_to_server() ``` - Load a video onto the EvaDB server (we use
-[ua_detrac.mp4](data/ua_detrac/ua_detrac.mp4) for illustration): ```mysql LOAD
-VIDEO "data/ua_detrac/ua_detrac.mp4" INTO TrafficVideo; ``` - That's it! You
-can now run queries over the loaded video: ```mysql SELECT id, data FROM
-TrafficVideo WHERE id < 5; ``` - Search for frames in the video that contain a
-car: ```mysql SELECT id, data FROM TrafficVideo WHERE ['car'] <@ Yolo
-(data).labels; ``` | Source Video | Query Result | |---------------|-----------
----| |[Source Video] |[Query Result] | - Search for frames in the video that
-contain a pedestrian and a car: ```mysql SELECT id, data FROM TrafficVideo
-WHERE ['pedestrian', 'car'] <@ Yolo(data).labels; ``` - Search for frames with
-more than three cars: ```mysql SELECT id, data FROM TrafficVideo WHERE
-ArrayCount(Yolo(data).labels, 'car') > 3; ``` - **Use your custom deep learning
-model in queries** with a user-defined function (UDF): ```mysql CREATE UDF IF
-NOT EXISTS Yolo TYPE ultralytics 'model' 'yolov8m.pt'; ``` - **Chain multiple
-models in a single query** to set up useful AI pipelines. ```mysql -- Analyse
-emotions of faces in a video SELECT id, bbox, EmotionDetector(Crop(data, bbox))
-FROM MovieVideo JOIN LATERAL UNNEST(FaceDetector(data)) AS Face(bbox, conf)
-WHERE id < 15; ``` - **EvaDB runs queries faster using its AI-centric query
-optimizer**. Two key optimizations are: ð¾ **Caching**: EvaDB automatically
-caches and reuses previous query results (especially model inference results),
-eliminating redundant computation and reducing query processing time. ð¯
-**Predicate Reordering**: EvaDB optimizes the order in which the query
-predicates are evaluated (e.g., runs the faster, more selective model first),
-leading to faster queries and lower inference costs. Consider these two
-exploratory queries on a dataset of dog images: [https://github.com/georgia-
-tech-db/eva/blob/master/data/assets/eva_performance_comparison.png?raw=true]
- ```mysql -- Query 1: Find all images of black-colored dogs SELECT id, bbox
-FROM dogs JOIN LATERAL UNNEST(Yolo(data)) AS Obj(label, bbox, score) WHERE
-Obj.label = 'dog' AND Color(Crop(data, bbox)) = 'black'; -- Query 2: Find all
-Great Danes that are black-colored SELECT id, bbox FROM dogs JOIN LATERAL
-UNNEST(Yolo(data)) AS Obj(label, bbox, score) WHERE Obj.label = 'dog' AND
-DogBreedClassifier(Crop(data, bbox)) = 'great dane' AND Color(Crop(data, bbox))
-= 'black'; ``` By reusing the results of the first query and reordering the
-predicates based on the available cached inference results, EvaDB runs the
-second query **10x faster**! ## Architecture Diagram This diagram presents the
-key components of EvaDB. EvaDB's AI-centric Query Optimizer takes a parsed
-query as input and generates a query plan that is then executed by the Query
-Engine. The Query Engine hits multiple storage engines to retrieve the data
+EvaDB is a database system for developing AI apps. We aim to simplify the
+development and deployment of AI-powered apps that operate on unstructured data
+(text documents, videos, PDFs, podcasts, etc.) and structured data (tables,
+vector index). The high-level Python and SQL APIs allow beginners to use EvaDB
+in a few lines of code. Advanced users can define custom user-defined functions
+that wrap around any AI model or Python library. EvaDB is fully implemented in
+Python and licensed under the Apache license. ## Quick Links - [Features]
+(#features) - [Quick Start](#quick-start) - [Documentation](#documentation) -
+[Community and Support](#community-and-support) - [Twitter](https://
+twitter.com/evadb_ai) ## Features - ð® Build simpler AI-powered applications
+using Python functions or SQL queries - â¡ï¸ 10x faster applications using
+AI-centric query optimization - ð° Save money spent on GPUs - ð First-
+class support for your custom deep learning models through user-defined
+functions - ð¦ Built-in caching to eliminate redundant model invocations
+across queries - â¨ï¸ First-class support for PyTorch, Hugging Face, YOLO,
+and Open AI models - ð Installable via pip and fully implemented in Python
+## Illustrative Applications Here are some illustrative EvaDB-powered
+applications (each Jupyter notebook can be opened on Google Colab): * ð®
+PrivateGPT * ð® ChatGPT-based_Video_Question_Answering * ð® Querying_PDF
+Documents * ð® Analysing_Traffic_Flow_with_YOLO * ð® Examining_Emotions_of
+Movie * ð® Image_Segmentation_with_Hugging_Face ## Documentation *
+[Documentation](https://evadb.readthedocs.io/) - The Getting_Started page shows
+how you can use EvaDB for different AI tasks and how you can easily extend
+EvaDB to support your custom deep learning model through user-defined
+functions. - The User_Guides section contains Jupyter Notebooks that
+demonstrate how to use various features of EvaDB. Each notebook includes a link
+to Google Colab, where you can run the code yourself. * [Join us on Slack]
+(https://join.slack.com/t/eva-db/shared_invite/zt-1i10zyddy-
+PlJ4iawLdurDv~aIAq90Dg) * [Follow us on Twitter](https://twitter.com/evadb_ai)
+* [Roadmap](https://github.com/orgs/georgia-tech-db/projects/3) ## Quick Start
+- Step 1: Install EvaDB using pip. EvaDB supports Python versions >= `3.8`:
+```shell pip install evadb ``` - Step 2: Write your AI app! ```python import
+evadb # Grab a EvaDB cursor to load data and run queries cursor = evadb.connect
+().cursor() # Load a collection of news videos into the 'news_videos' table #
+This command returns a Pandas Dataframe with the query's output # In this case,
+the output indicates the number of loaded videos cursor.load
+( file_regex="news_videos/*.mp4", format="VIDEO", table_name="news_videos" ).df
+() # Define a function that wraps around your deep learning model # Here, this
+function wraps around an off-the-shelf speech-to-text (Whisper) model # Such
+functions are known as user-defined functions or UDFs # So, we are creating a
+Whisper UDF here # After creating the UDF, we can use the function in any query
+cursor.create_udf( udf_name="SpeechRecognizer", type="HuggingFace",
+task='automatic-speech-recognition', model='openai/whisper-base' ).df() # EvaDB
+automatically extract the audio from the video # We only need to run the
+SpeechRecongizer UDF on the 'audio' column # to get the transcript and persist
+it in a table called 'transcripts' cursor.query( """CREATE TABLE transcripts AS
+SELECT SpeechRecognizer(audio) from news_videos;""" ).df() # We next
+incrementally construct the ChatGPT query using EvaDB's Python API # The query
+is based on the 'transcripts' table # This table has a column called 'text'
+with the transcript text query = cursor.table('transcripts') # Since ChatGPT is
+a built-in function, we don't have to define it # We can just directly use it
+in the query # We need to set the OPENAI_KEY as an environment variable
+os.environ["OPENAI_KEY"] = OPENAI_KEY query = query.select("ChatGPT('Is this
+video summary related to LLMs', text)") # Finally, we run the query to get the
+results as a dataframe response = query.df() ``` - **Chain multiple models in a
+single query to set up useful AI pipelines** ```python # Analyse emotions of
+actors in an Interstellar movie clip using PyTorch models query = cursor.table
+("Interstellar") # Get faces using a `FaceDetector` function query =
+query.cross_apply("UNNEST(FaceDetector(data))", "Face(bounding_box,
+confidence)") # Focus only on frames 100 through 200 in the clip query =
+query.filter("id > 100 AND id < 200") # Get the emotions of the detected faces
+using a `EmotionDetector` function query = query.select("id, bbox,
+EmotionDetector(Crop(data, bounding_box))") # Run the query and get the query
+result as a dataframe response = query.df() ``` - **EvaDB runs AI apps 10--100x
+faster using its AI-centric query optimizer**. Three key built-in optimizations
+are: ð¾ **Caching**: EvaDB automatically caches and reuses model inference
+results. â¡ï¸ **Parallel Query Execution**: EvaDB runs the app in parallel on
+all the available hardware resources (CPUs and GPUs). ð¯ **Model Ordering**:
+EvaDB optimizes the order in which models are evaluated (e.g., runs the faster,
+more selective model first). ## Architecture Diagram This diagram presents the
+key components of EvaDB. EvaDB's AI-centric query optimizer takes a query as
+input and generates a query plan that is executed by the query engine. The
+query engine hits the relevant storage engines to quickly retrieve the data
 required for efficiently running the query: 1. Structured data (SQL database
 system connected via `sqlalchemy`). 2. Unstructured media data (on cloud
-buckets or local filesystem). 3. Vector data (vector database system).
+buckets/local filesystem). 3. Feature data (vector database system).
 [Architecture Diagram] ## Screenshots ### ð® [Traffic Analysis](https://
 evadb.readthedocs.io/en/stable/source/tutorials/02-object-detection.html)
 (Object Detection Model) | Source Video | Query Result | |---------------|-----
 ---------| |[Source Video] |[Query Result] | ### ð® [PDF Question Answering]
 (https://evadb.readthedocs.io/en/stable/source/tutorials/12-query-pdf.html)
 (Question Answering Model) | App | |-----| |[Source Video] | ### ð® [MNIST
 Digit Recognition](https://evadb.readthedocs.io/en/stable/source/tutorials/01-
```

### Comparing `evadb-0.2.9/evadb.egg-info/SOURCES.txt` & `evadb-0.3.0/evadb.egg-info/SOURCES.txt`

 * *Files 2% similar despite different names*

```diff
@@ -52,15 +52,14 @@
 evadb/configuration/configuration_manager.py
 evadb/configuration/constants.py
 evadb/executor/__init__.py
 evadb/executor/abstract_executor.py
 evadb/executor/apply_and_merge_executor.py
 evadb/executor/create_executor.py
 evadb/executor/create_index_executor.py
-evadb/executor/create_mat_view_executor.py
 evadb/executor/create_udf_executor.py
 evadb/executor/delete_executor.py
 evadb/executor/drop_object_executor.py
 evadb/executor/exchange_executor.py
 evadb/executor/execution_context.py
 evadb/executor/executor_utils.py
 evadb/executor/explain_executor.py
@@ -129,15 +128,14 @@
 evadb/optimizer/rules/pattern.py
 evadb/optimizer/rules/rules.py
 evadb/optimizer/rules/rules_base.py
 evadb/optimizer/rules/rules_manager.py
 evadb/parser/__init__.py
 evadb/parser/alias.py
 evadb/parser/create_index_statement.py
-evadb/parser/create_mat_view_statement.py
 evadb/parser/create_statement.py
 evadb/parser/create_udf_statement.py
 evadb/parser/delete_statement.py
 evadb/parser/drop_object_statement.py
 evadb/parser/evadb.lark
 evadb/parser/explain_statement.py
 evadb/parser/insert_statement.py
@@ -167,15 +165,14 @@
 evadb/parser/lark_visitor/_table_sources.py
 evadb/plan_nodes/__init__.py
 evadb/plan_nodes/abstract_join_plan.py
 evadb/plan_nodes/abstract_plan.py
 evadb/plan_nodes/abstract_scan_plan.py
 evadb/plan_nodes/apply_and_merge_plan.py
 evadb/plan_nodes/create_index_plan.py
-evadb/plan_nodes/create_mat_view_plan.py
 evadb/plan_nodes/create_plan.py
 evadb/plan_nodes/create_udf_plan.py
 evadb/plan_nodes/delete_plan.py
 evadb/plan_nodes/drop_object_plan.py
 evadb/plan_nodes/exchange_plan.py
 evadb/plan_nodes/explain_plan.py
 evadb/plan_nodes/function_scan_plan.py
@@ -235,22 +232,22 @@
 evadb/udfs/__init__.py
 evadb/udfs/asl_action_recognition.py
 evadb/udfs/chatgpt.py
 evadb/udfs/emotion_detector.py
 evadb/udfs/face_detector.py
 evadb/udfs/fastrcnn_object_detector.py
 evadb/udfs/feature_extractor.py
+evadb/udfs/fuzzy_join.py
 evadb/udfs/gpu_compatible.py
 evadb/udfs/mnist_image_classifier.py
 evadb/udfs/mvit_action_recognition.py
-evadb/udfs/ocr_extractor.py
 evadb/udfs/saliency_feature_extractor.py
 evadb/udfs/sentence_feature_extractor.py
-evadb/udfs/sentence_transformer_feature_extractor.py
 evadb/udfs/sift_feature_extractor.py
+evadb/udfs/text_filter_keyword.py
 evadb/udfs/udf_bootstrap_queries.py
 evadb/udfs/yolo_object_detector.py
 evadb/udfs/abstract/__init__.py
 evadb/udfs/abstract/abstract_udf.py
 evadb/udfs/abstract/hf_abstract_udf.py
 evadb/udfs/abstract/pytorch_abstract_udf.py
 evadb/udfs/abstract/tracker_abstract_udf.py
@@ -269,29 +266,33 @@
 evadb/udfs/ndarray/horizontal_flip.py
 evadb/udfs/ndarray/open.py
 evadb/udfs/ndarray/similarity.py
 evadb/udfs/ndarray/to_grayscale.py
 evadb/udfs/ndarray/vertical_flip.py
 evadb/udfs/trackers/__init__.py
 evadb/udfs/trackers/nor_fair.py
-evadb/udfs/tutorials/__init__.py
 evadb/utils/__init__.py
 evadb/utils/errors.py
 evadb/utils/generic_utils.py
 evadb/utils/kv_cache.py
 evadb/utils/logging_manager.py
 evadb/utils/math_utils.py
 evadb/utils/s3_utils.py
 evadb/utils/stats.py
 test/__init__.py
 test/markers.py
 test/test_eva_cmd_client.py
 test/test_eva_imports.py
 test/test_eva_server.py
 test/util.py
+test/app_tests/__init__.py
+test/app_tests/test_pandas_qa.py
+test/app_tests/test_privategpt.py
+test/app_tests/test_youtube_channel_qa.py
+test/app_tests/test_youtube_qa.py
 test/benchmark_tests/__init__.py
 test/benchmark_tests/conftest.py
 test/benchmark_tests/test_benchmark_pytorch.py
 test/binder/__init__.py
 test/binder/test_statement_binder.py
 test/binder/test_statement_binder_context.py
 test/catalog/__init__.py
@@ -328,25 +329,25 @@
 test/integration_tests/test_explain_executor.py
 test/integration_tests/test_fuzzy_join.py
 test/integration_tests/test_huggingface_udfs.py
 test/integration_tests/test_insert_executor.py
 test/integration_tests/test_like.py
 test/integration_tests/test_load_executor.py
 test/integration_tests/test_load_pdf_executor.py
-test/integration_tests/test_mat_executor.py
 test/integration_tests/test_open.py
 test/integration_tests/test_optimizer_rules.py
 test/integration_tests/test_pytorch.py
 test/integration_tests/test_rename_executor.py
 test/integration_tests/test_reuse.py
 test/integration_tests/test_s3_load_executor.py
 test/integration_tests/test_saliency.py
 test/integration_tests/test_select_executor.py
 test/integration_tests/test_show_info_executor.py
 test/integration_tests/test_similarity.py
+test/integration_tests/test_text_filtering.py
 test/integration_tests/test_udf_executor.py
 test/interfaces/__init__.py
 test/interfaces/relational/__init__.py
 test/interfaces/relational/test_relational_api.py
 test/models/__init__.py
 test/models/catalog/__init__.py
 test/models/catalog/test_frame_info.py
@@ -370,14 +371,15 @@
 test/plan_nodes/__init__.py
 test/plan_nodes/test_plan.py
 test/readers/__init__.py
 test/readers/test_csv_reader.py
 test/readers/test_decord_reader.py
 test/server/__init__.py
 test/server/test_command_handler.py
+test/server/test_configuration_file.py
 test/server/test_db_api.py
 test/server/test_interpreter.py
 test/server/test_server.py
 test/storage/__init__.py
 test/storage/test_sqlite_storage_engine.py
 test/storage/test_video_storage.py
 test/udfs/__init__.py
```

### Comparing `evadb-0.2.9/setup.py` & `evadb-0.3.0/setup.py`

 * *Files 16% similar despite different names*

```diff
@@ -18,14 +18,18 @@
 
 DESCRIPTION = "EvaDB AI-Relational Database System"
 NAME = "evadb"
 AUTHOR = "Georgia Tech Database Group"
 AUTHOR_EMAIL = "arulraj@gatech.edu"
 URL = "https://github.com/georgia-tech-db/eva"
 
+# Check Python version
+# import sys
+# if sys.version_info < (3, 8):
+#     sys.exit("Python 3.8 or later is required.")
 
 def read(path, encoding="utf-8"):
     path = os.path.join(os.path.dirname(__file__), path)
     with io.open(path, encoding=encoding) as fp:
         return fp.read()
 
 
@@ -34,122 +38,117 @@
 with open("evadb/version.py", "r") as version_file:
     exec(version_file.read(), VERSION_DICT)
 
 DOWNLOAD_URL = "https://github.com/georgia-tech-db/eva"
 LICENSE = "Apache License 2.0"
 VERSION = VERSION_DICT["VERSION"]
 
-minimal_requirement = [
+minimal_requirements = [
     "numpy>=1.19.5",
     "pandas>=1.1.5",
-    "opencv-contrib-python-headless>=4.6.0.66",
-    "Pillow>=8.4.0",
-    "sqlalchemy>=1.4.0,<2.0.0",  # major changes in 2.0.0
+    "sqlalchemy>=1.4.0,<2.0.0",  # BREAKING CHANGES IN 2.0.0
     "sqlalchemy-utils>=0.36.6",
     "lark>=1.0.0",
     "pyyaml>=5.1",
-    "importlib-metadata<5.0",
-    "ray>=1.13.0,<2.5.0", # breaking change in 2.5.0
-    "retry>=0.9.2",
     "aenum>=2.2.0",
     "diskcache>=5.4.0",
-    "eva-decord>=0.6.1",
-    "boto3",
-    "nest_asyncio",
-    "langchain",
+    "retry>=0.9.2",
+    "psutil",
+]
+
+vision_libs = [
+    "torch>=1.10.0",
+    "torchvision>=0.11.1",
+    "transformers>=4.27.4,<4.30.2",  # HUGGINGFACE
+    "faiss-cpu",  # DEFAULT VECTOR INDEX
+    "opencv-python-headless>=4.6.0.66",
+    "Pillow>=8.4.0",
+    "eva-decord>=0.6.1",  # VIDEO PROCESSING
+    "ultralytics>=8.0.93",  # OBJECT DETECTION
+    "timm>=0.6.13",  # HUGGINGFACE VISION TASKS
+    "sentencepiece",  # TRANSFORMERS
+]
+
+document_libs = [
+    "transformers>=4.27.4,<4.30.2",  # HUGGINGFACE
+    "langchain",  # DATA LOADERS
+    "faiss-cpu",  # DEFAULT VECTOR INDEX
     "pymupdf",
     "pdfminer.six",
-    "sentence-transformers"
-
+    "sentence-transformers",
+    "protobuf<=3.20.1",
+    "bs4",
+    "openai>=0.27.4",  # CHATGPT
+    "gpt4all",  # PRIVATE GPT
+    "sentencepiece",  # TRANSFORMERS
 ]
 
-formatter_libs = ["black>=23.1.0", "isort>=5.10.1"]
+udf_libs = [
+    "facenet-pytorch>=2.5.2",  # FACE DETECTION
+    "thefuzz",  # FUZZY STRING MATCHING
+    "pytube",  # YOUTUBE QA APP
+    "youtube-transcript-api",  # YOUTUBE QA APP
+    "boto3",  # AWS
+    "norfair>=2.2.0",  # OBJECT TRACKING
+    "kornia",  # SIFT FEATURES
+]
 
-test_libs = [
-    "pytest>=6.1.2",
-    "pytest-cov>=2.11.1",
-    "pytest-random-order>=1.0.4",
-    "pytest-virtualenv",
-    "pytest-asyncio",
-    "pytest-xdist",
-    "coveralls>=3.0.1",
-    "flake8>=3.9.1",
-    "moto[s3]>=4.1.1",
+ray_libs = [
+    "ray>=1.13.0,<2.5.0",  # BREAKING CHANGES IN 2.5.0
 ]
 
 notebook_libs = [
+    "ipython<8.13.0",
     "ipywidgets>=7.7.2",
     "matplotlib>=3.3.4",
     "nbmake>=1.2.1",
     "nest-asyncio>=1.5.6",
 ]
 
-### NEEDED FOR INTEGRATION TESTS ONLY
-integration_test_libs = [
-    "torch>=1.10.0",
-    "torchvision>=0.11.1",
-    "faiss-cpu",  # faiss-gpu does not work on mac
-]
-
-benchmark_libs = [
-    "pytest-benchmark",
+qdrant_libs = [
+    "qdrant_client" # cannot install on 3.11 due to grcpio
 ]
 
-doc_libs = ["codespell", "pylint"]
+### NEEDED FOR DEVELOPER TESTING ONLY
 
-dist_libs = [
+dev_libs = [
+    # TESTING PACKAGES
+    "pytest>=6.1.2",
+    "pytest-cov>=2.11.1",
+    "mock",
+    "coveralls>=3.0.1",
+    "moto[s3]>=4.1.1",
+    # BENCHMARK PACKAGES
+    "pytest-benchmark",
+    # LINTING PACKAGES
+    "codespell",
+    "pylint",
+    "black>=23.1.0",
+    "isort>=5.10.1",
+    "flake8>=3.9.1",
+    # DISTRIBUTION PACKAGES
     "wheel>=0.37.1",
     "semantic_version",
     "PyGithub",
     "twine",
-    "PyDriller"
-]
-
-### NEEDED FOR AN ALTERNATE DATA SYSTEM OTHER THAN SQLITE
-database_libs = ["pymysql>=0.10.1"]
-
-### NEEDED FOR A BATTERIES-LOADED EXPERIENCE
-udf_libs = [
-    "facenet-pytorch>=2.5.2",  # FACE DETECTION
-    "ipython<8.13.0",  # NOTEBOOKS
-    "thefuzz",  # FUZZY STRING MATCHING
-    "ultralytics>=8.0.93",  # OBJECT DETECTION
-    "transformers>=4.27.4",  # HUGGINGFACE
-    "openai>=0.27.4",  # CHATGPT
-    "retry>=0.9.2", #CHATGPT
-    "timm>=0.6.13",  # HUGGINGFACE VISION TASKS
-    "norfair>=2.2.0",  # OBJECT TRACKING
+    "PyDriller",
 ]
 
-### NEEDED FOR EXPERIMENTAL FEATURES
-third_party_libs = [
-    "qdrant-client>=1.1.7",  # Qdrant vector store client
-    "kornia",  # SIFT features
-    "langchain>=0.0.177",  # langchain document loaders
-    "pdfminer.six",  # for reading pdfs
-]
-
-### NEEDED FOR EXPERIMENTAL FEATURES
-experimental_libs = []
-
-INSTALL_REQUIRES = minimal_requirement + integration_test_libs + udf_libs
-DEV_REQUIRES = (
-    INSTALL_REQUIRES
-    + formatter_libs
-    + test_libs
-    + notebook_libs
-    + benchmark_libs
-    + doc_libs
-    + database_libs
-    + dist_libs
-    + experimental_libs
-    + third_party_libs
-)
+INSTALL_REQUIRES = minimal_requirements
 
-EXTRA_REQUIRES = {"dev": DEV_REQUIRES}
+EXTRA_REQUIRES = {
+    "ray": ray_libs,
+    "vision": vision_libs,
+    "document": document_libs,
+    "udf": udf_libs,
+    "notebook": notebook_libs,
+    "qdrant": qdrant_libs,
+    # everything except ray and qdrant
+    "dev": dev_libs + vision_libs + document_libs + udf_libs + notebook_libs,
+}
 
 setup(
     name=NAME,
     version=VERSION,
     description=DESCRIPTION,
     long_description=LONG_DESCRIPTION,
     long_description_content_type="text/markdown",
@@ -166,16 +165,16 @@
         "Programming Language :: Python :: 3.10",
         # "Programming Language :: Python :: 3.11",
     ],
     packages=find_packages(exclude=["tests", "tests.*"]),
     # https://python-packaging.readthedocs.io/en/latest/command-line-scripts.html#the-console-scripts-entry-point
     entry_points={
         "console_scripts": [
-            "eva_server=evadb.evadb_server:main",
-            "eva_client=evadb.evadb_cmd_client:main",
+            "evadb_server=evadb.evadb_server:main",
+            "evadb_client=evadb.evadb_cmd_client:main",
         ]
     },
     python_requires=">=3.8",
     install_requires=INSTALL_REQUIRES,
     extras_require=EXTRA_REQUIRES,
     include_package_data=True,
     package_data={"evadb": ["evadb.yml", "parser/evadb.lark"]},
```

### Comparing `evadb-0.2.9/test/__init__.py` & `evadb-0.3.0/test/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/benchmark_tests/__init__.py` & `evadb-0.3.0/test/app_tests/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/benchmark_tests/conftest.py` & `evadb-0.3.0/test/benchmark_tests/conftest.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/benchmark_tests/test_benchmark_pytorch.py` & `evadb-0.3.0/test/benchmark_tests/test_benchmark_pytorch.py`

 * *Files 2% similar despite different names*

```diff
@@ -23,29 +23,29 @@
 @pytest.mark.torchtest
 @pytest.mark.benchmark(
     warmup=False,
     warmup_iterations=1,
     min_rounds=1,
 )
 @pytest.mark.notparallel
-def test_should_run_pytorch_and_yolo(benchmark, setup_pytorch_tests):
+def test_should_run_benchmark_pytorch_and_yolo(benchmark, setup_pytorch_tests):
     select_query = """SELECT Yolo(data) FROM MyVideo
                     WHERE id < 5;"""
     actual_batch = benchmark(execute_query_fetch_all, setup_pytorch_tests, select_query)
     assert len(actual_batch) == 5
 
 
 @pytest.mark.torchtest
 @pytest.mark.benchmark(
     warmup=False,
     warmup_iterations=1,
     min_rounds=1,
 )
 @pytest.mark.notparallel
-def test_should_run_pytorch_and_facenet(benchmark, setup_pytorch_tests):
+def test_should_run_benchmark_pytorch_and_facenet(benchmark, setup_pytorch_tests):
     create_udf_query = """CREATE UDF IF NOT EXISTS FaceDetector
                 INPUT  (frame NDARRAY UINT8(3, ANYDIM, ANYDIM))
                 OUTPUT (bboxes NDARRAY FLOAT32(ANYDIM, 4),
                         scores NDARRAY FLOAT32(ANYDIM))
                 TYPE  FaceDetection
                 IMPL  'evadb/udfs/face_detector.py';
     """
@@ -61,15 +61,15 @@
 @pytest.mark.torchtest
 @pytest.mark.benchmark(
     warmup=False,
     warmup_iterations=1,
     min_rounds=1,
 )
 @pytest.mark.notparallel
-def test_should_run_pytorch_and_resnet50(benchmark, setup_pytorch_tests):
+def test_should_run_benchmark_pytorch_and_resnet50(benchmark, setup_pytorch_tests):
     create_udf_query = """CREATE UDF IF NOT EXISTS FeatureExtractor
                 INPUT  (frame NDARRAY UINT8(3, ANYDIM, ANYDIM))
                 OUTPUT (features NDARRAY FLOAT32(ANYDIM))
                 TYPE  Classification
                 IMPL  'evadb/udfs/feature_extractor.py';
     """
     execute_query_fetch_all(setup_pytorch_tests, create_udf_query)
```

### Comparing `evadb-0.2.9/test/binder/__init__.py` & `evadb-0.3.0/test/benchmark_tests/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/binder/test_statement_binder.py` & `evadb-0.3.0/test/binder/test_statement_binder.py`

 * *Files 4% similar despite different names*

```diff
@@ -14,30 +14,29 @@
 # limitations under the License.
 import unittest
 from unittest.mock import MagicMock, patch
 
 from evadb.binder.binder_utils import BinderError
 from evadb.binder.statement_binder import StatementBinder
 from evadb.binder.statement_binder_context import StatementBinderContext
-from evadb.catalog.catalog_type import NdArrayType
+from evadb.catalog.catalog_type import ColumnType, NdArrayType
 from evadb.expression.tuple_value_expression import TupleValueExpression
 from evadb.parser.alias import Alias
-from evadb.parser.create_statement import ColumnDefinition
 
 
 class StatementBinderTests(unittest.TestCase):
     def __init__(self, *args, **kwargs):
         super().__init__(*args, **kwargs)
 
     def test_bind_tuple_value_expression(self):
         with patch.object(StatementBinderContext, "get_binded_column") as mock:
             mock.return_value = ["table_alias", "col_obj"]
             binder = StatementBinder(StatementBinderContext(MagicMock()))
             tve = MagicMock()
-            tve.col_name = "col_name"
+            tve.name = "col_name"
             binder._bind_tuple_expr(tve)
             col_alias = "{}.{}".format("table_alias", "col_name")
             mock.assert_called_once()
             self.assertEqual(tve.col_object, "col_obj")
             self.assertEqual(tve.col_alias, col_alias)
 
     @patch("evadb.binder.statement_binder.bind_table_info")
@@ -107,47 +106,43 @@
             tableref = MagicMock()
             tableref.is_table_atom.return_value = False
             tableref.is_join.return_value = False
             tableref.is_select.return_value = True
             binder._bind_tableref(tableref)
             self.assertEqual(mock_ctx.call_count, 1)
 
-    def test_bind_create_mat_statement(self):
+    def test_bind_create_table_from_select_statement(self):
         with patch.object(StatementBinder, "bind") as mock_binder:
             binder = StatementBinder(StatementBinderContext(MagicMock()))
-            mat_statement = MagicMock()
-            binder._bind_create_mat_statement(mat_statement)
-            mock_binder.assert_called_with(mat_statement.query)
 
-    def test_raises_mismatch_columns_create_mat_statement(self):
-        with patch.object(StatementBinder, "bind"):
-            binder = StatementBinder(StatementBinderContext(MagicMock()))
-            mat_statement = MagicMock()
-            mat_statement.col_list = [ColumnDefinition("id", None, None, None)]
-            mat_statement.query.target_list = [
-                TupleValueExpression(col_name="id"),
-                TupleValueExpression(col_name="label"),
+            output_obj = MagicMock()
+            output_obj.type = ColumnType.INTEGER
+            output_obj.array_type = NdArrayType.UINT8
+            output_obj.array_dimensions = (1, 1)
+
+            create_statement = MagicMock()
+            create_statement.column_list = []
+            create_statement.query.target_list = [
+                TupleValueExpression(name="id", col_object=output_obj),
+                TupleValueExpression(name="label", col_object=output_obj),
             ]
-            with self.assertRaises(
-                Exception, msg="Projected columns mismatch, expected 1 found 2."
-            ):
-                binder._bind_create_mat_statement(mat_statement)
+
+            binder._bind_create_statement(create_statement)
+            mock_binder.assert_called_with(create_statement.query)
+            self.assertEqual(2, len(create_statement.column_list))
 
     def test_bind_explain_statement(self):
         with patch.object(StatementBinder, "bind") as mock_binder:
             binder = StatementBinder(StatementBinderContext(MagicMock()))
             stmt = MagicMock()
             binder._bind_explain_statement(stmt)
             mock_binder.assert_called_with(stmt.explainable_stmt)
 
     @patch("evadb.binder.statement_binder.load_udf_class_from_file")
-    @patch("evadb.binder.statement_binder.get_file_checksum")
-    def test_bind_func_expr(
-        self, mock_get_file_checksum, mock_load_udf_class_from_file
-    ):
+    def test_bind_func_expr(self, mock_load_udf_class_from_file):
         # setup
         func_expr = MagicMock(
             name="func_expr", alias=Alias("func_expr"), output_col_aliases=[]
         )
         func_expr.name.lower.return_value = "func_expr"
         obj1 = MagicMock()
         obj1.name.lower.return_value = "out1"
@@ -163,22 +158,22 @@
         mock_get_udf_outputs = (
             mock_catalog().get_udf_io_catalog_output_entries
         ) = MagicMock()
         mock_get_udf_outputs.return_value = func_output_objs
         mock_load_udf_class_from_file.return_value.return_value = (
             "load_udf_class_from_file"
         )
-        mock_get_file_checksum.return_value = udf_obj.checksum
+        # mock_get_file_checksum.return_value = udf_obj.checksum
 
         # Case 1 set output
         func_expr.output = "out1"
         binder = StatementBinder(StatementBinderContext(mock_catalog))
         binder._bind_func_expr(func_expr)
 
-        mock_get_file_checksum.assert_called_with(udf_obj.impl_file_path)
+        # mock_get_file_checksum.assert_called_with(udf_obj.impl_file_path)
         mock_get_name.assert_called_with(func_expr.name)
         mock_get_udf_outputs.assert_called_with(udf_obj)
         mock_load_udf_class_from_file.assert_called_with(
             udf_obj.impl_file_path, udf_obj.name
         )
         self.assertEqual(func_expr.output_objs, [obj1])
         print(str(func_expr.alias))
@@ -190,15 +185,15 @@
 
         # Case 2 output not set
         func_expr.output = None
         func_expr.alias = Alias("func_expr")
         binder = StatementBinder(StatementBinderContext(mock_catalog))
         binder._bind_func_expr(func_expr)
 
-        mock_get_file_checksum.assert_called_with(udf_obj.impl_file_path)
+        # mock_get_file_checksum.assert_called_with(udf_obj.impl_file_path)
         mock_get_name.assert_called_with(func_expr.name)
         mock_get_udf_outputs.assert_called_with(udf_obj)
         mock_load_udf_class_from_file.assert_called_with(
             udf_obj.impl_file_path, udf_obj.name
         )
         self.assertEqual(func_expr.output_objs, func_output_objs)
         self.assertEqual(
@@ -216,15 +211,15 @@
         mock_load_udf_class_from_file.side_effect = MagicMock(
             side_effect=RuntimeError(mock_error_msg)
         )
         binder = StatementBinder(StatementBinderContext(mock_catalog))
         with self.assertRaises(BinderError) as cm:
             binder._bind_func_expr(func_expr)
         err_msg = (
-            f"{mock_error_msg}. Please verify that the UDF class name in the"
+            f"{mock_error_msg}. Please verify that the UDF class name in the "
             "implementation file matches the UDF name."
         )
         self.assertEqual(str(cm.exception), err_msg)
 
     @patch("evadb.binder.statement_binder.check_table_object_is_groupable")
     @patch("evadb.binder.statement_binder.check_groupby_pattern")
     def test_bind_select_statement(self, is_groupable_mock, groupby_mock):
@@ -232,14 +227,15 @@
             binder = StatementBinder(StatementBinderContext(MagicMock()))
             select_statement = MagicMock()
             mocks = [MagicMock(), MagicMock(), MagicMock(), MagicMock(), MagicMock()]
             select_statement.target_list = mocks[:2]
             select_statement.orderby_list = [(mocks[2], 0), (mocks[3], 0)]
             select_statement.groupby_clause = mocks[4]
             select_statement.groupby_clause.value = "8 frames"
+            select_statement.from_table.chunk_params = None
             binder._bind_select_statement(select_statement)
             mock_binder.assert_any_call(select_statement.from_table)
             mock_binder.assert_any_call(select_statement.where_clause)
             mock_binder.assert_any_call(select_statement.groupby_clause)
             mock_binder.assert_any_call(select_statement.union_link)
             is_groupable_mock.assert_called()
             for mock in mocks:
@@ -248,19 +244,21 @@
     @patch("evadb.binder.statement_binder.StatementBinderContext")
     def test_bind_select_statement_union_starts_new_context(self, mock_ctx):
         with patch.object(StatementBinder, "bind"):
             binder = StatementBinder(StatementBinderContext(MagicMock()))
             select_statement = MagicMock()
             select_statement.union_link = None
             select_statement.groupby_clause = None
+            select_statement.from_table.chunk_params = None
             binder._bind_select_statement(select_statement)
             self.assertEqual(mock_ctx.call_count, 0)
 
             binder = StatementBinder(StatementBinderContext(MagicMock()))
             select_statement = MagicMock()
+            select_statement.from_table.chunk_params = None
             select_statement.groupby_clause = None
             binder._bind_select_statement(select_statement)
             self.assertEqual(mock_ctx.call_count, 1)
 
     def test_bind_unknown_object(self):
         class UnknownType:
             pass
```

### Comparing `evadb-0.2.9/test/binder/test_statement_binder_context.py` & `evadb-0.3.0/test/binder/test_statement_binder_context.py`

 * *Files 5% similar despite different names*

```diff
@@ -53,23 +53,29 @@
         ctx.add_table_alias("alias", "table_name")
         mock_check.assert_called_with("alias")
         mock_get.assert_called_with("table_name")
         self.assertEqual(ctx._table_alias_map["alias"], "table_obj")
 
     def test_add_derived_table_alias(self):
         objs = [MagicMock(), MagicMock()]
+
+        attributes = {"name": "A", "col_object": "A_obj"}
+
+        mock = MagicMock(spec=TupleValueExpression)
+        for attr, value in attributes.items():
+            setattr(mock, attr, value)
+
         exprs = [
-            MagicMock(spec=TupleValueExpression, col_name="A", col_object="A_obj"),
+            mock,
             MagicMock(spec=FunctionExpression, output_objs=objs),
         ]
         ctx = StatementBinderContext(MagicMock())
 
         mock_check = ctx._check_duplicate_alias = MagicMock()
         ctx.add_derived_table_alias("alias", exprs)
-
         mock_check.assert_called_with("alias")
         col_map = {"A": "A_obj", objs[0].name: objs[0], objs[1].name: objs[1]}
         self.assertEqual(ctx._derived_table_alias_map["alias"], col_map)
 
     def test_get_binded_column_should_search_all(self):
         ctx = StatementBinderContext(MagicMock())
         mock_search_all = ctx._search_all_alias_maps = MagicMock()
```

### Comparing `evadb-0.2.9/test/catalog/__init__.py` & `evadb-0.3.0/test/binder/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/catalog/models/__init__.py` & `evadb-0.3.0/test/catalog/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/catalog/models/test_models.py` & `evadb-0.3.0/test/catalog/models/test_models.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/catalog/test_catalog_manager.py` & `evadb-0.3.0/test/catalog/test_catalog_manager.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/catalog/test_column_type.py` & `evadb-0.3.0/test/catalog/test_column_type.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/executor/__init__.py` & `evadb-0.3.0/test/catalog/models/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/executor/test_abstract_executor.py` & `evadb-0.3.0/test/executor/test_abstract_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/executor/test_create_udf_executor.py` & `evadb-0.3.0/test/executor/test_create_udf_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/executor/test_execution_context.py` & `evadb-0.3.0/test/executor/test_execution_context.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/executor/test_limit_executor.py` & `evadb-0.3.0/test/executor/test_limit_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/executor/test_orderby_executor.py` & `evadb-0.3.0/test/executor/test_orderby_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/executor/test_plan_executor.py` & `evadb-0.3.0/test/executor/test_plan_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/executor/test_sample_executor.py` & `evadb-0.3.0/test/executor/test_sample_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/executor/test_seq_scan_executor.py` & `evadb-0.3.0/test/executor/test_seq_scan_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/executor/utils.py` & `evadb-0.3.0/test/executor/utils.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/expression/__init__.py` & `evadb-0.3.0/test/executor/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/expression/test_abstract_expression.py` & `evadb-0.3.0/test/expression/test_abstract_expression.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/expression/test_aggregation.py` & `evadb-0.3.0/test/expression/test_aggregation.py`

 * *Files 4% similar despite different names*

```diff
@@ -25,100 +25,100 @@
 
 
 class AggregationExpressionsTest(unittest.TestCase):
     def __init__(self, *args, **kwargs):
         super().__init__(*args, **kwargs)
 
     def test_aggregation_first(self):
-        columnName = TupleValueExpression(col_name=0)
+        columnName = TupleValueExpression(name=0)
         columnName.col_alias = 0
         aggr_expr = AggregationExpression(
             ExpressionType.AGGREGATION_FIRST, None, columnName
         )
         tuples = Batch(pd.DataFrame({0: [1, 2, 3], 1: [2, 3, 4], 2: [3, 4, 5]}))
         batch = aggr_expr.evaluate(tuples, None)
         self.assertEqual(1, batch.frames.iloc[0][0])
         self.assertNotEqual(str(aggr_expr), None)
 
     def test_aggregation_last(self):
-        columnName = TupleValueExpression(col_name=0)
+        columnName = TupleValueExpression(name=0)
         columnName.col_alias = 0
         aggr_expr = AggregationExpression(
             ExpressionType.AGGREGATION_LAST, None, columnName
         )
         tuples = Batch(pd.DataFrame({0: [1, 2, 3], 1: [2, 3, 4], 2: [3, 4, 5]}))
         batch = aggr_expr.evaluate(tuples, None)
         self.assertEqual(3, batch.frames.iloc[0][0])
         self.assertNotEqual(str(aggr_expr), None)
 
     def test_aggregation_segment(self):
-        columnName = TupleValueExpression(col_name=0)
+        columnName = TupleValueExpression(name=0)
         columnName.col_alias = 0
         aggr_expr = AggregationExpression(
             ExpressionType.AGGREGATION_SEGMENT, None, columnName
         )
         tuples = Batch(pd.DataFrame({0: [1, 2, 3], 1: [2, 3, 4], 2: [3, 4, 5]}))
         batch = aggr_expr.evaluate(tuples, None)
         self.assertTrue((np.array([1, 2, 3]) == batch.frames.iloc[0][0]).all())
         self.assertNotEqual(str(aggr_expr), None)
 
     def test_aggregation_sum(self):
-        columnName = TupleValueExpression(col_name=0)
+        columnName = TupleValueExpression(name=0)
         columnName.col_alias = 0
         aggr_expr = AggregationExpression(
             ExpressionType.AGGREGATION_SUM, None, columnName
         )
         tuples = Batch(pd.DataFrame({0: [1, 2, 3], 1: [2, 3, 4], 2: [3, 4, 5]}))
         batch = aggr_expr.evaluate(tuples, None)
         self.assertEqual(6, batch.frames.iloc[0][0])
         self.assertNotEqual(str(aggr_expr), None)
 
     def test_aggregation_count(self):
-        columnName = TupleValueExpression(col_name=0)
+        columnName = TupleValueExpression(name=0)
         columnName.col_alias = 0
         aggr_expr = AggregationExpression(
             ExpressionType.AGGREGATION_COUNT, None, columnName
         )
         tuples = Batch(pd.DataFrame({0: [1, 2, 3], 1: [2, 3, 4], 2: [3, 4, 5]}))
         batch = aggr_expr.evaluate(tuples, None)
         self.assertEqual(3, batch.frames.iloc[0][0])
         self.assertNotEqual(str(aggr_expr), None)
 
     def test_aggregation_avg(self):
-        columnName = TupleValueExpression(col_name=0)
+        columnName = TupleValueExpression(name=0)
         columnName.col_alias = 0
         aggr_expr = AggregationExpression(
             ExpressionType.AGGREGATION_AVG, None, columnName
         )
         tuples = Batch(pd.DataFrame({0: [1, 2, 3], 1: [2, 3, 4], 2: [3, 4, 5]}))
         batch = aggr_expr.evaluate(tuples, None)
         self.assertEqual(2, batch.frames.iloc[0][0])
         self.assertNotEqual(str(aggr_expr), None)
 
     def test_aggregation_min(self):
-        columnName = TupleValueExpression(col_name=0)
+        columnName = TupleValueExpression(name=0)
         columnName.col_alias = 0
         aggr_expr = AggregationExpression(
             ExpressionType.AGGREGATION_MIN, None, columnName
         )
         tuples = Batch(pd.DataFrame({0: [1, 2, 3], 1: [2, 3, 4], 2: [3, 4, 5]}))
         batch = aggr_expr.evaluate(tuples, None)
         self.assertEqual(1, batch.frames.iloc[0][0])
         self.assertNotEqual(str(aggr_expr), None)
 
     def test_aggregation_max(self):
-        columnName = TupleValueExpression(col_name=0)
+        columnName = TupleValueExpression(name=0)
         columnName.col_alias = 0
         aggr_expr = AggregationExpression(
             ExpressionType.AGGREGATION_MAX, None, columnName
         )
         tuples = Batch(pd.DataFrame({0: [1, 2, 3], 1: [2, 3, 4], 2: [3, 4, 5]}))
         batch = aggr_expr.evaluate(tuples, None)
         self.assertEqual(3, batch.frames.iloc[0][0])
         self.assertNotEqual(str(aggr_expr), None)
 
     def test_aggregation_incorrect_etype(self):
         incorrect_etype = 100
-        columnName = TupleValueExpression(col_name=0)
+        columnName = TupleValueExpression(name=0)
         aggr_expr = AggregationExpression(incorrect_etype, columnName, columnName)
         with pytest.raises(NotImplementedError):
             str(aggr_expr)
```

### Comparing `evadb-0.2.9/test/expression/test_arithmetic.py` & `evadb-0.3.0/test/expression/test_arithmetic.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/expression/test_comparison.py` & `evadb-0.3.0/test/expression/test_comparison.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/expression/test_expression_tree.py` & `evadb-0.3.0/test/expression/test_expression_tree.py`

 * *Files 2% similar despite different names*

```diff
@@ -23,16 +23,16 @@
 from evadb.expression.tuple_value_expression import TupleValueExpression
 
 
 class ExpressionEvaluationTest(unittest.TestCase):
     def test_if_expr_tree_is_equal(self):
         const_exp1 = ConstantValueExpression(0)
         const_exp2 = ConstantValueExpression(0)
-        columnName1 = TupleValueExpression(col_name="DATA")
-        columnName2 = TupleValueExpression(col_name="DATA")
+        columnName1 = TupleValueExpression(name="DATA")
+        columnName2 = TupleValueExpression(name="DATA")
 
         aggr_expr1 = AggregationExpression(
             ExpressionType.AGGREGATION_AVG, None, columnName1
         )
         aggr_expr2 = AggregationExpression(
             ExpressionType.AGGREGATION_AVG, None, columnName2
         )
@@ -48,15 +48,15 @@
     def test_should_return_false_for_unequal_expressions(self):
         const_exp1 = ConstantValueExpression(0)
         const_exp2 = ConstantValueExpression(1)
         func_expr = FunctionExpression(lambda x: x + 1, name="test")
         cmpr_exp = ComparisonExpression(
             ExpressionType.COMPARE_NEQ, const_exp1, const_exp2
         )
-        tuple_expr = TupleValueExpression(col_name="id")
+        tuple_expr = TupleValueExpression(name="id")
         aggr_expr = AggregationExpression(
             ExpressionType.AGGREGATION_MAX, None, tuple_expr
         )
         logical_expr = LogicalExpression(ExpressionType.LOGICAL_OR, cmpr_exp, cmpr_exp)
 
         self.assertNotEqual(const_exp1, const_exp2)
         self.assertNotEqual(cmpr_exp, const_exp1)
```

### Comparing `evadb-0.2.9/test/expression/test_expression_utils.py` & `evadb-0.3.0/test/expression/test_expression_utils.py`

 * *Files 0% similar despite different names*

```diff
@@ -35,15 +35,15 @@
         self,
         val,
         expr_type=ExpressionType.COMPARE_GREATER,
         name="id",
         const_first=False,
     ):
         constexpr = ConstantValueExpression(val)
-        colname = TupleValueExpression(col_name=name, col_alias=f"T.{name}")
+        colname = TupleValueExpression(name=name, col_alias=f"T.{name}")
         if const_first:
             return ComparisonExpression(expr_type, constexpr, colname)
         return ComparisonExpression(expr_type, colname, constexpr)
 
     def test_extract_range_list_from_comparison_expr(self):
         expr_types = [
             ExpressionType.COMPARE_NEQ,
```

### Comparing `evadb-0.2.9/test/expression/test_function_expression.py` & `evadb-0.3.0/test/expression/test_function_expression.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/expression/test_logical.py` & `evadb-0.3.0/test/expression/test_logical.py`

 * *Files 2% similar despite different names*

```diff
@@ -79,17 +79,17 @@
         logical_expr = LogicalExpression(
             ExpressionType.LOGICAL_NOT, None, comparison_expression_right
         )
         self.assertEqual([True], logical_expr.evaluate(self.batch).frames[0].tolist())
 
     def test_short_circuiting_and_complete(self):
         # tests whether right-hand side is bypassed completely with and
-        tup_val_exp_l = TupleValueExpression(col_name=0)
+        tup_val_exp_l = TupleValueExpression(name=0)
         tup_val_exp_l.col_alias = 0
-        tup_val_exp_r = TupleValueExpression(col_name=1)
+        tup_val_exp_r = TupleValueExpression(name=1)
         tup_val_exp_r.col_alias = 1
 
         comp_exp_l = ComparisonExpression(
             ExpressionType.COMPARE_EQUAL, tup_val_exp_l, tup_val_exp_r
         )
         comp_exp_r = Mock(spec=ComparisonExpression)
 
@@ -101,17 +101,17 @@
         self.assertEqual(
             [False, False, False], logical_exp.evaluate(tuples).frames[0].tolist()
         )
         comp_exp_r.evaluate.assert_not_called()
 
     def test_short_circuiting_or_complete(self):
         # tests whether right-hand side is bypassed completely with or
-        tup_val_exp_l = TupleValueExpression(col_name=0)
+        tup_val_exp_l = TupleValueExpression(name=0)
         tup_val_exp_l.col_alias = 0
-        tup_val_exp_r = TupleValueExpression(col_name=1)
+        tup_val_exp_r = TupleValueExpression(name=1)
         tup_val_exp_r.col_alias = 1
 
         comp_exp_l = ComparisonExpression(
             ExpressionType.COMPARE_EQUAL, tup_val_exp_l, tup_val_exp_r
         )
         comp_exp_r = Mock(spec=ComparisonExpression)
 
@@ -123,17 +123,17 @@
         self.assertEqual(
             [True, True, True], logical_exp.evaluate(tuples).frames[0].tolist()
         )
         comp_exp_r.evaluate.assert_not_called()
 
     def test_short_circuiting_and_partial(self):
         # tests whether right-hand side is partially executed with and
-        tup_val_exp_l = TupleValueExpression(col_name=0)
+        tup_val_exp_l = TupleValueExpression(name=0)
         tup_val_exp_l.col_alias = 0
-        tup_val_exp_r = TupleValueExpression(col_name=1)
+        tup_val_exp_r = TupleValueExpression(name=1)
         tup_val_exp_r.col_alias = 1
 
         comp_exp_l = ComparisonExpression(
             ExpressionType.COMPARE_EQUAL, tup_val_exp_l, tup_val_exp_r
         )
         comp_exp_r = Mock(spec=ComparisonExpression)
         comp_exp_r.evaluate = Mock(return_value=Mock(_frames=[[True], [False]]))
@@ -146,17 +146,17 @@
         self.assertEqual(
             [True, False, False, False], logical_exp.evaluate(tuples).frames[0].tolist()
         )
         comp_exp_r.evaluate.assert_called_once_with(tuples[[0, 1]])
 
     def test_short_circuiting_or_partial(self):
         # tests whether right-hand side is partially executed with or
-        tup_val_exp_l = TupleValueExpression(col_name=0)
+        tup_val_exp_l = TupleValueExpression(name=0)
         tup_val_exp_l.col_alias = 0
-        tup_val_exp_r = TupleValueExpression(col_name=1)
+        tup_val_exp_r = TupleValueExpression(name=1)
         tup_val_exp_r.col_alias = 1
 
         comp_exp_l = ComparisonExpression(
             ExpressionType.COMPARE_EQUAL, tup_val_exp_l, tup_val_exp_r
         )
         comp_exp_r = Mock(spec=ComparisonExpression)
         comp_exp_r.evaluate = Mock(return_value=Mock(_frames=[[True], [False]]))
```

### Comparing `evadb-0.2.9/test/integration_tests/__init__.py` & `evadb-0.3.0/test/expression/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/integration_tests/test_array_count.py` & `evadb-0.3.0/test/integration_tests/test_array_count.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/integration_tests/test_create_index_executor.py` & `evadb-0.3.0/test/integration_tests/test_create_index_executor.py`

 * *Files 9% similar despite different names*

```diff
@@ -10,25 +10,26 @@
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import unittest
 from pathlib import Path
+from test.markers import macos_skip_marker
 from test.util import get_evadb_for_testing, load_udfs_for_testing
 
-import faiss
 import numpy as np
 import pandas as pd
 import pytest
 
 from evadb.catalog.catalog_type import VectorStoreType
 from evadb.models.storage.batch import Batch
 from evadb.server.command_handler import execute_query_fetch_all
 from evadb.storage.storage_engine import StorageEngine
+from evadb.utils.generic_utils import try_to_import_faiss
 
 
 @pytest.mark.notparallel
 class CreateIndexTest(unittest.TestCase):
     def _index_save_path(self):
         return str(
             Path(self.evadb.config.get_value("storage", "index_dir"))
@@ -92,14 +93,15 @@
     @classmethod
     def tearDownClass(cls):
         query = "DROP TABLE testCreateIndexFeatTable;"
         execute_query_fetch_all(cls.evadb, query)
         query = "DROP TABLE testCreateIndexInputTable;"
         execute_query_fetch_all(cls.evadb, query)
 
+    @macos_skip_marker
     def test_should_create_index_faiss(self):
         query = "CREATE INDEX testCreateIndexName ON testCreateIndexFeatTable (feat) USING FAISS;"
         execute_query_fetch_all(self.evadb, query)
 
         # Test index catalog.
         index_catalog_entry = self.evadb.catalog().get_index_catalog_entry_by_name(
             "testCreateIndexName"
@@ -119,22 +121,26 @@
             "testCreateIndexFeatTable"
         )
         feat_column = [col for col in feat_table_entry.columns if col.name == "feat"][0]
         self.assertEqual(index_catalog_entry.feat_column_id, feat_column.row_id)
         self.assertEqual(index_catalog_entry.feat_column, feat_column)
 
         # Test on disk index.
+        try_to_import_faiss()
+        import faiss
+
         index = faiss.read_index(index_catalog_entry.save_file_path)
         distance, row_id = index.search(np.array([[0, 0, 0]]).astype(np.float32), 1)
         self.assertEqual(distance[0][0], 0)
         self.assertEqual(row_id[0][0], 1)
 
         # Cleanup.
         self.evadb.catalog().drop_index_catalog_entry("testCreateIndexName")
 
+    @macos_skip_marker
     def test_should_create_index_with_udf(self):
         query = "CREATE INDEX testCreateIndexName ON testCreateIndexInputTable (DummyFeatureExtractor(input)) USING FAISS;"
         execute_query_fetch_all(self.evadb, query)
 
         # Test index udf signature.
         index_catalog_entry = self.evadb.catalog().get_index_catalog_entry_by_name(
             "testCreateIndexName"
@@ -152,14 +158,17 @@
         input_column = [
             col for col in input_table_entry.columns if col.name == "input"
         ][0]
         self.assertEqual(index_catalog_entry.feat_column_id, input_column.row_id)
         self.assertEqual(index_catalog_entry.feat_column, input_column)
 
         # Test on disk index.
+        try_to_import_faiss()
+        import faiss
+
         index = faiss.read_index(index_catalog_entry.save_file_path)
         distance, row_id = index.search(np.array([[0, 0, 0]]).astype(np.float32), 1)
         self.assertEqual(distance[0][0], 0)
         self.assertEqual(row_id[0][0], 1)
 
         # Cleanup.
         self.evadb.catalog().drop_index_catalog_entry("testCreateIndexName")
```

### Comparing `evadb-0.2.9/test/integration_tests/test_create_table_executor.py` & `evadb-0.3.0/test/integration_tests/test_create_table_executor.py`

 * *Files 5% similar despite different names*

```diff
@@ -9,14 +9,15 @@
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import unittest
+from test.markers import macos_skip_marker
 from test.util import (
     DummyObjectDetector,
     create_sample_video,
     file_remove,
     get_evadb_for_testing,
     load_udfs_for_testing,
     shutdown_ray,
@@ -58,15 +59,15 @@
 
     def _test_currently_cannot_create_boolean_table(self):
         query = """ CREATE TABLE BooleanTable( A BOOLEAN);"""
 
         with self.assertRaises(ExecutorError):
             execute_query_fetch_all(self.evadb, query)
 
-    # @ray_skip_marker
+    @macos_skip_marker
     def test_should_create_table_from_select(self):
         create_query = """CREATE TABLE dummy_table
             AS SELECT id, DummyObjectDetector(data).label FROM MyVideo;
         """
         execute_query_fetch_all(self.evadb, create_query)
 
         select_query = "SELECT id, label FROM dummy_table;"
@@ -77,14 +78,15 @@
         expected = [
             {"dummy_table.id": i, "dummy_table.label": [labels[1 + i % 2]]}
             for i in range(NUM_FRAMES)
         ]
         expected_batch = Batch(frames=pd.DataFrame(expected))
         self.assertEqual(actual_batch, expected_batch)
 
+    @macos_skip_marker
     @pytest.mark.torchtest
     def test_should_create_table_from_select_lateral_join(self):
         select_query = (
             "SELECT id, label, bbox FROM UATRAC JOIN LATERAL "
             "Yolo(data) AS T(label, bbox, score) WHERE id < 5;"
         )
         query = "CREATE TABLE IF NOT EXISTS " f"uadtrac_fastRCNN AS {select_query};"
```

### Comparing `evadb-0.2.9/test/integration_tests/test_delete_executor.py` & `evadb-0.3.0/test/integration_tests/test_delete_executor.py`

 * *Files 2% similar despite different names*

```diff
@@ -9,14 +9,15 @@
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import unittest
+from test.markers import macos_skip_marker
 from test.util import (
     file_remove,
     get_evadb_for_testing,
     load_udfs_for_testing,
     shutdown_ray,
 )
 
@@ -118,14 +119,15 @@
         self.assertIsNone(
             np.testing.assert_array_equal(
                 batch.frames["data"][0],
                 np.array([[[41, 41, 41], [41, 41, 41]], [[41, 41, 41], [41, 41, 41]]]),
             )
         )
 
+    @macos_skip_marker
     def test_should_delete_tuple_in_table(self):
         delete_query = """DELETE FROM testDeleteOne WHERE
                id < 20 OR dummyfloat < 2 AND id < 5 AND 20 > id
                AND id <= 20 AND id >= 5 OR id != 15 OR id = 15;"""
         batch = execute_query_fetch_all(self.evadb, delete_query)
 
         query = "SELECT * FROM testDeleteOne;"
```

### Comparing `evadb-0.2.9/test/integration_tests/test_drop_executor.py` & `evadb-0.3.0/test/integration_tests/test_drop_executor.py`

 * *Files 4% similar despite different names*

```diff
@@ -104,15 +104,17 @@
         )
         self.assertEqual(len(column_objects), 0)
         self.assertFalse(Path(video_dir).exists())
 
         # Fail if table already dropped
         drop_query = """DROP TABLE MyVideo;"""
         with self.assertRaises(ExecutorError):
-            execute_query_fetch_all(self.evadb, drop_query)
+            execute_query_fetch_all(
+                self.evadb, drop_query, do_not_print_exceptions=True
+            )
 
     def run_create_udf_query(self):
         create_udf_query = """CREATE UDF DummyObjectDetector
             INPUT  (Frame_Array NDARRAY UINT8(3, 256, 256))
             OUTPUT (label NDARRAY STR(10))
             TYPE  Classification
             IMPL  'test/util.py';"""
@@ -138,15 +140,17 @@
         self.assertTrue(udf is not None)
 
         # Test that dropping the wrong UDF:
         # - does not affect UDFs in the catalog
         # - raises an appropriate exception
         drop_query = "DROP UDF {};".format(wrong_udf_name)
         try:
-            execute_query_fetch_all(self.evadb, drop_query)
+            execute_query_fetch_all(
+                self.evadb, drop_query, do_not_print_exceptions=True
+            )
         except Exception as e:
             err_msg = "UDF {} does not exist, therefore cannot be dropped.".format(
                 wrong_udf_name
             )
             self.assertTrue(str(e) == err_msg)
         udf = self.evadb.catalog().get_udf_catalog_entry_by_name(right_udf_name)
         self.assertTrue(udf is not None)
@@ -162,15 +166,17 @@
 
         # Test that dropping the wrong Index:
         # - does not affect Indexes in the catalog
         # - raises an appropriate exception
         wrong_udf_name = "wrong_udf_name"
         drop_query = f"DROP INDEX {wrong_udf_name};"
         with self.assertRaises(ExecutorError):
-            execute_query_fetch_all(self.evadb, drop_query)
+            execute_query_fetch_all(
+                self.evadb, drop_query, do_not_print_exceptions=True
+            )
         obj = self.evadb.catalog().get_index_catalog_entry_by_name(index_name)
         self.assertTrue(obj is not None)
 
         # Test that dropping the Index reflects in the catalog
         drop_query = f"DROP INDEX IF EXISTS {index_name};"
         execute_query_fetch_all(self.evadb, drop_query)
         index_obj = self.evadb.catalog().get_index_catalog_entry_by_name(index_name)
```

### Comparing `evadb-0.2.9/test/integration_tests/test_error_handling_with_ray.py` & `evadb-0.3.0/test/integration_tests/test_error_handling_with_ray.py`

 * *Files 6% similar despite different names*

```diff
@@ -12,15 +12,15 @@
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import os
 import time
 import unittest
 from pathlib import Path
-from test.markers import ray_only_marker
+from test.markers import ray_skip_marker
 from test.util import (
     create_sample_image,
     get_evadb_for_testing,
     is_ray_stage_running,
     load_udfs_for_testing,
     shutdown_ray,
 )
@@ -49,15 +49,15 @@
     def tearDown(self):
         shutdown_ray()
 
         # Drop table.
         drop_table_query = "DROP TABLE testRayErrorHandling;"
         execute_query_fetch_all(self.evadb, drop_table_query)
 
-    @ray_only_marker
+    @ray_skip_marker
     def test_ray_error_populate_to_all_stages(self):
         udf_name, task = "HFObjectDetector", "image-classification"
         create_udf_query = f"""CREATE UDF {udf_name}
             TYPE HuggingFace
             'task' '{task}'
         """
```

### Comparing `evadb-0.2.9/test/integration_tests/test_explain_executor.py` & `evadb-0.3.0/test/integration_tests/test_explain_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/integration_tests/test_fuzzy_join.py` & `evadb-0.3.0/test/integration_tests/test_fuzzy_join.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/integration_tests/test_huggingface_udfs.py` & `evadb-0.3.0/test/integration_tests/test_huggingface_udfs.py`

 * *Files 1% similar despite different names*

```diff
@@ -80,15 +80,17 @@
         create_udf_query = f"""CREATE UDF {udf_name}
             TYPE HuggingFace
             'task' '{task}'
         """
         # catch an assert
 
         with self.assertRaises(ExecutorError) as exc_info:
-            execute_query_fetch_all(self.evadb, create_udf_query)
+            execute_query_fetch_all(
+                self.evadb, create_udf_query, do_not_print_exceptions=True
+            )
         self.assertIn(
             f"Task {task} not supported in EvaDB currently", str(exc_info.exception)
         )
 
     def test_object_detection(self):
         udf_name = "HFObjectDetector"
         create_udf_query = f"""CREATE UDF {udf_name}
@@ -270,15 +272,14 @@
         )
 
         drop_udf_query = f"DROP UDF {asr_udf};"
         execute_query_fetch_all(self.evadb, drop_udf_query)
         drop_udf_query = f"DROP UDF {summary_udf};"
         execute_query_fetch_all(self.evadb, drop_udf_query)
 
-    @pytest.mark.benchmark
     def test_toxicity_classification(self):
         udf_name = "HFToxicityClassifier"
         create_udf_query = f"""CREATE UDF {udf_name}
             TYPE HuggingFace
             'task' 'text-classification'
             'model' 'martin-ha/toxic-comment-model'
         """
```

### Comparing `evadb-0.2.9/test/integration_tests/test_insert_executor.py` & `evadb-0.3.0/test/integration_tests/test_insert_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/integration_tests/test_like.py` & `evadb-0.3.0/test/integration_tests/test_like.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/integration_tests/test_load_executor.py` & `evadb-0.3.0/test/integration_tests/test_load_executor.py`

 * *Files 10% similar despite different names*

```diff
@@ -39,15 +39,15 @@
 from evadb.executor.executor_utils import ExecutorError
 from evadb.models.storage.batch import Batch
 from evadb.parser.types import FileFormatType
 from evadb.server.command_handler import execute_query_fetch_all
 
 
 @pytest.mark.notparallel
-class LoadExecutorTest(unittest.TestCase):
+class LoadExecutorTests(unittest.TestCase):
     def setUp(self):
         self.evadb = get_evadb_for_testing()
         # reset the catalog manager before running each test
         self.evadb.catalog().reset()
         self.video_file_path = create_sample_video()
         self.image_files_path = Path(
             f"{EvaDB_ROOT_DIR}/test/data/uadetrac/small-data/MVI_20011/*.jpg"
@@ -104,15 +104,17 @@
         self.assertEqual(actual_batch, expected_batch)
 
         # remove the source file
         file_remove("dummy.avi")
 
         # try to read the table again
         with self.assertRaises(ExecutorError) as e:
-            execute_query_fetch_all(self.evadb, select_query)
+            execute_query_fetch_all(
+                self.evadb, select_query, do_not_print_exceptions=True
+            )
         self.assertEqual(
             str(e.exception),
             "The dataset file could not be found. Please verify that the file exists in the specified path.",
         )
 
         # create the file again for other test cases
         create_sample_video()
@@ -171,49 +173,51 @@
             self.evadb, "SELECT id FROM MyVideos;"
         )
 
         # try adding duplicate files to the table
         path = f"{EvaDB_ROOT_DIR}/data/sample_videos/**/*.mp4"
         query = f"""LOAD VIDEO "{path}" INTO MyVideos;"""
         with self.assertRaises(ExecutorError):
-            execute_query_fetch_all(self.evadb, query)
+            execute_query_fetch_all(self.evadb, query, do_not_print_exceptions=True)
 
         # original data should be preserved
         after_load_fail = execute_query_fetch_all(
             self.evadb, "SELECT id FROM MyVideos;"
         )
 
         self.assertEqual(expected_output, after_load_fail)
 
     def test_should_fail_to_load_missing_video(self):
         path = f"{EvaDB_ROOT_DIR}/data/sample_videos/missing.mp4"
         query = f"""LOAD VIDEO "{path}" INTO MyVideos;"""
         with self.assertRaises(ExecutorError) as exc_info:
-            execute_query_fetch_all(self.evadb, query)
+            execute_query_fetch_all(self.evadb, query, do_not_print_exceptions=True)
         self.assertIn(
-            "Load VIDEO failed due to no valid files found on path",
+            "Load VIDEO failed",
             str(exc_info.exception),
         )
 
     def test_should_fail_to_load_corrupt_video(self):
         # should fail on an empty file
         tempfile_name = os.urandom(24).hex()
         tempfile_path = os.path.join(tempfile.gettempdir(), tempfile_name)
         with open(tempfile_path, "wb") as tmp:
             query = f"""LOAD VIDEO "{tmp.name}" INTO MyVideos;"""
             with self.assertRaises(Exception):
-                execute_query_fetch_all(self.evadb, query)
+                execute_query_fetch_all(self.evadb, query, do_not_print_exceptions=True)
 
     def test_should_fail_to_load_invalid_files_as_video(self):
-        path = f"{EvaDB_ROOT_DIR}/data/**"
+        path = f"{EvaDB_ROOT_DIR}/data/README.md"
         query = f"""LOAD VIDEO "{path}" INTO MyVideos;"""
         with self.assertRaises(Exception):
-            execute_query_fetch_all(self.evadb, query)
+            execute_query_fetch_all(self.evadb, query, do_not_print_exceptions=True)
         with self.assertRaises(BinderError):
-            execute_query_fetch_all(self.evadb, "SELECT name FROM MyVideos")
+            execute_query_fetch_all(
+                self.evadb, "SELECT name FROM MyVideos", do_not_print_exceptions=True
+            )
 
     def test_should_rollback_if_video_load_fails(self):
         path_regex = Path(f"{EvaDB_ROOT_DIR}/data/sample_videos/1/*.mp4")
         valid_videos = glob.glob(str(path_regex.expanduser()), recursive=True)
 
         tempfile_name = os.urandom(24).hex()
         tempfile_path = os.path.join(tempfile.gettempdir(), tempfile_name)
@@ -222,30 +226,42 @@
             # nothing should be added
             with tempfile.TemporaryDirectory() as tmp_dir:
                 shutil.copy2(str(valid_videos[0]), tmp_dir)
                 shutil.copy2(str(empty_file.name), tmp_dir)
                 path = Path(tmp_dir) / "*"
                 query = f"""LOAD VIDEO "{path}" INTO MyVideos;"""
                 with self.assertRaises(Exception):
-                    execute_query_fetch_all(self.evadb, query)
+                    execute_query_fetch_all(
+                        self.evadb, query, do_not_print_exceptions=True
+                    )
                 with self.assertRaises(BinderError):
-                    execute_query_fetch_all(self.evadb, "SELECT name FROM MyVideos")
+                    execute_query_fetch_all(
+                        self.evadb,
+                        "SELECT name FROM MyVideos",
+                        do_not_print_exceptions=True,
+                    )
 
             # Load two correct file and one empty file
             # nothing should be added
             with tempfile.TemporaryDirectory() as tmp_dir:
                 shutil.copy2(str(valid_videos[0]), tmp_dir)
                 shutil.copy2(str(valid_videos[1]), tmp_dir)
                 shutil.copy2(str(empty_file.name), tmp_dir)
                 path = Path(tmp_dir) / "*"
                 query = f"""LOAD VIDEO "{path}" INTO MyVideos;"""
                 with self.assertRaises(Exception):
-                    execute_query_fetch_all(self.evadb, query)
+                    execute_query_fetch_all(
+                        self.evadb, query, do_not_print_exceptions=True
+                    )
                 with self.assertRaises(BinderError):
-                    execute_query_fetch_all(self.evadb, "SELECT name FROM MyVideos")
+                    execute_query_fetch_all(
+                        self.evadb,
+                        "SELECT name FROM MyVideos",
+                        do_not_print_exceptions=True,
+                    )
 
     def test_should_rollback_and_preserve_previous_state(self):
         path_regex = Path(f"{EvaDB_ROOT_DIR}/data/sample_videos/1/*.mp4")
         valid_videos = glob.glob(str(path_regex.expanduser()), recursive=True)
         # Load one correct file
         # commit
         load_file = f"{EvaDB_ROOT_DIR}/data/sample_videos/1/1.mp4"
@@ -260,15 +276,17 @@
         with open(tempfile_path, "wb") as empty_file:
             with tempfile.TemporaryDirectory() as tmp_dir:
                 shutil.copy2(str(valid_videos[1]), tmp_dir)
                 shutil.copy2(str(empty_file.name), tmp_dir)
                 path = Path(tmp_dir) / "*"
                 query = f"""LOAD VIDEO "{path}" INTO MyVideos;"""
                 with self.assertRaises(Exception):
-                    execute_query_fetch_all(self.evadb, query)
+                    execute_query_fetch_all(
+                        self.evadb, query, do_not_print_exceptions=True
+                    )
                 result = execute_query_fetch_all(
                     self.evadb, "SELECT name FROM MyVideos"
                 )
                 file_names = np.unique(result.frames)
                 self.assertEqual(len(file_names), 1)
 
     ###########################################
@@ -284,17 +302,17 @@
         )
         self.assertEqual(result, expected)
 
     def test_should_fail_to_load_missing_image(self):
         path = f"{EvaDB_ROOT_DIR}/data/sample_images/missing.jpg"
         query = f"""LOAD IMAGE "{path}" INTO MyImages;"""
         with self.assertRaises(ExecutorError) as exc_info:
-            execute_query_fetch_all(self.evadb, query)
+            execute_query_fetch_all(self.evadb, query, do_not_print_exceptions=True)
         self.assertIn(
-            "Load IMAGE failed due to no valid files found on path",
+            "Load IMAGE failed",
             str(exc_info.exception),
         )
 
     def test_should_fail_to_load_images_with_same_path(self):
         image_files = glob.glob(
             os.path.expanduser(self.image_files_path), recursive=True
         )
@@ -309,15 +327,15 @@
         expected_output = execute_query_fetch_all(
             self.evadb, "SELECT name FROM MyImages;"
         )
 
         # try adding duplicate files to the table
         query = f"""LOAD IMAGE "{image_files[0]}" INTO MyImages;"""
         with self.assertRaises(Exception):
-            execute_query_fetch_all(self.evadb, query)
+            execute_query_fetch_all(self.evadb, query, do_not_print_exceptions=True)
 
         # original data should be preserved
         after_load_fail = execute_query_fetch_all(
             self.evadb, "SELECT name FROM MyImages;"
         )
 
         self.assertEqual(expected_output, after_load_fail)
@@ -325,23 +343,25 @@
     def test_should_fail_to_load_corrupt_image(self):
         # should fail on an empty file
         tempfile_name = os.urandom(24).hex()
         tempfile_path = os.path.join(tempfile.gettempdir(), tempfile_name)
         with open(tempfile_path, "wb") as tmp:
             query = f"""LOAD IMAGE "{tmp.name}" INTO MyImages;"""
             with self.assertRaises(Exception):
-                execute_query_fetch_all(self.evadb, query)
+                execute_query_fetch_all(self.evadb, query, do_not_print_exceptions=True)
 
     def test_should_fail_to_load_invalid_files_as_image(self):
-        path = f"{EvaDB_ROOT_DIR}/data/**"
+        path = f"{EvaDB_ROOT_DIR}/data/README.md"
         query = f"""LOAD IMAGE "{path}" INTO MyImages;"""
         with self.assertRaises(Exception):
-            execute_query_fetch_all(self.evadb, query)
+            execute_query_fetch_all(self.evadb, query, do_not_print_exceptions=True)
         with self.assertRaises(BinderError):
-            execute_query_fetch_all(self.evadb, "SELECT name FROM MyImages;")
+            execute_query_fetch_all(
+                self.evadb, "SELECT name FROM MyImages;", do_not_print_exceptions=True
+            )
 
     def test_should_rollback_if_image_load_fails(self):
         valid_images = glob.glob(
             str(self.image_files_path.expanduser()), recursive=True
         )
 
         tempfile_name = os.urandom(24).hex()
@@ -351,30 +371,42 @@
             # nothing should be added
             with tempfile.TemporaryDirectory() as tmp_dir:
                 shutil.copy2(str(valid_images[0]), tmp_dir)
                 shutil.copy2(str(empty_file.name), tmp_dir)
                 path = Path(tmp_dir) / "*"
                 query = f"""LOAD IMAGE "{path}" INTO MyImages;"""
                 with self.assertRaises(Exception):
-                    execute_query_fetch_all(self.evadb, query)
+                    execute_query_fetch_all(
+                        self.evadb, query, do_not_print_exceptions=True
+                    )
                 with self.assertRaises(BinderError):
-                    execute_query_fetch_all(self.evadb, "SELECT name FROM MyImages;")
+                    execute_query_fetch_all(
+                        self.evadb,
+                        "SELECT name FROM MyImages;",
+                        do_not_print_exceptions=True,
+                    )
 
             # Load two correct file and one empty file
             # nothing should be added
             with tempfile.TemporaryDirectory() as tmp_dir:
                 shutil.copy2(str(valid_images[0]), tmp_dir)
                 shutil.copy2(str(valid_images[1]), tmp_dir)
                 shutil.copy2(str(empty_file.name), tmp_dir)
                 path = Path(tmp_dir) / "*"
                 query = f"""LOAD IMAGE "{path}" INTO MyImages;"""
                 with self.assertRaises(Exception):
-                    execute_query_fetch_all(self.evadb, query)
+                    execute_query_fetch_all(
+                        self.evadb, query, do_not_print_exceptions=True
+                    )
                 with self.assertRaises(BinderError):
-                    execute_query_fetch_all(self.evadb, "SELECT name FROM MyImages;")
+                    execute_query_fetch_all(
+                        self.evadb,
+                        "SELECT name FROM MyImages;",
+                        do_not_print_exceptions=True,
+                    )
 
     def test_should_rollback_and_preserve_previous_state_for_load_images(self):
         valid_images = glob.glob(
             str(self.image_files_path.expanduser()), recursive=True
         )
         # Load one correct file
         # commit
@@ -389,15 +421,17 @@
         with open(tempfile_path, "wb") as empty_file:
             with tempfile.TemporaryDirectory() as tmp_dir:
                 shutil.copy2(str(valid_images[1]), tmp_dir)
                 shutil.copy2(str(empty_file.name), tmp_dir)
                 path = Path(tmp_dir) / "*"
                 query = f"""LOAD IMAGE "{path}" INTO MyImages;"""
                 with self.assertRaises(Exception):
-                    execute_query_fetch_all(self.evadb, query)
+                    execute_query_fetch_all(
+                        self.evadb, query, do_not_print_exceptions=True
+                    )
                 result = execute_query_fetch_all(
                     self.evadb, "SELECT name FROM MyImages"
                 )
                 self.assertEqual(len(result), 1)
                 expected = Batch(pd.DataFrame([{"myimages.name": valid_images[0]}]))
                 self.assertEqual(expected, result)
 
@@ -501,27 +535,29 @@
 
         # Corrupt an image.
         with open(os.path.join(large_scale_image_files_path, "img0.jpg"), "w") as f:
             f.write("aa")
 
         with self.assertRaises(ExecutorError):
             load_query = f"LOAD IMAGE '{large_scale_image_files_path}/**/*.jpg' INTO MyLargeScaleImages;"
-            execute_query_fetch_all(self.evadb, load_query)
+            execute_query_fetch_all(
+                self.evadb, load_query, do_not_print_exceptions=True
+            )
 
         drop_query = "DROP TABLE IF EXISTS MyLargeScaleImages;"
         execute_query_fetch_all(self.evadb, drop_query)
 
         # Clean up large scale image directory.
         shutil.rmtree(large_scale_image_files_path)
 
     def test_load_pdfs(self):
         execute_query_fetch_all(
             self.evadb,
             f"""LOAD DOCUMENT '{EvaDB_ROOT_DIR}/data/documents/*.pdf' INTO pdfs;""",
         )
         result = execute_query_fetch_all(self.evadb, "SELECT * from pdfs;")
-        self.assertEqual(len(result.columns), 3)
-        self.assertEqual(len(result), 4)
+        self.assertEqual(len(result.columns), 4)
+        self.assertEqual(len(result), 26)
 
 
 if __name__ == "__main__":
     unittest.main()
```

### Comparing `evadb-0.2.9/test/integration_tests/test_load_pdf_executor.py` & `evadb-0.3.0/test/integration_tests/test_load_pdf_executor.py`

 * *Files 8% similar despite different names*

```diff
@@ -18,15 +18,15 @@
 import pytest
 
 from evadb.configuration.constants import EvaDB_ROOT_DIR
 from evadb.server.command_handler import execute_query_fetch_all
 
 
 @pytest.mark.notparallel
-class LoadExecutorTest(unittest.TestCase):
+class LoadPDFExecutorTests(unittest.TestCase):
     def setUp(self):
         self.evadb = get_evadb_for_testing()
         # reset the catalog manager before running each test
         self.evadb.catalog().reset()
 
     def tearDown(self):
         execute_query_fetch_all(self.evadb, "DROP TABLE IF EXISTS MyPDFs;")
```

### Comparing `evadb-0.2.9/test/integration_tests/test_open.py` & `evadb-0.3.0/test/integration_tests/test_open.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/integration_tests/test_optimizer_rules.py` & `evadb-0.3.0/test/integration_tests/test_optimizer_rules.py`

 * *Files 0% similar despite different names*

```diff
@@ -9,15 +9,15 @@
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import unittest
-from test.markers import ray_skip_marker
+from test.markers import gpu_skip_marker
 from test.util import (
     get_evadb_for_testing,
     get_physical_query_plan,
     load_udfs_for_testing,
     shutdown_ray,
 )
 
@@ -39,15 +39,15 @@
 from evadb.optimizer.rules.rules_manager import RulesManager, disable_rules
 from evadb.plan_nodes.predicate_plan import PredicatePlan
 from evadb.server.command_handler import execute_query_fetch_all
 from evadb.utils.stats import Timer
 
 
 @pytest.mark.notparallel
-@ray_skip_marker
+@gpu_skip_marker
 class OptimizerRulesTest(unittest.TestCase):
     @classmethod
     def setUpClass(cls):
         cls.evadb = get_evadb_for_testing()
         cls.evadb.catalog().reset()
         ua_detrac = f"{EvaDB_ROOT_DIR}/data/ua_detrac/ua_detrac.mp4"
         execute_query_fetch_all(cls.evadb, f"LOAD VIDEO '{ua_detrac}' INTO MyVideo;")
```

### Comparing `evadb-0.2.9/test/integration_tests/test_pytorch.py` & `evadb-0.3.0/test/integration_tests/test_pytorch.py`

 * *Files 1% similar despite different names*

```diff
@@ -10,33 +10,38 @@
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import os
 import unittest
-from test.markers import ocr_skip_marker, ray_only_marker, windows_skip_marker
+from test.markers import (
+    gpu_skip_marker,
+    ocr_skip_marker,
+    ray_skip_marker,
+    windows_skip_marker,
+)
 from test.util import (
     create_sample_video,
     file_remove,
     get_evadb_for_testing,
     load_udfs_for_testing,
     shutdown_ray,
 )
 
-import cv2
 import numpy as np
 import pandas.testing as pd_testing
 import pytest
 
 from evadb.configuration.constants import EvaDB_ROOT_DIR
 from evadb.executor.executor_utils import ExecutorError
 from evadb.models.storage.batch import Batch
 from evadb.server.command_handler import execute_query_fetch_all
 from evadb.udfs.udf_bootstrap_queries import Asl_udf_query, Mvit_udf_query
+from evadb.utils.generic_utils import try_to_import_cv2
 
 
 @pytest.mark.notparallel
 class PytorchTest(unittest.TestCase):
     @classmethod
     def setUpClass(cls):
         cls.evadb = get_evadb_for_testing()
@@ -81,15 +86,15 @@
 
     def setUp(self):
         self.addTypeEqualityFunc(Batch, self.assertBatchEqual)
 
     def tearDown(self) -> None:
         shutdown_ray()
 
-    @ray_only_marker
+    @ray_skip_marker
     def test_should_apply_parallel_match_sequential(self):
         # Parallel execution
         select_query = """SELECT id, obj.labels
                           FROM MyVideo JOIN LATERAL
                           FastRCNNObjectDetector(data)
                           AS obj(labels, bboxes, scores)
                          WHERE id < 20;"""
@@ -105,16 +110,17 @@
         seq_batch = execute_query_fetch_all(self.evadb, select_query)
         # Recover configuration back.
         self.evadb.config.update_value("experimental", "ray", True)
 
         self.assertEqual(len(par_batch), len(seq_batch))
         self.assertEqual(par_batch, seq_batch)
 
-    @ray_only_marker
+    @ray_skip_marker
     def test_should_project_parallel_match_sequential(self):
+        print(os.environ.get("ray"))
         create_udf_query = """CREATE UDF IF NOT EXISTS FaceDetector
                   INPUT  (frame NDARRAY UINT8(3, ANYDIM, ANYDIM))
                   OUTPUT (bboxes NDARRAY FLOAT32(ANYDIM, 4),
                           scores NDARRAY FLOAT32(ANYDIM))
                   TYPE  FaceDetection
                   IMPL  'evadb/udfs/face_detector.py';
         """
@@ -142,15 +148,17 @@
 
         select_query = """SELECT id, obj.labels
                           FROM parallelErrorVideo JOIN LATERAL
                           FastRCNNObjectDetector(data)
                           AS obj(labels, bboxes, scores)
                          WHERE id < 2;"""
         with self.assertRaises(ExecutorError):
-            execute_query_fetch_all(self.evadb, select_query)
+            execute_query_fetch_all(
+                self.evadb, select_query, do_not_print_exceptions=True
+            )
 
     @pytest.mark.torchtest
     def test_should_run_pytorch_and_fastrcnn_with_lateral_join(self):
         select_query = """SELECT id, obj.labels
                           FROM MyVideo JOIN LATERAL
                           FastRCNNObjectDetector(data)
                           AS obj(labels, bboxes, scores)
@@ -288,14 +296,18 @@
         tmp_dir_from_config = self.evadb.config.get_value("storage", "tmp_dir")
 
         img_save_path = os.path.join(tmp_dir_from_config, "dummy.jpg")
         try:
             os.remove(img_save_path)
         except FileNotFoundError:
             pass
+
+        try_to_import_cv2()
+        import cv2
+
         cv2.imwrite(img_save_path, img)
 
         similarity_query = """SELECT data FROM MyVideo WHERE id < 5
                     ORDER BY Similarity(FeatureExtractor(Open("{}")),
                                         FeatureExtractor(data))
                     LIMIT 1;""".format(
             img_save_path
@@ -326,14 +338,15 @@
 
         # non-trivial test case for MNIST
         res = actual_batch.frames
         self.assertTrue(res["ocrextractor.labels"][0][0] == "4")
         self.assertTrue(res["ocrextractor.scores"][2][0] > 0.9)
 
     @pytest.mark.torchtest
+    @gpu_skip_marker
     def test_should_run_extract_object(self):
         select_query = """
             SELECT id, T.iids, T.bboxes, T.scores, T.labels
             FROM MyVideo JOIN LATERAL EXTRACT_OBJECT(data, Yolo, NorFairTracker)
                 AS T(iids, labels, bboxes, scores)
             WHERE id < 30;
             """
```

### Comparing `evadb-0.2.9/test/integration_tests/test_rename_executor.py` & `evadb-0.3.0/test/integration_tests/test_rename_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/integration_tests/test_reuse.py` & `evadb-0.3.0/test/integration_tests/test_reuse.py`

 * *Files 2% similar despite different names*

```diff
@@ -12,15 +12,15 @@
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import gc
 import os
 import unittest
 from pathlib import Path
-from test.markers import duplicate_skip_marker, windows_skip_marker
+from test.markers import gpu_skip_marker, windows_skip_marker
 from test.util import (
     get_evadb_for_testing,
     get_logical_query_plan,
     load_udfs_for_testing,
     shutdown_ray,
 )
 
@@ -99,24 +99,25 @@
         select_query = """SELECT id, label FROM DETRAC JOIN
             LATERAL HFObjectDetector(data) AS Obj(score, label, bbox) WHERE id < 15;"""
         batches, exec_times = self._reuse_experiment([select_query, select_query])
         self._verify_reuse_correctness(select_query, batches[1])
         # reuse should be faster than no reuse
         self.assertTrue(exec_times[0] > exec_times[1])
 
-    @duplicate_skip_marker
+    @gpu_skip_marker
     def test_reuse_partial(self):
         select_query1 = """SELECT id, label FROM DETRAC JOIN
             LATERAL HFObjectDetector(data) AS Obj(score, label, bbox) WHERE id < 5;"""
         select_query2 = """SELECT id, label FROM DETRAC JOIN
             LATERAL HFObjectDetector(data) AS Obj(score, label, bbox) WHERE id < 15;"""
 
         batches, exec_times = self._reuse_experiment([select_query1, select_query2])
         self._verify_reuse_correctness(select_query2, batches[1])
 
+    @gpu_skip_marker
     def test_reuse_in_with_multiple_occurrences(self):
         select_query1 = """SELECT id, label FROM DETRAC JOIN
             LATERAL HFObjectDetector(data) AS Obj(score, label, bbox) WHERE id < 10;"""
 
         # multiple occurrences of the same function expression
         select_query2 = """SELECT id, HFObjectDetector(data).label FROM DETRAC JOIN
             LATERAL HFObjectDetector(data) AS Obj(score, label, bbox) WHERE id < 5;"""
@@ -133,52 +134,57 @@
         self._verify_reuse_correctness(select_query, reuse_batch)
 
         # different query format
         select_query = """SELECT id, HFObjectDetector(data).label FROM DETRAC WHERE ['car'] <@ HFObjectDetector(data).label AND id < 20"""
         reuse_batch = execute_query_fetch_all(self.evadb, select_query)
         self._verify_reuse_correctness(select_query, reuse_batch)
 
+    @gpu_skip_marker
     def test_reuse_logical_project_with_duplicate_query(self):
         project_query = (
             """SELECT id, HFObjectDetector(data).label FROM DETRAC WHERE id < 10;"""
         )
         batches, exec_times = self._reuse_experiment([project_query, project_query])
         self._verify_reuse_correctness(project_query, batches[1])
         # reuse should be faster than no reuse
         self.assertGreater(exec_times[0], exec_times[1])
 
+    @gpu_skip_marker
     def test_reuse_with_udf_in_predicate(self):
         select_query = """SELECT id FROM DETRAC WHERE ['car'] <@ HFObjectDetector(data).label AND id < 4"""
 
         batches, exec_times = self._reuse_experiment([select_query, select_query])
         self._verify_reuse_correctness(select_query, batches[1])
         # reuse should be faster than no reuse
         self.assertGreater(exec_times[0], exec_times[1])
 
+    @gpu_skip_marker
     def test_reuse_across_different_predicate_using_same_udf(self):
         query1 = """SELECT id FROM DETRAC WHERE ['car'] <@ HFObjectDetector(data).label AND id < 15"""
 
         query2 = """SELECT id FROM DETRAC WHERE ArrayCount(HFObjectDetector(data).label, 'car') > 3 AND id < 12;"""
 
         batches, exec_times = self._reuse_experiment([query1, query2])
         self._verify_reuse_correctness(query2, batches[1])
         # reuse should be faster than no reuse
         self.assertGreater(exec_times[0], exec_times[1])
 
+    @gpu_skip_marker
     def test_reuse_filter_with_project(self):
         project_query = """
             SELECT id, Yolo(data).labels FROM DETRAC WHERE id < 5;"""
         select_query = """
             SELECT id FROM DETRAC
             WHERE ArrayCount(Yolo(data).labels, 'car') > 3 AND id < 5;"""
         batches, exec_times = self._reuse_experiment([project_query, select_query])
         self._verify_reuse_correctness(select_query, batches[1])
         # reuse should be faster than no reuse
         self.assertGreater(exec_times[0], exec_times[1])
 
+    @gpu_skip_marker
     def test_reuse_in_extract_object(self):
         select_query = """
             SELECT id, T.iids, T.bboxes, T.scores, T.labels
             FROM DETRAC JOIN LATERAL EXTRACT_OBJECT(data, Yolo, NorFairTracker)
                 AS T(iids, labels, bboxes, scores)
             WHERE id < 30;
             """
```

### Comparing `evadb-0.2.9/test/integration_tests/test_s3_load_executor.py` & `evadb-0.3.0/test/integration_tests/test_s3_load_executor.py`

 * *Files 2% similar despite different names*

```diff
@@ -19,29 +19,26 @@
     create_dummy_batches,
     create_sample_video,
     file_remove,
     get_evadb_for_testing,
     shutdown_ray,
 )
 
-import boto3
 import pandas as pd
 import pytest
-from moto import mock_s3
 
 from evadb.configuration.constants import EvaDB_ROOT_DIR
 from evadb.models.storage.batch import Batch
 from evadb.parser.types import FileFormatType
 from evadb.server.command_handler import execute_query_fetch_all
+from evadb.utils.generic_utils import try_to_import_moto
 
 
 @pytest.mark.notparallel
 class S3LoadExecutorTest(unittest.TestCase):
-    mock_s3 = mock_s3()
-
     def setUp(self):
         self.evadb = get_evadb_for_testing()
         # reset the catalog manager before running each test
         self.evadb.catalog().reset()
         self.video_file_path = create_sample_video()
         self.multiple_video_file_path = f"{EvaDB_ROOT_DIR}/data/sample_videos/1"
         self.s3_download_dir = self.evadb.config.get_value("storage", "s3_download_dir")
@@ -49,15 +46,20 @@
         """Mocked AWS Credentials for moto."""
         os.environ["AWS_ACCESS_KEY_ID"] = "testing"
         os.environ["AWS_SECRET_ACCESS_KEY"] = "testing"
         os.environ["AWS_SECURITY_TOKEN"] = "testing"
         os.environ["AWS_SESSION_TOKEN"] = "testing"
         os.environ["AWS_DEFAULT_REGION"] = "us-east-1"
 
+        try_to_import_moto()
+        from moto import mock_s3
+
+        self.mock_s3 = mock_s3()
         self.mock_s3.start()
+        import boto3
 
         self.s3_client = boto3.client("s3")
 
     def upload_single_file(self, bucket_name="test-bucket"):
         self.s3_client.create_bucket(Bucket=bucket_name)
         self.s3_client.upload_file(self.video_file_path, bucket_name, "dummy.avi")
```

### Comparing `evadb-0.2.9/test/integration_tests/test_saliency.py` & `evadb-0.3.0/test/integration_tests/test_saliency.py`

 * *Files 3% similar despite different names*

```diff
@@ -33,14 +33,15 @@
     @classmethod
     def tearDownClass(cls):
         shutdown_ray()
         # execute_query_fetch_all("DROP TABLE IF EXISTS MyVideo;")
         execute_query_fetch_all(cls.evadb, "DROP TABLE IF EXISTS SALIENCY;")
         # file_remove("dummy.avi")
 
+    @unittest.skip("Not supported in current version")
     def test_saliency(self):
         Saliency1 = f"{EvaDB_ROOT_DIR}/data/saliency/test1.jpeg"
         create_udf_query = f"LOAD IMAGE '{Saliency1}' INTO SALIENCY;"
 
         execute_query_fetch_all(self.evadb, "DROP TABLE IF EXISTS SALIENCY;")
 
         execute_query_fetch_all(self.evadb, create_udf_query)
```

### Comparing `evadb-0.2.9/test/integration_tests/test_select_executor.py` & `evadb-0.3.0/test/integration_tests/test_select_executor.py`

 * *Files 0% similar despite different names*

```diff
@@ -557,15 +557,15 @@
         self.assertEqual(unnest_batch, expected)
 
     def test_should_raise_error_with_missing_alias_in_lateral_join(self):
         udf_name = "DummyMultiObjectDetector"
         query = """SELECT id, labels
                   FROM MyVideo JOIN LATERAL DummyMultiObjectDetector(data).labels;"""
         with self.assertRaises(SyntaxError) as cm:
-            execute_query_fetch_all(self.evadb, query)
+            execute_query_fetch_all(self.evadb, query, do_not_print_exceptions=True)
         self.assertEqual(
             str(cm.exception),
             f"TableValuedFunction {udf_name} should have alias.",
         )
 
         query = """SELECT id, labels
                   FROM MyVideo JOIN LATERAL
@@ -762,7 +762,20 @@
                 }
             )
         )
         self.assertEqual(batch, expected)
 
         batch = execute_query_fetch_all(self.evadb, "SELECT * FROM table1;")
         self.assertTrue("table1._row_id" in batch.columns)
+
+    def test_chunk_param_should_fail(self):
+        with self.assertRaises(AssertionError):
+            execute_query_fetch_all(
+                self.evadb,
+                "SELECT data from MyVideo chunk_size 4000 chunk_overlap 200;",
+            )
+
+        with self.assertRaises(AssertionError):
+            execute_query_fetch_all(
+                self.evadb,
+                "SELECT data from MemeImages chunk_size 4000 chunk_overlap 200;",
+            )
```

### Comparing `evadb-0.2.9/test/integration_tests/test_show_info_executor.py` & `evadb-0.3.0/test/integration_tests/test_show_info_executor.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/integration_tests/test_similarity.py` & `evadb-0.3.0/test/integration_tests/test_similarity.py`

 * *Files 12% similar despite different names*

```diff
@@ -10,30 +10,30 @@
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import os
 import unittest
-from test.markers import ray_skip_marker
+from test.markers import gpu_skip_marker
 from test.util import (
     create_sample_image,
     get_evadb_for_testing,
     load_udfs_for_testing,
     shutdown_ray,
 )
 
-import cv2
 import numpy as np
 import pandas as pd
 import pytest
 
 from evadb.models.storage.batch import Batch
 from evadb.server.command_handler import execute_query_fetch_all
 from evadb.storage.storage_engine import StorageEngine
+from evadb.utils.generic_utils import try_to_import_cv2
 
 
 @pytest.mark.notparallel
 class SimilarityTests(unittest.TestCase):
     def setUp(self):
         self.evadb = get_evadb_for_testing()
         self.evadb.catalog().reset()
@@ -101,14 +101,17 @@
             )
 
             # Create an actual image dataset.
             img_save_path = os.path.join(
                 self.evadb.config.get_value("storage", "tmp_dir"),
                 f"test_similar_img{i}.jpg",
             )
+            try_to_import_cv2()
+            import cv2
+
             cv2.imwrite(img_save_path, base_img)
             load_image_query = (
                 f"LOAD IMAGE '{img_save_path}' INTO testSimilarityImageDataset;"
             )
             execute_query_fetch_all(self.evadb, load_image_query)
 
             base_img -= 1
@@ -138,33 +141,40 @@
 
         base_img = np.array(np.ones((3, 3, 3)), dtype=np.uint8)
         base_img[0] -= 1
         base_img[2] += 1
 
         actual_open = actual_batch.frames["testsimilaritytable.data_col"].to_numpy()[0]
         self.assertTrue(np.array_equal(actual_open, base_img))
-        # actual_distance = actual_batch.frames["similarity.distance"].to_numpy()[0]
-        # self.assertEqual(actual_distance, 0)
 
         # Top 2 - assume table contains base data.
         select_query = """SELECT data_col FROM testSimilarityTable
                             ORDER BY Similarity(DummyFeatureExtractor(Open("{}")), DummyFeatureExtractor(data_col))
                             LIMIT 2;""".format(
             self.img_path
         )
         actual_batch = execute_query_fetch_all(self.evadb, select_query)
 
         actual_open = actual_batch.frames["testsimilaritytable.data_col"].to_numpy()[0]
         self.assertTrue(np.array_equal(actual_open, base_img))
         actual_open = actual_batch.frames["testsimilaritytable.data_col"].to_numpy()[1]
         self.assertTrue(np.array_equal(actual_open, base_img + 1))
-        # actual_distance = actual_batch.frames["similarity.distance"].to_numpy()[0]
-        # self.assertEqual(actual_distance, 0)
-        # actual_distance = actual_batch.frames["similarity.distance"].to_numpy()[1]
-        # self.assertEqual(actual_distance, 27)
+
+        # Top 2 - descending order
+        select_query = """SELECT data_col FROM testSimilarityTable
+                            ORDER BY Similarity(DummyFeatureExtractor(Open("{}")), DummyFeatureExtractor(data_col)) DESC
+                            LIMIT 2;""".format(
+            self.img_path
+        )
+        actual_batch = execute_query_fetch_all(self.evadb, select_query)
+
+        actual_open = actual_batch.frames["testsimilaritytable.data_col"].to_numpy()[0]
+        self.assertTrue(np.array_equal(actual_open, base_img + 4))
+        actual_open = actual_batch.frames["testsimilaritytable.data_col"].to_numpy()[1]
+        self.assertTrue(np.array_equal(actual_open, base_img + 3))
 
         ###########################################
         # Test case runs on feature vector table. #
         ###########################################
 
         # Top 1 - assume table contains feature data.
         select_query = """SELECT feature_col FROM testSimilarityFeatureTable
@@ -179,16 +189,14 @@
         base_img[2] += 1
         base_img = base_img.astype(np.float32).reshape(1, -1)
 
         actual_open = actual_batch.frames[
             "testsimilarityfeaturetable.feature_col"
         ].to_numpy()[0]
         self.assertTrue(np.array_equal(actual_open, base_img))
-        # actual_distance = actual_batch.frames["similarity.distance"].to_numpy()[0]
-        # self.assertEqual(actual_distance, 0)
 
         # Top 2 - assume table contains feature data.
         select_query = """SELECT feature_col FROM testSimilarityFeatureTable
                             ORDER BY Similarity(DummyFeatureExtractor(Open("{}")), feature_col)
                             LIMIT 2;""".format(
             self.img_path
         )
@@ -198,18 +206,14 @@
             "testsimilarityfeaturetable.feature_col"
         ].to_numpy()[0]
         self.assertTrue(np.array_equal(actual_open, base_img))
         actual_open = actual_batch.frames[
             "testsimilarityfeaturetable.feature_col"
         ].to_numpy()[1]
         self.assertTrue(np.array_equal(actual_open, base_img + 1))
-        # actual_distance = actual_batch.frames["similarity.distance"].to_numpy()[0]
-        # self.assertEqual(actual_distance, 0)
-        # actual_distance = actual_batch.frames["similarity.distance"].to_numpy()[1]
-        # self.assertEqual(actual_distance, 27)
 
     def test_should_do_vector_index_scan(self):
         ###########################################
         # Test case runs on feature vector table. #
         ###########################################
 
         # Execution without index scan.
@@ -284,14 +288,54 @@
                 )
             )
 
         # Cleanup
         self.evadb.catalog().drop_index_catalog_entry("testFaissIndexScanRewrite1")
         self.evadb.catalog().drop_index_catalog_entry("testFaissIndexScanRewrite2")
 
+    def test_should_not_do_vector_index_scan_with_desc_order(self):
+        # Execution with index scan.
+        create_index_query = """CREATE INDEX testFaissIndexScanRewrite
+                                    ON testSimilarityTable (DummyFeatureExtractor(data_col))
+                                    USING FAISS;"""
+        execute_query_fetch_all(self.evadb, create_index_query)
+
+        explain_query = """
+            EXPLAIN
+                SELECT data_col FROM testSimilarityTable WHERE dummy = 0
+                  ORDER BY Similarity(DummyFeatureExtractor(Open("{}")), DummyFeatureExtractor(data_col))
+                  LIMIT 3;
+        """.format(
+            "dummypath"
+        )
+        batch = execute_query_fetch_all(self.evadb, explain_query)
+
+        # Index scan should not be used.
+        self.assertFalse("FaissIndexScan" in batch.frames[0][0])
+
+        # Check results are in descending order
+        base_img = np.array(np.ones((3, 3, 3)), dtype=np.uint8)
+        base_img[0] -= 1
+        base_img[2] += 1
+
+        select_query = """SELECT data_col FROM testSimilarityTable
+                            ORDER BY Similarity(DummyFeatureExtractor(Open("{}")), DummyFeatureExtractor(data_col)) DESC
+                            LIMIT 2;""".format(
+            self.img_path
+        )
+        actual_batch = execute_query_fetch_all(self.evadb, select_query)
+
+        actual_open = actual_batch.frames["testsimilaritytable.data_col"].to_numpy()[0]
+        self.assertTrue(np.array_equal(actual_open, base_img + 4))
+        actual_open = actual_batch.frames["testsimilaritytable.data_col"].to_numpy()[1]
+        self.assertTrue(np.array_equal(actual_open, base_img + 3))
+
+        # Cleanup
+        self.evadb.catalog().drop_index_catalog_entry("testFaissIndexScanRewrite")
+
     def test_should_not_do_vector_index_scan_with_predicate(self):
         # Execution with index scan.
         create_index_query = """CREATE INDEX testFaissIndexScanRewrite
                                     ON testSimilarityTable (DummyFeatureExtractor(data_col))
                                     USING FAISS;"""
         execute_query_fetch_all(self.evadb, create_index_query)
 
@@ -320,15 +364,15 @@
                             ORDER BY Similarity(DummyFeatureExtractor(Open("{}")), DummyFeatureExtractor(data))
                             LIMIT 1;""".format(
             self.img_path
         )
         res_batch = execute_query_fetch_all(self.evadb, select_query)
         self.assertEqual(res_batch.frames["testsimilarityimagedataset._row_id"][0], 5)
 
-    @ray_skip_marker
+    @gpu_skip_marker
     def test_end_to_end_index_scan_should_work_correctly_on_image_dataset_qdrant(self):
         create_index_query = """CREATE INDEX testFaissIndexImageDataset
                                     ON testSimilarityImageDataset (DummyFeatureExtractor(data))
                                     USING QDRANT;"""
         execute_query_fetch_all(self.evadb, create_index_query)
         select_query = """SELECT _row_id FROM testSimilarityImageDataset
                             ORDER BY Similarity(DummyFeatureExtractor(Open("{}")), DummyFeatureExtractor(data))
```

### Comparing `evadb-0.2.9/test/integration_tests/test_udf_executor.py` & `evadb-0.3.0/test/integration_tests/test_udf_executor.py`

 * *Files 5% similar despite different names*

```diff
@@ -214,31 +214,35 @@
         entries = self.evadb.catalog().get_udf_metadata_entries_by_udf_name(udf_name)
         self.assertEqual(len(entries), 0)
 
     def test_should_raise_using_missing_udf(self):
         select_query = "SELECT id,DummyObjectDetector1(data) FROM MyVideo \
             ORDER BY id;"
         with self.assertRaises(BinderError) as cm:
-            execute_query_fetch_all(self.evadb, select_query)
+            execute_query_fetch_all(
+                self.evadb, select_query, do_not_print_exceptions=True
+            )
 
         err_msg = (
-            "UDF with name DummyObjectDetector1 does not exist in the catalog. "
-            "Please create the UDF using CREATE UDF command."
+            "Function 'DummyObjectDetector1' does not exist in the catalog. "
+            "Please create the function using CREATE UDF command."
         )
         self.assertEqual(str(cm.exception), err_msg)
 
     def test_should_raise_for_udf_name_mismatch(self):
         create_udf_query = """CREATE UDF TestUDF
                   INPUT  (Frame_Array NDARRAY UINT8(3, 256, 256))
                   OUTPUT (label NDARRAY STR(10))
                   TYPE  Classification
                   IMPL  'test/util.py';
         """
         with self.assertRaises(ExecutorError):
-            execute_query_fetch_all(self.evadb, create_udf_query)
+            execute_query_fetch_all(
+                self.evadb, create_udf_query, do_not_print_exceptions=True
+            )
 
     def test_should_raise_if_udf_file_is_modified(self):
         execute_query_fetch_all(self.evadb, "DROP UDF DummyObjectDetector;")
 
         # Test IF EXISTS
         execute_query_fetch_all(self.evadb, "DROP UDF IF EXISTS DummyObjectDetector;")
 
@@ -264,16 +268,17 @@
             tmp_file.write("#comment")
             tmp_file.seek(0)
 
             select_query = (
                 "SELECT id,DummyObjectDetector(data) FROM MyVideo ORDER BY id;"
             )
 
-            with self.assertRaises(AssertionError):
-                execute_query_fetch_all(self.evadb, select_query)
+            # disabling warning for UDF modificiation for now
+            # with self.assertRaises(AssertionError):
+            execute_query_fetch_all(self.evadb, select_query)
 
     def test_create_udf_with_decorators(self):
         execute_query_fetch_all(
             self.evadb, "DROP UDF IF EXISTS DummyObjectDetectorDecorators;"
         )
         create_udf_query = """CREATE UDF DummyObjectDetectorDecorators
                   IMPL  'test/util.py';
```

### Comparing `evadb-0.2.9/test/interfaces/__init__.py` & `evadb-0.3.0/test/integration_tests/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/interfaces/relational/__init__.py` & `evadb-0.3.0/test/interfaces/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/interfaces/relational/test_relational_api.py` & `evadb-0.3.0/test/interfaces/relational/test_relational_api.py`

 * *Files 18% similar despite different names*

```diff
@@ -9,14 +9,15 @@
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import unittest
+from test.markers import qdrant_skip_marker
 from test.util import (
     DummyObjectDetector,
     create_sample_video,
     load_udfs_for_testing,
     shutdown_ray,
     suffix_pytest_xdist_worker_id_to_dir,
 )
@@ -157,14 +158,15 @@
         )
 
         assert_frame_equal(
             filtered_rel.select("_row_id, id").df(),
             cursor.query("select _row_id, id from mnist_video where id > 10;").df(),
         )
 
+    @qdrant_skip_marker
     def test_create_index(self):
         cursor = self.conn.cursor()
 
         # load some images
         rel = cursor.load(
             self.images,
             table_name="meme_images",
@@ -321,47 +323,157 @@
         drop_table = cursor.drop_table("dummy_video", if_exists=False)
         with self.assertRaises(ExecutorError):
             drop_table.execute()
 
     def test_pdf_similarity_search(self):
         conn = connect()
         cursor = conn.cursor()
-        pdf_path1 = f"{EvaDB_ROOT_DIR}/data/documents/state_of_the_union.pdf"
-        pdf_path2 = f"{EvaDB_ROOT_DIR}/data/documents/layout-parser-paper.pdf"
-
-        load_pdf = cursor.load(file_regex=pdf_path1, format="PDF", table_name="PDFs")
-        load_pdf.execute()
+        pdf_path = f"{EvaDB_ROOT_DIR}/data/documents/state_of_the_union.pdf"
 
-        load_pdf = cursor.load(file_regex=pdf_path2, format="PDF", table_name="PDFs")
+        load_pdf = cursor.load(file_regex=pdf_path, format="PDF", table_name="PDFs")
         load_pdf.execute()
 
-        udf_check = cursor.drop_udf("SentenceTransformerFeatureExtractor")
+        udf_check = cursor.drop_udf("SentenceFeatureExtractor")
         udf_check.df()
         udf = cursor.create_udf(
-            "SentenceTransformerFeatureExtractor",
+            "SentenceFeatureExtractor",
             True,
-            f"{EvaDB_ROOT_DIR}/evadb/udfs/sentence_transformer_feature_extractor.py",
+            f"{EvaDB_ROOT_DIR}/evadb/udfs/sentence_feature_extractor.py",
         )
         udf.execute()
 
         cursor.create_vector_index(
             "faiss_index",
             table_name="PDFs",
-            expr="SentenceTransformerFeatureExtractor(data)",
-            using="QDRANT",
+            expr="SentenceFeatureExtractor(data)",
+            using="FAISS",
         ).df()
 
         query = (
             cursor.table("PDFs")
             .order(
                 """Similarity(
-                    SentenceTransformerFeatureExtractor('When was the NATO created?'), SentenceTransformerFeatureExtractor(data)
+                    SentenceFeatureExtractor('When was the NATO created?'), SentenceFeatureExtractor(data)
                 ) DESC"""
             )
             .limit(3)
             .select("data")
         )
         output = query.df()
         self.assertEqual(len(output), 3)
         self.assertTrue("pdfs.data" in output.columns)
 
         cursor.drop_index("faiss_index").df()
+
+    def test_langchain_split_doc(self):
+        conn = connect()
+        cursor = conn.cursor()
+        pdf_path1 = f"{EvaDB_ROOT_DIR}/data/documents/state_of_the_union.pdf"
+
+        load_pdf = cursor.load(
+            file_regex=pdf_path1, format="DOCUMENT", table_name="docs"
+        )
+        load_pdf.execute()
+
+        result1 = (
+            cursor.table("docs", chunk_size=2000, chunk_overlap=0).select("data").df()
+        )
+
+        result2 = (
+            cursor.table("docs", chunk_size=4000, chunk_overlap=2000)
+            .select("data")
+            .df()
+        )
+
+        self.assertEqual(len(result1), len(result2))
+
+        result1 = cursor.table("docs").select("data").df()
+
+        result2 = cursor.query(
+            "SELECT data from docs chunk_size 4000 chunk_overlap 200"
+        ).df()
+        self.assertEqual(len(result1), len(result2))
+
+    def test_show_relational(self):
+        video_file_path = create_sample_video(10)
+
+        cursor = self.conn.cursor()
+        # load video
+        rel = cursor.load(
+            video_file_path,
+            table_name="dummy_video",
+            format="video",
+        )
+        rel.execute()
+
+        result = cursor.show("tables").df()
+        self.assertEqual(len(result), 1)
+        self.assertEqual(result["name"][0], "dummy_video")
+
+    def test_explain_relational(self):
+        video_file_path = create_sample_video(10)
+
+        cursor = self.conn.cursor()
+        # load video
+        rel = cursor.load(
+            video_file_path,
+            table_name="dummy_video",
+            format="video",
+        )
+        rel.execute()
+
+        result = cursor.explain("SELECT * FROM dummy_video").df()
+        self.assertEqual(len(result), 1)
+        self.assertEqual(
+            result[0][0],
+            "|__ ProjectPlan\n    |__ SeqScanPlan\n        |__ StoragePlan\n",
+        )
+
+    def test_rename_relational(self):
+        video_file_path = create_sample_video(10)
+
+        cursor = self.conn.cursor()
+        # load video
+        rel = cursor.load(
+            video_file_path,
+            table_name="dummy_video",
+            format="video",
+        )
+        rel.execute()
+
+        cursor.rename("dummy_video", "dummy_video_renamed").df()
+
+        result = cursor.show("tables").df()
+
+        self.assertEqual(len(result), 1)
+        self.assertEqual(result["name"][0], "dummy_video_renamed")
+
+    def test_create_table_relational(self):
+        cursor = self.conn.cursor()
+
+        cursor.create_table(
+            table_name="dummy_table",
+            if_not_exists=True,
+            columns="id INTEGER, name text(30)",
+        ).df()
+
+        result = cursor.show("tables").df()
+
+        self.assertEqual(len(result), 1)
+        self.assertEqual(result["name"][0], "dummy_table")
+
+        # if_not_exists=True should not raise error
+        # rel = cursor.create_table(table_name="dummy_table", if_not_exists=True, columns="id INTEGER, name text(30)")
+        # rel.execute()
+
+        # if_not_exists=False should raise error
+        rel = cursor.create_table(
+            table_name="dummy_table",
+            if_not_exists=False,
+            columns="id INTEGER, name text(30)",
+        )
+        with self.assertRaises(ExecutorError):
+            rel.execute()
+
+
+if __name__ == "__main__":
+    unittest.main()
```

### Comparing `evadb-0.2.9/test/markers.py` & `evadb-0.3.0/test/markers.py`

 * *Files 7% similar despite different names*

```diff
@@ -14,42 +14,50 @@
 # limitations under the License.
 
 import os
 import sys
 
 import pytest
 
+from evadb.utils.generic_utils import is_gpu_available
+
 asyncio_skip_marker = pytest.mark.skipif(
     sys.version_info < (3, 8), reason="Test case requires asyncio support"
 )
 
+qdrant_skip_marker = pytest.mark.skipif(
+    sys.version_info.minor == 11,
+    reason="qdrant requires grcpio which is broken on 3.11",
+)
+
 windows_skip_marker = pytest.mark.skipif(
     sys.platform == "win32", reason="Test case not supported on Windows"
 )
 
 linux_skip_marker = pytest.mark.skipif(
     sys.platform == "linux", reason="Test case not supported on Linux"
 )
 
+macos_skip_marker = pytest.mark.skipif(
+    "darwin" in sys.platform, reason="Test case not supported on MacOS"
+)
+
 memory_skip_marker = pytest.mark.skipif(
     sys.platform == "linux", reason="Test case consumes too much memory"
 )
 
 ray_skip_marker = pytest.mark.skipif(
-    os.environ.get("ray") is None,
-    reason="Skip test for ray execution.",
+    os.environ.get("ray") is None, reason="Run only if Ray is enabled"
 )
 
-ray_only_marker = pytest.mark.skipif(
-    os.environ.get("ray") is not None,
-    reason="Run only if ray is enabled",
-)
-
-duplicate_skip_marker = pytest.mark.skipif(
+redundant_test_skip_marker = pytest.mark.skipif(
     sys.platform == "linux",
     reason="Test case is duplicate. Disabling to speed up test suite",
 )
 
-ocr_skip_marker = pytest.mark.skipif(
-    sys.platform == "linux",
+ocr_skip_marker = pytest.mark.skip(
     reason="We do not have built-in support for OCR",
 )
+
+gpu_skip_marker = pytest.mark.skipif(
+    is_gpu_available() is False, reason="Run only if gpu is available"
+)
```

### Comparing `evadb-0.2.9/test/models/__init__.py` & `evadb-0.3.0/test/interfaces/relational/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/models/catalog/__init__.py` & `evadb-0.3.0/test/models/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/models/catalog/test_frame_info.py` & `evadb-0.3.0/test/models/catalog/test_frame_info.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/models/storage/__init__.py` & `evadb-0.3.0/test/models/catalog/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/models/storage/test_batch.py` & `evadb-0.3.0/test/models/storage/test_batch.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/optimizer/__init__.py` & `evadb-0.3.0/test/models/storage/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/optimizer/rules/__init__.py` & `evadb-0.3.0/test/optimizer/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/optimizer/rules/test_rules.py` & `evadb-0.3.0/test/optimizer/rules/test_rules.py`

 * *Files 13% similar despite different names*

```diff
@@ -33,15 +33,14 @@
     CombineSimilarityOrderByAndLimitToVectorIndexScan,
     EmbedFilterIntoGet,
     EmbedSampleIntoGet,
     LogicalApplyAndMergeToPhysical,
     LogicalApplyAndMergeToRayPhysical,
     LogicalCreateFromSelectToPhysical,
     LogicalCreateIndexToVectorIndex,
-    LogicalCreateMaterializedViewToPhysical,
     LogicalCreateToPhysical,
     LogicalCreateUDFToPhysical,
     LogicalDeleteToPhysical,
     LogicalDerivedGetToPhysical,
     LogicalDropObjectToPhysical,
     LogicalExchangeToPhysical,
     LogicalExplainToPhysical,
@@ -71,14 +70,15 @@
     RuleType,
     XformExtractObjectToLinearFlow,
     XformLateralJoinToLinearFlow,
 )
 from evadb.optimizer.rules.rules_manager import RulesManager, disable_rules
 from evadb.parser.types import JoinType
 from evadb.server.command_handler import execute_query_fetch_all
+from evadb.utils.generic_utils import is_ray_enabled_and_installed
 
 
 @pytest.mark.notparallel
 class RulesTest(unittest.TestCase):
     @classmethod
     def setUpClass(cls):
         cls.evadb = get_evadb_for_testing()
@@ -109,15 +109,14 @@
         for promise in rewrite_promises:
             self.assertTrue(promise > Promise.IMPLEMENTATION_DELIMITER)
 
         # Promise of implementation rules should be lesser than rewrite rules
         implementation_promises = [
             Promise.LOGICAL_EXCHANGE_TO_PHYSICAL,
             Promise.LOGICAL_UNION_TO_PHYSICAL,
-            Promise.LOGICAL_MATERIALIZED_VIEW_TO_PHYSICAL,
             Promise.LOGICAL_GROUPBY_TO_PHYSICAL,
             Promise.LOGICAL_ORDERBY_TO_PHYSICAL,
             Promise.LOGICAL_LIMIT_TO_PHYSICAL,
             Promise.LOGICAL_INSERT_TO_PHYSICAL,
             Promise.LOGICAL_DELETE_TO_PHYSICAL,
             Promise.LOGICAL_RENAME_TO_PHYSICAL,
             Promise.LOGICAL_DROP_OBJECT_TO_PHYSICAL,
@@ -192,14 +191,15 @@
                 any(
                     isinstance(rule, type(x))
                     for x in RulesManager(self.evadb.config).logical_rules
                 )
             )
 
         ray_enabled = self.evadb.config.get_value("experimental", "ray")
+        ray_enabled_and_installed = is_ray_enabled_and_installed(ray_enabled)
 
         # For the current version, we choose either the distributed or the
         # sequential rule, because we do not have a logic to choose one over
         # the other in the current optimizer. Sequential rewrite is currently
         # embedded inside distributed rule if ray is enabled. The rule itself
         # has some simple heuristics to choose one over the other.
         supported_implementation_rules = [
@@ -209,37 +209,36 @@
             LogicalCreateUDFToPhysical(),
             LogicalDropObjectToPhysical(),
             LogicalInsertToPhysical(),
             LogicalDeleteToPhysical(),
             LogicalLoadToPhysical(),
             LogicalGetToSeqScan(),
             LogicalProjectToRayPhysical()
-            if ray_enabled
+            if ray_enabled_and_installed
             else LogicalProjectToPhysical(),
             LogicalDerivedGetToPhysical(),
             LogicalUnionToPhysical(),
             LogicalGroupByToPhysical(),
             LogicalOrderByToPhysical(),
             LogicalLimitToPhysical(),
             LogicalJoinToPhysicalNestedLoopJoin(),
             LogicalLateralJoinToPhysical(),
             LogicalFunctionScanToPhysical(),
             LogicalJoinToPhysicalHashJoin(),
-            LogicalCreateMaterializedViewToPhysical(),
             LogicalFilterToPhysical(),
             LogicalApplyAndMergeToRayPhysical()
-            if ray_enabled
+            if ray_enabled_and_installed
             else LogicalApplyAndMergeToPhysical(),
             LogicalShowToPhysical(),
             LogicalExplainToPhysical(),
             LogicalCreateIndexToVectorIndex(),
             LogicalVectorIndexScanToPhysical(),
         ]
 
-        if ray_enabled:
+        if ray_enabled_and_installed:
             supported_implementation_rules.append(LogicalExchangeToPhysical())
         self.assertEqual(
             len(supported_implementation_rules),
             len(RulesManager(self.evadb.config).implementation_rules),
         )
 
         for rule in supported_implementation_rules:
```

### Comparing `evadb-0.2.9/test/optimizer/test_binder.py` & `evadb-0.3.0/test/optimizer/test_binder.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/optimizer/test_cascade_optimizer.py` & `evadb-0.3.0/test/optimizer/test_cascade_optimizer.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/optimizer/test_cost_model.py` & `evadb-0.3.0/test/optimizer/test_cost_model.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/optimizer/test_group.py` & `evadb-0.3.0/test/optimizer/test_group.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/optimizer/test_memo.py` & `evadb-0.3.0/test/optimizer/test_memo.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/optimizer/test_optimizer_context.py` & `evadb-0.3.0/test/optimizer/test_optimizer_context.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/optimizer/test_optimizer_task.py` & `evadb-0.3.0/test/optimizer/test_optimizer_task.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/optimizer/test_optimizer_utils.py` & `evadb-0.3.0/test/optimizer/test_optimizer_utils.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/optimizer/test_statement_to_opr_converter.py` & `evadb-0.3.0/test/optimizer/test_statement_to_opr_converter.py`

 * *Files 2% similar despite different names*

```diff
@@ -19,15 +19,14 @@
 from mock import MagicMock, patch
 
 from evadb.optimizer.operators import (
     Dummy,
     LogicalApplyAndMerge,
     LogicalCreate,
     LogicalCreateIndex,
-    LogicalCreateMaterializedView,
     LogicalCreateUDF,
     LogicalDelete,
     LogicalDropObject,
     LogicalExchange,
     LogicalExplain,
     LogicalExtractObject,
     LogicalFilter,
@@ -247,17 +246,14 @@
         create_plan = LogicalCreate(MagicMock(), MagicMock())
         create_udf_plan = LogicalCreateUDF(
             MagicMock(), MagicMock(), MagicMock(), MagicMock(), MagicMock(), MagicMock()
         )
         create_index_plan = LogicalCreateIndex(
             MagicMock(), MagicMock(), MagicMock(), MagicMock(), MagicMock()
         )
-        create_materialized_view_plan = LogicalCreateMaterializedView(
-            MagicMock(), MagicMock(), MagicMock(), MagicMock()
-        )
         delete_plan = LogicalDelete(MagicMock())
         insert_plan = LogicalInsert(
             MagicMock(), MagicMock(), [MagicMock()], [MagicMock()]
         )
         query_derived_plan = LogicalQueryDerivedGet(MagicMock())
         load_plan = LogicalLoadData(MagicMock(), MagicMock(), MagicMock(), MagicMock())
         limit_plan = LogicalLimit(MagicMock())
@@ -285,15 +281,14 @@
         )
         create_plan.append_child(create_udf_plan)
 
         plans.append(dummy_plan)
         plans.append(create_plan)
         plans.append(create_udf_plan)
         plans.append(create_index_plan)
-        plans.append(create_materialized_view_plan)
         plans.append(delete_plan)
         plans.append(insert_plan)
         plans.append(query_derived_plan)
         plans.append(load_plan)
         plans.append(limit_plan)
         plans.append(rename_plan)
         plans.append(drop_plan)
@@ -334,8 +329,8 @@
                 self.assertNotEqual(plans[i - 1], plans[i])
 
         derived_operators = list(get_all_subclasses(Operator))
 
         for derived_operator in derived_operators:
             sig = signature(derived_operator.__init__)
             params = sig.parameters
-            self.assertLess(len(params), 10)
+            self.assertLess(len(params), 15)
```

### Comparing `evadb-0.2.9/test/parser/__init__.py` & `evadb-0.3.0/test/optimizer/rules/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/parser/test_parser.py` & `evadb-0.3.0/test/parser/test_parser.py`

 * *Files 1% similar despite different names*

```diff
@@ -19,15 +19,14 @@
 from evadb.expression.abstract_expression import ExpressionType
 from evadb.expression.comparison_expression import ComparisonExpression
 from evadb.expression.constant_value_expression import ConstantValueExpression
 from evadb.expression.function_expression import FunctionExpression
 from evadb.expression.tuple_value_expression import TupleValueExpression
 from evadb.parser.alias import Alias
 from evadb.parser.create_index_statement import CreateIndexStatement
-from evadb.parser.create_mat_view_statement import CreateMaterializedViewStatement
 from evadb.parser.create_statement import (
     ColConstraintInfo,
     ColumnDefinition,
     CreateTableStatement,
 )
 from evadb.parser.create_udf_statement import CreateUDFStatement
 from evadb.parser.delete_statement import DeleteTableStatement
@@ -130,32 +129,32 @@
         self.assertEqual(inner_stmt.from_table.table.table_name, "TAIPAI")
 
     def test_explain_ddl_statement(self):
         parser = Parser()
 
         select_query = """SELECT id, Yolo(frame).labels FROM MyVideo
                         WHERE id<5; """
-        explain_query = "EXPLAIN CREATE MATERIALIZED VIEW uadtrac_fastRCNN (id, labels) AS {}".format(
+        explain_query = "EXPLAIN CREATE TABLE uadtrac_fastRCNN AS {}".format(
             select_query
         )
 
         evadb_statement_list = parser.parse(explain_query)
 
         # check explain stmt itself
         self.assertIsInstance(evadb_statement_list, list)
         self.assertEqual(len(evadb_statement_list), 1)
         self.assertEqual(evadb_statement_list[0].stmt_type, StatementType.EXPLAIN)
 
         # check inner stmt
         inner_stmt = evadb_statement_list[0].explainable_stmt
-        self.assertEqual(inner_stmt.stmt_type, StatementType.CREATE_MATERIALIZED_VIEW)
+        self.assertEqual(inner_stmt.stmt_type, StatementType.CREATE)
 
         # check inner stmt from
         self.assertIsNotNone(
-            inner_stmt.view_info, TableRef(TableInfo("uadetrac_fastRCNN"))
+            inner_stmt.table_info, TableRef(TableInfo("uadetrac_fastRCNN"))
         )
 
     def test_create_table_statement(self):
         parser = Parser()
 
         single_queries = []
         single_queries.append(
@@ -445,17 +444,17 @@
 
         # where_clause
         self.assertIsNotNone(select_stmt.where_clause)
 
         # orderby_clause
         self.assertIsNotNone(select_stmt.orderby_list)
         self.assertEqual(len(select_stmt.orderby_list), 2)
-        self.assertEqual(select_stmt.orderby_list[0][0].col_name, "CLASS")
+        self.assertEqual(select_stmt.orderby_list[0][0].name, "CLASS")
         self.assertEqual(select_stmt.orderby_list[0][1], ParserOrderBySortType.ASC)
-        self.assertEqual(select_stmt.orderby_list[1][0].col_name, "REDNESS")
+        self.assertEqual(select_stmt.orderby_list[1][0].name, "REDNESS")
         self.assertEqual(select_stmt.orderby_list[1][1], ParserOrderBySortType.DESC)
 
     def test_select_statement_limit_class(self):
         """Testing limit clause in select statement
         Class: SelectStatement"""
 
         parser = Parser()
@@ -484,17 +483,17 @@
 
         # where_clause
         self.assertIsNotNone(select_stmt.where_clause)
 
         # orderby_clause
         self.assertIsNotNone(select_stmt.orderby_list)
         self.assertEqual(len(select_stmt.orderby_list), 2)
-        self.assertEqual(select_stmt.orderby_list[0][0].col_name, "CLASS")
+        self.assertEqual(select_stmt.orderby_list[0][0].name, "CLASS")
         self.assertEqual(select_stmt.orderby_list[0][1], ParserOrderBySortType.ASC)
-        self.assertEqual(select_stmt.orderby_list[1][0].col_name, "REDNESS")
+        self.assertEqual(select_stmt.orderby_list[1][0].name, "REDNESS")
         self.assertEqual(select_stmt.orderby_list[1][1], ParserOrderBySortType.DESC)
 
         # limit_count
         self.assertIsNotNone(select_stmt.limit_count)
         self.assertEqual(select_stmt.limit_count, ConstantValueExpression(3))
 
     def test_select_statement_sample_class(self):
@@ -679,15 +678,15 @@
     def test_nested_select_statement(self):
         parser = Parser()
         sub_query = """SELECT CLASS FROM TAIPAI WHERE CLASS = 'VAN'"""
         nested_query = """SELECT ID FROM ({}) AS T;""".format(sub_query)
         parsed_sub_query = parser.parse(sub_query)[0]
         actual_stmt = parser.parse(nested_query)[0]
         self.assertEqual(actual_stmt.stmt_type, StatementType.SELECT)
-        self.assertEqual(actual_stmt.target_list[0].col_name, "ID")
+        self.assertEqual(actual_stmt.target_list[0].name, "ID")
         self.assertEqual(
             actual_stmt.from_table, TableRef(parsed_sub_query, alias=Alias("T"))
         )
 
         sub_query = """SELECT Yolo(frame).bbox FROM autonomous_vehicle_1
                               WHERE Yolo(frame).label = 'vehicle'"""
         nested_query = """SELECT Licence_plate(bbox) FROM
@@ -733,30 +732,25 @@
         )
         select_stmt = SelectStatement()
         self.assertNotEqual(load_stmt, insert_stmt)
         self.assertNotEqual(insert_stmt, load_stmt)
         self.assertNotEqual(create_udf, insert_stmt)
         self.assertNotEqual(select_stmt, create_udf)
 
-    def test_materialized_view(self):
+    def test_create_table_from_select(self):
         select_query = """SELECT id, Yolo(frame).labels FROM MyVideo
                         WHERE id<5; """
-        query = "CREATE MATERIALIZED VIEW uadtrac_fastRCNN (id, labels) AS {}".format(
-            select_query
-        )
+        query = "CREATE TABLE uadtrac_fastRCNN AS {}".format(select_query)
         parser = Parser()
         mat_view_stmt = parser.parse(query)
         select_stmt = parser.parse(select_query)
-        expected_stmt = CreateMaterializedViewStatement(
+        expected_stmt = CreateTableStatement(
             TableInfo("uadtrac_fastRCNN"),
-            [
-                ColumnDefinition("id", None, None, None),
-                ColumnDefinition("labels", None, None, None),
-            ],
             False,
+            [],
             select_stmt[0],
         )
         self.assertEqual(mat_view_stmt[0], expected_stmt)
 
     def test_join(self):
         select_query = """SELECT table1.a FROM table1 JOIN table2
                     ON table1.a = table2.a; """
```

### Comparing `evadb-0.2.9/test/parser/test_parser_statements.py` & `evadb-0.3.0/test/parser/test_parser_statements.py`

 * *Files 2% similar despite different names*

```diff
@@ -58,15 +58,15 @@
             """LOAD CSV 'data/meta.csv' INTO
                              MyMeta (id, frame_id, video_id, label);""",
             """SELECT Licence_plate(bbox) FROM
                             (SELECT Yolo(frame).bbox FROM autonomous_vehicle_1
                               WHERE Yolo(frame).label = 'vehicle') AS T
                           WHERE Is_suspicious(bbox) = 1 AND
                                 Licence_plate(bbox) = '12345';""",
-            """CREATE MATERIALIZED VIEW uadtrac_fastRCNN (id, labels) AS
+            """CREATE TABLE uadtrac_fastRCNN AS
                SELECT id, Yolo(frame).labels FROM MyVideo
                         WHERE id<5; """,
             """SELECT table1.a FROM table1 JOIN table2
             ON table1.a = table2.a WHERE table1.a <= 5""",
             """SELECT table1.a FROM table1 JOIN table2
             ON table1.a = table2.a JOIN table3
             ON table3.a = table1.a WHERE table1.a <= 5""",
@@ -118,15 +118,15 @@
             """Load csv 'data/meta.csv' into
                 MyMeta (id, Frame_ID, video_ID, label);""",
             """select Licence_plate(bbox) from
                 (select Yolo(Frame).bbox from autonomous_vehicle_1
                 where Yolo(frame).label = 'vehicle') as T
                 where is_suspicious(bbox) = 1 and
                 Licence_plate(bbox) = '12345';""",
-            """Create materialized view UADTrac_FastRCNN (id, labels) as
+            """Create TABLE UADTrac_FastRCNN as
                 Select id, YoloV5(Frame).labels from MyVideo
                     where id<5; """,
             """Select Table1.A from Table1 join Table2
                 on Table1.A = Table2.a where Table1.A <= 5""",
             """Select Table1.A from Table1 Join Table2
                     On Table1.a = Table2.A Join Table3
                 On Table3.A = Table1.A where Table1.a <= 5""",
```

### Comparing `evadb-0.2.9/test/plan_nodes/__init__.py` & `evadb-0.3.0/test/parser/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/plan_nodes/test_plan.py` & `evadb-0.3.0/test/plan_nodes/test_plan.py`

 * *Files 6% similar despite different names*

```diff
@@ -19,15 +19,14 @@
 import pytest
 
 from evadb.catalog.catalog_type import ColumnType
 from evadb.catalog.models.column_catalog import ColumnCatalogEntry
 from evadb.parser.table_ref import TableInfo, TableRef
 from evadb.parser.types import FileFormatType, ObjectType
 from evadb.plan_nodes.abstract_plan import AbstractPlan
-from evadb.plan_nodes.create_mat_view_plan import CreateMaterializedViewPlan
 from evadb.plan_nodes.create_plan import CreatePlan
 from evadb.plan_nodes.create_udf_plan import CreateUDFPlan
 from evadb.plan_nodes.drop_object_plan import DropObjectPlan
 from evadb.plan_nodes.insert_plan import InsertPlan
 from evadb.plan_nodes.load_data_plan import LoadDataPlan
 from evadb.plan_nodes.rename_plan import RenamePlan
 from evadb.plan_nodes.types import PlanOprType
@@ -122,22 +121,14 @@
 
     def test_union_plan(self):
         all = True
         plan = UnionPlan(all)
         self.assertEqual(plan.opr_type, PlanOprType.UNION)
         self.assertEqual(plan.all, all)
 
-    def test_create_materialized_view_plan(self):
-        dummy_view = TableRef(TableInfo("dummy"))
-        columns = ["id", "id2"]
-        plan = CreateMaterializedViewPlan(dummy_view, columns)
-        self.assertEqual(plan.opr_type, PlanOprType.CREATE_MATERIALIZED_VIEW)
-        self.assertEqual(plan.view, dummy_view)
-        self.assertEqual(plan.columns, columns)
-
     def test_abstract_plan_str(self):
         derived_plan_classes = list(get_all_subclasses(AbstractPlan))
         for derived_plan_class in derived_plan_classes:
             sig = signature(derived_plan_class.__init__)
             params = sig.parameters
             plan_dict = {}
             if isabstract(derived_plan_class) is False:
```

### Comparing `evadb-0.2.9/test/readers/__init__.py` & `evadb-0.3.0/test/plan_nodes/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/readers/test_csv_reader.py` & `evadb-0.3.0/test/readers/test_csv_reader.py`

 * *Files 21% similar despite different names*

```diff
@@ -24,17 +24,17 @@
         self.csv_file_path = create_sample_csv()
 
     def tearDown(self):
         file_remove("dummy.csv")
 
     def test_should_return_one_batch(self):
         column_list = [
-            TupleValueExpression(col_name="id", table_alias="dummy"),
-            TupleValueExpression(col_name="frame_id", table_alias="dummy"),
-            TupleValueExpression(col_name="video_id", table_alias="dummy"),
+            TupleValueExpression(name="id", table_alias="dummy"),
+            TupleValueExpression(name="frame_id", table_alias="dummy"),
+            TupleValueExpression(name="video_id", table_alias="dummy"),
         ]
 
         # call the CSVReader
         csv_loader = CSVReader(
             file_url=self.csv_file_path,
             column_list=column_list,
         )
```

### Comparing `evadb-0.2.9/test/readers/test_decord_reader.py` & `evadb-0.3.0/test/readers/test_decord_reader.py`

 * *Files 4% similar despite different names*

```diff
@@ -28,20 +28,22 @@
 from evadb.constants import AUDIORATE, IFRAMES
 from evadb.expression.abstract_expression import ExpressionType
 from evadb.expression.comparison_expression import ComparisonExpression
 from evadb.expression.constant_value_expression import ConstantValueExpression
 from evadb.expression.logical_expression import LogicalExpression
 from evadb.expression.tuple_value_expression import TupleValueExpression
 from evadb.readers.decord_reader import DecordReader
+from evadb.utils.generic_utils import try_to_import_decord
 
 
 @pytest.mark.notparallel
 class DecordLoaderTest(unittest.TestCase):
     @classmethod
     def setUpClass(self):
+        try_to_import_decord()
         self.video_file_url = create_sample_video()
         self.video_with_audio_file_url = (
             f"{EvaDB_ROOT_DIR}/data/sample_videos/touchdown.mp4"
         )
         self.frame_size = FRAME_SIZE[0] * FRAME_SIZE[1] * 3
         self.audio_frames = []
         for line in open(
```

### Comparing `evadb-0.2.9/test/server/__init__.py` & `evadb-0.3.0/test/readers/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/server/test_command_handler.py` & `evadb-0.3.0/test/server/test_command_handler.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/server/test_db_api.py` & `evadb-0.3.0/test/server/test_db_api.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/server/test_interpreter.py` & `evadb-0.3.0/test/server/test_interpreter.py`

 * *Files 9% similar despite different names*

```diff
@@ -11,14 +11,15 @@
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import asyncio
 import sys
 import unittest
+from test.markers import macos_skip_marker
 from test.util import find_free_port
 
 from mock import MagicMock, patch
 
 from evadb.server.interpreter import create_stdin_reader, start_cmd_client
 
 # Check for Python 3.8+ for IsolatedAsyncioTestCase support
@@ -57,14 +58,15 @@
 
         @patch("asyncio.open_connection")
         async def test_exception_in_start_cmd_client(self, mock_open):
             mock_open.side_effect = Exception("open")
 
             await start_cmd_client(MagicMock(), MagicMock())
 
+        @macos_skip_marker
         @patch("asyncio.events.AbstractEventLoop.connect_read_pipe")
         async def test_create_stdin_reader(self, mock_read_pipe):
             sys.stdin = MagicMock()
 
             try:
                 stdin_reader = await create_stdin_reader()
                 self.assertNotEqual(stdin_reader, None)
```

### Comparing `evadb-0.2.9/test/server/test_server.py` & `evadb-0.3.0/test/server/test_server.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/storage/__init__.py` & `evadb-0.3.0/test/server/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/storage/test_sqlite_storage_engine.py` & `evadb-0.3.0/test/storage/test_sqlite_storage_engine.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/storage/test_video_storage.py` & `evadb-0.3.0/test/storage/test_video_storage.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/test_eva_cmd_client.py` & `evadb-0.3.0/test/test_eva_cmd_client.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/test_eva_imports.py` & `evadb-0.3.0/test/test_eva_imports.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/test_eva_server.py` & `evadb-0.3.0/test/test_eva_server.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/udfs/__init__.py` & `evadb-0.3.0/test/storage/__init__.py`

 * *Files 11% similar despite different names*

```diff
@@ -8,8 +8,7 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-"""user defined functions operating on ndarrays"""
```

### Comparing `evadb-0.2.9/test/udfs/decorators/__init__.py` & `evadb-0.3.0/test/udfs/decorators/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/udfs/decorators/io_descriptors/__init__.py` & `evadb-0.3.0/test/udfs/decorators/io_descriptors/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/udfs/decorators/io_descriptors/test_descriptors.py` & `evadb-0.3.0/test/udfs/decorators/io_descriptors/test_descriptors.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/udfs/decorators/test_decorators.py` & `evadb-0.3.0/test/udfs/decorators/test_decorators.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/udfs/ndarray/__init__.py` & `evadb-0.3.0/test/udfs/ndarray/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/udfs/ndarray/test_annotate.py` & `evadb-0.3.0/test/udfs/ndarray/test_annotate.py`

 * *Files 13% similar despite different names*

```diff
@@ -13,28 +13,31 @@
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import unittest
 
 import numpy as np
 import pandas as pd
 from numpy import asarray
-from PIL import Image
 
 from evadb.configuration.constants import EvaDB_ROOT_DIR
 from evadb.udfs.ndarray.annotate import Annotate
+from evadb.utils.generic_utils import try_to_import_pillow
 
 
 class AnnotateTests(unittest.TestCase):
     def setUp(self):
+        try_to_import_pillow()
         self.annotate_instance = Annotate()
 
     def test_annotate_name_exists(self):
         assert hasattr(self.annotate_instance, "name")
 
     def test_should_annotate(self):
+        from PIL import Image
+
         img = Image.open(
             f"{EvaDB_ROOT_DIR}/test/data/uadetrac/small-data/MVI_20011/img00001.jpg"
         )
         arr = asarray(img)
         arr_copy = 0 + arr
         object_type = np.array(["object"])
         bbox = np.array([[50, 50, 70, 70]])
```

### Comparing `evadb-0.2.9/test/udfs/ndarray/test_array_count.py` & `evadb-0.3.0/test/udfs/ndarray/test_array_count.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/udfs/ndarray/test_crop.py` & `evadb-0.3.0/test/udfs/ndarray/test_crop.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/udfs/ndarray/test_flips.py` & `evadb-0.3.0/test/udfs/ndarray/test_flips.py`

 * *Files 13% similar despite different names*

```diff
@@ -13,43 +13,49 @@
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import unittest
 
 import numpy as np
 import pandas as pd
 from numpy import asarray
-from PIL import Image
 
 from evadb.configuration.constants import EvaDB_ROOT_DIR
 from evadb.udfs.ndarray.horizontal_flip import HorizontalFlip
 from evadb.udfs.ndarray.vertical_flip import VerticalFlip
+from evadb.utils.generic_utils import try_to_import_pillow
 
 
 class FlipTests(unittest.TestCase):
     def setUp(self):
         self.horizontal_flip_instance = HorizontalFlip()
         self.vertical_flip_instance = VerticalFlip()
 
     def test_flip_name_exists(self):
         assert hasattr(self.horizontal_flip_instance, "name")
         assert hasattr(self.vertical_flip_instance, "name")
 
     def test_should_flip_horizontally(self):
+        try_to_import_pillow()
+        from PIL import Image
+
         img = Image.open(
             f"{EvaDB_ROOT_DIR}/test/data/uadetrac/small-data/MVI_20011/img00001.jpg"
         )
         arr = asarray(img)
         df = pd.DataFrame([[arr]])
         flipped_arr = self.horizontal_flip_instance(df)[
             "horizontally_flipped_frame_array"
         ]
 
         self.assertEqual(np.sum(arr[:, 0] - np.flip(flipped_arr[0][:, -1], 1)), 0)
 
     def test_should_flip_vertically(self):
+        try_to_import_pillow()
+        from PIL import Image
+
         img = Image.open(
             f"{EvaDB_ROOT_DIR}/test/data/uadetrac/small-data/MVI_20011/img00001.jpg"
         )
         arr = asarray(img)
         df = pd.DataFrame([[arr]])
         flipped_arr = self.vertical_flip_instance(df)["vertically_flipped_frame_array"]
```

### Comparing `evadb-0.2.9/test/udfs/ndarray/test_gaussian_blur.py` & `evadb-0.3.0/test/udfs/ndarray/test_gaussian_blur.py`

 * *Files 9% similar despite different names*

```diff
@@ -12,31 +12,34 @@
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import unittest
 from pathlib import Path
 from test.util import file_remove
 
-import cv2
 import numpy as np
 import pandas as pd
 
 from evadb.configuration.constants import EvaDB_ROOT_DIR
 from evadb.udfs.ndarray.gaussian_blur import GaussianBlur
+from evadb.utils.generic_utils import try_to_import_cv2
 
 
 class GaussianBlurTests(unittest.TestCase):
     def setUp(self):
         self.gb_instance = GaussianBlur()
         self.tmp_file = f"{EvaDB_ROOT_DIR}/test/udfs/data/tmp.jpeg"
 
     def test_gb_name_exists(self):
         assert hasattr(self.gb_instance, "name")
 
     def test_should_blur_image(self):
+        try_to_import_cv2()
+        import cv2
+
         arr = cv2.imread(f"{EvaDB_ROOT_DIR}/test/udfs/data/dog.jpeg")
         df = pd.DataFrame([[arr]])
         modified_arr = self.gb_instance(df)["blurred_frame_array"]
         cv2.imwrite(
             self.tmp_file,
             cv2.cvtColor(modified_arr[0], cv2.COLOR_RGB2BGR),
         )
```

### Comparing `evadb-0.2.9/test/udfs/ndarray/test_open.py` & `evadb-0.3.0/test/udfs/ndarray/test_open.py`

 * *Files 11% similar despite different names*

```diff
@@ -17,21 +17,23 @@
 
 import numpy as np
 import pandas as pd
 import pytest
 from mock import patch
 
 from evadb.udfs.ndarray.open import Open
+from evadb.utils.generic_utils import try_to_import_cv2
 
 
 @pytest.mark.notparallel
 class OpenTests(unittest.TestCase):
     def setUp(self):
         self.open_instance = Open()
         self.image_file_path = create_sample_image()
+        try_to_import_cv2()
 
     def test_open_name_exists(self):
         assert hasattr(self.open_instance, "name")
 
     def test_should_open_image(self):
         df = self.open_instance(pd.DataFrame([self.image_file_path]))
         actual_img = df["data"].to_numpy()[0]
@@ -42,20 +44,22 @@
 
         self.assertEqual(actual_img.shape, expected_img.shape)
         self.assertEqual(np.sum(actual_img[0]), np.sum(expected_img[0]))
         self.assertEqual(np.sum(actual_img[1]), np.sum(expected_img[1]))
         self.assertEqual(np.sum(actual_img[2]), np.sum(expected_img[2]))
 
     def test_open_same_path_should_use_cache(self):
+        import cv2  # noqa: F401
+
         # un-cached open
-        with patch("evadb.udfs.ndarray.open.cv2") as mock_cv2:
+        with patch("cv2.imread") as mock_cv2_imread:
             self.open_instance(pd.DataFrame([self.image_file_path]))
-            mock_cv2.imread.assert_called_once_with(self.image_file_path)
+            mock_cv2_imread.assert_called_once_with(self.image_file_path)
 
         # cached open
-        with patch("evadb.udfs.ndarray.open.cv2") as mock_cv2:
+        with patch("cv2.imread") as mock_cv2_imread:
             self.open_instance(pd.DataFrame([self.image_file_path]))
-            mock_cv2.imread.assert_not_called()
+            mock_cv2_imread.assert_not_called()
 
     def test_open_path_should_raise_error(self):
         with self.assertRaises((AssertionError, FileNotFoundError)):
             self.open_instance(pd.DataFrame(["incorrect_path"]))
```

### Comparing `evadb-0.2.9/test/udfs/ndarray/test_to_grayscale.py` & `evadb-0.3.0/test/udfs/ndarray/test_to_grayscale.py`

 * *Files 12% similar despite different names*

```diff
@@ -12,30 +12,33 @@
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import unittest
 from pathlib import Path
 from test.util import file_remove
 
-import cv2
 import numpy as np
 import pandas as pd
 
 from evadb.configuration.constants import EvaDB_ROOT_DIR
 from evadb.udfs.ndarray.to_grayscale import ToGrayscale
+from evadb.utils.generic_utils import try_to_import_cv2
 
 
 class ToGrayscaleTests(unittest.TestCase):
     def setUp(self):
         self.to_grayscale_instance = ToGrayscale()
 
     def test_gray_scale_name_exists(self):
         assert hasattr(self.to_grayscale_instance, "name")
 
     def test_should_convert_to_grayscale(self):
+        try_to_import_cv2()
+        import cv2
+
         arr = cv2.imread(f"{EvaDB_ROOT_DIR}/test/udfs/data/dog.jpeg")
         df = pd.DataFrame([[arr]])
         modified_arr = self.to_grayscale_instance(df)["grayscale_frame_array"]
         cv2.imwrite(f"{EvaDB_ROOT_DIR}/test/udfs/data/tmp.jpeg", modified_arr[0])
         actual_array = cv2.imread(f"{EvaDB_ROOT_DIR}/test/udfs/data/tmp.jpeg")
         expected_arr = cv2.imread(f"{EvaDB_ROOT_DIR}/test/udfs/data/grayscale_dog.jpeg")
         self.assertEqual(np.sum(actual_array - expected_arr), 0)
```

### Comparing `evadb-0.2.9/test/udfs/test_abstract_udf.py` & `evadb-0.3.0/test/udfs/test_abstract_udf.py`

 * *Files 1% similar despite different names*

```diff
@@ -71,14 +71,16 @@
                                 continue
                             if issubclass(obj, Enum):
                                 continue
                             if "python" not in str(source_file):
                                 class_list.append([obj])
                         except OSError:
                             pass
+                        except TypeError:
+                            pass
 
             flat_class_list = [item for sublist in class_list for item in sublist]
             return set(flat_class_list)
 
         class_list = get_all_classes(evadb, 1)
 
         base_id = 0
```

### Comparing `evadb-0.2.9/test/udfs/test_emotion_detector.py` & `evadb-0.3.0/test/udfs/test_emotion_detector.py`

 * *Files 4% similar despite different names*

```diff
@@ -13,26 +13,29 @@
 # See the License for the specific language governing permissions and
 # limitations under the License.
 
 import unittest
 from pathlib import Path
 from test.util import EvaDB_TEST_DATA_DIR
 
-import cv2
 import pandas as pd
 
 from evadb.models.storage.batch import Batch
+from evadb.utils.generic_utils import try_to_import_cv2
 
 
 class EmotionDetector(unittest.TestCase):
     def __init__(self, *args, **kwargs):
         super().__init__(*args, **kwargs)
         self.base_path = Path(EvaDB_TEST_DATA_DIR) / "data" / "emotion_detector"
 
     def _load_image(self, path):
+        try_to_import_cv2()
+        import cv2
+
         assert path.exists(), f"File does not exist at the path {str(path)}"
         img = cv2.imread(str(path))
         return cv2.cvtColor(img, cv2.COLOR_BGR2RGB)
 
     @unittest.skip("disable test due to model downloading time")
     def test_should_return_correct_emotion(self):
         from evadb.udfs.emotion_detector import EmotionDetector
```

### Comparing `evadb-0.2.9/test/udfs/test_facenet_udf.py` & `evadb-0.3.0/test/udfs/test_facenet_udf.py`

 * *Files 6% similar despite different names*

```diff
@@ -12,31 +12,33 @@
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import unittest
 from pathlib import Path
 from test.markers import windows_skip_marker
 from test.util import EvaDB_TEST_DATA_DIR
-from unittest.mock import patch
 
-import cv2
 import pandas as pd
 
 from evadb.models.storage.batch import Batch
+from evadb.utils.generic_utils import try_to_import_cv2
 
 NUM_FRAMES = 10
 
 
 class FaceNet(unittest.TestCase):
     def __init__(self, *args, **kwargs):
         super().__init__(*args, **kwargs)
         self.base_path = Path(EvaDB_TEST_DATA_DIR) / "data" / "facenet"
 
     def _load_image(self, path):
         assert path.exists(), f"File does not exist at the path {str(path)}"
+        try_to_import_cv2()
+        import cv2
+
         img = cv2.imread(str(path))
         return cv2.cvtColor(img, cv2.COLOR_BGR2RGB)
 
     @windows_skip_marker
     def test_should_return_batches_equivalent_to_number_of_frames(self):
         from evadb.udfs.face_detector import FaceDetector
 
@@ -72,19 +74,7 @@
         }
         frame_batch = Batch(pd.DataFrame([frame_single_face, frame_single_face]))
 
         # test on GPU
         detector = FaceDetector().to_device(0)
         result = detector(frame_batch.project(["data"]).frames)
         self.assertEqual(6, len(result.iloc[0]["bboxes"]))
-
-    def test_mock_to_device(self):
-        device = 10
-        from evadb.udfs.face_detector import FaceDetector
-
-        with patch("evadb.udfs.face_detector.MTCNN") as mock_mtcnn:
-            with patch("evadb.udfs.face_detector.torch") as mock_torch:
-                mock_torch.device.return_value = "cuda:10"
-                detector = FaceDetector()
-                detector = detector.to_device(device)
-                mock_torch.device.assert_called_once()
-            mock_mtcnn.assert_called_with(device=f"cuda:{device}")
```

### Comparing `evadb-0.2.9/test/udfs/test_fastrcnn_object_detector.py` & `evadb-0.3.0/test/udfs/test_yolo_object_detector.py`

 * *Files 24% similar despite different names*

```diff
@@ -12,63 +12,76 @@
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import os
 import sys
 import unittest
 
-import cv2
 import mock
+import numpy as np
 import pandas as pd
 
-from evadb.models.storage.batch import Batch
+from evadb.utils.generic_utils import try_to_import_cv2, try_to_import_torch
 
 NUM_FRAMES = 10
 
 
-class FastRCNNObjectDetectorTest(unittest.TestCase):
+def numpy_to_yolo_format(numpy_image):
+    numpy_image = numpy_image.astype(np.float64)
+    numpy_image = numpy_image / 255
+    try_to_import_torch()
+    import torch
+
+    r = torch.tensor(numpy_image[:, :, 0])
+    g = torch.tensor(numpy_image[:, :, 1])
+    b = torch.tensor(numpy_image[:, :, 2])
+    rgb = torch.stack((r, g, b), dim=0)
+    rgb = rgb.unsqueeze(0)
+    return rgb
+
+
+class YoloTest(unittest.TestCase):
     def __init__(self, *args, **kwargs):
         super().__init__(*args, **kwargs)
         self.base_path = os.path.dirname(os.path.abspath(__file__))
 
     def _load_image(self, path):
+        try_to_import_cv2()
+        import cv2
+
         img = cv2.imread(path)
         return cv2.cvtColor(img, cv2.COLOR_BGR2RGB)
 
     def test_should_raise_import_error_with_missing_torch(self):
         with self.assertRaises(ImportError):
             with mock.patch.dict(sys.modules, {"torch": None}):
-                from evadb.udfs.fastrcnn_object_detector import (  # noqa: F401
-                    FastRCNNObjectDetector,
-                )
-
-                pass
-
-    def test_should_raise_import_error_with_missing_torchvision(self):
-        with self.assertRaises(ImportError):
-            with mock.patch.dict(sys.modules, {"torchvision": None}):
-                from evadb.udfs.fastrcnn_object_detector import (  # noqa: F401
-                    FastRCNNObjectDetector,
+                from evadb.udfs.decorators.yolo_object_detection_decorators import (  # noqa: F401
+                    Yolo,
                 )
 
                 pass
 
     @unittest.skip("disable test due to model downloading time")
     def test_should_return_batches_equivalent_to_number_of_frames(self):
-        from evadb.udfs.fastrcnn_object_detector import FastRCNNObjectDetector
+        from evadb.udfs.decorators.yolo_object_detection_decorators import Yolo
 
         frame_dog = {
             "id": 1,
             "data": self._load_image(os.path.join(self.base_path, "data", "dog.jpeg")),
         }
         frame_dog_cat = {
             "id": 2,
             "data": self._load_image(
                 os.path.join(self.base_path, "data", "dog_cat.jpg")
             ),
         }
-        frame_batch = Batch(pd.DataFrame([frame_dog, frame_dog_cat]))
-        detector = FastRCNNObjectDetector()
-        result = detector.classify(frame_batch)
+        test_df_dog = pd.DataFrame([frame_dog])
+        test_df_cat = pd.DataFrame([frame_dog_cat])
+        frame_dog = numpy_to_yolo_format(test_df_dog["data"].values[0])
+        frame_cat = numpy_to_yolo_format(test_df_cat["data"].values[0])
+        detector = Yolo()
+        result = []
+        result.append(detector.forward(frame_dog))
+        result.append(detector.forward(frame_cat))
 
-        self.assertEqual(["dog"], result[0].labels)
-        self.assertEqual(["cat", "dog"], result[1].labels)
+        self.assertEqual(["dog"], result[0]["labels"].tolist()[0])
+        self.assertEqual(["cat", "dog"], result[1]["labels"].tolist()[0])
```

### Comparing `evadb-0.2.9/test/util.py` & `evadb-0.3.0/test/util.py`

 * *Files 3% similar despite different names*

```diff
@@ -8,30 +8,26 @@
 #     http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
-import asyncio
 import gc
 import multiprocessing as mp
 import os
 import shutil
 import socket
 from contextlib import closing
 from itertools import repeat
 from multiprocessing import Pool
 from pathlib import Path
 
-import cv2
 import numpy as np
 import pandas as pd
-import psutil
-import ray
 from mock import MagicMock
 
 from evadb.binder.statement_binder import StatementBinder
 from evadb.binder.statement_binder_context import StatementBinderContext
 from evadb.catalog.catalog_type import NdArrayType
 from evadb.configuration.configuration_manager import ConfigurationManager
 from evadb.configuration.constants import EvaDB_DATABASE_DIR, EvaDB_INSTALLATION_DIR
@@ -44,15 +40,19 @@
 from evadb.parser.parser import Parser
 from evadb.plan_nodes.abstract_plan import AbstractPlan
 from evadb.server.command_handler import execute_query_fetch_all
 from evadb.udfs.abstract.abstract_udf import AbstractClassifierUDF
 from evadb.udfs.decorators import decorators
 from evadb.udfs.decorators.io_descriptors.data_types import NumpyArray, PandasDataframe
 from evadb.udfs.udf_bootstrap_queries import init_builtin_udfs
-from evadb.utils.generic_utils import remove_directory_contents
+from evadb.utils.generic_utils import (
+    is_ray_available,
+    remove_directory_contents,
+    try_to_import_cv2,
+)
 
 NUM_FRAMES = 10
 FRAME_SIZE = (32, 32)
 
 
 def suffix_pytest_xdist_worker_id_to_dir(path: str):
     try:
@@ -82,21 +82,24 @@
     return config.get_value("storage", "s3_download_dir")
 
 
 EvaDB_TEST_DATA_DIR = Path(EvaDB_INSTALLATION_DIR).parent
 
 
 def is_ray_stage_running():
+    import psutil
+
     return "ray::ray_stage" in (p.name() for p in psutil.process_iter())
 
 
 def shutdown_ray():
-    db_dir = suffix_pytest_xdist_worker_id_to_dir(EvaDB_DATABASE_DIR)
-    config = ConfigurationManager(Path(db_dir))
-    if config.get_value("experimental", "ray"):
+    is_ray_enabled = is_ray_available()
+    if is_ray_enabled:
+        import ray
+
         ray.shutdown()
 
 
 # Ref: https://stackoverflow.com/a/63851681
 def get_all_subclasses(cls):
     subclass_list = []
 
@@ -185,14 +188,29 @@
             MagicMock(),
             MagicMock(),
             MagicMock(),
             MagicMock(),
             MagicMock(),
             MagicMock(),
         )
+    elif number_of_args == 13:
+        return class_type(
+            MagicMock(),
+            MagicMock(),
+            MagicMock(),
+            MagicMock(),
+            MagicMock(),
+            MagicMock(),
+            MagicMock(),
+            MagicMock(),
+            MagicMock(),
+            MagicMock(),
+            MagicMock(),
+            MagicMock(),
+        )
     else:
         raise Exception("Too many args")
 
 
 def find_free_port():
     with closing(socket.socket(socket.AF_INET, socket.SOCK_STREAM)) as s:
         s.bind(("", 0))
@@ -207,15 +225,15 @@
     return l_plan
 
 
 def get_physical_query_plan(
     db, query: str, rule_manager=None, cost_model=None
 ) -> AbstractPlan:
     l_plan = get_logical_query_plan(db, query)
-    p_plan = asyncio.run(PlanGenerator(db, rule_manager, cost_model).build(l_plan))
+    p_plan = PlanGenerator(db, rule_manager, cost_model).build(l_plan)
     return p_plan
 
 
 def remove_udf_cache(db, query):
     plan = next(get_logical_query_plan(db, query).find_all(LogicalFilter))
     func_exprs = plan.predicate.find_all(FunctionExpression)
     for expr in func_exprs:
@@ -361,20 +379,26 @@
         os.remove(img_path)
     except FileNotFoundError:
         pass
 
     img = np.array(np.ones((3, 3, 3)), dtype=np.uint8)
     img[0] -= 1
     img[2] += 1
+    try_to_import_cv2()
+    import cv2
+
     cv2.imwrite(img_path, img)
     return img_path
 
 
 def create_random_image(i, path):
     img = np.random.random_sample([400, 400, 3]).astype(np.uint8)
+    try_to_import_cv2()
+    import cv2
+
     cv2.imwrite(os.path.join(path, f"img{i}.jpg"), img)
 
 
 def create_large_scale_image_dataset(num=1000000):
     img_dir = os.path.join(get_tmp_dir(), f"large_scale_image_dataset_{num}")
     Path(img_dir).mkdir(parents=True, exist_ok=True)
 
@@ -392,14 +416,17 @@
     try:
         os.remove(file_name)
     except FileNotFoundError:
         pass
 
     duration = 1
     fps = NUM_FRAMES
+    try_to_import_cv2()
+    import cv2
+
     out = cv2.VideoWriter(
         file_name, cv2.VideoWriter_fourcc("M", "J", "P", "G"), fps, (32, 32), False
     )
     for i in range(fps * duration):
         data = np.array(np.ones((FRAME_SIZE[1], FRAME_SIZE[0])) * i, dtype=np.uint8)
         out.write(data)
     out.release()
```

### Comparing `evadb-0.2.9/test/utils/__init__.py` & `evadb-0.3.0/test/utils/__init__.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/utils/test_generic_utils.py` & `evadb-0.3.0/test/utils/test_generic_utils.py`

 * *Files identical despite different names*

### Comparing `evadb-0.2.9/test/utils/test_timer.py` & `evadb-0.3.0/test/utils/test_timer.py`

 * *Files identical despite different names*


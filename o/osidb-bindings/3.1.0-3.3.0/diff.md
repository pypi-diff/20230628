# Comparing `tmp/osidb-bindings-3.1.0.tar.gz` & `tmp/osidb-bindings-3.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "osidb-bindings-3.1.0.tar", last modified: Wed Apr 26 21:08:58 2023, max compression
+gzip compressed data, was "osidb-bindings-3.3.0.tar", last modified: Wed Jun 28 11:35:12 2023, max compression
```

## Comparing `osidb-bindings-3.1.0.tar` & `osidb-bindings-3.3.0.tar`

### file list

```diff
@@ -1,240 +1,272 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:58.473001 osidb-bindings-3.1.0/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1863 2023-04-26 21:08:58.473001 osidb-bindings-3.1.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1182 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:58.445001 osidb-bindings-3.1.0/osidb_bindings/
--rw-r--r--   0 runner    (1001) docker     (123)       71 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:58.445001 osidb-bindings-3.1.0/osidb_bindings/bindings/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:58.445001 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/
--rw-r--r--   0 runner    (1001) docker     (123)       97 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:58.445001 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/
--rw-r--r--   0 runner    (1001) docker     (123)       47 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:58.445001 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/auth/
--rw-r--r--   0 runner    (1001) docker     (123)      149 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/auth/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2756 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/auth/auth_token_create.py
--rw-r--r--   0 runner    (1001) docker     (123)     2766 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/auth/auth_token_refresh_create.py
--rw-r--r--   0 runner    (1001) docker     (123)     1874 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/auth/auth_token_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     2761 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/auth/auth_token_verify_create.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:58.445001 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/collectors/
--rw-r--r--   0 runner    (1001) docker     (123)      127 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/collectors/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2021 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/collectors/collectors_api_v1_status_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     1929 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/collectors/collectors_healthy_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     1875 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/collectors/collectors_retrieve.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:58.449001 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/
--rw-r--r--   0 runner    (1001) docker     (123)      498 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_collect_update.py
--rw-r--r--   0 runner    (1001) docker     (123)     2322 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_cve_map_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     2534 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_epss_list.py
--rw-r--r--   0 runner    (1001) docker     (123)     2538 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_flaw_data_list.py
--rw-r--r--   0 runner    (1001) docker     (123)     2604 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_data_list.py
--rw-r--r--   0 runner    (1001) docker     (123)     2812 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_date_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     2353 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_explanations_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     2615 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_pending_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     2075 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_status_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     2664 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_supported_products_list.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:58.449001 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/
--rw-r--r--   0 runner    (1001) docker     (123)      677 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2694 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_create.py
--rw-r--r--   0 runner    (1001) docker     (123)     1997 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_destroy.py
--rw-r--r--   0 runner    (1001) docker     (123)    61427 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_list.py
--rw-r--r--   0 runner    (1001) docker     (123)     3957 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     2753 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_update.py
--rw-r--r--   0 runner    (1001) docker     (123)     2652 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_create.py
--rw-r--r--   0 runner    (1001) docker     (123)    68872 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_list.py
--rw-r--r--   0 runner    (1001) docker     (123)     5035 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     2691 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_update.py
--rw-r--r--   0 runner    (1001) docker     (123)     1949 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_manifest_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     3403 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_schema_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     1899 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_status_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)    68643 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_trackers_list.py
--rw-r--r--   0 runner    (1001) docker     (123)     3996 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_trackers_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     1902 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_healthy_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     1890 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_whoami_retrieve.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:58.449001 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osim/
--rw-r--r--   0 runner    (1001) docker     (123)      211 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osim/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2368 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osim/osim_api_v1_workflows_adjust_create.py
--rw-r--r--   0 runner    (1001) docker     (123)     1957 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osim/osim_api_v1_workflows_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     2684 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osim/osim_api_v1_workflows_retrieve_2.py
--rw-r--r--   0 runner    (1001) docker     (123)     1866 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osim/osim_healthy_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     1811 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osim/osim_retrieve.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:58.453001 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/
--rw-r--r--   0 runner    (1001) docker     (123)      507 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2703 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_create.py
--rw-r--r--   0 runner    (1001) docker     (123)     2329 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     2614 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_update.py
--rw-r--r--   0 runner    (1001) docker     (123)     2688 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_comment_create.py
--rw-r--r--   0 runner    (1001) docker     (123)     2850 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_comment_update.py
--rw-r--r--   0 runner    (1001) docker     (123)     2374 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_create.py
--rw-r--r--   0 runner    (1001) docker     (123)     2394 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     2373 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_update.py
--rw-r--r--   0 runner    (1001) docker     (123)     2315 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     3043 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_status_update.py
--rw-r--r--   0 runner    (1001) docker     (123)     1902 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_healthy_retrieve.py
--rw-r--r--   0 runner    (1001) docker     (123)     1952 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/client.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:58.469001 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/
--rw-r--r--   0 runner    (1001) docker     (123)    11852 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18836 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/affect.py
--rw-r--r--   0 runner    (1001) docker     (123)     3990 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/affect_meta_attr.py
--rw-r--r--   0 runner    (1001) docker     (123)    18101 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/affect_post.py
--rw-r--r--   0 runner    (1001) docker     (123)     4013 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/affect_post_meta_attr.py
--rw-r--r--   0 runner    (1001) docker     (123)     7027 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/affect_report_data.py
--rw-r--r--   0 runner    (1001) docker     (123)      195 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/affectedness_enum.py
--rw-r--r--   0 runner    (1001) docker     (123)     3482 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/auth_token_create_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     3048 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/auth_token_refresh_create_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     3064 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/auth_token_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     2807 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/auth_token_verify_create_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)      131 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/blank_enum.py
--rw-r--r--   0 runner    (1001) docker     (123)     4254 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     6346 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item.py
--rw-r--r--   0 runner    (1001) docker     (123)      233 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item_data.py
--rw-r--r--   0 runner    (1001) docker     (123)     1509 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item_error.py
--rw-r--r--   0 runner    (1001) docker     (123)      256 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item_state.py
--rw-r--r--   0 runner    (1001) docker     (123)     2621 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/collectors_healthy_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     2941 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/collectors_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     4436 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/comment.py
--rw-r--r--   0 runner    (1001) docker     (123)     1284 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/comment_meta_attr.py
--rw-r--r--   0 runner    (1001) docker     (123)      146 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/comment_type_enum.py
--rw-r--r--   0 runner    (1001) docker     (123)     2746 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/cv_ev_5_package_versions.py
--rw-r--r--   0 runner    (1001) docker     (123)     2044 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/cv_ev_5_versions.py
--rw-r--r--   0 runner    (1001) docker     (123)     1585 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/epss.py
--rw-r--r--   0 runner    (1001) docker     (123)     2913 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/erratum.py
--rw-r--r--   0 runner    (1001) docker     (123)     4177 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploit_only_report_data.py
--rw-r--r--   0 runner    (1001) docker     (123)      214 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploit_only_report_data_source_enum.py
--rw-r--r--   0 runner    (1001) docker     (123)     2923 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_collect_update_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     3663 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_cve_map_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     1397 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_cve_map_retrieve_response_200_cves.py
--rw-r--r--   0 runner    (1001) docker     (123)     4452 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_epss_list_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     4537 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_flaw_data_list_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     4590 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_data_list_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     8420 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     1517 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200_action_required_item.py
--rw-r--r--   0 runner    (1001) docker     (123)     1487 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200_no_action_item.py
--rw-r--r--   0 runner    (1001) docker     (123)     1502 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200_not_relevant_item.py
--rw-r--r--   0 runner    (1001) docker     (123)     4771 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_explanations_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     1598 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_explanations_retrieve_response_200_explanations_item.py
--rw-r--r--   0 runner    (1001) docker     (123)     4939 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_pending_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     1562 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_pending_retrieve_response_200_pending_actions_item.py
--rw-r--r--   0 runner    (1001) docker     (123)     3686 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_status_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     4599 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_supported_products_list_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)    29673 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw.py
--rw-r--r--   0 runner    (1001) docker     (123)     2196 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw_classification.py
--rw-r--r--   0 runner    (1001) docker     (123)      246 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw_classification_state.py
--rw-r--r--   0 runner    (1001) docker     (123)     9426 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw_meta_attr.py
--rw-r--r--   0 runner    (1001) docker     (123)    28963 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw_post.py
--rw-r--r--   0 runner    (1001) docker     (123)     2248 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw_post_classification.py
--rw-r--r--   0 runner    (1001) docker     (123)      250 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw_post_classification_state.py
--rw-r--r--   0 runner    (1001) docker     (123)     9449 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw_post_meta_attr.py
--rw-r--r--   0 runner    (1001) docker     (123)     3182 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw_report_data.py
--rw-r--r--   0 runner    (1001) docker     (123)      211 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/impact_enum.py
--rw-r--r--   0 runner    (1001) docker     (123)     3199 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/jira_comment.py
--rw-r--r--   0 runner    (1001) docker     (123)     2348 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/jira_issue.py
--rw-r--r--   0 runner    (1001) docker     (123)     3299 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/jira_issue_fields.py
--rw-r--r--   0 runner    (1001) docker     (123)     2595 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/jira_issue_query_result.py
--rw-r--r--   0 runner    (1001) docker     (123)     1666 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/jira_issue_type.py
--rw-r--r--   0 runner    (1001) docker     (123)     2169 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/jira_user.py
--rw-r--r--   0 runner    (1001) docker     (123)      193 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/maturity_preliminary_enum.py
--rw-r--r--   0 runner    (1001) docker     (123)     4001 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/meta.py
--rw-r--r--   0 runner    (1001) docker     (123)     1269 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/meta_meta_attr.py
--rw-r--r--   0 runner    (1001) docker     (123)      489 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/meta_type_enum.py
--rw-r--r--   0 runner    (1001) docker     (123)    14328 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_create_response_201.py
--rw-r--r--   0 runner    (1001) docker     (123)     2622 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_destroy_response_204.py
--rw-r--r--   0 runner    (1001) docker     (123)      229 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_affectedness.py
--rw-r--r--   0 runner    (1001) docker     (123)      249 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_flaw_impact.py
--rw-r--r--   0 runner    (1001) docker     (123)     2113 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_flaw_source.py
--rw-r--r--   0 runner    (1001) docker     (123)      196 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_flaw_type.py
--rw-r--r--   0 runner    (1001) docker     (123)      245 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_impact.py
--rw-r--r--   0 runner    (1001) docker     (123)     2808 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_order_item.py
--rw-r--r--   0 runner    (1001) docker     (123)      289 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_resolution.py
--rw-r--r--   0 runner    (1001) docker     (123)     4464 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)      182 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_trackers_type.py
--rw-r--r--   0 runner    (1001) docker     (123)      154 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_type.py
--rw-r--r--   0 runner    (1001) docker     (123)    14338 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)    14328 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_update_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)    20622 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_create_response_201.py
--rw-r--r--   0 runner    (1001) docker     (123)      234 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_affectedness.py
--rw-r--r--   0 runner    (1001) docker     (123)      250 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_impact.py
--rw-r--r--   0 runner    (1001) docker     (123)      294 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_resolution.py
--rw-r--r--   0 runner    (1001) docker     (123)      187 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_trackers_type.py
--rw-r--r--   0 runner    (1001) docker     (123)      159 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_type.py
--rw-r--r--   0 runner    (1001) docker     (123)      243 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_impact.py
--rw-r--r--   0 runner    (1001) docker     (123)     3046 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_order_item.py
--rw-r--r--   0 runner    (1001) docker     (123)     4442 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     2107 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_source.py
--rw-r--r--   0 runner    (1001) docker     (123)      190 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_type.py
--rw-r--r--   0 runner    (1001) docker     (123)    20632 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)    20622 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_update_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     2632 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_manifest_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)      171 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_schema_retrieve_format.py
--rw-r--r--   0 runner    (1001) docker     (123)     1571 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_schema_retrieve_lang.py
--rw-r--r--   0 runner    (1001) docker     (123)     2622 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_schema_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     4502 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_status_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     1726 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_status_retrieve_response_200_osidb_data.py
--rw-r--r--   0 runner    (1001) docker     (123)     1446 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_status_retrieve_response_200_osidb_service.py
--rw-r--r--   0 runner    (1001) docker     (123)      237 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_affectedness.py
--rw-r--r--   0 runner    (1001) docker     (123)      257 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_flaw_impact.py
--rw-r--r--   0 runner    (1001) docker     (123)     2121 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_flaw_source.py
--rw-r--r--   0 runner    (1001) docker     (123)      204 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_flaw_type.py
--rw-r--r--   0 runner    (1001) docker     (123)      253 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_impact.py
--rw-r--r--   0 runner    (1001) docker     (123)      297 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_resolution.py
--rw-r--r--   0 runner    (1001) docker     (123)      162 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_type.py
--rw-r--r--   0 runner    (1001) docker     (123)     3383 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_order_item.py
--rw-r--r--   0 runner    (1001) docker     (123)     4475 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)      175 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_type.py
--rw-r--r--   0 runner    (1001) docker     (123)     7353 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     2596 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_healthy_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     4220 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_whoami_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     1984 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_whoami_retrieve_response_200_profile.py
--rw-r--r--   0 runner    (1001) docker     (123)     2655 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osim_api_v1_workflows_adjust_create_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     2640 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osim_api_v1_workflows_retrieve_2_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     2632 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osim_api_v1_workflows_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     2591 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osim_healthy_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     2553 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osim_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     3159 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/paginated_affect_list.py
--rw-r--r--   0 runner    (1001) docker     (123)     3137 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/paginated_epss_list.py
--rw-r--r--   0 runner    (1001) docker     (123)     3336 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/paginated_exploit_only_report_data_list.py
--rw-r--r--   0 runner    (1001) docker     (123)     3137 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/paginated_flaw_list.py
--rw-r--r--   0 runner    (1001) docker     (123)     3255 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/paginated_flaw_report_data_list.py
--rw-r--r--   0 runner    (1001) docker     (123)     3284 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/paginated_supported_products_list.py
--rw-r--r--   0 runner    (1001) docker     (123)     3170 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/paginated_tracker_list.py
--rw-r--r--   0 runner    (1001) docker     (123)      255 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/resolution_enum.py
--rw-r--r--   0 runner    (1001) docker     (123)     2078 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/source_666_enum.py
--rw-r--r--   0 runner    (1001) docker     (123)      195 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/status_enum.py
--rw-r--r--   0 runner    (1001) docker     (123)     1468 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/supported_products.py
--rw-r--r--   0 runner    (1001) docker     (123)     3723 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_group_create_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     3919 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_group_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     2617 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_group_update_response_204.py
--rw-r--r--   0 runner    (1001) docker     (123)     4544 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_comment_create_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     4544 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_comment_update_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     2635 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_create_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     3751 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     2635 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_update_response_204.py
--rw-r--r--   0 runner    (1001) docker     (123)     3728 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     2645 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_status_update_response_204.py
--rw-r--r--   0 runner    (1001) docker     (123)      239 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_status_update_status.py
--rw-r--r--   0 runner    (1001) docker     (123)     2606 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_healthy_retrieve_response_200.py
--rw-r--r--   0 runner    (1001) docker     (123)     3394 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/token_obtain_pair.py
--rw-r--r--   0 runner    (1001) docker     (123)     2438 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/token_refresh.py
--rw-r--r--   0 runner    (1001) docker     (123)     1940 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/token_verify.py
--rw-r--r--   0 runner    (1001) docker     (123)     6028 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/tracker.py
--rw-r--r--   0 runner    (1001) docker     (123)     3424 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/tracker_meta_attr.py
--rw-r--r--   0 runner    (1001) docker     (123)     2625 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/tracker_report_data.py
--rw-r--r--   0 runner    (1001) docker     (123)      160 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/type_0d0_enum.py
--rw-r--r--   0 runner    (1001) docker     (123)      140 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/type_5b2_enum.py
--rw-r--r--   0 runner    (1001) docker     (123)      178 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/type_824_enum.py
--rw-r--r--   0 runner    (1001) docker     (123)     1108 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/types.py
--rw-r--r--   0 runner    (1001) docker     (123)      471 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/constants.py
--rw-r--r--   0 runner    (1001) docker     (123)    12412 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/session.py
--rw-r--r--   0 runner    (1001) docker     (123)      483 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/osidb_bindings/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:58.445001 osidb-bindings-3.1.0/osidb_bindings.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1863 2023-04-26 21:08:58.000000 osidb-bindings-3.1.0/osidb_bindings.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17176 2023-04-26 21:08:58.000000 osidb-bindings-3.1.0/osidb_bindings.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-04-26 21:08:58.000000 osidb-bindings-3.1.0/osidb_bindings.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       47 2023-04-26 21:08:58.000000 osidb-bindings-3.1.0/osidb_bindings.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       21 2023-04-26 21:08:58.000000 osidb-bindings-3.1.0/osidb_bindings.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-04-26 21:08:58.473001 osidb-bindings-3.1.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1029 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:58.473001 osidb-bindings-3.1.0/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/tests/conftest.py
--rw-r--r--   0 runner    (1001) docker     (123)      203 2023-04-26 21:08:32.000000 osidb-bindings-3.1.0/tests/test_core.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:35:12.573502 osidb-bindings-3.3.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     1863 2023-06-28 11:35:12.573502 osidb-bindings-3.3.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1182 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:35:12.533498 osidb-bindings-3.3.0/osidb_bindings/
+-rw-r--r--   0 runner    (1001) docker     (123)       71 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:35:12.533498 osidb-bindings-3.3.0/osidb_bindings/bindings/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:35:12.533498 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/
+-rw-r--r--   0 runner    (1001) docker     (123)       97 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:35:12.537499 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/
+-rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:35:12.537499 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/auth/
+-rw-r--r--   0 runner    (1001) docker     (123)      149 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/auth/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2756 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/auth/auth_token_create.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2766 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/auth/auth_token_refresh_create.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1874 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/auth/auth_token_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2761 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/auth/auth_token_verify_create.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:35:12.537499 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/collectors/
+-rw-r--r--   0 runner    (1001) docker     (123)      127 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/collectors/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2021 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/collectors/collectors_api_v1_status_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1929 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/collectors/collectors_healthy_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1875 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/collectors/collectors_retrieve.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:35:12.537499 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/
+-rw-r--r--   0 runner    (1001) docker     (123)      498 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_collect_update.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2322 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_cve_map_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2534 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_epss_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2538 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_flaw_data_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2604 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_data_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2812 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_date_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2353 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_explanations_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2615 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_pending_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2075 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_status_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2664 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_supported_products_list.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:35:12.541499 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/
+-rw-r--r--   0 runner    (1001) docker     (123)     1088 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2694 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_create.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1997 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_destroy.py
+-rw-r--r--   0 runner    (1001) docker     (123)    61427 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3957 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2753 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_update.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3163 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_comments_create.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5436 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_comments_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4440 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_comments_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2652 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_create.py
+-rw-r--r--   0 runner    (1001) docker     (123)    69414 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3022 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_references_create.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2220 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_references_destroy.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4501 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_references_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4180 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_references_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3061 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_references_update.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5035 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2691 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_update.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1949 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_manifest_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3403 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_schema_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1899 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_status_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)    68643 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_trackers_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3996 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_trackers_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1902 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_healthy_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1890 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_whoami_retrieve.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:35:12.541499 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osim/
+-rw-r--r--   0 runner    (1001) docker     (123)      211 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osim/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2368 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osim/osim_api_v1_workflows_adjust_create.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1957 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osim/osim_api_v1_workflows_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2684 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osim/osim_api_v1_workflows_retrieve_2.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1866 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osim/osim_healthy_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1811 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osim/osim_retrieve.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:35:12.545500 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/
+-rw-r--r--   0 runner    (1001) docker     (123)      666 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2703 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_create.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2329 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2614 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_update.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2373 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_assignee_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2659 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_assignee_update.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2688 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_comment_create.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2850 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_comment_update.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2374 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_create.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2394 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2373 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_update.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2315 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4494 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_status_update.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2296 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_unassigned_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1902 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_healthy_retrieve.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1952 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/client.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:35:12.569502 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/
+-rw-r--r--   0 runner    (1001) docker     (123)    13727 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18827 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/affect.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3990 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/affect_meta_attr.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18092 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/affect_post.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4013 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/affect_post_meta_attr.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7027 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/affect_report_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)      139 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/affect_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)      195 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/affectedness_enum.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3482 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/auth_token_create_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3048 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/auth_token_refresh_create_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3064 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/auth_token_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2807 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/auth_token_verify_create_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)      131 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/blank_enum.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4254 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6346 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)      233 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1509 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item_error.py
+-rw-r--r--   0 runner    (1001) docker     (123)      256 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item_state.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2621 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/collectors_healthy_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2941 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/collectors_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4484 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/comment.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1284 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/comment_meta_attr.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2746 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/cv_ev_5_package_versions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2044 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/cv_ev_5_versions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1585 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/epss.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2913 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/erratum.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4177 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploit_only_report_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)      214 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploit_only_report_data_source_enum.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2923 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_collect_update_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3663 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_cve_map_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1397 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_cve_map_retrieve_response_200_cves.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4452 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_epss_list_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4537 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_flaw_data_list_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4590 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_data_list_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8420 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1517 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200_action_required_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1487 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200_no_action_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1502 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200_not_relevant_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4771 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_explanations_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1598 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_explanations_retrieve_response_200_explanations_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4939 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_pending_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1562 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_pending_retrieve_response_200_pending_actions_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3686 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_status_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4599 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_supported_products_list_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31519 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2196 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_classification.py
+-rw-r--r--   0 runner    (1001) docker     (123)      246 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_classification_state.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4460 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_comment.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5479 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_comment_post.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1330 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_comment_post_meta_attr.py
+-rw-r--r--   0 runner    (1001) docker     (123)      146 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_comment_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9426 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_meta_attr.py
+-rw-r--r--   0 runner    (1001) docker     (123)      489 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_meta_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30809 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_post.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2248 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_post_classification.py
+-rw-r--r--   0 runner    (1001) docker     (123)      250 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_post_classification_state.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9449 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_post_meta_attr.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6094 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_reference.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4985 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_reference_post.py
+-rw-r--r--   0 runner    (1001) docker     (123)      172 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_reference_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3182 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_report_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)      175 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)      211 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/impact_enum.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3199 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/jira_comment.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2348 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/jira_issue.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4313 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/jira_issue_fields.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2595 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/jira_issue_query_result.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1666 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/jira_issue_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2169 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/jira_user.py
+-rw-r--r--   0 runner    (1001) docker     (123)      193 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/maturity_preliminary_enum.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4001 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/meta.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1269 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/meta_meta_attr.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14320 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_create_response_201.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2622 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_destroy_response_204.py
+-rw-r--r--   0 runner    (1001) docker     (123)      229 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_affectedness.py
+-rw-r--r--   0 runner    (1001) docker     (123)      249 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_flaw_impact.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2113 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_flaw_source.py
+-rw-r--r--   0 runner    (1001) docker     (123)      196 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_flaw_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)      245 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_impact.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2808 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_order_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)      289 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_resolution.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4464 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)      182 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_trackers_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)      154 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14330 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14320 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_update_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5742 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_comments_create_response_201.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4528 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_comments_list_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5752 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_comments_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21849 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_create_response_201.py
+-rw-r--r--   0 runner    (1001) docker     (123)      234 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_affectedness.py
+-rw-r--r--   0 runner    (1001) docker     (123)      250 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_impact.py
+-rw-r--r--   0 runner    (1001) docker     (123)      294 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_resolution.py
+-rw-r--r--   0 runner    (1001) docker     (123)      187 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_trackers_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)      159 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)      243 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_impact.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3192 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_order_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4442 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2107 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_source.py
+-rw-r--r--   0 runner    (1001) docker     (123)      190 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5469 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_references_create_response_201.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2665 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_references_destroy_response_204.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4550 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_references_list_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5479 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_references_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5469 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_references_update_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21859 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21849 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_update_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2632 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_manifest_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)      171 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_schema_retrieve_format.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1571 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_schema_retrieve_lang.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2622 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_schema_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4502 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_status_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1726 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_status_retrieve_response_200_osidb_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1446 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_status_retrieve_response_200_osidb_service.py
+-rw-r--r--   0 runner    (1001) docker     (123)      237 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_affectedness.py
+-rw-r--r--   0 runner    (1001) docker     (123)      257 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_flaw_impact.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2121 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_flaw_source.py
+-rw-r--r--   0 runner    (1001) docker     (123)      204 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_flaw_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)      253 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_impact.py
+-rw-r--r--   0 runner    (1001) docker     (123)      297 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_resolution.py
+-rw-r--r--   0 runner    (1001) docker     (123)      162 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3383 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_order_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4475 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)      175 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7352 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2596 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_healthy_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4220 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_whoami_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1984 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_whoami_retrieve_response_200_profile.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2655 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osim_api_v1_workflows_adjust_create_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2640 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osim_api_v1_workflows_retrieve_2_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2632 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osim_api_v1_workflows_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2591 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osim_healthy_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2553 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osim_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3159 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_affect_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3137 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_epss_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3336 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_exploit_only_report_data_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3218 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_flaw_comment_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3137 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_flaw_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3240 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_flaw_reference_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3255 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_flaw_report_data_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3284 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_supported_products_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3170 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_tracker_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)      255 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/resolution_enum.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2078 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/source_666_enum.py
+-rw-r--r--   0 runner    (1001) docker     (123)      195 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/status_enum.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1468 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/supported_products.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3723 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_group_create_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3919 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_group_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2617 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_group_update_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3957 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_assignee_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2655 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_assignee_update_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4544 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_comment_create_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4544 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_comment_update_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2635 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_create_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3751 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2635 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_update_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3728 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)      239 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_status_update_reason.py
+-rw-r--r--   0 runner    (1001) docker     (123)      435 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_status_update_resolution.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2645 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_status_update_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)      239 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_status_update_status.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3967 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_unassigned_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2606 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_healthy_retrieve_response_200.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3394 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/token_obtain_pair.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2438 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/token_refresh.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1940 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/token_verify.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6027 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/tracker.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3424 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/tracker_meta_attr.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2624 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/tracker_report_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)      160 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/tracker_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1108 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/types.py
+-rw-r--r--   0 runner    (1001) docker     (123)      396 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13872 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/session.py
+-rw-r--r--   0 runner    (1001) docker     (123)      483 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/osidb_bindings/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:35:12.533498 osidb-bindings-3.3.0/osidb_bindings.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1863 2023-06-28 11:35:12.000000 osidb-bindings-3.3.0/osidb_bindings.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19955 2023-06-28 11:35:12.000000 osidb-bindings-3.3.0/osidb_bindings.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:35:12.000000 osidb-bindings-3.3.0/osidb_bindings.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-28 11:35:12.000000 osidb-bindings-3.3.0/osidb_bindings.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-28 11:35:12.000000 osidb-bindings-3.3.0/osidb_bindings.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 11:35:12.573502 osidb-bindings-3.3.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1029 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:35:12.573502 osidb-bindings-3.3.0/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/tests/conftest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      203 2023-06-28 11:34:53.000000 osidb-bindings-3.3.0/tests/test_core.py
```

### Comparing `osidb-bindings-3.1.0/LICENSE` & `osidb-bindings-3.3.0/LICENSE`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/PKG-INFO` & `osidb-bindings-3.3.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: osidb-bindings
-Version: 3.1.0
+Version: 3.3.0
 Summary: Python bindings for accessing OSIDB API
 Home-page: https://github.com/RedHatProductSecurity/osidb-bindings
 Author: Jakub Frejlach, Red Hat Product Security
 Author-email: jfrejlac@redhat.com
 Project-URL: Changelog, https://github.com/RedHatProductSecurity/osidb-bindings/blob/master/CHANGELOG.md
 Project-URL: Documentation, https://github.com/RedHatProductSecurity/osidb-bindings/blob/master/TUTORIAL.md
 Project-URL: Source, https://github.com/RedHatProductSecurity/osidb-bindings
```

### Comparing `osidb-bindings-3.1.0/README.md` & `osidb-bindings-3.3.0/README.md`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/auth/auth_token_create.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/auth/auth_token_create.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/auth/auth_token_refresh_create.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/auth/auth_token_refresh_create.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/auth/auth_token_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/auth/auth_token_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/auth/auth_token_verify_create.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/auth/auth_token_verify_create.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/collectors/collectors_api_v1_status_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/collectors/collectors_api_v1_status_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/collectors/collectors_healthy_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/collectors/collectors_healthy_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/collectors/collectors_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/collectors/collectors_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_collect_update.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_collect_update.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_cve_map_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_cve_map_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_epss_list.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_epss_list.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_flaw_data_list.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_flaw_data_list.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_data_list.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_data_list.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_date_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_date_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_explanations_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_explanations_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_pending_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_report_pending_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_status_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_status_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_supported_products_list.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_supported_products_list.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/__init__.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/__init__.py`

 * *Files 27% similar despite different names*

```diff
@@ -1,14 +1,22 @@
 from .osidb_api_v1_affects_create import *
 from .osidb_api_v1_affects_destroy import *
 from .osidb_api_v1_affects_list import *
 from .osidb_api_v1_affects_retrieve import *
 from .osidb_api_v1_affects_update import *
+from .osidb_api_v1_flaws_comments_create import *
+from .osidb_api_v1_flaws_comments_list import *
+from .osidb_api_v1_flaws_comments_retrieve import *
 from .osidb_api_v1_flaws_create import *
 from .osidb_api_v1_flaws_list import *
+from .osidb_api_v1_flaws_references_create import *
+from .osidb_api_v1_flaws_references_destroy import *
+from .osidb_api_v1_flaws_references_list import *
+from .osidb_api_v1_flaws_references_retrieve import *
+from .osidb_api_v1_flaws_references_update import *
 from .osidb_api_v1_flaws_retrieve import *
 from .osidb_api_v1_flaws_update import *
 from .osidb_api_v1_manifest_retrieve import *
 from .osidb_api_v1_schema_retrieve import *
 from .osidb_api_v1_status_retrieve import *
 from .osidb_api_v1_trackers_list import *
 from .osidb_api_v1_trackers_retrieve import *
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_create.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_create.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_destroy.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_destroy.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_list.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_list.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_update.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_update.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_create.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_create.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_list.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_list.py`

 * *Files 0% similar despite different names*

```diff
@@ -60,14 +60,15 @@
     "affects__trackers__created_dt__date__gte": datetime.date,
     "affects__trackers__created_dt__date__lte": datetime.date,
     "affects__trackers__created_dt__gt": datetime.datetime,
     "affects__trackers__created_dt__gte": datetime.datetime,
     "affects__trackers__created_dt__lt": datetime.datetime,
     "affects__trackers__created_dt__lte": datetime.datetime,
     "affects__trackers__embargoed": bool,
+    "affects__trackers__errata__advisory_name": str,
     "affects__trackers__external_system_id": str,
     "affects__trackers__ps_update_stream": str,
     "affects__trackers__resolution": str,
     "affects__trackers__status": str,
     "affects__trackers__type": OsidbApiV1FlawsListAffectsTrackersType,
     "affects__trackers__updated_dt": datetime.datetime,
     "affects__trackers__updated_dt__date": datetime.date,
@@ -193,14 +194,15 @@
     affects_trackers_created_dt_date_gte: Union[Unset, None, datetime.date] = UNSET,
     affects_trackers_created_dt_date_lte: Union[Unset, None, datetime.date] = UNSET,
     affects_trackers_created_dt_gt: Union[Unset, None, datetime.datetime] = UNSET,
     affects_trackers_created_dt_gte: Union[Unset, None, datetime.datetime] = UNSET,
     affects_trackers_created_dt_lt: Union[Unset, None, datetime.datetime] = UNSET,
     affects_trackers_created_dt_lte: Union[Unset, None, datetime.datetime] = UNSET,
     affects_trackers_embargoed: Union[Unset, None, bool] = UNSET,
+    affects_trackers_errata_advisory_name: Union[Unset, None, str] = UNSET,
     affects_trackers_external_system_id: Union[Unset, None, str] = UNSET,
     affects_trackers_ps_update_stream: Union[Unset, None, str] = UNSET,
     affects_trackers_resolution: Union[Unset, None, str] = UNSET,
     affects_trackers_status: Union[Unset, None, str] = UNSET,
     affects_trackers_type: Union[
         Unset, None, OsidbApiV1FlawsListAffectsTrackersType
     ] = UNSET,
@@ -794,14 +796,15 @@
         "affects__trackers__created_dt__date__gte": json_affects_trackers_created_dt_date_gte,
         "affects__trackers__created_dt__date__lte": json_affects_trackers_created_dt_date_lte,
         "affects__trackers__created_dt__gt": json_affects_trackers_created_dt_gt,
         "affects__trackers__created_dt__gte": json_affects_trackers_created_dt_gte,
         "affects__trackers__created_dt__lt": json_affects_trackers_created_dt_lt,
         "affects__trackers__created_dt__lte": json_affects_trackers_created_dt_lte,
         "affects__trackers__embargoed": affects_trackers_embargoed,
+        "affects__trackers__errata__advisory_name": affects_trackers_errata_advisory_name,
         "affects__trackers__external_system_id": affects_trackers_external_system_id,
         "affects__trackers__ps_update_stream": affects_trackers_ps_update_stream,
         "affects__trackers__resolution": affects_trackers_resolution,
         "affects__trackers__status": affects_trackers_status,
         "affects__trackers__type": json_affects_trackers_type,
         "affects__trackers__updated_dt": json_affects_trackers_updated_dt,
         "affects__trackers__updated_dt__date": json_affects_trackers_updated_dt_date,
@@ -960,14 +963,15 @@
     affects_trackers_created_dt_date_gte: Union[Unset, None, datetime.date] = UNSET,
     affects_trackers_created_dt_date_lte: Union[Unset, None, datetime.date] = UNSET,
     affects_trackers_created_dt_gt: Union[Unset, None, datetime.datetime] = UNSET,
     affects_trackers_created_dt_gte: Union[Unset, None, datetime.datetime] = UNSET,
     affects_trackers_created_dt_lt: Union[Unset, None, datetime.datetime] = UNSET,
     affects_trackers_created_dt_lte: Union[Unset, None, datetime.datetime] = UNSET,
     affects_trackers_embargoed: Union[Unset, None, bool] = UNSET,
+    affects_trackers_errata_advisory_name: Union[Unset, None, str] = UNSET,
     affects_trackers_external_system_id: Union[Unset, None, str] = UNSET,
     affects_trackers_ps_update_stream: Union[Unset, None, str] = UNSET,
     affects_trackers_resolution: Union[Unset, None, str] = UNSET,
     affects_trackers_status: Union[Unset, None, str] = UNSET,
     affects_trackers_type: Union[
         Unset, None, OsidbApiV1FlawsListAffectsTrackersType
     ] = UNSET,
@@ -1088,14 +1092,15 @@
         affects_trackers_created_dt_date_gte=affects_trackers_created_dt_date_gte,
         affects_trackers_created_dt_date_lte=affects_trackers_created_dt_date_lte,
         affects_trackers_created_dt_gt=affects_trackers_created_dt_gt,
         affects_trackers_created_dt_gte=affects_trackers_created_dt_gte,
         affects_trackers_created_dt_lt=affects_trackers_created_dt_lt,
         affects_trackers_created_dt_lte=affects_trackers_created_dt_lte,
         affects_trackers_embargoed=affects_trackers_embargoed,
+        affects_trackers_errata_advisory_name=affects_trackers_errata_advisory_name,
         affects_trackers_external_system_id=affects_trackers_external_system_id,
         affects_trackers_ps_update_stream=affects_trackers_ps_update_stream,
         affects_trackers_resolution=affects_trackers_resolution,
         affects_trackers_status=affects_trackers_status,
         affects_trackers_type=affects_trackers_type,
         affects_trackers_updated_dt=affects_trackers_updated_dt,
         affects_trackers_updated_dt_date=affects_trackers_updated_dt_date,
@@ -1231,14 +1236,15 @@
     affects_trackers_created_dt_date_gte: Union[Unset, None, datetime.date] = UNSET,
     affects_trackers_created_dt_date_lte: Union[Unset, None, datetime.date] = UNSET,
     affects_trackers_created_dt_gt: Union[Unset, None, datetime.datetime] = UNSET,
     affects_trackers_created_dt_gte: Union[Unset, None, datetime.datetime] = UNSET,
     affects_trackers_created_dt_lt: Union[Unset, None, datetime.datetime] = UNSET,
     affects_trackers_created_dt_lte: Union[Unset, None, datetime.datetime] = UNSET,
     affects_trackers_embargoed: Union[Unset, None, bool] = UNSET,
+    affects_trackers_errata_advisory_name: Union[Unset, None, str] = UNSET,
     affects_trackers_external_system_id: Union[Unset, None, str] = UNSET,
     affects_trackers_ps_update_stream: Union[Unset, None, str] = UNSET,
     affects_trackers_resolution: Union[Unset, None, str] = UNSET,
     affects_trackers_status: Union[Unset, None, str] = UNSET,
     affects_trackers_type: Union[
         Unset, None, OsidbApiV1FlawsListAffectsTrackersType
     ] = UNSET,
@@ -1361,14 +1367,15 @@
         affects_trackers_created_dt_date_gte=affects_trackers_created_dt_date_gte,
         affects_trackers_created_dt_date_lte=affects_trackers_created_dt_date_lte,
         affects_trackers_created_dt_gt=affects_trackers_created_dt_gt,
         affects_trackers_created_dt_gte=affects_trackers_created_dt_gte,
         affects_trackers_created_dt_lt=affects_trackers_created_dt_lt,
         affects_trackers_created_dt_lte=affects_trackers_created_dt_lte,
         affects_trackers_embargoed=affects_trackers_embargoed,
+        affects_trackers_errata_advisory_name=affects_trackers_errata_advisory_name,
         affects_trackers_external_system_id=affects_trackers_external_system_id,
         affects_trackers_ps_update_stream=affects_trackers_ps_update_stream,
         affects_trackers_resolution=affects_trackers_resolution,
         affects_trackers_status=affects_trackers_status,
         affects_trackers_type=affects_trackers_type,
         affects_trackers_updated_dt=affects_trackers_updated_dt,
         affects_trackers_updated_dt_date=affects_trackers_updated_dt_date,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_update.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_update.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_manifest_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_manifest_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_schema_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_schema_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_status_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_status_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_trackers_list.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_trackers_list.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_trackers_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_trackers_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_healthy_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_healthy_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osidb/osidb_whoami_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osidb/osidb_whoami_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osim/osim_api_v1_workflows_adjust_create.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osim/osim_api_v1_workflows_adjust_create.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osim/osim_api_v1_workflows_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osim/osim_api_v1_workflows_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osim/osim_api_v1_workflows_retrieve_2.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osim/osim_api_v1_workflows_retrieve_2.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osim/osim_healthy_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osim/osim_healthy_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/osim/osim_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/osim/osim_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_create.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_create.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_update.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_update.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 from typing import Any, Dict, Optional
 
 import requests
 
 from ...client import AuthenticatedClient
-from ...models.taskman_api_v1_group_update_response_204 import (
-    TaskmanApiV1GroupUpdateResponse204,
+from ...models.taskman_api_v1_group_update_response_200 import (
+    TaskmanApiV1GroupUpdateResponse200,
 )
 from ...types import UNSET, Response, Unset
 
 QUERY_PARAMS = {
     "task_key": str,
 }
 
@@ -39,45 +39,45 @@
         "headers": headers,
         "params": params,
     }
 
 
 def _parse_response(
     *, response: requests.Response
-) -> Optional[TaskmanApiV1GroupUpdateResponse204]:
-    if response.status_code == 204:
-        _response_204 = response.json()
-        response_204: TaskmanApiV1GroupUpdateResponse204
-        if isinstance(_response_204, Unset):
-            response_204 = UNSET
+) -> Optional[TaskmanApiV1GroupUpdateResponse200]:
+    if response.status_code == 200:
+        _response_200 = response.json()
+        response_200: TaskmanApiV1GroupUpdateResponse200
+        if isinstance(_response_200, Unset):
+            response_200 = UNSET
         else:
-            response_204 = TaskmanApiV1GroupUpdateResponse204.from_dict(_response_204)
+            response_200 = TaskmanApiV1GroupUpdateResponse200.from_dict(_response_200)
 
-        return response_204
+        return response_200
     return None
 
 
 def _build_response(
     *, response: requests.Response
-) -> Response[TaskmanApiV1GroupUpdateResponse204]:
+) -> Response[TaskmanApiV1GroupUpdateResponse200]:
     return Response(
         status_code=response.status_code,
         content=response.content,
         headers=response.headers,
         parsed=_parse_response(response=response),
     )
 
 
 def sync_detailed(
     group_key: str,
     *,
     client: AuthenticatedClient,
     task_key: str,
     jira_authentication: str,
-) -> Response[TaskmanApiV1GroupUpdateResponse204]:
+) -> Response[TaskmanApiV1GroupUpdateResponse200]:
     kwargs = _get_kwargs(
         group_key=group_key,
         client=client,
         task_key=task_key,
         jira_authentication=jira_authentication,
     )
 
@@ -94,15 +94,15 @@
 
 def sync(
     group_key: str,
     *,
     client: AuthenticatedClient,
     task_key: str,
     jira_authentication: str,
-) -> Optional[TaskmanApiV1GroupUpdateResponse204]:
+) -> Optional[TaskmanApiV1GroupUpdateResponse200]:
     """Add a task into a group"""
 
     return sync_detailed(
         group_key=group_key,
         client=client,
         task_key=task_key,
         jira_authentication=jira_authentication,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_comment_create.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_comment_create.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_comment_update.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_comment_update.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_create.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_create.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_update.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_update.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 from typing import Any, Dict, Optional
 
 import requests
 
 from ...client import AuthenticatedClient
-from ...models.taskman_api_v1_task_flaw_update_response_204 import (
-    TaskmanApiV1TaskFlawUpdateResponse204,
+from ...models.taskman_api_v1_task_flaw_update_response_200 import (
+    TaskmanApiV1TaskFlawUpdateResponse200,
 )
 from ...types import UNSET, Response, Unset
 
 QUERY_PARAMS = {}
 
 
 def _get_kwargs(
@@ -30,46 +30,46 @@
         "url": url,
         "headers": headers,
     }
 
 
 def _parse_response(
     *, response: requests.Response
-) -> Optional[TaskmanApiV1TaskFlawUpdateResponse204]:
-    if response.status_code == 204:
-        _response_204 = response.json()
-        response_204: TaskmanApiV1TaskFlawUpdateResponse204
-        if isinstance(_response_204, Unset):
-            response_204 = UNSET
+) -> Optional[TaskmanApiV1TaskFlawUpdateResponse200]:
+    if response.status_code == 200:
+        _response_200 = response.json()
+        response_200: TaskmanApiV1TaskFlawUpdateResponse200
+        if isinstance(_response_200, Unset):
+            response_200 = UNSET
         else:
-            response_204 = TaskmanApiV1TaskFlawUpdateResponse204.from_dict(
-                _response_204
+            response_200 = TaskmanApiV1TaskFlawUpdateResponse200.from_dict(
+                _response_200
             )
 
-        return response_204
+        return response_200
     return None
 
 
 def _build_response(
     *, response: requests.Response
-) -> Response[TaskmanApiV1TaskFlawUpdateResponse204]:
+) -> Response[TaskmanApiV1TaskFlawUpdateResponse200]:
     return Response(
         status_code=response.status_code,
         content=response.content,
         headers=response.headers,
         parsed=_parse_response(response=response),
     )
 
 
 def sync_detailed(
     flaw_uuid: str,
     *,
     client: AuthenticatedClient,
     jira_authentication: str,
-) -> Response[TaskmanApiV1TaskFlawUpdateResponse204]:
+) -> Response[TaskmanApiV1TaskFlawUpdateResponse200]:
     kwargs = _get_kwargs(
         flaw_uuid=flaw_uuid,
         client=client,
         jira_authentication=jira_authentication,
     )
 
     response = requests.put(
@@ -84,15 +84,15 @@
 
 
 def sync(
     flaw_uuid: str,
     *,
     client: AuthenticatedClient,
     jira_authentication: str,
-) -> Optional[TaskmanApiV1TaskFlawUpdateResponse204]:
+) -> Optional[TaskmanApiV1TaskFlawUpdateResponse200]:
     """Update a task in Jira from a Flaw"""
 
     return sync_detailed(
         flaw_uuid=flaw_uuid,
         client=client,
         jira_authentication=jira_authentication,
     ).parsed
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_status_update.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_assignee_retrieve.py`

 * *Files 17% similar despite different names*

```diff
@@ -1,119 +1,98 @@
 from typing import Any, Dict, Optional
 
 import requests
 
 from ...client import AuthenticatedClient
-from ...models.taskman_api_v1_task_status_update_response_204 import (
-    TaskmanApiV1TaskStatusUpdateResponse204,
-)
-from ...models.taskman_api_v1_task_status_update_status import (
-    TaskmanApiV1TaskStatusUpdateStatus,
+from ...models.taskman_api_v1_task_assignee_retrieve_response_200 import (
+    TaskmanApiV1TaskAssigneeRetrieveResponse200,
 )
 from ...types import UNSET, Response, Unset
 
-QUERY_PARAMS = {
-    "status": TaskmanApiV1TaskStatusUpdateStatus,
-}
+QUERY_PARAMS = {}
 
 
 def _get_kwargs(
-    task_key: str,
+    user: str,
     *,
     client: AuthenticatedClient,
-    status: TaskmanApiV1TaskStatusUpdateStatus,
     jira_authentication: str,
 ) -> Dict[str, Any]:
-    url = "{}/taskman/api/v1/task/{task_key}/status".format(
+    url = "{}/taskman/api/v1/task/assignee/{user}".format(
         client.base_url,
-        task_key=task_key,
+        user=user,
     )
 
     headers: Dict[str, Any] = client.get_headers()
 
     headers["jira-authentication"] = jira_authentication
 
-    json_status: str = UNSET
-    if not isinstance(status, Unset):
-
-        json_status = TaskmanApiV1TaskStatusUpdateStatus(status).value
-
-    params: Dict[str, Any] = {
-        "status": json_status,
-    }
-    params = {k: v for k, v in params.items() if v is not UNSET and v is not None}
-
     return {
         "url": url,
         "headers": headers,
-        "params": params,
     }
 
 
 def _parse_response(
     *, response: requests.Response
-) -> Optional[TaskmanApiV1TaskStatusUpdateResponse204]:
-    if response.status_code == 204:
-        _response_204 = response.json()
-        response_204: TaskmanApiV1TaskStatusUpdateResponse204
-        if isinstance(_response_204, Unset):
-            response_204 = UNSET
+) -> Optional[TaskmanApiV1TaskAssigneeRetrieveResponse200]:
+    if response.status_code == 200:
+        _response_200 = response.json()
+        response_200: TaskmanApiV1TaskAssigneeRetrieveResponse200
+        if isinstance(_response_200, Unset):
+            response_200 = UNSET
         else:
-            response_204 = TaskmanApiV1TaskStatusUpdateResponse204.from_dict(
-                _response_204
+            response_200 = TaskmanApiV1TaskAssigneeRetrieveResponse200.from_dict(
+                _response_200
             )
 
-        return response_204
+        return response_200
     return None
 
 
 def _build_response(
     *, response: requests.Response
-) -> Response[TaskmanApiV1TaskStatusUpdateResponse204]:
+) -> Response[TaskmanApiV1TaskAssigneeRetrieveResponse200]:
     return Response(
         status_code=response.status_code,
         content=response.content,
         headers=response.headers,
         parsed=_parse_response(response=response),
     )
 
 
 def sync_detailed(
-    task_key: str,
+    user: str,
     *,
     client: AuthenticatedClient,
-    status: TaskmanApiV1TaskStatusUpdateStatus,
     jira_authentication: str,
-) -> Response[TaskmanApiV1TaskStatusUpdateResponse204]:
+) -> Response[TaskmanApiV1TaskAssigneeRetrieveResponse200]:
     kwargs = _get_kwargs(
-        task_key=task_key,
+        user=user,
         client=client,
-        status=status,
         jira_authentication=jira_authentication,
     )
 
-    response = requests.put(
+    response = requests.get(
         verify=client.verify_ssl,
         auth=client.auth,
         timeout=client.timeout,
         **kwargs,
     )
     response.raise_for_status()
 
     return _build_response(response=response)
 
 
 def sync(
-    task_key: str,
+    user: str,
     *,
     client: AuthenticatedClient,
-    status: TaskmanApiV1TaskStatusUpdateStatus,
     jira_authentication: str,
-) -> Optional[TaskmanApiV1TaskStatusUpdateResponse204]:
-    """Change a task workflow status"""
+) -> Optional[TaskmanApiV1TaskAssigneeRetrieveResponse200]:
+    """Get a list of tasks from a user"""
 
     return sync_detailed(
-        task_key=task_key,
+        user=user,
         client=client,
-        status=status,
         jira_authentication=jira_authentication,
     ).parsed
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/api/taskman/taskman_healthy_retrieve.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/api/taskman/taskman_healthy_retrieve.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/client.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/client.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/__init__.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/__init__.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,14 +1,15 @@
 """ Contains all the data models used in inputs/outputs """
 
 from .affect import Affect
 from .affect_meta_attr import AffectMetaAttr
 from .affect_post import AffectPost
 from .affect_post_meta_attr import AffectPostMetaAttr
 from .affect_report_data import AffectReportData
+from .affect_type import AffectType
 from .affectedness_enum import AffectednessEnum
 from .auth_token_create_response_200 import AuthTokenCreateResponse200
 from .auth_token_refresh_create_response_200 import AuthTokenRefreshCreateResponse200
 from .auth_token_retrieve_response_200 import AuthTokenRetrieveResponse200
 from .auth_token_verify_create_response_200 import AuthTokenVerifyCreateResponse200
 from .blank_enum import BlankEnum
 from .collectors_api_v1_status_retrieve_response_200 import (
@@ -28,15 +29,14 @@
 )
 from .collectors_healthy_retrieve_response_200 import (
     CollectorsHealthyRetrieveResponse200,
 )
 from .collectors_retrieve_response_200 import CollectorsRetrieveResponse200
 from .comment import Comment
 from .comment_meta_attr import CommentMetaAttr
-from .comment_type_enum import CommentTypeEnum
 from .cv_ev_5_package_versions import CVEv5PackageVersions
 from .cv_ev_5_versions import CVEv5Versions
 from .epss import EPSS
 from .erratum import Erratum
 from .exploit_only_report_data import ExploitOnlyReportData
 from .exploit_only_report_data_source_enum import ExploitOnlyReportDataSourceEnum
 from .exploits_api_v1_collect_update_response_200 import (
@@ -84,31 +84,39 @@
 )
 from .exploits_api_v1_supported_products_list_response_200 import (
     ExploitsApiV1SupportedProductsListResponse200,
 )
 from .flaw import Flaw
 from .flaw_classification import FlawClassification
 from .flaw_classification_state import FlawClassificationState
+from .flaw_comment import FlawComment
+from .flaw_comment_post import FlawCommentPost
+from .flaw_comment_post_meta_attr import FlawCommentPostMetaAttr
+from .flaw_comment_type import FlawCommentType
 from .flaw_meta_attr import FlawMetaAttr
+from .flaw_meta_type import FlawMetaType
 from .flaw_post import FlawPost
 from .flaw_post_classification import FlawPostClassification
 from .flaw_post_classification_state import FlawPostClassificationState
 from .flaw_post_meta_attr import FlawPostMetaAttr
+from .flaw_reference import FlawReference
+from .flaw_reference_post import FlawReferencePost
+from .flaw_reference_type import FlawReferenceType
 from .flaw_report_data import FlawReportData
+from .flaw_type import FlawType
 from .impact_enum import ImpactEnum
 from .jira_comment import JiraComment
 from .jira_issue import JiraIssue
 from .jira_issue_fields import JiraIssueFields
 from .jira_issue_query_result import JiraIssueQueryResult
 from .jira_issue_type import JiraIssueType
 from .jira_user import JiraUser
 from .maturity_preliminary_enum import MaturityPreliminaryEnum
 from .meta import Meta
 from .meta_meta_attr import MetaMetaAttr
-from .meta_type_enum import MetaTypeEnum
 from .osidb_api_v1_affects_create_response_201 import OsidbApiV1AffectsCreateResponse201
 from .osidb_api_v1_affects_destroy_response_204 import (
     OsidbApiV1AffectsDestroyResponse204,
 )
 from .osidb_api_v1_affects_list_affectedness import OsidbApiV1AffectsListAffectedness
 from .osidb_api_v1_affects_list_flaw_impact import OsidbApiV1AffectsListFlawImpact
 from .osidb_api_v1_affects_list_flaw_source import OsidbApiV1AffectsListFlawSource
@@ -119,14 +127,23 @@
 from .osidb_api_v1_affects_list_response_200 import OsidbApiV1AffectsListResponse200
 from .osidb_api_v1_affects_list_trackers_type import OsidbApiV1AffectsListTrackersType
 from .osidb_api_v1_affects_list_type import OsidbApiV1AffectsListType
 from .osidb_api_v1_affects_retrieve_response_200 import (
     OsidbApiV1AffectsRetrieveResponse200,
 )
 from .osidb_api_v1_affects_update_response_200 import OsidbApiV1AffectsUpdateResponse200
+from .osidb_api_v1_flaws_comments_create_response_201 import (
+    OsidbApiV1FlawsCommentsCreateResponse201,
+)
+from .osidb_api_v1_flaws_comments_list_response_200 import (
+    OsidbApiV1FlawsCommentsListResponse200,
+)
+from .osidb_api_v1_flaws_comments_retrieve_response_200 import (
+    OsidbApiV1FlawsCommentsRetrieveResponse200,
+)
 from .osidb_api_v1_flaws_create_response_201 import OsidbApiV1FlawsCreateResponse201
 from .osidb_api_v1_flaws_list_affects_affectedness import (
     OsidbApiV1FlawsListAffectsAffectedness,
 )
 from .osidb_api_v1_flaws_list_affects_impact import OsidbApiV1FlawsListAffectsImpact
 from .osidb_api_v1_flaws_list_affects_resolution import (
     OsidbApiV1FlawsListAffectsResolution,
@@ -136,14 +153,29 @@
 )
 from .osidb_api_v1_flaws_list_affects_type import OsidbApiV1FlawsListAffectsType
 from .osidb_api_v1_flaws_list_impact import OsidbApiV1FlawsListImpact
 from .osidb_api_v1_flaws_list_order_item import OsidbApiV1FlawsListOrderItem
 from .osidb_api_v1_flaws_list_response_200 import OsidbApiV1FlawsListResponse200
 from .osidb_api_v1_flaws_list_source import OsidbApiV1FlawsListSource
 from .osidb_api_v1_flaws_list_type import OsidbApiV1FlawsListType
+from .osidb_api_v1_flaws_references_create_response_201 import (
+    OsidbApiV1FlawsReferencesCreateResponse201,
+)
+from .osidb_api_v1_flaws_references_destroy_response_204 import (
+    OsidbApiV1FlawsReferencesDestroyResponse204,
+)
+from .osidb_api_v1_flaws_references_list_response_200 import (
+    OsidbApiV1FlawsReferencesListResponse200,
+)
+from .osidb_api_v1_flaws_references_retrieve_response_200 import (
+    OsidbApiV1FlawsReferencesRetrieveResponse200,
+)
+from .osidb_api_v1_flaws_references_update_response_200 import (
+    OsidbApiV1FlawsReferencesUpdateResponse200,
+)
 from .osidb_api_v1_flaws_retrieve_response_200 import OsidbApiV1FlawsRetrieveResponse200
 from .osidb_api_v1_flaws_update_response_200 import OsidbApiV1FlawsUpdateResponse200
 from .osidb_api_v1_manifest_retrieve_response_200 import (
     OsidbApiV1ManifestRetrieveResponse200,
 )
 from .osidb_api_v1_schema_retrieve_format import OsidbApiV1SchemaRetrieveFormat
 from .osidb_api_v1_schema_retrieve_lang import OsidbApiV1SchemaRetrieveLang
@@ -199,52 +231,65 @@
     OsimApiV1WorkflowsRetrieveResponse200,
 )
 from .osim_healthy_retrieve_response_200 import OsimHealthyRetrieveResponse200
 from .osim_retrieve_response_200 import OsimRetrieveResponse200
 from .paginated_affect_list import PaginatedAffectList
 from .paginated_epss_list import PaginatedEPSSList
 from .paginated_exploit_only_report_data_list import PaginatedExploitOnlyReportDataList
+from .paginated_flaw_comment_list import PaginatedFlawCommentList
 from .paginated_flaw_list import PaginatedFlawList
+from .paginated_flaw_reference_list import PaginatedFlawReferenceList
 from .paginated_flaw_report_data_list import PaginatedFlawReportDataList
 from .paginated_supported_products_list import PaginatedSupportedProductsList
 from .paginated_tracker_list import PaginatedTrackerList
 from .resolution_enum import ResolutionEnum
 from .source_666_enum import Source666Enum
 from .status_enum import StatusEnum
 from .supported_products import SupportedProducts
 from .taskman_api_v1_group_create_response_200 import TaskmanApiV1GroupCreateResponse200
 from .taskman_api_v1_group_retrieve_response_200 import (
     TaskmanApiV1GroupRetrieveResponse200,
 )
-from .taskman_api_v1_group_update_response_204 import TaskmanApiV1GroupUpdateResponse204
+from .taskman_api_v1_group_update_response_200 import TaskmanApiV1GroupUpdateResponse200
+from .taskman_api_v1_task_assignee_retrieve_response_200 import (
+    TaskmanApiV1TaskAssigneeRetrieveResponse200,
+)
+from .taskman_api_v1_task_assignee_update_response_200 import (
+    TaskmanApiV1TaskAssigneeUpdateResponse200,
+)
 from .taskman_api_v1_task_comment_create_response_200 import (
     TaskmanApiV1TaskCommentCreateResponse200,
 )
 from .taskman_api_v1_task_comment_update_response_200 import (
     TaskmanApiV1TaskCommentUpdateResponse200,
 )
 from .taskman_api_v1_task_flaw_create_response_200 import (
     TaskmanApiV1TaskFlawCreateResponse200,
 )
 from .taskman_api_v1_task_flaw_retrieve_response_200 import (
     TaskmanApiV1TaskFlawRetrieveResponse200,
 )
-from .taskman_api_v1_task_flaw_update_response_204 import (
-    TaskmanApiV1TaskFlawUpdateResponse204,
+from .taskman_api_v1_task_flaw_update_response_200 import (
+    TaskmanApiV1TaskFlawUpdateResponse200,
 )
 from .taskman_api_v1_task_retrieve_response_200 import (
     TaskmanApiV1TaskRetrieveResponse200,
 )
-from .taskman_api_v1_task_status_update_response_204 import (
-    TaskmanApiV1TaskStatusUpdateResponse204,
+from .taskman_api_v1_task_status_update_reason import TaskmanApiV1TaskStatusUpdateReason
+from .taskman_api_v1_task_status_update_resolution import (
+    TaskmanApiV1TaskStatusUpdateResolution,
+)
+from .taskman_api_v1_task_status_update_response_200 import (
+    TaskmanApiV1TaskStatusUpdateResponse200,
 )
 from .taskman_api_v1_task_status_update_status import TaskmanApiV1TaskStatusUpdateStatus
+from .taskman_api_v1_task_unassigned_retrieve_response_200 import (
+    TaskmanApiV1TaskUnassignedRetrieveResponse200,
+)
 from .taskman_healthy_retrieve_response_200 import TaskmanHealthyRetrieveResponse200
 from .token_obtain_pair import TokenObtainPair
 from .token_refresh import TokenRefresh
 from .token_verify import TokenVerify
 from .tracker import Tracker
 from .tracker_meta_attr import TrackerMetaAttr
 from .tracker_report_data import TrackerReportData
-from .type_0d0_enum import Type0D0Enum
-from .type_5b2_enum import Type5B2Enum
-from .type_824_enum import Type824Enum
+from .tracker_type import TrackerType
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/affect.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/affect.py`

 * *Files 0% similar despite different names*

```diff
@@ -2,20 +2,20 @@
 import json
 from typing import Any, Dict, List, Optional, Tuple, Type, TypeVar, Union
 
 import attr
 from dateutil.parser import isoparse
 
 from ..models.affect_meta_attr import AffectMetaAttr
+from ..models.affect_type import AffectType
 from ..models.affectedness_enum import AffectednessEnum
 from ..models.blank_enum import BlankEnum
 from ..models.impact_enum import ImpactEnum
 from ..models.resolution_enum import ResolutionEnum
 from ..models.tracker import Tracker
-from ..models.type_5b2_enum import Type5B2Enum
 from ..types import UNSET, OSIDBModel, Unset
 
 T = TypeVar("T", bound="Affect")
 
 
 @attr.s(auto_attribs=True)
 class Affect(OSIDBModel):
@@ -27,15 +27,15 @@
     trackers: List[Tracker]
     meta_attr: AffectMetaAttr
     delegated_resolution: str
     embargoed: bool
     created_dt: datetime.datetime
     updated_dt: datetime.datetime
     flaw: Optional[str]
-    type: Union[Unset, Type5B2Enum] = UNSET
+    type: Union[Unset, AffectType] = UNSET
     affectedness: Union[AffectednessEnum, BlankEnum, Unset] = UNSET
     resolution: Union[BlankEnum, ResolutionEnum, Unset] = UNSET
     impact: Union[BlankEnum, ImpactEnum, Unset] = UNSET
     cvss2: Union[Unset, str] = UNSET
     cvss2_score: Union[Unset, None, float] = UNSET
     cvss3: Union[Unset, str] = UNSET
     cvss3_score: Union[Unset, None, float] = UNSET
@@ -69,15 +69,15 @@
         if not isinstance(self.updated_dt, Unset):
             updated_dt = self.updated_dt.isoformat()
 
         flaw = self.flaw
         type: Union[Unset, str] = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type5B2Enum(self.type).value
+            type = AffectType(self.type).value
 
         affectedness: Union[Unset, str]
         if isinstance(self.affectedness, Unset):
             affectedness = UNSET
         elif isinstance(self.affectedness, AffectednessEnum):
             affectedness = UNSET
             if not isinstance(self.affectedness, Unset):
@@ -211,15 +211,15 @@
         if not isinstance(self.updated_dt, Unset):
             updated_dt = self.updated_dt.isoformat()
 
         flaw = self.flaw if self.flaw is UNSET else (None, str(self.flaw), "text/plain")
         type: Union[Unset, Tuple[None, str, str]] = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type5B2Enum(self.type).value
+            type = AffectType(self.type).value
 
         affectedness: Union[Unset, str]
         if isinstance(self.affectedness, Unset):
             affectedness = UNSET
         elif isinstance(self.affectedness, AffectednessEnum):
             affectedness = UNSET
             if not isinstance(self.affectedness, Unset):
@@ -373,19 +373,19 @@
             updated_dt = UNSET
         else:
             updated_dt = isoparse(_updated_dt)
 
         flaw = d.pop("flaw", UNSET)
 
         _type = d.pop("type", UNSET)
-        type: Union[Unset, Type5B2Enum]
+        type: Union[Unset, AffectType]
         if isinstance(_type, Unset):
             type = UNSET
         else:
-            type = Type5B2Enum(_type)
+            type = AffectType(_type)
 
         def _parse_affectedness(
             data: object,
         ) -> Union[AffectednessEnum, BlankEnum, Unset]:
             if isinstance(data, Unset):
                 return data
             try:
@@ -513,15 +513,15 @@
             "trackers": List[Tracker],
             "meta_attr": AffectMetaAttr,
             "delegated_resolution": str,
             "embargoed": bool,
             "created_dt": datetime.datetime,
             "updated_dt": datetime.datetime,
             "flaw": str,
-            "type": Type5B2Enum,
+            "type": AffectType,
             "affectedness": Union[AffectednessEnum, BlankEnum],
             "resolution": Union[BlankEnum, ResolutionEnum],
             "impact": Union[BlankEnum, ImpactEnum],
             "cvss2": str,
             "cvss2_score": float,
             "cvss3": str,
             "cvss3_score": float,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/affect_meta_attr.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/affect_meta_attr.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/affect_post.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/affect_post.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,20 +2,20 @@
 import json
 from typing import Any, Dict, List, Optional, Tuple, Type, TypeVar, Union
 
 import attr
 from dateutil.parser import isoparse
 
 from ..models.affect_post_meta_attr import AffectPostMetaAttr
+from ..models.affect_type import AffectType
 from ..models.affectedness_enum import AffectednessEnum
 from ..models.blank_enum import BlankEnum
 from ..models.impact_enum import ImpactEnum
 from ..models.resolution_enum import ResolutionEnum
 from ..models.tracker import Tracker
-from ..models.type_5b2_enum import Type5B2Enum
 from ..types import UNSET, OSIDBModel, Unset
 
 T = TypeVar("T", bound="AffectPost")
 
 
 @attr.s(auto_attribs=True)
 class AffectPost(OSIDBModel):
@@ -26,15 +26,15 @@
     ps_component: str
     trackers: List[Tracker]
     meta_attr: AffectPostMetaAttr
     delegated_resolution: str
     embargoed: bool
     created_dt: datetime.datetime
     flaw: Optional[str]
-    type: Union[Unset, Type5B2Enum] = UNSET
+    type: Union[Unset, AffectType] = UNSET
     affectedness: Union[AffectednessEnum, BlankEnum, Unset] = UNSET
     resolution: Union[BlankEnum, ResolutionEnum, Unset] = UNSET
     impact: Union[BlankEnum, ImpactEnum, Unset] = UNSET
     cvss2: Union[Unset, str] = UNSET
     cvss2_score: Union[Unset, None, float] = UNSET
     cvss3: Union[Unset, str] = UNSET
     cvss3_score: Union[Unset, None, float] = UNSET
@@ -64,15 +64,15 @@
         if not isinstance(self.created_dt, Unset):
             created_dt = self.created_dt.isoformat()
 
         flaw = self.flaw
         type: Union[Unset, str] = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type5B2Enum(self.type).value
+            type = AffectType(self.type).value
 
         affectedness: Union[Unset, str]
         if isinstance(self.affectedness, Unset):
             affectedness = UNSET
         elif isinstance(self.affectedness, AffectednessEnum):
             affectedness = UNSET
             if not isinstance(self.affectedness, Unset):
@@ -200,15 +200,15 @@
         if not isinstance(self.created_dt, Unset):
             created_dt = self.created_dt.isoformat()
 
         flaw = self.flaw if self.flaw is UNSET else (None, str(self.flaw), "text/plain")
         type: Union[Unset, Tuple[None, str, str]] = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type5B2Enum(self.type).value
+            type = AffectType(self.type).value
 
         affectedness: Union[Unset, str]
         if isinstance(self.affectedness, Unset):
             affectedness = UNSET
         elif isinstance(self.affectedness, AffectednessEnum):
             affectedness = UNSET
             if not isinstance(self.affectedness, Unset):
@@ -353,19 +353,19 @@
             created_dt = UNSET
         else:
             created_dt = isoparse(_created_dt)
 
         flaw = d.pop("flaw", UNSET)
 
         _type = d.pop("type", UNSET)
-        type: Union[Unset, Type5B2Enum]
+        type: Union[Unset, AffectType]
         if isinstance(_type, Unset):
             type = UNSET
         else:
-            type = Type5B2Enum(_type)
+            type = AffectType(_type)
 
         def _parse_affectedness(
             data: object,
         ) -> Union[AffectednessEnum, BlankEnum, Unset]:
             if isinstance(data, Unset):
                 return data
             try:
@@ -491,15 +491,15 @@
             "ps_component": str,
             "trackers": List[Tracker],
             "meta_attr": AffectPostMetaAttr,
             "delegated_resolution": str,
             "embargoed": bool,
             "created_dt": datetime.datetime,
             "flaw": str,
-            "type": Type5B2Enum,
+            "type": AffectType,
             "affectedness": Union[AffectednessEnum, BlankEnum],
             "resolution": Union[BlankEnum, ResolutionEnum],
             "impact": Union[BlankEnum, ImpactEnum],
             "cvss2": str,
             "cvss2_score": float,
             "cvss3": str,
             "cvss3_score": float,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/affect_post_meta_attr.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/affect_post_meta_attr.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/affect_report_data.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/affect_report_data.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/auth_token_create_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/auth_token_create_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/auth_token_refresh_create_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/auth_token_refresh_create_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/auth_token_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/auth_token_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/auth_token_verify_create_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/auth_token_verify_create_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item_error.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item_error.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/collectors_healthy_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/collectors_healthy_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/collectors_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/collectors_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/comment.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/meta.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,79 +1,82 @@
 import datetime
 from typing import Any, Dict, List, Type, TypeVar, Union
 
 import attr
 from dateutil.parser import isoparse
 
-from ..models.comment_meta_attr import CommentMetaAttr
-from ..models.comment_type_enum import CommentTypeEnum
+from ..models.flaw_meta_type import FlawMetaType
+from ..models.meta_meta_attr import MetaMetaAttr
 from ..types import UNSET, OSIDBModel, Unset
 
-T = TypeVar("T", bound="Comment")
+T = TypeVar("T", bound="Meta")
 
 
 @attr.s(auto_attribs=True)
-class Comment(OSIDBModel):
-    """FlawComment serializer"""
+class Meta(OSIDBModel):
+    """FlawMeta serializer"""
 
     uuid: str
-    external_system_id: str
+    type: FlawMetaType
+    embargoed: bool
     created_dt: datetime.datetime
     updated_dt: datetime.datetime
-    type: Union[Unset, CommentTypeEnum] = UNSET
-    order: Union[Unset, None, int] = UNSET
-    meta_attr: Union[Unset, CommentMetaAttr] = UNSET
+    meta_attr: Union[Unset, MetaMetaAttr] = UNSET
     additional_properties: Dict[str, Any] = attr.ib(init=False, factory=dict)
 
     def to_dict(self) -> Dict[str, Any]:
         uuid = self.uuid
-        external_system_id = self.external_system_id
+        type: str = UNSET
+        if not isinstance(self.type, Unset):
+
+            type = FlawMetaType(self.type).value
+
+        embargoed = self.embargoed
         created_dt: str = UNSET
         if not isinstance(self.created_dt, Unset):
             created_dt = self.created_dt.isoformat()
 
         updated_dt: str = UNSET
         if not isinstance(self.updated_dt, Unset):
             updated_dt = self.updated_dt.isoformat()
 
-        type: Union[Unset, str] = UNSET
-        if not isinstance(self.type, Unset):
-
-            type = CommentTypeEnum(self.type).value
-
-        order = self.order
         meta_attr: Union[Unset, Dict[str, Any]] = UNSET
         if not isinstance(self.meta_attr, Unset):
             meta_attr = self.meta_attr.to_dict()
 
         field_dict: Dict[str, Any] = {}
         field_dict.update(self.additional_properties)
         if uuid is not UNSET:
             field_dict["uuid"] = uuid
-        if external_system_id is not UNSET:
-            field_dict["external_system_id"] = external_system_id
+        if type is not UNSET:
+            field_dict["type"] = type
+        if embargoed is not UNSET:
+            field_dict["embargoed"] = embargoed
         if created_dt is not UNSET:
             field_dict["created_dt"] = created_dt
         if updated_dt is not UNSET:
             field_dict["updated_dt"] = updated_dt
-        if type is not UNSET:
-            field_dict["type"] = type
-        if order is not UNSET:
-            field_dict["order"] = order
         if meta_attr is not UNSET:
             field_dict["meta_attr"] = meta_attr
 
         return field_dict
 
     @classmethod
     def from_dict(cls: Type[T], src_dict: Dict[str, Any]) -> T:
         d = src_dict.copy()
         uuid = d.pop("uuid", UNSET)
 
-        external_system_id = d.pop("external_system_id", UNSET)
+        _type = d.pop("type", UNSET)
+        type: FlawMetaType
+        if isinstance(_type, Unset):
+            type = UNSET
+        else:
+            type = FlawMetaType(_type)
+
+        embargoed = d.pop("embargoed", UNSET)
 
         _created_dt = d.pop("created_dt", UNSET)
         created_dt: datetime.datetime
         if isinstance(_created_dt, Unset):
             created_dt = UNSET
         else:
             created_dt = isoparse(_created_dt)
@@ -81,53 +84,42 @@
         _updated_dt = d.pop("updated_dt", UNSET)
         updated_dt: datetime.datetime
         if isinstance(_updated_dt, Unset):
             updated_dt = UNSET
         else:
             updated_dt = isoparse(_updated_dt)
 
-        _type = d.pop("type", UNSET)
-        type: Union[Unset, CommentTypeEnum]
-        if isinstance(_type, Unset):
-            type = UNSET
-        else:
-            type = CommentTypeEnum(_type)
-
-        order = d.pop("order", UNSET)
-
         _meta_attr = d.pop("meta_attr", UNSET)
-        meta_attr: Union[Unset, CommentMetaAttr]
+        meta_attr: Union[Unset, MetaMetaAttr]
         if isinstance(_meta_attr, Unset):
             meta_attr = UNSET
         else:
-            meta_attr = CommentMetaAttr.from_dict(_meta_attr)
+            meta_attr = MetaMetaAttr.from_dict(_meta_attr)
 
-        comment = cls(
+        meta = cls(
             uuid=uuid,
-            external_system_id=external_system_id,
+            type=type,
+            embargoed=embargoed,
             created_dt=created_dt,
             updated_dt=updated_dt,
-            type=type,
-            order=order,
             meta_attr=meta_attr,
         )
 
-        comment.additional_properties = d
-        return comment
+        meta.additional_properties = d
+        return meta
 
     @staticmethod
     def get_fields():
         return {
             "uuid": str,
-            "external_system_id": str,
+            "type": FlawMetaType,
+            "embargoed": bool,
             "created_dt": datetime.datetime,
             "updated_dt": datetime.datetime,
-            "type": CommentTypeEnum,
-            "order": int,
-            "meta_attr": CommentMetaAttr,
+            "meta_attr": MetaMetaAttr,
         }
 
     @property
     def additional_keys(self) -> List[str]:
         return list(self.additional_properties.keys())
 
     def __getitem__(self, key: str) -> Any:
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/comment_meta_attr.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/comment_meta_attr.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/cv_ev_5_package_versions.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/cv_ev_5_package_versions.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/cv_ev_5_versions.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/cv_ev_5_versions.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/epss.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/epss.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/erratum.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/erratum.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploit_only_report_data.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploit_only_report_data.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_collect_update_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_collect_update_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_cve_map_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_cve_map_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_cve_map_retrieve_response_200_cves.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_cve_map_retrieve_response_200_cves.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_epss_list_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_epss_list_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_flaw_data_list_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_flaw_data_list_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_data_list_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_data_list_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200_action_required_item.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200_action_required_item.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200_no_action_item.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200_no_action_item.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200_not_relevant_item.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_date_retrieve_response_200_not_relevant_item.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_explanations_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_explanations_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_explanations_retrieve_response_200_explanations_item.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_explanations_retrieve_response_200_explanations_item.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_pending_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_pending_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_pending_retrieve_response_200_pending_actions_item.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_report_pending_retrieve_response_200_pending_actions_item.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_status_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_status_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_supported_products_list_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/exploits_api_v1_supported_products_list_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw.py`

 * *Files 7% similar despite different names*

```diff
@@ -7,18 +7,19 @@
 
 from ..models.affect import Affect
 from ..models.blank_enum import BlankEnum
 from ..models.comment import Comment
 from ..models.cv_ev_5_package_versions import CVEv5PackageVersions
 from ..models.flaw_classification import FlawClassification
 from ..models.flaw_meta_attr import FlawMetaAttr
+from ..models.flaw_reference import FlawReference
+from ..models.flaw_type import FlawType
 from ..models.impact_enum import ImpactEnum
 from ..models.meta import Meta
 from ..models.source_666_enum import Source666Enum
-from ..models.type_824_enum import Type824Enum
 from ..types import UNSET, OSIDBModel, Unset
 
 T = TypeVar("T", bound="Flaw")
 
 
 @attr.s(auto_attribs=True)
 class Flaw(OSIDBModel):
@@ -31,19 +32,20 @@
     trackers: List[str]
     description: str
     affects: List[Affect]
     meta: List[Meta]
     comments: List[Comment]
     meta_attr: FlawMetaAttr
     package_versions: List[CVEv5PackageVersions]
+    references: List[FlawReference]
     embargoed: bool
     created_dt: datetime.datetime
     updated_dt: datetime.datetime
     classification: FlawClassification
-    type: Union[Unset, Type824Enum] = UNSET
+    type: Union[Unset, FlawType] = UNSET
     cve_id: Union[Unset, None, str] = UNSET
     impact: Union[BlankEnum, ImpactEnum, Unset] = UNSET
     component: Union[Unset, str] = UNSET
     summary: Union[Unset, str] = UNSET
     statement: Union[Unset, str] = UNSET
     cwe_id: Union[Unset, str] = UNSET
     unembargo_dt: Union[Unset, None, datetime.datetime] = UNSET
@@ -109,14 +111,24 @@
             for package_versions_item_data in self.package_versions:
                 package_versions_item: Dict[str, Any] = UNSET
                 if not isinstance(package_versions_item_data, Unset):
                     package_versions_item = package_versions_item_data.to_dict()
 
                 package_versions.append(package_versions_item)
 
+        references: List[Dict[str, Any]] = UNSET
+        if not isinstance(self.references, Unset):
+            references = []
+            for references_item_data in self.references:
+                references_item: Dict[str, Any] = UNSET
+                if not isinstance(references_item_data, Unset):
+                    references_item = references_item_data.to_dict()
+
+                references.append(references_item)
+
         embargoed = self.embargoed
         created_dt: str = UNSET
         if not isinstance(self.created_dt, Unset):
             created_dt = self.created_dt.isoformat()
 
         updated_dt: str = UNSET
         if not isinstance(self.updated_dt, Unset):
@@ -125,15 +137,15 @@
         classification: Dict[str, Any] = UNSET
         if not isinstance(self.classification, Unset):
             classification = self.classification.to_dict()
 
         type: Union[Unset, str] = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type824Enum(self.type).value
+            type = FlawType(self.type).value
 
         cve_id = self.cve_id
         impact: Union[Unset, str]
         if isinstance(self.impact, Unset):
             impact = UNSET
         elif isinstance(self.impact, ImpactEnum):
             impact = UNSET
@@ -203,14 +215,16 @@
             field_dict["meta"] = meta
         if comments is not UNSET:
             field_dict["comments"] = comments
         if meta_attr is not UNSET:
             field_dict["meta_attr"] = meta_attr
         if package_versions is not UNSET:
             field_dict["package_versions"] = package_versions
+        if references is not UNSET:
+            field_dict["references"] = references
         if embargoed is not UNSET:
             field_dict["embargoed"] = embargoed
         if created_dt is not UNSET:
             field_dict["created_dt"] = created_dt
         if updated_dt is not UNSET:
             field_dict["updated_dt"] = updated_dt
         if classification is not UNSET:
@@ -325,14 +339,25 @@
                 _temp_package_versions.append(package_versions_item)
             package_versions = (
                 None,
                 json.dumps(_temp_package_versions),
                 "application/json",
             )
 
+        references: Union[Unset, Tuple[None, str, str]] = UNSET
+        if not isinstance(self.references, Unset):
+            _temp_references = []
+            for references_item_data in self.references:
+                references_item: Dict[str, Any] = UNSET
+                if not isinstance(references_item_data, Unset):
+                    references_item = references_item_data.to_dict()
+
+                _temp_references.append(references_item)
+            references = (None, json.dumps(_temp_references), "application/json")
+
         embargoed = (
             self.embargoed
             if self.embargoed is UNSET
             else (None, str(self.embargoed), "text/plain")
         )
         created_dt: str = UNSET
         if not isinstance(self.created_dt, Unset):
@@ -349,15 +374,15 @@
                 json.dumps(self.classification.to_dict()),
                 "application/json",
             )
 
         type: Union[Unset, Tuple[None, str, str]] = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type824Enum(self.type).value
+            type = FlawType(self.type).value
 
         cve_id = (
             self.cve_id
             if self.cve_id is UNSET
             else (None, str(self.cve_id), "text/plain")
         )
         impact: Union[Unset, str]
@@ -480,14 +505,16 @@
             field_dict["meta"] = meta
         if comments is not UNSET:
             field_dict["comments"] = comments
         if meta_attr is not UNSET:
             field_dict["meta_attr"] = meta_attr
         if package_versions is not UNSET:
             field_dict["package_versions"] = package_versions
+        if references is not UNSET:
+            field_dict["references"] = references
         if embargoed is not UNSET:
             field_dict["embargoed"] = embargoed
         if created_dt is not UNSET:
             field_dict["created_dt"] = created_dt
         if updated_dt is not UNSET:
             field_dict["updated_dt"] = updated_dt
         if classification is not UNSET:
@@ -611,14 +638,29 @@
                 else:
                     package_versions_item = CVEv5PackageVersions.from_dict(
                         _package_versions_item
                     )
 
                 package_versions.append(package_versions_item)
 
+        references = []
+        _references = d.pop("references", UNSET)
+        if _references is UNSET:
+            references = UNSET
+        else:
+            for references_item_data in _references or []:
+                _references_item = references_item_data
+                references_item: FlawReference
+                if isinstance(_references_item, Unset):
+                    references_item = UNSET
+                else:
+                    references_item = FlawReference.from_dict(_references_item)
+
+                references.append(references_item)
+
         embargoed = d.pop("embargoed", UNSET)
 
         _created_dt = d.pop("created_dt", UNSET)
         created_dt: datetime.datetime
         if isinstance(_created_dt, Unset):
             created_dt = UNSET
         else:
@@ -635,19 +677,19 @@
         classification: FlawClassification
         if isinstance(_classification, Unset):
             classification = UNSET
         else:
             classification = FlawClassification.from_dict(_classification)
 
         _type = d.pop("type", UNSET)
-        type: Union[Unset, Type824Enum]
+        type: Union[Unset, FlawType]
         if isinstance(_type, Unset):
             type = UNSET
         else:
-            type = Type824Enum(_type)
+            type = FlawType(_type)
 
         cve_id = d.pop("cve_id", UNSET)
 
         def _parse_impact(data: object) -> Union[BlankEnum, ImpactEnum, Unset]:
             if isinstance(data, Unset):
                 return data
             try:
@@ -755,14 +797,15 @@
             trackers=trackers,
             description=description,
             affects=affects,
             meta=meta,
             comments=comments,
             meta_attr=meta_attr,
             package_versions=package_versions,
+            references=references,
             embargoed=embargoed,
             created_dt=created_dt,
             updated_dt=updated_dt,
             classification=classification,
             type=type,
             cve_id=cve_id,
             impact=impact,
@@ -796,19 +839,20 @@
             "trackers": List[str],
             "description": str,
             "affects": List[Affect],
             "meta": List[Meta],
             "comments": List[Comment],
             "meta_attr": FlawMetaAttr,
             "package_versions": List[CVEv5PackageVersions],
+            "references": List[FlawReference],
             "embargoed": bool,
             "created_dt": datetime.datetime,
             "updated_dt": datetime.datetime,
             "classification": FlawClassification,
-            "type": Type824Enum,
+            "type": FlawType,
             "cve_id": str,
             "impact": Union[BlankEnum, ImpactEnum],
             "component": str,
             "summary": str,
             "statement": str,
             "cwe_id": str,
             "unembargo_dt": datetime.datetime,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw_classification.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_classification.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw_meta_attr.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_meta_attr.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw_post.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_post.py`

 * *Files 11% similar despite different names*

```diff
@@ -7,18 +7,19 @@
 
 from ..models.affect import Affect
 from ..models.blank_enum import BlankEnum
 from ..models.comment import Comment
 from ..models.cv_ev_5_package_versions import CVEv5PackageVersions
 from ..models.flaw_post_classification import FlawPostClassification
 from ..models.flaw_post_meta_attr import FlawPostMetaAttr
+from ..models.flaw_reference import FlawReference
+from ..models.flaw_type import FlawType
 from ..models.impact_enum import ImpactEnum
 from ..models.meta import Meta
 from ..models.source_666_enum import Source666Enum
-from ..models.type_824_enum import Type824Enum
 from ..types import UNSET, OSIDBModel, Unset
 
 T = TypeVar("T", bound="FlawPost")
 
 
 @attr.s(auto_attribs=True)
 class FlawPost(OSIDBModel):
@@ -31,18 +32,19 @@
     trackers: List[str]
     description: str
     affects: List[Affect]
     meta: List[Meta]
     comments: List[Comment]
     meta_attr: FlawPostMetaAttr
     package_versions: List[CVEv5PackageVersions]
+    references: List[FlawReference]
     embargoed: bool
     created_dt: datetime.datetime
     classification: FlawPostClassification
-    type: Union[Unset, Type824Enum] = UNSET
+    type: Union[Unset, FlawType] = UNSET
     cve_id: Union[Unset, None, str] = UNSET
     impact: Union[BlankEnum, ImpactEnum, Unset] = UNSET
     component: Union[Unset, str] = UNSET
     summary: Union[Unset, str] = UNSET
     statement: Union[Unset, str] = UNSET
     cwe_id: Union[Unset, str] = UNSET
     unembargo_dt: Union[Unset, None, datetime.datetime] = UNSET
@@ -108,27 +110,37 @@
             for package_versions_item_data in self.package_versions:
                 package_versions_item: Dict[str, Any] = UNSET
                 if not isinstance(package_versions_item_data, Unset):
                     package_versions_item = package_versions_item_data.to_dict()
 
                 package_versions.append(package_versions_item)
 
+        references: List[Dict[str, Any]] = UNSET
+        if not isinstance(self.references, Unset):
+            references = []
+            for references_item_data in self.references:
+                references_item: Dict[str, Any] = UNSET
+                if not isinstance(references_item_data, Unset):
+                    references_item = references_item_data.to_dict()
+
+                references.append(references_item)
+
         embargoed = self.embargoed
         created_dt: str = UNSET
         if not isinstance(self.created_dt, Unset):
             created_dt = self.created_dt.isoformat()
 
         classification: Dict[str, Any] = UNSET
         if not isinstance(self.classification, Unset):
             classification = self.classification.to_dict()
 
         type: Union[Unset, str] = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type824Enum(self.type).value
+            type = FlawType(self.type).value
 
         cve_id = self.cve_id
         impact: Union[Unset, str]
         if isinstance(self.impact, Unset):
             impact = UNSET
         elif isinstance(self.impact, ImpactEnum):
             impact = UNSET
@@ -198,14 +210,16 @@
             field_dict["meta"] = meta
         if comments is not UNSET:
             field_dict["comments"] = comments
         if meta_attr is not UNSET:
             field_dict["meta_attr"] = meta_attr
         if package_versions is not UNSET:
             field_dict["package_versions"] = package_versions
+        if references is not UNSET:
+            field_dict["references"] = references
         if embargoed is not UNSET:
             field_dict["embargoed"] = embargoed
         if created_dt is not UNSET:
             field_dict["created_dt"] = created_dt
         if classification is not UNSET:
             field_dict["classification"] = classification
         if type is not UNSET:
@@ -318,14 +332,25 @@
                 _temp_package_versions.append(package_versions_item)
             package_versions = (
                 None,
                 json.dumps(_temp_package_versions),
                 "application/json",
             )
 
+        references: Union[Unset, Tuple[None, str, str]] = UNSET
+        if not isinstance(self.references, Unset):
+            _temp_references = []
+            for references_item_data in self.references:
+                references_item: Dict[str, Any] = UNSET
+                if not isinstance(references_item_data, Unset):
+                    references_item = references_item_data.to_dict()
+
+                _temp_references.append(references_item)
+            references = (None, json.dumps(_temp_references), "application/json")
+
         embargoed = (
             self.embargoed
             if self.embargoed is UNSET
             else (None, str(self.embargoed), "text/plain")
         )
         created_dt: str = UNSET
         if not isinstance(self.created_dt, Unset):
@@ -338,15 +363,15 @@
                 json.dumps(self.classification.to_dict()),
                 "application/json",
             )
 
         type: Union[Unset, Tuple[None, str, str]] = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type824Enum(self.type).value
+            type = FlawType(self.type).value
 
         cve_id = (
             self.cve_id
             if self.cve_id is UNSET
             else (None, str(self.cve_id), "text/plain")
         )
         impact: Union[Unset, str]
@@ -469,14 +494,16 @@
             field_dict["meta"] = meta
         if comments is not UNSET:
             field_dict["comments"] = comments
         if meta_attr is not UNSET:
             field_dict["meta_attr"] = meta_attr
         if package_versions is not UNSET:
             field_dict["package_versions"] = package_versions
+        if references is not UNSET:
+            field_dict["references"] = references
         if embargoed is not UNSET:
             field_dict["embargoed"] = embargoed
         if created_dt is not UNSET:
             field_dict["created_dt"] = created_dt
         if classification is not UNSET:
             field_dict["classification"] = classification
         if type is not UNSET:
@@ -598,14 +625,29 @@
                 else:
                     package_versions_item = CVEv5PackageVersions.from_dict(
                         _package_versions_item
                     )
 
                 package_versions.append(package_versions_item)
 
+        references = []
+        _references = d.pop("references", UNSET)
+        if _references is UNSET:
+            references = UNSET
+        else:
+            for references_item_data in _references or []:
+                _references_item = references_item_data
+                references_item: FlawReference
+                if isinstance(_references_item, Unset):
+                    references_item = UNSET
+                else:
+                    references_item = FlawReference.from_dict(_references_item)
+
+                references.append(references_item)
+
         embargoed = d.pop("embargoed", UNSET)
 
         _created_dt = d.pop("created_dt", UNSET)
         created_dt: datetime.datetime
         if isinstance(_created_dt, Unset):
             created_dt = UNSET
         else:
@@ -615,19 +657,19 @@
         classification: FlawPostClassification
         if isinstance(_classification, Unset):
             classification = UNSET
         else:
             classification = FlawPostClassification.from_dict(_classification)
 
         _type = d.pop("type", UNSET)
-        type: Union[Unset, Type824Enum]
+        type: Union[Unset, FlawType]
         if isinstance(_type, Unset):
             type = UNSET
         else:
-            type = Type824Enum(_type)
+            type = FlawType(_type)
 
         cve_id = d.pop("cve_id", UNSET)
 
         def _parse_impact(data: object) -> Union[BlankEnum, ImpactEnum, Unset]:
             if isinstance(data, Unset):
                 return data
             try:
@@ -735,14 +777,15 @@
             trackers=trackers,
             description=description,
             affects=affects,
             meta=meta,
             comments=comments,
             meta_attr=meta_attr,
             package_versions=package_versions,
+            references=references,
             embargoed=embargoed,
             created_dt=created_dt,
             classification=classification,
             type=type,
             cve_id=cve_id,
             impact=impact,
             component=component,
@@ -775,18 +818,19 @@
             "trackers": List[str],
             "description": str,
             "affects": List[Affect],
             "meta": List[Meta],
             "comments": List[Comment],
             "meta_attr": FlawPostMetaAttr,
             "package_versions": List[CVEv5PackageVersions],
+            "references": List[FlawReference],
             "embargoed": bool,
             "created_dt": datetime.datetime,
             "classification": FlawPostClassification,
-            "type": Type824Enum,
+            "type": FlawType,
             "cve_id": str,
             "impact": Union[BlankEnum, ImpactEnum],
             "component": str,
             "summary": str,
             "statement": str,
             "cwe_id": str,
             "unembargo_dt": datetime.datetime,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw_post_classification.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_post_classification.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw_post_meta_attr.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_post_meta_attr.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/flaw_report_data.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/flaw_report_data.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/jira_comment.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/jira_comment.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/jira_issue.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/jira_issue.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/jira_issue_fields.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_healthy_retrieve_response_200.py`

 * *Files 17% similar despite different names*

```diff
@@ -1,99 +1,83 @@
-from typing import Any, Dict, List, Type, TypeVar
+import datetime
+from typing import Any, Dict, List, Type, TypeVar, Union
 
 import attr
+from dateutil.parser import isoparse
 
-from ..models.jira_issue_type import JiraIssueType
-from ..models.jira_user import JiraUser
 from ..types import UNSET, OSIDBModel, Unset
 
-T = TypeVar("T", bound="JiraIssueFields")
+T = TypeVar("T", bound="TaskmanHealthyRetrieveResponse200")
 
 
 @attr.s(auto_attribs=True)
-class JiraIssueFields(OSIDBModel):
+class TaskmanHealthyRetrieveResponse200(OSIDBModel):
     """ """
 
-    issuetype: JiraIssueType
-    summary: str
-    description: str
-    assignee: JiraUser
-    customfield_12311140: str
+    dt: Union[Unset, datetime.datetime] = UNSET
+    env: Union[Unset, str] = UNSET
+    revision: Union[Unset, str] = UNSET
+    version: Union[Unset, str] = UNSET
     additional_properties: Dict[str, Any] = attr.ib(init=False, factory=dict)
 
     def to_dict(self) -> Dict[str, Any]:
-        issuetype: Dict[str, Any] = UNSET
-        if not isinstance(self.issuetype, Unset):
-            issuetype = self.issuetype.to_dict()
-
-        summary = self.summary
-        description = self.description
-        assignee: Dict[str, Any] = UNSET
-        if not isinstance(self.assignee, Unset):
-            assignee = self.assignee.to_dict()
-
-        customfield_12311140 = self.customfield_12311140
+        dt: Union[Unset, str] = UNSET
+        if not isinstance(self.dt, Unset):
+            dt = self.dt.isoformat()
+
+        env = self.env
+        revision = self.revision
+        version = self.version
 
         field_dict: Dict[str, Any] = {}
         field_dict.update(self.additional_properties)
-        if issuetype is not UNSET:
-            field_dict["issuetype"] = issuetype
-        if summary is not UNSET:
-            field_dict["summary"] = summary
-        if description is not UNSET:
-            field_dict["description"] = description
-        if assignee is not UNSET:
-            field_dict["assignee"] = assignee
-        if customfield_12311140 is not UNSET:
-            field_dict["customfield_12311140"] = customfield_12311140
+        if dt is not UNSET:
+            field_dict["dt"] = dt
+        if env is not UNSET:
+            field_dict["env"] = env
+        if revision is not UNSET:
+            field_dict["revision"] = revision
+        if version is not UNSET:
+            field_dict["version"] = version
 
         return field_dict
 
     @classmethod
     def from_dict(cls: Type[T], src_dict: Dict[str, Any]) -> T:
         d = src_dict.copy()
-        _issuetype = d.pop("issuetype", UNSET)
-        issuetype: JiraIssueType
-        if isinstance(_issuetype, Unset):
-            issuetype = UNSET
+        _dt = d.pop("dt", UNSET)
+        dt: Union[Unset, datetime.datetime]
+        if isinstance(_dt, Unset):
+            dt = UNSET
         else:
-            issuetype = JiraIssueType.from_dict(_issuetype)
-
-        summary = d.pop("summary", UNSET)
+            dt = isoparse(_dt)
 
-        description = d.pop("description", UNSET)
+        env = d.pop("env", UNSET)
 
-        _assignee = d.pop("assignee", UNSET)
-        assignee: JiraUser
-        if isinstance(_assignee, Unset):
-            assignee = UNSET
-        else:
-            assignee = JiraUser.from_dict(_assignee)
+        revision = d.pop("revision", UNSET)
 
-        customfield_12311140 = d.pop("customfield_12311140", UNSET)
+        version = d.pop("version", UNSET)
 
-        jira_issue_fields = cls(
-            issuetype=issuetype,
-            summary=summary,
-            description=description,
-            assignee=assignee,
-            customfield_12311140=customfield_12311140,
+        taskman_healthy_retrieve_response_200 = cls(
+            dt=dt,
+            env=env,
+            revision=revision,
+            version=version,
         )
 
-        jira_issue_fields.additional_properties = d
-        return jira_issue_fields
+        taskman_healthy_retrieve_response_200.additional_properties = d
+        return taskman_healthy_retrieve_response_200
 
     @staticmethod
     def get_fields():
         return {
-            "issuetype": JiraIssueType,
-            "summary": str,
-            "description": str,
-            "assignee": JiraUser,
-            "customfield_12311140": str,
+            "dt": datetime.datetime,
+            "env": str,
+            "revision": str,
+            "version": str,
         }
 
     @property
     def additional_keys(self) -> List[str]:
         return list(self.additional_properties.keys())
 
     def __getitem__(self, key: str) -> Any:
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/jira_issue_query_result.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/jira_issue_query_result.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/jira_issue_type.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/jira_issue_type.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/jira_user.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/jira_user.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/meta.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/comment.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,125 +1,133 @@
 import datetime
 from typing import Any, Dict, List, Type, TypeVar, Union
 
 import attr
 from dateutil.parser import isoparse
 
-from ..models.meta_meta_attr import MetaMetaAttr
-from ..models.meta_type_enum import MetaTypeEnum
+from ..models.comment_meta_attr import CommentMetaAttr
+from ..models.flaw_comment_type import FlawCommentType
 from ..types import UNSET, OSIDBModel, Unset
 
-T = TypeVar("T", bound="Meta")
+T = TypeVar("T", bound="Comment")
 
 
 @attr.s(auto_attribs=True)
-class Meta(OSIDBModel):
-    """FlawMeta serializer"""
+class Comment(OSIDBModel):
+    """FlawComment serializer for use by FlawSerializer"""
 
     uuid: str
-    type: MetaTypeEnum
-    embargoed: bool
     created_dt: datetime.datetime
     updated_dt: datetime.datetime
-    meta_attr: Union[Unset, MetaMetaAttr] = UNSET
+    type: Union[Unset, FlawCommentType] = UNSET
+    external_system_id: Union[Unset, str] = UNSET
+    order: Union[Unset, None, int] = UNSET
+    meta_attr: Union[Unset, CommentMetaAttr] = UNSET
     additional_properties: Dict[str, Any] = attr.ib(init=False, factory=dict)
 
     def to_dict(self) -> Dict[str, Any]:
         uuid = self.uuid
-        type: str = UNSET
-        if not isinstance(self.type, Unset):
-
-            type = MetaTypeEnum(self.type).value
-
-        embargoed = self.embargoed
         created_dt: str = UNSET
         if not isinstance(self.created_dt, Unset):
             created_dt = self.created_dt.isoformat()
 
         updated_dt: str = UNSET
         if not isinstance(self.updated_dt, Unset):
             updated_dt = self.updated_dt.isoformat()
 
+        type: Union[Unset, str] = UNSET
+        if not isinstance(self.type, Unset):
+
+            type = FlawCommentType(self.type).value
+
+        external_system_id = self.external_system_id
+        order = self.order
         meta_attr: Union[Unset, Dict[str, Any]] = UNSET
         if not isinstance(self.meta_attr, Unset):
             meta_attr = self.meta_attr.to_dict()
 
         field_dict: Dict[str, Any] = {}
         field_dict.update(self.additional_properties)
         if uuid is not UNSET:
             field_dict["uuid"] = uuid
-        if type is not UNSET:
-            field_dict["type"] = type
-        if embargoed is not UNSET:
-            field_dict["embargoed"] = embargoed
         if created_dt is not UNSET:
             field_dict["created_dt"] = created_dt
         if updated_dt is not UNSET:
             field_dict["updated_dt"] = updated_dt
+        if type is not UNSET:
+            field_dict["type"] = type
+        if external_system_id is not UNSET:
+            field_dict["external_system_id"] = external_system_id
+        if order is not UNSET:
+            field_dict["order"] = order
         if meta_attr is not UNSET:
             field_dict["meta_attr"] = meta_attr
 
         return field_dict
 
     @classmethod
     def from_dict(cls: Type[T], src_dict: Dict[str, Any]) -> T:
         d = src_dict.copy()
         uuid = d.pop("uuid", UNSET)
 
-        _type = d.pop("type", UNSET)
-        type: MetaTypeEnum
-        if isinstance(_type, Unset):
-            type = UNSET
-        else:
-            type = MetaTypeEnum(_type)
-
-        embargoed = d.pop("embargoed", UNSET)
-
         _created_dt = d.pop("created_dt", UNSET)
         created_dt: datetime.datetime
         if isinstance(_created_dt, Unset):
             created_dt = UNSET
         else:
             created_dt = isoparse(_created_dt)
 
         _updated_dt = d.pop("updated_dt", UNSET)
         updated_dt: datetime.datetime
         if isinstance(_updated_dt, Unset):
             updated_dt = UNSET
         else:
             updated_dt = isoparse(_updated_dt)
 
+        _type = d.pop("type", UNSET)
+        type: Union[Unset, FlawCommentType]
+        if isinstance(_type, Unset):
+            type = UNSET
+        else:
+            type = FlawCommentType(_type)
+
+        external_system_id = d.pop("external_system_id", UNSET)
+
+        order = d.pop("order", UNSET)
+
         _meta_attr = d.pop("meta_attr", UNSET)
-        meta_attr: Union[Unset, MetaMetaAttr]
+        meta_attr: Union[Unset, CommentMetaAttr]
         if isinstance(_meta_attr, Unset):
             meta_attr = UNSET
         else:
-            meta_attr = MetaMetaAttr.from_dict(_meta_attr)
+            meta_attr = CommentMetaAttr.from_dict(_meta_attr)
 
-        meta = cls(
+        comment = cls(
             uuid=uuid,
-            type=type,
-            embargoed=embargoed,
             created_dt=created_dt,
             updated_dt=updated_dt,
+            type=type,
+            external_system_id=external_system_id,
+            order=order,
             meta_attr=meta_attr,
         )
 
-        meta.additional_properties = d
-        return meta
+        comment.additional_properties = d
+        return comment
 
     @staticmethod
     def get_fields():
         return {
             "uuid": str,
-            "type": MetaTypeEnum,
-            "embargoed": bool,
             "created_dt": datetime.datetime,
             "updated_dt": datetime.datetime,
-            "meta_attr": MetaMetaAttr,
+            "type": FlawCommentType,
+            "external_system_id": str,
+            "order": int,
+            "meta_attr": CommentMetaAttr,
         }
 
     @property
     def additional_keys(self) -> List[str]:
         return list(self.additional_properties.keys())
 
     def __getitem__(self, key: str) -> Any:
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/meta_meta_attr.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/meta_meta_attr.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_create_response_201.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_create_response_201.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,20 +1,20 @@
 import datetime
 from typing import Any, Dict, List, Optional, Type, TypeVar, Union
 
 import attr
 from dateutil.parser import isoparse
 
 from ..models.affect_meta_attr import AffectMetaAttr
+from ..models.affect_type import AffectType
 from ..models.affectedness_enum import AffectednessEnum
 from ..models.blank_enum import BlankEnum
 from ..models.impact_enum import ImpactEnum
 from ..models.resolution_enum import ResolutionEnum
 from ..models.tracker import Tracker
-from ..models.type_5b2_enum import Type5B2Enum
 from ..types import UNSET, OSIDBModel, Unset
 
 T = TypeVar("T", bound="OsidbApiV1AffectsCreateResponse201")
 
 
 @attr.s(auto_attribs=True)
 class OsidbApiV1AffectsCreateResponse201(OSIDBModel):
@@ -26,15 +26,15 @@
     trackers: List[Tracker]
     meta_attr: AffectMetaAttr
     delegated_resolution: str
     embargoed: bool
     created_dt: datetime.datetime
     updated_dt: datetime.datetime
     flaw: Optional[str]
-    type: Union[Unset, Type5B2Enum] = UNSET
+    type: Union[Unset, AffectType] = UNSET
     affectedness: Union[AffectednessEnum, BlankEnum, Unset] = UNSET
     resolution: Union[BlankEnum, ResolutionEnum, Unset] = UNSET
     impact: Union[BlankEnum, ImpactEnum, Unset] = UNSET
     cvss2: Union[Unset, str] = UNSET
     cvss2_score: Union[Unset, None, float] = UNSET
     cvss3: Union[Unset, str] = UNSET
     cvss3_score: Union[Unset, None, float] = UNSET
@@ -72,15 +72,15 @@
         if not isinstance(self.updated_dt, Unset):
             updated_dt = self.updated_dt.isoformat()
 
         flaw = self.flaw
         type: Union[Unset, str] = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type5B2Enum(self.type).value
+            type = AffectType(self.type).value
 
         affectedness: Union[Unset, str]
         if isinstance(self.affectedness, Unset):
             affectedness = UNSET
         elif isinstance(self.affectedness, AffectednessEnum):
             affectedness = UNSET
             if not isinstance(self.affectedness, Unset):
@@ -232,19 +232,19 @@
             updated_dt = UNSET
         else:
             updated_dt = isoparse(_updated_dt)
 
         flaw = d.pop("flaw", UNSET)
 
         _type = d.pop("type", UNSET)
-        type: Union[Unset, Type5B2Enum]
+        type: Union[Unset, AffectType]
         if isinstance(_type, Unset):
             type = UNSET
         else:
-            type = Type5B2Enum(_type)
+            type = AffectType(_type)
 
         def _parse_affectedness(
             data: object,
         ) -> Union[AffectednessEnum, BlankEnum, Unset]:
             if isinstance(data, Unset):
                 return data
             try:
@@ -389,15 +389,15 @@
             "trackers": List[Tracker],
             "meta_attr": AffectMetaAttr,
             "delegated_resolution": str,
             "embargoed": bool,
             "created_dt": datetime.datetime,
             "updated_dt": datetime.datetime,
             "flaw": str,
-            "type": Type5B2Enum,
+            "type": AffectType,
             "affectedness": Union[AffectednessEnum, BlankEnum],
             "resolution": Union[BlankEnum, ResolutionEnum],
             "impact": Union[BlankEnum, ImpactEnum],
             "cvss2": str,
             "cvss2_score": float,
             "cvss3": str,
             "cvss3_score": float,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_destroy_response_204.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_destroy_response_204.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_flaw_source.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_flaw_source.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_order_item.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_order_item.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_update_response_200.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,40 +1,40 @@
 import datetime
 from typing import Any, Dict, List, Optional, Type, TypeVar, Union
 
 import attr
 from dateutil.parser import isoparse
 
 from ..models.affect_meta_attr import AffectMetaAttr
+from ..models.affect_type import AffectType
 from ..models.affectedness_enum import AffectednessEnum
 from ..models.blank_enum import BlankEnum
 from ..models.impact_enum import ImpactEnum
 from ..models.resolution_enum import ResolutionEnum
 from ..models.tracker import Tracker
-from ..models.type_5b2_enum import Type5B2Enum
 from ..types import UNSET, OSIDBModel, Unset
 
-T = TypeVar("T", bound="OsidbApiV1AffectsRetrieveResponse200")
+T = TypeVar("T", bound="OsidbApiV1AffectsUpdateResponse200")
 
 
 @attr.s(auto_attribs=True)
-class OsidbApiV1AffectsRetrieveResponse200(OSIDBModel):
+class OsidbApiV1AffectsUpdateResponse200(OSIDBModel):
     """ """
 
     uuid: str
     ps_module: str
     ps_component: str
     trackers: List[Tracker]
     meta_attr: AffectMetaAttr
     delegated_resolution: str
     embargoed: bool
     created_dt: datetime.datetime
     updated_dt: datetime.datetime
     flaw: Optional[str]
-    type: Union[Unset, Type5B2Enum] = UNSET
+    type: Union[Unset, AffectType] = UNSET
     affectedness: Union[AffectednessEnum, BlankEnum, Unset] = UNSET
     resolution: Union[BlankEnum, ResolutionEnum, Unset] = UNSET
     impact: Union[BlankEnum, ImpactEnum, Unset] = UNSET
     cvss2: Union[Unset, str] = UNSET
     cvss2_score: Union[Unset, None, float] = UNSET
     cvss3: Union[Unset, str] = UNSET
     cvss3_score: Union[Unset, None, float] = UNSET
@@ -72,15 +72,15 @@
         if not isinstance(self.updated_dt, Unset):
             updated_dt = self.updated_dt.isoformat()
 
         flaw = self.flaw
         type: Union[Unset, str] = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type5B2Enum(self.type).value
+            type = AffectType(self.type).value
 
         affectedness: Union[Unset, str]
         if isinstance(self.affectedness, Unset):
             affectedness = UNSET
         elif isinstance(self.affectedness, AffectednessEnum):
             affectedness = UNSET
             if not isinstance(self.affectedness, Unset):
@@ -232,19 +232,19 @@
             updated_dt = UNSET
         else:
             updated_dt = isoparse(_updated_dt)
 
         flaw = d.pop("flaw", UNSET)
 
         _type = d.pop("type", UNSET)
-        type: Union[Unset, Type5B2Enum]
+        type: Union[Unset, AffectType]
         if isinstance(_type, Unset):
             type = UNSET
         else:
-            type = Type5B2Enum(_type)
+            type = AffectType(_type)
 
         def _parse_affectedness(
             data: object,
         ) -> Union[AffectednessEnum, BlankEnum, Unset]:
             if isinstance(data, Unset):
                 return data
             try:
@@ -348,15 +348,15 @@
 
         env = d.pop("env", UNSET)
 
         revision = d.pop("revision", UNSET)
 
         version = d.pop("version", UNSET)
 
-        osidb_api_v1_affects_retrieve_response_200 = cls(
+        osidb_api_v1_affects_update_response_200 = cls(
             uuid=uuid,
             ps_module=ps_module,
             ps_component=ps_component,
             trackers=trackers,
             meta_attr=meta_attr,
             delegated_resolution=delegated_resolution,
             embargoed=embargoed,
@@ -373,31 +373,31 @@
             cvss3_score=cvss3_score,
             dt=dt,
             env=env,
             revision=revision,
             version=version,
         )
 
-        osidb_api_v1_affects_retrieve_response_200.additional_properties = d
-        return osidb_api_v1_affects_retrieve_response_200
+        osidb_api_v1_affects_update_response_200.additional_properties = d
+        return osidb_api_v1_affects_update_response_200
 
     @staticmethod
     def get_fields():
         return {
             "uuid": str,
             "ps_module": str,
             "ps_component": str,
             "trackers": List[Tracker],
             "meta_attr": AffectMetaAttr,
             "delegated_resolution": str,
             "embargoed": bool,
             "created_dt": datetime.datetime,
             "updated_dt": datetime.datetime,
             "flaw": str,
-            "type": Type5B2Enum,
+            "type": AffectType,
             "affectedness": Union[AffectednessEnum, BlankEnum],
             "resolution": Union[BlankEnum, ResolutionEnum],
             "impact": Union[BlankEnum, ImpactEnum],
             "cvss2": str,
             "cvss2_score": float,
             "cvss3": str,
             "cvss3_score": float,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_update_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_retrieve_response_200.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,40 +1,40 @@
 import datetime
 from typing import Any, Dict, List, Optional, Type, TypeVar, Union
 
 import attr
 from dateutil.parser import isoparse
 
 from ..models.affect_meta_attr import AffectMetaAttr
+from ..models.affect_type import AffectType
 from ..models.affectedness_enum import AffectednessEnum
 from ..models.blank_enum import BlankEnum
 from ..models.impact_enum import ImpactEnum
 from ..models.resolution_enum import ResolutionEnum
 from ..models.tracker import Tracker
-from ..models.type_5b2_enum import Type5B2Enum
 from ..types import UNSET, OSIDBModel, Unset
 
-T = TypeVar("T", bound="OsidbApiV1AffectsUpdateResponse200")
+T = TypeVar("T", bound="OsidbApiV1AffectsRetrieveResponse200")
 
 
 @attr.s(auto_attribs=True)
-class OsidbApiV1AffectsUpdateResponse200(OSIDBModel):
+class OsidbApiV1AffectsRetrieveResponse200(OSIDBModel):
     """ """
 
     uuid: str
     ps_module: str
     ps_component: str
     trackers: List[Tracker]
     meta_attr: AffectMetaAttr
     delegated_resolution: str
     embargoed: bool
     created_dt: datetime.datetime
     updated_dt: datetime.datetime
     flaw: Optional[str]
-    type: Union[Unset, Type5B2Enum] = UNSET
+    type: Union[Unset, AffectType] = UNSET
     affectedness: Union[AffectednessEnum, BlankEnum, Unset] = UNSET
     resolution: Union[BlankEnum, ResolutionEnum, Unset] = UNSET
     impact: Union[BlankEnum, ImpactEnum, Unset] = UNSET
     cvss2: Union[Unset, str] = UNSET
     cvss2_score: Union[Unset, None, float] = UNSET
     cvss3: Union[Unset, str] = UNSET
     cvss3_score: Union[Unset, None, float] = UNSET
@@ -72,15 +72,15 @@
         if not isinstance(self.updated_dt, Unset):
             updated_dt = self.updated_dt.isoformat()
 
         flaw = self.flaw
         type: Union[Unset, str] = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type5B2Enum(self.type).value
+            type = AffectType(self.type).value
 
         affectedness: Union[Unset, str]
         if isinstance(self.affectedness, Unset):
             affectedness = UNSET
         elif isinstance(self.affectedness, AffectednessEnum):
             affectedness = UNSET
             if not isinstance(self.affectedness, Unset):
@@ -232,19 +232,19 @@
             updated_dt = UNSET
         else:
             updated_dt = isoparse(_updated_dt)
 
         flaw = d.pop("flaw", UNSET)
 
         _type = d.pop("type", UNSET)
-        type: Union[Unset, Type5B2Enum]
+        type: Union[Unset, AffectType]
         if isinstance(_type, Unset):
             type = UNSET
         else:
-            type = Type5B2Enum(_type)
+            type = AffectType(_type)
 
         def _parse_affectedness(
             data: object,
         ) -> Union[AffectednessEnum, BlankEnum, Unset]:
             if isinstance(data, Unset):
                 return data
             try:
@@ -348,15 +348,15 @@
 
         env = d.pop("env", UNSET)
 
         revision = d.pop("revision", UNSET)
 
         version = d.pop("version", UNSET)
 
-        osidb_api_v1_affects_update_response_200 = cls(
+        osidb_api_v1_affects_retrieve_response_200 = cls(
             uuid=uuid,
             ps_module=ps_module,
             ps_component=ps_component,
             trackers=trackers,
             meta_attr=meta_attr,
             delegated_resolution=delegated_resolution,
             embargoed=embargoed,
@@ -373,31 +373,31 @@
             cvss3_score=cvss3_score,
             dt=dt,
             env=env,
             revision=revision,
             version=version,
         )
 
-        osidb_api_v1_affects_update_response_200.additional_properties = d
-        return osidb_api_v1_affects_update_response_200
+        osidb_api_v1_affects_retrieve_response_200.additional_properties = d
+        return osidb_api_v1_affects_retrieve_response_200
 
     @staticmethod
     def get_fields():
         return {
             "uuid": str,
             "ps_module": str,
             "ps_component": str,
             "trackers": List[Tracker],
             "meta_attr": AffectMetaAttr,
             "delegated_resolution": str,
             "embargoed": bool,
             "created_dt": datetime.datetime,
             "updated_dt": datetime.datetime,
             "flaw": str,
-            "type": Type5B2Enum,
+            "type": AffectType,
             "affectedness": Union[AffectednessEnum, BlankEnum],
             "resolution": Union[BlankEnum, ResolutionEnum],
             "impact": Union[BlankEnum, ImpactEnum],
             "cvss2": str,
             "cvss2_score": float,
             "cvss3": str,
             "cvss3_score": float,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_create_response_201.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_update_response_200.py`

 * *Files 12% similar despite different names*

```diff
@@ -6,43 +6,45 @@
 
 from ..models.affect import Affect
 from ..models.blank_enum import BlankEnum
 from ..models.comment import Comment
 from ..models.cv_ev_5_package_versions import CVEv5PackageVersions
 from ..models.flaw_classification import FlawClassification
 from ..models.flaw_meta_attr import FlawMetaAttr
+from ..models.flaw_reference import FlawReference
+from ..models.flaw_type import FlawType
 from ..models.impact_enum import ImpactEnum
 from ..models.meta import Meta
 from ..models.source_666_enum import Source666Enum
-from ..models.type_824_enum import Type824Enum
 from ..types import UNSET, OSIDBModel, Unset
 
-T = TypeVar("T", bound="OsidbApiV1FlawsCreateResponse201")
+T = TypeVar("T", bound="OsidbApiV1FlawsUpdateResponse200")
 
 
 @attr.s(auto_attribs=True)
-class OsidbApiV1FlawsCreateResponse201(OSIDBModel):
+class OsidbApiV1FlawsUpdateResponse200(OSIDBModel):
     """ """
 
     uuid: str
     state: str
     resolution: str
     title: str
     trackers: List[str]
     description: str
     affects: List[Affect]
     meta: List[Meta]
     comments: List[Comment]
     meta_attr: FlawMetaAttr
     package_versions: List[CVEv5PackageVersions]
+    references: List[FlawReference]
     embargoed: bool
     created_dt: datetime.datetime
     updated_dt: datetime.datetime
     classification: FlawClassification
-    type: Union[Unset, Type824Enum] = UNSET
+    type: Union[Unset, FlawType] = UNSET
     cve_id: Union[Unset, None, str] = UNSET
     impact: Union[BlankEnum, ImpactEnum, Unset] = UNSET
     component: Union[Unset, str] = UNSET
     summary: Union[Unset, str] = UNSET
     statement: Union[Unset, str] = UNSET
     cwe_id: Union[Unset, str] = UNSET
     unembargo_dt: Union[Unset, None, datetime.datetime] = UNSET
@@ -112,14 +114,24 @@
             for package_versions_item_data in self.package_versions:
                 package_versions_item: Dict[str, Any] = UNSET
                 if not isinstance(package_versions_item_data, Unset):
                     package_versions_item = package_versions_item_data.to_dict()
 
                 package_versions.append(package_versions_item)
 
+        references: List[Dict[str, Any]] = UNSET
+        if not isinstance(self.references, Unset):
+            references = []
+            for references_item_data in self.references:
+                references_item: Dict[str, Any] = UNSET
+                if not isinstance(references_item_data, Unset):
+                    references_item = references_item_data.to_dict()
+
+                references.append(references_item)
+
         embargoed = self.embargoed
         created_dt: str = UNSET
         if not isinstance(self.created_dt, Unset):
             created_dt = self.created_dt.isoformat()
 
         updated_dt: str = UNSET
         if not isinstance(self.updated_dt, Unset):
@@ -128,15 +140,15 @@
         classification: Dict[str, Any] = UNSET
         if not isinstance(self.classification, Unset):
             classification = self.classification.to_dict()
 
         type: Union[Unset, str] = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type824Enum(self.type).value
+            type = FlawType(self.type).value
 
         cve_id = self.cve_id
         impact: Union[Unset, str]
         if isinstance(self.impact, Unset):
             impact = UNSET
         elif isinstance(self.impact, ImpactEnum):
             impact = UNSET
@@ -213,14 +225,16 @@
             field_dict["meta"] = meta
         if comments is not UNSET:
             field_dict["comments"] = comments
         if meta_attr is not UNSET:
             field_dict["meta_attr"] = meta_attr
         if package_versions is not UNSET:
             field_dict["package_versions"] = package_versions
+        if references is not UNSET:
+            field_dict["references"] = references
         if embargoed is not UNSET:
             field_dict["embargoed"] = embargoed
         if created_dt is not UNSET:
             field_dict["created_dt"] = created_dt
         if updated_dt is not UNSET:
             field_dict["updated_dt"] = updated_dt
         if classification is not UNSET:
@@ -352,14 +366,29 @@
                 else:
                     package_versions_item = CVEv5PackageVersions.from_dict(
                         _package_versions_item
                     )
 
                 package_versions.append(package_versions_item)
 
+        references = []
+        _references = d.pop("references", UNSET)
+        if _references is UNSET:
+            references = UNSET
+        else:
+            for references_item_data in _references or []:
+                _references_item = references_item_data
+                references_item: FlawReference
+                if isinstance(_references_item, Unset):
+                    references_item = UNSET
+                else:
+                    references_item = FlawReference.from_dict(_references_item)
+
+                references.append(references_item)
+
         embargoed = d.pop("embargoed", UNSET)
 
         _created_dt = d.pop("created_dt", UNSET)
         created_dt: datetime.datetime
         if isinstance(_created_dt, Unset):
             created_dt = UNSET
         else:
@@ -376,19 +405,19 @@
         classification: FlawClassification
         if isinstance(_classification, Unset):
             classification = UNSET
         else:
             classification = FlawClassification.from_dict(_classification)
 
         _type = d.pop("type", UNSET)
-        type: Union[Unset, Type824Enum]
+        type: Union[Unset, FlawType]
         if isinstance(_type, Unset):
             type = UNSET
         else:
-            type = Type824Enum(_type)
+            type = FlawType(_type)
 
         cve_id = d.pop("cve_id", UNSET)
 
         def _parse_impact(data: object) -> Union[BlankEnum, ImpactEnum, Unset]:
             if isinstance(data, Unset):
                 return data
             try:
@@ -497,26 +526,27 @@
 
         env = d.pop("env", UNSET)
 
         revision = d.pop("revision", UNSET)
 
         version = d.pop("version", UNSET)
 
-        osidb_api_v1_flaws_create_response_201 = cls(
+        osidb_api_v1_flaws_update_response_200 = cls(
             uuid=uuid,
             state=state,
             resolution=resolution,
             title=title,
             trackers=trackers,
             description=description,
             affects=affects,
             meta=meta,
             comments=comments,
             meta_attr=meta_attr,
             package_versions=package_versions,
+            references=references,
             embargoed=embargoed,
             created_dt=created_dt,
             updated_dt=updated_dt,
             classification=classification,
             type=type,
             cve_id=cve_id,
             impact=impact,
@@ -537,16 +567,16 @@
             is_major_incident=is_major_incident,
             dt=dt,
             env=env,
             revision=revision,
             version=version,
         )
 
-        osidb_api_v1_flaws_create_response_201.additional_properties = d
-        return osidb_api_v1_flaws_create_response_201
+        osidb_api_v1_flaws_update_response_200.additional_properties = d
+        return osidb_api_v1_flaws_update_response_200
 
     @staticmethod
     def get_fields():
         return {
             "uuid": str,
             "state": str,
             "resolution": str,
@@ -554,19 +584,20 @@
             "trackers": List[str],
             "description": str,
             "affects": List[Affect],
             "meta": List[Meta],
             "comments": List[Comment],
             "meta_attr": FlawMetaAttr,
             "package_versions": List[CVEv5PackageVersions],
+            "references": List[FlawReference],
             "embargoed": bool,
             "created_dt": datetime.datetime,
             "updated_dt": datetime.datetime,
             "classification": FlawClassification,
-            "type": Type824Enum,
+            "type": FlawType,
             "cve_id": str,
             "impact": Union[BlankEnum, ImpactEnum],
             "component": str,
             "summary": str,
             "statement": str,
             "cwe_id": str,
             "unembargo_dt": datetime.datetime,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_order_item.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_order_item.py`

 * *Files 6% similar despite different names*

```diff
@@ -9,53 +9,55 @@
     VALUE_4 = "-affects__cvss3"
     VALUE_5 = "-affects__cvss3_score"
     VALUE_6 = "-affects__impact"
     VALUE_7 = "-affects__ps_component"
     VALUE_8 = "-affects__ps_module"
     VALUE_9 = "-affects__resolution"
     VALUE_10 = "-affects__trackers__created_dt"
-    VALUE_11 = "-affects__trackers__external_system_id"
-    VALUE_12 = "-affects__trackers__ps_update_stream"
-    VALUE_13 = "-affects__trackers__resolution"
-    VALUE_14 = "-affects__trackers__status"
-    VALUE_15 = "-affects__trackers__type"
-    VALUE_16 = "-affects__trackers__updated_dt"
-    VALUE_17 = "-affects__trackers__uuid"
-    VALUE_18 = "-affects__type"
-    VALUE_19 = "-affects__updated_dt"
-    VALUE_20 = "-affects__uuid"
-    VALUE_21 = "-component"
-    VALUE_22 = "-created_dt"
-    VALUE_23 = "-cve_id"
-    VALUE_24 = "-cvss2"
-    VALUE_25 = "-cvss2_score"
-    VALUE_26 = "-cvss3"
-    VALUE_27 = "-cvss3_score"
-    VALUE_28 = "-cwe_id"
-    VALUE_29 = "-impact"
-    VALUE_30 = "-is_major_incident"
-    VALUE_31 = "-nvd_cvss2"
-    VALUE_32 = "-nvd_cvss3"
-    VALUE_33 = "-reported_dt"
-    VALUE_34 = "-source"
-    VALUE_35 = "-type"
-    VALUE_36 = "-unembargo_dt"
-    VALUE_37 = "-updated_dt"
-    VALUE_38 = "-uuid"
+    VALUE_11 = "-affects__trackers__errata__advisory_name"
+    VALUE_12 = "-affects__trackers__external_system_id"
+    VALUE_13 = "-affects__trackers__ps_update_stream"
+    VALUE_14 = "-affects__trackers__resolution"
+    VALUE_15 = "-affects__trackers__status"
+    VALUE_16 = "-affects__trackers__type"
+    VALUE_17 = "-affects__trackers__updated_dt"
+    VALUE_18 = "-affects__trackers__uuid"
+    VALUE_19 = "-affects__type"
+    VALUE_20 = "-affects__updated_dt"
+    VALUE_21 = "-affects__uuid"
+    VALUE_22 = "-component"
+    VALUE_23 = "-created_dt"
+    VALUE_24 = "-cve_id"
+    VALUE_25 = "-cvss2"
+    VALUE_26 = "-cvss2_score"
+    VALUE_27 = "-cvss3"
+    VALUE_28 = "-cvss3_score"
+    VALUE_29 = "-cwe_id"
+    VALUE_30 = "-impact"
+    VALUE_31 = "-is_major_incident"
+    VALUE_32 = "-nvd_cvss2"
+    VALUE_33 = "-nvd_cvss3"
+    VALUE_34 = "-reported_dt"
+    VALUE_35 = "-source"
+    VALUE_36 = "-type"
+    VALUE_37 = "-unembargo_dt"
+    VALUE_38 = "-updated_dt"
+    VALUE_39 = "-uuid"
     AFFECTS_AFFECTEDNESS = "affects__affectedness"
     AFFECTS_CREATED_DT = "affects__created_dt"
     AFFECTS_CVSS2 = "affects__cvss2"
     AFFECTS_CVSS2_SCORE = "affects__cvss2_score"
     AFFECTS_CVSS3 = "affects__cvss3"
     AFFECTS_CVSS3_SCORE = "affects__cvss3_score"
     AFFECTS_IMPACT = "affects__impact"
     AFFECTS_PS_COMPONENT = "affects__ps_component"
     AFFECTS_PS_MODULE = "affects__ps_module"
     AFFECTS_RESOLUTION = "affects__resolution"
     AFFECTS_TRACKERS_CREATED_DT = "affects__trackers__created_dt"
+    AFFECTS_TRACKERS_ERRATA_ADVISORY_NAME = "affects__trackers__errata__advisory_name"
     AFFECTS_TRACKERS_EXTERNAL_SYSTEM_ID = "affects__trackers__external_system_id"
     AFFECTS_TRACKERS_PS_UPDATE_STREAM = "affects__trackers__ps_update_stream"
     AFFECTS_TRACKERS_RESOLUTION = "affects__trackers__resolution"
     AFFECTS_TRACKERS_STATUS = "affects__trackers__status"
     AFFECTS_TRACKERS_TYPE = "affects__trackers__type"
     AFFECTS_TRACKERS_UPDATED_DT = "affects__trackers__updated_dt"
     AFFECTS_TRACKERS_UUID = "affects__trackers__uuid"
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_source.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_source.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_create_response_201.py`

 * *Files 9% similar despite different names*

```diff
@@ -6,43 +6,45 @@
 
 from ..models.affect import Affect
 from ..models.blank_enum import BlankEnum
 from ..models.comment import Comment
 from ..models.cv_ev_5_package_versions import CVEv5PackageVersions
 from ..models.flaw_classification import FlawClassification
 from ..models.flaw_meta_attr import FlawMetaAttr
+from ..models.flaw_reference import FlawReference
+from ..models.flaw_type import FlawType
 from ..models.impact_enum import ImpactEnum
 from ..models.meta import Meta
 from ..models.source_666_enum import Source666Enum
-from ..models.type_824_enum import Type824Enum
 from ..types import UNSET, OSIDBModel, Unset
 
-T = TypeVar("T", bound="OsidbApiV1FlawsRetrieveResponse200")
+T = TypeVar("T", bound="OsidbApiV1FlawsCreateResponse201")
 
 
 @attr.s(auto_attribs=True)
-class OsidbApiV1FlawsRetrieveResponse200(OSIDBModel):
+class OsidbApiV1FlawsCreateResponse201(OSIDBModel):
     """ """
 
     uuid: str
     state: str
     resolution: str
     title: str
     trackers: List[str]
     description: str
     affects: List[Affect]
     meta: List[Meta]
     comments: List[Comment]
     meta_attr: FlawMetaAttr
     package_versions: List[CVEv5PackageVersions]
+    references: List[FlawReference]
     embargoed: bool
     created_dt: datetime.datetime
     updated_dt: datetime.datetime
     classification: FlawClassification
-    type: Union[Unset, Type824Enum] = UNSET
+    type: Union[Unset, FlawType] = UNSET
     cve_id: Union[Unset, None, str] = UNSET
     impact: Union[BlankEnum, ImpactEnum, Unset] = UNSET
     component: Union[Unset, str] = UNSET
     summary: Union[Unset, str] = UNSET
     statement: Union[Unset, str] = UNSET
     cwe_id: Union[Unset, str] = UNSET
     unembargo_dt: Union[Unset, None, datetime.datetime] = UNSET
@@ -112,14 +114,24 @@
             for package_versions_item_data in self.package_versions:
                 package_versions_item: Dict[str, Any] = UNSET
                 if not isinstance(package_versions_item_data, Unset):
                     package_versions_item = package_versions_item_data.to_dict()
 
                 package_versions.append(package_versions_item)
 
+        references: List[Dict[str, Any]] = UNSET
+        if not isinstance(self.references, Unset):
+            references = []
+            for references_item_data in self.references:
+                references_item: Dict[str, Any] = UNSET
+                if not isinstance(references_item_data, Unset):
+                    references_item = references_item_data.to_dict()
+
+                references.append(references_item)
+
         embargoed = self.embargoed
         created_dt: str = UNSET
         if not isinstance(self.created_dt, Unset):
             created_dt = self.created_dt.isoformat()
 
         updated_dt: str = UNSET
         if not isinstance(self.updated_dt, Unset):
@@ -128,15 +140,15 @@
         classification: Dict[str, Any] = UNSET
         if not isinstance(self.classification, Unset):
             classification = self.classification.to_dict()
 
         type: Union[Unset, str] = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type824Enum(self.type).value
+            type = FlawType(self.type).value
 
         cve_id = self.cve_id
         impact: Union[Unset, str]
         if isinstance(self.impact, Unset):
             impact = UNSET
         elif isinstance(self.impact, ImpactEnum):
             impact = UNSET
@@ -213,14 +225,16 @@
             field_dict["meta"] = meta
         if comments is not UNSET:
             field_dict["comments"] = comments
         if meta_attr is not UNSET:
             field_dict["meta_attr"] = meta_attr
         if package_versions is not UNSET:
             field_dict["package_versions"] = package_versions
+        if references is not UNSET:
+            field_dict["references"] = references
         if embargoed is not UNSET:
             field_dict["embargoed"] = embargoed
         if created_dt is not UNSET:
             field_dict["created_dt"] = created_dt
         if updated_dt is not UNSET:
             field_dict["updated_dt"] = updated_dt
         if classification is not UNSET:
@@ -352,14 +366,29 @@
                 else:
                     package_versions_item = CVEv5PackageVersions.from_dict(
                         _package_versions_item
                     )
 
                 package_versions.append(package_versions_item)
 
+        references = []
+        _references = d.pop("references", UNSET)
+        if _references is UNSET:
+            references = UNSET
+        else:
+            for references_item_data in _references or []:
+                _references_item = references_item_data
+                references_item: FlawReference
+                if isinstance(_references_item, Unset):
+                    references_item = UNSET
+                else:
+                    references_item = FlawReference.from_dict(_references_item)
+
+                references.append(references_item)
+
         embargoed = d.pop("embargoed", UNSET)
 
         _created_dt = d.pop("created_dt", UNSET)
         created_dt: datetime.datetime
         if isinstance(_created_dt, Unset):
             created_dt = UNSET
         else:
@@ -376,19 +405,19 @@
         classification: FlawClassification
         if isinstance(_classification, Unset):
             classification = UNSET
         else:
             classification = FlawClassification.from_dict(_classification)
 
         _type = d.pop("type", UNSET)
-        type: Union[Unset, Type824Enum]
+        type: Union[Unset, FlawType]
         if isinstance(_type, Unset):
             type = UNSET
         else:
-            type = Type824Enum(_type)
+            type = FlawType(_type)
 
         cve_id = d.pop("cve_id", UNSET)
 
         def _parse_impact(data: object) -> Union[BlankEnum, ImpactEnum, Unset]:
             if isinstance(data, Unset):
                 return data
             try:
@@ -497,26 +526,27 @@
 
         env = d.pop("env", UNSET)
 
         revision = d.pop("revision", UNSET)
 
         version = d.pop("version", UNSET)
 
-        osidb_api_v1_flaws_retrieve_response_200 = cls(
+        osidb_api_v1_flaws_create_response_201 = cls(
             uuid=uuid,
             state=state,
             resolution=resolution,
             title=title,
             trackers=trackers,
             description=description,
             affects=affects,
             meta=meta,
             comments=comments,
             meta_attr=meta_attr,
             package_versions=package_versions,
+            references=references,
             embargoed=embargoed,
             created_dt=created_dt,
             updated_dt=updated_dt,
             classification=classification,
             type=type,
             cve_id=cve_id,
             impact=impact,
@@ -537,16 +567,16 @@
             is_major_incident=is_major_incident,
             dt=dt,
             env=env,
             revision=revision,
             version=version,
         )
 
-        osidb_api_v1_flaws_retrieve_response_200.additional_properties = d
-        return osidb_api_v1_flaws_retrieve_response_200
+        osidb_api_v1_flaws_create_response_201.additional_properties = d
+        return osidb_api_v1_flaws_create_response_201
 
     @staticmethod
     def get_fields():
         return {
             "uuid": str,
             "state": str,
             "resolution": str,
@@ -554,19 +584,20 @@
             "trackers": List[str],
             "description": str,
             "affects": List[Affect],
             "meta": List[Meta],
             "comments": List[Comment],
             "meta_attr": FlawMetaAttr,
             "package_versions": List[CVEv5PackageVersions],
+            "references": List[FlawReference],
             "embargoed": bool,
             "created_dt": datetime.datetime,
             "updated_dt": datetime.datetime,
             "classification": FlawClassification,
-            "type": Type824Enum,
+            "type": FlawType,
             "cve_id": str,
             "impact": Union[BlankEnum, ImpactEnum],
             "component": str,
             "summary": str,
             "statement": str,
             "cwe_id": str,
             "unembargo_dt": datetime.datetime,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_update_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_retrieve_response_200.py`

 * *Files 9% similar despite different names*

```diff
@@ -6,43 +6,45 @@
 
 from ..models.affect import Affect
 from ..models.blank_enum import BlankEnum
 from ..models.comment import Comment
 from ..models.cv_ev_5_package_versions import CVEv5PackageVersions
 from ..models.flaw_classification import FlawClassification
 from ..models.flaw_meta_attr import FlawMetaAttr
+from ..models.flaw_reference import FlawReference
+from ..models.flaw_type import FlawType
 from ..models.impact_enum import ImpactEnum
 from ..models.meta import Meta
 from ..models.source_666_enum import Source666Enum
-from ..models.type_824_enum import Type824Enum
 from ..types import UNSET, OSIDBModel, Unset
 
-T = TypeVar("T", bound="OsidbApiV1FlawsUpdateResponse200")
+T = TypeVar("T", bound="OsidbApiV1FlawsRetrieveResponse200")
 
 
 @attr.s(auto_attribs=True)
-class OsidbApiV1FlawsUpdateResponse200(OSIDBModel):
+class OsidbApiV1FlawsRetrieveResponse200(OSIDBModel):
     """ """
 
     uuid: str
     state: str
     resolution: str
     title: str
     trackers: List[str]
     description: str
     affects: List[Affect]
     meta: List[Meta]
     comments: List[Comment]
     meta_attr: FlawMetaAttr
     package_versions: List[CVEv5PackageVersions]
+    references: List[FlawReference]
     embargoed: bool
     created_dt: datetime.datetime
     updated_dt: datetime.datetime
     classification: FlawClassification
-    type: Union[Unset, Type824Enum] = UNSET
+    type: Union[Unset, FlawType] = UNSET
     cve_id: Union[Unset, None, str] = UNSET
     impact: Union[BlankEnum, ImpactEnum, Unset] = UNSET
     component: Union[Unset, str] = UNSET
     summary: Union[Unset, str] = UNSET
     statement: Union[Unset, str] = UNSET
     cwe_id: Union[Unset, str] = UNSET
     unembargo_dt: Union[Unset, None, datetime.datetime] = UNSET
@@ -112,14 +114,24 @@
             for package_versions_item_data in self.package_versions:
                 package_versions_item: Dict[str, Any] = UNSET
                 if not isinstance(package_versions_item_data, Unset):
                     package_versions_item = package_versions_item_data.to_dict()
 
                 package_versions.append(package_versions_item)
 
+        references: List[Dict[str, Any]] = UNSET
+        if not isinstance(self.references, Unset):
+            references = []
+            for references_item_data in self.references:
+                references_item: Dict[str, Any] = UNSET
+                if not isinstance(references_item_data, Unset):
+                    references_item = references_item_data.to_dict()
+
+                references.append(references_item)
+
         embargoed = self.embargoed
         created_dt: str = UNSET
         if not isinstance(self.created_dt, Unset):
             created_dt = self.created_dt.isoformat()
 
         updated_dt: str = UNSET
         if not isinstance(self.updated_dt, Unset):
@@ -128,15 +140,15 @@
         classification: Dict[str, Any] = UNSET
         if not isinstance(self.classification, Unset):
             classification = self.classification.to_dict()
 
         type: Union[Unset, str] = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type824Enum(self.type).value
+            type = FlawType(self.type).value
 
         cve_id = self.cve_id
         impact: Union[Unset, str]
         if isinstance(self.impact, Unset):
             impact = UNSET
         elif isinstance(self.impact, ImpactEnum):
             impact = UNSET
@@ -213,14 +225,16 @@
             field_dict["meta"] = meta
         if comments is not UNSET:
             field_dict["comments"] = comments
         if meta_attr is not UNSET:
             field_dict["meta_attr"] = meta_attr
         if package_versions is not UNSET:
             field_dict["package_versions"] = package_versions
+        if references is not UNSET:
+            field_dict["references"] = references
         if embargoed is not UNSET:
             field_dict["embargoed"] = embargoed
         if created_dt is not UNSET:
             field_dict["created_dt"] = created_dt
         if updated_dt is not UNSET:
             field_dict["updated_dt"] = updated_dt
         if classification is not UNSET:
@@ -352,14 +366,29 @@
                 else:
                     package_versions_item = CVEv5PackageVersions.from_dict(
                         _package_versions_item
                     )
 
                 package_versions.append(package_versions_item)
 
+        references = []
+        _references = d.pop("references", UNSET)
+        if _references is UNSET:
+            references = UNSET
+        else:
+            for references_item_data in _references or []:
+                _references_item = references_item_data
+                references_item: FlawReference
+                if isinstance(_references_item, Unset):
+                    references_item = UNSET
+                else:
+                    references_item = FlawReference.from_dict(_references_item)
+
+                references.append(references_item)
+
         embargoed = d.pop("embargoed", UNSET)
 
         _created_dt = d.pop("created_dt", UNSET)
         created_dt: datetime.datetime
         if isinstance(_created_dt, Unset):
             created_dt = UNSET
         else:
@@ -376,19 +405,19 @@
         classification: FlawClassification
         if isinstance(_classification, Unset):
             classification = UNSET
         else:
             classification = FlawClassification.from_dict(_classification)
 
         _type = d.pop("type", UNSET)
-        type: Union[Unset, Type824Enum]
+        type: Union[Unset, FlawType]
         if isinstance(_type, Unset):
             type = UNSET
         else:
-            type = Type824Enum(_type)
+            type = FlawType(_type)
 
         cve_id = d.pop("cve_id", UNSET)
 
         def _parse_impact(data: object) -> Union[BlankEnum, ImpactEnum, Unset]:
             if isinstance(data, Unset):
                 return data
             try:
@@ -497,26 +526,27 @@
 
         env = d.pop("env", UNSET)
 
         revision = d.pop("revision", UNSET)
 
         version = d.pop("version", UNSET)
 
-        osidb_api_v1_flaws_update_response_200 = cls(
+        osidb_api_v1_flaws_retrieve_response_200 = cls(
             uuid=uuid,
             state=state,
             resolution=resolution,
             title=title,
             trackers=trackers,
             description=description,
             affects=affects,
             meta=meta,
             comments=comments,
             meta_attr=meta_attr,
             package_versions=package_versions,
+            references=references,
             embargoed=embargoed,
             created_dt=created_dt,
             updated_dt=updated_dt,
             classification=classification,
             type=type,
             cve_id=cve_id,
             impact=impact,
@@ -537,16 +567,16 @@
             is_major_incident=is_major_incident,
             dt=dt,
             env=env,
             revision=revision,
             version=version,
         )
 
-        osidb_api_v1_flaws_update_response_200.additional_properties = d
-        return osidb_api_v1_flaws_update_response_200
+        osidb_api_v1_flaws_retrieve_response_200.additional_properties = d
+        return osidb_api_v1_flaws_retrieve_response_200
 
     @staticmethod
     def get_fields():
         return {
             "uuid": str,
             "state": str,
             "resolution": str,
@@ -554,19 +584,20 @@
             "trackers": List[str],
             "description": str,
             "affects": List[Affect],
             "meta": List[Meta],
             "comments": List[Comment],
             "meta_attr": FlawMetaAttr,
             "package_versions": List[CVEv5PackageVersions],
+            "references": List[FlawReference],
             "embargoed": bool,
             "created_dt": datetime.datetime,
             "updated_dt": datetime.datetime,
             "classification": FlawClassification,
-            "type": Type824Enum,
+            "type": FlawType,
             "cve_id": str,
             "impact": Union[BlankEnum, ImpactEnum],
             "component": str,
             "summary": str,
             "statement": str,
             "cwe_id": str,
             "unembargo_dt": datetime.datetime,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_manifest_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_manifest_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_schema_retrieve_lang.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_schema_retrieve_lang.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_schema_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_schema_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_status_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_status_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_status_retrieve_response_200_osidb_data.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_status_retrieve_response_200_osidb_data.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_status_retrieve_response_200_osidb_service.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_status_retrieve_response_200_osidb_service.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_flaw_source.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_affects_flaw_source.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_order_item.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_order_item.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_list_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_api_v1_trackers_retrieve_response_200.py`

 * *Files 6% similar despite different names*

```diff
@@ -2,26 +2,26 @@
 from typing import Any, Dict, List, Type, TypeVar, Union, cast
 
 import attr
 from dateutil.parser import isoparse
 
 from ..models.erratum import Erratum
 from ..models.tracker_meta_attr import TrackerMetaAttr
-from ..models.type_0d0_enum import Type0D0Enum
+from ..models.tracker_type import TrackerType
 from ..types import UNSET, OSIDBModel, Unset
 
 T = TypeVar("T", bound="OsidbApiV1TrackersRetrieveResponse200")
 
 
 @attr.s(auto_attribs=True)
 class OsidbApiV1TrackersRetrieveResponse200(OSIDBModel):
     """ """
 
     uuid: str
-    type: Type0D0Enum
+    type: TrackerType
     external_system_id: str
     status: str
     errata: List[Erratum]
     meta_attr: TrackerMetaAttr
     created_dt: datetime.datetime
     updated_dt: datetime.datetime
     affects: Union[Unset, List[str]] = UNSET
@@ -33,15 +33,15 @@
     additional_properties: Dict[str, Any] = attr.ib(init=False, factory=dict)
 
     def to_dict(self) -> Dict[str, Any]:
         uuid = self.uuid
         type: str = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type0D0Enum(self.type).value
+            type = TrackerType(self.type).value
 
         external_system_id = self.external_system_id
         status = self.status
         errata: List[Dict[str, Any]] = UNSET
         if not isinstance(self.errata, Unset):
             errata = []
             for errata_item_data in self.errata:
@@ -111,19 +111,19 @@
 
     @classmethod
     def from_dict(cls: Type[T], src_dict: Dict[str, Any]) -> T:
         d = src_dict.copy()
         uuid = d.pop("uuid", UNSET)
 
         _type = d.pop("type", UNSET)
-        type: Type0D0Enum
+        type: TrackerType
         if isinstance(_type, Unset):
             type = UNSET
         else:
-            type = Type0D0Enum(_type)
+            type = TrackerType(_type)
 
         external_system_id = d.pop("external_system_id", UNSET)
 
         status = d.pop("status", UNSET)
 
         errata = []
         _errata = d.pop("errata", UNSET)
@@ -198,15 +198,15 @@
         osidb_api_v1_trackers_retrieve_response_200.additional_properties = d
         return osidb_api_v1_trackers_retrieve_response_200
 
     @staticmethod
     def get_fields():
         return {
             "uuid": str,
-            "type": Type0D0Enum,
+            "type": TrackerType,
             "external_system_id": str,
             "status": str,
             "errata": List[Erratum],
             "meta_attr": TrackerMetaAttr,
             "created_dt": datetime.datetime,
             "updated_dt": datetime.datetime,
             "affects": List[str],
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_healthy_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_healthy_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_whoami_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_whoami_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osidb_whoami_retrieve_response_200_profile.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osidb_whoami_retrieve_response_200_profile.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osim_api_v1_workflows_adjust_create_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osim_api_v1_workflows_adjust_create_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osim_api_v1_workflows_retrieve_2_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osim_api_v1_workflows_retrieve_2_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osim_api_v1_workflows_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osim_api_v1_workflows_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osim_healthy_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osim_healthy_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/osim_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/osim_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/paginated_affect_list.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_affect_list.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/paginated_epss_list.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_epss_list.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/paginated_exploit_only_report_data_list.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_exploit_only_report_data_list.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/paginated_flaw_list.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_flaw_list.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/paginated_flaw_report_data_list.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_flaw_report_data_list.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/paginated_supported_products_list.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_supported_products_list.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/paginated_tracker_list.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/paginated_tracker_list.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/source_666_enum.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/source_666_enum.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/supported_products.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/supported_products.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_group_create_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_group_create_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_group_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_group_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_group_update_response_204.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_group_update_response_200.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,19 +2,19 @@
 from typing import Any, Dict, List, Type, TypeVar, Union
 
 import attr
 from dateutil.parser import isoparse
 
 from ..types import UNSET, OSIDBModel, Unset
 
-T = TypeVar("T", bound="TaskmanApiV1GroupUpdateResponse204")
+T = TypeVar("T", bound="TaskmanApiV1GroupUpdateResponse200")
 
 
 @attr.s(auto_attribs=True)
-class TaskmanApiV1GroupUpdateResponse204(OSIDBModel):
+class TaskmanApiV1GroupUpdateResponse200(OSIDBModel):
     """ """
 
     dt: Union[Unset, datetime.datetime] = UNSET
     env: Union[Unset, str] = UNSET
     revision: Union[Unset, str] = UNSET
     version: Union[Unset, str] = UNSET
     additional_properties: Dict[str, Any] = attr.ib(init=False, factory=dict)
@@ -53,23 +53,23 @@
 
         env = d.pop("env", UNSET)
 
         revision = d.pop("revision", UNSET)
 
         version = d.pop("version", UNSET)
 
-        taskman_api_v1_group_update_response_204 = cls(
+        taskman_api_v1_group_update_response_200 = cls(
             dt=dt,
             env=env,
             revision=revision,
             version=version,
         )
 
-        taskman_api_v1_group_update_response_204.additional_properties = d
-        return taskman_api_v1_group_update_response_204
+        taskman_api_v1_group_update_response_200.additional_properties = d
+        return taskman_api_v1_group_update_response_200
 
     @staticmethod
     def get_fields():
         return {
             "dt": datetime.datetime,
             "env": str,
             "revision": str,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_comment_create_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_comment_create_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_comment_update_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_comment_update_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_create_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_create_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_update_response_204.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_update_response_200.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,19 +2,19 @@
 from typing import Any, Dict, List, Type, TypeVar, Union
 
 import attr
 from dateutil.parser import isoparse
 
 from ..types import UNSET, OSIDBModel, Unset
 
-T = TypeVar("T", bound="TaskmanApiV1TaskFlawUpdateResponse204")
+T = TypeVar("T", bound="TaskmanApiV1TaskFlawUpdateResponse200")
 
 
 @attr.s(auto_attribs=True)
-class TaskmanApiV1TaskFlawUpdateResponse204(OSIDBModel):
+class TaskmanApiV1TaskFlawUpdateResponse200(OSIDBModel):
     """ """
 
     dt: Union[Unset, datetime.datetime] = UNSET
     env: Union[Unset, str] = UNSET
     revision: Union[Unset, str] = UNSET
     version: Union[Unset, str] = UNSET
     additional_properties: Dict[str, Any] = attr.ib(init=False, factory=dict)
@@ -53,23 +53,23 @@
 
         env = d.pop("env", UNSET)
 
         revision = d.pop("revision", UNSET)
 
         version = d.pop("version", UNSET)
 
-        taskman_api_v1_task_flaw_update_response_204 = cls(
+        taskman_api_v1_task_flaw_update_response_200 = cls(
             dt=dt,
             env=env,
             revision=revision,
             version=version,
         )
 
-        taskman_api_v1_task_flaw_update_response_204.additional_properties = d
-        return taskman_api_v1_task_flaw_update_response_204
+        taskman_api_v1_task_flaw_update_response_200.additional_properties = d
+        return taskman_api_v1_task_flaw_update_response_200
 
     @staticmethod
     def get_fields():
         return {
             "dt": datetime.datetime,
             "env": str,
             "revision": str,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_retrieve_response_200.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_status_update_response_204.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_status_update_response_200.py`

 * *Files 5% similar despite different names*

```diff
@@ -2,19 +2,19 @@
 from typing import Any, Dict, List, Type, TypeVar, Union
 
 import attr
 from dateutil.parser import isoparse
 
 from ..types import UNSET, OSIDBModel, Unset
 
-T = TypeVar("T", bound="TaskmanApiV1TaskStatusUpdateResponse204")
+T = TypeVar("T", bound="TaskmanApiV1TaskStatusUpdateResponse200")
 
 
 @attr.s(auto_attribs=True)
-class TaskmanApiV1TaskStatusUpdateResponse204(OSIDBModel):
+class TaskmanApiV1TaskStatusUpdateResponse200(OSIDBModel):
     """ """
 
     dt: Union[Unset, datetime.datetime] = UNSET
     env: Union[Unset, str] = UNSET
     revision: Union[Unset, str] = UNSET
     version: Union[Unset, str] = UNSET
     additional_properties: Dict[str, Any] = attr.ib(init=False, factory=dict)
@@ -53,23 +53,23 @@
 
         env = d.pop("env", UNSET)
 
         revision = d.pop("revision", UNSET)
 
         version = d.pop("version", UNSET)
 
-        taskman_api_v1_task_status_update_response_204 = cls(
+        taskman_api_v1_task_status_update_response_200 = cls(
             dt=dt,
             env=env,
             revision=revision,
             version=version,
         )
 
-        taskman_api_v1_task_status_update_response_204.additional_properties = d
-        return taskman_api_v1_task_status_update_response_204
+        taskman_api_v1_task_status_update_response_200.additional_properties = d
+        return taskman_api_v1_task_status_update_response_200
 
     @staticmethod
     def get_fields():
         return {
             "dt": datetime.datetime,
             "env": str,
             "revision": str,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/taskman_healthy_retrieve_response_200.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/taskman_api_v1_task_assignee_update_response_200.py`

 * *Files 8% similar despite different names*

```diff
@@ -2,19 +2,19 @@
 from typing import Any, Dict, List, Type, TypeVar, Union
 
 import attr
 from dateutil.parser import isoparse
 
 from ..types import UNSET, OSIDBModel, Unset
 
-T = TypeVar("T", bound="TaskmanHealthyRetrieveResponse200")
+T = TypeVar("T", bound="TaskmanApiV1TaskAssigneeUpdateResponse200")
 
 
 @attr.s(auto_attribs=True)
-class TaskmanHealthyRetrieveResponse200(OSIDBModel):
+class TaskmanApiV1TaskAssigneeUpdateResponse200(OSIDBModel):
     """ """
 
     dt: Union[Unset, datetime.datetime] = UNSET
     env: Union[Unset, str] = UNSET
     revision: Union[Unset, str] = UNSET
     version: Union[Unset, str] = UNSET
     additional_properties: Dict[str, Any] = attr.ib(init=False, factory=dict)
@@ -53,23 +53,23 @@
 
         env = d.pop("env", UNSET)
 
         revision = d.pop("revision", UNSET)
 
         version = d.pop("version", UNSET)
 
-        taskman_healthy_retrieve_response_200 = cls(
+        taskman_api_v1_task_assignee_update_response_200 = cls(
             dt=dt,
             env=env,
             revision=revision,
             version=version,
         )
 
-        taskman_healthy_retrieve_response_200.additional_properties = d
-        return taskman_healthy_retrieve_response_200
+        taskman_api_v1_task_assignee_update_response_200.additional_properties = d
+        return taskman_api_v1_task_assignee_update_response_200
 
     @staticmethod
     def get_fields():
         return {
             "dt": datetime.datetime,
             "env": str,
             "revision": str,
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/token_obtain_pair.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/token_obtain_pair.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/token_refresh.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/token_refresh.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/token_verify.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/token_verify.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/tracker.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/tracker.py`

 * *Files 6% similar despite different names*

```diff
@@ -2,26 +2,26 @@
 from typing import Any, Dict, List, Type, TypeVar, Union, cast
 
 import attr
 from dateutil.parser import isoparse
 
 from ..models.erratum import Erratum
 from ..models.tracker_meta_attr import TrackerMetaAttr
-from ..models.type_0d0_enum import Type0D0Enum
+from ..models.tracker_type import TrackerType
 from ..types import UNSET, OSIDBModel, Unset
 
 T = TypeVar("T", bound="Tracker")
 
 
 @attr.s(auto_attribs=True)
 class Tracker(OSIDBModel):
     """Tracker serializer"""
 
     uuid: str
-    type: Type0D0Enum
+    type: TrackerType
     external_system_id: str
     status: str
     errata: List[Erratum]
     meta_attr: TrackerMetaAttr
     created_dt: datetime.datetime
     updated_dt: datetime.datetime
     affects: Union[Unset, List[str]] = UNSET
@@ -29,15 +29,15 @@
     additional_properties: Dict[str, Any] = attr.ib(init=False, factory=dict)
 
     def to_dict(self) -> Dict[str, Any]:
         uuid = self.uuid
         type: str = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type0D0Enum(self.type).value
+            type = TrackerType(self.type).value
 
         external_system_id = self.external_system_id
         status = self.status
         errata: List[Dict[str, Any]] = UNSET
         if not isinstance(self.errata, Unset):
             errata = []
             for errata_item_data in self.errata:
@@ -92,19 +92,19 @@
 
     @classmethod
     def from_dict(cls: Type[T], src_dict: Dict[str, Any]) -> T:
         d = src_dict.copy()
         uuid = d.pop("uuid", UNSET)
 
         _type = d.pop("type", UNSET)
-        type: Type0D0Enum
+        type: TrackerType
         if isinstance(_type, Unset):
             type = UNSET
         else:
-            type = Type0D0Enum(_type)
+            type = TrackerType(_type)
 
         external_system_id = d.pop("external_system_id", UNSET)
 
         status = d.pop("status", UNSET)
 
         errata = []
         _errata = d.pop("errata", UNSET)
@@ -162,15 +162,15 @@
         tracker.additional_properties = d
         return tracker
 
     @staticmethod
     def get_fields():
         return {
             "uuid": str,
-            "type": Type0D0Enum,
+            "type": TrackerType,
             "external_system_id": str,
             "status": str,
             "errata": List[Erratum],
             "meta_attr": TrackerMetaAttr,
             "created_dt": datetime.datetime,
             "updated_dt": datetime.datetime,
             "affects": List[str],
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/tracker_meta_attr.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/tracker_meta_attr.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/models/tracker_report_data.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/models/tracker_report_data.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,32 +1,32 @@
 from typing import Any, Dict, List, Type, TypeVar, Union
 
 import attr
 
-from ..models.type_0d0_enum import Type0D0Enum
+from ..models.tracker_type import TrackerType
 from ..types import UNSET, OSIDBModel, Unset
 
 T = TypeVar("T", bound="TrackerReportData")
 
 
 @attr.s(auto_attribs=True)
 class TrackerReportData(OSIDBModel):
     """ """
 
-    type: Type0D0Enum
+    type: TrackerType
     external_system_id: str
     status: str
     resolution: Union[Unset, str] = UNSET
     additional_properties: Dict[str, Any] = attr.ib(init=False, factory=dict)
 
     def to_dict(self) -> Dict[str, Any]:
         type: str = UNSET
         if not isinstance(self.type, Unset):
 
-            type = Type0D0Enum(self.type).value
+            type = TrackerType(self.type).value
 
         external_system_id = self.external_system_id
         status = self.status
         resolution = self.resolution
 
         field_dict: Dict[str, Any] = {}
         field_dict.update(self.additional_properties)
@@ -41,19 +41,19 @@
 
         return field_dict
 
     @classmethod
     def from_dict(cls: Type[T], src_dict: Dict[str, Any]) -> T:
         d = src_dict.copy()
         _type = d.pop("type", UNSET)
-        type: Type0D0Enum
+        type: TrackerType
         if isinstance(_type, Unset):
             type = UNSET
         else:
-            type = Type0D0Enum(_type)
+            type = TrackerType(_type)
 
         external_system_id = d.pop("external_system_id", UNSET)
 
         status = d.pop("status", UNSET)
 
         resolution = d.pop("resolution", UNSET)
 
@@ -66,15 +66,15 @@
 
         tracker_report_data.additional_properties = d
         return tracker_report_data
 
     @staticmethod
     def get_fields():
         return {
-            "type": Type0D0Enum,
+            "type": TrackerType,
             "external_system_id": str,
             "status": str,
             "resolution": str,
         }
 
     @property
     def additional_keys(self) -> List[str]:
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings/bindings/python_client/types.py` & `osidb-bindings-3.3.0/osidb_bindings/bindings/python_client/types.py`

 * *Files identical despite different names*

### Comparing `osidb-bindings-3.1.0/osidb_bindings/session.py` & `osidb-bindings-3.3.0/osidb_bindings/session.py`

 * *Files 12% similar despite different names*

```diff
@@ -16,27 +16,33 @@
 )
 from .bindings.python_client.types import UNSET
 from .constants import (
     ALL_SESSION_OPERATIONS,
     OSIDB_API_VERSION,
     OSIDB_BINDINGS_API_PATH,
     OSIDB_BINDINGS_USERAGENT,
-    RESOURCE_TO_MODEL_MAPPING,
 )
 
 osidb_status_retrieve = importlib.import_module(
     f"{OSIDB_BINDINGS_API_PATH}.osidb_api_{OSIDB_API_VERSION}_status_retrieve",
     package="osidb_bindings",
 )
 
 
 class OperationUnsupported(Exception):
     """Session operation is unsupported exception"""
 
 
+class UndefinedRequestBody(Exception):
+    """
+    Request body is not defined for the particular
+    resource and operation combination
+    """
+
+
 def get_sync_function(api_module: ModuleType) -> Callable:
     """
     Get 'sync' function from API module if available (response example is defined in schema)
     or get basic 'sync_detailed' function (response example is not defined in schema)
     """
     return getattr(api_module, "sync", getattr(api_module, "sync_detailed"))
 
@@ -84,14 +90,26 @@
             allowed_operations=(
                 "retrieve",
                 "update",
                 "list",
                 "create",
                 "search",
             ),
+            subresources={
+                "comments": {"allowed_operations": ["retrieve", "list", "create"]},
+                "references": {
+                    "allowed_operations": [
+                        "retrieve",
+                        "update",
+                        "list",
+                        "create",
+                        "destroy",
+                    ]
+                },
+            },
         )
         self.affects = SessionOperationsGroup(
             self.__get_client_with_new_access_token,
             "affects",
             allowed_operations=(
                 "retrieve",
                 "update",
@@ -174,42 +192,44 @@
     """
 
     def __init__(
         self,
         client: Callable,
         resource_name: str,
         allowed_operations: List[str] = ALL_SESSION_OPERATIONS,
+        subresources: Dict[str, dict] = None,
     ):
         self.client = client
         self.resource_name = resource_name
         self.allowed_operations = allowed_operations
 
-    @property
-    def model_name(self) -> str:
-        if self.resource_name in RESOURCE_TO_MODEL_MAPPING:
-            # from mapping
-            return RESOURCE_TO_MODEL_MAPPING[self.resource_name]
-        else:
-            # parse it from the resource name
-            name_components = self.resource_name.split("_")
-            name_components[-1] = name_components[-1][:-1]
-            return "".join(name_component.title() for name_component in name_components)
-
-    @property
-    def model(self):
-        return getattr(models, self.model_name)
+        if subresources is None:
+            subresources = {}
+
+        # Create a session operation group for each subresource with respective
+        # allowed session operations
+        for subresource_name, subresource_metadata in subresources.items():
+            setattr(
+                self,
+                subresource_name,
+                SessionOperationsGroup(
+                    client,
+                    resource_name=f"{resource_name}_{subresource_name}",
+                    **subresource_metadata,
+                ),
+            )
 
     def __get_method_module(self, resource_name: str, method: str) -> ModuleType:
         # import endpoint module based on a method
         return importlib.import_module(
             f"{OSIDB_BINDINGS_API_PATH}.osidb_api_{OSIDB_API_VERSION}_{resource_name}_{method}",
             package="osidb_bindings",
         )
 
-    def __make_iterable(self, response, **kwargs):
+    def __make_iterable(self, response, *args, **kwargs):
         """
         Populate next, prev and iterator helper methods for paginated responses
         """
 
         response.iterator = Paginator(
             session_operation=self.retrieve_list, init_response=response
         )
@@ -224,99 +244,120 @@
                 limit = re.search("limit=(\d+)", param)
                 if limit is not None:
                     kwargs["limit"] = limit.group(1)
                 offset = re.search("offset=(\d+)", param)
                 if offset is not None:
                     kwargs["offset"] = offset.group(1)
 
-                setattr(response, func_name, partial(self.retrieve_list, **kwargs))
+                setattr(
+                    response, func_name, partial(self.retrieve_list, *args, **kwargs)
+                )
 
         return response
 
     # CRUD operations
 
-    def retrieve(self, id, **kwargs):
+    def retrieve(self, id, *args, **kwargs):
         if "retrieve" in self.allowed_operations:
             method_module = self.__get_method_module(
                 resource_name=self.resource_name, method="retrieve"
             )
             sync_fn = get_sync_function(method_module)
-            return sync_fn(id, client=self.client(), **kwargs)
+            return sync_fn(id, *args, client=self.client(), **kwargs)
         else:
             raise OperationUnsupported(
                 'Operation "update" is not supported for the '
                 f'"{self.resource_name}" resource.'
             )
 
-    def retrieve_list(self, **kwargs):
+    def retrieve_list(self, *args, **kwargs):
         if "list" in self.allowed_operations:
             method_module = self.__get_method_module(
                 resource_name=self.resource_name, method="list"
             )
             sync_fn = get_sync_function(method_module)
             return self.__make_iterable(
-                sync_fn(client=self.client(), **kwargs), **kwargs
+                sync_fn(*args, client=self.client(), **kwargs), *args, **kwargs
             )
         else:
             raise OperationUnsupported(
                 'Operation "update" is not supported for the '
                 f'"{self.resource_name}" resource.'
             )
 
-    def create(self, form_data: Dict[str, Any]):
+    def create(self, form_data: Dict[str, Any], *args, **kwargs):
         if "create" in self.allowed_operations:
-            model = getattr(models, self.model_name)
-            transformed_data = model.from_dict(form_data)
-
             method_module = self.__get_method_module(
                 resource_name=self.resource_name, method="create"
             )
+            model = getattr(method_module, "REQUEST_BODY_TYPE", None)
+            if model is None:
+                raise UndefinedRequestBody(
+                    "There is no defined request body "
+                    f'for the resource "{self.resource_name}" '
+                    'and "create" operation.'
+                )
+
+            transformed_data = model.from_dict(form_data)
             sync_fn = get_sync_function(method_module)
             return sync_fn(
+                *args,
                 client=self.client(),
                 form_data=transformed_data,
                 multipart_data=UNSET,
                 json_body=UNSET,
+                **kwargs,
             )
         else:
             raise OperationUnsupported(
                 'Operation "update" is not supported for the '
                 f'"{self.resource_name}" resource.'
             )
 
-    def update(self, id, form_data: Dict[str, Any]):
+    def update(self, id, form_data: Dict[str, Any], *args, **kwargs):
         if "update" in self.allowed_operations:
-            transformed_data = self.model.from_dict(form_data)
-
             method_module = self.__get_method_module(
                 resource_name=self.resource_name, method="update"
             )
+            model = getattr(method_module, "REQUEST_BODY_TYPE", None)
+            if model is None:
+                raise UndefinedRequestBody(
+                    "There is no defined request body "
+                    f'for the resource "{self.resource_name}" '
+                    'and "update" operation.'
+                )
+
+            transformed_data = model.from_dict(form_data)
             sync_fn = get_sync_function(method_module)
             return sync_fn(
                 id,
+                *args,
                 client=self.client(),
                 form_data=transformed_data,
                 multipart_data=UNSET,
                 json_body=UNSET,
+                **kwargs,
             )
         else:
             raise OperationUnsupported(
                 'Operation "update" is not supported for the '
                 f'"{self.resource_name}" resource.'
             )
 
-    def delete(self, id):
+    def delete(self, id, *args, **kwargs):
         if "destroy" in self.allowed_operations:
             method_module = self.__get_method_module(
                 resource_name=self.resource_name, method="destroy"
             )
             sync_fn = get_sync_function(method_module)
             return sync_fn(
                 id,
+                *args,
                 client=self.client(),
+                **kwargs,
             )
         else:
             raise OperationUnsupported(
                 'Operation "delete" is not supported for the '
                 f'"{self.resource_name}" resource.'
             )
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings.egg-info/PKG-INFO` & `osidb-bindings-3.3.0/osidb_bindings.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: osidb-bindings
-Version: 3.1.0
+Version: 3.3.0
 Summary: Python bindings for accessing OSIDB API
 Home-page: https://github.com/RedHatProductSecurity/osidb-bindings
 Author: Jakub Frejlach, Red Hat Product Security
 Author-email: jfrejlac@redhat.com
 Project-URL: Changelog, https://github.com/RedHatProductSecurity/osidb-bindings/blob/master/CHANGELOG.md
 Project-URL: Documentation, https://github.com/RedHatProductSecurity/osidb-bindings/blob/master/TUTORIAL.md
 Project-URL: Source, https://github.com/RedHatProductSecurity/osidb-bindings
```

### Comparing `osidb-bindings-3.1.0/osidb_bindings.egg-info/SOURCES.txt` & `osidb-bindings-3.3.0/osidb_bindings.egg-info/SOURCES.txt`

 * *Files 8% similar despite different names*

```diff
@@ -37,16 +37,24 @@
 osidb_bindings/bindings/python_client/api/exploits/exploits_api_v1_supported_products_list.py
 osidb_bindings/bindings/python_client/api/osidb/__init__.py
 osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_create.py
 osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_destroy.py
 osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_list.py
 osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_retrieve.py
 osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_affects_update.py
+osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_comments_create.py
+osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_comments_list.py
+osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_comments_retrieve.py
 osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_create.py
 osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_list.py
+osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_references_create.py
+osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_references_destroy.py
+osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_references_list.py
+osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_references_retrieve.py
+osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_references_update.py
 osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_retrieve.py
 osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_flaws_update.py
 osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_manifest_retrieve.py
 osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_schema_retrieve.py
 osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_status_retrieve.py
 osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_trackers_list.py
 osidb_bindings/bindings/python_client/api/osidb/osidb_api_v1_trackers_retrieve.py
@@ -58,28 +66,32 @@
 osidb_bindings/bindings/python_client/api/osim/osim_api_v1_workflows_retrieve_2.py
 osidb_bindings/bindings/python_client/api/osim/osim_healthy_retrieve.py
 osidb_bindings/bindings/python_client/api/osim/osim_retrieve.py
 osidb_bindings/bindings/python_client/api/taskman/__init__.py
 osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_create.py
 osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_retrieve.py
 osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_group_update.py
+osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_assignee_retrieve.py
+osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_assignee_update.py
 osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_comment_create.py
 osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_comment_update.py
 osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_create.py
 osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_retrieve.py
 osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_flaw_update.py
 osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_retrieve.py
 osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_status_update.py
+osidb_bindings/bindings/python_client/api/taskman/taskman_api_v1_task_unassigned_retrieve.py
 osidb_bindings/bindings/python_client/api/taskman/taskman_healthy_retrieve.py
 osidb_bindings/bindings/python_client/models/__init__.py
 osidb_bindings/bindings/python_client/models/affect.py
 osidb_bindings/bindings/python_client/models/affect_meta_attr.py
 osidb_bindings/bindings/python_client/models/affect_post.py
 osidb_bindings/bindings/python_client/models/affect_post_meta_attr.py
 osidb_bindings/bindings/python_client/models/affect_report_data.py
+osidb_bindings/bindings/python_client/models/affect_type.py
 osidb_bindings/bindings/python_client/models/affectedness_enum.py
 osidb_bindings/bindings/python_client/models/auth_token_create_response_200.py
 osidb_bindings/bindings/python_client/models/auth_token_refresh_create_response_200.py
 osidb_bindings/bindings/python_client/models/auth_token_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/auth_token_verify_create_response_200.py
 osidb_bindings/bindings/python_client/models/blank_enum.py
 osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200.py
@@ -87,15 +99,14 @@
 osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item_data.py
 osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item_error.py
 osidb_bindings/bindings/python_client/models/collectors_api_v1_status_retrieve_response_200_collectors_item_state.py
 osidb_bindings/bindings/python_client/models/collectors_healthy_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/collectors_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/comment.py
 osidb_bindings/bindings/python_client/models/comment_meta_attr.py
-osidb_bindings/bindings/python_client/models/comment_type_enum.py
 osidb_bindings/bindings/python_client/models/cv_ev_5_package_versions.py
 osidb_bindings/bindings/python_client/models/cv_ev_5_versions.py
 osidb_bindings/bindings/python_client/models/epss.py
 osidb_bindings/bindings/python_client/models/erratum.py
 osidb_bindings/bindings/python_client/models/exploit_only_report_data.py
 osidb_bindings/bindings/python_client/models/exploit_only_report_data_source_enum.py
 osidb_bindings/bindings/python_client/models/exploits_api_v1_collect_update_response_200.py
@@ -113,56 +124,72 @@
 osidb_bindings/bindings/python_client/models/exploits_api_v1_report_pending_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/exploits_api_v1_report_pending_retrieve_response_200_pending_actions_item.py
 osidb_bindings/bindings/python_client/models/exploits_api_v1_status_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/exploits_api_v1_supported_products_list_response_200.py
 osidb_bindings/bindings/python_client/models/flaw.py
 osidb_bindings/bindings/python_client/models/flaw_classification.py
 osidb_bindings/bindings/python_client/models/flaw_classification_state.py
+osidb_bindings/bindings/python_client/models/flaw_comment.py
+osidb_bindings/bindings/python_client/models/flaw_comment_post.py
+osidb_bindings/bindings/python_client/models/flaw_comment_post_meta_attr.py
+osidb_bindings/bindings/python_client/models/flaw_comment_type.py
 osidb_bindings/bindings/python_client/models/flaw_meta_attr.py
+osidb_bindings/bindings/python_client/models/flaw_meta_type.py
 osidb_bindings/bindings/python_client/models/flaw_post.py
 osidb_bindings/bindings/python_client/models/flaw_post_classification.py
 osidb_bindings/bindings/python_client/models/flaw_post_classification_state.py
 osidb_bindings/bindings/python_client/models/flaw_post_meta_attr.py
+osidb_bindings/bindings/python_client/models/flaw_reference.py
+osidb_bindings/bindings/python_client/models/flaw_reference_post.py
+osidb_bindings/bindings/python_client/models/flaw_reference_type.py
 osidb_bindings/bindings/python_client/models/flaw_report_data.py
+osidb_bindings/bindings/python_client/models/flaw_type.py
 osidb_bindings/bindings/python_client/models/impact_enum.py
 osidb_bindings/bindings/python_client/models/jira_comment.py
 osidb_bindings/bindings/python_client/models/jira_issue.py
 osidb_bindings/bindings/python_client/models/jira_issue_fields.py
 osidb_bindings/bindings/python_client/models/jira_issue_query_result.py
 osidb_bindings/bindings/python_client/models/jira_issue_type.py
 osidb_bindings/bindings/python_client/models/jira_user.py
 osidb_bindings/bindings/python_client/models/maturity_preliminary_enum.py
 osidb_bindings/bindings/python_client/models/meta.py
 osidb_bindings/bindings/python_client/models/meta_meta_attr.py
-osidb_bindings/bindings/python_client/models/meta_type_enum.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_create_response_201.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_destroy_response_204.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_affectedness.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_flaw_impact.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_flaw_source.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_flaw_type.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_impact.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_order_item.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_resolution.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_response_200.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_trackers_type.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_list_type.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_affects_update_response_200.py
+osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_comments_create_response_201.py
+osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_comments_list_response_200.py
+osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_comments_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_create_response_201.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_affectedness.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_impact.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_resolution.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_trackers_type.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_affects_type.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_impact.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_order_item.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_response_200.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_source.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_list_type.py
+osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_references_create_response_201.py
+osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_references_destroy_response_204.py
+osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_references_list_response_200.py
+osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_references_retrieve_response_200.py
+osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_references_update_response_200.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_flaws_update_response_200.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_manifest_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_schema_retrieve_format.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_schema_retrieve_lang.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_schema_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/osidb_api_v1_status_retrieve_response_200.py
@@ -186,39 +213,44 @@
 osidb_bindings/bindings/python_client/models/osim_api_v1_workflows_retrieve_2_response_200.py
 osidb_bindings/bindings/python_client/models/osim_api_v1_workflows_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/osim_healthy_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/osim_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/paginated_affect_list.py
 osidb_bindings/bindings/python_client/models/paginated_epss_list.py
 osidb_bindings/bindings/python_client/models/paginated_exploit_only_report_data_list.py
+osidb_bindings/bindings/python_client/models/paginated_flaw_comment_list.py
 osidb_bindings/bindings/python_client/models/paginated_flaw_list.py
+osidb_bindings/bindings/python_client/models/paginated_flaw_reference_list.py
 osidb_bindings/bindings/python_client/models/paginated_flaw_report_data_list.py
 osidb_bindings/bindings/python_client/models/paginated_supported_products_list.py
 osidb_bindings/bindings/python_client/models/paginated_tracker_list.py
 osidb_bindings/bindings/python_client/models/resolution_enum.py
 osidb_bindings/bindings/python_client/models/source_666_enum.py
 osidb_bindings/bindings/python_client/models/status_enum.py
 osidb_bindings/bindings/python_client/models/supported_products.py
 osidb_bindings/bindings/python_client/models/taskman_api_v1_group_create_response_200.py
 osidb_bindings/bindings/python_client/models/taskman_api_v1_group_retrieve_response_200.py
-osidb_bindings/bindings/python_client/models/taskman_api_v1_group_update_response_204.py
+osidb_bindings/bindings/python_client/models/taskman_api_v1_group_update_response_200.py
+osidb_bindings/bindings/python_client/models/taskman_api_v1_task_assignee_retrieve_response_200.py
+osidb_bindings/bindings/python_client/models/taskman_api_v1_task_assignee_update_response_200.py
 osidb_bindings/bindings/python_client/models/taskman_api_v1_task_comment_create_response_200.py
 osidb_bindings/bindings/python_client/models/taskman_api_v1_task_comment_update_response_200.py
 osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_create_response_200.py
 osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_retrieve_response_200.py
-osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_update_response_204.py
+osidb_bindings/bindings/python_client/models/taskman_api_v1_task_flaw_update_response_200.py
 osidb_bindings/bindings/python_client/models/taskman_api_v1_task_retrieve_response_200.py
-osidb_bindings/bindings/python_client/models/taskman_api_v1_task_status_update_response_204.py
+osidb_bindings/bindings/python_client/models/taskman_api_v1_task_status_update_reason.py
+osidb_bindings/bindings/python_client/models/taskman_api_v1_task_status_update_resolution.py
+osidb_bindings/bindings/python_client/models/taskman_api_v1_task_status_update_response_200.py
 osidb_bindings/bindings/python_client/models/taskman_api_v1_task_status_update_status.py
+osidb_bindings/bindings/python_client/models/taskman_api_v1_task_unassigned_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/taskman_healthy_retrieve_response_200.py
 osidb_bindings/bindings/python_client/models/token_obtain_pair.py
 osidb_bindings/bindings/python_client/models/token_refresh.py
 osidb_bindings/bindings/python_client/models/token_verify.py
 osidb_bindings/bindings/python_client/models/tracker.py
 osidb_bindings/bindings/python_client/models/tracker_meta_attr.py
 osidb_bindings/bindings/python_client/models/tracker_report_data.py
-osidb_bindings/bindings/python_client/models/type_0d0_enum.py
-osidb_bindings/bindings/python_client/models/type_5b2_enum.py
-osidb_bindings/bindings/python_client/models/type_824_enum.py
+osidb_bindings/bindings/python_client/models/tracker_type.py
 tests/__init__.py
 tests/conftest.py
 tests/test_core.py
```

### Comparing `osidb-bindings-3.1.0/setup.py` & `osidb-bindings-3.3.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import find_packages, setup
 
 with open("README.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
 
 setup(
     name="osidb-bindings",
-    version="3.1.0",
+    version="3.3.0",
     author="Jakub Frejlach, Red Hat Product Security",
     author_email="jfrejlac@redhat.com",
     description="Python bindings for accessing OSIDB API",
     url="https://github.com/RedHatProductSecurity/osidb-bindings",
     project_urls={
         "Changelog": "https://github.com/RedHatProductSecurity/osidb-bindings/blob/master/CHANGELOG.md",
         "Documentation": "https://github.com/RedHatProductSecurity/osidb-bindings/blob/master/TUTORIAL.md",
```


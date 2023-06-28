# Comparing `tmp/rhoas_sdks-1.0.2b2.tar.gz` & `tmp/rhoas_sdks-1.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "rhoas_sdks-1.0.2b2.tar", max compression
+gzip compressed data, was "rhoas_sdks-1.0.3.tar", max compression
```

## Comparing `rhoas_sdks-1.0.2b2.tar` & `rhoas_sdks-1.0.3.tar`

### file list

```diff
@@ -1,373 +1,376 @@
--rw-r--r--   0        0        0      119 2023-03-29 10:40:27.630118 rhoas_sdks-1.0.2b2/auth/constants.py
--rw-r--r--   0        0        0      739 2023-03-29 10:40:27.630118 rhoas_sdks-1.0.2b2/auth/rhoas_auth.py
--rw-r--r--   0        0        0    13055 2023-03-29 10:40:27.630118 rhoas_sdks-1.0.2b2/docs/README.md
--rw-r--r--   0        0        0     1106 2023-03-29 10:43:42.539419 rhoas_sdks-1.0.2b2/pyproject.toml
--rw-r--r--   0        0        0      856 2023-03-29 10:40:27.634118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/__init__.py
--rw-r--r--   0        0        0      238 2023-03-29 10:40:27.634118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/__init__.py
--rw-r--r--   0        0        0    46289 2023-03-29 10:40:27.634118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_clusters_api.py
--rw-r--r--   0        0        0    20339 2023-03-29 10:40:27.634118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_namespaces_api.py
--rw-r--r--   0        0        0     5593 2023-03-29 10:40:27.634118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_service_api.py
--rw-r--r--   0        0        0    22768 2023-03-29 10:40:27.634118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_types_api.py
--rw-r--r--   0        0        0    30236 2023-03-29 10:40:27.634118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connectors_api.py
--rw-r--r--   0        0        0    39197 2023-03-29 10:40:27.634118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api_client.py
--rw-r--r--   0        0        0      864 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/apis/__init__.py
--rw-r--r--   0        0        0    16938 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/configuration.py
--rw-r--r--   0        0        0     5108 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/exceptions.py
--rw-r--r--   0        0        0      358 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/__init__.py
--rw-r--r--   0        0        0    11633 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/addon_parameter.py
--rw-r--r--   0        0        0    12084 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/addon_parameter_list.py
--rw-r--r--   0        0        0    11602 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/channel.py
--rw-r--r--   0        0        0    18979 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector.py
--rw-r--r--   0        0        0    16118 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster.py
--rw-r--r--   0        0        0    14477 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_list.py
--rw-r--r--   0        0        0    11742 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_list_all_of.py
--rw-r--r--   0        0        0    14971 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_meta.py
--rw-r--r--   0        0        0    14209 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_request.py
--rw-r--r--   0        0        0    12035 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_request_meta.py
--rw-r--r--   0        0        0    12114 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_state.py
--rw-r--r--   0        0        0    11818 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_status.py
--rw-r--r--   0        0        0    11964 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_status_status.py
--rw-r--r--   0        0        0    13260 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_configuration.py
--rw-r--r--   0        0        0    12174 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_desired_state.py
--rw-r--r--   0        0        0    14370 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_list.py
--rw-r--r--   0        0        0    11671 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_list_all_of.py
--rw-r--r--   0        0        0    16328 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_meta.py
--rw-r--r--   0        0        0    11532 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_meta_all_of.py
--rw-r--r--   0        0        0    17393 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace.py
--rw-r--r--   0        0        0    13045 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_all_of.py
--rw-r--r--   0        0        0    14648 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_eval_request.py
--rw-r--r--   0        0        0    14507 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_list.py
--rw-r--r--   0        0        0    11762 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_list_all_of.py
--rw-r--r--   0        0        0    16268 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_meta.py
--rw-r--r--   0        0        0    12030 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_meta_all_of.py
--rw-r--r--   0        0        0    14651 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_patch_request.py
--rw-r--r--   0        0        0    12759 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_quota.py
--rw-r--r--   0        0        0    15370 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_request.py
--rw-r--r--   0        0        0    12040 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_request_all_of.py
--rw-r--r--   0        0        0    12452 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_request_meta.py
--rw-r--r--   0        0        0    12198 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_state.py
--rw-r--r--   0        0        0    12562 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_status.py
--rw-r--r--   0        0        0    12148 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_tenant.py
--rw-r--r--   0        0        0    12045 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_tenant_kind.py
--rw-r--r--   0        0        0    16918 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_request.py
--rw-r--r--   0        0        0    13469 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_request_meta.py
--rw-r--r--   0        0        0    11267 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_resource_annotations.py
--rw-r--r--   0        0        0    12699 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_state.py
--rw-r--r--   0        0        0    11747 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_status.py
--rw-r--r--   0        0        0    11893 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_status_status.py
--rw-r--r--   0        0        0    17665 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type.py
--rw-r--r--   0        0        0    15009 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_all_of.py
--rw-r--r--   0        0        0    11895 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_label_count.py
--rw-r--r--   0        0        0    11799 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_label_count_list.py
--rw-r--r--   0        0        0    14432 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_list.py
--rw-r--r--   0        0        0    11712 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_list_all_of.py
--rw-r--r--   0        0        0    11961 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/cpu_quota.py
--rw-r--r--   0        0        0    12452 2023-03-29 10:40:27.638118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/error.py
--rw-r--r--   0        0        0    13789 2023-03-29 10:40:27.642118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/kafka_connection_settings.py
--rw-r--r--   0        0        0    12491 2023-03-29 10:40:27.642118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/list.py
--rw-r--r--   0        0        0    11982 2023-03-29 10:40:27.642118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/memory_quota.py
--rw-r--r--   0        0        0    11904 2023-03-29 10:40:27.642118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/object_meta.py
--rw-r--r--   0        0        0    11809 2023-03-29 10:40:27.642118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/object_reference.py
--rw-r--r--   0        0        0    13816 2023-03-29 10:40:27.642118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/schema_registry_connection_settings.py
--rw-r--r--   0        0        0    11846 2023-03-29 10:40:27.642118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/service_account.py
--rw-r--r--   0        0        0    11692 2023-03-29 10:40:27.642118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/service_connection_settings.py
--rw-r--r--   0        0        0    14576 2023-03-29 10:40:27.642118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/version_metadata.py
--rw-r--r--   0        0        0    11690 2023-03-29 10:40:27.642118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/version_metadata_all_of.py
--rw-r--r--   0        0        0    82645 2023-03-29 10:40:27.642118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model_utils.py
--rw-r--r--   0        0        0     5510 2023-03-29 10:40:27.642118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/models/__init__.py
--rw-r--r--   0        0        0    14345 2023-03-29 10:40:27.642118 rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/rest.py
--rw-r--r--   0        0        0      842 2023-03-29 10:40:27.646118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/__init__.py
--rw-r--r--   0        0        0      225 2023-03-29 10:40:27.646118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/__init__.py
--rw-r--r--   0        0        0    27080 2023-03-29 10:40:27.646118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/acls_api.py
--rw-r--r--   0        0        0    10474 2023-03-29 10:40:27.646118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/errors_api.py
--rw-r--r--   0        0        0    26325 2023-03-29 10:40:27.646118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/groups_api.py
--rw-r--r--   0        0        0    14337 2023-03-29 10:40:27.646118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/records_api.py
--rw-r--r--   0        0        0    28894 2023-03-29 10:40:27.646118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/topics_api.py
--rw-r--r--   0        0        0    39114 2023-03-29 10:40:27.646118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api_client.py
--rw-r--r--   0        0        0      739 2023-03-29 10:40:27.646118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/apis/__init__.py
--rw-r--r--   0        0        0    16782 2023-03-29 10:40:27.646118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/configuration.py
--rw-r--r--   0        0        0     5094 2023-03-29 10:40:27.646118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/exceptions.py
--rw-r--r--   0        0        0      358 2023-03-29 10:40:27.646118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/__init__.py
--rw-r--r--   0        0        0    16700 2023-03-29 10:40:27.646118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding.py
--rw-r--r--   0        0        0    14245 2023-03-29 10:40:27.646118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_all_of.py
--rw-r--r--   0        0        0    14868 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_list_page.py
--rw-r--r--   0        0        0    11728 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_list_page_all_of.py
--rw-r--r--   0        0        0    12427 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_order_key.py
--rw-r--r--   0        0        0    12535 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_operation.py
--rw-r--r--   0        0        0    12607 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_operation_filter.py
--rw-r--r--   0        0        0    11983 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_pattern_type.py
--rw-r--r--   0        0        0    12313 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_pattern_type_filter.py
--rw-r--r--   0        0        0    11956 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_permission_type.py
--rw-r--r--   0        0        0    12028 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_permission_type_filter.py
--rw-r--r--   0        0        0    12166 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_resource_type.py
--rw-r--r--   0        0        0    12238 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_resource_type_filter.py
--rw-r--r--   0        0        0    12195 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/config_entry.py
--rw-r--r--   0        0        0    13848 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer.py
--rw-r--r--   0        0        0    15979 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group.py
--rw-r--r--   0        0        0    13063 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_all_of.py
--rw-r--r--   0        0        0    12181 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_description_order_key.py
--rw-r--r--   0        0        0    15781 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_list.py
--rw-r--r--   0        0        0    11746 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_list_all_of.py
--rw-r--r--   0        0        0    12032 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_metrics.py
--rw-r--r--   0        0        0    11606 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_order_key.py
--rw-r--r--   0        0        0    13012 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_parameters.py
--rw-r--r--   0        0        0    15137 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_result.py
--rw-r--r--   0        0        0    11936 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_result_all_of.py
--rw-r--r--   0        0        0    11902 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_result_item.py
--rw-r--r--   0        0        0    12415 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_state.py
--rw-r--r--   0        0        0    15745 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error.py
--rw-r--r--   0        0        0    12598 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error_all_of.py
--rw-r--r--   0        0        0    14760 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error_list.py
--rw-r--r--   0        0        0    11946 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error_list_all_of.py
--rw-r--r--   0        0        0    12315 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/list.py
--rw-r--r--   0        0        0    15413 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/list_deprecated.py
--rw-r--r--   0        0        0    12133 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/list_deprecated_all_of.py
--rw-r--r--   0        0        0    12140 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/new_topic_input.py
--rw-r--r--   0        0        0    11406 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/node.py
--rw-r--r--   0        0        0    12107 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/object_reference.py
--rw-r--r--   0        0        0    12139 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/offset_type.py
--rw-r--r--   0        0        0    13002 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/partition.py
--rw-r--r--   0        0        0    13571 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/partition_leader.py
--rw-r--r--   0        0        0    16556 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record.py
--rw-r--r--   0        0        0    13502 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_all_of.py
--rw-r--r--   0        0        0    12409 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_included_property.py
--rw-r--r--   0        0        0    14743 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_list.py
--rw-r--r--   0        0        0    12498 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_list_all_of.py
--rw-r--r--   0        0        0    11932 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/sort_direction.py
--rw-r--r--   0        0        0    15627 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic.py
--rw-r--r--   0        0        0    12544 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic_all_of.py
--rw-r--r--   0        0        0    12208 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic_order_key.py
--rw-r--r--   0        0        0    12387 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic_settings.py
--rw-r--r--   0        0        0    15667 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topics_list.py
--rw-r--r--   0        0        0    11668 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topics_list_all_of.py
--rw-r--r--   0        0        0    11728 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topics_to_reset_offset.py
--rw-r--r--   0        0        0    82631 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model_utils.py
--rw-r--r--   0        0        0     4561 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/models/__init__.py
--rw-r--r--   0        0        0    14331 2023-03-29 10:40:27.650118 rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/rest.py
--rw-r--r--   0        0        0      821 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/__init__.py
--rw-r--r--   0        0        0      224 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/__init__.py
--rw-r--r--   0        0        0    74161 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/default_api.py
--rw-r--r--   0        0        0    27032 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/enterprise_dataplane_clusters_api.py
--rw-r--r--   0        0        0    10387 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/errors_api.py
--rw-r--r--   0        0        0    30984 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/security_api.py
--rw-r--r--   0        0        0    39120 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api_client.py
--rw-r--r--   0        0        0      715 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/apis/__init__.py
--rw-r--r--   0        0        0    16928 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/configuration.py
--rw-r--r--   0        0        0     5105 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/exceptions.py
--rw-r--r--   0        0        0      354 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/__init__.py
--rw-r--r--   0        0        0    12840 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_provider.py
--rw-r--r--   0        0        0    14431 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_provider_list.py
--rw-r--r--   0        0        0    11703 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_provider_list_all_of.py
--rw-r--r--   0        0        0    13304 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_region.py
--rw-r--r--   0        0        0    14415 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_region_list.py
--rw-r--r--   0        0        0    11697 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_region_list_all_of.py
--rw-r--r--   0        0        0    17599 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster.py
--rw-r--r--   0        0        0    12522 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_all_of.py
--rw-r--r--   0        0        0    13911 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_all_of_capacity_information.py
--rw-r--r--   0        0        0    14463 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_list.py
--rw-r--r--   0        0        0    11715 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_list_all_of.py
--rw-r--r--   0        0        0    16450 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_list_item.py
--rw-r--r--   0        0        0    14022 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_list_item_all_of.py
--rw-r--r--   0        0        0    17031 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_with_addon_parameters.py
--rw-r--r--   0        0        0    11792 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_with_addon_parameters_all_of.py
--rw-r--r--   0        0        0    14587 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_osd_cluster_payload.py
--rw-r--r--   0        0        0    12986 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/error.py
--rw-r--r--   0        0        0    14287 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/error_list.py
--rw-r--r--   0        0        0    11664 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/error_list_all_of.py
--rw-r--r--   0        0        0    11637 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/fleetshard_parameter.py
--rw-r--r--   0        0        0    11923 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/instant_query.py
--rw-r--r--   0        0        0    13499 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_promote_request.py
--rw-r--r--   0        0        0    25271 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request.py
--rw-r--r--   0        0        0    22920 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_all_of.py
--rw-r--r--   0        0        0    14423 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_list.py
--rw-r--r--   0        0        0    11700 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_list_all_of.py
--rw-r--r--   0        0        0    14946 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_payload.py
--rw-r--r--   0        0        0    12125 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_update_request.py
--rw-r--r--   0        0        0    12042 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/list.py
--rw-r--r--   0        0        0    14257 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_instant_query_list.py
--rw-r--r--   0        0        0    12019 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_instant_query_list_all_of.py
--rw-r--r--   0        0        0    14241 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_range_query_list.py
--rw-r--r--   0        0        0    12013 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_range_query_list_all_of.py
--rw-r--r--   0        0        0    11852 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/object_reference.py
--rw-r--r--   0        0        0    11834 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/range_query.py
--rw-r--r--   0        0        0    12233 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/region_capacity_list_item.py
--rw-r--r--   0        0        0    15548 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account.py
--rw-r--r--   0        0        0    12995 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_all_of.py
--rw-r--r--   0        0        0    13948 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list.py
--rw-r--r--   0        0        0    11896 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list_all_of.py
--rw-r--r--   0        0        0    15787 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list_item.py
--rw-r--r--   0        0        0    13192 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list_item_all_of.py
--rw-r--r--   0        0        0    11867 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_request.py
--rw-r--r--   0        0        0    15032 2023-03-29 10:40:27.658118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/sso_provider.py
--rw-r--r--   0        0        0    12324 2023-03-29 10:40:27.662118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/sso_provider_all_of.py
--rw-r--r--   0        0        0    13258 2023-03-29 10:40:27.662118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_billing_model.py
--rw-r--r--   0        0        0    13608 2023-03-29 10:40:27.662118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_type.py
--rw-r--r--   0        0        0    20642 2023-03-29 10:40:27.662118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_type_sizes_inner.py
--rw-r--r--   0        0        0    14021 2023-03-29 10:40:27.662118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_types_list.py
--rw-r--r--   0        0        0    11742 2023-03-29 10:40:27.662118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_types_list_all_of.py
--rw-r--r--   0        0        0    18452 2023-03-29 10:40:27.662118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_size.py
--rw-r--r--   0        0        0    11508 2023-03-29 10:40:27.662118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_size_bytes_value_item.py
--rw-r--r--   0        0        0    11687 2023-03-29 10:40:27.662118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/values.py
--rw-r--r--   0        0        0    14635 2023-03-29 10:40:27.662118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/version_metadata.py
--rw-r--r--   0        0        0    11907 2023-03-29 10:40:27.662118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/version_metadata_all_of.py
--rw-r--r--   0        0        0    82638 2023-03-29 10:40:27.662118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model_utils.py
--rw-r--r--   0        0        0     5048 2023-03-29 10:40:27.662118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/models/__init__.py
--rw-r--r--   0        0        0    14338 2023-03-29 10:40:27.662118 rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/rest.py
--rw-r--r--   0        0        0     2084 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/__init__.py
--rw-r--r--   0        0        0      229 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/__init__.py
--rw-r--r--   0        0        0   116696 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/admin_api.py
--rw-r--r--   0        0        0    47524 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/artifact_rules_api.py
--rw-r--r--   0        0        0    88699 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/artifacts_api.py
--rw-r--r--   0        0        0    23764 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/groups_api.py
--rw-r--r--   0        0        0    53083 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/metadata_api.py
--rw-r--r--   0        0        0    17954 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/search_api.py
--rw-r--r--   0        0        0    11617 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/system_api.py
--rw-r--r--   0        0        0     6836 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/users_api.py
--rw-r--r--   0        0        0    45777 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/versions_api.py
--rw-r--r--   0        0        0    40377 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api_client.py
--rw-r--r--   0        0        0     1046 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/apis/__init__.py
--rw-r--r--   0        0        0    17456 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/configuration.py
--rw-r--r--   0        0        0     6312 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/exceptions.py
--rw-r--r--   0        0        0      361 2023-03-29 10:40:27.666118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/__init__.py
--rw-r--r--   0        0        0    16767 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_meta_data.py
--rw-r--r--   0        0        0    12672 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_owner.py
--rw-r--r--   0        0        0    13413 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_reference.py
--rw-r--r--   0        0        0    13610 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_search_results.py
--rw-r--r--   0        0        0    13816 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_state.py
--rw-r--r--   0        0        0    12676 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_type_info.py
--rw-r--r--   0        0        0    13598 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/configuration_property.py
--rw-r--r--   0        0        0    13547 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/content_create_request.py
--rw-r--r--   0        0        0    13326 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/create_group_meta_data.py
--rw-r--r--   0        0        0    12957 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/download_ref.py
--rw-r--r--   0        0        0    13493 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/editable_meta_data.py
--rw-r--r--   0        0        0    13676 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/error.py
--rw-r--r--   0        0        0    14548 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/group_meta_data.py
--rw-r--r--   0        0        0    13529 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/group_search_results.py
--rw-r--r--   0        0        0    13371 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/if_exists.py
--rw-r--r--   0        0        0    15923 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/limits.py
--rw-r--r--   0        0        0    12914 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/log_configuration.py
--rw-r--r--   0        0        0    13773 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/log_level.py
--rw-r--r--   0        0        0    15316 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/named_log_configuration.py
--rw-r--r--   0        0        0    12750 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/named_log_configuration_all_of.py
--rw-r--r--   0        0        0    12423 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/properties.py
--rw-r--r--   0        0        0    13466 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/role_mapping.py
--rw-r--r--   0        0        0    13281 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/role_type.py
--rw-r--r--   0        0        0    13067 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule.py
--rw-r--r--   0        0        0    13233 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_type.py
--rw-r--r--   0        0        0    12910 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_violation_cause.py
--rw-r--r--   0        0        0    16461 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_violation_error.py
--rw-r--r--   0        0        0    13085 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_violation_error_all_of.py
--rw-r--r--   0        0        0    15207 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/searched_artifact.py
--rw-r--r--   0        0        0    14104 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/searched_group.py
--rw-r--r--   0        0        0    15782 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/searched_version.py
--rw-r--r--   0        0        0    13179 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/sort_by.py
--rw-r--r--   0        0        0    13152 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/sort_order.py
--rw-r--r--   0        0        0    13276 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/system_info.py
--rw-r--r--   0        0        0    12762 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/update_configuration_property.py
--rw-r--r--   0        0        0    12885 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/update_role.py
--rw-r--r--   0        0        0    12934 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/update_state.py
--rw-r--r--   0        0        0    13472 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/user_info.py
--rw-r--r--   0        0        0    15795 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/version_meta_data.py
--rw-r--r--   0        0        0    13587 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/version_search_results.py
--rw-r--r--   0        0        0    83852 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model_utils.py
--rw-r--r--   0        0        0     3494 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/models/__init__.py
--rw-r--r--   0        0        0    15552 2023-03-29 10:40:27.670118 rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/rest.py
--rw-r--r--   0        0        0     1078 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/__init__.py
--rw-r--r--   0        0        0      234 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api/__init__.py
--rw-r--r--   0        0        0     5947 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api/default_api.py
--rw-r--r--   0        0        0    11488 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api/errors_api.py
--rw-r--r--   0        0        0    23774 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api/registries_api.py
--rw-r--r--   0        0        0    39320 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api_client.py
--rw-r--r--   0        0        0      659 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/apis/__init__.py
--rw-r--r--   0        0        0    17118 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/configuration.py
--rw-r--r--   0        0        0     5274 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/exceptions.py
--rw-r--r--   0        0        0      365 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/__init__.py
--rw-r--r--   0        0        0    12257 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/abstract_list.py
--rw-r--r--   0        0        0    11829 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/empty.py
--rw-r--r--   0        0        0    14633 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error.py
--rw-r--r--   0        0        0    12100 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error_all_of.py
--rw-r--r--   0        0        0    14552 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error_list.py
--rw-r--r--   0        0        0    11866 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error_list_all_of.py
--rw-r--r--   0        0        0    14582 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/list.py
--rw-r--r--   0        0        0    11922 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/list_all_of.py
--rw-r--r--   0        0        0    12043 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/object_reference.py
--rw-r--r--   0        0        0    17009 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry.py
--rw-r--r--   0        0        0    12507 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_create.py
--rw-r--r--   0        0        0    13176 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_instance_type_value.py
--rw-r--r--   0        0        0    14597 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_list.py
--rw-r--r--   0        0        0    11896 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_list_all_of.py
--rw-r--r--   0        0        0    14374 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_status_value.py
--rw-r--r--   0        0        0    14892 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/root_type_for_registry.py
--rw-r--r--   0        0        0    12041 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/service_status.py
--rw-r--r--   0        0        0    82818 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model_utils.py
--rw-r--r--   0        0        0     1721 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/models/__init__.py
--rw-r--r--   0        0        0    14518 2023-03-29 10:40:27.674118 rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/rest.py
--rw-r--r--   0        0        0      921 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/__init__.py
--rw-r--r--   0        0        0      238 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api/__init__.py
--rw-r--r--   0        0        0    11813 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api/acs_tenants_api.py
--rw-r--r--   0        0        0    11471 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api/default_api.py
--rw-r--r--   0        0        0    34067 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api/service_accounts_api.py
--rw-r--r--   0        0        0    39199 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api_client.py
--rw-r--r--   0        0        0      688 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/apis/__init__.py
--rw-r--r--   0        0        0    17479 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/configuration.py
--rw-r--r--   0        0        0     5117 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/exceptions.py
--rw-r--r--   0        0        0      365 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/__init__.py
--rw-r--r--   0        0        0    12294 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/acs_client_request_data.py
--rw-r--r--   0        0        0    12101 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/acs_client_response_data.py
--rw-r--r--   0        0        0    11652 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/authentication_factors.py
--rw-r--r--   0        0        0    11870 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/authentication_policy.py
--rw-r--r--   0        0        0    11557 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/error.py
--rw-r--r--   0        0        0    11473 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/otp.py
--rw-r--r--   0        0        0    12719 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/red_hat_error_representation.py
--rw-r--r--   0        0        0    11979 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/service_account_create_request_data.py
--rw-r--r--   0        0        0    12824 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/service_account_data.py
--rw-r--r--   0        0        0    11919 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/service_account_request_data.py
--rw-r--r--   0        0        0    11976 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/validation_exception_data.py
--rw-r--r--   0        0        0    82661 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model_utils.py
--rw-r--r--   0        0        0     1411 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/models/__init__.py
--rw-r--r--   0        0        0    14361 2023-03-29 10:40:27.678118 rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/rest.py
--rw-r--r--   0        0        0      906 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/__init__.py
--rw-r--r--   0        0        0      231 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/__init__.py
--rw-r--r--   0        0        0    22654 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/bridges_api.py
--rw-r--r--   0        0        0    17973 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/cloud_providers_api.py
--rw-r--r--   0        0        0    11522 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/error_catalog_api.py
--rw-r--r--   0        0        0    30966 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/processors_api.py
--rw-r--r--   0        0        0    31097 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/sink_connectors_api.py
--rw-r--r--   0        0        0    31340 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/source_connectors_api.py
--rw-r--r--   0        0        0    39229 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api_client.py
--rw-r--r--   0        0        0      908 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/apis/__init__.py
--rw-r--r--   0        0        0    16974 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/configuration.py
--rw-r--r--   0        0        0     5134 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/exceptions.py
--rw-r--r--   0        0        0      361 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/__init__.py
--rw-r--r--   0        0        0    12252 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_error.py
--rw-r--r--   0        0        0    12454 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_error_instance.py
--rw-r--r--   0        0        0    12014 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_error_type.py
--rw-r--r--   0        0        0    12543 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_list_response.py
--rw-r--r--   0        0        0    12474 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_request.py
--rw-r--r--   0        0        0    15062 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_response.py
--rw-r--r--   0        0        0    12614 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_provider_list_response.py
--rw-r--r--   0        0        0    12897 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_provider_response.py
--rw-r--r--   0        0        0    12594 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_region_list_response.py
--rw-r--r--   0        0        0    12243 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_region_response.py
--rw-r--r--   0        0        0    12627 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/connector_request.py
--rw-r--r--   0        0        0    12735 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/error.py
--rw-r--r--   0        0        0    12476 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/error_list_response.py
--rw-r--r--   0        0        0    11874 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/errors_list.py
--rw-r--r--   0        0        0    14500 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/list.py
--rw-r--r--   0        0        0    11910 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/list_all_of.py
--rw-r--r--   0        0        0    11915 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/list_response.py
--rw-r--r--   0        0        0    12980 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/managed_resource_status.py
--rw-r--r--   0        0        0    12375 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/object_reference.py
--rw-r--r--   0        0        0    12634 2023-03-29 10:40:27.682118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processing_error_list_response.py
--rw-r--r--   0        0        0    12183 2023-03-29 10:40:27.686118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processing_error_response.py
--rw-r--r--   0        0        0    12573 2023-03-29 10:40:27.686118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processor_list_response.py
--rw-r--r--   0        0        0    12220 2023-03-29 10:40:27.686118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processor_request.py
--rw-r--r--   0        0        0    14580 2023-03-29 10:40:27.686118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processor_response.py
--rw-r--r--   0        0        0    12614 2023-03-29 10:40:27.686118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/sink_connector_list_response.py
--rw-r--r--   0        0        0    15396 2023-03-29 10:40:27.686118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/sink_connector_response.py
--rw-r--r--   0        0        0    12634 2023-03-29 10:40:27.686118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/source_connector_list_response.py
--rw-r--r--   0        0        0    15063 2023-03-29 10:40:27.686118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/source_connector_response.py
--rw-r--r--   0        0        0    82674 2023-03-29 10:40:27.686118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model_utils.py
--rw-r--r--   0        0        0     2755 2023-03-29 10:40:27.686118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/models/__init__.py
--rw-r--r--   0        0        0    14374 2023-03-29 10:40:27.686118 rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/rest.py
--rw-r--r--   0        0        0    13669 1970-01-01 00:00:00.000000 rhoas_sdks-1.0.2b2/PKG-INFO
+-rw-r--r--   0        0        0      119 2023-06-28 11:20:46.735591 rhoas_sdks-1.0.3/auth/constants.py
+-rw-r--r--   0        0        0      739 2023-06-28 11:20:46.735591 rhoas_sdks-1.0.3/auth/rhoas_auth.py
+-rw-r--r--   0        0        0    13014 2023-06-28 11:20:46.735591 rhoas_sdks-1.0.3/docs/README.md
+-rw-r--r--   0        0        0     1100 2023-06-28 11:22:05.519981 rhoas_sdks-1.0.3/pyproject.toml
+-rw-r--r--   0        0        0      856 2023-06-28 11:20:46.735591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/__init__.py
+-rw-r--r--   0        0        0      238 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/__init__.py
+-rw-r--r--   0        0        0    46289 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_clusters_api.py
+-rw-r--r--   0        0        0    20339 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_namespaces_api.py
+-rw-r--r--   0        0        0     5593 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_service_api.py
+-rw-r--r--   0        0        0    22768 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_types_api.py
+-rw-r--r--   0        0        0    30236 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connectors_api.py
+-rw-r--r--   0        0        0    39197 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api_client.py
+-rw-r--r--   0        0        0      864 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/apis/__init__.py
+-rw-r--r--   0        0        0    16938 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/configuration.py
+-rw-r--r--   0        0        0     5108 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/exceptions.py
+-rw-r--r--   0        0        0      358 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/__init__.py
+-rw-r--r--   0        0        0    11633 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/addon_parameter.py
+-rw-r--r--   0        0        0    12084 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/addon_parameter_list.py
+-rw-r--r--   0        0        0    11602 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/channel.py
+-rw-r--r--   0        0        0    18979 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector.py
+-rw-r--r--   0        0        0    16118 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster.py
+-rw-r--r--   0        0        0    14477 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_list.py
+-rw-r--r--   0        0        0    11742 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_list_all_of.py
+-rw-r--r--   0        0        0    14971 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_meta.py
+-rw-r--r--   0        0        0    14209 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_request.py
+-rw-r--r--   0        0        0    12035 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_request_meta.py
+-rw-r--r--   0        0        0    12114 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_state.py
+-rw-r--r--   0        0        0    11818 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_status.py
+-rw-r--r--   0        0        0    11964 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_status_status.py
+-rw-r--r--   0        0        0    13260 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_configuration.py
+-rw-r--r--   0        0        0    12174 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_desired_state.py
+-rw-r--r--   0        0        0    14370 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_list.py
+-rw-r--r--   0        0        0    11671 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_list_all_of.py
+-rw-r--r--   0        0        0    16328 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_meta.py
+-rw-r--r--   0        0        0    11532 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_meta_all_of.py
+-rw-r--r--   0        0        0    17393 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace.py
+-rw-r--r--   0        0        0    13045 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_all_of.py
+-rw-r--r--   0        0        0    14648 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_eval_request.py
+-rw-r--r--   0        0        0    14507 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_list.py
+-rw-r--r--   0        0        0    11762 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_list_all_of.py
+-rw-r--r--   0        0        0    16268 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_meta.py
+-rw-r--r--   0        0        0    12030 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_meta_all_of.py
+-rw-r--r--   0        0        0    14651 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_patch_request.py
+-rw-r--r--   0        0        0    12759 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_quota.py
+-rw-r--r--   0        0        0    15370 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_request.py
+-rw-r--r--   0        0        0    12040 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_request_all_of.py
+-rw-r--r--   0        0        0    12452 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_request_meta.py
+-rw-r--r--   0        0        0    12198 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_state.py
+-rw-r--r--   0        0        0    12562 2023-06-28 11:20:46.739591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_status.py
+-rw-r--r--   0        0        0    12148 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_tenant.py
+-rw-r--r--   0        0        0    12045 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_tenant_kind.py
+-rw-r--r--   0        0        0    16918 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_request.py
+-rw-r--r--   0        0        0    13469 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_request_meta.py
+-rw-r--r--   0        0        0    11267 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_resource_annotations.py
+-rw-r--r--   0        0        0    12699 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_state.py
+-rw-r--r--   0        0        0    11747 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_status.py
+-rw-r--r--   0        0        0    11893 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_status_status.py
+-rw-r--r--   0        0        0    17665 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type.py
+-rw-r--r--   0        0        0    15009 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_all_of.py
+-rw-r--r--   0        0        0    11895 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_label_count.py
+-rw-r--r--   0        0        0    11799 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_label_count_list.py
+-rw-r--r--   0        0        0    14432 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_list.py
+-rw-r--r--   0        0        0    11712 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_list_all_of.py
+-rw-r--r--   0        0        0    11961 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/cpu_quota.py
+-rw-r--r--   0        0        0    12452 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/error.py
+-rw-r--r--   0        0        0    13789 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/kafka_connection_settings.py
+-rw-r--r--   0        0        0    12053 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/list.py
+-rw-r--r--   0        0        0    11982 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/memory_quota.py
+-rw-r--r--   0        0        0    11904 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/object_meta.py
+-rw-r--r--   0        0        0    11809 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/object_reference.py
+-rw-r--r--   0        0        0    13816 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/schema_registry_connection_settings.py
+-rw-r--r--   0        0        0    11846 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/service_account.py
+-rw-r--r--   0        0        0    11692 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/service_connection_settings.py
+-rw-r--r--   0        0        0    14441 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/version_metadata.py
+-rw-r--r--   0        0        0    11750 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/version_metadata_all_of.py
+-rw-r--r--   0        0        0    82645 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model_utils.py
+-rw-r--r--   0        0        0     5510 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/models/__init__.py
+-rw-r--r--   0        0        0    14345 2023-06-28 11:20:46.743591 rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/rest.py
+-rw-r--r--   0        0        0      842 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/__init__.py
+-rw-r--r--   0        0        0      225 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/__init__.py
+-rw-r--r--   0        0        0    27080 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/acls_api.py
+-rw-r--r--   0        0        0    10474 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/errors_api.py
+-rw-r--r--   0        0        0    26325 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/groups_api.py
+-rw-r--r--   0        0        0    14337 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/records_api.py
+-rw-r--r--   0        0        0    28894 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/topics_api.py
+-rw-r--r--   0        0        0    39114 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api_client.py
+-rw-r--r--   0        0        0      739 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/apis/__init__.py
+-rw-r--r--   0        0        0    16782 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/configuration.py
+-rw-r--r--   0        0        0     5094 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/exceptions.py
+-rw-r--r--   0        0        0      358 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/__init__.py
+-rw-r--r--   0        0        0    16700 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding.py
+-rw-r--r--   0        0        0    14245 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_all_of.py
+-rw-r--r--   0        0        0    14868 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_list_page.py
+-rw-r--r--   0        0        0    11728 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_list_page_all_of.py
+-rw-r--r--   0        0        0    12427 2023-06-28 11:20:46.751591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_order_key.py
+-rw-r--r--   0        0        0    12535 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_operation.py
+-rw-r--r--   0        0        0    12607 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_operation_filter.py
+-rw-r--r--   0        0        0    11983 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_pattern_type.py
+-rw-r--r--   0        0        0    12313 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_pattern_type_filter.py
+-rw-r--r--   0        0        0    11956 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_permission_type.py
+-rw-r--r--   0        0        0    12028 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_permission_type_filter.py
+-rw-r--r--   0        0        0    12166 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_resource_type.py
+-rw-r--r--   0        0        0    12238 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_resource_type_filter.py
+-rw-r--r--   0        0        0    12195 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/config_entry.py
+-rw-r--r--   0        0        0    13848 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer.py
+-rw-r--r--   0        0        0    15979 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group.py
+-rw-r--r--   0        0        0    13063 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_all_of.py
+-rw-r--r--   0        0        0    12181 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_description_order_key.py
+-rw-r--r--   0        0        0    15781 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_list.py
+-rw-r--r--   0        0        0    11746 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_list_all_of.py
+-rw-r--r--   0        0        0    12032 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_metrics.py
+-rw-r--r--   0        0        0    11606 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_order_key.py
+-rw-r--r--   0        0        0    13012 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_parameters.py
+-rw-r--r--   0        0        0    15137 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_result.py
+-rw-r--r--   0        0        0    11936 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_result_all_of.py
+-rw-r--r--   0        0        0    11902 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_result_item.py
+-rw-r--r--   0        0        0    12415 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_state.py
+-rw-r--r--   0        0        0    15745 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error.py
+-rw-r--r--   0        0        0    12598 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error_all_of.py
+-rw-r--r--   0        0        0    14760 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error_list.py
+-rw-r--r--   0        0        0    11946 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error_list_all_of.py
+-rw-r--r--   0        0        0    12315 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/list.py
+-rw-r--r--   0        0        0    15413 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/list_deprecated.py
+-rw-r--r--   0        0        0    12133 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/list_deprecated_all_of.py
+-rw-r--r--   0        0        0    12140 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/new_topic_input.py
+-rw-r--r--   0        0        0    11406 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/node.py
+-rw-r--r--   0        0        0    12107 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/object_reference.py
+-rw-r--r--   0        0        0    12139 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/offset_type.py
+-rw-r--r--   0        0        0    13002 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/partition.py
+-rw-r--r--   0        0        0    13571 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/partition_leader.py
+-rw-r--r--   0        0        0    16556 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record.py
+-rw-r--r--   0        0        0    13502 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_all_of.py
+-rw-r--r--   0        0        0    12409 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_included_property.py
+-rw-r--r--   0        0        0    14743 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_list.py
+-rw-r--r--   0        0        0    12498 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_list_all_of.py
+-rw-r--r--   0        0        0    11932 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/sort_direction.py
+-rw-r--r--   0        0        0    15627 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic.py
+-rw-r--r--   0        0        0    12544 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic_all_of.py
+-rw-r--r--   0        0        0    12208 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic_order_key.py
+-rw-r--r--   0        0        0    12387 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic_settings.py
+-rw-r--r--   0        0        0    15667 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topics_list.py
+-rw-r--r--   0        0        0    11668 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topics_list_all_of.py
+-rw-r--r--   0        0        0    11728 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topics_to_reset_offset.py
+-rw-r--r--   0        0        0    82631 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model_utils.py
+-rw-r--r--   0        0        0     4561 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/models/__init__.py
+-rw-r--r--   0        0        0    14331 2023-06-28 11:20:46.755591 rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/rest.py
+-rw-r--r--   0        0        0      821 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/__init__.py
+-rw-r--r--   0        0        0      224 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/__init__.py
+-rw-r--r--   0        0        0    74161 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/default_api.py
+-rw-r--r--   0        0        0    27109 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/enterprise_dataplane_clusters_api.py
+-rw-r--r--   0        0        0    10387 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/errors_api.py
+-rw-r--r--   0        0        0    30984 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/security_api.py
+-rw-r--r--   0        0        0    39120 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api_client.py
+-rw-r--r--   0        0        0      715 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/apis/__init__.py
+-rw-r--r--   0        0        0    16928 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/configuration.py
+-rw-r--r--   0        0        0     5105 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/exceptions.py
+-rw-r--r--   0        0        0      354 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/__init__.py
+-rw-r--r--   0        0        0    12840 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_provider.py
+-rw-r--r--   0        0        0    14431 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_provider_list.py
+-rw-r--r--   0        0        0    11703 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_provider_list_all_of.py
+-rw-r--r--   0        0        0    13304 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_region.py
+-rw-r--r--   0        0        0    14415 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_region_list.py
+-rw-r--r--   0        0        0    11697 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_region_list_all_of.py
+-rw-r--r--   0        0        0    17547 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster.py
+-rw-r--r--   0        0        0    14650 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_addon_parameters.py
+-rw-r--r--   0        0        0    15225 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_all_of.py
+-rw-r--r--   0        0        0    13911 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_all_of_capacity_information.py
+-rw-r--r--   0        0        0    11901 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_fleetshard_parameters.py
+-rw-r--r--   0        0        0    14463 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_list.py
+-rw-r--r--   0        0        0    11715 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_list_all_of.py
+-rw-r--r--   0        0        0    18189 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_registration_response.py
+-rw-r--r--   0        0        0    14587 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_osd_cluster_payload.py
+-rw-r--r--   0        0        0    12986 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/error.py
+-rw-r--r--   0        0        0    14287 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/error_list.py
+-rw-r--r--   0        0        0    11664 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/error_list_all_of.py
+-rw-r--r--   0        0        0    11637 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/fleetshard_parameter.py
+-rw-r--r--   0        0        0    12215 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/fleetshard_parameters_array.py
+-rw-r--r--   0        0        0    11923 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/instant_query.py
+-rw-r--r--   0        0        0    13499 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_promote_request.py
+-rw-r--r--   0        0        0    25271 2023-06-28 11:20:46.763591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request.py
+-rw-r--r--   0        0        0    22920 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_all_of.py
+-rw-r--r--   0        0        0    14423 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_list.py
+-rw-r--r--   0        0        0    11700 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_list_all_of.py
+-rw-r--r--   0        0        0    14946 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_payload.py
+-rw-r--r--   0        0        0    12125 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_update_request.py
+-rw-r--r--   0        0        0    12042 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/list.py
+-rw-r--r--   0        0        0    14257 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_instant_query_list.py
+-rw-r--r--   0        0        0    12019 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_instant_query_list_all_of.py
+-rw-r--r--   0        0        0    14241 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_range_query_list.py
+-rw-r--r--   0        0        0    12013 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_range_query_list_all_of.py
+-rw-r--r--   0        0        0    11852 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/object_reference.py
+-rw-r--r--   0        0        0    11834 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/range_query.py
+-rw-r--r--   0        0        0    12233 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/region_capacity_list_item.py
+-rw-r--r--   0        0        0    15548 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account.py
+-rw-r--r--   0        0        0    12995 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_all_of.py
+-rw-r--r--   0        0        0    13948 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list.py
+-rw-r--r--   0        0        0    11896 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list_all_of.py
+-rw-r--r--   0        0        0    15787 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list_item.py
+-rw-r--r--   0        0        0    13192 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list_item_all_of.py
+-rw-r--r--   0        0        0    11867 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_request.py
+-rw-r--r--   0        0        0    15032 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/sso_provider.py
+-rw-r--r--   0        0        0    12324 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/sso_provider_all_of.py
+-rw-r--r--   0        0        0    13258 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_billing_model.py
+-rw-r--r--   0        0        0    13608 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_type.py
+-rw-r--r--   0        0        0    20642 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_type_sizes_inner.py
+-rw-r--r--   0        0        0    14021 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_types_list.py
+-rw-r--r--   0        0        0    11742 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_types_list_all_of.py
+-rw-r--r--   0        0        0    18452 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_size.py
+-rw-r--r--   0        0        0    11508 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_size_bytes_value_item.py
+-rw-r--r--   0        0        0    11687 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/values.py
+-rw-r--r--   0        0        0    14500 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/version_metadata.py
+-rw-r--r--   0        0        0    11963 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/version_metadata_all_of.py
+-rw-r--r--   0        0        0    82638 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model_utils.py
+-rw-r--r--   0        0        0     5039 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/models/__init__.py
+-rw-r--r--   0        0        0    14338 2023-06-28 11:20:46.767591 rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/rest.py
+-rw-r--r--   0        0        0     2084 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/__init__.py
+-rw-r--r--   0        0        0      229 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/__init__.py
+-rw-r--r--   0        0        0   116696 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/admin_api.py
+-rw-r--r--   0        0        0    47674 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/artifact_rules_api.py
+-rw-r--r--   0        0        0    89279 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/artifacts_api.py
+-rw-r--r--   0        0        0    23764 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/groups_api.py
+-rw-r--r--   0        0        0    53464 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/metadata_api.py
+-rw-r--r--   0        0        0    17954 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/search_api.py
+-rw-r--r--   0        0        0    11617 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/system_api.py
+-rw-r--r--   0        0        0     6836 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/users_api.py
+-rw-r--r--   0        0        0    73252 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/versions_api.py
+-rw-r--r--   0        0        0    40377 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api_client.py
+-rw-r--r--   0        0        0     1046 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/apis/__init__.py
+-rw-r--r--   0        0        0    17456 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/configuration.py
+-rw-r--r--   0        0        0     6312 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/exceptions.py
+-rw-r--r--   0        0        0      361 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/__init__.py
+-rw-r--r--   0        0        0    13532 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_content.py
+-rw-r--r--   0        0        0    16767 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_meta_data.py
+-rw-r--r--   0        0        0    12672 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_owner.py
+-rw-r--r--   0        0        0    13413 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_reference.py
+-rw-r--r--   0        0        0    13610 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_search_results.py
+-rw-r--r--   0        0        0    13816 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_state.py
+-rw-r--r--   0        0        0    12676 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_type_info.py
+-rw-r--r--   0        0        0    13551 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/comment.py
+-rw-r--r--   0        0        0    13598 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/configuration_property.py
+-rw-r--r--   0        0        0    13326 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/create_group_meta_data.py
+-rw-r--r--   0        0        0    12957 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/download_ref.py
+-rw-r--r--   0        0        0    13493 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/editable_meta_data.py
+-rw-r--r--   0        0        0    13676 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/error.py
+-rw-r--r--   0        0        0    14548 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/group_meta_data.py
+-rw-r--r--   0        0        0    13529 2023-06-28 11:20:46.775591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/group_search_results.py
+-rw-r--r--   0        0        0    13371 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/if_exists.py
+-rw-r--r--   0        0        0    15923 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/limits.py
+-rw-r--r--   0        0        0    12914 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/log_configuration.py
+-rw-r--r--   0        0        0    13773 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/log_level.py
+-rw-r--r--   0        0        0    15316 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/named_log_configuration.py
+-rw-r--r--   0        0        0    12750 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/named_log_configuration_all_of.py
+-rw-r--r--   0        0        0    12711 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/new_comment.py
+-rw-r--r--   0        0        0    12423 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/properties.py
+-rw-r--r--   0        0        0    13212 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/reference_type.py
+-rw-r--r--   0        0        0    13466 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/role_mapping.py
+-rw-r--r--   0        0        0    13281 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/role_type.py
+-rw-r--r--   0        0        0    13067 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule.py
+-rw-r--r--   0        0        0    13323 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_type.py
+-rw-r--r--   0        0        0    12910 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_violation_cause.py
+-rw-r--r--   0        0        0    16461 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_violation_error.py
+-rw-r--r--   0        0        0    13085 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_violation_error_all_of.py
+-rw-r--r--   0        0        0    15207 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/searched_artifact.py
+-rw-r--r--   0        0        0    14104 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/searched_group.py
+-rw-r--r--   0        0        0    15782 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/searched_version.py
+-rw-r--r--   0        0        0    13179 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/sort_by.py
+-rw-r--r--   0        0        0    13152 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/sort_order.py
+-rw-r--r--   0        0        0    13276 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/system_info.py
+-rw-r--r--   0        0        0    12762 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/update_configuration_property.py
+-rw-r--r--   0        0        0    12885 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/update_role.py
+-rw-r--r--   0        0        0    12934 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/update_state.py
+-rw-r--r--   0        0        0    13472 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/user_info.py
+-rw-r--r--   0        0        0    15795 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/version_meta_data.py
+-rw-r--r--   0        0        0    13587 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/version_search_results.py
+-rw-r--r--   0        0        0    83852 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model_utils.py
+-rw-r--r--   0        0        0     3689 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/models/__init__.py
+-rw-r--r--   0        0        0    15552 2023-06-28 11:20:46.779591 rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/rest.py
+-rw-r--r--   0        0        0     1078 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/__init__.py
+-rw-r--r--   0        0        0      234 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api/__init__.py
+-rw-r--r--   0        0        0     5947 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api/default_api.py
+-rw-r--r--   0        0        0    11488 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api/errors_api.py
+-rw-r--r--   0        0        0    23774 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api/registries_api.py
+-rw-r--r--   0        0        0    39320 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api_client.py
+-rw-r--r--   0        0        0      659 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/apis/__init__.py
+-rw-r--r--   0        0        0    17118 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/configuration.py
+-rw-r--r--   0        0        0     5274 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/exceptions.py
+-rw-r--r--   0        0        0      365 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/__init__.py
+-rw-r--r--   0        0        0    12257 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/abstract_list.py
+-rw-r--r--   0        0        0    11829 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/empty.py
+-rw-r--r--   0        0        0    14633 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error.py
+-rw-r--r--   0        0        0    12100 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error_all_of.py
+-rw-r--r--   0        0        0    14552 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error_list.py
+-rw-r--r--   0        0        0    11866 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error_list_all_of.py
+-rw-r--r--   0        0        0    14582 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/list.py
+-rw-r--r--   0        0        0    11922 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/list_all_of.py
+-rw-r--r--   0        0        0    12043 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/object_reference.py
+-rw-r--r--   0        0        0    17009 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry.py
+-rw-r--r--   0        0        0    12507 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_create.py
+-rw-r--r--   0        0        0    13176 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_instance_type_value.py
+-rw-r--r--   0        0        0    14597 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_list.py
+-rw-r--r--   0        0        0    11896 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_list_all_of.py
+-rw-r--r--   0        0        0    14374 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_status_value.py
+-rw-r--r--   0        0        0    14892 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/root_type_for_registry.py
+-rw-r--r--   0        0        0    12041 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/service_status.py
+-rw-r--r--   0        0        0    82818 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model_utils.py
+-rw-r--r--   0        0        0     1721 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/models/__init__.py
+-rw-r--r--   0        0        0    14518 2023-06-28 11:20:46.783591 rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/rest.py
+-rw-r--r--   0        0        0      921 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/__init__.py
+-rw-r--r--   0        0        0      238 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api/__init__.py
+-rw-r--r--   0        0        0    11813 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api/acs_tenants_api.py
+-rw-r--r--   0        0        0    11471 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api/default_api.py
+-rw-r--r--   0        0        0    34067 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api/service_accounts_api.py
+-rw-r--r--   0        0        0    39199 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api_client.py
+-rw-r--r--   0        0        0      688 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/apis/__init__.py
+-rw-r--r--   0        0        0    17479 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/configuration.py
+-rw-r--r--   0        0        0     5117 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/exceptions.py
+-rw-r--r--   0        0        0      365 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/__init__.py
+-rw-r--r--   0        0        0    12294 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/acs_client_request_data.py
+-rw-r--r--   0        0        0    12101 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/acs_client_response_data.py
+-rw-r--r--   0        0        0    11652 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/authentication_factors.py
+-rw-r--r--   0        0        0    11870 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/authentication_policy.py
+-rw-r--r--   0        0        0    11557 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/error.py
+-rw-r--r--   0        0        0    11473 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/otp.py
+-rw-r--r--   0        0        0    12719 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/red_hat_error_representation.py
+-rw-r--r--   0        0        0    11979 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/service_account_create_request_data.py
+-rw-r--r--   0        0        0    12824 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/service_account_data.py
+-rw-r--r--   0        0        0    11919 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/service_account_request_data.py
+-rw-r--r--   0        0        0    11976 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/validation_exception_data.py
+-rw-r--r--   0        0        0    82661 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model_utils.py
+-rw-r--r--   0        0        0     1411 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/models/__init__.py
+-rw-r--r--   0        0        0    14361 2023-06-28 11:20:46.787592 rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/rest.py
+-rw-r--r--   0        0        0      906 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/__init__.py
+-rw-r--r--   0        0        0      231 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/__init__.py
+-rw-r--r--   0        0        0    22654 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/bridges_api.py
+-rw-r--r--   0        0        0    17973 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/cloud_providers_api.py
+-rw-r--r--   0        0        0    11522 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/error_catalog_api.py
+-rw-r--r--   0        0        0    30966 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/processors_api.py
+-rw-r--r--   0        0        0    31097 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/sink_connectors_api.py
+-rw-r--r--   0        0        0    31340 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/source_connectors_api.py
+-rw-r--r--   0        0        0    39229 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api_client.py
+-rw-r--r--   0        0        0      908 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/apis/__init__.py
+-rw-r--r--   0        0        0    16974 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/configuration.py
+-rw-r--r--   0        0        0     5134 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/exceptions.py
+-rw-r--r--   0        0        0      361 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/__init__.py
+-rw-r--r--   0        0        0    12252 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_error.py
+-rw-r--r--   0        0        0    12454 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_error_instance.py
+-rw-r--r--   0        0        0    12014 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_error_type.py
+-rw-r--r--   0        0        0    12543 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_list_response.py
+-rw-r--r--   0        0        0    12474 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_request.py
+-rw-r--r--   0        0        0    15062 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_response.py
+-rw-r--r--   0        0        0    12614 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_provider_list_response.py
+-rw-r--r--   0        0        0    12897 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_provider_response.py
+-rw-r--r--   0        0        0    12594 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_region_list_response.py
+-rw-r--r--   0        0        0    12243 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_region_response.py
+-rw-r--r--   0        0        0    12627 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/connector_request.py
+-rw-r--r--   0        0        0    12735 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/error.py
+-rw-r--r--   0        0        0    12476 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/error_list_response.py
+-rw-r--r--   0        0        0    11874 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/errors_list.py
+-rw-r--r--   0        0        0    14500 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/list.py
+-rw-r--r--   0        0        0    11910 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/list_all_of.py
+-rw-r--r--   0        0        0    11915 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/list_response.py
+-rw-r--r--   0        0        0    12980 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/managed_resource_status.py
+-rw-r--r--   0        0        0    12375 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/object_reference.py
+-rw-r--r--   0        0        0    12634 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processing_error_list_response.py
+-rw-r--r--   0        0        0    12183 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processing_error_response.py
+-rw-r--r--   0        0        0    12573 2023-06-28 11:20:46.791592 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processor_list_response.py
+-rw-r--r--   0        0        0    12220 2023-06-28 11:20:46.795591 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processor_request.py
+-rw-r--r--   0        0        0    14580 2023-06-28 11:20:46.795591 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processor_response.py
+-rw-r--r--   0        0        0    12614 2023-06-28 11:20:46.795591 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/sink_connector_list_response.py
+-rw-r--r--   0        0        0    15396 2023-06-28 11:20:46.795591 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/sink_connector_response.py
+-rw-r--r--   0        0        0    12634 2023-06-28 11:20:46.795591 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/source_connector_list_response.py
+-rw-r--r--   0        0        0    15063 2023-06-28 11:20:46.795591 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/source_connector_response.py
+-rw-r--r--   0        0        0    82674 2023-06-28 11:20:46.795591 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model_utils.py
+-rw-r--r--   0        0        0     2755 2023-06-28 11:20:46.795591 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/models/__init__.py
+-rw-r--r--   0        0        0    14374 2023-06-28 11:20:46.795591 rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/rest.py
+-rw-r--r--   0        0        0    13626 1970-01-01 00:00:00.000000 rhoas_sdks-1.0.3/PKG-INFO
```

### Comparing `rhoas_sdks-1.0.2b2/auth/rhoas_auth.py` & `rhoas_sdks-1.0.3/auth/rhoas_auth.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/docs/README.md` & `rhoas_sdks-1.0.3/docs/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 # RHOAS Core SDKs
 
 > If you are moving a project from the old RHOAS SDKs to core read this [moving](./MOVING.md) doc to get started.
 
 | Supported Langauge  | SDK |
 | ----------- | ----------- |
-| JavaScript/TypeScript  | [app-services-sdk-js](/app-services-sdk-js/) |
+| JavaScript  | [app-services-sdk-ts](/app-services-sdk-ts/) |
 | Python   | [app-services-sdk-python](/app-services-sdk-python/)    |
 | Java   | [app-services-sdk-java](/app-services-sdk-java/)        |
 |  Go   | [app-services-sdk-go](/app-services-sdk-go/)        |
 
 ## Structure
 
 RHOAS SDK's are delivered as set of individual packages.
@@ -18,17 +18,17 @@
 - **Instance SDKs** -  support direct interaction with services
 
 ## Purpose of this repository
 
 Repository contains source code for openapi based generator along with automation scripts that generate all
 underlying RHOAS SDKS. 
 
-# RHOAS SDK for Typescript and JavaScript
+# RHOAS SDK for Typescript
 
-Typescript and JavaScript packages and API clients for RHOAS services
+Typescript packages and API clients for RHOAS services
 
 ## Prequisites
 
 - [NodeJS 14.x lts](https://nodejs.org/en/about/releases/) or above
 
 ## Management SDK's
```

### Comparing `rhoas_sdks-1.0.2b2/pyproject.toml` & `rhoas_sdks-1.0.3/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "rhoas_sdks"
-version = "1.0.2-beta2"
+version = "1.0.3"
 description = "A package which includes RHOAS SDKs"
 authors = ["dimakis <dsaridak@redhat.com>"]
 license = "Apache License"
 readme = "docs/README.md"
 packages = [
     { include = "rhoas_connector_mgmt_sdk", from = "sdks/connector_mgmt_sdk/" },
     { include = "rhoas_kafka_instance_sdk", from = "sdks/kafka_instance_sdk/"},
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/__init__.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_clusters_api.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_clusters_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_namespaces_api.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_namespaces_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_service_api.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_service_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_types_api.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connector_types_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connectors_api.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api/connectors_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api_client.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/api_client.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/apis/__init__.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/apis/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/configuration.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/configuration.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/exceptions.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/exceptions.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/addon_parameter.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/addon_parameter.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/addon_parameter_list.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/addon_parameter_list.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/channel.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/channel.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_list.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_list.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_list_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_meta.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_meta.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_request.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_request.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_request_meta.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_request_meta.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_state.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_state.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_status.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_status.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_status_status.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_cluster_status_status.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_configuration.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_configuration.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_desired_state.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_desired_state.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_list.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_list.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_list_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_meta.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_meta.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_meta_all_of.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_meta_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_all_of.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_eval_request.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_eval_request.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_list.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_list.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_list_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_meta.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_meta.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_meta_all_of.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_meta_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_patch_request.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_patch_request.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_quota.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_quota.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_request.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_request.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_request_all_of.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_request_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_request_meta.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_request_meta.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_state.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_state.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_status.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_status.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_tenant.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_tenant.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_tenant_kind.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_namespace_tenant_kind.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_request.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_request.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_request_meta.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_request_meta.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_resource_annotations.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_resource_annotations.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_state.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_state.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_status.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_status.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_status_status.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_status_status.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_all_of.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_label_count.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_label_count.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_label_count_list.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_label_count_list.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_list.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_list.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/connector_type_list_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/cpu_quota.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/cpu_quota.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/error.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/error.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/kafka_connection_settings.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/kafka_connection_settings.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/list.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/sink_connector_list_response.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,45 +1,45 @@
 """
-    Connector Management API
+    Red Hat Openshift SmartEvents Fleet Manager V2
 
-    Connector Management API is a REST API to manage connectors.  # noqa: E501
+    The API exposed by the fleet manager of the SmartEvents service.  # noqa: E501
 
-    The version of the OpenAPI document: 0.1.0
-    Contact: rhosak-support@redhat.com
+    The version of the OpenAPI document: 0.0.1
+    Contact: openbridge-dev@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
 
-from rhoas_connector_mgmt_sdk.model_utils import (  # noqa: F401
+from rhoas_smart_events_mgmt_sdk.model_utils import (  # noqa: F401
     ApiTypeError,
     ModelComposed,
     ModelNormal,
     ModelSimple,
     cached_property,
     change_keys_js_to_python,
     convert_js_args_to_python_args,
     date,
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
-from rhoas_connector_mgmt_sdk.exceptions import ApiAttributeError
+from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
 
 
 def lazy_import():
-    from rhoas_connector_mgmt_sdk.model.object_reference import ObjectReference
-    globals()['ObjectReference'] = ObjectReference
+    from rhoas_smart_events_mgmt_sdk.model.sink_connector_response import SinkConnectorResponse
+    globals()['SinkConnectorResponse'] = SinkConnectorResponse
 
 
-class List(ModelNormal):
+class SinkConnectorListResponse(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -88,15 +88,15 @@
         """
         lazy_import()
         return {
             'kind': (str,),  # noqa: E501
             'page': (int,),  # noqa: E501
             'size': (int,),  # noqa: E501
             'total': (int,),  # noqa: E501
-            'items': ([ObjectReference],),  # noqa: E501
+            'items': ([SinkConnectorResponse],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
@@ -111,23 +111,22 @@
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, kind, page, size, total, items, *args, **kwargs):  # noqa: E501
-        """List - a model defined in OpenAPI
+    def _from_openapi_data(cls, kind, page, size, total, *args, **kwargs):  # noqa: E501
+        """SinkConnectorListResponse - a model defined in OpenAPI
 
         Args:
             kind (str):
             page (int):
             size (int):
             total (int):
-            items ([ObjectReference]):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -152,14 +151,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
+            items ([SinkConnectorResponse]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -187,15 +187,14 @@
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
         self.kind = kind
         self.page = page
         self.size = size
         self.total = total
-        self.items = items
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -208,23 +207,22 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, kind, page, size, total, items, *args, **kwargs):  # noqa: E501
-        """List - a model defined in OpenAPI
+    def __init__(self, kind, page, size, total, *args, **kwargs):  # noqa: E501
+        """SinkConnectorListResponse - a model defined in OpenAPI
 
         Args:
             kind (str):
             page (int):
             size (int):
             total (int):
-            items ([ObjectReference]):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -249,14 +247,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
+            items ([SinkConnectorResponse]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -282,15 +281,14 @@
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
         self.kind = kind
         self.page = page
         self.size = size
         self.total = total
-        self.items = items
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/memory_quota.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/memory_quota.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/object_meta.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/object_meta.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/object_reference.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/object_reference.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/schema_registry_connection_settings.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/schema_registry_connection_settings.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/service_account.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/service_account.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/service_connection_settings.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/service_connection_settings.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/version_metadata.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/version_metadata.py`

 * *Files 4% similar despite different names*

```diff
@@ -89,15 +89,15 @@
                 and the value is attribute type.
         """
         lazy_import()
         return {
             'id': (str,),  # noqa: E501
             'kind': (str,),  # noqa: E501
             'href': (str,),  # noqa: E501
-            'collections': ([bool, date, datetime, dict, float, int, list, str, none_type],),  # noqa: E501
+            'collections': ([ObjectReference],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
@@ -146,15 +146,15 @@
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
             id (str): [optional]  # noqa: E501
             kind (str): [optional]  # noqa: E501
             href (str): [optional]  # noqa: E501
-            collections ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
+            collections ([ObjectReference]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -253,15 +253,15 @@
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
             id (str): [optional]  # noqa: E501
             kind (str): [optional]  # noqa: E501
             href (str): [optional]  # noqa: E501
-            collections ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
+            collections ([ObjectReference]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/version_metadata_all_of.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/version_metadata_all_of.py`

 * *Files 4% similar despite different names*

```diff
@@ -26,14 +26,18 @@
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_connector_mgmt_sdk.exceptions import ApiAttributeError
 
 
+def lazy_import():
+    from rhoas_connector_mgmt_sdk.model.object_reference import ObjectReference
+    globals()['ObjectReference'] = ObjectReference
+
 
 class VersionMetadataAllOf(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
@@ -63,30 +67,32 @@
 
     @cached_property
     def additional_properties_type():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
         """
+        lazy_import()
         return (bool, date, datetime, dict, float, int, list, str, none_type,)  # noqa: E501
 
     _nullable = False
 
     @cached_property
     def openapi_types():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
+        lazy_import()
         return {
-            'collections': ([bool, date, datetime, dict, float, int, list, str, none_type],),  # noqa: E501
+            'collections': ([ObjectReference],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
@@ -131,15 +137,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            collections ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
+            collections ([ObjectReference]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -217,15 +223,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            collections ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
+            collections ([ObjectReference]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model_utils.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model_utils.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/models/__init__.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/models/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/rest.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/rest.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/__init__.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/acls_api.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/acls_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/errors_api.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/errors_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/groups_api.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/groups_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/records_api.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/records_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/topics_api.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api/topics_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api_client.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/api_client.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/apis/__init__.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/apis/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/configuration.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/configuration.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/exceptions.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/exceptions.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_list_page.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_list_page.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_list_page_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_list_page_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_order_key.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_binding_order_key.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_operation.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_operation.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_operation_filter.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_operation_filter.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_pattern_type.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_pattern_type.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_pattern_type_filter.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_pattern_type_filter.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_permission_type.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_permission_type.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_permission_type_filter.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_permission_type_filter.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_resource_type.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_resource_type.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_resource_type_filter.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/acl_resource_type_filter.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/config_entry.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/config_entry.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_description_order_key.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_description_order_key.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_list.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_list.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_list_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_metrics.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_metrics.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_order_key.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_order_key.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_parameters.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_parameters.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_result.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_result.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_result_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_result_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_result_item.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_reset_offset_result_item.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_state.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/consumer_group_state.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error_list.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error_list.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/error_list_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/list.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/list.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/list_deprecated.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/list_deprecated.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/list_deprecated_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/list_deprecated_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/new_topic_input.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/new_topic_input.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/node.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/node.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/object_reference.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/object_reference.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/offset_type.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/offset_type.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/partition.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/partition.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/partition_leader.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/partition_leader.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_included_property.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_included_property.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_list.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_list.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/record_list_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/sort_direction.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/sort_direction.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic_order_key.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic_order_key.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic_settings.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topic_settings.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topics_list.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topics_list.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topics_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topics_list_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topics_to_reset_offset.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model/topics_to_reset_offset.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model_utils.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/model_utils.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/models/__init__.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/models/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/rest.py` & `rhoas_sdks-1.0.3/sdks/kafka_instance_sdk/rhoas_kafka_instance_sdk/rest.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/__init__.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 # flake8: noqa
 
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 __version__ = "1.0.0"
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/default_api.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/default_api.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/enterprise_dataplane_clusters_api.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/enterprise_dataplane_clusters_api.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
@@ -19,16 +19,17 @@
     date,
     datetime,
     file_type,
     none_type,
     validate_and_convert_types
 )
 from rhoas_kafka_mgmt_sdk.model.enterprise_cluster import EnterpriseCluster
+from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_addon_parameters import EnterpriseClusterAddonParameters
 from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_list import EnterpriseClusterList
-from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_with_addon_parameters import EnterpriseClusterWithAddonParameters
+from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_registration_response import EnterpriseClusterRegistrationResponse
 from rhoas_kafka_mgmt_sdk.model.enterprise_osd_cluster_payload import EnterpriseOsdClusterPayload
 from rhoas_kafka_mgmt_sdk.model.error import Error
 
 
 class EnterpriseDataplaneClustersApi(object):
     """NOTE: This class is auto generated by OpenAPI Generator
     Ref: https://openapi-generator.tech
@@ -93,22 +94,22 @@
                 'accept': [
                     'application/json'
                 ],
                 'content_type': [],
             },
             api_client=api_client
         )
-        self.get_enterprise_cluster_by_id_endpoint = _Endpoint(
+        self.get_enterprise_cluster_addon_parameters_endpoint = _Endpoint(
             settings={
-                'response_type': (EnterpriseCluster,),
+                'response_type': (EnterpriseClusterAddonParameters,),
                 'auth': [
                     'Bearer'
                 ],
-                'endpoint_path': '/api/kafkas_mgmt/v1/clusters/{id}',
-                'operation_id': 'get_enterprise_cluster_by_id',
+                'endpoint_path': '/api/kafkas_mgmt/v1/clusters/{id}/addon_parameters',
+                'operation_id': 'get_enterprise_cluster_addon_parameters',
                 'http_method': 'GET',
                 'servers': None,
             },
             params_map={
                 'all': [
                     'id',
                 ],
@@ -144,22 +145,22 @@
                 'accept': [
                     'application/json'
                 ],
                 'content_type': [],
             },
             api_client=api_client
         )
-        self.get_enterprise_cluster_with_addon_parameters_endpoint = _Endpoint(
+        self.get_enterprise_cluster_by_id_endpoint = _Endpoint(
             settings={
-                'response_type': (EnterpriseClusterWithAddonParameters,),
+                'response_type': (EnterpriseCluster,),
                 'auth': [
                     'Bearer'
                 ],
-                'endpoint_path': '/api/kafkas_mgmt/v1/clusters/{id}/addon_parameters',
-                'operation_id': 'get_enterprise_cluster_with_addon_parameters',
+                'endpoint_path': '/api/kafkas_mgmt/v1/clusters/{id}',
+                'operation_id': 'get_enterprise_cluster_by_id',
                 'http_method': 'GET',
                 'servers': None,
             },
             params_map={
                 'all': [
                     'id',
                 ],
@@ -241,15 +242,15 @@
                 ],
                 'content_type': [],
             },
             api_client=api_client
         )
         self.register_enterprise_osd_cluster_endpoint = _Endpoint(
             settings={
-                'response_type': (EnterpriseClusterWithAddonParameters,),
+                'response_type': (EnterpriseClusterRegistrationResponse,),
                 'auth': [
                     'Bearer'
                 ],
                 'endpoint_path': '/api/kafkas_mgmt/v1/clusters',
                 'operation_id': 'register_enterprise_osd_cluster',
                 'http_method': 'POST',
                 'servers': None,
@@ -378,26 +379,26 @@
         kwargs['_request_auths'] = kwargs.get('_request_auths', None)
         kwargs['_async'] = \
             _async
         kwargs['id'] = \
             id
         return self.delete_enterprise_cluster_by_id_endpoint.call_with_http_info(**kwargs)
 
-    def get_enterprise_cluster_by_id(
+    def get_enterprise_cluster_addon_parameters(
         self,
         id,
         **kwargs
     ):
-        """get_enterprise_cluster_by_id  # noqa: E501
+        """get_enterprise_cluster_addon_parameters  # noqa: E501
 
-        Returns enterprise data plane cluster by ID  # noqa: E501
+        Returns the addon parameters belonging to the enterprise dataplane cluster {id}  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
 
-        >>> thread = api.get_enterprise_cluster_by_id(id, async_req=True)
+        >>> thread = api.get_enterprise_cluster_addon_parameters(id, async_req=True)
         >>> result = thread.get()
 
         Args:
             id (str): ID of the enterprise data plane cluster
 
         Keyword Args:
             _return_http_data_only (bool): response data without head status
@@ -428,15 +429,15 @@
             _request_auths (list): set to override the auth_settings for an a single
                 request; this effectively ignores the authentication
                 in the spec for a single request.
                 Default is None
             async_req (bool): execute request asynchronously
 
         Returns:
-            EnterpriseCluster
+            EnterpriseClusterAddonParameters
                 If the method is called asynchronously, returns the request
                 thread.
         """
         kwargs['async_req'] = kwargs.get(
             'async_req', False
         )
         kwargs['_return_http_data_only'] = kwargs.get(
@@ -459,28 +460,28 @@
         )
         kwargs['_content_type'] = kwargs.get(
             '_content_type')
         kwargs['_host_index'] = kwargs.get('_host_index')
         kwargs['_request_auths'] = kwargs.get('_request_auths', None)
         kwargs['id'] = \
             id
-        return self.get_enterprise_cluster_by_id_endpoint.call_with_http_info(**kwargs)
+        return self.get_enterprise_cluster_addon_parameters_endpoint.call_with_http_info(**kwargs)
 
-    def get_enterprise_cluster_with_addon_parameters(
+    def get_enterprise_cluster_by_id(
         self,
         id,
         **kwargs
     ):
-        """get_enterprise_cluster_with_addon_parameters  # noqa: E501
+        """get_enterprise_cluster_by_id  # noqa: E501
 
-        Returns enterprise data plane cluster by ID along with its addon parameters  # noqa: E501
+        Returns enterprise data plane cluster by ID  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
 
-        >>> thread = api.get_enterprise_cluster_with_addon_parameters(id, async_req=True)
+        >>> thread = api.get_enterprise_cluster_by_id(id, async_req=True)
         >>> result = thread.get()
 
         Args:
             id (str): ID of the enterprise data plane cluster
 
         Keyword Args:
             _return_http_data_only (bool): response data without head status
@@ -511,15 +512,15 @@
             _request_auths (list): set to override the auth_settings for an a single
                 request; this effectively ignores the authentication
                 in the spec for a single request.
                 Default is None
             async_req (bool): execute request asynchronously
 
         Returns:
-            EnterpriseClusterWithAddonParameters
+            EnterpriseCluster
                 If the method is called asynchronously, returns the request
                 thread.
         """
         kwargs['async_req'] = kwargs.get(
             'async_req', False
         )
         kwargs['_return_http_data_only'] = kwargs.get(
@@ -542,15 +543,15 @@
         )
         kwargs['_content_type'] = kwargs.get(
             '_content_type')
         kwargs['_host_index'] = kwargs.get('_host_index')
         kwargs['_request_auths'] = kwargs.get('_request_auths', None)
         kwargs['id'] = \
             id
-        return self.get_enterprise_cluster_with_addon_parameters_endpoint.call_with_http_info(**kwargs)
+        return self.get_enterprise_cluster_by_id_endpoint.call_with_http_info(**kwargs)
 
     def get_enterprise_osd_clusters(
         self,
         **kwargs
     ):
         """get_enterprise_osd_clusters  # noqa: E501
 
@@ -672,15 +673,15 @@
             _request_auths (list): set to override the auth_settings for an a single
                 request; this effectively ignores the authentication
                 in the spec for a single request.
                 Default is None
             async_req (bool): execute request asynchronously
 
         Returns:
-            EnterpriseClusterWithAddonParameters
+            EnterpriseClusterRegistrationResponse
                 If the method is called asynchronously, returns the request
                 thread.
         """
         kwargs['async_req'] = kwargs.get(
             'async_req', False
         )
         kwargs['_return_http_data_only'] = kwargs.get(
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/errors_api.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/errors_api.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/security_api.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api/security_api.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api_client.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/api_client.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import json
 import atexit
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/apis/__init__.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/apis/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/configuration.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/configuration.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import copy
 import logging
@@ -385,15 +385,15 @@
         """Gets the essential information for debugging.
 
         :return: The report for debugging.
         """
         return "Python SDK Debug Report:\n"\
                "OS: {env}\n"\
                "Python Version: {pyversion}\n"\
-               "Version of the API: 1.15.0\n"\
+               "Version of the API: 1.16.0\n"\
                "SDK Package Version: 1.0.0".\
                format(env=sys.platform, pyversion=sys.version)
 
     def get_host_settings(self):
         """Gets an array of host settings
 
         :return: An array of host settings
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/exceptions.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/exceptions.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 class OpenApiException(Exception):
     """The base exception class for all OpenAPIExceptions"""
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_provider.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_provider.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_provider_list.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_provider_list.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_provider_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_provider_list_all_of.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_region.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_region.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_region_list.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_region_list.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_region_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/cloud_region_list_all_of.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
@@ -29,19 +29,19 @@
 )
 from rhoas_kafka_mgmt_sdk.exceptions import ApiAttributeError
 
 
 def lazy_import():
     from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_all_of import EnterpriseClusterAllOf
     from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_all_of_capacity_information import EnterpriseClusterAllOfCapacityInformation
-    from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_list_item import EnterpriseClusterListItem
+    from rhoas_kafka_mgmt_sdk.model.object_reference import ObjectReference
     from rhoas_kafka_mgmt_sdk.model.supported_kafka_instance_types_list import SupportedKafkaInstanceTypesList
     globals()['EnterpriseClusterAllOf'] = EnterpriseClusterAllOf
     globals()['EnterpriseClusterAllOfCapacityInformation'] = EnterpriseClusterAllOfCapacityInformation
-    globals()['EnterpriseClusterListItem'] = EnterpriseClusterListItem
+    globals()['ObjectReference'] = ObjectReference
     globals()['SupportedKafkaInstanceTypesList'] = SupportedKafkaInstanceTypesList
 
 
 class EnterpriseCluster(ModelComposed):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
@@ -356,12 +356,12 @@
         # loading
         lazy_import()
         return {
           'anyOf': [
           ],
           'allOf': [
               EnterpriseClusterAllOf,
-              EnterpriseClusterListItem,
+              ObjectReference,
           ],
           'oneOf': [
           ],
         }
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_size_bytes_value_item.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
@@ -26,22 +26,16 @@
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_kafka_mgmt_sdk.exceptions import ApiAttributeError
 
 
-def lazy_import():
-    from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_all_of_capacity_information import EnterpriseClusterAllOfCapacityInformation
-    from rhoas_kafka_mgmt_sdk.model.supported_kafka_instance_types_list import SupportedKafkaInstanceTypesList
-    globals()['EnterpriseClusterAllOfCapacityInformation'] = EnterpriseClusterAllOfCapacityInformation
-    globals()['SupportedKafkaInstanceTypesList'] = SupportedKafkaInstanceTypesList
 
-
-class EnterpriseClusterAllOf(ModelNormal):
+class SupportedKafkaSizeBytesValueItem(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -69,54 +63,50 @@
 
     @cached_property
     def additional_properties_type():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
         """
-        lazy_import()
         return (bool, date, datetime, dict, float, int, list, str, none_type,)  # noqa: E501
 
     _nullable = False
 
     @cached_property
     def openapi_types():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
-        lazy_import()
         return {
-            'supported_instance_types': (SupportedKafkaInstanceTypesList,),  # noqa: E501
-            'capacity_information': (EnterpriseClusterAllOfCapacityInformation,),  # noqa: E501
+            'bytes': (int,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'supported_instance_types': 'supported_instance_types',  # noqa: E501
-        'capacity_information': 'capacity_information',  # noqa: E501
+        'bytes': 'bytes',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
     def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
-        """EnterpriseClusterAllOf - a model defined in OpenAPI
+        """SupportedKafkaSizeBytesValueItem - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -141,16 +131,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            supported_instance_types (SupportedKafkaInstanceTypesList): [optional]  # noqa: E501
-            capacity_information (EnterpriseClusterAllOfCapacityInformation): [optional]  # noqa: E501
+            bytes (int): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -195,15 +184,15 @@
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, *args, **kwargs):  # noqa: E501
-        """EnterpriseClusterAllOf - a model defined in OpenAPI
+        """SupportedKafkaSizeBytesValueItem - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -228,16 +217,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            supported_instance_types (SupportedKafkaInstanceTypesList): [optional]  # noqa: E501
-            capacity_information (EnterpriseClusterAllOfCapacityInformation): [optional]  # noqa: E501
+            bytes (int): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_all_of_capacity_information.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_all_of_capacity_information.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_list.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_list.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_list_all_of.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_list_item.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_registration_response.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
@@ -27,21 +27,27 @@
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_kafka_mgmt_sdk.exceptions import ApiAttributeError
 
 
 def lazy_import():
-    from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_list_item_all_of import EnterpriseClusterListItemAllOf
-    from rhoas_kafka_mgmt_sdk.model.object_reference import ObjectReference
-    globals()['EnterpriseClusterListItemAllOf'] = EnterpriseClusterListItemAllOf
-    globals()['ObjectReference'] = ObjectReference
+    from rhoas_kafka_mgmt_sdk.model.enterprise_cluster import EnterpriseCluster
+    from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_all_of_capacity_information import EnterpriseClusterAllOfCapacityInformation
+    from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_fleetshard_parameters import EnterpriseClusterFleetshardParameters
+    from rhoas_kafka_mgmt_sdk.model.fleetshard_parameters_array import FleetshardParametersArray
+    from rhoas_kafka_mgmt_sdk.model.supported_kafka_instance_types_list import SupportedKafkaInstanceTypesList
+    globals()['EnterpriseCluster'] = EnterpriseCluster
+    globals()['EnterpriseClusterAllOfCapacityInformation'] = EnterpriseClusterAllOfCapacityInformation
+    globals()['EnterpriseClusterFleetshardParameters'] = EnterpriseClusterFleetshardParameters
+    globals()['FleetshardParametersArray'] = FleetshardParametersArray
+    globals()['SupportedKafkaInstanceTypesList'] = SupportedKafkaInstanceTypesList
 
 
-class EnterpriseClusterListItem(ModelComposed):
+class EnterpriseClusterRegistrationResponse(ModelComposed):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -95,14 +101,17 @@
             'href': (str,),  # noqa: E501
             'access_kafkas_via_private_network': (bool,),  # noqa: E501
             'multi_az': (bool,),  # noqa: E501
             'cluster_id': (str,),  # noqa: E501
             'status': (str,),  # noqa: E501
             'cloud_provider': (str,),  # noqa: E501
             'region': (str,),  # noqa: E501
+            'supported_instance_types': (SupportedKafkaInstanceTypesList,),  # noqa: E501
+            'capacity_information': (EnterpriseClusterAllOfCapacityInformation,),  # noqa: E501
+            'fleetshard_parameters': (FleetshardParametersArray,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
@@ -112,23 +121,26 @@
         'href': 'href',  # noqa: E501
         'access_kafkas_via_private_network': 'access_kafkas_via_private_network',  # noqa: E501
         'multi_az': 'multi_az',  # noqa: E501
         'cluster_id': 'cluster_id',  # noqa: E501
         'status': 'status',  # noqa: E501
         'cloud_provider': 'cloud_provider',  # noqa: E501
         'region': 'region',  # noqa: E501
+        'supported_instance_types': 'supported_instance_types',  # noqa: E501
+        'capacity_information': 'capacity_information',  # noqa: E501
+        'fleetshard_parameters': 'fleetshard_parameters',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     @classmethod
     @convert_js_args_to_python_args
     def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
-        """EnterpriseClusterListItem - a model defined in OpenAPI
+        """EnterpriseClusterRegistrationResponse - a model defined in OpenAPI
 
         Keyword Args:
             id (str):
             kind (str):
             href (str):
             access_kafkas_via_private_network (bool): Indicates whether Kafkas created on this data plane cluster have to be accessed via private network
             multi_az (bool): A flag indicating whether this cluster is available on multiple availability zones or not
@@ -162,14 +174,17 @@
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
             cluster_id (str): The OCM's cluster id of the registered Enterprise cluster.. [optional]  # noqa: E501
             status (str): The status of Enterprise cluster registration. [optional]  # noqa: E501
             cloud_provider (str): The cloud provider for this cluster. This valus will be used as the Kafka's cloud provider value when a Kafka is created on this cluster. [optional]  # noqa: E501
             region (str): The region of this cluster. This valus will be used as the Kafka's region value when a Kafka is created on this cluster. [optional]  # noqa: E501
+            supported_instance_types (SupportedKafkaInstanceTypesList): [optional]  # noqa: E501
+            capacity_information (EnterpriseClusterAllOfCapacityInformation): [optional]  # noqa: E501
+            fleetshard_parameters (FleetshardParametersArray): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -232,15 +247,15 @@
         '_composed_instances',
         '_var_name_to_model_instances',
         '_additional_properties_model_instances',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, *args, **kwargs):  # noqa: E501
-        """EnterpriseClusterListItem - a model defined in OpenAPI
+        """EnterpriseClusterRegistrationResponse - a model defined in OpenAPI
 
         Keyword Args:
             id (str):
             kind (str):
             href (str):
             access_kafkas_via_private_network (bool): Indicates whether Kafkas created on this data plane cluster have to be accessed via private network
             multi_az (bool): A flag indicating whether this cluster is available on multiple availability zones or not
@@ -274,14 +289,17 @@
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
             cluster_id (str): The OCM's cluster id of the registered Enterprise cluster.. [optional]  # noqa: E501
             status (str): The status of Enterprise cluster registration. [optional]  # noqa: E501
             cloud_provider (str): The cloud provider for this cluster. This valus will be used as the Kafka's cloud provider value when a Kafka is created on this cluster. [optional]  # noqa: E501
             region (str): The region of this cluster. This valus will be used as the Kafka's region value when a Kafka is created on this cluster. [optional]  # noqa: E501
+            supported_instance_types (SupportedKafkaInstanceTypesList): [optional]  # noqa: E501
+            capacity_information (EnterpriseClusterAllOfCapacityInformation): [optional]  # noqa: E501
+            fleetshard_parameters (FleetshardParametersArray): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -343,13 +361,13 @@
         # classes don't exist yet because their module has not finished
         # loading
         lazy_import()
         return {
           'anyOf': [
           ],
           'allOf': [
-              EnterpriseClusterListItemAllOf,
-              ObjectReference,
+              EnterpriseCluster,
+              EnterpriseClusterFleetshardParameters,
           ],
           'oneOf': [
           ],
         }
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_list_item_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_all_of.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
@@ -26,16 +26,22 @@
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_kafka_mgmt_sdk.exceptions import ApiAttributeError
 
 
+def lazy_import():
+    from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_all_of_capacity_information import EnterpriseClusterAllOfCapacityInformation
+    from rhoas_kafka_mgmt_sdk.model.supported_kafka_instance_types_list import SupportedKafkaInstanceTypesList
+    globals()['EnterpriseClusterAllOfCapacityInformation'] = EnterpriseClusterAllOfCapacityInformation
+    globals()['SupportedKafkaInstanceTypesList'] = SupportedKafkaInstanceTypesList
 
-class EnterpriseClusterListItemAllOf(ModelNormal):
+
+class EnterpriseClusterAllOf(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -63,60 +69,66 @@
 
     @cached_property
     def additional_properties_type():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
         """
+        lazy_import()
         return (bool, date, datetime, dict, float, int, list, str, none_type,)  # noqa: E501
 
     _nullable = False
 
     @cached_property
     def openapi_types():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
+        lazy_import()
         return {
             'access_kafkas_via_private_network': (bool,),  # noqa: E501
             'multi_az': (bool,),  # noqa: E501
             'cluster_id': (str,),  # noqa: E501
             'status': (str,),  # noqa: E501
             'cloud_provider': (str,),  # noqa: E501
             'region': (str,),  # noqa: E501
+            'supported_instance_types': (SupportedKafkaInstanceTypesList,),  # noqa: E501
+            'capacity_information': (EnterpriseClusterAllOfCapacityInformation,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
         'access_kafkas_via_private_network': 'access_kafkas_via_private_network',  # noqa: E501
         'multi_az': 'multi_az',  # noqa: E501
         'cluster_id': 'cluster_id',  # noqa: E501
         'status': 'status',  # noqa: E501
         'cloud_provider': 'cloud_provider',  # noqa: E501
         'region': 'region',  # noqa: E501
+        'supported_instance_types': 'supported_instance_types',  # noqa: E501
+        'capacity_information': 'capacity_information',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
     def _from_openapi_data(cls, access_kafkas_via_private_network, multi_az, *args, **kwargs):  # noqa: E501
-        """EnterpriseClusterListItemAllOf - a model defined in OpenAPI
+        """EnterpriseClusterAllOf - a model defined in OpenAPI
 
         Args:
             access_kafkas_via_private_network (bool): Indicates whether Kafkas created on this data plane cluster have to be accessed via private network
             multi_az (bool): A flag indicating whether this cluster is available on multiple availability zones or not
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
@@ -149,14 +161,16 @@
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
             cluster_id (str): The OCM's cluster id of the registered Enterprise cluster.. [optional]  # noqa: E501
             status (str): The status of Enterprise cluster registration. [optional]  # noqa: E501
             cloud_provider (str): The cloud provider for this cluster. This valus will be used as the Kafka's cloud provider value when a Kafka is created on this cluster. [optional]  # noqa: E501
             region (str): The region of this cluster. This valus will be used as the Kafka's region value when a Kafka is created on this cluster. [optional]  # noqa: E501
+            supported_instance_types (SupportedKafkaInstanceTypesList): [optional]  # noqa: E501
+            capacity_information (EnterpriseClusterAllOfCapacityInformation): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -203,15 +217,15 @@
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, access_kafkas_via_private_network, multi_az, *args, **kwargs):  # noqa: E501
-        """EnterpriseClusterListItemAllOf - a model defined in OpenAPI
+        """EnterpriseClusterAllOf - a model defined in OpenAPI
 
         Args:
             access_kafkas_via_private_network (bool): Indicates whether Kafkas created on this data plane cluster have to be accessed via private network
             multi_az (bool): A flag indicating whether this cluster is available on multiple availability zones or not
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
@@ -244,14 +258,16 @@
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
             cluster_id (str): The OCM's cluster id of the registered Enterprise cluster.. [optional]  # noqa: E501
             status (str): The status of Enterprise cluster registration. [optional]  # noqa: E501
             cloud_provider (str): The cloud provider for this cluster. This valus will be used as the Kafka's cloud provider value when a Kafka is created on this cluster. [optional]  # noqa: E501
             region (str): The region of this cluster. This valus will be used as the Kafka's region value when a Kafka is created on this cluster. [optional]  # noqa: E501
+            supported_instance_types (SupportedKafkaInstanceTypesList): [optional]  # noqa: E501
+            capacity_information (EnterpriseClusterAllOfCapacityInformation): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_with_addon_parameters.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/list.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,47 +1,49 @@
 """
-    Kafka Management API
+    Service Registry Management API
 
-    Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
+    Service Registry Management API is a REST API for managing Service Registry instances. Service Registry is a datastore for event schemas and API designs, which is based on the open source Apicurio Registry project.  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
-    Contact: rhosak-support@redhat.com
+    The version of the OpenAPI document: 1.0.0
+    Contact: rhosak-eval-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
 
-from rhoas_kafka_mgmt_sdk.model_utils import (  # noqa: F401
+from rhoas_service_registry_mgmt_sdk.model_utils import (  # noqa: F401
     ApiTypeError,
     ModelComposed,
     ModelNormal,
     ModelSimple,
     cached_property,
     change_keys_js_to_python,
     convert_js_args_to_python_args,
     date,
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
-from rhoas_kafka_mgmt_sdk.exceptions import ApiAttributeError
+from rhoas_service_registry_mgmt_sdk.exceptions import ApiAttributeError
 
 
 def lazy_import():
-    from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_list_item import EnterpriseClusterListItem
-    from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_with_addon_parameters_all_of import EnterpriseClusterWithAddonParametersAllOf
-    globals()['EnterpriseClusterListItem'] = EnterpriseClusterListItem
-    globals()['EnterpriseClusterWithAddonParametersAllOf'] = EnterpriseClusterWithAddonParametersAllOf
+    from rhoas_service_registry_mgmt_sdk.model.abstract_list import AbstractList
+    from rhoas_service_registry_mgmt_sdk.model.list_all_of import ListAllOf
+    from rhoas_service_registry_mgmt_sdk.model.object_reference import ObjectReference
+    globals()['AbstractList'] = AbstractList
+    globals()['ListAllOf'] = ListAllOf
+    globals()['ObjectReference'] = ObjectReference
 
 
-class EnterpriseClusterWithAddonParameters(ModelComposed):
+class List(ModelComposed):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -86,58 +88,48 @@
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         lazy_import()
         return {
-            'id': (str,),  # noqa: E501
             'kind': (str,),  # noqa: E501
-            'href': (str,),  # noqa: E501
-            'access_kafkas_via_private_network': (bool,),  # noqa: E501
-            'multi_az': (bool,),  # noqa: E501
-            'cluster_id': (str,),  # noqa: E501
-            'status': (str,),  # noqa: E501
-            'cloud_provider': (str,),  # noqa: E501
-            'region': (str,),  # noqa: E501
-            'fleetshard_parameters': ([bool, date, datetime, dict, float, int, list, str, none_type],),  # noqa: E501
+            'page': (int,),  # noqa: E501
+            'size': (int,),  # noqa: E501
+            'total': (int,),  # noqa: E501
+            'items': ([ObjectReference],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'id': 'id',  # noqa: E501
         'kind': 'kind',  # noqa: E501
-        'href': 'href',  # noqa: E501
-        'access_kafkas_via_private_network': 'access_kafkas_via_private_network',  # noqa: E501
-        'multi_az': 'multi_az',  # noqa: E501
-        'cluster_id': 'cluster_id',  # noqa: E501
-        'status': 'status',  # noqa: E501
-        'cloud_provider': 'cloud_provider',  # noqa: E501
-        'region': 'region',  # noqa: E501
-        'fleetshard_parameters': 'fleetshard_parameters',  # noqa: E501
+        'page': 'page',  # noqa: E501
+        'size': 'size',  # noqa: E501
+        'total': 'total',  # noqa: E501
+        'items': 'items',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     @classmethod
     @convert_js_args_to_python_args
     def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
-        """EnterpriseClusterWithAddonParameters - a model defined in OpenAPI
+        """List - a model defined in OpenAPI
 
         Keyword Args:
-            id (str):
             kind (str):
-            href (str):
-            access_kafkas_via_private_network (bool): Indicates whether Kafkas created on this data plane cluster have to be accessed via private network
-            multi_az (bool): A flag indicating whether this cluster is available on multiple availability zones or not
+            page (int):
+            size (int):
+            total (int):
+            items ([ObjectReference]):
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
                                 drill down to the model in received_data
                                 when deserializing a response
@@ -160,19 +152,14 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            cluster_id (str): The OCM's cluster id of the registered Enterprise cluster.. [optional]  # noqa: E501
-            status (str): The status of Enterprise cluster registration. [optional]  # noqa: E501
-            cloud_provider (str): The cloud provider for this cluster. This valus will be used as the Kafka's cloud provider value when a Kafka is created on this cluster. [optional]  # noqa: E501
-            region (str): The region of this cluster. This valus will be used as the Kafka's region value when a Kafka is created on this cluster. [optional]  # noqa: E501
-            fleetshard_parameters ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -235,22 +222,22 @@
         '_composed_instances',
         '_var_name_to_model_instances',
         '_additional_properties_model_instances',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, *args, **kwargs):  # noqa: E501
-        """EnterpriseClusterWithAddonParameters - a model defined in OpenAPI
+        """List - a model defined in OpenAPI
 
         Keyword Args:
-            id (str):
             kind (str):
-            href (str):
-            access_kafkas_via_private_network (bool): Indicates whether Kafkas created on this data plane cluster have to be accessed via private network
-            multi_az (bool): A flag indicating whether this cluster is available on multiple availability zones or not
+            page (int):
+            size (int):
+            total (int):
+            items ([ObjectReference]):
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
                                 drill down to the model in received_data
                                 when deserializing a response
@@ -273,19 +260,14 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            cluster_id (str): The OCM's cluster id of the registered Enterprise cluster.. [optional]  # noqa: E501
-            status (str): The status of Enterprise cluster registration. [optional]  # noqa: E501
-            cloud_provider (str): The cloud provider for this cluster. This valus will be used as the Kafka's cloud provider value when a Kafka is created on this cluster. [optional]  # noqa: E501
-            region (str): The region of this cluster. This valus will be used as the Kafka's region value when a Kafka is created on this cluster. [optional]  # noqa: E501
-            fleetshard_parameters ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -347,13 +329,13 @@
         # classes don't exist yet because their module has not finished
         # loading
         lazy_import()
         return {
           'anyOf': [
           ],
           'allOf': [
-              EnterpriseClusterListItem,
-              EnterpriseClusterWithAddonParametersAllOf,
+              AbstractList,
+              ListAllOf,
           ],
           'oneOf': [
           ],
         }
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_cluster_with_addon_parameters_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_list_all_of.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
@@ -27,15 +27,15 @@
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_kafka_mgmt_sdk.exceptions import ApiAttributeError
 
 
 
-class EnterpriseClusterWithAddonParametersAllOf(ModelNormal):
+class KafkaRequestListAllOf(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -78,35 +78,38 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
-            'fleetshard_parameters': ([bool, date, datetime, dict, float, int, list, str, none_type],),  # noqa: E501
+            'items': ([bool, date, datetime, dict, float, int, list, str, none_type],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'fleetshard_parameters': 'fleetshard_parameters',  # noqa: E501
+        'items': 'items',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
-        """EnterpriseClusterWithAddonParametersAllOf - a model defined in OpenAPI
+    def _from_openapi_data(cls, items, *args, **kwargs):  # noqa: E501
+        """KafkaRequestListAllOf - a model defined in OpenAPI
+
+        Args:
+            items ([bool, date, datetime, dict, float, int, list, str, none_type]):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -131,15 +134,14 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            fleetshard_parameters ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -163,14 +165,15 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.items = items
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -183,16 +186,19 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, *args, **kwargs):  # noqa: E501
-        """EnterpriseClusterWithAddonParametersAllOf - a model defined in OpenAPI
+    def __init__(self, items, *args, **kwargs):  # noqa: E501
+        """KafkaRequestListAllOf - a model defined in OpenAPI
+
+        Args:
+            items ([bool, date, datetime, dict, float, int, list, str, none_type]):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -217,15 +223,14 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            fleetshard_parameters ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -247,14 +252,15 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.items = items
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_osd_cluster_payload.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/enterprise_osd_cluster_payload.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/error.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/error.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/error_list.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/error_list.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/error_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/error_list_all_of.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/fleetshard_parameter.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/fleetshard_parameter.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/instant_query.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/instant_query.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_promote_request.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_promote_request.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_all_of.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_list.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_list.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list_all_of.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
@@ -27,15 +27,15 @@
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_kafka_mgmt_sdk.exceptions import ApiAttributeError
 
 
 
-class KafkaRequestListAllOf(ModelNormal):
+class ServiceAccountListAllOf(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -78,37 +78,40 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
+            'kind': (str,),  # noqa: E501
             'items': ([bool, date, datetime, dict, float, int, list, str, none_type],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
+        'kind': 'kind',  # noqa: E501
         'items': 'items',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, items, *args, **kwargs):  # noqa: E501
-        """KafkaRequestListAllOf - a model defined in OpenAPI
+    def _from_openapi_data(cls, kind, items, *args, **kwargs):  # noqa: E501
+        """ServiceAccountListAllOf - a model defined in OpenAPI
 
         Args:
+            kind (str):
             items ([bool, date, datetime, dict, float, int, list, str, none_type]):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
@@ -165,14 +168,15 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.kind = kind
         self.items = items
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
@@ -186,18 +190,19 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, items, *args, **kwargs):  # noqa: E501
-        """KafkaRequestListAllOf - a model defined in OpenAPI
+    def __init__(self, kind, items, *args, **kwargs):  # noqa: E501
+        """ServiceAccountListAllOf - a model defined in OpenAPI
 
         Args:
+            kind (str):
             items ([bool, date, datetime, dict, float, int, list, str, none_type]):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
@@ -252,14 +257,15 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.kind = kind
         self.items = items
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_payload.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_request_payload.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_update_request.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/kafka_update_request.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/list.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/list.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_instant_query_list.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_instant_query_list.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_instant_query_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_instant_query_list_all_of.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_range_query_list.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_range_query_list.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_range_query_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/metrics_range_query_list_all_of.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/object_reference.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/object_reference.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/range_query.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/range_query.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/region_capacity_list_item.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/region_capacity_list_item.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_all_of.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_types_list_all_of.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
@@ -27,15 +27,15 @@
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_kafka_mgmt_sdk.exceptions import ApiAttributeError
 
 
 
-class ServiceAccountListAllOf(ModelNormal):
+class SupportedKafkaInstanceTypesListAllOf(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -78,41 +78,35 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
-            'kind': (str,),  # noqa: E501
-            'items': ([bool, date, datetime, dict, float, int, list, str, none_type],),  # noqa: E501
+            'instance_types': ([bool, date, datetime, dict, float, int, list, str, none_type],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'kind': 'kind',  # noqa: E501
-        'items': 'items',  # noqa: E501
+        'instance_types': 'instance_types',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, kind, items, *args, **kwargs):  # noqa: E501
-        """ServiceAccountListAllOf - a model defined in OpenAPI
-
-        Args:
-            kind (str):
-            items ([bool, date, datetime, dict, float, int, list, str, none_type]):
+    def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
+        """SupportedKafkaInstanceTypesListAllOf - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -137,14 +131,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
+            instance_types ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -168,16 +163,14 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.kind = kind
-        self.items = items
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -190,20 +183,16 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, kind, items, *args, **kwargs):  # noqa: E501
-        """ServiceAccountListAllOf - a model defined in OpenAPI
-
-        Args:
-            kind (str):
-            items ([bool, date, datetime, dict, float, int, list, str, none_type]):
+    def __init__(self, *args, **kwargs):  # noqa: E501
+        """SupportedKafkaInstanceTypesListAllOf - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -228,14 +217,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
+            instance_types ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -257,16 +247,14 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.kind = kind
-        self.items = items
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list_item.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list_item.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list_item_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_list_item_all_of.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_request.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/service_account_request.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/sso_provider.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/sso_provider.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/sso_provider_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/sso_provider_all_of.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_billing_model.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_billing_model.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_type.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_type.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_type_sizes_inner.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_type_sizes_inner.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_types_list.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_types_list.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_instance_types_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/list_response.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,41 +1,41 @@
 """
-    Kafka Management API
+    Red Hat Openshift SmartEvents Fleet Manager V2
 
-    Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
+    The API exposed by the fleet manager of the SmartEvents service.  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
-    Contact: rhosak-support@redhat.com
+    The version of the OpenAPI document: 0.0.1
+    Contact: openbridge-dev@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
 
-from rhoas_kafka_mgmt_sdk.model_utils import (  # noqa: F401
+from rhoas_smart_events_mgmt_sdk.model_utils import (  # noqa: F401
     ApiTypeError,
     ModelComposed,
     ModelNormal,
     ModelSimple,
     cached_property,
     change_keys_js_to_python,
     convert_js_args_to_python_args,
     date,
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
-from rhoas_kafka_mgmt_sdk.exceptions import ApiAttributeError
+from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
 
 
 
-class SupportedKafkaInstanceTypesListAllOf(ModelNormal):
+class ListResponse(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -78,35 +78,40 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
-            'instance_types': ([bool, date, datetime, dict, float, int, list, str, none_type],),  # noqa: E501
+            'kind': (str,),  # noqa: E501
+            'items': ([{str: (bool, date, datetime, dict, float, int, list, str, none_type)}],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'instance_types': 'instance_types',  # noqa: E501
+        'kind': 'kind',  # noqa: E501
+        'items': 'items',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
-        """SupportedKafkaInstanceTypesListAllOf - a model defined in OpenAPI
+    def _from_openapi_data(cls, kind, *args, **kwargs):  # noqa: E501
+        """ListResponse - a model defined in OpenAPI
+
+        Args:
+            kind (str):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -131,15 +136,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            instance_types ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
+            items ([{str: (bool, date, datetime, dict, float, int, list, str, none_type)}]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -163,14 +168,15 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.kind = kind
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -183,16 +189,19 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, *args, **kwargs):  # noqa: E501
-        """SupportedKafkaInstanceTypesListAllOf - a model defined in OpenAPI
+    def __init__(self, kind, *args, **kwargs):  # noqa: E501
+        """ListResponse - a model defined in OpenAPI
+
+        Args:
+            kind (str):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -217,15 +226,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            instance_types ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
+            items ([{str: (bool, date, datetime, dict, float, int, list, str, none_type)}]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -247,14 +256,15 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.kind = kind
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_size.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_size.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/supported_kafka_size_bytes_value_item.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/error.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,41 +1,41 @@
 """
-    Kafka Management API
+    sso.redhat.com API documentation
 
-    Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
+    This is the API documentation for sso.redhat.com  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
-    Contact: rhosak-support@redhat.com
+    The version of the OpenAPI document: 5.0.19-SNAPSHOT
+    Contact: it-user-team-list@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
 
-from rhoas_kafka_mgmt_sdk.model_utils import (  # noqa: F401
+from rhoas_service_accounts_mgmt_sdk.model_utils import (  # noqa: F401
     ApiTypeError,
     ModelComposed,
     ModelNormal,
     ModelSimple,
     cached_property,
     change_keys_js_to_python,
     convert_js_args_to_python_args,
     date,
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
-from rhoas_kafka_mgmt_sdk.exceptions import ApiAttributeError
+from rhoas_service_accounts_mgmt_sdk.exceptions import ApiAttributeError
 
 
 
-class SupportedKafkaSizeBytesValueItem(ModelNormal):
+class Error(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -78,35 +78,38 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
-            'bytes': (int,),  # noqa: E501
+            'error': (str,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'bytes': 'bytes',  # noqa: E501
+        'error': 'error',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
-        """SupportedKafkaSizeBytesValueItem - a model defined in OpenAPI
+    def _from_openapi_data(cls, error, *args, **kwargs):  # noqa: E501
+        """Error - a model defined in OpenAPI
+
+        Args:
+            error (str): The cause of the Error.
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -131,15 +134,14 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            bytes (int): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -163,14 +165,15 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.error = error
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -183,16 +186,19 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, *args, **kwargs):  # noqa: E501
-        """SupportedKafkaSizeBytesValueItem - a model defined in OpenAPI
+    def __init__(self, error, *args, **kwargs):  # noqa: E501
+        """Error - a model defined in OpenAPI
+
+        Args:
+            error (str): The cause of the Error.
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -217,15 +223,14 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            bytes (int): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -247,14 +252,15 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.error = error
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/values.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/values.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/version_metadata.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/version_metadata.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
@@ -90,15 +90,15 @@
         """
         lazy_import()
         return {
             'id': (str,),  # noqa: E501
             'kind': (str,),  # noqa: E501
             'href': (str,),  # noqa: E501
             'server_version': (str,),  # noqa: E501
-            'collections': ([bool, date, datetime, dict, float, int, list, str, none_type],),  # noqa: E501
+            'collections': ([ObjectReference],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
@@ -149,15 +149,15 @@
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
             server_version (str): [optional]  # noqa: E501
-            collections ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
+            collections ([ObjectReference]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -257,15 +257,15 @@
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
             server_version (str): [optional]  # noqa: E501
-            collections ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
+            collections ([ObjectReference]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/version_metadata_all_of.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/errors_list.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,41 +1,45 @@
 """
-    Kafka Management API
+    Red Hat Openshift SmartEvents Fleet Manager V2
 
-    Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
+    The API exposed by the fleet manager of the SmartEvents service.  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
-    Contact: rhosak-support@redhat.com
+    The version of the OpenAPI document: 0.0.1
+    Contact: openbridge-dev@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
 
-from rhoas_kafka_mgmt_sdk.model_utils import (  # noqa: F401
+from rhoas_smart_events_mgmt_sdk.model_utils import (  # noqa: F401
     ApiTypeError,
     ModelComposed,
     ModelNormal,
     ModelSimple,
     cached_property,
     change_keys_js_to_python,
     convert_js_args_to_python_args,
     date,
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
-from rhoas_kafka_mgmt_sdk.exceptions import ApiAttributeError
+from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
 
 
+def lazy_import():
+    from rhoas_smart_events_mgmt_sdk.model.error import Error
+    globals()['Error'] = Error
 
-class VersionMetadataAllOf(ModelNormal):
+
+class ErrorsList(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -63,52 +67,57 @@
 
     @cached_property
     def additional_properties_type():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
         """
+        lazy_import()
         return (bool, date, datetime, dict, float, int, list, str, none_type,)  # noqa: E501
 
     _nullable = False
 
     @cached_property
     def openapi_types():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
+        lazy_import()
         return {
-            'server_version': (str,),  # noqa: E501
-            'collections': ([bool, date, datetime, dict, float, int, list, str, none_type],),  # noqa: E501
+            'kind': (str,),  # noqa: E501
+            'items': ([Error],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'server_version': 'server_version',  # noqa: E501
-        'collections': 'collections',  # noqa: E501
+        'kind': 'kind',  # noqa: E501
+        'items': 'items',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
-        """VersionMetadataAllOf - a model defined in OpenAPI
+    def _from_openapi_data(cls, kind, *args, **kwargs):  # noqa: E501
+        """ErrorsList - a model defined in OpenAPI
+
+        Args:
+            kind (str):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -133,16 +142,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            server_version (str): [optional]  # noqa: E501
-            collections ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
+            items ([Error]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -166,14 +174,15 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.kind = kind
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -186,16 +195,19 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, *args, **kwargs):  # noqa: E501
-        """VersionMetadataAllOf - a model defined in OpenAPI
+    def __init__(self, kind, *args, **kwargs):  # noqa: E501
+        """ErrorsList - a model defined in OpenAPI
+
+        Args:
+            kind (str):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -220,16 +232,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            server_version (str): [optional]  # noqa: E501
-            collections ([bool, date, datetime, dict, float, int, list, str, none_type]): [optional]  # noqa: E501
+            items ([Error]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -251,14 +262,15 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.kind = kind
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model_utils.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model_utils.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 from datetime import date, datetime  # noqa: F401
 from copy import deepcopy
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/models/__init__.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/models/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -12,27 +12,27 @@
 from rhoas_kafka_mgmt_sdk.model.cloud_provider import CloudProvider
 from rhoas_kafka_mgmt_sdk.model.cloud_provider_list import CloudProviderList
 from rhoas_kafka_mgmt_sdk.model.cloud_provider_list_all_of import CloudProviderListAllOf
 from rhoas_kafka_mgmt_sdk.model.cloud_region import CloudRegion
 from rhoas_kafka_mgmt_sdk.model.cloud_region_list import CloudRegionList
 from rhoas_kafka_mgmt_sdk.model.cloud_region_list_all_of import CloudRegionListAllOf
 from rhoas_kafka_mgmt_sdk.model.enterprise_cluster import EnterpriseCluster
+from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_addon_parameters import EnterpriseClusterAddonParameters
 from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_all_of import EnterpriseClusterAllOf
 from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_all_of_capacity_information import EnterpriseClusterAllOfCapacityInformation
+from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_fleetshard_parameters import EnterpriseClusterFleetshardParameters
 from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_list import EnterpriseClusterList
 from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_list_all_of import EnterpriseClusterListAllOf
-from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_list_item import EnterpriseClusterListItem
-from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_list_item_all_of import EnterpriseClusterListItemAllOf
-from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_with_addon_parameters import EnterpriseClusterWithAddonParameters
-from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_with_addon_parameters_all_of import EnterpriseClusterWithAddonParametersAllOf
+from rhoas_kafka_mgmt_sdk.model.enterprise_cluster_registration_response import EnterpriseClusterRegistrationResponse
 from rhoas_kafka_mgmt_sdk.model.enterprise_osd_cluster_payload import EnterpriseOsdClusterPayload
 from rhoas_kafka_mgmt_sdk.model.error import Error
 from rhoas_kafka_mgmt_sdk.model.error_list import ErrorList
 from rhoas_kafka_mgmt_sdk.model.error_list_all_of import ErrorListAllOf
 from rhoas_kafka_mgmt_sdk.model.fleetshard_parameter import FleetshardParameter
+from rhoas_kafka_mgmt_sdk.model.fleetshard_parameters_array import FleetshardParametersArray
 from rhoas_kafka_mgmt_sdk.model.instant_query import InstantQuery
 from rhoas_kafka_mgmt_sdk.model.kafka_promote_request import KafkaPromoteRequest
 from rhoas_kafka_mgmt_sdk.model.kafka_request import KafkaRequest
 from rhoas_kafka_mgmt_sdk.model.kafka_request_all_of import KafkaRequestAllOf
 from rhoas_kafka_mgmt_sdk.model.kafka_request_list import KafkaRequestList
 from rhoas_kafka_mgmt_sdk.model.kafka_request_list_all_of import KafkaRequestListAllOf
 from rhoas_kafka_mgmt_sdk.model.kafka_request_payload import KafkaRequestPayload
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/rest.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/rest.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 """
     Kafka Management API
 
     Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 1.15.0
+    The version of the OpenAPI document: 1.16.0
     Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import io
 import json
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/__init__.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/admin_api.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/admin_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/artifact_rules_api.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/artifact_rules_api.py`

 * *Files 0% similar despite different names*

```diff
@@ -132,15 +132,16 @@
             root_map={
                 'validations': {
                 },
                 'allowed_values': {
                     ('rule',): {
 
                         "VALIDITY": "VALIDITY",
-                        "COMPATIBILITY": "COMPATIBILITY"
+                        "COMPATIBILITY": "COMPATIBILITY",
+                        "INTEGRITY": "INTEGRITY"
                     },
                 },
                 'openapi_types': {
                     'group_id':
                         (str,),
                     'artifact_id':
                         (str,),
@@ -254,15 +255,16 @@
             root_map={
                 'validations': {
                 },
                 'allowed_values': {
                     ('rule',): {
 
                         "VALIDITY": "VALIDITY",
-                        "COMPATIBILITY": "COMPATIBILITY"
+                        "COMPATIBILITY": "COMPATIBILITY",
+                        "INTEGRITY": "INTEGRITY"
                     },
                 },
                 'openapi_types': {
                     'group_id':
                         (str,),
                     'artifact_id':
                         (str,),
@@ -438,15 +440,16 @@
             root_map={
                 'validations': {
                 },
                 'allowed_values': {
                     ('rule',): {
 
                         "VALIDITY": "VALIDITY",
-                        "COMPATIBILITY": "COMPATIBILITY"
+                        "COMPATIBILITY": "COMPATIBILITY",
+                        "INTEGRITY": "INTEGRITY"
                     },
                 },
                 'openapi_types': {
                     'group_id':
                         (str,),
                     'artifact_id':
                         (str,),
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/artifacts_api.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/artifacts_api.py`

 * *Files 1% similar despite different names*

```diff
@@ -18,20 +18,21 @@
     check_validations,
     date,
     datetime,
     file_type,
     none_type,
     validate_and_convert_types
 )
+from rhoas_registry_instance_sdk.model.artifact_content import ArtifactContent
 from rhoas_registry_instance_sdk.model.artifact_meta_data import ArtifactMetaData
 from rhoas_registry_instance_sdk.model.artifact_reference import ArtifactReference
 from rhoas_registry_instance_sdk.model.artifact_search_results import ArtifactSearchResults
-from rhoas_registry_instance_sdk.model.content_create_request import ContentCreateRequest
 from rhoas_registry_instance_sdk.model.error import Error
 from rhoas_registry_instance_sdk.model.if_exists import IfExists
+from rhoas_registry_instance_sdk.model.reference_type import ReferenceType
 from rhoas_registry_instance_sdk.model.rule_violation_error import RuleViolationError
 from rhoas_registry_instance_sdk.model.sort_by import SortBy
 from rhoas_registry_instance_sdk.model.sort_order import SortOrder
 from rhoas_registry_instance_sdk.model.update_state import UpdateState
 
 
 class ArtifactsApi(object):
@@ -663,14 +664,15 @@
                 'operation_id': 'references_by_global_id',
                 'http_method': 'GET',
                 'servers': None,
             },
             params_map={
                 'all': [
                     'global_id',
+                    'ref_type',
                 ],
                 'required': [
                     'global_id',
                 ],
                 'nullable': [
                 ],
                 'enum': [
@@ -682,20 +684,24 @@
                 'validations': {
                 },
                 'allowed_values': {
                 },
                 'openapi_types': {
                     'global_id':
                         (int,),
+                    'ref_type':
+                        (ReferenceType,),
                 },
                 'attribute_map': {
                     'global_id': 'globalId',
+                    'ref_type': 'refType',
                 },
                 'location_map': {
                     'global_id': 'path',
+                    'ref_type': 'query',
                 },
                 'collection_format_map': {
                 }
             },
             headers_map={
                 'accept': [
                     'application/json'
@@ -1383,15 +1389,15 @@
         self,
         group_id,
         artifact_id,
         **kwargs
     ):
         """Get latest artifact  # noqa: E501
 
-        Returns the latest version of the artifact in its raw form.  The `Content-Type` of the response depends on the artifact type.  In most cases, this is `application/json`, but  for some types it may be different (for example, `PROTOBUF`).  This operation may fail for one of the following reasons:  * No artifact with this `artifactId` exists (HTTP error `404`) * A server error occurred (HTTP error `500`)   # noqa: E501
+        Returns the latest version of the artifact in its raw form.  The `Content-Type` of the response depends on the artifact type.  In most cases, this is `application/json`, but  for some types it may be different (for example, `PROTOBUF`). If the latest version of the artifact is marked as `DISABLED`, the next available non-disabled version will be used.  This operation may fail for one of the following reasons:  * No artifact with this `artifactId` exists or all versions are `DISABLED` (HTTP error `404`) * A server error occurred (HTTP error `500`)   # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
 
         >>> thread = api.get_latest_artifact(group_id, artifact_id, async_req=True)
         >>> result = thread.get()
 
         Args:
@@ -1734,14 +1740,15 @@
         >>> thread = api.references_by_global_id(global_id, async_req=True)
         >>> result = thread.get()
 
         Args:
             global_id (int): Global identifier for an artifact version.
 
         Keyword Args:
+            ref_type (ReferenceType): Determines the type of reference to return, either INBOUND or OUTBOUND.  Defaults to OUTBOUND.. [optional]
             _return_http_data_only (bool): response data without head status
                 code and headers. Default is True.
             _preload_content (bool): if False, the urllib3.HTTPResponse object
                 will be returned without reading/decoding response data.
                 Default is True.
             _request_timeout (int/float/tuple): timeout setting for this request. If
                 one number provided, it will be total request timeout. It can also
@@ -1905,15 +1912,15 @@
         group_id,
         artifact_id,
         update_state,
         **kwargs
     ):
         """Update artifact state  # noqa: E501
 
-        Updates the state of the artifact.  For example, you can use this to mark the latest version of an artifact as `DEPRECATED`.  The operation changes the state of the latest  version of the artifact.  If multiple versions exist, only the most recent is changed.  This operation can fail for the following reasons:  * No artifact with this `artifactId` exists (HTTP error `404`) * A server error occurred (HTTP error `500`)   # noqa: E501
+        Updates the state of the artifact.  For example, you can use this to mark the latest version of an artifact as `DEPRECATED`. The operation changes the state of the latest version of the artifact, even if this version is `DISABLED`. If multiple versions exist, only the most recent is changed.  This operation can fail for the following reasons:  * No artifact with this `artifactId` exists (HTTP error `404`) * A server error occurred (HTTP error `500`)   # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
 
         >>> thread = api.update_artifact_state(group_id, artifact_id, update_state, async_req=True)
         >>> result = thread.get()
 
         Args:
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/groups_api.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/groups_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/metadata_api.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/metadata_api.py`

 * *Files 1% similar despite different names*

```diff
@@ -18,14 +18,15 @@
     check_validations,
     date,
     datetime,
     file_type,
     none_type,
     validate_and_convert_types
 )
+from rhoas_registry_instance_sdk.model.artifact_content import ArtifactContent
 from rhoas_registry_instance_sdk.model.artifact_meta_data import ArtifactMetaData
 from rhoas_registry_instance_sdk.model.artifact_owner import ArtifactOwner
 from rhoas_registry_instance_sdk.model.editable_meta_data import EditableMetaData
 from rhoas_registry_instance_sdk.model.error import Error
 from rhoas_registry_instance_sdk.model.version_meta_data import VersionMetaData
 
 
@@ -329,15 +330,18 @@
                 'collection_format_map': {
                 }
             },
             headers_map={
                 'accept': [
                     'application/json'
                 ],
-                'content_type': [],
+                'content_type': [
+                    'application/get.extended+json',
+                    'application/vnd.get.extended+json'
+                ]
             },
             api_client=api_client
         )
         self.update_artifact_meta_data_endpoint = _Endpoint(
             settings={
                 'response_type': None,
                 'auth': [],
@@ -625,15 +629,15 @@
         self,
         group_id,
         artifact_id,
         **kwargs
     ):
         """Get artifact metadata  # noqa: E501
 
-        Gets the metadata for an artifact in the registry.  The returned metadata includes both generated (read-only) and editable metadata (such as name and description).  This operation can fail for the following reasons:  * No artifact with this `artifactId` exists (HTTP error `404`) * A server error occurred (HTTP error `500`)  # noqa: E501
+        Gets the metadata for an artifact in the registry, based on the latest version. If the latest version of the artifact is marked as `DISABLED`, the next available non-disabled version will be used. The returned metadata includes both generated (read-only) and editable metadata (such as name and description).  This operation can fail for the following reasons:  * No artifact with this `artifactId` exists  or all versions are `DISABLED` (HTTP error `404`) * A server error occurred (HTTP error `500`)  # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
 
         >>> thread = api.get_artifact_meta_data(group_id, artifact_id, async_req=True)
         >>> result = thread.get()
 
         Args:
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/search_api.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/search_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/system_api.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/system_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/users_api.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/users_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/versions_api.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api/versions_api.py`

 * *Files 15% similar despite different names*

```diff
@@ -18,17 +18,20 @@
     check_validations,
     date,
     datetime,
     file_type,
     none_type,
     validate_and_convert_types
 )
+from rhoas_registry_instance_sdk.model.artifact_content import ArtifactContent
 from rhoas_registry_instance_sdk.model.artifact_reference import ArtifactReference
-from rhoas_registry_instance_sdk.model.content_create_request import ContentCreateRequest
+from rhoas_registry_instance_sdk.model.comment import Comment
 from rhoas_registry_instance_sdk.model.error import Error
+from rhoas_registry_instance_sdk.model.new_comment import NewComment
+from rhoas_registry_instance_sdk.model.reference_type import ReferenceType
 from rhoas_registry_instance_sdk.model.rule_violation_error import RuleViolationError
 from rhoas_registry_instance_sdk.model.update_state import UpdateState
 from rhoas_registry_instance_sdk.model.version_meta_data import VersionMetaData
 from rhoas_registry_instance_sdk.model.version_search_results import VersionSearchResults
 
 
 class VersionsApi(object):
@@ -38,14 +41,82 @@
     Do not edit the class manually.
     """
 
     def __init__(self, api_client=None):
         if api_client is None:
             api_client = ApiClient()
         self.api_client = api_client
+        self.add_artifact_version_comment_endpoint = _Endpoint(
+            settings={
+                'response_type': (Comment,),
+                'auth': [],
+                'endpoint_path': '/groups/{groupId}/artifacts/{artifactId}/versions/{version}/comments',
+                'operation_id': 'add_artifact_version_comment',
+                'http_method': 'POST',
+                'servers': None,
+            },
+            params_map={
+                'all': [
+                    'group_id',
+                    'artifact_id',
+                    'version',
+                    'new_comment',
+                ],
+                'required': [
+                    'group_id',
+                    'artifact_id',
+                    'version',
+                    'new_comment',
+                ],
+                'nullable': [
+                ],
+                'enum': [
+                ],
+                'validation': [
+                ]
+            },
+            root_map={
+                'validations': {
+                },
+                'allowed_values': {
+                },
+                'openapi_types': {
+                    'group_id':
+                        (str,),
+                    'artifact_id':
+                        (str,),
+                    'version':
+                        (str,),
+                    'new_comment':
+                        (NewComment,),
+                },
+                'attribute_map': {
+                    'group_id': 'groupId',
+                    'artifact_id': 'artifactId',
+                    'version': 'version',
+                },
+                'location_map': {
+                    'group_id': 'path',
+                    'artifact_id': 'path',
+                    'version': 'path',
+                    'new_comment': 'body',
+                },
+                'collection_format_map': {
+                }
+            },
+            headers_map={
+                'accept': [
+                    'application/json'
+                ],
+                'content_type': [
+                    'application/json'
+                ]
+            },
+            api_client=api_client
+        )
         self.create_artifact_version_endpoint = _Endpoint(
             settings={
                 'response_type': (VersionMetaData,),
                 'auth': [],
                 'endpoint_path': '/groups/{groupId}/artifacts/{artifactId}/versions',
                 'operation_id': 'create_artifact_version',
                 'http_method': 'POST',
@@ -192,14 +263,81 @@
                 'accept': [
                     'application/json'
                 ],
                 'content_type': [],
             },
             api_client=api_client
         )
+        self.delete_artifact_version_comment_endpoint = _Endpoint(
+            settings={
+                'response_type': None,
+                'auth': [],
+                'endpoint_path': '/groups/{groupId}/artifacts/{artifactId}/versions/{version}/comments/{commentId}',
+                'operation_id': 'delete_artifact_version_comment',
+                'http_method': 'DELETE',
+                'servers': None,
+            },
+            params_map={
+                'all': [
+                    'group_id',
+                    'artifact_id',
+                    'version',
+                    'comment_id',
+                ],
+                'required': [
+                    'group_id',
+                    'artifact_id',
+                    'version',
+                    'comment_id',
+                ],
+                'nullable': [
+                ],
+                'enum': [
+                ],
+                'validation': [
+                ]
+            },
+            root_map={
+                'validations': {
+                },
+                'allowed_values': {
+                },
+                'openapi_types': {
+                    'group_id':
+                        (str,),
+                    'artifact_id':
+                        (str,),
+                    'version':
+                        (str,),
+                    'comment_id':
+                        (str,),
+                },
+                'attribute_map': {
+                    'group_id': 'groupId',
+                    'artifact_id': 'artifactId',
+                    'version': 'version',
+                    'comment_id': 'commentId',
+                },
+                'location_map': {
+                    'group_id': 'path',
+                    'artifact_id': 'path',
+                    'version': 'path',
+                    'comment_id': 'path',
+                },
+                'collection_format_map': {
+                }
+            },
+            headers_map={
+                'accept': [
+                    'application/json'
+                ],
+                'content_type': [],
+            },
+            api_client=api_client
+        )
         self.get_artifact_version_endpoint = _Endpoint(
             settings={
                 'response_type': (file_type,),
                 'auth': [],
                 'endpoint_path': '/groups/{groupId}/artifacts/{artifactId}/versions/{version}',
                 'operation_id': 'get_artifact_version',
                 'http_method': 'GET',
@@ -259,28 +397,90 @@
                     '*/*',
                     'application/json'
                 ],
                 'content_type': [],
             },
             api_client=api_client
         )
+        self.get_artifact_version_comments_endpoint = _Endpoint(
+            settings={
+                'response_type': ([Comment],),
+                'auth': [],
+                'endpoint_path': '/groups/{groupId}/artifacts/{artifactId}/versions/{version}/comments',
+                'operation_id': 'get_artifact_version_comments',
+                'http_method': 'GET',
+                'servers': None,
+            },
+            params_map={
+                'all': [
+                    'group_id',
+                    'artifact_id',
+                    'version',
+                ],
+                'required': [
+                    'group_id',
+                    'artifact_id',
+                    'version',
+                ],
+                'nullable': [
+                ],
+                'enum': [
+                ],
+                'validation': [
+                ]
+            },
+            root_map={
+                'validations': {
+                },
+                'allowed_values': {
+                },
+                'openapi_types': {
+                    'group_id':
+                        (str,),
+                    'artifact_id':
+                        (str,),
+                    'version':
+                        (str,),
+                },
+                'attribute_map': {
+                    'group_id': 'groupId',
+                    'artifact_id': 'artifactId',
+                    'version': 'version',
+                },
+                'location_map': {
+                    'group_id': 'path',
+                    'artifact_id': 'path',
+                    'version': 'path',
+                },
+                'collection_format_map': {
+                }
+            },
+            headers_map={
+                'accept': [
+                    'application/json'
+                ],
+                'content_type': [],
+            },
+            api_client=api_client
+        )
         self.get_artifact_version_references_endpoint = _Endpoint(
             settings={
                 'response_type': ([ArtifactReference],),
                 'auth': [],
                 'endpoint_path': '/groups/{groupId}/artifacts/{artifactId}/versions/{version}/references',
                 'operation_id': 'get_artifact_version_references',
                 'http_method': 'GET',
                 'servers': None,
             },
             params_map={
                 'all': [
                     'group_id',
                     'artifact_id',
                     'version',
+                    'ref_type',
                 ],
                 'required': [
                     'group_id',
                     'artifact_id',
                     'version',
                 ],
                 'nullable': [
@@ -298,24 +498,28 @@
                 'openapi_types': {
                     'group_id':
                         (str,),
                     'artifact_id':
                         (str,),
                     'version':
                         (str,),
+                    'ref_type':
+                        (ReferenceType,),
                 },
                 'attribute_map': {
                     'group_id': 'groupId',
                     'artifact_id': 'artifactId',
                     'version': 'version',
+                    'ref_type': 'refType',
                 },
                 'location_map': {
                     'group_id': 'path',
                     'artifact_id': 'path',
                     'version': 'path',
+                    'ref_type': 'query',
                 },
                 'collection_format_map': {
                 }
             },
             headers_map={
                 'accept': [
                     'application/json'
@@ -385,14 +589,88 @@
                 'accept': [
                     'application/json'
                 ],
                 'content_type': [],
             },
             api_client=api_client
         )
+        self.update_artifact_version_comment_endpoint = _Endpoint(
+            settings={
+                'response_type': None,
+                'auth': [],
+                'endpoint_path': '/groups/{groupId}/artifacts/{artifactId}/versions/{version}/comments/{commentId}',
+                'operation_id': 'update_artifact_version_comment',
+                'http_method': 'PUT',
+                'servers': None,
+            },
+            params_map={
+                'all': [
+                    'group_id',
+                    'artifact_id',
+                    'version',
+                    'comment_id',
+                    'new_comment',
+                ],
+                'required': [
+                    'group_id',
+                    'artifact_id',
+                    'version',
+                    'comment_id',
+                    'new_comment',
+                ],
+                'nullable': [
+                ],
+                'enum': [
+                ],
+                'validation': [
+                ]
+            },
+            root_map={
+                'validations': {
+                },
+                'allowed_values': {
+                },
+                'openapi_types': {
+                    'group_id':
+                        (str,),
+                    'artifact_id':
+                        (str,),
+                    'version':
+                        (str,),
+                    'comment_id':
+                        (str,),
+                    'new_comment':
+                        (NewComment,),
+                },
+                'attribute_map': {
+                    'group_id': 'groupId',
+                    'artifact_id': 'artifactId',
+                    'version': 'version',
+                    'comment_id': 'commentId',
+                },
+                'location_map': {
+                    'group_id': 'path',
+                    'artifact_id': 'path',
+                    'version': 'path',
+                    'comment_id': 'path',
+                    'new_comment': 'body',
+                },
+                'collection_format_map': {
+                }
+            },
+            headers_map={
+                'accept': [
+                    'application/json'
+                ],
+                'content_type': [
+                    'application/json'
+                ]
+            },
+            api_client=api_client
+        )
         self.update_artifact_version_state_endpoint = _Endpoint(
             settings={
                 'response_type': None,
                 'auth': [],
                 'endpoint_path': '/groups/{groupId}/artifacts/{artifactId}/versions/{version}/state',
                 'operation_id': 'update_artifact_version_state',
                 'http_method': 'PUT',
@@ -454,14 +732,109 @@
                 'content_type': [
                     'application/json'
                 ]
             },
             api_client=api_client
         )
 
+    def add_artifact_version_comment(
+        self,
+        group_id,
+        artifact_id,
+        version,
+        new_comment,
+        **kwargs
+    ):
+        """Add new comment  # noqa: E501
+
+        Adds a new comment to the artifact version.  Both the `artifactId` and the unique `version` number must be provided.  This operation can fail for the following reasons:  * No artifact with this `artifactId` exists (HTTP error `404`) * No version with this `version` exists (HTTP error `404`) * A server error occurred (HTTP error `500`)   # noqa: E501
+        This method makes a synchronous HTTP request by default. To make an
+        asynchronous HTTP request, please pass async_req=True
+
+        >>> thread = api.add_artifact_version_comment(group_id, artifact_id, version, new_comment, async_req=True)
+        >>> result = thread.get()
+
+        Args:
+            group_id (str): The artifact group ID.  Must be a string provided by the client, representing the name of the grouping of artifacts.
+            artifact_id (str): The artifact ID.  Can be a string (client-provided) or UUID (server-generated), representing the unique artifact identifier.
+            version (str): The unique identifier of a specific version of the artifact content.
+            new_comment (NewComment):
+
+        Keyword Args:
+            _return_http_data_only (bool): response data without head status
+                code and headers. Default is True.
+            _preload_content (bool): if False, the urllib3.HTTPResponse object
+                will be returned without reading/decoding response data.
+                Default is True.
+            _request_timeout (int/float/tuple): timeout setting for this request. If
+                one number provided, it will be total request timeout. It can also
+                be a pair (tuple) of (connection, read) timeouts.
+                Default is None.
+            _check_input_type (bool): specifies if type checking
+                should be done one the data sent to the server.
+                Default is True.
+            _check_return_type (bool): specifies if type checking
+                should be done one the data received from the server.
+                Default is True.
+            _spec_property_naming (bool): True if the variable names in the input data
+                are serialized names, as specified in the OpenAPI document.
+                False if the variable names in the input data
+                are pythonic names, e.g. snake case (default)
+            _content_type (str/None): force body content-type.
+                Default is None and content-type will be predicted by allowed
+                content-types and body.
+            _host_index (int/None): specifies the index of the server
+                that we want to use.
+                Default is read from the configuration.
+            _request_auths (list): set to override the auth_settings for an a single
+                request; this effectively ignores the authentication
+                in the spec for a single request.
+                Default is None
+            async_req (bool): execute request asynchronously
+
+        Returns:
+            Comment
+                If the method is called asynchronously, returns the request
+                thread.
+        """
+        kwargs['async_req'] = kwargs.get(
+            'async_req', False
+        )
+        kwargs['_return_http_data_only'] = kwargs.get(
+            '_return_http_data_only', True
+        )
+        kwargs['_preload_content'] = kwargs.get(
+            '_preload_content', True
+        )
+        kwargs['_request_timeout'] = kwargs.get(
+            '_request_timeout', None
+        )
+        kwargs['_check_input_type'] = kwargs.get(
+            '_check_input_type', True
+        )
+        kwargs['_check_return_type'] = kwargs.get(
+            '_check_return_type', True
+        )
+        kwargs['_spec_property_naming'] = kwargs.get(
+            '_spec_property_naming', False
+        )
+        kwargs['_content_type'] = kwargs.get(
+            '_content_type')
+        kwargs['_host_index'] = kwargs.get('_host_index')
+        kwargs['_request_auths'] = kwargs.get('_request_auths', None)
+        kwargs['group_id'] = \
+            group_id
+        kwargs['artifact_id'] = \
+            artifact_id
+        kwargs['version'] = \
+            version
+        kwargs['new_comment'] = \
+            new_comment
+        return self.add_artifact_version_comment_endpoint.call_with_http_info(**kwargs)
+
     def create_artifact_version(
         self,
         group_id,
         artifact_id,
         body,
         **kwargs
     ):
@@ -642,14 +1015,109 @@
             group_id
         kwargs['artifact_id'] = \
             artifact_id
         kwargs['version'] = \
             version
         return self.delete_artifact_version_endpoint.call_with_http_info(**kwargs)
 
+    def delete_artifact_version_comment(
+        self,
+        group_id,
+        artifact_id,
+        version,
+        comment_id,
+        **kwargs
+    ):
+        """Delete a single comment  # noqa: E501
+
+        Deletes a single comment in an artifact version.  Only the owner of the comment can delete it.  The `artifactId`, unique `version` number, and `commentId`  must be provided.  This operation can fail for the following reasons:  * No artifact with this `artifactId` exists (HTTP error `404`) * No version with this `version` exists (HTTP error `404`) * No comment with this `commentId` exists (HTTP error `404`) * A server error occurred (HTTP error `500`)   # noqa: E501
+        This method makes a synchronous HTTP request by default. To make an
+        asynchronous HTTP request, please pass async_req=True
+
+        >>> thread = api.delete_artifact_version_comment(group_id, artifact_id, version, comment_id, async_req=True)
+        >>> result = thread.get()
+
+        Args:
+            group_id (str): The artifact group ID.  Must be a string provided by the client, representing the name of the grouping of artifacts.
+            artifact_id (str): The artifact ID.  Can be a string (client-provided) or UUID (server-generated), representing the unique artifact identifier.
+            version (str): The unique identifier of a specific version of the artifact content.
+            comment_id (str): The unique identifier of a single comment.
+
+        Keyword Args:
+            _return_http_data_only (bool): response data without head status
+                code and headers. Default is True.
+            _preload_content (bool): if False, the urllib3.HTTPResponse object
+                will be returned without reading/decoding response data.
+                Default is True.
+            _request_timeout (int/float/tuple): timeout setting for this request. If
+                one number provided, it will be total request timeout. It can also
+                be a pair (tuple) of (connection, read) timeouts.
+                Default is None.
+            _check_input_type (bool): specifies if type checking
+                should be done one the data sent to the server.
+                Default is True.
+            _check_return_type (bool): specifies if type checking
+                should be done one the data received from the server.
+                Default is True.
+            _spec_property_naming (bool): True if the variable names in the input data
+                are serialized names, as specified in the OpenAPI document.
+                False if the variable names in the input data
+                are pythonic names, e.g. snake case (default)
+            _content_type (str/None): force body content-type.
+                Default is None and content-type will be predicted by allowed
+                content-types and body.
+            _host_index (int/None): specifies the index of the server
+                that we want to use.
+                Default is read from the configuration.
+            _request_auths (list): set to override the auth_settings for an a single
+                request; this effectively ignores the authentication
+                in the spec for a single request.
+                Default is None
+            async_req (bool): execute request asynchronously
+
+        Returns:
+            None
+                If the method is called asynchronously, returns the request
+                thread.
+        """
+        kwargs['async_req'] = kwargs.get(
+            'async_req', False
+        )
+        kwargs['_return_http_data_only'] = kwargs.get(
+            '_return_http_data_only', True
+        )
+        kwargs['_preload_content'] = kwargs.get(
+            '_preload_content', True
+        )
+        kwargs['_request_timeout'] = kwargs.get(
+            '_request_timeout', None
+        )
+        kwargs['_check_input_type'] = kwargs.get(
+            '_check_input_type', True
+        )
+        kwargs['_check_return_type'] = kwargs.get(
+            '_check_return_type', True
+        )
+        kwargs['_spec_property_naming'] = kwargs.get(
+            '_spec_property_naming', False
+        )
+        kwargs['_content_type'] = kwargs.get(
+            '_content_type')
+        kwargs['_host_index'] = kwargs.get('_host_index')
+        kwargs['_request_auths'] = kwargs.get('_request_auths', None)
+        kwargs['group_id'] = \
+            group_id
+        kwargs['artifact_id'] = \
+            artifact_id
+        kwargs['version'] = \
+            version
+        kwargs['comment_id'] = \
+            comment_id
+        return self.delete_artifact_version_comment_endpoint.call_with_http_info(**kwargs)
+
     def get_artifact_version(
         self,
         group_id,
         artifact_id,
         version,
         **kwargs
     ):
@@ -734,36 +1202,128 @@
             group_id
         kwargs['artifact_id'] = \
             artifact_id
         kwargs['version'] = \
             version
         return self.get_artifact_version_endpoint.call_with_http_info(**kwargs)
 
+    def get_artifact_version_comments(
+        self,
+        group_id,
+        artifact_id,
+        version,
+        **kwargs
+    ):
+        """Get artifact version comments  # noqa: E501
+
+        Retrieves all comments for a version of an artifact.  Both the `artifactId` and the unique `version` number must be provided.  This operation can fail for the following reasons:  * No artifact with this `artifactId` exists (HTTP error `404`) * No version with this `version` exists (HTTP error `404`) * A server error occurred (HTTP error `500`)   # noqa: E501
+        This method makes a synchronous HTTP request by default. To make an
+        asynchronous HTTP request, please pass async_req=True
+
+        >>> thread = api.get_artifact_version_comments(group_id, artifact_id, version, async_req=True)
+        >>> result = thread.get()
+
+        Args:
+            group_id (str): The artifact group ID.  Must be a string provided by the client, representing the name of the grouping of artifacts.
+            artifact_id (str): The artifact ID.  Can be a string (client-provided) or UUID (server-generated), representing the unique artifact identifier.
+            version (str): The unique identifier of a specific version of the artifact content.
+
+        Keyword Args:
+            _return_http_data_only (bool): response data without head status
+                code and headers. Default is True.
+            _preload_content (bool): if False, the urllib3.HTTPResponse object
+                will be returned without reading/decoding response data.
+                Default is True.
+            _request_timeout (int/float/tuple): timeout setting for this request. If
+                one number provided, it will be total request timeout. It can also
+                be a pair (tuple) of (connection, read) timeouts.
+                Default is None.
+            _check_input_type (bool): specifies if type checking
+                should be done one the data sent to the server.
+                Default is True.
+            _check_return_type (bool): specifies if type checking
+                should be done one the data received from the server.
+                Default is True.
+            _spec_property_naming (bool): True if the variable names in the input data
+                are serialized names, as specified in the OpenAPI document.
+                False if the variable names in the input data
+                are pythonic names, e.g. snake case (default)
+            _content_type (str/None): force body content-type.
+                Default is None and content-type will be predicted by allowed
+                content-types and body.
+            _host_index (int/None): specifies the index of the server
+                that we want to use.
+                Default is read from the configuration.
+            _request_auths (list): set to override the auth_settings for an a single
+                request; this effectively ignores the authentication
+                in the spec for a single request.
+                Default is None
+            async_req (bool): execute request asynchronously
+
+        Returns:
+            [Comment]
+                If the method is called asynchronously, returns the request
+                thread.
+        """
+        kwargs['async_req'] = kwargs.get(
+            'async_req', False
+        )
+        kwargs['_return_http_data_only'] = kwargs.get(
+            '_return_http_data_only', True
+        )
+        kwargs['_preload_content'] = kwargs.get(
+            '_preload_content', True
+        )
+        kwargs['_request_timeout'] = kwargs.get(
+            '_request_timeout', None
+        )
+        kwargs['_check_input_type'] = kwargs.get(
+            '_check_input_type', True
+        )
+        kwargs['_check_return_type'] = kwargs.get(
+            '_check_return_type', True
+        )
+        kwargs['_spec_property_naming'] = kwargs.get(
+            '_spec_property_naming', False
+        )
+        kwargs['_content_type'] = kwargs.get(
+            '_content_type')
+        kwargs['_host_index'] = kwargs.get('_host_index')
+        kwargs['_request_auths'] = kwargs.get('_request_auths', None)
+        kwargs['group_id'] = \
+            group_id
+        kwargs['artifact_id'] = \
+            artifact_id
+        kwargs['version'] = \
+            version
+        return self.get_artifact_version_comments_endpoint.call_with_http_info(**kwargs)
+
     def get_artifact_version_references(
         self,
         group_id,
         artifact_id,
         version,
         **kwargs
     ):
-        """Get artifact version  # noqa: E501
+        """Get artifact version references  # noqa: E501
 
-        Retrieves a single version of the artifact content.  Both the `artifactId` and the unique `version` number must be provided.  The `Content-Type` of the response depends  on the artifact type.  In most cases, this is `application/json`, but for some types  it may be different (for example, `PROTOBUF`).  This operation can fail for the following reasons:  * No artifact with this `artifactId` exists (HTTP error `404`) * No version with this `version` exists (HTTP error `404`) * A server error occurred (HTTP error `500`)   # noqa: E501
+        Retrieves all references for a single version of an artifact.  Both the `artifactId` and the unique `version` number must be provided.  Using the `refType` query parameter, it is possible to retrieve an array of either the inbound or outbound references.  This operation can fail for the following reasons:  * No artifact with this `artifactId` exists (HTTP error `404`) * No version with this `version` exists (HTTP error `404`) * A server error occurred (HTTP error `500`)   # noqa: E501
         This method makes a synchronous HTTP request by default. To make an
         asynchronous HTTP request, please pass async_req=True
 
         >>> thread = api.get_artifact_version_references(group_id, artifact_id, version, async_req=True)
         >>> result = thread.get()
 
         Args:
             group_id (str): The artifact group ID.  Must be a string provided by the client, representing the name of the grouping of artifacts.
             artifact_id (str): The artifact ID.  Can be a string (client-provided) or UUID (server-generated), representing the unique artifact identifier.
             version (str): The unique identifier of a specific version of the artifact content.
 
         Keyword Args:
+            ref_type (ReferenceType): Determines the type of reference to return, either INBOUND or OUTBOUND.  Defaults to OUTBOUND.. [optional]
             _return_http_data_only (bool): response data without head status
                 code and headers. Default is True.
             _preload_content (bool): if False, the urllib3.HTTPResponse object
                 will be returned without reading/decoding response data.
                 Default is True.
             _request_timeout (int/float/tuple): timeout setting for this request. If
                 one number provided, it will be total request timeout. It can also
@@ -914,14 +1474,113 @@
         kwargs['_request_auths'] = kwargs.get('_request_auths', None)
         kwargs['group_id'] = \
             group_id
         kwargs['artifact_id'] = \
             artifact_id
         return self.list_artifact_versions_endpoint.call_with_http_info(**kwargs)
 
+    def update_artifact_version_comment(
+        self,
+        group_id,
+        artifact_id,
+        version,
+        comment_id,
+        new_comment,
+        **kwargs
+    ):
+        """Update a comment  # noqa: E501
+
+        Updates the value of a single comment in an artifact version.  Only the owner of the comment can modify it.  The `artifactId`, unique `version` number, and `commentId`  must be provided.  This operation can fail for the following reasons:  * No artifact with this `artifactId` exists (HTTP error `404`) * No version with this `version` exists (HTTP error `404`) * No comment with this `commentId` exists (HTTP error `404`) * A server error occurred (HTTP error `500`)   # noqa: E501
+        This method makes a synchronous HTTP request by default. To make an
+        asynchronous HTTP request, please pass async_req=True
+
+        >>> thread = api.update_artifact_version_comment(group_id, artifact_id, version, comment_id, new_comment, async_req=True)
+        >>> result = thread.get()
+
+        Args:
+            group_id (str): The artifact group ID.  Must be a string provided by the client, representing the name of the grouping of artifacts.
+            artifact_id (str): The artifact ID.  Can be a string (client-provided) or UUID (server-generated), representing the unique artifact identifier.
+            version (str): The unique identifier of a specific version of the artifact content.
+            comment_id (str): The unique identifier of a single comment.
+            new_comment (NewComment):
+
+        Keyword Args:
+            _return_http_data_only (bool): response data without head status
+                code and headers. Default is True.
+            _preload_content (bool): if False, the urllib3.HTTPResponse object
+                will be returned without reading/decoding response data.
+                Default is True.
+            _request_timeout (int/float/tuple): timeout setting for this request. If
+                one number provided, it will be total request timeout. It can also
+                be a pair (tuple) of (connection, read) timeouts.
+                Default is None.
+            _check_input_type (bool): specifies if type checking
+                should be done one the data sent to the server.
+                Default is True.
+            _check_return_type (bool): specifies if type checking
+                should be done one the data received from the server.
+                Default is True.
+            _spec_property_naming (bool): True if the variable names in the input data
+                are serialized names, as specified in the OpenAPI document.
+                False if the variable names in the input data
+                are pythonic names, e.g. snake case (default)
+            _content_type (str/None): force body content-type.
+                Default is None and content-type will be predicted by allowed
+                content-types and body.
+            _host_index (int/None): specifies the index of the server
+                that we want to use.
+                Default is read from the configuration.
+            _request_auths (list): set to override the auth_settings for an a single
+                request; this effectively ignores the authentication
+                in the spec for a single request.
+                Default is None
+            async_req (bool): execute request asynchronously
+
+        Returns:
+            None
+                If the method is called asynchronously, returns the request
+                thread.
+        """
+        kwargs['async_req'] = kwargs.get(
+            'async_req', False
+        )
+        kwargs['_return_http_data_only'] = kwargs.get(
+            '_return_http_data_only', True
+        )
+        kwargs['_preload_content'] = kwargs.get(
+            '_preload_content', True
+        )
+        kwargs['_request_timeout'] = kwargs.get(
+            '_request_timeout', None
+        )
+        kwargs['_check_input_type'] = kwargs.get(
+            '_check_input_type', True
+        )
+        kwargs['_check_return_type'] = kwargs.get(
+            '_check_return_type', True
+        )
+        kwargs['_spec_property_naming'] = kwargs.get(
+            '_spec_property_naming', False
+        )
+        kwargs['_content_type'] = kwargs.get(
+            '_content_type')
+        kwargs['_host_index'] = kwargs.get('_host_index')
+        kwargs['_request_auths'] = kwargs.get('_request_auths', None)
+        kwargs['group_id'] = \
+            group_id
+        kwargs['artifact_id'] = \
+            artifact_id
+        kwargs['version'] = \
+            version
+        kwargs['comment_id'] = \
+            comment_id
+        kwargs['new_comment'] = \
+            new_comment
+        return self.update_artifact_version_comment_endpoint.call_with_http_info(**kwargs)
+
     def update_artifact_version_state(
         self,
         group_id,
         artifact_id,
         version,
         update_state,
         **kwargs
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api_client.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/api_client.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/apis/__init__.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/apis/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/configuration.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/configuration.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/exceptions.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/exceptions.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_meta_data.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_meta_data.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_owner.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_owner.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_reference.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_reference.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_search_results.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_search_results.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_state.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_state.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_type_info.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_type_info.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/configuration_property.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/configuration_property.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/content_create_request.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/artifact_content.py`

 * *Files 2% similar despite different names*

```diff
@@ -31,15 +31,15 @@
 
 
 def lazy_import():
     from rhoas_registry_instance_sdk.model.artifact_reference import ArtifactReference
     globals()['ArtifactReference'] = ArtifactReference
 
 
-class ContentCreateRequest(ModelNormal):
+class ArtifactContent(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -106,15 +106,15 @@
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
     def _from_openapi_data(cls, content, references, *args, **kwargs):  # noqa: E501
-        """ContentCreateRequest - a model defined in OpenAPI
+        """ArtifactContent - a model defined in OpenAPI
 
         Args:
             content (str): Raw content of the artifact or a valid (and accessible) URL where the content can be found.
             references ([ArtifactReference]): Collection of references to other artifacts.
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
@@ -197,15 +197,15 @@
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, content, references, *args, **kwargs):  # noqa: E501
-        """ContentCreateRequest - a model defined in OpenAPI
+        """ArtifactContent - a model defined in OpenAPI
 
         Args:
             content (str): Raw content of the artifact or a valid (and accessible) URL where the content can be found.
             references ([ArtifactReference]): Collection of references to other artifacts.
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/create_group_meta_data.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/create_group_meta_data.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/download_ref.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/download_ref.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/editable_meta_data.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/editable_meta_data.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/error.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/error.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/group_meta_data.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/group_meta_data.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/group_search_results.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/group_search_results.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/if_exists.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/if_exists.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/limits.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/limits.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/log_configuration.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/log_configuration.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/log_level.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/log_level.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/named_log_configuration.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/named_log_configuration.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/named_log_configuration_all_of.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/named_log_configuration_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/properties.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/properties.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/role_mapping.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/role_mapping.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/role_type.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/role_type.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_type.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_type.py`

 * *Files 2% similar despite different names*

```diff
@@ -51,14 +51,15 @@
           as additional properties values.
     """
 
     allowed_values = {
         ('value',): {
             'VALIDITY': "VALIDITY",
             'COMPATIBILITY': "COMPATIBILITY",
+            'INTEGRITY': "INTEGRITY",
         },
     }
 
     validations = {
     }
 
     additional_properties_type = None
@@ -102,18 +103,18 @@
     @convert_js_args_to_python_args
     def __init__(self, *args, **kwargs):
         """RuleType - a model defined in OpenAPI
 
         Note that value can be passed either in args or in kwargs, but not in both.
 
         Args:
-            args[0] (str): ., must be one of ["VALIDITY", "COMPATIBILITY", ]  # noqa: E501
+            args[0] (str): ., must be one of ["VALIDITY", "COMPATIBILITY", "INTEGRITY", ]  # noqa: E501
 
         Keyword Args:
-            value (str): ., must be one of ["VALIDITY", "COMPATIBILITY", ]  # noqa: E501
+            value (str): ., must be one of ["VALIDITY", "COMPATIBILITY", "INTEGRITY", ]  # noqa: E501
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
                                 drill down to the model in received_data
                                 when deserializing a response
@@ -196,18 +197,18 @@
     @convert_js_args_to_python_args
     def _from_openapi_data(cls, *args, **kwargs):
         """RuleType - a model defined in OpenAPI
 
         Note that value can be passed either in args or in kwargs, but not in both.
 
         Args:
-            args[0] (str): ., must be one of ["VALIDITY", "COMPATIBILITY", ]  # noqa: E501
+            args[0] (str): ., must be one of ["VALIDITY", "COMPATIBILITY", "INTEGRITY", ]  # noqa: E501
 
         Keyword Args:
-            value (str): ., must be one of ["VALIDITY", "COMPATIBILITY", ]  # noqa: E501
+            value (str): ., must be one of ["VALIDITY", "COMPATIBILITY", "INTEGRITY", ]  # noqa: E501
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
                                 drill down to the model in received_data
                                 when deserializing a response
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_violation_cause.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_violation_cause.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_violation_error.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_violation_error.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_violation_error_all_of.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/rule_violation_error_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/searched_artifact.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/searched_artifact.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/searched_group.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/searched_group.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/searched_version.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/searched_version.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/sort_by.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/sort_by.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/sort_order.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/sort_order.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/system_info.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/system_info.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/update_configuration_property.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/update_configuration_property.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/update_role.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/update_role.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/update_state.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/update_state.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/user_info.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/user_info.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/version_meta_data.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/version_meta_data.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/version_search_results.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/version_search_results.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model_utils.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model_utils.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/models/__init__.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/models/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,35 +5,38 @@
 # raise a RecursionError
 # to avoid this, import only the models that you directly need like:
 # from from rhoas_registry_instance_sdk.model.pet import Pet
 # or import this package, but before doing it, use:
 # import sys
 # sys.setrecursionlimit(n)
 
+from rhoas_registry_instance_sdk.model.artifact_content import ArtifactContent
 from rhoas_registry_instance_sdk.model.artifact_meta_data import ArtifactMetaData
 from rhoas_registry_instance_sdk.model.artifact_owner import ArtifactOwner
 from rhoas_registry_instance_sdk.model.artifact_reference import ArtifactReference
 from rhoas_registry_instance_sdk.model.artifact_search_results import ArtifactSearchResults
 from rhoas_registry_instance_sdk.model.artifact_state import ArtifactState
 from rhoas_registry_instance_sdk.model.artifact_type_info import ArtifactTypeInfo
+from rhoas_registry_instance_sdk.model.comment import Comment
 from rhoas_registry_instance_sdk.model.configuration_property import ConfigurationProperty
-from rhoas_registry_instance_sdk.model.content_create_request import ContentCreateRequest
 from rhoas_registry_instance_sdk.model.create_group_meta_data import CreateGroupMetaData
 from rhoas_registry_instance_sdk.model.download_ref import DownloadRef
 from rhoas_registry_instance_sdk.model.editable_meta_data import EditableMetaData
 from rhoas_registry_instance_sdk.model.error import Error
 from rhoas_registry_instance_sdk.model.group_meta_data import GroupMetaData
 from rhoas_registry_instance_sdk.model.group_search_results import GroupSearchResults
 from rhoas_registry_instance_sdk.model.if_exists import IfExists
 from rhoas_registry_instance_sdk.model.limits import Limits
 from rhoas_registry_instance_sdk.model.log_configuration import LogConfiguration
 from rhoas_registry_instance_sdk.model.log_level import LogLevel
 from rhoas_registry_instance_sdk.model.named_log_configuration import NamedLogConfiguration
 from rhoas_registry_instance_sdk.model.named_log_configuration_all_of import NamedLogConfigurationAllOf
+from rhoas_registry_instance_sdk.model.new_comment import NewComment
 from rhoas_registry_instance_sdk.model.properties import Properties
+from rhoas_registry_instance_sdk.model.reference_type import ReferenceType
 from rhoas_registry_instance_sdk.model.role_mapping import RoleMapping
 from rhoas_registry_instance_sdk.model.role_type import RoleType
 from rhoas_registry_instance_sdk.model.rule import Rule
 from rhoas_registry_instance_sdk.model.rule_type import RuleType
 from rhoas_registry_instance_sdk.model.rule_violation_cause import RuleViolationCause
 from rhoas_registry_instance_sdk.model.rule_violation_error import RuleViolationError
 from rhoas_registry_instance_sdk.model.rule_violation_error_all_of import RuleViolationErrorAllOf
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/rest.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/rest.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/__init__.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api/default_api.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api/default_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api/errors_api.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api/errors_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api/registries_api.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api/registries_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api_client.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/api_client.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/apis/__init__.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/apis/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/configuration.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/configuration.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/exceptions.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/exceptions.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/abstract_list.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/abstract_list.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/empty.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/empty.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error_all_of.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error_list.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error_list.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/error_list_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/list.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_list.py`

 * *Files 2% similar despite different names*

```diff
@@ -28,22 +28,22 @@
     OpenApiModel
 )
 from rhoas_service_registry_mgmt_sdk.exceptions import ApiAttributeError
 
 
 def lazy_import():
     from rhoas_service_registry_mgmt_sdk.model.abstract_list import AbstractList
-    from rhoas_service_registry_mgmt_sdk.model.list_all_of import ListAllOf
-    from rhoas_service_registry_mgmt_sdk.model.object_reference import ObjectReference
+    from rhoas_service_registry_mgmt_sdk.model.registry import Registry
+    from rhoas_service_registry_mgmt_sdk.model.registry_list_all_of import RegistryListAllOf
     globals()['AbstractList'] = AbstractList
-    globals()['ListAllOf'] = ListAllOf
-    globals()['ObjectReference'] = ObjectReference
+    globals()['Registry'] = Registry
+    globals()['RegistryListAllOf'] = RegistryListAllOf
 
 
-class List(ModelComposed):
+class RegistryList(ModelComposed):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -92,15 +92,15 @@
         """
         lazy_import()
         return {
             'kind': (str,),  # noqa: E501
             'page': (int,),  # noqa: E501
             'size': (int,),  # noqa: E501
             'total': (int,),  # noqa: E501
-            'items': ([ObjectReference],),  # noqa: E501
+            'items': ([Registry],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
@@ -114,22 +114,22 @@
 
     read_only_vars = {
     }
 
     @classmethod
     @convert_js_args_to_python_args
     def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
-        """List - a model defined in OpenAPI
+        """RegistryList - a model defined in OpenAPI
 
         Keyword Args:
             kind (str):
             page (int):
             size (int):
             total (int):
-            items ([ObjectReference]):
+            items ([Registry]):
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
                                 drill down to the model in received_data
                                 when deserializing a response
@@ -222,22 +222,22 @@
         '_composed_instances',
         '_var_name_to_model_instances',
         '_additional_properties_model_instances',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, *args, **kwargs):  # noqa: E501
-        """List - a model defined in OpenAPI
+        """RegistryList - a model defined in OpenAPI
 
         Keyword Args:
             kind (str):
             page (int):
             size (int):
             total (int):
-            items ([ObjectReference]):
+            items ([Registry]):
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
                                 drill down to the model in received_data
                                 when deserializing a response
@@ -330,12 +330,12 @@
         # loading
         lazy_import()
         return {
           'anyOf': [
           ],
           'allOf': [
               AbstractList,
-              ListAllOf,
+              RegistryListAllOf,
           ],
           'oneOf': [
           ],
         }
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/list_all_of.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/list_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/object_reference.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/object_reference.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_create.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_create.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_instance_type_value.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_instance_type_value.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_list.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/list.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,49 +1,47 @@
 """
-    Service Registry Management API
+    Red Hat Openshift SmartEvents Fleet Manager V2
 
-    Service Registry Management API is a REST API for managing Service Registry instances. Service Registry is a datastore for event schemas and API designs, which is based on the open source Apicurio Registry project.  # noqa: E501
+    The API exposed by the fleet manager of the SmartEvents service.  # noqa: E501
 
-    The version of the OpenAPI document: 1.0.0
-    Contact: rhosak-eval-support@redhat.com
+    The version of the OpenAPI document: 0.0.1
+    Contact: openbridge-dev@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
 
-from rhoas_service_registry_mgmt_sdk.model_utils import (  # noqa: F401
+from rhoas_smart_events_mgmt_sdk.model_utils import (  # noqa: F401
     ApiTypeError,
     ModelComposed,
     ModelNormal,
     ModelSimple,
     cached_property,
     change_keys_js_to_python,
     convert_js_args_to_python_args,
     date,
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
-from rhoas_service_registry_mgmt_sdk.exceptions import ApiAttributeError
+from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
 
 
 def lazy_import():
-    from rhoas_service_registry_mgmt_sdk.model.abstract_list import AbstractList
-    from rhoas_service_registry_mgmt_sdk.model.registry import Registry
-    from rhoas_service_registry_mgmt_sdk.model.registry_list_all_of import RegistryListAllOf
-    globals()['AbstractList'] = AbstractList
-    globals()['Registry'] = Registry
-    globals()['RegistryListAllOf'] = RegistryListAllOf
+    from rhoas_smart_events_mgmt_sdk.model.list_all_of import ListAllOf
+    from rhoas_smart_events_mgmt_sdk.model.list_response import ListResponse
+    globals()['ListAllOf'] = ListAllOf
+    globals()['ListResponse'] = ListResponse
 
 
-class RegistryList(ModelComposed):
+class List(ModelComposed):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -92,15 +90,15 @@
         """
         lazy_import()
         return {
             'kind': (str,),  # noqa: E501
             'page': (int,),  # noqa: E501
             'size': (int,),  # noqa: E501
             'total': (int,),  # noqa: E501
-            'items': ([Registry],),  # noqa: E501
+            'items': ([{str: (bool, date, datetime, dict, float, int, list, str, none_type)}],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
@@ -114,22 +112,21 @@
 
     read_only_vars = {
     }
 
     @classmethod
     @convert_js_args_to_python_args
     def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
-        """RegistryList - a model defined in OpenAPI
+        """List - a model defined in OpenAPI
 
         Keyword Args:
             kind (str):
             page (int):
             size (int):
             total (int):
-            items ([Registry]):
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
                                 drill down to the model in received_data
                                 when deserializing a response
@@ -152,14 +149,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
+            items ([{str: (bool, date, datetime, dict, float, int, list, str, none_type)}]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -222,22 +220,21 @@
         '_composed_instances',
         '_var_name_to_model_instances',
         '_additional_properties_model_instances',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, *args, **kwargs):  # noqa: E501
-        """RegistryList - a model defined in OpenAPI
+        """List - a model defined in OpenAPI
 
         Keyword Args:
             kind (str):
             page (int):
             size (int):
             total (int):
-            items ([Registry]):
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
                                 drill down to the model in received_data
                                 when deserializing a response
@@ -260,14 +257,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
+            items ([{str: (bool, date, datetime, dict, float, int, list, str, none_type)}]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -329,13 +327,13 @@
         # classes don't exist yet because their module has not finished
         # loading
         lazy_import()
         return {
           'anyOf': [
           ],
           'allOf': [
-              AbstractList,
-              RegistryListAllOf,
+              ListAllOf,
+              ListResponse,
           ],
           'oneOf': [
           ],
         }
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_list_all_of.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_list_all_of.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_status_value.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/registry_status_value.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/root_type_for_registry.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/root_type_for_registry.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/service_status.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model/service_status.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model_utils.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/model_utils.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/models/__init__.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/models/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/rest.py` & `rhoas_sdks-1.0.3/sdks/registry_mgmt_sdk/rhoas_service_registry_mgmt_sdk/rest.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/__init__.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api/acs_tenants_api.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api/acs_tenants_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api/default_api.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api/default_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api/service_accounts_api.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api/service_accounts_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api_client.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/api_client.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/apis/__init__.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/apis/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/configuration.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/configuration.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/exceptions.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/exceptions.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/acs_client_request_data.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/acs_client_request_data.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/acs_client_response_data.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/acs_client_response_data.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/authentication_factors.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/authentication_factors.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/authentication_policy.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/authentication_policy.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/error.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/otp.py`

 * *Files 3% similar despite different names*

```diff
@@ -27,15 +27,15 @@
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_service_accounts_mgmt_sdk.exceptions import ApiAttributeError
 
 
 
-class Error(ModelNormal):
+class Otp(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -78,38 +78,35 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
-            'error': (str,),  # noqa: E501
+            'required': (bool,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'error': 'error',  # noqa: E501
+        'required': 'required',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, error, *args, **kwargs):  # noqa: E501
-        """Error - a model defined in OpenAPI
-
-        Args:
-            error (str): The cause of the Error.
+    def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
+        """Otp - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -134,14 +131,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
+            required (bool): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -165,15 +163,14 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.error = error
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -186,19 +183,16 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, error, *args, **kwargs):  # noqa: E501
-        """Error - a model defined in OpenAPI
-
-        Args:
-            error (str): The cause of the Error.
+    def __init__(self, *args, **kwargs):  # noqa: E501
+        """Otp - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -223,14 +217,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
+            required (bool): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -252,15 +247,14 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.error = error
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/otp.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/service_account_create_request_data.py`

 * *Files 4% similar despite different names*

```diff
@@ -27,15 +27,15 @@
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_service_accounts_mgmt_sdk.exceptions import ApiAttributeError
 
 
 
-class Otp(ModelNormal):
+class ServiceAccountCreateRequestData(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -55,14 +55,22 @@
           as additional properties values.
     """
 
     allowed_values = {
     }
 
     validations = {
+        ('name',): {
+            'max_length': 50,
+            'min_length': 1,
+        },
+        ('description',): {
+            'max_length': 255,
+            'min_length': 0,
+        },
     }
 
     @cached_property
     def additional_properties_type():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
@@ -78,35 +86,40 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
-            'required': (bool,),  # noqa: E501
+            'name': (str,),  # noqa: E501
+            'description': (str,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'required': 'required',  # noqa: E501
+        'name': 'name',  # noqa: E501
+        'description': 'description',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
-        """Otp - a model defined in OpenAPI
+    def _from_openapi_data(cls, name, *args, **kwargs):  # noqa: E501
+        """ServiceAccountCreateRequestData - a model defined in OpenAPI
+
+        Args:
+            name (str):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -131,15 +144,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            required (bool): [optional]  # noqa: E501
+            description (str): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -163,14 +176,15 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.name = name
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -183,16 +197,19 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, *args, **kwargs):  # noqa: E501
-        """Otp - a model defined in OpenAPI
+    def __init__(self, name, *args, **kwargs):  # noqa: E501
+        """ServiceAccountCreateRequestData - a model defined in OpenAPI
+
+        Args:
+            name (str):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -217,15 +234,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            required (bool): [optional]  # noqa: E501
+            description (str): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -247,14 +264,15 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.name = name
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/red_hat_error_representation.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/red_hat_error_representation.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/service_account_create_request_data.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/service_account_request_data.py`

 * *Files 2% similar despite different names*

```diff
@@ -27,15 +27,15 @@
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_service_accounts_mgmt_sdk.exceptions import ApiAttributeError
 
 
 
-class ServiceAccountCreateRequestData(ModelNormal):
+class ServiceAccountRequestData(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -107,19 +107,16 @@
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, name, *args, **kwargs):  # noqa: E501
-        """ServiceAccountCreateRequestData - a model defined in OpenAPI
-
-        Args:
-            name (str):
+    def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
+        """ServiceAccountRequestData - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -144,14 +141,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
+            name (str): [optional]  # noqa: E501
             description (str): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
@@ -176,15 +174,14 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.name = name
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -197,19 +194,16 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, name, *args, **kwargs):  # noqa: E501
-        """ServiceAccountCreateRequestData - a model defined in OpenAPI
-
-        Args:
-            name (str):
+    def __init__(self, *args, **kwargs):  # noqa: E501
+        """ServiceAccountRequestData - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -234,14 +228,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
+            name (str): [optional]  # noqa: E501
             description (str): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
@@ -264,15 +259,14 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.name = name
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/service_account_data.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/service_account_data.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/service_account_request_data.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/validation_exception_data.py`

 * *Files 2% similar despite different names*

```diff
@@ -27,15 +27,15 @@
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_service_accounts_mgmt_sdk.exceptions import ApiAttributeError
 
 
 
-class ServiceAccountRequestData(ModelNormal):
+class ValidationExceptionData(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -55,22 +55,14 @@
           as additional properties values.
     """
 
     allowed_values = {
     }
 
     validations = {
-        ('name',): {
-            'max_length': 50,
-            'min_length': 1,
-        },
-        ('description',): {
-            'max_length': 255,
-            'min_length': 0,
-        },
     }
 
     @cached_property
     def additional_properties_type():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
@@ -86,37 +78,39 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
-            'name': (str,),  # noqa: E501
-            'description': (str,),  # noqa: E501
+            'fields': ({str: (str,)},),  # noqa: E501
+            'error': (str,),  # noqa: E501
+            'error_description': (str,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'name': 'name',  # noqa: E501
-        'description': 'description',  # noqa: E501
+        'fields': 'fields',  # noqa: E501
+        'error': 'error',  # noqa: E501
+        'error_description': 'error_description',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
     def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
-        """ServiceAccountRequestData - a model defined in OpenAPI
+        """ValidationExceptionData - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -141,16 +135,17 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            name (str): [optional]  # noqa: E501
-            description (str): [optional]  # noqa: E501
+            fields ({str: (str,)}): [optional]  # noqa: E501
+            error (str): [optional]  # noqa: E501
+            error_description (str): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -195,15 +190,15 @@
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, *args, **kwargs):  # noqa: E501
-        """ServiceAccountRequestData - a model defined in OpenAPI
+        """ValidationExceptionData - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -228,16 +223,17 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            name (str): [optional]  # noqa: E501
-            description (str): [optional]  # noqa: E501
+            fields ({str: (str,)}): [optional]  # noqa: E501
+            error (str): [optional]  # noqa: E501
+            error_description (str): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model/validation_exception_data.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/list_all_of.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,41 +1,41 @@
 """
-    sso.redhat.com API documentation
+    Red Hat Openshift SmartEvents Fleet Manager V2
 
-    This is the API documentation for sso.redhat.com  # noqa: E501
+    The API exposed by the fleet manager of the SmartEvents service.  # noqa: E501
 
-    The version of the OpenAPI document: 5.0.19-SNAPSHOT
-    Contact: it-user-team-list@redhat.com
+    The version of the OpenAPI document: 0.0.1
+    Contact: openbridge-dev@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
 
-from rhoas_service_accounts_mgmt_sdk.model_utils import (  # noqa: F401
+from rhoas_smart_events_mgmt_sdk.model_utils import (  # noqa: F401
     ApiTypeError,
     ModelComposed,
     ModelNormal,
     ModelSimple,
     cached_property,
     change_keys_js_to_python,
     convert_js_args_to_python_args,
     date,
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
-from rhoas_service_accounts_mgmt_sdk.exceptions import ApiAttributeError
+from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
 
 
 
-class ValidationExceptionData(ModelNormal):
+class ListAllOf(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -78,39 +78,44 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
-            'fields': ({str: (str,)},),  # noqa: E501
-            'error': (str,),  # noqa: E501
-            'error_description': (str,),  # noqa: E501
+            'page': (int,),  # noqa: E501
+            'size': (int,),  # noqa: E501
+            'total': (int,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'fields': 'fields',  # noqa: E501
-        'error': 'error',  # noqa: E501
-        'error_description': 'error_description',  # noqa: E501
+        'page': 'page',  # noqa: E501
+        'size': 'size',  # noqa: E501
+        'total': 'total',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
-        """ValidationExceptionData - a model defined in OpenAPI
+    def _from_openapi_data(cls, page, size, total, *args, **kwargs):  # noqa: E501
+        """ListAllOf - a model defined in OpenAPI
+
+        Args:
+            page (int):
+            size (int):
+            total (int):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -135,17 +140,14 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            fields ({str: (str,)}): [optional]  # noqa: E501
-            error (str): [optional]  # noqa: E501
-            error_description (str): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -169,14 +171,17 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.page = page
+        self.size = size
+        self.total = total
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -189,16 +194,21 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, *args, **kwargs):  # noqa: E501
-        """ValidationExceptionData - a model defined in OpenAPI
+    def __init__(self, page, size, total, *args, **kwargs):  # noqa: E501
+        """ListAllOf - a model defined in OpenAPI
+
+        Args:
+            page (int):
+            size (int):
+            total (int):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -223,17 +233,14 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            fields ({str: (str,)}): [optional]  # noqa: E501
-            error (str): [optional]  # noqa: E501
-            error_description (str): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -255,14 +262,17 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.page = page
+        self.size = size
+        self.total = total
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model_utils.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/model_utils.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/models/__init__.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/models/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/rest.py` & `rhoas_sdks-1.0.3/sdks/service_accounts_mgmt_sdk/rhoas_service_accounts_mgmt_sdk/rest.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/__init__.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/bridges_api.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/bridges_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/cloud_providers_api.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/cloud_providers_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/error_catalog_api.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/error_catalog_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/processors_api.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/processors_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/sink_connectors_api.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/sink_connectors_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/source_connectors_api.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api/source_connectors_api.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api_client.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/api_client.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/apis/__init__.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/apis/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/configuration.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/configuration.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/exceptions.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/exceptions.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_error.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_error.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_error_instance.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_error_instance.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_error_type.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_error_type.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_list_response.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_list_response.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_request.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_request.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_response.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/bridge_response.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_provider_list_response.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_provider_list_response.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_provider_response.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_provider_response.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_region_list_response.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_region_list_response.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_region_response.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/cloud_region_response.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/connector_request.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/connector_request.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/error.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/error.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/error_list_response.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/error_list_response.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/errors_list.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processor_request.py`

 * *Files 5% similar despite different names*

```diff
@@ -26,20 +26,16 @@
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
 
 
-def lazy_import():
-    from rhoas_smart_events_mgmt_sdk.model.error import Error
-    globals()['Error'] = Error
 
-
-class ErrorsList(ModelNormal):
+class ProcessorRequest(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -59,65 +55,67 @@
           as additional properties values.
     """
 
     allowed_values = {
     }
 
     validations = {
+        ('name',): {
+            'min_length': 1,
+        },
     }
 
     @cached_property
     def additional_properties_type():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
         """
-        lazy_import()
         return (bool, date, datetime, dict, float, int, list, str, none_type,)  # noqa: E501
 
     _nullable = False
 
     @cached_property
     def openapi_types():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
-        lazy_import()
         return {
-            'kind': (str,),  # noqa: E501
-            'items': ([Error],),  # noqa: E501
+            'name': (str,),  # noqa: E501
+            'flows': ({str: (bool, date, datetime, dict, float, int, list, str, none_type)},),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'kind': 'kind',  # noqa: E501
-        'items': 'items',  # noqa: E501
+        'name': 'name',  # noqa: E501
+        'flows': 'flows',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, kind, *args, **kwargs):  # noqa: E501
-        """ErrorsList - a model defined in OpenAPI
+    def _from_openapi_data(cls, name, flows, *args, **kwargs):  # noqa: E501
+        """ProcessorRequest - a model defined in OpenAPI
 
         Args:
-            kind (str):
+            name (str): The name of the processor
+            flows ({str: (bool, date, datetime, dict, float, int, list, str, none_type)}): The Camel YAML DSL code, formatted as JSON, that defines the flows in the processor
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -142,15 +140,14 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            items ([Error]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -174,15 +171,16 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.kind = kind
+        self.name = name
+        self.flows = flows
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -195,19 +193,20 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, kind, *args, **kwargs):  # noqa: E501
-        """ErrorsList - a model defined in OpenAPI
+    def __init__(self, name, flows, *args, **kwargs):  # noqa: E501
+        """ProcessorRequest - a model defined in OpenAPI
 
         Args:
-            kind (str):
+            name (str): The name of the processor
+            flows ({str: (bool, date, datetime, dict, float, int, list, str, none_type)}): The Camel YAML DSL code, formatted as JSON, that defines the flows in the processor
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -232,15 +231,14 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            items ([Error]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -262,15 +260,16 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.kind = kind
+        self.name = name
+        self.flows = flows
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/list.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processing_error_list_response.py`

 * *Files 8% similar despite different names*

```diff
@@ -27,21 +27,19 @@
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
 
 
 def lazy_import():
-    from rhoas_smart_events_mgmt_sdk.model.list_all_of import ListAllOf
-    from rhoas_smart_events_mgmt_sdk.model.list_response import ListResponse
-    globals()['ListAllOf'] = ListAllOf
-    globals()['ListResponse'] = ListResponse
+    from rhoas_smart_events_mgmt_sdk.model.processing_error_response import ProcessingErrorResponse
+    globals()['ProcessingErrorResponse'] = ProcessingErrorResponse
 
 
-class List(ModelComposed):
+class ProcessingErrorListResponse(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -90,15 +88,15 @@
         """
         lazy_import()
         return {
             'kind': (str,),  # noqa: E501
             'page': (int,),  # noqa: E501
             'size': (int,),  # noqa: E501
             'total': (int,),  # noqa: E501
-            'items': ([{str: (bool, date, datetime, dict, float, int, list, str, none_type)}],),  # noqa: E501
+            'items': ([ProcessingErrorResponse],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
@@ -109,24 +107,28 @@
         'total': 'total',  # noqa: E501
         'items': 'items',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
+    _composed_schemas = {}
+
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
-        """List - a model defined in OpenAPI
+    def _from_openapi_data(cls, kind, page, size, total, *args, **kwargs):  # noqa: E501
+        """ProcessingErrorListResponse - a model defined in OpenAPI
 
-        Keyword Args:
+        Args:
             kind (str):
             page (int):
             size (int):
             total (int):
+
+        Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
                                 drill down to the model in received_data
                                 when deserializing a response
@@ -149,19 +151,19 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            items ([{str: (bool, date, datetime, dict, float, int, list, str, none_type)}]): [optional]  # noqa: E501
+            items ([ProcessingErrorResponse]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
-        _spec_property_naming = kwargs.pop('_spec_property_naming', False)
+        _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
 
         self = super(OpenApiModel, cls).__new__(cls)
 
         if args:
@@ -181,60 +183,48 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        constant_args = {
-            '_check_type': _check_type,
-            '_path_to_item': _path_to_item,
-            '_spec_property_naming': _spec_property_naming,
-            '_configuration': _configuration,
-            '_visited_composed_classes': self._visited_composed_classes,
-        }
-        composed_info = validate_get_composed_info(
-            constant_args, kwargs, self)
-        self._composed_instances = composed_info[0]
-        self._var_name_to_model_instances = composed_info[1]
-        self._additional_properties_model_instances = composed_info[2]
-        discarded_args = composed_info[3]
-
+        self.kind = kind
+        self.page = page
+        self.size = size
+        self.total = total
         for var_name, var_value in kwargs.items():
-            if var_name in discarded_args and \
+            if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
-                        self._additional_properties_model_instances:
+                        self.additional_properties_type is None:
                 # discard variable.
                 continue
             setattr(self, var_name, var_value)
-
         return self
 
     required_properties = set([
         '_data_store',
         '_check_type',
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
-        '_composed_instances',
-        '_var_name_to_model_instances',
-        '_additional_properties_model_instances',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, *args, **kwargs):  # noqa: E501
-        """List - a model defined in OpenAPI
+    def __init__(self, kind, page, size, total, *args, **kwargs):  # noqa: E501
+        """ProcessingErrorListResponse - a model defined in OpenAPI
 
-        Keyword Args:
+        Args:
             kind (str):
             page (int):
             size (int):
             total (int):
+
+        Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
                                 drill down to the model in received_data
                                 when deserializing a response
@@ -257,15 +247,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            items ([{str: (bool, date, datetime, dict, float, int, list, str, none_type)}]): [optional]  # noqa: E501
+            items ([ProcessingErrorResponse]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -287,53 +277,22 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        constant_args = {
-            '_check_type': _check_type,
-            '_path_to_item': _path_to_item,
-            '_spec_property_naming': _spec_property_naming,
-            '_configuration': _configuration,
-            '_visited_composed_classes': self._visited_composed_classes,
-        }
-        composed_info = validate_get_composed_info(
-            constant_args, kwargs, self)
-        self._composed_instances = composed_info[0]
-        self._var_name_to_model_instances = composed_info[1]
-        self._additional_properties_model_instances = composed_info[2]
-        discarded_args = composed_info[3]
-
+        self.kind = kind
+        self.page = page
+        self.size = size
+        self.total = total
         for var_name, var_value in kwargs.items():
-            if var_name in discarded_args and \
+            if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
-                        self._additional_properties_model_instances:
+                        self.additional_properties_type is None:
                 # discard variable.
                 continue
             setattr(self, var_name, var_value)
             if var_name in self.read_only_vars:
                 raise ApiAttributeError(f"`{var_name}` is a read-only attribute. Use `from_openapi_data` to instantiate "
                                      f"class with read only attributes.")
-
-    @cached_property
-    def _composed_schemas():
-        # we need this here to make our import statements work
-        # we must store _composed_schemas in here so the code is only run
-        # when we invoke this method. If we kept this at the class
-        # level we would get an error because the class level
-        # code would be run when this module is imported, and these composed
-        # classes don't exist yet because their module has not finished
-        # loading
-        lazy_import()
-        return {
-          'anyOf': [
-          ],
-          'allOf': [
-              ListAllOf,
-              ListResponse,
-          ],
-          'oneOf': [
-          ],
-        }
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/list_all_of.py` & `rhoas_sdks-1.0.3/sdks/kafka_mgmt_sdk/rhoas_kafka_mgmt_sdk/model/version_metadata_all_of.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,41 +1,45 @@
 """
-    Red Hat Openshift SmartEvents Fleet Manager V2
+    Kafka Management API
 
-    The API exposed by the fleet manager of the SmartEvents service.  # noqa: E501
+    Kafka Management API is a REST API to manage Kafka instances  # noqa: E501
 
-    The version of the OpenAPI document: 0.0.1
-    Contact: openbridge-dev@redhat.com
+    The version of the OpenAPI document: 1.16.0
+    Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
 
-from rhoas_smart_events_mgmt_sdk.model_utils import (  # noqa: F401
+from rhoas_kafka_mgmt_sdk.model_utils import (  # noqa: F401
     ApiTypeError,
     ModelComposed,
     ModelNormal,
     ModelSimple,
     cached_property,
     change_keys_js_to_python,
     convert_js_args_to_python_args,
     date,
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
-from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
+from rhoas_kafka_mgmt_sdk.exceptions import ApiAttributeError
 
 
+def lazy_import():
+    from rhoas_kafka_mgmt_sdk.model.object_reference import ObjectReference
+    globals()['ObjectReference'] = ObjectReference
 
-class ListAllOf(ModelNormal):
+
+class VersionMetadataAllOf(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -63,59 +67,54 @@
 
     @cached_property
     def additional_properties_type():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
         """
+        lazy_import()
         return (bool, date, datetime, dict, float, int, list, str, none_type,)  # noqa: E501
 
     _nullable = False
 
     @cached_property
     def openapi_types():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
+        lazy_import()
         return {
-            'page': (int,),  # noqa: E501
-            'size': (int,),  # noqa: E501
-            'total': (int,),  # noqa: E501
+            'server_version': (str,),  # noqa: E501
+            'collections': ([ObjectReference],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'page': 'page',  # noqa: E501
-        'size': 'size',  # noqa: E501
-        'total': 'total',  # noqa: E501
+        'server_version': 'server_version',  # noqa: E501
+        'collections': 'collections',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, page, size, total, *args, **kwargs):  # noqa: E501
-        """ListAllOf - a model defined in OpenAPI
-
-        Args:
-            page (int):
-            size (int):
-            total (int):
+    def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
+        """VersionMetadataAllOf - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -140,14 +139,16 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
+            server_version (str): [optional]  # noqa: E501
+            collections ([ObjectReference]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -171,17 +172,14 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.page = page
-        self.size = size
-        self.total = total
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -194,21 +192,16 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, page, size, total, *args, **kwargs):  # noqa: E501
-        """ListAllOf - a model defined in OpenAPI
-
-        Args:
-            page (int):
-            size (int):
-            total (int):
+    def __init__(self, *args, **kwargs):  # noqa: E501
+        """VersionMetadataAllOf - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -233,14 +226,16 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
+            server_version (str): [optional]  # noqa: E501
+            collections ([ObjectReference]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -262,17 +257,14 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.page = page
-        self.size = size
-        self.total = total
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/list_response.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processing_error_response.py`

 * *Files 9% similar despite different names*

```diff
@@ -27,15 +27,15 @@
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
 
 
 
-class ListResponse(ModelNormal):
+class ProcessingErrorResponse(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -78,40 +78,39 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
-            'kind': (str,),  # noqa: E501
-            'items': ([{str: (bool, date, datetime, dict, float, int, list, str, none_type)}],),  # noqa: E501
+            'recorded_at': (datetime,),  # noqa: E501
+            'headers': ({str: (str,)},),  # noqa: E501
+            'payload': ({str: (bool, date, datetime, dict, float, int, list, str, none_type)},),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'kind': 'kind',  # noqa: E501
-        'items': 'items',  # noqa: E501
+        'recorded_at': 'recorded_at',  # noqa: E501
+        'headers': 'headers',  # noqa: E501
+        'payload': 'payload',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, kind, *args, **kwargs):  # noqa: E501
-        """ListResponse - a model defined in OpenAPI
-
-        Args:
-            kind (str):
+    def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
+        """ProcessingErrorResponse - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -136,15 +135,17 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            items ([{str: (bool, date, datetime, dict, float, int, list, str, none_type)}]): [optional]  # noqa: E501
+            recorded_at (datetime): [optional]  # noqa: E501
+            headers ({str: (str,)}): [optional]  # noqa: E501
+            payload ({str: (bool, date, datetime, dict, float, int, list, str, none_type)}): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -168,15 +169,14 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.kind = kind
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -189,19 +189,16 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, kind, *args, **kwargs):  # noqa: E501
-        """ListResponse - a model defined in OpenAPI
-
-        Args:
-            kind (str):
+    def __init__(self, *args, **kwargs):  # noqa: E501
+        """ProcessingErrorResponse - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -226,15 +223,17 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            items ([{str: (bool, date, datetime, dict, float, int, list, str, none_type)}]): [optional]  # noqa: E501
+            recorded_at (datetime): [optional]  # noqa: E501
+            headers ({str: (str,)}): [optional]  # noqa: E501
+            payload ({str: (bool, date, datetime, dict, float, int, list, str, none_type)}): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -256,15 +255,14 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.kind = kind
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/managed_resource_status.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/managed_resource_status.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/object_reference.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/object_reference.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processing_error_list_response.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processor_list_response.py`

 * *Files 2% similar despite different names*

```diff
@@ -27,19 +27,19 @@
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
 
 
 def lazy_import():
-    from rhoas_smart_events_mgmt_sdk.model.processing_error_response import ProcessingErrorResponse
-    globals()['ProcessingErrorResponse'] = ProcessingErrorResponse
+    from rhoas_smart_events_mgmt_sdk.model.processor_response import ProcessorResponse
+    globals()['ProcessorResponse'] = ProcessorResponse
 
 
-class ProcessingErrorListResponse(ModelNormal):
+class ProcessorListResponse(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -88,15 +88,15 @@
         """
         lazy_import()
         return {
             'kind': (str,),  # noqa: E501
             'page': (int,),  # noqa: E501
             'size': (int,),  # noqa: E501
             'total': (int,),  # noqa: E501
-            'items': ([ProcessingErrorResponse],),  # noqa: E501
+            'items': ([ProcessorResponse],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
@@ -112,15 +112,15 @@
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
     def _from_openapi_data(cls, kind, page, size, total, *args, **kwargs):  # noqa: E501
-        """ProcessingErrorListResponse - a model defined in OpenAPI
+        """ProcessorListResponse - a model defined in OpenAPI
 
         Args:
             kind (str):
             page (int):
             size (int):
             total (int):
 
@@ -151,15 +151,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            items ([ProcessingErrorResponse]): [optional]  # noqa: E501
+            items ([ProcessorResponse]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -208,15 +208,15 @@
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, kind, page, size, total, *args, **kwargs):  # noqa: E501
-        """ProcessingErrorListResponse - a model defined in OpenAPI
+        """ProcessorListResponse - a model defined in OpenAPI
 
         Args:
             kind (str):
             page (int):
             size (int):
             total (int):
 
@@ -247,15 +247,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            items ([ProcessingErrorResponse]): [optional]  # noqa: E501
+            items ([ProcessorResponse]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processing_error_response.py` & `rhoas_sdks-1.0.3/sdks/connector_mgmt_sdk/rhoas_connector_mgmt_sdk/model/list.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,41 +1,41 @@
 """
-    Red Hat Openshift SmartEvents Fleet Manager V2
+    Connector Management API
 
-    The API exposed by the fleet manager of the SmartEvents service.  # noqa: E501
+    Connector Management API is a REST API to manage connectors.  # noqa: E501
 
-    The version of the OpenAPI document: 0.0.1
-    Contact: openbridge-dev@redhat.com
+    The version of the OpenAPI document: 0.1.0
+    Contact: rhosak-support@redhat.com
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
 
-from rhoas_smart_events_mgmt_sdk.model_utils import (  # noqa: F401
+from rhoas_connector_mgmt_sdk.model_utils import (  # noqa: F401
     ApiTypeError,
     ModelComposed,
     ModelNormal,
     ModelSimple,
     cached_property,
     change_keys_js_to_python,
     convert_js_args_to_python_args,
     date,
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
-from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
+from rhoas_connector_mgmt_sdk.exceptions import ApiAttributeError
 
 
 
-class ProcessingErrorResponse(ModelNormal):
+class List(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -78,39 +78,47 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
-            'recorded_at': (datetime,),  # noqa: E501
-            'headers': ({str: (str,)},),  # noqa: E501
-            'payload': ({str: (bool, date, datetime, dict, float, int, list, str, none_type)},),  # noqa: E501
+            'kind': (str,),  # noqa: E501
+            'page': (int,),  # noqa: E501
+            'size': (int,),  # noqa: E501
+            'total': (int,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'recorded_at': 'recorded_at',  # noqa: E501
-        'headers': 'headers',  # noqa: E501
-        'payload': 'payload',  # noqa: E501
+        'kind': 'kind',  # noqa: E501
+        'page': 'page',  # noqa: E501
+        'size': 'size',  # noqa: E501
+        'total': 'total',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, *args, **kwargs):  # noqa: E501
-        """ProcessingErrorResponse - a model defined in OpenAPI
+    def _from_openapi_data(cls, kind, page, size, total, *args, **kwargs):  # noqa: E501
+        """List - a model defined in OpenAPI
+
+        Args:
+            kind (str):
+            page (int):
+            size (int):
+            total (int):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -135,17 +143,14 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            recorded_at (datetime): [optional]  # noqa: E501
-            headers ({str: (str,)}): [optional]  # noqa: E501
-            payload ({str: (bool, date, datetime, dict, float, int, list, str, none_type)}): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -169,14 +174,18 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.kind = kind
+        self.page = page
+        self.size = size
+        self.total = total
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -189,16 +198,22 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, *args, **kwargs):  # noqa: E501
-        """ProcessingErrorResponse - a model defined in OpenAPI
+    def __init__(self, kind, page, size, total, *args, **kwargs):  # noqa: E501
+        """List - a model defined in OpenAPI
+
+        Args:
+            kind (str):
+            page (int):
+            size (int):
+            total (int):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -223,17 +238,14 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            recorded_at (datetime): [optional]  # noqa: E501
-            headers ({str: (str,)}): [optional]  # noqa: E501
-            payload ({str: (bool, date, datetime, dict, float, int, list, str, none_type)}): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -255,14 +267,18 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
+        self.kind = kind
+        self.page = page
+        self.size = size
+        self.total = total
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processor_list_response.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/source_connector_list_response.py`

 * *Files 5% similar despite different names*

```diff
@@ -27,19 +27,19 @@
     validate_get_composed_info,
     OpenApiModel
 )
 from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
 
 
 def lazy_import():
-    from rhoas_smart_events_mgmt_sdk.model.processor_response import ProcessorResponse
-    globals()['ProcessorResponse'] = ProcessorResponse
+    from rhoas_smart_events_mgmt_sdk.model.source_connector_response import SourceConnectorResponse
+    globals()['SourceConnectorResponse'] = SourceConnectorResponse
 
 
-class ProcessorListResponse(ModelNormal):
+class SourceConnectorListResponse(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -88,15 +88,15 @@
         """
         lazy_import()
         return {
             'kind': (str,),  # noqa: E501
             'page': (int,),  # noqa: E501
             'size': (int,),  # noqa: E501
             'total': (int,),  # noqa: E501
-            'items': ([ProcessorResponse],),  # noqa: E501
+            'items': ([SourceConnectorResponse],),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
@@ -112,15 +112,15 @@
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
     def _from_openapi_data(cls, kind, page, size, total, *args, **kwargs):  # noqa: E501
-        """ProcessorListResponse - a model defined in OpenAPI
+        """SourceConnectorListResponse - a model defined in OpenAPI
 
         Args:
             kind (str):
             page (int):
             size (int):
             total (int):
 
@@ -151,15 +151,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            items ([ProcessorResponse]): [optional]  # noqa: E501
+            items ([SourceConnectorResponse]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -208,15 +208,15 @@
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, kind, page, size, total, *args, **kwargs):  # noqa: E501
-        """ProcessorListResponse - a model defined in OpenAPI
+        """SourceConnectorListResponse - a model defined in OpenAPI
 
         Args:
             kind (str):
             page (int):
             size (int):
             total (int):
 
@@ -247,15 +247,15 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            items ([ProcessorResponse]): [optional]  # noqa: E501
+            items ([SourceConnectorResponse]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processor_request.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/comment.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,41 +1,41 @@
 """
-    Red Hat Openshift SmartEvents Fleet Manager V2
+    Apicurio Registry API [v2]
 
-    The API exposed by the fleet manager of the SmartEvents service.  # noqa: E501
+    Apicurio Registry is a datastore for standard event schemas and API designs. Apicurio Registry enables developers to manage and share the structure of their data using a REST interface. For example, client applications can dynamically push or pull the latest updates to or from the registry without needing to redeploy. Apicurio Registry also enables developers to create rules that govern how registry content can evolve over time. For example, this includes rules for content validation and version compatibility.  The Apicurio Registry REST API enables client applications to manage the artifacts in the registry. This API provides create, read, update, and delete operations for schema and API artifacts, rules, versions, and metadata.   The supported artifact types include: - Apache Avro schema - AsyncAPI specification - Google protocol buffers - GraphQL schema - JSON Schema - Kafka Connect schema - OpenAPI specification - Web Services Description Language - XML Schema Definition   **Important**: The Apicurio Registry REST API is available from `https://MY-REGISTRY-URL/apis/registry/v2` by default. Therefore you must prefix all API operation paths with `../apis/registry/v2` in this case. For example: `../apis/registry/v2/ids/globalIds/{globalId}`.   # noqa: E501
 
-    The version of the OpenAPI document: 0.0.1
-    Contact: openbridge-dev@redhat.com
+    The version of the OpenAPI document: 2.4.x
+    Contact: apicurio@lists.jboss.org
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
 
-from rhoas_smart_events_mgmt_sdk.model_utils import (  # noqa: F401
+from rhoas_registry_instance_sdk.model_utils import (  # noqa: F401
     ApiTypeError,
     ModelComposed,
     ModelNormal,
     ModelSimple,
     cached_property,
     change_keys_js_to_python,
     convert_js_args_to_python_args,
     date,
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
-from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
+from rhoas_registry_instance_sdk.exceptions import ApiAttributeError
 
 
 
-class ProcessorRequest(ModelNormal):
+class Comment(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -55,16 +55,16 @@
           as additional properties values.
     """
 
     allowed_values = {
     }
 
     validations = {
-        ('name',): {
-            'min_length': 1,
+        ('value',): {
+            'max_length': 1024,
         },
     }
 
     @cached_property
     def additional_properties_type():
         """
         This must be a method because a model may have properties that are
@@ -81,41 +81,47 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
-            'name': (str,),  # noqa: E501
-            'flows': ({str: (bool, date, datetime, dict, float, int, list, str, none_type)},),  # noqa: E501
+            'value': (str,),  # noqa: E501
+            'created_on': (datetime,),  # noqa: E501
+            'created_by': (str,),  # noqa: E501
+            'comment_id': (str,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'name': 'name',  # noqa: E501
-        'flows': 'flows',  # noqa: E501
+        'value': 'value',  # noqa: E501
+        'created_on': 'createdOn',  # noqa: E501
+        'created_by': 'createdBy',  # noqa: E501
+        'comment_id': 'commentId',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, name, flows, *args, **kwargs):  # noqa: E501
-        """ProcessorRequest - a model defined in OpenAPI
+    def _from_openapi_data(cls, value, created_on, created_by, comment_id, *args, **kwargs):  # noqa: E501
+        """Comment - a model defined in OpenAPI
 
         Args:
-            name (str): The name of the processor
-            flows ({str: (bool, date, datetime, dict, float, int, list, str, none_type)}): The Camel YAML DSL code, formatted as JSON, that defines the flows in the processor
+            value (str):
+            created_on (datetime):
+            created_by (str): 
+            comment_id (str): 
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -171,16 +177,18 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.name = name
-        self.flows = flows
+        self.value = value
+        self.created_on = created_on
+        self.created_by = created_by
+        self.comment_id = comment_id
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -193,20 +201,22 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, name, flows, *args, **kwargs):  # noqa: E501
-        """ProcessorRequest - a model defined in OpenAPI
+    def __init__(self, value, created_on, created_by, comment_id, *args, **kwargs):  # noqa: E501
+        """Comment - a model defined in OpenAPI
 
         Args:
-            name (str): The name of the processor
-            flows ({str: (bool, date, datetime, dict, float, int, list, str, none_type)}): The Camel YAML DSL code, formatted as JSON, that defines the flows in the processor
+            value (str):
+            created_on (datetime):
+            created_by (str): 
+            comment_id (str): 
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -260,16 +270,18 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.name = name
-        self.flows = flows
+        self.value = value
+        self.created_on = created_on
+        self.created_by = created_by
+        self.comment_id = comment_id
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processor_response.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/processor_response.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/sink_connector_list_response.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/new_comment.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,45 +1,41 @@
 """
-    Red Hat Openshift SmartEvents Fleet Manager V2
+    Apicurio Registry API [v2]
 
-    The API exposed by the fleet manager of the SmartEvents service.  # noqa: E501
+    Apicurio Registry is a datastore for standard event schemas and API designs. Apicurio Registry enables developers to manage and share the structure of their data using a REST interface. For example, client applications can dynamically push or pull the latest updates to or from the registry without needing to redeploy. Apicurio Registry also enables developers to create rules that govern how registry content can evolve over time. For example, this includes rules for content validation and version compatibility.  The Apicurio Registry REST API enables client applications to manage the artifacts in the registry. This API provides create, read, update, and delete operations for schema and API artifacts, rules, versions, and metadata.   The supported artifact types include: - Apache Avro schema - AsyncAPI specification - Google protocol buffers - GraphQL schema - JSON Schema - Kafka Connect schema - OpenAPI specification - Web Services Description Language - XML Schema Definition   **Important**: The Apicurio Registry REST API is available from `https://MY-REGISTRY-URL/apis/registry/v2` by default. Therefore you must prefix all API operation paths with `../apis/registry/v2` in this case. For example: `../apis/registry/v2/ids/globalIds/{globalId}`.   # noqa: E501
 
-    The version of the OpenAPI document: 0.0.1
-    Contact: openbridge-dev@redhat.com
+    The version of the OpenAPI document: 2.4.x
+    Contact: apicurio@lists.jboss.org
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
 
-from rhoas_smart_events_mgmt_sdk.model_utils import (  # noqa: F401
+from rhoas_registry_instance_sdk.model_utils import (  # noqa: F401
     ApiTypeError,
     ModelComposed,
     ModelNormal,
     ModelSimple,
     cached_property,
     change_keys_js_to_python,
     convert_js_args_to_python_args,
     date,
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
-from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
+from rhoas_registry_instance_sdk.exceptions import ApiAttributeError
 
 
-def lazy_import():
-    from rhoas_smart_events_mgmt_sdk.model.sink_connector_response import SinkConnectorResponse
-    globals()['SinkConnectorResponse'] = SinkConnectorResponse
 
-
-class SinkConnectorListResponse(ModelNormal):
+class NewComment(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -67,66 +63,53 @@
 
     @cached_property
     def additional_properties_type():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
         """
-        lazy_import()
         return (bool, date, datetime, dict, float, int, list, str, none_type,)  # noqa: E501
 
     _nullable = False
 
     @cached_property
     def openapi_types():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
-        lazy_import()
         return {
-            'kind': (str,),  # noqa: E501
-            'page': (int,),  # noqa: E501
-            'size': (int,),  # noqa: E501
-            'total': (int,),  # noqa: E501
-            'items': ([SinkConnectorResponse],),  # noqa: E501
+            'value': (str,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'kind': 'kind',  # noqa: E501
-        'page': 'page',  # noqa: E501
-        'size': 'size',  # noqa: E501
-        'total': 'total',  # noqa: E501
-        'items': 'items',  # noqa: E501
+        'value': 'value',  # noqa: E501
     }
 
     read_only_vars = {
     }
 
     _composed_schemas = {}
 
     @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, kind, page, size, total, *args, **kwargs):  # noqa: E501
-        """SinkConnectorListResponse - a model defined in OpenAPI
+    def _from_openapi_data(cls, value, *args, **kwargs):  # noqa: E501
+        """NewComment - a model defined in OpenAPI
 
         Args:
-            kind (str):
-            page (int):
-            size (int):
-            total (int):
+            value (str):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -151,15 +134,14 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            items ([SinkConnectorResponse]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', True)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -183,18 +165,15 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.kind = kind
-        self.page = page
-        self.size = size
-        self.total = total
+        self.value = value
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
@@ -207,22 +186,19 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, kind, page, size, total, *args, **kwargs):  # noqa: E501
-        """SinkConnectorListResponse - a model defined in OpenAPI
+    def __init__(self, value, *args, **kwargs):  # noqa: E501
+        """NewComment - a model defined in OpenAPI
 
         Args:
-            kind (str):
-            page (int):
-            size (int):
-            total (int):
+            value (str):
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -247,15 +223,14 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            items ([SinkConnectorResponse]): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -277,18 +252,15 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.kind = kind
-        self.page = page
-        self.size = size
-        self.total = total
+        self.value = value
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/sink_connector_response.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/sink_connector_response.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/source_connector_list_response.py` & `rhoas_sdks-1.0.3/sdks/registry_instance_sdk/rhoas_registry_instance_sdk/model/reference_type.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,134 +1,119 @@
 """
-    Red Hat Openshift SmartEvents Fleet Manager V2
+    Apicurio Registry API [v2]
 
-    The API exposed by the fleet manager of the SmartEvents service.  # noqa: E501
+    Apicurio Registry is a datastore for standard event schemas and API designs. Apicurio Registry enables developers to manage and share the structure of their data using a REST interface. For example, client applications can dynamically push or pull the latest updates to or from the registry without needing to redeploy. Apicurio Registry also enables developers to create rules that govern how registry content can evolve over time. For example, this includes rules for content validation and version compatibility.  The Apicurio Registry REST API enables client applications to manage the artifacts in the registry. This API provides create, read, update, and delete operations for schema and API artifacts, rules, versions, and metadata.   The supported artifact types include: - Apache Avro schema - AsyncAPI specification - Google protocol buffers - GraphQL schema - JSON Schema - Kafka Connect schema - OpenAPI specification - Web Services Description Language - XML Schema Definition   **Important**: The Apicurio Registry REST API is available from `https://MY-REGISTRY-URL/apis/registry/v2` by default. Therefore you must prefix all API operation paths with `../apis/registry/v2` in this case. For example: `../apis/registry/v2/ids/globalIds/{globalId}`.   # noqa: E501
 
-    The version of the OpenAPI document: 0.0.1
-    Contact: openbridge-dev@redhat.com
+    The version of the OpenAPI document: 2.4.x
+    Contact: apicurio@lists.jboss.org
     Generated by: https://openapi-generator.tech
 """
 
 
 import re  # noqa: F401
 import sys  # noqa: F401
 
-from rhoas_smart_events_mgmt_sdk.model_utils import (  # noqa: F401
+from rhoas_registry_instance_sdk.model_utils import (  # noqa: F401
     ApiTypeError,
     ModelComposed,
     ModelNormal,
     ModelSimple,
     cached_property,
     change_keys_js_to_python,
     convert_js_args_to_python_args,
     date,
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
     OpenApiModel
 )
-from rhoas_smart_events_mgmt_sdk.exceptions import ApiAttributeError
+from rhoas_registry_instance_sdk.exceptions import ApiAttributeError
 
 
-def lazy_import():
-    from rhoas_smart_events_mgmt_sdk.model.source_connector_response import SourceConnectorResponse
-    globals()['SourceConnectorResponse'] = SourceConnectorResponse
 
-
-class SourceConnectorListResponse(ModelNormal):
+class ReferenceType(ModelSimple):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
           and the for var_name this is (var_name,). The value is a dict
           with a capitalized key describing the allowed value and an allowed
           value. These dicts store the allowed enum values.
-      attribute_map (dict): The key is attribute name
-          and the value is json key in definition.
-      discriminator_value_class_map (dict): A dict to go from the discriminator
-          variable value to the discriminator class name.
       validations (dict): The key is the tuple path to the attribute
           and the for var_name this is (var_name,). The value is a dict
           that stores validations for max_length, min_length, max_items,
           min_items, exclusive_maximum, inclusive_maximum, exclusive_minimum,
           inclusive_minimum, and regex.
       additional_properties_type (tuple): A tuple of classes accepted
           as additional properties values.
     """
 
     allowed_values = {
+        ('value',): {
+            'OUTBOUND': "OUTBOUND",
+            'INBOUND': "INBOUND",
+        },
     }
 
     validations = {
     }
 
-    @cached_property
-    def additional_properties_type():
-        """
-        This must be a method because a model may have properties that are
-        of type self, this must run after the class is loaded
-        """
-        lazy_import()
-        return (bool, date, datetime, dict, float, int, list, str, none_type,)  # noqa: E501
+    additional_properties_type = None
 
     _nullable = False
 
     @cached_property
     def openapi_types():
         """
         This must be a method because a model may have properties that are
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
-        lazy_import()
         return {
-            'kind': (str,),  # noqa: E501
-            'page': (int,),  # noqa: E501
-            'size': (int,),  # noqa: E501
-            'total': (int,),  # noqa: E501
-            'items': ([SourceConnectorResponse],),  # noqa: E501
+            'value': (str,),
         }
 
     @cached_property
     def discriminator():
         return None
 
 
-    attribute_map = {
-        'kind': 'kind',  # noqa: E501
-        'page': 'page',  # noqa: E501
-        'size': 'size',  # noqa: E501
-        'total': 'total',  # noqa: E501
-        'items': 'items',  # noqa: E501
-    }
+    attribute_map = {}
 
-    read_only_vars = {
-    }
+    read_only_vars = set()
 
-    _composed_schemas = {}
+    _composed_schemas = None
+
+    required_properties = set([
+        '_data_store',
+        '_check_type',
+        '_spec_property_naming',
+        '_path_to_item',
+        '_configuration',
+        '_visited_composed_classes',
+    ])
 
-    @classmethod
     @convert_js_args_to_python_args
-    def _from_openapi_data(cls, kind, page, size, total, *args, **kwargs):  # noqa: E501
-        """SourceConnectorListResponse - a model defined in OpenAPI
+    def __init__(self, *args, **kwargs):
+        """ReferenceType - a model defined in OpenAPI
+
+        Note that value can be passed either in args or in kwargs, but not in both.
 
         Args:
-            kind (str):
-            page (int):
-            size (int):
-            total (int):
+            args[0] (str): ., must be one of ["OUTBOUND", "INBOUND", ]  # noqa: E501
 
         Keyword Args:
+            value (str): ., must be one of ["OUTBOUND", "INBOUND", ]  # noqa: E501
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
                                 drill down to the model in received_data
                                 when deserializing a response
@@ -151,25 +136,35 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            items ([SourceConnectorResponse]): [optional]  # noqa: E501
         """
+        # required up here when default value is not given
+        _path_to_item = kwargs.pop('_path_to_item', ())
+
+        if 'value' in kwargs:
+            value = kwargs.pop('value')
+        elif args:
+            args = list(args)
+            value = args.pop(0)
+        else:
+            raise ApiTypeError(
+                "value is required, but not passed in args or kwargs and doesn't have default",
+                path_to_item=_path_to_item,
+                valid_classes=(self.__class__,),
+            )
 
         _check_type = kwargs.pop('_check_type', True)
-        _spec_property_naming = kwargs.pop('_spec_property_naming', True)
-        _path_to_item = kwargs.pop('_path_to_item', ())
+        _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
 
-        self = super(OpenApiModel, cls).__new__(cls)
-
         if args:
             for arg in args:
                 if isinstance(arg, dict):
                     kwargs.update(arg)
                 else:
                     raise ApiTypeError(
                         "Invalid positional arguments=%s passed to %s. Remove those invalid positional arguments." % (
@@ -182,49 +177,37 @@
 
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
+        self.value = value
+        if kwargs:
+            raise ApiTypeError(
+                "Invalid named arguments=%s passed to %s. Remove those invalid named arguments." % (
+                    kwargs,
+                    self.__class__.__name__,
+                ),
+                path_to_item=_path_to_item,
+                valid_classes=(self.__class__,),
+            )
 
-        self.kind = kind
-        self.page = page
-        self.size = size
-        self.total = total
-        for var_name, var_value in kwargs.items():
-            if var_name not in self.attribute_map and \
-                        self._configuration is not None and \
-                        self._configuration.discard_unknown_keys and \
-                        self.additional_properties_type is None:
-                # discard variable.
-                continue
-            setattr(self, var_name, var_value)
-        return self
-
-    required_properties = set([
-        '_data_store',
-        '_check_type',
-        '_spec_property_naming',
-        '_path_to_item',
-        '_configuration',
-        '_visited_composed_classes',
-    ])
-
+    @classmethod
     @convert_js_args_to_python_args
-    def __init__(self, kind, page, size, total, *args, **kwargs):  # noqa: E501
-        """SourceConnectorListResponse - a model defined in OpenAPI
+    def _from_openapi_data(cls, *args, **kwargs):
+        """ReferenceType - a model defined in OpenAPI
+
+        Note that value can be passed either in args or in kwargs, but not in both.
 
         Args:
-            kind (str):
-            page (int):
-            size (int):
-            total (int):
+            args[0] (str): ., must be one of ["OUTBOUND", "INBOUND", ]  # noqa: E501
 
         Keyword Args:
+            value (str): ., must be one of ["OUTBOUND", "INBOUND", ]  # noqa: E501
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
                                 drill down to the model in received_data
                                 when deserializing a response
@@ -247,20 +230,34 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            items ([SourceConnectorResponse]): [optional]  # noqa: E501
         """
+        # required up here when default value is not given
+        _path_to_item = kwargs.pop('_path_to_item', ())
+
+        self = super(OpenApiModel, cls).__new__(cls)
+
+        if 'value' in kwargs:
+            value = kwargs.pop('value')
+        elif args:
+            args = list(args)
+            value = args.pop(0)
+        else:
+            raise ApiTypeError(
+                "value is required, but not passed in args or kwargs and doesn't have default",
+                path_to_item=_path_to_item,
+                valid_classes=(self.__class__,),
+            )
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
-        _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
 
         if args:
             for arg in args:
                 if isinstance(arg, dict):
                     kwargs.update(arg)
@@ -276,23 +273,19 @@
 
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
+        self.value = value
+        if kwargs:
+            raise ApiTypeError(
+                "Invalid named arguments=%s passed to %s. Remove those invalid named arguments." % (
+                    kwargs,
+                    self.__class__.__name__,
+                ),
+                path_to_item=_path_to_item,
+                valid_classes=(self.__class__,),
+            )
 
-        self.kind = kind
-        self.page = page
-        self.size = size
-        self.total = total
-        for var_name, var_value in kwargs.items():
-            if var_name not in self.attribute_map and \
-                        self._configuration is not None and \
-                        self._configuration.discard_unknown_keys and \
-                        self.additional_properties_type is None:
-                # discard variable.
-                continue
-            setattr(self, var_name, var_value)
-            if var_name in self.read_only_vars:
-                raise ApiAttributeError(f"`{var_name}` is a read-only attribute. Use `from_openapi_data` to instantiate "
-                                     f"class with read only attributes.")
+        return self
```

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/source_connector_response.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model/source_connector_response.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model_utils.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/model_utils.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/models/__init__.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/models/__init__.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/rest.py` & `rhoas_sdks-1.0.3/sdks/smart_events_mgmt_sdk/rhoas_smart_events_mgmt_sdk/rest.py`

 * *Files identical despite different names*

### Comparing `rhoas_sdks-1.0.2b2/PKG-INFO` & `rhoas_sdks-1.0.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: rhoas-sdks
-Version: 1.0.2b2
+Version: 1.0.3
 Summary: A package which includes RHOAS SDKs
 License: Apache License
 Author: dimakis
 Author-email: dsaridak@redhat.com
 Requires-Python: >=3.9,<4.0
 Classifier: License :: Other/Proprietary License
 Classifier: Programming Language :: Python :: 3
@@ -18,15 +18,15 @@
 
 # RHOAS Core SDKs
 
 > If you are moving a project from the old RHOAS SDKs to core read this [moving](./MOVING.md) doc to get started.
 
 | Supported Langauge  | SDK |
 | ----------- | ----------- |
-| JavaScript/TypeScript  | [app-services-sdk-js](/app-services-sdk-js/) |
+| JavaScript  | [app-services-sdk-ts](/app-services-sdk-ts/) |
 | Python   | [app-services-sdk-python](/app-services-sdk-python/)    |
 | Java   | [app-services-sdk-java](/app-services-sdk-java/)        |
 |  Go   | [app-services-sdk-go](/app-services-sdk-go/)        |
 
 ## Structure
 
 RHOAS SDK's are delivered as set of individual packages.
@@ -36,17 +36,17 @@
 - **Instance SDKs** -  support direct interaction with services
 
 ## Purpose of this repository
 
 Repository contains source code for openapi based generator along with automation scripts that generate all
 underlying RHOAS SDKS. 
 
-# RHOAS SDK for Typescript and JavaScript
+# RHOAS SDK for Typescript
 
-Typescript and JavaScript packages and API clients for RHOAS services
+Typescript packages and API clients for RHOAS services
 
 ## Prequisites
 
 - [NodeJS 14.x lts](https://nodejs.org/en/about/releases/) or above
 
 ## Management SDK's
```


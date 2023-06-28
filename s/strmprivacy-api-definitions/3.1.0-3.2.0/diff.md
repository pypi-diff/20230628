# Comparing `tmp/strmprivacy-api-definitions-3.1.0.tar.gz` & `tmp/strmprivacy-api-definitions-3.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "strmprivacy-api-definitions-3.1.0.tar", last modified: Wed Jun 28 11:11:31 2023, max compression
+gzip compressed data, was "strmprivacy-api-definitions-3.2.0.tar", last modified: Wed Jun 28 12:26:12 2023, max compression
```

## Comparing `strmprivacy-api-definitions-3.1.0.tar` & `strmprivacy-api-definitions-3.2.0.tar`

### file list

```diff
@@ -1,227 +1,227 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.741913 strmprivacy-api-definitions-3.1.0/
--rw-r--r--   0 root         (0) root         (0)      629 2023-06-28 11:11:31.741913 strmprivacy-api-definitions-3.1.0/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 11:11:31.741913 strmprivacy-api-definitions-3.1.0/setup.cfg
--rw-r--r--   0 root         (0) root         (0)     1443 2023-06-28 11:10:54.000000 strmprivacy-api-definitions-3.1.0/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.708910 strmprivacy-api-definitions-3.1.0/strmprivacy/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.708910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.709910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/account/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/account/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.709910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/account/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/account/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)    12198 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/account/v1/account_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)    16789 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/account/v1/account_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.710910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.711910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     2356 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/batch_exporters_agent_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     3269 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/batch_exporters_agent_v1_pb2_grpc.py
--rw-r--r--   0 root         (0) root         (0)     2300 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/batch_jobs_agent_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     3129 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/batch_jobs_agent_v1_pb2_grpc.py
--rw-r--r--   0 root         (0) root         (0)     2369 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/data_connector_agent_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     3261 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/data_connector_agent_v1_pb2_grpc.py
--rw-r--r--   0 root         (0) root         (0)     2161 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/streams_agent_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     3267 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/streams_agent_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.712910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/audit/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/audit/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.712910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/audit/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/audit/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3449 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/audit/v1/audit_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     5030 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/audit/v1/audit_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.712910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_exporters/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_exporters/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.713910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_exporters/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_exporters/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5338 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_exporters/v1/batch_exporters_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     9468 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_exporters/v1/batch_exporters_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.713910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_jobs/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_jobs/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.714910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_jobs/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_jobs/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     7665 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_jobs/v1/batch_jobs_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)    10858 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_jobs/v1/batch_jobs_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.714910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/cli/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/cli/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.715911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/cli/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/cli/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3799 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/cli/v1/cli_pb2.py
--rw-r--r--   0 root         (0) root         (0)     2753 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/cli/v1/cli_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.715911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/comments/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/comments/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.715911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/comments/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/comments/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3987 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/comments/v1/comments_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     6740 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/comments/v1/comments_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.716910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/credentials/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/credentials/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.716910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/credentials/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/credentials/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5049 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/credentials/v1/credentials_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     8979 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/credentials/v1/credentials_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.716910 strmprivacy-api-definitions-3.1.0/strmprivacy/api/customer_entity_versions/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/customer_entity_versions/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.717911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/customer_entity_versions/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/customer_entity_versions/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     7497 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/customer_entity_versions/v1/customer_entity_versions_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)    10288 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/customer_entity_versions/v1/customer_entity_versions_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.717911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_connectors/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_connectors/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.718911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_connectors/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_connectors/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5978 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_connectors/v1/data_connectors_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     9468 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_connectors/v1/data_connectors_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.718911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_contracts/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_contracts/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.719911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_contracts/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_contracts/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)    22863 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_contracts/v1/data_contracts_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)    28488 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_contracts/v1/data_contracts_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.719911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_subjects/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_subjects/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.720911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_subjects/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_subjects/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     9499 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_subjects/v1/data_subjects_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     9865 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_subjects/v1/data_subjects_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.720911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/entities/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/entities/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.721911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/entities/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/entities/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)    81835 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/entities/v1/entities_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)      159 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/entities/v1/entities_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.722911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/entities/v1alpha/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/entities/v1alpha/__init__.py
--rw-r--r--   0 root         (0) root         (0)    12377 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/entities/v1alpha/entities_v1alpha_pb2.py
--rw-r--r--   0 root         (0) root         (0)      159 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/entities/v1alpha/entities_v1alpha_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.722911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/event_contracts/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/event_contracts/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.722911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/event_contracts/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/event_contracts/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)    15658 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/event_contracts/v1/event_contracts_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)    20098 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/event_contracts/v1/event_contracts_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.723911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/handles/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/handles/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.723911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/handles/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/handles/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     2239 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/handles/v1/handles_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     3057 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/handles/v1/handles_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.724911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.725911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     7909 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/v1/entities_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)      159 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/v1/entities_v1_pb2_grpc.py
--rw-r--r--   0 root         (0) root         (0)     6253 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/v1/installations_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     9499 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/v1/installations_v1_pb2_grpc.py
--rw-r--r--   0 root         (0) root         (0)     6958 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/v1/installed_components_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)    10345 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/v1/installed_components_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.725911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_clusters/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_clusters/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.726911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_clusters/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_clusters/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     6199 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_clusters/v1/kafka_clusters_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     9342 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_clusters/v1/kafka_clusters_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.726911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_exporters/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_exporters/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.727912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_exporters/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_exporters/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5362 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_exporters/v1/kafka_exporters_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     9468 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_exporters/v1/kafka_exporters_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.727912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_users/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_users/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.728911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_users/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_users/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5369 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_users/v1/kafka_users_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     8964 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_users/v1/kafka_users_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.728911 strmprivacy-api-definitions-3.1.0/strmprivacy/api/key_streams/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/key_streams/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.729912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/key_streams/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/key_streams/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3713 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/key_streams/v1/key_streams_pb2.py
--rw-r--r--   0 root         (0) root         (0)     4941 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/key_streams/v1/key_streams_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.729912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/monitoring/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/monitoring/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.730912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/monitoring/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/monitoring/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     6738 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/monitoring/v1/monitoring_pb2.py
--rw-r--r--   0 root         (0) root         (0)     7722 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/monitoring/v1/monitoring_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.730912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/notifications/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/notifications/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.730912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/notifications/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/notifications/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)    10605 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/notifications/v1/notifications_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)    13648 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/notifications/v1/notifications_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.731912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/onboarding/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/onboarding/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.731912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/onboarding/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/onboarding/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     2789 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/onboarding/v1/onboarding_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     3161 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/onboarding/v1/onboarding_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.731912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/organizations/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/organizations/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.732912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/organizations/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/organizations/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5842 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/organizations/v1/organizations_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     9075 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/organizations/v1/organizations_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.732912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/paging/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/paging/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.733912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/paging/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/paging/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1340 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/paging/v1/paging_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)      159 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/paging/v1/paging_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.733912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/policies/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/policies/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.734912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/policies/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/policies/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5782 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/policies/v1/policies_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)    10449 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/policies/v1/policies_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.734912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/project_plans/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/project_plans/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.735912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/project_plans/v1alpha/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/project_plans/v1alpha/__init__.py
--rw-r--r--   0 root         (0) root         (0)     4442 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/project_plans/v1alpha/project_plans_v1alpha_pb2.py
--rw-r--r--   0 root         (0) root         (0)     7409 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/project_plans/v1alpha/project_plans_v1alpha_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.735912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/projects/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/projects/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.736912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/projects/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/projects/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     7458 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/projects/v1/projects_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)    14509 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/projects/v1/projects_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.736912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/purpose_mapping/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/purpose_mapping/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.737912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/purpose_mapping/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/purpose_mapping/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     4483 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/purpose_mapping/v1/purpose_mapping_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     7407 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/purpose_mapping/v1/purpose_mapping_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.737912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/schemas/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/schemas/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.738912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/schemas/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/schemas/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)    13192 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/schemas/v1/schemas_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)    17973 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/schemas/v1/schemas_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.738912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/sinks/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/sinks/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.738912 strmprivacy-api-definitions-3.1.0/strmprivacy/api/sinks/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/sinks/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5254 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/sinks/v1/sinks_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     8223 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/sinks/v1/sinks_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.739913 strmprivacy-api-definitions-3.1.0/strmprivacy/api/streams/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/streams/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.739913 strmprivacy-api-definitions-3.1.0/strmprivacy/api/streams/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/streams/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5689 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/streams/v1/streams_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)    10437 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/streams/v1/streams_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.739913 strmprivacy-api-definitions-3.1.0/strmprivacy/api/usage/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/usage/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.739913 strmprivacy-api-definitions-3.1.0/strmprivacy/api/usage/v1/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:11:30.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/usage/v1/__init__.py
--rw-r--r--   0 root         (0) root         (0)     4644 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/usage/v1/usage_v1_pb2.py
--rw-r--r--   0 root         (0) root         (0)     4831 2023-06-28 11:10:08.000000 strmprivacy-api-definitions-3.1.0/strmprivacy/api/usage/v1/usage_v1_pb2_grpc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:11:31.740913 strmprivacy-api-definitions-3.1.0/strmprivacy_api_definitions.egg-info/
--rw-r--r--   0 root         (0) root         (0)      629 2023-06-28 11:11:31.000000 strmprivacy-api-definitions-3.1.0/strmprivacy_api_definitions.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     7436 2023-06-28 11:11:31.000000 strmprivacy-api-definitions-3.1.0/strmprivacy_api_definitions.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 11:11:31.000000 strmprivacy-api-definitions-3.1.0/strmprivacy_api_definitions.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 11:11:31.000000 strmprivacy-api-definitions-3.1.0/strmprivacy_api_definitions.egg-info/not-zip-safe
--rw-r--r--   0 root         (0) root         (0)       15 2023-06-28 11:11:31.000000 strmprivacy-api-definitions-3.1.0/strmprivacy_api_definitions.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       12 2023-06-28 11:11:31.000000 strmprivacy-api-definitions-3.1.0/strmprivacy_api_definitions.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.436246 strmprivacy-api-definitions-3.2.0/
+-rw-r--r--   0 root         (0) root         (0)      629 2023-06-28 12:26:12.435246 strmprivacy-api-definitions-3.2.0/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 12:26:12.436246 strmprivacy-api-definitions-3.2.0/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)     1443 2023-06-28 12:25:34.000000 strmprivacy-api-definitions-3.2.0/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.288233 strmprivacy-api-definitions-3.2.0/strmprivacy/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.288233 strmprivacy-api-definitions-3.2.0/strmprivacy/api/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.289233 strmprivacy-api-definitions-3.2.0/strmprivacy/api/account/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/account/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.289233 strmprivacy-api-definitions-3.2.0/strmprivacy/api/account/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/account/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    12198 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/account/v1/account_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)    16789 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/account/v1/account_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.290233 strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.292233 strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     2356 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/batch_exporters_agent_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     3269 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/batch_exporters_agent_v1_pb2_grpc.py
+-rw-r--r--   0 root         (0) root         (0)     2300 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/batch_jobs_agent_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     3129 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/batch_jobs_agent_v1_pb2_grpc.py
+-rw-r--r--   0 root         (0) root         (0)     2369 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/data_connector_agent_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     3261 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/data_connector_agent_v1_pb2_grpc.py
+-rw-r--r--   0 root         (0) root         (0)     2161 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/streams_agent_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     3267 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/streams_agent_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.293233 strmprivacy-api-definitions-3.2.0/strmprivacy/api/audit/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/audit/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.293233 strmprivacy-api-definitions-3.2.0/strmprivacy/api/audit/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/audit/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3449 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/audit/v1/audit_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     5030 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/audit/v1/audit_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.294233 strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_exporters/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_exporters/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.295234 strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_exporters/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_exporters/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5338 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_exporters/v1/batch_exporters_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     9468 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_exporters/v1/batch_exporters_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.295234 strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_jobs/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_jobs/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.296234 strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_jobs/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_jobs/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     7665 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_jobs/v1/batch_jobs_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)    10858 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_jobs/v1/batch_jobs_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.297234 strmprivacy-api-definitions-3.2.0/strmprivacy/api/cli/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/cli/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.298234 strmprivacy-api-definitions-3.2.0/strmprivacy/api/cli/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/cli/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3799 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/cli/v1/cli_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     2753 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/cli/v1/cli_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.298234 strmprivacy-api-definitions-3.2.0/strmprivacy/api/comments/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/comments/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.299234 strmprivacy-api-definitions-3.2.0/strmprivacy/api/comments/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/comments/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3987 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/comments/v1/comments_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     6740 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/comments/v1/comments_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.299234 strmprivacy-api-definitions-3.2.0/strmprivacy/api/credentials/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/credentials/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.300234 strmprivacy-api-definitions-3.2.0/strmprivacy/api/credentials/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/credentials/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5049 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/credentials/v1/credentials_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     8979 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/credentials/v1/credentials_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.301234 strmprivacy-api-definitions-3.2.0/strmprivacy/api/customer_entity_versions/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/customer_entity_versions/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.302234 strmprivacy-api-definitions-3.2.0/strmprivacy/api/customer_entity_versions/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/customer_entity_versions/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     7497 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/customer_entity_versions/v1/customer_entity_versions_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)    10288 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/customer_entity_versions/v1/customer_entity_versions_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.302234 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_connectors/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_connectors/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.303234 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_connectors/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_connectors/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5978 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_connectors/v1/data_connectors_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     9468 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_connectors/v1/data_connectors_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.307235 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_contracts/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_contracts/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.308235 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_contracts/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_contracts/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    22863 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_contracts/v1/data_contracts_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)    28488 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_contracts/v1/data_contracts_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.308235 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_subjects/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_subjects/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.309235 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_subjects/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_subjects/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     9499 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_subjects/v1/data_subjects_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     9865 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_subjects/v1/data_subjects_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.309235 strmprivacy-api-definitions-3.2.0/strmprivacy/api/entities/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/entities/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.310235 strmprivacy-api-definitions-3.2.0/strmprivacy/api/entities/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/entities/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    81835 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/entities/v1/entities_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)      159 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/entities/v1/entities_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.310235 strmprivacy-api-definitions-3.2.0/strmprivacy/api/entities/v1alpha/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/entities/v1alpha/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    12632 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/entities/v1alpha/entities_v1alpha_pb2.py
+-rw-r--r--   0 root         (0) root         (0)      159 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/entities/v1alpha/entities_v1alpha_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.311235 strmprivacy-api-definitions-3.2.0/strmprivacy/api/event_contracts/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/event_contracts/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.331237 strmprivacy-api-definitions-3.2.0/strmprivacy/api/event_contracts/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/event_contracts/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    15658 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/event_contracts/v1/event_contracts_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)    20098 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/event_contracts/v1/event_contracts_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.331237 strmprivacy-api-definitions-3.2.0/strmprivacy/api/handles/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/handles/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.332237 strmprivacy-api-definitions-3.2.0/strmprivacy/api/handles/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/handles/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     2239 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/handles/v1/handles_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     3057 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/handles/v1/handles_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.332237 strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.334237 strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     7909 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/v1/entities_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)      159 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/v1/entities_v1_pb2_grpc.py
+-rw-r--r--   0 root         (0) root         (0)     6253 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/v1/installations_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     9499 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/v1/installations_v1_pb2_grpc.py
+-rw-r--r--   0 root         (0) root         (0)     6958 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/v1/installed_components_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)    10345 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/v1/installed_components_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.334237 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_clusters/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_clusters/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.338237 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_clusters/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_clusters/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     6199 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_clusters/v1/kafka_clusters_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     9342 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_clusters/v1/kafka_clusters_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.339237 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_exporters/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_exporters/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.339237 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_exporters/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_exporters/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5362 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_exporters/v1/kafka_exporters_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     9468 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_exporters/v1/kafka_exporters_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.339237 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_users/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_users/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.340237 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_users/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_users/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5369 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_users/v1/kafka_users_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     8964 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_users/v1/kafka_users_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.341237 strmprivacy-api-definitions-3.2.0/strmprivacy/api/key_streams/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/key_streams/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.341237 strmprivacy-api-definitions-3.2.0/strmprivacy/api/key_streams/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/key_streams/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3713 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/key_streams/v1/key_streams_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     4941 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/key_streams/v1/key_streams_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.344238 strmprivacy-api-definitions-3.2.0/strmprivacy/api/monitoring/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/monitoring/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.362239 strmprivacy-api-definitions-3.2.0/strmprivacy/api/monitoring/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/monitoring/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     6738 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/monitoring/v1/monitoring_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     7722 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/monitoring/v1/monitoring_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.363239 strmprivacy-api-definitions-3.2.0/strmprivacy/api/notifications/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/notifications/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.364240 strmprivacy-api-definitions-3.2.0/strmprivacy/api/notifications/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/notifications/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    10605 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/notifications/v1/notifications_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)    13648 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/notifications/v1/notifications_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.365240 strmprivacy-api-definitions-3.2.0/strmprivacy/api/onboarding/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/onboarding/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.366240 strmprivacy-api-definitions-3.2.0/strmprivacy/api/onboarding/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/onboarding/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     2789 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/onboarding/v1/onboarding_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     3161 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/onboarding/v1/onboarding_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.367240 strmprivacy-api-definitions-3.2.0/strmprivacy/api/organizations/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/organizations/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.375240 strmprivacy-api-definitions-3.2.0/strmprivacy/api/organizations/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/organizations/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5842 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/organizations/v1/organizations_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     9075 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/organizations/v1/organizations_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.375240 strmprivacy-api-definitions-3.2.0/strmprivacy/api/paging/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/paging/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.376241 strmprivacy-api-definitions-3.2.0/strmprivacy/api/paging/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/paging/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1340 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/paging/v1/paging_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)      159 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/paging/v1/paging_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.376241 strmprivacy-api-definitions-3.2.0/strmprivacy/api/policies/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/policies/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.377241 strmprivacy-api-definitions-3.2.0/strmprivacy/api/policies/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/policies/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5782 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/policies/v1/policies_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)    10449 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/policies/v1/policies_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.377241 strmprivacy-api-definitions-3.2.0/strmprivacy/api/project_plans/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/project_plans/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.382241 strmprivacy-api-definitions-3.2.0/strmprivacy/api/project_plans/v1alpha/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/project_plans/v1alpha/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     4442 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/project_plans/v1alpha/project_plans_v1alpha_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     7409 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/project_plans/v1alpha/project_plans_v1alpha_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.383241 strmprivacy-api-definitions-3.2.0/strmprivacy/api/projects/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/projects/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.384241 strmprivacy-api-definitions-3.2.0/strmprivacy/api/projects/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/projects/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     7458 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/projects/v1/projects_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)    14509 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/projects/v1/projects_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.384241 strmprivacy-api-definitions-3.2.0/strmprivacy/api/purpose_mapping/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/purpose_mapping/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.392242 strmprivacy-api-definitions-3.2.0/strmprivacy/api/purpose_mapping/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/purpose_mapping/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     4483 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/purpose_mapping/v1/purpose_mapping_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     7407 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/purpose_mapping/v1/purpose_mapping_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.392242 strmprivacy-api-definitions-3.2.0/strmprivacy/api/schemas/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/schemas/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.399242 strmprivacy-api-definitions-3.2.0/strmprivacy/api/schemas/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/schemas/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    13192 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/schemas/v1/schemas_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)    17973 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/schemas/v1/schemas_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.400243 strmprivacy-api-definitions-3.2.0/strmprivacy/api/sinks/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/sinks/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.403243 strmprivacy-api-definitions-3.2.0/strmprivacy/api/sinks/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/sinks/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5254 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/sinks/v1/sinks_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     8223 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/sinks/v1/sinks_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.405243 strmprivacy-api-definitions-3.2.0/strmprivacy/api/streams/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/streams/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.409243 strmprivacy-api-definitions-3.2.0/strmprivacy/api/streams/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/streams/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5689 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/streams/v1/streams_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)    10437 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/streams/v1/streams_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.409243 strmprivacy-api-definitions-3.2.0/strmprivacy/api/usage/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/usage/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.415244 strmprivacy-api-definitions-3.2.0/strmprivacy/api/usage/v1/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 12:26:11.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/usage/v1/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     4644 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/usage/v1/usage_v1_pb2.py
+-rw-r--r--   0 root         (0) root         (0)     4831 2023-06-28 12:24:56.000000 strmprivacy-api-definitions-3.2.0/strmprivacy/api/usage/v1/usage_v1_pb2_grpc.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:26:12.435246 strmprivacy-api-definitions-3.2.0/strmprivacy_api_definitions.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      629 2023-06-28 12:26:12.000000 strmprivacy-api-definitions-3.2.0/strmprivacy_api_definitions.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     7436 2023-06-28 12:26:12.000000 strmprivacy-api-definitions-3.2.0/strmprivacy_api_definitions.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 12:26:12.000000 strmprivacy-api-definitions-3.2.0/strmprivacy_api_definitions.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 12:26:12.000000 strmprivacy-api-definitions-3.2.0/strmprivacy_api_definitions.egg-info/not-zip-safe
+-rw-r--r--   0 root         (0) root         (0)       15 2023-06-28 12:26:12.000000 strmprivacy-api-definitions-3.2.0/strmprivacy_api_definitions.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       12 2023-06-28 12:26:12.000000 strmprivacy-api-definitions-3.2.0/strmprivacy_api_definitions.egg-info/top_level.txt
```

### Comparing `strmprivacy-api-definitions-3.1.0/PKG-INFO` & `strmprivacy-api-definitions-3.2.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: strmprivacy-api-definitions
-Version: 3.1.0
+Version: 3.2.0
 Summary: STRM Privacy API definitions
 Home-page: UNKNOWN
 Author: Stream Machine B.V.
 Author-email: apis@strmprivacy.io
 License: UNKNOWN
 Keywords: strmprivacy api definitions
 Platform: UNKNOWN
```

### Comparing `strmprivacy-api-definitions-3.1.0/setup.py` & `strmprivacy-api-definitions-3.2.0/setup.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/account/v1/account_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/account/v1/account_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/account/v1/account_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/account/v1/account_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/batch_exporters_agent_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/batch_exporters_agent_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/batch_exporters_agent_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/batch_exporters_agent_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/batch_jobs_agent_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/batch_jobs_agent_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/batch_jobs_agent_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/batch_jobs_agent_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/data_connector_agent_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/data_connector_agent_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/data_connector_agent_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/data_connector_agent_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/streams_agent_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/streams_agent_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/agents/v1/streams_agent_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/agents/v1/streams_agent_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/audit/v1/audit_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/audit/v1/audit_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/audit/v1/audit_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/audit/v1/audit_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_exporters/v1/batch_exporters_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_exporters/v1/batch_exporters_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_exporters/v1/batch_exporters_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_exporters/v1/batch_exporters_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_jobs/v1/batch_jobs_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_jobs/v1/batch_jobs_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/batch_jobs/v1/batch_jobs_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/batch_jobs/v1/batch_jobs_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/cli/v1/cli_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/cli/v1/cli_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/cli/v1/cli_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/cli/v1/cli_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/comments/v1/comments_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/comments/v1/comments_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/comments/v1/comments_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/comments/v1/comments_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/credentials/v1/credentials_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/credentials/v1/credentials_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/credentials/v1/credentials_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/credentials/v1/credentials_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/customer_entity_versions/v1/customer_entity_versions_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/customer_entity_versions/v1/customer_entity_versions_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/customer_entity_versions/v1/customer_entity_versions_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/customer_entity_versions/v1/customer_entity_versions_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_connectors/v1/data_connectors_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_connectors/v1/data_connectors_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_connectors/v1/data_connectors_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_connectors/v1/data_connectors_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_contracts/v1/data_contracts_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_contracts/v1/data_contracts_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_contracts/v1/data_contracts_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_contracts/v1/data_contracts_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_subjects/v1/data_subjects_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_subjects/v1/data_subjects_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/data_subjects/v1/data_subjects_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/data_subjects/v1/data_subjects_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/entities/v1/entities_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/entities/v1/entities_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/entities/v1alpha/entities_v1alpha_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/entities/v1alpha/entities_v1alpha_pb2.py`

 * *Files 2% similar despite different names*

```diff
@@ -13,15 +13,15 @@
 
 from google.api import field_behavior_pb2 as google_dot_api_dot_field__behavior__pb2
 from google.protobuf import timestamp_pb2 as google_dot_protobuf_dot_timestamp__pb2
 from validate import validate_pb2 as validate_dot_validate__pb2
 from strmprivacy.api.entities.v1 import entities_v1_pb2 as strmprivacy_dot_api_dot_entities_dot_v1_dot_entities__v1__pb2
 
 
-DESCRIPTOR = _descriptor_pool.Default().AddSerializedFile(b'\n7strmprivacy/api/entities/v1alpha/entities_v1alpha.proto\x12 strmprivacy.api.entities.v1alpha\x1a\x1fgoogle/api/field_behavior.proto\x1a\x1fgoogle/protobuf/timestamp.proto\x1a\x17validate/validate.proto\x1a-strmprivacy/api/entities/v1/entities_v1.proto\"\xc2\x02\n\x0bProjectPlan\x12\x1d\n\nproject_id\x18\x01 \x01(\tR\tprojectId\x12#\n\x05title\x18\x02 \x01(\tB\r\xfa\x42\nr\x08\x10\x01\x18\xac\x02\xd0\x01\x01R\x05title\x12-\n\x0b\x64\x65scription\x18\x03 \x01(\tB\x0b\xfa\x42\x08r\x06\x18\x88\'\xd0\x01\x01R\x0b\x64\x65scription\x12L\n\x0bitem_groups\x18\x04 \x03(\x0b\x32+.strmprivacy.api.entities.v1alpha.ItemGroupR\nitemGroups\x12\x37\n\x05users\x18\x05 \x03(\x0b\x32!.strmprivacy.api.entities.v1.UserR\x05users\x12\x1f\n\x0bis_template\x18\x06 \x01(\x08R\nisTemplate\x12\x18\n\x02id\x18\x07 \x01(\tB\x08\xfa\x42\x05r\x03\xb0\x01\x01R\x02id\"\xae\x04\n\tItemGroup\x12\x1d\n\x04name\x18\x01 \x01(\tB\t\xfa\x42\x06r\x04\x10\x01\x18\x64R\x04name\x12-\n\x0b\x64\x65scription\x18\x02 \x01(\tB\x0b\xfa\x42\x08r\x06\x18\x88\'\xd0\x01\x01R\x0b\x64\x65scription\x12L\n\ntodo_items\x18\x04 \x01(\x0b\x32+.strmprivacy.api.entities.v1alpha.TodoItemsH\x00R\ttodoItems\x12\x65\n\x13\x64\x61ta_contract_items\x18\x05 \x01(\x0b\x32\x33.strmprivacy.api.entities.v1alpha.DataContractItemsH\x00R\x11\x64\x61taContractItems\x12\\\n\x10info_asset_items\x18\x06 \x01(\x0b\x32\x30.strmprivacy.api.entities.v1alpha.InfoAssetItemsH\x00R\x0einfoAssetItems\x12X\n\x0e\x64ocument_items\x18\x07 \x01(\x0b\x32/.strmprivacy.api.entities.v1alpha.DocumentItemsH\x00R\rdocumentItems\x12X\n\x0epipeline_items\x18\x08 \x01(\x0b\x32/.strmprivacy.api.entities.v1alpha.PipelineItemsH\x00R\rpipelineItemsB\x0c\n\x05items\x12\x03\xf8\x42\x01\"\xe3\x02\n\x0eItemProperties\x12\x18\n\x02id\x18\x01 \x01(\tB\x08\xfa\x42\x05r\x03\xb0\x01\x01R\x02id\x12?\n\rcreation_time\x18\x02 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\x0c\x63reationTime\x12\x35\n\x08\x64ue_time\x18\x03 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\x07\x64ueTime\x12\x43\n\x0f\x63ompletion_time\x18\x04 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\x0e\x63ompletionTime\x12;\n\x07\x63reator\x18\x05 \x01(\x0b\x32!.strmprivacy.api.entities.v1.UserR\x07\x63reator\x12=\n\x08\x61ssignee\x18\x06 \x01(\x0b\x32!.strmprivacy.api.entities.v1.UserR\x08\x61ssignee\"\xeb\x01\n\tTodoItems\x12J\n\x05items\x18\x02 \x03(\x0b\x32\x34.strmprivacy.api.entities.v1alpha.TodoItems.TodoItemR\x05items\x1a\x91\x01\n\x08TodoItem\x12Y\n\x0fitem_properties\x18\x01 \x01(\x0b\x32\x30.strmprivacy.api.entities.v1alpha.ItemPropertiesR\x0eitemProperties\x12*\n\x0b\x64\x65scription\x18\x02 \x01(\tB\x08\xfa\x42\x05r\x03\x18\x88\'R\x0b\x64\x65scription\"\xa9\x02\n\x11\x44\x61taContractItems\x12Z\n\x05items\x18\x01 \x03(\x0b\x32\x44.strmprivacy.api.entities.v1alpha.DataContractItems.DataContractItemR\x05items\x1a\xb7\x01\n\x10\x44\x61taContractItem\x12Y\n\x0fitem_properties\x18\x01 \x01(\x0b\x32\x30.strmprivacy.api.entities.v1alpha.ItemPropertiesR\x0eitemProperties\x12H\n\x03ref\x18\x02 \x01(\x0b\x32,.strmprivacy.api.entities.v1.DataContractRefB\x08\xfa\x42\x05\x8a\x01\x02\x10\x01R\x03ref\"\xc2\x05\n\x0eInfoAssetItems\x12T\n\x05items\x18\x01 \x03(\x0b\x32>.strmprivacy.api.entities.v1alpha.InfoAssetItems.InfoAssetItemR\x05items\x1a\xd9\x04\n\rInfoAssetItem\x12Y\n\x0fitem_properties\x18\x01 \x01(\x0b\x32\x30.strmprivacy.api.entities.v1alpha.ItemPropertiesR\x0eitemProperties\x12\x1c\n\x04name\x18\x02 \x01(\tB\x08\xfa\x42\x05r\x03\x18\xac\x02R\x04name\x12_\n\x05state\x18\x03 \x01(\x0e\x32\x44.strmprivacy.api.entities.v1alpha.InfoAssetItems.InfoAssetItem.StateB\x03\xe0\x41\x03R\x05state\x12u\n\x0e\x63lassification\x18\x04 \x01(\x0b\x32M.strmprivacy.api.entities.v1alpha.InfoAssetItems.InfoAssetItem.ClassificationR\x0e\x63lassification\x12J\n\ninfo_asset\x18\x05 \x01(\x0b\x32+.strmprivacy.api.entities.v1alpha.InfoAssetR\tinfoAsset\x1a\x63\n\x0e\x43lassification\x12\x1c\n\x04name\x18\x01 \x01(\tB\x08\xfa\x42\x05r\x03\x18\xac\x02R\x04name\x12\x1b\n\tcolor_css\x18\x02 \x01(\tR\x08\x63olorCss\x12\x16\n\x06points\x18\x04 \x01(\x05R\x06points\"F\n\x05State\x12\x15\n\x11STATE_UNSPECIFIED\x10\x00\x12\t\n\x05\x44RAFT\x10\x01\x12\r\n\tIN_REVIEW\x10\x02\x12\x0c\n\x08\x41PPROVED\x10\x03\"\xfd\x01\n\rDocumentItems\x12R\n\x05items\x18\x01 \x03(\x0b\x32<.strmprivacy.api.entities.v1alpha.DocumentItems.DocumentItemR\x05items\x1a\x97\x01\n\x0c\x44ocumentItem\x12Y\n\x0fitem_properties\x18\x01 \x01(\x0b\x32\x30.strmprivacy.api.entities.v1alpha.ItemPropertiesR\x0eitemProperties\x12\x1a\n\x08\x66ilename\x18\x02 \x01(\tR\x08\x66ilename\x12\x10\n\x03uri\x18\x03 \x01(\tR\x03uri\"\xeb\x02\n\rPipelineItems\x12R\n\x05items\x18\x02 \x03(\x0b\x32<.strmprivacy.api.entities.v1alpha.PipelineItems.PipelineItemR\x05items\x1a\x85\x02\n\x0cPipelineItem\x12Y\n\x0fitem_properties\x18\x01 \x01(\x0b\x32\x30.strmprivacy.api.entities.v1alpha.ItemPropertiesR\x0eitemProperties\x12@\n\x06stream\x18\x02 \x01(\x0b\x32&.strmprivacy.api.entities.v1.StreamRefH\x00R\x06stream\x12G\n\tbatch_job\x18\x03 \x01(\x0b\x32(.strmprivacy.api.entities.v1.BatchJobRefH\x00R\x08\x62\x61tchJobB\x0f\n\x08pipeline\x12\x03\xf8\x42\x01\"\xfd\x07\n\tInfoAsset\x12\x1a\n\x08template\x18\x01 \x01(\tR\x08template\x12\x12\n\x04name\x18\x02 \x01(\tR\x04name\x12\x18\n\x07\x65mbargo\x18\x03 \x01(\x08R\x07\x65mbargo\x12k\n\x10\x62usiness_impacts\x18\x04 \x03(\x0b\x32@.strmprivacy.api.entities.v1alpha.InfoAsset.BusinessImpactRatingR\x0f\x62usinessImpacts\x12\'\n\x0fsecurity_levels\x18\x05 \x03(\tR\x0esecurityLevels\x12%\n\x0esecurity_level\x18\x06 \x01(\tR\rsecurityLevel\x12O\n\x08sections\x18\x07 \x03(\x0b\x32\x33.strmprivacy.api.entities.v1alpha.InfoAsset.SectionR\x08sections\x12\x1f\n\x0bis_template\x18\x08 \x01(\x08R\nisTemplate\x1ax\n\x07Section\x12\x12\n\x04name\x18\x01 \x01(\tR\x04name\x12Y\n\x0csub_sections\x18\x02 \x03(\x0b\x32\x36.strmprivacy.api.entities.v1alpha.InfoAsset.SubSectionR\x0bsubSections\x1a\xaf\x01\n\nSubSection\x12\x12\n\x04name\x18\x01 \x01(\tR\x04name\x12 \n\x0b\x64\x65scription\x18\x02 \x01(\tR\x0b\x64\x65scription\x12 \n\x0b\x65xplanation\x18\x03 \x01(\tR\x0b\x65xplanation\x12I\n\x06\x63hecks\x18\x04 \x03(\x0b\x32\x31.strmprivacy.api.entities.v1alpha.InfoAsset.CheckR\x06\x63hecks\x1aV\n\x05\x43heck\x12\x12\n\x04name\x18\x01 \x01(\tR\x04name\x12\x1f\n\x0b\x64\x65tail_info\x18\x02 \x01(\tR\ndetailInfo\x12\x18\n\x07\x63hecked\x18\x03 \x01(\x08R\x07\x63hecked\x1a\x8c\x01\n\x14\x42usinessImpactRating\x12\x14\n\x05label\x18\x01 \x01(\tR\x05label\x12^\n\x08\x63\x61tegory\x18\x02 \x01(\x0b\x32\x42.strmprivacy.api.entities.v1alpha.InfoAsset.BusinessImpactCategoryR\x08\x63\x61tegory\x1a\x64\n\x16\x42usinessImpactCategory\x12\x12\n\x04name\x18\x01 \x01(\tR\x04name\x12 \n\x0b\x64\x65scription\x18\x02 \x01(\tR\x0b\x64\x65scription\x12\x14\n\x05value\x18\x03 \x01(\x02R\x05valueBs\n#io.strmprivacy.api.entities.v1alphaP\x01ZJgithub.com/strmprivacy/api-definitions-go/v2/api/entities/v1alpha;entitiesb\x06proto3')
+DESCRIPTOR = _descriptor_pool.Default().AddSerializedFile(b'\n7strmprivacy/api/entities/v1alpha/entities_v1alpha.proto\x12 strmprivacy.api.entities.v1alpha\x1a\x1fgoogle/api/field_behavior.proto\x1a\x1fgoogle/protobuf/timestamp.proto\x1a\x17validate/validate.proto\x1a-strmprivacy/api/entities/v1/entities_v1.proto\"\xc2\x02\n\x0bProjectPlan\x12\x1d\n\nproject_id\x18\x01 \x01(\tR\tprojectId\x12#\n\x05title\x18\x02 \x01(\tB\r\xfa\x42\nr\x08\x10\x01\x18\xac\x02\xd0\x01\x01R\x05title\x12-\n\x0b\x64\x65scription\x18\x03 \x01(\tB\x0b\xfa\x42\x08r\x06\x18\x88\'\xd0\x01\x01R\x0b\x64\x65scription\x12L\n\x0bitem_groups\x18\x04 \x03(\x0b\x32+.strmprivacy.api.entities.v1alpha.ItemGroupR\nitemGroups\x12\x37\n\x05users\x18\x05 \x03(\x0b\x32!.strmprivacy.api.entities.v1.UserR\x05users\x12\x1f\n\x0bis_template\x18\x06 \x01(\x08R\nisTemplate\x12\x18\n\x02id\x18\x07 \x01(\tB\x08\xfa\x42\x05r\x03\xb0\x01\x01R\x02id\"\xcb\x04\n\tItemGroup\x12\x1d\n\x04name\x18\x01 \x01(\tB\t\xfa\x42\x06r\x04\x10\x01\x18\x64R\x04name\x12-\n\x0b\x64\x65scription\x18\x02 \x01(\tB\x0b\xfa\x42\x08r\x06\x18\x88\'\xd0\x01\x01R\x0b\x64\x65scription\x12L\n\ntodo_items\x18\x04 \x01(\x0b\x32+.strmprivacy.api.entities.v1alpha.TodoItemsH\x00R\ttodoItems\x12\x65\n\x13\x64\x61ta_contract_items\x18\x05 \x01(\x0b\x32\x33.strmprivacy.api.entities.v1alpha.DataContractItemsH\x00R\x11\x64\x61taContractItems\x12\\\n\x10info_asset_items\x18\x06 \x01(\x0b\x32\x30.strmprivacy.api.entities.v1alpha.InfoAssetItemsH\x00R\x0einfoAssetItems\x12X\n\x0e\x64ocument_items\x18\x07 \x01(\x0b\x32/.strmprivacy.api.entities.v1alpha.DocumentItemsH\x00R\rdocumentItems\x12X\n\x0epipeline_items\x18\x08 \x01(\x0b\x32/.strmprivacy.api.entities.v1alpha.PipelineItemsH\x00R\rpipelineItems\x12\x1b\n\x02id\x18\t \x01(\tB\x0b\xfa\x42\x08r\x06\xd0\x01\x01\xb0\x01\x01R\x02idB\x0c\n\x05items\x12\x03\xf8\x42\x01\"\xe6\x02\n\x0eItemProperties\x12\x1b\n\x02id\x18\x01 \x01(\tB\x0b\xfa\x42\x08r\x06\xd0\x01\x01\xb0\x01\x01R\x02id\x12?\n\rcreation_time\x18\x02 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\x0c\x63reationTime\x12\x35\n\x08\x64ue_time\x18\x03 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\x07\x64ueTime\x12\x43\n\x0f\x63ompletion_time\x18\x04 \x01(\x0b\x32\x1a.google.protobuf.TimestampR\x0e\x63ompletionTime\x12;\n\x07\x63reator\x18\x05 \x01(\x0b\x32!.strmprivacy.api.entities.v1.UserR\x07\x63reator\x12=\n\x08\x61ssignee\x18\x06 \x01(\x0b\x32!.strmprivacy.api.entities.v1.UserR\x08\x61ssignee\"\xeb\x01\n\tTodoItems\x12J\n\x05items\x18\x02 \x03(\x0b\x32\x34.strmprivacy.api.entities.v1alpha.TodoItems.TodoItemR\x05items\x1a\x91\x01\n\x08TodoItem\x12Y\n\x0fitem_properties\x18\x01 \x01(\x0b\x32\x30.strmprivacy.api.entities.v1alpha.ItemPropertiesR\x0eitemProperties\x12*\n\x0b\x64\x65scription\x18\x02 \x01(\tB\x08\xfa\x42\x05r\x03\x18\x88\'R\x0b\x64\x65scription\"\xa9\x02\n\x11\x44\x61taContractItems\x12Z\n\x05items\x18\x01 \x03(\x0b\x32\x44.strmprivacy.api.entities.v1alpha.DataContractItems.DataContractItemR\x05items\x1a\xb7\x01\n\x10\x44\x61taContractItem\x12Y\n\x0fitem_properties\x18\x01 \x01(\x0b\x32\x30.strmprivacy.api.entities.v1alpha.ItemPropertiesR\x0eitemProperties\x12H\n\x03ref\x18\x02 \x01(\x0b\x32,.strmprivacy.api.entities.v1.DataContractRefB\x08\xfa\x42\x05\x8a\x01\x02\x10\x01R\x03ref\"\xc2\x05\n\x0eInfoAssetItems\x12T\n\x05items\x18\x01 \x03(\x0b\x32>.strmprivacy.api.entities.v1alpha.InfoAssetItems.InfoAssetItemR\x05items\x1a\xd9\x04\n\rInfoAssetItem\x12Y\n\x0fitem_properties\x18\x01 \x01(\x0b\x32\x30.strmprivacy.api.entities.v1alpha.ItemPropertiesR\x0eitemProperties\x12\x1c\n\x04name\x18\x02 \x01(\tB\x08\xfa\x42\x05r\x03\x18\xac\x02R\x04name\x12_\n\x05state\x18\x03 \x01(\x0e\x32\x44.strmprivacy.api.entities.v1alpha.InfoAssetItems.InfoAssetItem.StateB\x03\xe0\x41\x03R\x05state\x12u\n\x0e\x63lassification\x18\x04 \x01(\x0b\x32M.strmprivacy.api.entities.v1alpha.InfoAssetItems.InfoAssetItem.ClassificationR\x0e\x63lassification\x12J\n\ninfo_asset\x18\x05 \x01(\x0b\x32+.strmprivacy.api.entities.v1alpha.InfoAssetR\tinfoAsset\x1a\x63\n\x0e\x43lassification\x12\x1c\n\x04name\x18\x01 \x01(\tB\x08\xfa\x42\x05r\x03\x18\xac\x02R\x04name\x12\x1b\n\tcolor_css\x18\x02 \x01(\tR\x08\x63olorCss\x12\x16\n\x06points\x18\x04 \x01(\x05R\x06points\"F\n\x05State\x12\x15\n\x11STATE_UNSPECIFIED\x10\x00\x12\t\n\x05\x44RAFT\x10\x01\x12\r\n\tIN_REVIEW\x10\x02\x12\x0c\n\x08\x41PPROVED\x10\x03\"\xfd\x01\n\rDocumentItems\x12R\n\x05items\x18\x01 \x03(\x0b\x32<.strmprivacy.api.entities.v1alpha.DocumentItems.DocumentItemR\x05items\x1a\x97\x01\n\x0c\x44ocumentItem\x12Y\n\x0fitem_properties\x18\x01 \x01(\x0b\x32\x30.strmprivacy.api.entities.v1alpha.ItemPropertiesR\x0eitemProperties\x12\x1a\n\x08\x66ilename\x18\x02 \x01(\tR\x08\x66ilename\x12\x10\n\x03uri\x18\x03 \x01(\tR\x03uri\"\xeb\x02\n\rPipelineItems\x12R\n\x05items\x18\x02 \x03(\x0b\x32<.strmprivacy.api.entities.v1alpha.PipelineItems.PipelineItemR\x05items\x1a\x85\x02\n\x0cPipelineItem\x12Y\n\x0fitem_properties\x18\x01 \x01(\x0b\x32\x30.strmprivacy.api.entities.v1alpha.ItemPropertiesR\x0eitemProperties\x12@\n\x06stream\x18\x02 \x01(\x0b\x32&.strmprivacy.api.entities.v1.StreamRefH\x00R\x06stream\x12G\n\tbatch_job\x18\x03 \x01(\x0b\x32(.strmprivacy.api.entities.v1.BatchJobRefH\x00R\x08\x62\x61tchJobB\x0f\n\x08pipeline\x12\x03\xf8\x42\x01\"\xfd\x07\n\tInfoAsset\x12\x1a\n\x08template\x18\x01 \x01(\tR\x08template\x12\x12\n\x04name\x18\x02 \x01(\tR\x04name\x12\x18\n\x07\x65mbargo\x18\x03 \x01(\x08R\x07\x65mbargo\x12k\n\x10\x62usiness_impacts\x18\x04 \x03(\x0b\x32@.strmprivacy.api.entities.v1alpha.InfoAsset.BusinessImpactRatingR\x0f\x62usinessImpacts\x12\'\n\x0fsecurity_levels\x18\x05 \x03(\tR\x0esecurityLevels\x12%\n\x0esecurity_level\x18\x06 \x01(\tR\rsecurityLevel\x12O\n\x08sections\x18\x07 \x03(\x0b\x32\x33.strmprivacy.api.entities.v1alpha.InfoAsset.SectionR\x08sections\x12\x1f\n\x0bis_template\x18\x08 \x01(\x08R\nisTemplate\x1ax\n\x07Section\x12\x12\n\x04name\x18\x01 \x01(\tR\x04name\x12Y\n\x0csub_sections\x18\x02 \x03(\x0b\x32\x36.strmprivacy.api.entities.v1alpha.InfoAsset.SubSectionR\x0bsubSections\x1a\xaf\x01\n\nSubSection\x12\x12\n\x04name\x18\x01 \x01(\tR\x04name\x12 \n\x0b\x64\x65scription\x18\x02 \x01(\tR\x0b\x64\x65scription\x12 \n\x0b\x65xplanation\x18\x03 \x01(\tR\x0b\x65xplanation\x12I\n\x06\x63hecks\x18\x04 \x03(\x0b\x32\x31.strmprivacy.api.entities.v1alpha.InfoAsset.CheckR\x06\x63hecks\x1aV\n\x05\x43heck\x12\x12\n\x04name\x18\x01 \x01(\tR\x04name\x12\x1f\n\x0b\x64\x65tail_info\x18\x02 \x01(\tR\ndetailInfo\x12\x18\n\x07\x63hecked\x18\x03 \x01(\x08R\x07\x63hecked\x1a\x8c\x01\n\x14\x42usinessImpactRating\x12\x14\n\x05label\x18\x01 \x01(\tR\x05label\x12^\n\x08\x63\x61tegory\x18\x02 \x01(\x0b\x32\x42.strmprivacy.api.entities.v1alpha.InfoAsset.BusinessImpactCategoryR\x08\x63\x61tegory\x1a\x64\n\x16\x42usinessImpactCategory\x12\x12\n\x04name\x18\x01 \x01(\tR\x04name\x12 \n\x0b\x64\x65scription\x18\x02 \x01(\tR\x0b\x64\x65scription\x12\x14\n\x05value\x18\x03 \x01(\x02R\x05valueBs\n#io.strmprivacy.api.entities.v1alphaP\x01ZJgithub.com/strmprivacy/api-definitions-go/v2/api/entities/v1alpha;entitiesb\x06proto3')
 
 _builder.BuildMessageAndEnumDescriptors(DESCRIPTOR, globals())
 _builder.BuildTopDescriptorsAndMessages(DESCRIPTOR, 'strmprivacy.api.entities.v1alpha.entities_v1alpha_pb2', globals())
 if _descriptor._USE_C_DESCRIPTORS == False:
 
   DESCRIPTOR._options = None
   DESCRIPTOR._serialized_options = b'\n#io.strmprivacy.api.entities.v1alphaP\001ZJgithub.com/strmprivacy/api-definitions-go/v2/api/entities/v1alpha;entities'
@@ -33,16 +33,18 @@
   _PROJECTPLAN.fields_by_name['id']._serialized_options = b'\372B\005r\003\260\001\001'
   _ITEMGROUP.oneofs_by_name['items']._options = None
   _ITEMGROUP.oneofs_by_name['items']._serialized_options = b'\370B\001'
   _ITEMGROUP.fields_by_name['name']._options = None
   _ITEMGROUP.fields_by_name['name']._serialized_options = b'\372B\006r\004\020\001\030d'
   _ITEMGROUP.fields_by_name['description']._options = None
   _ITEMGROUP.fields_by_name['description']._serialized_options = b'\372B\010r\006\030\210\'\320\001\001'
+  _ITEMGROUP.fields_by_name['id']._options = None
+  _ITEMGROUP.fields_by_name['id']._serialized_options = b'\372B\010r\006\320\001\001\260\001\001'
   _ITEMPROPERTIES.fields_by_name['id']._options = None
-  _ITEMPROPERTIES.fields_by_name['id']._serialized_options = b'\372B\005r\003\260\001\001'
+  _ITEMPROPERTIES.fields_by_name['id']._serialized_options = b'\372B\010r\006\320\001\001\260\001\001'
   _TODOITEMS_TODOITEM.fields_by_name['description']._options = None
   _TODOITEMS_TODOITEM.fields_by_name['description']._serialized_options = b'\372B\005r\003\030\210\''
   _DATACONTRACTITEMS_DATACONTRACTITEM.fields_by_name['ref']._options = None
   _DATACONTRACTITEMS_DATACONTRACTITEM.fields_by_name['ref']._serialized_options = b'\372B\005\212\001\002\020\001'
   _INFOASSETITEMS_INFOASSETITEM_CLASSIFICATION.fields_by_name['name']._options = None
   _INFOASSETITEMS_INFOASSETITEM_CLASSIFICATION.fields_by_name['name']._serialized_options = b'\372B\005r\003\030\254\002'
   _INFOASSETITEMS_INFOASSETITEM.fields_by_name['name']._options = None
@@ -50,47 +52,47 @@
   _INFOASSETITEMS_INFOASSETITEM.fields_by_name['state']._options = None
   _INFOASSETITEMS_INFOASSETITEM.fields_by_name['state']._serialized_options = b'\340A\003'
   _PIPELINEITEMS_PIPELINEITEM.oneofs_by_name['pipeline']._options = None
   _PIPELINEITEMS_PIPELINEITEM.oneofs_by_name['pipeline']._serialized_options = b'\370B\001'
   _PROJECTPLAN._serialized_start=232
   _PROJECTPLAN._serialized_end=554
   _ITEMGROUP._serialized_start=557
-  _ITEMGROUP._serialized_end=1115
-  _ITEMPROPERTIES._serialized_start=1118
-  _ITEMPROPERTIES._serialized_end=1473
-  _TODOITEMS._serialized_start=1476
-  _TODOITEMS._serialized_end=1711
-  _TODOITEMS_TODOITEM._serialized_start=1566
-  _TODOITEMS_TODOITEM._serialized_end=1711
-  _DATACONTRACTITEMS._serialized_start=1714
-  _DATACONTRACTITEMS._serialized_end=2011
-  _DATACONTRACTITEMS_DATACONTRACTITEM._serialized_start=1828
-  _DATACONTRACTITEMS_DATACONTRACTITEM._serialized_end=2011
-  _INFOASSETITEMS._serialized_start=2014
-  _INFOASSETITEMS._serialized_end=2720
-  _INFOASSETITEMS_INFOASSETITEM._serialized_start=2119
-  _INFOASSETITEMS_INFOASSETITEM._serialized_end=2720
-  _INFOASSETITEMS_INFOASSETITEM_CLASSIFICATION._serialized_start=2549
-  _INFOASSETITEMS_INFOASSETITEM_CLASSIFICATION._serialized_end=2648
-  _INFOASSETITEMS_INFOASSETITEM_STATE._serialized_start=2650
-  _INFOASSETITEMS_INFOASSETITEM_STATE._serialized_end=2720
-  _DOCUMENTITEMS._serialized_start=2723
-  _DOCUMENTITEMS._serialized_end=2976
-  _DOCUMENTITEMS_DOCUMENTITEM._serialized_start=2825
-  _DOCUMENTITEMS_DOCUMENTITEM._serialized_end=2976
-  _PIPELINEITEMS._serialized_start=2979
-  _PIPELINEITEMS._serialized_end=3342
-  _PIPELINEITEMS_PIPELINEITEM._serialized_start=3081
-  _PIPELINEITEMS_PIPELINEITEM._serialized_end=3342
-  _INFOASSET._serialized_start=3345
-  _INFOASSET._serialized_end=4366
-  _INFOASSET_SECTION._serialized_start=3735
-  _INFOASSET_SECTION._serialized_end=3855
-  _INFOASSET_SUBSECTION._serialized_start=3858
-  _INFOASSET_SUBSECTION._serialized_end=4033
-  _INFOASSET_CHECK._serialized_start=4035
-  _INFOASSET_CHECK._serialized_end=4121
-  _INFOASSET_BUSINESSIMPACTRATING._serialized_start=4124
-  _INFOASSET_BUSINESSIMPACTRATING._serialized_end=4264
-  _INFOASSET_BUSINESSIMPACTCATEGORY._serialized_start=4266
-  _INFOASSET_BUSINESSIMPACTCATEGORY._serialized_end=4366
+  _ITEMGROUP._serialized_end=1144
+  _ITEMPROPERTIES._serialized_start=1147
+  _ITEMPROPERTIES._serialized_end=1505
+  _TODOITEMS._serialized_start=1508
+  _TODOITEMS._serialized_end=1743
+  _TODOITEMS_TODOITEM._serialized_start=1598
+  _TODOITEMS_TODOITEM._serialized_end=1743
+  _DATACONTRACTITEMS._serialized_start=1746
+  _DATACONTRACTITEMS._serialized_end=2043
+  _DATACONTRACTITEMS_DATACONTRACTITEM._serialized_start=1860
+  _DATACONTRACTITEMS_DATACONTRACTITEM._serialized_end=2043
+  _INFOASSETITEMS._serialized_start=2046
+  _INFOASSETITEMS._serialized_end=2752
+  _INFOASSETITEMS_INFOASSETITEM._serialized_start=2151
+  _INFOASSETITEMS_INFOASSETITEM._serialized_end=2752
+  _INFOASSETITEMS_INFOASSETITEM_CLASSIFICATION._serialized_start=2581
+  _INFOASSETITEMS_INFOASSETITEM_CLASSIFICATION._serialized_end=2680
+  _INFOASSETITEMS_INFOASSETITEM_STATE._serialized_start=2682
+  _INFOASSETITEMS_INFOASSETITEM_STATE._serialized_end=2752
+  _DOCUMENTITEMS._serialized_start=2755
+  _DOCUMENTITEMS._serialized_end=3008
+  _DOCUMENTITEMS_DOCUMENTITEM._serialized_start=2857
+  _DOCUMENTITEMS_DOCUMENTITEM._serialized_end=3008
+  _PIPELINEITEMS._serialized_start=3011
+  _PIPELINEITEMS._serialized_end=3374
+  _PIPELINEITEMS_PIPELINEITEM._serialized_start=3113
+  _PIPELINEITEMS_PIPELINEITEM._serialized_end=3374
+  _INFOASSET._serialized_start=3377
+  _INFOASSET._serialized_end=4398
+  _INFOASSET_SECTION._serialized_start=3767
+  _INFOASSET_SECTION._serialized_end=3887
+  _INFOASSET_SUBSECTION._serialized_start=3890
+  _INFOASSET_SUBSECTION._serialized_end=4065
+  _INFOASSET_CHECK._serialized_start=4067
+  _INFOASSET_CHECK._serialized_end=4153
+  _INFOASSET_BUSINESSIMPACTRATING._serialized_start=4156
+  _INFOASSET_BUSINESSIMPACTRATING._serialized_end=4296
+  _INFOASSET_BUSINESSIMPACTCATEGORY._serialized_start=4298
+  _INFOASSET_BUSINESSIMPACTCATEGORY._serialized_end=4398
 # @@protoc_insertion_point(module_scope)
```

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/event_contracts/v1/event_contracts_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/event_contracts/v1/event_contracts_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/event_contracts/v1/event_contracts_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/event_contracts/v1/event_contracts_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/handles/v1/handles_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/handles/v1/handles_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/handles/v1/handles_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/handles/v1/handles_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/v1/entities_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/v1/entities_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/v1/installations_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/v1/installations_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/v1/installations_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/v1/installations_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/v1/installed_components_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/v1/installed_components_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/installations/v1/installed_components_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/installations/v1/installed_components_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_clusters/v1/kafka_clusters_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_clusters/v1/kafka_clusters_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_clusters/v1/kafka_clusters_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_clusters/v1/kafka_clusters_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_exporters/v1/kafka_exporters_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_exporters/v1/kafka_exporters_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_exporters/v1/kafka_exporters_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_exporters/v1/kafka_exporters_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_users/v1/kafka_users_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_users/v1/kafka_users_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/kafka_users/v1/kafka_users_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/kafka_users/v1/kafka_users_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/key_streams/v1/key_streams_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/key_streams/v1/key_streams_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/key_streams/v1/key_streams_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/key_streams/v1/key_streams_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/monitoring/v1/monitoring_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/monitoring/v1/monitoring_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/monitoring/v1/monitoring_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/monitoring/v1/monitoring_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/notifications/v1/notifications_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/notifications/v1/notifications_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/notifications/v1/notifications_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/notifications/v1/notifications_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/onboarding/v1/onboarding_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/onboarding/v1/onboarding_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/onboarding/v1/onboarding_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/onboarding/v1/onboarding_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/organizations/v1/organizations_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/organizations/v1/organizations_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/organizations/v1/organizations_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/organizations/v1/organizations_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/paging/v1/paging_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/paging/v1/paging_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/policies/v1/policies_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/policies/v1/policies_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/policies/v1/policies_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/policies/v1/policies_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/project_plans/v1alpha/project_plans_v1alpha_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/project_plans/v1alpha/project_plans_v1alpha_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/project_plans/v1alpha/project_plans_v1alpha_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/project_plans/v1alpha/project_plans_v1alpha_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/projects/v1/projects_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/projects/v1/projects_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/projects/v1/projects_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/projects/v1/projects_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/purpose_mapping/v1/purpose_mapping_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/purpose_mapping/v1/purpose_mapping_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/purpose_mapping/v1/purpose_mapping_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/purpose_mapping/v1/purpose_mapping_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/schemas/v1/schemas_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/schemas/v1/schemas_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/schemas/v1/schemas_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/schemas/v1/schemas_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/sinks/v1/sinks_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/sinks/v1/sinks_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/sinks/v1/sinks_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/sinks/v1/sinks_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/streams/v1/streams_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/streams/v1/streams_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/streams/v1/streams_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/streams/v1/streams_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/usage/v1/usage_v1_pb2.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/usage/v1/usage_v1_pb2.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy/api/usage/v1/usage_v1_pb2_grpc.py` & `strmprivacy-api-definitions-3.2.0/strmprivacy/api/usage/v1/usage_v1_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy_api_definitions.egg-info/PKG-INFO` & `strmprivacy-api-definitions-3.2.0/strmprivacy_api_definitions.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: strmprivacy-api-definitions
-Version: 3.1.0
+Version: 3.2.0
 Summary: STRM Privacy API definitions
 Home-page: UNKNOWN
 Author: Stream Machine B.V.
 Author-email: apis@strmprivacy.io
 License: UNKNOWN
 Keywords: strmprivacy api definitions
 Platform: UNKNOWN
```

### Comparing `strmprivacy-api-definitions-3.1.0/strmprivacy_api_definitions.egg-info/SOURCES.txt` & `strmprivacy-api-definitions-3.2.0/strmprivacy_api_definitions.egg-info/SOURCES.txt`

 * *Files identical despite different names*


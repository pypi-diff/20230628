# Comparing `tmp/types-aiobotocore-iot-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iot-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iot-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:46 2023, max compression
+gzip compressed data, was "types-aiobotocore-iot-2.5.1.tar", last modified: Wed Jun 28 01:43:37 2023, max compression
```

## Comparing `types-aiobotocore-iot-2.5.0.post1.tar` & `types-aiobotocore-iot-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.367293 types-aiobotocore-iot-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:59.000000 types-aiobotocore-iot-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    53179 2023-03-11 12:26:46.367293 types-aiobotocore-iot-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    51624 2023-03-11 12:15:59.000000 types-aiobotocore-iot-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:46.367293 types-aiobotocore-iot-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:15:59.000000 types-aiobotocore-iot-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.367293 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/
--rw-r--r--   0 runner    (1001) docker     (123)    13213 2023-03-11 12:15:59.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13212 2023-03-11 12:15:59.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:15:59.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)   180485 2023-03-11 12:16:01.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/client.py
--rw-r--r--   0 runner    (1001) docker     (123)   180183 2023-03-11 12:16:00.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    23887 2023-03-11 12:16:03.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    23885 2023-03-11 12:16:01.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    67154 2023-03-11 12:16:01.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    67096 2023-03-11 12:16:01.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:59.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   244686 2023-03-11 12:16:09.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   244377 2023-03-11 12:16:05.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:59.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.367293 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    53179 2023-03-11 12:26:46.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:26:46.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:46.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:46.000000 types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:37.866152 types-aiobotocore-iot-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:37.000000 types-aiobotocore-iot-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    55298 2023-06-28 01:43:37.866152 types-aiobotocore-iot-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    53749 2023-06-28 01:32:37.000000 types-aiobotocore-iot-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:37.866152 types-aiobotocore-iot-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:32:37.000000 types-aiobotocore-iot-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:37.858152 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/
+-rw-r--r--   0 runner    (1001) docker     (123)    14185 2023-06-28 01:32:37.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14184 2023-06-28 01:32:37.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:32:37.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)   190083 2023-06-28 01:32:39.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)   189765 2023-06-28 01:32:39.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    24962 2023-06-28 01:32:40.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24960 2023-06-28 01:32:40.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    71939 2023-06-28 01:32:40.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    71878 2023-06-28 01:32:39.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:37.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   257109 2023-06-28 01:32:47.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   256782 2023-06-28 01:32:44.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:37.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:37.866152 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    55298 2023-06-28 01:43:37.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:43:37.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:37.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:37.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:37.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:37.000000 types-aiobotocore-iot-2.5.1/types_aiobotocore_iot.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/LICENSE` & `types-aiobotocore-iot-2.5.1/LICENSE`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 MIT License
 
-Copyright (c) 2022 Vlad Emelianov
+Copyright (c) 2023 Vlad Emelianov
 
 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iot-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iot
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoT 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoT 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iot"></a>
 
 # types-aiobotocore-iot
 
 [![PyPI - types-aiobotocore-iot](https://img.shields.io/pypi/v/types-aiobotocore-iot.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoT 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT)
+[aiobotocore.IoT 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT)
 service compatible with [VSCode](https://code.visualstudio.com/),
 [PyCharm](https://www.jetbrains.com/pycharm/),
 [Emacs](https://www.gnu.org/software/emacs/),
 [Sublime Text](https://www.sublimetext.com/),
 [mypy](https://github.com/python/mypy),
 [pyright](https://github.com/microsoft/pyright) and other tools.
 
 Generated by
-[mypy-boto3-builder 7.13.0](https://github.com/youtype/mypy_boto3_builder).
+[mypy-boto3-builder 7.14.5](https://github.com/youtype/mypy_boto3_builder).
 
 More information can be found on
 [types-aiobotocore](https://pypi.org/project/types-aiobotocore/) page and in
 [types-aiobotocore-iot docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/).
 
 See how it helps to find and fix potential bugs:
 
@@ -295,24 +295,28 @@
     ListDomainConfigurationsPaginator,
     ListFleetMetricsPaginator,
     ListIndicesPaginator,
     ListJobExecutionsForJobPaginator,
     ListJobExecutionsForThingPaginator,
     ListJobTemplatesPaginator,
     ListJobsPaginator,
+    ListManagedJobTemplatesPaginator,
     ListMetricValuesPaginator,
     ListMitigationActionsPaginator,
     ListOTAUpdatesPaginator,
     ListOutgoingCertificatesPaginator,
+    ListPackageVersionsPaginator,
+    ListPackagesPaginator,
     ListPoliciesPaginator,
     ListPolicyPrincipalsPaginator,
     ListPrincipalPoliciesPaginator,
     ListPrincipalThingsPaginator,
     ListProvisioningTemplateVersionsPaginator,
     ListProvisioningTemplatesPaginator,
+    ListRelatedResourcesForAuditFindingPaginator,
     ListRoleAliasesPaginator,
     ListScheduledAuditsPaginator,
     ListSecurityProfilesPaginator,
     ListSecurityProfilesForTargetPaginator,
     ListStreamsPaginator,
     ListTagsForResourcePaginator,
     ListTargetsForPolicyPaginator,
@@ -396,24 +400,31 @@
     list_job_executions_for_thing_paginator: ListJobExecutionsForThingPaginator = (
         client.get_paginator("list_job_executions_for_thing")
     )
     list_job_templates_paginator: ListJobTemplatesPaginator = client.get_paginator(
         "list_job_templates"
     )
     list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
+    list_managed_job_templates_paginator: ListManagedJobTemplatesPaginator = client.get_paginator(
+        "list_managed_job_templates"
+    )
     list_metric_values_paginator: ListMetricValuesPaginator = client.get_paginator(
         "list_metric_values"
     )
     list_mitigation_actions_paginator: ListMitigationActionsPaginator = client.get_paginator(
         "list_mitigation_actions"
     )
     list_ota_updates_paginator: ListOTAUpdatesPaginator = client.get_paginator("list_ota_updates")
     list_outgoing_certificates_paginator: ListOutgoingCertificatesPaginator = client.get_paginator(
         "list_outgoing_certificates"
     )
+    list_package_versions_paginator: ListPackageVersionsPaginator = client.get_paginator(
+        "list_package_versions"
+    )
+    list_packages_paginator: ListPackagesPaginator = client.get_paginator("list_packages")
     list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
     list_policy_principals_paginator: ListPolicyPrincipalsPaginator = client.get_paginator(
         "list_policy_principals"
     )
     list_principal_policies_paginator: ListPrincipalPoliciesPaginator = client.get_paginator(
         "list_principal_policies"
     )
@@ -422,14 +433,17 @@
     )
     list_provisioning_template_versions_paginator: ListProvisioningTemplateVersionsPaginator = (
         client.get_paginator("list_provisioning_template_versions")
     )
     list_provisioning_templates_paginator: ListProvisioningTemplatesPaginator = (
         client.get_paginator("list_provisioning_templates")
     )
+    list_related_resources_for_audit_finding_paginator: ListRelatedResourcesForAuditFindingPaginator = client.get_paginator(
+        "list_related_resources_for_audit_finding"
+    )
     list_role_aliases_paginator: ListRoleAliasesPaginator = client.get_paginator(
         "list_role_aliases"
     )
     list_scheduled_audits_paginator: ListScheduledAuditsPaginator = client.get_paginator(
         "list_scheduled_audits"
     )
     list_security_profiles_paginator: ListSecurityProfilesPaginator = client.get_paginator(
@@ -557,24 +571,28 @@
     ListDomainConfigurationsPaginatorName,
     ListFleetMetricsPaginatorName,
     ListIndicesPaginatorName,
     ListJobExecutionsForJobPaginatorName,
     ListJobExecutionsForThingPaginatorName,
     ListJobTemplatesPaginatorName,
     ListJobsPaginatorName,
+    ListManagedJobTemplatesPaginatorName,
     ListMetricValuesPaginatorName,
     ListMitigationActionsPaginatorName,
     ListOTAUpdatesPaginatorName,
     ListOutgoingCertificatesPaginatorName,
+    ListPackageVersionsPaginatorName,
+    ListPackagesPaginatorName,
     ListPoliciesPaginatorName,
     ListPolicyPrincipalsPaginatorName,
     ListPrincipalPoliciesPaginatorName,
     ListPrincipalThingsPaginatorName,
     ListProvisioningTemplateVersionsPaginatorName,
     ListProvisioningTemplatesPaginatorName,
+    ListRelatedResourcesForAuditFindingPaginatorName,
     ListRoleAliasesPaginatorName,
     ListScheduledAuditsPaginatorName,
     ListSecurityProfilesForTargetPaginatorName,
     ListSecurityProfilesPaginatorName,
     ListStreamsPaginatorName,
     ListTagsForResourcePaginatorName,
     ListTargetsForPolicyPaginatorName,
@@ -595,14 +613,16 @@
     LogLevelType,
     LogTargetTypeType,
     MessageFormatType,
     MitigationActionTypeType,
     ModelStatusType,
     NamedShadowIndexingModeType,
     OTAUpdateStatusType,
+    PackageVersionActionType,
+    PackageVersionStatusType,
     PolicyTemplateNameType,
     ProtocolType,
     ReportTypeType,
     ResourceTypeType,
     RetryableFailureTypeType,
     ServerCertificateStatusType,
     ServiceTypeType,
@@ -662,15 +682,15 @@
     AddThingsToThingGroupParamsTypeDef,
     AggregationTypeTypeDef,
     AlertTargetTypeDef,
     PolicyTypeDef,
     AssetPropertyTimestampTypeDef,
     AssetPropertyVariantTypeDef,
     AssociateTargetsWithJobRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateTargetsWithJobResponseTypeDef,
     AttachPolicyRequestRequestTypeDef,
     AttachPrincipalPolicyRequestRequestTypeDef,
     AttachSecurityProfileRequestRequestTypeDef,
     AttachThingPrincipalRequestRequestTypeDef,
     AttributePayloadTypeDef,
     AuditCheckConfigurationTypeDef,
     AuditCheckDetailsTypeDef,
@@ -699,32 +719,61 @@
     CACertificateTypeDef,
     CancelAuditMitigationActionsTaskRequestRequestTypeDef,
     CancelAuditTaskRequestRequestTypeDef,
     CancelCertificateTransferRequestRequestTypeDef,
     CancelDetectMitigationActionsTaskRequestRequestTypeDef,
     CancelJobExecutionRequestRequestTypeDef,
     CancelJobRequestRequestTypeDef,
+    CancelJobResponseTypeDef,
     TransferDataTypeDef,
     CertificateTypeDef,
     CodeSigningCertificateChainTypeDef,
     CodeSigningSignatureTypeDef,
     ConfigurationTypeDef,
     ConfirmTopicRuleDestinationRequestRequestTypeDef,
     TagTypeDef,
+    CreateAuthorizerResponseTypeDef,
+    CreateBillingGroupResponseTypeDef,
     CreateCertificateFromCsrRequestRequestTypeDef,
+    CreateCertificateFromCsrResponseTypeDef,
+    CreateCustomMetricResponseTypeDef,
+    CreateDimensionResponseTypeDef,
+    TlsConfigTypeDef,
+    CreateDomainConfigurationResponseTypeDef,
+    CreateDynamicThingGroupResponseTypeDef,
+    CreateFleetMetricResponseTypeDef,
     PresignedUrlConfigTypeDef,
-    SchedulingConfigTypeDef,
     TimeoutConfigTypeDef,
+    CreateJobResponseTypeDef,
+    MaintenanceWindowTypeDef,
+    CreateJobTemplateResponseTypeDef,
     CreateKeysAndCertificateRequestRequestTypeDef,
     KeyPairTypeDef,
+    CreateMitigationActionResponseTypeDef,
+    CreateOTAUpdateResponseTypeDef,
+    CreatePackageRequestRequestTypeDef,
+    CreatePackageResponseTypeDef,
+    CreatePackageVersionRequestRequestTypeDef,
+    CreatePackageVersionResponseTypeDef,
+    CreatePolicyResponseTypeDef,
     CreatePolicyVersionRequestRequestTypeDef,
+    CreatePolicyVersionResponseTypeDef,
     CreateProvisioningClaimRequestRequestTypeDef,
     ProvisioningHookTypeDef,
+    CreateProvisioningTemplateResponseTypeDef,
     CreateProvisioningTemplateVersionRequestRequestTypeDef,
+    CreateProvisioningTemplateVersionResponseTypeDef,
+    CreateRoleAliasResponseTypeDef,
+    CreateScheduledAuditResponseTypeDef,
+    CreateSecurityProfileResponseTypeDef,
+    CreateStreamResponseTypeDef,
+    CreateThingGroupResponseTypeDef,
+    CreateThingResponseTypeDef,
     ThingTypePropertiesTypeDef,
+    CreateThingTypeResponseTypeDef,
     DeleteAccountAuditConfigurationRequestRequestTypeDef,
     DeleteAuthorizerRequestRequestTypeDef,
     DeleteBillingGroupRequestRequestTypeDef,
     DeleteCACertificateRequestRequestTypeDef,
     DeleteCertificateRequestRequestTypeDef,
     DeleteCustomMetricRequestRequestTypeDef,
     DeleteDimensionRequestRequestTypeDef,
@@ -732,14 +781,16 @@
     DeleteDynamicThingGroupRequestRequestTypeDef,
     DeleteFleetMetricRequestRequestTypeDef,
     DeleteJobExecutionRequestRequestTypeDef,
     DeleteJobRequestRequestTypeDef,
     DeleteJobTemplateRequestRequestTypeDef,
     DeleteMitigationActionRequestRequestTypeDef,
     DeleteOTAUpdateRequestRequestTypeDef,
+    DeletePackageRequestRequestTypeDef,
+    DeletePackageVersionRequestRequestTypeDef,
     DeletePolicyRequestRequestTypeDef,
     DeletePolicyVersionRequestRequestTypeDef,
     DeleteProvisioningTemplateRequestRequestTypeDef,
     DeleteProvisioningTemplateVersionRequestRequestTypeDef,
     DeleteRoleAliasRequestRequestTypeDef,
     DeleteScheduledAuditRequestRequestTypeDef,
     DeleteSecurityProfileRequestRequestTypeDef,
@@ -758,37 +809,45 @@
     TaskStatisticsTypeDef,
     DescribeAuthorizerRequestRequestTypeDef,
     DescribeBillingGroupRequestRequestTypeDef,
     DescribeCACertificateRequestRequestTypeDef,
     RegistrationConfigTypeDef,
     DescribeCertificateRequestRequestTypeDef,
     DescribeCustomMetricRequestRequestTypeDef,
+    DescribeCustomMetricResponseTypeDef,
     DescribeDetectMitigationActionsTaskRequestRequestTypeDef,
     DescribeDimensionRequestRequestTypeDef,
+    DescribeDimensionResponseTypeDef,
     DescribeDomainConfigurationRequestRequestTypeDef,
     ServerCertificateSummaryTypeDef,
     DescribeEndpointRequestRequestTypeDef,
+    DescribeEndpointResponseTypeDef,
     DescribeFleetMetricRequestRequestTypeDef,
     DescribeIndexRequestRequestTypeDef,
+    DescribeIndexResponseTypeDef,
     DescribeJobExecutionRequestRequestTypeDef,
     DescribeJobRequestRequestTypeDef,
     DescribeJobTemplateRequestRequestTypeDef,
     DescribeManagedJobTemplateRequestRequestTypeDef,
     DocumentParameterTypeDef,
     DescribeMitigationActionRequestRequestTypeDef,
     DescribeProvisioningTemplateRequestRequestTypeDef,
     DescribeProvisioningTemplateVersionRequestRequestTypeDef,
+    DescribeProvisioningTemplateVersionResponseTypeDef,
     DescribeRoleAliasRequestRequestTypeDef,
     RoleAliasDescriptionTypeDef,
     DescribeScheduledAuditRequestRequestTypeDef,
+    DescribeScheduledAuditResponseTypeDef,
     DescribeSecurityProfileRequestRequestTypeDef,
     DescribeStreamRequestRequestTypeDef,
     DescribeThingGroupRequestRequestTypeDef,
     DescribeThingRegistrationTaskRequestRequestTypeDef,
+    DescribeThingRegistrationTaskResponseTypeDef,
     DescribeThingRequestRequestTypeDef,
+    DescribeThingResponseTypeDef,
     DescribeThingTypeRequestRequestTypeDef,
     ThingTypeMetadataTypeDef,
     S3DestinationTypeDef,
     DetachPolicyRequestRequestTypeDef,
     DetachPrincipalPolicyRequestRequestTypeDef,
     DetachSecurityProfileRequestRequestTypeDef,
     DetachThingPrincipalRequestRequestTypeDef,
@@ -796,36 +855,49 @@
     DetectMitigationActionsTaskStatisticsTypeDef,
     DetectMitigationActionsTaskTargetTypeDef,
     ViolationEventOccurrenceRangeTypeDef,
     DisableTopicRuleRequestRequestTypeDef,
     DomainConfigurationSummaryTypeDef,
     PutItemInputTypeDef,
     EffectivePolicyTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableIoTLoggingParamsTypeDef,
     EnableTopicRuleRequestRequestTypeDef,
     ErrorInfoTypeDef,
     RateIncreaseCriteriaTypeDef,
     FieldTypeDef,
     S3LocationTypeDef,
     StreamTypeDef,
     FleetMetricNameAndArnTypeDef,
-    PaginatorConfigTypeDef,
+    GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef,
     GetBehaviorModelTrainingSummariesRequestRequestTypeDef,
     GetCardinalityRequestRequestTypeDef,
+    GetCardinalityResponseTypeDef,
     GetEffectivePoliciesRequestRequestTypeDef,
     GetJobDocumentRequestRequestTypeDef,
+    GetJobDocumentResponseTypeDef,
+    GetLoggingOptionsResponseTypeDef,
     GetOTAUpdateRequestRequestTypeDef,
+    VersionUpdateByJobsConfigTypeDef,
+    GetPackageRequestRequestTypeDef,
+    GetPackageResponseTypeDef,
+    GetPackageVersionRequestRequestTypeDef,
+    GetPackageVersionResponseTypeDef,
     GetPercentilesRequestRequestTypeDef,
     PercentPairTypeDef,
     GetPolicyRequestRequestTypeDef,
+    GetPolicyResponseTypeDef,
     GetPolicyVersionRequestRequestTypeDef,
+    GetPolicyVersionResponseTypeDef,
+    GetRegistrationCodeResponseTypeDef,
     GetStatisticsRequestRequestTypeDef,
     StatisticsTypeDef,
     GetTopicRuleDestinationRequestRequestTypeDef,
     GetTopicRuleRequestRequestTypeDef,
+    GetV2LoggingOptionsResponseTypeDef,
     GroupNameAndArnTypeDef,
     HttpActionHeaderTypeDef,
     SigV4AuthorizationTypeDef,
     HttpContextTypeDef,
     HttpUrlDestinationConfigurationTypeDef,
     HttpUrlDestinationPropertiesTypeDef,
     HttpUrlDestinationSummaryTypeDef,
@@ -833,223 +905,246 @@
     IssuerCertificateIdentifierTypeDef,
     JobExecutionStatusDetailsTypeDef,
     JobExecutionSummaryTypeDef,
     RetryCriteriaTypeDef,
     JobProcessDetailsTypeDef,
     JobSummaryTypeDef,
     JobTemplateSummaryTypeDef,
+    ScheduledJobRolloutTypeDef,
+    ListActiveViolationsRequestListActiveViolationsPaginateTypeDef,
     ListActiveViolationsRequestRequestTypeDef,
+    ListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef,
     ListAttachedPoliciesRequestRequestTypeDef,
+    ListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef,
     ListAuditMitigationActionsExecutionsRequestRequestTypeDef,
+    ListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef,
     ListAuditMitigationActionsTasksRequestRequestTypeDef,
+    ListAuditTasksRequestListAuditTasksPaginateTypeDef,
     ListAuditTasksRequestRequestTypeDef,
+    ListAuthorizersRequestListAuthorizersPaginateTypeDef,
     ListAuthorizersRequestRequestTypeDef,
+    ListBillingGroupsRequestListBillingGroupsPaginateTypeDef,
     ListBillingGroupsRequestRequestTypeDef,
+    ListCACertificatesRequestListCACertificatesPaginateTypeDef,
     ListCACertificatesRequestRequestTypeDef,
+    ListCertificatesByCARequestListCertificatesByCAPaginateTypeDef,
     ListCertificatesByCARequestRequestTypeDef,
+    ListCertificatesRequestListCertificatesPaginateTypeDef,
     ListCertificatesRequestRequestTypeDef,
+    ListCustomMetricsRequestListCustomMetricsPaginateTypeDef,
     ListCustomMetricsRequestRequestTypeDef,
+    ListCustomMetricsResponseTypeDef,
+    ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef,
     ListDetectMitigationActionsExecutionsRequestRequestTypeDef,
+    ListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef,
     ListDetectMitigationActionsTasksRequestRequestTypeDef,
+    ListDimensionsRequestListDimensionsPaginateTypeDef,
     ListDimensionsRequestRequestTypeDef,
+    ListDimensionsResponseTypeDef,
+    ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef,
     ListDomainConfigurationsRequestRequestTypeDef,
+    ListFleetMetricsRequestListFleetMetricsPaginateTypeDef,
     ListFleetMetricsRequestRequestTypeDef,
+    ListIndicesRequestListIndicesPaginateTypeDef,
     ListIndicesRequestRequestTypeDef,
+    ListIndicesResponseTypeDef,
+    ListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef,
     ListJobExecutionsForJobRequestRequestTypeDef,
+    ListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef,
     ListJobExecutionsForThingRequestRequestTypeDef,
+    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
     ListJobTemplatesRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListManagedJobTemplatesRequestListManagedJobTemplatesPaginateTypeDef,
     ListManagedJobTemplatesRequestRequestTypeDef,
     ManagedJobTemplateSummaryTypeDef,
+    ListMetricValuesRequestListMetricValuesPaginateTypeDef,
     ListMetricValuesRequestRequestTypeDef,
+    ListMitigationActionsRequestListMitigationActionsPaginateTypeDef,
     ListMitigationActionsRequestRequestTypeDef,
     MitigationActionIdentifierTypeDef,
+    ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef,
     ListOTAUpdatesRequestRequestTypeDef,
     OTAUpdateSummaryTypeDef,
+    ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef,
     ListOutgoingCertificatesRequestRequestTypeDef,
     OutgoingCertificateTypeDef,
+    ListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
+    ListPackageVersionsRequestRequestTypeDef,
+    PackageVersionSummaryTypeDef,
+    ListPackagesRequestListPackagesPaginateTypeDef,
+    ListPackagesRequestRequestTypeDef,
+    PackageSummaryTypeDef,
+    ListPoliciesRequestListPoliciesPaginateTypeDef,
     ListPoliciesRequestRequestTypeDef,
+    ListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef,
     ListPolicyPrincipalsRequestRequestTypeDef,
+    ListPolicyPrincipalsResponseTypeDef,
     ListPolicyVersionsRequestRequestTypeDef,
     PolicyVersionTypeDef,
+    ListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef,
     ListPrincipalPoliciesRequestRequestTypeDef,
+    ListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef,
     ListPrincipalThingsRequestRequestTypeDef,
+    ListPrincipalThingsResponseTypeDef,
+    ListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef,
     ListProvisioningTemplateVersionsRequestRequestTypeDef,
     ProvisioningTemplateVersionSummaryTypeDef,
+    ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef,
     ListProvisioningTemplatesRequestRequestTypeDef,
     ProvisioningTemplateSummaryTypeDef,
+    ListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef,
     ListRelatedResourcesForAuditFindingRequestRequestTypeDef,
+    ListRoleAliasesRequestListRoleAliasesPaginateTypeDef,
     ListRoleAliasesRequestRequestTypeDef,
+    ListRoleAliasesResponseTypeDef,
+    ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef,
     ListScheduledAuditsRequestRequestTypeDef,
     ScheduledAuditMetadataTypeDef,
+    ListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef,
     ListSecurityProfilesForTargetRequestRequestTypeDef,
+    ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef,
     ListSecurityProfilesRequestRequestTypeDef,
     SecurityProfileIdentifierTypeDef,
+    ListStreamsRequestListStreamsPaginateTypeDef,
     ListStreamsRequestRequestTypeDef,
     StreamSummaryTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
     ListTargetsForPolicyRequestRequestTypeDef,
+    ListTargetsForPolicyResponseTypeDef,
+    ListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef,
     ListTargetsForSecurityProfileRequestRequestTypeDef,
     SecurityProfileTargetTypeDef,
+    ListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef,
     ListThingGroupsForThingRequestRequestTypeDef,
+    ListThingGroupsRequestListThingGroupsPaginateTypeDef,
     ListThingGroupsRequestRequestTypeDef,
+    ListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef,
     ListThingPrincipalsRequestRequestTypeDef,
+    ListThingPrincipalsResponseTypeDef,
+    ListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef,
     ListThingRegistrationTaskReportsRequestRequestTypeDef,
+    ListThingRegistrationTaskReportsResponseTypeDef,
+    ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef,
     ListThingRegistrationTasksRequestRequestTypeDef,
+    ListThingRegistrationTasksResponseTypeDef,
+    ListThingTypesRequestListThingTypesPaginateTypeDef,
     ListThingTypesRequestRequestTypeDef,
+    ListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef,
     ListThingsInBillingGroupRequestRequestTypeDef,
+    ListThingsInBillingGroupResponseTypeDef,
+    ListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef,
     ListThingsInThingGroupRequestRequestTypeDef,
+    ListThingsInThingGroupResponseTypeDef,
+    ListThingsRequestListThingsPaginateTypeDef,
     ListThingsRequestRequestTypeDef,
     ThingAttributeTypeDef,
+    ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef,
     ListTopicRuleDestinationsRequestRequestTypeDef,
+    ListTopicRulesRequestListTopicRulesPaginateTypeDef,
     ListTopicRulesRequestRequestTypeDef,
     TopicRuleListItemTypeDef,
+    ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef,
     ListV2LoggingLevelsRequestRequestTypeDef,
+    ListViolationEventsRequestListViolationEventsPaginateTypeDef,
     ListViolationEventsRequestRequestTypeDef,
     LocationTimestampTypeDef,
     LogTargetTypeDef,
     LoggingOptionsPayloadTypeDef,
     PublishFindingToSnsParamsTypeDef,
     ReplaceDefaultPolicyVersionParamsTypeDef,
     UpdateCACertificateParamsTypeDef,
     UpdateDeviceCertificateParamsTypeDef,
     MqttContextTypeDef,
     UserPropertyTypeDef,
+    PaginatorConfigTypeDef,
     PolicyVersionIdentifierTypeDef,
     PutVerificationStateOnViolationRequestRequestTypeDef,
+    RegisterCACertificateResponseTypeDef,
     RegisterCertificateRequestRequestTypeDef,
+    RegisterCertificateResponseTypeDef,
     RegisterCertificateWithoutCARequestRequestTypeDef,
+    RegisterCertificateWithoutCAResponseTypeDef,
     RegisterThingRequestRequestTypeDef,
+    RegisterThingResponseTypeDef,
     RejectCertificateTransferRequestRequestTypeDef,
     RemoveThingFromBillingGroupRequestRequestTypeDef,
     RemoveThingFromThingGroupRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SearchIndexRequestRequestTypeDef,
     ThingGroupDocumentTypeDef,
     SetDefaultAuthorizerRequestRequestTypeDef,
+    SetDefaultAuthorizerResponseTypeDef,
     SetDefaultPolicyVersionRequestRequestTypeDef,
     SetV2LoggingOptionsRequestRequestTypeDef,
     SigningProfileParameterTypeDef,
+    StartAuditMitigationActionsTaskResponseTypeDef,
+    StartDetectMitigationActionsTaskResponseTypeDef,
     StartOnDemandAuditTaskRequestRequestTypeDef,
+    StartOnDemandAuditTaskResponseTypeDef,
     StartThingRegistrationTaskRequestRequestTypeDef,
+    StartThingRegistrationTaskResponseTypeDef,
     StopThingRegistrationTaskRequestRequestTypeDef,
     TlsContextTypeDef,
+    TestInvokeAuthorizerResponseTypeDef,
     ThingConnectivityTypeDef,
     TimestreamDimensionTypeDef,
     TimestreamTimestampTypeDef,
     VpcDestinationConfigurationTypeDef,
     VpcDestinationSummaryTypeDef,
     VpcDestinationPropertiesTypeDef,
     TransferCertificateRequestRequestTypeDef,
+    TransferCertificateResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAuthorizerRequestRequestTypeDef,
+    UpdateAuthorizerResponseTypeDef,
+    UpdateBillingGroupResponseTypeDef,
     UpdateCertificateRequestRequestTypeDef,
     UpdateCustomMetricRequestRequestTypeDef,
+    UpdateCustomMetricResponseTypeDef,
     UpdateDimensionRequestRequestTypeDef,
+    UpdateDimensionResponseTypeDef,
+    UpdateDomainConfigurationResponseTypeDef,
+    UpdateDynamicThingGroupResponseTypeDef,
+    UpdateMitigationActionResponseTypeDef,
+    UpdatePackageRequestRequestTypeDef,
+    UpdatePackageVersionRequestRequestTypeDef,
     UpdateRoleAliasRequestRequestTypeDef,
+    UpdateRoleAliasResponseTypeDef,
     UpdateScheduledAuditRequestRequestTypeDef,
+    UpdateScheduledAuditResponseTypeDef,
+    UpdateStreamResponseTypeDef,
+    UpdateThingGroupResponseTypeDef,
     UpdateThingGroupsForThingRequestRequestTypeDef,
     UpdateTopicRuleDestinationRequestRequestTypeDef,
     ValidationErrorTypeDef,
     AbortConfigTypeDef,
     MetricDatumTypeDef,
+    DescribeFleetMetricResponseTypeDef,
     UpdateFleetMetricRequestRequestTypeDef,
     AllowedTypeDef,
     ExplicitDenyTypeDef,
     ImplicitDenyTypeDef,
-    AssetPropertyValueTypeDef,
-    AssociateTargetsWithJobResponseTypeDef,
-    CancelJobResponseTypeDef,
-    CreateAuthorizerResponseTypeDef,
-    CreateBillingGroupResponseTypeDef,
-    CreateCertificateFromCsrResponseTypeDef,
-    CreateCustomMetricResponseTypeDef,
-    CreateDimensionResponseTypeDef,
-    CreateDomainConfigurationResponseTypeDef,
-    CreateDynamicThingGroupResponseTypeDef,
-    CreateFleetMetricResponseTypeDef,
-    CreateJobResponseTypeDef,
-    CreateJobTemplateResponseTypeDef,
-    CreateMitigationActionResponseTypeDef,
-    CreateOTAUpdateResponseTypeDef,
-    CreatePolicyResponseTypeDef,
-    CreatePolicyVersionResponseTypeDef,
-    CreateProvisioningTemplateResponseTypeDef,
-    CreateProvisioningTemplateVersionResponseTypeDef,
-    CreateRoleAliasResponseTypeDef,
-    CreateScheduledAuditResponseTypeDef,
-    CreateSecurityProfileResponseTypeDef,
-    CreateStreamResponseTypeDef,
-    CreateThingGroupResponseTypeDef,
-    CreateThingResponseTypeDef,
-    CreateThingTypeResponseTypeDef,
-    DescribeCustomMetricResponseTypeDef,
-    DescribeDimensionResponseTypeDef,
-    DescribeEndpointResponseTypeDef,
-    DescribeFleetMetricResponseTypeDef,
-    DescribeIndexResponseTypeDef,
-    DescribeProvisioningTemplateVersionResponseTypeDef,
-    DescribeScheduledAuditResponseTypeDef,
-    DescribeThingRegistrationTaskResponseTypeDef,
-    DescribeThingResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCardinalityResponseTypeDef,
-    GetJobDocumentResponseTypeDef,
-    GetLoggingOptionsResponseTypeDef,
-    GetPolicyResponseTypeDef,
-    GetPolicyVersionResponseTypeDef,
-    GetRegistrationCodeResponseTypeDef,
-    GetV2LoggingOptionsResponseTypeDef,
     ListAttachedPoliciesResponseTypeDef,
-    ListCustomMetricsResponseTypeDef,
-    ListDimensionsResponseTypeDef,
-    ListIndicesResponseTypeDef,
     ListPoliciesResponseTypeDef,
-    ListPolicyPrincipalsResponseTypeDef,
     ListPrincipalPoliciesResponseTypeDef,
-    ListPrincipalThingsResponseTypeDef,
-    ListRoleAliasesResponseTypeDef,
-    ListTargetsForPolicyResponseTypeDef,
-    ListThingPrincipalsResponseTypeDef,
-    ListThingRegistrationTaskReportsResponseTypeDef,
-    ListThingRegistrationTasksResponseTypeDef,
-    ListThingsInBillingGroupResponseTypeDef,
-    ListThingsInThingGroupResponseTypeDef,
-    RegisterCACertificateResponseTypeDef,
-    RegisterCertificateResponseTypeDef,
-    RegisterCertificateWithoutCAResponseTypeDef,
-    RegisterThingResponseTypeDef,
-    SetDefaultAuthorizerResponseTypeDef,
-    StartAuditMitigationActionsTaskResponseTypeDef,
-    StartDetectMitigationActionsTaskResponseTypeDef,
-    StartOnDemandAuditTaskResponseTypeDef,
-    StartThingRegistrationTaskResponseTypeDef,
-    TestInvokeAuthorizerResponseTypeDef,
-    TransferCertificateResponseTypeDef,
-    UpdateAuthorizerResponseTypeDef,
-    UpdateBillingGroupResponseTypeDef,
-    UpdateCustomMetricResponseTypeDef,
-    UpdateDimensionResponseTypeDef,
-    UpdateDomainConfigurationResponseTypeDef,
-    UpdateDynamicThingGroupResponseTypeDef,
-    UpdateMitigationActionResponseTypeDef,
-    UpdateRoleAliasResponseTypeDef,
-    UpdateScheduledAuditResponseTypeDef,
-    UpdateStreamResponseTypeDef,
-    UpdateThingGroupResponseTypeDef,
+    AssetPropertyValueTypeDef,
     CreateThingRequestRequestTypeDef,
     ThingGroupPropertiesTypeDef,
     UpdateThingRequestRequestTypeDef,
     ListAuditMitigationActionsExecutionsResponseTypeDef,
     ListAuditMitigationActionsTasksResponseTypeDef,
     StartAuditMitigationActionsTaskRequestRequestTypeDef,
     DescribeAccountAuditConfigurationResponseTypeDef,
     UpdateAccountAuditConfigurationRequestRequestTypeDef,
     ListAuditTasksResponseTypeDef,
     TestAuthorizationRequestRequestTypeDef,
-    UpdateDomainConfigurationRequestRequestTypeDef,
     DescribeAuthorizerResponseTypeDef,
     DescribeDefaultAuthorizerResponseTypeDef,
     ListAuthorizersResponseTypeDef,
     AwsJobAbortConfigTypeDef,
     AwsJobExponentialRolloutRateTypeDef,
     BehaviorCriteriaTypeDef,
     GetBehaviorModelTrainingSummariesResponseTypeDef,
@@ -1066,21 +1161,23 @@
     CustomCodeSigningTypeDef,
     DescribeEventConfigurationsResponseTypeDef,
     UpdateEventConfigurationsRequestRequestTypeDef,
     CreateAuthorizerRequestRequestTypeDef,
     CreateBillingGroupRequestRequestTypeDef,
     CreateCustomMetricRequestRequestTypeDef,
     CreateDimensionRequestRequestTypeDef,
-    CreateDomainConfigurationRequestRequestTypeDef,
     CreateFleetMetricRequestRequestTypeDef,
     CreatePolicyRequestRequestTypeDef,
     CreateRoleAliasRequestRequestTypeDef,
     CreateScheduledAuditRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    CreateDomainConfigurationRequestRequestTypeDef,
+    UpdateDomainConfigurationRequestRequestTypeDef,
+    SchedulingConfigTypeDef,
     CreateKeysAndCertificateResponseTypeDef,
     CreateProvisioningClaimResponseTypeDef,
     CreateProvisioningTemplateRequestRequestTypeDef,
     DescribeProvisioningTemplateResponseTypeDef,
     UpdateProvisioningTemplateRequestRequestTypeDef,
     CreateThingTypeRequestRequestTypeDef,
     DescribeAuditTaskResponseTypeDef,
@@ -1098,67 +1195,16 @@
     DynamoDBv2ActionTypeDef,
     GetEffectivePoliciesResponseTypeDef,
     ExponentialRolloutRateTypeDef,
     ThingGroupIndexingConfigurationTypeDef,
     StreamFileTypeDef,
     FileLocationTypeDef,
     ListFleetMetricsResponseTypeDef,
-    GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef,
-    ListActiveViolationsRequestListActiveViolationsPaginateTypeDef,
-    ListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef,
-    ListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef,
-    ListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef,
-    ListAuditTasksRequestListAuditTasksPaginateTypeDef,
-    ListAuthorizersRequestListAuthorizersPaginateTypeDef,
-    ListBillingGroupsRequestListBillingGroupsPaginateTypeDef,
-    ListCACertificatesRequestListCACertificatesPaginateTypeDef,
-    ListCertificatesByCARequestListCertificatesByCAPaginateTypeDef,
-    ListCertificatesRequestListCertificatesPaginateTypeDef,
-    ListCustomMetricsRequestListCustomMetricsPaginateTypeDef,
-    ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef,
-    ListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef,
-    ListDimensionsRequestListDimensionsPaginateTypeDef,
-    ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef,
-    ListFleetMetricsRequestListFleetMetricsPaginateTypeDef,
-    ListIndicesRequestListIndicesPaginateTypeDef,
-    ListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef,
-    ListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef,
-    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListMetricValuesRequestListMetricValuesPaginateTypeDef,
-    ListMitigationActionsRequestListMitigationActionsPaginateTypeDef,
-    ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef,
-    ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef,
-    ListPoliciesRequestListPoliciesPaginateTypeDef,
-    ListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef,
-    ListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef,
-    ListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef,
-    ListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef,
-    ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef,
-    ListRoleAliasesRequestListRoleAliasesPaginateTypeDef,
-    ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef,
-    ListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef,
-    ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef,
-    ListStreamsRequestListStreamsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
-    ListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef,
-    ListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef,
-    ListThingGroupsRequestListThingGroupsPaginateTypeDef,
-    ListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef,
-    ListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef,
-    ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef,
-    ListThingTypesRequestListThingTypesPaginateTypeDef,
-    ListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef,
-    ListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef,
-    ListThingsRequestListThingsPaginateTypeDef,
-    ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef,
-    ListTopicRulesRequestListTopicRulesPaginateTypeDef,
-    ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef,
-    ListViolationEventsRequestListViolationEventsPaginateTypeDef,
+    GetPackageConfigurationResponseTypeDef,
+    UpdatePackageConfigurationRequestRequestTypeDef,
     GetPercentilesResponseTypeDef,
     GetStatisticsResponseTypeDef,
     ListBillingGroupsResponseTypeDef,
     ListThingGroupsForThingResponseTypeDef,
     ListThingGroupsResponseTypeDef,
     ThingGroupMetadataTypeDef,
     HttpAuthorizationTypeDef,
@@ -1169,14 +1215,16 @@
     JobExecutionsRetryConfigTypeDef,
     ListJobsResponseTypeDef,
     ListJobTemplatesResponseTypeDef,
     ListManagedJobTemplatesResponseTypeDef,
     ListMitigationActionsResponseTypeDef,
     ListOTAUpdatesResponseTypeDef,
     ListOutgoingCertificatesResponseTypeDef,
+    ListPackageVersionsResponseTypeDef,
+    ListPackagesResponseTypeDef,
     ListPolicyVersionsResponseTypeDef,
     ListProvisioningTemplateVersionsResponseTypeDef,
     ListProvisioningTemplatesResponseTypeDef,
     ListScheduledAuditsResponseTypeDef,
     ListSecurityProfilesResponseTypeDef,
     ListStreamsResponseTypeDef,
     ListTargetsForSecurityProfileResponseTypeDef,
@@ -1295,43 +1343,43 @@
 <a id="how-it-works"></a>
 
 ## How it works
 
 Fully automated
 [mypy-boto3-builder](https://github.com/youtype/mypy_boto3_builder) carefully
 generates type annotations for each service, patiently waiting for
-`aiobotocore` updates. It delivers a drop-in type annotations for you and makes
+`aiobotocore` updates. It delivers drop-in type annotations for you and makes
 sure that:
 
 - All available `aiobotocore` services are covered.
 - Each public class and method of every `aiobotocore` service gets valid type
-  annotations extracted from the documentation (blame `botocore` docs if types
-  are incorrect).
+  annotations extracted from `botocore` schemas.
 - Type annotations include up-to-date documentation.
 - Link to documentation is provided for every method.
 - Code is processed by [black](https://github.com/psf/black) and
   [isort](https://github.com/PyCQA/isort) for readability.
 
 <a id="what's-new"></a>
 
 ## What's new
 
 <a id="implemented-features"></a>
 
 ### Implemented features
 
-- Fully type annotated `boto3`, `botocore` and `aiobotocore` libraries
+- Fully type annotated `boto3`, `botocore`, `aiobotocore` and `aioboto3`
+  libraries
 - `mypy`, `pyright`, `VSCode`, `PyCharm`, `Sublime Text` and `Emacs`
   compatibility
 - `Client`, `ServiceResource`, `Resource`, `Waiter` `Paginator` type
   annotations for each service
 - Generated `TypeDefs` for each service
 - Generated `Literals` for each service
-- Auto discovery of types for `boto3.client` and `boto3.session` calls
-- Auto discovery of types for `session.client` and `session.session` calls
+- Auto discovery of types for `boto3.client` and `boto3.resource` calls
+- Auto discovery of types for `session.client` and `session.resource` calls
 - Auto discovery of types for `client.get_waiter` and `client.get_paginator`
   calls
 - Auto discovery of types for `ServiceResource` and `Resource` collections
 - Auto discovery of types for `aiobotocore.Session.create_client` calls
 
 <a id="latest-changes"></a>
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/README.md` & `types-aiobotocore-iot-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iot"></a>
 
 # types-aiobotocore-iot
 
 [![PyPI - types-aiobotocore-iot](https://img.shields.io/pypi/v/types-aiobotocore-iot.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoT 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT)
+[aiobotocore.IoT 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT)
 service compatible with [VSCode](https://code.visualstudio.com/),
 [PyCharm](https://www.jetbrains.com/pycharm/),
 [Emacs](https://www.gnu.org/software/emacs/),
 [Sublime Text](https://www.sublimetext.com/),
 [mypy](https://github.com/python/mypy),
 [pyright](https://github.com/microsoft/pyright) and other tools.
 
 Generated by
-[mypy-boto3-builder 7.13.0](https://github.com/youtype/mypy_boto3_builder).
+[mypy-boto3-builder 7.14.5](https://github.com/youtype/mypy_boto3_builder).
 
 More information can be found on
 [types-aiobotocore](https://pypi.org/project/types-aiobotocore/) page and in
 [types-aiobotocore-iot docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/).
 
 See how it helps to find and fix potential bugs:
 
@@ -262,24 +262,28 @@
     ListDomainConfigurationsPaginator,
     ListFleetMetricsPaginator,
     ListIndicesPaginator,
     ListJobExecutionsForJobPaginator,
     ListJobExecutionsForThingPaginator,
     ListJobTemplatesPaginator,
     ListJobsPaginator,
+    ListManagedJobTemplatesPaginator,
     ListMetricValuesPaginator,
     ListMitigationActionsPaginator,
     ListOTAUpdatesPaginator,
     ListOutgoingCertificatesPaginator,
+    ListPackageVersionsPaginator,
+    ListPackagesPaginator,
     ListPoliciesPaginator,
     ListPolicyPrincipalsPaginator,
     ListPrincipalPoliciesPaginator,
     ListPrincipalThingsPaginator,
     ListProvisioningTemplateVersionsPaginator,
     ListProvisioningTemplatesPaginator,
+    ListRelatedResourcesForAuditFindingPaginator,
     ListRoleAliasesPaginator,
     ListScheduledAuditsPaginator,
     ListSecurityProfilesPaginator,
     ListSecurityProfilesForTargetPaginator,
     ListStreamsPaginator,
     ListTagsForResourcePaginator,
     ListTargetsForPolicyPaginator,
@@ -363,24 +367,31 @@
     list_job_executions_for_thing_paginator: ListJobExecutionsForThingPaginator = (
         client.get_paginator("list_job_executions_for_thing")
     )
     list_job_templates_paginator: ListJobTemplatesPaginator = client.get_paginator(
         "list_job_templates"
     )
     list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
+    list_managed_job_templates_paginator: ListManagedJobTemplatesPaginator = client.get_paginator(
+        "list_managed_job_templates"
+    )
     list_metric_values_paginator: ListMetricValuesPaginator = client.get_paginator(
         "list_metric_values"
     )
     list_mitigation_actions_paginator: ListMitigationActionsPaginator = client.get_paginator(
         "list_mitigation_actions"
     )
     list_ota_updates_paginator: ListOTAUpdatesPaginator = client.get_paginator("list_ota_updates")
     list_outgoing_certificates_paginator: ListOutgoingCertificatesPaginator = client.get_paginator(
         "list_outgoing_certificates"
     )
+    list_package_versions_paginator: ListPackageVersionsPaginator = client.get_paginator(
+        "list_package_versions"
+    )
+    list_packages_paginator: ListPackagesPaginator = client.get_paginator("list_packages")
     list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
     list_policy_principals_paginator: ListPolicyPrincipalsPaginator = client.get_paginator(
         "list_policy_principals"
     )
     list_principal_policies_paginator: ListPrincipalPoliciesPaginator = client.get_paginator(
         "list_principal_policies"
     )
@@ -389,14 +400,17 @@
     )
     list_provisioning_template_versions_paginator: ListProvisioningTemplateVersionsPaginator = (
         client.get_paginator("list_provisioning_template_versions")
     )
     list_provisioning_templates_paginator: ListProvisioningTemplatesPaginator = (
         client.get_paginator("list_provisioning_templates")
     )
+    list_related_resources_for_audit_finding_paginator: ListRelatedResourcesForAuditFindingPaginator = client.get_paginator(
+        "list_related_resources_for_audit_finding"
+    )
     list_role_aliases_paginator: ListRoleAliasesPaginator = client.get_paginator(
         "list_role_aliases"
     )
     list_scheduled_audits_paginator: ListScheduledAuditsPaginator = client.get_paginator(
         "list_scheduled_audits"
     )
     list_security_profiles_paginator: ListSecurityProfilesPaginator = client.get_paginator(
@@ -524,24 +538,28 @@
     ListDomainConfigurationsPaginatorName,
     ListFleetMetricsPaginatorName,
     ListIndicesPaginatorName,
     ListJobExecutionsForJobPaginatorName,
     ListJobExecutionsForThingPaginatorName,
     ListJobTemplatesPaginatorName,
     ListJobsPaginatorName,
+    ListManagedJobTemplatesPaginatorName,
     ListMetricValuesPaginatorName,
     ListMitigationActionsPaginatorName,
     ListOTAUpdatesPaginatorName,
     ListOutgoingCertificatesPaginatorName,
+    ListPackageVersionsPaginatorName,
+    ListPackagesPaginatorName,
     ListPoliciesPaginatorName,
     ListPolicyPrincipalsPaginatorName,
     ListPrincipalPoliciesPaginatorName,
     ListPrincipalThingsPaginatorName,
     ListProvisioningTemplateVersionsPaginatorName,
     ListProvisioningTemplatesPaginatorName,
+    ListRelatedResourcesForAuditFindingPaginatorName,
     ListRoleAliasesPaginatorName,
     ListScheduledAuditsPaginatorName,
     ListSecurityProfilesForTargetPaginatorName,
     ListSecurityProfilesPaginatorName,
     ListStreamsPaginatorName,
     ListTagsForResourcePaginatorName,
     ListTargetsForPolicyPaginatorName,
@@ -562,14 +580,16 @@
     LogLevelType,
     LogTargetTypeType,
     MessageFormatType,
     MitigationActionTypeType,
     ModelStatusType,
     NamedShadowIndexingModeType,
     OTAUpdateStatusType,
+    PackageVersionActionType,
+    PackageVersionStatusType,
     PolicyTemplateNameType,
     ProtocolType,
     ReportTypeType,
     ResourceTypeType,
     RetryableFailureTypeType,
     ServerCertificateStatusType,
     ServiceTypeType,
@@ -629,15 +649,15 @@
     AddThingsToThingGroupParamsTypeDef,
     AggregationTypeTypeDef,
     AlertTargetTypeDef,
     PolicyTypeDef,
     AssetPropertyTimestampTypeDef,
     AssetPropertyVariantTypeDef,
     AssociateTargetsWithJobRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateTargetsWithJobResponseTypeDef,
     AttachPolicyRequestRequestTypeDef,
     AttachPrincipalPolicyRequestRequestTypeDef,
     AttachSecurityProfileRequestRequestTypeDef,
     AttachThingPrincipalRequestRequestTypeDef,
     AttributePayloadTypeDef,
     AuditCheckConfigurationTypeDef,
     AuditCheckDetailsTypeDef,
@@ -666,32 +686,61 @@
     CACertificateTypeDef,
     CancelAuditMitigationActionsTaskRequestRequestTypeDef,
     CancelAuditTaskRequestRequestTypeDef,
     CancelCertificateTransferRequestRequestTypeDef,
     CancelDetectMitigationActionsTaskRequestRequestTypeDef,
     CancelJobExecutionRequestRequestTypeDef,
     CancelJobRequestRequestTypeDef,
+    CancelJobResponseTypeDef,
     TransferDataTypeDef,
     CertificateTypeDef,
     CodeSigningCertificateChainTypeDef,
     CodeSigningSignatureTypeDef,
     ConfigurationTypeDef,
     ConfirmTopicRuleDestinationRequestRequestTypeDef,
     TagTypeDef,
+    CreateAuthorizerResponseTypeDef,
+    CreateBillingGroupResponseTypeDef,
     CreateCertificateFromCsrRequestRequestTypeDef,
+    CreateCertificateFromCsrResponseTypeDef,
+    CreateCustomMetricResponseTypeDef,
+    CreateDimensionResponseTypeDef,
+    TlsConfigTypeDef,
+    CreateDomainConfigurationResponseTypeDef,
+    CreateDynamicThingGroupResponseTypeDef,
+    CreateFleetMetricResponseTypeDef,
     PresignedUrlConfigTypeDef,
-    SchedulingConfigTypeDef,
     TimeoutConfigTypeDef,
+    CreateJobResponseTypeDef,
+    MaintenanceWindowTypeDef,
+    CreateJobTemplateResponseTypeDef,
     CreateKeysAndCertificateRequestRequestTypeDef,
     KeyPairTypeDef,
+    CreateMitigationActionResponseTypeDef,
+    CreateOTAUpdateResponseTypeDef,
+    CreatePackageRequestRequestTypeDef,
+    CreatePackageResponseTypeDef,
+    CreatePackageVersionRequestRequestTypeDef,
+    CreatePackageVersionResponseTypeDef,
+    CreatePolicyResponseTypeDef,
     CreatePolicyVersionRequestRequestTypeDef,
+    CreatePolicyVersionResponseTypeDef,
     CreateProvisioningClaimRequestRequestTypeDef,
     ProvisioningHookTypeDef,
+    CreateProvisioningTemplateResponseTypeDef,
     CreateProvisioningTemplateVersionRequestRequestTypeDef,
+    CreateProvisioningTemplateVersionResponseTypeDef,
+    CreateRoleAliasResponseTypeDef,
+    CreateScheduledAuditResponseTypeDef,
+    CreateSecurityProfileResponseTypeDef,
+    CreateStreamResponseTypeDef,
+    CreateThingGroupResponseTypeDef,
+    CreateThingResponseTypeDef,
     ThingTypePropertiesTypeDef,
+    CreateThingTypeResponseTypeDef,
     DeleteAccountAuditConfigurationRequestRequestTypeDef,
     DeleteAuthorizerRequestRequestTypeDef,
     DeleteBillingGroupRequestRequestTypeDef,
     DeleteCACertificateRequestRequestTypeDef,
     DeleteCertificateRequestRequestTypeDef,
     DeleteCustomMetricRequestRequestTypeDef,
     DeleteDimensionRequestRequestTypeDef,
@@ -699,14 +748,16 @@
     DeleteDynamicThingGroupRequestRequestTypeDef,
     DeleteFleetMetricRequestRequestTypeDef,
     DeleteJobExecutionRequestRequestTypeDef,
     DeleteJobRequestRequestTypeDef,
     DeleteJobTemplateRequestRequestTypeDef,
     DeleteMitigationActionRequestRequestTypeDef,
     DeleteOTAUpdateRequestRequestTypeDef,
+    DeletePackageRequestRequestTypeDef,
+    DeletePackageVersionRequestRequestTypeDef,
     DeletePolicyRequestRequestTypeDef,
     DeletePolicyVersionRequestRequestTypeDef,
     DeleteProvisioningTemplateRequestRequestTypeDef,
     DeleteProvisioningTemplateVersionRequestRequestTypeDef,
     DeleteRoleAliasRequestRequestTypeDef,
     DeleteScheduledAuditRequestRequestTypeDef,
     DeleteSecurityProfileRequestRequestTypeDef,
@@ -725,37 +776,45 @@
     TaskStatisticsTypeDef,
     DescribeAuthorizerRequestRequestTypeDef,
     DescribeBillingGroupRequestRequestTypeDef,
     DescribeCACertificateRequestRequestTypeDef,
     RegistrationConfigTypeDef,
     DescribeCertificateRequestRequestTypeDef,
     DescribeCustomMetricRequestRequestTypeDef,
+    DescribeCustomMetricResponseTypeDef,
     DescribeDetectMitigationActionsTaskRequestRequestTypeDef,
     DescribeDimensionRequestRequestTypeDef,
+    DescribeDimensionResponseTypeDef,
     DescribeDomainConfigurationRequestRequestTypeDef,
     ServerCertificateSummaryTypeDef,
     DescribeEndpointRequestRequestTypeDef,
+    DescribeEndpointResponseTypeDef,
     DescribeFleetMetricRequestRequestTypeDef,
     DescribeIndexRequestRequestTypeDef,
+    DescribeIndexResponseTypeDef,
     DescribeJobExecutionRequestRequestTypeDef,
     DescribeJobRequestRequestTypeDef,
     DescribeJobTemplateRequestRequestTypeDef,
     DescribeManagedJobTemplateRequestRequestTypeDef,
     DocumentParameterTypeDef,
     DescribeMitigationActionRequestRequestTypeDef,
     DescribeProvisioningTemplateRequestRequestTypeDef,
     DescribeProvisioningTemplateVersionRequestRequestTypeDef,
+    DescribeProvisioningTemplateVersionResponseTypeDef,
     DescribeRoleAliasRequestRequestTypeDef,
     RoleAliasDescriptionTypeDef,
     DescribeScheduledAuditRequestRequestTypeDef,
+    DescribeScheduledAuditResponseTypeDef,
     DescribeSecurityProfileRequestRequestTypeDef,
     DescribeStreamRequestRequestTypeDef,
     DescribeThingGroupRequestRequestTypeDef,
     DescribeThingRegistrationTaskRequestRequestTypeDef,
+    DescribeThingRegistrationTaskResponseTypeDef,
     DescribeThingRequestRequestTypeDef,
+    DescribeThingResponseTypeDef,
     DescribeThingTypeRequestRequestTypeDef,
     ThingTypeMetadataTypeDef,
     S3DestinationTypeDef,
     DetachPolicyRequestRequestTypeDef,
     DetachPrincipalPolicyRequestRequestTypeDef,
     DetachSecurityProfileRequestRequestTypeDef,
     DetachThingPrincipalRequestRequestTypeDef,
@@ -763,36 +822,49 @@
     DetectMitigationActionsTaskStatisticsTypeDef,
     DetectMitigationActionsTaskTargetTypeDef,
     ViolationEventOccurrenceRangeTypeDef,
     DisableTopicRuleRequestRequestTypeDef,
     DomainConfigurationSummaryTypeDef,
     PutItemInputTypeDef,
     EffectivePolicyTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableIoTLoggingParamsTypeDef,
     EnableTopicRuleRequestRequestTypeDef,
     ErrorInfoTypeDef,
     RateIncreaseCriteriaTypeDef,
     FieldTypeDef,
     S3LocationTypeDef,
     StreamTypeDef,
     FleetMetricNameAndArnTypeDef,
-    PaginatorConfigTypeDef,
+    GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef,
     GetBehaviorModelTrainingSummariesRequestRequestTypeDef,
     GetCardinalityRequestRequestTypeDef,
+    GetCardinalityResponseTypeDef,
     GetEffectivePoliciesRequestRequestTypeDef,
     GetJobDocumentRequestRequestTypeDef,
+    GetJobDocumentResponseTypeDef,
+    GetLoggingOptionsResponseTypeDef,
     GetOTAUpdateRequestRequestTypeDef,
+    VersionUpdateByJobsConfigTypeDef,
+    GetPackageRequestRequestTypeDef,
+    GetPackageResponseTypeDef,
+    GetPackageVersionRequestRequestTypeDef,
+    GetPackageVersionResponseTypeDef,
     GetPercentilesRequestRequestTypeDef,
     PercentPairTypeDef,
     GetPolicyRequestRequestTypeDef,
+    GetPolicyResponseTypeDef,
     GetPolicyVersionRequestRequestTypeDef,
+    GetPolicyVersionResponseTypeDef,
+    GetRegistrationCodeResponseTypeDef,
     GetStatisticsRequestRequestTypeDef,
     StatisticsTypeDef,
     GetTopicRuleDestinationRequestRequestTypeDef,
     GetTopicRuleRequestRequestTypeDef,
+    GetV2LoggingOptionsResponseTypeDef,
     GroupNameAndArnTypeDef,
     HttpActionHeaderTypeDef,
     SigV4AuthorizationTypeDef,
     HttpContextTypeDef,
     HttpUrlDestinationConfigurationTypeDef,
     HttpUrlDestinationPropertiesTypeDef,
     HttpUrlDestinationSummaryTypeDef,
@@ -800,223 +872,246 @@
     IssuerCertificateIdentifierTypeDef,
     JobExecutionStatusDetailsTypeDef,
     JobExecutionSummaryTypeDef,
     RetryCriteriaTypeDef,
     JobProcessDetailsTypeDef,
     JobSummaryTypeDef,
     JobTemplateSummaryTypeDef,
+    ScheduledJobRolloutTypeDef,
+    ListActiveViolationsRequestListActiveViolationsPaginateTypeDef,
     ListActiveViolationsRequestRequestTypeDef,
+    ListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef,
     ListAttachedPoliciesRequestRequestTypeDef,
+    ListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef,
     ListAuditMitigationActionsExecutionsRequestRequestTypeDef,
+    ListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef,
     ListAuditMitigationActionsTasksRequestRequestTypeDef,
+    ListAuditTasksRequestListAuditTasksPaginateTypeDef,
     ListAuditTasksRequestRequestTypeDef,
+    ListAuthorizersRequestListAuthorizersPaginateTypeDef,
     ListAuthorizersRequestRequestTypeDef,
+    ListBillingGroupsRequestListBillingGroupsPaginateTypeDef,
     ListBillingGroupsRequestRequestTypeDef,
+    ListCACertificatesRequestListCACertificatesPaginateTypeDef,
     ListCACertificatesRequestRequestTypeDef,
+    ListCertificatesByCARequestListCertificatesByCAPaginateTypeDef,
     ListCertificatesByCARequestRequestTypeDef,
+    ListCertificatesRequestListCertificatesPaginateTypeDef,
     ListCertificatesRequestRequestTypeDef,
+    ListCustomMetricsRequestListCustomMetricsPaginateTypeDef,
     ListCustomMetricsRequestRequestTypeDef,
+    ListCustomMetricsResponseTypeDef,
+    ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef,
     ListDetectMitigationActionsExecutionsRequestRequestTypeDef,
+    ListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef,
     ListDetectMitigationActionsTasksRequestRequestTypeDef,
+    ListDimensionsRequestListDimensionsPaginateTypeDef,
     ListDimensionsRequestRequestTypeDef,
+    ListDimensionsResponseTypeDef,
+    ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef,
     ListDomainConfigurationsRequestRequestTypeDef,
+    ListFleetMetricsRequestListFleetMetricsPaginateTypeDef,
     ListFleetMetricsRequestRequestTypeDef,
+    ListIndicesRequestListIndicesPaginateTypeDef,
     ListIndicesRequestRequestTypeDef,
+    ListIndicesResponseTypeDef,
+    ListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef,
     ListJobExecutionsForJobRequestRequestTypeDef,
+    ListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef,
     ListJobExecutionsForThingRequestRequestTypeDef,
+    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
     ListJobTemplatesRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListManagedJobTemplatesRequestListManagedJobTemplatesPaginateTypeDef,
     ListManagedJobTemplatesRequestRequestTypeDef,
     ManagedJobTemplateSummaryTypeDef,
+    ListMetricValuesRequestListMetricValuesPaginateTypeDef,
     ListMetricValuesRequestRequestTypeDef,
+    ListMitigationActionsRequestListMitigationActionsPaginateTypeDef,
     ListMitigationActionsRequestRequestTypeDef,
     MitigationActionIdentifierTypeDef,
+    ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef,
     ListOTAUpdatesRequestRequestTypeDef,
     OTAUpdateSummaryTypeDef,
+    ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef,
     ListOutgoingCertificatesRequestRequestTypeDef,
     OutgoingCertificateTypeDef,
+    ListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
+    ListPackageVersionsRequestRequestTypeDef,
+    PackageVersionSummaryTypeDef,
+    ListPackagesRequestListPackagesPaginateTypeDef,
+    ListPackagesRequestRequestTypeDef,
+    PackageSummaryTypeDef,
+    ListPoliciesRequestListPoliciesPaginateTypeDef,
     ListPoliciesRequestRequestTypeDef,
+    ListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef,
     ListPolicyPrincipalsRequestRequestTypeDef,
+    ListPolicyPrincipalsResponseTypeDef,
     ListPolicyVersionsRequestRequestTypeDef,
     PolicyVersionTypeDef,
+    ListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef,
     ListPrincipalPoliciesRequestRequestTypeDef,
+    ListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef,
     ListPrincipalThingsRequestRequestTypeDef,
+    ListPrincipalThingsResponseTypeDef,
+    ListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef,
     ListProvisioningTemplateVersionsRequestRequestTypeDef,
     ProvisioningTemplateVersionSummaryTypeDef,
+    ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef,
     ListProvisioningTemplatesRequestRequestTypeDef,
     ProvisioningTemplateSummaryTypeDef,
+    ListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef,
     ListRelatedResourcesForAuditFindingRequestRequestTypeDef,
+    ListRoleAliasesRequestListRoleAliasesPaginateTypeDef,
     ListRoleAliasesRequestRequestTypeDef,
+    ListRoleAliasesResponseTypeDef,
+    ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef,
     ListScheduledAuditsRequestRequestTypeDef,
     ScheduledAuditMetadataTypeDef,
+    ListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef,
     ListSecurityProfilesForTargetRequestRequestTypeDef,
+    ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef,
     ListSecurityProfilesRequestRequestTypeDef,
     SecurityProfileIdentifierTypeDef,
+    ListStreamsRequestListStreamsPaginateTypeDef,
     ListStreamsRequestRequestTypeDef,
     StreamSummaryTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
     ListTargetsForPolicyRequestRequestTypeDef,
+    ListTargetsForPolicyResponseTypeDef,
+    ListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef,
     ListTargetsForSecurityProfileRequestRequestTypeDef,
     SecurityProfileTargetTypeDef,
+    ListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef,
     ListThingGroupsForThingRequestRequestTypeDef,
+    ListThingGroupsRequestListThingGroupsPaginateTypeDef,
     ListThingGroupsRequestRequestTypeDef,
+    ListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef,
     ListThingPrincipalsRequestRequestTypeDef,
+    ListThingPrincipalsResponseTypeDef,
+    ListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef,
     ListThingRegistrationTaskReportsRequestRequestTypeDef,
+    ListThingRegistrationTaskReportsResponseTypeDef,
+    ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef,
     ListThingRegistrationTasksRequestRequestTypeDef,
+    ListThingRegistrationTasksResponseTypeDef,
+    ListThingTypesRequestListThingTypesPaginateTypeDef,
     ListThingTypesRequestRequestTypeDef,
+    ListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef,
     ListThingsInBillingGroupRequestRequestTypeDef,
+    ListThingsInBillingGroupResponseTypeDef,
+    ListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef,
     ListThingsInThingGroupRequestRequestTypeDef,
+    ListThingsInThingGroupResponseTypeDef,
+    ListThingsRequestListThingsPaginateTypeDef,
     ListThingsRequestRequestTypeDef,
     ThingAttributeTypeDef,
+    ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef,
     ListTopicRuleDestinationsRequestRequestTypeDef,
+    ListTopicRulesRequestListTopicRulesPaginateTypeDef,
     ListTopicRulesRequestRequestTypeDef,
     TopicRuleListItemTypeDef,
+    ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef,
     ListV2LoggingLevelsRequestRequestTypeDef,
+    ListViolationEventsRequestListViolationEventsPaginateTypeDef,
     ListViolationEventsRequestRequestTypeDef,
     LocationTimestampTypeDef,
     LogTargetTypeDef,
     LoggingOptionsPayloadTypeDef,
     PublishFindingToSnsParamsTypeDef,
     ReplaceDefaultPolicyVersionParamsTypeDef,
     UpdateCACertificateParamsTypeDef,
     UpdateDeviceCertificateParamsTypeDef,
     MqttContextTypeDef,
     UserPropertyTypeDef,
+    PaginatorConfigTypeDef,
     PolicyVersionIdentifierTypeDef,
     PutVerificationStateOnViolationRequestRequestTypeDef,
+    RegisterCACertificateResponseTypeDef,
     RegisterCertificateRequestRequestTypeDef,
+    RegisterCertificateResponseTypeDef,
     RegisterCertificateWithoutCARequestRequestTypeDef,
+    RegisterCertificateWithoutCAResponseTypeDef,
     RegisterThingRequestRequestTypeDef,
+    RegisterThingResponseTypeDef,
     RejectCertificateTransferRequestRequestTypeDef,
     RemoveThingFromBillingGroupRequestRequestTypeDef,
     RemoveThingFromThingGroupRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SearchIndexRequestRequestTypeDef,
     ThingGroupDocumentTypeDef,
     SetDefaultAuthorizerRequestRequestTypeDef,
+    SetDefaultAuthorizerResponseTypeDef,
     SetDefaultPolicyVersionRequestRequestTypeDef,
     SetV2LoggingOptionsRequestRequestTypeDef,
     SigningProfileParameterTypeDef,
+    StartAuditMitigationActionsTaskResponseTypeDef,
+    StartDetectMitigationActionsTaskResponseTypeDef,
     StartOnDemandAuditTaskRequestRequestTypeDef,
+    StartOnDemandAuditTaskResponseTypeDef,
     StartThingRegistrationTaskRequestRequestTypeDef,
+    StartThingRegistrationTaskResponseTypeDef,
     StopThingRegistrationTaskRequestRequestTypeDef,
     TlsContextTypeDef,
+    TestInvokeAuthorizerResponseTypeDef,
     ThingConnectivityTypeDef,
     TimestreamDimensionTypeDef,
     TimestreamTimestampTypeDef,
     VpcDestinationConfigurationTypeDef,
     VpcDestinationSummaryTypeDef,
     VpcDestinationPropertiesTypeDef,
     TransferCertificateRequestRequestTypeDef,
+    TransferCertificateResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAuthorizerRequestRequestTypeDef,
+    UpdateAuthorizerResponseTypeDef,
+    UpdateBillingGroupResponseTypeDef,
     UpdateCertificateRequestRequestTypeDef,
     UpdateCustomMetricRequestRequestTypeDef,
+    UpdateCustomMetricResponseTypeDef,
     UpdateDimensionRequestRequestTypeDef,
+    UpdateDimensionResponseTypeDef,
+    UpdateDomainConfigurationResponseTypeDef,
+    UpdateDynamicThingGroupResponseTypeDef,
+    UpdateMitigationActionResponseTypeDef,
+    UpdatePackageRequestRequestTypeDef,
+    UpdatePackageVersionRequestRequestTypeDef,
     UpdateRoleAliasRequestRequestTypeDef,
+    UpdateRoleAliasResponseTypeDef,
     UpdateScheduledAuditRequestRequestTypeDef,
+    UpdateScheduledAuditResponseTypeDef,
+    UpdateStreamResponseTypeDef,
+    UpdateThingGroupResponseTypeDef,
     UpdateThingGroupsForThingRequestRequestTypeDef,
     UpdateTopicRuleDestinationRequestRequestTypeDef,
     ValidationErrorTypeDef,
     AbortConfigTypeDef,
     MetricDatumTypeDef,
+    DescribeFleetMetricResponseTypeDef,
     UpdateFleetMetricRequestRequestTypeDef,
     AllowedTypeDef,
     ExplicitDenyTypeDef,
     ImplicitDenyTypeDef,
-    AssetPropertyValueTypeDef,
-    AssociateTargetsWithJobResponseTypeDef,
-    CancelJobResponseTypeDef,
-    CreateAuthorizerResponseTypeDef,
-    CreateBillingGroupResponseTypeDef,
-    CreateCertificateFromCsrResponseTypeDef,
-    CreateCustomMetricResponseTypeDef,
-    CreateDimensionResponseTypeDef,
-    CreateDomainConfigurationResponseTypeDef,
-    CreateDynamicThingGroupResponseTypeDef,
-    CreateFleetMetricResponseTypeDef,
-    CreateJobResponseTypeDef,
-    CreateJobTemplateResponseTypeDef,
-    CreateMitigationActionResponseTypeDef,
-    CreateOTAUpdateResponseTypeDef,
-    CreatePolicyResponseTypeDef,
-    CreatePolicyVersionResponseTypeDef,
-    CreateProvisioningTemplateResponseTypeDef,
-    CreateProvisioningTemplateVersionResponseTypeDef,
-    CreateRoleAliasResponseTypeDef,
-    CreateScheduledAuditResponseTypeDef,
-    CreateSecurityProfileResponseTypeDef,
-    CreateStreamResponseTypeDef,
-    CreateThingGroupResponseTypeDef,
-    CreateThingResponseTypeDef,
-    CreateThingTypeResponseTypeDef,
-    DescribeCustomMetricResponseTypeDef,
-    DescribeDimensionResponseTypeDef,
-    DescribeEndpointResponseTypeDef,
-    DescribeFleetMetricResponseTypeDef,
-    DescribeIndexResponseTypeDef,
-    DescribeProvisioningTemplateVersionResponseTypeDef,
-    DescribeScheduledAuditResponseTypeDef,
-    DescribeThingRegistrationTaskResponseTypeDef,
-    DescribeThingResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCardinalityResponseTypeDef,
-    GetJobDocumentResponseTypeDef,
-    GetLoggingOptionsResponseTypeDef,
-    GetPolicyResponseTypeDef,
-    GetPolicyVersionResponseTypeDef,
-    GetRegistrationCodeResponseTypeDef,
-    GetV2LoggingOptionsResponseTypeDef,
     ListAttachedPoliciesResponseTypeDef,
-    ListCustomMetricsResponseTypeDef,
-    ListDimensionsResponseTypeDef,
-    ListIndicesResponseTypeDef,
     ListPoliciesResponseTypeDef,
-    ListPolicyPrincipalsResponseTypeDef,
     ListPrincipalPoliciesResponseTypeDef,
-    ListPrincipalThingsResponseTypeDef,
-    ListRoleAliasesResponseTypeDef,
-    ListTargetsForPolicyResponseTypeDef,
-    ListThingPrincipalsResponseTypeDef,
-    ListThingRegistrationTaskReportsResponseTypeDef,
-    ListThingRegistrationTasksResponseTypeDef,
-    ListThingsInBillingGroupResponseTypeDef,
-    ListThingsInThingGroupResponseTypeDef,
-    RegisterCACertificateResponseTypeDef,
-    RegisterCertificateResponseTypeDef,
-    RegisterCertificateWithoutCAResponseTypeDef,
-    RegisterThingResponseTypeDef,
-    SetDefaultAuthorizerResponseTypeDef,
-    StartAuditMitigationActionsTaskResponseTypeDef,
-    StartDetectMitigationActionsTaskResponseTypeDef,
-    StartOnDemandAuditTaskResponseTypeDef,
-    StartThingRegistrationTaskResponseTypeDef,
-    TestInvokeAuthorizerResponseTypeDef,
-    TransferCertificateResponseTypeDef,
-    UpdateAuthorizerResponseTypeDef,
-    UpdateBillingGroupResponseTypeDef,
-    UpdateCustomMetricResponseTypeDef,
-    UpdateDimensionResponseTypeDef,
-    UpdateDomainConfigurationResponseTypeDef,
-    UpdateDynamicThingGroupResponseTypeDef,
-    UpdateMitigationActionResponseTypeDef,
-    UpdateRoleAliasResponseTypeDef,
-    UpdateScheduledAuditResponseTypeDef,
-    UpdateStreamResponseTypeDef,
-    UpdateThingGroupResponseTypeDef,
+    AssetPropertyValueTypeDef,
     CreateThingRequestRequestTypeDef,
     ThingGroupPropertiesTypeDef,
     UpdateThingRequestRequestTypeDef,
     ListAuditMitigationActionsExecutionsResponseTypeDef,
     ListAuditMitigationActionsTasksResponseTypeDef,
     StartAuditMitigationActionsTaskRequestRequestTypeDef,
     DescribeAccountAuditConfigurationResponseTypeDef,
     UpdateAccountAuditConfigurationRequestRequestTypeDef,
     ListAuditTasksResponseTypeDef,
     TestAuthorizationRequestRequestTypeDef,
-    UpdateDomainConfigurationRequestRequestTypeDef,
     DescribeAuthorizerResponseTypeDef,
     DescribeDefaultAuthorizerResponseTypeDef,
     ListAuthorizersResponseTypeDef,
     AwsJobAbortConfigTypeDef,
     AwsJobExponentialRolloutRateTypeDef,
     BehaviorCriteriaTypeDef,
     GetBehaviorModelTrainingSummariesResponseTypeDef,
@@ -1033,21 +1128,23 @@
     CustomCodeSigningTypeDef,
     DescribeEventConfigurationsResponseTypeDef,
     UpdateEventConfigurationsRequestRequestTypeDef,
     CreateAuthorizerRequestRequestTypeDef,
     CreateBillingGroupRequestRequestTypeDef,
     CreateCustomMetricRequestRequestTypeDef,
     CreateDimensionRequestRequestTypeDef,
-    CreateDomainConfigurationRequestRequestTypeDef,
     CreateFleetMetricRequestRequestTypeDef,
     CreatePolicyRequestRequestTypeDef,
     CreateRoleAliasRequestRequestTypeDef,
     CreateScheduledAuditRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    CreateDomainConfigurationRequestRequestTypeDef,
+    UpdateDomainConfigurationRequestRequestTypeDef,
+    SchedulingConfigTypeDef,
     CreateKeysAndCertificateResponseTypeDef,
     CreateProvisioningClaimResponseTypeDef,
     CreateProvisioningTemplateRequestRequestTypeDef,
     DescribeProvisioningTemplateResponseTypeDef,
     UpdateProvisioningTemplateRequestRequestTypeDef,
     CreateThingTypeRequestRequestTypeDef,
     DescribeAuditTaskResponseTypeDef,
@@ -1065,67 +1162,16 @@
     DynamoDBv2ActionTypeDef,
     GetEffectivePoliciesResponseTypeDef,
     ExponentialRolloutRateTypeDef,
     ThingGroupIndexingConfigurationTypeDef,
     StreamFileTypeDef,
     FileLocationTypeDef,
     ListFleetMetricsResponseTypeDef,
-    GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef,
-    ListActiveViolationsRequestListActiveViolationsPaginateTypeDef,
-    ListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef,
-    ListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef,
-    ListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef,
-    ListAuditTasksRequestListAuditTasksPaginateTypeDef,
-    ListAuthorizersRequestListAuthorizersPaginateTypeDef,
-    ListBillingGroupsRequestListBillingGroupsPaginateTypeDef,
-    ListCACertificatesRequestListCACertificatesPaginateTypeDef,
-    ListCertificatesByCARequestListCertificatesByCAPaginateTypeDef,
-    ListCertificatesRequestListCertificatesPaginateTypeDef,
-    ListCustomMetricsRequestListCustomMetricsPaginateTypeDef,
-    ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef,
-    ListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef,
-    ListDimensionsRequestListDimensionsPaginateTypeDef,
-    ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef,
-    ListFleetMetricsRequestListFleetMetricsPaginateTypeDef,
-    ListIndicesRequestListIndicesPaginateTypeDef,
-    ListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef,
-    ListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef,
-    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListMetricValuesRequestListMetricValuesPaginateTypeDef,
-    ListMitigationActionsRequestListMitigationActionsPaginateTypeDef,
-    ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef,
-    ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef,
-    ListPoliciesRequestListPoliciesPaginateTypeDef,
-    ListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef,
-    ListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef,
-    ListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef,
-    ListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef,
-    ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef,
-    ListRoleAliasesRequestListRoleAliasesPaginateTypeDef,
-    ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef,
-    ListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef,
-    ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef,
-    ListStreamsRequestListStreamsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
-    ListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef,
-    ListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef,
-    ListThingGroupsRequestListThingGroupsPaginateTypeDef,
-    ListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef,
-    ListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef,
-    ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef,
-    ListThingTypesRequestListThingTypesPaginateTypeDef,
-    ListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef,
-    ListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef,
-    ListThingsRequestListThingsPaginateTypeDef,
-    ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef,
-    ListTopicRulesRequestListTopicRulesPaginateTypeDef,
-    ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef,
-    ListViolationEventsRequestListViolationEventsPaginateTypeDef,
+    GetPackageConfigurationResponseTypeDef,
+    UpdatePackageConfigurationRequestRequestTypeDef,
     GetPercentilesResponseTypeDef,
     GetStatisticsResponseTypeDef,
     ListBillingGroupsResponseTypeDef,
     ListThingGroupsForThingResponseTypeDef,
     ListThingGroupsResponseTypeDef,
     ThingGroupMetadataTypeDef,
     HttpAuthorizationTypeDef,
@@ -1136,14 +1182,16 @@
     JobExecutionsRetryConfigTypeDef,
     ListJobsResponseTypeDef,
     ListJobTemplatesResponseTypeDef,
     ListManagedJobTemplatesResponseTypeDef,
     ListMitigationActionsResponseTypeDef,
     ListOTAUpdatesResponseTypeDef,
     ListOutgoingCertificatesResponseTypeDef,
+    ListPackageVersionsResponseTypeDef,
+    ListPackagesResponseTypeDef,
     ListPolicyVersionsResponseTypeDef,
     ListProvisioningTemplateVersionsResponseTypeDef,
     ListProvisioningTemplatesResponseTypeDef,
     ListScheduledAuditsResponseTypeDef,
     ListSecurityProfilesResponseTypeDef,
     ListStreamsResponseTypeDef,
     ListTargetsForSecurityProfileResponseTypeDef,
@@ -1262,43 +1310,43 @@
 <a id="how-it-works"></a>
 
 ## How it works
 
 Fully automated
 [mypy-boto3-builder](https://github.com/youtype/mypy_boto3_builder) carefully
 generates type annotations for each service, patiently waiting for
-`aiobotocore` updates. It delivers a drop-in type annotations for you and makes
+`aiobotocore` updates. It delivers drop-in type annotations for you and makes
 sure that:
 
 - All available `aiobotocore` services are covered.
 - Each public class and method of every `aiobotocore` service gets valid type
-  annotations extracted from the documentation (blame `botocore` docs if types
-  are incorrect).
+  annotations extracted from `botocore` schemas.
 - Type annotations include up-to-date documentation.
 - Link to documentation is provided for every method.
 - Code is processed by [black](https://github.com/psf/black) and
   [isort](https://github.com/PyCQA/isort) for readability.
 
 <a id="what's-new"></a>
 
 ## What's new
 
 <a id="implemented-features"></a>
 
 ### Implemented features
 
-- Fully type annotated `boto3`, `botocore` and `aiobotocore` libraries
+- Fully type annotated `boto3`, `botocore`, `aiobotocore` and `aioboto3`
+  libraries
 - `mypy`, `pyright`, `VSCode`, `PyCharm`, `Sublime Text` and `Emacs`
   compatibility
 - `Client`, `ServiceResource`, `Resource`, `Waiter` `Paginator` type
   annotations for each service
 - Generated `TypeDefs` for each service
 - Generated `Literals` for each service
-- Auto discovery of types for `boto3.client` and `boto3.session` calls
-- Auto discovery of types for `session.client` and `session.session` calls
+- Auto discovery of types for `boto3.client` and `boto3.resource` calls
+- Auto discovery of types for `session.client` and `session.resource` calls
 - Auto discovery of types for `client.get_waiter` and `client.get_paginator`
   calls
 - Auto discovery of types for `ServiceResource` and `Resource` collections
 - Auto discovery of types for `aiobotocore.Session.create_client` calls
 
 <a id="latest-changes"></a>
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/setup.py` & `types-aiobotocore-iot-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iot.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iot",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iot"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoT 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.IoT 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -46,11 +46,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/",
         "Source": "https://github.com/youtype/mypy_boto3_builder",
         "Tracker": "https://github.com/youtype/mypy_boto3_builder/issues",
     },
     install_requires=[
-        "typing-extensions>=4.1.0",
+        'typing-extensions>=4.1.0; python_version<"3.9"',
     ],
     zip_safe=False,
 )
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/__init__.py` & `types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -28,24 +28,28 @@
         ListDomainConfigurationsPaginator,
         ListFleetMetricsPaginator,
         ListIndicesPaginator,
         ListJobExecutionsForJobPaginator,
         ListJobExecutionsForThingPaginator,
         ListJobTemplatesPaginator,
         ListJobsPaginator,
+        ListManagedJobTemplatesPaginator,
         ListMetricValuesPaginator,
         ListMitigationActionsPaginator,
         ListOTAUpdatesPaginator,
         ListOutgoingCertificatesPaginator,
+        ListPackageVersionsPaginator,
+        ListPackagesPaginator,
         ListPoliciesPaginator,
         ListPolicyPrincipalsPaginator,
         ListPrincipalPoliciesPaginator,
         ListPrincipalThingsPaginator,
         ListProvisioningTemplateVersionsPaginator,
         ListProvisioningTemplatesPaginator,
+        ListRelatedResourcesForAuditFindingPaginator,
         ListRoleAliasesPaginator,
         ListScheduledAuditsPaginator,
         ListSecurityProfilesForTargetPaginator,
         ListSecurityProfilesPaginator,
         ListStreamsPaginator,
         ListTagsForResourcePaginator,
         ListTargetsForPolicyPaginator,
@@ -91,24 +95,28 @@
     list_domain_configurations_paginator: ListDomainConfigurationsPaginator = client.get_paginator("list_domain_configurations")
     list_fleet_metrics_paginator: ListFleetMetricsPaginator = client.get_paginator("list_fleet_metrics")
     list_indices_paginator: ListIndicesPaginator = client.get_paginator("list_indices")
     list_job_executions_for_job_paginator: ListJobExecutionsForJobPaginator = client.get_paginator("list_job_executions_for_job")
     list_job_executions_for_thing_paginator: ListJobExecutionsForThingPaginator = client.get_paginator("list_job_executions_for_thing")
     list_job_templates_paginator: ListJobTemplatesPaginator = client.get_paginator("list_job_templates")
     list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
+    list_managed_job_templates_paginator: ListManagedJobTemplatesPaginator = client.get_paginator("list_managed_job_templates")
     list_metric_values_paginator: ListMetricValuesPaginator = client.get_paginator("list_metric_values")
     list_mitigation_actions_paginator: ListMitigationActionsPaginator = client.get_paginator("list_mitigation_actions")
     list_ota_updates_paginator: ListOTAUpdatesPaginator = client.get_paginator("list_ota_updates")
     list_outgoing_certificates_paginator: ListOutgoingCertificatesPaginator = client.get_paginator("list_outgoing_certificates")
+    list_package_versions_paginator: ListPackageVersionsPaginator = client.get_paginator("list_package_versions")
+    list_packages_paginator: ListPackagesPaginator = client.get_paginator("list_packages")
     list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
     list_policy_principals_paginator: ListPolicyPrincipalsPaginator = client.get_paginator("list_policy_principals")
     list_principal_policies_paginator: ListPrincipalPoliciesPaginator = client.get_paginator("list_principal_policies")
     list_principal_things_paginator: ListPrincipalThingsPaginator = client.get_paginator("list_principal_things")
     list_provisioning_template_versions_paginator: ListProvisioningTemplateVersionsPaginator = client.get_paginator("list_provisioning_template_versions")
     list_provisioning_templates_paginator: ListProvisioningTemplatesPaginator = client.get_paginator("list_provisioning_templates")
+    list_related_resources_for_audit_finding_paginator: ListRelatedResourcesForAuditFindingPaginator = client.get_paginator("list_related_resources_for_audit_finding")
     list_role_aliases_paginator: ListRoleAliasesPaginator = client.get_paginator("list_role_aliases")
     list_scheduled_audits_paginator: ListScheduledAuditsPaginator = client.get_paginator("list_scheduled_audits")
     list_security_profiles_paginator: ListSecurityProfilesPaginator = client.get_paginator("list_security_profiles")
     list_security_profiles_for_target_paginator: ListSecurityProfilesForTargetPaginator = client.get_paginator("list_security_profiles_for_target")
     list_streams_paginator: ListStreamsPaginator = client.get_paginator("list_streams")
     list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     list_targets_for_policy_paginator: ListTargetsForPolicyPaginator = client.get_paginator("list_targets_for_policy")
@@ -150,24 +158,28 @@
     ListDomainConfigurationsPaginator,
     ListFleetMetricsPaginator,
     ListIndicesPaginator,
     ListJobExecutionsForJobPaginator,
     ListJobExecutionsForThingPaginator,
     ListJobsPaginator,
     ListJobTemplatesPaginator,
+    ListManagedJobTemplatesPaginator,
     ListMetricValuesPaginator,
     ListMitigationActionsPaginator,
     ListOTAUpdatesPaginator,
     ListOutgoingCertificatesPaginator,
+    ListPackagesPaginator,
+    ListPackageVersionsPaginator,
     ListPoliciesPaginator,
     ListPolicyPrincipalsPaginator,
     ListPrincipalPoliciesPaginator,
     ListPrincipalThingsPaginator,
     ListProvisioningTemplatesPaginator,
     ListProvisioningTemplateVersionsPaginator,
+    ListRelatedResourcesForAuditFindingPaginator,
     ListRoleAliasesPaginator,
     ListScheduledAuditsPaginator,
     ListSecurityProfilesForTargetPaginator,
     ListSecurityProfilesPaginator,
     ListStreamsPaginator,
     ListTagsForResourcePaginator,
     ListTargetsForPolicyPaginator,
@@ -213,24 +225,28 @@
     "ListDomainConfigurationsPaginator",
     "ListFleetMetricsPaginator",
     "ListIndicesPaginator",
     "ListJobExecutionsForJobPaginator",
     "ListJobExecutionsForThingPaginator",
     "ListJobTemplatesPaginator",
     "ListJobsPaginator",
+    "ListManagedJobTemplatesPaginator",
     "ListMetricValuesPaginator",
     "ListMitigationActionsPaginator",
     "ListOTAUpdatesPaginator",
     "ListOutgoingCertificatesPaginator",
+    "ListPackageVersionsPaginator",
+    "ListPackagesPaginator",
     "ListPoliciesPaginator",
     "ListPolicyPrincipalsPaginator",
     "ListPrincipalPoliciesPaginator",
     "ListPrincipalThingsPaginator",
     "ListProvisioningTemplateVersionsPaginator",
     "ListProvisioningTemplatesPaginator",
+    "ListRelatedResourcesForAuditFindingPaginator",
     "ListRoleAliasesPaginator",
     "ListScheduledAuditsPaginator",
     "ListSecurityProfilesForTargetPaginator",
     "ListSecurityProfilesPaginator",
     "ListStreamsPaginator",
     "ListTagsForResourcePaginator",
     "ListTargetsForPolicyPaginator",
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/__init__.pyi` & `types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/__init__.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -28,24 +28,28 @@
         ListDomainConfigurationsPaginator,
         ListFleetMetricsPaginator,
         ListIndicesPaginator,
         ListJobExecutionsForJobPaginator,
         ListJobExecutionsForThingPaginator,
         ListJobTemplatesPaginator,
         ListJobsPaginator,
+        ListManagedJobTemplatesPaginator,
         ListMetricValuesPaginator,
         ListMitigationActionsPaginator,
         ListOTAUpdatesPaginator,
         ListOutgoingCertificatesPaginator,
+        ListPackageVersionsPaginator,
+        ListPackagesPaginator,
         ListPoliciesPaginator,
         ListPolicyPrincipalsPaginator,
         ListPrincipalPoliciesPaginator,
         ListPrincipalThingsPaginator,
         ListProvisioningTemplateVersionsPaginator,
         ListProvisioningTemplatesPaginator,
+        ListRelatedResourcesForAuditFindingPaginator,
         ListRoleAliasesPaginator,
         ListScheduledAuditsPaginator,
         ListSecurityProfilesForTargetPaginator,
         ListSecurityProfilesPaginator,
         ListStreamsPaginator,
         ListTagsForResourcePaginator,
         ListTargetsForPolicyPaginator,
@@ -91,24 +95,28 @@
     list_domain_configurations_paginator: ListDomainConfigurationsPaginator = client.get_paginator("list_domain_configurations")
     list_fleet_metrics_paginator: ListFleetMetricsPaginator = client.get_paginator("list_fleet_metrics")
     list_indices_paginator: ListIndicesPaginator = client.get_paginator("list_indices")
     list_job_executions_for_job_paginator: ListJobExecutionsForJobPaginator = client.get_paginator("list_job_executions_for_job")
     list_job_executions_for_thing_paginator: ListJobExecutionsForThingPaginator = client.get_paginator("list_job_executions_for_thing")
     list_job_templates_paginator: ListJobTemplatesPaginator = client.get_paginator("list_job_templates")
     list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
+    list_managed_job_templates_paginator: ListManagedJobTemplatesPaginator = client.get_paginator("list_managed_job_templates")
     list_metric_values_paginator: ListMetricValuesPaginator = client.get_paginator("list_metric_values")
     list_mitigation_actions_paginator: ListMitigationActionsPaginator = client.get_paginator("list_mitigation_actions")
     list_ota_updates_paginator: ListOTAUpdatesPaginator = client.get_paginator("list_ota_updates")
     list_outgoing_certificates_paginator: ListOutgoingCertificatesPaginator = client.get_paginator("list_outgoing_certificates")
+    list_package_versions_paginator: ListPackageVersionsPaginator = client.get_paginator("list_package_versions")
+    list_packages_paginator: ListPackagesPaginator = client.get_paginator("list_packages")
     list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
     list_policy_principals_paginator: ListPolicyPrincipalsPaginator = client.get_paginator("list_policy_principals")
     list_principal_policies_paginator: ListPrincipalPoliciesPaginator = client.get_paginator("list_principal_policies")
     list_principal_things_paginator: ListPrincipalThingsPaginator = client.get_paginator("list_principal_things")
     list_provisioning_template_versions_paginator: ListProvisioningTemplateVersionsPaginator = client.get_paginator("list_provisioning_template_versions")
     list_provisioning_templates_paginator: ListProvisioningTemplatesPaginator = client.get_paginator("list_provisioning_templates")
+    list_related_resources_for_audit_finding_paginator: ListRelatedResourcesForAuditFindingPaginator = client.get_paginator("list_related_resources_for_audit_finding")
     list_role_aliases_paginator: ListRoleAliasesPaginator = client.get_paginator("list_role_aliases")
     list_scheduled_audits_paginator: ListScheduledAuditsPaginator = client.get_paginator("list_scheduled_audits")
     list_security_profiles_paginator: ListSecurityProfilesPaginator = client.get_paginator("list_security_profiles")
     list_security_profiles_for_target_paginator: ListSecurityProfilesForTargetPaginator = client.get_paginator("list_security_profiles_for_target")
     list_streams_paginator: ListStreamsPaginator = client.get_paginator("list_streams")
     list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     list_targets_for_policy_paginator: ListTargetsForPolicyPaginator = client.get_paginator("list_targets_for_policy")
@@ -150,24 +158,28 @@
     ListDomainConfigurationsPaginator,
     ListFleetMetricsPaginator,
     ListIndicesPaginator,
     ListJobExecutionsForJobPaginator,
     ListJobExecutionsForThingPaginator,
     ListJobsPaginator,
     ListJobTemplatesPaginator,
+    ListManagedJobTemplatesPaginator,
     ListMetricValuesPaginator,
     ListMitigationActionsPaginator,
     ListOTAUpdatesPaginator,
     ListOutgoingCertificatesPaginator,
+    ListPackagesPaginator,
+    ListPackageVersionsPaginator,
     ListPoliciesPaginator,
     ListPolicyPrincipalsPaginator,
     ListPrincipalPoliciesPaginator,
     ListPrincipalThingsPaginator,
     ListProvisioningTemplatesPaginator,
     ListProvisioningTemplateVersionsPaginator,
+    ListRelatedResourcesForAuditFindingPaginator,
     ListRoleAliasesPaginator,
     ListScheduledAuditsPaginator,
     ListSecurityProfilesForTargetPaginator,
     ListSecurityProfilesPaginator,
     ListStreamsPaginator,
     ListTagsForResourcePaginator,
     ListTargetsForPolicyPaginator,
@@ -212,24 +224,28 @@
     "ListDomainConfigurationsPaginator",
     "ListFleetMetricsPaginator",
     "ListIndicesPaginator",
     "ListJobExecutionsForJobPaginator",
     "ListJobExecutionsForThingPaginator",
     "ListJobTemplatesPaginator",
     "ListJobsPaginator",
+    "ListManagedJobTemplatesPaginator",
     "ListMetricValuesPaginator",
     "ListMitigationActionsPaginator",
     "ListOTAUpdatesPaginator",
     "ListOutgoingCertificatesPaginator",
+    "ListPackageVersionsPaginator",
+    "ListPackagesPaginator",
     "ListPoliciesPaginator",
     "ListPolicyPrincipalsPaginator",
     "ListPrincipalPoliciesPaginator",
     "ListPrincipalThingsPaginator",
     "ListProvisioningTemplateVersionsPaginator",
     "ListProvisioningTemplatesPaginator",
+    "ListRelatedResourcesForAuditFindingPaginator",
     "ListRoleAliasesPaginator",
     "ListScheduledAuditsPaginator",
     "ListSecurityProfilesForTargetPaginator",
     "ListSecurityProfilesPaginator",
     "ListStreamsPaginator",
     "ListTagsForResourcePaginator",
     "ListTargetsForPolicyPaginator",
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/__main__.py` & `types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoT 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoT 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT\nOther"
         " services:  https://pypi.org/project/boto3-stubs/\nChangelog:      "
         " https://github.com/youtype/mypy_boto3_builder/releases"
     )
 
 
 def print_version() -> None:
     """
     Print package version to stdout.
     """
-    print("2.5.0.post1")
+    print("2.5.1")
 
 
 def main() -> None:
     """
     Main CLI entrypoint.
     """
     if "--version" in sys.argv:
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/client.py` & `types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -41,14 +41,16 @@
     FleetMetricUnitType,
     JobExecutionStatusType,
     JobStatusType,
     LogLevelType,
     LogTargetTypeType,
     MitigationActionTypeType,
     OTAUpdateStatusType,
+    PackageVersionActionType,
+    PackageVersionStatusType,
     ProtocolType,
     ReportTypeType,
     ServiceTypeType,
     StatusType,
     TargetSelectionType,
     TemplateTypeType,
     TopicRuleDestinationStatusType,
@@ -75,24 +77,28 @@
     ListDomainConfigurationsPaginator,
     ListFleetMetricsPaginator,
     ListIndicesPaginator,
     ListJobExecutionsForJobPaginator,
     ListJobExecutionsForThingPaginator,
     ListJobsPaginator,
     ListJobTemplatesPaginator,
+    ListManagedJobTemplatesPaginator,
     ListMetricValuesPaginator,
     ListMitigationActionsPaginator,
     ListOTAUpdatesPaginator,
     ListOutgoingCertificatesPaginator,
+    ListPackagesPaginator,
+    ListPackageVersionsPaginator,
     ListPoliciesPaginator,
     ListPolicyPrincipalsPaginator,
     ListPrincipalPoliciesPaginator,
     ListPrincipalThingsPaginator,
     ListProvisioningTemplatesPaginator,
     ListProvisioningTemplateVersionsPaginator,
+    ListRelatedResourcesForAuditFindingPaginator,
     ListRoleAliasesPaginator,
     ListScheduledAuditsPaginator,
     ListSecurityProfilesForTargetPaginator,
     ListSecurityProfilesPaginator,
     ListStreamsPaginator,
     ListTagsForResourcePaginator,
     ListTargetsForPolicyPaginator,
@@ -140,14 +146,16 @@
     CreateDynamicThingGroupResponseTypeDef,
     CreateFleetMetricResponseTypeDef,
     CreateJobResponseTypeDef,
     CreateJobTemplateResponseTypeDef,
     CreateKeysAndCertificateResponseTypeDef,
     CreateMitigationActionResponseTypeDef,
     CreateOTAUpdateResponseTypeDef,
+    CreatePackageResponseTypeDef,
+    CreatePackageVersionResponseTypeDef,
     CreatePolicyResponseTypeDef,
     CreatePolicyVersionResponseTypeDef,
     CreateProvisioningClaimResponseTypeDef,
     CreateProvisioningTemplateResponseTypeDef,
     CreateProvisioningTemplateVersionResponseTypeDef,
     CreateRoleAliasResponseTypeDef,
     CreateScheduledAuditResponseTypeDef,
@@ -196,14 +204,17 @@
     GetBucketsAggregationResponseTypeDef,
     GetCardinalityResponseTypeDef,
     GetEffectivePoliciesResponseTypeDef,
     GetIndexingConfigurationResponseTypeDef,
     GetJobDocumentResponseTypeDef,
     GetLoggingOptionsResponseTypeDef,
     GetOTAUpdateResponseTypeDef,
+    GetPackageConfigurationResponseTypeDef,
+    GetPackageResponseTypeDef,
+    GetPackageVersionResponseTypeDef,
     GetPercentilesResponseTypeDef,
     GetPolicyResponseTypeDef,
     GetPolicyVersionResponseTypeDef,
     GetRegistrationCodeResponseTypeDef,
     GetStatisticsResponseTypeDef,
     GetTopicRuleDestinationResponseTypeDef,
     GetTopicRuleResponseTypeDef,
@@ -235,14 +246,16 @@
     ListJobsResponseTypeDef,
     ListJobTemplatesResponseTypeDef,
     ListManagedJobTemplatesResponseTypeDef,
     ListMetricValuesResponseTypeDef,
     ListMitigationActionsResponseTypeDef,
     ListOTAUpdatesResponseTypeDef,
     ListOutgoingCertificatesResponseTypeDef,
+    ListPackagesResponseTypeDef,
+    ListPackageVersionsResponseTypeDef,
     ListPoliciesResponseTypeDef,
     ListPolicyPrincipalsResponseTypeDef,
     ListPolicyVersionsResponseTypeDef,
     ListPrincipalPoliciesResponseTypeDef,
     ListPrincipalThingsResponseTypeDef,
     ListProvisioningTemplatesResponseTypeDef,
     ListProvisioningTemplateVersionsResponseTypeDef,
@@ -266,14 +279,15 @@
     ListThingTypesResponseTypeDef,
     ListTopicRuleDestinationsResponseTypeDef,
     ListTopicRulesResponseTypeDef,
     ListV2LoggingLevelsResponseTypeDef,
     ListViolationEventsResponseTypeDef,
     LoggingOptionsPayloadTypeDef,
     LogTargetTypeDef,
+    MaintenanceWindowTypeDef,
     MetricToRetainTypeDef,
     MitigationActionParamsTypeDef,
     MqttContextTypeDef,
     OTAUpdateFileTypeDef,
     PresignedUrlConfigTypeDef,
     ProvisioningHookTypeDef,
     RegisterCACertificateResponseTypeDef,
@@ -294,14 +308,15 @@
     TestAuthorizationResponseTypeDef,
     TestInvokeAuthorizerResponseTypeDef,
     ThingGroupIndexingConfigurationTypeDef,
     ThingGroupPropertiesTypeDef,
     ThingIndexingConfigurationTypeDef,
     ThingTypePropertiesTypeDef,
     TimeoutConfigTypeDef,
+    TlsConfigTypeDef,
     TlsContextTypeDef,
     TopicRuleDestinationConfigurationTypeDef,
     TopicRulePayloadTypeDef,
     TransferCertificateResponseTypeDef,
     UpdateAuthorizerResponseTypeDef,
     UpdateBillingGroupResponseTypeDef,
     UpdateCustomMetricResponseTypeDef,
@@ -311,14 +326,15 @@
     UpdateMitigationActionResponseTypeDef,
     UpdateRoleAliasResponseTypeDef,
     UpdateScheduledAuditResponseTypeDef,
     UpdateSecurityProfileResponseTypeDef,
     UpdateStreamResponseTypeDef,
     UpdateThingGroupResponseTypeDef,
     ValidateSecurityProfileBehaviorsResponseTypeDef,
+    VersionUpdateByJobsConfigTypeDef,
     ViolationEventOccurrenceRangeTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -355,21 +371,23 @@
     LimitExceededException: Type[BotocoreClientError]
     MalformedPolicyException: Type[BotocoreClientError]
     NotConfiguredException: Type[BotocoreClientError]
     RegistrationCodeValidationException: Type[BotocoreClientError]
     ResourceAlreadyExistsException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ResourceRegistrationFailureException: Type[BotocoreClientError]
+    ServiceQuotaExceededException: Type[BotocoreClientError]
     ServiceUnavailableException: Type[BotocoreClientError]
     SqlParseException: Type[BotocoreClientError]
     TaskAlreadyExistsException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     TransferAlreadyCompletedException: Type[BotocoreClientError]
     TransferConflictException: Type[BotocoreClientError]
     UnauthorizedException: Type[BotocoreClientError]
+    ValidationException: Type[BotocoreClientError]
     VersionConflictException: Type[BotocoreClientError]
     VersionsLimitExceededException: Type[BotocoreClientError]
 
 
 class IoTClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client)
@@ -668,15 +686,16 @@
         *,
         domainConfigurationName: str,
         domainName: str = ...,
         serverCertificateArns: Sequence[str] = ...,
         validationCertificateArn: str = ...,
         authorizerConfig: AuthorizerConfigTypeDef = ...,
         serviceType: ServiceTypeType = ...,
-        tags: Sequence[TagTypeDef] = ...
+        tags: Sequence[TagTypeDef] = ...,
+        tlsConfig: TlsConfigTypeDef = ...
     ) -> CreateDomainConfigurationResponseTypeDef:
         """
         Creates a domain configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_domain_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#create_domain_configuration)
         """
@@ -733,15 +752,16 @@
         abortConfig: AbortConfigTypeDef = ...,
         timeoutConfig: TimeoutConfigTypeDef = ...,
         tags: Sequence[TagTypeDef] = ...,
         namespaceId: str = ...,
         jobTemplateArn: str = ...,
         jobExecutionsRetryConfig: JobExecutionsRetryConfigTypeDef = ...,
         documentParameters: Mapping[str, str] = ...,
-        schedulingConfig: SchedulingConfigTypeDef = ...
+        schedulingConfig: SchedulingConfigTypeDef = ...,
+        destinationPackageVersions: Sequence[str] = ...
     ) -> CreateJobResponseTypeDef:
         """
         Creates a job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#create_job)
         """
@@ -755,15 +775,17 @@
         documentSource: str = ...,
         document: str = ...,
         presignedUrlConfig: PresignedUrlConfigTypeDef = ...,
         jobExecutionsRolloutConfig: JobExecutionsRolloutConfigTypeDef = ...,
         abortConfig: AbortConfigTypeDef = ...,
         timeoutConfig: TimeoutConfigTypeDef = ...,
         tags: Sequence[TagTypeDef] = ...,
-        jobExecutionsRetryConfig: JobExecutionsRetryConfigTypeDef = ...
+        jobExecutionsRetryConfig: JobExecutionsRetryConfigTypeDef = ...,
+        maintenanceWindows: Sequence[MaintenanceWindowTypeDef] = ...,
+        destinationPackageVersions: Sequence[str] = ...
     ) -> CreateJobTemplateResponseTypeDef:
         """
         Creates a job template.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_job_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#create_job_template)
         """
@@ -815,14 +837,46 @@
         """
         Creates an IoT OTA update on a target group of things or groups.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_ota_update)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#create_ota_update)
         """
 
+    async def create_package(
+        self,
+        *,
+        packageName: str,
+        description: str = ...,
+        tags: Mapping[str, str] = ...,
+        clientToken: str = ...
+    ) -> CreatePackageResponseTypeDef:
+        """
+        Creates an IoT software package that can be deployed to your fleet.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_package)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#create_package)
+        """
+
+    async def create_package_version(
+        self,
+        *,
+        packageName: str,
+        versionName: str,
+        description: str = ...,
+        attributes: Mapping[str, str] = ...,
+        tags: Mapping[str, str] = ...,
+        clientToken: str = ...
+    ) -> CreatePackageVersionResponseTypeDef:
+        """
+        Creates a new version for an existing IoT software package.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_package_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#create_package_version)
+        """
+
     async def create_policy(
         self, *, policyName: str, policyDocument: str, tags: Sequence[TagTypeDef] = ...
     ) -> CreatePolicyResponseTypeDef:
         """
         Creates an IoT policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_policy)
@@ -1156,14 +1210,32 @@
         """
         Delete an OTA update.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_ota_update)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#delete_ota_update)
         """
 
+    async def delete_package(self, *, packageName: str, clientToken: str = ...) -> Dict[str, Any]:
+        """
+        Deletes a specific version from a software package.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_package)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#delete_package)
+        """
+
+    async def delete_package_version(
+        self, *, packageName: str, versionName: str, clientToken: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Deletes a specific version from a software package.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_package_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#delete_package_version)
+        """
+
     async def delete_policy(self, *, policyName: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the specified policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#delete_policy)
         """
@@ -1761,14 +1833,40 @@
         """
         Gets an OTA update.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_ota_update)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_ota_update)
         """
 
+    async def get_package(self, *, packageName: str) -> GetPackageResponseTypeDef:
+        """
+        Gets information about the specified software package.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_package)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_package)
+        """
+
+    async def get_package_configuration(self) -> GetPackageConfigurationResponseTypeDef:
+        """
+        Gets information about the specified software package's configuration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_package_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_package_configuration)
+        """
+
+    async def get_package_version(
+        self, *, packageName: str, versionName: str
+    ) -> GetPackageVersionResponseTypeDef:
+        """
+        Gets information about the specified package version.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_package_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_package_version)
+        """
+
     async def get_percentiles(
         self,
         *,
         queryString: str,
         indexName: str = ...,
         aggregationField: str = ...,
         queryVersion: str = ...,
@@ -2241,14 +2339,39 @@
         """
         Lists certificates that are being transferred but not yet accepted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_outgoing_certificates)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#list_outgoing_certificates)
         """
 
+    async def list_package_versions(
+        self,
+        *,
+        packageName: str,
+        status: PackageVersionStatusType = ...,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> ListPackageVersionsResponseTypeDef:
+        """
+        Lists the software package versions associated to the account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_package_versions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#list_package_versions)
+        """
+
+    async def list_packages(
+        self, *, maxResults: int = ..., nextToken: str = ...
+    ) -> ListPackagesResponseTypeDef:
+        """
+        Lists the software packages associated to the account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_packages)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#list_packages)
+        """
+
     async def list_policies(
         self, *, marker: str = ..., pageSize: int = ..., ascendingOrder: bool = ...
     ) -> ListPoliciesResponseTypeDef:
         """
         Lists your policies.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_policies)
@@ -3004,15 +3127,16 @@
 
     async def update_domain_configuration(
         self,
         *,
         domainConfigurationName: str,
         authorizerConfig: AuthorizerConfigTypeDef = ...,
         domainConfigurationStatus: DomainConfigurationStatusType = ...,
-        removeAuthorizerConfig: bool = ...
+        removeAuthorizerConfig: bool = ...,
+        tlsConfig: TlsConfigTypeDef = ...
     ) -> UpdateDomainConfigurationResponseTypeDef:
         """
         Updates values stored in the domain configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_domain_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#update_domain_configuration)
         """
@@ -3107,14 +3231,60 @@
         """
         Updates the definition for the specified mitigation action.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_mitigation_action)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#update_mitigation_action)
         """
 
+    async def update_package(
+        self,
+        *,
+        packageName: str,
+        description: str = ...,
+        defaultVersionName: str = ...,
+        unsetDefaultVersion: bool = ...,
+        clientToken: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Updates the supported fields for a specific package.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_package)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#update_package)
+        """
+
+    async def update_package_configuration(
+        self,
+        *,
+        versionUpdateByJobsConfig: VersionUpdateByJobsConfigTypeDef = ...,
+        clientToken: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Updates the package configuration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_package_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#update_package_configuration)
+        """
+
+    async def update_package_version(
+        self,
+        *,
+        packageName: str,
+        versionName: str,
+        description: str = ...,
+        attributes: Mapping[str, str] = ...,
+        action: PackageVersionActionType = ...,
+        clientToken: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Updates the supported fields for a specific package version.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_package_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#update_package_version)
+        """
+
     async def update_provisioning_template(
         self,
         *,
         templateName: str,
         description: str = ...,
         enabled: bool = ...,
         defaultVersionId: int = ...,
@@ -3463,14 +3633,23 @@
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
         """
 
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_managed_job_templates"]
+    ) -> ListManagedJobTemplatesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_metric_values"]
     ) -> ListMetricValuesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
         """
 
@@ -3496,14 +3675,30 @@
     ) -> ListOutgoingCertificatesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
         """
 
     @overload
+    def get_paginator(
+        self, operation_name: Literal["list_package_versions"]
+    ) -> ListPackageVersionsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(self, operation_name: Literal["list_packages"]) -> ListPackagesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
+        """
+
+    @overload
     def get_paginator(self, operation_name: Literal["list_policies"]) -> ListPoliciesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
         """
 
     @overload
@@ -3549,14 +3744,23 @@
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
         """
 
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_related_resources_for_audit_finding"]
+    ) -> ListRelatedResourcesForAuditFindingPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_role_aliases"]
     ) -> ListRoleAliasesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
         """
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/client.pyi` & `types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -41,14 +41,16 @@
     FleetMetricUnitType,
     JobExecutionStatusType,
     JobStatusType,
     LogLevelType,
     LogTargetTypeType,
     MitigationActionTypeType,
     OTAUpdateStatusType,
+    PackageVersionActionType,
+    PackageVersionStatusType,
     ProtocolType,
     ReportTypeType,
     ServiceTypeType,
     StatusType,
     TargetSelectionType,
     TemplateTypeType,
     TopicRuleDestinationStatusType,
@@ -75,24 +77,28 @@
     ListDomainConfigurationsPaginator,
     ListFleetMetricsPaginator,
     ListIndicesPaginator,
     ListJobExecutionsForJobPaginator,
     ListJobExecutionsForThingPaginator,
     ListJobsPaginator,
     ListJobTemplatesPaginator,
+    ListManagedJobTemplatesPaginator,
     ListMetricValuesPaginator,
     ListMitigationActionsPaginator,
     ListOTAUpdatesPaginator,
     ListOutgoingCertificatesPaginator,
+    ListPackagesPaginator,
+    ListPackageVersionsPaginator,
     ListPoliciesPaginator,
     ListPolicyPrincipalsPaginator,
     ListPrincipalPoliciesPaginator,
     ListPrincipalThingsPaginator,
     ListProvisioningTemplatesPaginator,
     ListProvisioningTemplateVersionsPaginator,
+    ListRelatedResourcesForAuditFindingPaginator,
     ListRoleAliasesPaginator,
     ListScheduledAuditsPaginator,
     ListSecurityProfilesForTargetPaginator,
     ListSecurityProfilesPaginator,
     ListStreamsPaginator,
     ListTagsForResourcePaginator,
     ListTargetsForPolicyPaginator,
@@ -140,14 +146,16 @@
     CreateDynamicThingGroupResponseTypeDef,
     CreateFleetMetricResponseTypeDef,
     CreateJobResponseTypeDef,
     CreateJobTemplateResponseTypeDef,
     CreateKeysAndCertificateResponseTypeDef,
     CreateMitigationActionResponseTypeDef,
     CreateOTAUpdateResponseTypeDef,
+    CreatePackageResponseTypeDef,
+    CreatePackageVersionResponseTypeDef,
     CreatePolicyResponseTypeDef,
     CreatePolicyVersionResponseTypeDef,
     CreateProvisioningClaimResponseTypeDef,
     CreateProvisioningTemplateResponseTypeDef,
     CreateProvisioningTemplateVersionResponseTypeDef,
     CreateRoleAliasResponseTypeDef,
     CreateScheduledAuditResponseTypeDef,
@@ -196,14 +204,17 @@
     GetBucketsAggregationResponseTypeDef,
     GetCardinalityResponseTypeDef,
     GetEffectivePoliciesResponseTypeDef,
     GetIndexingConfigurationResponseTypeDef,
     GetJobDocumentResponseTypeDef,
     GetLoggingOptionsResponseTypeDef,
     GetOTAUpdateResponseTypeDef,
+    GetPackageConfigurationResponseTypeDef,
+    GetPackageResponseTypeDef,
+    GetPackageVersionResponseTypeDef,
     GetPercentilesResponseTypeDef,
     GetPolicyResponseTypeDef,
     GetPolicyVersionResponseTypeDef,
     GetRegistrationCodeResponseTypeDef,
     GetStatisticsResponseTypeDef,
     GetTopicRuleDestinationResponseTypeDef,
     GetTopicRuleResponseTypeDef,
@@ -235,14 +246,16 @@
     ListJobsResponseTypeDef,
     ListJobTemplatesResponseTypeDef,
     ListManagedJobTemplatesResponseTypeDef,
     ListMetricValuesResponseTypeDef,
     ListMitigationActionsResponseTypeDef,
     ListOTAUpdatesResponseTypeDef,
     ListOutgoingCertificatesResponseTypeDef,
+    ListPackagesResponseTypeDef,
+    ListPackageVersionsResponseTypeDef,
     ListPoliciesResponseTypeDef,
     ListPolicyPrincipalsResponseTypeDef,
     ListPolicyVersionsResponseTypeDef,
     ListPrincipalPoliciesResponseTypeDef,
     ListPrincipalThingsResponseTypeDef,
     ListProvisioningTemplatesResponseTypeDef,
     ListProvisioningTemplateVersionsResponseTypeDef,
@@ -266,14 +279,15 @@
     ListThingTypesResponseTypeDef,
     ListTopicRuleDestinationsResponseTypeDef,
     ListTopicRulesResponseTypeDef,
     ListV2LoggingLevelsResponseTypeDef,
     ListViolationEventsResponseTypeDef,
     LoggingOptionsPayloadTypeDef,
     LogTargetTypeDef,
+    MaintenanceWindowTypeDef,
     MetricToRetainTypeDef,
     MitigationActionParamsTypeDef,
     MqttContextTypeDef,
     OTAUpdateFileTypeDef,
     PresignedUrlConfigTypeDef,
     ProvisioningHookTypeDef,
     RegisterCACertificateResponseTypeDef,
@@ -294,14 +308,15 @@
     TestAuthorizationResponseTypeDef,
     TestInvokeAuthorizerResponseTypeDef,
     ThingGroupIndexingConfigurationTypeDef,
     ThingGroupPropertiesTypeDef,
     ThingIndexingConfigurationTypeDef,
     ThingTypePropertiesTypeDef,
     TimeoutConfigTypeDef,
+    TlsConfigTypeDef,
     TlsContextTypeDef,
     TopicRuleDestinationConfigurationTypeDef,
     TopicRulePayloadTypeDef,
     TransferCertificateResponseTypeDef,
     UpdateAuthorizerResponseTypeDef,
     UpdateBillingGroupResponseTypeDef,
     UpdateCustomMetricResponseTypeDef,
@@ -311,14 +326,15 @@
     UpdateMitigationActionResponseTypeDef,
     UpdateRoleAliasResponseTypeDef,
     UpdateScheduledAuditResponseTypeDef,
     UpdateSecurityProfileResponseTypeDef,
     UpdateStreamResponseTypeDef,
     UpdateThingGroupResponseTypeDef,
     ValidateSecurityProfileBehaviorsResponseTypeDef,
+    VersionUpdateByJobsConfigTypeDef,
     ViolationEventOccurrenceRangeTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -352,21 +368,23 @@
     LimitExceededException: Type[BotocoreClientError]
     MalformedPolicyException: Type[BotocoreClientError]
     NotConfiguredException: Type[BotocoreClientError]
     RegistrationCodeValidationException: Type[BotocoreClientError]
     ResourceAlreadyExistsException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ResourceRegistrationFailureException: Type[BotocoreClientError]
+    ServiceQuotaExceededException: Type[BotocoreClientError]
     ServiceUnavailableException: Type[BotocoreClientError]
     SqlParseException: Type[BotocoreClientError]
     TaskAlreadyExistsException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     TransferAlreadyCompletedException: Type[BotocoreClientError]
     TransferConflictException: Type[BotocoreClientError]
     UnauthorizedException: Type[BotocoreClientError]
+    ValidationException: Type[BotocoreClientError]
     VersionConflictException: Type[BotocoreClientError]
     VersionsLimitExceededException: Type[BotocoreClientError]
 
 class IoTClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/)
@@ -639,15 +657,16 @@
         *,
         domainConfigurationName: str,
         domainName: str = ...,
         serverCertificateArns: Sequence[str] = ...,
         validationCertificateArn: str = ...,
         authorizerConfig: AuthorizerConfigTypeDef = ...,
         serviceType: ServiceTypeType = ...,
-        tags: Sequence[TagTypeDef] = ...
+        tags: Sequence[TagTypeDef] = ...,
+        tlsConfig: TlsConfigTypeDef = ...
     ) -> CreateDomainConfigurationResponseTypeDef:
         """
         Creates a domain configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_domain_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#create_domain_configuration)
         """
@@ -701,15 +720,16 @@
         abortConfig: AbortConfigTypeDef = ...,
         timeoutConfig: TimeoutConfigTypeDef = ...,
         tags: Sequence[TagTypeDef] = ...,
         namespaceId: str = ...,
         jobTemplateArn: str = ...,
         jobExecutionsRetryConfig: JobExecutionsRetryConfigTypeDef = ...,
         documentParameters: Mapping[str, str] = ...,
-        schedulingConfig: SchedulingConfigTypeDef = ...
+        schedulingConfig: SchedulingConfigTypeDef = ...,
+        destinationPackageVersions: Sequence[str] = ...
     ) -> CreateJobResponseTypeDef:
         """
         Creates a job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#create_job)
         """
@@ -722,15 +742,17 @@
         documentSource: str = ...,
         document: str = ...,
         presignedUrlConfig: PresignedUrlConfigTypeDef = ...,
         jobExecutionsRolloutConfig: JobExecutionsRolloutConfigTypeDef = ...,
         abortConfig: AbortConfigTypeDef = ...,
         timeoutConfig: TimeoutConfigTypeDef = ...,
         tags: Sequence[TagTypeDef] = ...,
-        jobExecutionsRetryConfig: JobExecutionsRetryConfigTypeDef = ...
+        jobExecutionsRetryConfig: JobExecutionsRetryConfigTypeDef = ...,
+        maintenanceWindows: Sequence[MaintenanceWindowTypeDef] = ...,
+        destinationPackageVersions: Sequence[str] = ...
     ) -> CreateJobTemplateResponseTypeDef:
         """
         Creates a job template.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_job_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#create_job_template)
         """
@@ -778,14 +800,44 @@
     ) -> CreateOTAUpdateResponseTypeDef:
         """
         Creates an IoT OTA update on a target group of things or groups.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_ota_update)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#create_ota_update)
         """
+    async def create_package(
+        self,
+        *,
+        packageName: str,
+        description: str = ...,
+        tags: Mapping[str, str] = ...,
+        clientToken: str = ...
+    ) -> CreatePackageResponseTypeDef:
+        """
+        Creates an IoT software package that can be deployed to your fleet.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_package)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#create_package)
+        """
+    async def create_package_version(
+        self,
+        *,
+        packageName: str,
+        versionName: str,
+        description: str = ...,
+        attributes: Mapping[str, str] = ...,
+        tags: Mapping[str, str] = ...,
+        clientToken: str = ...
+    ) -> CreatePackageVersionResponseTypeDef:
+        """
+        Creates a new version for an existing IoT software package.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_package_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#create_package_version)
+        """
     async def create_policy(
         self, *, policyName: str, policyDocument: str, tags: Sequence[TagTypeDef] = ...
     ) -> CreatePolicyResponseTypeDef:
         """
         Creates an IoT policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.create_policy)
@@ -1089,14 +1141,30 @@
     ) -> Dict[str, Any]:
         """
         Delete an OTA update.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_ota_update)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#delete_ota_update)
         """
+    async def delete_package(self, *, packageName: str, clientToken: str = ...) -> Dict[str, Any]:
+        """
+        Deletes a specific version from a software package.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_package)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#delete_package)
+        """
+    async def delete_package_version(
+        self, *, packageName: str, versionName: str, clientToken: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Deletes a specific version from a software package.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_package_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#delete_package_version)
+        """
     async def delete_policy(self, *, policyName: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the specified policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.delete_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#delete_policy)
         """
@@ -1630,14 +1698,37 @@
     async def get_ota_update(self, *, otaUpdateId: str) -> GetOTAUpdateResponseTypeDef:
         """
         Gets an OTA update.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_ota_update)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_ota_update)
         """
+    async def get_package(self, *, packageName: str) -> GetPackageResponseTypeDef:
+        """
+        Gets information about the specified software package.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_package)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_package)
+        """
+    async def get_package_configuration(self) -> GetPackageConfigurationResponseTypeDef:
+        """
+        Gets information about the specified software package's configuration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_package_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_package_configuration)
+        """
+    async def get_package_version(
+        self, *, packageName: str, versionName: str
+    ) -> GetPackageVersionResponseTypeDef:
+        """
+        Gets information about the specified package version.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_package_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_package_version)
+        """
     async def get_percentiles(
         self,
         *,
         queryString: str,
         indexName: str = ...,
         aggregationField: str = ...,
         queryVersion: str = ...,
@@ -2074,14 +2165,37 @@
     ) -> ListOutgoingCertificatesResponseTypeDef:
         """
         Lists certificates that are being transferred but not yet accepted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_outgoing_certificates)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#list_outgoing_certificates)
         """
+    async def list_package_versions(
+        self,
+        *,
+        packageName: str,
+        status: PackageVersionStatusType = ...,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> ListPackageVersionsResponseTypeDef:
+        """
+        Lists the software package versions associated to the account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_package_versions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#list_package_versions)
+        """
+    async def list_packages(
+        self, *, maxResults: int = ..., nextToken: str = ...
+    ) -> ListPackagesResponseTypeDef:
+        """
+        Lists the software packages associated to the account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_packages)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#list_packages)
+        """
     async def list_policies(
         self, *, marker: str = ..., pageSize: int = ..., ascendingOrder: bool = ...
     ) -> ListPoliciesResponseTypeDef:
         """
         Lists your policies.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.list_policies)
@@ -2775,15 +2889,16 @@
         """
     async def update_domain_configuration(
         self,
         *,
         domainConfigurationName: str,
         authorizerConfig: AuthorizerConfigTypeDef = ...,
         domainConfigurationStatus: DomainConfigurationStatusType = ...,
-        removeAuthorizerConfig: bool = ...
+        removeAuthorizerConfig: bool = ...,
+        tlsConfig: TlsConfigTypeDef = ...
     ) -> UpdateDomainConfigurationResponseTypeDef:
         """
         Updates values stored in the domain configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_domain_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#update_domain_configuration)
         """
@@ -2871,14 +2986,57 @@
     ) -> UpdateMitigationActionResponseTypeDef:
         """
         Updates the definition for the specified mitigation action.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_mitigation_action)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#update_mitigation_action)
         """
+    async def update_package(
+        self,
+        *,
+        packageName: str,
+        description: str = ...,
+        defaultVersionName: str = ...,
+        unsetDefaultVersion: bool = ...,
+        clientToken: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Updates the supported fields for a specific package.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_package)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#update_package)
+        """
+    async def update_package_configuration(
+        self,
+        *,
+        versionUpdateByJobsConfig: VersionUpdateByJobsConfigTypeDef = ...,
+        clientToken: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Updates the package configuration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_package_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#update_package_configuration)
+        """
+    async def update_package_version(
+        self,
+        *,
+        packageName: str,
+        versionName: str,
+        description: str = ...,
+        attributes: Mapping[str, str] = ...,
+        action: PackageVersionActionType = ...,
+        clientToken: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Updates the supported fields for a specific package version.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.update_package_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#update_package_version)
+        """
     async def update_provisioning_template(
         self,
         *,
         templateName: str,
         description: str = ...,
         enabled: bool = ...,
         defaultVersionId: int = ...,
@@ -3193,14 +3351,22 @@
     def get_paginator(self, operation_name: Literal["list_jobs"]) -> ListJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
         """
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_managed_job_templates"]
+    ) -> ListManagedJobTemplatesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_metric_values"]
     ) -> ListMetricValuesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
         """
     @overload
@@ -3222,14 +3388,28 @@
         self, operation_name: Literal["list_outgoing_certificates"]
     ) -> ListOutgoingCertificatesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
         """
     @overload
+    def get_paginator(
+        self, operation_name: Literal["list_package_versions"]
+    ) -> ListPackageVersionsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(self, operation_name: Literal["list_packages"]) -> ListPackagesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
+        """
+    @overload
     def get_paginator(self, operation_name: Literal["list_policies"]) -> ListPoliciesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
         """
     @overload
     def get_paginator(
@@ -3269,14 +3449,22 @@
     ) -> ListProvisioningTemplatesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
         """
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_related_resources_for_audit_finding"]
+    ) -> ListRelatedResourcesForAuditFindingPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_role_aliases"]
     ) -> ListRoleAliasesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/client/#get_paginator)
         """
     @overload
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/literals.py` & `types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -85,24 +85,28 @@
     "ListDomainConfigurationsPaginatorName",
     "ListFleetMetricsPaginatorName",
     "ListIndicesPaginatorName",
     "ListJobExecutionsForJobPaginatorName",
     "ListJobExecutionsForThingPaginatorName",
     "ListJobTemplatesPaginatorName",
     "ListJobsPaginatorName",
+    "ListManagedJobTemplatesPaginatorName",
     "ListMetricValuesPaginatorName",
     "ListMitigationActionsPaginatorName",
     "ListOTAUpdatesPaginatorName",
     "ListOutgoingCertificatesPaginatorName",
+    "ListPackageVersionsPaginatorName",
+    "ListPackagesPaginatorName",
     "ListPoliciesPaginatorName",
     "ListPolicyPrincipalsPaginatorName",
     "ListPrincipalPoliciesPaginatorName",
     "ListPrincipalThingsPaginatorName",
     "ListProvisioningTemplateVersionsPaginatorName",
     "ListProvisioningTemplatesPaginatorName",
+    "ListRelatedResourcesForAuditFindingPaginatorName",
     "ListRoleAliasesPaginatorName",
     "ListScheduledAuditsPaginatorName",
     "ListSecurityProfilesForTargetPaginatorName",
     "ListSecurityProfilesPaginatorName",
     "ListStreamsPaginatorName",
     "ListTagsForResourcePaginatorName",
     "ListTargetsForPolicyPaginatorName",
@@ -123,14 +127,16 @@
     "LogLevelType",
     "LogTargetTypeType",
     "MessageFormatType",
     "MitigationActionTypeType",
     "ModelStatusType",
     "NamedShadowIndexingModeType",
     "OTAUpdateStatusType",
+    "PackageVersionActionType",
+    "PackageVersionStatusType",
     "PolicyTemplateNameType",
     "ProtocolType",
     "ReportTypeType",
     "ResourceTypeType",
     "RetryableFailureTypeType",
     "ServerCertificateStatusType",
     "ServiceTypeType",
@@ -295,24 +301,30 @@
 ListDomainConfigurationsPaginatorName = Literal["list_domain_configurations"]
 ListFleetMetricsPaginatorName = Literal["list_fleet_metrics"]
 ListIndicesPaginatorName = Literal["list_indices"]
 ListJobExecutionsForJobPaginatorName = Literal["list_job_executions_for_job"]
 ListJobExecutionsForThingPaginatorName = Literal["list_job_executions_for_thing"]
 ListJobTemplatesPaginatorName = Literal["list_job_templates"]
 ListJobsPaginatorName = Literal["list_jobs"]
+ListManagedJobTemplatesPaginatorName = Literal["list_managed_job_templates"]
 ListMetricValuesPaginatorName = Literal["list_metric_values"]
 ListMitigationActionsPaginatorName = Literal["list_mitigation_actions"]
 ListOTAUpdatesPaginatorName = Literal["list_ota_updates"]
 ListOutgoingCertificatesPaginatorName = Literal["list_outgoing_certificates"]
+ListPackageVersionsPaginatorName = Literal["list_package_versions"]
+ListPackagesPaginatorName = Literal["list_packages"]
 ListPoliciesPaginatorName = Literal["list_policies"]
 ListPolicyPrincipalsPaginatorName = Literal["list_policy_principals"]
 ListPrincipalPoliciesPaginatorName = Literal["list_principal_policies"]
 ListPrincipalThingsPaginatorName = Literal["list_principal_things"]
 ListProvisioningTemplateVersionsPaginatorName = Literal["list_provisioning_template_versions"]
 ListProvisioningTemplatesPaginatorName = Literal["list_provisioning_templates"]
+ListRelatedResourcesForAuditFindingPaginatorName = Literal[
+    "list_related_resources_for_audit_finding"
+]
 ListRoleAliasesPaginatorName = Literal["list_role_aliases"]
 ListScheduledAuditsPaginatorName = Literal["list_scheduled_audits"]
 ListSecurityProfilesForTargetPaginatorName = Literal["list_security_profiles_for_target"]
 ListSecurityProfilesPaginatorName = Literal["list_security_profiles"]
 ListStreamsPaginatorName = Literal["list_streams"]
 ListTagsForResourcePaginatorName = Literal["list_tags_for_resource"]
 ListTargetsForPolicyPaginatorName = Literal["list_targets_for_policy"]
@@ -340,16 +352,23 @@
     "REPLACE_DEFAULT_POLICY_VERSION",
     "UPDATE_CA_CERTIFICATE",
     "UPDATE_DEVICE_CERTIFICATE",
 ]
 ModelStatusType = Literal["ACTIVE", "EXPIRED", "PENDING_BUILD"]
 NamedShadowIndexingModeType = Literal["OFF", "ON"]
 OTAUpdateStatusType = Literal[
-    "CREATE_COMPLETE", "CREATE_FAILED", "CREATE_IN_PROGRESS", "CREATE_PENDING"
+    "CREATE_COMPLETE",
+    "CREATE_FAILED",
+    "CREATE_IN_PROGRESS",
+    "CREATE_PENDING",
+    "DELETE_FAILED",
+    "DELETE_IN_PROGRESS",
 ]
+PackageVersionActionType = Literal["DEPRECATE", "PUBLISH"]
+PackageVersionStatusType = Literal["DEPRECATED", "DRAFT", "PUBLISHED"]
 PolicyTemplateNameType = Literal["BLANK_POLICY"]
 ProtocolType = Literal["HTTP", "MQTT"]
 ReportTypeType = Literal["ERRORS", "RESULTS"]
 ResourceTypeType = Literal[
     "ACCOUNT_SETTINGS",
     "CA_CERTIFICATE",
     "CLIENT_ID",
@@ -431,14 +450,15 @@
     "cloudwatch",
     "codeartifact",
     "codebuild",
     "codecatalyst",
     "codecommit",
     "codedeploy",
     "codeguru-reviewer",
+    "codeguru-security",
     "codeguruprofiler",
     "codepipeline",
     "codestar",
     "codestar-connections",
     "codestar-notifications",
     "cognito-identity",
     "cognito-idp",
@@ -517,14 +537,15 @@
     "honeycode",
     "iam",
     "identitystore",
     "imagebuilder",
     "importexport",
     "inspector",
     "inspector2",
+    "internetmonitor",
     "iot",
     "iot-data",
     "iot-jobs-data",
     "iot-roborunner",
     "iot1click-devices",
     "iot1click-projects",
     "iotanalytics",
@@ -535,14 +556,15 @@
     "iotfleetwise",
     "iotsecuretunneling",
     "iotsitewise",
     "iotthingsgraph",
     "iottwinmaker",
     "iotwireless",
     "ivs",
+    "ivs-realtime",
     "ivschat",
     "kafka",
     "kafkaconnect",
     "kendra",
     "kendra-ranking",
     "keyspaces",
     "kinesis",
@@ -578,14 +600,15 @@
     "marketplace-entitlement",
     "marketplacecommerceanalytics",
     "mediaconnect",
     "mediaconvert",
     "medialive",
     "mediapackage",
     "mediapackage-vod",
+    "mediapackagev2",
     "mediastore",
     "mediastore-data",
     "mediatailor",
     "memorydb",
     "meteringmarketplace",
     "mgh",
     "mgn",
@@ -604,16 +627,19 @@
     "oam",
     "omics",
     "opensearch",
     "opensearchserverless",
     "opsworks",
     "opsworkscm",
     "organizations",
+    "osis",
     "outposts",
     "panorama",
+    "payment-cryptography",
+    "payment-cryptography-data",
     "personalize",
     "personalize-events",
     "personalize-runtime",
     "pi",
     "pinpoint",
     "pinpoint-email",
     "pinpoint-sms-voice",
@@ -697,15 +723,17 @@
     "textract",
     "timestream-query",
     "timestream-write",
     "tnb",
     "transcribe",
     "transfer",
     "translate",
+    "verifiedpermissions",
     "voice-id",
+    "vpc-lattice",
     "waf",
     "waf-regional",
     "wafv2",
     "wellarchitected",
     "wisdom",
     "workdocs",
     "worklink",
@@ -748,24 +776,28 @@
     "list_domain_configurations",
     "list_fleet_metrics",
     "list_indices",
     "list_job_executions_for_job",
     "list_job_executions_for_thing",
     "list_job_templates",
     "list_jobs",
+    "list_managed_job_templates",
     "list_metric_values",
     "list_mitigation_actions",
     "list_ota_updates",
     "list_outgoing_certificates",
+    "list_package_versions",
+    "list_packages",
     "list_policies",
     "list_policy_principals",
     "list_principal_policies",
     "list_principal_things",
     "list_provisioning_template_versions",
     "list_provisioning_templates",
+    "list_related_resources_for_audit_finding",
     "list_role_aliases",
     "list_scheduled_audits",
     "list_security_profiles",
     "list_security_profiles_for_target",
     "list_streams",
     "list_tags_for_resource",
     "list_targets_for_policy",
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/literals.pyi` & `types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -84,24 +84,28 @@
     "ListDomainConfigurationsPaginatorName",
     "ListFleetMetricsPaginatorName",
     "ListIndicesPaginatorName",
     "ListJobExecutionsForJobPaginatorName",
     "ListJobExecutionsForThingPaginatorName",
     "ListJobTemplatesPaginatorName",
     "ListJobsPaginatorName",
+    "ListManagedJobTemplatesPaginatorName",
     "ListMetricValuesPaginatorName",
     "ListMitigationActionsPaginatorName",
     "ListOTAUpdatesPaginatorName",
     "ListOutgoingCertificatesPaginatorName",
+    "ListPackageVersionsPaginatorName",
+    "ListPackagesPaginatorName",
     "ListPoliciesPaginatorName",
     "ListPolicyPrincipalsPaginatorName",
     "ListPrincipalPoliciesPaginatorName",
     "ListPrincipalThingsPaginatorName",
     "ListProvisioningTemplateVersionsPaginatorName",
     "ListProvisioningTemplatesPaginatorName",
+    "ListRelatedResourcesForAuditFindingPaginatorName",
     "ListRoleAliasesPaginatorName",
     "ListScheduledAuditsPaginatorName",
     "ListSecurityProfilesForTargetPaginatorName",
     "ListSecurityProfilesPaginatorName",
     "ListStreamsPaginatorName",
     "ListTagsForResourcePaginatorName",
     "ListTargetsForPolicyPaginatorName",
@@ -122,14 +126,16 @@
     "LogLevelType",
     "LogTargetTypeType",
     "MessageFormatType",
     "MitigationActionTypeType",
     "ModelStatusType",
     "NamedShadowIndexingModeType",
     "OTAUpdateStatusType",
+    "PackageVersionActionType",
+    "PackageVersionStatusType",
     "PolicyTemplateNameType",
     "ProtocolType",
     "ReportTypeType",
     "ResourceTypeType",
     "RetryableFailureTypeType",
     "ServerCertificateStatusType",
     "ServiceTypeType",
@@ -293,24 +299,30 @@
 ListDomainConfigurationsPaginatorName = Literal["list_domain_configurations"]
 ListFleetMetricsPaginatorName = Literal["list_fleet_metrics"]
 ListIndicesPaginatorName = Literal["list_indices"]
 ListJobExecutionsForJobPaginatorName = Literal["list_job_executions_for_job"]
 ListJobExecutionsForThingPaginatorName = Literal["list_job_executions_for_thing"]
 ListJobTemplatesPaginatorName = Literal["list_job_templates"]
 ListJobsPaginatorName = Literal["list_jobs"]
+ListManagedJobTemplatesPaginatorName = Literal["list_managed_job_templates"]
 ListMetricValuesPaginatorName = Literal["list_metric_values"]
 ListMitigationActionsPaginatorName = Literal["list_mitigation_actions"]
 ListOTAUpdatesPaginatorName = Literal["list_ota_updates"]
 ListOutgoingCertificatesPaginatorName = Literal["list_outgoing_certificates"]
+ListPackageVersionsPaginatorName = Literal["list_package_versions"]
+ListPackagesPaginatorName = Literal["list_packages"]
 ListPoliciesPaginatorName = Literal["list_policies"]
 ListPolicyPrincipalsPaginatorName = Literal["list_policy_principals"]
 ListPrincipalPoliciesPaginatorName = Literal["list_principal_policies"]
 ListPrincipalThingsPaginatorName = Literal["list_principal_things"]
 ListProvisioningTemplateVersionsPaginatorName = Literal["list_provisioning_template_versions"]
 ListProvisioningTemplatesPaginatorName = Literal["list_provisioning_templates"]
+ListRelatedResourcesForAuditFindingPaginatorName = Literal[
+    "list_related_resources_for_audit_finding"
+]
 ListRoleAliasesPaginatorName = Literal["list_role_aliases"]
 ListScheduledAuditsPaginatorName = Literal["list_scheduled_audits"]
 ListSecurityProfilesForTargetPaginatorName = Literal["list_security_profiles_for_target"]
 ListSecurityProfilesPaginatorName = Literal["list_security_profiles"]
 ListStreamsPaginatorName = Literal["list_streams"]
 ListTagsForResourcePaginatorName = Literal["list_tags_for_resource"]
 ListTargetsForPolicyPaginatorName = Literal["list_targets_for_policy"]
@@ -338,16 +350,23 @@
     "REPLACE_DEFAULT_POLICY_VERSION",
     "UPDATE_CA_CERTIFICATE",
     "UPDATE_DEVICE_CERTIFICATE",
 ]
 ModelStatusType = Literal["ACTIVE", "EXPIRED", "PENDING_BUILD"]
 NamedShadowIndexingModeType = Literal["OFF", "ON"]
 OTAUpdateStatusType = Literal[
-    "CREATE_COMPLETE", "CREATE_FAILED", "CREATE_IN_PROGRESS", "CREATE_PENDING"
+    "CREATE_COMPLETE",
+    "CREATE_FAILED",
+    "CREATE_IN_PROGRESS",
+    "CREATE_PENDING",
+    "DELETE_FAILED",
+    "DELETE_IN_PROGRESS",
 ]
+PackageVersionActionType = Literal["DEPRECATE", "PUBLISH"]
+PackageVersionStatusType = Literal["DEPRECATED", "DRAFT", "PUBLISHED"]
 PolicyTemplateNameType = Literal["BLANK_POLICY"]
 ProtocolType = Literal["HTTP", "MQTT"]
 ReportTypeType = Literal["ERRORS", "RESULTS"]
 ResourceTypeType = Literal[
     "ACCOUNT_SETTINGS",
     "CA_CERTIFICATE",
     "CLIENT_ID",
@@ -429,14 +448,15 @@
     "cloudwatch",
     "codeartifact",
     "codebuild",
     "codecatalyst",
     "codecommit",
     "codedeploy",
     "codeguru-reviewer",
+    "codeguru-security",
     "codeguruprofiler",
     "codepipeline",
     "codestar",
     "codestar-connections",
     "codestar-notifications",
     "cognito-identity",
     "cognito-idp",
@@ -515,14 +535,15 @@
     "honeycode",
     "iam",
     "identitystore",
     "imagebuilder",
     "importexport",
     "inspector",
     "inspector2",
+    "internetmonitor",
     "iot",
     "iot-data",
     "iot-jobs-data",
     "iot-roborunner",
     "iot1click-devices",
     "iot1click-projects",
     "iotanalytics",
@@ -533,14 +554,15 @@
     "iotfleetwise",
     "iotsecuretunneling",
     "iotsitewise",
     "iotthingsgraph",
     "iottwinmaker",
     "iotwireless",
     "ivs",
+    "ivs-realtime",
     "ivschat",
     "kafka",
     "kafkaconnect",
     "kendra",
     "kendra-ranking",
     "keyspaces",
     "kinesis",
@@ -576,14 +598,15 @@
     "marketplace-entitlement",
     "marketplacecommerceanalytics",
     "mediaconnect",
     "mediaconvert",
     "medialive",
     "mediapackage",
     "mediapackage-vod",
+    "mediapackagev2",
     "mediastore",
     "mediastore-data",
     "mediatailor",
     "memorydb",
     "meteringmarketplace",
     "mgh",
     "mgn",
@@ -602,16 +625,19 @@
     "oam",
     "omics",
     "opensearch",
     "opensearchserverless",
     "opsworks",
     "opsworkscm",
     "organizations",
+    "osis",
     "outposts",
     "panorama",
+    "payment-cryptography",
+    "payment-cryptography-data",
     "personalize",
     "personalize-events",
     "personalize-runtime",
     "pi",
     "pinpoint",
     "pinpoint-email",
     "pinpoint-sms-voice",
@@ -695,15 +721,17 @@
     "textract",
     "timestream-query",
     "timestream-write",
     "tnb",
     "transcribe",
     "transfer",
     "translate",
+    "verifiedpermissions",
     "voice-id",
+    "vpc-lattice",
     "waf",
     "waf-regional",
     "wafv2",
     "wellarchitected",
     "wisdom",
     "workdocs",
     "worklink",
@@ -746,24 +774,28 @@
     "list_domain_configurations",
     "list_fleet_metrics",
     "list_indices",
     "list_job_executions_for_job",
     "list_job_executions_for_thing",
     "list_job_templates",
     "list_jobs",
+    "list_managed_job_templates",
     "list_metric_values",
     "list_mitigation_actions",
     "list_ota_updates",
     "list_outgoing_certificates",
+    "list_package_versions",
+    "list_packages",
     "list_policies",
     "list_policy_principals",
     "list_principal_policies",
     "list_principal_things",
     "list_provisioning_template_versions",
     "list_provisioning_templates",
+    "list_related_resources_for_audit_finding",
     "list_role_aliases",
     "list_scheduled_audits",
     "list_security_profiles",
     "list_security_profiles_for_target",
     "list_streams",
     "list_tags_for_resource",
     "list_targets_for_policy",
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/paginator.py` & `types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -30,24 +30,28 @@
         ListDomainConfigurationsPaginator,
         ListFleetMetricsPaginator,
         ListIndicesPaginator,
         ListJobExecutionsForJobPaginator,
         ListJobExecutionsForThingPaginator,
         ListJobTemplatesPaginator,
         ListJobsPaginator,
+        ListManagedJobTemplatesPaginator,
         ListMetricValuesPaginator,
         ListMitigationActionsPaginator,
         ListOTAUpdatesPaginator,
         ListOutgoingCertificatesPaginator,
+        ListPackageVersionsPaginator,
+        ListPackagesPaginator,
         ListPoliciesPaginator,
         ListPolicyPrincipalsPaginator,
         ListPrincipalPoliciesPaginator,
         ListPrincipalThingsPaginator,
         ListProvisioningTemplateVersionsPaginator,
         ListProvisioningTemplatesPaginator,
+        ListRelatedResourcesForAuditFindingPaginator,
         ListRoleAliasesPaginator,
         ListScheduledAuditsPaginator,
         ListSecurityProfilesPaginator,
         ListSecurityProfilesForTargetPaginator,
         ListStreamsPaginator,
         ListTagsForResourcePaginator,
         ListTargetsForPolicyPaginator,
@@ -91,24 +95,28 @@
         list_domain_configurations_paginator: ListDomainConfigurationsPaginator = client.get_paginator("list_domain_configurations")
         list_fleet_metrics_paginator: ListFleetMetricsPaginator = client.get_paginator("list_fleet_metrics")
         list_indices_paginator: ListIndicesPaginator = client.get_paginator("list_indices")
         list_job_executions_for_job_paginator: ListJobExecutionsForJobPaginator = client.get_paginator("list_job_executions_for_job")
         list_job_executions_for_thing_paginator: ListJobExecutionsForThingPaginator = client.get_paginator("list_job_executions_for_thing")
         list_job_templates_paginator: ListJobTemplatesPaginator = client.get_paginator("list_job_templates")
         list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
+        list_managed_job_templates_paginator: ListManagedJobTemplatesPaginator = client.get_paginator("list_managed_job_templates")
         list_metric_values_paginator: ListMetricValuesPaginator = client.get_paginator("list_metric_values")
         list_mitigation_actions_paginator: ListMitigationActionsPaginator = client.get_paginator("list_mitigation_actions")
         list_ota_updates_paginator: ListOTAUpdatesPaginator = client.get_paginator("list_ota_updates")
         list_outgoing_certificates_paginator: ListOutgoingCertificatesPaginator = client.get_paginator("list_outgoing_certificates")
+        list_package_versions_paginator: ListPackageVersionsPaginator = client.get_paginator("list_package_versions")
+        list_packages_paginator: ListPackagesPaginator = client.get_paginator("list_packages")
         list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
         list_policy_principals_paginator: ListPolicyPrincipalsPaginator = client.get_paginator("list_policy_principals")
         list_principal_policies_paginator: ListPrincipalPoliciesPaginator = client.get_paginator("list_principal_policies")
         list_principal_things_paginator: ListPrincipalThingsPaginator = client.get_paginator("list_principal_things")
         list_provisioning_template_versions_paginator: ListProvisioningTemplateVersionsPaginator = client.get_paginator("list_provisioning_template_versions")
         list_provisioning_templates_paginator: ListProvisioningTemplatesPaginator = client.get_paginator("list_provisioning_templates")
+        list_related_resources_for_audit_finding_paginator: ListRelatedResourcesForAuditFindingPaginator = client.get_paginator("list_related_resources_for_audit_finding")
         list_role_aliases_paginator: ListRoleAliasesPaginator = client.get_paginator("list_role_aliases")
         list_scheduled_audits_paginator: ListScheduledAuditsPaginator = client.get_paginator("list_scheduled_audits")
         list_security_profiles_paginator: ListSecurityProfilesPaginator = client.get_paginator("list_security_profiles")
         list_security_profiles_for_target_paginator: ListSecurityProfilesForTargetPaginator = client.get_paginator("list_security_profiles_for_target")
         list_streams_paginator: ListStreamsPaginator = client.get_paginator("list_streams")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         list_targets_for_policy_paginator: ListTargetsForPolicyPaginator = client.get_paginator("list_targets_for_policy")
@@ -124,17 +132,16 @@
         list_things_in_thing_group_paginator: ListThingsInThingGroupPaginator = client.get_paginator("list_things_in_thing_group")
         list_topic_rule_destinations_paginator: ListTopicRuleDestinationsPaginator = client.get_paginator("list_topic_rule_destinations")
         list_topic_rules_paginator: ListTopicRulesPaginator = client.get_paginator("list_topic_rules")
         list_v2_logging_levels_paginator: ListV2LoggingLevelsPaginator = client.get_paginator("list_v2_logging_levels")
         list_violation_events_paginator: ListViolationEventsPaginator = client.get_paginator("list_violation_events")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     AuditMitigationActionsExecutionStatusType,
     AuditMitigationActionsTaskStatusType,
@@ -144,14 +151,15 @@
     BehaviorCriteriaTypeType,
     DimensionValueOperatorType,
     JobExecutionStatusType,
     JobStatusType,
     LogTargetTypeType,
     MitigationActionTypeType,
     OTAUpdateStatusType,
+    PackageVersionStatusType,
     ReportTypeType,
     ServiceTypeType,
     StatusType,
     TargetSelectionType,
     VerificationStateType,
 )
 from .type_defs import (
@@ -175,24 +183,28 @@
     ListDomainConfigurationsResponseTypeDef,
     ListFleetMetricsResponseTypeDef,
     ListIndicesResponseTypeDef,
     ListJobExecutionsForJobResponseTypeDef,
     ListJobExecutionsForThingResponseTypeDef,
     ListJobsResponseTypeDef,
     ListJobTemplatesResponseTypeDef,
+    ListManagedJobTemplatesResponseTypeDef,
     ListMetricValuesResponseTypeDef,
     ListMitigationActionsResponseTypeDef,
     ListOTAUpdatesResponseTypeDef,
     ListOutgoingCertificatesResponseTypeDef,
+    ListPackagesResponseTypeDef,
+    ListPackageVersionsResponseTypeDef,
     ListPoliciesResponseTypeDef,
     ListPolicyPrincipalsResponseTypeDef,
     ListPrincipalPoliciesResponseTypeDef,
     ListPrincipalThingsResponseTypeDef,
     ListProvisioningTemplatesResponseTypeDef,
     ListProvisioningTemplateVersionsResponseTypeDef,
+    ListRelatedResourcesForAuditFindingResponseTypeDef,
     ListRoleAliasesResponseTypeDef,
     ListScheduledAuditsResponseTypeDef,
     ListSecurityProfilesForTargetResponseTypeDef,
     ListSecurityProfilesResponseTypeDef,
     ListStreamsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTargetsForPolicyResponseTypeDef,
@@ -210,20 +222,14 @@
     ListTopicRulesResponseTypeDef,
     ListV2LoggingLevelsResponseTypeDef,
     ListViolationEventsResponseTypeDef,
     PaginatorConfigTypeDef,
     ResourceIdentifierTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetBehaviorModelTrainingSummariesPaginator",
     "ListActiveViolationsPaginator",
     "ListAttachedPoliciesPaginator",
     "ListAuditFindingsPaginator",
     "ListAuditMitigationActionsExecutionsPaginator",
     "ListAuditMitigationActionsTasksPaginator",
@@ -241,24 +247,28 @@
     "ListDomainConfigurationsPaginator",
     "ListFleetMetricsPaginator",
     "ListIndicesPaginator",
     "ListJobExecutionsForJobPaginator",
     "ListJobExecutionsForThingPaginator",
     "ListJobTemplatesPaginator",
     "ListJobsPaginator",
+    "ListManagedJobTemplatesPaginator",
     "ListMetricValuesPaginator",
     "ListMitigationActionsPaginator",
     "ListOTAUpdatesPaginator",
     "ListOutgoingCertificatesPaginator",
+    "ListPackageVersionsPaginator",
+    "ListPackagesPaginator",
     "ListPoliciesPaginator",
     "ListPolicyPrincipalsPaginator",
     "ListPrincipalPoliciesPaginator",
     "ListPrincipalThingsPaginator",
     "ListProvisioningTemplateVersionsPaginator",
     "ListProvisioningTemplatesPaginator",
+    "ListRelatedResourcesForAuditFindingPaginator",
     "ListRoleAliasesPaginator",
     "ListScheduledAuditsPaginator",
     "ListSecurityProfilesPaginator",
     "ListSecurityProfilesForTargetPaginator",
     "ListStreamsPaginator",
     "ListTagsForResourcePaginator",
     "ListTargetsForPolicyPaginator",
@@ -292,15 +302,15 @@
 class GetBehaviorModelTrainingSummariesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.GetBehaviorModelTrainingSummaries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#getbehaviormodeltrainingsummariespaginator)
     """
 
     def paginate(
-        self, *, securityProfileName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, securityProfileName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBehaviorModelTrainingSummariesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.GetBehaviorModelTrainingSummaries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#getbehaviormodeltrainingsummariespaginator)
         """
 
 
@@ -314,30 +324,34 @@
         self,
         *,
         thingName: str = ...,
         securityProfileName: str = ...,
         behaviorCriteriaType: BehaviorCriteriaTypeType = ...,
         listSuppressedAlerts: bool = ...,
         verificationState: VerificationStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListActiveViolationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListActiveViolations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listactiveviolationspaginator)
         """
 
 
 class ListAttachedPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAttachedPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listattachedpoliciespaginator)
     """
 
     def paginate(
-        self, *, target: str, recursive: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        target: str,
+        recursive: bool = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttachedPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAttachedPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listattachedpoliciespaginator)
         """
 
 
@@ -352,15 +366,15 @@
         *,
         taskId: str = ...,
         checkName: str = ...,
         resourceIdentifier: ResourceIdentifierTypeDef = ...,
         startTime: Union[datetime, str] = ...,
         endTime: Union[datetime, str] = ...,
         listSuppressedFindings: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAuditFindingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAuditFindings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listauditfindingspaginator)
         """
 
 
@@ -372,15 +386,15 @@
 
     def paginate(
         self,
         *,
         taskId: str,
         findingId: str,
         actionStatus: AuditMitigationActionsExecutionStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAuditMitigationActionsExecutionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAuditMitigationActionsExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listauditmitigationactionsexecutionspaginator)
         """
 
 
@@ -394,15 +408,15 @@
         self,
         *,
         startTime: Union[datetime, str],
         endTime: Union[datetime, str],
         auditTaskId: str = ...,
         findingId: str = ...,
         taskStatus: AuditMitigationActionsTaskStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAuditMitigationActionsTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAuditMitigationActionsTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listauditmitigationactionstaskspaginator)
         """
 
 
@@ -414,15 +428,15 @@
 
     def paginate(
         self,
         *,
         checkName: str = ...,
         resourceIdentifier: ResourceIdentifierTypeDef = ...,
         ascendingOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAuditSuppressionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAuditSuppressions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listauditsuppressionspaginator)
         """
 
 
@@ -435,15 +449,15 @@
     def paginate(
         self,
         *,
         startTime: Union[datetime, str],
         endTime: Union[datetime, str],
         taskType: AuditTaskTypeType = ...,
         taskStatus: AuditTaskStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAuditTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAuditTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listaudittaskspaginator)
         """
 
 
@@ -454,30 +468,30 @@
     """
 
     def paginate(
         self,
         *,
         ascendingOrder: bool = ...,
         status: AuthorizerStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAuthorizersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAuthorizers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listauthorizerspaginator)
         """
 
 
 class ListBillingGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListBillingGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listbillinggroupspaginator)
     """
 
     def paginate(
-        self, *, namePrefixFilter: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, namePrefixFilter: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBillingGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListBillingGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listbillinggroupspaginator)
         """
 
 
@@ -488,30 +502,30 @@
     """
 
     def paginate(
         self,
         *,
         ascendingOrder: bool = ...,
         templateName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCACertificatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListCACertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listcacertificatespaginator)
         """
 
 
 class ListCertificatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListCertificates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listcertificatespaginator)
     """
 
     def paginate(
-        self, *, ascendingOrder: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ascendingOrder: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCertificatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listcertificatespaginator)
         """
 
 
@@ -522,30 +536,30 @@
     """
 
     def paginate(
         self,
         *,
         caCertificateId: str,
         ascendingOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCertificatesByCAResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListCertificatesByCA.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listcertificatesbycapaginator)
         """
 
 
 class ListCustomMetricsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListCustomMetrics)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listcustommetricspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomMetricsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListCustomMetrics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listcustommetricspaginator)
         """
 
 
@@ -559,15 +573,15 @@
         self,
         *,
         taskId: str = ...,
         violationId: str = ...,
         thingName: str = ...,
         startTime: Union[datetime, str] = ...,
         endTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDetectMitigationActionsExecutionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListDetectMitigationActionsExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listdetectmitigationactionsexecutionspaginator)
         """
 
 
@@ -578,75 +592,78 @@
     """
 
     def paginate(
         self,
         *,
         startTime: Union[datetime, str],
         endTime: Union[datetime, str],
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDetectMitigationActionsTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListDetectMitigationActionsTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listdetectmitigationactionstaskspaginator)
         """
 
 
 class ListDimensionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListDimensions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listdimensionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDimensionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListDimensions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listdimensionspaginator)
         """
 
 
 class ListDomainConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListDomainConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listdomainconfigurationspaginator)
     """
 
     def paginate(
-        self, *, serviceType: ServiceTypeType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        serviceType: ServiceTypeType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDomainConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListDomainConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listdomainconfigurationspaginator)
         """
 
 
 class ListFleetMetricsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListFleetMetrics)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listfleetmetricspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFleetMetricsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListFleetMetrics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listfleetmetricspaginator)
         """
 
 
 class ListIndicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListIndices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listindicespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIndicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListIndices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listindicespaginator)
         """
 
 
@@ -657,15 +674,15 @@
     """
 
     def paginate(
         self,
         *,
         jobId: str,
         status: JobExecutionStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobExecutionsForJobResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListJobExecutionsForJob.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listjobexecutionsforjobpaginator)
         """
 
 
@@ -678,30 +695,30 @@
     def paginate(
         self,
         *,
         thingName: str,
         status: JobExecutionStatusType = ...,
         namespaceId: str = ...,
         jobId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobExecutionsForThingResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListJobExecutionsForThing.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listjobexecutionsforthingpaginator)
         """
 
 
 class ListJobTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListJobTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listjobtemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListJobTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listjobtemplatespaginator)
         """
 
 
@@ -715,22 +732,37 @@
         self,
         *,
         status: JobStatusType = ...,
         targetSelection: TargetSelectionType = ...,
         thingGroupName: str = ...,
         thingGroupId: str = ...,
         namespaceId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listjobspaginator)
         """
 
 
+class ListManagedJobTemplatesPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListManagedJobTemplates)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listmanagedjobtemplatespaginator)
+    """
+
+    def paginate(
+        self, *, templateName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListManagedJobTemplatesResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListManagedJobTemplates.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listmanagedjobtemplatespaginator)
+        """
+
+
 class ListMetricValuesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListMetricValues)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listmetricvaluespaginator)
     """
 
     def paginate(
@@ -738,15 +770,15 @@
         *,
         thingName: str,
         metricName: str,
         startTime: Union[datetime, str],
         endTime: Union[datetime, str],
         dimensionName: str = ...,
         dimensionValueOperator: DimensionValueOperatorType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMetricValuesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListMetricValues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listmetricvaluespaginator)
         """
 
 
@@ -756,15 +788,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listmitigationactionspaginator)
     """
 
     def paginate(
         self,
         *,
         actionType: MitigationActionTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMitigationActionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListMitigationActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listmitigationactionspaginator)
         """
 
 
@@ -774,45 +806,79 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listotaupdatespaginator)
     """
 
     def paginate(
         self,
         *,
         otaUpdateStatus: OTAUpdateStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOTAUpdatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListOTAUpdates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listotaupdatespaginator)
         """
 
 
 class ListOutgoingCertificatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListOutgoingCertificates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listoutgoingcertificatespaginator)
     """
 
     def paginate(
-        self, *, ascendingOrder: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ascendingOrder: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOutgoingCertificatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListOutgoingCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listoutgoingcertificatespaginator)
         """
 
 
+class ListPackageVersionsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPackageVersions)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listpackageversionspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        packageName: str,
+        status: PackageVersionStatusType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListPackageVersionsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPackageVersions.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listpackageversionspaginator)
+        """
+
+
+class ListPackagesPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPackages)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listpackagespaginator)
+    """
+
+    def paginate(
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListPackagesResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPackages.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listpackagespaginator)
+        """
+
+
 class ListPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listpoliciespaginator)
     """
 
     def paginate(
-        self, *, ascendingOrder: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ascendingOrder: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listpoliciespaginator)
         """
 
 
@@ -823,15 +889,15 @@
     """
 
     def paginate(
         self,
         *,
         policyName: str,
         ascendingOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPolicyPrincipalsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPolicyPrincipals.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listpolicyprincipalspaginator)
         """
 
 
@@ -842,90 +908,105 @@
     """
 
     def paginate(
         self,
         *,
         principal: str,
         ascendingOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPrincipalPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPrincipalPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listprincipalpoliciespaginator)
         """
 
 
 class ListPrincipalThingsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPrincipalThings)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listprincipalthingspaginator)
     """
 
     def paginate(
-        self, *, principal: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, principal: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPrincipalThingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPrincipalThings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listprincipalthingspaginator)
         """
 
 
 class ListProvisioningTemplateVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListProvisioningTemplateVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listprovisioningtemplateversionspaginator)
     """
 
     def paginate(
-        self, *, templateName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, templateName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProvisioningTemplateVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListProvisioningTemplateVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listprovisioningtemplateversionspaginator)
         """
 
 
 class ListProvisioningTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListProvisioningTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listprovisioningtemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProvisioningTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListProvisioningTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listprovisioningtemplatespaginator)
         """
 
 
+class ListRelatedResourcesForAuditFindingPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListRelatedResourcesForAuditFinding)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listrelatedresourcesforauditfindingpaginator)
+    """
+
+    def paginate(
+        self, *, findingId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListRelatedResourcesForAuditFindingResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListRelatedResourcesForAuditFinding.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listrelatedresourcesforauditfindingpaginator)
+        """
+
+
 class ListRoleAliasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListRoleAliases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listrolealiasespaginator)
     """
 
     def paginate(
-        self, *, ascendingOrder: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ascendingOrder: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRoleAliasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListRoleAliases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listrolealiasespaginator)
         """
 
 
 class ListScheduledAuditsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListScheduledAudits)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listscheduledauditspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListScheduledAuditsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListScheduledAudits.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listscheduledauditspaginator)
         """
 
 
@@ -936,15 +1017,15 @@
     """
 
     def paginate(
         self,
         *,
         dimensionName: str = ...,
         metricName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSecurityProfilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListSecurityProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listsecurityprofilespaginator)
         """
 
 
@@ -955,75 +1036,75 @@
     """
 
     def paginate(
         self,
         *,
         securityProfileTargetArn: str,
         recursive: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSecurityProfilesForTargetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListSecurityProfilesForTarget.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listsecurityprofilesfortargetpaginator)
         """
 
 
 class ListStreamsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListStreams)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#liststreamspaginator)
     """
 
     def paginate(
-        self, *, ascendingOrder: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ascendingOrder: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListStreams.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#liststreamspaginator)
         """
 
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtagsforresourcepaginator)
         """
 
 
 class ListTargetsForPolicyPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTargetsForPolicy)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtargetsforpolicypaginator)
     """
 
     def paginate(
-        self, *, policyName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, policyName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTargetsForPolicyResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTargetsForPolicy.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtargetsforpolicypaginator)
         """
 
 
 class ListTargetsForSecurityProfilePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTargetsForSecurityProfile)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtargetsforsecurityprofilepaginator)
     """
 
     def paginate(
-        self, *, securityProfileName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, securityProfileName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTargetsForSecurityProfileResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTargetsForSecurityProfile.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtargetsforsecurityprofilepaginator)
         """
 
 
@@ -1035,45 +1116,45 @@
 
     def paginate(
         self,
         *,
         parentGroup: str = ...,
         namePrefixFilter: str = ...,
         recursive: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthinggroupspaginator)
         """
 
 
 class ListThingGroupsForThingPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingGroupsForThing)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthinggroupsforthingpaginator)
     """
 
     def paginate(
-        self, *, thingName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, thingName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingGroupsForThingResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingGroupsForThing.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthinggroupsforthingpaginator)
         """
 
 
 class ListThingPrincipalsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingPrincipals)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingprincipalspaginator)
     """
 
     def paginate(
-        self, *, thingName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, thingName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingPrincipalsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingPrincipals.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingprincipalspaginator)
         """
 
 
@@ -1084,45 +1165,45 @@
     """
 
     def paginate(
         self,
         *,
         taskId: str,
         reportType: ReportTypeType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingRegistrationTaskReportsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingRegistrationTaskReports.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingregistrationtaskreportspaginator)
         """
 
 
 class ListThingRegistrationTasksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingRegistrationTasks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingregistrationtaskspaginator)
     """
 
     def paginate(
-        self, *, status: StatusType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, status: StatusType = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingRegistrationTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingRegistrationTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingregistrationtaskspaginator)
         """
 
 
 class ListThingTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingtypespaginator)
     """
 
     def paginate(
-        self, *, thingTypeName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, thingTypeName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingtypespaginator)
         """
 
 
@@ -1135,30 +1216,30 @@
     def paginate(
         self,
         *,
         attributeName: str = ...,
         attributeValue: str = ...,
         thingTypeName: str = ...,
         usePrefixAttributeValue: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingspaginator)
         """
 
 
 class ListThingsInBillingGroupPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingsInBillingGroup)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingsinbillinggrouppaginator)
     """
 
     def paginate(
-        self, *, billingGroupName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, billingGroupName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingsInBillingGroupResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingsInBillingGroup.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingsinbillinggrouppaginator)
         """
 
 
@@ -1169,30 +1250,30 @@
     """
 
     def paginate(
         self,
         *,
         thingGroupName: str,
         recursive: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingsInThingGroupResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingsInThingGroup.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingsinthinggrouppaginator)
         """
 
 
 class ListTopicRuleDestinationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTopicRuleDestinations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtopicruledestinationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTopicRuleDestinationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTopicRuleDestinations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtopicruledestinationspaginator)
         """
 
 
@@ -1203,30 +1284,33 @@
     """
 
     def paginate(
         self,
         *,
         topic: str = ...,
         ruleDisabled: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTopicRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTopicRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtopicrulespaginator)
         """
 
 
 class ListV2LoggingLevelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListV2LoggingLevels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listv2logginglevelspaginator)
     """
 
     def paginate(
-        self, *, targetType: LogTargetTypeType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        targetType: LogTargetTypeType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListV2LoggingLevelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListV2LoggingLevels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listv2logginglevelspaginator)
         """
 
 
@@ -1242,13 +1326,13 @@
         startTime: Union[datetime, str],
         endTime: Union[datetime, str],
         thingName: str = ...,
         securityProfileName: str = ...,
         behaviorCriteriaType: BehaviorCriteriaTypeType = ...,
         listSuppressedAlerts: bool = ...,
         verificationState: VerificationStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListViolationEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListViolationEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listviolationeventspaginator)
         """
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/paginator.pyi` & `types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -30,24 +30,28 @@
         ListDomainConfigurationsPaginator,
         ListFleetMetricsPaginator,
         ListIndicesPaginator,
         ListJobExecutionsForJobPaginator,
         ListJobExecutionsForThingPaginator,
         ListJobTemplatesPaginator,
         ListJobsPaginator,
+        ListManagedJobTemplatesPaginator,
         ListMetricValuesPaginator,
         ListMitigationActionsPaginator,
         ListOTAUpdatesPaginator,
         ListOutgoingCertificatesPaginator,
+        ListPackageVersionsPaginator,
+        ListPackagesPaginator,
         ListPoliciesPaginator,
         ListPolicyPrincipalsPaginator,
         ListPrincipalPoliciesPaginator,
         ListPrincipalThingsPaginator,
         ListProvisioningTemplateVersionsPaginator,
         ListProvisioningTemplatesPaginator,
+        ListRelatedResourcesForAuditFindingPaginator,
         ListRoleAliasesPaginator,
         ListScheduledAuditsPaginator,
         ListSecurityProfilesPaginator,
         ListSecurityProfilesForTargetPaginator,
         ListStreamsPaginator,
         ListTagsForResourcePaginator,
         ListTargetsForPolicyPaginator,
@@ -91,24 +95,28 @@
         list_domain_configurations_paginator: ListDomainConfigurationsPaginator = client.get_paginator("list_domain_configurations")
         list_fleet_metrics_paginator: ListFleetMetricsPaginator = client.get_paginator("list_fleet_metrics")
         list_indices_paginator: ListIndicesPaginator = client.get_paginator("list_indices")
         list_job_executions_for_job_paginator: ListJobExecutionsForJobPaginator = client.get_paginator("list_job_executions_for_job")
         list_job_executions_for_thing_paginator: ListJobExecutionsForThingPaginator = client.get_paginator("list_job_executions_for_thing")
         list_job_templates_paginator: ListJobTemplatesPaginator = client.get_paginator("list_job_templates")
         list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
+        list_managed_job_templates_paginator: ListManagedJobTemplatesPaginator = client.get_paginator("list_managed_job_templates")
         list_metric_values_paginator: ListMetricValuesPaginator = client.get_paginator("list_metric_values")
         list_mitigation_actions_paginator: ListMitigationActionsPaginator = client.get_paginator("list_mitigation_actions")
         list_ota_updates_paginator: ListOTAUpdatesPaginator = client.get_paginator("list_ota_updates")
         list_outgoing_certificates_paginator: ListOutgoingCertificatesPaginator = client.get_paginator("list_outgoing_certificates")
+        list_package_versions_paginator: ListPackageVersionsPaginator = client.get_paginator("list_package_versions")
+        list_packages_paginator: ListPackagesPaginator = client.get_paginator("list_packages")
         list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
         list_policy_principals_paginator: ListPolicyPrincipalsPaginator = client.get_paginator("list_policy_principals")
         list_principal_policies_paginator: ListPrincipalPoliciesPaginator = client.get_paginator("list_principal_policies")
         list_principal_things_paginator: ListPrincipalThingsPaginator = client.get_paginator("list_principal_things")
         list_provisioning_template_versions_paginator: ListProvisioningTemplateVersionsPaginator = client.get_paginator("list_provisioning_template_versions")
         list_provisioning_templates_paginator: ListProvisioningTemplatesPaginator = client.get_paginator("list_provisioning_templates")
+        list_related_resources_for_audit_finding_paginator: ListRelatedResourcesForAuditFindingPaginator = client.get_paginator("list_related_resources_for_audit_finding")
         list_role_aliases_paginator: ListRoleAliasesPaginator = client.get_paginator("list_role_aliases")
         list_scheduled_audits_paginator: ListScheduledAuditsPaginator = client.get_paginator("list_scheduled_audits")
         list_security_profiles_paginator: ListSecurityProfilesPaginator = client.get_paginator("list_security_profiles")
         list_security_profiles_for_target_paginator: ListSecurityProfilesForTargetPaginator = client.get_paginator("list_security_profiles_for_target")
         list_streams_paginator: ListStreamsPaginator = client.get_paginator("list_streams")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         list_targets_for_policy_paginator: ListTargetsForPolicyPaginator = client.get_paginator("list_targets_for_policy")
@@ -124,17 +132,16 @@
         list_things_in_thing_group_paginator: ListThingsInThingGroupPaginator = client.get_paginator("list_things_in_thing_group")
         list_topic_rule_destinations_paginator: ListTopicRuleDestinationsPaginator = client.get_paginator("list_topic_rule_destinations")
         list_topic_rules_paginator: ListTopicRulesPaginator = client.get_paginator("list_topic_rules")
         list_v2_logging_levels_paginator: ListV2LoggingLevelsPaginator = client.get_paginator("list_v2_logging_levels")
         list_violation_events_paginator: ListViolationEventsPaginator = client.get_paginator("list_violation_events")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     AuditMitigationActionsExecutionStatusType,
     AuditMitigationActionsTaskStatusType,
@@ -144,14 +151,15 @@
     BehaviorCriteriaTypeType,
     DimensionValueOperatorType,
     JobExecutionStatusType,
     JobStatusType,
     LogTargetTypeType,
     MitigationActionTypeType,
     OTAUpdateStatusType,
+    PackageVersionStatusType,
     ReportTypeType,
     ServiceTypeType,
     StatusType,
     TargetSelectionType,
     VerificationStateType,
 )
 from .type_defs import (
@@ -175,24 +183,28 @@
     ListDomainConfigurationsResponseTypeDef,
     ListFleetMetricsResponseTypeDef,
     ListIndicesResponseTypeDef,
     ListJobExecutionsForJobResponseTypeDef,
     ListJobExecutionsForThingResponseTypeDef,
     ListJobsResponseTypeDef,
     ListJobTemplatesResponseTypeDef,
+    ListManagedJobTemplatesResponseTypeDef,
     ListMetricValuesResponseTypeDef,
     ListMitigationActionsResponseTypeDef,
     ListOTAUpdatesResponseTypeDef,
     ListOutgoingCertificatesResponseTypeDef,
+    ListPackagesResponseTypeDef,
+    ListPackageVersionsResponseTypeDef,
     ListPoliciesResponseTypeDef,
     ListPolicyPrincipalsResponseTypeDef,
     ListPrincipalPoliciesResponseTypeDef,
     ListPrincipalThingsResponseTypeDef,
     ListProvisioningTemplatesResponseTypeDef,
     ListProvisioningTemplateVersionsResponseTypeDef,
+    ListRelatedResourcesForAuditFindingResponseTypeDef,
     ListRoleAliasesResponseTypeDef,
     ListScheduledAuditsResponseTypeDef,
     ListSecurityProfilesForTargetResponseTypeDef,
     ListSecurityProfilesResponseTypeDef,
     ListStreamsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTargetsForPolicyResponseTypeDef,
@@ -210,19 +222,14 @@
     ListTopicRulesResponseTypeDef,
     ListV2LoggingLevelsResponseTypeDef,
     ListViolationEventsResponseTypeDef,
     PaginatorConfigTypeDef,
     ResourceIdentifierTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetBehaviorModelTrainingSummariesPaginator",
     "ListActiveViolationsPaginator",
     "ListAttachedPoliciesPaginator",
     "ListAuditFindingsPaginator",
     "ListAuditMitigationActionsExecutionsPaginator",
     "ListAuditMitigationActionsTasksPaginator",
@@ -240,24 +247,28 @@
     "ListDomainConfigurationsPaginator",
     "ListFleetMetricsPaginator",
     "ListIndicesPaginator",
     "ListJobExecutionsForJobPaginator",
     "ListJobExecutionsForThingPaginator",
     "ListJobTemplatesPaginator",
     "ListJobsPaginator",
+    "ListManagedJobTemplatesPaginator",
     "ListMetricValuesPaginator",
     "ListMitigationActionsPaginator",
     "ListOTAUpdatesPaginator",
     "ListOutgoingCertificatesPaginator",
+    "ListPackageVersionsPaginator",
+    "ListPackagesPaginator",
     "ListPoliciesPaginator",
     "ListPolicyPrincipalsPaginator",
     "ListPrincipalPoliciesPaginator",
     "ListPrincipalThingsPaginator",
     "ListProvisioningTemplateVersionsPaginator",
     "ListProvisioningTemplatesPaginator",
+    "ListRelatedResourcesForAuditFindingPaginator",
     "ListRoleAliasesPaginator",
     "ListScheduledAuditsPaginator",
     "ListSecurityProfilesPaginator",
     "ListSecurityProfilesForTargetPaginator",
     "ListStreamsPaginator",
     "ListTagsForResourcePaginator",
     "ListTargetsForPolicyPaginator",
@@ -288,15 +299,15 @@
 class GetBehaviorModelTrainingSummariesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.GetBehaviorModelTrainingSummaries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#getbehaviormodeltrainingsummariespaginator)
     """
 
     def paginate(
-        self, *, securityProfileName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, securityProfileName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBehaviorModelTrainingSummariesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.GetBehaviorModelTrainingSummaries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#getbehaviormodeltrainingsummariespaginator)
         """
 
 class ListActiveViolationsPaginator(AioPaginator):
@@ -309,29 +320,33 @@
         self,
         *,
         thingName: str = ...,
         securityProfileName: str = ...,
         behaviorCriteriaType: BehaviorCriteriaTypeType = ...,
         listSuppressedAlerts: bool = ...,
         verificationState: VerificationStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListActiveViolationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListActiveViolations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listactiveviolationspaginator)
         """
 
 class ListAttachedPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAttachedPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listattachedpoliciespaginator)
     """
 
     def paginate(
-        self, *, target: str, recursive: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        target: str,
+        recursive: bool = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttachedPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAttachedPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listattachedpoliciespaginator)
         """
 
 class ListAuditFindingsPaginator(AioPaginator):
@@ -345,15 +360,15 @@
         *,
         taskId: str = ...,
         checkName: str = ...,
         resourceIdentifier: ResourceIdentifierTypeDef = ...,
         startTime: Union[datetime, str] = ...,
         endTime: Union[datetime, str] = ...,
         listSuppressedFindings: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAuditFindingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAuditFindings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listauditfindingspaginator)
         """
 
 class ListAuditMitigationActionsExecutionsPaginator(AioPaginator):
@@ -364,15 +379,15 @@
 
     def paginate(
         self,
         *,
         taskId: str,
         findingId: str,
         actionStatus: AuditMitigationActionsExecutionStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAuditMitigationActionsExecutionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAuditMitigationActionsExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listauditmitigationactionsexecutionspaginator)
         """
 
 class ListAuditMitigationActionsTasksPaginator(AioPaginator):
@@ -385,15 +400,15 @@
         self,
         *,
         startTime: Union[datetime, str],
         endTime: Union[datetime, str],
         auditTaskId: str = ...,
         findingId: str = ...,
         taskStatus: AuditMitigationActionsTaskStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAuditMitigationActionsTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAuditMitigationActionsTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listauditmitigationactionstaskspaginator)
         """
 
 class ListAuditSuppressionsPaginator(AioPaginator):
@@ -404,15 +419,15 @@
 
     def paginate(
         self,
         *,
         checkName: str = ...,
         resourceIdentifier: ResourceIdentifierTypeDef = ...,
         ascendingOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAuditSuppressionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAuditSuppressions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listauditsuppressionspaginator)
         """
 
 class ListAuditTasksPaginator(AioPaginator):
@@ -424,15 +439,15 @@
     def paginate(
         self,
         *,
         startTime: Union[datetime, str],
         endTime: Union[datetime, str],
         taskType: AuditTaskTypeType = ...,
         taskStatus: AuditTaskStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAuditTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAuditTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listaudittaskspaginator)
         """
 
 class ListAuthorizersPaginator(AioPaginator):
@@ -442,29 +457,29 @@
     """
 
     def paginate(
         self,
         *,
         ascendingOrder: bool = ...,
         status: AuthorizerStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAuthorizersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListAuthorizers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listauthorizerspaginator)
         """
 
 class ListBillingGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListBillingGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listbillinggroupspaginator)
     """
 
     def paginate(
-        self, *, namePrefixFilter: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, namePrefixFilter: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBillingGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListBillingGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listbillinggroupspaginator)
         """
 
 class ListCACertificatesPaginator(AioPaginator):
@@ -474,29 +489,29 @@
     """
 
     def paginate(
         self,
         *,
         ascendingOrder: bool = ...,
         templateName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCACertificatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListCACertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listcacertificatespaginator)
         """
 
 class ListCertificatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListCertificates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listcertificatespaginator)
     """
 
     def paginate(
-        self, *, ascendingOrder: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ascendingOrder: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCertificatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listcertificatespaginator)
         """
 
 class ListCertificatesByCAPaginator(AioPaginator):
@@ -506,29 +521,29 @@
     """
 
     def paginate(
         self,
         *,
         caCertificateId: str,
         ascendingOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCertificatesByCAResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListCertificatesByCA.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listcertificatesbycapaginator)
         """
 
 class ListCustomMetricsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListCustomMetrics)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listcustommetricspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomMetricsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListCustomMetrics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listcustommetricspaginator)
         """
 
 class ListDetectMitigationActionsExecutionsPaginator(AioPaginator):
@@ -541,15 +556,15 @@
         self,
         *,
         taskId: str = ...,
         violationId: str = ...,
         thingName: str = ...,
         startTime: Union[datetime, str] = ...,
         endTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDetectMitigationActionsExecutionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListDetectMitigationActionsExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listdetectmitigationactionsexecutionspaginator)
         """
 
 class ListDetectMitigationActionsTasksPaginator(AioPaginator):
@@ -559,71 +574,74 @@
     """
 
     def paginate(
         self,
         *,
         startTime: Union[datetime, str],
         endTime: Union[datetime, str],
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDetectMitigationActionsTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListDetectMitigationActionsTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listdetectmitigationactionstaskspaginator)
         """
 
 class ListDimensionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListDimensions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listdimensionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDimensionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListDimensions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listdimensionspaginator)
         """
 
 class ListDomainConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListDomainConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listdomainconfigurationspaginator)
     """
 
     def paginate(
-        self, *, serviceType: ServiceTypeType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        serviceType: ServiceTypeType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDomainConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListDomainConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listdomainconfigurationspaginator)
         """
 
 class ListFleetMetricsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListFleetMetrics)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listfleetmetricspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFleetMetricsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListFleetMetrics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listfleetmetricspaginator)
         """
 
 class ListIndicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListIndices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listindicespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIndicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListIndices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listindicespaginator)
         """
 
 class ListJobExecutionsForJobPaginator(AioPaginator):
@@ -633,15 +651,15 @@
     """
 
     def paginate(
         self,
         *,
         jobId: str,
         status: JobExecutionStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobExecutionsForJobResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListJobExecutionsForJob.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listjobexecutionsforjobpaginator)
         """
 
 class ListJobExecutionsForThingPaginator(AioPaginator):
@@ -653,29 +671,29 @@
     def paginate(
         self,
         *,
         thingName: str,
         status: JobExecutionStatusType = ...,
         namespaceId: str = ...,
         jobId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobExecutionsForThingResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListJobExecutionsForThing.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listjobexecutionsforthingpaginator)
         """
 
 class ListJobTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListJobTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listjobtemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListJobTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listjobtemplatespaginator)
         """
 
 class ListJobsPaginator(AioPaginator):
@@ -688,21 +706,35 @@
         self,
         *,
         status: JobStatusType = ...,
         targetSelection: TargetSelectionType = ...,
         thingGroupName: str = ...,
         thingGroupId: str = ...,
         namespaceId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listjobspaginator)
         """
 
+class ListManagedJobTemplatesPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListManagedJobTemplates)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listmanagedjobtemplatespaginator)
+    """
+
+    def paginate(
+        self, *, templateName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListManagedJobTemplatesResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListManagedJobTemplates.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listmanagedjobtemplatespaginator)
+        """
+
 class ListMetricValuesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListMetricValues)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listmetricvaluespaginator)
     """
 
     def paginate(
@@ -710,15 +742,15 @@
         *,
         thingName: str,
         metricName: str,
         startTime: Union[datetime, str],
         endTime: Union[datetime, str],
         dimensionName: str = ...,
         dimensionValueOperator: DimensionValueOperatorType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMetricValuesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListMetricValues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listmetricvaluespaginator)
         """
 
 class ListMitigationActionsPaginator(AioPaginator):
@@ -727,15 +759,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listmitigationactionspaginator)
     """
 
     def paginate(
         self,
         *,
         actionType: MitigationActionTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMitigationActionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListMitigationActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listmitigationactionspaginator)
         """
 
 class ListOTAUpdatesPaginator(AioPaginator):
@@ -744,43 +776,75 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listotaupdatespaginator)
     """
 
     def paginate(
         self,
         *,
         otaUpdateStatus: OTAUpdateStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOTAUpdatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListOTAUpdates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listotaupdatespaginator)
         """
 
 class ListOutgoingCertificatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListOutgoingCertificates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listoutgoingcertificatespaginator)
     """
 
     def paginate(
-        self, *, ascendingOrder: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ascendingOrder: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOutgoingCertificatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListOutgoingCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listoutgoingcertificatespaginator)
         """
 
+class ListPackageVersionsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPackageVersions)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listpackageversionspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        packageName: str,
+        status: PackageVersionStatusType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListPackageVersionsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPackageVersions.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listpackageversionspaginator)
+        """
+
+class ListPackagesPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPackages)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listpackagespaginator)
+    """
+
+    def paginate(
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListPackagesResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPackages.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listpackagespaginator)
+        """
+
 class ListPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listpoliciespaginator)
     """
 
     def paginate(
-        self, *, ascendingOrder: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ascendingOrder: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listpoliciespaginator)
         """
 
 class ListPolicyPrincipalsPaginator(AioPaginator):
@@ -790,15 +854,15 @@
     """
 
     def paginate(
         self,
         *,
         policyName: str,
         ascendingOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPolicyPrincipalsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPolicyPrincipals.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listpolicyprincipalspaginator)
         """
 
 class ListPrincipalPoliciesPaginator(AioPaginator):
@@ -808,85 +872,99 @@
     """
 
     def paginate(
         self,
         *,
         principal: str,
         ascendingOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPrincipalPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPrincipalPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listprincipalpoliciespaginator)
         """
 
 class ListPrincipalThingsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPrincipalThings)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listprincipalthingspaginator)
     """
 
     def paginate(
-        self, *, principal: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, principal: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPrincipalThingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListPrincipalThings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listprincipalthingspaginator)
         """
 
 class ListProvisioningTemplateVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListProvisioningTemplateVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listprovisioningtemplateversionspaginator)
     """
 
     def paginate(
-        self, *, templateName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, templateName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProvisioningTemplateVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListProvisioningTemplateVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listprovisioningtemplateversionspaginator)
         """
 
 class ListProvisioningTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListProvisioningTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listprovisioningtemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProvisioningTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListProvisioningTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listprovisioningtemplatespaginator)
         """
 
+class ListRelatedResourcesForAuditFindingPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListRelatedResourcesForAuditFinding)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listrelatedresourcesforauditfindingpaginator)
+    """
+
+    def paginate(
+        self, *, findingId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListRelatedResourcesForAuditFindingResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListRelatedResourcesForAuditFinding.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listrelatedresourcesforauditfindingpaginator)
+        """
+
 class ListRoleAliasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListRoleAliases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listrolealiasespaginator)
     """
 
     def paginate(
-        self, *, ascendingOrder: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ascendingOrder: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRoleAliasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListRoleAliases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listrolealiasespaginator)
         """
 
 class ListScheduledAuditsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListScheduledAudits)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listscheduledauditspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListScheduledAuditsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListScheduledAudits.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listscheduledauditspaginator)
         """
 
 class ListSecurityProfilesPaginator(AioPaginator):
@@ -896,15 +974,15 @@
     """
 
     def paginate(
         self,
         *,
         dimensionName: str = ...,
         metricName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSecurityProfilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListSecurityProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listsecurityprofilespaginator)
         """
 
 class ListSecurityProfilesForTargetPaginator(AioPaginator):
@@ -914,71 +992,71 @@
     """
 
     def paginate(
         self,
         *,
         securityProfileTargetArn: str,
         recursive: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSecurityProfilesForTargetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListSecurityProfilesForTarget.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listsecurityprofilesfortargetpaginator)
         """
 
 class ListStreamsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListStreams)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#liststreamspaginator)
     """
 
     def paginate(
-        self, *, ascendingOrder: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ascendingOrder: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListStreams.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#liststreamspaginator)
         """
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtagsforresourcepaginator)
         """
 
 class ListTargetsForPolicyPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTargetsForPolicy)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtargetsforpolicypaginator)
     """
 
     def paginate(
-        self, *, policyName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, policyName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTargetsForPolicyResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTargetsForPolicy.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtargetsforpolicypaginator)
         """
 
 class ListTargetsForSecurityProfilePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTargetsForSecurityProfile)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtargetsforsecurityprofilepaginator)
     """
 
     def paginate(
-        self, *, securityProfileName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, securityProfileName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTargetsForSecurityProfileResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTargetsForSecurityProfile.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtargetsforsecurityprofilepaginator)
         """
 
 class ListThingGroupsPaginator(AioPaginator):
@@ -989,43 +1067,43 @@
 
     def paginate(
         self,
         *,
         parentGroup: str = ...,
         namePrefixFilter: str = ...,
         recursive: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthinggroupspaginator)
         """
 
 class ListThingGroupsForThingPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingGroupsForThing)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthinggroupsforthingpaginator)
     """
 
     def paginate(
-        self, *, thingName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, thingName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingGroupsForThingResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingGroupsForThing.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthinggroupsforthingpaginator)
         """
 
 class ListThingPrincipalsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingPrincipals)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingprincipalspaginator)
     """
 
     def paginate(
-        self, *, thingName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, thingName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingPrincipalsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingPrincipals.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingprincipalspaginator)
         """
 
 class ListThingRegistrationTaskReportsPaginator(AioPaginator):
@@ -1035,43 +1113,43 @@
     """
 
     def paginate(
         self,
         *,
         taskId: str,
         reportType: ReportTypeType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingRegistrationTaskReportsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingRegistrationTaskReports.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingregistrationtaskreportspaginator)
         """
 
 class ListThingRegistrationTasksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingRegistrationTasks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingregistrationtaskspaginator)
     """
 
     def paginate(
-        self, *, status: StatusType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, status: StatusType = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingRegistrationTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingRegistrationTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingregistrationtaskspaginator)
         """
 
 class ListThingTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingtypespaginator)
     """
 
     def paginate(
-        self, *, thingTypeName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, thingTypeName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingtypespaginator)
         """
 
 class ListThingsPaginator(AioPaginator):
@@ -1083,29 +1161,29 @@
     def paginate(
         self,
         *,
         attributeName: str = ...,
         attributeValue: str = ...,
         thingTypeName: str = ...,
         usePrefixAttributeValue: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingspaginator)
         """
 
 class ListThingsInBillingGroupPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingsInBillingGroup)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingsinbillinggrouppaginator)
     """
 
     def paginate(
-        self, *, billingGroupName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, billingGroupName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingsInBillingGroupResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingsInBillingGroup.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingsinbillinggrouppaginator)
         """
 
 class ListThingsInThingGroupPaginator(AioPaginator):
@@ -1115,29 +1193,29 @@
     """
 
     def paginate(
         self,
         *,
         thingGroupName: str,
         recursive: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThingsInThingGroupResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListThingsInThingGroup.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listthingsinthinggrouppaginator)
         """
 
 class ListTopicRuleDestinationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTopicRuleDestinations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtopicruledestinationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTopicRuleDestinationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTopicRuleDestinations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtopicruledestinationspaginator)
         """
 
 class ListTopicRulesPaginator(AioPaginator):
@@ -1147,29 +1225,32 @@
     """
 
     def paginate(
         self,
         *,
         topic: str = ...,
         ruleDisabled: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTopicRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListTopicRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listtopicrulespaginator)
         """
 
 class ListV2LoggingLevelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListV2LoggingLevels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listv2logginglevelspaginator)
     """
 
     def paginate(
-        self, *, targetType: LogTargetTypeType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        targetType: LogTargetTypeType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListV2LoggingLevelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListV2LoggingLevels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listv2logginglevelspaginator)
         """
 
 class ListViolationEventsPaginator(AioPaginator):
@@ -1184,13 +1265,13 @@
         startTime: Union[datetime, str],
         endTime: Union[datetime, str],
         thingName: str = ...,
         securityProfileName: str = ...,
         behaviorCriteriaType: BehaviorCriteriaTypeType = ...,
         listSuppressedAlerts: bool = ...,
         verificationState: VerificationStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListViolationEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT.Paginator.ListViolationEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/paginators/#listviolationeventspaginator)
         """
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/type_defs.py` & `types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -59,14 +59,16 @@
     LogLevelType,
     LogTargetTypeType,
     MessageFormatType,
     MitigationActionTypeType,
     ModelStatusType,
     NamedShadowIndexingModeType,
     OTAUpdateStatusType,
+    PackageVersionActionType,
+    PackageVersionStatusType,
     ProtocolType,
     ReportTypeType,
     ResourceTypeType,
     RetryableFailureTypeType,
     ServerCertificateStatusType,
     ServiceTypeType,
     StatusType,
@@ -117,15 +119,15 @@
     "AddThingsToThingGroupParamsTypeDef",
     "AggregationTypeTypeDef",
     "AlertTargetTypeDef",
     "PolicyTypeDef",
     "AssetPropertyTimestampTypeDef",
     "AssetPropertyVariantTypeDef",
     "AssociateTargetsWithJobRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateTargetsWithJobResponseTypeDef",
     "AttachPolicyRequestRequestTypeDef",
     "AttachPrincipalPolicyRequestRequestTypeDef",
     "AttachSecurityProfileRequestRequestTypeDef",
     "AttachThingPrincipalRequestRequestTypeDef",
     "AttributePayloadTypeDef",
     "AuditCheckConfigurationTypeDef",
     "AuditCheckDetailsTypeDef",
@@ -154,32 +156,61 @@
     "CACertificateTypeDef",
     "CancelAuditMitigationActionsTaskRequestRequestTypeDef",
     "CancelAuditTaskRequestRequestTypeDef",
     "CancelCertificateTransferRequestRequestTypeDef",
     "CancelDetectMitigationActionsTaskRequestRequestTypeDef",
     "CancelJobExecutionRequestRequestTypeDef",
     "CancelJobRequestRequestTypeDef",
+    "CancelJobResponseTypeDef",
     "TransferDataTypeDef",
     "CertificateTypeDef",
     "CodeSigningCertificateChainTypeDef",
     "CodeSigningSignatureTypeDef",
     "ConfigurationTypeDef",
     "ConfirmTopicRuleDestinationRequestRequestTypeDef",
     "TagTypeDef",
+    "CreateAuthorizerResponseTypeDef",
+    "CreateBillingGroupResponseTypeDef",
     "CreateCertificateFromCsrRequestRequestTypeDef",
+    "CreateCertificateFromCsrResponseTypeDef",
+    "CreateCustomMetricResponseTypeDef",
+    "CreateDimensionResponseTypeDef",
+    "TlsConfigTypeDef",
+    "CreateDomainConfigurationResponseTypeDef",
+    "CreateDynamicThingGroupResponseTypeDef",
+    "CreateFleetMetricResponseTypeDef",
     "PresignedUrlConfigTypeDef",
-    "SchedulingConfigTypeDef",
     "TimeoutConfigTypeDef",
+    "CreateJobResponseTypeDef",
+    "MaintenanceWindowTypeDef",
+    "CreateJobTemplateResponseTypeDef",
     "CreateKeysAndCertificateRequestRequestTypeDef",
     "KeyPairTypeDef",
+    "CreateMitigationActionResponseTypeDef",
+    "CreateOTAUpdateResponseTypeDef",
+    "CreatePackageRequestRequestTypeDef",
+    "CreatePackageResponseTypeDef",
+    "CreatePackageVersionRequestRequestTypeDef",
+    "CreatePackageVersionResponseTypeDef",
+    "CreatePolicyResponseTypeDef",
     "CreatePolicyVersionRequestRequestTypeDef",
+    "CreatePolicyVersionResponseTypeDef",
     "CreateProvisioningClaimRequestRequestTypeDef",
     "ProvisioningHookTypeDef",
+    "CreateProvisioningTemplateResponseTypeDef",
     "CreateProvisioningTemplateVersionRequestRequestTypeDef",
+    "CreateProvisioningTemplateVersionResponseTypeDef",
+    "CreateRoleAliasResponseTypeDef",
+    "CreateScheduledAuditResponseTypeDef",
+    "CreateSecurityProfileResponseTypeDef",
+    "CreateStreamResponseTypeDef",
+    "CreateThingGroupResponseTypeDef",
+    "CreateThingResponseTypeDef",
     "ThingTypePropertiesTypeDef",
+    "CreateThingTypeResponseTypeDef",
     "DeleteAccountAuditConfigurationRequestRequestTypeDef",
     "DeleteAuthorizerRequestRequestTypeDef",
     "DeleteBillingGroupRequestRequestTypeDef",
     "DeleteCACertificateRequestRequestTypeDef",
     "DeleteCertificateRequestRequestTypeDef",
     "DeleteCustomMetricRequestRequestTypeDef",
     "DeleteDimensionRequestRequestTypeDef",
@@ -187,14 +218,16 @@
     "DeleteDynamicThingGroupRequestRequestTypeDef",
     "DeleteFleetMetricRequestRequestTypeDef",
     "DeleteJobExecutionRequestRequestTypeDef",
     "DeleteJobRequestRequestTypeDef",
     "DeleteJobTemplateRequestRequestTypeDef",
     "DeleteMitigationActionRequestRequestTypeDef",
     "DeleteOTAUpdateRequestRequestTypeDef",
+    "DeletePackageRequestRequestTypeDef",
+    "DeletePackageVersionRequestRequestTypeDef",
     "DeletePolicyRequestRequestTypeDef",
     "DeletePolicyVersionRequestRequestTypeDef",
     "DeleteProvisioningTemplateRequestRequestTypeDef",
     "DeleteProvisioningTemplateVersionRequestRequestTypeDef",
     "DeleteRoleAliasRequestRequestTypeDef",
     "DeleteScheduledAuditRequestRequestTypeDef",
     "DeleteSecurityProfileRequestRequestTypeDef",
@@ -213,37 +246,45 @@
     "TaskStatisticsTypeDef",
     "DescribeAuthorizerRequestRequestTypeDef",
     "DescribeBillingGroupRequestRequestTypeDef",
     "DescribeCACertificateRequestRequestTypeDef",
     "RegistrationConfigTypeDef",
     "DescribeCertificateRequestRequestTypeDef",
     "DescribeCustomMetricRequestRequestTypeDef",
+    "DescribeCustomMetricResponseTypeDef",
     "DescribeDetectMitigationActionsTaskRequestRequestTypeDef",
     "DescribeDimensionRequestRequestTypeDef",
+    "DescribeDimensionResponseTypeDef",
     "DescribeDomainConfigurationRequestRequestTypeDef",
     "ServerCertificateSummaryTypeDef",
     "DescribeEndpointRequestRequestTypeDef",
+    "DescribeEndpointResponseTypeDef",
     "DescribeFleetMetricRequestRequestTypeDef",
     "DescribeIndexRequestRequestTypeDef",
+    "DescribeIndexResponseTypeDef",
     "DescribeJobExecutionRequestRequestTypeDef",
     "DescribeJobRequestRequestTypeDef",
     "DescribeJobTemplateRequestRequestTypeDef",
     "DescribeManagedJobTemplateRequestRequestTypeDef",
     "DocumentParameterTypeDef",
     "DescribeMitigationActionRequestRequestTypeDef",
     "DescribeProvisioningTemplateRequestRequestTypeDef",
     "DescribeProvisioningTemplateVersionRequestRequestTypeDef",
+    "DescribeProvisioningTemplateVersionResponseTypeDef",
     "DescribeRoleAliasRequestRequestTypeDef",
     "RoleAliasDescriptionTypeDef",
     "DescribeScheduledAuditRequestRequestTypeDef",
+    "DescribeScheduledAuditResponseTypeDef",
     "DescribeSecurityProfileRequestRequestTypeDef",
     "DescribeStreamRequestRequestTypeDef",
     "DescribeThingGroupRequestRequestTypeDef",
     "DescribeThingRegistrationTaskRequestRequestTypeDef",
+    "DescribeThingRegistrationTaskResponseTypeDef",
     "DescribeThingRequestRequestTypeDef",
+    "DescribeThingResponseTypeDef",
     "DescribeThingTypeRequestRequestTypeDef",
     "ThingTypeMetadataTypeDef",
     "S3DestinationTypeDef",
     "DetachPolicyRequestRequestTypeDef",
     "DetachPrincipalPolicyRequestRequestTypeDef",
     "DetachSecurityProfileRequestRequestTypeDef",
     "DetachThingPrincipalRequestRequestTypeDef",
@@ -251,36 +292,49 @@
     "DetectMitigationActionsTaskStatisticsTypeDef",
     "DetectMitigationActionsTaskTargetTypeDef",
     "ViolationEventOccurrenceRangeTypeDef",
     "DisableTopicRuleRequestRequestTypeDef",
     "DomainConfigurationSummaryTypeDef",
     "PutItemInputTypeDef",
     "EffectivePolicyTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableIoTLoggingParamsTypeDef",
     "EnableTopicRuleRequestRequestTypeDef",
     "ErrorInfoTypeDef",
     "RateIncreaseCriteriaTypeDef",
     "FieldTypeDef",
     "S3LocationTypeDef",
     "StreamTypeDef",
     "FleetMetricNameAndArnTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef",
     "GetBehaviorModelTrainingSummariesRequestRequestTypeDef",
     "GetCardinalityRequestRequestTypeDef",
+    "GetCardinalityResponseTypeDef",
     "GetEffectivePoliciesRequestRequestTypeDef",
     "GetJobDocumentRequestRequestTypeDef",
+    "GetJobDocumentResponseTypeDef",
+    "GetLoggingOptionsResponseTypeDef",
     "GetOTAUpdateRequestRequestTypeDef",
+    "VersionUpdateByJobsConfigTypeDef",
+    "GetPackageRequestRequestTypeDef",
+    "GetPackageResponseTypeDef",
+    "GetPackageVersionRequestRequestTypeDef",
+    "GetPackageVersionResponseTypeDef",
     "GetPercentilesRequestRequestTypeDef",
     "PercentPairTypeDef",
     "GetPolicyRequestRequestTypeDef",
+    "GetPolicyResponseTypeDef",
     "GetPolicyVersionRequestRequestTypeDef",
+    "GetPolicyVersionResponseTypeDef",
+    "GetRegistrationCodeResponseTypeDef",
     "GetStatisticsRequestRequestTypeDef",
     "StatisticsTypeDef",
     "GetTopicRuleDestinationRequestRequestTypeDef",
     "GetTopicRuleRequestRequestTypeDef",
+    "GetV2LoggingOptionsResponseTypeDef",
     "GroupNameAndArnTypeDef",
     "HttpActionHeaderTypeDef",
     "SigV4AuthorizationTypeDef",
     "HttpContextTypeDef",
     "HttpUrlDestinationConfigurationTypeDef",
     "HttpUrlDestinationPropertiesTypeDef",
     "HttpUrlDestinationSummaryTypeDef",
@@ -288,223 +342,246 @@
     "IssuerCertificateIdentifierTypeDef",
     "JobExecutionStatusDetailsTypeDef",
     "JobExecutionSummaryTypeDef",
     "RetryCriteriaTypeDef",
     "JobProcessDetailsTypeDef",
     "JobSummaryTypeDef",
     "JobTemplateSummaryTypeDef",
+    "ScheduledJobRolloutTypeDef",
+    "ListActiveViolationsRequestListActiveViolationsPaginateTypeDef",
     "ListActiveViolationsRequestRequestTypeDef",
+    "ListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef",
     "ListAttachedPoliciesRequestRequestTypeDef",
+    "ListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef",
     "ListAuditMitigationActionsExecutionsRequestRequestTypeDef",
+    "ListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef",
     "ListAuditMitigationActionsTasksRequestRequestTypeDef",
+    "ListAuditTasksRequestListAuditTasksPaginateTypeDef",
     "ListAuditTasksRequestRequestTypeDef",
+    "ListAuthorizersRequestListAuthorizersPaginateTypeDef",
     "ListAuthorizersRequestRequestTypeDef",
+    "ListBillingGroupsRequestListBillingGroupsPaginateTypeDef",
     "ListBillingGroupsRequestRequestTypeDef",
+    "ListCACertificatesRequestListCACertificatesPaginateTypeDef",
     "ListCACertificatesRequestRequestTypeDef",
+    "ListCertificatesByCARequestListCertificatesByCAPaginateTypeDef",
     "ListCertificatesByCARequestRequestTypeDef",
+    "ListCertificatesRequestListCertificatesPaginateTypeDef",
     "ListCertificatesRequestRequestTypeDef",
+    "ListCustomMetricsRequestListCustomMetricsPaginateTypeDef",
     "ListCustomMetricsRequestRequestTypeDef",
+    "ListCustomMetricsResponseTypeDef",
+    "ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef",
     "ListDetectMitigationActionsExecutionsRequestRequestTypeDef",
+    "ListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef",
     "ListDetectMitigationActionsTasksRequestRequestTypeDef",
+    "ListDimensionsRequestListDimensionsPaginateTypeDef",
     "ListDimensionsRequestRequestTypeDef",
+    "ListDimensionsResponseTypeDef",
+    "ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef",
     "ListDomainConfigurationsRequestRequestTypeDef",
+    "ListFleetMetricsRequestListFleetMetricsPaginateTypeDef",
     "ListFleetMetricsRequestRequestTypeDef",
+    "ListIndicesRequestListIndicesPaginateTypeDef",
     "ListIndicesRequestRequestTypeDef",
+    "ListIndicesResponseTypeDef",
+    "ListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef",
     "ListJobExecutionsForJobRequestRequestTypeDef",
+    "ListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef",
     "ListJobExecutionsForThingRequestRequestTypeDef",
+    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
     "ListJobTemplatesRequestRequestTypeDef",
+    "ListJobsRequestListJobsPaginateTypeDef",
     "ListJobsRequestRequestTypeDef",
+    "ListManagedJobTemplatesRequestListManagedJobTemplatesPaginateTypeDef",
     "ListManagedJobTemplatesRequestRequestTypeDef",
     "ManagedJobTemplateSummaryTypeDef",
+    "ListMetricValuesRequestListMetricValuesPaginateTypeDef",
     "ListMetricValuesRequestRequestTypeDef",
+    "ListMitigationActionsRequestListMitigationActionsPaginateTypeDef",
     "ListMitigationActionsRequestRequestTypeDef",
     "MitigationActionIdentifierTypeDef",
+    "ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef",
     "ListOTAUpdatesRequestRequestTypeDef",
     "OTAUpdateSummaryTypeDef",
+    "ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef",
     "ListOutgoingCertificatesRequestRequestTypeDef",
     "OutgoingCertificateTypeDef",
+    "ListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
+    "ListPackageVersionsRequestRequestTypeDef",
+    "PackageVersionSummaryTypeDef",
+    "ListPackagesRequestListPackagesPaginateTypeDef",
+    "ListPackagesRequestRequestTypeDef",
+    "PackageSummaryTypeDef",
+    "ListPoliciesRequestListPoliciesPaginateTypeDef",
     "ListPoliciesRequestRequestTypeDef",
+    "ListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef",
     "ListPolicyPrincipalsRequestRequestTypeDef",
+    "ListPolicyPrincipalsResponseTypeDef",
     "ListPolicyVersionsRequestRequestTypeDef",
     "PolicyVersionTypeDef",
+    "ListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef",
     "ListPrincipalPoliciesRequestRequestTypeDef",
+    "ListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef",
     "ListPrincipalThingsRequestRequestTypeDef",
+    "ListPrincipalThingsResponseTypeDef",
+    "ListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef",
     "ListProvisioningTemplateVersionsRequestRequestTypeDef",
     "ProvisioningTemplateVersionSummaryTypeDef",
+    "ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef",
     "ListProvisioningTemplatesRequestRequestTypeDef",
     "ProvisioningTemplateSummaryTypeDef",
+    "ListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef",
     "ListRelatedResourcesForAuditFindingRequestRequestTypeDef",
+    "ListRoleAliasesRequestListRoleAliasesPaginateTypeDef",
     "ListRoleAliasesRequestRequestTypeDef",
+    "ListRoleAliasesResponseTypeDef",
+    "ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef",
     "ListScheduledAuditsRequestRequestTypeDef",
     "ScheduledAuditMetadataTypeDef",
+    "ListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef",
     "ListSecurityProfilesForTargetRequestRequestTypeDef",
+    "ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef",
     "ListSecurityProfilesRequestRequestTypeDef",
     "SecurityProfileIdentifierTypeDef",
+    "ListStreamsRequestListStreamsPaginateTypeDef",
     "ListStreamsRequestRequestTypeDef",
     "StreamSummaryTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
     "ListTargetsForPolicyRequestRequestTypeDef",
+    "ListTargetsForPolicyResponseTypeDef",
+    "ListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef",
     "ListTargetsForSecurityProfileRequestRequestTypeDef",
     "SecurityProfileTargetTypeDef",
+    "ListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef",
     "ListThingGroupsForThingRequestRequestTypeDef",
+    "ListThingGroupsRequestListThingGroupsPaginateTypeDef",
     "ListThingGroupsRequestRequestTypeDef",
+    "ListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef",
     "ListThingPrincipalsRequestRequestTypeDef",
+    "ListThingPrincipalsResponseTypeDef",
+    "ListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef",
     "ListThingRegistrationTaskReportsRequestRequestTypeDef",
+    "ListThingRegistrationTaskReportsResponseTypeDef",
+    "ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef",
     "ListThingRegistrationTasksRequestRequestTypeDef",
+    "ListThingRegistrationTasksResponseTypeDef",
+    "ListThingTypesRequestListThingTypesPaginateTypeDef",
     "ListThingTypesRequestRequestTypeDef",
+    "ListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef",
     "ListThingsInBillingGroupRequestRequestTypeDef",
+    "ListThingsInBillingGroupResponseTypeDef",
+    "ListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef",
     "ListThingsInThingGroupRequestRequestTypeDef",
+    "ListThingsInThingGroupResponseTypeDef",
+    "ListThingsRequestListThingsPaginateTypeDef",
     "ListThingsRequestRequestTypeDef",
     "ThingAttributeTypeDef",
+    "ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef",
     "ListTopicRuleDestinationsRequestRequestTypeDef",
+    "ListTopicRulesRequestListTopicRulesPaginateTypeDef",
     "ListTopicRulesRequestRequestTypeDef",
     "TopicRuleListItemTypeDef",
+    "ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef",
     "ListV2LoggingLevelsRequestRequestTypeDef",
+    "ListViolationEventsRequestListViolationEventsPaginateTypeDef",
     "ListViolationEventsRequestRequestTypeDef",
     "LocationTimestampTypeDef",
     "LogTargetTypeDef",
     "LoggingOptionsPayloadTypeDef",
     "PublishFindingToSnsParamsTypeDef",
     "ReplaceDefaultPolicyVersionParamsTypeDef",
     "UpdateCACertificateParamsTypeDef",
     "UpdateDeviceCertificateParamsTypeDef",
     "MqttContextTypeDef",
     "UserPropertyTypeDef",
+    "PaginatorConfigTypeDef",
     "PolicyVersionIdentifierTypeDef",
     "PutVerificationStateOnViolationRequestRequestTypeDef",
+    "RegisterCACertificateResponseTypeDef",
     "RegisterCertificateRequestRequestTypeDef",
+    "RegisterCertificateResponseTypeDef",
     "RegisterCertificateWithoutCARequestRequestTypeDef",
+    "RegisterCertificateWithoutCAResponseTypeDef",
     "RegisterThingRequestRequestTypeDef",
+    "RegisterThingResponseTypeDef",
     "RejectCertificateTransferRequestRequestTypeDef",
     "RemoveThingFromBillingGroupRequestRequestTypeDef",
     "RemoveThingFromThingGroupRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "SearchIndexRequestRequestTypeDef",
     "ThingGroupDocumentTypeDef",
     "SetDefaultAuthorizerRequestRequestTypeDef",
+    "SetDefaultAuthorizerResponseTypeDef",
     "SetDefaultPolicyVersionRequestRequestTypeDef",
     "SetV2LoggingOptionsRequestRequestTypeDef",
     "SigningProfileParameterTypeDef",
+    "StartAuditMitigationActionsTaskResponseTypeDef",
+    "StartDetectMitigationActionsTaskResponseTypeDef",
     "StartOnDemandAuditTaskRequestRequestTypeDef",
+    "StartOnDemandAuditTaskResponseTypeDef",
     "StartThingRegistrationTaskRequestRequestTypeDef",
+    "StartThingRegistrationTaskResponseTypeDef",
     "StopThingRegistrationTaskRequestRequestTypeDef",
     "TlsContextTypeDef",
+    "TestInvokeAuthorizerResponseTypeDef",
     "ThingConnectivityTypeDef",
     "TimestreamDimensionTypeDef",
     "TimestreamTimestampTypeDef",
     "VpcDestinationConfigurationTypeDef",
     "VpcDestinationSummaryTypeDef",
     "VpcDestinationPropertiesTypeDef",
     "TransferCertificateRequestRequestTypeDef",
+    "TransferCertificateResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAuthorizerRequestRequestTypeDef",
+    "UpdateAuthorizerResponseTypeDef",
+    "UpdateBillingGroupResponseTypeDef",
     "UpdateCertificateRequestRequestTypeDef",
     "UpdateCustomMetricRequestRequestTypeDef",
+    "UpdateCustomMetricResponseTypeDef",
     "UpdateDimensionRequestRequestTypeDef",
+    "UpdateDimensionResponseTypeDef",
+    "UpdateDomainConfigurationResponseTypeDef",
+    "UpdateDynamicThingGroupResponseTypeDef",
+    "UpdateMitigationActionResponseTypeDef",
+    "UpdatePackageRequestRequestTypeDef",
+    "UpdatePackageVersionRequestRequestTypeDef",
     "UpdateRoleAliasRequestRequestTypeDef",
+    "UpdateRoleAliasResponseTypeDef",
     "UpdateScheduledAuditRequestRequestTypeDef",
+    "UpdateScheduledAuditResponseTypeDef",
+    "UpdateStreamResponseTypeDef",
+    "UpdateThingGroupResponseTypeDef",
     "UpdateThingGroupsForThingRequestRequestTypeDef",
     "UpdateTopicRuleDestinationRequestRequestTypeDef",
     "ValidationErrorTypeDef",
     "AbortConfigTypeDef",
     "MetricDatumTypeDef",
+    "DescribeFleetMetricResponseTypeDef",
     "UpdateFleetMetricRequestRequestTypeDef",
     "AllowedTypeDef",
     "ExplicitDenyTypeDef",
     "ImplicitDenyTypeDef",
-    "AssetPropertyValueTypeDef",
-    "AssociateTargetsWithJobResponseTypeDef",
-    "CancelJobResponseTypeDef",
-    "CreateAuthorizerResponseTypeDef",
-    "CreateBillingGroupResponseTypeDef",
-    "CreateCertificateFromCsrResponseTypeDef",
-    "CreateCustomMetricResponseTypeDef",
-    "CreateDimensionResponseTypeDef",
-    "CreateDomainConfigurationResponseTypeDef",
-    "CreateDynamicThingGroupResponseTypeDef",
-    "CreateFleetMetricResponseTypeDef",
-    "CreateJobResponseTypeDef",
-    "CreateJobTemplateResponseTypeDef",
-    "CreateMitigationActionResponseTypeDef",
-    "CreateOTAUpdateResponseTypeDef",
-    "CreatePolicyResponseTypeDef",
-    "CreatePolicyVersionResponseTypeDef",
-    "CreateProvisioningTemplateResponseTypeDef",
-    "CreateProvisioningTemplateVersionResponseTypeDef",
-    "CreateRoleAliasResponseTypeDef",
-    "CreateScheduledAuditResponseTypeDef",
-    "CreateSecurityProfileResponseTypeDef",
-    "CreateStreamResponseTypeDef",
-    "CreateThingGroupResponseTypeDef",
-    "CreateThingResponseTypeDef",
-    "CreateThingTypeResponseTypeDef",
-    "DescribeCustomMetricResponseTypeDef",
-    "DescribeDimensionResponseTypeDef",
-    "DescribeEndpointResponseTypeDef",
-    "DescribeFleetMetricResponseTypeDef",
-    "DescribeIndexResponseTypeDef",
-    "DescribeProvisioningTemplateVersionResponseTypeDef",
-    "DescribeScheduledAuditResponseTypeDef",
-    "DescribeThingRegistrationTaskResponseTypeDef",
-    "DescribeThingResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetCardinalityResponseTypeDef",
-    "GetJobDocumentResponseTypeDef",
-    "GetLoggingOptionsResponseTypeDef",
-    "GetPolicyResponseTypeDef",
-    "GetPolicyVersionResponseTypeDef",
-    "GetRegistrationCodeResponseTypeDef",
-    "GetV2LoggingOptionsResponseTypeDef",
     "ListAttachedPoliciesResponseTypeDef",
-    "ListCustomMetricsResponseTypeDef",
-    "ListDimensionsResponseTypeDef",
-    "ListIndicesResponseTypeDef",
     "ListPoliciesResponseTypeDef",
-    "ListPolicyPrincipalsResponseTypeDef",
     "ListPrincipalPoliciesResponseTypeDef",
-    "ListPrincipalThingsResponseTypeDef",
-    "ListRoleAliasesResponseTypeDef",
-    "ListTargetsForPolicyResponseTypeDef",
-    "ListThingPrincipalsResponseTypeDef",
-    "ListThingRegistrationTaskReportsResponseTypeDef",
-    "ListThingRegistrationTasksResponseTypeDef",
-    "ListThingsInBillingGroupResponseTypeDef",
-    "ListThingsInThingGroupResponseTypeDef",
-    "RegisterCACertificateResponseTypeDef",
-    "RegisterCertificateResponseTypeDef",
-    "RegisterCertificateWithoutCAResponseTypeDef",
-    "RegisterThingResponseTypeDef",
-    "SetDefaultAuthorizerResponseTypeDef",
-    "StartAuditMitigationActionsTaskResponseTypeDef",
-    "StartDetectMitigationActionsTaskResponseTypeDef",
-    "StartOnDemandAuditTaskResponseTypeDef",
-    "StartThingRegistrationTaskResponseTypeDef",
-    "TestInvokeAuthorizerResponseTypeDef",
-    "TransferCertificateResponseTypeDef",
-    "UpdateAuthorizerResponseTypeDef",
-    "UpdateBillingGroupResponseTypeDef",
-    "UpdateCustomMetricResponseTypeDef",
-    "UpdateDimensionResponseTypeDef",
-    "UpdateDomainConfigurationResponseTypeDef",
-    "UpdateDynamicThingGroupResponseTypeDef",
-    "UpdateMitigationActionResponseTypeDef",
-    "UpdateRoleAliasResponseTypeDef",
-    "UpdateScheduledAuditResponseTypeDef",
-    "UpdateStreamResponseTypeDef",
-    "UpdateThingGroupResponseTypeDef",
+    "AssetPropertyValueTypeDef",
     "CreateThingRequestRequestTypeDef",
     "ThingGroupPropertiesTypeDef",
     "UpdateThingRequestRequestTypeDef",
     "ListAuditMitigationActionsExecutionsResponseTypeDef",
     "ListAuditMitigationActionsTasksResponseTypeDef",
     "StartAuditMitigationActionsTaskRequestRequestTypeDef",
     "DescribeAccountAuditConfigurationResponseTypeDef",
     "UpdateAccountAuditConfigurationRequestRequestTypeDef",
     "ListAuditTasksResponseTypeDef",
     "TestAuthorizationRequestRequestTypeDef",
-    "UpdateDomainConfigurationRequestRequestTypeDef",
     "DescribeAuthorizerResponseTypeDef",
     "DescribeDefaultAuthorizerResponseTypeDef",
     "ListAuthorizersResponseTypeDef",
     "AwsJobAbortConfigTypeDef",
     "AwsJobExponentialRolloutRateTypeDef",
     "BehaviorCriteriaTypeDef",
     "GetBehaviorModelTrainingSummariesResponseTypeDef",
@@ -521,21 +598,23 @@
     "CustomCodeSigningTypeDef",
     "DescribeEventConfigurationsResponseTypeDef",
     "UpdateEventConfigurationsRequestRequestTypeDef",
     "CreateAuthorizerRequestRequestTypeDef",
     "CreateBillingGroupRequestRequestTypeDef",
     "CreateCustomMetricRequestRequestTypeDef",
     "CreateDimensionRequestRequestTypeDef",
-    "CreateDomainConfigurationRequestRequestTypeDef",
     "CreateFleetMetricRequestRequestTypeDef",
     "CreatePolicyRequestRequestTypeDef",
     "CreateRoleAliasRequestRequestTypeDef",
     "CreateScheduledAuditRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "CreateDomainConfigurationRequestRequestTypeDef",
+    "UpdateDomainConfigurationRequestRequestTypeDef",
+    "SchedulingConfigTypeDef",
     "CreateKeysAndCertificateResponseTypeDef",
     "CreateProvisioningClaimResponseTypeDef",
     "CreateProvisioningTemplateRequestRequestTypeDef",
     "DescribeProvisioningTemplateResponseTypeDef",
     "UpdateProvisioningTemplateRequestRequestTypeDef",
     "CreateThingTypeRequestRequestTypeDef",
     "DescribeAuditTaskResponseTypeDef",
@@ -553,67 +632,16 @@
     "DynamoDBv2ActionTypeDef",
     "GetEffectivePoliciesResponseTypeDef",
     "ExponentialRolloutRateTypeDef",
     "ThingGroupIndexingConfigurationTypeDef",
     "StreamFileTypeDef",
     "FileLocationTypeDef",
     "ListFleetMetricsResponseTypeDef",
-    "GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef",
-    "ListActiveViolationsRequestListActiveViolationsPaginateTypeDef",
-    "ListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef",
-    "ListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef",
-    "ListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef",
-    "ListAuditTasksRequestListAuditTasksPaginateTypeDef",
-    "ListAuthorizersRequestListAuthorizersPaginateTypeDef",
-    "ListBillingGroupsRequestListBillingGroupsPaginateTypeDef",
-    "ListCACertificatesRequestListCACertificatesPaginateTypeDef",
-    "ListCertificatesByCARequestListCertificatesByCAPaginateTypeDef",
-    "ListCertificatesRequestListCertificatesPaginateTypeDef",
-    "ListCustomMetricsRequestListCustomMetricsPaginateTypeDef",
-    "ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef",
-    "ListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef",
-    "ListDimensionsRequestListDimensionsPaginateTypeDef",
-    "ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef",
-    "ListFleetMetricsRequestListFleetMetricsPaginateTypeDef",
-    "ListIndicesRequestListIndicesPaginateTypeDef",
-    "ListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef",
-    "ListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef",
-    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
-    "ListJobsRequestListJobsPaginateTypeDef",
-    "ListMetricValuesRequestListMetricValuesPaginateTypeDef",
-    "ListMitigationActionsRequestListMitigationActionsPaginateTypeDef",
-    "ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef",
-    "ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef",
-    "ListPoliciesRequestListPoliciesPaginateTypeDef",
-    "ListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef",
-    "ListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef",
-    "ListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef",
-    "ListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef",
-    "ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef",
-    "ListRoleAliasesRequestListRoleAliasesPaginateTypeDef",
-    "ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef",
-    "ListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef",
-    "ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef",
-    "ListStreamsRequestListStreamsPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    "ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
-    "ListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef",
-    "ListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef",
-    "ListThingGroupsRequestListThingGroupsPaginateTypeDef",
-    "ListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef",
-    "ListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef",
-    "ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef",
-    "ListThingTypesRequestListThingTypesPaginateTypeDef",
-    "ListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef",
-    "ListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef",
-    "ListThingsRequestListThingsPaginateTypeDef",
-    "ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef",
-    "ListTopicRulesRequestListTopicRulesPaginateTypeDef",
-    "ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef",
-    "ListViolationEventsRequestListViolationEventsPaginateTypeDef",
+    "GetPackageConfigurationResponseTypeDef",
+    "UpdatePackageConfigurationRequestRequestTypeDef",
     "GetPercentilesResponseTypeDef",
     "GetStatisticsResponseTypeDef",
     "ListBillingGroupsResponseTypeDef",
     "ListThingGroupsForThingResponseTypeDef",
     "ListThingGroupsResponseTypeDef",
     "ThingGroupMetadataTypeDef",
     "HttpAuthorizationTypeDef",
@@ -624,14 +652,16 @@
     "JobExecutionsRetryConfigTypeDef",
     "ListJobsResponseTypeDef",
     "ListJobTemplatesResponseTypeDef",
     "ListManagedJobTemplatesResponseTypeDef",
     "ListMitigationActionsResponseTypeDef",
     "ListOTAUpdatesResponseTypeDef",
     "ListOutgoingCertificatesResponseTypeDef",
+    "ListPackageVersionsResponseTypeDef",
+    "ListPackagesResponseTypeDef",
     "ListPolicyVersionsResponseTypeDef",
     "ListProvisioningTemplateVersionsResponseTypeDef",
     "ListProvisioningTemplatesResponseTypeDef",
     "ListScheduledAuditsResponseTypeDef",
     "ListSecurityProfilesResponseTypeDef",
     "ListStreamsResponseTypeDef",
     "ListTargetsForSecurityProfileResponseTypeDef",
@@ -1226,22 +1256,21 @@
 class AssociateTargetsWithJobRequestRequestTypeDef(
     _RequiredAssociateTargetsWithJobRequestRequestTypeDef,
     _OptionalAssociateTargetsWithJobRequestRequestTypeDef,
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateTargetsWithJobResponseTypeDef = TypedDict(
+    "AssociateTargetsWithJobResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "jobArn": str,
+        "jobId": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachPolicyRequestRequestTypeDef = TypedDict(
     "AttachPolicyRequestRequestTypeDef",
     {
         "policyName": str,
@@ -1621,14 +1650,24 @@
 
 class CancelJobRequestRequestTypeDef(
     _RequiredCancelJobRequestRequestTypeDef, _OptionalCancelJobRequestRequestTypeDef
 ):
     pass
 
 
+CancelJobResponseTypeDef = TypedDict(
+    "CancelJobResponseTypeDef",
+    {
+        "jobArn": str,
+        "jobId": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TransferDataTypeDef = TypedDict(
     "TransferDataTypeDef",
     {
         "transferMessage": str,
         "rejectReason": str,
         "transferDate": datetime,
         "acceptDate": datetime,
@@ -1696,14 +1735,33 @@
 )
 
 
 class TagTypeDef(_RequiredTagTypeDef, _OptionalTagTypeDef):
     pass
 
 
+CreateAuthorizerResponseTypeDef = TypedDict(
+    "CreateAuthorizerResponseTypeDef",
+    {
+        "authorizerName": str,
+        "authorizerArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateBillingGroupResponseTypeDef = TypedDict(
+    "CreateBillingGroupResponseTypeDef",
+    {
+        "billingGroupName": str,
+        "billingGroupArn": str,
+        "billingGroupId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateCertificateFromCsrRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCertificateFromCsrRequestRequestTypeDef",
     {
         "certificateSigningRequest": str,
     },
 )
 _OptionalCreateCertificateFromCsrRequestRequestTypeDef = TypedDict(
@@ -1718,41 +1776,125 @@
 class CreateCertificateFromCsrRequestRequestTypeDef(
     _RequiredCreateCertificateFromCsrRequestRequestTypeDef,
     _OptionalCreateCertificateFromCsrRequestRequestTypeDef,
 ):
     pass
 
 
-PresignedUrlConfigTypeDef = TypedDict(
-    "PresignedUrlConfigTypeDef",
+CreateCertificateFromCsrResponseTypeDef = TypedDict(
+    "CreateCertificateFromCsrResponseTypeDef",
     {
-        "roleArn": str,
-        "expiresInSec": int,
+        "certificateArn": str,
+        "certificateId": str,
+        "certificatePem": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateCustomMetricResponseTypeDef = TypedDict(
+    "CreateCustomMetricResponseTypeDef",
+    {
+        "metricName": str,
+        "metricArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDimensionResponseTypeDef = TypedDict(
+    "CreateDimensionResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TlsConfigTypeDef = TypedDict(
+    "TlsConfigTypeDef",
+    {
+        "securityPolicy": str,
     },
     total=False,
 )
 
-SchedulingConfigTypeDef = TypedDict(
-    "SchedulingConfigTypeDef",
+CreateDomainConfigurationResponseTypeDef = TypedDict(
+    "CreateDomainConfigurationResponseTypeDef",
     {
-        "startTime": str,
-        "endTime": str,
-        "endBehavior": JobEndBehaviorType,
+        "domainConfigurationName": str,
+        "domainConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDynamicThingGroupResponseTypeDef = TypedDict(
+    "CreateDynamicThingGroupResponseTypeDef",
+    {
+        "thingGroupName": str,
+        "thingGroupArn": str,
+        "thingGroupId": str,
+        "indexName": str,
+        "queryString": str,
+        "queryVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFleetMetricResponseTypeDef = TypedDict(
+    "CreateFleetMetricResponseTypeDef",
+    {
+        "metricName": str,
+        "metricArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PresignedUrlConfigTypeDef = TypedDict(
+    "PresignedUrlConfigTypeDef",
+    {
+        "roleArn": str,
+        "expiresInSec": int,
     },
     total=False,
 )
 
 TimeoutConfigTypeDef = TypedDict(
     "TimeoutConfigTypeDef",
     {
         "inProgressTimeoutInMinutes": int,
     },
     total=False,
 )
 
+CreateJobResponseTypeDef = TypedDict(
+    "CreateJobResponseTypeDef",
+    {
+        "jobArn": str,
+        "jobId": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+MaintenanceWindowTypeDef = TypedDict(
+    "MaintenanceWindowTypeDef",
+    {
+        "startTime": str,
+        "durationInMinutes": int,
+    },
+)
+
+CreateJobTemplateResponseTypeDef = TypedDict(
+    "CreateJobTemplateResponseTypeDef",
+    {
+        "jobTemplateArn": str,
+        "jobTemplateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateKeysAndCertificateRequestRequestTypeDef = TypedDict(
     "CreateKeysAndCertificateRequestRequestTypeDef",
     {
         "setAsActive": bool,
     },
     total=False,
 )
@@ -1762,14 +1904,119 @@
     {
         "PublicKey": str,
         "PrivateKey": str,
     },
     total=False,
 )
 
+CreateMitigationActionResponseTypeDef = TypedDict(
+    "CreateMitigationActionResponseTypeDef",
+    {
+        "actionArn": str,
+        "actionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateOTAUpdateResponseTypeDef = TypedDict(
+    "CreateOTAUpdateResponseTypeDef",
+    {
+        "otaUpdateId": str,
+        "awsIotJobId": str,
+        "otaUpdateArn": str,
+        "awsIotJobArn": str,
+        "otaUpdateStatus": OTAUpdateStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreatePackageRequestRequestTypeDef = TypedDict(
+    "_RequiredCreatePackageRequestRequestTypeDef",
+    {
+        "packageName": str,
+    },
+)
+_OptionalCreatePackageRequestRequestTypeDef = TypedDict(
+    "_OptionalCreatePackageRequestRequestTypeDef",
+    {
+        "description": str,
+        "tags": Mapping[str, str],
+        "clientToken": str,
+    },
+    total=False,
+)
+
+
+class CreatePackageRequestRequestTypeDef(
+    _RequiredCreatePackageRequestRequestTypeDef, _OptionalCreatePackageRequestRequestTypeDef
+):
+    pass
+
+
+CreatePackageResponseTypeDef = TypedDict(
+    "CreatePackageResponseTypeDef",
+    {
+        "packageName": str,
+        "packageArn": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreatePackageVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreatePackageVersionRequestRequestTypeDef",
+    {
+        "packageName": str,
+        "versionName": str,
+    },
+)
+_OptionalCreatePackageVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreatePackageVersionRequestRequestTypeDef",
+    {
+        "description": str,
+        "attributes": Mapping[str, str],
+        "tags": Mapping[str, str],
+        "clientToken": str,
+    },
+    total=False,
+)
+
+
+class CreatePackageVersionRequestRequestTypeDef(
+    _RequiredCreatePackageVersionRequestRequestTypeDef,
+    _OptionalCreatePackageVersionRequestRequestTypeDef,
+):
+    pass
+
+
+CreatePackageVersionResponseTypeDef = TypedDict(
+    "CreatePackageVersionResponseTypeDef",
+    {
+        "packageVersionArn": str,
+        "packageName": str,
+        "versionName": str,
+        "description": str,
+        "attributes": Dict[str, str],
+        "status": PackageVersionStatusType,
+        "errorReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePolicyResponseTypeDef = TypedDict(
+    "CreatePolicyResponseTypeDef",
+    {
+        "policyName": str,
+        "policyArn": str,
+        "policyDocument": str,
+        "policyVersionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreatePolicyVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePolicyVersionRequestRequestTypeDef",
     {
         "policyName": str,
         "policyDocument": str,
     },
 )
@@ -1785,14 +2032,25 @@
 class CreatePolicyVersionRequestRequestTypeDef(
     _RequiredCreatePolicyVersionRequestRequestTypeDef,
     _OptionalCreatePolicyVersionRequestRequestTypeDef,
 ):
     pass
 
 
+CreatePolicyVersionResponseTypeDef = TypedDict(
+    "CreatePolicyVersionResponseTypeDef",
+    {
+        "policyArn": str,
+        "policyDocument": str,
+        "policyVersionId": str,
+        "isDefaultVersion": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateProvisioningClaimRequestRequestTypeDef = TypedDict(
     "CreateProvisioningClaimRequestRequestTypeDef",
     {
         "templateName": str,
     },
 )
 
@@ -1811,14 +2069,24 @@
 )
 
 
 class ProvisioningHookTypeDef(_RequiredProvisioningHookTypeDef, _OptionalProvisioningHookTypeDef):
     pass
 
 
+CreateProvisioningTemplateResponseTypeDef = TypedDict(
+    "CreateProvisioningTemplateResponseTypeDef",
+    {
+        "templateArn": str,
+        "templateName": str,
+        "defaultVersionId": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateProvisioningTemplateVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateProvisioningTemplateVersionRequestRequestTypeDef",
     {
         "templateName": str,
         "templateBody": str,
     },
 )
@@ -1834,23 +2102,101 @@
 class CreateProvisioningTemplateVersionRequestRequestTypeDef(
     _RequiredCreateProvisioningTemplateVersionRequestRequestTypeDef,
     _OptionalCreateProvisioningTemplateVersionRequestRequestTypeDef,
 ):
     pass
 
 
+CreateProvisioningTemplateVersionResponseTypeDef = TypedDict(
+    "CreateProvisioningTemplateVersionResponseTypeDef",
+    {
+        "templateArn": str,
+        "templateName": str,
+        "versionId": int,
+        "isDefaultVersion": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateRoleAliasResponseTypeDef = TypedDict(
+    "CreateRoleAliasResponseTypeDef",
+    {
+        "roleAlias": str,
+        "roleAliasArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateScheduledAuditResponseTypeDef = TypedDict(
+    "CreateScheduledAuditResponseTypeDef",
+    {
+        "scheduledAuditArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateSecurityProfileResponseTypeDef = TypedDict(
+    "CreateSecurityProfileResponseTypeDef",
+    {
+        "securityProfileName": str,
+        "securityProfileArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateStreamResponseTypeDef = TypedDict(
+    "CreateStreamResponseTypeDef",
+    {
+        "streamId": str,
+        "streamArn": str,
+        "description": str,
+        "streamVersion": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateThingGroupResponseTypeDef = TypedDict(
+    "CreateThingGroupResponseTypeDef",
+    {
+        "thingGroupName": str,
+        "thingGroupArn": str,
+        "thingGroupId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateThingResponseTypeDef = TypedDict(
+    "CreateThingResponseTypeDef",
+    {
+        "thingName": str,
+        "thingArn": str,
+        "thingId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ThingTypePropertiesTypeDef = TypedDict(
     "ThingTypePropertiesTypeDef",
     {
         "thingTypeDescription": str,
         "searchableAttributes": Sequence[str],
     },
     total=False,
 )
 
+CreateThingTypeResponseTypeDef = TypedDict(
+    "CreateThingTypeResponseTypeDef",
+    {
+        "thingTypeName": str,
+        "thingTypeArn": str,
+        "thingTypeId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteAccountAuditConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteAccountAuditConfigurationRequestRequestTypeDef",
     {
         "deleteScheduledAudits": bool,
     },
     total=False,
 )
@@ -2055,14 +2401,58 @@
 
 class DeleteOTAUpdateRequestRequestTypeDef(
     _RequiredDeleteOTAUpdateRequestRequestTypeDef, _OptionalDeleteOTAUpdateRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredDeletePackageRequestRequestTypeDef = TypedDict(
+    "_RequiredDeletePackageRequestRequestTypeDef",
+    {
+        "packageName": str,
+    },
+)
+_OptionalDeletePackageRequestRequestTypeDef = TypedDict(
+    "_OptionalDeletePackageRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+
+class DeletePackageRequestRequestTypeDef(
+    _RequiredDeletePackageRequestRequestTypeDef, _OptionalDeletePackageRequestRequestTypeDef
+):
+    pass
+
+
+_RequiredDeletePackageVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredDeletePackageVersionRequestRequestTypeDef",
+    {
+        "packageName": str,
+        "versionName": str,
+    },
+)
+_OptionalDeletePackageVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalDeletePackageVersionRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+
+class DeletePackageVersionRequestRequestTypeDef(
+    _RequiredDeletePackageVersionRequestRequestTypeDef,
+    _OptionalDeletePackageVersionRequestRequestTypeDef,
+):
+    pass
+
+
 DeletePolicyRequestRequestTypeDef = TypedDict(
     "DeletePolicyRequestRequestTypeDef",
     {
         "policyName": str,
     },
 )
 
@@ -2313,28 +2703,54 @@
 DescribeCustomMetricRequestRequestTypeDef = TypedDict(
     "DescribeCustomMetricRequestRequestTypeDef",
     {
         "metricName": str,
     },
 )
 
+DescribeCustomMetricResponseTypeDef = TypedDict(
+    "DescribeCustomMetricResponseTypeDef",
+    {
+        "metricName": str,
+        "metricArn": str,
+        "metricType": CustomMetricTypeType,
+        "displayName": str,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDetectMitigationActionsTaskRequestRequestTypeDef = TypedDict(
     "DescribeDetectMitigationActionsTaskRequestRequestTypeDef",
     {
         "taskId": str,
     },
 )
 
 DescribeDimensionRequestRequestTypeDef = TypedDict(
     "DescribeDimensionRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+DescribeDimensionResponseTypeDef = TypedDict(
+    "DescribeDimensionResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "type": Literal["TOPIC_FILTER"],
+        "stringValues": List[str],
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDomainConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeDomainConfigurationRequestRequestTypeDef",
     {
         "domainConfigurationName": str,
     },
 )
 
@@ -2352,28 +2768,46 @@
     "DescribeEndpointRequestRequestTypeDef",
     {
         "endpointType": str,
     },
     total=False,
 )
 
+DescribeEndpointResponseTypeDef = TypedDict(
+    "DescribeEndpointResponseTypeDef",
+    {
+        "endpointAddress": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeFleetMetricRequestRequestTypeDef = TypedDict(
     "DescribeFleetMetricRequestRequestTypeDef",
     {
         "metricName": str,
     },
 )
 
 DescribeIndexRequestRequestTypeDef = TypedDict(
     "DescribeIndexRequestRequestTypeDef",
     {
         "indexName": str,
     },
 )
 
+DescribeIndexResponseTypeDef = TypedDict(
+    "DescribeIndexResponseTypeDef",
+    {
+        "indexName": str,
+        "indexStatus": IndexStatusType,
+        "schema": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeJobExecutionRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeJobExecutionRequestRequestTypeDef",
     {
         "jobId": str,
         "thingName": str,
     },
 )
@@ -2459,14 +2893,25 @@
     "DescribeProvisioningTemplateVersionRequestRequestTypeDef",
     {
         "templateName": str,
         "versionId": int,
     },
 )
 
+DescribeProvisioningTemplateVersionResponseTypeDef = TypedDict(
+    "DescribeProvisioningTemplateVersionResponseTypeDef",
+    {
+        "versionId": int,
+        "creationDate": datetime,
+        "templateBody": str,
+        "isDefaultVersion": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeRoleAliasRequestRequestTypeDef = TypedDict(
     "DescribeRoleAliasRequestRequestTypeDef",
     {
         "roleAlias": str,
     },
 )
 
@@ -2487,14 +2932,27 @@
 DescribeScheduledAuditRequestRequestTypeDef = TypedDict(
     "DescribeScheduledAuditRequestRequestTypeDef",
     {
         "scheduledAuditName": str,
     },
 )
 
+DescribeScheduledAuditResponseTypeDef = TypedDict(
+    "DescribeScheduledAuditResponseTypeDef",
+    {
+        "frequency": AuditFrequencyType,
+        "dayOfMonth": str,
+        "dayOfWeek": DayOfWeekType,
+        "targetCheckNames": List[str],
+        "scheduledAuditName": str,
+        "scheduledAuditArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeSecurityProfileRequestRequestTypeDef = TypedDict(
     "DescribeSecurityProfileRequestRequestTypeDef",
     {
         "securityProfileName": str,
     },
 )
 
@@ -2515,21 +2973,55 @@
 DescribeThingRegistrationTaskRequestRequestTypeDef = TypedDict(
     "DescribeThingRegistrationTaskRequestRequestTypeDef",
     {
         "taskId": str,
     },
 )
 
+DescribeThingRegistrationTaskResponseTypeDef = TypedDict(
+    "DescribeThingRegistrationTaskResponseTypeDef",
+    {
+        "taskId": str,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "templateBody": str,
+        "inputFileBucket": str,
+        "inputFileKey": str,
+        "roleArn": str,
+        "status": StatusType,
+        "message": str,
+        "successCount": int,
+        "failureCount": int,
+        "percentageProgress": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeThingRequestRequestTypeDef = TypedDict(
     "DescribeThingRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 
+DescribeThingResponseTypeDef = TypedDict(
+    "DescribeThingResponseTypeDef",
+    {
+        "defaultClientId": str,
+        "thingName": str,
+        "thingId": str,
+        "thingArn": str,
+        "thingTypeName": str,
+        "attributes": Dict[str, str],
+        "version": int,
+        "billingGroupName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeThingTypeRequestRequestTypeDef = TypedDict(
     "DescribeThingTypeRequestRequestTypeDef",
     {
         "thingTypeName": str,
     },
 )
 
@@ -2658,14 +3150,21 @@
         "policyName": str,
         "policyArn": str,
         "policyDocument": str,
     },
     total=False,
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableIoTLoggingParamsTypeDef = TypedDict(
     "EnableIoTLoggingParamsTypeDef",
     {
         "roleArnForLogging": str,
         "logLevel": LogLevelType,
     },
 )
@@ -2728,22 +3227,23 @@
     {
         "metricName": str,
         "metricArn": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
+GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef = (
+    TypedDict(
+        "GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef",
+        {
+            "securityProfileName": str,
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
 )
 
 GetBehaviorModelTrainingSummariesRequestRequestTypeDef = TypedDict(
     "GetBehaviorModelTrainingSummariesRequestRequestTypeDef",
     {
         "securityProfileName": str,
         "maxResults": int,
@@ -2771,14 +3271,22 @@
 
 class GetCardinalityRequestRequestTypeDef(
     _RequiredGetCardinalityRequestRequestTypeDef, _OptionalGetCardinalityRequestRequestTypeDef
 ):
     pass
 
 
+GetCardinalityResponseTypeDef = TypedDict(
+    "GetCardinalityResponseTypeDef",
+    {
+        "cardinality": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetEffectivePoliciesRequestRequestTypeDef = TypedDict(
     "GetEffectivePoliciesRequestRequestTypeDef",
     {
         "principal": str,
         "cognitoIdentityPoolId": str,
         "thingName": str,
     },
@@ -2788,21 +3296,91 @@
 GetJobDocumentRequestRequestTypeDef = TypedDict(
     "GetJobDocumentRequestRequestTypeDef",
     {
         "jobId": str,
     },
 )
 
+GetJobDocumentResponseTypeDef = TypedDict(
+    "GetJobDocumentResponseTypeDef",
+    {
+        "document": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetLoggingOptionsResponseTypeDef = TypedDict(
+    "GetLoggingOptionsResponseTypeDef",
+    {
+        "roleArn": str,
+        "logLevel": LogLevelType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetOTAUpdateRequestRequestTypeDef = TypedDict(
     "GetOTAUpdateRequestRequestTypeDef",
     {
         "otaUpdateId": str,
     },
 )
 
+VersionUpdateByJobsConfigTypeDef = TypedDict(
+    "VersionUpdateByJobsConfigTypeDef",
+    {
+        "enabled": bool,
+        "roleArn": str,
+    },
+    total=False,
+)
+
+GetPackageRequestRequestTypeDef = TypedDict(
+    "GetPackageRequestRequestTypeDef",
+    {
+        "packageName": str,
+    },
+)
+
+GetPackageResponseTypeDef = TypedDict(
+    "GetPackageResponseTypeDef",
+    {
+        "packageName": str,
+        "packageArn": str,
+        "description": str,
+        "defaultVersionName": str,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetPackageVersionRequestRequestTypeDef = TypedDict(
+    "GetPackageVersionRequestRequestTypeDef",
+    {
+        "packageName": str,
+        "versionName": str,
+    },
+)
+
+GetPackageVersionResponseTypeDef = TypedDict(
+    "GetPackageVersionResponseTypeDef",
+    {
+        "packageVersionArn": str,
+        "packageName": str,
+        "versionName": str,
+        "description": str,
+        "attributes": Dict[str, str],
+        "status": PackageVersionStatusType,
+        "errorReason": str,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetPercentilesRequestRequestTypeDef = TypedDict(
     "_RequiredGetPercentilesRequestRequestTypeDef",
     {
         "queryString": str,
     },
 )
 _OptionalGetPercentilesRequestRequestTypeDef = TypedDict(
@@ -2835,22 +3413,59 @@
 GetPolicyRequestRequestTypeDef = TypedDict(
     "GetPolicyRequestRequestTypeDef",
     {
         "policyName": str,
     },
 )
 
+GetPolicyResponseTypeDef = TypedDict(
+    "GetPolicyResponseTypeDef",
+    {
+        "policyName": str,
+        "policyArn": str,
+        "policyDocument": str,
+        "defaultVersionId": str,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "generationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetPolicyVersionRequestRequestTypeDef = TypedDict(
     "GetPolicyVersionRequestRequestTypeDef",
     {
         "policyName": str,
         "policyVersionId": str,
     },
 )
 
+GetPolicyVersionResponseTypeDef = TypedDict(
+    "GetPolicyVersionResponseTypeDef",
+    {
+        "policyArn": str,
+        "policyName": str,
+        "policyDocument": str,
+        "policyVersionId": str,
+        "isDefaultVersion": bool,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "generationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetRegistrationCodeResponseTypeDef = TypedDict(
+    "GetRegistrationCodeResponseTypeDef",
+    {
+        "registrationCode": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetStatisticsRequestRequestTypeDef = TypedDict(
     "_RequiredGetStatisticsRequestRequestTypeDef",
     {
         "queryString": str,
     },
 )
 _OptionalGetStatisticsRequestRequestTypeDef = TypedDict(
@@ -2895,14 +3510,24 @@
 GetTopicRuleRequestRequestTypeDef = TypedDict(
     "GetTopicRuleRequestRequestTypeDef",
     {
         "ruleName": str,
     },
 )
 
+GetV2LoggingOptionsResponseTypeDef = TypedDict(
+    "GetV2LoggingOptionsResponseTypeDef",
+    {
+        "roleArn": str,
+        "defaultLogLevel": LogLevelType,
+        "disableAllLogs": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GroupNameAndArnTypeDef = TypedDict(
     "GroupNameAndArnTypeDef",
     {
         "groupName": str,
         "groupArn": str,
     },
     total=False,
@@ -3043,28 +3668,72 @@
         "jobTemplateId": str,
         "description": str,
         "createdAt": datetime,
     },
     total=False,
 )
 
+ScheduledJobRolloutTypeDef = TypedDict(
+    "ScheduledJobRolloutTypeDef",
+    {
+        "startTime": str,
+    },
+    total=False,
+)
+
+ListActiveViolationsRequestListActiveViolationsPaginateTypeDef = TypedDict(
+    "ListActiveViolationsRequestListActiveViolationsPaginateTypeDef",
+    {
+        "thingName": str,
+        "securityProfileName": str,
+        "behaviorCriteriaType": BehaviorCriteriaTypeType,
+        "listSuppressedAlerts": bool,
+        "verificationState": VerificationStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListActiveViolationsRequestRequestTypeDef = TypedDict(
     "ListActiveViolationsRequestRequestTypeDef",
     {
         "thingName": str,
         "securityProfileName": str,
         "behaviorCriteriaType": BehaviorCriteriaTypeType,
         "listSuppressedAlerts": bool,
         "verificationState": VerificationStateType,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef",
+    {
+        "target": str,
+    },
+)
+_OptionalListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef",
+    {
+        "recursive": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef(
+    _RequiredListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef,
+    _OptionalListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAttachedPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListAttachedPoliciesRequestRequestTypeDef",
     {
         "target": str,
     },
 )
 _OptionalListAttachedPoliciesRequestRequestTypeDef = TypedDict(
@@ -3081,14 +3750,38 @@
 class ListAttachedPoliciesRequestRequestTypeDef(
     _RequiredListAttachedPoliciesRequestRequestTypeDef,
     _OptionalListAttachedPoliciesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef = TypedDict(
+    "_RequiredListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef",
+    {
+        "taskId": str,
+        "findingId": str,
+    },
+)
+_OptionalListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef = TypedDict(
+    "_OptionalListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef",
+    {
+        "actionStatus": AuditMitigationActionsExecutionStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef(
+    _RequiredListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef,
+    _OptionalListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAuditMitigationActionsExecutionsRequestRequestTypeDef = TypedDict(
     "_RequiredListAuditMitigationActionsExecutionsRequestRequestTypeDef",
     {
         "taskId": str,
         "findingId": str,
     },
 )
@@ -3106,14 +3799,40 @@
 class ListAuditMitigationActionsExecutionsRequestRequestTypeDef(
     _RequiredListAuditMitigationActionsExecutionsRequestRequestTypeDef,
     _OptionalListAuditMitigationActionsExecutionsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef = TypedDict(
+    "_RequiredListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef",
+    {
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+    },
+)
+_OptionalListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef = TypedDict(
+    "_OptionalListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef",
+    {
+        "auditTaskId": str,
+        "findingId": str,
+        "taskStatus": AuditMitigationActionsTaskStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef(
+    _RequiredListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef,
+    _OptionalListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAuditMitigationActionsTasksRequestRequestTypeDef = TypedDict(
     "_RequiredListAuditMitigationActionsTasksRequestRequestTypeDef",
     {
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
     },
 )
@@ -3133,14 +3852,39 @@
 class ListAuditMitigationActionsTasksRequestRequestTypeDef(
     _RequiredListAuditMitigationActionsTasksRequestRequestTypeDef,
     _OptionalListAuditMitigationActionsTasksRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListAuditTasksRequestListAuditTasksPaginateTypeDef = TypedDict(
+    "_RequiredListAuditTasksRequestListAuditTasksPaginateTypeDef",
+    {
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+    },
+)
+_OptionalListAuditTasksRequestListAuditTasksPaginateTypeDef = TypedDict(
+    "_OptionalListAuditTasksRequestListAuditTasksPaginateTypeDef",
+    {
+        "taskType": AuditTaskTypeType,
+        "taskStatus": AuditTaskStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAuditTasksRequestListAuditTasksPaginateTypeDef(
+    _RequiredListAuditTasksRequestListAuditTasksPaginateTypeDef,
+    _OptionalListAuditTasksRequestListAuditTasksPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAuditTasksRequestRequestTypeDef = TypedDict(
     "_RequiredListAuditTasksRequestRequestTypeDef",
     {
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
     },
 )
@@ -3158,46 +3902,98 @@
 
 class ListAuditTasksRequestRequestTypeDef(
     _RequiredListAuditTasksRequestRequestTypeDef, _OptionalListAuditTasksRequestRequestTypeDef
 ):
     pass
 
 
+ListAuthorizersRequestListAuthorizersPaginateTypeDef = TypedDict(
+    "ListAuthorizersRequestListAuthorizersPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "status": AuthorizerStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAuthorizersRequestRequestTypeDef = TypedDict(
     "ListAuthorizersRequestRequestTypeDef",
     {
         "pageSize": int,
         "marker": str,
         "ascendingOrder": bool,
         "status": AuthorizerStatusType,
     },
     total=False,
 )
 
+ListBillingGroupsRequestListBillingGroupsPaginateTypeDef = TypedDict(
+    "ListBillingGroupsRequestListBillingGroupsPaginateTypeDef",
+    {
+        "namePrefixFilter": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBillingGroupsRequestRequestTypeDef = TypedDict(
     "ListBillingGroupsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "namePrefixFilter": str,
     },
     total=False,
 )
 
+ListCACertificatesRequestListCACertificatesPaginateTypeDef = TypedDict(
+    "ListCACertificatesRequestListCACertificatesPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "templateName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCACertificatesRequestRequestTypeDef = TypedDict(
     "ListCACertificatesRequestRequestTypeDef",
     {
         "pageSize": int,
         "marker": str,
         "ascendingOrder": bool,
         "templateName": str,
     },
     total=False,
 )
 
+_RequiredListCertificatesByCARequestListCertificatesByCAPaginateTypeDef = TypedDict(
+    "_RequiredListCertificatesByCARequestListCertificatesByCAPaginateTypeDef",
+    {
+        "caCertificateId": str,
+    },
+)
+_OptionalListCertificatesByCARequestListCertificatesByCAPaginateTypeDef = TypedDict(
+    "_OptionalListCertificatesByCARequestListCertificatesByCAPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListCertificatesByCARequestListCertificatesByCAPaginateTypeDef(
+    _RequiredListCertificatesByCARequestListCertificatesByCAPaginateTypeDef,
+    _OptionalListCertificatesByCARequestListCertificatesByCAPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListCertificatesByCARequestRequestTypeDef = TypedDict(
     "_RequiredListCertificatesByCARequestRequestTypeDef",
     {
         "caCertificateId": str,
     },
 )
 _OptionalListCertificatesByCARequestRequestTypeDef = TypedDict(
@@ -3214,47 +4010,109 @@
 class ListCertificatesByCARequestRequestTypeDef(
     _RequiredListCertificatesByCARequestRequestTypeDef,
     _OptionalListCertificatesByCARequestRequestTypeDef,
 ):
     pass
 
 
+ListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
+    "ListCertificatesRequestListCertificatesPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCertificatesRequestRequestTypeDef = TypedDict(
     "ListCertificatesRequestRequestTypeDef",
     {
         "pageSize": int,
         "marker": str,
         "ascendingOrder": bool,
     },
     total=False,
 )
 
+ListCustomMetricsRequestListCustomMetricsPaginateTypeDef = TypedDict(
+    "ListCustomMetricsRequestListCustomMetricsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCustomMetricsRequestRequestTypeDef = TypedDict(
     "ListCustomMetricsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListCustomMetricsResponseTypeDef = TypedDict(
+    "ListCustomMetricsResponseTypeDef",
+    {
+        "metricNames": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef = TypedDict(
+    "ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef",
+    {
+        "taskId": str,
+        "violationId": str,
+        "thingName": str,
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDetectMitigationActionsExecutionsRequestRequestTypeDef = TypedDict(
     "ListDetectMitigationActionsExecutionsRequestRequestTypeDef",
     {
         "taskId": str,
         "violationId": str,
         "thingName": str,
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef = TypedDict(
+    "_RequiredListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef",
+    {
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+    },
+)
+_OptionalListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef = TypedDict(
+    "_OptionalListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef(
+    _RequiredListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef,
+    _OptionalListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDetectMitigationActionsTasksRequestRequestTypeDef = TypedDict(
     "_RequiredListDetectMitigationActionsTasksRequestRequestTypeDef",
     {
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
     },
 )
@@ -3271,51 +4129,125 @@
 class ListDetectMitigationActionsTasksRequestRequestTypeDef(
     _RequiredListDetectMitigationActionsTasksRequestRequestTypeDef,
     _OptionalListDetectMitigationActionsTasksRequestRequestTypeDef,
 ):
     pass
 
 
+ListDimensionsRequestListDimensionsPaginateTypeDef = TypedDict(
+    "ListDimensionsRequestListDimensionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDimensionsRequestRequestTypeDef = TypedDict(
     "ListDimensionsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListDimensionsResponseTypeDef = TypedDict(
+    "ListDimensionsResponseTypeDef",
+    {
+        "dimensionNames": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef = TypedDict(
+    "ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef",
+    {
+        "serviceType": ServiceTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDomainConfigurationsRequestRequestTypeDef = TypedDict(
     "ListDomainConfigurationsRequestRequestTypeDef",
     {
         "marker": str,
         "pageSize": int,
         "serviceType": ServiceTypeType,
     },
     total=False,
 )
 
+ListFleetMetricsRequestListFleetMetricsPaginateTypeDef = TypedDict(
+    "ListFleetMetricsRequestListFleetMetricsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFleetMetricsRequestRequestTypeDef = TypedDict(
     "ListFleetMetricsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListIndicesRequestListIndicesPaginateTypeDef = TypedDict(
+    "ListIndicesRequestListIndicesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListIndicesRequestRequestTypeDef = TypedDict(
     "ListIndicesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListIndicesResponseTypeDef = TypedDict(
+    "ListIndicesResponseTypeDef",
+    {
+        "indexNames": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef = TypedDict(
+    "_RequiredListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef",
+    {
+        "jobId": str,
+    },
+)
+_OptionalListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef = TypedDict(
+    "_OptionalListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef",
+    {
+        "status": JobExecutionStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef(
+    _RequiredListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef,
+    _OptionalListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListJobExecutionsForJobRequestRequestTypeDef = TypedDict(
     "_RequiredListJobExecutionsForJobRequestRequestTypeDef",
     {
         "jobId": str,
     },
 )
 _OptionalListJobExecutionsForJobRequestRequestTypeDef = TypedDict(
@@ -3332,14 +4264,39 @@
 class ListJobExecutionsForJobRequestRequestTypeDef(
     _RequiredListJobExecutionsForJobRequestRequestTypeDef,
     _OptionalListJobExecutionsForJobRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef = TypedDict(
+    "_RequiredListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef",
+    {
+        "thingName": str,
+    },
+)
+_OptionalListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef = TypedDict(
+    "_OptionalListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef",
+    {
+        "status": JobExecutionStatusType,
+        "namespaceId": str,
+        "jobId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef(
+    _RequiredListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef,
+    _OptionalListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListJobExecutionsForThingRequestRequestTypeDef = TypedDict(
     "_RequiredListJobExecutionsForThingRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 _OptionalListJobExecutionsForThingRequestRequestTypeDef = TypedDict(
@@ -3358,37 +4315,67 @@
 class ListJobExecutionsForThingRequestRequestTypeDef(
     _RequiredListJobExecutionsForThingRequestRequestTypeDef,
     _OptionalListJobExecutionsForThingRequestRequestTypeDef,
 ):
     pass
 
 
+ListJobTemplatesRequestListJobTemplatesPaginateTypeDef = TypedDict(
+    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListJobTemplatesRequestRequestTypeDef = TypedDict(
     "ListJobTemplatesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListJobsRequestListJobsPaginateTypeDef = TypedDict(
+    "ListJobsRequestListJobsPaginateTypeDef",
+    {
+        "status": JobStatusType,
+        "targetSelection": TargetSelectionType,
+        "thingGroupName": str,
+        "thingGroupId": str,
+        "namespaceId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListJobsRequestRequestTypeDef = TypedDict(
     "ListJobsRequestRequestTypeDef",
     {
         "status": JobStatusType,
         "targetSelection": TargetSelectionType,
         "maxResults": int,
         "nextToken": str,
         "thingGroupName": str,
         "thingGroupId": str,
         "namespaceId": str,
     },
     total=False,
 )
 
+ListManagedJobTemplatesRequestListManagedJobTemplatesPaginateTypeDef = TypedDict(
+    "ListManagedJobTemplatesRequestListManagedJobTemplatesPaginateTypeDef",
+    {
+        "templateName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListManagedJobTemplatesRequestRequestTypeDef = TypedDict(
     "ListManagedJobTemplatesRequestRequestTypeDef",
     {
         "templateName": str,
         "maxResults": int,
         "nextToken": str,
     },
@@ -3403,14 +4390,41 @@
         "description": str,
         "environments": List[str],
         "templateVersion": str,
     },
     total=False,
 )
 
+_RequiredListMetricValuesRequestListMetricValuesPaginateTypeDef = TypedDict(
+    "_RequiredListMetricValuesRequestListMetricValuesPaginateTypeDef",
+    {
+        "thingName": str,
+        "metricName": str,
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+    },
+)
+_OptionalListMetricValuesRequestListMetricValuesPaginateTypeDef = TypedDict(
+    "_OptionalListMetricValuesRequestListMetricValuesPaginateTypeDef",
+    {
+        "dimensionName": str,
+        "dimensionValueOperator": DimensionValueOperatorType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListMetricValuesRequestListMetricValuesPaginateTypeDef(
+    _RequiredListMetricValuesRequestListMetricValuesPaginateTypeDef,
+    _OptionalListMetricValuesRequestListMetricValuesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListMetricValuesRequestRequestTypeDef = TypedDict(
     "_RequiredListMetricValuesRequestRequestTypeDef",
     {
         "thingName": str,
         "metricName": str,
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
@@ -3430,14 +4444,23 @@
 
 class ListMetricValuesRequestRequestTypeDef(
     _RequiredListMetricValuesRequestRequestTypeDef, _OptionalListMetricValuesRequestRequestTypeDef
 ):
     pass
 
 
+ListMitigationActionsRequestListMitigationActionsPaginateTypeDef = TypedDict(
+    "ListMitigationActionsRequestListMitigationActionsPaginateTypeDef",
+    {
+        "actionType": MitigationActionTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMitigationActionsRequestRequestTypeDef = TypedDict(
     "ListMitigationActionsRequestRequestTypeDef",
     {
         "actionType": MitigationActionTypeType,
         "maxResults": int,
         "nextToken": str,
     },
@@ -3450,14 +4473,23 @@
         "actionName": str,
         "actionArn": str,
         "creationDate": datetime,
     },
     total=False,
 )
 
+ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef = TypedDict(
+    "ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef",
+    {
+        "otaUpdateStatus": OTAUpdateStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOTAUpdatesRequestRequestTypeDef = TypedDict(
     "ListOTAUpdatesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "otaUpdateStatus": OTAUpdateStatusType,
     },
@@ -3470,14 +4502,23 @@
         "otaUpdateId": str,
         "otaUpdateArn": str,
         "creationDate": datetime,
     },
     total=False,
 )
 
+ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef = TypedDict(
+    "ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOutgoingCertificatesRequestRequestTypeDef = TypedDict(
     "ListOutgoingCertificatesRequestRequestTypeDef",
     {
         "pageSize": int,
         "marker": str,
         "ascendingOrder": bool,
     },
@@ -3493,24 +4534,143 @@
         "transferDate": datetime,
         "transferMessage": str,
         "creationDate": datetime,
     },
     total=False,
 )
 
+_RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
+    {
+        "packageName": str,
+    },
+)
+_OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
+    {
+        "status": PackageVersionStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPackageVersionsRequestListPackageVersionsPaginateTypeDef(
+    _RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
+    _OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
+):
+    pass
+
+
+_RequiredListPackageVersionsRequestRequestTypeDef = TypedDict(
+    "_RequiredListPackageVersionsRequestRequestTypeDef",
+    {
+        "packageName": str,
+    },
+)
+_OptionalListPackageVersionsRequestRequestTypeDef = TypedDict(
+    "_OptionalListPackageVersionsRequestRequestTypeDef",
+    {
+        "status": PackageVersionStatusType,
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+
+class ListPackageVersionsRequestRequestTypeDef(
+    _RequiredListPackageVersionsRequestRequestTypeDef,
+    _OptionalListPackageVersionsRequestRequestTypeDef,
+):
+    pass
+
+
+PackageVersionSummaryTypeDef = TypedDict(
+    "PackageVersionSummaryTypeDef",
+    {
+        "packageName": str,
+        "versionName": str,
+        "status": PackageVersionStatusType,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+    },
+    total=False,
+)
+
+ListPackagesRequestListPackagesPaginateTypeDef = TypedDict(
+    "ListPackagesRequestListPackagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListPackagesRequestRequestTypeDef = TypedDict(
+    "ListPackagesRequestRequestTypeDef",
+    {
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+PackageSummaryTypeDef = TypedDict(
+    "PackageSummaryTypeDef",
+    {
+        "packageName": str,
+        "defaultVersionName": str,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+    },
+    total=False,
+)
+
+ListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
+    "ListPoliciesRequestListPoliciesPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPoliciesRequestRequestTypeDef = TypedDict(
     "ListPoliciesRequestRequestTypeDef",
     {
         "marker": str,
         "pageSize": int,
         "ascendingOrder": bool,
     },
     total=False,
 )
 
+_RequiredListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef = TypedDict(
+    "_RequiredListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef",
+    {
+        "policyName": str,
+    },
+)
+_OptionalListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef = TypedDict(
+    "_OptionalListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef(
+    _RequiredListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef,
+    _OptionalListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPolicyPrincipalsRequestRequestTypeDef = TypedDict(
     "_RequiredListPolicyPrincipalsRequestRequestTypeDef",
     {
         "policyName": str,
     },
 )
 _OptionalListPolicyPrincipalsRequestRequestTypeDef = TypedDict(
@@ -3527,14 +4687,23 @@
 class ListPolicyPrincipalsRequestRequestTypeDef(
     _RequiredListPolicyPrincipalsRequestRequestTypeDef,
     _OptionalListPolicyPrincipalsRequestRequestTypeDef,
 ):
     pass
 
 
+ListPolicyPrincipalsResponseTypeDef = TypedDict(
+    "ListPolicyPrincipalsResponseTypeDef",
+    {
+        "principals": List[str],
+        "nextMarker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListPolicyVersionsRequestRequestTypeDef = TypedDict(
     "ListPolicyVersionsRequestRequestTypeDef",
     {
         "policyName": str,
     },
 )
 
@@ -3544,14 +4713,37 @@
         "versionId": str,
         "isDefaultVersion": bool,
         "createDate": datetime,
     },
     total=False,
 )
 
+_RequiredListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef",
+    {
+        "principal": str,
+    },
+)
+_OptionalListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef(
+    _RequiredListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef,
+    _OptionalListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPrincipalPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListPrincipalPoliciesRequestRequestTypeDef",
     {
         "principal": str,
     },
 )
 _OptionalListPrincipalPoliciesRequestRequestTypeDef = TypedDict(
@@ -3568,14 +4760,36 @@
 class ListPrincipalPoliciesRequestRequestTypeDef(
     _RequiredListPrincipalPoliciesRequestRequestTypeDef,
     _OptionalListPrincipalPoliciesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef = TypedDict(
+    "_RequiredListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef",
+    {
+        "principal": str,
+    },
+)
+_OptionalListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef = TypedDict(
+    "_OptionalListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef(
+    _RequiredListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef,
+    _OptionalListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPrincipalThingsRequestRequestTypeDef = TypedDict(
     "_RequiredListPrincipalThingsRequestRequestTypeDef",
     {
         "principal": str,
     },
 )
 _OptionalListPrincipalThingsRequestRequestTypeDef = TypedDict(
@@ -3591,14 +4805,45 @@
 class ListPrincipalThingsRequestRequestTypeDef(
     _RequiredListPrincipalThingsRequestRequestTypeDef,
     _OptionalListPrincipalThingsRequestRequestTypeDef,
 ):
     pass
 
 
+ListPrincipalThingsResponseTypeDef = TypedDict(
+    "ListPrincipalThingsResponseTypeDef",
+    {
+        "things": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef",
+    {
+        "templateName": str,
+    },
+)
+_OptionalListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef(
+    _RequiredListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef,
+    _OptionalListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListProvisioningTemplateVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListProvisioningTemplateVersionsRequestRequestTypeDef",
     {
         "templateName": str,
     },
 )
 _OptionalListProvisioningTemplateVersionsRequestRequestTypeDef = TypedDict(
@@ -3624,14 +4869,22 @@
         "versionId": int,
         "creationDate": datetime,
         "isDefaultVersion": bool,
     },
     total=False,
 )
 
+ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef = TypedDict(
+    "ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProvisioningTemplatesRequestRequestTypeDef = TypedDict(
     "ListProvisioningTemplatesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -3647,14 +4900,36 @@
         "lastModifiedDate": datetime,
         "enabled": bool,
         "type": TemplateTypeType,
     },
     total=False,
 )
 
+_RequiredListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef = TypedDict(
+    "_RequiredListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef",
+    {
+        "findingId": str,
+    },
+)
+_OptionalListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef = TypedDict(
+    "_OptionalListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef(
+    _RequiredListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef,
+    _OptionalListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRelatedResourcesForAuditFindingRequestRequestTypeDef = TypedDict(
     "_RequiredListRelatedResourcesForAuditFindingRequestRequestTypeDef",
     {
         "findingId": str,
     },
 )
 _OptionalListRelatedResourcesForAuditFindingRequestRequestTypeDef = TypedDict(
@@ -3670,24 +4945,50 @@
 class ListRelatedResourcesForAuditFindingRequestRequestTypeDef(
     _RequiredListRelatedResourcesForAuditFindingRequestRequestTypeDef,
     _OptionalListRelatedResourcesForAuditFindingRequestRequestTypeDef,
 ):
     pass
 
 
+ListRoleAliasesRequestListRoleAliasesPaginateTypeDef = TypedDict(
+    "ListRoleAliasesRequestListRoleAliasesPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRoleAliasesRequestRequestTypeDef = TypedDict(
     "ListRoleAliasesRequestRequestTypeDef",
     {
         "pageSize": int,
         "marker": str,
         "ascendingOrder": bool,
     },
     total=False,
 )
 
+ListRoleAliasesResponseTypeDef = TypedDict(
+    "ListRoleAliasesResponseTypeDef",
+    {
+        "roleAliases": List[str],
+        "nextMarker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef = TypedDict(
+    "ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListScheduledAuditsRequestRequestTypeDef = TypedDict(
     "ListScheduledAuditsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -3701,14 +5002,41 @@
         "frequency": AuditFrequencyType,
         "dayOfMonth": str,
         "dayOfWeek": DayOfWeekType,
     },
     total=False,
 )
 
+_RequiredListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef",
+        {
+            "securityProfileTargetArn": str,
+        },
+    )
+)
+_OptionalListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef",
+        {
+            "recursive": bool,
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+
+class ListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef(
+    _RequiredListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef,
+    _OptionalListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSecurityProfilesForTargetRequestRequestTypeDef = TypedDict(
     "_RequiredListSecurityProfilesForTargetRequestRequestTypeDef",
     {
         "securityProfileTargetArn": str,
     },
 )
 _OptionalListSecurityProfilesForTargetRequestRequestTypeDef = TypedDict(
@@ -3725,14 +5053,24 @@
 class ListSecurityProfilesForTargetRequestRequestTypeDef(
     _RequiredListSecurityProfilesForTargetRequestRequestTypeDef,
     _OptionalListSecurityProfilesForTargetRequestRequestTypeDef,
 ):
     pass
 
 
+ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef = TypedDict(
+    "ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef",
+    {
+        "dimensionName": str,
+        "metricName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSecurityProfilesRequestRequestTypeDef = TypedDict(
     "ListSecurityProfilesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "dimensionName": str,
         "metricName": str,
@@ -3744,14 +5082,23 @@
     "SecurityProfileIdentifierTypeDef",
     {
         "name": str,
         "arn": str,
     },
 )
 
+ListStreamsRequestListStreamsPaginateTypeDef = TypedDict(
+    "ListStreamsRequestListStreamsPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStreamsRequestRequestTypeDef = TypedDict(
     "ListStreamsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "ascendingOrder": bool,
     },
@@ -3765,14 +5112,36 @@
         "streamArn": str,
         "streamVersion": int,
         "description": str,
     },
     total=False,
 )
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -3787,14 +5156,36 @@
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
+    "_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
+    {
+        "policyName": str,
+    },
+)
+_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
+    "_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef(
+    _RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
+    _OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTargetsForPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredListTargetsForPolicyRequestRequestTypeDef",
     {
         "policyName": str,
     },
 )
 _OptionalListTargetsForPolicyRequestRequestTypeDef = TypedDict(
@@ -3810,14 +5201,49 @@
 class ListTargetsForPolicyRequestRequestTypeDef(
     _RequiredListTargetsForPolicyRequestRequestTypeDef,
     _OptionalListTargetsForPolicyRequestRequestTypeDef,
 ):
     pass
 
 
+ListTargetsForPolicyResponseTypeDef = TypedDict(
+    "ListTargetsForPolicyResponseTypeDef",
+    {
+        "targets": List[str],
+        "nextMarker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef = (
+    TypedDict(
+        "_RequiredListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef",
+        {
+            "securityProfileName": str,
+        },
+    )
+)
+_OptionalListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef = (
+    TypedDict(
+        "_OptionalListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef",
+        {
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+
+class ListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef(
+    _RequiredListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef,
+    _OptionalListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTargetsForSecurityProfileRequestRequestTypeDef = TypedDict(
     "_RequiredListTargetsForSecurityProfileRequestRequestTypeDef",
     {
         "securityProfileName": str,
     },
 )
 _OptionalListTargetsForSecurityProfileRequestRequestTypeDef = TypedDict(
@@ -3840,14 +5266,36 @@
 SecurityProfileTargetTypeDef = TypedDict(
     "SecurityProfileTargetTypeDef",
     {
         "arn": str,
     },
 )
 
+_RequiredListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef = TypedDict(
+    "_RequiredListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef",
+    {
+        "thingName": str,
+    },
+)
+_OptionalListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef = TypedDict(
+    "_OptionalListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef(
+    _RequiredListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef,
+    _OptionalListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListThingGroupsForThingRequestRequestTypeDef = TypedDict(
     "_RequiredListThingGroupsForThingRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 _OptionalListThingGroupsForThingRequestRequestTypeDef = TypedDict(
@@ -3863,26 +5311,59 @@
 class ListThingGroupsForThingRequestRequestTypeDef(
     _RequiredListThingGroupsForThingRequestRequestTypeDef,
     _OptionalListThingGroupsForThingRequestRequestTypeDef,
 ):
     pass
 
 
+ListThingGroupsRequestListThingGroupsPaginateTypeDef = TypedDict(
+    "ListThingGroupsRequestListThingGroupsPaginateTypeDef",
+    {
+        "parentGroup": str,
+        "namePrefixFilter": str,
+        "recursive": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListThingGroupsRequestRequestTypeDef = TypedDict(
     "ListThingGroupsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "parentGroup": str,
         "namePrefixFilter": str,
         "recursive": bool,
     },
     total=False,
 )
 
+_RequiredListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef = TypedDict(
+    "_RequiredListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef",
+    {
+        "thingName": str,
+    },
+)
+_OptionalListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef = TypedDict(
+    "_OptionalListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef(
+    _RequiredListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef,
+    _OptionalListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListThingPrincipalsRequestRequestTypeDef = TypedDict(
     "_RequiredListThingPrincipalsRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 _OptionalListThingPrincipalsRequestRequestTypeDef = TypedDict(
@@ -3898,14 +5379,46 @@
 class ListThingPrincipalsRequestRequestTypeDef(
     _RequiredListThingPrincipalsRequestRequestTypeDef,
     _OptionalListThingPrincipalsRequestRequestTypeDef,
 ):
     pass
 
 
+ListThingPrincipalsResponseTypeDef = TypedDict(
+    "ListThingPrincipalsResponseTypeDef",
+    {
+        "principals": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef = TypedDict(
+    "_RequiredListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef",
+    {
+        "taskId": str,
+        "reportType": ReportTypeType,
+    },
+)
+_OptionalListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef = TypedDict(
+    "_OptionalListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef(
+    _RequiredListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef,
+    _OptionalListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListThingRegistrationTaskReportsRequestRequestTypeDef = TypedDict(
     "_RequiredListThingRegistrationTaskReportsRequestRequestTypeDef",
     {
         "taskId": str,
         "reportType": ReportTypeType,
     },
 )
@@ -3922,34 +5435,93 @@
 class ListThingRegistrationTaskReportsRequestRequestTypeDef(
     _RequiredListThingRegistrationTaskReportsRequestRequestTypeDef,
     _OptionalListThingRegistrationTaskReportsRequestRequestTypeDef,
 ):
     pass
 
 
+ListThingRegistrationTaskReportsResponseTypeDef = TypedDict(
+    "ListThingRegistrationTaskReportsResponseTypeDef",
+    {
+        "resourceLinks": List[str],
+        "reportType": ReportTypeType,
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef = TypedDict(
+    "ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef",
+    {
+        "status": StatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListThingRegistrationTasksRequestRequestTypeDef = TypedDict(
     "ListThingRegistrationTasksRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "status": StatusType,
     },
     total=False,
 )
 
+ListThingRegistrationTasksResponseTypeDef = TypedDict(
+    "ListThingRegistrationTasksResponseTypeDef",
+    {
+        "taskIds": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListThingTypesRequestListThingTypesPaginateTypeDef = TypedDict(
+    "ListThingTypesRequestListThingTypesPaginateTypeDef",
+    {
+        "thingTypeName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListThingTypesRequestRequestTypeDef = TypedDict(
     "ListThingTypesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "thingTypeName": str,
     },
     total=False,
 )
 
+_RequiredListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef = TypedDict(
+    "_RequiredListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef",
+    {
+        "billingGroupName": str,
+    },
+)
+_OptionalListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef = TypedDict(
+    "_OptionalListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef(
+    _RequiredListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef,
+    _OptionalListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListThingsInBillingGroupRequestRequestTypeDef = TypedDict(
     "_RequiredListThingsInBillingGroupRequestRequestTypeDef",
     {
         "billingGroupName": str,
     },
 )
 _OptionalListThingsInBillingGroupRequestRequestTypeDef = TypedDict(
@@ -3965,14 +5537,46 @@
 class ListThingsInBillingGroupRequestRequestTypeDef(
     _RequiredListThingsInBillingGroupRequestRequestTypeDef,
     _OptionalListThingsInBillingGroupRequestRequestTypeDef,
 ):
     pass
 
 
+ListThingsInBillingGroupResponseTypeDef = TypedDict(
+    "ListThingsInBillingGroupResponseTypeDef",
+    {
+        "things": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef = TypedDict(
+    "_RequiredListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef",
+    {
+        "thingGroupName": str,
+    },
+)
+_OptionalListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef = TypedDict(
+    "_OptionalListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef",
+    {
+        "recursive": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef(
+    _RequiredListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef,
+    _OptionalListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListThingsInThingGroupRequestRequestTypeDef = TypedDict(
     "_RequiredListThingsInThingGroupRequestRequestTypeDef",
     {
         "thingGroupName": str,
     },
 )
 _OptionalListThingsInThingGroupRequestRequestTypeDef = TypedDict(
@@ -3989,14 +5593,35 @@
 class ListThingsInThingGroupRequestRequestTypeDef(
     _RequiredListThingsInThingGroupRequestRequestTypeDef,
     _OptionalListThingsInThingGroupRequestRequestTypeDef,
 ):
     pass
 
 
+ListThingsInThingGroupResponseTypeDef = TypedDict(
+    "ListThingsInThingGroupResponseTypeDef",
+    {
+        "things": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListThingsRequestListThingsPaginateTypeDef = TypedDict(
+    "ListThingsRequestListThingsPaginateTypeDef",
+    {
+        "attributeName": str,
+        "attributeValue": str,
+        "thingTypeName": str,
+        "usePrefixAttributeValue": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListThingsRequestRequestTypeDef = TypedDict(
     "ListThingsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "attributeName": str,
         "attributeValue": str,
@@ -4014,23 +5639,41 @@
         "thingArn": str,
         "attributes": Dict[str, str],
         "version": int,
     },
     total=False,
 )
 
+ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef = TypedDict(
+    "ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTopicRuleDestinationsRequestRequestTypeDef = TypedDict(
     "ListTopicRuleDestinationsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListTopicRulesRequestListTopicRulesPaginateTypeDef = TypedDict(
+    "ListTopicRulesRequestListTopicRulesPaginateTypeDef",
+    {
+        "topic": str,
+        "ruleDisabled": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTopicRulesRequestRequestTypeDef = TypedDict(
     "ListTopicRulesRequestRequestTypeDef",
     {
         "topic": str,
         "maxResults": int,
         "nextToken": str,
         "ruleDisabled": bool,
@@ -4046,24 +5689,61 @@
         "topicPattern": str,
         "createdAt": datetime,
         "ruleDisabled": bool,
     },
     total=False,
 )
 
+ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef = TypedDict(
+    "ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef",
+    {
+        "targetType": LogTargetTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListV2LoggingLevelsRequestRequestTypeDef = TypedDict(
     "ListV2LoggingLevelsRequestRequestTypeDef",
     {
         "targetType": LogTargetTypeType,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListViolationEventsRequestListViolationEventsPaginateTypeDef = TypedDict(
+    "_RequiredListViolationEventsRequestListViolationEventsPaginateTypeDef",
+    {
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+    },
+)
+_OptionalListViolationEventsRequestListViolationEventsPaginateTypeDef = TypedDict(
+    "_OptionalListViolationEventsRequestListViolationEventsPaginateTypeDef",
+    {
+        "thingName": str,
+        "securityProfileName": str,
+        "behaviorCriteriaType": BehaviorCriteriaTypeType,
+        "listSuppressedAlerts": bool,
+        "verificationState": VerificationStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListViolationEventsRequestListViolationEventsPaginateTypeDef(
+    _RequiredListViolationEventsRequestListViolationEventsPaginateTypeDef,
+    _OptionalListViolationEventsRequestListViolationEventsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListViolationEventsRequestRequestTypeDef = TypedDict(
     "_RequiredListViolationEventsRequestRequestTypeDef",
     {
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
     },
 )
@@ -4192,14 +5872,24 @@
     "UserPropertyTypeDef",
     {
         "key": str,
         "value": str,
     },
 )
 
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
+    {
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
+    },
+    total=False,
+)
+
 PolicyVersionIdentifierTypeDef = TypedDict(
     "PolicyVersionIdentifierTypeDef",
     {
         "policyName": str,
         "policyVersionId": str,
     },
     total=False,
@@ -4224,14 +5914,23 @@
 class PutVerificationStateOnViolationRequestRequestTypeDef(
     _RequiredPutVerificationStateOnViolationRequestRequestTypeDef,
     _OptionalPutVerificationStateOnViolationRequestRequestTypeDef,
 ):
     pass
 
 
+RegisterCACertificateResponseTypeDef = TypedDict(
+    "RegisterCACertificateResponseTypeDef",
+    {
+        "certificateArn": str,
+        "certificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRegisterCertificateRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterCertificateRequestRequestTypeDef",
     {
         "certificatePem": str,
     },
 )
 _OptionalRegisterCertificateRequestRequestTypeDef = TypedDict(
@@ -4248,14 +5947,23 @@
 class RegisterCertificateRequestRequestTypeDef(
     _RequiredRegisterCertificateRequestRequestTypeDef,
     _OptionalRegisterCertificateRequestRequestTypeDef,
 ):
     pass
 
 
+RegisterCertificateResponseTypeDef = TypedDict(
+    "RegisterCertificateResponseTypeDef",
+    {
+        "certificateArn": str,
+        "certificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRegisterCertificateWithoutCARequestRequestTypeDef = TypedDict(
     "_RequiredRegisterCertificateWithoutCARequestRequestTypeDef",
     {
         "certificatePem": str,
     },
 )
 _OptionalRegisterCertificateWithoutCARequestRequestTypeDef = TypedDict(
@@ -4270,14 +5978,23 @@
 class RegisterCertificateWithoutCARequestRequestTypeDef(
     _RequiredRegisterCertificateWithoutCARequestRequestTypeDef,
     _OptionalRegisterCertificateWithoutCARequestRequestTypeDef,
 ):
     pass
 
 
+RegisterCertificateWithoutCAResponseTypeDef = TypedDict(
+    "RegisterCertificateWithoutCAResponseTypeDef",
+    {
+        "certificateArn": str,
+        "certificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRegisterThingRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterThingRequestRequestTypeDef",
     {
         "templateBody": str,
     },
 )
 _OptionalRegisterThingRequestRequestTypeDef = TypedDict(
@@ -4291,14 +6008,23 @@
 
 class RegisterThingRequestRequestTypeDef(
     _RequiredRegisterThingRequestRequestTypeDef, _OptionalRegisterThingRequestRequestTypeDef
 ):
     pass
 
 
+RegisterThingResponseTypeDef = TypedDict(
+    "RegisterThingResponseTypeDef",
+    {
+        "certificatePem": str,
+        "resourceArns": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRejectCertificateTransferRequestRequestTypeDef = TypedDict(
     "_RequiredRejectCertificateTransferRequestRequestTypeDef",
     {
         "certificateId": str,
     },
 )
 _OptionalRejectCertificateTransferRequestRequestTypeDef = TypedDict(
@@ -4335,14 +6061,25 @@
         "thingGroupArn": str,
         "thingName": str,
         "thingArn": str,
     },
     total=False,
 )
 
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
+    {
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
+    },
+)
+
 _RequiredSearchIndexRequestRequestTypeDef = TypedDict(
     "_RequiredSearchIndexRequestRequestTypeDef",
     {
         "queryString": str,
     },
 )
 _OptionalSearchIndexRequestRequestTypeDef = TypedDict(
@@ -4378,14 +6115,23 @@
 SetDefaultAuthorizerRequestRequestTypeDef = TypedDict(
     "SetDefaultAuthorizerRequestRequestTypeDef",
     {
         "authorizerName": str,
     },
 )
 
+SetDefaultAuthorizerResponseTypeDef = TypedDict(
+    "SetDefaultAuthorizerResponseTypeDef",
+    {
+        "authorizerName": str,
+        "authorizerArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SetDefaultPolicyVersionRequestRequestTypeDef = TypedDict(
     "SetDefaultPolicyVersionRequestRequestTypeDef",
     {
         "policyName": str,
         "policyVersionId": str,
     },
 )
@@ -4406,31 +6152,63 @@
         "certificateArn": str,
         "platform": str,
         "certificatePathOnDevice": str,
     },
     total=False,
 )
 
+StartAuditMitigationActionsTaskResponseTypeDef = TypedDict(
+    "StartAuditMitigationActionsTaskResponseTypeDef",
+    {
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartDetectMitigationActionsTaskResponseTypeDef = TypedDict(
+    "StartDetectMitigationActionsTaskResponseTypeDef",
+    {
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartOnDemandAuditTaskRequestRequestTypeDef = TypedDict(
     "StartOnDemandAuditTaskRequestRequestTypeDef",
     {
         "targetCheckNames": Sequence[str],
     },
 )
 
+StartOnDemandAuditTaskResponseTypeDef = TypedDict(
+    "StartOnDemandAuditTaskResponseTypeDef",
+    {
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartThingRegistrationTaskRequestRequestTypeDef = TypedDict(
     "StartThingRegistrationTaskRequestRequestTypeDef",
     {
         "templateBody": str,
         "inputFileBucket": str,
         "inputFileKey": str,
         "roleArn": str,
     },
 )
 
+StartThingRegistrationTaskResponseTypeDef = TypedDict(
+    "StartThingRegistrationTaskResponseTypeDef",
+    {
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopThingRegistrationTaskRequestRequestTypeDef = TypedDict(
     "StopThingRegistrationTaskRequestRequestTypeDef",
     {
         "taskId": str,
     },
 )
 
@@ -4438,14 +6216,26 @@
     "TlsContextTypeDef",
     {
         "serverName": str,
     },
     total=False,
 )
 
+TestInvokeAuthorizerResponseTypeDef = TypedDict(
+    "TestInvokeAuthorizerResponseTypeDef",
+    {
+        "isAuthenticated": bool,
+        "principalId": str,
+        "policyDocuments": List[str],
+        "refreshAfterInSeconds": int,
+        "disconnectAfterInSeconds": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ThingConnectivityTypeDef = TypedDict(
     "ThingConnectivityTypeDef",
     {
         "connected": bool,
         "timestamp": int,
         "disconnectReason": str,
     },
@@ -4532,14 +6322,22 @@
 class TransferCertificateRequestRequestTypeDef(
     _RequiredTransferCertificateRequestRequestTypeDef,
     _OptionalTransferCertificateRequestRequestTypeDef,
 ):
     pass
 
 
+TransferCertificateResponseTypeDef = TypedDict(
+    "TransferCertificateResponseTypeDef",
+    {
+        "transferredCertificateArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -4565,483 +6363,281 @@
 
 class UpdateAuthorizerRequestRequestTypeDef(
     _RequiredUpdateAuthorizerRequestRequestTypeDef, _OptionalUpdateAuthorizerRequestRequestTypeDef
 ):
     pass
 
 
-UpdateCertificateRequestRequestTypeDef = TypedDict(
-    "UpdateCertificateRequestRequestTypeDef",
+UpdateAuthorizerResponseTypeDef = TypedDict(
+    "UpdateAuthorizerResponseTypeDef",
     {
-        "certificateId": str,
-        "newStatus": CertificateStatusType,
+        "authorizerName": str,
+        "authorizerArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateCustomMetricRequestRequestTypeDef = TypedDict(
-    "UpdateCustomMetricRequestRequestTypeDef",
+UpdateBillingGroupResponseTypeDef = TypedDict(
+    "UpdateBillingGroupResponseTypeDef",
     {
-        "metricName": str,
-        "displayName": str,
+        "version": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateDimensionRequestRequestTypeDef = TypedDict(
-    "UpdateDimensionRequestRequestTypeDef",
+UpdateCertificateRequestRequestTypeDef = TypedDict(
+    "UpdateCertificateRequestRequestTypeDef",
     {
-        "name": str,
-        "stringValues": Sequence[str],
+        "certificateId": str,
+        "newStatus": CertificateStatusType,
     },
 )
 
-_RequiredUpdateRoleAliasRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateRoleAliasRequestRequestTypeDef",
-    {
-        "roleAlias": str,
-    },
-)
-_OptionalUpdateRoleAliasRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateRoleAliasRequestRequestTypeDef",
+UpdateCustomMetricRequestRequestTypeDef = TypedDict(
+    "UpdateCustomMetricRequestRequestTypeDef",
     {
-        "roleArn": str,
-        "credentialDurationSeconds": int,
+        "metricName": str,
+        "displayName": str,
     },
-    total=False,
 )
 
-
-class UpdateRoleAliasRequestRequestTypeDef(
-    _RequiredUpdateRoleAliasRequestRequestTypeDef, _OptionalUpdateRoleAliasRequestRequestTypeDef
-):
-    pass
-
-
-_RequiredUpdateScheduledAuditRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateScheduledAuditRequestRequestTypeDef",
-    {
-        "scheduledAuditName": str,
-    },
-)
-_OptionalUpdateScheduledAuditRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateScheduledAuditRequestRequestTypeDef",
+UpdateCustomMetricResponseTypeDef = TypedDict(
+    "UpdateCustomMetricResponseTypeDef",
     {
-        "frequency": AuditFrequencyType,
-        "dayOfMonth": str,
-        "dayOfWeek": DayOfWeekType,
-        "targetCheckNames": Sequence[str],
+        "metricName": str,
+        "metricArn": str,
+        "metricType": CustomMetricTypeType,
+        "displayName": str,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class UpdateScheduledAuditRequestRequestTypeDef(
-    _RequiredUpdateScheduledAuditRequestRequestTypeDef,
-    _OptionalUpdateScheduledAuditRequestRequestTypeDef,
-):
-    pass
-
-
-UpdateThingGroupsForThingRequestRequestTypeDef = TypedDict(
-    "UpdateThingGroupsForThingRequestRequestTypeDef",
+UpdateDimensionRequestRequestTypeDef = TypedDict(
+    "UpdateDimensionRequestRequestTypeDef",
     {
-        "thingName": str,
-        "thingGroupsToAdd": Sequence[str],
-        "thingGroupsToRemove": Sequence[str],
-        "overrideDynamicGroups": bool,
+        "name": str,
+        "stringValues": Sequence[str],
     },
-    total=False,
 )
 
-UpdateTopicRuleDestinationRequestRequestTypeDef = TypedDict(
-    "UpdateTopicRuleDestinationRequestRequestTypeDef",
+UpdateDimensionResponseTypeDef = TypedDict(
+    "UpdateDimensionResponseTypeDef",
     {
+        "name": str,
         "arn": str,
-        "status": TopicRuleDestinationStatusType,
+        "type": Literal["TOPIC_FILTER"],
+        "stringValues": List[str],
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ValidationErrorTypeDef = TypedDict(
-    "ValidationErrorTypeDef",
+UpdateDomainConfigurationResponseTypeDef = TypedDict(
+    "UpdateDomainConfigurationResponseTypeDef",
     {
-        "errorMessage": str,
+        "domainConfigurationName": str,
+        "domainConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-AbortConfigTypeDef = TypedDict(
-    "AbortConfigTypeDef",
+UpdateDynamicThingGroupResponseTypeDef = TypedDict(
+    "UpdateDynamicThingGroupResponseTypeDef",
     {
-        "criteriaList": Sequence[AbortCriteriaTypeDef],
+        "version": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-MetricDatumTypeDef = TypedDict(
-    "MetricDatumTypeDef",
+UpdateMitigationActionResponseTypeDef = TypedDict(
+    "UpdateMitigationActionResponseTypeDef",
     {
-        "timestamp": datetime,
-        "value": MetricValueTypeDef,
+        "actionArn": str,
+        "actionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredUpdateFleetMetricRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateFleetMetricRequestRequestTypeDef",
+_RequiredUpdatePackageRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdatePackageRequestRequestTypeDef",
     {
-        "metricName": str,
-        "indexName": str,
+        "packageName": str,
     },
 )
-_OptionalUpdateFleetMetricRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateFleetMetricRequestRequestTypeDef",
+_OptionalUpdatePackageRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdatePackageRequestRequestTypeDef",
     {
-        "queryString": str,
-        "aggregationType": AggregationTypeTypeDef,
-        "period": int,
-        "aggregationField": str,
         "description": str,
-        "queryVersion": str,
-        "unit": FleetMetricUnitType,
-        "expectedVersion": int,
+        "defaultVersionName": str,
+        "unsetDefaultVersion": bool,
+        "clientToken": str,
     },
     total=False,
 )
 
 
-class UpdateFleetMetricRequestRequestTypeDef(
-    _RequiredUpdateFleetMetricRequestRequestTypeDef, _OptionalUpdateFleetMetricRequestRequestTypeDef
+class UpdatePackageRequestRequestTypeDef(
+    _RequiredUpdatePackageRequestRequestTypeDef, _OptionalUpdatePackageRequestRequestTypeDef
 ):
     pass
 
 
-AllowedTypeDef = TypedDict(
-    "AllowedTypeDef",
-    {
-        "policies": List[PolicyTypeDef],
-    },
-    total=False,
-)
-
-ExplicitDenyTypeDef = TypedDict(
-    "ExplicitDenyTypeDef",
-    {
-        "policies": List[PolicyTypeDef],
-    },
-    total=False,
-)
-
-ImplicitDenyTypeDef = TypedDict(
-    "ImplicitDenyTypeDef",
-    {
-        "policies": List[PolicyTypeDef],
-    },
-    total=False,
-)
-
-_RequiredAssetPropertyValueTypeDef = TypedDict(
-    "_RequiredAssetPropertyValueTypeDef",
+_RequiredUpdatePackageVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdatePackageVersionRequestRequestTypeDef",
     {
-        "value": AssetPropertyVariantTypeDef,
-        "timestamp": AssetPropertyTimestampTypeDef,
+        "packageName": str,
+        "versionName": str,
     },
 )
-_OptionalAssetPropertyValueTypeDef = TypedDict(
-    "_OptionalAssetPropertyValueTypeDef",
+_OptionalUpdatePackageVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdatePackageVersionRequestRequestTypeDef",
     {
-        "quality": str,
+        "description": str,
+        "attributes": Mapping[str, str],
+        "action": PackageVersionActionType,
+        "clientToken": str,
     },
     total=False,
 )
 
 
-class AssetPropertyValueTypeDef(
-    _RequiredAssetPropertyValueTypeDef, _OptionalAssetPropertyValueTypeDef
+class UpdatePackageVersionRequestRequestTypeDef(
+    _RequiredUpdatePackageVersionRequestRequestTypeDef,
+    _OptionalUpdatePackageVersionRequestRequestTypeDef,
 ):
     pass
 
 
-AssociateTargetsWithJobResponseTypeDef = TypedDict(
-    "AssociateTargetsWithJobResponseTypeDef",
-    {
-        "jobArn": str,
-        "jobId": str,
-        "description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelJobResponseTypeDef = TypedDict(
-    "CancelJobResponseTypeDef",
-    {
-        "jobArn": str,
-        "jobId": str,
-        "description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAuthorizerResponseTypeDef = TypedDict(
-    "CreateAuthorizerResponseTypeDef",
-    {
-        "authorizerName": str,
-        "authorizerArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBillingGroupResponseTypeDef = TypedDict(
-    "CreateBillingGroupResponseTypeDef",
-    {
-        "billingGroupName": str,
-        "billingGroupArn": str,
-        "billingGroupId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCertificateFromCsrResponseTypeDef = TypedDict(
-    "CreateCertificateFromCsrResponseTypeDef",
-    {
-        "certificateArn": str,
-        "certificateId": str,
-        "certificatePem": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCustomMetricResponseTypeDef = TypedDict(
-    "CreateCustomMetricResponseTypeDef",
-    {
-        "metricName": str,
-        "metricArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDimensionResponseTypeDef = TypedDict(
-    "CreateDimensionResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDomainConfigurationResponseTypeDef = TypedDict(
-    "CreateDomainConfigurationResponseTypeDef",
+_RequiredUpdateRoleAliasRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateRoleAliasRequestRequestTypeDef",
     {
-        "domainConfigurationName": str,
-        "domainConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "roleAlias": str,
     },
 )
-
-CreateDynamicThingGroupResponseTypeDef = TypedDict(
-    "CreateDynamicThingGroupResponseTypeDef",
+_OptionalUpdateRoleAliasRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateRoleAliasRequestRequestTypeDef",
     {
-        "thingGroupName": str,
-        "thingGroupArn": str,
-        "thingGroupId": str,
-        "indexName": str,
-        "queryString": str,
-        "queryVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "roleArn": str,
+        "credentialDurationSeconds": int,
     },
+    total=False,
 )
 
-CreateFleetMetricResponseTypeDef = TypedDict(
-    "CreateFleetMetricResponseTypeDef",
-    {
-        "metricName": str,
-        "metricArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-CreateJobResponseTypeDef = TypedDict(
-    "CreateJobResponseTypeDef",
-    {
-        "jobArn": str,
-        "jobId": str,
-        "description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateRoleAliasRequestRequestTypeDef(
+    _RequiredUpdateRoleAliasRequestRequestTypeDef, _OptionalUpdateRoleAliasRequestRequestTypeDef
+):
+    pass
 
-CreateJobTemplateResponseTypeDef = TypedDict(
-    "CreateJobTemplateResponseTypeDef",
-    {
-        "jobTemplateArn": str,
-        "jobTemplateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-CreateMitigationActionResponseTypeDef = TypedDict(
-    "CreateMitigationActionResponseTypeDef",
-    {
-        "actionArn": str,
-        "actionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateOTAUpdateResponseTypeDef = TypedDict(
-    "CreateOTAUpdateResponseTypeDef",
+UpdateRoleAliasResponseTypeDef = TypedDict(
+    "UpdateRoleAliasResponseTypeDef",
     {
-        "otaUpdateId": str,
-        "awsIotJobId": str,
-        "otaUpdateArn": str,
-        "awsIotJobArn": str,
-        "otaUpdateStatus": OTAUpdateStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "roleAlias": str,
+        "roleAliasArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreatePolicyResponseTypeDef = TypedDict(
-    "CreatePolicyResponseTypeDef",
+_RequiredUpdateScheduledAuditRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateScheduledAuditRequestRequestTypeDef",
     {
-        "policyName": str,
-        "policyArn": str,
-        "policyDocument": str,
-        "policyVersionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "scheduledAuditName": str,
     },
 )
-
-CreatePolicyVersionResponseTypeDef = TypedDict(
-    "CreatePolicyVersionResponseTypeDef",
+_OptionalUpdateScheduledAuditRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateScheduledAuditRequestRequestTypeDef",
     {
-        "policyArn": str,
-        "policyDocument": str,
-        "policyVersionId": str,
-        "isDefaultVersion": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "frequency": AuditFrequencyType,
+        "dayOfMonth": str,
+        "dayOfWeek": DayOfWeekType,
+        "targetCheckNames": Sequence[str],
     },
+    total=False,
 )
 
-CreateProvisioningTemplateResponseTypeDef = TypedDict(
-    "CreateProvisioningTemplateResponseTypeDef",
-    {
-        "templateArn": str,
-        "templateName": str,
-        "defaultVersionId": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-CreateProvisioningTemplateVersionResponseTypeDef = TypedDict(
-    "CreateProvisioningTemplateVersionResponseTypeDef",
-    {
-        "templateArn": str,
-        "templateName": str,
-        "versionId": int,
-        "isDefaultVersion": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateScheduledAuditRequestRequestTypeDef(
+    _RequiredUpdateScheduledAuditRequestRequestTypeDef,
+    _OptionalUpdateScheduledAuditRequestRequestTypeDef,
+):
+    pass
 
-CreateRoleAliasResponseTypeDef = TypedDict(
-    "CreateRoleAliasResponseTypeDef",
-    {
-        "roleAlias": str,
-        "roleAliasArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-CreateScheduledAuditResponseTypeDef = TypedDict(
-    "CreateScheduledAuditResponseTypeDef",
+UpdateScheduledAuditResponseTypeDef = TypedDict(
+    "UpdateScheduledAuditResponseTypeDef",
     {
         "scheduledAuditArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateSecurityProfileResponseTypeDef = TypedDict(
-    "CreateSecurityProfileResponseTypeDef",
-    {
-        "securityProfileName": str,
-        "securityProfileArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStreamResponseTypeDef = TypedDict(
-    "CreateStreamResponseTypeDef",
+UpdateStreamResponseTypeDef = TypedDict(
+    "UpdateStreamResponseTypeDef",
     {
         "streamId": str,
         "streamArn": str,
         "description": str,
         "streamVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateThingGroupResponseTypeDef = TypedDict(
-    "CreateThingGroupResponseTypeDef",
+UpdateThingGroupResponseTypeDef = TypedDict(
+    "UpdateThingGroupResponseTypeDef",
     {
-        "thingGroupName": str,
-        "thingGroupArn": str,
-        "thingGroupId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "version": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateThingResponseTypeDef = TypedDict(
-    "CreateThingResponseTypeDef",
+UpdateThingGroupsForThingRequestRequestTypeDef = TypedDict(
+    "UpdateThingGroupsForThingRequestRequestTypeDef",
     {
         "thingName": str,
-        "thingArn": str,
-        "thingId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "thingGroupsToAdd": Sequence[str],
+        "thingGroupsToRemove": Sequence[str],
+        "overrideDynamicGroups": bool,
     },
+    total=False,
 )
 
-CreateThingTypeResponseTypeDef = TypedDict(
-    "CreateThingTypeResponseTypeDef",
+UpdateTopicRuleDestinationRequestRequestTypeDef = TypedDict(
+    "UpdateTopicRuleDestinationRequestRequestTypeDef",
     {
-        "thingTypeName": str,
-        "thingTypeArn": str,
-        "thingTypeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "arn": str,
+        "status": TopicRuleDestinationStatusType,
     },
 )
 
-DescribeCustomMetricResponseTypeDef = TypedDict(
-    "DescribeCustomMetricResponseTypeDef",
+ValidationErrorTypeDef = TypedDict(
+    "ValidationErrorTypeDef",
     {
-        "metricName": str,
-        "metricArn": str,
-        "metricType": CustomMetricTypeType,
-        "displayName": str,
-        "creationDate": datetime,
-        "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "errorMessage": str,
     },
+    total=False,
 )
 
-DescribeDimensionResponseTypeDef = TypedDict(
-    "DescribeDimensionResponseTypeDef",
+AbortConfigTypeDef = TypedDict(
+    "AbortConfigTypeDef",
     {
-        "name": str,
-        "arn": str,
-        "type": Literal["TOPIC_FILTER"],
-        "stringValues": List[str],
-        "creationDate": datetime,
-        "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "criteriaList": Sequence[AbortCriteriaTypeDef],
     },
 )
 
-DescribeEndpointResponseTypeDef = TypedDict(
-    "DescribeEndpointResponseTypeDef",
+MetricDatumTypeDef = TypedDict(
+    "MetricDatumTypeDef",
     {
-        "endpointAddress": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "timestamp": datetime,
+        "value": MetricValueTypeDef,
     },
+    total=False,
 )
 
 DescribeFleetMetricResponseTypeDef = TypedDict(
     "DescribeFleetMetricResponseTypeDef",
     {
         "metricName": str,
         "queryString": str,
@@ -5052,502 +6648,119 @@
         "queryVersion": str,
         "indexName": str,
         "creationDate": datetime,
         "lastModifiedDate": datetime,
         "unit": FleetMetricUnitType,
         "version": int,
         "metricArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeIndexResponseTypeDef = TypedDict(
-    "DescribeIndexResponseTypeDef",
+_RequiredUpdateFleetMetricRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateFleetMetricRequestRequestTypeDef",
     {
+        "metricName": str,
         "indexName": str,
-        "indexStatus": IndexStatusType,
-        "schema": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeProvisioningTemplateVersionResponseTypeDef = TypedDict(
-    "DescribeProvisioningTemplateVersionResponseTypeDef",
-    {
-        "versionId": int,
-        "creationDate": datetime,
-        "templateBody": str,
-        "isDefaultVersion": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeScheduledAuditResponseTypeDef = TypedDict(
-    "DescribeScheduledAuditResponseTypeDef",
-    {
-        "frequency": AuditFrequencyType,
-        "dayOfMonth": str,
-        "dayOfWeek": DayOfWeekType,
-        "targetCheckNames": List[str],
-        "scheduledAuditName": str,
-        "scheduledAuditArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeThingRegistrationTaskResponseTypeDef = TypedDict(
-    "DescribeThingRegistrationTaskResponseTypeDef",
-    {
-        "taskId": str,
-        "creationDate": datetime,
-        "lastModifiedDate": datetime,
-        "templateBody": str,
-        "inputFileBucket": str,
-        "inputFileKey": str,
-        "roleArn": str,
-        "status": StatusType,
-        "message": str,
-        "successCount": int,
-        "failureCount": int,
-        "percentageProgress": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeThingResponseTypeDef = TypedDict(
-    "DescribeThingResponseTypeDef",
-    {
-        "defaultClientId": str,
-        "thingName": str,
-        "thingId": str,
-        "thingArn": str,
-        "thingTypeName": str,
-        "attributes": Dict[str, str],
-        "version": int,
-        "billingGroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-GetCardinalityResponseTypeDef = TypedDict(
-    "GetCardinalityResponseTypeDef",
+_OptionalUpdateFleetMetricRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateFleetMetricRequestRequestTypeDef",
     {
-        "cardinality": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "queryString": str,
+        "aggregationType": AggregationTypeTypeDef,
+        "period": int,
+        "aggregationField": str,
+        "description": str,
+        "queryVersion": str,
+        "unit": FleetMetricUnitType,
+        "expectedVersion": int,
     },
+    total=False,
 )
 
-GetJobDocumentResponseTypeDef = TypedDict(
-    "GetJobDocumentResponseTypeDef",
-    {
-        "document": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-GetLoggingOptionsResponseTypeDef = TypedDict(
-    "GetLoggingOptionsResponseTypeDef",
-    {
-        "roleArn": str,
-        "logLevel": LogLevelType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateFleetMetricRequestRequestTypeDef(
+    _RequiredUpdateFleetMetricRequestRequestTypeDef, _OptionalUpdateFleetMetricRequestRequestTypeDef
+):
+    pass
 
-GetPolicyResponseTypeDef = TypedDict(
-    "GetPolicyResponseTypeDef",
-    {
-        "policyName": str,
-        "policyArn": str,
-        "policyDocument": str,
-        "defaultVersionId": str,
-        "creationDate": datetime,
-        "lastModifiedDate": datetime,
-        "generationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-GetPolicyVersionResponseTypeDef = TypedDict(
-    "GetPolicyVersionResponseTypeDef",
+AllowedTypeDef = TypedDict(
+    "AllowedTypeDef",
     {
-        "policyArn": str,
-        "policyName": str,
-        "policyDocument": str,
-        "policyVersionId": str,
-        "isDefaultVersion": bool,
-        "creationDate": datetime,
-        "lastModifiedDate": datetime,
-        "generationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "policies": List[PolicyTypeDef],
     },
+    total=False,
 )
 
-GetRegistrationCodeResponseTypeDef = TypedDict(
-    "GetRegistrationCodeResponseTypeDef",
+ExplicitDenyTypeDef = TypedDict(
+    "ExplicitDenyTypeDef",
     {
-        "registrationCode": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "policies": List[PolicyTypeDef],
     },
+    total=False,
 )
 
-GetV2LoggingOptionsResponseTypeDef = TypedDict(
-    "GetV2LoggingOptionsResponseTypeDef",
+ImplicitDenyTypeDef = TypedDict(
+    "ImplicitDenyTypeDef",
     {
-        "roleArn": str,
-        "defaultLogLevel": LogLevelType,
-        "disableAllLogs": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "policies": List[PolicyTypeDef],
     },
+    total=False,
 )
 
 ListAttachedPoliciesResponseTypeDef = TypedDict(
     "ListAttachedPoliciesResponseTypeDef",
     {
         "policies": List[PolicyTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListCustomMetricsResponseTypeDef = TypedDict(
-    "ListCustomMetricsResponseTypeDef",
-    {
-        "metricNames": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDimensionsResponseTypeDef = TypedDict(
-    "ListDimensionsResponseTypeDef",
-    {
-        "dimensionNames": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListIndicesResponseTypeDef = TypedDict(
-    "ListIndicesResponseTypeDef",
-    {
-        "indexNames": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPoliciesResponseTypeDef = TypedDict(
     "ListPoliciesResponseTypeDef",
     {
         "policies": List[PolicyTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListPolicyPrincipalsResponseTypeDef = TypedDict(
-    "ListPolicyPrincipalsResponseTypeDef",
-    {
-        "principals": List[str],
-        "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPrincipalPoliciesResponseTypeDef = TypedDict(
     "ListPrincipalPoliciesResponseTypeDef",
     {
         "policies": List[PolicyTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListPrincipalThingsResponseTypeDef = TypedDict(
-    "ListPrincipalThingsResponseTypeDef",
-    {
-        "things": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListRoleAliasesResponseTypeDef = TypedDict(
-    "ListRoleAliasesResponseTypeDef",
-    {
-        "roleAliases": List[str],
-        "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTargetsForPolicyResponseTypeDef = TypedDict(
-    "ListTargetsForPolicyResponseTypeDef",
-    {
-        "targets": List[str],
-        "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListThingPrincipalsResponseTypeDef = TypedDict(
-    "ListThingPrincipalsResponseTypeDef",
-    {
-        "principals": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListThingRegistrationTaskReportsResponseTypeDef = TypedDict(
-    "ListThingRegistrationTaskReportsResponseTypeDef",
-    {
-        "resourceLinks": List[str],
-        "reportType": ReportTypeType,
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListThingRegistrationTasksResponseTypeDef = TypedDict(
-    "ListThingRegistrationTasksResponseTypeDef",
-    {
-        "taskIds": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListThingsInBillingGroupResponseTypeDef = TypedDict(
-    "ListThingsInBillingGroupResponseTypeDef",
-    {
-        "things": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListThingsInThingGroupResponseTypeDef = TypedDict(
-    "ListThingsInThingGroupResponseTypeDef",
-    {
-        "things": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterCACertificateResponseTypeDef = TypedDict(
-    "RegisterCACertificateResponseTypeDef",
-    {
-        "certificateArn": str,
-        "certificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterCertificateResponseTypeDef = TypedDict(
-    "RegisterCertificateResponseTypeDef",
-    {
-        "certificateArn": str,
-        "certificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterCertificateWithoutCAResponseTypeDef = TypedDict(
-    "RegisterCertificateWithoutCAResponseTypeDef",
-    {
-        "certificateArn": str,
-        "certificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterThingResponseTypeDef = TypedDict(
-    "RegisterThingResponseTypeDef",
-    {
-        "certificatePem": str,
-        "resourceArns": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SetDefaultAuthorizerResponseTypeDef = TypedDict(
-    "SetDefaultAuthorizerResponseTypeDef",
-    {
-        "authorizerName": str,
-        "authorizerArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartAuditMitigationActionsTaskResponseTypeDef = TypedDict(
-    "StartAuditMitigationActionsTaskResponseTypeDef",
-    {
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDetectMitigationActionsTaskResponseTypeDef = TypedDict(
-    "StartDetectMitigationActionsTaskResponseTypeDef",
-    {
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartOnDemandAuditTaskResponseTypeDef = TypedDict(
-    "StartOnDemandAuditTaskResponseTypeDef",
-    {
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartThingRegistrationTaskResponseTypeDef = TypedDict(
-    "StartThingRegistrationTaskResponseTypeDef",
-    {
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestInvokeAuthorizerResponseTypeDef = TypedDict(
-    "TestInvokeAuthorizerResponseTypeDef",
-    {
-        "isAuthenticated": bool,
-        "principalId": str,
-        "policyDocuments": List[str],
-        "refreshAfterInSeconds": int,
-        "disconnectAfterInSeconds": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TransferCertificateResponseTypeDef = TypedDict(
-    "TransferCertificateResponseTypeDef",
-    {
-        "transferredCertificateArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateAuthorizerResponseTypeDef = TypedDict(
-    "UpdateAuthorizerResponseTypeDef",
-    {
-        "authorizerName": str,
-        "authorizerArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateBillingGroupResponseTypeDef = TypedDict(
-    "UpdateBillingGroupResponseTypeDef",
-    {
-        "version": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateCustomMetricResponseTypeDef = TypedDict(
-    "UpdateCustomMetricResponseTypeDef",
-    {
-        "metricName": str,
-        "metricArn": str,
-        "metricType": CustomMetricTypeType,
-        "displayName": str,
-        "creationDate": datetime,
-        "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDimensionResponseTypeDef = TypedDict(
-    "UpdateDimensionResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "type": Literal["TOPIC_FILTER"],
-        "stringValues": List[str],
-        "creationDate": datetime,
-        "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDomainConfigurationResponseTypeDef = TypedDict(
-    "UpdateDomainConfigurationResponseTypeDef",
+_RequiredAssetPropertyValueTypeDef = TypedDict(
+    "_RequiredAssetPropertyValueTypeDef",
     {
-        "domainConfigurationName": str,
-        "domainConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "value": AssetPropertyVariantTypeDef,
+        "timestamp": AssetPropertyTimestampTypeDef,
     },
 )
-
-UpdateDynamicThingGroupResponseTypeDef = TypedDict(
-    "UpdateDynamicThingGroupResponseTypeDef",
+_OptionalAssetPropertyValueTypeDef = TypedDict(
+    "_OptionalAssetPropertyValueTypeDef",
     {
-        "version": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "quality": str,
     },
+    total=False,
 )
 
-UpdateMitigationActionResponseTypeDef = TypedDict(
-    "UpdateMitigationActionResponseTypeDef",
-    {
-        "actionArn": str,
-        "actionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-UpdateRoleAliasResponseTypeDef = TypedDict(
-    "UpdateRoleAliasResponseTypeDef",
-    {
-        "roleAlias": str,
-        "roleAliasArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class AssetPropertyValueTypeDef(
+    _RequiredAssetPropertyValueTypeDef, _OptionalAssetPropertyValueTypeDef
+):
+    pass
 
-UpdateScheduledAuditResponseTypeDef = TypedDict(
-    "UpdateScheduledAuditResponseTypeDef",
-    {
-        "scheduledAuditArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateStreamResponseTypeDef = TypedDict(
-    "UpdateStreamResponseTypeDef",
-    {
-        "streamId": str,
-        "streamArn": str,
-        "description": str,
-        "streamVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateThingGroupResponseTypeDef = TypedDict(
-    "UpdateThingGroupResponseTypeDef",
-    {
-        "version": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 _RequiredCreateThingRequestRequestTypeDef = TypedDict(
     "_RequiredCreateThingRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
@@ -5602,24 +6815,24 @@
 
 
 ListAuditMitigationActionsExecutionsResponseTypeDef = TypedDict(
     "ListAuditMitigationActionsExecutionsResponseTypeDef",
     {
         "actionsExecutions": List[AuditMitigationActionExecutionMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAuditMitigationActionsTasksResponseTypeDef = TypedDict(
     "ListAuditMitigationActionsTasksResponseTypeDef",
     {
         "tasks": List[AuditMitigationActionsTaskMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartAuditMitigationActionsTaskRequestRequestTypeDef = TypedDict(
     "StartAuditMitigationActionsTaskRequestRequestTypeDef",
     {
         "taskId": str,
@@ -5633,15 +6846,15 @@
     "DescribeAccountAuditConfigurationResponseTypeDef",
     {
         "roleArn": str,
         "auditNotificationTargetConfigurations": Dict[
             Literal["SNS"], AuditNotificationTargetTypeDef
         ],
         "auditCheckConfigurations": Dict[str, AuditCheckConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAccountAuditConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateAccountAuditConfigurationRequestRequestTypeDef",
     {
         "roleArn": str,
@@ -5654,15 +6867,15 @@
 )
 
 ListAuditTasksResponseTypeDef = TypedDict(
     "ListAuditTasksResponseTypeDef",
     {
         "tasks": List[AuditTaskMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTestAuthorizationRequestRequestTypeDef = TypedDict(
     "_RequiredTestAuthorizationRequestRequestTypeDef",
     {
         "authInfos": Sequence[AuthInfoTypeDef],
@@ -5683,60 +6896,36 @@
 
 class TestAuthorizationRequestRequestTypeDef(
     _RequiredTestAuthorizationRequestRequestTypeDef, _OptionalTestAuthorizationRequestRequestTypeDef
 ):
     pass
 
 
-_RequiredUpdateDomainConfigurationRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateDomainConfigurationRequestRequestTypeDef",
-    {
-        "domainConfigurationName": str,
-    },
-)
-_OptionalUpdateDomainConfigurationRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateDomainConfigurationRequestRequestTypeDef",
-    {
-        "authorizerConfig": AuthorizerConfigTypeDef,
-        "domainConfigurationStatus": DomainConfigurationStatusType,
-        "removeAuthorizerConfig": bool,
-    },
-    total=False,
-)
-
-
-class UpdateDomainConfigurationRequestRequestTypeDef(
-    _RequiredUpdateDomainConfigurationRequestRequestTypeDef,
-    _OptionalUpdateDomainConfigurationRequestRequestTypeDef,
-):
-    pass
-
-
 DescribeAuthorizerResponseTypeDef = TypedDict(
     "DescribeAuthorizerResponseTypeDef",
     {
         "authorizerDescription": AuthorizerDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDefaultAuthorizerResponseTypeDef = TypedDict(
     "DescribeDefaultAuthorizerResponseTypeDef",
     {
         "authorizerDescription": AuthorizerDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAuthorizersResponseTypeDef = TypedDict(
     "ListAuthorizersResponseTypeDef",
     {
         "authorizers": List[AuthorizerSummaryTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AwsJobAbortConfigTypeDef = TypedDict(
     "AwsJobAbortConfigTypeDef",
     {
         "abortCriteriaList": Sequence[AwsJobAbortCriteriaTypeDef],
@@ -5767,15 +6956,15 @@
 )
 
 GetBehaviorModelTrainingSummariesResponseTypeDef = TypedDict(
     "GetBehaviorModelTrainingSummariesResponseTypeDef",
     {
         "summaries": List[BehaviorModelTrainingSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMetricToRetainTypeDef = TypedDict(
     "_RequiredMetricToRetainTypeDef",
     {
         "metric": str,
@@ -5799,15 +6988,15 @@
     {
         "billingGroupName": str,
         "billingGroupId": str,
         "billingGroupArn": str,
         "version": int,
         "billingGroupProperties": BillingGroupPropertiesTypeDef,
         "billingGroupMetadata": BillingGroupMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateBillingGroupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateBillingGroupRequestRequestTypeDef",
     {
         "billingGroupName": str,
@@ -5831,15 +7020,15 @@
 
 
 GetBucketsAggregationResponseTypeDef = TypedDict(
     "GetBucketsAggregationResponseTypeDef",
     {
         "totalCount": int,
         "buckets": List[BucketTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BucketsAggregationTypeTypeDef = TypedDict(
     "BucketsAggregationTypeTypeDef",
     {
         "termsAggregation": TermsAggregationTypeDef,
@@ -5867,15 +7056,15 @@
 )
 
 ListCACertificatesResponseTypeDef = TypedDict(
     "ListCACertificatesResponseTypeDef",
     {
         "certificates": List[CACertificateTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CertificateDescriptionTypeDef = TypedDict(
     "CertificateDescriptionTypeDef",
     {
         "certificateArn": str,
@@ -5897,24 +7086,24 @@
 )
 
 ListCertificatesByCAResponseTypeDef = TypedDict(
     "ListCertificatesByCAResponseTypeDef",
     {
         "certificates": List[CertificateTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCertificatesResponseTypeDef = TypedDict(
     "ListCertificatesResponseTypeDef",
     {
         "certificates": List[CertificateTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CustomCodeSigningTypeDef = TypedDict(
     "CustomCodeSigningTypeDef",
     {
         "signature": CodeSigningSignatureTypeDef,
@@ -5927,15 +7116,15 @@
 
 DescribeEventConfigurationsResponseTypeDef = TypedDict(
     "DescribeEventConfigurationsResponseTypeDef",
     {
         "eventConfigurations": Dict[EventTypeType, ConfigurationTypeDef],
         "creationDate": datetime,
         "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEventConfigurationsRequestRequestTypeDef = TypedDict(
     "UpdateEventConfigurationsRequestRequestTypeDef",
     {
         "eventConfigurations": Mapping[EventTypeType, ConfigurationTypeDef],
@@ -6038,41 +7227,14 @@
 
 class CreateDimensionRequestRequestTypeDef(
     _RequiredCreateDimensionRequestRequestTypeDef, _OptionalCreateDimensionRequestRequestTypeDef
 ):
     pass
 
 
-_RequiredCreateDomainConfigurationRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateDomainConfigurationRequestRequestTypeDef",
-    {
-        "domainConfigurationName": str,
-    },
-)
-_OptionalCreateDomainConfigurationRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateDomainConfigurationRequestRequestTypeDef",
-    {
-        "domainName": str,
-        "serverCertificateArns": Sequence[str],
-        "validationCertificateArn": str,
-        "authorizerConfig": AuthorizerConfigTypeDef,
-        "serviceType": ServiceTypeType,
-        "tags": Sequence[TagTypeDef],
-    },
-    total=False,
-)
-
-
-class CreateDomainConfigurationRequestRequestTypeDef(
-    _RequiredCreateDomainConfigurationRequestRequestTypeDef,
-    _OptionalCreateDomainConfigurationRequestRequestTypeDef,
-):
-    pass
-
-
 _RequiredCreateFleetMetricRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFleetMetricRequestRequestTypeDef",
     {
         "metricName": str,
         "queryString": str,
         "aggregationType": AggregationTypeTypeDef,
         "period": int,
@@ -6170,45 +7332,109 @@
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Sequence[TagTypeDef],
     },
 )
 
+_RequiredCreateDomainConfigurationRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateDomainConfigurationRequestRequestTypeDef",
+    {
+        "domainConfigurationName": str,
+    },
+)
+_OptionalCreateDomainConfigurationRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateDomainConfigurationRequestRequestTypeDef",
+    {
+        "domainName": str,
+        "serverCertificateArns": Sequence[str],
+        "validationCertificateArn": str,
+        "authorizerConfig": AuthorizerConfigTypeDef,
+        "serviceType": ServiceTypeType,
+        "tags": Sequence[TagTypeDef],
+        "tlsConfig": TlsConfigTypeDef,
+    },
+    total=False,
+)
+
+
+class CreateDomainConfigurationRequestRequestTypeDef(
+    _RequiredCreateDomainConfigurationRequestRequestTypeDef,
+    _OptionalCreateDomainConfigurationRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredUpdateDomainConfigurationRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateDomainConfigurationRequestRequestTypeDef",
+    {
+        "domainConfigurationName": str,
+    },
+)
+_OptionalUpdateDomainConfigurationRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateDomainConfigurationRequestRequestTypeDef",
+    {
+        "authorizerConfig": AuthorizerConfigTypeDef,
+        "domainConfigurationStatus": DomainConfigurationStatusType,
+        "removeAuthorizerConfig": bool,
+        "tlsConfig": TlsConfigTypeDef,
+    },
+    total=False,
+)
+
+
+class UpdateDomainConfigurationRequestRequestTypeDef(
+    _RequiredUpdateDomainConfigurationRequestRequestTypeDef,
+    _OptionalUpdateDomainConfigurationRequestRequestTypeDef,
+):
+    pass
+
+
+SchedulingConfigTypeDef = TypedDict(
+    "SchedulingConfigTypeDef",
+    {
+        "startTime": str,
+        "endTime": str,
+        "endBehavior": JobEndBehaviorType,
+        "maintenanceWindows": Sequence[MaintenanceWindowTypeDef],
+    },
+    total=False,
+)
+
 CreateKeysAndCertificateResponseTypeDef = TypedDict(
     "CreateKeysAndCertificateResponseTypeDef",
     {
         "certificateArn": str,
         "certificateId": str,
         "certificatePem": str,
         "keyPair": KeyPairTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateProvisioningClaimResponseTypeDef = TypedDict(
     "CreateProvisioningClaimResponseTypeDef",
     {
         "certificateId": str,
         "certificatePem": str,
         "keyPair": KeyPairTypeDef,
         "expiration": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateProvisioningTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateProvisioningTemplateRequestRequestTypeDef",
     {
         "templateName": str,
@@ -6246,15 +7472,15 @@
         "lastModifiedDate": datetime,
         "defaultVersionId": int,
         "templateBody": str,
         "enabled": bool,
         "provisioningRoleArn": str,
         "preProvisioningHook": ProvisioningHookTypeDef,
         "type": TemplateTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateProvisioningTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateProvisioningTemplateRequestRequestTypeDef",
     {
         "templateName": str,
@@ -6308,15 +7534,15 @@
     {
         "taskStatus": AuditTaskStatusType,
         "taskType": AuditTaskTypeType,
         "taskStartTime": datetime,
         "taskStatistics": TaskStatisticsTypeDef,
         "scheduledAuditName": str,
         "auditDetails": Dict[str, AuditCheckDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterCACertificateRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterCACertificateRequestRequestTypeDef",
     {
         "caCertificate": str,
@@ -6376,49 +7602,50 @@
         "domainName": str,
         "serverCertificates": List[ServerCertificateSummaryTypeDef],
         "authorizerConfig": AuthorizerConfigTypeDef,
         "domainConfigurationStatus": DomainConfigurationStatusType,
         "serviceType": ServiceTypeType,
         "domainType": DomainTypeType,
         "lastStatusChangeDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "tlsConfig": TlsConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeManagedJobTemplateResponseTypeDef = TypedDict(
     "DescribeManagedJobTemplateResponseTypeDef",
     {
         "templateName": str,
         "templateArn": str,
         "description": str,
         "templateVersion": str,
         "environments": List[str],
         "documentParameters": List[DocumentParameterTypeDef],
         "document": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRoleAliasResponseTypeDef = TypedDict(
     "DescribeRoleAliasResponseTypeDef",
     {
         "roleAliasDescription": RoleAliasDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeThingTypeResponseTypeDef = TypedDict(
     "DescribeThingTypeResponseTypeDef",
     {
         "thingTypeName": str,
         "thingTypeId": str,
         "thingTypeArn": str,
         "thingTypeProperties": ThingTypePropertiesTypeDef,
         "thingTypeMetadata": ThingTypeMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ThingTypeDefinitionTypeDef = TypedDict(
     "ThingTypeDefinitionTypeDef",
     {
         "thingTypeName": str,
@@ -6438,15 +7665,15 @@
 )
 
 ListDetectMitigationActionsExecutionsResponseTypeDef = TypedDict(
     "ListDetectMitigationActionsExecutionsResponseTypeDef",
     {
         "actionsExecutions": List[DetectMitigationActionExecutionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartDetectMitigationActionsTaskRequestRequestTypeDef = TypedDict(
     "_RequiredStartDetectMitigationActionsTaskRequestRequestTypeDef",
     {
         "taskId": str,
@@ -6474,15 +7701,15 @@
 
 
 ListDomainConfigurationsResponseTypeDef = TypedDict(
     "ListDomainConfigurationsResponseTypeDef",
     {
         "domainConfigurations": List[DomainConfigurationSummaryTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DynamoDBv2ActionTypeDef = TypedDict(
     "DynamoDBv2ActionTypeDef",
     {
         "roleArn": str,
@@ -6490,15 +7717,15 @@
     },
 )
 
 GetEffectivePoliciesResponseTypeDef = TypedDict(
     "GetEffectivePoliciesResponseTypeDef",
     {
         "effectivePolicies": List[EffectivePolicyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExponentialRolloutRateTypeDef = TypedDict(
     "ExponentialRolloutRateTypeDef",
     {
         "baseRatePerMinute": int,
@@ -6548,889 +7775,75 @@
 )
 
 ListFleetMetricsResponseTypeDef = TypedDict(
     "ListFleetMetricsResponseTypeDef",
     {
         "fleetMetrics": List[FleetMetricNameAndArnTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef = (
-    TypedDict(
-        "GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef",
-        {
-            "securityProfileName": str,
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-ListActiveViolationsRequestListActiveViolationsPaginateTypeDef = TypedDict(
-    "ListActiveViolationsRequestListActiveViolationsPaginateTypeDef",
-    {
-        "thingName": str,
-        "securityProfileName": str,
-        "behaviorCriteriaType": BehaviorCriteriaTypeType,
-        "listSuppressedAlerts": bool,
-        "verificationState": VerificationStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef",
-    {
-        "target": str,
-    },
-)
-_OptionalListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef",
-    {
-        "recursive": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef(
-    _RequiredListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef,
-    _OptionalListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef = TypedDict(
-    "_RequiredListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef",
-    {
-        "taskId": str,
-        "findingId": str,
-    },
-)
-_OptionalListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef = TypedDict(
-    "_OptionalListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef",
-    {
-        "actionStatus": AuditMitigationActionsExecutionStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef(
-    _RequiredListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef,
-    _OptionalListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef = TypedDict(
-    "_RequiredListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef",
-    {
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-    },
-)
-_OptionalListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef = TypedDict(
-    "_OptionalListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef",
+GetPackageConfigurationResponseTypeDef = TypedDict(
+    "GetPackageConfigurationResponseTypeDef",
     {
-        "auditTaskId": str,
-        "findingId": str,
-        "taskStatus": AuditMitigationActionsTaskStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "versionUpdateByJobsConfig": VersionUpdateByJobsConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef(
-    _RequiredListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef,
-    _OptionalListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAuditTasksRequestListAuditTasksPaginateTypeDef = TypedDict(
-    "_RequiredListAuditTasksRequestListAuditTasksPaginateTypeDef",
-    {
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-    },
-)
-_OptionalListAuditTasksRequestListAuditTasksPaginateTypeDef = TypedDict(
-    "_OptionalListAuditTasksRequestListAuditTasksPaginateTypeDef",
+UpdatePackageConfigurationRequestRequestTypeDef = TypedDict(
+    "UpdatePackageConfigurationRequestRequestTypeDef",
     {
-        "taskType": AuditTaskTypeType,
-        "taskStatus": AuditTaskStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "versionUpdateByJobsConfig": VersionUpdateByJobsConfigTypeDef,
+        "clientToken": str,
     },
     total=False,
 )
 
-
-class ListAuditTasksRequestListAuditTasksPaginateTypeDef(
-    _RequiredListAuditTasksRequestListAuditTasksPaginateTypeDef,
-    _OptionalListAuditTasksRequestListAuditTasksPaginateTypeDef,
-):
-    pass
-
-
-ListAuthorizersRequestListAuthorizersPaginateTypeDef = TypedDict(
-    "ListAuthorizersRequestListAuthorizersPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "status": AuthorizerStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListBillingGroupsRequestListBillingGroupsPaginateTypeDef = TypedDict(
-    "ListBillingGroupsRequestListBillingGroupsPaginateTypeDef",
-    {
-        "namePrefixFilter": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCACertificatesRequestListCACertificatesPaginateTypeDef = TypedDict(
-    "ListCACertificatesRequestListCACertificatesPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "templateName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListCertificatesByCARequestListCertificatesByCAPaginateTypeDef = TypedDict(
-    "_RequiredListCertificatesByCARequestListCertificatesByCAPaginateTypeDef",
-    {
-        "caCertificateId": str,
-    },
-)
-_OptionalListCertificatesByCARequestListCertificatesByCAPaginateTypeDef = TypedDict(
-    "_OptionalListCertificatesByCARequestListCertificatesByCAPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListCertificatesByCARequestListCertificatesByCAPaginateTypeDef(
-    _RequiredListCertificatesByCARequestListCertificatesByCAPaginateTypeDef,
-    _OptionalListCertificatesByCARequestListCertificatesByCAPaginateTypeDef,
-):
-    pass
-
-
-ListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
-    "ListCertificatesRequestListCertificatesPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCustomMetricsRequestListCustomMetricsPaginateTypeDef = TypedDict(
-    "ListCustomMetricsRequestListCustomMetricsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef = TypedDict(
-    "ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef",
-    {
-        "taskId": str,
-        "violationId": str,
-        "thingName": str,
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef = TypedDict(
-    "_RequiredListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef",
-    {
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-    },
-)
-_OptionalListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef = TypedDict(
-    "_OptionalListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef(
-    _RequiredListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef,
-    _OptionalListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef,
-):
-    pass
-
-
-ListDimensionsRequestListDimensionsPaginateTypeDef = TypedDict(
-    "ListDimensionsRequestListDimensionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef = TypedDict(
-    "ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef",
-    {
-        "serviceType": ServiceTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListFleetMetricsRequestListFleetMetricsPaginateTypeDef = TypedDict(
-    "ListFleetMetricsRequestListFleetMetricsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListIndicesRequestListIndicesPaginateTypeDef = TypedDict(
-    "ListIndicesRequestListIndicesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef = TypedDict(
-    "_RequiredListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef",
-    {
-        "jobId": str,
-    },
-)
-_OptionalListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef = TypedDict(
-    "_OptionalListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef",
-    {
-        "status": JobExecutionStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef(
-    _RequiredListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef,
-    _OptionalListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef = TypedDict(
-    "_RequiredListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef",
-    {
-        "thingName": str,
-    },
-)
-_OptionalListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef = TypedDict(
-    "_OptionalListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef",
-    {
-        "status": JobExecutionStatusType,
-        "namespaceId": str,
-        "jobId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef(
-    _RequiredListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef,
-    _OptionalListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef,
-):
-    pass
-
-
-ListJobTemplatesRequestListJobTemplatesPaginateTypeDef = TypedDict(
-    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListJobsRequestListJobsPaginateTypeDef = TypedDict(
-    "ListJobsRequestListJobsPaginateTypeDef",
-    {
-        "status": JobStatusType,
-        "targetSelection": TargetSelectionType,
-        "thingGroupName": str,
-        "thingGroupId": str,
-        "namespaceId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListMetricValuesRequestListMetricValuesPaginateTypeDef = TypedDict(
-    "_RequiredListMetricValuesRequestListMetricValuesPaginateTypeDef",
-    {
-        "thingName": str,
-        "metricName": str,
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-    },
-)
-_OptionalListMetricValuesRequestListMetricValuesPaginateTypeDef = TypedDict(
-    "_OptionalListMetricValuesRequestListMetricValuesPaginateTypeDef",
-    {
-        "dimensionName": str,
-        "dimensionValueOperator": DimensionValueOperatorType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListMetricValuesRequestListMetricValuesPaginateTypeDef(
-    _RequiredListMetricValuesRequestListMetricValuesPaginateTypeDef,
-    _OptionalListMetricValuesRequestListMetricValuesPaginateTypeDef,
-):
-    pass
-
-
-ListMitigationActionsRequestListMitigationActionsPaginateTypeDef = TypedDict(
-    "ListMitigationActionsRequestListMitigationActionsPaginateTypeDef",
-    {
-        "actionType": MitigationActionTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef = TypedDict(
-    "ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef",
-    {
-        "otaUpdateStatus": OTAUpdateStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef = TypedDict(
-    "ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
-    "ListPoliciesRequestListPoliciesPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef = TypedDict(
-    "_RequiredListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef",
-    {
-        "policyName": str,
-    },
-)
-_OptionalListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef = TypedDict(
-    "_OptionalListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef(
-    _RequiredListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef,
-    _OptionalListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef",
-    {
-        "principal": str,
-    },
-)
-_OptionalListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef(
-    _RequiredListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef,
-    _OptionalListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef = TypedDict(
-    "_RequiredListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef",
-    {
-        "principal": str,
-    },
-)
-_OptionalListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef = TypedDict(
-    "_OptionalListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef(
-    _RequiredListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef,
-    _OptionalListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef",
-    {
-        "templateName": str,
-    },
-)
-_OptionalListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef(
-    _RequiredListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef,
-    _OptionalListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef,
-):
-    pass
-
-
-ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef = TypedDict(
-    "ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRoleAliasesRequestListRoleAliasesPaginateTypeDef = TypedDict(
-    "ListRoleAliasesRequestListRoleAliasesPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef = TypedDict(
-    "ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef = (
-    TypedDict(
-        "_RequiredListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef",
-        {
-            "securityProfileTargetArn": str,
-        },
-    )
-)
-_OptionalListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef = (
-    TypedDict(
-        "_OptionalListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef",
-        {
-            "recursive": bool,
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-
-class ListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef(
-    _RequiredListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef,
-    _OptionalListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef,
-):
-    pass
-
-
-ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef = TypedDict(
-    "ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef",
-    {
-        "dimensionName": str,
-        "metricName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListStreamsRequestListStreamsPaginateTypeDef = TypedDict(
-    "ListStreamsRequestListStreamsPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
-    "_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
-    {
-        "policyName": str,
-    },
-)
-_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
-    "_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef(
-    _RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
-    _OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef = (
-    TypedDict(
-        "_RequiredListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef",
-        {
-            "securityProfileName": str,
-        },
-    )
-)
-_OptionalListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef = (
-    TypedDict(
-        "_OptionalListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef",
-        {
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-
-class ListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef(
-    _RequiredListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef,
-    _OptionalListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef,
-):
-    pass
-
-
-_RequiredListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef = TypedDict(
-    "_RequiredListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef",
-    {
-        "thingName": str,
-    },
-)
-_OptionalListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef = TypedDict(
-    "_OptionalListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef(
-    _RequiredListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef,
-    _OptionalListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef,
-):
-    pass
-
-
-ListThingGroupsRequestListThingGroupsPaginateTypeDef = TypedDict(
-    "ListThingGroupsRequestListThingGroupsPaginateTypeDef",
-    {
-        "parentGroup": str,
-        "namePrefixFilter": str,
-        "recursive": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef = TypedDict(
-    "_RequiredListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef",
-    {
-        "thingName": str,
-    },
-)
-_OptionalListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef = TypedDict(
-    "_OptionalListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef(
-    _RequiredListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef,
-    _OptionalListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef = TypedDict(
-    "_RequiredListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef",
-    {
-        "taskId": str,
-        "reportType": ReportTypeType,
-    },
-)
-_OptionalListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef = TypedDict(
-    "_OptionalListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef(
-    _RequiredListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef,
-    _OptionalListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef,
-):
-    pass
-
-
-ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef = TypedDict(
-    "ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef",
-    {
-        "status": StatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListThingTypesRequestListThingTypesPaginateTypeDef = TypedDict(
-    "ListThingTypesRequestListThingTypesPaginateTypeDef",
-    {
-        "thingTypeName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef = TypedDict(
-    "_RequiredListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef",
-    {
-        "billingGroupName": str,
-    },
-)
-_OptionalListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef = TypedDict(
-    "_OptionalListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef(
-    _RequiredListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef,
-    _OptionalListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef = TypedDict(
-    "_RequiredListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef",
-    {
-        "thingGroupName": str,
-    },
-)
-_OptionalListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef = TypedDict(
-    "_OptionalListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef",
-    {
-        "recursive": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef(
-    _RequiredListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef,
-    _OptionalListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef,
-):
-    pass
-
-
-ListThingsRequestListThingsPaginateTypeDef = TypedDict(
-    "ListThingsRequestListThingsPaginateTypeDef",
-    {
-        "attributeName": str,
-        "attributeValue": str,
-        "thingTypeName": str,
-        "usePrefixAttributeValue": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef = TypedDict(
-    "ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTopicRulesRequestListTopicRulesPaginateTypeDef = TypedDict(
-    "ListTopicRulesRequestListTopicRulesPaginateTypeDef",
-    {
-        "topic": str,
-        "ruleDisabled": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef = TypedDict(
-    "ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef",
-    {
-        "targetType": LogTargetTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListViolationEventsRequestListViolationEventsPaginateTypeDef = TypedDict(
-    "_RequiredListViolationEventsRequestListViolationEventsPaginateTypeDef",
-    {
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-    },
-)
-_OptionalListViolationEventsRequestListViolationEventsPaginateTypeDef = TypedDict(
-    "_OptionalListViolationEventsRequestListViolationEventsPaginateTypeDef",
-    {
-        "thingName": str,
-        "securityProfileName": str,
-        "behaviorCriteriaType": BehaviorCriteriaTypeType,
-        "listSuppressedAlerts": bool,
-        "verificationState": VerificationStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListViolationEventsRequestListViolationEventsPaginateTypeDef(
-    _RequiredListViolationEventsRequestListViolationEventsPaginateTypeDef,
-    _OptionalListViolationEventsRequestListViolationEventsPaginateTypeDef,
-):
-    pass
-
-
 GetPercentilesResponseTypeDef = TypedDict(
     "GetPercentilesResponseTypeDef",
     {
         "percentiles": List[PercentPairTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStatisticsResponseTypeDef = TypedDict(
     "GetStatisticsResponseTypeDef",
     {
         "statistics": StatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBillingGroupsResponseTypeDef = TypedDict(
     "ListBillingGroupsResponseTypeDef",
     {
         "billingGroups": List[GroupNameAndArnTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListThingGroupsForThingResponseTypeDef = TypedDict(
     "ListThingGroupsForThingResponseTypeDef",
     {
         "thingGroups": List[GroupNameAndArnTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListThingGroupsResponseTypeDef = TypedDict(
     "ListThingGroupsResponseTypeDef",
     {
         "thingGroups": List[GroupNameAndArnTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ThingGroupMetadataTypeDef = TypedDict(
     "ThingGroupMetadataTypeDef",
     {
         "parentGroupName": str,
@@ -7518,122 +7931,140 @@
 )
 
 ListJobsResponseTypeDef = TypedDict(
     "ListJobsResponseTypeDef",
     {
         "jobs": List[JobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobTemplatesResponseTypeDef = TypedDict(
     "ListJobTemplatesResponseTypeDef",
     {
         "jobTemplates": List[JobTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListManagedJobTemplatesResponseTypeDef = TypedDict(
     "ListManagedJobTemplatesResponseTypeDef",
     {
         "managedJobTemplates": List[ManagedJobTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMitigationActionsResponseTypeDef = TypedDict(
     "ListMitigationActionsResponseTypeDef",
     {
         "actionIdentifiers": List[MitigationActionIdentifierTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOTAUpdatesResponseTypeDef = TypedDict(
     "ListOTAUpdatesResponseTypeDef",
     {
         "otaUpdates": List[OTAUpdateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOutgoingCertificatesResponseTypeDef = TypedDict(
     "ListOutgoingCertificatesResponseTypeDef",
     {
         "outgoingCertificates": List[OutgoingCertificateTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListPackageVersionsResponseTypeDef = TypedDict(
+    "ListPackageVersionsResponseTypeDef",
+    {
+        "packageVersionSummaries": List[PackageVersionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListPackagesResponseTypeDef = TypedDict(
+    "ListPackagesResponseTypeDef",
+    {
+        "packageSummaries": List[PackageSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPolicyVersionsResponseTypeDef = TypedDict(
     "ListPolicyVersionsResponseTypeDef",
     {
         "policyVersions": List[PolicyVersionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProvisioningTemplateVersionsResponseTypeDef = TypedDict(
     "ListProvisioningTemplateVersionsResponseTypeDef",
     {
         "versions": List[ProvisioningTemplateVersionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProvisioningTemplatesResponseTypeDef = TypedDict(
     "ListProvisioningTemplatesResponseTypeDef",
     {
         "templates": List[ProvisioningTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListScheduledAuditsResponseTypeDef = TypedDict(
     "ListScheduledAuditsResponseTypeDef",
     {
         "scheduledAudits": List[ScheduledAuditMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSecurityProfilesResponseTypeDef = TypedDict(
     "ListSecurityProfilesResponseTypeDef",
     {
         "securityProfileIdentifiers": List[SecurityProfileIdentifierTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamsResponseTypeDef = TypedDict(
     "ListStreamsResponseTypeDef",
     {
         "streams": List[StreamSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTargetsForSecurityProfileResponseTypeDef = TypedDict(
     "ListTargetsForSecurityProfileResponseTypeDef",
     {
         "securityProfileTargets": List[SecurityProfileTargetTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SecurityProfileTargetMappingTypeDef = TypedDict(
     "SecurityProfileTargetMappingTypeDef",
     {
         "securityProfileIdentifier": SecurityProfileIdentifierTypeDef,
@@ -7643,24 +8074,24 @@
 )
 
 ListThingsResponseTypeDef = TypedDict(
     "ListThingsResponseTypeDef",
     {
         "things": List[ThingAttributeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTopicRulesResponseTypeDef = TypedDict(
     "ListTopicRulesResponseTypeDef",
     {
         "rules": List[TopicRuleListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredLocationActionTypeDef = TypedDict(
     "_RequiredLocationActionTypeDef",
     {
         "roleArn": str,
@@ -7851,24 +8282,24 @@
 )
 
 ValidateSecurityProfileBehaviorsResponseTypeDef = TypedDict(
     "ValidateSecurityProfileBehaviorsResponseTypeDef",
     {
         "valid": bool,
         "validationErrors": List[ValidationErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMetricValuesResponseTypeDef = TypedDict(
     "ListMetricValuesResponseTypeDef",
     {
         "metricDatumList": List[MetricDatumTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeniedTypeDef = TypedDict(
     "DeniedTypeDef",
     {
         "implicitDeny": ImplicitDenyTypeDef,
@@ -8055,32 +8486,32 @@
 
 
 DescribeCACertificateResponseTypeDef = TypedDict(
     "DescribeCACertificateResponseTypeDef",
     {
         "certificateDescription": CACertificateDescriptionTypeDef,
         "registrationConfig": RegistrationConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCertificateResponseTypeDef = TypedDict(
     "DescribeCertificateResponseTypeDef",
     {
         "certificateDescription": CertificateDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListThingTypesResponseTypeDef = TypedDict(
     "ListThingTypesResponseTypeDef",
     {
         "thingTypes": List[ThingTypeDefinitionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartSigningJobParameterTypeDef = TypedDict(
     "StartSigningJobParameterTypeDef",
     {
         "signingProfileParameter": SigningProfileParameterTypeDef,
@@ -8170,15 +8601,15 @@
         "version": int,
         "thingGroupProperties": ThingGroupPropertiesTypeDef,
         "thingGroupMetadata": ThingGroupMetadataTypeDef,
         "indexName": str,
         "queryString": str,
         "queryVersion": str,
         "status": DynamicGroupStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredHttpActionTypeDef = TypedDict(
     "_RequiredHttpActionTypeDef",
     {
         "url": str,
@@ -8200,15 +8631,15 @@
 
 
 GetIndexingConfigurationResponseTypeDef = TypedDict(
     "GetIndexingConfigurationResponseTypeDef",
     {
         "thingIndexingConfiguration": ThingIndexingConfigurationTypeDef,
         "thingGroupIndexingConfiguration": ThingGroupIndexingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateIndexingConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateIndexingConfigurationRequestRequestTypeDef",
     {
         "thingIndexingConfiguration": ThingIndexingConfigurationTypeDef,
@@ -8217,51 +8648,51 @@
     total=False,
 )
 
 DescribeJobExecutionResponseTypeDef = TypedDict(
     "DescribeJobExecutionResponseTypeDef",
     {
         "execution": JobExecutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobExecutionsForJobResponseTypeDef = TypedDict(
     "ListJobExecutionsForJobResponseTypeDef",
     {
         "executionSummaries": List[JobExecutionSummaryForJobTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobExecutionsForThingResponseTypeDef = TypedDict(
     "ListJobExecutionsForThingResponseTypeDef",
     {
         "executionSummaries": List[JobExecutionSummaryForThingTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSecurityProfilesForTargetResponseTypeDef = TypedDict(
     "ListSecurityProfilesForTargetResponseTypeDef",
     {
         "securityProfileTargetMappings": List[SecurityProfileTargetMappingTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListV2LoggingLevelsResponseTypeDef = TypedDict(
     "ListV2LoggingLevelsResponseTypeDef",
     {
         "logTargetConfigurations": List[LogTargetConfigurationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateMitigationActionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateMitigationActionRequestRequestTypeDef",
     {
         "actionName": str,
@@ -8292,15 +8723,15 @@
         "actionType": MitigationActionTypeType,
         "actionArn": str,
         "actionId": str,
         "roleArn": str,
         "actionParams": MitigationActionParamsTypeDef,
         "creationDate": datetime,
         "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MitigationActionTypeDef = TypedDict(
     "MitigationActionTypeDef",
     {
         "name": str,
@@ -8423,28 +8854,28 @@
     "DescribeAuditSuppressionResponseTypeDef",
     {
         "checkName": str,
         "resourceIdentifier": ResourceIdentifierTypeDef,
         "expirationDate": datetime,
         "suppressIndefinitely": bool,
         "description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAuditFindingsRequestListAuditFindingsPaginateTypeDef = TypedDict(
     "ListAuditFindingsRequestListAuditFindingsPaginateTypeDef",
     {
         "taskId": str,
         "checkName": str,
         "resourceIdentifier": ResourceIdentifierTypeDef,
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
         "listSuppressedFindings": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAuditFindingsRequestRequestTypeDef = TypedDict(
     "ListAuditFindingsRequestRequestTypeDef",
     {
@@ -8462,15 +8893,15 @@
 
 ListAuditSuppressionsRequestListAuditSuppressionsPaginateTypeDef = TypedDict(
     "ListAuditSuppressionsRequestListAuditSuppressionsPaginateTypeDef",
     {
         "checkName": str,
         "resourceIdentifier": ResourceIdentifierTypeDef,
         "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAuditSuppressionsRequestRequestTypeDef = TypedDict(
     "ListAuditSuppressionsRequestRequestTypeDef",
     {
@@ -8530,15 +8961,15 @@
 
 SearchIndexResponseTypeDef = TypedDict(
     "SearchIndexResponseTypeDef",
     {
         "nextToken": str,
         "things": List[ThingDocumentTypeDef],
         "thingGroups": List[ThingGroupDocumentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTopicRuleDestinationRequestRequestTypeDef = TypedDict(
     "CreateTopicRuleDestinationRequestRequestTypeDef",
     {
         "destinationConfiguration": TopicRuleDestinationConfigurationTypeDef,
@@ -8546,31 +8977,31 @@
 )
 
 ListTopicRuleDestinationsResponseTypeDef = TypedDict(
     "ListTopicRuleDestinationsResponseTypeDef",
     {
         "destinationSummaries": List[TopicRuleDestinationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTopicRuleDestinationResponseTypeDef = TypedDict(
     "CreateTopicRuleDestinationResponseTypeDef",
     {
         "topicRuleDestination": TopicRuleDestinationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTopicRuleDestinationResponseTypeDef = TypedDict(
     "GetTopicRuleDestinationResponseTypeDef",
     {
         "topicRuleDestination": TopicRuleDestinationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AuthResultTypeDef = TypedDict(
     "AuthResultTypeDef",
     {
         "authInfo": AuthInfoTypeDef,
@@ -8643,15 +9074,15 @@
         "behaviors": List[BehaviorTypeDef],
         "alertTargets": Dict[Literal["SNS"], AlertTargetTypeDef],
         "additionalMetricsToRetain": List[str],
         "additionalMetricsToRetainV2": List[MetricToRetainTypeDef],
         "version": int,
         "creationDate": datetime,
         "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateSecurityProfileRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSecurityProfileRequestRequestTypeDef",
     {
         "securityProfileName": str,
@@ -8690,15 +9121,15 @@
         "behaviors": List[BehaviorTypeDef],
         "alertTargets": Dict[Literal["SNS"], AlertTargetTypeDef],
         "additionalMetricsToRetain": List[str],
         "additionalMetricsToRetainV2": List[MetricToRetainTypeDef],
         "version": int,
         "creationDate": datetime,
         "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ValidateSecurityProfileBehaviorsRequestRequestTypeDef = TypedDict(
     "ValidateSecurityProfileBehaviorsRequestRequestTypeDef",
     {
         "behaviors": Sequence[BehaviorTypeDef],
@@ -8752,14 +9183,15 @@
         "timeoutConfig": TimeoutConfigTypeDef,
         "tags": Sequence[TagTypeDef],
         "namespaceId": str,
         "jobTemplateArn": str,
         "jobExecutionsRetryConfig": JobExecutionsRetryConfigTypeDef,
         "documentParameters": Mapping[str, str],
         "schedulingConfig": SchedulingConfigTypeDef,
+        "destinationPackageVersions": Sequence[str],
     },
     total=False,
 )
 
 
 class CreateJobRequestRequestTypeDef(
     _RequiredCreateJobRequestRequestTypeDef, _OptionalCreateJobRequestRequestTypeDef
@@ -8782,14 +9214,16 @@
         "document": str,
         "presignedUrlConfig": PresignedUrlConfigTypeDef,
         "jobExecutionsRolloutConfig": JobExecutionsRolloutConfigTypeDef,
         "abortConfig": AbortConfigTypeDef,
         "timeoutConfig": TimeoutConfigTypeDef,
         "tags": Sequence[TagTypeDef],
         "jobExecutionsRetryConfig": JobExecutionsRetryConfigTypeDef,
+        "maintenanceWindows": Sequence[MaintenanceWindowTypeDef],
+        "destinationPackageVersions": Sequence[str],
     },
     total=False,
 )
 
 
 class CreateJobTemplateRequestRequestTypeDef(
     _RequiredCreateJobTemplateRequestRequestTypeDef, _OptionalCreateJobTemplateRequestRequestTypeDef
@@ -8807,15 +9241,17 @@
         "document": str,
         "createdAt": datetime,
         "presignedUrlConfig": PresignedUrlConfigTypeDef,
         "jobExecutionsRolloutConfig": JobExecutionsRolloutConfigTypeDef,
         "abortConfig": AbortConfigTypeDef,
         "timeoutConfig": TimeoutConfigTypeDef,
         "jobExecutionsRetryConfig": JobExecutionsRetryConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "maintenanceWindows": List[MaintenanceWindowTypeDef],
+        "destinationPackageVersions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 JobTypeDef = TypedDict(
     "JobTypeDef",
     {
         "jobArn": str,
@@ -8837,14 +9273,16 @@
         "timeoutConfig": TimeoutConfigTypeDef,
         "namespaceId": str,
         "jobTemplateArn": str,
         "jobExecutionsRetryConfig": JobExecutionsRetryConfigTypeDef,
         "documentParameters": Dict[str, str],
         "isConcurrent": bool,
         "schedulingConfig": SchedulingConfigTypeDef,
+        "scheduledJobRollouts": List[ScheduledJobRolloutTypeDef],
+        "destinationPackageVersions": List[str],
     },
     total=False,
 )
 
 _RequiredUpdateJobRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateJobRequestRequestTypeDef",
     {
@@ -8872,29 +9310,29 @@
     pass
 
 
 DescribeStreamResponseTypeDef = TypedDict(
     "DescribeStreamResponseTypeDef",
     {
         "streamInfo": StreamInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAuditMitigationActionsTaskResponseTypeDef = TypedDict(
     "DescribeAuditMitigationActionsTaskResponseTypeDef",
     {
         "taskStatus": AuditMitigationActionsTaskStatusType,
         "startTime": datetime,
         "endTime": datetime,
         "taskStatistics": Dict[str, TaskStatisticsForAuditCheckTypeDef],
         "target": AuditMitigationActionsTaskTargetTypeDef,
         "auditCheckToActionsMapping": Dict[str, List[str]],
         "actionsDefinition": List[MitigationActionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectMitigationActionsTaskSummaryTypeDef = TypedDict(
     "DetectMitigationActionsTaskSummaryTypeDef",
     {
         "taskId": str,
@@ -8912,15 +9350,15 @@
 )
 
 ListAuditSuppressionsResponseTypeDef = TypedDict(
     "ListAuditSuppressionsResponseTypeDef",
     {
         "suppressions": List[AuditSuppressionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AuditFindingTypeDef = TypedDict(
     "AuditFindingTypeDef",
     {
         "findingId": str,
@@ -8939,23 +9377,23 @@
 )
 
 ListRelatedResourcesForAuditFindingResponseTypeDef = TypedDict(
     "ListRelatedResourcesForAuditFindingResponseTypeDef",
     {
         "relatedResources": List[RelatedResourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TestAuthorizationResponseTypeDef = TypedDict(
     "TestAuthorizationResponseTypeDef",
     {
         "authResults": List[AuthResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActionTypeDef = TypedDict(
     "ActionTypeDef",
     {
         "dynamoDB": DynamoDBActionTypeDef,
@@ -8986,24 +9424,24 @@
 )
 
 ListActiveViolationsResponseTypeDef = TypedDict(
     "ListActiveViolationsResponseTypeDef",
     {
         "activeViolations": List[ActiveViolationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListViolationEventsResponseTypeDef = TypedDict(
     "ListViolationEventsResponseTypeDef",
     {
         "violationEvents": List[ViolationEventTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OTAUpdateFileTypeDef = TypedDict(
     "OTAUpdateFileTypeDef",
     {
         "fileName": str,
@@ -9017,49 +9455,49 @@
 )
 
 DescribeJobResponseTypeDef = TypedDict(
     "DescribeJobResponseTypeDef",
     {
         "documentSource": str,
         "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDetectMitigationActionsTaskResponseTypeDef = TypedDict(
     "DescribeDetectMitigationActionsTaskResponseTypeDef",
     {
         "taskSummary": DetectMitigationActionsTaskSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDetectMitigationActionsTasksResponseTypeDef = TypedDict(
     "ListDetectMitigationActionsTasksResponseTypeDef",
     {
         "tasks": List[DetectMitigationActionsTaskSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAuditFindingResponseTypeDef = TypedDict(
     "DescribeAuditFindingResponseTypeDef",
     {
         "finding": AuditFindingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAuditFindingsResponseTypeDef = TypedDict(
     "ListAuditFindingsResponseTypeDef",
     {
         "findings": List[AuditFindingTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTopicRulePayloadTypeDef = TypedDict(
     "_RequiredTopicRulePayloadTypeDef",
     {
         "sql": str,
@@ -9183,18 +9621,18 @@
 )
 
 GetTopicRuleResponseTypeDef = TypedDict(
     "GetTopicRuleResponseTypeDef",
     {
         "ruleArn": str,
         "rule": TopicRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOTAUpdateResponseTypeDef = TypedDict(
     "GetOTAUpdateResponseTypeDef",
     {
         "otaUpdateInfo": OTAUpdateInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot/type_defs.pyi` & `types-aiobotocore-iot-2.5.1/types_aiobotocore_iot/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -59,14 +59,16 @@
     LogLevelType,
     LogTargetTypeType,
     MessageFormatType,
     MitigationActionTypeType,
     ModelStatusType,
     NamedShadowIndexingModeType,
     OTAUpdateStatusType,
+    PackageVersionActionType,
+    PackageVersionStatusType,
     ProtocolType,
     ReportTypeType,
     ResourceTypeType,
     RetryableFailureTypeType,
     ServerCertificateStatusType,
     ServiceTypeType,
     StatusType,
@@ -116,15 +118,15 @@
     "AddThingsToThingGroupParamsTypeDef",
     "AggregationTypeTypeDef",
     "AlertTargetTypeDef",
     "PolicyTypeDef",
     "AssetPropertyTimestampTypeDef",
     "AssetPropertyVariantTypeDef",
     "AssociateTargetsWithJobRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateTargetsWithJobResponseTypeDef",
     "AttachPolicyRequestRequestTypeDef",
     "AttachPrincipalPolicyRequestRequestTypeDef",
     "AttachSecurityProfileRequestRequestTypeDef",
     "AttachThingPrincipalRequestRequestTypeDef",
     "AttributePayloadTypeDef",
     "AuditCheckConfigurationTypeDef",
     "AuditCheckDetailsTypeDef",
@@ -153,32 +155,61 @@
     "CACertificateTypeDef",
     "CancelAuditMitigationActionsTaskRequestRequestTypeDef",
     "CancelAuditTaskRequestRequestTypeDef",
     "CancelCertificateTransferRequestRequestTypeDef",
     "CancelDetectMitigationActionsTaskRequestRequestTypeDef",
     "CancelJobExecutionRequestRequestTypeDef",
     "CancelJobRequestRequestTypeDef",
+    "CancelJobResponseTypeDef",
     "TransferDataTypeDef",
     "CertificateTypeDef",
     "CodeSigningCertificateChainTypeDef",
     "CodeSigningSignatureTypeDef",
     "ConfigurationTypeDef",
     "ConfirmTopicRuleDestinationRequestRequestTypeDef",
     "TagTypeDef",
+    "CreateAuthorizerResponseTypeDef",
+    "CreateBillingGroupResponseTypeDef",
     "CreateCertificateFromCsrRequestRequestTypeDef",
+    "CreateCertificateFromCsrResponseTypeDef",
+    "CreateCustomMetricResponseTypeDef",
+    "CreateDimensionResponseTypeDef",
+    "TlsConfigTypeDef",
+    "CreateDomainConfigurationResponseTypeDef",
+    "CreateDynamicThingGroupResponseTypeDef",
+    "CreateFleetMetricResponseTypeDef",
     "PresignedUrlConfigTypeDef",
-    "SchedulingConfigTypeDef",
     "TimeoutConfigTypeDef",
+    "CreateJobResponseTypeDef",
+    "MaintenanceWindowTypeDef",
+    "CreateJobTemplateResponseTypeDef",
     "CreateKeysAndCertificateRequestRequestTypeDef",
     "KeyPairTypeDef",
+    "CreateMitigationActionResponseTypeDef",
+    "CreateOTAUpdateResponseTypeDef",
+    "CreatePackageRequestRequestTypeDef",
+    "CreatePackageResponseTypeDef",
+    "CreatePackageVersionRequestRequestTypeDef",
+    "CreatePackageVersionResponseTypeDef",
+    "CreatePolicyResponseTypeDef",
     "CreatePolicyVersionRequestRequestTypeDef",
+    "CreatePolicyVersionResponseTypeDef",
     "CreateProvisioningClaimRequestRequestTypeDef",
     "ProvisioningHookTypeDef",
+    "CreateProvisioningTemplateResponseTypeDef",
     "CreateProvisioningTemplateVersionRequestRequestTypeDef",
+    "CreateProvisioningTemplateVersionResponseTypeDef",
+    "CreateRoleAliasResponseTypeDef",
+    "CreateScheduledAuditResponseTypeDef",
+    "CreateSecurityProfileResponseTypeDef",
+    "CreateStreamResponseTypeDef",
+    "CreateThingGroupResponseTypeDef",
+    "CreateThingResponseTypeDef",
     "ThingTypePropertiesTypeDef",
+    "CreateThingTypeResponseTypeDef",
     "DeleteAccountAuditConfigurationRequestRequestTypeDef",
     "DeleteAuthorizerRequestRequestTypeDef",
     "DeleteBillingGroupRequestRequestTypeDef",
     "DeleteCACertificateRequestRequestTypeDef",
     "DeleteCertificateRequestRequestTypeDef",
     "DeleteCustomMetricRequestRequestTypeDef",
     "DeleteDimensionRequestRequestTypeDef",
@@ -186,14 +217,16 @@
     "DeleteDynamicThingGroupRequestRequestTypeDef",
     "DeleteFleetMetricRequestRequestTypeDef",
     "DeleteJobExecutionRequestRequestTypeDef",
     "DeleteJobRequestRequestTypeDef",
     "DeleteJobTemplateRequestRequestTypeDef",
     "DeleteMitigationActionRequestRequestTypeDef",
     "DeleteOTAUpdateRequestRequestTypeDef",
+    "DeletePackageRequestRequestTypeDef",
+    "DeletePackageVersionRequestRequestTypeDef",
     "DeletePolicyRequestRequestTypeDef",
     "DeletePolicyVersionRequestRequestTypeDef",
     "DeleteProvisioningTemplateRequestRequestTypeDef",
     "DeleteProvisioningTemplateVersionRequestRequestTypeDef",
     "DeleteRoleAliasRequestRequestTypeDef",
     "DeleteScheduledAuditRequestRequestTypeDef",
     "DeleteSecurityProfileRequestRequestTypeDef",
@@ -212,37 +245,45 @@
     "TaskStatisticsTypeDef",
     "DescribeAuthorizerRequestRequestTypeDef",
     "DescribeBillingGroupRequestRequestTypeDef",
     "DescribeCACertificateRequestRequestTypeDef",
     "RegistrationConfigTypeDef",
     "DescribeCertificateRequestRequestTypeDef",
     "DescribeCustomMetricRequestRequestTypeDef",
+    "DescribeCustomMetricResponseTypeDef",
     "DescribeDetectMitigationActionsTaskRequestRequestTypeDef",
     "DescribeDimensionRequestRequestTypeDef",
+    "DescribeDimensionResponseTypeDef",
     "DescribeDomainConfigurationRequestRequestTypeDef",
     "ServerCertificateSummaryTypeDef",
     "DescribeEndpointRequestRequestTypeDef",
+    "DescribeEndpointResponseTypeDef",
     "DescribeFleetMetricRequestRequestTypeDef",
     "DescribeIndexRequestRequestTypeDef",
+    "DescribeIndexResponseTypeDef",
     "DescribeJobExecutionRequestRequestTypeDef",
     "DescribeJobRequestRequestTypeDef",
     "DescribeJobTemplateRequestRequestTypeDef",
     "DescribeManagedJobTemplateRequestRequestTypeDef",
     "DocumentParameterTypeDef",
     "DescribeMitigationActionRequestRequestTypeDef",
     "DescribeProvisioningTemplateRequestRequestTypeDef",
     "DescribeProvisioningTemplateVersionRequestRequestTypeDef",
+    "DescribeProvisioningTemplateVersionResponseTypeDef",
     "DescribeRoleAliasRequestRequestTypeDef",
     "RoleAliasDescriptionTypeDef",
     "DescribeScheduledAuditRequestRequestTypeDef",
+    "DescribeScheduledAuditResponseTypeDef",
     "DescribeSecurityProfileRequestRequestTypeDef",
     "DescribeStreamRequestRequestTypeDef",
     "DescribeThingGroupRequestRequestTypeDef",
     "DescribeThingRegistrationTaskRequestRequestTypeDef",
+    "DescribeThingRegistrationTaskResponseTypeDef",
     "DescribeThingRequestRequestTypeDef",
+    "DescribeThingResponseTypeDef",
     "DescribeThingTypeRequestRequestTypeDef",
     "ThingTypeMetadataTypeDef",
     "S3DestinationTypeDef",
     "DetachPolicyRequestRequestTypeDef",
     "DetachPrincipalPolicyRequestRequestTypeDef",
     "DetachSecurityProfileRequestRequestTypeDef",
     "DetachThingPrincipalRequestRequestTypeDef",
@@ -250,36 +291,49 @@
     "DetectMitigationActionsTaskStatisticsTypeDef",
     "DetectMitigationActionsTaskTargetTypeDef",
     "ViolationEventOccurrenceRangeTypeDef",
     "DisableTopicRuleRequestRequestTypeDef",
     "DomainConfigurationSummaryTypeDef",
     "PutItemInputTypeDef",
     "EffectivePolicyTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableIoTLoggingParamsTypeDef",
     "EnableTopicRuleRequestRequestTypeDef",
     "ErrorInfoTypeDef",
     "RateIncreaseCriteriaTypeDef",
     "FieldTypeDef",
     "S3LocationTypeDef",
     "StreamTypeDef",
     "FleetMetricNameAndArnTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef",
     "GetBehaviorModelTrainingSummariesRequestRequestTypeDef",
     "GetCardinalityRequestRequestTypeDef",
+    "GetCardinalityResponseTypeDef",
     "GetEffectivePoliciesRequestRequestTypeDef",
     "GetJobDocumentRequestRequestTypeDef",
+    "GetJobDocumentResponseTypeDef",
+    "GetLoggingOptionsResponseTypeDef",
     "GetOTAUpdateRequestRequestTypeDef",
+    "VersionUpdateByJobsConfigTypeDef",
+    "GetPackageRequestRequestTypeDef",
+    "GetPackageResponseTypeDef",
+    "GetPackageVersionRequestRequestTypeDef",
+    "GetPackageVersionResponseTypeDef",
     "GetPercentilesRequestRequestTypeDef",
     "PercentPairTypeDef",
     "GetPolicyRequestRequestTypeDef",
+    "GetPolicyResponseTypeDef",
     "GetPolicyVersionRequestRequestTypeDef",
+    "GetPolicyVersionResponseTypeDef",
+    "GetRegistrationCodeResponseTypeDef",
     "GetStatisticsRequestRequestTypeDef",
     "StatisticsTypeDef",
     "GetTopicRuleDestinationRequestRequestTypeDef",
     "GetTopicRuleRequestRequestTypeDef",
+    "GetV2LoggingOptionsResponseTypeDef",
     "GroupNameAndArnTypeDef",
     "HttpActionHeaderTypeDef",
     "SigV4AuthorizationTypeDef",
     "HttpContextTypeDef",
     "HttpUrlDestinationConfigurationTypeDef",
     "HttpUrlDestinationPropertiesTypeDef",
     "HttpUrlDestinationSummaryTypeDef",
@@ -287,223 +341,246 @@
     "IssuerCertificateIdentifierTypeDef",
     "JobExecutionStatusDetailsTypeDef",
     "JobExecutionSummaryTypeDef",
     "RetryCriteriaTypeDef",
     "JobProcessDetailsTypeDef",
     "JobSummaryTypeDef",
     "JobTemplateSummaryTypeDef",
+    "ScheduledJobRolloutTypeDef",
+    "ListActiveViolationsRequestListActiveViolationsPaginateTypeDef",
     "ListActiveViolationsRequestRequestTypeDef",
+    "ListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef",
     "ListAttachedPoliciesRequestRequestTypeDef",
+    "ListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef",
     "ListAuditMitigationActionsExecutionsRequestRequestTypeDef",
+    "ListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef",
     "ListAuditMitigationActionsTasksRequestRequestTypeDef",
+    "ListAuditTasksRequestListAuditTasksPaginateTypeDef",
     "ListAuditTasksRequestRequestTypeDef",
+    "ListAuthorizersRequestListAuthorizersPaginateTypeDef",
     "ListAuthorizersRequestRequestTypeDef",
+    "ListBillingGroupsRequestListBillingGroupsPaginateTypeDef",
     "ListBillingGroupsRequestRequestTypeDef",
+    "ListCACertificatesRequestListCACertificatesPaginateTypeDef",
     "ListCACertificatesRequestRequestTypeDef",
+    "ListCertificatesByCARequestListCertificatesByCAPaginateTypeDef",
     "ListCertificatesByCARequestRequestTypeDef",
+    "ListCertificatesRequestListCertificatesPaginateTypeDef",
     "ListCertificatesRequestRequestTypeDef",
+    "ListCustomMetricsRequestListCustomMetricsPaginateTypeDef",
     "ListCustomMetricsRequestRequestTypeDef",
+    "ListCustomMetricsResponseTypeDef",
+    "ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef",
     "ListDetectMitigationActionsExecutionsRequestRequestTypeDef",
+    "ListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef",
     "ListDetectMitigationActionsTasksRequestRequestTypeDef",
+    "ListDimensionsRequestListDimensionsPaginateTypeDef",
     "ListDimensionsRequestRequestTypeDef",
+    "ListDimensionsResponseTypeDef",
+    "ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef",
     "ListDomainConfigurationsRequestRequestTypeDef",
+    "ListFleetMetricsRequestListFleetMetricsPaginateTypeDef",
     "ListFleetMetricsRequestRequestTypeDef",
+    "ListIndicesRequestListIndicesPaginateTypeDef",
     "ListIndicesRequestRequestTypeDef",
+    "ListIndicesResponseTypeDef",
+    "ListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef",
     "ListJobExecutionsForJobRequestRequestTypeDef",
+    "ListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef",
     "ListJobExecutionsForThingRequestRequestTypeDef",
+    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
     "ListJobTemplatesRequestRequestTypeDef",
+    "ListJobsRequestListJobsPaginateTypeDef",
     "ListJobsRequestRequestTypeDef",
+    "ListManagedJobTemplatesRequestListManagedJobTemplatesPaginateTypeDef",
     "ListManagedJobTemplatesRequestRequestTypeDef",
     "ManagedJobTemplateSummaryTypeDef",
+    "ListMetricValuesRequestListMetricValuesPaginateTypeDef",
     "ListMetricValuesRequestRequestTypeDef",
+    "ListMitigationActionsRequestListMitigationActionsPaginateTypeDef",
     "ListMitigationActionsRequestRequestTypeDef",
     "MitigationActionIdentifierTypeDef",
+    "ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef",
     "ListOTAUpdatesRequestRequestTypeDef",
     "OTAUpdateSummaryTypeDef",
+    "ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef",
     "ListOutgoingCertificatesRequestRequestTypeDef",
     "OutgoingCertificateTypeDef",
+    "ListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
+    "ListPackageVersionsRequestRequestTypeDef",
+    "PackageVersionSummaryTypeDef",
+    "ListPackagesRequestListPackagesPaginateTypeDef",
+    "ListPackagesRequestRequestTypeDef",
+    "PackageSummaryTypeDef",
+    "ListPoliciesRequestListPoliciesPaginateTypeDef",
     "ListPoliciesRequestRequestTypeDef",
+    "ListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef",
     "ListPolicyPrincipalsRequestRequestTypeDef",
+    "ListPolicyPrincipalsResponseTypeDef",
     "ListPolicyVersionsRequestRequestTypeDef",
     "PolicyVersionTypeDef",
+    "ListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef",
     "ListPrincipalPoliciesRequestRequestTypeDef",
+    "ListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef",
     "ListPrincipalThingsRequestRequestTypeDef",
+    "ListPrincipalThingsResponseTypeDef",
+    "ListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef",
     "ListProvisioningTemplateVersionsRequestRequestTypeDef",
     "ProvisioningTemplateVersionSummaryTypeDef",
+    "ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef",
     "ListProvisioningTemplatesRequestRequestTypeDef",
     "ProvisioningTemplateSummaryTypeDef",
+    "ListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef",
     "ListRelatedResourcesForAuditFindingRequestRequestTypeDef",
+    "ListRoleAliasesRequestListRoleAliasesPaginateTypeDef",
     "ListRoleAliasesRequestRequestTypeDef",
+    "ListRoleAliasesResponseTypeDef",
+    "ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef",
     "ListScheduledAuditsRequestRequestTypeDef",
     "ScheduledAuditMetadataTypeDef",
+    "ListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef",
     "ListSecurityProfilesForTargetRequestRequestTypeDef",
+    "ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef",
     "ListSecurityProfilesRequestRequestTypeDef",
     "SecurityProfileIdentifierTypeDef",
+    "ListStreamsRequestListStreamsPaginateTypeDef",
     "ListStreamsRequestRequestTypeDef",
     "StreamSummaryTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
     "ListTargetsForPolicyRequestRequestTypeDef",
+    "ListTargetsForPolicyResponseTypeDef",
+    "ListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef",
     "ListTargetsForSecurityProfileRequestRequestTypeDef",
     "SecurityProfileTargetTypeDef",
+    "ListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef",
     "ListThingGroupsForThingRequestRequestTypeDef",
+    "ListThingGroupsRequestListThingGroupsPaginateTypeDef",
     "ListThingGroupsRequestRequestTypeDef",
+    "ListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef",
     "ListThingPrincipalsRequestRequestTypeDef",
+    "ListThingPrincipalsResponseTypeDef",
+    "ListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef",
     "ListThingRegistrationTaskReportsRequestRequestTypeDef",
+    "ListThingRegistrationTaskReportsResponseTypeDef",
+    "ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef",
     "ListThingRegistrationTasksRequestRequestTypeDef",
+    "ListThingRegistrationTasksResponseTypeDef",
+    "ListThingTypesRequestListThingTypesPaginateTypeDef",
     "ListThingTypesRequestRequestTypeDef",
+    "ListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef",
     "ListThingsInBillingGroupRequestRequestTypeDef",
+    "ListThingsInBillingGroupResponseTypeDef",
+    "ListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef",
     "ListThingsInThingGroupRequestRequestTypeDef",
+    "ListThingsInThingGroupResponseTypeDef",
+    "ListThingsRequestListThingsPaginateTypeDef",
     "ListThingsRequestRequestTypeDef",
     "ThingAttributeTypeDef",
+    "ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef",
     "ListTopicRuleDestinationsRequestRequestTypeDef",
+    "ListTopicRulesRequestListTopicRulesPaginateTypeDef",
     "ListTopicRulesRequestRequestTypeDef",
     "TopicRuleListItemTypeDef",
+    "ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef",
     "ListV2LoggingLevelsRequestRequestTypeDef",
+    "ListViolationEventsRequestListViolationEventsPaginateTypeDef",
     "ListViolationEventsRequestRequestTypeDef",
     "LocationTimestampTypeDef",
     "LogTargetTypeDef",
     "LoggingOptionsPayloadTypeDef",
     "PublishFindingToSnsParamsTypeDef",
     "ReplaceDefaultPolicyVersionParamsTypeDef",
     "UpdateCACertificateParamsTypeDef",
     "UpdateDeviceCertificateParamsTypeDef",
     "MqttContextTypeDef",
     "UserPropertyTypeDef",
+    "PaginatorConfigTypeDef",
     "PolicyVersionIdentifierTypeDef",
     "PutVerificationStateOnViolationRequestRequestTypeDef",
+    "RegisterCACertificateResponseTypeDef",
     "RegisterCertificateRequestRequestTypeDef",
+    "RegisterCertificateResponseTypeDef",
     "RegisterCertificateWithoutCARequestRequestTypeDef",
+    "RegisterCertificateWithoutCAResponseTypeDef",
     "RegisterThingRequestRequestTypeDef",
+    "RegisterThingResponseTypeDef",
     "RejectCertificateTransferRequestRequestTypeDef",
     "RemoveThingFromBillingGroupRequestRequestTypeDef",
     "RemoveThingFromThingGroupRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "SearchIndexRequestRequestTypeDef",
     "ThingGroupDocumentTypeDef",
     "SetDefaultAuthorizerRequestRequestTypeDef",
+    "SetDefaultAuthorizerResponseTypeDef",
     "SetDefaultPolicyVersionRequestRequestTypeDef",
     "SetV2LoggingOptionsRequestRequestTypeDef",
     "SigningProfileParameterTypeDef",
+    "StartAuditMitigationActionsTaskResponseTypeDef",
+    "StartDetectMitigationActionsTaskResponseTypeDef",
     "StartOnDemandAuditTaskRequestRequestTypeDef",
+    "StartOnDemandAuditTaskResponseTypeDef",
     "StartThingRegistrationTaskRequestRequestTypeDef",
+    "StartThingRegistrationTaskResponseTypeDef",
     "StopThingRegistrationTaskRequestRequestTypeDef",
     "TlsContextTypeDef",
+    "TestInvokeAuthorizerResponseTypeDef",
     "ThingConnectivityTypeDef",
     "TimestreamDimensionTypeDef",
     "TimestreamTimestampTypeDef",
     "VpcDestinationConfigurationTypeDef",
     "VpcDestinationSummaryTypeDef",
     "VpcDestinationPropertiesTypeDef",
     "TransferCertificateRequestRequestTypeDef",
+    "TransferCertificateResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAuthorizerRequestRequestTypeDef",
+    "UpdateAuthorizerResponseTypeDef",
+    "UpdateBillingGroupResponseTypeDef",
     "UpdateCertificateRequestRequestTypeDef",
     "UpdateCustomMetricRequestRequestTypeDef",
+    "UpdateCustomMetricResponseTypeDef",
     "UpdateDimensionRequestRequestTypeDef",
+    "UpdateDimensionResponseTypeDef",
+    "UpdateDomainConfigurationResponseTypeDef",
+    "UpdateDynamicThingGroupResponseTypeDef",
+    "UpdateMitigationActionResponseTypeDef",
+    "UpdatePackageRequestRequestTypeDef",
+    "UpdatePackageVersionRequestRequestTypeDef",
     "UpdateRoleAliasRequestRequestTypeDef",
+    "UpdateRoleAliasResponseTypeDef",
     "UpdateScheduledAuditRequestRequestTypeDef",
+    "UpdateScheduledAuditResponseTypeDef",
+    "UpdateStreamResponseTypeDef",
+    "UpdateThingGroupResponseTypeDef",
     "UpdateThingGroupsForThingRequestRequestTypeDef",
     "UpdateTopicRuleDestinationRequestRequestTypeDef",
     "ValidationErrorTypeDef",
     "AbortConfigTypeDef",
     "MetricDatumTypeDef",
+    "DescribeFleetMetricResponseTypeDef",
     "UpdateFleetMetricRequestRequestTypeDef",
     "AllowedTypeDef",
     "ExplicitDenyTypeDef",
     "ImplicitDenyTypeDef",
-    "AssetPropertyValueTypeDef",
-    "AssociateTargetsWithJobResponseTypeDef",
-    "CancelJobResponseTypeDef",
-    "CreateAuthorizerResponseTypeDef",
-    "CreateBillingGroupResponseTypeDef",
-    "CreateCertificateFromCsrResponseTypeDef",
-    "CreateCustomMetricResponseTypeDef",
-    "CreateDimensionResponseTypeDef",
-    "CreateDomainConfigurationResponseTypeDef",
-    "CreateDynamicThingGroupResponseTypeDef",
-    "CreateFleetMetricResponseTypeDef",
-    "CreateJobResponseTypeDef",
-    "CreateJobTemplateResponseTypeDef",
-    "CreateMitigationActionResponseTypeDef",
-    "CreateOTAUpdateResponseTypeDef",
-    "CreatePolicyResponseTypeDef",
-    "CreatePolicyVersionResponseTypeDef",
-    "CreateProvisioningTemplateResponseTypeDef",
-    "CreateProvisioningTemplateVersionResponseTypeDef",
-    "CreateRoleAliasResponseTypeDef",
-    "CreateScheduledAuditResponseTypeDef",
-    "CreateSecurityProfileResponseTypeDef",
-    "CreateStreamResponseTypeDef",
-    "CreateThingGroupResponseTypeDef",
-    "CreateThingResponseTypeDef",
-    "CreateThingTypeResponseTypeDef",
-    "DescribeCustomMetricResponseTypeDef",
-    "DescribeDimensionResponseTypeDef",
-    "DescribeEndpointResponseTypeDef",
-    "DescribeFleetMetricResponseTypeDef",
-    "DescribeIndexResponseTypeDef",
-    "DescribeProvisioningTemplateVersionResponseTypeDef",
-    "DescribeScheduledAuditResponseTypeDef",
-    "DescribeThingRegistrationTaskResponseTypeDef",
-    "DescribeThingResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetCardinalityResponseTypeDef",
-    "GetJobDocumentResponseTypeDef",
-    "GetLoggingOptionsResponseTypeDef",
-    "GetPolicyResponseTypeDef",
-    "GetPolicyVersionResponseTypeDef",
-    "GetRegistrationCodeResponseTypeDef",
-    "GetV2LoggingOptionsResponseTypeDef",
     "ListAttachedPoliciesResponseTypeDef",
-    "ListCustomMetricsResponseTypeDef",
-    "ListDimensionsResponseTypeDef",
-    "ListIndicesResponseTypeDef",
     "ListPoliciesResponseTypeDef",
-    "ListPolicyPrincipalsResponseTypeDef",
     "ListPrincipalPoliciesResponseTypeDef",
-    "ListPrincipalThingsResponseTypeDef",
-    "ListRoleAliasesResponseTypeDef",
-    "ListTargetsForPolicyResponseTypeDef",
-    "ListThingPrincipalsResponseTypeDef",
-    "ListThingRegistrationTaskReportsResponseTypeDef",
-    "ListThingRegistrationTasksResponseTypeDef",
-    "ListThingsInBillingGroupResponseTypeDef",
-    "ListThingsInThingGroupResponseTypeDef",
-    "RegisterCACertificateResponseTypeDef",
-    "RegisterCertificateResponseTypeDef",
-    "RegisterCertificateWithoutCAResponseTypeDef",
-    "RegisterThingResponseTypeDef",
-    "SetDefaultAuthorizerResponseTypeDef",
-    "StartAuditMitigationActionsTaskResponseTypeDef",
-    "StartDetectMitigationActionsTaskResponseTypeDef",
-    "StartOnDemandAuditTaskResponseTypeDef",
-    "StartThingRegistrationTaskResponseTypeDef",
-    "TestInvokeAuthorizerResponseTypeDef",
-    "TransferCertificateResponseTypeDef",
-    "UpdateAuthorizerResponseTypeDef",
-    "UpdateBillingGroupResponseTypeDef",
-    "UpdateCustomMetricResponseTypeDef",
-    "UpdateDimensionResponseTypeDef",
-    "UpdateDomainConfigurationResponseTypeDef",
-    "UpdateDynamicThingGroupResponseTypeDef",
-    "UpdateMitigationActionResponseTypeDef",
-    "UpdateRoleAliasResponseTypeDef",
-    "UpdateScheduledAuditResponseTypeDef",
-    "UpdateStreamResponseTypeDef",
-    "UpdateThingGroupResponseTypeDef",
+    "AssetPropertyValueTypeDef",
     "CreateThingRequestRequestTypeDef",
     "ThingGroupPropertiesTypeDef",
     "UpdateThingRequestRequestTypeDef",
     "ListAuditMitigationActionsExecutionsResponseTypeDef",
     "ListAuditMitigationActionsTasksResponseTypeDef",
     "StartAuditMitigationActionsTaskRequestRequestTypeDef",
     "DescribeAccountAuditConfigurationResponseTypeDef",
     "UpdateAccountAuditConfigurationRequestRequestTypeDef",
     "ListAuditTasksResponseTypeDef",
     "TestAuthorizationRequestRequestTypeDef",
-    "UpdateDomainConfigurationRequestRequestTypeDef",
     "DescribeAuthorizerResponseTypeDef",
     "DescribeDefaultAuthorizerResponseTypeDef",
     "ListAuthorizersResponseTypeDef",
     "AwsJobAbortConfigTypeDef",
     "AwsJobExponentialRolloutRateTypeDef",
     "BehaviorCriteriaTypeDef",
     "GetBehaviorModelTrainingSummariesResponseTypeDef",
@@ -520,21 +597,23 @@
     "CustomCodeSigningTypeDef",
     "DescribeEventConfigurationsResponseTypeDef",
     "UpdateEventConfigurationsRequestRequestTypeDef",
     "CreateAuthorizerRequestRequestTypeDef",
     "CreateBillingGroupRequestRequestTypeDef",
     "CreateCustomMetricRequestRequestTypeDef",
     "CreateDimensionRequestRequestTypeDef",
-    "CreateDomainConfigurationRequestRequestTypeDef",
     "CreateFleetMetricRequestRequestTypeDef",
     "CreatePolicyRequestRequestTypeDef",
     "CreateRoleAliasRequestRequestTypeDef",
     "CreateScheduledAuditRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "CreateDomainConfigurationRequestRequestTypeDef",
+    "UpdateDomainConfigurationRequestRequestTypeDef",
+    "SchedulingConfigTypeDef",
     "CreateKeysAndCertificateResponseTypeDef",
     "CreateProvisioningClaimResponseTypeDef",
     "CreateProvisioningTemplateRequestRequestTypeDef",
     "DescribeProvisioningTemplateResponseTypeDef",
     "UpdateProvisioningTemplateRequestRequestTypeDef",
     "CreateThingTypeRequestRequestTypeDef",
     "DescribeAuditTaskResponseTypeDef",
@@ -552,67 +631,16 @@
     "DynamoDBv2ActionTypeDef",
     "GetEffectivePoliciesResponseTypeDef",
     "ExponentialRolloutRateTypeDef",
     "ThingGroupIndexingConfigurationTypeDef",
     "StreamFileTypeDef",
     "FileLocationTypeDef",
     "ListFleetMetricsResponseTypeDef",
-    "GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef",
-    "ListActiveViolationsRequestListActiveViolationsPaginateTypeDef",
-    "ListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef",
-    "ListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef",
-    "ListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef",
-    "ListAuditTasksRequestListAuditTasksPaginateTypeDef",
-    "ListAuthorizersRequestListAuthorizersPaginateTypeDef",
-    "ListBillingGroupsRequestListBillingGroupsPaginateTypeDef",
-    "ListCACertificatesRequestListCACertificatesPaginateTypeDef",
-    "ListCertificatesByCARequestListCertificatesByCAPaginateTypeDef",
-    "ListCertificatesRequestListCertificatesPaginateTypeDef",
-    "ListCustomMetricsRequestListCustomMetricsPaginateTypeDef",
-    "ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef",
-    "ListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef",
-    "ListDimensionsRequestListDimensionsPaginateTypeDef",
-    "ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef",
-    "ListFleetMetricsRequestListFleetMetricsPaginateTypeDef",
-    "ListIndicesRequestListIndicesPaginateTypeDef",
-    "ListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef",
-    "ListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef",
-    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
-    "ListJobsRequestListJobsPaginateTypeDef",
-    "ListMetricValuesRequestListMetricValuesPaginateTypeDef",
-    "ListMitigationActionsRequestListMitigationActionsPaginateTypeDef",
-    "ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef",
-    "ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef",
-    "ListPoliciesRequestListPoliciesPaginateTypeDef",
-    "ListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef",
-    "ListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef",
-    "ListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef",
-    "ListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef",
-    "ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef",
-    "ListRoleAliasesRequestListRoleAliasesPaginateTypeDef",
-    "ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef",
-    "ListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef",
-    "ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef",
-    "ListStreamsRequestListStreamsPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    "ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
-    "ListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef",
-    "ListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef",
-    "ListThingGroupsRequestListThingGroupsPaginateTypeDef",
-    "ListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef",
-    "ListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef",
-    "ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef",
-    "ListThingTypesRequestListThingTypesPaginateTypeDef",
-    "ListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef",
-    "ListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef",
-    "ListThingsRequestListThingsPaginateTypeDef",
-    "ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef",
-    "ListTopicRulesRequestListTopicRulesPaginateTypeDef",
-    "ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef",
-    "ListViolationEventsRequestListViolationEventsPaginateTypeDef",
+    "GetPackageConfigurationResponseTypeDef",
+    "UpdatePackageConfigurationRequestRequestTypeDef",
     "GetPercentilesResponseTypeDef",
     "GetStatisticsResponseTypeDef",
     "ListBillingGroupsResponseTypeDef",
     "ListThingGroupsForThingResponseTypeDef",
     "ListThingGroupsResponseTypeDef",
     "ThingGroupMetadataTypeDef",
     "HttpAuthorizationTypeDef",
@@ -623,14 +651,16 @@
     "JobExecutionsRetryConfigTypeDef",
     "ListJobsResponseTypeDef",
     "ListJobTemplatesResponseTypeDef",
     "ListManagedJobTemplatesResponseTypeDef",
     "ListMitigationActionsResponseTypeDef",
     "ListOTAUpdatesResponseTypeDef",
     "ListOutgoingCertificatesResponseTypeDef",
+    "ListPackageVersionsResponseTypeDef",
+    "ListPackagesResponseTypeDef",
     "ListPolicyVersionsResponseTypeDef",
     "ListProvisioningTemplateVersionsResponseTypeDef",
     "ListProvisioningTemplatesResponseTypeDef",
     "ListScheduledAuditsResponseTypeDef",
     "ListSecurityProfilesResponseTypeDef",
     "ListStreamsResponseTypeDef",
     "ListTargetsForSecurityProfileResponseTypeDef",
@@ -1193,22 +1223,21 @@
 
 class AssociateTargetsWithJobRequestRequestTypeDef(
     _RequiredAssociateTargetsWithJobRequestRequestTypeDef,
     _OptionalAssociateTargetsWithJobRequestRequestTypeDef,
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateTargetsWithJobResponseTypeDef = TypedDict(
+    "AssociateTargetsWithJobResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "jobArn": str,
+        "jobId": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachPolicyRequestRequestTypeDef = TypedDict(
     "AttachPolicyRequestRequestTypeDef",
     {
         "policyName": str,
@@ -1580,14 +1609,24 @@
 )
 
 class CancelJobRequestRequestTypeDef(
     _RequiredCancelJobRequestRequestTypeDef, _OptionalCancelJobRequestRequestTypeDef
 ):
     pass
 
+CancelJobResponseTypeDef = TypedDict(
+    "CancelJobResponseTypeDef",
+    {
+        "jobArn": str,
+        "jobId": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TransferDataTypeDef = TypedDict(
     "TransferDataTypeDef",
     {
         "transferMessage": str,
         "rejectReason": str,
         "transferDate": datetime,
         "acceptDate": datetime,
@@ -1653,14 +1692,33 @@
     },
     total=False,
 )
 
 class TagTypeDef(_RequiredTagTypeDef, _OptionalTagTypeDef):
     pass
 
+CreateAuthorizerResponseTypeDef = TypedDict(
+    "CreateAuthorizerResponseTypeDef",
+    {
+        "authorizerName": str,
+        "authorizerArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateBillingGroupResponseTypeDef = TypedDict(
+    "CreateBillingGroupResponseTypeDef",
+    {
+        "billingGroupName": str,
+        "billingGroupArn": str,
+        "billingGroupId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateCertificateFromCsrRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCertificateFromCsrRequestRequestTypeDef",
     {
         "certificateSigningRequest": str,
     },
 )
 _OptionalCreateCertificateFromCsrRequestRequestTypeDef = TypedDict(
@@ -1673,41 +1731,125 @@
 
 class CreateCertificateFromCsrRequestRequestTypeDef(
     _RequiredCreateCertificateFromCsrRequestRequestTypeDef,
     _OptionalCreateCertificateFromCsrRequestRequestTypeDef,
 ):
     pass
 
-PresignedUrlConfigTypeDef = TypedDict(
-    "PresignedUrlConfigTypeDef",
+CreateCertificateFromCsrResponseTypeDef = TypedDict(
+    "CreateCertificateFromCsrResponseTypeDef",
     {
-        "roleArn": str,
-        "expiresInSec": int,
+        "certificateArn": str,
+        "certificateId": str,
+        "certificatePem": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateCustomMetricResponseTypeDef = TypedDict(
+    "CreateCustomMetricResponseTypeDef",
+    {
+        "metricName": str,
+        "metricArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDimensionResponseTypeDef = TypedDict(
+    "CreateDimensionResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TlsConfigTypeDef = TypedDict(
+    "TlsConfigTypeDef",
+    {
+        "securityPolicy": str,
     },
     total=False,
 )
 
-SchedulingConfigTypeDef = TypedDict(
-    "SchedulingConfigTypeDef",
+CreateDomainConfigurationResponseTypeDef = TypedDict(
+    "CreateDomainConfigurationResponseTypeDef",
     {
-        "startTime": str,
-        "endTime": str,
-        "endBehavior": JobEndBehaviorType,
+        "domainConfigurationName": str,
+        "domainConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDynamicThingGroupResponseTypeDef = TypedDict(
+    "CreateDynamicThingGroupResponseTypeDef",
+    {
+        "thingGroupName": str,
+        "thingGroupArn": str,
+        "thingGroupId": str,
+        "indexName": str,
+        "queryString": str,
+        "queryVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFleetMetricResponseTypeDef = TypedDict(
+    "CreateFleetMetricResponseTypeDef",
+    {
+        "metricName": str,
+        "metricArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PresignedUrlConfigTypeDef = TypedDict(
+    "PresignedUrlConfigTypeDef",
+    {
+        "roleArn": str,
+        "expiresInSec": int,
     },
     total=False,
 )
 
 TimeoutConfigTypeDef = TypedDict(
     "TimeoutConfigTypeDef",
     {
         "inProgressTimeoutInMinutes": int,
     },
     total=False,
 )
 
+CreateJobResponseTypeDef = TypedDict(
+    "CreateJobResponseTypeDef",
+    {
+        "jobArn": str,
+        "jobId": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+MaintenanceWindowTypeDef = TypedDict(
+    "MaintenanceWindowTypeDef",
+    {
+        "startTime": str,
+        "durationInMinutes": int,
+    },
+)
+
+CreateJobTemplateResponseTypeDef = TypedDict(
+    "CreateJobTemplateResponseTypeDef",
+    {
+        "jobTemplateArn": str,
+        "jobTemplateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateKeysAndCertificateRequestRequestTypeDef = TypedDict(
     "CreateKeysAndCertificateRequestRequestTypeDef",
     {
         "setAsActive": bool,
     },
     total=False,
 )
@@ -1717,14 +1859,115 @@
     {
         "PublicKey": str,
         "PrivateKey": str,
     },
     total=False,
 )
 
+CreateMitigationActionResponseTypeDef = TypedDict(
+    "CreateMitigationActionResponseTypeDef",
+    {
+        "actionArn": str,
+        "actionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateOTAUpdateResponseTypeDef = TypedDict(
+    "CreateOTAUpdateResponseTypeDef",
+    {
+        "otaUpdateId": str,
+        "awsIotJobId": str,
+        "otaUpdateArn": str,
+        "awsIotJobArn": str,
+        "otaUpdateStatus": OTAUpdateStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreatePackageRequestRequestTypeDef = TypedDict(
+    "_RequiredCreatePackageRequestRequestTypeDef",
+    {
+        "packageName": str,
+    },
+)
+_OptionalCreatePackageRequestRequestTypeDef = TypedDict(
+    "_OptionalCreatePackageRequestRequestTypeDef",
+    {
+        "description": str,
+        "tags": Mapping[str, str],
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class CreatePackageRequestRequestTypeDef(
+    _RequiredCreatePackageRequestRequestTypeDef, _OptionalCreatePackageRequestRequestTypeDef
+):
+    pass
+
+CreatePackageResponseTypeDef = TypedDict(
+    "CreatePackageResponseTypeDef",
+    {
+        "packageName": str,
+        "packageArn": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreatePackageVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreatePackageVersionRequestRequestTypeDef",
+    {
+        "packageName": str,
+        "versionName": str,
+    },
+)
+_OptionalCreatePackageVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreatePackageVersionRequestRequestTypeDef",
+    {
+        "description": str,
+        "attributes": Mapping[str, str],
+        "tags": Mapping[str, str],
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class CreatePackageVersionRequestRequestTypeDef(
+    _RequiredCreatePackageVersionRequestRequestTypeDef,
+    _OptionalCreatePackageVersionRequestRequestTypeDef,
+):
+    pass
+
+CreatePackageVersionResponseTypeDef = TypedDict(
+    "CreatePackageVersionResponseTypeDef",
+    {
+        "packageVersionArn": str,
+        "packageName": str,
+        "versionName": str,
+        "description": str,
+        "attributes": Dict[str, str],
+        "status": PackageVersionStatusType,
+        "errorReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePolicyResponseTypeDef = TypedDict(
+    "CreatePolicyResponseTypeDef",
+    {
+        "policyName": str,
+        "policyArn": str,
+        "policyDocument": str,
+        "policyVersionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreatePolicyVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePolicyVersionRequestRequestTypeDef",
     {
         "policyName": str,
         "policyDocument": str,
     },
 )
@@ -1738,14 +1981,25 @@
 
 class CreatePolicyVersionRequestRequestTypeDef(
     _RequiredCreatePolicyVersionRequestRequestTypeDef,
     _OptionalCreatePolicyVersionRequestRequestTypeDef,
 ):
     pass
 
+CreatePolicyVersionResponseTypeDef = TypedDict(
+    "CreatePolicyVersionResponseTypeDef",
+    {
+        "policyArn": str,
+        "policyDocument": str,
+        "policyVersionId": str,
+        "isDefaultVersion": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateProvisioningClaimRequestRequestTypeDef = TypedDict(
     "CreateProvisioningClaimRequestRequestTypeDef",
     {
         "templateName": str,
     },
 )
 
@@ -1762,14 +2016,24 @@
     },
     total=False,
 )
 
 class ProvisioningHookTypeDef(_RequiredProvisioningHookTypeDef, _OptionalProvisioningHookTypeDef):
     pass
 
+CreateProvisioningTemplateResponseTypeDef = TypedDict(
+    "CreateProvisioningTemplateResponseTypeDef",
+    {
+        "templateArn": str,
+        "templateName": str,
+        "defaultVersionId": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateProvisioningTemplateVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateProvisioningTemplateVersionRequestRequestTypeDef",
     {
         "templateName": str,
         "templateBody": str,
     },
 )
@@ -1783,23 +2047,101 @@
 
 class CreateProvisioningTemplateVersionRequestRequestTypeDef(
     _RequiredCreateProvisioningTemplateVersionRequestRequestTypeDef,
     _OptionalCreateProvisioningTemplateVersionRequestRequestTypeDef,
 ):
     pass
 
+CreateProvisioningTemplateVersionResponseTypeDef = TypedDict(
+    "CreateProvisioningTemplateVersionResponseTypeDef",
+    {
+        "templateArn": str,
+        "templateName": str,
+        "versionId": int,
+        "isDefaultVersion": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateRoleAliasResponseTypeDef = TypedDict(
+    "CreateRoleAliasResponseTypeDef",
+    {
+        "roleAlias": str,
+        "roleAliasArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateScheduledAuditResponseTypeDef = TypedDict(
+    "CreateScheduledAuditResponseTypeDef",
+    {
+        "scheduledAuditArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateSecurityProfileResponseTypeDef = TypedDict(
+    "CreateSecurityProfileResponseTypeDef",
+    {
+        "securityProfileName": str,
+        "securityProfileArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateStreamResponseTypeDef = TypedDict(
+    "CreateStreamResponseTypeDef",
+    {
+        "streamId": str,
+        "streamArn": str,
+        "description": str,
+        "streamVersion": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateThingGroupResponseTypeDef = TypedDict(
+    "CreateThingGroupResponseTypeDef",
+    {
+        "thingGroupName": str,
+        "thingGroupArn": str,
+        "thingGroupId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateThingResponseTypeDef = TypedDict(
+    "CreateThingResponseTypeDef",
+    {
+        "thingName": str,
+        "thingArn": str,
+        "thingId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ThingTypePropertiesTypeDef = TypedDict(
     "ThingTypePropertiesTypeDef",
     {
         "thingTypeDescription": str,
         "searchableAttributes": Sequence[str],
     },
     total=False,
 )
 
+CreateThingTypeResponseTypeDef = TypedDict(
+    "CreateThingTypeResponseTypeDef",
+    {
+        "thingTypeName": str,
+        "thingTypeArn": str,
+        "thingTypeId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteAccountAuditConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteAccountAuditConfigurationRequestRequestTypeDef",
     {
         "deleteScheduledAudits": bool,
     },
     total=False,
 )
@@ -1990,14 +2332,54 @@
 )
 
 class DeleteOTAUpdateRequestRequestTypeDef(
     _RequiredDeleteOTAUpdateRequestRequestTypeDef, _OptionalDeleteOTAUpdateRequestRequestTypeDef
 ):
     pass
 
+_RequiredDeletePackageRequestRequestTypeDef = TypedDict(
+    "_RequiredDeletePackageRequestRequestTypeDef",
+    {
+        "packageName": str,
+    },
+)
+_OptionalDeletePackageRequestRequestTypeDef = TypedDict(
+    "_OptionalDeletePackageRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class DeletePackageRequestRequestTypeDef(
+    _RequiredDeletePackageRequestRequestTypeDef, _OptionalDeletePackageRequestRequestTypeDef
+):
+    pass
+
+_RequiredDeletePackageVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredDeletePackageVersionRequestRequestTypeDef",
+    {
+        "packageName": str,
+        "versionName": str,
+    },
+)
+_OptionalDeletePackageVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalDeletePackageVersionRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class DeletePackageVersionRequestRequestTypeDef(
+    _RequiredDeletePackageVersionRequestRequestTypeDef,
+    _OptionalDeletePackageVersionRequestRequestTypeDef,
+):
+    pass
+
 DeletePolicyRequestRequestTypeDef = TypedDict(
     "DeletePolicyRequestRequestTypeDef",
     {
         "policyName": str,
     },
 )
 
@@ -2240,28 +2622,54 @@
 DescribeCustomMetricRequestRequestTypeDef = TypedDict(
     "DescribeCustomMetricRequestRequestTypeDef",
     {
         "metricName": str,
     },
 )
 
+DescribeCustomMetricResponseTypeDef = TypedDict(
+    "DescribeCustomMetricResponseTypeDef",
+    {
+        "metricName": str,
+        "metricArn": str,
+        "metricType": CustomMetricTypeType,
+        "displayName": str,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDetectMitigationActionsTaskRequestRequestTypeDef = TypedDict(
     "DescribeDetectMitigationActionsTaskRequestRequestTypeDef",
     {
         "taskId": str,
     },
 )
 
 DescribeDimensionRequestRequestTypeDef = TypedDict(
     "DescribeDimensionRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+DescribeDimensionResponseTypeDef = TypedDict(
+    "DescribeDimensionResponseTypeDef",
+    {
+        "name": str,
+        "arn": str,
+        "type": Literal["TOPIC_FILTER"],
+        "stringValues": List[str],
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDomainConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeDomainConfigurationRequestRequestTypeDef",
     {
         "domainConfigurationName": str,
     },
 )
 
@@ -2279,28 +2687,46 @@
     "DescribeEndpointRequestRequestTypeDef",
     {
         "endpointType": str,
     },
     total=False,
 )
 
+DescribeEndpointResponseTypeDef = TypedDict(
+    "DescribeEndpointResponseTypeDef",
+    {
+        "endpointAddress": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeFleetMetricRequestRequestTypeDef = TypedDict(
     "DescribeFleetMetricRequestRequestTypeDef",
     {
         "metricName": str,
     },
 )
 
 DescribeIndexRequestRequestTypeDef = TypedDict(
     "DescribeIndexRequestRequestTypeDef",
     {
         "indexName": str,
     },
 )
 
+DescribeIndexResponseTypeDef = TypedDict(
+    "DescribeIndexResponseTypeDef",
+    {
+        "indexName": str,
+        "indexStatus": IndexStatusType,
+        "schema": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeJobExecutionRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeJobExecutionRequestRequestTypeDef",
     {
         "jobId": str,
         "thingName": str,
     },
 )
@@ -2382,14 +2808,25 @@
     "DescribeProvisioningTemplateVersionRequestRequestTypeDef",
     {
         "templateName": str,
         "versionId": int,
     },
 )
 
+DescribeProvisioningTemplateVersionResponseTypeDef = TypedDict(
+    "DescribeProvisioningTemplateVersionResponseTypeDef",
+    {
+        "versionId": int,
+        "creationDate": datetime,
+        "templateBody": str,
+        "isDefaultVersion": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeRoleAliasRequestRequestTypeDef = TypedDict(
     "DescribeRoleAliasRequestRequestTypeDef",
     {
         "roleAlias": str,
     },
 )
 
@@ -2410,14 +2847,27 @@
 DescribeScheduledAuditRequestRequestTypeDef = TypedDict(
     "DescribeScheduledAuditRequestRequestTypeDef",
     {
         "scheduledAuditName": str,
     },
 )
 
+DescribeScheduledAuditResponseTypeDef = TypedDict(
+    "DescribeScheduledAuditResponseTypeDef",
+    {
+        "frequency": AuditFrequencyType,
+        "dayOfMonth": str,
+        "dayOfWeek": DayOfWeekType,
+        "targetCheckNames": List[str],
+        "scheduledAuditName": str,
+        "scheduledAuditArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeSecurityProfileRequestRequestTypeDef = TypedDict(
     "DescribeSecurityProfileRequestRequestTypeDef",
     {
         "securityProfileName": str,
     },
 )
 
@@ -2438,21 +2888,55 @@
 DescribeThingRegistrationTaskRequestRequestTypeDef = TypedDict(
     "DescribeThingRegistrationTaskRequestRequestTypeDef",
     {
         "taskId": str,
     },
 )
 
+DescribeThingRegistrationTaskResponseTypeDef = TypedDict(
+    "DescribeThingRegistrationTaskResponseTypeDef",
+    {
+        "taskId": str,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "templateBody": str,
+        "inputFileBucket": str,
+        "inputFileKey": str,
+        "roleArn": str,
+        "status": StatusType,
+        "message": str,
+        "successCount": int,
+        "failureCount": int,
+        "percentageProgress": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeThingRequestRequestTypeDef = TypedDict(
     "DescribeThingRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 
+DescribeThingResponseTypeDef = TypedDict(
+    "DescribeThingResponseTypeDef",
+    {
+        "defaultClientId": str,
+        "thingName": str,
+        "thingId": str,
+        "thingArn": str,
+        "thingTypeName": str,
+        "attributes": Dict[str, str],
+        "version": int,
+        "billingGroupName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeThingTypeRequestRequestTypeDef = TypedDict(
     "DescribeThingTypeRequestRequestTypeDef",
     {
         "thingTypeName": str,
     },
 )
 
@@ -2581,14 +3065,21 @@
         "policyName": str,
         "policyArn": str,
         "policyDocument": str,
     },
     total=False,
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableIoTLoggingParamsTypeDef = TypedDict(
     "EnableIoTLoggingParamsTypeDef",
     {
         "roleArnForLogging": str,
         "logLevel": LogLevelType,
     },
 )
@@ -2651,22 +3142,23 @@
     {
         "metricName": str,
         "metricArn": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
+GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef = (
+    TypedDict(
+        "GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef",
+        {
+            "securityProfileName": str,
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
 )
 
 GetBehaviorModelTrainingSummariesRequestRequestTypeDef = TypedDict(
     "GetBehaviorModelTrainingSummariesRequestRequestTypeDef",
     {
         "securityProfileName": str,
         "maxResults": int,
@@ -2692,14 +3184,22 @@
 )
 
 class GetCardinalityRequestRequestTypeDef(
     _RequiredGetCardinalityRequestRequestTypeDef, _OptionalGetCardinalityRequestRequestTypeDef
 ):
     pass
 
+GetCardinalityResponseTypeDef = TypedDict(
+    "GetCardinalityResponseTypeDef",
+    {
+        "cardinality": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetEffectivePoliciesRequestRequestTypeDef = TypedDict(
     "GetEffectivePoliciesRequestRequestTypeDef",
     {
         "principal": str,
         "cognitoIdentityPoolId": str,
         "thingName": str,
     },
@@ -2709,21 +3209,91 @@
 GetJobDocumentRequestRequestTypeDef = TypedDict(
     "GetJobDocumentRequestRequestTypeDef",
     {
         "jobId": str,
     },
 )
 
+GetJobDocumentResponseTypeDef = TypedDict(
+    "GetJobDocumentResponseTypeDef",
+    {
+        "document": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetLoggingOptionsResponseTypeDef = TypedDict(
+    "GetLoggingOptionsResponseTypeDef",
+    {
+        "roleArn": str,
+        "logLevel": LogLevelType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetOTAUpdateRequestRequestTypeDef = TypedDict(
     "GetOTAUpdateRequestRequestTypeDef",
     {
         "otaUpdateId": str,
     },
 )
 
+VersionUpdateByJobsConfigTypeDef = TypedDict(
+    "VersionUpdateByJobsConfigTypeDef",
+    {
+        "enabled": bool,
+        "roleArn": str,
+    },
+    total=False,
+)
+
+GetPackageRequestRequestTypeDef = TypedDict(
+    "GetPackageRequestRequestTypeDef",
+    {
+        "packageName": str,
+    },
+)
+
+GetPackageResponseTypeDef = TypedDict(
+    "GetPackageResponseTypeDef",
+    {
+        "packageName": str,
+        "packageArn": str,
+        "description": str,
+        "defaultVersionName": str,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetPackageVersionRequestRequestTypeDef = TypedDict(
+    "GetPackageVersionRequestRequestTypeDef",
+    {
+        "packageName": str,
+        "versionName": str,
+    },
+)
+
+GetPackageVersionResponseTypeDef = TypedDict(
+    "GetPackageVersionResponseTypeDef",
+    {
+        "packageVersionArn": str,
+        "packageName": str,
+        "versionName": str,
+        "description": str,
+        "attributes": Dict[str, str],
+        "status": PackageVersionStatusType,
+        "errorReason": str,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetPercentilesRequestRequestTypeDef = TypedDict(
     "_RequiredGetPercentilesRequestRequestTypeDef",
     {
         "queryString": str,
     },
 )
 _OptionalGetPercentilesRequestRequestTypeDef = TypedDict(
@@ -2754,22 +3324,59 @@
 GetPolicyRequestRequestTypeDef = TypedDict(
     "GetPolicyRequestRequestTypeDef",
     {
         "policyName": str,
     },
 )
 
+GetPolicyResponseTypeDef = TypedDict(
+    "GetPolicyResponseTypeDef",
+    {
+        "policyName": str,
+        "policyArn": str,
+        "policyDocument": str,
+        "defaultVersionId": str,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "generationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetPolicyVersionRequestRequestTypeDef = TypedDict(
     "GetPolicyVersionRequestRequestTypeDef",
     {
         "policyName": str,
         "policyVersionId": str,
     },
 )
 
+GetPolicyVersionResponseTypeDef = TypedDict(
+    "GetPolicyVersionResponseTypeDef",
+    {
+        "policyArn": str,
+        "policyName": str,
+        "policyDocument": str,
+        "policyVersionId": str,
+        "isDefaultVersion": bool,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "generationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetRegistrationCodeResponseTypeDef = TypedDict(
+    "GetRegistrationCodeResponseTypeDef",
+    {
+        "registrationCode": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetStatisticsRequestRequestTypeDef = TypedDict(
     "_RequiredGetStatisticsRequestRequestTypeDef",
     {
         "queryString": str,
     },
 )
 _OptionalGetStatisticsRequestRequestTypeDef = TypedDict(
@@ -2812,14 +3419,24 @@
 GetTopicRuleRequestRequestTypeDef = TypedDict(
     "GetTopicRuleRequestRequestTypeDef",
     {
         "ruleName": str,
     },
 )
 
+GetV2LoggingOptionsResponseTypeDef = TypedDict(
+    "GetV2LoggingOptionsResponseTypeDef",
+    {
+        "roleArn": str,
+        "defaultLogLevel": LogLevelType,
+        "disableAllLogs": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GroupNameAndArnTypeDef = TypedDict(
     "GroupNameAndArnTypeDef",
     {
         "groupName": str,
         "groupArn": str,
     },
     total=False,
@@ -2960,28 +3577,70 @@
         "jobTemplateId": str,
         "description": str,
         "createdAt": datetime,
     },
     total=False,
 )
 
+ScheduledJobRolloutTypeDef = TypedDict(
+    "ScheduledJobRolloutTypeDef",
+    {
+        "startTime": str,
+    },
+    total=False,
+)
+
+ListActiveViolationsRequestListActiveViolationsPaginateTypeDef = TypedDict(
+    "ListActiveViolationsRequestListActiveViolationsPaginateTypeDef",
+    {
+        "thingName": str,
+        "securityProfileName": str,
+        "behaviorCriteriaType": BehaviorCriteriaTypeType,
+        "listSuppressedAlerts": bool,
+        "verificationState": VerificationStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListActiveViolationsRequestRequestTypeDef = TypedDict(
     "ListActiveViolationsRequestRequestTypeDef",
     {
         "thingName": str,
         "securityProfileName": str,
         "behaviorCriteriaType": BehaviorCriteriaTypeType,
         "listSuppressedAlerts": bool,
         "verificationState": VerificationStateType,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef",
+    {
+        "target": str,
+    },
+)
+_OptionalListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef",
+    {
+        "recursive": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef(
+    _RequiredListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef,
+    _OptionalListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredListAttachedPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListAttachedPoliciesRequestRequestTypeDef",
     {
         "target": str,
     },
 )
 _OptionalListAttachedPoliciesRequestRequestTypeDef = TypedDict(
@@ -2996,14 +3655,36 @@
 
 class ListAttachedPoliciesRequestRequestTypeDef(
     _RequiredListAttachedPoliciesRequestRequestTypeDef,
     _OptionalListAttachedPoliciesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef = TypedDict(
+    "_RequiredListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef",
+    {
+        "taskId": str,
+        "findingId": str,
+    },
+)
+_OptionalListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef = TypedDict(
+    "_OptionalListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef",
+    {
+        "actionStatus": AuditMitigationActionsExecutionStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef(
+    _RequiredListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef,
+    _OptionalListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListAuditMitigationActionsExecutionsRequestRequestTypeDef = TypedDict(
     "_RequiredListAuditMitigationActionsExecutionsRequestRequestTypeDef",
     {
         "taskId": str,
         "findingId": str,
     },
 )
@@ -3019,14 +3700,38 @@
 
 class ListAuditMitigationActionsExecutionsRequestRequestTypeDef(
     _RequiredListAuditMitigationActionsExecutionsRequestRequestTypeDef,
     _OptionalListAuditMitigationActionsExecutionsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef = TypedDict(
+    "_RequiredListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef",
+    {
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+    },
+)
+_OptionalListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef = TypedDict(
+    "_OptionalListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef",
+    {
+        "auditTaskId": str,
+        "findingId": str,
+        "taskStatus": AuditMitigationActionsTaskStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef(
+    _RequiredListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef,
+    _OptionalListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef,
+):
+    pass
+
 _RequiredListAuditMitigationActionsTasksRequestRequestTypeDef = TypedDict(
     "_RequiredListAuditMitigationActionsTasksRequestRequestTypeDef",
     {
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
     },
 )
@@ -3044,14 +3749,37 @@
 
 class ListAuditMitigationActionsTasksRequestRequestTypeDef(
     _RequiredListAuditMitigationActionsTasksRequestRequestTypeDef,
     _OptionalListAuditMitigationActionsTasksRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListAuditTasksRequestListAuditTasksPaginateTypeDef = TypedDict(
+    "_RequiredListAuditTasksRequestListAuditTasksPaginateTypeDef",
+    {
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+    },
+)
+_OptionalListAuditTasksRequestListAuditTasksPaginateTypeDef = TypedDict(
+    "_OptionalListAuditTasksRequestListAuditTasksPaginateTypeDef",
+    {
+        "taskType": AuditTaskTypeType,
+        "taskStatus": AuditTaskStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAuditTasksRequestListAuditTasksPaginateTypeDef(
+    _RequiredListAuditTasksRequestListAuditTasksPaginateTypeDef,
+    _OptionalListAuditTasksRequestListAuditTasksPaginateTypeDef,
+):
+    pass
+
 _RequiredListAuditTasksRequestRequestTypeDef = TypedDict(
     "_RequiredListAuditTasksRequestRequestTypeDef",
     {
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
     },
 )
@@ -3067,46 +3795,96 @@
 )
 
 class ListAuditTasksRequestRequestTypeDef(
     _RequiredListAuditTasksRequestRequestTypeDef, _OptionalListAuditTasksRequestRequestTypeDef
 ):
     pass
 
+ListAuthorizersRequestListAuthorizersPaginateTypeDef = TypedDict(
+    "ListAuthorizersRequestListAuthorizersPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "status": AuthorizerStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAuthorizersRequestRequestTypeDef = TypedDict(
     "ListAuthorizersRequestRequestTypeDef",
     {
         "pageSize": int,
         "marker": str,
         "ascendingOrder": bool,
         "status": AuthorizerStatusType,
     },
     total=False,
 )
 
+ListBillingGroupsRequestListBillingGroupsPaginateTypeDef = TypedDict(
+    "ListBillingGroupsRequestListBillingGroupsPaginateTypeDef",
+    {
+        "namePrefixFilter": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBillingGroupsRequestRequestTypeDef = TypedDict(
     "ListBillingGroupsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "namePrefixFilter": str,
     },
     total=False,
 )
 
+ListCACertificatesRequestListCACertificatesPaginateTypeDef = TypedDict(
+    "ListCACertificatesRequestListCACertificatesPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "templateName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCACertificatesRequestRequestTypeDef = TypedDict(
     "ListCACertificatesRequestRequestTypeDef",
     {
         "pageSize": int,
         "marker": str,
         "ascendingOrder": bool,
         "templateName": str,
     },
     total=False,
 )
 
+_RequiredListCertificatesByCARequestListCertificatesByCAPaginateTypeDef = TypedDict(
+    "_RequiredListCertificatesByCARequestListCertificatesByCAPaginateTypeDef",
+    {
+        "caCertificateId": str,
+    },
+)
+_OptionalListCertificatesByCARequestListCertificatesByCAPaginateTypeDef = TypedDict(
+    "_OptionalListCertificatesByCARequestListCertificatesByCAPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListCertificatesByCARequestListCertificatesByCAPaginateTypeDef(
+    _RequiredListCertificatesByCARequestListCertificatesByCAPaginateTypeDef,
+    _OptionalListCertificatesByCARequestListCertificatesByCAPaginateTypeDef,
+):
+    pass
+
 _RequiredListCertificatesByCARequestRequestTypeDef = TypedDict(
     "_RequiredListCertificatesByCARequestRequestTypeDef",
     {
         "caCertificateId": str,
     },
 )
 _OptionalListCertificatesByCARequestRequestTypeDef = TypedDict(
@@ -3121,47 +3899,107 @@
 
 class ListCertificatesByCARequestRequestTypeDef(
     _RequiredListCertificatesByCARequestRequestTypeDef,
     _OptionalListCertificatesByCARequestRequestTypeDef,
 ):
     pass
 
+ListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
+    "ListCertificatesRequestListCertificatesPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCertificatesRequestRequestTypeDef = TypedDict(
     "ListCertificatesRequestRequestTypeDef",
     {
         "pageSize": int,
         "marker": str,
         "ascendingOrder": bool,
     },
     total=False,
 )
 
+ListCustomMetricsRequestListCustomMetricsPaginateTypeDef = TypedDict(
+    "ListCustomMetricsRequestListCustomMetricsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCustomMetricsRequestRequestTypeDef = TypedDict(
     "ListCustomMetricsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListCustomMetricsResponseTypeDef = TypedDict(
+    "ListCustomMetricsResponseTypeDef",
+    {
+        "metricNames": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef = TypedDict(
+    "ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef",
+    {
+        "taskId": str,
+        "violationId": str,
+        "thingName": str,
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDetectMitigationActionsExecutionsRequestRequestTypeDef = TypedDict(
     "ListDetectMitigationActionsExecutionsRequestRequestTypeDef",
     {
         "taskId": str,
         "violationId": str,
         "thingName": str,
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef = TypedDict(
+    "_RequiredListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef",
+    {
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+    },
+)
+_OptionalListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef = TypedDict(
+    "_OptionalListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef(
+    _RequiredListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef,
+    _OptionalListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef,
+):
+    pass
+
 _RequiredListDetectMitigationActionsTasksRequestRequestTypeDef = TypedDict(
     "_RequiredListDetectMitigationActionsTasksRequestRequestTypeDef",
     {
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
     },
 )
@@ -3176,51 +4014,123 @@
 
 class ListDetectMitigationActionsTasksRequestRequestTypeDef(
     _RequiredListDetectMitigationActionsTasksRequestRequestTypeDef,
     _OptionalListDetectMitigationActionsTasksRequestRequestTypeDef,
 ):
     pass
 
+ListDimensionsRequestListDimensionsPaginateTypeDef = TypedDict(
+    "ListDimensionsRequestListDimensionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDimensionsRequestRequestTypeDef = TypedDict(
     "ListDimensionsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListDimensionsResponseTypeDef = TypedDict(
+    "ListDimensionsResponseTypeDef",
+    {
+        "dimensionNames": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef = TypedDict(
+    "ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef",
+    {
+        "serviceType": ServiceTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDomainConfigurationsRequestRequestTypeDef = TypedDict(
     "ListDomainConfigurationsRequestRequestTypeDef",
     {
         "marker": str,
         "pageSize": int,
         "serviceType": ServiceTypeType,
     },
     total=False,
 )
 
+ListFleetMetricsRequestListFleetMetricsPaginateTypeDef = TypedDict(
+    "ListFleetMetricsRequestListFleetMetricsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFleetMetricsRequestRequestTypeDef = TypedDict(
     "ListFleetMetricsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListIndicesRequestListIndicesPaginateTypeDef = TypedDict(
+    "ListIndicesRequestListIndicesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListIndicesRequestRequestTypeDef = TypedDict(
     "ListIndicesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListIndicesResponseTypeDef = TypedDict(
+    "ListIndicesResponseTypeDef",
+    {
+        "indexNames": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef = TypedDict(
+    "_RequiredListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef",
+    {
+        "jobId": str,
+    },
+)
+_OptionalListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef = TypedDict(
+    "_OptionalListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef",
+    {
+        "status": JobExecutionStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef(
+    _RequiredListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef,
+    _OptionalListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef,
+):
+    pass
+
 _RequiredListJobExecutionsForJobRequestRequestTypeDef = TypedDict(
     "_RequiredListJobExecutionsForJobRequestRequestTypeDef",
     {
         "jobId": str,
     },
 )
 _OptionalListJobExecutionsForJobRequestRequestTypeDef = TypedDict(
@@ -3235,14 +4145,37 @@
 
 class ListJobExecutionsForJobRequestRequestTypeDef(
     _RequiredListJobExecutionsForJobRequestRequestTypeDef,
     _OptionalListJobExecutionsForJobRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef = TypedDict(
+    "_RequiredListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef",
+    {
+        "thingName": str,
+    },
+)
+_OptionalListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef = TypedDict(
+    "_OptionalListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef",
+    {
+        "status": JobExecutionStatusType,
+        "namespaceId": str,
+        "jobId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef(
+    _RequiredListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef,
+    _OptionalListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef,
+):
+    pass
+
 _RequiredListJobExecutionsForThingRequestRequestTypeDef = TypedDict(
     "_RequiredListJobExecutionsForThingRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 _OptionalListJobExecutionsForThingRequestRequestTypeDef = TypedDict(
@@ -3259,37 +4192,67 @@
 
 class ListJobExecutionsForThingRequestRequestTypeDef(
     _RequiredListJobExecutionsForThingRequestRequestTypeDef,
     _OptionalListJobExecutionsForThingRequestRequestTypeDef,
 ):
     pass
 
+ListJobTemplatesRequestListJobTemplatesPaginateTypeDef = TypedDict(
+    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListJobTemplatesRequestRequestTypeDef = TypedDict(
     "ListJobTemplatesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListJobsRequestListJobsPaginateTypeDef = TypedDict(
+    "ListJobsRequestListJobsPaginateTypeDef",
+    {
+        "status": JobStatusType,
+        "targetSelection": TargetSelectionType,
+        "thingGroupName": str,
+        "thingGroupId": str,
+        "namespaceId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListJobsRequestRequestTypeDef = TypedDict(
     "ListJobsRequestRequestTypeDef",
     {
         "status": JobStatusType,
         "targetSelection": TargetSelectionType,
         "maxResults": int,
         "nextToken": str,
         "thingGroupName": str,
         "thingGroupId": str,
         "namespaceId": str,
     },
     total=False,
 )
 
+ListManagedJobTemplatesRequestListManagedJobTemplatesPaginateTypeDef = TypedDict(
+    "ListManagedJobTemplatesRequestListManagedJobTemplatesPaginateTypeDef",
+    {
+        "templateName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListManagedJobTemplatesRequestRequestTypeDef = TypedDict(
     "ListManagedJobTemplatesRequestRequestTypeDef",
     {
         "templateName": str,
         "maxResults": int,
         "nextToken": str,
     },
@@ -3304,14 +4267,39 @@
         "description": str,
         "environments": List[str],
         "templateVersion": str,
     },
     total=False,
 )
 
+_RequiredListMetricValuesRequestListMetricValuesPaginateTypeDef = TypedDict(
+    "_RequiredListMetricValuesRequestListMetricValuesPaginateTypeDef",
+    {
+        "thingName": str,
+        "metricName": str,
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+    },
+)
+_OptionalListMetricValuesRequestListMetricValuesPaginateTypeDef = TypedDict(
+    "_OptionalListMetricValuesRequestListMetricValuesPaginateTypeDef",
+    {
+        "dimensionName": str,
+        "dimensionValueOperator": DimensionValueOperatorType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListMetricValuesRequestListMetricValuesPaginateTypeDef(
+    _RequiredListMetricValuesRequestListMetricValuesPaginateTypeDef,
+    _OptionalListMetricValuesRequestListMetricValuesPaginateTypeDef,
+):
+    pass
+
 _RequiredListMetricValuesRequestRequestTypeDef = TypedDict(
     "_RequiredListMetricValuesRequestRequestTypeDef",
     {
         "thingName": str,
         "metricName": str,
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
@@ -3329,14 +4317,23 @@
 )
 
 class ListMetricValuesRequestRequestTypeDef(
     _RequiredListMetricValuesRequestRequestTypeDef, _OptionalListMetricValuesRequestRequestTypeDef
 ):
     pass
 
+ListMitigationActionsRequestListMitigationActionsPaginateTypeDef = TypedDict(
+    "ListMitigationActionsRequestListMitigationActionsPaginateTypeDef",
+    {
+        "actionType": MitigationActionTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMitigationActionsRequestRequestTypeDef = TypedDict(
     "ListMitigationActionsRequestRequestTypeDef",
     {
         "actionType": MitigationActionTypeType,
         "maxResults": int,
         "nextToken": str,
     },
@@ -3349,14 +4346,23 @@
         "actionName": str,
         "actionArn": str,
         "creationDate": datetime,
     },
     total=False,
 )
 
+ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef = TypedDict(
+    "ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef",
+    {
+        "otaUpdateStatus": OTAUpdateStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOTAUpdatesRequestRequestTypeDef = TypedDict(
     "ListOTAUpdatesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "otaUpdateStatus": OTAUpdateStatusType,
     },
@@ -3369,14 +4375,23 @@
         "otaUpdateId": str,
         "otaUpdateArn": str,
         "creationDate": datetime,
     },
     total=False,
 )
 
+ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef = TypedDict(
+    "ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOutgoingCertificatesRequestRequestTypeDef = TypedDict(
     "ListOutgoingCertificatesRequestRequestTypeDef",
     {
         "pageSize": int,
         "marker": str,
         "ascendingOrder": bool,
     },
@@ -3392,24 +4407,137 @@
         "transferDate": datetime,
         "transferMessage": str,
         "creationDate": datetime,
     },
     total=False,
 )
 
+_RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
+    {
+        "packageName": str,
+    },
+)
+_OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef",
+    {
+        "status": PackageVersionStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPackageVersionsRequestListPackageVersionsPaginateTypeDef(
+    _RequiredListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
+    _OptionalListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
+):
+    pass
+
+_RequiredListPackageVersionsRequestRequestTypeDef = TypedDict(
+    "_RequiredListPackageVersionsRequestRequestTypeDef",
+    {
+        "packageName": str,
+    },
+)
+_OptionalListPackageVersionsRequestRequestTypeDef = TypedDict(
+    "_OptionalListPackageVersionsRequestRequestTypeDef",
+    {
+        "status": PackageVersionStatusType,
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+class ListPackageVersionsRequestRequestTypeDef(
+    _RequiredListPackageVersionsRequestRequestTypeDef,
+    _OptionalListPackageVersionsRequestRequestTypeDef,
+):
+    pass
+
+PackageVersionSummaryTypeDef = TypedDict(
+    "PackageVersionSummaryTypeDef",
+    {
+        "packageName": str,
+        "versionName": str,
+        "status": PackageVersionStatusType,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+    },
+    total=False,
+)
+
+ListPackagesRequestListPackagesPaginateTypeDef = TypedDict(
+    "ListPackagesRequestListPackagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListPackagesRequestRequestTypeDef = TypedDict(
+    "ListPackagesRequestRequestTypeDef",
+    {
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+PackageSummaryTypeDef = TypedDict(
+    "PackageSummaryTypeDef",
+    {
+        "packageName": str,
+        "defaultVersionName": str,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+    },
+    total=False,
+)
+
+ListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
+    "ListPoliciesRequestListPoliciesPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPoliciesRequestRequestTypeDef = TypedDict(
     "ListPoliciesRequestRequestTypeDef",
     {
         "marker": str,
         "pageSize": int,
         "ascendingOrder": bool,
     },
     total=False,
 )
 
+_RequiredListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef = TypedDict(
+    "_RequiredListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef",
+    {
+        "policyName": str,
+    },
+)
+_OptionalListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef = TypedDict(
+    "_OptionalListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef(
+    _RequiredListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef,
+    _OptionalListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef,
+):
+    pass
+
 _RequiredListPolicyPrincipalsRequestRequestTypeDef = TypedDict(
     "_RequiredListPolicyPrincipalsRequestRequestTypeDef",
     {
         "policyName": str,
     },
 )
 _OptionalListPolicyPrincipalsRequestRequestTypeDef = TypedDict(
@@ -3424,14 +4552,23 @@
 
 class ListPolicyPrincipalsRequestRequestTypeDef(
     _RequiredListPolicyPrincipalsRequestRequestTypeDef,
     _OptionalListPolicyPrincipalsRequestRequestTypeDef,
 ):
     pass
 
+ListPolicyPrincipalsResponseTypeDef = TypedDict(
+    "ListPolicyPrincipalsResponseTypeDef",
+    {
+        "principals": List[str],
+        "nextMarker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListPolicyVersionsRequestRequestTypeDef = TypedDict(
     "ListPolicyVersionsRequestRequestTypeDef",
     {
         "policyName": str,
     },
 )
 
@@ -3441,14 +4578,35 @@
         "versionId": str,
         "isDefaultVersion": bool,
         "createDate": datetime,
     },
     total=False,
 )
 
+_RequiredListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef",
+    {
+        "principal": str,
+    },
+)
+_OptionalListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef(
+    _RequiredListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef,
+    _OptionalListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredListPrincipalPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListPrincipalPoliciesRequestRequestTypeDef",
     {
         "principal": str,
     },
 )
 _OptionalListPrincipalPoliciesRequestRequestTypeDef = TypedDict(
@@ -3463,14 +4621,34 @@
 
 class ListPrincipalPoliciesRequestRequestTypeDef(
     _RequiredListPrincipalPoliciesRequestRequestTypeDef,
     _OptionalListPrincipalPoliciesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef = TypedDict(
+    "_RequiredListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef",
+    {
+        "principal": str,
+    },
+)
+_OptionalListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef = TypedDict(
+    "_OptionalListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef(
+    _RequiredListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef,
+    _OptionalListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef,
+):
+    pass
+
 _RequiredListPrincipalThingsRequestRequestTypeDef = TypedDict(
     "_RequiredListPrincipalThingsRequestRequestTypeDef",
     {
         "principal": str,
     },
 )
 _OptionalListPrincipalThingsRequestRequestTypeDef = TypedDict(
@@ -3484,14 +4662,43 @@
 
 class ListPrincipalThingsRequestRequestTypeDef(
     _RequiredListPrincipalThingsRequestRequestTypeDef,
     _OptionalListPrincipalThingsRequestRequestTypeDef,
 ):
     pass
 
+ListPrincipalThingsResponseTypeDef = TypedDict(
+    "ListPrincipalThingsResponseTypeDef",
+    {
+        "things": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef",
+    {
+        "templateName": str,
+    },
+)
+_OptionalListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef(
+    _RequiredListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef,
+    _OptionalListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListProvisioningTemplateVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListProvisioningTemplateVersionsRequestRequestTypeDef",
     {
         "templateName": str,
     },
 )
 _OptionalListProvisioningTemplateVersionsRequestRequestTypeDef = TypedDict(
@@ -3515,14 +4722,22 @@
         "versionId": int,
         "creationDate": datetime,
         "isDefaultVersion": bool,
     },
     total=False,
 )
 
+ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef = TypedDict(
+    "ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProvisioningTemplatesRequestRequestTypeDef = TypedDict(
     "ListProvisioningTemplatesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -3538,14 +4753,34 @@
         "lastModifiedDate": datetime,
         "enabled": bool,
         "type": TemplateTypeType,
     },
     total=False,
 )
 
+_RequiredListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef = TypedDict(
+    "_RequiredListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef",
+    {
+        "findingId": str,
+    },
+)
+_OptionalListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef = TypedDict(
+    "_OptionalListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef(
+    _RequiredListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef,
+    _OptionalListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef,
+):
+    pass
+
 _RequiredListRelatedResourcesForAuditFindingRequestRequestTypeDef = TypedDict(
     "_RequiredListRelatedResourcesForAuditFindingRequestRequestTypeDef",
     {
         "findingId": str,
     },
 )
 _OptionalListRelatedResourcesForAuditFindingRequestRequestTypeDef = TypedDict(
@@ -3559,24 +4794,50 @@
 
 class ListRelatedResourcesForAuditFindingRequestRequestTypeDef(
     _RequiredListRelatedResourcesForAuditFindingRequestRequestTypeDef,
     _OptionalListRelatedResourcesForAuditFindingRequestRequestTypeDef,
 ):
     pass
 
+ListRoleAliasesRequestListRoleAliasesPaginateTypeDef = TypedDict(
+    "ListRoleAliasesRequestListRoleAliasesPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRoleAliasesRequestRequestTypeDef = TypedDict(
     "ListRoleAliasesRequestRequestTypeDef",
     {
         "pageSize": int,
         "marker": str,
         "ascendingOrder": bool,
     },
     total=False,
 )
 
+ListRoleAliasesResponseTypeDef = TypedDict(
+    "ListRoleAliasesResponseTypeDef",
+    {
+        "roleAliases": List[str],
+        "nextMarker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef = TypedDict(
+    "ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListScheduledAuditsRequestRequestTypeDef = TypedDict(
     "ListScheduledAuditsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -3590,14 +4851,39 @@
         "frequency": AuditFrequencyType,
         "dayOfMonth": str,
         "dayOfWeek": DayOfWeekType,
     },
     total=False,
 )
 
+_RequiredListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef",
+        {
+            "securityProfileTargetArn": str,
+        },
+    )
+)
+_OptionalListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef",
+        {
+            "recursive": bool,
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+class ListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef(
+    _RequiredListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef,
+    _OptionalListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef,
+):
+    pass
+
 _RequiredListSecurityProfilesForTargetRequestRequestTypeDef = TypedDict(
     "_RequiredListSecurityProfilesForTargetRequestRequestTypeDef",
     {
         "securityProfileTargetArn": str,
     },
 )
 _OptionalListSecurityProfilesForTargetRequestRequestTypeDef = TypedDict(
@@ -3612,14 +4898,24 @@
 
 class ListSecurityProfilesForTargetRequestRequestTypeDef(
     _RequiredListSecurityProfilesForTargetRequestRequestTypeDef,
     _OptionalListSecurityProfilesForTargetRequestRequestTypeDef,
 ):
     pass
 
+ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef = TypedDict(
+    "ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef",
+    {
+        "dimensionName": str,
+        "metricName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSecurityProfilesRequestRequestTypeDef = TypedDict(
     "ListSecurityProfilesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "dimensionName": str,
         "metricName": str,
@@ -3631,14 +4927,23 @@
     "SecurityProfileIdentifierTypeDef",
     {
         "name": str,
         "arn": str,
     },
 )
 
+ListStreamsRequestListStreamsPaginateTypeDef = TypedDict(
+    "ListStreamsRequestListStreamsPaginateTypeDef",
+    {
+        "ascendingOrder": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStreamsRequestRequestTypeDef = TypedDict(
     "ListStreamsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "ascendingOrder": bool,
     },
@@ -3652,14 +4957,34 @@
         "streamArn": str,
         "streamVersion": int,
         "description": str,
     },
     total=False,
 )
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+):
+    pass
+
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -3672,14 +4997,34 @@
 
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
+    "_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
+    {
+        "policyName": str,
+    },
+)
+_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
+    "_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef(
+    _RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
+    _OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
+):
+    pass
+
 _RequiredListTargetsForPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredListTargetsForPolicyRequestRequestTypeDef",
     {
         "policyName": str,
     },
 )
 _OptionalListTargetsForPolicyRequestRequestTypeDef = TypedDict(
@@ -3693,14 +5038,47 @@
 
 class ListTargetsForPolicyRequestRequestTypeDef(
     _RequiredListTargetsForPolicyRequestRequestTypeDef,
     _OptionalListTargetsForPolicyRequestRequestTypeDef,
 ):
     pass
 
+ListTargetsForPolicyResponseTypeDef = TypedDict(
+    "ListTargetsForPolicyResponseTypeDef",
+    {
+        "targets": List[str],
+        "nextMarker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef = (
+    TypedDict(
+        "_RequiredListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef",
+        {
+            "securityProfileName": str,
+        },
+    )
+)
+_OptionalListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef = (
+    TypedDict(
+        "_OptionalListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef",
+        {
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+class ListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef(
+    _RequiredListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef,
+    _OptionalListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef,
+):
+    pass
+
 _RequiredListTargetsForSecurityProfileRequestRequestTypeDef = TypedDict(
     "_RequiredListTargetsForSecurityProfileRequestRequestTypeDef",
     {
         "securityProfileName": str,
     },
 )
 _OptionalListTargetsForSecurityProfileRequestRequestTypeDef = TypedDict(
@@ -3721,14 +5099,34 @@
 SecurityProfileTargetTypeDef = TypedDict(
     "SecurityProfileTargetTypeDef",
     {
         "arn": str,
     },
 )
 
+_RequiredListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef = TypedDict(
+    "_RequiredListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef",
+    {
+        "thingName": str,
+    },
+)
+_OptionalListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef = TypedDict(
+    "_OptionalListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef(
+    _RequiredListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef,
+    _OptionalListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef,
+):
+    pass
+
 _RequiredListThingGroupsForThingRequestRequestTypeDef = TypedDict(
     "_RequiredListThingGroupsForThingRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 _OptionalListThingGroupsForThingRequestRequestTypeDef = TypedDict(
@@ -3742,26 +5140,57 @@
 
 class ListThingGroupsForThingRequestRequestTypeDef(
     _RequiredListThingGroupsForThingRequestRequestTypeDef,
     _OptionalListThingGroupsForThingRequestRequestTypeDef,
 ):
     pass
 
+ListThingGroupsRequestListThingGroupsPaginateTypeDef = TypedDict(
+    "ListThingGroupsRequestListThingGroupsPaginateTypeDef",
+    {
+        "parentGroup": str,
+        "namePrefixFilter": str,
+        "recursive": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListThingGroupsRequestRequestTypeDef = TypedDict(
     "ListThingGroupsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "parentGroup": str,
         "namePrefixFilter": str,
         "recursive": bool,
     },
     total=False,
 )
 
+_RequiredListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef = TypedDict(
+    "_RequiredListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef",
+    {
+        "thingName": str,
+    },
+)
+_OptionalListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef = TypedDict(
+    "_OptionalListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef(
+    _RequiredListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef,
+    _OptionalListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef,
+):
+    pass
+
 _RequiredListThingPrincipalsRequestRequestTypeDef = TypedDict(
     "_RequiredListThingPrincipalsRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
 _OptionalListThingPrincipalsRequestRequestTypeDef = TypedDict(
@@ -3775,14 +5204,44 @@
 
 class ListThingPrincipalsRequestRequestTypeDef(
     _RequiredListThingPrincipalsRequestRequestTypeDef,
     _OptionalListThingPrincipalsRequestRequestTypeDef,
 ):
     pass
 
+ListThingPrincipalsResponseTypeDef = TypedDict(
+    "ListThingPrincipalsResponseTypeDef",
+    {
+        "principals": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef = TypedDict(
+    "_RequiredListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef",
+    {
+        "taskId": str,
+        "reportType": ReportTypeType,
+    },
+)
+_OptionalListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef = TypedDict(
+    "_OptionalListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef(
+    _RequiredListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef,
+    _OptionalListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef,
+):
+    pass
+
 _RequiredListThingRegistrationTaskReportsRequestRequestTypeDef = TypedDict(
     "_RequiredListThingRegistrationTaskReportsRequestRequestTypeDef",
     {
         "taskId": str,
         "reportType": ReportTypeType,
     },
 )
@@ -3797,34 +5256,91 @@
 
 class ListThingRegistrationTaskReportsRequestRequestTypeDef(
     _RequiredListThingRegistrationTaskReportsRequestRequestTypeDef,
     _OptionalListThingRegistrationTaskReportsRequestRequestTypeDef,
 ):
     pass
 
+ListThingRegistrationTaskReportsResponseTypeDef = TypedDict(
+    "ListThingRegistrationTaskReportsResponseTypeDef",
+    {
+        "resourceLinks": List[str],
+        "reportType": ReportTypeType,
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef = TypedDict(
+    "ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef",
+    {
+        "status": StatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListThingRegistrationTasksRequestRequestTypeDef = TypedDict(
     "ListThingRegistrationTasksRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "status": StatusType,
     },
     total=False,
 )
 
+ListThingRegistrationTasksResponseTypeDef = TypedDict(
+    "ListThingRegistrationTasksResponseTypeDef",
+    {
+        "taskIds": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListThingTypesRequestListThingTypesPaginateTypeDef = TypedDict(
+    "ListThingTypesRequestListThingTypesPaginateTypeDef",
+    {
+        "thingTypeName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListThingTypesRequestRequestTypeDef = TypedDict(
     "ListThingTypesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "thingTypeName": str,
     },
     total=False,
 )
 
+_RequiredListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef = TypedDict(
+    "_RequiredListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef",
+    {
+        "billingGroupName": str,
+    },
+)
+_OptionalListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef = TypedDict(
+    "_OptionalListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef(
+    _RequiredListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef,
+    _OptionalListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef,
+):
+    pass
+
 _RequiredListThingsInBillingGroupRequestRequestTypeDef = TypedDict(
     "_RequiredListThingsInBillingGroupRequestRequestTypeDef",
     {
         "billingGroupName": str,
     },
 )
 _OptionalListThingsInBillingGroupRequestRequestTypeDef = TypedDict(
@@ -3838,14 +5354,44 @@
 
 class ListThingsInBillingGroupRequestRequestTypeDef(
     _RequiredListThingsInBillingGroupRequestRequestTypeDef,
     _OptionalListThingsInBillingGroupRequestRequestTypeDef,
 ):
     pass
 
+ListThingsInBillingGroupResponseTypeDef = TypedDict(
+    "ListThingsInBillingGroupResponseTypeDef",
+    {
+        "things": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef = TypedDict(
+    "_RequiredListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef",
+    {
+        "thingGroupName": str,
+    },
+)
+_OptionalListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef = TypedDict(
+    "_OptionalListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef",
+    {
+        "recursive": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef(
+    _RequiredListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef,
+    _OptionalListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef,
+):
+    pass
+
 _RequiredListThingsInThingGroupRequestRequestTypeDef = TypedDict(
     "_RequiredListThingsInThingGroupRequestRequestTypeDef",
     {
         "thingGroupName": str,
     },
 )
 _OptionalListThingsInThingGroupRequestRequestTypeDef = TypedDict(
@@ -3860,14 +5406,35 @@
 
 class ListThingsInThingGroupRequestRequestTypeDef(
     _RequiredListThingsInThingGroupRequestRequestTypeDef,
     _OptionalListThingsInThingGroupRequestRequestTypeDef,
 ):
     pass
 
+ListThingsInThingGroupResponseTypeDef = TypedDict(
+    "ListThingsInThingGroupResponseTypeDef",
+    {
+        "things": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListThingsRequestListThingsPaginateTypeDef = TypedDict(
+    "ListThingsRequestListThingsPaginateTypeDef",
+    {
+        "attributeName": str,
+        "attributeValue": str,
+        "thingTypeName": str,
+        "usePrefixAttributeValue": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListThingsRequestRequestTypeDef = TypedDict(
     "ListThingsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "attributeName": str,
         "attributeValue": str,
@@ -3885,23 +5452,41 @@
         "thingArn": str,
         "attributes": Dict[str, str],
         "version": int,
     },
     total=False,
 )
 
+ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef = TypedDict(
+    "ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTopicRuleDestinationsRequestRequestTypeDef = TypedDict(
     "ListTopicRuleDestinationsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListTopicRulesRequestListTopicRulesPaginateTypeDef = TypedDict(
+    "ListTopicRulesRequestListTopicRulesPaginateTypeDef",
+    {
+        "topic": str,
+        "ruleDisabled": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTopicRulesRequestRequestTypeDef = TypedDict(
     "ListTopicRulesRequestRequestTypeDef",
     {
         "topic": str,
         "maxResults": int,
         "nextToken": str,
         "ruleDisabled": bool,
@@ -3917,24 +5502,59 @@
         "topicPattern": str,
         "createdAt": datetime,
         "ruleDisabled": bool,
     },
     total=False,
 )
 
+ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef = TypedDict(
+    "ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef",
+    {
+        "targetType": LogTargetTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListV2LoggingLevelsRequestRequestTypeDef = TypedDict(
     "ListV2LoggingLevelsRequestRequestTypeDef",
     {
         "targetType": LogTargetTypeType,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListViolationEventsRequestListViolationEventsPaginateTypeDef = TypedDict(
+    "_RequiredListViolationEventsRequestListViolationEventsPaginateTypeDef",
+    {
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+    },
+)
+_OptionalListViolationEventsRequestListViolationEventsPaginateTypeDef = TypedDict(
+    "_OptionalListViolationEventsRequestListViolationEventsPaginateTypeDef",
+    {
+        "thingName": str,
+        "securityProfileName": str,
+        "behaviorCriteriaType": BehaviorCriteriaTypeType,
+        "listSuppressedAlerts": bool,
+        "verificationState": VerificationStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListViolationEventsRequestListViolationEventsPaginateTypeDef(
+    _RequiredListViolationEventsRequestListViolationEventsPaginateTypeDef,
+    _OptionalListViolationEventsRequestListViolationEventsPaginateTypeDef,
+):
+    pass
+
 _RequiredListViolationEventsRequestRequestTypeDef = TypedDict(
     "_RequiredListViolationEventsRequestRequestTypeDef",
     {
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
     },
 )
@@ -4055,14 +5675,24 @@
     "UserPropertyTypeDef",
     {
         "key": str,
         "value": str,
     },
 )
 
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
+    {
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
+    },
+    total=False,
+)
+
 PolicyVersionIdentifierTypeDef = TypedDict(
     "PolicyVersionIdentifierTypeDef",
     {
         "policyName": str,
         "policyVersionId": str,
     },
     total=False,
@@ -4085,14 +5715,23 @@
 
 class PutVerificationStateOnViolationRequestRequestTypeDef(
     _RequiredPutVerificationStateOnViolationRequestRequestTypeDef,
     _OptionalPutVerificationStateOnViolationRequestRequestTypeDef,
 ):
     pass
 
+RegisterCACertificateResponseTypeDef = TypedDict(
+    "RegisterCACertificateResponseTypeDef",
+    {
+        "certificateArn": str,
+        "certificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRegisterCertificateRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterCertificateRequestRequestTypeDef",
     {
         "certificatePem": str,
     },
 )
 _OptionalRegisterCertificateRequestRequestTypeDef = TypedDict(
@@ -4107,14 +5746,23 @@
 
 class RegisterCertificateRequestRequestTypeDef(
     _RequiredRegisterCertificateRequestRequestTypeDef,
     _OptionalRegisterCertificateRequestRequestTypeDef,
 ):
     pass
 
+RegisterCertificateResponseTypeDef = TypedDict(
+    "RegisterCertificateResponseTypeDef",
+    {
+        "certificateArn": str,
+        "certificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRegisterCertificateWithoutCARequestRequestTypeDef = TypedDict(
     "_RequiredRegisterCertificateWithoutCARequestRequestTypeDef",
     {
         "certificatePem": str,
     },
 )
 _OptionalRegisterCertificateWithoutCARequestRequestTypeDef = TypedDict(
@@ -4127,14 +5775,23 @@
 
 class RegisterCertificateWithoutCARequestRequestTypeDef(
     _RequiredRegisterCertificateWithoutCARequestRequestTypeDef,
     _OptionalRegisterCertificateWithoutCARequestRequestTypeDef,
 ):
     pass
 
+RegisterCertificateWithoutCAResponseTypeDef = TypedDict(
+    "RegisterCertificateWithoutCAResponseTypeDef",
+    {
+        "certificateArn": str,
+        "certificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRegisterThingRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterThingRequestRequestTypeDef",
     {
         "templateBody": str,
     },
 )
 _OptionalRegisterThingRequestRequestTypeDef = TypedDict(
@@ -4146,14 +5803,23 @@
 )
 
 class RegisterThingRequestRequestTypeDef(
     _RequiredRegisterThingRequestRequestTypeDef, _OptionalRegisterThingRequestRequestTypeDef
 ):
     pass
 
+RegisterThingResponseTypeDef = TypedDict(
+    "RegisterThingResponseTypeDef",
+    {
+        "certificatePem": str,
+        "resourceArns": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRejectCertificateTransferRequestRequestTypeDef = TypedDict(
     "_RequiredRejectCertificateTransferRequestRequestTypeDef",
     {
         "certificateId": str,
     },
 )
 _OptionalRejectCertificateTransferRequestRequestTypeDef = TypedDict(
@@ -4188,14 +5854,25 @@
         "thingGroupArn": str,
         "thingName": str,
         "thingArn": str,
     },
     total=False,
 )
 
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
+    {
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
+    },
+)
+
 _RequiredSearchIndexRequestRequestTypeDef = TypedDict(
     "_RequiredSearchIndexRequestRequestTypeDef",
     {
         "queryString": str,
     },
 )
 _OptionalSearchIndexRequestRequestTypeDef = TypedDict(
@@ -4229,14 +5906,23 @@
 SetDefaultAuthorizerRequestRequestTypeDef = TypedDict(
     "SetDefaultAuthorizerRequestRequestTypeDef",
     {
         "authorizerName": str,
     },
 )
 
+SetDefaultAuthorizerResponseTypeDef = TypedDict(
+    "SetDefaultAuthorizerResponseTypeDef",
+    {
+        "authorizerName": str,
+        "authorizerArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SetDefaultPolicyVersionRequestRequestTypeDef = TypedDict(
     "SetDefaultPolicyVersionRequestRequestTypeDef",
     {
         "policyName": str,
         "policyVersionId": str,
     },
 )
@@ -4257,31 +5943,63 @@
         "certificateArn": str,
         "platform": str,
         "certificatePathOnDevice": str,
     },
     total=False,
 )
 
+StartAuditMitigationActionsTaskResponseTypeDef = TypedDict(
+    "StartAuditMitigationActionsTaskResponseTypeDef",
+    {
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartDetectMitigationActionsTaskResponseTypeDef = TypedDict(
+    "StartDetectMitigationActionsTaskResponseTypeDef",
+    {
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartOnDemandAuditTaskRequestRequestTypeDef = TypedDict(
     "StartOnDemandAuditTaskRequestRequestTypeDef",
     {
         "targetCheckNames": Sequence[str],
     },
 )
 
+StartOnDemandAuditTaskResponseTypeDef = TypedDict(
+    "StartOnDemandAuditTaskResponseTypeDef",
+    {
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartThingRegistrationTaskRequestRequestTypeDef = TypedDict(
     "StartThingRegistrationTaskRequestRequestTypeDef",
     {
         "templateBody": str,
         "inputFileBucket": str,
         "inputFileKey": str,
         "roleArn": str,
     },
 )
 
+StartThingRegistrationTaskResponseTypeDef = TypedDict(
+    "StartThingRegistrationTaskResponseTypeDef",
+    {
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopThingRegistrationTaskRequestRequestTypeDef = TypedDict(
     "StopThingRegistrationTaskRequestRequestTypeDef",
     {
         "taskId": str,
     },
 )
 
@@ -4289,14 +6007,26 @@
     "TlsContextTypeDef",
     {
         "serverName": str,
     },
     total=False,
 )
 
+TestInvokeAuthorizerResponseTypeDef = TypedDict(
+    "TestInvokeAuthorizerResponseTypeDef",
+    {
+        "isAuthenticated": bool,
+        "principalId": str,
+        "policyDocuments": List[str],
+        "refreshAfterInSeconds": int,
+        "disconnectAfterInSeconds": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ThingConnectivityTypeDef = TypedDict(
     "ThingConnectivityTypeDef",
     {
         "connected": bool,
         "timestamp": int,
         "disconnectReason": str,
     },
@@ -4379,14 +6109,22 @@
 
 class TransferCertificateRequestRequestTypeDef(
     _RequiredTransferCertificateRequestRequestTypeDef,
     _OptionalTransferCertificateRequestRequestTypeDef,
 ):
     pass
 
+TransferCertificateResponseTypeDef = TypedDict(
+    "TransferCertificateResponseTypeDef",
+    {
+        "transferredCertificateArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -4410,475 +6148,273 @@
 )
 
 class UpdateAuthorizerRequestRequestTypeDef(
     _RequiredUpdateAuthorizerRequestRequestTypeDef, _OptionalUpdateAuthorizerRequestRequestTypeDef
 ):
     pass
 
-UpdateCertificateRequestRequestTypeDef = TypedDict(
-    "UpdateCertificateRequestRequestTypeDef",
+UpdateAuthorizerResponseTypeDef = TypedDict(
+    "UpdateAuthorizerResponseTypeDef",
     {
-        "certificateId": str,
-        "newStatus": CertificateStatusType,
+        "authorizerName": str,
+        "authorizerArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateCustomMetricRequestRequestTypeDef = TypedDict(
-    "UpdateCustomMetricRequestRequestTypeDef",
+UpdateBillingGroupResponseTypeDef = TypedDict(
+    "UpdateBillingGroupResponseTypeDef",
     {
-        "metricName": str,
-        "displayName": str,
+        "version": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateDimensionRequestRequestTypeDef = TypedDict(
-    "UpdateDimensionRequestRequestTypeDef",
+UpdateCertificateRequestRequestTypeDef = TypedDict(
+    "UpdateCertificateRequestRequestTypeDef",
     {
-        "name": str,
-        "stringValues": Sequence[str],
+        "certificateId": str,
+        "newStatus": CertificateStatusType,
     },
 )
 
-_RequiredUpdateRoleAliasRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateRoleAliasRequestRequestTypeDef",
-    {
-        "roleAlias": str,
-    },
-)
-_OptionalUpdateRoleAliasRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateRoleAliasRequestRequestTypeDef",
+UpdateCustomMetricRequestRequestTypeDef = TypedDict(
+    "UpdateCustomMetricRequestRequestTypeDef",
     {
-        "roleArn": str,
-        "credentialDurationSeconds": int,
+        "metricName": str,
+        "displayName": str,
     },
-    total=False,
 )
 
-class UpdateRoleAliasRequestRequestTypeDef(
-    _RequiredUpdateRoleAliasRequestRequestTypeDef, _OptionalUpdateRoleAliasRequestRequestTypeDef
-):
-    pass
-
-_RequiredUpdateScheduledAuditRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateScheduledAuditRequestRequestTypeDef",
-    {
-        "scheduledAuditName": str,
-    },
-)
-_OptionalUpdateScheduledAuditRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateScheduledAuditRequestRequestTypeDef",
+UpdateCustomMetricResponseTypeDef = TypedDict(
+    "UpdateCustomMetricResponseTypeDef",
     {
-        "frequency": AuditFrequencyType,
-        "dayOfMonth": str,
-        "dayOfWeek": DayOfWeekType,
-        "targetCheckNames": Sequence[str],
+        "metricName": str,
+        "metricArn": str,
+        "metricType": CustomMetricTypeType,
+        "displayName": str,
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class UpdateScheduledAuditRequestRequestTypeDef(
-    _RequiredUpdateScheduledAuditRequestRequestTypeDef,
-    _OptionalUpdateScheduledAuditRequestRequestTypeDef,
-):
-    pass
-
-UpdateThingGroupsForThingRequestRequestTypeDef = TypedDict(
-    "UpdateThingGroupsForThingRequestRequestTypeDef",
+UpdateDimensionRequestRequestTypeDef = TypedDict(
+    "UpdateDimensionRequestRequestTypeDef",
     {
-        "thingName": str,
-        "thingGroupsToAdd": Sequence[str],
-        "thingGroupsToRemove": Sequence[str],
-        "overrideDynamicGroups": bool,
+        "name": str,
+        "stringValues": Sequence[str],
     },
-    total=False,
 )
 
-UpdateTopicRuleDestinationRequestRequestTypeDef = TypedDict(
-    "UpdateTopicRuleDestinationRequestRequestTypeDef",
+UpdateDimensionResponseTypeDef = TypedDict(
+    "UpdateDimensionResponseTypeDef",
     {
+        "name": str,
         "arn": str,
-        "status": TopicRuleDestinationStatusType,
+        "type": Literal["TOPIC_FILTER"],
+        "stringValues": List[str],
+        "creationDate": datetime,
+        "lastModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ValidationErrorTypeDef = TypedDict(
-    "ValidationErrorTypeDef",
+UpdateDomainConfigurationResponseTypeDef = TypedDict(
+    "UpdateDomainConfigurationResponseTypeDef",
     {
-        "errorMessage": str,
+        "domainConfigurationName": str,
+        "domainConfigurationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-AbortConfigTypeDef = TypedDict(
-    "AbortConfigTypeDef",
+UpdateDynamicThingGroupResponseTypeDef = TypedDict(
+    "UpdateDynamicThingGroupResponseTypeDef",
     {
-        "criteriaList": Sequence[AbortCriteriaTypeDef],
+        "version": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-MetricDatumTypeDef = TypedDict(
-    "MetricDatumTypeDef",
+UpdateMitigationActionResponseTypeDef = TypedDict(
+    "UpdateMitigationActionResponseTypeDef",
     {
-        "timestamp": datetime,
-        "value": MetricValueTypeDef,
+        "actionArn": str,
+        "actionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredUpdateFleetMetricRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateFleetMetricRequestRequestTypeDef",
+_RequiredUpdatePackageRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdatePackageRequestRequestTypeDef",
     {
-        "metricName": str,
-        "indexName": str,
+        "packageName": str,
     },
 )
-_OptionalUpdateFleetMetricRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateFleetMetricRequestRequestTypeDef",
+_OptionalUpdatePackageRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdatePackageRequestRequestTypeDef",
     {
-        "queryString": str,
-        "aggregationType": AggregationTypeTypeDef,
-        "period": int,
-        "aggregationField": str,
         "description": str,
-        "queryVersion": str,
-        "unit": FleetMetricUnitType,
-        "expectedVersion": int,
+        "defaultVersionName": str,
+        "unsetDefaultVersion": bool,
+        "clientToken": str,
     },
     total=False,
 )
 
-class UpdateFleetMetricRequestRequestTypeDef(
-    _RequiredUpdateFleetMetricRequestRequestTypeDef, _OptionalUpdateFleetMetricRequestRequestTypeDef
+class UpdatePackageRequestRequestTypeDef(
+    _RequiredUpdatePackageRequestRequestTypeDef, _OptionalUpdatePackageRequestRequestTypeDef
 ):
     pass
 
-AllowedTypeDef = TypedDict(
-    "AllowedTypeDef",
+_RequiredUpdatePackageVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdatePackageVersionRequestRequestTypeDef",
     {
-        "policies": List[PolicyTypeDef],
+        "packageName": str,
+        "versionName": str,
     },
-    total=False,
 )
-
-ExplicitDenyTypeDef = TypedDict(
-    "ExplicitDenyTypeDef",
+_OptionalUpdatePackageVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdatePackageVersionRequestRequestTypeDef",
     {
-        "policies": List[PolicyTypeDef],
+        "description": str,
+        "attributes": Mapping[str, str],
+        "action": PackageVersionActionType,
+        "clientToken": str,
     },
     total=False,
 )
 
-ImplicitDenyTypeDef = TypedDict(
-    "ImplicitDenyTypeDef",
-    {
-        "policies": List[PolicyTypeDef],
-    },
-    total=False,
-)
+class UpdatePackageVersionRequestRequestTypeDef(
+    _RequiredUpdatePackageVersionRequestRequestTypeDef,
+    _OptionalUpdatePackageVersionRequestRequestTypeDef,
+):
+    pass
 
-_RequiredAssetPropertyValueTypeDef = TypedDict(
-    "_RequiredAssetPropertyValueTypeDef",
+_RequiredUpdateRoleAliasRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateRoleAliasRequestRequestTypeDef",
     {
-        "value": AssetPropertyVariantTypeDef,
-        "timestamp": AssetPropertyTimestampTypeDef,
+        "roleAlias": str,
     },
 )
-_OptionalAssetPropertyValueTypeDef = TypedDict(
-    "_OptionalAssetPropertyValueTypeDef",
+_OptionalUpdateRoleAliasRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateRoleAliasRequestRequestTypeDef",
     {
-        "quality": str,
+        "roleArn": str,
+        "credentialDurationSeconds": int,
     },
     total=False,
 )
 
-class AssetPropertyValueTypeDef(
-    _RequiredAssetPropertyValueTypeDef, _OptionalAssetPropertyValueTypeDef
+class UpdateRoleAliasRequestRequestTypeDef(
+    _RequiredUpdateRoleAliasRequestRequestTypeDef, _OptionalUpdateRoleAliasRequestRequestTypeDef
 ):
     pass
 
-AssociateTargetsWithJobResponseTypeDef = TypedDict(
-    "AssociateTargetsWithJobResponseTypeDef",
-    {
-        "jobArn": str,
-        "jobId": str,
-        "description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelJobResponseTypeDef = TypedDict(
-    "CancelJobResponseTypeDef",
-    {
-        "jobArn": str,
-        "jobId": str,
-        "description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAuthorizerResponseTypeDef = TypedDict(
-    "CreateAuthorizerResponseTypeDef",
-    {
-        "authorizerName": str,
-        "authorizerArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBillingGroupResponseTypeDef = TypedDict(
-    "CreateBillingGroupResponseTypeDef",
-    {
-        "billingGroupName": str,
-        "billingGroupArn": str,
-        "billingGroupId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCertificateFromCsrResponseTypeDef = TypedDict(
-    "CreateCertificateFromCsrResponseTypeDef",
-    {
-        "certificateArn": str,
-        "certificateId": str,
-        "certificatePem": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCustomMetricResponseTypeDef = TypedDict(
-    "CreateCustomMetricResponseTypeDef",
-    {
-        "metricName": str,
-        "metricArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDimensionResponseTypeDef = TypedDict(
-    "CreateDimensionResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDomainConfigurationResponseTypeDef = TypedDict(
-    "CreateDomainConfigurationResponseTypeDef",
-    {
-        "domainConfigurationName": str,
-        "domainConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDynamicThingGroupResponseTypeDef = TypedDict(
-    "CreateDynamicThingGroupResponseTypeDef",
-    {
-        "thingGroupName": str,
-        "thingGroupArn": str,
-        "thingGroupId": str,
-        "indexName": str,
-        "queryString": str,
-        "queryVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFleetMetricResponseTypeDef = TypedDict(
-    "CreateFleetMetricResponseTypeDef",
-    {
-        "metricName": str,
-        "metricArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateJobResponseTypeDef = TypedDict(
-    "CreateJobResponseTypeDef",
-    {
-        "jobArn": str,
-        "jobId": str,
-        "description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateJobTemplateResponseTypeDef = TypedDict(
-    "CreateJobTemplateResponseTypeDef",
-    {
-        "jobTemplateArn": str,
-        "jobTemplateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMitigationActionResponseTypeDef = TypedDict(
-    "CreateMitigationActionResponseTypeDef",
-    {
-        "actionArn": str,
-        "actionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateOTAUpdateResponseTypeDef = TypedDict(
-    "CreateOTAUpdateResponseTypeDef",
-    {
-        "otaUpdateId": str,
-        "awsIotJobId": str,
-        "otaUpdateArn": str,
-        "awsIotJobArn": str,
-        "otaUpdateStatus": OTAUpdateStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePolicyResponseTypeDef = TypedDict(
-    "CreatePolicyResponseTypeDef",
-    {
-        "policyName": str,
-        "policyArn": str,
-        "policyDocument": str,
-        "policyVersionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePolicyVersionResponseTypeDef = TypedDict(
-    "CreatePolicyVersionResponseTypeDef",
+UpdateRoleAliasResponseTypeDef = TypedDict(
+    "UpdateRoleAliasResponseTypeDef",
     {
-        "policyArn": str,
-        "policyDocument": str,
-        "policyVersionId": str,
-        "isDefaultVersion": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "roleAlias": str,
+        "roleAliasArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateProvisioningTemplateResponseTypeDef = TypedDict(
-    "CreateProvisioningTemplateResponseTypeDef",
+_RequiredUpdateScheduledAuditRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateScheduledAuditRequestRequestTypeDef",
     {
-        "templateArn": str,
-        "templateName": str,
-        "defaultVersionId": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "scheduledAuditName": str,
     },
 )
-
-CreateProvisioningTemplateVersionResponseTypeDef = TypedDict(
-    "CreateProvisioningTemplateVersionResponseTypeDef",
+_OptionalUpdateScheduledAuditRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateScheduledAuditRequestRequestTypeDef",
     {
-        "templateArn": str,
-        "templateName": str,
-        "versionId": int,
-        "isDefaultVersion": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "frequency": AuditFrequencyType,
+        "dayOfMonth": str,
+        "dayOfWeek": DayOfWeekType,
+        "targetCheckNames": Sequence[str],
     },
+    total=False,
 )
 
-CreateRoleAliasResponseTypeDef = TypedDict(
-    "CreateRoleAliasResponseTypeDef",
-    {
-        "roleAlias": str,
-        "roleAliasArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateScheduledAuditRequestRequestTypeDef(
+    _RequiredUpdateScheduledAuditRequestRequestTypeDef,
+    _OptionalUpdateScheduledAuditRequestRequestTypeDef,
+):
+    pass
 
-CreateScheduledAuditResponseTypeDef = TypedDict(
-    "CreateScheduledAuditResponseTypeDef",
+UpdateScheduledAuditResponseTypeDef = TypedDict(
+    "UpdateScheduledAuditResponseTypeDef",
     {
         "scheduledAuditArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSecurityProfileResponseTypeDef = TypedDict(
-    "CreateSecurityProfileResponseTypeDef",
-    {
-        "securityProfileName": str,
-        "securityProfileArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateStreamResponseTypeDef = TypedDict(
-    "CreateStreamResponseTypeDef",
+UpdateStreamResponseTypeDef = TypedDict(
+    "UpdateStreamResponseTypeDef",
     {
         "streamId": str,
         "streamArn": str,
         "description": str,
         "streamVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateThingGroupResponseTypeDef = TypedDict(
-    "CreateThingGroupResponseTypeDef",
+UpdateThingGroupResponseTypeDef = TypedDict(
+    "UpdateThingGroupResponseTypeDef",
     {
-        "thingGroupName": str,
-        "thingGroupArn": str,
-        "thingGroupId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "version": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateThingResponseTypeDef = TypedDict(
-    "CreateThingResponseTypeDef",
+UpdateThingGroupsForThingRequestRequestTypeDef = TypedDict(
+    "UpdateThingGroupsForThingRequestRequestTypeDef",
     {
         "thingName": str,
-        "thingArn": str,
-        "thingId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "thingGroupsToAdd": Sequence[str],
+        "thingGroupsToRemove": Sequence[str],
+        "overrideDynamicGroups": bool,
     },
+    total=False,
 )
 
-CreateThingTypeResponseTypeDef = TypedDict(
-    "CreateThingTypeResponseTypeDef",
+UpdateTopicRuleDestinationRequestRequestTypeDef = TypedDict(
+    "UpdateTopicRuleDestinationRequestRequestTypeDef",
     {
-        "thingTypeName": str,
-        "thingTypeArn": str,
-        "thingTypeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "arn": str,
+        "status": TopicRuleDestinationStatusType,
     },
 )
 
-DescribeCustomMetricResponseTypeDef = TypedDict(
-    "DescribeCustomMetricResponseTypeDef",
+ValidationErrorTypeDef = TypedDict(
+    "ValidationErrorTypeDef",
     {
-        "metricName": str,
-        "metricArn": str,
-        "metricType": CustomMetricTypeType,
-        "displayName": str,
-        "creationDate": datetime,
-        "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "errorMessage": str,
     },
+    total=False,
 )
 
-DescribeDimensionResponseTypeDef = TypedDict(
-    "DescribeDimensionResponseTypeDef",
+AbortConfigTypeDef = TypedDict(
+    "AbortConfigTypeDef",
     {
-        "name": str,
-        "arn": str,
-        "type": Literal["TOPIC_FILTER"],
-        "stringValues": List[str],
-        "creationDate": datetime,
-        "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "criteriaList": Sequence[AbortCriteriaTypeDef],
     },
 )
 
-DescribeEndpointResponseTypeDef = TypedDict(
-    "DescribeEndpointResponseTypeDef",
+MetricDatumTypeDef = TypedDict(
+    "MetricDatumTypeDef",
     {
-        "endpointAddress": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "timestamp": datetime,
+        "value": MetricValueTypeDef,
     },
+    total=False,
 )
 
 DescribeFleetMetricResponseTypeDef = TypedDict(
     "DescribeFleetMetricResponseTypeDef",
     {
         "metricName": str,
         "queryString": str,
@@ -4889,502 +6425,115 @@
         "queryVersion": str,
         "indexName": str,
         "creationDate": datetime,
         "lastModifiedDate": datetime,
         "unit": FleetMetricUnitType,
         "version": int,
         "metricArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeIndexResponseTypeDef = TypedDict(
-    "DescribeIndexResponseTypeDef",
+_RequiredUpdateFleetMetricRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateFleetMetricRequestRequestTypeDef",
     {
+        "metricName": str,
         "indexName": str,
-        "indexStatus": IndexStatusType,
-        "schema": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-DescribeProvisioningTemplateVersionResponseTypeDef = TypedDict(
-    "DescribeProvisioningTemplateVersionResponseTypeDef",
-    {
-        "versionId": int,
-        "creationDate": datetime,
-        "templateBody": str,
-        "isDefaultVersion": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeScheduledAuditResponseTypeDef = TypedDict(
-    "DescribeScheduledAuditResponseTypeDef",
-    {
-        "frequency": AuditFrequencyType,
-        "dayOfMonth": str,
-        "dayOfWeek": DayOfWeekType,
-        "targetCheckNames": List[str],
-        "scheduledAuditName": str,
-        "scheduledAuditArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeThingRegistrationTaskResponseTypeDef = TypedDict(
-    "DescribeThingRegistrationTaskResponseTypeDef",
-    {
-        "taskId": str,
-        "creationDate": datetime,
-        "lastModifiedDate": datetime,
-        "templateBody": str,
-        "inputFileBucket": str,
-        "inputFileKey": str,
-        "roleArn": str,
-        "status": StatusType,
-        "message": str,
-        "successCount": int,
-        "failureCount": int,
-        "percentageProgress": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeThingResponseTypeDef = TypedDict(
-    "DescribeThingResponseTypeDef",
-    {
-        "defaultClientId": str,
-        "thingName": str,
-        "thingId": str,
-        "thingArn": str,
-        "thingTypeName": str,
-        "attributes": Dict[str, str],
-        "version": int,
-        "billingGroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCardinalityResponseTypeDef = TypedDict(
-    "GetCardinalityResponseTypeDef",
-    {
-        "cardinality": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetJobDocumentResponseTypeDef = TypedDict(
-    "GetJobDocumentResponseTypeDef",
-    {
-        "document": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetLoggingOptionsResponseTypeDef = TypedDict(
-    "GetLoggingOptionsResponseTypeDef",
+_OptionalUpdateFleetMetricRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateFleetMetricRequestRequestTypeDef",
     {
-        "roleArn": str,
-        "logLevel": LogLevelType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "queryString": str,
+        "aggregationType": AggregationTypeTypeDef,
+        "period": int,
+        "aggregationField": str,
+        "description": str,
+        "queryVersion": str,
+        "unit": FleetMetricUnitType,
+        "expectedVersion": int,
     },
+    total=False,
 )
 
-GetPolicyResponseTypeDef = TypedDict(
-    "GetPolicyResponseTypeDef",
-    {
-        "policyName": str,
-        "policyArn": str,
-        "policyDocument": str,
-        "defaultVersionId": str,
-        "creationDate": datetime,
-        "lastModifiedDate": datetime,
-        "generationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateFleetMetricRequestRequestTypeDef(
+    _RequiredUpdateFleetMetricRequestRequestTypeDef, _OptionalUpdateFleetMetricRequestRequestTypeDef
+):
+    pass
 
-GetPolicyVersionResponseTypeDef = TypedDict(
-    "GetPolicyVersionResponseTypeDef",
+AllowedTypeDef = TypedDict(
+    "AllowedTypeDef",
     {
-        "policyArn": str,
-        "policyName": str,
-        "policyDocument": str,
-        "policyVersionId": str,
-        "isDefaultVersion": bool,
-        "creationDate": datetime,
-        "lastModifiedDate": datetime,
-        "generationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "policies": List[PolicyTypeDef],
     },
+    total=False,
 )
 
-GetRegistrationCodeResponseTypeDef = TypedDict(
-    "GetRegistrationCodeResponseTypeDef",
+ExplicitDenyTypeDef = TypedDict(
+    "ExplicitDenyTypeDef",
     {
-        "registrationCode": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "policies": List[PolicyTypeDef],
     },
+    total=False,
 )
 
-GetV2LoggingOptionsResponseTypeDef = TypedDict(
-    "GetV2LoggingOptionsResponseTypeDef",
+ImplicitDenyTypeDef = TypedDict(
+    "ImplicitDenyTypeDef",
     {
-        "roleArn": str,
-        "defaultLogLevel": LogLevelType,
-        "disableAllLogs": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "policies": List[PolicyTypeDef],
     },
+    total=False,
 )
 
 ListAttachedPoliciesResponseTypeDef = TypedDict(
     "ListAttachedPoliciesResponseTypeDef",
     {
         "policies": List[PolicyTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListCustomMetricsResponseTypeDef = TypedDict(
-    "ListCustomMetricsResponseTypeDef",
-    {
-        "metricNames": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDimensionsResponseTypeDef = TypedDict(
-    "ListDimensionsResponseTypeDef",
-    {
-        "dimensionNames": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListIndicesResponseTypeDef = TypedDict(
-    "ListIndicesResponseTypeDef",
-    {
-        "indexNames": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPoliciesResponseTypeDef = TypedDict(
     "ListPoliciesResponseTypeDef",
     {
         "policies": List[PolicyTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListPolicyPrincipalsResponseTypeDef = TypedDict(
-    "ListPolicyPrincipalsResponseTypeDef",
-    {
-        "principals": List[str],
-        "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPrincipalPoliciesResponseTypeDef = TypedDict(
     "ListPrincipalPoliciesResponseTypeDef",
     {
         "policies": List[PolicyTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListPrincipalThingsResponseTypeDef = TypedDict(
-    "ListPrincipalThingsResponseTypeDef",
-    {
-        "things": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListRoleAliasesResponseTypeDef = TypedDict(
-    "ListRoleAliasesResponseTypeDef",
-    {
-        "roleAliases": List[str],
-        "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTargetsForPolicyResponseTypeDef = TypedDict(
-    "ListTargetsForPolicyResponseTypeDef",
-    {
-        "targets": List[str],
-        "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListThingPrincipalsResponseTypeDef = TypedDict(
-    "ListThingPrincipalsResponseTypeDef",
-    {
-        "principals": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListThingRegistrationTaskReportsResponseTypeDef = TypedDict(
-    "ListThingRegistrationTaskReportsResponseTypeDef",
-    {
-        "resourceLinks": List[str],
-        "reportType": ReportTypeType,
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListThingRegistrationTasksResponseTypeDef = TypedDict(
-    "ListThingRegistrationTasksResponseTypeDef",
-    {
-        "taskIds": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListThingsInBillingGroupResponseTypeDef = TypedDict(
-    "ListThingsInBillingGroupResponseTypeDef",
-    {
-        "things": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListThingsInThingGroupResponseTypeDef = TypedDict(
-    "ListThingsInThingGroupResponseTypeDef",
-    {
-        "things": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterCACertificateResponseTypeDef = TypedDict(
-    "RegisterCACertificateResponseTypeDef",
-    {
-        "certificateArn": str,
-        "certificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterCertificateResponseTypeDef = TypedDict(
-    "RegisterCertificateResponseTypeDef",
-    {
-        "certificateArn": str,
-        "certificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterCertificateWithoutCAResponseTypeDef = TypedDict(
-    "RegisterCertificateWithoutCAResponseTypeDef",
-    {
-        "certificateArn": str,
-        "certificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterThingResponseTypeDef = TypedDict(
-    "RegisterThingResponseTypeDef",
-    {
-        "certificatePem": str,
-        "resourceArns": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SetDefaultAuthorizerResponseTypeDef = TypedDict(
-    "SetDefaultAuthorizerResponseTypeDef",
-    {
-        "authorizerName": str,
-        "authorizerArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartAuditMitigationActionsTaskResponseTypeDef = TypedDict(
-    "StartAuditMitigationActionsTaskResponseTypeDef",
-    {
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDetectMitigationActionsTaskResponseTypeDef = TypedDict(
-    "StartDetectMitigationActionsTaskResponseTypeDef",
-    {
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartOnDemandAuditTaskResponseTypeDef = TypedDict(
-    "StartOnDemandAuditTaskResponseTypeDef",
-    {
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartThingRegistrationTaskResponseTypeDef = TypedDict(
-    "StartThingRegistrationTaskResponseTypeDef",
-    {
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestInvokeAuthorizerResponseTypeDef = TypedDict(
-    "TestInvokeAuthorizerResponseTypeDef",
-    {
-        "isAuthenticated": bool,
-        "principalId": str,
-        "policyDocuments": List[str],
-        "refreshAfterInSeconds": int,
-        "disconnectAfterInSeconds": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TransferCertificateResponseTypeDef = TypedDict(
-    "TransferCertificateResponseTypeDef",
-    {
-        "transferredCertificateArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateAuthorizerResponseTypeDef = TypedDict(
-    "UpdateAuthorizerResponseTypeDef",
-    {
-        "authorizerName": str,
-        "authorizerArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateBillingGroupResponseTypeDef = TypedDict(
-    "UpdateBillingGroupResponseTypeDef",
-    {
-        "version": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateCustomMetricResponseTypeDef = TypedDict(
-    "UpdateCustomMetricResponseTypeDef",
-    {
-        "metricName": str,
-        "metricArn": str,
-        "metricType": CustomMetricTypeType,
-        "displayName": str,
-        "creationDate": datetime,
-        "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDimensionResponseTypeDef = TypedDict(
-    "UpdateDimensionResponseTypeDef",
-    {
-        "name": str,
-        "arn": str,
-        "type": Literal["TOPIC_FILTER"],
-        "stringValues": List[str],
-        "creationDate": datetime,
-        "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDomainConfigurationResponseTypeDef = TypedDict(
-    "UpdateDomainConfigurationResponseTypeDef",
-    {
-        "domainConfigurationName": str,
-        "domainConfigurationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDynamicThingGroupResponseTypeDef = TypedDict(
-    "UpdateDynamicThingGroupResponseTypeDef",
-    {
-        "version": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateMitigationActionResponseTypeDef = TypedDict(
-    "UpdateMitigationActionResponseTypeDef",
-    {
-        "actionArn": str,
-        "actionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateRoleAliasResponseTypeDef = TypedDict(
-    "UpdateRoleAliasResponseTypeDef",
-    {
-        "roleAlias": str,
-        "roleAliasArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateScheduledAuditResponseTypeDef = TypedDict(
-    "UpdateScheduledAuditResponseTypeDef",
+_RequiredAssetPropertyValueTypeDef = TypedDict(
+    "_RequiredAssetPropertyValueTypeDef",
     {
-        "scheduledAuditArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "value": AssetPropertyVariantTypeDef,
+        "timestamp": AssetPropertyTimestampTypeDef,
     },
 )
-
-UpdateStreamResponseTypeDef = TypedDict(
-    "UpdateStreamResponseTypeDef",
+_OptionalAssetPropertyValueTypeDef = TypedDict(
+    "_OptionalAssetPropertyValueTypeDef",
     {
-        "streamId": str,
-        "streamArn": str,
-        "description": str,
-        "streamVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "quality": str,
     },
+    total=False,
 )
 
-UpdateThingGroupResponseTypeDef = TypedDict(
-    "UpdateThingGroupResponseTypeDef",
-    {
-        "version": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class AssetPropertyValueTypeDef(
+    _RequiredAssetPropertyValueTypeDef, _OptionalAssetPropertyValueTypeDef
+):
+    pass
 
 _RequiredCreateThingRequestRequestTypeDef = TypedDict(
     "_RequiredCreateThingRequestRequestTypeDef",
     {
         "thingName": str,
     },
 )
@@ -5435,24 +6584,24 @@
     pass
 
 ListAuditMitigationActionsExecutionsResponseTypeDef = TypedDict(
     "ListAuditMitigationActionsExecutionsResponseTypeDef",
     {
         "actionsExecutions": List[AuditMitigationActionExecutionMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAuditMitigationActionsTasksResponseTypeDef = TypedDict(
     "ListAuditMitigationActionsTasksResponseTypeDef",
     {
         "tasks": List[AuditMitigationActionsTaskMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartAuditMitigationActionsTaskRequestRequestTypeDef = TypedDict(
     "StartAuditMitigationActionsTaskRequestRequestTypeDef",
     {
         "taskId": str,
@@ -5466,15 +6615,15 @@
     "DescribeAccountAuditConfigurationResponseTypeDef",
     {
         "roleArn": str,
         "auditNotificationTargetConfigurations": Dict[
             Literal["SNS"], AuditNotificationTargetTypeDef
         ],
         "auditCheckConfigurations": Dict[str, AuditCheckConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAccountAuditConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateAccountAuditConfigurationRequestRequestTypeDef",
     {
         "roleArn": str,
@@ -5487,15 +6636,15 @@
 )
 
 ListAuditTasksResponseTypeDef = TypedDict(
     "ListAuditTasksResponseTypeDef",
     {
         "tasks": List[AuditTaskMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTestAuthorizationRequestRequestTypeDef = TypedDict(
     "_RequiredTestAuthorizationRequestRequestTypeDef",
     {
         "authInfos": Sequence[AuthInfoTypeDef],
@@ -5514,58 +6663,36 @@
 )
 
 class TestAuthorizationRequestRequestTypeDef(
     _RequiredTestAuthorizationRequestRequestTypeDef, _OptionalTestAuthorizationRequestRequestTypeDef
 ):
     pass
 
-_RequiredUpdateDomainConfigurationRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateDomainConfigurationRequestRequestTypeDef",
-    {
-        "domainConfigurationName": str,
-    },
-)
-_OptionalUpdateDomainConfigurationRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateDomainConfigurationRequestRequestTypeDef",
-    {
-        "authorizerConfig": AuthorizerConfigTypeDef,
-        "domainConfigurationStatus": DomainConfigurationStatusType,
-        "removeAuthorizerConfig": bool,
-    },
-    total=False,
-)
-
-class UpdateDomainConfigurationRequestRequestTypeDef(
-    _RequiredUpdateDomainConfigurationRequestRequestTypeDef,
-    _OptionalUpdateDomainConfigurationRequestRequestTypeDef,
-):
-    pass
-
 DescribeAuthorizerResponseTypeDef = TypedDict(
     "DescribeAuthorizerResponseTypeDef",
     {
         "authorizerDescription": AuthorizerDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDefaultAuthorizerResponseTypeDef = TypedDict(
     "DescribeDefaultAuthorizerResponseTypeDef",
     {
         "authorizerDescription": AuthorizerDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAuthorizersResponseTypeDef = TypedDict(
     "ListAuthorizersResponseTypeDef",
     {
         "authorizers": List[AuthorizerSummaryTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AwsJobAbortConfigTypeDef = TypedDict(
     "AwsJobAbortConfigTypeDef",
     {
         "abortCriteriaList": Sequence[AwsJobAbortCriteriaTypeDef],
@@ -5596,15 +6723,15 @@
 )
 
 GetBehaviorModelTrainingSummariesResponseTypeDef = TypedDict(
     "GetBehaviorModelTrainingSummariesResponseTypeDef",
     {
         "summaries": List[BehaviorModelTrainingSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMetricToRetainTypeDef = TypedDict(
     "_RequiredMetricToRetainTypeDef",
     {
         "metric": str,
@@ -5626,15 +6753,15 @@
     {
         "billingGroupName": str,
         "billingGroupId": str,
         "billingGroupArn": str,
         "version": int,
         "billingGroupProperties": BillingGroupPropertiesTypeDef,
         "billingGroupMetadata": BillingGroupMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateBillingGroupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateBillingGroupRequestRequestTypeDef",
     {
         "billingGroupName": str,
@@ -5656,15 +6783,15 @@
     pass
 
 GetBucketsAggregationResponseTypeDef = TypedDict(
     "GetBucketsAggregationResponseTypeDef",
     {
         "totalCount": int,
         "buckets": List[BucketTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BucketsAggregationTypeTypeDef = TypedDict(
     "BucketsAggregationTypeTypeDef",
     {
         "termsAggregation": TermsAggregationTypeDef,
@@ -5692,15 +6819,15 @@
 )
 
 ListCACertificatesResponseTypeDef = TypedDict(
     "ListCACertificatesResponseTypeDef",
     {
         "certificates": List[CACertificateTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CertificateDescriptionTypeDef = TypedDict(
     "CertificateDescriptionTypeDef",
     {
         "certificateArn": str,
@@ -5722,24 +6849,24 @@
 )
 
 ListCertificatesByCAResponseTypeDef = TypedDict(
     "ListCertificatesByCAResponseTypeDef",
     {
         "certificates": List[CertificateTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCertificatesResponseTypeDef = TypedDict(
     "ListCertificatesResponseTypeDef",
     {
         "certificates": List[CertificateTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CustomCodeSigningTypeDef = TypedDict(
     "CustomCodeSigningTypeDef",
     {
         "signature": CodeSigningSignatureTypeDef,
@@ -5752,15 +6879,15 @@
 
 DescribeEventConfigurationsResponseTypeDef = TypedDict(
     "DescribeEventConfigurationsResponseTypeDef",
     {
         "eventConfigurations": Dict[EventTypeType, ConfigurationTypeDef],
         "creationDate": datetime,
         "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEventConfigurationsRequestRequestTypeDef = TypedDict(
     "UpdateEventConfigurationsRequestRequestTypeDef",
     {
         "eventConfigurations": Mapping[EventTypeType, ConfigurationTypeDef],
@@ -5855,39 +6982,14 @@
 )
 
 class CreateDimensionRequestRequestTypeDef(
     _RequiredCreateDimensionRequestRequestTypeDef, _OptionalCreateDimensionRequestRequestTypeDef
 ):
     pass
 
-_RequiredCreateDomainConfigurationRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateDomainConfigurationRequestRequestTypeDef",
-    {
-        "domainConfigurationName": str,
-    },
-)
-_OptionalCreateDomainConfigurationRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateDomainConfigurationRequestRequestTypeDef",
-    {
-        "domainName": str,
-        "serverCertificateArns": Sequence[str],
-        "validationCertificateArn": str,
-        "authorizerConfig": AuthorizerConfigTypeDef,
-        "serviceType": ServiceTypeType,
-        "tags": Sequence[TagTypeDef],
-    },
-    total=False,
-)
-
-class CreateDomainConfigurationRequestRequestTypeDef(
-    _RequiredCreateDomainConfigurationRequestRequestTypeDef,
-    _OptionalCreateDomainConfigurationRequestRequestTypeDef,
-):
-    pass
-
 _RequiredCreateFleetMetricRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFleetMetricRequestRequestTypeDef",
     {
         "metricName": str,
         "queryString": str,
         "aggregationType": AggregationTypeTypeDef,
         "period": int,
@@ -5977,45 +7079,105 @@
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Sequence[TagTypeDef],
     },
 )
 
+_RequiredCreateDomainConfigurationRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateDomainConfigurationRequestRequestTypeDef",
+    {
+        "domainConfigurationName": str,
+    },
+)
+_OptionalCreateDomainConfigurationRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateDomainConfigurationRequestRequestTypeDef",
+    {
+        "domainName": str,
+        "serverCertificateArns": Sequence[str],
+        "validationCertificateArn": str,
+        "authorizerConfig": AuthorizerConfigTypeDef,
+        "serviceType": ServiceTypeType,
+        "tags": Sequence[TagTypeDef],
+        "tlsConfig": TlsConfigTypeDef,
+    },
+    total=False,
+)
+
+class CreateDomainConfigurationRequestRequestTypeDef(
+    _RequiredCreateDomainConfigurationRequestRequestTypeDef,
+    _OptionalCreateDomainConfigurationRequestRequestTypeDef,
+):
+    pass
+
+_RequiredUpdateDomainConfigurationRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateDomainConfigurationRequestRequestTypeDef",
+    {
+        "domainConfigurationName": str,
+    },
+)
+_OptionalUpdateDomainConfigurationRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateDomainConfigurationRequestRequestTypeDef",
+    {
+        "authorizerConfig": AuthorizerConfigTypeDef,
+        "domainConfigurationStatus": DomainConfigurationStatusType,
+        "removeAuthorizerConfig": bool,
+        "tlsConfig": TlsConfigTypeDef,
+    },
+    total=False,
+)
+
+class UpdateDomainConfigurationRequestRequestTypeDef(
+    _RequiredUpdateDomainConfigurationRequestRequestTypeDef,
+    _OptionalUpdateDomainConfigurationRequestRequestTypeDef,
+):
+    pass
+
+SchedulingConfigTypeDef = TypedDict(
+    "SchedulingConfigTypeDef",
+    {
+        "startTime": str,
+        "endTime": str,
+        "endBehavior": JobEndBehaviorType,
+        "maintenanceWindows": Sequence[MaintenanceWindowTypeDef],
+    },
+    total=False,
+)
+
 CreateKeysAndCertificateResponseTypeDef = TypedDict(
     "CreateKeysAndCertificateResponseTypeDef",
     {
         "certificateArn": str,
         "certificateId": str,
         "certificatePem": str,
         "keyPair": KeyPairTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateProvisioningClaimResponseTypeDef = TypedDict(
     "CreateProvisioningClaimResponseTypeDef",
     {
         "certificateId": str,
         "certificatePem": str,
         "keyPair": KeyPairTypeDef,
         "expiration": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateProvisioningTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateProvisioningTemplateRequestRequestTypeDef",
     {
         "templateName": str,
@@ -6051,15 +7213,15 @@
         "lastModifiedDate": datetime,
         "defaultVersionId": int,
         "templateBody": str,
         "enabled": bool,
         "provisioningRoleArn": str,
         "preProvisioningHook": ProvisioningHookTypeDef,
         "type": TemplateTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateProvisioningTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateProvisioningTemplateRequestRequestTypeDef",
     {
         "templateName": str,
@@ -6109,15 +7271,15 @@
     {
         "taskStatus": AuditTaskStatusType,
         "taskType": AuditTaskTypeType,
         "taskStartTime": datetime,
         "taskStatistics": TaskStatisticsTypeDef,
         "scheduledAuditName": str,
         "auditDetails": Dict[str, AuditCheckDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterCACertificateRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterCACertificateRequestRequestTypeDef",
     {
         "caCertificate": str,
@@ -6173,49 +7335,50 @@
         "domainName": str,
         "serverCertificates": List[ServerCertificateSummaryTypeDef],
         "authorizerConfig": AuthorizerConfigTypeDef,
         "domainConfigurationStatus": DomainConfigurationStatusType,
         "serviceType": ServiceTypeType,
         "domainType": DomainTypeType,
         "lastStatusChangeDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "tlsConfig": TlsConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeManagedJobTemplateResponseTypeDef = TypedDict(
     "DescribeManagedJobTemplateResponseTypeDef",
     {
         "templateName": str,
         "templateArn": str,
         "description": str,
         "templateVersion": str,
         "environments": List[str],
         "documentParameters": List[DocumentParameterTypeDef],
         "document": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRoleAliasResponseTypeDef = TypedDict(
     "DescribeRoleAliasResponseTypeDef",
     {
         "roleAliasDescription": RoleAliasDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeThingTypeResponseTypeDef = TypedDict(
     "DescribeThingTypeResponseTypeDef",
     {
         "thingTypeName": str,
         "thingTypeId": str,
         "thingTypeArn": str,
         "thingTypeProperties": ThingTypePropertiesTypeDef,
         "thingTypeMetadata": ThingTypeMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ThingTypeDefinitionTypeDef = TypedDict(
     "ThingTypeDefinitionTypeDef",
     {
         "thingTypeName": str,
@@ -6235,15 +7398,15 @@
 )
 
 ListDetectMitigationActionsExecutionsResponseTypeDef = TypedDict(
     "ListDetectMitigationActionsExecutionsResponseTypeDef",
     {
         "actionsExecutions": List[DetectMitigationActionExecutionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartDetectMitigationActionsTaskRequestRequestTypeDef = TypedDict(
     "_RequiredStartDetectMitigationActionsTaskRequestRequestTypeDef",
     {
         "taskId": str,
@@ -6269,15 +7432,15 @@
     pass
 
 ListDomainConfigurationsResponseTypeDef = TypedDict(
     "ListDomainConfigurationsResponseTypeDef",
     {
         "domainConfigurations": List[DomainConfigurationSummaryTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DynamoDBv2ActionTypeDef = TypedDict(
     "DynamoDBv2ActionTypeDef",
     {
         "roleArn": str,
@@ -6285,15 +7448,15 @@
     },
 )
 
 GetEffectivePoliciesResponseTypeDef = TypedDict(
     "GetEffectivePoliciesResponseTypeDef",
     {
         "effectivePolicies": List[EffectivePolicyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExponentialRolloutRateTypeDef = TypedDict(
     "ExponentialRolloutRateTypeDef",
     {
         "baseRatePerMinute": int,
@@ -6341,843 +7504,75 @@
 )
 
 ListFleetMetricsResponseTypeDef = TypedDict(
     "ListFleetMetricsResponseTypeDef",
     {
         "fleetMetrics": List[FleetMetricNameAndArnTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef = (
-    TypedDict(
-        "GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef",
-        {
-            "securityProfileName": str,
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-ListActiveViolationsRequestListActiveViolationsPaginateTypeDef = TypedDict(
-    "ListActiveViolationsRequestListActiveViolationsPaginateTypeDef",
-    {
-        "thingName": str,
-        "securityProfileName": str,
-        "behaviorCriteriaType": BehaviorCriteriaTypeType,
-        "listSuppressedAlerts": bool,
-        "verificationState": VerificationStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef",
-    {
-        "target": str,
-    },
-)
-_OptionalListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef",
-    {
-        "recursive": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef(
-    _RequiredListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef,
-    _OptionalListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef,
-):
-    pass
-
-_RequiredListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef = TypedDict(
-    "_RequiredListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef",
+GetPackageConfigurationResponseTypeDef = TypedDict(
+    "GetPackageConfigurationResponseTypeDef",
     {
-        "taskId": str,
-        "findingId": str,
+        "versionUpdateByJobsConfig": VersionUpdateByJobsConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef = TypedDict(
-    "_OptionalListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef",
-    {
-        "actionStatus": AuditMitigationActionsExecutionStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef(
-    _RequiredListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef,
-    _OptionalListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef,
-):
-    pass
 
-_RequiredListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef = TypedDict(
-    "_RequiredListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef",
-    {
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-    },
-)
-_OptionalListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef = TypedDict(
-    "_OptionalListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef",
+UpdatePackageConfigurationRequestRequestTypeDef = TypedDict(
+    "UpdatePackageConfigurationRequestRequestTypeDef",
     {
-        "auditTaskId": str,
-        "findingId": str,
-        "taskStatus": AuditMitigationActionsTaskStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "versionUpdateByJobsConfig": VersionUpdateByJobsConfigTypeDef,
+        "clientToken": str,
     },
     total=False,
 )
 
-class ListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef(
-    _RequiredListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef,
-    _OptionalListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef,
-):
-    pass
-
-_RequiredListAuditTasksRequestListAuditTasksPaginateTypeDef = TypedDict(
-    "_RequiredListAuditTasksRequestListAuditTasksPaginateTypeDef",
-    {
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-    },
-)
-_OptionalListAuditTasksRequestListAuditTasksPaginateTypeDef = TypedDict(
-    "_OptionalListAuditTasksRequestListAuditTasksPaginateTypeDef",
-    {
-        "taskType": AuditTaskTypeType,
-        "taskStatus": AuditTaskStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAuditTasksRequestListAuditTasksPaginateTypeDef(
-    _RequiredListAuditTasksRequestListAuditTasksPaginateTypeDef,
-    _OptionalListAuditTasksRequestListAuditTasksPaginateTypeDef,
-):
-    pass
-
-ListAuthorizersRequestListAuthorizersPaginateTypeDef = TypedDict(
-    "ListAuthorizersRequestListAuthorizersPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "status": AuthorizerStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListBillingGroupsRequestListBillingGroupsPaginateTypeDef = TypedDict(
-    "ListBillingGroupsRequestListBillingGroupsPaginateTypeDef",
-    {
-        "namePrefixFilter": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCACertificatesRequestListCACertificatesPaginateTypeDef = TypedDict(
-    "ListCACertificatesRequestListCACertificatesPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "templateName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListCertificatesByCARequestListCertificatesByCAPaginateTypeDef = TypedDict(
-    "_RequiredListCertificatesByCARequestListCertificatesByCAPaginateTypeDef",
-    {
-        "caCertificateId": str,
-    },
-)
-_OptionalListCertificatesByCARequestListCertificatesByCAPaginateTypeDef = TypedDict(
-    "_OptionalListCertificatesByCARequestListCertificatesByCAPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListCertificatesByCARequestListCertificatesByCAPaginateTypeDef(
-    _RequiredListCertificatesByCARequestListCertificatesByCAPaginateTypeDef,
-    _OptionalListCertificatesByCARequestListCertificatesByCAPaginateTypeDef,
-):
-    pass
-
-ListCertificatesRequestListCertificatesPaginateTypeDef = TypedDict(
-    "ListCertificatesRequestListCertificatesPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCustomMetricsRequestListCustomMetricsPaginateTypeDef = TypedDict(
-    "ListCustomMetricsRequestListCustomMetricsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef = TypedDict(
-    "ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef",
-    {
-        "taskId": str,
-        "violationId": str,
-        "thingName": str,
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef = TypedDict(
-    "_RequiredListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef",
-    {
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-    },
-)
-_OptionalListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef = TypedDict(
-    "_OptionalListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef(
-    _RequiredListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef,
-    _OptionalListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef,
-):
-    pass
-
-ListDimensionsRequestListDimensionsPaginateTypeDef = TypedDict(
-    "ListDimensionsRequestListDimensionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef = TypedDict(
-    "ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef",
-    {
-        "serviceType": ServiceTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListFleetMetricsRequestListFleetMetricsPaginateTypeDef = TypedDict(
-    "ListFleetMetricsRequestListFleetMetricsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListIndicesRequestListIndicesPaginateTypeDef = TypedDict(
-    "ListIndicesRequestListIndicesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef = TypedDict(
-    "_RequiredListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef",
-    {
-        "jobId": str,
-    },
-)
-_OptionalListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef = TypedDict(
-    "_OptionalListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef",
-    {
-        "status": JobExecutionStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef(
-    _RequiredListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef,
-    _OptionalListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef,
-):
-    pass
-
-_RequiredListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef = TypedDict(
-    "_RequiredListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef",
-    {
-        "thingName": str,
-    },
-)
-_OptionalListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef = TypedDict(
-    "_OptionalListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef",
-    {
-        "status": JobExecutionStatusType,
-        "namespaceId": str,
-        "jobId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef(
-    _RequiredListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef,
-    _OptionalListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef,
-):
-    pass
-
-ListJobTemplatesRequestListJobTemplatesPaginateTypeDef = TypedDict(
-    "ListJobTemplatesRequestListJobTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListJobsRequestListJobsPaginateTypeDef = TypedDict(
-    "ListJobsRequestListJobsPaginateTypeDef",
-    {
-        "status": JobStatusType,
-        "targetSelection": TargetSelectionType,
-        "thingGroupName": str,
-        "thingGroupId": str,
-        "namespaceId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListMetricValuesRequestListMetricValuesPaginateTypeDef = TypedDict(
-    "_RequiredListMetricValuesRequestListMetricValuesPaginateTypeDef",
-    {
-        "thingName": str,
-        "metricName": str,
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-    },
-)
-_OptionalListMetricValuesRequestListMetricValuesPaginateTypeDef = TypedDict(
-    "_OptionalListMetricValuesRequestListMetricValuesPaginateTypeDef",
-    {
-        "dimensionName": str,
-        "dimensionValueOperator": DimensionValueOperatorType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListMetricValuesRequestListMetricValuesPaginateTypeDef(
-    _RequiredListMetricValuesRequestListMetricValuesPaginateTypeDef,
-    _OptionalListMetricValuesRequestListMetricValuesPaginateTypeDef,
-):
-    pass
-
-ListMitigationActionsRequestListMitigationActionsPaginateTypeDef = TypedDict(
-    "ListMitigationActionsRequestListMitigationActionsPaginateTypeDef",
-    {
-        "actionType": MitigationActionTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef = TypedDict(
-    "ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef",
-    {
-        "otaUpdateStatus": OTAUpdateStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef = TypedDict(
-    "ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
-    "ListPoliciesRequestListPoliciesPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef = TypedDict(
-    "_RequiredListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef",
-    {
-        "policyName": str,
-    },
-)
-_OptionalListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef = TypedDict(
-    "_OptionalListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef(
-    _RequiredListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef,
-    _OptionalListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef,
-):
-    pass
-
-_RequiredListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef",
-    {
-        "principal": str,
-    },
-)
-_OptionalListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef(
-    _RequiredListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef,
-    _OptionalListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef,
-):
-    pass
-
-_RequiredListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef = TypedDict(
-    "_RequiredListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef",
-    {
-        "principal": str,
-    },
-)
-_OptionalListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef = TypedDict(
-    "_OptionalListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef(
-    _RequiredListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef,
-    _OptionalListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef,
-):
-    pass
-
-_RequiredListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef",
-    {
-        "templateName": str,
-    },
-)
-_OptionalListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef(
-    _RequiredListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef,
-    _OptionalListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef,
-):
-    pass
-
-ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef = TypedDict(
-    "ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRoleAliasesRequestListRoleAliasesPaginateTypeDef = TypedDict(
-    "ListRoleAliasesRequestListRoleAliasesPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef = TypedDict(
-    "ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef = (
-    TypedDict(
-        "_RequiredListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef",
-        {
-            "securityProfileTargetArn": str,
-        },
-    )
-)
-_OptionalListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef = (
-    TypedDict(
-        "_OptionalListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef",
-        {
-            "recursive": bool,
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-class ListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef(
-    _RequiredListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef,
-    _OptionalListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef,
-):
-    pass
-
-ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef = TypedDict(
-    "ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef",
-    {
-        "dimensionName": str,
-        "metricName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListStreamsRequestListStreamsPaginateTypeDef = TypedDict(
-    "ListStreamsRequestListStreamsPaginateTypeDef",
-    {
-        "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
-    "_RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
-    {
-        "policyName": str,
-    },
-)
-_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef = TypedDict(
-    "_OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef(
-    _RequiredListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
-    _OptionalListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
-):
-    pass
-
-_RequiredListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef = (
-    TypedDict(
-        "_RequiredListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef",
-        {
-            "securityProfileName": str,
-        },
-    )
-)
-_OptionalListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef = (
-    TypedDict(
-        "_OptionalListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef",
-        {
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-class ListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef(
-    _RequiredListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef,
-    _OptionalListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef,
-):
-    pass
-
-_RequiredListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef = TypedDict(
-    "_RequiredListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef",
-    {
-        "thingName": str,
-    },
-)
-_OptionalListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef = TypedDict(
-    "_OptionalListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef(
-    _RequiredListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef,
-    _OptionalListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef,
-):
-    pass
-
-ListThingGroupsRequestListThingGroupsPaginateTypeDef = TypedDict(
-    "ListThingGroupsRequestListThingGroupsPaginateTypeDef",
-    {
-        "parentGroup": str,
-        "namePrefixFilter": str,
-        "recursive": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef = TypedDict(
-    "_RequiredListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef",
-    {
-        "thingName": str,
-    },
-)
-_OptionalListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef = TypedDict(
-    "_OptionalListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef(
-    _RequiredListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef,
-    _OptionalListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef,
-):
-    pass
-
-_RequiredListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef = TypedDict(
-    "_RequiredListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef",
-    {
-        "taskId": str,
-        "reportType": ReportTypeType,
-    },
-)
-_OptionalListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef = TypedDict(
-    "_OptionalListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef(
-    _RequiredListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef,
-    _OptionalListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef,
-):
-    pass
-
-ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef = TypedDict(
-    "ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef",
-    {
-        "status": StatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListThingTypesRequestListThingTypesPaginateTypeDef = TypedDict(
-    "ListThingTypesRequestListThingTypesPaginateTypeDef",
-    {
-        "thingTypeName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef = TypedDict(
-    "_RequiredListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef",
-    {
-        "billingGroupName": str,
-    },
-)
-_OptionalListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef = TypedDict(
-    "_OptionalListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef(
-    _RequiredListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef,
-    _OptionalListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef,
-):
-    pass
-
-_RequiredListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef = TypedDict(
-    "_RequiredListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef",
-    {
-        "thingGroupName": str,
-    },
-)
-_OptionalListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef = TypedDict(
-    "_OptionalListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef",
-    {
-        "recursive": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef(
-    _RequiredListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef,
-    _OptionalListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef,
-):
-    pass
-
-ListThingsRequestListThingsPaginateTypeDef = TypedDict(
-    "ListThingsRequestListThingsPaginateTypeDef",
-    {
-        "attributeName": str,
-        "attributeValue": str,
-        "thingTypeName": str,
-        "usePrefixAttributeValue": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef = TypedDict(
-    "ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTopicRulesRequestListTopicRulesPaginateTypeDef = TypedDict(
-    "ListTopicRulesRequestListTopicRulesPaginateTypeDef",
-    {
-        "topic": str,
-        "ruleDisabled": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef = TypedDict(
-    "ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef",
-    {
-        "targetType": LogTargetTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListViolationEventsRequestListViolationEventsPaginateTypeDef = TypedDict(
-    "_RequiredListViolationEventsRequestListViolationEventsPaginateTypeDef",
-    {
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-    },
-)
-_OptionalListViolationEventsRequestListViolationEventsPaginateTypeDef = TypedDict(
-    "_OptionalListViolationEventsRequestListViolationEventsPaginateTypeDef",
-    {
-        "thingName": str,
-        "securityProfileName": str,
-        "behaviorCriteriaType": BehaviorCriteriaTypeType,
-        "listSuppressedAlerts": bool,
-        "verificationState": VerificationStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListViolationEventsRequestListViolationEventsPaginateTypeDef(
-    _RequiredListViolationEventsRequestListViolationEventsPaginateTypeDef,
-    _OptionalListViolationEventsRequestListViolationEventsPaginateTypeDef,
-):
-    pass
-
 GetPercentilesResponseTypeDef = TypedDict(
     "GetPercentilesResponseTypeDef",
     {
         "percentiles": List[PercentPairTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStatisticsResponseTypeDef = TypedDict(
     "GetStatisticsResponseTypeDef",
     {
         "statistics": StatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBillingGroupsResponseTypeDef = TypedDict(
     "ListBillingGroupsResponseTypeDef",
     {
         "billingGroups": List[GroupNameAndArnTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListThingGroupsForThingResponseTypeDef = TypedDict(
     "ListThingGroupsForThingResponseTypeDef",
     {
         "thingGroups": List[GroupNameAndArnTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListThingGroupsResponseTypeDef = TypedDict(
     "ListThingGroupsResponseTypeDef",
     {
         "thingGroups": List[GroupNameAndArnTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ThingGroupMetadataTypeDef = TypedDict(
     "ThingGroupMetadataTypeDef",
     {
         "parentGroupName": str,
@@ -7263,122 +7658,140 @@
 )
 
 ListJobsResponseTypeDef = TypedDict(
     "ListJobsResponseTypeDef",
     {
         "jobs": List[JobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobTemplatesResponseTypeDef = TypedDict(
     "ListJobTemplatesResponseTypeDef",
     {
         "jobTemplates": List[JobTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListManagedJobTemplatesResponseTypeDef = TypedDict(
     "ListManagedJobTemplatesResponseTypeDef",
     {
         "managedJobTemplates": List[ManagedJobTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMitigationActionsResponseTypeDef = TypedDict(
     "ListMitigationActionsResponseTypeDef",
     {
         "actionIdentifiers": List[MitigationActionIdentifierTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOTAUpdatesResponseTypeDef = TypedDict(
     "ListOTAUpdatesResponseTypeDef",
     {
         "otaUpdates": List[OTAUpdateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOutgoingCertificatesResponseTypeDef = TypedDict(
     "ListOutgoingCertificatesResponseTypeDef",
     {
         "outgoingCertificates": List[OutgoingCertificateTypeDef],
         "nextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListPackageVersionsResponseTypeDef = TypedDict(
+    "ListPackageVersionsResponseTypeDef",
+    {
+        "packageVersionSummaries": List[PackageVersionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListPackagesResponseTypeDef = TypedDict(
+    "ListPackagesResponseTypeDef",
+    {
+        "packageSummaries": List[PackageSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPolicyVersionsResponseTypeDef = TypedDict(
     "ListPolicyVersionsResponseTypeDef",
     {
         "policyVersions": List[PolicyVersionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProvisioningTemplateVersionsResponseTypeDef = TypedDict(
     "ListProvisioningTemplateVersionsResponseTypeDef",
     {
         "versions": List[ProvisioningTemplateVersionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProvisioningTemplatesResponseTypeDef = TypedDict(
     "ListProvisioningTemplatesResponseTypeDef",
     {
         "templates": List[ProvisioningTemplateSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListScheduledAuditsResponseTypeDef = TypedDict(
     "ListScheduledAuditsResponseTypeDef",
     {
         "scheduledAudits": List[ScheduledAuditMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSecurityProfilesResponseTypeDef = TypedDict(
     "ListSecurityProfilesResponseTypeDef",
     {
         "securityProfileIdentifiers": List[SecurityProfileIdentifierTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamsResponseTypeDef = TypedDict(
     "ListStreamsResponseTypeDef",
     {
         "streams": List[StreamSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTargetsForSecurityProfileResponseTypeDef = TypedDict(
     "ListTargetsForSecurityProfileResponseTypeDef",
     {
         "securityProfileTargets": List[SecurityProfileTargetTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SecurityProfileTargetMappingTypeDef = TypedDict(
     "SecurityProfileTargetMappingTypeDef",
     {
         "securityProfileIdentifier": SecurityProfileIdentifierTypeDef,
@@ -7388,24 +7801,24 @@
 )
 
 ListThingsResponseTypeDef = TypedDict(
     "ListThingsResponseTypeDef",
     {
         "things": List[ThingAttributeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTopicRulesResponseTypeDef = TypedDict(
     "ListTopicRulesResponseTypeDef",
     {
         "rules": List[TopicRuleListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredLocationActionTypeDef = TypedDict(
     "_RequiredLocationActionTypeDef",
     {
         "roleArn": str,
@@ -7590,24 +8003,24 @@
 )
 
 ValidateSecurityProfileBehaviorsResponseTypeDef = TypedDict(
     "ValidateSecurityProfileBehaviorsResponseTypeDef",
     {
         "valid": bool,
         "validationErrors": List[ValidationErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMetricValuesResponseTypeDef = TypedDict(
     "ListMetricValuesResponseTypeDef",
     {
         "metricDatumList": List[MetricDatumTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeniedTypeDef = TypedDict(
     "DeniedTypeDef",
     {
         "implicitDeny": ImplicitDenyTypeDef,
@@ -7780,32 +8193,32 @@
     pass
 
 DescribeCACertificateResponseTypeDef = TypedDict(
     "DescribeCACertificateResponseTypeDef",
     {
         "certificateDescription": CACertificateDescriptionTypeDef,
         "registrationConfig": RegistrationConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCertificateResponseTypeDef = TypedDict(
     "DescribeCertificateResponseTypeDef",
     {
         "certificateDescription": CertificateDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListThingTypesResponseTypeDef = TypedDict(
     "ListThingTypesResponseTypeDef",
     {
         "thingTypes": List[ThingTypeDefinitionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartSigningJobParameterTypeDef = TypedDict(
     "StartSigningJobParameterTypeDef",
     {
         "signingProfileParameter": SigningProfileParameterTypeDef,
@@ -7891,15 +8304,15 @@
         "version": int,
         "thingGroupProperties": ThingGroupPropertiesTypeDef,
         "thingGroupMetadata": ThingGroupMetadataTypeDef,
         "indexName": str,
         "queryString": str,
         "queryVersion": str,
         "status": DynamicGroupStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredHttpActionTypeDef = TypedDict(
     "_RequiredHttpActionTypeDef",
     {
         "url": str,
@@ -7919,15 +8332,15 @@
     pass
 
 GetIndexingConfigurationResponseTypeDef = TypedDict(
     "GetIndexingConfigurationResponseTypeDef",
     {
         "thingIndexingConfiguration": ThingIndexingConfigurationTypeDef,
         "thingGroupIndexingConfiguration": ThingGroupIndexingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateIndexingConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateIndexingConfigurationRequestRequestTypeDef",
     {
         "thingIndexingConfiguration": ThingIndexingConfigurationTypeDef,
@@ -7936,51 +8349,51 @@
     total=False,
 )
 
 DescribeJobExecutionResponseTypeDef = TypedDict(
     "DescribeJobExecutionResponseTypeDef",
     {
         "execution": JobExecutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobExecutionsForJobResponseTypeDef = TypedDict(
     "ListJobExecutionsForJobResponseTypeDef",
     {
         "executionSummaries": List[JobExecutionSummaryForJobTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobExecutionsForThingResponseTypeDef = TypedDict(
     "ListJobExecutionsForThingResponseTypeDef",
     {
         "executionSummaries": List[JobExecutionSummaryForThingTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSecurityProfilesForTargetResponseTypeDef = TypedDict(
     "ListSecurityProfilesForTargetResponseTypeDef",
     {
         "securityProfileTargetMappings": List[SecurityProfileTargetMappingTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListV2LoggingLevelsResponseTypeDef = TypedDict(
     "ListV2LoggingLevelsResponseTypeDef",
     {
         "logTargetConfigurations": List[LogTargetConfigurationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateMitigationActionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateMitigationActionRequestRequestTypeDef",
     {
         "actionName": str,
@@ -8009,15 +8422,15 @@
         "actionType": MitigationActionTypeType,
         "actionArn": str,
         "actionId": str,
         "roleArn": str,
         "actionParams": MitigationActionParamsTypeDef,
         "creationDate": datetime,
         "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MitigationActionTypeDef = TypedDict(
     "MitigationActionTypeDef",
     {
         "name": str,
@@ -8132,28 +8545,28 @@
     "DescribeAuditSuppressionResponseTypeDef",
     {
         "checkName": str,
         "resourceIdentifier": ResourceIdentifierTypeDef,
         "expirationDate": datetime,
         "suppressIndefinitely": bool,
         "description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAuditFindingsRequestListAuditFindingsPaginateTypeDef = TypedDict(
     "ListAuditFindingsRequestListAuditFindingsPaginateTypeDef",
     {
         "taskId": str,
         "checkName": str,
         "resourceIdentifier": ResourceIdentifierTypeDef,
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
         "listSuppressedFindings": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAuditFindingsRequestRequestTypeDef = TypedDict(
     "ListAuditFindingsRequestRequestTypeDef",
     {
@@ -8171,15 +8584,15 @@
 
 ListAuditSuppressionsRequestListAuditSuppressionsPaginateTypeDef = TypedDict(
     "ListAuditSuppressionsRequestListAuditSuppressionsPaginateTypeDef",
     {
         "checkName": str,
         "resourceIdentifier": ResourceIdentifierTypeDef,
         "ascendingOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAuditSuppressionsRequestRequestTypeDef = TypedDict(
     "ListAuditSuppressionsRequestRequestTypeDef",
     {
@@ -8237,15 +8650,15 @@
 
 SearchIndexResponseTypeDef = TypedDict(
     "SearchIndexResponseTypeDef",
     {
         "nextToken": str,
         "things": List[ThingDocumentTypeDef],
         "thingGroups": List[ThingGroupDocumentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTopicRuleDestinationRequestRequestTypeDef = TypedDict(
     "CreateTopicRuleDestinationRequestRequestTypeDef",
     {
         "destinationConfiguration": TopicRuleDestinationConfigurationTypeDef,
@@ -8253,31 +8666,31 @@
 )
 
 ListTopicRuleDestinationsResponseTypeDef = TypedDict(
     "ListTopicRuleDestinationsResponseTypeDef",
     {
         "destinationSummaries": List[TopicRuleDestinationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTopicRuleDestinationResponseTypeDef = TypedDict(
     "CreateTopicRuleDestinationResponseTypeDef",
     {
         "topicRuleDestination": TopicRuleDestinationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTopicRuleDestinationResponseTypeDef = TypedDict(
     "GetTopicRuleDestinationResponseTypeDef",
     {
         "topicRuleDestination": TopicRuleDestinationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AuthResultTypeDef = TypedDict(
     "AuthResultTypeDef",
     {
         "authInfo": AuthInfoTypeDef,
@@ -8348,15 +8761,15 @@
         "behaviors": List[BehaviorTypeDef],
         "alertTargets": Dict[Literal["SNS"], AlertTargetTypeDef],
         "additionalMetricsToRetain": List[str],
         "additionalMetricsToRetainV2": List[MetricToRetainTypeDef],
         "version": int,
         "creationDate": datetime,
         "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateSecurityProfileRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSecurityProfileRequestRequestTypeDef",
     {
         "securityProfileName": str,
@@ -8393,15 +8806,15 @@
         "behaviors": List[BehaviorTypeDef],
         "alertTargets": Dict[Literal["SNS"], AlertTargetTypeDef],
         "additionalMetricsToRetain": List[str],
         "additionalMetricsToRetainV2": List[MetricToRetainTypeDef],
         "version": int,
         "creationDate": datetime,
         "lastModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ValidateSecurityProfileBehaviorsRequestRequestTypeDef = TypedDict(
     "ValidateSecurityProfileBehaviorsRequestRequestTypeDef",
     {
         "behaviors": Sequence[BehaviorTypeDef],
@@ -8455,14 +8868,15 @@
         "timeoutConfig": TimeoutConfigTypeDef,
         "tags": Sequence[TagTypeDef],
         "namespaceId": str,
         "jobTemplateArn": str,
         "jobExecutionsRetryConfig": JobExecutionsRetryConfigTypeDef,
         "documentParameters": Mapping[str, str],
         "schedulingConfig": SchedulingConfigTypeDef,
+        "destinationPackageVersions": Sequence[str],
     },
     total=False,
 )
 
 class CreateJobRequestRequestTypeDef(
     _RequiredCreateJobRequestRequestTypeDef, _OptionalCreateJobRequestRequestTypeDef
 ):
@@ -8483,14 +8897,16 @@
         "document": str,
         "presignedUrlConfig": PresignedUrlConfigTypeDef,
         "jobExecutionsRolloutConfig": JobExecutionsRolloutConfigTypeDef,
         "abortConfig": AbortConfigTypeDef,
         "timeoutConfig": TimeoutConfigTypeDef,
         "tags": Sequence[TagTypeDef],
         "jobExecutionsRetryConfig": JobExecutionsRetryConfigTypeDef,
+        "maintenanceWindows": Sequence[MaintenanceWindowTypeDef],
+        "destinationPackageVersions": Sequence[str],
     },
     total=False,
 )
 
 class CreateJobTemplateRequestRequestTypeDef(
     _RequiredCreateJobTemplateRequestRequestTypeDef, _OptionalCreateJobTemplateRequestRequestTypeDef
 ):
@@ -8506,15 +8922,17 @@
         "document": str,
         "createdAt": datetime,
         "presignedUrlConfig": PresignedUrlConfigTypeDef,
         "jobExecutionsRolloutConfig": JobExecutionsRolloutConfigTypeDef,
         "abortConfig": AbortConfigTypeDef,
         "timeoutConfig": TimeoutConfigTypeDef,
         "jobExecutionsRetryConfig": JobExecutionsRetryConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "maintenanceWindows": List[MaintenanceWindowTypeDef],
+        "destinationPackageVersions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 JobTypeDef = TypedDict(
     "JobTypeDef",
     {
         "jobArn": str,
@@ -8536,14 +8954,16 @@
         "timeoutConfig": TimeoutConfigTypeDef,
         "namespaceId": str,
         "jobTemplateArn": str,
         "jobExecutionsRetryConfig": JobExecutionsRetryConfigTypeDef,
         "documentParameters": Dict[str, str],
         "isConcurrent": bool,
         "schedulingConfig": SchedulingConfigTypeDef,
+        "scheduledJobRollouts": List[ScheduledJobRolloutTypeDef],
+        "destinationPackageVersions": List[str],
     },
     total=False,
 )
 
 _RequiredUpdateJobRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateJobRequestRequestTypeDef",
     {
@@ -8569,29 +8989,29 @@
 ):
     pass
 
 DescribeStreamResponseTypeDef = TypedDict(
     "DescribeStreamResponseTypeDef",
     {
         "streamInfo": StreamInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAuditMitigationActionsTaskResponseTypeDef = TypedDict(
     "DescribeAuditMitigationActionsTaskResponseTypeDef",
     {
         "taskStatus": AuditMitigationActionsTaskStatusType,
         "startTime": datetime,
         "endTime": datetime,
         "taskStatistics": Dict[str, TaskStatisticsForAuditCheckTypeDef],
         "target": AuditMitigationActionsTaskTargetTypeDef,
         "auditCheckToActionsMapping": Dict[str, List[str]],
         "actionsDefinition": List[MitigationActionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectMitigationActionsTaskSummaryTypeDef = TypedDict(
     "DetectMitigationActionsTaskSummaryTypeDef",
     {
         "taskId": str,
@@ -8609,15 +9029,15 @@
 )
 
 ListAuditSuppressionsResponseTypeDef = TypedDict(
     "ListAuditSuppressionsResponseTypeDef",
     {
         "suppressions": List[AuditSuppressionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AuditFindingTypeDef = TypedDict(
     "AuditFindingTypeDef",
     {
         "findingId": str,
@@ -8636,23 +9056,23 @@
 )
 
 ListRelatedResourcesForAuditFindingResponseTypeDef = TypedDict(
     "ListRelatedResourcesForAuditFindingResponseTypeDef",
     {
         "relatedResources": List[RelatedResourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TestAuthorizationResponseTypeDef = TypedDict(
     "TestAuthorizationResponseTypeDef",
     {
         "authResults": List[AuthResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActionTypeDef = TypedDict(
     "ActionTypeDef",
     {
         "dynamoDB": DynamoDBActionTypeDef,
@@ -8683,24 +9103,24 @@
 )
 
 ListActiveViolationsResponseTypeDef = TypedDict(
     "ListActiveViolationsResponseTypeDef",
     {
         "activeViolations": List[ActiveViolationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListViolationEventsResponseTypeDef = TypedDict(
     "ListViolationEventsResponseTypeDef",
     {
         "violationEvents": List[ViolationEventTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OTAUpdateFileTypeDef = TypedDict(
     "OTAUpdateFileTypeDef",
     {
         "fileName": str,
@@ -8714,49 +9134,49 @@
 )
 
 DescribeJobResponseTypeDef = TypedDict(
     "DescribeJobResponseTypeDef",
     {
         "documentSource": str,
         "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDetectMitigationActionsTaskResponseTypeDef = TypedDict(
     "DescribeDetectMitigationActionsTaskResponseTypeDef",
     {
         "taskSummary": DetectMitigationActionsTaskSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDetectMitigationActionsTasksResponseTypeDef = TypedDict(
     "ListDetectMitigationActionsTasksResponseTypeDef",
     {
         "tasks": List[DetectMitigationActionsTaskSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAuditFindingResponseTypeDef = TypedDict(
     "DescribeAuditFindingResponseTypeDef",
     {
         "finding": AuditFindingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAuditFindingsResponseTypeDef = TypedDict(
     "ListAuditFindingsResponseTypeDef",
     {
         "findings": List[AuditFindingTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTopicRulePayloadTypeDef = TypedDict(
     "_RequiredTopicRulePayloadTypeDef",
     {
         "sql": str,
@@ -8874,18 +9294,18 @@
 )
 
 GetTopicRuleResponseTypeDef = TypedDict(
     "GetTopicRuleResponseTypeDef",
     {
         "ruleArn": str,
         "rule": TopicRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOTAUpdateResponseTypeDef = TypedDict(
     "GetOTAUpdateResponseTypeDef",
     {
         "otaUpdateInfo": OTAUpdateInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot.egg-info/PKG-INFO` & `types-aiobotocore-iot-2.5.1/types_aiobotocore_iot.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iot
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoT 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoT 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iot"></a>
 
 # types-aiobotocore-iot
 
 [![PyPI - types-aiobotocore-iot](https://img.shields.io/pypi/v/types-aiobotocore-iot.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoT 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT)
+[aiobotocore.IoT 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot.html#IoT)
 service compatible with [VSCode](https://code.visualstudio.com/),
 [PyCharm](https://www.jetbrains.com/pycharm/),
 [Emacs](https://www.gnu.org/software/emacs/),
 [Sublime Text](https://www.sublimetext.com/),
 [mypy](https://github.com/python/mypy),
 [pyright](https://github.com/microsoft/pyright) and other tools.
 
 Generated by
-[mypy-boto3-builder 7.13.0](https://github.com/youtype/mypy_boto3_builder).
+[mypy-boto3-builder 7.14.5](https://github.com/youtype/mypy_boto3_builder).
 
 More information can be found on
 [types-aiobotocore](https://pypi.org/project/types-aiobotocore/) page and in
 [types-aiobotocore-iot docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/).
 
 See how it helps to find and fix potential bugs:
 
@@ -295,24 +295,28 @@
     ListDomainConfigurationsPaginator,
     ListFleetMetricsPaginator,
     ListIndicesPaginator,
     ListJobExecutionsForJobPaginator,
     ListJobExecutionsForThingPaginator,
     ListJobTemplatesPaginator,
     ListJobsPaginator,
+    ListManagedJobTemplatesPaginator,
     ListMetricValuesPaginator,
     ListMitigationActionsPaginator,
     ListOTAUpdatesPaginator,
     ListOutgoingCertificatesPaginator,
+    ListPackageVersionsPaginator,
+    ListPackagesPaginator,
     ListPoliciesPaginator,
     ListPolicyPrincipalsPaginator,
     ListPrincipalPoliciesPaginator,
     ListPrincipalThingsPaginator,
     ListProvisioningTemplateVersionsPaginator,
     ListProvisioningTemplatesPaginator,
+    ListRelatedResourcesForAuditFindingPaginator,
     ListRoleAliasesPaginator,
     ListScheduledAuditsPaginator,
     ListSecurityProfilesPaginator,
     ListSecurityProfilesForTargetPaginator,
     ListStreamsPaginator,
     ListTagsForResourcePaginator,
     ListTargetsForPolicyPaginator,
@@ -396,24 +400,31 @@
     list_job_executions_for_thing_paginator: ListJobExecutionsForThingPaginator = (
         client.get_paginator("list_job_executions_for_thing")
     )
     list_job_templates_paginator: ListJobTemplatesPaginator = client.get_paginator(
         "list_job_templates"
     )
     list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
+    list_managed_job_templates_paginator: ListManagedJobTemplatesPaginator = client.get_paginator(
+        "list_managed_job_templates"
+    )
     list_metric_values_paginator: ListMetricValuesPaginator = client.get_paginator(
         "list_metric_values"
     )
     list_mitigation_actions_paginator: ListMitigationActionsPaginator = client.get_paginator(
         "list_mitigation_actions"
     )
     list_ota_updates_paginator: ListOTAUpdatesPaginator = client.get_paginator("list_ota_updates")
     list_outgoing_certificates_paginator: ListOutgoingCertificatesPaginator = client.get_paginator(
         "list_outgoing_certificates"
     )
+    list_package_versions_paginator: ListPackageVersionsPaginator = client.get_paginator(
+        "list_package_versions"
+    )
+    list_packages_paginator: ListPackagesPaginator = client.get_paginator("list_packages")
     list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
     list_policy_principals_paginator: ListPolicyPrincipalsPaginator = client.get_paginator(
         "list_policy_principals"
     )
     list_principal_policies_paginator: ListPrincipalPoliciesPaginator = client.get_paginator(
         "list_principal_policies"
     )
@@ -422,14 +433,17 @@
     )
     list_provisioning_template_versions_paginator: ListProvisioningTemplateVersionsPaginator = (
         client.get_paginator("list_provisioning_template_versions")
     )
     list_provisioning_templates_paginator: ListProvisioningTemplatesPaginator = (
         client.get_paginator("list_provisioning_templates")
     )
+    list_related_resources_for_audit_finding_paginator: ListRelatedResourcesForAuditFindingPaginator = client.get_paginator(
+        "list_related_resources_for_audit_finding"
+    )
     list_role_aliases_paginator: ListRoleAliasesPaginator = client.get_paginator(
         "list_role_aliases"
     )
     list_scheduled_audits_paginator: ListScheduledAuditsPaginator = client.get_paginator(
         "list_scheduled_audits"
     )
     list_security_profiles_paginator: ListSecurityProfilesPaginator = client.get_paginator(
@@ -557,24 +571,28 @@
     ListDomainConfigurationsPaginatorName,
     ListFleetMetricsPaginatorName,
     ListIndicesPaginatorName,
     ListJobExecutionsForJobPaginatorName,
     ListJobExecutionsForThingPaginatorName,
     ListJobTemplatesPaginatorName,
     ListJobsPaginatorName,
+    ListManagedJobTemplatesPaginatorName,
     ListMetricValuesPaginatorName,
     ListMitigationActionsPaginatorName,
     ListOTAUpdatesPaginatorName,
     ListOutgoingCertificatesPaginatorName,
+    ListPackageVersionsPaginatorName,
+    ListPackagesPaginatorName,
     ListPoliciesPaginatorName,
     ListPolicyPrincipalsPaginatorName,
     ListPrincipalPoliciesPaginatorName,
     ListPrincipalThingsPaginatorName,
     ListProvisioningTemplateVersionsPaginatorName,
     ListProvisioningTemplatesPaginatorName,
+    ListRelatedResourcesForAuditFindingPaginatorName,
     ListRoleAliasesPaginatorName,
     ListScheduledAuditsPaginatorName,
     ListSecurityProfilesForTargetPaginatorName,
     ListSecurityProfilesPaginatorName,
     ListStreamsPaginatorName,
     ListTagsForResourcePaginatorName,
     ListTargetsForPolicyPaginatorName,
@@ -595,14 +613,16 @@
     LogLevelType,
     LogTargetTypeType,
     MessageFormatType,
     MitigationActionTypeType,
     ModelStatusType,
     NamedShadowIndexingModeType,
     OTAUpdateStatusType,
+    PackageVersionActionType,
+    PackageVersionStatusType,
     PolicyTemplateNameType,
     ProtocolType,
     ReportTypeType,
     ResourceTypeType,
     RetryableFailureTypeType,
     ServerCertificateStatusType,
     ServiceTypeType,
@@ -662,15 +682,15 @@
     AddThingsToThingGroupParamsTypeDef,
     AggregationTypeTypeDef,
     AlertTargetTypeDef,
     PolicyTypeDef,
     AssetPropertyTimestampTypeDef,
     AssetPropertyVariantTypeDef,
     AssociateTargetsWithJobRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateTargetsWithJobResponseTypeDef,
     AttachPolicyRequestRequestTypeDef,
     AttachPrincipalPolicyRequestRequestTypeDef,
     AttachSecurityProfileRequestRequestTypeDef,
     AttachThingPrincipalRequestRequestTypeDef,
     AttributePayloadTypeDef,
     AuditCheckConfigurationTypeDef,
     AuditCheckDetailsTypeDef,
@@ -699,32 +719,61 @@
     CACertificateTypeDef,
     CancelAuditMitigationActionsTaskRequestRequestTypeDef,
     CancelAuditTaskRequestRequestTypeDef,
     CancelCertificateTransferRequestRequestTypeDef,
     CancelDetectMitigationActionsTaskRequestRequestTypeDef,
     CancelJobExecutionRequestRequestTypeDef,
     CancelJobRequestRequestTypeDef,
+    CancelJobResponseTypeDef,
     TransferDataTypeDef,
     CertificateTypeDef,
     CodeSigningCertificateChainTypeDef,
     CodeSigningSignatureTypeDef,
     ConfigurationTypeDef,
     ConfirmTopicRuleDestinationRequestRequestTypeDef,
     TagTypeDef,
+    CreateAuthorizerResponseTypeDef,
+    CreateBillingGroupResponseTypeDef,
     CreateCertificateFromCsrRequestRequestTypeDef,
+    CreateCertificateFromCsrResponseTypeDef,
+    CreateCustomMetricResponseTypeDef,
+    CreateDimensionResponseTypeDef,
+    TlsConfigTypeDef,
+    CreateDomainConfigurationResponseTypeDef,
+    CreateDynamicThingGroupResponseTypeDef,
+    CreateFleetMetricResponseTypeDef,
     PresignedUrlConfigTypeDef,
-    SchedulingConfigTypeDef,
     TimeoutConfigTypeDef,
+    CreateJobResponseTypeDef,
+    MaintenanceWindowTypeDef,
+    CreateJobTemplateResponseTypeDef,
     CreateKeysAndCertificateRequestRequestTypeDef,
     KeyPairTypeDef,
+    CreateMitigationActionResponseTypeDef,
+    CreateOTAUpdateResponseTypeDef,
+    CreatePackageRequestRequestTypeDef,
+    CreatePackageResponseTypeDef,
+    CreatePackageVersionRequestRequestTypeDef,
+    CreatePackageVersionResponseTypeDef,
+    CreatePolicyResponseTypeDef,
     CreatePolicyVersionRequestRequestTypeDef,
+    CreatePolicyVersionResponseTypeDef,
     CreateProvisioningClaimRequestRequestTypeDef,
     ProvisioningHookTypeDef,
+    CreateProvisioningTemplateResponseTypeDef,
     CreateProvisioningTemplateVersionRequestRequestTypeDef,
+    CreateProvisioningTemplateVersionResponseTypeDef,
+    CreateRoleAliasResponseTypeDef,
+    CreateScheduledAuditResponseTypeDef,
+    CreateSecurityProfileResponseTypeDef,
+    CreateStreamResponseTypeDef,
+    CreateThingGroupResponseTypeDef,
+    CreateThingResponseTypeDef,
     ThingTypePropertiesTypeDef,
+    CreateThingTypeResponseTypeDef,
     DeleteAccountAuditConfigurationRequestRequestTypeDef,
     DeleteAuthorizerRequestRequestTypeDef,
     DeleteBillingGroupRequestRequestTypeDef,
     DeleteCACertificateRequestRequestTypeDef,
     DeleteCertificateRequestRequestTypeDef,
     DeleteCustomMetricRequestRequestTypeDef,
     DeleteDimensionRequestRequestTypeDef,
@@ -732,14 +781,16 @@
     DeleteDynamicThingGroupRequestRequestTypeDef,
     DeleteFleetMetricRequestRequestTypeDef,
     DeleteJobExecutionRequestRequestTypeDef,
     DeleteJobRequestRequestTypeDef,
     DeleteJobTemplateRequestRequestTypeDef,
     DeleteMitigationActionRequestRequestTypeDef,
     DeleteOTAUpdateRequestRequestTypeDef,
+    DeletePackageRequestRequestTypeDef,
+    DeletePackageVersionRequestRequestTypeDef,
     DeletePolicyRequestRequestTypeDef,
     DeletePolicyVersionRequestRequestTypeDef,
     DeleteProvisioningTemplateRequestRequestTypeDef,
     DeleteProvisioningTemplateVersionRequestRequestTypeDef,
     DeleteRoleAliasRequestRequestTypeDef,
     DeleteScheduledAuditRequestRequestTypeDef,
     DeleteSecurityProfileRequestRequestTypeDef,
@@ -758,37 +809,45 @@
     TaskStatisticsTypeDef,
     DescribeAuthorizerRequestRequestTypeDef,
     DescribeBillingGroupRequestRequestTypeDef,
     DescribeCACertificateRequestRequestTypeDef,
     RegistrationConfigTypeDef,
     DescribeCertificateRequestRequestTypeDef,
     DescribeCustomMetricRequestRequestTypeDef,
+    DescribeCustomMetricResponseTypeDef,
     DescribeDetectMitigationActionsTaskRequestRequestTypeDef,
     DescribeDimensionRequestRequestTypeDef,
+    DescribeDimensionResponseTypeDef,
     DescribeDomainConfigurationRequestRequestTypeDef,
     ServerCertificateSummaryTypeDef,
     DescribeEndpointRequestRequestTypeDef,
+    DescribeEndpointResponseTypeDef,
     DescribeFleetMetricRequestRequestTypeDef,
     DescribeIndexRequestRequestTypeDef,
+    DescribeIndexResponseTypeDef,
     DescribeJobExecutionRequestRequestTypeDef,
     DescribeJobRequestRequestTypeDef,
     DescribeJobTemplateRequestRequestTypeDef,
     DescribeManagedJobTemplateRequestRequestTypeDef,
     DocumentParameterTypeDef,
     DescribeMitigationActionRequestRequestTypeDef,
     DescribeProvisioningTemplateRequestRequestTypeDef,
     DescribeProvisioningTemplateVersionRequestRequestTypeDef,
+    DescribeProvisioningTemplateVersionResponseTypeDef,
     DescribeRoleAliasRequestRequestTypeDef,
     RoleAliasDescriptionTypeDef,
     DescribeScheduledAuditRequestRequestTypeDef,
+    DescribeScheduledAuditResponseTypeDef,
     DescribeSecurityProfileRequestRequestTypeDef,
     DescribeStreamRequestRequestTypeDef,
     DescribeThingGroupRequestRequestTypeDef,
     DescribeThingRegistrationTaskRequestRequestTypeDef,
+    DescribeThingRegistrationTaskResponseTypeDef,
     DescribeThingRequestRequestTypeDef,
+    DescribeThingResponseTypeDef,
     DescribeThingTypeRequestRequestTypeDef,
     ThingTypeMetadataTypeDef,
     S3DestinationTypeDef,
     DetachPolicyRequestRequestTypeDef,
     DetachPrincipalPolicyRequestRequestTypeDef,
     DetachSecurityProfileRequestRequestTypeDef,
     DetachThingPrincipalRequestRequestTypeDef,
@@ -796,36 +855,49 @@
     DetectMitigationActionsTaskStatisticsTypeDef,
     DetectMitigationActionsTaskTargetTypeDef,
     ViolationEventOccurrenceRangeTypeDef,
     DisableTopicRuleRequestRequestTypeDef,
     DomainConfigurationSummaryTypeDef,
     PutItemInputTypeDef,
     EffectivePolicyTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableIoTLoggingParamsTypeDef,
     EnableTopicRuleRequestRequestTypeDef,
     ErrorInfoTypeDef,
     RateIncreaseCriteriaTypeDef,
     FieldTypeDef,
     S3LocationTypeDef,
     StreamTypeDef,
     FleetMetricNameAndArnTypeDef,
-    PaginatorConfigTypeDef,
+    GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef,
     GetBehaviorModelTrainingSummariesRequestRequestTypeDef,
     GetCardinalityRequestRequestTypeDef,
+    GetCardinalityResponseTypeDef,
     GetEffectivePoliciesRequestRequestTypeDef,
     GetJobDocumentRequestRequestTypeDef,
+    GetJobDocumentResponseTypeDef,
+    GetLoggingOptionsResponseTypeDef,
     GetOTAUpdateRequestRequestTypeDef,
+    VersionUpdateByJobsConfigTypeDef,
+    GetPackageRequestRequestTypeDef,
+    GetPackageResponseTypeDef,
+    GetPackageVersionRequestRequestTypeDef,
+    GetPackageVersionResponseTypeDef,
     GetPercentilesRequestRequestTypeDef,
     PercentPairTypeDef,
     GetPolicyRequestRequestTypeDef,
+    GetPolicyResponseTypeDef,
     GetPolicyVersionRequestRequestTypeDef,
+    GetPolicyVersionResponseTypeDef,
+    GetRegistrationCodeResponseTypeDef,
     GetStatisticsRequestRequestTypeDef,
     StatisticsTypeDef,
     GetTopicRuleDestinationRequestRequestTypeDef,
     GetTopicRuleRequestRequestTypeDef,
+    GetV2LoggingOptionsResponseTypeDef,
     GroupNameAndArnTypeDef,
     HttpActionHeaderTypeDef,
     SigV4AuthorizationTypeDef,
     HttpContextTypeDef,
     HttpUrlDestinationConfigurationTypeDef,
     HttpUrlDestinationPropertiesTypeDef,
     HttpUrlDestinationSummaryTypeDef,
@@ -833,223 +905,246 @@
     IssuerCertificateIdentifierTypeDef,
     JobExecutionStatusDetailsTypeDef,
     JobExecutionSummaryTypeDef,
     RetryCriteriaTypeDef,
     JobProcessDetailsTypeDef,
     JobSummaryTypeDef,
     JobTemplateSummaryTypeDef,
+    ScheduledJobRolloutTypeDef,
+    ListActiveViolationsRequestListActiveViolationsPaginateTypeDef,
     ListActiveViolationsRequestRequestTypeDef,
+    ListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef,
     ListAttachedPoliciesRequestRequestTypeDef,
+    ListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef,
     ListAuditMitigationActionsExecutionsRequestRequestTypeDef,
+    ListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef,
     ListAuditMitigationActionsTasksRequestRequestTypeDef,
+    ListAuditTasksRequestListAuditTasksPaginateTypeDef,
     ListAuditTasksRequestRequestTypeDef,
+    ListAuthorizersRequestListAuthorizersPaginateTypeDef,
     ListAuthorizersRequestRequestTypeDef,
+    ListBillingGroupsRequestListBillingGroupsPaginateTypeDef,
     ListBillingGroupsRequestRequestTypeDef,
+    ListCACertificatesRequestListCACertificatesPaginateTypeDef,
     ListCACertificatesRequestRequestTypeDef,
+    ListCertificatesByCARequestListCertificatesByCAPaginateTypeDef,
     ListCertificatesByCARequestRequestTypeDef,
+    ListCertificatesRequestListCertificatesPaginateTypeDef,
     ListCertificatesRequestRequestTypeDef,
+    ListCustomMetricsRequestListCustomMetricsPaginateTypeDef,
     ListCustomMetricsRequestRequestTypeDef,
+    ListCustomMetricsResponseTypeDef,
+    ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef,
     ListDetectMitigationActionsExecutionsRequestRequestTypeDef,
+    ListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef,
     ListDetectMitigationActionsTasksRequestRequestTypeDef,
+    ListDimensionsRequestListDimensionsPaginateTypeDef,
     ListDimensionsRequestRequestTypeDef,
+    ListDimensionsResponseTypeDef,
+    ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef,
     ListDomainConfigurationsRequestRequestTypeDef,
+    ListFleetMetricsRequestListFleetMetricsPaginateTypeDef,
     ListFleetMetricsRequestRequestTypeDef,
+    ListIndicesRequestListIndicesPaginateTypeDef,
     ListIndicesRequestRequestTypeDef,
+    ListIndicesResponseTypeDef,
+    ListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef,
     ListJobExecutionsForJobRequestRequestTypeDef,
+    ListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef,
     ListJobExecutionsForThingRequestRequestTypeDef,
+    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
     ListJobTemplatesRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListManagedJobTemplatesRequestListManagedJobTemplatesPaginateTypeDef,
     ListManagedJobTemplatesRequestRequestTypeDef,
     ManagedJobTemplateSummaryTypeDef,
+    ListMetricValuesRequestListMetricValuesPaginateTypeDef,
     ListMetricValuesRequestRequestTypeDef,
+    ListMitigationActionsRequestListMitigationActionsPaginateTypeDef,
     ListMitigationActionsRequestRequestTypeDef,
     MitigationActionIdentifierTypeDef,
+    ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef,
     ListOTAUpdatesRequestRequestTypeDef,
     OTAUpdateSummaryTypeDef,
+    ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef,
     ListOutgoingCertificatesRequestRequestTypeDef,
     OutgoingCertificateTypeDef,
+    ListPackageVersionsRequestListPackageVersionsPaginateTypeDef,
+    ListPackageVersionsRequestRequestTypeDef,
+    PackageVersionSummaryTypeDef,
+    ListPackagesRequestListPackagesPaginateTypeDef,
+    ListPackagesRequestRequestTypeDef,
+    PackageSummaryTypeDef,
+    ListPoliciesRequestListPoliciesPaginateTypeDef,
     ListPoliciesRequestRequestTypeDef,
+    ListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef,
     ListPolicyPrincipalsRequestRequestTypeDef,
+    ListPolicyPrincipalsResponseTypeDef,
     ListPolicyVersionsRequestRequestTypeDef,
     PolicyVersionTypeDef,
+    ListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef,
     ListPrincipalPoliciesRequestRequestTypeDef,
+    ListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef,
     ListPrincipalThingsRequestRequestTypeDef,
+    ListPrincipalThingsResponseTypeDef,
+    ListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef,
     ListProvisioningTemplateVersionsRequestRequestTypeDef,
     ProvisioningTemplateVersionSummaryTypeDef,
+    ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef,
     ListProvisioningTemplatesRequestRequestTypeDef,
     ProvisioningTemplateSummaryTypeDef,
+    ListRelatedResourcesForAuditFindingRequestListRelatedResourcesForAuditFindingPaginateTypeDef,
     ListRelatedResourcesForAuditFindingRequestRequestTypeDef,
+    ListRoleAliasesRequestListRoleAliasesPaginateTypeDef,
     ListRoleAliasesRequestRequestTypeDef,
+    ListRoleAliasesResponseTypeDef,
+    ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef,
     ListScheduledAuditsRequestRequestTypeDef,
     ScheduledAuditMetadataTypeDef,
+    ListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef,
     ListSecurityProfilesForTargetRequestRequestTypeDef,
+    ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef,
     ListSecurityProfilesRequestRequestTypeDef,
     SecurityProfileIdentifierTypeDef,
+    ListStreamsRequestListStreamsPaginateTypeDef,
     ListStreamsRequestRequestTypeDef,
     StreamSummaryTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
     ListTargetsForPolicyRequestRequestTypeDef,
+    ListTargetsForPolicyResponseTypeDef,
+    ListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef,
     ListTargetsForSecurityProfileRequestRequestTypeDef,
     SecurityProfileTargetTypeDef,
+    ListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef,
     ListThingGroupsForThingRequestRequestTypeDef,
+    ListThingGroupsRequestListThingGroupsPaginateTypeDef,
     ListThingGroupsRequestRequestTypeDef,
+    ListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef,
     ListThingPrincipalsRequestRequestTypeDef,
+    ListThingPrincipalsResponseTypeDef,
+    ListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef,
     ListThingRegistrationTaskReportsRequestRequestTypeDef,
+    ListThingRegistrationTaskReportsResponseTypeDef,
+    ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef,
     ListThingRegistrationTasksRequestRequestTypeDef,
+    ListThingRegistrationTasksResponseTypeDef,
+    ListThingTypesRequestListThingTypesPaginateTypeDef,
     ListThingTypesRequestRequestTypeDef,
+    ListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef,
     ListThingsInBillingGroupRequestRequestTypeDef,
+    ListThingsInBillingGroupResponseTypeDef,
+    ListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef,
     ListThingsInThingGroupRequestRequestTypeDef,
+    ListThingsInThingGroupResponseTypeDef,
+    ListThingsRequestListThingsPaginateTypeDef,
     ListThingsRequestRequestTypeDef,
     ThingAttributeTypeDef,
+    ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef,
     ListTopicRuleDestinationsRequestRequestTypeDef,
+    ListTopicRulesRequestListTopicRulesPaginateTypeDef,
     ListTopicRulesRequestRequestTypeDef,
     TopicRuleListItemTypeDef,
+    ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef,
     ListV2LoggingLevelsRequestRequestTypeDef,
+    ListViolationEventsRequestListViolationEventsPaginateTypeDef,
     ListViolationEventsRequestRequestTypeDef,
     LocationTimestampTypeDef,
     LogTargetTypeDef,
     LoggingOptionsPayloadTypeDef,
     PublishFindingToSnsParamsTypeDef,
     ReplaceDefaultPolicyVersionParamsTypeDef,
     UpdateCACertificateParamsTypeDef,
     UpdateDeviceCertificateParamsTypeDef,
     MqttContextTypeDef,
     UserPropertyTypeDef,
+    PaginatorConfigTypeDef,
     PolicyVersionIdentifierTypeDef,
     PutVerificationStateOnViolationRequestRequestTypeDef,
+    RegisterCACertificateResponseTypeDef,
     RegisterCertificateRequestRequestTypeDef,
+    RegisterCertificateResponseTypeDef,
     RegisterCertificateWithoutCARequestRequestTypeDef,
+    RegisterCertificateWithoutCAResponseTypeDef,
     RegisterThingRequestRequestTypeDef,
+    RegisterThingResponseTypeDef,
     RejectCertificateTransferRequestRequestTypeDef,
     RemoveThingFromBillingGroupRequestRequestTypeDef,
     RemoveThingFromThingGroupRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SearchIndexRequestRequestTypeDef,
     ThingGroupDocumentTypeDef,
     SetDefaultAuthorizerRequestRequestTypeDef,
+    SetDefaultAuthorizerResponseTypeDef,
     SetDefaultPolicyVersionRequestRequestTypeDef,
     SetV2LoggingOptionsRequestRequestTypeDef,
     SigningProfileParameterTypeDef,
+    StartAuditMitigationActionsTaskResponseTypeDef,
+    StartDetectMitigationActionsTaskResponseTypeDef,
     StartOnDemandAuditTaskRequestRequestTypeDef,
+    StartOnDemandAuditTaskResponseTypeDef,
     StartThingRegistrationTaskRequestRequestTypeDef,
+    StartThingRegistrationTaskResponseTypeDef,
     StopThingRegistrationTaskRequestRequestTypeDef,
     TlsContextTypeDef,
+    TestInvokeAuthorizerResponseTypeDef,
     ThingConnectivityTypeDef,
     TimestreamDimensionTypeDef,
     TimestreamTimestampTypeDef,
     VpcDestinationConfigurationTypeDef,
     VpcDestinationSummaryTypeDef,
     VpcDestinationPropertiesTypeDef,
     TransferCertificateRequestRequestTypeDef,
+    TransferCertificateResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAuthorizerRequestRequestTypeDef,
+    UpdateAuthorizerResponseTypeDef,
+    UpdateBillingGroupResponseTypeDef,
     UpdateCertificateRequestRequestTypeDef,
     UpdateCustomMetricRequestRequestTypeDef,
+    UpdateCustomMetricResponseTypeDef,
     UpdateDimensionRequestRequestTypeDef,
+    UpdateDimensionResponseTypeDef,
+    UpdateDomainConfigurationResponseTypeDef,
+    UpdateDynamicThingGroupResponseTypeDef,
+    UpdateMitigationActionResponseTypeDef,
+    UpdatePackageRequestRequestTypeDef,
+    UpdatePackageVersionRequestRequestTypeDef,
     UpdateRoleAliasRequestRequestTypeDef,
+    UpdateRoleAliasResponseTypeDef,
     UpdateScheduledAuditRequestRequestTypeDef,
+    UpdateScheduledAuditResponseTypeDef,
+    UpdateStreamResponseTypeDef,
+    UpdateThingGroupResponseTypeDef,
     UpdateThingGroupsForThingRequestRequestTypeDef,
     UpdateTopicRuleDestinationRequestRequestTypeDef,
     ValidationErrorTypeDef,
     AbortConfigTypeDef,
     MetricDatumTypeDef,
+    DescribeFleetMetricResponseTypeDef,
     UpdateFleetMetricRequestRequestTypeDef,
     AllowedTypeDef,
     ExplicitDenyTypeDef,
     ImplicitDenyTypeDef,
-    AssetPropertyValueTypeDef,
-    AssociateTargetsWithJobResponseTypeDef,
-    CancelJobResponseTypeDef,
-    CreateAuthorizerResponseTypeDef,
-    CreateBillingGroupResponseTypeDef,
-    CreateCertificateFromCsrResponseTypeDef,
-    CreateCustomMetricResponseTypeDef,
-    CreateDimensionResponseTypeDef,
-    CreateDomainConfigurationResponseTypeDef,
-    CreateDynamicThingGroupResponseTypeDef,
-    CreateFleetMetricResponseTypeDef,
-    CreateJobResponseTypeDef,
-    CreateJobTemplateResponseTypeDef,
-    CreateMitigationActionResponseTypeDef,
-    CreateOTAUpdateResponseTypeDef,
-    CreatePolicyResponseTypeDef,
-    CreatePolicyVersionResponseTypeDef,
-    CreateProvisioningTemplateResponseTypeDef,
-    CreateProvisioningTemplateVersionResponseTypeDef,
-    CreateRoleAliasResponseTypeDef,
-    CreateScheduledAuditResponseTypeDef,
-    CreateSecurityProfileResponseTypeDef,
-    CreateStreamResponseTypeDef,
-    CreateThingGroupResponseTypeDef,
-    CreateThingResponseTypeDef,
-    CreateThingTypeResponseTypeDef,
-    DescribeCustomMetricResponseTypeDef,
-    DescribeDimensionResponseTypeDef,
-    DescribeEndpointResponseTypeDef,
-    DescribeFleetMetricResponseTypeDef,
-    DescribeIndexResponseTypeDef,
-    DescribeProvisioningTemplateVersionResponseTypeDef,
-    DescribeScheduledAuditResponseTypeDef,
-    DescribeThingRegistrationTaskResponseTypeDef,
-    DescribeThingResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCardinalityResponseTypeDef,
-    GetJobDocumentResponseTypeDef,
-    GetLoggingOptionsResponseTypeDef,
-    GetPolicyResponseTypeDef,
-    GetPolicyVersionResponseTypeDef,
-    GetRegistrationCodeResponseTypeDef,
-    GetV2LoggingOptionsResponseTypeDef,
     ListAttachedPoliciesResponseTypeDef,
-    ListCustomMetricsResponseTypeDef,
-    ListDimensionsResponseTypeDef,
-    ListIndicesResponseTypeDef,
     ListPoliciesResponseTypeDef,
-    ListPolicyPrincipalsResponseTypeDef,
     ListPrincipalPoliciesResponseTypeDef,
-    ListPrincipalThingsResponseTypeDef,
-    ListRoleAliasesResponseTypeDef,
-    ListTargetsForPolicyResponseTypeDef,
-    ListThingPrincipalsResponseTypeDef,
-    ListThingRegistrationTaskReportsResponseTypeDef,
-    ListThingRegistrationTasksResponseTypeDef,
-    ListThingsInBillingGroupResponseTypeDef,
-    ListThingsInThingGroupResponseTypeDef,
-    RegisterCACertificateResponseTypeDef,
-    RegisterCertificateResponseTypeDef,
-    RegisterCertificateWithoutCAResponseTypeDef,
-    RegisterThingResponseTypeDef,
-    SetDefaultAuthorizerResponseTypeDef,
-    StartAuditMitigationActionsTaskResponseTypeDef,
-    StartDetectMitigationActionsTaskResponseTypeDef,
-    StartOnDemandAuditTaskResponseTypeDef,
-    StartThingRegistrationTaskResponseTypeDef,
-    TestInvokeAuthorizerResponseTypeDef,
-    TransferCertificateResponseTypeDef,
-    UpdateAuthorizerResponseTypeDef,
-    UpdateBillingGroupResponseTypeDef,
-    UpdateCustomMetricResponseTypeDef,
-    UpdateDimensionResponseTypeDef,
-    UpdateDomainConfigurationResponseTypeDef,
-    UpdateDynamicThingGroupResponseTypeDef,
-    UpdateMitigationActionResponseTypeDef,
-    UpdateRoleAliasResponseTypeDef,
-    UpdateScheduledAuditResponseTypeDef,
-    UpdateStreamResponseTypeDef,
-    UpdateThingGroupResponseTypeDef,
+    AssetPropertyValueTypeDef,
     CreateThingRequestRequestTypeDef,
     ThingGroupPropertiesTypeDef,
     UpdateThingRequestRequestTypeDef,
     ListAuditMitigationActionsExecutionsResponseTypeDef,
     ListAuditMitigationActionsTasksResponseTypeDef,
     StartAuditMitigationActionsTaskRequestRequestTypeDef,
     DescribeAccountAuditConfigurationResponseTypeDef,
     UpdateAccountAuditConfigurationRequestRequestTypeDef,
     ListAuditTasksResponseTypeDef,
     TestAuthorizationRequestRequestTypeDef,
-    UpdateDomainConfigurationRequestRequestTypeDef,
     DescribeAuthorizerResponseTypeDef,
     DescribeDefaultAuthorizerResponseTypeDef,
     ListAuthorizersResponseTypeDef,
     AwsJobAbortConfigTypeDef,
     AwsJobExponentialRolloutRateTypeDef,
     BehaviorCriteriaTypeDef,
     GetBehaviorModelTrainingSummariesResponseTypeDef,
@@ -1066,21 +1161,23 @@
     CustomCodeSigningTypeDef,
     DescribeEventConfigurationsResponseTypeDef,
     UpdateEventConfigurationsRequestRequestTypeDef,
     CreateAuthorizerRequestRequestTypeDef,
     CreateBillingGroupRequestRequestTypeDef,
     CreateCustomMetricRequestRequestTypeDef,
     CreateDimensionRequestRequestTypeDef,
-    CreateDomainConfigurationRequestRequestTypeDef,
     CreateFleetMetricRequestRequestTypeDef,
     CreatePolicyRequestRequestTypeDef,
     CreateRoleAliasRequestRequestTypeDef,
     CreateScheduledAuditRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    CreateDomainConfigurationRequestRequestTypeDef,
+    UpdateDomainConfigurationRequestRequestTypeDef,
+    SchedulingConfigTypeDef,
     CreateKeysAndCertificateResponseTypeDef,
     CreateProvisioningClaimResponseTypeDef,
     CreateProvisioningTemplateRequestRequestTypeDef,
     DescribeProvisioningTemplateResponseTypeDef,
     UpdateProvisioningTemplateRequestRequestTypeDef,
     CreateThingTypeRequestRequestTypeDef,
     DescribeAuditTaskResponseTypeDef,
@@ -1098,67 +1195,16 @@
     DynamoDBv2ActionTypeDef,
     GetEffectivePoliciesResponseTypeDef,
     ExponentialRolloutRateTypeDef,
     ThingGroupIndexingConfigurationTypeDef,
     StreamFileTypeDef,
     FileLocationTypeDef,
     ListFleetMetricsResponseTypeDef,
-    GetBehaviorModelTrainingSummariesRequestGetBehaviorModelTrainingSummariesPaginateTypeDef,
-    ListActiveViolationsRequestListActiveViolationsPaginateTypeDef,
-    ListAttachedPoliciesRequestListAttachedPoliciesPaginateTypeDef,
-    ListAuditMitigationActionsExecutionsRequestListAuditMitigationActionsExecutionsPaginateTypeDef,
-    ListAuditMitigationActionsTasksRequestListAuditMitigationActionsTasksPaginateTypeDef,
-    ListAuditTasksRequestListAuditTasksPaginateTypeDef,
-    ListAuthorizersRequestListAuthorizersPaginateTypeDef,
-    ListBillingGroupsRequestListBillingGroupsPaginateTypeDef,
-    ListCACertificatesRequestListCACertificatesPaginateTypeDef,
-    ListCertificatesByCARequestListCertificatesByCAPaginateTypeDef,
-    ListCertificatesRequestListCertificatesPaginateTypeDef,
-    ListCustomMetricsRequestListCustomMetricsPaginateTypeDef,
-    ListDetectMitigationActionsExecutionsRequestListDetectMitigationActionsExecutionsPaginateTypeDef,
-    ListDetectMitigationActionsTasksRequestListDetectMitigationActionsTasksPaginateTypeDef,
-    ListDimensionsRequestListDimensionsPaginateTypeDef,
-    ListDomainConfigurationsRequestListDomainConfigurationsPaginateTypeDef,
-    ListFleetMetricsRequestListFleetMetricsPaginateTypeDef,
-    ListIndicesRequestListIndicesPaginateTypeDef,
-    ListJobExecutionsForJobRequestListJobExecutionsForJobPaginateTypeDef,
-    ListJobExecutionsForThingRequestListJobExecutionsForThingPaginateTypeDef,
-    ListJobTemplatesRequestListJobTemplatesPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListMetricValuesRequestListMetricValuesPaginateTypeDef,
-    ListMitigationActionsRequestListMitigationActionsPaginateTypeDef,
-    ListOTAUpdatesRequestListOTAUpdatesPaginateTypeDef,
-    ListOutgoingCertificatesRequestListOutgoingCertificatesPaginateTypeDef,
-    ListPoliciesRequestListPoliciesPaginateTypeDef,
-    ListPolicyPrincipalsRequestListPolicyPrincipalsPaginateTypeDef,
-    ListPrincipalPoliciesRequestListPrincipalPoliciesPaginateTypeDef,
-    ListPrincipalThingsRequestListPrincipalThingsPaginateTypeDef,
-    ListProvisioningTemplateVersionsRequestListProvisioningTemplateVersionsPaginateTypeDef,
-    ListProvisioningTemplatesRequestListProvisioningTemplatesPaginateTypeDef,
-    ListRoleAliasesRequestListRoleAliasesPaginateTypeDef,
-    ListScheduledAuditsRequestListScheduledAuditsPaginateTypeDef,
-    ListSecurityProfilesForTargetRequestListSecurityProfilesForTargetPaginateTypeDef,
-    ListSecurityProfilesRequestListSecurityProfilesPaginateTypeDef,
-    ListStreamsRequestListStreamsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    ListTargetsForPolicyRequestListTargetsForPolicyPaginateTypeDef,
-    ListTargetsForSecurityProfileRequestListTargetsForSecurityProfilePaginateTypeDef,
-    ListThingGroupsForThingRequestListThingGroupsForThingPaginateTypeDef,
-    ListThingGroupsRequestListThingGroupsPaginateTypeDef,
-    ListThingPrincipalsRequestListThingPrincipalsPaginateTypeDef,
-    ListThingRegistrationTaskReportsRequestListThingRegistrationTaskReportsPaginateTypeDef,
-    ListThingRegistrationTasksRequestListThingRegistrationTasksPaginateTypeDef,
-    ListThingTypesRequestListThingTypesPaginateTypeDef,
-    ListThingsInBillingGroupRequestListThingsInBillingGroupPaginateTypeDef,
-    ListThingsInThingGroupRequestListThingsInThingGroupPaginateTypeDef,
-    ListThingsRequestListThingsPaginateTypeDef,
-    ListTopicRuleDestinationsRequestListTopicRuleDestinationsPaginateTypeDef,
-    ListTopicRulesRequestListTopicRulesPaginateTypeDef,
-    ListV2LoggingLevelsRequestListV2LoggingLevelsPaginateTypeDef,
-    ListViolationEventsRequestListViolationEventsPaginateTypeDef,
+    GetPackageConfigurationResponseTypeDef,
+    UpdatePackageConfigurationRequestRequestTypeDef,
     GetPercentilesResponseTypeDef,
     GetStatisticsResponseTypeDef,
     ListBillingGroupsResponseTypeDef,
     ListThingGroupsForThingResponseTypeDef,
     ListThingGroupsResponseTypeDef,
     ThingGroupMetadataTypeDef,
     HttpAuthorizationTypeDef,
@@ -1169,14 +1215,16 @@
     JobExecutionsRetryConfigTypeDef,
     ListJobsResponseTypeDef,
     ListJobTemplatesResponseTypeDef,
     ListManagedJobTemplatesResponseTypeDef,
     ListMitigationActionsResponseTypeDef,
     ListOTAUpdatesResponseTypeDef,
     ListOutgoingCertificatesResponseTypeDef,
+    ListPackageVersionsResponseTypeDef,
+    ListPackagesResponseTypeDef,
     ListPolicyVersionsResponseTypeDef,
     ListProvisioningTemplateVersionsResponseTypeDef,
     ListProvisioningTemplatesResponseTypeDef,
     ListScheduledAuditsResponseTypeDef,
     ListSecurityProfilesResponseTypeDef,
     ListStreamsResponseTypeDef,
     ListTargetsForSecurityProfileResponseTypeDef,
@@ -1295,43 +1343,43 @@
 <a id="how-it-works"></a>
 
 ## How it works
 
 Fully automated
 [mypy-boto3-builder](https://github.com/youtype/mypy_boto3_builder) carefully
 generates type annotations for each service, patiently waiting for
-`aiobotocore` updates. It delivers a drop-in type annotations for you and makes
+`aiobotocore` updates. It delivers drop-in type annotations for you and makes
 sure that:
 
 - All available `aiobotocore` services are covered.
 - Each public class and method of every `aiobotocore` service gets valid type
-  annotations extracted from the documentation (blame `botocore` docs if types
-  are incorrect).
+  annotations extracted from `botocore` schemas.
 - Type annotations include up-to-date documentation.
 - Link to documentation is provided for every method.
 - Code is processed by [black](https://github.com/psf/black) and
   [isort](https://github.com/PyCQA/isort) for readability.
 
 <a id="what's-new"></a>
 
 ## What's new
 
 <a id="implemented-features"></a>
 
 ### Implemented features
 
-- Fully type annotated `boto3`, `botocore` and `aiobotocore` libraries
+- Fully type annotated `boto3`, `botocore`, `aiobotocore` and `aioboto3`
+  libraries
 - `mypy`, `pyright`, `VSCode`, `PyCharm`, `Sublime Text` and `Emacs`
   compatibility
 - `Client`, `ServiceResource`, `Resource`, `Waiter` `Paginator` type
   annotations for each service
 - Generated `TypeDefs` for each service
 - Generated `Literals` for each service
-- Auto discovery of types for `boto3.client` and `boto3.session` calls
-- Auto discovery of types for `session.client` and `session.session` calls
+- Auto discovery of types for `boto3.client` and `boto3.resource` calls
+- Auto discovery of types for `session.client` and `session.resource` calls
 - Auto discovery of types for `client.get_waiter` and `client.get_paginator`
   calls
 - Auto discovery of types for `ServiceResource` and `Resource` collections
 - Auto discovery of types for `aiobotocore.Session.create_client` calls
 
 <a id="latest-changes"></a>
```

### Comparing `types-aiobotocore-iot-2.5.0.post1/types_aiobotocore_iot.egg-info/SOURCES.txt` & `types-aiobotocore-iot-2.5.1/types_aiobotocore_iot.egg-info/SOURCES.txt`

 * *Files identical despite different names*


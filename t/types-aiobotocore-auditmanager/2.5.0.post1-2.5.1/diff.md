# Comparing `tmp/types-aiobotocore-auditmanager-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-auditmanager-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-auditmanager-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-auditmanager-2.5.1.tar", last modified: Wed Jun 28 01:43:08 2023, max compression
```

## Comparing `types-aiobotocore-auditmanager-2.5.0.post1.tar` & `types-aiobotocore-auditmanager-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.034972 types-aiobotocore-auditmanager-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:55.000000 types-aiobotocore-auditmanager-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19681 2023-03-11 12:26:15.034972 types-aiobotocore-auditmanager-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    18090 2023-03-11 12:09:55.000000 types-aiobotocore-auditmanager-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:15.034972 types-aiobotocore-auditmanager-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:09:55.000000 types-aiobotocore-auditmanager-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.022972 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/
--rw-r--r--   0 runner    (1001) docker     (123)      482 2023-03-11 12:09:55.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      481 2023-03-11 12:09:55.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:09:55.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    45097 2023-03-11 12:09:55.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    45028 2023-03-11 12:09:55.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10293 2023-03-11 12:09:56.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10291 2023-03-11 12:09:55.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:55.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    56815 2023-03-11 12:09:57.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    56770 2023-03-11 12:09:56.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:55.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.034972 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19681 2023-03-11 12:26:14.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      819 2023-03-11 12:26:14.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:14.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:14.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:14.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:14.000000 types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.706098 types-aiobotocore-auditmanager-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:32.000000 types-aiobotocore-auditmanager-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19842 2023-06-28 01:43:08.702098 types-aiobotocore-auditmanager-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    18257 2023-06-28 01:26:32.000000 types-aiobotocore-auditmanager-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:08.706098 types-aiobotocore-auditmanager-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:26:32.000000 types-aiobotocore-auditmanager-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.702098 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/
+-rw-r--r--   0 runner    (1001) docker     (123)      482 2023-06-28 01:26:32.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      481 2023-06-28 01:26:32.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:26:32.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45840 2023-06-28 01:26:32.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45770 2023-06-28 01:26:32.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10640 2023-06-28 01:26:32.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10638 2023-06-28 01:26:32.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:32.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    57845 2023-06-28 01:26:34.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    57800 2023-06-28 01:26:33.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:32.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.702098 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19842 2023-06-28 01:43:08.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      819 2023-06-28 01:43:08.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:08.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:08.000000 types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-auditmanager-2.5.0.post1/LICENSE` & `types-aiobotocore-auditmanager-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-auditmanager-2.5.0.post1/PKG-INFO` & `types-aiobotocore-auditmanager-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-auditmanager
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AuditManager 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AuditManager 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-auditmanager"></a>
 
 # types-aiobotocore-auditmanager
 
 [![PyPI - types-aiobotocore-auditmanager](https://img.shields.io/pypi/v/types-aiobotocore-auditmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-auditmanager)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-auditmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-auditmanager)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-auditmanager?color=blue)](https://pypistats.org/packages/types-aiobotocore-auditmanager)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AuditManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager)
+[aiobotocore.AuditManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager)
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
 [types-aiobotocore-auditmanager docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/).
 
 See how it helps to find and fix potential bugs:
 
@@ -282,14 +282,15 @@
     ControlSetStatusType,
     ControlStatusType,
     ControlTypeType,
     DelegationStatusType,
     DeleteResourcesType,
     EvidenceFinderBackfillStatusType,
     EvidenceFinderEnablementStatusType,
+    ExportDestinationTypeType,
     FrameworkTypeType,
     KeywordInputTypeType,
     ObjectTypeEnumType,
     RoleTypeType,
     SettingAttributeType,
     ShareRequestActionType,
     ShareRequestStatusType,
@@ -328,99 +329,102 @@
     FrameworkMetadataTypeDef,
     AssessmentReportsDestinationTypeDef,
     AssessmentReportEvidenceErrorTypeDef,
     AssessmentReportMetadataTypeDef,
     AssessmentReportTypeDef,
     AssociateAssessmentReportEvidenceFolderRequestRequestTypeDef,
     BatchAssociateAssessmentReportEvidenceRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateDelegationRequestTypeDef,
     BatchDeleteDelegationByAssessmentErrorTypeDef,
     BatchDeleteDelegationByAssessmentRequestRequestTypeDef,
     BatchDisassociateAssessmentReportEvidenceRequestRequestTypeDef,
     ManualEvidenceTypeDef,
     ChangeLogTypeDef,
     EvidenceInsightsTypeDef,
     SourceKeywordTypeDef,
     ControlMetadataTypeDef,
     CreateAssessmentFrameworkControlTypeDef,
     CreateAssessmentReportRequestRequestTypeDef,
+    DefaultExportDestinationTypeDef,
     DelegationMetadataTypeDef,
     DeleteAssessmentFrameworkRequestRequestTypeDef,
     DeleteAssessmentFrameworkShareRequestRequestTypeDef,
     DeleteAssessmentReportRequestRequestTypeDef,
     DeleteAssessmentRequestRequestTypeDef,
     DeleteControlRequestRequestTypeDef,
+    DeregisterAccountResponseTypeDef,
     DeregisterOrganizationAdminAccountRequestRequestTypeDef,
     DeregistrationPolicyTypeDef,
     DisassociateAssessmentReportEvidenceFolderRequestRequestTypeDef,
     EvidenceFinderEnablementTypeDef,
     ResourceTypeDef,
+    GetAccountStatusResponseTypeDef,
     GetAssessmentFrameworkRequestRequestTypeDef,
     GetAssessmentReportUrlRequestRequestTypeDef,
     URLTypeDef,
     GetAssessmentRequestRequestTypeDef,
     GetChangeLogsRequestRequestTypeDef,
     GetControlRequestRequestTypeDef,
     GetDelegationsRequestRequestTypeDef,
     GetEvidenceByEvidenceFolderRequestRequestTypeDef,
+    GetEvidenceFileUploadUrlRequestRequestTypeDef,
+    GetEvidenceFileUploadUrlResponseTypeDef,
     GetEvidenceFolderRequestRequestTypeDef,
     GetEvidenceFoldersByAssessmentControlRequestRequestTypeDef,
     GetEvidenceFoldersByAssessmentRequestRequestTypeDef,
     GetEvidenceRequestRequestTypeDef,
     GetInsightsByAssessmentRequestRequestTypeDef,
     InsightsByAssessmentTypeDef,
     InsightsTypeDef,
+    GetOrganizationAdminAccountResponseTypeDef,
     ServiceMetadataTypeDef,
     GetSettingsRequestRequestTypeDef,
     ListAssessmentControlInsightsByControlDomainRequestRequestTypeDef,
     ListAssessmentFrameworkShareRequestsRequestRequestTypeDef,
     ListAssessmentFrameworksRequestRequestTypeDef,
     ListAssessmentReportsRequestRequestTypeDef,
     ListAssessmentsRequestRequestTypeDef,
     ListControlDomainInsightsByAssessmentRequestRequestTypeDef,
     ListControlDomainInsightsRequestRequestTypeDef,
     ListControlInsightsByControlDomainRequestRequestTypeDef,
     ListControlsRequestRequestTypeDef,
     ListKeywordsForDataSourceRequestRequestTypeDef,
+    ListKeywordsForDataSourceResponseTypeDef,
     ListNotificationsRequestRequestTypeDef,
     NotificationTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     RegisterAccountRequestRequestTypeDef,
+    RegisterAccountResponseTypeDef,
     RegisterOrganizationAdminAccountRequestRequestTypeDef,
+    RegisterOrganizationAdminAccountResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartAssessmentFrameworkShareRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAssessmentControlRequestRequestTypeDef,
     UpdateAssessmentControlSetStatusRequestRequestTypeDef,
     UpdateAssessmentFrameworkShareRequestRequestTypeDef,
     UpdateAssessmentStatusRequestRequestTypeDef,
     ValidateAssessmentReportIntegrityRequestRequestTypeDef,
+    ValidateAssessmentReportIntegrityResponseTypeDef,
     ScopeTypeDef,
     AssessmentMetadataItemTypeDef,
     AssessmentControlTypeDef,
-    BatchAssociateAssessmentReportEvidenceResponseTypeDef,
-    BatchDisassociateAssessmentReportEvidenceResponseTypeDef,
-    CreateAssessmentReportResponseTypeDef,
-    DeregisterAccountResponseTypeDef,
-    GetAccountStatusResponseTypeDef,
     GetEvidenceFolderResponseTypeDef,
     GetEvidenceFoldersByAssessmentControlResponseTypeDef,
     GetEvidenceFoldersByAssessmentResponseTypeDef,
-    GetOrganizationAdminAccountResponseTypeDef,
-    ListAssessmentFrameworkShareRequestsResponseTypeDef,
     ListAssessmentFrameworksResponseTypeDef,
-    ListAssessmentReportsResponseTypeDef,
-    ListKeywordsForDataSourceResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RegisterAccountResponseTypeDef,
-    RegisterOrganizationAdminAccountResponseTypeDef,
+    ListAssessmentFrameworkShareRequestsResponseTypeDef,
     StartAssessmentFrameworkShareResponseTypeDef,
     UpdateAssessmentFrameworkShareResponseTypeDef,
-    ValidateAssessmentReportIntegrityResponseTypeDef,
+    BatchAssociateAssessmentReportEvidenceResponseTypeDef,
+    BatchDisassociateAssessmentReportEvidenceResponseTypeDef,
+    ListAssessmentReportsResponseTypeDef,
+    CreateAssessmentReportResponseTypeDef,
     BatchCreateDelegationByAssessmentErrorTypeDef,
     BatchCreateDelegationByAssessmentRequestRequestTypeDef,
     BatchDeleteDelegationByAssessmentResponseTypeDef,
     BatchImportEvidenceToAssessmentControlErrorTypeDef,
     BatchImportEvidenceToAssessmentControlRequestRequestTypeDef,
     GetChangeLogsResponseTypeDef,
     ControlDomainInsightsTypeDef,
@@ -486,43 +490,43 @@
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

### Comparing `types-aiobotocore-auditmanager-2.5.0.post1/README.md` & `types-aiobotocore-auditmanager-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-auditmanager"></a>
 
 # types-aiobotocore-auditmanager
 
 [![PyPI - types-aiobotocore-auditmanager](https://img.shields.io/pypi/v/types-aiobotocore-auditmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-auditmanager)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-auditmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-auditmanager)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-auditmanager?color=blue)](https://pypistats.org/packages/types-aiobotocore-auditmanager)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AuditManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager)
+[aiobotocore.AuditManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager)
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
 [types-aiobotocore-auditmanager docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/).
 
 See how it helps to find and fix potential bugs:
 
@@ -249,14 +249,15 @@
     ControlSetStatusType,
     ControlStatusType,
     ControlTypeType,
     DelegationStatusType,
     DeleteResourcesType,
     EvidenceFinderBackfillStatusType,
     EvidenceFinderEnablementStatusType,
+    ExportDestinationTypeType,
     FrameworkTypeType,
     KeywordInputTypeType,
     ObjectTypeEnumType,
     RoleTypeType,
     SettingAttributeType,
     ShareRequestActionType,
     ShareRequestStatusType,
@@ -295,99 +296,102 @@
     FrameworkMetadataTypeDef,
     AssessmentReportsDestinationTypeDef,
     AssessmentReportEvidenceErrorTypeDef,
     AssessmentReportMetadataTypeDef,
     AssessmentReportTypeDef,
     AssociateAssessmentReportEvidenceFolderRequestRequestTypeDef,
     BatchAssociateAssessmentReportEvidenceRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateDelegationRequestTypeDef,
     BatchDeleteDelegationByAssessmentErrorTypeDef,
     BatchDeleteDelegationByAssessmentRequestRequestTypeDef,
     BatchDisassociateAssessmentReportEvidenceRequestRequestTypeDef,
     ManualEvidenceTypeDef,
     ChangeLogTypeDef,
     EvidenceInsightsTypeDef,
     SourceKeywordTypeDef,
     ControlMetadataTypeDef,
     CreateAssessmentFrameworkControlTypeDef,
     CreateAssessmentReportRequestRequestTypeDef,
+    DefaultExportDestinationTypeDef,
     DelegationMetadataTypeDef,
     DeleteAssessmentFrameworkRequestRequestTypeDef,
     DeleteAssessmentFrameworkShareRequestRequestTypeDef,
     DeleteAssessmentReportRequestRequestTypeDef,
     DeleteAssessmentRequestRequestTypeDef,
     DeleteControlRequestRequestTypeDef,
+    DeregisterAccountResponseTypeDef,
     DeregisterOrganizationAdminAccountRequestRequestTypeDef,
     DeregistrationPolicyTypeDef,
     DisassociateAssessmentReportEvidenceFolderRequestRequestTypeDef,
     EvidenceFinderEnablementTypeDef,
     ResourceTypeDef,
+    GetAccountStatusResponseTypeDef,
     GetAssessmentFrameworkRequestRequestTypeDef,
     GetAssessmentReportUrlRequestRequestTypeDef,
     URLTypeDef,
     GetAssessmentRequestRequestTypeDef,
     GetChangeLogsRequestRequestTypeDef,
     GetControlRequestRequestTypeDef,
     GetDelegationsRequestRequestTypeDef,
     GetEvidenceByEvidenceFolderRequestRequestTypeDef,
+    GetEvidenceFileUploadUrlRequestRequestTypeDef,
+    GetEvidenceFileUploadUrlResponseTypeDef,
     GetEvidenceFolderRequestRequestTypeDef,
     GetEvidenceFoldersByAssessmentControlRequestRequestTypeDef,
     GetEvidenceFoldersByAssessmentRequestRequestTypeDef,
     GetEvidenceRequestRequestTypeDef,
     GetInsightsByAssessmentRequestRequestTypeDef,
     InsightsByAssessmentTypeDef,
     InsightsTypeDef,
+    GetOrganizationAdminAccountResponseTypeDef,
     ServiceMetadataTypeDef,
     GetSettingsRequestRequestTypeDef,
     ListAssessmentControlInsightsByControlDomainRequestRequestTypeDef,
     ListAssessmentFrameworkShareRequestsRequestRequestTypeDef,
     ListAssessmentFrameworksRequestRequestTypeDef,
     ListAssessmentReportsRequestRequestTypeDef,
     ListAssessmentsRequestRequestTypeDef,
     ListControlDomainInsightsByAssessmentRequestRequestTypeDef,
     ListControlDomainInsightsRequestRequestTypeDef,
     ListControlInsightsByControlDomainRequestRequestTypeDef,
     ListControlsRequestRequestTypeDef,
     ListKeywordsForDataSourceRequestRequestTypeDef,
+    ListKeywordsForDataSourceResponseTypeDef,
     ListNotificationsRequestRequestTypeDef,
     NotificationTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     RegisterAccountRequestRequestTypeDef,
+    RegisterAccountResponseTypeDef,
     RegisterOrganizationAdminAccountRequestRequestTypeDef,
+    RegisterOrganizationAdminAccountResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartAssessmentFrameworkShareRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAssessmentControlRequestRequestTypeDef,
     UpdateAssessmentControlSetStatusRequestRequestTypeDef,
     UpdateAssessmentFrameworkShareRequestRequestTypeDef,
     UpdateAssessmentStatusRequestRequestTypeDef,
     ValidateAssessmentReportIntegrityRequestRequestTypeDef,
+    ValidateAssessmentReportIntegrityResponseTypeDef,
     ScopeTypeDef,
     AssessmentMetadataItemTypeDef,
     AssessmentControlTypeDef,
-    BatchAssociateAssessmentReportEvidenceResponseTypeDef,
-    BatchDisassociateAssessmentReportEvidenceResponseTypeDef,
-    CreateAssessmentReportResponseTypeDef,
-    DeregisterAccountResponseTypeDef,
-    GetAccountStatusResponseTypeDef,
     GetEvidenceFolderResponseTypeDef,
     GetEvidenceFoldersByAssessmentControlResponseTypeDef,
     GetEvidenceFoldersByAssessmentResponseTypeDef,
-    GetOrganizationAdminAccountResponseTypeDef,
-    ListAssessmentFrameworkShareRequestsResponseTypeDef,
     ListAssessmentFrameworksResponseTypeDef,
-    ListAssessmentReportsResponseTypeDef,
-    ListKeywordsForDataSourceResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RegisterAccountResponseTypeDef,
-    RegisterOrganizationAdminAccountResponseTypeDef,
+    ListAssessmentFrameworkShareRequestsResponseTypeDef,
     StartAssessmentFrameworkShareResponseTypeDef,
     UpdateAssessmentFrameworkShareResponseTypeDef,
-    ValidateAssessmentReportIntegrityResponseTypeDef,
+    BatchAssociateAssessmentReportEvidenceResponseTypeDef,
+    BatchDisassociateAssessmentReportEvidenceResponseTypeDef,
+    ListAssessmentReportsResponseTypeDef,
+    CreateAssessmentReportResponseTypeDef,
     BatchCreateDelegationByAssessmentErrorTypeDef,
     BatchCreateDelegationByAssessmentRequestRequestTypeDef,
     BatchDeleteDelegationByAssessmentResponseTypeDef,
     BatchImportEvidenceToAssessmentControlErrorTypeDef,
     BatchImportEvidenceToAssessmentControlRequestRequestTypeDef,
     GetChangeLogsResponseTypeDef,
     ControlDomainInsightsTypeDef,
@@ -453,43 +457,43 @@
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

### Comparing `types-aiobotocore-auditmanager-2.5.0.post1/setup.py` & `types-aiobotocore-auditmanager-2.5.1/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-auditmanager.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-auditmanager",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_auditmanager"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.AuditManager 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.AuditManager 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -48,11 +48,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/"
         ),
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

### Comparing `types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/__main__.py` & `types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/__main__.py`

 * *Files 20% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.AuditManager 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.AuditManager 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager\nOther"
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

### Comparing `types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/client.py` & `types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -41,24 +41,26 @@
     CreateAssessmentFrameworkControlSetTypeDef,
     CreateAssessmentFrameworkResponseTypeDef,
     CreateAssessmentReportResponseTypeDef,
     CreateAssessmentResponseTypeDef,
     CreateControlMappingSourceTypeDef,
     CreateControlResponseTypeDef,
     CreateDelegationRequestTypeDef,
+    DefaultExportDestinationTypeDef,
     DeregisterAccountResponseTypeDef,
     DeregistrationPolicyTypeDef,
     GetAccountStatusResponseTypeDef,
     GetAssessmentFrameworkResponseTypeDef,
     GetAssessmentReportUrlResponseTypeDef,
     GetAssessmentResponseTypeDef,
     GetChangeLogsResponseTypeDef,
     GetControlResponseTypeDef,
     GetDelegationsResponseTypeDef,
     GetEvidenceByEvidenceFolderResponseTypeDef,
+    GetEvidenceFileUploadUrlResponseTypeDef,
     GetEvidenceFolderResponseTypeDef,
     GetEvidenceFoldersByAssessmentControlResponseTypeDef,
     GetEvidenceFoldersByAssessmentResponseTypeDef,
     GetEvidenceResponseTypeDef,
     GetInsightsByAssessmentResponseTypeDef,
     GetInsightsResponseTypeDef,
     GetOrganizationAdminAccountResponseTypeDef,
@@ -192,16 +194,15 @@
         *,
         assessmentId: str,
         controlSetId: str,
         controlId: str,
         manualEvidence: Sequence[ManualEvidenceTypeDef]
     ) -> BatchImportEvidenceToAssessmentControlResponseTypeDef:
         """
-        Uploads one or more pieces of evidence to a control in an Audit Manager
-        assessment.
+        Adds one or more pieces of evidence to a control in an Audit Manager assessment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.batch_import_evidence_to_assessment_control)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#batch_import_evidence_to_assessment_control)
         """
 
     def can_paginate(self, operation_name: str) -> bool:
         """
@@ -367,43 +368,43 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#generate_presigned_url)
         """
 
     async def get_account_status(self) -> GetAccountStatusResponseTypeDef:
         """
-        Returns the registration status of an account in Audit Manager.
+        Gets the registration status of an account in Audit Manager.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_account_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_account_status)
         """
 
     async def get_assessment(self, *, assessmentId: str) -> GetAssessmentResponseTypeDef:
         """
-        Returns an assessment from Audit Manager.
+        Gets information about a specified assessment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_assessment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_assessment)
         """
 
     async def get_assessment_framework(
         self, *, frameworkId: str
     ) -> GetAssessmentFrameworkResponseTypeDef:
         """
-        Returns a framework from Audit Manager.
+        Gets information about a specified framework.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_assessment_framework)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_assessment_framework)
         """
 
     async def get_assessment_report_url(
         self, *, assessmentReportId: str, assessmentId: str
     ) -> GetAssessmentReportUrlResponseTypeDef:
         """
-        Returns the URL of an assessment report in Audit Manager.
+        Gets the URL of an assessment report in Audit Manager.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_assessment_report_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_assessment_report_url)
         """
 
     async def get_change_logs(
         self,
@@ -411,43 +412,43 @@
         assessmentId: str,
         controlSetId: str = ...,
         controlId: str = ...,
         nextToken: str = ...,
         maxResults: int = ...
     ) -> GetChangeLogsResponseTypeDef:
         """
-        Returns a list of changelogs from Audit Manager.
+        Gets a list of changelogs from Audit Manager.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_change_logs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_change_logs)
         """
 
     async def get_control(self, *, controlId: str) -> GetControlResponseTypeDef:
         """
-        Returns a control from Audit Manager.
+        Gets information about a specified control.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_control)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_control)
         """
 
     async def get_delegations(
         self, *, nextToken: str = ..., maxResults: int = ...
     ) -> GetDelegationsResponseTypeDef:
         """
-        Returns a list of delegations from an audit owner to a delegate.
+        Gets a list of delegations from an audit owner to a delegate.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_delegations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_delegations)
         """
 
     async def get_evidence(
         self, *, assessmentId: str, controlSetId: str, evidenceFolderId: str, evidenceId: str
     ) -> GetEvidenceResponseTypeDef:
         """
-        Returns evidence from Audit Manager.
+        Gets information about a specified evidence item.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_evidence)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_evidence)
         """
 
     async def get_evidence_by_evidence_folder(
         self,
@@ -455,35 +456,46 @@
         assessmentId: str,
         controlSetId: str,
         evidenceFolderId: str,
         nextToken: str = ...,
         maxResults: int = ...
     ) -> GetEvidenceByEvidenceFolderResponseTypeDef:
         """
-        Returns all evidence from a specified evidence folder in Audit Manager.
+        Gets all evidence from a specified evidence folder in Audit Manager.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_evidence_by_evidence_folder)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_evidence_by_evidence_folder)
         """
 
+    async def get_evidence_file_upload_url(
+        self, *, fileName: str
+    ) -> GetEvidenceFileUploadUrlResponseTypeDef:
+        """
+        Creates a presigned Amazon S3 URL that can be used to upload a file as manual
+        evidence.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_evidence_file_upload_url)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_evidence_file_upload_url)
+        """
+
     async def get_evidence_folder(
         self, *, assessmentId: str, controlSetId: str, evidenceFolderId: str
     ) -> GetEvidenceFolderResponseTypeDef:
         """
-        Returns an evidence folder from the specified assessment in Audit Manager.
+        Gets an evidence folder from a specified assessment in Audit Manager.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_evidence_folder)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_evidence_folder)
         """
 
     async def get_evidence_folders_by_assessment(
         self, *, assessmentId: str, nextToken: str = ..., maxResults: int = ...
     ) -> GetEvidenceFoldersByAssessmentResponseTypeDef:
         """
-        Returns the evidence folders from a specified assessment in Audit Manager.
+        Gets the evidence folders from a specified assessment in Audit Manager.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_evidence_folders_by_assessment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_evidence_folders_by_assessment)
         """
 
     async def get_evidence_folders_by_assessment_control(
         self,
@@ -491,16 +503,16 @@
         assessmentId: str,
         controlSetId: str,
         controlId: str,
         nextToken: str = ...,
         maxResults: int = ...
     ) -> GetEvidenceFoldersByAssessmentControlResponseTypeDef:
         """
-        Returns a list of evidence folders that are associated with a specified control
-        in an Audit Manager assessment.
+        Gets a list of evidence folders that are associated with a specified control in
+        an Audit Manager assessment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_evidence_folders_by_assessment_control)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_evidence_folders_by_assessment_control)
         """
 
     async def get_insights(self) -> GetInsightsResponseTypeDef:
         """
@@ -518,33 +530,33 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_insights_by_assessment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_insights_by_assessment)
         """
 
     async def get_organization_admin_account(self) -> GetOrganizationAdminAccountResponseTypeDef:
         """
-        Returns the name of the delegated Amazon Web Services administrator account for
-        the organization.
+        Gets the name of the delegated Amazon Web Services administrator account for a
+        specified organization.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_organization_admin_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_organization_admin_account)
         """
 
     async def get_services_in_scope(self) -> GetServicesInScopeResponseTypeDef:
         """
-        Returns a list of all of the Amazon Web Services that you can choose to include
-        in your assessment.
+        Gets a list of all of the Amazon Web Services that you can choose to include in
+        your assessment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_services_in_scope)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_services_in_scope)
         """
 
     async def get_settings(self, *, attribute: SettingAttributeType) -> GetSettingsResponseTypeDef:
         """
-        Returns the settings for the specified Amazon Web Services account.
+        Gets the settings for a specified Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_settings)
         """
 
     async def list_assessment_control_insights_by_control_domain(
         self,
@@ -830,15 +842,16 @@
         self,
         *,
         snsTopic: str = ...,
         defaultAssessmentReportsDestination: AssessmentReportsDestinationTypeDef = ...,
         defaultProcessOwners: Sequence[RoleTypeDef] = ...,
         kmsKey: str = ...,
         evidenceFinderEnabled: bool = ...,
-        deregistrationPolicy: DeregistrationPolicyTypeDef = ...
+        deregistrationPolicy: DeregistrationPolicyTypeDef = ...,
+        defaultExportDestination: DefaultExportDestinationTypeDef = ...
     ) -> UpdateSettingsResponseTypeDef:
         """
         Updates Audit Manager settings for the current account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.update_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#update_settings)
         """
```

### Comparing `types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/client.pyi` & `types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/client.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -41,24 +41,26 @@
     CreateAssessmentFrameworkControlSetTypeDef,
     CreateAssessmentFrameworkResponseTypeDef,
     CreateAssessmentReportResponseTypeDef,
     CreateAssessmentResponseTypeDef,
     CreateControlMappingSourceTypeDef,
     CreateControlResponseTypeDef,
     CreateDelegationRequestTypeDef,
+    DefaultExportDestinationTypeDef,
     DeregisterAccountResponseTypeDef,
     DeregistrationPolicyTypeDef,
     GetAccountStatusResponseTypeDef,
     GetAssessmentFrameworkResponseTypeDef,
     GetAssessmentReportUrlResponseTypeDef,
     GetAssessmentResponseTypeDef,
     GetChangeLogsResponseTypeDef,
     GetControlResponseTypeDef,
     GetDelegationsResponseTypeDef,
     GetEvidenceByEvidenceFolderResponseTypeDef,
+    GetEvidenceFileUploadUrlResponseTypeDef,
     GetEvidenceFolderResponseTypeDef,
     GetEvidenceFoldersByAssessmentControlResponseTypeDef,
     GetEvidenceFoldersByAssessmentResponseTypeDef,
     GetEvidenceResponseTypeDef,
     GetInsightsByAssessmentResponseTypeDef,
     GetInsightsResponseTypeDef,
     GetOrganizationAdminAccountResponseTypeDef,
@@ -183,16 +185,15 @@
         *,
         assessmentId: str,
         controlSetId: str,
         controlId: str,
         manualEvidence: Sequence[ManualEvidenceTypeDef]
     ) -> BatchImportEvidenceToAssessmentControlResponseTypeDef:
         """
-        Uploads one or more pieces of evidence to a control in an Audit Manager
-        assessment.
+        Adds one or more pieces of evidence to a control in an Audit Manager assessment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.batch_import_evidence_to_assessment_control)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#batch_import_evidence_to_assessment_control)
         """
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
@@ -342,129 +343,139 @@
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#generate_presigned_url)
         """
     async def get_account_status(self) -> GetAccountStatusResponseTypeDef:
         """
-        Returns the registration status of an account in Audit Manager.
+        Gets the registration status of an account in Audit Manager.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_account_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_account_status)
         """
     async def get_assessment(self, *, assessmentId: str) -> GetAssessmentResponseTypeDef:
         """
-        Returns an assessment from Audit Manager.
+        Gets information about a specified assessment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_assessment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_assessment)
         """
     async def get_assessment_framework(
         self, *, frameworkId: str
     ) -> GetAssessmentFrameworkResponseTypeDef:
         """
-        Returns a framework from Audit Manager.
+        Gets information about a specified framework.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_assessment_framework)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_assessment_framework)
         """
     async def get_assessment_report_url(
         self, *, assessmentReportId: str, assessmentId: str
     ) -> GetAssessmentReportUrlResponseTypeDef:
         """
-        Returns the URL of an assessment report in Audit Manager.
+        Gets the URL of an assessment report in Audit Manager.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_assessment_report_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_assessment_report_url)
         """
     async def get_change_logs(
         self,
         *,
         assessmentId: str,
         controlSetId: str = ...,
         controlId: str = ...,
         nextToken: str = ...,
         maxResults: int = ...
     ) -> GetChangeLogsResponseTypeDef:
         """
-        Returns a list of changelogs from Audit Manager.
+        Gets a list of changelogs from Audit Manager.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_change_logs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_change_logs)
         """
     async def get_control(self, *, controlId: str) -> GetControlResponseTypeDef:
         """
-        Returns a control from Audit Manager.
+        Gets information about a specified control.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_control)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_control)
         """
     async def get_delegations(
         self, *, nextToken: str = ..., maxResults: int = ...
     ) -> GetDelegationsResponseTypeDef:
         """
-        Returns a list of delegations from an audit owner to a delegate.
+        Gets a list of delegations from an audit owner to a delegate.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_delegations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_delegations)
         """
     async def get_evidence(
         self, *, assessmentId: str, controlSetId: str, evidenceFolderId: str, evidenceId: str
     ) -> GetEvidenceResponseTypeDef:
         """
-        Returns evidence from Audit Manager.
+        Gets information about a specified evidence item.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_evidence)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_evidence)
         """
     async def get_evidence_by_evidence_folder(
         self,
         *,
         assessmentId: str,
         controlSetId: str,
         evidenceFolderId: str,
         nextToken: str = ...,
         maxResults: int = ...
     ) -> GetEvidenceByEvidenceFolderResponseTypeDef:
         """
-        Returns all evidence from a specified evidence folder in Audit Manager.
+        Gets all evidence from a specified evidence folder in Audit Manager.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_evidence_by_evidence_folder)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_evidence_by_evidence_folder)
         """
+    async def get_evidence_file_upload_url(
+        self, *, fileName: str
+    ) -> GetEvidenceFileUploadUrlResponseTypeDef:
+        """
+        Creates a presigned Amazon S3 URL that can be used to upload a file as manual
+        evidence.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_evidence_file_upload_url)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_evidence_file_upload_url)
+        """
     async def get_evidence_folder(
         self, *, assessmentId: str, controlSetId: str, evidenceFolderId: str
     ) -> GetEvidenceFolderResponseTypeDef:
         """
-        Returns an evidence folder from the specified assessment in Audit Manager.
+        Gets an evidence folder from a specified assessment in Audit Manager.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_evidence_folder)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_evidence_folder)
         """
     async def get_evidence_folders_by_assessment(
         self, *, assessmentId: str, nextToken: str = ..., maxResults: int = ...
     ) -> GetEvidenceFoldersByAssessmentResponseTypeDef:
         """
-        Returns the evidence folders from a specified assessment in Audit Manager.
+        Gets the evidence folders from a specified assessment in Audit Manager.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_evidence_folders_by_assessment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_evidence_folders_by_assessment)
         """
     async def get_evidence_folders_by_assessment_control(
         self,
         *,
         assessmentId: str,
         controlSetId: str,
         controlId: str,
         nextToken: str = ...,
         maxResults: int = ...
     ) -> GetEvidenceFoldersByAssessmentControlResponseTypeDef:
         """
-        Returns a list of evidence folders that are associated with a specified control
-        in an Audit Manager assessment.
+        Gets a list of evidence folders that are associated with a specified control in
+        an Audit Manager assessment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_evidence_folders_by_assessment_control)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_evidence_folders_by_assessment_control)
         """
     async def get_insights(self) -> GetInsightsResponseTypeDef:
         """
         Gets the latest analytics data for all your current active assessments.
@@ -479,31 +490,31 @@
         Gets the latest analytics data for a specific active assessment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_insights_by_assessment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_insights_by_assessment)
         """
     async def get_organization_admin_account(self) -> GetOrganizationAdminAccountResponseTypeDef:
         """
-        Returns the name of the delegated Amazon Web Services administrator account for
-        the organization.
+        Gets the name of the delegated Amazon Web Services administrator account for a
+        specified organization.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_organization_admin_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_organization_admin_account)
         """
     async def get_services_in_scope(self) -> GetServicesInScopeResponseTypeDef:
         """
-        Returns a list of all of the Amazon Web Services that you can choose to include
-        in your assessment.
+        Gets a list of all of the Amazon Web Services that you can choose to include in
+        your assessment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_services_in_scope)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_services_in_scope)
         """
     async def get_settings(self, *, attribute: SettingAttributeType) -> GetSettingsResponseTypeDef:
         """
-        Returns the settings for the specified Amazon Web Services account.
+        Gets the settings for a specified Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.get_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#get_settings)
         """
     async def list_assessment_control_insights_by_control_domain(
         self,
         *,
@@ -764,15 +775,16 @@
         self,
         *,
         snsTopic: str = ...,
         defaultAssessmentReportsDestination: AssessmentReportsDestinationTypeDef = ...,
         defaultProcessOwners: Sequence[RoleTypeDef] = ...,
         kmsKey: str = ...,
         evidenceFinderEnabled: bool = ...,
-        deregistrationPolicy: DeregistrationPolicyTypeDef = ...
+        deregistrationPolicy: DeregistrationPolicyTypeDef = ...,
+        defaultExportDestination: DefaultExportDestinationTypeDef = ...
     ) -> UpdateSettingsResponseTypeDef:
         """
         Updates Audit Manager settings for the current account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager.Client.update_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/client/#update_settings)
         """
```

### Comparing `types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/literals.py` & `types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -29,14 +29,15 @@
     "ControlSetStatusType",
     "ControlStatusType",
     "ControlTypeType",
     "DelegationStatusType",
     "DeleteResourcesType",
     "EvidenceFinderBackfillStatusType",
     "EvidenceFinderEnablementStatusType",
+    "ExportDestinationTypeType",
     "FrameworkTypeType",
     "KeywordInputTypeType",
     "ObjectTypeEnumType",
     "RoleTypeType",
     "SettingAttributeType",
     "ShareRequestActionType",
     "ShareRequestStatusType",
@@ -71,23 +72,25 @@
 ControlTypeType = Literal["Custom", "Standard"]
 DelegationStatusType = Literal["COMPLETE", "IN_PROGRESS", "UNDER_REVIEW"]
 DeleteResourcesType = Literal["ALL", "DEFAULT"]
 EvidenceFinderBackfillStatusType = Literal["COMPLETED", "IN_PROGRESS", "NOT_STARTED"]
 EvidenceFinderEnablementStatusType = Literal[
     "DISABLED", "DISABLE_IN_PROGRESS", "ENABLED", "ENABLE_IN_PROGRESS"
 ]
+ExportDestinationTypeType = Literal["S3"]
 FrameworkTypeType = Literal["Custom", "Standard"]
-KeywordInputTypeType = Literal["SELECT_FROM_LIST"]
+KeywordInputTypeType = Literal["INPUT_TEXT", "SELECT_FROM_LIST", "UPLOAD_FILE"]
 ObjectTypeEnumType = Literal[
     "ASSESSMENT", "ASSESSMENT_REPORT", "CONTROL", "CONTROL_SET", "DELEGATION"
 ]
 RoleTypeType = Literal["PROCESS_OWNER", "RESOURCE_OWNER"]
 SettingAttributeType = Literal[
     "ALL",
     "DEFAULT_ASSESSMENT_REPORTS_DESTINATION",
+    "DEFAULT_EXPORT_DESTINATION",
     "DEFAULT_PROCESS_OWNERS",
     "DEREGISTRATION_POLICY",
     "EVIDENCE_FINDER_ENABLEMENT",
     "IS_AWS_ORG_ENABLED",
     "SNS_TOPIC",
 ]
 ShareRequestActionType = Literal["ACCEPT", "DECLINE", "REVOKE"]
@@ -159,14 +162,15 @@
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
@@ -245,14 +249,15 @@
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
@@ -263,14 +268,15 @@
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
@@ -306,14 +312,15 @@
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
@@ -332,16 +339,19 @@
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
@@ -425,15 +435,17 @@
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
```

### Comparing `types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/literals.pyi` & `types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -28,14 +28,15 @@
     "ControlSetStatusType",
     "ControlStatusType",
     "ControlTypeType",
     "DelegationStatusType",
     "DeleteResourcesType",
     "EvidenceFinderBackfillStatusType",
     "EvidenceFinderEnablementStatusType",
+    "ExportDestinationTypeType",
     "FrameworkTypeType",
     "KeywordInputTypeType",
     "ObjectTypeEnumType",
     "RoleTypeType",
     "SettingAttributeType",
     "ShareRequestActionType",
     "ShareRequestStatusType",
@@ -69,23 +70,25 @@
 ControlTypeType = Literal["Custom", "Standard"]
 DelegationStatusType = Literal["COMPLETE", "IN_PROGRESS", "UNDER_REVIEW"]
 DeleteResourcesType = Literal["ALL", "DEFAULT"]
 EvidenceFinderBackfillStatusType = Literal["COMPLETED", "IN_PROGRESS", "NOT_STARTED"]
 EvidenceFinderEnablementStatusType = Literal[
     "DISABLED", "DISABLE_IN_PROGRESS", "ENABLED", "ENABLE_IN_PROGRESS"
 ]
+ExportDestinationTypeType = Literal["S3"]
 FrameworkTypeType = Literal["Custom", "Standard"]
-KeywordInputTypeType = Literal["SELECT_FROM_LIST"]
+KeywordInputTypeType = Literal["INPUT_TEXT", "SELECT_FROM_LIST", "UPLOAD_FILE"]
 ObjectTypeEnumType = Literal[
     "ASSESSMENT", "ASSESSMENT_REPORT", "CONTROL", "CONTROL_SET", "DELEGATION"
 ]
 RoleTypeType = Literal["PROCESS_OWNER", "RESOURCE_OWNER"]
 SettingAttributeType = Literal[
     "ALL",
     "DEFAULT_ASSESSMENT_REPORTS_DESTINATION",
+    "DEFAULT_EXPORT_DESTINATION",
     "DEFAULT_PROCESS_OWNERS",
     "DEREGISTRATION_POLICY",
     "EVIDENCE_FINDER_ENABLEMENT",
     "IS_AWS_ORG_ENABLED",
     "SNS_TOPIC",
 ]
 ShareRequestActionType = Literal["ACCEPT", "DECLINE", "REVOKE"]
@@ -157,14 +160,15 @@
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
@@ -243,14 +247,15 @@
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
@@ -261,14 +266,15 @@
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
@@ -304,14 +310,15 @@
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
@@ -330,16 +337,19 @@
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
@@ -423,15 +433,17 @@
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
```

### Comparing `types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/type_defs.py` & `types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -25,14 +25,15 @@
     ControlStatusType,
     ControlTypeType,
     DelegationStatusType,
     DeleteResourcesType,
     EvidenceFinderBackfillStatusType,
     EvidenceFinderEnablementStatusType,
     FrameworkTypeType,
+    KeywordInputTypeType,
     ObjectTypeEnumType,
     RoleTypeType,
     SettingAttributeType,
     ShareRequestActionType,
     ShareRequestStatusType,
     ShareRequestTypeType,
     SourceFrequencyType,
@@ -62,99 +63,102 @@
     "FrameworkMetadataTypeDef",
     "AssessmentReportsDestinationTypeDef",
     "AssessmentReportEvidenceErrorTypeDef",
     "AssessmentReportMetadataTypeDef",
     "AssessmentReportTypeDef",
     "AssociateAssessmentReportEvidenceFolderRequestRequestTypeDef",
     "BatchAssociateAssessmentReportEvidenceRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateDelegationRequestTypeDef",
     "BatchDeleteDelegationByAssessmentErrorTypeDef",
     "BatchDeleteDelegationByAssessmentRequestRequestTypeDef",
     "BatchDisassociateAssessmentReportEvidenceRequestRequestTypeDef",
     "ManualEvidenceTypeDef",
     "ChangeLogTypeDef",
     "EvidenceInsightsTypeDef",
     "SourceKeywordTypeDef",
     "ControlMetadataTypeDef",
     "CreateAssessmentFrameworkControlTypeDef",
     "CreateAssessmentReportRequestRequestTypeDef",
+    "DefaultExportDestinationTypeDef",
     "DelegationMetadataTypeDef",
     "DeleteAssessmentFrameworkRequestRequestTypeDef",
     "DeleteAssessmentFrameworkShareRequestRequestTypeDef",
     "DeleteAssessmentReportRequestRequestTypeDef",
     "DeleteAssessmentRequestRequestTypeDef",
     "DeleteControlRequestRequestTypeDef",
+    "DeregisterAccountResponseTypeDef",
     "DeregisterOrganizationAdminAccountRequestRequestTypeDef",
     "DeregistrationPolicyTypeDef",
     "DisassociateAssessmentReportEvidenceFolderRequestRequestTypeDef",
     "EvidenceFinderEnablementTypeDef",
     "ResourceTypeDef",
+    "GetAccountStatusResponseTypeDef",
     "GetAssessmentFrameworkRequestRequestTypeDef",
     "GetAssessmentReportUrlRequestRequestTypeDef",
     "URLTypeDef",
     "GetAssessmentRequestRequestTypeDef",
     "GetChangeLogsRequestRequestTypeDef",
     "GetControlRequestRequestTypeDef",
     "GetDelegationsRequestRequestTypeDef",
     "GetEvidenceByEvidenceFolderRequestRequestTypeDef",
+    "GetEvidenceFileUploadUrlRequestRequestTypeDef",
+    "GetEvidenceFileUploadUrlResponseTypeDef",
     "GetEvidenceFolderRequestRequestTypeDef",
     "GetEvidenceFoldersByAssessmentControlRequestRequestTypeDef",
     "GetEvidenceFoldersByAssessmentRequestRequestTypeDef",
     "GetEvidenceRequestRequestTypeDef",
     "GetInsightsByAssessmentRequestRequestTypeDef",
     "InsightsByAssessmentTypeDef",
     "InsightsTypeDef",
+    "GetOrganizationAdminAccountResponseTypeDef",
     "ServiceMetadataTypeDef",
     "GetSettingsRequestRequestTypeDef",
     "ListAssessmentControlInsightsByControlDomainRequestRequestTypeDef",
     "ListAssessmentFrameworkShareRequestsRequestRequestTypeDef",
     "ListAssessmentFrameworksRequestRequestTypeDef",
     "ListAssessmentReportsRequestRequestTypeDef",
     "ListAssessmentsRequestRequestTypeDef",
     "ListControlDomainInsightsByAssessmentRequestRequestTypeDef",
     "ListControlDomainInsightsRequestRequestTypeDef",
     "ListControlInsightsByControlDomainRequestRequestTypeDef",
     "ListControlsRequestRequestTypeDef",
     "ListKeywordsForDataSourceRequestRequestTypeDef",
+    "ListKeywordsForDataSourceResponseTypeDef",
     "ListNotificationsRequestRequestTypeDef",
     "NotificationTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "RegisterAccountRequestRequestTypeDef",
+    "RegisterAccountResponseTypeDef",
     "RegisterOrganizationAdminAccountRequestRequestTypeDef",
+    "RegisterOrganizationAdminAccountResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "StartAssessmentFrameworkShareRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAssessmentControlRequestRequestTypeDef",
     "UpdateAssessmentControlSetStatusRequestRequestTypeDef",
     "UpdateAssessmentFrameworkShareRequestRequestTypeDef",
     "UpdateAssessmentStatusRequestRequestTypeDef",
     "ValidateAssessmentReportIntegrityRequestRequestTypeDef",
+    "ValidateAssessmentReportIntegrityResponseTypeDef",
     "ScopeTypeDef",
     "AssessmentMetadataItemTypeDef",
     "AssessmentControlTypeDef",
-    "BatchAssociateAssessmentReportEvidenceResponseTypeDef",
-    "BatchDisassociateAssessmentReportEvidenceResponseTypeDef",
-    "CreateAssessmentReportResponseTypeDef",
-    "DeregisterAccountResponseTypeDef",
-    "GetAccountStatusResponseTypeDef",
     "GetEvidenceFolderResponseTypeDef",
     "GetEvidenceFoldersByAssessmentControlResponseTypeDef",
     "GetEvidenceFoldersByAssessmentResponseTypeDef",
-    "GetOrganizationAdminAccountResponseTypeDef",
-    "ListAssessmentFrameworkShareRequestsResponseTypeDef",
     "ListAssessmentFrameworksResponseTypeDef",
-    "ListAssessmentReportsResponseTypeDef",
-    "ListKeywordsForDataSourceResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RegisterAccountResponseTypeDef",
-    "RegisterOrganizationAdminAccountResponseTypeDef",
+    "ListAssessmentFrameworkShareRequestsResponseTypeDef",
     "StartAssessmentFrameworkShareResponseTypeDef",
     "UpdateAssessmentFrameworkShareResponseTypeDef",
-    "ValidateAssessmentReportIntegrityResponseTypeDef",
+    "BatchAssociateAssessmentReportEvidenceResponseTypeDef",
+    "BatchDisassociateAssessmentReportEvidenceResponseTypeDef",
+    "ListAssessmentReportsResponseTypeDef",
+    "CreateAssessmentReportResponseTypeDef",
     "BatchCreateDelegationByAssessmentErrorTypeDef",
     "BatchCreateDelegationByAssessmentRequestRequestTypeDef",
     "BatchDeleteDelegationByAssessmentResponseTypeDef",
     "BatchImportEvidenceToAssessmentControlErrorTypeDef",
     "BatchImportEvidenceToAssessmentControlRequestRequestTypeDef",
     "GetChangeLogsResponseTypeDef",
     "ControlDomainInsightsTypeDef",
@@ -405,25 +409,14 @@
     {
         "assessmentId": str,
         "evidenceFolderId": str,
         "evidenceIds": Sequence[str],
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
-    {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
-    },
-)
-
 CreateDelegationRequestTypeDef = TypedDict(
     "CreateDelegationRequestTypeDef",
     {
         "comment": str,
         "controlSetId": str,
         "roleArn": str,
         "roleType": RoleTypeType,
@@ -458,14 +451,16 @@
     },
 )
 
 ManualEvidenceTypeDef = TypedDict(
     "ManualEvidenceTypeDef",
     {
         "s3ResourcePath": str,
+        "textResponse": str,
+        "evidenceFileName": str,
     },
     total=False,
 )
 
 ChangeLogTypeDef = TypedDict(
     "ChangeLogTypeDef",
     {
@@ -487,15 +482,15 @@
     },
     total=False,
 )
 
 SourceKeywordTypeDef = TypedDict(
     "SourceKeywordTypeDef",
     {
-        "keywordInputType": Literal["SELECT_FROM_LIST"],
+        "keywordInputType": KeywordInputTypeType,
         "keywordValue": str,
     },
     total=False,
 )
 
 ControlMetadataTypeDef = TypedDict(
     "ControlMetadataTypeDef",
@@ -537,14 +532,23 @@
 class CreateAssessmentReportRequestRequestTypeDef(
     _RequiredCreateAssessmentReportRequestRequestTypeDef,
     _OptionalCreateAssessmentReportRequestRequestTypeDef,
 ):
     pass
 
 
+DefaultExportDestinationTypeDef = TypedDict(
+    "DefaultExportDestinationTypeDef",
+    {
+        "destinationType": Literal["S3"],
+        "destination": str,
+    },
+    total=False,
+)
+
 DelegationMetadataTypeDef = TypedDict(
     "DelegationMetadataTypeDef",
     {
         "id": str,
         "assessmentName": str,
         "assessmentId": str,
         "status": DelegationStatusType,
@@ -588,14 +592,22 @@
 DeleteControlRequestRequestTypeDef = TypedDict(
     "DeleteControlRequestRequestTypeDef",
     {
         "controlId": str,
     },
 )
 
+DeregisterAccountResponseTypeDef = TypedDict(
+    "DeregisterAccountResponseTypeDef",
+    {
+        "status": AccountStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeregisterOrganizationAdminAccountRequestRequestTypeDef = TypedDict(
     "DeregisterOrganizationAdminAccountRequestRequestTypeDef",
     {
         "adminAccountId": str,
     },
     total=False,
 )
@@ -633,14 +645,22 @@
         "arn": str,
         "value": str,
         "complianceCheck": str,
     },
     total=False,
 )
 
+GetAccountStatusResponseTypeDef = TypedDict(
+    "GetAccountStatusResponseTypeDef",
+    {
+        "status": AccountStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAssessmentFrameworkRequestRequestTypeDef = TypedDict(
     "GetAssessmentFrameworkRequestRequestTypeDef",
     {
         "frameworkId": str,
     },
 )
 
@@ -729,14 +749,30 @@
 class GetEvidenceByEvidenceFolderRequestRequestTypeDef(
     _RequiredGetEvidenceByEvidenceFolderRequestRequestTypeDef,
     _OptionalGetEvidenceByEvidenceFolderRequestRequestTypeDef,
 ):
     pass
 
 
+GetEvidenceFileUploadUrlRequestRequestTypeDef = TypedDict(
+    "GetEvidenceFileUploadUrlRequestRequestTypeDef",
+    {
+        "fileName": str,
+    },
+)
+
+GetEvidenceFileUploadUrlResponseTypeDef = TypedDict(
+    "GetEvidenceFileUploadUrlResponseTypeDef",
+    {
+        "evidenceFileName": str,
+        "uploadUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetEvidenceFolderRequestRequestTypeDef = TypedDict(
     "GetEvidenceFolderRequestRequestTypeDef",
     {
         "assessmentId": str,
         "controlSetId": str,
         "evidenceFolderId": str,
     },
@@ -830,14 +866,23 @@
         "assessmentControlsCountByNoncompliantEvidence": int,
         "totalAssessmentControlsCount": int,
         "lastUpdated": datetime,
     },
     total=False,
 )
 
+GetOrganizationAdminAccountResponseTypeDef = TypedDict(
+    "GetOrganizationAdminAccountResponseTypeDef",
+    {
+        "adminAccountId": str,
+        "organizationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ServiceMetadataTypeDef = TypedDict(
     "ServiceMetadataTypeDef",
     {
         "name": str,
         "displayName": str,
         "description": str,
         "category": str,
@@ -1037,14 +1082,23 @@
 class ListKeywordsForDataSourceRequestRequestTypeDef(
     _RequiredListKeywordsForDataSourceRequestRequestTypeDef,
     _OptionalListKeywordsForDataSourceRequestRequestTypeDef,
 ):
     pass
 
 
+ListKeywordsForDataSourceResponseTypeDef = TypedDict(
+    "ListKeywordsForDataSourceResponseTypeDef",
+    {
+        "keywords": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListNotificationsRequestRequestTypeDef = TypedDict(
     "ListNotificationsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -1068,30 +1122,66 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterAccountRequestRequestTypeDef = TypedDict(
     "RegisterAccountRequestRequestTypeDef",
     {
         "kmsKey": str,
         "delegatedAdminAccount": str,
     },
     total=False,
 )
 
+RegisterAccountResponseTypeDef = TypedDict(
+    "RegisterAccountResponseTypeDef",
+    {
+        "status": AccountStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterOrganizationAdminAccountRequestRequestTypeDef = TypedDict(
     "RegisterOrganizationAdminAccountRequestRequestTypeDef",
     {
         "adminAccountId": str,
     },
 )
 
+RegisterOrganizationAdminAccountResponseTypeDef = TypedDict(
+    "RegisterOrganizationAdminAccountResponseTypeDef",
+    {
+        "adminAccountId": str,
+        "organizationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
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
 _RequiredStartAssessmentFrameworkShareRequestRequestTypeDef = TypedDict(
     "_RequiredStartAssessmentFrameworkShareRequestRequestTypeDef",
     {
         "frameworkId": str,
         "destinationAccount": str,
         "destinationRegion": str,
     },
@@ -1183,14 +1273,26 @@
 ValidateAssessmentReportIntegrityRequestRequestTypeDef = TypedDict(
     "ValidateAssessmentReportIntegrityRequestRequestTypeDef",
     {
         "s3RelativePath": str,
     },
 )
 
+ValidateAssessmentReportIntegrityResponseTypeDef = TypedDict(
+    "ValidateAssessmentReportIntegrityResponseTypeDef",
+    {
+        "signatureValid": bool,
+        "signatureAlgorithm": str,
+        "signatureDateTime": str,
+        "signatureKeyId": str,
+        "validationErrors": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ScopeTypeDef = TypedDict(
     "ScopeTypeDef",
     {
         "awsAccounts": Sequence[AWSAccountTypeDef],
         "awsServices": Sequence[AWSServiceTypeDef],
     },
     total=False,
@@ -1223,177 +1325,106 @@
         "evidenceSources": List[str],
         "evidenceCount": int,
         "assessmentReportEvidenceCount": int,
     },
     total=False,
 )
 
-BatchAssociateAssessmentReportEvidenceResponseTypeDef = TypedDict(
-    "BatchAssociateAssessmentReportEvidenceResponseTypeDef",
-    {
-        "evidenceIds": List[str],
-        "errors": List[AssessmentReportEvidenceErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-BatchDisassociateAssessmentReportEvidenceResponseTypeDef = TypedDict(
-    "BatchDisassociateAssessmentReportEvidenceResponseTypeDef",
-    {
-        "evidenceIds": List[str],
-        "errors": List[AssessmentReportEvidenceErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAssessmentReportResponseTypeDef = TypedDict(
-    "CreateAssessmentReportResponseTypeDef",
-    {
-        "assessmentReport": AssessmentReportTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeregisterAccountResponseTypeDef = TypedDict(
-    "DeregisterAccountResponseTypeDef",
-    {
-        "status": AccountStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccountStatusResponseTypeDef = TypedDict(
-    "GetAccountStatusResponseTypeDef",
-    {
-        "status": AccountStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetEvidenceFolderResponseTypeDef = TypedDict(
     "GetEvidenceFolderResponseTypeDef",
     {
         "evidenceFolder": AssessmentEvidenceFolderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEvidenceFoldersByAssessmentControlResponseTypeDef = TypedDict(
     "GetEvidenceFoldersByAssessmentControlResponseTypeDef",
     {
         "evidenceFolders": List[AssessmentEvidenceFolderTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEvidenceFoldersByAssessmentResponseTypeDef = TypedDict(
     "GetEvidenceFoldersByAssessmentResponseTypeDef",
     {
         "evidenceFolders": List[AssessmentEvidenceFolderTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetOrganizationAdminAccountResponseTypeDef = TypedDict(
-    "GetOrganizationAdminAccountResponseTypeDef",
-    {
-        "adminAccountId": str,
-        "organizationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAssessmentFrameworkShareRequestsResponseTypeDef = TypedDict(
-    "ListAssessmentFrameworkShareRequestsResponseTypeDef",
-    {
-        "assessmentFrameworkShareRequests": List[AssessmentFrameworkShareRequestTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssessmentFrameworksResponseTypeDef = TypedDict(
     "ListAssessmentFrameworksResponseTypeDef",
     {
         "frameworkMetadataList": List[AssessmentFrameworkMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAssessmentReportsResponseTypeDef = TypedDict(
-    "ListAssessmentReportsResponseTypeDef",
-    {
-        "assessmentReports": List[AssessmentReportMetadataTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListKeywordsForDataSourceResponseTypeDef = TypedDict(
-    "ListKeywordsForDataSourceResponseTypeDef",
+ListAssessmentFrameworkShareRequestsResponseTypeDef = TypedDict(
+    "ListAssessmentFrameworkShareRequestsResponseTypeDef",
     {
-        "keywords": List[str],
+        "assessmentFrameworkShareRequests": List[AssessmentFrameworkShareRequestTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+StartAssessmentFrameworkShareResponseTypeDef = TypedDict(
+    "StartAssessmentFrameworkShareResponseTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "assessmentFrameworkShareRequest": AssessmentFrameworkShareRequestTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RegisterAccountResponseTypeDef = TypedDict(
-    "RegisterAccountResponseTypeDef",
+UpdateAssessmentFrameworkShareResponseTypeDef = TypedDict(
+    "UpdateAssessmentFrameworkShareResponseTypeDef",
     {
-        "status": AccountStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "assessmentFrameworkShareRequest": AssessmentFrameworkShareRequestTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RegisterOrganizationAdminAccountResponseTypeDef = TypedDict(
-    "RegisterOrganizationAdminAccountResponseTypeDef",
+BatchAssociateAssessmentReportEvidenceResponseTypeDef = TypedDict(
+    "BatchAssociateAssessmentReportEvidenceResponseTypeDef",
     {
-        "adminAccountId": str,
-        "organizationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "evidenceIds": List[str],
+        "errors": List[AssessmentReportEvidenceErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartAssessmentFrameworkShareResponseTypeDef = TypedDict(
-    "StartAssessmentFrameworkShareResponseTypeDef",
+BatchDisassociateAssessmentReportEvidenceResponseTypeDef = TypedDict(
+    "BatchDisassociateAssessmentReportEvidenceResponseTypeDef",
     {
-        "assessmentFrameworkShareRequest": AssessmentFrameworkShareRequestTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "evidenceIds": List[str],
+        "errors": List[AssessmentReportEvidenceErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateAssessmentFrameworkShareResponseTypeDef = TypedDict(
-    "UpdateAssessmentFrameworkShareResponseTypeDef",
+ListAssessmentReportsResponseTypeDef = TypedDict(
+    "ListAssessmentReportsResponseTypeDef",
     {
-        "assessmentFrameworkShareRequest": AssessmentFrameworkShareRequestTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "assessmentReports": List[AssessmentReportMetadataTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ValidateAssessmentReportIntegrityResponseTypeDef = TypedDict(
-    "ValidateAssessmentReportIntegrityResponseTypeDef",
+CreateAssessmentReportResponseTypeDef = TypedDict(
+    "CreateAssessmentReportResponseTypeDef",
     {
-        "signatureValid": bool,
-        "signatureAlgorithm": str,
-        "signatureDateTime": str,
-        "signatureKeyId": str,
-        "validationErrors": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "assessmentReport": AssessmentReportTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchCreateDelegationByAssessmentErrorTypeDef = TypedDict(
     "BatchCreateDelegationByAssessmentErrorTypeDef",
     {
         "createDelegationRequest": CreateDelegationRequestTypeDef,
@@ -1411,15 +1442,15 @@
     },
 )
 
 BatchDeleteDelegationByAssessmentResponseTypeDef = TypedDict(
     "BatchDeleteDelegationByAssessmentResponseTypeDef",
     {
         "errors": List[BatchDeleteDelegationByAssessmentErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchImportEvidenceToAssessmentControlErrorTypeDef = TypedDict(
     "BatchImportEvidenceToAssessmentControlErrorTypeDef",
     {
         "manualEvidence": ManualEvidenceTypeDef,
@@ -1440,15 +1471,15 @@
 )
 
 GetChangeLogsResponseTypeDef = TypedDict(
     "GetChangeLogsResponseTypeDef",
     {
         "changeLogs": List[ChangeLogTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ControlDomainInsightsTypeDef = TypedDict(
     "ControlDomainInsightsTypeDef",
     {
         "name": str,
@@ -1514,15 +1545,15 @@
 )
 
 ListControlsResponseTypeDef = TypedDict(
     "ListControlsResponseTypeDef",
     {
         "controlMetadataList": List[ControlMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateAssessmentFrameworkControlSetTypeDef = TypedDict(
     "_RequiredCreateAssessmentFrameworkControlSetTypeDef",
     {
         "name": str,
@@ -1568,41 +1599,43 @@
 
 
 GetDelegationsResponseTypeDef = TypedDict(
     "GetDelegationsResponseTypeDef",
     {
         "delegations": List[DelegationMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSettingsRequestRequestTypeDef = TypedDict(
     "UpdateSettingsRequestRequestTypeDef",
     {
         "snsTopic": str,
         "defaultAssessmentReportsDestination": AssessmentReportsDestinationTypeDef,
         "defaultProcessOwners": Sequence[RoleTypeDef],
         "kmsKey": str,
         "evidenceFinderEnabled": bool,
         "deregistrationPolicy": DeregistrationPolicyTypeDef,
+        "defaultExportDestination": DefaultExportDestinationTypeDef,
     },
     total=False,
 )
 
 SettingsTypeDef = TypedDict(
     "SettingsTypeDef",
     {
         "isAwsOrgEnabled": bool,
         "snsTopic": str,
         "defaultAssessmentReportsDestination": AssessmentReportsDestinationTypeDef,
         "defaultProcessOwners": List[RoleTypeDef],
         "kmsKey": str,
         "evidenceFinderEnablement": EvidenceFinderEnablementTypeDef,
         "deregistrationPolicy": DeregistrationPolicyTypeDef,
+        "defaultExportDestination": DefaultExportDestinationTypeDef,
     },
     total=False,
 )
 
 EvidenceTypeDef = TypedDict(
     "EvidenceTypeDef",
     {
@@ -1625,48 +1658,48 @@
     total=False,
 )
 
 GetAssessmentReportUrlResponseTypeDef = TypedDict(
     "GetAssessmentReportUrlResponseTypeDef",
     {
         "preSignedUrl": URLTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInsightsByAssessmentResponseTypeDef = TypedDict(
     "GetInsightsByAssessmentResponseTypeDef",
     {
         "insights": InsightsByAssessmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInsightsResponseTypeDef = TypedDict(
     "GetInsightsResponseTypeDef",
     {
         "insights": InsightsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServicesInScopeResponseTypeDef = TypedDict(
     "GetServicesInScopeResponseTypeDef",
     {
         "serviceMetadata": List[ServiceMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNotificationsResponseTypeDef = TypedDict(
     "ListNotificationsResponseTypeDef",
     {
         "notifications": List[NotificationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssessmentMetadataTypeDef = TypedDict(
     "AssessmentMetadataTypeDef",
     {
         "name": str,
@@ -1736,15 +1769,15 @@
 
 
 ListAssessmentsResponseTypeDef = TypedDict(
     "ListAssessmentsResponseTypeDef",
     {
         "assessmentMetadata": List[AssessmentMetadataItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssessmentControlSetTypeDef = TypedDict(
     "AssessmentControlSetTypeDef",
     {
         "id": str,
@@ -1759,68 +1792,68 @@
     total=False,
 )
 
 UpdateAssessmentControlResponseTypeDef = TypedDict(
     "UpdateAssessmentControlResponseTypeDef",
     {
         "control": AssessmentControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchCreateDelegationByAssessmentResponseTypeDef = TypedDict(
     "BatchCreateDelegationByAssessmentResponseTypeDef",
     {
         "delegations": List[DelegationTypeDef],
         "errors": List[BatchCreateDelegationByAssessmentErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchImportEvidenceToAssessmentControlResponseTypeDef = TypedDict(
     "BatchImportEvidenceToAssessmentControlResponseTypeDef",
     {
         "errors": List[BatchImportEvidenceToAssessmentControlErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListControlDomainInsightsByAssessmentResponseTypeDef = TypedDict(
     "ListControlDomainInsightsByAssessmentResponseTypeDef",
     {
         "controlDomainInsights": List[ControlDomainInsightsTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListControlDomainInsightsResponseTypeDef = TypedDict(
     "ListControlDomainInsightsResponseTypeDef",
     {
         "controlDomainInsights": List[ControlDomainInsightsTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssessmentControlInsightsByControlDomainResponseTypeDef = TypedDict(
     "ListAssessmentControlInsightsByControlDomainResponseTypeDef",
     {
         "controlInsightsByAssessment": List[ControlInsightsMetadataByAssessmentItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListControlInsightsByControlDomainResponseTypeDef = TypedDict(
     "ListControlInsightsByControlDomainResponseTypeDef",
     {
         "controlInsightsMetadata": List[ControlInsightsMetadataItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ControlTypeDef = TypedDict(
     "ControlTypeDef",
     {
         "arn": str,
@@ -1944,40 +1977,40 @@
     pass
 
 
 GetSettingsResponseTypeDef = TypedDict(
     "GetSettingsResponseTypeDef",
     {
         "settings": SettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSettingsResponseTypeDef = TypedDict(
     "UpdateSettingsResponseTypeDef",
     {
         "settings": SettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEvidenceByEvidenceFolderResponseTypeDef = TypedDict(
     "GetEvidenceByEvidenceFolderResponseTypeDef",
     {
         "evidence": List[EvidenceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEvidenceResponseTypeDef = TypedDict(
     "GetEvidenceResponseTypeDef",
     {
         "evidence": EvidenceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssessmentFrameworkTypeDef = TypedDict(
     "AssessmentFrameworkTypeDef",
     {
         "id": str,
@@ -1988,15 +2021,15 @@
     total=False,
 )
 
 UpdateAssessmentControlSetStatusResponseTypeDef = TypedDict(
     "UpdateAssessmentControlSetStatusResponseTypeDef",
     {
         "controlSet": AssessmentControlSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ControlSetTypeDef = TypedDict(
     "ControlSetTypeDef",
     {
         "id": str,
@@ -2006,31 +2039,31 @@
     total=False,
 )
 
 CreateControlResponseTypeDef = TypedDict(
     "CreateControlResponseTypeDef",
     {
         "control": ControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetControlResponseTypeDef = TypedDict(
     "GetControlResponseTypeDef",
     {
         "control": ControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateControlResponseTypeDef = TypedDict(
     "UpdateControlResponseTypeDef",
     {
         "control": ControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssessmentTypeDef = TypedDict(
     "AssessmentTypeDef",
     {
         "arn": str,
@@ -2063,59 +2096,59 @@
     total=False,
 )
 
 CreateAssessmentResponseTypeDef = TypedDict(
     "CreateAssessmentResponseTypeDef",
     {
         "assessment": AssessmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAssessmentResponseTypeDef = TypedDict(
     "GetAssessmentResponseTypeDef",
     {
         "assessment": AssessmentTypeDef,
         "userRole": RoleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssessmentResponseTypeDef = TypedDict(
     "UpdateAssessmentResponseTypeDef",
     {
         "assessment": AssessmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssessmentStatusResponseTypeDef = TypedDict(
     "UpdateAssessmentStatusResponseTypeDef",
     {
         "assessment": AssessmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAssessmentFrameworkResponseTypeDef = TypedDict(
     "CreateAssessmentFrameworkResponseTypeDef",
     {
         "framework": FrameworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAssessmentFrameworkResponseTypeDef = TypedDict(
     "GetAssessmentFrameworkResponseTypeDef",
     {
         "framework": FrameworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssessmentFrameworkResponseTypeDef = TypedDict(
     "UpdateAssessmentFrameworkResponseTypeDef",
     {
         "framework": FrameworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager/type_defs.pyi` & `types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -25,14 +25,15 @@
     ControlStatusType,
     ControlTypeType,
     DelegationStatusType,
     DeleteResourcesType,
     EvidenceFinderBackfillStatusType,
     EvidenceFinderEnablementStatusType,
     FrameworkTypeType,
+    KeywordInputTypeType,
     ObjectTypeEnumType,
     RoleTypeType,
     SettingAttributeType,
     ShareRequestActionType,
     ShareRequestStatusType,
     ShareRequestTypeType,
     SourceFrequencyType,
@@ -61,99 +62,102 @@
     "FrameworkMetadataTypeDef",
     "AssessmentReportsDestinationTypeDef",
     "AssessmentReportEvidenceErrorTypeDef",
     "AssessmentReportMetadataTypeDef",
     "AssessmentReportTypeDef",
     "AssociateAssessmentReportEvidenceFolderRequestRequestTypeDef",
     "BatchAssociateAssessmentReportEvidenceRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateDelegationRequestTypeDef",
     "BatchDeleteDelegationByAssessmentErrorTypeDef",
     "BatchDeleteDelegationByAssessmentRequestRequestTypeDef",
     "BatchDisassociateAssessmentReportEvidenceRequestRequestTypeDef",
     "ManualEvidenceTypeDef",
     "ChangeLogTypeDef",
     "EvidenceInsightsTypeDef",
     "SourceKeywordTypeDef",
     "ControlMetadataTypeDef",
     "CreateAssessmentFrameworkControlTypeDef",
     "CreateAssessmentReportRequestRequestTypeDef",
+    "DefaultExportDestinationTypeDef",
     "DelegationMetadataTypeDef",
     "DeleteAssessmentFrameworkRequestRequestTypeDef",
     "DeleteAssessmentFrameworkShareRequestRequestTypeDef",
     "DeleteAssessmentReportRequestRequestTypeDef",
     "DeleteAssessmentRequestRequestTypeDef",
     "DeleteControlRequestRequestTypeDef",
+    "DeregisterAccountResponseTypeDef",
     "DeregisterOrganizationAdminAccountRequestRequestTypeDef",
     "DeregistrationPolicyTypeDef",
     "DisassociateAssessmentReportEvidenceFolderRequestRequestTypeDef",
     "EvidenceFinderEnablementTypeDef",
     "ResourceTypeDef",
+    "GetAccountStatusResponseTypeDef",
     "GetAssessmentFrameworkRequestRequestTypeDef",
     "GetAssessmentReportUrlRequestRequestTypeDef",
     "URLTypeDef",
     "GetAssessmentRequestRequestTypeDef",
     "GetChangeLogsRequestRequestTypeDef",
     "GetControlRequestRequestTypeDef",
     "GetDelegationsRequestRequestTypeDef",
     "GetEvidenceByEvidenceFolderRequestRequestTypeDef",
+    "GetEvidenceFileUploadUrlRequestRequestTypeDef",
+    "GetEvidenceFileUploadUrlResponseTypeDef",
     "GetEvidenceFolderRequestRequestTypeDef",
     "GetEvidenceFoldersByAssessmentControlRequestRequestTypeDef",
     "GetEvidenceFoldersByAssessmentRequestRequestTypeDef",
     "GetEvidenceRequestRequestTypeDef",
     "GetInsightsByAssessmentRequestRequestTypeDef",
     "InsightsByAssessmentTypeDef",
     "InsightsTypeDef",
+    "GetOrganizationAdminAccountResponseTypeDef",
     "ServiceMetadataTypeDef",
     "GetSettingsRequestRequestTypeDef",
     "ListAssessmentControlInsightsByControlDomainRequestRequestTypeDef",
     "ListAssessmentFrameworkShareRequestsRequestRequestTypeDef",
     "ListAssessmentFrameworksRequestRequestTypeDef",
     "ListAssessmentReportsRequestRequestTypeDef",
     "ListAssessmentsRequestRequestTypeDef",
     "ListControlDomainInsightsByAssessmentRequestRequestTypeDef",
     "ListControlDomainInsightsRequestRequestTypeDef",
     "ListControlInsightsByControlDomainRequestRequestTypeDef",
     "ListControlsRequestRequestTypeDef",
     "ListKeywordsForDataSourceRequestRequestTypeDef",
+    "ListKeywordsForDataSourceResponseTypeDef",
     "ListNotificationsRequestRequestTypeDef",
     "NotificationTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "RegisterAccountRequestRequestTypeDef",
+    "RegisterAccountResponseTypeDef",
     "RegisterOrganizationAdminAccountRequestRequestTypeDef",
+    "RegisterOrganizationAdminAccountResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "StartAssessmentFrameworkShareRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAssessmentControlRequestRequestTypeDef",
     "UpdateAssessmentControlSetStatusRequestRequestTypeDef",
     "UpdateAssessmentFrameworkShareRequestRequestTypeDef",
     "UpdateAssessmentStatusRequestRequestTypeDef",
     "ValidateAssessmentReportIntegrityRequestRequestTypeDef",
+    "ValidateAssessmentReportIntegrityResponseTypeDef",
     "ScopeTypeDef",
     "AssessmentMetadataItemTypeDef",
     "AssessmentControlTypeDef",
-    "BatchAssociateAssessmentReportEvidenceResponseTypeDef",
-    "BatchDisassociateAssessmentReportEvidenceResponseTypeDef",
-    "CreateAssessmentReportResponseTypeDef",
-    "DeregisterAccountResponseTypeDef",
-    "GetAccountStatusResponseTypeDef",
     "GetEvidenceFolderResponseTypeDef",
     "GetEvidenceFoldersByAssessmentControlResponseTypeDef",
     "GetEvidenceFoldersByAssessmentResponseTypeDef",
-    "GetOrganizationAdminAccountResponseTypeDef",
-    "ListAssessmentFrameworkShareRequestsResponseTypeDef",
     "ListAssessmentFrameworksResponseTypeDef",
-    "ListAssessmentReportsResponseTypeDef",
-    "ListKeywordsForDataSourceResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RegisterAccountResponseTypeDef",
-    "RegisterOrganizationAdminAccountResponseTypeDef",
+    "ListAssessmentFrameworkShareRequestsResponseTypeDef",
     "StartAssessmentFrameworkShareResponseTypeDef",
     "UpdateAssessmentFrameworkShareResponseTypeDef",
-    "ValidateAssessmentReportIntegrityResponseTypeDef",
+    "BatchAssociateAssessmentReportEvidenceResponseTypeDef",
+    "BatchDisassociateAssessmentReportEvidenceResponseTypeDef",
+    "ListAssessmentReportsResponseTypeDef",
+    "CreateAssessmentReportResponseTypeDef",
     "BatchCreateDelegationByAssessmentErrorTypeDef",
     "BatchCreateDelegationByAssessmentRequestRequestTypeDef",
     "BatchDeleteDelegationByAssessmentResponseTypeDef",
     "BatchImportEvidenceToAssessmentControlErrorTypeDef",
     "BatchImportEvidenceToAssessmentControlRequestRequestTypeDef",
     "GetChangeLogsResponseTypeDef",
     "ControlDomainInsightsTypeDef",
@@ -404,25 +408,14 @@
     {
         "assessmentId": str,
         "evidenceFolderId": str,
         "evidenceIds": Sequence[str],
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
-    {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
-    },
-)
-
 CreateDelegationRequestTypeDef = TypedDict(
     "CreateDelegationRequestTypeDef",
     {
         "comment": str,
         "controlSetId": str,
         "roleArn": str,
         "roleType": RoleTypeType,
@@ -457,14 +450,16 @@
     },
 )
 
 ManualEvidenceTypeDef = TypedDict(
     "ManualEvidenceTypeDef",
     {
         "s3ResourcePath": str,
+        "textResponse": str,
+        "evidenceFileName": str,
     },
     total=False,
 )
 
 ChangeLogTypeDef = TypedDict(
     "ChangeLogTypeDef",
     {
@@ -486,15 +481,15 @@
     },
     total=False,
 )
 
 SourceKeywordTypeDef = TypedDict(
     "SourceKeywordTypeDef",
     {
-        "keywordInputType": Literal["SELECT_FROM_LIST"],
+        "keywordInputType": KeywordInputTypeType,
         "keywordValue": str,
     },
     total=False,
 )
 
 ControlMetadataTypeDef = TypedDict(
     "ControlMetadataTypeDef",
@@ -534,14 +529,23 @@
 
 class CreateAssessmentReportRequestRequestTypeDef(
     _RequiredCreateAssessmentReportRequestRequestTypeDef,
     _OptionalCreateAssessmentReportRequestRequestTypeDef,
 ):
     pass
 
+DefaultExportDestinationTypeDef = TypedDict(
+    "DefaultExportDestinationTypeDef",
+    {
+        "destinationType": Literal["S3"],
+        "destination": str,
+    },
+    total=False,
+)
+
 DelegationMetadataTypeDef = TypedDict(
     "DelegationMetadataTypeDef",
     {
         "id": str,
         "assessmentName": str,
         "assessmentId": str,
         "status": DelegationStatusType,
@@ -585,14 +589,22 @@
 DeleteControlRequestRequestTypeDef = TypedDict(
     "DeleteControlRequestRequestTypeDef",
     {
         "controlId": str,
     },
 )
 
+DeregisterAccountResponseTypeDef = TypedDict(
+    "DeregisterAccountResponseTypeDef",
+    {
+        "status": AccountStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeregisterOrganizationAdminAccountRequestRequestTypeDef = TypedDict(
     "DeregisterOrganizationAdminAccountRequestRequestTypeDef",
     {
         "adminAccountId": str,
     },
     total=False,
 )
@@ -630,14 +642,22 @@
         "arn": str,
         "value": str,
         "complianceCheck": str,
     },
     total=False,
 )
 
+GetAccountStatusResponseTypeDef = TypedDict(
+    "GetAccountStatusResponseTypeDef",
+    {
+        "status": AccountStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAssessmentFrameworkRequestRequestTypeDef = TypedDict(
     "GetAssessmentFrameworkRequestRequestTypeDef",
     {
         "frameworkId": str,
     },
 )
 
@@ -722,14 +742,30 @@
 
 class GetEvidenceByEvidenceFolderRequestRequestTypeDef(
     _RequiredGetEvidenceByEvidenceFolderRequestRequestTypeDef,
     _OptionalGetEvidenceByEvidenceFolderRequestRequestTypeDef,
 ):
     pass
 
+GetEvidenceFileUploadUrlRequestRequestTypeDef = TypedDict(
+    "GetEvidenceFileUploadUrlRequestRequestTypeDef",
+    {
+        "fileName": str,
+    },
+)
+
+GetEvidenceFileUploadUrlResponseTypeDef = TypedDict(
+    "GetEvidenceFileUploadUrlResponseTypeDef",
+    {
+        "evidenceFileName": str,
+        "uploadUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetEvidenceFolderRequestRequestTypeDef = TypedDict(
     "GetEvidenceFolderRequestRequestTypeDef",
     {
         "assessmentId": str,
         "controlSetId": str,
         "evidenceFolderId": str,
     },
@@ -819,14 +855,23 @@
         "assessmentControlsCountByNoncompliantEvidence": int,
         "totalAssessmentControlsCount": int,
         "lastUpdated": datetime,
     },
     total=False,
 )
 
+GetOrganizationAdminAccountResponseTypeDef = TypedDict(
+    "GetOrganizationAdminAccountResponseTypeDef",
+    {
+        "adminAccountId": str,
+        "organizationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ServiceMetadataTypeDef = TypedDict(
     "ServiceMetadataTypeDef",
     {
         "name": str,
         "displayName": str,
         "description": str,
         "category": str,
@@ -1012,14 +1057,23 @@
 
 class ListKeywordsForDataSourceRequestRequestTypeDef(
     _RequiredListKeywordsForDataSourceRequestRequestTypeDef,
     _OptionalListKeywordsForDataSourceRequestRequestTypeDef,
 ):
     pass
 
+ListKeywordsForDataSourceResponseTypeDef = TypedDict(
+    "ListKeywordsForDataSourceResponseTypeDef",
+    {
+        "keywords": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListNotificationsRequestRequestTypeDef = TypedDict(
     "ListNotificationsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -1043,30 +1097,66 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterAccountRequestRequestTypeDef = TypedDict(
     "RegisterAccountRequestRequestTypeDef",
     {
         "kmsKey": str,
         "delegatedAdminAccount": str,
     },
     total=False,
 )
 
+RegisterAccountResponseTypeDef = TypedDict(
+    "RegisterAccountResponseTypeDef",
+    {
+        "status": AccountStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterOrganizationAdminAccountRequestRequestTypeDef = TypedDict(
     "RegisterOrganizationAdminAccountRequestRequestTypeDef",
     {
         "adminAccountId": str,
     },
 )
 
+RegisterOrganizationAdminAccountResponseTypeDef = TypedDict(
+    "RegisterOrganizationAdminAccountResponseTypeDef",
+    {
+        "adminAccountId": str,
+        "organizationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
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
 _RequiredStartAssessmentFrameworkShareRequestRequestTypeDef = TypedDict(
     "_RequiredStartAssessmentFrameworkShareRequestRequestTypeDef",
     {
         "frameworkId": str,
         "destinationAccount": str,
         "destinationRegion": str,
     },
@@ -1154,14 +1244,26 @@
 ValidateAssessmentReportIntegrityRequestRequestTypeDef = TypedDict(
     "ValidateAssessmentReportIntegrityRequestRequestTypeDef",
     {
         "s3RelativePath": str,
     },
 )
 
+ValidateAssessmentReportIntegrityResponseTypeDef = TypedDict(
+    "ValidateAssessmentReportIntegrityResponseTypeDef",
+    {
+        "signatureValid": bool,
+        "signatureAlgorithm": str,
+        "signatureDateTime": str,
+        "signatureKeyId": str,
+        "validationErrors": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ScopeTypeDef = TypedDict(
     "ScopeTypeDef",
     {
         "awsAccounts": Sequence[AWSAccountTypeDef],
         "awsServices": Sequence[AWSServiceTypeDef],
     },
     total=False,
@@ -1194,177 +1296,106 @@
         "evidenceSources": List[str],
         "evidenceCount": int,
         "assessmentReportEvidenceCount": int,
     },
     total=False,
 )
 
-BatchAssociateAssessmentReportEvidenceResponseTypeDef = TypedDict(
-    "BatchAssociateAssessmentReportEvidenceResponseTypeDef",
-    {
-        "evidenceIds": List[str],
-        "errors": List[AssessmentReportEvidenceErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-BatchDisassociateAssessmentReportEvidenceResponseTypeDef = TypedDict(
-    "BatchDisassociateAssessmentReportEvidenceResponseTypeDef",
-    {
-        "evidenceIds": List[str],
-        "errors": List[AssessmentReportEvidenceErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAssessmentReportResponseTypeDef = TypedDict(
-    "CreateAssessmentReportResponseTypeDef",
-    {
-        "assessmentReport": AssessmentReportTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeregisterAccountResponseTypeDef = TypedDict(
-    "DeregisterAccountResponseTypeDef",
-    {
-        "status": AccountStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccountStatusResponseTypeDef = TypedDict(
-    "GetAccountStatusResponseTypeDef",
-    {
-        "status": AccountStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetEvidenceFolderResponseTypeDef = TypedDict(
     "GetEvidenceFolderResponseTypeDef",
     {
         "evidenceFolder": AssessmentEvidenceFolderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEvidenceFoldersByAssessmentControlResponseTypeDef = TypedDict(
     "GetEvidenceFoldersByAssessmentControlResponseTypeDef",
     {
         "evidenceFolders": List[AssessmentEvidenceFolderTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEvidenceFoldersByAssessmentResponseTypeDef = TypedDict(
     "GetEvidenceFoldersByAssessmentResponseTypeDef",
     {
         "evidenceFolders": List[AssessmentEvidenceFolderTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetOrganizationAdminAccountResponseTypeDef = TypedDict(
-    "GetOrganizationAdminAccountResponseTypeDef",
-    {
-        "adminAccountId": str,
-        "organizationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAssessmentFrameworkShareRequestsResponseTypeDef = TypedDict(
-    "ListAssessmentFrameworkShareRequestsResponseTypeDef",
-    {
-        "assessmentFrameworkShareRequests": List[AssessmentFrameworkShareRequestTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssessmentFrameworksResponseTypeDef = TypedDict(
     "ListAssessmentFrameworksResponseTypeDef",
     {
         "frameworkMetadataList": List[AssessmentFrameworkMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAssessmentReportsResponseTypeDef = TypedDict(
-    "ListAssessmentReportsResponseTypeDef",
-    {
-        "assessmentReports": List[AssessmentReportMetadataTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListKeywordsForDataSourceResponseTypeDef = TypedDict(
-    "ListKeywordsForDataSourceResponseTypeDef",
+ListAssessmentFrameworkShareRequestsResponseTypeDef = TypedDict(
+    "ListAssessmentFrameworkShareRequestsResponseTypeDef",
     {
-        "keywords": List[str],
+        "assessmentFrameworkShareRequests": List[AssessmentFrameworkShareRequestTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+StartAssessmentFrameworkShareResponseTypeDef = TypedDict(
+    "StartAssessmentFrameworkShareResponseTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "assessmentFrameworkShareRequest": AssessmentFrameworkShareRequestTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RegisterAccountResponseTypeDef = TypedDict(
-    "RegisterAccountResponseTypeDef",
+UpdateAssessmentFrameworkShareResponseTypeDef = TypedDict(
+    "UpdateAssessmentFrameworkShareResponseTypeDef",
     {
-        "status": AccountStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "assessmentFrameworkShareRequest": AssessmentFrameworkShareRequestTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RegisterOrganizationAdminAccountResponseTypeDef = TypedDict(
-    "RegisterOrganizationAdminAccountResponseTypeDef",
+BatchAssociateAssessmentReportEvidenceResponseTypeDef = TypedDict(
+    "BatchAssociateAssessmentReportEvidenceResponseTypeDef",
     {
-        "adminAccountId": str,
-        "organizationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "evidenceIds": List[str],
+        "errors": List[AssessmentReportEvidenceErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartAssessmentFrameworkShareResponseTypeDef = TypedDict(
-    "StartAssessmentFrameworkShareResponseTypeDef",
+BatchDisassociateAssessmentReportEvidenceResponseTypeDef = TypedDict(
+    "BatchDisassociateAssessmentReportEvidenceResponseTypeDef",
     {
-        "assessmentFrameworkShareRequest": AssessmentFrameworkShareRequestTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "evidenceIds": List[str],
+        "errors": List[AssessmentReportEvidenceErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateAssessmentFrameworkShareResponseTypeDef = TypedDict(
-    "UpdateAssessmentFrameworkShareResponseTypeDef",
+ListAssessmentReportsResponseTypeDef = TypedDict(
+    "ListAssessmentReportsResponseTypeDef",
     {
-        "assessmentFrameworkShareRequest": AssessmentFrameworkShareRequestTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "assessmentReports": List[AssessmentReportMetadataTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ValidateAssessmentReportIntegrityResponseTypeDef = TypedDict(
-    "ValidateAssessmentReportIntegrityResponseTypeDef",
+CreateAssessmentReportResponseTypeDef = TypedDict(
+    "CreateAssessmentReportResponseTypeDef",
     {
-        "signatureValid": bool,
-        "signatureAlgorithm": str,
-        "signatureDateTime": str,
-        "signatureKeyId": str,
-        "validationErrors": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "assessmentReport": AssessmentReportTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchCreateDelegationByAssessmentErrorTypeDef = TypedDict(
     "BatchCreateDelegationByAssessmentErrorTypeDef",
     {
         "createDelegationRequest": CreateDelegationRequestTypeDef,
@@ -1382,15 +1413,15 @@
     },
 )
 
 BatchDeleteDelegationByAssessmentResponseTypeDef = TypedDict(
     "BatchDeleteDelegationByAssessmentResponseTypeDef",
     {
         "errors": List[BatchDeleteDelegationByAssessmentErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchImportEvidenceToAssessmentControlErrorTypeDef = TypedDict(
     "BatchImportEvidenceToAssessmentControlErrorTypeDef",
     {
         "manualEvidence": ManualEvidenceTypeDef,
@@ -1411,15 +1442,15 @@
 )
 
 GetChangeLogsResponseTypeDef = TypedDict(
     "GetChangeLogsResponseTypeDef",
     {
         "changeLogs": List[ChangeLogTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ControlDomainInsightsTypeDef = TypedDict(
     "ControlDomainInsightsTypeDef",
     {
         "name": str,
@@ -1485,15 +1516,15 @@
 )
 
 ListControlsResponseTypeDef = TypedDict(
     "ListControlsResponseTypeDef",
     {
         "controlMetadataList": List[ControlMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateAssessmentFrameworkControlSetTypeDef = TypedDict(
     "_RequiredCreateAssessmentFrameworkControlSetTypeDef",
     {
         "name": str,
@@ -1535,41 +1566,43 @@
     pass
 
 GetDelegationsResponseTypeDef = TypedDict(
     "GetDelegationsResponseTypeDef",
     {
         "delegations": List[DelegationMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSettingsRequestRequestTypeDef = TypedDict(
     "UpdateSettingsRequestRequestTypeDef",
     {
         "snsTopic": str,
         "defaultAssessmentReportsDestination": AssessmentReportsDestinationTypeDef,
         "defaultProcessOwners": Sequence[RoleTypeDef],
         "kmsKey": str,
         "evidenceFinderEnabled": bool,
         "deregistrationPolicy": DeregistrationPolicyTypeDef,
+        "defaultExportDestination": DefaultExportDestinationTypeDef,
     },
     total=False,
 )
 
 SettingsTypeDef = TypedDict(
     "SettingsTypeDef",
     {
         "isAwsOrgEnabled": bool,
         "snsTopic": str,
         "defaultAssessmentReportsDestination": AssessmentReportsDestinationTypeDef,
         "defaultProcessOwners": List[RoleTypeDef],
         "kmsKey": str,
         "evidenceFinderEnablement": EvidenceFinderEnablementTypeDef,
         "deregistrationPolicy": DeregistrationPolicyTypeDef,
+        "defaultExportDestination": DefaultExportDestinationTypeDef,
     },
     total=False,
 )
 
 EvidenceTypeDef = TypedDict(
     "EvidenceTypeDef",
     {
@@ -1592,48 +1625,48 @@
     total=False,
 )
 
 GetAssessmentReportUrlResponseTypeDef = TypedDict(
     "GetAssessmentReportUrlResponseTypeDef",
     {
         "preSignedUrl": URLTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInsightsByAssessmentResponseTypeDef = TypedDict(
     "GetInsightsByAssessmentResponseTypeDef",
     {
         "insights": InsightsByAssessmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInsightsResponseTypeDef = TypedDict(
     "GetInsightsResponseTypeDef",
     {
         "insights": InsightsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServicesInScopeResponseTypeDef = TypedDict(
     "GetServicesInScopeResponseTypeDef",
     {
         "serviceMetadata": List[ServiceMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNotificationsResponseTypeDef = TypedDict(
     "ListNotificationsResponseTypeDef",
     {
         "notifications": List[NotificationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssessmentMetadataTypeDef = TypedDict(
     "AssessmentMetadataTypeDef",
     {
         "name": str,
@@ -1699,15 +1732,15 @@
     pass
 
 ListAssessmentsResponseTypeDef = TypedDict(
     "ListAssessmentsResponseTypeDef",
     {
         "assessmentMetadata": List[AssessmentMetadataItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssessmentControlSetTypeDef = TypedDict(
     "AssessmentControlSetTypeDef",
     {
         "id": str,
@@ -1722,68 +1755,68 @@
     total=False,
 )
 
 UpdateAssessmentControlResponseTypeDef = TypedDict(
     "UpdateAssessmentControlResponseTypeDef",
     {
         "control": AssessmentControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchCreateDelegationByAssessmentResponseTypeDef = TypedDict(
     "BatchCreateDelegationByAssessmentResponseTypeDef",
     {
         "delegations": List[DelegationTypeDef],
         "errors": List[BatchCreateDelegationByAssessmentErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchImportEvidenceToAssessmentControlResponseTypeDef = TypedDict(
     "BatchImportEvidenceToAssessmentControlResponseTypeDef",
     {
         "errors": List[BatchImportEvidenceToAssessmentControlErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListControlDomainInsightsByAssessmentResponseTypeDef = TypedDict(
     "ListControlDomainInsightsByAssessmentResponseTypeDef",
     {
         "controlDomainInsights": List[ControlDomainInsightsTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListControlDomainInsightsResponseTypeDef = TypedDict(
     "ListControlDomainInsightsResponseTypeDef",
     {
         "controlDomainInsights": List[ControlDomainInsightsTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssessmentControlInsightsByControlDomainResponseTypeDef = TypedDict(
     "ListAssessmentControlInsightsByControlDomainResponseTypeDef",
     {
         "controlInsightsByAssessment": List[ControlInsightsMetadataByAssessmentItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListControlInsightsByControlDomainResponseTypeDef = TypedDict(
     "ListControlInsightsByControlDomainResponseTypeDef",
     {
         "controlInsightsMetadata": List[ControlInsightsMetadataItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ControlTypeDef = TypedDict(
     "ControlTypeDef",
     {
         "arn": str,
@@ -1899,40 +1932,40 @@
 ):
     pass
 
 GetSettingsResponseTypeDef = TypedDict(
     "GetSettingsResponseTypeDef",
     {
         "settings": SettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSettingsResponseTypeDef = TypedDict(
     "UpdateSettingsResponseTypeDef",
     {
         "settings": SettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEvidenceByEvidenceFolderResponseTypeDef = TypedDict(
     "GetEvidenceByEvidenceFolderResponseTypeDef",
     {
         "evidence": List[EvidenceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEvidenceResponseTypeDef = TypedDict(
     "GetEvidenceResponseTypeDef",
     {
         "evidence": EvidenceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssessmentFrameworkTypeDef = TypedDict(
     "AssessmentFrameworkTypeDef",
     {
         "id": str,
@@ -1943,15 +1976,15 @@
     total=False,
 )
 
 UpdateAssessmentControlSetStatusResponseTypeDef = TypedDict(
     "UpdateAssessmentControlSetStatusResponseTypeDef",
     {
         "controlSet": AssessmentControlSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ControlSetTypeDef = TypedDict(
     "ControlSetTypeDef",
     {
         "id": str,
@@ -1961,31 +1994,31 @@
     total=False,
 )
 
 CreateControlResponseTypeDef = TypedDict(
     "CreateControlResponseTypeDef",
     {
         "control": ControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetControlResponseTypeDef = TypedDict(
     "GetControlResponseTypeDef",
     {
         "control": ControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateControlResponseTypeDef = TypedDict(
     "UpdateControlResponseTypeDef",
     {
         "control": ControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssessmentTypeDef = TypedDict(
     "AssessmentTypeDef",
     {
         "arn": str,
@@ -2018,59 +2051,59 @@
     total=False,
 )
 
 CreateAssessmentResponseTypeDef = TypedDict(
     "CreateAssessmentResponseTypeDef",
     {
         "assessment": AssessmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAssessmentResponseTypeDef = TypedDict(
     "GetAssessmentResponseTypeDef",
     {
         "assessment": AssessmentTypeDef,
         "userRole": RoleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssessmentResponseTypeDef = TypedDict(
     "UpdateAssessmentResponseTypeDef",
     {
         "assessment": AssessmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssessmentStatusResponseTypeDef = TypedDict(
     "UpdateAssessmentStatusResponseTypeDef",
     {
         "assessment": AssessmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAssessmentFrameworkResponseTypeDef = TypedDict(
     "CreateAssessmentFrameworkResponseTypeDef",
     {
         "framework": FrameworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAssessmentFrameworkResponseTypeDef = TypedDict(
     "GetAssessmentFrameworkResponseTypeDef",
     {
         "framework": FrameworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssessmentFrameworkResponseTypeDef = TypedDict(
     "UpdateAssessmentFrameworkResponseTypeDef",
     {
         "framework": FrameworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager.egg-info/PKG-INFO` & `types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-auditmanager
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AuditManager 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AuditManager 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-auditmanager"></a>
 
 # types-aiobotocore-auditmanager
 
 [![PyPI - types-aiobotocore-auditmanager](https://img.shields.io/pypi/v/types-aiobotocore-auditmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-auditmanager)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-auditmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-auditmanager)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-auditmanager?color=blue)](https://pypistats.org/packages/types-aiobotocore-auditmanager)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AuditManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager)
+[aiobotocore.AuditManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/auditmanager.html#AuditManager)
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
 [types-aiobotocore-auditmanager docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_auditmanager/).
 
 See how it helps to find and fix potential bugs:
 
@@ -282,14 +282,15 @@
     ControlSetStatusType,
     ControlStatusType,
     ControlTypeType,
     DelegationStatusType,
     DeleteResourcesType,
     EvidenceFinderBackfillStatusType,
     EvidenceFinderEnablementStatusType,
+    ExportDestinationTypeType,
     FrameworkTypeType,
     KeywordInputTypeType,
     ObjectTypeEnumType,
     RoleTypeType,
     SettingAttributeType,
     ShareRequestActionType,
     ShareRequestStatusType,
@@ -328,99 +329,102 @@
     FrameworkMetadataTypeDef,
     AssessmentReportsDestinationTypeDef,
     AssessmentReportEvidenceErrorTypeDef,
     AssessmentReportMetadataTypeDef,
     AssessmentReportTypeDef,
     AssociateAssessmentReportEvidenceFolderRequestRequestTypeDef,
     BatchAssociateAssessmentReportEvidenceRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateDelegationRequestTypeDef,
     BatchDeleteDelegationByAssessmentErrorTypeDef,
     BatchDeleteDelegationByAssessmentRequestRequestTypeDef,
     BatchDisassociateAssessmentReportEvidenceRequestRequestTypeDef,
     ManualEvidenceTypeDef,
     ChangeLogTypeDef,
     EvidenceInsightsTypeDef,
     SourceKeywordTypeDef,
     ControlMetadataTypeDef,
     CreateAssessmentFrameworkControlTypeDef,
     CreateAssessmentReportRequestRequestTypeDef,
+    DefaultExportDestinationTypeDef,
     DelegationMetadataTypeDef,
     DeleteAssessmentFrameworkRequestRequestTypeDef,
     DeleteAssessmentFrameworkShareRequestRequestTypeDef,
     DeleteAssessmentReportRequestRequestTypeDef,
     DeleteAssessmentRequestRequestTypeDef,
     DeleteControlRequestRequestTypeDef,
+    DeregisterAccountResponseTypeDef,
     DeregisterOrganizationAdminAccountRequestRequestTypeDef,
     DeregistrationPolicyTypeDef,
     DisassociateAssessmentReportEvidenceFolderRequestRequestTypeDef,
     EvidenceFinderEnablementTypeDef,
     ResourceTypeDef,
+    GetAccountStatusResponseTypeDef,
     GetAssessmentFrameworkRequestRequestTypeDef,
     GetAssessmentReportUrlRequestRequestTypeDef,
     URLTypeDef,
     GetAssessmentRequestRequestTypeDef,
     GetChangeLogsRequestRequestTypeDef,
     GetControlRequestRequestTypeDef,
     GetDelegationsRequestRequestTypeDef,
     GetEvidenceByEvidenceFolderRequestRequestTypeDef,
+    GetEvidenceFileUploadUrlRequestRequestTypeDef,
+    GetEvidenceFileUploadUrlResponseTypeDef,
     GetEvidenceFolderRequestRequestTypeDef,
     GetEvidenceFoldersByAssessmentControlRequestRequestTypeDef,
     GetEvidenceFoldersByAssessmentRequestRequestTypeDef,
     GetEvidenceRequestRequestTypeDef,
     GetInsightsByAssessmentRequestRequestTypeDef,
     InsightsByAssessmentTypeDef,
     InsightsTypeDef,
+    GetOrganizationAdminAccountResponseTypeDef,
     ServiceMetadataTypeDef,
     GetSettingsRequestRequestTypeDef,
     ListAssessmentControlInsightsByControlDomainRequestRequestTypeDef,
     ListAssessmentFrameworkShareRequestsRequestRequestTypeDef,
     ListAssessmentFrameworksRequestRequestTypeDef,
     ListAssessmentReportsRequestRequestTypeDef,
     ListAssessmentsRequestRequestTypeDef,
     ListControlDomainInsightsByAssessmentRequestRequestTypeDef,
     ListControlDomainInsightsRequestRequestTypeDef,
     ListControlInsightsByControlDomainRequestRequestTypeDef,
     ListControlsRequestRequestTypeDef,
     ListKeywordsForDataSourceRequestRequestTypeDef,
+    ListKeywordsForDataSourceResponseTypeDef,
     ListNotificationsRequestRequestTypeDef,
     NotificationTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     RegisterAccountRequestRequestTypeDef,
+    RegisterAccountResponseTypeDef,
     RegisterOrganizationAdminAccountRequestRequestTypeDef,
+    RegisterOrganizationAdminAccountResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartAssessmentFrameworkShareRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAssessmentControlRequestRequestTypeDef,
     UpdateAssessmentControlSetStatusRequestRequestTypeDef,
     UpdateAssessmentFrameworkShareRequestRequestTypeDef,
     UpdateAssessmentStatusRequestRequestTypeDef,
     ValidateAssessmentReportIntegrityRequestRequestTypeDef,
+    ValidateAssessmentReportIntegrityResponseTypeDef,
     ScopeTypeDef,
     AssessmentMetadataItemTypeDef,
     AssessmentControlTypeDef,
-    BatchAssociateAssessmentReportEvidenceResponseTypeDef,
-    BatchDisassociateAssessmentReportEvidenceResponseTypeDef,
-    CreateAssessmentReportResponseTypeDef,
-    DeregisterAccountResponseTypeDef,
-    GetAccountStatusResponseTypeDef,
     GetEvidenceFolderResponseTypeDef,
     GetEvidenceFoldersByAssessmentControlResponseTypeDef,
     GetEvidenceFoldersByAssessmentResponseTypeDef,
-    GetOrganizationAdminAccountResponseTypeDef,
-    ListAssessmentFrameworkShareRequestsResponseTypeDef,
     ListAssessmentFrameworksResponseTypeDef,
-    ListAssessmentReportsResponseTypeDef,
-    ListKeywordsForDataSourceResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RegisterAccountResponseTypeDef,
-    RegisterOrganizationAdminAccountResponseTypeDef,
+    ListAssessmentFrameworkShareRequestsResponseTypeDef,
     StartAssessmentFrameworkShareResponseTypeDef,
     UpdateAssessmentFrameworkShareResponseTypeDef,
-    ValidateAssessmentReportIntegrityResponseTypeDef,
+    BatchAssociateAssessmentReportEvidenceResponseTypeDef,
+    BatchDisassociateAssessmentReportEvidenceResponseTypeDef,
+    ListAssessmentReportsResponseTypeDef,
+    CreateAssessmentReportResponseTypeDef,
     BatchCreateDelegationByAssessmentErrorTypeDef,
     BatchCreateDelegationByAssessmentRequestRequestTypeDef,
     BatchDeleteDelegationByAssessmentResponseTypeDef,
     BatchImportEvidenceToAssessmentControlErrorTypeDef,
     BatchImportEvidenceToAssessmentControlRequestRequestTypeDef,
     GetChangeLogsResponseTypeDef,
     ControlDomainInsightsTypeDef,
@@ -486,43 +490,43 @@
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

### Comparing `types-aiobotocore-auditmanager-2.5.0.post1/types_aiobotocore_auditmanager.egg-info/SOURCES.txt` & `types-aiobotocore-auditmanager-2.5.1/types_aiobotocore_auditmanager.egg-info/SOURCES.txt`

 * *Files identical despite different names*


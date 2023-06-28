# Comparing `tmp/types-aiobotocore-appflow-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-appflow-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-appflow-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:10 2023, max compression
+gzip compressed data, was "types-aiobotocore-appflow-2.5.1.tar", last modified: Wed Jun 28 01:43:04 2023, max compression
```

## Comparing `types-aiobotocore-appflow-2.5.0.post1.tar` & `types-aiobotocore-appflow-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.334924 types-aiobotocore-appflow-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:32.000000 types-aiobotocore-appflow-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19740 2023-03-11 12:26:10.334924 types-aiobotocore-appflow-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    18169 2023-03-11 12:09:32.000000 types-aiobotocore-appflow-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:10.334924 types-aiobotocore-appflow-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-03-11 12:09:32.000000 types-aiobotocore-appflow-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.326924 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/
--rw-r--r--   0 runner    (1001) docker     (123)      442 2023-03-11 12:09:32.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      441 2023-03-11 12:09:32.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      943 2023-03-11 12:09:32.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19593 2023-03-11 12:09:32.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    19561 2023-03-11 12:09:32.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    17920 2023-03-11 12:09:32.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    17918 2023-03-11 12:09:32.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:32.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    68343 2023-03-11 12:09:33.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    68247 2023-03-11 12:09:33.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:32.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.334924 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19740 2023-03-11 12:26:10.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      734 2023-03-11 12:26:10.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:10.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:10.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:10.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:26:10.000000 types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.262090 types-aiobotocore-appflow-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:08.000000 types-aiobotocore-appflow-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19966 2023-06-28 01:43:04.262090 types-aiobotocore-appflow-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    18401 2023-06-28 01:26:08.000000 types-aiobotocore-appflow-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:04.262090 types-aiobotocore-appflow-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2118 2023-06-28 01:26:08.000000 types-aiobotocore-appflow-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.262090 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/
+-rw-r--r--   0 runner    (1001) docker     (123)      442 2023-06-28 01:26:08.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      441 2023-06-28 01:26:08.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      931 2023-06-28 01:26:08.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21145 2023-06-28 01:26:09.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21111 2023-06-28 01:26:09.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    18362 2023-06-28 01:26:09.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18360 2023-06-28 01:26:09.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:08.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    71147 2023-06-28 01:26:10.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    71045 2023-06-28 01:26:10.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:08.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.262090 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19966 2023-06-28 01:43:04.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      734 2023-06-28 01:43:04.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:04.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:04.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:04.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:43:04.000000 types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-appflow-2.5.0.post1/LICENSE` & `types-aiobotocore-appflow-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-appflow-2.5.0.post1/PKG-INFO` & `types-aiobotocore-appflow-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-appflow
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Appflow 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Appflow 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-appflow"></a>
 
 # types-aiobotocore-appflow
 
 [![PyPI - types-aiobotocore-appflow](https://img.shields.io/pypi/v/types-aiobotocore-appflow.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appflow)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appflow.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appflow)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appflow?color=blue)](https://pypistats.org/packages/types-aiobotocore-appflow)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Appflow 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow)
+[aiobotocore.Appflow 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow)
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
 [types-aiobotocore-appflow docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/).
 
 See how it helps to find and fix potential bugs:
 
@@ -276,14 +276,15 @@
     AmplitudeConnectorOperatorType,
     AuthenticationTypeType,
     CatalogTypeType,
     ConnectionModeType,
     ConnectorProvisioningTypeType,
     ConnectorTypeType,
     DataPullModeType,
+    DataTransferApiTypeType,
     DatadogConnectorOperatorType,
     DynatraceConnectorOperatorType,
     ExecutionStatusType,
     FileTypeType,
     FlowStatusType,
     GoogleAnalyticsConnectorOperatorType,
     InforNexusConnectorOperatorType,
@@ -304,14 +305,15 @@
     SAPODataConnectorOperatorType,
     SalesforceConnectorOperatorType,
     SalesforceDataTransferApiType,
     ScheduleFrequencyTypeType,
     ServiceNowConnectorOperatorType,
     SingularConnectorOperatorType,
     SlackConnectorOperatorType,
+    SupportedDataTransferTypeType,
     TaskTypeType,
     TrendmicroConnectorOperatorType,
     TriggerTypeType,
     VeevaConnectorOperatorType,
     WriteOperationTypeType,
     ZendeskConnectorOperatorType,
     AppflowServiceName,
@@ -336,15 +338,18 @@
 from types_aiobotocore_appflow.type_defs import (
     AggregationConfigTypeDef,
     AmplitudeConnectorProfileCredentialsTypeDef,
     AmplitudeSourcePropertiesTypeDef,
     ApiKeyCredentialsTypeDef,
     AuthParameterTypeDef,
     BasicAuthCredentialsTypeDef,
+    CancelFlowExecutionsRequestRequestTypeDef,
+    CancelFlowExecutionsResponseTypeDef,
     ConnectorRuntimeSettingTypeDef,
+    DataTransferApiTypeDef,
     ConnectorDetailTypeDef,
     DestinationFieldPropertiesTypeDef,
     SourceFieldPropertiesTypeDef,
     ConnectorEntityTypeDef,
     GoogleAnalyticsMetadataTypeDef,
     HoneycodeMetadataTypeDef,
     SalesforceMetadataTypeDef,
@@ -372,19 +377,19 @@
     ServiceNowConnectorProfilePropertiesTypeDef,
     SlackConnectorProfilePropertiesTypeDef,
     SnowflakeConnectorProfilePropertiesTypeDef,
     VeevaConnectorProfilePropertiesTypeDef,
     ZendeskConnectorProfilePropertiesTypeDef,
     PrivateConnectionProvisioningStateTypeDef,
     LambdaConnectorProvisioningConfigTypeDef,
-    ResponseMetadataTypeDef,
+    CreateConnectorProfileResponseTypeDef,
+    CreateFlowResponseTypeDef,
     CustomAuthCredentialsTypeDef,
     ErrorHandlingConfigTypeDef,
     OAuth2PropertiesTypeDef,
-    CustomConnectorSourcePropertiesTypeDef,
     CustomerProfilesDestinationPropertiesTypeDef,
     DatadogSourcePropertiesTypeDef,
     DeleteConnectorProfileRequestRequestTypeDef,
     DeleteFlowRequestRequestTypeDef,
     DescribeConnectorEntityRequestRequestTypeDef,
     DescribeConnectorProfilesRequestRequestTypeDef,
     DescribeConnectorRequestRequestTypeDef,
@@ -399,60 +404,61 @@
     GoogleAnalyticsSourcePropertiesTypeDef,
     IncrementalPullConfigTypeDef,
     InforNexusSourcePropertiesTypeDef,
     ListConnectorEntitiesRequestRequestTypeDef,
     ListConnectorsRequestRequestTypeDef,
     ListFlowsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     MarketoSourcePropertiesTypeDef,
     RegistrationOutputTypeDef,
     OAuth2CustomParameterTypeDef,
     OAuthPropertiesTypeDef,
     PardotSourcePropertiesTypeDef,
     PrefixConfigTypeDef,
+    RegisterConnectorResponseTypeDef,
+    ResetConnectorMetadataCacheRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     S3InputFormatConfigTypeDef,
     SuccessResponseHandlingConfigTypeDef,
     SAPODataSourcePropertiesTypeDef,
     SalesforceSourcePropertiesTypeDef,
     ScheduledTriggerPropertiesTypeDef,
     ServiceNowSourcePropertiesTypeDef,
     SingularSourcePropertiesTypeDef,
     SlackSourcePropertiesTypeDef,
     TrendmicroSourcePropertiesTypeDef,
     VeevaSourcePropertiesTypeDef,
     ZendeskSourcePropertiesTypeDef,
     StartFlowRequestRequestTypeDef,
+    StartFlowResponseTypeDef,
     StopFlowRequestRequestTypeDef,
+    StopFlowResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UnregisterConnectorRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateConnectorProfileResponseTypeDef,
+    UpdateConnectorRegistrationResponseTypeDef,
+    UpdateFlowResponseTypeDef,
     CustomAuthConfigTypeDef,
+    CustomConnectorSourcePropertiesTypeDef,
+    ListConnectorsResponseTypeDef,
+    ListConnectorEntitiesResponseTypeDef,
     ConnectorMetadataTypeDef,
     GoogleAnalyticsConnectorProfileCredentialsTypeDef,
     HoneycodeConnectorProfileCredentialsTypeDef,
     MarketoConnectorProfileCredentialsTypeDef,
     OAuth2CredentialsTypeDef,
     OAuthCredentialsTypeDef,
     PardotConnectorProfileCredentialsTypeDef,
     SalesforceConnectorProfileCredentialsTypeDef,
     SlackConnectorProfileCredentialsTypeDef,
     ZendeskConnectorProfileCredentialsTypeDef,
     TaskTypeDef,
     ConnectorProvisioningConfigTypeDef,
-    CreateConnectorProfileResponseTypeDef,
-    CreateFlowResponseTypeDef,
-    ListConnectorEntitiesResponseTypeDef,
-    ListConnectorsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RegisterConnectorResponseTypeDef,
-    StartFlowResponseTypeDef,
-    StopFlowResponseTypeDef,
-    UpdateConnectorProfileResponseTypeDef,
-    UpdateConnectorRegistrationResponseTypeDef,
-    UpdateFlowResponseTypeDef,
     CustomConnectorDestinationPropertiesTypeDef,
     EventBridgeDestinationPropertiesTypeDef,
     HoneycodeDestinationPropertiesTypeDef,
     MarketoDestinationPropertiesTypeDef,
     RedshiftDestinationPropertiesTypeDef,
     SalesforceDestinationPropertiesTypeDef,
     SnowflakeDestinationPropertiesTypeDef,
@@ -511,43 +517,43 @@
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

### Comparing `types-aiobotocore-appflow-2.5.0.post1/README.md` & `types-aiobotocore-appflow-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-appflow"></a>
 
 # types-aiobotocore-appflow
 
 [![PyPI - types-aiobotocore-appflow](https://img.shields.io/pypi/v/types-aiobotocore-appflow.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appflow)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appflow.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appflow)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appflow?color=blue)](https://pypistats.org/packages/types-aiobotocore-appflow)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Appflow 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow)
+[aiobotocore.Appflow 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow)
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
 [types-aiobotocore-appflow docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/).
 
 See how it helps to find and fix potential bugs:
 
@@ -243,14 +243,15 @@
     AmplitudeConnectorOperatorType,
     AuthenticationTypeType,
     CatalogTypeType,
     ConnectionModeType,
     ConnectorProvisioningTypeType,
     ConnectorTypeType,
     DataPullModeType,
+    DataTransferApiTypeType,
     DatadogConnectorOperatorType,
     DynatraceConnectorOperatorType,
     ExecutionStatusType,
     FileTypeType,
     FlowStatusType,
     GoogleAnalyticsConnectorOperatorType,
     InforNexusConnectorOperatorType,
@@ -271,14 +272,15 @@
     SAPODataConnectorOperatorType,
     SalesforceConnectorOperatorType,
     SalesforceDataTransferApiType,
     ScheduleFrequencyTypeType,
     ServiceNowConnectorOperatorType,
     SingularConnectorOperatorType,
     SlackConnectorOperatorType,
+    SupportedDataTransferTypeType,
     TaskTypeType,
     TrendmicroConnectorOperatorType,
     TriggerTypeType,
     VeevaConnectorOperatorType,
     WriteOperationTypeType,
     ZendeskConnectorOperatorType,
     AppflowServiceName,
@@ -303,15 +305,18 @@
 from types_aiobotocore_appflow.type_defs import (
     AggregationConfigTypeDef,
     AmplitudeConnectorProfileCredentialsTypeDef,
     AmplitudeSourcePropertiesTypeDef,
     ApiKeyCredentialsTypeDef,
     AuthParameterTypeDef,
     BasicAuthCredentialsTypeDef,
+    CancelFlowExecutionsRequestRequestTypeDef,
+    CancelFlowExecutionsResponseTypeDef,
     ConnectorRuntimeSettingTypeDef,
+    DataTransferApiTypeDef,
     ConnectorDetailTypeDef,
     DestinationFieldPropertiesTypeDef,
     SourceFieldPropertiesTypeDef,
     ConnectorEntityTypeDef,
     GoogleAnalyticsMetadataTypeDef,
     HoneycodeMetadataTypeDef,
     SalesforceMetadataTypeDef,
@@ -339,19 +344,19 @@
     ServiceNowConnectorProfilePropertiesTypeDef,
     SlackConnectorProfilePropertiesTypeDef,
     SnowflakeConnectorProfilePropertiesTypeDef,
     VeevaConnectorProfilePropertiesTypeDef,
     ZendeskConnectorProfilePropertiesTypeDef,
     PrivateConnectionProvisioningStateTypeDef,
     LambdaConnectorProvisioningConfigTypeDef,
-    ResponseMetadataTypeDef,
+    CreateConnectorProfileResponseTypeDef,
+    CreateFlowResponseTypeDef,
     CustomAuthCredentialsTypeDef,
     ErrorHandlingConfigTypeDef,
     OAuth2PropertiesTypeDef,
-    CustomConnectorSourcePropertiesTypeDef,
     CustomerProfilesDestinationPropertiesTypeDef,
     DatadogSourcePropertiesTypeDef,
     DeleteConnectorProfileRequestRequestTypeDef,
     DeleteFlowRequestRequestTypeDef,
     DescribeConnectorEntityRequestRequestTypeDef,
     DescribeConnectorProfilesRequestRequestTypeDef,
     DescribeConnectorRequestRequestTypeDef,
@@ -366,60 +371,61 @@
     GoogleAnalyticsSourcePropertiesTypeDef,
     IncrementalPullConfigTypeDef,
     InforNexusSourcePropertiesTypeDef,
     ListConnectorEntitiesRequestRequestTypeDef,
     ListConnectorsRequestRequestTypeDef,
     ListFlowsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     MarketoSourcePropertiesTypeDef,
     RegistrationOutputTypeDef,
     OAuth2CustomParameterTypeDef,
     OAuthPropertiesTypeDef,
     PardotSourcePropertiesTypeDef,
     PrefixConfigTypeDef,
+    RegisterConnectorResponseTypeDef,
+    ResetConnectorMetadataCacheRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     S3InputFormatConfigTypeDef,
     SuccessResponseHandlingConfigTypeDef,
     SAPODataSourcePropertiesTypeDef,
     SalesforceSourcePropertiesTypeDef,
     ScheduledTriggerPropertiesTypeDef,
     ServiceNowSourcePropertiesTypeDef,
     SingularSourcePropertiesTypeDef,
     SlackSourcePropertiesTypeDef,
     TrendmicroSourcePropertiesTypeDef,
     VeevaSourcePropertiesTypeDef,
     ZendeskSourcePropertiesTypeDef,
     StartFlowRequestRequestTypeDef,
+    StartFlowResponseTypeDef,
     StopFlowRequestRequestTypeDef,
+    StopFlowResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UnregisterConnectorRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateConnectorProfileResponseTypeDef,
+    UpdateConnectorRegistrationResponseTypeDef,
+    UpdateFlowResponseTypeDef,
     CustomAuthConfigTypeDef,
+    CustomConnectorSourcePropertiesTypeDef,
+    ListConnectorsResponseTypeDef,
+    ListConnectorEntitiesResponseTypeDef,
     ConnectorMetadataTypeDef,
     GoogleAnalyticsConnectorProfileCredentialsTypeDef,
     HoneycodeConnectorProfileCredentialsTypeDef,
     MarketoConnectorProfileCredentialsTypeDef,
     OAuth2CredentialsTypeDef,
     OAuthCredentialsTypeDef,
     PardotConnectorProfileCredentialsTypeDef,
     SalesforceConnectorProfileCredentialsTypeDef,
     SlackConnectorProfileCredentialsTypeDef,
     ZendeskConnectorProfileCredentialsTypeDef,
     TaskTypeDef,
     ConnectorProvisioningConfigTypeDef,
-    CreateConnectorProfileResponseTypeDef,
-    CreateFlowResponseTypeDef,
-    ListConnectorEntitiesResponseTypeDef,
-    ListConnectorsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RegisterConnectorResponseTypeDef,
-    StartFlowResponseTypeDef,
-    StopFlowResponseTypeDef,
-    UpdateConnectorProfileResponseTypeDef,
-    UpdateConnectorRegistrationResponseTypeDef,
-    UpdateFlowResponseTypeDef,
     CustomConnectorDestinationPropertiesTypeDef,
     EventBridgeDestinationPropertiesTypeDef,
     HoneycodeDestinationPropertiesTypeDef,
     MarketoDestinationPropertiesTypeDef,
     RedshiftDestinationPropertiesTypeDef,
     SalesforceDestinationPropertiesTypeDef,
     SnowflakeDestinationPropertiesTypeDef,
@@ -478,43 +484,43 @@
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

### Comparing `types-aiobotocore-appflow-2.5.0.post1/setup.py` & `types-aiobotocore-appflow-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-appflow.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-appflow",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_appflow"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Appflow 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Appflow 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -48,11 +48,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/"
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

### Comparing `types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/__main__.py` & `types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/__main__.py`

 * *Files 27% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Appflow 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Appflow 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow\nOther"
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

### Comparing `types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/client.py` & `types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/client.py`

 * *Files 5% similar despite different names*

```diff
@@ -18,14 +18,15 @@
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import ConnectionModeType, ConnectorTypeType
 from .type_defs import (
+    CancelFlowExecutionsResponseTypeDef,
     ConnectorProfileConfigTypeDef,
     ConnectorProvisioningConfigTypeDef,
     CreateConnectorProfileResponseTypeDef,
     CreateFlowResponseTypeDef,
     DescribeConnectorEntityResponseTypeDef,
     DescribeConnectorProfilesResponseTypeDef,
     DescribeConnectorResponseTypeDef,
@@ -101,14 +102,24 @@
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#can_paginate)
         """
 
+    async def cancel_flow_executions(
+        self, *, flowName: str, executionIds: Sequence[str] = ...
+    ) -> CancelFlowExecutionsResponseTypeDef:
+        """
+        Cancels active runs for a flow.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.cancel_flow_executions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#cancel_flow_executions)
+        """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#close)
         """
@@ -117,15 +128,16 @@
         self,
         *,
         connectorProfileName: str,
         connectorType: ConnectorTypeType,
         connectionMode: ConnectionModeType,
         connectorProfileConfig: ConnectorProfileConfigTypeDef,
         kmsArn: str = ...,
-        connectorLabel: str = ...
+        connectorLabel: str = ...,
+        clientToken: str = ...
     ) -> CreateConnectorProfileResponseTypeDef:
         """
         Creates a new connector profile associated with your Amazon Web Services
         account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.create_connector_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#create_connector_profile)
@@ -138,15 +150,16 @@
         triggerConfig: TriggerConfigTypeDef,
         sourceFlowConfig: SourceFlowConfigTypeDef,
         destinationFlowConfigList: Sequence[DestinationFlowConfigTypeDef],
         tasks: Sequence[TaskTypeDef],
         description: str = ...,
         kmsArn: str = ...,
         tags: Mapping[str, str] = ...,
-        metadataCatalogConfig: MetadataCatalogConfigTypeDef = ...
+        metadataCatalogConfig: MetadataCatalogConfigTypeDef = ...,
+        clientToken: str = ...
     ) -> CreateFlowResponseTypeDef:
         """
         Enables your application to create a new flow using Amazon AppFlow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.create_flow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#create_flow)
         """
@@ -309,24 +322,44 @@
 
     async def register_connector(
         self,
         *,
         connectorLabel: str = ...,
         description: str = ...,
         connectorProvisioningType: Literal["LAMBDA"] = ...,
-        connectorProvisioningConfig: ConnectorProvisioningConfigTypeDef = ...
+        connectorProvisioningConfig: ConnectorProvisioningConfigTypeDef = ...,
+        clientToken: str = ...
     ) -> RegisterConnectorResponseTypeDef:
         """
         Registers a new custom connector with your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.register_connector)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#register_connector)
         """
 
-    async def start_flow(self, *, flowName: str) -> StartFlowResponseTypeDef:
+    async def reset_connector_metadata_cache(
+        self,
+        *,
+        connectorProfileName: str = ...,
+        connectorType: ConnectorTypeType = ...,
+        connectorEntityName: str = ...,
+        entitiesPath: str = ...,
+        apiVersion: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Resets metadata about your connector entities that Amazon AppFlow stored in its
+        cache.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.reset_connector_metadata_cache)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#reset_connector_metadata_cache)
+        """
+
+    async def start_flow(
+        self, *, flowName: str, clientToken: str = ...
+    ) -> StartFlowResponseTypeDef:
         """
         Activates an existing flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.start_flow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#start_flow)
         """
 
@@ -366,29 +399,31 @@
         """
 
     async def update_connector_profile(
         self,
         *,
         connectorProfileName: str,
         connectionMode: ConnectionModeType,
-        connectorProfileConfig: ConnectorProfileConfigTypeDef
+        connectorProfileConfig: ConnectorProfileConfigTypeDef,
+        clientToken: str = ...
     ) -> UpdateConnectorProfileResponseTypeDef:
         """
         Updates a given connector profile associated with your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.update_connector_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#update_connector_profile)
         """
 
     async def update_connector_registration(
         self,
         *,
         connectorLabel: str,
         description: str = ...,
-        connectorProvisioningConfig: ConnectorProvisioningConfigTypeDef = ...
+        connectorProvisioningConfig: ConnectorProvisioningConfigTypeDef = ...,
+        clientToken: str = ...
     ) -> UpdateConnectorRegistrationResponseTypeDef:
         """
         Updates a custom connector that you've previously registered.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.update_connector_registration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#update_connector_registration)
         """
@@ -398,15 +433,16 @@
         *,
         flowName: str,
         triggerConfig: TriggerConfigTypeDef,
         sourceFlowConfig: SourceFlowConfigTypeDef,
         destinationFlowConfigList: Sequence[DestinationFlowConfigTypeDef],
         tasks: Sequence[TaskTypeDef],
         description: str = ...,
-        metadataCatalogConfig: MetadataCatalogConfigTypeDef = ...
+        metadataCatalogConfig: MetadataCatalogConfigTypeDef = ...,
+        clientToken: str = ...
     ) -> UpdateFlowResponseTypeDef:
         """
         Updates an existing flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.update_flow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#update_flow)
         """
```

### Comparing `types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/client.pyi` & `types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/client.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -18,14 +18,15 @@
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import ConnectionModeType, ConnectorTypeType
 from .type_defs import (
+    CancelFlowExecutionsResponseTypeDef,
     ConnectorProfileConfigTypeDef,
     ConnectorProvisioningConfigTypeDef,
     CreateConnectorProfileResponseTypeDef,
     CreateFlowResponseTypeDef,
     DescribeConnectorEntityResponseTypeDef,
     DescribeConnectorProfilesResponseTypeDef,
     DescribeConnectorResponseTypeDef,
@@ -95,14 +96,23 @@
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#can_paginate)
         """
+    async def cancel_flow_executions(
+        self, *, flowName: str, executionIds: Sequence[str] = ...
+    ) -> CancelFlowExecutionsResponseTypeDef:
+        """
+        Cancels active runs for a flow.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.cancel_flow_executions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#cancel_flow_executions)
+        """
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#close)
         """
@@ -110,15 +120,16 @@
         self,
         *,
         connectorProfileName: str,
         connectorType: ConnectorTypeType,
         connectionMode: ConnectionModeType,
         connectorProfileConfig: ConnectorProfileConfigTypeDef,
         kmsArn: str = ...,
-        connectorLabel: str = ...
+        connectorLabel: str = ...,
+        clientToken: str = ...
     ) -> CreateConnectorProfileResponseTypeDef:
         """
         Creates a new connector profile associated with your Amazon Web Services
         account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.create_connector_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#create_connector_profile)
@@ -130,15 +141,16 @@
         triggerConfig: TriggerConfigTypeDef,
         sourceFlowConfig: SourceFlowConfigTypeDef,
         destinationFlowConfigList: Sequence[DestinationFlowConfigTypeDef],
         tasks: Sequence[TaskTypeDef],
         description: str = ...,
         kmsArn: str = ...,
         tags: Mapping[str, str] = ...,
-        metadataCatalogConfig: MetadataCatalogConfigTypeDef = ...
+        metadataCatalogConfig: MetadataCatalogConfigTypeDef = ...,
+        clientToken: str = ...
     ) -> CreateFlowResponseTypeDef:
         """
         Enables your application to create a new flow using Amazon AppFlow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.create_flow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#create_flow)
         """
@@ -287,23 +299,42 @@
         """
     async def register_connector(
         self,
         *,
         connectorLabel: str = ...,
         description: str = ...,
         connectorProvisioningType: Literal["LAMBDA"] = ...,
-        connectorProvisioningConfig: ConnectorProvisioningConfigTypeDef = ...
+        connectorProvisioningConfig: ConnectorProvisioningConfigTypeDef = ...,
+        clientToken: str = ...
     ) -> RegisterConnectorResponseTypeDef:
         """
         Registers a new custom connector with your Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.register_connector)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#register_connector)
         """
-    async def start_flow(self, *, flowName: str) -> StartFlowResponseTypeDef:
+    async def reset_connector_metadata_cache(
+        self,
+        *,
+        connectorProfileName: str = ...,
+        connectorType: ConnectorTypeType = ...,
+        connectorEntityName: str = ...,
+        entitiesPath: str = ...,
+        apiVersion: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Resets metadata about your connector entities that Amazon AppFlow stored in its
+        cache.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.reset_connector_metadata_cache)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#reset_connector_metadata_cache)
+        """
+    async def start_flow(
+        self, *, flowName: str, clientToken: str = ...
+    ) -> StartFlowResponseTypeDef:
         """
         Activates an existing flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.start_flow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#start_flow)
         """
     async def stop_flow(self, *, flowName: str) -> StopFlowResponseTypeDef:
@@ -338,28 +369,30 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#untag_resource)
         """
     async def update_connector_profile(
         self,
         *,
         connectorProfileName: str,
         connectionMode: ConnectionModeType,
-        connectorProfileConfig: ConnectorProfileConfigTypeDef
+        connectorProfileConfig: ConnectorProfileConfigTypeDef,
+        clientToken: str = ...
     ) -> UpdateConnectorProfileResponseTypeDef:
         """
         Updates a given connector profile associated with your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.update_connector_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#update_connector_profile)
         """
     async def update_connector_registration(
         self,
         *,
         connectorLabel: str,
         description: str = ...,
-        connectorProvisioningConfig: ConnectorProvisioningConfigTypeDef = ...
+        connectorProvisioningConfig: ConnectorProvisioningConfigTypeDef = ...,
+        clientToken: str = ...
     ) -> UpdateConnectorRegistrationResponseTypeDef:
         """
         Updates a custom connector that you've previously registered.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.update_connector_registration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#update_connector_registration)
         """
@@ -368,15 +401,16 @@
         *,
         flowName: str,
         triggerConfig: TriggerConfigTypeDef,
         sourceFlowConfig: SourceFlowConfigTypeDef,
         destinationFlowConfigList: Sequence[DestinationFlowConfigTypeDef],
         tasks: Sequence[TaskTypeDef],
         description: str = ...,
-        metadataCatalogConfig: MetadataCatalogConfigTypeDef = ...
+        metadataCatalogConfig: MetadataCatalogConfigTypeDef = ...,
+        clientToken: str = ...
     ) -> UpdateFlowResponseTypeDef:
         """
         Updates an existing flow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow.Client.update_flow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/client/#update_flow)
         """
```

### Comparing `types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/literals.py` & `types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -14,24 +14,24 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "AggregationTypeType",
     "AmplitudeConnectorOperatorType",
     "AuthenticationTypeType",
     "CatalogTypeType",
     "ConnectionModeType",
     "ConnectorProvisioningTypeType",
     "ConnectorTypeType",
     "DataPullModeType",
+    "DataTransferApiTypeType",
     "DatadogConnectorOperatorType",
     "DynatraceConnectorOperatorType",
     "ExecutionStatusType",
     "FileTypeType",
     "FlowStatusType",
     "GoogleAnalyticsConnectorOperatorType",
     "InforNexusConnectorOperatorType",
@@ -52,27 +52,27 @@
     "SAPODataConnectorOperatorType",
     "SalesforceConnectorOperatorType",
     "SalesforceDataTransferApiType",
     "ScheduleFrequencyTypeType",
     "ServiceNowConnectorOperatorType",
     "SingularConnectorOperatorType",
     "SlackConnectorOperatorType",
+    "SupportedDataTransferTypeType",
     "TaskTypeType",
     "TrendmicroConnectorOperatorType",
     "TriggerTypeType",
     "VeevaConnectorOperatorType",
     "WriteOperationTypeType",
     "ZendeskConnectorOperatorType",
     "AppflowServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 AggregationTypeType = Literal["None", "SingleFile"]
 AmplitudeConnectorOperatorType = Literal["BETWEEN"]
 AuthenticationTypeType = Literal["APIKEY", "BASIC", "CUSTOM", "OAUTH2"]
 CatalogTypeType = Literal["GLUE"]
 ConnectionModeType = Literal["Private", "Public"]
 ConnectorProvisioningTypeType = Literal["LAMBDA"]
 ConnectorTypeType = Literal[
@@ -98,14 +98,15 @@
     "Snowflake",
     "Trendmicro",
     "Upsolver",
     "Veeva",
     "Zendesk",
 ]
 DataPullModeType = Literal["Complete", "Incremental"]
+DataTransferApiTypeType = Literal["ASYNC", "AUTOMATIC", "SYNC"]
 DatadogConnectorOperatorType = Literal[
     "ADDITION",
     "BETWEEN",
     "DIVISION",
     "EQUAL_TO",
     "MASK_ALL",
     "MASK_FIRST_N",
@@ -132,15 +133,15 @@
     "PROJECTION",
     "SUBTRACTION",
     "VALIDATE_NON_NEGATIVE",
     "VALIDATE_NON_NULL",
     "VALIDATE_NON_ZERO",
     "VALIDATE_NUMERIC",
 ]
-ExecutionStatusType = Literal["Error", "InProgress", "Successful"]
+ExecutionStatusType = Literal["CancelStarted", "Canceled", "Error", "InProgress", "Successful"]
 FileTypeType = Literal["CSV", "JSON", "PARQUET"]
 FlowStatusType = Literal["Active", "Deleted", "Deprecated", "Draft", "Errored", "Suspended"]
 GoogleAnalyticsConnectorOperatorType = Literal["BETWEEN", "PROJECTION"]
 InforNexusConnectorOperatorType = Literal[
     "ADDITION",
     "BETWEEN",
     "DIVISION",
@@ -172,15 +173,15 @@
     "SUBTRACTION",
     "VALIDATE_NON_NEGATIVE",
     "VALIDATE_NON_NULL",
     "VALIDATE_NON_ZERO",
     "VALIDATE_NUMERIC",
 ]
 OAuth2CustomPropTypeType = Literal["AUTH_URL", "TOKEN_URL"]
-OAuth2GrantTypeType = Literal["AUTHORIZATION_CODE", "CLIENT_CREDENTIALS"]
+OAuth2GrantTypeType = Literal["AUTHORIZATION_CODE", "CLIENT_CREDENTIALS", "JWT_BEARER"]
 OperatorPropertiesKeysType = Literal[
     "CONCAT_FORMAT",
     "DATA_TYPE",
     "DESTINATION_DATA_TYPE",
     "EXCLUDE_SOURCE_FIELDS_LIST",
     "INCLUDE_NEW_FIELDS",
     "LOWER_BOUND",
@@ -392,14 +393,15 @@
     "PROJECTION",
     "SUBTRACTION",
     "VALIDATE_NON_NEGATIVE",
     "VALIDATE_NON_NULL",
     "VALIDATE_NON_ZERO",
     "VALIDATE_NUMERIC",
 ]
+SupportedDataTransferTypeType = Literal["FILE", "RECORD"]
 TaskTypeType = Literal[
     "Arithmetic",
     "Filter",
     "Map",
     "Map_all",
     "Mask",
     "Merge",
@@ -524,14 +526,15 @@
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
@@ -610,14 +613,15 @@
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
@@ -628,14 +632,15 @@
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
@@ -671,14 +676,15 @@
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
@@ -697,16 +703,19 @@
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
@@ -790,15 +799,17 @@
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

### Comparing `types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/literals.pyi` & `types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -14,23 +14,25 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "AggregationTypeType",
     "AmplitudeConnectorOperatorType",
     "AuthenticationTypeType",
     "CatalogTypeType",
     "ConnectionModeType",
     "ConnectorProvisioningTypeType",
     "ConnectorTypeType",
     "DataPullModeType",
+    "DataTransferApiTypeType",
     "DatadogConnectorOperatorType",
     "DynatraceConnectorOperatorType",
     "ExecutionStatusType",
     "FileTypeType",
     "FlowStatusType",
     "GoogleAnalyticsConnectorOperatorType",
     "InforNexusConnectorOperatorType",
@@ -51,26 +53,28 @@
     "SAPODataConnectorOperatorType",
     "SalesforceConnectorOperatorType",
     "SalesforceDataTransferApiType",
     "ScheduleFrequencyTypeType",
     "ServiceNowConnectorOperatorType",
     "SingularConnectorOperatorType",
     "SlackConnectorOperatorType",
+    "SupportedDataTransferTypeType",
     "TaskTypeType",
     "TrendmicroConnectorOperatorType",
     "TriggerTypeType",
     "VeevaConnectorOperatorType",
     "WriteOperationTypeType",
     "ZendeskConnectorOperatorType",
     "AppflowServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 AggregationTypeType = Literal["None", "SingleFile"]
 AmplitudeConnectorOperatorType = Literal["BETWEEN"]
 AuthenticationTypeType = Literal["APIKEY", "BASIC", "CUSTOM", "OAUTH2"]
 CatalogTypeType = Literal["GLUE"]
 ConnectionModeType = Literal["Private", "Public"]
 ConnectorProvisioningTypeType = Literal["LAMBDA"]
 ConnectorTypeType = Literal[
@@ -96,14 +100,15 @@
     "Snowflake",
     "Trendmicro",
     "Upsolver",
     "Veeva",
     "Zendesk",
 ]
 DataPullModeType = Literal["Complete", "Incremental"]
+DataTransferApiTypeType = Literal["ASYNC", "AUTOMATIC", "SYNC"]
 DatadogConnectorOperatorType = Literal[
     "ADDITION",
     "BETWEEN",
     "DIVISION",
     "EQUAL_TO",
     "MASK_ALL",
     "MASK_FIRST_N",
@@ -130,15 +135,15 @@
     "PROJECTION",
     "SUBTRACTION",
     "VALIDATE_NON_NEGATIVE",
     "VALIDATE_NON_NULL",
     "VALIDATE_NON_ZERO",
     "VALIDATE_NUMERIC",
 ]
-ExecutionStatusType = Literal["Error", "InProgress", "Successful"]
+ExecutionStatusType = Literal["CancelStarted", "Canceled", "Error", "InProgress", "Successful"]
 FileTypeType = Literal["CSV", "JSON", "PARQUET"]
 FlowStatusType = Literal["Active", "Deleted", "Deprecated", "Draft", "Errored", "Suspended"]
 GoogleAnalyticsConnectorOperatorType = Literal["BETWEEN", "PROJECTION"]
 InforNexusConnectorOperatorType = Literal[
     "ADDITION",
     "BETWEEN",
     "DIVISION",
@@ -170,15 +175,15 @@
     "SUBTRACTION",
     "VALIDATE_NON_NEGATIVE",
     "VALIDATE_NON_NULL",
     "VALIDATE_NON_ZERO",
     "VALIDATE_NUMERIC",
 ]
 OAuth2CustomPropTypeType = Literal["AUTH_URL", "TOKEN_URL"]
-OAuth2GrantTypeType = Literal["AUTHORIZATION_CODE", "CLIENT_CREDENTIALS"]
+OAuth2GrantTypeType = Literal["AUTHORIZATION_CODE", "CLIENT_CREDENTIALS", "JWT_BEARER"]
 OperatorPropertiesKeysType = Literal[
     "CONCAT_FORMAT",
     "DATA_TYPE",
     "DESTINATION_DATA_TYPE",
     "EXCLUDE_SOURCE_FIELDS_LIST",
     "INCLUDE_NEW_FIELDS",
     "LOWER_BOUND",
@@ -390,14 +395,15 @@
     "PROJECTION",
     "SUBTRACTION",
     "VALIDATE_NON_NEGATIVE",
     "VALIDATE_NON_NULL",
     "VALIDATE_NON_ZERO",
     "VALIDATE_NUMERIC",
 ]
+SupportedDataTransferTypeType = Literal["FILE", "RECORD"]
 TaskTypeType = Literal[
     "Arithmetic",
     "Filter",
     "Map",
     "Map_all",
     "Mask",
     "Merge",
@@ -522,14 +528,15 @@
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
@@ -608,14 +615,15 @@
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
@@ -626,14 +634,15 @@
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
@@ -669,14 +678,15 @@
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
@@ -695,16 +705,19 @@
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
@@ -788,15 +801,17 @@
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

### Comparing `types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/type_defs.py` & `types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -18,14 +18,15 @@
 from .literals import (
     AggregationTypeType,
     AuthenticationTypeType,
     ConnectionModeType,
     ConnectorTypeType,
     DatadogConnectorOperatorType,
     DataPullModeType,
+    DataTransferApiTypeType,
     DynatraceConnectorOperatorType,
     ExecutionStatusType,
     FileTypeType,
     FlowStatusType,
     GoogleAnalyticsConnectorOperatorType,
     InforNexusConnectorOperatorType,
     MarketoConnectorOperatorType,
@@ -45,14 +46,15 @@
     SalesforceConnectorOperatorType,
     SalesforceDataTransferApiType,
     SAPODataConnectorOperatorType,
     ScheduleFrequencyTypeType,
     ServiceNowConnectorOperatorType,
     SingularConnectorOperatorType,
     SlackConnectorOperatorType,
+    SupportedDataTransferTypeType,
     TaskTypeType,
     TrendmicroConnectorOperatorType,
     TriggerTypeType,
     VeevaConnectorOperatorType,
     WriteOperationTypeType,
     ZendeskConnectorOperatorType,
 )
@@ -62,23 +64,25 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AggregationConfigTypeDef",
     "AmplitudeConnectorProfileCredentialsTypeDef",
     "AmplitudeSourcePropertiesTypeDef",
     "ApiKeyCredentialsTypeDef",
     "AuthParameterTypeDef",
     "BasicAuthCredentialsTypeDef",
+    "CancelFlowExecutionsRequestRequestTypeDef",
+    "CancelFlowExecutionsResponseTypeDef",
     "ConnectorRuntimeSettingTypeDef",
+    "DataTransferApiTypeDef",
     "ConnectorDetailTypeDef",
     "DestinationFieldPropertiesTypeDef",
     "SourceFieldPropertiesTypeDef",
     "ConnectorEntityTypeDef",
     "GoogleAnalyticsMetadataTypeDef",
     "HoneycodeMetadataTypeDef",
     "SalesforceMetadataTypeDef",
@@ -106,19 +110,19 @@
     "ServiceNowConnectorProfilePropertiesTypeDef",
     "SlackConnectorProfilePropertiesTypeDef",
     "SnowflakeConnectorProfilePropertiesTypeDef",
     "VeevaConnectorProfilePropertiesTypeDef",
     "ZendeskConnectorProfilePropertiesTypeDef",
     "PrivateConnectionProvisioningStateTypeDef",
     "LambdaConnectorProvisioningConfigTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateConnectorProfileResponseTypeDef",
+    "CreateFlowResponseTypeDef",
     "CustomAuthCredentialsTypeDef",
     "ErrorHandlingConfigTypeDef",
     "OAuth2PropertiesTypeDef",
-    "CustomConnectorSourcePropertiesTypeDef",
     "CustomerProfilesDestinationPropertiesTypeDef",
     "DatadogSourcePropertiesTypeDef",
     "DeleteConnectorProfileRequestRequestTypeDef",
     "DeleteFlowRequestRequestTypeDef",
     "DescribeConnectorEntityRequestRequestTypeDef",
     "DescribeConnectorProfilesRequestRequestTypeDef",
     "DescribeConnectorRequestRequestTypeDef",
@@ -133,60 +137,61 @@
     "GoogleAnalyticsSourcePropertiesTypeDef",
     "IncrementalPullConfigTypeDef",
     "InforNexusSourcePropertiesTypeDef",
     "ListConnectorEntitiesRequestRequestTypeDef",
     "ListConnectorsRequestRequestTypeDef",
     "ListFlowsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "MarketoSourcePropertiesTypeDef",
     "RegistrationOutputTypeDef",
     "OAuth2CustomParameterTypeDef",
     "OAuthPropertiesTypeDef",
     "PardotSourcePropertiesTypeDef",
     "PrefixConfigTypeDef",
+    "RegisterConnectorResponseTypeDef",
+    "ResetConnectorMetadataCacheRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "S3InputFormatConfigTypeDef",
     "SuccessResponseHandlingConfigTypeDef",
     "SAPODataSourcePropertiesTypeDef",
     "SalesforceSourcePropertiesTypeDef",
     "ScheduledTriggerPropertiesTypeDef",
     "ServiceNowSourcePropertiesTypeDef",
     "SingularSourcePropertiesTypeDef",
     "SlackSourcePropertiesTypeDef",
     "TrendmicroSourcePropertiesTypeDef",
     "VeevaSourcePropertiesTypeDef",
     "ZendeskSourcePropertiesTypeDef",
     "StartFlowRequestRequestTypeDef",
+    "StartFlowResponseTypeDef",
     "StopFlowRequestRequestTypeDef",
+    "StopFlowResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UnregisterConnectorRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateConnectorProfileResponseTypeDef",
+    "UpdateConnectorRegistrationResponseTypeDef",
+    "UpdateFlowResponseTypeDef",
     "CustomAuthConfigTypeDef",
+    "CustomConnectorSourcePropertiesTypeDef",
+    "ListConnectorsResponseTypeDef",
+    "ListConnectorEntitiesResponseTypeDef",
     "ConnectorMetadataTypeDef",
     "GoogleAnalyticsConnectorProfileCredentialsTypeDef",
     "HoneycodeConnectorProfileCredentialsTypeDef",
     "MarketoConnectorProfileCredentialsTypeDef",
     "OAuth2CredentialsTypeDef",
     "OAuthCredentialsTypeDef",
     "PardotConnectorProfileCredentialsTypeDef",
     "SalesforceConnectorProfileCredentialsTypeDef",
     "SlackConnectorProfileCredentialsTypeDef",
     "ZendeskConnectorProfileCredentialsTypeDef",
     "TaskTypeDef",
     "ConnectorProvisioningConfigTypeDef",
-    "CreateConnectorProfileResponseTypeDef",
-    "CreateFlowResponseTypeDef",
-    "ListConnectorEntitiesResponseTypeDef",
-    "ListConnectorsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RegisterConnectorResponseTypeDef",
-    "StartFlowResponseTypeDef",
-    "StopFlowResponseTypeDef",
-    "UpdateConnectorProfileResponseTypeDef",
-    "UpdateConnectorRegistrationResponseTypeDef",
-    "UpdateFlowResponseTypeDef",
     "CustomConnectorDestinationPropertiesTypeDef",
     "EventBridgeDestinationPropertiesTypeDef",
     "HoneycodeDestinationPropertiesTypeDef",
     "MarketoDestinationPropertiesTypeDef",
     "RedshiftDestinationPropertiesTypeDef",
     "SalesforceDestinationPropertiesTypeDef",
     "SnowflakeDestinationPropertiesTypeDef",
@@ -271,21 +276,19 @@
     "_OptionalApiKeyCredentialsTypeDef",
     {
         "apiSecretKey": str,
     },
     total=False,
 )
 
-
 class ApiKeyCredentialsTypeDef(
     _RequiredApiKeyCredentialsTypeDef, _OptionalApiKeyCredentialsTypeDef
 ):
     pass
 
-
 AuthParameterTypeDef = TypedDict(
     "AuthParameterTypeDef",
     {
         "key": str,
         "isRequired": bool,
         "label": str,
         "description": str,
@@ -299,42 +302,80 @@
     "BasicAuthCredentialsTypeDef",
     {
         "username": str,
         "password": str,
     },
 )
 
+_RequiredCancelFlowExecutionsRequestRequestTypeDef = TypedDict(
+    "_RequiredCancelFlowExecutionsRequestRequestTypeDef",
+    {
+        "flowName": str,
+    },
+)
+_OptionalCancelFlowExecutionsRequestRequestTypeDef = TypedDict(
+    "_OptionalCancelFlowExecutionsRequestRequestTypeDef",
+    {
+        "executionIds": Sequence[str],
+    },
+    total=False,
+)
+
+class CancelFlowExecutionsRequestRequestTypeDef(
+    _RequiredCancelFlowExecutionsRequestRequestTypeDef,
+    _OptionalCancelFlowExecutionsRequestRequestTypeDef,
+):
+    pass
+
+CancelFlowExecutionsResponseTypeDef = TypedDict(
+    "CancelFlowExecutionsResponseTypeDef",
+    {
+        "invalidExecutions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ConnectorRuntimeSettingTypeDef = TypedDict(
     "ConnectorRuntimeSettingTypeDef",
     {
         "key": str,
         "dataType": str,
         "isRequired": bool,
         "label": str,
         "description": str,
         "scope": str,
         "connectorSuppliedValueOptions": List[str],
     },
     total=False,
 )
 
+DataTransferApiTypeDef = TypedDict(
+    "DataTransferApiTypeDef",
+    {
+        "Name": str,
+        "Type": DataTransferApiTypeType,
+    },
+    total=False,
+)
+
 ConnectorDetailTypeDef = TypedDict(
     "ConnectorDetailTypeDef",
     {
         "connectorDescription": str,
         "connectorName": str,
         "connectorOwner": str,
         "connectorVersion": str,
         "applicationType": str,
         "connectorType": ConnectorTypeType,
         "connectorLabel": str,
         "registeredAt": datetime,
         "registeredBy": str,
         "connectorProvisioningType": Literal["LAMBDA"],
         "connectorModes": List[str],
+        "supportedDataTransferTypes": List[SupportedDataTransferTypeType],
     },
     total=False,
 )
 
 DestinationFieldPropertiesTypeDef = TypedDict(
     "DestinationFieldPropertiesTypeDef",
     {
@@ -369,19 +410,17 @@
     {
         "label": str,
         "hasNestedEntities": bool,
     },
     total=False,
 )
 
-
 class ConnectorEntityTypeDef(_RequiredConnectorEntityTypeDef, _OptionalConnectorEntityTypeDef):
     pass
 
-
 GoogleAnalyticsMetadataTypeDef = TypedDict(
     "GoogleAnalyticsMetadataTypeDef",
     {
         "oAuthScopes": List[str],
     },
     total=False,
 )
@@ -395,14 +434,15 @@
 )
 
 SalesforceMetadataTypeDef = TypedDict(
     "SalesforceMetadataTypeDef",
     {
         "oAuthScopes": List[str],
         "dataTransferApis": List[SalesforceDataTransferApiType],
+        "oauth2GrantTypesSupported": List[OAuth2GrantTypeType],
     },
     total=False,
 )
 
 SlackMetadataTypeDef = TypedDict(
     "SlackMetadataTypeDef",
     {
@@ -587,27 +627,26 @@
         "clusterIdentifier": str,
         "workgroupName": str,
         "databaseName": str,
     },
     total=False,
 )
 
-
 class RedshiftConnectorProfilePropertiesTypeDef(
     _RequiredRedshiftConnectorProfilePropertiesTypeDef,
     _OptionalRedshiftConnectorProfilePropertiesTypeDef,
 ):
     pass
 
-
 SalesforceConnectorProfilePropertiesTypeDef = TypedDict(
     "SalesforceConnectorProfilePropertiesTypeDef",
     {
         "instanceUrl": str,
         "isSandboxEnvironment": bool,
+        "usePrivateLinkForMetadataAndAuthorization": bool,
     },
     total=False,
 )
 
 ServiceNowConnectorProfilePropertiesTypeDef = TypedDict(
     "ServiceNowConnectorProfilePropertiesTypeDef",
     {
@@ -637,22 +676,20 @@
         "privateLinkServiceName": str,
         "accountName": str,
         "region": str,
     },
     total=False,
 )
 
-
 class SnowflakeConnectorProfilePropertiesTypeDef(
     _RequiredSnowflakeConnectorProfilePropertiesTypeDef,
     _OptionalSnowflakeConnectorProfilePropertiesTypeDef,
 ):
     pass
 
-
 VeevaConnectorProfilePropertiesTypeDef = TypedDict(
     "VeevaConnectorProfilePropertiesTypeDef",
     {
         "instanceUrl": str,
     },
 )
 
@@ -676,22 +713,28 @@
 LambdaConnectorProvisioningConfigTypeDef = TypedDict(
     "LambdaConnectorProvisioningConfigTypeDef",
     {
         "lambdaArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateConnectorProfileResponseTypeDef = TypedDict(
+    "CreateConnectorProfileResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "connectorProfileArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFlowResponseTypeDef = TypedDict(
+    "CreateFlowResponseTypeDef",
+    {
+        "flowArn": str,
+        "flowStatus": FlowStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCustomAuthCredentialsTypeDef = TypedDict(
     "_RequiredCustomAuthCredentialsTypeDef",
     {
         "customAuthenticationType": str,
@@ -701,21 +744,19 @@
     "_OptionalCustomAuthCredentialsTypeDef",
     {
         "credentialsMap": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CustomAuthCredentialsTypeDef(
     _RequiredCustomAuthCredentialsTypeDef, _OptionalCustomAuthCredentialsTypeDef
 ):
     pass
 
-
 ErrorHandlingConfigTypeDef = TypedDict(
     "ErrorHandlingConfigTypeDef",
     {
         "failOnFirstDestinationError": bool,
         "bucketPrefix": str,
         "bucketName": str,
     },
@@ -733,62 +774,37 @@
     "_OptionalOAuth2PropertiesTypeDef",
     {
         "tokenUrlCustomProperties": Mapping[str, str],
     },
     total=False,
 )
 
-
 class OAuth2PropertiesTypeDef(_RequiredOAuth2PropertiesTypeDef, _OptionalOAuth2PropertiesTypeDef):
     pass
 
-
-_RequiredCustomConnectorSourcePropertiesTypeDef = TypedDict(
-    "_RequiredCustomConnectorSourcePropertiesTypeDef",
-    {
-        "entityName": str,
-    },
-)
-_OptionalCustomConnectorSourcePropertiesTypeDef = TypedDict(
-    "_OptionalCustomConnectorSourcePropertiesTypeDef",
-    {
-        "customProperties": Mapping[str, str],
-    },
-    total=False,
-)
-
-
-class CustomConnectorSourcePropertiesTypeDef(
-    _RequiredCustomConnectorSourcePropertiesTypeDef, _OptionalCustomConnectorSourcePropertiesTypeDef
-):
-    pass
-
-
 _RequiredCustomerProfilesDestinationPropertiesTypeDef = TypedDict(
     "_RequiredCustomerProfilesDestinationPropertiesTypeDef",
     {
         "domainName": str,
     },
 )
 _OptionalCustomerProfilesDestinationPropertiesTypeDef = TypedDict(
     "_OptionalCustomerProfilesDestinationPropertiesTypeDef",
     {
         "objectTypeName": str,
     },
     total=False,
 )
 
-
 class CustomerProfilesDestinationPropertiesTypeDef(
     _RequiredCustomerProfilesDestinationPropertiesTypeDef,
     _OptionalCustomerProfilesDestinationPropertiesTypeDef,
 ):
     pass
 
-
 DatadogSourcePropertiesTypeDef = TypedDict(
     "DatadogSourcePropertiesTypeDef",
     {
         "object": str,
     },
 )
 
@@ -802,43 +818,39 @@
     "_OptionalDeleteConnectorProfileRequestRequestTypeDef",
     {
         "forceDelete": bool,
     },
     total=False,
 )
 
-
 class DeleteConnectorProfileRequestRequestTypeDef(
     _RequiredDeleteConnectorProfileRequestRequestTypeDef,
     _OptionalDeleteConnectorProfileRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredDeleteFlowRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteFlowRequestRequestTypeDef",
     {
         "flowName": str,
     },
 )
 _OptionalDeleteFlowRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteFlowRequestRequestTypeDef",
     {
         "forceDelete": bool,
     },
     total=False,
 )
 
-
 class DeleteFlowRequestRequestTypeDef(
     _RequiredDeleteFlowRequestRequestTypeDef, _OptionalDeleteFlowRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredDescribeConnectorEntityRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeConnectorEntityRequestRequestTypeDef",
     {
         "connectorEntityName": str,
     },
 )
 _OptionalDescribeConnectorEntityRequestRequestTypeDef = TypedDict(
@@ -847,22 +859,20 @@
         "connectorType": ConnectorTypeType,
         "connectorProfileName": str,
         "apiVersion": str,
     },
     total=False,
 )
 
-
 class DescribeConnectorEntityRequestRequestTypeDef(
     _RequiredDescribeConnectorEntityRequestRequestTypeDef,
     _OptionalDescribeConnectorEntityRequestRequestTypeDef,
 ):
     pass
 
-
 DescribeConnectorProfilesRequestRequestTypeDef = TypedDict(
     "DescribeConnectorProfilesRequestRequestTypeDef",
     {
         "connectorProfileNames": Sequence[str],
         "connectorType": ConnectorTypeType,
         "connectorLabel": str,
         "maxResults": int,
@@ -881,21 +891,19 @@
     "_OptionalDescribeConnectorRequestRequestTypeDef",
     {
         "connectorLabel": str,
     },
     total=False,
 )
 
-
 class DescribeConnectorRequestRequestTypeDef(
     _RequiredDescribeConnectorRequestRequestTypeDef, _OptionalDescribeConnectorRequestRequestTypeDef
 ):
     pass
 
-
 DescribeConnectorsRequestRequestTypeDef = TypedDict(
     "DescribeConnectorsRequestRequestTypeDef",
     {
         "connectorTypes": Sequence[ConnectorTypeType],
         "maxResults": int,
         "nextToken": str,
     },
@@ -913,22 +921,20 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class DescribeFlowExecutionRecordsRequestRequestTypeDef(
     _RequiredDescribeFlowExecutionRecordsRequestRequestTypeDef,
     _OptionalDescribeFlowExecutionRecordsRequestRequestTypeDef,
 ):
     pass
 
-
 DescribeFlowRequestRequestTypeDef = TypedDict(
     "DescribeFlowRequestRequestTypeDef",
     {
         "flowName": str,
     },
 )
 
@@ -1032,14 +1038,22 @@
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
 MarketoSourcePropertiesTypeDef = TypedDict(
     "MarketoSourcePropertiesTypeDef",
     {
         "object": str,
     },
 )
 
@@ -1089,14 +1103,45 @@
         "prefixType": PrefixTypeType,
         "prefixFormat": PrefixFormatType,
         "pathPrefixHierarchy": Sequence[PathPrefixType],
     },
     total=False,
 )
 
+RegisterConnectorResponseTypeDef = TypedDict(
+    "RegisterConnectorResponseTypeDef",
+    {
+        "connectorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ResetConnectorMetadataCacheRequestRequestTypeDef = TypedDict(
+    "ResetConnectorMetadataCacheRequestRequestTypeDef",
+    {
+        "connectorProfileName": str,
+        "connectorType": ConnectorTypeType,
+        "connectorEntityName": str,
+        "entitiesPath": str,
+        "apiVersion": str,
+    },
+    total=False,
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
 S3InputFormatConfigTypeDef = TypedDict(
     "S3InputFormatConfigTypeDef",
     {
         "s3InputFileType": S3InputFileTypeType,
     },
     total=False,
 )
@@ -1130,21 +1175,19 @@
         "enableDynamicFieldUpdate": bool,
         "includeDeletedRecords": bool,
         "dataTransferApi": SalesforceDataTransferApiType,
     },
     total=False,
 )
 
-
 class SalesforceSourcePropertiesTypeDef(
     _RequiredSalesforceSourcePropertiesTypeDef, _OptionalSalesforceSourcePropertiesTypeDef
 ):
     pass
 
-
 _RequiredScheduledTriggerPropertiesTypeDef = TypedDict(
     "_RequiredScheduledTriggerPropertiesTypeDef",
     {
         "scheduleExpression": str,
     },
 )
 _OptionalScheduledTriggerPropertiesTypeDef = TypedDict(
@@ -1157,21 +1200,19 @@
         "scheduleOffset": int,
         "firstExecutionFrom": Union[datetime, str],
         "flowErrorDeactivationThreshold": int,
     },
     total=False,
 )
 
-
 class ScheduledTriggerPropertiesTypeDef(
     _RequiredScheduledTriggerPropertiesTypeDef, _OptionalScheduledTriggerPropertiesTypeDef
 ):
     pass
 
-
 ServiceNowSourcePropertiesTypeDef = TypedDict(
     "ServiceNowSourcePropertiesTypeDef",
     {
         "object": str,
     },
 )
 
@@ -1209,42 +1250,71 @@
         "includeSourceFiles": bool,
         "includeRenditions": bool,
         "includeAllVersions": bool,
     },
     total=False,
 )
 
-
 class VeevaSourcePropertiesTypeDef(
     _RequiredVeevaSourcePropertiesTypeDef, _OptionalVeevaSourcePropertiesTypeDef
 ):
     pass
 
-
 ZendeskSourcePropertiesTypeDef = TypedDict(
     "ZendeskSourcePropertiesTypeDef",
     {
         "object": str,
     },
 )
 
-StartFlowRequestRequestTypeDef = TypedDict(
-    "StartFlowRequestRequestTypeDef",
+_RequiredStartFlowRequestRequestTypeDef = TypedDict(
+    "_RequiredStartFlowRequestRequestTypeDef",
     {
         "flowName": str,
     },
 )
+_OptionalStartFlowRequestRequestTypeDef = TypedDict(
+    "_OptionalStartFlowRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class StartFlowRequestRequestTypeDef(
+    _RequiredStartFlowRequestRequestTypeDef, _OptionalStartFlowRequestRequestTypeDef
+):
+    pass
+
+StartFlowResponseTypeDef = TypedDict(
+    "StartFlowResponseTypeDef",
+    {
+        "flowArn": str,
+        "flowStatus": FlowStatusType,
+        "executionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 StopFlowRequestRequestTypeDef = TypedDict(
     "StopFlowRequestRequestTypeDef",
     {
         "flowName": str,
     },
 )
 
+StopFlowResponseTypeDef = TypedDict(
+    "StopFlowResponseTypeDef",
+    {
+        "flowArn": str,
+        "flowStatus": FlowStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -1259,39 +1329,99 @@
     "_OptionalUnregisterConnectorRequestRequestTypeDef",
     {
         "forceDelete": bool,
     },
     total=False,
 )
 
-
 class UnregisterConnectorRequestRequestTypeDef(
     _RequiredUnregisterConnectorRequestRequestTypeDef,
     _OptionalUnregisterConnectorRequestRequestTypeDef,
 ):
     pass
 
-
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateConnectorProfileResponseTypeDef = TypedDict(
+    "UpdateConnectorProfileResponseTypeDef",
+    {
+        "connectorProfileArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateConnectorRegistrationResponseTypeDef = TypedDict(
+    "UpdateConnectorRegistrationResponseTypeDef",
+    {
+        "connectorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateFlowResponseTypeDef = TypedDict(
+    "UpdateFlowResponseTypeDef",
+    {
+        "flowStatus": FlowStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomAuthConfigTypeDef = TypedDict(
     "CustomAuthConfigTypeDef",
     {
         "customAuthenticationType": str,
         "authParameters": List[AuthParameterTypeDef],
     },
     total=False,
 )
 
+_RequiredCustomConnectorSourcePropertiesTypeDef = TypedDict(
+    "_RequiredCustomConnectorSourcePropertiesTypeDef",
+    {
+        "entityName": str,
+    },
+)
+_OptionalCustomConnectorSourcePropertiesTypeDef = TypedDict(
+    "_OptionalCustomConnectorSourcePropertiesTypeDef",
+    {
+        "customProperties": Mapping[str, str],
+        "dataTransferApi": DataTransferApiTypeDef,
+    },
+    total=False,
+)
+
+class CustomConnectorSourcePropertiesTypeDef(
+    _RequiredCustomConnectorSourcePropertiesTypeDef, _OptionalCustomConnectorSourcePropertiesTypeDef
+):
+    pass
+
+ListConnectorsResponseTypeDef = TypedDict(
+    "ListConnectorsResponseTypeDef",
+    {
+        "connectors": List[ConnectorDetailTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListConnectorEntitiesResponseTypeDef = TypedDict(
+    "ListConnectorEntitiesResponseTypeDef",
+    {
+        "connectorEntityMap": Dict[str, List[ConnectorEntityTypeDef]],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ConnectorMetadataTypeDef = TypedDict(
     "ConnectorMetadataTypeDef",
     {
         "Amplitude": Dict[str, Any],
         "Datadog": Dict[str, Any],
         "Dynatrace": Dict[str, Any],
         "GoogleAnalytics": GoogleAnalyticsMetadataTypeDef,
@@ -1330,22 +1460,20 @@
         "accessToken": str,
         "refreshToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
     },
     total=False,
 )
 
-
 class GoogleAnalyticsConnectorProfileCredentialsTypeDef(
     _RequiredGoogleAnalyticsConnectorProfileCredentialsTypeDef,
     _OptionalGoogleAnalyticsConnectorProfileCredentialsTypeDef,
 ):
     pass
 
-
 HoneycodeConnectorProfileCredentialsTypeDef = TypedDict(
     "HoneycodeConnectorProfileCredentialsTypeDef",
     {
         "accessToken": str,
         "refreshToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
     },
@@ -1364,22 +1492,20 @@
     {
         "accessToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
     },
     total=False,
 )
 
-
 class MarketoConnectorProfileCredentialsTypeDef(
     _RequiredMarketoConnectorProfileCredentialsTypeDef,
     _OptionalMarketoConnectorProfileCredentialsTypeDef,
 ):
     pass
 
-
 OAuth2CredentialsTypeDef = TypedDict(
     "OAuth2CredentialsTypeDef",
     {
         "clientId": str,
         "clientSecret": str,
         "accessToken": str,
         "refreshToken": str,
@@ -1401,19 +1527,17 @@
         "accessToken": str,
         "refreshToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
     },
     total=False,
 )
 
-
 class OAuthCredentialsTypeDef(_RequiredOAuthCredentialsTypeDef, _OptionalOAuthCredentialsTypeDef):
     pass
 
-
 PardotConnectorProfileCredentialsTypeDef = TypedDict(
     "PardotConnectorProfileCredentialsTypeDef",
     {
         "accessToken": str,
         "refreshToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
         "clientCredentialsArn": str,
@@ -1424,14 +1548,16 @@
 SalesforceConnectorProfileCredentialsTypeDef = TypedDict(
     "SalesforceConnectorProfileCredentialsTypeDef",
     {
         "accessToken": str,
         "refreshToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
         "clientCredentialsArn": str,
+        "oAuth2GrantType": OAuth2GrantTypeType,
+        "jwtToken": str,
     },
     total=False,
 )
 
 _RequiredSlackConnectorProfileCredentialsTypeDef = TypedDict(
     "_RequiredSlackConnectorProfileCredentialsTypeDef",
     {
@@ -1444,22 +1570,20 @@
     {
         "accessToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
     },
     total=False,
 )
 
-
 class SlackConnectorProfileCredentialsTypeDef(
     _RequiredSlackConnectorProfileCredentialsTypeDef,
     _OptionalSlackConnectorProfileCredentialsTypeDef,
 ):
     pass
 
-
 _RequiredZendeskConnectorProfileCredentialsTypeDef = TypedDict(
     "_RequiredZendeskConnectorProfileCredentialsTypeDef",
     {
         "clientId": str,
         "clientSecret": str,
     },
 )
@@ -1468,22 +1592,20 @@
     {
         "accessToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
     },
     total=False,
 )
 
-
 class ZendeskConnectorProfileCredentialsTypeDef(
     _RequiredZendeskConnectorProfileCredentialsTypeDef,
     _OptionalZendeskConnectorProfileCredentialsTypeDef,
 ):
     pass
 
-
 _RequiredTaskTypeDef = TypedDict(
     "_RequiredTaskTypeDef",
     {
         "sourceFields": Sequence[str],
         "taskType": TaskTypeType,
     },
 )
@@ -1493,121 +1615,25 @@
         "connectorOperator": ConnectorOperatorTypeDef,
         "destinationField": str,
         "taskProperties": Mapping[OperatorPropertiesKeysType, str],
     },
     total=False,
 )
 
-
 class TaskTypeDef(_RequiredTaskTypeDef, _OptionalTaskTypeDef):
     pass
 
-
 ConnectorProvisioningConfigTypeDef = TypedDict(
     "ConnectorProvisioningConfigTypeDef",
     {
         "lambda": LambdaConnectorProvisioningConfigTypeDef,
     },
     total=False,
 )
 
-CreateConnectorProfileResponseTypeDef = TypedDict(
-    "CreateConnectorProfileResponseTypeDef",
-    {
-        "connectorProfileArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFlowResponseTypeDef = TypedDict(
-    "CreateFlowResponseTypeDef",
-    {
-        "flowArn": str,
-        "flowStatus": FlowStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConnectorEntitiesResponseTypeDef = TypedDict(
-    "ListConnectorEntitiesResponseTypeDef",
-    {
-        "connectorEntityMap": Dict[str, List[ConnectorEntityTypeDef]],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConnectorsResponseTypeDef = TypedDict(
-    "ListConnectorsResponseTypeDef",
-    {
-        "connectors": List[ConnectorDetailTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterConnectorResponseTypeDef = TypedDict(
-    "RegisterConnectorResponseTypeDef",
-    {
-        "connectorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartFlowResponseTypeDef = TypedDict(
-    "StartFlowResponseTypeDef",
-    {
-        "flowArn": str,
-        "flowStatus": FlowStatusType,
-        "executionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopFlowResponseTypeDef = TypedDict(
-    "StopFlowResponseTypeDef",
-    {
-        "flowArn": str,
-        "flowStatus": FlowStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateConnectorProfileResponseTypeDef = TypedDict(
-    "UpdateConnectorProfileResponseTypeDef",
-    {
-        "connectorProfileArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateConnectorRegistrationResponseTypeDef = TypedDict(
-    "UpdateConnectorRegistrationResponseTypeDef",
-    {
-        "connectorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFlowResponseTypeDef = TypedDict(
-    "UpdateFlowResponseTypeDef",
-    {
-        "flowStatus": FlowStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCustomConnectorDestinationPropertiesTypeDef = TypedDict(
     "_RequiredCustomConnectorDestinationPropertiesTypeDef",
     {
         "entityName": str,
     },
 )
 _OptionalCustomConnectorDestinationPropertiesTypeDef = TypedDict(
@@ -1617,86 +1643,78 @@
         "writeOperationType": WriteOperationTypeType,
         "idFieldNames": Sequence[str],
         "customProperties": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CustomConnectorDestinationPropertiesTypeDef(
     _RequiredCustomConnectorDestinationPropertiesTypeDef,
     _OptionalCustomConnectorDestinationPropertiesTypeDef,
 ):
     pass
 
-
 _RequiredEventBridgeDestinationPropertiesTypeDef = TypedDict(
     "_RequiredEventBridgeDestinationPropertiesTypeDef",
     {
         "object": str,
     },
 )
 _OptionalEventBridgeDestinationPropertiesTypeDef = TypedDict(
     "_OptionalEventBridgeDestinationPropertiesTypeDef",
     {
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
     },
     total=False,
 )
 
-
 class EventBridgeDestinationPropertiesTypeDef(
     _RequiredEventBridgeDestinationPropertiesTypeDef,
     _OptionalEventBridgeDestinationPropertiesTypeDef,
 ):
     pass
 
-
 _RequiredHoneycodeDestinationPropertiesTypeDef = TypedDict(
     "_RequiredHoneycodeDestinationPropertiesTypeDef",
     {
         "object": str,
     },
 )
 _OptionalHoneycodeDestinationPropertiesTypeDef = TypedDict(
     "_OptionalHoneycodeDestinationPropertiesTypeDef",
     {
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
     },
     total=False,
 )
 
-
 class HoneycodeDestinationPropertiesTypeDef(
     _RequiredHoneycodeDestinationPropertiesTypeDef, _OptionalHoneycodeDestinationPropertiesTypeDef
 ):
     pass
 
-
 _RequiredMarketoDestinationPropertiesTypeDef = TypedDict(
     "_RequiredMarketoDestinationPropertiesTypeDef",
     {
         "object": str,
     },
 )
 _OptionalMarketoDestinationPropertiesTypeDef = TypedDict(
     "_OptionalMarketoDestinationPropertiesTypeDef",
     {
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
     },
     total=False,
 )
 
-
 class MarketoDestinationPropertiesTypeDef(
     _RequiredMarketoDestinationPropertiesTypeDef, _OptionalMarketoDestinationPropertiesTypeDef
 ):
     pass
 
-
 _RequiredRedshiftDestinationPropertiesTypeDef = TypedDict(
     "_RequiredRedshiftDestinationPropertiesTypeDef",
     {
         "object": str,
         "intermediateBucketName": str,
     },
 )
@@ -1705,21 +1723,19 @@
     {
         "bucketPrefix": str,
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
     },
     total=False,
 )
 
-
 class RedshiftDestinationPropertiesTypeDef(
     _RequiredRedshiftDestinationPropertiesTypeDef, _OptionalRedshiftDestinationPropertiesTypeDef
 ):
     pass
 
-
 _RequiredSalesforceDestinationPropertiesTypeDef = TypedDict(
     "_RequiredSalesforceDestinationPropertiesTypeDef",
     {
         "object": str,
     },
 )
 _OptionalSalesforceDestinationPropertiesTypeDef = TypedDict(
@@ -1729,21 +1745,19 @@
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
         "writeOperationType": WriteOperationTypeType,
         "dataTransferApi": SalesforceDataTransferApiType,
     },
     total=False,
 )
 
-
 class SalesforceDestinationPropertiesTypeDef(
     _RequiredSalesforceDestinationPropertiesTypeDef, _OptionalSalesforceDestinationPropertiesTypeDef
 ):
     pass
 
-
 _RequiredSnowflakeDestinationPropertiesTypeDef = TypedDict(
     "_RequiredSnowflakeDestinationPropertiesTypeDef",
     {
         "object": str,
         "intermediateBucketName": str,
     },
 )
@@ -1752,21 +1766,19 @@
     {
         "bucketPrefix": str,
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
     },
     total=False,
 )
 
-
 class SnowflakeDestinationPropertiesTypeDef(
     _RequiredSnowflakeDestinationPropertiesTypeDef, _OptionalSnowflakeDestinationPropertiesTypeDef
 ):
     pass
 
-
 _RequiredZendeskDestinationPropertiesTypeDef = TypedDict(
     "_RequiredZendeskDestinationPropertiesTypeDef",
     {
         "object": str,
     },
 )
 _OptionalZendeskDestinationPropertiesTypeDef = TypedDict(
@@ -1775,21 +1787,19 @@
         "idFieldNames": Sequence[str],
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
         "writeOperationType": WriteOperationTypeType,
     },
     total=False,
 )
 
-
 class ZendeskDestinationPropertiesTypeDef(
     _RequiredZendeskDestinationPropertiesTypeDef, _OptionalZendeskDestinationPropertiesTypeDef
 ):
     pass
 
-
 CustomConnectorProfilePropertiesTypeDef = TypedDict(
     "CustomConnectorProfilePropertiesTypeDef",
     {
         "profileProperties": Mapping[str, str],
         "oAuth2Properties": OAuth2PropertiesTypeDef,
     },
     total=False,
@@ -1843,19 +1853,17 @@
         "supportedDateFormat": str,
         "fieldValueRange": RangeTypeDef,
         "fieldLengthRange": RangeTypeDef,
     },
     total=False,
 )
 
-
 class FieldTypeDetailsTypeDef(_RequiredFieldTypeDetailsTypeDef, _OptionalFieldTypeDetailsTypeDef):
     pass
 
-
 MetadataCatalogConfigTypeDef = TypedDict(
     "MetadataCatalogConfigTypeDef",
     {
         "glueDataCatalog": GlueDataCatalogConfigTypeDef,
     },
     total=False,
 )
@@ -1898,22 +1906,20 @@
         "logonLanguage": str,
         "privateLinkServiceName": str,
         "oAuthProperties": OAuthPropertiesTypeDef,
     },
     total=False,
 )
 
-
 class SAPODataConnectorProfilePropertiesTypeDef(
     _RequiredSAPODataConnectorProfilePropertiesTypeDef,
     _OptionalSAPODataConnectorProfilePropertiesTypeDef,
 ):
     pass
 
-
 S3OutputFormatConfigTypeDef = TypedDict(
     "S3OutputFormatConfigTypeDef",
     {
         "fileType": FileTypeType,
         "prefixConfig": PrefixConfigTypeDef,
         "aggregationConfig": AggregationConfigTypeDef,
         "preserveSourceDataTyping": bool,
@@ -1932,21 +1938,19 @@
     {
         "fileType": FileTypeType,
         "aggregationConfig": AggregationConfigTypeDef,
     },
     total=False,
 )
 
-
 class UpsolverS3OutputFormatConfigTypeDef(
     _RequiredUpsolverS3OutputFormatConfigTypeDef, _OptionalUpsolverS3OutputFormatConfigTypeDef
 ):
     pass
 
-
 _RequiredS3SourcePropertiesTypeDef = TypedDict(
     "_RequiredS3SourcePropertiesTypeDef",
     {
         "bucketName": str,
     },
 )
 _OptionalS3SourcePropertiesTypeDef = TypedDict(
@@ -1954,21 +1958,19 @@
     {
         "bucketPrefix": str,
         "s3InputFormatConfig": S3InputFormatConfigTypeDef,
     },
     total=False,
 )
 
-
 class S3SourcePropertiesTypeDef(
     _RequiredS3SourcePropertiesTypeDef, _OptionalS3SourcePropertiesTypeDef
 ):
     pass
 
-
 _RequiredSAPODataDestinationPropertiesTypeDef = TypedDict(
     "_RequiredSAPODataDestinationPropertiesTypeDef",
     {
         "objectPath": str,
     },
 )
 _OptionalSAPODataDestinationPropertiesTypeDef = TypedDict(
@@ -1978,21 +1980,19 @@
         "idFieldNames": Sequence[str],
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
         "writeOperationType": WriteOperationTypeType,
     },
     total=False,
 )
 
-
 class SAPODataDestinationPropertiesTypeDef(
     _RequiredSAPODataDestinationPropertiesTypeDef, _OptionalSAPODataDestinationPropertiesTypeDef
 ):
     pass
 
-
 TriggerPropertiesTypeDef = TypedDict(
     "TriggerPropertiesTypeDef",
     {
         "Scheduled": ScheduledTriggerPropertiesTypeDef,
     },
     total=False,
 )
@@ -2010,22 +2010,20 @@
         "oauth2": OAuth2CredentialsTypeDef,
         "apiKey": ApiKeyCredentialsTypeDef,
         "custom": CustomAuthCredentialsTypeDef,
     },
     total=False,
 )
 
-
 class CustomConnectorProfileCredentialsTypeDef(
     _RequiredCustomConnectorProfileCredentialsTypeDef,
     _OptionalCustomConnectorProfileCredentialsTypeDef,
 ):
     pass
 
-
 SAPODataConnectorProfileCredentialsTypeDef = TypedDict(
     "SAPODataConnectorProfileCredentialsTypeDef",
     {
         "basicAuthCredentials": BasicAuthCredentialsTypeDef,
         "oAuthCredentials": OAuthCredentialsTypeDef,
     },
     total=False,
@@ -2034,14 +2032,15 @@
 RegisterConnectorRequestRequestTypeDef = TypedDict(
     "RegisterConnectorRequestRequestTypeDef",
     {
         "connectorLabel": str,
         "description": str,
         "connectorProvisioningType": Literal["LAMBDA"],
         "connectorProvisioningConfig": ConnectorProvisioningConfigTypeDef,
+        "clientToken": str,
     },
     total=False,
 )
 
 _RequiredUpdateConnectorRegistrationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateConnectorRegistrationRequestRequestTypeDef",
     {
@@ -2049,32 +2048,31 @@
     },
 )
 _OptionalUpdateConnectorRegistrationRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateConnectorRegistrationRequestRequestTypeDef",
     {
         "description": str,
         "connectorProvisioningConfig": ConnectorProvisioningConfigTypeDef,
+        "clientToken": str,
     },
     total=False,
 )
 
-
 class UpdateConnectorRegistrationRequestRequestTypeDef(
     _RequiredUpdateConnectorRegistrationRequestRequestTypeDef,
     _OptionalUpdateConnectorRegistrationRequestRequestTypeDef,
 ):
     pass
 
-
 ListFlowsResponseTypeDef = TypedDict(
     "ListFlowsResponseTypeDef",
     {
         "flows": List[FlowDefinitionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SupportedFieldTypeDetailsTypeDef = TypedDict(
     "SupportedFieldTypeDetailsTypeDef",
     {
         "v1": FieldTypeDetailsTypeDef,
@@ -2146,21 +2144,19 @@
     {
         "bucketPrefix": str,
         "s3OutputFormatConfig": S3OutputFormatConfigTypeDef,
     },
     total=False,
 )
 
-
 class S3DestinationPropertiesTypeDef(
     _RequiredS3DestinationPropertiesTypeDef, _OptionalS3DestinationPropertiesTypeDef
 ):
     pass
 
-
 _RequiredUpsolverDestinationPropertiesTypeDef = TypedDict(
     "_RequiredUpsolverDestinationPropertiesTypeDef",
     {
         "bucketName": str,
         "s3OutputFormatConfig": UpsolverS3OutputFormatConfigTypeDef,
     },
 )
@@ -2168,21 +2164,19 @@
     "_OptionalUpsolverDestinationPropertiesTypeDef",
     {
         "bucketPrefix": str,
     },
     total=False,
 )
 
-
 class UpsolverDestinationPropertiesTypeDef(
     _RequiredUpsolverDestinationPropertiesTypeDef, _OptionalUpsolverDestinationPropertiesTypeDef
 ):
     pass
 
-
 SourceConnectorPropertiesTypeDef = TypedDict(
     "SourceConnectorPropertiesTypeDef",
     {
         "Amplitude": AmplitudeSourcePropertiesTypeDef,
         "Datadog": DatadogSourcePropertiesTypeDef,
         "Dynatrace": DynatraceSourcePropertiesTypeDef,
         "GoogleAnalytics": GoogleAnalyticsSourcePropertiesTypeDef,
@@ -2213,19 +2207,17 @@
     "_OptionalTriggerConfigTypeDef",
     {
         "triggerProperties": TriggerPropertiesTypeDef,
     },
     total=False,
 )
 
-
 class TriggerConfigTypeDef(_RequiredTriggerConfigTypeDef, _OptionalTriggerConfigTypeDef):
     pass
 
-
 ConnectorProfileCredentialsTypeDef = TypedDict(
     "ConnectorProfileCredentialsTypeDef",
     {
         "Amplitude": AmplitudeConnectorProfileCredentialsTypeDef,
         "Datadog": DatadogConnectorProfileCredentialsTypeDef,
         "Dynatrace": DynatraceConnectorProfileCredentialsTypeDef,
         "GoogleAnalytics": GoogleAnalyticsConnectorProfileCredentialsTypeDef,
@@ -2267,27 +2259,25 @@
         "sourceProperties": SourceFieldPropertiesTypeDef,
         "destinationProperties": DestinationFieldPropertiesTypeDef,
         "customProperties": Dict[str, str],
     },
     total=False,
 )
 
-
 class ConnectorEntityFieldTypeDef(
     _RequiredConnectorEntityFieldTypeDef, _OptionalConnectorEntityFieldTypeDef
 ):
     pass
 
-
 DescribeFlowExecutionRecordsResponseTypeDef = TypedDict(
     "DescribeFlowExecutionRecordsResponseTypeDef",
     {
         "flowExecutions": List[ExecutionRecordTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectorConfigurationTypeDef = TypedDict(
     "ConnectorConfigurationTypeDef",
     {
         "canUseAsSource": bool,
@@ -2312,14 +2302,16 @@
         "supportedOperators": List[OperatorsType],
         "supportedWriteOperations": List[WriteOperationTypeType],
         "connectorProvisioningType": Literal["LAMBDA"],
         "connectorProvisioningConfig": ConnectorProvisioningConfigTypeDef,
         "logoURL": str,
         "registeredAt": datetime,
         "registeredBy": str,
+        "supportedDataTransferTypes": List[SupportedDataTransferTypeType],
+        "supportedDataTransferApis": List[DataTransferApiTypeDef],
     },
     total=False,
 )
 
 ConnectorProfileTypeDef = TypedDict(
     "ConnectorProfileTypeDef",
     {
@@ -2370,72 +2362,68 @@
         "apiVersion": str,
         "connectorProfileName": str,
         "incrementalPullConfig": IncrementalPullConfigTypeDef,
     },
     total=False,
 )
 
-
 class SourceFlowConfigTypeDef(_RequiredSourceFlowConfigTypeDef, _OptionalSourceFlowConfigTypeDef):
     pass
 
-
 _RequiredConnectorProfileConfigTypeDef = TypedDict(
     "_RequiredConnectorProfileConfigTypeDef",
     {
         "connectorProfileProperties": ConnectorProfilePropertiesTypeDef,
     },
 )
 _OptionalConnectorProfileConfigTypeDef = TypedDict(
     "_OptionalConnectorProfileConfigTypeDef",
     {
         "connectorProfileCredentials": ConnectorProfileCredentialsTypeDef,
     },
     total=False,
 )
 
-
 class ConnectorProfileConfigTypeDef(
     _RequiredConnectorProfileConfigTypeDef, _OptionalConnectorProfileConfigTypeDef
 ):
     pass
 
-
 DescribeConnectorEntityResponseTypeDef = TypedDict(
     "DescribeConnectorEntityResponseTypeDef",
     {
         "connectorEntityFields": List[ConnectorEntityFieldTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConnectorResponseTypeDef = TypedDict(
     "DescribeConnectorResponseTypeDef",
     {
         "connectorConfiguration": ConnectorConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConnectorsResponseTypeDef = TypedDict(
     "DescribeConnectorsResponseTypeDef",
     {
         "connectorConfigurations": Dict[ConnectorTypeType, ConnectorConfigurationTypeDef],
         "connectors": List[ConnectorDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConnectorProfilesResponseTypeDef = TypedDict(
     "DescribeConnectorProfilesResponseTypeDef",
     {
         "connectorProfileDetails": List[ConnectorProfileTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDestinationFlowConfigTypeDef = TypedDict(
     "_RequiredDestinationFlowConfigTypeDef",
     {
         "connectorType": ConnectorTypeType,
@@ -2447,55 +2435,65 @@
     {
         "apiVersion": str,
         "connectorProfileName": str,
     },
     total=False,
 )
 
-
 class DestinationFlowConfigTypeDef(
     _RequiredDestinationFlowConfigTypeDef, _OptionalDestinationFlowConfigTypeDef
 ):
     pass
 
-
 _RequiredCreateConnectorProfileRequestRequestTypeDef = TypedDict(
     "_RequiredCreateConnectorProfileRequestRequestTypeDef",
     {
         "connectorProfileName": str,
         "connectorType": ConnectorTypeType,
         "connectionMode": ConnectionModeType,
         "connectorProfileConfig": ConnectorProfileConfigTypeDef,
     },
 )
 _OptionalCreateConnectorProfileRequestRequestTypeDef = TypedDict(
     "_OptionalCreateConnectorProfileRequestRequestTypeDef",
     {
         "kmsArn": str,
         "connectorLabel": str,
+        "clientToken": str,
     },
     total=False,
 )
 
-
 class CreateConnectorProfileRequestRequestTypeDef(
     _RequiredCreateConnectorProfileRequestRequestTypeDef,
     _OptionalCreateConnectorProfileRequestRequestTypeDef,
 ):
     pass
 
-
-UpdateConnectorProfileRequestRequestTypeDef = TypedDict(
-    "UpdateConnectorProfileRequestRequestTypeDef",
+_RequiredUpdateConnectorProfileRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateConnectorProfileRequestRequestTypeDef",
     {
         "connectorProfileName": str,
         "connectionMode": ConnectionModeType,
         "connectorProfileConfig": ConnectorProfileConfigTypeDef,
     },
 )
+_OptionalUpdateConnectorProfileRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateConnectorProfileRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class UpdateConnectorProfileRequestRequestTypeDef(
+    _RequiredUpdateConnectorProfileRequestRequestTypeDef,
+    _OptionalUpdateConnectorProfileRequestRequestTypeDef,
+):
+    pass
 
 _RequiredCreateFlowRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFlowRequestRequestTypeDef",
     {
         "flowName": str,
         "triggerConfig": TriggerConfigTypeDef,
         "sourceFlowConfig": SourceFlowConfigTypeDef,
@@ -2506,25 +2504,24 @@
 _OptionalCreateFlowRequestRequestTypeDef = TypedDict(
     "_OptionalCreateFlowRequestRequestTypeDef",
     {
         "description": str,
         "kmsArn": str,
         "tags": Mapping[str, str],
         "metadataCatalogConfig": MetadataCatalogConfigTypeDef,
+        "clientToken": str,
     },
     total=False,
 )
 
-
 class CreateFlowRequestRequestTypeDef(
     _RequiredCreateFlowRequestRequestTypeDef, _OptionalCreateFlowRequestRequestTypeDef
 ):
     pass
 
-
 DescribeFlowResponseTypeDef = TypedDict(
     "DescribeFlowResponseTypeDef",
     {
         "flowArn": str,
         "description": str,
         "flowName": str,
         "kmsArn": str,
@@ -2539,15 +2536,15 @@
         "lastUpdatedAt": datetime,
         "createdBy": str,
         "lastUpdatedBy": str,
         "tags": Dict[str, str],
         "metadataCatalogConfig": MetadataCatalogConfigTypeDef,
         "lastRunMetadataCatalogDetails": List[MetadataCatalogDetailTypeDef],
         "schemaVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateFlowRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFlowRequestRequestTypeDef",
     {
         "flowName": str,
@@ -2558,16 +2555,16 @@
     },
 )
 _OptionalUpdateFlowRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateFlowRequestRequestTypeDef",
     {
         "description": str,
         "metadataCatalogConfig": MetadataCatalogConfigTypeDef,
+        "clientToken": str,
     },
     total=False,
 )
 
-
 class UpdateFlowRequestRequestTypeDef(
     _RequiredUpdateFlowRequestRequestTypeDef, _OptionalUpdateFlowRequestRequestTypeDef
 ):
     pass
```

### Comparing `types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow/type_defs.pyi` & `types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -18,14 +18,15 @@
 from .literals import (
     AggregationTypeType,
     AuthenticationTypeType,
     ConnectionModeType,
     ConnectorTypeType,
     DatadogConnectorOperatorType,
     DataPullModeType,
+    DataTransferApiTypeType,
     DynatraceConnectorOperatorType,
     ExecutionStatusType,
     FileTypeType,
     FlowStatusType,
     GoogleAnalyticsConnectorOperatorType,
     InforNexusConnectorOperatorType,
     MarketoConnectorOperatorType,
@@ -45,14 +46,15 @@
     SalesforceConnectorOperatorType,
     SalesforceDataTransferApiType,
     SAPODataConnectorOperatorType,
     ScheduleFrequencyTypeType,
     ServiceNowConnectorOperatorType,
     SingularConnectorOperatorType,
     SlackConnectorOperatorType,
+    SupportedDataTransferTypeType,
     TaskTypeType,
     TrendmicroConnectorOperatorType,
     TriggerTypeType,
     VeevaConnectorOperatorType,
     WriteOperationTypeType,
     ZendeskConnectorOperatorType,
 )
@@ -62,22 +64,26 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AggregationConfigTypeDef",
     "AmplitudeConnectorProfileCredentialsTypeDef",
     "AmplitudeSourcePropertiesTypeDef",
     "ApiKeyCredentialsTypeDef",
     "AuthParameterTypeDef",
     "BasicAuthCredentialsTypeDef",
+    "CancelFlowExecutionsRequestRequestTypeDef",
+    "CancelFlowExecutionsResponseTypeDef",
     "ConnectorRuntimeSettingTypeDef",
+    "DataTransferApiTypeDef",
     "ConnectorDetailTypeDef",
     "DestinationFieldPropertiesTypeDef",
     "SourceFieldPropertiesTypeDef",
     "ConnectorEntityTypeDef",
     "GoogleAnalyticsMetadataTypeDef",
     "HoneycodeMetadataTypeDef",
     "SalesforceMetadataTypeDef",
@@ -105,19 +111,19 @@
     "ServiceNowConnectorProfilePropertiesTypeDef",
     "SlackConnectorProfilePropertiesTypeDef",
     "SnowflakeConnectorProfilePropertiesTypeDef",
     "VeevaConnectorProfilePropertiesTypeDef",
     "ZendeskConnectorProfilePropertiesTypeDef",
     "PrivateConnectionProvisioningStateTypeDef",
     "LambdaConnectorProvisioningConfigTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateConnectorProfileResponseTypeDef",
+    "CreateFlowResponseTypeDef",
     "CustomAuthCredentialsTypeDef",
     "ErrorHandlingConfigTypeDef",
     "OAuth2PropertiesTypeDef",
-    "CustomConnectorSourcePropertiesTypeDef",
     "CustomerProfilesDestinationPropertiesTypeDef",
     "DatadogSourcePropertiesTypeDef",
     "DeleteConnectorProfileRequestRequestTypeDef",
     "DeleteFlowRequestRequestTypeDef",
     "DescribeConnectorEntityRequestRequestTypeDef",
     "DescribeConnectorProfilesRequestRequestTypeDef",
     "DescribeConnectorRequestRequestTypeDef",
@@ -132,60 +138,61 @@
     "GoogleAnalyticsSourcePropertiesTypeDef",
     "IncrementalPullConfigTypeDef",
     "InforNexusSourcePropertiesTypeDef",
     "ListConnectorEntitiesRequestRequestTypeDef",
     "ListConnectorsRequestRequestTypeDef",
     "ListFlowsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "MarketoSourcePropertiesTypeDef",
     "RegistrationOutputTypeDef",
     "OAuth2CustomParameterTypeDef",
     "OAuthPropertiesTypeDef",
     "PardotSourcePropertiesTypeDef",
     "PrefixConfigTypeDef",
+    "RegisterConnectorResponseTypeDef",
+    "ResetConnectorMetadataCacheRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "S3InputFormatConfigTypeDef",
     "SuccessResponseHandlingConfigTypeDef",
     "SAPODataSourcePropertiesTypeDef",
     "SalesforceSourcePropertiesTypeDef",
     "ScheduledTriggerPropertiesTypeDef",
     "ServiceNowSourcePropertiesTypeDef",
     "SingularSourcePropertiesTypeDef",
     "SlackSourcePropertiesTypeDef",
     "TrendmicroSourcePropertiesTypeDef",
     "VeevaSourcePropertiesTypeDef",
     "ZendeskSourcePropertiesTypeDef",
     "StartFlowRequestRequestTypeDef",
+    "StartFlowResponseTypeDef",
     "StopFlowRequestRequestTypeDef",
+    "StopFlowResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UnregisterConnectorRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateConnectorProfileResponseTypeDef",
+    "UpdateConnectorRegistrationResponseTypeDef",
+    "UpdateFlowResponseTypeDef",
     "CustomAuthConfigTypeDef",
+    "CustomConnectorSourcePropertiesTypeDef",
+    "ListConnectorsResponseTypeDef",
+    "ListConnectorEntitiesResponseTypeDef",
     "ConnectorMetadataTypeDef",
     "GoogleAnalyticsConnectorProfileCredentialsTypeDef",
     "HoneycodeConnectorProfileCredentialsTypeDef",
     "MarketoConnectorProfileCredentialsTypeDef",
     "OAuth2CredentialsTypeDef",
     "OAuthCredentialsTypeDef",
     "PardotConnectorProfileCredentialsTypeDef",
     "SalesforceConnectorProfileCredentialsTypeDef",
     "SlackConnectorProfileCredentialsTypeDef",
     "ZendeskConnectorProfileCredentialsTypeDef",
     "TaskTypeDef",
     "ConnectorProvisioningConfigTypeDef",
-    "CreateConnectorProfileResponseTypeDef",
-    "CreateFlowResponseTypeDef",
-    "ListConnectorEntitiesResponseTypeDef",
-    "ListConnectorsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RegisterConnectorResponseTypeDef",
-    "StartFlowResponseTypeDef",
-    "StopFlowResponseTypeDef",
-    "UpdateConnectorProfileResponseTypeDef",
-    "UpdateConnectorRegistrationResponseTypeDef",
-    "UpdateFlowResponseTypeDef",
     "CustomConnectorDestinationPropertiesTypeDef",
     "EventBridgeDestinationPropertiesTypeDef",
     "HoneycodeDestinationPropertiesTypeDef",
     "MarketoDestinationPropertiesTypeDef",
     "RedshiftDestinationPropertiesTypeDef",
     "SalesforceDestinationPropertiesTypeDef",
     "SnowflakeDestinationPropertiesTypeDef",
@@ -270,19 +277,21 @@
     "_OptionalApiKeyCredentialsTypeDef",
     {
         "apiSecretKey": str,
     },
     total=False,
 )
 
+
 class ApiKeyCredentialsTypeDef(
     _RequiredApiKeyCredentialsTypeDef, _OptionalApiKeyCredentialsTypeDef
 ):
     pass
 
+
 AuthParameterTypeDef = TypedDict(
     "AuthParameterTypeDef",
     {
         "key": str,
         "isRequired": bool,
         "label": str,
         "description": str,
@@ -296,42 +305,82 @@
     "BasicAuthCredentialsTypeDef",
     {
         "username": str,
         "password": str,
     },
 )
 
+_RequiredCancelFlowExecutionsRequestRequestTypeDef = TypedDict(
+    "_RequiredCancelFlowExecutionsRequestRequestTypeDef",
+    {
+        "flowName": str,
+    },
+)
+_OptionalCancelFlowExecutionsRequestRequestTypeDef = TypedDict(
+    "_OptionalCancelFlowExecutionsRequestRequestTypeDef",
+    {
+        "executionIds": Sequence[str],
+    },
+    total=False,
+)
+
+
+class CancelFlowExecutionsRequestRequestTypeDef(
+    _RequiredCancelFlowExecutionsRequestRequestTypeDef,
+    _OptionalCancelFlowExecutionsRequestRequestTypeDef,
+):
+    pass
+
+
+CancelFlowExecutionsResponseTypeDef = TypedDict(
+    "CancelFlowExecutionsResponseTypeDef",
+    {
+        "invalidExecutions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ConnectorRuntimeSettingTypeDef = TypedDict(
     "ConnectorRuntimeSettingTypeDef",
     {
         "key": str,
         "dataType": str,
         "isRequired": bool,
         "label": str,
         "description": str,
         "scope": str,
         "connectorSuppliedValueOptions": List[str],
     },
     total=False,
 )
 
+DataTransferApiTypeDef = TypedDict(
+    "DataTransferApiTypeDef",
+    {
+        "Name": str,
+        "Type": DataTransferApiTypeType,
+    },
+    total=False,
+)
+
 ConnectorDetailTypeDef = TypedDict(
     "ConnectorDetailTypeDef",
     {
         "connectorDescription": str,
         "connectorName": str,
         "connectorOwner": str,
         "connectorVersion": str,
         "applicationType": str,
         "connectorType": ConnectorTypeType,
         "connectorLabel": str,
         "registeredAt": datetime,
         "registeredBy": str,
         "connectorProvisioningType": Literal["LAMBDA"],
         "connectorModes": List[str],
+        "supportedDataTransferTypes": List[SupportedDataTransferTypeType],
     },
     total=False,
 )
 
 DestinationFieldPropertiesTypeDef = TypedDict(
     "DestinationFieldPropertiesTypeDef",
     {
@@ -366,17 +415,19 @@
     {
         "label": str,
         "hasNestedEntities": bool,
     },
     total=False,
 )
 
+
 class ConnectorEntityTypeDef(_RequiredConnectorEntityTypeDef, _OptionalConnectorEntityTypeDef):
     pass
 
+
 GoogleAnalyticsMetadataTypeDef = TypedDict(
     "GoogleAnalyticsMetadataTypeDef",
     {
         "oAuthScopes": List[str],
     },
     total=False,
 )
@@ -390,14 +441,15 @@
 )
 
 SalesforceMetadataTypeDef = TypedDict(
     "SalesforceMetadataTypeDef",
     {
         "oAuthScopes": List[str],
         "dataTransferApis": List[SalesforceDataTransferApiType],
+        "oauth2GrantTypesSupported": List[OAuth2GrantTypeType],
     },
     total=False,
 )
 
 SlackMetadataTypeDef = TypedDict(
     "SlackMetadataTypeDef",
     {
@@ -582,25 +634,28 @@
         "clusterIdentifier": str,
         "workgroupName": str,
         "databaseName": str,
     },
     total=False,
 )
 
+
 class RedshiftConnectorProfilePropertiesTypeDef(
     _RequiredRedshiftConnectorProfilePropertiesTypeDef,
     _OptionalRedshiftConnectorProfilePropertiesTypeDef,
 ):
     pass
 
+
 SalesforceConnectorProfilePropertiesTypeDef = TypedDict(
     "SalesforceConnectorProfilePropertiesTypeDef",
     {
         "instanceUrl": str,
         "isSandboxEnvironment": bool,
+        "usePrivateLinkForMetadataAndAuthorization": bool,
     },
     total=False,
 )
 
 ServiceNowConnectorProfilePropertiesTypeDef = TypedDict(
     "ServiceNowConnectorProfilePropertiesTypeDef",
     {
@@ -630,20 +685,22 @@
         "privateLinkServiceName": str,
         "accountName": str,
         "region": str,
     },
     total=False,
 )
 
+
 class SnowflakeConnectorProfilePropertiesTypeDef(
     _RequiredSnowflakeConnectorProfilePropertiesTypeDef,
     _OptionalSnowflakeConnectorProfilePropertiesTypeDef,
 ):
     pass
 
+
 VeevaConnectorProfilePropertiesTypeDef = TypedDict(
     "VeevaConnectorProfilePropertiesTypeDef",
     {
         "instanceUrl": str,
     },
 )
 
@@ -667,22 +724,28 @@
 LambdaConnectorProvisioningConfigTypeDef = TypedDict(
     "LambdaConnectorProvisioningConfigTypeDef",
     {
         "lambdaArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateConnectorProfileResponseTypeDef = TypedDict(
+    "CreateConnectorProfileResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "connectorProfileArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFlowResponseTypeDef = TypedDict(
+    "CreateFlowResponseTypeDef",
+    {
+        "flowArn": str,
+        "flowStatus": FlowStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCustomAuthCredentialsTypeDef = TypedDict(
     "_RequiredCustomAuthCredentialsTypeDef",
     {
         "customAuthenticationType": str,
@@ -692,19 +755,21 @@
     "_OptionalCustomAuthCredentialsTypeDef",
     {
         "credentialsMap": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CustomAuthCredentialsTypeDef(
     _RequiredCustomAuthCredentialsTypeDef, _OptionalCustomAuthCredentialsTypeDef
 ):
     pass
 
+
 ErrorHandlingConfigTypeDef = TypedDict(
     "ErrorHandlingConfigTypeDef",
     {
         "failOnFirstDestinationError": bool,
         "bucketPrefix": str,
         "bucketName": str,
     },
@@ -722,35 +787,18 @@
     "_OptionalOAuth2PropertiesTypeDef",
     {
         "tokenUrlCustomProperties": Mapping[str, str],
     },
     total=False,
 )
 
+
 class OAuth2PropertiesTypeDef(_RequiredOAuth2PropertiesTypeDef, _OptionalOAuth2PropertiesTypeDef):
     pass
 
-_RequiredCustomConnectorSourcePropertiesTypeDef = TypedDict(
-    "_RequiredCustomConnectorSourcePropertiesTypeDef",
-    {
-        "entityName": str,
-    },
-)
-_OptionalCustomConnectorSourcePropertiesTypeDef = TypedDict(
-    "_OptionalCustomConnectorSourcePropertiesTypeDef",
-    {
-        "customProperties": Mapping[str, str],
-    },
-    total=False,
-)
-
-class CustomConnectorSourcePropertiesTypeDef(
-    _RequiredCustomConnectorSourcePropertiesTypeDef, _OptionalCustomConnectorSourcePropertiesTypeDef
-):
-    pass
 
 _RequiredCustomerProfilesDestinationPropertiesTypeDef = TypedDict(
     "_RequiredCustomerProfilesDestinationPropertiesTypeDef",
     {
         "domainName": str,
     },
 )
@@ -758,20 +806,22 @@
     "_OptionalCustomerProfilesDestinationPropertiesTypeDef",
     {
         "objectTypeName": str,
     },
     total=False,
 )
 
+
 class CustomerProfilesDestinationPropertiesTypeDef(
     _RequiredCustomerProfilesDestinationPropertiesTypeDef,
     _OptionalCustomerProfilesDestinationPropertiesTypeDef,
 ):
     pass
 
+
 DatadogSourcePropertiesTypeDef = TypedDict(
     "DatadogSourcePropertiesTypeDef",
     {
         "object": str,
     },
 )
 
@@ -785,39 +835,43 @@
     "_OptionalDeleteConnectorProfileRequestRequestTypeDef",
     {
         "forceDelete": bool,
     },
     total=False,
 )
 
+
 class DeleteConnectorProfileRequestRequestTypeDef(
     _RequiredDeleteConnectorProfileRequestRequestTypeDef,
     _OptionalDeleteConnectorProfileRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredDeleteFlowRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteFlowRequestRequestTypeDef",
     {
         "flowName": str,
     },
 )
 _OptionalDeleteFlowRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteFlowRequestRequestTypeDef",
     {
         "forceDelete": bool,
     },
     total=False,
 )
 
+
 class DeleteFlowRequestRequestTypeDef(
     _RequiredDeleteFlowRequestRequestTypeDef, _OptionalDeleteFlowRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredDescribeConnectorEntityRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeConnectorEntityRequestRequestTypeDef",
     {
         "connectorEntityName": str,
     },
 )
 _OptionalDescribeConnectorEntityRequestRequestTypeDef = TypedDict(
@@ -826,20 +880,22 @@
         "connectorType": ConnectorTypeType,
         "connectorProfileName": str,
         "apiVersion": str,
     },
     total=False,
 )
 
+
 class DescribeConnectorEntityRequestRequestTypeDef(
     _RequiredDescribeConnectorEntityRequestRequestTypeDef,
     _OptionalDescribeConnectorEntityRequestRequestTypeDef,
 ):
     pass
 
+
 DescribeConnectorProfilesRequestRequestTypeDef = TypedDict(
     "DescribeConnectorProfilesRequestRequestTypeDef",
     {
         "connectorProfileNames": Sequence[str],
         "connectorType": ConnectorTypeType,
         "connectorLabel": str,
         "maxResults": int,
@@ -858,19 +914,21 @@
     "_OptionalDescribeConnectorRequestRequestTypeDef",
     {
         "connectorLabel": str,
     },
     total=False,
 )
 
+
 class DescribeConnectorRequestRequestTypeDef(
     _RequiredDescribeConnectorRequestRequestTypeDef, _OptionalDescribeConnectorRequestRequestTypeDef
 ):
     pass
 
+
 DescribeConnectorsRequestRequestTypeDef = TypedDict(
     "DescribeConnectorsRequestRequestTypeDef",
     {
         "connectorTypes": Sequence[ConnectorTypeType],
         "maxResults": int,
         "nextToken": str,
     },
@@ -888,20 +946,22 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class DescribeFlowExecutionRecordsRequestRequestTypeDef(
     _RequiredDescribeFlowExecutionRecordsRequestRequestTypeDef,
     _OptionalDescribeFlowExecutionRecordsRequestRequestTypeDef,
 ):
     pass
 
+
 DescribeFlowRequestRequestTypeDef = TypedDict(
     "DescribeFlowRequestRequestTypeDef",
     {
         "flowName": str,
     },
 )
 
@@ -1005,14 +1065,22 @@
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
 MarketoSourcePropertiesTypeDef = TypedDict(
     "MarketoSourcePropertiesTypeDef",
     {
         "object": str,
     },
 )
 
@@ -1062,14 +1130,45 @@
         "prefixType": PrefixTypeType,
         "prefixFormat": PrefixFormatType,
         "pathPrefixHierarchy": Sequence[PathPrefixType],
     },
     total=False,
 )
 
+RegisterConnectorResponseTypeDef = TypedDict(
+    "RegisterConnectorResponseTypeDef",
+    {
+        "connectorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ResetConnectorMetadataCacheRequestRequestTypeDef = TypedDict(
+    "ResetConnectorMetadataCacheRequestRequestTypeDef",
+    {
+        "connectorProfileName": str,
+        "connectorType": ConnectorTypeType,
+        "connectorEntityName": str,
+        "entitiesPath": str,
+        "apiVersion": str,
+    },
+    total=False,
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
 S3InputFormatConfigTypeDef = TypedDict(
     "S3InputFormatConfigTypeDef",
     {
         "s3InputFileType": S3InputFileTypeType,
     },
     total=False,
 )
@@ -1103,19 +1202,21 @@
         "enableDynamicFieldUpdate": bool,
         "includeDeletedRecords": bool,
         "dataTransferApi": SalesforceDataTransferApiType,
     },
     total=False,
 )
 
+
 class SalesforceSourcePropertiesTypeDef(
     _RequiredSalesforceSourcePropertiesTypeDef, _OptionalSalesforceSourcePropertiesTypeDef
 ):
     pass
 
+
 _RequiredScheduledTriggerPropertiesTypeDef = TypedDict(
     "_RequiredScheduledTriggerPropertiesTypeDef",
     {
         "scheduleExpression": str,
     },
 )
 _OptionalScheduledTriggerPropertiesTypeDef = TypedDict(
@@ -1128,19 +1229,21 @@
         "scheduleOffset": int,
         "firstExecutionFrom": Union[datetime, str],
         "flowErrorDeactivationThreshold": int,
     },
     total=False,
 )
 
+
 class ScheduledTriggerPropertiesTypeDef(
     _RequiredScheduledTriggerPropertiesTypeDef, _OptionalScheduledTriggerPropertiesTypeDef
 ):
     pass
 
+
 ServiceNowSourcePropertiesTypeDef = TypedDict(
     "ServiceNowSourcePropertiesTypeDef",
     {
         "object": str,
     },
 )
 
@@ -1178,40 +1281,75 @@
         "includeSourceFiles": bool,
         "includeRenditions": bool,
         "includeAllVersions": bool,
     },
     total=False,
 )
 
+
 class VeevaSourcePropertiesTypeDef(
     _RequiredVeevaSourcePropertiesTypeDef, _OptionalVeevaSourcePropertiesTypeDef
 ):
     pass
 
+
 ZendeskSourcePropertiesTypeDef = TypedDict(
     "ZendeskSourcePropertiesTypeDef",
     {
         "object": str,
     },
 )
 
-StartFlowRequestRequestTypeDef = TypedDict(
-    "StartFlowRequestRequestTypeDef",
+_RequiredStartFlowRequestRequestTypeDef = TypedDict(
+    "_RequiredStartFlowRequestRequestTypeDef",
     {
         "flowName": str,
     },
 )
+_OptionalStartFlowRequestRequestTypeDef = TypedDict(
+    "_OptionalStartFlowRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+
+class StartFlowRequestRequestTypeDef(
+    _RequiredStartFlowRequestRequestTypeDef, _OptionalStartFlowRequestRequestTypeDef
+):
+    pass
+
+
+StartFlowResponseTypeDef = TypedDict(
+    "StartFlowResponseTypeDef",
+    {
+        "flowArn": str,
+        "flowStatus": FlowStatusType,
+        "executionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 StopFlowRequestRequestTypeDef = TypedDict(
     "StopFlowRequestRequestTypeDef",
     {
         "flowName": str,
     },
 )
 
+StopFlowResponseTypeDef = TypedDict(
+    "StopFlowResponseTypeDef",
+    {
+        "flowArn": str,
+        "flowStatus": FlowStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -1226,37 +1364,103 @@
     "_OptionalUnregisterConnectorRequestRequestTypeDef",
     {
         "forceDelete": bool,
     },
     total=False,
 )
 
+
 class UnregisterConnectorRequestRequestTypeDef(
     _RequiredUnregisterConnectorRequestRequestTypeDef,
     _OptionalUnregisterConnectorRequestRequestTypeDef,
 ):
     pass
 
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateConnectorProfileResponseTypeDef = TypedDict(
+    "UpdateConnectorProfileResponseTypeDef",
+    {
+        "connectorProfileArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateConnectorRegistrationResponseTypeDef = TypedDict(
+    "UpdateConnectorRegistrationResponseTypeDef",
+    {
+        "connectorArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateFlowResponseTypeDef = TypedDict(
+    "UpdateFlowResponseTypeDef",
+    {
+        "flowStatus": FlowStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomAuthConfigTypeDef = TypedDict(
     "CustomAuthConfigTypeDef",
     {
         "customAuthenticationType": str,
         "authParameters": List[AuthParameterTypeDef],
     },
     total=False,
 )
 
+_RequiredCustomConnectorSourcePropertiesTypeDef = TypedDict(
+    "_RequiredCustomConnectorSourcePropertiesTypeDef",
+    {
+        "entityName": str,
+    },
+)
+_OptionalCustomConnectorSourcePropertiesTypeDef = TypedDict(
+    "_OptionalCustomConnectorSourcePropertiesTypeDef",
+    {
+        "customProperties": Mapping[str, str],
+        "dataTransferApi": DataTransferApiTypeDef,
+    },
+    total=False,
+)
+
+
+class CustomConnectorSourcePropertiesTypeDef(
+    _RequiredCustomConnectorSourcePropertiesTypeDef, _OptionalCustomConnectorSourcePropertiesTypeDef
+):
+    pass
+
+
+ListConnectorsResponseTypeDef = TypedDict(
+    "ListConnectorsResponseTypeDef",
+    {
+        "connectors": List[ConnectorDetailTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListConnectorEntitiesResponseTypeDef = TypedDict(
+    "ListConnectorEntitiesResponseTypeDef",
+    {
+        "connectorEntityMap": Dict[str, List[ConnectorEntityTypeDef]],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ConnectorMetadataTypeDef = TypedDict(
     "ConnectorMetadataTypeDef",
     {
         "Amplitude": Dict[str, Any],
         "Datadog": Dict[str, Any],
         "Dynatrace": Dict[str, Any],
         "GoogleAnalytics": GoogleAnalyticsMetadataTypeDef,
@@ -1295,20 +1499,22 @@
         "accessToken": str,
         "refreshToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
     },
     total=False,
 )
 
+
 class GoogleAnalyticsConnectorProfileCredentialsTypeDef(
     _RequiredGoogleAnalyticsConnectorProfileCredentialsTypeDef,
     _OptionalGoogleAnalyticsConnectorProfileCredentialsTypeDef,
 ):
     pass
 
+
 HoneycodeConnectorProfileCredentialsTypeDef = TypedDict(
     "HoneycodeConnectorProfileCredentialsTypeDef",
     {
         "accessToken": str,
         "refreshToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
     },
@@ -1327,20 +1533,22 @@
     {
         "accessToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
     },
     total=False,
 )
 
+
 class MarketoConnectorProfileCredentialsTypeDef(
     _RequiredMarketoConnectorProfileCredentialsTypeDef,
     _OptionalMarketoConnectorProfileCredentialsTypeDef,
 ):
     pass
 
+
 OAuth2CredentialsTypeDef = TypedDict(
     "OAuth2CredentialsTypeDef",
     {
         "clientId": str,
         "clientSecret": str,
         "accessToken": str,
         "refreshToken": str,
@@ -1362,17 +1570,19 @@
         "accessToken": str,
         "refreshToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
     },
     total=False,
 )
 
+
 class OAuthCredentialsTypeDef(_RequiredOAuthCredentialsTypeDef, _OptionalOAuthCredentialsTypeDef):
     pass
 
+
 PardotConnectorProfileCredentialsTypeDef = TypedDict(
     "PardotConnectorProfileCredentialsTypeDef",
     {
         "accessToken": str,
         "refreshToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
         "clientCredentialsArn": str,
@@ -1383,14 +1593,16 @@
 SalesforceConnectorProfileCredentialsTypeDef = TypedDict(
     "SalesforceConnectorProfileCredentialsTypeDef",
     {
         "accessToken": str,
         "refreshToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
         "clientCredentialsArn": str,
+        "oAuth2GrantType": OAuth2GrantTypeType,
+        "jwtToken": str,
     },
     total=False,
 )
 
 _RequiredSlackConnectorProfileCredentialsTypeDef = TypedDict(
     "_RequiredSlackConnectorProfileCredentialsTypeDef",
     {
@@ -1403,20 +1615,22 @@
     {
         "accessToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
     },
     total=False,
 )
 
+
 class SlackConnectorProfileCredentialsTypeDef(
     _RequiredSlackConnectorProfileCredentialsTypeDef,
     _OptionalSlackConnectorProfileCredentialsTypeDef,
 ):
     pass
 
+
 _RequiredZendeskConnectorProfileCredentialsTypeDef = TypedDict(
     "_RequiredZendeskConnectorProfileCredentialsTypeDef",
     {
         "clientId": str,
         "clientSecret": str,
     },
 )
@@ -1425,20 +1639,22 @@
     {
         "accessToken": str,
         "oAuthRequest": ConnectorOAuthRequestTypeDef,
     },
     total=False,
 )
 
+
 class ZendeskConnectorProfileCredentialsTypeDef(
     _RequiredZendeskConnectorProfileCredentialsTypeDef,
     _OptionalZendeskConnectorProfileCredentialsTypeDef,
 ):
     pass
 
+
 _RequiredTaskTypeDef = TypedDict(
     "_RequiredTaskTypeDef",
     {
         "sourceFields": Sequence[str],
         "taskType": TaskTypeType,
     },
 )
@@ -1448,119 +1664,27 @@
         "connectorOperator": ConnectorOperatorTypeDef,
         "destinationField": str,
         "taskProperties": Mapping[OperatorPropertiesKeysType, str],
     },
     total=False,
 )
 
+
 class TaskTypeDef(_RequiredTaskTypeDef, _OptionalTaskTypeDef):
     pass
 
+
 ConnectorProvisioningConfigTypeDef = TypedDict(
     "ConnectorProvisioningConfigTypeDef",
     {
         "lambda": LambdaConnectorProvisioningConfigTypeDef,
     },
     total=False,
 )
 
-CreateConnectorProfileResponseTypeDef = TypedDict(
-    "CreateConnectorProfileResponseTypeDef",
-    {
-        "connectorProfileArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFlowResponseTypeDef = TypedDict(
-    "CreateFlowResponseTypeDef",
-    {
-        "flowArn": str,
-        "flowStatus": FlowStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConnectorEntitiesResponseTypeDef = TypedDict(
-    "ListConnectorEntitiesResponseTypeDef",
-    {
-        "connectorEntityMap": Dict[str, List[ConnectorEntityTypeDef]],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConnectorsResponseTypeDef = TypedDict(
-    "ListConnectorsResponseTypeDef",
-    {
-        "connectors": List[ConnectorDetailTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterConnectorResponseTypeDef = TypedDict(
-    "RegisterConnectorResponseTypeDef",
-    {
-        "connectorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartFlowResponseTypeDef = TypedDict(
-    "StartFlowResponseTypeDef",
-    {
-        "flowArn": str,
-        "flowStatus": FlowStatusType,
-        "executionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopFlowResponseTypeDef = TypedDict(
-    "StopFlowResponseTypeDef",
-    {
-        "flowArn": str,
-        "flowStatus": FlowStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateConnectorProfileResponseTypeDef = TypedDict(
-    "UpdateConnectorProfileResponseTypeDef",
-    {
-        "connectorProfileArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateConnectorRegistrationResponseTypeDef = TypedDict(
-    "UpdateConnectorRegistrationResponseTypeDef",
-    {
-        "connectorArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFlowResponseTypeDef = TypedDict(
-    "UpdateFlowResponseTypeDef",
-    {
-        "flowStatus": FlowStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCustomConnectorDestinationPropertiesTypeDef = TypedDict(
     "_RequiredCustomConnectorDestinationPropertiesTypeDef",
     {
         "entityName": str,
     },
 )
 _OptionalCustomConnectorDestinationPropertiesTypeDef = TypedDict(
@@ -1570,78 +1694,86 @@
         "writeOperationType": WriteOperationTypeType,
         "idFieldNames": Sequence[str],
         "customProperties": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CustomConnectorDestinationPropertiesTypeDef(
     _RequiredCustomConnectorDestinationPropertiesTypeDef,
     _OptionalCustomConnectorDestinationPropertiesTypeDef,
 ):
     pass
 
+
 _RequiredEventBridgeDestinationPropertiesTypeDef = TypedDict(
     "_RequiredEventBridgeDestinationPropertiesTypeDef",
     {
         "object": str,
     },
 )
 _OptionalEventBridgeDestinationPropertiesTypeDef = TypedDict(
     "_OptionalEventBridgeDestinationPropertiesTypeDef",
     {
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
     },
     total=False,
 )
 
+
 class EventBridgeDestinationPropertiesTypeDef(
     _RequiredEventBridgeDestinationPropertiesTypeDef,
     _OptionalEventBridgeDestinationPropertiesTypeDef,
 ):
     pass
 
+
 _RequiredHoneycodeDestinationPropertiesTypeDef = TypedDict(
     "_RequiredHoneycodeDestinationPropertiesTypeDef",
     {
         "object": str,
     },
 )
 _OptionalHoneycodeDestinationPropertiesTypeDef = TypedDict(
     "_OptionalHoneycodeDestinationPropertiesTypeDef",
     {
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
     },
     total=False,
 )
 
+
 class HoneycodeDestinationPropertiesTypeDef(
     _RequiredHoneycodeDestinationPropertiesTypeDef, _OptionalHoneycodeDestinationPropertiesTypeDef
 ):
     pass
 
+
 _RequiredMarketoDestinationPropertiesTypeDef = TypedDict(
     "_RequiredMarketoDestinationPropertiesTypeDef",
     {
         "object": str,
     },
 )
 _OptionalMarketoDestinationPropertiesTypeDef = TypedDict(
     "_OptionalMarketoDestinationPropertiesTypeDef",
     {
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
     },
     total=False,
 )
 
+
 class MarketoDestinationPropertiesTypeDef(
     _RequiredMarketoDestinationPropertiesTypeDef, _OptionalMarketoDestinationPropertiesTypeDef
 ):
     pass
 
+
 _RequiredRedshiftDestinationPropertiesTypeDef = TypedDict(
     "_RequiredRedshiftDestinationPropertiesTypeDef",
     {
         "object": str,
         "intermediateBucketName": str,
     },
 )
@@ -1650,19 +1782,21 @@
     {
         "bucketPrefix": str,
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
     },
     total=False,
 )
 
+
 class RedshiftDestinationPropertiesTypeDef(
     _RequiredRedshiftDestinationPropertiesTypeDef, _OptionalRedshiftDestinationPropertiesTypeDef
 ):
     pass
 
+
 _RequiredSalesforceDestinationPropertiesTypeDef = TypedDict(
     "_RequiredSalesforceDestinationPropertiesTypeDef",
     {
         "object": str,
     },
 )
 _OptionalSalesforceDestinationPropertiesTypeDef = TypedDict(
@@ -1672,19 +1806,21 @@
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
         "writeOperationType": WriteOperationTypeType,
         "dataTransferApi": SalesforceDataTransferApiType,
     },
     total=False,
 )
 
+
 class SalesforceDestinationPropertiesTypeDef(
     _RequiredSalesforceDestinationPropertiesTypeDef, _OptionalSalesforceDestinationPropertiesTypeDef
 ):
     pass
 
+
 _RequiredSnowflakeDestinationPropertiesTypeDef = TypedDict(
     "_RequiredSnowflakeDestinationPropertiesTypeDef",
     {
         "object": str,
         "intermediateBucketName": str,
     },
 )
@@ -1693,19 +1829,21 @@
     {
         "bucketPrefix": str,
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
     },
     total=False,
 )
 
+
 class SnowflakeDestinationPropertiesTypeDef(
     _RequiredSnowflakeDestinationPropertiesTypeDef, _OptionalSnowflakeDestinationPropertiesTypeDef
 ):
     pass
 
+
 _RequiredZendeskDestinationPropertiesTypeDef = TypedDict(
     "_RequiredZendeskDestinationPropertiesTypeDef",
     {
         "object": str,
     },
 )
 _OptionalZendeskDestinationPropertiesTypeDef = TypedDict(
@@ -1714,19 +1852,21 @@
         "idFieldNames": Sequence[str],
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
         "writeOperationType": WriteOperationTypeType,
     },
     total=False,
 )
 
+
 class ZendeskDestinationPropertiesTypeDef(
     _RequiredZendeskDestinationPropertiesTypeDef, _OptionalZendeskDestinationPropertiesTypeDef
 ):
     pass
 
+
 CustomConnectorProfilePropertiesTypeDef = TypedDict(
     "CustomConnectorProfilePropertiesTypeDef",
     {
         "profileProperties": Mapping[str, str],
         "oAuth2Properties": OAuth2PropertiesTypeDef,
     },
     total=False,
@@ -1780,17 +1920,19 @@
         "supportedDateFormat": str,
         "fieldValueRange": RangeTypeDef,
         "fieldLengthRange": RangeTypeDef,
     },
     total=False,
 )
 
+
 class FieldTypeDetailsTypeDef(_RequiredFieldTypeDetailsTypeDef, _OptionalFieldTypeDetailsTypeDef):
     pass
 
+
 MetadataCatalogConfigTypeDef = TypedDict(
     "MetadataCatalogConfigTypeDef",
     {
         "glueDataCatalog": GlueDataCatalogConfigTypeDef,
     },
     total=False,
 )
@@ -1833,20 +1975,22 @@
         "logonLanguage": str,
         "privateLinkServiceName": str,
         "oAuthProperties": OAuthPropertiesTypeDef,
     },
     total=False,
 )
 
+
 class SAPODataConnectorProfilePropertiesTypeDef(
     _RequiredSAPODataConnectorProfilePropertiesTypeDef,
     _OptionalSAPODataConnectorProfilePropertiesTypeDef,
 ):
     pass
 
+
 S3OutputFormatConfigTypeDef = TypedDict(
     "S3OutputFormatConfigTypeDef",
     {
         "fileType": FileTypeType,
         "prefixConfig": PrefixConfigTypeDef,
         "aggregationConfig": AggregationConfigTypeDef,
         "preserveSourceDataTyping": bool,
@@ -1865,19 +2009,21 @@
     {
         "fileType": FileTypeType,
         "aggregationConfig": AggregationConfigTypeDef,
     },
     total=False,
 )
 
+
 class UpsolverS3OutputFormatConfigTypeDef(
     _RequiredUpsolverS3OutputFormatConfigTypeDef, _OptionalUpsolverS3OutputFormatConfigTypeDef
 ):
     pass
 
+
 _RequiredS3SourcePropertiesTypeDef = TypedDict(
     "_RequiredS3SourcePropertiesTypeDef",
     {
         "bucketName": str,
     },
 )
 _OptionalS3SourcePropertiesTypeDef = TypedDict(
@@ -1885,19 +2031,21 @@
     {
         "bucketPrefix": str,
         "s3InputFormatConfig": S3InputFormatConfigTypeDef,
     },
     total=False,
 )
 
+
 class S3SourcePropertiesTypeDef(
     _RequiredS3SourcePropertiesTypeDef, _OptionalS3SourcePropertiesTypeDef
 ):
     pass
 
+
 _RequiredSAPODataDestinationPropertiesTypeDef = TypedDict(
     "_RequiredSAPODataDestinationPropertiesTypeDef",
     {
         "objectPath": str,
     },
 )
 _OptionalSAPODataDestinationPropertiesTypeDef = TypedDict(
@@ -1907,19 +2055,21 @@
         "idFieldNames": Sequence[str],
         "errorHandlingConfig": ErrorHandlingConfigTypeDef,
         "writeOperationType": WriteOperationTypeType,
     },
     total=False,
 )
 
+
 class SAPODataDestinationPropertiesTypeDef(
     _RequiredSAPODataDestinationPropertiesTypeDef, _OptionalSAPODataDestinationPropertiesTypeDef
 ):
     pass
 
+
 TriggerPropertiesTypeDef = TypedDict(
     "TriggerPropertiesTypeDef",
     {
         "Scheduled": ScheduledTriggerPropertiesTypeDef,
     },
     total=False,
 )
@@ -1937,20 +2087,22 @@
         "oauth2": OAuth2CredentialsTypeDef,
         "apiKey": ApiKeyCredentialsTypeDef,
         "custom": CustomAuthCredentialsTypeDef,
     },
     total=False,
 )
 
+
 class CustomConnectorProfileCredentialsTypeDef(
     _RequiredCustomConnectorProfileCredentialsTypeDef,
     _OptionalCustomConnectorProfileCredentialsTypeDef,
 ):
     pass
 
+
 SAPODataConnectorProfileCredentialsTypeDef = TypedDict(
     "SAPODataConnectorProfileCredentialsTypeDef",
     {
         "basicAuthCredentials": BasicAuthCredentialsTypeDef,
         "oAuthCredentials": OAuthCredentialsTypeDef,
     },
     total=False,
@@ -1959,14 +2111,15 @@
 RegisterConnectorRequestRequestTypeDef = TypedDict(
     "RegisterConnectorRequestRequestTypeDef",
     {
         "connectorLabel": str,
         "description": str,
         "connectorProvisioningType": Literal["LAMBDA"],
         "connectorProvisioningConfig": ConnectorProvisioningConfigTypeDef,
+        "clientToken": str,
     },
     total=False,
 )
 
 _RequiredUpdateConnectorRegistrationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateConnectorRegistrationRequestRequestTypeDef",
     {
@@ -1974,30 +2127,33 @@
     },
 )
 _OptionalUpdateConnectorRegistrationRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateConnectorRegistrationRequestRequestTypeDef",
     {
         "description": str,
         "connectorProvisioningConfig": ConnectorProvisioningConfigTypeDef,
+        "clientToken": str,
     },
     total=False,
 )
 
+
 class UpdateConnectorRegistrationRequestRequestTypeDef(
     _RequiredUpdateConnectorRegistrationRequestRequestTypeDef,
     _OptionalUpdateConnectorRegistrationRequestRequestTypeDef,
 ):
     pass
 
+
 ListFlowsResponseTypeDef = TypedDict(
     "ListFlowsResponseTypeDef",
     {
         "flows": List[FlowDefinitionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SupportedFieldTypeDetailsTypeDef = TypedDict(
     "SupportedFieldTypeDetailsTypeDef",
     {
         "v1": FieldTypeDetailsTypeDef,
@@ -2069,19 +2225,21 @@
     {
         "bucketPrefix": str,
         "s3OutputFormatConfig": S3OutputFormatConfigTypeDef,
     },
     total=False,
 )
 
+
 class S3DestinationPropertiesTypeDef(
     _RequiredS3DestinationPropertiesTypeDef, _OptionalS3DestinationPropertiesTypeDef
 ):
     pass
 
+
 _RequiredUpsolverDestinationPropertiesTypeDef = TypedDict(
     "_RequiredUpsolverDestinationPropertiesTypeDef",
     {
         "bucketName": str,
         "s3OutputFormatConfig": UpsolverS3OutputFormatConfigTypeDef,
     },
 )
@@ -2089,19 +2247,21 @@
     "_OptionalUpsolverDestinationPropertiesTypeDef",
     {
         "bucketPrefix": str,
     },
     total=False,
 )
 
+
 class UpsolverDestinationPropertiesTypeDef(
     _RequiredUpsolverDestinationPropertiesTypeDef, _OptionalUpsolverDestinationPropertiesTypeDef
 ):
     pass
 
+
 SourceConnectorPropertiesTypeDef = TypedDict(
     "SourceConnectorPropertiesTypeDef",
     {
         "Amplitude": AmplitudeSourcePropertiesTypeDef,
         "Datadog": DatadogSourcePropertiesTypeDef,
         "Dynatrace": DynatraceSourcePropertiesTypeDef,
         "GoogleAnalytics": GoogleAnalyticsSourcePropertiesTypeDef,
@@ -2132,17 +2292,19 @@
     "_OptionalTriggerConfigTypeDef",
     {
         "triggerProperties": TriggerPropertiesTypeDef,
     },
     total=False,
 )
 
+
 class TriggerConfigTypeDef(_RequiredTriggerConfigTypeDef, _OptionalTriggerConfigTypeDef):
     pass
 
+
 ConnectorProfileCredentialsTypeDef = TypedDict(
     "ConnectorProfileCredentialsTypeDef",
     {
         "Amplitude": AmplitudeConnectorProfileCredentialsTypeDef,
         "Datadog": DatadogConnectorProfileCredentialsTypeDef,
         "Dynatrace": DynatraceConnectorProfileCredentialsTypeDef,
         "GoogleAnalytics": GoogleAnalyticsConnectorProfileCredentialsTypeDef,
@@ -2184,25 +2346,27 @@
         "sourceProperties": SourceFieldPropertiesTypeDef,
         "destinationProperties": DestinationFieldPropertiesTypeDef,
         "customProperties": Dict[str, str],
     },
     total=False,
 )
 
+
 class ConnectorEntityFieldTypeDef(
     _RequiredConnectorEntityFieldTypeDef, _OptionalConnectorEntityFieldTypeDef
 ):
     pass
 
+
 DescribeFlowExecutionRecordsResponseTypeDef = TypedDict(
     "DescribeFlowExecutionRecordsResponseTypeDef",
     {
         "flowExecutions": List[ExecutionRecordTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectorConfigurationTypeDef = TypedDict(
     "ConnectorConfigurationTypeDef",
     {
         "canUseAsSource": bool,
@@ -2227,14 +2391,16 @@
         "supportedOperators": List[OperatorsType],
         "supportedWriteOperations": List[WriteOperationTypeType],
         "connectorProvisioningType": Literal["LAMBDA"],
         "connectorProvisioningConfig": ConnectorProvisioningConfigTypeDef,
         "logoURL": str,
         "registeredAt": datetime,
         "registeredBy": str,
+        "supportedDataTransferTypes": List[SupportedDataTransferTypeType],
+        "supportedDataTransferApis": List[DataTransferApiTypeDef],
     },
     total=False,
 )
 
 ConnectorProfileTypeDef = TypedDict(
     "ConnectorProfileTypeDef",
     {
@@ -2285,68 +2451,72 @@
         "apiVersion": str,
         "connectorProfileName": str,
         "incrementalPullConfig": IncrementalPullConfigTypeDef,
     },
     total=False,
 )
 
+
 class SourceFlowConfigTypeDef(_RequiredSourceFlowConfigTypeDef, _OptionalSourceFlowConfigTypeDef):
     pass
 
+
 _RequiredConnectorProfileConfigTypeDef = TypedDict(
     "_RequiredConnectorProfileConfigTypeDef",
     {
         "connectorProfileProperties": ConnectorProfilePropertiesTypeDef,
     },
 )
 _OptionalConnectorProfileConfigTypeDef = TypedDict(
     "_OptionalConnectorProfileConfigTypeDef",
     {
         "connectorProfileCredentials": ConnectorProfileCredentialsTypeDef,
     },
     total=False,
 )
 
+
 class ConnectorProfileConfigTypeDef(
     _RequiredConnectorProfileConfigTypeDef, _OptionalConnectorProfileConfigTypeDef
 ):
     pass
 
+
 DescribeConnectorEntityResponseTypeDef = TypedDict(
     "DescribeConnectorEntityResponseTypeDef",
     {
         "connectorEntityFields": List[ConnectorEntityFieldTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConnectorResponseTypeDef = TypedDict(
     "DescribeConnectorResponseTypeDef",
     {
         "connectorConfiguration": ConnectorConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConnectorsResponseTypeDef = TypedDict(
     "DescribeConnectorsResponseTypeDef",
     {
         "connectorConfigurations": Dict[ConnectorTypeType, ConnectorConfigurationTypeDef],
         "connectors": List[ConnectorDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConnectorProfilesResponseTypeDef = TypedDict(
     "DescribeConnectorProfilesResponseTypeDef",
     {
         "connectorProfileDetails": List[ConnectorProfileTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDestinationFlowConfigTypeDef = TypedDict(
     "_RequiredDestinationFlowConfigTypeDef",
     {
         "connectorType": ConnectorTypeType,
@@ -2358,51 +2528,71 @@
     {
         "apiVersion": str,
         "connectorProfileName": str,
     },
     total=False,
 )
 
+
 class DestinationFlowConfigTypeDef(
     _RequiredDestinationFlowConfigTypeDef, _OptionalDestinationFlowConfigTypeDef
 ):
     pass
 
+
 _RequiredCreateConnectorProfileRequestRequestTypeDef = TypedDict(
     "_RequiredCreateConnectorProfileRequestRequestTypeDef",
     {
         "connectorProfileName": str,
         "connectorType": ConnectorTypeType,
         "connectionMode": ConnectionModeType,
         "connectorProfileConfig": ConnectorProfileConfigTypeDef,
     },
 )
 _OptionalCreateConnectorProfileRequestRequestTypeDef = TypedDict(
     "_OptionalCreateConnectorProfileRequestRequestTypeDef",
     {
         "kmsArn": str,
         "connectorLabel": str,
+        "clientToken": str,
     },
     total=False,
 )
 
+
 class CreateConnectorProfileRequestRequestTypeDef(
     _RequiredCreateConnectorProfileRequestRequestTypeDef,
     _OptionalCreateConnectorProfileRequestRequestTypeDef,
 ):
     pass
 
-UpdateConnectorProfileRequestRequestTypeDef = TypedDict(
-    "UpdateConnectorProfileRequestRequestTypeDef",
+
+_RequiredUpdateConnectorProfileRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateConnectorProfileRequestRequestTypeDef",
     {
         "connectorProfileName": str,
         "connectionMode": ConnectionModeType,
         "connectorProfileConfig": ConnectorProfileConfigTypeDef,
     },
 )
+_OptionalUpdateConnectorProfileRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateConnectorProfileRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+
+class UpdateConnectorProfileRequestRequestTypeDef(
+    _RequiredUpdateConnectorProfileRequestRequestTypeDef,
+    _OptionalUpdateConnectorProfileRequestRequestTypeDef,
+):
+    pass
+
 
 _RequiredCreateFlowRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFlowRequestRequestTypeDef",
     {
         "flowName": str,
         "triggerConfig": TriggerConfigTypeDef,
         "sourceFlowConfig": SourceFlowConfigTypeDef,
@@ -2413,23 +2603,26 @@
 _OptionalCreateFlowRequestRequestTypeDef = TypedDict(
     "_OptionalCreateFlowRequestRequestTypeDef",
     {
         "description": str,
         "kmsArn": str,
         "tags": Mapping[str, str],
         "metadataCatalogConfig": MetadataCatalogConfigTypeDef,
+        "clientToken": str,
     },
     total=False,
 )
 
+
 class CreateFlowRequestRequestTypeDef(
     _RequiredCreateFlowRequestRequestTypeDef, _OptionalCreateFlowRequestRequestTypeDef
 ):
     pass
 
+
 DescribeFlowResponseTypeDef = TypedDict(
     "DescribeFlowResponseTypeDef",
     {
         "flowArn": str,
         "description": str,
         "flowName": str,
         "kmsArn": str,
@@ -2444,15 +2637,15 @@
         "lastUpdatedAt": datetime,
         "createdBy": str,
         "lastUpdatedBy": str,
         "tags": Dict[str, str],
         "metadataCatalogConfig": MetadataCatalogConfigTypeDef,
         "lastRunMetadataCatalogDetails": List[MetadataCatalogDetailTypeDef],
         "schemaVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateFlowRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFlowRequestRequestTypeDef",
     {
         "flowName": str,
@@ -2463,15 +2656,17 @@
     },
 )
 _OptionalUpdateFlowRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateFlowRequestRequestTypeDef",
     {
         "description": str,
         "metadataCatalogConfig": MetadataCatalogConfigTypeDef,
+        "clientToken": str,
     },
     total=False,
 )
 
+
 class UpdateFlowRequestRequestTypeDef(
     _RequiredUpdateFlowRequestRequestTypeDef, _OptionalUpdateFlowRequestRequestTypeDef
 ):
     pass
```

### Comparing `types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow.egg-info/PKG-INFO` & `types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-appflow
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Appflow 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Appflow 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-appflow"></a>
 
 # types-aiobotocore-appflow
 
 [![PyPI - types-aiobotocore-appflow](https://img.shields.io/pypi/v/types-aiobotocore-appflow.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appflow)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appflow.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appflow)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appflow?color=blue)](https://pypistats.org/packages/types-aiobotocore-appflow)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Appflow 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow)
+[aiobotocore.Appflow 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appflow.html#Appflow)
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
 [types-aiobotocore-appflow docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appflow/).
 
 See how it helps to find and fix potential bugs:
 
@@ -276,14 +276,15 @@
     AmplitudeConnectorOperatorType,
     AuthenticationTypeType,
     CatalogTypeType,
     ConnectionModeType,
     ConnectorProvisioningTypeType,
     ConnectorTypeType,
     DataPullModeType,
+    DataTransferApiTypeType,
     DatadogConnectorOperatorType,
     DynatraceConnectorOperatorType,
     ExecutionStatusType,
     FileTypeType,
     FlowStatusType,
     GoogleAnalyticsConnectorOperatorType,
     InforNexusConnectorOperatorType,
@@ -304,14 +305,15 @@
     SAPODataConnectorOperatorType,
     SalesforceConnectorOperatorType,
     SalesforceDataTransferApiType,
     ScheduleFrequencyTypeType,
     ServiceNowConnectorOperatorType,
     SingularConnectorOperatorType,
     SlackConnectorOperatorType,
+    SupportedDataTransferTypeType,
     TaskTypeType,
     TrendmicroConnectorOperatorType,
     TriggerTypeType,
     VeevaConnectorOperatorType,
     WriteOperationTypeType,
     ZendeskConnectorOperatorType,
     AppflowServiceName,
@@ -336,15 +338,18 @@
 from types_aiobotocore_appflow.type_defs import (
     AggregationConfigTypeDef,
     AmplitudeConnectorProfileCredentialsTypeDef,
     AmplitudeSourcePropertiesTypeDef,
     ApiKeyCredentialsTypeDef,
     AuthParameterTypeDef,
     BasicAuthCredentialsTypeDef,
+    CancelFlowExecutionsRequestRequestTypeDef,
+    CancelFlowExecutionsResponseTypeDef,
     ConnectorRuntimeSettingTypeDef,
+    DataTransferApiTypeDef,
     ConnectorDetailTypeDef,
     DestinationFieldPropertiesTypeDef,
     SourceFieldPropertiesTypeDef,
     ConnectorEntityTypeDef,
     GoogleAnalyticsMetadataTypeDef,
     HoneycodeMetadataTypeDef,
     SalesforceMetadataTypeDef,
@@ -372,19 +377,19 @@
     ServiceNowConnectorProfilePropertiesTypeDef,
     SlackConnectorProfilePropertiesTypeDef,
     SnowflakeConnectorProfilePropertiesTypeDef,
     VeevaConnectorProfilePropertiesTypeDef,
     ZendeskConnectorProfilePropertiesTypeDef,
     PrivateConnectionProvisioningStateTypeDef,
     LambdaConnectorProvisioningConfigTypeDef,
-    ResponseMetadataTypeDef,
+    CreateConnectorProfileResponseTypeDef,
+    CreateFlowResponseTypeDef,
     CustomAuthCredentialsTypeDef,
     ErrorHandlingConfigTypeDef,
     OAuth2PropertiesTypeDef,
-    CustomConnectorSourcePropertiesTypeDef,
     CustomerProfilesDestinationPropertiesTypeDef,
     DatadogSourcePropertiesTypeDef,
     DeleteConnectorProfileRequestRequestTypeDef,
     DeleteFlowRequestRequestTypeDef,
     DescribeConnectorEntityRequestRequestTypeDef,
     DescribeConnectorProfilesRequestRequestTypeDef,
     DescribeConnectorRequestRequestTypeDef,
@@ -399,60 +404,61 @@
     GoogleAnalyticsSourcePropertiesTypeDef,
     IncrementalPullConfigTypeDef,
     InforNexusSourcePropertiesTypeDef,
     ListConnectorEntitiesRequestRequestTypeDef,
     ListConnectorsRequestRequestTypeDef,
     ListFlowsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     MarketoSourcePropertiesTypeDef,
     RegistrationOutputTypeDef,
     OAuth2CustomParameterTypeDef,
     OAuthPropertiesTypeDef,
     PardotSourcePropertiesTypeDef,
     PrefixConfigTypeDef,
+    RegisterConnectorResponseTypeDef,
+    ResetConnectorMetadataCacheRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     S3InputFormatConfigTypeDef,
     SuccessResponseHandlingConfigTypeDef,
     SAPODataSourcePropertiesTypeDef,
     SalesforceSourcePropertiesTypeDef,
     ScheduledTriggerPropertiesTypeDef,
     ServiceNowSourcePropertiesTypeDef,
     SingularSourcePropertiesTypeDef,
     SlackSourcePropertiesTypeDef,
     TrendmicroSourcePropertiesTypeDef,
     VeevaSourcePropertiesTypeDef,
     ZendeskSourcePropertiesTypeDef,
     StartFlowRequestRequestTypeDef,
+    StartFlowResponseTypeDef,
     StopFlowRequestRequestTypeDef,
+    StopFlowResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UnregisterConnectorRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateConnectorProfileResponseTypeDef,
+    UpdateConnectorRegistrationResponseTypeDef,
+    UpdateFlowResponseTypeDef,
     CustomAuthConfigTypeDef,
+    CustomConnectorSourcePropertiesTypeDef,
+    ListConnectorsResponseTypeDef,
+    ListConnectorEntitiesResponseTypeDef,
     ConnectorMetadataTypeDef,
     GoogleAnalyticsConnectorProfileCredentialsTypeDef,
     HoneycodeConnectorProfileCredentialsTypeDef,
     MarketoConnectorProfileCredentialsTypeDef,
     OAuth2CredentialsTypeDef,
     OAuthCredentialsTypeDef,
     PardotConnectorProfileCredentialsTypeDef,
     SalesforceConnectorProfileCredentialsTypeDef,
     SlackConnectorProfileCredentialsTypeDef,
     ZendeskConnectorProfileCredentialsTypeDef,
     TaskTypeDef,
     ConnectorProvisioningConfigTypeDef,
-    CreateConnectorProfileResponseTypeDef,
-    CreateFlowResponseTypeDef,
-    ListConnectorEntitiesResponseTypeDef,
-    ListConnectorsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RegisterConnectorResponseTypeDef,
-    StartFlowResponseTypeDef,
-    StopFlowResponseTypeDef,
-    UpdateConnectorProfileResponseTypeDef,
-    UpdateConnectorRegistrationResponseTypeDef,
-    UpdateFlowResponseTypeDef,
     CustomConnectorDestinationPropertiesTypeDef,
     EventBridgeDestinationPropertiesTypeDef,
     HoneycodeDestinationPropertiesTypeDef,
     MarketoDestinationPropertiesTypeDef,
     RedshiftDestinationPropertiesTypeDef,
     SalesforceDestinationPropertiesTypeDef,
     SnowflakeDestinationPropertiesTypeDef,
@@ -511,43 +517,43 @@
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

### Comparing `types-aiobotocore-appflow-2.5.0.post1/types_aiobotocore_appflow.egg-info/SOURCES.txt` & `types-aiobotocore-appflow-2.5.1/types_aiobotocore_appflow.egg-info/SOURCES.txt`

 * *Files identical despite different names*


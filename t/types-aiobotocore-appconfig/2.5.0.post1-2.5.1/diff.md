# Comparing `tmp/types-aiobotocore-appconfig-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-appconfig-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-appconfig-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:10 2023, max compression
+gzip compressed data, was "types-aiobotocore-appconfig-2.5.1.tar", last modified: Wed Jun 28 01:43:04 2023, max compression
```

## Comparing `types-aiobotocore-appconfig-2.5.0.post1.tar` & `types-aiobotocore-appconfig-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.342924 types-aiobotocore-appconfig-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:28.000000 types-aiobotocore-appconfig-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15391 2023-03-11 12:26:10.342924 types-aiobotocore-appconfig-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13812 2023-03-11 12:09:28.000000 types-aiobotocore-appconfig-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:10.342924 types-aiobotocore-appconfig-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:09:28.000000 types-aiobotocore-appconfig-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.334924 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/
--rw-r--r--   0 runner    (1001) docker     (123)      458 2023-03-11 12:09:28.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      457 2023-03-11 12:09:28.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:09:28.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    31094 2023-03-11 12:09:29.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    31043 2023-03-11 12:09:29.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8980 2023-03-11 12:09:29.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8978 2023-03-11 12:09:29.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:28.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    31181 2023-03-11 12:09:30.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    31136 2023-03-11 12:09:30.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:28.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.342924 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15391 2023-03-11 12:26:10.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      768 2023-03-11 12:26:10.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:10.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:10.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:10.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:26:10.000000 types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.322090 types-aiobotocore-appconfig-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:05.000000 types-aiobotocore-appconfig-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15385 2023-06-28 01:43:04.322090 types-aiobotocore-appconfig-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13812 2023-06-28 01:26:05.000000 types-aiobotocore-appconfig-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:04.322090 types-aiobotocore-appconfig-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:26:05.000000 types-aiobotocore-appconfig-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.322090 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/
+-rw-r--r--   0 runner    (1001) docker     (123)      458 2023-06-28 01:26:05.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      457 2023-06-28 01:26:05.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:26:05.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31094 2023-06-28 01:26:06.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31043 2023-06-28 01:26:05.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9189 2023-06-28 01:26:06.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9187 2023-06-28 01:26:06.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:05.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    31219 2023-06-28 01:26:07.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31174 2023-06-28 01:26:06.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:05.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.322090 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15385 2023-06-28 01:43:04.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      768 2023-06-28 01:43:04.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:04.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:04.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:04.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:43:04.000000 types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-appconfig-2.5.0.post1/LICENSE` & `types-aiobotocore-appconfig-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-appconfig-2.5.0.post1/PKG-INFO` & `types-aiobotocore-appconfig-2.5.1/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-appconfig
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AppConfig 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AppConfig 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appconfig/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-appconfig"></a>
 
 # types-aiobotocore-appconfig
 
 [![PyPI - types-aiobotocore-appconfig](https://img.shields.io/pypi/v/types-aiobotocore-appconfig.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appconfig)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appconfig.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appconfig)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appconfig/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appconfig?color=blue)](https://pypistats.org/packages/types-aiobotocore-appconfig)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppConfig 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appconfig.html#AppConfig)
+[aiobotocore.AppConfig 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appconfig.html#AppConfig)
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
 [types-aiobotocore-appconfig docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appconfig/).
 
 See how it helps to find and fix potential bugs:
 
@@ -299,71 +299,71 @@
 `types_aiobotocore_appconfig.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_appconfig.type_defs import (
     ActionInvocationTypeDef,
     ActionTypeDef,
-    ResponseMetadataTypeDef,
+    ApplicationResponseMetadataTypeDef,
     ApplicationTypeDef,
     AppliedExtensionTypeDef,
     ConfigurationProfileSummaryTypeDef,
     ValidatorTypeDef,
+    ConfigurationTypeDef,
     CreateApplicationRequestRequestTypeDef,
     CreateDeploymentStrategyRequestRequestTypeDef,
     MonitorTypeDef,
     CreateExtensionAssociationRequestRequestTypeDef,
     ParameterTypeDef,
     CreateHostedConfigurationVersionRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteConfigurationProfileRequestRequestTypeDef,
     DeleteDeploymentStrategyRequestRequestTypeDef,
     DeleteEnvironmentRequestRequestTypeDef,
     DeleteExtensionAssociationRequestRequestTypeDef,
     DeleteExtensionRequestRequestTypeDef,
     DeleteHostedConfigurationVersionRequestRequestTypeDef,
     DeploymentStrategyTypeDef,
+    DeploymentStrategyResponseMetadataTypeDef,
     DeploymentSummaryTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExtensionAssociationSummaryTypeDef,
+    ExtensionAssociationTypeDef,
     ExtensionSummaryTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetConfigurationProfileRequestRequestTypeDef,
     GetConfigurationRequestRequestTypeDef,
     GetDeploymentRequestRequestTypeDef,
     GetDeploymentStrategyRequestRequestTypeDef,
     GetEnvironmentRequestRequestTypeDef,
     GetExtensionAssociationRequestRequestTypeDef,
     GetExtensionRequestRequestTypeDef,
     GetHostedConfigurationVersionRequestRequestTypeDef,
     HostedConfigurationVersionSummaryTypeDef,
+    HostedConfigurationVersionTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListConfigurationProfilesRequestRequestTypeDef,
     ListDeploymentStrategiesRequestRequestTypeDef,
     ListDeploymentsRequestRequestTypeDef,
     ListEnvironmentsRequestRequestTypeDef,
     ListExtensionAssociationsRequestRequestTypeDef,
     ListExtensionsRequestRequestTypeDef,
     ListHostedConfigurationVersionsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ResourceTagsTypeDef,
+    ResponseMetadataTypeDef,
     StartDeploymentRequestRequestTypeDef,
     StopDeploymentRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     UpdateDeploymentStrategyRequestRequestTypeDef,
     UpdateExtensionAssociationRequestRequestTypeDef,
     ValidateConfigurationRequestRequestTypeDef,
     DeploymentEventTypeDef,
-    ApplicationResponseMetadataTypeDef,
-    ConfigurationTypeDef,
-    DeploymentStrategyResponseMetadataTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExtensionAssociationTypeDef,
-    HostedConfigurationVersionTypeDef,
-    ResourceTagsTypeDef,
     ApplicationsTypeDef,
     ConfigurationProfilesTypeDef,
     ConfigurationProfileTypeDef,
     CreateConfigurationProfileRequestRequestTypeDef,
     UpdateConfigurationProfileRequestRequestTypeDef,
     CreateEnvironmentRequestRequestTypeDef,
     EnvironmentResponseMetadataTypeDef,
@@ -389,43 +389,43 @@
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

### Comparing `types-aiobotocore-appconfig-2.5.0.post1/README.md` & `types-aiobotocore-appconfig-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-appconfig"></a>
 
 # types-aiobotocore-appconfig
 
 [![PyPI - types-aiobotocore-appconfig](https://img.shields.io/pypi/v/types-aiobotocore-appconfig.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appconfig)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appconfig.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appconfig)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appconfig/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appconfig?color=blue)](https://pypistats.org/packages/types-aiobotocore-appconfig)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppConfig 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appconfig.html#AppConfig)
+[aiobotocore.AppConfig 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appconfig.html#AppConfig)
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
 [types-aiobotocore-appconfig docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appconfig/).
 
 See how it helps to find and fix potential bugs:
 
@@ -266,71 +266,71 @@
 `types_aiobotocore_appconfig.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_appconfig.type_defs import (
     ActionInvocationTypeDef,
     ActionTypeDef,
-    ResponseMetadataTypeDef,
+    ApplicationResponseMetadataTypeDef,
     ApplicationTypeDef,
     AppliedExtensionTypeDef,
     ConfigurationProfileSummaryTypeDef,
     ValidatorTypeDef,
+    ConfigurationTypeDef,
     CreateApplicationRequestRequestTypeDef,
     CreateDeploymentStrategyRequestRequestTypeDef,
     MonitorTypeDef,
     CreateExtensionAssociationRequestRequestTypeDef,
     ParameterTypeDef,
     CreateHostedConfigurationVersionRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteConfigurationProfileRequestRequestTypeDef,
     DeleteDeploymentStrategyRequestRequestTypeDef,
     DeleteEnvironmentRequestRequestTypeDef,
     DeleteExtensionAssociationRequestRequestTypeDef,
     DeleteExtensionRequestRequestTypeDef,
     DeleteHostedConfigurationVersionRequestRequestTypeDef,
     DeploymentStrategyTypeDef,
+    DeploymentStrategyResponseMetadataTypeDef,
     DeploymentSummaryTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExtensionAssociationSummaryTypeDef,
+    ExtensionAssociationTypeDef,
     ExtensionSummaryTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetConfigurationProfileRequestRequestTypeDef,
     GetConfigurationRequestRequestTypeDef,
     GetDeploymentRequestRequestTypeDef,
     GetDeploymentStrategyRequestRequestTypeDef,
     GetEnvironmentRequestRequestTypeDef,
     GetExtensionAssociationRequestRequestTypeDef,
     GetExtensionRequestRequestTypeDef,
     GetHostedConfigurationVersionRequestRequestTypeDef,
     HostedConfigurationVersionSummaryTypeDef,
+    HostedConfigurationVersionTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListConfigurationProfilesRequestRequestTypeDef,
     ListDeploymentStrategiesRequestRequestTypeDef,
     ListDeploymentsRequestRequestTypeDef,
     ListEnvironmentsRequestRequestTypeDef,
     ListExtensionAssociationsRequestRequestTypeDef,
     ListExtensionsRequestRequestTypeDef,
     ListHostedConfigurationVersionsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ResourceTagsTypeDef,
+    ResponseMetadataTypeDef,
     StartDeploymentRequestRequestTypeDef,
     StopDeploymentRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     UpdateDeploymentStrategyRequestRequestTypeDef,
     UpdateExtensionAssociationRequestRequestTypeDef,
     ValidateConfigurationRequestRequestTypeDef,
     DeploymentEventTypeDef,
-    ApplicationResponseMetadataTypeDef,
-    ConfigurationTypeDef,
-    DeploymentStrategyResponseMetadataTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExtensionAssociationTypeDef,
-    HostedConfigurationVersionTypeDef,
-    ResourceTagsTypeDef,
     ApplicationsTypeDef,
     ConfigurationProfilesTypeDef,
     ConfigurationProfileTypeDef,
     CreateConfigurationProfileRequestRequestTypeDef,
     UpdateConfigurationProfileRequestRequestTypeDef,
     CreateEnvironmentRequestRequestTypeDef,
     EnvironmentResponseMetadataTypeDef,
@@ -356,43 +356,43 @@
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

### Comparing `types-aiobotocore-appconfig-2.5.0.post1/setup.py` & `types-aiobotocore-appconfig-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-appconfig.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-appconfig",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_appconfig"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.AppConfig 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.AppConfig 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appconfig/"
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

### Comparing `types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/__main__.py` & `types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.AppConfig 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.AppConfig 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appconfig//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appconfig.html#AppConfig\nOther"
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

### Comparing `types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/client.py` & `types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/client.pyi` & `types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/literals.py` & `types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -119,14 +119,15 @@
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
@@ -205,14 +206,15 @@
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
@@ -223,14 +225,15 @@
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
@@ -266,14 +269,15 @@
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
@@ -292,16 +296,19 @@
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
@@ -385,15 +392,17 @@
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

### Comparing `types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/literals.pyi` & `types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -117,14 +117,15 @@
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
@@ -203,14 +204,15 @@
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
@@ -221,14 +223,15 @@
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
@@ -264,14 +267,15 @@
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
@@ -290,16 +294,19 @@
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
@@ -383,15 +390,17 @@
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

### Comparing `types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/type_defs.py` & `types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/type_defs.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -29,75 +29,74 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ActionInvocationTypeDef",
     "ActionTypeDef",
-    "ResponseMetadataTypeDef",
+    "ApplicationResponseMetadataTypeDef",
     "ApplicationTypeDef",
     "AppliedExtensionTypeDef",
     "ConfigurationProfileSummaryTypeDef",
     "ValidatorTypeDef",
+    "ConfigurationTypeDef",
     "CreateApplicationRequestRequestTypeDef",
     "CreateDeploymentStrategyRequestRequestTypeDef",
     "MonitorTypeDef",
     "CreateExtensionAssociationRequestRequestTypeDef",
     "ParameterTypeDef",
     "CreateHostedConfigurationVersionRequestRequestTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DeleteConfigurationProfileRequestRequestTypeDef",
     "DeleteDeploymentStrategyRequestRequestTypeDef",
     "DeleteEnvironmentRequestRequestTypeDef",
     "DeleteExtensionAssociationRequestRequestTypeDef",
     "DeleteExtensionRequestRequestTypeDef",
     "DeleteHostedConfigurationVersionRequestRequestTypeDef",
     "DeploymentStrategyTypeDef",
+    "DeploymentStrategyResponseMetadataTypeDef",
     "DeploymentSummaryTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExtensionAssociationSummaryTypeDef",
+    "ExtensionAssociationTypeDef",
     "ExtensionSummaryTypeDef",
     "GetApplicationRequestRequestTypeDef",
     "GetConfigurationProfileRequestRequestTypeDef",
     "GetConfigurationRequestRequestTypeDef",
     "GetDeploymentRequestRequestTypeDef",
     "GetDeploymentStrategyRequestRequestTypeDef",
     "GetEnvironmentRequestRequestTypeDef",
     "GetExtensionAssociationRequestRequestTypeDef",
     "GetExtensionRequestRequestTypeDef",
     "GetHostedConfigurationVersionRequestRequestTypeDef",
     "HostedConfigurationVersionSummaryTypeDef",
+    "HostedConfigurationVersionTypeDef",
     "ListApplicationsRequestRequestTypeDef",
     "ListConfigurationProfilesRequestRequestTypeDef",
     "ListDeploymentStrategiesRequestRequestTypeDef",
     "ListDeploymentsRequestRequestTypeDef",
     "ListEnvironmentsRequestRequestTypeDef",
     "ListExtensionAssociationsRequestRequestTypeDef",
     "ListExtensionsRequestRequestTypeDef",
     "ListHostedConfigurationVersionsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ResourceTagsTypeDef",
+    "ResponseMetadataTypeDef",
     "StartDeploymentRequestRequestTypeDef",
     "StopDeploymentRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
     "UpdateDeploymentStrategyRequestRequestTypeDef",
     "UpdateExtensionAssociationRequestRequestTypeDef",
     "ValidateConfigurationRequestRequestTypeDef",
     "DeploymentEventTypeDef",
-    "ApplicationResponseMetadataTypeDef",
-    "ConfigurationTypeDef",
-    "DeploymentStrategyResponseMetadataTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExtensionAssociationTypeDef",
-    "HostedConfigurationVersionTypeDef",
-    "ResourceTagsTypeDef",
     "ApplicationsTypeDef",
     "ConfigurationProfilesTypeDef",
     "ConfigurationProfileTypeDef",
     "CreateConfigurationProfileRequestRequestTypeDef",
     "UpdateConfigurationProfileRequestRequestTypeDef",
     "CreateEnvironmentRequestRequestTypeDef",
     "EnvironmentResponseMetadataTypeDef",
@@ -136,22 +135,21 @@
         "Description": str,
         "Uri": str,
         "RoleArn": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ApplicationResponseMetadataTypeDef = TypedDict(
+    "ApplicationResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Id": str,
+        "Name": str,
+        "Description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ApplicationTypeDef = TypedDict(
     "ApplicationTypeDef",
     {
         "Id": str,
@@ -189,14 +187,24 @@
     "ValidatorTypeDef",
     {
         "Type": ValidatorTypeType,
         "Content": str,
     },
 )
 
+ConfigurationTypeDef = TypedDict(
+    "ConfigurationTypeDef",
+    {
+        "Content": StreamingBody,
+        "ConfigurationVersion": str,
+        "ContentType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateApplicationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateApplicationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCreateApplicationRequestRequestTypeDef = TypedDict(
@@ -204,21 +212,19 @@
     {
         "Description": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateApplicationRequestRequestTypeDef(
     _RequiredCreateApplicationRequestRequestTypeDef, _OptionalCreateApplicationRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateDeploymentStrategyRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDeploymentStrategyRequestRequestTypeDef",
     {
         "Name": str,
         "DeploymentDurationInMinutes": int,
         "GrowthFactor": float,
     },
@@ -231,41 +237,37 @@
         "GrowthType": GrowthTypeType,
         "ReplicateTo": ReplicateToType,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateDeploymentStrategyRequestRequestTypeDef(
     _RequiredCreateDeploymentStrategyRequestRequestTypeDef,
     _OptionalCreateDeploymentStrategyRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredMonitorTypeDef = TypedDict(
     "_RequiredMonitorTypeDef",
     {
         "AlarmArn": str,
     },
 )
 _OptionalMonitorTypeDef = TypedDict(
     "_OptionalMonitorTypeDef",
     {
         "AlarmRoleArn": str,
     },
     total=False,
 )
 
-
 class MonitorTypeDef(_RequiredMonitorTypeDef, _OptionalMonitorTypeDef):
     pass
 
-
 _RequiredCreateExtensionAssociationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateExtensionAssociationRequestRequestTypeDef",
     {
         "ExtensionIdentifier": str,
         "ResourceIdentifier": str,
     },
 )
@@ -275,22 +277,20 @@
         "ExtensionVersionNumber": int,
         "Parameters": Mapping[str, str],
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateExtensionAssociationRequestRequestTypeDef(
     _RequiredCreateExtensionAssociationRequestRequestTypeDef,
     _OptionalCreateExtensionAssociationRequestRequestTypeDef,
 ):
     pass
 
-
 ParameterTypeDef = TypedDict(
     "ParameterTypeDef",
     {
         "Description": str,
         "Required": bool,
     },
     total=False,
@@ -311,22 +311,20 @@
         "Description": str,
         "LatestVersionNumber": int,
         "VersionLabel": str,
     },
     total=False,
 )
 
-
 class CreateHostedConfigurationVersionRequestRequestTypeDef(
     _RequiredCreateHostedConfigurationVersionRequestRequestTypeDef,
     _OptionalCreateHostedConfigurationVersionRequestRequestTypeDef,
 ):
     pass
 
-
 DeleteApplicationRequestRequestTypeDef = TypedDict(
     "DeleteApplicationRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
@@ -370,21 +368,19 @@
     "_OptionalDeleteExtensionRequestRequestTypeDef",
     {
         "VersionNumber": int,
     },
     total=False,
 )
 
-
 class DeleteExtensionRequestRequestTypeDef(
     _RequiredDeleteExtensionRequestRequestTypeDef, _OptionalDeleteExtensionRequestRequestTypeDef
 ):
     pass
 
-
 DeleteHostedConfigurationVersionRequestRequestTypeDef = TypedDict(
     "DeleteHostedConfigurationVersionRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "ConfigurationProfileId": str,
         "VersionNumber": int,
     },
@@ -401,14 +397,29 @@
         "GrowthFactor": float,
         "FinalBakeTimeInMinutes": int,
         "ReplicateTo": ReplicateToType,
     },
     total=False,
 )
 
+DeploymentStrategyResponseMetadataTypeDef = TypedDict(
+    "DeploymentStrategyResponseMetadataTypeDef",
+    {
+        "Id": str,
+        "Name": str,
+        "Description": str,
+        "DeploymentDurationInMinutes": int,
+        "GrowthType": GrowthTypeType,
+        "GrowthFactor": float,
+        "FinalBakeTimeInMinutes": int,
+        "ReplicateTo": ReplicateToType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeploymentSummaryTypeDef = TypedDict(
     "DeploymentSummaryTypeDef",
     {
         "DeploymentNumber": int,
         "ConfigurationName": str,
         "ConfigurationVersion": str,
         "DeploymentDurationInMinutes": int,
@@ -419,24 +430,44 @@
         "PercentageComplete": float,
         "StartedAt": datetime,
         "CompletedAt": datetime,
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
 ExtensionAssociationSummaryTypeDef = TypedDict(
     "ExtensionAssociationSummaryTypeDef",
     {
         "Id": str,
         "ExtensionArn": str,
         "ResourceArn": str,
     },
     total=False,
 )
 
+ExtensionAssociationTypeDef = TypedDict(
+    "ExtensionAssociationTypeDef",
+    {
+        "Id": str,
+        "ExtensionArn": str,
+        "ResourceArn": str,
+        "Arn": str,
+        "Parameters": Dict[str, str],
+        "ExtensionVersionNumber": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExtensionSummaryTypeDef = TypedDict(
     "ExtensionSummaryTypeDef",
     {
         "Id": str,
         "Name": str,
         "VersionNumber": int,
         "Arn": str,
@@ -473,21 +504,19 @@
     "_OptionalGetConfigurationRequestRequestTypeDef",
     {
         "ClientConfigurationVersion": str,
     },
     total=False,
 )
 
-
 class GetConfigurationRequestRequestTypeDef(
     _RequiredGetConfigurationRequestRequestTypeDef, _OptionalGetConfigurationRequestRequestTypeDef
 ):
     pass
 
-
 GetDeploymentRequestRequestTypeDef = TypedDict(
     "GetDeploymentRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "EnvironmentId": str,
         "DeploymentNumber": int,
     },
@@ -525,21 +554,19 @@
     "_OptionalGetExtensionRequestRequestTypeDef",
     {
         "VersionNumber": int,
     },
     total=False,
 )
 
-
 class GetExtensionRequestRequestTypeDef(
     _RequiredGetExtensionRequestRequestTypeDef, _OptionalGetExtensionRequestRequestTypeDef
 ):
     pass
 
-
 GetHostedConfigurationVersionRequestRequestTypeDef = TypedDict(
     "GetHostedConfigurationVersionRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "ConfigurationProfileId": str,
         "VersionNumber": int,
     },
@@ -554,14 +581,28 @@
         "Description": str,
         "ContentType": str,
         "VersionLabel": str,
     },
     total=False,
 )
 
+HostedConfigurationVersionTypeDef = TypedDict(
+    "HostedConfigurationVersionTypeDef",
+    {
+        "ApplicationId": str,
+        "ConfigurationProfileId": str,
+        "VersionNumber": int,
+        "Description": str,
+        "Content": StreamingBody,
+        "ContentType": str,
+        "VersionLabel": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -579,22 +620,20 @@
         "MaxResults": int,
         "NextToken": str,
         "Type": str,
     },
     total=False,
 )
 
-
 class ListConfigurationProfilesRequestRequestTypeDef(
     _RequiredListConfigurationProfilesRequestRequestTypeDef,
     _OptionalListConfigurationProfilesRequestRequestTypeDef,
 ):
     pass
 
-
 ListDeploymentStrategiesRequestRequestTypeDef = TypedDict(
     "ListDeploymentStrategiesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -612,21 +651,19 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListDeploymentsRequestRequestTypeDef(
     _RequiredListDeploymentsRequestRequestTypeDef, _OptionalListDeploymentsRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredListEnvironmentsRequestRequestTypeDef = TypedDict(
     "_RequiredListEnvironmentsRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 _OptionalListEnvironmentsRequestRequestTypeDef = TypedDict(
@@ -634,21 +671,19 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListEnvironmentsRequestRequestTypeDef(
     _RequiredListEnvironmentsRequestRequestTypeDef, _OptionalListEnvironmentsRequestRequestTypeDef
 ):
     pass
 
-
 ListExtensionAssociationsRequestRequestTypeDef = TypedDict(
     "ListExtensionAssociationsRequestRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "ExtensionIdentifier": str,
         "ExtensionVersionNumber": int,
         "MaxResults": int,
@@ -680,29 +715,46 @@
         "MaxResults": int,
         "NextToken": str,
         "VersionLabel": str,
     },
     total=False,
 )
 
-
 class ListHostedConfigurationVersionsRequestRequestTypeDef(
     _RequiredListHostedConfigurationVersionsRequestRequestTypeDef,
     _OptionalListHostedConfigurationVersionsRequestRequestTypeDef,
 ):
     pass
 
-
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ResourceTagsTypeDef = TypedDict(
+    "ResourceTagsTypeDef",
+    {
+        "Tags": Dict[str, str],
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
 _RequiredStartDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredStartDeploymentRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "EnvironmentId": str,
         "DeploymentStrategyId": str,
         "ConfigurationProfileId": str,
@@ -715,21 +767,19 @@
         "Description": str,
         "Tags": Mapping[str, str],
         "KmsKeyIdentifier": str,
     },
     total=False,
 )
 
-
 class StartDeploymentRequestRequestTypeDef(
     _RequiredStartDeploymentRequestRequestTypeDef, _OptionalStartDeploymentRequestRequestTypeDef
 ):
     pass
 
-
 StopDeploymentRequestRequestTypeDef = TypedDict(
     "StopDeploymentRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "EnvironmentId": str,
         "DeploymentNumber": int,
     },
@@ -762,21 +812,19 @@
     {
         "Name": str,
         "Description": str,
     },
     total=False,
 )
 
-
 class UpdateApplicationRequestRequestTypeDef(
     _RequiredUpdateApplicationRequestRequestTypeDef, _OptionalUpdateApplicationRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateDeploymentStrategyRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDeploymentStrategyRequestRequestTypeDef",
     {
         "DeploymentStrategyId": str,
     },
 )
 _OptionalUpdateDeploymentStrategyRequestRequestTypeDef = TypedDict(
@@ -787,44 +835,40 @@
         "FinalBakeTimeInMinutes": int,
         "GrowthFactor": float,
         "GrowthType": GrowthTypeType,
     },
     total=False,
 )
 
-
 class UpdateDeploymentStrategyRequestRequestTypeDef(
     _RequiredUpdateDeploymentStrategyRequestRequestTypeDef,
     _OptionalUpdateDeploymentStrategyRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateExtensionAssociationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateExtensionAssociationRequestRequestTypeDef",
     {
         "ExtensionAssociationId": str,
     },
 )
 _OptionalUpdateExtensionAssociationRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateExtensionAssociationRequestRequestTypeDef",
     {
         "Parameters": Mapping[str, str],
     },
     total=False,
 )
 
-
 class UpdateExtensionAssociationRequestRequestTypeDef(
     _RequiredUpdateExtensionAssociationRequestRequestTypeDef,
     _OptionalUpdateExtensionAssociationRequestRequestTypeDef,
 ):
     pass
 
-
 ValidateConfigurationRequestRequestTypeDef = TypedDict(
     "ValidateConfigurationRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "ConfigurationProfileId": str,
         "ConfigurationVersion": str,
     },
@@ -838,121 +882,44 @@
         "Description": str,
         "ActionInvocations": List[ActionInvocationTypeDef],
         "OccurredAt": datetime,
     },
     total=False,
 )
 
-ApplicationResponseMetadataTypeDef = TypedDict(
-    "ApplicationResponseMetadataTypeDef",
-    {
-        "Id": str,
-        "Name": str,
-        "Description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConfigurationTypeDef = TypedDict(
-    "ConfigurationTypeDef",
-    {
-        "Content": StreamingBody,
-        "ConfigurationVersion": str,
-        "ContentType": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeploymentStrategyResponseMetadataTypeDef = TypedDict(
-    "DeploymentStrategyResponseMetadataTypeDef",
-    {
-        "Id": str,
-        "Name": str,
-        "Description": str,
-        "DeploymentDurationInMinutes": int,
-        "GrowthType": GrowthTypeType,
-        "GrowthFactor": float,
-        "FinalBakeTimeInMinutes": int,
-        "ReplicateTo": ReplicateToType,
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
-ExtensionAssociationTypeDef = TypedDict(
-    "ExtensionAssociationTypeDef",
-    {
-        "Id": str,
-        "ExtensionArn": str,
-        "ResourceArn": str,
-        "Arn": str,
-        "Parameters": Dict[str, str],
-        "ExtensionVersionNumber": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-HostedConfigurationVersionTypeDef = TypedDict(
-    "HostedConfigurationVersionTypeDef",
-    {
-        "ApplicationId": str,
-        "ConfigurationProfileId": str,
-        "VersionNumber": int,
-        "Description": str,
-        "Content": StreamingBody,
-        "ContentType": str,
-        "VersionLabel": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ResourceTagsTypeDef = TypedDict(
-    "ResourceTagsTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ApplicationsTypeDef = TypedDict(
     "ApplicationsTypeDef",
     {
         "Items": List[ApplicationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConfigurationProfilesTypeDef = TypedDict(
     "ConfigurationProfilesTypeDef",
     {
         "Items": List[ConfigurationProfileSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConfigurationProfileTypeDef = TypedDict(
     "ConfigurationProfileTypeDef",
     {
         "ApplicationId": str,
         "Id": str,
         "Name": str,
         "Description": str,
         "LocationUri": str,
         "RetrievalRoleArn": str,
         "Validators": List[ValidatorTypeDef],
         "Type": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateConfigurationProfileRequestRequestTypeDef = TypedDict(
     "_RequiredCreateConfigurationProfileRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -968,22 +935,20 @@
         "Validators": Sequence[ValidatorTypeDef],
         "Tags": Mapping[str, str],
         "Type": str,
     },
     total=False,
 )
 
-
 class CreateConfigurationProfileRequestRequestTypeDef(
     _RequiredCreateConfigurationProfileRequestRequestTypeDef,
     _OptionalCreateConfigurationProfileRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateConfigurationProfileRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateConfigurationProfileRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "ConfigurationProfileId": str,
     },
 )
@@ -994,22 +959,20 @@
         "Description": str,
         "RetrievalRoleArn": str,
         "Validators": Sequence[ValidatorTypeDef],
     },
     total=False,
 )
 
-
 class UpdateConfigurationProfileRequestRequestTypeDef(
     _RequiredUpdateConfigurationProfileRequestRequestTypeDef,
     _OptionalUpdateConfigurationProfileRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateEnvironmentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEnvironmentRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "Name": str,
     },
 )
@@ -1019,31 +982,29 @@
         "Description": str,
         "Monitors": Sequence[MonitorTypeDef],
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateEnvironmentRequestRequestTypeDef(
     _RequiredCreateEnvironmentRequestRequestTypeDef, _OptionalCreateEnvironmentRequestRequestTypeDef
 ):
     pass
 
-
 EnvironmentResponseMetadataTypeDef = TypedDict(
     "EnvironmentResponseMetadataTypeDef",
     {
         "ApplicationId": str,
         "Id": str,
         "Name": str,
         "Description": str,
         "State": EnvironmentStateType,
         "Monitors": List[MonitorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentTypeDef = TypedDict(
     "EnvironmentTypeDef",
     {
         "ApplicationId": str,
@@ -1069,21 +1030,19 @@
         "Name": str,
         "Description": str,
         "Monitors": Sequence[MonitorTypeDef],
     },
     total=False,
 )
 
-
 class UpdateEnvironmentRequestRequestTypeDef(
     _RequiredUpdateEnvironmentRequestRequestTypeDef, _OptionalUpdateEnvironmentRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateExtensionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateExtensionRequestRequestTypeDef",
     {
         "Name": str,
         "Actions": Mapping[ActionPointType, Sequence[ActionTypeDef]],
     },
 )
@@ -1094,32 +1053,30 @@
         "Parameters": Mapping[str, ParameterTypeDef],
         "Tags": Mapping[str, str],
         "LatestVersionNumber": int,
     },
     total=False,
 )
 
-
 class CreateExtensionRequestRequestTypeDef(
     _RequiredCreateExtensionRequestRequestTypeDef, _OptionalCreateExtensionRequestRequestTypeDef
 ):
     pass
 
-
 ExtensionTypeDef = TypedDict(
     "ExtensionTypeDef",
     {
         "Id": str,
         "Name": str,
         "VersionNumber": int,
         "Arn": str,
         "Description": str,
         "Actions": Dict[ActionPointType, List[ActionTypeDef]],
         "Parameters": Dict[str, ParameterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateExtensionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateExtensionRequestRequestTypeDef",
     {
         "ExtensionIdentifier": str,
@@ -1132,63 +1089,61 @@
         "Actions": Mapping[ActionPointType, Sequence[ActionTypeDef]],
         "Parameters": Mapping[str, ParameterTypeDef],
         "VersionNumber": int,
     },
     total=False,
 )
 
-
 class UpdateExtensionRequestRequestTypeDef(
     _RequiredUpdateExtensionRequestRequestTypeDef, _OptionalUpdateExtensionRequestRequestTypeDef
 ):
     pass
 
-
 DeploymentStrategiesTypeDef = TypedDict(
     "DeploymentStrategiesTypeDef",
     {
         "Items": List[DeploymentStrategyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploymentsTypeDef = TypedDict(
     "DeploymentsTypeDef",
     {
         "Items": List[DeploymentSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExtensionAssociationsTypeDef = TypedDict(
     "ExtensionAssociationsTypeDef",
     {
         "Items": List[ExtensionAssociationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExtensionsTypeDef = TypedDict(
     "ExtensionsTypeDef",
     {
         "Items": List[ExtensionSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 HostedConfigurationVersionsTypeDef = TypedDict(
     "HostedConfigurationVersionsTypeDef",
     {
         "Items": List[HostedConfigurationVersionSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploymentTypeDef = TypedDict(
     "DeploymentTypeDef",
     {
         "ApplicationId": str,
@@ -1208,19 +1163,19 @@
         "EventLog": List[DeploymentEventTypeDef],
         "PercentageComplete": float,
         "StartedAt": datetime,
         "CompletedAt": datetime,
         "AppliedExtensions": List[AppliedExtensionTypeDef],
         "KmsKeyArn": str,
         "KmsKeyIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentsTypeDef = TypedDict(
     "EnvironmentsTypeDef",
     {
         "Items": List[EnvironmentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig/type_defs.pyi` & `types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -29,74 +29,75 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ActionInvocationTypeDef",
     "ActionTypeDef",
-    "ResponseMetadataTypeDef",
+    "ApplicationResponseMetadataTypeDef",
     "ApplicationTypeDef",
     "AppliedExtensionTypeDef",
     "ConfigurationProfileSummaryTypeDef",
     "ValidatorTypeDef",
+    "ConfigurationTypeDef",
     "CreateApplicationRequestRequestTypeDef",
     "CreateDeploymentStrategyRequestRequestTypeDef",
     "MonitorTypeDef",
     "CreateExtensionAssociationRequestRequestTypeDef",
     "ParameterTypeDef",
     "CreateHostedConfigurationVersionRequestRequestTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DeleteConfigurationProfileRequestRequestTypeDef",
     "DeleteDeploymentStrategyRequestRequestTypeDef",
     "DeleteEnvironmentRequestRequestTypeDef",
     "DeleteExtensionAssociationRequestRequestTypeDef",
     "DeleteExtensionRequestRequestTypeDef",
     "DeleteHostedConfigurationVersionRequestRequestTypeDef",
     "DeploymentStrategyTypeDef",
+    "DeploymentStrategyResponseMetadataTypeDef",
     "DeploymentSummaryTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExtensionAssociationSummaryTypeDef",
+    "ExtensionAssociationTypeDef",
     "ExtensionSummaryTypeDef",
     "GetApplicationRequestRequestTypeDef",
     "GetConfigurationProfileRequestRequestTypeDef",
     "GetConfigurationRequestRequestTypeDef",
     "GetDeploymentRequestRequestTypeDef",
     "GetDeploymentStrategyRequestRequestTypeDef",
     "GetEnvironmentRequestRequestTypeDef",
     "GetExtensionAssociationRequestRequestTypeDef",
     "GetExtensionRequestRequestTypeDef",
     "GetHostedConfigurationVersionRequestRequestTypeDef",
     "HostedConfigurationVersionSummaryTypeDef",
+    "HostedConfigurationVersionTypeDef",
     "ListApplicationsRequestRequestTypeDef",
     "ListConfigurationProfilesRequestRequestTypeDef",
     "ListDeploymentStrategiesRequestRequestTypeDef",
     "ListDeploymentsRequestRequestTypeDef",
     "ListEnvironmentsRequestRequestTypeDef",
     "ListExtensionAssociationsRequestRequestTypeDef",
     "ListExtensionsRequestRequestTypeDef",
     "ListHostedConfigurationVersionsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ResourceTagsTypeDef",
+    "ResponseMetadataTypeDef",
     "StartDeploymentRequestRequestTypeDef",
     "StopDeploymentRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
     "UpdateDeploymentStrategyRequestRequestTypeDef",
     "UpdateExtensionAssociationRequestRequestTypeDef",
     "ValidateConfigurationRequestRequestTypeDef",
     "DeploymentEventTypeDef",
-    "ApplicationResponseMetadataTypeDef",
-    "ConfigurationTypeDef",
-    "DeploymentStrategyResponseMetadataTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExtensionAssociationTypeDef",
-    "HostedConfigurationVersionTypeDef",
-    "ResourceTagsTypeDef",
     "ApplicationsTypeDef",
     "ConfigurationProfilesTypeDef",
     "ConfigurationProfileTypeDef",
     "CreateConfigurationProfileRequestRequestTypeDef",
     "UpdateConfigurationProfileRequestRequestTypeDef",
     "CreateEnvironmentRequestRequestTypeDef",
     "EnvironmentResponseMetadataTypeDef",
@@ -135,22 +136,21 @@
         "Description": str,
         "Uri": str,
         "RoleArn": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ApplicationResponseMetadataTypeDef = TypedDict(
+    "ApplicationResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Id": str,
+        "Name": str,
+        "Description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ApplicationTypeDef = TypedDict(
     "ApplicationTypeDef",
     {
         "Id": str,
@@ -188,14 +188,24 @@
     "ValidatorTypeDef",
     {
         "Type": ValidatorTypeType,
         "Content": str,
     },
 )
 
+ConfigurationTypeDef = TypedDict(
+    "ConfigurationTypeDef",
+    {
+        "Content": StreamingBody,
+        "ConfigurationVersion": str,
+        "ContentType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateApplicationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateApplicationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCreateApplicationRequestRequestTypeDef = TypedDict(
@@ -203,19 +213,21 @@
     {
         "Description": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateApplicationRequestRequestTypeDef(
     _RequiredCreateApplicationRequestRequestTypeDef, _OptionalCreateApplicationRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateDeploymentStrategyRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDeploymentStrategyRequestRequestTypeDef",
     {
         "Name": str,
         "DeploymentDurationInMinutes": int,
         "GrowthFactor": float,
     },
@@ -228,37 +240,41 @@
         "GrowthType": GrowthTypeType,
         "ReplicateTo": ReplicateToType,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateDeploymentStrategyRequestRequestTypeDef(
     _RequiredCreateDeploymentStrategyRequestRequestTypeDef,
     _OptionalCreateDeploymentStrategyRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredMonitorTypeDef = TypedDict(
     "_RequiredMonitorTypeDef",
     {
         "AlarmArn": str,
     },
 )
 _OptionalMonitorTypeDef = TypedDict(
     "_OptionalMonitorTypeDef",
     {
         "AlarmRoleArn": str,
     },
     total=False,
 )
 
+
 class MonitorTypeDef(_RequiredMonitorTypeDef, _OptionalMonitorTypeDef):
     pass
 
+
 _RequiredCreateExtensionAssociationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateExtensionAssociationRequestRequestTypeDef",
     {
         "ExtensionIdentifier": str,
         "ResourceIdentifier": str,
     },
 )
@@ -268,20 +284,22 @@
         "ExtensionVersionNumber": int,
         "Parameters": Mapping[str, str],
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateExtensionAssociationRequestRequestTypeDef(
     _RequiredCreateExtensionAssociationRequestRequestTypeDef,
     _OptionalCreateExtensionAssociationRequestRequestTypeDef,
 ):
     pass
 
+
 ParameterTypeDef = TypedDict(
     "ParameterTypeDef",
     {
         "Description": str,
         "Required": bool,
     },
     total=False,
@@ -302,20 +320,22 @@
         "Description": str,
         "LatestVersionNumber": int,
         "VersionLabel": str,
     },
     total=False,
 )
 
+
 class CreateHostedConfigurationVersionRequestRequestTypeDef(
     _RequiredCreateHostedConfigurationVersionRequestRequestTypeDef,
     _OptionalCreateHostedConfigurationVersionRequestRequestTypeDef,
 ):
     pass
 
+
 DeleteApplicationRequestRequestTypeDef = TypedDict(
     "DeleteApplicationRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
@@ -359,19 +379,21 @@
     "_OptionalDeleteExtensionRequestRequestTypeDef",
     {
         "VersionNumber": int,
     },
     total=False,
 )
 
+
 class DeleteExtensionRequestRequestTypeDef(
     _RequiredDeleteExtensionRequestRequestTypeDef, _OptionalDeleteExtensionRequestRequestTypeDef
 ):
     pass
 
+
 DeleteHostedConfigurationVersionRequestRequestTypeDef = TypedDict(
     "DeleteHostedConfigurationVersionRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "ConfigurationProfileId": str,
         "VersionNumber": int,
     },
@@ -388,14 +410,29 @@
         "GrowthFactor": float,
         "FinalBakeTimeInMinutes": int,
         "ReplicateTo": ReplicateToType,
     },
     total=False,
 )
 
+DeploymentStrategyResponseMetadataTypeDef = TypedDict(
+    "DeploymentStrategyResponseMetadataTypeDef",
+    {
+        "Id": str,
+        "Name": str,
+        "Description": str,
+        "DeploymentDurationInMinutes": int,
+        "GrowthType": GrowthTypeType,
+        "GrowthFactor": float,
+        "FinalBakeTimeInMinutes": int,
+        "ReplicateTo": ReplicateToType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeploymentSummaryTypeDef = TypedDict(
     "DeploymentSummaryTypeDef",
     {
         "DeploymentNumber": int,
         "ConfigurationName": str,
         "ConfigurationVersion": str,
         "DeploymentDurationInMinutes": int,
@@ -406,24 +443,44 @@
         "PercentageComplete": float,
         "StartedAt": datetime,
         "CompletedAt": datetime,
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
 ExtensionAssociationSummaryTypeDef = TypedDict(
     "ExtensionAssociationSummaryTypeDef",
     {
         "Id": str,
         "ExtensionArn": str,
         "ResourceArn": str,
     },
     total=False,
 )
 
+ExtensionAssociationTypeDef = TypedDict(
+    "ExtensionAssociationTypeDef",
+    {
+        "Id": str,
+        "ExtensionArn": str,
+        "ResourceArn": str,
+        "Arn": str,
+        "Parameters": Dict[str, str],
+        "ExtensionVersionNumber": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExtensionSummaryTypeDef = TypedDict(
     "ExtensionSummaryTypeDef",
     {
         "Id": str,
         "Name": str,
         "VersionNumber": int,
         "Arn": str,
@@ -460,19 +517,21 @@
     "_OptionalGetConfigurationRequestRequestTypeDef",
     {
         "ClientConfigurationVersion": str,
     },
     total=False,
 )
 
+
 class GetConfigurationRequestRequestTypeDef(
     _RequiredGetConfigurationRequestRequestTypeDef, _OptionalGetConfigurationRequestRequestTypeDef
 ):
     pass
 
+
 GetDeploymentRequestRequestTypeDef = TypedDict(
     "GetDeploymentRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "EnvironmentId": str,
         "DeploymentNumber": int,
     },
@@ -510,19 +569,21 @@
     "_OptionalGetExtensionRequestRequestTypeDef",
     {
         "VersionNumber": int,
     },
     total=False,
 )
 
+
 class GetExtensionRequestRequestTypeDef(
     _RequiredGetExtensionRequestRequestTypeDef, _OptionalGetExtensionRequestRequestTypeDef
 ):
     pass
 
+
 GetHostedConfigurationVersionRequestRequestTypeDef = TypedDict(
     "GetHostedConfigurationVersionRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "ConfigurationProfileId": str,
         "VersionNumber": int,
     },
@@ -537,14 +598,28 @@
         "Description": str,
         "ContentType": str,
         "VersionLabel": str,
     },
     total=False,
 )
 
+HostedConfigurationVersionTypeDef = TypedDict(
+    "HostedConfigurationVersionTypeDef",
+    {
+        "ApplicationId": str,
+        "ConfigurationProfileId": str,
+        "VersionNumber": int,
+        "Description": str,
+        "Content": StreamingBody,
+        "ContentType": str,
+        "VersionLabel": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -562,20 +637,22 @@
         "MaxResults": int,
         "NextToken": str,
         "Type": str,
     },
     total=False,
 )
 
+
 class ListConfigurationProfilesRequestRequestTypeDef(
     _RequiredListConfigurationProfilesRequestRequestTypeDef,
     _OptionalListConfigurationProfilesRequestRequestTypeDef,
 ):
     pass
 
+
 ListDeploymentStrategiesRequestRequestTypeDef = TypedDict(
     "ListDeploymentStrategiesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -593,19 +670,21 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListDeploymentsRequestRequestTypeDef(
     _RequiredListDeploymentsRequestRequestTypeDef, _OptionalListDeploymentsRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredListEnvironmentsRequestRequestTypeDef = TypedDict(
     "_RequiredListEnvironmentsRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 _OptionalListEnvironmentsRequestRequestTypeDef = TypedDict(
@@ -613,19 +692,21 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListEnvironmentsRequestRequestTypeDef(
     _RequiredListEnvironmentsRequestRequestTypeDef, _OptionalListEnvironmentsRequestRequestTypeDef
 ):
     pass
 
+
 ListExtensionAssociationsRequestRequestTypeDef = TypedDict(
     "ListExtensionAssociationsRequestRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "ExtensionIdentifier": str,
         "ExtensionVersionNumber": int,
         "MaxResults": int,
@@ -657,27 +738,48 @@
         "MaxResults": int,
         "NextToken": str,
         "VersionLabel": str,
     },
     total=False,
 )
 
+
 class ListHostedConfigurationVersionsRequestRequestTypeDef(
     _RequiredListHostedConfigurationVersionsRequestRequestTypeDef,
     _OptionalListHostedConfigurationVersionsRequestRequestTypeDef,
 ):
     pass
 
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ResourceTagsTypeDef = TypedDict(
+    "ResourceTagsTypeDef",
+    {
+        "Tags": Dict[str, str],
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
 _RequiredStartDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredStartDeploymentRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "EnvironmentId": str,
         "DeploymentStrategyId": str,
         "ConfigurationProfileId": str,
@@ -690,19 +792,21 @@
         "Description": str,
         "Tags": Mapping[str, str],
         "KmsKeyIdentifier": str,
     },
     total=False,
 )
 
+
 class StartDeploymentRequestRequestTypeDef(
     _RequiredStartDeploymentRequestRequestTypeDef, _OptionalStartDeploymentRequestRequestTypeDef
 ):
     pass
 
+
 StopDeploymentRequestRequestTypeDef = TypedDict(
     "StopDeploymentRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "EnvironmentId": str,
         "DeploymentNumber": int,
     },
@@ -735,19 +839,21 @@
     {
         "Name": str,
         "Description": str,
     },
     total=False,
 )
 
+
 class UpdateApplicationRequestRequestTypeDef(
     _RequiredUpdateApplicationRequestRequestTypeDef, _OptionalUpdateApplicationRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateDeploymentStrategyRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDeploymentStrategyRequestRequestTypeDef",
     {
         "DeploymentStrategyId": str,
     },
 )
 _OptionalUpdateDeploymentStrategyRequestRequestTypeDef = TypedDict(
@@ -758,40 +864,44 @@
         "FinalBakeTimeInMinutes": int,
         "GrowthFactor": float,
         "GrowthType": GrowthTypeType,
     },
     total=False,
 )
 
+
 class UpdateDeploymentStrategyRequestRequestTypeDef(
     _RequiredUpdateDeploymentStrategyRequestRequestTypeDef,
     _OptionalUpdateDeploymentStrategyRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateExtensionAssociationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateExtensionAssociationRequestRequestTypeDef",
     {
         "ExtensionAssociationId": str,
     },
 )
 _OptionalUpdateExtensionAssociationRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateExtensionAssociationRequestRequestTypeDef",
     {
         "Parameters": Mapping[str, str],
     },
     total=False,
 )
 
+
 class UpdateExtensionAssociationRequestRequestTypeDef(
     _RequiredUpdateExtensionAssociationRequestRequestTypeDef,
     _OptionalUpdateExtensionAssociationRequestRequestTypeDef,
 ):
     pass
 
+
 ValidateConfigurationRequestRequestTypeDef = TypedDict(
     "ValidateConfigurationRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "ConfigurationProfileId": str,
         "ConfigurationVersion": str,
     },
@@ -805,121 +915,44 @@
         "Description": str,
         "ActionInvocations": List[ActionInvocationTypeDef],
         "OccurredAt": datetime,
     },
     total=False,
 )
 
-ApplicationResponseMetadataTypeDef = TypedDict(
-    "ApplicationResponseMetadataTypeDef",
-    {
-        "Id": str,
-        "Name": str,
-        "Description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConfigurationTypeDef = TypedDict(
-    "ConfigurationTypeDef",
-    {
-        "Content": StreamingBody,
-        "ConfigurationVersion": str,
-        "ContentType": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeploymentStrategyResponseMetadataTypeDef = TypedDict(
-    "DeploymentStrategyResponseMetadataTypeDef",
-    {
-        "Id": str,
-        "Name": str,
-        "Description": str,
-        "DeploymentDurationInMinutes": int,
-        "GrowthType": GrowthTypeType,
-        "GrowthFactor": float,
-        "FinalBakeTimeInMinutes": int,
-        "ReplicateTo": ReplicateToType,
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
-ExtensionAssociationTypeDef = TypedDict(
-    "ExtensionAssociationTypeDef",
-    {
-        "Id": str,
-        "ExtensionArn": str,
-        "ResourceArn": str,
-        "Arn": str,
-        "Parameters": Dict[str, str],
-        "ExtensionVersionNumber": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-HostedConfigurationVersionTypeDef = TypedDict(
-    "HostedConfigurationVersionTypeDef",
-    {
-        "ApplicationId": str,
-        "ConfigurationProfileId": str,
-        "VersionNumber": int,
-        "Description": str,
-        "Content": StreamingBody,
-        "ContentType": str,
-        "VersionLabel": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ResourceTagsTypeDef = TypedDict(
-    "ResourceTagsTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ApplicationsTypeDef = TypedDict(
     "ApplicationsTypeDef",
     {
         "Items": List[ApplicationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConfigurationProfilesTypeDef = TypedDict(
     "ConfigurationProfilesTypeDef",
     {
         "Items": List[ConfigurationProfileSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConfigurationProfileTypeDef = TypedDict(
     "ConfigurationProfileTypeDef",
     {
         "ApplicationId": str,
         "Id": str,
         "Name": str,
         "Description": str,
         "LocationUri": str,
         "RetrievalRoleArn": str,
         "Validators": List[ValidatorTypeDef],
         "Type": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateConfigurationProfileRequestRequestTypeDef = TypedDict(
     "_RequiredCreateConfigurationProfileRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -935,20 +968,22 @@
         "Validators": Sequence[ValidatorTypeDef],
         "Tags": Mapping[str, str],
         "Type": str,
     },
     total=False,
 )
 
+
 class CreateConfigurationProfileRequestRequestTypeDef(
     _RequiredCreateConfigurationProfileRequestRequestTypeDef,
     _OptionalCreateConfigurationProfileRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateConfigurationProfileRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateConfigurationProfileRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "ConfigurationProfileId": str,
     },
 )
@@ -959,20 +994,22 @@
         "Description": str,
         "RetrievalRoleArn": str,
         "Validators": Sequence[ValidatorTypeDef],
     },
     total=False,
 )
 
+
 class UpdateConfigurationProfileRequestRequestTypeDef(
     _RequiredUpdateConfigurationProfileRequestRequestTypeDef,
     _OptionalUpdateConfigurationProfileRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateEnvironmentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEnvironmentRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "Name": str,
     },
 )
@@ -982,29 +1019,31 @@
         "Description": str,
         "Monitors": Sequence[MonitorTypeDef],
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateEnvironmentRequestRequestTypeDef(
     _RequiredCreateEnvironmentRequestRequestTypeDef, _OptionalCreateEnvironmentRequestRequestTypeDef
 ):
     pass
 
+
 EnvironmentResponseMetadataTypeDef = TypedDict(
     "EnvironmentResponseMetadataTypeDef",
     {
         "ApplicationId": str,
         "Id": str,
         "Name": str,
         "Description": str,
         "State": EnvironmentStateType,
         "Monitors": List[MonitorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentTypeDef = TypedDict(
     "EnvironmentTypeDef",
     {
         "ApplicationId": str,
@@ -1030,19 +1069,21 @@
         "Name": str,
         "Description": str,
         "Monitors": Sequence[MonitorTypeDef],
     },
     total=False,
 )
 
+
 class UpdateEnvironmentRequestRequestTypeDef(
     _RequiredUpdateEnvironmentRequestRequestTypeDef, _OptionalUpdateEnvironmentRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateExtensionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateExtensionRequestRequestTypeDef",
     {
         "Name": str,
         "Actions": Mapping[ActionPointType, Sequence[ActionTypeDef]],
     },
 )
@@ -1053,30 +1094,32 @@
         "Parameters": Mapping[str, ParameterTypeDef],
         "Tags": Mapping[str, str],
         "LatestVersionNumber": int,
     },
     total=False,
 )
 
+
 class CreateExtensionRequestRequestTypeDef(
     _RequiredCreateExtensionRequestRequestTypeDef, _OptionalCreateExtensionRequestRequestTypeDef
 ):
     pass
 
+
 ExtensionTypeDef = TypedDict(
     "ExtensionTypeDef",
     {
         "Id": str,
         "Name": str,
         "VersionNumber": int,
         "Arn": str,
         "Description": str,
         "Actions": Dict[ActionPointType, List[ActionTypeDef]],
         "Parameters": Dict[str, ParameterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateExtensionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateExtensionRequestRequestTypeDef",
     {
         "ExtensionIdentifier": str,
@@ -1089,61 +1132,63 @@
         "Actions": Mapping[ActionPointType, Sequence[ActionTypeDef]],
         "Parameters": Mapping[str, ParameterTypeDef],
         "VersionNumber": int,
     },
     total=False,
 )
 
+
 class UpdateExtensionRequestRequestTypeDef(
     _RequiredUpdateExtensionRequestRequestTypeDef, _OptionalUpdateExtensionRequestRequestTypeDef
 ):
     pass
 
+
 DeploymentStrategiesTypeDef = TypedDict(
     "DeploymentStrategiesTypeDef",
     {
         "Items": List[DeploymentStrategyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploymentsTypeDef = TypedDict(
     "DeploymentsTypeDef",
     {
         "Items": List[DeploymentSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExtensionAssociationsTypeDef = TypedDict(
     "ExtensionAssociationsTypeDef",
     {
         "Items": List[ExtensionAssociationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExtensionsTypeDef = TypedDict(
     "ExtensionsTypeDef",
     {
         "Items": List[ExtensionSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 HostedConfigurationVersionsTypeDef = TypedDict(
     "HostedConfigurationVersionsTypeDef",
     {
         "Items": List[HostedConfigurationVersionSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploymentTypeDef = TypedDict(
     "DeploymentTypeDef",
     {
         "ApplicationId": str,
@@ -1163,19 +1208,19 @@
         "EventLog": List[DeploymentEventTypeDef],
         "PercentageComplete": float,
         "StartedAt": datetime,
         "CompletedAt": datetime,
         "AppliedExtensions": List[AppliedExtensionTypeDef],
         "KmsKeyArn": str,
         "KmsKeyIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentsTypeDef = TypedDict(
     "EnvironmentsTypeDef",
     {
         "Items": List[EnvironmentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig.egg-info/PKG-INFO` & `types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-appconfig
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AppConfig 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AppConfig 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appconfig/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-appconfig"></a>
 
 # types-aiobotocore-appconfig
 
 [![PyPI - types-aiobotocore-appconfig](https://img.shields.io/pypi/v/types-aiobotocore-appconfig.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appconfig)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appconfig.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appconfig)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appconfig/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appconfig?color=blue)](https://pypistats.org/packages/types-aiobotocore-appconfig)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppConfig 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appconfig.html#AppConfig)
+[aiobotocore.AppConfig 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appconfig.html#AppConfig)
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
 [types-aiobotocore-appconfig docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appconfig/).
 
 See how it helps to find and fix potential bugs:
 
@@ -299,71 +299,71 @@
 `types_aiobotocore_appconfig.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_appconfig.type_defs import (
     ActionInvocationTypeDef,
     ActionTypeDef,
-    ResponseMetadataTypeDef,
+    ApplicationResponseMetadataTypeDef,
     ApplicationTypeDef,
     AppliedExtensionTypeDef,
     ConfigurationProfileSummaryTypeDef,
     ValidatorTypeDef,
+    ConfigurationTypeDef,
     CreateApplicationRequestRequestTypeDef,
     CreateDeploymentStrategyRequestRequestTypeDef,
     MonitorTypeDef,
     CreateExtensionAssociationRequestRequestTypeDef,
     ParameterTypeDef,
     CreateHostedConfigurationVersionRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteConfigurationProfileRequestRequestTypeDef,
     DeleteDeploymentStrategyRequestRequestTypeDef,
     DeleteEnvironmentRequestRequestTypeDef,
     DeleteExtensionAssociationRequestRequestTypeDef,
     DeleteExtensionRequestRequestTypeDef,
     DeleteHostedConfigurationVersionRequestRequestTypeDef,
     DeploymentStrategyTypeDef,
+    DeploymentStrategyResponseMetadataTypeDef,
     DeploymentSummaryTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExtensionAssociationSummaryTypeDef,
+    ExtensionAssociationTypeDef,
     ExtensionSummaryTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetConfigurationProfileRequestRequestTypeDef,
     GetConfigurationRequestRequestTypeDef,
     GetDeploymentRequestRequestTypeDef,
     GetDeploymentStrategyRequestRequestTypeDef,
     GetEnvironmentRequestRequestTypeDef,
     GetExtensionAssociationRequestRequestTypeDef,
     GetExtensionRequestRequestTypeDef,
     GetHostedConfigurationVersionRequestRequestTypeDef,
     HostedConfigurationVersionSummaryTypeDef,
+    HostedConfigurationVersionTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListConfigurationProfilesRequestRequestTypeDef,
     ListDeploymentStrategiesRequestRequestTypeDef,
     ListDeploymentsRequestRequestTypeDef,
     ListEnvironmentsRequestRequestTypeDef,
     ListExtensionAssociationsRequestRequestTypeDef,
     ListExtensionsRequestRequestTypeDef,
     ListHostedConfigurationVersionsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ResourceTagsTypeDef,
+    ResponseMetadataTypeDef,
     StartDeploymentRequestRequestTypeDef,
     StopDeploymentRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     UpdateDeploymentStrategyRequestRequestTypeDef,
     UpdateExtensionAssociationRequestRequestTypeDef,
     ValidateConfigurationRequestRequestTypeDef,
     DeploymentEventTypeDef,
-    ApplicationResponseMetadataTypeDef,
-    ConfigurationTypeDef,
-    DeploymentStrategyResponseMetadataTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExtensionAssociationTypeDef,
-    HostedConfigurationVersionTypeDef,
-    ResourceTagsTypeDef,
     ApplicationsTypeDef,
     ConfigurationProfilesTypeDef,
     ConfigurationProfileTypeDef,
     CreateConfigurationProfileRequestRequestTypeDef,
     UpdateConfigurationProfileRequestRequestTypeDef,
     CreateEnvironmentRequestRequestTypeDef,
     EnvironmentResponseMetadataTypeDef,
@@ -389,43 +389,43 @@
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

### Comparing `types-aiobotocore-appconfig-2.5.0.post1/types_aiobotocore_appconfig.egg-info/SOURCES.txt` & `types-aiobotocore-appconfig-2.5.1/types_aiobotocore_appconfig.egg-info/SOURCES.txt`

 * *Files identical despite different names*


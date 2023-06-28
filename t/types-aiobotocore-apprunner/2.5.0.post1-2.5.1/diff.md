# Comparing `tmp/types-aiobotocore-apprunner-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-apprunner-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-apprunner-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:12 2023, max compression
+gzip compressed data, was "types-aiobotocore-apprunner-2.5.1.tar", last modified: Wed Jun 28 01:43:06 2023, max compression
```

## Comparing `types-aiobotocore-apprunner-2.5.0.post1.tar` & `types-aiobotocore-apprunner-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.722948 types-aiobotocore-apprunner-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:43.000000 types-aiobotocore-apprunner-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16900 2023-03-11 12:26:12.718948 types-aiobotocore-apprunner-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15321 2023-03-11 12:09:43.000000 types-aiobotocore-apprunner-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:12.722948 types-aiobotocore-apprunner-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:09:43.000000 types-aiobotocore-apprunner-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.718948 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/
--rw-r--r--   0 runner    (1001) docker     (123)      458 2023-03-11 12:09:43.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      457 2023-03-11 12:09:43.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:09:43.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27528 2023-03-11 12:09:43.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    27484 2023-03-11 12:09:43.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9782 2023-03-11 12:09:44.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9780 2023-03-11 12:09:43.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:43.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    35601 2023-03-11 12:09:44.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    35566 2023-03-11 12:09:44.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:43.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.718948 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16900 2023-03-11 12:26:12.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      768 2023-03-11 12:26:12.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:12.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:26:12.000000 types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.550094 types-aiobotocore-apprunner-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:20.000000 types-aiobotocore-apprunner-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16894 2023-06-28 01:43:06.550094 types-aiobotocore-apprunner-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15321 2023-06-28 01:26:20.000000 types-aiobotocore-apprunner-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:06.550094 types-aiobotocore-apprunner-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:26:20.000000 types-aiobotocore-apprunner-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.546094 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/
+-rw-r--r--   0 runner    (1001) docker     (123)      458 2023-06-28 01:26:20.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      457 2023-06-28 01:26:20.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:26:20.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27528 2023-06-28 01:26:20.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27484 2023-06-28 01:26:20.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10078 2023-06-28 01:26:20.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10076 2023-06-28 01:26:20.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:20.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    35667 2023-06-28 01:26:21.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35632 2023-06-28 01:26:21.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:20.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.550094 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16894 2023-06-28 01:43:06.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      768 2023-06-28 01:43:06.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:06.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:43:06.000000 types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-apprunner-2.5.0.post1/LICENSE` & `types-aiobotocore-apprunner-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-apprunner-2.5.0.post1/PKG-INFO` & `types-aiobotocore-apprunner-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-apprunner
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AppRunner 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AppRunner 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apprunner/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-apprunner"></a>
 
 # types-aiobotocore-apprunner
 
 [![PyPI - types-aiobotocore-apprunner](https://img.shields.io/pypi/v/types-aiobotocore-apprunner.svg?color=blue)](https://pypi.org/project/types-aiobotocore-apprunner)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-apprunner.svg?color=blue)](https://pypi.org/project/types-aiobotocore-apprunner)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apprunner/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-apprunner?color=blue)](https://pypistats.org/packages/types-aiobotocore-apprunner)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppRunner 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apprunner.html#AppRunner)
+[aiobotocore.AppRunner 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apprunner.html#AppRunner)
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
 [types-aiobotocore-apprunner docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apprunner/).
 
 See how it helps to find and fix potential bugs:
 
@@ -308,15 +308,14 @@
 
 `types_aiobotocore_apprunner.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_apprunner.type_defs import (
     AssociateCustomDomainRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     VpcDNSTargetTypeDef,
     AuthenticationConfigurationTypeDef,
     AutoScalingConfigurationSummaryTypeDef,
     AutoScalingConfigurationTypeDef,
     CertificateValidationRecordTypeDef,
     CodeConfigurationValuesTypeDef,
     SourceCodeVersionTypeDef,
@@ -355,18 +354,19 @@
     ListServicesRequestRequestTypeDef,
     ServiceSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListVpcConnectorsRequestRequestTypeDef,
     ListVpcIngressConnectionsFilterTypeDef,
     VpcIngressConnectionSummaryTypeDef,
     PauseServiceRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ResumeServiceRequestRequestTypeDef,
     StartDeploymentRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
     StartDeploymentResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
     ListAutoScalingConfigurationsResponseTypeDef,
     CreateAutoScalingConfigurationResponseTypeDef,
     DeleteAutoScalingConfigurationResponseTypeDef,
     DescribeAutoScalingConfigurationResponseTypeDef,
     CustomDomainTypeDef,
     CodeConfigurationTypeDef,
     ListConnectionsResponseTypeDef,
@@ -424,43 +424,43 @@
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

### Comparing `types-aiobotocore-apprunner-2.5.0.post1/README.md` & `types-aiobotocore-apprunner-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-apprunner"></a>
 
 # types-aiobotocore-apprunner
 
 [![PyPI - types-aiobotocore-apprunner](https://img.shields.io/pypi/v/types-aiobotocore-apprunner.svg?color=blue)](https://pypi.org/project/types-aiobotocore-apprunner)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-apprunner.svg?color=blue)](https://pypi.org/project/types-aiobotocore-apprunner)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apprunner/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-apprunner?color=blue)](https://pypistats.org/packages/types-aiobotocore-apprunner)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppRunner 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apprunner.html#AppRunner)
+[aiobotocore.AppRunner 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apprunner.html#AppRunner)
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
 [types-aiobotocore-apprunner docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apprunner/).
 
 See how it helps to find and fix potential bugs:
 
@@ -275,15 +275,14 @@
 
 `types_aiobotocore_apprunner.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_apprunner.type_defs import (
     AssociateCustomDomainRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     VpcDNSTargetTypeDef,
     AuthenticationConfigurationTypeDef,
     AutoScalingConfigurationSummaryTypeDef,
     AutoScalingConfigurationTypeDef,
     CertificateValidationRecordTypeDef,
     CodeConfigurationValuesTypeDef,
     SourceCodeVersionTypeDef,
@@ -322,18 +321,19 @@
     ListServicesRequestRequestTypeDef,
     ServiceSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListVpcConnectorsRequestRequestTypeDef,
     ListVpcIngressConnectionsFilterTypeDef,
     VpcIngressConnectionSummaryTypeDef,
     PauseServiceRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ResumeServiceRequestRequestTypeDef,
     StartDeploymentRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
     StartDeploymentResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
     ListAutoScalingConfigurationsResponseTypeDef,
     CreateAutoScalingConfigurationResponseTypeDef,
     DeleteAutoScalingConfigurationResponseTypeDef,
     DescribeAutoScalingConfigurationResponseTypeDef,
     CustomDomainTypeDef,
     CodeConfigurationTypeDef,
     ListConnectionsResponseTypeDef,
@@ -391,43 +391,43 @@
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

### Comparing `types-aiobotocore-apprunner-2.5.0.post1/setup.py` & `types-aiobotocore-apprunner-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-apprunner.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-apprunner",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_apprunner"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.AppRunner 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.AppRunner 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apprunner/"
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

### Comparing `types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/__main__.py` & `types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.AppRunner 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.AppRunner 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apprunner//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apprunner.html#AppRunner\nOther"
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

### Comparing `types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/client.py` & `types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/client.pyi` & `types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/literals.py` & `types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "AutoScalingConfigurationStatusType",
     "CertificateValidationRecordStatusType",
     "ConfigurationSourceType",
     "ConnectionStatusType",
     "CustomDomainAssociationStatusType",
     "EgressTypeType",
@@ -40,15 +39,14 @@
     "VpcIngressConnectionStatusType",
     "AppRunnerServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 AutoScalingConfigurationStatusType = Literal["ACTIVE", "INACTIVE"]
 CertificateValidationRecordStatusType = Literal["FAILED", "PENDING_VALIDATION", "SUCCESS"]
 ConfigurationSourceType = Literal["API", "REPOSITORY"]
 ConnectionStatusType = Literal["AVAILABLE", "DELETED", "ERROR", "PENDING_HANDSHAKE"]
 CustomDomainAssociationStatusType = Literal[
     "ACTIVE",
     "BINDING_CERTIFICATE",
@@ -167,14 +165,15 @@
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
@@ -253,14 +252,15 @@
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
@@ -271,14 +271,15 @@
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
@@ -314,14 +315,15 @@
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
@@ -340,16 +342,19 @@
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
@@ -433,15 +438,17 @@
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
@@ -459,8 +466,17 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
-RegionName = Literal["ap-northeast-1", "eu-west-1", "us-east-1", "us-east-2", "us-west-2"]
+RegionName = Literal[
+    "ap-northeast-1",
+    "ap-southeast-1",
+    "ap-southeast-2",
+    "eu-central-1",
+    "eu-west-1",
+    "us-east-1",
+    "us-east-2",
+    "us-west-2",
+]
```

### Comparing `types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/literals.pyi` & `types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "AutoScalingConfigurationStatusType",
     "CertificateValidationRecordStatusType",
     "ConfigurationSourceType",
     "ConnectionStatusType",
     "CustomDomainAssociationStatusType",
     "EgressTypeType",
@@ -39,14 +40,15 @@
     "VpcIngressConnectionStatusType",
     "AppRunnerServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 AutoScalingConfigurationStatusType = Literal["ACTIVE", "INACTIVE"]
 CertificateValidationRecordStatusType = Literal["FAILED", "PENDING_VALIDATION", "SUCCESS"]
 ConfigurationSourceType = Literal["API", "REPOSITORY"]
 ConnectionStatusType = Literal["AVAILABLE", "DELETED", "ERROR", "PENDING_HANDSHAKE"]
 CustomDomainAssociationStatusType = Literal[
     "ACTIVE",
     "BINDING_CERTIFICATE",
@@ -165,14 +167,15 @@
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
@@ -251,14 +254,15 @@
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
@@ -269,14 +273,15 @@
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
@@ -312,14 +317,15 @@
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
@@ -338,16 +344,19 @@
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
@@ -431,15 +440,17 @@
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
@@ -457,8 +468,17 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
-RegionName = Literal["ap-northeast-1", "eu-west-1", "us-east-1", "us-east-2", "us-west-2"]
+RegionName = Literal[
+    "ap-northeast-1",
+    "ap-southeast-1",
+    "ap-southeast-2",
+    "eu-central-1",
+    "eu-west-1",
+    "us-east-1",
+    "us-east-2",
+    "us-west-2",
+]
```

### Comparing `types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/type_defs.py` & `types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -41,15 +41,14 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AssociateCustomDomainRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "VpcDNSTargetTypeDef",
     "AuthenticationConfigurationTypeDef",
     "AutoScalingConfigurationSummaryTypeDef",
     "AutoScalingConfigurationTypeDef",
     "CertificateValidationRecordTypeDef",
     "CodeConfigurationValuesTypeDef",
     "SourceCodeVersionTypeDef",
@@ -88,18 +87,19 @@
     "ListServicesRequestRequestTypeDef",
     "ServiceSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ListVpcConnectorsRequestRequestTypeDef",
     "ListVpcIngressConnectionsFilterTypeDef",
     "VpcIngressConnectionSummaryTypeDef",
     "PauseServiceRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "ResumeServiceRequestRequestTypeDef",
     "StartDeploymentRequestRequestTypeDef",
-    "UntagResourceRequestRequestTypeDef",
     "StartDeploymentResponseTypeDef",
+    "UntagResourceRequestRequestTypeDef",
     "ListAutoScalingConfigurationsResponseTypeDef",
     "CreateAutoScalingConfigurationResponseTypeDef",
     "DeleteAutoScalingConfigurationResponseTypeDef",
     "DescribeAutoScalingConfigurationResponseTypeDef",
     "CustomDomainTypeDef",
     "CodeConfigurationTypeDef",
     "ListConnectionsResponseTypeDef",
@@ -168,25 +168,14 @@
 class AssociateCustomDomainRequestRequestTypeDef(
     _RequiredAssociateCustomDomainRequestRequestTypeDef,
     _OptionalAssociateCustomDomainRequestRequestTypeDef,
 ):
     pass
 
 
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
 VpcDNSTargetTypeDef = TypedDict(
     "VpcDNSTargetTypeDef",
     {
         "VpcIngressConnectionArn": str,
         "VpcId": str,
         "DomainName": str,
     },
@@ -663,74 +652,85 @@
 PauseServiceRequestRequestTypeDef = TypedDict(
     "PauseServiceRequestRequestTypeDef",
     {
         "ServiceArn": str,
     },
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
 ResumeServiceRequestRequestTypeDef = TypedDict(
     "ResumeServiceRequestRequestTypeDef",
     {
         "ServiceArn": str,
     },
 )
 
 StartDeploymentRequestRequestTypeDef = TypedDict(
     "StartDeploymentRequestRequestTypeDef",
     {
         "ServiceArn": str,
     },
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
+StartDeploymentResponseTypeDef = TypedDict(
+    "StartDeploymentResponseTypeDef",
     {
-        "ResourceArn": str,
-        "TagKeys": Sequence[str],
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartDeploymentResponseTypeDef = TypedDict(
-    "StartDeploymentResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "TagKeys": Sequence[str],
     },
 )
 
 ListAutoScalingConfigurationsResponseTypeDef = TypedDict(
     "ListAutoScalingConfigurationsResponseTypeDef",
     {
         "AutoScalingConfigurationSummaryList": List[AutoScalingConfigurationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAutoScalingConfigurationResponseTypeDef = TypedDict(
     "CreateAutoScalingConfigurationResponseTypeDef",
     {
         "AutoScalingConfiguration": AutoScalingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAutoScalingConfigurationResponseTypeDef = TypedDict(
     "DeleteAutoScalingConfigurationResponseTypeDef",
     {
         "AutoScalingConfiguration": AutoScalingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAutoScalingConfigurationResponseTypeDef = TypedDict(
     "DescribeAutoScalingConfigurationResponseTypeDef",
     {
         "AutoScalingConfiguration": AutoScalingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCustomDomainTypeDef = TypedDict(
     "_RequiredCustomDomainTypeDef",
     {
         "DomainName": str,
@@ -773,31 +773,31 @@
 
 
 ListConnectionsResponseTypeDef = TypedDict(
     "ListConnectionsResponseTypeDef",
     {
         "ConnectionSummaryList": List[ConnectionSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateConnectionResponseTypeDef = TypedDict(
     "CreateConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteConnectionResponseTypeDef = TypedDict(
     "DeleteConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateAutoScalingConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAutoScalingConfigurationRequestRequestTypeDef",
     {
         "AutoScalingConfigurationName": str,
@@ -868,15 +868,15 @@
     pass
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -922,40 +922,40 @@
     total=False,
 )
 
 CreateVpcConnectorResponseTypeDef = TypedDict(
     "CreateVpcConnectorResponseTypeDef",
     {
         "VpcConnector": VpcConnectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVpcConnectorResponseTypeDef = TypedDict(
     "DeleteVpcConnectorResponseTypeDef",
     {
         "VpcConnector": VpcConnectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVpcConnectorResponseTypeDef = TypedDict(
     "DescribeVpcConnectorResponseTypeDef",
     {
         "VpcConnector": VpcConnectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcConnectorsResponseTypeDef = TypedDict(
     "ListVpcConnectorsResponseTypeDef",
     {
         "VpcConnectors": List[VpcConnectorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateVpcIngressConnectionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateVpcIngressConnectionRequestRequestTypeDef",
     {
         "ServiceArn": str,
@@ -1033,33 +1033,33 @@
 )
 
 ListObservabilityConfigurationsResponseTypeDef = TypedDict(
     "ListObservabilityConfigurationsResponseTypeDef",
     {
         "ObservabilityConfigurationSummaryList": List[ObservabilityConfigurationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOperationsResponseTypeDef = TypedDict(
     "ListOperationsResponseTypeDef",
     {
         "OperationSummaryList": List[OperationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServicesResponseTypeDef = TypedDict(
     "ListServicesResponseTypeDef",
     {
         "ServiceSummaryList": List[ServiceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcIngressConnectionsRequestRequestTypeDef = TypedDict(
     "ListVpcIngressConnectionsRequestRequestTypeDef",
     {
         "Filter": ListVpcIngressConnectionsFilterTypeDef,
@@ -1070,49 +1070,49 @@
 )
 
 ListVpcIngressConnectionsResponseTypeDef = TypedDict(
     "ListVpcIngressConnectionsResponseTypeDef",
     {
         "VpcIngressConnectionSummaryList": List[VpcIngressConnectionSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateCustomDomainResponseTypeDef = TypedDict(
     "AssociateCustomDomainResponseTypeDef",
     {
         "DNSTarget": str,
         "ServiceArn": str,
         "CustomDomain": CustomDomainTypeDef,
         "VpcDNSTargets": List[VpcDNSTargetTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCustomDomainsResponseTypeDef = TypedDict(
     "DescribeCustomDomainsResponseTypeDef",
     {
         "DNSTarget": str,
         "ServiceArn": str,
         "CustomDomains": List[CustomDomainTypeDef],
         "VpcDNSTargets": List[VpcDNSTargetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateCustomDomainResponseTypeDef = TypedDict(
     "DisassociateCustomDomainResponseTypeDef",
     {
         "DNSTarget": str,
         "ServiceArn": str,
         "CustomDomain": CustomDomainTypeDef,
         "VpcDNSTargets": List[VpcDNSTargetTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCodeRepositoryTypeDef = TypedDict(
     "_RequiredCodeRepositoryTypeDef",
     {
         "RepositoryUrl": str,
@@ -1132,63 +1132,63 @@
     pass
 
 
 CreateObservabilityConfigurationResponseTypeDef = TypedDict(
     "CreateObservabilityConfigurationResponseTypeDef",
     {
         "ObservabilityConfiguration": ObservabilityConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteObservabilityConfigurationResponseTypeDef = TypedDict(
     "DeleteObservabilityConfigurationResponseTypeDef",
     {
         "ObservabilityConfiguration": ObservabilityConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeObservabilityConfigurationResponseTypeDef = TypedDict(
     "DescribeObservabilityConfigurationResponseTypeDef",
     {
         "ObservabilityConfiguration": ObservabilityConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVpcIngressConnectionResponseTypeDef = TypedDict(
     "CreateVpcIngressConnectionResponseTypeDef",
     {
         "VpcIngressConnection": VpcIngressConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVpcIngressConnectionResponseTypeDef = TypedDict(
     "DeleteVpcIngressConnectionResponseTypeDef",
     {
         "VpcIngressConnection": VpcIngressConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVpcIngressConnectionResponseTypeDef = TypedDict(
     "DescribeVpcIngressConnectionResponseTypeDef",
     {
         "VpcIngressConnection": VpcIngressConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVpcIngressConnectionResponseTypeDef = TypedDict(
     "UpdateVpcIngressConnectionResponseTypeDef",
     {
         "VpcIngressConnection": VpcIngressConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourceConfigurationTypeDef = TypedDict(
     "SourceConfigurationTypeDef",
     {
         "CodeRepository": CodeRepositoryTypeDef,
@@ -1286,54 +1286,54 @@
 
 
 CreateServiceResponseTypeDef = TypedDict(
     "CreateServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteServiceResponseTypeDef = TypedDict(
     "DeleteServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeServiceResponseTypeDef = TypedDict(
     "DescribeServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PauseServiceResponseTypeDef = TypedDict(
     "PauseServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResumeServiceResponseTypeDef = TypedDict(
     "ResumeServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceResponseTypeDef = TypedDict(
     "UpdateServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner/type_defs.pyi` & `types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -40,15 +40,14 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AssociateCustomDomainRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "VpcDNSTargetTypeDef",
     "AuthenticationConfigurationTypeDef",
     "AutoScalingConfigurationSummaryTypeDef",
     "AutoScalingConfigurationTypeDef",
     "CertificateValidationRecordTypeDef",
     "CodeConfigurationValuesTypeDef",
     "SourceCodeVersionTypeDef",
@@ -87,18 +86,19 @@
     "ListServicesRequestRequestTypeDef",
     "ServiceSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ListVpcConnectorsRequestRequestTypeDef",
     "ListVpcIngressConnectionsFilterTypeDef",
     "VpcIngressConnectionSummaryTypeDef",
     "PauseServiceRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "ResumeServiceRequestRequestTypeDef",
     "StartDeploymentRequestRequestTypeDef",
-    "UntagResourceRequestRequestTypeDef",
     "StartDeploymentResponseTypeDef",
+    "UntagResourceRequestRequestTypeDef",
     "ListAutoScalingConfigurationsResponseTypeDef",
     "CreateAutoScalingConfigurationResponseTypeDef",
     "DeleteAutoScalingConfigurationResponseTypeDef",
     "DescribeAutoScalingConfigurationResponseTypeDef",
     "CustomDomainTypeDef",
     "CodeConfigurationTypeDef",
     "ListConnectionsResponseTypeDef",
@@ -165,25 +165,14 @@
 
 class AssociateCustomDomainRequestRequestTypeDef(
     _RequiredAssociateCustomDomainRequestRequestTypeDef,
     _OptionalAssociateCustomDomainRequestRequestTypeDef,
 ):
     pass
 
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
 VpcDNSTargetTypeDef = TypedDict(
     "VpcDNSTargetTypeDef",
     {
         "VpcIngressConnectionArn": str,
         "VpcId": str,
         "DomainName": str,
     },
@@ -652,74 +641,85 @@
 PauseServiceRequestRequestTypeDef = TypedDict(
     "PauseServiceRequestRequestTypeDef",
     {
         "ServiceArn": str,
     },
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
 ResumeServiceRequestRequestTypeDef = TypedDict(
     "ResumeServiceRequestRequestTypeDef",
     {
         "ServiceArn": str,
     },
 )
 
 StartDeploymentRequestRequestTypeDef = TypedDict(
     "StartDeploymentRequestRequestTypeDef",
     {
         "ServiceArn": str,
     },
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
+StartDeploymentResponseTypeDef = TypedDict(
+    "StartDeploymentResponseTypeDef",
     {
-        "ResourceArn": str,
-        "TagKeys": Sequence[str],
+        "OperationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartDeploymentResponseTypeDef = TypedDict(
-    "StartDeploymentResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "TagKeys": Sequence[str],
     },
 )
 
 ListAutoScalingConfigurationsResponseTypeDef = TypedDict(
     "ListAutoScalingConfigurationsResponseTypeDef",
     {
         "AutoScalingConfigurationSummaryList": List[AutoScalingConfigurationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAutoScalingConfigurationResponseTypeDef = TypedDict(
     "CreateAutoScalingConfigurationResponseTypeDef",
     {
         "AutoScalingConfiguration": AutoScalingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAutoScalingConfigurationResponseTypeDef = TypedDict(
     "DeleteAutoScalingConfigurationResponseTypeDef",
     {
         "AutoScalingConfiguration": AutoScalingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAutoScalingConfigurationResponseTypeDef = TypedDict(
     "DescribeAutoScalingConfigurationResponseTypeDef",
     {
         "AutoScalingConfiguration": AutoScalingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCustomDomainTypeDef = TypedDict(
     "_RequiredCustomDomainTypeDef",
     {
         "DomainName": str,
@@ -758,31 +758,31 @@
     pass
 
 ListConnectionsResponseTypeDef = TypedDict(
     "ListConnectionsResponseTypeDef",
     {
         "ConnectionSummaryList": List[ConnectionSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateConnectionResponseTypeDef = TypedDict(
     "CreateConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteConnectionResponseTypeDef = TypedDict(
     "DeleteConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateAutoScalingConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAutoScalingConfigurationRequestRequestTypeDef",
     {
         "AutoScalingConfigurationName": str,
@@ -847,15 +847,15 @@
 ):
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -899,40 +899,40 @@
     total=False,
 )
 
 CreateVpcConnectorResponseTypeDef = TypedDict(
     "CreateVpcConnectorResponseTypeDef",
     {
         "VpcConnector": VpcConnectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVpcConnectorResponseTypeDef = TypedDict(
     "DeleteVpcConnectorResponseTypeDef",
     {
         "VpcConnector": VpcConnectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVpcConnectorResponseTypeDef = TypedDict(
     "DescribeVpcConnectorResponseTypeDef",
     {
         "VpcConnector": VpcConnectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcConnectorsResponseTypeDef = TypedDict(
     "ListVpcConnectorsResponseTypeDef",
     {
         "VpcConnectors": List[VpcConnectorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateVpcIngressConnectionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateVpcIngressConnectionRequestRequestTypeDef",
     {
         "ServiceArn": str,
@@ -1006,33 +1006,33 @@
 )
 
 ListObservabilityConfigurationsResponseTypeDef = TypedDict(
     "ListObservabilityConfigurationsResponseTypeDef",
     {
         "ObservabilityConfigurationSummaryList": List[ObservabilityConfigurationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOperationsResponseTypeDef = TypedDict(
     "ListOperationsResponseTypeDef",
     {
         "OperationSummaryList": List[OperationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServicesResponseTypeDef = TypedDict(
     "ListServicesResponseTypeDef",
     {
         "ServiceSummaryList": List[ServiceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcIngressConnectionsRequestRequestTypeDef = TypedDict(
     "ListVpcIngressConnectionsRequestRequestTypeDef",
     {
         "Filter": ListVpcIngressConnectionsFilterTypeDef,
@@ -1043,49 +1043,49 @@
 )
 
 ListVpcIngressConnectionsResponseTypeDef = TypedDict(
     "ListVpcIngressConnectionsResponseTypeDef",
     {
         "VpcIngressConnectionSummaryList": List[VpcIngressConnectionSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociateCustomDomainResponseTypeDef = TypedDict(
     "AssociateCustomDomainResponseTypeDef",
     {
         "DNSTarget": str,
         "ServiceArn": str,
         "CustomDomain": CustomDomainTypeDef,
         "VpcDNSTargets": List[VpcDNSTargetTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCustomDomainsResponseTypeDef = TypedDict(
     "DescribeCustomDomainsResponseTypeDef",
     {
         "DNSTarget": str,
         "ServiceArn": str,
         "CustomDomains": List[CustomDomainTypeDef],
         "VpcDNSTargets": List[VpcDNSTargetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateCustomDomainResponseTypeDef = TypedDict(
     "DisassociateCustomDomainResponseTypeDef",
     {
         "DNSTarget": str,
         "ServiceArn": str,
         "CustomDomain": CustomDomainTypeDef,
         "VpcDNSTargets": List[VpcDNSTargetTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCodeRepositoryTypeDef = TypedDict(
     "_RequiredCodeRepositoryTypeDef",
     {
         "RepositoryUrl": str,
@@ -1103,63 +1103,63 @@
 class CodeRepositoryTypeDef(_RequiredCodeRepositoryTypeDef, _OptionalCodeRepositoryTypeDef):
     pass
 
 CreateObservabilityConfigurationResponseTypeDef = TypedDict(
     "CreateObservabilityConfigurationResponseTypeDef",
     {
         "ObservabilityConfiguration": ObservabilityConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteObservabilityConfigurationResponseTypeDef = TypedDict(
     "DeleteObservabilityConfigurationResponseTypeDef",
     {
         "ObservabilityConfiguration": ObservabilityConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeObservabilityConfigurationResponseTypeDef = TypedDict(
     "DescribeObservabilityConfigurationResponseTypeDef",
     {
         "ObservabilityConfiguration": ObservabilityConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVpcIngressConnectionResponseTypeDef = TypedDict(
     "CreateVpcIngressConnectionResponseTypeDef",
     {
         "VpcIngressConnection": VpcIngressConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVpcIngressConnectionResponseTypeDef = TypedDict(
     "DeleteVpcIngressConnectionResponseTypeDef",
     {
         "VpcIngressConnection": VpcIngressConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVpcIngressConnectionResponseTypeDef = TypedDict(
     "DescribeVpcIngressConnectionResponseTypeDef",
     {
         "VpcIngressConnection": VpcIngressConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVpcIngressConnectionResponseTypeDef = TypedDict(
     "UpdateVpcIngressConnectionResponseTypeDef",
     {
         "VpcIngressConnection": VpcIngressConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourceConfigurationTypeDef = TypedDict(
     "SourceConfigurationTypeDef",
     {
         "CodeRepository": CodeRepositoryTypeDef,
@@ -1251,54 +1251,54 @@
     pass
 
 CreateServiceResponseTypeDef = TypedDict(
     "CreateServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteServiceResponseTypeDef = TypedDict(
     "DeleteServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeServiceResponseTypeDef = TypedDict(
     "DescribeServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PauseServiceResponseTypeDef = TypedDict(
     "PauseServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResumeServiceResponseTypeDef = TypedDict(
     "ResumeServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceResponseTypeDef = TypedDict(
     "UpdateServiceResponseTypeDef",
     {
         "Service": ServiceTypeDef,
         "OperationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner.egg-info/PKG-INFO` & `types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-apprunner
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AppRunner 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AppRunner 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apprunner/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-apprunner"></a>
 
 # types-aiobotocore-apprunner
 
 [![PyPI - types-aiobotocore-apprunner](https://img.shields.io/pypi/v/types-aiobotocore-apprunner.svg?color=blue)](https://pypi.org/project/types-aiobotocore-apprunner)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-apprunner.svg?color=blue)](https://pypi.org/project/types-aiobotocore-apprunner)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apprunner/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-apprunner?color=blue)](https://pypistats.org/packages/types-aiobotocore-apprunner)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppRunner 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apprunner.html#AppRunner)
+[aiobotocore.AppRunner 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apprunner.html#AppRunner)
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
 [types-aiobotocore-apprunner docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apprunner/).
 
 See how it helps to find and fix potential bugs:
 
@@ -308,15 +308,14 @@
 
 `types_aiobotocore_apprunner.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_apprunner.type_defs import (
     AssociateCustomDomainRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     VpcDNSTargetTypeDef,
     AuthenticationConfigurationTypeDef,
     AutoScalingConfigurationSummaryTypeDef,
     AutoScalingConfigurationTypeDef,
     CertificateValidationRecordTypeDef,
     CodeConfigurationValuesTypeDef,
     SourceCodeVersionTypeDef,
@@ -355,18 +354,19 @@
     ListServicesRequestRequestTypeDef,
     ServiceSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListVpcConnectorsRequestRequestTypeDef,
     ListVpcIngressConnectionsFilterTypeDef,
     VpcIngressConnectionSummaryTypeDef,
     PauseServiceRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ResumeServiceRequestRequestTypeDef,
     StartDeploymentRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
     StartDeploymentResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
     ListAutoScalingConfigurationsResponseTypeDef,
     CreateAutoScalingConfigurationResponseTypeDef,
     DeleteAutoScalingConfigurationResponseTypeDef,
     DescribeAutoScalingConfigurationResponseTypeDef,
     CustomDomainTypeDef,
     CodeConfigurationTypeDef,
     ListConnectionsResponseTypeDef,
@@ -424,43 +424,43 @@
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

### Comparing `types-aiobotocore-apprunner-2.5.0.post1/types_aiobotocore_apprunner.egg-info/SOURCES.txt` & `types-aiobotocore-apprunner-2.5.1/types_aiobotocore_apprunner.egg-info/SOURCES.txt`

 * *Files identical despite different names*


# Comparing `tmp/types-aiobotocore-appstream-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-appstream-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-appstream-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:12 2023, max compression
+gzip compressed data, was "types-aiobotocore-appstream-2.5.1.tar", last modified: Wed Jun 28 01:43:06 2023, max compression
```

## Comparing `types-aiobotocore-appstream-2.5.0.post1.tar` & `types-aiobotocore-appstream-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.766948 types-aiobotocore-appstream-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    22705 2023-03-11 12:26:12.766948 types-aiobotocore-appstream-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    21126 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:12.766948 types-aiobotocore-appstream-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:09:45.000000 types-aiobotocore-appstream-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.758948 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/
--rw-r--r--   0 runner    (1001) docker     (123)     3011 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3010 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    53969 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    53883 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14039 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    14037 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12991 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    12978 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    60883 2023-03-11 12:09:47.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    60796 2023-03-11 12:09:47.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     2638 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2636 2023-03-11 12:09:46.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.766948 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    22705 2023-03-11 12:26:12.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-03-11 12:26:12.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:12.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:26:12.000000 types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.586094 types-aiobotocore-appstream-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:22.000000 types-aiobotocore-appstream-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    22699 2023-06-28 01:43:06.586094 types-aiobotocore-appstream-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    21126 2023-06-28 01:26:22.000000 types-aiobotocore-appstream-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:06.586094 types-aiobotocore-appstream-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:26:22.000000 types-aiobotocore-appstream-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.578094 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/
+-rw-r--r--   0 runner    (1001) docker     (123)     3011 2023-06-28 01:26:22.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3010 2023-06-28 01:26:22.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:26:22.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    53969 2023-06-28 01:26:22.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    53883 2023-06-28 01:26:22.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14248 2023-06-28 01:26:23.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14246 2023-06-28 01:26:23.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12915 2023-06-28 01:26:23.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12903 2023-06-28 01:26:23.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:22.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    60987 2023-06-28 01:26:24.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    60900 2023-06-28 01:26:23.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:22.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2638 2023-06-28 01:26:23.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2636 2023-06-28 01:26:23.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.586094 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    22699 2023-06-28 01:43:06.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      928 2023-06-28 01:43:06.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:06.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:43:06.000000 types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-appstream-2.5.0.post1/LICENSE` & `types-aiobotocore-appstream-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-appstream-2.5.0.post1/PKG-INFO` & `types-aiobotocore-appstream-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-appstream
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AppStream 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AppStream 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-appstream"></a>
 
 # types-aiobotocore-appstream
 
 [![PyPI - types-aiobotocore-appstream](https://img.shields.io/pypi/v/types-aiobotocore-appstream.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appstream)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appstream.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appstream)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appstream?color=blue)](https://pypistats.org/packages/types-aiobotocore-appstream)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppStream 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream)
+[aiobotocore.AppStream 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream)
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
 [types-aiobotocore-appstream docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/).
 
 See how it helps to find and fix potential bugs:
 
@@ -416,58 +416,68 @@
 from types_aiobotocore_appstream.type_defs import (
     AccessEndpointTypeDef,
     S3LocationTypeDef,
     ApplicationFleetAssociationTypeDef,
     ApplicationSettingsResponseTypeDef,
     ApplicationSettingsTypeDef,
     AssociateApplicationFleetRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AssociateApplicationToEntitlementRequestRequestTypeDef,
     AssociateFleetRequestRequestTypeDef,
     UserStackAssociationTypeDef,
     CertificateBasedAuthPropertiesTypeDef,
     ComputeCapacityStatusTypeDef,
     ComputeCapacityTypeDef,
     CopyImageRequestRequestTypeDef,
+    CopyImageResponseTypeDef,
     ServiceAccountCredentialsTypeDef,
     EntitlementAttributeTypeDef,
     DomainJoinInfoTypeDef,
     VpcConfigTypeDef,
     CreateImageBuilderStreamingURLRequestRequestTypeDef,
+    CreateImageBuilderStreamingURLResultTypeDef,
     StorageConnectorTypeDef,
     StreamingExperienceSettingsTypeDef,
     UserSettingTypeDef,
     CreateStreamingURLRequestRequestTypeDef,
+    CreateStreamingURLResultTypeDef,
     CreateUpdatedImageRequestRequestTypeDef,
+    CreateUsageReportSubscriptionResultTypeDef,
     CreateUserRequestRequestTypeDef,
     DeleteAppBlockRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteDirectoryConfigRequestRequestTypeDef,
     DeleteEntitlementRequestRequestTypeDef,
     DeleteFleetRequestRequestTypeDef,
     DeleteImageBuilderRequestRequestTypeDef,
     DeleteImagePermissionsRequestRequestTypeDef,
     DeleteImageRequestRequestTypeDef,
     DeleteStackRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DescribeAppBlocksRequestRequestTypeDef,
     DescribeApplicationFleetAssociationsRequestRequestTypeDef,
     DescribeApplicationsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef,
     DescribeDirectoryConfigsRequestRequestTypeDef,
     DescribeEntitlementsRequestRequestTypeDef,
+    DescribeFleetsRequestDescribeFleetsPaginateTypeDef,
     WaiterConfigTypeDef,
     DescribeFleetsRequestRequestTypeDef,
+    DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef,
     DescribeImageBuildersRequestRequestTypeDef,
     DescribeImagePermissionsRequestRequestTypeDef,
+    DescribeImagesRequestDescribeImagesPaginateTypeDef,
     DescribeImagesRequestRequestTypeDef,
+    DescribeSessionsRequestDescribeSessionsPaginateTypeDef,
     DescribeSessionsRequestRequestTypeDef,
+    DescribeStacksRequestDescribeStacksPaginateTypeDef,
     DescribeStacksRequestRequestTypeDef,
     DescribeUsageReportSubscriptionsRequestRequestTypeDef,
+    DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef,
     DescribeUserStackAssociationsRequestRequestTypeDef,
+    DescribeUsersRequestDescribeUsersPaginateTypeDef,
     DescribeUsersRequestRequestTypeDef,
     UserTypeDef,
     DisableUserRequestRequestTypeDef,
     DisassociateApplicationFleetRequestRequestTypeDef,
     DisassociateApplicationFromEntitlementRequestRequestTypeDef,
     DisassociateFleetRequestRequestTypeDef,
     EnableUserRequestRequestTypeDef,
@@ -476,38 +486,38 @@
     FleetErrorTypeDef,
     ImageBuilderStateChangeReasonTypeDef,
     NetworkAccessConfigurationTypeDef,
     ResourceErrorTypeDef,
     ImagePermissionsTypeDef,
     ImageStateChangeReasonTypeDef,
     LastReportGenerationExecutionErrorTypeDef,
+    ListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef,
     ListAssociatedFleetsRequestRequestTypeDef,
+    ListAssociatedFleetsResultTypeDef,
+    ListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef,
     ListAssociatedStacksRequestRequestTypeDef,
+    ListAssociatedStacksResultTypeDef,
     ListEntitledApplicationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StackErrorTypeDef,
     StartFleetRequestRequestTypeDef,
     StartImageBuilderRequestRequestTypeDef,
     StopFleetRequestRequestTypeDef,
     StopImageBuilderRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ApplicationTypeDef,
     CreateApplicationRequestRequestTypeDef,
     ScriptDetailsTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     AssociateApplicationFleetResultTypeDef,
-    CopyImageResponseTypeDef,
-    CreateImageBuilderStreamingURLResultTypeDef,
-    CreateStreamingURLResultTypeDef,
-    CreateUsageReportSubscriptionResultTypeDef,
     DescribeApplicationFleetAssociationsResultTypeDef,
-    ListAssociatedFleetsResultTypeDef,
-    ListAssociatedStacksResultTypeDef,
-    ListTagsForResourceResponseTypeDef,
     BatchAssociateUserStackRequestRequestTypeDef,
     BatchDisassociateUserStackRequestRequestTypeDef,
     DescribeUserStackAssociationsResultTypeDef,
     UserStackAssociationErrorTypeDef,
     CreateDirectoryConfigRequestRequestTypeDef,
     DirectoryConfigTypeDef,
     UpdateDirectoryConfigRequestRequestTypeDef,
@@ -515,24 +525,14 @@
     EntitlementTypeDef,
     UpdateEntitlementRequestRequestTypeDef,
     CreateFleetRequestRequestTypeDef,
     CreateImageBuilderRequestRequestTypeDef,
     UpdateFleetRequestRequestTypeDef,
     CreateStackRequestRequestTypeDef,
     UpdateStackRequestRequestTypeDef,
-    DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef,
-    DescribeFleetsRequestDescribeFleetsPaginateTypeDef,
-    DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef,
-    DescribeImagesRequestDescribeImagesPaginateTypeDef,
-    DescribeSessionsRequestDescribeSessionsPaginateTypeDef,
-    DescribeStacksRequestDescribeStacksPaginateTypeDef,
-    DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef,
-    DescribeUsersRequestDescribeUsersPaginateTypeDef,
-    ListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef,
-    ListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef,
     DescribeFleetsRequestFleetStartedWaitTypeDef,
     DescribeFleetsRequestFleetStoppedWaitTypeDef,
     DescribeUsersResultTypeDef,
     ListEntitledApplicationsResultTypeDef,
     FleetTypeDef,
     SessionTypeDef,
     ImageBuilderTypeDef,
@@ -583,43 +583,43 @@
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

### Comparing `types-aiobotocore-appstream-2.5.0.post1/README.md` & `types-aiobotocore-appstream-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-appstream"></a>
 
 # types-aiobotocore-appstream
 
 [![PyPI - types-aiobotocore-appstream](https://img.shields.io/pypi/v/types-aiobotocore-appstream.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appstream)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appstream.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appstream)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appstream?color=blue)](https://pypistats.org/packages/types-aiobotocore-appstream)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppStream 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream)
+[aiobotocore.AppStream 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream)
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
 [types-aiobotocore-appstream docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/).
 
 See how it helps to find and fix potential bugs:
 
@@ -383,58 +383,68 @@
 from types_aiobotocore_appstream.type_defs import (
     AccessEndpointTypeDef,
     S3LocationTypeDef,
     ApplicationFleetAssociationTypeDef,
     ApplicationSettingsResponseTypeDef,
     ApplicationSettingsTypeDef,
     AssociateApplicationFleetRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AssociateApplicationToEntitlementRequestRequestTypeDef,
     AssociateFleetRequestRequestTypeDef,
     UserStackAssociationTypeDef,
     CertificateBasedAuthPropertiesTypeDef,
     ComputeCapacityStatusTypeDef,
     ComputeCapacityTypeDef,
     CopyImageRequestRequestTypeDef,
+    CopyImageResponseTypeDef,
     ServiceAccountCredentialsTypeDef,
     EntitlementAttributeTypeDef,
     DomainJoinInfoTypeDef,
     VpcConfigTypeDef,
     CreateImageBuilderStreamingURLRequestRequestTypeDef,
+    CreateImageBuilderStreamingURLResultTypeDef,
     StorageConnectorTypeDef,
     StreamingExperienceSettingsTypeDef,
     UserSettingTypeDef,
     CreateStreamingURLRequestRequestTypeDef,
+    CreateStreamingURLResultTypeDef,
     CreateUpdatedImageRequestRequestTypeDef,
+    CreateUsageReportSubscriptionResultTypeDef,
     CreateUserRequestRequestTypeDef,
     DeleteAppBlockRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteDirectoryConfigRequestRequestTypeDef,
     DeleteEntitlementRequestRequestTypeDef,
     DeleteFleetRequestRequestTypeDef,
     DeleteImageBuilderRequestRequestTypeDef,
     DeleteImagePermissionsRequestRequestTypeDef,
     DeleteImageRequestRequestTypeDef,
     DeleteStackRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DescribeAppBlocksRequestRequestTypeDef,
     DescribeApplicationFleetAssociationsRequestRequestTypeDef,
     DescribeApplicationsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef,
     DescribeDirectoryConfigsRequestRequestTypeDef,
     DescribeEntitlementsRequestRequestTypeDef,
+    DescribeFleetsRequestDescribeFleetsPaginateTypeDef,
     WaiterConfigTypeDef,
     DescribeFleetsRequestRequestTypeDef,
+    DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef,
     DescribeImageBuildersRequestRequestTypeDef,
     DescribeImagePermissionsRequestRequestTypeDef,
+    DescribeImagesRequestDescribeImagesPaginateTypeDef,
     DescribeImagesRequestRequestTypeDef,
+    DescribeSessionsRequestDescribeSessionsPaginateTypeDef,
     DescribeSessionsRequestRequestTypeDef,
+    DescribeStacksRequestDescribeStacksPaginateTypeDef,
     DescribeStacksRequestRequestTypeDef,
     DescribeUsageReportSubscriptionsRequestRequestTypeDef,
+    DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef,
     DescribeUserStackAssociationsRequestRequestTypeDef,
+    DescribeUsersRequestDescribeUsersPaginateTypeDef,
     DescribeUsersRequestRequestTypeDef,
     UserTypeDef,
     DisableUserRequestRequestTypeDef,
     DisassociateApplicationFleetRequestRequestTypeDef,
     DisassociateApplicationFromEntitlementRequestRequestTypeDef,
     DisassociateFleetRequestRequestTypeDef,
     EnableUserRequestRequestTypeDef,
@@ -443,38 +453,38 @@
     FleetErrorTypeDef,
     ImageBuilderStateChangeReasonTypeDef,
     NetworkAccessConfigurationTypeDef,
     ResourceErrorTypeDef,
     ImagePermissionsTypeDef,
     ImageStateChangeReasonTypeDef,
     LastReportGenerationExecutionErrorTypeDef,
+    ListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef,
     ListAssociatedFleetsRequestRequestTypeDef,
+    ListAssociatedFleetsResultTypeDef,
+    ListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef,
     ListAssociatedStacksRequestRequestTypeDef,
+    ListAssociatedStacksResultTypeDef,
     ListEntitledApplicationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StackErrorTypeDef,
     StartFleetRequestRequestTypeDef,
     StartImageBuilderRequestRequestTypeDef,
     StopFleetRequestRequestTypeDef,
     StopImageBuilderRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ApplicationTypeDef,
     CreateApplicationRequestRequestTypeDef,
     ScriptDetailsTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     AssociateApplicationFleetResultTypeDef,
-    CopyImageResponseTypeDef,
-    CreateImageBuilderStreamingURLResultTypeDef,
-    CreateStreamingURLResultTypeDef,
-    CreateUsageReportSubscriptionResultTypeDef,
     DescribeApplicationFleetAssociationsResultTypeDef,
-    ListAssociatedFleetsResultTypeDef,
-    ListAssociatedStacksResultTypeDef,
-    ListTagsForResourceResponseTypeDef,
     BatchAssociateUserStackRequestRequestTypeDef,
     BatchDisassociateUserStackRequestRequestTypeDef,
     DescribeUserStackAssociationsResultTypeDef,
     UserStackAssociationErrorTypeDef,
     CreateDirectoryConfigRequestRequestTypeDef,
     DirectoryConfigTypeDef,
     UpdateDirectoryConfigRequestRequestTypeDef,
@@ -482,24 +492,14 @@
     EntitlementTypeDef,
     UpdateEntitlementRequestRequestTypeDef,
     CreateFleetRequestRequestTypeDef,
     CreateImageBuilderRequestRequestTypeDef,
     UpdateFleetRequestRequestTypeDef,
     CreateStackRequestRequestTypeDef,
     UpdateStackRequestRequestTypeDef,
-    DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef,
-    DescribeFleetsRequestDescribeFleetsPaginateTypeDef,
-    DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef,
-    DescribeImagesRequestDescribeImagesPaginateTypeDef,
-    DescribeSessionsRequestDescribeSessionsPaginateTypeDef,
-    DescribeStacksRequestDescribeStacksPaginateTypeDef,
-    DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef,
-    DescribeUsersRequestDescribeUsersPaginateTypeDef,
-    ListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef,
-    ListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef,
     DescribeFleetsRequestFleetStartedWaitTypeDef,
     DescribeFleetsRequestFleetStoppedWaitTypeDef,
     DescribeUsersResultTypeDef,
     ListEntitledApplicationsResultTypeDef,
     FleetTypeDef,
     SessionTypeDef,
     ImageBuilderTypeDef,
@@ -550,43 +550,43 @@
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

### Comparing `types-aiobotocore-appstream-2.5.0.post1/setup.py` & `types-aiobotocore-appstream-2.5.1/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-appstream.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-appstream",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_appstream"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.AppStream 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.AppStream 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/"
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

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/__init__.py` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/__init__.pyi` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/__main__.py` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.AppStream 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.AppStream 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream\nOther"
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

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/client.py` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/client.pyi` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/literals.py` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -249,14 +249,15 @@
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
@@ -335,14 +336,15 @@
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
@@ -353,14 +355,15 @@
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
@@ -396,14 +399,15 @@
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
@@ -422,16 +426,19 @@
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
@@ -515,15 +522,17 @@
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

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/literals.pyi` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -247,14 +247,15 @@
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
@@ -333,14 +334,15 @@
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
@@ -351,14 +353,15 @@
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
@@ -394,14 +397,15 @@
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
@@ -420,16 +424,19 @@
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
@@ -513,15 +520,17 @@
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

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/paginator.py` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         describe_stacks_paginator: DescribeStacksPaginator = client.get_paginator("describe_stacks")
         describe_user_stack_associations_paginator: DescribeUserStackAssociationsPaginator = client.get_paginator("describe_user_stack_associations")
         describe_users_paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
         list_associated_fleets_paginator: ListAssociatedFleetsPaginator = client.get_paginator("list_associated_fleets")
         list_associated_stacks_paginator: ListAssociatedStacksPaginator = client.get_paginator("list_associated_stacks")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import AuthenticationTypeType, VisibilityTypeType
 from .type_defs import (
     DescribeDirectoryConfigsResultTypeDef,
@@ -55,204 +54,189 @@
     DescribeUsersResultTypeDef,
     DescribeUserStackAssociationsResultTypeDef,
     ListAssociatedFleetsResultTypeDef,
     ListAssociatedStacksResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeDirectoryConfigsPaginator",
     "DescribeFleetsPaginator",
     "DescribeImageBuildersPaginator",
     "DescribeImagesPaginator",
     "DescribeSessionsPaginator",
     "DescribeStacksPaginator",
     "DescribeUserStackAssociationsPaginator",
     "DescribeUsersPaginator",
     "ListAssociatedFleetsPaginator",
     "ListAssociatedStacksPaginator",
 )
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class DescribeDirectoryConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeDirectoryConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describedirectoryconfigspaginator)
     """
 
     def paginate(
-        self, *, DirectoryNames: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        DirectoryNames: Sequence[str] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDirectoryConfigsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeDirectoryConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describedirectoryconfigspaginator)
         """
 
-
 class DescribeFleetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeFleets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describefleetspaginator)
     """
 
     def paginate(
-        self, *, Names: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Names: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFleetsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeFleets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describefleetspaginator)
         """
 
-
 class DescribeImageBuildersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeImageBuilders)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeimagebuilderspaginator)
     """
 
     def paginate(
-        self, *, Names: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Names: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeImageBuildersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeImageBuilders.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeimagebuilderspaginator)
         """
 
-
 class DescribeImagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeImages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeimagespaginator)
     """
 
     def paginate(
         self,
         *,
         Names: Sequence[str] = ...,
         Arns: Sequence[str] = ...,
         Type: VisibilityTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeImagesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeImages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeimagespaginator)
         """
 
-
 class DescribeSessionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeSessions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describesessionspaginator)
     """
 
     def paginate(
         self,
         *,
         StackName: str,
         FleetName: str,
         UserId: str = ...,
         AuthenticationType: AuthenticationTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSessionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describesessionspaginator)
         """
 
-
 class DescribeStacksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeStacks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describestackspaginator)
     """
 
     def paginate(
-        self, *, Names: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Names: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeStacksResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeStacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describestackspaginator)
         """
 
-
 class DescribeUserStackAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeUserStackAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeuserstackassociationspaginator)
     """
 
     def paginate(
         self,
         *,
         StackName: str = ...,
         UserName: str = ...,
         AuthenticationType: AuthenticationTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeUserStackAssociationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeUserStackAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeuserstackassociationspaginator)
         """
 
-
 class DescribeUsersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeUsers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeuserspaginator)
     """
 
     def paginate(
         self,
         *,
         AuthenticationType: AuthenticationTypeType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeUsersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeuserspaginator)
         """
 
-
 class ListAssociatedFleetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.ListAssociatedFleets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#listassociatedfleetspaginator)
     """
 
     def paginate(
-        self, *, StackName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, StackName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociatedFleetsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.ListAssociatedFleets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#listassociatedfleetspaginator)
         """
 
-
 class ListAssociatedStacksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.ListAssociatedStacks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#listassociatedstackspaginator)
     """
 
     def paginate(
-        self, *, FleetName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FleetName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociatedStacksResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.ListAssociatedStacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#listassociatedstackspaginator)
         """
```

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/paginator.pyi` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         describe_stacks_paginator: DescribeStacksPaginator = client.get_paginator("describe_stacks")
         describe_user_stack_associations_paginator: DescribeUserStackAssociationsPaginator = client.get_paginator("describe_user_stack_associations")
         describe_users_paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
         list_associated_fleets_paginator: ListAssociatedFleetsPaginator = client.get_paginator("list_associated_fleets")
         list_associated_stacks_paginator: ListAssociatedStacksPaginator = client.get_paginator("list_associated_stacks")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import AuthenticationTypeType, VisibilityTypeType
 from .type_defs import (
     DescribeDirectoryConfigsResultTypeDef,
@@ -55,191 +54,201 @@
     DescribeUsersResultTypeDef,
     DescribeUserStackAssociationsResultTypeDef,
     ListAssociatedFleetsResultTypeDef,
     ListAssociatedStacksResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeDirectoryConfigsPaginator",
     "DescribeFleetsPaginator",
     "DescribeImageBuildersPaginator",
     "DescribeImagesPaginator",
     "DescribeSessionsPaginator",
     "DescribeStacksPaginator",
     "DescribeUserStackAssociationsPaginator",
     "DescribeUsersPaginator",
     "ListAssociatedFleetsPaginator",
     "ListAssociatedStacksPaginator",
 )
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class DescribeDirectoryConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeDirectoryConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describedirectoryconfigspaginator)
     """
 
     def paginate(
-        self, *, DirectoryNames: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        DirectoryNames: Sequence[str] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDirectoryConfigsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeDirectoryConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describedirectoryconfigspaginator)
         """
 
+
 class DescribeFleetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeFleets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describefleetspaginator)
     """
 
     def paginate(
-        self, *, Names: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Names: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFleetsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeFleets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describefleetspaginator)
         """
 
+
 class DescribeImageBuildersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeImageBuilders)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeimagebuilderspaginator)
     """
 
     def paginate(
-        self, *, Names: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Names: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeImageBuildersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeImageBuilders.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeimagebuilderspaginator)
         """
 
+
 class DescribeImagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeImages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeimagespaginator)
     """
 
     def paginate(
         self,
         *,
         Names: Sequence[str] = ...,
         Arns: Sequence[str] = ...,
         Type: VisibilityTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeImagesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeImages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeimagespaginator)
         """
 
+
 class DescribeSessionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeSessions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describesessionspaginator)
     """
 
     def paginate(
         self,
         *,
         StackName: str,
         FleetName: str,
         UserId: str = ...,
         AuthenticationType: AuthenticationTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSessionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describesessionspaginator)
         """
 
+
 class DescribeStacksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeStacks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describestackspaginator)
     """
 
     def paginate(
-        self, *, Names: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Names: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeStacksResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeStacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describestackspaginator)
         """
 
+
 class DescribeUserStackAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeUserStackAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeuserstackassociationspaginator)
     """
 
     def paginate(
         self,
         *,
         StackName: str = ...,
         UserName: str = ...,
         AuthenticationType: AuthenticationTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeUserStackAssociationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeUserStackAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeuserstackassociationspaginator)
         """
 
+
 class DescribeUsersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeUsers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeuserspaginator)
     """
 
     def paginate(
         self,
         *,
         AuthenticationType: AuthenticationTypeType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeUsersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.DescribeUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#describeuserspaginator)
         """
 
+
 class ListAssociatedFleetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.ListAssociatedFleets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#listassociatedfleetspaginator)
     """
 
     def paginate(
-        self, *, StackName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, StackName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociatedFleetsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.ListAssociatedFleets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#listassociatedfleetspaginator)
         """
 
+
 class ListAssociatedStacksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.ListAssociatedStacks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#listassociatedstackspaginator)
     """
 
     def paginate(
-        self, *, FleetName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FleetName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociatedStacksResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream.Paginator.ListAssociatedStacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/paginators/#listassociatedstackspaginator)
         """
```

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/type_defs.py` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -57,58 +57,68 @@
 __all__ = (
     "AccessEndpointTypeDef",
     "S3LocationTypeDef",
     "ApplicationFleetAssociationTypeDef",
     "ApplicationSettingsResponseTypeDef",
     "ApplicationSettingsTypeDef",
     "AssociateApplicationFleetRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AssociateApplicationToEntitlementRequestRequestTypeDef",
     "AssociateFleetRequestRequestTypeDef",
     "UserStackAssociationTypeDef",
     "CertificateBasedAuthPropertiesTypeDef",
     "ComputeCapacityStatusTypeDef",
     "ComputeCapacityTypeDef",
     "CopyImageRequestRequestTypeDef",
+    "CopyImageResponseTypeDef",
     "ServiceAccountCredentialsTypeDef",
     "EntitlementAttributeTypeDef",
     "DomainJoinInfoTypeDef",
     "VpcConfigTypeDef",
     "CreateImageBuilderStreamingURLRequestRequestTypeDef",
+    "CreateImageBuilderStreamingURLResultTypeDef",
     "StorageConnectorTypeDef",
     "StreamingExperienceSettingsTypeDef",
     "UserSettingTypeDef",
     "CreateStreamingURLRequestRequestTypeDef",
+    "CreateStreamingURLResultTypeDef",
     "CreateUpdatedImageRequestRequestTypeDef",
+    "CreateUsageReportSubscriptionResultTypeDef",
     "CreateUserRequestRequestTypeDef",
     "DeleteAppBlockRequestRequestTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DeleteDirectoryConfigRequestRequestTypeDef",
     "DeleteEntitlementRequestRequestTypeDef",
     "DeleteFleetRequestRequestTypeDef",
     "DeleteImageBuilderRequestRequestTypeDef",
     "DeleteImagePermissionsRequestRequestTypeDef",
     "DeleteImageRequestRequestTypeDef",
     "DeleteStackRequestRequestTypeDef",
     "DeleteUserRequestRequestTypeDef",
     "DescribeAppBlocksRequestRequestTypeDef",
     "DescribeApplicationFleetAssociationsRequestRequestTypeDef",
     "DescribeApplicationsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef",
     "DescribeDirectoryConfigsRequestRequestTypeDef",
     "DescribeEntitlementsRequestRequestTypeDef",
+    "DescribeFleetsRequestDescribeFleetsPaginateTypeDef",
     "WaiterConfigTypeDef",
     "DescribeFleetsRequestRequestTypeDef",
+    "DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef",
     "DescribeImageBuildersRequestRequestTypeDef",
     "DescribeImagePermissionsRequestRequestTypeDef",
+    "DescribeImagesRequestDescribeImagesPaginateTypeDef",
     "DescribeImagesRequestRequestTypeDef",
+    "DescribeSessionsRequestDescribeSessionsPaginateTypeDef",
     "DescribeSessionsRequestRequestTypeDef",
+    "DescribeStacksRequestDescribeStacksPaginateTypeDef",
     "DescribeStacksRequestRequestTypeDef",
     "DescribeUsageReportSubscriptionsRequestRequestTypeDef",
+    "DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef",
     "DescribeUserStackAssociationsRequestRequestTypeDef",
+    "DescribeUsersRequestDescribeUsersPaginateTypeDef",
     "DescribeUsersRequestRequestTypeDef",
     "UserTypeDef",
     "DisableUserRequestRequestTypeDef",
     "DisassociateApplicationFleetRequestRequestTypeDef",
     "DisassociateApplicationFromEntitlementRequestRequestTypeDef",
     "DisassociateFleetRequestRequestTypeDef",
     "EnableUserRequestRequestTypeDef",
@@ -117,38 +127,38 @@
     "FleetErrorTypeDef",
     "ImageBuilderStateChangeReasonTypeDef",
     "NetworkAccessConfigurationTypeDef",
     "ResourceErrorTypeDef",
     "ImagePermissionsTypeDef",
     "ImageStateChangeReasonTypeDef",
     "LastReportGenerationExecutionErrorTypeDef",
+    "ListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef",
     "ListAssociatedFleetsRequestRequestTypeDef",
+    "ListAssociatedFleetsResultTypeDef",
+    "ListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef",
     "ListAssociatedStacksRequestRequestTypeDef",
+    "ListAssociatedStacksResultTypeDef",
     "ListEntitledApplicationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "StackErrorTypeDef",
     "StartFleetRequestRequestTypeDef",
     "StartImageBuilderRequestRequestTypeDef",
     "StopFleetRequestRequestTypeDef",
     "StopImageBuilderRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "ApplicationTypeDef",
     "CreateApplicationRequestRequestTypeDef",
     "ScriptDetailsTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
     "AssociateApplicationFleetResultTypeDef",
-    "CopyImageResponseTypeDef",
-    "CreateImageBuilderStreamingURLResultTypeDef",
-    "CreateStreamingURLResultTypeDef",
-    "CreateUsageReportSubscriptionResultTypeDef",
     "DescribeApplicationFleetAssociationsResultTypeDef",
-    "ListAssociatedFleetsResultTypeDef",
-    "ListAssociatedStacksResultTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "BatchAssociateUserStackRequestRequestTypeDef",
     "BatchDisassociateUserStackRequestRequestTypeDef",
     "DescribeUserStackAssociationsResultTypeDef",
     "UserStackAssociationErrorTypeDef",
     "CreateDirectoryConfigRequestRequestTypeDef",
     "DirectoryConfigTypeDef",
     "UpdateDirectoryConfigRequestRequestTypeDef",
@@ -156,24 +166,14 @@
     "EntitlementTypeDef",
     "UpdateEntitlementRequestRequestTypeDef",
     "CreateFleetRequestRequestTypeDef",
     "CreateImageBuilderRequestRequestTypeDef",
     "UpdateFleetRequestRequestTypeDef",
     "CreateStackRequestRequestTypeDef",
     "UpdateStackRequestRequestTypeDef",
-    "DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef",
-    "DescribeFleetsRequestDescribeFleetsPaginateTypeDef",
-    "DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef",
-    "DescribeImagesRequestDescribeImagesPaginateTypeDef",
-    "DescribeSessionsRequestDescribeSessionsPaginateTypeDef",
-    "DescribeStacksRequestDescribeStacksPaginateTypeDef",
-    "DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef",
-    "DescribeUsersRequestDescribeUsersPaginateTypeDef",
-    "ListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef",
-    "ListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef",
     "DescribeFleetsRequestFleetStartedWaitTypeDef",
     "DescribeFleetsRequestFleetStoppedWaitTypeDef",
     "DescribeUsersResultTypeDef",
     "ListEntitledApplicationsResultTypeDef",
     "FleetTypeDef",
     "SessionTypeDef",
     "ImageBuilderTypeDef",
@@ -286,25 +286,14 @@
     "AssociateApplicationFleetRequestRequestTypeDef",
     {
         "FleetName": str,
         "ApplicationArn": str,
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
 AssociateApplicationToEntitlementRequestRequestTypeDef = TypedDict(
     "AssociateApplicationToEntitlementRequestRequestTypeDef",
     {
         "StackName": str,
         "EntitlementName": str,
         "ApplicationIdentifier": str,
     },
@@ -399,14 +388,22 @@
 
 class CopyImageRequestRequestTypeDef(
     _RequiredCopyImageRequestRequestTypeDef, _OptionalCopyImageRequestRequestTypeDef
 ):
     pass
 
 
+CopyImageResponseTypeDef = TypedDict(
+    "CopyImageResponseTypeDef",
+    {
+        "DestinationImageName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ServiceAccountCredentialsTypeDef = TypedDict(
     "ServiceAccountCredentialsTypeDef",
     {
         "AccountName": str,
         "AccountPassword": str,
     },
 )
@@ -455,14 +452,23 @@
 class CreateImageBuilderStreamingURLRequestRequestTypeDef(
     _RequiredCreateImageBuilderStreamingURLRequestRequestTypeDef,
     _OptionalCreateImageBuilderStreamingURLRequestRequestTypeDef,
 ):
     pass
 
 
+CreateImageBuilderStreamingURLResultTypeDef = TypedDict(
+    "CreateImageBuilderStreamingURLResultTypeDef",
+    {
+        "StreamingURL": str,
+        "Expires": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStorageConnectorTypeDef = TypedDict(
     "_RequiredStorageConnectorTypeDef",
     {
         "ConnectorType": StorageConnectorTypeType,
     },
 )
 _OptionalStorageConnectorTypeDef = TypedDict(
@@ -517,14 +523,23 @@
 class CreateStreamingURLRequestRequestTypeDef(
     _RequiredCreateStreamingURLRequestRequestTypeDef,
     _OptionalCreateStreamingURLRequestRequestTypeDef,
 ):
     pass
 
 
+CreateStreamingURLResultTypeDef = TypedDict(
+    "CreateStreamingURLResultTypeDef",
+    {
+        "StreamingURL": str,
+        "Expires": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateUpdatedImageRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUpdatedImageRequestRequestTypeDef",
     {
         "existingImageName": str,
         "newImageName": str,
     },
 )
@@ -543,14 +558,23 @@
 class CreateUpdatedImageRequestRequestTypeDef(
     _RequiredCreateUpdatedImageRequestRequestTypeDef,
     _OptionalCreateUpdatedImageRequestRequestTypeDef,
 ):
     pass
 
 
+CreateUsageReportSubscriptionResultTypeDef = TypedDict(
+    "CreateUsageReportSubscriptionResultTypeDef",
+    {
+        "S3BucketName": str,
+        "Schedule": Literal["DAILY"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateUserRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserRequestRequestTypeDef",
     {
         "UserName": str,
         "AuthenticationType": AuthenticationTypeType,
     },
 )
@@ -671,20 +695,19 @@
         "Arns": Sequence[str],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef = TypedDict(
+    "DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "DirectoryNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeDirectoryConfigsRequestRequestTypeDef = TypedDict(
     "DescribeDirectoryConfigsRequestRequestTypeDef",
     {
@@ -715,14 +738,23 @@
 class DescribeEntitlementsRequestRequestTypeDef(
     _RequiredDescribeEntitlementsRequestRequestTypeDef,
     _OptionalDescribeEntitlementsRequestRequestTypeDef,
 ):
     pass
 
 
+DescribeFleetsRequestDescribeFleetsPaginateTypeDef = TypedDict(
+    "DescribeFleetsRequestDescribeFleetsPaginateTypeDef",
+    {
+        "Names": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -733,14 +765,23 @@
     {
         "Names": Sequence[str],
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef = TypedDict(
+    "DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef",
+    {
+        "Names": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeImageBuildersRequestRequestTypeDef = TypedDict(
     "DescribeImageBuildersRequestRequestTypeDef",
     {
         "Names": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
@@ -767,26 +808,62 @@
 class DescribeImagePermissionsRequestRequestTypeDef(
     _RequiredDescribeImagePermissionsRequestRequestTypeDef,
     _OptionalDescribeImagePermissionsRequestRequestTypeDef,
 ):
     pass
 
 
+DescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
+    "DescribeImagesRequestDescribeImagesPaginateTypeDef",
+    {
+        "Names": Sequence[str],
+        "Arns": Sequence[str],
+        "Type": VisibilityTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeImagesRequestRequestTypeDef = TypedDict(
     "DescribeImagesRequestRequestTypeDef",
     {
         "Names": Sequence[str],
         "Arns": Sequence[str],
         "Type": VisibilityTypeType,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredDescribeSessionsRequestDescribeSessionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeSessionsRequestDescribeSessionsPaginateTypeDef",
+    {
+        "StackName": str,
+        "FleetName": str,
+    },
+)
+_OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef",
+    {
+        "UserId": str,
+        "AuthenticationType": AuthenticationTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeSessionsRequestDescribeSessionsPaginateTypeDef(
+    _RequiredDescribeSessionsRequestDescribeSessionsPaginateTypeDef,
+    _OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeSessionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeSessionsRequestRequestTypeDef",
     {
         "StackName": str,
         "FleetName": str,
     },
 )
@@ -804,14 +881,23 @@
 
 class DescribeSessionsRequestRequestTypeDef(
     _RequiredDescribeSessionsRequestRequestTypeDef, _OptionalDescribeSessionsRequestRequestTypeDef
 ):
     pass
 
 
+DescribeStacksRequestDescribeStacksPaginateTypeDef = TypedDict(
+    "DescribeStacksRequestDescribeStacksPaginateTypeDef",
+    {
+        "Names": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeStacksRequestRequestTypeDef = TypedDict(
     "DescribeStacksRequestRequestTypeDef",
     {
         "Names": Sequence[str],
         "NextToken": str,
     },
     total=False,
@@ -822,26 +908,59 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef = TypedDict(
+    "DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef",
+    {
+        "StackName": str,
+        "UserName": str,
+        "AuthenticationType": AuthenticationTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeUserStackAssociationsRequestRequestTypeDef = TypedDict(
     "DescribeUserStackAssociationsRequestRequestTypeDef",
     {
         "StackName": str,
         "UserName": str,
         "AuthenticationType": AuthenticationTypeType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredDescribeUsersRequestDescribeUsersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeUsersRequestDescribeUsersPaginateTypeDef",
+    {
+        "AuthenticationType": AuthenticationTypeType,
+    },
+)
+_OptionalDescribeUsersRequestDescribeUsersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeUsersRequestDescribeUsersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeUsersRequestDescribeUsersPaginateTypeDef(
+    _RequiredDescribeUsersRequestDescribeUsersPaginateTypeDef,
+    _OptionalDescribeUsersRequestDescribeUsersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeUsersRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeUsersRequestRequestTypeDef",
     {
         "AuthenticationType": AuthenticationTypeType,
     },
 )
 _OptionalDescribeUsersRequestRequestTypeDef = TypedDict(
@@ -1000,14 +1119,36 @@
     {
         "ErrorCode": UsageReportExecutionErrorCodeType,
         "ErrorMessage": str,
     },
     total=False,
 )
 
+_RequiredListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef = TypedDict(
+    "_RequiredListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef",
+    {
+        "StackName": str,
+    },
+)
+_OptionalListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef = TypedDict(
+    "_OptionalListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef(
+    _RequiredListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef,
+    _OptionalListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAssociatedFleetsRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociatedFleetsRequestRequestTypeDef",
     {
         "StackName": str,
     },
 )
 _OptionalListAssociatedFleetsRequestRequestTypeDef = TypedDict(
@@ -1022,14 +1163,45 @@
 class ListAssociatedFleetsRequestRequestTypeDef(
     _RequiredListAssociatedFleetsRequestRequestTypeDef,
     _OptionalListAssociatedFleetsRequestRequestTypeDef,
 ):
     pass
 
 
+ListAssociatedFleetsResultTypeDef = TypedDict(
+    "ListAssociatedFleetsResultTypeDef",
+    {
+        "Names": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef = TypedDict(
+    "_RequiredListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef",
+    {
+        "FleetName": str,
+    },
+)
+_OptionalListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef = TypedDict(
+    "_OptionalListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef(
+    _RequiredListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef,
+    _OptionalListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAssociatedStacksRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociatedStacksRequestRequestTypeDef",
     {
         "FleetName": str,
     },
 )
 _OptionalListAssociatedStacksRequestRequestTypeDef = TypedDict(
@@ -1044,14 +1216,23 @@
 class ListAssociatedStacksRequestRequestTypeDef(
     _RequiredListAssociatedStacksRequestRequestTypeDef,
     _OptionalListAssociatedStacksRequestRequestTypeDef,
 ):
     pass
 
 
+ListAssociatedStacksResultTypeDef = TypedDict(
+    "ListAssociatedStacksResultTypeDef",
+    {
+        "Names": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListEntitledApplicationsRequestRequestTypeDef = TypedDict(
     "_RequiredListEntitledApplicationsRequestRequestTypeDef",
     {
         "StackName": str,
         "EntitlementName": str,
     },
 )
@@ -1075,14 +1256,43 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
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
 StackErrorTypeDef = TypedDict(
     "StackErrorTypeDef",
     {
         "ErrorCode": StackErrorCodeType,
         "ErrorMessage": str,
     },
     total=False,
@@ -1247,85 +1457,24 @@
     pass
 
 
 AssociateApplicationFleetResultTypeDef = TypedDict(
     "AssociateApplicationFleetResultTypeDef",
     {
         "ApplicationFleetAssociation": ApplicationFleetAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CopyImageResponseTypeDef = TypedDict(
-    "CopyImageResponseTypeDef",
-    {
-        "DestinationImageName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateImageBuilderStreamingURLResultTypeDef = TypedDict(
-    "CreateImageBuilderStreamingURLResultTypeDef",
-    {
-        "StreamingURL": str,
-        "Expires": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStreamingURLResultTypeDef = TypedDict(
-    "CreateStreamingURLResultTypeDef",
-    {
-        "StreamingURL": str,
-        "Expires": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUsageReportSubscriptionResultTypeDef = TypedDict(
-    "CreateUsageReportSubscriptionResultTypeDef",
-    {
-        "S3BucketName": str,
-        "Schedule": Literal["DAILY"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeApplicationFleetAssociationsResultTypeDef = TypedDict(
     "DescribeApplicationFleetAssociationsResultTypeDef",
     {
         "ApplicationFleetAssociations": List[ApplicationFleetAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAssociatedFleetsResultTypeDef = TypedDict(
-    "ListAssociatedFleetsResultTypeDef",
-    {
-        "Names": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAssociatedStacksResultTypeDef = TypedDict(
-    "ListAssociatedStacksResultTypeDef",
-    {
-        "Names": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchAssociateUserStackRequestRequestTypeDef = TypedDict(
     "BatchAssociateUserStackRequestRequestTypeDef",
     {
         "UserStackAssociations": Sequence[UserStackAssociationTypeDef],
@@ -1340,15 +1489,15 @@
 )
 
 DescribeUserStackAssociationsResultTypeDef = TypedDict(
     "DescribeUserStackAssociationsResultTypeDef",
     {
         "UserStackAssociations": List[UserStackAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UserStackAssociationErrorTypeDef = TypedDict(
     "UserStackAssociationErrorTypeDef",
     {
         "UserStackAssociation": UserStackAssociationTypeDef,
@@ -1660,163 +1809,14 @@
 
 class UpdateStackRequestRequestTypeDef(
     _RequiredUpdateStackRequestRequestTypeDef, _OptionalUpdateStackRequestRequestTypeDef
 ):
     pass
 
 
-DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef = TypedDict(
-    "DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef",
-    {
-        "DirectoryNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeFleetsRequestDescribeFleetsPaginateTypeDef = TypedDict(
-    "DescribeFleetsRequestDescribeFleetsPaginateTypeDef",
-    {
-        "Names": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef = TypedDict(
-    "DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef",
-    {
-        "Names": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
-    "DescribeImagesRequestDescribeImagesPaginateTypeDef",
-    {
-        "Names": Sequence[str],
-        "Arns": Sequence[str],
-        "Type": VisibilityTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeSessionsRequestDescribeSessionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeSessionsRequestDescribeSessionsPaginateTypeDef",
-    {
-        "StackName": str,
-        "FleetName": str,
-    },
-)
-_OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef",
-    {
-        "UserId": str,
-        "AuthenticationType": AuthenticationTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeSessionsRequestDescribeSessionsPaginateTypeDef(
-    _RequiredDescribeSessionsRequestDescribeSessionsPaginateTypeDef,
-    _OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef,
-):
-    pass
-
-
-DescribeStacksRequestDescribeStacksPaginateTypeDef = TypedDict(
-    "DescribeStacksRequestDescribeStacksPaginateTypeDef",
-    {
-        "Names": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef = TypedDict(
-    "DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef",
-    {
-        "StackName": str,
-        "UserName": str,
-        "AuthenticationType": AuthenticationTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeUsersRequestDescribeUsersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeUsersRequestDescribeUsersPaginateTypeDef",
-    {
-        "AuthenticationType": AuthenticationTypeType,
-    },
-)
-_OptionalDescribeUsersRequestDescribeUsersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeUsersRequestDescribeUsersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeUsersRequestDescribeUsersPaginateTypeDef(
-    _RequiredDescribeUsersRequestDescribeUsersPaginateTypeDef,
-    _OptionalDescribeUsersRequestDescribeUsersPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef = TypedDict(
-    "_RequiredListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef",
-    {
-        "StackName": str,
-    },
-)
-_OptionalListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef = TypedDict(
-    "_OptionalListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef(
-    _RequiredListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef,
-    _OptionalListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef = TypedDict(
-    "_RequiredListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef",
-    {
-        "FleetName": str,
-    },
-)
-_OptionalListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef = TypedDict(
-    "_OptionalListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef(
-    _RequiredListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef,
-    _OptionalListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef,
-):
-    pass
-
-
 DescribeFleetsRequestFleetStartedWaitTypeDef = TypedDict(
     "DescribeFleetsRequestFleetStartedWaitTypeDef",
     {
         "Names": Sequence[str],
         "NextToken": str,
         "WaiterConfig": WaiterConfigTypeDef,
     },
@@ -1834,24 +1834,24 @@
 )
 
 DescribeUsersResultTypeDef = TypedDict(
     "DescribeUsersResultTypeDef",
     {
         "Users": List[UserTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEntitledApplicationsResultTypeDef = TypedDict(
     "ListEntitledApplicationsResultTypeDef",
     {
         "EntitledApplications": List[EntitledApplicationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFleetTypeDef = TypedDict(
     "_RequiredFleetTypeDef",
     {
         "Arn": str,
@@ -2013,24 +2013,24 @@
     pass
 
 
 CreateApplicationResultTypeDef = TypedDict(
     "CreateApplicationResultTypeDef",
     {
         "Application": ApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeApplicationsResultTypeDef = TypedDict(
     "DescribeApplicationsResultTypeDef",
     {
         "Applications": List[ApplicationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImageTypeDef = TypedDict(
     "_RequiredImageTypeDef",
     {
         "Name": str,
@@ -2064,15 +2064,15 @@
     pass
 
 
 UpdateApplicationResultTypeDef = TypedDict(
     "UpdateApplicationResultTypeDef",
     {
         "Application": ApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAppBlockTypeDef = TypedDict(
     "_RequiredAppBlockTypeDef",
     {
         "Name": str,
@@ -2121,230 +2121,230 @@
     pass
 
 
 BatchAssociateUserStackResultTypeDef = TypedDict(
     "BatchAssociateUserStackResultTypeDef",
     {
         "errors": List[UserStackAssociationErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDisassociateUserStackResultTypeDef = TypedDict(
     "BatchDisassociateUserStackResultTypeDef",
     {
         "errors": List[UserStackAssociationErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDirectoryConfigResultTypeDef = TypedDict(
     "CreateDirectoryConfigResultTypeDef",
     {
         "DirectoryConfig": DirectoryConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDirectoryConfigsResultTypeDef = TypedDict(
     "DescribeDirectoryConfigsResultTypeDef",
     {
         "DirectoryConfigs": List[DirectoryConfigTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDirectoryConfigResultTypeDef = TypedDict(
     "UpdateDirectoryConfigResultTypeDef",
     {
         "DirectoryConfig": DirectoryConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEntitlementResultTypeDef = TypedDict(
     "CreateEntitlementResultTypeDef",
     {
         "Entitlement": EntitlementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEntitlementsResultTypeDef = TypedDict(
     "DescribeEntitlementsResultTypeDef",
     {
         "Entitlements": List[EntitlementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEntitlementResultTypeDef = TypedDict(
     "UpdateEntitlementResultTypeDef",
     {
         "Entitlement": EntitlementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFleetResultTypeDef = TypedDict(
     "CreateFleetResultTypeDef",
     {
         "Fleet": FleetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetsResultTypeDef = TypedDict(
     "DescribeFleetsResultTypeDef",
     {
         "Fleets": List[FleetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFleetResultTypeDef = TypedDict(
     "UpdateFleetResultTypeDef",
     {
         "Fleet": FleetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSessionsResultTypeDef = TypedDict(
     "DescribeSessionsResultTypeDef",
     {
         "Sessions": List[SessionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateImageBuilderResultTypeDef = TypedDict(
     "CreateImageBuilderResultTypeDef",
     {
         "ImageBuilder": ImageBuilderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteImageBuilderResultTypeDef = TypedDict(
     "DeleteImageBuilderResultTypeDef",
     {
         "ImageBuilder": ImageBuilderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeImageBuildersResultTypeDef = TypedDict(
     "DescribeImageBuildersResultTypeDef",
     {
         "ImageBuilders": List[ImageBuilderTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartImageBuilderResultTypeDef = TypedDict(
     "StartImageBuilderResultTypeDef",
     {
         "ImageBuilder": ImageBuilderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopImageBuilderResultTypeDef = TypedDict(
     "StopImageBuilderResultTypeDef",
     {
         "ImageBuilder": ImageBuilderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeImagePermissionsResultTypeDef = TypedDict(
     "DescribeImagePermissionsResultTypeDef",
     {
         "Name": str,
         "SharedImagePermissionsList": List[SharedImagePermissionsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUsageReportSubscriptionsResultTypeDef = TypedDict(
     "DescribeUsageReportSubscriptionsResultTypeDef",
     {
         "UsageReportSubscriptions": List[UsageReportSubscriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateStackResultTypeDef = TypedDict(
     "CreateStackResultTypeDef",
     {
         "Stack": StackTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStacksResultTypeDef = TypedDict(
     "DescribeStacksResultTypeDef",
     {
         "Stacks": List[StackTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateStackResultTypeDef = TypedDict(
     "UpdateStackResultTypeDef",
     {
         "Stack": StackTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateUpdatedImageResultTypeDef = TypedDict(
     "CreateUpdatedImageResultTypeDef",
     {
         "image": ImageTypeDef,
         "canUpdateImage": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteImageResultTypeDef = TypedDict(
     "DeleteImageResultTypeDef",
     {
         "Image": ImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeImagesResultTypeDef = TypedDict(
     "DescribeImagesResultTypeDef",
     {
         "Images": List[ImageTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAppBlockResultTypeDef = TypedDict(
     "CreateAppBlockResultTypeDef",
     {
         "AppBlock": AppBlockTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppBlocksResultTypeDef = TypedDict(
     "DescribeAppBlocksResultTypeDef",
     {
         "AppBlocks": List[AppBlockTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/type_defs.pyi` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -56,58 +56,68 @@
 __all__ = (
     "AccessEndpointTypeDef",
     "S3LocationTypeDef",
     "ApplicationFleetAssociationTypeDef",
     "ApplicationSettingsResponseTypeDef",
     "ApplicationSettingsTypeDef",
     "AssociateApplicationFleetRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AssociateApplicationToEntitlementRequestRequestTypeDef",
     "AssociateFleetRequestRequestTypeDef",
     "UserStackAssociationTypeDef",
     "CertificateBasedAuthPropertiesTypeDef",
     "ComputeCapacityStatusTypeDef",
     "ComputeCapacityTypeDef",
     "CopyImageRequestRequestTypeDef",
+    "CopyImageResponseTypeDef",
     "ServiceAccountCredentialsTypeDef",
     "EntitlementAttributeTypeDef",
     "DomainJoinInfoTypeDef",
     "VpcConfigTypeDef",
     "CreateImageBuilderStreamingURLRequestRequestTypeDef",
+    "CreateImageBuilderStreamingURLResultTypeDef",
     "StorageConnectorTypeDef",
     "StreamingExperienceSettingsTypeDef",
     "UserSettingTypeDef",
     "CreateStreamingURLRequestRequestTypeDef",
+    "CreateStreamingURLResultTypeDef",
     "CreateUpdatedImageRequestRequestTypeDef",
+    "CreateUsageReportSubscriptionResultTypeDef",
     "CreateUserRequestRequestTypeDef",
     "DeleteAppBlockRequestRequestTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DeleteDirectoryConfigRequestRequestTypeDef",
     "DeleteEntitlementRequestRequestTypeDef",
     "DeleteFleetRequestRequestTypeDef",
     "DeleteImageBuilderRequestRequestTypeDef",
     "DeleteImagePermissionsRequestRequestTypeDef",
     "DeleteImageRequestRequestTypeDef",
     "DeleteStackRequestRequestTypeDef",
     "DeleteUserRequestRequestTypeDef",
     "DescribeAppBlocksRequestRequestTypeDef",
     "DescribeApplicationFleetAssociationsRequestRequestTypeDef",
     "DescribeApplicationsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef",
     "DescribeDirectoryConfigsRequestRequestTypeDef",
     "DescribeEntitlementsRequestRequestTypeDef",
+    "DescribeFleetsRequestDescribeFleetsPaginateTypeDef",
     "WaiterConfigTypeDef",
     "DescribeFleetsRequestRequestTypeDef",
+    "DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef",
     "DescribeImageBuildersRequestRequestTypeDef",
     "DescribeImagePermissionsRequestRequestTypeDef",
+    "DescribeImagesRequestDescribeImagesPaginateTypeDef",
     "DescribeImagesRequestRequestTypeDef",
+    "DescribeSessionsRequestDescribeSessionsPaginateTypeDef",
     "DescribeSessionsRequestRequestTypeDef",
+    "DescribeStacksRequestDescribeStacksPaginateTypeDef",
     "DescribeStacksRequestRequestTypeDef",
     "DescribeUsageReportSubscriptionsRequestRequestTypeDef",
+    "DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef",
     "DescribeUserStackAssociationsRequestRequestTypeDef",
+    "DescribeUsersRequestDescribeUsersPaginateTypeDef",
     "DescribeUsersRequestRequestTypeDef",
     "UserTypeDef",
     "DisableUserRequestRequestTypeDef",
     "DisassociateApplicationFleetRequestRequestTypeDef",
     "DisassociateApplicationFromEntitlementRequestRequestTypeDef",
     "DisassociateFleetRequestRequestTypeDef",
     "EnableUserRequestRequestTypeDef",
@@ -116,38 +126,38 @@
     "FleetErrorTypeDef",
     "ImageBuilderStateChangeReasonTypeDef",
     "NetworkAccessConfigurationTypeDef",
     "ResourceErrorTypeDef",
     "ImagePermissionsTypeDef",
     "ImageStateChangeReasonTypeDef",
     "LastReportGenerationExecutionErrorTypeDef",
+    "ListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef",
     "ListAssociatedFleetsRequestRequestTypeDef",
+    "ListAssociatedFleetsResultTypeDef",
+    "ListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef",
     "ListAssociatedStacksRequestRequestTypeDef",
+    "ListAssociatedStacksResultTypeDef",
     "ListEntitledApplicationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "StackErrorTypeDef",
     "StartFleetRequestRequestTypeDef",
     "StartImageBuilderRequestRequestTypeDef",
     "StopFleetRequestRequestTypeDef",
     "StopImageBuilderRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "ApplicationTypeDef",
     "CreateApplicationRequestRequestTypeDef",
     "ScriptDetailsTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
     "AssociateApplicationFleetResultTypeDef",
-    "CopyImageResponseTypeDef",
-    "CreateImageBuilderStreamingURLResultTypeDef",
-    "CreateStreamingURLResultTypeDef",
-    "CreateUsageReportSubscriptionResultTypeDef",
     "DescribeApplicationFleetAssociationsResultTypeDef",
-    "ListAssociatedFleetsResultTypeDef",
-    "ListAssociatedStacksResultTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "BatchAssociateUserStackRequestRequestTypeDef",
     "BatchDisassociateUserStackRequestRequestTypeDef",
     "DescribeUserStackAssociationsResultTypeDef",
     "UserStackAssociationErrorTypeDef",
     "CreateDirectoryConfigRequestRequestTypeDef",
     "DirectoryConfigTypeDef",
     "UpdateDirectoryConfigRequestRequestTypeDef",
@@ -155,24 +165,14 @@
     "EntitlementTypeDef",
     "UpdateEntitlementRequestRequestTypeDef",
     "CreateFleetRequestRequestTypeDef",
     "CreateImageBuilderRequestRequestTypeDef",
     "UpdateFleetRequestRequestTypeDef",
     "CreateStackRequestRequestTypeDef",
     "UpdateStackRequestRequestTypeDef",
-    "DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef",
-    "DescribeFleetsRequestDescribeFleetsPaginateTypeDef",
-    "DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef",
-    "DescribeImagesRequestDescribeImagesPaginateTypeDef",
-    "DescribeSessionsRequestDescribeSessionsPaginateTypeDef",
-    "DescribeStacksRequestDescribeStacksPaginateTypeDef",
-    "DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef",
-    "DescribeUsersRequestDescribeUsersPaginateTypeDef",
-    "ListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef",
-    "ListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef",
     "DescribeFleetsRequestFleetStartedWaitTypeDef",
     "DescribeFleetsRequestFleetStoppedWaitTypeDef",
     "DescribeUsersResultTypeDef",
     "ListEntitledApplicationsResultTypeDef",
     "FleetTypeDef",
     "SessionTypeDef",
     "ImageBuilderTypeDef",
@@ -281,25 +281,14 @@
     "AssociateApplicationFleetRequestRequestTypeDef",
     {
         "FleetName": str,
         "ApplicationArn": str,
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
 AssociateApplicationToEntitlementRequestRequestTypeDef = TypedDict(
     "AssociateApplicationToEntitlementRequestRequestTypeDef",
     {
         "StackName": str,
         "EntitlementName": str,
         "ApplicationIdentifier": str,
     },
@@ -388,14 +377,22 @@
 )
 
 class CopyImageRequestRequestTypeDef(
     _RequiredCopyImageRequestRequestTypeDef, _OptionalCopyImageRequestRequestTypeDef
 ):
     pass
 
+CopyImageResponseTypeDef = TypedDict(
+    "CopyImageResponseTypeDef",
+    {
+        "DestinationImageName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ServiceAccountCredentialsTypeDef = TypedDict(
     "ServiceAccountCredentialsTypeDef",
     {
         "AccountName": str,
         "AccountPassword": str,
     },
 )
@@ -442,14 +439,23 @@
 
 class CreateImageBuilderStreamingURLRequestRequestTypeDef(
     _RequiredCreateImageBuilderStreamingURLRequestRequestTypeDef,
     _OptionalCreateImageBuilderStreamingURLRequestRequestTypeDef,
 ):
     pass
 
+CreateImageBuilderStreamingURLResultTypeDef = TypedDict(
+    "CreateImageBuilderStreamingURLResultTypeDef",
+    {
+        "StreamingURL": str,
+        "Expires": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStorageConnectorTypeDef = TypedDict(
     "_RequiredStorageConnectorTypeDef",
     {
         "ConnectorType": StorageConnectorTypeType,
     },
 )
 _OptionalStorageConnectorTypeDef = TypedDict(
@@ -500,14 +506,23 @@
 
 class CreateStreamingURLRequestRequestTypeDef(
     _RequiredCreateStreamingURLRequestRequestTypeDef,
     _OptionalCreateStreamingURLRequestRequestTypeDef,
 ):
     pass
 
+CreateStreamingURLResultTypeDef = TypedDict(
+    "CreateStreamingURLResultTypeDef",
+    {
+        "StreamingURL": str,
+        "Expires": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateUpdatedImageRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUpdatedImageRequestRequestTypeDef",
     {
         "existingImageName": str,
         "newImageName": str,
     },
 )
@@ -524,14 +539,23 @@
 
 class CreateUpdatedImageRequestRequestTypeDef(
     _RequiredCreateUpdatedImageRequestRequestTypeDef,
     _OptionalCreateUpdatedImageRequestRequestTypeDef,
 ):
     pass
 
+CreateUsageReportSubscriptionResultTypeDef = TypedDict(
+    "CreateUsageReportSubscriptionResultTypeDef",
+    {
+        "S3BucketName": str,
+        "Schedule": Literal["DAILY"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateUserRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserRequestRequestTypeDef",
     {
         "UserName": str,
         "AuthenticationType": AuthenticationTypeType,
     },
 )
@@ -650,20 +674,19 @@
         "Arns": Sequence[str],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef = TypedDict(
+    "DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "DirectoryNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeDirectoryConfigsRequestRequestTypeDef = TypedDict(
     "DescribeDirectoryConfigsRequestRequestTypeDef",
     {
@@ -692,14 +715,23 @@
 
 class DescribeEntitlementsRequestRequestTypeDef(
     _RequiredDescribeEntitlementsRequestRequestTypeDef,
     _OptionalDescribeEntitlementsRequestRequestTypeDef,
 ):
     pass
 
+DescribeFleetsRequestDescribeFleetsPaginateTypeDef = TypedDict(
+    "DescribeFleetsRequestDescribeFleetsPaginateTypeDef",
+    {
+        "Names": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -710,14 +742,23 @@
     {
         "Names": Sequence[str],
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef = TypedDict(
+    "DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef",
+    {
+        "Names": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeImageBuildersRequestRequestTypeDef = TypedDict(
     "DescribeImageBuildersRequestRequestTypeDef",
     {
         "Names": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
@@ -742,26 +783,60 @@
 
 class DescribeImagePermissionsRequestRequestTypeDef(
     _RequiredDescribeImagePermissionsRequestRequestTypeDef,
     _OptionalDescribeImagePermissionsRequestRequestTypeDef,
 ):
     pass
 
+DescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
+    "DescribeImagesRequestDescribeImagesPaginateTypeDef",
+    {
+        "Names": Sequence[str],
+        "Arns": Sequence[str],
+        "Type": VisibilityTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeImagesRequestRequestTypeDef = TypedDict(
     "DescribeImagesRequestRequestTypeDef",
     {
         "Names": Sequence[str],
         "Arns": Sequence[str],
         "Type": VisibilityTypeType,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredDescribeSessionsRequestDescribeSessionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeSessionsRequestDescribeSessionsPaginateTypeDef",
+    {
+        "StackName": str,
+        "FleetName": str,
+    },
+)
+_OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef",
+    {
+        "UserId": str,
+        "AuthenticationType": AuthenticationTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeSessionsRequestDescribeSessionsPaginateTypeDef(
+    _RequiredDescribeSessionsRequestDescribeSessionsPaginateTypeDef,
+    _OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeSessionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeSessionsRequestRequestTypeDef",
     {
         "StackName": str,
         "FleetName": str,
     },
 )
@@ -777,14 +852,23 @@
 )
 
 class DescribeSessionsRequestRequestTypeDef(
     _RequiredDescribeSessionsRequestRequestTypeDef, _OptionalDescribeSessionsRequestRequestTypeDef
 ):
     pass
 
+DescribeStacksRequestDescribeStacksPaginateTypeDef = TypedDict(
+    "DescribeStacksRequestDescribeStacksPaginateTypeDef",
+    {
+        "Names": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeStacksRequestRequestTypeDef = TypedDict(
     "DescribeStacksRequestRequestTypeDef",
     {
         "Names": Sequence[str],
         "NextToken": str,
     },
     total=False,
@@ -795,26 +879,57 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef = TypedDict(
+    "DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef",
+    {
+        "StackName": str,
+        "UserName": str,
+        "AuthenticationType": AuthenticationTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeUserStackAssociationsRequestRequestTypeDef = TypedDict(
     "DescribeUserStackAssociationsRequestRequestTypeDef",
     {
         "StackName": str,
         "UserName": str,
         "AuthenticationType": AuthenticationTypeType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredDescribeUsersRequestDescribeUsersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeUsersRequestDescribeUsersPaginateTypeDef",
+    {
+        "AuthenticationType": AuthenticationTypeType,
+    },
+)
+_OptionalDescribeUsersRequestDescribeUsersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeUsersRequestDescribeUsersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeUsersRequestDescribeUsersPaginateTypeDef(
+    _RequiredDescribeUsersRequestDescribeUsersPaginateTypeDef,
+    _OptionalDescribeUsersRequestDescribeUsersPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeUsersRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeUsersRequestRequestTypeDef",
     {
         "AuthenticationType": AuthenticationTypeType,
     },
 )
 _OptionalDescribeUsersRequestRequestTypeDef = TypedDict(
@@ -969,14 +1084,34 @@
     {
         "ErrorCode": UsageReportExecutionErrorCodeType,
         "ErrorMessage": str,
     },
     total=False,
 )
 
+_RequiredListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef = TypedDict(
+    "_RequiredListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef",
+    {
+        "StackName": str,
+    },
+)
+_OptionalListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef = TypedDict(
+    "_OptionalListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef(
+    _RequiredListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef,
+    _OptionalListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef,
+):
+    pass
+
 _RequiredListAssociatedFleetsRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociatedFleetsRequestRequestTypeDef",
     {
         "StackName": str,
     },
 )
 _OptionalListAssociatedFleetsRequestRequestTypeDef = TypedDict(
@@ -989,14 +1124,43 @@
 
 class ListAssociatedFleetsRequestRequestTypeDef(
     _RequiredListAssociatedFleetsRequestRequestTypeDef,
     _OptionalListAssociatedFleetsRequestRequestTypeDef,
 ):
     pass
 
+ListAssociatedFleetsResultTypeDef = TypedDict(
+    "ListAssociatedFleetsResultTypeDef",
+    {
+        "Names": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef = TypedDict(
+    "_RequiredListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef",
+    {
+        "FleetName": str,
+    },
+)
+_OptionalListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef = TypedDict(
+    "_OptionalListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef(
+    _RequiredListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef,
+    _OptionalListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef,
+):
+    pass
+
 _RequiredListAssociatedStacksRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociatedStacksRequestRequestTypeDef",
     {
         "FleetName": str,
     },
 )
 _OptionalListAssociatedStacksRequestRequestTypeDef = TypedDict(
@@ -1009,14 +1173,23 @@
 
 class ListAssociatedStacksRequestRequestTypeDef(
     _RequiredListAssociatedStacksRequestRequestTypeDef,
     _OptionalListAssociatedStacksRequestRequestTypeDef,
 ):
     pass
 
+ListAssociatedStacksResultTypeDef = TypedDict(
+    "ListAssociatedStacksResultTypeDef",
+    {
+        "Names": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListEntitledApplicationsRequestRequestTypeDef = TypedDict(
     "_RequiredListEntitledApplicationsRequestRequestTypeDef",
     {
         "StackName": str,
         "EntitlementName": str,
     },
 )
@@ -1038,14 +1211,43 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
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
 StackErrorTypeDef = TypedDict(
     "StackErrorTypeDef",
     {
         "ErrorCode": StackErrorCodeType,
         "ErrorMessage": str,
     },
     total=False,
@@ -1202,85 +1404,24 @@
 ):
     pass
 
 AssociateApplicationFleetResultTypeDef = TypedDict(
     "AssociateApplicationFleetResultTypeDef",
     {
         "ApplicationFleetAssociation": ApplicationFleetAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CopyImageResponseTypeDef = TypedDict(
-    "CopyImageResponseTypeDef",
-    {
-        "DestinationImageName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateImageBuilderStreamingURLResultTypeDef = TypedDict(
-    "CreateImageBuilderStreamingURLResultTypeDef",
-    {
-        "StreamingURL": str,
-        "Expires": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStreamingURLResultTypeDef = TypedDict(
-    "CreateStreamingURLResultTypeDef",
-    {
-        "StreamingURL": str,
-        "Expires": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUsageReportSubscriptionResultTypeDef = TypedDict(
-    "CreateUsageReportSubscriptionResultTypeDef",
-    {
-        "S3BucketName": str,
-        "Schedule": Literal["DAILY"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeApplicationFleetAssociationsResultTypeDef = TypedDict(
     "DescribeApplicationFleetAssociationsResultTypeDef",
     {
         "ApplicationFleetAssociations": List[ApplicationFleetAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAssociatedFleetsResultTypeDef = TypedDict(
-    "ListAssociatedFleetsResultTypeDef",
-    {
-        "Names": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAssociatedStacksResultTypeDef = TypedDict(
-    "ListAssociatedStacksResultTypeDef",
-    {
-        "Names": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchAssociateUserStackRequestRequestTypeDef = TypedDict(
     "BatchAssociateUserStackRequestRequestTypeDef",
     {
         "UserStackAssociations": Sequence[UserStackAssociationTypeDef],
@@ -1295,15 +1436,15 @@
 )
 
 DescribeUserStackAssociationsResultTypeDef = TypedDict(
     "DescribeUserStackAssociationsResultTypeDef",
     {
         "UserStackAssociations": List[UserStackAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UserStackAssociationErrorTypeDef = TypedDict(
     "UserStackAssociationErrorTypeDef",
     {
         "UserStackAssociation": UserStackAssociationTypeDef,
@@ -1595,155 +1736,14 @@
 )
 
 class UpdateStackRequestRequestTypeDef(
     _RequiredUpdateStackRequestRequestTypeDef, _OptionalUpdateStackRequestRequestTypeDef
 ):
     pass
 
-DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef = TypedDict(
-    "DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef",
-    {
-        "DirectoryNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeFleetsRequestDescribeFleetsPaginateTypeDef = TypedDict(
-    "DescribeFleetsRequestDescribeFleetsPaginateTypeDef",
-    {
-        "Names": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef = TypedDict(
-    "DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef",
-    {
-        "Names": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
-    "DescribeImagesRequestDescribeImagesPaginateTypeDef",
-    {
-        "Names": Sequence[str],
-        "Arns": Sequence[str],
-        "Type": VisibilityTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeSessionsRequestDescribeSessionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeSessionsRequestDescribeSessionsPaginateTypeDef",
-    {
-        "StackName": str,
-        "FleetName": str,
-    },
-)
-_OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef",
-    {
-        "UserId": str,
-        "AuthenticationType": AuthenticationTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeSessionsRequestDescribeSessionsPaginateTypeDef(
-    _RequiredDescribeSessionsRequestDescribeSessionsPaginateTypeDef,
-    _OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef,
-):
-    pass
-
-DescribeStacksRequestDescribeStacksPaginateTypeDef = TypedDict(
-    "DescribeStacksRequestDescribeStacksPaginateTypeDef",
-    {
-        "Names": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef = TypedDict(
-    "DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef",
-    {
-        "StackName": str,
-        "UserName": str,
-        "AuthenticationType": AuthenticationTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeUsersRequestDescribeUsersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeUsersRequestDescribeUsersPaginateTypeDef",
-    {
-        "AuthenticationType": AuthenticationTypeType,
-    },
-)
-_OptionalDescribeUsersRequestDescribeUsersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeUsersRequestDescribeUsersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeUsersRequestDescribeUsersPaginateTypeDef(
-    _RequiredDescribeUsersRequestDescribeUsersPaginateTypeDef,
-    _OptionalDescribeUsersRequestDescribeUsersPaginateTypeDef,
-):
-    pass
-
-_RequiredListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef = TypedDict(
-    "_RequiredListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef",
-    {
-        "StackName": str,
-    },
-)
-_OptionalListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef = TypedDict(
-    "_OptionalListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef(
-    _RequiredListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef,
-    _OptionalListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef,
-):
-    pass
-
-_RequiredListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef = TypedDict(
-    "_RequiredListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef",
-    {
-        "FleetName": str,
-    },
-)
-_OptionalListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef = TypedDict(
-    "_OptionalListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef(
-    _RequiredListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef,
-    _OptionalListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef,
-):
-    pass
-
 DescribeFleetsRequestFleetStartedWaitTypeDef = TypedDict(
     "DescribeFleetsRequestFleetStartedWaitTypeDef",
     {
         "Names": Sequence[str],
         "NextToken": str,
         "WaiterConfig": WaiterConfigTypeDef,
     },
@@ -1761,24 +1761,24 @@
 )
 
 DescribeUsersResultTypeDef = TypedDict(
     "DescribeUsersResultTypeDef",
     {
         "Users": List[UserTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEntitledApplicationsResultTypeDef = TypedDict(
     "ListEntitledApplicationsResultTypeDef",
     {
         "EntitledApplications": List[EntitledApplicationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFleetTypeDef = TypedDict(
     "_RequiredFleetTypeDef",
     {
         "Arn": str,
@@ -1932,24 +1932,24 @@
 class StackTypeDef(_RequiredStackTypeDef, _OptionalStackTypeDef):
     pass
 
 CreateApplicationResultTypeDef = TypedDict(
     "CreateApplicationResultTypeDef",
     {
         "Application": ApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeApplicationsResultTypeDef = TypedDict(
     "DescribeApplicationsResultTypeDef",
     {
         "Applications": List[ApplicationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImageTypeDef = TypedDict(
     "_RequiredImageTypeDef",
     {
         "Name": str,
@@ -1981,15 +1981,15 @@
 class ImageTypeDef(_RequiredImageTypeDef, _OptionalImageTypeDef):
     pass
 
 UpdateApplicationResultTypeDef = TypedDict(
     "UpdateApplicationResultTypeDef",
     {
         "Application": ApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAppBlockTypeDef = TypedDict(
     "_RequiredAppBlockTypeDef",
     {
         "Name": str,
@@ -2034,230 +2034,230 @@
 ):
     pass
 
 BatchAssociateUserStackResultTypeDef = TypedDict(
     "BatchAssociateUserStackResultTypeDef",
     {
         "errors": List[UserStackAssociationErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDisassociateUserStackResultTypeDef = TypedDict(
     "BatchDisassociateUserStackResultTypeDef",
     {
         "errors": List[UserStackAssociationErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDirectoryConfigResultTypeDef = TypedDict(
     "CreateDirectoryConfigResultTypeDef",
     {
         "DirectoryConfig": DirectoryConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDirectoryConfigsResultTypeDef = TypedDict(
     "DescribeDirectoryConfigsResultTypeDef",
     {
         "DirectoryConfigs": List[DirectoryConfigTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDirectoryConfigResultTypeDef = TypedDict(
     "UpdateDirectoryConfigResultTypeDef",
     {
         "DirectoryConfig": DirectoryConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEntitlementResultTypeDef = TypedDict(
     "CreateEntitlementResultTypeDef",
     {
         "Entitlement": EntitlementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEntitlementsResultTypeDef = TypedDict(
     "DescribeEntitlementsResultTypeDef",
     {
         "Entitlements": List[EntitlementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEntitlementResultTypeDef = TypedDict(
     "UpdateEntitlementResultTypeDef",
     {
         "Entitlement": EntitlementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFleetResultTypeDef = TypedDict(
     "CreateFleetResultTypeDef",
     {
         "Fleet": FleetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetsResultTypeDef = TypedDict(
     "DescribeFleetsResultTypeDef",
     {
         "Fleets": List[FleetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFleetResultTypeDef = TypedDict(
     "UpdateFleetResultTypeDef",
     {
         "Fleet": FleetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSessionsResultTypeDef = TypedDict(
     "DescribeSessionsResultTypeDef",
     {
         "Sessions": List[SessionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateImageBuilderResultTypeDef = TypedDict(
     "CreateImageBuilderResultTypeDef",
     {
         "ImageBuilder": ImageBuilderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteImageBuilderResultTypeDef = TypedDict(
     "DeleteImageBuilderResultTypeDef",
     {
         "ImageBuilder": ImageBuilderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeImageBuildersResultTypeDef = TypedDict(
     "DescribeImageBuildersResultTypeDef",
     {
         "ImageBuilders": List[ImageBuilderTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartImageBuilderResultTypeDef = TypedDict(
     "StartImageBuilderResultTypeDef",
     {
         "ImageBuilder": ImageBuilderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopImageBuilderResultTypeDef = TypedDict(
     "StopImageBuilderResultTypeDef",
     {
         "ImageBuilder": ImageBuilderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeImagePermissionsResultTypeDef = TypedDict(
     "DescribeImagePermissionsResultTypeDef",
     {
         "Name": str,
         "SharedImagePermissionsList": List[SharedImagePermissionsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUsageReportSubscriptionsResultTypeDef = TypedDict(
     "DescribeUsageReportSubscriptionsResultTypeDef",
     {
         "UsageReportSubscriptions": List[UsageReportSubscriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateStackResultTypeDef = TypedDict(
     "CreateStackResultTypeDef",
     {
         "Stack": StackTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStacksResultTypeDef = TypedDict(
     "DescribeStacksResultTypeDef",
     {
         "Stacks": List[StackTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateStackResultTypeDef = TypedDict(
     "UpdateStackResultTypeDef",
     {
         "Stack": StackTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateUpdatedImageResultTypeDef = TypedDict(
     "CreateUpdatedImageResultTypeDef",
     {
         "image": ImageTypeDef,
         "canUpdateImage": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteImageResultTypeDef = TypedDict(
     "DeleteImageResultTypeDef",
     {
         "Image": ImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeImagesResultTypeDef = TypedDict(
     "DescribeImagesResultTypeDef",
     {
         "Images": List[ImageTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAppBlockResultTypeDef = TypedDict(
     "CreateAppBlockResultTypeDef",
     {
         "AppBlock": AppBlockTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppBlocksResultTypeDef = TypedDict(
     "DescribeAppBlocksResultTypeDef",
     {
         "AppBlocks": List[AppBlockTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/waiter.py` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream/waiter.pyi` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream.egg-info/PKG-INFO` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-appstream
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AppStream 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AppStream 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-appstream"></a>
 
 # types-aiobotocore-appstream
 
 [![PyPI - types-aiobotocore-appstream](https://img.shields.io/pypi/v/types-aiobotocore-appstream.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appstream)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appstream.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appstream)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appstream?color=blue)](https://pypistats.org/packages/types-aiobotocore-appstream)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppStream 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream)
+[aiobotocore.AppStream 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appstream.html#AppStream)
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
 [types-aiobotocore-appstream docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appstream/).
 
 See how it helps to find and fix potential bugs:
 
@@ -416,58 +416,68 @@
 from types_aiobotocore_appstream.type_defs import (
     AccessEndpointTypeDef,
     S3LocationTypeDef,
     ApplicationFleetAssociationTypeDef,
     ApplicationSettingsResponseTypeDef,
     ApplicationSettingsTypeDef,
     AssociateApplicationFleetRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AssociateApplicationToEntitlementRequestRequestTypeDef,
     AssociateFleetRequestRequestTypeDef,
     UserStackAssociationTypeDef,
     CertificateBasedAuthPropertiesTypeDef,
     ComputeCapacityStatusTypeDef,
     ComputeCapacityTypeDef,
     CopyImageRequestRequestTypeDef,
+    CopyImageResponseTypeDef,
     ServiceAccountCredentialsTypeDef,
     EntitlementAttributeTypeDef,
     DomainJoinInfoTypeDef,
     VpcConfigTypeDef,
     CreateImageBuilderStreamingURLRequestRequestTypeDef,
+    CreateImageBuilderStreamingURLResultTypeDef,
     StorageConnectorTypeDef,
     StreamingExperienceSettingsTypeDef,
     UserSettingTypeDef,
     CreateStreamingURLRequestRequestTypeDef,
+    CreateStreamingURLResultTypeDef,
     CreateUpdatedImageRequestRequestTypeDef,
+    CreateUsageReportSubscriptionResultTypeDef,
     CreateUserRequestRequestTypeDef,
     DeleteAppBlockRequestRequestTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteDirectoryConfigRequestRequestTypeDef,
     DeleteEntitlementRequestRequestTypeDef,
     DeleteFleetRequestRequestTypeDef,
     DeleteImageBuilderRequestRequestTypeDef,
     DeleteImagePermissionsRequestRequestTypeDef,
     DeleteImageRequestRequestTypeDef,
     DeleteStackRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
     DescribeAppBlocksRequestRequestTypeDef,
     DescribeApplicationFleetAssociationsRequestRequestTypeDef,
     DescribeApplicationsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef,
     DescribeDirectoryConfigsRequestRequestTypeDef,
     DescribeEntitlementsRequestRequestTypeDef,
+    DescribeFleetsRequestDescribeFleetsPaginateTypeDef,
     WaiterConfigTypeDef,
     DescribeFleetsRequestRequestTypeDef,
+    DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef,
     DescribeImageBuildersRequestRequestTypeDef,
     DescribeImagePermissionsRequestRequestTypeDef,
+    DescribeImagesRequestDescribeImagesPaginateTypeDef,
     DescribeImagesRequestRequestTypeDef,
+    DescribeSessionsRequestDescribeSessionsPaginateTypeDef,
     DescribeSessionsRequestRequestTypeDef,
+    DescribeStacksRequestDescribeStacksPaginateTypeDef,
     DescribeStacksRequestRequestTypeDef,
     DescribeUsageReportSubscriptionsRequestRequestTypeDef,
+    DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef,
     DescribeUserStackAssociationsRequestRequestTypeDef,
+    DescribeUsersRequestDescribeUsersPaginateTypeDef,
     DescribeUsersRequestRequestTypeDef,
     UserTypeDef,
     DisableUserRequestRequestTypeDef,
     DisassociateApplicationFleetRequestRequestTypeDef,
     DisassociateApplicationFromEntitlementRequestRequestTypeDef,
     DisassociateFleetRequestRequestTypeDef,
     EnableUserRequestRequestTypeDef,
@@ -476,38 +486,38 @@
     FleetErrorTypeDef,
     ImageBuilderStateChangeReasonTypeDef,
     NetworkAccessConfigurationTypeDef,
     ResourceErrorTypeDef,
     ImagePermissionsTypeDef,
     ImageStateChangeReasonTypeDef,
     LastReportGenerationExecutionErrorTypeDef,
+    ListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef,
     ListAssociatedFleetsRequestRequestTypeDef,
+    ListAssociatedFleetsResultTypeDef,
+    ListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef,
     ListAssociatedStacksRequestRequestTypeDef,
+    ListAssociatedStacksResultTypeDef,
     ListEntitledApplicationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StackErrorTypeDef,
     StartFleetRequestRequestTypeDef,
     StartImageBuilderRequestRequestTypeDef,
     StopFleetRequestRequestTypeDef,
     StopImageBuilderRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ApplicationTypeDef,
     CreateApplicationRequestRequestTypeDef,
     ScriptDetailsTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     AssociateApplicationFleetResultTypeDef,
-    CopyImageResponseTypeDef,
-    CreateImageBuilderStreamingURLResultTypeDef,
-    CreateStreamingURLResultTypeDef,
-    CreateUsageReportSubscriptionResultTypeDef,
     DescribeApplicationFleetAssociationsResultTypeDef,
-    ListAssociatedFleetsResultTypeDef,
-    ListAssociatedStacksResultTypeDef,
-    ListTagsForResourceResponseTypeDef,
     BatchAssociateUserStackRequestRequestTypeDef,
     BatchDisassociateUserStackRequestRequestTypeDef,
     DescribeUserStackAssociationsResultTypeDef,
     UserStackAssociationErrorTypeDef,
     CreateDirectoryConfigRequestRequestTypeDef,
     DirectoryConfigTypeDef,
     UpdateDirectoryConfigRequestRequestTypeDef,
@@ -515,24 +525,14 @@
     EntitlementTypeDef,
     UpdateEntitlementRequestRequestTypeDef,
     CreateFleetRequestRequestTypeDef,
     CreateImageBuilderRequestRequestTypeDef,
     UpdateFleetRequestRequestTypeDef,
     CreateStackRequestRequestTypeDef,
     UpdateStackRequestRequestTypeDef,
-    DescribeDirectoryConfigsRequestDescribeDirectoryConfigsPaginateTypeDef,
-    DescribeFleetsRequestDescribeFleetsPaginateTypeDef,
-    DescribeImageBuildersRequestDescribeImageBuildersPaginateTypeDef,
-    DescribeImagesRequestDescribeImagesPaginateTypeDef,
-    DescribeSessionsRequestDescribeSessionsPaginateTypeDef,
-    DescribeStacksRequestDescribeStacksPaginateTypeDef,
-    DescribeUserStackAssociationsRequestDescribeUserStackAssociationsPaginateTypeDef,
-    DescribeUsersRequestDescribeUsersPaginateTypeDef,
-    ListAssociatedFleetsRequestListAssociatedFleetsPaginateTypeDef,
-    ListAssociatedStacksRequestListAssociatedStacksPaginateTypeDef,
     DescribeFleetsRequestFleetStartedWaitTypeDef,
     DescribeFleetsRequestFleetStoppedWaitTypeDef,
     DescribeUsersResultTypeDef,
     ListEntitledApplicationsResultTypeDef,
     FleetTypeDef,
     SessionTypeDef,
     ImageBuilderTypeDef,
@@ -583,43 +583,43 @@
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

### Comparing `types-aiobotocore-appstream-2.5.0.post1/types_aiobotocore_appstream.egg-info/SOURCES.txt` & `types-aiobotocore-appstream-2.5.1/types_aiobotocore_appstream.egg-info/SOURCES.txt`

 * *Files identical despite different names*


# Comparing `tmp/types-aiobotocore-workdocs-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-workdocs-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-workdocs-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:30 2023, max compression
+gzip compressed data, was "types-aiobotocore-workdocs-2.5.1.tar", last modified: Wed Jun 28 01:44:20 2023, max compression
```

## Comparing `types-aiobotocore-workdocs-2.5.0.post1.tar` & `types-aiobotocore-workdocs-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.207720 types-aiobotocore-workdocs-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:34.000000 types-aiobotocore-workdocs-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19360 2023-03-11 12:27:30.207720 types-aiobotocore-workdocs-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17785 2023-03-11 12:25:34.000000 types-aiobotocore-workdocs-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:30.207720 types-aiobotocore-workdocs-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:25:34.000000 types-aiobotocore-workdocs-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.207720 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/
--rw-r--r--   0 runner    (1001) docker     (123)     2569 2023-03-11 12:25:34.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2568 2023-03-11 12:25:34.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:25:34.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    39358 2023-03-11 12:25:35.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    39297 2023-03-11 12:25:34.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12093 2023-03-11 12:25:35.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    12091 2023-03-11 12:25:35.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12911 2023-03-11 12:25:35.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    12899 2023-03-11 12:25:35.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:34.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    46858 2023-03-11 12:25:39.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    46769 2023-03-11 12:25:35.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:34.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:30.207720 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19360 2023-03-11 12:27:30.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      832 2023-03-11 12:27:30.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:30.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:30.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:30.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:27:30.000000 types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.190232 types-aiobotocore-workdocs-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:42:31.000000 types-aiobotocore-workdocs-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20089 2023-06-28 01:44:20.190232 types-aiobotocore-workdocs-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    18520 2023-06-28 01:42:31.000000 types-aiobotocore-workdocs-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:20.190232 types-aiobotocore-workdocs-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:42:31.000000 types-aiobotocore-workdocs-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.190232 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/
+-rw-r--r--   0 runner    (1001) docker     (123)     2765 2023-06-28 01:42:31.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2764 2023-06-28 01:42:31.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:42:31.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40882 2023-06-28 01:42:32.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40819 2023-06-28 01:42:31.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    13805 2023-06-28 01:42:32.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13803 2023-06-28 01:42:32.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14449 2023-06-28 01:42:32.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14436 2023-06-28 01:42:32.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:42:31.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    50632 2023-06-28 01:42:33.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    50541 2023-06-28 01:42:32.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:42:31.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.190232 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20089 2023-06-28 01:44:20.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      832 2023-06-28 01:44:20.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:20.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:20.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:20.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:44:20.000000 types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/LICENSE` & `types-aiobotocore-workdocs-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/PKG-INFO` & `types-aiobotocore-workdocs-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-workdocs
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.WorkDocs 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.WorkDocs 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-workdocs"></a>
 
 # types-aiobotocore-workdocs
 
 [![PyPI - types-aiobotocore-workdocs](https://img.shields.io/pypi/v/types-aiobotocore-workdocs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workdocs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-workdocs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workdocs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-workdocs?color=blue)](https://pypistats.org/packages/types-aiobotocore-workdocs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkDocs 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs)
+[aiobotocore.WorkDocs 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs)
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
 [types-aiobotocore-workdocs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -281,14 +281,15 @@
     DescribeDocumentVersionsPaginator,
     DescribeFolderContentsPaginator,
     DescribeGroupsPaginator,
     DescribeNotificationSubscriptionsPaginator,
     DescribeResourcePermissionsPaginator,
     DescribeRootFoldersPaginator,
     DescribeUsersPaginator,
+    SearchResourcesPaginator,
 )
 
 session = get_session()
 async with session.create_client("workdocs") as client:
     client: WorkDocsClient
 
     # Explicit type annotations are optional here
@@ -312,53 +313,65 @@
     describe_resource_permissions_paginator: DescribeResourcePermissionsPaginator = (
         client.get_paginator("describe_resource_permissions")
     )
     describe_root_folders_paginator: DescribeRootFoldersPaginator = client.get_paginator(
         "describe_root_folders"
     )
     describe_users_paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
+    search_resources_paginator: SearchResourcesPaginator = client.get_paginator("search_resources")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_workdocs.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_workdocs.literals import (
     ActivityTypeType,
+    AdditionalResponseFieldTypeType,
     BooleanEnumTypeType,
     CommentStatusTypeType,
     CommentVisibilityTypeType,
+    ContentCategoryTypeType,
     DescribeActivitiesPaginatorName,
     DescribeCommentsPaginatorName,
     DescribeDocumentVersionsPaginatorName,
     DescribeFolderContentsPaginatorName,
     DescribeGroupsPaginatorName,
     DescribeNotificationSubscriptionsPaginatorName,
     DescribeResourcePermissionsPaginatorName,
     DescribeRootFoldersPaginatorName,
     DescribeUsersPaginatorName,
     DocumentSourceTypeType,
     DocumentStatusTypeType,
     DocumentThumbnailTypeType,
     DocumentVersionStatusType,
     FolderContentTypeType,
+    LanguageCodeTypeType,
     LocaleTypeType,
+    OrderByFieldTypeType,
     OrderTypeType,
+    PrincipalRoleTypeType,
     PrincipalTypeType,
     ResourceCollectionTypeType,
     ResourceSortTypeType,
     ResourceStateTypeType,
     ResourceTypeType,
+    ResponseItemTypeType,
     RolePermissionTypeType,
     RoleTypeType,
+    SearchCollectionTypeType,
+    SearchQueryScopeTypeType,
+    SearchResourceTypeType,
+    SearchResourcesPaginatorName,
     ShareStatusTypeType,
+    SortOrderType,
     StorageTypeType,
     SubscriptionProtocolTypeType,
     SubscriptionTypeType,
     UserFilterTypeType,
     UserSortTypeType,
     UserStatusTypeType,
     UserTypeType,
@@ -381,156 +394,165 @@
 `types_aiobotocore_workdocs.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_workdocs.type_defs import (
     AbortDocumentVersionUploadRequestRequestTypeDef,
     ActivateUserRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     UserMetadataTypeDef,
     NotificationOptionsTypeDef,
     SharePrincipalTypeDef,
     ShareResultTypeDef,
     CreateCommentRequestRequestTypeDef,
     CreateCustomMetadataRequestRequestTypeDef,
     CreateFolderRequestRequestTypeDef,
     FolderMetadataTypeDef,
     CreateLabelsRequestRequestTypeDef,
     CreateNotificationSubscriptionRequestRequestTypeDef,
     SubscriptionTypeDef,
     StorageRuleTypeTypeDef,
+    DateRangeTypeTypeDef,
     DeactivateUserRequestRequestTypeDef,
     DeleteCommentRequestRequestTypeDef,
     DeleteCustomMetadataRequestRequestTypeDef,
     DeleteDocumentRequestRequestTypeDef,
     DeleteDocumentVersionRequestRequestTypeDef,
     DeleteFolderContentsRequestRequestTypeDef,
     DeleteFolderRequestRequestTypeDef,
     DeleteLabelsRequestRequestTypeDef,
     DeleteNotificationSubscriptionRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef,
     DescribeActivitiesRequestRequestTypeDef,
+    DescribeCommentsRequestDescribeCommentsPaginateTypeDef,
     DescribeCommentsRequestRequestTypeDef,
+    DescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef,
     DescribeDocumentVersionsRequestRequestTypeDef,
     DocumentVersionMetadataTypeDef,
+    DescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef,
     DescribeFolderContentsRequestRequestTypeDef,
+    DescribeGroupsRequestDescribeGroupsPaginateTypeDef,
     DescribeGroupsRequestRequestTypeDef,
     GroupMetadataTypeDef,
+    DescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef,
     DescribeNotificationSubscriptionsRequestRequestTypeDef,
+    DescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef,
     DescribeResourcePermissionsRequestRequestTypeDef,
+    DescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef,
     DescribeRootFoldersRequestRequestTypeDef,
+    DescribeUsersRequestDescribeUsersPaginateTypeDef,
     DescribeUsersRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
+    LongRangeTypeTypeDef,
+    SearchPrincipalTypeTypeDef,
     GetCurrentUserRequestRequestTypeDef,
     GetDocumentPathRequestRequestTypeDef,
     GetDocumentRequestRequestTypeDef,
     GetDocumentVersionRequestRequestTypeDef,
     GetFolderPathRequestRequestTypeDef,
     GetFolderRequestRequestTypeDef,
     GetResourcesRequestRequestTypeDef,
     InitiateDocumentVersionUploadRequestRequestTypeDef,
     UploadMetadataTypeDef,
+    PaginatorConfigTypeDef,
     PermissionInfoTypeDef,
     RemoveAllResourcePermissionsRequestRequestTypeDef,
     RemoveResourcePermissionRequestRequestTypeDef,
     ResourcePathComponentTypeDef,
+    ResponseMetadataTypeDef,
     RestoreDocumentVersionsRequestRequestTypeDef,
+    SearchSortResultTypeDef,
     UpdateDocumentRequestRequestTypeDef,
     UpdateDocumentVersionRequestRequestTypeDef,
     UpdateFolderRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
     ResourceMetadataTypeDef,
     AddResourcePermissionsRequestRequestTypeDef,
     AddResourcePermissionsResponseTypeDef,
     CreateFolderResponseTypeDef,
     DescribeRootFoldersResponseTypeDef,
     GetFolderResponseTypeDef,
     CreateNotificationSubscriptionResponseTypeDef,
     DescribeNotificationSubscriptionsResponseTypeDef,
     CreateUserRequestRequestTypeDef,
     UpdateUserRequestRequestTypeDef,
     UserStorageMetadataTypeDef,
-    DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef,
-    DescribeCommentsRequestDescribeCommentsPaginateTypeDef,
-    DescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef,
-    DescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef,
-    DescribeGroupsRequestDescribeGroupsPaginateTypeDef,
-    DescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef,
-    DescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef,
-    DescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef,
-    DescribeUsersRequestDescribeUsersPaginateTypeDef,
     DescribeDocumentVersionsResponseTypeDef,
     DocumentMetadataTypeDef,
     GetDocumentVersionResponseTypeDef,
     DescribeGroupsResponseTypeDef,
     ParticipantsTypeDef,
+    FiltersTypeDef,
     PrincipalTypeDef,
     ResourcePathTypeDef,
     UserTypeDef,
     DescribeFolderContentsResponseTypeDef,
     GetDocumentResponseTypeDef,
     GetResourcesResponseTypeDef,
     InitiateDocumentVersionUploadResponseTypeDef,
+    SearchResourcesRequestRequestTypeDef,
+    SearchResourcesRequestSearchResourcesPaginateTypeDef,
     DescribeResourcePermissionsResponseTypeDef,
     GetDocumentPathResponseTypeDef,
     GetFolderPathResponseTypeDef,
     ActivateUserResponseTypeDef,
     CommentMetadataTypeDef,
     CommentTypeDef,
     CreateUserResponseTypeDef,
     DescribeUsersResponseTypeDef,
     GetCurrentUserResponseTypeDef,
     UpdateUserResponseTypeDef,
     ActivityTypeDef,
+    ResponseItemTypeDef,
     CreateCommentResponseTypeDef,
     DescribeCommentsResponseTypeDef,
     DescribeActivitiesResponseTypeDef,
+    SearchResourcesResponseTypeDef,
 )
 
 
 def get_structure() -> AbortDocumentVersionUploadRequestRequestTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/README.md` & `types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-workdocs
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.WorkDocs 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore workdocs type-annotations boto3-stubs mypy typeshed autocomplete
+Classifier: Development Status :: 5 - Production/Stable
+Classifier: Intended Audience :: Developers
+Classifier: Environment :: Console
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Natural Language :: English
+Classifier: Operating System :: OS Independent
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
+Classifier: Programming Language :: Python :: 3 :: Only
+Classifier: Programming Language :: Python :: Implementation :: CPython
+Classifier: Typing :: Typed
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 <a id="types-aiobotocore-workdocs"></a>
 
 # types-aiobotocore-workdocs
 
 [![PyPI - types-aiobotocore-workdocs](https://img.shields.io/pypi/v/types-aiobotocore-workdocs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workdocs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-workdocs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workdocs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-workdocs?color=blue)](https://pypistats.org/packages/types-aiobotocore-workdocs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkDocs 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs)
+[aiobotocore.WorkDocs 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs)
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
 [types-aiobotocore-workdocs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -248,14 +281,15 @@
     DescribeDocumentVersionsPaginator,
     DescribeFolderContentsPaginator,
     DescribeGroupsPaginator,
     DescribeNotificationSubscriptionsPaginator,
     DescribeResourcePermissionsPaginator,
     DescribeRootFoldersPaginator,
     DescribeUsersPaginator,
+    SearchResourcesPaginator,
 )
 
 session = get_session()
 async with session.create_client("workdocs") as client:
     client: WorkDocsClient
 
     # Explicit type annotations are optional here
@@ -279,53 +313,65 @@
     describe_resource_permissions_paginator: DescribeResourcePermissionsPaginator = (
         client.get_paginator("describe_resource_permissions")
     )
     describe_root_folders_paginator: DescribeRootFoldersPaginator = client.get_paginator(
         "describe_root_folders"
     )
     describe_users_paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
+    search_resources_paginator: SearchResourcesPaginator = client.get_paginator("search_resources")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_workdocs.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_workdocs.literals import (
     ActivityTypeType,
+    AdditionalResponseFieldTypeType,
     BooleanEnumTypeType,
     CommentStatusTypeType,
     CommentVisibilityTypeType,
+    ContentCategoryTypeType,
     DescribeActivitiesPaginatorName,
     DescribeCommentsPaginatorName,
     DescribeDocumentVersionsPaginatorName,
     DescribeFolderContentsPaginatorName,
     DescribeGroupsPaginatorName,
     DescribeNotificationSubscriptionsPaginatorName,
     DescribeResourcePermissionsPaginatorName,
     DescribeRootFoldersPaginatorName,
     DescribeUsersPaginatorName,
     DocumentSourceTypeType,
     DocumentStatusTypeType,
     DocumentThumbnailTypeType,
     DocumentVersionStatusType,
     FolderContentTypeType,
+    LanguageCodeTypeType,
     LocaleTypeType,
+    OrderByFieldTypeType,
     OrderTypeType,
+    PrincipalRoleTypeType,
     PrincipalTypeType,
     ResourceCollectionTypeType,
     ResourceSortTypeType,
     ResourceStateTypeType,
     ResourceTypeType,
+    ResponseItemTypeType,
     RolePermissionTypeType,
     RoleTypeType,
+    SearchCollectionTypeType,
+    SearchQueryScopeTypeType,
+    SearchResourceTypeType,
+    SearchResourcesPaginatorName,
     ShareStatusTypeType,
+    SortOrderType,
     StorageTypeType,
     SubscriptionProtocolTypeType,
     SubscriptionTypeType,
     UserFilterTypeType,
     UserSortTypeType,
     UserStatusTypeType,
     UserTypeType,
@@ -348,156 +394,165 @@
 `types_aiobotocore_workdocs.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_workdocs.type_defs import (
     AbortDocumentVersionUploadRequestRequestTypeDef,
     ActivateUserRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     UserMetadataTypeDef,
     NotificationOptionsTypeDef,
     SharePrincipalTypeDef,
     ShareResultTypeDef,
     CreateCommentRequestRequestTypeDef,
     CreateCustomMetadataRequestRequestTypeDef,
     CreateFolderRequestRequestTypeDef,
     FolderMetadataTypeDef,
     CreateLabelsRequestRequestTypeDef,
     CreateNotificationSubscriptionRequestRequestTypeDef,
     SubscriptionTypeDef,
     StorageRuleTypeTypeDef,
+    DateRangeTypeTypeDef,
     DeactivateUserRequestRequestTypeDef,
     DeleteCommentRequestRequestTypeDef,
     DeleteCustomMetadataRequestRequestTypeDef,
     DeleteDocumentRequestRequestTypeDef,
     DeleteDocumentVersionRequestRequestTypeDef,
     DeleteFolderContentsRequestRequestTypeDef,
     DeleteFolderRequestRequestTypeDef,
     DeleteLabelsRequestRequestTypeDef,
     DeleteNotificationSubscriptionRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef,
     DescribeActivitiesRequestRequestTypeDef,
+    DescribeCommentsRequestDescribeCommentsPaginateTypeDef,
     DescribeCommentsRequestRequestTypeDef,
+    DescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef,
     DescribeDocumentVersionsRequestRequestTypeDef,
     DocumentVersionMetadataTypeDef,
+    DescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef,
     DescribeFolderContentsRequestRequestTypeDef,
+    DescribeGroupsRequestDescribeGroupsPaginateTypeDef,
     DescribeGroupsRequestRequestTypeDef,
     GroupMetadataTypeDef,
+    DescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef,
     DescribeNotificationSubscriptionsRequestRequestTypeDef,
+    DescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef,
     DescribeResourcePermissionsRequestRequestTypeDef,
+    DescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef,
     DescribeRootFoldersRequestRequestTypeDef,
+    DescribeUsersRequestDescribeUsersPaginateTypeDef,
     DescribeUsersRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
+    LongRangeTypeTypeDef,
+    SearchPrincipalTypeTypeDef,
     GetCurrentUserRequestRequestTypeDef,
     GetDocumentPathRequestRequestTypeDef,
     GetDocumentRequestRequestTypeDef,
     GetDocumentVersionRequestRequestTypeDef,
     GetFolderPathRequestRequestTypeDef,
     GetFolderRequestRequestTypeDef,
     GetResourcesRequestRequestTypeDef,
     InitiateDocumentVersionUploadRequestRequestTypeDef,
     UploadMetadataTypeDef,
+    PaginatorConfigTypeDef,
     PermissionInfoTypeDef,
     RemoveAllResourcePermissionsRequestRequestTypeDef,
     RemoveResourcePermissionRequestRequestTypeDef,
     ResourcePathComponentTypeDef,
+    ResponseMetadataTypeDef,
     RestoreDocumentVersionsRequestRequestTypeDef,
+    SearchSortResultTypeDef,
     UpdateDocumentRequestRequestTypeDef,
     UpdateDocumentVersionRequestRequestTypeDef,
     UpdateFolderRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
     ResourceMetadataTypeDef,
     AddResourcePermissionsRequestRequestTypeDef,
     AddResourcePermissionsResponseTypeDef,
     CreateFolderResponseTypeDef,
     DescribeRootFoldersResponseTypeDef,
     GetFolderResponseTypeDef,
     CreateNotificationSubscriptionResponseTypeDef,
     DescribeNotificationSubscriptionsResponseTypeDef,
     CreateUserRequestRequestTypeDef,
     UpdateUserRequestRequestTypeDef,
     UserStorageMetadataTypeDef,
-    DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef,
-    DescribeCommentsRequestDescribeCommentsPaginateTypeDef,
-    DescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef,
-    DescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef,
-    DescribeGroupsRequestDescribeGroupsPaginateTypeDef,
-    DescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef,
-    DescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef,
-    DescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef,
-    DescribeUsersRequestDescribeUsersPaginateTypeDef,
     DescribeDocumentVersionsResponseTypeDef,
     DocumentMetadataTypeDef,
     GetDocumentVersionResponseTypeDef,
     DescribeGroupsResponseTypeDef,
     ParticipantsTypeDef,
+    FiltersTypeDef,
     PrincipalTypeDef,
     ResourcePathTypeDef,
     UserTypeDef,
     DescribeFolderContentsResponseTypeDef,
     GetDocumentResponseTypeDef,
     GetResourcesResponseTypeDef,
     InitiateDocumentVersionUploadResponseTypeDef,
+    SearchResourcesRequestRequestTypeDef,
+    SearchResourcesRequestSearchResourcesPaginateTypeDef,
     DescribeResourcePermissionsResponseTypeDef,
     GetDocumentPathResponseTypeDef,
     GetFolderPathResponseTypeDef,
     ActivateUserResponseTypeDef,
     CommentMetadataTypeDef,
     CommentTypeDef,
     CreateUserResponseTypeDef,
     DescribeUsersResponseTypeDef,
     GetCurrentUserResponseTypeDef,
     UpdateUserResponseTypeDef,
     ActivityTypeDef,
+    ResponseItemTypeDef,
     CreateCommentResponseTypeDef,
     DescribeCommentsResponseTypeDef,
     DescribeActivitiesResponseTypeDef,
+    SearchResourcesResponseTypeDef,
 )
 
 
 def get_structure() -> AbortDocumentVersionUploadRequestRequestTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/setup.py` & `types-aiobotocore-workdocs-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-workdocs.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-workdocs",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_workdocs"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.WorkDocs 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.WorkDocs 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/"
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

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/__init__.py` & `types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/__init__.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -12,14 +12,15 @@
         DescribeDocumentVersionsPaginator,
         DescribeFolderContentsPaginator,
         DescribeGroupsPaginator,
         DescribeNotificationSubscriptionsPaginator,
         DescribeResourcePermissionsPaginator,
         DescribeRootFoldersPaginator,
         DescribeUsersPaginator,
+        SearchResourcesPaginator,
         WorkDocsClient,
     )
 
     session = get_session()
     async with session.create_client("workdocs") as client:
         client: WorkDocsClient
         ...
@@ -30,38 +31,40 @@
     describe_document_versions_paginator: DescribeDocumentVersionsPaginator = client.get_paginator("describe_document_versions")
     describe_folder_contents_paginator: DescribeFolderContentsPaginator = client.get_paginator("describe_folder_contents")
     describe_groups_paginator: DescribeGroupsPaginator = client.get_paginator("describe_groups")
     describe_notification_subscriptions_paginator: DescribeNotificationSubscriptionsPaginator = client.get_paginator("describe_notification_subscriptions")
     describe_resource_permissions_paginator: DescribeResourcePermissionsPaginator = client.get_paginator("describe_resource_permissions")
     describe_root_folders_paginator: DescribeRootFoldersPaginator = client.get_paginator("describe_root_folders")
     describe_users_paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
+    search_resources_paginator: SearchResourcesPaginator = client.get_paginator("search_resources")
     ```
 """
 from .client import WorkDocsClient
 from .paginator import (
     DescribeActivitiesPaginator,
     DescribeCommentsPaginator,
     DescribeDocumentVersionsPaginator,
     DescribeFolderContentsPaginator,
     DescribeGroupsPaginator,
     DescribeNotificationSubscriptionsPaginator,
     DescribeResourcePermissionsPaginator,
     DescribeRootFoldersPaginator,
     DescribeUsersPaginator,
+    SearchResourcesPaginator,
 )
 
 Client = WorkDocsClient
 
-
 __all__ = (
     "Client",
     "DescribeActivitiesPaginator",
     "DescribeCommentsPaginator",
     "DescribeDocumentVersionsPaginator",
     "DescribeFolderContentsPaginator",
     "DescribeGroupsPaginator",
     "DescribeNotificationSubscriptionsPaginator",
     "DescribeResourcePermissionsPaginator",
     "DescribeRootFoldersPaginator",
     "DescribeUsersPaginator",
+    "SearchResourcesPaginator",
     "WorkDocsClient",
 )
```

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/__init__.pyi` & `types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/__init__.py`

 * *Files 10% similar despite different names*

```diff
@@ -12,14 +12,15 @@
         DescribeDocumentVersionsPaginator,
         DescribeFolderContentsPaginator,
         DescribeGroupsPaginator,
         DescribeNotificationSubscriptionsPaginator,
         DescribeResourcePermissionsPaginator,
         DescribeRootFoldersPaginator,
         DescribeUsersPaginator,
+        SearchResourcesPaginator,
         WorkDocsClient,
     )
 
     session = get_session()
     async with session.create_client("workdocs") as client:
         client: WorkDocsClient
         ...
@@ -30,37 +31,41 @@
     describe_document_versions_paginator: DescribeDocumentVersionsPaginator = client.get_paginator("describe_document_versions")
     describe_folder_contents_paginator: DescribeFolderContentsPaginator = client.get_paginator("describe_folder_contents")
     describe_groups_paginator: DescribeGroupsPaginator = client.get_paginator("describe_groups")
     describe_notification_subscriptions_paginator: DescribeNotificationSubscriptionsPaginator = client.get_paginator("describe_notification_subscriptions")
     describe_resource_permissions_paginator: DescribeResourcePermissionsPaginator = client.get_paginator("describe_resource_permissions")
     describe_root_folders_paginator: DescribeRootFoldersPaginator = client.get_paginator("describe_root_folders")
     describe_users_paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
+    search_resources_paginator: SearchResourcesPaginator = client.get_paginator("search_resources")
     ```
 """
 from .client import WorkDocsClient
 from .paginator import (
     DescribeActivitiesPaginator,
     DescribeCommentsPaginator,
     DescribeDocumentVersionsPaginator,
     DescribeFolderContentsPaginator,
     DescribeGroupsPaginator,
     DescribeNotificationSubscriptionsPaginator,
     DescribeResourcePermissionsPaginator,
     DescribeRootFoldersPaginator,
     DescribeUsersPaginator,
+    SearchResourcesPaginator,
 )
 
 Client = WorkDocsClient
 
+
 __all__ = (
     "Client",
     "DescribeActivitiesPaginator",
     "DescribeCommentsPaginator",
     "DescribeDocumentVersionsPaginator",
     "DescribeFolderContentsPaginator",
     "DescribeGroupsPaginator",
     "DescribeNotificationSubscriptionsPaginator",
     "DescribeResourcePermissionsPaginator",
     "DescribeRootFoldersPaginator",
     "DescribeUsersPaginator",
+    "SearchResourcesPaginator",
     "WorkDocsClient",
 )
```

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/__main__.py` & `types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.WorkDocs 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.WorkDocs 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs\nOther"
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

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/client.py` & `types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -26,14 +26,15 @@
     CommentVisibilityTypeType,
     FolderContentTypeType,
     LocaleTypeType,
     OrderTypeType,
     PrincipalTypeType,
     ResourceSortTypeType,
     ResourceStateTypeType,
+    SearchQueryScopeTypeType,
     SubscriptionProtocolTypeType,
     UserFilterTypeType,
     UserSortTypeType,
     UserTypeType,
 )
 from .paginator import (
     DescribeActivitiesPaginator,
@@ -41,14 +42,15 @@
     DescribeDocumentVersionsPaginator,
     DescribeFolderContentsPaginator,
     DescribeGroupsPaginator,
     DescribeNotificationSubscriptionsPaginator,
     DescribeResourcePermissionsPaginator,
     DescribeRootFoldersPaginator,
     DescribeUsersPaginator,
+    SearchResourcesPaginator,
 )
 from .type_defs import (
     ActivateUserResponseTypeDef,
     AddResourcePermissionsResponseTypeDef,
     CreateCommentResponseTypeDef,
     CreateFolderResponseTypeDef,
     CreateNotificationSubscriptionResponseTypeDef,
@@ -59,23 +61,26 @@
     DescribeFolderContentsResponseTypeDef,
     DescribeGroupsResponseTypeDef,
     DescribeNotificationSubscriptionsResponseTypeDef,
     DescribeResourcePermissionsResponseTypeDef,
     DescribeRootFoldersResponseTypeDef,
     DescribeUsersResponseTypeDef,
     EmptyResponseMetadataTypeDef,
+    FiltersTypeDef,
     GetCurrentUserResponseTypeDef,
     GetDocumentPathResponseTypeDef,
     GetDocumentResponseTypeDef,
     GetDocumentVersionResponseTypeDef,
     GetFolderPathResponseTypeDef,
     GetFolderResponseTypeDef,
     GetResourcesResponseTypeDef,
     InitiateDocumentVersionUploadResponseTypeDef,
     NotificationOptionsTypeDef,
+    SearchResourcesResponseTypeDef,
+    SearchSortResultTypeDef,
     SharePrincipalTypeDef,
     StorageRuleTypeTypeDef,
     UpdateUserResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
@@ -708,14 +713,35 @@
         """
         Recovers a deleted version of an Amazon WorkDocs document.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Client.restore_document_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/client/#restore_document_versions)
         """
 
+    async def search_resources(
+        self,
+        *,
+        AuthenticationToken: str = ...,
+        QueryText: str = ...,
+        QueryScopes: Sequence[SearchQueryScopeTypeType] = ...,
+        OrganizationId: str = ...,
+        AdditionalResponseFields: Sequence[Literal["WEBURL"]] = ...,
+        Filters: FiltersTypeDef = ...,
+        OrderBy: Sequence[SearchSortResultTypeDef] = ...,
+        Limit: int = ...,
+        Marker: str = ...
+    ) -> SearchResourcesResponseTypeDef:
+        """
+        Searches metadata and the content of folders, documents, document versions, and
+        comments.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Client.search_resources)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/client/#search_resources)
+        """
+
     async def update_document(
         self,
         *,
         DocumentId: str,
         AuthenticationToken: str = ...,
         Name: str = ...,
         ParentFolderId: str = ...,
@@ -853,14 +879,23 @@
     @overload
     def get_paginator(self, operation_name: Literal["describe_users"]) -> DescribeUsersPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/client/#get_paginator)
         """
 
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["search_resources"]
+    ) -> SearchResourcesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/client/#get_paginator)
+        """
+
     async def __aenter__(self) -> "WorkDocsClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/client/)
         """
 
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
```

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/client.pyi` & `types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -26,14 +26,15 @@
     CommentVisibilityTypeType,
     FolderContentTypeType,
     LocaleTypeType,
     OrderTypeType,
     PrincipalTypeType,
     ResourceSortTypeType,
     ResourceStateTypeType,
+    SearchQueryScopeTypeType,
     SubscriptionProtocolTypeType,
     UserFilterTypeType,
     UserSortTypeType,
     UserTypeType,
 )
 from .paginator import (
     DescribeActivitiesPaginator,
@@ -41,14 +42,15 @@
     DescribeDocumentVersionsPaginator,
     DescribeFolderContentsPaginator,
     DescribeGroupsPaginator,
     DescribeNotificationSubscriptionsPaginator,
     DescribeResourcePermissionsPaginator,
     DescribeRootFoldersPaginator,
     DescribeUsersPaginator,
+    SearchResourcesPaginator,
 )
 from .type_defs import (
     ActivateUserResponseTypeDef,
     AddResourcePermissionsResponseTypeDef,
     CreateCommentResponseTypeDef,
     CreateFolderResponseTypeDef,
     CreateNotificationSubscriptionResponseTypeDef,
@@ -59,23 +61,26 @@
     DescribeFolderContentsResponseTypeDef,
     DescribeGroupsResponseTypeDef,
     DescribeNotificationSubscriptionsResponseTypeDef,
     DescribeResourcePermissionsResponseTypeDef,
     DescribeRootFoldersResponseTypeDef,
     DescribeUsersResponseTypeDef,
     EmptyResponseMetadataTypeDef,
+    FiltersTypeDef,
     GetCurrentUserResponseTypeDef,
     GetDocumentPathResponseTypeDef,
     GetDocumentResponseTypeDef,
     GetDocumentVersionResponseTypeDef,
     GetFolderPathResponseTypeDef,
     GetFolderResponseTypeDef,
     GetResourcesResponseTypeDef,
     InitiateDocumentVersionUploadResponseTypeDef,
     NotificationOptionsTypeDef,
+    SearchResourcesResponseTypeDef,
+    SearchSortResultTypeDef,
     SharePrincipalTypeDef,
     StorageRuleTypeTypeDef,
     UpdateUserResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
@@ -661,14 +666,34 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Recovers a deleted version of an Amazon WorkDocs document.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Client.restore_document_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/client/#restore_document_versions)
         """
+    async def search_resources(
+        self,
+        *,
+        AuthenticationToken: str = ...,
+        QueryText: str = ...,
+        QueryScopes: Sequence[SearchQueryScopeTypeType] = ...,
+        OrganizationId: str = ...,
+        AdditionalResponseFields: Sequence[Literal["WEBURL"]] = ...,
+        Filters: FiltersTypeDef = ...,
+        OrderBy: Sequence[SearchSortResultTypeDef] = ...,
+        Limit: int = ...,
+        Marker: str = ...
+    ) -> SearchResourcesResponseTypeDef:
+        """
+        Searches metadata and the content of folders, documents, document versions, and
+        comments.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Client.search_resources)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/client/#search_resources)
+        """
     async def update_document(
         self,
         *,
         DocumentId: str,
         AuthenticationToken: str = ...,
         Name: str = ...,
         ParentFolderId: str = ...,
@@ -793,14 +818,22 @@
         """
     @overload
     def get_paginator(self, operation_name: Literal["describe_users"]) -> DescribeUsersPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/client/#get_paginator)
         """
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["search_resources"]
+    ) -> SearchResourcesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/client/#get_paginator)
+        """
     async def __aenter__(self) -> "WorkDocsClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/client/)
         """
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
```

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/literals.py` & `types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/literals.py`

 * *Files 8% similar despite different names*

```diff
@@ -17,41 +17,52 @@
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
     "ActivityTypeType",
+    "AdditionalResponseFieldTypeType",
     "BooleanEnumTypeType",
     "CommentStatusTypeType",
     "CommentVisibilityTypeType",
+    "ContentCategoryTypeType",
     "DescribeActivitiesPaginatorName",
     "DescribeCommentsPaginatorName",
     "DescribeDocumentVersionsPaginatorName",
     "DescribeFolderContentsPaginatorName",
     "DescribeGroupsPaginatorName",
     "DescribeNotificationSubscriptionsPaginatorName",
     "DescribeResourcePermissionsPaginatorName",
     "DescribeRootFoldersPaginatorName",
     "DescribeUsersPaginatorName",
     "DocumentSourceTypeType",
     "DocumentStatusTypeType",
     "DocumentThumbnailTypeType",
     "DocumentVersionStatusType",
     "FolderContentTypeType",
+    "LanguageCodeTypeType",
     "LocaleTypeType",
+    "OrderByFieldTypeType",
     "OrderTypeType",
+    "PrincipalRoleTypeType",
     "PrincipalTypeType",
     "ResourceCollectionTypeType",
     "ResourceSortTypeType",
     "ResourceStateTypeType",
     "ResourceTypeType",
+    "ResponseItemTypeType",
     "RolePermissionTypeType",
     "RoleTypeType",
+    "SearchCollectionTypeType",
+    "SearchQueryScopeTypeType",
+    "SearchResourceTypeType",
+    "SearchResourcesPaginatorName",
     "ShareStatusTypeType",
+    "SortOrderType",
     "StorageTypeType",
     "SubscriptionProtocolTypeType",
     "SubscriptionTypeType",
     "UserFilterTypeType",
     "UserSortTypeType",
     "UserStatusTypeType",
     "UserTypeType",
@@ -94,43 +105,98 @@
     "FOLDER_SHAREABLE_LINK_CREATED",
     "FOLDER_SHAREABLE_LINK_PERMISSION_CHANGED",
     "FOLDER_SHAREABLE_LINK_REMOVED",
     "FOLDER_SHARED",
     "FOLDER_SHARE_PERMISSION_CHANGED",
     "FOLDER_UNSHARED",
 ]
+AdditionalResponseFieldTypeType = Literal["WEBURL"]
 BooleanEnumTypeType = Literal["FALSE", "TRUE"]
 CommentStatusTypeType = Literal["DELETED", "DRAFT", "PUBLISHED"]
 CommentVisibilityTypeType = Literal["PRIVATE", "PUBLIC"]
+ContentCategoryTypeType = Literal[
+    "AUDIO",
+    "DOCUMENT",
+    "IMAGE",
+    "OTHER",
+    "PDF",
+    "PRESENTATION",
+    "SOURCE_CODE",
+    "SPREADSHEET",
+    "VIDEO",
+]
 DescribeActivitiesPaginatorName = Literal["describe_activities"]
 DescribeCommentsPaginatorName = Literal["describe_comments"]
 DescribeDocumentVersionsPaginatorName = Literal["describe_document_versions"]
 DescribeFolderContentsPaginatorName = Literal["describe_folder_contents"]
 DescribeGroupsPaginatorName = Literal["describe_groups"]
 DescribeNotificationSubscriptionsPaginatorName = Literal["describe_notification_subscriptions"]
 DescribeResourcePermissionsPaginatorName = Literal["describe_resource_permissions"]
 DescribeRootFoldersPaginatorName = Literal["describe_root_folders"]
 DescribeUsersPaginatorName = Literal["describe_users"]
 DocumentSourceTypeType = Literal["ORIGINAL", "WITH_COMMENTS"]
 DocumentStatusTypeType = Literal["ACTIVE", "INITIALIZED"]
 DocumentThumbnailTypeType = Literal["LARGE", "SMALL", "SMALL_HQ"]
 DocumentVersionStatusType = Literal["ACTIVE"]
 FolderContentTypeType = Literal["ALL", "DOCUMENT", "FOLDER"]
+LanguageCodeTypeType = Literal[
+    "AR",
+    "BG",
+    "BN",
+    "CS",
+    "DA",
+    "DE",
+    "DEFAULT",
+    "EL",
+    "EN",
+    "ES",
+    "FA",
+    "FI",
+    "FR",
+    "HI",
+    "HU",
+    "ID",
+    "IT",
+    "JA",
+    "KO",
+    "LT",
+    "LV",
+    "NL",
+    "NO",
+    "PT",
+    "RO",
+    "RU",
+    "SV",
+    "SW",
+    "TH",
+    "TR",
+    "ZH",
+]
 LocaleTypeType = Literal[
     "de", "default", "en", "es", "fr", "ja", "ko", "pt_BR", "ru", "zh_CN", "zh_TW"
 ]
+OrderByFieldTypeType = Literal[
+    "CREATED_TIMESTAMP", "MODIFIED_TIMESTAMP", "NAME", "RELEVANCE", "SIZE"
+]
 OrderTypeType = Literal["ASCENDING", "DESCENDING"]
+PrincipalRoleTypeType = Literal["CONTRIBUTOR", "COOWNER", "OWNER", "VIEWER"]
 PrincipalTypeType = Literal["ANONYMOUS", "GROUP", "INVITE", "ORGANIZATION", "USER"]
 ResourceCollectionTypeType = Literal["SHARED_WITH_ME"]
 ResourceSortTypeType = Literal["DATE", "NAME"]
 ResourceStateTypeType = Literal["ACTIVE", "RECYCLED", "RECYCLING", "RESTORING"]
 ResourceTypeType = Literal["DOCUMENT", "FOLDER"]
+ResponseItemTypeType = Literal["COMMENT", "DOCUMENT", "DOCUMENT_VERSION", "FOLDER"]
 RolePermissionTypeType = Literal["DIRECT", "INHERITED"]
 RoleTypeType = Literal["CONTRIBUTOR", "COOWNER", "OWNER", "VIEWER"]
+SearchCollectionTypeType = Literal["OWNED", "SHARED_WITH_ME"]
+SearchQueryScopeTypeType = Literal["CONTENT", "NAME"]
+SearchResourceTypeType = Literal["COMMENT", "DOCUMENT", "DOCUMENT_VERSION", "FOLDER"]
+SearchResourcesPaginatorName = Literal["search_resources"]
 ShareStatusTypeType = Literal["FAILURE", "SUCCESS"]
+SortOrderType = Literal["ASC", "DESC"]
 StorageTypeType = Literal["QUOTA", "UNLIMITED"]
 SubscriptionProtocolTypeType = Literal["HTTPS", "SQS"]
 SubscriptionTypeType = Literal["ALL"]
 UserFilterTypeType = Literal["ACTIVE_PENDING", "ALL"]
 UserSortTypeType = Literal["FULL_NAME", "STORAGE_LIMIT", "STORAGE_USED", "USER_NAME", "USER_STATUS"]
 UserStatusTypeType = Literal["ACTIVE", "INACTIVE", "PENDING"]
 UserTypeType = Literal["ADMIN", "MINIMALUSER", "POWERUSER", "USER", "WORKSPACESUSER"]
@@ -193,14 +259,15 @@
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
@@ -279,14 +346,15 @@
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
@@ -297,14 +365,15 @@
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
@@ -340,14 +409,15 @@
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
@@ -366,16 +436,19 @@
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
@@ -459,15 +532,17 @@
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
@@ -495,11 +570,12 @@
     "describe_document_versions",
     "describe_folder_contents",
     "describe_groups",
     "describe_notification_subscriptions",
     "describe_resource_permissions",
     "describe_root_folders",
     "describe_users",
+    "search_resources",
 ]
 RegionName = Literal[
     "ap-northeast-1", "ap-southeast-1", "ap-southeast-2", "eu-west-1", "us-east-1", "us-west-2"
 ]
```

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/literals.pyi` & `types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -16,41 +16,52 @@
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "ActivityTypeType",
+    "AdditionalResponseFieldTypeType",
     "BooleanEnumTypeType",
     "CommentStatusTypeType",
     "CommentVisibilityTypeType",
+    "ContentCategoryTypeType",
     "DescribeActivitiesPaginatorName",
     "DescribeCommentsPaginatorName",
     "DescribeDocumentVersionsPaginatorName",
     "DescribeFolderContentsPaginatorName",
     "DescribeGroupsPaginatorName",
     "DescribeNotificationSubscriptionsPaginatorName",
     "DescribeResourcePermissionsPaginatorName",
     "DescribeRootFoldersPaginatorName",
     "DescribeUsersPaginatorName",
     "DocumentSourceTypeType",
     "DocumentStatusTypeType",
     "DocumentThumbnailTypeType",
     "DocumentVersionStatusType",
     "FolderContentTypeType",
+    "LanguageCodeTypeType",
     "LocaleTypeType",
+    "OrderByFieldTypeType",
     "OrderTypeType",
+    "PrincipalRoleTypeType",
     "PrincipalTypeType",
     "ResourceCollectionTypeType",
     "ResourceSortTypeType",
     "ResourceStateTypeType",
     "ResourceTypeType",
+    "ResponseItemTypeType",
     "RolePermissionTypeType",
     "RoleTypeType",
+    "SearchCollectionTypeType",
+    "SearchQueryScopeTypeType",
+    "SearchResourceTypeType",
+    "SearchResourcesPaginatorName",
     "ShareStatusTypeType",
+    "SortOrderType",
     "StorageTypeType",
     "SubscriptionProtocolTypeType",
     "SubscriptionTypeType",
     "UserFilterTypeType",
     "UserSortTypeType",
     "UserStatusTypeType",
     "UserTypeType",
@@ -92,43 +103,98 @@
     "FOLDER_SHAREABLE_LINK_CREATED",
     "FOLDER_SHAREABLE_LINK_PERMISSION_CHANGED",
     "FOLDER_SHAREABLE_LINK_REMOVED",
     "FOLDER_SHARED",
     "FOLDER_SHARE_PERMISSION_CHANGED",
     "FOLDER_UNSHARED",
 ]
+AdditionalResponseFieldTypeType = Literal["WEBURL"]
 BooleanEnumTypeType = Literal["FALSE", "TRUE"]
 CommentStatusTypeType = Literal["DELETED", "DRAFT", "PUBLISHED"]
 CommentVisibilityTypeType = Literal["PRIVATE", "PUBLIC"]
+ContentCategoryTypeType = Literal[
+    "AUDIO",
+    "DOCUMENT",
+    "IMAGE",
+    "OTHER",
+    "PDF",
+    "PRESENTATION",
+    "SOURCE_CODE",
+    "SPREADSHEET",
+    "VIDEO",
+]
 DescribeActivitiesPaginatorName = Literal["describe_activities"]
 DescribeCommentsPaginatorName = Literal["describe_comments"]
 DescribeDocumentVersionsPaginatorName = Literal["describe_document_versions"]
 DescribeFolderContentsPaginatorName = Literal["describe_folder_contents"]
 DescribeGroupsPaginatorName = Literal["describe_groups"]
 DescribeNotificationSubscriptionsPaginatorName = Literal["describe_notification_subscriptions"]
 DescribeResourcePermissionsPaginatorName = Literal["describe_resource_permissions"]
 DescribeRootFoldersPaginatorName = Literal["describe_root_folders"]
 DescribeUsersPaginatorName = Literal["describe_users"]
 DocumentSourceTypeType = Literal["ORIGINAL", "WITH_COMMENTS"]
 DocumentStatusTypeType = Literal["ACTIVE", "INITIALIZED"]
 DocumentThumbnailTypeType = Literal["LARGE", "SMALL", "SMALL_HQ"]
 DocumentVersionStatusType = Literal["ACTIVE"]
 FolderContentTypeType = Literal["ALL", "DOCUMENT", "FOLDER"]
+LanguageCodeTypeType = Literal[
+    "AR",
+    "BG",
+    "BN",
+    "CS",
+    "DA",
+    "DE",
+    "DEFAULT",
+    "EL",
+    "EN",
+    "ES",
+    "FA",
+    "FI",
+    "FR",
+    "HI",
+    "HU",
+    "ID",
+    "IT",
+    "JA",
+    "KO",
+    "LT",
+    "LV",
+    "NL",
+    "NO",
+    "PT",
+    "RO",
+    "RU",
+    "SV",
+    "SW",
+    "TH",
+    "TR",
+    "ZH",
+]
 LocaleTypeType = Literal[
     "de", "default", "en", "es", "fr", "ja", "ko", "pt_BR", "ru", "zh_CN", "zh_TW"
 ]
+OrderByFieldTypeType = Literal[
+    "CREATED_TIMESTAMP", "MODIFIED_TIMESTAMP", "NAME", "RELEVANCE", "SIZE"
+]
 OrderTypeType = Literal["ASCENDING", "DESCENDING"]
+PrincipalRoleTypeType = Literal["CONTRIBUTOR", "COOWNER", "OWNER", "VIEWER"]
 PrincipalTypeType = Literal["ANONYMOUS", "GROUP", "INVITE", "ORGANIZATION", "USER"]
 ResourceCollectionTypeType = Literal["SHARED_WITH_ME"]
 ResourceSortTypeType = Literal["DATE", "NAME"]
 ResourceStateTypeType = Literal["ACTIVE", "RECYCLED", "RECYCLING", "RESTORING"]
 ResourceTypeType = Literal["DOCUMENT", "FOLDER"]
+ResponseItemTypeType = Literal["COMMENT", "DOCUMENT", "DOCUMENT_VERSION", "FOLDER"]
 RolePermissionTypeType = Literal["DIRECT", "INHERITED"]
 RoleTypeType = Literal["CONTRIBUTOR", "COOWNER", "OWNER", "VIEWER"]
+SearchCollectionTypeType = Literal["OWNED", "SHARED_WITH_ME"]
+SearchQueryScopeTypeType = Literal["CONTENT", "NAME"]
+SearchResourceTypeType = Literal["COMMENT", "DOCUMENT", "DOCUMENT_VERSION", "FOLDER"]
+SearchResourcesPaginatorName = Literal["search_resources"]
 ShareStatusTypeType = Literal["FAILURE", "SUCCESS"]
+SortOrderType = Literal["ASC", "DESC"]
 StorageTypeType = Literal["QUOTA", "UNLIMITED"]
 SubscriptionProtocolTypeType = Literal["HTTPS", "SQS"]
 SubscriptionTypeType = Literal["ALL"]
 UserFilterTypeType = Literal["ACTIVE_PENDING", "ALL"]
 UserSortTypeType = Literal["FULL_NAME", "STORAGE_LIMIT", "STORAGE_USED", "USER_NAME", "USER_STATUS"]
 UserStatusTypeType = Literal["ACTIVE", "INACTIVE", "PENDING"]
 UserTypeType = Literal["ADMIN", "MINIMALUSER", "POWERUSER", "USER", "WORKSPACESUSER"]
@@ -191,14 +257,15 @@
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
@@ -277,14 +344,15 @@
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
@@ -295,14 +363,15 @@
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
@@ -338,14 +407,15 @@
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
@@ -364,16 +434,19 @@
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
@@ -457,15 +530,17 @@
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
@@ -493,11 +568,12 @@
     "describe_document_versions",
     "describe_folder_contents",
     "describe_groups",
     "describe_notification_subscriptions",
     "describe_resource_permissions",
     "describe_root_folders",
     "describe_users",
+    "search_resources",
 ]
 RegionName = Literal[
     "ap-northeast-1", "ap-southeast-1", "ap-southeast-2", "eu-west-1", "us-east-1", "us-west-2"
 ]
```

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/paginator.py` & `types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/paginator.py`

 * *Files 9% similar despite different names*

```diff
@@ -15,14 +15,15 @@
         DescribeDocumentVersionsPaginator,
         DescribeFolderContentsPaginator,
         DescribeGroupsPaginator,
         DescribeNotificationSubscriptionsPaginator,
         DescribeResourcePermissionsPaginator,
         DescribeRootFoldersPaginator,
         DescribeUsersPaginator,
+        SearchResourcesPaginator,
     )
 
     session = get_session()
     with session.create_client("workdocs") as client:
         client: WorkDocsClient
 
         describe_activities_paginator: DescribeActivitiesPaginator = client.get_paginator("describe_activities")
@@ -30,59 +31,65 @@
         describe_document_versions_paginator: DescribeDocumentVersionsPaginator = client.get_paginator("describe_document_versions")
         describe_folder_contents_paginator: DescribeFolderContentsPaginator = client.get_paginator("describe_folder_contents")
         describe_groups_paginator: DescribeGroupsPaginator = client.get_paginator("describe_groups")
         describe_notification_subscriptions_paginator: DescribeNotificationSubscriptionsPaginator = client.get_paginator("describe_notification_subscriptions")
         describe_resource_permissions_paginator: DescribeResourcePermissionsPaginator = client.get_paginator("describe_resource_permissions")
         describe_root_folders_paginator: DescribeRootFoldersPaginator = client.get_paginator("describe_root_folders")
         describe_users_paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
+        search_resources_paginator: SearchResourcesPaginator = client.get_paginator("search_resources")
     ```
 """
 import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     FolderContentTypeType,
     OrderTypeType,
     ResourceSortTypeType,
+    SearchQueryScopeTypeType,
     UserFilterTypeType,
     UserSortTypeType,
 )
 from .type_defs import (
     DescribeActivitiesResponseTypeDef,
     DescribeCommentsResponseTypeDef,
     DescribeDocumentVersionsResponseTypeDef,
     DescribeFolderContentsResponseTypeDef,
     DescribeGroupsResponseTypeDef,
     DescribeNotificationSubscriptionsResponseTypeDef,
     DescribeResourcePermissionsResponseTypeDef,
     DescribeRootFoldersResponseTypeDef,
     DescribeUsersResponseTypeDef,
+    FiltersTypeDef,
     PaginatorConfigTypeDef,
+    SearchResourcesResponseTypeDef,
+    SearchSortResultTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
+if sys.version_info >= (3, 9):
+    from typing import Literal
 else:
-    from typing_extensions import AsyncIterator
+    from typing_extensions import Literal
 
 
 __all__ = (
     "DescribeActivitiesPaginator",
     "DescribeCommentsPaginator",
     "DescribeDocumentVersionsPaginator",
     "DescribeFolderContentsPaginator",
     "DescribeGroupsPaginator",
     "DescribeNotificationSubscriptionsPaginator",
     "DescribeResourcePermissionsPaginator",
     "DescribeRootFoldersPaginator",
     "DescribeUsersPaginator",
+    "SearchResourcesPaginator",
 )
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -105,15 +112,15 @@
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
         OrganizationId: str = ...,
         ActivityTypes: str = ...,
         ResourceId: str = ...,
         UserId: str = ...,
         IncludeIndirectActivities: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeActivitiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeActivities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describeactivitiespaginator)
         """
 
 
@@ -125,15 +132,15 @@
 
     def paginate(
         self,
         *,
         DocumentId: str,
         VersionId: str,
         AuthenticationToken: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeCommentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeComments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describecommentspaginator)
         """
 
 
@@ -146,15 +153,15 @@
     def paginate(
         self,
         *,
         DocumentId: str,
         AuthenticationToken: str = ...,
         Include: str = ...,
         Fields: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDocumentVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeDocumentVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describedocumentversionspaginator)
         """
 
 
@@ -169,15 +176,15 @@
         *,
         FolderId: str,
         AuthenticationToken: str = ...,
         Sort: ResourceSortTypeType = ...,
         Order: OrderTypeType = ...,
         Type: FolderContentTypeType = ...,
         Include: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFolderContentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeFolderContents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describefoldercontentspaginator)
         """
 
 
@@ -189,30 +196,30 @@
 
     def paginate(
         self,
         *,
         SearchQuery: str,
         AuthenticationToken: str = ...,
         OrganizationId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describegroupspaginator)
         """
 
 
 class DescribeNotificationSubscriptionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeNotificationSubscriptions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describenotificationsubscriptionspaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OrganizationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeNotificationSubscriptionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeNotificationSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describenotificationsubscriptionspaginator)
         """
 
 
@@ -224,30 +231,30 @@
 
     def paginate(
         self,
         *,
         ResourceId: str,
         AuthenticationToken: str = ...,
         PrincipalId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeResourcePermissionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeResourcePermissions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describeresourcepermissionspaginator)
         """
 
 
 class DescribeRootFoldersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeRootFolders)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describerootfolderspaginator)
     """
 
     def paginate(
-        self, *, AuthenticationToken: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AuthenticationToken: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRootFoldersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeRootFolders.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describerootfolderspaginator)
         """
 
 
@@ -264,13 +271,37 @@
         OrganizationId: str = ...,
         UserIds: str = ...,
         Query: str = ...,
         Include: UserFilterTypeType = ...,
         Order: OrderTypeType = ...,
         Sort: UserSortTypeType = ...,
         Fields: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describeuserspaginator)
         """
+
+
+class SearchResourcesPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.SearchResources)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#searchresourcespaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        AuthenticationToken: str = ...,
+        QueryText: str = ...,
+        QueryScopes: Sequence[SearchQueryScopeTypeType] = ...,
+        OrganizationId: str = ...,
+        AdditionalResponseFields: Sequence[Literal["WEBURL"]] = ...,
+        Filters: FiltersTypeDef = ...,
+        OrderBy: Sequence[SearchSortResultTypeDef] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[SearchResourcesResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.SearchResources.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#searchresourcespaginator)
+        """
```

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/paginator.pyi` & `types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/paginator.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -15,14 +15,15 @@
         DescribeDocumentVersionsPaginator,
         DescribeFolderContentsPaginator,
         DescribeGroupsPaginator,
         DescribeNotificationSubscriptionsPaginator,
         DescribeResourcePermissionsPaginator,
         DescribeRootFoldersPaginator,
         DescribeUsersPaginator,
+        SearchResourcesPaginator,
     )
 
     session = get_session()
     with session.create_client("workdocs") as client:
         client: WorkDocsClient
 
         describe_activities_paginator: DescribeActivitiesPaginator = client.get_paginator("describe_activities")
@@ -30,58 +31,64 @@
         describe_document_versions_paginator: DescribeDocumentVersionsPaginator = client.get_paginator("describe_document_versions")
         describe_folder_contents_paginator: DescribeFolderContentsPaginator = client.get_paginator("describe_folder_contents")
         describe_groups_paginator: DescribeGroupsPaginator = client.get_paginator("describe_groups")
         describe_notification_subscriptions_paginator: DescribeNotificationSubscriptionsPaginator = client.get_paginator("describe_notification_subscriptions")
         describe_resource_permissions_paginator: DescribeResourcePermissionsPaginator = client.get_paginator("describe_resource_permissions")
         describe_root_folders_paginator: DescribeRootFoldersPaginator = client.get_paginator("describe_root_folders")
         describe_users_paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
+        search_resources_paginator: SearchResourcesPaginator = client.get_paginator("search_resources")
     ```
 """
 import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     FolderContentTypeType,
     OrderTypeType,
     ResourceSortTypeType,
+    SearchQueryScopeTypeType,
     UserFilterTypeType,
     UserSortTypeType,
 )
 from .type_defs import (
     DescribeActivitiesResponseTypeDef,
     DescribeCommentsResponseTypeDef,
     DescribeDocumentVersionsResponseTypeDef,
     DescribeFolderContentsResponseTypeDef,
     DescribeGroupsResponseTypeDef,
     DescribeNotificationSubscriptionsResponseTypeDef,
     DescribeResourcePermissionsResponseTypeDef,
     DescribeRootFoldersResponseTypeDef,
     DescribeUsersResponseTypeDef,
+    FiltersTypeDef,
     PaginatorConfigTypeDef,
+    SearchResourcesResponseTypeDef,
+    SearchSortResultTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
+if sys.version_info >= (3, 9):
+    from typing import Literal
 else:
-    from typing_extensions import AsyncIterator
+    from typing_extensions import Literal
 
 __all__ = (
     "DescribeActivitiesPaginator",
     "DescribeCommentsPaginator",
     "DescribeDocumentVersionsPaginator",
     "DescribeFolderContentsPaginator",
     "DescribeGroupsPaginator",
     "DescribeNotificationSubscriptionsPaginator",
     "DescribeResourcePermissionsPaginator",
     "DescribeRootFoldersPaginator",
     "DescribeUsersPaginator",
+    "SearchResourcesPaginator",
 )
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -101,15 +108,15 @@
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
         OrganizationId: str = ...,
         ActivityTypes: str = ...,
         ResourceId: str = ...,
         UserId: str = ...,
         IncludeIndirectActivities: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeActivitiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeActivities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describeactivitiespaginator)
         """
 
 class DescribeCommentsPaginator(AioPaginator):
@@ -120,15 +127,15 @@
 
     def paginate(
         self,
         *,
         DocumentId: str,
         VersionId: str,
         AuthenticationToken: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeCommentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeComments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describecommentspaginator)
         """
 
 class DescribeDocumentVersionsPaginator(AioPaginator):
@@ -140,15 +147,15 @@
     def paginate(
         self,
         *,
         DocumentId: str,
         AuthenticationToken: str = ...,
         Include: str = ...,
         Fields: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeDocumentVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeDocumentVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describedocumentversionspaginator)
         """
 
 class DescribeFolderContentsPaginator(AioPaginator):
@@ -162,15 +169,15 @@
         *,
         FolderId: str,
         AuthenticationToken: str = ...,
         Sort: ResourceSortTypeType = ...,
         Order: OrderTypeType = ...,
         Type: FolderContentTypeType = ...,
         Include: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFolderContentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeFolderContents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describefoldercontentspaginator)
         """
 
 class DescribeGroupsPaginator(AioPaginator):
@@ -181,29 +188,29 @@
 
     def paginate(
         self,
         *,
         SearchQuery: str,
         AuthenticationToken: str = ...,
         OrganizationId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describegroupspaginator)
         """
 
 class DescribeNotificationSubscriptionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeNotificationSubscriptions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describenotificationsubscriptionspaginator)
     """
 
     def paginate(
-        self, *, OrganizationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OrganizationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeNotificationSubscriptionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeNotificationSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describenotificationsubscriptionspaginator)
         """
 
 class DescribeResourcePermissionsPaginator(AioPaginator):
@@ -214,29 +221,29 @@
 
     def paginate(
         self,
         *,
         ResourceId: str,
         AuthenticationToken: str = ...,
         PrincipalId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeResourcePermissionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeResourcePermissions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describeresourcepermissionspaginator)
         """
 
 class DescribeRootFoldersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeRootFolders)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describerootfolderspaginator)
     """
 
     def paginate(
-        self, *, AuthenticationToken: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AuthenticationToken: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRootFoldersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeRootFolders.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describerootfolderspaginator)
         """
 
 class DescribeUsersPaginator(AioPaginator):
@@ -252,13 +259,36 @@
         OrganizationId: str = ...,
         UserIds: str = ...,
         Query: str = ...,
         Include: UserFilterTypeType = ...,
         Order: OrderTypeType = ...,
         Sort: UserSortTypeType = ...,
         Fields: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.DescribeUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#describeuserspaginator)
         """
+
+class SearchResourcesPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.SearchResources)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#searchresourcespaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        AuthenticationToken: str = ...,
+        QueryText: str = ...,
+        QueryScopes: Sequence[SearchQueryScopeTypeType] = ...,
+        OrganizationId: str = ...,
+        AdditionalResponseFields: Sequence[Literal["WEBURL"]] = ...,
+        Filters: FiltersTypeDef = ...,
+        OrderBy: Sequence[SearchSortResultTypeDef] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[SearchResourcesResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs.Paginator.SearchResources.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/paginators/#searchresourcespaginator)
+        """
```

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/type_defs.py` & `types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -16,27 +16,36 @@
 from typing import Dict, List, Mapping, Sequence, Union
 
 from .literals import (
     ActivityTypeType,
     BooleanEnumTypeType,
     CommentStatusTypeType,
     CommentVisibilityTypeType,
+    ContentCategoryTypeType,
     DocumentSourceTypeType,
     DocumentStatusTypeType,
     DocumentThumbnailTypeType,
     FolderContentTypeType,
+    LanguageCodeTypeType,
     LocaleTypeType,
+    OrderByFieldTypeType,
     OrderTypeType,
+    PrincipalRoleTypeType,
     PrincipalTypeType,
     ResourceSortTypeType,
     ResourceStateTypeType,
     ResourceTypeType,
+    ResponseItemTypeType,
     RolePermissionTypeType,
     RoleTypeType,
+    SearchCollectionTypeType,
+    SearchQueryScopeTypeType,
+    SearchResourceTypeType,
     ShareStatusTypeType,
+    SortOrderType,
     StorageTypeType,
     SubscriptionProtocolTypeType,
     UserFilterTypeType,
     UserSortTypeType,
     UserStatusTypeType,
     UserTypeType,
 )
@@ -50,113 +59,122 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AbortDocumentVersionUploadRequestRequestTypeDef",
     "ActivateUserRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "UserMetadataTypeDef",
     "NotificationOptionsTypeDef",
     "SharePrincipalTypeDef",
     "ShareResultTypeDef",
     "CreateCommentRequestRequestTypeDef",
     "CreateCustomMetadataRequestRequestTypeDef",
     "CreateFolderRequestRequestTypeDef",
     "FolderMetadataTypeDef",
     "CreateLabelsRequestRequestTypeDef",
     "CreateNotificationSubscriptionRequestRequestTypeDef",
     "SubscriptionTypeDef",
     "StorageRuleTypeTypeDef",
+    "DateRangeTypeTypeDef",
     "DeactivateUserRequestRequestTypeDef",
     "DeleteCommentRequestRequestTypeDef",
     "DeleteCustomMetadataRequestRequestTypeDef",
     "DeleteDocumentRequestRequestTypeDef",
     "DeleteDocumentVersionRequestRequestTypeDef",
     "DeleteFolderContentsRequestRequestTypeDef",
     "DeleteFolderRequestRequestTypeDef",
     "DeleteLabelsRequestRequestTypeDef",
     "DeleteNotificationSubscriptionRequestRequestTypeDef",
     "DeleteUserRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef",
     "DescribeActivitiesRequestRequestTypeDef",
+    "DescribeCommentsRequestDescribeCommentsPaginateTypeDef",
     "DescribeCommentsRequestRequestTypeDef",
+    "DescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef",
     "DescribeDocumentVersionsRequestRequestTypeDef",
     "DocumentVersionMetadataTypeDef",
+    "DescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef",
     "DescribeFolderContentsRequestRequestTypeDef",
+    "DescribeGroupsRequestDescribeGroupsPaginateTypeDef",
     "DescribeGroupsRequestRequestTypeDef",
     "GroupMetadataTypeDef",
+    "DescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef",
     "DescribeNotificationSubscriptionsRequestRequestTypeDef",
+    "DescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef",
     "DescribeResourcePermissionsRequestRequestTypeDef",
+    "DescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef",
     "DescribeRootFoldersRequestRequestTypeDef",
+    "DescribeUsersRequestDescribeUsersPaginateTypeDef",
     "DescribeUsersRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "LongRangeTypeTypeDef",
+    "SearchPrincipalTypeTypeDef",
     "GetCurrentUserRequestRequestTypeDef",
     "GetDocumentPathRequestRequestTypeDef",
     "GetDocumentRequestRequestTypeDef",
     "GetDocumentVersionRequestRequestTypeDef",
     "GetFolderPathRequestRequestTypeDef",
     "GetFolderRequestRequestTypeDef",
     "GetResourcesRequestRequestTypeDef",
     "InitiateDocumentVersionUploadRequestRequestTypeDef",
     "UploadMetadataTypeDef",
+    "PaginatorConfigTypeDef",
     "PermissionInfoTypeDef",
     "RemoveAllResourcePermissionsRequestRequestTypeDef",
     "RemoveResourcePermissionRequestRequestTypeDef",
     "ResourcePathComponentTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreDocumentVersionsRequestRequestTypeDef",
+    "SearchSortResultTypeDef",
     "UpdateDocumentRequestRequestTypeDef",
     "UpdateDocumentVersionRequestRequestTypeDef",
     "UpdateFolderRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ResourceMetadataTypeDef",
     "AddResourcePermissionsRequestRequestTypeDef",
     "AddResourcePermissionsResponseTypeDef",
     "CreateFolderResponseTypeDef",
     "DescribeRootFoldersResponseTypeDef",
     "GetFolderResponseTypeDef",
     "CreateNotificationSubscriptionResponseTypeDef",
     "DescribeNotificationSubscriptionsResponseTypeDef",
     "CreateUserRequestRequestTypeDef",
     "UpdateUserRequestRequestTypeDef",
     "UserStorageMetadataTypeDef",
-    "DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef",
-    "DescribeCommentsRequestDescribeCommentsPaginateTypeDef",
-    "DescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef",
-    "DescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef",
-    "DescribeGroupsRequestDescribeGroupsPaginateTypeDef",
-    "DescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef",
-    "DescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef",
-    "DescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef",
-    "DescribeUsersRequestDescribeUsersPaginateTypeDef",
     "DescribeDocumentVersionsResponseTypeDef",
     "DocumentMetadataTypeDef",
     "GetDocumentVersionResponseTypeDef",
     "DescribeGroupsResponseTypeDef",
     "ParticipantsTypeDef",
+    "FiltersTypeDef",
     "PrincipalTypeDef",
     "ResourcePathTypeDef",
     "UserTypeDef",
     "DescribeFolderContentsResponseTypeDef",
     "GetDocumentResponseTypeDef",
     "GetResourcesResponseTypeDef",
     "InitiateDocumentVersionUploadResponseTypeDef",
+    "SearchResourcesRequestRequestTypeDef",
+    "SearchResourcesRequestSearchResourcesPaginateTypeDef",
     "DescribeResourcePermissionsResponseTypeDef",
     "GetDocumentPathResponseTypeDef",
     "GetFolderPathResponseTypeDef",
     "ActivateUserResponseTypeDef",
     "CommentMetadataTypeDef",
     "CommentTypeDef",
     "CreateUserResponseTypeDef",
     "DescribeUsersResponseTypeDef",
     "GetCurrentUserResponseTypeDef",
     "UpdateUserResponseTypeDef",
     "ActivityTypeDef",
+    "ResponseItemTypeDef",
     "CreateCommentResponseTypeDef",
     "DescribeCommentsResponseTypeDef",
     "DescribeActivitiesResponseTypeDef",
+    "SearchResourcesResponseTypeDef",
 )
 
 _RequiredAbortDocumentVersionUploadRequestRequestTypeDef = TypedDict(
     "_RequiredAbortDocumentVersionUploadRequestRequestTypeDef",
     {
         "DocumentId": str,
         "VersionId": str,
@@ -195,25 +213,14 @@
 
 class ActivateUserRequestRequestTypeDef(
     _RequiredActivateUserRequestRequestTypeDef, _OptionalActivateUserRequestRequestTypeDef
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
 UserMetadataTypeDef = TypedDict(
     "UserMetadataTypeDef",
     {
         "Id": str,
         "Username": str,
         "GivenName": str,
         "Surname": str,
@@ -391,14 +398,23 @@
     {
         "StorageAllocatedInBytes": int,
         "StorageType": StorageTypeType,
     },
     total=False,
 )
 
+DateRangeTypeTypeDef = TypedDict(
+    "DateRangeTypeTypeDef",
+    {
+        "StartValue": Union[datetime, str],
+        "EndValue": Union[datetime, str],
+    },
+    total=False,
+)
+
 _RequiredDeactivateUserRequestRequestTypeDef = TypedDict(
     "_RequiredDeactivateUserRequestRequestTypeDef",
     {
         "UserId": str,
     },
 )
 _OptionalDeactivateUserRequestRequestTypeDef = TypedDict(
@@ -600,20 +616,26 @@
 
 class DeleteUserRequestRequestTypeDef(
     _RequiredDeleteUserRequestRequestTypeDef, _OptionalDeleteUserRequestRequestTypeDef
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef = TypedDict(
+    "DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "AuthenticationToken": str,
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "OrganizationId": str,
+        "ActivityTypes": str,
+        "ResourceId": str,
+        "UserId": str,
+        "IncludeIndirectActivities": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeActivitiesRequestRequestTypeDef = TypedDict(
     "DescribeActivitiesRequestRequestTypeDef",
     {
@@ -627,14 +649,38 @@
         "IncludeIndirectActivities": bool,
         "Limit": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredDescribeCommentsRequestDescribeCommentsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeCommentsRequestDescribeCommentsPaginateTypeDef",
+    {
+        "DocumentId": str,
+        "VersionId": str,
+    },
+)
+_OptionalDescribeCommentsRequestDescribeCommentsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeCommentsRequestDescribeCommentsPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeCommentsRequestDescribeCommentsPaginateTypeDef(
+    _RequiredDescribeCommentsRequestDescribeCommentsPaginateTypeDef,
+    _OptionalDescribeCommentsRequestDescribeCommentsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeCommentsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeCommentsRequestRequestTypeDef",
     {
         "DocumentId": str,
         "VersionId": str,
     },
 )
@@ -651,14 +697,39 @@
 
 class DescribeCommentsRequestRequestTypeDef(
     _RequiredDescribeCommentsRequestRequestTypeDef, _OptionalDescribeCommentsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef",
+    {
+        "DocumentId": str,
+    },
+)
+_OptionalDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+        "Include": str,
+        "Fields": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef(
+    _RequiredDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef,
+    _OptionalDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeDocumentVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeDocumentVersionsRequestRequestTypeDef",
     {
         "DocumentId": str,
     },
 )
 _OptionalDescribeDocumentVersionsRequestRequestTypeDef = TypedDict(
@@ -697,14 +768,41 @@
         "CreatorId": str,
         "Thumbnail": Dict[DocumentThumbnailTypeType, str],
         "Source": Dict[DocumentSourceTypeType, str],
     },
     total=False,
 )
 
+_RequiredDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef",
+    {
+        "FolderId": str,
+    },
+)
+_OptionalDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+        "Sort": ResourceSortTypeType,
+        "Order": OrderTypeType,
+        "Type": FolderContentTypeType,
+        "Include": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef(
+    _RequiredDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef,
+    _OptionalDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeFolderContentsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeFolderContentsRequestRequestTypeDef",
     {
         "FolderId": str,
     },
 )
 _OptionalDescribeFolderContentsRequestRequestTypeDef = TypedDict(
@@ -725,14 +823,38 @@
 class DescribeFolderContentsRequestRequestTypeDef(
     _RequiredDescribeFolderContentsRequestRequestTypeDef,
     _OptionalDescribeFolderContentsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredDescribeGroupsRequestDescribeGroupsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeGroupsRequestDescribeGroupsPaginateTypeDef",
+    {
+        "SearchQuery": str,
+    },
+)
+_OptionalDescribeGroupsRequestDescribeGroupsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeGroupsRequestDescribeGroupsPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+        "OrganizationId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeGroupsRequestDescribeGroupsPaginateTypeDef(
+    _RequiredDescribeGroupsRequestDescribeGroupsPaginateTypeDef,
+    _OptionalDescribeGroupsRequestDescribeGroupsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeGroupsRequestRequestTypeDef",
     {
         "SearchQuery": str,
     },
 )
 _OptionalDescribeGroupsRequestRequestTypeDef = TypedDict(
@@ -758,14 +880,36 @@
     {
         "Id": str,
         "Name": str,
     },
     total=False,
 )
 
+_RequiredDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef",
+    {
+        "OrganizationId": str,
+    },
+)
+_OptionalDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef(
+    _RequiredDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef,
+    _OptionalDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeNotificationSubscriptionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeNotificationSubscriptionsRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 _OptionalDescribeNotificationSubscriptionsRequestRequestTypeDef = TypedDict(
@@ -781,14 +925,38 @@
 class DescribeNotificationSubscriptionsRequestRequestTypeDef(
     _RequiredDescribeNotificationSubscriptionsRequestRequestTypeDef,
     _OptionalDescribeNotificationSubscriptionsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef",
+    {
+        "ResourceId": str,
+    },
+)
+_OptionalDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+        "PrincipalId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef(
+    _RequiredDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef,
+    _OptionalDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeResourcePermissionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeResourcePermissionsRequestRequestTypeDef",
     {
         "ResourceId": str,
     },
 )
 _OptionalDescribeResourcePermissionsRequestRequestTypeDef = TypedDict(
@@ -806,14 +974,36 @@
 class DescribeResourcePermissionsRequestRequestTypeDef(
     _RequiredDescribeResourcePermissionsRequestRequestTypeDef,
     _OptionalDescribeResourcePermissionsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+    },
+)
+_OptionalDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef(
+    _RequiredDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef,
+    _OptionalDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeRootFoldersRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeRootFoldersRequestRequestTypeDef",
     {
         "AuthenticationToken": str,
     },
 )
 _OptionalDescribeRootFoldersRequestRequestTypeDef = TypedDict(
@@ -829,14 +1019,30 @@
 class DescribeRootFoldersRequestRequestTypeDef(
     _RequiredDescribeRootFoldersRequestRequestTypeDef,
     _OptionalDescribeRootFoldersRequestRequestTypeDef,
 ):
     pass
 
 
+DescribeUsersRequestDescribeUsersPaginateTypeDef = TypedDict(
+    "DescribeUsersRequestDescribeUsersPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+        "OrganizationId": str,
+        "UserIds": str,
+        "Query": str,
+        "Include": UserFilterTypeType,
+        "Order": OrderTypeType,
+        "Sort": UserSortTypeType,
+        "Fields": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeUsersRequestRequestTypeDef = TypedDict(
     "DescribeUsersRequestRequestTypeDef",
     {
         "AuthenticationToken": str,
         "OrganizationId": str,
         "UserIds": str,
         "Query": str,
@@ -846,14 +1052,51 @@
         "Marker": str,
         "Limit": int,
         "Fields": str,
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
+LongRangeTypeTypeDef = TypedDict(
+    "LongRangeTypeTypeDef",
+    {
+        "StartValue": int,
+        "EndValue": int,
+    },
+    total=False,
+)
+
+_RequiredSearchPrincipalTypeTypeDef = TypedDict(
+    "_RequiredSearchPrincipalTypeTypeDef",
+    {
+        "Id": str,
+    },
+)
+_OptionalSearchPrincipalTypeTypeDef = TypedDict(
+    "_OptionalSearchPrincipalTypeTypeDef",
+    {
+        "Roles": Sequence[PrincipalRoleTypeType],
+    },
+    total=False,
+)
+
+
+class SearchPrincipalTypeTypeDef(
+    _RequiredSearchPrincipalTypeTypeDef, _OptionalSearchPrincipalTypeTypeDef
+):
+    pass
+
+
 GetCurrentUserRequestRequestTypeDef = TypedDict(
     "GetCurrentUserRequestRequestTypeDef",
     {
         "AuthenticationToken": str,
     },
 )
 
@@ -1006,14 +1249,24 @@
     {
         "UploadUrl": str,
         "SignedHeaders": Dict[str, str],
     },
     total=False,
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
 PermissionInfoTypeDef = TypedDict(
     "PermissionInfoTypeDef",
     {
         "Role": RoleTypeType,
         "Type": RolePermissionTypeType,
     },
     total=False,
@@ -1070,14 +1323,25 @@
     {
         "Id": str,
         "Name": str,
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
 _RequiredRestoreDocumentVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredRestoreDocumentVersionsRequestRequestTypeDef",
     {
         "DocumentId": str,
     },
 )
 _OptionalRestoreDocumentVersionsRequestRequestTypeDef = TypedDict(
@@ -1092,14 +1356,23 @@
 class RestoreDocumentVersionsRequestRequestTypeDef(
     _RequiredRestoreDocumentVersionsRequestRequestTypeDef,
     _OptionalRestoreDocumentVersionsRequestRequestTypeDef,
 ):
     pass
 
 
+SearchSortResultTypeDef = TypedDict(
+    "SearchSortResultTypeDef",
+    {
+        "Field": OrderByFieldTypeType,
+        "Order": SortOrderType,
+    },
+    total=False,
+)
+
 _RequiredUpdateDocumentRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDocumentRequestRequestTypeDef",
     {
         "DocumentId": str,
     },
 )
 _OptionalUpdateDocumentRequestRequestTypeDef = TypedDict(
@@ -1164,21 +1437,14 @@
 
 class UpdateFolderRequestRequestTypeDef(
     _RequiredUpdateFolderRequestRequestTypeDef, _OptionalUpdateFolderRequestRequestTypeDef
 ):
     pass
 
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ResourceMetadataTypeDef = TypedDict(
     "ResourceMetadataTypeDef",
     {
         "Type": ResourceTypeType,
         "Name": str,
         "OriginalName": str,
         "Id": str,
@@ -1213,58 +1479,58 @@
     pass
 
 
 AddResourcePermissionsResponseTypeDef = TypedDict(
     "AddResourcePermissionsResponseTypeDef",
     {
         "ShareResults": List[ShareResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFolderResponseTypeDef = TypedDict(
     "CreateFolderResponseTypeDef",
     {
         "Metadata": FolderMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRootFoldersResponseTypeDef = TypedDict(
     "DescribeRootFoldersResponseTypeDef",
     {
         "Folders": List[FolderMetadataTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFolderResponseTypeDef = TypedDict(
     "GetFolderResponseTypeDef",
     {
         "Metadata": FolderMetadataTypeDef,
         "CustomMetadata": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateNotificationSubscriptionResponseTypeDef = TypedDict(
     "CreateNotificationSubscriptionResponseTypeDef",
     {
         "Subscription": SubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeNotificationSubscriptionsResponseTypeDef = TypedDict(
     "DescribeNotificationSubscriptionsResponseTypeDef",
     {
         "Subscriptions": List[SubscriptionTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateUserRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserRequestRequestTypeDef",
     {
         "Username": str,
@@ -1325,220 +1591,20 @@
     {
         "StorageUtilizedInBytes": int,
         "StorageRule": StorageRuleTypeTypeDef,
     },
     total=False,
 )
 
-DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef = TypedDict(
-    "DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "OrganizationId": str,
-        "ActivityTypes": str,
-        "ResourceId": str,
-        "UserId": str,
-        "IncludeIndirectActivities": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeCommentsRequestDescribeCommentsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeCommentsRequestDescribeCommentsPaginateTypeDef",
-    {
-        "DocumentId": str,
-        "VersionId": str,
-    },
-)
-_OptionalDescribeCommentsRequestDescribeCommentsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeCommentsRequestDescribeCommentsPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeCommentsRequestDescribeCommentsPaginateTypeDef(
-    _RequiredDescribeCommentsRequestDescribeCommentsPaginateTypeDef,
-    _OptionalDescribeCommentsRequestDescribeCommentsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef",
-    {
-        "DocumentId": str,
-    },
-)
-_OptionalDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-        "Include": str,
-        "Fields": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef(
-    _RequiredDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef,
-    _OptionalDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef",
-    {
-        "FolderId": str,
-    },
-)
-_OptionalDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-        "Sort": ResourceSortTypeType,
-        "Order": OrderTypeType,
-        "Type": FolderContentTypeType,
-        "Include": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef(
-    _RequiredDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef,
-    _OptionalDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeGroupsRequestDescribeGroupsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeGroupsRequestDescribeGroupsPaginateTypeDef",
-    {
-        "SearchQuery": str,
-    },
-)
-_OptionalDescribeGroupsRequestDescribeGroupsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeGroupsRequestDescribeGroupsPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-        "OrganizationId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeGroupsRequestDescribeGroupsPaginateTypeDef(
-    _RequiredDescribeGroupsRequestDescribeGroupsPaginateTypeDef,
-    _OptionalDescribeGroupsRequestDescribeGroupsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef",
-    {
-        "OrganizationId": str,
-    },
-)
-_OptionalDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef(
-    _RequiredDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef,
-    _OptionalDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef",
-    {
-        "ResourceId": str,
-    },
-)
-_OptionalDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-        "PrincipalId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef(
-    _RequiredDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef,
-    _OptionalDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-    },
-)
-_OptionalDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef(
-    _RequiredDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef,
-    _OptionalDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef,
-):
-    pass
-
-
-DescribeUsersRequestDescribeUsersPaginateTypeDef = TypedDict(
-    "DescribeUsersRequestDescribeUsersPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-        "OrganizationId": str,
-        "UserIds": str,
-        "Query": str,
-        "Include": UserFilterTypeType,
-        "Order": OrderTypeType,
-        "Sort": UserSortTypeType,
-        "Fields": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeDocumentVersionsResponseTypeDef = TypedDict(
     "DescribeDocumentVersionsResponseTypeDef",
     {
         "DocumentVersions": List[DocumentVersionMetadataTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DocumentMetadataTypeDef = TypedDict(
     "DocumentMetadataTypeDef",
     {
         "Id": str,
@@ -1554,36 +1620,53 @@
 )
 
 GetDocumentVersionResponseTypeDef = TypedDict(
     "GetDocumentVersionResponseTypeDef",
     {
         "Metadata": DocumentVersionMetadataTypeDef,
         "CustomMetadata": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGroupsResponseTypeDef = TypedDict(
     "DescribeGroupsResponseTypeDef",
     {
         "Groups": List[GroupMetadataTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ParticipantsTypeDef = TypedDict(
     "ParticipantsTypeDef",
     {
         "Users": List[UserMetadataTypeDef],
         "Groups": List[GroupMetadataTypeDef],
     },
     total=False,
 )
 
+FiltersTypeDef = TypedDict(
+    "FiltersTypeDef",
+    {
+        "TextLocales": Sequence[LanguageCodeTypeType],
+        "ContentCategories": Sequence[ContentCategoryTypeType],
+        "ResourceTypes": Sequence[SearchResourceTypeType],
+        "Labels": Sequence[str],
+        "Principals": Sequence[SearchPrincipalTypeTypeDef],
+        "AncestorIds": Sequence[str],
+        "SearchCollectionTypes": Sequence[SearchCollectionTypeType],
+        "SizeRange": LongRangeTypeTypeDef,
+        "CreatedRange": DateRangeTypeTypeDef,
+        "ModifiedRange": DateRangeTypeTypeDef,
+    },
+    total=False,
+)
+
 PrincipalTypeDef = TypedDict(
     "PrincipalTypeDef",
     {
         "Id": str,
         "Type": PrincipalTypeType,
         "Roles": List[PermissionInfoTypeDef],
     },
@@ -1622,87 +1705,119 @@
 
 DescribeFolderContentsResponseTypeDef = TypedDict(
     "DescribeFolderContentsResponseTypeDef",
     {
         "Folders": List[FolderMetadataTypeDef],
         "Documents": List[DocumentMetadataTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDocumentResponseTypeDef = TypedDict(
     "GetDocumentResponseTypeDef",
     {
         "Metadata": DocumentMetadataTypeDef,
         "CustomMetadata": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourcesResponseTypeDef = TypedDict(
     "GetResourcesResponseTypeDef",
     {
         "Folders": List[FolderMetadataTypeDef],
         "Documents": List[DocumentMetadataTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InitiateDocumentVersionUploadResponseTypeDef = TypedDict(
     "InitiateDocumentVersionUploadResponseTypeDef",
     {
         "Metadata": DocumentMetadataTypeDef,
         "UploadMetadata": UploadMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SearchResourcesRequestRequestTypeDef = TypedDict(
+    "SearchResourcesRequestRequestTypeDef",
+    {
+        "AuthenticationToken": str,
+        "QueryText": str,
+        "QueryScopes": Sequence[SearchQueryScopeTypeType],
+        "OrganizationId": str,
+        "AdditionalResponseFields": Sequence[Literal["WEBURL"]],
+        "Filters": FiltersTypeDef,
+        "OrderBy": Sequence[SearchSortResultTypeDef],
+        "Limit": int,
+        "Marker": str,
+    },
+    total=False,
+)
+
+SearchResourcesRequestSearchResourcesPaginateTypeDef = TypedDict(
+    "SearchResourcesRequestSearchResourcesPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+        "QueryText": str,
+        "QueryScopes": Sequence[SearchQueryScopeTypeType],
+        "OrganizationId": str,
+        "AdditionalResponseFields": Sequence[Literal["WEBURL"]],
+        "Filters": FiltersTypeDef,
+        "OrderBy": Sequence[SearchSortResultTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
 DescribeResourcePermissionsResponseTypeDef = TypedDict(
     "DescribeResourcePermissionsResponseTypeDef",
     {
         "Principals": List[PrincipalTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDocumentPathResponseTypeDef = TypedDict(
     "GetDocumentPathResponseTypeDef",
     {
         "Path": ResourcePathTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFolderPathResponseTypeDef = TypedDict(
     "GetFolderPathResponseTypeDef",
     {
         "Path": ResourcePathTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActivateUserResponseTypeDef = TypedDict(
     "ActivateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CommentMetadataTypeDef = TypedDict(
     "CommentMetadataTypeDef",
     {
         "CommentId": str,
         "Contributor": UserTypeDef,
         "CreatedTimestamp": datetime,
         "CommentStatus": CommentStatusTypeType,
         "RecipientId": str,
+        "ContributorId": str,
     },
     total=False,
 )
 
 _RequiredCommentTypeDef = TypedDict(
     "_RequiredCommentTypeDef",
     {
@@ -1729,41 +1844,41 @@
     pass
 
 
 CreateUserResponseTypeDef = TypedDict(
     "CreateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUsersResponseTypeDef = TypedDict(
     "DescribeUsersResponseTypeDef",
     {
         "Users": List[UserTypeDef],
         "TotalNumberOfUsers": int,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCurrentUserResponseTypeDef = TypedDict(
     "GetCurrentUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUserResponseTypeDef = TypedDict(
     "UpdateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActivityTypeDef = TypedDict(
     "ActivityTypeDef",
     {
         "Type": ActivityTypeType,
@@ -1775,32 +1890,54 @@
         "ResourceMetadata": ResourceMetadataTypeDef,
         "OriginalParent": ResourceMetadataTypeDef,
         "CommentMetadata": CommentMetadataTypeDef,
     },
     total=False,
 )
 
+ResponseItemTypeDef = TypedDict(
+    "ResponseItemTypeDef",
+    {
+        "ResourceType": ResponseItemTypeType,
+        "WebUrl": str,
+        "DocumentMetadata": DocumentMetadataTypeDef,
+        "FolderMetadata": FolderMetadataTypeDef,
+        "CommentMetadata": CommentMetadataTypeDef,
+        "DocumentVersionMetadata": DocumentVersionMetadataTypeDef,
+    },
+    total=False,
+)
+
 CreateCommentResponseTypeDef = TypedDict(
     "CreateCommentResponseTypeDef",
     {
         "Comment": CommentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCommentsResponseTypeDef = TypedDict(
     "DescribeCommentsResponseTypeDef",
     {
         "Comments": List[CommentTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeActivitiesResponseTypeDef = TypedDict(
     "DescribeActivitiesResponseTypeDef",
     {
         "UserActivities": List[ActivityTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SearchResourcesResponseTypeDef = TypedDict(
+    "SearchResourcesResponseTypeDef",
+    {
+        "Items": List[ResponseItemTypeDef],
+        "Marker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs/type_defs.pyi` & `types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -16,27 +16,36 @@
 from typing import Dict, List, Mapping, Sequence, Union
 
 from .literals import (
     ActivityTypeType,
     BooleanEnumTypeType,
     CommentStatusTypeType,
     CommentVisibilityTypeType,
+    ContentCategoryTypeType,
     DocumentSourceTypeType,
     DocumentStatusTypeType,
     DocumentThumbnailTypeType,
     FolderContentTypeType,
+    LanguageCodeTypeType,
     LocaleTypeType,
+    OrderByFieldTypeType,
     OrderTypeType,
+    PrincipalRoleTypeType,
     PrincipalTypeType,
     ResourceSortTypeType,
     ResourceStateTypeType,
     ResourceTypeType,
+    ResponseItemTypeType,
     RolePermissionTypeType,
     RoleTypeType,
+    SearchCollectionTypeType,
+    SearchQueryScopeTypeType,
+    SearchResourceTypeType,
     ShareStatusTypeType,
+    SortOrderType,
     StorageTypeType,
     SubscriptionProtocolTypeType,
     UserFilterTypeType,
     UserSortTypeType,
     UserStatusTypeType,
     UserTypeType,
 )
@@ -49,113 +58,122 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AbortDocumentVersionUploadRequestRequestTypeDef",
     "ActivateUserRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "UserMetadataTypeDef",
     "NotificationOptionsTypeDef",
     "SharePrincipalTypeDef",
     "ShareResultTypeDef",
     "CreateCommentRequestRequestTypeDef",
     "CreateCustomMetadataRequestRequestTypeDef",
     "CreateFolderRequestRequestTypeDef",
     "FolderMetadataTypeDef",
     "CreateLabelsRequestRequestTypeDef",
     "CreateNotificationSubscriptionRequestRequestTypeDef",
     "SubscriptionTypeDef",
     "StorageRuleTypeTypeDef",
+    "DateRangeTypeTypeDef",
     "DeactivateUserRequestRequestTypeDef",
     "DeleteCommentRequestRequestTypeDef",
     "DeleteCustomMetadataRequestRequestTypeDef",
     "DeleteDocumentRequestRequestTypeDef",
     "DeleteDocumentVersionRequestRequestTypeDef",
     "DeleteFolderContentsRequestRequestTypeDef",
     "DeleteFolderRequestRequestTypeDef",
     "DeleteLabelsRequestRequestTypeDef",
     "DeleteNotificationSubscriptionRequestRequestTypeDef",
     "DeleteUserRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef",
     "DescribeActivitiesRequestRequestTypeDef",
+    "DescribeCommentsRequestDescribeCommentsPaginateTypeDef",
     "DescribeCommentsRequestRequestTypeDef",
+    "DescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef",
     "DescribeDocumentVersionsRequestRequestTypeDef",
     "DocumentVersionMetadataTypeDef",
+    "DescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef",
     "DescribeFolderContentsRequestRequestTypeDef",
+    "DescribeGroupsRequestDescribeGroupsPaginateTypeDef",
     "DescribeGroupsRequestRequestTypeDef",
     "GroupMetadataTypeDef",
+    "DescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef",
     "DescribeNotificationSubscriptionsRequestRequestTypeDef",
+    "DescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef",
     "DescribeResourcePermissionsRequestRequestTypeDef",
+    "DescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef",
     "DescribeRootFoldersRequestRequestTypeDef",
+    "DescribeUsersRequestDescribeUsersPaginateTypeDef",
     "DescribeUsersRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "LongRangeTypeTypeDef",
+    "SearchPrincipalTypeTypeDef",
     "GetCurrentUserRequestRequestTypeDef",
     "GetDocumentPathRequestRequestTypeDef",
     "GetDocumentRequestRequestTypeDef",
     "GetDocumentVersionRequestRequestTypeDef",
     "GetFolderPathRequestRequestTypeDef",
     "GetFolderRequestRequestTypeDef",
     "GetResourcesRequestRequestTypeDef",
     "InitiateDocumentVersionUploadRequestRequestTypeDef",
     "UploadMetadataTypeDef",
+    "PaginatorConfigTypeDef",
     "PermissionInfoTypeDef",
     "RemoveAllResourcePermissionsRequestRequestTypeDef",
     "RemoveResourcePermissionRequestRequestTypeDef",
     "ResourcePathComponentTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreDocumentVersionsRequestRequestTypeDef",
+    "SearchSortResultTypeDef",
     "UpdateDocumentRequestRequestTypeDef",
     "UpdateDocumentVersionRequestRequestTypeDef",
     "UpdateFolderRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ResourceMetadataTypeDef",
     "AddResourcePermissionsRequestRequestTypeDef",
     "AddResourcePermissionsResponseTypeDef",
     "CreateFolderResponseTypeDef",
     "DescribeRootFoldersResponseTypeDef",
     "GetFolderResponseTypeDef",
     "CreateNotificationSubscriptionResponseTypeDef",
     "DescribeNotificationSubscriptionsResponseTypeDef",
     "CreateUserRequestRequestTypeDef",
     "UpdateUserRequestRequestTypeDef",
     "UserStorageMetadataTypeDef",
-    "DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef",
-    "DescribeCommentsRequestDescribeCommentsPaginateTypeDef",
-    "DescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef",
-    "DescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef",
-    "DescribeGroupsRequestDescribeGroupsPaginateTypeDef",
-    "DescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef",
-    "DescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef",
-    "DescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef",
-    "DescribeUsersRequestDescribeUsersPaginateTypeDef",
     "DescribeDocumentVersionsResponseTypeDef",
     "DocumentMetadataTypeDef",
     "GetDocumentVersionResponseTypeDef",
     "DescribeGroupsResponseTypeDef",
     "ParticipantsTypeDef",
+    "FiltersTypeDef",
     "PrincipalTypeDef",
     "ResourcePathTypeDef",
     "UserTypeDef",
     "DescribeFolderContentsResponseTypeDef",
     "GetDocumentResponseTypeDef",
     "GetResourcesResponseTypeDef",
     "InitiateDocumentVersionUploadResponseTypeDef",
+    "SearchResourcesRequestRequestTypeDef",
+    "SearchResourcesRequestSearchResourcesPaginateTypeDef",
     "DescribeResourcePermissionsResponseTypeDef",
     "GetDocumentPathResponseTypeDef",
     "GetFolderPathResponseTypeDef",
     "ActivateUserResponseTypeDef",
     "CommentMetadataTypeDef",
     "CommentTypeDef",
     "CreateUserResponseTypeDef",
     "DescribeUsersResponseTypeDef",
     "GetCurrentUserResponseTypeDef",
     "UpdateUserResponseTypeDef",
     "ActivityTypeDef",
+    "ResponseItemTypeDef",
     "CreateCommentResponseTypeDef",
     "DescribeCommentsResponseTypeDef",
     "DescribeActivitiesResponseTypeDef",
+    "SearchResourcesResponseTypeDef",
 )
 
 _RequiredAbortDocumentVersionUploadRequestRequestTypeDef = TypedDict(
     "_RequiredAbortDocumentVersionUploadRequestRequestTypeDef",
     {
         "DocumentId": str,
         "VersionId": str,
@@ -190,25 +208,14 @@
 )
 
 class ActivateUserRequestRequestTypeDef(
     _RequiredActivateUserRequestRequestTypeDef, _OptionalActivateUserRequestRequestTypeDef
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
 UserMetadataTypeDef = TypedDict(
     "UserMetadataTypeDef",
     {
         "Id": str,
         "Username": str,
         "GivenName": str,
         "Surname": str,
@@ -378,14 +385,23 @@
     {
         "StorageAllocatedInBytes": int,
         "StorageType": StorageTypeType,
     },
     total=False,
 )
 
+DateRangeTypeTypeDef = TypedDict(
+    "DateRangeTypeTypeDef",
+    {
+        "StartValue": Union[datetime, str],
+        "EndValue": Union[datetime, str],
+    },
+    total=False,
+)
+
 _RequiredDeactivateUserRequestRequestTypeDef = TypedDict(
     "_RequiredDeactivateUserRequestRequestTypeDef",
     {
         "UserId": str,
     },
 )
 _OptionalDeactivateUserRequestRequestTypeDef = TypedDict(
@@ -569,20 +585,26 @@
 )
 
 class DeleteUserRequestRequestTypeDef(
     _RequiredDeleteUserRequestRequestTypeDef, _OptionalDeleteUserRequestRequestTypeDef
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef = TypedDict(
+    "DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "AuthenticationToken": str,
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "OrganizationId": str,
+        "ActivityTypes": str,
+        "ResourceId": str,
+        "UserId": str,
+        "IncludeIndirectActivities": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeActivitiesRequestRequestTypeDef = TypedDict(
     "DescribeActivitiesRequestRequestTypeDef",
     {
@@ -596,14 +618,36 @@
         "IncludeIndirectActivities": bool,
         "Limit": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredDescribeCommentsRequestDescribeCommentsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeCommentsRequestDescribeCommentsPaginateTypeDef",
+    {
+        "DocumentId": str,
+        "VersionId": str,
+    },
+)
+_OptionalDescribeCommentsRequestDescribeCommentsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeCommentsRequestDescribeCommentsPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeCommentsRequestDescribeCommentsPaginateTypeDef(
+    _RequiredDescribeCommentsRequestDescribeCommentsPaginateTypeDef,
+    _OptionalDescribeCommentsRequestDescribeCommentsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeCommentsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeCommentsRequestRequestTypeDef",
     {
         "DocumentId": str,
         "VersionId": str,
     },
 )
@@ -618,14 +662,37 @@
 )
 
 class DescribeCommentsRequestRequestTypeDef(
     _RequiredDescribeCommentsRequestRequestTypeDef, _OptionalDescribeCommentsRequestRequestTypeDef
 ):
     pass
 
+_RequiredDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef",
+    {
+        "DocumentId": str,
+    },
+)
+_OptionalDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+        "Include": str,
+        "Fields": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef(
+    _RequiredDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef,
+    _OptionalDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeDocumentVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeDocumentVersionsRequestRequestTypeDef",
     {
         "DocumentId": str,
     },
 )
 _OptionalDescribeDocumentVersionsRequestRequestTypeDef = TypedDict(
@@ -662,14 +729,39 @@
         "CreatorId": str,
         "Thumbnail": Dict[DocumentThumbnailTypeType, str],
         "Source": Dict[DocumentSourceTypeType, str],
     },
     total=False,
 )
 
+_RequiredDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef",
+    {
+        "FolderId": str,
+    },
+)
+_OptionalDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+        "Sort": ResourceSortTypeType,
+        "Order": OrderTypeType,
+        "Type": FolderContentTypeType,
+        "Include": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef(
+    _RequiredDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef,
+    _OptionalDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeFolderContentsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeFolderContentsRequestRequestTypeDef",
     {
         "FolderId": str,
     },
 )
 _OptionalDescribeFolderContentsRequestRequestTypeDef = TypedDict(
@@ -688,14 +780,36 @@
 
 class DescribeFolderContentsRequestRequestTypeDef(
     _RequiredDescribeFolderContentsRequestRequestTypeDef,
     _OptionalDescribeFolderContentsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredDescribeGroupsRequestDescribeGroupsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeGroupsRequestDescribeGroupsPaginateTypeDef",
+    {
+        "SearchQuery": str,
+    },
+)
+_OptionalDescribeGroupsRequestDescribeGroupsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeGroupsRequestDescribeGroupsPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+        "OrganizationId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeGroupsRequestDescribeGroupsPaginateTypeDef(
+    _RequiredDescribeGroupsRequestDescribeGroupsPaginateTypeDef,
+    _OptionalDescribeGroupsRequestDescribeGroupsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeGroupsRequestRequestTypeDef",
     {
         "SearchQuery": str,
     },
 )
 _OptionalDescribeGroupsRequestRequestTypeDef = TypedDict(
@@ -719,14 +833,34 @@
     {
         "Id": str,
         "Name": str,
     },
     total=False,
 )
 
+_RequiredDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef",
+    {
+        "OrganizationId": str,
+    },
+)
+_OptionalDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef(
+    _RequiredDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef,
+    _OptionalDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeNotificationSubscriptionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeNotificationSubscriptionsRequestRequestTypeDef",
     {
         "OrganizationId": str,
     },
 )
 _OptionalDescribeNotificationSubscriptionsRequestRequestTypeDef = TypedDict(
@@ -740,14 +874,36 @@
 
 class DescribeNotificationSubscriptionsRequestRequestTypeDef(
     _RequiredDescribeNotificationSubscriptionsRequestRequestTypeDef,
     _OptionalDescribeNotificationSubscriptionsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef",
+    {
+        "ResourceId": str,
+    },
+)
+_OptionalDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+        "PrincipalId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef(
+    _RequiredDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef,
+    _OptionalDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeResourcePermissionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeResourcePermissionsRequestRequestTypeDef",
     {
         "ResourceId": str,
     },
 )
 _OptionalDescribeResourcePermissionsRequestRequestTypeDef = TypedDict(
@@ -763,14 +919,34 @@
 
 class DescribeResourcePermissionsRequestRequestTypeDef(
     _RequiredDescribeResourcePermissionsRequestRequestTypeDef,
     _OptionalDescribeResourcePermissionsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+    },
+)
+_OptionalDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef(
+    _RequiredDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef,
+    _OptionalDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeRootFoldersRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeRootFoldersRequestRequestTypeDef",
     {
         "AuthenticationToken": str,
     },
 )
 _OptionalDescribeRootFoldersRequestRequestTypeDef = TypedDict(
@@ -784,14 +960,30 @@
 
 class DescribeRootFoldersRequestRequestTypeDef(
     _RequiredDescribeRootFoldersRequestRequestTypeDef,
     _OptionalDescribeRootFoldersRequestRequestTypeDef,
 ):
     pass
 
+DescribeUsersRequestDescribeUsersPaginateTypeDef = TypedDict(
+    "DescribeUsersRequestDescribeUsersPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+        "OrganizationId": str,
+        "UserIds": str,
+        "Query": str,
+        "Include": UserFilterTypeType,
+        "Order": OrderTypeType,
+        "Sort": UserSortTypeType,
+        "Fields": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeUsersRequestRequestTypeDef = TypedDict(
     "DescribeUsersRequestRequestTypeDef",
     {
         "AuthenticationToken": str,
         "OrganizationId": str,
         "UserIds": str,
         "Query": str,
@@ -801,14 +993,49 @@
         "Marker": str,
         "Limit": int,
         "Fields": str,
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
+LongRangeTypeTypeDef = TypedDict(
+    "LongRangeTypeTypeDef",
+    {
+        "StartValue": int,
+        "EndValue": int,
+    },
+    total=False,
+)
+
+_RequiredSearchPrincipalTypeTypeDef = TypedDict(
+    "_RequiredSearchPrincipalTypeTypeDef",
+    {
+        "Id": str,
+    },
+)
+_OptionalSearchPrincipalTypeTypeDef = TypedDict(
+    "_OptionalSearchPrincipalTypeTypeDef",
+    {
+        "Roles": Sequence[PrincipalRoleTypeType],
+    },
+    total=False,
+)
+
+class SearchPrincipalTypeTypeDef(
+    _RequiredSearchPrincipalTypeTypeDef, _OptionalSearchPrincipalTypeTypeDef
+):
+    pass
+
 GetCurrentUserRequestRequestTypeDef = TypedDict(
     "GetCurrentUserRequestRequestTypeDef",
     {
         "AuthenticationToken": str,
     },
 )
 
@@ -951,14 +1178,24 @@
     {
         "UploadUrl": str,
         "SignedHeaders": Dict[str, str],
     },
     total=False,
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
 PermissionInfoTypeDef = TypedDict(
     "PermissionInfoTypeDef",
     {
         "Role": RoleTypeType,
         "Type": RolePermissionTypeType,
     },
     total=False,
@@ -1011,14 +1248,25 @@
     {
         "Id": str,
         "Name": str,
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
 _RequiredRestoreDocumentVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredRestoreDocumentVersionsRequestRequestTypeDef",
     {
         "DocumentId": str,
     },
 )
 _OptionalRestoreDocumentVersionsRequestRequestTypeDef = TypedDict(
@@ -1031,14 +1279,23 @@
 
 class RestoreDocumentVersionsRequestRequestTypeDef(
     _RequiredRestoreDocumentVersionsRequestRequestTypeDef,
     _OptionalRestoreDocumentVersionsRequestRequestTypeDef,
 ):
     pass
 
+SearchSortResultTypeDef = TypedDict(
+    "SearchSortResultTypeDef",
+    {
+        "Field": OrderByFieldTypeType,
+        "Order": SortOrderType,
+    },
+    total=False,
+)
+
 _RequiredUpdateDocumentRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDocumentRequestRequestTypeDef",
     {
         "DocumentId": str,
     },
 )
 _OptionalUpdateDocumentRequestRequestTypeDef = TypedDict(
@@ -1097,21 +1354,14 @@
 )
 
 class UpdateFolderRequestRequestTypeDef(
     _RequiredUpdateFolderRequestRequestTypeDef, _OptionalUpdateFolderRequestRequestTypeDef
 ):
     pass
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ResourceMetadataTypeDef = TypedDict(
     "ResourceMetadataTypeDef",
     {
         "Type": ResourceTypeType,
         "Name": str,
         "OriginalName": str,
         "Id": str,
@@ -1144,58 +1394,58 @@
 ):
     pass
 
 AddResourcePermissionsResponseTypeDef = TypedDict(
     "AddResourcePermissionsResponseTypeDef",
     {
         "ShareResults": List[ShareResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFolderResponseTypeDef = TypedDict(
     "CreateFolderResponseTypeDef",
     {
         "Metadata": FolderMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRootFoldersResponseTypeDef = TypedDict(
     "DescribeRootFoldersResponseTypeDef",
     {
         "Folders": List[FolderMetadataTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFolderResponseTypeDef = TypedDict(
     "GetFolderResponseTypeDef",
     {
         "Metadata": FolderMetadataTypeDef,
         "CustomMetadata": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateNotificationSubscriptionResponseTypeDef = TypedDict(
     "CreateNotificationSubscriptionResponseTypeDef",
     {
         "Subscription": SubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeNotificationSubscriptionsResponseTypeDef = TypedDict(
     "DescribeNotificationSubscriptionsResponseTypeDef",
     {
         "Subscriptions": List[SubscriptionTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateUserRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserRequestRequestTypeDef",
     {
         "Username": str,
@@ -1252,206 +1502,20 @@
     {
         "StorageUtilizedInBytes": int,
         "StorageRule": StorageRuleTypeTypeDef,
     },
     total=False,
 )
 
-DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef = TypedDict(
-    "DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "OrganizationId": str,
-        "ActivityTypes": str,
-        "ResourceId": str,
-        "UserId": str,
-        "IncludeIndirectActivities": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeCommentsRequestDescribeCommentsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeCommentsRequestDescribeCommentsPaginateTypeDef",
-    {
-        "DocumentId": str,
-        "VersionId": str,
-    },
-)
-_OptionalDescribeCommentsRequestDescribeCommentsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeCommentsRequestDescribeCommentsPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeCommentsRequestDescribeCommentsPaginateTypeDef(
-    _RequiredDescribeCommentsRequestDescribeCommentsPaginateTypeDef,
-    _OptionalDescribeCommentsRequestDescribeCommentsPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef",
-    {
-        "DocumentId": str,
-    },
-)
-_OptionalDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-        "Include": str,
-        "Fields": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef(
-    _RequiredDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef,
-    _OptionalDescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef",
-    {
-        "FolderId": str,
-    },
-)
-_OptionalDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-        "Sort": ResourceSortTypeType,
-        "Order": OrderTypeType,
-        "Type": FolderContentTypeType,
-        "Include": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef(
-    _RequiredDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef,
-    _OptionalDescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeGroupsRequestDescribeGroupsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeGroupsRequestDescribeGroupsPaginateTypeDef",
-    {
-        "SearchQuery": str,
-    },
-)
-_OptionalDescribeGroupsRequestDescribeGroupsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeGroupsRequestDescribeGroupsPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-        "OrganizationId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeGroupsRequestDescribeGroupsPaginateTypeDef(
-    _RequiredDescribeGroupsRequestDescribeGroupsPaginateTypeDef,
-    _OptionalDescribeGroupsRequestDescribeGroupsPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef",
-    {
-        "OrganizationId": str,
-    },
-)
-_OptionalDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef(
-    _RequiredDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef,
-    _OptionalDescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef",
-    {
-        "ResourceId": str,
-    },
-)
-_OptionalDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-        "PrincipalId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef(
-    _RequiredDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef,
-    _OptionalDescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-    },
-)
-_OptionalDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef(
-    _RequiredDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef,
-    _OptionalDescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef,
-):
-    pass
-
-DescribeUsersRequestDescribeUsersPaginateTypeDef = TypedDict(
-    "DescribeUsersRequestDescribeUsersPaginateTypeDef",
-    {
-        "AuthenticationToken": str,
-        "OrganizationId": str,
-        "UserIds": str,
-        "Query": str,
-        "Include": UserFilterTypeType,
-        "Order": OrderTypeType,
-        "Sort": UserSortTypeType,
-        "Fields": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeDocumentVersionsResponseTypeDef = TypedDict(
     "DescribeDocumentVersionsResponseTypeDef",
     {
         "DocumentVersions": List[DocumentVersionMetadataTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DocumentMetadataTypeDef = TypedDict(
     "DocumentMetadataTypeDef",
     {
         "Id": str,
@@ -1467,36 +1531,53 @@
 )
 
 GetDocumentVersionResponseTypeDef = TypedDict(
     "GetDocumentVersionResponseTypeDef",
     {
         "Metadata": DocumentVersionMetadataTypeDef,
         "CustomMetadata": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGroupsResponseTypeDef = TypedDict(
     "DescribeGroupsResponseTypeDef",
     {
         "Groups": List[GroupMetadataTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ParticipantsTypeDef = TypedDict(
     "ParticipantsTypeDef",
     {
         "Users": List[UserMetadataTypeDef],
         "Groups": List[GroupMetadataTypeDef],
     },
     total=False,
 )
 
+FiltersTypeDef = TypedDict(
+    "FiltersTypeDef",
+    {
+        "TextLocales": Sequence[LanguageCodeTypeType],
+        "ContentCategories": Sequence[ContentCategoryTypeType],
+        "ResourceTypes": Sequence[SearchResourceTypeType],
+        "Labels": Sequence[str],
+        "Principals": Sequence[SearchPrincipalTypeTypeDef],
+        "AncestorIds": Sequence[str],
+        "SearchCollectionTypes": Sequence[SearchCollectionTypeType],
+        "SizeRange": LongRangeTypeTypeDef,
+        "CreatedRange": DateRangeTypeTypeDef,
+        "ModifiedRange": DateRangeTypeTypeDef,
+    },
+    total=False,
+)
+
 PrincipalTypeDef = TypedDict(
     "PrincipalTypeDef",
     {
         "Id": str,
         "Type": PrincipalTypeType,
         "Roles": List[PermissionInfoTypeDef],
     },
@@ -1535,87 +1616,119 @@
 
 DescribeFolderContentsResponseTypeDef = TypedDict(
     "DescribeFolderContentsResponseTypeDef",
     {
         "Folders": List[FolderMetadataTypeDef],
         "Documents": List[DocumentMetadataTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDocumentResponseTypeDef = TypedDict(
     "GetDocumentResponseTypeDef",
     {
         "Metadata": DocumentMetadataTypeDef,
         "CustomMetadata": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourcesResponseTypeDef = TypedDict(
     "GetResourcesResponseTypeDef",
     {
         "Folders": List[FolderMetadataTypeDef],
         "Documents": List[DocumentMetadataTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InitiateDocumentVersionUploadResponseTypeDef = TypedDict(
     "InitiateDocumentVersionUploadResponseTypeDef",
     {
         "Metadata": DocumentMetadataTypeDef,
         "UploadMetadata": UploadMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SearchResourcesRequestRequestTypeDef = TypedDict(
+    "SearchResourcesRequestRequestTypeDef",
+    {
+        "AuthenticationToken": str,
+        "QueryText": str,
+        "QueryScopes": Sequence[SearchQueryScopeTypeType],
+        "OrganizationId": str,
+        "AdditionalResponseFields": Sequence[Literal["WEBURL"]],
+        "Filters": FiltersTypeDef,
+        "OrderBy": Sequence[SearchSortResultTypeDef],
+        "Limit": int,
+        "Marker": str,
+    },
+    total=False,
+)
+
+SearchResourcesRequestSearchResourcesPaginateTypeDef = TypedDict(
+    "SearchResourcesRequestSearchResourcesPaginateTypeDef",
+    {
+        "AuthenticationToken": str,
+        "QueryText": str,
+        "QueryScopes": Sequence[SearchQueryScopeTypeType],
+        "OrganizationId": str,
+        "AdditionalResponseFields": Sequence[Literal["WEBURL"]],
+        "Filters": FiltersTypeDef,
+        "OrderBy": Sequence[SearchSortResultTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
 DescribeResourcePermissionsResponseTypeDef = TypedDict(
     "DescribeResourcePermissionsResponseTypeDef",
     {
         "Principals": List[PrincipalTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDocumentPathResponseTypeDef = TypedDict(
     "GetDocumentPathResponseTypeDef",
     {
         "Path": ResourcePathTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFolderPathResponseTypeDef = TypedDict(
     "GetFolderPathResponseTypeDef",
     {
         "Path": ResourcePathTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActivateUserResponseTypeDef = TypedDict(
     "ActivateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CommentMetadataTypeDef = TypedDict(
     "CommentMetadataTypeDef",
     {
         "CommentId": str,
         "Contributor": UserTypeDef,
         "CreatedTimestamp": datetime,
         "CommentStatus": CommentStatusTypeType,
         "RecipientId": str,
+        "ContributorId": str,
     },
     total=False,
 )
 
 _RequiredCommentTypeDef = TypedDict(
     "_RequiredCommentTypeDef",
     {
@@ -1640,41 +1753,41 @@
 class CommentTypeDef(_RequiredCommentTypeDef, _OptionalCommentTypeDef):
     pass
 
 CreateUserResponseTypeDef = TypedDict(
     "CreateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUsersResponseTypeDef = TypedDict(
     "DescribeUsersResponseTypeDef",
     {
         "Users": List[UserTypeDef],
         "TotalNumberOfUsers": int,
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCurrentUserResponseTypeDef = TypedDict(
     "GetCurrentUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUserResponseTypeDef = TypedDict(
     "UpdateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActivityTypeDef = TypedDict(
     "ActivityTypeDef",
     {
         "Type": ActivityTypeType,
@@ -1686,32 +1799,54 @@
         "ResourceMetadata": ResourceMetadataTypeDef,
         "OriginalParent": ResourceMetadataTypeDef,
         "CommentMetadata": CommentMetadataTypeDef,
     },
     total=False,
 )
 
+ResponseItemTypeDef = TypedDict(
+    "ResponseItemTypeDef",
+    {
+        "ResourceType": ResponseItemTypeType,
+        "WebUrl": str,
+        "DocumentMetadata": DocumentMetadataTypeDef,
+        "FolderMetadata": FolderMetadataTypeDef,
+        "CommentMetadata": CommentMetadataTypeDef,
+        "DocumentVersionMetadata": DocumentVersionMetadataTypeDef,
+    },
+    total=False,
+)
+
 CreateCommentResponseTypeDef = TypedDict(
     "CreateCommentResponseTypeDef",
     {
         "Comment": CommentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCommentsResponseTypeDef = TypedDict(
     "DescribeCommentsResponseTypeDef",
     {
         "Comments": List[CommentTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeActivitiesResponseTypeDef = TypedDict(
     "DescribeActivitiesResponseTypeDef",
     {
         "UserActivities": List[ActivityTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SearchResourcesResponseTypeDef = TypedDict(
+    "SearchResourcesResponseTypeDef",
+    {
+        "Items": List[ResponseItemTypeDef],
+        "Marker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs.egg-info/PKG-INFO` & `types-aiobotocore-workdocs-2.5.1/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-workdocs
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.WorkDocs 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore workdocs type-annotations boto3-stubs mypy typeshed autocomplete
-Classifier: Development Status :: 5 - Production/Stable
-Classifier: Intended Audience :: Developers
-Classifier: Environment :: Console
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Natural Language :: English
-Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: 3.12
-Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: Implementation :: CPython
-Classifier: Typing :: Typed
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 <a id="types-aiobotocore-workdocs"></a>
 
 # types-aiobotocore-workdocs
 
 [![PyPI - types-aiobotocore-workdocs](https://img.shields.io/pypi/v/types-aiobotocore-workdocs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workdocs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-workdocs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-workdocs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-workdocs?color=blue)](https://pypistats.org/packages/types-aiobotocore-workdocs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WorkDocs 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs)
+[aiobotocore.WorkDocs 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/workdocs.html#WorkDocs)
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
 [types-aiobotocore-workdocs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_workdocs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -281,14 +248,15 @@
     DescribeDocumentVersionsPaginator,
     DescribeFolderContentsPaginator,
     DescribeGroupsPaginator,
     DescribeNotificationSubscriptionsPaginator,
     DescribeResourcePermissionsPaginator,
     DescribeRootFoldersPaginator,
     DescribeUsersPaginator,
+    SearchResourcesPaginator,
 )
 
 session = get_session()
 async with session.create_client("workdocs") as client:
     client: WorkDocsClient
 
     # Explicit type annotations are optional here
@@ -312,53 +280,65 @@
     describe_resource_permissions_paginator: DescribeResourcePermissionsPaginator = (
         client.get_paginator("describe_resource_permissions")
     )
     describe_root_folders_paginator: DescribeRootFoldersPaginator = client.get_paginator(
         "describe_root_folders"
     )
     describe_users_paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
+    search_resources_paginator: SearchResourcesPaginator = client.get_paginator("search_resources")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_workdocs.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_workdocs.literals import (
     ActivityTypeType,
+    AdditionalResponseFieldTypeType,
     BooleanEnumTypeType,
     CommentStatusTypeType,
     CommentVisibilityTypeType,
+    ContentCategoryTypeType,
     DescribeActivitiesPaginatorName,
     DescribeCommentsPaginatorName,
     DescribeDocumentVersionsPaginatorName,
     DescribeFolderContentsPaginatorName,
     DescribeGroupsPaginatorName,
     DescribeNotificationSubscriptionsPaginatorName,
     DescribeResourcePermissionsPaginatorName,
     DescribeRootFoldersPaginatorName,
     DescribeUsersPaginatorName,
     DocumentSourceTypeType,
     DocumentStatusTypeType,
     DocumentThumbnailTypeType,
     DocumentVersionStatusType,
     FolderContentTypeType,
+    LanguageCodeTypeType,
     LocaleTypeType,
+    OrderByFieldTypeType,
     OrderTypeType,
+    PrincipalRoleTypeType,
     PrincipalTypeType,
     ResourceCollectionTypeType,
     ResourceSortTypeType,
     ResourceStateTypeType,
     ResourceTypeType,
+    ResponseItemTypeType,
     RolePermissionTypeType,
     RoleTypeType,
+    SearchCollectionTypeType,
+    SearchQueryScopeTypeType,
+    SearchResourceTypeType,
+    SearchResourcesPaginatorName,
     ShareStatusTypeType,
+    SortOrderType,
     StorageTypeType,
     SubscriptionProtocolTypeType,
     SubscriptionTypeType,
     UserFilterTypeType,
     UserSortTypeType,
     UserStatusTypeType,
     UserTypeType,
@@ -381,156 +361,165 @@
 `types_aiobotocore_workdocs.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_workdocs.type_defs import (
     AbortDocumentVersionUploadRequestRequestTypeDef,
     ActivateUserRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     UserMetadataTypeDef,
     NotificationOptionsTypeDef,
     SharePrincipalTypeDef,
     ShareResultTypeDef,
     CreateCommentRequestRequestTypeDef,
     CreateCustomMetadataRequestRequestTypeDef,
     CreateFolderRequestRequestTypeDef,
     FolderMetadataTypeDef,
     CreateLabelsRequestRequestTypeDef,
     CreateNotificationSubscriptionRequestRequestTypeDef,
     SubscriptionTypeDef,
     StorageRuleTypeTypeDef,
+    DateRangeTypeTypeDef,
     DeactivateUserRequestRequestTypeDef,
     DeleteCommentRequestRequestTypeDef,
     DeleteCustomMetadataRequestRequestTypeDef,
     DeleteDocumentRequestRequestTypeDef,
     DeleteDocumentVersionRequestRequestTypeDef,
     DeleteFolderContentsRequestRequestTypeDef,
     DeleteFolderRequestRequestTypeDef,
     DeleteLabelsRequestRequestTypeDef,
     DeleteNotificationSubscriptionRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef,
     DescribeActivitiesRequestRequestTypeDef,
+    DescribeCommentsRequestDescribeCommentsPaginateTypeDef,
     DescribeCommentsRequestRequestTypeDef,
+    DescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef,
     DescribeDocumentVersionsRequestRequestTypeDef,
     DocumentVersionMetadataTypeDef,
+    DescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef,
     DescribeFolderContentsRequestRequestTypeDef,
+    DescribeGroupsRequestDescribeGroupsPaginateTypeDef,
     DescribeGroupsRequestRequestTypeDef,
     GroupMetadataTypeDef,
+    DescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef,
     DescribeNotificationSubscriptionsRequestRequestTypeDef,
+    DescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef,
     DescribeResourcePermissionsRequestRequestTypeDef,
+    DescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef,
     DescribeRootFoldersRequestRequestTypeDef,
+    DescribeUsersRequestDescribeUsersPaginateTypeDef,
     DescribeUsersRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
+    LongRangeTypeTypeDef,
+    SearchPrincipalTypeTypeDef,
     GetCurrentUserRequestRequestTypeDef,
     GetDocumentPathRequestRequestTypeDef,
     GetDocumentRequestRequestTypeDef,
     GetDocumentVersionRequestRequestTypeDef,
     GetFolderPathRequestRequestTypeDef,
     GetFolderRequestRequestTypeDef,
     GetResourcesRequestRequestTypeDef,
     InitiateDocumentVersionUploadRequestRequestTypeDef,
     UploadMetadataTypeDef,
+    PaginatorConfigTypeDef,
     PermissionInfoTypeDef,
     RemoveAllResourcePermissionsRequestRequestTypeDef,
     RemoveResourcePermissionRequestRequestTypeDef,
     ResourcePathComponentTypeDef,
+    ResponseMetadataTypeDef,
     RestoreDocumentVersionsRequestRequestTypeDef,
+    SearchSortResultTypeDef,
     UpdateDocumentRequestRequestTypeDef,
     UpdateDocumentVersionRequestRequestTypeDef,
     UpdateFolderRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
     ResourceMetadataTypeDef,
     AddResourcePermissionsRequestRequestTypeDef,
     AddResourcePermissionsResponseTypeDef,
     CreateFolderResponseTypeDef,
     DescribeRootFoldersResponseTypeDef,
     GetFolderResponseTypeDef,
     CreateNotificationSubscriptionResponseTypeDef,
     DescribeNotificationSubscriptionsResponseTypeDef,
     CreateUserRequestRequestTypeDef,
     UpdateUserRequestRequestTypeDef,
     UserStorageMetadataTypeDef,
-    DescribeActivitiesRequestDescribeActivitiesPaginateTypeDef,
-    DescribeCommentsRequestDescribeCommentsPaginateTypeDef,
-    DescribeDocumentVersionsRequestDescribeDocumentVersionsPaginateTypeDef,
-    DescribeFolderContentsRequestDescribeFolderContentsPaginateTypeDef,
-    DescribeGroupsRequestDescribeGroupsPaginateTypeDef,
-    DescribeNotificationSubscriptionsRequestDescribeNotificationSubscriptionsPaginateTypeDef,
-    DescribeResourcePermissionsRequestDescribeResourcePermissionsPaginateTypeDef,
-    DescribeRootFoldersRequestDescribeRootFoldersPaginateTypeDef,
-    DescribeUsersRequestDescribeUsersPaginateTypeDef,
     DescribeDocumentVersionsResponseTypeDef,
     DocumentMetadataTypeDef,
     GetDocumentVersionResponseTypeDef,
     DescribeGroupsResponseTypeDef,
     ParticipantsTypeDef,
+    FiltersTypeDef,
     PrincipalTypeDef,
     ResourcePathTypeDef,
     UserTypeDef,
     DescribeFolderContentsResponseTypeDef,
     GetDocumentResponseTypeDef,
     GetResourcesResponseTypeDef,
     InitiateDocumentVersionUploadResponseTypeDef,
+    SearchResourcesRequestRequestTypeDef,
+    SearchResourcesRequestSearchResourcesPaginateTypeDef,
     DescribeResourcePermissionsResponseTypeDef,
     GetDocumentPathResponseTypeDef,
     GetFolderPathResponseTypeDef,
     ActivateUserResponseTypeDef,
     CommentMetadataTypeDef,
     CommentTypeDef,
     CreateUserResponseTypeDef,
     DescribeUsersResponseTypeDef,
     GetCurrentUserResponseTypeDef,
     UpdateUserResponseTypeDef,
     ActivityTypeDef,
+    ResponseItemTypeDef,
     CreateCommentResponseTypeDef,
     DescribeCommentsResponseTypeDef,
     DescribeActivitiesResponseTypeDef,
+    SearchResourcesResponseTypeDef,
 )
 
 
 def get_structure() -> AbortDocumentVersionUploadRequestRequestTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-workdocs-2.5.0.post1/types_aiobotocore_workdocs.egg-info/SOURCES.txt` & `types-aiobotocore-workdocs-2.5.1/types_aiobotocore_workdocs.egg-info/SOURCES.txt`

 * *Files identical despite different names*


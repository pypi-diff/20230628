# Comparing `tmp/types-aiobotocore-clouddirectory-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-clouddirectory-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-clouddirectory-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:19 2023, max compression
+gzip compressed data, was "types-aiobotocore-clouddirectory-2.5.1.tar", last modified: Wed Jun 28 01:43:13 2023, max compression
```

## Comparing `types-aiobotocore-clouddirectory-2.5.0.post1.tar` & `types-aiobotocore-clouddirectory-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.851023 types-aiobotocore-clouddirectory-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:39.000000 types-aiobotocore-clouddirectory-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    26376 2023-03-11 12:26:19.851023 types-aiobotocore-clouddirectory-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    24777 2023-03-11 12:10:39.000000 types-aiobotocore-clouddirectory-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:19.851023 types-aiobotocore-clouddirectory-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-03-11 12:10:39.000000 types-aiobotocore-clouddirectory-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.851023 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/
--rw-r--r--   0 runner    (1001) docker     (123)     4839 2023-03-11 12:10:39.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4838 2023-03-11 12:10:39.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-03-11 12:10:39.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    59763 2023-03-11 12:10:39.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    59669 2023-03-11 12:10:39.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11668 2023-03-11 12:10:39.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11666 2023-03-11 12:10:39.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    25445 2023-03-11 12:10:39.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    25423 2023-03-11 12:10:39.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:39.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    86378 2023-03-11 12:10:42.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    86251 2023-03-11 12:10:41.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:39.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.851023 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    26376 2023-03-11 12:26:19.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:26:19.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:19.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:26:19.000000 types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.290107 types-aiobotocore-clouddirectory-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:16.000000 types-aiobotocore-clouddirectory-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    26375 2023-06-28 01:43:13.290107 types-aiobotocore-clouddirectory-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    24782 2023-06-28 01:27:16.000000 types-aiobotocore-clouddirectory-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:13.290107 types-aiobotocore-clouddirectory-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-28 01:27:16.000000 types-aiobotocore-clouddirectory-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.286107 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/
+-rw-r--r--   0 runner    (1001) docker     (123)     4839 2023-06-28 01:27:16.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4838 2023-06-28 01:27:16.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      959 2023-06-28 01:27:16.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    59759 2023-06-28 01:27:16.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    59665 2023-06-28 01:27:16.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11877 2023-06-28 01:27:17.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11875 2023-06-28 01:27:17.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    25363 2023-06-28 01:27:17.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25342 2023-06-28 01:27:17.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:16.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    86520 2023-06-28 01:27:19.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    86393 2023-06-28 01:27:18.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:16.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.290107 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    26375 2023-06-28 01:43:13.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:43:13.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:13.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:43:13.000000 types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/LICENSE` & `types-aiobotocore-clouddirectory-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/PKG-INFO` & `types-aiobotocore-clouddirectory-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-clouddirectory
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudDirectory 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudDirectory 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-clouddirectory"></a>
 
 # types-aiobotocore-clouddirectory
 
 [![PyPI - types-aiobotocore-clouddirectory](https://img.shields.io/pypi/v/types-aiobotocore-clouddirectory.svg?color=blue)](https://pypi.org/project/types-aiobotocore-clouddirectory)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-clouddirectory.svg?color=blue)](https://pypi.org/project/types-aiobotocore-clouddirectory)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-clouddirectory?color=blue)](https://pypistats.org/packages/types-aiobotocore-clouddirectory)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudDirectory 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory)
+[aiobotocore.CloudDirectory 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory)
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
 [types-aiobotocore-clouddirectory docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/).
 
 See how it helps to find and fix potential bugs:
 
@@ -413,15 +413,17 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_clouddirectory.type_defs import (
     ObjectReferenceTypeDef,
     SchemaFacetTypeDef,
     ApplySchemaRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    ApplySchemaResponseTypeDef,
+    AttachObjectResponseTypeDef,
+    AttachToIndexResponseTypeDef,
     TypedLinkSchemaAndFacetNameTypeDef,
     AttributeKeyTypeDef,
     TypedAttributeValueTypeDef,
     BatchAttachObjectResponseTypeDef,
     BatchAttachToIndexResponseTypeDef,
     BatchCreateIndexResponseTypeDef,
     BatchCreateObjectResponseTypeDef,
@@ -431,49 +433,89 @@
     PathToObjectIdentifiersTypeDef,
     ObjectIdentifierAndLinkNameTupleTypeDef,
     BatchListObjectPoliciesResponseTypeDef,
     BatchListPolicyAttachmentsResponseTypeDef,
     BatchReadExceptionTypeDef,
     BatchUpdateObjectAttributesResponseTypeDef,
     CreateDirectoryRequestRequestTypeDef,
+    CreateDirectoryResponseTypeDef,
+    CreateIndexResponseTypeDef,
+    CreateObjectResponseTypeDef,
     CreateSchemaRequestRequestTypeDef,
+    CreateSchemaResponseTypeDef,
     DeleteDirectoryRequestRequestTypeDef,
+    DeleteDirectoryResponseTypeDef,
     DeleteFacetRequestRequestTypeDef,
     DeleteSchemaRequestRequestTypeDef,
+    DeleteSchemaResponseTypeDef,
     DeleteTypedLinkFacetRequestRequestTypeDef,
+    DetachFromIndexResponseTypeDef,
+    DetachObjectResponseTypeDef,
     DirectoryTypeDef,
     DisableDirectoryRequestRequestTypeDef,
+    DisableDirectoryResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableDirectoryRequestRequestTypeDef,
+    EnableDirectoryResponseTypeDef,
     RuleTypeDef,
     FacetAttributeReferenceTypeDef,
     FacetTypeDef,
     GetAppliedSchemaVersionRequestRequestTypeDef,
+    GetAppliedSchemaVersionResponseTypeDef,
     GetDirectoryRequestRequestTypeDef,
     GetFacetRequestRequestTypeDef,
     GetSchemaAsJsonRequestRequestTypeDef,
+    GetSchemaAsJsonResponseTypeDef,
     GetTypedLinkFacetInformationRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetTypedLinkFacetInformationResponseTypeDef,
+    ListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef,
     ListAppliedSchemaArnsRequestRequestTypeDef,
+    ListAppliedSchemaArnsResponseTypeDef,
+    ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef,
     ListDevelopmentSchemaArnsRequestRequestTypeDef,
+    ListDevelopmentSchemaArnsResponseTypeDef,
+    ListDirectoriesRequestListDirectoriesPaginateTypeDef,
     ListDirectoriesRequestRequestTypeDef,
+    ListFacetAttributesRequestListFacetAttributesPaginateTypeDef,
     ListFacetAttributesRequestRequestTypeDef,
+    ListFacetNamesRequestListFacetNamesPaginateTypeDef,
     ListFacetNamesRequestRequestTypeDef,
+    ListFacetNamesResponseTypeDef,
+    ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef,
     ListManagedSchemaArnsRequestRequestTypeDef,
+    ListManagedSchemaArnsResponseTypeDef,
+    ListObjectChildrenResponseTypeDef,
+    ListObjectPoliciesResponseTypeDef,
+    ListPolicyAttachmentsResponseTypeDef,
+    ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef,
     ListPublishedSchemaArnsRequestRequestTypeDef,
+    ListPublishedSchemaArnsResponseTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
+    ListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef,
     ListTypedLinkFacetAttributesRequestRequestTypeDef,
+    ListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef,
     ListTypedLinkFacetNamesRequestRequestTypeDef,
+    ListTypedLinkFacetNamesResponseTypeDef,
+    PaginatorConfigTypeDef,
     PolicyAttachmentTypeDef,
     PublishSchemaRequestRequestTypeDef,
+    PublishSchemaResponseTypeDef,
     PutSchemaFromJsonRequestRequestTypeDef,
+    PutSchemaFromJsonResponseTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateObjectAttributesResponseTypeDef,
     UpdateSchemaRequestRequestTypeDef,
+    UpdateSchemaResponseTypeDef,
     UpgradeAppliedSchemaRequestRequestTypeDef,
+    UpgradeAppliedSchemaResponseTypeDef,
     UpgradePublishedSchemaRequestRequestTypeDef,
+    UpgradePublishedSchemaResponseTypeDef,
     AttachObjectRequestRequestTypeDef,
     AttachPolicyRequestRequestTypeDef,
     AttachToIndexRequestRequestTypeDef,
     BatchAttachObjectTypeDef,
     BatchAttachPolicyTypeDef,
     BatchAttachToIndexTypeDef,
     BatchDeleteObjectTypeDef,
@@ -489,61 +531,35 @@
     BatchListPolicyAttachmentsTypeDef,
     BatchLookupPolicyTypeDef,
     DeleteObjectRequestRequestTypeDef,
     DetachFromIndexRequestRequestTypeDef,
     DetachObjectRequestRequestTypeDef,
     DetachPolicyRequestRequestTypeDef,
     GetObjectInformationRequestRequestTypeDef,
+    ListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef,
     ListAttachedIndicesRequestRequestTypeDef,
     ListObjectChildrenRequestRequestTypeDef,
+    ListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef,
     ListObjectParentPathsRequestRequestTypeDef,
     ListObjectParentsRequestRequestTypeDef,
+    ListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef,
     ListObjectPoliciesRequestRequestTypeDef,
+    ListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef,
     ListPolicyAttachmentsRequestRequestTypeDef,
+    LookupPolicyRequestLookupPolicyPaginateTypeDef,
     LookupPolicyRequestRequestTypeDef,
     BatchGetObjectAttributesTypeDef,
     BatchGetObjectInformationResponseTypeDef,
     BatchListObjectAttributesTypeDef,
     BatchRemoveFacetFromObjectTypeDef,
     GetObjectAttributesRequestRequestTypeDef,
+    GetObjectInformationResponseTypeDef,
+    ListObjectAttributesRequestListObjectAttributesPaginateTypeDef,
     ListObjectAttributesRequestRequestTypeDef,
     RemoveFacetFromObjectRequestRequestTypeDef,
-    ApplySchemaResponseTypeDef,
-    AttachObjectResponseTypeDef,
-    AttachToIndexResponseTypeDef,
-    CreateDirectoryResponseTypeDef,
-    CreateIndexResponseTypeDef,
-    CreateObjectResponseTypeDef,
-    CreateSchemaResponseTypeDef,
-    DeleteDirectoryResponseTypeDef,
-    DeleteSchemaResponseTypeDef,
-    DetachFromIndexResponseTypeDef,
-    DetachObjectResponseTypeDef,
-    DisableDirectoryResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EnableDirectoryResponseTypeDef,
-    GetAppliedSchemaVersionResponseTypeDef,
-    GetObjectInformationResponseTypeDef,
-    GetSchemaAsJsonResponseTypeDef,
-    GetTypedLinkFacetInformationResponseTypeDef,
-    ListAppliedSchemaArnsResponseTypeDef,
-    ListDevelopmentSchemaArnsResponseTypeDef,
-    ListFacetNamesResponseTypeDef,
-    ListManagedSchemaArnsResponseTypeDef,
-    ListObjectChildrenResponseTypeDef,
-    ListObjectPoliciesResponseTypeDef,
-    ListPolicyAttachmentsResponseTypeDef,
-    ListPublishedSchemaArnsResponseTypeDef,
-    ListTypedLinkFacetNamesResponseTypeDef,
-    PublishSchemaResponseTypeDef,
-    PutSchemaFromJsonResponseTypeDef,
-    UpdateObjectAttributesResponseTypeDef,
-    UpdateSchemaResponseTypeDef,
-    UpgradeAppliedSchemaResponseTypeDef,
-    UpgradePublishedSchemaResponseTypeDef,
     BatchCreateIndexTypeDef,
     CreateIndexRequestRequestTypeDef,
     AttributeKeyAndValueTypeDef,
     AttributeNameAndValueTypeDef,
     LinkAttributeActionTypeDef,
     ObjectAttributeActionTypeDef,
     TypedAttributeValueRangeTypeDef,
@@ -552,30 +568,14 @@
     BatchListObjectParentsResponseTypeDef,
     ListObjectParentsResponseTypeDef,
     GetDirectoryResponseTypeDef,
     ListDirectoriesResponseTypeDef,
     FacetAttributeDefinitionTypeDef,
     TypedLinkAttributeDefinitionTypeDef,
     GetFacetResponseTypeDef,
-    ListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef,
-    ListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef,
-    ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef,
-    ListDirectoriesRequestListDirectoriesPaginateTypeDef,
-    ListFacetAttributesRequestListFacetAttributesPaginateTypeDef,
-    ListFacetNamesRequestListFacetNamesPaginateTypeDef,
-    ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef,
-    ListObjectAttributesRequestListObjectAttributesPaginateTypeDef,
-    ListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef,
-    ListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef,
-    ListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef,
-    ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    ListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef,
-    ListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef,
-    LookupPolicyRequestLookupPolicyPaginateTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     PolicyToPathTypeDef,
     AddFacetToObjectRequestRequestTypeDef,
     BatchAddFacetToObjectTypeDef,
     BatchCreateObjectTypeDef,
     BatchGetLinkAttributesResponseTypeDef,
@@ -651,43 +651,43 @@
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

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/README.md` & `types-aiobotocore-clouddirectory-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-clouddirectory"></a>
 
 # types-aiobotocore-clouddirectory
 
 [![PyPI - types-aiobotocore-clouddirectory](https://img.shields.io/pypi/v/types-aiobotocore-clouddirectory.svg?color=blue)](https://pypi.org/project/types-aiobotocore-clouddirectory)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-clouddirectory.svg?color=blue)](https://pypi.org/project/types-aiobotocore-clouddirectory)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-clouddirectory?color=blue)](https://pypistats.org/packages/types-aiobotocore-clouddirectory)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudDirectory 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory)
+[aiobotocore.CloudDirectory 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory)
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
 [types-aiobotocore-clouddirectory docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/).
 
 See how it helps to find and fix potential bugs:
 
@@ -380,15 +380,17 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_clouddirectory.type_defs import (
     ObjectReferenceTypeDef,
     SchemaFacetTypeDef,
     ApplySchemaRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    ApplySchemaResponseTypeDef,
+    AttachObjectResponseTypeDef,
+    AttachToIndexResponseTypeDef,
     TypedLinkSchemaAndFacetNameTypeDef,
     AttributeKeyTypeDef,
     TypedAttributeValueTypeDef,
     BatchAttachObjectResponseTypeDef,
     BatchAttachToIndexResponseTypeDef,
     BatchCreateIndexResponseTypeDef,
     BatchCreateObjectResponseTypeDef,
@@ -398,49 +400,89 @@
     PathToObjectIdentifiersTypeDef,
     ObjectIdentifierAndLinkNameTupleTypeDef,
     BatchListObjectPoliciesResponseTypeDef,
     BatchListPolicyAttachmentsResponseTypeDef,
     BatchReadExceptionTypeDef,
     BatchUpdateObjectAttributesResponseTypeDef,
     CreateDirectoryRequestRequestTypeDef,
+    CreateDirectoryResponseTypeDef,
+    CreateIndexResponseTypeDef,
+    CreateObjectResponseTypeDef,
     CreateSchemaRequestRequestTypeDef,
+    CreateSchemaResponseTypeDef,
     DeleteDirectoryRequestRequestTypeDef,
+    DeleteDirectoryResponseTypeDef,
     DeleteFacetRequestRequestTypeDef,
     DeleteSchemaRequestRequestTypeDef,
+    DeleteSchemaResponseTypeDef,
     DeleteTypedLinkFacetRequestRequestTypeDef,
+    DetachFromIndexResponseTypeDef,
+    DetachObjectResponseTypeDef,
     DirectoryTypeDef,
     DisableDirectoryRequestRequestTypeDef,
+    DisableDirectoryResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableDirectoryRequestRequestTypeDef,
+    EnableDirectoryResponseTypeDef,
     RuleTypeDef,
     FacetAttributeReferenceTypeDef,
     FacetTypeDef,
     GetAppliedSchemaVersionRequestRequestTypeDef,
+    GetAppliedSchemaVersionResponseTypeDef,
     GetDirectoryRequestRequestTypeDef,
     GetFacetRequestRequestTypeDef,
     GetSchemaAsJsonRequestRequestTypeDef,
+    GetSchemaAsJsonResponseTypeDef,
     GetTypedLinkFacetInformationRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetTypedLinkFacetInformationResponseTypeDef,
+    ListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef,
     ListAppliedSchemaArnsRequestRequestTypeDef,
+    ListAppliedSchemaArnsResponseTypeDef,
+    ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef,
     ListDevelopmentSchemaArnsRequestRequestTypeDef,
+    ListDevelopmentSchemaArnsResponseTypeDef,
+    ListDirectoriesRequestListDirectoriesPaginateTypeDef,
     ListDirectoriesRequestRequestTypeDef,
+    ListFacetAttributesRequestListFacetAttributesPaginateTypeDef,
     ListFacetAttributesRequestRequestTypeDef,
+    ListFacetNamesRequestListFacetNamesPaginateTypeDef,
     ListFacetNamesRequestRequestTypeDef,
+    ListFacetNamesResponseTypeDef,
+    ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef,
     ListManagedSchemaArnsRequestRequestTypeDef,
+    ListManagedSchemaArnsResponseTypeDef,
+    ListObjectChildrenResponseTypeDef,
+    ListObjectPoliciesResponseTypeDef,
+    ListPolicyAttachmentsResponseTypeDef,
+    ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef,
     ListPublishedSchemaArnsRequestRequestTypeDef,
+    ListPublishedSchemaArnsResponseTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
+    ListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef,
     ListTypedLinkFacetAttributesRequestRequestTypeDef,
+    ListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef,
     ListTypedLinkFacetNamesRequestRequestTypeDef,
+    ListTypedLinkFacetNamesResponseTypeDef,
+    PaginatorConfigTypeDef,
     PolicyAttachmentTypeDef,
     PublishSchemaRequestRequestTypeDef,
+    PublishSchemaResponseTypeDef,
     PutSchemaFromJsonRequestRequestTypeDef,
+    PutSchemaFromJsonResponseTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateObjectAttributesResponseTypeDef,
     UpdateSchemaRequestRequestTypeDef,
+    UpdateSchemaResponseTypeDef,
     UpgradeAppliedSchemaRequestRequestTypeDef,
+    UpgradeAppliedSchemaResponseTypeDef,
     UpgradePublishedSchemaRequestRequestTypeDef,
+    UpgradePublishedSchemaResponseTypeDef,
     AttachObjectRequestRequestTypeDef,
     AttachPolicyRequestRequestTypeDef,
     AttachToIndexRequestRequestTypeDef,
     BatchAttachObjectTypeDef,
     BatchAttachPolicyTypeDef,
     BatchAttachToIndexTypeDef,
     BatchDeleteObjectTypeDef,
@@ -456,61 +498,35 @@
     BatchListPolicyAttachmentsTypeDef,
     BatchLookupPolicyTypeDef,
     DeleteObjectRequestRequestTypeDef,
     DetachFromIndexRequestRequestTypeDef,
     DetachObjectRequestRequestTypeDef,
     DetachPolicyRequestRequestTypeDef,
     GetObjectInformationRequestRequestTypeDef,
+    ListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef,
     ListAttachedIndicesRequestRequestTypeDef,
     ListObjectChildrenRequestRequestTypeDef,
+    ListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef,
     ListObjectParentPathsRequestRequestTypeDef,
     ListObjectParentsRequestRequestTypeDef,
+    ListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef,
     ListObjectPoliciesRequestRequestTypeDef,
+    ListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef,
     ListPolicyAttachmentsRequestRequestTypeDef,
+    LookupPolicyRequestLookupPolicyPaginateTypeDef,
     LookupPolicyRequestRequestTypeDef,
     BatchGetObjectAttributesTypeDef,
     BatchGetObjectInformationResponseTypeDef,
     BatchListObjectAttributesTypeDef,
     BatchRemoveFacetFromObjectTypeDef,
     GetObjectAttributesRequestRequestTypeDef,
+    GetObjectInformationResponseTypeDef,
+    ListObjectAttributesRequestListObjectAttributesPaginateTypeDef,
     ListObjectAttributesRequestRequestTypeDef,
     RemoveFacetFromObjectRequestRequestTypeDef,
-    ApplySchemaResponseTypeDef,
-    AttachObjectResponseTypeDef,
-    AttachToIndexResponseTypeDef,
-    CreateDirectoryResponseTypeDef,
-    CreateIndexResponseTypeDef,
-    CreateObjectResponseTypeDef,
-    CreateSchemaResponseTypeDef,
-    DeleteDirectoryResponseTypeDef,
-    DeleteSchemaResponseTypeDef,
-    DetachFromIndexResponseTypeDef,
-    DetachObjectResponseTypeDef,
-    DisableDirectoryResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EnableDirectoryResponseTypeDef,
-    GetAppliedSchemaVersionResponseTypeDef,
-    GetObjectInformationResponseTypeDef,
-    GetSchemaAsJsonResponseTypeDef,
-    GetTypedLinkFacetInformationResponseTypeDef,
-    ListAppliedSchemaArnsResponseTypeDef,
-    ListDevelopmentSchemaArnsResponseTypeDef,
-    ListFacetNamesResponseTypeDef,
-    ListManagedSchemaArnsResponseTypeDef,
-    ListObjectChildrenResponseTypeDef,
-    ListObjectPoliciesResponseTypeDef,
-    ListPolicyAttachmentsResponseTypeDef,
-    ListPublishedSchemaArnsResponseTypeDef,
-    ListTypedLinkFacetNamesResponseTypeDef,
-    PublishSchemaResponseTypeDef,
-    PutSchemaFromJsonResponseTypeDef,
-    UpdateObjectAttributesResponseTypeDef,
-    UpdateSchemaResponseTypeDef,
-    UpgradeAppliedSchemaResponseTypeDef,
-    UpgradePublishedSchemaResponseTypeDef,
     BatchCreateIndexTypeDef,
     CreateIndexRequestRequestTypeDef,
     AttributeKeyAndValueTypeDef,
     AttributeNameAndValueTypeDef,
     LinkAttributeActionTypeDef,
     ObjectAttributeActionTypeDef,
     TypedAttributeValueRangeTypeDef,
@@ -519,30 +535,14 @@
     BatchListObjectParentsResponseTypeDef,
     ListObjectParentsResponseTypeDef,
     GetDirectoryResponseTypeDef,
     ListDirectoriesResponseTypeDef,
     FacetAttributeDefinitionTypeDef,
     TypedLinkAttributeDefinitionTypeDef,
     GetFacetResponseTypeDef,
-    ListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef,
-    ListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef,
-    ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef,
-    ListDirectoriesRequestListDirectoriesPaginateTypeDef,
-    ListFacetAttributesRequestListFacetAttributesPaginateTypeDef,
-    ListFacetNamesRequestListFacetNamesPaginateTypeDef,
-    ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef,
-    ListObjectAttributesRequestListObjectAttributesPaginateTypeDef,
-    ListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef,
-    ListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef,
-    ListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef,
-    ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    ListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef,
-    ListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef,
-    LookupPolicyRequestLookupPolicyPaginateTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     PolicyToPathTypeDef,
     AddFacetToObjectRequestRequestTypeDef,
     BatchAddFacetToObjectTypeDef,
     BatchCreateObjectTypeDef,
     BatchGetLinkAttributesResponseTypeDef,
@@ -618,43 +618,43 @@
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

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/setup.py` & `types-aiobotocore-clouddirectory-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-clouddirectory.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-clouddirectory",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_clouddirectory"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CloudDirectory 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CloudDirectory 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/"
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

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/__init__.py` & `types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/__init__.pyi` & `types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/__main__.py` & `types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CloudDirectory 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CloudDirectory 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory\nOther"
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

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/client.py` & `types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -525,15 +525,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Client.get_directory)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/client/#get_directory)
         """
 
     async def get_facet(self, *, SchemaArn: str, Name: str) -> GetFacetResponseTypeDef:
         """
-        Gets details of the  Facet, such as facet name, attributes,  Rule s, or
+        Gets details of the  Facet, such as facet name, attributes,  Rules, or
         `ObjectType`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Client.get_facet)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/client/#get_facet)
         """
 
     async def get_link_attributes(
@@ -947,15 +947,15 @@
         *,
         SchemaArn: str,
         Name: str,
         AttributeUpdates: Sequence[FacetAttributeUpdateTypeDef] = ...,
         ObjectType: ObjectTypeType = ...
     ) -> Dict[str, Any]:
         """
-        Does the following * Adds new `Attributes` , `Rules` , or `ObjectTypes` .
+        Does the following: * Adds new `Attributes`, `Rules`, or `ObjectTypes`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Client.update_facet)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/client/#update_facet)
         """
 
     async def update_link_attributes(
         self,
@@ -1025,15 +1025,15 @@
         DevelopmentSchemaArn: str,
         PublishedSchemaArn: str,
         MinorVersion: str,
         DryRun: bool = ...
     ) -> UpgradePublishedSchemaResponseTypeDef:
         """
         Upgrades a published schema under a new minor version revision using the current
-        contents of `DevelopmentSchemaArn` .
+        contents of `DevelopmentSchemaArn`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Client.upgrade_published_schema)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/client/#upgrade_published_schema)
         """
 
     @overload
     def get_paginator(
```

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/client.pyi` & `types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -490,15 +490,15 @@
         Retrieves metadata about a directory.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Client.get_directory)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/client/#get_directory)
         """
     async def get_facet(self, *, SchemaArn: str, Name: str) -> GetFacetResponseTypeDef:
         """
-        Gets details of the  Facet, such as facet name, attributes,  Rule s, or
+        Gets details of the  Facet, such as facet name, attributes,  Rules, or
         `ObjectType`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Client.get_facet)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/client/#get_facet)
         """
     async def get_link_attributes(
         self,
@@ -880,15 +880,15 @@
         *,
         SchemaArn: str,
         Name: str,
         AttributeUpdates: Sequence[FacetAttributeUpdateTypeDef] = ...,
         ObjectType: ObjectTypeType = ...
     ) -> Dict[str, Any]:
         """
-        Does the following * Adds new `Attributes` , `Rules` , or `ObjectTypes` .
+        Does the following: * Adds new `Attributes`, `Rules`, or `ObjectTypes`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Client.update_facet)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/client/#update_facet)
         """
     async def update_link_attributes(
         self,
         *,
@@ -952,15 +952,15 @@
         DevelopmentSchemaArn: str,
         PublishedSchemaArn: str,
         MinorVersion: str,
         DryRun: bool = ...
     ) -> UpgradePublishedSchemaResponseTypeDef:
         """
         Upgrades a published schema under a new minor version revision using the current
-        contents of `DevelopmentSchemaArn` .
+        contents of `DevelopmentSchemaArn`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Client.upgrade_published_schema)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/client/#upgrade_published_schema)
         """
     @overload
     def get_paginator(
         self, operation_name: Literal["list_applied_schema_arns"]
```

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/literals.py` & `types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -159,14 +159,15 @@
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
@@ -245,14 +246,15 @@
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
@@ -263,14 +265,15 @@
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
@@ -306,14 +309,15 @@
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
@@ -332,16 +336,19 @@
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
@@ -425,15 +432,17 @@
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

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/literals.pyi` & `types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -157,14 +157,15 @@
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
@@ -243,14 +244,15 @@
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
@@ -261,14 +263,15 @@
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
@@ -304,14 +307,15 @@
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
@@ -330,16 +334,19 @@
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
@@ -423,15 +430,17 @@
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

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/paginator.py` & `types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/paginator.py`

 * *Files 1% similar despite different names*

```diff
@@ -52,16 +52,15 @@
         list_published_schema_arns_paginator: ListPublishedSchemaArnsPaginator = client.get_paginator("list_published_schema_arns")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         list_typed_link_facet_attributes_paginator: ListTypedLinkFacetAttributesPaginator = client.get_paginator("list_typed_link_facet_attributes")
         list_typed_link_facet_names_paginator: ListTypedLinkFacetNamesPaginator = client.get_paginator("list_typed_link_facet_names")
         lookup_policy_paginator: LookupPolicyPaginator = client.get_paginator("lookup_policy")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ConsistencyLevelType, DirectoryStateType
 from .type_defs import (
     ListAppliedSchemaArnsResponseTypeDef,
@@ -87,20 +86,14 @@
     ObjectReferenceTypeDef,
     PaginatorConfigTypeDef,
     SchemaFacetTypeDef,
     TypedLinkAttributeRangeTypeDef,
     TypedLinkSchemaAndFacetNameTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAppliedSchemaArnsPaginator",
     "ListAttachedIndicesPaginator",
     "ListDevelopmentSchemaArnsPaginator",
     "ListDirectoriesPaginator",
     "ListFacetAttributesPaginator",
     "ListFacetNamesPaginator",
@@ -137,15 +130,15 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryArn: str,
         SchemaArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAppliedSchemaArnsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListAppliedSchemaArns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listappliedschemaarnspaginator)
         """
 
 
@@ -157,75 +150,75 @@
 
     def paginate(
         self,
         *,
         DirectoryArn: str,
         TargetReference: ObjectReferenceTypeDef,
         ConsistencyLevel: ConsistencyLevelType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttachedIndicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListAttachedIndices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listattachedindicespaginator)
         """
 
 
 class ListDevelopmentSchemaArnsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListDevelopmentSchemaArns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listdevelopmentschemaarnspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDevelopmentSchemaArnsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListDevelopmentSchemaArns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listdevelopmentschemaarnspaginator)
         """
 
 
 class ListDirectoriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListDirectories)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listdirectoriespaginator)
     """
 
     def paginate(
-        self, *, state: DirectoryStateType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, state: DirectoryStateType = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDirectoriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListDirectories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listdirectoriespaginator)
         """
 
 
 class ListFacetAttributesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListFacetAttributes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listfacetattributespaginator)
     """
 
     def paginate(
-        self, *, SchemaArn: str, Name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SchemaArn: str, Name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFacetAttributesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListFacetAttributes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listfacetattributespaginator)
         """
 
 
 class ListFacetNamesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListFacetNames)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listfacetnamespaginator)
     """
 
     def paginate(
-        self, *, SchemaArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SchemaArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFacetNamesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListFacetNames.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listfacetnamespaginator)
         """
 
 
@@ -239,15 +232,15 @@
         self,
         *,
         DirectoryArn: str,
         ObjectReference: ObjectReferenceTypeDef,
         FilterAttributeRanges: Sequence[TypedLinkAttributeRangeTypeDef] = ...,
         FilterTypedLink: TypedLinkSchemaAndFacetNameTypeDef = ...,
         ConsistencyLevel: ConsistencyLevelType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIncomingTypedLinksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListIncomingTypedLinks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listincomingtypedlinkspaginator)
         """
 
 
@@ -260,30 +253,30 @@
     def paginate(
         self,
         *,
         DirectoryArn: str,
         IndexReference: ObjectReferenceTypeDef,
         RangesOnIndexedValues: Sequence[ObjectAttributeRangeTypeDef] = ...,
         ConsistencyLevel: ConsistencyLevelType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIndexResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListIndex.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listindexpaginator)
         """
 
 
 class ListManagedSchemaArnsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListManagedSchemaArns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listmanagedschemaarnspaginator)
     """
 
     def paginate(
-        self, *, SchemaArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SchemaArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListManagedSchemaArnsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListManagedSchemaArns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listmanagedschemaarnspaginator)
         """
 
 
@@ -296,15 +289,15 @@
     def paginate(
         self,
         *,
         DirectoryArn: str,
         ObjectReference: ObjectReferenceTypeDef,
         ConsistencyLevel: ConsistencyLevelType = ...,
         FacetFilter: SchemaFacetTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListObjectAttributesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListObjectAttributes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listobjectattributespaginator)
         """
 
 
@@ -315,15 +308,15 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryArn: str,
         ObjectReference: ObjectReferenceTypeDef,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListObjectParentPathsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListObjectParentPaths.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listobjectparentpathspaginator)
         """
 
 
@@ -335,15 +328,15 @@
 
     def paginate(
         self,
         *,
         DirectoryArn: str,
         ObjectReference: ObjectReferenceTypeDef,
         ConsistencyLevel: ConsistencyLevelType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListObjectPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListObjectPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listobjectpoliciespaginator)
         """
 
 
@@ -357,15 +350,15 @@
         self,
         *,
         DirectoryArn: str,
         ObjectReference: ObjectReferenceTypeDef,
         FilterAttributeRanges: Sequence[TypedLinkAttributeRangeTypeDef] = ...,
         FilterTypedLink: TypedLinkSchemaAndFacetNameTypeDef = ...,
         ConsistencyLevel: ConsistencyLevelType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOutgoingTypedLinksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListOutgoingTypedLinks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listoutgoingtypedlinkspaginator)
         """
 
 
@@ -377,75 +370,75 @@
 
     def paginate(
         self,
         *,
         DirectoryArn: str,
         PolicyReference: ObjectReferenceTypeDef,
         ConsistencyLevel: ConsistencyLevelType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPolicyAttachmentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListPolicyAttachments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listpolicyattachmentspaginator)
         """
 
 
 class ListPublishedSchemaArnsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListPublishedSchemaArns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listpublishedschemaarnspaginator)
     """
 
     def paginate(
-        self, *, SchemaArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SchemaArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPublishedSchemaArnsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListPublishedSchemaArns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listpublishedschemaarnspaginator)
         """
 
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listtagsforresourcepaginator)
         """
 
 
 class ListTypedLinkFacetAttributesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListTypedLinkFacetAttributes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listtypedlinkfacetattributespaginator)
     """
 
     def paginate(
-        self, *, SchemaArn: str, Name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SchemaArn: str, Name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTypedLinkFacetAttributesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListTypedLinkFacetAttributes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listtypedlinkfacetattributespaginator)
         """
 
 
 class ListTypedLinkFacetNamesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListTypedLinkFacetNames)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listtypedlinkfacetnamespaginator)
     """
 
     def paginate(
-        self, *, SchemaArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SchemaArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTypedLinkFacetNamesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListTypedLinkFacetNames.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listtypedlinkfacetnamespaginator)
         """
 
 
@@ -456,13 +449,13 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryArn: str,
         ObjectReference: ObjectReferenceTypeDef,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[LookupPolicyResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.LookupPolicy.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#lookuppolicypaginator)
         """
```

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/paginator.pyi` & `types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -52,16 +52,15 @@
         list_published_schema_arns_paginator: ListPublishedSchemaArnsPaginator = client.get_paginator("list_published_schema_arns")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         list_typed_link_facet_attributes_paginator: ListTypedLinkFacetAttributesPaginator = client.get_paginator("list_typed_link_facet_attributes")
         list_typed_link_facet_names_paginator: ListTypedLinkFacetNamesPaginator = client.get_paginator("list_typed_link_facet_names")
         lookup_policy_paginator: LookupPolicyPaginator = client.get_paginator("lookup_policy")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ConsistencyLevelType, DirectoryStateType
 from .type_defs import (
     ListAppliedSchemaArnsResponseTypeDef,
@@ -87,19 +86,14 @@
     ObjectReferenceTypeDef,
     PaginatorConfigTypeDef,
     SchemaFacetTypeDef,
     TypedLinkAttributeRangeTypeDef,
     TypedLinkSchemaAndFacetNameTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAppliedSchemaArnsPaginator",
     "ListAttachedIndicesPaginator",
     "ListDevelopmentSchemaArnsPaginator",
     "ListDirectoriesPaginator",
     "ListFacetAttributesPaginator",
     "ListFacetNamesPaginator",
@@ -133,15 +127,15 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryArn: str,
         SchemaArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAppliedSchemaArnsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListAppliedSchemaArns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listappliedschemaarnspaginator)
         """
 
 class ListAttachedIndicesPaginator(AioPaginator):
@@ -152,71 +146,71 @@
 
     def paginate(
         self,
         *,
         DirectoryArn: str,
         TargetReference: ObjectReferenceTypeDef,
         ConsistencyLevel: ConsistencyLevelType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttachedIndicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListAttachedIndices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listattachedindicespaginator)
         """
 
 class ListDevelopmentSchemaArnsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListDevelopmentSchemaArns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listdevelopmentschemaarnspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDevelopmentSchemaArnsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListDevelopmentSchemaArns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listdevelopmentschemaarnspaginator)
         """
 
 class ListDirectoriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListDirectories)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listdirectoriespaginator)
     """
 
     def paginate(
-        self, *, state: DirectoryStateType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, state: DirectoryStateType = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDirectoriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListDirectories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listdirectoriespaginator)
         """
 
 class ListFacetAttributesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListFacetAttributes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listfacetattributespaginator)
     """
 
     def paginate(
-        self, *, SchemaArn: str, Name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SchemaArn: str, Name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFacetAttributesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListFacetAttributes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listfacetattributespaginator)
         """
 
 class ListFacetNamesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListFacetNames)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listfacetnamespaginator)
     """
 
     def paginate(
-        self, *, SchemaArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SchemaArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFacetNamesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListFacetNames.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listfacetnamespaginator)
         """
 
 class ListIncomingTypedLinksPaginator(AioPaginator):
@@ -229,15 +223,15 @@
         self,
         *,
         DirectoryArn: str,
         ObjectReference: ObjectReferenceTypeDef,
         FilterAttributeRanges: Sequence[TypedLinkAttributeRangeTypeDef] = ...,
         FilterTypedLink: TypedLinkSchemaAndFacetNameTypeDef = ...,
         ConsistencyLevel: ConsistencyLevelType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIncomingTypedLinksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListIncomingTypedLinks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listincomingtypedlinkspaginator)
         """
 
 class ListIndexPaginator(AioPaginator):
@@ -249,29 +243,29 @@
     def paginate(
         self,
         *,
         DirectoryArn: str,
         IndexReference: ObjectReferenceTypeDef,
         RangesOnIndexedValues: Sequence[ObjectAttributeRangeTypeDef] = ...,
         ConsistencyLevel: ConsistencyLevelType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIndexResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListIndex.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listindexpaginator)
         """
 
 class ListManagedSchemaArnsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListManagedSchemaArns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listmanagedschemaarnspaginator)
     """
 
     def paginate(
-        self, *, SchemaArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SchemaArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListManagedSchemaArnsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListManagedSchemaArns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listmanagedschemaarnspaginator)
         """
 
 class ListObjectAttributesPaginator(AioPaginator):
@@ -283,15 +277,15 @@
     def paginate(
         self,
         *,
         DirectoryArn: str,
         ObjectReference: ObjectReferenceTypeDef,
         ConsistencyLevel: ConsistencyLevelType = ...,
         FacetFilter: SchemaFacetTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListObjectAttributesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListObjectAttributes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listobjectattributespaginator)
         """
 
 class ListObjectParentPathsPaginator(AioPaginator):
@@ -301,15 +295,15 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryArn: str,
         ObjectReference: ObjectReferenceTypeDef,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListObjectParentPathsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListObjectParentPaths.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listobjectparentpathspaginator)
         """
 
 class ListObjectPoliciesPaginator(AioPaginator):
@@ -320,15 +314,15 @@
 
     def paginate(
         self,
         *,
         DirectoryArn: str,
         ObjectReference: ObjectReferenceTypeDef,
         ConsistencyLevel: ConsistencyLevelType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListObjectPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListObjectPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listobjectpoliciespaginator)
         """
 
 class ListOutgoingTypedLinksPaginator(AioPaginator):
@@ -341,15 +335,15 @@
         self,
         *,
         DirectoryArn: str,
         ObjectReference: ObjectReferenceTypeDef,
         FilterAttributeRanges: Sequence[TypedLinkAttributeRangeTypeDef] = ...,
         FilterTypedLink: TypedLinkSchemaAndFacetNameTypeDef = ...,
         ConsistencyLevel: ConsistencyLevelType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOutgoingTypedLinksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListOutgoingTypedLinks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listoutgoingtypedlinkspaginator)
         """
 
 class ListPolicyAttachmentsPaginator(AioPaginator):
@@ -360,71 +354,71 @@
 
     def paginate(
         self,
         *,
         DirectoryArn: str,
         PolicyReference: ObjectReferenceTypeDef,
         ConsistencyLevel: ConsistencyLevelType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPolicyAttachmentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListPolicyAttachments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listpolicyattachmentspaginator)
         """
 
 class ListPublishedSchemaArnsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListPublishedSchemaArns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listpublishedschemaarnspaginator)
     """
 
     def paginate(
-        self, *, SchemaArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SchemaArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPublishedSchemaArnsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListPublishedSchemaArns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listpublishedschemaarnspaginator)
         """
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listtagsforresourcepaginator)
         """
 
 class ListTypedLinkFacetAttributesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListTypedLinkFacetAttributes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listtypedlinkfacetattributespaginator)
     """
 
     def paginate(
-        self, *, SchemaArn: str, Name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SchemaArn: str, Name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTypedLinkFacetAttributesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListTypedLinkFacetAttributes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listtypedlinkfacetattributespaginator)
         """
 
 class ListTypedLinkFacetNamesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListTypedLinkFacetNames)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listtypedlinkfacetnamespaginator)
     """
 
     def paginate(
-        self, *, SchemaArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SchemaArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTypedLinkFacetNamesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.ListTypedLinkFacetNames.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#listtypedlinkfacetnamespaginator)
         """
 
 class LookupPolicyPaginator(AioPaginator):
@@ -434,13 +428,13 @@
     """
 
     def paginate(
         self,
         *,
         DirectoryArn: str,
         ObjectReference: ObjectReferenceTypeDef,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[LookupPolicyResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory.Paginator.LookupPolicy.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/paginators/#lookuppolicypaginator)
         """
```

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/type_defs.py` & `types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -31,20 +31,21 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ObjectReferenceTypeDef",
     "SchemaFacetTypeDef",
     "ApplySchemaRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "ApplySchemaResponseTypeDef",
+    "AttachObjectResponseTypeDef",
+    "AttachToIndexResponseTypeDef",
     "TypedLinkSchemaAndFacetNameTypeDef",
     "AttributeKeyTypeDef",
     "TypedAttributeValueTypeDef",
     "BatchAttachObjectResponseTypeDef",
     "BatchAttachToIndexResponseTypeDef",
     "BatchCreateIndexResponseTypeDef",
     "BatchCreateObjectResponseTypeDef",
@@ -54,49 +55,89 @@
     "PathToObjectIdentifiersTypeDef",
     "ObjectIdentifierAndLinkNameTupleTypeDef",
     "BatchListObjectPoliciesResponseTypeDef",
     "BatchListPolicyAttachmentsResponseTypeDef",
     "BatchReadExceptionTypeDef",
     "BatchUpdateObjectAttributesResponseTypeDef",
     "CreateDirectoryRequestRequestTypeDef",
+    "CreateDirectoryResponseTypeDef",
+    "CreateIndexResponseTypeDef",
+    "CreateObjectResponseTypeDef",
     "CreateSchemaRequestRequestTypeDef",
+    "CreateSchemaResponseTypeDef",
     "DeleteDirectoryRequestRequestTypeDef",
+    "DeleteDirectoryResponseTypeDef",
     "DeleteFacetRequestRequestTypeDef",
     "DeleteSchemaRequestRequestTypeDef",
+    "DeleteSchemaResponseTypeDef",
     "DeleteTypedLinkFacetRequestRequestTypeDef",
+    "DetachFromIndexResponseTypeDef",
+    "DetachObjectResponseTypeDef",
     "DirectoryTypeDef",
     "DisableDirectoryRequestRequestTypeDef",
+    "DisableDirectoryResponseTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableDirectoryRequestRequestTypeDef",
+    "EnableDirectoryResponseTypeDef",
     "RuleTypeDef",
     "FacetAttributeReferenceTypeDef",
     "FacetTypeDef",
     "GetAppliedSchemaVersionRequestRequestTypeDef",
+    "GetAppliedSchemaVersionResponseTypeDef",
     "GetDirectoryRequestRequestTypeDef",
     "GetFacetRequestRequestTypeDef",
     "GetSchemaAsJsonRequestRequestTypeDef",
+    "GetSchemaAsJsonResponseTypeDef",
     "GetTypedLinkFacetInformationRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetTypedLinkFacetInformationResponseTypeDef",
+    "ListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef",
     "ListAppliedSchemaArnsRequestRequestTypeDef",
+    "ListAppliedSchemaArnsResponseTypeDef",
+    "ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef",
     "ListDevelopmentSchemaArnsRequestRequestTypeDef",
+    "ListDevelopmentSchemaArnsResponseTypeDef",
+    "ListDirectoriesRequestListDirectoriesPaginateTypeDef",
     "ListDirectoriesRequestRequestTypeDef",
+    "ListFacetAttributesRequestListFacetAttributesPaginateTypeDef",
     "ListFacetAttributesRequestRequestTypeDef",
+    "ListFacetNamesRequestListFacetNamesPaginateTypeDef",
     "ListFacetNamesRequestRequestTypeDef",
+    "ListFacetNamesResponseTypeDef",
+    "ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef",
     "ListManagedSchemaArnsRequestRequestTypeDef",
+    "ListManagedSchemaArnsResponseTypeDef",
+    "ListObjectChildrenResponseTypeDef",
+    "ListObjectPoliciesResponseTypeDef",
+    "ListPolicyAttachmentsResponseTypeDef",
+    "ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef",
     "ListPublishedSchemaArnsRequestRequestTypeDef",
+    "ListPublishedSchemaArnsResponseTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
+    "ListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef",
     "ListTypedLinkFacetAttributesRequestRequestTypeDef",
+    "ListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef",
     "ListTypedLinkFacetNamesRequestRequestTypeDef",
+    "ListTypedLinkFacetNamesResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PolicyAttachmentTypeDef",
     "PublishSchemaRequestRequestTypeDef",
+    "PublishSchemaResponseTypeDef",
     "PutSchemaFromJsonRequestRequestTypeDef",
+    "PutSchemaFromJsonResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateObjectAttributesResponseTypeDef",
     "UpdateSchemaRequestRequestTypeDef",
+    "UpdateSchemaResponseTypeDef",
     "UpgradeAppliedSchemaRequestRequestTypeDef",
+    "UpgradeAppliedSchemaResponseTypeDef",
     "UpgradePublishedSchemaRequestRequestTypeDef",
+    "UpgradePublishedSchemaResponseTypeDef",
     "AttachObjectRequestRequestTypeDef",
     "AttachPolicyRequestRequestTypeDef",
     "AttachToIndexRequestRequestTypeDef",
     "BatchAttachObjectTypeDef",
     "BatchAttachPolicyTypeDef",
     "BatchAttachToIndexTypeDef",
     "BatchDeleteObjectTypeDef",
@@ -112,61 +153,35 @@
     "BatchListPolicyAttachmentsTypeDef",
     "BatchLookupPolicyTypeDef",
     "DeleteObjectRequestRequestTypeDef",
     "DetachFromIndexRequestRequestTypeDef",
     "DetachObjectRequestRequestTypeDef",
     "DetachPolicyRequestRequestTypeDef",
     "GetObjectInformationRequestRequestTypeDef",
+    "ListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef",
     "ListAttachedIndicesRequestRequestTypeDef",
     "ListObjectChildrenRequestRequestTypeDef",
+    "ListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef",
     "ListObjectParentPathsRequestRequestTypeDef",
     "ListObjectParentsRequestRequestTypeDef",
+    "ListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef",
     "ListObjectPoliciesRequestRequestTypeDef",
+    "ListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef",
     "ListPolicyAttachmentsRequestRequestTypeDef",
+    "LookupPolicyRequestLookupPolicyPaginateTypeDef",
     "LookupPolicyRequestRequestTypeDef",
     "BatchGetObjectAttributesTypeDef",
     "BatchGetObjectInformationResponseTypeDef",
     "BatchListObjectAttributesTypeDef",
     "BatchRemoveFacetFromObjectTypeDef",
     "GetObjectAttributesRequestRequestTypeDef",
+    "GetObjectInformationResponseTypeDef",
+    "ListObjectAttributesRequestListObjectAttributesPaginateTypeDef",
     "ListObjectAttributesRequestRequestTypeDef",
     "RemoveFacetFromObjectRequestRequestTypeDef",
-    "ApplySchemaResponseTypeDef",
-    "AttachObjectResponseTypeDef",
-    "AttachToIndexResponseTypeDef",
-    "CreateDirectoryResponseTypeDef",
-    "CreateIndexResponseTypeDef",
-    "CreateObjectResponseTypeDef",
-    "CreateSchemaResponseTypeDef",
-    "DeleteDirectoryResponseTypeDef",
-    "DeleteSchemaResponseTypeDef",
-    "DetachFromIndexResponseTypeDef",
-    "DetachObjectResponseTypeDef",
-    "DisableDirectoryResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "EnableDirectoryResponseTypeDef",
-    "GetAppliedSchemaVersionResponseTypeDef",
-    "GetObjectInformationResponseTypeDef",
-    "GetSchemaAsJsonResponseTypeDef",
-    "GetTypedLinkFacetInformationResponseTypeDef",
-    "ListAppliedSchemaArnsResponseTypeDef",
-    "ListDevelopmentSchemaArnsResponseTypeDef",
-    "ListFacetNamesResponseTypeDef",
-    "ListManagedSchemaArnsResponseTypeDef",
-    "ListObjectChildrenResponseTypeDef",
-    "ListObjectPoliciesResponseTypeDef",
-    "ListPolicyAttachmentsResponseTypeDef",
-    "ListPublishedSchemaArnsResponseTypeDef",
-    "ListTypedLinkFacetNamesResponseTypeDef",
-    "PublishSchemaResponseTypeDef",
-    "PutSchemaFromJsonResponseTypeDef",
-    "UpdateObjectAttributesResponseTypeDef",
-    "UpdateSchemaResponseTypeDef",
-    "UpgradeAppliedSchemaResponseTypeDef",
-    "UpgradePublishedSchemaResponseTypeDef",
     "BatchCreateIndexTypeDef",
     "CreateIndexRequestRequestTypeDef",
     "AttributeKeyAndValueTypeDef",
     "AttributeNameAndValueTypeDef",
     "LinkAttributeActionTypeDef",
     "ObjectAttributeActionTypeDef",
     "TypedAttributeValueRangeTypeDef",
@@ -175,30 +190,14 @@
     "BatchListObjectParentsResponseTypeDef",
     "ListObjectParentsResponseTypeDef",
     "GetDirectoryResponseTypeDef",
     "ListDirectoriesResponseTypeDef",
     "FacetAttributeDefinitionTypeDef",
     "TypedLinkAttributeDefinitionTypeDef",
     "GetFacetResponseTypeDef",
-    "ListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef",
-    "ListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef",
-    "ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef",
-    "ListDirectoriesRequestListDirectoriesPaginateTypeDef",
-    "ListFacetAttributesRequestListFacetAttributesPaginateTypeDef",
-    "ListFacetNamesRequestListFacetNamesPaginateTypeDef",
-    "ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef",
-    "ListObjectAttributesRequestListObjectAttributesPaginateTypeDef",
-    "ListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef",
-    "ListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef",
-    "ListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef",
-    "ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    "ListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef",
-    "ListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef",
-    "LookupPolicyRequestLookupPolicyPaginateTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "PolicyToPathTypeDef",
     "AddFacetToObjectRequestRequestTypeDef",
     "BatchAddFacetToObjectTypeDef",
     "BatchCreateObjectTypeDef",
     "BatchGetLinkAttributesResponseTypeDef",
@@ -287,22 +286,36 @@
     "ApplySchemaRequestRequestTypeDef",
     {
         "PublishedSchemaArn": str,
         "DirectoryArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ApplySchemaResponseTypeDef = TypedDict(
+    "ApplySchemaResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AppliedSchemaArn": str,
+        "DirectoryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AttachObjectResponseTypeDef = TypedDict(
+    "AttachObjectResponseTypeDef",
+    {
+        "AttachedObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AttachToIndexResponseTypeDef = TypedDict(
+    "AttachToIndexResponseTypeDef",
+    {
+        "AttachedObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TypedLinkSchemaAndFacetNameTypeDef = TypedDict(
     "TypedLinkSchemaAndFacetNameTypeDef",
     {
         "SchemaArn": str,
@@ -445,28 +458,71 @@
     "CreateDirectoryRequestRequestTypeDef",
     {
         "Name": str,
         "SchemaArn": str,
     },
 )
 
+CreateDirectoryResponseTypeDef = TypedDict(
+    "CreateDirectoryResponseTypeDef",
+    {
+        "DirectoryArn": str,
+        "Name": str,
+        "ObjectIdentifier": str,
+        "AppliedSchemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateIndexResponseTypeDef = TypedDict(
+    "CreateIndexResponseTypeDef",
+    {
+        "ObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateObjectResponseTypeDef = TypedDict(
+    "CreateObjectResponseTypeDef",
+    {
+        "ObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateSchemaRequestRequestTypeDef = TypedDict(
     "CreateSchemaRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+CreateSchemaResponseTypeDef = TypedDict(
+    "CreateSchemaResponseTypeDef",
+    {
+        "SchemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDirectoryRequestRequestTypeDef = TypedDict(
     "DeleteDirectoryRequestRequestTypeDef",
     {
         "DirectoryArn": str,
     },
 )
 
+DeleteDirectoryResponseTypeDef = TypedDict(
+    "DeleteDirectoryResponseTypeDef",
+    {
+        "DirectoryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteFacetRequestRequestTypeDef = TypedDict(
     "DeleteFacetRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Name": str,
     },
 )
@@ -474,22 +530,46 @@
 DeleteSchemaRequestRequestTypeDef = TypedDict(
     "DeleteSchemaRequestRequestTypeDef",
     {
         "SchemaArn": str,
     },
 )
 
+DeleteSchemaResponseTypeDef = TypedDict(
+    "DeleteSchemaResponseTypeDef",
+    {
+        "SchemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteTypedLinkFacetRequestRequestTypeDef = TypedDict(
     "DeleteTypedLinkFacetRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Name": str,
     },
 )
 
+DetachFromIndexResponseTypeDef = TypedDict(
+    "DetachFromIndexResponseTypeDef",
+    {
+        "DetachedObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DetachObjectResponseTypeDef = TypedDict(
+    "DetachObjectResponseTypeDef",
+    {
+        "DetachedObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DirectoryTypeDef = TypedDict(
     "DirectoryTypeDef",
     {
         "Name": str,
         "DirectoryArn": str,
         "State": DirectoryStateType,
         "CreationDateTime": datetime,
@@ -500,21 +580,44 @@
 DisableDirectoryRequestRequestTypeDef = TypedDict(
     "DisableDirectoryRequestRequestTypeDef",
     {
         "DirectoryArn": str,
     },
 )
 
+DisableDirectoryResponseTypeDef = TypedDict(
+    "DisableDirectoryResponseTypeDef",
+    {
+        "DirectoryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableDirectoryRequestRequestTypeDef = TypedDict(
     "EnableDirectoryRequestRequestTypeDef",
     {
         "DirectoryArn": str,
     },
 )
 
+EnableDirectoryResponseTypeDef = TypedDict(
+    "EnableDirectoryResponseTypeDef",
+    {
+        "DirectoryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RuleTypeDef = TypedDict(
     "RuleTypeDef",
     {
         "Type": RuleTypeType,
         "Parameters": Mapping[str, str],
     },
     total=False,
@@ -541,14 +644,22 @@
 GetAppliedSchemaVersionRequestRequestTypeDef = TypedDict(
     "GetAppliedSchemaVersionRequestRequestTypeDef",
     {
         "SchemaArn": str,
     },
 )
 
+GetAppliedSchemaVersionResponseTypeDef = TypedDict(
+    "GetAppliedSchemaVersionResponseTypeDef",
+    {
+        "AppliedSchemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDirectoryRequestRequestTypeDef = TypedDict(
     "GetDirectoryRequestRequestTypeDef",
     {
         "DirectoryArn": str,
     },
 )
 
@@ -563,32 +674,60 @@
 GetSchemaAsJsonRequestRequestTypeDef = TypedDict(
     "GetSchemaAsJsonRequestRequestTypeDef",
     {
         "SchemaArn": str,
     },
 )
 
+GetSchemaAsJsonResponseTypeDef = TypedDict(
+    "GetSchemaAsJsonResponseTypeDef",
+    {
+        "Name": str,
+        "Document": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTypedLinkFacetInformationRequestRequestTypeDef = TypedDict(
     "GetTypedLinkFacetInformationRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Name": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetTypedLinkFacetInformationResponseTypeDef = TypedDict(
+    "GetTypedLinkFacetInformationResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "IdentityAttributeOrder": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef = TypedDict(
+    "_RequiredListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef",
+    {
+        "DirectoryArn": str,
+    },
+)
+_OptionalListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef = TypedDict(
+    "_OptionalListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef",
+    {
+        "SchemaArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef(
+    _RequiredListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef,
+    _OptionalListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef,
+):
+    pass
+
 _RequiredListAppliedSchemaArnsRequestRequestTypeDef = TypedDict(
     "_RequiredListAppliedSchemaArnsRequestRequestTypeDef",
     {
         "DirectoryArn": str,
     },
 )
 _OptionalListAppliedSchemaArnsRequestRequestTypeDef = TypedDict(
@@ -597,41 +736,95 @@
         "SchemaArn": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListAppliedSchemaArnsRequestRequestTypeDef(
     _RequiredListAppliedSchemaArnsRequestRequestTypeDef,
     _OptionalListAppliedSchemaArnsRequestRequestTypeDef,
 ):
     pass
 
+ListAppliedSchemaArnsResponseTypeDef = TypedDict(
+    "ListAppliedSchemaArnsResponseTypeDef",
+    {
+        "SchemaArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef = TypedDict(
+    "ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListDevelopmentSchemaArnsRequestRequestTypeDef = TypedDict(
     "ListDevelopmentSchemaArnsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListDevelopmentSchemaArnsResponseTypeDef = TypedDict(
+    "ListDevelopmentSchemaArnsResponseTypeDef",
+    {
+        "SchemaArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDirectoriesRequestListDirectoriesPaginateTypeDef = TypedDict(
+    "ListDirectoriesRequestListDirectoriesPaginateTypeDef",
+    {
+        "state": DirectoryStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDirectoriesRequestRequestTypeDef = TypedDict(
     "ListDirectoriesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "state": DirectoryStateType,
     },
     total=False,
 )
 
+_RequiredListFacetAttributesRequestListFacetAttributesPaginateTypeDef = TypedDict(
+    "_RequiredListFacetAttributesRequestListFacetAttributesPaginateTypeDef",
+    {
+        "SchemaArn": str,
+        "Name": str,
+    },
+)
+_OptionalListFacetAttributesRequestListFacetAttributesPaginateTypeDef = TypedDict(
+    "_OptionalListFacetAttributesRequestListFacetAttributesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListFacetAttributesRequestListFacetAttributesPaginateTypeDef(
+    _RequiredListFacetAttributesRequestListFacetAttributesPaginateTypeDef,
+    _OptionalListFacetAttributesRequestListFacetAttributesPaginateTypeDef,
+):
+    pass
+
 _RequiredListFacetAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredListFacetAttributesRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Name": str,
     },
 )
@@ -640,21 +833,39 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListFacetAttributesRequestRequestTypeDef(
     _RequiredListFacetAttributesRequestRequestTypeDef,
     _OptionalListFacetAttributesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListFacetNamesRequestListFacetNamesPaginateTypeDef = TypedDict(
+    "_RequiredListFacetNamesRequestListFacetNamesPaginateTypeDef",
+    {
+        "SchemaArn": str,
+    },
+)
+_OptionalListFacetNamesRequestListFacetNamesPaginateTypeDef = TypedDict(
+    "_OptionalListFacetNamesRequestListFacetNamesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListFacetNamesRequestListFacetNamesPaginateTypeDef(
+    _RequiredListFacetNamesRequestListFacetNamesPaginateTypeDef,
+    _OptionalListFacetNamesRequestListFacetNamesPaginateTypeDef,
+):
+    pass
 
 _RequiredListFacetNamesRequestRequestTypeDef = TypedDict(
     "_RequiredListFacetNamesRequestRequestTypeDef",
     {
         "SchemaArn": str,
     },
 )
@@ -663,41 +874,131 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListFacetNamesRequestRequestTypeDef(
     _RequiredListFacetNamesRequestRequestTypeDef, _OptionalListFacetNamesRequestRequestTypeDef
 ):
     pass
 
+ListFacetNamesResponseTypeDef = TypedDict(
+    "ListFacetNamesResponseTypeDef",
+    {
+        "FacetNames": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef = TypedDict(
+    "ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef",
+    {
+        "SchemaArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListManagedSchemaArnsRequestRequestTypeDef = TypedDict(
     "ListManagedSchemaArnsRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListManagedSchemaArnsResponseTypeDef = TypedDict(
+    "ListManagedSchemaArnsResponseTypeDef",
+    {
+        "SchemaArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListObjectChildrenResponseTypeDef = TypedDict(
+    "ListObjectChildrenResponseTypeDef",
+    {
+        "Children": Dict[str, str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListObjectPoliciesResponseTypeDef = TypedDict(
+    "ListObjectPoliciesResponseTypeDef",
+    {
+        "AttachedPolicyIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListPolicyAttachmentsResponseTypeDef = TypedDict(
+    "ListPolicyAttachmentsResponseTypeDef",
+    {
+        "ObjectIdentifiers": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef = TypedDict(
+    "ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef",
+    {
+        "SchemaArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPublishedSchemaArnsRequestRequestTypeDef = TypedDict(
     "ListPublishedSchemaArnsRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListPublishedSchemaArnsResponseTypeDef = TypedDict(
+    "ListPublishedSchemaArnsResponseTypeDef",
+    {
+        "SchemaArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceArn": str,
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
         "ResourceArn": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -705,31 +1006,50 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
-
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
     total=False,
 )
 
+_RequiredListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef = TypedDict(
+    "_RequiredListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef",
+    {
+        "SchemaArn": str,
+        "Name": str,
+    },
+)
+_OptionalListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef = TypedDict(
+    "_OptionalListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef(
+    _RequiredListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef,
+    _OptionalListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef,
+):
+    pass
+
 _RequiredListTypedLinkFacetAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredListTypedLinkFacetAttributesRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Name": str,
     },
 )
@@ -738,21 +1058,39 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListTypedLinkFacetAttributesRequestRequestTypeDef(
     _RequiredListTypedLinkFacetAttributesRequestRequestTypeDef,
     _OptionalListTypedLinkFacetAttributesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef = TypedDict(
+    "_RequiredListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef",
+    {
+        "SchemaArn": str,
+    },
+)
+_OptionalListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef = TypedDict(
+    "_OptionalListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef(
+    _RequiredListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef,
+    _OptionalListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef,
+):
+    pass
 
 _RequiredListTypedLinkFacetNamesRequestRequestTypeDef = TypedDict(
     "_RequiredListTypedLinkFacetNamesRequestRequestTypeDef",
     {
         "SchemaArn": str,
     },
 )
@@ -761,21 +1099,38 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListTypedLinkFacetNamesRequestRequestTypeDef(
     _RequiredListTypedLinkFacetNamesRequestRequestTypeDef,
     _OptionalListTypedLinkFacetNamesRequestRequestTypeDef,
 ):
     pass
 
+ListTypedLinkFacetNamesResponseTypeDef = TypedDict(
+    "ListTypedLinkFacetNamesResponseTypeDef",
+    {
+        "FacetNames": List[str],
+        "NextToken": str,
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
 
 PolicyAttachmentTypeDef = TypedDict(
     "PolicyAttachmentTypeDef",
     {
         "PolicyId": str,
         "ObjectIdentifier": str,
         "PolicyType": str,
@@ -795,45 +1150,86 @@
     {
         "MinorVersion": str,
         "Name": str,
     },
     total=False,
 )
 
-
 class PublishSchemaRequestRequestTypeDef(
     _RequiredPublishSchemaRequestRequestTypeDef, _OptionalPublishSchemaRequestRequestTypeDef
 ):
     pass
 
+PublishSchemaResponseTypeDef = TypedDict(
+    "PublishSchemaResponseTypeDef",
+    {
+        "PublishedSchemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 PutSchemaFromJsonRequestRequestTypeDef = TypedDict(
     "PutSchemaFromJsonRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Document": str,
     },
 )
 
+PutSchemaFromJsonResponseTypeDef = TypedDict(
+    "PutSchemaFromJsonResponseTypeDef",
+    {
+        "Arn": str,
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateObjectAttributesResponseTypeDef = TypedDict(
+    "UpdateObjectAttributesResponseTypeDef",
+    {
+        "ObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateSchemaRequestRequestTypeDef = TypedDict(
     "UpdateSchemaRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Name": str,
     },
 )
 
+UpdateSchemaResponseTypeDef = TypedDict(
+    "UpdateSchemaResponseTypeDef",
+    {
+        "SchemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpgradeAppliedSchemaRequestRequestTypeDef = TypedDict(
     "_RequiredUpgradeAppliedSchemaRequestRequestTypeDef",
     {
         "PublishedSchemaArn": str,
         "DirectoryArn": str,
     },
 )
@@ -841,21 +1237,28 @@
     "_OptionalUpgradeAppliedSchemaRequestRequestTypeDef",
     {
         "DryRun": bool,
     },
     total=False,
 )
 
-
 class UpgradeAppliedSchemaRequestRequestTypeDef(
     _RequiredUpgradeAppliedSchemaRequestRequestTypeDef,
     _OptionalUpgradeAppliedSchemaRequestRequestTypeDef,
 ):
     pass
 
+UpgradeAppliedSchemaResponseTypeDef = TypedDict(
+    "UpgradeAppliedSchemaResponseTypeDef",
+    {
+        "UpgradedSchemaArn": str,
+        "DirectoryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredUpgradePublishedSchemaRequestRequestTypeDef = TypedDict(
     "_RequiredUpgradePublishedSchemaRequestRequestTypeDef",
     {
         "DevelopmentSchemaArn": str,
         "PublishedSchemaArn": str,
         "MinorVersion": str,
@@ -865,21 +1268,27 @@
     "_OptionalUpgradePublishedSchemaRequestRequestTypeDef",
     {
         "DryRun": bool,
     },
     total=False,
 )
 
-
 class UpgradePublishedSchemaRequestRequestTypeDef(
     _RequiredUpgradePublishedSchemaRequestRequestTypeDef,
     _OptionalUpgradePublishedSchemaRequestRequestTypeDef,
 ):
     pass
 
+UpgradePublishedSchemaResponseTypeDef = TypedDict(
+    "UpgradePublishedSchemaResponseTypeDef",
+    {
+        "UpgradedSchemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 AttachObjectRequestRequestTypeDef = TypedDict(
     "AttachObjectRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ParentReference": ObjectReferenceTypeDef,
         "ChildReference": ObjectReferenceTypeDef,
@@ -956,21 +1365,19 @@
     "_OptionalBatchDetachObjectTypeDef",
     {
         "BatchReferenceName": str,
     },
     total=False,
 )
 
-
 class BatchDetachObjectTypeDef(
     _RequiredBatchDetachObjectTypeDef, _OptionalBatchDetachObjectTypeDef
 ):
     pass
 
-
 BatchDetachPolicyTypeDef = TypedDict(
     "BatchDetachPolicyTypeDef",
     {
         "PolicyReference": ObjectReferenceTypeDef,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -993,21 +1400,19 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class BatchListAttachedIndicesTypeDef(
     _RequiredBatchListAttachedIndicesTypeDef, _OptionalBatchListAttachedIndicesTypeDef
 ):
     pass
 
-
 _RequiredBatchListObjectChildrenTypeDef = TypedDict(
     "_RequiredBatchListObjectChildrenTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchListObjectChildrenTypeDef = TypedDict(
@@ -1015,21 +1420,19 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class BatchListObjectChildrenTypeDef(
     _RequiredBatchListObjectChildrenTypeDef, _OptionalBatchListObjectChildrenTypeDef
 ):
     pass
 
-
 _RequiredBatchListObjectParentPathsTypeDef = TypedDict(
     "_RequiredBatchListObjectParentPathsTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchListObjectParentPathsTypeDef = TypedDict(
@@ -1037,21 +1440,19 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class BatchListObjectParentPathsTypeDef(
     _RequiredBatchListObjectParentPathsTypeDef, _OptionalBatchListObjectParentPathsTypeDef
 ):
     pass
 
-
 _RequiredBatchListObjectParentsTypeDef = TypedDict(
     "_RequiredBatchListObjectParentsTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchListObjectParentsTypeDef = TypedDict(
@@ -1059,21 +1460,19 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class BatchListObjectParentsTypeDef(
     _RequiredBatchListObjectParentsTypeDef, _OptionalBatchListObjectParentsTypeDef
 ):
     pass
 
-
 _RequiredBatchListObjectPoliciesTypeDef = TypedDict(
     "_RequiredBatchListObjectPoliciesTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchListObjectPoliciesTypeDef = TypedDict(
@@ -1081,21 +1480,19 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class BatchListObjectPoliciesTypeDef(
     _RequiredBatchListObjectPoliciesTypeDef, _OptionalBatchListObjectPoliciesTypeDef
 ):
     pass
 
-
 _RequiredBatchListPolicyAttachmentsTypeDef = TypedDict(
     "_RequiredBatchListPolicyAttachmentsTypeDef",
     {
         "PolicyReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchListPolicyAttachmentsTypeDef = TypedDict(
@@ -1103,21 +1500,19 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class BatchListPolicyAttachmentsTypeDef(
     _RequiredBatchListPolicyAttachmentsTypeDef, _OptionalBatchListPolicyAttachmentsTypeDef
 ):
     pass
 
-
 _RequiredBatchLookupPolicyTypeDef = TypedDict(
     "_RequiredBatchLookupPolicyTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchLookupPolicyTypeDef = TypedDict(
@@ -1125,21 +1520,19 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class BatchLookupPolicyTypeDef(
     _RequiredBatchLookupPolicyTypeDef, _OptionalBatchLookupPolicyTypeDef
 ):
     pass
 
-
 DeleteObjectRequestRequestTypeDef = TypedDict(
     "DeleteObjectRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -1182,21 +1575,41 @@
     "_OptionalGetObjectInformationRequestRequestTypeDef",
     {
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
-
 class GetObjectInformationRequestRequestTypeDef(
     _RequiredGetObjectInformationRequestRequestTypeDef,
     _OptionalGetObjectInformationRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef = TypedDict(
+    "_RequiredListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef",
+    {
+        "DirectoryArn": str,
+        "TargetReference": ObjectReferenceTypeDef,
+    },
+)
+_OptionalListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef = TypedDict(
+    "_OptionalListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef",
+    {
+        "ConsistencyLevel": ConsistencyLevelType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef(
+    _RequiredListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef,
+    _OptionalListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef,
+):
+    pass
 
 _RequiredListAttachedIndicesRequestRequestTypeDef = TypedDict(
     "_RequiredListAttachedIndicesRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "TargetReference": ObjectReferenceTypeDef,
     },
@@ -1207,22 +1620,20 @@
         "NextToken": str,
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
-
 class ListAttachedIndicesRequestRequestTypeDef(
     _RequiredListAttachedIndicesRequestRequestTypeDef,
     _OptionalListAttachedIndicesRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredListObjectChildrenRequestRequestTypeDef = TypedDict(
     "_RequiredListObjectChildrenRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -1232,21 +1643,40 @@
         "NextToken": str,
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
-
 class ListObjectChildrenRequestRequestTypeDef(
     _RequiredListObjectChildrenRequestRequestTypeDef,
     _OptionalListObjectChildrenRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef = TypedDict(
+    "_RequiredListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef",
+    {
+        "DirectoryArn": str,
+        "ObjectReference": ObjectReferenceTypeDef,
+    },
+)
+_OptionalListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef = TypedDict(
+    "_OptionalListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef(
+    _RequiredListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef,
+    _OptionalListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef,
+):
+    pass
 
 _RequiredListObjectParentPathsRequestRequestTypeDef = TypedDict(
     "_RequiredListObjectParentPathsRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
@@ -1256,22 +1686,20 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListObjectParentPathsRequestRequestTypeDef(
     _RequiredListObjectParentPathsRequestRequestTypeDef,
     _OptionalListObjectParentPathsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredListObjectParentsRequestRequestTypeDef = TypedDict(
     "_RequiredListObjectParentsRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -1282,20 +1710,40 @@
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
         "IncludeAllLinksToEachParent": bool,
     },
     total=False,
 )
 
-
 class ListObjectParentsRequestRequestTypeDef(
     _RequiredListObjectParentsRequestRequestTypeDef, _OptionalListObjectParentsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef",
+    {
+        "DirectoryArn": str,
+        "ObjectReference": ObjectReferenceTypeDef,
+    },
+)
+_OptionalListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef",
+    {
+        "ConsistencyLevel": ConsistencyLevelType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef(
+    _RequiredListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef,
+    _OptionalListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef,
+):
+    pass
 
 _RequiredListObjectPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListObjectPoliciesRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
@@ -1306,21 +1754,41 @@
         "NextToken": str,
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
-
 class ListObjectPoliciesRequestRequestTypeDef(
     _RequiredListObjectPoliciesRequestRequestTypeDef,
     _OptionalListObjectPoliciesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef = TypedDict(
+    "_RequiredListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef",
+    {
+        "DirectoryArn": str,
+        "PolicyReference": ObjectReferenceTypeDef,
+    },
+)
+_OptionalListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef = TypedDict(
+    "_OptionalListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef",
+    {
+        "ConsistencyLevel": ConsistencyLevelType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef(
+    _RequiredListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef,
+    _OptionalListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef,
+):
+    pass
 
 _RequiredListPolicyAttachmentsRequestRequestTypeDef = TypedDict(
     "_RequiredListPolicyAttachmentsRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "PolicyReference": ObjectReferenceTypeDef,
     },
@@ -1331,21 +1799,40 @@
         "NextToken": str,
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
-
 class ListPolicyAttachmentsRequestRequestTypeDef(
     _RequiredListPolicyAttachmentsRequestRequestTypeDef,
     _OptionalListPolicyAttachmentsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredLookupPolicyRequestLookupPolicyPaginateTypeDef = TypedDict(
+    "_RequiredLookupPolicyRequestLookupPolicyPaginateTypeDef",
+    {
+        "DirectoryArn": str,
+        "ObjectReference": ObjectReferenceTypeDef,
+    },
+)
+_OptionalLookupPolicyRequestLookupPolicyPaginateTypeDef = TypedDict(
+    "_OptionalLookupPolicyRequestLookupPolicyPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class LookupPolicyRequestLookupPolicyPaginateTypeDef(
+    _RequiredLookupPolicyRequestLookupPolicyPaginateTypeDef,
+    _OptionalLookupPolicyRequestLookupPolicyPaginateTypeDef,
+):
+    pass
 
 _RequiredLookupPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredLookupPolicyRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
@@ -1355,21 +1842,19 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class LookupPolicyRequestRequestTypeDef(
     _RequiredLookupPolicyRequestRequestTypeDef, _OptionalLookupPolicyRequestRequestTypeDef
 ):
     pass
 
-
 BatchGetObjectAttributesTypeDef = TypedDict(
     "BatchGetObjectAttributesTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
         "SchemaFacet": SchemaFacetTypeDef,
         "AttributeNames": Sequence[str],
     },
@@ -1396,21 +1881,19 @@
         "NextToken": str,
         "MaxResults": int,
         "FacetFilter": SchemaFacetTypeDef,
     },
     total=False,
 )
 
-
 class BatchListObjectAttributesTypeDef(
     _RequiredBatchListObjectAttributesTypeDef, _OptionalBatchListObjectAttributesTypeDef
 ):
     pass
 
-
 BatchRemoveFacetFromObjectTypeDef = TypedDict(
     "BatchRemoveFacetFromObjectTypeDef",
     {
         "SchemaFacet": SchemaFacetTypeDef,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -1428,21 +1911,51 @@
     "_OptionalGetObjectAttributesRequestRequestTypeDef",
     {
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
-
 class GetObjectAttributesRequestRequestTypeDef(
     _RequiredGetObjectAttributesRequestRequestTypeDef,
     _OptionalGetObjectAttributesRequestRequestTypeDef,
 ):
     pass
 
+GetObjectInformationResponseTypeDef = TypedDict(
+    "GetObjectInformationResponseTypeDef",
+    {
+        "SchemaFacets": List[SchemaFacetTypeDef],
+        "ObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListObjectAttributesRequestListObjectAttributesPaginateTypeDef = TypedDict(
+    "_RequiredListObjectAttributesRequestListObjectAttributesPaginateTypeDef",
+    {
+        "DirectoryArn": str,
+        "ObjectReference": ObjectReferenceTypeDef,
+    },
+)
+_OptionalListObjectAttributesRequestListObjectAttributesPaginateTypeDef = TypedDict(
+    "_OptionalListObjectAttributesRequestListObjectAttributesPaginateTypeDef",
+    {
+        "ConsistencyLevel": ConsistencyLevelType,
+        "FacetFilter": SchemaFacetTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListObjectAttributesRequestListObjectAttributesPaginateTypeDef(
+    _RequiredListObjectAttributesRequestListObjectAttributesPaginateTypeDef,
+    _OptionalListObjectAttributesRequestListObjectAttributesPaginateTypeDef,
+):
+    pass
 
 _RequiredListObjectAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredListObjectAttributesRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
@@ -1454,310 +1967,29 @@
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
         "FacetFilter": SchemaFacetTypeDef,
     },
     total=False,
 )
 
-
 class ListObjectAttributesRequestRequestTypeDef(
     _RequiredListObjectAttributesRequestRequestTypeDef,
     _OptionalListObjectAttributesRequestRequestTypeDef,
 ):
     pass
 
-
 RemoveFacetFromObjectRequestRequestTypeDef = TypedDict(
     "RemoveFacetFromObjectRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "SchemaFacet": SchemaFacetTypeDef,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 
-ApplySchemaResponseTypeDef = TypedDict(
-    "ApplySchemaResponseTypeDef",
-    {
-        "AppliedSchemaArn": str,
-        "DirectoryArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AttachObjectResponseTypeDef = TypedDict(
-    "AttachObjectResponseTypeDef",
-    {
-        "AttachedObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AttachToIndexResponseTypeDef = TypedDict(
-    "AttachToIndexResponseTypeDef",
-    {
-        "AttachedObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDirectoryResponseTypeDef = TypedDict(
-    "CreateDirectoryResponseTypeDef",
-    {
-        "DirectoryArn": str,
-        "Name": str,
-        "ObjectIdentifier": str,
-        "AppliedSchemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateIndexResponseTypeDef = TypedDict(
-    "CreateIndexResponseTypeDef",
-    {
-        "ObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateObjectResponseTypeDef = TypedDict(
-    "CreateObjectResponseTypeDef",
-    {
-        "ObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSchemaResponseTypeDef = TypedDict(
-    "CreateSchemaResponseTypeDef",
-    {
-        "SchemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDirectoryResponseTypeDef = TypedDict(
-    "DeleteDirectoryResponseTypeDef",
-    {
-        "DirectoryArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSchemaResponseTypeDef = TypedDict(
-    "DeleteSchemaResponseTypeDef",
-    {
-        "SchemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DetachFromIndexResponseTypeDef = TypedDict(
-    "DetachFromIndexResponseTypeDef",
-    {
-        "DetachedObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DetachObjectResponseTypeDef = TypedDict(
-    "DetachObjectResponseTypeDef",
-    {
-        "DetachedObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisableDirectoryResponseTypeDef = TypedDict(
-    "DisableDirectoryResponseTypeDef",
-    {
-        "DirectoryArn": str,
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
-EnableDirectoryResponseTypeDef = TypedDict(
-    "EnableDirectoryResponseTypeDef",
-    {
-        "DirectoryArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAppliedSchemaVersionResponseTypeDef = TypedDict(
-    "GetAppliedSchemaVersionResponseTypeDef",
-    {
-        "AppliedSchemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetObjectInformationResponseTypeDef = TypedDict(
-    "GetObjectInformationResponseTypeDef",
-    {
-        "SchemaFacets": List[SchemaFacetTypeDef],
-        "ObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSchemaAsJsonResponseTypeDef = TypedDict(
-    "GetSchemaAsJsonResponseTypeDef",
-    {
-        "Name": str,
-        "Document": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTypedLinkFacetInformationResponseTypeDef = TypedDict(
-    "GetTypedLinkFacetInformationResponseTypeDef",
-    {
-        "IdentityAttributeOrder": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAppliedSchemaArnsResponseTypeDef = TypedDict(
-    "ListAppliedSchemaArnsResponseTypeDef",
-    {
-        "SchemaArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDevelopmentSchemaArnsResponseTypeDef = TypedDict(
-    "ListDevelopmentSchemaArnsResponseTypeDef",
-    {
-        "SchemaArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFacetNamesResponseTypeDef = TypedDict(
-    "ListFacetNamesResponseTypeDef",
-    {
-        "FacetNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListManagedSchemaArnsResponseTypeDef = TypedDict(
-    "ListManagedSchemaArnsResponseTypeDef",
-    {
-        "SchemaArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListObjectChildrenResponseTypeDef = TypedDict(
-    "ListObjectChildrenResponseTypeDef",
-    {
-        "Children": Dict[str, str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListObjectPoliciesResponseTypeDef = TypedDict(
-    "ListObjectPoliciesResponseTypeDef",
-    {
-        "AttachedPolicyIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListPolicyAttachmentsResponseTypeDef = TypedDict(
-    "ListPolicyAttachmentsResponseTypeDef",
-    {
-        "ObjectIdentifiers": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListPublishedSchemaArnsResponseTypeDef = TypedDict(
-    "ListPublishedSchemaArnsResponseTypeDef",
-    {
-        "SchemaArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTypedLinkFacetNamesResponseTypeDef = TypedDict(
-    "ListTypedLinkFacetNamesResponseTypeDef",
-    {
-        "FacetNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PublishSchemaResponseTypeDef = TypedDict(
-    "PublishSchemaResponseTypeDef",
-    {
-        "PublishedSchemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutSchemaFromJsonResponseTypeDef = TypedDict(
-    "PutSchemaFromJsonResponseTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateObjectAttributesResponseTypeDef = TypedDict(
-    "UpdateObjectAttributesResponseTypeDef",
-    {
-        "ObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSchemaResponseTypeDef = TypedDict(
-    "UpdateSchemaResponseTypeDef",
-    {
-        "SchemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpgradeAppliedSchemaResponseTypeDef = TypedDict(
-    "UpgradeAppliedSchemaResponseTypeDef",
-    {
-        "UpgradedSchemaArn": str,
-        "DirectoryArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpgradePublishedSchemaResponseTypeDef = TypedDict(
-    "UpgradePublishedSchemaResponseTypeDef",
-    {
-        "UpgradedSchemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredBatchCreateIndexTypeDef = TypedDict(
     "_RequiredBatchCreateIndexTypeDef",
     {
         "OrderedIndexedAttributeList": Sequence[AttributeKeyTypeDef],
         "IsUnique": bool,
     },
 )
@@ -1767,19 +1999,17 @@
         "ParentReference": ObjectReferenceTypeDef,
         "LinkName": str,
         "BatchReferenceName": str,
     },
     total=False,
 )
 
-
 class BatchCreateIndexTypeDef(_RequiredBatchCreateIndexTypeDef, _OptionalBatchCreateIndexTypeDef):
     pass
 
-
 _RequiredCreateIndexRequestRequestTypeDef = TypedDict(
     "_RequiredCreateIndexRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "OrderedIndexedAttributeList": Sequence[AttributeKeyTypeDef],
         "IsUnique": bool,
     },
@@ -1789,21 +2019,19 @@
     {
         "ParentReference": ObjectReferenceTypeDef,
         "LinkName": str,
     },
     total=False,
 )
 
-
 class CreateIndexRequestRequestTypeDef(
     _RequiredCreateIndexRequestRequestTypeDef, _OptionalCreateIndexRequestRequestTypeDef
 ):
     pass
 
-
 AttributeKeyAndValueTypeDef = TypedDict(
     "AttributeKeyAndValueTypeDef",
     {
         "Key": AttributeKeyTypeDef,
         "Value": TypedAttributeValueTypeDef,
     },
 )
@@ -1846,36 +2074,34 @@
     {
         "StartValue": TypedAttributeValueTypeDef,
         "EndValue": TypedAttributeValueTypeDef,
     },
     total=False,
 )
 
-
 class TypedAttributeValueRangeTypeDef(
     _RequiredTypedAttributeValueRangeTypeDef, _OptionalTypedAttributeValueRangeTypeDef
 ):
     pass
 
-
 BatchListObjectParentPathsResponseTypeDef = TypedDict(
     "BatchListObjectParentPathsResponseTypeDef",
     {
         "PathToObjectIdentifiersList": List[PathToObjectIdentifiersTypeDef],
         "NextToken": str,
     },
     total=False,
 )
 
 ListObjectParentPathsResponseTypeDef = TypedDict(
     "ListObjectParentPathsResponseTypeDef",
     {
         "PathToObjectIdentifiersList": List[PathToObjectIdentifiersTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchListObjectParentsResponseTypeDef = TypedDict(
     "BatchListObjectParentsResponseTypeDef",
     {
         "ParentLinks": List[ObjectIdentifierAndLinkNameTupleTypeDef],
@@ -1886,32 +2112,32 @@
 
 ListObjectParentsResponseTypeDef = TypedDict(
     "ListObjectParentsResponseTypeDef",
     {
         "Parents": Dict[str, str],
         "NextToken": str,
         "ParentLinks": List[ObjectIdentifierAndLinkNameTupleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDirectoryResponseTypeDef = TypedDict(
     "GetDirectoryResponseTypeDef",
     {
         "Directory": DirectoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDirectoriesResponseTypeDef = TypedDict(
     "ListDirectoriesResponseTypeDef",
     {
         "Directories": List[DirectoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFacetAttributeDefinitionTypeDef = TypedDict(
     "_RequiredFacetAttributeDefinitionTypeDef",
     {
         "Type": FacetAttributeTypeType,
@@ -1923,21 +2149,19 @@
         "DefaultValue": TypedAttributeValueTypeDef,
         "IsImmutable": bool,
         "Rules": Mapping[str, RuleTypeDef],
     },
     total=False,
 )
 
-
 class FacetAttributeDefinitionTypeDef(
     _RequiredFacetAttributeDefinitionTypeDef, _OptionalFacetAttributeDefinitionTypeDef
 ):
     pass
 
-
 _RequiredTypedLinkAttributeDefinitionTypeDef = TypedDict(
     "_RequiredTypedLinkAttributeDefinitionTypeDef",
     {
         "Name": str,
         "Type": FacetAttributeTypeType,
         "RequiredBehavior": RequiredAttributeBehaviorType,
     },
@@ -1948,348 +2172,33 @@
         "DefaultValue": TypedAttributeValueTypeDef,
         "IsImmutable": bool,
         "Rules": Mapping[str, RuleTypeDef],
     },
     total=False,
 )
 
-
 class TypedLinkAttributeDefinitionTypeDef(
     _RequiredTypedLinkAttributeDefinitionTypeDef, _OptionalTypedLinkAttributeDefinitionTypeDef
 ):
     pass
 
-
 GetFacetResponseTypeDef = TypedDict(
     "GetFacetResponseTypeDef",
     {
         "Facet": FacetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef = TypedDict(
-    "_RequiredListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef",
-    {
-        "DirectoryArn": str,
-    },
-)
-_OptionalListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef = TypedDict(
-    "_OptionalListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef",
-    {
-        "SchemaArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef(
-    _RequiredListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef,
-    _OptionalListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef = TypedDict(
-    "_RequiredListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef",
-    {
-        "DirectoryArn": str,
-        "TargetReference": ObjectReferenceTypeDef,
-    },
-)
-_OptionalListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef = TypedDict(
-    "_OptionalListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef",
-    {
-        "ConsistencyLevel": ConsistencyLevelType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef(
-    _RequiredListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef,
-    _OptionalListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef,
-):
-    pass
-
-
-ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef = TypedDict(
-    "ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDirectoriesRequestListDirectoriesPaginateTypeDef = TypedDict(
-    "ListDirectoriesRequestListDirectoriesPaginateTypeDef",
-    {
-        "state": DirectoryStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListFacetAttributesRequestListFacetAttributesPaginateTypeDef = TypedDict(
-    "_RequiredListFacetAttributesRequestListFacetAttributesPaginateTypeDef",
-    {
-        "SchemaArn": str,
-        "Name": str,
-    },
-)
-_OptionalListFacetAttributesRequestListFacetAttributesPaginateTypeDef = TypedDict(
-    "_OptionalListFacetAttributesRequestListFacetAttributesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListFacetAttributesRequestListFacetAttributesPaginateTypeDef(
-    _RequiredListFacetAttributesRequestListFacetAttributesPaginateTypeDef,
-    _OptionalListFacetAttributesRequestListFacetAttributesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListFacetNamesRequestListFacetNamesPaginateTypeDef = TypedDict(
-    "_RequiredListFacetNamesRequestListFacetNamesPaginateTypeDef",
-    {
-        "SchemaArn": str,
-    },
-)
-_OptionalListFacetNamesRequestListFacetNamesPaginateTypeDef = TypedDict(
-    "_OptionalListFacetNamesRequestListFacetNamesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListFacetNamesRequestListFacetNamesPaginateTypeDef(
-    _RequiredListFacetNamesRequestListFacetNamesPaginateTypeDef,
-    _OptionalListFacetNamesRequestListFacetNamesPaginateTypeDef,
-):
-    pass
-
-
-ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef = TypedDict(
-    "ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef",
-    {
-        "SchemaArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListObjectAttributesRequestListObjectAttributesPaginateTypeDef = TypedDict(
-    "_RequiredListObjectAttributesRequestListObjectAttributesPaginateTypeDef",
-    {
-        "DirectoryArn": str,
-        "ObjectReference": ObjectReferenceTypeDef,
-    },
-)
-_OptionalListObjectAttributesRequestListObjectAttributesPaginateTypeDef = TypedDict(
-    "_OptionalListObjectAttributesRequestListObjectAttributesPaginateTypeDef",
-    {
-        "ConsistencyLevel": ConsistencyLevelType,
-        "FacetFilter": SchemaFacetTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListObjectAttributesRequestListObjectAttributesPaginateTypeDef(
-    _RequiredListObjectAttributesRequestListObjectAttributesPaginateTypeDef,
-    _OptionalListObjectAttributesRequestListObjectAttributesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef = TypedDict(
-    "_RequiredListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef",
-    {
-        "DirectoryArn": str,
-        "ObjectReference": ObjectReferenceTypeDef,
-    },
-)
-_OptionalListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef = TypedDict(
-    "_OptionalListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef(
-    _RequiredListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef,
-    _OptionalListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef",
-    {
-        "DirectoryArn": str,
-        "ObjectReference": ObjectReferenceTypeDef,
-    },
-)
-_OptionalListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef",
-    {
-        "ConsistencyLevel": ConsistencyLevelType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef(
-    _RequiredListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef,
-    _OptionalListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef = TypedDict(
-    "_RequiredListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef",
-    {
-        "DirectoryArn": str,
-        "PolicyReference": ObjectReferenceTypeDef,
-    },
-)
-_OptionalListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef = TypedDict(
-    "_OptionalListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef",
-    {
-        "ConsistencyLevel": ConsistencyLevelType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef(
-    _RequiredListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef,
-    _OptionalListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef,
-):
-    pass
-
-
-ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef = TypedDict(
-    "ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef",
-    {
-        "SchemaArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceArn": str,
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
-_RequiredListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef = TypedDict(
-    "_RequiredListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef",
-    {
-        "SchemaArn": str,
-        "Name": str,
-    },
-)
-_OptionalListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef = TypedDict(
-    "_OptionalListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef(
-    _RequiredListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef,
-    _OptionalListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef = TypedDict(
-    "_RequiredListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef",
-    {
-        "SchemaArn": str,
-    },
-)
-_OptionalListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef = TypedDict(
-    "_OptionalListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef(
-    _RequiredListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef,
-    _OptionalListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredLookupPolicyRequestLookupPolicyPaginateTypeDef = TypedDict(
-    "_RequiredLookupPolicyRequestLookupPolicyPaginateTypeDef",
-    {
-        "DirectoryArn": str,
-        "ObjectReference": ObjectReferenceTypeDef,
-    },
-)
-_OptionalLookupPolicyRequestLookupPolicyPaginateTypeDef = TypedDict(
-    "_OptionalLookupPolicyRequestLookupPolicyPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class LookupPolicyRequestLookupPolicyPaginateTypeDef(
-    _RequiredLookupPolicyRequestLookupPolicyPaginateTypeDef,
-    _OptionalLookupPolicyRequestLookupPolicyPaginateTypeDef,
-):
-    pass
-
-
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -2318,21 +2227,19 @@
     "_OptionalAddFacetToObjectRequestRequestTypeDef",
     {
         "ObjectAttributeList": Sequence[AttributeKeyAndValueTypeDef],
     },
     total=False,
 )
 
-
 class AddFacetToObjectRequestRequestTypeDef(
     _RequiredAddFacetToObjectRequestRequestTypeDef, _OptionalAddFacetToObjectRequestRequestTypeDef
 ):
     pass
 
-
 BatchAddFacetToObjectTypeDef = TypedDict(
     "BatchAddFacetToObjectTypeDef",
     {
         "SchemaFacet": SchemaFacetTypeDef,
         "ObjectAttributeList": Sequence[AttributeKeyAndValueTypeDef],
         "ObjectReference": ObjectReferenceTypeDef,
     },
@@ -2351,21 +2258,19 @@
         "ParentReference": ObjectReferenceTypeDef,
         "LinkName": str,
         "BatchReferenceName": str,
     },
     total=False,
 )
 
-
 class BatchCreateObjectTypeDef(
     _RequiredBatchCreateObjectTypeDef, _OptionalBatchCreateObjectTypeDef
 ):
     pass
 
-
 BatchGetLinkAttributesResponseTypeDef = TypedDict(
     "BatchGetLinkAttributesResponseTypeDef",
     {
         "Attributes": List[AttributeKeyAndValueTypeDef],
     },
     total=False,
 )
@@ -2400,34 +2305,32 @@
         "ObjectAttributeList": Sequence[AttributeKeyAndValueTypeDef],
         "ParentReference": ObjectReferenceTypeDef,
         "LinkName": str,
     },
     total=False,
 )
 
-
 class CreateObjectRequestRequestTypeDef(
     _RequiredCreateObjectRequestRequestTypeDef, _OptionalCreateObjectRequestRequestTypeDef
 ):
     pass
 
-
 GetLinkAttributesResponseTypeDef = TypedDict(
     "GetLinkAttributesResponseTypeDef",
     {
         "Attributes": List[AttributeKeyAndValueTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetObjectAttributesResponseTypeDef = TypedDict(
     "GetObjectAttributesResponseTypeDef",
     {
         "Attributes": List[AttributeKeyAndValueTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IndexAttachmentTypeDef = TypedDict(
     "IndexAttachmentTypeDef",
     {
         "IndexedAttributes": List[AttributeKeyAndValueTypeDef],
@@ -2437,15 +2340,15 @@
 )
 
 ListObjectAttributesResponseTypeDef = TypedDict(
     "ListObjectAttributesResponseTypeDef",
     {
         "Attributes": List[AttributeKeyAndValueTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachTypedLinkRequestRequestTypeDef = TypedDict(
     "AttachTypedLinkRequestRequestTypeDef",
     {
         "DirectoryArn": str,
@@ -2513,21 +2416,19 @@
     "_OptionalTypedLinkAttributeRangeTypeDef",
     {
         "AttributeName": str,
     },
     total=False,
 )
 
-
 class TypedLinkAttributeRangeTypeDef(
     _RequiredTypedLinkAttributeRangeTypeDef, _OptionalTypedLinkAttributeRangeTypeDef
 ):
     pass
 
-
 _RequiredFacetAttributeTypeDef = TypedDict(
     "_RequiredFacetAttributeTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalFacetAttributeTypeDef = TypedDict(
@@ -2536,25 +2437,23 @@
         "AttributeDefinition": FacetAttributeDefinitionTypeDef,
         "AttributeReference": FacetAttributeReferenceTypeDef,
         "RequiredBehavior": RequiredAttributeBehaviorType,
     },
     total=False,
 )
 
-
 class FacetAttributeTypeDef(_RequiredFacetAttributeTypeDef, _OptionalFacetAttributeTypeDef):
     pass
 
-
 ListTypedLinkFacetAttributesResponseTypeDef = TypedDict(
     "ListTypedLinkFacetAttributesResponseTypeDef",
     {
         "Attributes": List[TypedLinkAttributeDefinitionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TypedLinkFacetAttributeUpdateTypeDef = TypedDict(
     "TypedLinkFacetAttributeUpdateTypeDef",
     {
         "Attribute": TypedLinkAttributeDefinitionTypeDef,
@@ -2581,15 +2480,15 @@
 )
 
 LookupPolicyResponseTypeDef = TypedDict(
     "LookupPolicyResponseTypeDef",
     {
         "PolicyToPathList": List[PolicyToPathTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchListAttachedIndicesResponseTypeDef = TypedDict(
     "BatchListAttachedIndicesResponseTypeDef",
     {
         "IndexAttachments": List[IndexAttachmentTypeDef],
@@ -2608,32 +2507,32 @@
 )
 
 ListAttachedIndicesResponseTypeDef = TypedDict(
     "ListAttachedIndicesResponseTypeDef",
     {
         "IndexAttachments": List[IndexAttachmentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIndexResponseTypeDef = TypedDict(
     "ListIndexResponseTypeDef",
     {
         "IndexAttachments": List[IndexAttachmentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachTypedLinkResponseTypeDef = TypedDict(
     "AttachTypedLinkResponseTypeDef",
     {
         "TypedLinkSpecifier": TypedLinkSpecifierTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchAttachTypedLinkResponseTypeDef = TypedDict(
     "BatchAttachTypedLinkResponseTypeDef",
     {
         "TypedLinkSpecifier": TypedLinkSpecifierTypeDef,
@@ -2694,36 +2593,34 @@
     "_OptionalGetLinkAttributesRequestRequestTypeDef",
     {
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
-
 class GetLinkAttributesRequestRequestTypeDef(
     _RequiredGetLinkAttributesRequestRequestTypeDef, _OptionalGetLinkAttributesRequestRequestTypeDef
 ):
     pass
 
-
 ListIncomingTypedLinksResponseTypeDef = TypedDict(
     "ListIncomingTypedLinksResponseTypeDef",
     {
         "LinkSpecifiers": List[TypedLinkSpecifierTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOutgoingTypedLinksResponseTypeDef = TypedDict(
     "ListOutgoingTypedLinksResponseTypeDef",
     {
         "TypedLinkSpecifiers": List[TypedLinkSpecifierTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdateLinkAttributesTypeDef = TypedDict(
     "BatchUpdateLinkAttributesTypeDef",
     {
         "TypedLinkSpecifier": TypedLinkSpecifierTypeDef,
@@ -2769,44 +2666,40 @@
         "RangesOnIndexedValues": Sequence[ObjectAttributeRangeTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class BatchListIndexTypeDef(_RequiredBatchListIndexTypeDef, _OptionalBatchListIndexTypeDef):
     pass
 
-
 _RequiredListIndexRequestListIndexPaginateTypeDef = TypedDict(
     "_RequiredListIndexRequestListIndexPaginateTypeDef",
     {
         "DirectoryArn": str,
         "IndexReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalListIndexRequestListIndexPaginateTypeDef = TypedDict(
     "_OptionalListIndexRequestListIndexPaginateTypeDef",
     {
         "RangesOnIndexedValues": Sequence[ObjectAttributeRangeTypeDef],
         "ConsistencyLevel": ConsistencyLevelType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class ListIndexRequestListIndexPaginateTypeDef(
     _RequiredListIndexRequestListIndexPaginateTypeDef,
     _OptionalListIndexRequestListIndexPaginateTypeDef,
 ):
     pass
 
-
 _RequiredListIndexRequestRequestTypeDef = TypedDict(
     "_RequiredListIndexRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "IndexReference": ObjectReferenceTypeDef,
     },
 )
@@ -2817,21 +2710,19 @@
         "MaxResults": int,
         "NextToken": str,
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
-
 class ListIndexRequestRequestTypeDef(
     _RequiredListIndexRequestRequestTypeDef, _OptionalListIndexRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredBatchListIncomingTypedLinksTypeDef = TypedDict(
     "_RequiredBatchListIncomingTypedLinksTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchListIncomingTypedLinksTypeDef = TypedDict(
@@ -2841,21 +2732,19 @@
         "FilterTypedLink": TypedLinkSchemaAndFacetNameTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class BatchListIncomingTypedLinksTypeDef(
     _RequiredBatchListIncomingTypedLinksTypeDef, _OptionalBatchListIncomingTypedLinksTypeDef
 ):
     pass
 
-
 _RequiredBatchListOutgoingTypedLinksTypeDef = TypedDict(
     "_RequiredBatchListOutgoingTypedLinksTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchListOutgoingTypedLinksTypeDef = TypedDict(
@@ -2865,47 +2754,43 @@
         "FilterTypedLink": TypedLinkSchemaAndFacetNameTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class BatchListOutgoingTypedLinksTypeDef(
     _RequiredBatchListOutgoingTypedLinksTypeDef, _OptionalBatchListOutgoingTypedLinksTypeDef
 ):
     pass
 
-
 _RequiredListIncomingTypedLinksRequestListIncomingTypedLinksPaginateTypeDef = TypedDict(
     "_RequiredListIncomingTypedLinksRequestListIncomingTypedLinksPaginateTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalListIncomingTypedLinksRequestListIncomingTypedLinksPaginateTypeDef = TypedDict(
     "_OptionalListIncomingTypedLinksRequestListIncomingTypedLinksPaginateTypeDef",
     {
         "FilterAttributeRanges": Sequence[TypedLinkAttributeRangeTypeDef],
         "FilterTypedLink": TypedLinkSchemaAndFacetNameTypeDef,
         "ConsistencyLevel": ConsistencyLevelType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class ListIncomingTypedLinksRequestListIncomingTypedLinksPaginateTypeDef(
     _RequiredListIncomingTypedLinksRequestListIncomingTypedLinksPaginateTypeDef,
     _OptionalListIncomingTypedLinksRequestListIncomingTypedLinksPaginateTypeDef,
 ):
     pass
 
-
 _RequiredListIncomingTypedLinksRequestRequestTypeDef = TypedDict(
     "_RequiredListIncomingTypedLinksRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -2917,48 +2802,44 @@
         "NextToken": str,
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
-
 class ListIncomingTypedLinksRequestRequestTypeDef(
     _RequiredListIncomingTypedLinksRequestRequestTypeDef,
     _OptionalListIncomingTypedLinksRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredListOutgoingTypedLinksRequestListOutgoingTypedLinksPaginateTypeDef = TypedDict(
     "_RequiredListOutgoingTypedLinksRequestListOutgoingTypedLinksPaginateTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalListOutgoingTypedLinksRequestListOutgoingTypedLinksPaginateTypeDef = TypedDict(
     "_OptionalListOutgoingTypedLinksRequestListOutgoingTypedLinksPaginateTypeDef",
     {
         "FilterAttributeRanges": Sequence[TypedLinkAttributeRangeTypeDef],
         "FilterTypedLink": TypedLinkSchemaAndFacetNameTypeDef,
         "ConsistencyLevel": ConsistencyLevelType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class ListOutgoingTypedLinksRequestListOutgoingTypedLinksPaginateTypeDef(
     _RequiredListOutgoingTypedLinksRequestListOutgoingTypedLinksPaginateTypeDef,
     _OptionalListOutgoingTypedLinksRequestListOutgoingTypedLinksPaginateTypeDef,
 ):
     pass
 
-
 _RequiredListOutgoingTypedLinksRequestRequestTypeDef = TypedDict(
     "_RequiredListOutgoingTypedLinksRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -2970,22 +2851,20 @@
         "NextToken": str,
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
-
 class ListOutgoingTypedLinksRequestRequestTypeDef(
     _RequiredListOutgoingTypedLinksRequestRequestTypeDef,
     _OptionalListOutgoingTypedLinksRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateFacetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFacetRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Name": str,
     },
 )
@@ -2995,36 +2874,34 @@
         "Attributes": Sequence[FacetAttributeTypeDef],
         "ObjectType": ObjectTypeType,
         "FacetStyle": FacetStyleType,
     },
     total=False,
 )
 
-
 class CreateFacetRequestRequestTypeDef(
     _RequiredCreateFacetRequestRequestTypeDef, _OptionalCreateFacetRequestRequestTypeDef
 ):
     pass
 
-
 FacetAttributeUpdateTypeDef = TypedDict(
     "FacetAttributeUpdateTypeDef",
     {
         "Attribute": FacetAttributeTypeDef,
         "Action": UpdateActionTypeType,
     },
     total=False,
 )
 
 ListFacetAttributesResponseTypeDef = TypedDict(
     "ListFacetAttributesResponseTypeDef",
     {
         "Attributes": List[FacetAttributeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTypedLinkFacetRequestRequestTypeDef = TypedDict(
     "UpdateTypedLinkFacetRequestRequestTypeDef",
     {
         "SchemaArn": str,
@@ -3140,26 +3017,24 @@
     {
         "AttributeUpdates": Sequence[FacetAttributeUpdateTypeDef],
         "ObjectType": ObjectTypeType,
     },
     total=False,
 )
 
-
 class UpdateFacetRequestRequestTypeDef(
     _RequiredUpdateFacetRequestRequestTypeDef, _OptionalUpdateFacetRequestRequestTypeDef
 ):
     pass
 
-
 BatchWriteResponseTypeDef = TypedDict(
     "BatchWriteResponseTypeDef",
     {
         "Responses": List[BatchWriteOperationResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchReadOperationResponseTypeDef = TypedDict(
     "BatchReadOperationResponseTypeDef",
     {
         "SuccessfulResponse": BatchReadSuccessfulResponseTypeDef,
@@ -3187,21 +3062,19 @@
     "_OptionalBatchReadRequestRequestTypeDef",
     {
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
-
 class BatchReadRequestRequestTypeDef(
     _RequiredBatchReadRequestRequestTypeDef, _OptionalBatchReadRequestRequestTypeDef
 ):
     pass
 
-
 BatchReadResponseTypeDef = TypedDict(
     "BatchReadResponseTypeDef",
     {
         "Responses": List[BatchReadOperationResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory/type_defs.pyi` & `types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory/type_defs.py`

 * *Files 8% similar despite different names*

```diff
@@ -31,19 +31,22 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ObjectReferenceTypeDef",
     "SchemaFacetTypeDef",
     "ApplySchemaRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "ApplySchemaResponseTypeDef",
+    "AttachObjectResponseTypeDef",
+    "AttachToIndexResponseTypeDef",
     "TypedLinkSchemaAndFacetNameTypeDef",
     "AttributeKeyTypeDef",
     "TypedAttributeValueTypeDef",
     "BatchAttachObjectResponseTypeDef",
     "BatchAttachToIndexResponseTypeDef",
     "BatchCreateIndexResponseTypeDef",
     "BatchCreateObjectResponseTypeDef",
@@ -53,49 +56,89 @@
     "PathToObjectIdentifiersTypeDef",
     "ObjectIdentifierAndLinkNameTupleTypeDef",
     "BatchListObjectPoliciesResponseTypeDef",
     "BatchListPolicyAttachmentsResponseTypeDef",
     "BatchReadExceptionTypeDef",
     "BatchUpdateObjectAttributesResponseTypeDef",
     "CreateDirectoryRequestRequestTypeDef",
+    "CreateDirectoryResponseTypeDef",
+    "CreateIndexResponseTypeDef",
+    "CreateObjectResponseTypeDef",
     "CreateSchemaRequestRequestTypeDef",
+    "CreateSchemaResponseTypeDef",
     "DeleteDirectoryRequestRequestTypeDef",
+    "DeleteDirectoryResponseTypeDef",
     "DeleteFacetRequestRequestTypeDef",
     "DeleteSchemaRequestRequestTypeDef",
+    "DeleteSchemaResponseTypeDef",
     "DeleteTypedLinkFacetRequestRequestTypeDef",
+    "DetachFromIndexResponseTypeDef",
+    "DetachObjectResponseTypeDef",
     "DirectoryTypeDef",
     "DisableDirectoryRequestRequestTypeDef",
+    "DisableDirectoryResponseTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableDirectoryRequestRequestTypeDef",
+    "EnableDirectoryResponseTypeDef",
     "RuleTypeDef",
     "FacetAttributeReferenceTypeDef",
     "FacetTypeDef",
     "GetAppliedSchemaVersionRequestRequestTypeDef",
+    "GetAppliedSchemaVersionResponseTypeDef",
     "GetDirectoryRequestRequestTypeDef",
     "GetFacetRequestRequestTypeDef",
     "GetSchemaAsJsonRequestRequestTypeDef",
+    "GetSchemaAsJsonResponseTypeDef",
     "GetTypedLinkFacetInformationRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetTypedLinkFacetInformationResponseTypeDef",
+    "ListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef",
     "ListAppliedSchemaArnsRequestRequestTypeDef",
+    "ListAppliedSchemaArnsResponseTypeDef",
+    "ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef",
     "ListDevelopmentSchemaArnsRequestRequestTypeDef",
+    "ListDevelopmentSchemaArnsResponseTypeDef",
+    "ListDirectoriesRequestListDirectoriesPaginateTypeDef",
     "ListDirectoriesRequestRequestTypeDef",
+    "ListFacetAttributesRequestListFacetAttributesPaginateTypeDef",
     "ListFacetAttributesRequestRequestTypeDef",
+    "ListFacetNamesRequestListFacetNamesPaginateTypeDef",
     "ListFacetNamesRequestRequestTypeDef",
+    "ListFacetNamesResponseTypeDef",
+    "ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef",
     "ListManagedSchemaArnsRequestRequestTypeDef",
+    "ListManagedSchemaArnsResponseTypeDef",
+    "ListObjectChildrenResponseTypeDef",
+    "ListObjectPoliciesResponseTypeDef",
+    "ListPolicyAttachmentsResponseTypeDef",
+    "ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef",
     "ListPublishedSchemaArnsRequestRequestTypeDef",
+    "ListPublishedSchemaArnsResponseTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
+    "ListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef",
     "ListTypedLinkFacetAttributesRequestRequestTypeDef",
+    "ListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef",
     "ListTypedLinkFacetNamesRequestRequestTypeDef",
+    "ListTypedLinkFacetNamesResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PolicyAttachmentTypeDef",
     "PublishSchemaRequestRequestTypeDef",
+    "PublishSchemaResponseTypeDef",
     "PutSchemaFromJsonRequestRequestTypeDef",
+    "PutSchemaFromJsonResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateObjectAttributesResponseTypeDef",
     "UpdateSchemaRequestRequestTypeDef",
+    "UpdateSchemaResponseTypeDef",
     "UpgradeAppliedSchemaRequestRequestTypeDef",
+    "UpgradeAppliedSchemaResponseTypeDef",
     "UpgradePublishedSchemaRequestRequestTypeDef",
+    "UpgradePublishedSchemaResponseTypeDef",
     "AttachObjectRequestRequestTypeDef",
     "AttachPolicyRequestRequestTypeDef",
     "AttachToIndexRequestRequestTypeDef",
     "BatchAttachObjectTypeDef",
     "BatchAttachPolicyTypeDef",
     "BatchAttachToIndexTypeDef",
     "BatchDeleteObjectTypeDef",
@@ -111,61 +154,35 @@
     "BatchListPolicyAttachmentsTypeDef",
     "BatchLookupPolicyTypeDef",
     "DeleteObjectRequestRequestTypeDef",
     "DetachFromIndexRequestRequestTypeDef",
     "DetachObjectRequestRequestTypeDef",
     "DetachPolicyRequestRequestTypeDef",
     "GetObjectInformationRequestRequestTypeDef",
+    "ListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef",
     "ListAttachedIndicesRequestRequestTypeDef",
     "ListObjectChildrenRequestRequestTypeDef",
+    "ListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef",
     "ListObjectParentPathsRequestRequestTypeDef",
     "ListObjectParentsRequestRequestTypeDef",
+    "ListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef",
     "ListObjectPoliciesRequestRequestTypeDef",
+    "ListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef",
     "ListPolicyAttachmentsRequestRequestTypeDef",
+    "LookupPolicyRequestLookupPolicyPaginateTypeDef",
     "LookupPolicyRequestRequestTypeDef",
     "BatchGetObjectAttributesTypeDef",
     "BatchGetObjectInformationResponseTypeDef",
     "BatchListObjectAttributesTypeDef",
     "BatchRemoveFacetFromObjectTypeDef",
     "GetObjectAttributesRequestRequestTypeDef",
+    "GetObjectInformationResponseTypeDef",
+    "ListObjectAttributesRequestListObjectAttributesPaginateTypeDef",
     "ListObjectAttributesRequestRequestTypeDef",
     "RemoveFacetFromObjectRequestRequestTypeDef",
-    "ApplySchemaResponseTypeDef",
-    "AttachObjectResponseTypeDef",
-    "AttachToIndexResponseTypeDef",
-    "CreateDirectoryResponseTypeDef",
-    "CreateIndexResponseTypeDef",
-    "CreateObjectResponseTypeDef",
-    "CreateSchemaResponseTypeDef",
-    "DeleteDirectoryResponseTypeDef",
-    "DeleteSchemaResponseTypeDef",
-    "DetachFromIndexResponseTypeDef",
-    "DetachObjectResponseTypeDef",
-    "DisableDirectoryResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "EnableDirectoryResponseTypeDef",
-    "GetAppliedSchemaVersionResponseTypeDef",
-    "GetObjectInformationResponseTypeDef",
-    "GetSchemaAsJsonResponseTypeDef",
-    "GetTypedLinkFacetInformationResponseTypeDef",
-    "ListAppliedSchemaArnsResponseTypeDef",
-    "ListDevelopmentSchemaArnsResponseTypeDef",
-    "ListFacetNamesResponseTypeDef",
-    "ListManagedSchemaArnsResponseTypeDef",
-    "ListObjectChildrenResponseTypeDef",
-    "ListObjectPoliciesResponseTypeDef",
-    "ListPolicyAttachmentsResponseTypeDef",
-    "ListPublishedSchemaArnsResponseTypeDef",
-    "ListTypedLinkFacetNamesResponseTypeDef",
-    "PublishSchemaResponseTypeDef",
-    "PutSchemaFromJsonResponseTypeDef",
-    "UpdateObjectAttributesResponseTypeDef",
-    "UpdateSchemaResponseTypeDef",
-    "UpgradeAppliedSchemaResponseTypeDef",
-    "UpgradePublishedSchemaResponseTypeDef",
     "BatchCreateIndexTypeDef",
     "CreateIndexRequestRequestTypeDef",
     "AttributeKeyAndValueTypeDef",
     "AttributeNameAndValueTypeDef",
     "LinkAttributeActionTypeDef",
     "ObjectAttributeActionTypeDef",
     "TypedAttributeValueRangeTypeDef",
@@ -174,30 +191,14 @@
     "BatchListObjectParentsResponseTypeDef",
     "ListObjectParentsResponseTypeDef",
     "GetDirectoryResponseTypeDef",
     "ListDirectoriesResponseTypeDef",
     "FacetAttributeDefinitionTypeDef",
     "TypedLinkAttributeDefinitionTypeDef",
     "GetFacetResponseTypeDef",
-    "ListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef",
-    "ListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef",
-    "ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef",
-    "ListDirectoriesRequestListDirectoriesPaginateTypeDef",
-    "ListFacetAttributesRequestListFacetAttributesPaginateTypeDef",
-    "ListFacetNamesRequestListFacetNamesPaginateTypeDef",
-    "ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef",
-    "ListObjectAttributesRequestListObjectAttributesPaginateTypeDef",
-    "ListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef",
-    "ListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef",
-    "ListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef",
-    "ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    "ListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef",
-    "ListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef",
-    "LookupPolicyRequestLookupPolicyPaginateTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "PolicyToPathTypeDef",
     "AddFacetToObjectRequestRequestTypeDef",
     "BatchAddFacetToObjectTypeDef",
     "BatchCreateObjectTypeDef",
     "BatchGetLinkAttributesResponseTypeDef",
@@ -286,22 +287,36 @@
     "ApplySchemaRequestRequestTypeDef",
     {
         "PublishedSchemaArn": str,
         "DirectoryArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ApplySchemaResponseTypeDef = TypedDict(
+    "ApplySchemaResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AppliedSchemaArn": str,
+        "DirectoryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AttachObjectResponseTypeDef = TypedDict(
+    "AttachObjectResponseTypeDef",
+    {
+        "AttachedObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AttachToIndexResponseTypeDef = TypedDict(
+    "AttachToIndexResponseTypeDef",
+    {
+        "AttachedObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TypedLinkSchemaAndFacetNameTypeDef = TypedDict(
     "TypedLinkSchemaAndFacetNameTypeDef",
     {
         "SchemaArn": str,
@@ -444,28 +459,71 @@
     "CreateDirectoryRequestRequestTypeDef",
     {
         "Name": str,
         "SchemaArn": str,
     },
 )
 
+CreateDirectoryResponseTypeDef = TypedDict(
+    "CreateDirectoryResponseTypeDef",
+    {
+        "DirectoryArn": str,
+        "Name": str,
+        "ObjectIdentifier": str,
+        "AppliedSchemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateIndexResponseTypeDef = TypedDict(
+    "CreateIndexResponseTypeDef",
+    {
+        "ObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateObjectResponseTypeDef = TypedDict(
+    "CreateObjectResponseTypeDef",
+    {
+        "ObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateSchemaRequestRequestTypeDef = TypedDict(
     "CreateSchemaRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+CreateSchemaResponseTypeDef = TypedDict(
+    "CreateSchemaResponseTypeDef",
+    {
+        "SchemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDirectoryRequestRequestTypeDef = TypedDict(
     "DeleteDirectoryRequestRequestTypeDef",
     {
         "DirectoryArn": str,
     },
 )
 
+DeleteDirectoryResponseTypeDef = TypedDict(
+    "DeleteDirectoryResponseTypeDef",
+    {
+        "DirectoryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteFacetRequestRequestTypeDef = TypedDict(
     "DeleteFacetRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Name": str,
     },
 )
@@ -473,22 +531,46 @@
 DeleteSchemaRequestRequestTypeDef = TypedDict(
     "DeleteSchemaRequestRequestTypeDef",
     {
         "SchemaArn": str,
     },
 )
 
+DeleteSchemaResponseTypeDef = TypedDict(
+    "DeleteSchemaResponseTypeDef",
+    {
+        "SchemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteTypedLinkFacetRequestRequestTypeDef = TypedDict(
     "DeleteTypedLinkFacetRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Name": str,
     },
 )
 
+DetachFromIndexResponseTypeDef = TypedDict(
+    "DetachFromIndexResponseTypeDef",
+    {
+        "DetachedObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DetachObjectResponseTypeDef = TypedDict(
+    "DetachObjectResponseTypeDef",
+    {
+        "DetachedObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DirectoryTypeDef = TypedDict(
     "DirectoryTypeDef",
     {
         "Name": str,
         "DirectoryArn": str,
         "State": DirectoryStateType,
         "CreationDateTime": datetime,
@@ -499,21 +581,44 @@
 DisableDirectoryRequestRequestTypeDef = TypedDict(
     "DisableDirectoryRequestRequestTypeDef",
     {
         "DirectoryArn": str,
     },
 )
 
+DisableDirectoryResponseTypeDef = TypedDict(
+    "DisableDirectoryResponseTypeDef",
+    {
+        "DirectoryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableDirectoryRequestRequestTypeDef = TypedDict(
     "EnableDirectoryRequestRequestTypeDef",
     {
         "DirectoryArn": str,
     },
 )
 
+EnableDirectoryResponseTypeDef = TypedDict(
+    "EnableDirectoryResponseTypeDef",
+    {
+        "DirectoryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RuleTypeDef = TypedDict(
     "RuleTypeDef",
     {
         "Type": RuleTypeType,
         "Parameters": Mapping[str, str],
     },
     total=False,
@@ -540,14 +645,22 @@
 GetAppliedSchemaVersionRequestRequestTypeDef = TypedDict(
     "GetAppliedSchemaVersionRequestRequestTypeDef",
     {
         "SchemaArn": str,
     },
 )
 
+GetAppliedSchemaVersionResponseTypeDef = TypedDict(
+    "GetAppliedSchemaVersionResponseTypeDef",
+    {
+        "AppliedSchemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDirectoryRequestRequestTypeDef = TypedDict(
     "GetDirectoryRequestRequestTypeDef",
     {
         "DirectoryArn": str,
     },
 )
 
@@ -562,32 +675,62 @@
 GetSchemaAsJsonRequestRequestTypeDef = TypedDict(
     "GetSchemaAsJsonRequestRequestTypeDef",
     {
         "SchemaArn": str,
     },
 )
 
+GetSchemaAsJsonResponseTypeDef = TypedDict(
+    "GetSchemaAsJsonResponseTypeDef",
+    {
+        "Name": str,
+        "Document": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTypedLinkFacetInformationRequestRequestTypeDef = TypedDict(
     "GetTypedLinkFacetInformationRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Name": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetTypedLinkFacetInformationResponseTypeDef = TypedDict(
+    "GetTypedLinkFacetInformationResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "IdentityAttributeOrder": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef = TypedDict(
+    "_RequiredListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef",
+    {
+        "DirectoryArn": str,
+    },
+)
+_OptionalListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef = TypedDict(
+    "_OptionalListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef",
+    {
+        "SchemaArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef(
+    _RequiredListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef,
+    _OptionalListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAppliedSchemaArnsRequestRequestTypeDef = TypedDict(
     "_RequiredListAppliedSchemaArnsRequestRequestTypeDef",
     {
         "DirectoryArn": str,
     },
 )
 _OptionalListAppliedSchemaArnsRequestRequestTypeDef = TypedDict(
@@ -596,39 +739,99 @@
         "SchemaArn": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListAppliedSchemaArnsRequestRequestTypeDef(
     _RequiredListAppliedSchemaArnsRequestRequestTypeDef,
     _OptionalListAppliedSchemaArnsRequestRequestTypeDef,
 ):
     pass
 
+
+ListAppliedSchemaArnsResponseTypeDef = TypedDict(
+    "ListAppliedSchemaArnsResponseTypeDef",
+    {
+        "SchemaArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef = TypedDict(
+    "ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDevelopmentSchemaArnsRequestRequestTypeDef = TypedDict(
     "ListDevelopmentSchemaArnsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListDevelopmentSchemaArnsResponseTypeDef = TypedDict(
+    "ListDevelopmentSchemaArnsResponseTypeDef",
+    {
+        "SchemaArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDirectoriesRequestListDirectoriesPaginateTypeDef = TypedDict(
+    "ListDirectoriesRequestListDirectoriesPaginateTypeDef",
+    {
+        "state": DirectoryStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDirectoriesRequestRequestTypeDef = TypedDict(
     "ListDirectoriesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "state": DirectoryStateType,
     },
     total=False,
 )
 
+_RequiredListFacetAttributesRequestListFacetAttributesPaginateTypeDef = TypedDict(
+    "_RequiredListFacetAttributesRequestListFacetAttributesPaginateTypeDef",
+    {
+        "SchemaArn": str,
+        "Name": str,
+    },
+)
+_OptionalListFacetAttributesRequestListFacetAttributesPaginateTypeDef = TypedDict(
+    "_OptionalListFacetAttributesRequestListFacetAttributesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListFacetAttributesRequestListFacetAttributesPaginateTypeDef(
+    _RequiredListFacetAttributesRequestListFacetAttributesPaginateTypeDef,
+    _OptionalListFacetAttributesRequestListFacetAttributesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListFacetAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredListFacetAttributesRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Name": str,
     },
 )
@@ -637,20 +840,44 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListFacetAttributesRequestRequestTypeDef(
     _RequiredListFacetAttributesRequestRequestTypeDef,
     _OptionalListFacetAttributesRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredListFacetNamesRequestListFacetNamesPaginateTypeDef = TypedDict(
+    "_RequiredListFacetNamesRequestListFacetNamesPaginateTypeDef",
+    {
+        "SchemaArn": str,
+    },
+)
+_OptionalListFacetNamesRequestListFacetNamesPaginateTypeDef = TypedDict(
+    "_OptionalListFacetNamesRequestListFacetNamesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListFacetNamesRequestListFacetNamesPaginateTypeDef(
+    _RequiredListFacetNamesRequestListFacetNamesPaginateTypeDef,
+    _OptionalListFacetNamesRequestListFacetNamesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListFacetNamesRequestRequestTypeDef = TypedDict(
     "_RequiredListFacetNamesRequestRequestTypeDef",
     {
         "SchemaArn": str,
     },
 )
 _OptionalListFacetNamesRequestRequestTypeDef = TypedDict(
@@ -658,39 +885,135 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListFacetNamesRequestRequestTypeDef(
     _RequiredListFacetNamesRequestRequestTypeDef, _OptionalListFacetNamesRequestRequestTypeDef
 ):
     pass
 
+
+ListFacetNamesResponseTypeDef = TypedDict(
+    "ListFacetNamesResponseTypeDef",
+    {
+        "FacetNames": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef = TypedDict(
+    "ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef",
+    {
+        "SchemaArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListManagedSchemaArnsRequestRequestTypeDef = TypedDict(
     "ListManagedSchemaArnsRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListManagedSchemaArnsResponseTypeDef = TypedDict(
+    "ListManagedSchemaArnsResponseTypeDef",
+    {
+        "SchemaArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListObjectChildrenResponseTypeDef = TypedDict(
+    "ListObjectChildrenResponseTypeDef",
+    {
+        "Children": Dict[str, str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListObjectPoliciesResponseTypeDef = TypedDict(
+    "ListObjectPoliciesResponseTypeDef",
+    {
+        "AttachedPolicyIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListPolicyAttachmentsResponseTypeDef = TypedDict(
+    "ListPolicyAttachmentsResponseTypeDef",
+    {
+        "ObjectIdentifiers": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef = TypedDict(
+    "ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef",
+    {
+        "SchemaArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPublishedSchemaArnsRequestRequestTypeDef = TypedDict(
     "ListPublishedSchemaArnsRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListPublishedSchemaArnsResponseTypeDef = TypedDict(
+    "ListPublishedSchemaArnsResponseTypeDef",
+    {
+        "SchemaArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceArn": str,
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
         "ResourceArn": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -698,29 +1021,54 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
     total=False,
 )
 
+_RequiredListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef = TypedDict(
+    "_RequiredListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef",
+    {
+        "SchemaArn": str,
+        "Name": str,
+    },
+)
+_OptionalListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef = TypedDict(
+    "_OptionalListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef(
+    _RequiredListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef,
+    _OptionalListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTypedLinkFacetAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredListTypedLinkFacetAttributesRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Name": str,
     },
 )
@@ -729,20 +1077,44 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListTypedLinkFacetAttributesRequestRequestTypeDef(
     _RequiredListTypedLinkFacetAttributesRequestRequestTypeDef,
     _OptionalListTypedLinkFacetAttributesRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef = TypedDict(
+    "_RequiredListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef",
+    {
+        "SchemaArn": str,
+    },
+)
+_OptionalListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef = TypedDict(
+    "_OptionalListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef(
+    _RequiredListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef,
+    _OptionalListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTypedLinkFacetNamesRequestRequestTypeDef = TypedDict(
     "_RequiredListTypedLinkFacetNamesRequestRequestTypeDef",
     {
         "SchemaArn": str,
     },
 )
 _OptionalListTypedLinkFacetNamesRequestRequestTypeDef = TypedDict(
@@ -750,20 +1122,41 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListTypedLinkFacetNamesRequestRequestTypeDef(
     _RequiredListTypedLinkFacetNamesRequestRequestTypeDef,
     _OptionalListTypedLinkFacetNamesRequestRequestTypeDef,
 ):
     pass
 
+
+ListTypedLinkFacetNamesResponseTypeDef = TypedDict(
+    "ListTypedLinkFacetNamesResponseTypeDef",
+    {
+        "FacetNames": List[str],
+        "NextToken": str,
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
 PolicyAttachmentTypeDef = TypedDict(
     "PolicyAttachmentTypeDef",
     {
         "PolicyId": str,
         "ObjectIdentifier": str,
         "PolicyType": str,
     },
@@ -782,43 +1175,88 @@
     {
         "MinorVersion": str,
         "Name": str,
     },
     total=False,
 )
 
+
 class PublishSchemaRequestRequestTypeDef(
     _RequiredPublishSchemaRequestRequestTypeDef, _OptionalPublishSchemaRequestRequestTypeDef
 ):
     pass
 
+
+PublishSchemaResponseTypeDef = TypedDict(
+    "PublishSchemaResponseTypeDef",
+    {
+        "PublishedSchemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutSchemaFromJsonRequestRequestTypeDef = TypedDict(
     "PutSchemaFromJsonRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Document": str,
     },
 )
 
+PutSchemaFromJsonResponseTypeDef = TypedDict(
+    "PutSchemaFromJsonResponseTypeDef",
+    {
+        "Arn": str,
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateObjectAttributesResponseTypeDef = TypedDict(
+    "UpdateObjectAttributesResponseTypeDef",
+    {
+        "ObjectIdentifier": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateSchemaRequestRequestTypeDef = TypedDict(
     "UpdateSchemaRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Name": str,
     },
 )
 
+UpdateSchemaResponseTypeDef = TypedDict(
+    "UpdateSchemaResponseTypeDef",
+    {
+        "SchemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpgradeAppliedSchemaRequestRequestTypeDef = TypedDict(
     "_RequiredUpgradeAppliedSchemaRequestRequestTypeDef",
     {
         "PublishedSchemaArn": str,
         "DirectoryArn": str,
     },
 )
@@ -826,20 +1264,31 @@
     "_OptionalUpgradeAppliedSchemaRequestRequestTypeDef",
     {
         "DryRun": bool,
     },
     total=False,
 )
 
+
 class UpgradeAppliedSchemaRequestRequestTypeDef(
     _RequiredUpgradeAppliedSchemaRequestRequestTypeDef,
     _OptionalUpgradeAppliedSchemaRequestRequestTypeDef,
 ):
     pass
 
+
+UpgradeAppliedSchemaResponseTypeDef = TypedDict(
+    "UpgradeAppliedSchemaResponseTypeDef",
+    {
+        "UpgradedSchemaArn": str,
+        "DirectoryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpgradePublishedSchemaRequestRequestTypeDef = TypedDict(
     "_RequiredUpgradePublishedSchemaRequestRequestTypeDef",
     {
         "DevelopmentSchemaArn": str,
         "PublishedSchemaArn": str,
         "MinorVersion": str,
     },
@@ -848,20 +1297,30 @@
     "_OptionalUpgradePublishedSchemaRequestRequestTypeDef",
     {
         "DryRun": bool,
     },
     total=False,
 )
 
+
 class UpgradePublishedSchemaRequestRequestTypeDef(
     _RequiredUpgradePublishedSchemaRequestRequestTypeDef,
     _OptionalUpgradePublishedSchemaRequestRequestTypeDef,
 ):
     pass
 
+
+UpgradePublishedSchemaResponseTypeDef = TypedDict(
+    "UpgradePublishedSchemaResponseTypeDef",
+    {
+        "UpgradedSchemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AttachObjectRequestRequestTypeDef = TypedDict(
     "AttachObjectRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ParentReference": ObjectReferenceTypeDef,
         "ChildReference": ObjectReferenceTypeDef,
         "LinkName": str,
@@ -937,19 +1396,21 @@
     "_OptionalBatchDetachObjectTypeDef",
     {
         "BatchReferenceName": str,
     },
     total=False,
 )
 
+
 class BatchDetachObjectTypeDef(
     _RequiredBatchDetachObjectTypeDef, _OptionalBatchDetachObjectTypeDef
 ):
     pass
 
+
 BatchDetachPolicyTypeDef = TypedDict(
     "BatchDetachPolicyTypeDef",
     {
         "PolicyReference": ObjectReferenceTypeDef,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -972,19 +1433,21 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class BatchListAttachedIndicesTypeDef(
     _RequiredBatchListAttachedIndicesTypeDef, _OptionalBatchListAttachedIndicesTypeDef
 ):
     pass
 
+
 _RequiredBatchListObjectChildrenTypeDef = TypedDict(
     "_RequiredBatchListObjectChildrenTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchListObjectChildrenTypeDef = TypedDict(
@@ -992,19 +1455,21 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class BatchListObjectChildrenTypeDef(
     _RequiredBatchListObjectChildrenTypeDef, _OptionalBatchListObjectChildrenTypeDef
 ):
     pass
 
+
 _RequiredBatchListObjectParentPathsTypeDef = TypedDict(
     "_RequiredBatchListObjectParentPathsTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchListObjectParentPathsTypeDef = TypedDict(
@@ -1012,19 +1477,21 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class BatchListObjectParentPathsTypeDef(
     _RequiredBatchListObjectParentPathsTypeDef, _OptionalBatchListObjectParentPathsTypeDef
 ):
     pass
 
+
 _RequiredBatchListObjectParentsTypeDef = TypedDict(
     "_RequiredBatchListObjectParentsTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchListObjectParentsTypeDef = TypedDict(
@@ -1032,19 +1499,21 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class BatchListObjectParentsTypeDef(
     _RequiredBatchListObjectParentsTypeDef, _OptionalBatchListObjectParentsTypeDef
 ):
     pass
 
+
 _RequiredBatchListObjectPoliciesTypeDef = TypedDict(
     "_RequiredBatchListObjectPoliciesTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchListObjectPoliciesTypeDef = TypedDict(
@@ -1052,19 +1521,21 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class BatchListObjectPoliciesTypeDef(
     _RequiredBatchListObjectPoliciesTypeDef, _OptionalBatchListObjectPoliciesTypeDef
 ):
     pass
 
+
 _RequiredBatchListPolicyAttachmentsTypeDef = TypedDict(
     "_RequiredBatchListPolicyAttachmentsTypeDef",
     {
         "PolicyReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchListPolicyAttachmentsTypeDef = TypedDict(
@@ -1072,19 +1543,21 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class BatchListPolicyAttachmentsTypeDef(
     _RequiredBatchListPolicyAttachmentsTypeDef, _OptionalBatchListPolicyAttachmentsTypeDef
 ):
     pass
 
+
 _RequiredBatchLookupPolicyTypeDef = TypedDict(
     "_RequiredBatchLookupPolicyTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchLookupPolicyTypeDef = TypedDict(
@@ -1092,19 +1565,21 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class BatchLookupPolicyTypeDef(
     _RequiredBatchLookupPolicyTypeDef, _OptionalBatchLookupPolicyTypeDef
 ):
     pass
 
+
 DeleteObjectRequestRequestTypeDef = TypedDict(
     "DeleteObjectRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -1147,20 +1622,46 @@
     "_OptionalGetObjectInformationRequestRequestTypeDef",
     {
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
+
 class GetObjectInformationRequestRequestTypeDef(
     _RequiredGetObjectInformationRequestRequestTypeDef,
     _OptionalGetObjectInformationRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef = TypedDict(
+    "_RequiredListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef",
+    {
+        "DirectoryArn": str,
+        "TargetReference": ObjectReferenceTypeDef,
+    },
+)
+_OptionalListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef = TypedDict(
+    "_OptionalListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef",
+    {
+        "ConsistencyLevel": ConsistencyLevelType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef(
+    _RequiredListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef,
+    _OptionalListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAttachedIndicesRequestRequestTypeDef = TypedDict(
     "_RequiredListAttachedIndicesRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "TargetReference": ObjectReferenceTypeDef,
     },
 )
@@ -1170,20 +1671,22 @@
         "NextToken": str,
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
+
 class ListAttachedIndicesRequestRequestTypeDef(
     _RequiredListAttachedIndicesRequestRequestTypeDef,
     _OptionalListAttachedIndicesRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredListObjectChildrenRequestRequestTypeDef = TypedDict(
     "_RequiredListObjectChildrenRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -1193,20 +1696,45 @@
         "NextToken": str,
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
+
 class ListObjectChildrenRequestRequestTypeDef(
     _RequiredListObjectChildrenRequestRequestTypeDef,
     _OptionalListObjectChildrenRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef = TypedDict(
+    "_RequiredListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef",
+    {
+        "DirectoryArn": str,
+        "ObjectReference": ObjectReferenceTypeDef,
+    },
+)
+_OptionalListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef = TypedDict(
+    "_OptionalListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef(
+    _RequiredListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef,
+    _OptionalListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListObjectParentPathsRequestRequestTypeDef = TypedDict(
     "_RequiredListObjectParentPathsRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -1215,20 +1743,22 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListObjectParentPathsRequestRequestTypeDef(
     _RequiredListObjectParentPathsRequestRequestTypeDef,
     _OptionalListObjectParentPathsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredListObjectParentsRequestRequestTypeDef = TypedDict(
     "_RequiredListObjectParentsRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -1239,19 +1769,45 @@
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
         "IncludeAllLinksToEachParent": bool,
     },
     total=False,
 )
 
+
 class ListObjectParentsRequestRequestTypeDef(
     _RequiredListObjectParentsRequestRequestTypeDef, _OptionalListObjectParentsRequestRequestTypeDef
 ):
     pass
 
+
+_RequiredListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef",
+    {
+        "DirectoryArn": str,
+        "ObjectReference": ObjectReferenceTypeDef,
+    },
+)
+_OptionalListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef",
+    {
+        "ConsistencyLevel": ConsistencyLevelType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef(
+    _RequiredListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef,
+    _OptionalListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListObjectPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListObjectPoliciesRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -1261,20 +1817,46 @@
         "NextToken": str,
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
+
 class ListObjectPoliciesRequestRequestTypeDef(
     _RequiredListObjectPoliciesRequestRequestTypeDef,
     _OptionalListObjectPoliciesRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef = TypedDict(
+    "_RequiredListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef",
+    {
+        "DirectoryArn": str,
+        "PolicyReference": ObjectReferenceTypeDef,
+    },
+)
+_OptionalListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef = TypedDict(
+    "_OptionalListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef",
+    {
+        "ConsistencyLevel": ConsistencyLevelType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef(
+    _RequiredListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef,
+    _OptionalListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPolicyAttachmentsRequestRequestTypeDef = TypedDict(
     "_RequiredListPolicyAttachmentsRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "PolicyReference": ObjectReferenceTypeDef,
     },
 )
@@ -1284,20 +1866,45 @@
         "NextToken": str,
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
+
 class ListPolicyAttachmentsRequestRequestTypeDef(
     _RequiredListPolicyAttachmentsRequestRequestTypeDef,
     _OptionalListPolicyAttachmentsRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredLookupPolicyRequestLookupPolicyPaginateTypeDef = TypedDict(
+    "_RequiredLookupPolicyRequestLookupPolicyPaginateTypeDef",
+    {
+        "DirectoryArn": str,
+        "ObjectReference": ObjectReferenceTypeDef,
+    },
+)
+_OptionalLookupPolicyRequestLookupPolicyPaginateTypeDef = TypedDict(
+    "_OptionalLookupPolicyRequestLookupPolicyPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class LookupPolicyRequestLookupPolicyPaginateTypeDef(
+    _RequiredLookupPolicyRequestLookupPolicyPaginateTypeDef,
+    _OptionalLookupPolicyRequestLookupPolicyPaginateTypeDef,
+):
+    pass
+
+
 _RequiredLookupPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredLookupPolicyRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -1306,19 +1913,21 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class LookupPolicyRequestRequestTypeDef(
     _RequiredLookupPolicyRequestRequestTypeDef, _OptionalLookupPolicyRequestRequestTypeDef
 ):
     pass
 
+
 BatchGetObjectAttributesTypeDef = TypedDict(
     "BatchGetObjectAttributesTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
         "SchemaFacet": SchemaFacetTypeDef,
         "AttributeNames": Sequence[str],
     },
@@ -1345,19 +1954,21 @@
         "NextToken": str,
         "MaxResults": int,
         "FacetFilter": SchemaFacetTypeDef,
     },
     total=False,
 )
 
+
 class BatchListObjectAttributesTypeDef(
     _RequiredBatchListObjectAttributesTypeDef, _OptionalBatchListObjectAttributesTypeDef
 ):
     pass
 
+
 BatchRemoveFacetFromObjectTypeDef = TypedDict(
     "BatchRemoveFacetFromObjectTypeDef",
     {
         "SchemaFacet": SchemaFacetTypeDef,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -1375,329 +1986,88 @@
     "_OptionalGetObjectAttributesRequestRequestTypeDef",
     {
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
+
 class GetObjectAttributesRequestRequestTypeDef(
     _RequiredGetObjectAttributesRequestRequestTypeDef,
     _OptionalGetObjectAttributesRequestRequestTypeDef,
 ):
     pass
 
-_RequiredListObjectAttributesRequestRequestTypeDef = TypedDict(
-    "_RequiredListObjectAttributesRequestRequestTypeDef",
-    {
-        "DirectoryArn": str,
-        "ObjectReference": ObjectReferenceTypeDef,
-    },
-)
-_OptionalListObjectAttributesRequestRequestTypeDef = TypedDict(
-    "_OptionalListObjectAttributesRequestRequestTypeDef",
-    {
-        "NextToken": str,
-        "MaxResults": int,
-        "ConsistencyLevel": ConsistencyLevelType,
-        "FacetFilter": SchemaFacetTypeDef,
-    },
-    total=False,
-)
-
-class ListObjectAttributesRequestRequestTypeDef(
-    _RequiredListObjectAttributesRequestRequestTypeDef,
-    _OptionalListObjectAttributesRequestRequestTypeDef,
-):
-    pass
-
-RemoveFacetFromObjectRequestRequestTypeDef = TypedDict(
-    "RemoveFacetFromObjectRequestRequestTypeDef",
-    {
-        "DirectoryArn": str,
-        "SchemaFacet": SchemaFacetTypeDef,
-        "ObjectReference": ObjectReferenceTypeDef,
-    },
-)
-
-ApplySchemaResponseTypeDef = TypedDict(
-    "ApplySchemaResponseTypeDef",
-    {
-        "AppliedSchemaArn": str,
-        "DirectoryArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AttachObjectResponseTypeDef = TypedDict(
-    "AttachObjectResponseTypeDef",
-    {
-        "AttachedObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AttachToIndexResponseTypeDef = TypedDict(
-    "AttachToIndexResponseTypeDef",
-    {
-        "AttachedObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDirectoryResponseTypeDef = TypedDict(
-    "CreateDirectoryResponseTypeDef",
-    {
-        "DirectoryArn": str,
-        "Name": str,
-        "ObjectIdentifier": str,
-        "AppliedSchemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateIndexResponseTypeDef = TypedDict(
-    "CreateIndexResponseTypeDef",
-    {
-        "ObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateObjectResponseTypeDef = TypedDict(
-    "CreateObjectResponseTypeDef",
-    {
-        "ObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSchemaResponseTypeDef = TypedDict(
-    "CreateSchemaResponseTypeDef",
-    {
-        "SchemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDirectoryResponseTypeDef = TypedDict(
-    "DeleteDirectoryResponseTypeDef",
-    {
-        "DirectoryArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSchemaResponseTypeDef = TypedDict(
-    "DeleteSchemaResponseTypeDef",
-    {
-        "SchemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DetachFromIndexResponseTypeDef = TypedDict(
-    "DetachFromIndexResponseTypeDef",
-    {
-        "DetachedObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DetachObjectResponseTypeDef = TypedDict(
-    "DetachObjectResponseTypeDef",
-    {
-        "DetachedObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisableDirectoryResponseTypeDef = TypedDict(
-    "DisableDirectoryResponseTypeDef",
-    {
-        "DirectoryArn": str,
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
-EnableDirectoryResponseTypeDef = TypedDict(
-    "EnableDirectoryResponseTypeDef",
-    {
-        "DirectoryArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAppliedSchemaVersionResponseTypeDef = TypedDict(
-    "GetAppliedSchemaVersionResponseTypeDef",
-    {
-        "AppliedSchemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 GetObjectInformationResponseTypeDef = TypedDict(
     "GetObjectInformationResponseTypeDef",
     {
         "SchemaFacets": List[SchemaFacetTypeDef],
         "ObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSchemaAsJsonResponseTypeDef = TypedDict(
-    "GetSchemaAsJsonResponseTypeDef",
-    {
-        "Name": str,
-        "Document": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTypedLinkFacetInformationResponseTypeDef = TypedDict(
-    "GetTypedLinkFacetInformationResponseTypeDef",
-    {
-        "IdentityAttributeOrder": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAppliedSchemaArnsResponseTypeDef = TypedDict(
-    "ListAppliedSchemaArnsResponseTypeDef",
-    {
-        "SchemaArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDevelopmentSchemaArnsResponseTypeDef = TypedDict(
-    "ListDevelopmentSchemaArnsResponseTypeDef",
+_RequiredListObjectAttributesRequestListObjectAttributesPaginateTypeDef = TypedDict(
+    "_RequiredListObjectAttributesRequestListObjectAttributesPaginateTypeDef",
     {
-        "SchemaArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DirectoryArn": str,
+        "ObjectReference": ObjectReferenceTypeDef,
     },
 )
-
-ListFacetNamesResponseTypeDef = TypedDict(
-    "ListFacetNamesResponseTypeDef",
+_OptionalListObjectAttributesRequestListObjectAttributesPaginateTypeDef = TypedDict(
+    "_OptionalListObjectAttributesRequestListObjectAttributesPaginateTypeDef",
     {
-        "FacetNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ConsistencyLevel": ConsistencyLevelType,
+        "FacetFilter": SchemaFacetTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
-ListManagedSchemaArnsResponseTypeDef = TypedDict(
-    "ListManagedSchemaArnsResponseTypeDef",
-    {
-        "SchemaArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-ListObjectChildrenResponseTypeDef = TypedDict(
-    "ListObjectChildrenResponseTypeDef",
-    {
-        "Children": Dict[str, str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListObjectPoliciesResponseTypeDef = TypedDict(
-    "ListObjectPoliciesResponseTypeDef",
-    {
-        "AttachedPolicyIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class ListObjectAttributesRequestListObjectAttributesPaginateTypeDef(
+    _RequiredListObjectAttributesRequestListObjectAttributesPaginateTypeDef,
+    _OptionalListObjectAttributesRequestListObjectAttributesPaginateTypeDef,
+):
+    pass
 
-ListPolicyAttachmentsResponseTypeDef = TypedDict(
-    "ListPolicyAttachmentsResponseTypeDef",
-    {
-        "ObjectIdentifiers": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-ListPublishedSchemaArnsResponseTypeDef = TypedDict(
-    "ListPublishedSchemaArnsResponseTypeDef",
+_RequiredListObjectAttributesRequestRequestTypeDef = TypedDict(
+    "_RequiredListObjectAttributesRequestRequestTypeDef",
     {
-        "SchemaArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DirectoryArn": str,
+        "ObjectReference": ObjectReferenceTypeDef,
     },
 )
-
-ListTypedLinkFacetNamesResponseTypeDef = TypedDict(
-    "ListTypedLinkFacetNamesResponseTypeDef",
+_OptionalListObjectAttributesRequestRequestTypeDef = TypedDict(
+    "_OptionalListObjectAttributesRequestRequestTypeDef",
     {
-        "FacetNames": List[str],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PublishSchemaResponseTypeDef = TypedDict(
-    "PublishSchemaResponseTypeDef",
-    {
-        "PublishedSchemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxResults": int,
+        "ConsistencyLevel": ConsistencyLevelType,
+        "FacetFilter": SchemaFacetTypeDef,
     },
+    total=False,
 )
 
-PutSchemaFromJsonResponseTypeDef = TypedDict(
-    "PutSchemaFromJsonResponseTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-UpdateObjectAttributesResponseTypeDef = TypedDict(
-    "UpdateObjectAttributesResponseTypeDef",
-    {
-        "ObjectIdentifier": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class ListObjectAttributesRequestRequestTypeDef(
+    _RequiredListObjectAttributesRequestRequestTypeDef,
+    _OptionalListObjectAttributesRequestRequestTypeDef,
+):
+    pass
 
-UpdateSchemaResponseTypeDef = TypedDict(
-    "UpdateSchemaResponseTypeDef",
-    {
-        "SchemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-UpgradeAppliedSchemaResponseTypeDef = TypedDict(
-    "UpgradeAppliedSchemaResponseTypeDef",
+RemoveFacetFromObjectRequestRequestTypeDef = TypedDict(
+    "RemoveFacetFromObjectRequestRequestTypeDef",
     {
-        "UpgradedSchemaArn": str,
         "DirectoryArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpgradePublishedSchemaResponseTypeDef = TypedDict(
-    "UpgradePublishedSchemaResponseTypeDef",
-    {
-        "UpgradedSchemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "SchemaFacet": SchemaFacetTypeDef,
+        "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 
 _RequiredBatchCreateIndexTypeDef = TypedDict(
     "_RequiredBatchCreateIndexTypeDef",
     {
         "OrderedIndexedAttributeList": Sequence[AttributeKeyTypeDef],
@@ -1710,17 +2080,19 @@
         "ParentReference": ObjectReferenceTypeDef,
         "LinkName": str,
         "BatchReferenceName": str,
     },
     total=False,
 )
 
+
 class BatchCreateIndexTypeDef(_RequiredBatchCreateIndexTypeDef, _OptionalBatchCreateIndexTypeDef):
     pass
 
+
 _RequiredCreateIndexRequestRequestTypeDef = TypedDict(
     "_RequiredCreateIndexRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "OrderedIndexedAttributeList": Sequence[AttributeKeyTypeDef],
         "IsUnique": bool,
     },
@@ -1730,19 +2102,21 @@
     {
         "ParentReference": ObjectReferenceTypeDef,
         "LinkName": str,
     },
     total=False,
 )
 
+
 class CreateIndexRequestRequestTypeDef(
     _RequiredCreateIndexRequestRequestTypeDef, _OptionalCreateIndexRequestRequestTypeDef
 ):
     pass
 
+
 AttributeKeyAndValueTypeDef = TypedDict(
     "AttributeKeyAndValueTypeDef",
     {
         "Key": AttributeKeyTypeDef,
         "Value": TypedAttributeValueTypeDef,
     },
 )
@@ -1785,34 +2159,36 @@
     {
         "StartValue": TypedAttributeValueTypeDef,
         "EndValue": TypedAttributeValueTypeDef,
     },
     total=False,
 )
 
+
 class TypedAttributeValueRangeTypeDef(
     _RequiredTypedAttributeValueRangeTypeDef, _OptionalTypedAttributeValueRangeTypeDef
 ):
     pass
 
+
 BatchListObjectParentPathsResponseTypeDef = TypedDict(
     "BatchListObjectParentPathsResponseTypeDef",
     {
         "PathToObjectIdentifiersList": List[PathToObjectIdentifiersTypeDef],
         "NextToken": str,
     },
     total=False,
 )
 
 ListObjectParentPathsResponseTypeDef = TypedDict(
     "ListObjectParentPathsResponseTypeDef",
     {
         "PathToObjectIdentifiersList": List[PathToObjectIdentifiersTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchListObjectParentsResponseTypeDef = TypedDict(
     "BatchListObjectParentsResponseTypeDef",
     {
         "ParentLinks": List[ObjectIdentifierAndLinkNameTupleTypeDef],
@@ -1823,32 +2199,32 @@
 
 ListObjectParentsResponseTypeDef = TypedDict(
     "ListObjectParentsResponseTypeDef",
     {
         "Parents": Dict[str, str],
         "NextToken": str,
         "ParentLinks": List[ObjectIdentifierAndLinkNameTupleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDirectoryResponseTypeDef = TypedDict(
     "GetDirectoryResponseTypeDef",
     {
         "Directory": DirectoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDirectoriesResponseTypeDef = TypedDict(
     "ListDirectoriesResponseTypeDef",
     {
         "Directories": List[DirectoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFacetAttributeDefinitionTypeDef = TypedDict(
     "_RequiredFacetAttributeDefinitionTypeDef",
     {
         "Type": FacetAttributeTypeType,
@@ -1860,19 +2236,21 @@
         "DefaultValue": TypedAttributeValueTypeDef,
         "IsImmutable": bool,
         "Rules": Mapping[str, RuleTypeDef],
     },
     total=False,
 )
 
+
 class FacetAttributeDefinitionTypeDef(
     _RequiredFacetAttributeDefinitionTypeDef, _OptionalFacetAttributeDefinitionTypeDef
 ):
     pass
 
+
 _RequiredTypedLinkAttributeDefinitionTypeDef = TypedDict(
     "_RequiredTypedLinkAttributeDefinitionTypeDef",
     {
         "Name": str,
         "Type": FacetAttributeTypeType,
         "RequiredBehavior": RequiredAttributeBehaviorType,
     },
@@ -1883,322 +2261,35 @@
         "DefaultValue": TypedAttributeValueTypeDef,
         "IsImmutable": bool,
         "Rules": Mapping[str, RuleTypeDef],
     },
     total=False,
 )
 
+
 class TypedLinkAttributeDefinitionTypeDef(
     _RequiredTypedLinkAttributeDefinitionTypeDef, _OptionalTypedLinkAttributeDefinitionTypeDef
 ):
     pass
 
+
 GetFacetResponseTypeDef = TypedDict(
     "GetFacetResponseTypeDef",
     {
         "Facet": FacetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef = TypedDict(
-    "_RequiredListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef",
-    {
-        "DirectoryArn": str,
-    },
-)
-_OptionalListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef = TypedDict(
-    "_OptionalListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef",
-    {
-        "SchemaArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef(
-    _RequiredListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef,
-    _OptionalListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef,
-):
-    pass
-
-_RequiredListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef = TypedDict(
-    "_RequiredListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef",
-    {
-        "DirectoryArn": str,
-        "TargetReference": ObjectReferenceTypeDef,
-    },
-)
-_OptionalListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef = TypedDict(
-    "_OptionalListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef",
-    {
-        "ConsistencyLevel": ConsistencyLevelType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef(
-    _RequiredListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef,
-    _OptionalListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef,
-):
-    pass
-
-ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef = TypedDict(
-    "ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDirectoriesRequestListDirectoriesPaginateTypeDef = TypedDict(
-    "ListDirectoriesRequestListDirectoriesPaginateTypeDef",
-    {
-        "state": DirectoryStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListFacetAttributesRequestListFacetAttributesPaginateTypeDef = TypedDict(
-    "_RequiredListFacetAttributesRequestListFacetAttributesPaginateTypeDef",
-    {
-        "SchemaArn": str,
-        "Name": str,
-    },
-)
-_OptionalListFacetAttributesRequestListFacetAttributesPaginateTypeDef = TypedDict(
-    "_OptionalListFacetAttributesRequestListFacetAttributesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListFacetAttributesRequestListFacetAttributesPaginateTypeDef(
-    _RequiredListFacetAttributesRequestListFacetAttributesPaginateTypeDef,
-    _OptionalListFacetAttributesRequestListFacetAttributesPaginateTypeDef,
-):
-    pass
-
-_RequiredListFacetNamesRequestListFacetNamesPaginateTypeDef = TypedDict(
-    "_RequiredListFacetNamesRequestListFacetNamesPaginateTypeDef",
-    {
-        "SchemaArn": str,
-    },
-)
-_OptionalListFacetNamesRequestListFacetNamesPaginateTypeDef = TypedDict(
-    "_OptionalListFacetNamesRequestListFacetNamesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListFacetNamesRequestListFacetNamesPaginateTypeDef(
-    _RequiredListFacetNamesRequestListFacetNamesPaginateTypeDef,
-    _OptionalListFacetNamesRequestListFacetNamesPaginateTypeDef,
-):
-    pass
-
-ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef = TypedDict(
-    "ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef",
-    {
-        "SchemaArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListObjectAttributesRequestListObjectAttributesPaginateTypeDef = TypedDict(
-    "_RequiredListObjectAttributesRequestListObjectAttributesPaginateTypeDef",
-    {
-        "DirectoryArn": str,
-        "ObjectReference": ObjectReferenceTypeDef,
-    },
-)
-_OptionalListObjectAttributesRequestListObjectAttributesPaginateTypeDef = TypedDict(
-    "_OptionalListObjectAttributesRequestListObjectAttributesPaginateTypeDef",
-    {
-        "ConsistencyLevel": ConsistencyLevelType,
-        "FacetFilter": SchemaFacetTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListObjectAttributesRequestListObjectAttributesPaginateTypeDef(
-    _RequiredListObjectAttributesRequestListObjectAttributesPaginateTypeDef,
-    _OptionalListObjectAttributesRequestListObjectAttributesPaginateTypeDef,
-):
-    pass
-
-_RequiredListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef = TypedDict(
-    "_RequiredListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef",
-    {
-        "DirectoryArn": str,
-        "ObjectReference": ObjectReferenceTypeDef,
-    },
-)
-_OptionalListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef = TypedDict(
-    "_OptionalListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef(
-    _RequiredListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef,
-    _OptionalListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef,
-):
-    pass
-
-_RequiredListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef",
-    {
-        "DirectoryArn": str,
-        "ObjectReference": ObjectReferenceTypeDef,
-    },
-)
-_OptionalListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef",
-    {
-        "ConsistencyLevel": ConsistencyLevelType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef(
-    _RequiredListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef,
-    _OptionalListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef,
-):
-    pass
-
-_RequiredListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef = TypedDict(
-    "_RequiredListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef",
-    {
-        "DirectoryArn": str,
-        "PolicyReference": ObjectReferenceTypeDef,
-    },
-)
-_OptionalListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef = TypedDict(
-    "_OptionalListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef",
-    {
-        "ConsistencyLevel": ConsistencyLevelType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef(
-    _RequiredListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef,
-    _OptionalListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef,
-):
-    pass
-
-ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef = TypedDict(
-    "ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef",
-    {
-        "SchemaArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceArn": str,
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
-_RequiredListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef = TypedDict(
-    "_RequiredListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef",
-    {
-        "SchemaArn": str,
-        "Name": str,
-    },
-)
-_OptionalListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef = TypedDict(
-    "_OptionalListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef(
-    _RequiredListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef,
-    _OptionalListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef,
-):
-    pass
-
-_RequiredListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef = TypedDict(
-    "_RequiredListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef",
-    {
-        "SchemaArn": str,
-    },
-)
-_OptionalListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef = TypedDict(
-    "_OptionalListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef(
-    _RequiredListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef,
-    _OptionalListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef,
-):
-    pass
-
-_RequiredLookupPolicyRequestLookupPolicyPaginateTypeDef = TypedDict(
-    "_RequiredLookupPolicyRequestLookupPolicyPaginateTypeDef",
-    {
-        "DirectoryArn": str,
-        "ObjectReference": ObjectReferenceTypeDef,
-    },
-)
-_OptionalLookupPolicyRequestLookupPolicyPaginateTypeDef = TypedDict(
-    "_OptionalLookupPolicyRequestLookupPolicyPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class LookupPolicyRequestLookupPolicyPaginateTypeDef(
-    _RequiredLookupPolicyRequestLookupPolicyPaginateTypeDef,
-    _OptionalLookupPolicyRequestLookupPolicyPaginateTypeDef,
-):
-    pass
-
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -2227,19 +2318,21 @@
     "_OptionalAddFacetToObjectRequestRequestTypeDef",
     {
         "ObjectAttributeList": Sequence[AttributeKeyAndValueTypeDef],
     },
     total=False,
 )
 
+
 class AddFacetToObjectRequestRequestTypeDef(
     _RequiredAddFacetToObjectRequestRequestTypeDef, _OptionalAddFacetToObjectRequestRequestTypeDef
 ):
     pass
 
+
 BatchAddFacetToObjectTypeDef = TypedDict(
     "BatchAddFacetToObjectTypeDef",
     {
         "SchemaFacet": SchemaFacetTypeDef,
         "ObjectAttributeList": Sequence[AttributeKeyAndValueTypeDef],
         "ObjectReference": ObjectReferenceTypeDef,
     },
@@ -2258,19 +2351,21 @@
         "ParentReference": ObjectReferenceTypeDef,
         "LinkName": str,
         "BatchReferenceName": str,
     },
     total=False,
 )
 
+
 class BatchCreateObjectTypeDef(
     _RequiredBatchCreateObjectTypeDef, _OptionalBatchCreateObjectTypeDef
 ):
     pass
 
+
 BatchGetLinkAttributesResponseTypeDef = TypedDict(
     "BatchGetLinkAttributesResponseTypeDef",
     {
         "Attributes": List[AttributeKeyAndValueTypeDef],
     },
     total=False,
 )
@@ -2305,32 +2400,34 @@
         "ObjectAttributeList": Sequence[AttributeKeyAndValueTypeDef],
         "ParentReference": ObjectReferenceTypeDef,
         "LinkName": str,
     },
     total=False,
 )
 
+
 class CreateObjectRequestRequestTypeDef(
     _RequiredCreateObjectRequestRequestTypeDef, _OptionalCreateObjectRequestRequestTypeDef
 ):
     pass
 
+
 GetLinkAttributesResponseTypeDef = TypedDict(
     "GetLinkAttributesResponseTypeDef",
     {
         "Attributes": List[AttributeKeyAndValueTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetObjectAttributesResponseTypeDef = TypedDict(
     "GetObjectAttributesResponseTypeDef",
     {
         "Attributes": List[AttributeKeyAndValueTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IndexAttachmentTypeDef = TypedDict(
     "IndexAttachmentTypeDef",
     {
         "IndexedAttributes": List[AttributeKeyAndValueTypeDef],
@@ -2340,15 +2437,15 @@
 )
 
 ListObjectAttributesResponseTypeDef = TypedDict(
     "ListObjectAttributesResponseTypeDef",
     {
         "Attributes": List[AttributeKeyAndValueTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachTypedLinkRequestRequestTypeDef = TypedDict(
     "AttachTypedLinkRequestRequestTypeDef",
     {
         "DirectoryArn": str,
@@ -2416,19 +2513,21 @@
     "_OptionalTypedLinkAttributeRangeTypeDef",
     {
         "AttributeName": str,
     },
     total=False,
 )
 
+
 class TypedLinkAttributeRangeTypeDef(
     _RequiredTypedLinkAttributeRangeTypeDef, _OptionalTypedLinkAttributeRangeTypeDef
 ):
     pass
 
+
 _RequiredFacetAttributeTypeDef = TypedDict(
     "_RequiredFacetAttributeTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalFacetAttributeTypeDef = TypedDict(
@@ -2437,23 +2536,25 @@
         "AttributeDefinition": FacetAttributeDefinitionTypeDef,
         "AttributeReference": FacetAttributeReferenceTypeDef,
         "RequiredBehavior": RequiredAttributeBehaviorType,
     },
     total=False,
 )
 
+
 class FacetAttributeTypeDef(_RequiredFacetAttributeTypeDef, _OptionalFacetAttributeTypeDef):
     pass
 
+
 ListTypedLinkFacetAttributesResponseTypeDef = TypedDict(
     "ListTypedLinkFacetAttributesResponseTypeDef",
     {
         "Attributes": List[TypedLinkAttributeDefinitionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TypedLinkFacetAttributeUpdateTypeDef = TypedDict(
     "TypedLinkFacetAttributeUpdateTypeDef",
     {
         "Attribute": TypedLinkAttributeDefinitionTypeDef,
@@ -2480,15 +2581,15 @@
 )
 
 LookupPolicyResponseTypeDef = TypedDict(
     "LookupPolicyResponseTypeDef",
     {
         "PolicyToPathList": List[PolicyToPathTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchListAttachedIndicesResponseTypeDef = TypedDict(
     "BatchListAttachedIndicesResponseTypeDef",
     {
         "IndexAttachments": List[IndexAttachmentTypeDef],
@@ -2507,32 +2608,32 @@
 )
 
 ListAttachedIndicesResponseTypeDef = TypedDict(
     "ListAttachedIndicesResponseTypeDef",
     {
         "IndexAttachments": List[IndexAttachmentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIndexResponseTypeDef = TypedDict(
     "ListIndexResponseTypeDef",
     {
         "IndexAttachments": List[IndexAttachmentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachTypedLinkResponseTypeDef = TypedDict(
     "AttachTypedLinkResponseTypeDef",
     {
         "TypedLinkSpecifier": TypedLinkSpecifierTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchAttachTypedLinkResponseTypeDef = TypedDict(
     "BatchAttachTypedLinkResponseTypeDef",
     {
         "TypedLinkSpecifier": TypedLinkSpecifierTypeDef,
@@ -2593,34 +2694,36 @@
     "_OptionalGetLinkAttributesRequestRequestTypeDef",
     {
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
+
 class GetLinkAttributesRequestRequestTypeDef(
     _RequiredGetLinkAttributesRequestRequestTypeDef, _OptionalGetLinkAttributesRequestRequestTypeDef
 ):
     pass
 
+
 ListIncomingTypedLinksResponseTypeDef = TypedDict(
     "ListIncomingTypedLinksResponseTypeDef",
     {
         "LinkSpecifiers": List[TypedLinkSpecifierTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOutgoingTypedLinksResponseTypeDef = TypedDict(
     "ListOutgoingTypedLinksResponseTypeDef",
     {
         "TypedLinkSpecifiers": List[TypedLinkSpecifierTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdateLinkAttributesTypeDef = TypedDict(
     "BatchUpdateLinkAttributesTypeDef",
     {
         "TypedLinkSpecifier": TypedLinkSpecifierTypeDef,
@@ -2666,40 +2769,44 @@
         "RangesOnIndexedValues": Sequence[ObjectAttributeRangeTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class BatchListIndexTypeDef(_RequiredBatchListIndexTypeDef, _OptionalBatchListIndexTypeDef):
     pass
 
+
 _RequiredListIndexRequestListIndexPaginateTypeDef = TypedDict(
     "_RequiredListIndexRequestListIndexPaginateTypeDef",
     {
         "DirectoryArn": str,
         "IndexReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalListIndexRequestListIndexPaginateTypeDef = TypedDict(
     "_OptionalListIndexRequestListIndexPaginateTypeDef",
     {
         "RangesOnIndexedValues": Sequence[ObjectAttributeRangeTypeDef],
         "ConsistencyLevel": ConsistencyLevelType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class ListIndexRequestListIndexPaginateTypeDef(
     _RequiredListIndexRequestListIndexPaginateTypeDef,
     _OptionalListIndexRequestListIndexPaginateTypeDef,
 ):
     pass
 
+
 _RequiredListIndexRequestRequestTypeDef = TypedDict(
     "_RequiredListIndexRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "IndexReference": ObjectReferenceTypeDef,
     },
 )
@@ -2710,19 +2817,21 @@
         "MaxResults": int,
         "NextToken": str,
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
+
 class ListIndexRequestRequestTypeDef(
     _RequiredListIndexRequestRequestTypeDef, _OptionalListIndexRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredBatchListIncomingTypedLinksTypeDef = TypedDict(
     "_RequiredBatchListIncomingTypedLinksTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchListIncomingTypedLinksTypeDef = TypedDict(
@@ -2732,19 +2841,21 @@
         "FilterTypedLink": TypedLinkSchemaAndFacetNameTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class BatchListIncomingTypedLinksTypeDef(
     _RequiredBatchListIncomingTypedLinksTypeDef, _OptionalBatchListIncomingTypedLinksTypeDef
 ):
     pass
 
+
 _RequiredBatchListOutgoingTypedLinksTypeDef = TypedDict(
     "_RequiredBatchListOutgoingTypedLinksTypeDef",
     {
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalBatchListOutgoingTypedLinksTypeDef = TypedDict(
@@ -2754,43 +2865,47 @@
         "FilterTypedLink": TypedLinkSchemaAndFacetNameTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class BatchListOutgoingTypedLinksTypeDef(
     _RequiredBatchListOutgoingTypedLinksTypeDef, _OptionalBatchListOutgoingTypedLinksTypeDef
 ):
     pass
 
+
 _RequiredListIncomingTypedLinksRequestListIncomingTypedLinksPaginateTypeDef = TypedDict(
     "_RequiredListIncomingTypedLinksRequestListIncomingTypedLinksPaginateTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalListIncomingTypedLinksRequestListIncomingTypedLinksPaginateTypeDef = TypedDict(
     "_OptionalListIncomingTypedLinksRequestListIncomingTypedLinksPaginateTypeDef",
     {
         "FilterAttributeRanges": Sequence[TypedLinkAttributeRangeTypeDef],
         "FilterTypedLink": TypedLinkSchemaAndFacetNameTypeDef,
         "ConsistencyLevel": ConsistencyLevelType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class ListIncomingTypedLinksRequestListIncomingTypedLinksPaginateTypeDef(
     _RequiredListIncomingTypedLinksRequestListIncomingTypedLinksPaginateTypeDef,
     _OptionalListIncomingTypedLinksRequestListIncomingTypedLinksPaginateTypeDef,
 ):
     pass
 
+
 _RequiredListIncomingTypedLinksRequestRequestTypeDef = TypedDict(
     "_RequiredListIncomingTypedLinksRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -2802,44 +2917,48 @@
         "NextToken": str,
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
+
 class ListIncomingTypedLinksRequestRequestTypeDef(
     _RequiredListIncomingTypedLinksRequestRequestTypeDef,
     _OptionalListIncomingTypedLinksRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredListOutgoingTypedLinksRequestListOutgoingTypedLinksPaginateTypeDef = TypedDict(
     "_RequiredListOutgoingTypedLinksRequestListOutgoingTypedLinksPaginateTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
 _OptionalListOutgoingTypedLinksRequestListOutgoingTypedLinksPaginateTypeDef = TypedDict(
     "_OptionalListOutgoingTypedLinksRequestListOutgoingTypedLinksPaginateTypeDef",
     {
         "FilterAttributeRanges": Sequence[TypedLinkAttributeRangeTypeDef],
         "FilterTypedLink": TypedLinkSchemaAndFacetNameTypeDef,
         "ConsistencyLevel": ConsistencyLevelType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class ListOutgoingTypedLinksRequestListOutgoingTypedLinksPaginateTypeDef(
     _RequiredListOutgoingTypedLinksRequestListOutgoingTypedLinksPaginateTypeDef,
     _OptionalListOutgoingTypedLinksRequestListOutgoingTypedLinksPaginateTypeDef,
 ):
     pass
 
+
 _RequiredListOutgoingTypedLinksRequestRequestTypeDef = TypedDict(
     "_RequiredListOutgoingTypedLinksRequestRequestTypeDef",
     {
         "DirectoryArn": str,
         "ObjectReference": ObjectReferenceTypeDef,
     },
 )
@@ -2851,20 +2970,22 @@
         "NextToken": str,
         "MaxResults": int,
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
+
 class ListOutgoingTypedLinksRequestRequestTypeDef(
     _RequiredListOutgoingTypedLinksRequestRequestTypeDef,
     _OptionalListOutgoingTypedLinksRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateFacetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFacetRequestRequestTypeDef",
     {
         "SchemaArn": str,
         "Name": str,
     },
 )
@@ -2874,34 +2995,36 @@
         "Attributes": Sequence[FacetAttributeTypeDef],
         "ObjectType": ObjectTypeType,
         "FacetStyle": FacetStyleType,
     },
     total=False,
 )
 
+
 class CreateFacetRequestRequestTypeDef(
     _RequiredCreateFacetRequestRequestTypeDef, _OptionalCreateFacetRequestRequestTypeDef
 ):
     pass
 
+
 FacetAttributeUpdateTypeDef = TypedDict(
     "FacetAttributeUpdateTypeDef",
     {
         "Attribute": FacetAttributeTypeDef,
         "Action": UpdateActionTypeType,
     },
     total=False,
 )
 
 ListFacetAttributesResponseTypeDef = TypedDict(
     "ListFacetAttributesResponseTypeDef",
     {
         "Attributes": List[FacetAttributeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTypedLinkFacetRequestRequestTypeDef = TypedDict(
     "UpdateTypedLinkFacetRequestRequestTypeDef",
     {
         "SchemaArn": str,
@@ -3017,24 +3140,26 @@
     {
         "AttributeUpdates": Sequence[FacetAttributeUpdateTypeDef],
         "ObjectType": ObjectTypeType,
     },
     total=False,
 )
 
+
 class UpdateFacetRequestRequestTypeDef(
     _RequiredUpdateFacetRequestRequestTypeDef, _OptionalUpdateFacetRequestRequestTypeDef
 ):
     pass
 
+
 BatchWriteResponseTypeDef = TypedDict(
     "BatchWriteResponseTypeDef",
     {
         "Responses": List[BatchWriteOperationResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchReadOperationResponseTypeDef = TypedDict(
     "BatchReadOperationResponseTypeDef",
     {
         "SuccessfulResponse": BatchReadSuccessfulResponseTypeDef,
@@ -3062,19 +3187,21 @@
     "_OptionalBatchReadRequestRequestTypeDef",
     {
         "ConsistencyLevel": ConsistencyLevelType,
     },
     total=False,
 )
 
+
 class BatchReadRequestRequestTypeDef(
     _RequiredBatchReadRequestRequestTypeDef, _OptionalBatchReadRequestRequestTypeDef
 ):
     pass
 
+
 BatchReadResponseTypeDef = TypedDict(
     "BatchReadResponseTypeDef",
     {
         "Responses": List[BatchReadOperationResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory.egg-info/PKG-INFO` & `types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-clouddirectory
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudDirectory 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudDirectory 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-clouddirectory"></a>
 
 # types-aiobotocore-clouddirectory
 
 [![PyPI - types-aiobotocore-clouddirectory](https://img.shields.io/pypi/v/types-aiobotocore-clouddirectory.svg?color=blue)](https://pypi.org/project/types-aiobotocore-clouddirectory)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-clouddirectory.svg?color=blue)](https://pypi.org/project/types-aiobotocore-clouddirectory)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-clouddirectory?color=blue)](https://pypistats.org/packages/types-aiobotocore-clouddirectory)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudDirectory 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory)
+[aiobotocore.CloudDirectory 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/clouddirectory.html#CloudDirectory)
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
 [types-aiobotocore-clouddirectory docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_clouddirectory/).
 
 See how it helps to find and fix potential bugs:
 
@@ -413,15 +413,17 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_clouddirectory.type_defs import (
     ObjectReferenceTypeDef,
     SchemaFacetTypeDef,
     ApplySchemaRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    ApplySchemaResponseTypeDef,
+    AttachObjectResponseTypeDef,
+    AttachToIndexResponseTypeDef,
     TypedLinkSchemaAndFacetNameTypeDef,
     AttributeKeyTypeDef,
     TypedAttributeValueTypeDef,
     BatchAttachObjectResponseTypeDef,
     BatchAttachToIndexResponseTypeDef,
     BatchCreateIndexResponseTypeDef,
     BatchCreateObjectResponseTypeDef,
@@ -431,49 +433,89 @@
     PathToObjectIdentifiersTypeDef,
     ObjectIdentifierAndLinkNameTupleTypeDef,
     BatchListObjectPoliciesResponseTypeDef,
     BatchListPolicyAttachmentsResponseTypeDef,
     BatchReadExceptionTypeDef,
     BatchUpdateObjectAttributesResponseTypeDef,
     CreateDirectoryRequestRequestTypeDef,
+    CreateDirectoryResponseTypeDef,
+    CreateIndexResponseTypeDef,
+    CreateObjectResponseTypeDef,
     CreateSchemaRequestRequestTypeDef,
+    CreateSchemaResponseTypeDef,
     DeleteDirectoryRequestRequestTypeDef,
+    DeleteDirectoryResponseTypeDef,
     DeleteFacetRequestRequestTypeDef,
     DeleteSchemaRequestRequestTypeDef,
+    DeleteSchemaResponseTypeDef,
     DeleteTypedLinkFacetRequestRequestTypeDef,
+    DetachFromIndexResponseTypeDef,
+    DetachObjectResponseTypeDef,
     DirectoryTypeDef,
     DisableDirectoryRequestRequestTypeDef,
+    DisableDirectoryResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableDirectoryRequestRequestTypeDef,
+    EnableDirectoryResponseTypeDef,
     RuleTypeDef,
     FacetAttributeReferenceTypeDef,
     FacetTypeDef,
     GetAppliedSchemaVersionRequestRequestTypeDef,
+    GetAppliedSchemaVersionResponseTypeDef,
     GetDirectoryRequestRequestTypeDef,
     GetFacetRequestRequestTypeDef,
     GetSchemaAsJsonRequestRequestTypeDef,
+    GetSchemaAsJsonResponseTypeDef,
     GetTypedLinkFacetInformationRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetTypedLinkFacetInformationResponseTypeDef,
+    ListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef,
     ListAppliedSchemaArnsRequestRequestTypeDef,
+    ListAppliedSchemaArnsResponseTypeDef,
+    ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef,
     ListDevelopmentSchemaArnsRequestRequestTypeDef,
+    ListDevelopmentSchemaArnsResponseTypeDef,
+    ListDirectoriesRequestListDirectoriesPaginateTypeDef,
     ListDirectoriesRequestRequestTypeDef,
+    ListFacetAttributesRequestListFacetAttributesPaginateTypeDef,
     ListFacetAttributesRequestRequestTypeDef,
+    ListFacetNamesRequestListFacetNamesPaginateTypeDef,
     ListFacetNamesRequestRequestTypeDef,
+    ListFacetNamesResponseTypeDef,
+    ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef,
     ListManagedSchemaArnsRequestRequestTypeDef,
+    ListManagedSchemaArnsResponseTypeDef,
+    ListObjectChildrenResponseTypeDef,
+    ListObjectPoliciesResponseTypeDef,
+    ListPolicyAttachmentsResponseTypeDef,
+    ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef,
     ListPublishedSchemaArnsRequestRequestTypeDef,
+    ListPublishedSchemaArnsResponseTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
+    ListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef,
     ListTypedLinkFacetAttributesRequestRequestTypeDef,
+    ListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef,
     ListTypedLinkFacetNamesRequestRequestTypeDef,
+    ListTypedLinkFacetNamesResponseTypeDef,
+    PaginatorConfigTypeDef,
     PolicyAttachmentTypeDef,
     PublishSchemaRequestRequestTypeDef,
+    PublishSchemaResponseTypeDef,
     PutSchemaFromJsonRequestRequestTypeDef,
+    PutSchemaFromJsonResponseTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateObjectAttributesResponseTypeDef,
     UpdateSchemaRequestRequestTypeDef,
+    UpdateSchemaResponseTypeDef,
     UpgradeAppliedSchemaRequestRequestTypeDef,
+    UpgradeAppliedSchemaResponseTypeDef,
     UpgradePublishedSchemaRequestRequestTypeDef,
+    UpgradePublishedSchemaResponseTypeDef,
     AttachObjectRequestRequestTypeDef,
     AttachPolicyRequestRequestTypeDef,
     AttachToIndexRequestRequestTypeDef,
     BatchAttachObjectTypeDef,
     BatchAttachPolicyTypeDef,
     BatchAttachToIndexTypeDef,
     BatchDeleteObjectTypeDef,
@@ -489,61 +531,35 @@
     BatchListPolicyAttachmentsTypeDef,
     BatchLookupPolicyTypeDef,
     DeleteObjectRequestRequestTypeDef,
     DetachFromIndexRequestRequestTypeDef,
     DetachObjectRequestRequestTypeDef,
     DetachPolicyRequestRequestTypeDef,
     GetObjectInformationRequestRequestTypeDef,
+    ListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef,
     ListAttachedIndicesRequestRequestTypeDef,
     ListObjectChildrenRequestRequestTypeDef,
+    ListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef,
     ListObjectParentPathsRequestRequestTypeDef,
     ListObjectParentsRequestRequestTypeDef,
+    ListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef,
     ListObjectPoliciesRequestRequestTypeDef,
+    ListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef,
     ListPolicyAttachmentsRequestRequestTypeDef,
+    LookupPolicyRequestLookupPolicyPaginateTypeDef,
     LookupPolicyRequestRequestTypeDef,
     BatchGetObjectAttributesTypeDef,
     BatchGetObjectInformationResponseTypeDef,
     BatchListObjectAttributesTypeDef,
     BatchRemoveFacetFromObjectTypeDef,
     GetObjectAttributesRequestRequestTypeDef,
+    GetObjectInformationResponseTypeDef,
+    ListObjectAttributesRequestListObjectAttributesPaginateTypeDef,
     ListObjectAttributesRequestRequestTypeDef,
     RemoveFacetFromObjectRequestRequestTypeDef,
-    ApplySchemaResponseTypeDef,
-    AttachObjectResponseTypeDef,
-    AttachToIndexResponseTypeDef,
-    CreateDirectoryResponseTypeDef,
-    CreateIndexResponseTypeDef,
-    CreateObjectResponseTypeDef,
-    CreateSchemaResponseTypeDef,
-    DeleteDirectoryResponseTypeDef,
-    DeleteSchemaResponseTypeDef,
-    DetachFromIndexResponseTypeDef,
-    DetachObjectResponseTypeDef,
-    DisableDirectoryResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EnableDirectoryResponseTypeDef,
-    GetAppliedSchemaVersionResponseTypeDef,
-    GetObjectInformationResponseTypeDef,
-    GetSchemaAsJsonResponseTypeDef,
-    GetTypedLinkFacetInformationResponseTypeDef,
-    ListAppliedSchemaArnsResponseTypeDef,
-    ListDevelopmentSchemaArnsResponseTypeDef,
-    ListFacetNamesResponseTypeDef,
-    ListManagedSchemaArnsResponseTypeDef,
-    ListObjectChildrenResponseTypeDef,
-    ListObjectPoliciesResponseTypeDef,
-    ListPolicyAttachmentsResponseTypeDef,
-    ListPublishedSchemaArnsResponseTypeDef,
-    ListTypedLinkFacetNamesResponseTypeDef,
-    PublishSchemaResponseTypeDef,
-    PutSchemaFromJsonResponseTypeDef,
-    UpdateObjectAttributesResponseTypeDef,
-    UpdateSchemaResponseTypeDef,
-    UpgradeAppliedSchemaResponseTypeDef,
-    UpgradePublishedSchemaResponseTypeDef,
     BatchCreateIndexTypeDef,
     CreateIndexRequestRequestTypeDef,
     AttributeKeyAndValueTypeDef,
     AttributeNameAndValueTypeDef,
     LinkAttributeActionTypeDef,
     ObjectAttributeActionTypeDef,
     TypedAttributeValueRangeTypeDef,
@@ -552,30 +568,14 @@
     BatchListObjectParentsResponseTypeDef,
     ListObjectParentsResponseTypeDef,
     GetDirectoryResponseTypeDef,
     ListDirectoriesResponseTypeDef,
     FacetAttributeDefinitionTypeDef,
     TypedLinkAttributeDefinitionTypeDef,
     GetFacetResponseTypeDef,
-    ListAppliedSchemaArnsRequestListAppliedSchemaArnsPaginateTypeDef,
-    ListAttachedIndicesRequestListAttachedIndicesPaginateTypeDef,
-    ListDevelopmentSchemaArnsRequestListDevelopmentSchemaArnsPaginateTypeDef,
-    ListDirectoriesRequestListDirectoriesPaginateTypeDef,
-    ListFacetAttributesRequestListFacetAttributesPaginateTypeDef,
-    ListFacetNamesRequestListFacetNamesPaginateTypeDef,
-    ListManagedSchemaArnsRequestListManagedSchemaArnsPaginateTypeDef,
-    ListObjectAttributesRequestListObjectAttributesPaginateTypeDef,
-    ListObjectParentPathsRequestListObjectParentPathsPaginateTypeDef,
-    ListObjectPoliciesRequestListObjectPoliciesPaginateTypeDef,
-    ListPolicyAttachmentsRequestListPolicyAttachmentsPaginateTypeDef,
-    ListPublishedSchemaArnsRequestListPublishedSchemaArnsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    ListTypedLinkFacetAttributesRequestListTypedLinkFacetAttributesPaginateTypeDef,
-    ListTypedLinkFacetNamesRequestListTypedLinkFacetNamesPaginateTypeDef,
-    LookupPolicyRequestLookupPolicyPaginateTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     PolicyToPathTypeDef,
     AddFacetToObjectRequestRequestTypeDef,
     BatchAddFacetToObjectTypeDef,
     BatchCreateObjectTypeDef,
     BatchGetLinkAttributesResponseTypeDef,
@@ -651,43 +651,43 @@
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

### Comparing `types-aiobotocore-clouddirectory-2.5.0.post1/types_aiobotocore_clouddirectory.egg-info/SOURCES.txt` & `types-aiobotocore-clouddirectory-2.5.1/types_aiobotocore_clouddirectory.egg-info/SOURCES.txt`

 * *Files identical despite different names*


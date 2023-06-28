# Comparing `tmp/types-aiobotocore-ssm-contacts-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-ssm-contacts-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-ssm-contacts-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:23 2023, max compression
+gzip compressed data, was "types-aiobotocore-ssm-contacts-2.5.1.tar", last modified: Wed Jun 28 01:44:13 2023, max compression
```

## Comparing `types-aiobotocore-ssm-contacts-2.5.0.post1.tar` & `types-aiobotocore-ssm-contacts-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.183654 types-aiobotocore-ssm-contacts-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16556 2023-03-11 12:27:23.179654 types-aiobotocore-ssm-contacts-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14966 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:23.183654 types-aiobotocore-ssm-contacts-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2158 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.175654 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/
--rw-r--r--   0 runner    (1001) docker     (123)     1770 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1769 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      961 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23799 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    23757 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8658 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8656 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8105 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     8096 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    23433 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    23389 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:39.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.179654 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16556 2023-03-11 12:27:22.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:22.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:22.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:22.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:27:22.000000 types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:13.866220 types-aiobotocore-ssm-contacts-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:25.000000 types-aiobotocore-ssm-contacts-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19077 2023-06-28 01:44:13.866220 types-aiobotocore-ssm-contacts-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17493 2023-06-28 01:41:25.000000 types-aiobotocore-ssm-contacts-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:13.866220 types-aiobotocore-ssm-contacts-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-06-28 01:41:25.000000 types-aiobotocore-ssm-contacts-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:13.854220 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/
+-rw-r--r--   0 runner    (1001) docker     (123)     2886 2023-06-28 01:41:25.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2885 2023-06-28 01:41:25.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      949 2023-06-28 01:41:25.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34382 2023-06-28 01:41:26.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34323 2023-06-28 01:41:26.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9739 2023-06-28 01:41:26.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9737 2023-06-28 01:41:26.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14457 2023-06-28 01:41:26.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14444 2023-06-28 01:41:26.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:25.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    39525 2023-06-28 01:41:27.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    39450 2023-06-28 01:41:26.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:25.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:13.866220 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19077 2023-06-28 01:44:13.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:44:13.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:13.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:13.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:13.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:44:13.000000 types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-ssm-contacts-2.5.0.post1/LICENSE` & `types-aiobotocore-ssm-contacts-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-ssm-contacts-2.5.0.post1/PKG-INFO` & `types-aiobotocore-ssm-contacts-2.5.1/PKG-INFO`

 * *Files 20% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ssm-contacts
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SSMContacts 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SSMContacts 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ssm-contacts"></a>
 
 # types-aiobotocore-ssm-contacts
 
 [![PyPI - types-aiobotocore-ssm-contacts](https://img.shields.io/pypi/v/types-aiobotocore-ssm-contacts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-contacts)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ssm-contacts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-contacts)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ssm-contacts?color=blue)](https://pypistats.org/packages/types-aiobotocore-ssm-contacts)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSMContacts 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts)
+[aiobotocore.SSMContacts 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts)
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
 [types-aiobotocore-ssm-contacts docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/).
 
 See how it helps to find and fix potential bugs:
 
@@ -277,16 +277,21 @@
 
 from types_aiobotocore_ssm_contacts import SSMContactsClient
 from types_aiobotocore_ssm_contacts.paginator import (
     ListContactChannelsPaginator,
     ListContactsPaginator,
     ListEngagementsPaginator,
     ListPageReceiptsPaginator,
+    ListPageResolutionsPaginator,
     ListPagesByContactPaginator,
     ListPagesByEngagementPaginator,
+    ListPreviewRotationShiftsPaginator,
+    ListRotationOverridesPaginator,
+    ListRotationShiftsPaginator,
+    ListRotationsPaginator,
 )
 
 session = get_session()
 async with session.create_client("ssm-contacts") as client:
     client: SSMContactsClient
 
     # Explicit type annotations are optional here
@@ -295,20 +300,33 @@
         "list_contact_channels"
     )
     list_contacts_paginator: ListContactsPaginator = client.get_paginator("list_contacts")
     list_engagements_paginator: ListEngagementsPaginator = client.get_paginator("list_engagements")
     list_page_receipts_paginator: ListPageReceiptsPaginator = client.get_paginator(
         "list_page_receipts"
     )
+    list_page_resolutions_paginator: ListPageResolutionsPaginator = client.get_paginator(
+        "list_page_resolutions"
+    )
     list_pages_by_contact_paginator: ListPagesByContactPaginator = client.get_paginator(
         "list_pages_by_contact"
     )
     list_pages_by_engagement_paginator: ListPagesByEngagementPaginator = client.get_paginator(
         "list_pages_by_engagement"
     )
+    list_preview_rotation_shifts_paginator: ListPreviewRotationShiftsPaginator = (
+        client.get_paginator("list_preview_rotation_shifts")
+    )
+    list_rotation_overrides_paginator: ListRotationOverridesPaginator = client.get_paginator(
+        "list_rotation_overrides"
+    )
+    list_rotation_shifts_paginator: ListRotationShiftsPaginator = client.get_paginator(
+        "list_rotation_shifts"
+    )
+    list_rotations_paginator: ListRotationsPaginator = client.get_paginator("list_rotations")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_ssm_contacts.literals` module contains literals extracted
@@ -317,21 +335,28 @@
 ```python
 from types_aiobotocore_ssm_contacts.literals import (
     AcceptCodeValidationType,
     AcceptTypeType,
     ActivationStatusType,
     ChannelTypeType,
     ContactTypeType,
+    DayOfWeekType,
     ListContactChannelsPaginatorName,
     ListContactsPaginatorName,
     ListEngagementsPaginatorName,
     ListPageReceiptsPaginatorName,
+    ListPageResolutionsPaginatorName,
     ListPagesByContactPaginatorName,
     ListPagesByEngagementPaginatorName,
+    ListPreviewRotationShiftsPaginatorName,
+    ListRotationOverridesPaginatorName,
+    ListRotationShiftsPaginatorName,
+    ListRotationsPaginatorName,
     ReceiptTypeType,
+    ShiftTypeType,
     SSMContactsServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
 )
 
 
@@ -350,114 +375,151 @@
 from types_aiobotocore_ssm_contacts.type_defs import (
     AcceptPageRequestRequestTypeDef,
     ActivateContactChannelRequestRequestTypeDef,
     ChannelTargetInfoTypeDef,
     ContactChannelAddressTypeDef,
     ContactTargetInfoTypeDef,
     ContactTypeDef,
-    ResponseMetadataTypeDef,
+    HandOffTimeTypeDef,
+    CreateContactChannelResultTypeDef,
     TagTypeDef,
+    CreateContactResultTypeDef,
+    CreateRotationOverrideRequestRequestTypeDef,
+    CreateRotationOverrideResultTypeDef,
+    CreateRotationResultTypeDef,
     DeactivateContactChannelRequestRequestTypeDef,
     DeleteContactChannelRequestRequestTypeDef,
     DeleteContactRequestRequestTypeDef,
+    DeleteRotationOverrideRequestRequestTypeDef,
+    DeleteRotationRequestRequestTypeDef,
     DescribeEngagementRequestRequestTypeDef,
+    DescribeEngagementResultTypeDef,
     DescribePageRequestRequestTypeDef,
+    DescribePageResultTypeDef,
     EngagementTypeDef,
     GetContactChannelRequestRequestTypeDef,
     GetContactPolicyRequestRequestTypeDef,
+    GetContactPolicyResultTypeDef,
     GetContactRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetRotationOverrideRequestRequestTypeDef,
+    GetRotationOverrideResultTypeDef,
+    GetRotationRequestRequestTypeDef,
+    ListContactChannelsRequestListContactChannelsPaginateTypeDef,
     ListContactChannelsRequestRequestTypeDef,
+    ListContactsRequestListContactsPaginateTypeDef,
     ListContactsRequestRequestTypeDef,
     TimeRangeTypeDef,
+    ListPageReceiptsRequestListPageReceiptsPaginateTypeDef,
     ListPageReceiptsRequestRequestTypeDef,
     ReceiptTypeDef,
+    ListPageResolutionsRequestListPageResolutionsPaginateTypeDef,
+    ListPageResolutionsRequestRequestTypeDef,
+    ResolutionContactTypeDef,
+    ListPagesByContactRequestListPagesByContactPaginateTypeDef,
     ListPagesByContactRequestRequestTypeDef,
     PageTypeDef,
+    ListPagesByEngagementRequestListPagesByEngagementPaginateTypeDef,
     ListPagesByEngagementRequestRequestTypeDef,
+    PreviewOverrideTypeDef,
+    ListRotationOverridesRequestListRotationOverridesPaginateTypeDef,
+    ListRotationOverridesRequestRequestTypeDef,
+    RotationOverrideTypeDef,
+    ListRotationShiftsRequestListRotationShiftsPaginateTypeDef,
+    ListRotationShiftsRequestRequestTypeDef,
+    ListRotationsRequestListRotationsPaginateTypeDef,
+    ListRotationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutContactPolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    ShiftDetailsTypeDef,
     SendActivationCodeRequestRequestTypeDef,
     StartEngagementRequestRequestTypeDef,
+    StartEngagementResultTypeDef,
     StopEngagementRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ContactChannelTypeDef,
     CreateContactChannelRequestRequestTypeDef,
+    GetContactChannelResultTypeDef,
     UpdateContactChannelRequestRequestTypeDef,
     TargetTypeDef,
-    CreateContactChannelResultTypeDef,
-    CreateContactResultTypeDef,
-    DescribeEngagementResultTypeDef,
-    DescribePageResultTypeDef,
-    GetContactChannelResultTypeDef,
-    GetContactPolicyResultTypeDef,
     ListContactsResultTypeDef,
-    StartEngagementResultTypeDef,
+    CoverageTimeTypeDef,
+    MonthlySettingTypeDef,
+    WeeklySettingTypeDef,
     ListTagsForResourceResultTypeDef,
     TagResourceRequestRequestTypeDef,
     ListEngagementsResultTypeDef,
-    ListContactChannelsRequestListContactChannelsPaginateTypeDef,
-    ListContactsRequestListContactsPaginateTypeDef,
-    ListPageReceiptsRequestListPageReceiptsPaginateTypeDef,
-    ListPagesByContactRequestListPagesByContactPaginateTypeDef,
-    ListPagesByEngagementRequestListPagesByEngagementPaginateTypeDef,
     ListEngagementsRequestListEngagementsPaginateTypeDef,
     ListEngagementsRequestRequestTypeDef,
     ListPageReceiptsResultTypeDef,
+    ListPageResolutionsResultTypeDef,
     ListPagesByContactResultTypeDef,
     ListPagesByEngagementResultTypeDef,
+    ListRotationOverridesResultTypeDef,
+    RotationShiftTypeDef,
     ListContactChannelsResultTypeDef,
     StageTypeDef,
+    RecurrenceSettingsTypeDef,
+    ListPreviewRotationShiftsResultTypeDef,
+    ListRotationShiftsResultTypeDef,
     PlanTypeDef,
+    CreateRotationRequestRequestTypeDef,
+    GetRotationResultTypeDef,
+    ListPreviewRotationShiftsRequestListPreviewRotationShiftsPaginateTypeDef,
+    ListPreviewRotationShiftsRequestRequestTypeDef,
+    RotationTypeDef,
+    UpdateRotationRequestRequestTypeDef,
     CreateContactRequestRequestTypeDef,
     GetContactResultTypeDef,
     UpdateContactRequestRequestTypeDef,
+    ListRotationsResultTypeDef,
 )
 
 
 def get_structure() -> AcceptPageRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-ssm-contacts-2.5.0.post1/README.md` & `types-aiobotocore-ssm-contacts-2.5.1/README.md`

 * *Files 22% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-ssm-contacts"></a>
 
 # types-aiobotocore-ssm-contacts
 
 [![PyPI - types-aiobotocore-ssm-contacts](https://img.shields.io/pypi/v/types-aiobotocore-ssm-contacts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-contacts)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ssm-contacts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-contacts)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ssm-contacts?color=blue)](https://pypistats.org/packages/types-aiobotocore-ssm-contacts)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSMContacts 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts)
+[aiobotocore.SSMContacts 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts)
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
 [types-aiobotocore-ssm-contacts docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/).
 
 See how it helps to find and fix potential bugs:
 
@@ -244,16 +244,21 @@
 
 from types_aiobotocore_ssm_contacts import SSMContactsClient
 from types_aiobotocore_ssm_contacts.paginator import (
     ListContactChannelsPaginator,
     ListContactsPaginator,
     ListEngagementsPaginator,
     ListPageReceiptsPaginator,
+    ListPageResolutionsPaginator,
     ListPagesByContactPaginator,
     ListPagesByEngagementPaginator,
+    ListPreviewRotationShiftsPaginator,
+    ListRotationOverridesPaginator,
+    ListRotationShiftsPaginator,
+    ListRotationsPaginator,
 )
 
 session = get_session()
 async with session.create_client("ssm-contacts") as client:
     client: SSMContactsClient
 
     # Explicit type annotations are optional here
@@ -262,20 +267,33 @@
         "list_contact_channels"
     )
     list_contacts_paginator: ListContactsPaginator = client.get_paginator("list_contacts")
     list_engagements_paginator: ListEngagementsPaginator = client.get_paginator("list_engagements")
     list_page_receipts_paginator: ListPageReceiptsPaginator = client.get_paginator(
         "list_page_receipts"
     )
+    list_page_resolutions_paginator: ListPageResolutionsPaginator = client.get_paginator(
+        "list_page_resolutions"
+    )
     list_pages_by_contact_paginator: ListPagesByContactPaginator = client.get_paginator(
         "list_pages_by_contact"
     )
     list_pages_by_engagement_paginator: ListPagesByEngagementPaginator = client.get_paginator(
         "list_pages_by_engagement"
     )
+    list_preview_rotation_shifts_paginator: ListPreviewRotationShiftsPaginator = (
+        client.get_paginator("list_preview_rotation_shifts")
+    )
+    list_rotation_overrides_paginator: ListRotationOverridesPaginator = client.get_paginator(
+        "list_rotation_overrides"
+    )
+    list_rotation_shifts_paginator: ListRotationShiftsPaginator = client.get_paginator(
+        "list_rotation_shifts"
+    )
+    list_rotations_paginator: ListRotationsPaginator = client.get_paginator("list_rotations")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_ssm_contacts.literals` module contains literals extracted
@@ -284,21 +302,28 @@
 ```python
 from types_aiobotocore_ssm_contacts.literals import (
     AcceptCodeValidationType,
     AcceptTypeType,
     ActivationStatusType,
     ChannelTypeType,
     ContactTypeType,
+    DayOfWeekType,
     ListContactChannelsPaginatorName,
     ListContactsPaginatorName,
     ListEngagementsPaginatorName,
     ListPageReceiptsPaginatorName,
+    ListPageResolutionsPaginatorName,
     ListPagesByContactPaginatorName,
     ListPagesByEngagementPaginatorName,
+    ListPreviewRotationShiftsPaginatorName,
+    ListRotationOverridesPaginatorName,
+    ListRotationShiftsPaginatorName,
+    ListRotationsPaginatorName,
     ReceiptTypeType,
+    ShiftTypeType,
     SSMContactsServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
 )
 
 
@@ -317,114 +342,151 @@
 from types_aiobotocore_ssm_contacts.type_defs import (
     AcceptPageRequestRequestTypeDef,
     ActivateContactChannelRequestRequestTypeDef,
     ChannelTargetInfoTypeDef,
     ContactChannelAddressTypeDef,
     ContactTargetInfoTypeDef,
     ContactTypeDef,
-    ResponseMetadataTypeDef,
+    HandOffTimeTypeDef,
+    CreateContactChannelResultTypeDef,
     TagTypeDef,
+    CreateContactResultTypeDef,
+    CreateRotationOverrideRequestRequestTypeDef,
+    CreateRotationOverrideResultTypeDef,
+    CreateRotationResultTypeDef,
     DeactivateContactChannelRequestRequestTypeDef,
     DeleteContactChannelRequestRequestTypeDef,
     DeleteContactRequestRequestTypeDef,
+    DeleteRotationOverrideRequestRequestTypeDef,
+    DeleteRotationRequestRequestTypeDef,
     DescribeEngagementRequestRequestTypeDef,
+    DescribeEngagementResultTypeDef,
     DescribePageRequestRequestTypeDef,
+    DescribePageResultTypeDef,
     EngagementTypeDef,
     GetContactChannelRequestRequestTypeDef,
     GetContactPolicyRequestRequestTypeDef,
+    GetContactPolicyResultTypeDef,
     GetContactRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetRotationOverrideRequestRequestTypeDef,
+    GetRotationOverrideResultTypeDef,
+    GetRotationRequestRequestTypeDef,
+    ListContactChannelsRequestListContactChannelsPaginateTypeDef,
     ListContactChannelsRequestRequestTypeDef,
+    ListContactsRequestListContactsPaginateTypeDef,
     ListContactsRequestRequestTypeDef,
     TimeRangeTypeDef,
+    ListPageReceiptsRequestListPageReceiptsPaginateTypeDef,
     ListPageReceiptsRequestRequestTypeDef,
     ReceiptTypeDef,
+    ListPageResolutionsRequestListPageResolutionsPaginateTypeDef,
+    ListPageResolutionsRequestRequestTypeDef,
+    ResolutionContactTypeDef,
+    ListPagesByContactRequestListPagesByContactPaginateTypeDef,
     ListPagesByContactRequestRequestTypeDef,
     PageTypeDef,
+    ListPagesByEngagementRequestListPagesByEngagementPaginateTypeDef,
     ListPagesByEngagementRequestRequestTypeDef,
+    PreviewOverrideTypeDef,
+    ListRotationOverridesRequestListRotationOverridesPaginateTypeDef,
+    ListRotationOverridesRequestRequestTypeDef,
+    RotationOverrideTypeDef,
+    ListRotationShiftsRequestListRotationShiftsPaginateTypeDef,
+    ListRotationShiftsRequestRequestTypeDef,
+    ListRotationsRequestListRotationsPaginateTypeDef,
+    ListRotationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutContactPolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    ShiftDetailsTypeDef,
     SendActivationCodeRequestRequestTypeDef,
     StartEngagementRequestRequestTypeDef,
+    StartEngagementResultTypeDef,
     StopEngagementRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ContactChannelTypeDef,
     CreateContactChannelRequestRequestTypeDef,
+    GetContactChannelResultTypeDef,
     UpdateContactChannelRequestRequestTypeDef,
     TargetTypeDef,
-    CreateContactChannelResultTypeDef,
-    CreateContactResultTypeDef,
-    DescribeEngagementResultTypeDef,
-    DescribePageResultTypeDef,
-    GetContactChannelResultTypeDef,
-    GetContactPolicyResultTypeDef,
     ListContactsResultTypeDef,
-    StartEngagementResultTypeDef,
+    CoverageTimeTypeDef,
+    MonthlySettingTypeDef,
+    WeeklySettingTypeDef,
     ListTagsForResourceResultTypeDef,
     TagResourceRequestRequestTypeDef,
     ListEngagementsResultTypeDef,
-    ListContactChannelsRequestListContactChannelsPaginateTypeDef,
-    ListContactsRequestListContactsPaginateTypeDef,
-    ListPageReceiptsRequestListPageReceiptsPaginateTypeDef,
-    ListPagesByContactRequestListPagesByContactPaginateTypeDef,
-    ListPagesByEngagementRequestListPagesByEngagementPaginateTypeDef,
     ListEngagementsRequestListEngagementsPaginateTypeDef,
     ListEngagementsRequestRequestTypeDef,
     ListPageReceiptsResultTypeDef,
+    ListPageResolutionsResultTypeDef,
     ListPagesByContactResultTypeDef,
     ListPagesByEngagementResultTypeDef,
+    ListRotationOverridesResultTypeDef,
+    RotationShiftTypeDef,
     ListContactChannelsResultTypeDef,
     StageTypeDef,
+    RecurrenceSettingsTypeDef,
+    ListPreviewRotationShiftsResultTypeDef,
+    ListRotationShiftsResultTypeDef,
     PlanTypeDef,
+    CreateRotationRequestRequestTypeDef,
+    GetRotationResultTypeDef,
+    ListPreviewRotationShiftsRequestListPreviewRotationShiftsPaginateTypeDef,
+    ListPreviewRotationShiftsRequestRequestTypeDef,
+    RotationTypeDef,
+    UpdateRotationRequestRequestTypeDef,
     CreateContactRequestRequestTypeDef,
     GetContactResultTypeDef,
     UpdateContactRequestRequestTypeDef,
+    ListRotationsResultTypeDef,
 )
 
 
 def get_structure() -> AcceptPageRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-ssm-contacts-2.5.0.post1/setup.py` & `types-aiobotocore-ssm-contacts-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-ssm-contacts.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-ssm-contacts",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_ssm_contacts"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SSMContacts 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.SSMContacts 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/"
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

### Comparing `types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/__main__.py` & `types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SSMContacts 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SSMContacts 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts\nOther"
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

### Comparing `types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/client.py` & `types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/client.pyi`

 * *Files 16% similar despite different names*

```diff
@@ -11,79 +11,92 @@
 
     session = get_session()
     async with session.create_client("ssm-contacts") as client:
         client: SSMContactsClient
     ```
 """
 import sys
-from typing import Any, Dict, Mapping, Sequence, Type, overload
+from datetime import datetime
+from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import AcceptCodeValidationType, AcceptTypeType, ChannelTypeType, ContactTypeType
 from .paginator import (
     ListContactChannelsPaginator,
     ListContactsPaginator,
     ListEngagementsPaginator,
     ListPageReceiptsPaginator,
+    ListPageResolutionsPaginator,
     ListPagesByContactPaginator,
     ListPagesByEngagementPaginator,
+    ListPreviewRotationShiftsPaginator,
+    ListRotationOverridesPaginator,
+    ListRotationShiftsPaginator,
+    ListRotationsPaginator,
 )
 from .type_defs import (
     ContactChannelAddressTypeDef,
     CreateContactChannelResultTypeDef,
     CreateContactResultTypeDef,
+    CreateRotationOverrideResultTypeDef,
+    CreateRotationResultTypeDef,
     DescribeEngagementResultTypeDef,
     DescribePageResultTypeDef,
     GetContactChannelResultTypeDef,
     GetContactPolicyResultTypeDef,
     GetContactResultTypeDef,
+    GetRotationOverrideResultTypeDef,
+    GetRotationResultTypeDef,
     ListContactChannelsResultTypeDef,
     ListContactsResultTypeDef,
     ListEngagementsResultTypeDef,
     ListPageReceiptsResultTypeDef,
+    ListPageResolutionsResultTypeDef,
     ListPagesByContactResultTypeDef,
     ListPagesByEngagementResultTypeDef,
+    ListPreviewRotationShiftsResultTypeDef,
+    ListRotationOverridesResultTypeDef,
+    ListRotationShiftsResultTypeDef,
+    ListRotationsResultTypeDef,
     ListTagsForResourceResultTypeDef,
     PlanTypeDef,
+    PreviewOverrideTypeDef,
+    RecurrenceSettingsTypeDef,
     StartEngagementResultTypeDef,
     TagTypeDef,
     TimeRangeTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = ("SSMContactsClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     DataEncryptionException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
-
 class SSMContactsClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/)
     """
 
     meta: ClientMeta
@@ -92,15 +105,14 @@
     def exceptions(self) -> Exceptions:
         """
         SSMContactsClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#exceptions)
         """
-
     async def accept_page(
         self,
         *,
         PageId: str,
         AcceptType: AcceptTypeType,
         AcceptCode: str,
         ContactChannelId: str = ...,
@@ -109,41 +121,37 @@
     ) -> Dict[str, Any]:
         """
         Used to acknowledge an engagement to a contact channel during an incident.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.accept_page)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#accept_page)
         """
-
     async def activate_contact_channel(
         self, *, ContactChannelId: str, ActivationCode: str
     ) -> Dict[str, Any]:
         """
         Activates a contact's contact channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.activate_contact_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#activate_contact_channel)
         """
-
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#can_paginate)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#close)
         """
-
     async def create_contact(
         self,
         *,
         Alias: str,
         Type: ContactTypeType,
         Plan: PlanTypeDef,
         DisplayName: str = ...,
@@ -154,15 +162,14 @@
         Contacts are either the contacts that Incident Manager engages during an
         incident or the escalation plans that Incident Manager uses to engage contacts
         in phases during an incident.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.create_contact)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#create_contact)
         """
-
     async def create_contact_channel(
         self,
         *,
         ContactId: str,
         Name: str,
         Type: ChannelTypeType,
         DeliveryAddress: ContactChannelAddressTypeDef,
@@ -172,191 +179,303 @@
         """
         A contact channel is the method that Incident Manager uses to engage your
         contact.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.create_contact_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#create_contact_channel)
         """
+    async def create_rotation(
+        self,
+        *,
+        Name: str,
+        ContactIds: Sequence[str],
+        TimeZoneId: str,
+        Recurrence: RecurrenceSettingsTypeDef,
+        StartTime: Union[datetime, str] = ...,
+        Tags: Sequence[TagTypeDef] = ...,
+        IdempotencyToken: str = ...
+    ) -> CreateRotationResultTypeDef:
+        """
+        Creates a rotation in an on-call schedule.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.create_rotation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#create_rotation)
+        """
+    async def create_rotation_override(
+        self,
+        *,
+        RotationId: str,
+        NewContactIds: Sequence[str],
+        StartTime: Union[datetime, str],
+        EndTime: Union[datetime, str],
+        IdempotencyToken: str = ...
+    ) -> CreateRotationOverrideResultTypeDef:
+        """
+        Creates an override for a rotation in an on-call schedule.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.create_rotation_override)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#create_rotation_override)
+        """
     async def deactivate_contact_channel(self, *, ContactChannelId: str) -> Dict[str, Any]:
         """
         To no longer receive Incident Manager engagements to a contact channel, you can
         deactivate the channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.deactivate_contact_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#deactivate_contact_channel)
         """
-
     async def delete_contact(self, *, ContactId: str) -> Dict[str, Any]:
         """
         To remove a contact from Incident Manager, you can delete the contact.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.delete_contact)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#delete_contact)
         """
-
     async def delete_contact_channel(self, *, ContactChannelId: str) -> Dict[str, Any]:
         """
         To no longer receive engagements on a contact channel, you can delete the
         channel from a contact.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.delete_contact_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#delete_contact_channel)
         """
+    async def delete_rotation(self, *, RotationId: str) -> Dict[str, Any]:
+        """
+        Deletes a rotation from the system.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.delete_rotation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#delete_rotation)
+        """
+    async def delete_rotation_override(
+        self, *, RotationId: str, RotationOverrideId: str
+    ) -> Dict[str, Any]:
+        """
+        Deletes an existing override for an on-call rotation.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.delete_rotation_override)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#delete_rotation_override)
+        """
     async def describe_engagement(self, *, EngagementId: str) -> DescribeEngagementResultTypeDef:
         """
         Incident Manager uses engagements to engage contacts and escalation plans during
         an incident.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.describe_engagement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#describe_engagement)
         """
-
     async def describe_page(self, *, PageId: str) -> DescribePageResultTypeDef:
         """
         Lists details of the engagement to a contact channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.describe_page)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#describe_page)
         """
-
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#generate_presigned_url)
         """
-
     async def get_contact(self, *, ContactId: str) -> GetContactResultTypeDef:
         """
         Retrieves information about the specified contact or escalation plan.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_contact)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_contact)
         """
-
     async def get_contact_channel(self, *, ContactChannelId: str) -> GetContactChannelResultTypeDef:
         """
         List details about a specific contact channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_contact_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_contact_channel)
         """
-
     async def get_contact_policy(self, *, ContactArn: str) -> GetContactPolicyResultTypeDef:
         """
         Retrieves the resource policies attached to the specified contact or escalation
         plan.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_contact_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_contact_policy)
         """
+    async def get_rotation(self, *, RotationId: str) -> GetRotationResultTypeDef:
+        """
+        Retrieves information about an on-call rotation.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_rotation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_rotation)
+        """
+    async def get_rotation_override(
+        self, *, RotationId: str, RotationOverrideId: str
+    ) -> GetRotationOverrideResultTypeDef:
+        """
+        Retrieves information about an override to an on-call rotation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_rotation_override)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_rotation_override)
+        """
     async def list_contact_channels(
         self, *, ContactId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListContactChannelsResultTypeDef:
         """
         Lists all contact channels for the specified contact.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_contact_channels)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_contact_channels)
         """
-
     async def list_contacts(
         self,
         *,
         NextToken: str = ...,
         MaxResults: int = ...,
         AliasPrefix: str = ...,
         Type: ContactTypeType = ...
     ) -> ListContactsResultTypeDef:
         """
         Lists all contacts and escalation plans in Incident Manager.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_contacts)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_contacts)
         """
-
     async def list_engagements(
         self,
         *,
         NextToken: str = ...,
         MaxResults: int = ...,
         IncidentId: str = ...,
         TimeRangeValue: TimeRangeTypeDef = ...
     ) -> ListEngagementsResultTypeDef:
         """
         Lists all engagements that have happened in an incident.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_engagements)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_engagements)
         """
-
     async def list_page_receipts(
         self, *, PageId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListPageReceiptsResultTypeDef:
         """
         Lists all of the engagements to contact channels that have been acknowledged.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_page_receipts)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_page_receipts)
         """
+    async def list_page_resolutions(
+        self, *, PageId: str, NextToken: str = ...
+    ) -> ListPageResolutionsResultTypeDef:
+        """
+        Returns the resolution path of an engagement.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_page_resolutions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_page_resolutions)
+        """
     async def list_pages_by_contact(
         self, *, ContactId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListPagesByContactResultTypeDef:
         """
         Lists the engagements to a contact's contact channels.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_pages_by_contact)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_pages_by_contact)
         """
-
     async def list_pages_by_engagement(
         self, *, EngagementId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListPagesByEngagementResultTypeDef:
         """
         Lists the engagements to contact channels that occurred by engaging a contact.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_pages_by_engagement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_pages_by_engagement)
         """
+    async def list_preview_rotation_shifts(
+        self,
+        *,
+        EndTime: Union[datetime, str],
+        Members: Sequence[str],
+        TimeZoneId: str,
+        Recurrence: RecurrenceSettingsTypeDef,
+        RotationStartTime: Union[datetime, str] = ...,
+        StartTime: Union[datetime, str] = ...,
+        Overrides: Sequence[PreviewOverrideTypeDef] = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> ListPreviewRotationShiftsResultTypeDef:
+        """
+        Returns a list of shifts based on rotation configuration parameters.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_preview_rotation_shifts)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_preview_rotation_shifts)
+        """
+    async def list_rotation_overrides(
+        self,
+        *,
+        RotationId: str,
+        StartTime: Union[datetime, str],
+        EndTime: Union[datetime, str],
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> ListRotationOverridesResultTypeDef:
+        """
+        Retrieves a list of overrides currently specified for an on-call rotation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_rotation_overrides)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_rotation_overrides)
+        """
+    async def list_rotation_shifts(
+        self,
+        *,
+        RotationId: str,
+        EndTime: Union[datetime, str],
+        StartTime: Union[datetime, str] = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> ListRotationShiftsResultTypeDef:
+        """
+        Returns a list of shifts generated by an existing rotation in the system.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_rotation_shifts)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_rotation_shifts)
+        """
+    async def list_rotations(
+        self, *, RotationNamePrefix: str = ..., NextToken: str = ..., MaxResults: int = ...
+    ) -> ListRotationsResultTypeDef:
+        """
+        Retrieves a list of on-call rotations.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_rotations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_rotations)
+        """
     async def list_tags_for_resource(self, *, ResourceARN: str) -> ListTagsForResourceResultTypeDef:
         """
         Lists the tags of an escalation plan or contact.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_tags_for_resource)
         """
-
     async def put_contact_policy(self, *, ContactArn: str, Policy: str) -> Dict[str, Any]:
         """
         Adds a resource policy to the specified contact or escalation plan.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.put_contact_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#put_contact_policy)
         """
-
     async def send_activation_code(self, *, ContactChannelId: str) -> Dict[str, Any]:
         """
         Sends an activation code to a contact channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.send_activation_code)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#send_activation_code)
         """
-
     async def start_engagement(
         self,
         *,
         ContactId: str,
         Sender: str,
         Subject: str,
         Content: str,
@@ -367,120 +486,160 @@
     ) -> StartEngagementResultTypeDef:
         """
         Starts an engagement to a contact or escalation plan.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.start_engagement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#start_engagement)
         """
-
     async def stop_engagement(self, *, EngagementId: str, Reason: str = ...) -> Dict[str, Any]:
         """
         Stops an engagement before it finishes the final stage of the escalation plan or
         engagement plan.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.stop_engagement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#stop_engagement)
         """
-
     async def tag_resource(self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Tags a contact or escalation plan.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#tag_resource)
         """
-
     async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes tags from the specified resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#untag_resource)
         """
-
     async def update_contact(
         self, *, ContactId: str, DisplayName: str = ..., Plan: PlanTypeDef = ...
     ) -> Dict[str, Any]:
         """
         Updates the contact or escalation plan specified.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.update_contact)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#update_contact)
         """
-
     async def update_contact_channel(
         self,
         *,
         ContactChannelId: str,
         Name: str = ...,
         DeliveryAddress: ContactChannelAddressTypeDef = ...
     ) -> Dict[str, Any]:
         """
         Updates a contact's contact channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.update_contact_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#update_contact_channel)
         """
+    async def update_rotation(
+        self,
+        *,
+        RotationId: str,
+        Recurrence: RecurrenceSettingsTypeDef,
+        ContactIds: Sequence[str] = ...,
+        StartTime: Union[datetime, str] = ...,
+        TimeZoneId: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Updates the information specified for an on-call rotation.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.update_rotation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#update_rotation)
+        """
     @overload
     def get_paginator(
         self, operation_name: Literal["list_contact_channels"]
     ) -> ListContactChannelsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
         """
-
     @overload
     def get_paginator(self, operation_name: Literal["list_contacts"]) -> ListContactsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_engagements"]
     ) -> ListEngagementsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_page_receipts"]
     ) -> ListPageReceiptsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
         """
-
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_page_resolutions"]
+    ) -> ListPageResolutionsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
+        """
     @overload
     def get_paginator(
         self, operation_name: Literal["list_pages_by_contact"]
     ) -> ListPagesByContactPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_pages_by_engagement"]
     ) -> ListPagesByEngagementPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
         """
-
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_preview_rotation_shifts"]
+    ) -> ListPreviewRotationShiftsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_rotation_overrides"]
+    ) -> ListRotationOverridesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_rotation_shifts"]
+    ) -> ListRotationShiftsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(self, operation_name: Literal["list_rotations"]) -> ListRotationsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
+        """
     async def __aenter__(self) -> "SSMContactsClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/)
         """
```

### Comparing `types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/client.pyi` & `types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/client.py`

 * *Files 20% similar despite different names*

```diff
@@ -11,75 +11,96 @@
 
     session = get_session()
     async with session.create_client("ssm-contacts") as client:
         client: SSMContactsClient
     ```
 """
 import sys
-from typing import Any, Dict, Mapping, Sequence, Type, overload
+from datetime import datetime
+from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import AcceptCodeValidationType, AcceptTypeType, ChannelTypeType, ContactTypeType
 from .paginator import (
     ListContactChannelsPaginator,
     ListContactsPaginator,
     ListEngagementsPaginator,
     ListPageReceiptsPaginator,
+    ListPageResolutionsPaginator,
     ListPagesByContactPaginator,
     ListPagesByEngagementPaginator,
+    ListPreviewRotationShiftsPaginator,
+    ListRotationOverridesPaginator,
+    ListRotationShiftsPaginator,
+    ListRotationsPaginator,
 )
 from .type_defs import (
     ContactChannelAddressTypeDef,
     CreateContactChannelResultTypeDef,
     CreateContactResultTypeDef,
+    CreateRotationOverrideResultTypeDef,
+    CreateRotationResultTypeDef,
     DescribeEngagementResultTypeDef,
     DescribePageResultTypeDef,
     GetContactChannelResultTypeDef,
     GetContactPolicyResultTypeDef,
     GetContactResultTypeDef,
+    GetRotationOverrideResultTypeDef,
+    GetRotationResultTypeDef,
     ListContactChannelsResultTypeDef,
     ListContactsResultTypeDef,
     ListEngagementsResultTypeDef,
     ListPageReceiptsResultTypeDef,
+    ListPageResolutionsResultTypeDef,
     ListPagesByContactResultTypeDef,
     ListPagesByEngagementResultTypeDef,
+    ListPreviewRotationShiftsResultTypeDef,
+    ListRotationOverridesResultTypeDef,
+    ListRotationShiftsResultTypeDef,
+    ListRotationsResultTypeDef,
     ListTagsForResourceResultTypeDef,
     PlanTypeDef,
+    PreviewOverrideTypeDef,
+    RecurrenceSettingsTypeDef,
     StartEngagementResultTypeDef,
     TagTypeDef,
     TimeRangeTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = ("SSMContactsClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     DataEncryptionException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
+
 class SSMContactsClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/)
     """
 
     meta: ClientMeta
@@ -88,14 +109,15 @@
     def exceptions(self) -> Exceptions:
         """
         SSMContactsClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#exceptions)
         """
+
     async def accept_page(
         self,
         *,
         PageId: str,
         AcceptType: AcceptTypeType,
         AcceptCode: str,
         ContactChannelId: str = ...,
@@ -104,37 +126,41 @@
     ) -> Dict[str, Any]:
         """
         Used to acknowledge an engagement to a contact channel during an incident.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.accept_page)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#accept_page)
         """
+
     async def activate_contact_channel(
         self, *, ContactChannelId: str, ActivationCode: str
     ) -> Dict[str, Any]:
         """
         Activates a contact's contact channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.activate_contact_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#activate_contact_channel)
         """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#can_paginate)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#close)
         """
+
     async def create_contact(
         self,
         *,
         Alias: str,
         Type: ContactTypeType,
         Plan: PlanTypeDef,
         DisplayName: str = ...,
@@ -145,14 +171,15 @@
         Contacts are either the contacts that Incident Manager engages during an
         incident or the escalation plans that Incident Manager uses to engage contacts
         in phases during an incident.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.create_contact)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#create_contact)
         """
+
     async def create_contact_channel(
         self,
         *,
         ContactId: str,
         Name: str,
         Type: ChannelTypeType,
         DeliveryAddress: ContactChannelAddressTypeDef,
@@ -162,172 +189,333 @@
         """
         A contact channel is the method that Incident Manager uses to engage your
         contact.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.create_contact_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#create_contact_channel)
         """
+
+    async def create_rotation(
+        self,
+        *,
+        Name: str,
+        ContactIds: Sequence[str],
+        TimeZoneId: str,
+        Recurrence: RecurrenceSettingsTypeDef,
+        StartTime: Union[datetime, str] = ...,
+        Tags: Sequence[TagTypeDef] = ...,
+        IdempotencyToken: str = ...
+    ) -> CreateRotationResultTypeDef:
+        """
+        Creates a rotation in an on-call schedule.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.create_rotation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#create_rotation)
+        """
+
+    async def create_rotation_override(
+        self,
+        *,
+        RotationId: str,
+        NewContactIds: Sequence[str],
+        StartTime: Union[datetime, str],
+        EndTime: Union[datetime, str],
+        IdempotencyToken: str = ...
+    ) -> CreateRotationOverrideResultTypeDef:
+        """
+        Creates an override for a rotation in an on-call schedule.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.create_rotation_override)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#create_rotation_override)
+        """
+
     async def deactivate_contact_channel(self, *, ContactChannelId: str) -> Dict[str, Any]:
         """
         To no longer receive Incident Manager engagements to a contact channel, you can
         deactivate the channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.deactivate_contact_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#deactivate_contact_channel)
         """
+
     async def delete_contact(self, *, ContactId: str) -> Dict[str, Any]:
         """
         To remove a contact from Incident Manager, you can delete the contact.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.delete_contact)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#delete_contact)
         """
+
     async def delete_contact_channel(self, *, ContactChannelId: str) -> Dict[str, Any]:
         """
         To no longer receive engagements on a contact channel, you can delete the
         channel from a contact.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.delete_contact_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#delete_contact_channel)
         """
+
+    async def delete_rotation(self, *, RotationId: str) -> Dict[str, Any]:
+        """
+        Deletes a rotation from the system.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.delete_rotation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#delete_rotation)
+        """
+
+    async def delete_rotation_override(
+        self, *, RotationId: str, RotationOverrideId: str
+    ) -> Dict[str, Any]:
+        """
+        Deletes an existing override for an on-call rotation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.delete_rotation_override)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#delete_rotation_override)
+        """
+
     async def describe_engagement(self, *, EngagementId: str) -> DescribeEngagementResultTypeDef:
         """
         Incident Manager uses engagements to engage contacts and escalation plans during
         an incident.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.describe_engagement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#describe_engagement)
         """
+
     async def describe_page(self, *, PageId: str) -> DescribePageResultTypeDef:
         """
         Lists details of the engagement to a contact channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.describe_page)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#describe_page)
         """
+
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#generate_presigned_url)
         """
+
     async def get_contact(self, *, ContactId: str) -> GetContactResultTypeDef:
         """
         Retrieves information about the specified contact or escalation plan.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_contact)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_contact)
         """
+
     async def get_contact_channel(self, *, ContactChannelId: str) -> GetContactChannelResultTypeDef:
         """
         List details about a specific contact channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_contact_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_contact_channel)
         """
+
     async def get_contact_policy(self, *, ContactArn: str) -> GetContactPolicyResultTypeDef:
         """
         Retrieves the resource policies attached to the specified contact or escalation
         plan.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_contact_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_contact_policy)
         """
+
+    async def get_rotation(self, *, RotationId: str) -> GetRotationResultTypeDef:
+        """
+        Retrieves information about an on-call rotation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_rotation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_rotation)
+        """
+
+    async def get_rotation_override(
+        self, *, RotationId: str, RotationOverrideId: str
+    ) -> GetRotationOverrideResultTypeDef:
+        """
+        Retrieves information about an override to an on-call rotation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_rotation_override)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_rotation_override)
+        """
+
     async def list_contact_channels(
         self, *, ContactId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListContactChannelsResultTypeDef:
         """
         Lists all contact channels for the specified contact.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_contact_channels)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_contact_channels)
         """
+
     async def list_contacts(
         self,
         *,
         NextToken: str = ...,
         MaxResults: int = ...,
         AliasPrefix: str = ...,
         Type: ContactTypeType = ...
     ) -> ListContactsResultTypeDef:
         """
         Lists all contacts and escalation plans in Incident Manager.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_contacts)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_contacts)
         """
+
     async def list_engagements(
         self,
         *,
         NextToken: str = ...,
         MaxResults: int = ...,
         IncidentId: str = ...,
         TimeRangeValue: TimeRangeTypeDef = ...
     ) -> ListEngagementsResultTypeDef:
         """
         Lists all engagements that have happened in an incident.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_engagements)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_engagements)
         """
+
     async def list_page_receipts(
         self, *, PageId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListPageReceiptsResultTypeDef:
         """
         Lists all of the engagements to contact channels that have been acknowledged.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_page_receipts)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_page_receipts)
         """
+
+    async def list_page_resolutions(
+        self, *, PageId: str, NextToken: str = ...
+    ) -> ListPageResolutionsResultTypeDef:
+        """
+        Returns the resolution path of an engagement.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_page_resolutions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_page_resolutions)
+        """
+
     async def list_pages_by_contact(
         self, *, ContactId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListPagesByContactResultTypeDef:
         """
         Lists the engagements to a contact's contact channels.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_pages_by_contact)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_pages_by_contact)
         """
+
     async def list_pages_by_engagement(
         self, *, EngagementId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListPagesByEngagementResultTypeDef:
         """
         Lists the engagements to contact channels that occurred by engaging a contact.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_pages_by_engagement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_pages_by_engagement)
         """
+
+    async def list_preview_rotation_shifts(
+        self,
+        *,
+        EndTime: Union[datetime, str],
+        Members: Sequence[str],
+        TimeZoneId: str,
+        Recurrence: RecurrenceSettingsTypeDef,
+        RotationStartTime: Union[datetime, str] = ...,
+        StartTime: Union[datetime, str] = ...,
+        Overrides: Sequence[PreviewOverrideTypeDef] = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> ListPreviewRotationShiftsResultTypeDef:
+        """
+        Returns a list of shifts based on rotation configuration parameters.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_preview_rotation_shifts)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_preview_rotation_shifts)
+        """
+
+    async def list_rotation_overrides(
+        self,
+        *,
+        RotationId: str,
+        StartTime: Union[datetime, str],
+        EndTime: Union[datetime, str],
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> ListRotationOverridesResultTypeDef:
+        """
+        Retrieves a list of overrides currently specified for an on-call rotation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_rotation_overrides)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_rotation_overrides)
+        """
+
+    async def list_rotation_shifts(
+        self,
+        *,
+        RotationId: str,
+        EndTime: Union[datetime, str],
+        StartTime: Union[datetime, str] = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> ListRotationShiftsResultTypeDef:
+        """
+        Returns a list of shifts generated by an existing rotation in the system.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_rotation_shifts)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_rotation_shifts)
+        """
+
+    async def list_rotations(
+        self, *, RotationNamePrefix: str = ..., NextToken: str = ..., MaxResults: int = ...
+    ) -> ListRotationsResultTypeDef:
+        """
+        Retrieves a list of on-call rotations.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_rotations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_rotations)
+        """
+
     async def list_tags_for_resource(self, *, ResourceARN: str) -> ListTagsForResourceResultTypeDef:
         """
         Lists the tags of an escalation plan or contact.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#list_tags_for_resource)
         """
+
     async def put_contact_policy(self, *, ContactArn: str, Policy: str) -> Dict[str, Any]:
         """
         Adds a resource policy to the specified contact or escalation plan.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.put_contact_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#put_contact_policy)
         """
+
     async def send_activation_code(self, *, ContactChannelId: str) -> Dict[str, Any]:
         """
         Sends an activation code to a contact channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.send_activation_code)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#send_activation_code)
         """
+
     async def start_engagement(
         self,
         *,
         ContactId: str,
         Sender: str,
         Subject: str,
         Content: str,
@@ -338,107 +526,179 @@
     ) -> StartEngagementResultTypeDef:
         """
         Starts an engagement to a contact or escalation plan.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.start_engagement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#start_engagement)
         """
+
     async def stop_engagement(self, *, EngagementId: str, Reason: str = ...) -> Dict[str, Any]:
         """
         Stops an engagement before it finishes the final stage of the escalation plan or
         engagement plan.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.stop_engagement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#stop_engagement)
         """
+
     async def tag_resource(self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Tags a contact or escalation plan.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#tag_resource)
         """
+
     async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes tags from the specified resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#untag_resource)
         """
+
     async def update_contact(
         self, *, ContactId: str, DisplayName: str = ..., Plan: PlanTypeDef = ...
     ) -> Dict[str, Any]:
         """
         Updates the contact or escalation plan specified.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.update_contact)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#update_contact)
         """
+
     async def update_contact_channel(
         self,
         *,
         ContactChannelId: str,
         Name: str = ...,
         DeliveryAddress: ContactChannelAddressTypeDef = ...
     ) -> Dict[str, Any]:
         """
         Updates a contact's contact channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.update_contact_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#update_contact_channel)
         """
+
+    async def update_rotation(
+        self,
+        *,
+        RotationId: str,
+        Recurrence: RecurrenceSettingsTypeDef,
+        ContactIds: Sequence[str] = ...,
+        StartTime: Union[datetime, str] = ...,
+        TimeZoneId: str = ...
+    ) -> Dict[str, Any]:
+        """
+        Updates the information specified for an on-call rotation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.update_rotation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#update_rotation)
+        """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_contact_channels"]
     ) -> ListContactChannelsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
         """
+
     @overload
     def get_paginator(self, operation_name: Literal["list_contacts"]) -> ListContactsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_engagements"]
     ) -> ListEngagementsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_page_receipts"]
     ) -> ListPageReceiptsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
         """
+
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_page_resolutions"]
+    ) -> ListPageResolutionsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
+        """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_pages_by_contact"]
     ) -> ListPagesByContactPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_pages_by_engagement"]
     ) -> ListPagesByEngagementPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
         """
+
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_preview_rotation_shifts"]
+    ) -> ListPreviewRotationShiftsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_rotation_overrides"]
+    ) -> ListRotationOverridesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_rotation_shifts"]
+    ) -> ListRotationShiftsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(self, operation_name: Literal["list_rotations"]) -> ListRotationsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/#get_paginator)
+        """
+
     async def __aenter__(self) -> "SSMContactsClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/client/)
         """
```

### Comparing `types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/literals.py` & `types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/literals.py`

 * *Files 5% similar despite different names*

```diff
@@ -21,40 +21,54 @@
 
 __all__ = (
     "AcceptCodeValidationType",
     "AcceptTypeType",
     "ActivationStatusType",
     "ChannelTypeType",
     "ContactTypeType",
+    "DayOfWeekType",
     "ListContactChannelsPaginatorName",
     "ListContactsPaginatorName",
     "ListEngagementsPaginatorName",
     "ListPageReceiptsPaginatorName",
+    "ListPageResolutionsPaginatorName",
     "ListPagesByContactPaginatorName",
     "ListPagesByEngagementPaginatorName",
+    "ListPreviewRotationShiftsPaginatorName",
+    "ListRotationOverridesPaginatorName",
+    "ListRotationShiftsPaginatorName",
+    "ListRotationsPaginatorName",
     "ReceiptTypeType",
+    "ShiftTypeType",
     "SSMContactsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
 
 AcceptCodeValidationType = Literal["ENFORCE", "IGNORE"]
 AcceptTypeType = Literal["DELIVERED", "READ"]
 ActivationStatusType = Literal["ACTIVATED", "NOT_ACTIVATED"]
 ChannelTypeType = Literal["EMAIL", "SMS", "VOICE"]
-ContactTypeType = Literal["ESCALATION", "PERSONAL"]
+ContactTypeType = Literal["ESCALATION", "ONCALL_SCHEDULE", "PERSONAL"]
+DayOfWeekType = Literal["FRI", "MON", "SAT", "SUN", "THU", "TUE", "WED"]
 ListContactChannelsPaginatorName = Literal["list_contact_channels"]
 ListContactsPaginatorName = Literal["list_contacts"]
 ListEngagementsPaginatorName = Literal["list_engagements"]
 ListPageReceiptsPaginatorName = Literal["list_page_receipts"]
+ListPageResolutionsPaginatorName = Literal["list_page_resolutions"]
 ListPagesByContactPaginatorName = Literal["list_pages_by_contact"]
 ListPagesByEngagementPaginatorName = Literal["list_pages_by_engagement"]
+ListPreviewRotationShiftsPaginatorName = Literal["list_preview_rotation_shifts"]
+ListRotationOverridesPaginatorName = Literal["list_rotation_overrides"]
+ListRotationShiftsPaginatorName = Literal["list_rotation_shifts"]
+ListRotationsPaginatorName = Literal["list_rotations"]
 ReceiptTypeType = Literal["DELIVERED", "ERROR", "READ", "SENT", "STOP"]
+ShiftTypeType = Literal["OVERRIDDEN", "REGULAR"]
 SSMContactsServiceName = Literal["ssm-contacts"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -110,14 +124,15 @@
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
@@ -196,14 +211,15 @@
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
@@ -214,14 +230,15 @@
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
@@ -257,14 +274,15 @@
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
@@ -283,16 +301,19 @@
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
@@ -376,15 +397,17 @@
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
@@ -407,10 +430,15 @@
     "sqs",
 ]
 PaginatorName = Literal[
     "list_contact_channels",
     "list_contacts",
     "list_engagements",
     "list_page_receipts",
+    "list_page_resolutions",
     "list_pages_by_contact",
     "list_pages_by_engagement",
+    "list_preview_rotation_shifts",
+    "list_rotation_overrides",
+    "list_rotation_shifts",
+    "list_rotations",
 ]
```

### Comparing `types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts/literals.pyi` & `types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts/literals.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -20,39 +20,53 @@
 
 __all__ = (
     "AcceptCodeValidationType",
     "AcceptTypeType",
     "ActivationStatusType",
     "ChannelTypeType",
     "ContactTypeType",
+    "DayOfWeekType",
     "ListContactChannelsPaginatorName",
     "ListContactsPaginatorName",
     "ListEngagementsPaginatorName",
     "ListPageReceiptsPaginatorName",
+    "ListPageResolutionsPaginatorName",
     "ListPagesByContactPaginatorName",
     "ListPagesByEngagementPaginatorName",
+    "ListPreviewRotationShiftsPaginatorName",
+    "ListRotationOverridesPaginatorName",
+    "ListRotationShiftsPaginatorName",
+    "ListRotationsPaginatorName",
     "ReceiptTypeType",
+    "ShiftTypeType",
     "SSMContactsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
 AcceptCodeValidationType = Literal["ENFORCE", "IGNORE"]
 AcceptTypeType = Literal["DELIVERED", "READ"]
 ActivationStatusType = Literal["ACTIVATED", "NOT_ACTIVATED"]
 ChannelTypeType = Literal["EMAIL", "SMS", "VOICE"]
-ContactTypeType = Literal["ESCALATION", "PERSONAL"]
+ContactTypeType = Literal["ESCALATION", "ONCALL_SCHEDULE", "PERSONAL"]
+DayOfWeekType = Literal["FRI", "MON", "SAT", "SUN", "THU", "TUE", "WED"]
 ListContactChannelsPaginatorName = Literal["list_contact_channels"]
 ListContactsPaginatorName = Literal["list_contacts"]
 ListEngagementsPaginatorName = Literal["list_engagements"]
 ListPageReceiptsPaginatorName = Literal["list_page_receipts"]
+ListPageResolutionsPaginatorName = Literal["list_page_resolutions"]
 ListPagesByContactPaginatorName = Literal["list_pages_by_contact"]
 ListPagesByEngagementPaginatorName = Literal["list_pages_by_engagement"]
+ListPreviewRotationShiftsPaginatorName = Literal["list_preview_rotation_shifts"]
+ListRotationOverridesPaginatorName = Literal["list_rotation_overrides"]
+ListRotationShiftsPaginatorName = Literal["list_rotation_shifts"]
+ListRotationsPaginatorName = Literal["list_rotations"]
 ReceiptTypeType = Literal["DELIVERED", "ERROR", "READ", "SENT", "STOP"]
+ShiftTypeType = Literal["OVERRIDDEN", "REGULAR"]
 SSMContactsServiceName = Literal["ssm-contacts"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -108,14 +122,15 @@
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
@@ -194,14 +209,15 @@
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
@@ -212,14 +228,15 @@
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
@@ -255,14 +272,15 @@
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
@@ -281,16 +299,19 @@
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
@@ -374,15 +395,17 @@
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
@@ -405,10 +428,15 @@
     "sqs",
 ]
 PaginatorName = Literal[
     "list_contact_channels",
     "list_contacts",
     "list_engagements",
     "list_page_receipts",
+    "list_page_resolutions",
     "list_pages_by_contact",
     "list_pages_by_engagement",
+    "list_preview_rotation_shifts",
+    "list_rotation_overrides",
+    "list_rotation_shifts",
+    "list_rotations",
 ]
```

### Comparing `types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts.egg-info/PKG-INFO` & `types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts.egg-info/PKG-INFO`

 * *Files 20% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ssm-contacts
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SSMContacts 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SSMContacts 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ssm-contacts"></a>
 
 # types-aiobotocore-ssm-contacts
 
 [![PyPI - types-aiobotocore-ssm-contacts](https://img.shields.io/pypi/v/types-aiobotocore-ssm-contacts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-contacts)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ssm-contacts.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-contacts)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ssm-contacts?color=blue)](https://pypistats.org/packages/types-aiobotocore-ssm-contacts)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSMContacts 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts)
+[aiobotocore.SSMContacts 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-contacts.html#SSMContacts)
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
 [types-aiobotocore-ssm-contacts docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_contacts/).
 
 See how it helps to find and fix potential bugs:
 
@@ -277,16 +277,21 @@
 
 from types_aiobotocore_ssm_contacts import SSMContactsClient
 from types_aiobotocore_ssm_contacts.paginator import (
     ListContactChannelsPaginator,
     ListContactsPaginator,
     ListEngagementsPaginator,
     ListPageReceiptsPaginator,
+    ListPageResolutionsPaginator,
     ListPagesByContactPaginator,
     ListPagesByEngagementPaginator,
+    ListPreviewRotationShiftsPaginator,
+    ListRotationOverridesPaginator,
+    ListRotationShiftsPaginator,
+    ListRotationsPaginator,
 )
 
 session = get_session()
 async with session.create_client("ssm-contacts") as client:
     client: SSMContactsClient
 
     # Explicit type annotations are optional here
@@ -295,20 +300,33 @@
         "list_contact_channels"
     )
     list_contacts_paginator: ListContactsPaginator = client.get_paginator("list_contacts")
     list_engagements_paginator: ListEngagementsPaginator = client.get_paginator("list_engagements")
     list_page_receipts_paginator: ListPageReceiptsPaginator = client.get_paginator(
         "list_page_receipts"
     )
+    list_page_resolutions_paginator: ListPageResolutionsPaginator = client.get_paginator(
+        "list_page_resolutions"
+    )
     list_pages_by_contact_paginator: ListPagesByContactPaginator = client.get_paginator(
         "list_pages_by_contact"
     )
     list_pages_by_engagement_paginator: ListPagesByEngagementPaginator = client.get_paginator(
         "list_pages_by_engagement"
     )
+    list_preview_rotation_shifts_paginator: ListPreviewRotationShiftsPaginator = (
+        client.get_paginator("list_preview_rotation_shifts")
+    )
+    list_rotation_overrides_paginator: ListRotationOverridesPaginator = client.get_paginator(
+        "list_rotation_overrides"
+    )
+    list_rotation_shifts_paginator: ListRotationShiftsPaginator = client.get_paginator(
+        "list_rotation_shifts"
+    )
+    list_rotations_paginator: ListRotationsPaginator = client.get_paginator("list_rotations")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_ssm_contacts.literals` module contains literals extracted
@@ -317,21 +335,28 @@
 ```python
 from types_aiobotocore_ssm_contacts.literals import (
     AcceptCodeValidationType,
     AcceptTypeType,
     ActivationStatusType,
     ChannelTypeType,
     ContactTypeType,
+    DayOfWeekType,
     ListContactChannelsPaginatorName,
     ListContactsPaginatorName,
     ListEngagementsPaginatorName,
     ListPageReceiptsPaginatorName,
+    ListPageResolutionsPaginatorName,
     ListPagesByContactPaginatorName,
     ListPagesByEngagementPaginatorName,
+    ListPreviewRotationShiftsPaginatorName,
+    ListRotationOverridesPaginatorName,
+    ListRotationShiftsPaginatorName,
+    ListRotationsPaginatorName,
     ReceiptTypeType,
+    ShiftTypeType,
     SSMContactsServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
 )
 
 
@@ -350,114 +375,151 @@
 from types_aiobotocore_ssm_contacts.type_defs import (
     AcceptPageRequestRequestTypeDef,
     ActivateContactChannelRequestRequestTypeDef,
     ChannelTargetInfoTypeDef,
     ContactChannelAddressTypeDef,
     ContactTargetInfoTypeDef,
     ContactTypeDef,
-    ResponseMetadataTypeDef,
+    HandOffTimeTypeDef,
+    CreateContactChannelResultTypeDef,
     TagTypeDef,
+    CreateContactResultTypeDef,
+    CreateRotationOverrideRequestRequestTypeDef,
+    CreateRotationOverrideResultTypeDef,
+    CreateRotationResultTypeDef,
     DeactivateContactChannelRequestRequestTypeDef,
     DeleteContactChannelRequestRequestTypeDef,
     DeleteContactRequestRequestTypeDef,
+    DeleteRotationOverrideRequestRequestTypeDef,
+    DeleteRotationRequestRequestTypeDef,
     DescribeEngagementRequestRequestTypeDef,
+    DescribeEngagementResultTypeDef,
     DescribePageRequestRequestTypeDef,
+    DescribePageResultTypeDef,
     EngagementTypeDef,
     GetContactChannelRequestRequestTypeDef,
     GetContactPolicyRequestRequestTypeDef,
+    GetContactPolicyResultTypeDef,
     GetContactRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetRotationOverrideRequestRequestTypeDef,
+    GetRotationOverrideResultTypeDef,
+    GetRotationRequestRequestTypeDef,
+    ListContactChannelsRequestListContactChannelsPaginateTypeDef,
     ListContactChannelsRequestRequestTypeDef,
+    ListContactsRequestListContactsPaginateTypeDef,
     ListContactsRequestRequestTypeDef,
     TimeRangeTypeDef,
+    ListPageReceiptsRequestListPageReceiptsPaginateTypeDef,
     ListPageReceiptsRequestRequestTypeDef,
     ReceiptTypeDef,
+    ListPageResolutionsRequestListPageResolutionsPaginateTypeDef,
+    ListPageResolutionsRequestRequestTypeDef,
+    ResolutionContactTypeDef,
+    ListPagesByContactRequestListPagesByContactPaginateTypeDef,
     ListPagesByContactRequestRequestTypeDef,
     PageTypeDef,
+    ListPagesByEngagementRequestListPagesByEngagementPaginateTypeDef,
     ListPagesByEngagementRequestRequestTypeDef,
+    PreviewOverrideTypeDef,
+    ListRotationOverridesRequestListRotationOverridesPaginateTypeDef,
+    ListRotationOverridesRequestRequestTypeDef,
+    RotationOverrideTypeDef,
+    ListRotationShiftsRequestListRotationShiftsPaginateTypeDef,
+    ListRotationShiftsRequestRequestTypeDef,
+    ListRotationsRequestListRotationsPaginateTypeDef,
+    ListRotationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutContactPolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    ShiftDetailsTypeDef,
     SendActivationCodeRequestRequestTypeDef,
     StartEngagementRequestRequestTypeDef,
+    StartEngagementResultTypeDef,
     StopEngagementRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ContactChannelTypeDef,
     CreateContactChannelRequestRequestTypeDef,
+    GetContactChannelResultTypeDef,
     UpdateContactChannelRequestRequestTypeDef,
     TargetTypeDef,
-    CreateContactChannelResultTypeDef,
-    CreateContactResultTypeDef,
-    DescribeEngagementResultTypeDef,
-    DescribePageResultTypeDef,
-    GetContactChannelResultTypeDef,
-    GetContactPolicyResultTypeDef,
     ListContactsResultTypeDef,
-    StartEngagementResultTypeDef,
+    CoverageTimeTypeDef,
+    MonthlySettingTypeDef,
+    WeeklySettingTypeDef,
     ListTagsForResourceResultTypeDef,
     TagResourceRequestRequestTypeDef,
     ListEngagementsResultTypeDef,
-    ListContactChannelsRequestListContactChannelsPaginateTypeDef,
-    ListContactsRequestListContactsPaginateTypeDef,
-    ListPageReceiptsRequestListPageReceiptsPaginateTypeDef,
-    ListPagesByContactRequestListPagesByContactPaginateTypeDef,
-    ListPagesByEngagementRequestListPagesByEngagementPaginateTypeDef,
     ListEngagementsRequestListEngagementsPaginateTypeDef,
     ListEngagementsRequestRequestTypeDef,
     ListPageReceiptsResultTypeDef,
+    ListPageResolutionsResultTypeDef,
     ListPagesByContactResultTypeDef,
     ListPagesByEngagementResultTypeDef,
+    ListRotationOverridesResultTypeDef,
+    RotationShiftTypeDef,
     ListContactChannelsResultTypeDef,
     StageTypeDef,
+    RecurrenceSettingsTypeDef,
+    ListPreviewRotationShiftsResultTypeDef,
+    ListRotationShiftsResultTypeDef,
     PlanTypeDef,
+    CreateRotationRequestRequestTypeDef,
+    GetRotationResultTypeDef,
+    ListPreviewRotationShiftsRequestListPreviewRotationShiftsPaginateTypeDef,
+    ListPreviewRotationShiftsRequestRequestTypeDef,
+    RotationTypeDef,
+    UpdateRotationRequestRequestTypeDef,
     CreateContactRequestRequestTypeDef,
     GetContactResultTypeDef,
     UpdateContactRequestRequestTypeDef,
+    ListRotationsResultTypeDef,
 )
 
 
 def get_structure() -> AcceptPageRequestRequestTypeDef:
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

### Comparing `types-aiobotocore-ssm-contacts-2.5.0.post1/types_aiobotocore_ssm_contacts.egg-info/SOURCES.txt` & `types-aiobotocore-ssm-contacts-2.5.1/types_aiobotocore_ssm_contacts.egg-info/SOURCES.txt`

 * *Files identical despite different names*


# Comparing `tmp/types-aiobotocore-ses-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-ses-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-ses-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:20 2023, max compression
+gzip compressed data, was "types-aiobotocore-ses-2.5.1.tar", last modified: Wed Jun 28 01:44:11 2023, max compression
```

## Comparing `types-aiobotocore-ses-2.5.0.post1.tar` & `types-aiobotocore-ses-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.719631 types-aiobotocore-ses-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:06.000000 types-aiobotocore-ses-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    20907 2023-03-11 12:27:20.719631 types-aiobotocore-ses-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    19352 2023-03-11 12:24:06.000000 types-aiobotocore-ses-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:20.719631 types-aiobotocore-ses-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:24:06.000000 types-aiobotocore-ses-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.711631 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/
--rw-r--r--   0 runner    (1001) docker     (123)     1797 2023-03-11 12:24:06.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1796 2023-03-11 12:24:06.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:24:06.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    52059 2023-03-11 12:24:07.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    51973 2023-03-11 12:24:06.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10679 2023-03-11 12:24:07.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10677 2023-03-11 12:24:07.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6711 2023-03-11 12:24:07.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6703 2023-03-11 12:24:07.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:06.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    47925 2023-03-11 12:24:08.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    47862 2023-03-11 12:24:07.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:06.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     1521 2023-03-11 12:24:07.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     1520 2023-03-11 12:24:07.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.719631 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    20907 2023-03-11 12:27:20.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-03-11 12:27:20.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:20.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:20.000000 types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:11.318215 types-aiobotocore-ses-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20895 2023-06-28 01:44:11.314215 types-aiobotocore-ses-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19346 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:11.318215 types-aiobotocore-ses-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:11.310215 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/
+-rw-r--r--   0 runner    (1001) docker     (123)     1797 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1796 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    52059 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    51973 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10888 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10886 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6601 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6594 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    47999 2023-06-28 01:40:56.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    47936 2023-06-28 01:40:56.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1521 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1520 2023-06-28 01:40:55.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:11.314215 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20895 2023-06-28 01:44:11.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 01:44:11.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:11.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:11.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:11.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:44:11.000000 types-aiobotocore-ses-2.5.1/types_aiobotocore_ses.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-ses-2.5.0.post1/LICENSE` & `types-aiobotocore-ses-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-ses-2.5.0.post1/PKG-INFO` & `types-aiobotocore-ses-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ses
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SES 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SES 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ses"></a>
 
 # types-aiobotocore-ses
 
 [![PyPI - types-aiobotocore-ses](https://img.shields.io/pypi/v/types-aiobotocore-ses.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ses)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ses.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ses)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ses?color=blue)](https://pypistats.org/packages/types-aiobotocore-ses)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SES 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES)
+[aiobotocore.SES 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES)
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
 [types-aiobotocore-ses docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/).
 
 See how it helps to find and fix potential bugs:
 
@@ -400,113 +400,113 @@
     DeleteReceiptFilterRequestRequestTypeDef,
     DeleteReceiptRuleRequestRequestTypeDef,
     DeleteReceiptRuleSetRequestRequestTypeDef,
     DeleteTemplateRequestRequestTypeDef,
     DeleteVerifiedEmailAddressRequestRequestTypeDef,
     DeliveryOptionsTypeDef,
     ReceiptRuleSetMetadataTypeDef,
-    ResponseMetadataTypeDef,
     DescribeConfigurationSetRequestRequestTypeDef,
     ReputationOptionsTypeDef,
     DescribeReceiptRuleRequestRequestTypeDef,
     DescribeReceiptRuleSetRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     KinesisFirehoseDestinationTypeDef,
     SNSDestinationTypeDef,
     ExtensionFieldTypeDef,
+    GetAccountSendingEnabledResponseTypeDef,
     GetCustomVerificationEmailTemplateRequestRequestTypeDef,
+    GetCustomVerificationEmailTemplateResponseTypeDef,
     GetIdentityDkimAttributesRequestRequestTypeDef,
     IdentityDkimAttributesTypeDef,
     GetIdentityMailFromDomainAttributesRequestRequestTypeDef,
     IdentityMailFromDomainAttributesTypeDef,
     GetIdentityNotificationAttributesRequestRequestTypeDef,
     IdentityNotificationAttributesTypeDef,
     GetIdentityPoliciesRequestRequestTypeDef,
+    GetIdentityPoliciesResponseTypeDef,
     WaiterConfigTypeDef,
     GetIdentityVerificationAttributesRequestRequestTypeDef,
     IdentityVerificationAttributesTypeDef,
+    GetSendQuotaResponseTypeDef,
     SendDataPointTypeDef,
     GetTemplateRequestRequestTypeDef,
     LambdaActionTypeDef,
-    PaginatorConfigTypeDef,
+    ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef,
     ListConfigurationSetsRequestRequestTypeDef,
+    ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef,
     ListCustomVerificationEmailTemplatesRequestRequestTypeDef,
+    ListIdentitiesRequestListIdentitiesPaginateTypeDef,
     ListIdentitiesRequestRequestTypeDef,
+    ListIdentitiesResponseTypeDef,
     ListIdentityPoliciesRequestRequestTypeDef,
+    ListIdentityPoliciesResponseTypeDef,
+    ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef,
     ListReceiptRuleSetsRequestRequestTypeDef,
+    ListTemplatesRequestListTemplatesPaginateTypeDef,
     ListTemplatesRequestRequestTypeDef,
     TemplateMetadataTypeDef,
+    ListVerifiedEmailAddressesResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutIdentityPolicyRequestRequestTypeDef,
     RawMessageTypeDef,
     S3ActionTypeDef,
     SNSActionTypeDef,
     StopActionTypeDef,
     WorkmailActionTypeDef,
     ReceiptIpFilterTypeDef,
     ReorderReceiptRuleSetRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SendBounceResponseTypeDef,
     SendCustomVerificationEmailRequestRequestTypeDef,
+    SendCustomVerificationEmailResponseTypeDef,
+    SendEmailResponseTypeDef,
+    SendRawEmailResponseTypeDef,
+    SendTemplatedEmailResponseTypeDef,
     SetActiveReceiptRuleSetRequestRequestTypeDef,
     SetIdentityDkimEnabledRequestRequestTypeDef,
     SetIdentityFeedbackForwardingEnabledRequestRequestTypeDef,
     SetIdentityHeadersInNotificationsEnabledRequestRequestTypeDef,
     SetIdentityMailFromDomainRequestRequestTypeDef,
     SetIdentityNotificationTopicRequestRequestTypeDef,
     SetReceiptRulePositionRequestRequestTypeDef,
     TestRenderTemplateRequestRequestTypeDef,
+    TestRenderTemplateResponseTypeDef,
     UpdateAccountSendingEnabledRequestRequestTypeDef,
     UpdateConfigurationSetReputationMetricsEnabledRequestRequestTypeDef,
     UpdateConfigurationSetSendingEnabledRequestRequestTypeDef,
     UpdateCustomVerificationEmailTemplateRequestRequestTypeDef,
     VerifyDomainDkimRequestRequestTypeDef,
+    VerifyDomainDkimResponseTypeDef,
     VerifyDomainIdentityRequestRequestTypeDef,
+    VerifyDomainIdentityResponseTypeDef,
     VerifyEmailAddressRequestRequestTypeDef,
     VerifyEmailIdentityRequestRequestTypeDef,
     BodyTypeDef,
+    SendBulkTemplatedEmailResponseTypeDef,
     BulkEmailDestinationTypeDef,
     SendTemplatedEmailRequestRequestTypeDef,
     CloudWatchDestinationTypeDef,
     CreateConfigurationSetRequestRequestTypeDef,
+    ListConfigurationSetsResponseTypeDef,
     CreateConfigurationSetTrackingOptionsRequestRequestTypeDef,
     UpdateConfigurationSetTrackingOptionsRequestRequestTypeDef,
     CreateTemplateRequestRequestTypeDef,
-    UpdateTemplateRequestRequestTypeDef,
-    PutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAccountSendingEnabledResponseTypeDef,
-    GetCustomVerificationEmailTemplateResponseTypeDef,
-    GetIdentityPoliciesResponseTypeDef,
-    GetSendQuotaResponseTypeDef,
     GetTemplateResponseTypeDef,
-    ListConfigurationSetsResponseTypeDef,
+    UpdateTemplateRequestRequestTypeDef,
     ListCustomVerificationEmailTemplatesResponseTypeDef,
-    ListIdentitiesResponseTypeDef,
-    ListIdentityPoliciesResponseTypeDef,
+    PutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
     ListReceiptRuleSetsResponseTypeDef,
-    ListVerifiedEmailAddressesResponseTypeDef,
-    SendBounceResponseTypeDef,
-    SendBulkTemplatedEmailResponseTypeDef,
-    SendCustomVerificationEmailResponseTypeDef,
-    SendEmailResponseTypeDef,
-    SendRawEmailResponseTypeDef,
-    SendTemplatedEmailResponseTypeDef,
-    TestRenderTemplateResponseTypeDef,
-    VerifyDomainDkimResponseTypeDef,
-    VerifyDomainIdentityResponseTypeDef,
     MessageDsnTypeDef,
     RecipientDsnFieldsTypeDef,
     GetIdentityDkimAttributesResponseTypeDef,
     GetIdentityMailFromDomainAttributesResponseTypeDef,
     GetIdentityNotificationAttributesResponseTypeDef,
     GetIdentityVerificationAttributesRequestIdentityExistsWaitTypeDef,
     GetIdentityVerificationAttributesResponseTypeDef,
     GetSendStatisticsResponseTypeDef,
-    ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef,
-    ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef,
-    ListIdentitiesRequestListIdentitiesPaginateTypeDef,
-    ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef,
-    ListTemplatesRequestListTemplatesPaginateTypeDef,
     ListTemplatesResponseTypeDef,
     SendRawEmailRequestRequestTypeDef,
     ReceiptActionTypeDef,
     ReceiptFilterTypeDef,
     MessageTypeDef,
     SendBulkTemplatedEmailRequestRequestTypeDef,
     EventDestinationTypeDef,
@@ -534,43 +534,43 @@
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

### Comparing `types-aiobotocore-ses-2.5.0.post1/README.md` & `types-aiobotocore-ses-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-ses"></a>
 
 # types-aiobotocore-ses
 
 [![PyPI - types-aiobotocore-ses](https://img.shields.io/pypi/v/types-aiobotocore-ses.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ses)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ses.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ses)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ses?color=blue)](https://pypistats.org/packages/types-aiobotocore-ses)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SES 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES)
+[aiobotocore.SES 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES)
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
 [types-aiobotocore-ses docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/).
 
 See how it helps to find and fix potential bugs:
 
@@ -367,113 +367,113 @@
     DeleteReceiptFilterRequestRequestTypeDef,
     DeleteReceiptRuleRequestRequestTypeDef,
     DeleteReceiptRuleSetRequestRequestTypeDef,
     DeleteTemplateRequestRequestTypeDef,
     DeleteVerifiedEmailAddressRequestRequestTypeDef,
     DeliveryOptionsTypeDef,
     ReceiptRuleSetMetadataTypeDef,
-    ResponseMetadataTypeDef,
     DescribeConfigurationSetRequestRequestTypeDef,
     ReputationOptionsTypeDef,
     DescribeReceiptRuleRequestRequestTypeDef,
     DescribeReceiptRuleSetRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     KinesisFirehoseDestinationTypeDef,
     SNSDestinationTypeDef,
     ExtensionFieldTypeDef,
+    GetAccountSendingEnabledResponseTypeDef,
     GetCustomVerificationEmailTemplateRequestRequestTypeDef,
+    GetCustomVerificationEmailTemplateResponseTypeDef,
     GetIdentityDkimAttributesRequestRequestTypeDef,
     IdentityDkimAttributesTypeDef,
     GetIdentityMailFromDomainAttributesRequestRequestTypeDef,
     IdentityMailFromDomainAttributesTypeDef,
     GetIdentityNotificationAttributesRequestRequestTypeDef,
     IdentityNotificationAttributesTypeDef,
     GetIdentityPoliciesRequestRequestTypeDef,
+    GetIdentityPoliciesResponseTypeDef,
     WaiterConfigTypeDef,
     GetIdentityVerificationAttributesRequestRequestTypeDef,
     IdentityVerificationAttributesTypeDef,
+    GetSendQuotaResponseTypeDef,
     SendDataPointTypeDef,
     GetTemplateRequestRequestTypeDef,
     LambdaActionTypeDef,
-    PaginatorConfigTypeDef,
+    ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef,
     ListConfigurationSetsRequestRequestTypeDef,
+    ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef,
     ListCustomVerificationEmailTemplatesRequestRequestTypeDef,
+    ListIdentitiesRequestListIdentitiesPaginateTypeDef,
     ListIdentitiesRequestRequestTypeDef,
+    ListIdentitiesResponseTypeDef,
     ListIdentityPoliciesRequestRequestTypeDef,
+    ListIdentityPoliciesResponseTypeDef,
+    ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef,
     ListReceiptRuleSetsRequestRequestTypeDef,
+    ListTemplatesRequestListTemplatesPaginateTypeDef,
     ListTemplatesRequestRequestTypeDef,
     TemplateMetadataTypeDef,
+    ListVerifiedEmailAddressesResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutIdentityPolicyRequestRequestTypeDef,
     RawMessageTypeDef,
     S3ActionTypeDef,
     SNSActionTypeDef,
     StopActionTypeDef,
     WorkmailActionTypeDef,
     ReceiptIpFilterTypeDef,
     ReorderReceiptRuleSetRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SendBounceResponseTypeDef,
     SendCustomVerificationEmailRequestRequestTypeDef,
+    SendCustomVerificationEmailResponseTypeDef,
+    SendEmailResponseTypeDef,
+    SendRawEmailResponseTypeDef,
+    SendTemplatedEmailResponseTypeDef,
     SetActiveReceiptRuleSetRequestRequestTypeDef,
     SetIdentityDkimEnabledRequestRequestTypeDef,
     SetIdentityFeedbackForwardingEnabledRequestRequestTypeDef,
     SetIdentityHeadersInNotificationsEnabledRequestRequestTypeDef,
     SetIdentityMailFromDomainRequestRequestTypeDef,
     SetIdentityNotificationTopicRequestRequestTypeDef,
     SetReceiptRulePositionRequestRequestTypeDef,
     TestRenderTemplateRequestRequestTypeDef,
+    TestRenderTemplateResponseTypeDef,
     UpdateAccountSendingEnabledRequestRequestTypeDef,
     UpdateConfigurationSetReputationMetricsEnabledRequestRequestTypeDef,
     UpdateConfigurationSetSendingEnabledRequestRequestTypeDef,
     UpdateCustomVerificationEmailTemplateRequestRequestTypeDef,
     VerifyDomainDkimRequestRequestTypeDef,
+    VerifyDomainDkimResponseTypeDef,
     VerifyDomainIdentityRequestRequestTypeDef,
+    VerifyDomainIdentityResponseTypeDef,
     VerifyEmailAddressRequestRequestTypeDef,
     VerifyEmailIdentityRequestRequestTypeDef,
     BodyTypeDef,
+    SendBulkTemplatedEmailResponseTypeDef,
     BulkEmailDestinationTypeDef,
     SendTemplatedEmailRequestRequestTypeDef,
     CloudWatchDestinationTypeDef,
     CreateConfigurationSetRequestRequestTypeDef,
+    ListConfigurationSetsResponseTypeDef,
     CreateConfigurationSetTrackingOptionsRequestRequestTypeDef,
     UpdateConfigurationSetTrackingOptionsRequestRequestTypeDef,
     CreateTemplateRequestRequestTypeDef,
-    UpdateTemplateRequestRequestTypeDef,
-    PutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAccountSendingEnabledResponseTypeDef,
-    GetCustomVerificationEmailTemplateResponseTypeDef,
-    GetIdentityPoliciesResponseTypeDef,
-    GetSendQuotaResponseTypeDef,
     GetTemplateResponseTypeDef,
-    ListConfigurationSetsResponseTypeDef,
+    UpdateTemplateRequestRequestTypeDef,
     ListCustomVerificationEmailTemplatesResponseTypeDef,
-    ListIdentitiesResponseTypeDef,
-    ListIdentityPoliciesResponseTypeDef,
+    PutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
     ListReceiptRuleSetsResponseTypeDef,
-    ListVerifiedEmailAddressesResponseTypeDef,
-    SendBounceResponseTypeDef,
-    SendBulkTemplatedEmailResponseTypeDef,
-    SendCustomVerificationEmailResponseTypeDef,
-    SendEmailResponseTypeDef,
-    SendRawEmailResponseTypeDef,
-    SendTemplatedEmailResponseTypeDef,
-    TestRenderTemplateResponseTypeDef,
-    VerifyDomainDkimResponseTypeDef,
-    VerifyDomainIdentityResponseTypeDef,
     MessageDsnTypeDef,
     RecipientDsnFieldsTypeDef,
     GetIdentityDkimAttributesResponseTypeDef,
     GetIdentityMailFromDomainAttributesResponseTypeDef,
     GetIdentityNotificationAttributesResponseTypeDef,
     GetIdentityVerificationAttributesRequestIdentityExistsWaitTypeDef,
     GetIdentityVerificationAttributesResponseTypeDef,
     GetSendStatisticsResponseTypeDef,
-    ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef,
-    ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef,
-    ListIdentitiesRequestListIdentitiesPaginateTypeDef,
-    ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef,
-    ListTemplatesRequestListTemplatesPaginateTypeDef,
     ListTemplatesResponseTypeDef,
     SendRawEmailRequestRequestTypeDef,
     ReceiptActionTypeDef,
     ReceiptFilterTypeDef,
     MessageTypeDef,
     SendBulkTemplatedEmailRequestRequestTypeDef,
     EventDestinationTypeDef,
@@ -501,43 +501,43 @@
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

### Comparing `types-aiobotocore-ses-2.5.0.post1/setup.py` & `types-aiobotocore-ses-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-ses.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-ses",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_ses"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SES 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.SES 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/",
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

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/__init__.py` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/__init__.pyi` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/__main__.py` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SES 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SES 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES\nOther"
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

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/client.py` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/client.pyi` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/literals.py` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -160,14 +160,15 @@
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
@@ -246,14 +247,15 @@
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
@@ -264,14 +266,15 @@
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
@@ -307,14 +310,15 @@
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
@@ -333,16 +337,19 @@
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
@@ -426,15 +433,17 @@
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

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/literals.pyi` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -158,14 +158,15 @@
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
@@ -244,14 +245,15 @@
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
@@ -262,14 +264,15 @@
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
@@ -305,14 +308,15 @@
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
@@ -331,16 +335,19 @@
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
@@ -424,15 +431,17 @@
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

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/paginator.py` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,36 +24,29 @@
         list_configuration_sets_paginator: ListConfigurationSetsPaginator = client.get_paginator("list_configuration_sets")
         list_custom_verification_email_templates_paginator: ListCustomVerificationEmailTemplatesPaginator = client.get_paginator("list_custom_verification_email_templates")
         list_identities_paginator: ListIdentitiesPaginator = client.get_paginator("list_identities")
         list_receipt_rule_sets_paginator: ListReceiptRuleSetsPaginator = client.get_paginator("list_receipt_rule_sets")
         list_templates_paginator: ListTemplatesPaginator = client.get_paginator("list_templates")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import IdentityTypeType
 from .type_defs import (
     ListConfigurationSetsResponseTypeDef,
     ListCustomVerificationEmailTemplatesResponseTypeDef,
     ListIdentitiesResponseTypeDef,
     ListReceiptRuleSetsResponseTypeDef,
     ListTemplatesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListConfigurationSetsPaginator",
     "ListCustomVerificationEmailTemplatesPaginator",
     "ListIdentitiesPaginator",
     "ListReceiptRuleSetsPaginator",
     "ListTemplatesPaginator",
 )
@@ -72,30 +65,30 @@
 class ListConfigurationSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListConfigurationSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listconfigurationsetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConfigurationSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListConfigurationSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listconfigurationsetspaginator)
         """
 
 
 class ListCustomVerificationEmailTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListCustomVerificationEmailTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listcustomverificationemailtemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomVerificationEmailTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListCustomVerificationEmailTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listcustomverificationemailtemplatespaginator)
         """
 
 
@@ -105,43 +98,43 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listidentitiespaginator)
     """
 
     def paginate(
         self,
         *,
         IdentityType: IdentityTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIdentitiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListIdentities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listidentitiespaginator)
         """
 
 
 class ListReceiptRuleSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListReceiptRuleSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listreceiptrulesetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReceiptRuleSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListReceiptRuleSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listreceiptrulesetspaginator)
         """
 
 
 class ListTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listtemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listtemplatespaginator)
         """
```

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/paginator.pyi` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,35 +24,29 @@
         list_configuration_sets_paginator: ListConfigurationSetsPaginator = client.get_paginator("list_configuration_sets")
         list_custom_verification_email_templates_paginator: ListCustomVerificationEmailTemplatesPaginator = client.get_paginator("list_custom_verification_email_templates")
         list_identities_paginator: ListIdentitiesPaginator = client.get_paginator("list_identities")
         list_receipt_rule_sets_paginator: ListReceiptRuleSetsPaginator = client.get_paginator("list_receipt_rule_sets")
         list_templates_paginator: ListTemplatesPaginator = client.get_paginator("list_templates")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import IdentityTypeType
 from .type_defs import (
     ListConfigurationSetsResponseTypeDef,
     ListCustomVerificationEmailTemplatesResponseTypeDef,
     ListIdentitiesResponseTypeDef,
     ListReceiptRuleSetsResponseTypeDef,
     ListTemplatesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListConfigurationSetsPaginator",
     "ListCustomVerificationEmailTemplatesPaginator",
     "ListIdentitiesPaginator",
     "ListReceiptRuleSetsPaginator",
     "ListTemplatesPaginator",
 )
@@ -68,29 +62,29 @@
 class ListConfigurationSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListConfigurationSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listconfigurationsetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConfigurationSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListConfigurationSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listconfigurationsetspaginator)
         """
 
 class ListCustomVerificationEmailTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListCustomVerificationEmailTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listcustomverificationemailtemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomVerificationEmailTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListCustomVerificationEmailTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listcustomverificationemailtemplatespaginator)
         """
 
 class ListIdentitiesPaginator(AioPaginator):
@@ -99,41 +93,41 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listidentitiespaginator)
     """
 
     def paginate(
         self,
         *,
         IdentityType: IdentityTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIdentitiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListIdentities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listidentitiespaginator)
         """
 
 class ListReceiptRuleSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListReceiptRuleSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listreceiptrulesetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReceiptRuleSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListReceiptRuleSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listreceiptrulesetspaginator)
         """
 
 class ListTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listtemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES.Paginator.ListTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/paginators/#listtemplatespaginator)
         """
```

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/type_defs.py` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -69,113 +69,113 @@
     "DeleteReceiptFilterRequestRequestTypeDef",
     "DeleteReceiptRuleRequestRequestTypeDef",
     "DeleteReceiptRuleSetRequestRequestTypeDef",
     "DeleteTemplateRequestRequestTypeDef",
     "DeleteVerifiedEmailAddressRequestRequestTypeDef",
     "DeliveryOptionsTypeDef",
     "ReceiptRuleSetMetadataTypeDef",
-    "ResponseMetadataTypeDef",
     "DescribeConfigurationSetRequestRequestTypeDef",
     "ReputationOptionsTypeDef",
     "DescribeReceiptRuleRequestRequestTypeDef",
     "DescribeReceiptRuleSetRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "KinesisFirehoseDestinationTypeDef",
     "SNSDestinationTypeDef",
     "ExtensionFieldTypeDef",
+    "GetAccountSendingEnabledResponseTypeDef",
     "GetCustomVerificationEmailTemplateRequestRequestTypeDef",
+    "GetCustomVerificationEmailTemplateResponseTypeDef",
     "GetIdentityDkimAttributesRequestRequestTypeDef",
     "IdentityDkimAttributesTypeDef",
     "GetIdentityMailFromDomainAttributesRequestRequestTypeDef",
     "IdentityMailFromDomainAttributesTypeDef",
     "GetIdentityNotificationAttributesRequestRequestTypeDef",
     "IdentityNotificationAttributesTypeDef",
     "GetIdentityPoliciesRequestRequestTypeDef",
+    "GetIdentityPoliciesResponseTypeDef",
     "WaiterConfigTypeDef",
     "GetIdentityVerificationAttributesRequestRequestTypeDef",
     "IdentityVerificationAttributesTypeDef",
+    "GetSendQuotaResponseTypeDef",
     "SendDataPointTypeDef",
     "GetTemplateRequestRequestTypeDef",
     "LambdaActionTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
     "ListConfigurationSetsRequestRequestTypeDef",
+    "ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef",
     "ListCustomVerificationEmailTemplatesRequestRequestTypeDef",
+    "ListIdentitiesRequestListIdentitiesPaginateTypeDef",
     "ListIdentitiesRequestRequestTypeDef",
+    "ListIdentitiesResponseTypeDef",
     "ListIdentityPoliciesRequestRequestTypeDef",
+    "ListIdentityPoliciesResponseTypeDef",
+    "ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef",
     "ListReceiptRuleSetsRequestRequestTypeDef",
+    "ListTemplatesRequestListTemplatesPaginateTypeDef",
     "ListTemplatesRequestRequestTypeDef",
     "TemplateMetadataTypeDef",
+    "ListVerifiedEmailAddressesResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PutIdentityPolicyRequestRequestTypeDef",
     "RawMessageTypeDef",
     "S3ActionTypeDef",
     "SNSActionTypeDef",
     "StopActionTypeDef",
     "WorkmailActionTypeDef",
     "ReceiptIpFilterTypeDef",
     "ReorderReceiptRuleSetRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "SendBounceResponseTypeDef",
     "SendCustomVerificationEmailRequestRequestTypeDef",
+    "SendCustomVerificationEmailResponseTypeDef",
+    "SendEmailResponseTypeDef",
+    "SendRawEmailResponseTypeDef",
+    "SendTemplatedEmailResponseTypeDef",
     "SetActiveReceiptRuleSetRequestRequestTypeDef",
     "SetIdentityDkimEnabledRequestRequestTypeDef",
     "SetIdentityFeedbackForwardingEnabledRequestRequestTypeDef",
     "SetIdentityHeadersInNotificationsEnabledRequestRequestTypeDef",
     "SetIdentityMailFromDomainRequestRequestTypeDef",
     "SetIdentityNotificationTopicRequestRequestTypeDef",
     "SetReceiptRulePositionRequestRequestTypeDef",
     "TestRenderTemplateRequestRequestTypeDef",
+    "TestRenderTemplateResponseTypeDef",
     "UpdateAccountSendingEnabledRequestRequestTypeDef",
     "UpdateConfigurationSetReputationMetricsEnabledRequestRequestTypeDef",
     "UpdateConfigurationSetSendingEnabledRequestRequestTypeDef",
     "UpdateCustomVerificationEmailTemplateRequestRequestTypeDef",
     "VerifyDomainDkimRequestRequestTypeDef",
+    "VerifyDomainDkimResponseTypeDef",
     "VerifyDomainIdentityRequestRequestTypeDef",
+    "VerifyDomainIdentityResponseTypeDef",
     "VerifyEmailAddressRequestRequestTypeDef",
     "VerifyEmailIdentityRequestRequestTypeDef",
     "BodyTypeDef",
+    "SendBulkTemplatedEmailResponseTypeDef",
     "BulkEmailDestinationTypeDef",
     "SendTemplatedEmailRequestRequestTypeDef",
     "CloudWatchDestinationTypeDef",
     "CreateConfigurationSetRequestRequestTypeDef",
+    "ListConfigurationSetsResponseTypeDef",
     "CreateConfigurationSetTrackingOptionsRequestRequestTypeDef",
     "UpdateConfigurationSetTrackingOptionsRequestRequestTypeDef",
     "CreateTemplateRequestRequestTypeDef",
-    "UpdateTemplateRequestRequestTypeDef",
-    "PutConfigurationSetDeliveryOptionsRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAccountSendingEnabledResponseTypeDef",
-    "GetCustomVerificationEmailTemplateResponseTypeDef",
-    "GetIdentityPoliciesResponseTypeDef",
-    "GetSendQuotaResponseTypeDef",
     "GetTemplateResponseTypeDef",
-    "ListConfigurationSetsResponseTypeDef",
+    "UpdateTemplateRequestRequestTypeDef",
     "ListCustomVerificationEmailTemplatesResponseTypeDef",
-    "ListIdentitiesResponseTypeDef",
-    "ListIdentityPoliciesResponseTypeDef",
+    "PutConfigurationSetDeliveryOptionsRequestRequestTypeDef",
     "ListReceiptRuleSetsResponseTypeDef",
-    "ListVerifiedEmailAddressesResponseTypeDef",
-    "SendBounceResponseTypeDef",
-    "SendBulkTemplatedEmailResponseTypeDef",
-    "SendCustomVerificationEmailResponseTypeDef",
-    "SendEmailResponseTypeDef",
-    "SendRawEmailResponseTypeDef",
-    "SendTemplatedEmailResponseTypeDef",
-    "TestRenderTemplateResponseTypeDef",
-    "VerifyDomainDkimResponseTypeDef",
-    "VerifyDomainIdentityResponseTypeDef",
     "MessageDsnTypeDef",
     "RecipientDsnFieldsTypeDef",
     "GetIdentityDkimAttributesResponseTypeDef",
     "GetIdentityMailFromDomainAttributesResponseTypeDef",
     "GetIdentityNotificationAttributesResponseTypeDef",
     "GetIdentityVerificationAttributesRequestIdentityExistsWaitTypeDef",
     "GetIdentityVerificationAttributesResponseTypeDef",
     "GetSendStatisticsResponseTypeDef",
-    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
-    "ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef",
-    "ListIdentitiesRequestListIdentitiesPaginateTypeDef",
-    "ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef",
-    "ListTemplatesRequestListTemplatesPaginateTypeDef",
     "ListTemplatesResponseTypeDef",
     "SendRawEmailRequestRequestTypeDef",
     "ReceiptActionTypeDef",
     "ReceiptFilterTypeDef",
     "MessageTypeDef",
     "SendBulkTemplatedEmailRequestRequestTypeDef",
     "EventDestinationTypeDef",
@@ -449,25 +449,14 @@
     {
         "Name": str,
         "CreatedTimestamp": datetime,
     },
     total=False,
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
 _RequiredDescribeConfigurationSetRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeConfigurationSetRequestRequestTypeDef",
     {
         "ConfigurationSetName": str,
     },
 )
 _OptionalDescribeConfigurationSetRequestRequestTypeDef = TypedDict(
@@ -507,14 +496,21 @@
 DescribeReceiptRuleSetRequestRequestTypeDef = TypedDict(
     "DescribeReceiptRuleSetRequestRequestTypeDef",
     {
         "RuleSetName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 KinesisFirehoseDestinationTypeDef = TypedDict(
     "KinesisFirehoseDestinationTypeDef",
     {
         "IAMRoleARN": str,
         "DeliveryStreamARN": str,
     },
 )
@@ -530,21 +526,42 @@
     "ExtensionFieldTypeDef",
     {
         "Name": str,
         "Value": str,
     },
 )
 
+GetAccountSendingEnabledResponseTypeDef = TypedDict(
+    "GetAccountSendingEnabledResponseTypeDef",
+    {
+        "Enabled": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetCustomVerificationEmailTemplateRequestRequestTypeDef = TypedDict(
     "GetCustomVerificationEmailTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
     },
 )
 
+GetCustomVerificationEmailTemplateResponseTypeDef = TypedDict(
+    "GetCustomVerificationEmailTemplateResponseTypeDef",
+    {
+        "TemplateName": str,
+        "FromEmailAddress": str,
+        "TemplateSubject": str,
+        "TemplateContent": str,
+        "SuccessRedirectionURL": str,
+        "FailureRedirectionURL": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetIdentityDkimAttributesRequestRequestTypeDef = TypedDict(
     "GetIdentityDkimAttributesRequestRequestTypeDef",
     {
         "Identities": Sequence[str],
     },
 )
 
@@ -623,14 +640,22 @@
     "GetIdentityPoliciesRequestRequestTypeDef",
     {
         "Identity": str,
         "PolicyNames": Sequence[str],
     },
 )
 
+GetIdentityPoliciesResponseTypeDef = TypedDict(
+    "GetIdentityPoliciesResponseTypeDef",
+    {
+        "Policies": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -660,14 +685,24 @@
 
 class IdentityVerificationAttributesTypeDef(
     _RequiredIdentityVerificationAttributesTypeDef, _OptionalIdentityVerificationAttributesTypeDef
 ):
     pass
 
 
+GetSendQuotaResponseTypeDef = TypedDict(
+    "GetSendQuotaResponseTypeDef",
+    {
+        "Max24HourSend": float,
+        "MaxSendRate": float,
+        "SentLast24Hours": float,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SendDataPointTypeDef = TypedDict(
     "SendDataPointTypeDef",
     {
         "Timestamp": datetime,
         "DeliveryAttempts": int,
         "Bounces": int,
         "Complaints": int,
@@ -699,67 +734,115 @@
 )
 
 
 class LambdaActionTypeDef(_RequiredLambdaActionTypeDef, _OptionalLambdaActionTypeDef):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef = TypedDict(
+    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListConfigurationSetsRequestRequestTypeDef = TypedDict(
     "ListConfigurationSetsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef = TypedDict(
+    "ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCustomVerificationEmailTemplatesRequestRequestTypeDef = TypedDict(
     "ListCustomVerificationEmailTemplatesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListIdentitiesRequestListIdentitiesPaginateTypeDef = TypedDict(
+    "ListIdentitiesRequestListIdentitiesPaginateTypeDef",
+    {
+        "IdentityType": IdentityTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListIdentitiesRequestRequestTypeDef = TypedDict(
     "ListIdentitiesRequestRequestTypeDef",
     {
         "IdentityType": IdentityTypeType,
         "NextToken": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+ListIdentitiesResponseTypeDef = TypedDict(
+    "ListIdentitiesResponseTypeDef",
+    {
+        "Identities": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListIdentityPoliciesRequestRequestTypeDef = TypedDict(
     "ListIdentityPoliciesRequestRequestTypeDef",
     {
         "Identity": str,
     },
 )
 
+ListIdentityPoliciesResponseTypeDef = TypedDict(
+    "ListIdentityPoliciesResponseTypeDef",
+    {
+        "PolicyNames": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef = TypedDict(
+    "ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListReceiptRuleSetsRequestRequestTypeDef = TypedDict(
     "ListReceiptRuleSetsRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+ListTemplatesRequestListTemplatesPaginateTypeDef = TypedDict(
+    "ListTemplatesRequestListTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTemplatesRequestRequestTypeDef = TypedDict(
     "ListTemplatesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxItems": int,
     },
     total=False,
@@ -770,14 +853,32 @@
     {
         "Name": str,
         "CreatedTimestamp": datetime,
     },
     total=False,
 )
 
+ListVerifiedEmailAddressesResponseTypeDef = TypedDict(
+    "ListVerifiedEmailAddressesResponseTypeDef",
+    {
+        "VerifiedEmailAddresses": List[str],
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
 PutIdentityPolicyRequestRequestTypeDef = TypedDict(
     "PutIdentityPolicyRequestRequestTypeDef",
     {
         "Identity": str,
         "PolicyName": str,
         "Policy": str,
     },
@@ -880,14 +981,33 @@
     "ReorderReceiptRuleSetRequestRequestTypeDef",
     {
         "RuleSetName": str,
         "RuleNames": Sequence[str],
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
+SendBounceResponseTypeDef = TypedDict(
+    "SendBounceResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSendCustomVerificationEmailRequestRequestTypeDef = TypedDict(
     "_RequiredSendCustomVerificationEmailRequestRequestTypeDef",
     {
         "EmailAddress": str,
         "TemplateName": str,
     },
 )
@@ -903,14 +1023,46 @@
 class SendCustomVerificationEmailRequestRequestTypeDef(
     _RequiredSendCustomVerificationEmailRequestRequestTypeDef,
     _OptionalSendCustomVerificationEmailRequestRequestTypeDef,
 ):
     pass
 
 
+SendCustomVerificationEmailResponseTypeDef = TypedDict(
+    "SendCustomVerificationEmailResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SendEmailResponseTypeDef = TypedDict(
+    "SendEmailResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SendRawEmailResponseTypeDef = TypedDict(
+    "SendRawEmailResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SendTemplatedEmailResponseTypeDef = TypedDict(
+    "SendTemplatedEmailResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SetActiveReceiptRuleSetRequestRequestTypeDef = TypedDict(
     "SetActiveReceiptRuleSetRequestRequestTypeDef",
     {
         "RuleSetName": str,
     },
     total=False,
 )
@@ -1013,14 +1165,22 @@
     "TestRenderTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
         "TemplateData": str,
     },
 )
 
+TestRenderTemplateResponseTypeDef = TypedDict(
+    "TestRenderTemplateResponseTypeDef",
+    {
+        "RenderedTemplate": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateAccountSendingEnabledRequestRequestTypeDef = TypedDict(
     "UpdateAccountSendingEnabledRequestRequestTypeDef",
     {
         "Enabled": bool,
     },
     total=False,
 )
@@ -1070,21 +1230,37 @@
 VerifyDomainDkimRequestRequestTypeDef = TypedDict(
     "VerifyDomainDkimRequestRequestTypeDef",
     {
         "Domain": str,
     },
 )
 
+VerifyDomainDkimResponseTypeDef = TypedDict(
+    "VerifyDomainDkimResponseTypeDef",
+    {
+        "DkimTokens": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 VerifyDomainIdentityRequestRequestTypeDef = TypedDict(
     "VerifyDomainIdentityRequestRequestTypeDef",
     {
         "Domain": str,
     },
 )
 
+VerifyDomainIdentityResponseTypeDef = TypedDict(
+    "VerifyDomainIdentityResponseTypeDef",
+    {
+        "VerificationToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 VerifyEmailAddressRequestRequestTypeDef = TypedDict(
     "VerifyEmailAddressRequestRequestTypeDef",
     {
         "EmailAddress": str,
     },
 )
 
@@ -1100,14 +1276,22 @@
     {
         "Text": ContentTypeDef,
         "Html": ContentTypeDef,
     },
     total=False,
 )
 
+SendBulkTemplatedEmailResponseTypeDef = TypedDict(
+    "SendBulkTemplatedEmailResponseTypeDef",
+    {
+        "Status": List[BulkEmailDestinationStatusTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredBulkEmailDestinationTypeDef = TypedDict(
     "_RequiredBulkEmailDestinationTypeDef",
     {
         "Destination": DestinationTypeDef,
     },
 )
 _OptionalBulkEmailDestinationTypeDef = TypedDict(
@@ -1167,14 +1351,23 @@
 CreateConfigurationSetRequestRequestTypeDef = TypedDict(
     "CreateConfigurationSetRequestRequestTypeDef",
     {
         "ConfigurationSet": ConfigurationSetTypeDef,
     },
 )
 
+ListConfigurationSetsResponseTypeDef = TypedDict(
+    "ListConfigurationSetsResponseTypeDef",
+    {
+        "ConfigurationSets": List[ConfigurationSetTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateConfigurationSetTrackingOptionsRequestRequestTypeDef = TypedDict(
     "CreateConfigurationSetTrackingOptionsRequestRequestTypeDef",
     {
         "ConfigurationSetName": str,
         "TrackingOptions": TrackingOptionsTypeDef,
     },
 )
@@ -1190,21 +1383,38 @@
 CreateTemplateRequestRequestTypeDef = TypedDict(
     "CreateTemplateRequestRequestTypeDef",
     {
         "Template": TemplateTypeDef,
     },
 )
 
+GetTemplateResponseTypeDef = TypedDict(
+    "GetTemplateResponseTypeDef",
+    {
+        "Template": TemplateTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateTemplateRequestRequestTypeDef = TypedDict(
     "UpdateTemplateRequestRequestTypeDef",
     {
         "Template": TemplateTypeDef,
     },
 )
 
+ListCustomVerificationEmailTemplatesResponseTypeDef = TypedDict(
+    "ListCustomVerificationEmailTemplatesResponseTypeDef",
+    {
+        "CustomVerificationEmailTemplates": List[CustomVerificationEmailTemplateTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutConfigurationSetDeliveryOptionsRequestRequestTypeDef = TypedDict(
     "_RequiredPutConfigurationSetDeliveryOptionsRequestRequestTypeDef",
     {
         "ConfigurationSetName": str,
     },
 )
 _OptionalPutConfigurationSetDeliveryOptionsRequestRequestTypeDef = TypedDict(
@@ -1219,189 +1429,20 @@
 class PutConfigurationSetDeliveryOptionsRequestRequestTypeDef(
     _RequiredPutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
     _OptionalPutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
 ):
     pass
 
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccountSendingEnabledResponseTypeDef = TypedDict(
-    "GetAccountSendingEnabledResponseTypeDef",
-    {
-        "Enabled": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCustomVerificationEmailTemplateResponseTypeDef = TypedDict(
-    "GetCustomVerificationEmailTemplateResponseTypeDef",
-    {
-        "TemplateName": str,
-        "FromEmailAddress": str,
-        "TemplateSubject": str,
-        "TemplateContent": str,
-        "SuccessRedirectionURL": str,
-        "FailureRedirectionURL": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetIdentityPoliciesResponseTypeDef = TypedDict(
-    "GetIdentityPoliciesResponseTypeDef",
-    {
-        "Policies": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSendQuotaResponseTypeDef = TypedDict(
-    "GetSendQuotaResponseTypeDef",
-    {
-        "Max24HourSend": float,
-        "MaxSendRate": float,
-        "SentLast24Hours": float,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTemplateResponseTypeDef = TypedDict(
-    "GetTemplateResponseTypeDef",
-    {
-        "Template": TemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConfigurationSetsResponseTypeDef = TypedDict(
-    "ListConfigurationSetsResponseTypeDef",
-    {
-        "ConfigurationSets": List[ConfigurationSetTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListCustomVerificationEmailTemplatesResponseTypeDef = TypedDict(
-    "ListCustomVerificationEmailTemplatesResponseTypeDef",
-    {
-        "CustomVerificationEmailTemplates": List[CustomVerificationEmailTemplateTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListIdentitiesResponseTypeDef = TypedDict(
-    "ListIdentitiesResponseTypeDef",
-    {
-        "Identities": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListIdentityPoliciesResponseTypeDef = TypedDict(
-    "ListIdentityPoliciesResponseTypeDef",
-    {
-        "PolicyNames": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListReceiptRuleSetsResponseTypeDef = TypedDict(
     "ListReceiptRuleSetsResponseTypeDef",
     {
         "RuleSets": List[ReceiptRuleSetMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListVerifiedEmailAddressesResponseTypeDef = TypedDict(
-    "ListVerifiedEmailAddressesResponseTypeDef",
-    {
-        "VerifiedEmailAddresses": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendBounceResponseTypeDef = TypedDict(
-    "SendBounceResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendBulkTemplatedEmailResponseTypeDef = TypedDict(
-    "SendBulkTemplatedEmailResponseTypeDef",
-    {
-        "Status": List[BulkEmailDestinationStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendCustomVerificationEmailResponseTypeDef = TypedDict(
-    "SendCustomVerificationEmailResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendEmailResponseTypeDef = TypedDict(
-    "SendEmailResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendRawEmailResponseTypeDef = TypedDict(
-    "SendRawEmailResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendTemplatedEmailResponseTypeDef = TypedDict(
-    "SendTemplatedEmailResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestRenderTemplateResponseTypeDef = TypedDict(
-    "TestRenderTemplateResponseTypeDef",
-    {
-        "RenderedTemplate": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-VerifyDomainDkimResponseTypeDef = TypedDict(
-    "VerifyDomainDkimResponseTypeDef",
-    {
-        "DkimTokens": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-VerifyDomainIdentityResponseTypeDef = TypedDict(
-    "VerifyDomainIdentityResponseTypeDef",
-    {
-        "VerificationToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMessageDsnTypeDef = TypedDict(
     "_RequiredMessageDsnTypeDef",
     {
         "ReportingMta": str,
@@ -1447,31 +1488,31 @@
     pass
 
 
 GetIdentityDkimAttributesResponseTypeDef = TypedDict(
     "GetIdentityDkimAttributesResponseTypeDef",
     {
         "DkimAttributes": Dict[str, IdentityDkimAttributesTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIdentityMailFromDomainAttributesResponseTypeDef = TypedDict(
     "GetIdentityMailFromDomainAttributesResponseTypeDef",
     {
         "MailFromDomainAttributes": Dict[str, IdentityMailFromDomainAttributesTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIdentityNotificationAttributesResponseTypeDef = TypedDict(
     "GetIdentityNotificationAttributesResponseTypeDef",
     {
         "NotificationAttributes": Dict[str, IdentityNotificationAttributesTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetIdentityVerificationAttributesRequestIdentityExistsWaitTypeDef = TypedDict(
     "_RequiredGetIdentityVerificationAttributesRequestIdentityExistsWaitTypeDef",
     {
         "Identities": Sequence[str],
@@ -1493,73 +1534,32 @@
     pass
 
 
 GetIdentityVerificationAttributesResponseTypeDef = TypedDict(
     "GetIdentityVerificationAttributesResponseTypeDef",
     {
         "VerificationAttributes": Dict[str, IdentityVerificationAttributesTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSendStatisticsResponseTypeDef = TypedDict(
     "GetSendStatisticsResponseTypeDef",
     {
         "SendDataPoints": List[SendDataPointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef = TypedDict(
-    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef = TypedDict(
-    "ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListIdentitiesRequestListIdentitiesPaginateTypeDef = TypedDict(
-    "ListIdentitiesRequestListIdentitiesPaginateTypeDef",
-    {
-        "IdentityType": IdentityTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef = TypedDict(
-    "ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTemplatesRequestListTemplatesPaginateTypeDef = TypedDict(
-    "ListTemplatesRequestListTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 ListTemplatesResponseTypeDef = TypedDict(
     "ListTemplatesResponseTypeDef",
     {
         "TemplatesMetadata": List[TemplateMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSendRawEmailRequestRequestTypeDef = TypedDict(
     "_RequiredSendRawEmailRequestRequestTypeDef",
     {
         "RawMessage": RawMessageTypeDef,
@@ -1723,15 +1723,15 @@
     },
 )
 
 ListReceiptFiltersResponseTypeDef = TypedDict(
     "ListReceiptFiltersResponseTypeDef",
     {
         "Filters": List[ReceiptFilterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSendEmailRequestRequestTypeDef = TypedDict(
     "_RequiredSendEmailRequestRequestTypeDef",
     {
         "Source": str,
@@ -1771,15 +1771,15 @@
     "DescribeConfigurationSetResponseTypeDef",
     {
         "ConfigurationSet": ConfigurationSetTypeDef,
         "EventDestinations": List[EventDestinationTypeDef],
         "TrackingOptions": TrackingOptionsTypeDef,
         "DeliveryOptions": DeliveryOptionsTypeDef,
         "ReputationOptions": ReputationOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateConfigurationSetEventDestinationRequestRequestTypeDef = TypedDict(
     "UpdateConfigurationSetEventDestinationRequestRequestTypeDef",
     {
         "ConfigurationSetName": str,
@@ -1835,32 +1835,32 @@
 
 
 DescribeActiveReceiptRuleSetResponseTypeDef = TypedDict(
     "DescribeActiveReceiptRuleSetResponseTypeDef",
     {
         "Metadata": ReceiptRuleSetMetadataTypeDef,
         "Rules": List[ReceiptRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReceiptRuleResponseTypeDef = TypedDict(
     "DescribeReceiptRuleResponseTypeDef",
     {
         "Rule": ReceiptRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReceiptRuleSetResponseTypeDef = TypedDict(
     "DescribeReceiptRuleSetResponseTypeDef",
     {
         "Metadata": ReceiptRuleSetMetadataTypeDef,
         "Rules": List[ReceiptRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateReceiptRuleRequestRequestTypeDef = TypedDict(
     "UpdateReceiptRuleRequestRequestTypeDef",
     {
         "RuleSetName": str,
```

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/type_defs.pyi` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -68,113 +68,113 @@
     "DeleteReceiptFilterRequestRequestTypeDef",
     "DeleteReceiptRuleRequestRequestTypeDef",
     "DeleteReceiptRuleSetRequestRequestTypeDef",
     "DeleteTemplateRequestRequestTypeDef",
     "DeleteVerifiedEmailAddressRequestRequestTypeDef",
     "DeliveryOptionsTypeDef",
     "ReceiptRuleSetMetadataTypeDef",
-    "ResponseMetadataTypeDef",
     "DescribeConfigurationSetRequestRequestTypeDef",
     "ReputationOptionsTypeDef",
     "DescribeReceiptRuleRequestRequestTypeDef",
     "DescribeReceiptRuleSetRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "KinesisFirehoseDestinationTypeDef",
     "SNSDestinationTypeDef",
     "ExtensionFieldTypeDef",
+    "GetAccountSendingEnabledResponseTypeDef",
     "GetCustomVerificationEmailTemplateRequestRequestTypeDef",
+    "GetCustomVerificationEmailTemplateResponseTypeDef",
     "GetIdentityDkimAttributesRequestRequestTypeDef",
     "IdentityDkimAttributesTypeDef",
     "GetIdentityMailFromDomainAttributesRequestRequestTypeDef",
     "IdentityMailFromDomainAttributesTypeDef",
     "GetIdentityNotificationAttributesRequestRequestTypeDef",
     "IdentityNotificationAttributesTypeDef",
     "GetIdentityPoliciesRequestRequestTypeDef",
+    "GetIdentityPoliciesResponseTypeDef",
     "WaiterConfigTypeDef",
     "GetIdentityVerificationAttributesRequestRequestTypeDef",
     "IdentityVerificationAttributesTypeDef",
+    "GetSendQuotaResponseTypeDef",
     "SendDataPointTypeDef",
     "GetTemplateRequestRequestTypeDef",
     "LambdaActionTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
     "ListConfigurationSetsRequestRequestTypeDef",
+    "ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef",
     "ListCustomVerificationEmailTemplatesRequestRequestTypeDef",
+    "ListIdentitiesRequestListIdentitiesPaginateTypeDef",
     "ListIdentitiesRequestRequestTypeDef",
+    "ListIdentitiesResponseTypeDef",
     "ListIdentityPoliciesRequestRequestTypeDef",
+    "ListIdentityPoliciesResponseTypeDef",
+    "ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef",
     "ListReceiptRuleSetsRequestRequestTypeDef",
+    "ListTemplatesRequestListTemplatesPaginateTypeDef",
     "ListTemplatesRequestRequestTypeDef",
     "TemplateMetadataTypeDef",
+    "ListVerifiedEmailAddressesResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PutIdentityPolicyRequestRequestTypeDef",
     "RawMessageTypeDef",
     "S3ActionTypeDef",
     "SNSActionTypeDef",
     "StopActionTypeDef",
     "WorkmailActionTypeDef",
     "ReceiptIpFilterTypeDef",
     "ReorderReceiptRuleSetRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "SendBounceResponseTypeDef",
     "SendCustomVerificationEmailRequestRequestTypeDef",
+    "SendCustomVerificationEmailResponseTypeDef",
+    "SendEmailResponseTypeDef",
+    "SendRawEmailResponseTypeDef",
+    "SendTemplatedEmailResponseTypeDef",
     "SetActiveReceiptRuleSetRequestRequestTypeDef",
     "SetIdentityDkimEnabledRequestRequestTypeDef",
     "SetIdentityFeedbackForwardingEnabledRequestRequestTypeDef",
     "SetIdentityHeadersInNotificationsEnabledRequestRequestTypeDef",
     "SetIdentityMailFromDomainRequestRequestTypeDef",
     "SetIdentityNotificationTopicRequestRequestTypeDef",
     "SetReceiptRulePositionRequestRequestTypeDef",
     "TestRenderTemplateRequestRequestTypeDef",
+    "TestRenderTemplateResponseTypeDef",
     "UpdateAccountSendingEnabledRequestRequestTypeDef",
     "UpdateConfigurationSetReputationMetricsEnabledRequestRequestTypeDef",
     "UpdateConfigurationSetSendingEnabledRequestRequestTypeDef",
     "UpdateCustomVerificationEmailTemplateRequestRequestTypeDef",
     "VerifyDomainDkimRequestRequestTypeDef",
+    "VerifyDomainDkimResponseTypeDef",
     "VerifyDomainIdentityRequestRequestTypeDef",
+    "VerifyDomainIdentityResponseTypeDef",
     "VerifyEmailAddressRequestRequestTypeDef",
     "VerifyEmailIdentityRequestRequestTypeDef",
     "BodyTypeDef",
+    "SendBulkTemplatedEmailResponseTypeDef",
     "BulkEmailDestinationTypeDef",
     "SendTemplatedEmailRequestRequestTypeDef",
     "CloudWatchDestinationTypeDef",
     "CreateConfigurationSetRequestRequestTypeDef",
+    "ListConfigurationSetsResponseTypeDef",
     "CreateConfigurationSetTrackingOptionsRequestRequestTypeDef",
     "UpdateConfigurationSetTrackingOptionsRequestRequestTypeDef",
     "CreateTemplateRequestRequestTypeDef",
-    "UpdateTemplateRequestRequestTypeDef",
-    "PutConfigurationSetDeliveryOptionsRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAccountSendingEnabledResponseTypeDef",
-    "GetCustomVerificationEmailTemplateResponseTypeDef",
-    "GetIdentityPoliciesResponseTypeDef",
-    "GetSendQuotaResponseTypeDef",
     "GetTemplateResponseTypeDef",
-    "ListConfigurationSetsResponseTypeDef",
+    "UpdateTemplateRequestRequestTypeDef",
     "ListCustomVerificationEmailTemplatesResponseTypeDef",
-    "ListIdentitiesResponseTypeDef",
-    "ListIdentityPoliciesResponseTypeDef",
+    "PutConfigurationSetDeliveryOptionsRequestRequestTypeDef",
     "ListReceiptRuleSetsResponseTypeDef",
-    "ListVerifiedEmailAddressesResponseTypeDef",
-    "SendBounceResponseTypeDef",
-    "SendBulkTemplatedEmailResponseTypeDef",
-    "SendCustomVerificationEmailResponseTypeDef",
-    "SendEmailResponseTypeDef",
-    "SendRawEmailResponseTypeDef",
-    "SendTemplatedEmailResponseTypeDef",
-    "TestRenderTemplateResponseTypeDef",
-    "VerifyDomainDkimResponseTypeDef",
-    "VerifyDomainIdentityResponseTypeDef",
     "MessageDsnTypeDef",
     "RecipientDsnFieldsTypeDef",
     "GetIdentityDkimAttributesResponseTypeDef",
     "GetIdentityMailFromDomainAttributesResponseTypeDef",
     "GetIdentityNotificationAttributesResponseTypeDef",
     "GetIdentityVerificationAttributesRequestIdentityExistsWaitTypeDef",
     "GetIdentityVerificationAttributesResponseTypeDef",
     "GetSendStatisticsResponseTypeDef",
-    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
-    "ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef",
-    "ListIdentitiesRequestListIdentitiesPaginateTypeDef",
-    "ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef",
-    "ListTemplatesRequestListTemplatesPaginateTypeDef",
     "ListTemplatesResponseTypeDef",
     "SendRawEmailRequestRequestTypeDef",
     "ReceiptActionTypeDef",
     "ReceiptFilterTypeDef",
     "MessageTypeDef",
     "SendBulkTemplatedEmailRequestRequestTypeDef",
     "EventDestinationTypeDef",
@@ -442,25 +442,14 @@
     {
         "Name": str,
         "CreatedTimestamp": datetime,
     },
     total=False,
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
 _RequiredDescribeConfigurationSetRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeConfigurationSetRequestRequestTypeDef",
     {
         "ConfigurationSetName": str,
     },
 )
 _OptionalDescribeConfigurationSetRequestRequestTypeDef = TypedDict(
@@ -498,14 +487,21 @@
 DescribeReceiptRuleSetRequestRequestTypeDef = TypedDict(
     "DescribeReceiptRuleSetRequestRequestTypeDef",
     {
         "RuleSetName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 KinesisFirehoseDestinationTypeDef = TypedDict(
     "KinesisFirehoseDestinationTypeDef",
     {
         "IAMRoleARN": str,
         "DeliveryStreamARN": str,
     },
 )
@@ -521,21 +517,42 @@
     "ExtensionFieldTypeDef",
     {
         "Name": str,
         "Value": str,
     },
 )
 
+GetAccountSendingEnabledResponseTypeDef = TypedDict(
+    "GetAccountSendingEnabledResponseTypeDef",
+    {
+        "Enabled": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetCustomVerificationEmailTemplateRequestRequestTypeDef = TypedDict(
     "GetCustomVerificationEmailTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
     },
 )
 
+GetCustomVerificationEmailTemplateResponseTypeDef = TypedDict(
+    "GetCustomVerificationEmailTemplateResponseTypeDef",
+    {
+        "TemplateName": str,
+        "FromEmailAddress": str,
+        "TemplateSubject": str,
+        "TemplateContent": str,
+        "SuccessRedirectionURL": str,
+        "FailureRedirectionURL": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetIdentityDkimAttributesRequestRequestTypeDef = TypedDict(
     "GetIdentityDkimAttributesRequestRequestTypeDef",
     {
         "Identities": Sequence[str],
     },
 )
 
@@ -610,14 +627,22 @@
     "GetIdentityPoliciesRequestRequestTypeDef",
     {
         "Identity": str,
         "PolicyNames": Sequence[str],
     },
 )
 
+GetIdentityPoliciesResponseTypeDef = TypedDict(
+    "GetIdentityPoliciesResponseTypeDef",
+    {
+        "Policies": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -645,14 +670,24 @@
 )
 
 class IdentityVerificationAttributesTypeDef(
     _RequiredIdentityVerificationAttributesTypeDef, _OptionalIdentityVerificationAttributesTypeDef
 ):
     pass
 
+GetSendQuotaResponseTypeDef = TypedDict(
+    "GetSendQuotaResponseTypeDef",
+    {
+        "Max24HourSend": float,
+        "MaxSendRate": float,
+        "SentLast24Hours": float,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SendDataPointTypeDef = TypedDict(
     "SendDataPointTypeDef",
     {
         "Timestamp": datetime,
         "DeliveryAttempts": int,
         "Bounces": int,
         "Complaints": int,
@@ -682,67 +717,115 @@
     },
     total=False,
 )
 
 class LambdaActionTypeDef(_RequiredLambdaActionTypeDef, _OptionalLambdaActionTypeDef):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef = TypedDict(
+    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListConfigurationSetsRequestRequestTypeDef = TypedDict(
     "ListConfigurationSetsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef = TypedDict(
+    "ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCustomVerificationEmailTemplatesRequestRequestTypeDef = TypedDict(
     "ListCustomVerificationEmailTemplatesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListIdentitiesRequestListIdentitiesPaginateTypeDef = TypedDict(
+    "ListIdentitiesRequestListIdentitiesPaginateTypeDef",
+    {
+        "IdentityType": IdentityTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListIdentitiesRequestRequestTypeDef = TypedDict(
     "ListIdentitiesRequestRequestTypeDef",
     {
         "IdentityType": IdentityTypeType,
         "NextToken": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+ListIdentitiesResponseTypeDef = TypedDict(
+    "ListIdentitiesResponseTypeDef",
+    {
+        "Identities": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListIdentityPoliciesRequestRequestTypeDef = TypedDict(
     "ListIdentityPoliciesRequestRequestTypeDef",
     {
         "Identity": str,
     },
 )
 
+ListIdentityPoliciesResponseTypeDef = TypedDict(
+    "ListIdentityPoliciesResponseTypeDef",
+    {
+        "PolicyNames": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef = TypedDict(
+    "ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListReceiptRuleSetsRequestRequestTypeDef = TypedDict(
     "ListReceiptRuleSetsRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+ListTemplatesRequestListTemplatesPaginateTypeDef = TypedDict(
+    "ListTemplatesRequestListTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTemplatesRequestRequestTypeDef = TypedDict(
     "ListTemplatesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxItems": int,
     },
     total=False,
@@ -753,14 +836,32 @@
     {
         "Name": str,
         "CreatedTimestamp": datetime,
     },
     total=False,
 )
 
+ListVerifiedEmailAddressesResponseTypeDef = TypedDict(
+    "ListVerifiedEmailAddressesResponseTypeDef",
+    {
+        "VerifiedEmailAddresses": List[str],
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
 PutIdentityPolicyRequestRequestTypeDef = TypedDict(
     "PutIdentityPolicyRequestRequestTypeDef",
     {
         "Identity": str,
         "PolicyName": str,
         "Policy": str,
     },
@@ -855,14 +956,33 @@
     "ReorderReceiptRuleSetRequestRequestTypeDef",
     {
         "RuleSetName": str,
         "RuleNames": Sequence[str],
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
+SendBounceResponseTypeDef = TypedDict(
+    "SendBounceResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSendCustomVerificationEmailRequestRequestTypeDef = TypedDict(
     "_RequiredSendCustomVerificationEmailRequestRequestTypeDef",
     {
         "EmailAddress": str,
         "TemplateName": str,
     },
 )
@@ -876,14 +996,46 @@
 
 class SendCustomVerificationEmailRequestRequestTypeDef(
     _RequiredSendCustomVerificationEmailRequestRequestTypeDef,
     _OptionalSendCustomVerificationEmailRequestRequestTypeDef,
 ):
     pass
 
+SendCustomVerificationEmailResponseTypeDef = TypedDict(
+    "SendCustomVerificationEmailResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SendEmailResponseTypeDef = TypedDict(
+    "SendEmailResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SendRawEmailResponseTypeDef = TypedDict(
+    "SendRawEmailResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SendTemplatedEmailResponseTypeDef = TypedDict(
+    "SendTemplatedEmailResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SetActiveReceiptRuleSetRequestRequestTypeDef = TypedDict(
     "SetActiveReceiptRuleSetRequestRequestTypeDef",
     {
         "RuleSetName": str,
     },
     total=False,
 )
@@ -980,14 +1132,22 @@
     "TestRenderTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
         "TemplateData": str,
     },
 )
 
+TestRenderTemplateResponseTypeDef = TypedDict(
+    "TestRenderTemplateResponseTypeDef",
+    {
+        "RenderedTemplate": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateAccountSendingEnabledRequestRequestTypeDef = TypedDict(
     "UpdateAccountSendingEnabledRequestRequestTypeDef",
     {
         "Enabled": bool,
     },
     total=False,
 )
@@ -1035,21 +1195,37 @@
 VerifyDomainDkimRequestRequestTypeDef = TypedDict(
     "VerifyDomainDkimRequestRequestTypeDef",
     {
         "Domain": str,
     },
 )
 
+VerifyDomainDkimResponseTypeDef = TypedDict(
+    "VerifyDomainDkimResponseTypeDef",
+    {
+        "DkimTokens": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 VerifyDomainIdentityRequestRequestTypeDef = TypedDict(
     "VerifyDomainIdentityRequestRequestTypeDef",
     {
         "Domain": str,
     },
 )
 
+VerifyDomainIdentityResponseTypeDef = TypedDict(
+    "VerifyDomainIdentityResponseTypeDef",
+    {
+        "VerificationToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 VerifyEmailAddressRequestRequestTypeDef = TypedDict(
     "VerifyEmailAddressRequestRequestTypeDef",
     {
         "EmailAddress": str,
     },
 )
 
@@ -1065,14 +1241,22 @@
     {
         "Text": ContentTypeDef,
         "Html": ContentTypeDef,
     },
     total=False,
 )
 
+SendBulkTemplatedEmailResponseTypeDef = TypedDict(
+    "SendBulkTemplatedEmailResponseTypeDef",
+    {
+        "Status": List[BulkEmailDestinationStatusTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredBulkEmailDestinationTypeDef = TypedDict(
     "_RequiredBulkEmailDestinationTypeDef",
     {
         "Destination": DestinationTypeDef,
     },
 )
 _OptionalBulkEmailDestinationTypeDef = TypedDict(
@@ -1128,14 +1312,23 @@
 CreateConfigurationSetRequestRequestTypeDef = TypedDict(
     "CreateConfigurationSetRequestRequestTypeDef",
     {
         "ConfigurationSet": ConfigurationSetTypeDef,
     },
 )
 
+ListConfigurationSetsResponseTypeDef = TypedDict(
+    "ListConfigurationSetsResponseTypeDef",
+    {
+        "ConfigurationSets": List[ConfigurationSetTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateConfigurationSetTrackingOptionsRequestRequestTypeDef = TypedDict(
     "CreateConfigurationSetTrackingOptionsRequestRequestTypeDef",
     {
         "ConfigurationSetName": str,
         "TrackingOptions": TrackingOptionsTypeDef,
     },
 )
@@ -1151,21 +1344,38 @@
 CreateTemplateRequestRequestTypeDef = TypedDict(
     "CreateTemplateRequestRequestTypeDef",
     {
         "Template": TemplateTypeDef,
     },
 )
 
+GetTemplateResponseTypeDef = TypedDict(
+    "GetTemplateResponseTypeDef",
+    {
+        "Template": TemplateTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateTemplateRequestRequestTypeDef = TypedDict(
     "UpdateTemplateRequestRequestTypeDef",
     {
         "Template": TemplateTypeDef,
     },
 )
 
+ListCustomVerificationEmailTemplatesResponseTypeDef = TypedDict(
+    "ListCustomVerificationEmailTemplatesResponseTypeDef",
+    {
+        "CustomVerificationEmailTemplates": List[CustomVerificationEmailTemplateTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutConfigurationSetDeliveryOptionsRequestRequestTypeDef = TypedDict(
     "_RequiredPutConfigurationSetDeliveryOptionsRequestRequestTypeDef",
     {
         "ConfigurationSetName": str,
     },
 )
 _OptionalPutConfigurationSetDeliveryOptionsRequestRequestTypeDef = TypedDict(
@@ -1178,189 +1388,20 @@
 
 class PutConfigurationSetDeliveryOptionsRequestRequestTypeDef(
     _RequiredPutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
     _OptionalPutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
 ):
     pass
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccountSendingEnabledResponseTypeDef = TypedDict(
-    "GetAccountSendingEnabledResponseTypeDef",
-    {
-        "Enabled": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCustomVerificationEmailTemplateResponseTypeDef = TypedDict(
-    "GetCustomVerificationEmailTemplateResponseTypeDef",
-    {
-        "TemplateName": str,
-        "FromEmailAddress": str,
-        "TemplateSubject": str,
-        "TemplateContent": str,
-        "SuccessRedirectionURL": str,
-        "FailureRedirectionURL": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetIdentityPoliciesResponseTypeDef = TypedDict(
-    "GetIdentityPoliciesResponseTypeDef",
-    {
-        "Policies": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSendQuotaResponseTypeDef = TypedDict(
-    "GetSendQuotaResponseTypeDef",
-    {
-        "Max24HourSend": float,
-        "MaxSendRate": float,
-        "SentLast24Hours": float,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTemplateResponseTypeDef = TypedDict(
-    "GetTemplateResponseTypeDef",
-    {
-        "Template": TemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConfigurationSetsResponseTypeDef = TypedDict(
-    "ListConfigurationSetsResponseTypeDef",
-    {
-        "ConfigurationSets": List[ConfigurationSetTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListCustomVerificationEmailTemplatesResponseTypeDef = TypedDict(
-    "ListCustomVerificationEmailTemplatesResponseTypeDef",
-    {
-        "CustomVerificationEmailTemplates": List[CustomVerificationEmailTemplateTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListIdentitiesResponseTypeDef = TypedDict(
-    "ListIdentitiesResponseTypeDef",
-    {
-        "Identities": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListIdentityPoliciesResponseTypeDef = TypedDict(
-    "ListIdentityPoliciesResponseTypeDef",
-    {
-        "PolicyNames": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListReceiptRuleSetsResponseTypeDef = TypedDict(
     "ListReceiptRuleSetsResponseTypeDef",
     {
         "RuleSets": List[ReceiptRuleSetMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListVerifiedEmailAddressesResponseTypeDef = TypedDict(
-    "ListVerifiedEmailAddressesResponseTypeDef",
-    {
-        "VerifiedEmailAddresses": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendBounceResponseTypeDef = TypedDict(
-    "SendBounceResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendBulkTemplatedEmailResponseTypeDef = TypedDict(
-    "SendBulkTemplatedEmailResponseTypeDef",
-    {
-        "Status": List[BulkEmailDestinationStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendCustomVerificationEmailResponseTypeDef = TypedDict(
-    "SendCustomVerificationEmailResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendEmailResponseTypeDef = TypedDict(
-    "SendEmailResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendRawEmailResponseTypeDef = TypedDict(
-    "SendRawEmailResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendTemplatedEmailResponseTypeDef = TypedDict(
-    "SendTemplatedEmailResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestRenderTemplateResponseTypeDef = TypedDict(
-    "TestRenderTemplateResponseTypeDef",
-    {
-        "RenderedTemplate": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-VerifyDomainDkimResponseTypeDef = TypedDict(
-    "VerifyDomainDkimResponseTypeDef",
-    {
-        "DkimTokens": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-VerifyDomainIdentityResponseTypeDef = TypedDict(
-    "VerifyDomainIdentityResponseTypeDef",
-    {
-        "VerificationToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMessageDsnTypeDef = TypedDict(
     "_RequiredMessageDsnTypeDef",
     {
         "ReportingMta": str,
@@ -1402,31 +1443,31 @@
 ):
     pass
 
 GetIdentityDkimAttributesResponseTypeDef = TypedDict(
     "GetIdentityDkimAttributesResponseTypeDef",
     {
         "DkimAttributes": Dict[str, IdentityDkimAttributesTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIdentityMailFromDomainAttributesResponseTypeDef = TypedDict(
     "GetIdentityMailFromDomainAttributesResponseTypeDef",
     {
         "MailFromDomainAttributes": Dict[str, IdentityMailFromDomainAttributesTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIdentityNotificationAttributesResponseTypeDef = TypedDict(
     "GetIdentityNotificationAttributesResponseTypeDef",
     {
         "NotificationAttributes": Dict[str, IdentityNotificationAttributesTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetIdentityVerificationAttributesRequestIdentityExistsWaitTypeDef = TypedDict(
     "_RequiredGetIdentityVerificationAttributesRequestIdentityExistsWaitTypeDef",
     {
         "Identities": Sequence[str],
@@ -1446,73 +1487,32 @@
 ):
     pass
 
 GetIdentityVerificationAttributesResponseTypeDef = TypedDict(
     "GetIdentityVerificationAttributesResponseTypeDef",
     {
         "VerificationAttributes": Dict[str, IdentityVerificationAttributesTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSendStatisticsResponseTypeDef = TypedDict(
     "GetSendStatisticsResponseTypeDef",
     {
         "SendDataPoints": List[SendDataPointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef = TypedDict(
-    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef = TypedDict(
-    "ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListIdentitiesRequestListIdentitiesPaginateTypeDef = TypedDict(
-    "ListIdentitiesRequestListIdentitiesPaginateTypeDef",
-    {
-        "IdentityType": IdentityTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef = TypedDict(
-    "ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTemplatesRequestListTemplatesPaginateTypeDef = TypedDict(
-    "ListTemplatesRequestListTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 ListTemplatesResponseTypeDef = TypedDict(
     "ListTemplatesResponseTypeDef",
     {
         "TemplatesMetadata": List[TemplateMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSendRawEmailRequestRequestTypeDef = TypedDict(
     "_RequiredSendRawEmailRequestRequestTypeDef",
     {
         "RawMessage": RawMessageTypeDef,
@@ -1666,15 +1666,15 @@
     },
 )
 
 ListReceiptFiltersResponseTypeDef = TypedDict(
     "ListReceiptFiltersResponseTypeDef",
     {
         "Filters": List[ReceiptFilterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSendEmailRequestRequestTypeDef = TypedDict(
     "_RequiredSendEmailRequestRequestTypeDef",
     {
         "Source": str,
@@ -1712,15 +1712,15 @@
     "DescribeConfigurationSetResponseTypeDef",
     {
         "ConfigurationSet": ConfigurationSetTypeDef,
         "EventDestinations": List[EventDestinationTypeDef],
         "TrackingOptions": TrackingOptionsTypeDef,
         "DeliveryOptions": DeliveryOptionsTypeDef,
         "ReputationOptions": ReputationOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateConfigurationSetEventDestinationRequestRequestTypeDef = TypedDict(
     "UpdateConfigurationSetEventDestinationRequestRequestTypeDef",
     {
         "ConfigurationSetName": str,
@@ -1772,32 +1772,32 @@
     pass
 
 DescribeActiveReceiptRuleSetResponseTypeDef = TypedDict(
     "DescribeActiveReceiptRuleSetResponseTypeDef",
     {
         "Metadata": ReceiptRuleSetMetadataTypeDef,
         "Rules": List[ReceiptRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReceiptRuleResponseTypeDef = TypedDict(
     "DescribeReceiptRuleResponseTypeDef",
     {
         "Rule": ReceiptRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReceiptRuleSetResponseTypeDef = TypedDict(
     "DescribeReceiptRuleSetResponseTypeDef",
     {
         "Metadata": ReceiptRuleSetMetadataTypeDef,
         "Rules": List[ReceiptRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateReceiptRuleRequestRequestTypeDef = TypedDict(
     "UpdateReceiptRuleRequestRequestTypeDef",
     {
         "RuleSetName": str,
```

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/waiter.py` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses/waiter.pyi` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses.egg-info/PKG-INFO` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ses
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SES 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SES 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ses"></a>
 
 # types-aiobotocore-ses
 
 [![PyPI - types-aiobotocore-ses](https://img.shields.io/pypi/v/types-aiobotocore-ses.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ses)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ses.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ses)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ses?color=blue)](https://pypistats.org/packages/types-aiobotocore-ses)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SES 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES)
+[aiobotocore.SES 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ses.html#SES)
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
 [types-aiobotocore-ses docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ses/).
 
 See how it helps to find and fix potential bugs:
 
@@ -400,113 +400,113 @@
     DeleteReceiptFilterRequestRequestTypeDef,
     DeleteReceiptRuleRequestRequestTypeDef,
     DeleteReceiptRuleSetRequestRequestTypeDef,
     DeleteTemplateRequestRequestTypeDef,
     DeleteVerifiedEmailAddressRequestRequestTypeDef,
     DeliveryOptionsTypeDef,
     ReceiptRuleSetMetadataTypeDef,
-    ResponseMetadataTypeDef,
     DescribeConfigurationSetRequestRequestTypeDef,
     ReputationOptionsTypeDef,
     DescribeReceiptRuleRequestRequestTypeDef,
     DescribeReceiptRuleSetRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     KinesisFirehoseDestinationTypeDef,
     SNSDestinationTypeDef,
     ExtensionFieldTypeDef,
+    GetAccountSendingEnabledResponseTypeDef,
     GetCustomVerificationEmailTemplateRequestRequestTypeDef,
+    GetCustomVerificationEmailTemplateResponseTypeDef,
     GetIdentityDkimAttributesRequestRequestTypeDef,
     IdentityDkimAttributesTypeDef,
     GetIdentityMailFromDomainAttributesRequestRequestTypeDef,
     IdentityMailFromDomainAttributesTypeDef,
     GetIdentityNotificationAttributesRequestRequestTypeDef,
     IdentityNotificationAttributesTypeDef,
     GetIdentityPoliciesRequestRequestTypeDef,
+    GetIdentityPoliciesResponseTypeDef,
     WaiterConfigTypeDef,
     GetIdentityVerificationAttributesRequestRequestTypeDef,
     IdentityVerificationAttributesTypeDef,
+    GetSendQuotaResponseTypeDef,
     SendDataPointTypeDef,
     GetTemplateRequestRequestTypeDef,
     LambdaActionTypeDef,
-    PaginatorConfigTypeDef,
+    ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef,
     ListConfigurationSetsRequestRequestTypeDef,
+    ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef,
     ListCustomVerificationEmailTemplatesRequestRequestTypeDef,
+    ListIdentitiesRequestListIdentitiesPaginateTypeDef,
     ListIdentitiesRequestRequestTypeDef,
+    ListIdentitiesResponseTypeDef,
     ListIdentityPoliciesRequestRequestTypeDef,
+    ListIdentityPoliciesResponseTypeDef,
+    ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef,
     ListReceiptRuleSetsRequestRequestTypeDef,
+    ListTemplatesRequestListTemplatesPaginateTypeDef,
     ListTemplatesRequestRequestTypeDef,
     TemplateMetadataTypeDef,
+    ListVerifiedEmailAddressesResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutIdentityPolicyRequestRequestTypeDef,
     RawMessageTypeDef,
     S3ActionTypeDef,
     SNSActionTypeDef,
     StopActionTypeDef,
     WorkmailActionTypeDef,
     ReceiptIpFilterTypeDef,
     ReorderReceiptRuleSetRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SendBounceResponseTypeDef,
     SendCustomVerificationEmailRequestRequestTypeDef,
+    SendCustomVerificationEmailResponseTypeDef,
+    SendEmailResponseTypeDef,
+    SendRawEmailResponseTypeDef,
+    SendTemplatedEmailResponseTypeDef,
     SetActiveReceiptRuleSetRequestRequestTypeDef,
     SetIdentityDkimEnabledRequestRequestTypeDef,
     SetIdentityFeedbackForwardingEnabledRequestRequestTypeDef,
     SetIdentityHeadersInNotificationsEnabledRequestRequestTypeDef,
     SetIdentityMailFromDomainRequestRequestTypeDef,
     SetIdentityNotificationTopicRequestRequestTypeDef,
     SetReceiptRulePositionRequestRequestTypeDef,
     TestRenderTemplateRequestRequestTypeDef,
+    TestRenderTemplateResponseTypeDef,
     UpdateAccountSendingEnabledRequestRequestTypeDef,
     UpdateConfigurationSetReputationMetricsEnabledRequestRequestTypeDef,
     UpdateConfigurationSetSendingEnabledRequestRequestTypeDef,
     UpdateCustomVerificationEmailTemplateRequestRequestTypeDef,
     VerifyDomainDkimRequestRequestTypeDef,
+    VerifyDomainDkimResponseTypeDef,
     VerifyDomainIdentityRequestRequestTypeDef,
+    VerifyDomainIdentityResponseTypeDef,
     VerifyEmailAddressRequestRequestTypeDef,
     VerifyEmailIdentityRequestRequestTypeDef,
     BodyTypeDef,
+    SendBulkTemplatedEmailResponseTypeDef,
     BulkEmailDestinationTypeDef,
     SendTemplatedEmailRequestRequestTypeDef,
     CloudWatchDestinationTypeDef,
     CreateConfigurationSetRequestRequestTypeDef,
+    ListConfigurationSetsResponseTypeDef,
     CreateConfigurationSetTrackingOptionsRequestRequestTypeDef,
     UpdateConfigurationSetTrackingOptionsRequestRequestTypeDef,
     CreateTemplateRequestRequestTypeDef,
-    UpdateTemplateRequestRequestTypeDef,
-    PutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAccountSendingEnabledResponseTypeDef,
-    GetCustomVerificationEmailTemplateResponseTypeDef,
-    GetIdentityPoliciesResponseTypeDef,
-    GetSendQuotaResponseTypeDef,
     GetTemplateResponseTypeDef,
-    ListConfigurationSetsResponseTypeDef,
+    UpdateTemplateRequestRequestTypeDef,
     ListCustomVerificationEmailTemplatesResponseTypeDef,
-    ListIdentitiesResponseTypeDef,
-    ListIdentityPoliciesResponseTypeDef,
+    PutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
     ListReceiptRuleSetsResponseTypeDef,
-    ListVerifiedEmailAddressesResponseTypeDef,
-    SendBounceResponseTypeDef,
-    SendBulkTemplatedEmailResponseTypeDef,
-    SendCustomVerificationEmailResponseTypeDef,
-    SendEmailResponseTypeDef,
-    SendRawEmailResponseTypeDef,
-    SendTemplatedEmailResponseTypeDef,
-    TestRenderTemplateResponseTypeDef,
-    VerifyDomainDkimResponseTypeDef,
-    VerifyDomainIdentityResponseTypeDef,
     MessageDsnTypeDef,
     RecipientDsnFieldsTypeDef,
     GetIdentityDkimAttributesResponseTypeDef,
     GetIdentityMailFromDomainAttributesResponseTypeDef,
     GetIdentityNotificationAttributesResponseTypeDef,
     GetIdentityVerificationAttributesRequestIdentityExistsWaitTypeDef,
     GetIdentityVerificationAttributesResponseTypeDef,
     GetSendStatisticsResponseTypeDef,
-    ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef,
-    ListCustomVerificationEmailTemplatesRequestListCustomVerificationEmailTemplatesPaginateTypeDef,
-    ListIdentitiesRequestListIdentitiesPaginateTypeDef,
-    ListReceiptRuleSetsRequestListReceiptRuleSetsPaginateTypeDef,
-    ListTemplatesRequestListTemplatesPaginateTypeDef,
     ListTemplatesResponseTypeDef,
     SendRawEmailRequestRequestTypeDef,
     ReceiptActionTypeDef,
     ReceiptFilterTypeDef,
     MessageTypeDef,
     SendBulkTemplatedEmailRequestRequestTypeDef,
     EventDestinationTypeDef,
@@ -534,43 +534,43 @@
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

### Comparing `types-aiobotocore-ses-2.5.0.post1/types_aiobotocore_ses.egg-info/SOURCES.txt` & `types-aiobotocore-ses-2.5.1/types_aiobotocore_ses.egg-info/SOURCES.txt`

 * *Files identical despite different names*


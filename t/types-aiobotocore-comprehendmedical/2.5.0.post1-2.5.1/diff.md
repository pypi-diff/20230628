# Comparing `tmp/types-aiobotocore-comprehendmedical-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-comprehendmedical-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-comprehendmedical-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:26 2023, max compression
+gzip compressed data, was "types-aiobotocore-comprehendmedical-2.5.1.tar", last modified: Wed Jun 28 01:43:18 2023, max compression
```

## Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1.tar` & `types-aiobotocore-comprehendmedical-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:26.063085 types-aiobotocore-comprehendmedical-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:40.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16053 2023-03-11 12:26:26.063085 types-aiobotocore-comprehendmedical-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14442 2023-03-11 12:11:40.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:26.063085 types-aiobotocore-comprehendmedical-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2210 2023-03-11 12:11:40.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:26.059085 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/
--rw-r--r--   0 runner    (1001) docker     (123)      522 2023-03-11 12:11:40.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      521 2023-03-11 12:11:40.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      983 2023-03-11 12:11:40.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23289 2023-03-11 12:11:40.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    23254 2023-03-11 12:11:40.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11363 2023-03-11 12:11:41.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11361 2023-03-11 12:11:41.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:40.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    24885 2023-03-11 12:11:42.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    24870 2023-03-11 12:11:42.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:40.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:26.063085 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16053 2023-03-11 12:26:25.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      904 2023-03-11 12:26:25.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:25.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:25.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:25.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       36 2023-03-11 12:26:25.000000 types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:18.082116 types-aiobotocore-comprehendmedical-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:18.000000 types-aiobotocore-comprehendmedical-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16055 2023-06-28 01:43:18.082116 types-aiobotocore-comprehendmedical-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14450 2023-06-28 01:28:18.000000 types-aiobotocore-comprehendmedical-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:18.082116 types-aiobotocore-comprehendmedical-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2204 2023-06-28 01:28:18.000000 types-aiobotocore-comprehendmedical-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:18.074115 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/
+-rw-r--r--   0 runner    (1001) docker     (123)      522 2023-06-28 01:28:18.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      521 2023-06-28 01:28:18.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      971 2023-06-28 01:28:18.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23289 2023-06-28 01:28:18.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23254 2023-06-28 01:28:18.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11640 2023-06-28 01:28:19.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11638 2023-06-28 01:28:19.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:18.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    24962 2023-06-28 01:28:19.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24947 2023-06-28 01:28:19.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:18.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:18.082116 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16055 2023-06-28 01:43:17.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:43:17.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:17.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:17.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:17.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 01:43:17.000000 types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/LICENSE` & `types-aiobotocore-comprehendmedical-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/PKG-INFO` & `types-aiobotocore-comprehendmedical-2.5.1/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-comprehendmedical
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ComprehendMedical 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ComprehendMedical 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehendmedical/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-comprehendmedical"></a>
 
 # types-aiobotocore-comprehendmedical
 
 [![PyPI - types-aiobotocore-comprehendmedical](https://img.shields.io/pypi/v/types-aiobotocore-comprehendmedical.svg?color=blue)](https://pypi.org/project/types-aiobotocore-comprehendmedical)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-comprehendmedical.svg?color=blue)](https://pypi.org/project/types-aiobotocore-comprehendmedical)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehendmedical/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-comprehendmedical?color=blue)](https://pypistats.org/packages/types-aiobotocore-comprehendmedical)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ComprehendMedical 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehendmedical.html#ComprehendMedical)
+[aiobotocore.ComprehendMedical 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehendmedical.html#ComprehendMedical)
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
 [types-aiobotocore-comprehendmedical docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehendmedical/).
 
 See how it helps to find and fix potential bugs:
 
@@ -315,59 +315,59 @@
 from types_aiobotocore_comprehendmedical.type_defs import (
     TraitTypeDef,
     CharactersTypeDef,
     ComprehendMedicalAsyncJobFilterTypeDef,
     InputDataConfigTypeDef,
     OutputDataConfigTypeDef,
     DescribeEntitiesDetectionV2JobRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     DescribeICD10CMInferenceJobRequestRequestTypeDef,
     DescribePHIDetectionJobRequestRequestTypeDef,
     DescribeRxNormInferenceJobRequestRequestTypeDef,
     DescribeSNOMEDCTInferenceJobRequestRequestTypeDef,
     DetectEntitiesRequestRequestTypeDef,
     DetectEntitiesV2RequestRequestTypeDef,
     DetectPHIRequestRequestTypeDef,
     ICD10CMTraitTypeDef,
     ICD10CMConceptTypeDef,
     InferICD10CMRequestRequestTypeDef,
     InferRxNormRequestRequestTypeDef,
     InferSNOMEDCTRequestRequestTypeDef,
     SNOMEDCTDetailsTypeDef,
+    ResponseMetadataTypeDef,
     RxNormTraitTypeDef,
     RxNormConceptTypeDef,
     SNOMEDCTConceptTypeDef,
     SNOMEDCTTraitTypeDef,
+    StartEntitiesDetectionV2JobResponseTypeDef,
+    StartICD10CMInferenceJobResponseTypeDef,
+    StartPHIDetectionJobResponseTypeDef,
+    StartRxNormInferenceJobResponseTypeDef,
+    StartSNOMEDCTInferenceJobResponseTypeDef,
     StopEntitiesDetectionV2JobRequestRequestTypeDef,
+    StopEntitiesDetectionV2JobResponseTypeDef,
     StopICD10CMInferenceJobRequestRequestTypeDef,
+    StopICD10CMInferenceJobResponseTypeDef,
     StopPHIDetectionJobRequestRequestTypeDef,
+    StopPHIDetectionJobResponseTypeDef,
     StopRxNormInferenceJobRequestRequestTypeDef,
+    StopRxNormInferenceJobResponseTypeDef,
     StopSNOMEDCTInferenceJobRequestRequestTypeDef,
+    StopSNOMEDCTInferenceJobResponseTypeDef,
     AttributeTypeDef,
     ListEntitiesDetectionV2JobsRequestRequestTypeDef,
     ListICD10CMInferenceJobsRequestRequestTypeDef,
     ListPHIDetectionJobsRequestRequestTypeDef,
     ListRxNormInferenceJobsRequestRequestTypeDef,
     ListSNOMEDCTInferenceJobsRequestRequestTypeDef,
     ComprehendMedicalAsyncJobPropertiesTypeDef,
     StartEntitiesDetectionV2JobRequestRequestTypeDef,
     StartICD10CMInferenceJobRequestRequestTypeDef,
     StartPHIDetectionJobRequestRequestTypeDef,
     StartRxNormInferenceJobRequestRequestTypeDef,
     StartSNOMEDCTInferenceJobRequestRequestTypeDef,
-    StartEntitiesDetectionV2JobResponseTypeDef,
-    StartICD10CMInferenceJobResponseTypeDef,
-    StartPHIDetectionJobResponseTypeDef,
-    StartRxNormInferenceJobResponseTypeDef,
-    StartSNOMEDCTInferenceJobResponseTypeDef,
-    StopEntitiesDetectionV2JobResponseTypeDef,
-    StopICD10CMInferenceJobResponseTypeDef,
-    StopPHIDetectionJobResponseTypeDef,
-    StopRxNormInferenceJobResponseTypeDef,
-    StopSNOMEDCTInferenceJobResponseTypeDef,
     ICD10CMAttributeTypeDef,
     RxNormAttributeTypeDef,
     SNOMEDCTAttributeTypeDef,
     EntityTypeDef,
     UnmappedAttributeTypeDef,
     DescribeEntitiesDetectionV2JobResponseTypeDef,
     DescribeICD10CMInferenceJobResponseTypeDef,
@@ -398,43 +398,43 @@
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

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/README.md` & `types-aiobotocore-comprehendmedical-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-comprehendmedical"></a>
 
 # types-aiobotocore-comprehendmedical
 
 [![PyPI - types-aiobotocore-comprehendmedical](https://img.shields.io/pypi/v/types-aiobotocore-comprehendmedical.svg?color=blue)](https://pypi.org/project/types-aiobotocore-comprehendmedical)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-comprehendmedical.svg?color=blue)](https://pypi.org/project/types-aiobotocore-comprehendmedical)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehendmedical/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-comprehendmedical?color=blue)](https://pypistats.org/packages/types-aiobotocore-comprehendmedical)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ComprehendMedical 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehendmedical.html#ComprehendMedical)
+[aiobotocore.ComprehendMedical 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehendmedical.html#ComprehendMedical)
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
 [types-aiobotocore-comprehendmedical docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehendmedical/).
 
 See how it helps to find and fix potential bugs:
 
@@ -282,59 +282,59 @@
 from types_aiobotocore_comprehendmedical.type_defs import (
     TraitTypeDef,
     CharactersTypeDef,
     ComprehendMedicalAsyncJobFilterTypeDef,
     InputDataConfigTypeDef,
     OutputDataConfigTypeDef,
     DescribeEntitiesDetectionV2JobRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     DescribeICD10CMInferenceJobRequestRequestTypeDef,
     DescribePHIDetectionJobRequestRequestTypeDef,
     DescribeRxNormInferenceJobRequestRequestTypeDef,
     DescribeSNOMEDCTInferenceJobRequestRequestTypeDef,
     DetectEntitiesRequestRequestTypeDef,
     DetectEntitiesV2RequestRequestTypeDef,
     DetectPHIRequestRequestTypeDef,
     ICD10CMTraitTypeDef,
     ICD10CMConceptTypeDef,
     InferICD10CMRequestRequestTypeDef,
     InferRxNormRequestRequestTypeDef,
     InferSNOMEDCTRequestRequestTypeDef,
     SNOMEDCTDetailsTypeDef,
+    ResponseMetadataTypeDef,
     RxNormTraitTypeDef,
     RxNormConceptTypeDef,
     SNOMEDCTConceptTypeDef,
     SNOMEDCTTraitTypeDef,
+    StartEntitiesDetectionV2JobResponseTypeDef,
+    StartICD10CMInferenceJobResponseTypeDef,
+    StartPHIDetectionJobResponseTypeDef,
+    StartRxNormInferenceJobResponseTypeDef,
+    StartSNOMEDCTInferenceJobResponseTypeDef,
     StopEntitiesDetectionV2JobRequestRequestTypeDef,
+    StopEntitiesDetectionV2JobResponseTypeDef,
     StopICD10CMInferenceJobRequestRequestTypeDef,
+    StopICD10CMInferenceJobResponseTypeDef,
     StopPHIDetectionJobRequestRequestTypeDef,
+    StopPHIDetectionJobResponseTypeDef,
     StopRxNormInferenceJobRequestRequestTypeDef,
+    StopRxNormInferenceJobResponseTypeDef,
     StopSNOMEDCTInferenceJobRequestRequestTypeDef,
+    StopSNOMEDCTInferenceJobResponseTypeDef,
     AttributeTypeDef,
     ListEntitiesDetectionV2JobsRequestRequestTypeDef,
     ListICD10CMInferenceJobsRequestRequestTypeDef,
     ListPHIDetectionJobsRequestRequestTypeDef,
     ListRxNormInferenceJobsRequestRequestTypeDef,
     ListSNOMEDCTInferenceJobsRequestRequestTypeDef,
     ComprehendMedicalAsyncJobPropertiesTypeDef,
     StartEntitiesDetectionV2JobRequestRequestTypeDef,
     StartICD10CMInferenceJobRequestRequestTypeDef,
     StartPHIDetectionJobRequestRequestTypeDef,
     StartRxNormInferenceJobRequestRequestTypeDef,
     StartSNOMEDCTInferenceJobRequestRequestTypeDef,
-    StartEntitiesDetectionV2JobResponseTypeDef,
-    StartICD10CMInferenceJobResponseTypeDef,
-    StartPHIDetectionJobResponseTypeDef,
-    StartRxNormInferenceJobResponseTypeDef,
-    StartSNOMEDCTInferenceJobResponseTypeDef,
-    StopEntitiesDetectionV2JobResponseTypeDef,
-    StopICD10CMInferenceJobResponseTypeDef,
-    StopPHIDetectionJobResponseTypeDef,
-    StopRxNormInferenceJobResponseTypeDef,
-    StopSNOMEDCTInferenceJobResponseTypeDef,
     ICD10CMAttributeTypeDef,
     RxNormAttributeTypeDef,
     SNOMEDCTAttributeTypeDef,
     EntityTypeDef,
     UnmappedAttributeTypeDef,
     DescribeEntitiesDetectionV2JobResponseTypeDef,
     DescribeICD10CMInferenceJobResponseTypeDef,
@@ -365,43 +365,43 @@
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

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/setup.py` & `types-aiobotocore-comprehendmedical-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-comprehendmedical.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-comprehendmedical",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_comprehendmedical"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ComprehendMedical 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ComprehendMedical 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -50,11 +50,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehendmedical/"
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

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/__init__.py` & `types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/__init__.pyi` & `types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/__main__.py` & `types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ComprehendMedical 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ComprehendMedical 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehendmedical//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehendmedical.html#ComprehendMedical\nOther"
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

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/client.py` & `types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/client.pyi` & `types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/literals.py` & `types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/literals.py`

 * *Files 5% similar despite different names*

```diff
@@ -121,15 +121,15 @@
     "QUANTITY",
     "SYSTEM_ORGAN_SITE",
     "TIME_EXPRESSION",
     "TIME_TO_DX_NAME",
 ]
 ICD10CMEntityCategoryType = Literal["MEDICAL_CONDITION"]
 ICD10CMEntityTypeType = Literal["DX_NAME", "TIME_EXPRESSION"]
-ICD10CMRelationshipTypeType = Literal["OVERLAP", "SYSTEM_ORGAN_SITE"]
+ICD10CMRelationshipTypeType = Literal["OVERLAP", "QUALITY", "SYSTEM_ORGAN_SITE"]
 ICD10CMTraitNameType = Literal[
     "DIAGNOSIS",
     "HYPOTHETICAL",
     "LOW_CONFIDENCE",
     "NEGATION",
     "PERTAINS_TO_FAMILY",
     "SIGN",
@@ -154,36 +154,38 @@
     "DURATION",
     "EVERY",
     "FOR",
     "FORM",
     "FREQUENCY",
     "NEGATIVE",
     "OVERLAP",
+    "QUALITY",
     "RATE",
     "ROUTE_OR_MODE",
     "STRENGTH",
     "SYSTEM_ORGAN_SITE",
     "TEST_UNIT",
     "TEST_UNITS",
     "TEST_VALUE",
+    "USAGE",
     "WITH_DOSAGE",
 ]
 RxNormAttributeTypeType = Literal[
     "DOSAGE", "DURATION", "FORM", "FREQUENCY", "RATE", "ROUTE_OR_MODE", "STRENGTH"
 ]
 RxNormEntityCategoryType = Literal["MEDICATION"]
 RxNormEntityTypeType = Literal["BRAND_NAME", "GENERIC_NAME"]
-RxNormTraitNameType = Literal["NEGATION"]
+RxNormTraitNameType = Literal["NEGATION", "PAST_HISTORY"]
 SNOMEDCTAttributeTypeType = Literal[
     "ACUITY", "DIRECTION", "QUALITY", "SYSTEM_ORGAN_SITE", "TEST_UNIT", "TEST_VALUE"
 ]
 SNOMEDCTEntityCategoryType = Literal["ANATOMY", "MEDICAL_CONDITION", "TEST_TREATMENT_PROCEDURE"]
 SNOMEDCTEntityTypeType = Literal["DX_NAME", "PROCEDURE_NAME", "TEST_NAME", "TREATMENT_NAME"]
 SNOMEDCTRelationshipTypeType = Literal[
-    "ACUITY", "DIRECTION", "QUALITY", "SYSTEM_ORGAN_SITE", "TEST_UNITS", "TEST_VALUE"
+    "ACUITY", "DIRECTION", "QUALITY", "SYSTEM_ORGAN_SITE", "TEST_UNIT", "TEST_UNITS", "TEST_VALUE"
 ]
 SNOMEDCTTraitNameType = Literal[
     "DIAGNOSIS",
     "FUTURE",
     "HYPOTHETICAL",
     "LOW_CONFIDENCE",
     "NEGATION",
@@ -251,14 +253,15 @@
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
@@ -337,14 +340,15 @@
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
@@ -355,14 +359,15 @@
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
@@ -398,14 +403,15 @@
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
@@ -424,16 +430,19 @@
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
@@ -517,15 +526,17 @@
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

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/literals.pyi` & `types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -119,15 +119,15 @@
     "QUANTITY",
     "SYSTEM_ORGAN_SITE",
     "TIME_EXPRESSION",
     "TIME_TO_DX_NAME",
 ]
 ICD10CMEntityCategoryType = Literal["MEDICAL_CONDITION"]
 ICD10CMEntityTypeType = Literal["DX_NAME", "TIME_EXPRESSION"]
-ICD10CMRelationshipTypeType = Literal["OVERLAP", "SYSTEM_ORGAN_SITE"]
+ICD10CMRelationshipTypeType = Literal["OVERLAP", "QUALITY", "SYSTEM_ORGAN_SITE"]
 ICD10CMTraitNameType = Literal[
     "DIAGNOSIS",
     "HYPOTHETICAL",
     "LOW_CONFIDENCE",
     "NEGATION",
     "PERTAINS_TO_FAMILY",
     "SIGN",
@@ -152,36 +152,38 @@
     "DURATION",
     "EVERY",
     "FOR",
     "FORM",
     "FREQUENCY",
     "NEGATIVE",
     "OVERLAP",
+    "QUALITY",
     "RATE",
     "ROUTE_OR_MODE",
     "STRENGTH",
     "SYSTEM_ORGAN_SITE",
     "TEST_UNIT",
     "TEST_UNITS",
     "TEST_VALUE",
+    "USAGE",
     "WITH_DOSAGE",
 ]
 RxNormAttributeTypeType = Literal[
     "DOSAGE", "DURATION", "FORM", "FREQUENCY", "RATE", "ROUTE_OR_MODE", "STRENGTH"
 ]
 RxNormEntityCategoryType = Literal["MEDICATION"]
 RxNormEntityTypeType = Literal["BRAND_NAME", "GENERIC_NAME"]
-RxNormTraitNameType = Literal["NEGATION"]
+RxNormTraitNameType = Literal["NEGATION", "PAST_HISTORY"]
 SNOMEDCTAttributeTypeType = Literal[
     "ACUITY", "DIRECTION", "QUALITY", "SYSTEM_ORGAN_SITE", "TEST_UNIT", "TEST_VALUE"
 ]
 SNOMEDCTEntityCategoryType = Literal["ANATOMY", "MEDICAL_CONDITION", "TEST_TREATMENT_PROCEDURE"]
 SNOMEDCTEntityTypeType = Literal["DX_NAME", "PROCEDURE_NAME", "TEST_NAME", "TREATMENT_NAME"]
 SNOMEDCTRelationshipTypeType = Literal[
-    "ACUITY", "DIRECTION", "QUALITY", "SYSTEM_ORGAN_SITE", "TEST_UNITS", "TEST_VALUE"
+    "ACUITY", "DIRECTION", "QUALITY", "SYSTEM_ORGAN_SITE", "TEST_UNIT", "TEST_UNITS", "TEST_VALUE"
 ]
 SNOMEDCTTraitNameType = Literal[
     "DIAGNOSIS",
     "FUTURE",
     "HYPOTHETICAL",
     "LOW_CONFIDENCE",
     "NEGATION",
@@ -249,14 +251,15 @@
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
@@ -335,14 +338,15 @@
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
@@ -353,14 +357,15 @@
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
@@ -396,14 +401,15 @@
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
@@ -422,16 +428,19 @@
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
@@ -515,15 +524,17 @@
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

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/type_defs.py` & `types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -23,14 +23,15 @@
     ICD10CMEntityTypeType,
     ICD10CMRelationshipTypeType,
     ICD10CMTraitNameType,
     JobStatusType,
     RelationshipTypeType,
     RxNormAttributeTypeType,
     RxNormEntityTypeType,
+    RxNormTraitNameType,
     SNOMEDCTAttributeTypeType,
     SNOMEDCTEntityCategoryType,
     SNOMEDCTEntityTypeType,
     SNOMEDCTRelationshipTypeType,
     SNOMEDCTTraitNameType,
 )
 
@@ -47,59 +48,59 @@
 __all__ = (
     "TraitTypeDef",
     "CharactersTypeDef",
     "ComprehendMedicalAsyncJobFilterTypeDef",
     "InputDataConfigTypeDef",
     "OutputDataConfigTypeDef",
     "DescribeEntitiesDetectionV2JobRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "DescribeICD10CMInferenceJobRequestRequestTypeDef",
     "DescribePHIDetectionJobRequestRequestTypeDef",
     "DescribeRxNormInferenceJobRequestRequestTypeDef",
     "DescribeSNOMEDCTInferenceJobRequestRequestTypeDef",
     "DetectEntitiesRequestRequestTypeDef",
     "DetectEntitiesV2RequestRequestTypeDef",
     "DetectPHIRequestRequestTypeDef",
     "ICD10CMTraitTypeDef",
     "ICD10CMConceptTypeDef",
     "InferICD10CMRequestRequestTypeDef",
     "InferRxNormRequestRequestTypeDef",
     "InferSNOMEDCTRequestRequestTypeDef",
     "SNOMEDCTDetailsTypeDef",
+    "ResponseMetadataTypeDef",
     "RxNormTraitTypeDef",
     "RxNormConceptTypeDef",
     "SNOMEDCTConceptTypeDef",
     "SNOMEDCTTraitTypeDef",
+    "StartEntitiesDetectionV2JobResponseTypeDef",
+    "StartICD10CMInferenceJobResponseTypeDef",
+    "StartPHIDetectionJobResponseTypeDef",
+    "StartRxNormInferenceJobResponseTypeDef",
+    "StartSNOMEDCTInferenceJobResponseTypeDef",
     "StopEntitiesDetectionV2JobRequestRequestTypeDef",
+    "StopEntitiesDetectionV2JobResponseTypeDef",
     "StopICD10CMInferenceJobRequestRequestTypeDef",
+    "StopICD10CMInferenceJobResponseTypeDef",
     "StopPHIDetectionJobRequestRequestTypeDef",
+    "StopPHIDetectionJobResponseTypeDef",
     "StopRxNormInferenceJobRequestRequestTypeDef",
+    "StopRxNormInferenceJobResponseTypeDef",
     "StopSNOMEDCTInferenceJobRequestRequestTypeDef",
+    "StopSNOMEDCTInferenceJobResponseTypeDef",
     "AttributeTypeDef",
     "ListEntitiesDetectionV2JobsRequestRequestTypeDef",
     "ListICD10CMInferenceJobsRequestRequestTypeDef",
     "ListPHIDetectionJobsRequestRequestTypeDef",
     "ListRxNormInferenceJobsRequestRequestTypeDef",
     "ListSNOMEDCTInferenceJobsRequestRequestTypeDef",
     "ComprehendMedicalAsyncJobPropertiesTypeDef",
     "StartEntitiesDetectionV2JobRequestRequestTypeDef",
     "StartICD10CMInferenceJobRequestRequestTypeDef",
     "StartPHIDetectionJobRequestRequestTypeDef",
     "StartRxNormInferenceJobRequestRequestTypeDef",
     "StartSNOMEDCTInferenceJobRequestRequestTypeDef",
-    "StartEntitiesDetectionV2JobResponseTypeDef",
-    "StartICD10CMInferenceJobResponseTypeDef",
-    "StartPHIDetectionJobResponseTypeDef",
-    "StartRxNormInferenceJobResponseTypeDef",
-    "StartSNOMEDCTInferenceJobResponseTypeDef",
-    "StopEntitiesDetectionV2JobResponseTypeDef",
-    "StopICD10CMInferenceJobResponseTypeDef",
-    "StopPHIDetectionJobResponseTypeDef",
-    "StopRxNormInferenceJobResponseTypeDef",
-    "StopSNOMEDCTInferenceJobResponseTypeDef",
     "ICD10CMAttributeTypeDef",
     "RxNormAttributeTypeDef",
     "SNOMEDCTAttributeTypeDef",
     "EntityTypeDef",
     "UnmappedAttributeTypeDef",
     "DescribeEntitiesDetectionV2JobResponseTypeDef",
     "DescribeICD10CMInferenceJobResponseTypeDef",
@@ -191,25 +192,14 @@
 DescribeEntitiesDetectionV2JobRequestRequestTypeDef = TypedDict(
     "DescribeEntitiesDetectionV2JobRequestRequestTypeDef",
     {
         "JobId": str,
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
 DescribeICD10CMInferenceJobRequestRequestTypeDef = TypedDict(
     "DescribeICD10CMInferenceJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
@@ -301,18 +291,29 @@
         "Edition": str,
         "Language": str,
         "VersionDate": str,
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
 RxNormTraitTypeDef = TypedDict(
     "RxNormTraitTypeDef",
     {
-        "Name": Literal["NEGATION"],
+        "Name": RxNormTraitNameType,
         "Score": float,
     },
     total=False,
 )
 
 RxNormConceptTypeDef = TypedDict(
     "RxNormConceptTypeDef",
@@ -339,49 +340,129 @@
     {
         "Name": SNOMEDCTTraitNameType,
         "Score": float,
     },
     total=False,
 )
 
+StartEntitiesDetectionV2JobResponseTypeDef = TypedDict(
+    "StartEntitiesDetectionV2JobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartICD10CMInferenceJobResponseTypeDef = TypedDict(
+    "StartICD10CMInferenceJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartPHIDetectionJobResponseTypeDef = TypedDict(
+    "StartPHIDetectionJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartRxNormInferenceJobResponseTypeDef = TypedDict(
+    "StartRxNormInferenceJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartSNOMEDCTInferenceJobResponseTypeDef = TypedDict(
+    "StartSNOMEDCTInferenceJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopEntitiesDetectionV2JobRequestRequestTypeDef = TypedDict(
     "StopEntitiesDetectionV2JobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+StopEntitiesDetectionV2JobResponseTypeDef = TypedDict(
+    "StopEntitiesDetectionV2JobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopICD10CMInferenceJobRequestRequestTypeDef = TypedDict(
     "StopICD10CMInferenceJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+StopICD10CMInferenceJobResponseTypeDef = TypedDict(
+    "StopICD10CMInferenceJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopPHIDetectionJobRequestRequestTypeDef = TypedDict(
     "StopPHIDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+StopPHIDetectionJobResponseTypeDef = TypedDict(
+    "StopPHIDetectionJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopRxNormInferenceJobRequestRequestTypeDef = TypedDict(
     "StopRxNormInferenceJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+StopRxNormInferenceJobResponseTypeDef = TypedDict(
+    "StopRxNormInferenceJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopSNOMEDCTInferenceJobRequestRequestTypeDef = TypedDict(
     "StopSNOMEDCTInferenceJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+StopSNOMEDCTInferenceJobResponseTypeDef = TypedDict(
+    "StopSNOMEDCTInferenceJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AttributeTypeDef = TypedDict(
     "AttributeTypeDef",
     {
         "Type": EntitySubTypeType,
         "Score": float,
         "RelationshipScore": float,
         "RelationshipType": RelationshipTypeType,
@@ -597,94 +678,14 @@
 class StartSNOMEDCTInferenceJobRequestRequestTypeDef(
     _RequiredStartSNOMEDCTInferenceJobRequestRequestTypeDef,
     _OptionalStartSNOMEDCTInferenceJobRequestRequestTypeDef,
 ):
     pass
 
 
-StartEntitiesDetectionV2JobResponseTypeDef = TypedDict(
-    "StartEntitiesDetectionV2JobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartICD10CMInferenceJobResponseTypeDef = TypedDict(
-    "StartICD10CMInferenceJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartPHIDetectionJobResponseTypeDef = TypedDict(
-    "StartPHIDetectionJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartRxNormInferenceJobResponseTypeDef = TypedDict(
-    "StartRxNormInferenceJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartSNOMEDCTInferenceJobResponseTypeDef = TypedDict(
-    "StartSNOMEDCTInferenceJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopEntitiesDetectionV2JobResponseTypeDef = TypedDict(
-    "StopEntitiesDetectionV2JobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopICD10CMInferenceJobResponseTypeDef = TypedDict(
-    "StopICD10CMInferenceJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopPHIDetectionJobResponseTypeDef = TypedDict(
-    "StopPHIDetectionJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopRxNormInferenceJobResponseTypeDef = TypedDict(
-    "StopRxNormInferenceJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopSNOMEDCTInferenceJobResponseTypeDef = TypedDict(
-    "StopSNOMEDCTInferenceJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ICD10CMAttributeTypeDef = TypedDict(
     "ICD10CMAttributeTypeDef",
     {
         "Type": ICD10CMAttributeTypeType,
         "Score": float,
         "RelationshipScore": float,
         "Id": int,
@@ -756,92 +757,92 @@
     total=False,
 )
 
 DescribeEntitiesDetectionV2JobResponseTypeDef = TypedDict(
     "DescribeEntitiesDetectionV2JobResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobProperties": ComprehendMedicalAsyncJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeICD10CMInferenceJobResponseTypeDef = TypedDict(
     "DescribeICD10CMInferenceJobResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobProperties": ComprehendMedicalAsyncJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePHIDetectionJobResponseTypeDef = TypedDict(
     "DescribePHIDetectionJobResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobProperties": ComprehendMedicalAsyncJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRxNormInferenceJobResponseTypeDef = TypedDict(
     "DescribeRxNormInferenceJobResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobProperties": ComprehendMedicalAsyncJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSNOMEDCTInferenceJobResponseTypeDef = TypedDict(
     "DescribeSNOMEDCTInferenceJobResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobProperties": ComprehendMedicalAsyncJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEntitiesDetectionV2JobsResponseTypeDef = TypedDict(
     "ListEntitiesDetectionV2JobsResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobPropertiesList": List[ComprehendMedicalAsyncJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListICD10CMInferenceJobsResponseTypeDef = TypedDict(
     "ListICD10CMInferenceJobsResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobPropertiesList": List[ComprehendMedicalAsyncJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPHIDetectionJobsResponseTypeDef = TypedDict(
     "ListPHIDetectionJobsResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobPropertiesList": List[ComprehendMedicalAsyncJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRxNormInferenceJobsResponseTypeDef = TypedDict(
     "ListRxNormInferenceJobsResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobPropertiesList": List[ComprehendMedicalAsyncJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSNOMEDCTInferenceJobsResponseTypeDef = TypedDict(
     "ListSNOMEDCTInferenceJobsResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobPropertiesList": List[ComprehendMedicalAsyncJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ICD10CMEntityTypeDef = TypedDict(
     "ICD10CMEntityTypeDef",
     {
         "Id": int,
@@ -894,64 +895,64 @@
 
 DetectPHIResponseTypeDef = TypedDict(
     "DetectPHIResponseTypeDef",
     {
         "Entities": List[EntityTypeDef],
         "PaginationToken": str,
         "ModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectEntitiesResponseTypeDef = TypedDict(
     "DetectEntitiesResponseTypeDef",
     {
         "Entities": List[EntityTypeDef],
         "UnmappedAttributes": List[UnmappedAttributeTypeDef],
         "PaginationToken": str,
         "ModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectEntitiesV2ResponseTypeDef = TypedDict(
     "DetectEntitiesV2ResponseTypeDef",
     {
         "Entities": List[EntityTypeDef],
         "UnmappedAttributes": List[UnmappedAttributeTypeDef],
         "PaginationToken": str,
         "ModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InferICD10CMResponseTypeDef = TypedDict(
     "InferICD10CMResponseTypeDef",
     {
         "Entities": List[ICD10CMEntityTypeDef],
         "PaginationToken": str,
         "ModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InferRxNormResponseTypeDef = TypedDict(
     "InferRxNormResponseTypeDef",
     {
         "Entities": List[RxNormEntityTypeDef],
         "PaginationToken": str,
         "ModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InferSNOMEDCTResponseTypeDef = TypedDict(
     "InferSNOMEDCTResponseTypeDef",
     {
         "Entities": List[SNOMEDCTEntityTypeDef],
         "PaginationToken": str,
         "ModelVersion": str,
         "SNOMEDCTDetails": SNOMEDCTDetailsTypeDef,
         "Characters": CharactersTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical/type_defs.pyi` & `types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -23,14 +23,15 @@
     ICD10CMEntityTypeType,
     ICD10CMRelationshipTypeType,
     ICD10CMTraitNameType,
     JobStatusType,
     RelationshipTypeType,
     RxNormAttributeTypeType,
     RxNormEntityTypeType,
+    RxNormTraitNameType,
     SNOMEDCTAttributeTypeType,
     SNOMEDCTEntityCategoryType,
     SNOMEDCTEntityTypeType,
     SNOMEDCTRelationshipTypeType,
     SNOMEDCTTraitNameType,
 )
 
@@ -46,59 +47,59 @@
 __all__ = (
     "TraitTypeDef",
     "CharactersTypeDef",
     "ComprehendMedicalAsyncJobFilterTypeDef",
     "InputDataConfigTypeDef",
     "OutputDataConfigTypeDef",
     "DescribeEntitiesDetectionV2JobRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "DescribeICD10CMInferenceJobRequestRequestTypeDef",
     "DescribePHIDetectionJobRequestRequestTypeDef",
     "DescribeRxNormInferenceJobRequestRequestTypeDef",
     "DescribeSNOMEDCTInferenceJobRequestRequestTypeDef",
     "DetectEntitiesRequestRequestTypeDef",
     "DetectEntitiesV2RequestRequestTypeDef",
     "DetectPHIRequestRequestTypeDef",
     "ICD10CMTraitTypeDef",
     "ICD10CMConceptTypeDef",
     "InferICD10CMRequestRequestTypeDef",
     "InferRxNormRequestRequestTypeDef",
     "InferSNOMEDCTRequestRequestTypeDef",
     "SNOMEDCTDetailsTypeDef",
+    "ResponseMetadataTypeDef",
     "RxNormTraitTypeDef",
     "RxNormConceptTypeDef",
     "SNOMEDCTConceptTypeDef",
     "SNOMEDCTTraitTypeDef",
+    "StartEntitiesDetectionV2JobResponseTypeDef",
+    "StartICD10CMInferenceJobResponseTypeDef",
+    "StartPHIDetectionJobResponseTypeDef",
+    "StartRxNormInferenceJobResponseTypeDef",
+    "StartSNOMEDCTInferenceJobResponseTypeDef",
     "StopEntitiesDetectionV2JobRequestRequestTypeDef",
+    "StopEntitiesDetectionV2JobResponseTypeDef",
     "StopICD10CMInferenceJobRequestRequestTypeDef",
+    "StopICD10CMInferenceJobResponseTypeDef",
     "StopPHIDetectionJobRequestRequestTypeDef",
+    "StopPHIDetectionJobResponseTypeDef",
     "StopRxNormInferenceJobRequestRequestTypeDef",
+    "StopRxNormInferenceJobResponseTypeDef",
     "StopSNOMEDCTInferenceJobRequestRequestTypeDef",
+    "StopSNOMEDCTInferenceJobResponseTypeDef",
     "AttributeTypeDef",
     "ListEntitiesDetectionV2JobsRequestRequestTypeDef",
     "ListICD10CMInferenceJobsRequestRequestTypeDef",
     "ListPHIDetectionJobsRequestRequestTypeDef",
     "ListRxNormInferenceJobsRequestRequestTypeDef",
     "ListSNOMEDCTInferenceJobsRequestRequestTypeDef",
     "ComprehendMedicalAsyncJobPropertiesTypeDef",
     "StartEntitiesDetectionV2JobRequestRequestTypeDef",
     "StartICD10CMInferenceJobRequestRequestTypeDef",
     "StartPHIDetectionJobRequestRequestTypeDef",
     "StartRxNormInferenceJobRequestRequestTypeDef",
     "StartSNOMEDCTInferenceJobRequestRequestTypeDef",
-    "StartEntitiesDetectionV2JobResponseTypeDef",
-    "StartICD10CMInferenceJobResponseTypeDef",
-    "StartPHIDetectionJobResponseTypeDef",
-    "StartRxNormInferenceJobResponseTypeDef",
-    "StartSNOMEDCTInferenceJobResponseTypeDef",
-    "StopEntitiesDetectionV2JobResponseTypeDef",
-    "StopICD10CMInferenceJobResponseTypeDef",
-    "StopPHIDetectionJobResponseTypeDef",
-    "StopRxNormInferenceJobResponseTypeDef",
-    "StopSNOMEDCTInferenceJobResponseTypeDef",
     "ICD10CMAttributeTypeDef",
     "RxNormAttributeTypeDef",
     "SNOMEDCTAttributeTypeDef",
     "EntityTypeDef",
     "UnmappedAttributeTypeDef",
     "DescribeEntitiesDetectionV2JobResponseTypeDef",
     "DescribeICD10CMInferenceJobResponseTypeDef",
@@ -186,25 +187,14 @@
 DescribeEntitiesDetectionV2JobRequestRequestTypeDef = TypedDict(
     "DescribeEntitiesDetectionV2JobRequestRequestTypeDef",
     {
         "JobId": str,
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
 DescribeICD10CMInferenceJobRequestRequestTypeDef = TypedDict(
     "DescribeICD10CMInferenceJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
@@ -296,18 +286,29 @@
         "Edition": str,
         "Language": str,
         "VersionDate": str,
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
 RxNormTraitTypeDef = TypedDict(
     "RxNormTraitTypeDef",
     {
-        "Name": Literal["NEGATION"],
+        "Name": RxNormTraitNameType,
         "Score": float,
     },
     total=False,
 )
 
 RxNormConceptTypeDef = TypedDict(
     "RxNormConceptTypeDef",
@@ -334,49 +335,129 @@
     {
         "Name": SNOMEDCTTraitNameType,
         "Score": float,
     },
     total=False,
 )
 
+StartEntitiesDetectionV2JobResponseTypeDef = TypedDict(
+    "StartEntitiesDetectionV2JobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartICD10CMInferenceJobResponseTypeDef = TypedDict(
+    "StartICD10CMInferenceJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartPHIDetectionJobResponseTypeDef = TypedDict(
+    "StartPHIDetectionJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartRxNormInferenceJobResponseTypeDef = TypedDict(
+    "StartRxNormInferenceJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartSNOMEDCTInferenceJobResponseTypeDef = TypedDict(
+    "StartSNOMEDCTInferenceJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopEntitiesDetectionV2JobRequestRequestTypeDef = TypedDict(
     "StopEntitiesDetectionV2JobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+StopEntitiesDetectionV2JobResponseTypeDef = TypedDict(
+    "StopEntitiesDetectionV2JobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopICD10CMInferenceJobRequestRequestTypeDef = TypedDict(
     "StopICD10CMInferenceJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+StopICD10CMInferenceJobResponseTypeDef = TypedDict(
+    "StopICD10CMInferenceJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopPHIDetectionJobRequestRequestTypeDef = TypedDict(
     "StopPHIDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+StopPHIDetectionJobResponseTypeDef = TypedDict(
+    "StopPHIDetectionJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopRxNormInferenceJobRequestRequestTypeDef = TypedDict(
     "StopRxNormInferenceJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+StopRxNormInferenceJobResponseTypeDef = TypedDict(
+    "StopRxNormInferenceJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopSNOMEDCTInferenceJobRequestRequestTypeDef = TypedDict(
     "StopSNOMEDCTInferenceJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+StopSNOMEDCTInferenceJobResponseTypeDef = TypedDict(
+    "StopSNOMEDCTInferenceJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AttributeTypeDef = TypedDict(
     "AttributeTypeDef",
     {
         "Type": EntitySubTypeType,
         "Score": float,
         "RelationshipScore": float,
         "RelationshipType": RelationshipTypeType,
@@ -582,94 +663,14 @@
 
 class StartSNOMEDCTInferenceJobRequestRequestTypeDef(
     _RequiredStartSNOMEDCTInferenceJobRequestRequestTypeDef,
     _OptionalStartSNOMEDCTInferenceJobRequestRequestTypeDef,
 ):
     pass
 
-StartEntitiesDetectionV2JobResponseTypeDef = TypedDict(
-    "StartEntitiesDetectionV2JobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartICD10CMInferenceJobResponseTypeDef = TypedDict(
-    "StartICD10CMInferenceJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartPHIDetectionJobResponseTypeDef = TypedDict(
-    "StartPHIDetectionJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartRxNormInferenceJobResponseTypeDef = TypedDict(
-    "StartRxNormInferenceJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartSNOMEDCTInferenceJobResponseTypeDef = TypedDict(
-    "StartSNOMEDCTInferenceJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopEntitiesDetectionV2JobResponseTypeDef = TypedDict(
-    "StopEntitiesDetectionV2JobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopICD10CMInferenceJobResponseTypeDef = TypedDict(
-    "StopICD10CMInferenceJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopPHIDetectionJobResponseTypeDef = TypedDict(
-    "StopPHIDetectionJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopRxNormInferenceJobResponseTypeDef = TypedDict(
-    "StopRxNormInferenceJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopSNOMEDCTInferenceJobResponseTypeDef = TypedDict(
-    "StopSNOMEDCTInferenceJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ICD10CMAttributeTypeDef = TypedDict(
     "ICD10CMAttributeTypeDef",
     {
         "Type": ICD10CMAttributeTypeType,
         "Score": float,
         "RelationshipScore": float,
         "Id": int,
@@ -741,92 +742,92 @@
     total=False,
 )
 
 DescribeEntitiesDetectionV2JobResponseTypeDef = TypedDict(
     "DescribeEntitiesDetectionV2JobResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobProperties": ComprehendMedicalAsyncJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeICD10CMInferenceJobResponseTypeDef = TypedDict(
     "DescribeICD10CMInferenceJobResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobProperties": ComprehendMedicalAsyncJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePHIDetectionJobResponseTypeDef = TypedDict(
     "DescribePHIDetectionJobResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobProperties": ComprehendMedicalAsyncJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRxNormInferenceJobResponseTypeDef = TypedDict(
     "DescribeRxNormInferenceJobResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobProperties": ComprehendMedicalAsyncJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSNOMEDCTInferenceJobResponseTypeDef = TypedDict(
     "DescribeSNOMEDCTInferenceJobResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobProperties": ComprehendMedicalAsyncJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEntitiesDetectionV2JobsResponseTypeDef = TypedDict(
     "ListEntitiesDetectionV2JobsResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobPropertiesList": List[ComprehendMedicalAsyncJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListICD10CMInferenceJobsResponseTypeDef = TypedDict(
     "ListICD10CMInferenceJobsResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobPropertiesList": List[ComprehendMedicalAsyncJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPHIDetectionJobsResponseTypeDef = TypedDict(
     "ListPHIDetectionJobsResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobPropertiesList": List[ComprehendMedicalAsyncJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRxNormInferenceJobsResponseTypeDef = TypedDict(
     "ListRxNormInferenceJobsResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobPropertiesList": List[ComprehendMedicalAsyncJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSNOMEDCTInferenceJobsResponseTypeDef = TypedDict(
     "ListSNOMEDCTInferenceJobsResponseTypeDef",
     {
         "ComprehendMedicalAsyncJobPropertiesList": List[ComprehendMedicalAsyncJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ICD10CMEntityTypeDef = TypedDict(
     "ICD10CMEntityTypeDef",
     {
         "Id": int,
@@ -879,64 +880,64 @@
 
 DetectPHIResponseTypeDef = TypedDict(
     "DetectPHIResponseTypeDef",
     {
         "Entities": List[EntityTypeDef],
         "PaginationToken": str,
         "ModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectEntitiesResponseTypeDef = TypedDict(
     "DetectEntitiesResponseTypeDef",
     {
         "Entities": List[EntityTypeDef],
         "UnmappedAttributes": List[UnmappedAttributeTypeDef],
         "PaginationToken": str,
         "ModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectEntitiesV2ResponseTypeDef = TypedDict(
     "DetectEntitiesV2ResponseTypeDef",
     {
         "Entities": List[EntityTypeDef],
         "UnmappedAttributes": List[UnmappedAttributeTypeDef],
         "PaginationToken": str,
         "ModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InferICD10CMResponseTypeDef = TypedDict(
     "InferICD10CMResponseTypeDef",
     {
         "Entities": List[ICD10CMEntityTypeDef],
         "PaginationToken": str,
         "ModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InferRxNormResponseTypeDef = TypedDict(
     "InferRxNormResponseTypeDef",
     {
         "Entities": List[RxNormEntityTypeDef],
         "PaginationToken": str,
         "ModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InferSNOMEDCTResponseTypeDef = TypedDict(
     "InferSNOMEDCTResponseTypeDef",
     {
         "Entities": List[SNOMEDCTEntityTypeDef],
         "PaginationToken": str,
         "ModelVersion": str,
         "SNOMEDCTDetails": SNOMEDCTDetailsTypeDef,
         "Characters": CharactersTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical.egg-info/PKG-INFO` & `types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-comprehendmedical
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ComprehendMedical 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ComprehendMedical 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehendmedical/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-comprehendmedical"></a>
 
 # types-aiobotocore-comprehendmedical
 
 [![PyPI - types-aiobotocore-comprehendmedical](https://img.shields.io/pypi/v/types-aiobotocore-comprehendmedical.svg?color=blue)](https://pypi.org/project/types-aiobotocore-comprehendmedical)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-comprehendmedical.svg?color=blue)](https://pypi.org/project/types-aiobotocore-comprehendmedical)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehendmedical/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-comprehendmedical?color=blue)](https://pypistats.org/packages/types-aiobotocore-comprehendmedical)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ComprehendMedical 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehendmedical.html#ComprehendMedical)
+[aiobotocore.ComprehendMedical 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehendmedical.html#ComprehendMedical)
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
 [types-aiobotocore-comprehendmedical docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehendmedical/).
 
 See how it helps to find and fix potential bugs:
 
@@ -315,59 +315,59 @@
 from types_aiobotocore_comprehendmedical.type_defs import (
     TraitTypeDef,
     CharactersTypeDef,
     ComprehendMedicalAsyncJobFilterTypeDef,
     InputDataConfigTypeDef,
     OutputDataConfigTypeDef,
     DescribeEntitiesDetectionV2JobRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     DescribeICD10CMInferenceJobRequestRequestTypeDef,
     DescribePHIDetectionJobRequestRequestTypeDef,
     DescribeRxNormInferenceJobRequestRequestTypeDef,
     DescribeSNOMEDCTInferenceJobRequestRequestTypeDef,
     DetectEntitiesRequestRequestTypeDef,
     DetectEntitiesV2RequestRequestTypeDef,
     DetectPHIRequestRequestTypeDef,
     ICD10CMTraitTypeDef,
     ICD10CMConceptTypeDef,
     InferICD10CMRequestRequestTypeDef,
     InferRxNormRequestRequestTypeDef,
     InferSNOMEDCTRequestRequestTypeDef,
     SNOMEDCTDetailsTypeDef,
+    ResponseMetadataTypeDef,
     RxNormTraitTypeDef,
     RxNormConceptTypeDef,
     SNOMEDCTConceptTypeDef,
     SNOMEDCTTraitTypeDef,
+    StartEntitiesDetectionV2JobResponseTypeDef,
+    StartICD10CMInferenceJobResponseTypeDef,
+    StartPHIDetectionJobResponseTypeDef,
+    StartRxNormInferenceJobResponseTypeDef,
+    StartSNOMEDCTInferenceJobResponseTypeDef,
     StopEntitiesDetectionV2JobRequestRequestTypeDef,
+    StopEntitiesDetectionV2JobResponseTypeDef,
     StopICD10CMInferenceJobRequestRequestTypeDef,
+    StopICD10CMInferenceJobResponseTypeDef,
     StopPHIDetectionJobRequestRequestTypeDef,
+    StopPHIDetectionJobResponseTypeDef,
     StopRxNormInferenceJobRequestRequestTypeDef,
+    StopRxNormInferenceJobResponseTypeDef,
     StopSNOMEDCTInferenceJobRequestRequestTypeDef,
+    StopSNOMEDCTInferenceJobResponseTypeDef,
     AttributeTypeDef,
     ListEntitiesDetectionV2JobsRequestRequestTypeDef,
     ListICD10CMInferenceJobsRequestRequestTypeDef,
     ListPHIDetectionJobsRequestRequestTypeDef,
     ListRxNormInferenceJobsRequestRequestTypeDef,
     ListSNOMEDCTInferenceJobsRequestRequestTypeDef,
     ComprehendMedicalAsyncJobPropertiesTypeDef,
     StartEntitiesDetectionV2JobRequestRequestTypeDef,
     StartICD10CMInferenceJobRequestRequestTypeDef,
     StartPHIDetectionJobRequestRequestTypeDef,
     StartRxNormInferenceJobRequestRequestTypeDef,
     StartSNOMEDCTInferenceJobRequestRequestTypeDef,
-    StartEntitiesDetectionV2JobResponseTypeDef,
-    StartICD10CMInferenceJobResponseTypeDef,
-    StartPHIDetectionJobResponseTypeDef,
-    StartRxNormInferenceJobResponseTypeDef,
-    StartSNOMEDCTInferenceJobResponseTypeDef,
-    StopEntitiesDetectionV2JobResponseTypeDef,
-    StopICD10CMInferenceJobResponseTypeDef,
-    StopPHIDetectionJobResponseTypeDef,
-    StopRxNormInferenceJobResponseTypeDef,
-    StopSNOMEDCTInferenceJobResponseTypeDef,
     ICD10CMAttributeTypeDef,
     RxNormAttributeTypeDef,
     SNOMEDCTAttributeTypeDef,
     EntityTypeDef,
     UnmappedAttributeTypeDef,
     DescribeEntitiesDetectionV2JobResponseTypeDef,
     DescribeICD10CMInferenceJobResponseTypeDef,
@@ -398,43 +398,43 @@
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

### Comparing `types-aiobotocore-comprehendmedical-2.5.0.post1/types_aiobotocore_comprehendmedical.egg-info/SOURCES.txt` & `types-aiobotocore-comprehendmedical-2.5.1/types_aiobotocore_comprehendmedical.egg-info/SOURCES.txt`

 * *Files identical despite different names*


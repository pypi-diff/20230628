# Comparing `tmp/types-aiobotocore-amplifyuibuilder-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-amplifyuibuilder-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-amplifyuibuilder-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:10 2023, max compression
+gzip compressed data, was "types-aiobotocore-amplifyuibuilder-2.5.1.tar", last modified: Wed Jun 28 01:43:04 2023, max compression
```

## Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1.tar` & `types-aiobotocore-amplifyuibuilder-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.430925 types-aiobotocore-amplifyuibuilder-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:17.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17385 2023-03-11 12:26:10.426925 types-aiobotocore-amplifyuibuilder-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15778 2023-03-11 12:09:17.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:10.430925 types-aiobotocore-amplifyuibuilder-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2187 2023-03-11 12:09:17.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.418924 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/
--rw-r--r--   0 runner    (1001) docker     (123)     1621 2023-03-11 12:09:17.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1620 2023-03-11 12:09:17.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      979 2023-03-11 12:09:17.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21240 2023-03-11 12:09:18.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    21203 2023-03-11 12:09:18.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8902 2023-03-11 12:09:18.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8900 2023-03-11 12:09:18.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7855 2023-03-11 12:09:18.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7846 2023-03-11 12:09:18.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:17.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    36010 2023-03-11 12:09:19.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    35946 2023-03-11 12:09:19.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:17.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.426925 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17385 2023-03-11 12:26:10.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      984 2023-03-11 12:26:10.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:10.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:10.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:10.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:26:10.000000 types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.326090 types-aiobotocore-amplifyuibuilder-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:25:54.000000 types-aiobotocore-amplifyuibuilder-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18732 2023-06-28 01:43:04.326090 types-aiobotocore-amplifyuibuilder-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17131 2023-06-28 01:25:54.000000 types-aiobotocore-amplifyuibuilder-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:04.326090 types-aiobotocore-amplifyuibuilder-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2181 2023-06-28 01:25:54.000000 types-aiobotocore-amplifyuibuilder-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.318090 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/
+-rw-r--r--   0 runner    (1001) docker     (123)     1819 2023-06-28 01:25:54.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1818 2023-06-28 01:25:54.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      967 2023-06-28 01:25:54.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23816 2023-06-28 01:25:54.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23775 2023-06-28 01:25:54.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10288 2023-06-28 01:25:55.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10286 2023-06-28 01:25:55.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8909 2023-06-28 01:25:55.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8900 2023-06-28 01:25:54.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:25:54.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    48035 2023-06-28 01:25:56.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    47943 2023-06-28 01:25:56.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:25:54.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.326090 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18732 2023-06-28 01:43:04.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      984 2023-06-28 01:43:04.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:04.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:04.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:04.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:43:04.000000 types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/LICENSE` & `types-aiobotocore-amplifyuibuilder-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/PKG-INFO` & `types-aiobotocore-amplifyuibuilder-2.5.1/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-amplifyuibuilder
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AmplifyUIBuilder 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AmplifyUIBuilder 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-amplifyuibuilder"></a>
 
 # types-aiobotocore-amplifyuibuilder
 
 [![PyPI - types-aiobotocore-amplifyuibuilder](https://img.shields.io/pypi/v/types-aiobotocore-amplifyuibuilder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-amplifyuibuilder)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-amplifyuibuilder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-amplifyuibuilder)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-amplifyuibuilder?color=blue)](https://pypistats.org/packages/types-aiobotocore-amplifyuibuilder)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AmplifyUIBuilder 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder)
+[aiobotocore.AmplifyUIBuilder 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder)
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
 [types-aiobotocore-amplifyuibuilder docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/).
 
 See how it helps to find and fix potential bugs:
 
@@ -276,14 +276,15 @@
 from aiobotocore.session import get_session
 
 from types_aiobotocore_amplifyuibuilder import AmplifyUIBuilderClient
 from types_aiobotocore_amplifyuibuilder.paginator import (
     ExportComponentsPaginator,
     ExportFormsPaginator,
     ExportThemesPaginator,
+    ListCodegenJobsPaginator,
     ListComponentsPaginator,
     ListFormsPaginator,
     ListThemesPaginator,
 )
 
 session = get_session()
 async with session.create_client("amplifyuibuilder") as client:
@@ -292,197 +293,234 @@
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     export_components_paginator: ExportComponentsPaginator = client.get_paginator(
         "export_components"
     )
     export_forms_paginator: ExportFormsPaginator = client.get_paginator("export_forms")
     export_themes_paginator: ExportThemesPaginator = client.get_paginator("export_themes")
+    list_codegen_jobs_paginator: ListCodegenJobsPaginator = client.get_paginator(
+        "list_codegen_jobs"
+    )
     list_components_paginator: ListComponentsPaginator = client.get_paginator("list_components")
     list_forms_paginator: ListFormsPaginator = client.get_paginator("list_forms")
     list_themes_paginator: ListThemesPaginator = client.get_paginator("list_themes")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_amplifyuibuilder.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_amplifyuibuilder.literals import (
+    CodegenGenericDataFieldDataTypeType,
+    CodegenJobGenericDataSourceTypeType,
+    CodegenJobStatusType,
     ExportComponentsPaginatorName,
     ExportFormsPaginatorName,
     ExportThemesPaginatorName,
     FixedPositionType,
     FormActionTypeType,
     FormButtonsPositionType,
     FormDataSourceTypeType,
+    GenericDataRelationshipTypeType,
+    JSModuleType,
+    JSScriptType,
+    JSTargetType,
+    LabelDecoratorType,
+    ListCodegenJobsPaginatorName,
     ListComponentsPaginatorName,
     ListFormsPaginatorName,
     ListThemesPaginatorName,
     SortDirectionType,
+    StorageAccessLevelType,
     TokenProvidersType,
     AmplifyUIBuilderServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: ExportComponentsPaginatorName) -> bool:
+def check_value(value: CodegenGenericDataFieldDataTypeType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_amplifyuibuilder.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_amplifyuibuilder.type_defs import (
-    MutationActionSetStateParameterTypeDef,
+    ActionParametersTypeDef,
+    CodegenFeatureFlagsTypeDef,
+    CodegenGenericDataEnumTypeDef,
+    CodegenGenericDataFieldTypeDef,
+    CodegenGenericDataModelTypeDef,
+    CodegenGenericDataNonModelTypeDef,
+    CodegenGenericDataRelationshipTypeTypeDef,
+    CodegenJobAssetTypeDef,
+    CodegenJobGenericDataSchemaTypeDef,
+    CodegenJobRenderConfigTypeDef,
+    CodegenJobSummaryTypeDef,
+    CodegenJobTypeDef,
     ComponentBindingPropertiesValuePropertiesTypeDef,
+    ComponentBindingPropertiesValueTypeDef,
+    ComponentChildTypeDef,
     ComponentConditionPropertyTypeDef,
-    SortPropertyTypeDef,
+    ComponentDataConfigurationTypeDef,
+    ComponentEventTypeDef,
     ComponentPropertyBindingPropertiesTypeDef,
-    FormBindingElementTypeDef,
+    ComponentPropertyTypeDef,
     ComponentSummaryTypeDef,
+    ComponentTypeDef,
     ComponentVariantTypeDef,
-    ResponseMetadataTypeDef,
-    FormDataTypeConfigTypeDef,
+    CreateComponentDataTypeDef,
+    CreateComponentRequestRequestTypeDef,
+    CreateComponentResponseTypeDef,
+    CreateFormDataTypeDef,
+    CreateFormRequestRequestTypeDef,
+    CreateFormResponseTypeDef,
     CreateThemeDataTypeDef,
-    ThemeTypeDef,
+    CreateThemeRequestRequestTypeDef,
+    CreateThemeResponseTypeDef,
     DeleteComponentRequestRequestTypeDef,
     DeleteFormRequestRequestTypeDef,
     DeleteThemeRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExchangeCodeForTokenRequestBodyTypeDef,
-    PaginatorConfigTypeDef,
+    ExchangeCodeForTokenRequestRequestTypeDef,
+    ExchangeCodeForTokenResponseTypeDef,
+    ExportComponentsRequestExportComponentsPaginateTypeDef,
     ExportComponentsRequestRequestTypeDef,
+    ExportComponentsResponseTypeDef,
+    ExportFormsRequestExportFormsPaginateTypeDef,
     ExportFormsRequestRequestTypeDef,
+    ExportFormsResponseTypeDef,
+    ExportThemesRequestExportThemesPaginateTypeDef,
     ExportThemesRequestRequestTypeDef,
+    ExportThemesResponseTypeDef,
+    FieldConfigTypeDef,
+    FieldInputConfigTypeDef,
     FieldPositionTypeDef,
     FieldValidationConfigurationTypeDef,
+    FileUploaderFieldConfigTypeDef,
+    FormBindingElementTypeDef,
+    FormButtonTypeDef,
+    FormCTATypeDef,
+    FormDataTypeConfigTypeDef,
+    FormInputBindingPropertiesValuePropertiesTypeDef,
+    FormInputBindingPropertiesValueTypeDef,
+    FormInputValuePropertyBindingPropertiesTypeDef,
     FormInputValuePropertyTypeDef,
     FormStyleConfigTypeDef,
+    FormStyleTypeDef,
+    FormSummaryTypeDef,
+    FormTypeDef,
+    GetCodegenJobRequestRequestTypeDef,
+    GetCodegenJobResponseTypeDef,
     GetComponentRequestRequestTypeDef,
+    GetComponentResponseTypeDef,
     GetFormRequestRequestTypeDef,
+    GetFormResponseTypeDef,
     GetMetadataRequestRequestTypeDef,
+    GetMetadataResponseTypeDef,
     GetThemeRequestRequestTypeDef,
+    GetThemeResponseTypeDef,
+    ListCodegenJobsRequestListCodegenJobsPaginateTypeDef,
+    ListCodegenJobsRequestRequestTypeDef,
+    ListCodegenJobsResponseTypeDef,
+    ListComponentsRequestListComponentsPaginateTypeDef,
     ListComponentsRequestRequestTypeDef,
+    ListComponentsResponseTypeDef,
+    ListFormsRequestListFormsPaginateTypeDef,
     ListFormsRequestRequestTypeDef,
+    ListFormsResponseTypeDef,
+    ListThemesRequestListThemesPaginateTypeDef,
     ListThemesRequestRequestTypeDef,
-    ThemeSummaryTypeDef,
+    ListThemesResponseTypeDef,
+    MutationActionSetStateParameterTypeDef,
+    PaginatorConfigTypeDef,
     PredicateTypeDef,
     PutMetadataFlagBodyTypeDef,
+    PutMetadataFlagRequestRequestTypeDef,
+    ReactStartCodegenJobDataTypeDef,
     RefreshTokenRequestBodyTypeDef,
-    ThemeValueTypeDef,
-    ThemeValuesTypeDef,
-    UpdateThemeDataTypeDef,
-    ActionParametersTypeDef,
-    ComponentBindingPropertiesValueTypeDef,
-    ComponentDataConfigurationTypeDef,
-    ComponentPropertyTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExchangeCodeForTokenResponseTypeDef,
-    GetMetadataResponseTypeDef,
-    ListComponentsResponseTypeDef,
+    RefreshTokenRequestRequestTypeDef,
     RefreshTokenResponseTypeDef,
-    FormSummaryTypeDef,
-    CreateThemeRequestRequestTypeDef,
-    CreateThemeResponseTypeDef,
-    ExportThemesResponseTypeDef,
-    GetThemeResponseTypeDef,
-    UpdateThemeResponseTypeDef,
-    ExchangeCodeForTokenRequestRequestTypeDef,
-    ExportComponentsRequestExportComponentsPaginateTypeDef,
-    ExportFormsRequestExportFormsPaginateTypeDef,
-    ExportThemesRequestExportThemesPaginateTypeDef,
-    ListComponentsRequestListComponentsPaginateTypeDef,
-    ListFormsRequestListFormsPaginateTypeDef,
-    ListThemesRequestListThemesPaginateTypeDef,
-    FormButtonTypeDef,
+    ResponseMetadataTypeDef,
     SectionalElementTypeDef,
-    ValueMappingTypeDef,
-    FormStyleTypeDef,
-    ListThemesResponseTypeDef,
-    PutMetadataFlagRequestRequestTypeDef,
-    RefreshTokenRequestRequestTypeDef,
-    UpdateThemeRequestRequestTypeDef,
-    ComponentEventTypeDef,
-    ListFormsResponseTypeDef,
-    FormCTATypeDef,
-    ValueMappingsTypeDef,
-    ComponentChildTypeDef,
-    ComponentTypeDef,
-    CreateComponentDataTypeDef,
+    SortPropertyTypeDef,
+    StartCodegenJobDataTypeDef,
+    StartCodegenJobRequestRequestTypeDef,
+    StartCodegenJobResponseTypeDef,
+    ThemeSummaryTypeDef,
+    ThemeTypeDef,
+    ThemeValueTypeDef,
+    ThemeValuesTypeDef,
     UpdateComponentDataTypeDef,
-    FieldInputConfigTypeDef,
-    CreateComponentResponseTypeDef,
-    ExportComponentsResponseTypeDef,
-    GetComponentResponseTypeDef,
-    UpdateComponentResponseTypeDef,
-    CreateComponentRequestRequestTypeDef,
     UpdateComponentRequestRequestTypeDef,
-    FieldConfigTypeDef,
-    CreateFormDataTypeDef,
-    FormTypeDef,
+    UpdateComponentResponseTypeDef,
     UpdateFormDataTypeDef,
-    CreateFormRequestRequestTypeDef,
-    CreateFormResponseTypeDef,
-    ExportFormsResponseTypeDef,
-    GetFormResponseTypeDef,
-    UpdateFormResponseTypeDef,
     UpdateFormRequestRequestTypeDef,
+    UpdateFormResponseTypeDef,
+    UpdateThemeDataTypeDef,
+    UpdateThemeRequestRequestTypeDef,
+    UpdateThemeResponseTypeDef,
+    ValueMappingTypeDef,
+    ValueMappingsTypeDef,
 )
 
 
-def get_structure() -> MutationActionSetStateParameterTypeDef:
+def get_structure() -> ActionParametersTypeDef:
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

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/README.md` & `types-aiobotocore-amplifyuibuilder-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-amplifyuibuilder"></a>
 
 # types-aiobotocore-amplifyuibuilder
 
 [![PyPI - types-aiobotocore-amplifyuibuilder](https://img.shields.io/pypi/v/types-aiobotocore-amplifyuibuilder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-amplifyuibuilder)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-amplifyuibuilder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-amplifyuibuilder)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-amplifyuibuilder?color=blue)](https://pypistats.org/packages/types-aiobotocore-amplifyuibuilder)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AmplifyUIBuilder 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder)
+[aiobotocore.AmplifyUIBuilder 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder)
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
 [types-aiobotocore-amplifyuibuilder docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/).
 
 See how it helps to find and fix potential bugs:
 
@@ -243,14 +243,15 @@
 from aiobotocore.session import get_session
 
 from types_aiobotocore_amplifyuibuilder import AmplifyUIBuilderClient
 from types_aiobotocore_amplifyuibuilder.paginator import (
     ExportComponentsPaginator,
     ExportFormsPaginator,
     ExportThemesPaginator,
+    ListCodegenJobsPaginator,
     ListComponentsPaginator,
     ListFormsPaginator,
     ListThemesPaginator,
 )
 
 session = get_session()
 async with session.create_client("amplifyuibuilder") as client:
@@ -259,197 +260,234 @@
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     export_components_paginator: ExportComponentsPaginator = client.get_paginator(
         "export_components"
     )
     export_forms_paginator: ExportFormsPaginator = client.get_paginator("export_forms")
     export_themes_paginator: ExportThemesPaginator = client.get_paginator("export_themes")
+    list_codegen_jobs_paginator: ListCodegenJobsPaginator = client.get_paginator(
+        "list_codegen_jobs"
+    )
     list_components_paginator: ListComponentsPaginator = client.get_paginator("list_components")
     list_forms_paginator: ListFormsPaginator = client.get_paginator("list_forms")
     list_themes_paginator: ListThemesPaginator = client.get_paginator("list_themes")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_amplifyuibuilder.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_amplifyuibuilder.literals import (
+    CodegenGenericDataFieldDataTypeType,
+    CodegenJobGenericDataSourceTypeType,
+    CodegenJobStatusType,
     ExportComponentsPaginatorName,
     ExportFormsPaginatorName,
     ExportThemesPaginatorName,
     FixedPositionType,
     FormActionTypeType,
     FormButtonsPositionType,
     FormDataSourceTypeType,
+    GenericDataRelationshipTypeType,
+    JSModuleType,
+    JSScriptType,
+    JSTargetType,
+    LabelDecoratorType,
+    ListCodegenJobsPaginatorName,
     ListComponentsPaginatorName,
     ListFormsPaginatorName,
     ListThemesPaginatorName,
     SortDirectionType,
+    StorageAccessLevelType,
     TokenProvidersType,
     AmplifyUIBuilderServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: ExportComponentsPaginatorName) -> bool:
+def check_value(value: CodegenGenericDataFieldDataTypeType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_amplifyuibuilder.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_amplifyuibuilder.type_defs import (
-    MutationActionSetStateParameterTypeDef,
+    ActionParametersTypeDef,
+    CodegenFeatureFlagsTypeDef,
+    CodegenGenericDataEnumTypeDef,
+    CodegenGenericDataFieldTypeDef,
+    CodegenGenericDataModelTypeDef,
+    CodegenGenericDataNonModelTypeDef,
+    CodegenGenericDataRelationshipTypeTypeDef,
+    CodegenJobAssetTypeDef,
+    CodegenJobGenericDataSchemaTypeDef,
+    CodegenJobRenderConfigTypeDef,
+    CodegenJobSummaryTypeDef,
+    CodegenJobTypeDef,
     ComponentBindingPropertiesValuePropertiesTypeDef,
+    ComponentBindingPropertiesValueTypeDef,
+    ComponentChildTypeDef,
     ComponentConditionPropertyTypeDef,
-    SortPropertyTypeDef,
+    ComponentDataConfigurationTypeDef,
+    ComponentEventTypeDef,
     ComponentPropertyBindingPropertiesTypeDef,
-    FormBindingElementTypeDef,
+    ComponentPropertyTypeDef,
     ComponentSummaryTypeDef,
+    ComponentTypeDef,
     ComponentVariantTypeDef,
-    ResponseMetadataTypeDef,
-    FormDataTypeConfigTypeDef,
+    CreateComponentDataTypeDef,
+    CreateComponentRequestRequestTypeDef,
+    CreateComponentResponseTypeDef,
+    CreateFormDataTypeDef,
+    CreateFormRequestRequestTypeDef,
+    CreateFormResponseTypeDef,
     CreateThemeDataTypeDef,
-    ThemeTypeDef,
+    CreateThemeRequestRequestTypeDef,
+    CreateThemeResponseTypeDef,
     DeleteComponentRequestRequestTypeDef,
     DeleteFormRequestRequestTypeDef,
     DeleteThemeRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExchangeCodeForTokenRequestBodyTypeDef,
-    PaginatorConfigTypeDef,
+    ExchangeCodeForTokenRequestRequestTypeDef,
+    ExchangeCodeForTokenResponseTypeDef,
+    ExportComponentsRequestExportComponentsPaginateTypeDef,
     ExportComponentsRequestRequestTypeDef,
+    ExportComponentsResponseTypeDef,
+    ExportFormsRequestExportFormsPaginateTypeDef,
     ExportFormsRequestRequestTypeDef,
+    ExportFormsResponseTypeDef,
+    ExportThemesRequestExportThemesPaginateTypeDef,
     ExportThemesRequestRequestTypeDef,
+    ExportThemesResponseTypeDef,
+    FieldConfigTypeDef,
+    FieldInputConfigTypeDef,
     FieldPositionTypeDef,
     FieldValidationConfigurationTypeDef,
+    FileUploaderFieldConfigTypeDef,
+    FormBindingElementTypeDef,
+    FormButtonTypeDef,
+    FormCTATypeDef,
+    FormDataTypeConfigTypeDef,
+    FormInputBindingPropertiesValuePropertiesTypeDef,
+    FormInputBindingPropertiesValueTypeDef,
+    FormInputValuePropertyBindingPropertiesTypeDef,
     FormInputValuePropertyTypeDef,
     FormStyleConfigTypeDef,
+    FormStyleTypeDef,
+    FormSummaryTypeDef,
+    FormTypeDef,
+    GetCodegenJobRequestRequestTypeDef,
+    GetCodegenJobResponseTypeDef,
     GetComponentRequestRequestTypeDef,
+    GetComponentResponseTypeDef,
     GetFormRequestRequestTypeDef,
+    GetFormResponseTypeDef,
     GetMetadataRequestRequestTypeDef,
+    GetMetadataResponseTypeDef,
     GetThemeRequestRequestTypeDef,
+    GetThemeResponseTypeDef,
+    ListCodegenJobsRequestListCodegenJobsPaginateTypeDef,
+    ListCodegenJobsRequestRequestTypeDef,
+    ListCodegenJobsResponseTypeDef,
+    ListComponentsRequestListComponentsPaginateTypeDef,
     ListComponentsRequestRequestTypeDef,
+    ListComponentsResponseTypeDef,
+    ListFormsRequestListFormsPaginateTypeDef,
     ListFormsRequestRequestTypeDef,
+    ListFormsResponseTypeDef,
+    ListThemesRequestListThemesPaginateTypeDef,
     ListThemesRequestRequestTypeDef,
-    ThemeSummaryTypeDef,
+    ListThemesResponseTypeDef,
+    MutationActionSetStateParameterTypeDef,
+    PaginatorConfigTypeDef,
     PredicateTypeDef,
     PutMetadataFlagBodyTypeDef,
+    PutMetadataFlagRequestRequestTypeDef,
+    ReactStartCodegenJobDataTypeDef,
     RefreshTokenRequestBodyTypeDef,
-    ThemeValueTypeDef,
-    ThemeValuesTypeDef,
-    UpdateThemeDataTypeDef,
-    ActionParametersTypeDef,
-    ComponentBindingPropertiesValueTypeDef,
-    ComponentDataConfigurationTypeDef,
-    ComponentPropertyTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExchangeCodeForTokenResponseTypeDef,
-    GetMetadataResponseTypeDef,
-    ListComponentsResponseTypeDef,
+    RefreshTokenRequestRequestTypeDef,
     RefreshTokenResponseTypeDef,
-    FormSummaryTypeDef,
-    CreateThemeRequestRequestTypeDef,
-    CreateThemeResponseTypeDef,
-    ExportThemesResponseTypeDef,
-    GetThemeResponseTypeDef,
-    UpdateThemeResponseTypeDef,
-    ExchangeCodeForTokenRequestRequestTypeDef,
-    ExportComponentsRequestExportComponentsPaginateTypeDef,
-    ExportFormsRequestExportFormsPaginateTypeDef,
-    ExportThemesRequestExportThemesPaginateTypeDef,
-    ListComponentsRequestListComponentsPaginateTypeDef,
-    ListFormsRequestListFormsPaginateTypeDef,
-    ListThemesRequestListThemesPaginateTypeDef,
-    FormButtonTypeDef,
+    ResponseMetadataTypeDef,
     SectionalElementTypeDef,
-    ValueMappingTypeDef,
-    FormStyleTypeDef,
-    ListThemesResponseTypeDef,
-    PutMetadataFlagRequestRequestTypeDef,
-    RefreshTokenRequestRequestTypeDef,
-    UpdateThemeRequestRequestTypeDef,
-    ComponentEventTypeDef,
-    ListFormsResponseTypeDef,
-    FormCTATypeDef,
-    ValueMappingsTypeDef,
-    ComponentChildTypeDef,
-    ComponentTypeDef,
-    CreateComponentDataTypeDef,
+    SortPropertyTypeDef,
+    StartCodegenJobDataTypeDef,
+    StartCodegenJobRequestRequestTypeDef,
+    StartCodegenJobResponseTypeDef,
+    ThemeSummaryTypeDef,
+    ThemeTypeDef,
+    ThemeValueTypeDef,
+    ThemeValuesTypeDef,
     UpdateComponentDataTypeDef,
-    FieldInputConfigTypeDef,
-    CreateComponentResponseTypeDef,
-    ExportComponentsResponseTypeDef,
-    GetComponentResponseTypeDef,
-    UpdateComponentResponseTypeDef,
-    CreateComponentRequestRequestTypeDef,
     UpdateComponentRequestRequestTypeDef,
-    FieldConfigTypeDef,
-    CreateFormDataTypeDef,
-    FormTypeDef,
+    UpdateComponentResponseTypeDef,
     UpdateFormDataTypeDef,
-    CreateFormRequestRequestTypeDef,
-    CreateFormResponseTypeDef,
-    ExportFormsResponseTypeDef,
-    GetFormResponseTypeDef,
-    UpdateFormResponseTypeDef,
     UpdateFormRequestRequestTypeDef,
+    UpdateFormResponseTypeDef,
+    UpdateThemeDataTypeDef,
+    UpdateThemeRequestRequestTypeDef,
+    UpdateThemeResponseTypeDef,
+    ValueMappingTypeDef,
+    ValueMappingsTypeDef,
 )
 
 
-def get_structure() -> MutationActionSetStateParameterTypeDef:
+def get_structure() -> ActionParametersTypeDef:
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

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/setup.py` & `types-aiobotocore-amplifyuibuilder-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-amplifyuibuilder.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-amplifyuibuilder",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_amplifyuibuilder"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.AmplifyUIBuilder 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.AmplifyUIBuilder 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/"
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

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/__init__.py` & `types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/__init__.py`

 * *Files 12% similar despite different names*

```diff
@@ -7,49 +7,53 @@
     from aiobotocore.session import get_session
     from types_aiobotocore_amplifyuibuilder import (
         AmplifyUIBuilderClient,
         Client,
         ExportComponentsPaginator,
         ExportFormsPaginator,
         ExportThemesPaginator,
+        ListCodegenJobsPaginator,
         ListComponentsPaginator,
         ListFormsPaginator,
         ListThemesPaginator,
     )
 
     session = get_session()
     async with session.create_client("amplifyuibuilder") as client:
         client: AmplifyUIBuilderClient
         ...
 
 
     export_components_paginator: ExportComponentsPaginator = client.get_paginator("export_components")
     export_forms_paginator: ExportFormsPaginator = client.get_paginator("export_forms")
     export_themes_paginator: ExportThemesPaginator = client.get_paginator("export_themes")
+    list_codegen_jobs_paginator: ListCodegenJobsPaginator = client.get_paginator("list_codegen_jobs")
     list_components_paginator: ListComponentsPaginator = client.get_paginator("list_components")
     list_forms_paginator: ListFormsPaginator = client.get_paginator("list_forms")
     list_themes_paginator: ListThemesPaginator = client.get_paginator("list_themes")
     ```
 """
 from .client import AmplifyUIBuilderClient
 from .paginator import (
     ExportComponentsPaginator,
     ExportFormsPaginator,
     ExportThemesPaginator,
+    ListCodegenJobsPaginator,
     ListComponentsPaginator,
     ListFormsPaginator,
     ListThemesPaginator,
 )
 
 Client = AmplifyUIBuilderClient
 
 
 __all__ = (
     "AmplifyUIBuilderClient",
     "Client",
     "ExportComponentsPaginator",
     "ExportFormsPaginator",
     "ExportThemesPaginator",
+    "ListCodegenJobsPaginator",
     "ListComponentsPaginator",
     "ListFormsPaginator",
     "ListThemesPaginator",
 )
```

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/__init__.pyi` & `types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/__init__.pyi`

 * *Files 13% similar despite different names*

```diff
@@ -7,48 +7,52 @@
     from aiobotocore.session import get_session
     from types_aiobotocore_amplifyuibuilder import (
         AmplifyUIBuilderClient,
         Client,
         ExportComponentsPaginator,
         ExportFormsPaginator,
         ExportThemesPaginator,
+        ListCodegenJobsPaginator,
         ListComponentsPaginator,
         ListFormsPaginator,
         ListThemesPaginator,
     )
 
     session = get_session()
     async with session.create_client("amplifyuibuilder") as client:
         client: AmplifyUIBuilderClient
         ...
 
 
     export_components_paginator: ExportComponentsPaginator = client.get_paginator("export_components")
     export_forms_paginator: ExportFormsPaginator = client.get_paginator("export_forms")
     export_themes_paginator: ExportThemesPaginator = client.get_paginator("export_themes")
+    list_codegen_jobs_paginator: ListCodegenJobsPaginator = client.get_paginator("list_codegen_jobs")
     list_components_paginator: ListComponentsPaginator = client.get_paginator("list_components")
     list_forms_paginator: ListFormsPaginator = client.get_paginator("list_forms")
     list_themes_paginator: ListThemesPaginator = client.get_paginator("list_themes")
     ```
 """
 from .client import AmplifyUIBuilderClient
 from .paginator import (
     ExportComponentsPaginator,
     ExportFormsPaginator,
     ExportThemesPaginator,
+    ListCodegenJobsPaginator,
     ListComponentsPaginator,
     ListFormsPaginator,
     ListThemesPaginator,
 )
 
 Client = AmplifyUIBuilderClient
 
 __all__ = (
     "AmplifyUIBuilderClient",
     "Client",
     "ExportComponentsPaginator",
     "ExportFormsPaginator",
     "ExportThemesPaginator",
+    "ListCodegenJobsPaginator",
     "ListComponentsPaginator",
     "ListFormsPaginator",
     "ListThemesPaginator",
 )
```

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/__main__.py` & `types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.AmplifyUIBuilder 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.AmplifyUIBuilder 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder\nOther"
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

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/client.py` & `types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/client.py`

 * *Files 14% similar despite different names*

```diff
@@ -20,14 +20,15 @@
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .paginator import (
     ExportComponentsPaginator,
     ExportFormsPaginator,
     ExportThemesPaginator,
+    ListCodegenJobsPaginator,
     ListComponentsPaginator,
     ListFormsPaginator,
     ListThemesPaginator,
 )
 from .type_defs import (
     CreateComponentDataTypeDef,
     CreateComponentResponseTypeDef,
@@ -37,24 +38,28 @@
     CreateThemeResponseTypeDef,
     EmptyResponseMetadataTypeDef,
     ExchangeCodeForTokenRequestBodyTypeDef,
     ExchangeCodeForTokenResponseTypeDef,
     ExportComponentsResponseTypeDef,
     ExportFormsResponseTypeDef,
     ExportThemesResponseTypeDef,
+    GetCodegenJobResponseTypeDef,
     GetComponentResponseTypeDef,
     GetFormResponseTypeDef,
     GetMetadataResponseTypeDef,
     GetThemeResponseTypeDef,
+    ListCodegenJobsResponseTypeDef,
     ListComponentsResponseTypeDef,
     ListFormsResponseTypeDef,
     ListThemesResponseTypeDef,
     PutMetadataFlagBodyTypeDef,
     RefreshTokenRequestBodyTypeDef,
     RefreshTokenResponseTypeDef,
+    StartCodegenJobDataTypeDef,
+    StartCodegenJobResponseTypeDef,
     UpdateComponentDataTypeDef,
     UpdateComponentResponseTypeDef,
     UpdateFormDataTypeDef,
     UpdateFormResponseTypeDef,
     UpdateThemeDataTypeDef,
     UpdateThemeResponseTypeDef,
 )
@@ -79,14 +84,15 @@
 class Exceptions:
     ClientError: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     InvalidParameterException: Type[BotocoreClientError]
     ResourceConflictException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
+    ThrottlingException: Type[BotocoreClientError]
     UnauthorizedException: Type[BotocoreClientError]
 
 
 class AmplifyUIBuilderClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/)
@@ -119,46 +125,46 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#close)
         """
 
     async def create_component(
         self,
         *,
         appId: str,
-        componentToCreate: CreateComponentDataTypeDef,
         environmentName: str,
+        componentToCreate: "CreateComponentDataTypeDef",
         clientToken: str = ...
     ) -> CreateComponentResponseTypeDef:
         """
         Creates a new component for an Amplify app.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.create_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#create_component)
         """
 
     async def create_form(
         self,
         *,
         appId: str,
         environmentName: str,
-        formToCreate: CreateFormDataTypeDef,
+        formToCreate: "CreateFormDataTypeDef",
         clientToken: str = ...
     ) -> CreateFormResponseTypeDef:
         """
-        Creates a new form for an Amplify app.
+        Creates a new form for an Amplify.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.create_form)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#create_form)
         """
 
     async def create_theme(
         self,
         *,
         appId: str,
         environmentName: str,
-        themeToCreate: CreateThemeDataTypeDef,
+        themeToCreate: "CreateThemeDataTypeDef",
         clientToken: str = ...
     ) -> CreateThemeResponseTypeDef:
         """
         Creates a theme to apply to the components in an Amplify app.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.create_theme)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#create_theme)
@@ -191,15 +197,15 @@
         Deletes a theme from an Amplify app.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.delete_theme)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#delete_theme)
         """
 
     async def exchange_code_for_token(
-        self, *, provider: Literal["figma"], request: ExchangeCodeForTokenRequestBodyTypeDef
+        self, *, provider: Literal["figma"], request: "ExchangeCodeForTokenRequestBodyTypeDef"
     ) -> ExchangeCodeForTokenResponseTypeDef:
         """
         Exchanges an access code for a token.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.exchange_code_for_token)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#exchange_code_for_token)
         """
@@ -247,14 +253,24 @@
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#generate_presigned_url)
         """
 
+    async def get_codegen_job(
+        self, *, appId: str, environmentName: str, id: str
+    ) -> GetCodegenJobResponseTypeDef:
+        """
+        Returns an existing code generation job.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.get_codegen_job)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#get_codegen_job)
+        """
+
     async def get_component(
         self, *, appId: str, environmentName: str, id: str
     ) -> GetComponentResponseTypeDef:
         """
         Returns an existing component for an Amplify app.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.get_component)
@@ -285,77 +301,104 @@
         """
         Returns an existing theme for an Amplify app.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.get_theme)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#get_theme)
         """
 
+    async def list_codegen_jobs(
+        self, *, appId: str, environmentName: str, nextToken: str = ..., maxResults: int = ...
+    ) -> ListCodegenJobsResponseTypeDef:
+        """
+        Retrieves a list of code generation jobs for a specified Amplify app and backend
+        environment.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.list_codegen_jobs)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#list_codegen_jobs)
+        """
+
     async def list_components(
-        self, *, appId: str, environmentName: str, maxResults: int = ..., nextToken: str = ...
+        self, *, appId: str, environmentName: str, nextToken: str = ..., maxResults: int = ...
     ) -> ListComponentsResponseTypeDef:
         """
         Retrieves a list of components for a specified Amplify app and backend
         environment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.list_components)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#list_components)
         """
 
     async def list_forms(
-        self, *, appId: str, environmentName: str, maxResults: int = ..., nextToken: str = ...
+        self, *, appId: str, environmentName: str, nextToken: str = ..., maxResults: int = ...
     ) -> ListFormsResponseTypeDef:
         """
         Retrieves a list of forms for a specified Amplify app and backend environment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.list_forms)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#list_forms)
         """
 
     async def list_themes(
-        self, *, appId: str, environmentName: str, maxResults: int = ..., nextToken: str = ...
+        self, *, appId: str, environmentName: str, nextToken: str = ..., maxResults: int = ...
     ) -> ListThemesResponseTypeDef:
         """
         Retrieves a list of themes for a specified Amplify app and backend environment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.list_themes)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#list_themes)
         """
 
     async def put_metadata_flag(
         self,
         *,
         appId: str,
-        body: PutMetadataFlagBodyTypeDef,
         environmentName: str,
-        featureName: str
+        featureName: str,
+        body: "PutMetadataFlagBodyTypeDef"
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Stores the metadata information about a feature on a form or view.
+        Stores the metadata information about a feature on a form.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.put_metadata_flag)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#put_metadata_flag)
         """
 
     async def refresh_token(
-        self, *, provider: Literal["figma"], refreshTokenBody: RefreshTokenRequestBodyTypeDef
+        self, *, provider: Literal["figma"], refreshTokenBody: "RefreshTokenRequestBodyTypeDef"
     ) -> RefreshTokenResponseTypeDef:
         """
         Refreshes a previously issued access token that might have expired.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.refresh_token)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#refresh_token)
         """
 
+    async def start_codegen_job(
+        self,
+        *,
+        appId: str,
+        environmentName: str,
+        codegenJobToCreate: "StartCodegenJobDataTypeDef",
+        clientToken: str = ...
+    ) -> StartCodegenJobResponseTypeDef:
+        """
+        Starts a code generation job for for a specified Amplify app and backend
+        environment.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.start_codegen_job)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#start_codegen_job)
+        """
+
     async def update_component(
         self,
         *,
         appId: str,
         environmentName: str,
         id: str,
-        updatedComponent: UpdateComponentDataTypeDef,
+        updatedComponent: "UpdateComponentDataTypeDef",
         clientToken: str = ...
     ) -> UpdateComponentResponseTypeDef:
         """
         Updates an existing component.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.update_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#update_component)
@@ -363,15 +406,15 @@
 
     async def update_form(
         self,
         *,
         appId: str,
         environmentName: str,
         id: str,
-        updatedForm: UpdateFormDataTypeDef,
+        updatedForm: "UpdateFormDataTypeDef",
         clientToken: str = ...
     ) -> UpdateFormResponseTypeDef:
         """
         Updates an existing form.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.update_form)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#update_form)
@@ -379,15 +422,15 @@
 
     async def update_theme(
         self,
         *,
         appId: str,
         environmentName: str,
         id: str,
-        updatedTheme: UpdateThemeDataTypeDef,
+        updatedTheme: "UpdateThemeDataTypeDef",
         clientToken: str = ...
     ) -> UpdateThemeResponseTypeDef:
         """
         Updates an existing theme.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.update_theme)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#update_theme)
@@ -413,14 +456,23 @@
     def get_paginator(self, operation_name: Literal["export_themes"]) -> ExportThemesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#get_paginator)
         """
 
     @overload
+    def get_paginator(
+        self, operation_name: Literal["list_codegen_jobs"]
+    ) -> ListCodegenJobsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#get_paginator)
+        """
+
+    @overload
     def get_paginator(self, operation_name: Literal["list_components"]) -> ListComponentsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#get_paginator)
         """
 
     @overload
```

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/client.pyi` & `types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/client.pyi`

 * *Files 20% similar despite different names*

```diff
@@ -20,14 +20,15 @@
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .paginator import (
     ExportComponentsPaginator,
     ExportFormsPaginator,
     ExportThemesPaginator,
+    ListCodegenJobsPaginator,
     ListComponentsPaginator,
     ListFormsPaginator,
     ListThemesPaginator,
 )
 from .type_defs import (
     CreateComponentDataTypeDef,
     CreateComponentResponseTypeDef,
@@ -37,24 +38,28 @@
     CreateThemeResponseTypeDef,
     EmptyResponseMetadataTypeDef,
     ExchangeCodeForTokenRequestBodyTypeDef,
     ExchangeCodeForTokenResponseTypeDef,
     ExportComponentsResponseTypeDef,
     ExportFormsResponseTypeDef,
     ExportThemesResponseTypeDef,
+    GetCodegenJobResponseTypeDef,
     GetComponentResponseTypeDef,
     GetFormResponseTypeDef,
     GetMetadataResponseTypeDef,
     GetThemeResponseTypeDef,
+    ListCodegenJobsResponseTypeDef,
     ListComponentsResponseTypeDef,
     ListFormsResponseTypeDef,
     ListThemesResponseTypeDef,
     PutMetadataFlagBodyTypeDef,
     RefreshTokenRequestBodyTypeDef,
     RefreshTokenResponseTypeDef,
+    StartCodegenJobDataTypeDef,
+    StartCodegenJobResponseTypeDef,
     UpdateComponentDataTypeDef,
     UpdateComponentResponseTypeDef,
     UpdateFormDataTypeDef,
     UpdateFormResponseTypeDef,
     UpdateThemeDataTypeDef,
     UpdateThemeResponseTypeDef,
 )
@@ -76,14 +81,15 @@
 class Exceptions:
     ClientError: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     InvalidParameterException: Type[BotocoreClientError]
     ResourceConflictException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
+    ThrottlingException: Type[BotocoreClientError]
     UnauthorizedException: Type[BotocoreClientError]
 
 class AmplifyUIBuilderClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/)
     """
@@ -112,44 +118,44 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#close)
         """
     async def create_component(
         self,
         *,
         appId: str,
-        componentToCreate: CreateComponentDataTypeDef,
         environmentName: str,
+        componentToCreate: "CreateComponentDataTypeDef",
         clientToken: str = ...
     ) -> CreateComponentResponseTypeDef:
         """
         Creates a new component for an Amplify app.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.create_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#create_component)
         """
     async def create_form(
         self,
         *,
         appId: str,
         environmentName: str,
-        formToCreate: CreateFormDataTypeDef,
+        formToCreate: "CreateFormDataTypeDef",
         clientToken: str = ...
     ) -> CreateFormResponseTypeDef:
         """
-        Creates a new form for an Amplify app.
+        Creates a new form for an Amplify.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.create_form)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#create_form)
         """
     async def create_theme(
         self,
         *,
         appId: str,
         environmentName: str,
-        themeToCreate: CreateThemeDataTypeDef,
+        themeToCreate: "CreateThemeDataTypeDef",
         clientToken: str = ...
     ) -> CreateThemeResponseTypeDef:
         """
         Creates a theme to apply to the components in an Amplify app.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.create_theme)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#create_theme)
@@ -178,15 +184,15 @@
         """
         Deletes a theme from an Amplify app.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.delete_theme)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#delete_theme)
         """
     async def exchange_code_for_token(
-        self, *, provider: Literal["figma"], request: ExchangeCodeForTokenRequestBodyTypeDef
+        self, *, provider: Literal["figma"], request: "ExchangeCodeForTokenRequestBodyTypeDef"
     ) -> ExchangeCodeForTokenResponseTypeDef:
         """
         Exchanges an access code for a token.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.exchange_code_for_token)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#exchange_code_for_token)
         """
@@ -229,14 +235,23 @@
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#generate_presigned_url)
         """
+    async def get_codegen_job(
+        self, *, appId: str, environmentName: str, id: str
+    ) -> GetCodegenJobResponseTypeDef:
+        """
+        Returns an existing code generation job.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.get_codegen_job)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#get_codegen_job)
+        """
     async def get_component(
         self, *, appId: str, environmentName: str, id: str
     ) -> GetComponentResponseTypeDef:
         """
         Returns an existing component for an Amplify app.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.get_component)
@@ -263,102 +278,127 @@
     ) -> GetThemeResponseTypeDef:
         """
         Returns an existing theme for an Amplify app.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.get_theme)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#get_theme)
         """
+    async def list_codegen_jobs(
+        self, *, appId: str, environmentName: str, nextToken: str = ..., maxResults: int = ...
+    ) -> ListCodegenJobsResponseTypeDef:
+        """
+        Retrieves a list of code generation jobs for a specified Amplify app and backend
+        environment.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.list_codegen_jobs)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#list_codegen_jobs)
+        """
     async def list_components(
-        self, *, appId: str, environmentName: str, maxResults: int = ..., nextToken: str = ...
+        self, *, appId: str, environmentName: str, nextToken: str = ..., maxResults: int = ...
     ) -> ListComponentsResponseTypeDef:
         """
         Retrieves a list of components for a specified Amplify app and backend
         environment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.list_components)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#list_components)
         """
     async def list_forms(
-        self, *, appId: str, environmentName: str, maxResults: int = ..., nextToken: str = ...
+        self, *, appId: str, environmentName: str, nextToken: str = ..., maxResults: int = ...
     ) -> ListFormsResponseTypeDef:
         """
         Retrieves a list of forms for a specified Amplify app and backend environment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.list_forms)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#list_forms)
         """
     async def list_themes(
-        self, *, appId: str, environmentName: str, maxResults: int = ..., nextToken: str = ...
+        self, *, appId: str, environmentName: str, nextToken: str = ..., maxResults: int = ...
     ) -> ListThemesResponseTypeDef:
         """
         Retrieves a list of themes for a specified Amplify app and backend environment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.list_themes)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#list_themes)
         """
     async def put_metadata_flag(
         self,
         *,
         appId: str,
-        body: PutMetadataFlagBodyTypeDef,
         environmentName: str,
-        featureName: str
+        featureName: str,
+        body: "PutMetadataFlagBodyTypeDef"
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Stores the metadata information about a feature on a form or view.
+        Stores the metadata information about a feature on a form.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.put_metadata_flag)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#put_metadata_flag)
         """
     async def refresh_token(
-        self, *, provider: Literal["figma"], refreshTokenBody: RefreshTokenRequestBodyTypeDef
+        self, *, provider: Literal["figma"], refreshTokenBody: "RefreshTokenRequestBodyTypeDef"
     ) -> RefreshTokenResponseTypeDef:
         """
         Refreshes a previously issued access token that might have expired.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.refresh_token)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#refresh_token)
         """
+    async def start_codegen_job(
+        self,
+        *,
+        appId: str,
+        environmentName: str,
+        codegenJobToCreate: "StartCodegenJobDataTypeDef",
+        clientToken: str = ...
+    ) -> StartCodegenJobResponseTypeDef:
+        """
+        Starts a code generation job for for a specified Amplify app and backend
+        environment.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.start_codegen_job)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#start_codegen_job)
+        """
     async def update_component(
         self,
         *,
         appId: str,
         environmentName: str,
         id: str,
-        updatedComponent: UpdateComponentDataTypeDef,
+        updatedComponent: "UpdateComponentDataTypeDef",
         clientToken: str = ...
     ) -> UpdateComponentResponseTypeDef:
         """
         Updates an existing component.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.update_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#update_component)
         """
     async def update_form(
         self,
         *,
         appId: str,
         environmentName: str,
         id: str,
-        updatedForm: UpdateFormDataTypeDef,
+        updatedForm: "UpdateFormDataTypeDef",
         clientToken: str = ...
     ) -> UpdateFormResponseTypeDef:
         """
         Updates an existing form.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.update_form)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#update_form)
         """
     async def update_theme(
         self,
         *,
         appId: str,
         environmentName: str,
         id: str,
-        updatedTheme: UpdateThemeDataTypeDef,
+        updatedTheme: "UpdateThemeDataTypeDef",
         clientToken: str = ...
     ) -> UpdateThemeResponseTypeDef:
         """
         Updates an existing theme.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.update_theme)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#update_theme)
@@ -380,14 +420,22 @@
     @overload
     def get_paginator(self, operation_name: Literal["export_themes"]) -> ExportThemesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#get_paginator)
         """
     @overload
+    def get_paginator(
+        self, operation_name: Literal["list_codegen_jobs"]
+    ) -> ListCodegenJobsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#get_paginator)
+        """
+    @overload
     def get_paginator(self, operation_name: Literal["list_components"]) -> ListComponentsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/client/#get_paginator)
         """
     @overload
     def get_paginator(self, operation_name: Literal["list_forms"]) -> ListFormsPaginator:
```

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/paginator.py` & `types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/paginator.py`

 * *Files 8% similar despite different names*

```diff
@@ -9,57 +9,54 @@
     from aiobotocore.session import get_session
 
     from types_aiobotocore_amplifyuibuilder.client import AmplifyUIBuilderClient
     from types_aiobotocore_amplifyuibuilder.paginator import (
         ExportComponentsPaginator,
         ExportFormsPaginator,
         ExportThemesPaginator,
+        ListCodegenJobsPaginator,
         ListComponentsPaginator,
         ListFormsPaginator,
         ListThemesPaginator,
     )
 
     session = get_session()
     with session.create_client("amplifyuibuilder") as client:
         client: AmplifyUIBuilderClient
 
         export_components_paginator: ExportComponentsPaginator = client.get_paginator("export_components")
         export_forms_paginator: ExportFormsPaginator = client.get_paginator("export_forms")
         export_themes_paginator: ExportThemesPaginator = client.get_paginator("export_themes")
+        list_codegen_jobs_paginator: ListCodegenJobsPaginator = client.get_paginator("list_codegen_jobs")
         list_components_paginator: ListComponentsPaginator = client.get_paginator("list_components")
         list_forms_paginator: ListFormsPaginator = client.get_paginator("list_forms")
         list_themes_paginator: ListThemesPaginator = client.get_paginator("list_themes")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ExportComponentsResponseTypeDef,
     ExportFormsResponseTypeDef,
     ExportThemesResponseTypeDef,
+    ListCodegenJobsResponseTypeDef,
     ListComponentsResponseTypeDef,
     ListFormsResponseTypeDef,
     ListThemesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ExportComponentsPaginator",
     "ExportFormsPaginator",
     "ExportThemesPaginator",
+    "ListCodegenJobsPaginator",
     "ListComponentsPaginator",
     "ListFormsPaginator",
     "ListThemesPaginator",
 )
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
@@ -75,88 +72,103 @@
 class ExportComponentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ExportComponents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#exportcomponentspaginator)
     """
 
     def paginate(
-        self, *, appId: str, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, appId: str, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ExportComponentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ExportComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#exportcomponentspaginator)
         """
 
 
 class ExportFormsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ExportForms)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#exportformspaginator)
     """
 
     def paginate(
-        self, *, appId: str, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, appId: str, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ExportFormsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ExportForms.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#exportformspaginator)
         """
 
 
 class ExportThemesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ExportThemes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#exportthemespaginator)
     """
 
     def paginate(
-        self, *, appId: str, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, appId: str, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ExportThemesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ExportThemes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#exportthemespaginator)
         """
 
 
+class ListCodegenJobsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListCodegenJobs)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listcodegenjobspaginator)
+    """
+
+    def paginate(
+        self, *, appId: str, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListCodegenJobsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListCodegenJobs.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listcodegenjobspaginator)
+        """
+
+
 class ListComponentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListComponents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listcomponentspaginator)
     """
 
     def paginate(
-        self, *, appId: str, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, appId: str, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComponentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listcomponentspaginator)
         """
 
 
 class ListFormsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListForms)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listformspaginator)
     """
 
     def paginate(
-        self, *, appId: str, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, appId: str, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFormsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListForms.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listformspaginator)
         """
 
 
 class ListThemesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListThemes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listthemespaginator)
     """
 
     def paginate(
-        self, *, appId: str, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, appId: str, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThemesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListThemes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listthemespaginator)
         """
```

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/paginator.pyi` & `types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -9,56 +9,54 @@
     from aiobotocore.session import get_session
 
     from types_aiobotocore_amplifyuibuilder.client import AmplifyUIBuilderClient
     from types_aiobotocore_amplifyuibuilder.paginator import (
         ExportComponentsPaginator,
         ExportFormsPaginator,
         ExportThemesPaginator,
+        ListCodegenJobsPaginator,
         ListComponentsPaginator,
         ListFormsPaginator,
         ListThemesPaginator,
     )
 
     session = get_session()
     with session.create_client("amplifyuibuilder") as client:
         client: AmplifyUIBuilderClient
 
         export_components_paginator: ExportComponentsPaginator = client.get_paginator("export_components")
         export_forms_paginator: ExportFormsPaginator = client.get_paginator("export_forms")
         export_themes_paginator: ExportThemesPaginator = client.get_paginator("export_themes")
+        list_codegen_jobs_paginator: ListCodegenJobsPaginator = client.get_paginator("list_codegen_jobs")
         list_components_paginator: ListComponentsPaginator = client.get_paginator("list_components")
         list_forms_paginator: ListFormsPaginator = client.get_paginator("list_forms")
         list_themes_paginator: ListThemesPaginator = client.get_paginator("list_themes")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ExportComponentsResponseTypeDef,
     ExportFormsResponseTypeDef,
     ExportThemesResponseTypeDef,
+    ListCodegenJobsResponseTypeDef,
     ListComponentsResponseTypeDef,
     ListFormsResponseTypeDef,
     ListThemesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ExportComponentsPaginator",
     "ExportFormsPaginator",
     "ExportThemesPaginator",
+    "ListCodegenJobsPaginator",
     "ListComponentsPaginator",
     "ListFormsPaginator",
     "ListThemesPaginator",
 )
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
@@ -71,83 +69,97 @@
 class ExportComponentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ExportComponents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#exportcomponentspaginator)
     """
 
     def paginate(
-        self, *, appId: str, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, appId: str, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ExportComponentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ExportComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#exportcomponentspaginator)
         """
 
 class ExportFormsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ExportForms)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#exportformspaginator)
     """
 
     def paginate(
-        self, *, appId: str, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, appId: str, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ExportFormsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ExportForms.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#exportformspaginator)
         """
 
 class ExportThemesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ExportThemes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#exportthemespaginator)
     """
 
     def paginate(
-        self, *, appId: str, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, appId: str, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ExportThemesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ExportThemes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#exportthemespaginator)
         """
 
+class ListCodegenJobsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListCodegenJobs)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listcodegenjobspaginator)
+    """
+
+    def paginate(
+        self, *, appId: str, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListCodegenJobsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListCodegenJobs.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listcodegenjobspaginator)
+        """
+
 class ListComponentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListComponents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listcomponentspaginator)
     """
 
     def paginate(
-        self, *, appId: str, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, appId: str, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComponentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listcomponentspaginator)
         """
 
 class ListFormsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListForms)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listformspaginator)
     """
 
     def paginate(
-        self, *, appId: str, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, appId: str, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFormsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListForms.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listformspaginator)
         """
 
 class ListThemesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListThemes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listthemespaginator)
     """
 
     def paginate(
-        self, *, appId: str, environmentName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, appId: str, environmentName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThemesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder.Paginator.ListThemes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/paginators/#listthemespaginator)
         """
```

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/type_defs.py` & `types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/type_defs.pyi`

 * *Files 20% similar despite different names*

```diff
@@ -2,181 +2,442 @@
 Type annotations for amplifyuibuilder service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_amplifyuibuilder.type_defs import MutationActionSetStateParameterTypeDef
+    from types_aiobotocore_amplifyuibuilder.type_defs import ActionParametersTypeDef
 
-    data: MutationActionSetStateParameterTypeDef = {...}
+    data: ActionParametersTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Any, Dict, List, Mapping, Sequence
 
 from .literals import (
+    CodegenGenericDataFieldDataTypeType,
+    CodegenJobStatusType,
     FormActionTypeType,
     FormButtonsPositionType,
     FormDataSourceTypeType,
+    GenericDataRelationshipTypeType,
+    JSModuleType,
+    JSScriptType,
+    JSTargetType,
+    LabelDecoratorType,
     SortDirectionType,
+    StorageAccessLevelType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
-    "MutationActionSetStateParameterTypeDef",
+    "ActionParametersTypeDef",
+    "CodegenFeatureFlagsTypeDef",
+    "CodegenGenericDataEnumTypeDef",
+    "CodegenGenericDataFieldTypeDef",
+    "CodegenGenericDataModelTypeDef",
+    "CodegenGenericDataNonModelTypeDef",
+    "CodegenGenericDataRelationshipTypeTypeDef",
+    "CodegenJobAssetTypeDef",
+    "CodegenJobGenericDataSchemaTypeDef",
+    "CodegenJobRenderConfigTypeDef",
+    "CodegenJobSummaryTypeDef",
+    "CodegenJobTypeDef",
     "ComponentBindingPropertiesValuePropertiesTypeDef",
+    "ComponentBindingPropertiesValueTypeDef",
+    "ComponentChildTypeDef",
     "ComponentConditionPropertyTypeDef",
-    "SortPropertyTypeDef",
+    "ComponentDataConfigurationTypeDef",
+    "ComponentEventTypeDef",
     "ComponentPropertyBindingPropertiesTypeDef",
-    "FormBindingElementTypeDef",
+    "ComponentPropertyTypeDef",
     "ComponentSummaryTypeDef",
+    "ComponentTypeDef",
     "ComponentVariantTypeDef",
-    "ResponseMetadataTypeDef",
-    "FormDataTypeConfigTypeDef",
+    "CreateComponentDataTypeDef",
+    "CreateComponentRequestRequestTypeDef",
+    "CreateComponentResponseTypeDef",
+    "CreateFormDataTypeDef",
+    "CreateFormRequestRequestTypeDef",
+    "CreateFormResponseTypeDef",
     "CreateThemeDataTypeDef",
-    "ThemeTypeDef",
+    "CreateThemeRequestRequestTypeDef",
+    "CreateThemeResponseTypeDef",
     "DeleteComponentRequestRequestTypeDef",
     "DeleteFormRequestRequestTypeDef",
     "DeleteThemeRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExchangeCodeForTokenRequestBodyTypeDef",
-    "PaginatorConfigTypeDef",
+    "ExchangeCodeForTokenRequestRequestTypeDef",
+    "ExchangeCodeForTokenResponseTypeDef",
+    "ExportComponentsRequestExportComponentsPaginateTypeDef",
     "ExportComponentsRequestRequestTypeDef",
+    "ExportComponentsResponseTypeDef",
+    "ExportFormsRequestExportFormsPaginateTypeDef",
     "ExportFormsRequestRequestTypeDef",
+    "ExportFormsResponseTypeDef",
+    "ExportThemesRequestExportThemesPaginateTypeDef",
     "ExportThemesRequestRequestTypeDef",
+    "ExportThemesResponseTypeDef",
+    "FieldConfigTypeDef",
+    "FieldInputConfigTypeDef",
     "FieldPositionTypeDef",
     "FieldValidationConfigurationTypeDef",
+    "FileUploaderFieldConfigTypeDef",
+    "FormBindingElementTypeDef",
+    "FormButtonTypeDef",
+    "FormCTATypeDef",
+    "FormDataTypeConfigTypeDef",
+    "FormInputBindingPropertiesValuePropertiesTypeDef",
+    "FormInputBindingPropertiesValueTypeDef",
+    "FormInputValuePropertyBindingPropertiesTypeDef",
     "FormInputValuePropertyTypeDef",
     "FormStyleConfigTypeDef",
+    "FormStyleTypeDef",
+    "FormSummaryTypeDef",
+    "FormTypeDef",
+    "GetCodegenJobRequestRequestTypeDef",
+    "GetCodegenJobResponseTypeDef",
     "GetComponentRequestRequestTypeDef",
+    "GetComponentResponseTypeDef",
     "GetFormRequestRequestTypeDef",
+    "GetFormResponseTypeDef",
     "GetMetadataRequestRequestTypeDef",
+    "GetMetadataResponseTypeDef",
     "GetThemeRequestRequestTypeDef",
+    "GetThemeResponseTypeDef",
+    "ListCodegenJobsRequestListCodegenJobsPaginateTypeDef",
+    "ListCodegenJobsRequestRequestTypeDef",
+    "ListCodegenJobsResponseTypeDef",
+    "ListComponentsRequestListComponentsPaginateTypeDef",
     "ListComponentsRequestRequestTypeDef",
+    "ListComponentsResponseTypeDef",
+    "ListFormsRequestListFormsPaginateTypeDef",
     "ListFormsRequestRequestTypeDef",
+    "ListFormsResponseTypeDef",
+    "ListThemesRequestListThemesPaginateTypeDef",
     "ListThemesRequestRequestTypeDef",
-    "ThemeSummaryTypeDef",
+    "ListThemesResponseTypeDef",
+    "MutationActionSetStateParameterTypeDef",
+    "PaginatorConfigTypeDef",
     "PredicateTypeDef",
     "PutMetadataFlagBodyTypeDef",
+    "PutMetadataFlagRequestRequestTypeDef",
+    "ReactStartCodegenJobDataTypeDef",
     "RefreshTokenRequestBodyTypeDef",
-    "ThemeValueTypeDef",
-    "ThemeValuesTypeDef",
-    "UpdateThemeDataTypeDef",
-    "ActionParametersTypeDef",
-    "ComponentBindingPropertiesValueTypeDef",
-    "ComponentDataConfigurationTypeDef",
-    "ComponentPropertyTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExchangeCodeForTokenResponseTypeDef",
-    "GetMetadataResponseTypeDef",
-    "ListComponentsResponseTypeDef",
+    "RefreshTokenRequestRequestTypeDef",
     "RefreshTokenResponseTypeDef",
-    "FormSummaryTypeDef",
-    "CreateThemeRequestRequestTypeDef",
-    "CreateThemeResponseTypeDef",
-    "ExportThemesResponseTypeDef",
-    "GetThemeResponseTypeDef",
-    "UpdateThemeResponseTypeDef",
-    "ExchangeCodeForTokenRequestRequestTypeDef",
-    "ExportComponentsRequestExportComponentsPaginateTypeDef",
-    "ExportFormsRequestExportFormsPaginateTypeDef",
-    "ExportThemesRequestExportThemesPaginateTypeDef",
-    "ListComponentsRequestListComponentsPaginateTypeDef",
-    "ListFormsRequestListFormsPaginateTypeDef",
-    "ListThemesRequestListThemesPaginateTypeDef",
-    "FormButtonTypeDef",
+    "ResponseMetadataTypeDef",
     "SectionalElementTypeDef",
-    "ValueMappingTypeDef",
-    "FormStyleTypeDef",
-    "ListThemesResponseTypeDef",
-    "PutMetadataFlagRequestRequestTypeDef",
-    "RefreshTokenRequestRequestTypeDef",
-    "UpdateThemeRequestRequestTypeDef",
-    "ComponentEventTypeDef",
-    "ListFormsResponseTypeDef",
-    "FormCTATypeDef",
-    "ValueMappingsTypeDef",
-    "ComponentChildTypeDef",
-    "ComponentTypeDef",
-    "CreateComponentDataTypeDef",
+    "SortPropertyTypeDef",
+    "StartCodegenJobDataTypeDef",
+    "StartCodegenJobRequestRequestTypeDef",
+    "StartCodegenJobResponseTypeDef",
+    "ThemeSummaryTypeDef",
+    "ThemeTypeDef",
+    "ThemeValueTypeDef",
+    "ThemeValuesTypeDef",
     "UpdateComponentDataTypeDef",
-    "FieldInputConfigTypeDef",
-    "CreateComponentResponseTypeDef",
-    "ExportComponentsResponseTypeDef",
-    "GetComponentResponseTypeDef",
-    "UpdateComponentResponseTypeDef",
-    "CreateComponentRequestRequestTypeDef",
     "UpdateComponentRequestRequestTypeDef",
-    "FieldConfigTypeDef",
-    "CreateFormDataTypeDef",
-    "FormTypeDef",
+    "UpdateComponentResponseTypeDef",
     "UpdateFormDataTypeDef",
-    "CreateFormRequestRequestTypeDef",
-    "CreateFormResponseTypeDef",
-    "ExportFormsResponseTypeDef",
-    "GetFormResponseTypeDef",
-    "UpdateFormResponseTypeDef",
     "UpdateFormRequestRequestTypeDef",
+    "UpdateFormResponseTypeDef",
+    "UpdateThemeDataTypeDef",
+    "UpdateThemeRequestRequestTypeDef",
+    "UpdateThemeResponseTypeDef",
+    "ValueMappingTypeDef",
+    "ValueMappingsTypeDef",
 )
 
-MutationActionSetStateParameterTypeDef = TypedDict(
-    "MutationActionSetStateParameterTypeDef",
+ActionParametersTypeDef = TypedDict(
+    "ActionParametersTypeDef",
     {
-        "componentName": str,
-        "property": str,
-        "set": "ComponentPropertyTypeDef",
+        "type": "ComponentPropertyTypeDef",
+        "url": "ComponentPropertyTypeDef",
+        "anchor": "ComponentPropertyTypeDef",
+        "target": "ComponentPropertyTypeDef",
+        "global": "ComponentPropertyTypeDef",
+        "model": str,
+        "id": "ComponentPropertyTypeDef",
+        "fields": Mapping[str, "ComponentPropertyTypeDef"],
+        "state": "MutationActionSetStateParameterTypeDef",
+    },
+    total=False,
+)
+
+CodegenFeatureFlagsTypeDef = TypedDict(
+    "CodegenFeatureFlagsTypeDef",
+    {
+        "isRelationshipSupported": bool,
+        "isNonModelSupported": bool,
+    },
+    total=False,
+)
+
+CodegenGenericDataEnumTypeDef = TypedDict(
+    "CodegenGenericDataEnumTypeDef",
+    {
+        "values": List[str],
+    },
+)
+
+_RequiredCodegenGenericDataFieldTypeDef = TypedDict(
+    "_RequiredCodegenGenericDataFieldTypeDef",
+    {
+        "dataType": CodegenGenericDataFieldDataTypeType,
+        "dataTypeValue": str,
+        "required": bool,
+        "readOnly": bool,
+        "isArray": bool,
+    },
+)
+_OptionalCodegenGenericDataFieldTypeDef = TypedDict(
+    "_OptionalCodegenGenericDataFieldTypeDef",
+    {
+        "relationship": "CodegenGenericDataRelationshipTypeTypeDef",
+    },
+    total=False,
+)
+
+class CodegenGenericDataFieldTypeDef(
+    _RequiredCodegenGenericDataFieldTypeDef, _OptionalCodegenGenericDataFieldTypeDef
+):
+    pass
+
+_RequiredCodegenGenericDataModelTypeDef = TypedDict(
+    "_RequiredCodegenGenericDataModelTypeDef",
+    {
+        "fields": Dict[str, "CodegenGenericDataFieldTypeDef"],
+        "primaryKeys": List[str],
+    },
+)
+_OptionalCodegenGenericDataModelTypeDef = TypedDict(
+    "_OptionalCodegenGenericDataModelTypeDef",
+    {
+        "isJoinTable": bool,
+    },
+    total=False,
+)
+
+class CodegenGenericDataModelTypeDef(
+    _RequiredCodegenGenericDataModelTypeDef, _OptionalCodegenGenericDataModelTypeDef
+):
+    pass
+
+CodegenGenericDataNonModelTypeDef = TypedDict(
+    "CodegenGenericDataNonModelTypeDef",
+    {
+        "fields": Dict[str, "CodegenGenericDataFieldTypeDef"],
+    },
+)
+
+_RequiredCodegenGenericDataRelationshipTypeTypeDef = TypedDict(
+    "_RequiredCodegenGenericDataRelationshipTypeTypeDef",
+    {
+        "type": GenericDataRelationshipTypeType,
+        "relatedModelName": str,
+    },
+)
+_OptionalCodegenGenericDataRelationshipTypeTypeDef = TypedDict(
+    "_OptionalCodegenGenericDataRelationshipTypeTypeDef",
+    {
+        "relatedModelFields": List[str],
+        "canUnlinkAssociatedModel": bool,
+        "relatedJoinFieldName": str,
+        "relatedJoinTableName": str,
+        "belongsToFieldOnRelatedModel": str,
+        "associatedFields": List[str],
+        "isHasManyIndex": bool,
+    },
+    total=False,
+)
+
+class CodegenGenericDataRelationshipTypeTypeDef(
+    _RequiredCodegenGenericDataRelationshipTypeTypeDef,
+    _OptionalCodegenGenericDataRelationshipTypeTypeDef,
+):
+    pass
+
+CodegenJobAssetTypeDef = TypedDict(
+    "CodegenJobAssetTypeDef",
+    {
+        "downloadUrl": str,
+    },
+    total=False,
+)
+
+CodegenJobGenericDataSchemaTypeDef = TypedDict(
+    "CodegenJobGenericDataSchemaTypeDef",
+    {
+        "dataSourceType": Literal["DataStore"],
+        "models": Dict[str, "CodegenGenericDataModelTypeDef"],
+        "enums": Dict[str, "CodegenGenericDataEnumTypeDef"],
+        "nonModels": Dict[str, "CodegenGenericDataNonModelTypeDef"],
+    },
+)
+
+CodegenJobRenderConfigTypeDef = TypedDict(
+    "CodegenJobRenderConfigTypeDef",
+    {
+        "react": "ReactStartCodegenJobDataTypeDef",
+    },
+    total=False,
+)
+
+_RequiredCodegenJobSummaryTypeDef = TypedDict(
+    "_RequiredCodegenJobSummaryTypeDef",
+    {
+        "appId": str,
+        "environmentName": str,
+        "id": str,
+    },
+)
+_OptionalCodegenJobSummaryTypeDef = TypedDict(
+    "_OptionalCodegenJobSummaryTypeDef",
+    {
+        "createdAt": datetime,
+        "modifiedAt": datetime,
+    },
+    total=False,
+)
+
+class CodegenJobSummaryTypeDef(
+    _RequiredCodegenJobSummaryTypeDef, _OptionalCodegenJobSummaryTypeDef
+):
+    pass
+
+_RequiredCodegenJobTypeDef = TypedDict(
+    "_RequiredCodegenJobTypeDef",
+    {
+        "id": str,
+        "appId": str,
+        "environmentName": str,
+    },
+)
+_OptionalCodegenJobTypeDef = TypedDict(
+    "_OptionalCodegenJobTypeDef",
+    {
+        "renderConfig": "CodegenJobRenderConfigTypeDef",
+        "genericDataSchema": "CodegenJobGenericDataSchemaTypeDef",
+        "autoGenerateForms": bool,
+        "features": "CodegenFeatureFlagsTypeDef",
+        "status": CodegenJobStatusType,
+        "statusMessage": str,
+        "asset": "CodegenJobAssetTypeDef",
+        "tags": Dict[str, str],
+        "createdAt": datetime,
+        "modifiedAt": datetime,
     },
+    total=False,
 )
 
+class CodegenJobTypeDef(_RequiredCodegenJobTypeDef, _OptionalCodegenJobTypeDef):
+    pass
+
 ComponentBindingPropertiesValuePropertiesTypeDef = TypedDict(
     "ComponentBindingPropertiesValuePropertiesTypeDef",
     {
-        "bucket": str,
-        "defaultValue": str,
-        "field": str,
-        "key": str,
         "model": str,
+        "field": str,
         "predicates": Sequence["PredicateTypeDef"],
-        "slotName": str,
         "userAttribute": str,
+        "bucket": str,
+        "key": str,
+        "defaultValue": str,
+        "slotName": str,
     },
     total=False,
 )
 
+ComponentBindingPropertiesValueTypeDef = TypedDict(
+    "ComponentBindingPropertiesValueTypeDef",
+    {
+        "type": str,
+        "bindingProperties": "ComponentBindingPropertiesValuePropertiesTypeDef",
+        "defaultValue": str,
+    },
+    total=False,
+)
+
+_RequiredComponentChildTypeDef = TypedDict(
+    "_RequiredComponentChildTypeDef",
+    {
+        "componentType": str,
+        "name": str,
+        "properties": Mapping[str, "ComponentPropertyTypeDef"],
+    },
+)
+_OptionalComponentChildTypeDef = TypedDict(
+    "_OptionalComponentChildTypeDef",
+    {
+        "children": Sequence[Dict[str, Any]],
+        "events": Mapping[str, "ComponentEventTypeDef"],
+        "sourceId": str,
+    },
+    total=False,
+)
+
+class ComponentChildTypeDef(_RequiredComponentChildTypeDef, _OptionalComponentChildTypeDef):
+    pass
+
 ComponentConditionPropertyTypeDef = TypedDict(
     "ComponentConditionPropertyTypeDef",
     {
-        "else": Dict[str, Any],
+        "property": str,
         "field": str,
-        "operand": str,
-        "operandType": str,
         "operator": str,
-        "property": str,
+        "operand": str,
         "then": Dict[str, Any],
+        "else": Dict[str, Any],
+        "operandType": str,
     },
     total=False,
 )
 
-SortPropertyTypeDef = TypedDict(
-    "SortPropertyTypeDef",
+_RequiredComponentDataConfigurationTypeDef = TypedDict(
+    "_RequiredComponentDataConfigurationTypeDef",
     {
-        "direction": SortDirectionType,
-        "field": str,
+        "model": str,
     },
 )
+_OptionalComponentDataConfigurationTypeDef = TypedDict(
+    "_OptionalComponentDataConfigurationTypeDef",
+    {
+        "sort": Sequence["SortPropertyTypeDef"],
+        "predicate": "PredicateTypeDef",
+        "identifiers": Sequence[str],
+    },
+    total=False,
+)
+
+class ComponentDataConfigurationTypeDef(
+    _RequiredComponentDataConfigurationTypeDef, _OptionalComponentDataConfigurationTypeDef
+):
+    pass
+
+ComponentEventTypeDef = TypedDict(
+    "ComponentEventTypeDef",
+    {
+        "action": str,
+        "parameters": "ActionParametersTypeDef",
+        "bindingEvent": str,
+    },
+    total=False,
+)
 
 _RequiredComponentPropertyBindingPropertiesTypeDef = TypedDict(
     "_RequiredComponentPropertyBindingPropertiesTypeDef",
     {
         "property": str,
     },
 )
@@ -184,66 +445,203 @@
     "_OptionalComponentPropertyBindingPropertiesTypeDef",
     {
         "field": str,
     },
     total=False,
 )
 
-
 class ComponentPropertyBindingPropertiesTypeDef(
     _RequiredComponentPropertyBindingPropertiesTypeDef,
     _OptionalComponentPropertyBindingPropertiesTypeDef,
 ):
     pass
 
-
-FormBindingElementTypeDef = TypedDict(
-    "FormBindingElementTypeDef",
+ComponentPropertyTypeDef = TypedDict(
+    "ComponentPropertyTypeDef",
     {
-        "element": str,
+        "value": str,
+        "bindingProperties": "ComponentPropertyBindingPropertiesTypeDef",
+        "collectionBindingProperties": "ComponentPropertyBindingPropertiesTypeDef",
+        "defaultValue": str,
+        "model": str,
+        "bindings": Mapping[str, "FormBindingElementTypeDef"],
+        "event": str,
+        "userAttribute": str,
+        "concat": Sequence[Dict[str, Any]],
+        "condition": Dict[str, Any],
+        "configured": bool,
+        "type": str,
+        "importedValue": str,
+        "componentName": str,
         "property": str,
     },
+    total=False,
 )
 
 ComponentSummaryTypeDef = TypedDict(
     "ComponentSummaryTypeDef",
     {
         "appId": str,
+        "environmentName": str,
+        "id": str,
+        "name": str,
         "componentType": str,
+    },
+)
+
+_RequiredComponentTypeDef = TypedDict(
+    "_RequiredComponentTypeDef",
+    {
+        "appId": str,
         "environmentName": str,
         "id": str,
         "name": str,
+        "componentType": str,
+        "properties": Dict[str, "ComponentPropertyTypeDef"],
+        "variants": List["ComponentVariantTypeDef"],
+        "overrides": Dict[str, Dict[str, str]],
+        "bindingProperties": Dict[str, "ComponentBindingPropertiesValueTypeDef"],
+        "createdAt": datetime,
+    },
+)
+_OptionalComponentTypeDef = TypedDict(
+    "_OptionalComponentTypeDef",
+    {
+        "sourceId": str,
+        "children": List["ComponentChildTypeDef"],
+        "collectionProperties": Dict[str, "ComponentDataConfigurationTypeDef"],
+        "modifiedAt": datetime,
+        "tags": Dict[str, str],
+        "events": Dict[str, "ComponentEventTypeDef"],
+        "schemaVersion": str,
     },
+    total=False,
 )
 
+class ComponentTypeDef(_RequiredComponentTypeDef, _OptionalComponentTypeDef):
+    pass
+
 ComponentVariantTypeDef = TypedDict(
     "ComponentVariantTypeDef",
     {
-        "overrides": Mapping[str, Mapping[str, str]],
         "variantValues": Mapping[str, str],
+        "overrides": Mapping[str, Mapping[str, str]],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+_RequiredCreateComponentDataTypeDef = TypedDict(
+    "_RequiredCreateComponentDataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "name": str,
+        "componentType": str,
+        "properties": Mapping[str, "ComponentPropertyTypeDef"],
+        "variants": Sequence["ComponentVariantTypeDef"],
+        "overrides": Mapping[str, Mapping[str, str]],
+        "bindingProperties": Mapping[str, "ComponentBindingPropertiesValueTypeDef"],
     },
 )
+_OptionalCreateComponentDataTypeDef = TypedDict(
+    "_OptionalCreateComponentDataTypeDef",
+    {
+        "sourceId": str,
+        "children": Sequence["ComponentChildTypeDef"],
+        "collectionProperties": Mapping[str, "ComponentDataConfigurationTypeDef"],
+        "tags": Mapping[str, str],
+        "events": Mapping[str, "ComponentEventTypeDef"],
+        "schemaVersion": str,
+    },
+    total=False,
+)
 
-FormDataTypeConfigTypeDef = TypedDict(
-    "FormDataTypeConfigTypeDef",
+class CreateComponentDataTypeDef(
+    _RequiredCreateComponentDataTypeDef, _OptionalCreateComponentDataTypeDef
+):
+    pass
+
+_RequiredCreateComponentRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateComponentRequestRequestTypeDef",
     {
-        "dataSourceType": FormDataSourceTypeType,
-        "dataTypeName": str,
+        "appId": str,
+        "environmentName": str,
+        "componentToCreate": "CreateComponentDataTypeDef",
+    },
+)
+_OptionalCreateComponentRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateComponentRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class CreateComponentRequestRequestTypeDef(
+    _RequiredCreateComponentRequestRequestTypeDef, _OptionalCreateComponentRequestRequestTypeDef
+):
+    pass
+
+CreateComponentResponseTypeDef = TypedDict(
+    "CreateComponentResponseTypeDef",
+    {
+        "entity": "ComponentTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreateFormDataTypeDef = TypedDict(
+    "_RequiredCreateFormDataTypeDef",
+    {
+        "name": str,
+        "dataType": "FormDataTypeConfigTypeDef",
+        "formActionType": FormActionTypeType,
+        "fields": Mapping[str, "FieldConfigTypeDef"],
+        "style": "FormStyleTypeDef",
+        "sectionalElements": Mapping[str, "SectionalElementTypeDef"],
+        "schemaVersion": str,
+    },
+)
+_OptionalCreateFormDataTypeDef = TypedDict(
+    "_OptionalCreateFormDataTypeDef",
+    {
+        "cta": "FormCTATypeDef",
+        "tags": Mapping[str, str],
+        "labelDecorator": LabelDecoratorType,
+    },
+    total=False,
+)
+
+class CreateFormDataTypeDef(_RequiredCreateFormDataTypeDef, _OptionalCreateFormDataTypeDef):
+    pass
+
+_RequiredCreateFormRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateFormRequestRequestTypeDef",
+    {
+        "appId": str,
+        "environmentName": str,
+        "formToCreate": "CreateFormDataTypeDef",
+    },
+)
+_OptionalCreateFormRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateFormRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class CreateFormRequestRequestTypeDef(
+    _RequiredCreateFormRequestRequestTypeDef, _OptionalCreateFormRequestRequestTypeDef
+):
+    pass
+
+CreateFormResponseTypeDef = TypedDict(
+    "CreateFormResponseTypeDef",
+    {
+        "entity": "FormTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateThemeDataTypeDef = TypedDict(
     "_RequiredCreateThemeDataTypeDef",
     {
         "name": str,
@@ -255,44 +653,45 @@
     {
         "overrides": Sequence["ThemeValuesTypeDef"],
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateThemeDataTypeDef(_RequiredCreateThemeDataTypeDef, _OptionalCreateThemeDataTypeDef):
     pass
 
-
-_RequiredThemeTypeDef = TypedDict(
-    "_RequiredThemeTypeDef",
+_RequiredCreateThemeRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateThemeRequestRequestTypeDef",
     {
         "appId": str,
-        "createdAt": datetime,
         "environmentName": str,
-        "id": str,
-        "name": str,
-        "values": List["ThemeValuesTypeDef"],
+        "themeToCreate": "CreateThemeDataTypeDef",
     },
 )
-_OptionalThemeTypeDef = TypedDict(
-    "_OptionalThemeTypeDef",
+_OptionalCreateThemeRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateThemeRequestRequestTypeDef",
     {
-        "modifiedAt": datetime,
-        "overrides": List["ThemeValuesTypeDef"],
-        "tags": Dict[str, str],
+        "clientToken": str,
     },
     total=False,
 )
 
-
-class ThemeTypeDef(_RequiredThemeTypeDef, _OptionalThemeTypeDef):
+class CreateThemeRequestRequestTypeDef(
+    _RequiredCreateThemeRequestRequestTypeDef, _OptionalCreateThemeRequestRequestTypeDef
+):
     pass
 
+CreateThemeResponseTypeDef = TypedDict(
+    "CreateThemeResponseTypeDef",
+    {
+        "entity": "ThemeTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DeleteComponentRequestRequestTypeDef = TypedDict(
     "DeleteComponentRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
         "id": str,
@@ -313,1176 +712,1147 @@
     {
         "appId": str,
         "environmentName": str,
         "id": str,
     },
 )
 
-ExchangeCodeForTokenRequestBodyTypeDef = TypedDict(
-    "ExchangeCodeForTokenRequestBodyTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredExchangeCodeForTokenRequestBodyTypeDef = TypedDict(
+    "_RequiredExchangeCodeForTokenRequestBodyTypeDef",
     {
         "code": str,
         "redirectUri": str,
     },
 )
-
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_OptionalExchangeCodeForTokenRequestBodyTypeDef = TypedDict(
+    "_OptionalExchangeCodeForTokenRequestBodyTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "clientId": str,
     },
     total=False,
 )
 
-_RequiredExportComponentsRequestRequestTypeDef = TypedDict(
-    "_RequiredExportComponentsRequestRequestTypeDef",
+class ExchangeCodeForTokenRequestBodyTypeDef(
+    _RequiredExchangeCodeForTokenRequestBodyTypeDef, _OptionalExchangeCodeForTokenRequestBodyTypeDef
+):
+    pass
+
+ExchangeCodeForTokenRequestRequestTypeDef = TypedDict(
+    "ExchangeCodeForTokenRequestRequestTypeDef",
     {
-        "appId": str,
-        "environmentName": str,
+        "provider": Literal["figma"],
+        "request": "ExchangeCodeForTokenRequestBodyTypeDef",
     },
 )
-_OptionalExportComponentsRequestRequestTypeDef = TypedDict(
-    "_OptionalExportComponentsRequestRequestTypeDef",
+
+ExchangeCodeForTokenResponseTypeDef = TypedDict(
+    "ExchangeCodeForTokenResponseTypeDef",
     {
-        "nextToken": str,
+        "accessToken": str,
+        "expiresIn": int,
+        "refreshToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ExportComponentsRequestRequestTypeDef(
-    _RequiredExportComponentsRequestRequestTypeDef, _OptionalExportComponentsRequestRequestTypeDef
-):
-    pass
-
-
-_RequiredExportFormsRequestRequestTypeDef = TypedDict(
-    "_RequiredExportFormsRequestRequestTypeDef",
+_RequiredExportComponentsRequestExportComponentsPaginateTypeDef = TypedDict(
+    "_RequiredExportComponentsRequestExportComponentsPaginateTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
-_OptionalExportFormsRequestRequestTypeDef = TypedDict(
-    "_OptionalExportFormsRequestRequestTypeDef",
+_OptionalExportComponentsRequestExportComponentsPaginateTypeDef = TypedDict(
+    "_OptionalExportComponentsRequestExportComponentsPaginateTypeDef",
     {
-        "nextToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
-class ExportFormsRequestRequestTypeDef(
-    _RequiredExportFormsRequestRequestTypeDef, _OptionalExportFormsRequestRequestTypeDef
+class ExportComponentsRequestExportComponentsPaginateTypeDef(
+    _RequiredExportComponentsRequestExportComponentsPaginateTypeDef,
+    _OptionalExportComponentsRequestExportComponentsPaginateTypeDef,
 ):
     pass
 
-
-_RequiredExportThemesRequestRequestTypeDef = TypedDict(
-    "_RequiredExportThemesRequestRequestTypeDef",
+_RequiredExportComponentsRequestRequestTypeDef = TypedDict(
+    "_RequiredExportComponentsRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
-_OptionalExportThemesRequestRequestTypeDef = TypedDict(
-    "_OptionalExportThemesRequestRequestTypeDef",
+_OptionalExportComponentsRequestRequestTypeDef = TypedDict(
+    "_OptionalExportComponentsRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
 
-
-class ExportThemesRequestRequestTypeDef(
-    _RequiredExportThemesRequestRequestTypeDef, _OptionalExportThemesRequestRequestTypeDef
+class ExportComponentsRequestRequestTypeDef(
+    _RequiredExportComponentsRequestRequestTypeDef, _OptionalExportComponentsRequestRequestTypeDef
 ):
     pass
 
-
-FieldPositionTypeDef = TypedDict(
-    "FieldPositionTypeDef",
+ExportComponentsResponseTypeDef = TypedDict(
+    "ExportComponentsResponseTypeDef",
     {
-        "below": str,
-        "fixed": Literal["first"],
-        "rightOf": str,
+        "entities": List["ComponentTypeDef"],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredFieldValidationConfigurationTypeDef = TypedDict(
-    "_RequiredFieldValidationConfigurationTypeDef",
+_RequiredExportFormsRequestExportFormsPaginateTypeDef = TypedDict(
+    "_RequiredExportFormsRequestExportFormsPaginateTypeDef",
     {
-        "type": str,
+        "appId": str,
+        "environmentName": str,
     },
 )
-_OptionalFieldValidationConfigurationTypeDef = TypedDict(
-    "_OptionalFieldValidationConfigurationTypeDef",
+_OptionalExportFormsRequestExportFormsPaginateTypeDef = TypedDict(
+    "_OptionalExportFormsRequestExportFormsPaginateTypeDef",
     {
-        "numValues": Sequence[int],
-        "strValues": Sequence[str],
-        "validationMessage": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
-class FieldValidationConfigurationTypeDef(
-    _RequiredFieldValidationConfigurationTypeDef, _OptionalFieldValidationConfigurationTypeDef
+class ExportFormsRequestExportFormsPaginateTypeDef(
+    _RequiredExportFormsRequestExportFormsPaginateTypeDef,
+    _OptionalExportFormsRequestExportFormsPaginateTypeDef,
 ):
     pass
 
-
-FormInputValuePropertyTypeDef = TypedDict(
-    "FormInputValuePropertyTypeDef",
-    {
-        "value": str,
-    },
-    total=False,
-)
-
-FormStyleConfigTypeDef = TypedDict(
-    "FormStyleConfigTypeDef",
-    {
-        "tokenReference": str,
-        "value": str,
-    },
-    total=False,
-)
-
-GetComponentRequestRequestTypeDef = TypedDict(
-    "GetComponentRequestRequestTypeDef",
+_RequiredExportFormsRequestRequestTypeDef = TypedDict(
+    "_RequiredExportFormsRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
-        "id": str,
     },
 )
-
-GetFormRequestRequestTypeDef = TypedDict(
-    "GetFormRequestRequestTypeDef",
+_OptionalExportFormsRequestRequestTypeDef = TypedDict(
+    "_OptionalExportFormsRequestRequestTypeDef",
     {
-        "appId": str,
-        "environmentName": str,
-        "id": str,
+        "nextToken": str,
     },
+    total=False,
 )
 
-GetMetadataRequestRequestTypeDef = TypedDict(
-    "GetMetadataRequestRequestTypeDef",
-    {
-        "appId": str,
-        "environmentName": str,
-    },
-)
+class ExportFormsRequestRequestTypeDef(
+    _RequiredExportFormsRequestRequestTypeDef, _OptionalExportFormsRequestRequestTypeDef
+):
+    pass
 
-GetThemeRequestRequestTypeDef = TypedDict(
-    "GetThemeRequestRequestTypeDef",
+ExportFormsResponseTypeDef = TypedDict(
+    "ExportFormsResponseTypeDef",
     {
-        "appId": str,
-        "environmentName": str,
-        "id": str,
+        "entities": List["FormTypeDef"],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListComponentsRequestRequestTypeDef = TypedDict(
-    "_RequiredListComponentsRequestRequestTypeDef",
+_RequiredExportThemesRequestExportThemesPaginateTypeDef = TypedDict(
+    "_RequiredExportThemesRequestExportThemesPaginateTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
-_OptionalListComponentsRequestRequestTypeDef = TypedDict(
-    "_OptionalListComponentsRequestRequestTypeDef",
+_OptionalExportThemesRequestExportThemesPaginateTypeDef = TypedDict(
+    "_OptionalExportThemesRequestExportThemesPaginateTypeDef",
     {
-        "maxResults": int,
-        "nextToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
-class ListComponentsRequestRequestTypeDef(
-    _RequiredListComponentsRequestRequestTypeDef, _OptionalListComponentsRequestRequestTypeDef
+class ExportThemesRequestExportThemesPaginateTypeDef(
+    _RequiredExportThemesRequestExportThemesPaginateTypeDef,
+    _OptionalExportThemesRequestExportThemesPaginateTypeDef,
 ):
     pass
 
-
-_RequiredListFormsRequestRequestTypeDef = TypedDict(
-    "_RequiredListFormsRequestRequestTypeDef",
+_RequiredExportThemesRequestRequestTypeDef = TypedDict(
+    "_RequiredExportThemesRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
-_OptionalListFormsRequestRequestTypeDef = TypedDict(
-    "_OptionalListFormsRequestRequestTypeDef",
+_OptionalExportThemesRequestRequestTypeDef = TypedDict(
+    "_OptionalExportThemesRequestRequestTypeDef",
     {
-        "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
-class ListFormsRequestRequestTypeDef(
-    _RequiredListFormsRequestRequestTypeDef, _OptionalListFormsRequestRequestTypeDef
+class ExportThemesRequestRequestTypeDef(
+    _RequiredExportThemesRequestRequestTypeDef, _OptionalExportThemesRequestRequestTypeDef
 ):
     pass
 
-
-_RequiredListThemesRequestRequestTypeDef = TypedDict(
-    "_RequiredListThemesRequestRequestTypeDef",
+ExportThemesResponseTypeDef = TypedDict(
+    "ExportThemesResponseTypeDef",
     {
-        "appId": str,
-        "environmentName": str,
+        "entities": List["ThemeTypeDef"],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListThemesRequestRequestTypeDef = TypedDict(
-    "_OptionalListThemesRequestRequestTypeDef",
+
+FieldConfigTypeDef = TypedDict(
+    "FieldConfigTypeDef",
     {
-        "maxResults": int,
-        "nextToken": str,
+        "label": str,
+        "position": "FieldPositionTypeDef",
+        "excluded": bool,
+        "inputType": "FieldInputConfigTypeDef",
+        "validations": Sequence["FieldValidationConfigurationTypeDef"],
     },
     total=False,
 )
 
-
-class ListThemesRequestRequestTypeDef(
-    _RequiredListThemesRequestRequestTypeDef, _OptionalListThemesRequestRequestTypeDef
-):
-    pass
-
-
-ThemeSummaryTypeDef = TypedDict(
-    "ThemeSummaryTypeDef",
+_RequiredFieldInputConfigTypeDef = TypedDict(
+    "_RequiredFieldInputConfigTypeDef",
     {
-        "appId": str,
-        "environmentName": str,
-        "id": str,
-        "name": str,
+        "type": str,
     },
 )
-
-PredicateTypeDef = TypedDict(
-    "PredicateTypeDef",
+_OptionalFieldInputConfigTypeDef = TypedDict(
+    "_OptionalFieldInputConfigTypeDef",
     {
-        "and": Sequence[Dict[str, Any]],
-        "field": str,
-        "operand": str,
-        "operator": str,
-        "or": Sequence[Dict[str, Any]],
+        "required": bool,
+        "readOnly": bool,
+        "placeholder": str,
+        "defaultValue": str,
+        "descriptiveText": str,
+        "defaultChecked": bool,
+        "defaultCountryCode": str,
+        "valueMappings": "ValueMappingsTypeDef",
+        "name": str,
+        "minValue": float,
+        "maxValue": float,
+        "step": float,
+        "value": str,
+        "isArray": bool,
+        "fileUploaderConfig": "FileUploaderFieldConfigTypeDef",
     },
     total=False,
 )
 
-PutMetadataFlagBodyTypeDef = TypedDict(
-    "PutMetadataFlagBodyTypeDef",
-    {
-        "newValue": str,
-    },
-)
+class FieldInputConfigTypeDef(_RequiredFieldInputConfigTypeDef, _OptionalFieldInputConfigTypeDef):
+    pass
 
-RefreshTokenRequestBodyTypeDef = TypedDict(
-    "RefreshTokenRequestBodyTypeDef",
+FieldPositionTypeDef = TypedDict(
+    "FieldPositionTypeDef",
     {
-        "token": str,
+        "fixed": Literal["first"],
+        "rightOf": str,
+        "below": str,
     },
+    total=False,
 )
 
-ThemeValueTypeDef = TypedDict(
-    "ThemeValueTypeDef",
+_RequiredFieldValidationConfigurationTypeDef = TypedDict(
+    "_RequiredFieldValidationConfigurationTypeDef",
     {
-        "children": Sequence[Dict[str, Any]],
-        "value": str,
+        "type": str,
     },
-    total=False,
 )
-
-ThemeValuesTypeDef = TypedDict(
-    "ThemeValuesTypeDef",
+_OptionalFieldValidationConfigurationTypeDef = TypedDict(
+    "_OptionalFieldValidationConfigurationTypeDef",
     {
-        "key": str,
-        "value": Dict[str, Any],
+        "strValues": Sequence[str],
+        "numValues": Sequence[int],
+        "validationMessage": str,
     },
     total=False,
 )
 
-_RequiredUpdateThemeDataTypeDef = TypedDict(
-    "_RequiredUpdateThemeDataTypeDef",
+class FieldValidationConfigurationTypeDef(
+    _RequiredFieldValidationConfigurationTypeDef, _OptionalFieldValidationConfigurationTypeDef
+):
+    pass
+
+_RequiredFileUploaderFieldConfigTypeDef = TypedDict(
+    "_RequiredFileUploaderFieldConfigTypeDef",
     {
-        "values": Sequence["ThemeValuesTypeDef"],
+        "accessLevel": StorageAccessLevelType,
+        "acceptedFileTypes": Sequence[str],
     },
 )
-_OptionalUpdateThemeDataTypeDef = TypedDict(
-    "_OptionalUpdateThemeDataTypeDef",
+_OptionalFileUploaderFieldConfigTypeDef = TypedDict(
+    "_OptionalFileUploaderFieldConfigTypeDef",
     {
-        "id": str,
-        "name": str,
-        "overrides": Sequence["ThemeValuesTypeDef"],
+        "showThumbnails": bool,
+        "isResumable": bool,
+        "maxFileCount": int,
+        "maxSize": int,
     },
     total=False,
 )
 
-
-class UpdateThemeDataTypeDef(_RequiredUpdateThemeDataTypeDef, _OptionalUpdateThemeDataTypeDef):
+class FileUploaderFieldConfigTypeDef(
+    _RequiredFileUploaderFieldConfigTypeDef, _OptionalFileUploaderFieldConfigTypeDef
+):
     pass
 
+FormBindingElementTypeDef = TypedDict(
+    "FormBindingElementTypeDef",
+    {
+        "element": str,
+        "property": str,
+    },
+)
 
-ActionParametersTypeDef = TypedDict(
-    "ActionParametersTypeDef",
+FormButtonTypeDef = TypedDict(
+    "FormButtonTypeDef",
     {
-        "anchor": "ComponentPropertyTypeDef",
-        "fields": Mapping[str, "ComponentPropertyTypeDef"],
-        "global": "ComponentPropertyTypeDef",
-        "id": "ComponentPropertyTypeDef",
-        "model": str,
-        "state": MutationActionSetStateParameterTypeDef,
-        "target": "ComponentPropertyTypeDef",
-        "type": "ComponentPropertyTypeDef",
-        "url": "ComponentPropertyTypeDef",
+        "excluded": bool,
+        "children": str,
+        "position": "FieldPositionTypeDef",
     },
     total=False,
 )
 
-ComponentBindingPropertiesValueTypeDef = TypedDict(
-    "ComponentBindingPropertiesValueTypeDef",
+FormCTATypeDef = TypedDict(
+    "FormCTATypeDef",
     {
-        "bindingProperties": ComponentBindingPropertiesValuePropertiesTypeDef,
-        "defaultValue": str,
-        "type": str,
+        "position": FormButtonsPositionType,
+        "clear": "FormButtonTypeDef",
+        "cancel": "FormButtonTypeDef",
+        "submit": "FormButtonTypeDef",
     },
     total=False,
 )
 
-_RequiredComponentDataConfigurationTypeDef = TypedDict(
-    "_RequiredComponentDataConfigurationTypeDef",
+FormDataTypeConfigTypeDef = TypedDict(
+    "FormDataTypeConfigTypeDef",
     {
-        "model": str,
+        "dataSourceType": FormDataSourceTypeType,
+        "dataTypeName": str,
     },
 )
-_OptionalComponentDataConfigurationTypeDef = TypedDict(
-    "_OptionalComponentDataConfigurationTypeDef",
+
+FormInputBindingPropertiesValuePropertiesTypeDef = TypedDict(
+    "FormInputBindingPropertiesValuePropertiesTypeDef",
     {
-        "identifiers": Sequence[str],
-        "predicate": "PredicateTypeDef",
-        "sort": Sequence[SortPropertyTypeDef],
+        "model": str,
     },
     total=False,
 )
 
-
-class ComponentDataConfigurationTypeDef(
-    _RequiredComponentDataConfigurationTypeDef, _OptionalComponentDataConfigurationTypeDef
-):
-    pass
-
-
-ComponentPropertyTypeDef = TypedDict(
-    "ComponentPropertyTypeDef",
+FormInputBindingPropertiesValueTypeDef = TypedDict(
+    "FormInputBindingPropertiesValueTypeDef",
     {
-        "bindingProperties": ComponentPropertyBindingPropertiesTypeDef,
-        "bindings": Mapping[str, FormBindingElementTypeDef],
-        "collectionBindingProperties": ComponentPropertyBindingPropertiesTypeDef,
-        "componentName": str,
-        "concat": Sequence[Dict[str, Any]],
-        "condition": Dict[str, Any],
-        "configured": bool,
-        "defaultValue": str,
-        "event": str,
-        "importedValue": str,
-        "model": str,
-        "property": str,
         "type": str,
-        "userAttribute": str,
-        "value": str,
+        "bindingProperties": "FormInputBindingPropertiesValuePropertiesTypeDef",
     },
     total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+_RequiredFormInputValuePropertyBindingPropertiesTypeDef = TypedDict(
+    "_RequiredFormInputValuePropertyBindingPropertiesTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "property": str,
     },
 )
-
-ExchangeCodeForTokenResponseTypeDef = TypedDict(
-    "ExchangeCodeForTokenResponseTypeDef",
+_OptionalFormInputValuePropertyBindingPropertiesTypeDef = TypedDict(
+    "_OptionalFormInputValuePropertyBindingPropertiesTypeDef",
     {
-        "accessToken": str,
-        "expiresIn": int,
-        "refreshToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "field": str,
     },
+    total=False,
 )
 
-GetMetadataResponseTypeDef = TypedDict(
-    "GetMetadataResponseTypeDef",
+class FormInputValuePropertyBindingPropertiesTypeDef(
+    _RequiredFormInputValuePropertyBindingPropertiesTypeDef,
+    _OptionalFormInputValuePropertyBindingPropertiesTypeDef,
+):
+    pass
+
+FormInputValuePropertyTypeDef = TypedDict(
+    "FormInputValuePropertyTypeDef",
     {
-        "features": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "value": str,
+        "bindingProperties": "FormInputValuePropertyBindingPropertiesTypeDef",
+        "concat": Sequence[Dict[str, Any]],
     },
+    total=False,
 )
 
-ListComponentsResponseTypeDef = TypedDict(
-    "ListComponentsResponseTypeDef",
+FormStyleConfigTypeDef = TypedDict(
+    "FormStyleConfigTypeDef",
     {
-        "entities": List[ComponentSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "tokenReference": str,
+        "value": str,
     },
+    total=False,
 )
 
-RefreshTokenResponseTypeDef = TypedDict(
-    "RefreshTokenResponseTypeDef",
+FormStyleTypeDef = TypedDict(
+    "FormStyleTypeDef",
     {
-        "accessToken": str,
-        "expiresIn": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "horizontalGap": "FormStyleConfigTypeDef",
+        "verticalGap": "FormStyleConfigTypeDef",
+        "outerPadding": "FormStyleConfigTypeDef",
     },
+    total=False,
 )
 
 FormSummaryTypeDef = TypedDict(
     "FormSummaryTypeDef",
     {
         "appId": str,
-        "dataType": FormDataTypeConfigTypeDef,
+        "dataType": "FormDataTypeConfigTypeDef",
         "environmentName": str,
         "formActionType": FormActionTypeType,
         "id": str,
         "name": str,
     },
 )
 
-_RequiredCreateThemeRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateThemeRequestRequestTypeDef",
+_RequiredFormTypeDef = TypedDict(
+    "_RequiredFormTypeDef",
     {
         "appId": str,
         "environmentName": str,
-        "themeToCreate": CreateThemeDataTypeDef,
+        "id": str,
+        "name": str,
+        "formActionType": FormActionTypeType,
+        "style": "FormStyleTypeDef",
+        "dataType": "FormDataTypeConfigTypeDef",
+        "fields": Dict[str, "FieldConfigTypeDef"],
+        "sectionalElements": Dict[str, "SectionalElementTypeDef"],
+        "schemaVersion": str,
     },
 )
-_OptionalCreateThemeRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateThemeRequestRequestTypeDef",
+_OptionalFormTypeDef = TypedDict(
+    "_OptionalFormTypeDef",
     {
-        "clientToken": str,
+        "tags": Dict[str, str],
+        "cta": "FormCTATypeDef",
+        "labelDecorator": LabelDecoratorType,
     },
     total=False,
 )
 
-
-class CreateThemeRequestRequestTypeDef(
-    _RequiredCreateThemeRequestRequestTypeDef, _OptionalCreateThemeRequestRequestTypeDef
-):
+class FormTypeDef(_RequiredFormTypeDef, _OptionalFormTypeDef):
     pass
 
+GetCodegenJobRequestRequestTypeDef = TypedDict(
+    "GetCodegenJobRequestRequestTypeDef",
+    {
+        "appId": str,
+        "environmentName": str,
+        "id": str,
+    },
+)
 
-CreateThemeResponseTypeDef = TypedDict(
-    "CreateThemeResponseTypeDef",
+GetCodegenJobResponseTypeDef = TypedDict(
+    "GetCodegenJobResponseTypeDef",
     {
-        "entity": ThemeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "job": "CodegenJobTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ExportThemesResponseTypeDef = TypedDict(
-    "ExportThemesResponseTypeDef",
+GetComponentRequestRequestTypeDef = TypedDict(
+    "GetComponentRequestRequestTypeDef",
     {
-        "entities": List[ThemeTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "appId": str,
+        "environmentName": str,
+        "id": str,
     },
 )
 
-GetThemeResponseTypeDef = TypedDict(
-    "GetThemeResponseTypeDef",
+GetComponentResponseTypeDef = TypedDict(
+    "GetComponentResponseTypeDef",
     {
-        "theme": ThemeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "component": "ComponentTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateThemeResponseTypeDef = TypedDict(
-    "UpdateThemeResponseTypeDef",
+GetFormRequestRequestTypeDef = TypedDict(
+    "GetFormRequestRequestTypeDef",
     {
-        "entity": ThemeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "appId": str,
+        "environmentName": str,
+        "id": str,
     },
 )
 
-ExchangeCodeForTokenRequestRequestTypeDef = TypedDict(
-    "ExchangeCodeForTokenRequestRequestTypeDef",
+GetFormResponseTypeDef = TypedDict(
+    "GetFormResponseTypeDef",
     {
-        "provider": Literal["figma"],
-        "request": ExchangeCodeForTokenRequestBodyTypeDef,
+        "form": "FormTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredExportComponentsRequestExportComponentsPaginateTypeDef = TypedDict(
-    "_RequiredExportComponentsRequestExportComponentsPaginateTypeDef",
+GetMetadataRequestRequestTypeDef = TypedDict(
+    "GetMetadataRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
-_OptionalExportComponentsRequestExportComponentsPaginateTypeDef = TypedDict(
-    "_OptionalExportComponentsRequestExportComponentsPaginateTypeDef",
+
+GetMetadataResponseTypeDef = TypedDict(
+    "GetMetadataResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "features": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
+GetThemeRequestRequestTypeDef = TypedDict(
+    "GetThemeRequestRequestTypeDef",
+    {
+        "appId": str,
+        "environmentName": str,
+        "id": str,
+    },
+)
 
-class ExportComponentsRequestExportComponentsPaginateTypeDef(
-    _RequiredExportComponentsRequestExportComponentsPaginateTypeDef,
-    _OptionalExportComponentsRequestExportComponentsPaginateTypeDef,
-):
-    pass
-
+GetThemeResponseTypeDef = TypedDict(
+    "GetThemeResponseTypeDef",
+    {
+        "theme": "ThemeTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-_RequiredExportFormsRequestExportFormsPaginateTypeDef = TypedDict(
-    "_RequiredExportFormsRequestExportFormsPaginateTypeDef",
+_RequiredListCodegenJobsRequestListCodegenJobsPaginateTypeDef = TypedDict(
+    "_RequiredListCodegenJobsRequestListCodegenJobsPaginateTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
-_OptionalExportFormsRequestExportFormsPaginateTypeDef = TypedDict(
-    "_OptionalExportFormsRequestExportFormsPaginateTypeDef",
+_OptionalListCodegenJobsRequestListCodegenJobsPaginateTypeDef = TypedDict(
+    "_OptionalListCodegenJobsRequestListCodegenJobsPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
-class ExportFormsRequestExportFormsPaginateTypeDef(
-    _RequiredExportFormsRequestExportFormsPaginateTypeDef,
-    _OptionalExportFormsRequestExportFormsPaginateTypeDef,
+class ListCodegenJobsRequestListCodegenJobsPaginateTypeDef(
+    _RequiredListCodegenJobsRequestListCodegenJobsPaginateTypeDef,
+    _OptionalListCodegenJobsRequestListCodegenJobsPaginateTypeDef,
 ):
     pass
 
-
-_RequiredExportThemesRequestExportThemesPaginateTypeDef = TypedDict(
-    "_RequiredExportThemesRequestExportThemesPaginateTypeDef",
+_RequiredListCodegenJobsRequestRequestTypeDef = TypedDict(
+    "_RequiredListCodegenJobsRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
-_OptionalExportThemesRequestExportThemesPaginateTypeDef = TypedDict(
-    "_OptionalExportThemesRequestExportThemesPaginateTypeDef",
+_OptionalListCodegenJobsRequestRequestTypeDef = TypedDict(
+    "_OptionalListCodegenJobsRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "nextToken": str,
+        "maxResults": int,
     },
     total=False,
 )
 
-
-class ExportThemesRequestExportThemesPaginateTypeDef(
-    _RequiredExportThemesRequestExportThemesPaginateTypeDef,
-    _OptionalExportThemesRequestExportThemesPaginateTypeDef,
+class ListCodegenJobsRequestRequestTypeDef(
+    _RequiredListCodegenJobsRequestRequestTypeDef, _OptionalListCodegenJobsRequestRequestTypeDef
 ):
     pass
 
+ListCodegenJobsResponseTypeDef = TypedDict(
+    "ListCodegenJobsResponseTypeDef",
+    {
+        "entities": List["CodegenJobSummaryTypeDef"],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredListComponentsRequestListComponentsPaginateTypeDef = TypedDict(
     "_RequiredListComponentsRequestListComponentsPaginateTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
 _OptionalListComponentsRequestListComponentsPaginateTypeDef = TypedDict(
     "_OptionalListComponentsRequestListComponentsPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class ListComponentsRequestListComponentsPaginateTypeDef(
     _RequiredListComponentsRequestListComponentsPaginateTypeDef,
     _OptionalListComponentsRequestListComponentsPaginateTypeDef,
 ):
     pass
 
+_RequiredListComponentsRequestRequestTypeDef = TypedDict(
+    "_RequiredListComponentsRequestRequestTypeDef",
+    {
+        "appId": str,
+        "environmentName": str,
+    },
+)
+_OptionalListComponentsRequestRequestTypeDef = TypedDict(
+    "_OptionalListComponentsRequestRequestTypeDef",
+    {
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+class ListComponentsRequestRequestTypeDef(
+    _RequiredListComponentsRequestRequestTypeDef, _OptionalListComponentsRequestRequestTypeDef
+):
+    pass
+
+ListComponentsResponseTypeDef = TypedDict(
+    "ListComponentsResponseTypeDef",
+    {
+        "entities": List["ComponentSummaryTypeDef"],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredListFormsRequestListFormsPaginateTypeDef = TypedDict(
     "_RequiredListFormsRequestListFormsPaginateTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
 _OptionalListFormsRequestListFormsPaginateTypeDef = TypedDict(
     "_OptionalListFormsRequestListFormsPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class ListFormsRequestListFormsPaginateTypeDef(
     _RequiredListFormsRequestListFormsPaginateTypeDef,
     _OptionalListFormsRequestListFormsPaginateTypeDef,
 ):
     pass
 
+_RequiredListFormsRequestRequestTypeDef = TypedDict(
+    "_RequiredListFormsRequestRequestTypeDef",
+    {
+        "appId": str,
+        "environmentName": str,
+    },
+)
+_OptionalListFormsRequestRequestTypeDef = TypedDict(
+    "_OptionalListFormsRequestRequestTypeDef",
+    {
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+class ListFormsRequestRequestTypeDef(
+    _RequiredListFormsRequestRequestTypeDef, _OptionalListFormsRequestRequestTypeDef
+):
+    pass
+
+ListFormsResponseTypeDef = TypedDict(
+    "ListFormsResponseTypeDef",
+    {
+        "entities": List["FormSummaryTypeDef"],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredListThemesRequestListThemesPaginateTypeDef = TypedDict(
     "_RequiredListThemesRequestListThemesPaginateTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
 _OptionalListThemesRequestListThemesPaginateTypeDef = TypedDict(
     "_OptionalListThemesRequestListThemesPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class ListThemesRequestListThemesPaginateTypeDef(
     _RequiredListThemesRequestListThemesPaginateTypeDef,
     _OptionalListThemesRequestListThemesPaginateTypeDef,
 ):
     pass
 
-
-FormButtonTypeDef = TypedDict(
-    "FormButtonTypeDef",
-    {
-        "children": str,
-        "excluded": bool,
-        "position": FieldPositionTypeDef,
-    },
-    total=False,
-)
-
-_RequiredSectionalElementTypeDef = TypedDict(
-    "_RequiredSectionalElementTypeDef",
+_RequiredListThemesRequestRequestTypeDef = TypedDict(
+    "_RequiredListThemesRequestRequestTypeDef",
     {
-        "type": str,
+        "appId": str,
+        "environmentName": str,
     },
 )
-_OptionalSectionalElementTypeDef = TypedDict(
-    "_OptionalSectionalElementTypeDef",
+_OptionalListThemesRequestRequestTypeDef = TypedDict(
+    "_OptionalListThemesRequestRequestTypeDef",
     {
-        "level": int,
-        "orientation": str,
-        "position": FieldPositionTypeDef,
-        "text": str,
+        "nextToken": str,
+        "maxResults": int,
     },
     total=False,
 )
 
-
-class SectionalElementTypeDef(_RequiredSectionalElementTypeDef, _OptionalSectionalElementTypeDef):
+class ListThemesRequestRequestTypeDef(
+    _RequiredListThemesRequestRequestTypeDef, _OptionalListThemesRequestRequestTypeDef
+):
     pass
 
+ListThemesResponseTypeDef = TypedDict(
+    "ListThemesResponseTypeDef",
+    {
+        "entities": List["ThemeSummaryTypeDef"],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-_RequiredValueMappingTypeDef = TypedDict(
-    "_RequiredValueMappingTypeDef",
+MutationActionSetStateParameterTypeDef = TypedDict(
+    "MutationActionSetStateParameterTypeDef",
     {
-        "value": FormInputValuePropertyTypeDef,
+        "componentName": str,
+        "property": str,
+        "set": "ComponentPropertyTypeDef",
     },
 )
-_OptionalValueMappingTypeDef = TypedDict(
-    "_OptionalValueMappingTypeDef",
+
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "displayValue": FormInputValuePropertyTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
     total=False,
 )
 
-
-class ValueMappingTypeDef(_RequiredValueMappingTypeDef, _OptionalValueMappingTypeDef):
-    pass
-
-
-FormStyleTypeDef = TypedDict(
-    "FormStyleTypeDef",
+PredicateTypeDef = TypedDict(
+    "PredicateTypeDef",
     {
-        "horizontalGap": FormStyleConfigTypeDef,
-        "outerPadding": FormStyleConfigTypeDef,
-        "verticalGap": FormStyleConfigTypeDef,
+        "or": Sequence[Dict[str, Any]],
+        "and": Sequence[Dict[str, Any]],
+        "field": str,
+        "operator": str,
+        "operand": str,
+        "operandType": str,
     },
     total=False,
 )
 
-ListThemesResponseTypeDef = TypedDict(
-    "ListThemesResponseTypeDef",
+PutMetadataFlagBodyTypeDef = TypedDict(
+    "PutMetadataFlagBodyTypeDef",
     {
-        "entities": List[ThemeSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "newValue": str,
     },
 )
 
 PutMetadataFlagRequestRequestTypeDef = TypedDict(
     "PutMetadataFlagRequestRequestTypeDef",
     {
         "appId": str,
-        "body": PutMetadataFlagBodyTypeDef,
         "environmentName": str,
         "featureName": str,
+        "body": "PutMetadataFlagBodyTypeDef",
     },
 )
 
-RefreshTokenRequestRequestTypeDef = TypedDict(
-    "RefreshTokenRequestRequestTypeDef",
+ReactStartCodegenJobDataTypeDef = TypedDict(
+    "ReactStartCodegenJobDataTypeDef",
     {
-        "provider": Literal["figma"],
-        "refreshTokenBody": RefreshTokenRequestBodyTypeDef,
+        "module": JSModuleType,
+        "target": JSTargetType,
+        "script": JSScriptType,
+        "renderTypeDeclarations": bool,
+        "inlineSourceMap": bool,
     },
+    total=False,
 )
 
-_RequiredUpdateThemeRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateThemeRequestRequestTypeDef",
+_RequiredRefreshTokenRequestBodyTypeDef = TypedDict(
+    "_RequiredRefreshTokenRequestBodyTypeDef",
     {
-        "appId": str,
-        "environmentName": str,
-        "id": str,
-        "updatedTheme": UpdateThemeDataTypeDef,
+        "token": str,
     },
 )
-_OptionalUpdateThemeRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateThemeRequestRequestTypeDef",
+_OptionalRefreshTokenRequestBodyTypeDef = TypedDict(
+    "_OptionalRefreshTokenRequestBodyTypeDef",
     {
-        "clientToken": str,
+        "clientId": str,
     },
     total=False,
 )
 
-
-class UpdateThemeRequestRequestTypeDef(
-    _RequiredUpdateThemeRequestRequestTypeDef, _OptionalUpdateThemeRequestRequestTypeDef
+class RefreshTokenRequestBodyTypeDef(
+    _RequiredRefreshTokenRequestBodyTypeDef, _OptionalRefreshTokenRequestBodyTypeDef
 ):
     pass
 
-
-ComponentEventTypeDef = TypedDict(
-    "ComponentEventTypeDef",
-    {
-        "action": str,
-        "bindingEvent": str,
-        "parameters": ActionParametersTypeDef,
-    },
-    total=False,
-)
-
-ListFormsResponseTypeDef = TypedDict(
-    "ListFormsResponseTypeDef",
+RefreshTokenRequestRequestTypeDef = TypedDict(
+    "RefreshTokenRequestRequestTypeDef",
     {
-        "entities": List[FormSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "provider": Literal["figma"],
+        "refreshTokenBody": "RefreshTokenRequestBodyTypeDef",
     },
 )
 
-FormCTATypeDef = TypedDict(
-    "FormCTATypeDef",
+RefreshTokenResponseTypeDef = TypedDict(
+    "RefreshTokenResponseTypeDef",
     {
-        "cancel": FormButtonTypeDef,
-        "clear": FormButtonTypeDef,
-        "position": FormButtonsPositionType,
-        "submit": FormButtonTypeDef,
+        "accessToken": str,
+        "expiresIn": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ValueMappingsTypeDef = TypedDict(
-    "ValueMappingsTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "values": Sequence[ValueMappingTypeDef],
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-_RequiredComponentChildTypeDef = TypedDict(
-    "_RequiredComponentChildTypeDef",
+_RequiredSectionalElementTypeDef = TypedDict(
+    "_RequiredSectionalElementTypeDef",
     {
-        "componentType": str,
-        "name": str,
-        "properties": Mapping[str, "ComponentPropertyTypeDef"],
+        "type": str,
     },
 )
-_OptionalComponentChildTypeDef = TypedDict(
-    "_OptionalComponentChildTypeDef",
+_OptionalSectionalElementTypeDef = TypedDict(
+    "_OptionalSectionalElementTypeDef",
     {
-        "children": Sequence[Dict[str, Any]],
-        "events": Mapping[str, ComponentEventTypeDef],
-        "sourceId": str,
+        "position": "FieldPositionTypeDef",
+        "text": str,
+        "level": int,
+        "orientation": str,
+        "excluded": bool,
     },
     total=False,
 )
 
-
-class ComponentChildTypeDef(_RequiredComponentChildTypeDef, _OptionalComponentChildTypeDef):
+class SectionalElementTypeDef(_RequiredSectionalElementTypeDef, _OptionalSectionalElementTypeDef):
     pass
 
+SortPropertyTypeDef = TypedDict(
+    "SortPropertyTypeDef",
+    {
+        "field": str,
+        "direction": SortDirectionType,
+    },
+)
 
-_RequiredComponentTypeDef = TypedDict(
-    "_RequiredComponentTypeDef",
+_RequiredStartCodegenJobDataTypeDef = TypedDict(
+    "_RequiredStartCodegenJobDataTypeDef",
     {
-        "appId": str,
-        "bindingProperties": Dict[str, ComponentBindingPropertiesValueTypeDef],
-        "componentType": str,
-        "createdAt": datetime,
-        "environmentName": str,
-        "id": str,
-        "name": str,
-        "overrides": Dict[str, Dict[str, str]],
-        "properties": Dict[str, "ComponentPropertyTypeDef"],
-        "variants": List[ComponentVariantTypeDef],
+        "renderConfig": "CodegenJobRenderConfigTypeDef",
     },
 )
-_OptionalComponentTypeDef = TypedDict(
-    "_OptionalComponentTypeDef",
+_OptionalStartCodegenJobDataTypeDef = TypedDict(
+    "_OptionalStartCodegenJobDataTypeDef",
     {
-        "children": List["ComponentChildTypeDef"],
-        "collectionProperties": Dict[str, ComponentDataConfigurationTypeDef],
-        "events": Dict[str, ComponentEventTypeDef],
-        "modifiedAt": datetime,
-        "schemaVersion": str,
-        "sourceId": str,
-        "tags": Dict[str, str],
+        "genericDataSchema": "CodegenJobGenericDataSchemaTypeDef",
+        "autoGenerateForms": bool,
+        "features": "CodegenFeatureFlagsTypeDef",
+        "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
-class ComponentTypeDef(_RequiredComponentTypeDef, _OptionalComponentTypeDef):
+class StartCodegenJobDataTypeDef(
+    _RequiredStartCodegenJobDataTypeDef, _OptionalStartCodegenJobDataTypeDef
+):
     pass
 
-
-_RequiredCreateComponentDataTypeDef = TypedDict(
-    "_RequiredCreateComponentDataTypeDef",
+_RequiredStartCodegenJobRequestRequestTypeDef = TypedDict(
+    "_RequiredStartCodegenJobRequestRequestTypeDef",
     {
-        "bindingProperties": Mapping[str, ComponentBindingPropertiesValueTypeDef],
-        "componentType": str,
-        "name": str,
-        "overrides": Mapping[str, Mapping[str, str]],
-        "properties": Mapping[str, "ComponentPropertyTypeDef"],
-        "variants": Sequence[ComponentVariantTypeDef],
+        "appId": str,
+        "environmentName": str,
+        "codegenJobToCreate": "StartCodegenJobDataTypeDef",
     },
 )
-_OptionalCreateComponentDataTypeDef = TypedDict(
-    "_OptionalCreateComponentDataTypeDef",
+_OptionalStartCodegenJobRequestRequestTypeDef = TypedDict(
+    "_OptionalStartCodegenJobRequestRequestTypeDef",
     {
-        "children": Sequence["ComponentChildTypeDef"],
-        "collectionProperties": Mapping[str, ComponentDataConfigurationTypeDef],
-        "events": Mapping[str, ComponentEventTypeDef],
-        "schemaVersion": str,
-        "sourceId": str,
-        "tags": Mapping[str, str],
+        "clientToken": str,
     },
     total=False,
 )
 
-
-class CreateComponentDataTypeDef(
-    _RequiredCreateComponentDataTypeDef, _OptionalCreateComponentDataTypeDef
+class StartCodegenJobRequestRequestTypeDef(
+    _RequiredStartCodegenJobRequestRequestTypeDef, _OptionalStartCodegenJobRequestRequestTypeDef
 ):
     pass
 
+StartCodegenJobResponseTypeDef = TypedDict(
+    "StartCodegenJobResponseTypeDef",
+    {
+        "entity": "CodegenJobTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-UpdateComponentDataTypeDef = TypedDict(
-    "UpdateComponentDataTypeDef",
+ThemeSummaryTypeDef = TypedDict(
+    "ThemeSummaryTypeDef",
     {
-        "bindingProperties": Mapping[str, ComponentBindingPropertiesValueTypeDef],
-        "children": Sequence["ComponentChildTypeDef"],
-        "collectionProperties": Mapping[str, ComponentDataConfigurationTypeDef],
-        "componentType": str,
-        "events": Mapping[str, ComponentEventTypeDef],
+        "appId": str,
+        "environmentName": str,
         "id": str,
         "name": str,
-        "overrides": Mapping[str, Mapping[str, str]],
-        "properties": Mapping[str, "ComponentPropertyTypeDef"],
-        "schemaVersion": str,
-        "sourceId": str,
-        "variants": Sequence[ComponentVariantTypeDef],
     },
-    total=False,
 )
 
-_RequiredFieldInputConfigTypeDef = TypedDict(
-    "_RequiredFieldInputConfigTypeDef",
+_RequiredThemeTypeDef = TypedDict(
+    "_RequiredThemeTypeDef",
     {
-        "type": str,
+        "appId": str,
+        "environmentName": str,
+        "id": str,
+        "name": str,
+        "createdAt": datetime,
+        "values": List["ThemeValuesTypeDef"],
     },
 )
-_OptionalFieldInputConfigTypeDef = TypedDict(
-    "_OptionalFieldInputConfigTypeDef",
+_OptionalThemeTypeDef = TypedDict(
+    "_OptionalThemeTypeDef",
     {
-        "defaultChecked": bool,
-        "defaultCountryCode": str,
-        "defaultValue": str,
-        "descriptiveText": str,
-        "isArray": bool,
-        "maxValue": float,
-        "minValue": float,
-        "name": str,
-        "placeholder": str,
-        "readOnly": bool,
-        "required": bool,
-        "step": float,
-        "value": str,
-        "valueMappings": ValueMappingsTypeDef,
+        "modifiedAt": datetime,
+        "overrides": List["ThemeValuesTypeDef"],
+        "tags": Dict[str, str],
     },
     total=False,
 )
 
-
-class FieldInputConfigTypeDef(_RequiredFieldInputConfigTypeDef, _OptionalFieldInputConfigTypeDef):
+class ThemeTypeDef(_RequiredThemeTypeDef, _OptionalThemeTypeDef):
     pass
 
-
-CreateComponentResponseTypeDef = TypedDict(
-    "CreateComponentResponseTypeDef",
-    {
-        "entity": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExportComponentsResponseTypeDef = TypedDict(
-    "ExportComponentsResponseTypeDef",
-    {
-        "entities": List[ComponentTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetComponentResponseTypeDef = TypedDict(
-    "GetComponentResponseTypeDef",
+ThemeValueTypeDef = TypedDict(
+    "ThemeValueTypeDef",
     {
-        "component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "value": str,
+        "children": Sequence[Dict[str, Any]],
     },
+    total=False,
 )
 
-UpdateComponentResponseTypeDef = TypedDict(
-    "UpdateComponentResponseTypeDef",
+ThemeValuesTypeDef = TypedDict(
+    "ThemeValuesTypeDef",
     {
-        "entity": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "key": str,
+        "value": Dict[str, Any],
     },
+    total=False,
 )
 
-_RequiredCreateComponentRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateComponentRequestRequestTypeDef",
-    {
-        "appId": str,
-        "componentToCreate": CreateComponentDataTypeDef,
-        "environmentName": str,
-    },
-)
-_OptionalCreateComponentRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateComponentRequestRequestTypeDef",
+UpdateComponentDataTypeDef = TypedDict(
+    "UpdateComponentDataTypeDef",
     {
-        "clientToken": str,
+        "id": str,
+        "name": str,
+        "sourceId": str,
+        "componentType": str,
+        "properties": Mapping[str, "ComponentPropertyTypeDef"],
+        "children": Sequence["ComponentChildTypeDef"],
+        "variants": Sequence["ComponentVariantTypeDef"],
+        "overrides": Mapping[str, Mapping[str, str]],
+        "bindingProperties": Mapping[str, "ComponentBindingPropertiesValueTypeDef"],
+        "collectionProperties": Mapping[str, "ComponentDataConfigurationTypeDef"],
+        "events": Mapping[str, "ComponentEventTypeDef"],
+        "schemaVersion": str,
     },
     total=False,
 )
 
-
-class CreateComponentRequestRequestTypeDef(
-    _RequiredCreateComponentRequestRequestTypeDef, _OptionalCreateComponentRequestRequestTypeDef
-):
-    pass
-
-
 _RequiredUpdateComponentRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateComponentRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
         "id": str,
-        "updatedComponent": UpdateComponentDataTypeDef,
+        "updatedComponent": "UpdateComponentDataTypeDef",
     },
 )
 _OptionalUpdateComponentRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateComponentRequestRequestTypeDef",
     {
         "clientToken": str,
     },
     total=False,
 )
 
-
 class UpdateComponentRequestRequestTypeDef(
     _RequiredUpdateComponentRequestRequestTypeDef, _OptionalUpdateComponentRequestRequestTypeDef
 ):
     pass
 
-
-FieldConfigTypeDef = TypedDict(
-    "FieldConfigTypeDef",
+UpdateComponentResponseTypeDef = TypedDict(
+    "UpdateComponentResponseTypeDef",
     {
-        "excluded": bool,
-        "inputType": FieldInputConfigTypeDef,
-        "label": str,
-        "position": FieldPositionTypeDef,
-        "validations": Sequence[FieldValidationConfigurationTypeDef],
+        "entity": "ComponentTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredCreateFormDataTypeDef = TypedDict(
-    "_RequiredCreateFormDataTypeDef",
+UpdateFormDataTypeDef = TypedDict(
+    "UpdateFormDataTypeDef",
     {
-        "dataType": FormDataTypeConfigTypeDef,
-        "fields": Mapping[str, FieldConfigTypeDef],
-        "formActionType": FormActionTypeType,
         "name": str,
+        "dataType": "FormDataTypeConfigTypeDef",
+        "formActionType": FormActionTypeType,
+        "fields": Mapping[str, "FieldConfigTypeDef"],
+        "style": "FormStyleTypeDef",
+        "sectionalElements": Mapping[str, "SectionalElementTypeDef"],
         "schemaVersion": str,
-        "sectionalElements": Mapping[str, SectionalElementTypeDef],
-        "style": FormStyleTypeDef,
-    },
-)
-_OptionalCreateFormDataTypeDef = TypedDict(
-    "_OptionalCreateFormDataTypeDef",
-    {
-        "cta": FormCTATypeDef,
-        "tags": Mapping[str, str],
+        "cta": "FormCTATypeDef",
+        "labelDecorator": LabelDecoratorType,
     },
     total=False,
 )
 
-
-class CreateFormDataTypeDef(_RequiredCreateFormDataTypeDef, _OptionalCreateFormDataTypeDef):
-    pass
-
-
-_RequiredFormTypeDef = TypedDict(
-    "_RequiredFormTypeDef",
+_RequiredUpdateFormRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateFormRequestRequestTypeDef",
     {
         "appId": str,
-        "dataType": FormDataTypeConfigTypeDef,
         "environmentName": str,
-        "fields": Dict[str, FieldConfigTypeDef],
-        "formActionType": FormActionTypeType,
         "id": str,
-        "name": str,
-        "schemaVersion": str,
-        "sectionalElements": Dict[str, SectionalElementTypeDef],
-        "style": FormStyleTypeDef,
+        "updatedForm": "UpdateFormDataTypeDef",
     },
 )
-_OptionalFormTypeDef = TypedDict(
-    "_OptionalFormTypeDef",
+_OptionalUpdateFormRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateFormRequestRequestTypeDef",
     {
-        "cta": FormCTATypeDef,
-        "tags": Dict[str, str],
+        "clientToken": str,
     },
     total=False,
 )
 
-
-class FormTypeDef(_RequiredFormTypeDef, _OptionalFormTypeDef):
+class UpdateFormRequestRequestTypeDef(
+    _RequiredUpdateFormRequestRequestTypeDef, _OptionalUpdateFormRequestRequestTypeDef
+):
     pass
 
+UpdateFormResponseTypeDef = TypedDict(
+    "UpdateFormResponseTypeDef",
+    {
+        "entity": "FormTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-UpdateFormDataTypeDef = TypedDict(
-    "UpdateFormDataTypeDef",
+_RequiredUpdateThemeDataTypeDef = TypedDict(
+    "_RequiredUpdateThemeDataTypeDef",
     {
-        "cta": FormCTATypeDef,
-        "dataType": FormDataTypeConfigTypeDef,
-        "fields": Mapping[str, FieldConfigTypeDef],
-        "formActionType": FormActionTypeType,
+        "values": Sequence["ThemeValuesTypeDef"],
+    },
+)
+_OptionalUpdateThemeDataTypeDef = TypedDict(
+    "_OptionalUpdateThemeDataTypeDef",
+    {
+        "id": str,
         "name": str,
-        "schemaVersion": str,
-        "sectionalElements": Mapping[str, SectionalElementTypeDef],
-        "style": FormStyleTypeDef,
+        "overrides": Sequence["ThemeValuesTypeDef"],
     },
     total=False,
 )
 
-_RequiredCreateFormRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateFormRequestRequestTypeDef",
+class UpdateThemeDataTypeDef(_RequiredUpdateThemeDataTypeDef, _OptionalUpdateThemeDataTypeDef):
+    pass
+
+_RequiredUpdateThemeRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateThemeRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
-        "formToCreate": CreateFormDataTypeDef,
+        "id": str,
+        "updatedTheme": "UpdateThemeDataTypeDef",
     },
 )
-_OptionalCreateFormRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateFormRequestRequestTypeDef",
+_OptionalUpdateThemeRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateThemeRequestRequestTypeDef",
     {
         "clientToken": str,
     },
     total=False,
 )
 
-
-class CreateFormRequestRequestTypeDef(
-    _RequiredCreateFormRequestRequestTypeDef, _OptionalCreateFormRequestRequestTypeDef
+class UpdateThemeRequestRequestTypeDef(
+    _RequiredUpdateThemeRequestRequestTypeDef, _OptionalUpdateThemeRequestRequestTypeDef
 ):
     pass
 
-
-CreateFormResponseTypeDef = TypedDict(
-    "CreateFormResponseTypeDef",
+UpdateThemeResponseTypeDef = TypedDict(
+    "UpdateThemeResponseTypeDef",
     {
-        "entity": FormTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "entity": "ThemeTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ExportFormsResponseTypeDef = TypedDict(
-    "ExportFormsResponseTypeDef",
+_RequiredValueMappingTypeDef = TypedDict(
+    "_RequiredValueMappingTypeDef",
     {
-        "entities": List[FormTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "value": "FormInputValuePropertyTypeDef",
     },
 )
-
-GetFormResponseTypeDef = TypedDict(
-    "GetFormResponseTypeDef",
+_OptionalValueMappingTypeDef = TypedDict(
+    "_OptionalValueMappingTypeDef",
     {
-        "form": FormTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "displayValue": "FormInputValuePropertyTypeDef",
     },
+    total=False,
 )
 
-UpdateFormResponseTypeDef = TypedDict(
-    "UpdateFormResponseTypeDef",
-    {
-        "entity": FormTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class ValueMappingTypeDef(_RequiredValueMappingTypeDef, _OptionalValueMappingTypeDef):
+    pass
 
-_RequiredUpdateFormRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateFormRequestRequestTypeDef",
+_RequiredValueMappingsTypeDef = TypedDict(
+    "_RequiredValueMappingsTypeDef",
     {
-        "appId": str,
-        "environmentName": str,
-        "id": str,
-        "updatedForm": UpdateFormDataTypeDef,
+        "values": Sequence["ValueMappingTypeDef"],
     },
 )
-_OptionalUpdateFormRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateFormRequestRequestTypeDef",
+_OptionalValueMappingsTypeDef = TypedDict(
+    "_OptionalValueMappingsTypeDef",
     {
-        "clientToken": str,
+        "bindingProperties": Mapping[str, "FormInputBindingPropertiesValueTypeDef"],
     },
     total=False,
 )
 
-
-class UpdateFormRequestRequestTypeDef(
-    _RequiredUpdateFormRequestRequestTypeDef, _OptionalUpdateFormRequestRequestTypeDef
-):
+class ValueMappingsTypeDef(_RequiredValueMappingsTypeDef, _OptionalValueMappingsTypeDef):
     pass
```

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder/type_defs.pyi` & `types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder/type_defs.py`

 * *Files 20% similar despite different names*

```diff
@@ -2,179 +2,456 @@
 Type annotations for amplifyuibuilder service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_amplifyuibuilder.type_defs import MutationActionSetStateParameterTypeDef
+    from types_aiobotocore_amplifyuibuilder.type_defs import ActionParametersTypeDef
 
-    data: MutationActionSetStateParameterTypeDef = {...}
+    data: ActionParametersTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Any, Dict, List, Mapping, Sequence
 
 from .literals import (
+    CodegenGenericDataFieldDataTypeType,
+    CodegenJobStatusType,
     FormActionTypeType,
     FormButtonsPositionType,
     FormDataSourceTypeType,
+    GenericDataRelationshipTypeType,
+    JSModuleType,
+    JSScriptType,
+    JSTargetType,
+    LabelDecoratorType,
     SortDirectionType,
+    StorageAccessLevelType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
-    "MutationActionSetStateParameterTypeDef",
+    "ActionParametersTypeDef",
+    "CodegenFeatureFlagsTypeDef",
+    "CodegenGenericDataEnumTypeDef",
+    "CodegenGenericDataFieldTypeDef",
+    "CodegenGenericDataModelTypeDef",
+    "CodegenGenericDataNonModelTypeDef",
+    "CodegenGenericDataRelationshipTypeTypeDef",
+    "CodegenJobAssetTypeDef",
+    "CodegenJobGenericDataSchemaTypeDef",
+    "CodegenJobRenderConfigTypeDef",
+    "CodegenJobSummaryTypeDef",
+    "CodegenJobTypeDef",
     "ComponentBindingPropertiesValuePropertiesTypeDef",
+    "ComponentBindingPropertiesValueTypeDef",
+    "ComponentChildTypeDef",
     "ComponentConditionPropertyTypeDef",
-    "SortPropertyTypeDef",
+    "ComponentDataConfigurationTypeDef",
+    "ComponentEventTypeDef",
     "ComponentPropertyBindingPropertiesTypeDef",
-    "FormBindingElementTypeDef",
+    "ComponentPropertyTypeDef",
     "ComponentSummaryTypeDef",
+    "ComponentTypeDef",
     "ComponentVariantTypeDef",
-    "ResponseMetadataTypeDef",
-    "FormDataTypeConfigTypeDef",
+    "CreateComponentDataTypeDef",
+    "CreateComponentRequestRequestTypeDef",
+    "CreateComponentResponseTypeDef",
+    "CreateFormDataTypeDef",
+    "CreateFormRequestRequestTypeDef",
+    "CreateFormResponseTypeDef",
     "CreateThemeDataTypeDef",
-    "ThemeTypeDef",
+    "CreateThemeRequestRequestTypeDef",
+    "CreateThemeResponseTypeDef",
     "DeleteComponentRequestRequestTypeDef",
     "DeleteFormRequestRequestTypeDef",
     "DeleteThemeRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExchangeCodeForTokenRequestBodyTypeDef",
-    "PaginatorConfigTypeDef",
+    "ExchangeCodeForTokenRequestRequestTypeDef",
+    "ExchangeCodeForTokenResponseTypeDef",
+    "ExportComponentsRequestExportComponentsPaginateTypeDef",
     "ExportComponentsRequestRequestTypeDef",
+    "ExportComponentsResponseTypeDef",
+    "ExportFormsRequestExportFormsPaginateTypeDef",
     "ExportFormsRequestRequestTypeDef",
+    "ExportFormsResponseTypeDef",
+    "ExportThemesRequestExportThemesPaginateTypeDef",
     "ExportThemesRequestRequestTypeDef",
+    "ExportThemesResponseTypeDef",
+    "FieldConfigTypeDef",
+    "FieldInputConfigTypeDef",
     "FieldPositionTypeDef",
     "FieldValidationConfigurationTypeDef",
+    "FileUploaderFieldConfigTypeDef",
+    "FormBindingElementTypeDef",
+    "FormButtonTypeDef",
+    "FormCTATypeDef",
+    "FormDataTypeConfigTypeDef",
+    "FormInputBindingPropertiesValuePropertiesTypeDef",
+    "FormInputBindingPropertiesValueTypeDef",
+    "FormInputValuePropertyBindingPropertiesTypeDef",
     "FormInputValuePropertyTypeDef",
     "FormStyleConfigTypeDef",
+    "FormStyleTypeDef",
+    "FormSummaryTypeDef",
+    "FormTypeDef",
+    "GetCodegenJobRequestRequestTypeDef",
+    "GetCodegenJobResponseTypeDef",
     "GetComponentRequestRequestTypeDef",
+    "GetComponentResponseTypeDef",
     "GetFormRequestRequestTypeDef",
+    "GetFormResponseTypeDef",
     "GetMetadataRequestRequestTypeDef",
+    "GetMetadataResponseTypeDef",
     "GetThemeRequestRequestTypeDef",
+    "GetThemeResponseTypeDef",
+    "ListCodegenJobsRequestListCodegenJobsPaginateTypeDef",
+    "ListCodegenJobsRequestRequestTypeDef",
+    "ListCodegenJobsResponseTypeDef",
+    "ListComponentsRequestListComponentsPaginateTypeDef",
     "ListComponentsRequestRequestTypeDef",
+    "ListComponentsResponseTypeDef",
+    "ListFormsRequestListFormsPaginateTypeDef",
     "ListFormsRequestRequestTypeDef",
+    "ListFormsResponseTypeDef",
+    "ListThemesRequestListThemesPaginateTypeDef",
     "ListThemesRequestRequestTypeDef",
-    "ThemeSummaryTypeDef",
+    "ListThemesResponseTypeDef",
+    "MutationActionSetStateParameterTypeDef",
+    "PaginatorConfigTypeDef",
     "PredicateTypeDef",
     "PutMetadataFlagBodyTypeDef",
+    "PutMetadataFlagRequestRequestTypeDef",
+    "ReactStartCodegenJobDataTypeDef",
     "RefreshTokenRequestBodyTypeDef",
-    "ThemeValueTypeDef",
-    "ThemeValuesTypeDef",
-    "UpdateThemeDataTypeDef",
-    "ActionParametersTypeDef",
-    "ComponentBindingPropertiesValueTypeDef",
-    "ComponentDataConfigurationTypeDef",
-    "ComponentPropertyTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExchangeCodeForTokenResponseTypeDef",
-    "GetMetadataResponseTypeDef",
-    "ListComponentsResponseTypeDef",
+    "RefreshTokenRequestRequestTypeDef",
     "RefreshTokenResponseTypeDef",
-    "FormSummaryTypeDef",
-    "CreateThemeRequestRequestTypeDef",
-    "CreateThemeResponseTypeDef",
-    "ExportThemesResponseTypeDef",
-    "GetThemeResponseTypeDef",
-    "UpdateThemeResponseTypeDef",
-    "ExchangeCodeForTokenRequestRequestTypeDef",
-    "ExportComponentsRequestExportComponentsPaginateTypeDef",
-    "ExportFormsRequestExportFormsPaginateTypeDef",
-    "ExportThemesRequestExportThemesPaginateTypeDef",
-    "ListComponentsRequestListComponentsPaginateTypeDef",
-    "ListFormsRequestListFormsPaginateTypeDef",
-    "ListThemesRequestListThemesPaginateTypeDef",
-    "FormButtonTypeDef",
+    "ResponseMetadataTypeDef",
     "SectionalElementTypeDef",
-    "ValueMappingTypeDef",
-    "FormStyleTypeDef",
-    "ListThemesResponseTypeDef",
-    "PutMetadataFlagRequestRequestTypeDef",
-    "RefreshTokenRequestRequestTypeDef",
-    "UpdateThemeRequestRequestTypeDef",
-    "ComponentEventTypeDef",
-    "ListFormsResponseTypeDef",
-    "FormCTATypeDef",
-    "ValueMappingsTypeDef",
-    "ComponentChildTypeDef",
-    "ComponentTypeDef",
-    "CreateComponentDataTypeDef",
+    "SortPropertyTypeDef",
+    "StartCodegenJobDataTypeDef",
+    "StartCodegenJobRequestRequestTypeDef",
+    "StartCodegenJobResponseTypeDef",
+    "ThemeSummaryTypeDef",
+    "ThemeTypeDef",
+    "ThemeValueTypeDef",
+    "ThemeValuesTypeDef",
     "UpdateComponentDataTypeDef",
-    "FieldInputConfigTypeDef",
-    "CreateComponentResponseTypeDef",
-    "ExportComponentsResponseTypeDef",
-    "GetComponentResponseTypeDef",
-    "UpdateComponentResponseTypeDef",
-    "CreateComponentRequestRequestTypeDef",
     "UpdateComponentRequestRequestTypeDef",
-    "FieldConfigTypeDef",
-    "CreateFormDataTypeDef",
-    "FormTypeDef",
+    "UpdateComponentResponseTypeDef",
     "UpdateFormDataTypeDef",
-    "CreateFormRequestRequestTypeDef",
-    "CreateFormResponseTypeDef",
-    "ExportFormsResponseTypeDef",
-    "GetFormResponseTypeDef",
-    "UpdateFormResponseTypeDef",
     "UpdateFormRequestRequestTypeDef",
+    "UpdateFormResponseTypeDef",
+    "UpdateThemeDataTypeDef",
+    "UpdateThemeRequestRequestTypeDef",
+    "UpdateThemeResponseTypeDef",
+    "ValueMappingTypeDef",
+    "ValueMappingsTypeDef",
 )
 
-MutationActionSetStateParameterTypeDef = TypedDict(
-    "MutationActionSetStateParameterTypeDef",
+ActionParametersTypeDef = TypedDict(
+    "ActionParametersTypeDef",
     {
-        "componentName": str,
-        "property": str,
-        "set": "ComponentPropertyTypeDef",
+        "type": "ComponentPropertyTypeDef",
+        "url": "ComponentPropertyTypeDef",
+        "anchor": "ComponentPropertyTypeDef",
+        "target": "ComponentPropertyTypeDef",
+        "global": "ComponentPropertyTypeDef",
+        "model": str,
+        "id": "ComponentPropertyTypeDef",
+        "fields": Mapping[str, "ComponentPropertyTypeDef"],
+        "state": "MutationActionSetStateParameterTypeDef",
     },
+    total=False,
 )
 
+CodegenFeatureFlagsTypeDef = TypedDict(
+    "CodegenFeatureFlagsTypeDef",
+    {
+        "isRelationshipSupported": bool,
+        "isNonModelSupported": bool,
+    },
+    total=False,
+)
+
+CodegenGenericDataEnumTypeDef = TypedDict(
+    "CodegenGenericDataEnumTypeDef",
+    {
+        "values": List[str],
+    },
+)
+
+_RequiredCodegenGenericDataFieldTypeDef = TypedDict(
+    "_RequiredCodegenGenericDataFieldTypeDef",
+    {
+        "dataType": CodegenGenericDataFieldDataTypeType,
+        "dataTypeValue": str,
+        "required": bool,
+        "readOnly": bool,
+        "isArray": bool,
+    },
+)
+_OptionalCodegenGenericDataFieldTypeDef = TypedDict(
+    "_OptionalCodegenGenericDataFieldTypeDef",
+    {
+        "relationship": "CodegenGenericDataRelationshipTypeTypeDef",
+    },
+    total=False,
+)
+
+
+class CodegenGenericDataFieldTypeDef(
+    _RequiredCodegenGenericDataFieldTypeDef, _OptionalCodegenGenericDataFieldTypeDef
+):
+    pass
+
+
+_RequiredCodegenGenericDataModelTypeDef = TypedDict(
+    "_RequiredCodegenGenericDataModelTypeDef",
+    {
+        "fields": Dict[str, "CodegenGenericDataFieldTypeDef"],
+        "primaryKeys": List[str],
+    },
+)
+_OptionalCodegenGenericDataModelTypeDef = TypedDict(
+    "_OptionalCodegenGenericDataModelTypeDef",
+    {
+        "isJoinTable": bool,
+    },
+    total=False,
+)
+
+
+class CodegenGenericDataModelTypeDef(
+    _RequiredCodegenGenericDataModelTypeDef, _OptionalCodegenGenericDataModelTypeDef
+):
+    pass
+
+
+CodegenGenericDataNonModelTypeDef = TypedDict(
+    "CodegenGenericDataNonModelTypeDef",
+    {
+        "fields": Dict[str, "CodegenGenericDataFieldTypeDef"],
+    },
+)
+
+_RequiredCodegenGenericDataRelationshipTypeTypeDef = TypedDict(
+    "_RequiredCodegenGenericDataRelationshipTypeTypeDef",
+    {
+        "type": GenericDataRelationshipTypeType,
+        "relatedModelName": str,
+    },
+)
+_OptionalCodegenGenericDataRelationshipTypeTypeDef = TypedDict(
+    "_OptionalCodegenGenericDataRelationshipTypeTypeDef",
+    {
+        "relatedModelFields": List[str],
+        "canUnlinkAssociatedModel": bool,
+        "relatedJoinFieldName": str,
+        "relatedJoinTableName": str,
+        "belongsToFieldOnRelatedModel": str,
+        "associatedFields": List[str],
+        "isHasManyIndex": bool,
+    },
+    total=False,
+)
+
+
+class CodegenGenericDataRelationshipTypeTypeDef(
+    _RequiredCodegenGenericDataRelationshipTypeTypeDef,
+    _OptionalCodegenGenericDataRelationshipTypeTypeDef,
+):
+    pass
+
+
+CodegenJobAssetTypeDef = TypedDict(
+    "CodegenJobAssetTypeDef",
+    {
+        "downloadUrl": str,
+    },
+    total=False,
+)
+
+CodegenJobGenericDataSchemaTypeDef = TypedDict(
+    "CodegenJobGenericDataSchemaTypeDef",
+    {
+        "dataSourceType": Literal["DataStore"],
+        "models": Dict[str, "CodegenGenericDataModelTypeDef"],
+        "enums": Dict[str, "CodegenGenericDataEnumTypeDef"],
+        "nonModels": Dict[str, "CodegenGenericDataNonModelTypeDef"],
+    },
+)
+
+CodegenJobRenderConfigTypeDef = TypedDict(
+    "CodegenJobRenderConfigTypeDef",
+    {
+        "react": "ReactStartCodegenJobDataTypeDef",
+    },
+    total=False,
+)
+
+_RequiredCodegenJobSummaryTypeDef = TypedDict(
+    "_RequiredCodegenJobSummaryTypeDef",
+    {
+        "appId": str,
+        "environmentName": str,
+        "id": str,
+    },
+)
+_OptionalCodegenJobSummaryTypeDef = TypedDict(
+    "_OptionalCodegenJobSummaryTypeDef",
+    {
+        "createdAt": datetime,
+        "modifiedAt": datetime,
+    },
+    total=False,
+)
+
+
+class CodegenJobSummaryTypeDef(
+    _RequiredCodegenJobSummaryTypeDef, _OptionalCodegenJobSummaryTypeDef
+):
+    pass
+
+
+_RequiredCodegenJobTypeDef = TypedDict(
+    "_RequiredCodegenJobTypeDef",
+    {
+        "id": str,
+        "appId": str,
+        "environmentName": str,
+    },
+)
+_OptionalCodegenJobTypeDef = TypedDict(
+    "_OptionalCodegenJobTypeDef",
+    {
+        "renderConfig": "CodegenJobRenderConfigTypeDef",
+        "genericDataSchema": "CodegenJobGenericDataSchemaTypeDef",
+        "autoGenerateForms": bool,
+        "features": "CodegenFeatureFlagsTypeDef",
+        "status": CodegenJobStatusType,
+        "statusMessage": str,
+        "asset": "CodegenJobAssetTypeDef",
+        "tags": Dict[str, str],
+        "createdAt": datetime,
+        "modifiedAt": datetime,
+    },
+    total=False,
+)
+
+
+class CodegenJobTypeDef(_RequiredCodegenJobTypeDef, _OptionalCodegenJobTypeDef):
+    pass
+
+
 ComponentBindingPropertiesValuePropertiesTypeDef = TypedDict(
     "ComponentBindingPropertiesValuePropertiesTypeDef",
     {
-        "bucket": str,
-        "defaultValue": str,
-        "field": str,
-        "key": str,
         "model": str,
+        "field": str,
         "predicates": Sequence["PredicateTypeDef"],
-        "slotName": str,
         "userAttribute": str,
+        "bucket": str,
+        "key": str,
+        "defaultValue": str,
+        "slotName": str,
+    },
+    total=False,
+)
+
+ComponentBindingPropertiesValueTypeDef = TypedDict(
+    "ComponentBindingPropertiesValueTypeDef",
+    {
+        "type": str,
+        "bindingProperties": "ComponentBindingPropertiesValuePropertiesTypeDef",
+        "defaultValue": str,
     },
     total=False,
 )
 
+_RequiredComponentChildTypeDef = TypedDict(
+    "_RequiredComponentChildTypeDef",
+    {
+        "componentType": str,
+        "name": str,
+        "properties": Mapping[str, "ComponentPropertyTypeDef"],
+    },
+)
+_OptionalComponentChildTypeDef = TypedDict(
+    "_OptionalComponentChildTypeDef",
+    {
+        "children": Sequence[Dict[str, Any]],
+        "events": Mapping[str, "ComponentEventTypeDef"],
+        "sourceId": str,
+    },
+    total=False,
+)
+
+
+class ComponentChildTypeDef(_RequiredComponentChildTypeDef, _OptionalComponentChildTypeDef):
+    pass
+
+
 ComponentConditionPropertyTypeDef = TypedDict(
     "ComponentConditionPropertyTypeDef",
     {
-        "else": Dict[str, Any],
+        "property": str,
         "field": str,
-        "operand": str,
-        "operandType": str,
         "operator": str,
-        "property": str,
+        "operand": str,
         "then": Dict[str, Any],
+        "else": Dict[str, Any],
+        "operandType": str,
     },
     total=False,
 )
 
-SortPropertyTypeDef = TypedDict(
-    "SortPropertyTypeDef",
+_RequiredComponentDataConfigurationTypeDef = TypedDict(
+    "_RequiredComponentDataConfigurationTypeDef",
     {
-        "direction": SortDirectionType,
-        "field": str,
+        "model": str,
+    },
+)
+_OptionalComponentDataConfigurationTypeDef = TypedDict(
+    "_OptionalComponentDataConfigurationTypeDef",
+    {
+        "sort": Sequence["SortPropertyTypeDef"],
+        "predicate": "PredicateTypeDef",
+        "identifiers": Sequence[str],
     },
+    total=False,
+)
+
+
+class ComponentDataConfigurationTypeDef(
+    _RequiredComponentDataConfigurationTypeDef, _OptionalComponentDataConfigurationTypeDef
+):
+    pass
+
+
+ComponentEventTypeDef = TypedDict(
+    "ComponentEventTypeDef",
+    {
+        "action": str,
+        "parameters": "ActionParametersTypeDef",
+        "bindingEvent": str,
+    },
+    total=False,
 )
 
 _RequiredComponentPropertyBindingPropertiesTypeDef = TypedDict(
     "_RequiredComponentPropertyBindingPropertiesTypeDef",
     {
         "property": str,
     },
@@ -183,64 +460,215 @@
     "_OptionalComponentPropertyBindingPropertiesTypeDef",
     {
         "field": str,
     },
     total=False,
 )
 
+
 class ComponentPropertyBindingPropertiesTypeDef(
     _RequiredComponentPropertyBindingPropertiesTypeDef,
     _OptionalComponentPropertyBindingPropertiesTypeDef,
 ):
     pass
 
-FormBindingElementTypeDef = TypedDict(
-    "FormBindingElementTypeDef",
+
+ComponentPropertyTypeDef = TypedDict(
+    "ComponentPropertyTypeDef",
     {
-        "element": str,
+        "value": str,
+        "bindingProperties": "ComponentPropertyBindingPropertiesTypeDef",
+        "collectionBindingProperties": "ComponentPropertyBindingPropertiesTypeDef",
+        "defaultValue": str,
+        "model": str,
+        "bindings": Mapping[str, "FormBindingElementTypeDef"],
+        "event": str,
+        "userAttribute": str,
+        "concat": Sequence[Dict[str, Any]],
+        "condition": Dict[str, Any],
+        "configured": bool,
+        "type": str,
+        "importedValue": str,
+        "componentName": str,
         "property": str,
     },
+    total=False,
 )
 
 ComponentSummaryTypeDef = TypedDict(
     "ComponentSummaryTypeDef",
     {
         "appId": str,
+        "environmentName": str,
+        "id": str,
+        "name": str,
         "componentType": str,
+    },
+)
+
+_RequiredComponentTypeDef = TypedDict(
+    "_RequiredComponentTypeDef",
+    {
+        "appId": str,
         "environmentName": str,
         "id": str,
         "name": str,
+        "componentType": str,
+        "properties": Dict[str, "ComponentPropertyTypeDef"],
+        "variants": List["ComponentVariantTypeDef"],
+        "overrides": Dict[str, Dict[str, str]],
+        "bindingProperties": Dict[str, "ComponentBindingPropertiesValueTypeDef"],
+        "createdAt": datetime,
     },
 )
+_OptionalComponentTypeDef = TypedDict(
+    "_OptionalComponentTypeDef",
+    {
+        "sourceId": str,
+        "children": List["ComponentChildTypeDef"],
+        "collectionProperties": Dict[str, "ComponentDataConfigurationTypeDef"],
+        "modifiedAt": datetime,
+        "tags": Dict[str, str],
+        "events": Dict[str, "ComponentEventTypeDef"],
+        "schemaVersion": str,
+    },
+    total=False,
+)
+
+
+class ComponentTypeDef(_RequiredComponentTypeDef, _OptionalComponentTypeDef):
+    pass
+
 
 ComponentVariantTypeDef = TypedDict(
     "ComponentVariantTypeDef",
     {
-        "overrides": Mapping[str, Mapping[str, str]],
         "variantValues": Mapping[str, str],
+        "overrides": Mapping[str, Mapping[str, str]],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+_RequiredCreateComponentDataTypeDef = TypedDict(
+    "_RequiredCreateComponentDataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "name": str,
+        "componentType": str,
+        "properties": Mapping[str, "ComponentPropertyTypeDef"],
+        "variants": Sequence["ComponentVariantTypeDef"],
+        "overrides": Mapping[str, Mapping[str, str]],
+        "bindingProperties": Mapping[str, "ComponentBindingPropertiesValueTypeDef"],
     },
 )
+_OptionalCreateComponentDataTypeDef = TypedDict(
+    "_OptionalCreateComponentDataTypeDef",
+    {
+        "sourceId": str,
+        "children": Sequence["ComponentChildTypeDef"],
+        "collectionProperties": Mapping[str, "ComponentDataConfigurationTypeDef"],
+        "tags": Mapping[str, str],
+        "events": Mapping[str, "ComponentEventTypeDef"],
+        "schemaVersion": str,
+    },
+    total=False,
+)
 
-FormDataTypeConfigTypeDef = TypedDict(
-    "FormDataTypeConfigTypeDef",
+
+class CreateComponentDataTypeDef(
+    _RequiredCreateComponentDataTypeDef, _OptionalCreateComponentDataTypeDef
+):
+    pass
+
+
+_RequiredCreateComponentRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateComponentRequestRequestTypeDef",
     {
-        "dataSourceType": FormDataSourceTypeType,
-        "dataTypeName": str,
+        "appId": str,
+        "environmentName": str,
+        "componentToCreate": "CreateComponentDataTypeDef",
+    },
+)
+_OptionalCreateComponentRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateComponentRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+
+class CreateComponentRequestRequestTypeDef(
+    _RequiredCreateComponentRequestRequestTypeDef, _OptionalCreateComponentRequestRequestTypeDef
+):
+    pass
+
+
+CreateComponentResponseTypeDef = TypedDict(
+    "CreateComponentResponseTypeDef",
+    {
+        "entity": "ComponentTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreateFormDataTypeDef = TypedDict(
+    "_RequiredCreateFormDataTypeDef",
+    {
+        "name": str,
+        "dataType": "FormDataTypeConfigTypeDef",
+        "formActionType": FormActionTypeType,
+        "fields": Mapping[str, "FieldConfigTypeDef"],
+        "style": "FormStyleTypeDef",
+        "sectionalElements": Mapping[str, "SectionalElementTypeDef"],
+        "schemaVersion": str,
+    },
+)
+_OptionalCreateFormDataTypeDef = TypedDict(
+    "_OptionalCreateFormDataTypeDef",
+    {
+        "cta": "FormCTATypeDef",
+        "tags": Mapping[str, str],
+        "labelDecorator": LabelDecoratorType,
+    },
+    total=False,
+)
+
+
+class CreateFormDataTypeDef(_RequiredCreateFormDataTypeDef, _OptionalCreateFormDataTypeDef):
+    pass
+
+
+_RequiredCreateFormRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateFormRequestRequestTypeDef",
+    {
+        "appId": str,
+        "environmentName": str,
+        "formToCreate": "CreateFormDataTypeDef",
+    },
+)
+_OptionalCreateFormRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateFormRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+
+class CreateFormRequestRequestTypeDef(
+    _RequiredCreateFormRequestRequestTypeDef, _OptionalCreateFormRequestRequestTypeDef
+):
+    pass
+
+
+CreateFormResponseTypeDef = TypedDict(
+    "CreateFormResponseTypeDef",
+    {
+        "entity": "FormTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateThemeDataTypeDef = TypedDict(
     "_RequiredCreateThemeDataTypeDef",
     {
         "name": str,
@@ -252,41 +680,50 @@
     {
         "overrides": Sequence["ThemeValuesTypeDef"],
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateThemeDataTypeDef(_RequiredCreateThemeDataTypeDef, _OptionalCreateThemeDataTypeDef):
     pass
 
-_RequiredThemeTypeDef = TypedDict(
-    "_RequiredThemeTypeDef",
+
+_RequiredCreateThemeRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateThemeRequestRequestTypeDef",
     {
         "appId": str,
-        "createdAt": datetime,
         "environmentName": str,
-        "id": str,
-        "name": str,
-        "values": List["ThemeValuesTypeDef"],
+        "themeToCreate": "CreateThemeDataTypeDef",
     },
 )
-_OptionalThemeTypeDef = TypedDict(
-    "_OptionalThemeTypeDef",
+_OptionalCreateThemeRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateThemeRequestRequestTypeDef",
     {
-        "modifiedAt": datetime,
-        "overrides": List["ThemeValuesTypeDef"],
-        "tags": Dict[str, str],
+        "clientToken": str,
     },
     total=False,
 )
 
-class ThemeTypeDef(_RequiredThemeTypeDef, _OptionalThemeTypeDef):
+
+class CreateThemeRequestRequestTypeDef(
+    _RequiredCreateThemeRequestRequestTypeDef, _OptionalCreateThemeRequestRequestTypeDef
+):
     pass
 
+
+CreateThemeResponseTypeDef = TypedDict(
+    "CreateThemeResponseTypeDef",
+    {
+        "entity": "ThemeTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteComponentRequestRequestTypeDef = TypedDict(
     "DeleteComponentRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
         "id": str,
     },
@@ -306,1119 +743,1208 @@
     {
         "appId": str,
         "environmentName": str,
         "id": str,
     },
 )
 
-ExchangeCodeForTokenRequestBodyTypeDef = TypedDict(
-    "ExchangeCodeForTokenRequestBodyTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
     {
-        "code": str,
-        "redirectUri": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredExchangeCodeForTokenRequestBodyTypeDef = TypedDict(
+    "_RequiredExchangeCodeForTokenRequestBodyTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
-)
-
-_RequiredExportComponentsRequestRequestTypeDef = TypedDict(
-    "_RequiredExportComponentsRequestRequestTypeDef",
-    {
-        "appId": str,
-        "environmentName": str,
+        "code": str,
+        "redirectUri": str,
     },
 )
-_OptionalExportComponentsRequestRequestTypeDef = TypedDict(
-    "_OptionalExportComponentsRequestRequestTypeDef",
+_OptionalExchangeCodeForTokenRequestBodyTypeDef = TypedDict(
+    "_OptionalExchangeCodeForTokenRequestBodyTypeDef",
     {
-        "nextToken": str,
+        "clientId": str,
     },
     total=False,
 )
 
-class ExportComponentsRequestRequestTypeDef(
-    _RequiredExportComponentsRequestRequestTypeDef, _OptionalExportComponentsRequestRequestTypeDef
+
+class ExchangeCodeForTokenRequestBodyTypeDef(
+    _RequiredExchangeCodeForTokenRequestBodyTypeDef, _OptionalExchangeCodeForTokenRequestBodyTypeDef
 ):
     pass
 
-_RequiredExportFormsRequestRequestTypeDef = TypedDict(
-    "_RequiredExportFormsRequestRequestTypeDef",
+
+ExchangeCodeForTokenRequestRequestTypeDef = TypedDict(
+    "ExchangeCodeForTokenRequestRequestTypeDef",
     {
-        "appId": str,
-        "environmentName": str,
+        "provider": Literal["figma"],
+        "request": "ExchangeCodeForTokenRequestBodyTypeDef",
     },
 )
-_OptionalExportFormsRequestRequestTypeDef = TypedDict(
-    "_OptionalExportFormsRequestRequestTypeDef",
+
+ExchangeCodeForTokenResponseTypeDef = TypedDict(
+    "ExchangeCodeForTokenResponseTypeDef",
     {
-        "nextToken": str,
+        "accessToken": str,
+        "expiresIn": int,
+        "refreshToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ExportFormsRequestRequestTypeDef(
-    _RequiredExportFormsRequestRequestTypeDef, _OptionalExportFormsRequestRequestTypeDef
-):
-    pass
-
-_RequiredExportThemesRequestRequestTypeDef = TypedDict(
-    "_RequiredExportThemesRequestRequestTypeDef",
+_RequiredExportComponentsRequestExportComponentsPaginateTypeDef = TypedDict(
+    "_RequiredExportComponentsRequestExportComponentsPaginateTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
-_OptionalExportThemesRequestRequestTypeDef = TypedDict(
-    "_OptionalExportThemesRequestRequestTypeDef",
+_OptionalExportComponentsRequestExportComponentsPaginateTypeDef = TypedDict(
+    "_OptionalExportComponentsRequestExportComponentsPaginateTypeDef",
     {
-        "nextToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class ExportThemesRequestRequestTypeDef(
-    _RequiredExportThemesRequestRequestTypeDef, _OptionalExportThemesRequestRequestTypeDef
+
+class ExportComponentsRequestExportComponentsPaginateTypeDef(
+    _RequiredExportComponentsRequestExportComponentsPaginateTypeDef,
+    _OptionalExportComponentsRequestExportComponentsPaginateTypeDef,
 ):
     pass
 
-FieldPositionTypeDef = TypedDict(
-    "FieldPositionTypeDef",
-    {
-        "below": str,
-        "fixed": Literal["first"],
-        "rightOf": str,
-    },
-    total=False,
-)
 
-_RequiredFieldValidationConfigurationTypeDef = TypedDict(
-    "_RequiredFieldValidationConfigurationTypeDef",
+_RequiredExportComponentsRequestRequestTypeDef = TypedDict(
+    "_RequiredExportComponentsRequestRequestTypeDef",
     {
-        "type": str,
+        "appId": str,
+        "environmentName": str,
     },
 )
-_OptionalFieldValidationConfigurationTypeDef = TypedDict(
-    "_OptionalFieldValidationConfigurationTypeDef",
+_OptionalExportComponentsRequestRequestTypeDef = TypedDict(
+    "_OptionalExportComponentsRequestRequestTypeDef",
     {
-        "numValues": Sequence[int],
-        "strValues": Sequence[str],
-        "validationMessage": str,
+        "nextToken": str,
     },
     total=False,
 )
 
-class FieldValidationConfigurationTypeDef(
-    _RequiredFieldValidationConfigurationTypeDef, _OptionalFieldValidationConfigurationTypeDef
+
+class ExportComponentsRequestRequestTypeDef(
+    _RequiredExportComponentsRequestRequestTypeDef, _OptionalExportComponentsRequestRequestTypeDef
 ):
     pass
 
-FormInputValuePropertyTypeDef = TypedDict(
-    "FormInputValuePropertyTypeDef",
-    {
-        "value": str,
-    },
-    total=False,
-)
 
-FormStyleConfigTypeDef = TypedDict(
-    "FormStyleConfigTypeDef",
+ExportComponentsResponseTypeDef = TypedDict(
+    "ExportComponentsResponseTypeDef",
     {
-        "tokenReference": str,
-        "value": str,
+        "entities": List["ComponentTypeDef"],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-GetComponentRequestRequestTypeDef = TypedDict(
-    "GetComponentRequestRequestTypeDef",
+_RequiredExportFormsRequestExportFormsPaginateTypeDef = TypedDict(
+    "_RequiredExportFormsRequestExportFormsPaginateTypeDef",
     {
         "appId": str,
         "environmentName": str,
-        "id": str,
     },
 )
-
-GetFormRequestRequestTypeDef = TypedDict(
-    "GetFormRequestRequestTypeDef",
+_OptionalExportFormsRequestExportFormsPaginateTypeDef = TypedDict(
+    "_OptionalExportFormsRequestExportFormsPaginateTypeDef",
     {
-        "appId": str,
-        "environmentName": str,
-        "id": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
-GetMetadataRequestRequestTypeDef = TypedDict(
-    "GetMetadataRequestRequestTypeDef",
-    {
-        "appId": str,
-        "environmentName": str,
-    },
-)
 
-GetThemeRequestRequestTypeDef = TypedDict(
-    "GetThemeRequestRequestTypeDef",
-    {
-        "appId": str,
-        "environmentName": str,
-        "id": str,
-    },
-)
+class ExportFormsRequestExportFormsPaginateTypeDef(
+    _RequiredExportFormsRequestExportFormsPaginateTypeDef,
+    _OptionalExportFormsRequestExportFormsPaginateTypeDef,
+):
+    pass
 
-_RequiredListComponentsRequestRequestTypeDef = TypedDict(
-    "_RequiredListComponentsRequestRequestTypeDef",
+
+_RequiredExportFormsRequestRequestTypeDef = TypedDict(
+    "_RequiredExportFormsRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
-_OptionalListComponentsRequestRequestTypeDef = TypedDict(
-    "_OptionalListComponentsRequestRequestTypeDef",
+_OptionalExportFormsRequestRequestTypeDef = TypedDict(
+    "_OptionalExportFormsRequestRequestTypeDef",
     {
-        "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-class ListComponentsRequestRequestTypeDef(
-    _RequiredListComponentsRequestRequestTypeDef, _OptionalListComponentsRequestRequestTypeDef
+
+class ExportFormsRequestRequestTypeDef(
+    _RequiredExportFormsRequestRequestTypeDef, _OptionalExportFormsRequestRequestTypeDef
 ):
     pass
 
-_RequiredListFormsRequestRequestTypeDef = TypedDict(
-    "_RequiredListFormsRequestRequestTypeDef",
+
+ExportFormsResponseTypeDef = TypedDict(
+    "ExportFormsResponseTypeDef",
+    {
+        "entities": List["FormTypeDef"],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredExportThemesRequestExportThemesPaginateTypeDef = TypedDict(
+    "_RequiredExportThemesRequestExportThemesPaginateTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
-_OptionalListFormsRequestRequestTypeDef = TypedDict(
-    "_OptionalListFormsRequestRequestTypeDef",
+_OptionalExportThemesRequestExportThemesPaginateTypeDef = TypedDict(
+    "_OptionalExportThemesRequestExportThemesPaginateTypeDef",
     {
-        "maxResults": int,
-        "nextToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class ListFormsRequestRequestTypeDef(
-    _RequiredListFormsRequestRequestTypeDef, _OptionalListFormsRequestRequestTypeDef
+
+class ExportThemesRequestExportThemesPaginateTypeDef(
+    _RequiredExportThemesRequestExportThemesPaginateTypeDef,
+    _OptionalExportThemesRequestExportThemesPaginateTypeDef,
 ):
     pass
 
-_RequiredListThemesRequestRequestTypeDef = TypedDict(
-    "_RequiredListThemesRequestRequestTypeDef",
+
+_RequiredExportThemesRequestRequestTypeDef = TypedDict(
+    "_RequiredExportThemesRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
-_OptionalListThemesRequestRequestTypeDef = TypedDict(
-    "_OptionalListThemesRequestRequestTypeDef",
+_OptionalExportThemesRequestRequestTypeDef = TypedDict(
+    "_OptionalExportThemesRequestRequestTypeDef",
     {
-        "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-class ListThemesRequestRequestTypeDef(
-    _RequiredListThemesRequestRequestTypeDef, _OptionalListThemesRequestRequestTypeDef
+
+class ExportThemesRequestRequestTypeDef(
+    _RequiredExportThemesRequestRequestTypeDef, _OptionalExportThemesRequestRequestTypeDef
 ):
     pass
 
-ThemeSummaryTypeDef = TypedDict(
-    "ThemeSummaryTypeDef",
+
+ExportThemesResponseTypeDef = TypedDict(
+    "ExportThemesResponseTypeDef",
     {
-        "appId": str,
-        "environmentName": str,
-        "id": str,
-        "name": str,
+        "entities": List["ThemeTypeDef"],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PredicateTypeDef = TypedDict(
-    "PredicateTypeDef",
+FieldConfigTypeDef = TypedDict(
+    "FieldConfigTypeDef",
     {
-        "and": Sequence[Dict[str, Any]],
-        "field": str,
-        "operand": str,
-        "operator": str,
-        "or": Sequence[Dict[str, Any]],
+        "label": str,
+        "position": "FieldPositionTypeDef",
+        "excluded": bool,
+        "inputType": "FieldInputConfigTypeDef",
+        "validations": Sequence["FieldValidationConfigurationTypeDef"],
     },
     total=False,
 )
 
-PutMetadataFlagBodyTypeDef = TypedDict(
-    "PutMetadataFlagBodyTypeDef",
+_RequiredFieldInputConfigTypeDef = TypedDict(
+    "_RequiredFieldInputConfigTypeDef",
     {
-        "newValue": str,
+        "type": str,
     },
 )
-
-RefreshTokenRequestBodyTypeDef = TypedDict(
-    "RefreshTokenRequestBodyTypeDef",
+_OptionalFieldInputConfigTypeDef = TypedDict(
+    "_OptionalFieldInputConfigTypeDef",
     {
-        "token": str,
+        "required": bool,
+        "readOnly": bool,
+        "placeholder": str,
+        "defaultValue": str,
+        "descriptiveText": str,
+        "defaultChecked": bool,
+        "defaultCountryCode": str,
+        "valueMappings": "ValueMappingsTypeDef",
+        "name": str,
+        "minValue": float,
+        "maxValue": float,
+        "step": float,
+        "value": str,
+        "isArray": bool,
+        "fileUploaderConfig": "FileUploaderFieldConfigTypeDef",
     },
+    total=False,
 )
 
-ThemeValueTypeDef = TypedDict(
-    "ThemeValueTypeDef",
+
+class FieldInputConfigTypeDef(_RequiredFieldInputConfigTypeDef, _OptionalFieldInputConfigTypeDef):
+    pass
+
+
+FieldPositionTypeDef = TypedDict(
+    "FieldPositionTypeDef",
     {
-        "children": Sequence[Dict[str, Any]],
-        "value": str,
+        "fixed": Literal["first"],
+        "rightOf": str,
+        "below": str,
     },
     total=False,
 )
 
-ThemeValuesTypeDef = TypedDict(
-    "ThemeValuesTypeDef",
+_RequiredFieldValidationConfigurationTypeDef = TypedDict(
+    "_RequiredFieldValidationConfigurationTypeDef",
     {
-        "key": str,
-        "value": Dict[str, Any],
+        "type": str,
+    },
+)
+_OptionalFieldValidationConfigurationTypeDef = TypedDict(
+    "_OptionalFieldValidationConfigurationTypeDef",
+    {
+        "strValues": Sequence[str],
+        "numValues": Sequence[int],
+        "validationMessage": str,
     },
     total=False,
 )
 
-_RequiredUpdateThemeDataTypeDef = TypedDict(
-    "_RequiredUpdateThemeDataTypeDef",
+
+class FieldValidationConfigurationTypeDef(
+    _RequiredFieldValidationConfigurationTypeDef, _OptionalFieldValidationConfigurationTypeDef
+):
+    pass
+
+
+_RequiredFileUploaderFieldConfigTypeDef = TypedDict(
+    "_RequiredFileUploaderFieldConfigTypeDef",
     {
-        "values": Sequence["ThemeValuesTypeDef"],
+        "accessLevel": StorageAccessLevelType,
+        "acceptedFileTypes": Sequence[str],
     },
 )
-_OptionalUpdateThemeDataTypeDef = TypedDict(
-    "_OptionalUpdateThemeDataTypeDef",
+_OptionalFileUploaderFieldConfigTypeDef = TypedDict(
+    "_OptionalFileUploaderFieldConfigTypeDef",
     {
-        "id": str,
-        "name": str,
-        "overrides": Sequence["ThemeValuesTypeDef"],
+        "showThumbnails": bool,
+        "isResumable": bool,
+        "maxFileCount": int,
+        "maxSize": int,
     },
     total=False,
 )
 
-class UpdateThemeDataTypeDef(_RequiredUpdateThemeDataTypeDef, _OptionalUpdateThemeDataTypeDef):
+
+class FileUploaderFieldConfigTypeDef(
+    _RequiredFileUploaderFieldConfigTypeDef, _OptionalFileUploaderFieldConfigTypeDef
+):
     pass
 
-ActionParametersTypeDef = TypedDict(
-    "ActionParametersTypeDef",
+
+FormBindingElementTypeDef = TypedDict(
+    "FormBindingElementTypeDef",
     {
-        "anchor": "ComponentPropertyTypeDef",
-        "fields": Mapping[str, "ComponentPropertyTypeDef"],
-        "global": "ComponentPropertyTypeDef",
-        "id": "ComponentPropertyTypeDef",
-        "model": str,
-        "state": MutationActionSetStateParameterTypeDef,
-        "target": "ComponentPropertyTypeDef",
-        "type": "ComponentPropertyTypeDef",
-        "url": "ComponentPropertyTypeDef",
+        "element": str,
+        "property": str,
+    },
+)
+
+FormButtonTypeDef = TypedDict(
+    "FormButtonTypeDef",
+    {
+        "excluded": bool,
+        "children": str,
+        "position": "FieldPositionTypeDef",
     },
     total=False,
 )
 
-ComponentBindingPropertiesValueTypeDef = TypedDict(
-    "ComponentBindingPropertiesValueTypeDef",
+FormCTATypeDef = TypedDict(
+    "FormCTATypeDef",
     {
-        "bindingProperties": ComponentBindingPropertiesValuePropertiesTypeDef,
-        "defaultValue": str,
-        "type": str,
+        "position": FormButtonsPositionType,
+        "clear": "FormButtonTypeDef",
+        "cancel": "FormButtonTypeDef",
+        "submit": "FormButtonTypeDef",
     },
     total=False,
 )
 
-_RequiredComponentDataConfigurationTypeDef = TypedDict(
-    "_RequiredComponentDataConfigurationTypeDef",
+FormDataTypeConfigTypeDef = TypedDict(
+    "FormDataTypeConfigTypeDef",
     {
-        "model": str,
+        "dataSourceType": FormDataSourceTypeType,
+        "dataTypeName": str,
     },
 )
-_OptionalComponentDataConfigurationTypeDef = TypedDict(
-    "_OptionalComponentDataConfigurationTypeDef",
+
+FormInputBindingPropertiesValuePropertiesTypeDef = TypedDict(
+    "FormInputBindingPropertiesValuePropertiesTypeDef",
     {
-        "identifiers": Sequence[str],
-        "predicate": "PredicateTypeDef",
-        "sort": Sequence[SortPropertyTypeDef],
+        "model": str,
     },
     total=False,
 )
 
-class ComponentDataConfigurationTypeDef(
-    _RequiredComponentDataConfigurationTypeDef, _OptionalComponentDataConfigurationTypeDef
-):
-    pass
-
-ComponentPropertyTypeDef = TypedDict(
-    "ComponentPropertyTypeDef",
+FormInputBindingPropertiesValueTypeDef = TypedDict(
+    "FormInputBindingPropertiesValueTypeDef",
     {
-        "bindingProperties": ComponentPropertyBindingPropertiesTypeDef,
-        "bindings": Mapping[str, FormBindingElementTypeDef],
-        "collectionBindingProperties": ComponentPropertyBindingPropertiesTypeDef,
-        "componentName": str,
-        "concat": Sequence[Dict[str, Any]],
-        "condition": Dict[str, Any],
-        "configured": bool,
-        "defaultValue": str,
-        "event": str,
-        "importedValue": str,
-        "model": str,
-        "property": str,
         "type": str,
-        "userAttribute": str,
-        "value": str,
+        "bindingProperties": "FormInputBindingPropertiesValuePropertiesTypeDef",
     },
     total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+_RequiredFormInputValuePropertyBindingPropertiesTypeDef = TypedDict(
+    "_RequiredFormInputValuePropertyBindingPropertiesTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "property": str,
     },
 )
-
-ExchangeCodeForTokenResponseTypeDef = TypedDict(
-    "ExchangeCodeForTokenResponseTypeDef",
+_OptionalFormInputValuePropertyBindingPropertiesTypeDef = TypedDict(
+    "_OptionalFormInputValuePropertyBindingPropertiesTypeDef",
     {
-        "accessToken": str,
-        "expiresIn": int,
-        "refreshToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "field": str,
     },
+    total=False,
 )
 
-GetMetadataResponseTypeDef = TypedDict(
-    "GetMetadataResponseTypeDef",
+
+class FormInputValuePropertyBindingPropertiesTypeDef(
+    _RequiredFormInputValuePropertyBindingPropertiesTypeDef,
+    _OptionalFormInputValuePropertyBindingPropertiesTypeDef,
+):
+    pass
+
+
+FormInputValuePropertyTypeDef = TypedDict(
+    "FormInputValuePropertyTypeDef",
     {
-        "features": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "value": str,
+        "bindingProperties": "FormInputValuePropertyBindingPropertiesTypeDef",
+        "concat": Sequence[Dict[str, Any]],
     },
+    total=False,
 )
 
-ListComponentsResponseTypeDef = TypedDict(
-    "ListComponentsResponseTypeDef",
+FormStyleConfigTypeDef = TypedDict(
+    "FormStyleConfigTypeDef",
     {
-        "entities": List[ComponentSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "tokenReference": str,
+        "value": str,
     },
+    total=False,
 )
 
-RefreshTokenResponseTypeDef = TypedDict(
-    "RefreshTokenResponseTypeDef",
+FormStyleTypeDef = TypedDict(
+    "FormStyleTypeDef",
     {
-        "accessToken": str,
-        "expiresIn": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "horizontalGap": "FormStyleConfigTypeDef",
+        "verticalGap": "FormStyleConfigTypeDef",
+        "outerPadding": "FormStyleConfigTypeDef",
     },
+    total=False,
 )
 
 FormSummaryTypeDef = TypedDict(
     "FormSummaryTypeDef",
     {
         "appId": str,
-        "dataType": FormDataTypeConfigTypeDef,
+        "dataType": "FormDataTypeConfigTypeDef",
         "environmentName": str,
         "formActionType": FormActionTypeType,
         "id": str,
         "name": str,
     },
 )
 
-_RequiredCreateThemeRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateThemeRequestRequestTypeDef",
+_RequiredFormTypeDef = TypedDict(
+    "_RequiredFormTypeDef",
     {
         "appId": str,
         "environmentName": str,
-        "themeToCreate": CreateThemeDataTypeDef,
+        "id": str,
+        "name": str,
+        "formActionType": FormActionTypeType,
+        "style": "FormStyleTypeDef",
+        "dataType": "FormDataTypeConfigTypeDef",
+        "fields": Dict[str, "FieldConfigTypeDef"],
+        "sectionalElements": Dict[str, "SectionalElementTypeDef"],
+        "schemaVersion": str,
     },
 )
-_OptionalCreateThemeRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateThemeRequestRequestTypeDef",
+_OptionalFormTypeDef = TypedDict(
+    "_OptionalFormTypeDef",
     {
-        "clientToken": str,
+        "tags": Dict[str, str],
+        "cta": "FormCTATypeDef",
+        "labelDecorator": LabelDecoratorType,
     },
     total=False,
 )
 
-class CreateThemeRequestRequestTypeDef(
-    _RequiredCreateThemeRequestRequestTypeDef, _OptionalCreateThemeRequestRequestTypeDef
-):
+
+class FormTypeDef(_RequiredFormTypeDef, _OptionalFormTypeDef):
     pass
 
-CreateThemeResponseTypeDef = TypedDict(
-    "CreateThemeResponseTypeDef",
+
+GetCodegenJobRequestRequestTypeDef = TypedDict(
+    "GetCodegenJobRequestRequestTypeDef",
     {
-        "entity": ThemeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "appId": str,
+        "environmentName": str,
+        "id": str,
     },
 )
 
-ExportThemesResponseTypeDef = TypedDict(
-    "ExportThemesResponseTypeDef",
+GetCodegenJobResponseTypeDef = TypedDict(
+    "GetCodegenJobResponseTypeDef",
     {
-        "entities": List[ThemeTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "job": "CodegenJobTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetThemeResponseTypeDef = TypedDict(
-    "GetThemeResponseTypeDef",
+GetComponentRequestRequestTypeDef = TypedDict(
+    "GetComponentRequestRequestTypeDef",
     {
-        "theme": ThemeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "appId": str,
+        "environmentName": str,
+        "id": str,
     },
 )
 
-UpdateThemeResponseTypeDef = TypedDict(
-    "UpdateThemeResponseTypeDef",
+GetComponentResponseTypeDef = TypedDict(
+    "GetComponentResponseTypeDef",
     {
-        "entity": ThemeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "component": "ComponentTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ExchangeCodeForTokenRequestRequestTypeDef = TypedDict(
-    "ExchangeCodeForTokenRequestRequestTypeDef",
+GetFormRequestRequestTypeDef = TypedDict(
+    "GetFormRequestRequestTypeDef",
     {
-        "provider": Literal["figma"],
-        "request": ExchangeCodeForTokenRequestBodyTypeDef,
+        "appId": str,
+        "environmentName": str,
+        "id": str,
     },
 )
 
-_RequiredExportComponentsRequestExportComponentsPaginateTypeDef = TypedDict(
-    "_RequiredExportComponentsRequestExportComponentsPaginateTypeDef",
+GetFormResponseTypeDef = TypedDict(
+    "GetFormResponseTypeDef",
+    {
+        "form": "FormTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetMetadataRequestRequestTypeDef = TypedDict(
+    "GetMetadataRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
-_OptionalExportComponentsRequestExportComponentsPaginateTypeDef = TypedDict(
-    "_OptionalExportComponentsRequestExportComponentsPaginateTypeDef",
+
+GetMetadataResponseTypeDef = TypedDict(
+    "GetMetadataResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "features": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ExportComponentsRequestExportComponentsPaginateTypeDef(
-    _RequiredExportComponentsRequestExportComponentsPaginateTypeDef,
-    _OptionalExportComponentsRequestExportComponentsPaginateTypeDef,
-):
-    pass
+GetThemeRequestRequestTypeDef = TypedDict(
+    "GetThemeRequestRequestTypeDef",
+    {
+        "appId": str,
+        "environmentName": str,
+        "id": str,
+    },
+)
 
-_RequiredExportFormsRequestExportFormsPaginateTypeDef = TypedDict(
-    "_RequiredExportFormsRequestExportFormsPaginateTypeDef",
+GetThemeResponseTypeDef = TypedDict(
+    "GetThemeResponseTypeDef",
+    {
+        "theme": "ThemeTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListCodegenJobsRequestListCodegenJobsPaginateTypeDef = TypedDict(
+    "_RequiredListCodegenJobsRequestListCodegenJobsPaginateTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
-_OptionalExportFormsRequestExportFormsPaginateTypeDef = TypedDict(
-    "_OptionalExportFormsRequestExportFormsPaginateTypeDef",
+_OptionalListCodegenJobsRequestListCodegenJobsPaginateTypeDef = TypedDict(
+    "_OptionalListCodegenJobsRequestListCodegenJobsPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class ExportFormsRequestExportFormsPaginateTypeDef(
-    _RequiredExportFormsRequestExportFormsPaginateTypeDef,
-    _OptionalExportFormsRequestExportFormsPaginateTypeDef,
+
+class ListCodegenJobsRequestListCodegenJobsPaginateTypeDef(
+    _RequiredListCodegenJobsRequestListCodegenJobsPaginateTypeDef,
+    _OptionalListCodegenJobsRequestListCodegenJobsPaginateTypeDef,
 ):
     pass
 
-_RequiredExportThemesRequestExportThemesPaginateTypeDef = TypedDict(
-    "_RequiredExportThemesRequestExportThemesPaginateTypeDef",
+
+_RequiredListCodegenJobsRequestRequestTypeDef = TypedDict(
+    "_RequiredListCodegenJobsRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
-_OptionalExportThemesRequestExportThemesPaginateTypeDef = TypedDict(
-    "_OptionalExportThemesRequestExportThemesPaginateTypeDef",
+_OptionalListCodegenJobsRequestRequestTypeDef = TypedDict(
+    "_OptionalListCodegenJobsRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "nextToken": str,
+        "maxResults": int,
     },
     total=False,
 )
 
-class ExportThemesRequestExportThemesPaginateTypeDef(
-    _RequiredExportThemesRequestExportThemesPaginateTypeDef,
-    _OptionalExportThemesRequestExportThemesPaginateTypeDef,
+
+class ListCodegenJobsRequestRequestTypeDef(
+    _RequiredListCodegenJobsRequestRequestTypeDef, _OptionalListCodegenJobsRequestRequestTypeDef
 ):
     pass
 
+
+ListCodegenJobsResponseTypeDef = TypedDict(
+    "ListCodegenJobsResponseTypeDef",
+    {
+        "entities": List["CodegenJobSummaryTypeDef"],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListComponentsRequestListComponentsPaginateTypeDef = TypedDict(
     "_RequiredListComponentsRequestListComponentsPaginateTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
 _OptionalListComponentsRequestListComponentsPaginateTypeDef = TypedDict(
     "_OptionalListComponentsRequestListComponentsPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class ListComponentsRequestListComponentsPaginateTypeDef(
     _RequiredListComponentsRequestListComponentsPaginateTypeDef,
     _OptionalListComponentsRequestListComponentsPaginateTypeDef,
 ):
     pass
 
+
+_RequiredListComponentsRequestRequestTypeDef = TypedDict(
+    "_RequiredListComponentsRequestRequestTypeDef",
+    {
+        "appId": str,
+        "environmentName": str,
+    },
+)
+_OptionalListComponentsRequestRequestTypeDef = TypedDict(
+    "_OptionalListComponentsRequestRequestTypeDef",
+    {
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+
+class ListComponentsRequestRequestTypeDef(
+    _RequiredListComponentsRequestRequestTypeDef, _OptionalListComponentsRequestRequestTypeDef
+):
+    pass
+
+
+ListComponentsResponseTypeDef = TypedDict(
+    "ListComponentsResponseTypeDef",
+    {
+        "entities": List["ComponentSummaryTypeDef"],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListFormsRequestListFormsPaginateTypeDef = TypedDict(
     "_RequiredListFormsRequestListFormsPaginateTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
 _OptionalListFormsRequestListFormsPaginateTypeDef = TypedDict(
     "_OptionalListFormsRequestListFormsPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class ListFormsRequestListFormsPaginateTypeDef(
     _RequiredListFormsRequestListFormsPaginateTypeDef,
     _OptionalListFormsRequestListFormsPaginateTypeDef,
 ):
     pass
 
+
+_RequiredListFormsRequestRequestTypeDef = TypedDict(
+    "_RequiredListFormsRequestRequestTypeDef",
+    {
+        "appId": str,
+        "environmentName": str,
+    },
+)
+_OptionalListFormsRequestRequestTypeDef = TypedDict(
+    "_OptionalListFormsRequestRequestTypeDef",
+    {
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+
+class ListFormsRequestRequestTypeDef(
+    _RequiredListFormsRequestRequestTypeDef, _OptionalListFormsRequestRequestTypeDef
+):
+    pass
+
+
+ListFormsResponseTypeDef = TypedDict(
+    "ListFormsResponseTypeDef",
+    {
+        "entities": List["FormSummaryTypeDef"],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListThemesRequestListThemesPaginateTypeDef = TypedDict(
     "_RequiredListThemesRequestListThemesPaginateTypeDef",
     {
         "appId": str,
         "environmentName": str,
     },
 )
 _OptionalListThemesRequestListThemesPaginateTypeDef = TypedDict(
     "_OptionalListThemesRequestListThemesPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class ListThemesRequestListThemesPaginateTypeDef(
     _RequiredListThemesRequestListThemesPaginateTypeDef,
     _OptionalListThemesRequestListThemesPaginateTypeDef,
 ):
     pass
 
-FormButtonTypeDef = TypedDict(
-    "FormButtonTypeDef",
-    {
-        "children": str,
-        "excluded": bool,
-        "position": FieldPositionTypeDef,
-    },
-    total=False,
-)
 
-_RequiredSectionalElementTypeDef = TypedDict(
-    "_RequiredSectionalElementTypeDef",
+_RequiredListThemesRequestRequestTypeDef = TypedDict(
+    "_RequiredListThemesRequestRequestTypeDef",
     {
-        "type": str,
+        "appId": str,
+        "environmentName": str,
     },
 )
-_OptionalSectionalElementTypeDef = TypedDict(
-    "_OptionalSectionalElementTypeDef",
+_OptionalListThemesRequestRequestTypeDef = TypedDict(
+    "_OptionalListThemesRequestRequestTypeDef",
     {
-        "level": int,
-        "orientation": str,
-        "position": FieldPositionTypeDef,
-        "text": str,
+        "nextToken": str,
+        "maxResults": int,
     },
     total=False,
 )
 
-class SectionalElementTypeDef(_RequiredSectionalElementTypeDef, _OptionalSectionalElementTypeDef):
+
+class ListThemesRequestRequestTypeDef(
+    _RequiredListThemesRequestRequestTypeDef, _OptionalListThemesRequestRequestTypeDef
+):
     pass
 
-_RequiredValueMappingTypeDef = TypedDict(
-    "_RequiredValueMappingTypeDef",
+
+ListThemesResponseTypeDef = TypedDict(
+    "ListThemesResponseTypeDef",
     {
-        "value": FormInputValuePropertyTypeDef,
+        "entities": List["ThemeSummaryTypeDef"],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalValueMappingTypeDef = TypedDict(
-    "_OptionalValueMappingTypeDef",
+
+MutationActionSetStateParameterTypeDef = TypedDict(
+    "MutationActionSetStateParameterTypeDef",
     {
-        "displayValue": FormInputValuePropertyTypeDef,
+        "componentName": str,
+        "property": str,
+        "set": "ComponentPropertyTypeDef",
     },
-    total=False,
 )
 
-class ValueMappingTypeDef(_RequiredValueMappingTypeDef, _OptionalValueMappingTypeDef):
-    pass
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
+    {
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
+    },
+    total=False,
+)
 
-FormStyleTypeDef = TypedDict(
-    "FormStyleTypeDef",
+PredicateTypeDef = TypedDict(
+    "PredicateTypeDef",
     {
-        "horizontalGap": FormStyleConfigTypeDef,
-        "outerPadding": FormStyleConfigTypeDef,
-        "verticalGap": FormStyleConfigTypeDef,
+        "or": Sequence[Dict[str, Any]],
+        "and": Sequence[Dict[str, Any]],
+        "field": str,
+        "operator": str,
+        "operand": str,
+        "operandType": str,
     },
     total=False,
 )
 
-ListThemesResponseTypeDef = TypedDict(
-    "ListThemesResponseTypeDef",
+PutMetadataFlagBodyTypeDef = TypedDict(
+    "PutMetadataFlagBodyTypeDef",
     {
-        "entities": List[ThemeSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "newValue": str,
     },
 )
 
 PutMetadataFlagRequestRequestTypeDef = TypedDict(
     "PutMetadataFlagRequestRequestTypeDef",
     {
         "appId": str,
-        "body": PutMetadataFlagBodyTypeDef,
         "environmentName": str,
         "featureName": str,
+        "body": "PutMetadataFlagBodyTypeDef",
     },
 )
 
-RefreshTokenRequestRequestTypeDef = TypedDict(
-    "RefreshTokenRequestRequestTypeDef",
+ReactStartCodegenJobDataTypeDef = TypedDict(
+    "ReactStartCodegenJobDataTypeDef",
     {
-        "provider": Literal["figma"],
-        "refreshTokenBody": RefreshTokenRequestBodyTypeDef,
+        "module": JSModuleType,
+        "target": JSTargetType,
+        "script": JSScriptType,
+        "renderTypeDeclarations": bool,
+        "inlineSourceMap": bool,
     },
+    total=False,
 )
 
-_RequiredUpdateThemeRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateThemeRequestRequestTypeDef",
+_RequiredRefreshTokenRequestBodyTypeDef = TypedDict(
+    "_RequiredRefreshTokenRequestBodyTypeDef",
     {
-        "appId": str,
-        "environmentName": str,
-        "id": str,
-        "updatedTheme": UpdateThemeDataTypeDef,
+        "token": str,
     },
 )
-_OptionalUpdateThemeRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateThemeRequestRequestTypeDef",
+_OptionalRefreshTokenRequestBodyTypeDef = TypedDict(
+    "_OptionalRefreshTokenRequestBodyTypeDef",
     {
-        "clientToken": str,
+        "clientId": str,
     },
     total=False,
 )
 
-class UpdateThemeRequestRequestTypeDef(
-    _RequiredUpdateThemeRequestRequestTypeDef, _OptionalUpdateThemeRequestRequestTypeDef
+
+class RefreshTokenRequestBodyTypeDef(
+    _RequiredRefreshTokenRequestBodyTypeDef, _OptionalRefreshTokenRequestBodyTypeDef
 ):
     pass
 
-ComponentEventTypeDef = TypedDict(
-    "ComponentEventTypeDef",
-    {
-        "action": str,
-        "bindingEvent": str,
-        "parameters": ActionParametersTypeDef,
-    },
-    total=False,
-)
 
-ListFormsResponseTypeDef = TypedDict(
-    "ListFormsResponseTypeDef",
+RefreshTokenRequestRequestTypeDef = TypedDict(
+    "RefreshTokenRequestRequestTypeDef",
     {
-        "entities": List[FormSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "provider": Literal["figma"],
+        "refreshTokenBody": "RefreshTokenRequestBodyTypeDef",
     },
 )
 
-FormCTATypeDef = TypedDict(
-    "FormCTATypeDef",
+RefreshTokenResponseTypeDef = TypedDict(
+    "RefreshTokenResponseTypeDef",
     {
-        "cancel": FormButtonTypeDef,
-        "clear": FormButtonTypeDef,
-        "position": FormButtonsPositionType,
-        "submit": FormButtonTypeDef,
+        "accessToken": str,
+        "expiresIn": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ValueMappingsTypeDef = TypedDict(
-    "ValueMappingsTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "values": Sequence[ValueMappingTypeDef],
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-_RequiredComponentChildTypeDef = TypedDict(
-    "_RequiredComponentChildTypeDef",
+_RequiredSectionalElementTypeDef = TypedDict(
+    "_RequiredSectionalElementTypeDef",
     {
-        "componentType": str,
-        "name": str,
-        "properties": Mapping[str, "ComponentPropertyTypeDef"],
+        "type": str,
     },
 )
-_OptionalComponentChildTypeDef = TypedDict(
-    "_OptionalComponentChildTypeDef",
+_OptionalSectionalElementTypeDef = TypedDict(
+    "_OptionalSectionalElementTypeDef",
     {
-        "children": Sequence[Dict[str, Any]],
-        "events": Mapping[str, ComponentEventTypeDef],
-        "sourceId": str,
+        "position": "FieldPositionTypeDef",
+        "text": str,
+        "level": int,
+        "orientation": str,
+        "excluded": bool,
     },
     total=False,
 )
 
-class ComponentChildTypeDef(_RequiredComponentChildTypeDef, _OptionalComponentChildTypeDef):
+
+class SectionalElementTypeDef(_RequiredSectionalElementTypeDef, _OptionalSectionalElementTypeDef):
     pass
 
-_RequiredComponentTypeDef = TypedDict(
-    "_RequiredComponentTypeDef",
-    {
-        "appId": str,
-        "bindingProperties": Dict[str, ComponentBindingPropertiesValueTypeDef],
-        "componentType": str,
-        "createdAt": datetime,
-        "environmentName": str,
-        "id": str,
-        "name": str,
-        "overrides": Dict[str, Dict[str, str]],
-        "properties": Dict[str, "ComponentPropertyTypeDef"],
-        "variants": List[ComponentVariantTypeDef],
-    },
-)
-_OptionalComponentTypeDef = TypedDict(
-    "_OptionalComponentTypeDef",
+
+SortPropertyTypeDef = TypedDict(
+    "SortPropertyTypeDef",
     {
-        "children": List["ComponentChildTypeDef"],
-        "collectionProperties": Dict[str, ComponentDataConfigurationTypeDef],
-        "events": Dict[str, ComponentEventTypeDef],
-        "modifiedAt": datetime,
-        "schemaVersion": str,
-        "sourceId": str,
-        "tags": Dict[str, str],
+        "field": str,
+        "direction": SortDirectionType,
     },
-    total=False,
 )
 
-class ComponentTypeDef(_RequiredComponentTypeDef, _OptionalComponentTypeDef):
-    pass
-
-_RequiredCreateComponentDataTypeDef = TypedDict(
-    "_RequiredCreateComponentDataTypeDef",
+_RequiredStartCodegenJobDataTypeDef = TypedDict(
+    "_RequiredStartCodegenJobDataTypeDef",
     {
-        "bindingProperties": Mapping[str, ComponentBindingPropertiesValueTypeDef],
-        "componentType": str,
-        "name": str,
-        "overrides": Mapping[str, Mapping[str, str]],
-        "properties": Mapping[str, "ComponentPropertyTypeDef"],
-        "variants": Sequence[ComponentVariantTypeDef],
+        "renderConfig": "CodegenJobRenderConfigTypeDef",
     },
 )
-_OptionalCreateComponentDataTypeDef = TypedDict(
-    "_OptionalCreateComponentDataTypeDef",
+_OptionalStartCodegenJobDataTypeDef = TypedDict(
+    "_OptionalStartCodegenJobDataTypeDef",
     {
-        "children": Sequence["ComponentChildTypeDef"],
-        "collectionProperties": Mapping[str, ComponentDataConfigurationTypeDef],
-        "events": Mapping[str, ComponentEventTypeDef],
-        "schemaVersion": str,
-        "sourceId": str,
+        "genericDataSchema": "CodegenJobGenericDataSchemaTypeDef",
+        "autoGenerateForms": bool,
+        "features": "CodegenFeatureFlagsTypeDef",
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-class CreateComponentDataTypeDef(
-    _RequiredCreateComponentDataTypeDef, _OptionalCreateComponentDataTypeDef
+
+class StartCodegenJobDataTypeDef(
+    _RequiredStartCodegenJobDataTypeDef, _OptionalStartCodegenJobDataTypeDef
 ):
     pass
 
-UpdateComponentDataTypeDef = TypedDict(
-    "UpdateComponentDataTypeDef",
-    {
-        "bindingProperties": Mapping[str, ComponentBindingPropertiesValueTypeDef],
-        "children": Sequence["ComponentChildTypeDef"],
-        "collectionProperties": Mapping[str, ComponentDataConfigurationTypeDef],
-        "componentType": str,
-        "events": Mapping[str, ComponentEventTypeDef],
-        "id": str,
-        "name": str,
-        "overrides": Mapping[str, Mapping[str, str]],
-        "properties": Mapping[str, "ComponentPropertyTypeDef"],
-        "schemaVersion": str,
-        "sourceId": str,
-        "variants": Sequence[ComponentVariantTypeDef],
-    },
-    total=False,
-)
 
-_RequiredFieldInputConfigTypeDef = TypedDict(
-    "_RequiredFieldInputConfigTypeDef",
+_RequiredStartCodegenJobRequestRequestTypeDef = TypedDict(
+    "_RequiredStartCodegenJobRequestRequestTypeDef",
     {
-        "type": str,
+        "appId": str,
+        "environmentName": str,
+        "codegenJobToCreate": "StartCodegenJobDataTypeDef",
     },
 )
-_OptionalFieldInputConfigTypeDef = TypedDict(
-    "_OptionalFieldInputConfigTypeDef",
+_OptionalStartCodegenJobRequestRequestTypeDef = TypedDict(
+    "_OptionalStartCodegenJobRequestRequestTypeDef",
     {
-        "defaultChecked": bool,
-        "defaultCountryCode": str,
-        "defaultValue": str,
-        "descriptiveText": str,
-        "isArray": bool,
-        "maxValue": float,
-        "minValue": float,
-        "name": str,
-        "placeholder": str,
-        "readOnly": bool,
-        "required": bool,
-        "step": float,
-        "value": str,
-        "valueMappings": ValueMappingsTypeDef,
+        "clientToken": str,
     },
     total=False,
 )
 
-class FieldInputConfigTypeDef(_RequiredFieldInputConfigTypeDef, _OptionalFieldInputConfigTypeDef):
+
+class StartCodegenJobRequestRequestTypeDef(
+    _RequiredStartCodegenJobRequestRequestTypeDef, _OptionalStartCodegenJobRequestRequestTypeDef
+):
     pass
 
-CreateComponentResponseTypeDef = TypedDict(
-    "CreateComponentResponseTypeDef",
+
+StartCodegenJobResponseTypeDef = TypedDict(
+    "StartCodegenJobResponseTypeDef",
     {
-        "entity": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "entity": "CodegenJobTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ExportComponentsResponseTypeDef = TypedDict(
-    "ExportComponentsResponseTypeDef",
+ThemeSummaryTypeDef = TypedDict(
+    "ThemeSummaryTypeDef",
     {
-        "entities": List[ComponentTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "appId": str,
+        "environmentName": str,
+        "id": str,
+        "name": str,
     },
 )
 
-GetComponentResponseTypeDef = TypedDict(
-    "GetComponentResponseTypeDef",
+_RequiredThemeTypeDef = TypedDict(
+    "_RequiredThemeTypeDef",
     {
-        "component": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "appId": str,
+        "environmentName": str,
+        "id": str,
+        "name": str,
+        "createdAt": datetime,
+        "values": List["ThemeValuesTypeDef"],
     },
 )
-
-UpdateComponentResponseTypeDef = TypedDict(
-    "UpdateComponentResponseTypeDef",
+_OptionalThemeTypeDef = TypedDict(
+    "_OptionalThemeTypeDef",
     {
-        "entity": ComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "modifiedAt": datetime,
+        "overrides": List["ThemeValuesTypeDef"],
+        "tags": Dict[str, str],
     },
+    total=False,
 )
 
-_RequiredCreateComponentRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateComponentRequestRequestTypeDef",
+
+class ThemeTypeDef(_RequiredThemeTypeDef, _OptionalThemeTypeDef):
+    pass
+
+
+ThemeValueTypeDef = TypedDict(
+    "ThemeValueTypeDef",
     {
-        "appId": str,
-        "componentToCreate": CreateComponentDataTypeDef,
-        "environmentName": str,
+        "value": str,
+        "children": Sequence[Dict[str, Any]],
     },
+    total=False,
 )
-_OptionalCreateComponentRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateComponentRequestRequestTypeDef",
+
+ThemeValuesTypeDef = TypedDict(
+    "ThemeValuesTypeDef",
     {
-        "clientToken": str,
+        "key": str,
+        "value": Dict[str, Any],
     },
     total=False,
 )
 
-class CreateComponentRequestRequestTypeDef(
-    _RequiredCreateComponentRequestRequestTypeDef, _OptionalCreateComponentRequestRequestTypeDef
-):
-    pass
+UpdateComponentDataTypeDef = TypedDict(
+    "UpdateComponentDataTypeDef",
+    {
+        "id": str,
+        "name": str,
+        "sourceId": str,
+        "componentType": str,
+        "properties": Mapping[str, "ComponentPropertyTypeDef"],
+        "children": Sequence["ComponentChildTypeDef"],
+        "variants": Sequence["ComponentVariantTypeDef"],
+        "overrides": Mapping[str, Mapping[str, str]],
+        "bindingProperties": Mapping[str, "ComponentBindingPropertiesValueTypeDef"],
+        "collectionProperties": Mapping[str, "ComponentDataConfigurationTypeDef"],
+        "events": Mapping[str, "ComponentEventTypeDef"],
+        "schemaVersion": str,
+    },
+    total=False,
+)
 
 _RequiredUpdateComponentRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateComponentRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
         "id": str,
-        "updatedComponent": UpdateComponentDataTypeDef,
+        "updatedComponent": "UpdateComponentDataTypeDef",
     },
 )
 _OptionalUpdateComponentRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateComponentRequestRequestTypeDef",
     {
         "clientToken": str,
     },
     total=False,
 )
 
+
 class UpdateComponentRequestRequestTypeDef(
     _RequiredUpdateComponentRequestRequestTypeDef, _OptionalUpdateComponentRequestRequestTypeDef
 ):
     pass
 
-FieldConfigTypeDef = TypedDict(
-    "FieldConfigTypeDef",
+
+UpdateComponentResponseTypeDef = TypedDict(
+    "UpdateComponentResponseTypeDef",
     {
-        "excluded": bool,
-        "inputType": FieldInputConfigTypeDef,
-        "label": str,
-        "position": FieldPositionTypeDef,
-        "validations": Sequence[FieldValidationConfigurationTypeDef],
+        "entity": "ComponentTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredCreateFormDataTypeDef = TypedDict(
-    "_RequiredCreateFormDataTypeDef",
+UpdateFormDataTypeDef = TypedDict(
+    "UpdateFormDataTypeDef",
     {
-        "dataType": FormDataTypeConfigTypeDef,
-        "fields": Mapping[str, FieldConfigTypeDef],
-        "formActionType": FormActionTypeType,
         "name": str,
+        "dataType": "FormDataTypeConfigTypeDef",
+        "formActionType": FormActionTypeType,
+        "fields": Mapping[str, "FieldConfigTypeDef"],
+        "style": "FormStyleTypeDef",
+        "sectionalElements": Mapping[str, "SectionalElementTypeDef"],
         "schemaVersion": str,
-        "sectionalElements": Mapping[str, SectionalElementTypeDef],
-        "style": FormStyleTypeDef,
-    },
-)
-_OptionalCreateFormDataTypeDef = TypedDict(
-    "_OptionalCreateFormDataTypeDef",
-    {
-        "cta": FormCTATypeDef,
-        "tags": Mapping[str, str],
+        "cta": "FormCTATypeDef",
+        "labelDecorator": LabelDecoratorType,
     },
     total=False,
 )
 
-class CreateFormDataTypeDef(_RequiredCreateFormDataTypeDef, _OptionalCreateFormDataTypeDef):
-    pass
-
-_RequiredFormTypeDef = TypedDict(
-    "_RequiredFormTypeDef",
+_RequiredUpdateFormRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateFormRequestRequestTypeDef",
     {
         "appId": str,
-        "dataType": FormDataTypeConfigTypeDef,
         "environmentName": str,
-        "fields": Dict[str, FieldConfigTypeDef],
-        "formActionType": FormActionTypeType,
         "id": str,
-        "name": str,
-        "schemaVersion": str,
-        "sectionalElements": Dict[str, SectionalElementTypeDef],
-        "style": FormStyleTypeDef,
+        "updatedForm": "UpdateFormDataTypeDef",
     },
 )
-_OptionalFormTypeDef = TypedDict(
-    "_OptionalFormTypeDef",
+_OptionalUpdateFormRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateFormRequestRequestTypeDef",
     {
-        "cta": FormCTATypeDef,
-        "tags": Dict[str, str],
+        "clientToken": str,
     },
     total=False,
 )
 
-class FormTypeDef(_RequiredFormTypeDef, _OptionalFormTypeDef):
+
+class UpdateFormRequestRequestTypeDef(
+    _RequiredUpdateFormRequestRequestTypeDef, _OptionalUpdateFormRequestRequestTypeDef
+):
     pass
 
-UpdateFormDataTypeDef = TypedDict(
-    "UpdateFormDataTypeDef",
+
+UpdateFormResponseTypeDef = TypedDict(
+    "UpdateFormResponseTypeDef",
     {
-        "cta": FormCTATypeDef,
-        "dataType": FormDataTypeConfigTypeDef,
-        "fields": Mapping[str, FieldConfigTypeDef],
-        "formActionType": FormActionTypeType,
+        "entity": "FormTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredUpdateThemeDataTypeDef = TypedDict(
+    "_RequiredUpdateThemeDataTypeDef",
+    {
+        "values": Sequence["ThemeValuesTypeDef"],
+    },
+)
+_OptionalUpdateThemeDataTypeDef = TypedDict(
+    "_OptionalUpdateThemeDataTypeDef",
+    {
+        "id": str,
         "name": str,
-        "schemaVersion": str,
-        "sectionalElements": Mapping[str, SectionalElementTypeDef],
-        "style": FormStyleTypeDef,
+        "overrides": Sequence["ThemeValuesTypeDef"],
     },
     total=False,
 )
 
-_RequiredCreateFormRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateFormRequestRequestTypeDef",
+
+class UpdateThemeDataTypeDef(_RequiredUpdateThemeDataTypeDef, _OptionalUpdateThemeDataTypeDef):
+    pass
+
+
+_RequiredUpdateThemeRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateThemeRequestRequestTypeDef",
     {
         "appId": str,
         "environmentName": str,
-        "formToCreate": CreateFormDataTypeDef,
+        "id": str,
+        "updatedTheme": "UpdateThemeDataTypeDef",
     },
 )
-_OptionalCreateFormRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateFormRequestRequestTypeDef",
+_OptionalUpdateThemeRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateThemeRequestRequestTypeDef",
     {
         "clientToken": str,
     },
     total=False,
 )
 
-class CreateFormRequestRequestTypeDef(
-    _RequiredCreateFormRequestRequestTypeDef, _OptionalCreateFormRequestRequestTypeDef
+
+class UpdateThemeRequestRequestTypeDef(
+    _RequiredUpdateThemeRequestRequestTypeDef, _OptionalUpdateThemeRequestRequestTypeDef
 ):
     pass
 
-CreateFormResponseTypeDef = TypedDict(
-    "CreateFormResponseTypeDef",
-    {
-        "entity": FormTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-ExportFormsResponseTypeDef = TypedDict(
-    "ExportFormsResponseTypeDef",
+UpdateThemeResponseTypeDef = TypedDict(
+    "UpdateThemeResponseTypeDef",
     {
-        "entities": List[FormTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "entity": "ThemeTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetFormResponseTypeDef = TypedDict(
-    "GetFormResponseTypeDef",
+_RequiredValueMappingTypeDef = TypedDict(
+    "_RequiredValueMappingTypeDef",
     {
-        "form": FormTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "value": "FormInputValuePropertyTypeDef",
     },
 )
-
-UpdateFormResponseTypeDef = TypedDict(
-    "UpdateFormResponseTypeDef",
+_OptionalValueMappingTypeDef = TypedDict(
+    "_OptionalValueMappingTypeDef",
     {
-        "entity": FormTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "displayValue": "FormInputValuePropertyTypeDef",
     },
+    total=False,
 )
 
-_RequiredUpdateFormRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateFormRequestRequestTypeDef",
+
+class ValueMappingTypeDef(_RequiredValueMappingTypeDef, _OptionalValueMappingTypeDef):
+    pass
+
+
+_RequiredValueMappingsTypeDef = TypedDict(
+    "_RequiredValueMappingsTypeDef",
     {
-        "appId": str,
-        "environmentName": str,
-        "id": str,
-        "updatedForm": UpdateFormDataTypeDef,
+        "values": Sequence["ValueMappingTypeDef"],
     },
 )
-_OptionalUpdateFormRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateFormRequestRequestTypeDef",
+_OptionalValueMappingsTypeDef = TypedDict(
+    "_OptionalValueMappingsTypeDef",
     {
-        "clientToken": str,
+        "bindingProperties": Mapping[str, "FormInputBindingPropertiesValueTypeDef"],
     },
     total=False,
 )
 
-class UpdateFormRequestRequestTypeDef(
-    _RequiredUpdateFormRequestRequestTypeDef, _OptionalUpdateFormRequestRequestTypeDef
-):
+
+class ValueMappingsTypeDef(_RequiredValueMappingsTypeDef, _OptionalValueMappingsTypeDef):
     pass
```

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder.egg-info/PKG-INFO` & `types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-amplifyuibuilder
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AmplifyUIBuilder 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AmplifyUIBuilder 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-amplifyuibuilder"></a>
 
 # types-aiobotocore-amplifyuibuilder
 
 [![PyPI - types-aiobotocore-amplifyuibuilder](https://img.shields.io/pypi/v/types-aiobotocore-amplifyuibuilder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-amplifyuibuilder)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-amplifyuibuilder.svg?color=blue)](https://pypi.org/project/types-aiobotocore-amplifyuibuilder)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-amplifyuibuilder?color=blue)](https://pypistats.org/packages/types-aiobotocore-amplifyuibuilder)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AmplifyUIBuilder 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder)
+[aiobotocore.AmplifyUIBuilder 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amplifyuibuilder.html#AmplifyUIBuilder)
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
 [types-aiobotocore-amplifyuibuilder docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amplifyuibuilder/).
 
 See how it helps to find and fix potential bugs:
 
@@ -276,14 +276,15 @@
 from aiobotocore.session import get_session
 
 from types_aiobotocore_amplifyuibuilder import AmplifyUIBuilderClient
 from types_aiobotocore_amplifyuibuilder.paginator import (
     ExportComponentsPaginator,
     ExportFormsPaginator,
     ExportThemesPaginator,
+    ListCodegenJobsPaginator,
     ListComponentsPaginator,
     ListFormsPaginator,
     ListThemesPaginator,
 )
 
 session = get_session()
 async with session.create_client("amplifyuibuilder") as client:
@@ -292,197 +293,234 @@
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     export_components_paginator: ExportComponentsPaginator = client.get_paginator(
         "export_components"
     )
     export_forms_paginator: ExportFormsPaginator = client.get_paginator("export_forms")
     export_themes_paginator: ExportThemesPaginator = client.get_paginator("export_themes")
+    list_codegen_jobs_paginator: ListCodegenJobsPaginator = client.get_paginator(
+        "list_codegen_jobs"
+    )
     list_components_paginator: ListComponentsPaginator = client.get_paginator("list_components")
     list_forms_paginator: ListFormsPaginator = client.get_paginator("list_forms")
     list_themes_paginator: ListThemesPaginator = client.get_paginator("list_themes")
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_amplifyuibuilder.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_amplifyuibuilder.literals import (
+    CodegenGenericDataFieldDataTypeType,
+    CodegenJobGenericDataSourceTypeType,
+    CodegenJobStatusType,
     ExportComponentsPaginatorName,
     ExportFormsPaginatorName,
     ExportThemesPaginatorName,
     FixedPositionType,
     FormActionTypeType,
     FormButtonsPositionType,
     FormDataSourceTypeType,
+    GenericDataRelationshipTypeType,
+    JSModuleType,
+    JSScriptType,
+    JSTargetType,
+    LabelDecoratorType,
+    ListCodegenJobsPaginatorName,
     ListComponentsPaginatorName,
     ListFormsPaginatorName,
     ListThemesPaginatorName,
     SortDirectionType,
+    StorageAccessLevelType,
     TokenProvidersType,
     AmplifyUIBuilderServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: ExportComponentsPaginatorName) -> bool:
+def check_value(value: CodegenGenericDataFieldDataTypeType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_amplifyuibuilder.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_amplifyuibuilder.type_defs import (
-    MutationActionSetStateParameterTypeDef,
+    ActionParametersTypeDef,
+    CodegenFeatureFlagsTypeDef,
+    CodegenGenericDataEnumTypeDef,
+    CodegenGenericDataFieldTypeDef,
+    CodegenGenericDataModelTypeDef,
+    CodegenGenericDataNonModelTypeDef,
+    CodegenGenericDataRelationshipTypeTypeDef,
+    CodegenJobAssetTypeDef,
+    CodegenJobGenericDataSchemaTypeDef,
+    CodegenJobRenderConfigTypeDef,
+    CodegenJobSummaryTypeDef,
+    CodegenJobTypeDef,
     ComponentBindingPropertiesValuePropertiesTypeDef,
+    ComponentBindingPropertiesValueTypeDef,
+    ComponentChildTypeDef,
     ComponentConditionPropertyTypeDef,
-    SortPropertyTypeDef,
+    ComponentDataConfigurationTypeDef,
+    ComponentEventTypeDef,
     ComponentPropertyBindingPropertiesTypeDef,
-    FormBindingElementTypeDef,
+    ComponentPropertyTypeDef,
     ComponentSummaryTypeDef,
+    ComponentTypeDef,
     ComponentVariantTypeDef,
-    ResponseMetadataTypeDef,
-    FormDataTypeConfigTypeDef,
+    CreateComponentDataTypeDef,
+    CreateComponentRequestRequestTypeDef,
+    CreateComponentResponseTypeDef,
+    CreateFormDataTypeDef,
+    CreateFormRequestRequestTypeDef,
+    CreateFormResponseTypeDef,
     CreateThemeDataTypeDef,
-    ThemeTypeDef,
+    CreateThemeRequestRequestTypeDef,
+    CreateThemeResponseTypeDef,
     DeleteComponentRequestRequestTypeDef,
     DeleteFormRequestRequestTypeDef,
     DeleteThemeRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExchangeCodeForTokenRequestBodyTypeDef,
-    PaginatorConfigTypeDef,
+    ExchangeCodeForTokenRequestRequestTypeDef,
+    ExchangeCodeForTokenResponseTypeDef,
+    ExportComponentsRequestExportComponentsPaginateTypeDef,
     ExportComponentsRequestRequestTypeDef,
+    ExportComponentsResponseTypeDef,
+    ExportFormsRequestExportFormsPaginateTypeDef,
     ExportFormsRequestRequestTypeDef,
+    ExportFormsResponseTypeDef,
+    ExportThemesRequestExportThemesPaginateTypeDef,
     ExportThemesRequestRequestTypeDef,
+    ExportThemesResponseTypeDef,
+    FieldConfigTypeDef,
+    FieldInputConfigTypeDef,
     FieldPositionTypeDef,
     FieldValidationConfigurationTypeDef,
+    FileUploaderFieldConfigTypeDef,
+    FormBindingElementTypeDef,
+    FormButtonTypeDef,
+    FormCTATypeDef,
+    FormDataTypeConfigTypeDef,
+    FormInputBindingPropertiesValuePropertiesTypeDef,
+    FormInputBindingPropertiesValueTypeDef,
+    FormInputValuePropertyBindingPropertiesTypeDef,
     FormInputValuePropertyTypeDef,
     FormStyleConfigTypeDef,
+    FormStyleTypeDef,
+    FormSummaryTypeDef,
+    FormTypeDef,
+    GetCodegenJobRequestRequestTypeDef,
+    GetCodegenJobResponseTypeDef,
     GetComponentRequestRequestTypeDef,
+    GetComponentResponseTypeDef,
     GetFormRequestRequestTypeDef,
+    GetFormResponseTypeDef,
     GetMetadataRequestRequestTypeDef,
+    GetMetadataResponseTypeDef,
     GetThemeRequestRequestTypeDef,
+    GetThemeResponseTypeDef,
+    ListCodegenJobsRequestListCodegenJobsPaginateTypeDef,
+    ListCodegenJobsRequestRequestTypeDef,
+    ListCodegenJobsResponseTypeDef,
+    ListComponentsRequestListComponentsPaginateTypeDef,
     ListComponentsRequestRequestTypeDef,
+    ListComponentsResponseTypeDef,
+    ListFormsRequestListFormsPaginateTypeDef,
     ListFormsRequestRequestTypeDef,
+    ListFormsResponseTypeDef,
+    ListThemesRequestListThemesPaginateTypeDef,
     ListThemesRequestRequestTypeDef,
-    ThemeSummaryTypeDef,
+    ListThemesResponseTypeDef,
+    MutationActionSetStateParameterTypeDef,
+    PaginatorConfigTypeDef,
     PredicateTypeDef,
     PutMetadataFlagBodyTypeDef,
+    PutMetadataFlagRequestRequestTypeDef,
+    ReactStartCodegenJobDataTypeDef,
     RefreshTokenRequestBodyTypeDef,
-    ThemeValueTypeDef,
-    ThemeValuesTypeDef,
-    UpdateThemeDataTypeDef,
-    ActionParametersTypeDef,
-    ComponentBindingPropertiesValueTypeDef,
-    ComponentDataConfigurationTypeDef,
-    ComponentPropertyTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExchangeCodeForTokenResponseTypeDef,
-    GetMetadataResponseTypeDef,
-    ListComponentsResponseTypeDef,
+    RefreshTokenRequestRequestTypeDef,
     RefreshTokenResponseTypeDef,
-    FormSummaryTypeDef,
-    CreateThemeRequestRequestTypeDef,
-    CreateThemeResponseTypeDef,
-    ExportThemesResponseTypeDef,
-    GetThemeResponseTypeDef,
-    UpdateThemeResponseTypeDef,
-    ExchangeCodeForTokenRequestRequestTypeDef,
-    ExportComponentsRequestExportComponentsPaginateTypeDef,
-    ExportFormsRequestExportFormsPaginateTypeDef,
-    ExportThemesRequestExportThemesPaginateTypeDef,
-    ListComponentsRequestListComponentsPaginateTypeDef,
-    ListFormsRequestListFormsPaginateTypeDef,
-    ListThemesRequestListThemesPaginateTypeDef,
-    FormButtonTypeDef,
+    ResponseMetadataTypeDef,
     SectionalElementTypeDef,
-    ValueMappingTypeDef,
-    FormStyleTypeDef,
-    ListThemesResponseTypeDef,
-    PutMetadataFlagRequestRequestTypeDef,
-    RefreshTokenRequestRequestTypeDef,
-    UpdateThemeRequestRequestTypeDef,
-    ComponentEventTypeDef,
-    ListFormsResponseTypeDef,
-    FormCTATypeDef,
-    ValueMappingsTypeDef,
-    ComponentChildTypeDef,
-    ComponentTypeDef,
-    CreateComponentDataTypeDef,
+    SortPropertyTypeDef,
+    StartCodegenJobDataTypeDef,
+    StartCodegenJobRequestRequestTypeDef,
+    StartCodegenJobResponseTypeDef,
+    ThemeSummaryTypeDef,
+    ThemeTypeDef,
+    ThemeValueTypeDef,
+    ThemeValuesTypeDef,
     UpdateComponentDataTypeDef,
-    FieldInputConfigTypeDef,
-    CreateComponentResponseTypeDef,
-    ExportComponentsResponseTypeDef,
-    GetComponentResponseTypeDef,
-    UpdateComponentResponseTypeDef,
-    CreateComponentRequestRequestTypeDef,
     UpdateComponentRequestRequestTypeDef,
-    FieldConfigTypeDef,
-    CreateFormDataTypeDef,
-    FormTypeDef,
+    UpdateComponentResponseTypeDef,
     UpdateFormDataTypeDef,
-    CreateFormRequestRequestTypeDef,
-    CreateFormResponseTypeDef,
-    ExportFormsResponseTypeDef,
-    GetFormResponseTypeDef,
-    UpdateFormResponseTypeDef,
     UpdateFormRequestRequestTypeDef,
+    UpdateFormResponseTypeDef,
+    UpdateThemeDataTypeDef,
+    UpdateThemeRequestRequestTypeDef,
+    UpdateThemeResponseTypeDef,
+    ValueMappingTypeDef,
+    ValueMappingsTypeDef,
 )
 
 
-def get_structure() -> MutationActionSetStateParameterTypeDef:
+def get_structure() -> ActionParametersTypeDef:
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

### Comparing `types-aiobotocore-amplifyuibuilder-2.5.0.post1/types_aiobotocore_amplifyuibuilder.egg-info/SOURCES.txt` & `types-aiobotocore-amplifyuibuilder-2.5.1/types_aiobotocore_amplifyuibuilder.egg-info/SOURCES.txt`

 * *Files identical despite different names*


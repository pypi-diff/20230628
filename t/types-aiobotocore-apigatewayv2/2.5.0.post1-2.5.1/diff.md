# Comparing `tmp/types-aiobotocore-apigatewayv2-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-apigatewayv2-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-apigatewayv2-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:10 2023, max compression
+gzip compressed data, was "types-aiobotocore-apigatewayv2-2.5.1.tar", last modified: Wed Jun 28 01:43:04 2023, max compression
```

## Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1.tar` & `types-aiobotocore-apigatewayv2-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.342924 types-aiobotocore-apigatewayv2-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:25.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    20859 2023-03-11 12:26:10.334924 types-aiobotocore-apigatewayv2-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    19268 2023-03-11 12:09:25.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:10.342924 types-aiobotocore-apigatewayv2-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:09:25.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.326924 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/
--rw-r--r--   0 runner    (1001) docker     (123)     2373 2023-03-11 12:09:25.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2372 2023-03-11 12:09:25.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:09:25.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    54790 2023-03-11 12:09:26.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    54699 2023-03-11 12:09:25.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10471 2023-03-11 12:09:26.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10469 2023-03-11 12:09:26.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12003 2023-03-11 12:09:26.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    11990 2023-03-11 12:09:26.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:25.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    75164 2023-03-11 12:09:28.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    75053 2023-03-11 12:09:27.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:25.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.334924 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    20859 2023-03-11 12:26:10.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:10.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:10.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:10.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:10.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:10.000000 types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.346090 types-aiobotocore-apigatewayv2-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:02.000000 types-aiobotocore-apigatewayv2-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20856 2023-06-28 01:43:04.346090 types-aiobotocore-apigatewayv2-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19271 2023-06-28 01:26:02.000000 types-aiobotocore-apigatewayv2-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:04.346090 types-aiobotocore-apigatewayv2-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:26:02.000000 types-aiobotocore-apigatewayv2-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.342090 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/
+-rw-r--r--   0 runner    (1001) docker     (123)     2373 2023-06-28 01:26:02.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2372 2023-06-28 01:26:02.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:26:02.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    54790 2023-06-28 01:26:02.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    54699 2023-06-28 01:26:02.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10680 2023-06-28 01:26:03.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10678 2023-06-28 01:26:03.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11903 2023-06-28 01:26:03.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11891 2023-06-28 01:26:03.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:02.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    75292 2023-06-28 01:26:05.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    75181 2023-06-28 01:26:04.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:02.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.346090 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20856 2023-06-28 01:43:04.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:04.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:04.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:04.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:04.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:04.000000 types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/LICENSE` & `types-aiobotocore-apigatewayv2-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/PKG-INFO` & `types-aiobotocore-apigatewayv2-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-apigatewayv2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ApiGatewayV2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ApiGatewayV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-apigatewayv2"></a>
 
 # types-aiobotocore-apigatewayv2
 
 [![PyPI - types-aiobotocore-apigatewayv2](https://img.shields.io/pypi/v/types-aiobotocore-apigatewayv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-apigatewayv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-apigatewayv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-apigatewayv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-apigatewayv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-apigatewayv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApiGatewayV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2)
+[aiobotocore.ApiGatewayV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2)
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
 [types-aiobotocore-apigatewayv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -368,26 +368,30 @@
 ```python
 from types_aiobotocore_apigatewayv2.type_defs import (
     AccessLogSettingsTypeDef,
     ApiMappingTypeDef,
     CorsTypeDef,
     JWTConfigurationTypeDef,
     CreateApiMappingRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateApiMappingResponseTypeDef,
     CreateDeploymentRequestRequestTypeDef,
+    CreateDeploymentResponseTypeDef,
     DomainNameConfigurationTypeDef,
     MutualTlsAuthenticationInputTypeDef,
     MutualTlsAuthenticationTypeDef,
     TlsConfigInputTypeDef,
     CreateIntegrationResponseRequestRequestTypeDef,
+    CreateIntegrationResponseResponseTypeDef,
     TlsConfigTypeDef,
     CreateModelRequestRequestTypeDef,
+    CreateModelResponseTypeDef,
     ParameterConstraintsTypeDef,
     RouteSettingsTypeDef,
     CreateVpcLinkRequestRequestTypeDef,
+    CreateVpcLinkResponseTypeDef,
     DeleteAccessLogSettingsRequestRequestTypeDef,
     DeleteApiMappingRequestRequestTypeDef,
     DeleteApiRequestRequestTypeDef,
     DeleteAuthorizerRequestRequestTypeDef,
     DeleteCorsConfigurationRequestRequestTypeDef,
     DeleteDeploymentRequestRequestTypeDef,
     DeleteDomainNameRequestRequestTypeDef,
@@ -397,89 +401,95 @@
     DeleteRouteRequestParameterRequestRequestTypeDef,
     DeleteRouteRequestRequestTypeDef,
     DeleteRouteResponseRequestRequestTypeDef,
     DeleteRouteSettingsRequestRequestTypeDef,
     DeleteStageRequestRequestTypeDef,
     DeleteVpcLinkRequestRequestTypeDef,
     DeploymentTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportApiRequestRequestTypeDef,
+    ExportApiResponseTypeDef,
     GetApiMappingRequestRequestTypeDef,
+    GetApiMappingResponseTypeDef,
     GetApiMappingsRequestRequestTypeDef,
     GetApiRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetApisRequestGetApisPaginateTypeDef,
     GetApisRequestRequestTypeDef,
     GetAuthorizerRequestRequestTypeDef,
+    GetAuthorizersRequestGetAuthorizersPaginateTypeDef,
     GetAuthorizersRequestRequestTypeDef,
     GetDeploymentRequestRequestTypeDef,
+    GetDeploymentResponseTypeDef,
+    GetDeploymentsRequestGetDeploymentsPaginateTypeDef,
     GetDeploymentsRequestRequestTypeDef,
     GetDomainNameRequestRequestTypeDef,
+    GetDomainNamesRequestGetDomainNamesPaginateTypeDef,
     GetDomainNamesRequestRequestTypeDef,
     GetIntegrationRequestRequestTypeDef,
     GetIntegrationResponseRequestRequestTypeDef,
+    GetIntegrationResponseResponseTypeDef,
+    GetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef,
     GetIntegrationResponsesRequestRequestTypeDef,
     IntegrationResponseTypeDef,
+    GetIntegrationsRequestGetIntegrationsPaginateTypeDef,
     GetIntegrationsRequestRequestTypeDef,
     GetModelRequestRequestTypeDef,
+    GetModelResponseTypeDef,
     GetModelTemplateRequestRequestTypeDef,
+    GetModelTemplateResponseTypeDef,
+    GetModelsRequestGetModelsPaginateTypeDef,
     GetModelsRequestRequestTypeDef,
     ModelTypeDef,
     GetRouteRequestRequestTypeDef,
     GetRouteResponseRequestRequestTypeDef,
+    GetRouteResponsesRequestGetRouteResponsesPaginateTypeDef,
     GetRouteResponsesRequestRequestTypeDef,
+    GetRoutesRequestGetRoutesPaginateTypeDef,
     GetRoutesRequestRequestTypeDef,
     GetStageRequestRequestTypeDef,
+    GetStagesRequestGetStagesPaginateTypeDef,
     GetStagesRequestRequestTypeDef,
     GetTagsRequestRequestTypeDef,
+    GetTagsResponseTypeDef,
     GetVpcLinkRequestRequestTypeDef,
+    GetVpcLinkResponseTypeDef,
     GetVpcLinksRequestRequestTypeDef,
     VpcLinkTypeDef,
     ImportApiRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ReimportApiRequestRequestTypeDef,
     ResetAuthorizersCacheRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApiMappingRequestRequestTypeDef,
+    UpdateApiMappingResponseTypeDef,
     UpdateDeploymentRequestRequestTypeDef,
+    UpdateDeploymentResponseTypeDef,
     UpdateIntegrationResponseRequestRequestTypeDef,
+    UpdateIntegrationResponseResponseTypeDef,
     UpdateModelRequestRequestTypeDef,
+    UpdateModelResponseTypeDef,
     UpdateVpcLinkRequestRequestTypeDef,
+    UpdateVpcLinkResponseTypeDef,
+    GetApiMappingsResponseTypeDef,
     ApiTypeDef,
     CreateApiRequestRequestTypeDef,
-    UpdateApiRequestRequestTypeDef,
-    AuthorizerTypeDef,
-    CreateAuthorizerRequestRequestTypeDef,
-    UpdateAuthorizerRequestRequestTypeDef,
-    CreateApiMappingResponseTypeDef,
     CreateApiResponseTypeDef,
-    CreateAuthorizerResponseTypeDef,
-    CreateDeploymentResponseTypeDef,
-    CreateIntegrationResponseResponseTypeDef,
-    CreateModelResponseTypeDef,
-    CreateVpcLinkResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportApiResponseTypeDef,
-    GetApiMappingResponseTypeDef,
-    GetApiMappingsResponseTypeDef,
     GetApiResponseTypeDef,
-    GetAuthorizerResponseTypeDef,
-    GetDeploymentResponseTypeDef,
-    GetIntegrationResponseResponseTypeDef,
-    GetModelResponseTypeDef,
-    GetModelTemplateResponseTypeDef,
-    GetTagsResponseTypeDef,
-    GetVpcLinkResponseTypeDef,
     ImportApiResponseTypeDef,
     ReimportApiResponseTypeDef,
-    UpdateApiMappingResponseTypeDef,
+    UpdateApiRequestRequestTypeDef,
     UpdateApiResponseTypeDef,
+    AuthorizerTypeDef,
+    CreateAuthorizerRequestRequestTypeDef,
+    CreateAuthorizerResponseTypeDef,
+    GetAuthorizerResponseTypeDef,
+    UpdateAuthorizerRequestRequestTypeDef,
     UpdateAuthorizerResponseTypeDef,
-    UpdateDeploymentResponseTypeDef,
-    UpdateIntegrationResponseResponseTypeDef,
-    UpdateModelResponseTypeDef,
-    UpdateVpcLinkResponseTypeDef,
     CreateDomainNameRequestRequestTypeDef,
     UpdateDomainNameRequestRequestTypeDef,
     CreateDomainNameResponseTypeDef,
     DomainNameTypeDef,
     GetDomainNameResponseTypeDef,
     UpdateDomainNameResponseTypeDef,
     CreateIntegrationRequestRequestTypeDef,
@@ -503,24 +513,14 @@
     CreateStageRequestRequestTypeDef,
     CreateStageResponseTypeDef,
     GetStageResponseTypeDef,
     StageTypeDef,
     UpdateStageRequestRequestTypeDef,
     UpdateStageResponseTypeDef,
     GetDeploymentsResponseTypeDef,
-    GetApisRequestGetApisPaginateTypeDef,
-    GetAuthorizersRequestGetAuthorizersPaginateTypeDef,
-    GetDeploymentsRequestGetDeploymentsPaginateTypeDef,
-    GetDomainNamesRequestGetDomainNamesPaginateTypeDef,
-    GetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef,
-    GetIntegrationsRequestGetIntegrationsPaginateTypeDef,
-    GetModelsRequestGetModelsPaginateTypeDef,
-    GetRouteResponsesRequestGetRouteResponsesPaginateTypeDef,
-    GetRoutesRequestGetRoutesPaginateTypeDef,
-    GetStagesRequestGetStagesPaginateTypeDef,
     GetIntegrationResponsesResponseTypeDef,
     GetModelsResponseTypeDef,
     GetVpcLinksResponseTypeDef,
     GetApisResponseTypeDef,
     GetAuthorizersResponseTypeDef,
     GetDomainNamesResponseTypeDef,
     GetIntegrationsResponseTypeDef,
@@ -537,43 +537,43 @@
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

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/README.md` & `types-aiobotocore-apigatewayv2-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-apigatewayv2"></a>
 
 # types-aiobotocore-apigatewayv2
 
 [![PyPI - types-aiobotocore-apigatewayv2](https://img.shields.io/pypi/v/types-aiobotocore-apigatewayv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-apigatewayv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-apigatewayv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-apigatewayv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-apigatewayv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-apigatewayv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApiGatewayV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2)
+[aiobotocore.ApiGatewayV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2)
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
 [types-aiobotocore-apigatewayv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -335,26 +335,30 @@
 ```python
 from types_aiobotocore_apigatewayv2.type_defs import (
     AccessLogSettingsTypeDef,
     ApiMappingTypeDef,
     CorsTypeDef,
     JWTConfigurationTypeDef,
     CreateApiMappingRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateApiMappingResponseTypeDef,
     CreateDeploymentRequestRequestTypeDef,
+    CreateDeploymentResponseTypeDef,
     DomainNameConfigurationTypeDef,
     MutualTlsAuthenticationInputTypeDef,
     MutualTlsAuthenticationTypeDef,
     TlsConfigInputTypeDef,
     CreateIntegrationResponseRequestRequestTypeDef,
+    CreateIntegrationResponseResponseTypeDef,
     TlsConfigTypeDef,
     CreateModelRequestRequestTypeDef,
+    CreateModelResponseTypeDef,
     ParameterConstraintsTypeDef,
     RouteSettingsTypeDef,
     CreateVpcLinkRequestRequestTypeDef,
+    CreateVpcLinkResponseTypeDef,
     DeleteAccessLogSettingsRequestRequestTypeDef,
     DeleteApiMappingRequestRequestTypeDef,
     DeleteApiRequestRequestTypeDef,
     DeleteAuthorizerRequestRequestTypeDef,
     DeleteCorsConfigurationRequestRequestTypeDef,
     DeleteDeploymentRequestRequestTypeDef,
     DeleteDomainNameRequestRequestTypeDef,
@@ -364,89 +368,95 @@
     DeleteRouteRequestParameterRequestRequestTypeDef,
     DeleteRouteRequestRequestTypeDef,
     DeleteRouteResponseRequestRequestTypeDef,
     DeleteRouteSettingsRequestRequestTypeDef,
     DeleteStageRequestRequestTypeDef,
     DeleteVpcLinkRequestRequestTypeDef,
     DeploymentTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportApiRequestRequestTypeDef,
+    ExportApiResponseTypeDef,
     GetApiMappingRequestRequestTypeDef,
+    GetApiMappingResponseTypeDef,
     GetApiMappingsRequestRequestTypeDef,
     GetApiRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetApisRequestGetApisPaginateTypeDef,
     GetApisRequestRequestTypeDef,
     GetAuthorizerRequestRequestTypeDef,
+    GetAuthorizersRequestGetAuthorizersPaginateTypeDef,
     GetAuthorizersRequestRequestTypeDef,
     GetDeploymentRequestRequestTypeDef,
+    GetDeploymentResponseTypeDef,
+    GetDeploymentsRequestGetDeploymentsPaginateTypeDef,
     GetDeploymentsRequestRequestTypeDef,
     GetDomainNameRequestRequestTypeDef,
+    GetDomainNamesRequestGetDomainNamesPaginateTypeDef,
     GetDomainNamesRequestRequestTypeDef,
     GetIntegrationRequestRequestTypeDef,
     GetIntegrationResponseRequestRequestTypeDef,
+    GetIntegrationResponseResponseTypeDef,
+    GetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef,
     GetIntegrationResponsesRequestRequestTypeDef,
     IntegrationResponseTypeDef,
+    GetIntegrationsRequestGetIntegrationsPaginateTypeDef,
     GetIntegrationsRequestRequestTypeDef,
     GetModelRequestRequestTypeDef,
+    GetModelResponseTypeDef,
     GetModelTemplateRequestRequestTypeDef,
+    GetModelTemplateResponseTypeDef,
+    GetModelsRequestGetModelsPaginateTypeDef,
     GetModelsRequestRequestTypeDef,
     ModelTypeDef,
     GetRouteRequestRequestTypeDef,
     GetRouteResponseRequestRequestTypeDef,
+    GetRouteResponsesRequestGetRouteResponsesPaginateTypeDef,
     GetRouteResponsesRequestRequestTypeDef,
+    GetRoutesRequestGetRoutesPaginateTypeDef,
     GetRoutesRequestRequestTypeDef,
     GetStageRequestRequestTypeDef,
+    GetStagesRequestGetStagesPaginateTypeDef,
     GetStagesRequestRequestTypeDef,
     GetTagsRequestRequestTypeDef,
+    GetTagsResponseTypeDef,
     GetVpcLinkRequestRequestTypeDef,
+    GetVpcLinkResponseTypeDef,
     GetVpcLinksRequestRequestTypeDef,
     VpcLinkTypeDef,
     ImportApiRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ReimportApiRequestRequestTypeDef,
     ResetAuthorizersCacheRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApiMappingRequestRequestTypeDef,
+    UpdateApiMappingResponseTypeDef,
     UpdateDeploymentRequestRequestTypeDef,
+    UpdateDeploymentResponseTypeDef,
     UpdateIntegrationResponseRequestRequestTypeDef,
+    UpdateIntegrationResponseResponseTypeDef,
     UpdateModelRequestRequestTypeDef,
+    UpdateModelResponseTypeDef,
     UpdateVpcLinkRequestRequestTypeDef,
+    UpdateVpcLinkResponseTypeDef,
+    GetApiMappingsResponseTypeDef,
     ApiTypeDef,
     CreateApiRequestRequestTypeDef,
-    UpdateApiRequestRequestTypeDef,
-    AuthorizerTypeDef,
-    CreateAuthorizerRequestRequestTypeDef,
-    UpdateAuthorizerRequestRequestTypeDef,
-    CreateApiMappingResponseTypeDef,
     CreateApiResponseTypeDef,
-    CreateAuthorizerResponseTypeDef,
-    CreateDeploymentResponseTypeDef,
-    CreateIntegrationResponseResponseTypeDef,
-    CreateModelResponseTypeDef,
-    CreateVpcLinkResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportApiResponseTypeDef,
-    GetApiMappingResponseTypeDef,
-    GetApiMappingsResponseTypeDef,
     GetApiResponseTypeDef,
-    GetAuthorizerResponseTypeDef,
-    GetDeploymentResponseTypeDef,
-    GetIntegrationResponseResponseTypeDef,
-    GetModelResponseTypeDef,
-    GetModelTemplateResponseTypeDef,
-    GetTagsResponseTypeDef,
-    GetVpcLinkResponseTypeDef,
     ImportApiResponseTypeDef,
     ReimportApiResponseTypeDef,
-    UpdateApiMappingResponseTypeDef,
+    UpdateApiRequestRequestTypeDef,
     UpdateApiResponseTypeDef,
+    AuthorizerTypeDef,
+    CreateAuthorizerRequestRequestTypeDef,
+    CreateAuthorizerResponseTypeDef,
+    GetAuthorizerResponseTypeDef,
+    UpdateAuthorizerRequestRequestTypeDef,
     UpdateAuthorizerResponseTypeDef,
-    UpdateDeploymentResponseTypeDef,
-    UpdateIntegrationResponseResponseTypeDef,
-    UpdateModelResponseTypeDef,
-    UpdateVpcLinkResponseTypeDef,
     CreateDomainNameRequestRequestTypeDef,
     UpdateDomainNameRequestRequestTypeDef,
     CreateDomainNameResponseTypeDef,
     DomainNameTypeDef,
     GetDomainNameResponseTypeDef,
     UpdateDomainNameResponseTypeDef,
     CreateIntegrationRequestRequestTypeDef,
@@ -470,24 +480,14 @@
     CreateStageRequestRequestTypeDef,
     CreateStageResponseTypeDef,
     GetStageResponseTypeDef,
     StageTypeDef,
     UpdateStageRequestRequestTypeDef,
     UpdateStageResponseTypeDef,
     GetDeploymentsResponseTypeDef,
-    GetApisRequestGetApisPaginateTypeDef,
-    GetAuthorizersRequestGetAuthorizersPaginateTypeDef,
-    GetDeploymentsRequestGetDeploymentsPaginateTypeDef,
-    GetDomainNamesRequestGetDomainNamesPaginateTypeDef,
-    GetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef,
-    GetIntegrationsRequestGetIntegrationsPaginateTypeDef,
-    GetModelsRequestGetModelsPaginateTypeDef,
-    GetRouteResponsesRequestGetRouteResponsesPaginateTypeDef,
-    GetRoutesRequestGetRoutesPaginateTypeDef,
-    GetStagesRequestGetStagesPaginateTypeDef,
     GetIntegrationResponsesResponseTypeDef,
     GetModelsResponseTypeDef,
     GetVpcLinksResponseTypeDef,
     GetApisResponseTypeDef,
     GetAuthorizersResponseTypeDef,
     GetDomainNamesResponseTypeDef,
     GetIntegrationsResponseTypeDef,
@@ -504,43 +504,43 @@
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

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/setup.py` & `types-aiobotocore-apigatewayv2-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-apigatewayv2.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-apigatewayv2",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_apigatewayv2"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ApiGatewayV2 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ApiGatewayV2 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/"
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

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/__init__.py` & `types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/__init__.pyi` & `types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/__main__.py` & `types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ApiGatewayV2 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ApiGatewayV2 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2\nOther"
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

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/client.py` & `types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/client.pyi` & `types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/literals.py` & `types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -141,14 +141,15 @@
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
@@ -227,14 +228,15 @@
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
@@ -245,14 +247,15 @@
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
@@ -288,14 +291,15 @@
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
@@ -314,16 +318,19 @@
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
@@ -407,15 +414,17 @@
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

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/literals.pyi` & `types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -139,14 +139,15 @@
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
@@ -225,14 +226,15 @@
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
@@ -243,14 +245,15 @@
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
@@ -286,14 +289,15 @@
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
@@ -312,16 +316,19 @@
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
@@ -405,15 +412,17 @@
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

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/paginator.py` & `types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         get_integrations_paginator: GetIntegrationsPaginator = client.get_paginator("get_integrations")
         get_models_paginator: GetModelsPaginator = client.get_paginator("get_models")
         get_route_responses_paginator: GetRouteResponsesPaginator = client.get_paginator("get_route_responses")
         get_routes_paginator: GetRoutesPaginator = client.get_paginator("get_routes")
         get_stages_paginator: GetStagesPaginator = client.get_paginator("get_stages")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetApisResponseTypeDef,
     GetAuthorizersResponseTypeDef,
@@ -54,20 +53,14 @@
     GetModelsResponseTypeDef,
     GetRouteResponsesResponseTypeDef,
     GetRoutesResponseTypeDef,
     GetStagesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetApisPaginator",
     "GetAuthorizersPaginator",
     "GetDeploymentsPaginator",
     "GetDomainNamesPaginator",
     "GetIntegrationResponsesPaginator",
     "GetIntegrationsPaginator",
@@ -91,148 +84,148 @@
 class GetApisPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetApis)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getapispaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetApisResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetApis.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getapispaginator)
         """
 
 
 class GetAuthorizersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetAuthorizers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getauthorizerspaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetAuthorizersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetAuthorizers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getauthorizerspaginator)
         """
 
 
 class GetDeploymentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetDeployments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getdeploymentspaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDeploymentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetDeployments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getdeploymentspaginator)
         """
 
 
 class GetDomainNamesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetDomainNames)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getdomainnamespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDomainNamesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetDomainNames.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getdomainnamespaginator)
         """
 
 
 class GetIntegrationResponsesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetIntegrationResponses)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getintegrationresponsespaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, IntegrationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, IntegrationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetIntegrationResponsesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetIntegrationResponses.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getintegrationresponsespaginator)
         """
 
 
 class GetIntegrationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetIntegrations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getintegrationspaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetIntegrationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetIntegrations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getintegrationspaginator)
         """
 
 
 class GetModelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetModels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getmodelspaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetModelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetModels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getmodelspaginator)
         """
 
 
 class GetRouteResponsesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetRouteResponses)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getrouteresponsespaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, RouteId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, RouteId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRouteResponsesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetRouteResponses.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getrouteresponsespaginator)
         """
 
 
 class GetRoutesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetRoutes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getroutespaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRoutesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetRoutes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getroutespaginator)
         """
 
 
 class GetStagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetStages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getstagespaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetStagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetStages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getstagespaginator)
         """
```

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/paginator.pyi` & `types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/paginator.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         get_integrations_paginator: GetIntegrationsPaginator = client.get_paginator("get_integrations")
         get_models_paginator: GetModelsPaginator = client.get_paginator("get_models")
         get_route_responses_paginator: GetRouteResponsesPaginator = client.get_paginator("get_route_responses")
         get_routes_paginator: GetRoutesPaginator = client.get_paginator("get_routes")
         get_stages_paginator: GetStagesPaginator = client.get_paginator("get_stages")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetApisResponseTypeDef,
     GetAuthorizersResponseTypeDef,
@@ -54,19 +53,14 @@
     GetModelsResponseTypeDef,
     GetRouteResponsesResponseTypeDef,
     GetRoutesResponseTypeDef,
     GetStagesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetApisPaginator",
     "GetAuthorizersPaginator",
     "GetDeploymentsPaginator",
     "GetDomainNamesPaginator",
     "GetIntegrationResponsesPaginator",
     "GetIntegrationsPaginator",
@@ -87,139 +81,139 @@
 class GetApisPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetApis)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getapispaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetApisResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetApis.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getapispaginator)
         """
 
 class GetAuthorizersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetAuthorizers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getauthorizerspaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetAuthorizersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetAuthorizers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getauthorizerspaginator)
         """
 
 class GetDeploymentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetDeployments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getdeploymentspaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDeploymentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetDeployments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getdeploymentspaginator)
         """
 
 class GetDomainNamesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetDomainNames)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getdomainnamespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDomainNamesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetDomainNames.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getdomainnamespaginator)
         """
 
 class GetIntegrationResponsesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetIntegrationResponses)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getintegrationresponsespaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, IntegrationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, IntegrationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetIntegrationResponsesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetIntegrationResponses.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getintegrationresponsespaginator)
         """
 
 class GetIntegrationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetIntegrations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getintegrationspaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetIntegrationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetIntegrations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getintegrationspaginator)
         """
 
 class GetModelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetModels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getmodelspaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetModelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetModels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getmodelspaginator)
         """
 
 class GetRouteResponsesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetRouteResponses)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getrouteresponsespaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, RouteId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, RouteId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRouteResponsesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetRouteResponses.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getrouteresponsespaginator)
         """
 
 class GetRoutesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetRoutes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getroutespaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRoutesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetRoutes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getroutespaginator)
         """
 
 class GetStagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetStages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getstagespaginator)
     """
 
     def paginate(
-        self, *, ApiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetStagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2.Paginator.GetStages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/paginators/#getstagespaginator)
         """
```

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/type_defs.py` & `types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -39,33 +39,36 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AccessLogSettingsTypeDef",
     "ApiMappingTypeDef",
     "CorsTypeDef",
     "JWTConfigurationTypeDef",
     "CreateApiMappingRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateApiMappingResponseTypeDef",
     "CreateDeploymentRequestRequestTypeDef",
+    "CreateDeploymentResponseTypeDef",
     "DomainNameConfigurationTypeDef",
     "MutualTlsAuthenticationInputTypeDef",
     "MutualTlsAuthenticationTypeDef",
     "TlsConfigInputTypeDef",
     "CreateIntegrationResponseRequestRequestTypeDef",
+    "CreateIntegrationResponseResponseTypeDef",
     "TlsConfigTypeDef",
     "CreateModelRequestRequestTypeDef",
+    "CreateModelResponseTypeDef",
     "ParameterConstraintsTypeDef",
     "RouteSettingsTypeDef",
     "CreateVpcLinkRequestRequestTypeDef",
+    "CreateVpcLinkResponseTypeDef",
     "DeleteAccessLogSettingsRequestRequestTypeDef",
     "DeleteApiMappingRequestRequestTypeDef",
     "DeleteApiRequestRequestTypeDef",
     "DeleteAuthorizerRequestRequestTypeDef",
     "DeleteCorsConfigurationRequestRequestTypeDef",
     "DeleteDeploymentRequestRequestTypeDef",
     "DeleteDomainNameRequestRequestTypeDef",
@@ -75,89 +78,95 @@
     "DeleteRouteRequestParameterRequestRequestTypeDef",
     "DeleteRouteRequestRequestTypeDef",
     "DeleteRouteResponseRequestRequestTypeDef",
     "DeleteRouteSettingsRequestRequestTypeDef",
     "DeleteStageRequestRequestTypeDef",
     "DeleteVpcLinkRequestRequestTypeDef",
     "DeploymentTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExportApiRequestRequestTypeDef",
+    "ExportApiResponseTypeDef",
     "GetApiMappingRequestRequestTypeDef",
+    "GetApiMappingResponseTypeDef",
     "GetApiMappingsRequestRequestTypeDef",
     "GetApiRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetApisRequestGetApisPaginateTypeDef",
     "GetApisRequestRequestTypeDef",
     "GetAuthorizerRequestRequestTypeDef",
+    "GetAuthorizersRequestGetAuthorizersPaginateTypeDef",
     "GetAuthorizersRequestRequestTypeDef",
     "GetDeploymentRequestRequestTypeDef",
+    "GetDeploymentResponseTypeDef",
+    "GetDeploymentsRequestGetDeploymentsPaginateTypeDef",
     "GetDeploymentsRequestRequestTypeDef",
     "GetDomainNameRequestRequestTypeDef",
+    "GetDomainNamesRequestGetDomainNamesPaginateTypeDef",
     "GetDomainNamesRequestRequestTypeDef",
     "GetIntegrationRequestRequestTypeDef",
     "GetIntegrationResponseRequestRequestTypeDef",
+    "GetIntegrationResponseResponseTypeDef",
+    "GetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef",
     "GetIntegrationResponsesRequestRequestTypeDef",
     "IntegrationResponseTypeDef",
+    "GetIntegrationsRequestGetIntegrationsPaginateTypeDef",
     "GetIntegrationsRequestRequestTypeDef",
     "GetModelRequestRequestTypeDef",
+    "GetModelResponseTypeDef",
     "GetModelTemplateRequestRequestTypeDef",
+    "GetModelTemplateResponseTypeDef",
+    "GetModelsRequestGetModelsPaginateTypeDef",
     "GetModelsRequestRequestTypeDef",
     "ModelTypeDef",
     "GetRouteRequestRequestTypeDef",
     "GetRouteResponseRequestRequestTypeDef",
+    "GetRouteResponsesRequestGetRouteResponsesPaginateTypeDef",
     "GetRouteResponsesRequestRequestTypeDef",
+    "GetRoutesRequestGetRoutesPaginateTypeDef",
     "GetRoutesRequestRequestTypeDef",
     "GetStageRequestRequestTypeDef",
+    "GetStagesRequestGetStagesPaginateTypeDef",
     "GetStagesRequestRequestTypeDef",
     "GetTagsRequestRequestTypeDef",
+    "GetTagsResponseTypeDef",
     "GetVpcLinkRequestRequestTypeDef",
+    "GetVpcLinkResponseTypeDef",
     "GetVpcLinksRequestRequestTypeDef",
     "VpcLinkTypeDef",
     "ImportApiRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ReimportApiRequestRequestTypeDef",
     "ResetAuthorizersCacheRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApiMappingRequestRequestTypeDef",
+    "UpdateApiMappingResponseTypeDef",
     "UpdateDeploymentRequestRequestTypeDef",
+    "UpdateDeploymentResponseTypeDef",
     "UpdateIntegrationResponseRequestRequestTypeDef",
+    "UpdateIntegrationResponseResponseTypeDef",
     "UpdateModelRequestRequestTypeDef",
+    "UpdateModelResponseTypeDef",
     "UpdateVpcLinkRequestRequestTypeDef",
+    "UpdateVpcLinkResponseTypeDef",
+    "GetApiMappingsResponseTypeDef",
     "ApiTypeDef",
     "CreateApiRequestRequestTypeDef",
-    "UpdateApiRequestRequestTypeDef",
-    "AuthorizerTypeDef",
-    "CreateAuthorizerRequestRequestTypeDef",
-    "UpdateAuthorizerRequestRequestTypeDef",
-    "CreateApiMappingResponseTypeDef",
     "CreateApiResponseTypeDef",
-    "CreateAuthorizerResponseTypeDef",
-    "CreateDeploymentResponseTypeDef",
-    "CreateIntegrationResponseResponseTypeDef",
-    "CreateModelResponseTypeDef",
-    "CreateVpcLinkResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExportApiResponseTypeDef",
-    "GetApiMappingResponseTypeDef",
-    "GetApiMappingsResponseTypeDef",
     "GetApiResponseTypeDef",
-    "GetAuthorizerResponseTypeDef",
-    "GetDeploymentResponseTypeDef",
-    "GetIntegrationResponseResponseTypeDef",
-    "GetModelResponseTypeDef",
-    "GetModelTemplateResponseTypeDef",
-    "GetTagsResponseTypeDef",
-    "GetVpcLinkResponseTypeDef",
     "ImportApiResponseTypeDef",
     "ReimportApiResponseTypeDef",
-    "UpdateApiMappingResponseTypeDef",
+    "UpdateApiRequestRequestTypeDef",
     "UpdateApiResponseTypeDef",
+    "AuthorizerTypeDef",
+    "CreateAuthorizerRequestRequestTypeDef",
+    "CreateAuthorizerResponseTypeDef",
+    "GetAuthorizerResponseTypeDef",
+    "UpdateAuthorizerRequestRequestTypeDef",
     "UpdateAuthorizerResponseTypeDef",
-    "UpdateDeploymentResponseTypeDef",
-    "UpdateIntegrationResponseResponseTypeDef",
-    "UpdateModelResponseTypeDef",
-    "UpdateVpcLinkResponseTypeDef",
     "CreateDomainNameRequestRequestTypeDef",
     "UpdateDomainNameRequestRequestTypeDef",
     "CreateDomainNameResponseTypeDef",
     "DomainNameTypeDef",
     "GetDomainNameResponseTypeDef",
     "UpdateDomainNameResponseTypeDef",
     "CreateIntegrationRequestRequestTypeDef",
@@ -181,24 +190,14 @@
     "CreateStageRequestRequestTypeDef",
     "CreateStageResponseTypeDef",
     "GetStageResponseTypeDef",
     "StageTypeDef",
     "UpdateStageRequestRequestTypeDef",
     "UpdateStageResponseTypeDef",
     "GetDeploymentsResponseTypeDef",
-    "GetApisRequestGetApisPaginateTypeDef",
-    "GetAuthorizersRequestGetAuthorizersPaginateTypeDef",
-    "GetDeploymentsRequestGetDeploymentsPaginateTypeDef",
-    "GetDomainNamesRequestGetDomainNamesPaginateTypeDef",
-    "GetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef",
-    "GetIntegrationsRequestGetIntegrationsPaginateTypeDef",
-    "GetModelsRequestGetModelsPaginateTypeDef",
-    "GetRouteResponsesRequestGetRouteResponsesPaginateTypeDef",
-    "GetRoutesRequestGetRoutesPaginateTypeDef",
-    "GetStagesRequestGetStagesPaginateTypeDef",
     "GetIntegrationResponsesResponseTypeDef",
     "GetModelsResponseTypeDef",
     "GetVpcLinksResponseTypeDef",
     "GetApisResponseTypeDef",
     "GetAuthorizersResponseTypeDef",
     "GetDomainNamesResponseTypeDef",
     "GetIntegrationsResponseTypeDef",
@@ -228,19 +227,17 @@
     {
         "ApiMappingId": str,
         "ApiMappingKey": str,
     },
     total=False,
 )
 
-
 class ApiMappingTypeDef(_RequiredApiMappingTypeDef, _OptionalApiMappingTypeDef):
     pass
 
-
 CorsTypeDef = TypedDict(
     "CorsTypeDef",
     {
         "AllowCredentials": bool,
         "AllowHeaders": Sequence[str],
         "AllowMethods": Sequence[str],
         "AllowOrigins": Sequence[str],
@@ -271,29 +268,27 @@
     "_OptionalCreateApiMappingRequestRequestTypeDef",
     {
         "ApiMappingKey": str,
     },
     total=False,
 )
 
-
 class CreateApiMappingRequestRequestTypeDef(
     _RequiredCreateApiMappingRequestRequestTypeDef, _OptionalCreateApiMappingRequestRequestTypeDef
 ):
     pass
 
-
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateApiMappingResponseTypeDef = TypedDict(
+    "CreateApiMappingResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ApiId": str,
+        "ApiMappingId": str,
+        "ApiMappingKey": str,
+        "Stage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDeploymentRequestRequestTypeDef",
     {
         "ApiId": str,
@@ -304,20 +299,31 @@
     {
         "Description": str,
         "StageName": str,
     },
     total=False,
 )
 
-
 class CreateDeploymentRequestRequestTypeDef(
     _RequiredCreateDeploymentRequestRequestTypeDef, _OptionalCreateDeploymentRequestRequestTypeDef
 ):
     pass
 
+CreateDeploymentResponseTypeDef = TypedDict(
+    "CreateDeploymentResponseTypeDef",
+    {
+        "AutoDeployed": bool,
+        "CreatedDate": datetime,
+        "DeploymentId": str,
+        "DeploymentStatus": DeploymentStatusType,
+        "DeploymentStatusMessage": str,
+        "Description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DomainNameConfigurationTypeDef = TypedDict(
     "DomainNameConfigurationTypeDef",
     {
         "ApiGatewayDomainName": str,
         "CertificateArn": str,
         "CertificateName": str,
@@ -374,21 +380,32 @@
         "ResponseParameters": Mapping[str, str],
         "ResponseTemplates": Mapping[str, str],
         "TemplateSelectionExpression": str,
     },
     total=False,
 )
 
-
 class CreateIntegrationResponseRequestRequestTypeDef(
     _RequiredCreateIntegrationResponseRequestRequestTypeDef,
     _OptionalCreateIntegrationResponseRequestRequestTypeDef,
 ):
     pass
 
+CreateIntegrationResponseResponseTypeDef = TypedDict(
+    "CreateIntegrationResponseResponseTypeDef",
+    {
+        "ContentHandlingStrategy": ContentHandlingStrategyType,
+        "IntegrationResponseId": str,
+        "IntegrationResponseKey": str,
+        "ResponseParameters": Dict[str, str],
+        "ResponseTemplates": Dict[str, str],
+        "TemplateSelectionExpression": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 TlsConfigTypeDef = TypedDict(
     "TlsConfigTypeDef",
     {
         "ServerNameToVerify": str,
     },
     total=False,
@@ -407,20 +424,30 @@
     {
         "ContentType": str,
         "Description": str,
     },
     total=False,
 )
 
-
 class CreateModelRequestRequestTypeDef(
     _RequiredCreateModelRequestRequestTypeDef, _OptionalCreateModelRequestRequestTypeDef
 ):
     pass
 
+CreateModelResponseTypeDef = TypedDict(
+    "CreateModelResponseTypeDef",
+    {
+        "ContentType": str,
+        "Description": str,
+        "ModelId": str,
+        "Name": str,
+        "Schema": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 ParameterConstraintsTypeDef = TypedDict(
     "ParameterConstraintsTypeDef",
     {
         "Required": bool,
     },
     total=False,
@@ -450,20 +477,34 @@
     {
         "SecurityGroupIds": Sequence[str],
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateVpcLinkRequestRequestTypeDef(
     _RequiredCreateVpcLinkRequestRequestTypeDef, _OptionalCreateVpcLinkRequestRequestTypeDef
 ):
     pass
 
+CreateVpcLinkResponseTypeDef = TypedDict(
+    "CreateVpcLinkResponseTypeDef",
+    {
+        "CreatedDate": datetime,
+        "Name": str,
+        "SecurityGroupIds": List[str],
+        "SubnetIds": List[str],
+        "Tags": Dict[str, str],
+        "VpcLinkId": str,
+        "VpcLinkStatus": VpcLinkStatusType,
+        "VpcLinkStatusMessage": str,
+        "VpcLinkVersion": Literal["V2"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DeleteAccessLogSettingsRequestRequestTypeDef = TypedDict(
     "DeleteAccessLogSettingsRequestRequestTypeDef",
     {
         "ApiId": str,
         "StageName": str,
     },
@@ -598,14 +639,21 @@
         "DeploymentStatus": DeploymentStatusType,
         "DeploymentStatusMessage": str,
         "Description": str,
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
 _RequiredExportApiRequestRequestTypeDef = TypedDict(
     "_RequiredExportApiRequestRequestTypeDef",
     {
         "ApiId": str,
         "OutputType": JSONYAMLType,
         "Specification": Literal["OAS30"],
     },
@@ -616,29 +664,46 @@
         "ExportVersion": str,
         "IncludeExtensions": bool,
         "StageName": str,
     },
     total=False,
 )
 
-
 class ExportApiRequestRequestTypeDef(
     _RequiredExportApiRequestRequestTypeDef, _OptionalExportApiRequestRequestTypeDef
 ):
     pass
 
+ExportApiResponseTypeDef = TypedDict(
+    "ExportApiResponseTypeDef",
+    {
+        "body": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 GetApiMappingRequestRequestTypeDef = TypedDict(
     "GetApiMappingRequestRequestTypeDef",
     {
         "ApiMappingId": str,
         "DomainName": str,
     },
 )
 
+GetApiMappingResponseTypeDef = TypedDict(
+    "GetApiMappingResponseTypeDef",
+    {
+        "ApiId": str,
+        "ApiMappingId": str,
+        "ApiMappingKey": str,
+        "Stage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetApiMappingsRequestRequestTypeDef = TypedDict(
     "_RequiredGetApiMappingsRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalGetApiMappingsRequestRequestTypeDef = TypedDict(
@@ -646,34 +711,30 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetApiMappingsRequestRequestTypeDef(
     _RequiredGetApiMappingsRequestRequestTypeDef, _OptionalGetApiMappingsRequestRequestTypeDef
 ):
     pass
 
-
 GetApiRequestRequestTypeDef = TypedDict(
     "GetApiRequestRequestTypeDef",
     {
         "ApiId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetApisRequestGetApisPaginateTypeDef = TypedDict(
+    "GetApisRequestGetApisPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetApisRequestRequestTypeDef = TypedDict(
     "GetApisRequestRequestTypeDef",
     {
@@ -687,14 +748,34 @@
     "GetAuthorizerRequestRequestTypeDef",
     {
         "ApiId": str,
         "AuthorizerId": str,
     },
 )
 
+_RequiredGetAuthorizersRequestGetAuthorizersPaginateTypeDef = TypedDict(
+    "_RequiredGetAuthorizersRequestGetAuthorizersPaginateTypeDef",
+    {
+        "ApiId": str,
+    },
+)
+_OptionalGetAuthorizersRequestGetAuthorizersPaginateTypeDef = TypedDict(
+    "_OptionalGetAuthorizersRequestGetAuthorizersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetAuthorizersRequestGetAuthorizersPaginateTypeDef(
+    _RequiredGetAuthorizersRequestGetAuthorizersPaginateTypeDef,
+    _OptionalGetAuthorizersRequestGetAuthorizersPaginateTypeDef,
+):
+    pass
+
 _RequiredGetAuthorizersRequestRequestTypeDef = TypedDict(
     "_RequiredGetAuthorizersRequestRequestTypeDef",
     {
         "ApiId": str,
     },
 )
 _OptionalGetAuthorizersRequestRequestTypeDef = TypedDict(
@@ -702,29 +783,60 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetAuthorizersRequestRequestTypeDef(
     _RequiredGetAuthorizersRequestRequestTypeDef, _OptionalGetAuthorizersRequestRequestTypeDef
 ):
     pass
 
-
 GetDeploymentRequestRequestTypeDef = TypedDict(
     "GetDeploymentRequestRequestTypeDef",
     {
         "ApiId": str,
         "DeploymentId": str,
     },
 )
 
+GetDeploymentResponseTypeDef = TypedDict(
+    "GetDeploymentResponseTypeDef",
+    {
+        "AutoDeployed": bool,
+        "CreatedDate": datetime,
+        "DeploymentId": str,
+        "DeploymentStatus": DeploymentStatusType,
+        "DeploymentStatusMessage": str,
+        "Description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetDeploymentsRequestGetDeploymentsPaginateTypeDef = TypedDict(
+    "_RequiredGetDeploymentsRequestGetDeploymentsPaginateTypeDef",
+    {
+        "ApiId": str,
+    },
+)
+_OptionalGetDeploymentsRequestGetDeploymentsPaginateTypeDef = TypedDict(
+    "_OptionalGetDeploymentsRequestGetDeploymentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetDeploymentsRequestGetDeploymentsPaginateTypeDef(
+    _RequiredGetDeploymentsRequestGetDeploymentsPaginateTypeDef,
+    _OptionalGetDeploymentsRequestGetDeploymentsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetDeploymentsRequestRequestTypeDef = TypedDict(
     "_RequiredGetDeploymentsRequestRequestTypeDef",
     {
         "ApiId": str,
     },
 )
 _OptionalGetDeploymentsRequestRequestTypeDef = TypedDict(
@@ -732,28 +844,34 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetDeploymentsRequestRequestTypeDef(
     _RequiredGetDeploymentsRequestRequestTypeDef, _OptionalGetDeploymentsRequestRequestTypeDef
 ):
     pass
 
-
 GetDomainNameRequestRequestTypeDef = TypedDict(
     "GetDomainNameRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+GetDomainNamesRequestGetDomainNamesPaginateTypeDef = TypedDict(
+    "GetDomainNamesRequestGetDomainNamesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetDomainNamesRequestRequestTypeDef = TypedDict(
     "GetDomainNamesRequestRequestTypeDef",
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
@@ -772,14 +890,48 @@
     {
         "ApiId": str,
         "IntegrationId": str,
         "IntegrationResponseId": str,
     },
 )
 
+GetIntegrationResponseResponseTypeDef = TypedDict(
+    "GetIntegrationResponseResponseTypeDef",
+    {
+        "ContentHandlingStrategy": ContentHandlingStrategyType,
+        "IntegrationResponseId": str,
+        "IntegrationResponseKey": str,
+        "ResponseParameters": Dict[str, str],
+        "ResponseTemplates": Dict[str, str],
+        "TemplateSelectionExpression": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef = TypedDict(
+    "_RequiredGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef",
+    {
+        "ApiId": str,
+        "IntegrationId": str,
+    },
+)
+_OptionalGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef = TypedDict(
+    "_OptionalGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef(
+    _RequiredGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef,
+    _OptionalGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef,
+):
+    pass
+
 _RequiredGetIntegrationResponsesRequestRequestTypeDef = TypedDict(
     "_RequiredGetIntegrationResponsesRequestRequestTypeDef",
     {
         "ApiId": str,
         "IntegrationId": str,
     },
 )
@@ -788,22 +940,20 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetIntegrationResponsesRequestRequestTypeDef(
     _RequiredGetIntegrationResponsesRequestRequestTypeDef,
     _OptionalGetIntegrationResponsesRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredIntegrationResponseTypeDef = TypedDict(
     "_RequiredIntegrationResponseTypeDef",
     {
         "IntegrationResponseKey": str,
     },
 )
 _OptionalIntegrationResponseTypeDef = TypedDict(
@@ -814,20 +964,38 @@
         "ResponseParameters": Dict[str, str],
         "ResponseTemplates": Dict[str, str],
         "TemplateSelectionExpression": str,
     },
     total=False,
 )
 
-
 class IntegrationResponseTypeDef(
     _RequiredIntegrationResponseTypeDef, _OptionalIntegrationResponseTypeDef
 ):
     pass
 
+_RequiredGetIntegrationsRequestGetIntegrationsPaginateTypeDef = TypedDict(
+    "_RequiredGetIntegrationsRequestGetIntegrationsPaginateTypeDef",
+    {
+        "ApiId": str,
+    },
+)
+_OptionalGetIntegrationsRequestGetIntegrationsPaginateTypeDef = TypedDict(
+    "_OptionalGetIntegrationsRequestGetIntegrationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetIntegrationsRequestGetIntegrationsPaginateTypeDef(
+    _RequiredGetIntegrationsRequestGetIntegrationsPaginateTypeDef,
+    _OptionalGetIntegrationsRequestGetIntegrationsPaginateTypeDef,
+):
+    pass
 
 _RequiredGetIntegrationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetIntegrationsRequestRequestTypeDef",
     {
         "ApiId": str,
     },
 )
@@ -836,37 +1004,75 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetIntegrationsRequestRequestTypeDef(
     _RequiredGetIntegrationsRequestRequestTypeDef, _OptionalGetIntegrationsRequestRequestTypeDef
 ):
     pass
 
-
 GetModelRequestRequestTypeDef = TypedDict(
     "GetModelRequestRequestTypeDef",
     {
         "ApiId": str,
         "ModelId": str,
     },
 )
 
+GetModelResponseTypeDef = TypedDict(
+    "GetModelResponseTypeDef",
+    {
+        "ContentType": str,
+        "Description": str,
+        "ModelId": str,
+        "Name": str,
+        "Schema": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetModelTemplateRequestRequestTypeDef = TypedDict(
     "GetModelTemplateRequestRequestTypeDef",
     {
         "ApiId": str,
         "ModelId": str,
     },
 )
 
+GetModelTemplateResponseTypeDef = TypedDict(
+    "GetModelTemplateResponseTypeDef",
+    {
+        "Value": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetModelsRequestGetModelsPaginateTypeDef = TypedDict(
+    "_RequiredGetModelsRequestGetModelsPaginateTypeDef",
+    {
+        "ApiId": str,
+    },
+)
+_OptionalGetModelsRequestGetModelsPaginateTypeDef = TypedDict(
+    "_OptionalGetModelsRequestGetModelsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetModelsRequestGetModelsPaginateTypeDef(
+    _RequiredGetModelsRequestGetModelsPaginateTypeDef,
+    _OptionalGetModelsRequestGetModelsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetModelsRequestRequestTypeDef = TypedDict(
     "_RequiredGetModelsRequestRequestTypeDef",
     {
         "ApiId": str,
     },
 )
 _OptionalGetModelsRequestRequestTypeDef = TypedDict(
@@ -874,21 +1080,19 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetModelsRequestRequestTypeDef(
     _RequiredGetModelsRequestRequestTypeDef, _OptionalGetModelsRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredModelTypeDef = TypedDict(
     "_RequiredModelTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalModelTypeDef = TypedDict(
@@ -898,19 +1102,17 @@
         "Description": str,
         "ModelId": str,
         "Schema": str,
     },
     total=False,
 )
 
-
 class ModelTypeDef(_RequiredModelTypeDef, _OptionalModelTypeDef):
     pass
 
-
 GetRouteRequestRequestTypeDef = TypedDict(
     "GetRouteRequestRequestTypeDef",
     {
         "ApiId": str,
         "RouteId": str,
     },
 )
@@ -920,14 +1122,35 @@
     {
         "ApiId": str,
         "RouteId": str,
         "RouteResponseId": str,
     },
 )
 
+_RequiredGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef = TypedDict(
+    "_RequiredGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef",
+    {
+        "ApiId": str,
+        "RouteId": str,
+    },
+)
+_OptionalGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef = TypedDict(
+    "_OptionalGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetRouteResponsesRequestGetRouteResponsesPaginateTypeDef(
+    _RequiredGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef,
+    _OptionalGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef,
+):
+    pass
+
 _RequiredGetRouteResponsesRequestRequestTypeDef = TypedDict(
     "_RequiredGetRouteResponsesRequestRequestTypeDef",
     {
         "ApiId": str,
         "RouteId": str,
     },
 )
@@ -936,20 +1159,38 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetRouteResponsesRequestRequestTypeDef(
     _RequiredGetRouteResponsesRequestRequestTypeDef, _OptionalGetRouteResponsesRequestRequestTypeDef
 ):
     pass
 
+_RequiredGetRoutesRequestGetRoutesPaginateTypeDef = TypedDict(
+    "_RequiredGetRoutesRequestGetRoutesPaginateTypeDef",
+    {
+        "ApiId": str,
+    },
+)
+_OptionalGetRoutesRequestGetRoutesPaginateTypeDef = TypedDict(
+    "_OptionalGetRoutesRequestGetRoutesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetRoutesRequestGetRoutesPaginateTypeDef(
+    _RequiredGetRoutesRequestGetRoutesPaginateTypeDef,
+    _OptionalGetRoutesRequestGetRoutesPaginateTypeDef,
+):
+    pass
 
 _RequiredGetRoutesRequestRequestTypeDef = TypedDict(
     "_RequiredGetRoutesRequestRequestTypeDef",
     {
         "ApiId": str,
     },
 )
@@ -958,29 +1199,47 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetRoutesRequestRequestTypeDef(
     _RequiredGetRoutesRequestRequestTypeDef, _OptionalGetRoutesRequestRequestTypeDef
 ):
     pass
 
-
 GetStageRequestRequestTypeDef = TypedDict(
     "GetStageRequestRequestTypeDef",
     {
         "ApiId": str,
         "StageName": str,
     },
 )
 
+_RequiredGetStagesRequestGetStagesPaginateTypeDef = TypedDict(
+    "_RequiredGetStagesRequestGetStagesPaginateTypeDef",
+    {
+        "ApiId": str,
+    },
+)
+_OptionalGetStagesRequestGetStagesPaginateTypeDef = TypedDict(
+    "_OptionalGetStagesRequestGetStagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetStagesRequestGetStagesPaginateTypeDef(
+    _RequiredGetStagesRequestGetStagesPaginateTypeDef,
+    _OptionalGetStagesRequestGetStagesPaginateTypeDef,
+):
+    pass
+
 _RequiredGetStagesRequestRequestTypeDef = TypedDict(
     "_RequiredGetStagesRequestRequestTypeDef",
     {
         "ApiId": str,
     },
 )
 _OptionalGetStagesRequestRequestTypeDef = TypedDict(
@@ -988,35 +1247,57 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetStagesRequestRequestTypeDef(
     _RequiredGetStagesRequestRequestTypeDef, _OptionalGetStagesRequestRequestTypeDef
 ):
     pass
 
-
 GetTagsRequestRequestTypeDef = TypedDict(
     "GetTagsRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+GetTagsResponseTypeDef = TypedDict(
+    "GetTagsResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetVpcLinkRequestRequestTypeDef = TypedDict(
     "GetVpcLinkRequestRequestTypeDef",
     {
         "VpcLinkId": str,
     },
 )
 
+GetVpcLinkResponseTypeDef = TypedDict(
+    "GetVpcLinkResponseTypeDef",
+    {
+        "CreatedDate": datetime,
+        "Name": str,
+        "SecurityGroupIds": List[str],
+        "SubnetIds": List[str],
+        "Tags": Dict[str, str],
+        "VpcLinkId": str,
+        "VpcLinkStatus": VpcLinkStatusType,
+        "VpcLinkStatusMessage": str,
+        "VpcLinkVersion": Literal["V2"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetVpcLinksRequestRequestTypeDef = TypedDict(
     "GetVpcLinksRequestRequestTypeDef",
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
@@ -1039,19 +1320,17 @@
         "VpcLinkStatus": VpcLinkStatusType,
         "VpcLinkStatusMessage": str,
         "VpcLinkVersion": Literal["V2"],
     },
     total=False,
 )
 
-
 class VpcLinkTypeDef(_RequiredVpcLinkTypeDef, _OptionalVpcLinkTypeDef):
     pass
 
-
 _RequiredImportApiRequestRequestTypeDef = TypedDict(
     "_RequiredImportApiRequestRequestTypeDef",
     {
         "Body": str,
     },
 )
 _OptionalImportApiRequestRequestTypeDef = TypedDict(
@@ -1059,20 +1338,28 @@
     {
         "Basepath": str,
         "FailOnWarnings": bool,
     },
     total=False,
 )
 
-
 class ImportApiRequestRequestTypeDef(
     _RequiredImportApiRequestRequestTypeDef, _OptionalImportApiRequestRequestTypeDef
 ):
     pass
 
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
+    {
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
+    },
+    total=False,
+)
 
 _RequiredReimportApiRequestRequestTypeDef = TypedDict(
     "_RequiredReimportApiRequestRequestTypeDef",
     {
         "ApiId": str,
         "Body": str,
     },
@@ -1082,50 +1369,57 @@
     {
         "Basepath": str,
         "FailOnWarnings": bool,
     },
     total=False,
 )
 
-
 class ReimportApiRequestRequestTypeDef(
     _RequiredReimportApiRequestRequestTypeDef, _OptionalReimportApiRequestRequestTypeDef
 ):
     pass
 
-
 ResetAuthorizersCacheRequestRequestTypeDef = TypedDict(
     "ResetAuthorizersCacheRequestRequestTypeDef",
     {
         "ApiId": str,
         "StageName": str,
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
 _RequiredTagResourceRequestRequestTypeDef = TypedDict(
     "_RequiredTagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalTagResourceRequestRequestTypeDef = TypedDict(
     "_OptionalTagResourceRequestRequestTypeDef",
     {
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class TagResourceRequestRequestTypeDef(
     _RequiredTagResourceRequestRequestTypeDef, _OptionalTagResourceRequestRequestTypeDef
 ):
     pass
 
-
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -1143,20 +1437,29 @@
     {
         "ApiMappingKey": str,
         "Stage": str,
     },
     total=False,
 )
 
-
 class UpdateApiMappingRequestRequestTypeDef(
     _RequiredUpdateApiMappingRequestRequestTypeDef, _OptionalUpdateApiMappingRequestRequestTypeDef
 ):
     pass
 
+UpdateApiMappingResponseTypeDef = TypedDict(
+    "UpdateApiMappingResponseTypeDef",
+    {
+        "ApiId": str,
+        "ApiMappingId": str,
+        "ApiMappingKey": str,
+        "Stage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredUpdateDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDeploymentRequestRequestTypeDef",
     {
         "ApiId": str,
         "DeploymentId": str,
     },
@@ -1165,20 +1468,31 @@
     "_OptionalUpdateDeploymentRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
-
 class UpdateDeploymentRequestRequestTypeDef(
     _RequiredUpdateDeploymentRequestRequestTypeDef, _OptionalUpdateDeploymentRequestRequestTypeDef
 ):
     pass
 
+UpdateDeploymentResponseTypeDef = TypedDict(
+    "UpdateDeploymentResponseTypeDef",
+    {
+        "AutoDeployed": bool,
+        "CreatedDate": datetime,
+        "DeploymentId": str,
+        "DeploymentStatus": DeploymentStatusType,
+        "DeploymentStatusMessage": str,
+        "Description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredUpdateIntegrationResponseRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateIntegrationResponseRequestRequestTypeDef",
     {
         "ApiId": str,
         "IntegrationId": str,
         "IntegrationResponseId": str,
@@ -1192,21 +1506,32 @@
         "ResponseParameters": Mapping[str, str],
         "ResponseTemplates": Mapping[str, str],
         "TemplateSelectionExpression": str,
     },
     total=False,
 )
 
-
 class UpdateIntegrationResponseRequestRequestTypeDef(
     _RequiredUpdateIntegrationResponseRequestRequestTypeDef,
     _OptionalUpdateIntegrationResponseRequestRequestTypeDef,
 ):
     pass
 
+UpdateIntegrationResponseResponseTypeDef = TypedDict(
+    "UpdateIntegrationResponseResponseTypeDef",
+    {
+        "ContentHandlingStrategy": ContentHandlingStrategyType,
+        "IntegrationResponseId": str,
+        "IntegrationResponseKey": str,
+        "ResponseParameters": Dict[str, str],
+        "ResponseTemplates": Dict[str, str],
+        "TemplateSelectionExpression": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredUpdateModelRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateModelRequestRequestTypeDef",
     {
         "ApiId": str,
         "ModelId": str,
     },
@@ -1218,20 +1543,30 @@
         "Description": str,
         "Name": str,
         "Schema": str,
     },
     total=False,
 )
 
-
 class UpdateModelRequestRequestTypeDef(
     _RequiredUpdateModelRequestRequestTypeDef, _OptionalUpdateModelRequestRequestTypeDef
 ):
     pass
 
+UpdateModelResponseTypeDef = TypedDict(
+    "UpdateModelResponseTypeDef",
+    {
+        "ContentType": str,
+        "Description": str,
+        "ModelId": str,
+        "Name": str,
+        "Schema": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredUpdateVpcLinkRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateVpcLinkRequestRequestTypeDef",
     {
         "VpcLinkId": str,
     },
 )
@@ -1239,20 +1574,43 @@
     "_OptionalUpdateVpcLinkRequestRequestTypeDef",
     {
         "Name": str,
     },
     total=False,
 )
 
-
 class UpdateVpcLinkRequestRequestTypeDef(
     _RequiredUpdateVpcLinkRequestRequestTypeDef, _OptionalUpdateVpcLinkRequestRequestTypeDef
 ):
     pass
 
+UpdateVpcLinkResponseTypeDef = TypedDict(
+    "UpdateVpcLinkResponseTypeDef",
+    {
+        "CreatedDate": datetime,
+        "Name": str,
+        "SecurityGroupIds": List[str],
+        "SubnetIds": List[str],
+        "Tags": Dict[str, str],
+        "VpcLinkId": str,
+        "VpcLinkStatus": VpcLinkStatusType,
+        "VpcLinkStatusMessage": str,
+        "VpcLinkVersion": Literal["V2"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetApiMappingsResponseTypeDef = TypedDict(
+    "GetApiMappingsResponseTypeDef",
+    {
+        "Items": List[ApiMappingTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredApiTypeDef = TypedDict(
     "_RequiredApiTypeDef",
     {
         "Name": str,
         "ProtocolType": ProtocolTypeType,
         "RouteSelectionExpression": str,
@@ -1274,19 +1632,17 @@
         "Tags": Dict[str, str],
         "Version": str,
         "Warnings": List[str],
     },
     total=False,
 )
 
-
 class ApiTypeDef(_RequiredApiTypeDef, _OptionalApiTypeDef):
     pass
 
-
 _RequiredCreateApiRequestRequestTypeDef = TypedDict(
     "_RequiredCreateApiRequestRequestTypeDef",
     {
         "Name": str,
         "ProtocolType": ProtocolTypeType,
     },
 )
@@ -1304,152 +1660,19 @@
         "Tags": Mapping[str, str],
         "Target": str,
         "Version": str,
     },
     total=False,
 )
 
-
 class CreateApiRequestRequestTypeDef(
     _RequiredCreateApiRequestRequestTypeDef, _OptionalCreateApiRequestRequestTypeDef
 ):
     pass
 
-
-_RequiredUpdateApiRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateApiRequestRequestTypeDef",
-    {
-        "ApiId": str,
-    },
-)
-_OptionalUpdateApiRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateApiRequestRequestTypeDef",
-    {
-        "ApiKeySelectionExpression": str,
-        "CorsConfiguration": CorsTypeDef,
-        "CredentialsArn": str,
-        "Description": str,
-        "DisableSchemaValidation": bool,
-        "DisableExecuteApiEndpoint": bool,
-        "Name": str,
-        "RouteKey": str,
-        "RouteSelectionExpression": str,
-        "Target": str,
-        "Version": str,
-    },
-    total=False,
-)
-
-
-class UpdateApiRequestRequestTypeDef(
-    _RequiredUpdateApiRequestRequestTypeDef, _OptionalUpdateApiRequestRequestTypeDef
-):
-    pass
-
-
-_RequiredAuthorizerTypeDef = TypedDict(
-    "_RequiredAuthorizerTypeDef",
-    {
-        "Name": str,
-    },
-)
-_OptionalAuthorizerTypeDef = TypedDict(
-    "_OptionalAuthorizerTypeDef",
-    {
-        "AuthorizerCredentialsArn": str,
-        "AuthorizerId": str,
-        "AuthorizerPayloadFormatVersion": str,
-        "AuthorizerResultTtlInSeconds": int,
-        "AuthorizerType": AuthorizerTypeType,
-        "AuthorizerUri": str,
-        "EnableSimpleResponses": bool,
-        "IdentitySource": List[str],
-        "IdentityValidationExpression": str,
-        "JwtConfiguration": JWTConfigurationTypeDef,
-    },
-    total=False,
-)
-
-
-class AuthorizerTypeDef(_RequiredAuthorizerTypeDef, _OptionalAuthorizerTypeDef):
-    pass
-
-
-_RequiredCreateAuthorizerRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateAuthorizerRequestRequestTypeDef",
-    {
-        "ApiId": str,
-        "AuthorizerType": AuthorizerTypeType,
-        "IdentitySource": Sequence[str],
-        "Name": str,
-    },
-)
-_OptionalCreateAuthorizerRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateAuthorizerRequestRequestTypeDef",
-    {
-        "AuthorizerCredentialsArn": str,
-        "AuthorizerPayloadFormatVersion": str,
-        "AuthorizerResultTtlInSeconds": int,
-        "AuthorizerUri": str,
-        "EnableSimpleResponses": bool,
-        "IdentityValidationExpression": str,
-        "JwtConfiguration": JWTConfigurationTypeDef,
-    },
-    total=False,
-)
-
-
-class CreateAuthorizerRequestRequestTypeDef(
-    _RequiredCreateAuthorizerRequestRequestTypeDef, _OptionalCreateAuthorizerRequestRequestTypeDef
-):
-    pass
-
-
-_RequiredUpdateAuthorizerRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateAuthorizerRequestRequestTypeDef",
-    {
-        "ApiId": str,
-        "AuthorizerId": str,
-    },
-)
-_OptionalUpdateAuthorizerRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateAuthorizerRequestRequestTypeDef",
-    {
-        "AuthorizerCredentialsArn": str,
-        "AuthorizerPayloadFormatVersion": str,
-        "AuthorizerResultTtlInSeconds": int,
-        "AuthorizerType": AuthorizerTypeType,
-        "AuthorizerUri": str,
-        "EnableSimpleResponses": bool,
-        "IdentitySource": Sequence[str],
-        "IdentityValidationExpression": str,
-        "JwtConfiguration": JWTConfigurationTypeDef,
-        "Name": str,
-    },
-    total=False,
-)
-
-
-class UpdateAuthorizerRequestRequestTypeDef(
-    _RequiredUpdateAuthorizerRequestRequestTypeDef, _OptionalUpdateAuthorizerRequestRequestTypeDef
-):
-    pass
-
-
-CreateApiMappingResponseTypeDef = TypedDict(
-    "CreateApiMappingResponseTypeDef",
-    {
-        "ApiId": str,
-        "ApiMappingId": str,
-        "ApiMappingKey": str,
-        "Stage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateApiResponseTypeDef = TypedDict(
     "CreateApiResponseTypeDef",
     {
         "ApiEndpoint": str,
         "ApiGatewayManaged": bool,
         "ApiId": str,
         "ApiKeySelectionExpression": str,
@@ -1461,122 +1684,15 @@
         "ImportInfo": List[str],
         "Name": str,
         "ProtocolType": ProtocolTypeType,
         "RouteSelectionExpression": str,
         "Tags": Dict[str, str],
         "Version": str,
         "Warnings": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAuthorizerResponseTypeDef = TypedDict(
-    "CreateAuthorizerResponseTypeDef",
-    {
-        "AuthorizerCredentialsArn": str,
-        "AuthorizerId": str,
-        "AuthorizerPayloadFormatVersion": str,
-        "AuthorizerResultTtlInSeconds": int,
-        "AuthorizerType": AuthorizerTypeType,
-        "AuthorizerUri": str,
-        "EnableSimpleResponses": bool,
-        "IdentitySource": List[str],
-        "IdentityValidationExpression": str,
-        "JwtConfiguration": JWTConfigurationTypeDef,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeploymentResponseTypeDef = TypedDict(
-    "CreateDeploymentResponseTypeDef",
-    {
-        "AutoDeployed": bool,
-        "CreatedDate": datetime,
-        "DeploymentId": str,
-        "DeploymentStatus": DeploymentStatusType,
-        "DeploymentStatusMessage": str,
-        "Description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateIntegrationResponseResponseTypeDef = TypedDict(
-    "CreateIntegrationResponseResponseTypeDef",
-    {
-        "ContentHandlingStrategy": ContentHandlingStrategyType,
-        "IntegrationResponseId": str,
-        "IntegrationResponseKey": str,
-        "ResponseParameters": Dict[str, str],
-        "ResponseTemplates": Dict[str, str],
-        "TemplateSelectionExpression": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateModelResponseTypeDef = TypedDict(
-    "CreateModelResponseTypeDef",
-    {
-        "ContentType": str,
-        "Description": str,
-        "ModelId": str,
-        "Name": str,
-        "Schema": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateVpcLinkResponseTypeDef = TypedDict(
-    "CreateVpcLinkResponseTypeDef",
-    {
-        "CreatedDate": datetime,
-        "Name": str,
-        "SecurityGroupIds": List[str],
-        "SubnetIds": List[str],
-        "Tags": Dict[str, str],
-        "VpcLinkId": str,
-        "VpcLinkStatus": VpcLinkStatusType,
-        "VpcLinkStatusMessage": str,
-        "VpcLinkVersion": Literal["V2"],
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
-ExportApiResponseTypeDef = TypedDict(
-    "ExportApiResponseTypeDef",
-    {
-        "body": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetApiMappingResponseTypeDef = TypedDict(
-    "GetApiMappingResponseTypeDef",
-    {
-        "ApiId": str,
-        "ApiMappingId": str,
-        "ApiMappingKey": str,
-        "Stage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetApiMappingsResponseTypeDef = TypedDict(
-    "GetApiMappingsResponseTypeDef",
-    {
-        "Items": List[ApiMappingTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetApiResponseTypeDef = TypedDict(
     "GetApiResponseTypeDef",
     {
         "ApiEndpoint": str,
@@ -1591,103 +1707,15 @@
         "ImportInfo": List[str],
         "Name": str,
         "ProtocolType": ProtocolTypeType,
         "RouteSelectionExpression": str,
         "Tags": Dict[str, str],
         "Version": str,
         "Warnings": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAuthorizerResponseTypeDef = TypedDict(
-    "GetAuthorizerResponseTypeDef",
-    {
-        "AuthorizerCredentialsArn": str,
-        "AuthorizerId": str,
-        "AuthorizerPayloadFormatVersion": str,
-        "AuthorizerResultTtlInSeconds": int,
-        "AuthorizerType": AuthorizerTypeType,
-        "AuthorizerUri": str,
-        "EnableSimpleResponses": bool,
-        "IdentitySource": List[str],
-        "IdentityValidationExpression": str,
-        "JwtConfiguration": JWTConfigurationTypeDef,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDeploymentResponseTypeDef = TypedDict(
-    "GetDeploymentResponseTypeDef",
-    {
-        "AutoDeployed": bool,
-        "CreatedDate": datetime,
-        "DeploymentId": str,
-        "DeploymentStatus": DeploymentStatusType,
-        "DeploymentStatusMessage": str,
-        "Description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetIntegrationResponseResponseTypeDef = TypedDict(
-    "GetIntegrationResponseResponseTypeDef",
-    {
-        "ContentHandlingStrategy": ContentHandlingStrategyType,
-        "IntegrationResponseId": str,
-        "IntegrationResponseKey": str,
-        "ResponseParameters": Dict[str, str],
-        "ResponseTemplates": Dict[str, str],
-        "TemplateSelectionExpression": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetModelResponseTypeDef = TypedDict(
-    "GetModelResponseTypeDef",
-    {
-        "ContentType": str,
-        "Description": str,
-        "ModelId": str,
-        "Name": str,
-        "Schema": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetModelTemplateResponseTypeDef = TypedDict(
-    "GetModelTemplateResponseTypeDef",
-    {
-        "Value": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTagsResponseTypeDef = TypedDict(
-    "GetTagsResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetVpcLinkResponseTypeDef = TypedDict(
-    "GetVpcLinkResponseTypeDef",
-    {
-        "CreatedDate": datetime,
-        "Name": str,
-        "SecurityGroupIds": List[str],
-        "SubnetIds": List[str],
-        "Tags": Dict[str, str],
-        "VpcLinkId": str,
-        "VpcLinkStatus": VpcLinkStatusType,
-        "VpcLinkStatusMessage": str,
-        "VpcLinkVersion": Literal["V2"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportApiResponseTypeDef = TypedDict(
     "ImportApiResponseTypeDef",
     {
         "ApiEndpoint": str,
@@ -1702,15 +1730,15 @@
         "ImportInfo": List[str],
         "Name": str,
         "ProtocolType": ProtocolTypeType,
         "RouteSelectionExpression": str,
         "Tags": Dict[str, str],
         "Version": str,
         "Warnings": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReimportApiResponseTypeDef = TypedDict(
     "ReimportApiResponseTypeDef",
     {
         "ApiEndpoint": str,
@@ -1725,28 +1753,46 @@
         "ImportInfo": List[str],
         "Name": str,
         "ProtocolType": ProtocolTypeType,
         "RouteSelectionExpression": str,
         "Tags": Dict[str, str],
         "Version": str,
         "Warnings": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateApiMappingResponseTypeDef = TypedDict(
-    "UpdateApiMappingResponseTypeDef",
+_RequiredUpdateApiRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateApiRequestRequestTypeDef",
     {
         "ApiId": str,
-        "ApiMappingId": str,
-        "ApiMappingKey": str,
-        "Stage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
+_OptionalUpdateApiRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateApiRequestRequestTypeDef",
+    {
+        "ApiKeySelectionExpression": str,
+        "CorsConfiguration": CorsTypeDef,
+        "CredentialsArn": str,
+        "Description": str,
+        "DisableSchemaValidation": bool,
+        "DisableExecuteApiEndpoint": bool,
+        "Name": str,
+        "RouteKey": str,
+        "RouteSelectionExpression": str,
+        "Target": str,
+        "Version": str,
+    },
+    total=False,
+)
+
+class UpdateApiRequestRequestTypeDef(
+    _RequiredUpdateApiRequestRequestTypeDef, _OptionalUpdateApiRequestRequestTypeDef
+):
+    pass
 
 UpdateApiResponseTypeDef = TypedDict(
     "UpdateApiResponseTypeDef",
     {
         "ApiEndpoint": str,
         "ApiGatewayManaged": bool,
         "ApiId": str,
@@ -1759,87 +1805,152 @@
         "ImportInfo": List[str],
         "Name": str,
         "ProtocolType": ProtocolTypeType,
         "RouteSelectionExpression": str,
         "Tags": Dict[str, str],
         "Version": str,
         "Warnings": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateAuthorizerResponseTypeDef = TypedDict(
-    "UpdateAuthorizerResponseTypeDef",
+_RequiredAuthorizerTypeDef = TypedDict(
+    "_RequiredAuthorizerTypeDef",
+    {
+        "Name": str,
+    },
+)
+_OptionalAuthorizerTypeDef = TypedDict(
+    "_OptionalAuthorizerTypeDef",
     {
         "AuthorizerCredentialsArn": str,
         "AuthorizerId": str,
         "AuthorizerPayloadFormatVersion": str,
         "AuthorizerResultTtlInSeconds": int,
         "AuthorizerType": AuthorizerTypeType,
         "AuthorizerUri": str,
         "EnableSimpleResponses": bool,
         "IdentitySource": List[str],
         "IdentityValidationExpression": str,
         "JwtConfiguration": JWTConfigurationTypeDef,
+    },
+    total=False,
+)
+
+class AuthorizerTypeDef(_RequiredAuthorizerTypeDef, _OptionalAuthorizerTypeDef):
+    pass
+
+_RequiredCreateAuthorizerRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateAuthorizerRequestRequestTypeDef",
+    {
+        "ApiId": str,
+        "AuthorizerType": AuthorizerTypeType,
+        "IdentitySource": Sequence[str],
         "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
+_OptionalCreateAuthorizerRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateAuthorizerRequestRequestTypeDef",
+    {
+        "AuthorizerCredentialsArn": str,
+        "AuthorizerPayloadFormatVersion": str,
+        "AuthorizerResultTtlInSeconds": int,
+        "AuthorizerUri": str,
+        "EnableSimpleResponses": bool,
+        "IdentityValidationExpression": str,
+        "JwtConfiguration": JWTConfigurationTypeDef,
+    },
+    total=False,
+)
 
-UpdateDeploymentResponseTypeDef = TypedDict(
-    "UpdateDeploymentResponseTypeDef",
+class CreateAuthorizerRequestRequestTypeDef(
+    _RequiredCreateAuthorizerRequestRequestTypeDef, _OptionalCreateAuthorizerRequestRequestTypeDef
+):
+    pass
+
+CreateAuthorizerResponseTypeDef = TypedDict(
+    "CreateAuthorizerResponseTypeDef",
     {
-        "AutoDeployed": bool,
-        "CreatedDate": datetime,
-        "DeploymentId": str,
-        "DeploymentStatus": DeploymentStatusType,
-        "DeploymentStatusMessage": str,
-        "Description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AuthorizerCredentialsArn": str,
+        "AuthorizerId": str,
+        "AuthorizerPayloadFormatVersion": str,
+        "AuthorizerResultTtlInSeconds": int,
+        "AuthorizerType": AuthorizerTypeType,
+        "AuthorizerUri": str,
+        "EnableSimpleResponses": bool,
+        "IdentitySource": List[str],
+        "IdentityValidationExpression": str,
+        "JwtConfiguration": JWTConfigurationTypeDef,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateIntegrationResponseResponseTypeDef = TypedDict(
-    "UpdateIntegrationResponseResponseTypeDef",
+GetAuthorizerResponseTypeDef = TypedDict(
+    "GetAuthorizerResponseTypeDef",
     {
-        "ContentHandlingStrategy": ContentHandlingStrategyType,
-        "IntegrationResponseId": str,
-        "IntegrationResponseKey": str,
-        "ResponseParameters": Dict[str, str],
-        "ResponseTemplates": Dict[str, str],
-        "TemplateSelectionExpression": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AuthorizerCredentialsArn": str,
+        "AuthorizerId": str,
+        "AuthorizerPayloadFormatVersion": str,
+        "AuthorizerResultTtlInSeconds": int,
+        "AuthorizerType": AuthorizerTypeType,
+        "AuthorizerUri": str,
+        "EnableSimpleResponses": bool,
+        "IdentitySource": List[str],
+        "IdentityValidationExpression": str,
+        "JwtConfiguration": JWTConfigurationTypeDef,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateModelResponseTypeDef = TypedDict(
-    "UpdateModelResponseTypeDef",
+_RequiredUpdateAuthorizerRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateAuthorizerRequestRequestTypeDef",
     {
-        "ContentType": str,
-        "Description": str,
-        "ModelId": str,
+        "ApiId": str,
+        "AuthorizerId": str,
+    },
+)
+_OptionalUpdateAuthorizerRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateAuthorizerRequestRequestTypeDef",
+    {
+        "AuthorizerCredentialsArn": str,
+        "AuthorizerPayloadFormatVersion": str,
+        "AuthorizerResultTtlInSeconds": int,
+        "AuthorizerType": AuthorizerTypeType,
+        "AuthorizerUri": str,
+        "EnableSimpleResponses": bool,
+        "IdentitySource": Sequence[str],
+        "IdentityValidationExpression": str,
+        "JwtConfiguration": JWTConfigurationTypeDef,
         "Name": str,
-        "Schema": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-UpdateVpcLinkResponseTypeDef = TypedDict(
-    "UpdateVpcLinkResponseTypeDef",
+class UpdateAuthorizerRequestRequestTypeDef(
+    _RequiredUpdateAuthorizerRequestRequestTypeDef, _OptionalUpdateAuthorizerRequestRequestTypeDef
+):
+    pass
+
+UpdateAuthorizerResponseTypeDef = TypedDict(
+    "UpdateAuthorizerResponseTypeDef",
     {
-        "CreatedDate": datetime,
+        "AuthorizerCredentialsArn": str,
+        "AuthorizerId": str,
+        "AuthorizerPayloadFormatVersion": str,
+        "AuthorizerResultTtlInSeconds": int,
+        "AuthorizerType": AuthorizerTypeType,
+        "AuthorizerUri": str,
+        "EnableSimpleResponses": bool,
+        "IdentitySource": List[str],
+        "IdentityValidationExpression": str,
+        "JwtConfiguration": JWTConfigurationTypeDef,
         "Name": str,
-        "SecurityGroupIds": List[str],
-        "SubnetIds": List[str],
-        "Tags": Dict[str, str],
-        "VpcLinkId": str,
-        "VpcLinkStatus": VpcLinkStatusType,
-        "VpcLinkStatusMessage": str,
-        "VpcLinkVersion": Literal["V2"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDomainNameRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDomainNameRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -1851,21 +1962,19 @@
         "DomainNameConfigurations": Sequence[DomainNameConfigurationTypeDef],
         "MutualTlsAuthentication": MutualTlsAuthenticationInputTypeDef,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateDomainNameRequestRequestTypeDef(
     _RequiredCreateDomainNameRequestRequestTypeDef, _OptionalCreateDomainNameRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateDomainNameRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDomainNameRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalUpdateDomainNameRequestRequestTypeDef = TypedDict(
@@ -1873,30 +1982,28 @@
     {
         "DomainNameConfigurations": Sequence[DomainNameConfigurationTypeDef],
         "MutualTlsAuthentication": MutualTlsAuthenticationInputTypeDef,
     },
     total=False,
 )
 
-
 class UpdateDomainNameRequestRequestTypeDef(
     _RequiredUpdateDomainNameRequestRequestTypeDef, _OptionalUpdateDomainNameRequestRequestTypeDef
 ):
     pass
 
-
 CreateDomainNameResponseTypeDef = TypedDict(
     "CreateDomainNameResponseTypeDef",
     {
         "ApiMappingSelectionExpression": str,
         "DomainName": str,
         "DomainNameConfigurations": List[DomainNameConfigurationTypeDef],
         "MutualTlsAuthentication": MutualTlsAuthenticationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDomainNameTypeDef = TypedDict(
     "_RequiredDomainNameTypeDef",
     {
         "DomainName": str,
@@ -1909,40 +2016,38 @@
         "DomainNameConfigurations": List[DomainNameConfigurationTypeDef],
         "MutualTlsAuthentication": MutualTlsAuthenticationTypeDef,
         "Tags": Dict[str, str],
     },
     total=False,
 )
 
-
 class DomainNameTypeDef(_RequiredDomainNameTypeDef, _OptionalDomainNameTypeDef):
     pass
 
-
 GetDomainNameResponseTypeDef = TypedDict(
     "GetDomainNameResponseTypeDef",
     {
         "ApiMappingSelectionExpression": str,
         "DomainName": str,
         "DomainNameConfigurations": List[DomainNameConfigurationTypeDef],
         "MutualTlsAuthentication": MutualTlsAuthenticationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDomainNameResponseTypeDef = TypedDict(
     "UpdateDomainNameResponseTypeDef",
     {
         "ApiMappingSelectionExpression": str,
         "DomainName": str,
         "DomainNameConfigurations": List[DomainNameConfigurationTypeDef],
         "MutualTlsAuthentication": MutualTlsAuthenticationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateIntegrationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateIntegrationRequestRequestTypeDef",
     {
         "ApiId": str,
@@ -1968,21 +2073,19 @@
         "TemplateSelectionExpression": str,
         "TimeoutInMillis": int,
         "TlsConfig": TlsConfigInputTypeDef,
     },
     total=False,
 )
 
-
 class CreateIntegrationRequestRequestTypeDef(
     _RequiredCreateIntegrationRequestRequestTypeDef, _OptionalCreateIntegrationRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateIntegrationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateIntegrationRequestRequestTypeDef",
     {
         "ApiId": str,
         "IntegrationId": str,
     },
 )
@@ -2006,21 +2109,19 @@
         "TemplateSelectionExpression": str,
         "TimeoutInMillis": int,
         "TlsConfig": TlsConfigInputTypeDef,
     },
     total=False,
 )
 
-
 class UpdateIntegrationRequestRequestTypeDef(
     _RequiredUpdateIntegrationRequestRequestTypeDef, _OptionalUpdateIntegrationRequestRequestTypeDef
 ):
     pass
 
-
 CreateIntegrationResultTypeDef = TypedDict(
     "CreateIntegrationResultTypeDef",
     {
         "ApiGatewayManaged": bool,
         "ConnectionId": str,
         "ConnectionType": ConnectionTypeType,
         "ContentHandlingStrategy": ContentHandlingStrategyType,
@@ -2036,15 +2137,15 @@
         "PayloadFormatVersion": str,
         "RequestParameters": Dict[str, str],
         "RequestTemplates": Dict[str, str],
         "ResponseParameters": Dict[str, Dict[str, str]],
         "TemplateSelectionExpression": str,
         "TimeoutInMillis": int,
         "TlsConfig": TlsConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIntegrationResultTypeDef = TypedDict(
     "GetIntegrationResultTypeDef",
     {
         "ApiGatewayManaged": bool,
@@ -2063,15 +2164,15 @@
         "PayloadFormatVersion": str,
         "RequestParameters": Dict[str, str],
         "RequestTemplates": Dict[str, str],
         "ResponseParameters": Dict[str, Dict[str, str]],
         "TemplateSelectionExpression": str,
         "TimeoutInMillis": int,
         "TlsConfig": TlsConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IntegrationTypeDef = TypedDict(
     "IntegrationTypeDef",
     {
         "ApiGatewayManaged": bool,
@@ -2117,15 +2218,15 @@
         "PayloadFormatVersion": str,
         "RequestParameters": Dict[str, str],
         "RequestTemplates": Dict[str, str],
         "ResponseParameters": Dict[str, Dict[str, str]],
         "TemplateSelectionExpression": str,
         "TimeoutInMillis": int,
         "TlsConfig": TlsConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateRouteRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRouteRequestRequestTypeDef",
     {
         "ApiId": str,
@@ -2145,21 +2246,19 @@
         "RequestParameters": Mapping[str, ParameterConstraintsTypeDef],
         "RouteResponseSelectionExpression": str,
         "Target": str,
     },
     total=False,
 )
 
-
 class CreateRouteRequestRequestTypeDef(
     _RequiredCreateRouteRequestRequestTypeDef, _OptionalCreateRouteRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateRouteResponseRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRouteResponseRequestRequestTypeDef",
     {
         "ApiId": str,
         "RouteId": str,
         "RouteResponseKey": str,
     },
@@ -2170,31 +2269,29 @@
         "ModelSelectionExpression": str,
         "ResponseModels": Mapping[str, str],
         "ResponseParameters": Mapping[str, ParameterConstraintsTypeDef],
     },
     total=False,
 )
 
-
 class CreateRouteResponseRequestRequestTypeDef(
     _RequiredCreateRouteResponseRequestRequestTypeDef,
     _OptionalCreateRouteResponseRequestRequestTypeDef,
 ):
     pass
 
-
 CreateRouteResponseResponseTypeDef = TypedDict(
     "CreateRouteResponseResponseTypeDef",
     {
         "ModelSelectionExpression": str,
         "ResponseModels": Dict[str, str],
         "ResponseParameters": Dict[str, ParameterConstraintsTypeDef],
         "RouteResponseId": str,
         "RouteResponseKey": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRouteResultTypeDef = TypedDict(
     "CreateRouteResultTypeDef",
     {
         "ApiGatewayManaged": bool,
@@ -2206,27 +2303,27 @@
         "OperationName": str,
         "RequestModels": Dict[str, str],
         "RequestParameters": Dict[str, ParameterConstraintsTypeDef],
         "RouteId": str,
         "RouteKey": str,
         "RouteResponseSelectionExpression": str,
         "Target": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRouteResponseResponseTypeDef = TypedDict(
     "GetRouteResponseResponseTypeDef",
     {
         "ModelSelectionExpression": str,
         "ResponseModels": Dict[str, str],
         "ResponseParameters": Dict[str, ParameterConstraintsTypeDef],
         "RouteResponseId": str,
         "RouteResponseKey": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRouteResultTypeDef = TypedDict(
     "GetRouteResultTypeDef",
     {
         "ApiGatewayManaged": bool,
@@ -2238,15 +2335,15 @@
         "OperationName": str,
         "RequestModels": Dict[str, str],
         "RequestParameters": Dict[str, ParameterConstraintsTypeDef],
         "RouteId": str,
         "RouteKey": str,
         "RouteResponseSelectionExpression": str,
         "Target": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRouteResponseTypeDef = TypedDict(
     "_RequiredRouteResponseTypeDef",
     {
         "RouteResponseKey": str,
@@ -2259,19 +2356,17 @@
         "ResponseModels": Dict[str, str],
         "ResponseParameters": Dict[str, ParameterConstraintsTypeDef],
         "RouteResponseId": str,
     },
     total=False,
 )
 
-
 class RouteResponseTypeDef(_RequiredRouteResponseTypeDef, _OptionalRouteResponseTypeDef):
     pass
 
-
 _RequiredRouteTypeDef = TypedDict(
     "_RequiredRouteTypeDef",
     {
         "RouteKey": str,
     },
 )
 _OptionalRouteTypeDef = TypedDict(
@@ -2289,19 +2384,17 @@
         "RouteId": str,
         "RouteResponseSelectionExpression": str,
         "Target": str,
     },
     total=False,
 )
 
-
 class RouteTypeDef(_RequiredRouteTypeDef, _OptionalRouteTypeDef):
     pass
 
-
 _RequiredUpdateRouteRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRouteRequestRequestTypeDef",
     {
         "ApiId": str,
         "RouteId": str,
     },
 )
@@ -2319,21 +2412,19 @@
         "RouteKey": str,
         "RouteResponseSelectionExpression": str,
         "Target": str,
     },
     total=False,
 )
 
-
 class UpdateRouteRequestRequestTypeDef(
     _RequiredUpdateRouteRequestRequestTypeDef, _OptionalUpdateRouteRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateRouteResponseRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRouteResponseRequestRequestTypeDef",
     {
         "ApiId": str,
         "RouteId": str,
         "RouteResponseId": str,
     },
@@ -2345,31 +2436,29 @@
         "ResponseModels": Mapping[str, str],
         "ResponseParameters": Mapping[str, ParameterConstraintsTypeDef],
         "RouteResponseKey": str,
     },
     total=False,
 )
 
-
 class UpdateRouteResponseRequestRequestTypeDef(
     _RequiredUpdateRouteResponseRequestRequestTypeDef,
     _OptionalUpdateRouteResponseRequestRequestTypeDef,
 ):
     pass
 
-
 UpdateRouteResponseResponseTypeDef = TypedDict(
     "UpdateRouteResponseResponseTypeDef",
     {
         "ModelSelectionExpression": str,
         "ResponseModels": Dict[str, str],
         "ResponseParameters": Dict[str, ParameterConstraintsTypeDef],
         "RouteResponseId": str,
         "RouteResponseKey": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRouteResultTypeDef = TypedDict(
     "UpdateRouteResultTypeDef",
     {
         "ApiGatewayManaged": bool,
@@ -2381,15 +2470,15 @@
         "OperationName": str,
         "RequestModels": Dict[str, str],
         "RequestParameters": Dict[str, ParameterConstraintsTypeDef],
         "RouteId": str,
         "RouteKey": str,
         "RouteResponseSelectionExpression": str,
         "Target": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateStageRequestRequestTypeDef = TypedDict(
     "_RequiredCreateStageRequestRequestTypeDef",
     {
         "ApiId": str,
@@ -2408,21 +2497,19 @@
         "RouteSettings": Mapping[str, RouteSettingsTypeDef],
         "StageVariables": Mapping[str, str],
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateStageRequestRequestTypeDef(
     _RequiredCreateStageRequestRequestTypeDef, _OptionalCreateStageRequestRequestTypeDef
 ):
     pass
 
-
 CreateStageResponseTypeDef = TypedDict(
     "CreateStageResponseTypeDef",
     {
         "AccessLogSettings": AccessLogSettingsTypeDef,
         "ApiGatewayManaged": bool,
         "AutoDeploy": bool,
         "ClientCertificateId": str,
@@ -2432,15 +2519,15 @@
         "Description": str,
         "LastDeploymentStatusMessage": str,
         "LastUpdatedDate": datetime,
         "RouteSettings": Dict[str, RouteSettingsTypeDef],
         "StageName": str,
         "StageVariables": Dict[str, str],
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStageResponseTypeDef = TypedDict(
     "GetStageResponseTypeDef",
     {
         "AccessLogSettings": AccessLogSettingsTypeDef,
@@ -2453,15 +2540,15 @@
         "Description": str,
         "LastDeploymentStatusMessage": str,
         "LastUpdatedDate": datetime,
         "RouteSettings": Dict[str, RouteSettingsTypeDef],
         "StageName": str,
         "StageVariables": Dict[str, str],
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStageTypeDef = TypedDict(
     "_RequiredStageTypeDef",
     {
         "StageName": str,
@@ -2483,19 +2570,17 @@
         "RouteSettings": Dict[str, RouteSettingsTypeDef],
         "StageVariables": Dict[str, str],
         "Tags": Dict[str, str],
     },
     total=False,
 )
 
-
 class StageTypeDef(_RequiredStageTypeDef, _OptionalStageTypeDef):
     pass
 
-
 _RequiredUpdateStageRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateStageRequestRequestTypeDef",
     {
         "ApiId": str,
         "StageName": str,
     },
 )
@@ -2510,21 +2595,19 @@
         "Description": str,
         "RouteSettings": Mapping[str, RouteSettingsTypeDef],
         "StageVariables": Mapping[str, str],
     },
     total=False,
 )
 
-
 class UpdateStageRequestRequestTypeDef(
     _RequiredUpdateStageRequestRequestTypeDef, _OptionalUpdateStageRequestRequestTypeDef
 ):
     pass
 
-
 UpdateStageResponseTypeDef = TypedDict(
     "UpdateStageResponseTypeDef",
     {
         "AccessLogSettings": AccessLogSettingsTypeDef,
         "ApiGatewayManaged": bool,
         "AutoDeploy": bool,
         "ClientCertificateId": str,
@@ -2534,303 +2617,109 @@
         "Description": str,
         "LastDeploymentStatusMessage": str,
         "LastUpdatedDate": datetime,
         "RouteSettings": Dict[str, RouteSettingsTypeDef],
         "StageName": str,
         "StageVariables": Dict[str, str],
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeploymentsResponseTypeDef = TypedDict(
     "GetDeploymentsResponseTypeDef",
     {
         "Items": List[DeploymentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetApisRequestGetApisPaginateTypeDef = TypedDict(
-    "GetApisRequestGetApisPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetAuthorizersRequestGetAuthorizersPaginateTypeDef = TypedDict(
-    "_RequiredGetAuthorizersRequestGetAuthorizersPaginateTypeDef",
-    {
-        "ApiId": str,
-    },
-)
-_OptionalGetAuthorizersRequestGetAuthorizersPaginateTypeDef = TypedDict(
-    "_OptionalGetAuthorizersRequestGetAuthorizersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetAuthorizersRequestGetAuthorizersPaginateTypeDef(
-    _RequiredGetAuthorizersRequestGetAuthorizersPaginateTypeDef,
-    _OptionalGetAuthorizersRequestGetAuthorizersPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetDeploymentsRequestGetDeploymentsPaginateTypeDef = TypedDict(
-    "_RequiredGetDeploymentsRequestGetDeploymentsPaginateTypeDef",
-    {
-        "ApiId": str,
-    },
-)
-_OptionalGetDeploymentsRequestGetDeploymentsPaginateTypeDef = TypedDict(
-    "_OptionalGetDeploymentsRequestGetDeploymentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetDeploymentsRequestGetDeploymentsPaginateTypeDef(
-    _RequiredGetDeploymentsRequestGetDeploymentsPaginateTypeDef,
-    _OptionalGetDeploymentsRequestGetDeploymentsPaginateTypeDef,
-):
-    pass
-
-
-GetDomainNamesRequestGetDomainNamesPaginateTypeDef = TypedDict(
-    "GetDomainNamesRequestGetDomainNamesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef = TypedDict(
-    "_RequiredGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef",
-    {
-        "ApiId": str,
-        "IntegrationId": str,
-    },
-)
-_OptionalGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef = TypedDict(
-    "_OptionalGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef(
-    _RequiredGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef,
-    _OptionalGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetIntegrationsRequestGetIntegrationsPaginateTypeDef = TypedDict(
-    "_RequiredGetIntegrationsRequestGetIntegrationsPaginateTypeDef",
-    {
-        "ApiId": str,
-    },
-)
-_OptionalGetIntegrationsRequestGetIntegrationsPaginateTypeDef = TypedDict(
-    "_OptionalGetIntegrationsRequestGetIntegrationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetIntegrationsRequestGetIntegrationsPaginateTypeDef(
-    _RequiredGetIntegrationsRequestGetIntegrationsPaginateTypeDef,
-    _OptionalGetIntegrationsRequestGetIntegrationsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetModelsRequestGetModelsPaginateTypeDef = TypedDict(
-    "_RequiredGetModelsRequestGetModelsPaginateTypeDef",
-    {
-        "ApiId": str,
-    },
-)
-_OptionalGetModelsRequestGetModelsPaginateTypeDef = TypedDict(
-    "_OptionalGetModelsRequestGetModelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetModelsRequestGetModelsPaginateTypeDef(
-    _RequiredGetModelsRequestGetModelsPaginateTypeDef,
-    _OptionalGetModelsRequestGetModelsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef = TypedDict(
-    "_RequiredGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef",
-    {
-        "ApiId": str,
-        "RouteId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef = TypedDict(
-    "_OptionalGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetRouteResponsesRequestGetRouteResponsesPaginateTypeDef(
-    _RequiredGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef,
-    _OptionalGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetRoutesRequestGetRoutesPaginateTypeDef = TypedDict(
-    "_RequiredGetRoutesRequestGetRoutesPaginateTypeDef",
-    {
-        "ApiId": str,
-    },
-)
-_OptionalGetRoutesRequestGetRoutesPaginateTypeDef = TypedDict(
-    "_OptionalGetRoutesRequestGetRoutesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetRoutesRequestGetRoutesPaginateTypeDef(
-    _RequiredGetRoutesRequestGetRoutesPaginateTypeDef,
-    _OptionalGetRoutesRequestGetRoutesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetStagesRequestGetStagesPaginateTypeDef = TypedDict(
-    "_RequiredGetStagesRequestGetStagesPaginateTypeDef",
-    {
-        "ApiId": str,
-    },
-)
-_OptionalGetStagesRequestGetStagesPaginateTypeDef = TypedDict(
-    "_OptionalGetStagesRequestGetStagesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetStagesRequestGetStagesPaginateTypeDef(
-    _RequiredGetStagesRequestGetStagesPaginateTypeDef,
-    _OptionalGetStagesRequestGetStagesPaginateTypeDef,
-):
-    pass
-
 
 GetIntegrationResponsesResponseTypeDef = TypedDict(
     "GetIntegrationResponsesResponseTypeDef",
     {
         "Items": List[IntegrationResponseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetModelsResponseTypeDef = TypedDict(
     "GetModelsResponseTypeDef",
     {
         "Items": List[ModelTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVpcLinksResponseTypeDef = TypedDict(
     "GetVpcLinksResponseTypeDef",
     {
         "Items": List[VpcLinkTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetApisResponseTypeDef = TypedDict(
     "GetApisResponseTypeDef",
     {
         "Items": List[ApiTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAuthorizersResponseTypeDef = TypedDict(
     "GetAuthorizersResponseTypeDef",
     {
         "Items": List[AuthorizerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainNamesResponseTypeDef = TypedDict(
     "GetDomainNamesResponseTypeDef",
     {
         "Items": List[DomainNameTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIntegrationsResponseTypeDef = TypedDict(
     "GetIntegrationsResponseTypeDef",
     {
         "Items": List[IntegrationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRouteResponsesResponseTypeDef = TypedDict(
     "GetRouteResponsesResponseTypeDef",
     {
         "Items": List[RouteResponseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRoutesResponseTypeDef = TypedDict(
     "GetRoutesResponseTypeDef",
     {
         "Items": List[RouteTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStagesResponseTypeDef = TypedDict(
     "GetStagesResponseTypeDef",
     {
         "Items": List[StageTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2/type_defs.pyi` & `types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -39,32 +39,37 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AccessLogSettingsTypeDef",
     "ApiMappingTypeDef",
     "CorsTypeDef",
     "JWTConfigurationTypeDef",
     "CreateApiMappingRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateApiMappingResponseTypeDef",
     "CreateDeploymentRequestRequestTypeDef",
+    "CreateDeploymentResponseTypeDef",
     "DomainNameConfigurationTypeDef",
     "MutualTlsAuthenticationInputTypeDef",
     "MutualTlsAuthenticationTypeDef",
     "TlsConfigInputTypeDef",
     "CreateIntegrationResponseRequestRequestTypeDef",
+    "CreateIntegrationResponseResponseTypeDef",
     "TlsConfigTypeDef",
     "CreateModelRequestRequestTypeDef",
+    "CreateModelResponseTypeDef",
     "ParameterConstraintsTypeDef",
     "RouteSettingsTypeDef",
     "CreateVpcLinkRequestRequestTypeDef",
+    "CreateVpcLinkResponseTypeDef",
     "DeleteAccessLogSettingsRequestRequestTypeDef",
     "DeleteApiMappingRequestRequestTypeDef",
     "DeleteApiRequestRequestTypeDef",
     "DeleteAuthorizerRequestRequestTypeDef",
     "DeleteCorsConfigurationRequestRequestTypeDef",
     "DeleteDeploymentRequestRequestTypeDef",
     "DeleteDomainNameRequestRequestTypeDef",
@@ -74,89 +79,95 @@
     "DeleteRouteRequestParameterRequestRequestTypeDef",
     "DeleteRouteRequestRequestTypeDef",
     "DeleteRouteResponseRequestRequestTypeDef",
     "DeleteRouteSettingsRequestRequestTypeDef",
     "DeleteStageRequestRequestTypeDef",
     "DeleteVpcLinkRequestRequestTypeDef",
     "DeploymentTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExportApiRequestRequestTypeDef",
+    "ExportApiResponseTypeDef",
     "GetApiMappingRequestRequestTypeDef",
+    "GetApiMappingResponseTypeDef",
     "GetApiMappingsRequestRequestTypeDef",
     "GetApiRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetApisRequestGetApisPaginateTypeDef",
     "GetApisRequestRequestTypeDef",
     "GetAuthorizerRequestRequestTypeDef",
+    "GetAuthorizersRequestGetAuthorizersPaginateTypeDef",
     "GetAuthorizersRequestRequestTypeDef",
     "GetDeploymentRequestRequestTypeDef",
+    "GetDeploymentResponseTypeDef",
+    "GetDeploymentsRequestGetDeploymentsPaginateTypeDef",
     "GetDeploymentsRequestRequestTypeDef",
     "GetDomainNameRequestRequestTypeDef",
+    "GetDomainNamesRequestGetDomainNamesPaginateTypeDef",
     "GetDomainNamesRequestRequestTypeDef",
     "GetIntegrationRequestRequestTypeDef",
     "GetIntegrationResponseRequestRequestTypeDef",
+    "GetIntegrationResponseResponseTypeDef",
+    "GetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef",
     "GetIntegrationResponsesRequestRequestTypeDef",
     "IntegrationResponseTypeDef",
+    "GetIntegrationsRequestGetIntegrationsPaginateTypeDef",
     "GetIntegrationsRequestRequestTypeDef",
     "GetModelRequestRequestTypeDef",
+    "GetModelResponseTypeDef",
     "GetModelTemplateRequestRequestTypeDef",
+    "GetModelTemplateResponseTypeDef",
+    "GetModelsRequestGetModelsPaginateTypeDef",
     "GetModelsRequestRequestTypeDef",
     "ModelTypeDef",
     "GetRouteRequestRequestTypeDef",
     "GetRouteResponseRequestRequestTypeDef",
+    "GetRouteResponsesRequestGetRouteResponsesPaginateTypeDef",
     "GetRouteResponsesRequestRequestTypeDef",
+    "GetRoutesRequestGetRoutesPaginateTypeDef",
     "GetRoutesRequestRequestTypeDef",
     "GetStageRequestRequestTypeDef",
+    "GetStagesRequestGetStagesPaginateTypeDef",
     "GetStagesRequestRequestTypeDef",
     "GetTagsRequestRequestTypeDef",
+    "GetTagsResponseTypeDef",
     "GetVpcLinkRequestRequestTypeDef",
+    "GetVpcLinkResponseTypeDef",
     "GetVpcLinksRequestRequestTypeDef",
     "VpcLinkTypeDef",
     "ImportApiRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ReimportApiRequestRequestTypeDef",
     "ResetAuthorizersCacheRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApiMappingRequestRequestTypeDef",
+    "UpdateApiMappingResponseTypeDef",
     "UpdateDeploymentRequestRequestTypeDef",
+    "UpdateDeploymentResponseTypeDef",
     "UpdateIntegrationResponseRequestRequestTypeDef",
+    "UpdateIntegrationResponseResponseTypeDef",
     "UpdateModelRequestRequestTypeDef",
+    "UpdateModelResponseTypeDef",
     "UpdateVpcLinkRequestRequestTypeDef",
+    "UpdateVpcLinkResponseTypeDef",
+    "GetApiMappingsResponseTypeDef",
     "ApiTypeDef",
     "CreateApiRequestRequestTypeDef",
-    "UpdateApiRequestRequestTypeDef",
-    "AuthorizerTypeDef",
-    "CreateAuthorizerRequestRequestTypeDef",
-    "UpdateAuthorizerRequestRequestTypeDef",
-    "CreateApiMappingResponseTypeDef",
     "CreateApiResponseTypeDef",
-    "CreateAuthorizerResponseTypeDef",
-    "CreateDeploymentResponseTypeDef",
-    "CreateIntegrationResponseResponseTypeDef",
-    "CreateModelResponseTypeDef",
-    "CreateVpcLinkResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExportApiResponseTypeDef",
-    "GetApiMappingResponseTypeDef",
-    "GetApiMappingsResponseTypeDef",
     "GetApiResponseTypeDef",
-    "GetAuthorizerResponseTypeDef",
-    "GetDeploymentResponseTypeDef",
-    "GetIntegrationResponseResponseTypeDef",
-    "GetModelResponseTypeDef",
-    "GetModelTemplateResponseTypeDef",
-    "GetTagsResponseTypeDef",
-    "GetVpcLinkResponseTypeDef",
     "ImportApiResponseTypeDef",
     "ReimportApiResponseTypeDef",
-    "UpdateApiMappingResponseTypeDef",
+    "UpdateApiRequestRequestTypeDef",
     "UpdateApiResponseTypeDef",
+    "AuthorizerTypeDef",
+    "CreateAuthorizerRequestRequestTypeDef",
+    "CreateAuthorizerResponseTypeDef",
+    "GetAuthorizerResponseTypeDef",
+    "UpdateAuthorizerRequestRequestTypeDef",
     "UpdateAuthorizerResponseTypeDef",
-    "UpdateDeploymentResponseTypeDef",
-    "UpdateIntegrationResponseResponseTypeDef",
-    "UpdateModelResponseTypeDef",
-    "UpdateVpcLinkResponseTypeDef",
     "CreateDomainNameRequestRequestTypeDef",
     "UpdateDomainNameRequestRequestTypeDef",
     "CreateDomainNameResponseTypeDef",
     "DomainNameTypeDef",
     "GetDomainNameResponseTypeDef",
     "UpdateDomainNameResponseTypeDef",
     "CreateIntegrationRequestRequestTypeDef",
@@ -180,24 +191,14 @@
     "CreateStageRequestRequestTypeDef",
     "CreateStageResponseTypeDef",
     "GetStageResponseTypeDef",
     "StageTypeDef",
     "UpdateStageRequestRequestTypeDef",
     "UpdateStageResponseTypeDef",
     "GetDeploymentsResponseTypeDef",
-    "GetApisRequestGetApisPaginateTypeDef",
-    "GetAuthorizersRequestGetAuthorizersPaginateTypeDef",
-    "GetDeploymentsRequestGetDeploymentsPaginateTypeDef",
-    "GetDomainNamesRequestGetDomainNamesPaginateTypeDef",
-    "GetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef",
-    "GetIntegrationsRequestGetIntegrationsPaginateTypeDef",
-    "GetModelsRequestGetModelsPaginateTypeDef",
-    "GetRouteResponsesRequestGetRouteResponsesPaginateTypeDef",
-    "GetRoutesRequestGetRoutesPaginateTypeDef",
-    "GetStagesRequestGetStagesPaginateTypeDef",
     "GetIntegrationResponsesResponseTypeDef",
     "GetModelsResponseTypeDef",
     "GetVpcLinksResponseTypeDef",
     "GetApisResponseTypeDef",
     "GetAuthorizersResponseTypeDef",
     "GetDomainNamesResponseTypeDef",
     "GetIntegrationsResponseTypeDef",
@@ -227,17 +228,19 @@
     {
         "ApiMappingId": str,
         "ApiMappingKey": str,
     },
     total=False,
 )
 
+
 class ApiMappingTypeDef(_RequiredApiMappingTypeDef, _OptionalApiMappingTypeDef):
     pass
 
+
 CorsTypeDef = TypedDict(
     "CorsTypeDef",
     {
         "AllowCredentials": bool,
         "AllowHeaders": Sequence[str],
         "AllowMethods": Sequence[str],
         "AllowOrigins": Sequence[str],
@@ -268,27 +271,29 @@
     "_OptionalCreateApiMappingRequestRequestTypeDef",
     {
         "ApiMappingKey": str,
     },
     total=False,
 )
 
+
 class CreateApiMappingRequestRequestTypeDef(
     _RequiredCreateApiMappingRequestRequestTypeDef, _OptionalCreateApiMappingRequestRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+
+CreateApiMappingResponseTypeDef = TypedDict(
+    "CreateApiMappingResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ApiId": str,
+        "ApiMappingId": str,
+        "ApiMappingKey": str,
+        "Stage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDeploymentRequestRequestTypeDef",
     {
         "ApiId": str,
@@ -299,19 +304,34 @@
     {
         "Description": str,
         "StageName": str,
     },
     total=False,
 )
 
+
 class CreateDeploymentRequestRequestTypeDef(
     _RequiredCreateDeploymentRequestRequestTypeDef, _OptionalCreateDeploymentRequestRequestTypeDef
 ):
     pass
 
+
+CreateDeploymentResponseTypeDef = TypedDict(
+    "CreateDeploymentResponseTypeDef",
+    {
+        "AutoDeployed": bool,
+        "CreatedDate": datetime,
+        "DeploymentId": str,
+        "DeploymentStatus": DeploymentStatusType,
+        "DeploymentStatusMessage": str,
+        "Description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DomainNameConfigurationTypeDef = TypedDict(
     "DomainNameConfigurationTypeDef",
     {
         "ApiGatewayDomainName": str,
         "CertificateArn": str,
         "CertificateName": str,
         "CertificateUploadDate": Union[datetime, str],
@@ -367,20 +387,35 @@
         "ResponseParameters": Mapping[str, str],
         "ResponseTemplates": Mapping[str, str],
         "TemplateSelectionExpression": str,
     },
     total=False,
 )
 
+
 class CreateIntegrationResponseRequestRequestTypeDef(
     _RequiredCreateIntegrationResponseRequestRequestTypeDef,
     _OptionalCreateIntegrationResponseRequestRequestTypeDef,
 ):
     pass
 
+
+CreateIntegrationResponseResponseTypeDef = TypedDict(
+    "CreateIntegrationResponseResponseTypeDef",
+    {
+        "ContentHandlingStrategy": ContentHandlingStrategyType,
+        "IntegrationResponseId": str,
+        "IntegrationResponseKey": str,
+        "ResponseParameters": Dict[str, str],
+        "ResponseTemplates": Dict[str, str],
+        "TemplateSelectionExpression": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TlsConfigTypeDef = TypedDict(
     "TlsConfigTypeDef",
     {
         "ServerNameToVerify": str,
     },
     total=False,
 )
@@ -398,19 +433,33 @@
     {
         "ContentType": str,
         "Description": str,
     },
     total=False,
 )
 
+
 class CreateModelRequestRequestTypeDef(
     _RequiredCreateModelRequestRequestTypeDef, _OptionalCreateModelRequestRequestTypeDef
 ):
     pass
 
+
+CreateModelResponseTypeDef = TypedDict(
+    "CreateModelResponseTypeDef",
+    {
+        "ContentType": str,
+        "Description": str,
+        "ModelId": str,
+        "Name": str,
+        "Schema": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ParameterConstraintsTypeDef = TypedDict(
     "ParameterConstraintsTypeDef",
     {
         "Required": bool,
     },
     total=False,
 )
@@ -439,19 +488,37 @@
     {
         "SecurityGroupIds": Sequence[str],
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateVpcLinkRequestRequestTypeDef(
     _RequiredCreateVpcLinkRequestRequestTypeDef, _OptionalCreateVpcLinkRequestRequestTypeDef
 ):
     pass
 
+
+CreateVpcLinkResponseTypeDef = TypedDict(
+    "CreateVpcLinkResponseTypeDef",
+    {
+        "CreatedDate": datetime,
+        "Name": str,
+        "SecurityGroupIds": List[str],
+        "SubnetIds": List[str],
+        "Tags": Dict[str, str],
+        "VpcLinkId": str,
+        "VpcLinkStatus": VpcLinkStatusType,
+        "VpcLinkStatusMessage": str,
+        "VpcLinkVersion": Literal["V2"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteAccessLogSettingsRequestRequestTypeDef = TypedDict(
     "DeleteAccessLogSettingsRequestRequestTypeDef",
     {
         "ApiId": str,
         "StageName": str,
     },
 )
@@ -585,14 +652,21 @@
         "DeploymentStatus": DeploymentStatusType,
         "DeploymentStatusMessage": str,
         "Description": str,
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
 _RequiredExportApiRequestRequestTypeDef = TypedDict(
     "_RequiredExportApiRequestRequestTypeDef",
     {
         "ApiId": str,
         "OutputType": JSONYAMLType,
         "Specification": Literal["OAS30"],
     },
@@ -603,27 +677,48 @@
         "ExportVersion": str,
         "IncludeExtensions": bool,
         "StageName": str,
     },
     total=False,
 )
 
+
 class ExportApiRequestRequestTypeDef(
     _RequiredExportApiRequestRequestTypeDef, _OptionalExportApiRequestRequestTypeDef
 ):
     pass
 
+
+ExportApiResponseTypeDef = TypedDict(
+    "ExportApiResponseTypeDef",
+    {
+        "body": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetApiMappingRequestRequestTypeDef = TypedDict(
     "GetApiMappingRequestRequestTypeDef",
     {
         "ApiMappingId": str,
         "DomainName": str,
     },
 )
 
+GetApiMappingResponseTypeDef = TypedDict(
+    "GetApiMappingResponseTypeDef",
+    {
+        "ApiId": str,
+        "ApiMappingId": str,
+        "ApiMappingKey": str,
+        "Stage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetApiMappingsRequestRequestTypeDef = TypedDict(
     "_RequiredGetApiMappingsRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalGetApiMappingsRequestRequestTypeDef = TypedDict(
@@ -631,32 +726,32 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetApiMappingsRequestRequestTypeDef(
     _RequiredGetApiMappingsRequestRequestTypeDef, _OptionalGetApiMappingsRequestRequestTypeDef
 ):
     pass
 
+
 GetApiRequestRequestTypeDef = TypedDict(
     "GetApiRequestRequestTypeDef",
     {
         "ApiId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetApisRequestGetApisPaginateTypeDef = TypedDict(
+    "GetApisRequestGetApisPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetApisRequestRequestTypeDef = TypedDict(
     "GetApisRequestRequestTypeDef",
     {
@@ -670,14 +765,36 @@
     "GetAuthorizerRequestRequestTypeDef",
     {
         "ApiId": str,
         "AuthorizerId": str,
     },
 )
 
+_RequiredGetAuthorizersRequestGetAuthorizersPaginateTypeDef = TypedDict(
+    "_RequiredGetAuthorizersRequestGetAuthorizersPaginateTypeDef",
+    {
+        "ApiId": str,
+    },
+)
+_OptionalGetAuthorizersRequestGetAuthorizersPaginateTypeDef = TypedDict(
+    "_OptionalGetAuthorizersRequestGetAuthorizersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetAuthorizersRequestGetAuthorizersPaginateTypeDef(
+    _RequiredGetAuthorizersRequestGetAuthorizersPaginateTypeDef,
+    _OptionalGetAuthorizersRequestGetAuthorizersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetAuthorizersRequestRequestTypeDef = TypedDict(
     "_RequiredGetAuthorizersRequestRequestTypeDef",
     {
         "ApiId": str,
     },
 )
 _OptionalGetAuthorizersRequestRequestTypeDef = TypedDict(
@@ -685,27 +802,64 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetAuthorizersRequestRequestTypeDef(
     _RequiredGetAuthorizersRequestRequestTypeDef, _OptionalGetAuthorizersRequestRequestTypeDef
 ):
     pass
 
+
 GetDeploymentRequestRequestTypeDef = TypedDict(
     "GetDeploymentRequestRequestTypeDef",
     {
         "ApiId": str,
         "DeploymentId": str,
     },
 )
 
+GetDeploymentResponseTypeDef = TypedDict(
+    "GetDeploymentResponseTypeDef",
+    {
+        "AutoDeployed": bool,
+        "CreatedDate": datetime,
+        "DeploymentId": str,
+        "DeploymentStatus": DeploymentStatusType,
+        "DeploymentStatusMessage": str,
+        "Description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetDeploymentsRequestGetDeploymentsPaginateTypeDef = TypedDict(
+    "_RequiredGetDeploymentsRequestGetDeploymentsPaginateTypeDef",
+    {
+        "ApiId": str,
+    },
+)
+_OptionalGetDeploymentsRequestGetDeploymentsPaginateTypeDef = TypedDict(
+    "_OptionalGetDeploymentsRequestGetDeploymentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetDeploymentsRequestGetDeploymentsPaginateTypeDef(
+    _RequiredGetDeploymentsRequestGetDeploymentsPaginateTypeDef,
+    _OptionalGetDeploymentsRequestGetDeploymentsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetDeploymentsRequestRequestTypeDef = TypedDict(
     "_RequiredGetDeploymentsRequestRequestTypeDef",
     {
         "ApiId": str,
     },
 )
 _OptionalGetDeploymentsRequestRequestTypeDef = TypedDict(
@@ -713,26 +867,36 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetDeploymentsRequestRequestTypeDef(
     _RequiredGetDeploymentsRequestRequestTypeDef, _OptionalGetDeploymentsRequestRequestTypeDef
 ):
     pass
 
+
 GetDomainNameRequestRequestTypeDef = TypedDict(
     "GetDomainNameRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+GetDomainNamesRequestGetDomainNamesPaginateTypeDef = TypedDict(
+    "GetDomainNamesRequestGetDomainNamesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetDomainNamesRequestRequestTypeDef = TypedDict(
     "GetDomainNamesRequestRequestTypeDef",
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
@@ -751,14 +915,50 @@
     {
         "ApiId": str,
         "IntegrationId": str,
         "IntegrationResponseId": str,
     },
 )
 
+GetIntegrationResponseResponseTypeDef = TypedDict(
+    "GetIntegrationResponseResponseTypeDef",
+    {
+        "ContentHandlingStrategy": ContentHandlingStrategyType,
+        "IntegrationResponseId": str,
+        "IntegrationResponseKey": str,
+        "ResponseParameters": Dict[str, str],
+        "ResponseTemplates": Dict[str, str],
+        "TemplateSelectionExpression": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef = TypedDict(
+    "_RequiredGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef",
+    {
+        "ApiId": str,
+        "IntegrationId": str,
+    },
+)
+_OptionalGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef = TypedDict(
+    "_OptionalGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef(
+    _RequiredGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef,
+    _OptionalGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetIntegrationResponsesRequestRequestTypeDef = TypedDict(
     "_RequiredGetIntegrationResponsesRequestRequestTypeDef",
     {
         "ApiId": str,
         "IntegrationId": str,
     },
 )
@@ -767,20 +967,22 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetIntegrationResponsesRequestRequestTypeDef(
     _RequiredGetIntegrationResponsesRequestRequestTypeDef,
     _OptionalGetIntegrationResponsesRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredIntegrationResponseTypeDef = TypedDict(
     "_RequiredIntegrationResponseTypeDef",
     {
         "IntegrationResponseKey": str,
     },
 )
 _OptionalIntegrationResponseTypeDef = TypedDict(
@@ -791,19 +993,43 @@
         "ResponseParameters": Dict[str, str],
         "ResponseTemplates": Dict[str, str],
         "TemplateSelectionExpression": str,
     },
     total=False,
 )
 
+
 class IntegrationResponseTypeDef(
     _RequiredIntegrationResponseTypeDef, _OptionalIntegrationResponseTypeDef
 ):
     pass
 
+
+_RequiredGetIntegrationsRequestGetIntegrationsPaginateTypeDef = TypedDict(
+    "_RequiredGetIntegrationsRequestGetIntegrationsPaginateTypeDef",
+    {
+        "ApiId": str,
+    },
+)
+_OptionalGetIntegrationsRequestGetIntegrationsPaginateTypeDef = TypedDict(
+    "_OptionalGetIntegrationsRequestGetIntegrationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetIntegrationsRequestGetIntegrationsPaginateTypeDef(
+    _RequiredGetIntegrationsRequestGetIntegrationsPaginateTypeDef,
+    _OptionalGetIntegrationsRequestGetIntegrationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetIntegrationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetIntegrationsRequestRequestTypeDef",
     {
         "ApiId": str,
     },
 )
 _OptionalGetIntegrationsRequestRequestTypeDef = TypedDict(
@@ -811,35 +1037,79 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetIntegrationsRequestRequestTypeDef(
     _RequiredGetIntegrationsRequestRequestTypeDef, _OptionalGetIntegrationsRequestRequestTypeDef
 ):
     pass
 
+
 GetModelRequestRequestTypeDef = TypedDict(
     "GetModelRequestRequestTypeDef",
     {
         "ApiId": str,
         "ModelId": str,
     },
 )
 
+GetModelResponseTypeDef = TypedDict(
+    "GetModelResponseTypeDef",
+    {
+        "ContentType": str,
+        "Description": str,
+        "ModelId": str,
+        "Name": str,
+        "Schema": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetModelTemplateRequestRequestTypeDef = TypedDict(
     "GetModelTemplateRequestRequestTypeDef",
     {
         "ApiId": str,
         "ModelId": str,
     },
 )
 
+GetModelTemplateResponseTypeDef = TypedDict(
+    "GetModelTemplateResponseTypeDef",
+    {
+        "Value": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetModelsRequestGetModelsPaginateTypeDef = TypedDict(
+    "_RequiredGetModelsRequestGetModelsPaginateTypeDef",
+    {
+        "ApiId": str,
+    },
+)
+_OptionalGetModelsRequestGetModelsPaginateTypeDef = TypedDict(
+    "_OptionalGetModelsRequestGetModelsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetModelsRequestGetModelsPaginateTypeDef(
+    _RequiredGetModelsRequestGetModelsPaginateTypeDef,
+    _OptionalGetModelsRequestGetModelsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetModelsRequestRequestTypeDef = TypedDict(
     "_RequiredGetModelsRequestRequestTypeDef",
     {
         "ApiId": str,
     },
 )
 _OptionalGetModelsRequestRequestTypeDef = TypedDict(
@@ -847,19 +1117,21 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetModelsRequestRequestTypeDef(
     _RequiredGetModelsRequestRequestTypeDef, _OptionalGetModelsRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredModelTypeDef = TypedDict(
     "_RequiredModelTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalModelTypeDef = TypedDict(
@@ -869,17 +1141,19 @@
         "Description": str,
         "ModelId": str,
         "Schema": str,
     },
     total=False,
 )
 
+
 class ModelTypeDef(_RequiredModelTypeDef, _OptionalModelTypeDef):
     pass
 
+
 GetRouteRequestRequestTypeDef = TypedDict(
     "GetRouteRequestRequestTypeDef",
     {
         "ApiId": str,
         "RouteId": str,
     },
 )
@@ -889,14 +1163,37 @@
     {
         "ApiId": str,
         "RouteId": str,
         "RouteResponseId": str,
     },
 )
 
+_RequiredGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef = TypedDict(
+    "_RequiredGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef",
+    {
+        "ApiId": str,
+        "RouteId": str,
+    },
+)
+_OptionalGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef = TypedDict(
+    "_OptionalGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetRouteResponsesRequestGetRouteResponsesPaginateTypeDef(
+    _RequiredGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef,
+    _OptionalGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetRouteResponsesRequestRequestTypeDef = TypedDict(
     "_RequiredGetRouteResponsesRequestRequestTypeDef",
     {
         "ApiId": str,
         "RouteId": str,
     },
 )
@@ -905,19 +1202,43 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetRouteResponsesRequestRequestTypeDef(
     _RequiredGetRouteResponsesRequestRequestTypeDef, _OptionalGetRouteResponsesRequestRequestTypeDef
 ):
     pass
 
+
+_RequiredGetRoutesRequestGetRoutesPaginateTypeDef = TypedDict(
+    "_RequiredGetRoutesRequestGetRoutesPaginateTypeDef",
+    {
+        "ApiId": str,
+    },
+)
+_OptionalGetRoutesRequestGetRoutesPaginateTypeDef = TypedDict(
+    "_OptionalGetRoutesRequestGetRoutesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetRoutesRequestGetRoutesPaginateTypeDef(
+    _RequiredGetRoutesRequestGetRoutesPaginateTypeDef,
+    _OptionalGetRoutesRequestGetRoutesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetRoutesRequestRequestTypeDef = TypedDict(
     "_RequiredGetRoutesRequestRequestTypeDef",
     {
         "ApiId": str,
     },
 )
 _OptionalGetRoutesRequestRequestTypeDef = TypedDict(
@@ -925,27 +1246,51 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetRoutesRequestRequestTypeDef(
     _RequiredGetRoutesRequestRequestTypeDef, _OptionalGetRoutesRequestRequestTypeDef
 ):
     pass
 
+
 GetStageRequestRequestTypeDef = TypedDict(
     "GetStageRequestRequestTypeDef",
     {
         "ApiId": str,
         "StageName": str,
     },
 )
 
+_RequiredGetStagesRequestGetStagesPaginateTypeDef = TypedDict(
+    "_RequiredGetStagesRequestGetStagesPaginateTypeDef",
+    {
+        "ApiId": str,
+    },
+)
+_OptionalGetStagesRequestGetStagesPaginateTypeDef = TypedDict(
+    "_OptionalGetStagesRequestGetStagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetStagesRequestGetStagesPaginateTypeDef(
+    _RequiredGetStagesRequestGetStagesPaginateTypeDef,
+    _OptionalGetStagesRequestGetStagesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetStagesRequestRequestTypeDef = TypedDict(
     "_RequiredGetStagesRequestRequestTypeDef",
     {
         "ApiId": str,
     },
 )
 _OptionalGetStagesRequestRequestTypeDef = TypedDict(
@@ -953,33 +1298,59 @@
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetStagesRequestRequestTypeDef(
     _RequiredGetStagesRequestRequestTypeDef, _OptionalGetStagesRequestRequestTypeDef
 ):
     pass
 
+
 GetTagsRequestRequestTypeDef = TypedDict(
     "GetTagsRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+GetTagsResponseTypeDef = TypedDict(
+    "GetTagsResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetVpcLinkRequestRequestTypeDef = TypedDict(
     "GetVpcLinkRequestRequestTypeDef",
     {
         "VpcLinkId": str,
     },
 )
 
+GetVpcLinkResponseTypeDef = TypedDict(
+    "GetVpcLinkResponseTypeDef",
+    {
+        "CreatedDate": datetime,
+        "Name": str,
+        "SecurityGroupIds": List[str],
+        "SubnetIds": List[str],
+        "Tags": Dict[str, str],
+        "VpcLinkId": str,
+        "VpcLinkStatus": VpcLinkStatusType,
+        "VpcLinkStatusMessage": str,
+        "VpcLinkVersion": Literal["V2"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetVpcLinksRequestRequestTypeDef = TypedDict(
     "GetVpcLinksRequestRequestTypeDef",
     {
         "MaxResults": str,
         "NextToken": str,
     },
     total=False,
@@ -1002,17 +1373,19 @@
         "VpcLinkStatus": VpcLinkStatusType,
         "VpcLinkStatusMessage": str,
         "VpcLinkVersion": Literal["V2"],
     },
     total=False,
 )
 
+
 class VpcLinkTypeDef(_RequiredVpcLinkTypeDef, _OptionalVpcLinkTypeDef):
     pass
 
+
 _RequiredImportApiRequestRequestTypeDef = TypedDict(
     "_RequiredImportApiRequestRequestTypeDef",
     {
         "Body": str,
     },
 )
 _OptionalImportApiRequestRequestTypeDef = TypedDict(
@@ -1020,19 +1393,31 @@
     {
         "Basepath": str,
         "FailOnWarnings": bool,
     },
     total=False,
 )
 
+
 class ImportApiRequestRequestTypeDef(
     _RequiredImportApiRequestRequestTypeDef, _OptionalImportApiRequestRequestTypeDef
 ):
     pass
 
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
 _RequiredReimportApiRequestRequestTypeDef = TypedDict(
     "_RequiredReimportApiRequestRequestTypeDef",
     {
         "ApiId": str,
         "Body": str,
     },
 )
@@ -1041,46 +1426,61 @@
     {
         "Basepath": str,
         "FailOnWarnings": bool,
     },
     total=False,
 )
 
+
 class ReimportApiRequestRequestTypeDef(
     _RequiredReimportApiRequestRequestTypeDef, _OptionalReimportApiRequestRequestTypeDef
 ):
     pass
 
+
 ResetAuthorizersCacheRequestRequestTypeDef = TypedDict(
     "ResetAuthorizersCacheRequestRequestTypeDef",
     {
         "ApiId": str,
         "StageName": str,
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
 _RequiredTagResourceRequestRequestTypeDef = TypedDict(
     "_RequiredTagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalTagResourceRequestRequestTypeDef = TypedDict(
     "_OptionalTagResourceRequestRequestTypeDef",
     {
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class TagResourceRequestRequestTypeDef(
     _RequiredTagResourceRequestRequestTypeDef, _OptionalTagResourceRequestRequestTypeDef
 ):
     pass
 
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -1098,19 +1498,32 @@
     {
         "ApiMappingKey": str,
         "Stage": str,
     },
     total=False,
 )
 
+
 class UpdateApiMappingRequestRequestTypeDef(
     _RequiredUpdateApiMappingRequestRequestTypeDef, _OptionalUpdateApiMappingRequestRequestTypeDef
 ):
     pass
 
+
+UpdateApiMappingResponseTypeDef = TypedDict(
+    "UpdateApiMappingResponseTypeDef",
+    {
+        "ApiId": str,
+        "ApiMappingId": str,
+        "ApiMappingKey": str,
+        "Stage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDeploymentRequestRequestTypeDef",
     {
         "ApiId": str,
         "DeploymentId": str,
     },
 )
@@ -1118,19 +1531,34 @@
     "_OptionalUpdateDeploymentRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
+
 class UpdateDeploymentRequestRequestTypeDef(
     _RequiredUpdateDeploymentRequestRequestTypeDef, _OptionalUpdateDeploymentRequestRequestTypeDef
 ):
     pass
 
+
+UpdateDeploymentResponseTypeDef = TypedDict(
+    "UpdateDeploymentResponseTypeDef",
+    {
+        "AutoDeployed": bool,
+        "CreatedDate": datetime,
+        "DeploymentId": str,
+        "DeploymentStatus": DeploymentStatusType,
+        "DeploymentStatusMessage": str,
+        "Description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateIntegrationResponseRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateIntegrationResponseRequestRequestTypeDef",
     {
         "ApiId": str,
         "IntegrationId": str,
         "IntegrationResponseId": str,
     },
@@ -1143,20 +1571,35 @@
         "ResponseParameters": Mapping[str, str],
         "ResponseTemplates": Mapping[str, str],
         "TemplateSelectionExpression": str,
     },
     total=False,
 )
 
+
 class UpdateIntegrationResponseRequestRequestTypeDef(
     _RequiredUpdateIntegrationResponseRequestRequestTypeDef,
     _OptionalUpdateIntegrationResponseRequestRequestTypeDef,
 ):
     pass
 
+
+UpdateIntegrationResponseResponseTypeDef = TypedDict(
+    "UpdateIntegrationResponseResponseTypeDef",
+    {
+        "ContentHandlingStrategy": ContentHandlingStrategyType,
+        "IntegrationResponseId": str,
+        "IntegrationResponseKey": str,
+        "ResponseParameters": Dict[str, str],
+        "ResponseTemplates": Dict[str, str],
+        "TemplateSelectionExpression": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateModelRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateModelRequestRequestTypeDef",
     {
         "ApiId": str,
         "ModelId": str,
     },
 )
@@ -1167,38 +1610,79 @@
         "Description": str,
         "Name": str,
         "Schema": str,
     },
     total=False,
 )
 
+
 class UpdateModelRequestRequestTypeDef(
     _RequiredUpdateModelRequestRequestTypeDef, _OptionalUpdateModelRequestRequestTypeDef
 ):
     pass
 
+
+UpdateModelResponseTypeDef = TypedDict(
+    "UpdateModelResponseTypeDef",
+    {
+        "ContentType": str,
+        "Description": str,
+        "ModelId": str,
+        "Name": str,
+        "Schema": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateVpcLinkRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateVpcLinkRequestRequestTypeDef",
     {
         "VpcLinkId": str,
     },
 )
 _OptionalUpdateVpcLinkRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateVpcLinkRequestRequestTypeDef",
     {
         "Name": str,
     },
     total=False,
 )
 
+
 class UpdateVpcLinkRequestRequestTypeDef(
     _RequiredUpdateVpcLinkRequestRequestTypeDef, _OptionalUpdateVpcLinkRequestRequestTypeDef
 ):
     pass
 
+
+UpdateVpcLinkResponseTypeDef = TypedDict(
+    "UpdateVpcLinkResponseTypeDef",
+    {
+        "CreatedDate": datetime,
+        "Name": str,
+        "SecurityGroupIds": List[str],
+        "SubnetIds": List[str],
+        "Tags": Dict[str, str],
+        "VpcLinkId": str,
+        "VpcLinkStatus": VpcLinkStatusType,
+        "VpcLinkStatusMessage": str,
+        "VpcLinkVersion": Literal["V2"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetApiMappingsResponseTypeDef = TypedDict(
+    "GetApiMappingsResponseTypeDef",
+    {
+        "Items": List[ApiMappingTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredApiTypeDef = TypedDict(
     "_RequiredApiTypeDef",
     {
         "Name": str,
         "ProtocolType": ProtocolTypeType,
         "RouteSelectionExpression": str,
     },
@@ -1219,17 +1703,19 @@
         "Tags": Dict[str, str],
         "Version": str,
         "Warnings": List[str],
     },
     total=False,
 )
 
+
 class ApiTypeDef(_RequiredApiTypeDef, _OptionalApiTypeDef):
     pass
 
+
 _RequiredCreateApiRequestRequestTypeDef = TypedDict(
     "_RequiredCreateApiRequestRequestTypeDef",
     {
         "Name": str,
         "ProtocolType": ProtocolTypeType,
     },
 )
@@ -1247,141 +1733,20 @@
         "Tags": Mapping[str, str],
         "Target": str,
         "Version": str,
     },
     total=False,
 )
 
+
 class CreateApiRequestRequestTypeDef(
     _RequiredCreateApiRequestRequestTypeDef, _OptionalCreateApiRequestRequestTypeDef
 ):
     pass
 
-_RequiredUpdateApiRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateApiRequestRequestTypeDef",
-    {
-        "ApiId": str,
-    },
-)
-_OptionalUpdateApiRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateApiRequestRequestTypeDef",
-    {
-        "ApiKeySelectionExpression": str,
-        "CorsConfiguration": CorsTypeDef,
-        "CredentialsArn": str,
-        "Description": str,
-        "DisableSchemaValidation": bool,
-        "DisableExecuteApiEndpoint": bool,
-        "Name": str,
-        "RouteKey": str,
-        "RouteSelectionExpression": str,
-        "Target": str,
-        "Version": str,
-    },
-    total=False,
-)
-
-class UpdateApiRequestRequestTypeDef(
-    _RequiredUpdateApiRequestRequestTypeDef, _OptionalUpdateApiRequestRequestTypeDef
-):
-    pass
-
-_RequiredAuthorizerTypeDef = TypedDict(
-    "_RequiredAuthorizerTypeDef",
-    {
-        "Name": str,
-    },
-)
-_OptionalAuthorizerTypeDef = TypedDict(
-    "_OptionalAuthorizerTypeDef",
-    {
-        "AuthorizerCredentialsArn": str,
-        "AuthorizerId": str,
-        "AuthorizerPayloadFormatVersion": str,
-        "AuthorizerResultTtlInSeconds": int,
-        "AuthorizerType": AuthorizerTypeType,
-        "AuthorizerUri": str,
-        "EnableSimpleResponses": bool,
-        "IdentitySource": List[str],
-        "IdentityValidationExpression": str,
-        "JwtConfiguration": JWTConfigurationTypeDef,
-    },
-    total=False,
-)
-
-class AuthorizerTypeDef(_RequiredAuthorizerTypeDef, _OptionalAuthorizerTypeDef):
-    pass
-
-_RequiredCreateAuthorizerRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateAuthorizerRequestRequestTypeDef",
-    {
-        "ApiId": str,
-        "AuthorizerType": AuthorizerTypeType,
-        "IdentitySource": Sequence[str],
-        "Name": str,
-    },
-)
-_OptionalCreateAuthorizerRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateAuthorizerRequestRequestTypeDef",
-    {
-        "AuthorizerCredentialsArn": str,
-        "AuthorizerPayloadFormatVersion": str,
-        "AuthorizerResultTtlInSeconds": int,
-        "AuthorizerUri": str,
-        "EnableSimpleResponses": bool,
-        "IdentityValidationExpression": str,
-        "JwtConfiguration": JWTConfigurationTypeDef,
-    },
-    total=False,
-)
-
-class CreateAuthorizerRequestRequestTypeDef(
-    _RequiredCreateAuthorizerRequestRequestTypeDef, _OptionalCreateAuthorizerRequestRequestTypeDef
-):
-    pass
-
-_RequiredUpdateAuthorizerRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateAuthorizerRequestRequestTypeDef",
-    {
-        "ApiId": str,
-        "AuthorizerId": str,
-    },
-)
-_OptionalUpdateAuthorizerRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateAuthorizerRequestRequestTypeDef",
-    {
-        "AuthorizerCredentialsArn": str,
-        "AuthorizerPayloadFormatVersion": str,
-        "AuthorizerResultTtlInSeconds": int,
-        "AuthorizerType": AuthorizerTypeType,
-        "AuthorizerUri": str,
-        "EnableSimpleResponses": bool,
-        "IdentitySource": Sequence[str],
-        "IdentityValidationExpression": str,
-        "JwtConfiguration": JWTConfigurationTypeDef,
-        "Name": str,
-    },
-    total=False,
-)
-
-class UpdateAuthorizerRequestRequestTypeDef(
-    _RequiredUpdateAuthorizerRequestRequestTypeDef, _OptionalUpdateAuthorizerRequestRequestTypeDef
-):
-    pass
-
-CreateApiMappingResponseTypeDef = TypedDict(
-    "CreateApiMappingResponseTypeDef",
-    {
-        "ApiId": str,
-        "ApiMappingId": str,
-        "ApiMappingKey": str,
-        "Stage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 CreateApiResponseTypeDef = TypedDict(
     "CreateApiResponseTypeDef",
     {
         "ApiEndpoint": str,
         "ApiGatewayManaged": bool,
         "ApiId": str,
@@ -1394,122 +1759,15 @@
         "ImportInfo": List[str],
         "Name": str,
         "ProtocolType": ProtocolTypeType,
         "RouteSelectionExpression": str,
         "Tags": Dict[str, str],
         "Version": str,
         "Warnings": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAuthorizerResponseTypeDef = TypedDict(
-    "CreateAuthorizerResponseTypeDef",
-    {
-        "AuthorizerCredentialsArn": str,
-        "AuthorizerId": str,
-        "AuthorizerPayloadFormatVersion": str,
-        "AuthorizerResultTtlInSeconds": int,
-        "AuthorizerType": AuthorizerTypeType,
-        "AuthorizerUri": str,
-        "EnableSimpleResponses": bool,
-        "IdentitySource": List[str],
-        "IdentityValidationExpression": str,
-        "JwtConfiguration": JWTConfigurationTypeDef,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeploymentResponseTypeDef = TypedDict(
-    "CreateDeploymentResponseTypeDef",
-    {
-        "AutoDeployed": bool,
-        "CreatedDate": datetime,
-        "DeploymentId": str,
-        "DeploymentStatus": DeploymentStatusType,
-        "DeploymentStatusMessage": str,
-        "Description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateIntegrationResponseResponseTypeDef = TypedDict(
-    "CreateIntegrationResponseResponseTypeDef",
-    {
-        "ContentHandlingStrategy": ContentHandlingStrategyType,
-        "IntegrationResponseId": str,
-        "IntegrationResponseKey": str,
-        "ResponseParameters": Dict[str, str],
-        "ResponseTemplates": Dict[str, str],
-        "TemplateSelectionExpression": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateModelResponseTypeDef = TypedDict(
-    "CreateModelResponseTypeDef",
-    {
-        "ContentType": str,
-        "Description": str,
-        "ModelId": str,
-        "Name": str,
-        "Schema": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateVpcLinkResponseTypeDef = TypedDict(
-    "CreateVpcLinkResponseTypeDef",
-    {
-        "CreatedDate": datetime,
-        "Name": str,
-        "SecurityGroupIds": List[str],
-        "SubnetIds": List[str],
-        "Tags": Dict[str, str],
-        "VpcLinkId": str,
-        "VpcLinkStatus": VpcLinkStatusType,
-        "VpcLinkStatusMessage": str,
-        "VpcLinkVersion": Literal["V2"],
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
-ExportApiResponseTypeDef = TypedDict(
-    "ExportApiResponseTypeDef",
-    {
-        "body": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetApiMappingResponseTypeDef = TypedDict(
-    "GetApiMappingResponseTypeDef",
-    {
-        "ApiId": str,
-        "ApiMappingId": str,
-        "ApiMappingKey": str,
-        "Stage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetApiMappingsResponseTypeDef = TypedDict(
-    "GetApiMappingsResponseTypeDef",
-    {
-        "Items": List[ApiMappingTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetApiResponseTypeDef = TypedDict(
     "GetApiResponseTypeDef",
     {
         "ApiEndpoint": str,
@@ -1524,103 +1782,15 @@
         "ImportInfo": List[str],
         "Name": str,
         "ProtocolType": ProtocolTypeType,
         "RouteSelectionExpression": str,
         "Tags": Dict[str, str],
         "Version": str,
         "Warnings": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAuthorizerResponseTypeDef = TypedDict(
-    "GetAuthorizerResponseTypeDef",
-    {
-        "AuthorizerCredentialsArn": str,
-        "AuthorizerId": str,
-        "AuthorizerPayloadFormatVersion": str,
-        "AuthorizerResultTtlInSeconds": int,
-        "AuthorizerType": AuthorizerTypeType,
-        "AuthorizerUri": str,
-        "EnableSimpleResponses": bool,
-        "IdentitySource": List[str],
-        "IdentityValidationExpression": str,
-        "JwtConfiguration": JWTConfigurationTypeDef,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDeploymentResponseTypeDef = TypedDict(
-    "GetDeploymentResponseTypeDef",
-    {
-        "AutoDeployed": bool,
-        "CreatedDate": datetime,
-        "DeploymentId": str,
-        "DeploymentStatus": DeploymentStatusType,
-        "DeploymentStatusMessage": str,
-        "Description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetIntegrationResponseResponseTypeDef = TypedDict(
-    "GetIntegrationResponseResponseTypeDef",
-    {
-        "ContentHandlingStrategy": ContentHandlingStrategyType,
-        "IntegrationResponseId": str,
-        "IntegrationResponseKey": str,
-        "ResponseParameters": Dict[str, str],
-        "ResponseTemplates": Dict[str, str],
-        "TemplateSelectionExpression": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetModelResponseTypeDef = TypedDict(
-    "GetModelResponseTypeDef",
-    {
-        "ContentType": str,
-        "Description": str,
-        "ModelId": str,
-        "Name": str,
-        "Schema": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetModelTemplateResponseTypeDef = TypedDict(
-    "GetModelTemplateResponseTypeDef",
-    {
-        "Value": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTagsResponseTypeDef = TypedDict(
-    "GetTagsResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetVpcLinkResponseTypeDef = TypedDict(
-    "GetVpcLinkResponseTypeDef",
-    {
-        "CreatedDate": datetime,
-        "Name": str,
-        "SecurityGroupIds": List[str],
-        "SubnetIds": List[str],
-        "Tags": Dict[str, str],
-        "VpcLinkId": str,
-        "VpcLinkStatus": VpcLinkStatusType,
-        "VpcLinkStatusMessage": str,
-        "VpcLinkVersion": Literal["V2"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportApiResponseTypeDef = TypedDict(
     "ImportApiResponseTypeDef",
     {
         "ApiEndpoint": str,
@@ -1635,15 +1805,15 @@
         "ImportInfo": List[str],
         "Name": str,
         "ProtocolType": ProtocolTypeType,
         "RouteSelectionExpression": str,
         "Tags": Dict[str, str],
         "Version": str,
         "Warnings": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReimportApiResponseTypeDef = TypedDict(
     "ReimportApiResponseTypeDef",
     {
         "ApiEndpoint": str,
@@ -1658,28 +1828,48 @@
         "ImportInfo": List[str],
         "Name": str,
         "ProtocolType": ProtocolTypeType,
         "RouteSelectionExpression": str,
         "Tags": Dict[str, str],
         "Version": str,
         "Warnings": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateApiMappingResponseTypeDef = TypedDict(
-    "UpdateApiMappingResponseTypeDef",
+_RequiredUpdateApiRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateApiRequestRequestTypeDef",
     {
         "ApiId": str,
-        "ApiMappingId": str,
-        "ApiMappingKey": str,
-        "Stage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
+_OptionalUpdateApiRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateApiRequestRequestTypeDef",
+    {
+        "ApiKeySelectionExpression": str,
+        "CorsConfiguration": CorsTypeDef,
+        "CredentialsArn": str,
+        "Description": str,
+        "DisableSchemaValidation": bool,
+        "DisableExecuteApiEndpoint": bool,
+        "Name": str,
+        "RouteKey": str,
+        "RouteSelectionExpression": str,
+        "Target": str,
+        "Version": str,
+    },
+    total=False,
+)
+
+
+class UpdateApiRequestRequestTypeDef(
+    _RequiredUpdateApiRequestRequestTypeDef, _OptionalUpdateApiRequestRequestTypeDef
+):
+    pass
+
 
 UpdateApiResponseTypeDef = TypedDict(
     "UpdateApiResponseTypeDef",
     {
         "ApiEndpoint": str,
         "ApiGatewayManaged": bool,
         "ApiId": str,
@@ -1692,87 +1882,158 @@
         "ImportInfo": List[str],
         "Name": str,
         "ProtocolType": ProtocolTypeType,
         "RouteSelectionExpression": str,
         "Tags": Dict[str, str],
         "Version": str,
         "Warnings": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateAuthorizerResponseTypeDef = TypedDict(
-    "UpdateAuthorizerResponseTypeDef",
+_RequiredAuthorizerTypeDef = TypedDict(
+    "_RequiredAuthorizerTypeDef",
+    {
+        "Name": str,
+    },
+)
+_OptionalAuthorizerTypeDef = TypedDict(
+    "_OptionalAuthorizerTypeDef",
     {
         "AuthorizerCredentialsArn": str,
         "AuthorizerId": str,
         "AuthorizerPayloadFormatVersion": str,
         "AuthorizerResultTtlInSeconds": int,
         "AuthorizerType": AuthorizerTypeType,
         "AuthorizerUri": str,
         "EnableSimpleResponses": bool,
         "IdentitySource": List[str],
         "IdentityValidationExpression": str,
         "JwtConfiguration": JWTConfigurationTypeDef,
+    },
+    total=False,
+)
+
+
+class AuthorizerTypeDef(_RequiredAuthorizerTypeDef, _OptionalAuthorizerTypeDef):
+    pass
+
+
+_RequiredCreateAuthorizerRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateAuthorizerRequestRequestTypeDef",
+    {
+        "ApiId": str,
+        "AuthorizerType": AuthorizerTypeType,
+        "IdentitySource": Sequence[str],
         "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
+_OptionalCreateAuthorizerRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateAuthorizerRequestRequestTypeDef",
+    {
+        "AuthorizerCredentialsArn": str,
+        "AuthorizerPayloadFormatVersion": str,
+        "AuthorizerResultTtlInSeconds": int,
+        "AuthorizerUri": str,
+        "EnableSimpleResponses": bool,
+        "IdentityValidationExpression": str,
+        "JwtConfiguration": JWTConfigurationTypeDef,
+    },
+    total=False,
+)
 
-UpdateDeploymentResponseTypeDef = TypedDict(
-    "UpdateDeploymentResponseTypeDef",
+
+class CreateAuthorizerRequestRequestTypeDef(
+    _RequiredCreateAuthorizerRequestRequestTypeDef, _OptionalCreateAuthorizerRequestRequestTypeDef
+):
+    pass
+
+
+CreateAuthorizerResponseTypeDef = TypedDict(
+    "CreateAuthorizerResponseTypeDef",
     {
-        "AutoDeployed": bool,
-        "CreatedDate": datetime,
-        "DeploymentId": str,
-        "DeploymentStatus": DeploymentStatusType,
-        "DeploymentStatusMessage": str,
-        "Description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AuthorizerCredentialsArn": str,
+        "AuthorizerId": str,
+        "AuthorizerPayloadFormatVersion": str,
+        "AuthorizerResultTtlInSeconds": int,
+        "AuthorizerType": AuthorizerTypeType,
+        "AuthorizerUri": str,
+        "EnableSimpleResponses": bool,
+        "IdentitySource": List[str],
+        "IdentityValidationExpression": str,
+        "JwtConfiguration": JWTConfigurationTypeDef,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateIntegrationResponseResponseTypeDef = TypedDict(
-    "UpdateIntegrationResponseResponseTypeDef",
+GetAuthorizerResponseTypeDef = TypedDict(
+    "GetAuthorizerResponseTypeDef",
     {
-        "ContentHandlingStrategy": ContentHandlingStrategyType,
-        "IntegrationResponseId": str,
-        "IntegrationResponseKey": str,
-        "ResponseParameters": Dict[str, str],
-        "ResponseTemplates": Dict[str, str],
-        "TemplateSelectionExpression": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AuthorizerCredentialsArn": str,
+        "AuthorizerId": str,
+        "AuthorizerPayloadFormatVersion": str,
+        "AuthorizerResultTtlInSeconds": int,
+        "AuthorizerType": AuthorizerTypeType,
+        "AuthorizerUri": str,
+        "EnableSimpleResponses": bool,
+        "IdentitySource": List[str],
+        "IdentityValidationExpression": str,
+        "JwtConfiguration": JWTConfigurationTypeDef,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateModelResponseTypeDef = TypedDict(
-    "UpdateModelResponseTypeDef",
+_RequiredUpdateAuthorizerRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateAuthorizerRequestRequestTypeDef",
     {
-        "ContentType": str,
-        "Description": str,
-        "ModelId": str,
+        "ApiId": str,
+        "AuthorizerId": str,
+    },
+)
+_OptionalUpdateAuthorizerRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateAuthorizerRequestRequestTypeDef",
+    {
+        "AuthorizerCredentialsArn": str,
+        "AuthorizerPayloadFormatVersion": str,
+        "AuthorizerResultTtlInSeconds": int,
+        "AuthorizerType": AuthorizerTypeType,
+        "AuthorizerUri": str,
+        "EnableSimpleResponses": bool,
+        "IdentitySource": Sequence[str],
+        "IdentityValidationExpression": str,
+        "JwtConfiguration": JWTConfigurationTypeDef,
         "Name": str,
-        "Schema": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-UpdateVpcLinkResponseTypeDef = TypedDict(
-    "UpdateVpcLinkResponseTypeDef",
+
+class UpdateAuthorizerRequestRequestTypeDef(
+    _RequiredUpdateAuthorizerRequestRequestTypeDef, _OptionalUpdateAuthorizerRequestRequestTypeDef
+):
+    pass
+
+
+UpdateAuthorizerResponseTypeDef = TypedDict(
+    "UpdateAuthorizerResponseTypeDef",
     {
-        "CreatedDate": datetime,
+        "AuthorizerCredentialsArn": str,
+        "AuthorizerId": str,
+        "AuthorizerPayloadFormatVersion": str,
+        "AuthorizerResultTtlInSeconds": int,
+        "AuthorizerType": AuthorizerTypeType,
+        "AuthorizerUri": str,
+        "EnableSimpleResponses": bool,
+        "IdentitySource": List[str],
+        "IdentityValidationExpression": str,
+        "JwtConfiguration": JWTConfigurationTypeDef,
         "Name": str,
-        "SecurityGroupIds": List[str],
-        "SubnetIds": List[str],
-        "Tags": Dict[str, str],
-        "VpcLinkId": str,
-        "VpcLinkStatus": VpcLinkStatusType,
-        "VpcLinkStatusMessage": str,
-        "VpcLinkVersion": Literal["V2"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDomainNameRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDomainNameRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -1784,19 +2045,21 @@
         "DomainNameConfigurations": Sequence[DomainNameConfigurationTypeDef],
         "MutualTlsAuthentication": MutualTlsAuthenticationInputTypeDef,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateDomainNameRequestRequestTypeDef(
     _RequiredCreateDomainNameRequestRequestTypeDef, _OptionalCreateDomainNameRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateDomainNameRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDomainNameRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalUpdateDomainNameRequestRequestTypeDef = TypedDict(
@@ -1804,28 +2067,30 @@
     {
         "DomainNameConfigurations": Sequence[DomainNameConfigurationTypeDef],
         "MutualTlsAuthentication": MutualTlsAuthenticationInputTypeDef,
     },
     total=False,
 )
 
+
 class UpdateDomainNameRequestRequestTypeDef(
     _RequiredUpdateDomainNameRequestRequestTypeDef, _OptionalUpdateDomainNameRequestRequestTypeDef
 ):
     pass
 
+
 CreateDomainNameResponseTypeDef = TypedDict(
     "CreateDomainNameResponseTypeDef",
     {
         "ApiMappingSelectionExpression": str,
         "DomainName": str,
         "DomainNameConfigurations": List[DomainNameConfigurationTypeDef],
         "MutualTlsAuthentication": MutualTlsAuthenticationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDomainNameTypeDef = TypedDict(
     "_RequiredDomainNameTypeDef",
     {
         "DomainName": str,
@@ -1838,38 +2103,40 @@
         "DomainNameConfigurations": List[DomainNameConfigurationTypeDef],
         "MutualTlsAuthentication": MutualTlsAuthenticationTypeDef,
         "Tags": Dict[str, str],
     },
     total=False,
 )
 
+
 class DomainNameTypeDef(_RequiredDomainNameTypeDef, _OptionalDomainNameTypeDef):
     pass
 
+
 GetDomainNameResponseTypeDef = TypedDict(
     "GetDomainNameResponseTypeDef",
     {
         "ApiMappingSelectionExpression": str,
         "DomainName": str,
         "DomainNameConfigurations": List[DomainNameConfigurationTypeDef],
         "MutualTlsAuthentication": MutualTlsAuthenticationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDomainNameResponseTypeDef = TypedDict(
     "UpdateDomainNameResponseTypeDef",
     {
         "ApiMappingSelectionExpression": str,
         "DomainName": str,
         "DomainNameConfigurations": List[DomainNameConfigurationTypeDef],
         "MutualTlsAuthentication": MutualTlsAuthenticationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateIntegrationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateIntegrationRequestRequestTypeDef",
     {
         "ApiId": str,
@@ -1895,19 +2162,21 @@
         "TemplateSelectionExpression": str,
         "TimeoutInMillis": int,
         "TlsConfig": TlsConfigInputTypeDef,
     },
     total=False,
 )
 
+
 class CreateIntegrationRequestRequestTypeDef(
     _RequiredCreateIntegrationRequestRequestTypeDef, _OptionalCreateIntegrationRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateIntegrationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateIntegrationRequestRequestTypeDef",
     {
         "ApiId": str,
         "IntegrationId": str,
     },
 )
@@ -1931,19 +2200,21 @@
         "TemplateSelectionExpression": str,
         "TimeoutInMillis": int,
         "TlsConfig": TlsConfigInputTypeDef,
     },
     total=False,
 )
 
+
 class UpdateIntegrationRequestRequestTypeDef(
     _RequiredUpdateIntegrationRequestRequestTypeDef, _OptionalUpdateIntegrationRequestRequestTypeDef
 ):
     pass
 
+
 CreateIntegrationResultTypeDef = TypedDict(
     "CreateIntegrationResultTypeDef",
     {
         "ApiGatewayManaged": bool,
         "ConnectionId": str,
         "ConnectionType": ConnectionTypeType,
         "ContentHandlingStrategy": ContentHandlingStrategyType,
@@ -1959,15 +2230,15 @@
         "PayloadFormatVersion": str,
         "RequestParameters": Dict[str, str],
         "RequestTemplates": Dict[str, str],
         "ResponseParameters": Dict[str, Dict[str, str]],
         "TemplateSelectionExpression": str,
         "TimeoutInMillis": int,
         "TlsConfig": TlsConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIntegrationResultTypeDef = TypedDict(
     "GetIntegrationResultTypeDef",
     {
         "ApiGatewayManaged": bool,
@@ -1986,15 +2257,15 @@
         "PayloadFormatVersion": str,
         "RequestParameters": Dict[str, str],
         "RequestTemplates": Dict[str, str],
         "ResponseParameters": Dict[str, Dict[str, str]],
         "TemplateSelectionExpression": str,
         "TimeoutInMillis": int,
         "TlsConfig": TlsConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IntegrationTypeDef = TypedDict(
     "IntegrationTypeDef",
     {
         "ApiGatewayManaged": bool,
@@ -2040,15 +2311,15 @@
         "PayloadFormatVersion": str,
         "RequestParameters": Dict[str, str],
         "RequestTemplates": Dict[str, str],
         "ResponseParameters": Dict[str, Dict[str, str]],
         "TemplateSelectionExpression": str,
         "TimeoutInMillis": int,
         "TlsConfig": TlsConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateRouteRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRouteRequestRequestTypeDef",
     {
         "ApiId": str,
@@ -2068,19 +2339,21 @@
         "RequestParameters": Mapping[str, ParameterConstraintsTypeDef],
         "RouteResponseSelectionExpression": str,
         "Target": str,
     },
     total=False,
 )
 
+
 class CreateRouteRequestRequestTypeDef(
     _RequiredCreateRouteRequestRequestTypeDef, _OptionalCreateRouteRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateRouteResponseRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRouteResponseRequestRequestTypeDef",
     {
         "ApiId": str,
         "RouteId": str,
         "RouteResponseKey": str,
     },
@@ -2091,29 +2364,31 @@
         "ModelSelectionExpression": str,
         "ResponseModels": Mapping[str, str],
         "ResponseParameters": Mapping[str, ParameterConstraintsTypeDef],
     },
     total=False,
 )
 
+
 class CreateRouteResponseRequestRequestTypeDef(
     _RequiredCreateRouteResponseRequestRequestTypeDef,
     _OptionalCreateRouteResponseRequestRequestTypeDef,
 ):
     pass
 
+
 CreateRouteResponseResponseTypeDef = TypedDict(
     "CreateRouteResponseResponseTypeDef",
     {
         "ModelSelectionExpression": str,
         "ResponseModels": Dict[str, str],
         "ResponseParameters": Dict[str, ParameterConstraintsTypeDef],
         "RouteResponseId": str,
         "RouteResponseKey": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRouteResultTypeDef = TypedDict(
     "CreateRouteResultTypeDef",
     {
         "ApiGatewayManaged": bool,
@@ -2125,27 +2400,27 @@
         "OperationName": str,
         "RequestModels": Dict[str, str],
         "RequestParameters": Dict[str, ParameterConstraintsTypeDef],
         "RouteId": str,
         "RouteKey": str,
         "RouteResponseSelectionExpression": str,
         "Target": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRouteResponseResponseTypeDef = TypedDict(
     "GetRouteResponseResponseTypeDef",
     {
         "ModelSelectionExpression": str,
         "ResponseModels": Dict[str, str],
         "ResponseParameters": Dict[str, ParameterConstraintsTypeDef],
         "RouteResponseId": str,
         "RouteResponseKey": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRouteResultTypeDef = TypedDict(
     "GetRouteResultTypeDef",
     {
         "ApiGatewayManaged": bool,
@@ -2157,15 +2432,15 @@
         "OperationName": str,
         "RequestModels": Dict[str, str],
         "RequestParameters": Dict[str, ParameterConstraintsTypeDef],
         "RouteId": str,
         "RouteKey": str,
         "RouteResponseSelectionExpression": str,
         "Target": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRouteResponseTypeDef = TypedDict(
     "_RequiredRouteResponseTypeDef",
     {
         "RouteResponseKey": str,
@@ -2178,17 +2453,19 @@
         "ResponseModels": Dict[str, str],
         "ResponseParameters": Dict[str, ParameterConstraintsTypeDef],
         "RouteResponseId": str,
     },
     total=False,
 )
 
+
 class RouteResponseTypeDef(_RequiredRouteResponseTypeDef, _OptionalRouteResponseTypeDef):
     pass
 
+
 _RequiredRouteTypeDef = TypedDict(
     "_RequiredRouteTypeDef",
     {
         "RouteKey": str,
     },
 )
 _OptionalRouteTypeDef = TypedDict(
@@ -2206,17 +2483,19 @@
         "RouteId": str,
         "RouteResponseSelectionExpression": str,
         "Target": str,
     },
     total=False,
 )
 
+
 class RouteTypeDef(_RequiredRouteTypeDef, _OptionalRouteTypeDef):
     pass
 
+
 _RequiredUpdateRouteRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRouteRequestRequestTypeDef",
     {
         "ApiId": str,
         "RouteId": str,
     },
 )
@@ -2234,19 +2513,21 @@
         "RouteKey": str,
         "RouteResponseSelectionExpression": str,
         "Target": str,
     },
     total=False,
 )
 
+
 class UpdateRouteRequestRequestTypeDef(
     _RequiredUpdateRouteRequestRequestTypeDef, _OptionalUpdateRouteRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateRouteResponseRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRouteResponseRequestRequestTypeDef",
     {
         "ApiId": str,
         "RouteId": str,
         "RouteResponseId": str,
     },
@@ -2258,29 +2539,31 @@
         "ResponseModels": Mapping[str, str],
         "ResponseParameters": Mapping[str, ParameterConstraintsTypeDef],
         "RouteResponseKey": str,
     },
     total=False,
 )
 
+
 class UpdateRouteResponseRequestRequestTypeDef(
     _RequiredUpdateRouteResponseRequestRequestTypeDef,
     _OptionalUpdateRouteResponseRequestRequestTypeDef,
 ):
     pass
 
+
 UpdateRouteResponseResponseTypeDef = TypedDict(
     "UpdateRouteResponseResponseTypeDef",
     {
         "ModelSelectionExpression": str,
         "ResponseModels": Dict[str, str],
         "ResponseParameters": Dict[str, ParameterConstraintsTypeDef],
         "RouteResponseId": str,
         "RouteResponseKey": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRouteResultTypeDef = TypedDict(
     "UpdateRouteResultTypeDef",
     {
         "ApiGatewayManaged": bool,
@@ -2292,15 +2575,15 @@
         "OperationName": str,
         "RequestModels": Dict[str, str],
         "RequestParameters": Dict[str, ParameterConstraintsTypeDef],
         "RouteId": str,
         "RouteKey": str,
         "RouteResponseSelectionExpression": str,
         "Target": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateStageRequestRequestTypeDef = TypedDict(
     "_RequiredCreateStageRequestRequestTypeDef",
     {
         "ApiId": str,
@@ -2319,19 +2602,21 @@
         "RouteSettings": Mapping[str, RouteSettingsTypeDef],
         "StageVariables": Mapping[str, str],
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateStageRequestRequestTypeDef(
     _RequiredCreateStageRequestRequestTypeDef, _OptionalCreateStageRequestRequestTypeDef
 ):
     pass
 
+
 CreateStageResponseTypeDef = TypedDict(
     "CreateStageResponseTypeDef",
     {
         "AccessLogSettings": AccessLogSettingsTypeDef,
         "ApiGatewayManaged": bool,
         "AutoDeploy": bool,
         "ClientCertificateId": str,
@@ -2341,15 +2626,15 @@
         "Description": str,
         "LastDeploymentStatusMessage": str,
         "LastUpdatedDate": datetime,
         "RouteSettings": Dict[str, RouteSettingsTypeDef],
         "StageName": str,
         "StageVariables": Dict[str, str],
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStageResponseTypeDef = TypedDict(
     "GetStageResponseTypeDef",
     {
         "AccessLogSettings": AccessLogSettingsTypeDef,
@@ -2362,15 +2647,15 @@
         "Description": str,
         "LastDeploymentStatusMessage": str,
         "LastUpdatedDate": datetime,
         "RouteSettings": Dict[str, RouteSettingsTypeDef],
         "StageName": str,
         "StageVariables": Dict[str, str],
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStageTypeDef = TypedDict(
     "_RequiredStageTypeDef",
     {
         "StageName": str,
@@ -2392,17 +2677,19 @@
         "RouteSettings": Dict[str, RouteSettingsTypeDef],
         "StageVariables": Dict[str, str],
         "Tags": Dict[str, str],
     },
     total=False,
 )
 
+
 class StageTypeDef(_RequiredStageTypeDef, _OptionalStageTypeDef):
     pass
 
+
 _RequiredUpdateStageRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateStageRequestRequestTypeDef",
     {
         "ApiId": str,
         "StageName": str,
     },
 )
@@ -2417,19 +2704,21 @@
         "Description": str,
         "RouteSettings": Mapping[str, RouteSettingsTypeDef],
         "StageVariables": Mapping[str, str],
     },
     total=False,
 )
 
+
 class UpdateStageRequestRequestTypeDef(
     _RequiredUpdateStageRequestRequestTypeDef, _OptionalUpdateStageRequestRequestTypeDef
 ):
     pass
 
+
 UpdateStageResponseTypeDef = TypedDict(
     "UpdateStageResponseTypeDef",
     {
         "AccessLogSettings": AccessLogSettingsTypeDef,
         "ApiGatewayManaged": bool,
         "AutoDeploy": bool,
         "ClientCertificateId": str,
@@ -2439,287 +2728,109 @@
         "Description": str,
         "LastDeploymentStatusMessage": str,
         "LastUpdatedDate": datetime,
         "RouteSettings": Dict[str, RouteSettingsTypeDef],
         "StageName": str,
         "StageVariables": Dict[str, str],
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeploymentsResponseTypeDef = TypedDict(
     "GetDeploymentsResponseTypeDef",
     {
         "Items": List[DeploymentTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetApisRequestGetApisPaginateTypeDef = TypedDict(
-    "GetApisRequestGetApisPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetAuthorizersRequestGetAuthorizersPaginateTypeDef = TypedDict(
-    "_RequiredGetAuthorizersRequestGetAuthorizersPaginateTypeDef",
-    {
-        "ApiId": str,
-    },
-)
-_OptionalGetAuthorizersRequestGetAuthorizersPaginateTypeDef = TypedDict(
-    "_OptionalGetAuthorizersRequestGetAuthorizersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetAuthorizersRequestGetAuthorizersPaginateTypeDef(
-    _RequiredGetAuthorizersRequestGetAuthorizersPaginateTypeDef,
-    _OptionalGetAuthorizersRequestGetAuthorizersPaginateTypeDef,
-):
-    pass
-
-_RequiredGetDeploymentsRequestGetDeploymentsPaginateTypeDef = TypedDict(
-    "_RequiredGetDeploymentsRequestGetDeploymentsPaginateTypeDef",
-    {
-        "ApiId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalGetDeploymentsRequestGetDeploymentsPaginateTypeDef = TypedDict(
-    "_OptionalGetDeploymentsRequestGetDeploymentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetDeploymentsRequestGetDeploymentsPaginateTypeDef(
-    _RequiredGetDeploymentsRequestGetDeploymentsPaginateTypeDef,
-    _OptionalGetDeploymentsRequestGetDeploymentsPaginateTypeDef,
-):
-    pass
-
-GetDomainNamesRequestGetDomainNamesPaginateTypeDef = TypedDict(
-    "GetDomainNamesRequestGetDomainNamesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef = TypedDict(
-    "_RequiredGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef",
-    {
-        "ApiId": str,
-        "IntegrationId": str,
-    },
-)
-_OptionalGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef = TypedDict(
-    "_OptionalGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef(
-    _RequiredGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef,
-    _OptionalGetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef,
-):
-    pass
-
-_RequiredGetIntegrationsRequestGetIntegrationsPaginateTypeDef = TypedDict(
-    "_RequiredGetIntegrationsRequestGetIntegrationsPaginateTypeDef",
-    {
-        "ApiId": str,
-    },
-)
-_OptionalGetIntegrationsRequestGetIntegrationsPaginateTypeDef = TypedDict(
-    "_OptionalGetIntegrationsRequestGetIntegrationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetIntegrationsRequestGetIntegrationsPaginateTypeDef(
-    _RequiredGetIntegrationsRequestGetIntegrationsPaginateTypeDef,
-    _OptionalGetIntegrationsRequestGetIntegrationsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetModelsRequestGetModelsPaginateTypeDef = TypedDict(
-    "_RequiredGetModelsRequestGetModelsPaginateTypeDef",
-    {
-        "ApiId": str,
-    },
-)
-_OptionalGetModelsRequestGetModelsPaginateTypeDef = TypedDict(
-    "_OptionalGetModelsRequestGetModelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetModelsRequestGetModelsPaginateTypeDef(
-    _RequiredGetModelsRequestGetModelsPaginateTypeDef,
-    _OptionalGetModelsRequestGetModelsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef = TypedDict(
-    "_RequiredGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef",
-    {
-        "ApiId": str,
-        "RouteId": str,
-    },
-)
-_OptionalGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef = TypedDict(
-    "_OptionalGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetRouteResponsesRequestGetRouteResponsesPaginateTypeDef(
-    _RequiredGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef,
-    _OptionalGetRouteResponsesRequestGetRouteResponsesPaginateTypeDef,
-):
-    pass
-
-_RequiredGetRoutesRequestGetRoutesPaginateTypeDef = TypedDict(
-    "_RequiredGetRoutesRequestGetRoutesPaginateTypeDef",
-    {
-        "ApiId": str,
-    },
-)
-_OptionalGetRoutesRequestGetRoutesPaginateTypeDef = TypedDict(
-    "_OptionalGetRoutesRequestGetRoutesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetRoutesRequestGetRoutesPaginateTypeDef(
-    _RequiredGetRoutesRequestGetRoutesPaginateTypeDef,
-    _OptionalGetRoutesRequestGetRoutesPaginateTypeDef,
-):
-    pass
-
-_RequiredGetStagesRequestGetStagesPaginateTypeDef = TypedDict(
-    "_RequiredGetStagesRequestGetStagesPaginateTypeDef",
-    {
-        "ApiId": str,
-    },
-)
-_OptionalGetStagesRequestGetStagesPaginateTypeDef = TypedDict(
-    "_OptionalGetStagesRequestGetStagesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetStagesRequestGetStagesPaginateTypeDef(
-    _RequiredGetStagesRequestGetStagesPaginateTypeDef,
-    _OptionalGetStagesRequestGetStagesPaginateTypeDef,
-):
-    pass
 
 GetIntegrationResponsesResponseTypeDef = TypedDict(
     "GetIntegrationResponsesResponseTypeDef",
     {
         "Items": List[IntegrationResponseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetModelsResponseTypeDef = TypedDict(
     "GetModelsResponseTypeDef",
     {
         "Items": List[ModelTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVpcLinksResponseTypeDef = TypedDict(
     "GetVpcLinksResponseTypeDef",
     {
         "Items": List[VpcLinkTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetApisResponseTypeDef = TypedDict(
     "GetApisResponseTypeDef",
     {
         "Items": List[ApiTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAuthorizersResponseTypeDef = TypedDict(
     "GetAuthorizersResponseTypeDef",
     {
         "Items": List[AuthorizerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainNamesResponseTypeDef = TypedDict(
     "GetDomainNamesResponseTypeDef",
     {
         "Items": List[DomainNameTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIntegrationsResponseTypeDef = TypedDict(
     "GetIntegrationsResponseTypeDef",
     {
         "Items": List[IntegrationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRouteResponsesResponseTypeDef = TypedDict(
     "GetRouteResponsesResponseTypeDef",
     {
         "Items": List[RouteResponseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRoutesResponseTypeDef = TypedDict(
     "GetRoutesResponseTypeDef",
     {
         "Items": List[RouteTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStagesResponseTypeDef = TypedDict(
     "GetStagesResponseTypeDef",
     {
         "Items": List[StageTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2.egg-info/PKG-INFO` & `types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-apigatewayv2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ApiGatewayV2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ApiGatewayV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-apigatewayv2"></a>
 
 # types-aiobotocore-apigatewayv2
 
 [![PyPI - types-aiobotocore-apigatewayv2](https://img.shields.io/pypi/v/types-aiobotocore-apigatewayv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-apigatewayv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-apigatewayv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-apigatewayv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-apigatewayv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-apigatewayv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApiGatewayV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2)
+[aiobotocore.ApiGatewayV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/apigatewayv2.html#ApiGatewayV2)
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
 [types-aiobotocore-apigatewayv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_apigatewayv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -368,26 +368,30 @@
 ```python
 from types_aiobotocore_apigatewayv2.type_defs import (
     AccessLogSettingsTypeDef,
     ApiMappingTypeDef,
     CorsTypeDef,
     JWTConfigurationTypeDef,
     CreateApiMappingRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateApiMappingResponseTypeDef,
     CreateDeploymentRequestRequestTypeDef,
+    CreateDeploymentResponseTypeDef,
     DomainNameConfigurationTypeDef,
     MutualTlsAuthenticationInputTypeDef,
     MutualTlsAuthenticationTypeDef,
     TlsConfigInputTypeDef,
     CreateIntegrationResponseRequestRequestTypeDef,
+    CreateIntegrationResponseResponseTypeDef,
     TlsConfigTypeDef,
     CreateModelRequestRequestTypeDef,
+    CreateModelResponseTypeDef,
     ParameterConstraintsTypeDef,
     RouteSettingsTypeDef,
     CreateVpcLinkRequestRequestTypeDef,
+    CreateVpcLinkResponseTypeDef,
     DeleteAccessLogSettingsRequestRequestTypeDef,
     DeleteApiMappingRequestRequestTypeDef,
     DeleteApiRequestRequestTypeDef,
     DeleteAuthorizerRequestRequestTypeDef,
     DeleteCorsConfigurationRequestRequestTypeDef,
     DeleteDeploymentRequestRequestTypeDef,
     DeleteDomainNameRequestRequestTypeDef,
@@ -397,89 +401,95 @@
     DeleteRouteRequestParameterRequestRequestTypeDef,
     DeleteRouteRequestRequestTypeDef,
     DeleteRouteResponseRequestRequestTypeDef,
     DeleteRouteSettingsRequestRequestTypeDef,
     DeleteStageRequestRequestTypeDef,
     DeleteVpcLinkRequestRequestTypeDef,
     DeploymentTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportApiRequestRequestTypeDef,
+    ExportApiResponseTypeDef,
     GetApiMappingRequestRequestTypeDef,
+    GetApiMappingResponseTypeDef,
     GetApiMappingsRequestRequestTypeDef,
     GetApiRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetApisRequestGetApisPaginateTypeDef,
     GetApisRequestRequestTypeDef,
     GetAuthorizerRequestRequestTypeDef,
+    GetAuthorizersRequestGetAuthorizersPaginateTypeDef,
     GetAuthorizersRequestRequestTypeDef,
     GetDeploymentRequestRequestTypeDef,
+    GetDeploymentResponseTypeDef,
+    GetDeploymentsRequestGetDeploymentsPaginateTypeDef,
     GetDeploymentsRequestRequestTypeDef,
     GetDomainNameRequestRequestTypeDef,
+    GetDomainNamesRequestGetDomainNamesPaginateTypeDef,
     GetDomainNamesRequestRequestTypeDef,
     GetIntegrationRequestRequestTypeDef,
     GetIntegrationResponseRequestRequestTypeDef,
+    GetIntegrationResponseResponseTypeDef,
+    GetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef,
     GetIntegrationResponsesRequestRequestTypeDef,
     IntegrationResponseTypeDef,
+    GetIntegrationsRequestGetIntegrationsPaginateTypeDef,
     GetIntegrationsRequestRequestTypeDef,
     GetModelRequestRequestTypeDef,
+    GetModelResponseTypeDef,
     GetModelTemplateRequestRequestTypeDef,
+    GetModelTemplateResponseTypeDef,
+    GetModelsRequestGetModelsPaginateTypeDef,
     GetModelsRequestRequestTypeDef,
     ModelTypeDef,
     GetRouteRequestRequestTypeDef,
     GetRouteResponseRequestRequestTypeDef,
+    GetRouteResponsesRequestGetRouteResponsesPaginateTypeDef,
     GetRouteResponsesRequestRequestTypeDef,
+    GetRoutesRequestGetRoutesPaginateTypeDef,
     GetRoutesRequestRequestTypeDef,
     GetStageRequestRequestTypeDef,
+    GetStagesRequestGetStagesPaginateTypeDef,
     GetStagesRequestRequestTypeDef,
     GetTagsRequestRequestTypeDef,
+    GetTagsResponseTypeDef,
     GetVpcLinkRequestRequestTypeDef,
+    GetVpcLinkResponseTypeDef,
     GetVpcLinksRequestRequestTypeDef,
     VpcLinkTypeDef,
     ImportApiRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ReimportApiRequestRequestTypeDef,
     ResetAuthorizersCacheRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApiMappingRequestRequestTypeDef,
+    UpdateApiMappingResponseTypeDef,
     UpdateDeploymentRequestRequestTypeDef,
+    UpdateDeploymentResponseTypeDef,
     UpdateIntegrationResponseRequestRequestTypeDef,
+    UpdateIntegrationResponseResponseTypeDef,
     UpdateModelRequestRequestTypeDef,
+    UpdateModelResponseTypeDef,
     UpdateVpcLinkRequestRequestTypeDef,
+    UpdateVpcLinkResponseTypeDef,
+    GetApiMappingsResponseTypeDef,
     ApiTypeDef,
     CreateApiRequestRequestTypeDef,
-    UpdateApiRequestRequestTypeDef,
-    AuthorizerTypeDef,
-    CreateAuthorizerRequestRequestTypeDef,
-    UpdateAuthorizerRequestRequestTypeDef,
-    CreateApiMappingResponseTypeDef,
     CreateApiResponseTypeDef,
-    CreateAuthorizerResponseTypeDef,
-    CreateDeploymentResponseTypeDef,
-    CreateIntegrationResponseResponseTypeDef,
-    CreateModelResponseTypeDef,
-    CreateVpcLinkResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportApiResponseTypeDef,
-    GetApiMappingResponseTypeDef,
-    GetApiMappingsResponseTypeDef,
     GetApiResponseTypeDef,
-    GetAuthorizerResponseTypeDef,
-    GetDeploymentResponseTypeDef,
-    GetIntegrationResponseResponseTypeDef,
-    GetModelResponseTypeDef,
-    GetModelTemplateResponseTypeDef,
-    GetTagsResponseTypeDef,
-    GetVpcLinkResponseTypeDef,
     ImportApiResponseTypeDef,
     ReimportApiResponseTypeDef,
-    UpdateApiMappingResponseTypeDef,
+    UpdateApiRequestRequestTypeDef,
     UpdateApiResponseTypeDef,
+    AuthorizerTypeDef,
+    CreateAuthorizerRequestRequestTypeDef,
+    CreateAuthorizerResponseTypeDef,
+    GetAuthorizerResponseTypeDef,
+    UpdateAuthorizerRequestRequestTypeDef,
     UpdateAuthorizerResponseTypeDef,
-    UpdateDeploymentResponseTypeDef,
-    UpdateIntegrationResponseResponseTypeDef,
-    UpdateModelResponseTypeDef,
-    UpdateVpcLinkResponseTypeDef,
     CreateDomainNameRequestRequestTypeDef,
     UpdateDomainNameRequestRequestTypeDef,
     CreateDomainNameResponseTypeDef,
     DomainNameTypeDef,
     GetDomainNameResponseTypeDef,
     UpdateDomainNameResponseTypeDef,
     CreateIntegrationRequestRequestTypeDef,
@@ -503,24 +513,14 @@
     CreateStageRequestRequestTypeDef,
     CreateStageResponseTypeDef,
     GetStageResponseTypeDef,
     StageTypeDef,
     UpdateStageRequestRequestTypeDef,
     UpdateStageResponseTypeDef,
     GetDeploymentsResponseTypeDef,
-    GetApisRequestGetApisPaginateTypeDef,
-    GetAuthorizersRequestGetAuthorizersPaginateTypeDef,
-    GetDeploymentsRequestGetDeploymentsPaginateTypeDef,
-    GetDomainNamesRequestGetDomainNamesPaginateTypeDef,
-    GetIntegrationResponsesRequestGetIntegrationResponsesPaginateTypeDef,
-    GetIntegrationsRequestGetIntegrationsPaginateTypeDef,
-    GetModelsRequestGetModelsPaginateTypeDef,
-    GetRouteResponsesRequestGetRouteResponsesPaginateTypeDef,
-    GetRoutesRequestGetRoutesPaginateTypeDef,
-    GetStagesRequestGetStagesPaginateTypeDef,
     GetIntegrationResponsesResponseTypeDef,
     GetModelsResponseTypeDef,
     GetVpcLinksResponseTypeDef,
     GetApisResponseTypeDef,
     GetAuthorizersResponseTypeDef,
     GetDomainNamesResponseTypeDef,
     GetIntegrationsResponseTypeDef,
@@ -537,43 +537,43 @@
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

### Comparing `types-aiobotocore-apigatewayv2-2.5.0.post1/types_aiobotocore_apigatewayv2.egg-info/SOURCES.txt` & `types-aiobotocore-apigatewayv2-2.5.1/types_aiobotocore_apigatewayv2.egg-info/SOURCES.txt`

 * *Files identical despite different names*


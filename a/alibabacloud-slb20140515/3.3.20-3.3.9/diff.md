# Comparing `tmp/alibabacloud_slb20140515-3.3.20.tar.gz` & `tmp/alibabacloud_slb20140515-3.3.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/alibabacloud_slb20140515-3.3.20.tar", last modified: Wed Jun 28 09:18:46 2023, max compression
+gzip compressed data, was "dist/alibabacloud_slb20140515-3.3.9.tar", last modified: Wed Dec 29 10:09:58 2021, max compression
```

## Comparing `alibabacloud_slb20140515-3.3.20.tar` & `alibabacloud_slb20140515-3.3.9.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/
--rw-r--r--   0 root         (0) root         (0)      861 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/ChangeLog.md
--rw-r--r--   0 root         (0) root         (0)      600 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/LICENSE
--rw-r--r--   0 root         (0) root         (0)       29 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/MANIFEST.in
--rw-r--r--   0 root         (0) root         (0)     2346 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     1022 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/README-CN.md
--rw-r--r--   0 root         (0) root         (0)     1107 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/alibabacloud_slb20140515/
--rw-r--r--   0 root         (0) root         (0)       22 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/alibabacloud_slb20140515/__init__.py
--rw-r--r--   0 root         (0) root         (0)   526160 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/alibabacloud_slb20140515/client.py
--rw-r--r--   0 root         (0) root         (0)  1007048 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/alibabacloud_slb20140515/models.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/alibabacloud_slb20140515.egg-info/
--rw-r--r--   0 root         (0) root         (0)     2346 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/alibabacloud_slb20140515.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      420 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/alibabacloud_slb20140515.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/alibabacloud_slb20140515.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      156 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/alibabacloud_slb20140515.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       25 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/alibabacloud_slb20140515.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)       73 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/setup.cfg
--rw-r--r--   0 root         (0) root         (0)     2627 2023-06-28 09:18:46.000000 alibabacloud_slb20140515-3.3.20/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/
+-rw-r--r--   0 root         (0) root         (0)      305 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/ChangeLog.md
+-rw-r--r--   0 root         (0) root         (0)      600 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/LICENSE
+-rw-r--r--   0 root         (0) root         (0)       29 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/MANIFEST.in
+-rw-r--r--   0 root         (0) root         (0)     2345 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     1022 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/README-CN.md
+-rw-r--r--   0 root         (0) root         (0)     1107 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/alibabacloud_slb20140515/
+-rw-r--r--   0 root         (0) root         (0)       21 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/alibabacloud_slb20140515/__init__.py
+-rw-r--r--   0 root         (0) root         (0)   431433 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/alibabacloud_slb20140515/client.py
+-rw-r--r--   0 root         (0) root         (0)   695669 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/alibabacloud_slb20140515/models.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/alibabacloud_slb20140515.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     2345 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/alibabacloud_slb20140515.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      420 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/alibabacloud_slb20140515.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/alibabacloud_slb20140515.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      156 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/alibabacloud_slb20140515.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       25 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/alibabacloud_slb20140515.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)       73 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)     2627 2021-12-29 10:09:58.000000 alibabacloud_slb20140515-3.3.9/setup.py
```

### Comparing `alibabacloud_slb20140515-3.3.20/LICENSE` & `alibabacloud_slb20140515-3.3.9/LICENSE`

 * *Files identical despite different names*

### Comparing `alibabacloud_slb20140515-3.3.20/PKG-INFO` & `alibabacloud_slb20140515-3.3.9/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: alibabacloud_slb20140515
-Version: 3.3.20
+Version: 3.3.9
 Summary: Alibaba Cloud Server Load Balancer (20140515) SDK Library for Python
 Home-page: https://github.com/aliyun/alibabacloud-python-sdk
 Author: Alibaba Cloud SDK
 Author-email: sdk-team@alibabacloud.com
 License: Apache License 2.0
 Description: English | [简体中文](README-CN.md)
         ![](https://aliyunsdk-pages.alicdn.com/icons/AlibabaCloud.svg)
```

### Comparing `alibabacloud_slb20140515-3.3.20/README-CN.md` & `alibabacloud_slb20140515-3.3.9/README-CN.md`

 * *Files identical despite different names*

### Comparing `alibabacloud_slb20140515-3.3.20/README.md` & `alibabacloud_slb20140515-3.3.9/README.md`

 * *Files identical despite different names*

### Comparing `alibabacloud_slb20140515-3.3.20/alibabacloud_slb20140515/client.py` & `alibabacloud_slb20140515-3.3.9/alibabacloud_slb20140515/client.py`

 * *Files 26% similar despite different names*

```diff
@@ -26,20 +26,21 @@
             'cn-qingdao': 'slb.aliyuncs.com',
             'cn-beijing': 'slb.aliyuncs.com',
             'cn-hangzhou': 'slb.aliyuncs.com',
             'cn-shanghai': 'slb.aliyuncs.com',
             'cn-shenzhen': 'slb.aliyuncs.com',
             'cn-hongkong': 'slb.aliyuncs.com',
             'ap-southeast-1': 'slb.aliyuncs.com',
-            'us-east-1': 'slb.aliyuncs.com',
             'us-west-1': 'slb.aliyuncs.com',
+            'us-east-1': 'slb.aliyuncs.com',
             'cn-shanghai-finance-1': 'slb.aliyuncs.com',
             'cn-shenzhen-finance-1': 'slb.aliyuncs.com',
             'cn-north-2-gov-1': 'slb.aliyuncs.com',
             'ap-northeast-2-pop': 'slb.aliyuncs.com',
+            'cn-beijing-finance-1': 'slb.aliyuncs.com',
             'cn-beijing-finance-pop': 'slb.aliyuncs.com',
             'cn-beijing-gov-1': 'slb.aliyuncs.com',
             'cn-beijing-nu16-b01': 'slb.aliyuncs.com',
             'cn-edge-1': 'slb.aliyuncs.com',
             'cn-fujian': 'slb.aliyuncs.com',
             'cn-haidian-cm12-c01': 'slb.aliyuncs.com',
             'cn-hangzhou-bj-b01': 'slb.aliyuncs.com',
@@ -56,15 +57,14 @@
             'cn-shanghai-inner': 'slb.aliyuncs.com',
             'cn-shanghai-internal-test-1': 'slb.aliyuncs.com',
             'cn-shenzhen-inner': 'slb.aliyuncs.com',
             'cn-shenzhen-st4-d01': 'slb.aliyuncs.com',
             'cn-shenzhen-su18-b01': 'slb.aliyuncs.com',
             'cn-wuhan': 'slb.aliyuncs.com',
             'cn-yushanfang': 'slb.aliyuncs.com',
-            'cn-zhangbei': 'slb.aliyuncs.com',
             'cn-zhangbei-na61-b01': 'slb.aliyuncs.com',
             'cn-zhangjiakou-na62-a01': 'slb.aliyuncs.com',
             'cn-zhengzhou-nebula-1': 'slb.aliyuncs.com',
             'eu-west-1-oxs': 'slb.aliyuncs.com',
             'rus-west-1-pop': 'slb.aliyuncs.com'
         }
         self.check_config(config)
@@ -87,23 +87,14 @@
         return EndpointUtilClient.get_endpoint_rules(product_id, region_id, endpoint_rule, network, suffix)
 
     def add_access_control_list_entry_with_options(
         self,
         request: slb_20140515_models.AddAccessControlListEntryRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.AddAccessControlListEntryResponse:
-        """
-        Each network ACL can contain one or more IP addresses or CIDR blocks. Take note of the following limits on network ACLs:
-        *   The number of IP entries that can be added to a network ACL with each Alibaba Cloud account at a time: 50
-        *   The maximum number of IP entries that each network ACL can contain: 300
-        
-        @param request: AddAccessControlListEntryRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: AddAccessControlListEntryResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_entrys):
             query['AclEntrys'] = request.acl_entrys
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.owner_account):
@@ -136,23 +127,14 @@
         )
 
     async def add_access_control_list_entry_with_options_async(
         self,
         request: slb_20140515_models.AddAccessControlListEntryRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.AddAccessControlListEntryResponse:
-        """
-        Each network ACL can contain one or more IP addresses or CIDR blocks. Take note of the following limits on network ACLs:
-        *   The number of IP entries that can be added to a network ACL with each Alibaba Cloud account at a time: 50
-        *   The maximum number of IP entries that each network ACL can contain: 300
-        
-        @param request: AddAccessControlListEntryRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: AddAccessControlListEntryResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_entrys):
             query['AclEntrys'] = request.acl_entrys
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.owner_account):
@@ -184,52 +166,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def add_access_control_list_entry(
         self,
         request: slb_20140515_models.AddAccessControlListEntryRequest,
     ) -> slb_20140515_models.AddAccessControlListEntryResponse:
-        """
-        Each network ACL can contain one or more IP addresses or CIDR blocks. Take note of the following limits on network ACLs:
-        *   The number of IP entries that can be added to a network ACL with each Alibaba Cloud account at a time: 50
-        *   The maximum number of IP entries that each network ACL can contain: 300
-        
-        @param request: AddAccessControlListEntryRequest
-        @return: AddAccessControlListEntryResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.add_access_control_list_entry_with_options(request, runtime)
 
     async def add_access_control_list_entry_async(
         self,
         request: slb_20140515_models.AddAccessControlListEntryRequest,
     ) -> slb_20140515_models.AddAccessControlListEntryResponse:
-        """
-        Each network ACL can contain one or more IP addresses or CIDR blocks. Take note of the following limits on network ACLs:
-        *   The number of IP entries that can be added to a network ACL with each Alibaba Cloud account at a time: 50
-        *   The maximum number of IP entries that each network ACL can contain: 300
-        
-        @param request: AddAccessControlListEntryRequest
-        @return: AddAccessControlListEntryResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.add_access_control_list_entry_with_options_async(request, runtime)
 
     def add_backend_servers_with_options(
         self,
         request: slb_20140515_models.AddBackendServersRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.AddBackendServersResponse:
-        """
-        The ID of the CLB instance.
-        
-        @param request: AddBackendServersRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: AddBackendServersResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.backend_servers):
             query['BackendServers'] = request.backend_servers
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
@@ -262,21 +221,14 @@
         )
 
     async def add_backend_servers_with_options_async(
         self,
         request: slb_20140515_models.AddBackendServersRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.AddBackendServersResponse:
-        """
-        The ID of the CLB instance.
-        
-        @param request: AddBackendServersRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: AddBackendServersResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.backend_servers):
             query['BackendServers'] = request.backend_servers
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
@@ -308,33 +260,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def add_backend_servers(
         self,
         request: slb_20140515_models.AddBackendServersRequest,
     ) -> slb_20140515_models.AddBackendServersResponse:
-        """
-        The ID of the CLB instance.
-        
-        @param request: AddBackendServersRequest
-        @return: AddBackendServersResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.add_backend_servers_with_options(request, runtime)
 
     async def add_backend_servers_async(
         self,
         request: slb_20140515_models.AddBackendServersRequest,
     ) -> slb_20140515_models.AddBackendServersResponse:
-        """
-        The ID of the CLB instance.
-        
-        @param request: AddBackendServersRequest
-        @return: AddBackendServersResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.add_backend_servers_with_options_async(request, runtime)
 
     def add_listener_white_list_item_with_options(
         self,
         request: slb_20140515_models.AddListenerWhiteListItemRequest,
         runtime: util_models.RuntimeOptions,
@@ -437,22 +377,14 @@
         return await self.add_listener_white_list_item_with_options_async(request, runtime)
 
     def add_tags_with_options(
         self,
         request: slb_20140515_models.AddTagsRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.AddTagsResponse:
-        """
-        The name of this action.
-        Value: **AddTags**\
-        
-        @param request: AddTagsRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: AddTagsResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -485,22 +417,14 @@
         )
 
     async def add_tags_with_options_async(
         self,
         request: slb_20140515_models.AddTagsRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.AddTagsResponse:
-        """
-        The name of this action.
-        Value: **AddTags**\
-        
-        @param request: AddTagsRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: AddTagsResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -532,35 +456,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def add_tags(
         self,
         request: slb_20140515_models.AddTagsRequest,
     ) -> slb_20140515_models.AddTagsResponse:
-        """
-        The name of this action.
-        Value: **AddTags**\
-        
-        @param request: AddTagsRequest
-        @return: AddTagsResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.add_tags_with_options(request, runtime)
 
     async def add_tags_async(
         self,
         request: slb_20140515_models.AddTagsRequest,
     ) -> slb_20140515_models.AddTagsResponse:
-        """
-        The name of this action.
-        Value: **AddTags**\
-        
-        @param request: AddTagsRequest
-        @return: AddTagsResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.add_tags_with_options_async(request, runtime)
 
     def add_vserver_group_backend_servers_with_options(
         self,
         request: slb_20140515_models.AddVServerGroupBackendServersRequest,
         runtime: util_models.RuntimeOptions,
@@ -655,21 +565,14 @@
         return await self.add_vserver_group_backend_servers_with_options_async(request, runtime)
 
     def create_access_control_list_with_options(
         self,
         request: slb_20140515_models.CreateAccessControlListRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.CreateAccessControlListResponse:
-        """
-        The ID of the region where you want to create the ACL.
-        
-        @param request: CreateAccessControlListRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: CreateAccessControlListResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_name):
             query['AclName'] = request.acl_name
         if not UtilClient.is_unset(request.address_ipversion):
             query['AddressIPVersion'] = request.address_ipversion
         if not UtilClient.is_unset(request.owner_account):
@@ -680,16 +583,14 @@
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_group_id):
             query['ResourceGroupId'] = request.resource_group_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='CreateAccessControlList',
             version='2014-05-15',
             protocol='HTTPS',
@@ -706,21 +607,14 @@
         )
 
     async def create_access_control_list_with_options_async(
         self,
         request: slb_20140515_models.CreateAccessControlListRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.CreateAccessControlListResponse:
-        """
-        The ID of the region where you want to create the ACL.
-        
-        @param request: CreateAccessControlListRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: CreateAccessControlListResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_name):
             query['AclName'] = request.acl_name
         if not UtilClient.is_unset(request.address_ipversion):
             query['AddressIPVersion'] = request.address_ipversion
         if not UtilClient.is_unset(request.owner_account):
@@ -731,16 +625,14 @@
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_group_id):
             query['ResourceGroupId'] = request.resource_group_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='CreateAccessControlList',
             version='2014-05-15',
             protocol='HTTPS',
@@ -756,33 +648,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def create_access_control_list(
         self,
         request: slb_20140515_models.CreateAccessControlListRequest,
     ) -> slb_20140515_models.CreateAccessControlListResponse:
-        """
-        The ID of the region where you want to create the ACL.
-        
-        @param request: CreateAccessControlListRequest
-        @return: CreateAccessControlListResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.create_access_control_list_with_options(request, runtime)
 
     async def create_access_control_list_async(
         self,
         request: slb_20140515_models.CreateAccessControlListRequest,
     ) -> slb_20140515_models.CreateAccessControlListResponse:
-        """
-        The ID of the region where you want to create the ACL.
-        
-        @param request: CreateAccessControlListRequest
-        @return: CreateAccessControlListResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.create_access_control_list_with_options_async(request, runtime)
 
     def create_domain_extension_with_options(
         self,
         request: slb_20140515_models.CreateDomainExtensionRequest,
         runtime: util_models.RuntimeOptions,
@@ -885,21 +765,14 @@
         return await self.create_domain_extension_with_options_async(request, runtime)
 
     def create_load_balancer_with_options(
         self,
         request: slb_20140515_models.CreateLoadBalancerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.CreateLoadBalancerResponse:
-        """
-        The order ID of the subscription CLB instance.
-        
-        @param request: CreateLoadBalancerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: CreateLoadBalancerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.address):
             query['Address'] = request.address
         if not UtilClient.is_unset(request.address_ipversion):
             query['AddressIPVersion'] = request.address_ipversion
         if not UtilClient.is_unset(request.address_type):
@@ -910,16 +783,14 @@
             query['Bandwidth'] = request.bandwidth
         if not UtilClient.is_unset(request.client_token):
             query['ClientToken'] = request.client_token
         if not UtilClient.is_unset(request.delete_protection):
             query['DeleteProtection'] = request.delete_protection
         if not UtilClient.is_unset(request.duration):
             query['Duration'] = request.duration
-        if not UtilClient.is_unset(request.instance_charge_type):
-            query['InstanceChargeType'] = request.instance_charge_type
         if not UtilClient.is_unset(request.internet_charge_type):
             query['InternetChargeType'] = request.internet_charge_type
         if not UtilClient.is_unset(request.load_balancer_name):
             query['LoadBalancerName'] = request.load_balancer_name
         if not UtilClient.is_unset(request.load_balancer_spec):
             query['LoadBalancerSpec'] = request.load_balancer_spec
         if not UtilClient.is_unset(request.master_zone_id):
@@ -942,16 +813,14 @@
             query['ResourceGroupId'] = request.resource_group_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.slave_zone_id):
             query['SlaveZoneId'] = request.slave_zone_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         if not UtilClient.is_unset(request.v_switch_id):
             query['VSwitchId'] = request.v_switch_id
         if not UtilClient.is_unset(request.vpc_id):
             query['VpcId'] = request.vpc_id
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
@@ -972,21 +841,14 @@
         )
 
     async def create_load_balancer_with_options_async(
         self,
         request: slb_20140515_models.CreateLoadBalancerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.CreateLoadBalancerResponse:
-        """
-        The order ID of the subscription CLB instance.
-        
-        @param request: CreateLoadBalancerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: CreateLoadBalancerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.address):
             query['Address'] = request.address
         if not UtilClient.is_unset(request.address_ipversion):
             query['AddressIPVersion'] = request.address_ipversion
         if not UtilClient.is_unset(request.address_type):
@@ -997,16 +859,14 @@
             query['Bandwidth'] = request.bandwidth
         if not UtilClient.is_unset(request.client_token):
             query['ClientToken'] = request.client_token
         if not UtilClient.is_unset(request.delete_protection):
             query['DeleteProtection'] = request.delete_protection
         if not UtilClient.is_unset(request.duration):
             query['Duration'] = request.duration
-        if not UtilClient.is_unset(request.instance_charge_type):
-            query['InstanceChargeType'] = request.instance_charge_type
         if not UtilClient.is_unset(request.internet_charge_type):
             query['InternetChargeType'] = request.internet_charge_type
         if not UtilClient.is_unset(request.load_balancer_name):
             query['LoadBalancerName'] = request.load_balancer_name
         if not UtilClient.is_unset(request.load_balancer_spec):
             query['LoadBalancerSpec'] = request.load_balancer_spec
         if not UtilClient.is_unset(request.master_zone_id):
@@ -1029,16 +889,14 @@
             query['ResourceGroupId'] = request.resource_group_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.slave_zone_id):
             query['SlaveZoneId'] = request.slave_zone_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         if not UtilClient.is_unset(request.v_switch_id):
             query['VSwitchId'] = request.v_switch_id
         if not UtilClient.is_unset(request.vpc_id):
             query['VpcId'] = request.vpc_id
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
@@ -1058,50 +916,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def create_load_balancer(
         self,
         request: slb_20140515_models.CreateLoadBalancerRequest,
     ) -> slb_20140515_models.CreateLoadBalancerResponse:
-        """
-        The order ID of the subscription CLB instance.
-        
-        @param request: CreateLoadBalancerRequest
-        @return: CreateLoadBalancerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.create_load_balancer_with_options(request, runtime)
 
     async def create_load_balancer_async(
         self,
         request: slb_20140515_models.CreateLoadBalancerRequest,
     ) -> slb_20140515_models.CreateLoadBalancerResponse:
-        """
-        The order ID of the subscription CLB instance.
-        
-        @param request: CreateLoadBalancerRequest
-        @return: CreateLoadBalancerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.create_load_balancer_with_options_async(request, runtime)
 
     def create_load_balancer_httplistener_with_options(
         self,
         request: slb_20140515_models.CreateLoadBalancerHTTPListenerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.CreateLoadBalancerHTTPListenerResponse:
-        """
-        The timeout period of a cookie. Unit: seconds.
-        Valid values: **1** to **86400**.
-        >  If **StickySession** is set to **on** and **StickySessionType** is set to **insert**, this parameter is required.
-        
-        @param request: CreateLoadBalancerHTTPListenerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: CreateLoadBalancerHTTPListenerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -1160,16 +997,14 @@
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.scheduler):
             query['Scheduler'] = request.scheduler
         if not UtilClient.is_unset(request.sticky_session):
             query['StickySession'] = request.sticky_session
         if not UtilClient.is_unset(request.sticky_session_type):
             query['StickySessionType'] = request.sticky_session_type
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         if not UtilClient.is_unset(request.unhealthy_threshold):
             query['UnhealthyThreshold'] = request.unhealthy_threshold
         if not UtilClient.is_unset(request.vserver_group_id):
             query['VServerGroupId'] = request.vserver_group_id
         if not UtilClient.is_unset(request.xforwarded_for):
             query['XForwardedFor'] = request.xforwarded_for
         if not UtilClient.is_unset(request.xforwarded_for__slbid):
@@ -1198,23 +1033,14 @@
         )
 
     async def create_load_balancer_httplistener_with_options_async(
         self,
         request: slb_20140515_models.CreateLoadBalancerHTTPListenerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.CreateLoadBalancerHTTPListenerResponse:
-        """
-        The timeout period of a cookie. Unit: seconds.
-        Valid values: **1** to **86400**.
-        >  If **StickySession** is set to **on** and **StickySessionType** is set to **insert**, this parameter is required.
-        
-        @param request: CreateLoadBalancerHTTPListenerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: CreateLoadBalancerHTTPListenerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -1273,16 +1099,14 @@
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.scheduler):
             query['Scheduler'] = request.scheduler
         if not UtilClient.is_unset(request.sticky_session):
             query['StickySession'] = request.sticky_session
         if not UtilClient.is_unset(request.sticky_session_type):
             query['StickySessionType'] = request.sticky_session_type
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         if not UtilClient.is_unset(request.unhealthy_threshold):
             query['UnhealthyThreshold'] = request.unhealthy_threshold
         if not UtilClient.is_unset(request.vserver_group_id):
             query['VServerGroupId'] = request.vserver_group_id
         if not UtilClient.is_unset(request.xforwarded_for):
             query['XForwardedFor'] = request.xforwarded_for
         if not UtilClient.is_unset(request.xforwarded_for__slbid):
@@ -1310,54 +1134,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def create_load_balancer_httplistener(
         self,
         request: slb_20140515_models.CreateLoadBalancerHTTPListenerRequest,
     ) -> slb_20140515_models.CreateLoadBalancerHTTPListenerResponse:
-        """
-        The timeout period of a cookie. Unit: seconds.
-        Valid values: **1** to **86400**.
-        >  If **StickySession** is set to **on** and **StickySessionType** is set to **insert**, this parameter is required.
-        
-        @param request: CreateLoadBalancerHTTPListenerRequest
-        @return: CreateLoadBalancerHTTPListenerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.create_load_balancer_httplistener_with_options(request, runtime)
 
     async def create_load_balancer_httplistener_async(
         self,
         request: slb_20140515_models.CreateLoadBalancerHTTPListenerRequest,
     ) -> slb_20140515_models.CreateLoadBalancerHTTPListenerResponse:
-        """
-        The timeout period of a cookie. Unit: seconds.
-        Valid values: **1** to **86400**.
-        >  If **StickySession** is set to **on** and **StickySessionType** is set to **insert**, this parameter is required.
-        
-        @param request: CreateLoadBalancerHTTPListenerRequest
-        @return: CreateLoadBalancerHTTPListenerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.create_load_balancer_httplistener_with_options_async(request, runtime)
 
     def create_load_balancer_httpslistener_with_options(
         self,
         request: slb_20140515_models.CreateLoadBalancerHTTPSListenerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.CreateLoadBalancerHTTPSListenerResponse:
-        """
-        The timeout period of a cookie. Unit: seconds.
-        Valid values: **1** to **86400**.
-        >  If **StickySession** is set to **on** and **StickySessionType** is set to **insert**, this parameter is required.
-        
-        @param request: CreateLoadBalancerHTTPSListenerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: CreateLoadBalancerHTTPSListenerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -1420,16 +1219,14 @@
             query['ServerCertificateId'] = request.server_certificate_id
         if not UtilClient.is_unset(request.sticky_session):
             query['StickySession'] = request.sticky_session
         if not UtilClient.is_unset(request.sticky_session_type):
             query['StickySessionType'] = request.sticky_session_type
         if not UtilClient.is_unset(request.tlscipher_policy):
             query['TLSCipherPolicy'] = request.tlscipher_policy
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         if not UtilClient.is_unset(request.unhealthy_threshold):
             query['UnhealthyThreshold'] = request.unhealthy_threshold
         if not UtilClient.is_unset(request.vserver_group_id):
             query['VServerGroupId'] = request.vserver_group_id
         if not UtilClient.is_unset(request.xforwarded_for):
             query['XForwardedFor'] = request.xforwarded_for
         if not UtilClient.is_unset(request.xforwarded_for__slbid):
@@ -1458,23 +1255,14 @@
         )
 
     async def create_load_balancer_httpslistener_with_options_async(
         self,
         request: slb_20140515_models.CreateLoadBalancerHTTPSListenerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.CreateLoadBalancerHTTPSListenerResponse:
-        """
-        The timeout period of a cookie. Unit: seconds.
-        Valid values: **1** to **86400**.
-        >  If **StickySession** is set to **on** and **StickySessionType** is set to **insert**, this parameter is required.
-        
-        @param request: CreateLoadBalancerHTTPSListenerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: CreateLoadBalancerHTTPSListenerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -1537,16 +1325,14 @@
             query['ServerCertificateId'] = request.server_certificate_id
         if not UtilClient.is_unset(request.sticky_session):
             query['StickySession'] = request.sticky_session
         if not UtilClient.is_unset(request.sticky_session_type):
             query['StickySessionType'] = request.sticky_session_type
         if not UtilClient.is_unset(request.tlscipher_policy):
             query['TLSCipherPolicy'] = request.tlscipher_policy
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         if not UtilClient.is_unset(request.unhealthy_threshold):
             query['UnhealthyThreshold'] = request.unhealthy_threshold
         if not UtilClient.is_unset(request.vserver_group_id):
             query['VServerGroupId'] = request.vserver_group_id
         if not UtilClient.is_unset(request.xforwarded_for):
             query['XForwardedFor'] = request.xforwarded_for
         if not UtilClient.is_unset(request.xforwarded_for__slbid):
@@ -1574,53 +1360,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def create_load_balancer_httpslistener(
         self,
         request: slb_20140515_models.CreateLoadBalancerHTTPSListenerRequest,
     ) -> slb_20140515_models.CreateLoadBalancerHTTPSListenerResponse:
-        """
-        The timeout period of a cookie. Unit: seconds.
-        Valid values: **1** to **86400**.
-        >  If **StickySession** is set to **on** and **StickySessionType** is set to **insert**, this parameter is required.
-        
-        @param request: CreateLoadBalancerHTTPSListenerRequest
-        @return: CreateLoadBalancerHTTPSListenerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.create_load_balancer_httpslistener_with_options(request, runtime)
 
     async def create_load_balancer_httpslistener_async(
         self,
         request: slb_20140515_models.CreateLoadBalancerHTTPSListenerRequest,
     ) -> slb_20140515_models.CreateLoadBalancerHTTPSListenerResponse:
-        """
-        The timeout period of a cookie. Unit: seconds.
-        Valid values: **1** to **86400**.
-        >  If **StickySession** is set to **on** and **StickySessionType** is set to **insert**, this parameter is required.
-        
-        @param request: CreateLoadBalancerHTTPSListenerRequest
-        @return: CreateLoadBalancerHTTPSListenerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.create_load_balancer_httpslistener_with_options_async(request, runtime)
 
     def create_load_balancer_tcplistener_with_options(
         self,
         request: slb_20140515_models.CreateLoadBalancerTCPListenerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.CreateLoadBalancerTCPListenerResponse:
-        """
-        The number of times that a healthy backend server must consecutively fail health checks before it is declared unhealthy. In this case, the health status is changed from *success** to **fail**.
-        Valid values: **2** to **10**.
-        
-        @param request: CreateLoadBalancerTCPListenerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: CreateLoadBalancerTCPListenerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -1641,16 +1403,14 @@
             query['HealthCheckConnectPort'] = request.health_check_connect_port
         if not UtilClient.is_unset(request.health_check_connect_timeout):
             query['HealthCheckConnectTimeout'] = request.health_check_connect_timeout
         if not UtilClient.is_unset(request.health_check_domain):
             query['HealthCheckDomain'] = request.health_check_domain
         if not UtilClient.is_unset(request.health_check_http_code):
             query['HealthCheckHttpCode'] = request.health_check_http_code
-        if not UtilClient.is_unset(request.health_check_switch):
-            query['HealthCheckSwitch'] = request.health_check_switch
         if not UtilClient.is_unset(request.health_check_type):
             query['HealthCheckType'] = request.health_check_type
         if not UtilClient.is_unset(request.health_check_uri):
             query['HealthCheckURI'] = request.health_check_uri
         if not UtilClient.is_unset(request.healthy_threshold):
             query['HealthyThreshold'] = request.healthy_threshold
         if not UtilClient.is_unset(request.listener_port):
@@ -1661,26 +1421,22 @@
             query['MasterSlaveServerGroupId'] = request.master_slave_server_group_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.persistence_timeout):
             query['PersistenceTimeout'] = request.persistence_timeout
-        if not UtilClient.is_unset(request.proxy_protocol_v2enabled):
-            query['ProxyProtocolV2Enabled'] = request.proxy_protocol_v2enabled
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.scheduler):
             query['Scheduler'] = request.scheduler
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         if not UtilClient.is_unset(request.unhealthy_threshold):
             query['UnhealthyThreshold'] = request.unhealthy_threshold
         if not UtilClient.is_unset(request.vserver_group_id):
             query['VServerGroupId'] = request.vserver_group_id
         if not UtilClient.is_unset(request.health_check_interval):
             query['healthCheckInterval'] = request.health_check_interval
         req = open_api_models.OpenApiRequest(
@@ -1703,22 +1459,14 @@
         )
 
     async def create_load_balancer_tcplistener_with_options_async(
         self,
         request: slb_20140515_models.CreateLoadBalancerTCPListenerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.CreateLoadBalancerTCPListenerResponse:
-        """
-        The number of times that a healthy backend server must consecutively fail health checks before it is declared unhealthy. In this case, the health status is changed from *success** to **fail**.
-        Valid values: **2** to **10**.
-        
-        @param request: CreateLoadBalancerTCPListenerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: CreateLoadBalancerTCPListenerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -1739,16 +1487,14 @@
             query['HealthCheckConnectPort'] = request.health_check_connect_port
         if not UtilClient.is_unset(request.health_check_connect_timeout):
             query['HealthCheckConnectTimeout'] = request.health_check_connect_timeout
         if not UtilClient.is_unset(request.health_check_domain):
             query['HealthCheckDomain'] = request.health_check_domain
         if not UtilClient.is_unset(request.health_check_http_code):
             query['HealthCheckHttpCode'] = request.health_check_http_code
-        if not UtilClient.is_unset(request.health_check_switch):
-            query['HealthCheckSwitch'] = request.health_check_switch
         if not UtilClient.is_unset(request.health_check_type):
             query['HealthCheckType'] = request.health_check_type
         if not UtilClient.is_unset(request.health_check_uri):
             query['HealthCheckURI'] = request.health_check_uri
         if not UtilClient.is_unset(request.healthy_threshold):
             query['HealthyThreshold'] = request.healthy_threshold
         if not UtilClient.is_unset(request.listener_port):
@@ -1759,26 +1505,22 @@
             query['MasterSlaveServerGroupId'] = request.master_slave_server_group_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.persistence_timeout):
             query['PersistenceTimeout'] = request.persistence_timeout
-        if not UtilClient.is_unset(request.proxy_protocol_v2enabled):
-            query['ProxyProtocolV2Enabled'] = request.proxy_protocol_v2enabled
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.scheduler):
             query['Scheduler'] = request.scheduler
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         if not UtilClient.is_unset(request.unhealthy_threshold):
             query['UnhealthyThreshold'] = request.unhealthy_threshold
         if not UtilClient.is_unset(request.vserver_group_id):
             query['VServerGroupId'] = request.vserver_group_id
         if not UtilClient.is_unset(request.health_check_interval):
             query['healthCheckInterval'] = request.health_check_interval
         req = open_api_models.OpenApiRequest(
@@ -1800,52 +1542,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def create_load_balancer_tcplistener(
         self,
         request: slb_20140515_models.CreateLoadBalancerTCPListenerRequest,
     ) -> slb_20140515_models.CreateLoadBalancerTCPListenerResponse:
-        """
-        The number of times that a healthy backend server must consecutively fail health checks before it is declared unhealthy. In this case, the health status is changed from *success** to **fail**.
-        Valid values: **2** to **10**.
-        
-        @param request: CreateLoadBalancerTCPListenerRequest
-        @return: CreateLoadBalancerTCPListenerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.create_load_balancer_tcplistener_with_options(request, runtime)
 
     async def create_load_balancer_tcplistener_async(
         self,
         request: slb_20140515_models.CreateLoadBalancerTCPListenerRequest,
     ) -> slb_20140515_models.CreateLoadBalancerTCPListenerResponse:
-        """
-        The number of times that a healthy backend server must consecutively fail health checks before it is declared unhealthy. In this case, the health status is changed from *success** to **fail**.
-        Valid values: **2** to **10**.
-        
-        @param request: CreateLoadBalancerTCPListenerRequest
-        @return: CreateLoadBalancerTCPListenerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.create_load_balancer_tcplistener_with_options_async(request, runtime)
 
     def create_load_balancer_udplistener_with_options(
         self,
         request: slb_20140515_models.CreateLoadBalancerUDPListenerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.CreateLoadBalancerUDPListenerResponse:
-        """
-        The port that is used for health checks.
-        Valid values: **1** to **65535**.
-        If this parameter is not set, the backend port specified by **BackendServerPort** is used for health checks.
-        
-        @param request: CreateLoadBalancerUDPListenerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: CreateLoadBalancerUDPListenerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -1856,40 +1575,34 @@
             query['Bandwidth'] = request.bandwidth
         if not UtilClient.is_unset(request.description):
             query['Description'] = request.description
         if not UtilClient.is_unset(request.health_check_connect_port):
             query['HealthCheckConnectPort'] = request.health_check_connect_port
         if not UtilClient.is_unset(request.health_check_connect_timeout):
             query['HealthCheckConnectTimeout'] = request.health_check_connect_timeout
-        if not UtilClient.is_unset(request.health_check_switch):
-            query['HealthCheckSwitch'] = request.health_check_switch
         if not UtilClient.is_unset(request.healthy_threshold):
             query['HealthyThreshold'] = request.healthy_threshold
         if not UtilClient.is_unset(request.listener_port):
             query['ListenerPort'] = request.listener_port
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.master_slave_server_group_id):
             query['MasterSlaveServerGroupId'] = request.master_slave_server_group_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.proxy_protocol_v2enabled):
-            query['ProxyProtocolV2Enabled'] = request.proxy_protocol_v2enabled
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.scheduler):
             query['Scheduler'] = request.scheduler
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         if not UtilClient.is_unset(request.unhealthy_threshold):
             query['UnhealthyThreshold'] = request.unhealthy_threshold
         if not UtilClient.is_unset(request.vserver_group_id):
             query['VServerGroupId'] = request.vserver_group_id
         if not UtilClient.is_unset(request.health_check_exp):
             query['healthCheckExp'] = request.health_check_exp
         if not UtilClient.is_unset(request.health_check_interval):
@@ -1916,23 +1629,14 @@
         )
 
     async def create_load_balancer_udplistener_with_options_async(
         self,
         request: slb_20140515_models.CreateLoadBalancerUDPListenerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.CreateLoadBalancerUDPListenerResponse:
-        """
-        The port that is used for health checks.
-        Valid values: **1** to **65535**.
-        If this parameter is not set, the backend port specified by **BackendServerPort** is used for health checks.
-        
-        @param request: CreateLoadBalancerUDPListenerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: CreateLoadBalancerUDPListenerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -1943,40 +1647,34 @@
             query['Bandwidth'] = request.bandwidth
         if not UtilClient.is_unset(request.description):
             query['Description'] = request.description
         if not UtilClient.is_unset(request.health_check_connect_port):
             query['HealthCheckConnectPort'] = request.health_check_connect_port
         if not UtilClient.is_unset(request.health_check_connect_timeout):
             query['HealthCheckConnectTimeout'] = request.health_check_connect_timeout
-        if not UtilClient.is_unset(request.health_check_switch):
-            query['HealthCheckSwitch'] = request.health_check_switch
         if not UtilClient.is_unset(request.healthy_threshold):
             query['HealthyThreshold'] = request.healthy_threshold
         if not UtilClient.is_unset(request.listener_port):
             query['ListenerPort'] = request.listener_port
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.master_slave_server_group_id):
             query['MasterSlaveServerGroupId'] = request.master_slave_server_group_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.proxy_protocol_v2enabled):
-            query['ProxyProtocolV2Enabled'] = request.proxy_protocol_v2enabled
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.scheduler):
             query['Scheduler'] = request.scheduler
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         if not UtilClient.is_unset(request.unhealthy_threshold):
             query['UnhealthyThreshold'] = request.unhealthy_threshold
         if not UtilClient.is_unset(request.vserver_group_id):
             query['VServerGroupId'] = request.vserver_group_id
         if not UtilClient.is_unset(request.health_check_exp):
             query['healthCheckExp'] = request.health_check_exp
         if not UtilClient.is_unset(request.health_check_interval):
@@ -2002,37 +1700,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def create_load_balancer_udplistener(
         self,
         request: slb_20140515_models.CreateLoadBalancerUDPListenerRequest,
     ) -> slb_20140515_models.CreateLoadBalancerUDPListenerResponse:
-        """
-        The port that is used for health checks.
-        Valid values: **1** to **65535**.
-        If this parameter is not set, the backend port specified by **BackendServerPort** is used for health checks.
-        
-        @param request: CreateLoadBalancerUDPListenerRequest
-        @return: CreateLoadBalancerUDPListenerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.create_load_balancer_udplistener_with_options(request, runtime)
 
     async def create_load_balancer_udplistener_async(
         self,
         request: slb_20140515_models.CreateLoadBalancerUDPListenerRequest,
     ) -> slb_20140515_models.CreateLoadBalancerUDPListenerResponse:
-        """
-        The port that is used for health checks.
-        Valid values: **1** to **65535**.
-        If this parameter is not set, the backend port specified by **BackendServerPort** is used for health checks.
-        
-        @param request: CreateLoadBalancerUDPListenerRequest
-        @return: CreateLoadBalancerUDPListenerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.create_load_balancer_udplistener_with_options_async(request, runtime)
 
     def create_master_slave_server_group_with_options(
         self,
         request: slb_20140515_models.CreateMasterSlaveServerGroupRequest,
         runtime: util_models.RuntimeOptions,
@@ -2051,16 +1733,14 @@
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='CreateMasterSlaveServerGroup',
             version='2014-05-15',
             protocol='HTTPS',
@@ -2095,16 +1775,14 @@
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='CreateMasterSlaveServerGroup',
             version='2014-05-15',
             protocol='HTTPS',
@@ -2255,14 +1933,16 @@
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.tlsversions):
             query['TLSVersions'] = request.tlsversions
+        if not UtilClient.is_unset(request.access_key_id):
+            query['access_key_id'] = request.access_key_id
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='CreateTLSCipherPolicy',
             version='2014-05-15',
             protocol='HTTPS',
@@ -2297,14 +1977,16 @@
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.tlsversions):
             query['TLSVersions'] = request.tlsversions
+        if not UtilClient.is_unset(request.access_key_id):
+            query['access_key_id'] = request.access_key_id
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='CreateTLSCipherPolicy',
             version='2014-05-15',
             protocol='HTTPS',
@@ -2351,16 +2033,14 @@
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         if not UtilClient.is_unset(request.vserver_group_name):
             query['VServerGroupName'] = request.vserver_group_name
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='CreateVServerGroup',
@@ -2395,16 +2075,14 @@
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         if not UtilClient.is_unset(request.vserver_group_name):
             query['VServerGroupName'] = request.vserver_group_name
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='CreateVServerGroup',
@@ -2437,22 +2115,14 @@
         return await self.create_vserver_group_with_options_async(request, runtime)
 
     def delete_access_control_list_with_options(
         self,
         request: slb_20140515_models.DeleteAccessControlListRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DeleteAccessControlListResponse:
-        """
-        The ID of the region to which the access control list belongs.
-        To query the region ID, call [DescribeRegions](~~27584~~).
-        
-        @param request: DeleteAccessControlListRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DeleteAccessControlListResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -2483,22 +2153,14 @@
         )
 
     async def delete_access_control_list_with_options_async(
         self,
         request: slb_20140515_models.DeleteAccessControlListRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DeleteAccessControlListResponse:
-        """
-        The ID of the region to which the access control list belongs.
-        To query the region ID, call [DescribeRegions](~~27584~~).
-        
-        @param request: DeleteAccessControlListRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DeleteAccessControlListResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -2528,149 +2190,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def delete_access_control_list(
         self,
         request: slb_20140515_models.DeleteAccessControlListRequest,
     ) -> slb_20140515_models.DeleteAccessControlListResponse:
-        """
-        The ID of the region to which the access control list belongs.
-        To query the region ID, call [DescribeRegions](~~27584~~).
-        
-        @param request: DeleteAccessControlListRequest
-        @return: DeleteAccessControlListResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.delete_access_control_list_with_options(request, runtime)
 
     async def delete_access_control_list_async(
         self,
         request: slb_20140515_models.DeleteAccessControlListRequest,
     ) -> slb_20140515_models.DeleteAccessControlListResponse:
-        """
-        The ID of the region to which the access control list belongs.
-        To query the region ID, call [DescribeRegions](~~27584~~).
-        
-        @param request: DeleteAccessControlListRequest
-        @return: DeleteAccessControlListResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.delete_access_control_list_with_options_async(request, runtime)
 
-    def delete_access_logs_download_attribute_with_options(
-        self,
-        request: slb_20140515_models.DeleteAccessLogsDownloadAttributeRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.DeleteAccessLogsDownloadAttributeResponse:
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.load_balancer_id):
-            query['LoadBalancerId'] = request.load_balancer_id
-        if not UtilClient.is_unset(request.logs_download_attributes):
-            query['LogsDownloadAttributes'] = request.logs_download_attributes
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tags):
-            query['Tags'] = request.tags
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='DeleteAccessLogsDownloadAttribute',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.DeleteAccessLogsDownloadAttributeResponse(),
-            self.call_api(params, req, runtime)
-        )
-
-    async def delete_access_logs_download_attribute_with_options_async(
-        self,
-        request: slb_20140515_models.DeleteAccessLogsDownloadAttributeRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.DeleteAccessLogsDownloadAttributeResponse:
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.load_balancer_id):
-            query['LoadBalancerId'] = request.load_balancer_id
-        if not UtilClient.is_unset(request.logs_download_attributes):
-            query['LogsDownloadAttributes'] = request.logs_download_attributes
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tags):
-            query['Tags'] = request.tags
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='DeleteAccessLogsDownloadAttribute',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.DeleteAccessLogsDownloadAttributeResponse(),
-            await self.call_api_async(params, req, runtime)
-        )
-
-    def delete_access_logs_download_attribute(
-        self,
-        request: slb_20140515_models.DeleteAccessLogsDownloadAttributeRequest,
-    ) -> slb_20140515_models.DeleteAccessLogsDownloadAttributeResponse:
-        runtime = util_models.RuntimeOptions()
-        return self.delete_access_logs_download_attribute_with_options(request, runtime)
-
-    async def delete_access_logs_download_attribute_async(
-        self,
-        request: slb_20140515_models.DeleteAccessLogsDownloadAttributeRequest,
-    ) -> slb_20140515_models.DeleteAccessLogsDownloadAttributeResponse:
-        runtime = util_models.RuntimeOptions()
-        return await self.delete_access_logs_download_attribute_with_options_async(request, runtime)
-
     def delete_cacertificate_with_options(
         self,
         request: slb_20140515_models.DeleteCACertificateRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DeleteCACertificateResponse:
-        """
-        The region to which the CA certificate belongs.
-        To query the region ID, call [DescribeRegions](~~27584~~).
-        
-        @param request: DeleteCACertificateRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DeleteCACertificateResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.cacertificate_id):
             query['CACertificateId'] = request.cacertificate_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -2701,22 +2243,14 @@
         )
 
     async def delete_cacertificate_with_options_async(
         self,
         request: slb_20140515_models.DeleteCACertificateRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DeleteCACertificateResponse:
-        """
-        The region to which the CA certificate belongs.
-        To query the region ID, call [DescribeRegions](~~27584~~).
-        
-        @param request: DeleteCACertificateRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DeleteCACertificateResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.cacertificate_id):
             query['CACertificateId'] = request.cacertificate_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -2746,35 +2280,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def delete_cacertificate(
         self,
         request: slb_20140515_models.DeleteCACertificateRequest,
     ) -> slb_20140515_models.DeleteCACertificateResponse:
-        """
-        The region to which the CA certificate belongs.
-        To query the region ID, call [DescribeRegions](~~27584~~).
-        
-        @param request: DeleteCACertificateRequest
-        @return: DeleteCACertificateResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.delete_cacertificate_with_options(request, runtime)
 
     async def delete_cacertificate_async(
         self,
         request: slb_20140515_models.DeleteCACertificateRequest,
     ) -> slb_20140515_models.DeleteCACertificateResponse:
-        """
-        The region to which the CA certificate belongs.
-        To query the region ID, call [DescribeRegions](~~27584~~).
-        
-        @param request: DeleteCACertificateRequest
-        @return: DeleteCACertificateResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.delete_cacertificate_with_options_async(request, runtime)
 
     def delete_domain_extension_with_options(
         self,
         request: slb_20140515_models.DeleteDomainExtensionRequest,
         runtime: util_models.RuntimeOptions,
@@ -2865,22 +2385,14 @@
         return await self.delete_domain_extension_with_options_async(request, runtime)
 
     def delete_load_balancer_with_options(
         self,
         request: slb_20140515_models.DeleteLoadBalancerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DeleteLoadBalancerResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **DeleteLoadBalancer**.
-        
-        @param request: DeleteLoadBalancerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DeleteLoadBalancerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -2911,22 +2423,14 @@
         )
 
     async def delete_load_balancer_with_options_async(
         self,
         request: slb_20140515_models.DeleteLoadBalancerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DeleteLoadBalancerResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **DeleteLoadBalancer**.
-        
-        @param request: DeleteLoadBalancerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DeleteLoadBalancerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -2956,50 +2460,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def delete_load_balancer(
         self,
         request: slb_20140515_models.DeleteLoadBalancerRequest,
     ) -> slb_20140515_models.DeleteLoadBalancerResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **DeleteLoadBalancer**.
-        
-        @param request: DeleteLoadBalancerRequest
-        @return: DeleteLoadBalancerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.delete_load_balancer_with_options(request, runtime)
 
     async def delete_load_balancer_async(
         self,
         request: slb_20140515_models.DeleteLoadBalancerRequest,
     ) -> slb_20140515_models.DeleteLoadBalancerResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **DeleteLoadBalancer**.
-        
-        @param request: DeleteLoadBalancerRequest
-        @return: DeleteLoadBalancerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.delete_load_balancer_with_options_async(request, runtime)
 
     def delete_load_balancer_listener_with_options(
         self,
         request: slb_20140515_models.DeleteLoadBalancerListenerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DeleteLoadBalancerListenerResponse:
-        """
-        >  You can delete only listeners that are in the *stopped** or **running** state.
-        
-        @param request: DeleteLoadBalancerListenerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DeleteLoadBalancerListenerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.listener_port):
             query['ListenerPort'] = request.listener_port
         if not UtilClient.is_unset(request.listener_protocol):
             query['ListenerProtocol'] = request.listener_protocol
         if not UtilClient.is_unset(request.load_balancer_id):
@@ -3034,21 +2517,14 @@
         )
 
     async def delete_load_balancer_listener_with_options_async(
         self,
         request: slb_20140515_models.DeleteLoadBalancerListenerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DeleteLoadBalancerListenerResponse:
-        """
-        >  You can delete only listeners that are in the *stopped** or **running** state.
-        
-        @param request: DeleteLoadBalancerListenerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DeleteLoadBalancerListenerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.listener_port):
             query['ListenerPort'] = request.listener_port
         if not UtilClient.is_unset(request.listener_protocol):
             query['ListenerProtocol'] = request.listener_protocol
         if not UtilClient.is_unset(request.load_balancer_id):
@@ -3082,33 +2558,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def delete_load_balancer_listener(
         self,
         request: slb_20140515_models.DeleteLoadBalancerListenerRequest,
     ) -> slb_20140515_models.DeleteLoadBalancerListenerResponse:
-        """
-        >  You can delete only listeners that are in the *stopped** or **running** state.
-        
-        @param request: DeleteLoadBalancerListenerRequest
-        @return: DeleteLoadBalancerListenerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.delete_load_balancer_listener_with_options(request, runtime)
 
     async def delete_load_balancer_listener_async(
         self,
         request: slb_20140515_models.DeleteLoadBalancerListenerRequest,
     ) -> slb_20140515_models.DeleteLoadBalancerListenerResponse:
-        """
-        >  You can delete only listeners that are in the *stopped** or **running** state.
-        
-        @param request: DeleteLoadBalancerListenerRequest
-        @return: DeleteLoadBalancerListenerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.delete_load_balancer_listener_with_options_async(request, runtime)
 
     def delete_master_slave_server_group_with_options(
         self,
         request: slb_20140515_models.DeleteMasterSlaveServerGroupRequest,
         runtime: util_models.RuntimeOptions,
@@ -3199,22 +2663,14 @@
         return await self.delete_master_slave_server_group_with_options_async(request, runtime)
 
     def delete_rules_with_options(
         self,
         request: slb_20140515_models.DeleteRulesRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DeleteRulesResponse:
-        """
-        The ID of the region where the Server Load Balancer (SLB) instance is deployed.
-        You can call the [DescribeRegions](~~27584~~) operation to query region IDs.
-        
-        @param request: DeleteRulesRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DeleteRulesResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
@@ -3245,22 +2701,14 @@
         )
 
     async def delete_rules_with_options_async(
         self,
         request: slb_20140515_models.DeleteRulesRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DeleteRulesResponse:
-        """
-        The ID of the region where the Server Load Balancer (SLB) instance is deployed.
-        You can call the [DescribeRegions](~~27584~~) operation to query region IDs.
-        
-        @param request: DeleteRulesRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DeleteRulesResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
@@ -3290,51 +2738,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def delete_rules(
         self,
         request: slb_20140515_models.DeleteRulesRequest,
     ) -> slb_20140515_models.DeleteRulesResponse:
-        """
-        The ID of the region where the Server Load Balancer (SLB) instance is deployed.
-        You can call the [DescribeRegions](~~27584~~) operation to query region IDs.
-        
-        @param request: DeleteRulesRequest
-        @return: DeleteRulesResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.delete_rules_with_options(request, runtime)
 
     async def delete_rules_async(
         self,
         request: slb_20140515_models.DeleteRulesRequest,
     ) -> slb_20140515_models.DeleteRulesResponse:
-        """
-        The ID of the region where the Server Load Balancer (SLB) instance is deployed.
-        You can call the [DescribeRegions](~~27584~~) operation to query region IDs.
-        
-        @param request: DeleteRulesRequest
-        @return: DeleteRulesResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.delete_rules_with_options_async(request, runtime)
 
     def delete_server_certificate_with_options(
         self,
         request: slb_20140515_models.DeleteServerCertificateRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DeleteServerCertificateResponse:
-        """
-        The region where the Server Load Balancer (SLB) instance is created.
-        You can call the [DescribeRegions](~~27584~~) operation to query region IDs.
-        
-        @param request: DeleteServerCertificateRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DeleteServerCertificateResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
@@ -3365,22 +2791,14 @@
         )
 
     async def delete_server_certificate_with_options_async(
         self,
         request: slb_20140515_models.DeleteServerCertificateRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DeleteServerCertificateResponse:
-        """
-        The region where the Server Load Balancer (SLB) instance is created.
-        You can call the [DescribeRegions](~~27584~~) operation to query region IDs.
-        
-        @param request: DeleteServerCertificateRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DeleteServerCertificateResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
@@ -3410,35 +2828,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def delete_server_certificate(
         self,
         request: slb_20140515_models.DeleteServerCertificateRequest,
     ) -> slb_20140515_models.DeleteServerCertificateResponse:
-        """
-        The region where the Server Load Balancer (SLB) instance is created.
-        You can call the [DescribeRegions](~~27584~~) operation to query region IDs.
-        
-        @param request: DeleteServerCertificateRequest
-        @return: DeleteServerCertificateResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.delete_server_certificate_with_options(request, runtime)
 
     async def delete_server_certificate_async(
         self,
         request: slb_20140515_models.DeleteServerCertificateRequest,
     ) -> slb_20140515_models.DeleteServerCertificateResponse:
-        """
-        The region where the Server Load Balancer (SLB) instance is created.
-        You can call the [DescribeRegions](~~27584~~) operation to query region IDs.
-        
-        @param request: DeleteServerCertificateRequest
-        @return: DeleteServerCertificateResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.delete_server_certificate_with_options_async(request, runtime)
 
     def delete_tlscipher_policy_with_options(
         self,
         request: slb_20140515_models.DeleteTLSCipherPolicyRequest,
         runtime: util_models.RuntimeOptions,
@@ -3453,14 +2857,16 @@
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.tlscipher_policy_id):
             query['TLSCipherPolicyId'] = request.tlscipher_policy_id
+        if not UtilClient.is_unset(request.access_key_id):
+            query['access_key_id'] = request.access_key_id
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='DeleteTLSCipherPolicy',
             version='2014-05-15',
             protocol='HTTPS',
@@ -3491,14 +2897,16 @@
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.tlscipher_policy_id):
             query['TLSCipherPolicyId'] = request.tlscipher_policy_id
+        if not UtilClient.is_unset(request.access_key_id):
+            query['access_key_id'] = request.access_key_id
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='DeleteTLSCipherPolicy',
             version='2014-05-15',
             protocol='HTTPS',
@@ -3629,18 +3037,14 @@
             query['AclEntryComment'] = request.acl_entry_comment
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.page):
-            query['Page'] = request.page
-        if not UtilClient.is_unset(request.page_size):
-            query['PageSize'] = request.page_size
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         req = open_api_models.OpenApiRequest(
@@ -3673,18 +3077,14 @@
             query['AclEntryComment'] = request.acl_entry_comment
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.page):
-            query['Page'] = request.page
-        if not UtilClient.is_unset(request.page_size):
-            query['PageSize'] = request.page_size
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         req = open_api_models.OpenApiRequest(
@@ -3822,132 +3222,19 @@
     async def describe_access_control_lists_async(
         self,
         request: slb_20140515_models.DescribeAccessControlListsRequest,
     ) -> slb_20140515_models.DescribeAccessControlListsResponse:
         runtime = util_models.RuntimeOptions()
         return await self.describe_access_control_lists_with_options_async(request, runtime)
 
-    def describe_access_logs_download_attribute_with_options(
-        self,
-        request: slb_20140515_models.DescribeAccessLogsDownloadAttributeRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.DescribeAccessLogsDownloadAttributeResponse:
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.load_balancer_id):
-            query['LoadBalancerId'] = request.load_balancer_id
-        if not UtilClient.is_unset(request.log_type):
-            query['LogType'] = request.log_type
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.page_number):
-            query['PageNumber'] = request.page_number
-        if not UtilClient.is_unset(request.page_size):
-            query['PageSize'] = request.page_size
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tags):
-            query['Tags'] = request.tags
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='DescribeAccessLogsDownloadAttribute',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.DescribeAccessLogsDownloadAttributeResponse(),
-            self.call_api(params, req, runtime)
-        )
-
-    async def describe_access_logs_download_attribute_with_options_async(
-        self,
-        request: slb_20140515_models.DescribeAccessLogsDownloadAttributeRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.DescribeAccessLogsDownloadAttributeResponse:
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.load_balancer_id):
-            query['LoadBalancerId'] = request.load_balancer_id
-        if not UtilClient.is_unset(request.log_type):
-            query['LogType'] = request.log_type
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.page_number):
-            query['PageNumber'] = request.page_number
-        if not UtilClient.is_unset(request.page_size):
-            query['PageSize'] = request.page_size
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tags):
-            query['Tags'] = request.tags
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='DescribeAccessLogsDownloadAttribute',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.DescribeAccessLogsDownloadAttributeResponse(),
-            await self.call_api_async(params, req, runtime)
-        )
-
-    def describe_access_logs_download_attribute(
-        self,
-        request: slb_20140515_models.DescribeAccessLogsDownloadAttributeRequest,
-    ) -> slb_20140515_models.DescribeAccessLogsDownloadAttributeResponse:
-        runtime = util_models.RuntimeOptions()
-        return self.describe_access_logs_download_attribute_with_options(request, runtime)
-
-    async def describe_access_logs_download_attribute_async(
-        self,
-        request: slb_20140515_models.DescribeAccessLogsDownloadAttributeRequest,
-    ) -> slb_20140515_models.DescribeAccessLogsDownloadAttributeResponse:
-        runtime = util_models.RuntimeOptions()
-        return await self.describe_access_logs_download_attribute_with_options_async(request, runtime)
-
     def describe_available_resource_with_options(
         self,
         request: slb_20140515_models.DescribeAvailableResourceRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeAvailableResourceResponse:
-        """
-        The ID of the region.
-        
-        @param request: DescribeAvailableResourceRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeAvailableResourceResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.address_ipversion):
             query['AddressIPVersion'] = request.address_ipversion
         if not UtilClient.is_unset(request.address_type):
             query['AddressType'] = request.address_type
         if not UtilClient.is_unset(request.owner_account):
@@ -3980,21 +3267,14 @@
         )
 
     async def describe_available_resource_with_options_async(
         self,
         request: slb_20140515_models.DescribeAvailableResourceRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeAvailableResourceResponse:
-        """
-        The ID of the region.
-        
-        @param request: DescribeAvailableResourceRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeAvailableResourceResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.address_ipversion):
             query['AddressIPVersion'] = request.address_ipversion
         if not UtilClient.is_unset(request.address_type):
             query['AddressType'] = request.address_type
         if not UtilClient.is_unset(request.owner_account):
@@ -4026,48 +3306,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def describe_available_resource(
         self,
         request: slb_20140515_models.DescribeAvailableResourceRequest,
     ) -> slb_20140515_models.DescribeAvailableResourceResponse:
-        """
-        The ID of the region.
-        
-        @param request: DescribeAvailableResourceRequest
-        @return: DescribeAvailableResourceResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.describe_available_resource_with_options(request, runtime)
 
     async def describe_available_resource_async(
         self,
         request: slb_20140515_models.DescribeAvailableResourceRequest,
     ) -> slb_20140515_models.DescribeAvailableResourceResponse:
-        """
-        The ID of the region.
-        
-        @param request: DescribeAvailableResourceRequest
-        @return: DescribeAvailableResourceResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.describe_available_resource_with_options_async(request, runtime)
 
     def describe_cacertificates_with_options(
         self,
         request: slb_20140515_models.DescribeCACertificatesRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeCACertificatesResponse:
-        """
-        The time when the CA certificate was created. The time is in the `YYYY-MM-DDThh:mm:ssZ` format.
-        
-        @param request: DescribeCACertificatesRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeCACertificatesResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.cacertificate_id):
             query['CACertificateId'] = request.cacertificate_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -4100,21 +3361,14 @@
         )
 
     async def describe_cacertificates_with_options_async(
         self,
         request: slb_20140515_models.DescribeCACertificatesRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeCACertificatesResponse:
-        """
-        The time when the CA certificate was created. The time is in the `YYYY-MM-DDThh:mm:ssZ` format.
-        
-        @param request: DescribeCACertificatesRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeCACertificatesResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.cacertificate_id):
             query['CACertificateId'] = request.cacertificate_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -4146,33 +3400,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def describe_cacertificates(
         self,
         request: slb_20140515_models.DescribeCACertificatesRequest,
     ) -> slb_20140515_models.DescribeCACertificatesResponse:
-        """
-        The time when the CA certificate was created. The time is in the `YYYY-MM-DDThh:mm:ssZ` format.
-        
-        @param request: DescribeCACertificatesRequest
-        @return: DescribeCACertificatesResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.describe_cacertificates_with_options(request, runtime)
 
     async def describe_cacertificates_async(
         self,
         request: slb_20140515_models.DescribeCACertificatesRequest,
     ) -> slb_20140515_models.DescribeCACertificatesResponse:
-        """
-        The time when the CA certificate was created. The time is in the `YYYY-MM-DDThh:mm:ssZ` format.
-        
-        @param request: DescribeCACertificatesRequest
-        @return: DescribeCACertificatesResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.describe_cacertificates_with_options_async(request, runtime)
 
     def describe_domain_extension_attribute_with_options(
         self,
         request: slb_20140515_models.DescribeDomainExtensionAttributeRequest,
         runtime: util_models.RuntimeOptions,
@@ -4454,104 +3696,14 @@
     async def describe_health_status_async(
         self,
         request: slb_20140515_models.DescribeHealthStatusRequest,
     ) -> slb_20140515_models.DescribeHealthStatusResponse:
         runtime = util_models.RuntimeOptions()
         return await self.describe_health_status_with_options_async(request, runtime)
 
-    def describe_high_defination_monitor_with_options(
-        self,
-        request: slb_20140515_models.DescribeHighDefinationMonitorRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.DescribeHighDefinationMonitorResponse:
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tags):
-            query['Tags'] = request.tags
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='DescribeHighDefinationMonitor',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.DescribeHighDefinationMonitorResponse(),
-            self.call_api(params, req, runtime)
-        )
-
-    async def describe_high_defination_monitor_with_options_async(
-        self,
-        request: slb_20140515_models.DescribeHighDefinationMonitorRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.DescribeHighDefinationMonitorResponse:
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tags):
-            query['Tags'] = request.tags
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='DescribeHighDefinationMonitor',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.DescribeHighDefinationMonitorResponse(),
-            await self.call_api_async(params, req, runtime)
-        )
-
-    def describe_high_defination_monitor(
-        self,
-        request: slb_20140515_models.DescribeHighDefinationMonitorRequest,
-    ) -> slb_20140515_models.DescribeHighDefinationMonitorResponse:
-        runtime = util_models.RuntimeOptions()
-        return self.describe_high_defination_monitor_with_options(request, runtime)
-
-    async def describe_high_defination_monitor_async(
-        self,
-        request: slb_20140515_models.DescribeHighDefinationMonitorRequest,
-    ) -> slb_20140515_models.DescribeHighDefinationMonitorResponse:
-        runtime = util_models.RuntimeOptions()
-        return await self.describe_high_defination_monitor_with_options_async(request, runtime)
-
     def describe_listener_access_control_attribute_with_options(
         self,
         request: slb_20140515_models.DescribeListenerAccessControlAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeListenerAccessControlAttributeResponse:
         UtilClient.validate_model(request)
         query = {}
@@ -4647,23 +3799,14 @@
         return await self.describe_listener_access_control_attribute_with_options_async(request, runtime)
 
     def describe_load_balancer_attribute_with_options(
         self,
         request: slb_20140515_models.DescribeLoadBalancerAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeLoadBalancerAttributeResponse:
-        """
-        The metering method of the CLB instance. Valid values:
-        *   **PayBySpec:** pay-by-specification.
-        *   **PayByCLCU:** pay-by-LCU.
-        
-        @param request: DescribeLoadBalancerAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeLoadBalancerAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -4694,23 +3837,14 @@
         )
 
     async def describe_load_balancer_attribute_with_options_async(
         self,
         request: slb_20140515_models.DescribeLoadBalancerAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeLoadBalancerAttributeResponse:
-        """
-        The metering method of the CLB instance. Valid values:
-        *   **PayBySpec:** pay-by-specification.
-        *   **PayByCLCU:** pay-by-LCU.
-        
-        @param request: DescribeLoadBalancerAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeLoadBalancerAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -4740,52 +3874,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def describe_load_balancer_attribute(
         self,
         request: slb_20140515_models.DescribeLoadBalancerAttributeRequest,
     ) -> slb_20140515_models.DescribeLoadBalancerAttributeResponse:
-        """
-        The metering method of the CLB instance. Valid values:
-        *   **PayBySpec:** pay-by-specification.
-        *   **PayByCLCU:** pay-by-LCU.
-        
-        @param request: DescribeLoadBalancerAttributeRequest
-        @return: DescribeLoadBalancerAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.describe_load_balancer_attribute_with_options(request, runtime)
 
     async def describe_load_balancer_attribute_async(
         self,
         request: slb_20140515_models.DescribeLoadBalancerAttributeRequest,
     ) -> slb_20140515_models.DescribeLoadBalancerAttributeResponse:
-        """
-        The metering method of the CLB instance. Valid values:
-        *   **PayBySpec:** pay-by-specification.
-        *   **PayByCLCU:** pay-by-LCU.
-        
-        @param request: DescribeLoadBalancerAttributeRequest
-        @return: DescribeLoadBalancerAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.describe_load_balancer_attribute_with_options_async(request, runtime)
 
     def describe_load_balancer_httplistener_attribute_with_options(
         self,
         request: slb_20140515_models.DescribeLoadBalancerHTTPListenerAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeLoadBalancerHTTPListenerAttributeResponse:
-        """
-        The HTTP status codes that are used to determine whether the backend server passes the health check.
-        
-        @param request: DescribeLoadBalancerHTTPListenerAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeLoadBalancerHTTPListenerAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.listener_port):
             query['ListenerPort'] = request.listener_port
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
@@ -4818,21 +3929,14 @@
         )
 
     async def describe_load_balancer_httplistener_attribute_with_options_async(
         self,
         request: slb_20140515_models.DescribeLoadBalancerHTTPListenerAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeLoadBalancerHTTPListenerAttributeResponse:
-        """
-        The HTTP status codes that are used to determine whether the backend server passes the health check.
-        
-        @param request: DescribeLoadBalancerHTTPListenerAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeLoadBalancerHTTPListenerAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.listener_port):
             query['ListenerPort'] = request.listener_port
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
@@ -4864,50 +3968,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def describe_load_balancer_httplistener_attribute(
         self,
         request: slb_20140515_models.DescribeLoadBalancerHTTPListenerAttributeRequest,
     ) -> slb_20140515_models.DescribeLoadBalancerHTTPListenerAttributeResponse:
-        """
-        The HTTP status codes that are used to determine whether the backend server passes the health check.
-        
-        @param request: DescribeLoadBalancerHTTPListenerAttributeRequest
-        @return: DescribeLoadBalancerHTTPListenerAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.describe_load_balancer_httplistener_attribute_with_options(request, runtime)
 
     async def describe_load_balancer_httplistener_attribute_async(
         self,
         request: slb_20140515_models.DescribeLoadBalancerHTTPListenerAttributeRequest,
     ) -> slb_20140515_models.DescribeLoadBalancerHTTPListenerAttributeResponse:
-        """
-        The HTTP status codes that are used to determine whether the backend server passes the health check.
-        
-        @param request: DescribeLoadBalancerHTTPListenerAttributeRequest
-        @return: DescribeLoadBalancerHTTPListenerAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.describe_load_balancer_httplistener_attribute_with_options_async(request, runtime)
 
     def describe_load_balancer_httpslistener_attribute_with_options(
         self,
         request: slb_20140515_models.DescribeLoadBalancerHTTPSListenerAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeLoadBalancerHTTPSListenerAttributeResponse:
-        """
-        Indicates whether the `XForwardedFor_ClientCertClientVerify` header is used to retrieve the verification result of the client certificate. Valid values:
-        *   **on**: yes
-        *   **off**: no
-        
-        @param request: DescribeLoadBalancerHTTPSListenerAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeLoadBalancerHTTPSListenerAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.listener_port):
             query['ListenerPort'] = request.listener_port
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
@@ -4940,23 +4023,14 @@
         )
 
     async def describe_load_balancer_httpslistener_attribute_with_options_async(
         self,
         request: slb_20140515_models.DescribeLoadBalancerHTTPSListenerAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeLoadBalancerHTTPSListenerAttributeResponse:
-        """
-        Indicates whether the `XForwardedFor_ClientCertClientVerify` header is used to retrieve the verification result of the client certificate. Valid values:
-        *   **on**: yes
-        *   **off**: no
-        
-        @param request: DescribeLoadBalancerHTTPSListenerAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeLoadBalancerHTTPSListenerAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.listener_port):
             query['ListenerPort'] = request.listener_port
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
@@ -4988,54 +4062,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def describe_load_balancer_httpslistener_attribute(
         self,
         request: slb_20140515_models.DescribeLoadBalancerHTTPSListenerAttributeRequest,
     ) -> slb_20140515_models.DescribeLoadBalancerHTTPSListenerAttributeResponse:
-        """
-        Indicates whether the `XForwardedFor_ClientCertClientVerify` header is used to retrieve the verification result of the client certificate. Valid values:
-        *   **on**: yes
-        *   **off**: no
-        
-        @param request: DescribeLoadBalancerHTTPSListenerAttributeRequest
-        @return: DescribeLoadBalancerHTTPSListenerAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.describe_load_balancer_httpslistener_attribute_with_options(request, runtime)
 
     async def describe_load_balancer_httpslistener_attribute_async(
         self,
         request: slb_20140515_models.DescribeLoadBalancerHTTPSListenerAttributeRequest,
     ) -> slb_20140515_models.DescribeLoadBalancerHTTPSListenerAttributeResponse:
-        """
-        Indicates whether the `XForwardedFor_ClientCertClientVerify` header is used to retrieve the verification result of the client certificate. Valid values:
-        *   **on**: yes
-        *   **off**: no
-        
-        @param request: DescribeLoadBalancerHTTPSListenerAttributeRequest
-        @return: DescribeLoadBalancerHTTPSListenerAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.describe_load_balancer_httpslistener_attribute_with_options_async(request, runtime)
 
     def describe_load_balancer_listeners_with_options(
         self,
         request: slb_20140515_models.DescribeLoadBalancerListenersRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeLoadBalancerListenersResponse:
-        """
-        Indicates whether the Proxy protocol is used to pass client IP addresses to backend servers. Valid values:
-        *   **true**: yes
-        *   **false**: no
-        
-        @param request: DescribeLoadBalancerListenersRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeLoadBalancerListenersResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.listener_protocol):
             query['ListenerProtocol'] = request.listener_protocol
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.max_results):
@@ -5048,16 +4097,14 @@
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='DescribeLoadBalancerListeners',
             version='2014-05-15',
             protocol='HTTPS',
@@ -5074,23 +4121,14 @@
         )
 
     async def describe_load_balancer_listeners_with_options_async(
         self,
         request: slb_20140515_models.DescribeLoadBalancerListenersRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeLoadBalancerListenersResponse:
-        """
-        Indicates whether the Proxy protocol is used to pass client IP addresses to backend servers. Valid values:
-        *   **true**: yes
-        *   **false**: no
-        
-        @param request: DescribeLoadBalancerListenersRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeLoadBalancerListenersResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.listener_protocol):
             query['ListenerProtocol'] = request.listener_protocol
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.max_results):
@@ -5103,16 +4141,14 @@
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='DescribeLoadBalancerListeners',
             version='2014-05-15',
             protocol='HTTPS',
@@ -5128,37 +4164,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def describe_load_balancer_listeners(
         self,
         request: slb_20140515_models.DescribeLoadBalancerListenersRequest,
     ) -> slb_20140515_models.DescribeLoadBalancerListenersResponse:
-        """
-        Indicates whether the Proxy protocol is used to pass client IP addresses to backend servers. Valid values:
-        *   **true**: yes
-        *   **false**: no
-        
-        @param request: DescribeLoadBalancerListenersRequest
-        @return: DescribeLoadBalancerListenersResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.describe_load_balancer_listeners_with_options(request, runtime)
 
     async def describe_load_balancer_listeners_async(
         self,
         request: slb_20140515_models.DescribeLoadBalancerListenersRequest,
     ) -> slb_20140515_models.DescribeLoadBalancerListenersResponse:
-        """
-        Indicates whether the Proxy protocol is used to pass client IP addresses to backend servers. Valid values:
-        *   **true**: yes
-        *   **false**: no
-        
-        @param request: DescribeLoadBalancerListenersRequest
-        @return: DescribeLoadBalancerListenersResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.describe_load_balancer_listeners_with_options_async(request, runtime)
 
     def describe_load_balancer_tcplistener_attribute_with_options(
         self,
         request: slb_20140515_models.DescribeLoadBalancerTCPListenerAttributeRequest,
         runtime: util_models.RuntimeOptions,
@@ -5615,16 +4635,14 @@
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='DescribeMasterSlaveServerGroups',
             version='2014-05-15',
             protocol='HTTPS',
@@ -5657,16 +4675,14 @@
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='DescribeMasterSlaveServerGroups',
             version='2014-05-15',
             protocol='HTTPS',
@@ -5975,21 +4991,14 @@
         return await self.describe_rules_with_options_async(request, runtime)
 
     def describe_server_certificates_with_options(
         self,
         request: slb_20140515_models.DescribeServerCertificatesRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeServerCertificatesResponse:
-        """
-        The name of the server certificate.
-        
-        @param request: DescribeServerCertificatesRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeServerCertificatesResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
@@ -6022,21 +5031,14 @@
         )
 
     async def describe_server_certificates_with_options_async(
         self,
         request: slb_20140515_models.DescribeServerCertificatesRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeServerCertificatesResponse:
-        """
-        The name of the server certificate.
-        
-        @param request: DescribeServerCertificatesRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeServerCertificatesResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
@@ -6068,53 +5070,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def describe_server_certificates(
         self,
         request: slb_20140515_models.DescribeServerCertificatesRequest,
     ) -> slb_20140515_models.DescribeServerCertificatesResponse:
-        """
-        The name of the server certificate.
-        
-        @param request: DescribeServerCertificatesRequest
-        @return: DescribeServerCertificatesResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.describe_server_certificates_with_options(request, runtime)
 
     async def describe_server_certificates_async(
         self,
         request: slb_20140515_models.DescribeServerCertificatesRequest,
     ) -> slb_20140515_models.DescribeServerCertificatesResponse:
-        """
-        The name of the server certificate.
-        
-        @param request: DescribeServerCertificatesRequest
-        @return: DescribeServerCertificatesResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.describe_server_certificates_with_options_async(request, runtime)
 
     def describe_tags_with_options(
         self,
         request: slb_20140515_models.DescribeTagsRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeTagsResponse:
-        """
-        When you call this operation, take note of the following items:
-        *   You can query tags by instance ID, tag key, and tag value. If the operation is successful, the system returns all tags that match the specified conditions.
-        *   The logical relationship among the specified conditions is AND. Only tags that match all the specified conditions are returned.
-        *   If the Tagkey parameter is set and the Tagvalue parameter is not set, all tags that contain the specified tag key are returned.
-        *   If you set the Tagvalue parameter in a request, you must also set the Tagkey parameter in the request.
-        *   If you set both the Tagkey and Tagvalue parameters, only tags that contain the specified keys and values are returned.
-        
-        @param request: DescribeTagsRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeTagsResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.distinct_key):
             query['DistinctKey'] = request.distinct_key
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
@@ -6153,26 +5131,14 @@
         )
 
     async def describe_tags_with_options_async(
         self,
         request: slb_20140515_models.DescribeTagsRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.DescribeTagsResponse:
-        """
-        When you call this operation, take note of the following items:
-        *   You can query tags by instance ID, tag key, and tag value. If the operation is successful, the system returns all tags that match the specified conditions.
-        *   The logical relationship among the specified conditions is AND. Only tags that match all the specified conditions are returned.
-        *   If the Tagkey parameter is set and the Tagvalue parameter is not set, all tags that contain the specified tag key are returned.
-        *   If you set the Tagvalue parameter in a request, you must also set the Tagkey parameter in the request.
-        *   If you set both the Tagkey and Tagvalue parameters, only tags that contain the specified keys and values are returned.
-        
-        @param request: DescribeTagsRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: DescribeTagsResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.distinct_key):
             query['DistinctKey'] = request.distinct_key
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
@@ -6210,43 +5176,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def describe_tags(
         self,
         request: slb_20140515_models.DescribeTagsRequest,
     ) -> slb_20140515_models.DescribeTagsResponse:
-        """
-        When you call this operation, take note of the following items:
-        *   You can query tags by instance ID, tag key, and tag value. If the operation is successful, the system returns all tags that match the specified conditions.
-        *   The logical relationship among the specified conditions is AND. Only tags that match all the specified conditions are returned.
-        *   If the Tagkey parameter is set and the Tagvalue parameter is not set, all tags that contain the specified tag key are returned.
-        *   If you set the Tagvalue parameter in a request, you must also set the Tagkey parameter in the request.
-        *   If you set both the Tagkey and Tagvalue parameters, only tags that contain the specified keys and values are returned.
-        
-        @param request: DescribeTagsRequest
-        @return: DescribeTagsResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.describe_tags_with_options(request, runtime)
 
     async def describe_tags_async(
         self,
         request: slb_20140515_models.DescribeTagsRequest,
     ) -> slb_20140515_models.DescribeTagsResponse:
-        """
-        When you call this operation, take note of the following items:
-        *   You can query tags by instance ID, tag key, and tag value. If the operation is successful, the system returns all tags that match the specified conditions.
-        *   The logical relationship among the specified conditions is AND. Only tags that match all the specified conditions are returned.
-        *   If the Tagkey parameter is set and the Tagvalue parameter is not set, all tags that contain the specified tag key are returned.
-        *   If you set the Tagvalue parameter in a request, you must also set the Tagkey parameter in the request.
-        *   If you set both the Tagkey and Tagvalue parameters, only tags that contain the specified keys and values are returned.
-        
-        @param request: DescribeTagsRequest
-        @return: DescribeTagsResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.describe_tags_with_options_async(request, runtime)
 
     def describe_vserver_group_attribute_with_options(
         self,
         request: slb_20140515_models.DescribeVServerGroupAttributeRequest,
         runtime: util_models.RuntimeOptions,
@@ -6355,16 +5299,14 @@
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='DescribeVServerGroups',
             version='2014-05-15',
             protocol='HTTPS',
@@ -6399,16 +5341,14 @@
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='DescribeVServerGroups',
             version='2014-05-15',
             protocol='HTTPS',
@@ -6520,112 +5460,14 @@
     async def describe_zones_async(
         self,
         request: slb_20140515_models.DescribeZonesRequest,
     ) -> slb_20140515_models.DescribeZonesResponse:
         runtime = util_models.RuntimeOptions()
         return await self.describe_zones_with_options_async(request, runtime)
 
-    def enable_high_defination_monitor_with_options(
-        self,
-        request: slb_20140515_models.EnableHighDefinationMonitorRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.EnableHighDefinationMonitorResponse:
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.log_project):
-            query['LogProject'] = request.log_project
-        if not UtilClient.is_unset(request.log_store):
-            query['LogStore'] = request.log_store
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tags):
-            query['Tags'] = request.tags
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='EnableHighDefinationMonitor',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.EnableHighDefinationMonitorResponse(),
-            self.call_api(params, req, runtime)
-        )
-
-    async def enable_high_defination_monitor_with_options_async(
-        self,
-        request: slb_20140515_models.EnableHighDefinationMonitorRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.EnableHighDefinationMonitorResponse:
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.log_project):
-            query['LogProject'] = request.log_project
-        if not UtilClient.is_unset(request.log_store):
-            query['LogStore'] = request.log_store
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tags):
-            query['Tags'] = request.tags
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='EnableHighDefinationMonitor',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.EnableHighDefinationMonitorResponse(),
-            await self.call_api_async(params, req, runtime)
-        )
-
-    def enable_high_defination_monitor(
-        self,
-        request: slb_20140515_models.EnableHighDefinationMonitorRequest,
-    ) -> slb_20140515_models.EnableHighDefinationMonitorResponse:
-        runtime = util_models.RuntimeOptions()
-        return self.enable_high_defination_monitor_with_options(request, runtime)
-
-    async def enable_high_defination_monitor_async(
-        self,
-        request: slb_20140515_models.EnableHighDefinationMonitorRequest,
-    ) -> slb_20140515_models.EnableHighDefinationMonitorResponse:
-        runtime = util_models.RuntimeOptions()
-        return await self.enable_high_defination_monitor_with_options_async(request, runtime)
-
     def list_tlscipher_policies_with_options(
         self,
         request: slb_20140515_models.ListTLSCipherPoliciesRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.ListTLSCipherPoliciesResponse:
         UtilClient.validate_model(request)
         query = {}
@@ -6645,14 +5487,16 @@
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.tlscipher_policy_id):
             query['TLSCipherPolicyId'] = request.tlscipher_policy_id
+        if not UtilClient.is_unset(request.access_key_id):
+            query['access_key_id'] = request.access_key_id
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='ListTLSCipherPolicies',
             version='2014-05-15',
             protocol='HTTPS',
@@ -6691,14 +5535,16 @@
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.tlscipher_policy_id):
             query['TLSCipherPolicyId'] = request.tlscipher_policy_id
+        if not UtilClient.is_unset(request.access_key_id):
+            query['access_key_id'] = request.access_key_id
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='ListTLSCipherPolicies',
             version='2014-05-15',
             protocol='HTTPS',
@@ -6729,24 +5575,14 @@
         return await self.list_tlscipher_policies_with_options_async(request, runtime)
 
     def list_tag_resources_with_options(
         self,
         request: slb_20140515_models.ListTagResourcesRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.ListTagResourcesResponse:
-        """
-        Set **ResourceId.N** or **Tag.N** that consists of **Tag.N.Key** and **Tag.N.Value** in the request to specify the object to be queried.
-        *   **Tag.N** is a resource tag that consists of a key-value pair. If you set only **Tag.N.Key**, all tag values that are associated with the specified tag key are returned. If you set only **Tag.N.Value**, an error message is returned.
-        *   If you set **Tag.N** and **ResourceId.N** to filter tags, **ResourceId.N** must match all specified key-value pairs.
-        *   If you specify multiple key-value pairs, resources that contain these key-value pairs are returned.
-        
-        @param request: ListTagResourcesRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: ListTagResourcesResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.next_token):
             query['NextToken'] = request.next_token
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -6783,24 +5619,14 @@
         )
 
     async def list_tag_resources_with_options_async(
         self,
         request: slb_20140515_models.ListTagResourcesRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.ListTagResourcesResponse:
-        """
-        Set **ResourceId.N** or **Tag.N** that consists of **Tag.N.Key** and **Tag.N.Value** in the request to specify the object to be queried.
-        *   **Tag.N** is a resource tag that consists of a key-value pair. If you set only **Tag.N.Key**, all tag values that are associated with the specified tag key are returned. If you set only **Tag.N.Value**, an error message is returned.
-        *   If you set **Tag.N** and **ResourceId.N** to filter tags, **ResourceId.N** must match all specified key-value pairs.
-        *   If you specify multiple key-value pairs, resources that contain these key-value pairs are returned.
-        
-        @param request: ListTagResourcesRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: ListTagResourcesResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.next_token):
             query['NextToken'] = request.next_token
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -6836,268 +5662,24 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def list_tag_resources(
         self,
         request: slb_20140515_models.ListTagResourcesRequest,
     ) -> slb_20140515_models.ListTagResourcesResponse:
-        """
-        Set **ResourceId.N** or **Tag.N** that consists of **Tag.N.Key** and **Tag.N.Value** in the request to specify the object to be queried.
-        *   **Tag.N** is a resource tag that consists of a key-value pair. If you set only **Tag.N.Key**, all tag values that are associated with the specified tag key are returned. If you set only **Tag.N.Value**, an error message is returned.
-        *   If you set **Tag.N** and **ResourceId.N** to filter tags, **ResourceId.N** must match all specified key-value pairs.
-        *   If you specify multiple key-value pairs, resources that contain these key-value pairs are returned.
-        
-        @param request: ListTagResourcesRequest
-        @return: ListTagResourcesResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.list_tag_resources_with_options(request, runtime)
 
     async def list_tag_resources_async(
         self,
         request: slb_20140515_models.ListTagResourcesRequest,
     ) -> slb_20140515_models.ListTagResourcesResponse:
-        """
-        Set **ResourceId.N** or **Tag.N** that consists of **Tag.N.Key** and **Tag.N.Value** in the request to specify the object to be queried.
-        *   **Tag.N** is a resource tag that consists of a key-value pair. If you set only **Tag.N.Key**, all tag values that are associated with the specified tag key are returned. If you set only **Tag.N.Value**, an error message is returned.
-        *   If you set **Tag.N** and **ResourceId.N** to filter tags, **ResourceId.N** must match all specified key-value pairs.
-        *   If you specify multiple key-value pairs, resources that contain these key-value pairs are returned.
-        
-        @param request: ListTagResourcesRequest
-        @return: ListTagResourcesResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.list_tag_resources_with_options_async(request, runtime)
 
-    def modify_high_defination_monitor_with_options(
-        self,
-        request: slb_20140515_models.ModifyHighDefinationMonitorRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.ModifyHighDefinationMonitorResponse:
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.log_project):
-            query['LogProject'] = request.log_project
-        if not UtilClient.is_unset(request.log_store):
-            query['LogStore'] = request.log_store
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='ModifyHighDefinationMonitor',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.ModifyHighDefinationMonitorResponse(),
-            self.call_api(params, req, runtime)
-        )
-
-    async def modify_high_defination_monitor_with_options_async(
-        self,
-        request: slb_20140515_models.ModifyHighDefinationMonitorRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.ModifyHighDefinationMonitorResponse:
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.log_project):
-            query['LogProject'] = request.log_project
-        if not UtilClient.is_unset(request.log_store):
-            query['LogStore'] = request.log_store
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='ModifyHighDefinationMonitor',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.ModifyHighDefinationMonitorResponse(),
-            await self.call_api_async(params, req, runtime)
-        )
-
-    def modify_high_defination_monitor(
-        self,
-        request: slb_20140515_models.ModifyHighDefinationMonitorRequest,
-    ) -> slb_20140515_models.ModifyHighDefinationMonitorResponse:
-        runtime = util_models.RuntimeOptions()
-        return self.modify_high_defination_monitor_with_options(request, runtime)
-
-    async def modify_high_defination_monitor_async(
-        self,
-        request: slb_20140515_models.ModifyHighDefinationMonitorRequest,
-    ) -> slb_20140515_models.ModifyHighDefinationMonitorResponse:
-        runtime = util_models.RuntimeOptions()
-        return await self.modify_high_defination_monitor_with_options_async(request, runtime)
-
-    def modify_load_balancer_instance_charge_type_with_options(
-        self,
-        request: slb_20140515_models.ModifyLoadBalancerInstanceChargeTypeRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.ModifyLoadBalancerInstanceChargeTypeResponse:
-        """
-        The ID of the CLB instance.
-        
-        @param request: ModifyLoadBalancerInstanceChargeTypeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: ModifyLoadBalancerInstanceChargeTypeResponse
-        """
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.bandwidth):
-            query['Bandwidth'] = request.bandwidth
-        if not UtilClient.is_unset(request.instance_charge_type):
-            query['InstanceChargeType'] = request.instance_charge_type
-        if not UtilClient.is_unset(request.internet_charge_type):
-            query['InternetChargeType'] = request.internet_charge_type
-        if not UtilClient.is_unset(request.load_balancer_id):
-            query['LoadBalancerId'] = request.load_balancer_id
-        if not UtilClient.is_unset(request.load_balancer_spec):
-            query['LoadBalancerSpec'] = request.load_balancer_spec
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='ModifyLoadBalancerInstanceChargeType',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.ModifyLoadBalancerInstanceChargeTypeResponse(),
-            self.call_api(params, req, runtime)
-        )
-
-    async def modify_load_balancer_instance_charge_type_with_options_async(
-        self,
-        request: slb_20140515_models.ModifyLoadBalancerInstanceChargeTypeRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.ModifyLoadBalancerInstanceChargeTypeResponse:
-        """
-        The ID of the CLB instance.
-        
-        @param request: ModifyLoadBalancerInstanceChargeTypeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: ModifyLoadBalancerInstanceChargeTypeResponse
-        """
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.bandwidth):
-            query['Bandwidth'] = request.bandwidth
-        if not UtilClient.is_unset(request.instance_charge_type):
-            query['InstanceChargeType'] = request.instance_charge_type
-        if not UtilClient.is_unset(request.internet_charge_type):
-            query['InternetChargeType'] = request.internet_charge_type
-        if not UtilClient.is_unset(request.load_balancer_id):
-            query['LoadBalancerId'] = request.load_balancer_id
-        if not UtilClient.is_unset(request.load_balancer_spec):
-            query['LoadBalancerSpec'] = request.load_balancer_spec
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='ModifyLoadBalancerInstanceChargeType',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.ModifyLoadBalancerInstanceChargeTypeResponse(),
-            await self.call_api_async(params, req, runtime)
-        )
-
-    def modify_load_balancer_instance_charge_type(
-        self,
-        request: slb_20140515_models.ModifyLoadBalancerInstanceChargeTypeRequest,
-    ) -> slb_20140515_models.ModifyLoadBalancerInstanceChargeTypeResponse:
-        """
-        The ID of the CLB instance.
-        
-        @param request: ModifyLoadBalancerInstanceChargeTypeRequest
-        @return: ModifyLoadBalancerInstanceChargeTypeResponse
-        """
-        runtime = util_models.RuntimeOptions()
-        return self.modify_load_balancer_instance_charge_type_with_options(request, runtime)
-
-    async def modify_load_balancer_instance_charge_type_async(
-        self,
-        request: slb_20140515_models.ModifyLoadBalancerInstanceChargeTypeRequest,
-    ) -> slb_20140515_models.ModifyLoadBalancerInstanceChargeTypeResponse:
-        """
-        The ID of the CLB instance.
-        
-        @param request: ModifyLoadBalancerInstanceChargeTypeRequest
-        @return: ModifyLoadBalancerInstanceChargeTypeResponse
-        """
-        runtime = util_models.RuntimeOptions()
-        return await self.modify_load_balancer_instance_charge_type_with_options_async(request, runtime)
-
     def modify_load_balancer_instance_spec_with_options(
         self,
         request: slb_20140515_models.ModifyLoadBalancerInstanceSpecRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.ModifyLoadBalancerInstanceSpecResponse:
         UtilClient.validate_model(request)
         query = {}
@@ -7193,21 +5775,14 @@
         return await self.modify_load_balancer_instance_spec_with_options_async(request, runtime)
 
     def modify_load_balancer_internet_spec_with_options(
         self,
         request: slb_20140515_models.ModifyLoadBalancerInternetSpecRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.ModifyLoadBalancerInternetSpecResponse:
-        """
-        The ID of the CLB instance.
-        
-        @param request: ModifyLoadBalancerInternetSpecRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: ModifyLoadBalancerInternetSpecResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.auto_pay):
             query['AutoPay'] = request.auto_pay
         if not UtilClient.is_unset(request.bandwidth):
             query['Bandwidth'] = request.bandwidth
         if not UtilClient.is_unset(request.internet_charge_type):
@@ -7244,21 +5819,14 @@
         )
 
     async def modify_load_balancer_internet_spec_with_options_async(
         self,
         request: slb_20140515_models.ModifyLoadBalancerInternetSpecRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.ModifyLoadBalancerInternetSpecResponse:
-        """
-        The ID of the CLB instance.
-        
-        @param request: ModifyLoadBalancerInternetSpecRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: ModifyLoadBalancerInternetSpecResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.auto_pay):
             query['AutoPay'] = request.auto_pay
         if not UtilClient.is_unset(request.bandwidth):
             query['Bandwidth'] = request.bandwidth
         if not UtilClient.is_unset(request.internet_charge_type):
@@ -7294,33 +5862,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def modify_load_balancer_internet_spec(
         self,
         request: slb_20140515_models.ModifyLoadBalancerInternetSpecRequest,
     ) -> slb_20140515_models.ModifyLoadBalancerInternetSpecResponse:
-        """
-        The ID of the CLB instance.
-        
-        @param request: ModifyLoadBalancerInternetSpecRequest
-        @return: ModifyLoadBalancerInternetSpecResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.modify_load_balancer_internet_spec_with_options(request, runtime)
 
     async def modify_load_balancer_internet_spec_async(
         self,
         request: slb_20140515_models.ModifyLoadBalancerInternetSpecRequest,
     ) -> slb_20140515_models.ModifyLoadBalancerInternetSpecResponse:
-        """
-        The ID of the CLB instance.
-        
-        @param request: ModifyLoadBalancerInternetSpecRequest
-        @return: ModifyLoadBalancerInternetSpecResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.modify_load_balancer_internet_spec_with_options_async(request, runtime)
 
     def modify_load_balancer_pay_type_with_options(
         self,
         request: slb_20140515_models.ModifyLoadBalancerPayTypeRequest,
         runtime: util_models.RuntimeOptions,
@@ -7427,21 +5983,14 @@
         return await self.modify_load_balancer_pay_type_with_options_async(request, runtime)
 
     def modify_vserver_group_backend_servers_with_options(
         self,
         request: slb_20140515_models.ModifyVServerGroupBackendServersRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.ModifyVServerGroupBackendServersResponse:
-        """
-        The ID of the region where the Classic Load Balancer (CLB) instance is deployed.
-        
-        @param request: ModifyVServerGroupBackendServersRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: ModifyVServerGroupBackendServersResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.new_backend_servers):
             query['NewBackendServers'] = request.new_backend_servers
         if not UtilClient.is_unset(request.old_backend_servers):
             query['OldBackendServers'] = request.old_backend_servers
         if not UtilClient.is_unset(request.owner_account):
@@ -7476,21 +6025,14 @@
         )
 
     async def modify_vserver_group_backend_servers_with_options_async(
         self,
         request: slb_20140515_models.ModifyVServerGroupBackendServersRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.ModifyVServerGroupBackendServersResponse:
-        """
-        The ID of the region where the Classic Load Balancer (CLB) instance is deployed.
-        
-        @param request: ModifyVServerGroupBackendServersRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: ModifyVServerGroupBackendServersResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.new_backend_servers):
             query['NewBackendServers'] = request.new_backend_servers
         if not UtilClient.is_unset(request.old_backend_servers):
             query['OldBackendServers'] = request.old_backend_servers
         if not UtilClient.is_unset(request.owner_account):
@@ -7524,142 +6066,24 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def modify_vserver_group_backend_servers(
         self,
         request: slb_20140515_models.ModifyVServerGroupBackendServersRequest,
     ) -> slb_20140515_models.ModifyVServerGroupBackendServersResponse:
-        """
-        The ID of the region where the Classic Load Balancer (CLB) instance is deployed.
-        
-        @param request: ModifyVServerGroupBackendServersRequest
-        @return: ModifyVServerGroupBackendServersResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.modify_vserver_group_backend_servers_with_options(request, runtime)
 
     async def modify_vserver_group_backend_servers_async(
         self,
         request: slb_20140515_models.ModifyVServerGroupBackendServersRequest,
     ) -> slb_20140515_models.ModifyVServerGroupBackendServersResponse:
-        """
-        The ID of the region where the Classic Load Balancer (CLB) instance is deployed.
-        
-        @param request: ModifyVServerGroupBackendServersRequest
-        @return: ModifyVServerGroupBackendServersResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.modify_vserver_group_backend_servers_with_options_async(request, runtime)
 
-    def move_resource_group_with_options(
-        self,
-        request: slb_20140515_models.MoveResourceGroupRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.MoveResourceGroupResponse:
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.new_resource_group_id):
-            query['NewResourceGroupId'] = request.new_resource_group_id
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_group_id):
-            query['ResourceGroupId'] = request.resource_group_id
-        if not UtilClient.is_unset(request.resource_id):
-            query['ResourceId'] = request.resource_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.resource_type):
-            query['ResourceType'] = request.resource_type
-        if not UtilClient.is_unset(request.access_key_id):
-            query['access_key_id'] = request.access_key_id
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='MoveResourceGroup',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.MoveResourceGroupResponse(),
-            self.call_api(params, req, runtime)
-        )
-
-    async def move_resource_group_with_options_async(
-        self,
-        request: slb_20140515_models.MoveResourceGroupRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.MoveResourceGroupResponse:
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.new_resource_group_id):
-            query['NewResourceGroupId'] = request.new_resource_group_id
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_group_id):
-            query['ResourceGroupId'] = request.resource_group_id
-        if not UtilClient.is_unset(request.resource_id):
-            query['ResourceId'] = request.resource_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.resource_type):
-            query['ResourceType'] = request.resource_type
-        if not UtilClient.is_unset(request.access_key_id):
-            query['access_key_id'] = request.access_key_id
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='MoveResourceGroup',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.MoveResourceGroupResponse(),
-            await self.call_api_async(params, req, runtime)
-        )
-
-    def move_resource_group(
-        self,
-        request: slb_20140515_models.MoveResourceGroupRequest,
-    ) -> slb_20140515_models.MoveResourceGroupResponse:
-        runtime = util_models.RuntimeOptions()
-        return self.move_resource_group_with_options(request, runtime)
-
-    async def move_resource_group_async(
-        self,
-        request: slb_20140515_models.MoveResourceGroupRequest,
-    ) -> slb_20140515_models.MoveResourceGroupResponse:
-        runtime = util_models.RuntimeOptions()
-        return await self.move_resource_group_with_options_async(request, runtime)
-
     def remove_access_control_list_entry_with_options(
         self,
         request: slb_20140515_models.RemoveAccessControlListEntryRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.RemoveAccessControlListEntryResponse:
         UtilClient.validate_model(request)
         query = {}
@@ -7751,22 +6175,14 @@
         return await self.remove_access_control_list_entry_with_options_async(request, runtime)
 
     def remove_backend_servers_with_options(
         self,
         request: slb_20140515_models.RemoveBackendServersRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.RemoveBackendServersResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **RemoveBackendServers**.
-        
-        @param request: RemoveBackendServersRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: RemoveBackendServersResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.backend_servers):
             query['BackendServers'] = request.backend_servers
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
@@ -7799,22 +6215,14 @@
         )
 
     async def remove_backend_servers_with_options_async(
         self,
         request: slb_20140515_models.RemoveBackendServersRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.RemoveBackendServersResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **RemoveBackendServers**.
-        
-        @param request: RemoveBackendServersRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: RemoveBackendServersResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.backend_servers):
             query['BackendServers'] = request.backend_servers
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.owner_account):
@@ -7846,35 +6254,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def remove_backend_servers(
         self,
         request: slb_20140515_models.RemoveBackendServersRequest,
     ) -> slb_20140515_models.RemoveBackendServersResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **RemoveBackendServers**.
-        
-        @param request: RemoveBackendServersRequest
-        @return: RemoveBackendServersResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.remove_backend_servers_with_options(request, runtime)
 
     async def remove_backend_servers_async(
         self,
         request: slb_20140515_models.RemoveBackendServersRequest,
     ) -> slb_20140515_models.RemoveBackendServersResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **RemoveBackendServers**.
-        
-        @param request: RemoveBackendServersRequest
-        @return: RemoveBackendServersResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.remove_backend_servers_with_options_async(request, runtime)
 
     def remove_listener_white_list_item_with_options(
         self,
         request: slb_20140515_models.RemoveListenerWhiteListItemRequest,
         runtime: util_models.RuntimeOptions,
@@ -8071,21 +6465,14 @@
         return await self.remove_tags_with_options_async(request, runtime)
 
     def remove_vserver_group_backend_servers_with_options(
         self,
         request: slb_20140515_models.RemoveVServerGroupBackendServersRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.RemoveVServerGroupBackendServersResponse:
-        """
-        The ID of the region where the Classic Load Balancer (CLB) instance is deployed.
-        
-        @param request: RemoveVServerGroupBackendServersRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: RemoveVServerGroupBackendServersResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.backend_servers):
             query['BackendServers'] = request.backend_servers
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -8118,21 +6505,14 @@
         )
 
     async def remove_vserver_group_backend_servers_with_options_async(
         self,
         request: slb_20140515_models.RemoveVServerGroupBackendServersRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.RemoveVServerGroupBackendServersResponse:
-        """
-        The ID of the region where the Classic Load Balancer (CLB) instance is deployed.
-        
-        @param request: RemoveVServerGroupBackendServersRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: RemoveVServerGroupBackendServersResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.backend_servers):
             query['BackendServers'] = request.backend_servers
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -8164,33 +6544,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def remove_vserver_group_backend_servers(
         self,
         request: slb_20140515_models.RemoveVServerGroupBackendServersRequest,
     ) -> slb_20140515_models.RemoveVServerGroupBackendServersResponse:
-        """
-        The ID of the region where the Classic Load Balancer (CLB) instance is deployed.
-        
-        @param request: RemoveVServerGroupBackendServersRequest
-        @return: RemoveVServerGroupBackendServersResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.remove_vserver_group_backend_servers_with_options(request, runtime)
 
     async def remove_vserver_group_backend_servers_async(
         self,
         request: slb_20140515_models.RemoveVServerGroupBackendServersRequest,
     ) -> slb_20140515_models.RemoveVServerGroupBackendServersResponse:
-        """
-        The ID of the region where the Classic Load Balancer (CLB) instance is deployed.
-        
-        @param request: RemoveVServerGroupBackendServersRequest
-        @return: RemoveVServerGroupBackendServersResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.remove_vserver_group_backend_servers_with_options_async(request, runtime)
 
     def set_access_control_list_attribute_with_options(
         self,
         request: slb_20140515_models.SetAccessControlListAttributeRequest,
         runtime: util_models.RuntimeOptions,
@@ -8280,112 +6648,14 @@
     async def set_access_control_list_attribute_async(
         self,
         request: slb_20140515_models.SetAccessControlListAttributeRequest,
     ) -> slb_20140515_models.SetAccessControlListAttributeResponse:
         runtime = util_models.RuntimeOptions()
         return await self.set_access_control_list_attribute_with_options_async(request, runtime)
 
-    def set_access_logs_download_attribute_with_options(
-        self,
-        request: slb_20140515_models.SetAccessLogsDownloadAttributeRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.SetAccessLogsDownloadAttributeResponse:
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.load_balancer_id):
-            query['LoadBalancerId'] = request.load_balancer_id
-        if not UtilClient.is_unset(request.logs_download_attributes):
-            query['LogsDownloadAttributes'] = request.logs_download_attributes
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tags):
-            query['Tags'] = request.tags
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='SetAccessLogsDownloadAttribute',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.SetAccessLogsDownloadAttributeResponse(),
-            self.call_api(params, req, runtime)
-        )
-
-    async def set_access_logs_download_attribute_with_options_async(
-        self,
-        request: slb_20140515_models.SetAccessLogsDownloadAttributeRequest,
-        runtime: util_models.RuntimeOptions,
-    ) -> slb_20140515_models.SetAccessLogsDownloadAttributeResponse:
-        UtilClient.validate_model(request)
-        query = {}
-        if not UtilClient.is_unset(request.load_balancer_id):
-            query['LoadBalancerId'] = request.load_balancer_id
-        if not UtilClient.is_unset(request.logs_download_attributes):
-            query['LogsDownloadAttributes'] = request.logs_download_attributes
-        if not UtilClient.is_unset(request.owner_account):
-            query['OwnerAccount'] = request.owner_account
-        if not UtilClient.is_unset(request.owner_id):
-            query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.region_id):
-            query['RegionId'] = request.region_id
-        if not UtilClient.is_unset(request.resource_owner_account):
-            query['ResourceOwnerAccount'] = request.resource_owner_account
-        if not UtilClient.is_unset(request.resource_owner_id):
-            query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tags):
-            query['Tags'] = request.tags
-        req = open_api_models.OpenApiRequest(
-            query=OpenApiUtilClient.query(query)
-        )
-        params = open_api_models.Params(
-            action='SetAccessLogsDownloadAttribute',
-            version='2014-05-15',
-            protocol='HTTPS',
-            pathname='/',
-            method='POST',
-            auth_type='AK',
-            style='RPC',
-            req_body_type='formData',
-            body_type='json'
-        )
-        return TeaCore.from_map(
-            slb_20140515_models.SetAccessLogsDownloadAttributeResponse(),
-            await self.call_api_async(params, req, runtime)
-        )
-
-    def set_access_logs_download_attribute(
-        self,
-        request: slb_20140515_models.SetAccessLogsDownloadAttributeRequest,
-    ) -> slb_20140515_models.SetAccessLogsDownloadAttributeResponse:
-        runtime = util_models.RuntimeOptions()
-        return self.set_access_logs_download_attribute_with_options(request, runtime)
-
-    async def set_access_logs_download_attribute_async(
-        self,
-        request: slb_20140515_models.SetAccessLogsDownloadAttributeRequest,
-    ) -> slb_20140515_models.SetAccessLogsDownloadAttributeResponse:
-        runtime = util_models.RuntimeOptions()
-        return await self.set_access_logs_download_attribute_with_options_async(request, runtime)
-
     def set_backend_servers_with_options(
         self,
         request: slb_20140515_models.SetBackendServersRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.SetBackendServersResponse:
         UtilClient.validate_model(request)
         query = {}
@@ -8571,21 +6841,14 @@
         return await self.set_cacertificate_name_with_options_async(request, runtime)
 
     def set_domain_extension_attribute_with_options(
         self,
         request: slb_20140515_models.SetDomainExtensionAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.SetDomainExtensionAttributeResponse:
-        """
-        The ID of the region where the SLB instance is created.
-        
-        @param request: SetDomainExtensionAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: SetDomainExtensionAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.domain_extension_id):
             query['DomainExtensionId'] = request.domain_extension_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -8618,21 +6881,14 @@
         )
 
     async def set_domain_extension_attribute_with_options_async(
         self,
         request: slb_20140515_models.SetDomainExtensionAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.SetDomainExtensionAttributeResponse:
-        """
-        The ID of the region where the SLB instance is created.
-        
-        @param request: SetDomainExtensionAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: SetDomainExtensionAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.domain_extension_id):
             query['DomainExtensionId'] = request.domain_extension_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -8664,33 +6920,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def set_domain_extension_attribute(
         self,
         request: slb_20140515_models.SetDomainExtensionAttributeRequest,
     ) -> slb_20140515_models.SetDomainExtensionAttributeResponse:
-        """
-        The ID of the region where the SLB instance is created.
-        
-        @param request: SetDomainExtensionAttributeRequest
-        @return: SetDomainExtensionAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.set_domain_extension_attribute_with_options(request, runtime)
 
     async def set_domain_extension_attribute_async(
         self,
         request: slb_20140515_models.SetDomainExtensionAttributeRequest,
     ) -> slb_20140515_models.SetDomainExtensionAttributeResponse:
-        """
-        The ID of the region where the SLB instance is created.
-        
-        @param request: SetDomainExtensionAttributeRequest
-        @return: SetDomainExtensionAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.set_domain_extension_attribute_with_options_async(request, runtime)
 
     def set_listener_access_control_status_with_options(
         self,
         request: slb_20140515_models.SetListenerAccessControlStatusRequest,
         runtime: util_models.RuntimeOptions,
@@ -8887,22 +7131,14 @@
         return await self.set_load_balancer_delete_protection_with_options_async(request, runtime)
 
     def set_load_balancer_httplistener_attribute_with_options(
         self,
         request: slb_20140515_models.SetLoadBalancerHTTPListenerAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.SetLoadBalancerHTTPListenerAttributeResponse:
-        """
-        The ID of the region where the CLB instance is deployed.
-        You can query the region ID from the [Regions and zones](~~27585~~) list or by calling the [DescribeRegions](~~27584~~) operation.
-        
-        @param request: SetLoadBalancerHTTPListenerAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: SetLoadBalancerHTTPListenerAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -8993,22 +7229,14 @@
         )
 
     async def set_load_balancer_httplistener_attribute_with_options_async(
         self,
         request: slb_20140515_models.SetLoadBalancerHTTPListenerAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.SetLoadBalancerHTTPListenerAttributeResponse:
-        """
-        The ID of the region where the CLB instance is deployed.
-        You can query the region ID from the [Regions and zones](~~27585~~) list or by calling the [DescribeRegions](~~27584~~) operation.
-        
-        @param request: SetLoadBalancerHTTPListenerAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: SetLoadBalancerHTTPListenerAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -9098,51 +7326,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def set_load_balancer_httplistener_attribute(
         self,
         request: slb_20140515_models.SetLoadBalancerHTTPListenerAttributeRequest,
     ) -> slb_20140515_models.SetLoadBalancerHTTPListenerAttributeResponse:
-        """
-        The ID of the region where the CLB instance is deployed.
-        You can query the region ID from the [Regions and zones](~~27585~~) list or by calling the [DescribeRegions](~~27584~~) operation.
-        
-        @param request: SetLoadBalancerHTTPListenerAttributeRequest
-        @return: SetLoadBalancerHTTPListenerAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.set_load_balancer_httplistener_attribute_with_options(request, runtime)
 
     async def set_load_balancer_httplistener_attribute_async(
         self,
         request: slb_20140515_models.SetLoadBalancerHTTPListenerAttributeRequest,
     ) -> slb_20140515_models.SetLoadBalancerHTTPListenerAttributeResponse:
-        """
-        The ID of the region where the CLB instance is deployed.
-        You can query the region ID from the [Regions and zones](~~27585~~) list or by calling the [DescribeRegions](~~27584~~) operation.
-        
-        @param request: SetLoadBalancerHTTPListenerAttributeRequest
-        @return: SetLoadBalancerHTTPListenerAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.set_load_balancer_httplistener_attribute_with_options_async(request, runtime)
 
     def set_load_balancer_httpslistener_attribute_with_options(
         self,
         request: slb_20140515_models.SetLoadBalancerHTTPSListenerAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.SetLoadBalancerHTTPSListenerAttributeResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **SetLoadBalancerHTTPSListenerAttribute**.
-        
-        @param request: SetLoadBalancerHTTPSListenerAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: SetLoadBalancerHTTPSListenerAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -9241,22 +7447,14 @@
         )
 
     async def set_load_balancer_httpslistener_attribute_with_options_async(
         self,
         request: slb_20140515_models.SetLoadBalancerHTTPSListenerAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.SetLoadBalancerHTTPSListenerAttributeResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **SetLoadBalancerHTTPSListenerAttribute**.
-        
-        @param request: SetLoadBalancerHTTPSListenerAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: SetLoadBalancerHTTPSListenerAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -9354,35 +7552,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def set_load_balancer_httpslistener_attribute(
         self,
         request: slb_20140515_models.SetLoadBalancerHTTPSListenerAttributeRequest,
     ) -> slb_20140515_models.SetLoadBalancerHTTPSListenerAttributeResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **SetLoadBalancerHTTPSListenerAttribute**.
-        
-        @param request: SetLoadBalancerHTTPSListenerAttributeRequest
-        @return: SetLoadBalancerHTTPSListenerAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.set_load_balancer_httpslistener_attribute_with_options(request, runtime)
 
     async def set_load_balancer_httpslistener_attribute_async(
         self,
         request: slb_20140515_models.SetLoadBalancerHTTPSListenerAttributeRequest,
     ) -> slb_20140515_models.SetLoadBalancerHTTPSListenerAttributeResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **SetLoadBalancerHTTPSListenerAttribute**.
-        
-        @param request: SetLoadBalancerHTTPSListenerAttributeRequest
-        @return: SetLoadBalancerHTTPSListenerAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.set_load_balancer_httpslistener_attribute_with_options_async(request, runtime)
 
     def set_load_balancer_modification_protection_with_options(
         self,
         request: slb_20140515_models.SetLoadBalancerModificationProtectionRequest,
         runtime: util_models.RuntimeOptions,
@@ -9669,24 +7853,14 @@
         return await self.set_load_balancer_status_with_options_async(request, runtime)
 
     def set_load_balancer_tcplistener_attribute_with_options(
         self,
         request: slb_20140515_models.SetLoadBalancerTCPListenerAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.SetLoadBalancerTCPListenerAttributeResponse:
-        """
-        The timeout period of a health check.
-        If a backend ECS instance does not return a health check response within the specified timeout period, the server fails the health check.
-        Valid values: **1** to **300**. Unit: seconds.
-        >  If the value of the **HealthCheckConnectTimeout** parameter is smaller than that of the **HealthCheckInterval** parameter, the timeout period specified by the **HCTimeout** parameter is ignored and the period of time specified by the **HealthCheckInterval** parameter is used as the timeout period.
-        
-        @param request: SetLoadBalancerTCPListenerAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: SetLoadBalancerTCPListenerAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -9707,16 +7881,14 @@
             query['HealthCheckConnectTimeout'] = request.health_check_connect_timeout
         if not UtilClient.is_unset(request.health_check_domain):
             query['HealthCheckDomain'] = request.health_check_domain
         if not UtilClient.is_unset(request.health_check_http_code):
             query['HealthCheckHttpCode'] = request.health_check_http_code
         if not UtilClient.is_unset(request.health_check_interval):
             query['HealthCheckInterval'] = request.health_check_interval
-        if not UtilClient.is_unset(request.health_check_switch):
-            query['HealthCheckSwitch'] = request.health_check_switch
         if not UtilClient.is_unset(request.health_check_type):
             query['HealthCheckType'] = request.health_check_type
         if not UtilClient.is_unset(request.health_check_uri):
             query['HealthCheckURI'] = request.health_check_uri
         if not UtilClient.is_unset(request.healthy_threshold):
             query['HealthyThreshold'] = request.healthy_threshold
         if not UtilClient.is_unset(request.listener_port):
@@ -9729,16 +7901,14 @@
             query['MasterSlaveServerGroupId'] = request.master_slave_server_group_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.persistence_timeout):
             query['PersistenceTimeout'] = request.persistence_timeout
-        if not UtilClient.is_unset(request.proxy_protocol_v2enabled):
-            query['ProxyProtocolV2Enabled'] = request.proxy_protocol_v2enabled
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.scheduler):
@@ -9771,24 +7941,14 @@
         )
 
     async def set_load_balancer_tcplistener_attribute_with_options_async(
         self,
         request: slb_20140515_models.SetLoadBalancerTCPListenerAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.SetLoadBalancerTCPListenerAttributeResponse:
-        """
-        The timeout period of a health check.
-        If a backend ECS instance does not return a health check response within the specified timeout period, the server fails the health check.
-        Valid values: **1** to **300**. Unit: seconds.
-        >  If the value of the **HealthCheckConnectTimeout** parameter is smaller than that of the **HealthCheckInterval** parameter, the timeout period specified by the **HCTimeout** parameter is ignored and the period of time specified by the **HealthCheckInterval** parameter is used as the timeout period.
-        
-        @param request: SetLoadBalancerTCPListenerAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: SetLoadBalancerTCPListenerAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -9809,16 +7969,14 @@
             query['HealthCheckConnectTimeout'] = request.health_check_connect_timeout
         if not UtilClient.is_unset(request.health_check_domain):
             query['HealthCheckDomain'] = request.health_check_domain
         if not UtilClient.is_unset(request.health_check_http_code):
             query['HealthCheckHttpCode'] = request.health_check_http_code
         if not UtilClient.is_unset(request.health_check_interval):
             query['HealthCheckInterval'] = request.health_check_interval
-        if not UtilClient.is_unset(request.health_check_switch):
-            query['HealthCheckSwitch'] = request.health_check_switch
         if not UtilClient.is_unset(request.health_check_type):
             query['HealthCheckType'] = request.health_check_type
         if not UtilClient.is_unset(request.health_check_uri):
             query['HealthCheckURI'] = request.health_check_uri
         if not UtilClient.is_unset(request.healthy_threshold):
             query['HealthyThreshold'] = request.healthy_threshold
         if not UtilClient.is_unset(request.listener_port):
@@ -9831,16 +7989,14 @@
             query['MasterSlaveServerGroupId'] = request.master_slave_server_group_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.persistence_timeout):
             query['PersistenceTimeout'] = request.persistence_timeout
-        if not UtilClient.is_unset(request.proxy_protocol_v2enabled):
-            query['ProxyProtocolV2Enabled'] = request.proxy_protocol_v2enabled
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.scheduler):
@@ -9872,54 +8028,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def set_load_balancer_tcplistener_attribute(
         self,
         request: slb_20140515_models.SetLoadBalancerTCPListenerAttributeRequest,
     ) -> slb_20140515_models.SetLoadBalancerTCPListenerAttributeResponse:
-        """
-        The timeout period of a health check.
-        If a backend ECS instance does not return a health check response within the specified timeout period, the server fails the health check.
-        Valid values: **1** to **300**. Unit: seconds.
-        >  If the value of the **HealthCheckConnectTimeout** parameter is smaller than that of the **HealthCheckInterval** parameter, the timeout period specified by the **HCTimeout** parameter is ignored and the period of time specified by the **HealthCheckInterval** parameter is used as the timeout period.
-        
-        @param request: SetLoadBalancerTCPListenerAttributeRequest
-        @return: SetLoadBalancerTCPListenerAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.set_load_balancer_tcplistener_attribute_with_options(request, runtime)
 
     async def set_load_balancer_tcplistener_attribute_async(
         self,
         request: slb_20140515_models.SetLoadBalancerTCPListenerAttributeRequest,
     ) -> slb_20140515_models.SetLoadBalancerTCPListenerAttributeResponse:
-        """
-        The timeout period of a health check.
-        If a backend ECS instance does not return a health check response within the specified timeout period, the server fails the health check.
-        Valid values: **1** to **300**. Unit: seconds.
-        >  If the value of the **HealthCheckConnectTimeout** parameter is smaller than that of the **HealthCheckInterval** parameter, the timeout period specified by the **HCTimeout** parameter is ignored and the period of time specified by the **HealthCheckInterval** parameter is used as the timeout period.
-        
-        @param request: SetLoadBalancerTCPListenerAttributeRequest
-        @return: SetLoadBalancerTCPListenerAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.set_load_balancer_tcplistener_attribute_with_options_async(request, runtime)
 
     def set_load_balancer_udplistener_attribute_with_options(
         self,
         request: slb_20140515_models.SetLoadBalancerUDPListenerAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.SetLoadBalancerUDPListenerAttributeResponse:
-        """
-        The response string for UDP listener health checks. The string must be 1 to 64 characters in length and can contain only letters and digits.
-        
-        @param request: SetLoadBalancerUDPListenerAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: SetLoadBalancerUDPListenerAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -9930,32 +8061,28 @@
             query['Description'] = request.description
         if not UtilClient.is_unset(request.health_check_connect_port):
             query['HealthCheckConnectPort'] = request.health_check_connect_port
         if not UtilClient.is_unset(request.health_check_connect_timeout):
             query['HealthCheckConnectTimeout'] = request.health_check_connect_timeout
         if not UtilClient.is_unset(request.health_check_interval):
             query['HealthCheckInterval'] = request.health_check_interval
-        if not UtilClient.is_unset(request.health_check_switch):
-            query['HealthCheckSwitch'] = request.health_check_switch
         if not UtilClient.is_unset(request.healthy_threshold):
             query['HealthyThreshold'] = request.healthy_threshold
         if not UtilClient.is_unset(request.listener_port):
             query['ListenerPort'] = request.listener_port
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.master_slave_server_group):
             query['MasterSlaveServerGroup'] = request.master_slave_server_group
         if not UtilClient.is_unset(request.master_slave_server_group_id):
             query['MasterSlaveServerGroupId'] = request.master_slave_server_group_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.proxy_protocol_v2enabled):
-            query['ProxyProtocolV2Enabled'] = request.proxy_protocol_v2enabled
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.scheduler):
@@ -9990,21 +8117,14 @@
         )
 
     async def set_load_balancer_udplistener_attribute_with_options_async(
         self,
         request: slb_20140515_models.SetLoadBalancerUDPListenerAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.SetLoadBalancerUDPListenerAttributeResponse:
-        """
-        The response string for UDP listener health checks. The string must be 1 to 64 characters in length and can contain only letters and digits.
-        
-        @param request: SetLoadBalancerUDPListenerAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: SetLoadBalancerUDPListenerAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.acl_id):
             query['AclId'] = request.acl_id
         if not UtilClient.is_unset(request.acl_status):
             query['AclStatus'] = request.acl_status
         if not UtilClient.is_unset(request.acl_type):
@@ -10015,32 +8135,28 @@
             query['Description'] = request.description
         if not UtilClient.is_unset(request.health_check_connect_port):
             query['HealthCheckConnectPort'] = request.health_check_connect_port
         if not UtilClient.is_unset(request.health_check_connect_timeout):
             query['HealthCheckConnectTimeout'] = request.health_check_connect_timeout
         if not UtilClient.is_unset(request.health_check_interval):
             query['HealthCheckInterval'] = request.health_check_interval
-        if not UtilClient.is_unset(request.health_check_switch):
-            query['HealthCheckSwitch'] = request.health_check_switch
         if not UtilClient.is_unset(request.healthy_threshold):
             query['HealthyThreshold'] = request.healthy_threshold
         if not UtilClient.is_unset(request.listener_port):
             query['ListenerPort'] = request.listener_port
         if not UtilClient.is_unset(request.load_balancer_id):
             query['LoadBalancerId'] = request.load_balancer_id
         if not UtilClient.is_unset(request.master_slave_server_group):
             query['MasterSlaveServerGroup'] = request.master_slave_server_group
         if not UtilClient.is_unset(request.master_slave_server_group_id):
             query['MasterSlaveServerGroupId'] = request.master_slave_server_group_id
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
-        if not UtilClient.is_unset(request.proxy_protocol_v2enabled):
-            query['ProxyProtocolV2Enabled'] = request.proxy_protocol_v2enabled
         if not UtilClient.is_unset(request.region_id):
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.scheduler):
@@ -10074,33 +8190,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def set_load_balancer_udplistener_attribute(
         self,
         request: slb_20140515_models.SetLoadBalancerUDPListenerAttributeRequest,
     ) -> slb_20140515_models.SetLoadBalancerUDPListenerAttributeResponse:
-        """
-        The response string for UDP listener health checks. The string must be 1 to 64 characters in length and can contain only letters and digits.
-        
-        @param request: SetLoadBalancerUDPListenerAttributeRequest
-        @return: SetLoadBalancerUDPListenerAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.set_load_balancer_udplistener_attribute_with_options(request, runtime)
 
     async def set_load_balancer_udplistener_attribute_async(
         self,
         request: slb_20140515_models.SetLoadBalancerUDPListenerAttributeRequest,
     ) -> slb_20140515_models.SetLoadBalancerUDPListenerAttributeResponse:
-        """
-        The response string for UDP listener health checks. The string must be 1 to 64 characters in length and can contain only letters and digits.
-        
-        @param request: SetLoadBalancerUDPListenerAttributeRequest
-        @return: SetLoadBalancerUDPListenerAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.set_load_balancer_udplistener_attribute_with_options_async(request, runtime)
 
     def set_rule_with_options(
         self,
         request: slb_20140515_models.SetRuleRequest,
         runtime: util_models.RuntimeOptions,
@@ -10373,14 +8477,16 @@
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.tlscipher_policy_id):
             query['TLSCipherPolicyId'] = request.tlscipher_policy_id
         if not UtilClient.is_unset(request.tlsversions):
             query['TLSVersions'] = request.tlsversions
+        if not UtilClient.is_unset(request.access_key_id):
+            query['access_key_id'] = request.access_key_id
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='SetTLSCipherPolicyAttribute',
             version='2014-05-15',
             protocol='HTTPS',
@@ -10417,14 +8523,16 @@
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.tlscipher_policy_id):
             query['TLSCipherPolicyId'] = request.tlscipher_policy_id
         if not UtilClient.is_unset(request.tlsversions):
             query['TLSVersions'] = request.tlsversions
+        if not UtilClient.is_unset(request.access_key_id):
+            query['access_key_id'] = request.access_key_id
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='SetTLSCipherPolicyAttribute',
             version='2014-05-15',
             protocol='HTTPS',
@@ -10455,21 +8563,14 @@
         return await self.set_tlscipher_policy_attribute_with_options_async(request, runtime)
 
     def set_vserver_group_attribute_with_options(
         self,
         request: slb_20140515_models.SetVServerGroupAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.SetVServerGroupAttributeResponse:
-        """
-        The ID of the region where the Classic Load Balancer (CLB) instance is deployed. This parameter cannot be modified.
-        
-        @param request: SetVServerGroupAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: SetVServerGroupAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.backend_servers):
             query['BackendServers'] = request.backend_servers
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -10504,21 +8605,14 @@
         )
 
     async def set_vserver_group_attribute_with_options_async(
         self,
         request: slb_20140515_models.SetVServerGroupAttributeRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.SetVServerGroupAttributeResponse:
-        """
-        The ID of the region where the Classic Load Balancer (CLB) instance is deployed. This parameter cannot be modified.
-        
-        @param request: SetVServerGroupAttributeRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: SetVServerGroupAttributeResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.backend_servers):
             query['BackendServers'] = request.backend_servers
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
@@ -10552,49 +8646,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def set_vserver_group_attribute(
         self,
         request: slb_20140515_models.SetVServerGroupAttributeRequest,
     ) -> slb_20140515_models.SetVServerGroupAttributeResponse:
-        """
-        The ID of the region where the Classic Load Balancer (CLB) instance is deployed. This parameter cannot be modified.
-        
-        @param request: SetVServerGroupAttributeRequest
-        @return: SetVServerGroupAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.set_vserver_group_attribute_with_options(request, runtime)
 
     async def set_vserver_group_attribute_async(
         self,
         request: slb_20140515_models.SetVServerGroupAttributeRequest,
     ) -> slb_20140515_models.SetVServerGroupAttributeResponse:
-        """
-        The ID of the region where the Classic Load Balancer (CLB) instance is deployed. This parameter cannot be modified.
-        
-        @param request: SetVServerGroupAttributeRequest
-        @return: SetVServerGroupAttributeResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.set_vserver_group_attribute_with_options_async(request, runtime)
 
     def start_load_balancer_listener_with_options(
         self,
         request: slb_20140515_models.StartLoadBalancerListenerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.StartLoadBalancerListenerResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **StartLoadBalancerListener**.
-        
-        @param request: StartLoadBalancerListenerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: StartLoadBalancerListenerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.listener_port):
             query['ListenerPort'] = request.listener_port
         if not UtilClient.is_unset(request.listener_protocol):
             query['ListenerProtocol'] = request.listener_protocol
         if not UtilClient.is_unset(request.load_balancer_id):
@@ -10629,22 +8703,14 @@
         )
 
     async def start_load_balancer_listener_with_options_async(
         self,
         request: slb_20140515_models.StartLoadBalancerListenerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.StartLoadBalancerListenerResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **StartLoadBalancerListener**.
-        
-        @param request: StartLoadBalancerListenerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: StartLoadBalancerListenerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.listener_port):
             query['ListenerPort'] = request.listener_port
         if not UtilClient.is_unset(request.listener_protocol):
             query['ListenerProtocol'] = request.listener_protocol
         if not UtilClient.is_unset(request.load_balancer_id):
@@ -10678,51 +8744,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def start_load_balancer_listener(
         self,
         request: slb_20140515_models.StartLoadBalancerListenerRequest,
     ) -> slb_20140515_models.StartLoadBalancerListenerResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **StartLoadBalancerListener**.
-        
-        @param request: StartLoadBalancerListenerRequest
-        @return: StartLoadBalancerListenerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.start_load_balancer_listener_with_options(request, runtime)
 
     async def start_load_balancer_listener_async(
         self,
         request: slb_20140515_models.StartLoadBalancerListenerRequest,
     ) -> slb_20140515_models.StartLoadBalancerListenerResponse:
-        """
-        The operation that you want to perform.
-        Set the value to **StartLoadBalancerListener**.
-        
-        @param request: StartLoadBalancerListenerRequest
-        @return: StartLoadBalancerListenerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.start_load_balancer_listener_with_options_async(request, runtime)
 
     def stop_load_balancer_listener_with_options(
         self,
         request: slb_20140515_models.StopLoadBalancerListenerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.StopLoadBalancerListenerResponse:
-        """
-        The name of this action.
-        Value: **StopLoadBalancerListener**\
-        
-        @param request: StopLoadBalancerListenerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: StopLoadBalancerListenerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.listener_port):
             query['ListenerPort'] = request.listener_port
         if not UtilClient.is_unset(request.listener_protocol):
             query['ListenerProtocol'] = request.listener_protocol
         if not UtilClient.is_unset(request.load_balancer_id):
@@ -10757,22 +8801,14 @@
         )
 
     async def stop_load_balancer_listener_with_options_async(
         self,
         request: slb_20140515_models.StopLoadBalancerListenerRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.StopLoadBalancerListenerResponse:
-        """
-        The name of this action.
-        Value: **StopLoadBalancerListener**\
-        
-        @param request: StopLoadBalancerListenerRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: StopLoadBalancerListenerResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.listener_port):
             query['ListenerPort'] = request.listener_port
         if not UtilClient.is_unset(request.listener_protocol):
             query['ListenerProtocol'] = request.listener_protocol
         if not UtilClient.is_unset(request.load_balancer_id):
@@ -10806,50 +8842,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def stop_load_balancer_listener(
         self,
         request: slb_20140515_models.StopLoadBalancerListenerRequest,
     ) -> slb_20140515_models.StopLoadBalancerListenerResponse:
-        """
-        The name of this action.
-        Value: **StopLoadBalancerListener**\
-        
-        @param request: StopLoadBalancerListenerRequest
-        @return: StopLoadBalancerListenerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.stop_load_balancer_listener_with_options(request, runtime)
 
     async def stop_load_balancer_listener_async(
         self,
         request: slb_20140515_models.StopLoadBalancerListenerRequest,
     ) -> slb_20140515_models.StopLoadBalancerListenerResponse:
-        """
-        The name of this action.
-        Value: **StopLoadBalancerListener**\
-        
-        @param request: StopLoadBalancerListenerRequest
-        @return: StopLoadBalancerListenerResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.stop_load_balancer_listener_with_options_async(request, runtime)
 
     def tag_resources_with_options(
         self,
         request: slb_20140515_models.TagResourcesRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.TagResourcesResponse:
-        """
-        The ID of the request.
-        
-        @param request: TagResourcesRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: TagResourcesResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
@@ -10884,21 +8899,14 @@
         )
 
     async def tag_resources_with_options_async(
         self,
         request: slb_20140515_models.TagResourcesRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.TagResourcesResponse:
-        """
-        The ID of the request.
-        
-        @param request: TagResourcesRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: TagResourcesResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.owner_account):
             query['OwnerAccount'] = request.owner_account
         if not UtilClient.is_unset(request.owner_id):
             query['OwnerId'] = request.owner_id
         if not UtilClient.is_unset(request.region_id):
@@ -10932,33 +8940,21 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def tag_resources(
         self,
         request: slb_20140515_models.TagResourcesRequest,
     ) -> slb_20140515_models.TagResourcesResponse:
-        """
-        The ID of the request.
-        
-        @param request: TagResourcesRequest
-        @return: TagResourcesResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.tag_resources_with_options(request, runtime)
 
     async def tag_resources_async(
         self,
         request: slb_20140515_models.TagResourcesRequest,
     ) -> slb_20140515_models.TagResourcesResponse:
-        """
-        The ID of the request.
-        
-        @param request: TagResourcesRequest
-        @return: TagResourcesResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.tag_resources_with_options_async(request, runtime)
 
     def untag_resources_with_options(
         self,
         request: slb_20140515_models.UntagResourcesRequest,
         runtime: util_models.RuntimeOptions,
@@ -11061,22 +9057,14 @@
         return await self.untag_resources_with_options_async(request, runtime)
 
     def upload_cacertificate_with_options(
         self,
         request: slb_20140515_models.UploadCACertificateRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.UploadCACertificateResponse:
-        """
-        The ID of the region to which the CA certificate belongs.
-        To query the region ID, call [DescribeRegions](~~27584~~).
-        
-        @param request: UploadCACertificateRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: UploadCACertificateResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.cacertificate):
             query['CACertificate'] = request.cacertificate
         if not UtilClient.is_unset(request.cacertificate_name):
             query['CACertificateName'] = request.cacertificate_name
         if not UtilClient.is_unset(request.owner_account):
@@ -11087,16 +9075,14 @@
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_group_id):
             query['ResourceGroupId'] = request.resource_group_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='UploadCACertificate',
             version='2014-05-15',
             protocol='HTTPS',
@@ -11113,22 +9099,14 @@
         )
 
     async def upload_cacertificate_with_options_async(
         self,
         request: slb_20140515_models.UploadCACertificateRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.UploadCACertificateResponse:
-        """
-        The ID of the region to which the CA certificate belongs.
-        To query the region ID, call [DescribeRegions](~~27584~~).
-        
-        @param request: UploadCACertificateRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: UploadCACertificateResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.cacertificate):
             query['CACertificate'] = request.cacertificate
         if not UtilClient.is_unset(request.cacertificate_name):
             query['CACertificateName'] = request.cacertificate_name
         if not UtilClient.is_unset(request.owner_account):
@@ -11139,16 +9117,14 @@
             query['RegionId'] = request.region_id
         if not UtilClient.is_unset(request.resource_group_id):
             query['ResourceGroupId'] = request.resource_group_id
         if not UtilClient.is_unset(request.resource_owner_account):
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='UploadCACertificate',
             version='2014-05-15',
             protocol='HTTPS',
@@ -11164,50 +9140,29 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def upload_cacertificate(
         self,
         request: slb_20140515_models.UploadCACertificateRequest,
     ) -> slb_20140515_models.UploadCACertificateResponse:
-        """
-        The ID of the region to which the CA certificate belongs.
-        To query the region ID, call [DescribeRegions](~~27584~~).
-        
-        @param request: UploadCACertificateRequest
-        @return: UploadCACertificateResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.upload_cacertificate_with_options(request, runtime)
 
     async def upload_cacertificate_async(
         self,
         request: slb_20140515_models.UploadCACertificateRequest,
     ) -> slb_20140515_models.UploadCACertificateResponse:
-        """
-        The ID of the region to which the CA certificate belongs.
-        To query the region ID, call [DescribeRegions](~~27584~~).
-        
-        @param request: UploadCACertificateRequest
-        @return: UploadCACertificateResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.upload_cacertificate_with_options_async(request, runtime)
 
     def upload_server_certificate_with_options(
         self,
         request: slb_20140515_models.UploadServerCertificateRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.UploadServerCertificateResponse:
-        """
-        The alternative domain names of the server certificate.
-        
-        @param request: UploadServerCertificateRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: UploadServerCertificateResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.ali_cloud_certificate_id):
             query['AliCloudCertificateId'] = request.ali_cloud_certificate_id
         if not UtilClient.is_unset(request.ali_cloud_certificate_name):
             query['AliCloudCertificateName'] = request.ali_cloud_certificate_name
         if not UtilClient.is_unset(request.ali_cloud_certificate_region_id):
@@ -11226,16 +9181,14 @@
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.server_certificate):
             query['ServerCertificate'] = request.server_certificate
         if not UtilClient.is_unset(request.server_certificate_name):
             query['ServerCertificateName'] = request.server_certificate_name
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='UploadServerCertificate',
             version='2014-05-15',
             protocol='HTTPS',
@@ -11252,21 +9205,14 @@
         )
 
     async def upload_server_certificate_with_options_async(
         self,
         request: slb_20140515_models.UploadServerCertificateRequest,
         runtime: util_models.RuntimeOptions,
     ) -> slb_20140515_models.UploadServerCertificateResponse:
-        """
-        The alternative domain names of the server certificate.
-        
-        @param request: UploadServerCertificateRequest
-        @param runtime: runtime options for this request RuntimeOptions
-        @return: UploadServerCertificateResponse
-        """
         UtilClient.validate_model(request)
         query = {}
         if not UtilClient.is_unset(request.ali_cloud_certificate_id):
             query['AliCloudCertificateId'] = request.ali_cloud_certificate_id
         if not UtilClient.is_unset(request.ali_cloud_certificate_name):
             query['AliCloudCertificateName'] = request.ali_cloud_certificate_name
         if not UtilClient.is_unset(request.ali_cloud_certificate_region_id):
@@ -11285,16 +9231,14 @@
             query['ResourceOwnerAccount'] = request.resource_owner_account
         if not UtilClient.is_unset(request.resource_owner_id):
             query['ResourceOwnerId'] = request.resource_owner_id
         if not UtilClient.is_unset(request.server_certificate):
             query['ServerCertificate'] = request.server_certificate
         if not UtilClient.is_unset(request.server_certificate_name):
             query['ServerCertificateName'] = request.server_certificate_name
-        if not UtilClient.is_unset(request.tag):
-            query['Tag'] = request.tag
         req = open_api_models.OpenApiRequest(
             query=OpenApiUtilClient.query(query)
         )
         params = open_api_models.Params(
             action='UploadServerCertificate',
             version='2014-05-15',
             protocol='HTTPS',
@@ -11310,28 +9254,16 @@
             await self.call_api_async(params, req, runtime)
         )
 
     def upload_server_certificate(
         self,
         request: slb_20140515_models.UploadServerCertificateRequest,
     ) -> slb_20140515_models.UploadServerCertificateResponse:
-        """
-        The alternative domain names of the server certificate.
-        
-        @param request: UploadServerCertificateRequest
-        @return: UploadServerCertificateResponse
-        """
         runtime = util_models.RuntimeOptions()
         return self.upload_server_certificate_with_options(request, runtime)
 
     async def upload_server_certificate_async(
         self,
         request: slb_20140515_models.UploadServerCertificateRequest,
     ) -> slb_20140515_models.UploadServerCertificateResponse:
-        """
-        The alternative domain names of the server certificate.
-        
-        @param request: UploadServerCertificateRequest
-        @return: UploadServerCertificateResponse
-        """
         runtime = util_models.RuntimeOptions()
         return await self.upload_server_certificate_with_options_async(request, runtime)
```

### Comparing `alibabacloud_slb20140515-3.3.20/alibabacloud_slb20140515.egg-info/PKG-INFO` & `alibabacloud_slb20140515-3.3.9/alibabacloud_slb20140515.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: alibabacloud-slb20140515
-Version: 3.3.20
+Version: 3.3.9
 Summary: Alibaba Cloud Server Load Balancer (20140515) SDK Library for Python
 Home-page: https://github.com/aliyun/alibabacloud-python-sdk
 Author: Alibaba Cloud SDK
 Author-email: sdk-team@alibabacloud.com
 License: Apache License 2.0
 Description: English | [简体中文](README-CN.md)
         ![](https://aliyunsdk-pages.alicdn.com/icons/AlibabaCloud.svg)
```

### Comparing `alibabacloud_slb20140515-3.3.20/setup.py` & `alibabacloud_slb20140515-3.3.9/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,30 +20,30 @@
 
 import os
 from setuptools import setup, find_packages
 
 """
 setup module for alibabacloud_slb20140515.
 
-Created on 28/06/2023
+Created on 29/12/2021
 
 @author: Alibaba Cloud SDK
 """
 
 PACKAGE = "alibabacloud_slb20140515"
 NAME = "alibabacloud_slb20140515" or "alibabacloud-package"
 DESCRIPTION = "Alibaba Cloud Server Load Balancer (20140515) SDK Library for Python"
 AUTHOR = "Alibaba Cloud SDK"
 AUTHOR_EMAIL = "sdk-team@alibabacloud.com"
 URL = "https://github.com/aliyun/alibabacloud-python-sdk"
 VERSION = __import__(PACKAGE).__version__
 REQUIRES = [
-    "alibabacloud_tea_util>=0.3.9, <1.0.0",
-    "alibabacloud_tea_openapi>=0.3.6, <1.0.0",
-    "alibabacloud_openapi_util>=0.2.1, <1.0.0",
+    "alibabacloud_tea_util>=0.3.5, <1.0.0",
+    "alibabacloud_tea_openapi>=0.3.1, <1.0.0",
+    "alibabacloud_openapi_util>=0.1.6, <1.0.0",
     "alibabacloud_endpoint_util>=0.0.3, <1.0.0"
 ]
 
 LONG_DESCRIPTION = ''
 if os.path.exists('./README.md'):
     with open("README.md", encoding='utf-8') as fp:
         LONG_DESCRIPTION = fp.read()
```


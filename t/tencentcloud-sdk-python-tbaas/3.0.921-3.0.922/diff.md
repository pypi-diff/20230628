# Comparing `tmp/tencentcloud-sdk-python-tbaas-3.0.921.tar.gz` & `tmp/tencentcloud-sdk-python-tbaas-3.0.922.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/tencentcloud-sdk-python-tbaas-3.0.921.tar", last modified: Mon Jun 26 00:32:55 2023, max compression
+gzip compressed data, was "dist/tencentcloud-sdk-python-tbaas-3.0.922.tar", last modified: Tue Jun 27 00:33:11 2023, max compression
```

## Comparing `tencentcloud-sdk-python-tbaas-3.0.921.tar` & `tencentcloud-sdk-python-tbaas-3.0.922.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/
--rw-r--r--   0 root         (0) root         (0)       88 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud/
--rw-r--r--   0 root         (0) root         (0)      630 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud/tbaas/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud/tbaas/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud/tbaas/v20180416/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud/tbaas/v20180416/__init__.py
--rw-r--r--   0 root         (0) root         (0)    27553 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud/tbaas/v20180416/tbaas_client.py
--rw-r--r--   0 root         (0) root         (0)    95691 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud/tbaas/v20180416/models.py
--rw-r--r--   0 root         (0) root         (0)    11697 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud/tbaas/v20180416/errorcodes.py
--rw-r--r--   0 root         (0) root         (0)      743 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/README.rst
--rw-r--r--   0 root         (0) root         (0)     1669 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud_sdk_python_tbaas.egg-info/
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud_sdk_python_tbaas.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      465 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud_sdk_python_tbaas.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)     1669 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud_sdk_python_tbaas.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       13 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud_sdk_python_tbaas.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)     1010 2023-06-26 00:32:55.000000 tencentcloud-sdk-python-tbaas-3.0.921/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/
+-rw-r--r--   0 root         (0) root         (0)       88 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud/
+-rw-r--r--   0 root         (0) root         (0)      630 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud/tbaas/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud/tbaas/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud/tbaas/v20180416/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud/tbaas/v20180416/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    28041 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud/tbaas/v20180416/tbaas_client.py
+-rw-r--r--   0 root         (0) root         (0)    95691 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud/tbaas/v20180416/models.py
+-rw-r--r--   0 root         (0) root         (0)    11697 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud/tbaas/v20180416/errorcodes.py
+-rw-r--r--   0 root         (0) root         (0)      743 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/README.rst
+-rw-r--r--   0 root         (0) root         (0)     1669 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud_sdk_python_tbaas.egg-info/
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud_sdk_python_tbaas.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      465 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud_sdk_python_tbaas.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)     1669 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud_sdk_python_tbaas.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud_sdk_python_tbaas.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)     1010 2023-06-27 00:33:11.000000 tencentcloud-sdk-python-tbaas-3.0.922/setup.py
```

### Comparing `tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud/__init__.py` & `tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -10,8 +10,8 @@
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 
 
-__version__ = '3.0.921'
+__version__ = '3.0.922'
```

### Comparing `tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud/tbaas/v20180416/tbaas_client.py` & `tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud/tbaas/v20180416/tbaas_client.py`

 * *Files 8% similar despite different names*

```diff
@@ -69,15 +69,17 @@
             if isinstance(e, TencentCloudSDKException):
                 raise
             else:
                 raise TencentCloudSDKException(e.message, e.message)
 
 
     def CreateChaincodeAndInstallForUser(self, request):
-        """创建并安装合约
+        """接口已废弃，请通过控制台查询或操作
+
+        创建并安装合约
 
         :param request: Request instance for CreateChaincodeAndInstallForUser.
         :type request: :class:`tencentcloud.tbaas.v20180416.models.CreateChaincodeAndInstallForUserRequest`
         :rtype: :class:`tencentcloud.tbaas.v20180416.models.CreateChaincodeAndInstallForUserResponse`
 
         """
         try:
@@ -161,15 +163,17 @@
             if isinstance(e, TencentCloudSDKException):
                 raise
             else:
                 raise TencentCloudSDKException(e.message, e.message)
 
 
     def GetChaincodeCompileLogForUser(self, request):
-        """获取合约编译日志
+        """接口已废弃，请通过控制台查询或操作
+
+        获取合约编译日志
 
         :param request: Request instance for GetChaincodeCompileLogForUser.
         :type request: :class:`tencentcloud.tbaas.v20180416.models.GetChaincodeCompileLogForUserRequest`
         :rtype: :class:`tencentcloud.tbaas.v20180416.models.GetChaincodeCompileLogForUserResponse`
 
         """
         try:
@@ -184,15 +188,17 @@
             if isinstance(e, TencentCloudSDKException):
                 raise
             else:
                 raise TencentCloudSDKException(e.message, e.message)
 
 
     def GetChaincodeInitializeResultForUser(self, request):
-        """实例化结果查询
+        """接口已废弃，请通过控制台查询或操作
+
+        实例化结果查询
 
         :param request: Request instance for GetChaincodeInitializeResultForUser.
         :type request: :class:`tencentcloud.tbaas.v20180416.models.GetChaincodeInitializeResultForUserRequest`
         :rtype: :class:`tencentcloud.tbaas.v20180416.models.GetChaincodeInitializeResultForUserResponse`
 
         """
         try:
@@ -207,15 +213,17 @@
             if isinstance(e, TencentCloudSDKException):
                 raise
             else:
                 raise TencentCloudSDKException(e.message, e.message)
 
 
     def GetChaincodeLogForUser(self, request):
-        """获取合约容器日志
+        """接口已废弃，请通过控制台查询或操作
+
+        获取合约容器日志
 
         :param request: Request instance for GetChaincodeLogForUser.
         :type request: :class:`tencentcloud.tbaas.v20180416.models.GetChaincodeLogForUserRequest`
         :rtype: :class:`tencentcloud.tbaas.v20180416.models.GetChaincodeLogForUserResponse`
 
         """
         try:
@@ -230,15 +238,17 @@
             if isinstance(e, TencentCloudSDKException):
                 raise
             else:
                 raise TencentCloudSDKException(e.message, e.message)
 
 
     def GetChannelListForUser(self, request):
-        """获取通道列表
+        """接口已废弃，请通过控制台查询或操作
+
+        获取通道列表
 
         :param request: Request instance for GetChannelListForUser.
         :type request: :class:`tencentcloud.tbaas.v20180416.models.GetChannelListForUserRequest`
         :rtype: :class:`tencentcloud.tbaas.v20180416.models.GetChannelListForUserResponse`
 
         """
         try:
@@ -253,15 +263,17 @@
             if isinstance(e, TencentCloudSDKException):
                 raise
             else:
                 raise TencentCloudSDKException(e.message, e.message)
 
 
     def GetClusterListForUser(self, request):
-        """获取该用户的网络列表。网络信息中包含组织信息，但仅包含该用户所在组织的信息。
+        """接口已废弃，请通过控制台查询或操作
+
+        获取该用户的网络列表。网络信息中包含组织信息，但仅包含该用户所在组织的信息。
 
         :param request: Request instance for GetClusterListForUser.
         :type request: :class:`tencentcloud.tbaas.v20180416.models.GetClusterListForUserRequest`
         :rtype: :class:`tencentcloud.tbaas.v20180416.models.GetClusterListForUserResponse`
 
         """
         try:
@@ -368,15 +380,17 @@
             if isinstance(e, TencentCloudSDKException):
                 raise
             else:
                 raise TencentCloudSDKException(e.message, e.message)
 
 
     def GetPeerLogForUser(self, request):
-        """获取节点日志
+        """接口已废弃，请通过控制台查询或操作
+
+        获取节点日志
 
         :param request: Request instance for GetPeerLogForUser.
         :type request: :class:`tencentcloud.tbaas.v20180416.models.GetPeerLogForUserRequest`
         :rtype: :class:`tencentcloud.tbaas.v20180416.models.GetPeerLogForUserResponse`
 
         """
         try:
@@ -414,15 +428,17 @@
             if isinstance(e, TencentCloudSDKException):
                 raise
             else:
                 raise TencentCloudSDKException(e.message, e.message)
 
 
     def InitializeChaincodeForUser(self, request):
-        """实例化合约
+        """接口已废弃，请通过控制台查询或操作
+
+        实例化合约
 
         :param request: Request instance for InitializeChaincodeForUser.
         :type request: :class:`tencentcloud.tbaas.v20180416.models.InitializeChaincodeForUserRequest`
         :rtype: :class:`tencentcloud.tbaas.v20180416.models.InitializeChaincodeForUserResponse`
 
         """
         try:
```

### Comparing `tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud/tbaas/v20180416/models.py` & `tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud/tbaas/v20180416/models.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud/tbaas/v20180416/errorcodes.py` & `tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud/tbaas/v20180416/errorcodes.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-tbaas-3.0.921/README.rst` & `tencentcloud-sdk-python-tbaas-3.0.922/README.rst`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-tbaas-3.0.921/PKG-INFO` & `tencentcloud-sdk-python-tbaas-3.0.922/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-tbaas
-Version: 3.0.921
+Version: 3.0.922
 Summary: Tencent Cloud Tbaas SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-tbaas-3.0.921/tencentcloud_sdk_python_tbaas.egg-info/PKG-INFO` & `tencentcloud-sdk-python-tbaas-3.0.922/tencentcloud_sdk_python_tbaas.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-tbaas
-Version: 3.0.921
+Version: 3.0.922
 Summary: Tencent Cloud Tbaas SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-tbaas-3.0.921/setup.py` & `tencentcloud-sdk-python-tbaas-3.0.922/setup.py`

 * *Files identical despite different names*


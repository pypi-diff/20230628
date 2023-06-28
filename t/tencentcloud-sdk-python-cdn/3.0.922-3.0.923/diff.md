# Comparing `tmp/tencentcloud-sdk-python-cdn-3.0.922.tar.gz` & `tmp/tencentcloud-sdk-python-cdn-3.0.923.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/tencentcloud-sdk-python-cdn-3.0.922.tar", last modified: Tue Jun 27 00:19:31 2023, max compression
+gzip compressed data, was "dist/tencentcloud-sdk-python-cdn-3.0.923.tar", last modified: Wed Jun 28 00:21:44 2023, max compression
```

## Comparing `tencentcloud-sdk-python-cdn-3.0.922.tar` & `tencentcloud-sdk-python-cdn-3.0.923.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/
--rw-r--r--   0 root         (0) root         (0)       88 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/tencentcloud/
--rw-r--r--   0 root         (0) root         (0)      630 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/tencentcloud/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/tencentcloud/cdn/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/tencentcloud/cdn/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/tencentcloud/cdn/v20180606/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/tencentcloud/cdn/v20180606/__init__.py
--rw-r--r--   0 root         (0) root         (0)   575031 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/tencentcloud/cdn/v20180606/models.py
--rw-r--r--   0 root         (0) root         (0)    82219 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/tencentcloud/cdn/v20180606/cdn_client.py
--rw-r--r--   0 root         (0) root         (0)    21972 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/tencentcloud/cdn/v20180606/errorcodes.py
--rw-r--r--   0 root         (0) root         (0)      737 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/README.rst
--rw-r--r--   0 root         (0) root         (0)     1659 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/tencentcloud_sdk_python_cdn.egg-info/
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/tencentcloud_sdk_python_cdn.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      445 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/tencentcloud_sdk_python_cdn.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)     1659 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/tencentcloud_sdk_python_cdn.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       13 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/tencentcloud_sdk_python_cdn.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)     1006 2023-06-27 00:19:31.000000 tencentcloud-sdk-python-cdn-3.0.922/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:21:44.000000 tencentcloud-sdk-python-cdn-3.0.923/
+-rw-r--r--   0 root         (0) root         (0)       88 2023-06-28 00:21:44.000000 tencentcloud-sdk-python-cdn-3.0.923/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:21:44.000000 tencentcloud-sdk-python-cdn-3.0.923/tencentcloud/
+-rw-r--r--   0 root         (0) root         (0)      630 2023-06-28 00:21:43.000000 tencentcloud-sdk-python-cdn-3.0.923/tencentcloud/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:21:44.000000 tencentcloud-sdk-python-cdn-3.0.923/tencentcloud/cdn/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 00:21:43.000000 tencentcloud-sdk-python-cdn-3.0.923/tencentcloud/cdn/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:21:44.000000 tencentcloud-sdk-python-cdn-3.0.923/tencentcloud/cdn/v20180606/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 00:21:43.000000 tencentcloud-sdk-python-cdn-3.0.923/tencentcloud/cdn/v20180606/__init__.py
+-rw-r--r--   0 root         (0) root         (0)   575037 2023-06-28 00:21:43.000000 tencentcloud-sdk-python-cdn-3.0.923/tencentcloud/cdn/v20180606/models.py
+-rw-r--r--   0 root         (0) root         (0)    82139 2023-06-28 00:21:43.000000 tencentcloud-sdk-python-cdn-3.0.923/tencentcloud/cdn/v20180606/cdn_client.py
+-rw-r--r--   0 root         (0) root         (0)    22160 2023-06-28 00:21:43.000000 tencentcloud-sdk-python-cdn-3.0.923/tencentcloud/cdn/v20180606/errorcodes.py
+-rw-r--r--   0 root         (0) root         (0)      737 2023-06-28 00:21:43.000000 tencentcloud-sdk-python-cdn-3.0.923/README.rst
+-rw-r--r--   0 root         (0) root         (0)     1659 2023-06-28 00:21:44.000000 tencentcloud-sdk-python-cdn-3.0.923/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:21:44.000000 tencentcloud-sdk-python-cdn-3.0.923/tencentcloud_sdk_python_cdn.egg-info/
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 00:21:44.000000 tencentcloud-sdk-python-cdn-3.0.923/tencentcloud_sdk_python_cdn.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      445 2023-06-28 00:21:44.000000 tencentcloud-sdk-python-cdn-3.0.923/tencentcloud_sdk_python_cdn.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)     1659 2023-06-28 00:21:44.000000 tencentcloud-sdk-python-cdn-3.0.923/tencentcloud_sdk_python_cdn.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-28 00:21:44.000000 tencentcloud-sdk-python-cdn-3.0.923/tencentcloud_sdk_python_cdn.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)     1006 2023-06-28 00:21:43.000000 tencentcloud-sdk-python-cdn-3.0.923/setup.py
```

### Comparing `tencentcloud-sdk-python-cdn-3.0.922/tencentcloud/__init__.py` & `tencentcloud-sdk-python-cdn-3.0.923/tencentcloud/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -10,8 +10,8 @@
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 
 
-__version__ = '3.0.922'
+__version__ = '3.0.923'
```

### Comparing `tencentcloud-sdk-python-cdn-3.0.922/tencentcloud/cdn/v20180606/models.py` & `tencentcloud-sdk-python-cdn-3.0.923/tencentcloud/cdn/v20180606/models.py`

 * *Files 0% similar despite different names*

```diff
@@ -15144,15 +15144,15 @@
         :type BandwidthAlert: :class:`tencentcloud.cdn.v20180606.models.BandwidthAlert`
         :param RangeOriginPull: Range 回源配置
         :type RangeOriginPull: :class:`tencentcloud.cdn.v20180606.models.RangeOriginPull`
         :param FollowRedirect: 301/302 回源跟随配置
         :type FollowRedirect: :class:`tencentcloud.cdn.v20180606.models.FollowRedirect`
         :param ErrorPage: 错误码重定向配置（功能灰度中，尚未全量）
         :type ErrorPage: :class:`tencentcloud.cdn.v20180606.models.ErrorPage`
-        :param RequestHeader: 请求头部配置
+        :param RequestHeader: 回源请求头部配置
         :type RequestHeader: :class:`tencentcloud.cdn.v20180606.models.RequestHeader`
         :param ResponseHeader: 响应头部配置
         :type ResponseHeader: :class:`tencentcloud.cdn.v20180606.models.ResponseHeader`
         :param DownstreamCapping: 下载速度配置
         :type DownstreamCapping: :class:`tencentcloud.cdn.v20180606.models.DownstreamCapping`
         :param CacheKey: 节点缓存键配置
         :type CacheKey: :class:`tencentcloud.cdn.v20180606.models.CacheKey`
```

### Comparing `tencentcloud-sdk-python-cdn-3.0.922/tencentcloud/cdn/v20180606/cdn_client.py` & `tencentcloud-sdk-python-cdn-3.0.923/tencentcloud/cdn/v20180606/cdn_client.py`

 * *Files 0% similar despite different names*

```diff
@@ -1830,16 +1830,16 @@
             if isinstance(e, TencentCloudSDKException):
                 raise
             else:
                 raise TencentCloudSDKException(e.message, e.message)
 
 
     def UpdateDomainConfig(self, request):
-        """UpdateDomainConfig 用于修改内容分发网络加速域名配置信息
-        注意：如果需要更新复杂类型的配置项，必须传递整个对象的所有属性，未传递的属性将使用默认值，建议通过查询接口获取配置属性后，直接修改后传递给本接口。Https配置由于证书的特殊性，更新时不用传递证书和密钥字段。
+        """UpdateDomainConfig 用于修改内容分发网络加速域名配置信息。
+        注意：如果需要更新复杂类型的配置项，必须传递整个对象的所有属性，未传递的属性将使用默认值，建议通过查询接口获取配置属性后，直接修改后传递给本接口。
         云审计相关：接口的入参可能包含密钥等敏感信息，所以此接口的入参不会上报到云审计。
 
         :param request: Request instance for UpdateDomainConfig.
         :type request: :class:`tencentcloud.cdn.v20180606.models.UpdateDomainConfigRequest`
         :rtype: :class:`tencentcloud.cdn.v20180606.models.UpdateDomainConfigResponse`
 
         """
```

### Comparing `tencentcloud-sdk-python-cdn-3.0.922/tencentcloud/cdn/v20180606/errorcodes.py` & `tencentcloud-sdk-python-cdn-3.0.923/tencentcloud/cdn/v20180606/errorcodes.py`

 * *Files 1% similar despite different names*

```diff
@@ -352,14 +352,17 @@
 
 # 缺少参数错误。
 MISSINGPARAMETER = 'MissingParameter'
 
 # 操作被拒绝。
 OPERATIONDENIED = 'OperationDenied'
 
+# 所选目标域名与当前域名平台不一致，请重新选择或联系腾讯云技术支持
+OPERATIONDENIED_SHARECACHEAREADNSNOTMATCH = 'OperationDenied.ShareCacheAreaDnsNotMatch'
+
 # 请求的次数超过了频率限制。
 REQUESTLIMITEXCEEDED = 'RequestLimitExceeded'
 
 # 域名与系统中已存在域名存在冲突。
 RESOURCEINUSE_CDNCONFLICTHOSTEXISTS = 'ResourceInUse.CdnConflictHostExists'
 
 # 域名已存在。
```

### Comparing `tencentcloud-sdk-python-cdn-3.0.922/README.rst` & `tencentcloud-sdk-python-cdn-3.0.923/README.rst`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-cdn-3.0.922/PKG-INFO` & `tencentcloud-sdk-python-cdn-3.0.923/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-cdn
-Version: 3.0.922
+Version: 3.0.923
 Summary: Tencent Cloud Cdn SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-cdn-3.0.922/tencentcloud_sdk_python_cdn.egg-info/PKG-INFO` & `tencentcloud-sdk-python-cdn-3.0.923/tencentcloud_sdk_python_cdn.egg-info/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-cdn
-Version: 3.0.922
+Version: 3.0.923
 Summary: Tencent Cloud Cdn SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-cdn-3.0.922/setup.py` & `tencentcloud-sdk-python-cdn-3.0.923/setup.py`

 * *Files identical despite different names*


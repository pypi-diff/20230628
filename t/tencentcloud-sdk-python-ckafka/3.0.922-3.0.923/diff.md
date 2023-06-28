# Comparing `tmp/tencentcloud-sdk-python-ckafka-3.0.922.tar.gz` & `tmp/tencentcloud-sdk-python-ckafka-3.0.923.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/tencentcloud-sdk-python-ckafka-3.0.922.tar", last modified: Tue Jun 27 00:20:38 2023, max compression
+gzip compressed data, was "dist/tencentcloud-sdk-python-ckafka-3.0.923.tar", last modified: Wed Jun 28 00:22:49 2023, max compression
```

## Comparing `tencentcloud-sdk-python-ckafka-3.0.922.tar` & `tencentcloud-sdk-python-ckafka-3.0.923.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/
--rw-r--r--   0 root         (0) root         (0)       88 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud/
--rw-r--r--   0 root         (0) root         (0)      630 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud/ckafka/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud/ckafka/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud/ckafka/v20190819/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud/ckafka/v20190819/__init__.py
--rw-r--r--   0 root         (0) root         (0)   486738 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud/ckafka/v20190819/models.py
--rw-r--r--   0 root         (0) root         (0)    71620 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud/ckafka/v20190819/ckafka_client.py
--rw-r--r--   0 root         (0) root         (0)     3315 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud/ckafka/v20190819/errorcodes.py
--rw-r--r--   0 root         (0) root         (0)      746 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/README.rst
--rw-r--r--   0 root         (0) root         (0)     1674 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud_sdk_python_ckafka.egg-info/
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud_sdk_python_ckafka.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      475 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud_sdk_python_ckafka.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)     1674 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud_sdk_python_ckafka.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       13 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud_sdk_python_ckafka.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)     1012 2023-06-27 00:20:38.000000 tencentcloud-sdk-python-ckafka-3.0.922/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/
+-rw-r--r--   0 root         (0) root         (0)       88 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud/
+-rw-r--r--   0 root         (0) root         (0)      630 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud/ckafka/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud/ckafka/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud/ckafka/v20190819/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud/ckafka/v20190819/__init__.py
+-rw-r--r--   0 root         (0) root         (0)   486907 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud/ckafka/v20190819/models.py
+-rw-r--r--   0 root         (0) root         (0)    71620 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud/ckafka/v20190819/ckafka_client.py
+-rw-r--r--   0 root         (0) root         (0)     3315 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud/ckafka/v20190819/errorcodes.py
+-rw-r--r--   0 root         (0) root         (0)      746 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/README.rst
+-rw-r--r--   0 root         (0) root         (0)     1674 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud_sdk_python_ckafka.egg-info/
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud_sdk_python_ckafka.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      475 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud_sdk_python_ckafka.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)     1674 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud_sdk_python_ckafka.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud_sdk_python_ckafka.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)     1012 2023-06-28 00:22:49.000000 tencentcloud-sdk-python-ckafka-3.0.923/setup.py
```

### Comparing `tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud/__init__.py` & `tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud/__init__.py`

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

### Comparing `tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud/ckafka/v20190819/models.py` & `tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud/ckafka/v20190819/models.py`

 * *Files 0% similar despite different names*

```diff
@@ -5036,15 +5036,15 @@
         r"""
         :param InstanceId: ckafka实例id。
         :type InstanceId: str
         :param GroupName: 可选，用户需要查询的group名称。
         :type GroupName: str
         :param TopicName: 可选，用户需要查询的group中的对应的topic名称，如果指定了该参数，而group又未指定则忽略该参数。
         :type TopicName: str
-        :param Limit: 本次返回个数限制
+        :param Limit: 本次返回个数限制，最大支持50
         :type Limit: int
         :param Offset: 偏移位置
         :type Offset: int
         """
         self.InstanceId = None
         self.GroupName = None
         self.TopicName = None
@@ -8075,29 +8075,29 @@
 class InquireCkafkaPriceRequest(AbstractModel):
     """InquireCkafkaPrice请求参数结构体
 
     """
 
     def __init__(self):
         r"""
-        :param InstanceType: 国内站标准版填写standards2, 专业版填写profession
+        :param InstanceType: 国内站标准版填写standards2, 国际站标准版填写standard，专业版填写profession
         :type InstanceType: str
         :param InstanceChargeParam: 购买/续费付费类型(购买时不填的话, 默认获取购买包年包月一个月的费用)
         :type InstanceChargeParam: :class:`tencentcloud.ckafka.v20190819.models.InstanceChargeParam`
         :param InstanceNum: 购买/续费时购买的实例数量(不填时, 默认为1个)
         :type InstanceNum: int
-        :param Bandwidth: 实例内网带宽大小, 单位MB/s (购买时必填)
+        :param Bandwidth: 实例内网带宽大小, 单位MB/s (购买时必填，专业版询价时带宽信息必填)
         :type Bandwidth: int
-        :param InquiryDiskParam: 实例的硬盘购买类型以及大小 (购买时必填)
+        :param InquiryDiskParam: 实例的硬盘购买类型以及大小 (购买时必填，专业版询价时磁盘信息必填)
         :type InquiryDiskParam: :class:`tencentcloud.ckafka.v20190819.models.InquiryDiskParam`
         :param MessageRetention: 实例消息保留时间大小, 单位小时 (购买时必填)
         :type MessageRetention: int
         :param Topic: 购买实例topic数, 单位个 (购买时必填)
         :type Topic: int
-        :param Partition: 购买实例分区数, 单位个 (购买时必填)
+        :param Partition: 购买实例分区数, 单位个 (购买时必填，专业版询价时带宽信息必填)
         :type Partition: int
         :param ZoneIds: 购买地域, 可通过查看DescribeCkafkaZone这个接口获取ZoneId
         :type ZoneIds: list of int
         :param CategoryAction: 标记操作, 新购填写purchase, 续费填写renew, (不填时, 默认为purchase)
         :type CategoryAction: str
         :param BillType: 国内站购买的版本, sv_ckafka_instance_s2_1(入门型), sv_ckafka_instance_s2_2(标准版), sv_ckafka_instance_s2_3(进阶型), 如果instanceType为standards2, 但该参数为空, 则默认值为sv_ckafka_instance_s2_1
         :type BillType: str
```

### Comparing `tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud/ckafka/v20190819/ckafka_client.py` & `tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud/ckafka/v20190819/ckafka_client.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud/ckafka/v20190819/errorcodes.py` & `tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud/ckafka/v20190819/errorcodes.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-ckafka-3.0.922/README.rst` & `tencentcloud-sdk-python-ckafka-3.0.923/README.rst`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-ckafka-3.0.922/PKG-INFO` & `tencentcloud-sdk-python-ckafka-3.0.923/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-ckafka
-Version: 3.0.922
+Version: 3.0.923
 Summary: Tencent Cloud Ckafka SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-ckafka-3.0.922/tencentcloud_sdk_python_ckafka.egg-info/PKG-INFO` & `tencentcloud-sdk-python-ckafka-3.0.923/tencentcloud_sdk_python_ckafka.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-ckafka
-Version: 3.0.922
+Version: 3.0.923
 Summary: Tencent Cloud Ckafka SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-ckafka-3.0.922/setup.py` & `tencentcloud-sdk-python-ckafka-3.0.923/setup.py`

 * *Files identical despite different names*


# Comparing `tmp/tencentcloud-sdk-python-redis-3.0.922.tar.gz` & `tmp/tencentcloud-sdk-python-redis-3.0.923.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/tencentcloud-sdk-python-redis-3.0.922.tar", last modified: Tue Jun 27 00:30:54 2023, max compression
+gzip compressed data, was "dist/tencentcloud-sdk-python-redis-3.0.923.tar", last modified: Wed Jun 28 00:33:17 2023, max compression
```

## Comparing `tencentcloud-sdk-python-redis-3.0.922.tar` & `tencentcloud-sdk-python-redis-3.0.923.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/tencentcloud_sdk_python_redis.egg-info/
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/tencentcloud_sdk_python_redis.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      465 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/tencentcloud_sdk_python_redis.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)     1669 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/tencentcloud_sdk_python_redis.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       13 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/tencentcloud_sdk_python_redis.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)       88 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/tencentcloud/
--rw-r--r--   0 root         (0) root         (0)      630 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/tencentcloud/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/tencentcloud/redis/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/tencentcloud/redis/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/tencentcloud/redis/v20180412/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/tencentcloud/redis/v20180412/__init__.py
--rw-r--r--   0 root         (0) root         (0)    87184 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/tencentcloud/redis/v20180412/redis_client.py
--rw-r--r--   0 root         (0) root         (0)   298078 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/tencentcloud/redis/v20180412/models.py
--rw-r--r--   0 root         (0) root         (0)    12423 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/tencentcloud/redis/v20180412/errorcodes.py
--rw-r--r--   0 root         (0) root         (0)      743 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/README.rst
--rw-r--r--   0 root         (0) root         (0)     1669 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     1010 2023-06-27 00:30:54.000000 tencentcloud-sdk-python-redis-3.0.922/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/tencentcloud_sdk_python_redis.egg-info/
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/tencentcloud_sdk_python_redis.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      465 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/tencentcloud_sdk_python_redis.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)     1669 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/tencentcloud_sdk_python_redis.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/tencentcloud_sdk_python_redis.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)       88 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/tencentcloud/
+-rw-r--r--   0 root         (0) root         (0)      630 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/tencentcloud/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/tencentcloud/redis/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/tencentcloud/redis/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/tencentcloud/redis/v20180412/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/tencentcloud/redis/v20180412/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    87353 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/tencentcloud/redis/v20180412/redis_client.py
+-rw-r--r--   0 root         (0) root         (0)   299340 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/tencentcloud/redis/v20180412/models.py
+-rw-r--r--   0 root         (0) root         (0)    12423 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/tencentcloud/redis/v20180412/errorcodes.py
+-rw-r--r--   0 root         (0) root         (0)      743 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/README.rst
+-rw-r--r--   0 root         (0) root         (0)     1669 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     1010 2023-06-28 00:33:17.000000 tencentcloud-sdk-python-redis-3.0.923/setup.py
```

### Comparing `tencentcloud-sdk-python-redis-3.0.922/tencentcloud_sdk_python_redis.egg-info/PKG-INFO` & `tencentcloud-sdk-python-redis-3.0.923/tencentcloud_sdk_python_redis.egg-info/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-redis
-Version: 3.0.922
+Version: 3.0.923
 Summary: Tencent Cloud Redis SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-redis-3.0.922/tencentcloud/__init__.py` & `tencentcloud-sdk-python-redis-3.0.923/tencentcloud/__init__.py`

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

### Comparing `tencentcloud-sdk-python-redis-3.0.922/tencentcloud/redis/v20180412/redis_client.py` & `tencentcloud-sdk-python-redis-3.0.923/tencentcloud/redis/v20180412/redis_client.py`

 * *Files 0% similar despite different names*

```diff
@@ -138,15 +138,15 @@
             if isinstance(e, TencentCloudSDKException):
                 raise
             else:
                 raise TencentCloudSDKException(e.message, e.message)
 
 
     def ChangeMasterInstance(self, request):
-        """复制组实例切主
+        """该接口（ChangeMasterInstance）用于将复制组内只读实例设置为主实例。
 
         :param request: Request instance for ChangeMasterInstance.
         :type request: :class:`tencentcloud.redis.v20180412.models.ChangeMasterInstanceRequest`
         :rtype: :class:`tencentcloud.redis.v20180412.models.ChangeMasterInstanceResponse`
 
         """
         try:
@@ -345,15 +345,15 @@
             if isinstance(e, TencentCloudSDKException):
                 raise
             else:
                 raise TencentCloudSDKException(e.message, e.message)
 
 
     def CreateReplicationGroup(self, request):
-        """创建复制组
+        """该接口（CreateReplicationGroup）用于创建复制组。
 
         :param request: Request instance for CreateReplicationGroup.
         :type request: :class:`tencentcloud.redis.v20180412.models.CreateReplicationGroupRequest`
         :rtype: :class:`tencentcloud.redis.v20180412.models.CreateReplicationGroupResponse`
 
         """
         try:
@@ -1173,15 +1173,15 @@
             if isinstance(e, TencentCloudSDKException):
                 raise
             else:
                 raise TencentCloudSDKException(e.message, e.message)
 
 
     def DescribeReplicationGroup(self, request):
-        """本接口（DescribeReplicationGroup）查询复制组。
+        """本接口（DescribeReplicationGroup）用于查询复制组。
 
         :param request: Request instance for DescribeReplicationGroup.
         :type request: :class:`tencentcloud.redis.v20180412.models.DescribeReplicationGroupRequest`
         :rtype: :class:`tencentcloud.redis.v20180412.models.DescribeReplicationGroupResponse`
 
         """
         try:
@@ -1242,15 +1242,15 @@
             if isinstance(e, TencentCloudSDKException):
                 raise
             else:
                 raise TencentCloudSDKException(e.message, e.message)
 
 
     def DescribeTaskInfo(self, request):
-        """用于查询任务结果
+        """本接口（DescribeTaskInfo）用于获取指定任务的执行情况。
 
         :param request: Request instance for DescribeTaskInfo.
         :type request: :class:`tencentcloud.redis.v20180412.models.DescribeTaskInfoRequest`
         :rtype: :class:`tencentcloud.redis.v20180412.models.DescribeTaskInfoResponse`
 
         """
         try:
```

### Comparing `tencentcloud-sdk-python-redis-3.0.922/tencentcloud/redis/v20180412/models.py` & `tencentcloud-sdk-python-redis-3.0.923/tencentcloud/redis/v20180412/models.py`

 * *Files 0% similar despite different names*

```diff
@@ -472,26 +472,35 @@
 class ChangeMasterInstanceRequest(AbstractModel):
     """ChangeMasterInstance请求参数结构体
 
     """
 
     def __init__(self):
         r"""
-        :param GroupId: 复制组ID
+        :param GroupId: 复制组ID。创建复制组时，系统自动分配的 ID，是复制组的唯一标识。例如：crs-rpl-m3zt****，请登录[Redis 控制台](https://console.cloud.tencent.com/redis/replication)的全球复制组列表获取复制组 ID。
+
         :type GroupId: str
-        :param InstanceId: 实例ID
+        :param InstanceId: 指定待提升为主实例的只读实例 ID。例如：crs-xjhsdj****。请登录[Redis控制台](https://console.cloud.tencent.com/redis)在实例列表复制实例 ID。
+
+
         :type InstanceId: str
+        :param ForceSwitch: 标识是否强制提主。
+- true：强制提主。
+- false：不强制提主。
+        :type ForceSwitch: bool
         """
         self.GroupId = None
         self.InstanceId = None
+        self.ForceSwitch = None
 
 
     def _deserialize(self, params):
         self.GroupId = params.get("GroupId")
         self.InstanceId = params.get("InstanceId")
+        self.ForceSwitch = params.get("ForceSwitch")
         memeber_set = set(params.keys())
         for name, value in vars(self).items():
             if name in memeber_set:
                 memeber_set.remove(name)
         if len(memeber_set) > 0:
             warnings.warn("%s fileds are useless." % ",".join(memeber_set))
         
@@ -500,15 +509,15 @@
 class ChangeMasterInstanceResponse(AbstractModel):
     """ChangeMasterInstance返回参数结构体
 
     """
 
     def __init__(self):
         r"""
-        :param TaskId: 异步流程ID
+        :param TaskId: 异步流程ID。
         :type TaskId: int
         :param RequestId: 唯一请求 ID，每次请求都会返回。定位问题时需要提供该次请求的 RequestId。
         :type RequestId: str
         """
         self.TaskId = None
         self.RequestId = None
 
@@ -1197,15 +1206,15 @@
 
     """
 
     def __init__(self):
         r"""
         :param InstanceId: 指定复制组中的主实例ID。
         :type InstanceId: str
-        :param GroupName: 复制组名称。
+        :param GroupName: 复制组名称。名称只支持长度为2-64个字符的中文、英文、数字、下划线_、分隔符-。
         :type GroupName: str
         :param Remark: 备注信息。
         :type Remark: str
         """
         self.InstanceId = None
         self.GroupName = None
         self.Remark = None
@@ -3645,17 +3654,17 @@
 
     def __init__(self):
         r"""
         :param Limit: 每页输出实例列表的大小，参数默认值20。
         :type Limit: int
         :param Offset: 分页偏移量，取Limit整数倍。计算公式：offset=limit*(页码-1)。
         :type Offset: int
-        :param GroupId: 复制组ID。
+        :param GroupId: 指定复制组 ID。例如：crs-rpl-m3zt****。请登录[Redis 控制台](https://console.cloud.tencent.com/redis/replication)的全球复制组列表获取复制组 ID。
         :type GroupId: str
-        :param SearchKey: 模糊查询的关键字，可以设置为复制组ID或复制组名称进行模糊查询。
+        :param SearchKey: 模糊查询的关键字，可以设置为复制组ID或复制组名称进行模糊查询。请登录[Redis 控制台](https://console.cloud.tencent.com/redis/replication)的全球复制组列表获取复制组 ID及名称。
         :type SearchKey: str
         """
         self.Limit = None
         self.Offset = None
         self.GroupId = None
         self.SearchKey = None
 
@@ -3853,15 +3862,15 @@
 class DescribeTaskInfoRequest(AbstractModel):
     """DescribeTaskInfo请求参数结构体
 
     """
 
     def __init__(self):
         r"""
-        :param TaskId: 任务ID
+        :param TaskId: 任务 ID。
         :type TaskId: int
         """
         self.TaskId = None
 
 
     def _deserialize(self, params):
         self.TaskId = params.get("TaskId")
@@ -3877,23 +3886,28 @@
 class DescribeTaskInfoResponse(AbstractModel):
     """DescribeTaskInfo返回参数结构体
 
     """
 
     def __init__(self):
         r"""
-        :param Status: 任务状态preparing:待执行，running：执行中，succeed：成功，failed：失败，error 执行出错
+        :param Status: 任务状态。
+- preparing：待执行。
+- running：执行中。
+- succeed：成功。
+- failed：失败。
+- error：执行出错。
         :type Status: str
-        :param StartTime: 任务开始时间
+        :param StartTime: 任务开始时间。
         :type StartTime: str
-        :param TaskType: 任务类型
+        :param TaskType: 任务类型。常见的类型包含：新建类型、配置变更、关闭实例、清空实例、重置密码、版本升级、备份实例、改变网络类型、实例可用区迁移、手动提主等。
         :type TaskType: str
-        :param InstanceId: 实例的ID
+        :param InstanceId: 实例的 ID。
         :type InstanceId: str
-        :param TaskMessage: 任务信息，错误时显示错误信息。执行中与成功则为空
+        :param TaskMessage: 任务执行返回的信息，执行错误时显示错误信息。执行中或执行成功则为空。
         :type TaskMessage: str
         :param RequestId: 唯一请求 ID，每次请求都会返回。定位问题时需要提供该次请求的 RequestId。
         :type RequestId: str
         """
         self.Status = None
         self.StartTime = None
         self.TaskType = None
@@ -4368,15 +4382,14 @@
 - 16：成都 
 - 17：德国 
 - 18：韩国 
 - 19：重庆 
 - 21：印度 
 - 22：美东（弗吉尼亚）
 - 23：泰国 
-- 24：俄罗斯 
 - 25：日本
         :type RegionId: int
         :param GroupId: 复制组 ID。格式如：crs-rpl-deind****。
         :type GroupId: str
         :param GroupName: 复制组名称。
 注意：此字段可能返回 null，表示取不到有效值。
         :type GroupName: str
@@ -5632,15 +5645,15 @@
         :type ZoneId: int
         :param RedisReplicasNum: 副本数量。
         :type RedisReplicasNum: int
         :param RedisShardNum: 分片数量。
         :type RedisShardNum: int
         :param RedisShardSize: 分片内存大小。
         :type RedisShardSize: int
-        :param DiskSize: 实例的磁盘大小
+        :param DiskSize: 实例的磁盘大小。
 注意：此字段可能返回 null，表示取不到有效值。
         :type DiskSize: int
         :param Engine: 引擎：社区版Redis、腾讯云CKV。
         :type Engine: str
         :param Role: 实例读写权限。<ul><li>rw：可读写。</li><li>r：只读。</li></ul>
         :type Role: str
         :param Vip: 实例 VIP 地址。
```

### Comparing `tencentcloud-sdk-python-redis-3.0.922/tencentcloud/redis/v20180412/errorcodes.py` & `tencentcloud-sdk-python-redis-3.0.923/tencentcloud/redis/v20180412/errorcodes.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-redis-3.0.922/README.rst` & `tencentcloud-sdk-python-redis-3.0.923/README.rst`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-redis-3.0.922/PKG-INFO` & `tencentcloud-sdk-python-redis-3.0.923/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-redis
-Version: 3.0.922
+Version: 3.0.923
 Summary: Tencent Cloud Redis SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-redis-3.0.922/setup.py` & `tencentcloud-sdk-python-redis-3.0.923/setup.py`

 * *Files identical despite different names*


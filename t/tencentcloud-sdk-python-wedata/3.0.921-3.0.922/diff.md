# Comparing `tmp/tencentcloud-sdk-python-wedata-3.0.921.tar.gz` & `tmp/tencentcloud-sdk-python-wedata-3.0.922.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/tencentcloud-sdk-python-wedata-3.0.921.tar", last modified: Mon Jun 26 00:37:28 2023, max compression
+gzip compressed data, was "dist/tencentcloud-sdk-python-wedata-3.0.922.tar", last modified: Tue Jun 27 00:38:04 2023, max compression
```

## Comparing `tencentcloud-sdk-python-wedata-3.0.921.tar` & `tencentcloud-sdk-python-wedata-3.0.922.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/
--rw-r--r--   0 root         (0) root         (0)       88 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/tencentcloud/
--rw-r--r--   0 root         (0) root         (0)      630 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/tencentcloud/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/tencentcloud/wedata/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/tencentcloud/wedata/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/tencentcloud/wedata/v20210820/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/tencentcloud/wedata/v20210820/__init__.py
--rw-r--r--   0 root         (0) root         (0)   725096 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/tencentcloud/wedata/v20210820/models.py
--rw-r--r--   0 root         (0) root         (0)   185172 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/tencentcloud/wedata/v20210820/wedata_client.py
--rw-r--r--   0 root         (0) root         (0)     3451 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/tencentcloud/wedata/v20210820/errorcodes.py
--rw-r--r--   0 root         (0) root         (0)      746 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/README.rst
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/tencentcloud_sdk_python_wedata.egg-info/
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/tencentcloud_sdk_python_wedata.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      475 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/tencentcloud_sdk_python_wedata.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)     1674 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/tencentcloud_sdk_python_wedata.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       13 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/tencentcloud_sdk_python_wedata.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)     1674 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     1012 2023-06-26 00:37:28.000000 tencentcloud-sdk-python-wedata-3.0.921/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/
+-rw-r--r--   0 root         (0) root         (0)       88 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/tencentcloud/
+-rw-r--r--   0 root         (0) root         (0)      630 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/tencentcloud/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/tencentcloud/wedata/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/tencentcloud/wedata/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/tencentcloud/wedata/v20210820/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/tencentcloud/wedata/v20210820/__init__.py
+-rw-r--r--   0 root         (0) root         (0)   728993 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/tencentcloud/wedata/v20210820/models.py
+-rw-r--r--   0 root         (0) root         (0)   185172 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/tencentcloud/wedata/v20210820/wedata_client.py
+-rw-r--r--   0 root         (0) root         (0)     3451 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/tencentcloud/wedata/v20210820/errorcodes.py
+-rw-r--r--   0 root         (0) root         (0)      746 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/README.rst
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/tencentcloud_sdk_python_wedata.egg-info/
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/tencentcloud_sdk_python_wedata.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      475 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/tencentcloud_sdk_python_wedata.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)     1674 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/tencentcloud_sdk_python_wedata.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/tencentcloud_sdk_python_wedata.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)     1674 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     1012 2023-06-27 00:38:04.000000 tencentcloud-sdk-python-wedata-3.0.922/setup.py
```

### Comparing `tencentcloud-sdk-python-wedata-3.0.921/tencentcloud/__init__.py` & `tencentcloud-sdk-python-wedata-3.0.922/tencentcloud/__init__.py`

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

### Comparing `tencentcloud-sdk-python-wedata-3.0.921/tencentcloud/wedata/v20210820/models.py` & `tencentcloud-sdk-python-wedata-3.0.922/tencentcloud/wedata/v20210820/models.py`

 * *Files 0% similar despite different names*

```diff
@@ -5306,24 +5306,33 @@
         r"""
         :param StatisticsDate: 统计日期 时间戳
         :type StatisticsDate: int
         :param ProjectId: 项目id
         :type ProjectId: str
         :param DatasourceId: 数据来源id
         :type DatasourceId: str
+        :param Filters: 过滤参数
+        :type Filters: list of Filter
         """
         self.StatisticsDate = None
         self.ProjectId = None
         self.DatasourceId = None
+        self.Filters = None
 
 
     def _deserialize(self, params):
         self.StatisticsDate = params.get("StatisticsDate")
         self.ProjectId = params.get("ProjectId")
         self.DatasourceId = params.get("DatasourceId")
+        if params.get("Filters") is not None:
+            self.Filters = []
+            for item in params.get("Filters"):
+                obj = Filter()
+                obj._deserialize(item)
+                self.Filters.append(obj)
         memeber_set = set(params.keys())
         for name, value in vars(self).items():
             if name in memeber_set:
                 memeber_set.remove(name)
         if len(memeber_set) > 0:
             warnings.warn("%s fileds are useless." % ",".join(memeber_set))
         
@@ -7565,24 +7574,37 @@
         r"""
         :param StatisticsDate: 统计日期
         :type StatisticsDate: int
         :param ProjectId: 项目id
         :type ProjectId: str
         :param DatasourceId: 数据来源id
         :type DatasourceId: str
+        :param ScoreType: 1:按全维度权重计算,2:按已配置维度权重计算,3:不按维度权重计算,默认1
+        :type ScoreType: str
+        :param Filters: 过滤参数
+        :type Filters: list of Filter
         """
         self.StatisticsDate = None
         self.ProjectId = None
         self.DatasourceId = None
+        self.ScoreType = None
+        self.Filters = None
 
 
     def _deserialize(self, params):
         self.StatisticsDate = params.get("StatisticsDate")
         self.ProjectId = params.get("ProjectId")
         self.DatasourceId = params.get("DatasourceId")
+        self.ScoreType = params.get("ScoreType")
+        if params.get("Filters") is not None:
+            self.Filters = []
+            for item in params.get("Filters"):
+                obj = Filter()
+                obj._deserialize(item)
+                self.Filters.append(obj)
         memeber_set = set(params.keys())
         for name, value in vars(self).items():
             if name in memeber_set:
                 memeber_set.remove(name)
         if len(memeber_set) > 0:
             warnings.warn("%s fileds are useless." % ",".join(memeber_set))
         
@@ -7623,26 +7645,39 @@
         :type StatisticsStartDate: int
         :param StatisticsEndDate: 统计结束日期
         :type StatisticsEndDate: int
         :param ProjectId: 项目id
         :type ProjectId: str
         :param DatasourceId: 数据来源id
         :type DatasourceId: str
+        :param ScoreType: 1:按全维度权重计算,2:按已配置维度权重计算,3:不按维度权重计算,默认1
+        :type ScoreType: str
+        :param Filters: 过滤参数
+        :type Filters: list of Filter
         """
         self.StatisticsStartDate = None
         self.StatisticsEndDate = None
         self.ProjectId = None
         self.DatasourceId = None
+        self.ScoreType = None
+        self.Filters = None
 
 
     def _deserialize(self, params):
         self.StatisticsStartDate = params.get("StatisticsStartDate")
         self.StatisticsEndDate = params.get("StatisticsEndDate")
         self.ProjectId = params.get("ProjectId")
         self.DatasourceId = params.get("DatasourceId")
+        self.ScoreType = params.get("ScoreType")
+        if params.get("Filters") is not None:
+            self.Filters = []
+            for item in params.get("Filters"):
+                obj = Filter()
+                obj._deserialize(item)
+                self.Filters.append(obj)
         memeber_set = set(params.keys())
         for name, value in vars(self).items():
             if name in memeber_set:
                 memeber_set.remove(name)
         if len(memeber_set) > 0:
             warnings.warn("%s fileds are useless." % ",".join(memeber_set))
         
@@ -9637,22 +9672,25 @@
         :type PageSize: int
         :param Filters: 过滤参数TableName、DatabaseId 、DatabaseName、OwnerUserName
         :type Filters: list of Filter
         :param OrderFields: 排序参数 排序方式 DESC 或者 ASC，表得分排序 TableScore
         :type OrderFields: list of OrderField
         :param DatasourceId: 数据来源id
         :type DatasourceId: str
+        :param ScoreType: 1:按全维度权重计算,2:按已配置维度权重计算,3:不按维度权重计算,默认1
+        :type ScoreType: str
         """
         self.StatisticsDate = None
         self.ProjectId = None
         self.PageNumber = None
         self.PageSize = None
         self.Filters = None
         self.OrderFields = None
         self.DatasourceId = None
+        self.ScoreType = None
 
 
     def _deserialize(self, params):
         self.StatisticsDate = params.get("StatisticsDate")
         self.ProjectId = params.get("ProjectId")
         self.PageNumber = params.get("PageNumber")
         self.PageSize = params.get("PageSize")
@@ -9665,14 +9703,15 @@
         if params.get("OrderFields") is not None:
             self.OrderFields = []
             for item in params.get("OrderFields"):
                 obj = OrderField()
                 obj._deserialize(item)
                 self.OrderFields.append(obj)
         self.DatasourceId = params.get("DatasourceId")
+        self.ScoreType = params.get("ScoreType")
         memeber_set = set(params.keys())
         for name, value in vars(self).items():
             if name in memeber_set:
                 memeber_set.remove(name)
         if len(memeber_set) > 0:
             warnings.warn("%s fileds are useless." % ",".join(memeber_set))
         
@@ -9784,26 +9823,30 @@
         :type ProjectId: str
         :param StatisticsStartDate: 开始时间 秒级时间戳
         :type StatisticsStartDate: int
         :param StatisticsEndDate: 结束时间 秒级时间戳
         :type StatisticsEndDate: int
         :param TableId: 表id
         :type TableId: str
+        :param ScoreType: 1:按全维度权重计算,2:按已配置维度权重计算,3:不按维度权重计算,默认1
+        :type ScoreType: str
         """
         self.ProjectId = None
         self.StatisticsStartDate = None
         self.StatisticsEndDate = None
         self.TableId = None
+        self.ScoreType = None
 
 
     def _deserialize(self, params):
         self.ProjectId = params.get("ProjectId")
         self.StatisticsStartDate = params.get("StatisticsStartDate")
         self.StatisticsEndDate = params.get("StatisticsEndDate")
         self.TableId = params.get("TableId")
+        self.ScoreType = params.get("ScoreType")
         memeber_set = set(params.keys())
         for name, value in vars(self).items():
             if name in memeber_set:
                 memeber_set.remove(name)
         if len(memeber_set) > 0:
             warnings.warn("%s fileds are useless." % ",".join(memeber_set))
         
@@ -10845,22 +10888,27 @@
         r"""
         :param DimType: 维度类型1：准确性，2：唯一性，3：完整性，4：一致性，5：及时性，6：有效性
 注意：此字段可能返回 null，表示取不到有效值。
         :type DimType: int
         :param Count: 统计值
 注意：此字段可能返回 null，表示取不到有效值。
         :type Count: int
+        :param QualityDim: 维度类型1：准确性，2：唯一性，3：完整性，4：一致性，5：及时性，6：有效性
+注意：此字段可能返回 null，表示取不到有效值。
+        :type QualityDim: int
         """
         self.DimType = None
         self.Count = None
+        self.QualityDim = None
 
 
     def _deserialize(self, params):
         self.DimType = params.get("DimType")
         self.Count = params.get("Count")
+        self.QualityDim = params.get("QualityDim")
         memeber_set = set(params.keys())
         for name, value in vars(self).items():
             if name in memeber_set:
                 memeber_set.remove(name)
         if len(memeber_set) > 0:
             warnings.warn("%s fileds are useless." % ",".join(memeber_set))
         
@@ -16641,14 +16689,20 @@
         :type TargetObjectDataType: str
         :param FieldConfig: 自定义模版sql表达式参数
 注意：此字段可能返回 null，表示取不到有效值。
         :type FieldConfig: :class:`tencentcloud.wedata.v20210820.models.RuleFieldConfig`
         :param RelConditionExpr: 源字段与目标字段关联条件on表达式
 注意：此字段可能返回 null，表示取不到有效值。
         :type RelConditionExpr: str
+        :param StartTime: 执行时间
+注意：此字段可能返回 null，表示取不到有效值。
+        :type StartTime: str
+        :param AlarmLevel: 1/2/3:低/中/高
+注意：此字段可能返回 null，表示取不到有效值。
+        :type AlarmLevel: int
         """
         self.RuleExecId = None
         self.RuleGroupExecId = None
         self.RuleGroupId = None
         self.RuleId = None
         self.RuleName = None
         self.RuleType = None
@@ -16661,14 +16715,16 @@
         self.TemplateName = None
         self.QualityDim = None
         self.TargetDBTableName = None
         self.TargetObjectValue = None
         self.TargetObjectDataType = None
         self.FieldConfig = None
         self.RelConditionExpr = None
+        self.StartTime = None
+        self.AlarmLevel = None
 
 
     def _deserialize(self, params):
         self.RuleExecId = params.get("RuleExecId")
         self.RuleGroupExecId = params.get("RuleGroupExecId")
         self.RuleGroupId = params.get("RuleGroupId")
         self.RuleId = params.get("RuleId")
@@ -16687,14 +16743,16 @@
         self.TargetDBTableName = params.get("TargetDBTableName")
         self.TargetObjectValue = params.get("TargetObjectValue")
         self.TargetObjectDataType = params.get("TargetObjectDataType")
         if params.get("FieldConfig") is not None:
             self.FieldConfig = RuleFieldConfig()
             self.FieldConfig._deserialize(params.get("FieldConfig"))
         self.RelConditionExpr = params.get("RelConditionExpr")
+        self.StartTime = params.get("StartTime")
+        self.AlarmLevel = params.get("AlarmLevel")
         memeber_set = set(params.keys())
         for name, value in vars(self).items():
             if name in memeber_set:
                 memeber_set.remove(name)
         if len(memeber_set) > 0:
             warnings.warn("%s fileds are useless." % ",".join(memeber_set))
         
@@ -16730,38 +16788,43 @@
         :type TableName: str
         :param RuleExecResult: 规则执行记录
 注意：此字段可能返回 null，表示取不到有效值。
         :type RuleExecResult: :class:`tencentcloud.wedata.v20210820.models.RuleExecResult`
         :param TableOwnerUserId: 表负责人userId
 注意：此字段可能返回 null，表示取不到有效值。
         :type TableOwnerUserId: int
+        :param DatasourceType: 2.HIVE 3.DLC
+注意：此字段可能返回 null，表示取不到有效值。
+        :type DatasourceType: int
         """
         self.DatasourceId = None
         self.DatasourceName = None
         self.DatabaseId = None
         self.DatabaseName = None
         self.InstanceId = None
         self.TableId = None
         self.TableName = None
         self.RuleExecResult = None
         self.TableOwnerUserId = None
+        self.DatasourceType = None
 
 
     def _deserialize(self, params):
         self.DatasourceId = params.get("DatasourceId")
         self.DatasourceName = params.get("DatasourceName")
         self.DatabaseId = params.get("DatabaseId")
         self.DatabaseName = params.get("DatabaseName")
         self.InstanceId = params.get("InstanceId")
         self.TableId = params.get("TableId")
         self.TableName = params.get("TableName")
         if params.get("RuleExecResult") is not None:
             self.RuleExecResult = RuleExecResult()
             self.RuleExecResult._deserialize(params.get("RuleExecResult"))
         self.TableOwnerUserId = params.get("TableOwnerUserId")
+        self.DatasourceType = params.get("DatasourceType")
         memeber_set = set(params.keys())
         for name, value in vars(self).items():
             if name in memeber_set:
                 memeber_set.remove(name)
         if len(memeber_set) > 0:
             warnings.warn("%s fileds are useless." % ",".join(memeber_set))
         
@@ -16987,14 +17050,17 @@
         :type RuleCount: int
         :param MonitorStatus: 监控状态
 注意：此字段可能返回 null，表示取不到有效值。
         :type MonitorStatus: bool
         :param TableOwnerUserId: 表负责人UserId
 注意：此字段可能返回 null，表示取不到有效值。
         :type TableOwnerUserId: int
+        :param InstanceId: 实例ID
+注意：此字段可能返回 null，表示取不到有效值。
+        :type InstanceId: str
         """
         self.RuleGroupId = None
         self.DatasourceId = None
         self.DatasourceName = None
         self.DatasourceType = None
         self.MonitorType = None
         self.UpdateTime = None
@@ -17005,14 +17071,15 @@
         self.Subscription = None
         self.DatabaseId = None
         self.DatabaseName = None
         self.Permission = None
         self.RuleCount = None
         self.MonitorStatus = None
         self.TableOwnerUserId = None
+        self.InstanceId = None
 
 
     def _deserialize(self, params):
         self.RuleGroupId = params.get("RuleGroupId")
         self.DatasourceId = params.get("DatasourceId")
         self.DatasourceName = params.get("DatasourceName")
         self.DatasourceType = params.get("DatasourceType")
@@ -17029,14 +17096,15 @@
             self.Subscription._deserialize(params.get("Subscription"))
         self.DatabaseId = params.get("DatabaseId")
         self.DatabaseName = params.get("DatabaseName")
         self.Permission = params.get("Permission")
         self.RuleCount = params.get("RuleCount")
         self.MonitorStatus = params.get("MonitorStatus")
         self.TableOwnerUserId = params.get("TableOwnerUserId")
+        self.InstanceId = params.get("InstanceId")
         memeber_set = set(params.keys())
         for name, value in vars(self).items():
             if name in memeber_set:
                 memeber_set.remove(name)
         if len(memeber_set) > 0:
             warnings.warn("%s fileds are useless." % ",".join(memeber_set))
         
@@ -18652,22 +18720,37 @@
         r"""
         :param SourceObjectDataTypeName: 源字段详细类型，int、string
 注意：此字段可能返回 null，表示取不到有效值。
         :type SourceObjectDataTypeName: str
         :param SourceObjectValue: 源字段名称
 注意：此字段可能返回 null，表示取不到有效值。
         :type SourceObjectValue: str
+        :param ObjectDataTypeName: 源字段详细类型，int、string
+注意：此字段可能返回 null，表示取不到有效值。
+        :type ObjectDataTypeName: str
+        :param ObjectValue: 源字段名称
+注意：此字段可能返回 null，表示取不到有效值。
+        :type ObjectValue: str
+        :param ObjectType: 对象类型 1.常量  2.离线表级   3.离线字段级
+注意：此字段可能返回 null，表示取不到有效值。
+        :type ObjectType: int
         """
         self.SourceObjectDataTypeName = None
         self.SourceObjectValue = None
+        self.ObjectDataTypeName = None
+        self.ObjectValue = None
+        self.ObjectType = None
 
 
     def _deserialize(self, params):
         self.SourceObjectDataTypeName = params.get("SourceObjectDataTypeName")
         self.SourceObjectValue = params.get("SourceObjectValue")
+        self.ObjectDataTypeName = params.get("ObjectDataTypeName")
+        self.ObjectValue = params.get("ObjectValue")
+        self.ObjectType = params.get("ObjectType")
         memeber_set = set(params.keys())
         for name, value in vars(self).items():
             if name in memeber_set:
                 memeber_set.remove(name)
         if len(memeber_set) > 0:
             warnings.warn("%s fileds are useless." % ",".join(memeber_set))
```

### Comparing `tencentcloud-sdk-python-wedata-3.0.921/tencentcloud/wedata/v20210820/wedata_client.py` & `tencentcloud-sdk-python-wedata-3.0.922/tencentcloud/wedata/v20210820/wedata_client.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-wedata-3.0.921/tencentcloud/wedata/v20210820/errorcodes.py` & `tencentcloud-sdk-python-wedata-3.0.922/tencentcloud/wedata/v20210820/errorcodes.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-wedata-3.0.921/README.rst` & `tencentcloud-sdk-python-wedata-3.0.922/README.rst`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-wedata-3.0.921/tencentcloud_sdk_python_wedata.egg-info/PKG-INFO` & `tencentcloud-sdk-python-wedata-3.0.922/tencentcloud_sdk_python_wedata.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-wedata
-Version: 3.0.921
+Version: 3.0.922
 Summary: Tencent Cloud Wedata SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-wedata-3.0.921/PKG-INFO` & `tencentcloud-sdk-python-wedata-3.0.922/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-wedata
-Version: 3.0.921
+Version: 3.0.922
 Summary: Tencent Cloud Wedata SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-wedata-3.0.921/setup.py` & `tencentcloud-sdk-python-wedata-3.0.922/setup.py`

 * *Files identical despite different names*


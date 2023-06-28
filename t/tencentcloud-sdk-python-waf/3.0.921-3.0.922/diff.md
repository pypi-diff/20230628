# Comparing `tmp/tencentcloud-sdk-python-waf-3.0.921.tar.gz` & `tmp/tencentcloud-sdk-python-waf-3.0.922.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/tencentcloud-sdk-python-waf-3.0.921.tar", last modified: Mon Jun 26 00:37:16 2023, max compression
+gzip compressed data, was "dist/tencentcloud-sdk-python-waf-3.0.922.tar", last modified: Tue Jun 27 00:37:52 2023, max compression
```

## Comparing `tencentcloud-sdk-python-waf-3.0.921.tar` & `tencentcloud-sdk-python-waf-3.0.922.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/
--rw-r--r--   0 root         (0) root         (0)       88 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/tencentcloud/
--rw-r--r--   0 root         (0) root         (0)      630 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/tencentcloud/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/tencentcloud/waf/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/tencentcloud/waf/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/tencentcloud/waf/v20180125/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/tencentcloud/waf/v20180125/__init__.py
--rw-r--r--   0 root         (0) root         (0)   180770 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/tencentcloud/waf/v20180125/models.py
--rw-r--r--   0 root         (0) root         (0)     2711 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/tencentcloud/waf/v20180125/errorcodes.py
--rw-r--r--   0 root         (0) root         (0)    46563 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/tencentcloud/waf/v20180125/waf_client.py
--rw-r--r--   0 root         (0) root         (0)      737 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/README.rst
--rw-r--r--   0 root         (0) root         (0)     1659 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/tencentcloud_sdk_python_waf.egg-info/
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/tencentcloud_sdk_python_waf.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      445 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/tencentcloud_sdk_python_waf.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)     1659 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/tencentcloud_sdk_python_waf.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       13 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/tencentcloud_sdk_python_waf.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)     1006 2023-06-26 00:37:16.000000 tencentcloud-sdk-python-waf-3.0.921/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/
+-rw-r--r--   0 root         (0) root         (0)       88 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/tencentcloud/
+-rw-r--r--   0 root         (0) root         (0)      630 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/tencentcloud/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/tencentcloud/waf/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/tencentcloud/waf/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/tencentcloud/waf/v20180125/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/tencentcloud/waf/v20180125/__init__.py
+-rw-r--r--   0 root         (0) root         (0)   188980 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/tencentcloud/waf/v20180125/models.py
+-rw-r--r--   0 root         (0) root         (0)     2711 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/tencentcloud/waf/v20180125/errorcodes.py
+-rw-r--r--   0 root         (0) root         (0)    47458 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/tencentcloud/waf/v20180125/waf_client.py
+-rw-r--r--   0 root         (0) root         (0)      737 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/README.rst
+-rw-r--r--   0 root         (0) root         (0)     1659 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/tencentcloud_sdk_python_waf.egg-info/
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/tencentcloud_sdk_python_waf.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      445 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/tencentcloud_sdk_python_waf.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)     1659 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/tencentcloud_sdk_python_waf.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/tencentcloud_sdk_python_waf.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)     1006 2023-06-27 00:37:52.000000 tencentcloud-sdk-python-waf-3.0.922/setup.py
```

### Comparing `tencentcloud-sdk-python-waf-3.0.921/tencentcloud/__init__.py` & `tencentcloud-sdk-python-waf-3.0.922/tencentcloud/__init__.py`

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

### Comparing `tencentcloud-sdk-python-waf-3.0.921/tencentcloud/waf/v20180125/models.py` & `tencentcloud-sdk-python-waf-3.0.922/tencentcloud/waf/v20180125/models.py`

 * *Files 2% similar despite different names*

```diff
@@ -4427,14 +4427,184 @@
         self.RequestId = None
 
 
     def _deserialize(self, params):
         self.RequestId = params.get("RequestId")
 
 
+class ModifySpartaProtectionRequest(AbstractModel):
+    """ModifySpartaProtection请求参数结构体
+
+    """
+
+    def __init__(self):
+        r"""
+        :param Domain: 域名
+        :type Domain: str
+        :param DomainId: 域名ID
+        :type DomainId: str
+        :param CertType: 证书类型，0表示没有证书，CertType=1表示自有证书,2 为托管证书
+        :type CertType: int
+        :param Cert: CertType=1时，需要填次参数，表示证书内容
+        :type Cert: str
+        :param PrivateKey: CertType=1时，需要填次参数，表示证书的私钥
+        :type PrivateKey: str
+        :param SSLId: CertType=2时，需要填次参数，表示证书的ID
+        :type SSLId: str
+        :param IsCdn: 表示是否开启了CDN代理
+        :type IsCdn: int
+        :param UpstreamScheme: HTTPS回源协议
+        :type UpstreamScheme: str
+        :param HttpsUpstreamPort: HTTPS回源端口,仅UpstreamScheme为http时需要填当前字段
+        :type HttpsUpstreamPort: str
+        :param HttpsRewrite: 表示是否强制跳转到HTTPS，1表示开启，0表示不开启
+        :type HttpsRewrite: int
+        :param UpstreamType: 回源类型，0表示通过IP回源,1 表示通过域名回源
+        :type UpstreamType: int
+        :param UpstreamDomain: UpstreamType=1时，填次字段表示回源域名
+        :type UpstreamDomain: str
+        :param SrcList: UpstreamType=0时，填次字段表示回源ip
+        :type SrcList: list of str
+        :param IsHttp2: 是否开启HTTP2，1表示开启，0表示不开启http2。开启HTTP2需要HTTPS支持
+        :type IsHttp2: int
+        :param IsWebsocket: 是否开启WebSocket， 1：开启WebSocket，0：不开启WebSocket
+        :type IsWebsocket: int
+        :param LoadBalance: 负载均衡策略，0表示轮徇，1表示IP hash
+        :type LoadBalance: int
+        :param IsGray: 是否灰度
+        :type IsGray: int
+        :param Edition: WAF版本
+        :type Edition: str
+        :param Ports: 端口信息
+        :type Ports: list of SpartaProtectionPort
+        :param IsKeepAlive: 长短连接标志，仅IP回源时有效
+        :type IsKeepAlive: str
+        :param InstanceID: 实例id
+        :type InstanceID: str
+        :param Anycast: 是否为Anycast ip类型：1 Anycast 0 普通ip
+        :type Anycast: int
+        :param Weights: src的权重
+        :type Weights: list of int
+        :param ActiveCheck: 是否开启源站的主动健康检测，1表示开启，0表示不开启
+        :type ActiveCheck: int
+        :param TLSVersion: TLS版本信息
+        :type TLSVersion: int
+        :param Ciphers: 加密套件信息
+        :type Ciphers: list of int
+        :param CipherTemplate: 0:不支持选择：默认模版  1:通用型模版 2:安全型模版 3:自定义模版
+        :type CipherTemplate: int
+        :param ProxyReadTimeout: 300s
+        :type ProxyReadTimeout: int
+        :param ProxySendTimeout: 300s
+        :type ProxySendTimeout: int
+        :param SniType: 0:关闭SNI；1:开启SNI，SNI=源请求host；2:开启SNI，SNI=修改为源站host；3：开启SNI，自定义host，SNI=SniHost；
+        :type SniType: int
+        :param SniHost: SniType=3时，需要填此参数，表示自定义的host；
+        :type SniHost: str
+        :param IpHeaders: IsCdn=3时，需要填此参数，表示自定义header
+        :type IpHeaders: list of str
+        """
+        self.Domain = None
+        self.DomainId = None
+        self.CertType = None
+        self.Cert = None
+        self.PrivateKey = None
+        self.SSLId = None
+        self.IsCdn = None
+        self.UpstreamScheme = None
+        self.HttpsUpstreamPort = None
+        self.HttpsRewrite = None
+        self.UpstreamType = None
+        self.UpstreamDomain = None
+        self.SrcList = None
+        self.IsHttp2 = None
+        self.IsWebsocket = None
+        self.LoadBalance = None
+        self.IsGray = None
+        self.Edition = None
+        self.Ports = None
+        self.IsKeepAlive = None
+        self.InstanceID = None
+        self.Anycast = None
+        self.Weights = None
+        self.ActiveCheck = None
+        self.TLSVersion = None
+        self.Ciphers = None
+        self.CipherTemplate = None
+        self.ProxyReadTimeout = None
+        self.ProxySendTimeout = None
+        self.SniType = None
+        self.SniHost = None
+        self.IpHeaders = None
+
+
+    def _deserialize(self, params):
+        self.Domain = params.get("Domain")
+        self.DomainId = params.get("DomainId")
+        self.CertType = params.get("CertType")
+        self.Cert = params.get("Cert")
+        self.PrivateKey = params.get("PrivateKey")
+        self.SSLId = params.get("SSLId")
+        self.IsCdn = params.get("IsCdn")
+        self.UpstreamScheme = params.get("UpstreamScheme")
+        self.HttpsUpstreamPort = params.get("HttpsUpstreamPort")
+        self.HttpsRewrite = params.get("HttpsRewrite")
+        self.UpstreamType = params.get("UpstreamType")
+        self.UpstreamDomain = params.get("UpstreamDomain")
+        self.SrcList = params.get("SrcList")
+        self.IsHttp2 = params.get("IsHttp2")
+        self.IsWebsocket = params.get("IsWebsocket")
+        self.LoadBalance = params.get("LoadBalance")
+        self.IsGray = params.get("IsGray")
+        self.Edition = params.get("Edition")
+        if params.get("Ports") is not None:
+            self.Ports = []
+            for item in params.get("Ports"):
+                obj = SpartaProtectionPort()
+                obj._deserialize(item)
+                self.Ports.append(obj)
+        self.IsKeepAlive = params.get("IsKeepAlive")
+        self.InstanceID = params.get("InstanceID")
+        self.Anycast = params.get("Anycast")
+        self.Weights = params.get("Weights")
+        self.ActiveCheck = params.get("ActiveCheck")
+        self.TLSVersion = params.get("TLSVersion")
+        self.Ciphers = params.get("Ciphers")
+        self.CipherTemplate = params.get("CipherTemplate")
+        self.ProxyReadTimeout = params.get("ProxyReadTimeout")
+        self.ProxySendTimeout = params.get("ProxySendTimeout")
+        self.SniType = params.get("SniType")
+        self.SniHost = params.get("SniHost")
+        self.IpHeaders = params.get("IpHeaders")
+        memeber_set = set(params.keys())
+        for name, value in vars(self).items():
+            if name in memeber_set:
+                memeber_set.remove(name)
+        if len(memeber_set) > 0:
+            warnings.warn("%s fileds are useless." % ",".join(memeber_set))
+        
+
+
+class ModifySpartaProtectionResponse(AbstractModel):
+    """ModifySpartaProtection返回参数结构体
+
+    """
+
+    def __init__(self):
+        r"""
+        :param RequestId: 唯一请求 ID，每次请求都会返回。定位问题时需要提供该次请求的 RequestId。
+        :type RequestId: str
+        """
+        self.RequestId = None
+
+
+    def _deserialize(self, params):
+        self.RequestId = params.get("RequestId")
+
+
 class ModifyWafAutoDenyRulesRequest(AbstractModel):
     """ModifyWafAutoDenyRules请求参数结构体
 
     """
 
     def __init__(self):
         r"""
@@ -5140,14 +5310,54 @@
                 obj._deserialize(item)
                 self.Data.append(obj)
         self.ListOver = params.get("ListOver")
         self.SqlFlag = params.get("SqlFlag")
         self.RequestId = params.get("RequestId")
 
 
+class SpartaProtectionPort(AbstractModel):
+    """waf斯巴达-编辑防护域名中的端口结构
+
+    """
+
+    def __init__(self):
+        r"""
+        :param NginxServerId: nginx Id
+        :type NginxServerId: int
+        :param Port: 端口
+        :type Port: str
+        :param Protocol: 协议
+        :type Protocol: str
+        :param UpstreamPort: 后端端口
+        :type UpstreamPort: str
+        :param UpstreamProtocol: 后端协议
+        :type UpstreamProtocol: str
+        """
+        self.NginxServerId = None
+        self.Port = None
+        self.Protocol = None
+        self.UpstreamPort = None
+        self.UpstreamProtocol = None
+
+
+    def _deserialize(self, params):
+        self.NginxServerId = params.get("NginxServerId")
+        self.Port = params.get("Port")
+        self.Protocol = params.get("Protocol")
+        self.UpstreamPort = params.get("UpstreamPort")
+        self.UpstreamProtocol = params.get("UpstreamProtocol")
+        memeber_set = set(params.keys())
+        for name, value in vars(self).items():
+            if name in memeber_set:
+                memeber_set.remove(name)
+        if len(memeber_set) > 0:
+            warnings.warn("%s fileds are useless." % ",".join(memeber_set))
+        
+
+
 class Strategy(AbstractModel):
     """自定义规则的匹配条件结构体
 
     """
 
     def __init__(self):
         r"""
```

### Comparing `tencentcloud-sdk-python-waf-3.0.921/tencentcloud/waf/v20180125/errorcodes.py` & `tencentcloud-sdk-python-waf-3.0.922/tencentcloud/waf/v20180125/errorcodes.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-waf-3.0.921/tencentcloud/waf/v20180125/waf_client.py` & `tencentcloud-sdk-python-waf-3.0.922/tencentcloud/waf/v20180125/waf_client.py`

 * *Files 1% similar despite different names*

```diff
@@ -988,14 +988,37 @@
         except Exception as e:
             if isinstance(e, TencentCloudSDKException):
                 raise
             else:
                 raise TencentCloudSDKException(e.message, e.message)
 
 
+    def ModifySpartaProtection(self, request):
+        """修改域名配置
+
+        :param request: Request instance for ModifySpartaProtection.
+        :type request: :class:`tencentcloud.waf.v20180125.models.ModifySpartaProtectionRequest`
+        :rtype: :class:`tencentcloud.waf.v20180125.models.ModifySpartaProtectionResponse`
+
+        """
+        try:
+            params = request._serialize()
+            headers = request.headers
+            body = self.call("ModifySpartaProtection", params, headers=headers)
+            response = json.loads(body)
+            model = models.ModifySpartaProtectionResponse()
+            model._deserialize(response["Response"])
+            return model
+        except Exception as e:
+            if isinstance(e, TencentCloudSDKException):
+                raise
+            else:
+                raise TencentCloudSDKException(e.message, e.message)
+
+
     def ModifyWafAutoDenyRules(self, request):
         """修改ip惩罚规则
 
         :param request: Request instance for ModifyWafAutoDenyRules.
         :type request: :class:`tencentcloud.waf.v20180125.models.ModifyWafAutoDenyRulesRequest`
         :rtype: :class:`tencentcloud.waf.v20180125.models.ModifyWafAutoDenyRulesResponse`
```

### Comparing `tencentcloud-sdk-python-waf-3.0.921/README.rst` & `tencentcloud-sdk-python-waf-3.0.922/README.rst`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-waf-3.0.921/PKG-INFO` & `tencentcloud-sdk-python-waf-3.0.922/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-waf
-Version: 3.0.921
+Version: 3.0.922
 Summary: Tencent Cloud Waf SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-waf-3.0.921/tencentcloud_sdk_python_waf.egg-info/PKG-INFO` & `tencentcloud-sdk-python-waf-3.0.922/tencentcloud_sdk_python_waf.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-waf
-Version: 3.0.921
+Version: 3.0.922
 Summary: Tencent Cloud Waf SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-waf-3.0.921/setup.py` & `tencentcloud-sdk-python-waf-3.0.922/setup.py`

 * *Files identical despite different names*


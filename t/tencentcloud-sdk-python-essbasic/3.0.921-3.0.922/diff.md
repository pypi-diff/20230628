# Comparing `tmp/tencentcloud-sdk-python-essbasic-3.0.921.tar.gz` & `tmp/tencentcloud-sdk-python-essbasic-3.0.922.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/tencentcloud-sdk-python-essbasic-3.0.921.tar", last modified: Mon Jun 26 00:24:16 2023, max compression
+gzip compressed data, was "dist/tencentcloud-sdk-python-essbasic-3.0.922.tar", last modified: Tue Jun 27 00:24:41 2023, max compression
```

## Comparing `tencentcloud-sdk-python-essbasic-3.0.921.tar` & `tencentcloud-sdk-python-essbasic-3.0.922.tar`

### file list

```diff
@@ -1,24 +1,24 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/
--rw-r--r--   0 root         (0) root         (0)       88 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/
--rw-r--r--   0 root         (0) root         (0)      630 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20210526/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20210526/__init__.py
--rw-r--r--   0 root         (0) root         (0)   240452 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20210526/models.py
--rw-r--r--   0 root         (0) root         (0)    52742 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20210526/essbasic_client.py
--rw-r--r--   0 root         (0) root         (0)    16662 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20210526/errorcodes.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20201222/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20201222/__init__.py
--rw-r--r--   0 root         (0) root         (0)   171664 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20201222/models.py
--rw-r--r--   0 root         (0) root         (0)    53845 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20201222/essbasic_client.py
--rw-r--r--   0 root         (0) root         (0)     5392 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20201222/errorcodes.py
--rw-r--r--   0 root         (0) root         (0)      752 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/README.rst
--rw-r--r--   0 root         (0) root         (0)     1684 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     1016 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud_sdk_python_essbasic.egg-info/
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud_sdk_python_essbasic.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      678 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud_sdk_python_essbasic.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)     1684 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud_sdk_python_essbasic.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       13 2023-06-26 00:24:16.000000 tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud_sdk_python_essbasic.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/
+-rw-r--r--   0 root         (0) root         (0)       88 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/
+-rw-r--r--   0 root         (0) root         (0)      630 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20210526/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20210526/__init__.py
+-rw-r--r--   0 root         (0) root         (0)   240452 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20210526/models.py
+-rw-r--r--   0 root         (0) root         (0)    52742 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20210526/essbasic_client.py
+-rw-r--r--   0 root         (0) root         (0)    16662 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20210526/errorcodes.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20201222/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20201222/__init__.py
+-rw-r--r--   0 root         (0) root         (0)   171664 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20201222/models.py
+-rw-r--r--   0 root         (0) root         (0)    53845 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20201222/essbasic_client.py
+-rw-r--r--   0 root         (0) root         (0)     5392 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20201222/errorcodes.py
+-rw-r--r--   0 root         (0) root         (0)      752 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/README.rst
+-rw-r--r--   0 root         (0) root         (0)     1684 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     1016 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud_sdk_python_essbasic.egg-info/
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud_sdk_python_essbasic.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      678 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud_sdk_python_essbasic.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)     1684 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud_sdk_python_essbasic.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-27 00:24:41.000000 tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud_sdk_python_essbasic.egg-info/top_level.txt
```

### Comparing `tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/__init__.py` & `tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/__init__.py`

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

### Comparing `tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20210526/models.py` & `tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20210526/models.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20210526/essbasic_client.py` & `tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20210526/essbasic_client.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20210526/errorcodes.py` & `tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20210526/errorcodes.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20201222/models.py` & `tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20201222/models.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20201222/essbasic_client.py` & `tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20201222/essbasic_client.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud/essbasic/v20201222/errorcodes.py` & `tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud/essbasic/v20201222/errorcodes.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-essbasic-3.0.921/README.rst` & `tencentcloud-sdk-python-essbasic-3.0.922/README.rst`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-essbasic-3.0.921/PKG-INFO` & `tencentcloud-sdk-python-essbasic-3.0.922/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-essbasic
-Version: 3.0.921
+Version: 3.0.922
 Summary: Tencent Cloud Essbasic SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-essbasic-3.0.921/setup.py` & `tencentcloud-sdk-python-essbasic-3.0.922/setup.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud_sdk_python_essbasic.egg-info/SOURCES.txt` & `tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud_sdk_python_essbasic.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-essbasic-3.0.921/tencentcloud_sdk_python_essbasic.egg-info/PKG-INFO` & `tencentcloud-sdk-python-essbasic-3.0.922/tencentcloud_sdk_python_essbasic.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-essbasic
-Version: 3.0.921
+Version: 3.0.922
 Summary: Tencent Cloud Essbasic SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```


# Comparing `tmp/tencentcloud-sdk-python-omics-3.0.921.tar.gz` & `tmp/tencentcloud-sdk-python-omics-3.0.922.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/tencentcloud-sdk-python-omics-3.0.921.tar", last modified: Mon Jun 26 00:29:49 2023, max compression
+gzip compressed data, was "dist/tencentcloud-sdk-python-omics-3.0.922.tar", last modified: Tue Jun 27 00:30:03 2023, max compression
```

## Comparing `tencentcloud-sdk-python-omics-3.0.921.tar` & `tencentcloud-sdk-python-omics-3.0.922.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/
--rw-r--r--   0 root         (0) root         (0)       88 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/tencentcloud/
--rw-r--r--   0 root         (0) root         (0)      630 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/tencentcloud/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/tencentcloud/omics/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/tencentcloud/omics/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/tencentcloud/omics/v20221128/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/tencentcloud/omics/v20221128/__init__.py
--rw-r--r--   0 root         (0) root         (0)    55938 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/tencentcloud/omics/v20221128/models.py
--rw-r--r--   0 root         (0) root         (0)     4079 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/tencentcloud/omics/v20221128/errorcodes.py
--rw-r--r--   0 root         (0) root         (0)    11298 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/tencentcloud/omics/v20221128/omics_client.py
--rw-r--r--   0 root         (0) root         (0)      743 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/README.rst
--rw-r--r--   0 root         (0) root         (0)     1669 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/tencentcloud_sdk_python_omics.egg-info/
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/tencentcloud_sdk_python_omics.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      465 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/tencentcloud_sdk_python_omics.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)     1669 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/tencentcloud_sdk_python_omics.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       13 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/tencentcloud_sdk_python_omics.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)     1010 2023-06-26 00:29:49.000000 tencentcloud-sdk-python-omics-3.0.921/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/
+-rw-r--r--   0 root         (0) root         (0)       88 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/tencentcloud/
+-rw-r--r--   0 root         (0) root         (0)      630 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/tencentcloud/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/tencentcloud/omics/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/tencentcloud/omics/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/tencentcloud/omics/v20221128/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/tencentcloud/omics/v20221128/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    55938 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/tencentcloud/omics/v20221128/models.py
+-rw-r--r--   0 root         (0) root         (0)     4079 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/tencentcloud/omics/v20221128/errorcodes.py
+-rw-r--r--   0 root         (0) root         (0)    11298 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/tencentcloud/omics/v20221128/omics_client.py
+-rw-r--r--   0 root         (0) root         (0)      743 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/README.rst
+-rw-r--r--   0 root         (0) root         (0)     1669 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/tencentcloud_sdk_python_omics.egg-info/
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/tencentcloud_sdk_python_omics.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      465 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/tencentcloud_sdk_python_omics.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)     1669 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/tencentcloud_sdk_python_omics.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/tencentcloud_sdk_python_omics.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)     1010 2023-06-27 00:30:03.000000 tencentcloud-sdk-python-omics-3.0.922/setup.py
```

### Comparing `tencentcloud-sdk-python-omics-3.0.921/tencentcloud/__init__.py` & `tencentcloud-sdk-python-omics-3.0.922/tencentcloud/__init__.py`

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

### Comparing `tencentcloud-sdk-python-omics-3.0.921/tencentcloud/omics/v20221128/models.py` & `tencentcloud-sdk-python-omics-3.0.922/tencentcloud/omics/v20221128/models.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-omics-3.0.921/tencentcloud/omics/v20221128/errorcodes.py` & `tencentcloud-sdk-python-omics-3.0.922/tencentcloud/omics/v20221128/errorcodes.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-omics-3.0.921/tencentcloud/omics/v20221128/omics_client.py` & `tencentcloud-sdk-python-omics-3.0.922/tencentcloud/omics/v20221128/omics_client.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-omics-3.0.921/README.rst` & `tencentcloud-sdk-python-omics-3.0.922/README.rst`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-omics-3.0.921/PKG-INFO` & `tencentcloud-sdk-python-omics-3.0.922/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-omics
-Version: 3.0.921
+Version: 3.0.922
 Summary: Tencent Cloud Omics SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-omics-3.0.921/tencentcloud_sdk_python_omics.egg-info/PKG-INFO` & `tencentcloud-sdk-python-omics-3.0.922/tencentcloud_sdk_python_omics.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-omics
-Version: 3.0.921
+Version: 3.0.922
 Summary: Tencent Cloud Omics SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-omics-3.0.921/setup.py` & `tencentcloud-sdk-python-omics-3.0.922/setup.py`

 * *Files identical despite different names*


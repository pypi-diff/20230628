# Comparing `tmp/tencentcloud-sdk-python-ivld-3.0.922.tar.gz` & `tmp/tencentcloud-sdk-python-ivld-3.0.923.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/tencentcloud-sdk-python-ivld-3.0.922.tar", last modified: Tue Jun 27 00:27:28 2023, max compression
+gzip compressed data, was "dist/tencentcloud-sdk-python-ivld-3.0.923.tar", last modified: Wed Jun 28 00:29:59 2023, max compression
```

## Comparing `tencentcloud-sdk-python-ivld-3.0.922.tar` & `tencentcloud-sdk-python-ivld-3.0.923.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/
--rw-r--r--   0 root         (0) root         (0)       88 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/tencentcloud/
--rw-r--r--   0 root         (0) root         (0)      630 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/tencentcloud/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/tencentcloud/ivld/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/tencentcloud/ivld/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/tencentcloud/ivld/v20210903/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/tencentcloud/ivld/v20210903/__init__.py
--rw-r--r--   0 root         (0) root         (0)   106629 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/tencentcloud/ivld/v20210903/models.py
--rw-r--r--   0 root         (0) root         (0)     9364 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/tencentcloud/ivld/v20210903/errorcodes.py
--rw-r--r--   0 root         (0) root         (0)    29455 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/tencentcloud/ivld/v20210903/ivld_client.py
--rw-r--r--   0 root         (0) root         (0)      740 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/README.rst
--rw-r--r--   0 root         (0) root         (0)     1664 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/tencentcloud_sdk_python_ivld.egg-info/
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/tencentcloud_sdk_python_ivld.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      455 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/tencentcloud_sdk_python_ivld.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)     1664 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/tencentcloud_sdk_python_ivld.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       13 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/tencentcloud_sdk_python_ivld.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)     1008 2023-06-27 00:27:28.000000 tencentcloud-sdk-python-ivld-3.0.922/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/
+-rw-r--r--   0 root         (0) root         (0)       88 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/tencentcloud/
+-rw-r--r--   0 root         (0) root         (0)      630 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/tencentcloud/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/tencentcloud/ivld/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/tencentcloud/ivld/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/tencentcloud/ivld/v20210903/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/tencentcloud/ivld/v20210903/__init__.py
+-rw-r--r--   0 root         (0) root         (0)   106629 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/tencentcloud/ivld/v20210903/models.py
+-rw-r--r--   0 root         (0) root         (0)     9364 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/tencentcloud/ivld/v20210903/errorcodes.py
+-rw-r--r--   0 root         (0) root         (0)    29455 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/tencentcloud/ivld/v20210903/ivld_client.py
+-rw-r--r--   0 root         (0) root         (0)      740 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/README.rst
+-rw-r--r--   0 root         (0) root         (0)     1664 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/tencentcloud_sdk_python_ivld.egg-info/
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/tencentcloud_sdk_python_ivld.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      455 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/tencentcloud_sdk_python_ivld.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)     1664 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/tencentcloud_sdk_python_ivld.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/tencentcloud_sdk_python_ivld.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)     1008 2023-06-28 00:29:59.000000 tencentcloud-sdk-python-ivld-3.0.923/setup.py
```

### Comparing `tencentcloud-sdk-python-ivld-3.0.922/tencentcloud/__init__.py` & `tencentcloud-sdk-python-ivld-3.0.923/tencentcloud/__init__.py`

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

### Comparing `tencentcloud-sdk-python-ivld-3.0.922/tencentcloud/ivld/v20210903/models.py` & `tencentcloud-sdk-python-ivld-3.0.923/tencentcloud/ivld/v20210903/models.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-ivld-3.0.922/tencentcloud/ivld/v20210903/errorcodes.py` & `tencentcloud-sdk-python-ivld-3.0.923/tencentcloud/ivld/v20210903/errorcodes.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-ivld-3.0.922/tencentcloud/ivld/v20210903/ivld_client.py` & `tencentcloud-sdk-python-ivld-3.0.923/tencentcloud/ivld/v20210903/ivld_client.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-ivld-3.0.922/README.rst` & `tencentcloud-sdk-python-ivld-3.0.923/README.rst`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-ivld-3.0.922/PKG-INFO` & `tencentcloud-sdk-python-ivld-3.0.923/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-ivld
-Version: 3.0.922
+Version: 3.0.923
 Summary: Tencent Cloud Ivld SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-ivld-3.0.922/tencentcloud_sdk_python_ivld.egg-info/PKG-INFO` & `tencentcloud-sdk-python-ivld-3.0.923/tencentcloud_sdk_python_ivld.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-ivld
-Version: 3.0.922
+Version: 3.0.923
 Summary: Tencent Cloud Ivld SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-ivld-3.0.922/setup.py` & `tencentcloud-sdk-python-ivld-3.0.923/setup.py`

 * *Files identical despite different names*


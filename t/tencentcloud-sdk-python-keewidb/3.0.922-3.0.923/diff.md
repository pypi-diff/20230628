# Comparing `tmp/tencentcloud-sdk-python-keewidb-3.0.922.tar.gz` & `tmp/tencentcloud-sdk-python-keewidb-3.0.923.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/tencentcloud-sdk-python-keewidb-3.0.922.tar", last modified: Tue Jun 27 00:27:34 2023, max compression
+gzip compressed data, was "dist/tencentcloud-sdk-python-keewidb-3.0.923.tar", last modified: Wed Jun 28 00:30:06 2023, max compression
```

## Comparing `tencentcloud-sdk-python-keewidb-3.0.922.tar` & `tencentcloud-sdk-python-keewidb-3.0.923.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/
--rw-r--r--   0 root         (0) root         (0)       88 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud/keewidb/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud/keewidb/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud/keewidb/v20220308/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud/keewidb/v20220308/__init__.py
--rw-r--r--   0 root         (0) root         (0)   137323 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud/keewidb/v20220308/models.py
--rw-r--r--   0 root         (0) root         (0)    37283 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud/keewidb/v20220308/keewidb_client.py
--rw-r--r--   0 root         (0) root         (0)     5675 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud/keewidb/v20220308/errorcodes.py
--rw-r--r--   0 root         (0) root         (0)      630 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud/__init__.py
--rw-r--r--   0 root         (0) root         (0)      749 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/README.rst
--rw-r--r--   0 root         (0) root         (0)     1679 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     1014 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud_sdk_python_keewidb.egg-info/
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud_sdk_python_keewidb.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      485 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud_sdk_python_keewidb.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)     1679 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud_sdk_python_keewidb.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       13 2023-06-27 00:27:34.000000 tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud_sdk_python_keewidb.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:30:06.000000 tencentcloud-sdk-python-keewidb-3.0.923/
+-rw-r--r--   0 root         (0) root         (0)       88 2023-06-28 00:30:06.000000 tencentcloud-sdk-python-keewidb-3.0.923/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:30:06.000000 tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:30:06.000000 tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud/keewidb/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 00:30:05.000000 tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud/keewidb/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:30:06.000000 tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud/keewidb/v20220308/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 00:30:05.000000 tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud/keewidb/v20220308/__init__.py
+-rw-r--r--   0 root         (0) root         (0)   137323 2023-06-28 00:30:05.000000 tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud/keewidb/v20220308/models.py
+-rw-r--r--   0 root         (0) root         (0)    37283 2023-06-28 00:30:05.000000 tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud/keewidb/v20220308/keewidb_client.py
+-rw-r--r--   0 root         (0) root         (0)     5675 2023-06-28 00:30:05.000000 tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud/keewidb/v20220308/errorcodes.py
+-rw-r--r--   0 root         (0) root         (0)      630 2023-06-28 00:30:05.000000 tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      749 2023-06-28 00:30:05.000000 tencentcloud-sdk-python-keewidb-3.0.923/README.rst
+-rw-r--r--   0 root         (0) root         (0)     1679 2023-06-28 00:30:06.000000 tencentcloud-sdk-python-keewidb-3.0.923/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     1014 2023-06-28 00:30:05.000000 tencentcloud-sdk-python-keewidb-3.0.923/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:30:06.000000 tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud_sdk_python_keewidb.egg-info/
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 00:30:06.000000 tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud_sdk_python_keewidb.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      485 2023-06-28 00:30:06.000000 tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud_sdk_python_keewidb.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)     1679 2023-06-28 00:30:06.000000 tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud_sdk_python_keewidb.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-28 00:30:06.000000 tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud_sdk_python_keewidb.egg-info/top_level.txt
```

### Comparing `tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud/keewidb/v20220308/models.py` & `tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud/keewidb/v20220308/models.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud/keewidb/v20220308/keewidb_client.py` & `tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud/keewidb/v20220308/keewidb_client.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud/keewidb/v20220308/errorcodes.py` & `tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud/keewidb/v20220308/errorcodes.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud/__init__.py` & `tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud/__init__.py`

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

### Comparing `tencentcloud-sdk-python-keewidb-3.0.922/README.rst` & `tencentcloud-sdk-python-keewidb-3.0.923/README.rst`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-keewidb-3.0.922/PKG-INFO` & `tencentcloud-sdk-python-keewidb-3.0.923/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-keewidb
-Version: 3.0.922
+Version: 3.0.923
 Summary: Tencent Cloud Keewidb SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-keewidb-3.0.922/setup.py` & `tencentcloud-sdk-python-keewidb-3.0.923/setup.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-keewidb-3.0.922/tencentcloud_sdk_python_keewidb.egg-info/PKG-INFO` & `tencentcloud-sdk-python-keewidb-3.0.923/tencentcloud_sdk_python_keewidb.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-keewidb
-Version: 3.0.922
+Version: 3.0.923
 Summary: Tencent Cloud Keewidb SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```


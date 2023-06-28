# Comparing `tmp/mobio-media-sdk-test-0.2.12.tar.gz` & `tmp/mobio-media-sdk-test-0.2.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mobio-media-sdk-test-0.2.12.tar", last modified: Wed Jun 28 02:53:44 2023, max compression
+gzip compressed data, was "mobio-media-sdk-test-0.2.9.tar", last modified: Wed Apr  5 08:06:12 2023, max compression
```

## Comparing `mobio-media-sdk-test-0.2.12.tar` & `mobio-media-sdk-test-0.2.9.tar`

### file list

```diff
@@ -1,25 +1,24 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 02:53:44.330259 mobio-media-sdk-test-0.2.12/
--rwxr-xr-x   0 root         (0) root         (0)     1073 2023-06-28 02:51:14.000000 mobio-media-sdk-test-0.2.12/LICENSE
--rw-r--r--   0 root         (0) root         (0)     3545 2023-06-28 02:53:44.330259 mobio-media-sdk-test-0.2.12/PKG-INFO
--rwxr-xr-x   0 root         (0) root         (0)     2698 2023-06-28 02:51:14.000000 mobio-media-sdk-test-0.2.12/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 02:53:44.313258 mobio-media-sdk-test-0.2.12/mobio/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 02:53:44.314258 mobio-media-sdk-test-0.2.12/mobio/sdks/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 02:53:44.324259 mobio-media-sdk-test-0.2.12/mobio/sdks/media/
--rwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 02:51:14.000000 mobio-media-sdk-test-0.2.12/mobio/sdks/media/__init__.py
--rwxr-xr-x   0 root         (0) root         (0)     1737 2023-06-28 02:51:14.000000 mobio-media-sdk-test-0.2.12/mobio/sdks/media/config.py
--rw-r--r--   0 root         (0) root         (0)     4351 2023-06-28 02:51:14.000000 mobio-media-sdk-test-0.2.12/mobio/sdks/media/constant.py
--rw-r--r--   0 root         (0) root         (0)    38208 2023-06-28 02:51:14.000000 mobio-media-sdk-test-0.2.12/mobio/sdks/media/custom_mimetypes.py
--rwxr-xr-x   0 root         (0) root         (0)      338 2023-06-28 02:51:14.000000 mobio-media-sdk-test-0.2.12/mobio/sdks/media/dir.py
--rw-r--r--   0 root         (0) root         (0)     2419 2023-06-28 02:51:14.000000 mobio-media-sdk-test-0.2.12/mobio/sdks/media/merchant_config.py
--rwxr-xr-x   0 root         (0) root         (0)    21002 2023-06-28 02:51:14.000000 mobio-media-sdk-test-0.2.12/mobio/sdks/media/mobio_media_sdk.py
--rw-r--r--   0 root         (0) root         (0)     1083 2023-06-28 02:51:14.000000 mobio-media-sdk-test-0.2.12/mobio/sdks/media/utils.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 02:53:44.329259 mobio-media-sdk-test-0.2.12/mobio_media_sdk_test.egg-info/
--rw-r--r--   0 root         (0) root         (0)     3545 2023-06-28 02:53:44.000000 mobio-media-sdk-test-0.2.12/mobio_media_sdk_test.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      567 2023-06-28 02:53:44.000000 mobio-media-sdk-test-0.2.12/mobio_media_sdk_test.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 02:53:44.000000 mobio-media-sdk-test-0.2.12/mobio_media_sdk_test.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)        6 2023-06-28 02:53:44.000000 mobio-media-sdk-test-0.2.12/mobio_media_sdk_test.egg-info/namespace_packages.txt
--rw-r--r--   0 root         (0) root         (0)       98 2023-06-28 02:53:44.000000 mobio-media-sdk-test-0.2.12/mobio_media_sdk_test.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        6 2023-06-28 02:53:44.000000 mobio-media-sdk-test-0.2.12/mobio_media_sdk_test.egg-info/top_level.txt
--rwxr-xr-x   0 root         (0) root         (0)      104 2023-06-28 02:51:14.000000 mobio-media-sdk-test-0.2.12/pyproject.toml
--rwxr-xr-x   0 root         (0) root         (0)       38 2023-06-28 02:53:44.332259 mobio-media-sdk-test-0.2.12/setup.cfg
--rw-r--r--   0 root         (0) root         (0)     9327 2023-06-28 02:53:43.000000 mobio-media-sdk-test-0.2.12/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-05 08:06:12.650004 mobio-media-sdk-test-0.2.9/
+-rw-r--r--   0 root         (0) root         (0)     4052 2023-04-05 08:06:12.650004 mobio-media-sdk-test-0.2.9/PKG-INFO
+-rwxr-xr-x   0 root         (0) root         (0)       82 2023-04-05 07:33:40.000000 mobio-media-sdk-test-0.2.9/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-05 08:06:12.634003 mobio-media-sdk-test-0.2.9/mobio/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-05 08:06:12.634003 mobio-media-sdk-test-0.2.9/mobio/sdks/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-05 08:06:12.644004 mobio-media-sdk-test-0.2.9/mobio/sdks/media/
+-rwxr-xr-x   0 root         (0) root         (0)        0 2023-04-05 07:33:40.000000 mobio-media-sdk-test-0.2.9/mobio/sdks/media/__init__.py
+-rwxr-xr-x   0 root         (0) root         (0)     1737 2023-04-05 07:33:40.000000 mobio-media-sdk-test-0.2.9/mobio/sdks/media/config.py
+-rw-r--r--   0 root         (0) root         (0)     4351 2023-04-05 07:33:40.000000 mobio-media-sdk-test-0.2.9/mobio/sdks/media/constant.py
+-rw-r--r--   0 root         (0) root         (0)    38208 2023-04-05 07:33:40.000000 mobio-media-sdk-test-0.2.9/mobio/sdks/media/custom_mimetypes.py
+-rwxr-xr-x   0 root         (0) root         (0)      338 2023-04-05 07:33:40.000000 mobio-media-sdk-test-0.2.9/mobio/sdks/media/dir.py
+-rw-r--r--   0 root         (0) root         (0)     2419 2023-04-05 07:33:40.000000 mobio-media-sdk-test-0.2.9/mobio/sdks/media/merchant_config.py
+-rwxr-xr-x   0 root         (0) root         (0)    20755 2023-04-05 07:33:40.000000 mobio-media-sdk-test-0.2.9/mobio/sdks/media/mobio_media_sdk.py
+-rw-r--r--   0 root         (0) root         (0)     1083 2023-04-05 07:33:40.000000 mobio-media-sdk-test-0.2.9/mobio/sdks/media/utils.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-04-05 08:06:12.649004 mobio-media-sdk-test-0.2.9/mobio_media_sdk_test.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     4052 2023-04-05 08:06:12.000000 mobio-media-sdk-test-0.2.9/mobio_media_sdk_test.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      559 2023-04-05 08:06:12.000000 mobio-media-sdk-test-0.2.9/mobio_media_sdk_test.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-04-05 08:06:12.000000 mobio-media-sdk-test-0.2.9/mobio_media_sdk_test.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)        6 2023-04-05 08:06:12.000000 mobio-media-sdk-test-0.2.9/mobio_media_sdk_test.egg-info/namespace_packages.txt
+-rw-r--r--   0 root         (0) root         (0)       98 2023-04-05 08:06:12.000000 mobio-media-sdk-test-0.2.9/mobio_media_sdk_test.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)        6 2023-04-05 08:06:12.000000 mobio-media-sdk-test-0.2.9/mobio_media_sdk_test.egg-info/top_level.txt
+-rwxr-xr-x   0 root         (0) root         (0)      104 2023-04-05 07:33:40.000000 mobio-media-sdk-test-0.2.9/pyproject.toml
+-rwxr-xr-x   0 root         (0) root         (0)       38 2023-04-05 08:06:12.651004 mobio-media-sdk-test-0.2.9/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)     9328 2023-04-05 08:06:11.000000 mobio-media-sdk-test-0.2.9/setup.py
```

### Comparing `mobio-media-sdk-test-0.2.12/PKG-INFO` & `mobio-media-sdk-test-0.2.9/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,92 +1,91 @@
 Metadata-Version: 2.1
 Name: mobio-media-sdk-test
-Version: 0.2.12
+Version: 0.2.9
 Summary: Mobio Media SDK
 Home-page: https://github.com/mobiovn
 Author: MOBIO
 Author-email: contact@mobio.vn
 License: MIT
 Project-URL: Source, https://github.com/mobiovn
+Description: ##  Thư viện Media.
+        
+        ### Cài đặt:
+        
+        ```bash
+         $ pip3 install mobio-media-sdk
+         ```
+        
+        #### Log:
+        
+        - Version: 0.1.1: Thêm mobio token.
+        - Version: 0.1.2: Add json.dums by func finish_save_file_by_filepath
+        - Version: 0.1.3: Add func get_path_by_url, get_binary_by_url
+            + Hướng dẫn sử dụng:
+                + func get_path_by_url -> kết quả trả về là path của url.
+                  ```python3
+                  from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK 
+                  MobioMediaSDK().get_path_by_url(url)
+                  ```
+                + func get_binary_by_url -> kết quả trả về là binary của url
+                  ```python3
+                  from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK 
+                  MobioMediaSDK().get_binary_by_url(url)
+                  ```
+        - Version: 0.1.4: Add func get_filename_by_url
+          + Hướng dẫn sử dụng:
+            + func get_filename_by_url -> kết quả trả về là filename của url
+              ```python3
+              from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK 
+              MobioMediaSDK().get_filename_by_url(url)
+              ```
+        - Version: 0.1.5: Delete system_config
+        - Version: 0.1.6: Rename get_local_path_by_url -> get_path_by_url
+        - Version: 0.1.7: Option read file "r" -> "rb"
+        - Version: 0.1.8: Update lại token call từ Admin
+        - Version: 0.1.9: Bổ sung tính năng:
+          - Tạo public link khi chưa có file upload.
+              ```python3
+              from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK 
+              MobioMediaSDK().create_public_url_without_file(
+                    merchant_id="merchant_id",
+                    filename="filename",
+                    mimetype_str="mimetype_str"
+              )
+          
+              result = {
+                'url': '',
+                'local_path': '',
+                'filename': ''
+              }
+              ```
+              Sau khi xử lý nghiệp vụ xong có thể dùng func sau để Lưu file được lấy path từ URL
+              ```python3
+               from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK 
+               MobioMediaSDK().finish_save_file_by_public_url(filepath="filepath", url="url")
+              ```
+          - Thêm option **file_byte** khi upload file. Option này phục vụ cho nhu cầu upload file bằng bytes.
+            
+        - Version: 0.2.0: Bổ sung option display, group_ids
+        - Version: 0.2.1: Bổ sung merchant_id
+        - Version: 0.2.2: Sửa từ get public-host từ module media sang module Admin.
+        - Version: 0.2.2 và 0.2.3: Bổ sung phần tính dung lượng file khi trả về.
+        - Version: 0.2.5: Chuyển việc lấy public-host sang admin-sdk
+        - Version: 0.2.6: Apply libs m-kafka-sdk-v2
+        - Version: 0.2.7: Bỏ m-kafka-sdk
+        - Version: 0.2.8: Fix lỗi encode url với những tên file đặc biệt
+        - Version: 0.2.9: Nâng cấp confluent_kafka
+        
 Keywords: mobio,media,upload
+Platform: UNKNOWN
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Topic :: Software Development :: Build Tools
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3 :: Only
 Requires-Python: >=3
 Description-Content-Type: text/markdown
-License-File: LICENSE
-
-##  Thư viện Media.
-
-### Cài đặt:
-
-```bash
- $ pip3 install mobio-media-sdk
- ```
-
-#### Log:
-
-- Version: 0.1.1: Thêm mobio token.
-- Version: 0.1.2: Add json.dums by func finish_save_file_by_filepath
-- Version: 0.1.3: Add func get_path_by_url, get_binary_by_url
-    + Hướng dẫn sử dụng:
-        + func get_path_by_url -> kết quả trả về là path của url.
-          ```python3
-          from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK
-          MobioMediaSDK().get_path_by_url(url)
-          ```
-        + func get_binary_by_url -> kết quả trả về là binary của url
-          ```python3
-          from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK
-          MobioMediaSDK().get_binary_by_url(url)
-          ```
-- Version: 0.1.4: Add func get_filename_by_url
-  + Hướng dẫn sử dụng:
-    + func get_filename_by_url -> kết quả trả về là filename của url
-      ```python3
-      from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK
-      MobioMediaSDK().get_filename_by_url(url)
-      ```
-- Version: 0.1.5: Delete system_config
-- Version: 0.1.6: Rename get_local_path_by_url -> get_path_by_url
-- Version: 0.1.7: Option read file "r" -> "rb"
-- Version: 0.1.8: Update lại token call từ Admin
-- Version: 0.1.9: Bổ sung tính năng:
-  - Tạo public link khi chưa có file upload.
-      ```python3
-      from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK
-      MobioMediaSDK().create_public_url_without_file(
-            merchant_id="merchant_id",
-            filename="filename",
-            mimetype_str="mimetype_str"
-      )
-
-      result = {
-        'url': '',
-        'local_path': '',
-        'filename': ''
-      }
-      ```
-      Sau khi xử lý nghiệp vụ xong có thể dùng func sau để Lưu file được lấy path từ URL
-      ```python3
-       from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK
-       MobioMediaSDK().finish_save_file_by_public_url(filepath="filepath", url="url")
-      ```
-  - Thêm option **file_byte** khi upload file. Option này phục vụ cho nhu cầu upload file bằng bytes.
-
-- Version: 0.2.0: Bổ sung option display, group_ids
-- Version: 0.2.1: Bổ sung merchant_id
-- Version: 0.2.2: Sửa từ get public-host từ module media sang module Admin.
-- Version: 0.2.2 và 0.2.3: Bổ sung phần tính dung lượng file khi trả về.
-- Version: 0.2.5: Chuyển việc lấy public-host sang admin-sdk
-- Version: 0.2.6: Apply libs m-kafka-sdk-v2
-- Version: 0.2.7: Bỏ m-kafka-sdk
-- Version: 0.2.8: Fix lỗi encode url với những tên file đặc biệt
-- Version: 0.2.9: Nâng cấp confluent_kafka
-- Version: 0.2.10: Thêm get mimetype file_byte
```

### Comparing `mobio-media-sdk-test-0.2.12/mobio/sdks/media/config.py` & `mobio-media-sdk-test-0.2.9/mobio/sdks/media/config.py`

 * *Files identical despite different names*

### Comparing `mobio-media-sdk-test-0.2.12/mobio/sdks/media/constant.py` & `mobio-media-sdk-test-0.2.9/mobio/sdks/media/constant.py`

 * *Files identical despite different names*

### Comparing `mobio-media-sdk-test-0.2.12/mobio/sdks/media/custom_mimetypes.py` & `mobio-media-sdk-test-0.2.9/mobio/sdks/media/custom_mimetypes.py`

 * *Files identical despite different names*

### Comparing `mobio-media-sdk-test-0.2.12/mobio/sdks/media/merchant_config.py` & `mobio-media-sdk-test-0.2.9/mobio/sdks/media/merchant_config.py`

 * *Files identical despite different names*

### Comparing `mobio-media-sdk-test-0.2.12/mobio/sdks/media/mobio_media_sdk.py` & `mobio-media-sdk-test-0.2.9/mobio/sdks/media/mobio_media_sdk.py`

 * *Files 1% similar despite different names*

```diff
@@ -149,15 +149,15 @@
             file_data=file_data,
             file_byte=file_byte,
             merchant_id=merchant_id,
             expire=expire
         )
 
         time_start = time.time()
-        mimetype_str = MobioMediaSDK.get_mimetype(file_path=file_path, file_data=file_data, file_byte=file_byte)
+        mimetype_str = MobioMediaSDK.get_mimetype(file_path=file_path, file_data=file_data)
         MobioMediaSDK.validate_desired_format(desired_format=desired_format, mimetype_str=mimetype_str)
         if not filename:
             filename = MobioMediaSDK.get_file_name(file_path=file_path, file_data=file_data)
         host_by_merchant_id = self._get_host_by_merchant_id(merchant_id=merchant_id)
         logger.debug("upload_without_kafka()::get_host_by_merchant_id:: %s" % (time.time() - time_start))
         dist_file, filename = self.create_dir_save_file(
             folder=STATIC_DATA_DIR,
@@ -246,15 +246,15 @@
             file_data=file_data,
             file_byte=file_byte,
             merchant_id=merchant_id,
             expire=expire
         )
 
         time_start = time.time()
-        mimetype_str = MobioMediaSDK.get_mimetype(file_path=file_path, file_data=file_data, file_byte=file_byte)
+        mimetype_str = MobioMediaSDK.get_mimetype(file_path=file_path, file_data=file_data)
         MobioMediaSDK.validate_desired_format(desired_format=desired_format, mimetype_str=mimetype_str)
         if not filename:
             filename = MobioMediaSDK.get_file_name(file_path=file_path, file_data=file_data)
 
         tmp_file, filename = self.create_dir_save_file(
             folder=APP_TMP_DATA_DIR,
             merchant_id=merchant_id,
@@ -453,24 +453,20 @@
             request_timeout=self.DEFAULT_REQUEST_TIMEOUT_SECONDS
         )
         if not host_by_merchant_id:
             return MobioEnvironment.PUBLIC_HOST
         return host_by_merchant_id
 
     @staticmethod
-    def get_mimetype(file_data, file_path, file_byte):
-        mimetype_str = None
-        if (file_path and os.path.isfile(file_path)):
+    def get_mimetype(file_data, file_path):
+        if file_path and os.path.isfile(file_path):
             magic_init = magic.Magic(mime=True)
             mimetype_str = magic_init.from_file(file_path)
-        elif file_data:
+        else:
             mimetype_str = file_data.mimetype if file_data.mimetype else file_data.content_type
-        elif file_byte:
-            magic_init = magic.Magic(mime=True)
-            mimetype_str = magic_init.from_buffer(file_byte)
         logger.info("mimetype_str:: %s" % mimetype_str)
         return mimetype_str
 
     def override_file(
             self,
             filename=None,
             merchant_id=None,
@@ -482,15 +478,15 @@
     ):
         MobioMediaSDK.valid_input_upload(
             file_path=file_path,
             file_data=file_data,
             file_byte=file_byte,
             merchant_id=merchant_id
         )
-        mimetype_str = MobioMediaSDK.get_mimetype(file_path=file_path, file_data=file_data, file_byte=file_byte)
+        mimetype_str = MobioMediaSDK.get_mimetype(file_path=file_path, file_data=file_data)
         MobioMediaSDK.validate_desired_format(desired_format=desired_format, mimetype_str=mimetype_str)
         time_start = time.time()
         # mimetype_str = self._get_mimetype(file)
         tmp_file, filename = self.create_dir_save_file(
             folder=APP_TMP_DATA_DIR,
             merchant_id=merchant_id,
             type_media=DirSaveFile.UPLOAD,
```

### Comparing `mobio-media-sdk-test-0.2.12/mobio/sdks/media/utils.py` & `mobio-media-sdk-test-0.2.9/mobio/sdks/media/utils.py`

 * *Files identical despite different names*

### Comparing `mobio-media-sdk-test-0.2.12/mobio_media_sdk_test.egg-info/PKG-INFO` & `mobio-media-sdk-test-0.2.9/mobio_media_sdk_test.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,92 +1,91 @@
 Metadata-Version: 2.1
 Name: mobio-media-sdk-test
-Version: 0.2.12
+Version: 0.2.9
 Summary: Mobio Media SDK
 Home-page: https://github.com/mobiovn
 Author: MOBIO
 Author-email: contact@mobio.vn
 License: MIT
 Project-URL: Source, https://github.com/mobiovn
+Description: ##  Thư viện Media.
+        
+        ### Cài đặt:
+        
+        ```bash
+         $ pip3 install mobio-media-sdk
+         ```
+        
+        #### Log:
+        
+        - Version: 0.1.1: Thêm mobio token.
+        - Version: 0.1.2: Add json.dums by func finish_save_file_by_filepath
+        - Version: 0.1.3: Add func get_path_by_url, get_binary_by_url
+            + Hướng dẫn sử dụng:
+                + func get_path_by_url -> kết quả trả về là path của url.
+                  ```python3
+                  from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK 
+                  MobioMediaSDK().get_path_by_url(url)
+                  ```
+                + func get_binary_by_url -> kết quả trả về là binary của url
+                  ```python3
+                  from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK 
+                  MobioMediaSDK().get_binary_by_url(url)
+                  ```
+        - Version: 0.1.4: Add func get_filename_by_url
+          + Hướng dẫn sử dụng:
+            + func get_filename_by_url -> kết quả trả về là filename của url
+              ```python3
+              from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK 
+              MobioMediaSDK().get_filename_by_url(url)
+              ```
+        - Version: 0.1.5: Delete system_config
+        - Version: 0.1.6: Rename get_local_path_by_url -> get_path_by_url
+        - Version: 0.1.7: Option read file "r" -> "rb"
+        - Version: 0.1.8: Update lại token call từ Admin
+        - Version: 0.1.9: Bổ sung tính năng:
+          - Tạo public link khi chưa có file upload.
+              ```python3
+              from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK 
+              MobioMediaSDK().create_public_url_without_file(
+                    merchant_id="merchant_id",
+                    filename="filename",
+                    mimetype_str="mimetype_str"
+              )
+          
+              result = {
+                'url': '',
+                'local_path': '',
+                'filename': ''
+              }
+              ```
+              Sau khi xử lý nghiệp vụ xong có thể dùng func sau để Lưu file được lấy path từ URL
+              ```python3
+               from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK 
+               MobioMediaSDK().finish_save_file_by_public_url(filepath="filepath", url="url")
+              ```
+          - Thêm option **file_byte** khi upload file. Option này phục vụ cho nhu cầu upload file bằng bytes.
+            
+        - Version: 0.2.0: Bổ sung option display, group_ids
+        - Version: 0.2.1: Bổ sung merchant_id
+        - Version: 0.2.2: Sửa từ get public-host từ module media sang module Admin.
+        - Version: 0.2.2 và 0.2.3: Bổ sung phần tính dung lượng file khi trả về.
+        - Version: 0.2.5: Chuyển việc lấy public-host sang admin-sdk
+        - Version: 0.2.6: Apply libs m-kafka-sdk-v2
+        - Version: 0.2.7: Bỏ m-kafka-sdk
+        - Version: 0.2.8: Fix lỗi encode url với những tên file đặc biệt
+        - Version: 0.2.9: Nâng cấp confluent_kafka
+        
 Keywords: mobio,media,upload
+Platform: UNKNOWN
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Topic :: Software Development :: Build Tools
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3 :: Only
 Requires-Python: >=3
 Description-Content-Type: text/markdown
-License-File: LICENSE
-
-##  Thư viện Media.
-
-### Cài đặt:
-
-```bash
- $ pip3 install mobio-media-sdk
- ```
-
-#### Log:
-
-- Version: 0.1.1: Thêm mobio token.
-- Version: 0.1.2: Add json.dums by func finish_save_file_by_filepath
-- Version: 0.1.3: Add func get_path_by_url, get_binary_by_url
-    + Hướng dẫn sử dụng:
-        + func get_path_by_url -> kết quả trả về là path của url.
-          ```python3
-          from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK
-          MobioMediaSDK().get_path_by_url(url)
-          ```
-        + func get_binary_by_url -> kết quả trả về là binary của url
-          ```python3
-          from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK
-          MobioMediaSDK().get_binary_by_url(url)
-          ```
-- Version: 0.1.4: Add func get_filename_by_url
-  + Hướng dẫn sử dụng:
-    + func get_filename_by_url -> kết quả trả về là filename của url
-      ```python3
-      from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK
-      MobioMediaSDK().get_filename_by_url(url)
-      ```
-- Version: 0.1.5: Delete system_config
-- Version: 0.1.6: Rename get_local_path_by_url -> get_path_by_url
-- Version: 0.1.7: Option read file "r" -> "rb"
-- Version: 0.1.8: Update lại token call từ Admin
-- Version: 0.1.9: Bổ sung tính năng:
-  - Tạo public link khi chưa có file upload.
-      ```python3
-      from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK
-      MobioMediaSDK().create_public_url_without_file(
-            merchant_id="merchant_id",
-            filename="filename",
-            mimetype_str="mimetype_str"
-      )
-
-      result = {
-        'url': '',
-        'local_path': '',
-        'filename': ''
-      }
-      ```
-      Sau khi xử lý nghiệp vụ xong có thể dùng func sau để Lưu file được lấy path từ URL
-      ```python3
-       from mobio.sdks.media.mobio_media_sdk import MobioMediaSDK
-       MobioMediaSDK().finish_save_file_by_public_url(filepath="filepath", url="url")
-      ```
-  - Thêm option **file_byte** khi upload file. Option này phục vụ cho nhu cầu upload file bằng bytes.
-
-- Version: 0.2.0: Bổ sung option display, group_ids
-- Version: 0.2.1: Bổ sung merchant_id
-- Version: 0.2.2: Sửa từ get public-host từ module media sang module Admin.
-- Version: 0.2.2 và 0.2.3: Bổ sung phần tính dung lượng file khi trả về.
-- Version: 0.2.5: Chuyển việc lấy public-host sang admin-sdk
-- Version: 0.2.6: Apply libs m-kafka-sdk-v2
-- Version: 0.2.7: Bỏ m-kafka-sdk
-- Version: 0.2.8: Fix lỗi encode url với những tên file đặc biệt
-- Version: 0.2.9: Nâng cấp confluent_kafka
-- Version: 0.2.10: Thêm get mimetype file_byte
```

### Comparing `mobio-media-sdk-test-0.2.12/mobio_media_sdk_test.egg-info/SOURCES.txt` & `mobio-media-sdk-test-0.2.9/mobio_media_sdk_test.egg-info/SOURCES.txt`

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,7 @@
-LICENSE
 README.md
 pyproject.toml
 setup.cfg
 setup.py
 mobio/sdks/media/__init__.py
 mobio/sdks/media/config.py
 mobio/sdks/media/constant.py
```

### Comparing `mobio-media-sdk-test-0.2.12/setup.py` & `mobio-media-sdk-test-0.2.9/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from setuptools import find_namespace_packages, setup
 
 
 class Readme(object):
-    __readme_path = "README.md"
+    __readme_path = "README_NEW.md"
 
     @staticmethod
     def get():
         """get content README.md
         :param filename:
         :return:
         """
@@ -24,16 +24,16 @@
         :param filename:
         :return:
         """
         requirements = ["m-singleton", "Werkzeug", "Flask", "m-caching", "requests", "confluent_kafka==1.7.0", "python-magic", "mobio-admin-sdk"]
         return requirements
 
 
-version_dev='0.2.12'  # Giữ nguyên định dạng không được format file có khoảng trống theo Pycharm (version_dev = '1.0.9' là file run.sh sẽ không bắt được current_version)
-version_prod='0.2.11'  # Giữ nguyên định dạng không được format file có khoảng trống theo Pycharm (version_dev = '1.0.9' là file run.sh sẽ không bắt được current_version)
+version_dev='0.2.9'  # Giữ nguyên định dạng không được format file có khoảng trống theo Pycharm (version_dev = '1.0.9' là file run.sh sẽ không bắt được current_version)
+version_prod='0.2.8'  # Giữ nguyên định dạng không được format file có khoảng trống theo Pycharm (version_dev = '1.0.9' là file run.sh sẽ không bắt được current_version)
 
 run_mode='-test'
 
 setup(
     # This is the name of your project. The first time you publish this
     # package, this name will be registered for you. It will determine how
     # users can install this project, e.g.:
@@ -48,15 +48,15 @@
     name="mobio-media-sdk" + run_mode,  # Required
     # Versions should comply with PEP 440:
     # https://www.python.org/dev/peps/pep-0440/
     #
     # For a discussion on single-sourcing the version across setup.py and the
     # project code, see
     # https://packaging.python.org/en/latest/single_source_version.html
-    version='0.2.12',  # Required, Phần này cũng không được format file.
+    version='0.2.9',  # Required, Phần này cũng không được format file.
     # This is a one-line description or tagline of what your project does. This
     # corresponds to the "Summary" metadata field:
     # https://packaging.python.org/specifications/core-metadata/#summary
     description="Mobio Media SDK",  # Optional
     # This is an optional longer description of your project that represents
     # the body of text which users will see when they visit PyPI.
     #
```

